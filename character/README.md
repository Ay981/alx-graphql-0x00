# GraphQL Character Query Examples

This directory contains example GraphQL queries and their expected outputs for fetching character details by ID.

## Instructions

Each `.graphql` file contains a query to fetch a character by a specific ID (1, 2, 3, 4) using the `character(id: ID!)` field. The following fields are included in each query:
- id
- name
- status
- species
- type
- gender

Each `.json` file contains the expected output for the corresponding query.

## Example Query

```
query {
  character(id: 1) {
    id
    name
    status
    species
    type
    gender
  }
}
```

Replace the `id` value for other queries as needed.
