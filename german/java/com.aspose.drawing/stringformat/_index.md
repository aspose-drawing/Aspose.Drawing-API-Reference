---
title: StringFormat
second_title: Aspose.Drawing für Java API-Referenz
description: Kapselt Textlayout-Informationen wie Ausrichtungsorientierung und Tabulatorpositionen sowie Anzeige-Manipulationen wie das Einfügen von Auslassungszeichen, nationale Ziffernersetzung und OpenType‑Funktionen.
type: docs
weight: 47
url: /de/java/com.aspose.drawing/stringformat/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public final class StringFormat implements System.IDisposable
```

Kapselt Textlayout-Informationen (wie Ausrichtung, Orientierung und Tabulatoren), Anzeige-Manipulationen (wie Ellipsen-Einfügung und nationale Ziffernersetzung) und OpenType‑Funktionen. Diese Klasse kann nicht abgeleitet werden.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [StringFormat()](#StringFormat--) | Initialisiert eine neue Instanz der [StringFormat](../../com.aspose.drawing/stringformat)-Klasse. |
| [StringFormat(StringFormat format)](#StringFormat-com.aspose.drawing.StringFormat-) | Initialisiert eine neue Instanz der [StringFormat](../../com.aspose.drawing/stringformat)-Klasse aus dem angegebenen vorhandenen [StringFormat](../../com.aspose.drawing/stringformat)-Objekt. |
| [StringFormat(int options, int language)](#StringFormat-int-int-) | Initialisiert eine neue Instanz der [StringFormat](../../com.aspose.drawing/stringformat)-Klasse mit der angegebenen [StringFormatFlags](../../com.aspose.drawing/stringformatflags)-Aufzählung und Sprache. |
| [StringFormat(int options)](#StringFormat-int-) | Initialisiert eine neue Instanz der [StringFormat](../../com.aspose.drawing/stringformat)-Klasse mit der angegebenen [StringFormatFlags](../../com.aspose.drawing/stringformatflags)-Aufzählung. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [setDigitSubstitutionLanguage(int value)](#setDigitSubstitutionLanguage-int-) |  |
| [setDigitSubstitutionMethod(int value)](#setDigitSubstitutionMethod-int-) |  |
| [getFirstTabOffset()](#getFirstTabOffset--) |  |
| [getGenericDefault()](#getGenericDefault--) | Ruft ein generisches Standard-[StringFormat](../../com.aspose.drawing/stringformat)-Objekt ab. |
| [getGenericTypographic()](#getGenericTypographic--) | Ruft ein generisches typografisches [StringFormat](../../com.aspose.drawing/stringformat)-Objekt ab. |
| [getFormatFlags()](#getFormatFlags--) | Ruft ab oder legt eine [StringFormatFlags](../../com.aspose.drawing/stringformatflags)-Aufzählung fest, die Formatierungsinformationen enthält. |
| [setFormatFlags(int value)](#setFormatFlags-int-) | Ruft ab oder legt eine [StringFormatFlags](../../com.aspose.drawing/stringformatflags)-Aufzählung fest, die Formatierungsinformationen enthält. |
| [getAlignment()](#getAlignment--) | Ruft ab oder legt Textausrichtungsinformationen in der vertikalen Ebene fest. |
| [setAlignment(int value)](#setAlignment-int-) | Ruft ab oder legt Textausrichtungsinformationen in der vertikalen Ebene fest. |
| [getLineAlignment()](#getLineAlignment--) | Ruft ab oder legt die Zeilenausrichtung in der horizontalen Ebene fest. |
| [setLineAlignment(int value)](#setLineAlignment-int-) | Ruft ab oder legt die Zeilenausrichtung in der horizontalen Ebene fest. |
| [getHotkeyPrefix()](#getHotkeyPrefix--) | Ruft ab oder legt das `HotkeyPrefix`([.getHotkeyPrefix](../../null/\#getHotkeyPrefix)/[.setHotkeyPrefix(int)](../../null/\#setHotkeyPrefix-int-))-Objekt für dieses [StringFormat](../../com.aspose.drawing/stringformat)-Objekt fest. |
| [setHotkeyPrefix(int value)](#setHotkeyPrefix-int-) | Ruft ab oder legt das `HotkeyPrefix`([.getHotkeyPrefix](../../null/\#getHotkeyPrefix)/[.setHotkeyPrefix(int)](../../null/\#setHotkeyPrefix-int-))-Objekt für dieses [StringFormat](../../com.aspose.drawing/stringformat)-Objekt fest. |
| [getTrimming()](#getTrimming--) | Ruft ab oder legt die [StringTrimming](../../com.aspose.drawing/stringtrimming)-Aufzählung für dieses [StringFormat](../../com.aspose.drawing/stringformat)-Objekt fest. |
| [setTrimming(int value)](#setTrimming-int-) | Ruft ab oder legt die [StringTrimming](../../com.aspose.drawing/stringtrimming)-Aufzählung für dieses [StringFormat](../../com.aspose.drawing/stringformat)-Objekt fest. |
| [getDigitSubstitutionLanguage()](#getDigitSubstitutionLanguage--) | Ruft die Sprache ab, die verwendet wird, wenn lokale Ziffern durch westliche Ziffern ersetzt werden. |
| [getDigitSubstitutionMethod()](#getDigitSubstitutionMethod--) | Ruft die Methode ab, die für die Ziffernersetzung verwendet wird. |
| [dispose()](#dispose--) | Gibt alle von diesem [StringFormat](../../com.aspose.drawing/stringformat)-Objekt verwendeten Ressourcen frei. |
| [deepClone()](#deepClone--) | Erstellt eine exakte Kopie dieses [StringFormat](../../com.aspose.drawing/stringformat)-Objekts. |
| [getTabStops(float[] firstTabOffset)](#getTabStops-float---) | Ruft die Tabulatoren für dieses [StringFormat](../../com.aspose.drawing/stringformat)-Objekt ab. |
| [getTabStops()](#getTabStops--) | Ruft ein Array von Abständen zwischen Tabulatoren in den durch die Eigenschaft `Aspose.Imaging.getGraphics().PageUnit` angegebenen Einheiten ab. |
| [setTabStops(float firstTabOffset, float[] tabStops)](#setTabStops-float-float---) | Legt Tabulatoren für dieses [StringFormat](../../com.aspose.drawing/stringformat)-Objekt fest. |
| [setDigitSubstitution(int language, int substitute)](#setDigitSubstitution-int-int-) | Gibt die Sprache und Methode an, die verwendet werden soll, wenn lokale Ziffern durch westliche Ziffern ersetzt werden. |
| [setMeasurableCharacterRanges(CharacterRange[] ranges)](#setMeasurableCharacterRanges-com.aspose.drawing.CharacterRange---) | Gibt ein Array von [CharacterRange](../../com.aspose.drawing/characterrange)-Strukturen an, die die Zeichenbereiche darstellen, die durch einen Aufruf der `MeasureCharacterRanges`‑Methode gemessen werden. |
### StringFormat() {#StringFormat--}
```
public StringFormat()
```


Initialisiert eine neue Instanz der [StringFormat](../../com.aspose.drawing/stringformat)-Klasse.

### StringFormat(StringFormat format) {#StringFormat-com.aspose.drawing.StringFormat-}
```
public StringFormat(StringFormat format)
```


Initialisiert eine neue Instanz der [StringFormat](../../com.aspose.drawing/stringformat)-Klasse aus dem angegebenen vorhandenen [StringFormat](../../com.aspose.drawing/stringformat)-Objekt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| format | [StringFormat](../../com.aspose.drawing/stringformat) | Das [StringFormat](../../com.aspose.drawing/stringformat)-Objekt, aus dem das neue [StringFormat](../../com.aspose.drawing/stringformat)-Objekt initialisiert wird. |

### StringFormat(int options, int language) {#StringFormat-int-int-}
```
public StringFormat(int options, int language)
```


Initialisiert eine neue Instanz der [StringFormat](../../com.aspose.drawing/stringformat)-Klasse mit der angegebenen [StringFormatFlags](../../com.aspose.drawing/stringformatflags)-Aufzählung und Sprache.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| options | int | Die [StringFormatFlags](../../com.aspose.drawing/stringformatflags)-Aufzählung für das neue [StringFormat](../../com.aspose.drawing/stringformat)-Objekt. |
| Sprache | int | Ein Wert, der die Sprache des Textes angibt. |

### StringFormat(int options) {#StringFormat-int-}
```
public StringFormat(int options)
```


Initialisiert eine neue Instanz der [StringFormat](../../com.aspose.drawing/stringformat)-Klasse mit der angegebenen [StringFormatFlags](../../com.aspose.drawing/stringformatflags)-Aufzählung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| options | int | Die [StringFormatFlags](../../com.aspose.drawing/stringformatflags)-Aufzählung für das neue [StringFormat](../../com.aspose.drawing/stringformat)-Objekt. |

### setDigitSubstitutionLanguage(int value) {#setDigitSubstitutionLanguage-int-}
```
public void setDigitSubstitutionLanguage(int value)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### setDigitSubstitutionMethod(int value) {#setDigitSubstitutionMethod-int-}
```
public void setDigitSubstitutionMethod(int value)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
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


Ruft ein generisches Standard-[StringFormat](../../com.aspose.drawing/stringformat)-Objekt ab.

**Returns:**
[StringFormat](../../com.aspose.drawing/stringformat)
### getGenericTypographic() {#getGenericTypographic--}
```
public static StringFormat getGenericTypographic()
```


Ruft ein generisches typografisches [StringFormat](../../com.aspose.drawing/stringformat)-Objekt ab.

**Returns:**
[StringFormat](../../com.aspose.drawing/stringformat) - A generic typographic [StringFormat](../../com.aspose.drawing/stringformat) object.
### getFormatFlags() {#getFormatFlags--}
```
public int getFormatFlags()
```


Ruft ab oder legt eine [StringFormatFlags](../../com.aspose.drawing/stringformatflags)-Aufzählung fest, die Formatierungsinformationen enthält.

**Returns:**
int
### setFormatFlags(int value) {#setFormatFlags-int-}
```
public void setFormatFlags(int value)
```


Ruft ab oder legt eine [StringFormatFlags](../../com.aspose.drawing/stringformatflags)-Aufzählung fest, die Formatierungsinformationen enthält.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getAlignment() {#getAlignment--}
```
public int getAlignment()
```


Ruft ab oder legt Textausrichtungsinformationen in der vertikalen Ebene fest.

**Returns:**
int
### setAlignment(int value) {#setAlignment-int-}
```
public void setAlignment(int value)
```


Ruft ab oder legt Textausrichtungsinformationen in der vertikalen Ebene fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getLineAlignment() {#getLineAlignment--}
```
public int getLineAlignment()
```


Ruft ab oder legt die Zeilenausrichtung in der horizontalen Ebene fest.

**Returns:**
int
### setLineAlignment(int value) {#setLineAlignment-int-}
```
public void setLineAlignment(int value)
```


Ruft ab oder legt die Zeilenausrichtung in der horizontalen Ebene fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getHotkeyPrefix() {#getHotkeyPrefix--}
```
public int getHotkeyPrefix()
```


Ruft ab oder legt das `HotkeyPrefix`([.getHotkeyPrefix](../../null/\#getHotkeyPrefix)/[.setHotkeyPrefix(int)](../../null/\#setHotkeyPrefix-int-))-Objekt für dieses [StringFormat](../../com.aspose.drawing/stringformat)-Objekt fest.

**Returns:**
int
### setHotkeyPrefix(int value) {#setHotkeyPrefix-int-}
```
public void setHotkeyPrefix(int value)
```


Ruft ab oder legt das `HotkeyPrefix`([.getHotkeyPrefix](../../null/\#getHotkeyPrefix)/[.setHotkeyPrefix(int)](../../null/\#setHotkeyPrefix-int-))-Objekt für dieses [StringFormat](../../com.aspose.drawing/stringformat)-Objekt fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getTrimming() {#getTrimming--}
```
public int getTrimming()
```


Ruft ab oder legt die [StringTrimming](../../com.aspose.drawing/stringtrimming)-Aufzählung für dieses [StringFormat](../../com.aspose.drawing/stringformat)-Objekt fest.

**Returns:**
int
### setTrimming(int value) {#setTrimming-int-}
```
public void setTrimming(int value)
```


Ruft ab oder legt die [StringTrimming](../../com.aspose.drawing/stringtrimming)-Aufzählung für dieses [StringFormat](../../com.aspose.drawing/stringformat)-Objekt fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getDigitSubstitutionLanguage() {#getDigitSubstitutionLanguage--}
```
public int getDigitSubstitutionLanguage()
```


Ruft die Sprache ab, die verwendet wird, wenn lokale Ziffern durch westliche Ziffern ersetzt werden.

**Returns:**
int - Ein National Language Support (NLS) Sprachbezeichner, der die Sprache identifiziert, die verwendet wird, wenn lokale Ziffern durch westliche Ziffern ersetzt werden. Sie können die `System.Globalization.CultureInfo.LCID`‑Eigenschaft eines java.util.Locale‑Objekts als NLS‑Sprachbezeichner übergeben. Zum Beispiel, nehmen wir an, Sie erstellen ein java.util.Locale‑Objekt, indem Sie den String "ar-EG" an einen java.util.Locale‑Konstruktor übergeben. Wenn Sie die `System.Globalization.CultureInfo.LCID`‑Eigenschaft dieses java.util.Locale‑Objekts zusammen mit `StringDigitSubstitute.Traditional` an die [.setDigitSubstitution(int,int)](../../null/\#setDigitSubstitution-int-int-)‑Methode übergeben, werden arabisch‑indische Ziffern zur Anzeigezeit durch westliche Ziffern ersetzt.
### getDigitSubstitutionMethod() {#getDigitSubstitutionMethod--}
```
public int getDigitSubstitutionMethod()
```


Ruft die Methode ab, die für die Ziffernersetzung verwendet wird.

**Returns:**
int - Ein [StringDigitSubstitute](../../com.aspose.drawing/stringdigitsubstitute)-Aufzählungswert, der angibt, wie Zeichen in einem String ersetzt werden sollen, die nicht angezeigt werden können, weil sie von der aktuellen Schriftart nicht unterstützt werden.
### dispose() {#dispose--}
```
public void dispose()
```


Gibt alle von diesem [StringFormat](../../com.aspose.drawing/stringformat)-Objekt verwendeten Ressourcen frei.

### deepClone() {#deepClone--}
```
public StringFormat deepClone()
```


Erstellt eine exakte Kopie dieses [StringFormat](../../com.aspose.drawing/stringformat)-Objekts.

**Returns:**
[StringFormat](../../com.aspose.drawing/stringformat) - The [StringFormat](../../com.aspose.drawing/stringformat) object this method creates.
### getTabStops(float[] firstTabOffset) {#getTabStops-float---}
```
public float[] getTabStops(float[] firstTabOffset)
```


Ruft die Tabulatoren für dieses [StringFormat](../../com.aspose.drawing/stringformat)-Objekt ab.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| firstTabOffset | float[] | Die Anzahl der Leerzeichen zwischen dem Beginn einer Textzeile und dem ersten Tabstopp. |

**Returns:**
float[] - Ein Array von Abständen (in Anzahl von Leerzeichen) zwischen Tabstopps.
### getTabStops() {#getTabStops--}
```
public float[] getTabStops()
```


Ruft ein Array von Abständen zwischen Tabulatoren in den durch die Eigenschaft `Aspose.Imaging.getGraphics().PageUnit` angegebenen Einheiten ab.

**Returns:**
float[] - Die Tabstopps.

Die Eigenschaft wurde für die entfernte Methode GetTabStops eingeführt.
### setTabStops(float firstTabOffset, float[] tabStops) {#setTabStops-float-float---}
```
public void setTabStops(float firstTabOffset, float[] tabStops)
```


Legt Tabulatoren für dieses [StringFormat](../../com.aspose.drawing/stringformat)-Objekt fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| firstTabOffset | float | Die Anzahl der Leerzeichen zwischen dem Beginn einer Textzeile und dem ersten Tabstopp. |
| tabStops | float[] | Ein Array von Abständen zwischen Tabstopps in den Einheiten, die durch die Eigenschaft Graphics.PageUnit angegeben werden. |

### setDigitSubstitution(int language, int substitute) {#setDigitSubstitution-int-int-}
```
public void setDigitSubstitution(int language, int substitute)
```


Gibt die Sprache und Methode an, die verwendet werden soll, wenn lokale Ziffern durch westliche Ziffern ersetzt werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Sprache | int | Ein National Language Support (NLS) Sprachbezeichner, der die Sprache identifiziert, die verwendet wird, wenn lokale Ziffern durch westliche Ziffern ersetzt werden. Sie können die `System.Globalization.CultureInfo.LCID`‑Eigenschaft eines java.util.Locale‑Objekts als NLS‑Sprachbezeichner übergeben. Zum Beispiel, nehmen wir an, Sie erstellen ein java.util.Locale‑Objekt, indem Sie den String `"ar-EG"` an einen java.util.Locale‑Konstruktor übergeben. Wenn Sie die `System.Globalization.CultureInfo.LCID`‑Eigenschaft dieses java.util.Locale‑Objekts zusammen mit `StringDigitSubstitute.Traditional` an die `M:StringFormat.SetDigitSubstitution(System.Int32,StringDigitSubstitute)`‑Methode übergeben, werden arabisch‑indische Ziffern zur Anzeigezeit durch westliche Ziffern ersetzt. |
| substitute | int | Ein Element der [StringDigitSubstitute](../../com.aspose.drawing/stringdigitsubstitute)-Aufzählung, das angibt, wie Ziffern angezeigt werden. |

### setMeasurableCharacterRanges(CharacterRange[] ranges) {#setMeasurableCharacterRanges-com.aspose.drawing.CharacterRange---}
```
public void setMeasurableCharacterRanges(CharacterRange[] ranges)
```


Gibt ein Array von [CharacterRange](../../com.aspose.drawing/characterrange)-Strukturen an, die die Zeichenbereiche darstellen, die durch einen Aufruf der `MeasureCharacterRanges`‑Methode gemessen werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| ranges | [CharacterRange\[\]](../../com.aspose.drawing/characterrange) | Ein Array von [CharacterRange](../../com.aspose.drawing/characterrange)-Strukturen, das die Bereiche von Zeichen angibt, die durch einen Aufruf der `MeasureCharacterRanges`‑Methode gemessen werden. |

