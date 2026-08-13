# Laboratory 03 – Multi-Cloud Explorer

## Mission 3: Become a Multi-Cloud Explorer

This laboratory investigates AWS, Microsoft Azure, and Google Cloud Platform and compares their services, infrastructure, and suitability for different business requirements.

# Checkpoint 7 – Linux Investigation

The KillerCoda Linux Playground reported the following operating system:

## Operating System

The operating system information was collected using:
cat /etc/os-release
The server is running Ubuntu 24.04.4 LTS (Noble Numbat) with an x86_64 architecture.

## CPU Information
CPU information was collected using:
lscpu
The server uses an Intel Xeon E312xx (Sandy Bridge) processor at approximately 2.0 GHz. The environment provides 1 CPU, 1 core, and 1 thread.

## Memory

Memory information was collected using:
free -h
The system has 1.9 GiB of total memory, with 417 MiB used, 866 MiB free, and approximately 1.5 GiB available.

## Disk Space
Disk space information was collected using:
df -h
The main disk partition has 19 GB of total storage, with 5.4 GB used and 13 GB available. The disk is approximately 30% utilized.


## Cloud Migration

If this Linux server were migrated to the cloud, it could be hosted using the following services:

| Cloud Provider  | Service                |
| --------------- | ---------------------- |
| AWS             | Amazon EC2             |
| Microsoft Azure | Azure Virtual Machines |
| GCP             | Compute Engine         |

Amazon EC2 can host Linux virtual machines in AWS. Azure Virtual Machines can run Linux workloads in Microsoft Azure, while Google Compute Engine provides Linux virtual machine instances in Google Cloud.

The most appropriate provider would depend on factors such as cost, required performance, storage, networking, security, scalability, and the organization's existing cloud environment.
