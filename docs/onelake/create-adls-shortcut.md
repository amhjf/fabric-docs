---
title: Create an Azure Data Lake Storage Gen2 shortcut
description: Learn how to create a OneLake shortcut for Azure Data Lake Storage Gen2 inside a Microsoft Fabric lakehouse.
ms.reviewer: eloldag
ms.author: trolson
author: TrevorLOlson
ms.search.form: Shortcuts
ms.topic: how-to
ms.custom:
ms.date: 07/25/2024
#customer intent: As a data engineer, I want to learn how to create an Azure Data Lake Storage Gen2 shortcut inside a Microsoft Fabric lakehouse so that I can efficiently manage and access my data.
---

# Create an Azure Data Lake Storage Gen2 shortcut

In this article, you learn how to create an Azure Data Lake Storage (ADLS) Gen2 shortcut inside a Microsoft Fabric lakehouse.

For an overview of shortcuts, see [OneLake shortcuts](onelake-shortcuts.md). To create shortcuts programmatically, see [OneLake shortcuts REST APIs](onelake-shortcuts-rest-api.md).

## Prerequisites

- If you don't have a lakehouse, create one by following these steps: [Create a lakehouse with OneLake](create-lakehouse-onelake.md).
- You must have Hierarchical Namespaces enabled on your ADLS Gen 2 storage account.

## Create a shortcut

1. Open a lakehouse.

1. Right-click on a directory within the **Lake view** of the lakehouse.

1. Select **New shortcut**.

   :::image type="content" source="media\create-onelake-shortcut\new-shortcut-lake-view.png" alt-text="The same screenshot displayed earlier showing where to select New shortcut from the Lake view.":::

[!INCLUDE [adls-gen2-shortcut](../includes/adls-gen2-shortcut.md)]

7. The lakehouse automatically refreshes. The shortcut appears in the left **Explorer** pane.

   :::image type="content" source="media\create-onelake-shortcut\folder-shortcut-symbol.png" alt-text="Screenshot showing a Lake view list of folders that display the shortcut symbol.":::

## Related content

- [Create a OneLake shortcut](create-onelake-shortcut.md)
- [Create an Amazon S3 shortcut](create-s3-shortcut.md)
- [Use OneLake shortcuts REST APIs](onelake-shortcuts-rest-api.md)
