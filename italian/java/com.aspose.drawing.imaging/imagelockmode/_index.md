---
title: ImageLockMode
second_title: Riferimento API di Aspose.Drawing per Java
description: Specifica i flag che vengono passati al parametro flags del metodo.
type: docs
weight: 28
url: /it/java/com.aspose.drawing.imaging/imagelockmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ImageLockMode extends System.Enum
```

Specifica i flag che vengono passati al parametro flags del metodo [Bitmap.lockBits(Rectangle, int, int)](../../com.aspose.drawing/bitmap\#lockBits-Rectangle--int--int-). Il metodo [Bitmap.lockBits(Rectangle, int, int)](../../com.aspose.drawing/bitmap\#lockBits-Rectangle--int--int-) blocca una porzione di un'immagine in modo da poter leggere o scrivere i dati del pixel.
## Campi

| Campo | Descrizione |
| --- | --- |
| [ReadOnly](#ReadOnly) | Specifica che una porzione dell'immagine è bloccata per la lettura. |
| [WriteOnly](#WriteOnly) | Specifica che una porzione dell'immagine è bloccata per la scrittura. |
| [ReadWrite](#ReadWrite) | Specifica che una porzione dell'immagine è bloccata per la lettura o la scrittura. |
| [UserInputBuffer](#UserInputBuffer) | Specifica che il buffer utilizzato per leggere o scrivere i dati del pixel è allocato dall'utente. |
### ReadOnly {#ReadOnly}
```
public static final int ReadOnly
```


Specifica che una porzione dell'immagine è bloccata per la lettura.

### WriteOnly {#WriteOnly}
```
public static final int WriteOnly
```


Specifica che una porzione dell'immagine è bloccata per la scrittura.

### ReadWrite {#ReadWrite}
```
public static final int ReadWrite
```


Specifica che una porzione dell'immagine è bloccata per la lettura o la scrittura.

### UserInputBuffer {#UserInputBuffer}
```
public static final int UserInputBuffer
```


Specifica che il buffer utilizzato per leggere o scrivere i dati del pixel è allocato dall'utente. Se questo flag è impostato, il parametro `flags` del metodo [Bitmap.lockBits(Rectangle, int, int)](../../com.aspose.drawing/bitmap\#lockBits-Rectangle--int--int-) funge da parametro di input (e possibilmente anche da parametro di output). Se questo flag è cancellato, allora il parametro `flags` funge solo da parametro di output.

