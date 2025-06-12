---
title: Azure Event Hubs SDK for C++
description: Reference for Azure Event Hubs SDK for C++
ms.date: 06/11/2025
ms.topic: reference
ms.devlang: cpp
ms.service: eventhubs
---
# Azure Event Hub modules for C++

[Azure Event Hubs](https://azure.microsoft.com/services/event-hubs/) is a highly scalable publish-subscribe service that can ingest millions of events per second and stream them to multiple consumers. This lets you process and analyze the massive amounts of data produced by your connected devices and applications.

## Libraries for data access

To send and receive events from an Azure Event Hub instance, you would use the below packages.

| Reference | Package | Source |
|---|---|---|
|[Event Hubs](event-hubs-readme.md)|[azure-messaging-eventhubs-cpp](https://vcpkg.io/en/package/azure-messaging-eventhubs-cpp)|[GitHub](https://github.com/Azure/azure-sdk-for-cpp/tree/main/sdk/eventhubs/azure-messaging-eventhubs)|
|[Event Hubs Blob Storage Checkpoint Store](eventhubs-checkpointstore-blob-readme.md)|[azure-messaging-eventhubs-checkpointstore-blob-cpp](https://vcpkg.io/en/package/azure-messaging-eventhubs-checkpointstore-blob-cpp)|[GitHub](https://github.com/Azure/azure-sdk-for-cpp/tree/main/sdk/eventhubs/azure-messaging-eventhubs-checkpointstore-blob)|
