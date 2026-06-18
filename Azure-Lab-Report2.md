# Azure Cloud Computing Lab Report

## Azure Account Creation

Step 1: Go to https://azure.microsoft.com/free  
Step 2: Click "Start free"  
Step 3: Sign in with Microsoft account  
Step 4: Enter personal details  
Step 5: Verify identity:
   - Phone verification (SMS)
   - Credit card verification
Step 6: Accept agreement and create account

## Subscription
Azure Subscription 1

## Azure Free Tier Summary

Microsoft Azure provides a free account with access to credits and free services to help users explore the platform.

| Feature        | Details |
|---------------|--------|
| Free Credit   | $200 credit valid for the first 30 days after account creation |
| Free Services | 12 months of popular services with limited monthly usage (e.g., virtual machines, storage) |
| Always Free   | 50+ services that are free with usage limits (e.g., Azure Functions, DevOps tools) |

These benefits allow new users to build and test applications without incurring immediate costs.

The $200 credit can be used to explore paid services, after which the account transitions to pay-as-you-go unless spending limits are enforced.

Reference:
https://azure.microsoft.com/free

## Resource Group
asiwaju-lab-rg

## Region Selected
East US

## Why I Chose This Region
East US provides good performance and availability and is one of the recommended regions for users in Africa.

## Resource Deployed
Azure Storage Account

## Azure Portal Navigation
The Azure portal is a web-based management console that allows users to create, monitor, and manage Azure resources and services from a single location.
Components of the Azure Portal 
Navigation Menu: located on the left side of the portal or console. it provides quick access to commonly used services such as storage, VMs, Resources groups.
Search Bar: its located at the top of the portal. it allows users to quickly find services, resources, settings, and documentations without navigating through menus.
Dashboard: The main landing page after signing in. Displays customizable tiles that provide quick access to resources, service health, cost information, and monitoring data.
Notifications Panel: Accessible through the bell icon at the top-right corner. Displays updates on deployments, resource creation, alerts, and system notifications.
Cloud Shell: Accessible from the top menu. Provides a browser-based command-line environment for managing Azure resources using Azure CLI or PowerShell.

## Shared Responsibility Model
Microsoft is responsible for the physical infrastructure, networking, hardware, and platform security.

I am responsible for configuring and securing my resources, managing identities and access, and protecting my data. MFA was set-up to protect my Azure account.

## Cost Monitoring
I accessed Cost Management + Billing and reviewed Cost Analysis to monitor resource usage and avoid charges beyond the Free Tier limits.

## Budget Alert
Cost Management + Billing → Budgets → Add Budget
Set threshold = 75%
Enable email alert

## Completion Checklist

- [x] Azure account created
- [x] MFA enabled
- [x] Dashboard customized
- [x] Budget alert configured
- [x] Free tier documented