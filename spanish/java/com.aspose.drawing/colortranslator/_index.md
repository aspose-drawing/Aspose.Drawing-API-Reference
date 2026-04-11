---
title: ColorTranslator
second_title: Referencia de la API de Aspose.Drawing para Java
description: Traduce colores a y desde estructuras GDI.
type: docs
weight: 16
url: /es/java/com.aspose.drawing/colortranslator/
---
**Inheritance:**
java.lang.Object
```
public final class ColorTranslator
```

Traduce colores a y desde estructuras GDI+ [Color](../../com.aspose.drawing/color). Esta clase no puede heredarse.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [ColorTranslator()](#ColorTranslator--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [fromHtml(String htmlColor)](#fromHtml-java.lang.String-) | Traduce una representación de color HTML a una estructura GDI+ [Color](../../com.aspose.drawing/color). |
| [toHtml(Color c)](#toHtml-com.aspose.drawing.Color-) | Traduce la estructura [Color](../../com.aspose.drawing/color) especificada a una representación de color en cadena HTML. |
| [fromWin32(int win32Color)](#fromWin32-int-) | Traduce un valor de color de Windows a una estructura GDI+ [Color](../../com.aspose.drawing/color). |
| [fromOle(int oleColor)](#fromOle-int-) | Traduce un valor de color OLE a una estructura GDI+ [Color](../../com.aspose.drawing/color). |
| [toWin32(Color c)](#toWin32-com.aspose.drawing.Color-) | Convierte la estructura [Color](../../com.aspose.drawing/color) a la presentación Win32 del color. |
| [toOle(Color c)](#toOle-com.aspose.drawing.Color-) | Convierte la estructura [Color](../../com.aspose.drawing/color) a la presentación OLE del color. |
### ColorTranslator() {#ColorTranslator--}
```
public ColorTranslator()
```


### fromHtml(String htmlColor) {#fromHtml-java.lang.String-}
```
public static Color fromHtml(String htmlColor)
```


Traduce una representación de color HTML a una estructura GDI+ [Color](../../com.aspose.drawing/color).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| htmlColor | java.lang.String | La representación en cadena del color Html a traducir. |

**Returns:**
[Color](../../com.aspose.drawing/color) - The [Color](../../com.aspose.drawing/color) structure that represents the translated HTML color or `Empty` if htmlColor is null.
### toHtml(Color c) {#toHtml-com.aspose.drawing.Color-}
```
public static String toHtml(Color c)
```


Traduce la estructura [Color](../../com.aspose.drawing/color) especificada a una representación de color en cadena HTML.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| c | [Color](../../com.aspose.drawing/color) | La estructura [Color](../../com.aspose.drawing/color) para traducir. |

**Returns:**
java.lang.String - La cadena que representa el color HTML.
### fromWin32(int win32Color) {#fromWin32-int-}
```
public static Color fromWin32(int win32Color)
```


Traduce un valor de color de Windows a una estructura GDI+ [Color](../../com.aspose.drawing/color).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| win32Color | int | El color de Windows para traducir. |

**Returns:**
[Color](../../com.aspose.drawing/color) - The [Color](../../com.aspose.drawing/color) structure that represents the translated Windows color.
### fromOle(int oleColor) {#fromOle-int-}
```
public static Color fromOle(int oleColor)
```


Traduce un valor de color OLE a una estructura GDI+ [Color](../../com.aspose.drawing/color).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| oleColor | int | El color OLE para traducir. |

**Returns:**
[Color](../../com.aspose.drawing/color) - The [Color](../../com.aspose.drawing/color) structure that represents the translated OLE color.
### toWin32(Color c) {#toWin32-com.aspose.drawing.Color-}
```
public static int toWin32(Color c)
```


Convierte la estructura [Color](../../com.aspose.drawing/color) a la presentación Win32 del color.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| c | [Color](../../com.aspose.drawing/color) | La estructura [Color](../../com.aspose.drawing/color) para convertir. |

**Returns:**
int - Valor que representa el formato Win32 del color.
### toOle(Color c) {#toOle-com.aspose.drawing.Color-}
```
public static int toOle(Color c)
```


Convierte la estructura [Color](../../com.aspose.drawing/color) a la presentación OLE del color.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| c | [Color](../../com.aspose.drawing/color) | La estructura [Color](../../com.aspose.drawing/color) para convertir. |

**Returns:**
int - Valor que representa el formato OLE del color.
