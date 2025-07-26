# AWS-Identity-Center-Setup-and-Access-Management

## Overview
This repository documents the process of setting up an AWS account and configuring AWS Identity Center for centralized access management and role-based user permissions.

## AWS Account Setup
I successfully created a new AWS (Amazon Web Services) account to enable access to cloud computing resources and services. The process involved:
- Registering on the AWS website using a valid email address.
- Providing billing information.
- Verifying identity through SMS.
- Selecting the free Basic Support Plan.

This foundational setup prepared the account for secure cloud resource management and further configuration.

![AWS Account Set Up](./Screenshots/AWS%20Account%20Set%20up.png)

## AWS Identity Center Configuration
After setting up the account, I configured AWS Identity Center as the central identity management hub. Key steps included:
- Activating Identity Center.
- Creating a new instance to manage users and permissions.

![Identity Center Instance](./Screenshots/Identity%20Center%20Instance.png)

## Users and Groups Created
To implement role-based access control, I:
- Created two groups:
  - **Development Team**
  - **Strategy Team**
- Added two users and assigned each to the appropriate group.

![Users Created](./Screenshots/Users%20Created.png)

## Permission Sets
Custom permission sets were defined based on team roles:
- **Development Team:** Granted permissions to build, deploy, and manage AWS resources.
- **Strategy Team:** Assigned read-only access for viewing reports, dashboards, and analytics.

This structure supports **secure, scalable, and organized** access control aligned with AWS best practices.

![Permissions Set](./Screenshots/Permissions%20Set.png)

## Screenshots
Screenshots of the configuration process are included in the [`/Screenshots`](./Screenshots/) folder to demonstrate:
- AWS Account Set up
- Identity Center activation
- Group and user creation
- Permission assignments

## Outcome
The setup ensures a secure, role-based identity and access management environment suitable for team collaboration and resource governance in AWS.
