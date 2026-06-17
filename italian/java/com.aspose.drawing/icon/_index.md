---
title: Icon
second_title: Riferimento API di Aspose.Drawing per Java
description: Rappresenta un'icona Windows che è una piccola immagine bitmap utilizzata per rappresentare un oggetto.
type: docs
weight: 29
url: /it/java/com.aspose.drawing/icon/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.ms.System.IDisposable
```
public final class Icon implements System.ICloneable, System.IDisposable
```

Rappresenta un'icona Windows, che è una piccola immagine bitmap utilizzata per rappresentare un oggetto. Le icone possono essere considerate bitmap trasparenti, sebbene la loro dimensione sia determinata dal sistema.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Icon(String fileName)](#Icon-java.lang.String-) | Inizializza una nuova istanza della classe [Icon](../../com.aspose.drawing/icon) dal nome file specificato. |
| [Icon(InputStream stream)](#Icon-java.io.InputStream-) | Inizializza una nuova istanza della classe [Icon](../../com.aspose.drawing/icon) dal flusso di dati specificato. |
| [Icon(String fileName, Size size)](#Icon-java.lang.String-com.aspose.drawing.Size-) | Inizializza una nuova istanza della classe [Icon](../../com.aspose.drawing/icon) della dimensione specificata dal file specificato. |
| [Icon(Icon original, Size size)](#Icon-com.aspose.drawing.Icon-com.aspose.drawing.Size-) | Inizializza una nuova istanza della classe [Icon](../../com.aspose.drawing/icon) e tenta di trovare una versione dell'icona che corrisponda alla dimensione richiesta. |
| [Icon(Object type, String resource)](#Icon-java.lang.Object-java.lang.String-) | Inizializza una nuova istanza della classe [Icon](../../com.aspose.drawing/icon) da una risorsa nell'assembly specificato. |
| [Icon(InputStream stream, Size size)](#Icon-java.io.InputStream-com.aspose.drawing.Size-) | Inizializza una nuova istanza della classe [Icon](../../com.aspose.drawing/icon) della dimensione specificata dal flusso specificato. |
| [Icon(String fileName, int width, int height)](#Icon-java.lang.String-int-int-) | Inizializza una nuova istanza della classe [Icon](../../com.aspose.drawing/icon) con la larghezza e l'altezza specificate dal file specificato. |
| [Icon(Icon original, int width, int height)](#Icon-com.aspose.drawing.Icon-int-int-) | Inizializza una nuova istanza della classe [Icon](../../com.aspose.drawing/icon) e tenta di trovare una versione dell'icona che corrisponda alle dimensioni richieste. |
| [Icon(InputStream stream, int width, int height)](#Icon-java.io.InputStream-int-int-) | Inizializza una nuova istanza della classe [Icon](../../com.aspose.drawing/icon) dal flusso di dati specificato e con la larghezza e l'altezza specificate. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getHandle()](#getHandle--) | Ottiene l'handle per questa [Icon](../../com.aspose.drawing/icon). |
| [getHeight()](#getHeight--) | Ottiene l'altezza di questa [Icon](../../com.aspose.drawing/icon). |
| [getSize()](#getSize--) | Ottiene le dimensioni di questa [Icon](../../com.aspose.drawing/icon). |
| [getWidth()](#getWidth--) | Ottiene la larghezza di questa [Icon](../../com.aspose.drawing/icon). |
| [extractAssociatedIcon(String filePath)](#extractAssociatedIcon-java.lang.String-) | Restituisce una rappresentazione icona di un'immagine contenuta nel file specificato. |
| [fromHandle(byte[] handle)](#fromHandle-byte---) | Crea una [Icon](../../com.aspose.drawing/icon) GDI+ dall'handle Windows specificato a un'icona (HICON). |
| [deepClone()](#deepClone--) | Clona la [Icon](../../com.aspose.drawing/icon), creando un'immagine duplicata. |
| [dispose()](#dispose--) | Esegue attività definite dall'applicazione associate al rilascio, alla liberazione o al reset delle risorse non gestite. |
| [save(OutputStream outputStream)](#save-java.io.OutputStream-) | Salva questa [Icon](../../com.aspose.drawing/icon) nello java.io.InputStream di output specificato. |
| [toBitmap()](#toBitmap--) | Converte questa [Icon](../../com.aspose.drawing/icon) in un [Bitmap](../../com.aspose.drawing/bitmap) GDI+. |
| [toString()](#toString--) | Ottiene una stringa leggibile dall'uomo che descrive la [Icon](../../com.aspose.drawing/icon). |
### Icon(String fileName) {#Icon-java.lang.String-}
```
public Icon(String fileName)
```


Inizializza una nuova istanza della classe [Icon](../../com.aspose.drawing/icon) dal nome file specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fileName | java.lang.String | Il file da cui caricare la [Icon](../../com.aspose.drawing/icon). |

### Icon(InputStream stream) {#Icon-java.io.InputStream-}
```
public Icon(InputStream stream)
```


Inizializza una nuova istanza della classe [Icon](../../com.aspose.drawing/icon) dal flusso di dati specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | java.io.InputStream | Il flusso di dati da cui caricare la [Icon](../../com.aspose.drawing/icon). |

### Icon(String fileName, Size size) {#Icon-java.lang.String-com.aspose.drawing.Size-}
```
public Icon(String fileName, Size size)
```


Inizializza una nuova istanza della classe [Icon](../../com.aspose.drawing/icon) della dimensione specificata dal file specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fileName | java.lang.String | Il nome e il percorso del file che contiene i dati dell'icona. |
| size | [Size](../../com.aspose.drawing/size) | La dimensione desiderata dell'icona. |

### Icon(Icon original, Size size) {#Icon-com.aspose.drawing.Icon-com.aspose.drawing.Size-}
```
public Icon(Icon original, Size size)
```


Inizializza una nuova istanza della classe [Icon](../../com.aspose.drawing/icon) e tenta di trovare una versione dell'icona che corrisponda alla dimensione richiesta.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| original | [Icon](../../com.aspose.drawing/icon) | La [Icon](../../com.aspose.drawing/icon) da cui caricare l'icona ridimensionata. |
| size | [Size](../../com.aspose.drawing/size) | Una struttura `Size`([.getSize](../../null/\#getSize)) che specifica l'altezza e la larghezza della nuova [Icon](../../com.aspose.drawing/icon). |

### Icon(Object type, String resource) {#Icon-java.lang.Object-java.lang.String-}
```
public Icon(Object type, String resource)
```


Inizializza una nuova istanza della classe [Icon](../../com.aspose.drawing/icon) da una risorsa nell'assembly specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| type | java.lang.Object | Un Type che specifica l'assembly in cui cercare la risorsa. |
| risorsa | java.lang.String | Il nome della risorsa da caricare. |

### Icon(InputStream stream, Size size) {#Icon-java.io.InputStream-com.aspose.drawing.Size-}
```
public Icon(InputStream stream, Size size)
```


Inizializza una nuova istanza della classe [Icon](../../com.aspose.drawing/icon) della dimensione specificata dal flusso specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| flusso | java.io.InputStream | Il flusso che contiene i dati dell'icona. |
| size | [Size](../../com.aspose.drawing/size) | La dimensione desiderata dell'icona. |

### Icon(String fileName, int width, int height) {#Icon-java.lang.String-int-int-}
```
public Icon(String fileName, int width, int height)
```


Inizializza una nuova istanza della classe [Icon](../../com.aspose.drawing/icon) con la larghezza e l'altezza specificate dal file specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fileName | java.lang.String | Il nome e il percorso del file che contiene i dati della [Icon](../../com.aspose.drawing/icon). |
| width | int | La larghezza desiderata della [Icon](../../com.aspose.drawing/icon). |
| height | int | L'altezza desiderata dell'[Icon](../../com.aspose.drawing/icon). |

### Icon(Icon original, int width, int height) {#Icon-com.aspose.drawing.Icon-int-int-}
```
public Icon(Icon original, int width, int height)
```


Inizializza una nuova istanza della classe [Icon](../../com.aspose.drawing/icon) e tenta di trovare una versione dell'icona che corrisponda alle dimensioni richieste.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| original | [Icon](../../com.aspose.drawing/icon) | L'icona da cui caricare la dimensione diversa. |
| width | int | La larghezza della nuova icona. |
| height | int | L'altezza della nuova icona. |

### Icon(InputStream stream, int width, int height) {#Icon-java.io.InputStream-int-int-}
```
public Icon(InputStream stream, int width, int height)
```


Inizializza una nuova istanza della classe [Icon](../../com.aspose.drawing/icon) dal flusso di dati specificato e con la larghezza e l'altezza specificate.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| flusso | java.io.InputStream | Il flusso di dati da cui caricare l'icona. |
| width | int | La larghezza, in pixel, dell'icona. |
| height | int | L'altezza, in pixel, dell'icona. |

### getHandle() {#getHandle--}
```
public System.IntPtr getHandle()
```


Ottiene l'handle per questa [Icon](../../com.aspose.drawing/icon). Non è una copia dell'handle; non liberarlo.

Valore: L'handle Windows per l'icona.

**Returns:**
com.aspose.ms.System.IntPtr
### getHeight() {#getHeight--}
```
public int getHeight()
```


Ottiene l'altezza di questa [Icon](../../com.aspose.drawing/icon).

Valore: L'altezza di questa [Icon](../../com.aspose.drawing/icon).

**Returns:**
int
### getSize() {#getSize--}
```
public Size getSize()
```


Ottiene le dimensioni di questa [Icon](../../com.aspose.drawing/icon).

Valore: Una struttura `Size`([.getSize](../../null/\#getSize)) che specifica la larghezza e l'altezza di questa [Icon](../../com.aspose.drawing/icon).

**Returns:**
[Size](../../com.aspose.drawing/size)
### getWidth() {#getWidth--}
```
public int getWidth()
```


Ottiene la larghezza di questa [Icon](../../com.aspose.drawing/icon).

Valore: La larghezza di questa [Icon](../../com.aspose.drawing/icon).

**Returns:**
int
### extractAssociatedIcon(String filePath) {#extractAssociatedIcon-java.lang.String-}
```
public static Icon extractAssociatedIcon(String filePath)
```


Restituisce una rappresentazione icona di un'immagine contenuta nel file specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | java.lang.String | Il percorso al file che contiene un'immagine. |

**Returns:**
[Icon](../../com.aspose.drawing/icon) - The [Icon](../../com.aspose.drawing/icon) representation of the image that is contained in the specified file.
### fromHandle(byte[] handle) {#fromHandle-byte---}
```
public static Icon fromHandle(byte[] handle)
```


Crea una [Icon](../../com.aspose.drawing/icon) GDI+ dall'handle Windows specificato a un'icona (HICON).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| handle | byte[] | Un handle Windows a un'icona. |

**Returns:**
[Icon](../../com.aspose.drawing/icon) - The [Icon](../../com.aspose.drawing/icon) this method creates.
### deepClone() {#deepClone--}
```
public Object deepClone()
```


Clona la [Icon](../../com.aspose.drawing/icon), creando un'immagine duplicata.

**Returns:**
java.lang.Object - Un oggetto che può essere convertito a una [Icon](../../com.aspose.drawing/icon).
### dispose() {#dispose--}
```
public void dispose()
```


Esegue attività definite dall'applicazione associate al rilascio, alla liberazione o al reset delle risorse non gestite.

### save(OutputStream outputStream) {#save-java.io.OutputStream-}
```
public void save(OutputStream outputStream)
```


Salva questa [Icon](../../com.aspose.drawing/icon) nello java.io.InputStream di output specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| outputStream | java.io.OutputStream | Il java.io.InputStream su cui salvare. |

### toBitmap() {#toBitmap--}
```
public Bitmap toBitmap()
```


Converte questa [Icon](../../com.aspose.drawing/icon) in un [Bitmap](../../com.aspose.drawing/bitmap) GDI+.

**Returns:**
[Bitmap](../../com.aspose.drawing/bitmap) - A [Bitmap](../../com.aspose.drawing/bitmap) that represents the converted [Icon](../../com.aspose.drawing/icon).
### toString() {#toString--}
```
public String toString()
```


Ottiene una stringa leggibile dall'uomo che descrive la [Icon](../../com.aspose.drawing/icon).

**Returns:**
java.lang.String - Una stringa che descrive la [Icon](../../com.aspose.drawing/icon).
