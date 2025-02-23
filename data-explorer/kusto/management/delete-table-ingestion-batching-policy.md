---
title: .delete table ingestion batching policy command - Azure Data Explorer
description: This article describes the .delete table ingestion batching policy command in Azure Data Explorer.
services: data-explorer
author: orspod
ms.author: orspodek
ms.reviewer: yonil
ms.service: data-explorer
ms.topic: reference
ms.date: 12/15/2021
---
# .delete table ingestion batching policy

Remove the table [ingestion batching policy](batchingpolicy.md) that defines data aggregation for batching.

## Syntax

`.delete` `table` *TableName* `policy` `ingestionbatching`

## Arguments

*TableName* - Specify the name of the table.

## Example

The following command deletes the batching policy on a table.

```kusto
.delete table MyTable policy ingestionbatching
```

## Next steps

* [delete database batching policy](delete-database-ingestion-batching-policy.md)