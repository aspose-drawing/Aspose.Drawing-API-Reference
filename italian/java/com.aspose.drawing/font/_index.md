---
title: Font
second_title: Riferimento API di Aspose.Drawing per Java
description: Definisce un formato particolare per il testo includendo la famiglia, la dimensione e gli attributi di stile del carattere.
type: docs
weight: 21
url: /it/java/com.aspose.drawing/font/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public final class Font implements System.IDisposable
```

Definisce un formato particolare per il testo, includendo la famiglia, la dimensione e gli attributi di stile del carattere. Questa classe non può essere ereditata.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Font(Font prototype, int newStyle)](#Font-com.aspose.drawing.Font-int-) | Inizializza una nuova istanza della classe [Font](../../com.aspose.drawing/font) utilizzando il [Font](../../com.aspose.drawing/font) e l'enumerazione [FontStyle](../../com.aspose.drawing/fontstyle) specificati. |
| [Font(FontFamily family, float emSize)](#Font-com.aspose.drawing.FontFamily-float-) | Inizializza una nuova istanza della classe [Font](../../com.aspose.drawing/font). |
| [Font(FontFamily family, float emSize, int style)](#Font-com.aspose.drawing.FontFamily-float-int-) | Inizializza una nuova istanza della classe [Font](../../com.aspose.drawing/font) utilizzando una dimensione e uno stile specificati.. |
| [Font(FontFamily family, float emSize, int style, int unit)](#Font-com.aspose.drawing.FontFamily-float-int-int-) | Inizializza una nuova istanza della classe [Font](../../com.aspose.drawing/font) utilizzando una dimensione, uno stile e un'unità specificati. |
| [Font(FontFamily family, float emSize, int style, int unit, byte gdiCharSet)](#Font-com.aspose.drawing.FontFamily-float-int-int-byte-) | Inizializza una nuova istanza della classe [Font](../../com.aspose.drawing/font) utilizzando una dimensione, uno stile, un'unità e un set di caratteri specificati.. |
| [Font(FontFamily family, float emSize, int style, int unit, byte gdiCharSet, boolean gdiVerticalFont)](#Font-com.aspose.drawing.FontFamily-float-int-int-byte-boolean-) | Inizializza una nuova istanza della classe [Font](../../com.aspose.drawing/font) utilizzando una dimensione, uno stile, un'unità e un set di caratteri specificati.. |
| [Font(String familyName, float emSize)](#Font-java.lang.String-float-) | Inizializza una nuova istanza della classe [Font](../../com.aspose.drawing/font) utilizzando una dimensione specificata. |
| [Font(String familyName, float emSize, int style)](#Font-java.lang.String-float-int-) | Inizializza una nuova istanza della classe [Font](../../com.aspose.drawing/font) utilizzando una dimensione e uno stile specificati. |
| [Font(String familyName, float emSize, int style, int unit)](#Font-java.lang.String-float-int-int-) | Inizializza una nuova istanza della classe [Font](../../com.aspose.drawing/font) utilizzando una dimensione, uno stile e un'unità specificati. |
| [Font(String familyName, float emSize, int style, int unit, byte gdiCharSet)](#Font-java.lang.String-float-int-int-byte-) | Inizializza una nuova istanza della classe [Font](../../com.aspose.drawing/font) utilizzando una dimensione, uno stile, un'unità e un set di caratteri specificati. |
| [Font(String familyName, float emSize, int style, int unit, byte gdiCharSet, boolean gdiVerticalFont)](#Font-java.lang.String-float-int-int-byte-boolean-) | Inizializza una nuova istanza della classe [Font](../../com.aspose.drawing/font) utilizzando la dimensione, lo stile, l'unità e il set di caratteri specificati. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getFontFamily()](#getFontFamily--) | Restituisce il `FontFamily`([.getFontFamily](../../null/\#getFontFamily)) associato a questo [Font](../../com.aspose.drawing/font). |
| [getBold()](#getBold--) | Restituisce un valore che indica se questo [Font](../../com.aspose.drawing/font) è in grassetto. |
| [getGdiCharSet()](#getGdiCharSet--) | Restituisce un valore byte che specifica il set di caratteri GDI utilizzato da questo [Font](../../com.aspose.drawing/font). |
| [getGdiVerticalFont()](#getGdiVerticalFont--) | Restituisce un valore che indica se questo [Font](../../com.aspose.drawing/font) è derivato da un font verticale GDI.. |
| [getItalic()](#getItalic--) | Restituisce un valore che indica se questo [Font](../../com.aspose.drawing/font) è in corsivo. |
| [getName()](#getName--) | Restituisce il nome del carattere di questo [Font](../../com.aspose.drawing/font). |
| [getStrikeout()](#getStrikeout--) | Restituisce un valore che indica se questo [Font](../../com.aspose.drawing/font) specifica una linea orizzontale attraverso il carattere. |
| [getUnderline()](#getUnderline--) | Restituisce un valore che indica se questo [Font](../../com.aspose.drawing/font) è sottolineato. |
| [getStyle()](#getStyle--) | Restituisce le informazioni di stile per questo [Font](../../com.aspose.drawing/font). |
| [getSize()](#getSize--) | Restituisce la dimensione em di questo [Font](../../com.aspose.drawing/font) misurata nelle unità specificate dalla proprietà `Font.Unit`. |
| [getSizeInPoints()](#getSizeInPoints--) | Restituisce la dimensione em, in punti, di questo [Font](../../com.aspose.drawing/font). |
| [getUnit()](#getUnit--) | Restituisce l'unità di misura per questo [Font](../../com.aspose.drawing/font). |
| [getHeight_Rename_Namesake()](#getHeight-Rename-Namesake--) | Restituisce l'interlinea di questo carattere. |
| [isSystemFont()](#isSystemFont--) | Restituisce un valore che indica se il carattere è un membro di [SystemFonts](../../com.aspose.drawing/systemfonts). |
| [getSystemFontName()](#getSystemFontName--) | Restituisce il nome del carattere di sistema se la proprietà IsSystemFont restituisce true. |
| [getOriginalFontName()](#getOriginalFontName--) | Restituisce il nome del carattere originariamente specificato. |
| [deepClone()](#deepClone--) | Crea una copia esatta di questo [Font](../../com.aspose.drawing/font). |
| [equals(Object obj)](#equals-java.lang.Object-) | Indica se l'oggetto specificato è un [Font](../../com.aspose.drawing/font) e ha gli stessi valori delle proprietà `FontFamily`([.getFontFamily](../../null/\#getFontFamily)), `M:GdiVerticalFont`, `M:GdiCharSet`, `M:Style`, `M:Size` e `M:Unit` di questo [Font](../../com.aspose.drawing/font). |
| [hashCode()](#hashCode--) | Ottiene il codice hash per questo [Font](../../com.aspose.drawing/font). |
| [getHeight()](#getHeight--) | Restituisce l'interlinea, in pixel, di questo font. |
| [getHeight(Graphics graphics)](#getHeight-com.aspose.drawing.Graphics-) | Restituisce l'interlinea, nell'unità corrente di un determinato [Graphics](../../com.aspose.drawing/graphics), di questo font. |
| [getHeight(float dpi)](#getHeight-float-) | Restituisce l'altezza, in pixel, di questo [Font](../../com.aspose.drawing/font) quando viene disegnato su un dispositivo con la risoluzione verticale specificata. |
| [dispose()](#dispose--) | Rilascia tutte le risorse utilizzate da questo [Font](../../com.aspose.drawing/font). |
| [toString()](#toString--) | Restituisce una rappresentazione stringa leggibile dall'uomo di questo [Font](../../com.aspose.drawing/font). |
| [getCharacterSet()](#getCharacterSet--) | Ottiene un valore byte che specifica il set di caratteri usato da questo `Font`. |
### Font(Font prototype, int newStyle) {#Font-com.aspose.drawing.Font-int-}
```
public Font(Font prototype, int newStyle)
```


Inizializza una nuova istanza della classe [Font](../../com.aspose.drawing/font) utilizzando il [Font](../../com.aspose.drawing/font) e l'enumerazione [FontStyle](../../com.aspose.drawing/fontstyle) specificati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| prototype | [Font](../../com.aspose.drawing/font) | Il [Font](../../com.aspose.drawing/font) esistente da cui creare il nuovo [Font](../../com.aspose.drawing/font). |
| newStyle | int | Il [FontStyle](../../com.aspose.drawing/fontstyle) da applicare al nuovo [Font](../../com.aspose.drawing/font). È possibile combinare più valori dell'enumerazione [FontStyle](../../com.aspose.drawing/fontstyle) con l'operatore OR. |

### Font(FontFamily family, float emSize) {#Font-com.aspose.drawing.FontFamily-float-}
```
public Font(FontFamily family, float emSize)
```


Inizializza una nuova istanza della classe [Font](../../com.aspose.drawing/font).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| family | [FontFamily](../../com.aspose.drawing/fontfamily) | Il `FontFamily`([.getFontFamily](../../null/\#getFontFamily)) del nuovo [Font](../../com.aspose.drawing/font). |
| emSize | float | La dimensione em, in punti, del nuovo font. |

### Font(FontFamily family, float emSize, int style) {#Font-com.aspose.drawing.FontFamily-float-int-}
```
public Font(FontFamily family, float emSize, int style)
```


Inizializza una nuova istanza della classe [Font](../../com.aspose.drawing/font) utilizzando una dimensione e uno stile specificati..

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| family | [FontFamily](../../com.aspose.drawing/fontfamily) | Il `FontFamily`([.getFontFamily](../../null/\#getFontFamily)) del nuovo [Font](../../com.aspose.drawing/font). |
| emSize | float | La dimensione em, in punti, del nuovo font. |
| style | int | Il [FontStyle](../../com.aspose.drawing/fontstyle) del nuovo font. |

### Font(FontFamily family, float emSize, int style, int unit) {#Font-com.aspose.drawing.FontFamily-float-int-int-}
```
public Font(FontFamily family, float emSize, int style, int unit)
```


Inizializza una nuova istanza della classe [Font](../../com.aspose.drawing/font) utilizzando una dimensione, uno stile e un'unità specificati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| family | [FontFamily](../../com.aspose.drawing/fontfamily) | Il `FontFamily`([.getFontFamily](../../null/\#getFontFamily)) del nuovo [Font](../../com.aspose.drawing/font). |
| emSize | float | La dimensione em del nuovo font nelle unità specificate dal parametro `unit`. |
| style | int | Il [FontStyle](../../com.aspose.drawing/fontstyle) del nuovo font. |
| unit | int | Il [GraphicsUnit](../../com.aspose.drawing/graphicsunit) del nuovo font. |

### Font(FontFamily family, float emSize, int style, int unit, byte gdiCharSet) {#Font-com.aspose.drawing.FontFamily-float-int-int-byte-}
```
public Font(FontFamily family, float emSize, int style, int unit, byte gdiCharSet)
```


Inizializza una nuova istanza della classe [Font](../../com.aspose.drawing/font) utilizzando una dimensione, uno stile, un'unità e un set di caratteri specificati..

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| family | [FontFamily](../../com.aspose.drawing/fontfamily) | Il `FontFamily`([.getFontFamily](../../null/\#getFontFamily)) del nuovo [Font](../../com.aspose.drawing/font). |
| emSize | float | La dimensione em del nuovo font nelle unità specificate dal parametro `unit`. |
| style | int | Il [FontStyle](../../com.aspose.drawing/fontstyle) del nuovo font. |
| unit | int | Il [GraphicsUnit](../../com.aspose.drawing/graphicsunit) del nuovo font. |
| gdiCharSet | byte | Set di caratteri GDI da utilizzare per il nuovo font. |

### Font(FontFamily family, float emSize, int style, int unit, byte gdiCharSet, boolean gdiVerticalFont) {#Font-com.aspose.drawing.FontFamily-float-int-int-byte-boolean-}
```
public Font(FontFamily family, float emSize, int style, int unit, byte gdiCharSet, boolean gdiVerticalFont)
```


Inizializza una nuova istanza della classe [Font](../../com.aspose.drawing/font) utilizzando una dimensione, uno stile, un'unità e un set di caratteri specificati..

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| family | [FontFamily](../../com.aspose.drawing/fontfamily) | Il `FontFamily`([.getFontFamily](../../null/\#getFontFamily)) del nuovo [Font](../../com.aspose.drawing/font). |
| emSize | float | La dimensione em del nuovo font nelle unità specificate dal parametro `unit`. |
| style | int | Il [FontStyle](../../com.aspose.drawing/fontstyle) del nuovo font. |
| unit | int | Il [GraphicsUnit](../../com.aspose.drawing/graphicsunit) del nuovo font. |
| gdiCharSet | byte | Set di caratteri GDI da utilizzare per il nuovo font. |
| gdiVerticalFont | boolean | Un valore Booleano che indica se il nuovo font è derivato da un font verticale GDI. |

### Font(String familyName, float emSize) {#Font-java.lang.String-float-}
```
public Font(String familyName, float emSize)
```


Inizializza una nuova istanza della classe [Font](../../com.aspose.drawing/font) utilizzando una dimensione specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| familyName | java.lang.String | Una rappresentazione stringa del FontFamily per il nuovo [Font](../../com.aspose.drawing/font). |
| emSize | float | La dimensione em, in punti, del nuovo font. |

### Font(String familyName, float emSize, int style) {#Font-java.lang.String-float-int-}
```
public Font(String familyName, float emSize, int style)
```


Inizializza una nuova istanza della classe [Font](../../com.aspose.drawing/font) utilizzando una dimensione e uno stile specificati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| familyName | java.lang.String | Una rappresentazione stringa del FontFamily per il nuovo [Font](../../com.aspose.drawing/font). |
| emSize | float | La dimensione em, in punti, del nuovo font. |
| style | int | Il [FontStyle](../../com.aspose.drawing/fontstyle) del nuovo font. |

### Font(String familyName, float emSize, int style, int unit) {#Font-java.lang.String-float-int-int-}
```
public Font(String familyName, float emSize, int style, int unit)
```


Inizializza una nuova istanza della classe [Font](../../com.aspose.drawing/font) utilizzando una dimensione, uno stile e un'unità specificati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| familyName | java.lang.String | Una rappresentazione stringa del `FontFamily`([.getFontFamily](../../null/\#getFontFamily)) per il nuovo [Font](../../com.aspose.drawing/font). |
| emSize | float | La dimensione em del nuovo font nelle unità specificate dal parametro `unit`. |
| style | int | Il [FontStyle](../../com.aspose.drawing/fontstyle) del nuovo font. |
| unit | int | Il [GraphicsUnit](../../com.aspose.drawing/graphicsunit) del nuovo font. |

### Font(String familyName, float emSize, int style, int unit, byte gdiCharSet) {#Font-java.lang.String-float-int-int-byte-}
```
public Font(String familyName, float emSize, int style, int unit, byte gdiCharSet)
```


Inizializza una nuova istanza della classe [Font](../../com.aspose.drawing/font) utilizzando una dimensione, uno stile, un'unità e un set di caratteri specificati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| familyName | java.lang.String | Una rappresentazione stringa del FontFamily per il nuovo [Font](../../com.aspose.drawing/font). |
| emSize | float | La dimensione em del nuovo font nelle unità specificate dal parametro `unit`. |
| style | int | Il [FontStyle](../../com.aspose.drawing/fontstyle) del nuovo font. |
| unit | int | Il [GraphicsUnit](../../com.aspose.drawing/graphicsunit) del nuovo font. |
| gdiCharSet | byte | Un byte che specifica un set di caratteri GDI da utilizzare per questo font. |

### Font(String familyName, float emSize, int style, int unit, byte gdiCharSet, boolean gdiVerticalFont) {#Font-java.lang.String-float-int-int-byte-boolean-}
```
public Font(String familyName, float emSize, int style, int unit, byte gdiCharSet, boolean gdiVerticalFont)
```


Inizializza una nuova istanza della classe [Font](../../com.aspose.drawing/font) utilizzando la dimensione, lo stile, l'unità e il set di caratteri specificati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| familyName | java.lang.String | Una rappresentazione stringa del FontFamily per il nuovo [Font](../../com.aspose.drawing/font). |
| emSize | float | La dimensione em del nuovo font nelle unità specificate dal parametro `unit`. |
| style | int | Il [FontStyle](../../com.aspose.drawing/fontstyle) del nuovo font. |
| unit | int | Il [GraphicsUnit](../../com.aspose.drawing/graphicsunit) del nuovo font. |
| gdiCharSet | byte | Un byte che specifica un set di caratteri GDI da utilizzare per questo font. |
| gdiVerticalFont | boolean | Un valore Booleano che indica se il nuovo [Font](../../com.aspose.drawing/font) è derivato da un font verticale GDI. |

### getFontFamily() {#getFontFamily--}
```
public FontFamily getFontFamily()
```


Restituisce il `FontFamily`([.getFontFamily](../../null/\#getFontFamily)) associato a questo [Font](../../com.aspose.drawing/font).

**Returns:**
[FontFamily](../../com.aspose.drawing/fontfamily) - The `FontFamily`([.getFontFamily](../../null/\#getFontFamily)) associated with this [Font](../../com.aspose.drawing/font).
### getBold() {#getBold--}
```
public boolean getBold()
```


Restituisce un valore che indica se questo [Font](../../com.aspose.drawing/font) è in grassetto.

**Returns:**
boolean - un valore che indica se questo [Font](../../com.aspose.drawing/font) è grassetto.
### getGdiCharSet() {#getGdiCharSet--}
```
public byte getGdiCharSet()
```


Restituisce un valore byte che specifica il set di caratteri GDI utilizzato da questo [Font](../../com.aspose.drawing/font).

**Returns:**
byte - Un valore byte che specifica il set di caratteri GDI utilizzato da questo [Font](../../com.aspose.drawing/font).
### getGdiVerticalFont() {#getGdiVerticalFont--}
```
public boolean getGdiVerticalFont()
```


Restituisce un valore che indica se questo [Font](../../com.aspose.drawing/font) è derivato da un font verticale GDI..

Valore: `true` se questo [Font](../../com.aspose.drawing/font) è derivato da un font verticale GDI; altrimenti, `false`.

**Returns:**
boolean - un valore che indica se questo [Font](../../com.aspose.drawing/font) è derivato da un font verticale GDI.
### getItalic() {#getItalic--}
```
public boolean getItalic()
```


Restituisce un valore che indica se questo [Font](../../com.aspose.drawing/font) è in corsivo.

**Returns:**
boolean - un valore che indica se questo [Font](../../com.aspose.drawing/font) è corsivo.
### getName() {#getName--}
```
public String getName()
```


Restituisce il nome del carattere di questo [Font](../../com.aspose.drawing/font).

**Returns:**
java.lang.String - il nome del tipo di carattere di questo [Font](../../com.aspose.drawing/font).
### getStrikeout() {#getStrikeout--}
```
public boolean getStrikeout()
```


Restituisce un valore che indica se questo [Font](../../com.aspose.drawing/font) specifica una linea orizzontale attraverso il carattere.

**Returns:**
boolean - un valore che indica se questo [Font](../../com.aspose.drawing/font) specifica una linea orizzontale attraverso il carattere.
### getUnderline() {#getUnderline--}
```
public boolean getUnderline()
```


Restituisce un valore che indica se questo [Font](../../com.aspose.drawing/font) è sottolineato.

**Returns:**
boolean - un valore che indica se questo [Font](../../com.aspose.drawing/font) è sottolineato.
### getStyle() {#getStyle--}
```
public int getStyle()
```


Restituisce le informazioni di stile per questo [Font](../../com.aspose.drawing/font).

**Returns:**
int - informazioni sullo stile per questo [Font](../../com.aspose.drawing/font).
### getSize() {#getSize--}
```
public float getSize()
```


Restituisce la dimensione em di questo [Font](../../com.aspose.drawing/font) misurata nelle unità specificate dalla proprietà `Font.Unit`.

**Returns:**
float - la dimensione em di questo [Font](../../com.aspose.drawing/font) misurata nelle unità specificate da \{@code Font.
### getSizeInPoints() {#getSizeInPoints--}
```
public float getSizeInPoints()
```


Restituisce la dimensione em, in punti, di questo [Font](../../com.aspose.drawing/font).

**Returns:**
float - La dimensione em, in punti, di questo [Font](../../com.aspose.drawing/font).
### getUnit() {#getUnit--}
```
public int getUnit()
```


Restituisce l'unità di misura per questo [Font](../../com.aspose.drawing/font).

**Returns:**
int - l'unità di misura per questo [Font](../../com.aspose.drawing/font).
### getHeight_Rename_Namesake() {#getHeight-Rename-Namesake--}
```
public int getHeight_Rename_Namesake()
```


Restituisce l'interlinea di questo carattere.

Valore: l'interlinea, in pixel, di questo font.

**Returns:**
int - l'interlinea di questo font.
### isSystemFont() {#isSystemFont--}
```
public boolean isSystemFont()
```


Restituisce un valore che indica se il carattere è un membro di [SystemFonts](../../com.aspose.drawing/systemfonts).

Valore: `true` se il font è un membro di [SystemFonts](../../com.aspose.drawing/systemfonts); altrimenti, `false`.

**Returns:**
boolean - un valore che indica se il font è un membro di [SystemFonts](../../com.aspose.drawing/systemfonts).
### getSystemFontName() {#getSystemFontName--}
```
public String getSystemFontName()
```


Restituisce il nome del carattere di sistema se la proprietà IsSystemFont restituisce true.

Valore: il nome del font di sistema, se IsSystemFont restituisce true; altrimenti, una stringa vuota ("").

**Returns:**
java.lang.String - il nome del font di sistema se la proprietà IsSystemFont restituisce true.
### getOriginalFontName() {#getOriginalFontName--}
```
public String getOriginalFontName()
```


Restituisce il nome del carattere originariamente specificato.

Valore: la stringa che rappresenta il nome del font specificato originariamente.

**Returns:**
java.lang.String - il nome del font specificato originariamente.
### deepClone() {#deepClone--}
```
public Font deepClone()
```


Crea una copia esatta di questo [Font](../../com.aspose.drawing/font).

**Returns:**
[Font](../../com.aspose.drawing/font) - The [Font](../../com.aspose.drawing/font) this method creates, cast as an Object.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Indica se l'oggetto specificato è un [Font](../../com.aspose.drawing/font) e ha gli stessi valori delle proprietà `FontFamily`([.getFontFamily](../../null/\#getFontFamily)), `M:GdiVerticalFont`, `M:GdiCharSet`, `M:Style`, `M:Size` e `M:Unit` di questo [Font](../../com.aspose.drawing/font).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | java.lang.Object | L'oggetto da testare. |

**Returns:**
boolean - `true` se il parametro obj è un [Font](../../com.aspose.drawing/font) e ha gli stessi valori delle proprietà `FontFamily`([.getFontFamily](../../null/\#getFontFamily)), `M:GdiVerticalFont`, `M:GdiCharSet`, `M:Style`, `M:Size` e `M:Unit` di questo [Font](../../com.aspose.drawing/font); altrimenti, `false`.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Ottiene il codice hash per questo [Font](../../com.aspose.drawing/font).

**Returns:**
int - Il codice hash per questo [Font](../../com.aspose.drawing/font).
### getHeight() {#getHeight--}
```
public int getHeight()
```


Restituisce l'interlinea, in pixel, di questo font.

**Returns:**
int - L'interlinea, in pixel, di questo font.
### getHeight(Graphics graphics) {#getHeight-com.aspose.drawing.Graphics-}
```
public float getHeight(Graphics graphics)
```


Restituisce l'interlinea, nell'unità corrente di un determinato [Graphics](../../com.aspose.drawing/graphics), di questo font.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| graphics | [Graphics](../../com.aspose.drawing/graphics) | Un [Graphics](../../com.aspose.drawing/graphics) che contiene la risoluzione verticale, in punti per pollice, del dispositivo di visualizzazione così come le impostazioni per l'unità di pagina e la scala della pagina. |

**Returns:**
float - L'interlinea, in pixel, di questo font.
### getHeight(float dpi) {#getHeight-float-}
```
public int getHeight(float dpi)
```


Restituisce l'altezza, in pixel, di questo [Font](../../com.aspose.drawing/font) quando viene disegnato su un dispositivo con la risoluzione verticale specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dpi | float | La risoluzione verticale, in punti per pollice, utilizzata per calcolare l'altezza del carattere. |

**Returns:**
int - L'altezza, in pixel, di questo [Font](../../com.aspose.drawing/font).
### dispose() {#dispose--}
```
public void dispose()
```


Rilascia tutte le risorse utilizzate da questo [Font](../../com.aspose.drawing/font).

### toString() {#toString--}
```
public String toString()
```


Restituisce una rappresentazione stringa leggibile dall'uomo di questo [Font](../../com.aspose.drawing/font).

**Returns:**
java.lang.String - Una stringa che rappresenta questo [Font](../../com.aspose.drawing/font).
### getCharacterSet() {#getCharacterSet--}
```
public int getCharacterSet()
```


Ottiene un valore byte che specifica il set di caratteri usato da questo `Font`.

**Returns:**
int - Un set di caratteri che questo `Font` utilizza.
