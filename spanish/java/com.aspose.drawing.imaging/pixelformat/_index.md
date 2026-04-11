---
title: PixelFormat
second_title: Referencia de la API de Aspose.Drawing para Java
description: Especifica el formato de los datos de color para cada píxel en la imagen.
type: docs
weight: 34
url: /es/java/com.aspose.drawing.imaging/pixelformat/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PixelFormat extends System.Enum
```

Especifica el formato de los datos de color para cada píxel en la imagen.
## Campos

| Campo | Descripción |
| --- | --- |
| [Indexed](#Indexed) | Los datos de píxel contienen valores indexados por color, lo que significa que los valores son un índice a los colores en la tabla de colores del sistema, en lugar de valores de color individuales. |
| [Gdi](#Gdi) | Los datos de píxel contienen colores GDI. |
| [Alpha](#Alpha) | Los datos de píxel contienen valores alfa que no están premultiplicados. |
| [PAlpha](#PAlpha) | El formato de píxel contiene valores alfa premultiplicados. |
| [Extended](#Extended) | Valor reservado. |
| [Canonical](#Canonical) | El formato de píxel predeterminado de 32 bits por píxel. |
| [Undefined](#Undefined) | El formato de píxel no está definido. |
| [DontCare](#DontCare) | No se ha especificado un formato de píxel. |
| [Format1bppIndexed](#Format1bppIndexed) | Especifica que el formato de píxel es de 1 bit por píxel y que utiliza color indexado. |
| [Format4bppIndexed](#Format4bppIndexed) | Especifica que el formato es de 4 bits por píxel, indexado. |
| [Format8bppIndexed](#Format8bppIndexed) | Especifica que el formato es de 8 bits por píxel, indexado. |
| [Format16bppGrayScale](#Format16bppGrayScale) | El formato de píxel es de 16 bits por píxel. |
| [Format16bppRgb555](#Format16bppRgb555) | Especifica que el formato es de 16 bits por píxel; se utilizan 5 bits para cada uno de los componentes rojo, verde y azul. |
| [Format16bppRgb565](#Format16bppRgb565) | Especifica que el formato es de 16 bits por píxel; se utilizan 5 bits para el componente rojo, 6 bits para el componente verde y 5 bits para el componente azul. |
| [Format16bppArgb1555](#Format16bppArgb1555) | El formato de píxel es de 16 bits por píxel. |
| [Format24bppRgb](#Format24bppRgb) | Especifica que el formato es de 24 bits por píxel; 8 bits cada uno se utilizan para los componentes rojo, verde y azul. |
| [Format32bppRgb](#Format32bppRgb) | Especifica que el formato es de 32 bits por píxel; 8 bits cada uno se utilizan para los componentes rojo, verde y azul. |
| [Format32bppArgb](#Format32bppArgb) | Especifica que el formato es de 32 bits por píxel; 8 bits cada uno se utilizan para los componentes alfa, rojo, verde y azul. |
| [Format32bppPArgb](#Format32bppPArgb) | Especifica que el formato es de 32 bits por píxel; 8 bits cada uno se utilizan para los componentes alfa, rojo, verde y azul. |
| [Format48bppRgb](#Format48bppRgb) | Especifica que el formato es de 48 bits por píxel; 16 bits cada uno se utilizan para los componentes rojo, verde y azul. |
| [Format64bppArgb](#Format64bppArgb) | Especifica que el formato es de 64 bits por píxel; 16 bits cada uno se utilizan para los componentes alfa, rojo, verde y azul. |
| [Format64bppPArgb](#Format64bppPArgb) | Especifica que el formato es de 64 bits por píxel; 16 bits cada uno se utilizan para los componentes alfa, rojo, verde y azul. |
| [Max](#Max) | El valor máximo para esta enumeración. |
### Indexed {#Indexed}
```
public static final int Indexed
```


Los datos de píxel contienen valores indexados por color, lo que significa que los valores son un índice a los colores en la tabla de colores del sistema, en lugar de valores de color individuales.

### Gdi {#Gdi}
```
public static final int Gdi
```


Los datos de píxel contienen colores GDI.

### Alpha {#Alpha}
```
public static final int Alpha
```


Los datos de píxel contienen valores alfa que no están premultiplicados.

### PAlpha {#PAlpha}
```
public static final int PAlpha
```


El formato de píxel contiene valores alfa premultiplicados.

### Extended {#Extended}
```
public static final int Extended
```


Valor reservado.

### Canonical {#Canonical}
```
public static final int Canonical
```


El formato de píxel predeterminado es de 32 bits por píxel. El formato especifica una profundidad de color de 24 bits y un canal alfa de 8 bits.

### Undefined {#Undefined}
```
public static final int Undefined
```


El formato de píxel no está definido.

### DontCare {#DontCare}
```
public static final int DontCare
```


No se ha especificado un formato de píxel.

### Format1bppIndexed {#Format1bppIndexed}
```
public static final int Format1bppIndexed
```


Especifica que el formato de píxel es de 1 bit por píxel y que utiliza color indexado. Por lo tanto, la tabla de colores contiene dos colores.

### Format4bppIndexed {#Format4bppIndexed}
```
public static final int Format4bppIndexed
```


Especifica que el formato es de 4 bits por píxel, indexado.

### Format8bppIndexed {#Format8bppIndexed}
```
public static final int Format8bppIndexed
```


Especifica que el formato es de 8 bits por píxel, indexado. Por lo tanto, la tabla de colores contiene 256 colores.

### Format16bppGrayScale {#Format16bppGrayScale}
```
public static final int Format16bppGrayScale
```


El formato de píxel es de 16 bits por píxel. La información de color especifica 65 536 tonos de gris.

### Format16bppRgb555 {#Format16bppRgb555}
```
public static final int Format16bppRgb555
```


Especifica que el formato es de 16 bits por píxel; 5 bits cada uno se utilizan para los componentes rojo, verde y azul. El bit restante no se utiliza.

### Format16bppRgb565 {#Format16bppRgb565}
```
public static final int Format16bppRgb565
```


Especifica que el formato es de 16 bits por píxel; se utilizan 5 bits para el componente rojo, 6 bits para el componente verde y 5 bits para el componente azul.

### Format16bppArgb1555 {#Format16bppArgb1555}
```
public static final int Format16bppArgb1555
```


El formato de píxel es de 16 bits por píxel. La información de color especifica 32 768 tonos de color, de los cuales 5 bits son rojo, 5 bits son verde, 5 bits son azul y 1 bit es alfa.

### Format24bppRgb {#Format24bppRgb}
```
public static final int Format24bppRgb
```


Especifica que el formato es de 24 bits por píxel; 8 bits cada uno se utilizan para los componentes rojo, verde y azul.

### Format32bppRgb {#Format32bppRgb}
```
public static final int Format32bppRgb
```


Especifica que el formato es de 32 bits por píxel; 8 bits cada uno se utilizan para los componentes rojo, verde y azul. Los 8 bits restantes no se utilizan.

### Format32bppArgb {#Format32bppArgb}
```
public static final int Format32bppArgb
```


Especifica que el formato es de 32 bits por píxel; 8 bits cada uno se utilizan para los componentes alfa, rojo, verde y azul.

### Format32bppPArgb {#Format32bppPArgb}
```
public static final int Format32bppPArgb
```


Especifica que el formato es de 32 bits por píxel; 8 bits cada uno se utilizan para los componentes alfa, rojo, verde y azul. Los componentes rojo, verde y azul están premultiplicados, según el componente alfa.

### Format48bppRgb {#Format48bppRgb}
```
public static final int Format48bppRgb
```


Especifica que el formato es de 48 bits por píxel; 16 bits cada uno se utilizan para los componentes rojo, verde y azul.

### Format64bppArgb {#Format64bppArgb}
```
public static final int Format64bppArgb
```


Especifica que el formato es de 64 bits por píxel; 16 bits cada uno se utilizan para los componentes alfa, rojo, verde y azul.

### Format64bppPArgb {#Format64bppPArgb}
```
public static final int Format64bppPArgb
```


Especifica que el formato es de 64 bits por píxel; 16 bits cada uno se utilizan para los componentes alfa, rojo, verde y azul. Los componentes rojo, verde y azul están premultiplicados según el componente alfa.

### Max {#Max}
```
public static final int Max
```


El valor máximo para esta enumeración.

