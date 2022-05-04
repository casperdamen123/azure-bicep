# Azure Bicep
This repository contains code examples on how to leverage [Bicep](https://docs.microsoft.com/en-us/azure/azure-resource-manager/bicep/overview?tabs=bicep) to manage Azure Cloud resources using Infrastructure as Code (IaC).

## Content
The file names describe the Bicep functionality it entails. Currently the following topics are included:
- `child.bicep`: Set up resources in a parent/child structure. The child resource only exists in the context of the parent resource and can't exist without it.
- `extensions.bicep`: Add extensions to existing resources.
- `existing.bicep`: Use existing resources initially created outside the context of your Bicep file.
- `templating.bicep`: Set up reusable templates that are clear to other developers and have the right balance between flexibility and simplicity.