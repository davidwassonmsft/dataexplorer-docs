---
title: Enable plugin command - Azure Data Explorer
description: This article describes plugins management command .enable plugin in Azure Data Explorer.
ms.reviewer: alexans
ms.topic: reference
ms.date: 11/02/2020
---
# .enable plugin

Enables a plugin.

This command requires `All Databases admin` permission.

## Syntax

`.enable` `plugin` *PluginName*

## Example

<!-- csl -->
```kusto
.enable plugin autocluster
``` 

## Next steps

* [`.disable plugin`](disable-plugin.md)
* [`.show plugins`](show-plugins.md)

