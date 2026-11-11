

# Azure Infrastructure Automation with IaC

A practical Infrastructure as Code (IaC) case study focused on automating Azure resource provisioning using ARM templates and Azure CLI. This repository demonstrates how to deploy a secure and scalable cloud environment for a web application workload with networking, compute, storage, database, monitoring, and governance controls.

This project was designed to showcase real-world Azure automation patterns and to highlight how cloud environments can be consistently provisioned, managed, and monitored through infrastructure-as-code practices.

## Project Overview

This repository contains Azure infrastructure deployment templates and automation scripts for provisioning a complete environment, including:

- Resource Group
- Virtual Network and Subnet
- Multiple Windows Virtual Machines
- Network Security Group (NSG)
- Azure Load Balancer
- Azure Storage Account
- File Share and VM mapping
- Azure SQL Database
- Recovery Services Vault
- Azure Monitor alerting
- RBAC-enabled AD group for administrator access

##  Automated Deployment
- **ARM/Bicep Templates** for standardization  
- **Parameterization** for flexibility  
- **Deployment via Azure CLI**  
- **GitHub Storage for version control**  

The goal is to standardize environment creation, reduce manual configuration errors, and provide a repeatable deployment model for cloud infrastructure.

## Why Infrastructure as Code?

Infrastructure as Code helps teams:

- Deploy infrastructure consistently and repeatedly
- Version control infrastructure changes
- Reduce configuration drift
- Speed up environment provisioning
- Improve collaboration and reviewability
- Make infrastructure changes auditable and reproducible

This repository is a hands-on example of that approach using Azure-native deployment tooling.

## Architecture

The deployment includes a typical production-style Azure environment structured around a shared application platform:

- Virtual network segmentation for application resources
- Windows-based compute layer for application hosting
- Storage for shared data and file access
- Database layer for application data
- Load balancing to distribute traffic
- Backup and recovery configuration
- Monitoring and alerting for resource health and thresholds
- Role-based access management for administrative control

## Repository Structure

```text
├── ARM/
│   └── Azure deployment templates and resource definitions
├── Case-study-IaC.pdf
├── IaC-Presentation.pptx
├── README.md






##  Tools Used
🔹 ARM Templates    
🔹 Azure CLI  
🔹 GitHub  


