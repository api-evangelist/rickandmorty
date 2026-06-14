# Rick and Morty GraphQL API

The Rick and Morty GraphQL API provides a flexible query interface for accessing data from the Rick and Morty animated series. It exposes three core data types — Character, Location, and Episode — and supports fetching individual records by ID, paginated lists with optional filtering, and batch lookups by multiple IDs. The API is completely free, requires no authentication, and is backed by data covering 826 characters, 126 locations, and 51 episodes.

The schema defines a read-only Query type (no mutations or subscriptions). Paginated list queries return a wrapper type (Characters, Locations, Episodes) that includes an Info object with pagination metadata (count, pages, next, prev) alongside the results array. Filtering is supported via dedicated input types (FilterCharacter, FilterLocation, FilterEpisode) that allow narrowing results by name, status, species, type, gender, dimension, or episode code.

The GraphQL endpoint is served publicly at https://rickandmortyapi.com/graphql and is accessible directly from a browser or any GraphQL client. The source code, including the full type definitions, is open source and maintained at https://github.com/afuh/rick-and-morty-api.

**Endpoint:** https://rickandmortyapi.com/graphql

**Documentation:** https://rickandmortyapi.com/documentation#graphql

**References:**

- Documentation: https://rickandmortyapi.com/documentation#graphql
- GettingStarted: https://rickandmortyapi.com/documentation
- Reference: https://github.com/afuh/rick-and-morty-api/blob/master/graphql/typeDefs.js
