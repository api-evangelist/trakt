# Trakt (trakt)

Trakt is the personal media database for movies and TV. Its API v2 (api.trakt.tv) exposes ~150 endpoints across movies, shows, seasons, episodes, people, search, lists, calendars, recommendations, comments, notes, scrobble, checkin, and full per-user sync. Authentication is OAuth 2.0 via Authorization Code or Device flows.

- **APIs.yml:** [apis.yml](apis.yml)
- **x-type:** company
- **x-tier:** 2 (full pipeline enrichment 2026-05-30)
- **Source:** [public-apis/public-apis](https://github.com/public-apis/public-apis) — Video category

## API

- **Trakt API v2** — base `https://api.trakt.tv` — [Documentation](https://trakt.docs.apiary.io/) — [OpenAPI](openapi/trakt-openapi.yml)

## Authentication

OAuth 2.0. Two flows:

- **Authorization Code** — `/oauth/token` for web/server apps.
- **Device Code** — `/oauth/device/code` then poll `/oauth/device/token` for TV / console / CLI apps.

All requests require these headers:

| Header | Value |
| --- | --- |
| `Content-Type` | `application/json` |
| `trakt-api-version` | `2` |
| `trakt-api-key` | `{client_id}` |
| `Authorization` | `Bearer {access_token}` (when calling authenticated endpoints) |

## Surface (representative)

Tags exposed in the OpenAPI: OAuth, Movies, Shows, Seasons, Episodes, People, Search, Users, Sync, Scrobble, Checkin, Lists, Calendars, Recommendations, Comments, Notes, Certifications, Countries, Languages, Genres, Networks, Studios.

## Artifacts

| Folder | Purpose | Count |
| --- | --- | --- |
| `openapi/` | OpenAPI 3.0.3 spec for the Trakt API v2 | 1 |
| `examples/` | Operation request/response examples | 8 |
| `json-schema/` | JSON Schema for Movie, Show, Episode, User, Scrobble | 5 |
| `json-structure/` | Field-group structure docs | 3 |
| `json-ld/` | JSON-LD context aligned to schema.org | 1 |
| `rules/` | Spectral ruleset enforcing Trakt conventions | 1 |
| `capabilities/` | Naftiko shared + workflow capabilities | 6 |
| `vocabulary/` | Trakt domain vocabulary | 1 |
| `plans/` | API Commons Plans 0.1 (Free / VIP / VIP EP / commercial) | 1 |
| `rate-limits/` | API Commons Rate Limits 0.1 | 1 |
| `finops/` | FOCUS-aligned billing surface | 1 |

## Capabilities

- `capabilities/shared/trakt-shared.yaml` — base primitives reused everywhere.
- `capabilities/personal-media-tracking.yaml` — OAuth + sync + report current state.
- `capabilities/media-center-scrobbling.yaml` — scrobble lifecycle with 80% / dedupe semantics.
- `capabilities/list-curation.yaml` — watchlist, favorites, custom lists, VIP-aware limits.
- `capabilities/discovery-and-recommendations.yaml` — trending + calendar + per-user recs.
- `capabilities/social-engagement.yaml` — follow graph, comments, checkins.

## Pricing

- **Free** — full API access bound by personal account limits (2026 update: 250 watchlist, 5 lists, 100k history, 10k ratings, 100 notes).
- **Trakt VIP** — $30 first year / $60 renewal — higher limits, watchlist notes, year-in-review, no ads.
- **Trakt VIP EP** — $1500 lifetime.
- **Commercial use** — approval-required; contact support via the Trakt forums.

See [plans/trakt-plans-pricing.yml](plans/trakt-plans-pricing.yml).

## Rate Limits

Trakt uses adaptive throttling per `client_id` + per access token. Always poll device tokens at the returned `interval` and use `/sync/last_activities` to avoid wasted refreshes. See [rate-limits/trakt-rate-limits.yml](rate-limits/trakt-rate-limits.yml).

## SDKs & Tools

Official: `trakt/trakt-api` (TypeScript/Deno), `trakt/trakt-android`, `trakt/trakt-apple`, `trakt/Plex-Trakt-Scrobbler`, `trakt/showly`, `trakt/trakt-web`, `trakt/discord-presence`.

Community: `moogar0880/PyTrakt`, `Bogstag/oauth2-trakt`, Auth.js Trakt provider.

## MCP Servers (community)

- `kud/mcp-trakt` — 36 tools for TV/movie tracking, sync, ratings, watchlists, checkins.
- `kofort9/trakt-mcp-go` — Go MCP server.
- `fab-codes/trakt-mcp-server`
- `phhusson/trakt-mcp-server`
- `popcornemil/trakt-mcp`
- `pipeworx-io/mcp-trakt`

No first-party MCP server or Claude Code skills from Trakt have been published as of 2026-05-30.

## Tags

Video, Movies, Television, Media Tracking, Scrobble, Recommendations, Social, OAuth2, Public APIs

## Timestamps

- **Created:** 2026-05-28
- **Modified:** 2026-05-30

## Maintainers

- **Kin Lane** — kin@apievangelist.com
