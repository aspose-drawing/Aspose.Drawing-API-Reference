---
title: LineJoin
second_title: Aspose.Drawing för Java API‑referens
description: Anger hur på varandra följande linje- eller kurvsegment i en figurunderväg som finns i ett GraphicsPath-objekt ska förenas.
type: docs
weight: 30
url: /sv/java/com.aspose.drawing.drawing2d/linejoin/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class LineJoin extends System.Enum
```

Anger hur man förenar på varandra följande linje- eller kurvsegment i en figur (subpath) som finns i ett GraphicsPath-objekt.
## Fält

| Fält | Beskrivning |
| --- | --- |
| [Miter](#Miter) | Anger en snedskuren fog. |
| [Bevel](#Bevel) | Anger en avfasad fog. |
| [Round](#Round) | Anger en cirkulär fog. |
| [MiterClipped](#MiterClipped) | Anger en snedskuren fog. |
### Miter {#Miter}
```
public static final int Miter
```


Anger en snedskuren fog. Detta ger ett skarpt hörn eller ett avklippt hörn, beroende på om snittets längd överskrider snittgränsen.

--------------------

För närvarande fungerar Miter-fog faktiskt som MiterClipped.

### Bevel {#Bevel}
```
public static final int Bevel
```


Anger en avfasad fog. Detta ger ett diagonalt hörn.

### Round {#Round}
```
public static final int Round
```


Anger en cirkulär fog. Detta ger en jämn, cirkulär båge mellan linjerna.

### MiterClipped {#MiterClipped}
```
public static final int MiterClipped
```


Anger en snedskuren fog. Detta ger ett skarpt hörn eller ett avfasat hörn, beroende på om snittets längd överskrider snittgränsen.

