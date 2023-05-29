# Deploy EKS with FSxN using NetApp Astra Trident CSI automated using AWS CloudFormation

EKS (Elastic Kubernetes Service) is a first-party managed kubernetes offering by AWS allowing for quick and easy setup of the kubernetes cluster. AWS creates and configures the control plane automatically when a new EKS cluster is provisioned.

FSxN (FSx for NetApp ONTAP) is a high-performance, enterprise-class, metered file-storage service. Follow the steps in this documentation to provision and configure FSx for NetApp ONTAP as a persistent volume (PV) option for applications running on the EKS cluster.

Astra Trident is an open-source and fully supported storage orchestrator for containers and Kubernetes distributions, including Red Hat OpenShift. Trident works with the entire NetApp storage portfolio and also supports NFS and iSCSI connections. Trident accelerates the DevOps workflow by allowing end users to provision and manage storage from their NetApp storage systems without requiring intervention from a storage administrator.

This solution aims to provide a one-touch option for users looking to deploy EKS with FSxN as the backend storage allowing for dynamic volume provisioning via Astra Trident CSI using AWS CloudFormation template. 

## Features
The solution provides the following features:

* Deploy an EKS Cluster using AWS Quick Start (https://aws-quickstart.github.io/quickstart-amazon-eks/)
* Deploy FSxN File System and Storage Virtual Machine (SVM)
* Install and configure Astra Trident
* Deploy a sample application to showcase the integration works end-to-end

## Pre-requisites
Before you begin, ensure that the following prerequisites are met: 

* An AWS account/subscription with sufficient permissions to provision EKS, FSxN, VPC, subnets and other constructs required.

## Solution Architecture and Deployment Guide

The documentation for the solution architecture used and the deployment guidelines are available at link-here


## License
By accessing, downloading, installing or using the content in this repository, you agree the terms of the License laid out in License file.

Note that there are certain restrictions around producing and/or sharing any derivative works with the content in this repository. Please make sure you read the terms of the License before using the content. If you do not agree to all of the terms, do not access, download or use the content in this repository.

Copyright: 2023 NetApp Inc.

## Author Information

- [Dhruv Tyagi](mailto:dhruv.tyagi@netapp.com) - NetApp Solutions Engineering Team
- [Niyaz Mohamed](mailto:niyaz.mohamed@netapp.com) - NetApp Solutions Engineering Team