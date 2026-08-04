# Rick and Morty API

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Free REST and GraphQL API providing data about characters, locations, and episodes from the Rick and Morty animated series.

**Base URL:** https://rickandmortyapi.com/api  
**GraphQL:** https://rickandmortyapi.com/graphql  
**Documentation:** https://rickandmortyapi.com/documentation  
**Status:** https://status.rickandmortyapi.com  
**Source:** https://github.com/afuh/rick-and-morty-api  

## Overview

The Rick and Morty API is an open source project maintained by Axel Fuhrmann. It provides programmatic access to data from the animated television series including 826 characters, 126 locations, and 51 episodes. No authentication is required.

## Resources

- **Characters** — `/api/character` — Filter by name, status, species, type, gender
- **Locations** — `/api/location` — Filter by name, type, dimension
- **Episodes** — `/api/episode` — Filter by name, episode code

## APIs.json

This repository contains an [APIs.json](apis.yml) profile for the Rick and Morty API catalogued under the [api-evangelist](https://github.com/api-evangelist) organization.

| File | Description |
|------|-------------|
| [apis.yml](apis.yml) | APIs.json 0.19 provider profile |
| [plans/rickandmorty-plans-pricing.yml](plans/rickandmorty-plans-pricing.yml) | Pricing and plan details (free) |
| [rate-limits/rickandmorty-rate-limits.yml](rate-limits/rickandmorty-rate-limits.yml) | Rate limit details (10,000 req/day/IP) |
| [finops/rickandmorty-finops.yml](finops/rickandmorty-finops.yml) | FinOps considerations for consumers |

## License

The Rick and Morty API source is licensed under the BSD-3-Clause License. This catalog profile is maintained by [Kin Lane](mailto:kin@apievangelist.com).
