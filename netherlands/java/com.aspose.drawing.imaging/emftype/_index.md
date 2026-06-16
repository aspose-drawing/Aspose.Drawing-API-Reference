---
title: EmfType
second_title: Aspose.Drawing voor Java API-referentie
description: Specificeert de aard van de records die in een Enhanced Metafile EMF-bestand worden geplaatst.
type: docs
weight: 18
url: /nl/java/com.aspose.drawing.imaging/emftype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfType extends System.Enum
```

Specificeert de aard van de records die in een Enhanced Metafile (EMF)-bestand worden geplaatst. Deze enumeratie wordt gebruikt door verschillende constructors in de [Metafile](../../com.aspose.drawing.imaging/metafile)-klasse.
## Velden

| Veld | Beschrijving |
| --- | --- |
| [EmfOnly](#EmfOnly) | Specificeert dat alle records in het metafile EMF-records zijn, die kunnen worden weergegeven door GDI of GDI+. |
| [EmfPlusOnly](#EmfPlusOnly) | Specificeert dat alle records in het metafile EMF+‑records zijn, die kunnen worden weergegeven door GDI+ maar niet door GDI. |
| [EmfPlusDual](#EmfPlusDual) | Specificeert dat alle EMF+‑records in het metafile zijn gekoppeld aan een alternatief EMF‑record. |
### EmfOnly {#EmfOnly}
```
public static final int EmfOnly
```


Specificeert dat alle records in het metafile EMF-records zijn, die kunnen worden weergegeven door GDI of GDI+.

### EmfPlusOnly {#EmfPlusOnly}
```
public static final int EmfPlusOnly
```


Specificeert dat alle records in het metafile EMF+‑records zijn, die kunnen worden weergegeven door GDI+ maar niet door GDI.

### EmfPlusDual {#EmfPlusDual}
```
public static final int EmfPlusDual
```


Specificeert dat alle EMF+‑records in het metafile zijn gekoppeld aan een alternatief EMF‑record. Metafiles van het type `EmfType.EmfPlusDual` kunnen worden weergegeven door GDI of door GDI+.

