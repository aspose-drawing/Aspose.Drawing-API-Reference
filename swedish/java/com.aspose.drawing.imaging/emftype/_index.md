---
title: EmfType
second_title: Aspose.Drawing för Java API‑referens
description: Anger typen av poster som placeras i en Enhanced Metafile (EMF)-fil.
type: docs
weight: 18
url: /sv/java/com.aspose.drawing.imaging/emftype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfType extends System.Enum
```

Anger typen av poster som placeras i en Enhanced Metafile (EMF)-fil. Denna uppräkning används av flera konstruktorer i klassen [Metafile](../../com.aspose.drawing.imaging/metafile).
## Fält

| Fält | Beskrivning |
| --- | --- |
| [EmfOnly](#EmfOnly) | Anger att alla poster i metafilen är EMF-poster, vilka kan visas av GDI eller GDI+. |
| [EmfPlusOnly](#EmfPlusOnly) | Anger att alla poster i metafilen är EMF+-poster, vilka kan visas av GDI+ men inte av GDI. |
| [EmfPlusDual](#EmfPlusDual) | Anger att alla EMF+-poster i metafilen är associerade med en alternativ EMF-post. |
### EmfOnly {#EmfOnly}
```
public static final int EmfOnly
```


Anger att alla poster i metafilen är EMF-poster, vilka kan visas av GDI eller GDI+.

### EmfPlusOnly {#EmfPlusOnly}
```
public static final int EmfPlusOnly
```


Anger att alla poster i metafilen är EMF+-poster, vilka kan visas av GDI+ men inte av GDI.

### EmfPlusDual {#EmfPlusDual}
```
public static final int EmfPlusDual
```


Anger att alla EMF+-poster i metafilen är associerade med en alternativ EMF-post. Metafiler av typen `EmfType.EmfPlusDual` kan visas av GDI eller av GDI+.

