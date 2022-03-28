# cfcode
<!--- See https://shields.io for others or to customize this set of shields.  --->

![GitHub last commit](https://img.shields.io/github/last-commit/dennislwm/archiveso?color=red&style=plastic)

<!-- TOC -->

- [cfcode](#cfcode)
- [Overview](#overview)
- [Introduction to AWS CloudFormation](#introduction-to-aws-cloudformation)
- [CloudFormation Deep Dive](#cloudformation-deep-dive)
- [References](#references)

<!-- /TOC -->
---
# Overview

In no particular order, my plan is to use the following resources to learn and research.

| Title | Author | Publisher Date [Short Code]
|---|---|---|
| E-Learning: [Introduction to AWS CloudFormation](https://learn.acloud.guru/course/intro-aws-cloudformation/dashboard) | Abhaya Chauhan | ACloudGuru 2022 [Chau2022]
| E-Learning: [CloudFormation Deep Dive](https://learn.acloud.guru/course/d8a92be0-dbab-4498-a2af-375a7a591ae8/dashboard) | Craig Arcuri | ACloudGuru 2022 [Arcu2022]

---
# Introduction to AWS CloudFormation

- [X] [CloudFormation Features](doc/chau2022-04.md#cloudformation-features)
  - [Intrinsic Functions](doc/chau2022-04.md#intrinsic-functions)
  - [Multiple Resources](doc/chau2022-04.md#multiple-resources)
  - [Pseudo Parameters](doc/chau2022-04.md#pseudo-parameters)
  - [Mappings](doc/chau2022-04.md#mappings)
  - [Input Parameters](doc/chau2022-04.md#input-parameters)
  - [Outputs](doc/chau2022-04.md#outputs)
  - [Alias](doc/chau2022-04.md#alias)
  - [Anchors](doc/chau2022-04.md#anchors)
- [X] [Setting up an EC2 Instance](doc/chau2022-05.md#setting-up-an-ec2-instance)
  - [Introduction](doc/chau2022-05.md#introduction)
  - [User Data](doc/chau2022-05.md#user-data)
  - [CloudFormation Helper Scripts](doc/chau2022-05.md#cloudformation-helper-scripts)
  - [CloudFormation Init](doc/chau2022-05.md#cloudformation-init)
  - [Summary](doc/chau2022-05.md#summary)
- [X] [Updating our Stack with Change Sets](doc/chau2022-06.md#updating-our-stack-with-change-sets)
  - [Introduction](doc/chau2022-06.md#introduction)
  - [Change Sets](doc/chau2022-06.md#change-sets)
  - [Scaling our EC2 using Launch Configuration](doc/chau2022-06.md#scaling-our-ec2-using-launch-configuration)
---
# CloudFormation Deep Dive

- [X] [CloudFormation and IAM](doc/arcu2022-02.md#cloudformation-and-iam)
  - [Policy and Permissions](doc/arcu2022-02.md#policy-and-permissions)
  - [Resource Types](doc/arcu2022-02.md#resource-types)
- [ ] [Templates In-Depth](doc/arcu2022-03.md#templates-in-depth)
  - [Format and Structure](doc/arcu2022-03.md#format-and-structure)
- [ ] [Stacks In-Depth](doc/arcu2022-04.md)
---
# References

The following resources were used as a single-use reference.

| Title | Author | Publisher Date
|---|---|---|
| GitHub Repo: [CloudFormation Linter](https://github.com/aws-cloudformation/cfn-lint) | AWS CloudFormation | 2022
| [AWS resource and property types reference](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-template-resource-type-ref.html) | AWS CloudFormation | 2022