---
services: Compute
platforms: dotnet
author: anuchandy
---

# Getting started with creating a Virtual Machine using specialized disks from Snapshots #

          Azure Compute sample for managing virtual machines -
           - Create an managed virtual machine from PIR image with data disks
           - Create snapshot from the virtual machine's OS and data disks
           - Create managed disks from the snapshots
           - Create virtual machine by attaching the managed disks
           - Get SAS Uri to the virtual machine's managed disks.


## Running this Sample ##

To run this sample:

Set the environment variable `AZURE_AUTH_LOCATION` with the full path for an auth file. See [how to create an auth file](https://github.com/Azure/azure-libraries-for-java/blob/master/AUTH.md).

    git clone https://github.com/Azure-Samples/managed-disk-dotnet-create-virtual-machine-using-specialized-disk-from-snapshot.git

    cd managed-disk-dotnet-create-virtual-machine-using-specialized-disk-from-snapshot

    dotnet restore

    dotnet run

## More information ##

[Azure Management Libraries for C#](https://github.com/Azure/azure-sdk-for-net/tree/Fluent)
[Azure .Net Developer Center](https://azure.microsoft.com/en-us/develop/net/)
If you don't have a Microsoft Azure subscription you can get a FREE trial account [here](http://go.microsoft.com/fwlink/?LinkId=330212)

---

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.