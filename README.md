# cf-templates
Templates for AWS Cloudformation

## iam-role-cross-account-administrator-simple
This Cloudformation template creates an AWS IAM Role for users in the Source/Administrative account perform the "switch role" action by the API sts:assumerole with policy AdministratorAccess in the Destination account.

*Required parameters:*

**SourceAccountId:** [12 digit id of the account containing the users to which you're granting access]

**RoleName:** [Set the role name to make Switch Role and granting access]
