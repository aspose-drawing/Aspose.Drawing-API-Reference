---
title: FontFamily
second_title: Riferimento API di Aspose.Drawing per Java
description: Definisce un gruppo di tipi di carattere con un design di base simile e alcune variazioni di stile.
type: docs
weight: 24
url: /it/java/com.aspose.drawing/fontfamily/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public final class FontFamily implements System.IDisposable
```

Definisce un gruppo di caratteri tipografici con un design di base simile e alcune variazioni di stile. Questa classe non può essere ereditata.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [FontFamily(String name)](#FontFamily-java.lang.String-) | Inizializza una nuova istanza della classe [FontFamily](../../com.aspose.drawing/fontfamily) con il nome specificato. |
| [FontFamily(String name, FontCollection fontCollection)](#FontFamily-java.lang.String-com.aspose.drawing.FontCollection-) | Inizializza una nuova istanza della classe [FontFamily](../../com.aspose.drawing/fontfamily). |
| [FontFamily(String name, FontFamilyDefinition definition)](#FontFamily-java.lang.String-com.aspose.drawing.FontFamilyDefinition-) | Inizializza una nuova istanza della classe [FontFamily](../../com.aspose.drawing/fontfamily). |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getFamilies()](#getFamilies--) | Restituisce un array che contiene tutti gli oggetti [FontFamily](../../com.aspose.drawing/fontfamily) associati al contesto grafico corrente. |
| [getGenericSansSerif()](#getGenericSansSerif--) | Restituisce un oggetto generico sans serif [FontFamily](../../com.aspose.drawing/fontfamily). |
| [getGenericSerif()](#getGenericSerif--) | Restituisce un oggetto generico serif [FontFamily](../../com.aspose.drawing/fontfamily). |
| [getGenericMonospace()](#getGenericMonospace--) | Restituisce un oggetto generico monospazio [FontFamily](../../com.aspose.drawing/fontfamily). |
| [getName()](#getName--) | Restituisce il nome di questo [FontFamily](../../com.aspose.drawing/fontfamily). |
| [dispose()](#dispose--) | Rilascia tutte le risorse utilizzate da questo [FontFamily](../../com.aspose.drawing/fontfamily). |
| [getName(int language)](#getName-int-) | Restituisce il nome, nella lingua specificata, di questo [FontFamily](../../com.aspose.drawing/fontfamily). |
| [isStyleAvailable(int style)](#isStyleAvailable-int-) | Indica se l'enumerazione [FontStyle](../../com.aspose.drawing/fontstyle) specificata è disponibile. |
| [getEmHeight(int style)](#getEmHeight-int-) | Ottiene l'altezza, in unità di progettazione del carattere, del quadrato EM per lo stile specificato. |
| [getCellAscent(int style)](#getCellAscent-int-) | Restituisce l'ascesa della cella, in unità di progettazione, della [FontFamily](../../com.aspose.drawing/fontfamily) dello stile specificato. |
| [getCellDescent(int style)](#getCellDescent-int-) | Restituisce la discesa della cella, in unità di progettazione, della [FontFamily](../../com.aspose.drawing/fontfamily) dello stile specificato. |
| [hashCode()](#hashCode--) | Ottiene un codice hash per questa [FontFamily](../../com.aspose.drawing/fontfamily). |
| [equals(Object obj)](#equals-java.lang.Object-) | Indica se l'oggetto specificato è una [FontFamily](../../com.aspose.drawing/fontfamily) ed è identico a questa [FontFamily](../../com.aspose.drawing/fontfamily). |
| [getLineSpacing(int style)](#getLineSpacing-int-) | Restituisce l'interlinea, in unità di progettazione, della [FontFamily](../../com.aspose.drawing/fontfamily) dello stile specificato. |
### FontFamily(String name) {#FontFamily-java.lang.String-}
```
public FontFamily(String name)
```


Inizializza una nuova istanza della classe [FontFamily](../../com.aspose.drawing/fontfamily) con il nome specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | java.lang.String | Il nome della nuova [FontFamily](../../com.aspose.drawing/fontfamily). |

### FontFamily(String name, FontCollection fontCollection) {#FontFamily-java.lang.String-com.aspose.drawing.FontCollection-}
```
public FontFamily(String name, FontCollection fontCollection)
```


Inizializza una nuova istanza della classe [FontFamily](../../com.aspose.drawing/fontfamily).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| nome | java.lang.String | Il nome della famiglia di caratteri. |
| fontCollection | [FontCollection](../../com.aspose.drawing/fontcollection) | La raccolta di caratteri. |

### FontFamily(String name, FontFamilyDefinition definition) {#FontFamily-java.lang.String-com.aspose.drawing.FontFamilyDefinition-}
```
public FontFamily(String name, FontFamilyDefinition definition)
```


Inizializza una nuova istanza della classe [FontFamily](../../com.aspose.drawing/fontfamily).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| nome | java.lang.String | Il nome della famiglia di caratteri. |
| definition | [FontFamilyDefinition](../../com.aspose.drawing/fontfamilydefinition) | La definizione. |

### getFamilies() {#getFamilies--}
```
public static FontFamily[] getFamilies()
```


Restituisce un array che contiene tutti gli oggetti [FontFamily](../../com.aspose.drawing/fontfamily) associati al contesto grafico corrente.

**Returns:**
com.aspose.drawing.FontFamily[] - Un array di oggetti [FontFamily](../../com.aspose.drawing/fontfamily) associati al contesto grafico corrente.
### getGenericSansSerif() {#getGenericSansSerif--}
```
public static FontFamily getGenericSansSerif()
```


Restituisce un oggetto generico sans serif [FontFamily](../../com.aspose.drawing/fontfamily).

**Returns:**
[FontFamily](../../com.aspose.drawing/fontfamily) - A [FontFamily](../../com.aspose.drawing/fontfamily) object that represents a generic sans serif font.
### getGenericSerif() {#getGenericSerif--}
```
public static FontFamily getGenericSerif()
```


Restituisce un oggetto generico serif [FontFamily](../../com.aspose.drawing/fontfamily).

**Returns:**
[FontFamily](../../com.aspose.drawing/fontfamily) - A [FontFamily](../../com.aspose.drawing/fontfamily) that represents a generic serif font.
### getGenericMonospace() {#getGenericMonospace--}
```
public static FontFamily getGenericMonospace()
```


Restituisce un oggetto generico monospazio [FontFamily](../../com.aspose.drawing/fontfamily).

**Returns:**
[FontFamily](../../com.aspose.drawing/fontfamily) - A [FontFamily](../../com.aspose.drawing/fontfamily) that represents a generic monospace font.
### getName() {#getName--}
```
public String getName()
```


Restituisce il nome di questo [FontFamily](../../com.aspose.drawing/fontfamily).

**Returns:**
java.lang.String - Una stringa che rappresenta il nome di questa [FontFamily](../../com.aspose.drawing/fontfamily).
### dispose() {#dispose--}
```
public void dispose()
```


Rilascia tutte le risorse utilizzate da questo [FontFamily](../../com.aspose.drawing/fontfamily).

### getName(int language) {#getName-int-}
```
public String getName(int language)
```


Restituisce il nome, nella lingua specificata, di questo [FontFamily](../../com.aspose.drawing/fontfamily).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| lingua | int | La lingua in cui viene restituito il nome. |

**Returns:**
java.lang.String - Una stringa che rappresenta il nome, nella lingua specificata, di questa [FontFamily](../../com.aspose.drawing/fontfamily).
### isStyleAvailable(int style) {#isStyleAvailable-int-}
```
public boolean isStyleAvailable(int style)
```


Indica se l'enumerazione [FontStyle](../../com.aspose.drawing/fontstyle) specificata è disponibile.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| style | int | Il [FontStyle](../../com.aspose.drawing/fontstyle) da testare. |

**Returns:**
boolean - true se il [FontStyle](../../com.aspose.drawing/fontstyle) specificato è disponibile; altrimenti, false.
### getEmHeight(int style) {#getEmHeight-int-}
```
public int getEmHeight(int style)
```


Ottiene l'altezza, in unità di progettazione del carattere, del quadrato EM per lo stile specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| style | int | Il [FontStyle](../../com.aspose.drawing/fontstyle) per cui ottenere l'altezza EM. |

**Returns:**
int - L'altezza del quadrato EM.
### getCellAscent(int style) {#getCellAscent-int-}
```
public int getCellAscent(int style)
```


Restituisce l'ascesa della cella, in unità di progettazione, della [FontFamily](../../com.aspose.drawing/fontfamily) dello stile specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| style | int | Un [FontStyle](../../com.aspose.drawing/fontstyle) che contiene le informazioni di stile per il carattere. |

**Returns:**
int - L'ascesa della cella per questa [FontFamily](../../com.aspose.drawing/fontfamily) che utilizza il [FontStyle](../../com.aspose.drawing/fontstyle) specificato.
### getCellDescent(int style) {#getCellDescent-int-}
```
public int getCellDescent(int style)
```


Restituisce la discesa della cella, in unità di progettazione, della [FontFamily](../../com.aspose.drawing/fontfamily) dello stile specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| style | int | Un [FontStyle](../../com.aspose.drawing/fontstyle) che contiene le informazioni di stile per il carattere. |

**Returns:**
int - La metrica di discesa della cella per questa [FontFamily](../../com.aspose.drawing/fontfamily) che utilizza il [FontStyle](../../com.aspose.drawing/fontstyle) specificato.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Ottiene un codice hash per questa [FontFamily](../../com.aspose.drawing/fontfamily).

**Returns:**
int - Il codice hash per questa [FontFamily](../../com.aspose.drawing/fontfamily).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Indica se l'oggetto specificato è una [FontFamily](../../com.aspose.drawing/fontfamily) ed è identico a questa [FontFamily](../../com.aspose.drawing/fontfamily).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | java.lang.Object | L'oggetto da testare. |

**Returns:**
boolean - `true` se `obj` è una [FontFamily](../../com.aspose.drawing/fontfamily) ed è identica a questa [FontFamily](../../com.aspose.drawing/fontfamily); altrimenti, `false`.
### getLineSpacing(int style) {#getLineSpacing-int-}
```
public int getLineSpacing(int style)
```


Restituisce l'interlinea, in unità di progetto, della [FontFamily](../../com.aspose.drawing/fontfamily) dello stile specificato. L'interlinea è la distanza verticale tra le linee di base di due righe consecutive di testo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| style | int | Il [FontStyle](../../com.aspose.drawing/fontstyle) da applicare. |

**Returns:**
int - La distanza tra due righe consecutive di testo.
