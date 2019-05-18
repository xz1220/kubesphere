# KubeSphere
[![License](http://img.shields.io/badge/license-apache%20v2-blue.svg)](https://github.com/KubeSphere/KubeSphere/blob/master/LICENSE)
[![Build Status](https://travis-ci.org/kubesphere/kubesphere.svg?branch=master)](https://travis-ci.org/kubesphere/kubesphere)

----

## What is KubeSphere

[KubeSphere](https://kubesphere.io/) is an enterprise-grade multi-tenant container management platform that built on [Kubernetes](https://kubernetes.io). It provides an easy-to-use UI enables creation of computing resources with a few clicks and one-click deployment, which reduces the learning curve and empower the DevOps teams. It greatly reduces the complexity of the daily work of development, testing, operation and maintenance, aiming to solve the pain spots of Kubernetes' storage, network, security and ease of use, etc.

> See this [document](https://docs.kubesphere.io/advanced-v2.0/zh-CN/introduction/intro/) that describes the KubeSphere landscape and details.

## Features

KubeSphere Advanced Edition 2.0.0 provides an easy-to-use console with the awesome user experience that allows you to quickly get started with a container management platform. KubeSphere provides and supports following core features:


- Workload management
- Microservice governance
- DevOps Delivery
- Source to Image
- Multi-tenant management
- Multi-dimensional monitoring, Logging, Alerting,
- Service and network management
- Application template 
- Infrastructure management, image registry management
- Interate Harbor and GitLab
- LB controller for Kubernetes on bare metal ([Porter](https://github.com/kubesphere/porter)), [cloud LB plugin](https://github.com/yunify/qingcloud-cloud-controller-manager)
- Support GPU node


It also supports multiple open source storage and high-performance cloud storage as the persistent storage services, as well as support multiple open source network plugins.

> See this [document](https://docs.kubesphere.io/advanced-v2.0/zh-CN/introduction/features/) that elaborates on the KubeSphere features and services from a professional point of view.

----

## Latest Release

KubeSphere Advanced Edition 2.0.0 was released on **May 18th, 2019**. See the [Release Notes For 2.0.0](https://docs.kubesphere.io/advanced-v2.0/release/release-v200/) to preview the updates.

## Installation

### Download

```shell
curl
```

### Install 

KubeSphere installation supports following 2 kinds of installation, please reference the following guides on how to get KubeSphere up and running.

- [All-in-One](https://docs.kubesphere.io/advanced-v2.0/zh-CN/installation/all-in-one/): For those who are new to KubeSphere and looking for the fastest way to install and experience the dashboard, the all-in-one installation must be your best choice since it supports one-click installation.
- [Multi-Node](https://docs.kubesphere.io/advanced-v2.0/zh-CN/installation/multi-node/): Multi-node is used for installing KubeSphere on multiple instances, supports for installing a highly available cluster which is able to use in a formal environment.


### Minimum Requirements

- Operating Systems
   - CentOS 7.5 (64 bit)
   - Ubuntu 16.04/18.04 LTS (64 bit)
   - Red Hat Enterprise Linux Server 7.4 (64 bit)
   - Debian Stretch 9.5 (64 bit)
- Hardware
   - CPU：8 Core,  Memory：16 G, Disk Space：100 G

## Quick Start

The [Quick Start Guide](https://docs.kubesphere.io/advanced-v2.0/quick-start/admin-quick-start/) provides 12 quick-start examples to walk you through the process and common manipulation in KubeSphere, with a quick overview of the core features of KubeSphere that helps you to get familiar with it.


## RoadMap

Currently, KubeSphere has released the following 4 major editions. Advanced Edition 2.0.0 was released on May 18, 2019. The future releases will include Big data, AI, Multicluster, QingCloud SDN, etc.

**Community Edition** => **Express Edition** => **Advanced Edition 1.0.0** => **Advanced Edition 2.0.0**

![Roadmap](docs/images/roadmap-en.png)

## Documentation

- [KubeSphere Documentation (En/中) ](https://docs.kubesphere.io/)
- [KubeSphere Docementation (PDF)](https://docs.kubesphere.io/KubeSphere-advanced-v2.0.pdf)

## Support, Discussion, and Community

If you need any help with KubeSphere, please join us at [Slack channel](http://kubesphere.slack.com/) where most of our team hangs out at.

Please submit any KubeSphere bugs, issues, and feature requests to [KubeSphere GitHub Issue](https://github.com/kubesphere/kubesphere/issues).

## Contributing to the project

All members of the KubeSphere community must abide by [Code of Conduct](docs/code-of-conduct.md). Only by respecting each other can we develop a productive, collaborative community.

How to submit a pull request to KubeSphere? See [Pull Request Instruction](docs/pull-requests.md).

You can then find out more detail [here](docs/welcome-to-KubeSphere-new-developer-guide.md).


