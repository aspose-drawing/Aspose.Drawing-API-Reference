---
title: ColorTranslator
second_title: Αναφορά API του Aspose.Drawing for Java
description: Μεταφράζει χρώματα προς και από δομές GDI.
type: docs
weight: 16
url: /el/java/com.aspose.drawing/colortranslator/
---
**Inheritance:**
java.lang.Object
```
public final class ColorTranslator
```

Μεταφράζει χρώματα προς και από δομές GDI+ [Color](../../com.aspose.drawing/color). Αυτή η κλάση δεν μπορεί να κληρονομηθεί.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [ColorTranslator()](#ColorTranslator--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [fromHtml(String htmlColor)](#fromHtml-java.lang.String-) | Μεταφράζει μια αναπαράσταση χρώματος HTML σε δομή GDI+ [Color](../../com.aspose.drawing/color). |
| [toHtml(Color c)](#toHtml-com.aspose.drawing.Color-) | Μεταφράζει τη συγκεκριμένη δομή [Color](../../com.aspose.drawing/color) σε αναπαράσταση χρώματος HTML σε μορφή συμβολοσειράς. |
| [fromWin32(int win32Color)](#fromWin32-int-) | Μεταφράζει μια τιμή χρώματος Windows σε δομή GDI+ [Color](../../com.aspose.drawing/color). |
| [fromOle(int oleColor)](#fromOle-int-) | Μεταφράζει μια τιμή χρώματος OLE σε δομή GDI+ [Color](../../com.aspose.drawing/color). |
| [toWin32(Color c)](#toWin32-com.aspose.drawing.Color-) | Μετατρέπει τη δομή [Color](../../com.aspose.drawing/color) σε παρουσίαση χρώματος Win32. |
| [toOle(Color c)](#toOle-com.aspose.drawing.Color-) | Μετατρέπει τη δομή [Color](../../com.aspose.drawing/color) σε παρουσίαση χρώματος OLE. |
### ColorTranslator() {#ColorTranslator--}
```
public ColorTranslator()
```


### fromHtml(String htmlColor) {#fromHtml-java.lang.String-}
```
public static Color fromHtml(String htmlColor)
```


Μεταφράζει μια αναπαράσταση χρώματος HTML σε δομή GDI+ [Color](../../com.aspose.drawing/color).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| htmlColor | java.lang.String | Η αναπαράσταση συμβολοσειράς του χρώματος Html για μετάφραση. |

**Returns:**
[Color](../../com.aspose.drawing/color) - The [Color](../../com.aspose.drawing/color) structure that represents the translated HTML color or `Empty` if htmlColor is null.
### toHtml(Color c) {#toHtml-com.aspose.drawing.Color-}
```
public static String toHtml(Color c)
```


Μεταφράζει τη συγκεκριμένη δομή [Color](../../com.aspose.drawing/color) σε αναπαράσταση χρώματος HTML σε μορφή συμβολοσειράς.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| c | [Color](../../com.aspose.drawing/color) | Η δομή [Color](../../com.aspose.drawing/color) για μετάφραση. |

**Returns:**
java.lang.String - Η συμβολοσειρά που αντιπροσωπεύει το χρώμα HTML.
### fromWin32(int win32Color) {#fromWin32-int-}
```
public static Color fromWin32(int win32Color)
```


Μεταφράζει μια τιμή χρώματος Windows σε δομή GDI+ [Color](../../com.aspose.drawing/color).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| win32Color | int | Το χρώμα Windows για μετάφραση. |

**Returns:**
[Color](../../com.aspose.drawing/color) - The [Color](../../com.aspose.drawing/color) structure that represents the translated Windows color.
### fromOle(int oleColor) {#fromOle-int-}
```
public static Color fromOle(int oleColor)
```


Μεταφράζει μια τιμή χρώματος OLE σε δομή GDI+ [Color](../../com.aspose.drawing/color).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| oleColor | int | Το χρώμα OLE για μετάφραση. |

**Returns:**
[Color](../../com.aspose.drawing/color) - The [Color](../../com.aspose.drawing/color) structure that represents the translated OLE color.
### toWin32(Color c) {#toWin32-com.aspose.drawing.Color-}
```
public static int toWin32(Color c)
```


Μετατρέπει τη δομή [Color](../../com.aspose.drawing/color) σε παρουσίαση χρώματος Win32.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| c | [Color](../../com.aspose.drawing/color) | Δομή [Color](../../com.aspose.drawing/color) για μετατροπή. |

**Returns:**
int - Τιμή που αντιπροσωπεύει τη μορφή Win32 του χρώματος.
### toOle(Color c) {#toOle-com.aspose.drawing.Color-}
```
public static int toOle(Color c)
```


Μετατρέπει τη δομή [Color](../../com.aspose.drawing/color) σε παρουσίαση χρώματος OLE.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| c | [Color](../../com.aspose.drawing/color) | Δομή [Color](../../com.aspose.drawing/color) για μετατροπή. |

**Returns:**
int - Τιμή που αντιπροσωπεύει τη μορφή OLE του χρώματος.
