---
title: ColorTranslator
second_title: Aspose.Drawing för Java API‑referens
description: Översätter färger till och från GDI‑strukturer.
type: docs
weight: 16
url: /sv/java/com.aspose.drawing/colortranslator/
---
**Inheritance:**
java.lang.Object
```
public final class ColorTranslator
```

Översätter färger till och från GDI+ [Color](../../com.aspose.drawing/color)‑strukturer. Denna klass kan inte ärvas.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [ColorTranslator()](#ColorTranslator--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [fromHtml(String htmlColor)](#fromHtml-java.lang.String-) | Översätter en HTML‑färgrepresentation till en GDI+ [Color](../../com.aspose.drawing/color)‑struktur. |
| [toHtml(Color c)](#toHtml-com.aspose.drawing.Color-) | Översätter den angivna [Color](../../com.aspose.drawing/color)‑strukturen till en HTML‑strängfärgrepresentation. |
| [fromWin32(int win32Color)](#fromWin32-int-) | Översätter ett Windows‑färgvärde till en GDI+ [Color](../../com.aspose.drawing/color)‑struktur. |
| [fromOle(int oleColor)](#fromOle-int-) | Översätter ett OLE‑färgvärde till en GDI+ [Color](../../com.aspose.drawing/color)‑struktur. |
| [toWin32(Color c)](#toWin32-com.aspose.drawing.Color-) | Konverterar [Color](../../com.aspose.drawing/color)‑struktur till Win32‑presentation av färg. |
| [toOle(Color c)](#toOle-com.aspose.drawing.Color-) | Konverterar [Color](../../com.aspose.drawing/color)‑struktur till OLE‑presentation av färg. |
### ColorTranslator() {#ColorTranslator--}
```
public ColorTranslator()
```


### fromHtml(String htmlColor) {#fromHtml-java.lang.String-}
```
public static Color fromHtml(String htmlColor)
```


Översätter en HTML‑färgrepresentation till en GDI+ [Color](../../com.aspose.drawing/color)‑struktur.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| htmlColor | java.lang.String | Strängrepresentationen av Html‑färgen som ska översättas. |

**Returns:**
[Color](../../com.aspose.drawing/color) - The [Color](../../com.aspose.drawing/color) structure that represents the translated HTML color or `Empty` if htmlColor is null.
### toHtml(Color c) {#toHtml-com.aspose.drawing.Color-}
```
public static String toHtml(Color c)
```


Översätter den angivna [Color](../../com.aspose.drawing/color)‑strukturen till en HTML‑strängfärgrepresentation.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| c | [Color](../../com.aspose.drawing/color) | Den [Color](../../com.aspose.drawing/color) strukturen att översätta. |

**Returns:**
java.lang.String - Strängen som representerar HTML-färgen.
### fromWin32(int win32Color) {#fromWin32-int-}
```
public static Color fromWin32(int win32Color)
```


Översätter ett Windows‑färgvärde till en GDI+ [Color](../../com.aspose.drawing/color)‑struktur.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| win32Color | int | Den Windows-färgen att översätta. |

**Returns:**
[Color](../../com.aspose.drawing/color) - The [Color](../../com.aspose.drawing/color) structure that represents the translated Windows color.
### fromOle(int oleColor) {#fromOle-int-}
```
public static Color fromOle(int oleColor)
```


Översätter ett OLE‑färgvärde till en GDI+ [Color](../../com.aspose.drawing/color)‑struktur.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| oleColor | int | Den OLE-färgen att översätta. |

**Returns:**
[Color](../../com.aspose.drawing/color) - The [Color](../../com.aspose.drawing/color) structure that represents the translated OLE color.
### toWin32(Color c) {#toWin32-com.aspose.drawing.Color-}
```
public static int toWin32(Color c)
```


Konverterar [Color](../../com.aspose.drawing/color)‑struktur till Win32‑presentation av färg.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| c | [Color](../../com.aspose.drawing/color) | Den [Color](../../com.aspose.drawing/color) strukturen att konvertera. |

**Returns:**
int - Värde som representerar Win32-formatet för färg.
### toOle(Color c) {#toOle-com.aspose.drawing.Color-}
```
public static int toOle(Color c)
```


Konverterar [Color](../../com.aspose.drawing/color)‑struktur till OLE‑presentation av färg.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| c | [Color](../../com.aspose.drawing/color) | Den [Color](../../com.aspose.drawing/color) strukturen att konvertera. |

**Returns:**
int - Värde som representerar OLE-formatet för färg.
