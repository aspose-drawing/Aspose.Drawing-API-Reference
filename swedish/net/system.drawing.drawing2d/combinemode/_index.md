---
title: CombineMode
second_title: Aspose.Drawing för .NET API Referens
description: Anger hur olika klippområden kan kombineras.
type: docs
weight: 160
url: /sv/net/system.drawing.drawing2d/combinemode/
---
## CombineMode enumeration

Anger hur olika klippområden kan kombineras.

```csharp
public enum CombineMode
```

### Värderingar

| namn | Värde | Beskrivning |
| --- | --- | --- |
| Replace | `0` | Ett klippområde ersätts av ett annat. |
| Intersect | `1` | Två klippområden kombineras genom att ta deras skärningspunkt. |
| Union | `2` | Två klippområden kombineras genom att ta föreningen av båda. |
| Xor | `3` | Två klippområden kombineras genom att endast ta de områden som omges av den ena eller andra regionen, men inte båda. |
| Exclude | `4` | Anger att den befintliga regionen ersätts av resultatet av att den nya regionen har tagits bort från den befintliga regionen. Sagt annorlunda, den nya regionen exkluderas från den befintliga regionen. |
| Complement | `5` | Anger att den befintliga regionen ersätts av resultatet av att den befintliga regionen har tagits bort från den nya regionen. Sagt annorlunda, den befintliga regionen exkluderas från den nya regionen. |

### Se även

* namnutrymme [System.Drawing.Drawing2D](../../system.drawing.drawing2d)
* hopsättning [Aspose.Drawing](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Drawing.dll -->