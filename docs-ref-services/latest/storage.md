---
title: Azure Storage SDK for C++
description: Reference for Azure Storage SDK for C++
ms.date: 12/04/2025
ms.topic: reference
ms.devlang: cpp
ms.service: storage
---
# Azure Storage libraries for C++

Azure Storage is a Microsoft-managed service providing cloud storage that is highly available, secure, durable, scalable, and redundant. Azure Storage includes Blobs (objects), Queues, and Files.

## Libraries for data access

|Reference|Package|Description|Source|
|---|---|---|---|
|[Storage Blobs](storage-blobs-readme.md)|[azure-storage-blobs-cpp](https://vcpkg.io/en/package/azure-storage-blobs-cpp)|Microsoft's object storage solution for the cloud. Blob storage is optimized for storing massive amounts of unstructured data that does not adhere to a particular data model or definition, such as text or binary data.|[GitHub](https://github.com/Azure/azure-sdk-for-cpp/tree/main/sdk/storage/azure-storage-blobs)|
|[Storage Queues](storage-queues-readme.md)|[azure-storage-queues-cpp](https://vcpkg.io/en/package/azure-storage-queues-cpp)|A service for storing large numbers of messages. A queue message can be up to 64 KB in size and a queue may contain millions of messages, up to the total capacity limit of a storage account.|[GitHub](https://github.com/Azure/azure-sdk-for-cpp/tree/main/sdk/storage/azure-storage-queues)|
|[Storage Files Shares](storage-files-shares-readme.md)|[azure-storage-files-shares-cpp](https://vcpkg.io/en/package/azure-storage-files-shares-cpp)|Offers fully managed file shares in the cloud that are accessible via the industry standard Server Message Block (SMB) protocol. Azure file shares can be mounted concurrently by cloud or on-premises deployments of Windows, Linux, and macOS.|[GitHub](https://github.com/Azure/azure-sdk-for-cpp/tree/main/sdk/storage/azure-storage-files-shares)|
|[Storage Files Data Lake](storage-files-datalake-readme.md)|[azure-storage-files-datalake-cpp](https://vcpkg.io/en/package/azure-storage-files-datalake-cpp)|Includes all the capabilities required to make it easy for developers, data scientists, and analysts to store data of any size, shape, and speed, and do all types of processing and analytics across platforms and languages.|[GitHub](https://github.com/Azure/azure-sdk-for-cpp/tree/main/sdk/storage/azure-storage-files-datalake)|
|[Storage Common](storage-common-readme.md)|[azure-storage-common-cpp](https://vcpkg.io/en/package/azure-storage-common-cpp)|Provides infrastructure shared by the other Azure Storage client libraries like shared key authentication and exceptions.|[GitHub](https://github.com/Azure/azure-sdk-for-cpp/tree/main/sdk/storage/azure-storage-common)|

## Contributing

See the [C++ Contributing Guide][sdk_contrib] for details on building,
testing, and contributing to these libraries.

See the [Storage Testing Guide][storage_testing] for how to set up storage resources running unit tests.

This project welcomes contributions and suggestions.  Most contributions require
you to agree to a Contributor License Agreement (CLA) declaring that you have
the right to, and actually do, grant us the rights to use your contribution. For
details, visit [cla.microsoft.com][cla].

This project has adopted the [Microsoft Open Source Code of Conduct][coc].
For more information see the [Code of Conduct FAQ][coc_faq]
or contact [opencode@microsoft.com][coc_contact] with any
additional questions or comments.

<!-- LINKS -->
[sdk_contrib]: https://github.com/Azure/azure-sdk-for-cpp/blob/main/CONTRIBUTING.md
[storage_testing]: https://github.com/Azure/azure-sdk-for-cpp/blob/main/sdk/storage/TestingGuide.md
[cla]: https://cla.microsoft.com
[coc]: https://opensource.microsoft.com/codeofconduct/
[coc_faq]: https://opensource.microsoft.com/codeofconduct/faq/
[coc_contact]: mailto:opencode@microsoft.com