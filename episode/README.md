# GraphQL Episode Query Example

This directory contains example GraphQL queries and their expected outputs for fetching episode details by ID.

## Instructions

Each `.graphql` file contains a query to fetch an episode by a specific ID using the `episode(id: ID!)` field. The following fields are included in each query:
- id
- name
- air_date
- episode

Each `.json` file contains the expected output for the corresponding query.

## Example Query

```
query {
  episode(id: 1) {
    id
    name
    air_date
    episode
  }
}
```
