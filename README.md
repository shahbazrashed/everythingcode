# everythingcode
This repo contains useful information and commands to do everything via code 

The purpose of the repo is to create step by step instructions to deploy Azure infrastructure via code. Portal shold only be used when code is not an option or during troubleshooting a quick ad-hoc change is required to resolve an issues, such as traffic flow etc.

The choice of coding language is Terrafom in this case and it is ssumed that local PC envoirnonemt has been setup with Terraform, VS code and Azure CLI. Ther are a number of videos avaible on Youtube to set this up. Choclatey is a good tool to setup Terraform : https://community.chocolatey.org/packages/terraform .

In this excercise 

az ad sp create-for-rbac --name "sp-shahbaz" --role owner --scopes /providers/Microsoft.Management/managementGroups/Tenanat-root-mg-GUID-here

