# Project Title

Static Website Deployment with Azure Storage and Azure DevOps

## Overview

This project demonstrates the deployment of a static website using Azure Storage and Azure DevOps. It provides step-by-step instructions to set up a continuous integration and deployment pipeline to automate the deployment process. The website is hosted on Azure Blob Storage and can be accessed globally through Azure CDN.

## Architectural Diagram

<img src="https://cdn.hashnode.com/res/hashnode/image/upload/v1688709556557/3c6a354d-be74-45fd-8d0d-90282a244ce6.png?auto=compress,format&format=webp">

## Prerequisites

Before getting started, make sure you have the following:

- Azure Account and Subscription
- Azure DevOps Account
- GitHub Account and Basic Knowledge of Git
- Static Website Template
- Domain Name or Sub-Domain (Optional)
- Resilient Attitude to learn and build on Azure Cloud 😉

## 📝 Detailed Step-by-Step Guide

If you're interested in learning more about the setup and deployment process, I've written a blog post 📝 that outlines each step in detail. You can access the blog post [[Here](https://joeloduyemi.hashnode.dev/unleashing-the-power-of-azure-storage-a-beginners-guide-to-hosting-static-websites-on-azure-cloud)] to gain insights into the configuration, automation, and best practices involved in building and deploying this architecture. 📚

## Table of Contents

1. [Prerequisites](#prerequisites)
2. [Getting Started](#getting-started)
3. [Setting Up Azure Storage and Static Website Hosting](#setting-up-azure-storage-and-static-website-hosting)
4. [Configuring Azure DevOps Pipeline](#configuring-azure-devops-pipeline)
5. [Setting Up Azure CDN and Custom Domain Mapping](#setting-up-azure-cdn-and-custom-domain-mapping)
6. [Cleaning Up Resources](#cleaning-up-resources)

## Getting Started

To get started with the deployment process, follow these steps:

1. Clone or download the project repository.
2. Install the necessary dependencies or tools mentioned in the prerequisites section.
3. Review the project structure and make any required modifications to suit your specific needs.

## Setting Up Azure Storage and Static Website Hosting

To set up Azure Storage and enable static website hosting, perform the following steps:

1. Create a new Azure Storage account.
2. Enable static website hosting for the storage account.
3. Configure the default index and error documents.
4. Upload your static website files to the storage account.

## Configuring Azure DevOps Pipeline

To configure the Azure DevOps pipeline for continuous integration and deployment, follow these steps:

1. Create a new project in Azure DevOps.
2. Set up a service connection between your Azure subscription and Azure DevOps account.
3. Configure the pipeline YAML file to create build artifacts and set up continuous integration.
4. Create a self-hosted agent pool (if necessary) to run the pipeline.

## Setting Up Azure CDN and Custom Domain Mapping

To enable Azure CDN and map a custom domain to your Azure Blob Storage endpoint, follow these steps:

1. Create an Azure CDN profile.
2. Create an Azure CDN endpoint and link it to your storage account.
3. Configure caching and content delivery settings.
4. Set up custom domain mapping using Azure CDN rules and your domain registrar.

## Cleaning Up Resources

To clean up the resources used in the project, follow these steps:

1. Delete the Azure CDN profile and endpoint.
2. Remove the Azure Storage account.
3. Delete any custom domain DNS records (if applicable).
