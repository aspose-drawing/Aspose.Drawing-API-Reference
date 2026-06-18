---
title: StringFormat
second_title: Referencia de la API de Aspose.Drawing para Java
description: Encapsula información de diseño de texto como la orientación de alineación y la visualización de tabulaciones, manipulaciones como la inserción de elipsis y la sustitución de dígitos nacionales y características OpenType.
type: docs
weight: 47
url: /es/java/com.aspose.drawing/stringformat/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public final class StringFormat implements System.IDisposable
```

Encapsula información de diseño de texto (como alineación, orientación y tabulaciones) manipulaciones de visualización (como inserción de elipsis y sustitución de dígitos nacionales) y características OpenType. Esta clase no puede heredarse.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [StringFormat()](#StringFormat--) | Inicializa una nueva instancia de la clase [StringFormat](../../com.aspose.drawing/stringformat). |
| [StringFormat(StringFormat format)](#StringFormat-com.aspose.drawing.StringFormat-) | Inicializa una nueva instancia de la clase [StringFormat](../../com.aspose.drawing/stringformat) a partir del objeto [StringFormat](../../com.aspose.drawing/stringformat) existente especificado. |
| [StringFormat(int options, int language)](#StringFormat-int-int-) | Inicializa una nueva instancia de la clase [StringFormat](../../com.aspose.drawing/stringformat) con la enumeración [StringFormatFlags](../../com.aspose.drawing/stringformatflags) y el idioma especificados. |
| [StringFormat(int options)](#StringFormat-int-) | Inicializa una nueva instancia de la clase [StringFormat](../../com.aspose.drawing/stringformat) con la enumeración [StringFormatFlags](../../com.aspose.drawing/stringformatflags) especificada. |
## Métodos

| Método | Descripción |
| --- | --- |
| [setDigitSubstitutionLanguage(int value)](#setDigitSubstitutionLanguage-int-) |  |
| [setDigitSubstitutionMethod(int value)](#setDigitSubstitutionMethod-int-) |  |
| [getFirstTabOffset()](#getFirstTabOffset--) |  |
| [getGenericDefault()](#getGenericDefault--) | Obtiene un objeto [StringFormat](../../com.aspose.drawing/stringformat) genérico predeterminado. |
| [getGenericTypographic()](#getGenericTypographic--) | Obtiene un objeto [StringFormat](../../com.aspose.drawing/stringformat) tipográfico genérico. |
| [getFormatFlags()](#getFormatFlags--) | Obtiene o establece una enumeración [StringFormatFlags](../../com.aspose.drawing/stringformatflags) que contiene información de formato. |
| [setFormatFlags(int value)](#setFormatFlags-int-) | Obtiene o establece una enumeración [StringFormatFlags](../../com.aspose.drawing/stringformatflags) que contiene información de formato. |
| [getAlignment()](#getAlignment--) | Obtiene o establece la información de alineación de texto en el plano vertical. |
| [setAlignment(int value)](#setAlignment-int-) | Obtiene o establece la información de alineación de texto en el plano vertical. |
| [getLineAlignment()](#getLineAlignment--) | Obtiene o establece la alineación de línea en el plano horizontal. |
| [setLineAlignment(int value)](#setLineAlignment-int-) | Obtiene o establece la alineación de línea en el plano horizontal. |
| [getHotkeyPrefix()](#getHotkeyPrefix--) | Obtiene o establece el objeto `HotkeyPrefix`([.getHotkeyPrefix](../../null/\#getHotkeyPrefix)/[.setHotkeyPrefix(int)](../../null/\#setHotkeyPrefix-int-)) para este objeto [StringFormat](../../com.aspose.drawing/stringformat). |
| [setHotkeyPrefix(int value)](#setHotkeyPrefix-int-) | Obtiene o establece el objeto `HotkeyPrefix`([.getHotkeyPrefix](../../null/\#getHotkeyPrefix)/[.setHotkeyPrefix(int)](../../null/\#setHotkeyPrefix-int-)) para este objeto [StringFormat](../../com.aspose.drawing/stringformat). |
| [getTrimming()](#getTrimming--) | Obtiene o establece la enumeración [StringTrimming](../../com.aspose.drawing/stringtrimming) para este objeto [StringFormat](../../com.aspose.drawing/stringformat). |
| [setTrimming(int value)](#setTrimming-int-) | Obtiene o establece la enumeración [StringTrimming](../../com.aspose.drawing/stringtrimming) para este objeto [StringFormat](../../com.aspose.drawing/stringformat). |
| [getDigitSubstitutionLanguage()](#getDigitSubstitutionLanguage--) | Obtiene el idioma que se utiliza cuando los dígitos locales se sustituyen por dígitos occidentales. |
| [getDigitSubstitutionMethod()](#getDigitSubstitutionMethod--) | Obtiene el método que se utilizará para la sustitución de dígitos. |
| [dispose()](#dispose--) | Libera todos los recursos utilizados por este objeto [StringFormat](../../com.aspose.drawing/stringformat). |
| [deepClone()](#deepClone--) | Crea una copia exacta de este objeto [StringFormat](../../com.aspose.drawing/stringformat). |
| [getTabStops(float[] firstTabOffset)](#getTabStops-float---) | Obtiene las tabulaciones para este objeto [StringFormat](../../com.aspose.drawing/stringformat). |
| [getTabStops()](#getTabStops--) | Obtiene una matriz de distancias entre tabulaciones en las unidades especificadas por la propiedad `Aspose.Imaging.getGraphics().PageUnit`. |
| [setTabStops(float firstTabOffset, float[] tabStops)](#setTabStops-float-float---) | Establece las tabulaciones para este objeto [StringFormat](../../com.aspose.drawing/stringformat). |
| [setDigitSubstitution(int language, int substitute)](#setDigitSubstitution-int-int-) | Especifica el idioma y el método que se utilizarán cuando los dígitos locales se sustituyan por dígitos occidentales. |
| [setMeasurableCharacterRanges(CharacterRange[] ranges)](#setMeasurableCharacterRanges-com.aspose.drawing.CharacterRange---) | Especifica una matriz de estructuras [CharacterRange](../../com.aspose.drawing/characterrange) que representan los rangos de caracteres medidos mediante una llamada al método `MeasureCharacterRanges`. |
### StringFormat() {#StringFormat--}
```
public StringFormat()
```


Inicializa una nueva instancia de la clase [StringFormat](../../com.aspose.drawing/stringformat).

### StringFormat(StringFormat format) {#StringFormat-com.aspose.drawing.StringFormat-}
```
public StringFormat(StringFormat format)
```


Inicializa una nueva instancia de la clase [StringFormat](../../com.aspose.drawing/stringformat) a partir del objeto [StringFormat](../../com.aspose.drawing/stringformat) existente especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| format | [StringFormat](../../com.aspose.drawing/stringformat) | El objeto [StringFormat](../../com.aspose.drawing/stringformat) del cual inicializar el nuevo objeto [StringFormat](../../com.aspose.drawing/stringformat). |

### StringFormat(int options, int language) {#StringFormat-int-int-}
```
public StringFormat(int options, int language)
```


Inicializa una nueva instancia de la clase [StringFormat](../../com.aspose.drawing/stringformat) con la enumeración [StringFormatFlags](../../com.aspose.drawing/stringformatflags) y el idioma especificados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| options | int | La enumeración [StringFormatFlags](../../com.aspose.drawing/stringformatflags) para el nuevo objeto [StringFormat](../../com.aspose.drawing/stringformat). |
| idioma | int | Un valor que indica el idioma del texto. |

### StringFormat(int options) {#StringFormat-int-}
```
public StringFormat(int options)
```


Inicializa una nueva instancia de la clase [StringFormat](../../com.aspose.drawing/stringformat) con la enumeración [StringFormatFlags](../../com.aspose.drawing/stringformatflags) especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| options | int | La enumeración [StringFormatFlags](../../com.aspose.drawing/stringformatflags) para el nuevo objeto [StringFormat](../../com.aspose.drawing/stringformat). |

### setDigitSubstitutionLanguage(int value) {#setDigitSubstitutionLanguage-int-}
```
public void setDigitSubstitutionLanguage(int value)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### setDigitSubstitutionMethod(int value) {#setDigitSubstitutionMethod-int-}
```
public void setDigitSubstitutionMethod(int value)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getFirstTabOffset() {#getFirstTabOffset--}
```
public float getFirstTabOffset()
```




**Returns:**
float
### getGenericDefault() {#getGenericDefault--}
```
public static StringFormat getGenericDefault()
```


Obtiene un objeto [StringFormat](../../com.aspose.drawing/stringformat) genérico predeterminado.

**Returns:**
[StringFormat](../../com.aspose.drawing/stringformat)
### getGenericTypographic() {#getGenericTypographic--}
```
public static StringFormat getGenericTypographic()
```


Obtiene un objeto [StringFormat](../../com.aspose.drawing/stringformat) tipográfico genérico.

**Returns:**
[StringFormat](../../com.aspose.drawing/stringformat) - A generic typographic [StringFormat](../../com.aspose.drawing/stringformat) object.
### getFormatFlags() {#getFormatFlags--}
```
public int getFormatFlags()
```


Obtiene o establece una enumeración [StringFormatFlags](../../com.aspose.drawing/stringformatflags) que contiene información de formato.

**Returns:**
int
### setFormatFlags(int value) {#setFormatFlags-int-}
```
public void setFormatFlags(int value)
```


Obtiene o establece una enumeración [StringFormatFlags](../../com.aspose.drawing/stringformatflags) que contiene información de formato.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getAlignment() {#getAlignment--}
```
public int getAlignment()
```


Obtiene o establece la información de alineación de texto en el plano vertical.

**Returns:**
int
### setAlignment(int value) {#setAlignment-int-}
```
public void setAlignment(int value)
```


Obtiene o establece la información de alineación de texto en el plano vertical.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getLineAlignment() {#getLineAlignment--}
```
public int getLineAlignment()
```


Obtiene o establece la alineación de línea en el plano horizontal.

**Returns:**
int
### setLineAlignment(int value) {#setLineAlignment-int-}
```
public void setLineAlignment(int value)
```


Obtiene o establece la alineación de línea en el plano horizontal.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getHotkeyPrefix() {#getHotkeyPrefix--}
```
public int getHotkeyPrefix()
```


Obtiene o establece el objeto `HotkeyPrefix`([.getHotkeyPrefix](../../null/\#getHotkeyPrefix)/[.setHotkeyPrefix(int)](../../null/\#setHotkeyPrefix-int-)) para este objeto [StringFormat](../../com.aspose.drawing/stringformat).

**Returns:**
int
### setHotkeyPrefix(int value) {#setHotkeyPrefix-int-}
```
public void setHotkeyPrefix(int value)
```


Obtiene o establece el objeto `HotkeyPrefix`([.getHotkeyPrefix](../../null/\#getHotkeyPrefix)/[.setHotkeyPrefix(int)](../../null/\#setHotkeyPrefix-int-)) para este objeto [StringFormat](../../com.aspose.drawing/stringformat).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getTrimming() {#getTrimming--}
```
public int getTrimming()
```


Obtiene o establece la enumeración [StringTrimming](../../com.aspose.drawing/stringtrimming) para este objeto [StringFormat](../../com.aspose.drawing/stringformat).

**Returns:**
int
### setTrimming(int value) {#setTrimming-int-}
```
public void setTrimming(int value)
```


Obtiene o establece la enumeración [StringTrimming](../../com.aspose.drawing/stringtrimming) para este objeto [StringFormat](../../com.aspose.drawing/stringformat).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getDigitSubstitutionLanguage() {#getDigitSubstitutionLanguage--}
```
public int getDigitSubstitutionLanguage()
```


Obtiene el idioma que se utiliza cuando los dígitos locales se sustituyen por dígitos occidentales.

**Returns:**
int - Un identificador de idioma de Soporte de Idioma Nacional (NLS) que identifica el idioma que se usará cuando los dígitos locales se sustituyan por dígitos occidentales. Puede pasar la propiedad `System.Globalization.CultureInfo.LCID` de un objeto java.util.Locale como el identificador de idioma NLS. Por ejemplo, suponga que crea un objeto java.util.Locale pasando la cadena "ar-EG" al constructor de java.util.Locale. Si pasa la propiedad `System.Globalization.CultureInfo.LCID` de ese objeto java.util.Locale junto con `StringDigitSubstitute.Traditional` al método [.setDigitSubstitution(int,int)](../../null/\#setDigitSubstitution-int-int-), entonces los dígitos árabe-indios se sustituirán por dígitos occidentales en tiempo de visualización.
### getDigitSubstitutionMethod() {#getDigitSubstitutionMethod--}
```
public int getDigitSubstitutionMethod()
```


Obtiene el método que se utilizará para la sustitución de dígitos.

**Returns:**
int - Un valor de enumeración [StringDigitSubstitute](../../com.aspose.drawing/stringdigitsubstitute) que especifica cómo sustituir caracteres en una cadena que no pueden mostrarse porque no son compatibles con la fuente actual.
### dispose() {#dispose--}
```
public void dispose()
```


Libera todos los recursos utilizados por este objeto [StringFormat](../../com.aspose.drawing/stringformat).

### deepClone() {#deepClone--}
```
public StringFormat deepClone()
```


Crea una copia exacta de este objeto [StringFormat](../../com.aspose.drawing/stringformat).

**Returns:**
[StringFormat](../../com.aspose.drawing/stringformat) - The [StringFormat](../../com.aspose.drawing/stringformat) object this method creates.
### getTabStops(float[] firstTabOffset) {#getTabStops-float---}
```
public float[] getTabStops(float[] firstTabOffset)
```


Obtiene las tabulaciones para este objeto [StringFormat](../../com.aspose.drawing/stringformat).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| firstTabOffset | float[] | El número de espacios entre el inicio de una línea de texto y la primera tabulación. |

**Returns:**
float[] - Una matriz de distancias (en número de espacios) entre tabulaciones.
### getTabStops() {#getTabStops--}
```
public float[] getTabStops()
```


Obtiene una matriz de distancias entre tabulaciones en las unidades especificadas por la propiedad `Aspose.Imaging.getGraphics().PageUnit`.

**Returns:**
float[] - Las tabulaciones.

La propiedad se introduce para el método eliminado GetTabStops.
### setTabStops(float firstTabOffset, float[] tabStops) {#setTabStops-float-float---}
```
public void setTabStops(float firstTabOffset, float[] tabStops)
```


Establece las tabulaciones para este objeto [StringFormat](../../com.aspose.drawing/stringformat).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| firstTabOffset | float | El número de espacios entre el inicio de una línea de texto y la primera tabulación. |
| tabStops | float[] | Una matriz de distancias entre tabulaciones en las unidades especificadas por la propiedad Graphics.PageUnit. |

### setDigitSubstitution(int language, int substitute) {#setDigitSubstitution-int-int-}
```
public void setDigitSubstitution(int language, int substitute)
```


Especifica el idioma y el método que se utilizarán cuando los dígitos locales se sustituyan por dígitos occidentales.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| idioma | int | Un identificador de idioma de Soporte de Idioma Nacional (NLS) que identifica el idioma que se usará cuando los dígitos locales se sustituyan por dígitos occidentales. Puede pasar la propiedad `System.Globalization.CultureInfo.LCID` de un objeto java.util.Locale como el identificador de idioma NLS. Por ejemplo, suponga que crea un objeto java.util.Locale pasando la cadena "ar-EG" al constructor de java.util.Locale. Si pasa la propiedad `System.Globalization.CultureInfo.LCID` de ese objeto java.util.Locale junto con `StringDigitSubstitute.Traditional` al método `M:StringFormat.SetDigitSubstitution(System.Int32,StringDigitSubstitute)`, entonces los dígitos árabe-indios se sustituirán por dígitos occidentales en tiempo de visualización. |
| substitute | int | Un elemento de la enumeración [StringDigitSubstitute](../../com.aspose.drawing/stringdigitsubstitute) que especifica cómo se muestran los dígitos. |

### setMeasurableCharacterRanges(CharacterRange[] ranges) {#setMeasurableCharacterRanges-com.aspose.drawing.CharacterRange---}
```
public void setMeasurableCharacterRanges(CharacterRange[] ranges)
```


Especifica una matriz de estructuras [CharacterRange](../../com.aspose.drawing/characterrange) que representan los rangos de caracteres medidos mediante una llamada al método `MeasureCharacterRanges`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ranges | [CharacterRange\[\]](../../com.aspose.drawing/characterrange) | Una matriz de estructuras [CharacterRange](../../com.aspose.drawing/characterrange) que especifica los rangos de caracteres medidos mediante una llamada al método `MeasureCharacterRanges`. |

