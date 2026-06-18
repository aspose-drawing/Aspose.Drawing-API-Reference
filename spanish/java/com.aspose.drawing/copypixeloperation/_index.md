---
title: CopyPixelOperation
second_title: Referencia de la API de Aspose.Drawing para Java
description: Determina cómo se combina el color de origen en una operación de copia de píxel con el color de destino para obtener un color final.
type: docs
weight: 18
url: /es/java/com.aspose.drawing/copypixeloperation/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class CopyPixelOperation extends System.Enum
```

Determina cómo se combina el color de origen en una operación de copia de píxel con el color de destino para obtener un color final.
## Campos

| Campo | Descripción |
| --- | --- |
| [NoMirrorBitmap](#NoMirrorBitmap) | El mapa de bits no está reflejado. |
| [Blackness](#Blackness) | El área de destino se rellena usando el color asociado al índice 0 en la paleta física. |
| [NotSourceErase](#NotSourceErase) | Los colores de origen y destino se combinan usando el operador booleano `OR`, y luego el color resultante se invierte. |
| [NotSourceCopy](#NotSourceCopy) | El área de origen invertida se copia al destino. |
| [SourceErase](#SourceErase) | Los colores invertidos del área de destino se combinan con los colores del área de origen usando el operador booleano `AND`. |
| [DestinationInvert](#DestinationInvert) | El área de destino se invierte. |
| [PatInvert](#PatInvert) | Los colores del pincel actualmente seleccionado en el contexto del dispositivo de destino se combinan con los colores del destino usando el operador booleano `XOR`. |
| [SourceInvert](#SourceInvert) | Los colores de las áreas de origen y destino se combinan usando el operador booleano `XOR`. |
| [SourceAnd](#SourceAnd) | Los colores de las áreas de origen y destino se combinan usando el operador booleano `AND`. |
| [MergePaint](#MergePaint) | Los colores del área de origen invertida se fusionan con los colores del área de destino usando el operador booleano `OR`. |
| [MergeCopy](#MergeCopy) | Los colores del área de origen se fusionan con los colores del pincel seleccionado del contexto del dispositivo de destino usando el operador booleano `AND`. |
| [SourceCopy](#SourceCopy) | El área de origen se copia directamente al área de destino. |
| [SourcePaint](#SourcePaint) | Los colores de las áreas de origen y destino se combinan usando el operador booleano `OR`. |
| [PatCopy](#PatCopy) | El pincel actualmente seleccionado en el contexto del dispositivo de destino se copia al mapa de bits de destino. |
| [PatPaint](#PatPaint) | Los colores del pincel actualmente seleccionado en el contexto del dispositivo de destino se combinan con los colores del área de origen invertida usando el operador booleano `OR`. |
| [Whiteness](#Whiteness) | El área de destino se rellena usando el color asociado al índice 1 en la paleta física. |
| [CaptureBlt](#CaptureBlt) | Las ventanas que se superponen encima de su ventana se incluyen en la imagen resultante. |
### NoMirrorBitmap {#NoMirrorBitmap}
```
public static final int NoMirrorBitmap
```


El mapa de bits no está reflejado.

### Blackness {#Blackness}
```
public static final int Blackness
```


El área de destino se rellena usando el color asociado al índice 0 en la paleta física. (Este color es negro para la paleta física predeterminada.)

### NotSourceErase {#NotSourceErase}
```
public static final int NotSourceErase
```


Los colores de origen y destino se combinan usando el operador booleano `OR`, y luego el color resultante se invierte.

### NotSourceCopy {#NotSourceCopy}
```
public static final int NotSourceCopy
```


El área de origen invertida se copia al destino.

### SourceErase {#SourceErase}
```
public static final int SourceErase
```


Los colores invertidos del área de destino se combinan con los colores del área de origen usando el operador booleano `AND`.

### DestinationInvert {#DestinationInvert}
```
public static final int DestinationInvert
```


El área de destino se invierte.

### PatInvert {#PatInvert}
```
public static final int PatInvert
```


Los colores del pincel actualmente seleccionado en el contexto del dispositivo de destino se combinan con los colores del destino usando el operador booleano `XOR`.

### SourceInvert {#SourceInvert}
```
public static final int SourceInvert
```


Los colores de las áreas de origen y destino se combinan usando el operador booleano `XOR`.

### SourceAnd {#SourceAnd}
```
public static final int SourceAnd
```


Los colores de las áreas de origen y destino se combinan usando el operador booleano `AND`.

### MergePaint {#MergePaint}
```
public static final int MergePaint
```


Los colores del área de origen invertida se fusionan con los colores del área de destino usando el operador booleano `OR`.

### MergeCopy {#MergeCopy}
```
public static final int MergeCopy
```


Los colores del área de origen se fusionan con los colores del pincel seleccionado del contexto del dispositivo de destino usando el operador booleano `AND`.

### SourceCopy {#SourceCopy}
```
public static final int SourceCopy
```


El área de origen se copia directamente al área de destino.

### SourcePaint {#SourcePaint}
```
public static final int SourcePaint
```


Los colores de las áreas de origen y destino se combinan usando el operador booleano `OR`.

### PatCopy {#PatCopy}
```
public static final int PatCopy
```


El pincel actualmente seleccionado en el contexto del dispositivo de destino se copia al mapa de bits de destino.

### PatPaint {#PatPaint}
```
public static final int PatPaint
```


Los colores del pincel actualmente seleccionado en el contexto de dispositivo de destino se combinan con los colores del área de origen invertida usando el operador booleano `OR`. El resultado de esta operación se combina con los colores del área de destino usando el operador booleano `OR`.

### Whiteness {#Whiteness}
```
public static final int Whiteness
```


El área de destino se rellena usando el color asociado al índice 1 en la paleta física. (Este color es blanco para la paleta física predeterminada.)

### CaptureBlt {#CaptureBlt}
```
public static final int CaptureBlt
```


Las ventanas que se superponen encima de su ventana se incluyen en la imagen resultante. Por defecto, la imagen contiene solo su ventana. Tenga en cuenta que generalmente no se puede usar para contextos de dispositivo de impresión.

