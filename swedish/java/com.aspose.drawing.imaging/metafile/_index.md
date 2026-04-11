---
title: Metafile
second_title: Aspose.Drawing för Java API‑referens
description: Definierar en grafisk metafil.
type: docs
weight: 30
url: /sv/java/com.aspose.drawing.imaging/metafile/
---
**Inheritance:**
java.lang.Object, [com.aspose.drawing.Image](../../com.aspose.drawing/image)
```
public final class Metafile extends Image
```

Definierar en grafisk metafil. En metafil innehåller poster som beskriver en sekvens av grafikoperationer som kan spelas in (konstrueras) och återges (visas). Denna klass är inte ärftlig.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [Metafile(byte[] henhmetafile, boolean deleteEmf)](#Metafile-byte---boolean-) | Initierar en ny instans av klassen [Metafile](../../com.aspose.drawing.imaging/metafile) från den angivna handtaget. |
| [Metafile(byte[] referenceHdc, int emfType)](#Metafile-byte---int-) | Initierar en ny instans av klassen [Metafile](../../com.aspose.drawing.imaging/metafile) från det angivna handtaget till en enhetskontext och en [EmfType](../../com.aspose.drawing.imaging/emftype)-enumeration som specificerar formatet för [Metafile](../../com.aspose.drawing.imaging/metafile). |
| [Metafile(String filename)](#Metafile-java.lang.String-) | Initierar en ny instans av klassen [Metafile](../../com.aspose.drawing.imaging/metafile) från det angivna filnamnet. |
| [Metafile(String filename, byte[] referenceHdc)](#Metafile-java.lang.String-byte---) | Initierar en ny instans av klassen [Metafile](../../com.aspose.drawing.imaging/metafile) från det angivna filnamnet. |
| [Metafile(InputStream stream)](#Metafile-java.io.InputStream-) | Initierar en ny instans av klassen [Metafile](../../com.aspose.drawing.imaging/metafile) från den angivna datastreamen. |
| [Metafile(InputStream stream, byte[] referenceHdc)](#Metafile-java.io.InputStream-byte---) | Initierar en ny instans av klassen [Metafile](../../com.aspose.drawing.imaging/metafile) från den angivna datastreamen och ett Windows-handtag till en enhetskontext. |
| [Metafile(System.IO.Stream stream, int type)](#Metafile-com.aspose.ms.System.IO.Stream-int-) | Initierar en ny instans av klassen [Metafile](../../com.aspose.drawing.imaging/metafile) från den angivna datastreamen och ett Windows-handtag till en enhetskontext. |
| [Metafile(InputStream stream, byte[] referenceHdc, int type)](#Metafile-java.io.InputStream-byte---int-) | Initierar en ny instans av klassen [Metafile](../../com.aspose.drawing.imaging/metafile) från den angivna datastreamen, ett Windows-handtag till en enhetskontext och en [EmfType](../../com.aspose.drawing.imaging/emftype)-enumeration som specificerar formatet för [Metafile](../../com.aspose.drawing.imaging/metafile). |
| [Metafile(InputStream stream, byte[] referenceHdc, RectangleF frameRect, int frameUnit, int type)](#Metafile-java.io.InputStream-byte---com.aspose.drawing.RectangleF-int-int-) | Initierar en ny instans av klassen [Metafile](../../com.aspose.drawing.imaging/metafile) från den angivna datastreamen, ett Windows-handtag till en enhetskontext och en [EmfType](../../com.aspose.drawing.imaging/emftype)-enumeration som specificerar formatet för [Metafile](../../com.aspose.drawing.imaging/metafile). |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getWidth()](#getWidth--) | Hämtar bredden, i pixlar, för denna [Metafile](../../com.aspose.drawing.imaging/metafile). |
| [getHeight()](#getHeight--) | Hämtar höjden, i pixlar, för denna [Metafile](../../com.aspose.drawing.imaging/metafile). |
| [getRawFormat()](#getRawFormat--) | Hämtar filformatet för denna [Image](../../com.aspose.drawing/image). |
| [getPixelFormat()](#getPixelFormat--) | Hämtar pixelformatet för denna [Image](../../com.aspose.drawing/image). |
| [getPalette()](#getPalette--) | Hämtar eller anger färgpaletten som används för denna [Image](../../com.aspose.drawing/image). |
| [setPalette(ColorPalette value)](#setPalette-com.aspose.drawing.imaging.ColorPalette-) | Hämtar eller anger färgpaletten som används för denna [Image](../../com.aspose.drawing/image). |
| [getFrameDimensionsList()](#getFrameDimensionsList--) | Hämtar en array av GUID:er som representerar dimensionerna för ramar inom denna [Image](../../com.aspose.drawing/image). |
| [getPropertyIdList()](#getPropertyIdList--) | Hämtar ID:n för egenskapsobjekten som lagras i denna [Image](../../com.aspose.drawing/image). |
| [getPropertyItems()](#getPropertyItems--) | Hämtar alla egenskapsobjekt (metadata) som lagras i denna [Image](../../com.aspose.drawing/image). |
| [getMetafileHeader(InputStream stream)](#getMetafileHeader-java.io.InputStream-) | Returnerar [MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) som är associerad med den angivna [Metafile](../../com.aspose.drawing.imaging/metafile). |
| [getMetafileHeader(String fileName)](#getMetafileHeader-java.lang.String-) | Returnerar [MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) som är associerad med den angivna [Metafile](../../com.aspose.drawing.imaging/metafile). |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | Denna metod roterar, vänder eller roterar och vänder [Image](../../com.aspose.drawing/image). |
| [getHenhmetafile()](#getHenhmetafile--) | Returnerar ett Windows-handtag till en förbättrad [Metafile](../../com.aspose.drawing.imaging/metafile). |
| [playRecord(int recordType, int flags, int dataSize, byte[] dataArray)](#playRecord-int-int-int-byte---) | Spelar upp en enskild metafilpost. |
| [getMetafileHeader()](#getMetafileHeader--) | Returnerar [MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) som är associerad med denna [Metafile](../../com.aspose.drawing.imaging/metafile). |
| [getPropertyItem(int propid)](#getPropertyItem-int-) | Hämtar det angivna egenskapsobjektet från denna [Image](../../com.aspose.drawing/image). |
| [removePropertyItem(int propid)](#removePropertyItem-int-) | Tar bort det angivna egenskapsobjektet från denna [Image](../../com.aspose.drawing/image). |
| [setPropertyItem(PropertyItem propitem)](#setPropertyItem-com.aspose.drawing.imaging.PropertyItem-) | Lagrar ett egenskapsobjekt (metadata) i denna [Image](../../com.aspose.drawing/image). |
### Metafile(byte[] henhmetafile, boolean deleteEmf) {#Metafile-byte---boolean-}
```
public Metafile(byte[] henhmetafile, boolean deleteEmf)
```


Initierar en ny instans av klassen [Metafile](../../com.aspose.drawing.imaging/metafile) från den angivna handtaget.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| henhmetafile | byte[] | Ett handtag till en förbättrad metafil. |
| deleteEmf | boolean | true för att ta bort handtaget för den förbättrade metafilen när [Metafile](../../com.aspose.drawing.imaging/metafile) tas bort; annars false. |

### Metafile(byte[] referenceHdc, int emfType) {#Metafile-byte---int-}
```
public Metafile(byte[] referenceHdc, int emfType)
```


Initierar en ny instans av klassen [Metafile](../../com.aspose.drawing.imaging/metafile) från det angivna handtaget till en enhetskontext och en [EmfType](../../com.aspose.drawing.imaging/emftype)-enumeration som specificerar formatet för [Metafile](../../com.aspose.drawing.imaging/metafile).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| referenceHdc | byte[] | Handtaget till ett enhetssammanhang. |
| emfType | int | En [EmfType](../../com.aspose.drawing.imaging/emftype) som specificerar formatet för [Metafile](../../com.aspose.drawing.imaging/metafile). |

### Metafile(String filename) {#Metafile-java.lang.String-}
```
public Metafile(String filename)
```


Initierar en ny instans av klassen [Metafile](../../com.aspose.drawing.imaging/metafile) från det angivna filnamnet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filename | java.lang.String | En sträng som representerar filnamnet från vilket den nya [Metafile](../../com.aspose.drawing.imaging/metafile) ska skapas. |

### Metafile(String filename, byte[] referenceHdc) {#Metafile-java.lang.String-byte---}
```
public Metafile(String filename, byte[] referenceHdc)
```


Initierar en ny instans av klassen [Metafile](../../com.aspose.drawing.imaging/metafile) från det angivna filnamnet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filename | java.lang.String | En sträng som representerar filnamnet från vilket den nya [Metafile](../../com.aspose.drawing.imaging/metafile) ska skapas. |
| referenceHdc | byte[] | Ett Windows-handtag till ett enhetssammanhang. |

### Metafile(InputStream stream) {#Metafile-java.io.InputStream-}
```
public Metafile(InputStream stream)
```


Initierar en ny instans av klassen [Metafile](../../com.aspose.drawing.imaging/metafile) från den angivna datastreamen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | java.io.InputStream | InputStreamen från vilken den nya [Metafile](../../com.aspose.drawing.imaging/metafile) ska skapas. |

### Metafile(InputStream stream, byte[] referenceHdc) {#Metafile-java.io.InputStream-byte---}
```
public Metafile(InputStream stream, byte[] referenceHdc)
```


Initierar en ny instans av klassen [Metafile](../../com.aspose.drawing.imaging/metafile) från den angivna datastreamen och ett Windows-handtag till ett enhetssammanhang. />.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | java.io.InputStream | En InputStream som innehåller data för denna [Metafile](../../com.aspose.drawing.imaging/metafile). |
| referenceHdc | byte[] | Ett Windows-handtag till ett enhetssammanhang för [Metafile](../../com.aspose.drawing.imaging/metafile)-objektet. |

### Metafile(System.IO.Stream stream, int type) {#Metafile-com.aspose.ms.System.IO.Stream-int-}
```
public Metafile(System.IO.Stream stream, int type)
```


Initierar en ny instans av klassen [Metafile](../../com.aspose.drawing.imaging/metafile) från den angivna datastreamen och ett Windows-handtag till ett enhetssammanhang. />.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | En InputStream som innehåller data för denna [Metafile](../../com.aspose.drawing.imaging/metafile). |
| type | int | måste vara int 1. |

### Metafile(InputStream stream, byte[] referenceHdc, int type) {#Metafile-java.io.InputStream-byte---int-}
```
public Metafile(InputStream stream, byte[] referenceHdc, int type)
```


Initierar en ny instans av klassen [Metafile](../../com.aspose.drawing.imaging/metafile) från den angivna datastreamen, ett Windows-handtag till en enhetskontext och en [EmfType](../../com.aspose.drawing.imaging/emftype)-enumeration som specificerar formatet för [Metafile](../../com.aspose.drawing.imaging/metafile).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | java.io.InputStream | En InputStream som innehåller data för denna [Metafile](../../com.aspose.drawing.imaging/metafile). |
| referenceHdc | byte[] | Ett Windows-handtag till ett enhetssammanhang. |
| type | int | En [EmfType](../../com.aspose.drawing.imaging/emftype) som specificerar formatet för [Metafile](../../com.aspose.drawing.imaging/metafile). |

### Metafile(InputStream stream, byte[] referenceHdc, RectangleF frameRect, int frameUnit, int type) {#Metafile-java.io.InputStream-byte---com.aspose.drawing.RectangleF-int-int-}
```
public Metafile(InputStream stream, byte[] referenceHdc, RectangleF frameRect, int frameUnit, int type)
```


Initierar en ny instans av klassen [Metafile](../../com.aspose.drawing.imaging/metafile) från den angivna datastreamen, ett Windows-handtag till en enhetskontext och en [EmfType](../../com.aspose.drawing.imaging/emftype)-enumeration som specificerar formatet för [Metafile](../../com.aspose.drawing.imaging/metafile).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | java.io.InputStream | En InputStream som innehåller data för denna [Metafile](../../com.aspose.drawing.imaging/metafile). |
| referenceHdc | byte[] | Ett Windows-handtag till ett enhetssammanhang. |
| frameRect | [RectangleF](../../com.aspose.drawing/rectanglef) | En [Rectangle](../../com.aspose.drawing/rectangle) som representerar rektangeln som avgränsar den nya [Metafile](../../com.aspose.drawing.imaging/metafile). |
| frameUnit | int | En [MetafileFrameUnit](../../com.aspose.drawing.imaging/metafileframeunit) som specificerar måttenheten för frameRect. |
| type | int | En [EmfType](../../com.aspose.drawing.imaging/emftype) som specificerar formatet för [Metafile](../../com.aspose.drawing.imaging/metafile). |

### getWidth() {#getWidth--}
```
public int getWidth()
```


Hämtar bredden, i pixlar, för denna [Metafile](../../com.aspose.drawing.imaging/metafile).

**Returns:**
int
### getHeight() {#getHeight--}
```
public int getHeight()
```


Hämtar höjden, i pixlar, för denna [Metafile](../../com.aspose.drawing.imaging/metafile).

**Returns:**
int - höjden, i pixlar, för denna [Metafile](../../com.aspose.drawing.imaging/metafile).
### getRawFormat() {#getRawFormat--}
```
public ImageFormat getRawFormat()
```


Hämtar filformatet för denna [Image](../../com.aspose.drawing/image).

**Returns:**
[ImageFormat](../../com.aspose.drawing.imaging/imageformat) - The [ImageFormat](../../com.aspose.drawing.imaging/imageformat) that represents the file format of this [Image](../../com.aspose.drawing/image).
### getPixelFormat() {#getPixelFormat--}
```
public int getPixelFormat()
```


Hämtar pixelformatet för denna [Image](../../com.aspose.drawing/image).

**Returns:**
int - En `PixelFormat`([Image.getPixelFormat](../../com.aspose.drawing/image\#getPixelFormat)) som representerar pixelformatet för denna [Image](../../com.aspose.drawing/image).
### getPalette() {#getPalette--}
```
public ColorPalette getPalette()
```


Hämtar eller anger färgpaletten som används för denna [Image](../../com.aspose.drawing/image).

**Returns:**
[ColorPalette](../../com.aspose.drawing.imaging/colorpalette) - A [ColorPalette](../../com.aspose.drawing.imaging/colorpalette) that represents the color palette used for this [Image](../../com.aspose.drawing/image).
### setPalette(ColorPalette value) {#setPalette-com.aspose.drawing.imaging.ColorPalette-}
```
public void setPalette(ColorPalette value)
```


Hämtar eller anger färgpaletten som används för denna [Image](../../com.aspose.drawing/image).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [ColorPalette](../../com.aspose.drawing.imaging/colorpalette) |  |

### getFrameDimensionsList() {#getFrameDimensionsList--}
```
public UUID[] getFrameDimensionsList()
```


Hämtar en array av GUID:er som representerar dimensionerna för ramar inom denna [Image](../../com.aspose.drawing/image).

**Returns:**
java.util.UUID[] - En array av GUID:er som specificerar dimensionerna för ramar inom denna [Image](../../com.aspose.drawing/image) från mest signifikant till minst signifikant.
### getPropertyIdList() {#getPropertyIdList--}
```
public int[] getPropertyIdList()
```


Hämtar ID:n för egenskapsobjekten som lagras i denna [Image](../../com.aspose.drawing/image).

**Returns:**
int[] - En array av egenskaps‑ID:n, en för varje egenskapselement som lagras i denna bild.
### getPropertyItems() {#getPropertyItems--}
```
public PropertyItem[] getPropertyItems()
```


Hämtar alla egenskapsobjekt (metadata) som lagras i denna [Image](../../com.aspose.drawing/image).

**Returns:**
com.aspose.drawing.imaging.PropertyItem[] - En array av [PropertyItem](../../com.aspose.drawing.imaging/propertyitem)‑objekt, ett för varje egenskapselement som lagras i bilden.
### getMetafileHeader(InputStream stream) {#getMetafileHeader-java.io.InputStream-}
```
public static MetafileHeader getMetafileHeader(InputStream stream)
```


Returnerar [MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) som är associerad med den angivna [Metafile](../../com.aspose.drawing.imaging/metafile).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | java.io.InputStream | En InputStream som innehåller [Metafile](../../com.aspose.drawing.imaging/metafile) för vilken ett huvud hämtas. |

**Returns:**
[MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) - The [MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) associated with the specified [Metafile](../../com.aspose.drawing.imaging/metafile).
### getMetafileHeader(String fileName) {#getMetafileHeader-java.lang.String-}
```
public static MetafileHeader getMetafileHeader(String fileName)
```


Returnerar [MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) som är associerad med den angivna [Metafile](../../com.aspose.drawing.imaging/metafile).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fileName | java.lang.String | En sträng som innehåller namnet på [Metafile](../../com.aspose.drawing.imaging/metafile) för vilken ett huvud hämtas. |

**Returns:**
[MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) - The [MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) associated with the specified [Metafile](../../com.aspose.drawing.imaging/metafile).
### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


Denna metod roterar, vänder eller roterar och vänder [Image](../../com.aspose.drawing/image).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rotateFlipType | int | En [RotateFlipType](../../com.aspose.drawing/rotatefliptype)‑medlem som specificerar vilken typ av rotation och vändning som ska tillämpas på bilden. |

### getHenhmetafile() {#getHenhmetafile--}
```
public System.IntPtr getHenhmetafile()
```


Returnerar ett Windows-handtag till en förbättrad [Metafile](../../com.aspose.drawing.imaging/metafile).

**Returns:**
com.aspose.ms.System.IntPtr - Ett Windows-handtag till denna förbättrade [Metafile](../../com.aspose.drawing.imaging/metafile).
### playRecord(int recordType, int flags, int dataSize, byte[] dataArray) {#playRecord-int-int-int-byte---}
```
public void playRecord(int recordType, int flags, int dataSize, byte[] dataArray)
```


Spelar upp en enskild metafilpost.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| recordType | int | Element av [EmfPlusRecordType](../../com.aspose.drawing.imaging/emfplusrecordtype) som specificerar typen av metafilpost som spelas upp. |
| flaggor | int | En uppsättning flaggor som specificerar attribut för posten. |
| datastorlek | int | Antalet byte i postdata. |
| dataArray | byte[] | En array av byte som innehåller postdata. |

### getMetafileHeader() {#getMetafileHeader--}
```
public MetafileHeader getMetafileHeader()
```


Returnerar [MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) som är associerad med denna [Metafile](../../com.aspose.drawing.imaging/metafile).

**Returns:**
[MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) - The [MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) associated with this [Metafile](../../com.aspose.drawing.imaging/metafile).
### getPropertyItem(int propid) {#getPropertyItem-int-}
```
public PropertyItem getPropertyItem(int propid)
```


Hämtar det angivna egenskapsobjektet från denna [Image](../../com.aspose.drawing/image).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| propid | int | ID för egenskapselementet som ska hämtas. |

**Returns:**
[PropertyItem](../../com.aspose.drawing.imaging/propertyitem) - The [PropertyItem](../../com.aspose.drawing.imaging/propertyitem) this method gets.
### removePropertyItem(int propid) {#removePropertyItem-int-}
```
public void removePropertyItem(int propid)
```


Tar bort det angivna egenskapsobjektet från denna [Image](../../com.aspose.drawing/image).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| propid | int | ID för egenskapselementet som ska tas bort. |

### setPropertyItem(PropertyItem propitem) {#setPropertyItem-com.aspose.drawing.imaging.PropertyItem-}
```
public void setPropertyItem(PropertyItem propitem)
```


Lagrar ett egenskapsobjekt (metadata) i denna [Image](../../com.aspose.drawing/image).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| propitem | [PropertyItem](../../com.aspose.drawing.imaging/propertyitem) | Den [PropertyItem](../../com.aspose.drawing.imaging/propertyitem) som ska lagras. |

