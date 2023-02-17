## IAM
- Global Service
- Every AWS accunt has its own IAM and it trusts IAM completely
- No additional Cost
- Allows Identify Federation and MFA

#### Functions of IAM
- Identity Provider (IDP)
- Authenticate Identities
- Authorize (Allow/Deny)

#### IAM identity object types
- users -  Humans/Apps - used when Identifiable
- groups - Collection of users
- role - Used by AWS services (eg: EC2 to access S3) or for allowing external access to the account - used when number of things is uncertain.\

A policy (only) when attached to user/group/role - allow/deny access rights to AWS services
