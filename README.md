---
page_type: sample
languages:
- java
products:
- azure
description: "Azure App Service basic sample for managing function apps."
urlFragment: app-service-java-manage-functions
---

# Getting Started with Appservice - Manage Function App Basic - in Java #


  Azure App Service basic sample for managing function apps.
   - Create 3 function apps under the same new app service plan:
     - 1, 2 are in the same resource group, 3 in a different one
     - 1, 3 are under the same consumption plan, 2 under a basic app service plan
   - List function apps
   - Delete a function app
 

## Running this Sample ##

To run this sample:

Set the environment variable `AZURE_AUTH_LOCATION` with the full path for an auth file. See [how to create an auth file](https://github.com/Azure/azure-libraries-for-java/blob/master/AUTH.md).

    git clone https://github.com/Azure-Samples/app-service-java-manage-functions.git

    cd app-service-java-manage-functions

    mvn clean compile exec:java

## More information ##

[http://azure.com/java](http://azure.com/java)

If you don't have a Microsoft Azure subscription you can get a FREE trial account [here](http://go.microsoft.com/fwlink/?LinkId=330212)

---

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.
