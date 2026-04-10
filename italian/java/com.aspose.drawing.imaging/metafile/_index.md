---
title: Metafile
second_title: Riferimento API di Aspose.Drawing per Java
description: Definisce un metafile grafico.
type: docs
weight: 30
url: /it/java/com.aspose.drawing.imaging/metafile/
---
**Inheritance:**
java.lang.Object, [com.aspose.drawing.Image](../../com.aspose.drawing/image)
```
public final class Metafile extends Image
```

Definisce un metafile grafico. Un metafile contiene record che descrivono una sequenza di operazioni grafiche che possono essere registrate (costruite) e riprodotte (visualizzate). Questa classe non è ereditabile.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Metafile(byte[] henhmetafile, boolean deleteEmf)](#Metafile-byte---boolean-) | Inizializza una nuova istanza della classe [Metafile](../../com.aspose.drawing.imaging/metafile) dal handle specificato. |
| [Metafile(byte[] referenceHdc, int emfType)](#Metafile-byte---int-) | Inizializza una nuova istanza della classe [Metafile](../../com.aspose.drawing.imaging/metafile) dal handle specificato a un contesto dispositivo e da un'enumerazione [EmfType](../../com.aspose.drawing.imaging/emftype) che specifica il formato del [Metafile](../../com.aspose.drawing.imaging/metafile). |
| [Metafile(String filename)](#Metafile-java.lang.String-) | Inizializza una nuova istanza della classe [Metafile](../../com.aspose.drawing.imaging/metafile) dal nome file specificato. |
| [Metafile(String filename, byte[] referenceHdc)](#Metafile-java.lang.String-byte---) | Inizializza una nuova istanza della classe [Metafile](../../com.aspose.drawing.imaging/metafile) dal nome file specificato. |
| [Metafile(InputStream stream)](#Metafile-java.io.InputStream-) | Inizializza una nuova istanza della classe [Metafile](../../com.aspose.drawing.imaging/metafile) dal flusso di dati specificato. |
| [Metafile(InputStream stream, byte[] referenceHdc)](#Metafile-java.io.InputStream-byte---) | Inizializza una nuova istanza della classe [Metafile](../../com.aspose.drawing.imaging/metafile) dal flusso di dati specificato e da un handle Windows a un contesto dispositivo. |
| [Metafile(System.IO.Stream stream, int type)](#Metafile-com.aspose.ms.System.IO.Stream-int-) | Inizializza una nuova istanza della classe [Metafile](../../com.aspose.drawing.imaging/metafile) dal flusso di dati specificato e da un handle Windows a un contesto dispositivo. |
| [Metafile(InputStream stream, byte[] referenceHdc, int type)](#Metafile-java.io.InputStream-byte---int-) | Inizializza una nuova istanza della classe [Metafile](../../com.aspose.drawing.imaging/metafile) dal flusso di dati specificato, da un handle Windows a un contesto dispositivo e da un'enumerazione [EmfType](../../com.aspose.drawing.imaging/emftype) che specifica il formato del [Metafile](../../com.aspose.drawing.imaging/metafile). |
| [Metafile(InputStream stream, byte[] referenceHdc, RectangleF frameRect, int frameUnit, int type)](#Metafile-java.io.InputStream-byte---com.aspose.drawing.RectangleF-int-int-) | Inizializza una nuova istanza della classe [Metafile](../../com.aspose.drawing.imaging/metafile) dal flusso di dati specificato, da un handle Windows a un contesto dispositivo e da un'enumerazione [EmfType](../../com.aspose.drawing.imaging/emftype) che specifica il formato del [Metafile](../../com.aspose.drawing.imaging/metafile). |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getWidth()](#getWidth--) | Restituisce la larghezza, in pixel, di questo [Metafile](../../com.aspose.drawing.imaging/metafile). |
| [getHeight()](#getHeight--) | Restituisce l'altezza, in pixel, di questo [Metafile](../../com.aspose.drawing.imaging/metafile). |
| [getRawFormat()](#getRawFormat--) | Restituisce il formato file di questa [Image](../../com.aspose.drawing/image). |
| [getPixelFormat()](#getPixelFormat--) | Restituisce il formato pixel di questa [Image](../../com.aspose.drawing/image). |
| [getPalette()](#getPalette--) | Ottiene o imposta la tavolozza dei colori utilizzata per questa [Image](../../com.aspose.drawing/image). |
| [setPalette(ColorPalette value)](#setPalette-com.aspose.drawing.imaging.ColorPalette-) | Ottiene o imposta la tavolozza dei colori utilizzata per questa [Image](../../com.aspose.drawing/image). |
| [getFrameDimensionsList()](#getFrameDimensionsList--) | Restituisce un array di GUID che rappresentano le dimensioni dei fotogrammi all'interno di questa [Image](../../com.aspose.drawing/image). |
| [getPropertyIdList()](#getPropertyIdList--) | Restituisce gli ID degli elementi di proprietà memorizzati in questa [Image](../../com.aspose.drawing/image). |
| [getPropertyItems()](#getPropertyItems--) | Restituisce tutti gli elementi di proprietà (pezzi di metadati) memorizzati in questa [Image](../../com.aspose.drawing/image). |
| [getMetafileHeader(InputStream stream)](#getMetafileHeader-java.io.InputStream-) | Restituisce il [MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) associato al [Metafile](../../com.aspose.drawing.imaging/metafile) specificato. |
| [getMetafileHeader(String fileName)](#getMetafileHeader-java.lang.String-) | Restituisce il [MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) associato al [Metafile](../../com.aspose.drawing.imaging/metafile) specificato. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | Questo metodo ruota, capovolge o ruota e capovolge l'[Image](../../com.aspose.drawing/image). |
| [getHenhmetafile()](#getHenhmetafile--) | Restituisce un handle Windows a un [Metafile](../../com.aspose.drawing.imaging/metafile) migliorato. |
| [playRecord(int recordType, int flags, int dataSize, byte[] dataArray)](#playRecord-int-int-int-byte---) | Esegue un record metafile individuale. |
| [getMetafileHeader()](#getMetafileHeader--) | Restituisce il [MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) associato a questo [Metafile](../../com.aspose.drawing.imaging/metafile). |
| [getPropertyItem(int propid)](#getPropertyItem-int-) | Restituisce l'elemento di proprietà specificato da questa [Image](../../com.aspose.drawing/image). |
| [removePropertyItem(int propid)](#removePropertyItem-int-) | Rimuove l'elemento di proprietà specificato da questa [Image](../../com.aspose.drawing/image). |
| [setPropertyItem(PropertyItem propitem)](#setPropertyItem-com.aspose.drawing.imaging.PropertyItem-) | Memorizza un elemento di proprietà (pezzo di metadati) in questa [Image](../../com.aspose.drawing/image). |
### Metafile(byte[] henhmetafile, boolean deleteEmf) {#Metafile-byte---boolean-}
```
public Metafile(byte[] henhmetafile, boolean deleteEmf)
```


Inizializza una nuova istanza della classe [Metafile](../../com.aspose.drawing.imaging/metafile) dal handle specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| henhmetafile | byte[] | Un handle a un metafile avanzato. |
| deleteEmf | boolean | true per eliminare l'handle del metafile avanzato quando il [Metafile](../../com.aspose.drawing.imaging/metafile) viene eliminato; altrimenti, false. |

### Metafile(byte[] referenceHdc, int emfType) {#Metafile-byte---int-}
```
public Metafile(byte[] referenceHdc, int emfType)
```


Inizializza una nuova istanza della classe [Metafile](../../com.aspose.drawing.imaging/metafile) dal handle specificato a un contesto dispositivo e da un'enumerazione [EmfType](../../com.aspose.drawing.imaging/emftype) che specifica il formato del [Metafile](../../com.aspose.drawing.imaging/metafile).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| referenceHdc | byte[] | Il handle a un contesto dispositivo. |
| emfType | int | Un [EmfType](../../com.aspose.drawing.imaging/emftype) che specifica il formato del [Metafile](../../com.aspose.drawing.imaging/metafile). |

### Metafile(String filename) {#Metafile-java.lang.String-}
```
public Metafile(String filename)
```


Inizializza una nuova istanza della classe [Metafile](../../com.aspose.drawing.imaging/metafile) dal nome file specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filename | java.lang.String | Una String che rappresenta il nome file da cui creare il nuovo [Metafile](../../com.aspose.drawing.imaging/metafile). |

### Metafile(String filename, byte[] referenceHdc) {#Metafile-java.lang.String-byte---}
```
public Metafile(String filename, byte[] referenceHdc)
```


Inizializza una nuova istanza della classe [Metafile](../../com.aspose.drawing.imaging/metafile) dal nome file specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filename | java.lang.String | Una String che rappresenta il nome file da cui creare il nuovo [Metafile](../../com.aspose.drawing.imaging/metafile). |
| referenceHdc | byte[] | Un handle Windows a un contesto dispositivo. |

### Metafile(InputStream stream) {#Metafile-java.io.InputStream-}
```
public Metafile(InputStream stream)
```


Inizializza una nuova istanza della classe [Metafile](../../com.aspose.drawing.imaging/metafile) dal flusso di dati specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | java.io.InputStream | L'InputStream da cui creare il nuovo [Metafile](../../com.aspose.drawing.imaging/metafile). |

### Metafile(InputStream stream, byte[] referenceHdc) {#Metafile-java.io.InputStream-byte---}
```
public Metafile(InputStream stream, byte[] referenceHdc)
```


Inizializza una nuova istanza della classe [Metafile](../../com.aspose.drawing.imaging/metafile) dal flusso di dati specificato e da un handle Windows a un contesto dispositivo. />.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | java.io.InputStream | Un InputStream che contiene i dati per questo [Metafile](../../com.aspose.drawing.imaging/metafile). |
| referenceHdc | byte[] | Un handle Windows a un contesto dispositivo dell'oggetto [Metafile](../../com.aspose.drawing.imaging/metafile). |

### Metafile(System.IO.Stream stream, int type) {#Metafile-com.aspose.ms.System.IO.Stream-int-}
```
public Metafile(System.IO.Stream stream, int type)
```


Inizializza una nuova istanza della classe [Metafile](../../com.aspose.drawing.imaging/metafile) dal flusso di dati specificato e da un handle Windows a un contesto dispositivo. />.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | Un InputStream che contiene i dati per questo [Metafile](../../com.aspose.drawing.imaging/metafile). |
| type | int | deve essere int 1. |

### Metafile(InputStream stream, byte[] referenceHdc, int type) {#Metafile-java.io.InputStream-byte---int-}
```
public Metafile(InputStream stream, byte[] referenceHdc, int type)
```


Inizializza una nuova istanza della classe [Metafile](../../com.aspose.drawing.imaging/metafile) dal flusso di dati specificato, da un handle Windows a un contesto dispositivo e da un'enumerazione [EmfType](../../com.aspose.drawing.imaging/emftype) che specifica il formato del [Metafile](../../com.aspose.drawing.imaging/metafile).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | java.io.InputStream | Un InputStream che contiene i dati per questo [Metafile](../../com.aspose.drawing.imaging/metafile). |
| referenceHdc | byte[] | Un handle Windows a un contesto dispositivo. |
| type | int | Un [EmfType](../../com.aspose.drawing.imaging/emftype) che specifica il formato del [Metafile](../../com.aspose.drawing.imaging/metafile). |

### Metafile(InputStream stream, byte[] referenceHdc, RectangleF frameRect, int frameUnit, int type) {#Metafile-java.io.InputStream-byte---com.aspose.drawing.RectangleF-int-int-}
```
public Metafile(InputStream stream, byte[] referenceHdc, RectangleF frameRect, int frameUnit, int type)
```


Inizializza una nuova istanza della classe [Metafile](../../com.aspose.drawing.imaging/metafile) dal flusso di dati specificato, da un handle Windows a un contesto dispositivo e da un'enumerazione [EmfType](../../com.aspose.drawing.imaging/emftype) che specifica il formato del [Metafile](../../com.aspose.drawing.imaging/metafile).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | java.io.InputStream | Un InputStream che contiene i dati per questo [Metafile](../../com.aspose.drawing.imaging/metafile). |
| referenceHdc | byte[] | Un handle Windows a un contesto dispositivo. |
| frameRect | [RectangleF](../../com.aspose.drawing/rectanglef) | Un [Rectangle](../../com.aspose.drawing/rectangle) che rappresenta il rettangolo che delimita il nuovo [Metafile](../../com.aspose.drawing.imaging/metafile). |
| frameUnit | int | Un [MetafileFrameUnit](../../com.aspose.drawing.imaging/metafileframeunit) che specifica l'unità di misura per frameRect. |
| type | int | Un [EmfType](../../com.aspose.drawing.imaging/emftype) che specifica il formato del [Metafile](../../com.aspose.drawing.imaging/metafile). |

### getWidth() {#getWidth--}
```
public int getWidth()
```


Restituisce la larghezza, in pixel, di questo [Metafile](../../com.aspose.drawing.imaging/metafile).

**Returns:**
int
### getHeight() {#getHeight--}
```
public int getHeight()
```


Restituisce l'altezza, in pixel, di questo [Metafile](../../com.aspose.drawing.imaging/metafile).

**Returns:**
int - l'altezza, in pixel, di questo [Metafile](../../com.aspose.drawing.imaging/metafile).
### getRawFormat() {#getRawFormat--}
```
public ImageFormat getRawFormat()
```


Restituisce il formato file di questa [Image](../../com.aspose.drawing/image).

**Returns:**
[ImageFormat](../../com.aspose.drawing.imaging/imageformat) - The [ImageFormat](../../com.aspose.drawing.imaging/imageformat) that represents the file format of this [Image](../../com.aspose.drawing/image).
### getPixelFormat() {#getPixelFormat--}
```
public int getPixelFormat()
```


Restituisce il formato pixel di questa [Image](../../com.aspose.drawing/image).

**Returns:**
int - Un `PixelFormat`([Image.getPixelFormat](../../com.aspose.drawing/image\#getPixelFormat)) che rappresenta il formato pixel per questa [Image](../../com.aspose.drawing/image).
### getPalette() {#getPalette--}
```
public ColorPalette getPalette()
```


Ottiene o imposta la tavolozza dei colori utilizzata per questa [Image](../../com.aspose.drawing/image).

**Returns:**
[ColorPalette](../../com.aspose.drawing.imaging/colorpalette) - A [ColorPalette](../../com.aspose.drawing.imaging/colorpalette) that represents the color palette used for this [Image](../../com.aspose.drawing/image).
### setPalette(ColorPalette value) {#setPalette-com.aspose.drawing.imaging.ColorPalette-}
```
public void setPalette(ColorPalette value)
```


Ottiene o imposta la tavolozza dei colori utilizzata per questa [Image](../../com.aspose.drawing/image).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [ColorPalette](../../com.aspose.drawing.imaging/colorpalette) |  |

### getFrameDimensionsList() {#getFrameDimensionsList--}
```
public UUID[] getFrameDimensionsList()
```


Restituisce un array di GUID che rappresentano le dimensioni dei fotogrammi all'interno di questa [Image](../../com.aspose.drawing/image).

**Returns:**
java.util.UUID[] - Un array di GUID che specifica le dimensioni dei fotogrammi all'interno di questa [Image](../../com.aspose.drawing/image) dal più significativo al meno significativo.
### getPropertyIdList() {#getPropertyIdList--}
```
public int[] getPropertyIdList()
```


Restituisce gli ID degli elementi di proprietà memorizzati in questa [Image](../../com.aspose.drawing/image).

**Returns:**
int[] - Un array degli ID proprietà, uno per ogni elemento proprietà memorizzato in questa immagine.
### getPropertyItems() {#getPropertyItems--}
```
public PropertyItem[] getPropertyItems()
```


Restituisce tutti gli elementi di proprietà (pezzi di metadati) memorizzati in questa [Image](../../com.aspose.drawing/image).

**Returns:**
com.aspose.drawing.imaging.PropertyItem[] - Un array di oggetti [PropertyItem](../../com.aspose.drawing.imaging/propertyitem) uno per ogni elemento proprietà memorizzato nell'immagine.
### getMetafileHeader(InputStream stream) {#getMetafileHeader-java.io.InputStream-}
```
public static MetafileHeader getMetafileHeader(InputStream stream)
```


Restituisce il [MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) associato al [Metafile](../../com.aspose.drawing.imaging/metafile) specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | java.io.InputStream | Un InputStream contenente il [Metafile](../../com.aspose.drawing.imaging/metafile) per il quale viene recuperata un'intestazione. |

**Returns:**
[MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) - The [MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) associated with the specified [Metafile](../../com.aspose.drawing.imaging/metafile).
### getMetafileHeader(String fileName) {#getMetafileHeader-java.lang.String-}
```
public static MetafileHeader getMetafileHeader(String fileName)
```


Restituisce il [MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) associato al [Metafile](../../com.aspose.drawing.imaging/metafile) specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fileName | java.lang.String | Una String contenente il nome del [Metafile](../../com.aspose.drawing.imaging/metafile) per il quale viene recuperata un'intestazione. |

**Returns:**
[MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) - The [MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) associated with the specified [Metafile](../../com.aspose.drawing.imaging/metafile).
### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


Questo metodo ruota, capovolge o ruota e capovolge l'[Image](../../com.aspose.drawing/image).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rotateFlipType | int | Un membro [RotateFlipType](../../com.aspose.drawing/rotatefliptype) che specifica il tipo di rotazione e ribaltamento da applicare all'immagine. |

### getHenhmetafile() {#getHenhmetafile--}
```
public System.IntPtr getHenhmetafile()
```


Restituisce un handle Windows a un [Metafile](../../com.aspose.drawing.imaging/metafile) migliorato.

**Returns:**
com.aspose.ms.System.IntPtr - Un handle Windows a questo [Metafile](../../com.aspose.drawing.imaging/metafile) avanzato.
### playRecord(int recordType, int flags, int dataSize, byte[] dataArray) {#playRecord-int-int-int-byte---}
```
public void playRecord(int recordType, int flags, int dataSize, byte[] dataArray)
```


Esegue un record metafile individuale.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| recordType | int | Elemento del [EmfPlusRecordType](../../com.aspose.drawing.imaging/emfplusrecordtype) che specifica il tipo di record metafile in riproduzione. |
| flags | int | Un insieme di flag che specificano gli attributi del record. |
| dataSize | int | Il numero di byte nei dati del record. |
| dataArray | byte[] | Un array di byte che contiene i dati del record. |

### getMetafileHeader() {#getMetafileHeader--}
```
public MetafileHeader getMetafileHeader()
```


Restituisce il [MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) associato a questo [Metafile](../../com.aspose.drawing.imaging/metafile).

**Returns:**
[MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) - The [MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) associated with this [Metafile](../../com.aspose.drawing.imaging/metafile).
### getPropertyItem(int propid) {#getPropertyItem-int-}
```
public PropertyItem getPropertyItem(int propid)
```


Restituisce l'elemento di proprietà specificato da questa [Image](../../com.aspose.drawing/image).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| propid | int | L'ID dell'elemento di proprietà da ottenere. |

**Returns:**
[PropertyItem](../../com.aspose.drawing.imaging/propertyitem) - The [PropertyItem](../../com.aspose.drawing.imaging/propertyitem) this method gets.
### removePropertyItem(int propid) {#removePropertyItem-int-}
```
public void removePropertyItem(int propid)
```


Rimuove l'elemento di proprietà specificato da questa [Image](../../com.aspose.drawing/image).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| propid | int | L'ID dell'elemento di proprietà da rimuovere. |

### setPropertyItem(PropertyItem propitem) {#setPropertyItem-com.aspose.drawing.imaging.PropertyItem-}
```
public void setPropertyItem(PropertyItem propitem)
```


Memorizza un elemento di proprietà (pezzo di metadati) in questa [Image](../../com.aspose.drawing/image).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| propitem | [PropertyItem](../../com.aspose.drawing.imaging/propertyitem) | Il [PropertyItem](../../com.aspose.drawing.imaging/propertyitem) da memorizzare. |

