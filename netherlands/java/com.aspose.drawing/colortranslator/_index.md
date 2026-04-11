---
title: ColorTranslator
second_title: Aspose.Drawing voor Java API-referentie
description: Vertaal kleuren naar en van GDI-structuren.
type: docs
weight: 16
url: /nl/java/com.aspose.drawing/colortranslator/
---
**Inheritance:**
java.lang.Object
```
public final class ColorTranslator
```

Vertaal kleuren naar en van GDI+ [Color](../../com.aspose.drawing/color)-structuren. Deze klasse kan niet worden geërfd.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [ColorTranslator()](#ColorTranslator--) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [fromHtml(String htmlColor)](#fromHtml-java.lang.String-) | Vertaal een HTML-kleurrepresentatie naar een GDI+ [Color](../../com.aspose.drawing/color)-structuur. |
| [toHtml(Color c)](#toHtml-com.aspose.drawing.Color-) | Vertaal de opgegeven [Color](../../com.aspose.drawing/color)-structuur naar een HTML‑tekenreeks kleurrepresentatie. |
| [fromWin32(int win32Color)](#fromWin32-int-) | Vertaal een Windows-kleurwaarde naar een GDI+ [Color](../../com.aspose.drawing/color)-structuur. |
| [fromOle(int oleColor)](#fromOle-int-) | Vertaal een OLE-kleurwaarde naar een GDI+ [Color](../../com.aspose.drawing/color)-structuur. |
| [toWin32(Color c)](#toWin32-com.aspose.drawing.Color-) | Converteert de [Color](../../com.aspose.drawing/color)-structuur naar Win32-presentatie van kleur. |
| [toOle(Color c)](#toOle-com.aspose.drawing.Color-) | Converteert de [Color](../../com.aspose.drawing/color)-structuur naar OLE-presentatie van kleur. |
### ColorTranslator() {#ColorTranslator--}
```
public ColorTranslator()
```


### fromHtml(String htmlColor) {#fromHtml-java.lang.String-}
```
public static Color fromHtml(String htmlColor)
```


Vertaal een HTML-kleurrepresentatie naar een GDI+ [Color](../../com.aspose.drawing/color)-structuur.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| htmlColor | java.lang.String | De tekenreeksrepresentatie van de Html-kleur die moet worden vertaald. |

**Returns:**
[Color](../../com.aspose.drawing/color) - The [Color](../../com.aspose.drawing/color) structure that represents the translated HTML color or `Empty` if htmlColor is null.
### toHtml(Color c) {#toHtml-com.aspose.drawing.Color-}
```
public static String toHtml(Color c)
```


Vertaal de opgegeven [Color](../../com.aspose.drawing/color)-structuur naar een HTML‑tekenreeks kleurrepresentatie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| c | [Color](../../com.aspose.drawing/color) | De [Color](../../com.aspose.drawing/color) structuur om te vertalen. |

**Returns:**
java.lang.String - De string die de HTML-kleur vertegenwoordigt.
### fromWin32(int win32Color) {#fromWin32-int-}
```
public static Color fromWin32(int win32Color)
```


Vertaal een Windows-kleurwaarde naar een GDI+ [Color](../../com.aspose.drawing/color)-structuur.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| win32Color | int | De Windows-kleur om te vertalen. |

**Returns:**
[Color](../../com.aspose.drawing/color) - The [Color](../../com.aspose.drawing/color) structure that represents the translated Windows color.
### fromOle(int oleColor) {#fromOle-int-}
```
public static Color fromOle(int oleColor)
```


Vertaal een OLE-kleurwaarde naar een GDI+ [Color](../../com.aspose.drawing/color)-structuur.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| oleColor | int | De OLE-kleur om te vertalen. |

**Returns:**
[Color](../../com.aspose.drawing/color) - The [Color](../../com.aspose.drawing/color) structure that represents the translated OLE color.
### toWin32(Color c) {#toWin32-com.aspose.drawing.Color-}
```
public static int toWin32(Color c)
```


Converteert de [Color](../../com.aspose.drawing/color)-structuur naar Win32-presentatie van kleur.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| c | [Color](../../com.aspose.drawing/color) | De [Color](../../com.aspose.drawing/color) structuur om te converteren. |

**Returns:**
int - Waarde die het Win32-formaat van kleur vertegenwoordigt.
### toOle(Color c) {#toOle-com.aspose.drawing.Color-}
```
public static int toOle(Color c)
```


Converteert de [Color](../../com.aspose.drawing/color)-structuur naar OLE-presentatie van kleur.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| c | [Color](../../com.aspose.drawing/color) | De [Color](../../com.aspose.drawing/color) structuur om te converteren. |

**Returns:**
int - Waarde die het OLE-formaat van kleur vertegenwoordigt.
