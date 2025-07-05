# Character Queries - GraphQL Practice

This directory contains GraphQL queries and output results for retrieving character information using two different GraphQL fields:

1. `character(id: ID!)` – retrieves a single character by ID
2. `characters(page: Int)` – retrieves a list of characters by page

---

## 1️⃣ Single Character Queries (By ID)

Each GraphQL query retrieves the following fields:

- id
- name
- status
- species
- type
- gender

### Files

- `character-id-1.graphql` & `character-id-1-output.json`
- `character-id-2.graphql` & `character-id-2-output.json`
- `character-id-3.graphql` & `character-id-3-output.json`
- `character-id-4.graphql` & `character-id-4-output.json`

These queries use IDs 1 through 4 respectively.

---

## 2️⃣ Multiple Characters Queries (By Page)

Each GraphQL query retrieves a list of characters from a given page and includes the following fields:

- id
- name
- status
- image

### Files

- `characters-page-1.graphql` & `characters-page-1-output.json`
- `characters-page-2.graphql` & `characters-page-2-output.json`
- `characters-page-3.graphql` & `characters-page-3-output.json`
- `characters-page-4.graphql` & `characters-page-4-output.json`

These queries use page numbers 1 through 4 respectively.

---

## API Used

All queries were run against the [Rick and Morty GraphQL API](https://rickandmortyapi.com/graphql).
