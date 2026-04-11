---
title: StringFormat
second_title: Aspose.Drawing voor Java API-referentie
description: Omvat tekstindelingsinformatie zoals uitlijningsoriëntatie en tabstops, weergavemanipulaties zoals het invoegen van ellipsis en nationale cijfervervanging, en OpenType-functies.
type: docs
weight: 47
url: /nl/java/com.aspose.drawing/stringformat/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public final class StringFormat implements System.IDisposable
```

Bevat tekstindelingsinformatie (zoals uitlijning, oriëntatie en tabstops) weergavemanipulaties (zoals invoegen van ellipsis en nationale cijfervervanging) en OpenType-functies. Deze klasse kan niet worden geërfd.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [StringFormat()](#StringFormat--) | Initialiseert een nieuw exemplaar van de [StringFormat](../../com.aspose.drawing/stringformat) klasse. |
| [StringFormat(StringFormat format)](#StringFormat-com.aspose.drawing.StringFormat-) | Initialiseert een nieuw exemplaar van de [StringFormat](../../com.aspose.drawing/stringformat) klasse vanuit het opgegeven bestaande [StringFormat](../../com.aspose.drawing/stringformat) object. |
| [StringFormat(int options, int language)](#StringFormat-int-int-) | Initialiseert een nieuw exemplaar van de [StringFormat](../../com.aspose.drawing/stringformat) klasse met de opgegeven [StringFormatFlags](../../com.aspose.drawing/stringformatflags) enumeratie en taal. |
| [StringFormat(int options)](#StringFormat-int-) | Initialiseert een nieuw exemplaar van de [StringFormat](../../com.aspose.drawing/stringformat) klasse met de opgegeven [StringFormatFlags](../../com.aspose.drawing/stringformatflags) enumeratie. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [setDigitSubstitutionLanguage(int value)](#setDigitSubstitutionLanguage-int-) |  |
| [setDigitSubstitutionMethod(int value)](#setDigitSubstitutionMethod-int-) |  |
| [getFirstTabOffset()](#getFirstTabOffset--) |  |
| [getGenericDefault()](#getGenericDefault--) | Haalt een generiek standaard [StringFormat](../../com.aspose.drawing/stringformat) object op. |
| [getGenericTypographic()](#getGenericTypographic--) | Haalt een generiek typografisch [StringFormat](../../com.aspose.drawing/stringformat) object op. |
| [getFormatFlags()](#getFormatFlags--) | Haalt op of stelt een [StringFormatFlags](../../com.aspose.drawing/stringformatflags) enumeratie in die opmaakinformatie bevat. |
| [setFormatFlags(int value)](#setFormatFlags-int-) | Haalt op of stelt een [StringFormatFlags](../../com.aspose.drawing/stringformatflags) enumeratie in die opmaakinformatie bevat. |
| [getAlignment()](#getAlignment--) | Haalt op of stelt tekstuitlijningsinformatie op het verticale vlak in. |
| [setAlignment(int value)](#setAlignment-int-) | Haalt op of stelt tekstuitlijningsinformatie op het verticale vlak in. |
| [getLineAlignment()](#getLineAlignment--) | Haalt op of stelt de lijnausrichting op het horizontale vlak in. |
| [setLineAlignment(int value)](#setLineAlignment-int-) | Haalt op of stelt de lijnausrichting op het horizontale vlak in. |
| [getHotkeyPrefix()](#getHotkeyPrefix--) | Haalt op of stelt het `HotkeyPrefix`([.getHotkeyPrefix](../../null/\#getHotkeyPrefix)/[.setHotkeyPrefix(int)](../../null/\#setHotkeyPrefix-int-)) object voor dit [StringFormat](../../com.aspose.drawing/stringformat) object in. |
| [setHotkeyPrefix(int value)](#setHotkeyPrefix-int-) | Haalt op of stelt het `HotkeyPrefix`([.getHotkeyPrefix](../../null/\#getHotkeyPrefix)/[.setHotkeyPrefix(int)](../../null/\#setHotkeyPrefix-int-)) object voor dit [StringFormat](../../com.aspose.drawing/stringformat) object in. |
| [getTrimming()](#getTrimming--) | Haalt op of stelt de [StringTrimming](../../com.aspose.drawing/stringtrimming) enumeratie voor dit [StringFormat](../../com.aspose.drawing/stringformat) object in. |
| [setTrimming(int value)](#setTrimming-int-) | Haalt op of stelt de [StringTrimming](../../com.aspose.drawing/stringtrimming) enumeratie voor dit [StringFormat](../../com.aspose.drawing/stringformat) object in. |
| [getDigitSubstitutionLanguage()](#getDigitSubstitutionLanguage--) | Haalt de taal op die wordt gebruikt wanneer lokale cijfers worden vervangen door westerse cijfers. |
| [getDigitSubstitutionMethod()](#getDigitSubstitutionMethod--) | Haalt de methode op die wordt gebruikt voor cijfervervanging. |
| [dispose()](#dispose--) | Geeft alle bronnen vrij die door dit [StringFormat](../../com.aspose.drawing/stringformat) object worden gebruikt. |
| [deepClone()](#deepClone--) | Maakt een exacte kopie van dit [StringFormat](../../com.aspose.drawing/stringformat) object. |
| [getTabStops(float[] firstTabOffset)](#getTabStops-float---) | Haalt de tabstops op voor dit [StringFormat](../../com.aspose.drawing/stringformat) object. |
| [getTabStops()](#getTabStops--) | Haalt een array op van afstanden tussen tabstops in de eenheden gespecificeerd door de `Aspose.Imaging.getGraphics().PageUnit` eigenschap. |
| [setTabStops(float firstTabOffset, float[] tabStops)](#setTabStops-float-float---) | Stelt tabstops in voor dit [StringFormat](../../com.aspose.drawing/stringformat) object. |
| [setDigitSubstitution(int language, int substitute)](#setDigitSubstitution-int-int-) | Specificeert de taal en methode die moeten worden gebruikt wanneer lokale cijfers worden vervangen door westerse cijfers. |
| [setMeasurableCharacterRanges(CharacterRange[] ranges)](#setMeasurableCharacterRanges-com.aspose.drawing.CharacterRange---) | Specificeert een array van [CharacterRange](../../com.aspose.drawing/characterrange) structuren die de reeksen van tekens vertegenwoordigen die gemeten worden door een aanroep van de `MeasureCharacterRanges` methode. |
### StringFormat() {#StringFormat--}
```
public StringFormat()
```


Initialiseert een nieuw exemplaar van de [StringFormat](../../com.aspose.drawing/stringformat) klasse.

### StringFormat(StringFormat format) {#StringFormat-com.aspose.drawing.StringFormat-}
```
public StringFormat(StringFormat format)
```


Initialiseert een nieuw exemplaar van de [StringFormat](../../com.aspose.drawing/stringformat) klasse vanuit het opgegeven bestaande [StringFormat](../../com.aspose.drawing/stringformat) object.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| format | [StringFormat](../../com.aspose.drawing/stringformat) | Het [StringFormat](../../com.aspose.drawing/stringformat) object waaruit het nieuwe [StringFormat](../../com.aspose.drawing/stringformat) object moet worden geïnitialiseerd. |

### StringFormat(int options, int language) {#StringFormat-int-int-}
```
public StringFormat(int options, int language)
```


Initialiseert een nieuw exemplaar van de [StringFormat](../../com.aspose.drawing/stringformat) klasse met de opgegeven [StringFormatFlags](../../com.aspose.drawing/stringformatflags) enumeratie en taal.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| options | int | De [StringFormatFlags](../../com.aspose.drawing/stringformatflags) enumeratie voor het nieuwe [StringFormat](../../com.aspose.drawing/stringformat) object. |
| taal | int | Een waarde die de taal van de tekst aangeeft. |

### StringFormat(int options) {#StringFormat-int-}
```
public StringFormat(int options)
```


Initialiseert een nieuw exemplaar van de [StringFormat](../../com.aspose.drawing/stringformat) klasse met de opgegeven [StringFormatFlags](../../com.aspose.drawing/stringformatflags) enumeratie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| options | int | De [StringFormatFlags](../../com.aspose.drawing/stringformatflags) enumeratie voor het nieuwe [StringFormat](../../com.aspose.drawing/stringformat) object. |

### setDigitSubstitutionLanguage(int value) {#setDigitSubstitutionLanguage-int-}
```
public void setDigitSubstitutionLanguage(int value)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### setDigitSubstitutionMethod(int value) {#setDigitSubstitutionMethod-int-}
```
public void setDigitSubstitutionMethod(int value)
```




**Parameters:**
| Parameter | Type | Beschrijving |
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


Haalt een generiek standaard [StringFormat](../../com.aspose.drawing/stringformat) object op.

**Returns:**
[StringFormat](../../com.aspose.drawing/stringformat)
### getGenericTypographic() {#getGenericTypographic--}
```
public static StringFormat getGenericTypographic()
```


Haalt een generiek typografisch [StringFormat](../../com.aspose.drawing/stringformat) object op.

**Returns:**
[StringFormat](../../com.aspose.drawing/stringformat) - A generic typographic [StringFormat](../../com.aspose.drawing/stringformat) object.
### getFormatFlags() {#getFormatFlags--}
```
public int getFormatFlags()
```


Haalt op of stelt een [StringFormatFlags](../../com.aspose.drawing/stringformatflags) enumeratie in die opmaakinformatie bevat.

**Returns:**
int
### setFormatFlags(int value) {#setFormatFlags-int-}
```
public void setFormatFlags(int value)
```


Haalt op of stelt een [StringFormatFlags](../../com.aspose.drawing/stringformatflags) enumeratie in die opmaakinformatie bevat.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getAlignment() {#getAlignment--}
```
public int getAlignment()
```


Haalt op of stelt tekstuitlijningsinformatie op het verticale vlak in.

**Returns:**
int
### setAlignment(int value) {#setAlignment-int-}
```
public void setAlignment(int value)
```


Haalt op of stelt tekstuitlijningsinformatie op het verticale vlak in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getLineAlignment() {#getLineAlignment--}
```
public int getLineAlignment()
```


Haalt op of stelt de lijnausrichting op het horizontale vlak in.

**Returns:**
int
### setLineAlignment(int value) {#setLineAlignment-int-}
```
public void setLineAlignment(int value)
```


Haalt op of stelt de lijnausrichting op het horizontale vlak in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getHotkeyPrefix() {#getHotkeyPrefix--}
```
public int getHotkeyPrefix()
```


Haalt op of stelt het `HotkeyPrefix`([.getHotkeyPrefix](../../null/\#getHotkeyPrefix)/[.setHotkeyPrefix(int)](../../null/\#setHotkeyPrefix-int-)) object voor dit [StringFormat](../../com.aspose.drawing/stringformat) object in.

**Returns:**
int
### setHotkeyPrefix(int value) {#setHotkeyPrefix-int-}
```
public void setHotkeyPrefix(int value)
```


Haalt op of stelt het `HotkeyPrefix`([.getHotkeyPrefix](../../null/\#getHotkeyPrefix)/[.setHotkeyPrefix(int)](../../null/\#setHotkeyPrefix-int-)) object voor dit [StringFormat](../../com.aspose.drawing/stringformat) object in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getTrimming() {#getTrimming--}
```
public int getTrimming()
```


Haalt op of stelt de [StringTrimming](../../com.aspose.drawing/stringtrimming) enumeratie voor dit [StringFormat](../../com.aspose.drawing/stringformat) object in.

**Returns:**
int
### setTrimming(int value) {#setTrimming-int-}
```
public void setTrimming(int value)
```


Haalt op of stelt de [StringTrimming](../../com.aspose.drawing/stringtrimming) enumeratie voor dit [StringFormat](../../com.aspose.drawing/stringformat) object in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getDigitSubstitutionLanguage() {#getDigitSubstitutionLanguage--}
```
public int getDigitSubstitutionLanguage()
```


Haalt de taal op die wordt gebruikt wanneer lokale cijfers worden vervangen door westerse cijfers.

**Returns:**
int - Een National Language Support (NLS) taalidentificatie die de taal aangeeft die zal worden gebruikt wanneer lokale cijfers worden vervangen door westerse cijfers. Je kunt de `System.Globalization.CultureInfo.LCID` eigenschap van een java.util.Locale object doorgeven als de NLS-taalidentificatie. Bijvoorbeeld, stel dat je een java.util.Locale object maakt door de tekenreeks "ar-EG" door te geven aan een java.util.Locale constructor. Als je de `System.Globalization.CultureInfo.LCID` eigenschap van dat java.util.Locale object samen met `StringDigitSubstitute.Traditional` doorgeeft aan de [.setDigitSubstitution(int,int)](../../null/\\#setDigitSubstitution-int-int-) methode, dan worden Arabisch-Indicische cijfers vervangen door westerse cijfers tijdens het weergeven.
### getDigitSubstitutionMethod() {#getDigitSubstitutionMethod--}
```
public int getDigitSubstitutionMethod()
```


Haalt de methode op die wordt gebruikt voor cijfervervanging.

**Returns:**
int - Een [StringDigitSubstitute](../../com.aspose.drawing/stringdigitsubstitute) enumeratiewaarde die aangeeft hoe tekens in een tekenreeks moeten worden vervangen die niet kunnen worden weergegeven omdat ze niet worden ondersteund door het huidige lettertype.
### dispose() {#dispose--}
```
public void dispose()
```


Geeft alle bronnen vrij die door dit [StringFormat](../../com.aspose.drawing/stringformat) object worden gebruikt.

### deepClone() {#deepClone--}
```
public StringFormat deepClone()
```


Maakt een exacte kopie van dit [StringFormat](../../com.aspose.drawing/stringformat) object.

**Returns:**
[StringFormat](../../com.aspose.drawing/stringformat) - The [StringFormat](../../com.aspose.drawing/stringformat) object this method creates.
### getTabStops(float[] firstTabOffset) {#getTabStops-float---}
```
public float[] getTabStops(float[] firstTabOffset)
```


Haalt de tabstops op voor dit [StringFormat](../../com.aspose.drawing/stringformat) object.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| firstTabOffset | float[] | Het aantal spaties tussen het begin van een tekstregel en de eerste tabstop. |

**Returns:**
float[] - Een array van afstanden (in aantal spaties) tussen tabstops.
### getTabStops() {#getTabStops--}
```
public float[] getTabStops()
```


Haalt een array op van afstanden tussen tabstops in de eenheden gespecificeerd door de `Aspose.Imaging.getGraphics().PageUnit` eigenschap.

**Returns:**
float[] - De tabstops.

De eigenschap is geïntroduceerd voor de verwijderde methode GetTabStops.
### setTabStops(float firstTabOffset, float[] tabStops) {#setTabStops-float-float---}
```
public void setTabStops(float firstTabOffset, float[] tabStops)
```


Stelt tabstops in voor dit [StringFormat](../../com.aspose.drawing/stringformat) object.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| firstTabOffset | float | Het aantal spaties tussen het begin van een tekstregel en de eerste tabstop. |
| tabStops | float[] | Een array van afstanden tussen tabstops in de eenheden die zijn opgegeven door de eigenschap Graphics.PageUnit. |

### setDigitSubstitution(int language, int substitute) {#setDigitSubstitution-int-int-}
```
public void setDigitSubstitution(int language, int substitute)
```


Specificeert de taal en methode die moeten worden gebruikt wanneer lokale cijfers worden vervangen door westerse cijfers.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| taal | int | Een National Language Support (NLS) taalidentificatie die de taal aangeeft die zal worden gebruikt wanneer lokale cijfers worden vervangen door westerse cijfers. Je kunt de `System.Globalization.CultureInfo.LCID` eigenschap van een java.util.Locale object doorgeven als de NLS-taalidentificatie. Bijvoorbeeld, stel dat je een java.util.Locale object maakt door de tekenreeks `\"ar-EG\"` door te geven aan een java.util.Locale constructor. Als je de `System.Globalization.CultureInfo.LCID` eigenschap van dat java.util.Locale object samen met `StringDigitSubstitute.Traditional` doorgeeft aan de `M:StringFormat.SetDigitSubstitution(System.Int32,StringDigitSubstitute)` methode, dan worden Arabisch-Indicische cijfers vervangen door westerse cijfers tijdens het weergeven. |
| substitute | int | Een element van de [StringDigitSubstitute](../../com.aspose.drawing/stringdigitsubstitute) enumeratie die aangeeft hoe cijfers worden weergegeven. |

### setMeasurableCharacterRanges(CharacterRange[] ranges) {#setMeasurableCharacterRanges-com.aspose.drawing.CharacterRange---}
```
public void setMeasurableCharacterRanges(CharacterRange[] ranges)
```


Specificeert een array van [CharacterRange](../../com.aspose.drawing/characterrange) structuren die de reeksen van tekens vertegenwoordigen die gemeten worden door een aanroep van de `MeasureCharacterRanges` methode.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| ranges | [CharacterRange\[\]](../../com.aspose.drawing/characterrange) | Een array van [CharacterRange](../../com.aspose.drawing/characterrange) structuren die de reeksen tekens specificeren die worden gemeten door een oproep naar de `MeasureCharacterRanges` methode. |

