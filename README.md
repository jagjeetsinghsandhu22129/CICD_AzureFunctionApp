# CICD_AzureFunctionApp


This project shows how to use Azure DevOps to deploy an Azure Function App utilizing an automated CI/CD pipeline. Build, Test, and Deploy are the three phases of the pipeline.


Prerequisites:

Azure Account with a Function App.
Azure DevOps Organization with access to your GitHub repository.
.NET Core SDK (or any other runtime for your Azure Function).


Pipeline Stages

Build:
Compiles the Azure Function App using dotnet build.

Test:
Runs unit tests for the Azure Function using dotnet test.

Deploy:
Deploys the app using the AzureFunctionApp@1 task in Azure DevOps.