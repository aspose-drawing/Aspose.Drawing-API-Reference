---
title: ImageLockMode
second_title: Aspose.Drawing für Java API-Referenz
description: Gibt Flags an, die an den flags-Parameter der Methode übergeben werden.
type: docs
weight: 28
url: /de/java/com.aspose.drawing.imaging/imagelockmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ImageLockMode extends System.Enum
```

Gibt Flags an, die an den flags-Parameter der [Bitmap.lockBits(Rectangle, int, int)](../../com.aspose.drawing/bitmap\#lockBits-Rectangle--int--int-) Methode übergeben werden. Die [Bitmap.lockBits(Rectangle, int, int)](../../com.aspose.drawing/bitmap\#lockBits-Rectangle--int--int-) Methode sperrt einen Bildbereich, sodass Sie die Pixeldaten lesen oder schreiben können.
## Felder

| Feld | Beschreibung |
| --- | --- |
| [ReadOnly](#ReadOnly) | Gibt an, dass ein Bildbereich zum Lesen gesperrt ist. |
| [WriteOnly](#WriteOnly) | Gibt an, dass ein Bildbereich zum Schreiben gesperrt ist. |
| [ReadWrite](#ReadWrite) | Gibt an, dass ein Bildbereich zum Lesen oder Schreiben gesperrt ist. |
| [UserInputBuffer](#UserInputBuffer) | Gibt an, dass der Puffer, der zum Lesen oder Schreiben von Pixeldaten verwendet wird, vom Benutzer zugewiesen wird. |
### ReadOnly {#ReadOnly}
```
public static final int ReadOnly
```


Gibt an, dass ein Bildbereich zum Lesen gesperrt ist.

### WriteOnly {#WriteOnly}
```
public static final int WriteOnly
```


Gibt an, dass ein Bildbereich zum Schreiben gesperrt ist.

### ReadWrite {#ReadWrite}
```
public static final int ReadWrite
```


Gibt an, dass ein Bildbereich zum Lesen oder Schreiben gesperrt ist.

### UserInputBuffer {#UserInputBuffer}
```
public static final int UserInputBuffer
```


Gibt an, dass der Puffer, der zum Lesen oder Schreiben von Pixeldaten verwendet wird, vom Benutzer zugewiesen wird. Wenn dieses Flag gesetzt ist, dient der `flags`‑Parameter der [Bitmap.lockBits(Rectangle, int, int)](../../com.aspose.drawing/bitmap\#lockBits-Rectangle--int--int-) Methode als Eingabeparameter (und möglicherweise auch als Ausgabeparameter). Wenn dieses Flag gelöscht wird, dient der `flags`‑Parameter nur als Ausgabeparameter.

