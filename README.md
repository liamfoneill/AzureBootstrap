# AzureBootstrap
Creates base-level resources for Azure - 
  - Geo-Redundant Storage Account for Azure Cloud Shell and associated file share
  - Geo-Redundant Storage Account for Terraform State Storage purpose and associate blob container with a soft delete policy of 30 days

# Example Usage

`New-AzSubscriptionDeployment -Location 'westeurope' -TemplateFile .\azuredeploy.json -TemplateParameterFile .\azuredeploy.parameters.json -WhatIf`

