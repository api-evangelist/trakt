# Trakt (trakt)

Trakt is the personal media database for movies and TV. Its API v2 (api.trakt.tv) exposes ~150 endpoints across movies, shows, seasons, episodes, people, search, lists, calendars, recommendations, comments, notes, scrobble, checkin, and full per-user sync (history, watchlist, ratings, collection, favorites, playback progress). Authentication is OAuth 2.0 via Authorization Code or Device flows. The platform powers the Trakt website, official Android/iOS apps, and a large third-party ecosystem of media-center plugins and trackers.

**APIs.json:** [https://trakt.tv](https://trakt.tv)

## Tags

- Video
- Movies
- Television
- Media Tracking
- Scrobble
- Recommendations
- Social
- OAuth2
- Public APIs

## Timestamps

- **Created:** 2026-05-28
- **Modified:** 2026-05-30

## APIs

### Trakt API v2

RESTful JSON API for the full Trakt platform. Supports OAuth 2.0 Authorization Code and Device flows, Title-Case operation summaries, and standard pagination (page/limit). All requests require headers trakt-api-version=2 and trakt-api-key={client_id}.

- **Human URL:** [https://trakt.docs.apiary.io/](https://trakt.docs.apiary.io/)
- **Base URL:** `https://api.trakt.tv`

#### Tags

- Video
- Movies
- Television
- Sync
- Scrobble

#### Properties

- [Documentation](https://trakt.docs.apiary.io/)
- [OpenAPI](openapi/trakt-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/trakt.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/trakt.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/trakt-movie-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/trakt-show-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/trakt-episode-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/trakt-user-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/trakt-scrobble-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/trakt-movie-structure.json)
- [JSON Structure](json-structure/trakt-show-structure.json)
- [JSON Structure](json-structure/trakt-history-structure.json)
- [Example](examples/trakt-getTrendingMovies-example.json)
- [Example](examples/trakt-getMovie-example.json)
- [Example](examples/trakt-generateDeviceCode-example.json)
- [Example](examples/trakt-pollDeviceToken-example.json)
- [Example](examples/trakt-scrobbleStart-example.json)
- [Example](examples/trakt-addToHistory-example.json)
- [Example](examples/trakt-searchText-example.json)
- [Example](examples/trakt-getShowWatchedProgress-example.json)
- [Authentication](https://trakt.docs.apiary.io/#reference/authentication-oauth)
- [API Reference](https://trakt.docs.apiary.io/)

## Common Properties

- [Website](https://trakt.tv)
- [Developer Portal](https://trakt.tv/oauth/applications)
- [Documentation](https://trakt.docs.apiary.io/)
- [Sign Up](https://trakt.tv/auth/join)
- [Pricing](https://trakt.tv/vip)
- [Plans](plans/trakt-plans-pricing.yml)
- [Rate Limits](rate-limits/trakt-rate-limits.yml)
- [Terms of Service](https://trakt.tv/terms)
- [Privacy Policy](https://trakt.tv/privacy)
- [Support](https://forums.trakt.tv)
- [F A Q](https://forums.trakt.tv/c/questions-help/8)
- [Blog](https://blog.trakt.tv)
- [Status Page](https://status.trakt.tv)
- [Changelog](https://forums.trakt.tv/c/announcements/3)
- [GitHub Organization](https://github.com/trakt)
- [GitHub Repository](https://github.com/trakt/trakt-api)
- [Spectral Rules](rules/trakt-rules.yml)
- [J S O N- L D](json-ld/trakt-context.jsonld)
- [Vocabulary](vocabulary/trakt-vocabulary.yml)
- [Resources](finops/trakt-finops.yml)
- [SDK](https://github.com/trakt/trakt-api)
- [SDK](https://github.com/moogar0880/PyTrakt)
- [SDK](https://github.com/trakt/nodeless-trakt)
- [SDK](https://github.com/Bogstag/oauth2-trakt)
- [SDK](https://authjs.dev/reference/core/providers/trakt)
- [Tools](https://github.com/trakt/trakt-android)
- [Tools](https://github.com/trakt/trakt-apple)
- [Tools](https://github.com/trakt/trakt-rippple)
- [Tools](https://github.com/trakt/Plex-Trakt-Scrobbler)
- [Tools](https://github.com/trakt/showly)
- [Tools](https://github.com/trakt/trakt-web)
- [Tools](https://github.com/trakt/discord-presence)
- [Tools](https://github.com/kud/mcp-trakt)
- [Tools](https://github.com/kofort9/trakt-mcp-go)
- [Tools](https://github.com/fab-codes/trakt-mcp-server)
- [Tools](https://github.com/phhusson/trakt-mcp-server)
- [Tools](https://github.com/popcornemil/trakt-mcp)
- [Tools](https://github.com/pipeworx-io/mcp-trakt)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)
- [Solutions](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
