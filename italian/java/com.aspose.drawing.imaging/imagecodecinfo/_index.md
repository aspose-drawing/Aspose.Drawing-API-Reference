---
title: ImageCodecInfo
second_title: Riferimento API di Aspose.Drawing per Java
description: La classe fornisce i membri di archiviazione necessari e i metodi per recuperare tutte le informazioni pertinenti sugli encoder e decoder di immagini installati, chiamati codec.
type: docs
weight: 25
url: /it/java/com.aspose.drawing.imaging/imagecodecinfo/
---
**Inheritance:**
java.lang.Object
```
public final class ImageCodecInfo
```

La classe [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo) fornisce i membri di archiviazione necessari e i metodi per recuperare tutte le informazioni pertinenti sugli encoder e decoder di immagini installati (chiamati codec). Non ereditabile.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [ImageCodecInfo()](#ImageCodecInfo--) | Inizializza una nuova istanza della classe [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo). |
| [ImageCodecInfo(UUID clsid, String codecName, String filenameExtension, String formatDescription, UUID formatID, String mimeType, int version)](#ImageCodecInfo-java.util.UUID-java.lang.String-java.lang.String-java.lang.String-java.util.UUID-java.lang.String-int-) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getClsid()](#getClsid--) | Ottiene una struttura java.util.UUID che contiene un GUID che identifica un codec specifico. |
| [setClsid(UUID value)](#setClsid-java.util.UUID-) | Imposta una struttura java.util.UUID che contiene un GUID che identifica un codec specifico. |
| [getFormatID()](#getFormatID--) | Ottiene una struttura java.util.UUID che contiene un GUID che identifica il formato del codec. |
| [setFormatID(UUID value)](#setFormatID-java.util.UUID-) | Imposta una struttura java.util.UUID che contiene un GUID che identifica il formato del codec. |
| [getCodecName()](#getCodecName--) | Ottiene o imposta una stringa che contiene il nome del codec. |
| [setCodecName(String value)](#setCodecName-java.lang.String-) | Ottiene o imposta una stringa che contiene il nome del codec. |
| [getFormatDescription()](#getFormatDescription--) | Ottiene o imposta una stringa che descrive il formato file del codec. |
| [setFormatDescription(String value)](#setFormatDescription-java.lang.String-) | Ottiene o imposta una stringa che descrive il formato file del codec. |
| [getFilenameExtension()](#getFilenameExtension--) | Ottiene o imposta una stringa che contiene le estensioni del nome file utilizzate nel codec. |
| [setFilenameExtension(String value)](#setFilenameExtension-java.lang.String-) | Ottiene o imposta una stringa che contiene le estensioni del nome file utilizzate nel codec. |
| [getMimeType()](#getMimeType--) | Ottiene o imposta una stringa che contiene il tipo Multipurpose Internet Mail Extensions (MIME) del codec. |
| [setMimeType(String value)](#setMimeType-java.lang.String-) | Ottiene o imposta una stringa che contiene il tipo Multipurpose Internet Mail Extensions (MIME) del codec. |
| [getVersion()](#getVersion--) | Ottiene o imposta il numero di versione del codec. |
| [setVersion(int value)](#setVersion-int-) | Ottiene o imposta il numero di versione del codec. |
| [getSignaturePatterns()](#getSignaturePatterns--) | Ottiene o imposta un array bidimensionale di byte che rappresenta la firma del codec. |
| [setSignaturePatterns(byte[][] value)](#setSignaturePatterns-byte-----) | Ottiene o imposta un array bidimensionale di byte che rappresenta la firma del codec. |
| [getSignatureMasks()](#getSignatureMasks--) | Ottiene o imposta un array bidimensionale di byte che può essere usato come filtro. |
| [setSignatureMasks(byte[][] value)](#setSignatureMasks-byte-----) | Ottiene o imposta un array bidimensionale di byte che può essere usato come filtro. |
| [getImageDecoders()](#getImageDecoders--) | Restituisce un array di oggetti [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo) che contengono informazioni sui decoder di immagini integrati in GDI+. |
| [getImageEncoders()](#getImageEncoders--) | Restituisce un array di oggetti [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo) che contengono informazioni sugli encoder di immagini integrati in GDI+. |
### ImageCodecInfo() {#ImageCodecInfo--}
```
public ImageCodecInfo()
```


Inizializza una nuova istanza della classe [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo).

### ImageCodecInfo(UUID clsid, String codecName, String filenameExtension, String formatDescription, UUID formatID, String mimeType, int version) {#ImageCodecInfo-java.util.UUID-java.lang.String-java.lang.String-java.lang.String-java.util.UUID-java.lang.String-int-}
```
public ImageCodecInfo(UUID clsid, String codecName, String filenameExtension, String formatDescription, UUID formatID, String mimeType, int version)
```


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| clsid | java.util.UUID |  |
| codecName | java.lang.String |  |
| filenameExtension | java.lang.String |  |
| formatDescription | java.lang.String |  |
| formatID | java.util.UUID |  |
| mimeType | java.lang.String |  |
| version | int |  |

### getClsid() {#getClsid--}
```
public UUID getClsid()
```


Ottiene una struttura java.util.UUID che contiene un GUID che identifica un codec specifico.

**Returns:**
java.util.UUID - un java.util.UUID
### setClsid(UUID value) {#setClsid-java.util.UUID-}
```
public void setClsid(UUID value)
```


Imposta una struttura java.util.UUID che contiene un GUID che identifica un codec specifico.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.util.UUID | un java.util.UUID |

### getFormatID() {#getFormatID--}
```
public UUID getFormatID()
```


Ottiene una struttura java.util.UUID che contiene un GUID che identifica il formato del codec.

**Returns:**
java.util.UUID - un java.util.UUID
### setFormatID(UUID value) {#setFormatID-java.util.UUID-}
```
public void setFormatID(UUID value)
```


Imposta una struttura java.util.UUID che contiene un GUID che identifica il formato del codec.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.util.UUID | un java.util.UUID |

### getCodecName() {#getCodecName--}
```
public String getCodecName()
```


Ottiene o imposta una stringa che contiene il nome del codec.

**Returns:**
java.lang.String
### setCodecName(String value) {#setCodecName-java.lang.String-}
```
public void setCodecName(String value)
```


Ottiene o imposta una stringa che contiene il nome del codec.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |

### getFormatDescription() {#getFormatDescription--}
```
public String getFormatDescription()
```


Ottiene o imposta una stringa che descrive il formato file del codec.

**Returns:**
java.lang.String
### setFormatDescription(String value) {#setFormatDescription-java.lang.String-}
```
public void setFormatDescription(String value)
```


Ottiene o imposta una stringa che descrive il formato file del codec.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |

### getFilenameExtension() {#getFilenameExtension--}
```
public String getFilenameExtension()
```


Ottiene o imposta la stringa che contiene le estensioni del nome file utilizzate nel codec. Le estensioni sono separate da punti e virgola.

**Returns:**
java.lang.String
### setFilenameExtension(String value) {#setFilenameExtension-java.lang.String-}
```
public void setFilenameExtension(String value)
```


Ottiene o imposta la stringa che contiene le estensioni del nome file utilizzate nel codec. Le estensioni sono separate da punti e virgola.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |

### getMimeType() {#getMimeType--}
```
public String getMimeType()
```


Ottiene o imposta una stringa che contiene il tipo Multipurpose Internet Mail Extensions (MIME) del codec.

**Returns:**
java.lang.String
### setMimeType(String value) {#setMimeType-java.lang.String-}
```
public void setMimeType(String value)
```


Ottiene o imposta una stringa che contiene il tipo Multipurpose Internet Mail Extensions (MIME) del codec.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |

### getVersion() {#getVersion--}
```
public int getVersion()
```


Ottiene o imposta il numero di versione del codec.

**Returns:**
int
### setVersion(int value) {#setVersion-int-}
```
public void setVersion(int value)
```


Ottiene o imposta il numero di versione del codec.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getSignaturePatterns() {#getSignaturePatterns--}
```
public byte[][] getSignaturePatterns()
```


Ottiene o imposta un array bidimensionale di byte che rappresenta la firma del codec.

**Returns:**
byte[][]
### setSignaturePatterns(byte[][] value) {#setSignaturePatterns-byte-----}
```
public void setSignaturePatterns(byte[][] value)
```


Ottiene o imposta un array bidimensionale di byte che rappresenta la firma del codec.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte[][] |  |

### getSignatureMasks() {#getSignatureMasks--}
```
public byte[][] getSignatureMasks()
```


Ottiene o imposta un array bidimensionale di byte che può essere usato come filtro.

**Returns:**
byte[][]
### setSignatureMasks(byte[][] value) {#setSignatureMasks-byte-----}
```
public void setSignatureMasks(byte[][] value)
```


Ottiene o imposta un array bidimensionale di byte che può essere usato come filtro.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte[][] |  |

### getImageDecoders() {#getImageDecoders--}
```
public static ImageCodecInfo[] getImageDecoders()
```


Restituisce un array di oggetti [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo) che contengono informazioni sui decoder di immagini integrati in GDI+.

**Returns:**
com.aspose.drawing.imaging.ImageCodecInfo[] - Un array di oggetti [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo). Ogni oggetto [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo) nell'array contiene informazioni su uno dei decoder di immagini integrati.
### getImageEncoders() {#getImageEncoders--}
```
public static ImageCodecInfo[] getImageEncoders()
```


Restituisce un array di oggetti [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo) che contengono informazioni sugli encoder di immagini integrati in GDI+.

**Returns:**
com.aspose.drawing.imaging.ImageCodecInfo[] - Un array di oggetti [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo). Ogni oggetto [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo) nell'array contiene informazioni su uno dei codificatori di immagini integrati.
