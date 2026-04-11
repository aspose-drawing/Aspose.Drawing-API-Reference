---
title: Font
second_title: Referencia de la API de Aspose.Drawing para Java
description: Define un formato particular para texto que incluye la fuente, el tamaño y los atributos de estilo.
type: docs
weight: 21
url: /es/java/com.aspose.drawing/font/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public final class Font implements System.IDisposable
```

Define un formato particular para texto, incluyendo la familia de fuente, el tamaño y los atributos de estilo. Esta clase no puede heredarse.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [Font(Font prototype, int newStyle)](#Font-com.aspose.drawing.Font-int-) | Inicializa una nueva instancia de la clase [Font](../../com.aspose.drawing/font) que usa la [Font](../../com.aspose.drawing/font) existente especificada y la enumeración [FontStyle](../../com.aspose.drawing/fontstyle).. |
| [Font(FontFamily family, float emSize)](#Font-com.aspose.drawing.FontFamily-float-) | Inicializa una nueva instancia de la clase [Font](../../com.aspose.drawing/font). |
| [Font(FontFamily family, float emSize, int style)](#Font-com.aspose.drawing.FontFamily-float-int-) | Inicializa una nueva instancia de la clase [Font](../../com.aspose.drawing/font) usando un tamaño y estilo especificados.. |
| [Font(FontFamily family, float emSize, int style, int unit)](#Font-com.aspose.drawing.FontFamily-float-int-int-) | Inicializa una nueva instancia de la clase [Font](../../com.aspose.drawing/font) usando un tamaño, estilo y unidad especificados. |
| [Font(FontFamily family, float emSize, int style, int unit, byte gdiCharSet)](#Font-com.aspose.drawing.FontFamily-float-int-int-byte-) | Inicializa una nueva instancia de la clase [Font](../../com.aspose.drawing/font) usando un tamaño, estilo, unidad y conjunto de caracteres especificados.. |
| [Font(FontFamily family, float emSize, int style, int unit, byte gdiCharSet, boolean gdiVerticalFont)](#Font-com.aspose.drawing.FontFamily-float-int-int-byte-boolean-) | Inicializa una nueva instancia de la clase [Font](../../com.aspose.drawing/font) usando un tamaño, estilo, unidad y conjunto de caracteres especificados.. |
| [Font(String familyName, float emSize)](#Font-java.lang.String-float-) | Inicializa una nueva instancia de la clase [Font](../../com.aspose.drawing/font) usando un tamaño especificado. |
| [Font(String familyName, float emSize, int style)](#Font-java.lang.String-float-int-) | Inicializa una nueva instancia de la clase [Font](../../com.aspose.drawing/font) usando un tamaño y estilo especificados. |
| [Font(String familyName, float emSize, int style, int unit)](#Font-java.lang.String-float-int-int-) | Inicializa una nueva instancia de la clase [Font](../../com.aspose.drawing/font) usando un tamaño, estilo y unidad especificados. |
| [Font(String familyName, float emSize, int style, int unit, byte gdiCharSet)](#Font-java.lang.String-float-int-int-byte-) | Inicializa una nueva instancia de la clase [Font](../../com.aspose.drawing/font) usando un tamaño, estilo, unidad y conjunto de caracteres especificados. |
| [Font(String familyName, float emSize, int style, int unit, byte gdiCharSet, boolean gdiVerticalFont)](#Font-java.lang.String-float-int-int-byte-boolean-) | Inicializa una nueva instancia de la clase [Font](../../com.aspose.drawing/font) usando el tamaño, estilo, unidad y conjunto de caracteres especificados. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getFontFamily()](#getFontFamily--) | Obtiene el `FontFamily`([.getFontFamily](../../null/\#getFontFamily)) asociado a este [Font](../../com.aspose.drawing/font). |
| [getBold()](#getBold--) | Obtiene un valor que indica si este [Font](../../com.aspose.drawing/font) está en negrita. |
| [getGdiCharSet()](#getGdiCharSet--) | Obtiene un valor de byte que especifica el conjunto de caracteres GDI que usa este [Font](../../com.aspose.drawing/font). |
| [getGdiVerticalFont()](#getGdiVerticalFont--) | Obtiene un valor que indica si este [Font](../../com.aspose.drawing/font) se deriva de una fuente vertical GDI.. |
| [getItalic()](#getItalic--) | Obtiene un valor que indica si este [Font](../../com.aspose.drawing/font) está en cursiva. |
| [getName()](#getName--) | Obtiene el nombre de la fuente de este [Font](../../com.aspose.drawing/font). |
| [getStrikeout()](#getStrikeout--) | Obtiene un valor que indica si este [Font](../../com.aspose.drawing/font) especifica una línea horizontal a través de la fuente. |
| [getUnderline()](#getUnderline--) | Obtiene un valor que indica si este [Font](../../com.aspose.drawing/font) está subrayado. |
| [getStyle()](#getStyle--) | Obtiene información de estilo para este [Font](../../com.aspose.drawing/font). |
| [getSize()](#getSize--) | Obtiene el tamaño em de este [Font](../../com.aspose.drawing/font) medido en las unidades especificadas por la propiedad `Font.Unit`. |
| [getSizeInPoints()](#getSizeInPoints--) | Obtiene el tamaño em, en puntos, de este [Font](../../com.aspose.drawing/font). |
| [getUnit()](#getUnit--) | Obtiene la unidad de medida de este [Font](../../com.aspose.drawing/font). |
| [getHeight_Rename_Namesake()](#getHeight-Rename-Namesake--) | Obtiene el interlineado de esta fuente. |
| [isSystemFont()](#isSystemFont--) | Obtiene un valor que indica si la fuente es miembro de [SystemFonts](../../com.aspose.drawing/systemfonts). |
| [getSystemFontName()](#getSystemFontName--) | Obtiene el nombre de la fuente del sistema si la propiedad IsSystemFont devuelve true. |
| [getOriginalFontName()](#getOriginalFontName--) | Obtiene el nombre de la fuente especificado originalmente. |
| [deepClone()](#deepClone--) | Crea una copia exacta de este [Font](../../com.aspose.drawing/font). |
| [equals(Object obj)](#equals-java.lang.Object-) | Indica si el objeto especificado es una [Font](../../com.aspose.drawing/font) y tiene los mismos valores de las propiedades `FontFamily`([.getFontFamily](../../null/\#getFontFamily)), `M:GdiVerticalFont`, `M:GdiCharSet`, `M:Style`, `M:Size` y `M:Unit` que este [Font](../../com.aspose.drawing/font). |
| [hashCode()](#hashCode--) | Obtiene el código hash de este [Font](../../com.aspose.drawing/font). |
| [getHeight()](#getHeight--) | Devuelve el interlineado, en píxeles, de esta fuente. |
| [getHeight(Graphics graphics)](#getHeight-com.aspose.drawing.Graphics-) | Devuelve el interlineado, en la unidad actual de un [Graphics](../../com.aspose.drawing/graphics) especificado, de esta fuente. |
| [getHeight(float dpi)](#getHeight-float-) | Devuelve la altura, en píxeles, de este [Font](../../com.aspose.drawing/font) cuando se dibuja en un dispositivo con la resolución vertical especificada. |
| [dispose()](#dispose--) | Libera todos los recursos utilizados por este [Font](../../com.aspose.drawing/font). |
| [toString()](#toString--) | Devuelve una representación de cadena legible por humanos de este [Font](../../com.aspose.drawing/font). |
| [getCharacterSet()](#getCharacterSet--) | Obtiene un valor byte que especifica el conjunto de caracteres que usa este `Font`. |
### Font(Font prototype, int newStyle) {#Font-com.aspose.drawing.Font-int-}
```
public Font(Font prototype, int newStyle)
```


Inicializa una nueva instancia de la clase [Font](../../com.aspose.drawing/font) que usa la [Font](../../com.aspose.drawing/font) existente especificada y la enumeración [FontStyle](../../com.aspose.drawing/fontstyle)..

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| prototype | [Font](../../com.aspose.drawing/font) | El [Font](../../com.aspose.drawing/font) existente del cual crear el nuevo [Font](../../com.aspose.drawing/font). |
| newStyle | int | El [FontStyle](../../com.aspose.drawing/fontstyle) que se aplicará al nuevo [Font](../../com.aspose.drawing/font). Se pueden combinar múltiples valores de la enumeración [FontStyle](../../com.aspose.drawing/fontstyle) con el operador OR. |

### Font(FontFamily family, float emSize) {#Font-com.aspose.drawing.FontFamily-float-}
```
public Font(FontFamily family, float emSize)
```


Inicializa una nueva instancia de la clase [Font](../../com.aspose.drawing/font).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| family | [FontFamily](../../com.aspose.drawing/fontfamily) | El `FontFamily`([.getFontFamily](../../null/\#getFontFamily)) del nuevo [Font](../../com.aspose.drawing/font). |
| emSize | float | El tamaño em, en puntos, de la nueva fuente. |

### Font(FontFamily family, float emSize, int style) {#Font-com.aspose.drawing.FontFamily-float-int-}
```
public Font(FontFamily family, float emSize, int style)
```


Inicializa una nueva instancia de la clase [Font](../../com.aspose.drawing/font) usando un tamaño y estilo especificados..

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| family | [FontFamily](../../com.aspose.drawing/fontfamily) | El `FontFamily`([.getFontFamily](../../null/\#getFontFamily)) del nuevo [Font](../../com.aspose.drawing/font). |
| emSize | float | El tamaño em, en puntos, de la nueva fuente. |
| style | int | El [FontStyle](../../com.aspose.drawing/fontstyle) de la nueva fuente. |

### Font(FontFamily family, float emSize, int style, int unit) {#Font-com.aspose.drawing.FontFamily-float-int-int-}
```
public Font(FontFamily family, float emSize, int style, int unit)
```


Inicializa una nueva instancia de la clase [Font](../../com.aspose.drawing/font) usando un tamaño, estilo y unidad especificados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| family | [FontFamily](../../com.aspose.drawing/fontfamily) | El `FontFamily`([.getFontFamily](../../null/\#getFontFamily)) del nuevo [Font](../../com.aspose.drawing/font). |
| emSize | float | El tamaño em de la nueva fuente en las unidades especificadas por el parámetro `unit`. |
| style | int | El [FontStyle](../../com.aspose.drawing/fontstyle) de la nueva fuente. |
| unit | int | La [GraphicsUnit](../../com.aspose.drawing/graphicsunit) de la nueva fuente. |

### Font(FontFamily family, float emSize, int style, int unit, byte gdiCharSet) {#Font-com.aspose.drawing.FontFamily-float-int-int-byte-}
```
public Font(FontFamily family, float emSize, int style, int unit, byte gdiCharSet)
```


Inicializa una nueva instancia de la clase [Font](../../com.aspose.drawing/font) usando un tamaño, estilo, unidad y conjunto de caracteres especificados..

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| family | [FontFamily](../../com.aspose.drawing/fontfamily) | El `FontFamily`([.getFontFamily](../../null/\#getFontFamily)) del nuevo [Font](../../com.aspose.drawing/font). |
| emSize | float | El tamaño em de la nueva fuente en las unidades especificadas por el parámetro `unit`. |
| style | int | El [FontStyle](../../com.aspose.drawing/fontstyle) de la nueva fuente. |
| unit | int | La [GraphicsUnit](../../com.aspose.drawing/graphicsunit) de la nueva fuente. |
| gdiCharSet | byte | Conjunto de caracteres GDI a usar para la nueva fuente. |

### Font(FontFamily family, float emSize, int style, int unit, byte gdiCharSet, boolean gdiVerticalFont) {#Font-com.aspose.drawing.FontFamily-float-int-int-byte-boolean-}
```
public Font(FontFamily family, float emSize, int style, int unit, byte gdiCharSet, boolean gdiVerticalFont)
```


Inicializa una nueva instancia de la clase [Font](../../com.aspose.drawing/font) usando un tamaño, estilo, unidad y conjunto de caracteres especificados..

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| family | [FontFamily](../../com.aspose.drawing/fontfamily) | El `FontFamily`([.getFontFamily](../../null/\#getFontFamily)) del nuevo [Font](../../com.aspose.drawing/font). |
| emSize | float | El tamaño em de la nueva fuente en las unidades especificadas por el parámetro `unit`. |
| style | int | El [FontStyle](../../com.aspose.drawing/fontstyle) de la nueva fuente. |
| unit | int | La [GraphicsUnit](../../com.aspose.drawing/graphicsunit) de la nueva fuente. |
| gdiCharSet | byte | Conjunto de caracteres GDI a usar para la nueva fuente. |
| gdiVerticalFont | boolean | Un valor Booleano que indica si la nueva fuente se deriva de una fuente vertical GDI. |

### Font(String familyName, float emSize) {#Font-java.lang.String-float-}
```
public Font(String familyName, float emSize)
```


Inicializa una nueva instancia de la clase [Font](../../com.aspose.drawing/font) usando un tamaño especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| familyName | java.lang.String | Una representación de cadena del FontFamily para el nuevo [Font](../../com.aspose.drawing/font). |
| emSize | float | El tamaño em, en puntos, de la nueva fuente. |

### Font(String familyName, float emSize, int style) {#Font-java.lang.String-float-int-}
```
public Font(String familyName, float emSize, int style)
```


Inicializa una nueva instancia de la clase [Font](../../com.aspose.drawing/font) usando un tamaño y estilo especificados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| familyName | java.lang.String | Una representación de cadena del FontFamily para el nuevo [Font](../../com.aspose.drawing/font). |
| emSize | float | El tamaño em, en puntos, de la nueva fuente. |
| style | int | El [FontStyle](../../com.aspose.drawing/fontstyle) de la nueva fuente. |

### Font(String familyName, float emSize, int style, int unit) {#Font-java.lang.String-float-int-int-}
```
public Font(String familyName, float emSize, int style, int unit)
```


Inicializa una nueva instancia de la clase [Font](../../com.aspose.drawing/font) usando un tamaño, estilo y unidad especificados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| familyName | java.lang.String | Una representación de cadena del `FontFamily`([.getFontFamily](../../null/\#getFontFamily)) para el nuevo [Font](../../com.aspose.drawing/font). |
| emSize | float | El tamaño em de la nueva fuente en las unidades especificadas por el parámetro `unit`. |
| style | int | El [FontStyle](../../com.aspose.drawing/fontstyle) de la nueva fuente. |
| unit | int | La [GraphicsUnit](../../com.aspose.drawing/graphicsunit) de la nueva fuente. |

### Font(String familyName, float emSize, int style, int unit, byte gdiCharSet) {#Font-java.lang.String-float-int-int-byte-}
```
public Font(String familyName, float emSize, int style, int unit, byte gdiCharSet)
```


Inicializa una nueva instancia de la clase [Font](../../com.aspose.drawing/font) usando un tamaño, estilo, unidad y conjunto de caracteres especificados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| familyName | java.lang.String | Una representación de cadena del FontFamily para el nuevo [Font](../../com.aspose.drawing/font). |
| emSize | float | El tamaño em de la nueva fuente en las unidades especificadas por el parámetro `unit`. |
| style | int | El [FontStyle](../../com.aspose.drawing/fontstyle) de la nueva fuente. |
| unit | int | La [GraphicsUnit](../../com.aspose.drawing/graphicsunit) de la nueva fuente. |
| gdiCharSet | byte | Un byte que especifica un conjunto de caracteres GDI a usar para esta fuente. |

### Font(String familyName, float emSize, int style, int unit, byte gdiCharSet, boolean gdiVerticalFont) {#Font-java.lang.String-float-int-int-byte-boolean-}
```
public Font(String familyName, float emSize, int style, int unit, byte gdiCharSet, boolean gdiVerticalFont)
```


Inicializa una nueva instancia de la clase [Font](../../com.aspose.drawing/font) usando el tamaño, estilo, unidad y conjunto de caracteres especificados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| familyName | java.lang.String | Una representación de cadena del FontFamily para el nuevo [Font](../../com.aspose.drawing/font). |
| emSize | float | El tamaño em de la nueva fuente en las unidades especificadas por el parámetro `unit`. |
| style | int | El [FontStyle](../../com.aspose.drawing/fontstyle) de la nueva fuente. |
| unit | int | La [GraphicsUnit](../../com.aspose.drawing/graphicsunit) de la nueva fuente. |
| gdiCharSet | byte | Un byte que especifica un conjunto de caracteres GDI a usar para esta fuente. |
| gdiVerticalFont | boolean | Un valor Booleano que indica si el nuevo [Font](../../com.aspose.drawing/font) se deriva de una fuente vertical GDI. |

### getFontFamily() {#getFontFamily--}
```
public FontFamily getFontFamily()
```


Obtiene el `FontFamily`([.getFontFamily](../../null/\#getFontFamily)) asociado a este [Font](../../com.aspose.drawing/font).

**Returns:**
[FontFamily](../../com.aspose.drawing/fontfamily) - The `FontFamily`([.getFontFamily](../../null/\#getFontFamily)) associated with this [Font](../../com.aspose.drawing/font).
### getBold() {#getBold--}
```
public boolean getBold()
```


Obtiene un valor que indica si este [Font](../../com.aspose.drawing/font) está en negrita.

**Returns:**
boolean - un valor que indica si este [Font](../../com.aspose.drawing/font) está en negrita.
### getGdiCharSet() {#getGdiCharSet--}
```
public byte getGdiCharSet()
```


Obtiene un valor de byte que especifica el conjunto de caracteres GDI que usa este [Font](../../com.aspose.drawing/font).

**Returns:**
byte - Un valor de byte que especifica el conjunto de caracteres GDI que utiliza este [Font](../../com.aspose.drawing/font).
### getGdiVerticalFont() {#getGdiVerticalFont--}
```
public boolean getGdiVerticalFont()
```


Obtiene un valor que indica si este [Font](../../com.aspose.drawing/font) se deriva de una fuente vertical GDI..

Valor: `true` si este [Font](../../com.aspose.drawing/font) se deriva de una fuente vertical GDI; de lo contrario, `false`.

**Returns:**
boolean - un valor que indica si este [Font](../../com.aspose.drawing/font) se deriva de una fuente vertical GDI.
### getItalic() {#getItalic--}
```
public boolean getItalic()
```


Obtiene un valor que indica si este [Font](../../com.aspose.drawing/font) está en cursiva.

**Returns:**
boolean - un valor que indica si este [Font](../../com.aspose.drawing/font) está en cursiva.
### getName() {#getName--}
```
public String getName()
```


Obtiene el nombre de la fuente de este [Font](../../com.aspose.drawing/font).

**Returns:**
java.lang.String - el nombre de la familia tipográfica de este [Font](../../com.aspose.drawing/font).
### getStrikeout() {#getStrikeout--}
```
public boolean getStrikeout()
```


Obtiene un valor que indica si este [Font](../../com.aspose.drawing/font) especifica una línea horizontal a través de la fuente.

**Returns:**
boolean - un valor que indica si este [Font](../../com.aspose.drawing/font) especifica una línea horizontal a través de la fuente.
### getUnderline() {#getUnderline--}
```
public boolean getUnderline()
```


Obtiene un valor que indica si este [Font](../../com.aspose.drawing/font) está subrayado.

**Returns:**
boolean - un valor que indica si este [Font](../../com.aspose.drawing/font) está subrayado.
### getStyle() {#getStyle--}
```
public int getStyle()
```


Obtiene información de estilo para este [Font](../../com.aspose.drawing/font).

**Returns:**
int - información de estilo para este [Font](../../com.aspose.drawing/font).
### getSize() {#getSize--}
```
public float getSize()
```


Obtiene el tamaño em de este [Font](../../com.aspose.drawing/font) medido en las unidades especificadas por la propiedad `Font.Unit`.

**Returns:**
float - el tamaño em de este [Font](../../com.aspose.drawing/font) medido en las unidades especificadas por el \{@code Font.
### getSizeInPoints() {#getSizeInPoints--}
```
public float getSizeInPoints()
```


Obtiene el tamaño em, en puntos, de este [Font](../../com.aspose.drawing/font).

**Returns:**
float - El tamaño em, en puntos, de este [Font](../../com.aspose.drawing/font).
### getUnit() {#getUnit--}
```
public int getUnit()
```


Obtiene la unidad de medida de este [Font](../../com.aspose.drawing/font).

**Returns:**
int - la unidad de medida para este [Font](../../com.aspose.drawing/font).
### getHeight_Rename_Namesake() {#getHeight-Rename-Namesake--}
```
public int getHeight_Rename_Namesake()
```


Obtiene el interlineado de esta fuente.

Valor: el interlineado, en píxeles, de esta fuente.

**Returns:**
int - el interlineado de esta fuente.
### isSystemFont() {#isSystemFont--}
```
public boolean isSystemFont()
```


Obtiene un valor que indica si la fuente es miembro de [SystemFonts](../../com.aspose.drawing/systemfonts).

Valor: `true` si la fuente es miembro de [SystemFonts](../../com.aspose.drawing/systemfonts); de lo contrario, `false`.

**Returns:**
boolean - un valor que indica si la fuente es miembro de [SystemFonts](../../com.aspose.drawing/systemfonts).
### getSystemFontName() {#getSystemFontName--}
```
public String getSystemFontName()
```


Obtiene el nombre de la fuente del sistema si la propiedad IsSystemFont devuelve true.

Valor: el nombre de la fuente del sistema, si IsSystemFont devuelve true; de lo contrario, una cadena vacía ("").

**Returns:**
java.lang.String - el nombre de la fuente del sistema si la propiedad IsSystemFont devuelve true.
### getOriginalFontName() {#getOriginalFontName--}
```
public String getOriginalFontName()
```


Obtiene el nombre de la fuente especificado originalmente.

Valor: la cadena que representa el nombre de la fuente especificada originalmente.

**Returns:**
java.lang.String - el nombre de la fuente especificada originalmente.
### deepClone() {#deepClone--}
```
public Font deepClone()
```


Crea una copia exacta de este [Font](../../com.aspose.drawing/font).

**Returns:**
[Font](../../com.aspose.drawing/font) - The [Font](../../com.aspose.drawing/font) this method creates, cast as an Object.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Indica si el objeto especificado es una [Font](../../com.aspose.drawing/font) y tiene los mismos valores de las propiedades `FontFamily`([.getFontFamily](../../null/\#getFontFamily)), `M:GdiVerticalFont`, `M:GdiCharSet`, `M:Style`, `M:Size` y `M:Unit` que este [Font](../../com.aspose.drawing/font).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | java.lang.Object | El objeto a probar. |

**Returns:**
boolean - `true` si el parámetro obj es un [Font](../../com.aspose.drawing/font) y tiene los mismos valores de propiedad `FontFamily`([.getFontFamily](../../null/\#getFontFamily)), `M:GdiVerticalFont`, `M:GdiCharSet`, `M:Style`, `M:Size` y `M:Unit` que este [Font](../../com.aspose.drawing/font); de lo contrario, `false`.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Obtiene el código hash de este [Font](../../com.aspose.drawing/font).

**Returns:**
int - El código hash para este [Font](../../com.aspose.drawing/font).
### getHeight() {#getHeight--}
```
public int getHeight()
```


Devuelve el interlineado, en píxeles, de esta fuente.

**Returns:**
int - El interlineado, en píxeles, de esta fuente.
### getHeight(Graphics graphics) {#getHeight-com.aspose.drawing.Graphics-}
```
public float getHeight(Graphics graphics)
```


Devuelve el interlineado, en la unidad actual de un [Graphics](../../com.aspose.drawing/graphics) especificado, de esta fuente.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| graphics | [Graphics](../../com.aspose.drawing/graphics) | Un [Graphics](../../com.aspose.drawing/graphics) que contiene la resolución vertical, en puntos por pulgada, del dispositivo de pantalla, así como la configuración de la unidad de página y la escala de página. |

**Returns:**
float - El interlineado, en píxeles, de esta fuente.
### getHeight(float dpi) {#getHeight-float-}
```
public int getHeight(float dpi)
```


Devuelve la altura, en píxeles, de este [Font](../../com.aspose.drawing/font) cuando se dibuja en un dispositivo con la resolución vertical especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| dpi | float | La resolución vertical, en puntos por pulgada, utilizada para calcular la altura de la fuente. |

**Returns:**
int - La altura, en píxeles, de este [Font](../../com.aspose.drawing/font).
### dispose() {#dispose--}
```
public void dispose()
```


Libera todos los recursos utilizados por este [Font](../../com.aspose.drawing/font).

### toString() {#toString--}
```
public String toString()
```


Devuelve una representación de cadena legible por humanos de este [Font](../../com.aspose.drawing/font).

**Returns:**
java.lang.String - Una cadena que representa este [Font](../../com.aspose.drawing/font).
### getCharacterSet() {#getCharacterSet--}
```
public int getCharacterSet()
```


Obtiene un valor byte que especifica el conjunto de caracteres que usa este `Font`.

**Returns:**
int - Un conjunto de caracteres que este `Font` usa.
