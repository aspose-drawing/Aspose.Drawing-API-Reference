---
title: ColorTranslator
second_title: Riferimento API di Aspose.Drawing per Java
description: Traduce i colori da e verso le strutture GDI.
type: docs
weight: 16
url: /it/java/com.aspose.drawing/colortranslator/
---
**Inheritance:**
java.lang.Object
```
public final class ColorTranslator
```

Traduce i colori da e verso le strutture GDI+ [Color](../../com.aspose.drawing/color). Questa classe non può essere ereditata.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [ColorTranslator()](#ColorTranslator--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [fromHtml(String htmlColor)](#fromHtml-java.lang.String-) | Traduce una rappresentazione di colore HTML in una struttura GDI+ [Color](../../com.aspose.drawing/color). |
| [toHtml(Color c)](#toHtml-com.aspose.drawing.Color-) | Traduce la struttura [Color](../../com.aspose.drawing/color) specificata in una rappresentazione di colore stringa HTML. |
| [fromWin32(int win32Color)](#fromWin32-int-) | Traduce un valore di colore Windows in una struttura GDI+ [Color](../../com.aspose.drawing/color). |
| [fromOle(int oleColor)](#fromOle-int-) | Traduce un valore di colore OLE in una struttura GDI+ [Color](../../com.aspose.drawing/color). |
| [toWin32(Color c)](#toWin32-com.aspose.drawing.Color-) | Converte la struttura [Color](../../com.aspose.drawing/color) nella presentazione Win32 del colore. |
| [toOle(Color c)](#toOle-com.aspose.drawing.Color-) | Converte la struttura [Color](../../com.aspose.drawing/color) nella presentazione OLE del colore. |
### ColorTranslator() {#ColorTranslator--}
```
public ColorTranslator()
```


### fromHtml(String htmlColor) {#fromHtml-java.lang.String-}
```
public static Color fromHtml(String htmlColor)
```


Traduce una rappresentazione di colore HTML in una struttura GDI+ [Color](../../com.aspose.drawing/color).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| htmlColor | java.lang.String | La rappresentazione stringa del colore Html da tradurre. |

**Returns:**
[Color](../../com.aspose.drawing/color) - The [Color](../../com.aspose.drawing/color) structure that represents the translated HTML color or `Empty` if htmlColor is null.
### toHtml(Color c) {#toHtml-com.aspose.drawing.Color-}
```
public static String toHtml(Color c)
```


Traduce la struttura [Color](../../com.aspose.drawing/color) specificata in una rappresentazione di colore stringa HTML.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| c | [Color](../../com.aspose.drawing/color) | La struttura [Color](../../com.aspose.drawing/color) da tradurre. |

**Returns:**
java.lang.String - La stringa che rappresenta il colore HTML.
### fromWin32(int win32Color) {#fromWin32-int-}
```
public static Color fromWin32(int win32Color)
```


Traduce un valore di colore Windows in una struttura GDI+ [Color](../../com.aspose.drawing/color).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| win32Color | int | Il colore Windows da tradurre. |

**Returns:**
[Color](../../com.aspose.drawing/color) - The [Color](../../com.aspose.drawing/color) structure that represents the translated Windows color.
### fromOle(int oleColor) {#fromOle-int-}
```
public static Color fromOle(int oleColor)
```


Traduce un valore di colore OLE in una struttura GDI+ [Color](../../com.aspose.drawing/color).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| oleColor | int | Il colore OLE da tradurre. |

**Returns:**
[Color](../../com.aspose.drawing/color) - The [Color](../../com.aspose.drawing/color) structure that represents the translated OLE color.
### toWin32(Color c) {#toWin32-com.aspose.drawing.Color-}
```
public static int toWin32(Color c)
```


Converte la struttura [Color](../../com.aspose.drawing/color) nella presentazione Win32 del colore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| c | [Color](../../com.aspose.drawing/color) | Struttura [Color](../../com.aspose.drawing/color) da convertire. |

**Returns:**
int - Valore che rappresenta il formato Win32 del colore.
### toOle(Color c) {#toOle-com.aspose.drawing.Color-}
```
public static int toOle(Color c)
```


Converte la struttura [Color](../../com.aspose.drawing/color) nella presentazione OLE del colore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| c | [Color](../../com.aspose.drawing/color) | Struttura [Color](../../com.aspose.drawing/color) da convertire. |

**Returns:**
int - Valore che rappresenta il formato OLE del colore.
