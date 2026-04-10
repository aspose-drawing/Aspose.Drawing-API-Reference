---
title: Font
second_title: Référence de l'API Aspose.Drawing pour Java
description: Définit un format particulier pour le texte incluant la police, la taille et les attributs de style.
type: docs
weight: 21
url: /fr/java/com.aspose.drawing/font/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public final class Font implements System.IDisposable
```

Définit un format particulier pour le texte, incluant la police, la taille et les attributs de style. Cette classe ne peut pas être héritée.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Font(Font prototype, int newStyle)](#Font-com.aspose.drawing.Font-int-) | Initialise une nouvelle instance de la classe [Font](../../com.aspose.drawing/font) en utilisant la [Font](../../com.aspose.drawing/font) existante spécifiée et l'énumération [FontStyle](../../com.aspose.drawing/fontstyle). |
| [Font(FontFamily family, float emSize)](#Font-com.aspose.drawing.FontFamily-float-) | Initialise une nouvelle instance de la classe [Font](../../com.aspose.drawing/font). |
| [Font(FontFamily family, float emSize, int style)](#Font-com.aspose.drawing.FontFamily-float-int-) | Initialise une nouvelle instance de la classe [Font](../../com.aspose.drawing/font) en utilisant une taille et un style spécifiés.. |
| [Font(FontFamily family, float emSize, int style, int unit)](#Font-com.aspose.drawing.FontFamily-float-int-int-) | Initialise une nouvelle instance de la classe [Font](../../com.aspose.drawing/font) en utilisant une taille, un style et une unité spécifiés. |
| [Font(FontFamily family, float emSize, int style, int unit, byte gdiCharSet)](#Font-com.aspose.drawing.FontFamily-float-int-int-byte-) | Initialise une nouvelle instance de la classe [Font](../../com.aspose.drawing/font) en utilisant une taille, un style, une unité et un jeu de caractères spécifiés.. |
| [Font(FontFamily family, float emSize, int style, int unit, byte gdiCharSet, boolean gdiVerticalFont)](#Font-com.aspose.drawing.FontFamily-float-int-int-byte-boolean-) | Initialise une nouvelle instance de la classe [Font](../../com.aspose.drawing/font) en utilisant une taille, un style, une unité et un jeu de caractères spécifiés.. |
| [Font(String familyName, float emSize)](#Font-java.lang.String-float-) | Initialise une nouvelle instance de la classe [Font](../../com.aspose.drawing/font) en utilisant une taille spécifiée. |
| [Font(String familyName, float emSize, int style)](#Font-java.lang.String-float-int-) | Initialise une nouvelle instance de la classe [Font](../../com.aspose.drawing/font) en utilisant une taille et un style spécifiés. |
| [Font(String familyName, float emSize, int style, int unit)](#Font-java.lang.String-float-int-int-) | Initialise une nouvelle instance de la classe [Font](../../com.aspose.drawing/font) en utilisant une taille, un style et une unité spécifiés. |
| [Font(String familyName, float emSize, int style, int unit, byte gdiCharSet)](#Font-java.lang.String-float-int-int-byte-) | Initialise une nouvelle instance de la classe [Font](../../com.aspose.drawing/font) en utilisant une taille, un style, une unité et un jeu de caractères spécifiés. |
| [Font(String familyName, float emSize, int style, int unit, byte gdiCharSet, boolean gdiVerticalFont)](#Font-java.lang.String-float-int-int-byte-boolean-) | Initialise une nouvelle instance de la classe [Font](../../com.aspose.drawing/font) en utilisant la taille, le style, l'unité et le jeu de caractères spécifiés. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getFontFamily()](#getFontFamily--) | Obtient le `FontFamily`([.getFontFamily](../../null/\#getFontFamily)) associé à ce [Font](../../com.aspose.drawing/font). |
| [getBold()](#getBold--) | Obtient une valeur indiquant si ce [Font](../../com.aspose.drawing/font) est en gras. |
| [getGdiCharSet()](#getGdiCharSet--) | Obtient une valeur byte qui spécifie le jeu de caractères GDI utilisé par ce [Font](../../com.aspose.drawing/font). |
| [getGdiVerticalFont()](#getGdiVerticalFont--) | Obtient une valeur indiquant si ce [Font](../../com.aspose.drawing/font) est dérivé d'une police verticale GDI.. |
| [getItalic()](#getItalic--) | Obtient une valeur indiquant si ce [Font](../../com.aspose.drawing/font) est en italique. |
| [getName()](#getName--) | Obtient le nom de la police de ce [Font](../../com.aspose.drawing/font). |
| [getStrikeout()](#getStrikeout--) | Obtient une valeur indiquant si ce [Font](../../com.aspose.drawing/font) spécifie une ligne horizontale traversant la police. |
| [getUnderline()](#getUnderline--) | Obtient une valeur indiquant si ce [Font](../../com.aspose.drawing/font) est souligné. |
| [getStyle()](#getStyle--) | Obtient les informations de style pour ce [Font](../../com.aspose.drawing/font). |
| [getSize()](#getSize--) | Obtient la taille en em de ce [Font](../../com.aspose.drawing/font) mesurée dans les unités spécifiées par la propriété `Font.Unit`. |
| [getSizeInPoints()](#getSizeInPoints--) | Obtient la taille en em, en points, de ce [Font](../../com.aspose.drawing/font). |
| [getUnit()](#getUnit--) | Obtient l'unité de mesure de ce [Font](../../com.aspose.drawing/font). |
| [getHeight_Rename_Namesake()](#getHeight-Rename-Namesake--) | Obtient l'interligne de cette police. |
| [isSystemFont()](#isSystemFont--) | Obtient une valeur indiquant si la police est un membre de [SystemFonts](../../com.aspose.drawing/systemfonts). |
| [getSystemFontName()](#getSystemFontName--) | Obtient le nom de la police système si la propriété IsSystemFont renvoie vrai. |
| [getOriginalFontName()](#getOriginalFontName--) | Obtient le nom de la police tel qu'il a été spécifié à l'origine. |
| [deepClone()](#deepClone--) | Crée une copie exacte de ce [Font](../../com.aspose.drawing/font). |
| [equals(Object obj)](#equals-java.lang.Object-) | Indique si l'objet spécifié est une [Font](../../com.aspose.drawing/font) et possède les mêmes valeurs de propriétés `FontFamily`([.getFontFamily](../../null/\#getFontFamily)), `M:GdiVerticalFont`, `M:GdiCharSet`, `M:Style`, `M:Size` et `M:Unit` que cette [Font](../../com.aspose.drawing/font). |
| [hashCode()](#hashCode--) | Obtient le code de hachage pour cette [Font](../../com.aspose.drawing/font). |
| [getHeight()](#getHeight--) | Renvoie l'interligne, en pixels, de cette police. |
| [getHeight(Graphics graphics)](#getHeight-com.aspose.drawing.Graphics-) | Renvoie l'interligne, dans l'unité actuelle d'un [Graphics](../../com.aspose.drawing/graphics) spécifié, de cette police. |
| [getHeight(float dpi)](#getHeight-float-) | Renvoie la hauteur, en pixels, de cette [Font](../../com.aspose.drawing/font) lorsqu'elle est dessinée sur un dispositif avec la résolution verticale spécifiée. |
| [dispose()](#dispose--) | Libère toutes les ressources utilisées par cette [Font](../../com.aspose.drawing/font). |
| [toString()](#toString--) | Renvoie une représentation sous forme de chaîne lisible par l'homme de cette [Font](../../com.aspose.drawing/font). |
| [getCharacterSet()](#getCharacterSet--) | Obtient une valeur d'octet qui spécifie le jeu de caractères utilisé par ce `Font`. |
### Font(Font prototype, int newStyle) {#Font-com.aspose.drawing.Font-int-}
```
public Font(Font prototype, int newStyle)
```


Initialise une nouvelle instance de la classe [Font](../../com.aspose.drawing/font) en utilisant la [Font](../../com.aspose.drawing/font) existante spécifiée et l'énumération [FontStyle](../../com.aspose.drawing/fontstyle).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| prototype | [Font](../../com.aspose.drawing/font) | La [Font](../../com.aspose.drawing/font) existante à partir de laquelle créer la nouvelle [Font](../../com.aspose.drawing/font). |
| newStyle | int | Le [FontStyle](../../com.aspose.drawing/fontstyle) à appliquer à la nouvelle [Font](../../com.aspose.drawing/font). Plusieurs valeurs de l'énumération [FontStyle](../../com.aspose.drawing/fontstyle) peuvent être combinées avec l'opérateur OR. |

### Font(FontFamily family, float emSize) {#Font-com.aspose.drawing.FontFamily-float-}
```
public Font(FontFamily family, float emSize)
```


Initialise une nouvelle instance de la classe [Font](../../com.aspose.drawing/font).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| family | [FontFamily](../../com.aspose.drawing/fontfamily) | Le `FontFamily`([.getFontFamily](../../null/\#getFontFamily)) de la nouvelle [Font](../../com.aspose.drawing/font). |
| emSize | float | La taille em, en points, de la nouvelle police. |

### Font(FontFamily family, float emSize, int style) {#Font-com.aspose.drawing.FontFamily-float-int-}
```
public Font(FontFamily family, float emSize, int style)
```


Initialise une nouvelle instance de la classe [Font](../../com.aspose.drawing/font) en utilisant une taille et un style spécifiés..

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| family | [FontFamily](../../com.aspose.drawing/fontfamily) | Le `FontFamily`([.getFontFamily](../../null/\#getFontFamily)) de la nouvelle [Font](../../com.aspose.drawing/font). |
| emSize | float | La taille em, en points, de la nouvelle police. |
| style | int | Le [FontStyle](../../com.aspose.drawing/fontstyle) de la nouvelle police. |

### Font(FontFamily family, float emSize, int style, int unit) {#Font-com.aspose.drawing.FontFamily-float-int-int-}
```
public Font(FontFamily family, float emSize, int style, int unit)
```


Initialise une nouvelle instance de la classe [Font](../../com.aspose.drawing/font) en utilisant une taille, un style et une unité spécifiés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| family | [FontFamily](../../com.aspose.drawing/fontfamily) | Le `FontFamily`([.getFontFamily](../../null/\#getFontFamily)) de la nouvelle [Font](../../com.aspose.drawing/font). |
| emSize | float | La taille em de la nouvelle police dans les unités spécifiées par le paramètre `unit`. |
| style | int | Le [FontStyle](../../com.aspose.drawing/fontstyle) de la nouvelle police. |
| unit | int | L'[GraphicsUnit](../../com.aspose.drawing/graphicsunit) de la nouvelle police. |

### Font(FontFamily family, float emSize, int style, int unit, byte gdiCharSet) {#Font-com.aspose.drawing.FontFamily-float-int-int-byte-}
```
public Font(FontFamily family, float emSize, int style, int unit, byte gdiCharSet)
```


Initialise une nouvelle instance de la classe [Font](../../com.aspose.drawing/font) en utilisant une taille, un style, une unité et un jeu de caractères spécifiés..

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| family | [FontFamily](../../com.aspose.drawing/fontfamily) | Le `FontFamily`([.getFontFamily](../../null/\#getFontFamily)) de la nouvelle [Font](../../com.aspose.drawing/font). |
| emSize | float | La taille em de la nouvelle police dans les unités spécifiées par le paramètre `unit`. |
| style | int | Le [FontStyle](../../com.aspose.drawing/fontstyle) de la nouvelle police. |
| unit | int | L'[GraphicsUnit](../../com.aspose.drawing/graphicsunit) de la nouvelle police. |
| gdiCharSet | byte | Jeu de caractères GDI à utiliser pour la nouvelle police. |

### Font(FontFamily family, float emSize, int style, int unit, byte gdiCharSet, boolean gdiVerticalFont) {#Font-com.aspose.drawing.FontFamily-float-int-int-byte-boolean-}
```
public Font(FontFamily family, float emSize, int style, int unit, byte gdiCharSet, boolean gdiVerticalFont)
```


Initialise une nouvelle instance de la classe [Font](../../com.aspose.drawing/font) en utilisant une taille, un style, une unité et un jeu de caractères spécifiés..

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| family | [FontFamily](../../com.aspose.drawing/fontfamily) | Le `FontFamily`([.getFontFamily](../../null/\#getFontFamily)) de la nouvelle [Font](../../com.aspose.drawing/font). |
| emSize | float | La taille em de la nouvelle police dans les unités spécifiées par le paramètre `unit`. |
| style | int | Le [FontStyle](../../com.aspose.drawing/fontstyle) de la nouvelle police. |
| unit | int | L'[GraphicsUnit](../../com.aspose.drawing/graphicsunit) de la nouvelle police. |
| gdiCharSet | byte | Jeu de caractères GDI à utiliser pour la nouvelle police. |
| gdiVerticalFont | boolean | Une valeur booléenne indiquant si la nouvelle police est dérivée d'une police verticale GDI. |

### Font(String familyName, float emSize) {#Font-java.lang.String-float-}
```
public Font(String familyName, float emSize)
```


Initialise une nouvelle instance de la classe [Font](../../com.aspose.drawing/font) en utilisant une taille spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| familyName | java.lang.String | Une représentation sous forme de chaîne du FontFamily pour la nouvelle [Font](../../com.aspose.drawing/font). |
| emSize | float | La taille em, en points, de la nouvelle police. |

### Font(String familyName, float emSize, int style) {#Font-java.lang.String-float-int-}
```
public Font(String familyName, float emSize, int style)
```


Initialise une nouvelle instance de la classe [Font](../../com.aspose.drawing/font) en utilisant une taille et un style spécifiés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| familyName | java.lang.String | Une représentation sous forme de chaîne du FontFamily pour la nouvelle [Font](../../com.aspose.drawing/font). |
| emSize | float | La taille em, en points, de la nouvelle police. |
| style | int | Le [FontStyle](../../com.aspose.drawing/fontstyle) de la nouvelle police. |

### Font(String familyName, float emSize, int style, int unit) {#Font-java.lang.String-float-int-int-}
```
public Font(String familyName, float emSize, int style, int unit)
```


Initialise une nouvelle instance de la classe [Font](../../com.aspose.drawing/font) en utilisant une taille, un style et une unité spécifiés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| familyName | java.lang.String | Une représentation sous forme de chaîne du `FontFamily`([.getFontFamily](../../null/\#getFontFamily)) pour la nouvelle [Font](../../com.aspose.drawing/font). |
| emSize | float | La taille em de la nouvelle police dans les unités spécifiées par le paramètre `unit`. |
| style | int | Le [FontStyle](../../com.aspose.drawing/fontstyle) de la nouvelle police. |
| unit | int | L'[GraphicsUnit](../../com.aspose.drawing/graphicsunit) de la nouvelle police. |

### Font(String familyName, float emSize, int style, int unit, byte gdiCharSet) {#Font-java.lang.String-float-int-int-byte-}
```
public Font(String familyName, float emSize, int style, int unit, byte gdiCharSet)
```


Initialise une nouvelle instance de la classe [Font](../../com.aspose.drawing/font) en utilisant une taille, un style, une unité et un jeu de caractères spécifiés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| familyName | java.lang.String | Une représentation sous forme de chaîne du FontFamily pour la nouvelle [Font](../../com.aspose.drawing/font). |
| emSize | float | La taille em de la nouvelle police dans les unités spécifiées par le paramètre `unit`. |
| style | int | Le [FontStyle](../../com.aspose.drawing/fontstyle) de la nouvelle police. |
| unit | int | L'[GraphicsUnit](../../com.aspose.drawing/graphicsunit) de la nouvelle police. |
| gdiCharSet | byte | Un octet qui spécifie un jeu de caractères GDI à utiliser pour cette police. |

### Font(String familyName, float emSize, int style, int unit, byte gdiCharSet, boolean gdiVerticalFont) {#Font-java.lang.String-float-int-int-byte-boolean-}
```
public Font(String familyName, float emSize, int style, int unit, byte gdiCharSet, boolean gdiVerticalFont)
```


Initialise une nouvelle instance de la classe [Font](../../com.aspose.drawing/font) en utilisant la taille, le style, l'unité et le jeu de caractères spécifiés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| familyName | java.lang.String | Une représentation sous forme de chaîne du FontFamily pour la nouvelle [Font](../../com.aspose.drawing/font). |
| emSize | float | La taille em de la nouvelle police dans les unités spécifiées par le paramètre `unit`. |
| style | int | Le [FontStyle](../../com.aspose.drawing/fontstyle) de la nouvelle police. |
| unit | int | L'[GraphicsUnit](../../com.aspose.drawing/graphicsunit) de la nouvelle police. |
| gdiCharSet | byte | Un octet qui spécifie un jeu de caractères GDI à utiliser pour cette police. |
| gdiVerticalFont | boolean | Une valeur booléenne indiquant si la nouvelle [Font](../../com.aspose.drawing/font) est dérivée d'une police verticale GDI. |

### getFontFamily() {#getFontFamily--}
```
public FontFamily getFontFamily()
```


Obtient le `FontFamily`([.getFontFamily](../../null/\#getFontFamily)) associé à ce [Font](../../com.aspose.drawing/font).

**Returns:**
[FontFamily](../../com.aspose.drawing/fontfamily) - The `FontFamily`([.getFontFamily](../../null/\#getFontFamily)) associated with this [Font](../../com.aspose.drawing/font).
### getBold() {#getBold--}
```
public boolean getBold()
```


Obtient une valeur indiquant si ce [Font](../../com.aspose.drawing/font) est en gras.

**Returns:**
boolean - a value indicating whether this [Font](../../com.aspose.drawing/font) is bold.
### getGdiCharSet() {#getGdiCharSet--}
```
public byte getGdiCharSet()
```


Obtient une valeur byte qui spécifie le jeu de caractères GDI utilisé par ce [Font](../../com.aspose.drawing/font).

**Returns:**
byte - A byte value that specifies the GDI character set that this [Font](../../com.aspose.drawing/font) uses.
### getGdiVerticalFont() {#getGdiVerticalFont--}
```
public boolean getGdiVerticalFont()
```


Obtient une valeur indiquant si ce [Font](../../com.aspose.drawing/font) est dérivé d'une police verticale GDI..

Value: `true` if this [Font](../../com.aspose.drawing/font) is derived from a GDI vertical font; otherwise, `false`.

**Returns:**
boolean - a value indicating whether this [Font](../../com.aspose.drawing/font) is derived from a GDI vertical font.
### getItalic() {#getItalic--}
```
public boolean getItalic()
```


Obtient une valeur indiquant si ce [Font](../../com.aspose.drawing/font) est en italique.

**Returns:**
boolean - a value indicating whether this [Font](../../com.aspose.drawing/font) is italic.
### getName() {#getName--}
```
public String getName()
```


Obtient le nom de la police de ce [Font](../../com.aspose.drawing/font).

**Returns:**
java.lang.String - the face name of this [Font](../../com.aspose.drawing/font).
### getStrikeout() {#getStrikeout--}
```
public boolean getStrikeout()
```


Obtient une valeur indiquant si ce [Font](../../com.aspose.drawing/font) spécifie une ligne horizontale traversant la police.

**Returns:**
boolean - a value indicating whether this [Font](../../com.aspose.drawing/font) specifies a horizontal line through the font.
### getUnderline() {#getUnderline--}
```
public boolean getUnderline()
```


Obtient une valeur indiquant si ce [Font](../../com.aspose.drawing/font) est souligné.

**Returns:**
boolean - a value indicating whether this [Font](../../com.aspose.drawing/font) is underlined.
### getStyle() {#getStyle--}
```
public int getStyle()
```


Obtient les informations de style pour ce [Font](../../com.aspose.drawing/font).

**Returns:**
int - style information for this [Font](../../com.aspose.drawing/font).
### getSize() {#getSize--}
```
public float getSize()
```


Obtient la taille en em de ce [Font](../../com.aspose.drawing/font) mesurée dans les unités spécifiées par la propriété `Font.Unit`.

**Returns:**
float - the em-size of this [Font](../../com.aspose.drawing/font) measured in the units specified by the \{@code Font.
### getSizeInPoints() {#getSizeInPoints--}
```
public float getSizeInPoints()
```


Obtient la taille en em, en points, de ce [Font](../../com.aspose.drawing/font).

**Returns:**
float - The em-size, in points, of this [Font](../../com.aspose.drawing/font).
### getUnit() {#getUnit--}
```
public int getUnit()
```


Obtient l'unité de mesure de ce [Font](../../com.aspose.drawing/font).

**Returns:**
int - the unit of measure for this [Font](../../com.aspose.drawing/font).
### getHeight_Rename_Namesake() {#getHeight-Rename-Namesake--}
```
public int getHeight_Rename_Namesake()
```


Obtient l'interligne de cette police.

Value: The line spacing, in pixels, of this font.

**Returns:**
int - the line spacing of this font.
### isSystemFont() {#isSystemFont--}
```
public boolean isSystemFont()
```


Obtient une valeur indiquant si la police est un membre de [SystemFonts](../../com.aspose.drawing/systemfonts).

Value: `true` if the font is a member of [SystemFonts](../../com.aspose.drawing/systemfonts); otherwise, `false`.

**Returns:**
boolean - a value indicating whether the font is a member of [SystemFonts](../../com.aspose.drawing/systemfonts).
### getSystemFontName() {#getSystemFontName--}
```
public String getSystemFontName()
```


Obtient le nom de la police système si la propriété IsSystemFont renvoie vrai.

Value: The name of the system font, if IsSystemFont returns true; otherwise, an empty string ("").

**Returns:**
java.lang.String - the name of the system font if the IsSystemFont property returns true.
### getOriginalFontName() {#getOriginalFontName--}
```
public String getOriginalFontName()
```


Obtient le nom de la police tel qu'il a été spécifié à l'origine.

Value: The string representing the name of the font originally specified.

**Returns:**
java.lang.String - the name of the font originally specified.
### deepClone() {#deepClone--}
```
public Font deepClone()
```


Crée une copie exacte de ce [Font](../../com.aspose.drawing/font).

**Returns:**
[Font](../../com.aspose.drawing/font) - The [Font](../../com.aspose.drawing/font) this method creates, cast as an Object.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Indique si l'objet spécifié est une [Font](../../com.aspose.drawing/font) et possède les mêmes valeurs de propriétés `FontFamily`([.getFontFamily](../../null/\#getFontFamily)), `M:GdiVerticalFont`, `M:GdiCharSet`, `M:Style`, `M:Size` et `M:Unit` que cette [Font](../../com.aspose.drawing/font).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | L'objet à tester. |

**Returns:**
boolean - `true` if the obj parameter is a [Font](../../com.aspose.drawing/font) and has the same `FontFamily`([.getFontFamily](../../null/\#getFontFamily)), `M:GdiVerticalFont`, `M:GdiCharSet`, `M:Style`, `M:Size`, and `M:Unit` property values as this [Font](../../com.aspose.drawing/font); otherwise, `false`.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Obtient le code de hachage pour cette [Font](../../com.aspose.drawing/font).

**Returns:**
int - The hash code for this [Font](../../com.aspose.drawing/font).
### getHeight() {#getHeight--}
```
public int getHeight()
```


Renvoie l'interligne, en pixels, de cette police.

**Returns:**
int - The line spacing, in pixels, of this font.
### getHeight(Graphics graphics) {#getHeight-com.aspose.drawing.Graphics-}
```
public float getHeight(Graphics graphics)
```


Renvoie l'interligne, dans l'unité actuelle d'un [Graphics](../../com.aspose.drawing/graphics) spécifié, de cette police.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| graphics | [Graphics](../../com.aspose.drawing/graphics) | A [Graphics](../../com.aspose.drawing/graphics) that holds the vertical resolution, in dots per inch, of the display device as well as settings for page unit and page scale. |

**Returns:**
float - The line spacing, in pixels, of this font.
### getHeight(float dpi) {#getHeight-float-}
```
public int getHeight(float dpi)
```


Renvoie la hauteur, en pixels, de cette [Font](../../com.aspose.drawing/font) lorsqu'elle est dessinée sur un dispositif avec la résolution verticale spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| dpi | float | La résolution verticale, en points par pouce, utilisée pour calculer la hauteur de la police. |

**Returns:**
int - La hauteur, en pixels, de ce [Font](../../com.aspose.drawing/font).
### dispose() {#dispose--}
```
public void dispose()
```


Libère toutes les ressources utilisées par cette [Font](../../com.aspose.drawing/font).

### toString() {#toString--}
```
public String toString()
```


Renvoie une représentation sous forme de chaîne lisible par l'homme de cette [Font](../../com.aspose.drawing/font).

**Returns:**
java.lang.String - Une chaîne qui représente ce [Font](../../com.aspose.drawing/font).
### getCharacterSet() {#getCharacterSet--}
```
public int getCharacterSet()
```


Obtient une valeur d'octet qui spécifie le jeu de caractères utilisé par ce `Font`.

**Returns:**
int - Un jeu de caractères que ce `Font` utilise.
