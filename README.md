# Azure Static Web App Deployment Guide

## Overview

This guide provides step-by-step instructions for deploying a static web app to Azure using Azure Static Web Apps service.

## Table of Contents

1. [Introduction](#introduction)
2. [Prerequisites](#prerequisites)
3. [Setup Instructions](#setup-instructions)
4. [Deployment](#deployment)
5. [Updating Your Web App](#updating-your-web-app)
6. [Reverting Changes](#reverting-changes)
7. [Conclusion](#conclusion)

## Introduction

This guide walks you through the process of deploying a static web app to Azure using Azure Static Web Apps service. By following these instructions, you'll be able to create a new static web app, connect it to your GitHub repository, and deploy your app to Azure.

## Prerequisites

Before you begin, ensure you have the following:

- An Azure account with sufficient permissions to create resources.
- Access to the Azure portal.
- A GitHub account with your static web app code in a repository.

## Setup Instructions

1. **Navigate to Azure Portal**:
   - Go to [portal.azure.com](https://portal.azure.com/).
   - Log in to the Azure Portal.

2. **Create a Virtual Network**:
   - Navigate to the Azure VNet service.
   - Click on "Create a Virtual Network".
   - Fill in the required details such as resource group and name for your VNet.
   - Choose the region for deployment.

...

## Deployment

Visit the deployed website at: [Website Link](https://blue-forest-003efc010.5.azurestaticapps.net/)


1. **Deploy Your Web App**:
   - Navigate to "All services" in the Azure portal.
   - Click on "App Services".
   - Select "Static Web App".
   - Choose the resource group and enter a unique name for your web app.
   - Click "Login" to authorize Azure-App-Service-Static-Web-Apps to access your GitHub repositories.
   - Select your static web page repository and choose the GitHub branch.
   - Configure the build preset for HTML and review the settings.
   - Click "Review + create" to deploy your web app.

...

## Updating Your Web App

1. **Edit Your Web App**:
   - Navigate to your GitHub repository.
   - Edit the files in your repository as needed.
   - Commit the changes to your GitHub repository.

2. **Update Your Azure Web App**:
   - Go back to the Azure portal.
   - Monitor the GitHub Action runs for deployment status.
   - Wait for the deployment to finish.
   - Visit your site to see the updates.

## Reverting Changes

1. **Revert Changes**:
   - If needed, revert the changes made to your web app files in your GitHub repository.
   - Commit the changes to your GitHub repository.

2. **Update Azure Web App**:
   - Repeat the steps for updating your Azure web app as described above.

## Conclusion

Congratulations! You have successfully deployed a static web app to Azure using Azure Static Web Apps service. For further assistance or troubleshooting, refer to the Azure documentation or community forums.

---
