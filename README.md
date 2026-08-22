# Trakt (trakt)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
