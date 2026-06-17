---
title: ColorTranslator
second_title: Référence de l'API Aspose.Drawing pour Java
description: Traduit les couleurs vers et depuis les structures GDI.
type: docs
weight: 16
url: /fr/java/com.aspose.drawing/colortranslator/
---
**Inheritance:**
java.lang.Object
```
public final class ColorTranslator
```

Traduit les couleurs vers et depuis les structures GDI+ [Color](../../com.aspose.drawing/color). Cette classe ne peut pas être héritée.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [ColorTranslator()](#ColorTranslator--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [fromHtml(String htmlColor)](#fromHtml-java.lang.String-) | Traduit une représentation de couleur HTML en une structure GDI+ [Color](../../com.aspose.drawing/color). |
| [toHtml(Color c)](#toHtml-com.aspose.drawing.Color-) | Traduit la structure [Color](../../com.aspose.drawing/color) spécifiée en une représentation de couleur sous forme de chaîne HTML. |
| [fromWin32(int win32Color)](#fromWin32-int-) | Traduit une valeur de couleur Windows en une structure GDI+ [Color](../../com.aspose.drawing/color). |
| [fromOle(int oleColor)](#fromOle-int-) | Traduit une valeur de couleur OLE en une structure GDI+ [Color](../../com.aspose.drawing/color). |
| [toWin32(Color c)](#toWin32-com.aspose.drawing.Color-) | Convertit la structure [Color](../../com.aspose.drawing/color) en présentation Win32 de la couleur. |
| [toOle(Color c)](#toOle-com.aspose.drawing.Color-) | Convertit la structure [Color](../../com.aspose.drawing/color) en présentation OLE de la couleur. |
### ColorTranslator() {#ColorTranslator--}
```
public ColorTranslator()
```


### fromHtml(String htmlColor) {#fromHtml-java.lang.String-}
```
public static Color fromHtml(String htmlColor)
```


Traduit une représentation de couleur HTML en une structure GDI+ [Color](../../com.aspose.drawing/color).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| htmlColor | java.lang.String | La représentation sous forme de chaîne de la couleur Html à traduire. |

**Returns:**
[Color](../../com.aspose.drawing/color) - The [Color](../../com.aspose.drawing/color) structure that represents the translated HTML color or `Empty` if htmlColor is null.
### toHtml(Color c) {#toHtml-com.aspose.drawing.Color-}
```
public static String toHtml(Color c)
```


Traduit la structure [Color](../../com.aspose.drawing/color) spécifiée en une représentation de couleur sous forme de chaîne HTML.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| c | [Color](../../com.aspose.drawing/color) | La structure [Color](../../com.aspose.drawing/color) à traduire. |

**Returns:**
java.lang.String - La chaîne qui représente la couleur HTML.
### fromWin32(int win32Color) {#fromWin32-int-}
```
public static Color fromWin32(int win32Color)
```


Traduit une valeur de couleur Windows en une structure GDI+ [Color](../../com.aspose.drawing/color).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| win32Color | int | La couleur Windows à traduire. |

**Returns:**
[Color](../../com.aspose.drawing/color) - The [Color](../../com.aspose.drawing/color) structure that represents the translated Windows color.
### fromOle(int oleColor) {#fromOle-int-}
```
public static Color fromOle(int oleColor)
```


Traduit une valeur de couleur OLE en une structure GDI+ [Color](../../com.aspose.drawing/color).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| oleColor | int | La couleur OLE à traduire. |

**Returns:**
[Color](../../com.aspose.drawing/color) - The [Color](../../com.aspose.drawing/color) structure that represents the translated OLE color.
### toWin32(Color c) {#toWin32-com.aspose.drawing.Color-}
```
public static int toWin32(Color c)
```


Convertit la structure [Color](../../com.aspose.drawing/color) en présentation Win32 de la couleur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| c | [Color](../../com.aspose.drawing/color) | Structure [Color](../../com.aspose.drawing/color) à convertir. |

**Returns:**
int - Valeur qui représente le format Win32 de la couleur.
### toOle(Color c) {#toOle-com.aspose.drawing.Color-}
```
public static int toOle(Color c)
```


Convertit la structure [Color](../../com.aspose.drawing/color) en présentation OLE de la couleur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| c | [Color](../../com.aspose.drawing/color) | Structure [Color](../../com.aspose.drawing/color) à convertir. |

**Returns:**
int - Valeur qui représente le format OLE de la couleur.
