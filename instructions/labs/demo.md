# Module 5: Authoring Serverless Applications in Azure

# Lab Answer Key: Deploying Serverless Workloads to Azure

## Exercise 1: Create Web App

#### Task 1: Open the Azure Portal

1. On the Taskbar, click the **Microsoft Edge** icon.

1. In the open browser window, navigate to the **Azure Portal** (<https://portal.azure.com>).

1. Enter the **email address** of your *Microsoft account*.

1. Click the **Next** button.

1. Enter the **password** for your *Microsoft account*.

1. Click the **Sign in** button.

#### Task 2: Create App Service Plan

1. At the top of the portal, click the **Cloud Shell** icon to open a new shell instance.

1. In the **Cloud Shell** command prompt at the bottom of the portal, type in the following command and press **Enter** to create a new **Resource Group**:

    ```
    az group create --name MOD05APPS --location eastus
    ```

1. Type in the following command and press **Enter** to create a new **Resource Group**:

    ```
