---
title: StringFormat
second_title: Riferimento API di Aspose.Drawing per Java
description: Incapsula le informazioni di layout del testo, come l'orientamento di allineamento e le manipolazioni di visualizzazione delle tabulazioni, come l'inserimento di ellissi, la sostituzione di cifre nazionali e le funzionalità OpenType.
type: docs
weight: 47
url: /it/java/com.aspose.drawing/stringformat/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public final class StringFormat implements System.IDisposable
```

Incapsula le informazioni di layout del testo (come allineamento, orientamento e tabulazioni), le manipolazioni di visualizzazione (come l'inserimento di ellissi e la sostituzione di cifre nazionali) e le funzionalità OpenType. Questa classe non può essere ereditata.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [StringFormat()](#StringFormat--) | Inizializza una nuova istanza della classe [StringFormat](../../com.aspose.drawing/stringformat). |
| [StringFormat(StringFormat format)](#StringFormat-com.aspose.drawing.StringFormat-) | Inizializza una nuova istanza della classe [StringFormat](../../com.aspose.drawing/stringformat) a partire dall'oggetto [StringFormat](../../com.aspose.drawing/stringformat) esistente specificato. |
| [StringFormat(int options, int language)](#StringFormat-int-int-) | Inizializza una nuova istanza della classe [StringFormat](../../com.aspose.drawing/stringformat) con l'enumerazione [StringFormatFlags](../../com.aspose.drawing/stringformatflags) specificata e la lingua. |
| [StringFormat(int options)](#StringFormat-int-) | Inizializza una nuova istanza della classe [StringFormat](../../com.aspose.drawing/stringformat) con l'enumerazione [StringFormatFlags](../../com.aspose.drawing/stringformatflags) specificata. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [setDigitSubstitutionLanguage(int value)](#setDigitSubstitutionLanguage-int-) |  |
| [setDigitSubstitutionMethod(int value)](#setDigitSubstitutionMethod-int-) |  |
| [getFirstTabOffset()](#getFirstTabOffset--) |  |
| [getGenericDefault()](#getGenericDefault--) | Ottiene un oggetto [StringFormat](../../com.aspose.drawing/stringformat) predefinito generico. |
| [getGenericTypographic()](#getGenericTypographic--) | Ottiene un oggetto [StringFormat](../../com.aspose.drawing/stringformat) tipografico generico. |
| [getFormatFlags()](#getFormatFlags--) | Ottiene o imposta un'enumerazione [StringFormatFlags](../../com.aspose.drawing/stringformatflags) che contiene informazioni di formattazione. |
| [setFormatFlags(int value)](#setFormatFlags-int-) | Ottiene o imposta un'enumerazione [StringFormatFlags](../../com.aspose.drawing/stringformatflags) che contiene informazioni di formattazione. |
| [getAlignment()](#getAlignment--) | Ottiene o imposta le informazioni di allineamento del testo sul piano verticale. |
| [setAlignment(int value)](#setAlignment-int-) | Ottiene o imposta le informazioni di allineamento del testo sul piano verticale. |
| [getLineAlignment()](#getLineAlignment--) | Ottiene o imposta l'allineamento della linea sul piano orizzontale. |
| [setLineAlignment(int value)](#setLineAlignment-int-) | Ottiene o imposta l'allineamento della linea sul piano orizzontale. |
| [getHotkeyPrefix()](#getHotkeyPrefix--) | Ottiene o imposta l'oggetto `HotkeyPrefix`([.getHotkeyPrefix](../../null/\#getHotkeyPrefix)/[.setHotkeyPrefix(int)](../../null/\#setHotkeyPrefix-int-)) per questo oggetto [StringFormat](../../com.aspose.drawing/stringformat). |
| [setHotkeyPrefix(int value)](#setHotkeyPrefix-int-) | Ottiene o imposta l'oggetto `HotkeyPrefix`([.getHotkeyPrefix](../../null/\#getHotkeyPrefix)/[.setHotkeyPrefix(int)](../../null/\#setHotkeyPrefix-int-)) per questo oggetto [StringFormat](../../com.aspose.drawing/stringformat). |
| [getTrimming()](#getTrimming--) | Ottiene o imposta l'enumerazione [StringTrimming](../../com.aspose.drawing/stringtrimming) per questo oggetto [StringFormat](../../com.aspose.drawing/stringformat). |
| [setTrimming(int value)](#setTrimming-int-) | Ottiene o imposta l'enumerazione [StringTrimming](../../com.aspose.drawing/stringtrimming) per questo oggetto [StringFormat](../../com.aspose.drawing/stringformat). |
| [getDigitSubstitutionLanguage()](#getDigitSubstitutionLanguage--) | Ottiene la lingua utilizzata quando le cifre locali sono sostituite con cifre occidentali. |
| [getDigitSubstitutionMethod()](#getDigitSubstitutionMethod--) | Ottiene il metodo da utilizzare per la sostituzione delle cifre. |
| [dispose()](#dispose--) | Rilascia tutte le risorse utilizzate da questo oggetto [StringFormat](../../com.aspose.drawing/stringformat). |
| [deepClone()](#deepClone--) | Crea una copia esatta di questo oggetto [StringFormat](../../com.aspose.drawing/stringformat). |
| [getTabStops(float[] firstTabOffset)](#getTabStops-float---) | Ottiene le tabulazioni per questo oggetto [StringFormat](../../com.aspose.drawing/stringformat). |
| [getTabStops()](#getTabStops--) | Ottiene un array di distanze tra le tabulazioni nelle unità specificate dalla proprietà `Aspose.Imaging.getGraphics().PageUnit`. |
| [setTabStops(float firstTabOffset, float[] tabStops)](#setTabStops-float-float---) | Imposta le tabulazioni per questo oggetto [StringFormat](../../com.aspose.drawing/stringformat). |
| [setDigitSubstitution(int language, int substitute)](#setDigitSubstitution-int-int-) | Specifica la lingua e il metodo da utilizzare quando le cifre locali sono sostituite con cifre occidentali. |
| [setMeasurableCharacterRanges(CharacterRange[] ranges)](#setMeasurableCharacterRanges-com.aspose.drawing.CharacterRange---) | Specifica un array di strutture [CharacterRange](../../com.aspose.drawing/characterrange) che rappresentano gli intervalli di caratteri misurati da una chiamata al metodo `MeasureCharacterRanges`. |
### StringFormat() {#StringFormat--}
```
public StringFormat()
```


Inizializza una nuova istanza della classe [StringFormat](../../com.aspose.drawing/stringformat).

### StringFormat(StringFormat format) {#StringFormat-com.aspose.drawing.StringFormat-}
```
public StringFormat(StringFormat format)
```


Inizializza una nuova istanza della classe [StringFormat](../../com.aspose.drawing/stringformat) a partire dall'oggetto [StringFormat](../../com.aspose.drawing/stringformat) esistente specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| format | [StringFormat](../../com.aspose.drawing/stringformat) | L'oggetto [StringFormat](../../com.aspose.drawing/stringformat) da cui inizializzare il nuovo oggetto [StringFormat](../../com.aspose.drawing/stringformat). |

### StringFormat(int options, int language) {#StringFormat-int-int-}
```
public StringFormat(int options, int language)
```


Inizializza una nuova istanza della classe [StringFormat](../../com.aspose.drawing/stringformat) con l'enumerazione [StringFormatFlags](../../com.aspose.drawing/stringformatflags) specificata e la lingua.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| options | int | L'enumerazione [StringFormatFlags](../../com.aspose.drawing/stringformatflags) per il nuovo oggetto [StringFormat](../../com.aspose.drawing/stringformat). |
| lingua | int | Un valore che indica la lingua del testo. |

### StringFormat(int options) {#StringFormat-int-}
```
public StringFormat(int options)
```


Inizializza una nuova istanza della classe [StringFormat](../../com.aspose.drawing/stringformat) con l'enumerazione [StringFormatFlags](../../com.aspose.drawing/stringformatflags) specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| options | int | L'enumerazione [StringFormatFlags](../../com.aspose.drawing/stringformatflags) per il nuovo oggetto [StringFormat](../../com.aspose.drawing/stringformat). |

### setDigitSubstitutionLanguage(int value) {#setDigitSubstitutionLanguage-int-}
```
public void setDigitSubstitutionLanguage(int value)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### setDigitSubstitutionMethod(int value) {#setDigitSubstitutionMethod-int-}
```
public void setDigitSubstitutionMethod(int value)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
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


Ottiene un oggetto [StringFormat](../../com.aspose.drawing/stringformat) predefinito generico.

**Returns:**
[StringFormat](../../com.aspose.drawing/stringformat)
### getGenericTypographic() {#getGenericTypographic--}
```
public static StringFormat getGenericTypographic()
```


Ottiene un oggetto [StringFormat](../../com.aspose.drawing/stringformat) tipografico generico.

**Returns:**
[StringFormat](../../com.aspose.drawing/stringformat) - A generic typographic [StringFormat](../../com.aspose.drawing/stringformat) object.
### getFormatFlags() {#getFormatFlags--}
```
public int getFormatFlags()
```


Ottiene o imposta un'enumerazione [StringFormatFlags](../../com.aspose.drawing/stringformatflags) che contiene informazioni di formattazione.

**Returns:**
int
### setFormatFlags(int value) {#setFormatFlags-int-}
```
public void setFormatFlags(int value)
```


Ottiene o imposta un'enumerazione [StringFormatFlags](../../com.aspose.drawing/stringformatflags) che contiene informazioni di formattazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getAlignment() {#getAlignment--}
```
public int getAlignment()
```


Ottiene o imposta le informazioni di allineamento del testo sul piano verticale.

**Returns:**
int
### setAlignment(int value) {#setAlignment-int-}
```
public void setAlignment(int value)
```


Ottiene o imposta le informazioni di allineamento del testo sul piano verticale.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getLineAlignment() {#getLineAlignment--}
```
public int getLineAlignment()
```


Ottiene o imposta l'allineamento della linea sul piano orizzontale.

**Returns:**
int
### setLineAlignment(int value) {#setLineAlignment-int-}
```
public void setLineAlignment(int value)
```


Ottiene o imposta l'allineamento della linea sul piano orizzontale.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getHotkeyPrefix() {#getHotkeyPrefix--}
```
public int getHotkeyPrefix()
```


Ottiene o imposta l'oggetto `HotkeyPrefix`([.getHotkeyPrefix](../../null/\#getHotkeyPrefix)/[.setHotkeyPrefix(int)](../../null/\#setHotkeyPrefix-int-)) per questo oggetto [StringFormat](../../com.aspose.drawing/stringformat).

**Returns:**
int
### setHotkeyPrefix(int value) {#setHotkeyPrefix-int-}
```
public void setHotkeyPrefix(int value)
```


Ottiene o imposta l'oggetto `HotkeyPrefix`([.getHotkeyPrefix](../../null/\#getHotkeyPrefix)/[.setHotkeyPrefix(int)](../../null/\#setHotkeyPrefix-int-)) per questo oggetto [StringFormat](../../com.aspose.drawing/stringformat).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getTrimming() {#getTrimming--}
```
public int getTrimming()
```


Ottiene o imposta l'enumerazione [StringTrimming](../../com.aspose.drawing/stringtrimming) per questo oggetto [StringFormat](../../com.aspose.drawing/stringformat).

**Returns:**
int
### setTrimming(int value) {#setTrimming-int-}
```
public void setTrimming(int value)
```


Ottiene o imposta l'enumerazione [StringTrimming](../../com.aspose.drawing/stringtrimming) per questo oggetto [StringFormat](../../com.aspose.drawing/stringformat).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getDigitSubstitutionLanguage() {#getDigitSubstitutionLanguage--}
```
public int getDigitSubstitutionLanguage()
```


Ottiene la lingua utilizzata quando le cifre locali sono sostituite con cifre occidentali.

**Returns:**
int - Un identificatore di lingua del National Language Support (NLS) che identifica la lingua da utilizzare quando le cifre locali vengono sostituite con cifre occidentali. È possibile passare la proprietà `System.Globalization.CultureInfo.LCID` di un oggetto java.util.Locale come identificatore di lingua NLS. Per esempio, supponiamo di creare un oggetto java.util.Locale passando la stringa \"ar-EG\" al costruttore java.util.Locale. Se si passa la proprietà `System.Globalization.CultureInfo.LCID` di quell'oggetto java.util.Locale insieme a `StringDigitSubstitute.Traditional` al metodo [.setDigitSubstitution(int,int)](../../null/\\#setDigitSubstitution-int-int-), allora le cifre arabo-indiane saranno sostituite alle cifre occidentali al momento della visualizzazione.
### getDigitSubstitutionMethod() {#getDigitSubstitutionMethod--}
```
public int getDigitSubstitutionMethod()
```


Ottiene il metodo da utilizzare per la sostituzione delle cifre.

**Returns:**
int - Un valore di enumerazione [StringDigitSubstitute](../../com.aspose.drawing/stringdigitsubstitute) che specifica come sostituire i caratteri in una stringa che non possono essere visualizzati perché non supportati dal font corrente.
### dispose() {#dispose--}
```
public void dispose()
```


Rilascia tutte le risorse utilizzate da questo oggetto [StringFormat](../../com.aspose.drawing/stringformat).

### deepClone() {#deepClone--}
```
public StringFormat deepClone()
```


Crea una copia esatta di questo oggetto [StringFormat](../../com.aspose.drawing/stringformat).

**Returns:**
[StringFormat](../../com.aspose.drawing/stringformat) - The [StringFormat](../../com.aspose.drawing/stringformat) object this method creates.
### getTabStops(float[] firstTabOffset) {#getTabStops-float---}
```
public float[] getTabStops(float[] firstTabOffset)
```


Ottiene le tabulazioni per questo oggetto [StringFormat](../../com.aspose.drawing/stringformat).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| firstTabOffset | float[] | Il numero di spazi tra l'inizio di una riga di testo e la prima tabulazione. |

**Returns:**
float[] - Un array di distanze (in numero di spazi) tra le tabulazioni.
### getTabStops() {#getTabStops--}
```
public float[] getTabStops()
```


Ottiene un array di distanze tra le tabulazioni nelle unità specificate dalla proprietà `Aspose.Imaging.getGraphics().PageUnit`.

**Returns:**
float[] - Le tabulazioni.

La proprietà è introdotta per il metodo rimosso GetTabStops.
### setTabStops(float firstTabOffset, float[] tabStops) {#setTabStops-float-float---}
```
public void setTabStops(float firstTabOffset, float[] tabStops)
```


Imposta le tabulazioni per questo oggetto [StringFormat](../../com.aspose.drawing/stringformat).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| firstTabOffset | float | Il numero di spazi tra l'inizio di una riga di testo e la prima tabulazione. |
| tabStops | float[] | Un array di distanze tra le tabulazioni nelle unità specificate dalla proprietà Graphics.PageUnit. |

### setDigitSubstitution(int language, int substitute) {#setDigitSubstitution-int-int-}
```
public void setDigitSubstitution(int language, int substitute)
```


Specifica la lingua e il metodo da utilizzare quando le cifre locali sono sostituite con cifre occidentali.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| lingua | int | Un identificatore di lingua del National Language Support (NLS) che identifica la lingua da utilizzare quando le cifre locali vengono sostituite con cifre occidentali. È possibile passare la proprietà `System.Globalization.CultureInfo.LCID` di un oggetto java.util.Locale come identificatore di lingua NLS. Per esempio, supponiamo di creare un oggetto java.util.Locale passando la stringa \"ar-EG\" al costruttore java.util.Locale. Se si passa la proprietà `System.Globalization.CultureInfo.LCID` di quell'oggetto java.util.Locale insieme a `StringDigitSubstitute.Traditional` al metodo `M:StringFormat.SetDigitSubstitution(System.Int32,StringDigitSubstitute)`, allora le cifre arabo-indiane saranno sostituite alle cifre occidentali al momento della visualizzazione. |
| substitute | int | Un elemento dell'enumerazione [StringDigitSubstitute](../../com.aspose.drawing/stringdigitsubstitute) che specifica come vengono visualizzate le cifre. |

### setMeasurableCharacterRanges(CharacterRange[] ranges) {#setMeasurableCharacterRanges-com.aspose.drawing.CharacterRange---}
```
public void setMeasurableCharacterRanges(CharacterRange[] ranges)
```


Specifica un array di strutture [CharacterRange](../../com.aspose.drawing/characterrange) che rappresentano gli intervalli di caratteri misurati da una chiamata al metodo `MeasureCharacterRanges`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| ranges | [CharacterRange\[\]](../../com.aspose.drawing/characterrange) | Un array di strutture [CharacterRange](../../com.aspose.drawing/characterrange) che specificano gli intervalli di caratteri misurati da una chiamata al metodo `MeasureCharacterRanges`. |

