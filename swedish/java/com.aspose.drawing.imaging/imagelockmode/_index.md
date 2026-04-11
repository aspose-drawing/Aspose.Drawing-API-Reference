---
title: ImageLockMode
second_title: Aspose.Drawing för Java API‑referens
description: Anger flaggor som skickas till flaggparametern för metoden.
type: docs
weight: 28
url: /sv/java/com.aspose.drawing.imaging/imagelockmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ImageLockMode extends System.Enum
```

Anger flaggor som skickas till flaggparametern för metoden [Bitmap.lockBits(Rectangle, int, int)](../../com.aspose.drawing/bitmap\#lockBits-Rectangle--int--int-). Metoden [Bitmap.lockBits(Rectangle, int, int)](../../com.aspose.drawing/bitmap\#lockBits-Rectangle--int--int-) låser en del av en bild så att du kan läsa eller skriva pixeldata.
## Fält

| Fält | Beskrivning |
| --- | --- |
| [ReadOnly](#ReadOnly) | Anger att en del av bilden är låst för läsning. |
| [WriteOnly](#WriteOnly) | Anger att en del av bilden är låst för skrivning. |
| [ReadWrite](#ReadWrite) | Anger att en del av bilden är låst för läsning eller skrivning. |
| [UserInputBuffer](#UserInputBuffer) | Anger att bufferten som används för att läsa eller skriva pixeldata allokeras av användaren. |
### ReadOnly {#ReadOnly}
```
public static final int ReadOnly
```


Anger att en del av bilden är låst för läsning.

### WriteOnly {#WriteOnly}
```
public static final int WriteOnly
```


Anger att en del av bilden är låst för skrivning.

### ReadWrite {#ReadWrite}
```
public static final int ReadWrite
```


Anger att en del av bilden är låst för läsning eller skrivning.

### UserInputBuffer {#UserInputBuffer}
```
public static final int UserInputBuffer
```


Anger att bufferten som används för att läsa eller skriva pixeldata allokeras av användaren. Om denna flagga är satt används `flags`-parametern för metoden [Bitmap.lockBits(Rectangle, int, int)](../../com.aspose.drawing/bitmap\#lockBits-Rectangle--int--int-) som en inparameter (och eventuellt som en utparameter). Om flaggan rensas används `flags`-parametern endast som en utparameter.

