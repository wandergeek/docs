---
keywords: docs, tutorials, 2fa
---

# Enforce two-factor authentication (2FA)

Two-factor authentication can be enforced for the whole organization to ensure
that all users who access the organization have two-factor authentication enabled.

## Before enforcing two-factor authentication

Before you enforce two-factor authentication (2FA) for your organization, consider
that users without 2FA enabled will immediately lose access to the organization
and subsequent pipelines.

Users can set up 2FA by following the [2FA tutorial].

## Steps to enforce two-factor authentication

To enforce 2FA:

1. Ensure you are logged in as an Administrator.
1. Visit your organization's [**Settings** > **Security**](https://buildkite.com/organizations/~/security) page.
1. Check **Enforce two-factor authentication**.
1. Select **Update Access Control**.

## Programmatically enforcing two-factor authentication

Please review the GraphQL [cookbook] for instructions on how to enable
enforced 2FA via the GraphQL API.

[cookbook]: </docs/apis/graphql/cookbooks/organizations#enforce-two-factor-authentication-2fa-for-your-organization>
[2FA tutorial]: </docs/platform/tutorials/2fa>
