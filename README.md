# Trakt

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

**Areas:** Video · Movies · Television · Media Tracking · Scrobble · Recommendations · Social · Authentication · Public APIs

## Trakt on APIs.io

Everything profiled for Trakt is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/trakt/](https://apis.io/providers/trakt/)** — or go straight to one of the APIs or properties below.

### APIs (22)

- [Trakt Calendars API](https://apis.io/apis/trakt/trakt-calendars-api/) — Upcoming and recently aired schedules for shows, episodes, and movies.
- [Trakt Certifications API](https://apis.io/apis/trakt/trakt-certifications-api/) — Movie and show certification reference data.
- [Trakt Comments API](https://apis.io/apis/trakt/trakt-comments-api/) — Comment threads, replies, likes, reactions.
- [Trakt Countries API](https://apis.io/apis/trakt/trakt-countries-api/) — Country reference data.
- [Trakt Episodes API](https://apis.io/apis/trakt/trakt-episodes-api/) — Episode metadata, ratings, comments, watching.
- [Trakt Genres API](https://apis.io/apis/trakt/trakt-genres-api/) — Genre reference data.
- [Trakt Languages API](https://apis.io/apis/trakt/trakt-languages-api/) — Language reference data.
- [Trakt Lists API](https://apis.io/apis/trakt/trakt-lists-api/) — Trending, popular, and personal lists.
- [Trakt Movies API](https://apis.io/apis/trakt/trakt-movies-api/) — Movie metadata, trending, watched, anticipated, popular, ratings, related, people.
- [Trakt Networks API](https://apis.io/apis/trakt/trakt-networks-api/) — Television network reference data.
- [Trakt Notes API](https://apis.io/apis/trakt/trakt-notes-api/) — Personal notes attached to media items.
- [Trakt People API](https://apis.io/apis/trakt/trakt-people-api/) — Person metadata, filmography, lists.
- [Trakt Recommendations API](https://apis.io/apis/trakt/trakt-recommendations-api/) — Personalized recommendations for movies and shows.
- [Trakt Scrobble API](https://apis.io/apis/trakt/trakt-scrobble-api/) — Start, pause, and stop scrobbles for movies and episodes.
- [Trakt Search API](https://apis.io/apis/trakt/trakt-search-api/) — Text and ID lookup across movies, shows, episodes, people, lists.
- [Trakt Seasons API](https://apis.io/apis/trakt/trakt-seasons-api/) — Season-level metadata and episodes.
- [Trakt Shows API](https://apis.io/apis/trakt/trakt-shows-api/) — Show metadata, trending, watched, anticipated, popular, progress, seasons, episodes.
- [Trakt Studios API](https://apis.io/apis/trakt/trakt-studios-api/) — Studio reference data.
- [Trakt Sync API](https://apis.io/apis/trakt/trakt-sync-api/) — History, watchlist, ratings, favorites, collection, playback progress.
- [Trakt Users API](https://apis.io/apis/trakt/trakt-users-api/) — Profiles, settings, follows, friends, social activity, comments, watching.
- [Trakt O Auth API](https://apis.io/apis/trakt/trakt-oauth-api/) — Authorization Code and Device OAuth flows.
- [Trakt Check In API](https://apis.io/apis/trakt/trakt-check-in-api/) — Lightweight social "now watching" check-ins.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Trakt Agentic Access](https://apis.io/agentic-access/trakt/trakt-agentic-access/)

#### JSON Schema (5)

The data models the API reads and writes.

- [Trakt Episode](https://apis.io/schemas/trakt/trakt-episode/)
- [Trakt Movie](https://apis.io/schemas/trakt/trakt-movie/)
- [Trakt Scrobble Event](https://apis.io/schemas/trakt/trakt-scrobble/)
- [Trakt Show](https://apis.io/schemas/trakt/trakt-show/)
- [Trakt User Profile](https://apis.io/schemas/trakt/trakt-user/)

#### JSON Structure (3)

Data models expressed in JSON Structure.

- [Trakt History Structure](https://apis.io/json-structure/trakt/trakt-history-structure/)
- [Trakt Movie Structure](https://apis.io/json-structure/trakt/trakt-movie-structure/)
- [Trakt Show Structure](https://apis.io/json-structure/trakt/trakt-show-structure/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Trakt Context](https://apis.io/jsonld/trakt/trakt-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [Trakt Vocabulary](https://apis.io/vocabularies/trakt/trakt-vocabulary/)

#### Examples (8)

Example requests and responses.

- [Trakt Addtohistory Example](https://apis.io/examples/trakt/trakt-addToHistory-example/)
- [Trakt Generatedevicecode Example](https://apis.io/examples/trakt/trakt-generateDeviceCode-example/)
- [Trakt Getmovie Example](https://apis.io/examples/trakt/trakt-getMovie-example/)
- [Trakt Getshowwatchedprogress Example](https://apis.io/examples/trakt/trakt-getShowWatchedProgress-example/)
- [Trakt Gettrendingmovies Example](https://apis.io/examples/trakt/trakt-getTrendingMovies-example/)
- [Trakt Polldevicetoken Example](https://apis.io/examples/trakt/trakt-pollDeviceToken-example/)
- [Trakt Scrobblestart Example](https://apis.io/examples/trakt/trakt-scrobbleStart-example/)
- [Trakt Searchtext Example](https://apis.io/examples/trakt/trakt-searchText-example/)

#### Collections (45)

Postman and Open Collection request collections.

- [Trakt API](https://apis.io/collections/trakt/open-trakt/)
- [Trakt Calendars API](https://apis.io/collections/trakt/open-trakt-calendars-api/)
- [Trakt Calendars Certifications API](https://apis.io/collections/trakt/open-trakt-certifications-api/)
- [Trakt Calendars Checkin API](https://apis.io/collections/trakt/open-trakt-checkin-api/)
- [Trakt Calendars Comments API](https://apis.io/collections/trakt/open-trakt-comments-api/)
- [Trakt Calendars Countries API](https://apis.io/collections/trakt/open-trakt-countries-api/)
- [Trakt Calendars Episodes API](https://apis.io/collections/trakt/open-trakt-episodes-api/)
- [Trakt Calendars Genres API](https://apis.io/collections/trakt/open-trakt-genres-api/)
- [Trakt Calendars Languages API](https://apis.io/collections/trakt/open-trakt-languages-api/)
- [Trakt Calendars Lists API](https://apis.io/collections/trakt/open-trakt-lists-api/)
- [Trakt Calendars Movies API](https://apis.io/collections/trakt/open-trakt-movies-api/)
- [Trakt Calendars Networks API](https://apis.io/collections/trakt/open-trakt-networks-api/)
- [Trakt Calendars Notes API](https://apis.io/collections/trakt/open-trakt-notes-api/)
- [Trakt Calendars OAuth API](https://apis.io/collections/trakt/open-trakt-oauth-api/)
- [Trakt Calendars People API](https://apis.io/collections/trakt/open-trakt-people-api/)
- [Trakt Calendars Recommendations API](https://apis.io/collections/trakt/open-trakt-recommendations-api/)
- [Trakt Calendars Scrobble API](https://apis.io/collections/trakt/open-trakt-scrobble-api/)
- [Trakt Calendars Search API](https://apis.io/collections/trakt/open-trakt-search-api/)
- [Trakt Calendars Seasons API](https://apis.io/collections/trakt/open-trakt-seasons-api/)
- [Trakt Calendars Shows API](https://apis.io/collections/trakt/open-trakt-shows-api/)
- [Trakt Calendars Studios API](https://apis.io/collections/trakt/open-trakt-studios-api/)
- [Trakt Calendars Sync API](https://apis.io/collections/trakt/open-trakt-sync-api/)
- [Trakt Calendars Users API](https://apis.io/collections/trakt/open-trakt-users-api/)
- [Trakt Calendars API](https://apis.io/collections/trakt/postman-trakt-calendars-api/)
- [Trakt Calendars Certifications API](https://apis.io/collections/trakt/postman-trakt-certifications-api/)
- …and 20 more published on APIs.io

#### Governance rules (2)

Spectral rulesets for the provider's contracts.

- [Trakt — jsonschema rules](https://apis.io/rules/trakt/trakt-jsonschema-spectral-rules/)
- [Trakt API Rules](https://apis.io/rules/trakt/trakt-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Trakt Authentication](https://apis.io/security/trakt/trakt-authentication/)
- [Trakt Domain Security](https://apis.io/security/trakt/trakt-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Trakt Plans Pricing](https://apis.io/plans/trakt/trakt-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Trakt Rate Limits](https://apis.io/rate-limits/trakt/trakt-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Trakt Finops](https://apis.io/finops/trakt/trakt-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://trakt.tv)
- [Documentation](https://trakt.docs.apiary.io/)
- [Pricing](https://trakt.tv/vip)
- [Support](https://forums.trakt.tv)
- [Changelog](https://forums.trakt.tv/c/announcements/3)
- [Blog](https://blog.trakt.tv)
- [Terms of service](https://trakt.tv/terms)
- [Privacy policy](https://trakt.tv/privacy)
- [GitHub](https://github.com/trakt)
- [Status](https://status.trakt.tv)

## API Evangelist rating

**Kin Score 49.0** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 73.2 |
| Contract quality | 62.0 |
| Contract governance | 27.3 |
| Operational transparency | 23.7 |
| Developer ergonomics | 47.6 |
| Access clarity | 52.6 |

**Agent readiness 21.9** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | documented (partial credit) |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | partial |
| Operation Distinctiveness | distinct |

**Regulatory alignment 24.5** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/trakt/](https://apis.io/providers/trakt/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Trakt: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/trakt/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
