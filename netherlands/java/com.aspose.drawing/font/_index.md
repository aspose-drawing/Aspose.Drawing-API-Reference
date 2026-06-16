---
title: Font
second_title: Aspose.Drawing voor Java API-referentie
description: Definieert een specifiek formaat voor tekst, inclusief lettertype, grootte en stijlkenmerken.
type: docs
weight: 21
url: /nl/java/com.aspose.drawing/font/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public final class Font implements System.IDisposable
```

Definieert een specifiek formaat voor tekst, inclusief lettertype, grootte en stijlkenmerken. Deze klasse kan niet worden geërfd.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [Font(Font prototype, int newStyle)](#Font-com.aspose.drawing.Font-int-) | Initialiseert een nieuw exemplaar van de [Font](../../com.aspose.drawing/font) klasse die de opgegeven bestaande [Font](../../com.aspose.drawing/font) en [FontStyle](../../com.aspose.drawing/fontstyle) enumeratie gebruikt. |
| [Font(FontFamily family, float emSize)](#Font-com.aspose.drawing.FontFamily-float-) | Initialiseert een nieuw exemplaar van de [Font](../../com.aspose.drawing/font) klasse. |
| [Font(FontFamily family, float emSize, int style)](#Font-com.aspose.drawing.FontFamily-float-int-) | Initialiseert een nieuw exemplaar van de [Font](../../com.aspose.drawing/font) klasse met een opgegeven grootte en stijl.. |
| [Font(FontFamily family, float emSize, int style, int unit)](#Font-com.aspose.drawing.FontFamily-float-int-int-) | Initialiseert een nieuw exemplaar van de [Font](../../com.aspose.drawing/font) klasse met een opgegeven grootte, stijl en eenheid. |
| [Font(FontFamily family, float emSize, int style, int unit, byte gdiCharSet)](#Font-com.aspose.drawing.FontFamily-float-int-int-byte-) | Initialiseert een nieuw exemplaar van de [Font](../../com.aspose.drawing/font) klasse met een opgegeven grootte, stijl, eenheid en tekenset.. |
| [Font(FontFamily family, float emSize, int style, int unit, byte gdiCharSet, boolean gdiVerticalFont)](#Font-com.aspose.drawing.FontFamily-float-int-int-byte-boolean-) | Initialiseert een nieuw exemplaar van de [Font](../../com.aspose.drawing/font) klasse met een opgegeven grootte, stijl, eenheid en tekenset.. |
| [Font(String familyName, float emSize)](#Font-java.lang.String-float-) | Initialiseert een nieuw exemplaar van de [Font](../../com.aspose.drawing/font) klasse met een opgegeven grootte. |
| [Font(String familyName, float emSize, int style)](#Font-java.lang.String-float-int-) | Initialiseert een nieuw exemplaar van de [Font](../../com.aspose.drawing/font) klasse met een opgegeven grootte en stijl. |
| [Font(String familyName, float emSize, int style, int unit)](#Font-java.lang.String-float-int-int-) | Initialiseert een nieuw exemplaar van de [Font](../../com.aspose.drawing/font) klasse met een opgegeven grootte, stijl en eenheid. |
| [Font(String familyName, float emSize, int style, int unit, byte gdiCharSet)](#Font-java.lang.String-float-int-int-byte-) | Initialiseert een nieuw exemplaar van de [Font](../../com.aspose.drawing/font) klasse met een opgegeven grootte, stijl, eenheid en tekenset. |
| [Font(String familyName, float emSize, int style, int unit, byte gdiCharSet, boolean gdiVerticalFont)](#Font-java.lang.String-float-int-int-byte-boolean-) | Initialiseert een nieuw exemplaar van de [Font](../../com.aspose.drawing/font) klasse met de opgegeven grootte, stijl, eenheid en tekenset. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getFontFamily()](#getFontFamily--) | Haalt de `FontFamily`([.getFontFamily](../../null/\#getFontFamily)) op die bij deze [Font](../../com.aspose.drawing/font) hoort. |
| [getBold()](#getBold--) | Haalt een waarde op die aangeeft of deze [Font](../../com.aspose.drawing/font) vet is. |
| [getGdiCharSet()](#getGdiCharSet--) | Haalt een byte‑waarde op die de GDI‑tekenset specificeert die deze [Font](../../com.aspose.drawing/font) gebruikt. |
| [getGdiVerticalFont()](#getGdiVerticalFont--) | Haalt een waarde op die aangeeft of deze [Font](../../com.aspose.drawing/font) is afgeleid van een verticale GDI‑lettertype.. |
| [getItalic()](#getItalic--) | Haalt een waarde op die aangeeft of deze [Font](../../com.aspose.drawing/font) cursief is. |
| [getName()](#getName--) | Haalt de naam van dit [Font](../../com.aspose.drawing/font) op. |
| [getStrikeout()](#getStrikeout--) | Haalt een waarde op die aangeeft of dit [Font](../../com.aspose.drawing/font) een horizontale doorstreping specificeert. |
| [getUnderline()](#getUnderline--) | Haalt een waarde op die aangeeft of dit [Font](../../com.aspose.drawing/font) onderstreept is. |
| [getStyle()](#getStyle--) | Haalt stijlinformatie op voor dit [Font](../../com.aspose.drawing/font). |
| [getSize()](#getSize--) | Haalt de em‑grootte van dit [Font](../../com.aspose.drawing/font) op, gemeten in de eenheden die zijn gespecificeerd door de eigenschap `Font.Unit`. |
| [getSizeInPoints()](#getSizeInPoints--) | Haalt de em‑grootte, in punten, van dit [Font](../../com.aspose.drawing/font) op. |
| [getUnit()](#getUnit--) | Haalt de meeteenheid voor dit [Font](../../com.aspose.drawing/font) op. |
| [getHeight_Rename_Namesake()](#getHeight-Rename-Namesake--) | Haalt de regelafstand van dit lettertype op. |
| [isSystemFont()](#isSystemFont--) | Haalt een waarde op die aangeeft of het lettertype lid is van [SystemFonts](../../com.aspose.drawing/systemfonts). |
| [getSystemFontName()](#getSystemFontName--) | Haalt de naam van het systeemlettertype op als de eigenschap IsSystemFont waar is. |
| [getOriginalFontName()](#getOriginalFontName--) | Haalt de oorspronkelijk opgegeven naam van het lettertype op. |
| [deepClone()](#deepClone--) | Maakt een exacte kopie van dit [Font](../../com.aspose.drawing/font). |
| [equals(Object obj)](#equals-java.lang.Object-) | Geeft aan of het opgegeven object een [Font](../../com.aspose.drawing/font) is en dezelfde `FontFamily`([.getFontFamily](../../null/\#getFontFamily)), `M:GdiVerticalFont`, `M:GdiCharSet`, `M:Style`, `M:Size` en `M:Unit` eigenschapswaarden heeft als deze [Font](../../com.aspose.drawing/font). |
| [hashCode()](#hashCode--) | Haalt de hashcode op voor deze [Font](../../com.aspose.drawing/font). |
| [getHeight()](#getHeight--) | Retourneert de regelafstand, in pixels, van dit lettertype. |
| [getHeight(Graphics graphics)](#getHeight-com.aspose.drawing.Graphics-) | Retourneert de regelafstand, in de huidige eenheid van een opgegeven [Graphics](../../com.aspose.drawing/graphics), van dit lettertype. |
| [getHeight(float dpi)](#getHeight-float-) | Retourneert de hoogte, in pixels, van dit [Font](../../com.aspose.drawing/font) wanneer getekend op een apparaat met de opgegeven verticale resolutie. |
| [dispose()](#dispose--) | Geeft alle bronnen vrij die door dit [Font](../../com.aspose.drawing/font) worden gebruikt. |
| [toString()](#toString--) | Retourneert een menselijk leesbare tekenreeksrepresentatie van dit [Font](../../com.aspose.drawing/font). |
| [getCharacterSet()](#getCharacterSet--) | Haalt een bytewaarde op die de tekenset specificeert die deze `Font` gebruikt. |
### Font(Font prototype, int newStyle) {#Font-com.aspose.drawing.Font-int-}
```
public Font(Font prototype, int newStyle)
```


Initialiseert een nieuw exemplaar van de [Font](../../com.aspose.drawing/font) klasse die de opgegeven bestaande [Font](../../com.aspose.drawing/font) en [FontStyle](../../com.aspose.drawing/fontstyle) enumeratie gebruikt.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| prototype | [Font](../../com.aspose.drawing/font) | De bestaande [Font](../../com.aspose.drawing/font) waaruit de nieuwe [Font](../../com.aspose.drawing/font) moet worden gemaakt. |
| newStyle | int | De [FontStyle](../../com.aspose.drawing/fontstyle) die op de nieuwe [Font](../../com.aspose.drawing/font) moet worden toegepast. Meerdere waarden van de [FontStyle](../../com.aspose.drawing/fontstyle) enumeratie kunnen worden gecombineerd met de OR-operator. |

### Font(FontFamily family, float emSize) {#Font-com.aspose.drawing.FontFamily-float-}
```
public Font(FontFamily family, float emSize)
```


Initialiseert een nieuw exemplaar van de [Font](../../com.aspose.drawing/font) klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| family | [FontFamily](../../com.aspose.drawing/fontfamily) | De `FontFamily`([.getFontFamily](../../null/\#getFontFamily)) van de nieuwe [Font](../../com.aspose.drawing/font). |
| emSize | float | De em-grootte, in punten, van het nieuwe lettertype. |

### Font(FontFamily family, float emSize, int style) {#Font-com.aspose.drawing.FontFamily-float-int-}
```
public Font(FontFamily family, float emSize, int style)
```


Initialiseert een nieuw exemplaar van de [Font](../../com.aspose.drawing/font) klasse met een opgegeven grootte en stijl..

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| family | [FontFamily](../../com.aspose.drawing/fontfamily) | De `FontFamily`([.getFontFamily](../../null/\#getFontFamily)) van de nieuwe [Font](../../com.aspose.drawing/font). |
| emSize | float | De em-grootte, in punten, van het nieuwe lettertype. |
| style | int | De [FontStyle](../../com.aspose.drawing/fontstyle) van het nieuwe lettertype. |

### Font(FontFamily family, float emSize, int style, int unit) {#Font-com.aspose.drawing.FontFamily-float-int-int-}
```
public Font(FontFamily family, float emSize, int style, int unit)
```


Initialiseert een nieuw exemplaar van de [Font](../../com.aspose.drawing/font) klasse met een opgegeven grootte, stijl en eenheid.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| family | [FontFamily](../../com.aspose.drawing/fontfamily) | De `FontFamily`([.getFontFamily](../../null/\#getFontFamily)) van de nieuwe [Font](../../com.aspose.drawing/font). |
| emSize | float | De em-grootte van het nieuwe lettertype in de eenheden die zijn opgegeven door de `unit`-parameter. |
| style | int | De [FontStyle](../../com.aspose.drawing/fontstyle) van het nieuwe lettertype. |
| unit | int | De [GraphicsUnit](../../com.aspose.drawing/graphicsunit) van het nieuwe lettertype. |

### Font(FontFamily family, float emSize, int style, int unit, byte gdiCharSet) {#Font-com.aspose.drawing.FontFamily-float-int-int-byte-}
```
public Font(FontFamily family, float emSize, int style, int unit, byte gdiCharSet)
```


Initialiseert een nieuw exemplaar van de [Font](../../com.aspose.drawing/font) klasse met een opgegeven grootte, stijl, eenheid en tekenset..

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| family | [FontFamily](../../com.aspose.drawing/fontfamily) | De `FontFamily`([.getFontFamily](../../null/\#getFontFamily)) van de nieuwe [Font](../../com.aspose.drawing/font). |
| emSize | float | De em-grootte van het nieuwe lettertype in de eenheden die zijn opgegeven door de `unit`-parameter. |
| style | int | De [FontStyle](../../com.aspose.drawing/fontstyle) van het nieuwe lettertype. |
| unit | int | De [GraphicsUnit](../../com.aspose.drawing/graphicsunit) van het nieuwe lettertype. |
| gdiCharSet | byte | GDI-tekenset die voor het nieuwe lettertype moet worden gebruikt. |

### Font(FontFamily family, float emSize, int style, int unit, byte gdiCharSet, boolean gdiVerticalFont) {#Font-com.aspose.drawing.FontFamily-float-int-int-byte-boolean-}
```
public Font(FontFamily family, float emSize, int style, int unit, byte gdiCharSet, boolean gdiVerticalFont)
```


Initialiseert een nieuw exemplaar van de [Font](../../com.aspose.drawing/font) klasse met een opgegeven grootte, stijl, eenheid en tekenset..

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| family | [FontFamily](../../com.aspose.drawing/fontfamily) | De `FontFamily`([.getFontFamily](../../null/\#getFontFamily)) van de nieuwe [Font](../../com.aspose.drawing/font). |
| emSize | float | De em-grootte van het nieuwe lettertype in de eenheden die zijn opgegeven door de `unit`-parameter. |
| style | int | De [FontStyle](../../com.aspose.drawing/fontstyle) van het nieuwe lettertype. |
| unit | int | De [GraphicsUnit](../../com.aspose.drawing/graphicsunit) van het nieuwe lettertype. |
| gdiCharSet | byte | GDI-tekenset die voor het nieuwe lettertype moet worden gebruikt. |
| gdiVerticalFont | boolean | Een Booleaanse waarde die aangeeft of het nieuwe lettertype is afgeleid van een GDI-verticaal lettertype. |

### Font(String familyName, float emSize) {#Font-java.lang.String-float-}
```
public Font(String familyName, float emSize)
```


Initialiseert een nieuw exemplaar van de [Font](../../com.aspose.drawing/font) klasse met een opgegeven grootte.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| familyName | java.lang.String | Een tekenreeksrepresentatie van de FontFamily voor de nieuwe [Font](../../com.aspose.drawing/font). |
| emSize | float | De em-grootte, in punten, van het nieuwe lettertype. |

### Font(String familyName, float emSize, int style) {#Font-java.lang.String-float-int-}
```
public Font(String familyName, float emSize, int style)
```


Initialiseert een nieuw exemplaar van de [Font](../../com.aspose.drawing/font) klasse met een opgegeven grootte en stijl.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| familyName | java.lang.String | Een tekenreeksrepresentatie van de FontFamily voor de nieuwe [Font](../../com.aspose.drawing/font). |
| emSize | float | De em-grootte, in punten, van het nieuwe lettertype. |
| style | int | De [FontStyle](../../com.aspose.drawing/fontstyle) van het nieuwe lettertype. |

### Font(String familyName, float emSize, int style, int unit) {#Font-java.lang.String-float-int-int-}
```
public Font(String familyName, float emSize, int style, int unit)
```


Initialiseert een nieuw exemplaar van de [Font](../../com.aspose.drawing/font) klasse met een opgegeven grootte, stijl en eenheid.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| familyName | java.lang.String | Een tekenreeksrepresentatie van de `FontFamily`([.getFontFamily](../../null/\#getFontFamily)) voor de nieuwe [Font](../../com.aspose.drawing/font). |
| emSize | float | De em-grootte van het nieuwe lettertype in de eenheden die zijn opgegeven door de `unit`-parameter. |
| style | int | De [FontStyle](../../com.aspose.drawing/fontstyle) van het nieuwe lettertype. |
| unit | int | De [GraphicsUnit](../../com.aspose.drawing/graphicsunit) van het nieuwe lettertype. |

### Font(String familyName, float emSize, int style, int unit, byte gdiCharSet) {#Font-java.lang.String-float-int-int-byte-}
```
public Font(String familyName, float emSize, int style, int unit, byte gdiCharSet)
```


Initialiseert een nieuw exemplaar van de [Font](../../com.aspose.drawing/font) klasse met een opgegeven grootte, stijl, eenheid en tekenset.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| familyName | java.lang.String | Een tekenreeksrepresentatie van de FontFamily voor de nieuwe [Font](../../com.aspose.drawing/font). |
| emSize | float | De em-grootte van het nieuwe lettertype in de eenheden die zijn opgegeven door de `unit`-parameter. |
| style | int | De [FontStyle](../../com.aspose.drawing/fontstyle) van het nieuwe lettertype. |
| unit | int | De [GraphicsUnit](../../com.aspose.drawing/graphicsunit) van het nieuwe lettertype. |
| gdiCharSet | byte | Een byte die een GDI-tekenset specificeert die voor dit lettertype moet worden gebruikt. |

### Font(String familyName, float emSize, int style, int unit, byte gdiCharSet, boolean gdiVerticalFont) {#Font-java.lang.String-float-int-int-byte-boolean-}
```
public Font(String familyName, float emSize, int style, int unit, byte gdiCharSet, boolean gdiVerticalFont)
```


Initialiseert een nieuw exemplaar van de [Font](../../com.aspose.drawing/font) klasse met de opgegeven grootte, stijl, eenheid en tekenset.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| familyName | java.lang.String | Een tekenreeksrepresentatie van de FontFamily voor de nieuwe [Font](../../com.aspose.drawing/font). |
| emSize | float | De em-grootte van het nieuwe lettertype in de eenheden die zijn opgegeven door de `unit`-parameter. |
| style | int | De [FontStyle](../../com.aspose.drawing/fontstyle) van het nieuwe lettertype. |
| unit | int | De [GraphicsUnit](../../com.aspose.drawing/graphicsunit) van het nieuwe lettertype. |
| gdiCharSet | byte | Een byte die een GDI-tekenset specificeert die voor dit lettertype moet worden gebruikt. |
| gdiVerticalFont | boolean | Een Booleaanse waarde die aangeeft of de nieuwe [Font](../../com.aspose.drawing/font) is afgeleid van een GDI-verticaal lettertype. |

### getFontFamily() {#getFontFamily--}
```
public FontFamily getFontFamily()
```


Haalt de `FontFamily`([.getFontFamily](../../null/\#getFontFamily)) op die bij deze [Font](../../com.aspose.drawing/font) hoort.

**Returns:**
[FontFamily](../../com.aspose.drawing/fontfamily) - The `FontFamily`([.getFontFamily](../../null/\#getFontFamily)) associated with this [Font](../../com.aspose.drawing/font).
### getBold() {#getBold--}
```
public boolean getBold()
```


Haalt een waarde op die aangeeft of deze [Font](../../com.aspose.drawing/font) vet is.

**Returns:**
boolean - een waarde die aangeeft of dit [Font](../../com.aspose.drawing/font) vet is.
### getGdiCharSet() {#getGdiCharSet--}
```
public byte getGdiCharSet()
```


Haalt een byte‑waarde op die de GDI‑tekenset specificeert die deze [Font](../../com.aspose.drawing/font) gebruikt.

**Returns:**
byte - Een byte‑waarde die de GDI‑tekenset specificeert die dit [Font](../../com.aspose.drawing/font) gebruikt.
### getGdiVerticalFont() {#getGdiVerticalFont--}
```
public boolean getGdiVerticalFont()
```


Haalt een waarde op die aangeeft of deze [Font](../../com.aspose.drawing/font) is afgeleid van een verticale GDI‑lettertype..

Waarde: `true` als dit [Font](../../com.aspose.drawing/font) is afgeleid van een GDI‑verticaal lettertype; anders `false`.

**Returns:**
boolean - een waarde die aangeeft of dit [Font](../../com.aspose.drawing/font) is afgeleid van een GDI‑verticaal lettertype.
### getItalic() {#getItalic--}
```
public boolean getItalic()
```


Haalt een waarde op die aangeeft of deze [Font](../../com.aspose.drawing/font) cursief is.

**Returns:**
boolean - een waarde die aangeeft of dit [Font](../../com.aspose.drawing/font) cursief is.
### getName() {#getName--}
```
public String getName()
```


Haalt de naam van dit [Font](../../com.aspose.drawing/font) op.

**Returns:**
java.lang.String - de gezichtsnaam van dit [Font](../../com.aspose.drawing/font).
### getStrikeout() {#getStrikeout--}
```
public boolean getStrikeout()
```


Haalt een waarde op die aangeeft of dit [Font](../../com.aspose.drawing/font) een horizontale doorstreping specificeert.

**Returns:**
boolean - een waarde die aangeeft of dit [Font](../../com.aspose.drawing/font) een horizontale doorstreping specificeert.
### getUnderline() {#getUnderline--}
```
public boolean getUnderline()
```


Haalt een waarde op die aangeeft of dit [Font](../../com.aspose.drawing/font) onderstreept is.

**Returns:**
boolean - een waarde die aangeeft of dit [Font](../../com.aspose.drawing/font) onderstreept is.
### getStyle() {#getStyle--}
```
public int getStyle()
```


Haalt stijlinformatie op voor dit [Font](../../com.aspose.drawing/font).

**Returns:**
int - stijl‑informatie voor dit [Font](../../com.aspose.drawing/font).
### getSize() {#getSize--}
```
public float getSize()
```


Haalt de em‑grootte van dit [Font](../../com.aspose.drawing/font) op, gemeten in de eenheden die zijn gespecificeerd door de eigenschap `Font.Unit`.

**Returns:**
float - de em‑grootte van dit [Font](../../com.aspose.drawing/font) gemeten in de eenheden gespecificeerd door de \{@code Font.
### getSizeInPoints() {#getSizeInPoints--}
```
public float getSizeInPoints()
```


Haalt de em‑grootte, in punten, van dit [Font](../../com.aspose.drawing/font) op.

**Returns:**
float - De em‑grootte, in punten, van dit [Font](../../com.aspose.drawing/font).
### getUnit() {#getUnit--}
```
public int getUnit()
```


Haalt de meeteenheid voor dit [Font](../../com.aspose.drawing/font) op.

**Returns:**
int - de meeteenheid voor dit [Font](../../com.aspose.drawing/font).
### getHeight_Rename_Namesake() {#getHeight-Rename-Namesake--}
```
public int getHeight_Rename_Namesake()
```


Haalt de regelafstand van dit lettertype op.

Waarde: de regelafstand, in pixels, van dit lettertype.

**Returns:**
int - de regelafstand van dit lettertype.
### isSystemFont() {#isSystemFont--}
```
public boolean isSystemFont()
```


Haalt een waarde op die aangeeft of het lettertype lid is van [SystemFonts](../../com.aspose.drawing/systemfonts).

Waarde: `true` als het lettertype lid is van [SystemFonts](../../com.aspose.drawing/systemfonts); anders `false`.

**Returns:**
boolean - een waarde die aangeeft of het lettertype lid is van [SystemFonts](../../com.aspose.drawing/systemfonts).
### getSystemFontName() {#getSystemFontName--}
```
public String getSystemFontName()
```


Haalt de naam van het systeemlettertype op als de eigenschap IsSystemFont waar is.

Waarde: de naam van het systeemlettertype, als IsSystemFont true retourneert; anders een lege tekenreeks ("").

**Returns:**
java.lang.String - de naam van het systeemlettertype als de IsSystemFont‑eigenschap true retourneert.
### getOriginalFontName() {#getOriginalFontName--}
```
public String getOriginalFontName()
```


Haalt de oorspronkelijk opgegeven naam van het lettertype op.

Waarde: de tekenreeks die de oorspronkelijk opgegeven naam van het lettertype weergeeft.

**Returns:**
java.lang.String - de oorspronkelijk opgegeven naam van het lettertype.
### deepClone() {#deepClone--}
```
public Font deepClone()
```


Maakt een exacte kopie van dit [Font](../../com.aspose.drawing/font).

**Returns:**
[Font](../../com.aspose.drawing/font) - The [Font](../../com.aspose.drawing/font) this method creates, cast as an Object.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Geeft aan of het opgegeven object een [Font](../../com.aspose.drawing/font) is en dezelfde `FontFamily`([.getFontFamily](../../null/\#getFontFamily)), `M:GdiVerticalFont`, `M:GdiCharSet`, `M:Style`, `M:Size` en `M:Unit` eigenschapswaarden heeft als deze [Font](../../com.aspose.drawing/font).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | java.lang.Object | Het object om te testen. |

**Returns:**
boolean - `true` als de obj‑parameter een [Font](../../com.aspose.drawing/font) is en dezelfde `FontFamily`([.getFontFamily](../../null/\#getFontFamily)), `M:GdiVerticalFont`, `M:GdiCharSet`, `M:Style`, `M:Size` en `M:Unit`‑eigenschapswaarden heeft als dit [Font](../../com.aspose.drawing/font); anders `false`.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Haalt de hashcode op voor deze [Font](../../com.aspose.drawing/font).

**Returns:**
int - De hashcode voor dit [Font](../../com.aspose.drawing/font).
### getHeight() {#getHeight--}
```
public int getHeight()
```


Retourneert de regelafstand, in pixels, van dit lettertype.

**Returns:**
int - De regelafstand, in pixels, van dit lettertype.
### getHeight(Graphics graphics) {#getHeight-com.aspose.drawing.Graphics-}
```
public float getHeight(Graphics graphics)
```


Retourneert de regelafstand, in de huidige eenheid van een opgegeven [Graphics](../../com.aspose.drawing/graphics), van dit lettertype.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| graphics | [Graphics](../../com.aspose.drawing/graphics) | Een [Graphics](../../com.aspose.drawing/graphics) die de verticale resolutie, in dots per inch, van het weergaveapparaat bevat, evenals instellingen voor paginabereik en paginaverschaling. |

**Returns:**
float - De regelafstand, in pixels, van dit lettertype.
### getHeight(float dpi) {#getHeight-float-}
```
public int getHeight(float dpi)
```


Retourneert de hoogte, in pixels, van dit [Font](../../com.aspose.drawing/font) wanneer getekend op een apparaat met de opgegeven verticale resolutie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| dpi | float | De verticale resolutie, in dots per inch, die wordt gebruikt om de hoogte van het lettertype te berekenen. |

**Returns:**
int - De hoogte, in pixels, van dit [Font](../../com.aspose.drawing/font).
### dispose() {#dispose--}
```
public void dispose()
```


Geeft alle bronnen vrij die door dit [Font](../../com.aspose.drawing/font) worden gebruikt.

### toString() {#toString--}
```
public String toString()
```


Retourneert een menselijk leesbare tekenreeksrepresentatie van dit [Font](../../com.aspose.drawing/font).

**Returns:**
java.lang.String - Een string die dit [Font](../../com.aspose.drawing/font) vertegenwoordigt.
### getCharacterSet() {#getCharacterSet--}
```
public int getCharacterSet()
```


Haalt een bytewaarde op die de tekenset specificeert die deze `Font` gebruikt.

**Returns:**
int - Een tekenset die dit `Font` gebruikt.
