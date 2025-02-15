# Changelog

## [1.0.0] - 2021-05-04

### Added
* Assisted Log Enabler for AWS
    * Main file
    * Subfuction files
    * Diagram files
    * LICENSE file
    * README file
    * NOTICE file
    * THIRD-PARTY file
    * CODE_OF_CONDUCT file
    * CONTRIBUTING file

## [1.0.1] - 2021-05-04

### Added
* PutPublicAccessBlock for Amazon S3 bucket created (single-account version).
* Step-by-step instructions for running Assisted Log Enabler for AWS in single-account mode using AWS CloudShell within the README file.

## [1.0.2] - 2021-05-04

### Added
* Error handling for AWS Organizations API call within multi-account version.

## [1.1.0] - 2021-05-11

### Added
* Route 53 Resolver Query Logging for single-account mode.

### Fixed
* Issue with Amazon S3 bucket creation.

### Changed
* IAM Permissions examples.
* Diagram to reflect Route 53 Resolver Query Logging.
* Diagram to correctly reflect Amazon EKS Audit & Authentication logs going to AWS CloudWatch.
* AWS CloudFormation template for deploying multi-account IAM roles.
* README documentation.

## [1.1.1] - 2021-05-14

### Added
* Multi-Account support for Route 53 Resolver Query Logging.
* Multi-Account support for Amazon EKS Audit & Authenticator Logs.
* Step-by-step instructions for running Assisted Log Enabler for AWS in multi-account mode using AWS CloudShell within the README file.

### Fixed
* Issue with log file output.

### Changed
* IAM Permissions examples.
* AWS CloudFormation template.

## [1.1.2] - 2021-05-17

### Added
* PutPublicAccessBlock for Amazon S3 bucket created (multi-account version).

### Changed
* Updates to IAM Permissions examples.
    * Added examples for both single account and multi-account.
* README documentation.

## [1.1.3] - 2021-05-18

### Fixed
* Documentation details about iam:CreateServiceLinkedRole.

## [1.1.4] - 2021-05-25

### Added
* Cleanup details in the README file.
* Cost details in the README file.

## [1.1.5] - 2021-06-04

### Added
* ap-northeast-3 Osaka to function code.

### Changed
* Log output file name to show clear date.
* Datetime output to show UTC time explicitly.
* README documentation.

## [1.2.0] - 2021-06-21

### Added
* Options for running the code for individual supported AWS services.
    * Maintained the ability to run for all services currently supported at once.
    * Documentation to reflect new supported commands.

### Changed
* README documentation.

## [1.2.1] - 2021-06-29

### Added
* CHANGELOG file

## [1.3.0] - 2021-07-08

### Added
* Code for cleaning up AWS resources created by Assisted Log Enabler for AWS.
    * Amazon Route 53 Resolver Query Logging in single account mode is only currently supported.
* Options for running cleanup mode within the main function.
* IAM Permissions example for cleanup operations.
* Information within the Step-by-Step instructions for multi-account to reflect details about AWS CloudFormation StackSets Delegated Administrator.

### Changed
* README documentation.
    * Updated Cleanup section to reflect new cleanup capabilities.
    * Updated IAM Permissions examples within the README.
* AWS CloudFormation template for deploying IAM Permissions to run cleanup code.
* Header in files to reflect "Assisted Log Enabler for AWS", instead of "Assisted Log Enabler (ALE)".

## [1.3.1] - 2021-07-22

### Added
* Randomization to the end of the Amazon S3 bucket name in both single and multi account modes.
* Instructions for deploying the AWS CloudFormation Stack individually, within the AWS Organizations root account for multi-account deployment.
* Link for the AWS Security Analytics Bootstrap within the README.

### Changed
* Feedback section within README to contain link to Issues section.

## [1.3.2] - 2021-08-03

### Changed
* README Documentation
    * Removed unzip steps from single and multi-account instructions.
    * Minor updates to various service names.

## [1.3.3] - 2021-08-10

### Added
* README Documentation
    * Added details for the point-and-clock Amazon Athena integration for VPC Flow Logs.

## [1.4.0] - 2021-08-13

### Added
* Dry Run mode for both single and multi-account modes.
    * Added README Documentation for Dry Run modes.

## [1.4.1] - 2021-08-23

### Added
* Tagging for VPC Flow Log Resources in single account mode.
* Cleanup options for VPC Flow Logs and CloudTrails created by Assisted Log Enabler for AWS.
* README Documentation
    * Added details in the Cleanup section to reflect VPC Flow Logs and CloudTrail commands.
    * Added section about the Shared Responsibility Model.

## [1.4.1b] - 2021-08-24

### Added
* Condition statements for if no options were selected during Dry Run and Cleanup modes.

## [1.4.2] - 2021-09-20

### Added
* CloudTrail tags to show that the trail is created by Assisted Log Enabler for AWS.

### Changed
* CloudTrail name to be more descriptive that it's created by Assisted Log Enabler for AWS.
