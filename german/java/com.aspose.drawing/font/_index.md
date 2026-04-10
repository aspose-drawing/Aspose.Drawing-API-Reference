---
title: Font
second_title: Aspose.Drawing für Java API-Referenz
description: Definiert ein bestimmtes Format für Text, einschließlich Schriftart, Größe und Stil-Attributen.
type: docs
weight: 21
url: /de/java/com.aspose.drawing/font/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public final class Font implements System.IDisposable
```

Definiert ein bestimmtes Format für Text, einschließlich Schriftart, Größe und Stilattribute. Diese Klasse kann nicht abgeleitet werden.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Font(Font prototype, int newStyle)](#Font-com.aspose.drawing.Font-int-) | Initialisiert eine neue Instanz der [Font](../../com.aspose.drawing/font)-Klasse, die das angegebene vorhandene [Font](../../com.aspose.drawing/font) und die [FontStyle](../../com.aspose.drawing/fontstyle)-Aufzählung verwendet. |
| [Font(FontFamily family, float emSize)](#Font-com.aspose.drawing.FontFamily-float-) | Initialisiert eine neue Instanz der [Font](../../com.aspose.drawing/font)-Klasse. |
| [Font(FontFamily family, float emSize, int style)](#Font-com.aspose.drawing.FontFamily-float-int-) | Initialisiert eine neue Instanz der [Font](../../com.aspose.drawing/font)-Klasse unter Verwendung einer angegebenen Größe und eines Stils.. |
| [Font(FontFamily family, float emSize, int style, int unit)](#Font-com.aspose.drawing.FontFamily-float-int-int-) | Initialisiert eine neue Instanz der [Font](../../com.aspose.drawing/font)-Klasse unter Verwendung einer angegebenen Größe, eines Stils und einer Einheit. |
| [Font(FontFamily family, float emSize, int style, int unit, byte gdiCharSet)](#Font-com.aspose.drawing.FontFamily-float-int-int-byte-) | Initialisiert eine neue Instanz der [Font](../../com.aspose.drawing/font)-Klasse unter Verwendung einer angegebenen Größe, eines Stils, einer Einheit und eines Zeichensatzes.. |
| [Font(FontFamily family, float emSize, int style, int unit, byte gdiCharSet, boolean gdiVerticalFont)](#Font-com.aspose.drawing.FontFamily-float-int-int-byte-boolean-) | Initialisiert eine neue Instanz der [Font](../../com.aspose.drawing/font)-Klasse unter Verwendung einer angegebenen Größe, eines Stils, einer Einheit und eines Zeichensatzes.. |
| [Font(String familyName, float emSize)](#Font-java.lang.String-float-) | Initialisiert eine neue Instanz der [Font](../../com.aspose.drawing/font)-Klasse unter Verwendung einer angegebenen Größe. |
| [Font(String familyName, float emSize, int style)](#Font-java.lang.String-float-int-) | Initialisiert eine neue Instanz der [Font](../../com.aspose.drawing/font)-Klasse unter Verwendung einer angegebenen Größe und eines Stils. |
| [Font(String familyName, float emSize, int style, int unit)](#Font-java.lang.String-float-int-int-) | Initialisiert eine neue Instanz der [Font](../../com.aspose.drawing/font)-Klasse unter Verwendung einer angegebenen Größe, eines Stils und einer Einheit. |
| [Font(String familyName, float emSize, int style, int unit, byte gdiCharSet)](#Font-java.lang.String-float-int-int-byte-) | Initialisiert eine neue Instanz der [Font](../../com.aspose.drawing/font)-Klasse unter Verwendung einer angegebenen Größe, eines Stils, einer Einheit und eines Zeichensatzes. |
| [Font(String familyName, float emSize, int style, int unit, byte gdiCharSet, boolean gdiVerticalFont)](#Font-java.lang.String-float-int-int-byte-boolean-) | Initialisiert eine neue Instanz der [Font](../../com.aspose.drawing/font)-Klasse unter Verwendung der angegebenen Größe, des Stils, der Einheit und des Zeichensatzes. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getFontFamily()](#getFontFamily--) | Ruft die `FontFamily`([.getFontFamily](../../null/\#getFontFamily)) ab, die mit diesem [Font](../../com.aspose.drawing/font) verknüpft ist. |
| [getBold()](#getBold--) | Ruft einen Wert ab, der angibt, ob dieses [Font](../../com.aspose.drawing/font) fett ist. |
| [getGdiCharSet()](#getGdiCharSet--) | Ruft einen Byte-Wert ab, der den GDI-Zeichensatz angibt, den dieses [Font](../../com.aspose.drawing/font) verwendet. |
| [getGdiVerticalFont()](#getGdiVerticalFont--) | Ruft einen Wert ab, der angibt, ob dieses [Font](../../com.aspose.drawing/font) von einer GDI‑vertikalen Schrift abgeleitet ist.. |
| [getItalic()](#getItalic--) | Ruft einen Wert ab, der angibt, ob dieses [Font](../../com.aspose.drawing/font) kursiv ist. |
| [getName()](#getName--) | Ruft den Schriftartnamen dieses [Font](../../com.aspose.drawing/font) ab. |
| [getStrikeout()](#getStrikeout--) | Ruft einen Wert ab, der angibt, ob dieses [Font](../../com.aspose.drawing/font) eine horizontale Durchstreichung definiert. |
| [getUnderline()](#getUnderline--) | Ruft einen Wert ab, der angibt, ob dieses [Font](../../com.aspose.drawing/font) unterstrichen ist. |
| [getStyle()](#getStyle--) | Ruft Stilinformationen für dieses [Font](../../com.aspose.drawing/font) ab. |
| [getSize()](#getSize--) | Ruft die Em-Größe dieses [Font](../../com.aspose.drawing/font) ab, gemessen in den Einheiten, die durch die Eigenschaft `Font.Unit` angegeben sind. |
| [getSizeInPoints()](#getSizeInPoints--) | Ruft die Em-Größe dieses [Font](../../com.aspose.drawing/font) in Punkten ab. |
| [getUnit()](#getUnit--) | Ruft die Maßeinheit für dieses [Font](../../com.aspose.drawing/font) ab. |
| [getHeight_Rename_Namesake()](#getHeight-Rename-Namesake--) | Ruft den Zeilenabstand dieser Schriftart ab. |
| [isSystemFont()](#isSystemFont--) | Ruft einen Wert ab, der angibt, ob die Schriftart Mitglied von [SystemFonts](../../com.aspose.drawing/systemfonts) ist. |
| [getSystemFontName()](#getSystemFontName--) | Ruft den Namen der Systemschriftart ab, wenn die Eigenschaft IsSystemFont den Wert true zurückgibt. |
| [getOriginalFontName()](#getOriginalFontName--) | Ruft den ursprünglich angegebenen Namen der Schriftart ab. |
| [deepClone()](#deepClone--) | Erstellt eine exakte Kopie dieses [Font](../../com.aspose.drawing/font). |
| [equals(Object obj)](#equals-java.lang.Object-) | Gibt an, ob das angegebene Objekt ein [Font](../../com.aspose.drawing/font) ist und die gleichen `FontFamily`([.getFontFamily](../../null/\#getFontFamily)), `M:GdiVerticalFont`, `M:GdiCharSet`, `M:Style`, `M:Size` und `M:Unit` Eigenschaftswerte wie dieses [Font](../../com.aspose.drawing/font) hat. |
| [hashCode()](#hashCode--) | Liefert den Hashcode für dieses [Font](../../com.aspose.drawing/font). |
| [getHeight()](#getHeight--) | Gibt den Zeilenabstand dieses Fonts in Pixel zurück. |
| [getHeight(Graphics graphics)](#getHeight-com.aspose.drawing.Graphics-) | Gibt den Zeilenabstand dieses Fonts in der aktuellen Einheit eines angegebenen [Graphics](../../com.aspose.drawing/graphics) zurück. |
| [getHeight(float dpi)](#getHeight-float-) | Gibt die Höhe dieses [Font](../../com.aspose.drawing/font) in Pixel zurück, wenn er auf ein Gerät mit der angegebenen vertikalen Auflösung gezeichnet wird. |
| [dispose()](#dispose--) | Gibt alle von diesem [Font](../../com.aspose.drawing/font) verwendeten Ressourcen frei. |
| [toString()](#toString--) | Gibt eine menschenlesbare Zeichenkettenrepräsentation dieses [Font](../../com.aspose.drawing/font) zurück. |
| [getCharacterSet()](#getCharacterSet--) | Liefert einen Byte‑Wert, der den Zeichensatz angibt, den dieses `Font` verwendet. |
### Font(Font prototype, int newStyle) {#Font-com.aspose.drawing.Font-int-}
```
public Font(Font prototype, int newStyle)
```


Initialisiert eine neue Instanz der [Font](../../com.aspose.drawing/font)-Klasse, die das angegebene vorhandene [Font](../../com.aspose.drawing/font) und die [FontStyle](../../com.aspose.drawing/fontstyle)-Aufzählung verwendet.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| prototype | [Font](../../com.aspose.drawing/font) | Der vorhandene [Font](../../com.aspose.drawing/font), aus dem der neue [Font](../../com.aspose.drawing/font) erstellt wird. |
| newStyle | int | Der [FontStyle](../../com.aspose.drawing/fontstyle), der auf den neuen [Font](../../com.aspose.drawing/font) angewendet werden soll. Mehrere Werte der Aufzählung [FontStyle](../../com.aspose.drawing/fontstyle) können mit dem ODER‑Operator kombiniert werden. |

### Font(FontFamily family, float emSize) {#Font-com.aspose.drawing.FontFamily-float-}
```
public Font(FontFamily family, float emSize)
```


Initialisiert eine neue Instanz der [Font](../../com.aspose.drawing/font)-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| family | [FontFamily](../../com.aspose.drawing/fontfamily) | Die `FontFamily`([.getFontFamily](../../null/\#getFontFamily)) des neuen [Font](../../com.aspose.drawing/font). |
| emSize | float | Die em‑Größe des neuen Fonts in Punkt. |

### Font(FontFamily family, float emSize, int style) {#Font-com.aspose.drawing.FontFamily-float-int-}
```
public Font(FontFamily family, float emSize, int style)
```


Initialisiert eine neue Instanz der [Font](../../com.aspose.drawing/font)-Klasse unter Verwendung einer angegebenen Größe und eines Stils..

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| family | [FontFamily](../../com.aspose.drawing/fontfamily) | Die `FontFamily`([.getFontFamily](../../null/\#getFontFamily)) des neuen [Font](../../com.aspose.drawing/font). |
| emSize | float | Die em‑Größe des neuen Fonts in Punkt. |
| style | int | Der [FontStyle](../../com.aspose.drawing/fontstyle) des neuen Fonts. |

### Font(FontFamily family, float emSize, int style, int unit) {#Font-com.aspose.drawing.FontFamily-float-int-int-}
```
public Font(FontFamily family, float emSize, int style, int unit)
```


Initialisiert eine neue Instanz der [Font](../../com.aspose.drawing/font)-Klasse unter Verwendung einer angegebenen Größe, eines Stils und einer Einheit.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| family | [FontFamily](../../com.aspose.drawing/fontfamily) | Die `FontFamily`([.getFontFamily](../../null/\#getFontFamily)) des neuen [Font](../../com.aspose.drawing/font). |
| emSize | float | Die em‑Größe des neuen Fonts in den durch den Parameter `unit` angegebenen Einheiten. |
| style | int | Der [FontStyle](../../com.aspose.drawing/fontstyle) des neuen Fonts. |
| unit | int | Die [GraphicsUnit](../../com.aspose.drawing/graphicsunit) des neuen Fonts. |

### Font(FontFamily family, float emSize, int style, int unit, byte gdiCharSet) {#Font-com.aspose.drawing.FontFamily-float-int-int-byte-}
```
public Font(FontFamily family, float emSize, int style, int unit, byte gdiCharSet)
```


Initialisiert eine neue Instanz der [Font](../../com.aspose.drawing/font)-Klasse unter Verwendung einer angegebenen Größe, eines Stils, einer Einheit und eines Zeichensatzes..

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| family | [FontFamily](../../com.aspose.drawing/fontfamily) | Die `FontFamily`([.getFontFamily](../../null/\#getFontFamily)) des neuen [Font](../../com.aspose.drawing/font). |
| emSize | float | Die em‑Größe des neuen Fonts in den durch den Parameter `unit` angegebenen Einheiten. |
| style | int | Der [FontStyle](../../com.aspose.drawing/fontstyle) des neuen Fonts. |
| unit | int | Die [GraphicsUnit](../../com.aspose.drawing/graphicsunit) des neuen Fonts. |
| gdiCharSet | byte | GDI‑Zeichensatz, der für den neuen Font verwendet werden soll. |

### Font(FontFamily family, float emSize, int style, int unit, byte gdiCharSet, boolean gdiVerticalFont) {#Font-com.aspose.drawing.FontFamily-float-int-int-byte-boolean-}
```
public Font(FontFamily family, float emSize, int style, int unit, byte gdiCharSet, boolean gdiVerticalFont)
```


Initialisiert eine neue Instanz der [Font](../../com.aspose.drawing/font)-Klasse unter Verwendung einer angegebenen Größe, eines Stils, einer Einheit und eines Zeichensatzes..

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| family | [FontFamily](../../com.aspose.drawing/fontfamily) | Die `FontFamily`([.getFontFamily](../../null/\#getFontFamily)) des neuen [Font](../../com.aspose.drawing/font). |
| emSize | float | Die em‑Größe des neuen Fonts in den durch den Parameter `unit` angegebenen Einheiten. |
| style | int | Der [FontStyle](../../com.aspose.drawing/fontstyle) des neuen Fonts. |
| unit | int | Die [GraphicsUnit](../../com.aspose.drawing/graphicsunit) des neuen Fonts. |
| gdiCharSet | byte | GDI‑Zeichensatz, der für den neuen Font verwendet werden soll. |
| gdiVerticalFont | boolean | Ein Boolescher Wert, der angibt, ob der neue Font von einem GDI‑vertikalen Font abgeleitet ist. |

### Font(String familyName, float emSize) {#Font-java.lang.String-float-}
```
public Font(String familyName, float emSize)
```


Initialisiert eine neue Instanz der [Font](../../com.aspose.drawing/font)-Klasse unter Verwendung einer angegebenen Größe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| familyName | java.lang.String | Eine Zeichenkettenrepräsentation der FontFamily für den neuen [Font](../../com.aspose.drawing/font). |
| emSize | float | Die em‑Größe des neuen Fonts in Punkt. |

### Font(String familyName, float emSize, int style) {#Font-java.lang.String-float-int-}
```
public Font(String familyName, float emSize, int style)
```


Initialisiert eine neue Instanz der [Font](../../com.aspose.drawing/font)-Klasse unter Verwendung einer angegebenen Größe und eines Stils.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| familyName | java.lang.String | Eine Zeichenkettenrepräsentation der FontFamily für den neuen [Font](../../com.aspose.drawing/font). |
| emSize | float | Die em‑Größe des neuen Fonts in Punkt. |
| style | int | Der [FontStyle](../../com.aspose.drawing/fontstyle) des neuen Fonts. |

### Font(String familyName, float emSize, int style, int unit) {#Font-java.lang.String-float-int-int-}
```
public Font(String familyName, float emSize, int style, int unit)
```


Initialisiert eine neue Instanz der [Font](../../com.aspose.drawing/font)-Klasse unter Verwendung einer angegebenen Größe, eines Stils und einer Einheit.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| familyName | java.lang.String | Eine Zeichenkettenrepräsentation der `FontFamily`([.getFontFamily](../../null/\#getFontFamily)) für den neuen [Font](../../com.aspose.drawing/font). |
| emSize | float | Die em‑Größe des neuen Fonts in den durch den Parameter `unit` angegebenen Einheiten. |
| style | int | Der [FontStyle](../../com.aspose.drawing/fontstyle) des neuen Fonts. |
| unit | int | Die [GraphicsUnit](../../com.aspose.drawing/graphicsunit) des neuen Fonts. |

### Font(String familyName, float emSize, int style, int unit, byte gdiCharSet) {#Font-java.lang.String-float-int-int-byte-}
```
public Font(String familyName, float emSize, int style, int unit, byte gdiCharSet)
```


Initialisiert eine neue Instanz der [Font](../../com.aspose.drawing/font)-Klasse unter Verwendung einer angegebenen Größe, eines Stils, einer Einheit und eines Zeichensatzes.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| familyName | java.lang.String | Eine Zeichenkettenrepräsentation der FontFamily für den neuen [Font](../../com.aspose.drawing/font). |
| emSize | float | Die em‑Größe des neuen Fonts in den durch den Parameter `unit` angegebenen Einheiten. |
| style | int | Der [FontStyle](../../com.aspose.drawing/fontstyle) des neuen Fonts. |
| unit | int | Die [GraphicsUnit](../../com.aspose.drawing/graphicsunit) des neuen Fonts. |
| gdiCharSet | byte | Ein Byte, das den für diesen Font zu verwendenden GDI‑Zeichensatz angibt. |

### Font(String familyName, float emSize, int style, int unit, byte gdiCharSet, boolean gdiVerticalFont) {#Font-java.lang.String-float-int-int-byte-boolean-}
```
public Font(String familyName, float emSize, int style, int unit, byte gdiCharSet, boolean gdiVerticalFont)
```


Initialisiert eine neue Instanz der [Font](../../com.aspose.drawing/font)-Klasse unter Verwendung der angegebenen Größe, des Stils, der Einheit und des Zeichensatzes.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| familyName | java.lang.String | Eine Zeichenkettenrepräsentation der FontFamily für den neuen [Font](../../com.aspose.drawing/font). |
| emSize | float | Die em‑Größe des neuen Fonts in den durch den Parameter `unit` angegebenen Einheiten. |
| style | int | Der [FontStyle](../../com.aspose.drawing/fontstyle) des neuen Fonts. |
| unit | int | Die [GraphicsUnit](../../com.aspose.drawing/graphicsunit) des neuen Fonts. |
| gdiCharSet | byte | Ein Byte, das den für diesen Font zu verwendenden GDI‑Zeichensatz angibt. |
| gdiVerticalFont | boolean | Ein Boolescher Wert, der angibt, ob der neue [Font](../../com.aspose.drawing/font) von einem GDI‑vertikalen Font abgeleitet ist. |

### getFontFamily() {#getFontFamily--}
```
public FontFamily getFontFamily()
```


Ruft die `FontFamily`([.getFontFamily](../../null/\#getFontFamily)) ab, die mit diesem [Font](../../com.aspose.drawing/font) verknüpft ist.

**Returns:**
[FontFamily](../../com.aspose.drawing/fontfamily) - The `FontFamily`([.getFontFamily](../../null/\#getFontFamily)) associated with this [Font](../../com.aspose.drawing/font).
### getBold() {#getBold--}
```
public boolean getBold()
```


Ruft einen Wert ab, der angibt, ob dieses [Font](../../com.aspose.drawing/font) fett ist.

**Returns:**
boolean - ein Wert, der angibt, ob diese [Font](../../com.aspose.drawing/font) fett ist.
### getGdiCharSet() {#getGdiCharSet--}
```
public byte getGdiCharSet()
```


Ruft einen Byte-Wert ab, der den GDI-Zeichensatz angibt, den dieses [Font](../../com.aspose.drawing/font) verwendet.

**Returns:**
byte - Ein Byte-Wert, der den GDI-Zeichensatz angibt, den diese [Font](../../com.aspose.drawing/font) verwendet.
### getGdiVerticalFont() {#getGdiVerticalFont--}
```
public boolean getGdiVerticalFont()
```


Ruft einen Wert ab, der angibt, ob dieses [Font](../../com.aspose.drawing/font) von einer GDI‑vertikalen Schrift abgeleitet ist..

Wert: `true`, wenn diese [Font](../../com.aspose.drawing/font) von einer GDI‑vertikalen Schrift abgeleitet ist; andernfalls `false`.

**Returns:**
boolean - ein Wert, der angibt, ob diese [Font](../../com.aspose.drawing/font) von einer GDI‑vertikalen Schrift abgeleitet ist.
### getItalic() {#getItalic--}
```
public boolean getItalic()
```


Ruft einen Wert ab, der angibt, ob dieses [Font](../../com.aspose.drawing/font) kursiv ist.

**Returns:**
boolean - ein Wert, der angibt, ob diese [Font](../../com.aspose.drawing/font) kursiv ist.
### getName() {#getName--}
```
public String getName()
```


Ruft den Schriftartnamen dieses [Font](../../com.aspose.drawing/font) ab.

**Returns:**
java.lang.String - der Schriftartname dieser [Font](../../com.aspose.drawing/font).
### getStrikeout() {#getStrikeout--}
```
public boolean getStrikeout()
```


Ruft einen Wert ab, der angibt, ob dieses [Font](../../com.aspose.drawing/font) eine horizontale Durchstreichung definiert.

**Returns:**
boolean - ein Wert, der angibt, ob diese [Font](../../com.aspose.drawing/font) eine horizontale Durchstreichung der Schrift festlegt.
### getUnderline() {#getUnderline--}
```
public boolean getUnderline()
```


Ruft einen Wert ab, der angibt, ob dieses [Font](../../com.aspose.drawing/font) unterstrichen ist.

**Returns:**
boolean - ein Wert, der angibt, ob diese [Font](../../com.aspose.drawing/font) unterstrichen ist.
### getStyle() {#getStyle--}
```
public int getStyle()
```


Ruft Stilinformationen für dieses [Font](../../com.aspose.drawing/font) ab.

**Returns:**
int - Stilinformationen für diese [Font](../../com.aspose.drawing/font).
### getSize() {#getSize--}
```
public float getSize()
```


Ruft die Em-Größe dieses [Font](../../com.aspose.drawing/font) ab, gemessen in den Einheiten, die durch die Eigenschaft `Font.Unit` angegeben sind.

**Returns:**
float - die Em-Größe dieser [Font](../../com.aspose.drawing/font), gemessen in den Einheiten, die durch \{@code Font angegeben werden.
### getSizeInPoints() {#getSizeInPoints--}
```
public float getSizeInPoints()
```


Ruft die Em-Größe dieses [Font](../../com.aspose.drawing/font) in Punkten ab.

**Returns:**
float - Die Em-Größe dieser [Font](../../com.aspose.drawing/font) in Punkten.
### getUnit() {#getUnit--}
```
public int getUnit()
```


Ruft die Maßeinheit für dieses [Font](../../com.aspose.drawing/font) ab.

**Returns:**
int - die Maßeinheit für diese [Font](../../com.aspose.drawing/font).
### getHeight_Rename_Namesake() {#getHeight-Rename-Namesake--}
```
public int getHeight_Rename_Namesake()
```


Ruft den Zeilenabstand dieser Schriftart ab.

Wert: Der Zeilenabstand dieser Schrift in Pixeln.

**Returns:**
int - der Zeilenabstand dieser Schrift.
### isSystemFont() {#isSystemFont--}
```
public boolean isSystemFont()
```


Ruft einen Wert ab, der angibt, ob die Schriftart Mitglied von [SystemFonts](../../com.aspose.drawing/systemfonts) ist.

Wert: `true`, wenn die Schrift ein Mitglied von [SystemFonts](../../com.aspose.drawing/systemfonts) ist; andernfalls `false`.

**Returns:**
boolean - ein Wert, der angibt, ob die Schrift ein Mitglied von [SystemFonts](../../com.aspose.drawing/systemfonts) ist.
### getSystemFontName() {#getSystemFontName--}
```
public String getSystemFontName()
```


Ruft den Namen der Systemschriftart ab, wenn die Eigenschaft IsSystemFont den Wert true zurückgibt.

Wert: Der Name der Systemschrift, wenn IsSystemFont true zurückgibt; andernfalls ein leerer String ("").

**Returns:**
java.lang.String - der Name der Systemschrift, wenn die Eigenschaft IsSystemFont true zurückgibt.
### getOriginalFontName() {#getOriginalFontName--}
```
public String getOriginalFontName()
```


Ruft den ursprünglich angegebenen Namen der Schriftart ab.

Wert: Der String, der den ursprünglich angegebenen Schriftnamen darstellt.

**Returns:**
java.lang.String - der ursprünglich angegebene Schriftname.
### deepClone() {#deepClone--}
```
public Font deepClone()
```


Erstellt eine exakte Kopie dieses [Font](../../com.aspose.drawing/font).

**Returns:**
[Font](../../com.aspose.drawing/font) - The [Font](../../com.aspose.drawing/font) this method creates, cast as an Object.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Gibt an, ob das angegebene Objekt ein [Font](../../com.aspose.drawing/font) ist und die gleichen `FontFamily`([.getFontFamily](../../null/\#getFontFamily)), `M:GdiVerticalFont`, `M:GdiCharSet`, `M:Style`, `M:Size` und `M:Unit` Eigenschaftswerte wie dieses [Font](../../com.aspose.drawing/font) hat.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | java.lang.Object | Das zu testende Objekt. |

**Returns:**
boolean - `true`, wenn der Parameter obj ein [Font](../../com.aspose.drawing/font) ist und die gleichen `FontFamily`([.getFontFamily](../../null/\#getFontFamily)), `M:GdiVerticalFont`, `M:GdiCharSet`, `M:Style`, `M:Size` und `M:Unit` Eigenschaftswerte wie dieses [Font](../../com.aspose.drawing/font) hat; andernfalls `false`.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Liefert den Hashcode für dieses [Font](../../com.aspose.drawing/font).

**Returns:**
int - Der Hashcode für dieses [Font](../../com.aspose.drawing/font).
### getHeight() {#getHeight--}
```
public int getHeight()
```


Gibt den Zeilenabstand dieses Fonts in Pixel zurück.

**Returns:**
int - Der Zeilenabstand dieser Schrift in Pixeln.
### getHeight(Graphics graphics) {#getHeight-com.aspose.drawing.Graphics-}
```
public float getHeight(Graphics graphics)
```


Gibt den Zeilenabstand dieses Fonts in der aktuellen Einheit eines angegebenen [Graphics](../../com.aspose.drawing/graphics) zurück.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| graphics | [Graphics](../../com.aspose.drawing/graphics) | Ein [Graphics](../../com.aspose.drawing/graphics), das die vertikale Auflösung des Anzeigegeräts in DPI sowie Einstellungen für Seiteneinheit und Seitenskalierung enthält. |

**Returns:**
float - Der Zeilenabstand dieser Schrift in Pixeln.
### getHeight(float dpi) {#getHeight-float-}
```
public int getHeight(float dpi)
```


Gibt die Höhe dieses [Font](../../com.aspose.drawing/font) in Pixel zurück, wenn er auf ein Gerät mit der angegebenen vertikalen Auflösung gezeichnet wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| dpi | float | Die vertikale Auflösung in Punkten pro Zoll, die zur Berechnung der Schrifthöhe verwendet wird. |

**Returns:**
int - Die Höhe in Pixeln dieses [Font](../../com.aspose.drawing/font).
### dispose() {#dispose--}
```
public void dispose()
```


Gibt alle von diesem [Font](../../com.aspose.drawing/font) verwendeten Ressourcen frei.

### toString() {#toString--}
```
public String toString()
```


Gibt eine menschenlesbare Zeichenkettenrepräsentation dieses [Font](../../com.aspose.drawing/font) zurück.

**Returns:**
java.lang.String - Eine Zeichenkette, die dieses [Font](../../com.aspose.drawing/font) repräsentiert.
### getCharacterSet() {#getCharacterSet--}
```
public int getCharacterSet()
```


Liefert einen Byte‑Wert, der den Zeichensatz angibt, den dieses `Font` verwendet.

**Returns:**
int - Ein Zeichensatz, den dieses `Font` verwendet.
