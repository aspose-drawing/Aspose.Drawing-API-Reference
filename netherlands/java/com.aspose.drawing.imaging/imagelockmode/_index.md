---
title: ImageLockMode
second_title: Aspose.Drawing voor Java API-referentie
description: Geeft vlaggen op die worden doorgegeven aan de vlaggenparameter van de  methode.
type: docs
weight: 28
url: /nl/java/com.aspose.drawing.imaging/imagelockmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ImageLockMode extends System.Enum
```

Geeft vlaggen op die worden doorgegeven aan de vlaggenparameter van de [Bitmap.lockBits(Rectangle, int, int)](../../com.aspose.drawing/bitmap\#lockBits-Rectangle--int--int-) methode. De [Bitmap.lockBits(Rectangle, int, int)](../../com.aspose.drawing/bitmap\#lockBits-Rectangle--int--int-) methode vergrendelt een deel van een afbeelding zodat u de pixelgegevens kunt lezen of schrijven.
## Velden

| Veld | Beschrijving |
| --- | --- |
| [ReadOnly](#ReadOnly) | Geeft aan dat een deel van de afbeelding is vergrendeld voor lezen. |
| [WriteOnly](#WriteOnly) | Geeft aan dat een deel van de afbeelding is vergrendeld voor schrijven. |
| [ReadWrite](#ReadWrite) | Geeft aan dat een deel van de afbeelding is vergrendeld voor lezen of schrijven. |
| [UserInputBuffer](#UserInputBuffer) | Geeft aan dat de buffer die wordt gebruikt voor het lezen of schrijven van pixelgegevens door de gebruiker wordt toegewezen. |
### ReadOnly {#ReadOnly}
```
public static final int ReadOnly
```


Geeft aan dat een deel van de afbeelding is vergrendeld voor lezen.

### WriteOnly {#WriteOnly}
```
public static final int WriteOnly
```


Geeft aan dat een deel van de afbeelding is vergrendeld voor schrijven.

### ReadWrite {#ReadWrite}
```
public static final int ReadWrite
```


Geeft aan dat een deel van de afbeelding is vergrendeld voor lezen of schrijven.

### UserInputBuffer {#UserInputBuffer}
```
public static final int UserInputBuffer
```


Geeft aan dat de buffer die wordt gebruikt voor het lezen of schrijven van pixelgegevens door de gebruiker wordt toegewezen. Als deze vlag is ingesteld, dient de `flags`-parameter van de [Bitmap.lockBits(Rectangle, int, int)](../../com.aspose.drawing/bitmap\#lockBits-Rectangle--int--int-) methode als invoerparameter (en mogelijk als uitvoerparameter). Als deze vlag wordt gewist, dient de `flags`-parameter alleen als uitvoerparameter.

