---
title: Font
second_title: Aspose.Drawing för Java API‑referens
description: Definierar ett specifikt format för text inklusive teckensnitt, storlek och stilattribut.
type: docs
weight: 21
url: /sv/java/com.aspose.drawing/font/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public final class Font implements System.IDisposable
```

Definierar ett specifikt format för text, inklusive teckensnitt, storlek och stilattribut. Denna klass kan inte ärvas.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [Font(Font prototype, int newStyle)](#Font-com.aspose.drawing.Font-int-) | Initierar en ny instans av klassen [Font](../../com.aspose.drawing/font) som använder den angivna befintliga [Font](../../com.aspose.drawing/font) och [FontStyle](../../com.aspose.drawing/fontstyle) uppräkningen. |
| [Font(FontFamily family, float emSize)](#Font-com.aspose.drawing.FontFamily-float-) | Initierar en ny instans av klassen [Font](../../com.aspose.drawing/font). |
| [Font(FontFamily family, float emSize, int style)](#Font-com.aspose.drawing.FontFamily-float-int-) | Initierar en ny instans av klassen [Font](../../com.aspose.drawing/font) med en angiven storlek och stil.. |
| [Font(FontFamily family, float emSize, int style, int unit)](#Font-com.aspose.drawing.FontFamily-float-int-int-) | Initierar en ny instans av klassen [Font](../../com.aspose.drawing/font) med en angiven storlek, stil och enhet. |
| [Font(FontFamily family, float emSize, int style, int unit, byte gdiCharSet)](#Font-com.aspose.drawing.FontFamily-float-int-int-byte-) | Initierar en ny instans av klassen [Font](../../com.aspose.drawing/font) med en angiven storlek, stil, enhet och teckenuppsättning.. |
| [Font(FontFamily family, float emSize, int style, int unit, byte gdiCharSet, boolean gdiVerticalFont)](#Font-com.aspose.drawing.FontFamily-float-int-int-byte-boolean-) | Initierar en ny instans av klassen [Font](../../com.aspose.drawing/font) med en angiven storlek, stil, enhet och teckenuppsättning.. |
| [Font(String familyName, float emSize)](#Font-java.lang.String-float-) | Initierar en ny instans av klassen [Font](../../com.aspose.drawing/font) med en angiven storlek. |
| [Font(String familyName, float emSize, int style)](#Font-java.lang.String-float-int-) | Initierar en ny instans av klassen [Font](../../com.aspose.drawing/font) med en angiven storlek och stil. |
| [Font(String familyName, float emSize, int style, int unit)](#Font-java.lang.String-float-int-int-) | Initierar en ny instans av klassen [Font](../../com.aspose.drawing/font) med en angiven storlek, stil och enhet. |
| [Font(String familyName, float emSize, int style, int unit, byte gdiCharSet)](#Font-java.lang.String-float-int-int-byte-) | Initierar en ny instans av klassen [Font](../../com.aspose.drawing/font) med en angiven storlek, stil, enhet och teckenuppsättning. |
| [Font(String familyName, float emSize, int style, int unit, byte gdiCharSet, boolean gdiVerticalFont)](#Font-java.lang.String-float-int-int-byte-boolean-) | Initierar en ny instans av klassen [Font](../../com.aspose.drawing/font) med den angivna storleken, stilen, enheten och teckenuppsättningen. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getFontFamily()](#getFontFamily--) | Hämtar `FontFamily`([.getFontFamily](../../null/\\#getFontFamily)) som är associerad med detta [Font](../../com.aspose.drawing/font). |
| [getBold()](#getBold--) | Hämtar ett värde som indikerar om detta [Font](../../com.aspose.drawing/font) är fetstil. |
| [getGdiCharSet()](#getGdiCharSet--) | Hämtar ett bytevärde som specificerar GDI-teckenuppsättningen som detta [Font](../../com.aspose.drawing/font) använder. |
| [getGdiVerticalFont()](#getGdiVerticalFont--) | Hämtar ett värde som indikerar om detta [Font](../../com.aspose.drawing/font) är härlett från ett vertikalt GDI-typsnitt.. |
| [getItalic()](#getItalic--) | Hämtar ett värde som indikerar om detta [Font](../../com.aspose.drawing/font) är kursivt. |
| [getName()](#getName--) | Hämtar typsnittets namn för detta [Font](../../com.aspose.drawing/font). |
| [getStrikeout()](#getStrikeout--) | Hämtar ett värde som indikerar om detta [Font](../../com.aspose.drawing/font) specificerar ett horisontellt streck genom typsnittet. |
| [getUnderline()](#getUnderline--) | Hämtar ett värde som indikerar om detta [Font](../../com.aspose.drawing/font) är understruket. |
| [getStyle()](#getStyle--) | Hämtar stilinformation för detta [Font](../../com.aspose.drawing/font). |
| [getSize()](#getSize--) | Hämtar em-storleken för detta [Font](../../com.aspose.drawing/font) mätt i de enheter som anges av egenskapen `Font.Unit`. |
| [getSizeInPoints()](#getSizeInPoints--) | Hämtar em-storleken, i punkter, för detta [Font](../../com.aspose.drawing/font). |
| [getUnit()](#getUnit--) | Hämtar måttenheten för detta [Font](../../com.aspose.drawing/font). |
| [getHeight_Rename_Namesake()](#getHeight-Rename-Namesake--) | Hämtar radavståndet för detta typsnitt. |
| [isSystemFont()](#isSystemFont--) | Hämtar ett värde som indikerar om typsnittet är en medlem av [SystemFonts](../../com.aspose.drawing/systemfonts). |
| [getSystemFontName()](#getSystemFontName--) | Hämtar namnet på systemtypsnittet om egenskapen IsSystemFont returnerar true. |
| [getOriginalFontName()](#getOriginalFontName--) | Hämtar namnet på det ursprungligen angivna typsnittet. |
| [deepClone()](#deepClone--) | Skapar en exakt kopia av detta [Font](../../com.aspose.drawing/font). |
| [equals(Object obj)](#equals-java.lang.Object-) | Anger om det angivna objektet är ett [Font](../../com.aspose.drawing/font) och har samma `FontFamily`([.getFontFamily](../../null/\#getFontFamily)), `M:GdiVerticalFont`, `M:GdiCharSet`, `M:Style`, `M:Size` och `M:Unit` egenskapsvärden som detta [Font](../../com.aspose.drawing/font). |
| [hashCode()](#hashCode--) | Hämtar hash‑koden för detta [Font](../../com.aspose.drawing/font). |
| [getHeight()](#getHeight--) | Returnerar radavståndet, i pixlar, för detta teckensnitt. |
| [getHeight(Graphics graphics)](#getHeight-com.aspose.drawing.Graphics-) | Returnerar radavståndet, i den aktuella enheten för en specificerad [Graphics](../../com.aspose.drawing/graphics), för detta teckensnitt. |
| [getHeight(float dpi)](#getHeight-float-) | Returnerar höjden, i pixlar, för detta [Font](../../com.aspose.drawing/font) när det ritas till en enhet med den angivna vertikala upplösningen. |
| [dispose()](#dispose--) | Frigör alla resurser som används av detta [Font](../../com.aspose.drawing/font). |
| [toString()](#toString--) | Returnerar en människoläsbar strängrepresentation av detta [Font](../../com.aspose.drawing/font). |
| [getCharacterSet()](#getCharacterSet--) | Hämtar ett byte‑värde som specificerar teckenuppsättningen som detta `Font` använder. |
### Font(Font prototype, int newStyle) {#Font-com.aspose.drawing.Font-int-}
```
public Font(Font prototype, int newStyle)
```


Initierar en ny instans av klassen [Font](../../com.aspose.drawing/font) som använder den angivna befintliga [Font](../../com.aspose.drawing/font) och [FontStyle](../../com.aspose.drawing/fontstyle) uppräkningen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| prototype | [Font](../../com.aspose.drawing/font) | Det befintliga [Font](../../com.aspose.drawing/font) som den nya [Font](../../com.aspose.drawing/font) ska skapas från. |
| newStyle | int | Den [FontStyle](../../com.aspose.drawing/fontstyle) som ska tillämpas på den nya [Font](../../com.aspose.drawing/font). Flera värden i [FontStyle](../../com.aspose.drawing/fontstyle)-enumerationen kan kombineras med OR‑operatorn. |

### Font(FontFamily family, float emSize) {#Font-com.aspose.drawing.FontFamily-float-}
```
public Font(FontFamily family, float emSize)
```


Initierar en ny instans av klassen [Font](../../com.aspose.drawing/font).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| family | [FontFamily](../../com.aspose.drawing/fontfamily) | `FontFamily`([.getFontFamily](../../null/\#getFontFamily)) för den nya [Font](../../com.aspose.drawing/font). |
| emSize | flyttal | Em‑storleken, i punkter, för det nya teckensnittet. |

### Font(FontFamily family, float emSize, int style) {#Font-com.aspose.drawing.FontFamily-float-int-}
```
public Font(FontFamily family, float emSize, int style)
```


Initierar en ny instans av klassen [Font](../../com.aspose.drawing/font) med en angiven storlek och stil..

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| family | [FontFamily](../../com.aspose.drawing/fontfamily) | `FontFamily`([.getFontFamily](../../null/\#getFontFamily)) för den nya [Font](../../com.aspose.drawing/font). |
| emSize | flyttal | Em‑storleken, i punkter, för det nya teckensnittet. |
| style | int | [FontStyle](../../com.aspose.drawing/fontstyle) för det nya teckensnittet. |

### Font(FontFamily family, float emSize, int style, int unit) {#Font-com.aspose.drawing.FontFamily-float-int-int-}
```
public Font(FontFamily family, float emSize, int style, int unit)
```


Initierar en ny instans av klassen [Font](../../com.aspose.drawing/font) med en angiven storlek, stil och enhet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| family | [FontFamily](../../com.aspose.drawing/fontfamily) | `FontFamily`([.getFontFamily](../../null/\#getFontFamily)) för den nya [Font](../../com.aspose.drawing/font). |
| emSize | flyttal | Em‑storleken för det nya teckensnittet i de enheter som anges av parametern `unit`. |
| style | int | [FontStyle](../../com.aspose.drawing/fontstyle) för det nya teckensnittet. |
| unit | int | [GraphicsUnit](../../com.aspose.drawing/graphicsunit) för det nya teckensnittet. |

### Font(FontFamily family, float emSize, int style, int unit, byte gdiCharSet) {#Font-com.aspose.drawing.FontFamily-float-int-int-byte-}
```
public Font(FontFamily family, float emSize, int style, int unit, byte gdiCharSet)
```


Initierar en ny instans av klassen [Font](../../com.aspose.drawing/font) med en angiven storlek, stil, enhet och teckenuppsättning..

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| family | [FontFamily](../../com.aspose.drawing/fontfamily) | `FontFamily`([.getFontFamily](../../null/\#getFontFamily)) för den nya [Font](../../com.aspose.drawing/font). |
| emSize | flyttal | Em‑storleken för det nya teckensnittet i de enheter som anges av parametern `unit`. |
| style | int | [FontStyle](../../com.aspose.drawing/fontstyle) för det nya teckensnittet. |
| unit | int | [GraphicsUnit](../../com.aspose.drawing/graphicsunit) för det nya teckensnittet. |
| gdiCharSet | byte | GDI‑teckenuppsättning att använda för det nya teckensnittet. |

### Font(FontFamily family, float emSize, int style, int unit, byte gdiCharSet, boolean gdiVerticalFont) {#Font-com.aspose.drawing.FontFamily-float-int-int-byte-boolean-}
```
public Font(FontFamily family, float emSize, int style, int unit, byte gdiCharSet, boolean gdiVerticalFont)
```


Initierar en ny instans av klassen [Font](../../com.aspose.drawing/font) med en angiven storlek, stil, enhet och teckenuppsättning..

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| family | [FontFamily](../../com.aspose.drawing/fontfamily) | `FontFamily`([.getFontFamily](../../null/\#getFontFamily)) för den nya [Font](../../com.aspose.drawing/font). |
| emSize | flyttal | Em‑storleken för det nya teckensnittet i de enheter som anges av parametern `unit`. |
| style | int | [FontStyle](../../com.aspose.drawing/fontstyle) för det nya teckensnittet. |
| unit | int | [GraphicsUnit](../../com.aspose.drawing/graphicsunit) för det nya teckensnittet. |
| gdiCharSet | byte | GDI‑teckenuppsättning att använda för det nya teckensnittet. |
| gdiVerticalFont | boolean | Ett booleskt värde som indikerar om det nya teckensnittet är härlett från ett GDI‑vertikalt teckensnitt. |

### Font(String familyName, float emSize) {#Font-java.lang.String-float-}
```
public Font(String familyName, float emSize)
```


Initierar en ny instans av klassen [Font](../../com.aspose.drawing/font) med en angiven storlek.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| familyName | java.lang.String | En strängrepresentation av FontFamily för den nya [Font](../../com.aspose.drawing/font). |
| emSize | flyttal | Em‑storleken, i punkter, för det nya teckensnittet. |

### Font(String familyName, float emSize, int style) {#Font-java.lang.String-float-int-}
```
public Font(String familyName, float emSize, int style)
```


Initierar en ny instans av klassen [Font](../../com.aspose.drawing/font) med en angiven storlek och stil.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| familyName | java.lang.String | En strängrepresentation av FontFamily för den nya [Font](../../com.aspose.drawing/font). |
| emSize | flyttal | Em‑storleken, i punkter, för det nya teckensnittet. |
| style | int | [FontStyle](../../com.aspose.drawing/fontstyle) för det nya teckensnittet. |

### Font(String familyName, float emSize, int style, int unit) {#Font-java.lang.String-float-int-int-}
```
public Font(String familyName, float emSize, int style, int unit)
```


Initierar en ny instans av klassen [Font](../../com.aspose.drawing/font) med en angiven storlek, stil och enhet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| familyName | java.lang.String | En strängrepresentation av `FontFamily`([.getFontFamily](../../null/\#getFontFamily)) för den nya [Font](../../com.aspose.drawing/font). |
| emSize | flyttal | Em‑storleken för det nya teckensnittet i de enheter som anges av parametern `unit`. |
| style | int | [FontStyle](../../com.aspose.drawing/fontstyle) för det nya teckensnittet. |
| unit | int | [GraphicsUnit](../../com.aspose.drawing/graphicsunit) för det nya teckensnittet. |

### Font(String familyName, float emSize, int style, int unit, byte gdiCharSet) {#Font-java.lang.String-float-int-int-byte-}
```
public Font(String familyName, float emSize, int style, int unit, byte gdiCharSet)
```


Initierar en ny instans av klassen [Font](../../com.aspose.drawing/font) med en angiven storlek, stil, enhet och teckenuppsättning.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| familyName | java.lang.String | En strängrepresentation av FontFamily för den nya [Font](../../com.aspose.drawing/font). |
| emSize | flyttal | Em‑storleken för det nya teckensnittet i de enheter som anges av parametern `unit`. |
| style | int | [FontStyle](../../com.aspose.drawing/fontstyle) för det nya teckensnittet. |
| unit | int | [GraphicsUnit](../../com.aspose.drawing/graphicsunit) för det nya teckensnittet. |
| gdiCharSet | byte | Ett byte som specificerar en GDI‑teckenuppsättning att använda för detta teckensnitt. |

### Font(String familyName, float emSize, int style, int unit, byte gdiCharSet, boolean gdiVerticalFont) {#Font-java.lang.String-float-int-int-byte-boolean-}
```
public Font(String familyName, float emSize, int style, int unit, byte gdiCharSet, boolean gdiVerticalFont)
```


Initierar en ny instans av klassen [Font](../../com.aspose.drawing/font) med den angivna storleken, stilen, enheten och teckenuppsättningen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| familyName | java.lang.String | En strängrepresentation av FontFamily för den nya [Font](../../com.aspose.drawing/font). |
| emSize | flyttal | Em‑storleken för det nya teckensnittet i de enheter som anges av parametern `unit`. |
| style | int | [FontStyle](../../com.aspose.drawing/fontstyle) för det nya teckensnittet. |
| unit | int | [GraphicsUnit](../../com.aspose.drawing/graphicsunit) för det nya teckensnittet. |
| gdiCharSet | byte | Ett byte som specificerar en GDI‑teckenuppsättning att använda för detta teckensnitt. |
| gdiVerticalFont | boolean | Ett booleskt värde som indikerar om den nya [Font](../../com.aspose.drawing/font) är härledd från ett GDI‑vertikalt teckensnitt. |

### getFontFamily() {#getFontFamily--}
```
public FontFamily getFontFamily()
```


Hämtar `FontFamily`([.getFontFamily](../../null/\\#getFontFamily)) som är associerad med detta [Font](../../com.aspose.drawing/font).

**Returns:**
[FontFamily](../../com.aspose.drawing/fontfamily) - The `FontFamily`([.getFontFamily](../../null/\#getFontFamily)) associated with this [Font](../../com.aspose.drawing/font).
### getBold() {#getBold--}
```
public boolean getBold()
```


Hämtar ett värde som indikerar om detta [Font](../../com.aspose.drawing/font) är fetstil.

**Returns:**
boolean - ett värde som indikerar om denna [Font](../../com.aspose.drawing/font) är fet.
### getGdiCharSet() {#getGdiCharSet--}
```
public byte getGdiCharSet()
```


Hämtar ett bytevärde som specificerar GDI-teckenuppsättningen som detta [Font](../../com.aspose.drawing/font) använder.

**Returns:**
byte - Ett byte‑värde som specificerar den GDI-teckenuppsättning som denna [Font](../../com.aspose.drawing/font) använder.
### getGdiVerticalFont() {#getGdiVerticalFont--}
```
public boolean getGdiVerticalFont()
```


Hämtar ett värde som indikerar om detta [Font](../../com.aspose.drawing/font) är härlett från ett vertikalt GDI-typsnitt..

Värde: `true` om denna [Font](../../com.aspose.drawing/font) är härledd från ett GDI‑vertikalt teckensnitt; annars `false`.

**Returns:**
boolean - ett värde som indikerar om denna [Font](../../com.aspose.drawing/font) är härledd från ett GDI‑vertikalt teckensnitt.
### getItalic() {#getItalic--}
```
public boolean getItalic()
```


Hämtar ett värde som indikerar om detta [Font](../../com.aspose.drawing/font) är kursivt.

**Returns:**
boolean - ett värde som indikerar om denna [Font](../../com.aspose.drawing/font) är kursiv.
### getName() {#getName--}
```
public String getName()
```


Hämtar typsnittets namn för detta [Font](../../com.aspose.drawing/font).

**Returns:**
java.lang.String - teckensnittets namn för detta [Font](../../com.aspose.drawing/font).
### getStrikeout() {#getStrikeout--}
```
public boolean getStrikeout()
```


Hämtar ett värde som indikerar om detta [Font](../../com.aspose.drawing/font) specificerar ett horisontellt streck genom typsnittet.

**Returns:**
boolean - ett värde som indikerar om denna [Font](../../com.aspose.drawing/font) specificerar ett horisontellt streck genom teckensnittet.
### getUnderline() {#getUnderline--}
```
public boolean getUnderline()
```


Hämtar ett värde som indikerar om detta [Font](../../com.aspose.drawing/font) är understruket.

**Returns:**
boolean - ett värde som indikerar om denna [Font](../../com.aspose.drawing/font) är understruken.
### getStyle() {#getStyle--}
```
public int getStyle()
```


Hämtar stilinformation för detta [Font](../../com.aspose.drawing/font).

**Returns:**
int - stilinformation för detta [Font](../../com.aspose.drawing/font).
### getSize() {#getSize--}
```
public float getSize()
```


Hämtar em-storleken för detta [Font](../../com.aspose.drawing/font) mätt i de enheter som anges av egenskapen `Font.Unit`.

**Returns:**
float - em‑storleken för detta [Font](../../com.aspose.drawing/font) mätt i enheterna som anges av \{@code Font.
### getSizeInPoints() {#getSizeInPoints--}
```
public float getSizeInPoints()
```


Hämtar em-storleken, i punkter, för detta [Font](../../com.aspose.drawing/font).

**Returns:**
float - Em‑storleken, i punkter, för detta [Font](../../com.aspose.drawing/font).
### getUnit() {#getUnit--}
```
public int getUnit()
```


Hämtar måttenheten för detta [Font](../../com.aspose.drawing/font).

**Returns:**
int - måttenheten för detta [Font](../../com.aspose.drawing/font).
### getHeight_Rename_Namesake() {#getHeight-Rename-Namesake--}
```
public int getHeight_Rename_Namesake()
```


Hämtar radavståndet för detta typsnitt.

Värde: radavståndet, i pixlar, för detta teckensnitt.

**Returns:**
int - radavståndet för detta teckensnitt.
### isSystemFont() {#isSystemFont--}
```
public boolean isSystemFont()
```


Hämtar ett värde som indikerar om typsnittet är en medlem av [SystemFonts](../../com.aspose.drawing/systemfonts).

Värde: `true` om teckensnittet är en medlem av [SystemFonts](../../com.aspose.drawing/systemfonts); annars `false`.

**Returns:**
boolean - ett värde som indikerar om teckensnittet är en medlem av [SystemFonts](../../com.aspose.drawing/systemfonts).
### getSystemFontName() {#getSystemFontName--}
```
public String getSystemFontName()
```


Hämtar namnet på systemtypsnittet om egenskapen IsSystemFont returnerar true.

Värde: namnet på systemteckensnittet, om IsSystemFont returnerar true; annars en tom sträng ("").

**Returns:**
java.lang.String - namnet på systemteckensnittet om egenskapen IsSystemFont returnerar true.
### getOriginalFontName() {#getOriginalFontName--}
```
public String getOriginalFontName()
```


Hämtar namnet på det ursprungligen angivna typsnittet.

Värde: strängen som representerar namnet på det ursprungligen angivna teckensnittet.

**Returns:**
java.lang.String - namnet på det ursprungligen angivna teckensnittet.
### deepClone() {#deepClone--}
```
public Font deepClone()
```


Skapar en exakt kopia av detta [Font](../../com.aspose.drawing/font).

**Returns:**
[Font](../../com.aspose.drawing/font) - The [Font](../../com.aspose.drawing/font) this method creates, cast as an Object.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Anger om det angivna objektet är ett [Font](../../com.aspose.drawing/font) och har samma `FontFamily`([.getFontFamily](../../null/\#getFontFamily)), `M:GdiVerticalFont`, `M:GdiCharSet`, `M:Style`, `M:Size` och `M:Unit` egenskapsvärden som detta [Font](../../com.aspose.drawing/font).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | java.lang.Object | Objektet att testa. |

**Returns:**
boolean - `true` om obj‑parametern är ett [Font](../../com.aspose.drawing/font) och har samma `FontFamily`([.getFontFamily](../../null/\#getFontFamily)), `M:GdiVerticalFont`, `M:GdiCharSet`, `M:Style`, `M:Size` och `M:Unit`‑egenskapsvärden som detta [Font](../../com.aspose.drawing/font); annars `false`.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Hämtar hash‑koden för detta [Font](../../com.aspose.drawing/font).

**Returns:**
int - hash‑koden för detta [Font](../../com.aspose.drawing/font).
### getHeight() {#getHeight--}
```
public int getHeight()
```


Returnerar radavståndet, i pixlar, för detta teckensnitt.

**Returns:**
int - radavståndet, i pixlar, för detta teckensnitt.
### getHeight(Graphics graphics) {#getHeight-com.aspose.drawing.Graphics-}
```
public float getHeight(Graphics graphics)
```


Returnerar radavståndet, i den aktuella enheten för en specificerad [Graphics](../../com.aspose.drawing/graphics), för detta teckensnitt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| graphics | [Graphics](../../com.aspose.drawing/graphics) | En [Graphics](../../com.aspose.drawing/graphics) som innehåller den vertikala upplösningen, i punkter per tum, för displayenheten samt inställningar för sidans enhet och sidans skala. |

**Returns:**
float - radavståndet, i pixlar, för detta teckensnitt.
### getHeight(float dpi) {#getHeight-float-}
```
public int getHeight(float dpi)
```


Returnerar höjden, i pixlar, för detta [Font](../../com.aspose.drawing/font) när det ritas till en enhet med den angivna vertikala upplösningen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dpi | flyttal | Den vertikala upplösningen, i punkter per tum, som används för att beräkna teckensnittets höjd. |

**Returns:**
int - Höjden, i pixlar, för detta [Font](../../com.aspose.drawing/font).
### dispose() {#dispose--}
```
public void dispose()
```


Frigör alla resurser som används av detta [Font](../../com.aspose.drawing/font).

### toString() {#toString--}
```
public String toString()
```


Returnerar en människoläsbar strängrepresentation av detta [Font](../../com.aspose.drawing/font).

**Returns:**
java.lang.String - En sträng som representerar detta [Font](../../com.aspose.drawing/font).
### getCharacterSet() {#getCharacterSet--}
```
public int getCharacterSet()
```


Hämtar ett byte‑värde som specificerar teckenuppsättningen som detta `Font` använder.

**Returns:**
int - En teckenuppsättning som detta `Font` använder.
