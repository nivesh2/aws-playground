# Lab

In this lab, we discover how security policies affect IAM users and groups, and we go further by implementing our own policies while also learning what a role is, how to create a role, and how to assume a role as a different user.

## Learning Objectives

### Create the Correct S3 Restricted Policies and Roles
    Perform the following tasks:

    1. Create the S3RestrictedPolicy IAM policy.
    2. Create the S3RestrictedRole IAM role.
    3. Revoke the S3 Administrator Access access policy to the dev1 user.
    4. Attach the S3RestrictedPolicy to the dev1 user.


### Configure IAM So the dev3 User Can Assume the Role
    Perform the following tasks:

    1. Create the AssumeS3Policy IAM policy.
    2. Attach the AssumeS3Policy to the dev3 user.
    3. Assume the S3RestrictedRole as the dev3 user.