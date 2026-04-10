---
title: CombineMode
second_title: Aspose.Drawing für Java API-Referenz
description: Gibt an, wie verschiedene Clipping‑Regionen kombiniert werden können.
type: docs
weight: 13
url: /de/java/com.aspose.drawing.drawing2d/combinemode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class CombineMode extends System.Enum
```

Gibt an, wie verschiedene Clipping‑Regionen kombiniert werden können.
## Felder

| Feld | Beschreibung |
| --- | --- |
| [Replace](#Replace) | Eine Clipping‑Region wird durch eine andere ersetzt. |
| [Intersect](#Intersect) | Zwei Clipping‑Regionen werden durch Bilden ihrer Schnittmenge kombiniert. |
| [Union](#Union) | Zwei Clipping‑Regionen werden durch Bilden ihrer Vereinigung kombiniert. |
| [Xor](#Xor) | Zwei Clipping‑Regionen werden kombiniert, indem nur die Flächen genommen werden, die von einer der beiden Regionen eingeschlossen sind, jedoch nicht von beiden. |
| [Exclude](#Exclude) | Gibt an, dass die vorhandene Region durch das Ergebnis ersetzt wird, das entsteht, wenn die neue Region von der vorhandenen Region entfernt wird. |
| [Complement](#Complement) | Gibt an, dass die vorhandene Region durch das Ergebnis ersetzt wird, das entsteht, wenn die vorhandene Region von der neuen Region entfernt wird. |
### Replace {#Replace}
```
public static final int Replace
```


Eine Clipping‑Region wird durch eine andere ersetzt.

### Intersect {#Intersect}
```
public static final int Intersect
```


Zwei Clipping‑Regionen werden durch Bilden ihrer Schnittmenge kombiniert.

### Union {#Union}
```
public static final int Union
```


Zwei Clipping‑Regionen werden durch Bilden ihrer Vereinigung kombiniert.

### Xor {#Xor}
```
public static final int Xor
```


Zwei Clipping‑Regionen werden kombiniert, indem nur die Flächen genommen werden, die von einer der beiden Regionen eingeschlossen sind, jedoch nicht von beiden.

### Exclude {#Exclude}
```
public static final int Exclude
```


Gibt an, dass die vorhandene Region durch das Ergebnis ersetzt wird, das entsteht, wenn die neue Region von der vorhandenen Region entfernt wird. Anders ausgedrückt, die neue Region wird von der vorhandenen Region ausgeschlossen.

### Complement {#Complement}
```
public static final int Complement
```


Gibt an, dass die vorhandene Region durch das Ergebnis ersetzt wird, das entsteht, wenn die vorhandene Region von der neuen Region entfernt wird. Anders ausgedrückt, die vorhandene Region wird von der neuen Region ausgeschlossen.

