# Rick and Morty API

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
