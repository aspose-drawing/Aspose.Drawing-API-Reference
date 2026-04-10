---
title: ColorTranslator
second_title: Aspose.Drawing für Java API-Referenz
description: Übersetzt Farben zu und von GDI‑Strukturen.
type: docs
weight: 16
url: /de/java/com.aspose.drawing/colortranslator/
---
**Inheritance:**
java.lang.Object
```
public final class ColorTranslator
```

Übersetzt Farben zu und von GDI+ [Color](../../com.aspose.drawing/color) Strukturen. Diese Klasse kann nicht abgeleitet werden.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [ColorTranslator()](#ColorTranslator--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [fromHtml(String htmlColor)](#fromHtml-java.lang.String-) | Übersetzt eine HTML‑Farbrepräsentation in eine GDI+ [Color](../../com.aspose.drawing/color) Struktur. |
| [toHtml(Color c)](#toHtml-com.aspose.drawing.Color-) | Übersetzt die angegebene [Color](../../com.aspose.drawing/color) Struktur in eine HTML‑Zeichenketten‑Farbrepräsentation. |
| [fromWin32(int win32Color)](#fromWin32-int-) | Übersetzt einen Windows‑Farbwert in eine GDI+ [Color](../../com.aspose.drawing/color) Struktur. |
| [fromOle(int oleColor)](#fromOle-int-) | Übersetzt einen OLE‑Farbwert in eine GDI+ [Color](../../com.aspose.drawing/color) Struktur. |
| [toWin32(Color c)](#toWin32-com.aspose.drawing.Color-) | Konvertiert die [Color](../../com.aspose.drawing/color) Struktur in die Win32‑Darstellung einer Farbe. |
| [toOle(Color c)](#toOle-com.aspose.drawing.Color-) | Konvertiert die [Color](../../com.aspose.drawing/color) Struktur in die OLE‑Darstellung einer Farbe. |
### ColorTranslator() {#ColorTranslator--}
```
public ColorTranslator()
```


### fromHtml(String htmlColor) {#fromHtml-java.lang.String-}
```
public static Color fromHtml(String htmlColor)
```


Übersetzt eine HTML‑Farbrepräsentation in eine GDI+ [Color](../../com.aspose.drawing/color) Struktur.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| htmlColor | java.lang.String | Die Zeichenkettenrepräsentation der HTML‑Farbe, die übersetzt werden soll. |

**Returns:**
[Color](../../com.aspose.drawing/color) - The [Color](../../com.aspose.drawing/color) structure that represents the translated HTML color or `Empty` if htmlColor is null.
### toHtml(Color c) {#toHtml-com.aspose.drawing.Color-}
```
public static String toHtml(Color c)
```


Übersetzt die angegebene [Color](../../com.aspose.drawing/color) Struktur in eine HTML‑Zeichenketten‑Farbrepräsentation.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| c | [Color](../../com.aspose.drawing/color) | Die [Color](../../com.aspose.drawing/color) Struktur zum Übersetzen. |

**Returns:**
java.lang.String - Die Zeichenkette, die die HTML‑Farbe darstellt.
### fromWin32(int win32Color) {#fromWin32-int-}
```
public static Color fromWin32(int win32Color)
```


Übersetzt einen Windows‑Farbwert in eine GDI+ [Color](../../com.aspose.drawing/color) Struktur.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| win32Color | int | Die Windows‑Farbe zum Übersetzen. |

**Returns:**
[Color](../../com.aspose.drawing/color) - The [Color](../../com.aspose.drawing/color) structure that represents the translated Windows color.
### fromOle(int oleColor) {#fromOle-int-}
```
public static Color fromOle(int oleColor)
```


Übersetzt einen OLE‑Farbwert in eine GDI+ [Color](../../com.aspose.drawing/color) Struktur.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| oleColor | int | Die OLE‑Farbe zum Übersetzen. |

**Returns:**
[Color](../../com.aspose.drawing/color) - The [Color](../../com.aspose.drawing/color) structure that represents the translated OLE color.
### toWin32(Color c) {#toWin32-com.aspose.drawing.Color-}
```
public static int toWin32(Color c)
```


Konvertiert die [Color](../../com.aspose.drawing/color) Struktur in die Win32‑Darstellung einer Farbe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| c | [Color](../../com.aspose.drawing/color) | Die [Color](../../com.aspose.drawing/color) Struktur zum Konvertieren. |

**Returns:**
int - Wert, der das Win32‑Format einer Farbe darstellt.
### toOle(Color c) {#toOle-com.aspose.drawing.Color-}
```
public static int toOle(Color c)
```


Konvertiert die [Color](../../com.aspose.drawing/color) Struktur in die OLE‑Darstellung einer Farbe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| c | [Color](../../com.aspose.drawing/color) | Die [Color](../../com.aspose.drawing/color) Struktur zum Konvertieren. |

**Returns:**
int - Wert, der das OLE‑Format einer Farbe darstellt.
