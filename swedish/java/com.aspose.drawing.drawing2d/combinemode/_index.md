---
title: CombineMode
second_title: Aspose.Drawing för Java API‑referens
description: Anger hur olika beskärningsregioner kan kombineras.
type: docs
weight: 13
url: /sv/java/com.aspose.drawing.drawing2d/combinemode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class CombineMode extends System.Enum
```

Anger hur olika beskärningsregioner kan kombineras.
## Fält

| Fält | Beskrivning |
| --- | --- |
| [Replace](#Replace) | En beskärningsregion ersätts av en annan. |
| [Intersect](#Intersect) | Två beskärningsregioner kombineras genom att ta deras skärningspunkt. |
| [Union](#Union) | Två beskärningsregioner kombineras genom att ta unionen av båda. |
| [Xor](#Xor) | Två beskärningsregioner kombineras genom att endast ta de områden som omsluts av den ena eller den andra regionen, men inte båda. |
| [Exclude](#Exclude) | Anger att den befintliga regionen ersätts av resultatet när den nya regionen tas bort från den befintliga regionen. |
| [Complement](#Complement) | Anger att den befintliga regionen ersätts av resultatet när den befintliga regionen tas bort från den nya regionen. |
### Replace {#Replace}
```
public static final int Replace
```


En beskärningsregion ersätts av en annan.

### Intersect {#Intersect}
```
public static final int Intersect
```


Två beskärningsregioner kombineras genom att ta deras skärningspunkt.

### Union {#Union}
```
public static final int Union
```


Två beskärningsregioner kombineras genom att ta unionen av båda.

### Xor {#Xor}
```
public static final int Xor
```


Två beskärningsregioner kombineras genom att endast ta de områden som omsluts av den ena eller den andra regionen, men inte båda.

### Exclude {#Exclude}
```
public static final int Exclude
```


Anger att den befintliga regionen ersätts av resultatet när den nya regionen tas bort från den befintliga regionen. Med andra ord, den nya regionen exkluderas från den befintliga regionen.

### Complement {#Complement}
```
public static final int Complement
```


Anger att den befintliga regionen ersätts av resultatet när den befintliga regionen tas bort från den nya regionen. Med andra ord, den befintliga regionen exkluderas från den nya regionen.

