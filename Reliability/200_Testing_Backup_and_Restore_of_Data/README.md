# Level 200: Backup and Restore of Data
https://wellarchitectedlabs.com

## Introduction

In this lab, you will become familiar with creating periodic backups of AWS resources such as EBS Volumes, RDS Databases, DynamoDB Tables, and EFS File Systems. You will learn how to restore data from backups, and how to automate the entire process.

It is not sufficient to just create backups of data sources, you must also test these backups to ensure they can be used to recover data. A backup is useless if you are unable to restore your data from it. Testing the restore process after each backup will ensure you are aware of any issues that might arise during a restore down the line.

In this lab, you will create an EBS Volume as a data source. You will then create a strategy to backup these data sources periodically using AWS Backup, and finally, automate the testing of the restore process as well as cleanup of resources using AWS Lambda.

The skills you learn will help you define a backup and restore plan in alignment with the [AWS Well-Architected Framework](https://aws.amazon.com/architecture/well-architected/)

## Goals:

* Create a Backup Strategy to ensure mission-critical data is being backed up regularly
* Test restoring from backups to ensure there are no data recovery issues
* Learn how to automate this process

## Prerequisites:

* An [AWS Account](https://portal.aws.amazon.com/gp/aws/developer/registration/index.html) that you are able to use for testing, that is not used for production or other purposes.
* An IAM user or role in your AWS account that has Administrator privileges.
Launch the CloudFormation Stack to provision resources that will act as data sources.

**NOTE**: You will be billed for any applicable AWS resources used as part of this lab, that are not covered in the AWS Free Tier.


<BR>

## [Start the Lab!](Lab_Guide.md)

<BR>
<BR>

***

## License

### Documentation License

Licensed under the [Creative Commons Share Alike 4.0](https://creativecommons.org/licenses/by-sa/4.0/) license.

### Code LicenseLicensed under the Apache 2.0 and MITnoAttr License.

Copyright 2019 Amazon.com, Inc. or its affiliates. All Rights Reserved.

Licensed under the Apache License, Version 2.0 (the "License"). You may not use this file except in compliance with the License. A copy of the License is located at

    https://aws.amazon.com/apache2.0/

or in the "license" file accompanying this file. This file is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.
