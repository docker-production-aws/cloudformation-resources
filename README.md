# Docker in Production using AWS CloudFormation Resources Playbook

## Introduction

This repository is part of the [Docker in Production using Amazon Web Services](https://app.pluralsight.com/library/courses/docker-production-using-amazon-web-services/table-of-contents) course material, and provides an Ansible playbook for creating CloudFormation related resources.

## Branches

This repository contains two branches:

- [`master`](tree/master) - represents the initial starting state of the repository as viewed in the course.  Specifically this is an empty repository that you are instructed to create in the module **Deploying AWS Infrastructure Using Ansible and CloudFormation**.

- [`final`](tree/final) - represents the final state of the repository after completing all configuration tasks as described in the course material.

> The `final` branch is provided as a convenience in the case you get stuck, or want to avoid manually typing out large configuration files.  In most cases however, you should attempt to configure this repository by following the course material.

To clone this repository and checkout a branch you can simply use the following commands:

```
$ git clone https://github.com/docker-production-aws/packer-ecs.git
...
...
$ git checkout final
Switched to branch 'final'
$ git checkout master
Switched to branch 'master'
```

## Errata

No known issues.

## Further Reading

Please see the README of the [AWS Starter repository](https://github.com/docker-production-aws/aws-starter) for instructions on how to use the Ansible playbook included with this repository.