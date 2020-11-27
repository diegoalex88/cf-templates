# cf-templates
Templates for AWS Cloudformation

## iam-role-cross-account-administrator-simple
This Cloudformation template make a role for users in another account makes "switch role" by sts:assumerole with policy AdministratorAccess.

*You set the parameters:*

**SourceAccountId:** [12 digit id of the account containing the users to which you're granting access]

**RoleName:** [Set the role name to make Switch Role and granting access]
