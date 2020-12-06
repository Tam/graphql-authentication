# GraphQL Authentication plugin for Craft CMS 3.5+

GraphQL Authentication adds a JWT authentication layer to your Craft CMS GraphQL endpoint.

## Plugin Overview

- Adds support for user registration and authentication (see [Authentication](/usage/authentication))
- Adds support for social sign-in – currently Google, Facebook and Twitter (see [Social](/usage/social))
- Adds ability to define per-section user restrictions (queries and mutations can be limited to author-only) (see [User Settings](/settings/users))
- Checks mutation fields against schema permissions, and prevents fields being saved if user is trying to access private entries/assets
- Adds ability to assign unique GraphQL schemas for each user group
- Adds a unique, per-user GraphQL query cache

## Documentation

You can view the documention for the plugin [here](https://graphql-authentication.jamesedmonston.co.uk).
