---
title: ImageLockMode
second_title: Referencia de la API de Aspose.Drawing para Java
description: Especifica los indicadores que se pasan al parámetro flags del método.
type: docs
weight: 28
url: /es/java/com.aspose.drawing.imaging/imagelockmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ImageLockMode extends System.Enum
```

Especifica los indicadores que se pasan al parámetro flags del método [Bitmap.lockBits(Rectangle, int, int)](../../com.aspose.drawing/bitmap\#lockBits-Rectangle--int--int-). El método [Bitmap.lockBits(Rectangle, int, int)](../../com.aspose.drawing/bitmap\#lockBits-Rectangle--int--int-) bloquea una parte de una imagen para que pueda leer o escribir los datos de píxeles.
## Campos

| Campo | Descripción |
| --- | --- |
| [ReadOnly](#ReadOnly) | Especifica que una parte de la imagen está bloqueada para lectura. |
| [WriteOnly](#WriteOnly) | Especifica que una parte de la imagen está bloqueada para escritura. |
| [ReadWrite](#ReadWrite) | Especifica que una parte de la imagen está bloqueada para lectura o escritura. |
| [UserInputBuffer](#UserInputBuffer) | Especifica que el búfer utilizado para leer o escribir datos de píxeles es asignado por el usuario. |
### ReadOnly {#ReadOnly}
```
public static final int ReadOnly
```


Especifica que una parte de la imagen está bloqueada para lectura.

### WriteOnly {#WriteOnly}
```
public static final int WriteOnly
```


Especifica que una parte de la imagen está bloqueada para escritura.

### ReadWrite {#ReadWrite}
```
public static final int ReadWrite
```


Especifica que una parte de la imagen está bloqueada para lectura o escritura.

### UserInputBuffer {#UserInputBuffer}
```
public static final int UserInputBuffer
```


Especifica que el búfer utilizado para leer o escribir datos de píxeles es asignado por el usuario. Si este indicador está activado, el parámetro `flags` del método [Bitmap.lockBits(Rectangle, int, int)](../../com.aspose.drawing/bitmap\#lockBits-Rectangle--int--int-) funciona como un parámetro de entrada (y posiblemente como un parámetro de salida). Si este indicador se desactiva, entonces el parámetro `flags` sirve solo como parámetro de salida.

