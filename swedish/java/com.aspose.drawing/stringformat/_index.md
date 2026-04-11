---
title: StringFormat
second_title: Aspose.Drawing för Java API‑referens
description: Inkapslar information om textlayout såsom justeringsorientering och tabbstopp, samt visningsmanipulationer som infogning av ellips och nationell siffrasubstitution samt OpenType-funktioner.
type: docs
weight: 47
url: /sv/java/com.aspose.drawing/stringformat/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public final class StringFormat implements System.IDisposable
```

Inkapslar information om textlayout (såsom justering, orientering och tabbstopp) displaymanipulationer (såsom införande av ellipser och nationell siffrasubstitution) och OpenType-funktioner. Denna klass kan inte ärvas.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [StringFormat()](#StringFormat--) | Initierar en ny instans av klassen [StringFormat](../../com.aspose.drawing/stringformat). |
| [StringFormat(StringFormat format)](#StringFormat-com.aspose.drawing.StringFormat-) | Initierar en ny instans av klassen [StringFormat](../../com.aspose.drawing/stringformat) från det angivna befintliga [StringFormat](../../com.aspose.drawing/stringformat)-objektet. |
| [StringFormat(int options, int language)](#StringFormat-int-int-) | Initierar en ny instans av klassen [StringFormat](../../com.aspose.drawing/stringformat) med den angivna uppräkningen [StringFormatFlags](../../com.aspose.drawing/stringformatflags) och språk. |
| [StringFormat(int options)](#StringFormat-int-) | Initierar en ny instans av klassen [StringFormat](../../com.aspose.drawing/stringformat) med den angivna uppräkningen [StringFormatFlags](../../com.aspose.drawing/stringformatflags). |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [setDigitSubstitutionLanguage(int value)](#setDigitSubstitutionLanguage-int-) |  |
| [setDigitSubstitutionMethod(int value)](#setDigitSubstitutionMethod-int-) |  |
| [getFirstTabOffset()](#getFirstTabOffset--) |  |
| [getGenericDefault()](#getGenericDefault--) | Hämtar ett generiskt standardobjekt av typen [StringFormat](../../com.aspose.drawing/stringformat). |
| [getGenericTypographic()](#getGenericTypographic--) | Hämtar ett generiskt typografiskt [StringFormat](../../com.aspose.drawing/stringformat)-objekt. |
| [getFormatFlags()](#getFormatFlags--) | Hämtar eller anger en uppräkning [StringFormatFlags](../../com.aspose.drawing/stringformatflags) som innehåller formateringsinformation. |
| [setFormatFlags(int value)](#setFormatFlags-int-) | Hämtar eller anger en uppräkning [StringFormatFlags](../../com.aspose.drawing/stringformatflags) som innehåller formateringsinformation. |
| [getAlignment()](#getAlignment--) | Hämtar eller anger information om textjustering på den vertikala planet. |
| [setAlignment(int value)](#setAlignment-int-) | Hämtar eller anger information om textjustering på den vertikala planet. |
| [getLineAlignment()](#getLineAlignment--) | Hämtar eller anger radjustering på det horisontella planet. |
| [setLineAlignment(int value)](#setLineAlignment-int-) | Hämtar eller anger radjustering på det horisontella planet. |
| [getHotkeyPrefix()](#getHotkeyPrefix--) | Hämtar eller anger `HotkeyPrefix`([.getHotkeyPrefix](../../null/\#getHotkeyPrefix)/[.setHotkeyPrefix(int)](../../null/\#setHotkeyPrefix-int-))-objektet för detta [StringFormat](../../com.aspose.drawing/stringformat)-objekt. |
| [setHotkeyPrefix(int value)](#setHotkeyPrefix-int-) | Hämtar eller anger `HotkeyPrefix`([.getHotkeyPrefix](../../null/\#getHotkeyPrefix)/[.setHotkeyPrefix(int)](../../null/\#setHotkeyPrefix-int-))-objektet för detta [StringFormat](../../com.aspose.drawing/stringformat)-objekt. |
| [getTrimming()](#getTrimming--) | Hämtar eller anger uppräkningen [StringTrimming](../../com.aspose.drawing/stringtrimming) för detta [StringFormat](../../com.aspose.drawing/stringformat)-objekt. |
| [setTrimming(int value)](#setTrimming-int-) | Hämtar eller anger uppräkningen [StringTrimming](../../com.aspose.drawing/stringtrimming) för detta [StringFormat](../../com.aspose.drawing/stringformat)-objekt. |
| [getDigitSubstitutionLanguage()](#getDigitSubstitutionLanguage--) | Hämtar språket som används när lokala siffror ersätts med västerländska siffror. |
| [getDigitSubstitutionMethod()](#getDigitSubstitutionMethod--) | Hämtar metoden som ska användas för siffersubstitution. |
| [dispose()](#dispose--) | Frigör alla resurser som används av detta [StringFormat](../../com.aspose.drawing/stringformat)-objekt. |
| [deepClone()](#deepClone--) | Skapar en exakt kopia av detta [StringFormat](../../com.aspose.drawing/stringformat)-objekt. |
| [getTabStops(float[] firstTabOffset)](#getTabStops-float---) | Hämtar tabbstoppen för detta [StringFormat](../../com.aspose.drawing/stringformat)-objekt. |
| [getTabStops()](#getTabStops--) | Hämtar en matris med avstånd mellan tabbstopp i de enheter som anges av egenskapen `Aspose.Imaging.getGraphics().PageUnit`. |
| [setTabStops(float firstTabOffset, float[] tabStops)](#setTabStops-float-float---) | Anger tabbstopp för detta [StringFormat](../../com.aspose.drawing/stringformat)-objekt. |
| [setDigitSubstitution(int language, int substitute)](#setDigitSubstitution-int-int-) | Anger språk och metod som ska användas när lokala siffror ersätts med västerländska siffror. |
| [setMeasurableCharacterRanges(CharacterRange[] ranges)](#setMeasurableCharacterRanges-com.aspose.drawing.CharacterRange---) | Anger en matris med [CharacterRange](../../com.aspose.drawing/characterrange)-strukturer som representerar teckenintervall som mäts av ett anrop till metoden `MeasureCharacterRanges`. |
### StringFormat() {#StringFormat--}
```
public StringFormat()
```


Initierar en ny instans av klassen [StringFormat](../../com.aspose.drawing/stringformat).

### StringFormat(StringFormat format) {#StringFormat-com.aspose.drawing.StringFormat-}
```
public StringFormat(StringFormat format)
```


Initierar en ny instans av klassen [StringFormat](../../com.aspose.drawing/stringformat) från det angivna befintliga [StringFormat](../../com.aspose.drawing/stringformat)-objektet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| format | [StringFormat](../../com.aspose.drawing/stringformat) | [StringFormat](../../com.aspose.drawing/stringformat)-objektet som ska användas för att initiera det nya [StringFormat](../../com.aspose.drawing/stringformat)-objektet. |

### StringFormat(int options, int language) {#StringFormat-int-int-}
```
public StringFormat(int options, int language)
```


Initierar en ny instans av klassen [StringFormat](../../com.aspose.drawing/stringformat) med den angivna uppräkningen [StringFormatFlags](../../com.aspose.drawing/stringformatflags) och språk.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| options | int | Uppräkningen [StringFormatFlags](../../com.aspose.drawing/stringformatflags) för det nya [StringFormat](../../com.aspose.drawing/stringformat)-objektet. |
| språk | int | Ett värde som indikerar textens språk. |

### StringFormat(int options) {#StringFormat-int-}
```
public StringFormat(int options)
```


Initierar en ny instans av klassen [StringFormat](../../com.aspose.drawing/stringformat) med den angivna uppräkningen [StringFormatFlags](../../com.aspose.drawing/stringformatflags).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| options | int | Uppräkningen [StringFormatFlags](../../com.aspose.drawing/stringformatflags) för det nya [StringFormat](../../com.aspose.drawing/stringformat)-objektet. |

### setDigitSubstitutionLanguage(int value) {#setDigitSubstitutionLanguage-int-}
```
public void setDigitSubstitutionLanguage(int value)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### setDigitSubstitutionMethod(int value) {#setDigitSubstitutionMethod-int-}
```
public void setDigitSubstitutionMethod(int value)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getFirstTabOffset() {#getFirstTabOffset--}
```
public float getFirstTabOffset()
```




**Returns:**
flyttal
### getGenericDefault() {#getGenericDefault--}
```
public static StringFormat getGenericDefault()
```


Hämtar ett generiskt standardobjekt av typen [StringFormat](../../com.aspose.drawing/stringformat).

**Returns:**
[StringFormat](../../com.aspose.drawing/stringformat)
### getGenericTypographic() {#getGenericTypographic--}
```
public static StringFormat getGenericTypographic()
```


Hämtar ett generiskt typografiskt [StringFormat](../../com.aspose.drawing/stringformat)-objekt.

**Returns:**
[StringFormat](../../com.aspose.drawing/stringformat) - A generic typographic [StringFormat](../../com.aspose.drawing/stringformat) object.
### getFormatFlags() {#getFormatFlags--}
```
public int getFormatFlags()
```


Hämtar eller anger en uppräkning [StringFormatFlags](../../com.aspose.drawing/stringformatflags) som innehåller formateringsinformation.

**Returns:**
int
### setFormatFlags(int value) {#setFormatFlags-int-}
```
public void setFormatFlags(int value)
```


Hämtar eller anger en uppräkning [StringFormatFlags](../../com.aspose.drawing/stringformatflags) som innehåller formateringsinformation.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getAlignment() {#getAlignment--}
```
public int getAlignment()
```


Hämtar eller anger information om textjustering på den vertikala planet.

**Returns:**
int
### setAlignment(int value) {#setAlignment-int-}
```
public void setAlignment(int value)
```


Hämtar eller anger information om textjustering på den vertikala planet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getLineAlignment() {#getLineAlignment--}
```
public int getLineAlignment()
```


Hämtar eller anger radjustering på det horisontella planet.

**Returns:**
int
### setLineAlignment(int value) {#setLineAlignment-int-}
```
public void setLineAlignment(int value)
```


Hämtar eller anger radjustering på det horisontella planet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getHotkeyPrefix() {#getHotkeyPrefix--}
```
public int getHotkeyPrefix()
```


Hämtar eller anger `HotkeyPrefix`([.getHotkeyPrefix](../../null/\#getHotkeyPrefix)/[.setHotkeyPrefix(int)](../../null/\#setHotkeyPrefix-int-))-objektet för detta [StringFormat](../../com.aspose.drawing/stringformat)-objekt.

**Returns:**
int
### setHotkeyPrefix(int value) {#setHotkeyPrefix-int-}
```
public void setHotkeyPrefix(int value)
```


Hämtar eller anger `HotkeyPrefix`([.getHotkeyPrefix](../../null/\#getHotkeyPrefix)/[.setHotkeyPrefix(int)](../../null/\#setHotkeyPrefix-int-))-objektet för detta [StringFormat](../../com.aspose.drawing/stringformat)-objekt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getTrimming() {#getTrimming--}
```
public int getTrimming()
```


Hämtar eller anger uppräkningen [StringTrimming](../../com.aspose.drawing/stringtrimming) för detta [StringFormat](../../com.aspose.drawing/stringformat)-objekt.

**Returns:**
int
### setTrimming(int value) {#setTrimming-int-}
```
public void setTrimming(int value)
```


Hämtar eller anger uppräkningen [StringTrimming](../../com.aspose.drawing/stringtrimming) för detta [StringFormat](../../com.aspose.drawing/stringformat)-objekt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getDigitSubstitutionLanguage() {#getDigitSubstitutionLanguage--}
```
public int getDigitSubstitutionLanguage()
```


Hämtar språket som används när lokala siffror ersätts med västerländska siffror.

**Returns:**
int - En National Language Support (NLS) språkidentifierare som identifierar språket som kommer att användas när lokala siffror ersätts med västerländska siffror. Du kan skicka `System.Globalization.CultureInfo.LCID`-egenskapen för ett java.util.Locale‑objekt som NLS‑språkidentifierare. Till exempel, anta att du skapar ett java.util.Locale‑objekt genom att skicka strängen \"ar-EG\" till en java.util.Locale‑konstruktor. Om du skickar `System.Globalization.CultureInfo.LCID`‑egenskapen för det java.util.Locale‑objektet tillsammans med`StringDigitSubstitute.Traditional` till metoden [.setDigitSubstitution(int,int)](../../null/\#setDigitSubstitution-int-int-), så kommer arabiskt‑indiska siffror att ersättas med västerländska siffror vid visningstid.
### getDigitSubstitutionMethod() {#getDigitSubstitutionMethod--}
```
public int getDigitSubstitutionMethod()
```


Hämtar metoden som ska användas för siffersubstitution.

**Returns:**
int - En [StringDigitSubstitute](../../com.aspose.drawing/stringdigitsubstitute)‑enumerationsvärde som specificerar hur tecken i en sträng som inte kan visas eftersom de inte stöds av det aktuella teckensnittet ska ersättas.
### dispose() {#dispose--}
```
public void dispose()
```


Frigör alla resurser som används av detta [StringFormat](../../com.aspose.drawing/stringformat)-objekt.

### deepClone() {#deepClone--}
```
public StringFormat deepClone()
```


Skapar en exakt kopia av detta [StringFormat](../../com.aspose.drawing/stringformat)-objekt.

**Returns:**
[StringFormat](../../com.aspose.drawing/stringformat) - The [StringFormat](../../com.aspose.drawing/stringformat) object this method creates.
### getTabStops(float[] firstTabOffset) {#getTabStops-float---}
```
public float[] getTabStops(float[] firstTabOffset)
```


Hämtar tabbstoppen för detta [StringFormat](../../com.aspose.drawing/stringformat)-objekt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| firstTabOffset | float[] | Antalet mellanslag mellan början av en textrad och den första tabbstoppet. |

**Returns:**
float[] - En array av avstånd (i antal mellanslag) mellan tabbstopp.
### getTabStops() {#getTabStops--}
```
public float[] getTabStops()
```


Hämtar en matris med avstånd mellan tabbstopp i de enheter som anges av egenskapen `Aspose.Imaging.getGraphics().PageUnit`.

**Returns:**
float[] - Tabbpositionerna.

Egenskapen introduceras för den borttagna metoden GetTabStops.
### setTabStops(float firstTabOffset, float[] tabStops) {#setTabStops-float-float---}
```
public void setTabStops(float firstTabOffset, float[] tabStops)
```


Anger tabbstopp för detta [StringFormat](../../com.aspose.drawing/stringformat)-objekt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| firstTabOffset | flyttal | Antalet mellanslag mellan början av en textrad och den första tabbstoppet. |
| tabStops | float[] | En array av avstånd mellan tabbstopp i de enheter som anges av egenskapen Graphics.PageUnit. |

### setDigitSubstitution(int language, int substitute) {#setDigitSubstitution-int-int-}
```
public void setDigitSubstitution(int language, int substitute)
```


Anger språk och metod som ska användas när lokala siffror ersätts med västerländska siffror.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| språk | int | En National Language Support (NLS) språkidentifierare som identifierar språket som kommer att användas när lokala siffror ersätts med västerländska siffror. Du kan skicka `System.Globalization.CultureInfo.LCID`‑egenskapen för ett java.util.Locale‑objekt som NLS‑språkidentifierare. Till exempel, anta att du skapar ett java.util.Locale‑objekt genom att skicka strängen `\"ar-EG\"` till en java.util.Locale‑konstruktor. Om du skickar `System.Globalization.CultureInfo.LCID`‑egenskapen för det java.util.Locale‑objektet tillsammans med `StringDigitSubstitute.Traditional` till metoden `M:StringFormat.SetDigitSubstitution(System.Int32,StringDigitSubstitute)`, så kommer arabiskt‑indiska siffror att ersättas med västerländska siffror vid visningstid. |
| substitute | int | Ett element i [StringDigitSubstitute](../../com.aspose.drawing/stringdigitsubstitute)‑enumerationen som specificerar hur siffror visas. |

### setMeasurableCharacterRanges(CharacterRange[] ranges) {#setMeasurableCharacterRanges-com.aspose.drawing.CharacterRange---}
```
public void setMeasurableCharacterRanges(CharacterRange[] ranges)
```


Anger en matris med [CharacterRange](../../com.aspose.drawing/characterrange)-strukturer som representerar teckenintervall som mäts av ett anrop till metoden `MeasureCharacterRanges`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ranges | [CharacterRange\[\]](../../com.aspose.drawing/characterrange) | En array av [CharacterRange](../../com.aspose.drawing/characterrange)‑strukturer som specificerar intervallen av tecken som mäts av ett anrop till `MeasureCharacterRanges`‑metoden. |

