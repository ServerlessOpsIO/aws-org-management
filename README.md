# aws-org-management

AWS organization management

This repository provides resources in the form of CloudFormation templates for managing the ServerlessOps AWS organization and Cloudformation StackSets for providing baseline configuration to the accounts within it. This repository does not cover the entirety of account baseline configuration. Certain larger and more complex configuration, eg. GitHub Actions and Datadog integration, are managed in separate repositories.

_*NOTE: This repository is not meant for general usage and is instead provided publicly as a reference for others.*_

## Features
These are features handled by this repository:

* Manage AWS organization OU structure
* Configuring top-level DNS zones
* Configure billing alarms in all accounts