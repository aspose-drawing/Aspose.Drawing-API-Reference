---
title: ColorTranslator
second_title: Referensi API Aspose.Drawing for Java
description: Menerjemahkan warna ke dan dari struktur GDI.
type: docs
weight: 16
url: /id/java/com.aspose.drawing/colortranslator/
---
**Inheritance:**
java.lang.Object
```
public final class ColorTranslator
```

Menerjemahkan warna ke dan dari struktur GDI+ [Color](../../com.aspose.drawing/color). Kelas ini tidak dapat diwarisi.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [ColorTranslator()](#ColorTranslator--) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [fromHtml(String htmlColor)](#fromHtml-java.lang.String-) | Menerjemahkan representasi warna HTML ke struktur GDI+ [Color](../../com.aspose.drawing/color). |
| [toHtml(Color c)](#toHtml-com.aspose.drawing.Color-) | Menerjemahkan struktur [Color](../../com.aspose.drawing/color) yang ditentukan ke representasi string warna HTML. |
| [fromWin32(int win32Color)](#fromWin32-int-) | Menerjemahkan nilai warna Windows ke struktur GDI+ [Color](../../com.aspose.drawing/color). |
| [fromOle(int oleColor)](#fromOle-int-) | Menerjemahkan nilai warna OLE ke struktur GDI+ [Color](../../com.aspose.drawing/color). |
| [toWin32(Color c)](#toWin32-com.aspose.drawing.Color-) | Mengonversi struktur [Color](../../com.aspose.drawing/color) ke presentasi warna Win32. |
| [toOle(Color c)](#toOle-com.aspose.drawing.Color-) | Mengonversi struktur [Color](../../com.aspose.drawing/color) ke presentasi warna OLE. |
### ColorTranslator() {#ColorTranslator--}
```
public ColorTranslator()
```


### fromHtml(String htmlColor) {#fromHtml-java.lang.String-}
```
public static Color fromHtml(String htmlColor)
```


Menerjemahkan representasi warna HTML ke struktur GDI+ [Color](../../com.aspose.drawing/color).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| htmlColor | java.lang.String | Representasi string warna Html yang akan diterjemahkan. |

**Returns:**
[Color](../../com.aspose.drawing/color) - The [Color](../../com.aspose.drawing/color) structure that represents the translated HTML color or `Empty` if htmlColor is null.
### toHtml(Color c) {#toHtml-com.aspose.drawing.Color-}
```
public static String toHtml(Color c)
```


Menerjemahkan struktur [Color](../../com.aspose.drawing/color) yang ditentukan ke representasi string warna HTML.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| c | [Color](../../com.aspose.drawing/color) | Struktur [Color](../../com.aspose.drawing/color) untuk diterjemahkan. |

**Returns:**
java.lang.String - String yang mewakili warna HTML.
### fromWin32(int win32Color) {#fromWin32-int-}
```
public static Color fromWin32(int win32Color)
```


Menerjemahkan nilai warna Windows ke struktur GDI+ [Color](../../com.aspose.drawing/color).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| win32Color | int | Warna Windows untuk diterjemahkan. |

**Returns:**
[Color](../../com.aspose.drawing/color) - The [Color](../../com.aspose.drawing/color) structure that represents the translated Windows color.
### fromOle(int oleColor) {#fromOle-int-}
```
public static Color fromOle(int oleColor)
```


Menerjemahkan nilai warna OLE ke struktur GDI+ [Color](../../com.aspose.drawing/color).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| oleColor | int | Warna OLE untuk diterjemahkan. |

**Returns:**
[Color](../../com.aspose.drawing/color) - The [Color](../../com.aspose.drawing/color) structure that represents the translated OLE color.
### toWin32(Color c) {#toWin32-com.aspose.drawing.Color-}
```
public static int toWin32(Color c)
```


Mengonversi struktur [Color](../../com.aspose.drawing/color) ke presentasi warna Win32.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| c | [Color](../../com.aspose.drawing/color) | Struktur [Color](../../com.aspose.drawing/color) untuk dikonversi. |

**Returns:**
int - Nilai yang mewakili format Win32 warna.
### toOle(Color c) {#toOle-com.aspose.drawing.Color-}
```
public static int toOle(Color c)
```


Mengonversi struktur [Color](../../com.aspose.drawing/color) ke presentasi warna OLE.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| c | [Color](../../com.aspose.drawing/color) | Struktur [Color](../../com.aspose.drawing/color) untuk dikonversi. |

**Returns:**
int - Nilai yang mewakili format OLE warna.
