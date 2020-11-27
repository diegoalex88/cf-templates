# cf-templates
Templates for AWS Cloudformation

## iam-role-cross-account-administrator-simple
This Cloudformation template creates an AWS IAM Role for users in the Source/Administrative account perform the "switch role" action by the API [sts:assumerole](https://docs.aws.amazon.com/STS/latest/APIReference/API_AssumeRole.html) with policy AdministratorAccess in the destination account.

*Required parameters:*

**SourceAccountId:** [12 digit id of the account containing the users to which you're granting access]

**RoleName:** [Set the role name to execute Switch Role and granting access]
