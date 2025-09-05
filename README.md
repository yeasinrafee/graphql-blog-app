# Blog App GraphQL

## Requirement

- user can post and publish blog content
- user can see post
- authentication system
- user can see their own profile

## Tables

- post

  - id
  - title
  - content
  - authorId
  - createdAt
  - updatedAt
  - published
  - publishedAt

- user

  - id
  - name
  - email
  - password
  - createdAt
  - updatedAt
  - profile

- profile
  - id
  - bio
  - createdAt
  - updatedAt
  - userId

## Technology Stack

    - graphql
    - typescript
    - postgresql
    - prisma
