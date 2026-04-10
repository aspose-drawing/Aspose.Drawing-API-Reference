---
title: Bitmap
second_title: Riferimento API di Aspose.Drawing per Java
description: Incapsula un bitmap che consiste nei dati pixel per un'immagine grafica e nei suoi attributi.
type: docs
weight: 10
url: /it/java/com.aspose.drawing/bitmap/
---
**Inheritance:**
java.lang.Object, [com.aspose.drawing.Image](../../com.aspose.drawing/image)
```
public class Bitmap extends Image
```

Incapsula un bitmap, che consiste nei dati pixel per un'immagine grafica e nei suoi attributi. Un [Bitmap](../../com.aspose.drawing/bitmap) è un oggetto usato per lavorare con immagini definite da dati pixel.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Bitmap(int width, int height)](#Bitmap-int-int-) | Inizializza una nuova istanza della classe [Bitmap](../../com.aspose.drawing/bitmap) con la dimensione specificata. |
| [Bitmap(String filename)](#Bitmap-java.lang.String-) | Inizializza una nuova istanza della classe [Bitmap](../../com.aspose.drawing/bitmap) dal file specificato. |
| [Bitmap(String filename, boolean useIcm)](#Bitmap-java.lang.String-boolean-) | Inizializza una nuova istanza della classe [Bitmap](../../com.aspose.drawing/bitmap) dal file specificato. |
| [Bitmap(InputStream stream)](#Bitmap-java.io.InputStream-) | Inizializza una nuova istanza della classe [Bitmap](../../com.aspose.drawing/bitmap) dal flusso di dati specificato. |
| [Bitmap(InputStream stream, boolean useIcm)](#Bitmap-java.io.InputStream-boolean-) | Inizializza una nuova istanza della classe [Bitmap](../../com.aspose.drawing/bitmap) dal flusso di dati specificato. |
| [Bitmap(int width, int height, int format)](#Bitmap-int-int-int-) | Inizializza una nuova istanza della classe [Bitmap](../../com.aspose.drawing/bitmap) con la dimensione e il formato specificati. |
| [Bitmap(int width, int height, int stride, int format, int[] data)](#Bitmap-int-int-int-int-int---) | Inizializza una nuova istanza della classe [Bitmap](../../com.aspose.drawing/bitmap) con la dimensione e i dati pixel specificati. |
| [Bitmap(Image original)](#Bitmap-com.aspose.drawing.Image-) | Inizializza una nuova istanza della classe [Bitmap](../../com.aspose.drawing/bitmap) dall'immagine esistente specificata. |
| [Bitmap(Image original, Size newSize)](#Bitmap-com.aspose.drawing.Image-com.aspose.drawing.Size-) | Inizializza una nuova istanza della classe [Bitmap](../../com.aspose.drawing/bitmap) dall'immagine esistente specificata, scalata alla dimensione specificata. |
| [Bitmap(Image original, int width, int height)](#Bitmap-com.aspose.drawing.Image-int-int-) | Inizializza una nuova istanza della classe [Bitmap](../../com.aspose.drawing/bitmap) dall'immagine esistente specificata, scalata alla dimensione specificata. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getWidth()](#getWidth--) | Restituisce la larghezza, in pixel, di questo Bitmap. |
| [getHeight()](#getHeight--) | Restituisce l'altezza, in pixel, di questo Bitmap. |
| [getRawFormat()](#getRawFormat--) | Restituisce il formato file di questa [Image](../../com.aspose.drawing/image). |
| [getPixelFormat()](#getPixelFormat--) | Restituisce il formato pixel di questa [Image](../../com.aspose.drawing/image). |
| [getPalette()](#getPalette--) | Ottiene o imposta la tavolozza dei colori utilizzata per questa [Image](../../com.aspose.drawing/image). |
| [setPalette(ColorPalette value)](#setPalette-com.aspose.drawing.imaging.ColorPalette-) | Ottiene o imposta la tavolozza dei colori utilizzata per questa [Image](../../com.aspose.drawing/image). |
| [getFrameDimensionsList()](#getFrameDimensionsList--) | Restituisce un array di GUID che rappresentano le dimensioni dei fotogrammi all'interno di questa [Image](../../com.aspose.drawing/image). |
| [getPropertyIdList()](#getPropertyIdList--) | Restituisce gli ID degli elementi di proprietà memorizzati in questa [Image](../../com.aspose.drawing/image). |
| [getPropertyItems()](#getPropertyItems--) | Restituisce tutti gli elementi di proprietà (pezzi di metadati) memorizzati in questa [Image](../../com.aspose.drawing/image). |
| [deepClone(Rectangle rect, int format)](#deepClone-com.aspose.drawing.Rectangle-int-) | Crea una copia della sezione di questo [Bitmap](../../com.aspose.drawing/bitmap) definita dalla struttura [Rectangle](../../com.aspose.drawing/rectangle) e con un `PixelFormat`([Image.getPixelFormat](../../com.aspose.drawing/image\#getPixelFormat)) specificato. |
| [deepClone(RectangleF rect, int format)](#deepClone-com.aspose.drawing.RectangleF-int-) | Crea una copia della sezione di questo [Bitmap](../../com.aspose.drawing/bitmap) definita con una enumerazione [PixelFormat](../../com.aspose.drawing.imaging/pixelformat) specificata. |
| [setResolution(float xDpi, float yDpi)](#setResolution-float-float-) | Imposta la risoluzione per questo [Bitmap](../../com.aspose.drawing/bitmap). |
| [lockBits(Rectangle rect, int flags, int format)](#lockBits-com.aspose.drawing.Rectangle-int-int-) | Blocca un [Bitmap](../../com.aspose.drawing/bitmap) nella memoria di sistema. |
| [unlockBits(BitmapData bitmapData)](#unlockBits-com.aspose.drawing.imaging.BitmapData-) | Sblocca questo [Bitmap](../../com.aspose.drawing/bitmap) dalla memoria di sistema. |
| [getPixel(int x, int y)](#getPixel-int-int-) | Ottiene il colore del pixel specificato in questo [Bitmap](../../com.aspose.drawing/bitmap). |
| [setPixel(int x, int y, Color color)](#setPixel-int-int-com.aspose.drawing.Color-) | Imposta il colore del pixel specificato in questo [Bitmap](../../com.aspose.drawing/bitmap). |
| [readArgb32Pixels(int[] pixels)](#readArgb32Pixels-int---) | Legge i pixel del bitmap in formato ARGB32 nell'array fornito. |
| [writeArgb32Pixels(int[] pixels)](#writeArgb32Pixels-int---) | Scrive i pixel nel bitmap. |
| [makeTransparent()](#makeTransparent--) | Rende trasparente il colore specificato per questo [Bitmap](../../com.aspose.drawing/bitmap). |
| [makeTransparent(Color transparentColor)](#makeTransparent-com.aspose.drawing.Color-) | Rende trasparente il colore specificato per questo [Bitmap](../../com.aspose.drawing/bitmap). |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | Questo metodo ruota, capovolge o ruota e capovolge l'[Image](../../com.aspose.drawing/image). |
| [getPropertyItem(int propid)](#getPropertyItem-int-) | Restituisce l'elemento di proprietà specificato da questa [Image](../../com.aspose.drawing/image). |
| [removePropertyItem(int propid)](#removePropertyItem-int-) | Rimuove l'elemento di proprietà specificato da questa [Image](../../com.aspose.drawing/image). |
| [setPropertyItem(PropertyItem propitem)](#setPropertyItem-com.aspose.drawing.imaging.PropertyItem-) | Memorizza un elemento di proprietà (pezzo di metadati) in questa [Image](../../com.aspose.drawing/image). |
### Bitmap(int width, int height) {#Bitmap-int-int-}
```
public Bitmap(int width, int height)
```


Inizializza una nuova istanza della classe [Bitmap](../../com.aspose.drawing/bitmap) con la dimensione specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| width | int | La larghezza, in pixel, del nuovo Bitmap. |
|  | height | int | L'altezza, in pixel, del nuovo Bitmap. |

--------------------

L'unico formato interno di bitmap supportato al momento è equivalente a `PixelFormat.Format32bppPArgb`. |

### Bitmap(String filename) {#Bitmap-java.lang.String-}
```
public Bitmap(String filename)
```


Inizializza una nuova istanza della classe [Bitmap](../../com.aspose.drawing/bitmap) dal file specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| nomefile | java.lang.String | Il nome del file bitmap. |

### Bitmap(String filename, boolean useIcm) {#Bitmap-java.lang.String-boolean-}
```
public Bitmap(String filename, boolean useIcm)
```


Inizializza una nuova istanza della classe [Bitmap](../../com.aspose.drawing/bitmap) dal file specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| nomefile | java.lang.String | Il nome del file bitmap. |
| useIcm | boolean | true per utilizzare la correzione del colore per questo [Bitmap](../../com.aspose.drawing/bitmap); altrimenti, false. |

### Bitmap(InputStream stream) {#Bitmap-java.io.InputStream-}
```
public Bitmap(InputStream stream)
```


Inizializza una nuova istanza della classe [Bitmap](../../com.aspose.drawing/bitmap) dal flusso di dati specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| flusso | java.io.InputStream | Il flusso di dati utilizzato per caricare l'immagine. |

### Bitmap(InputStream stream, boolean useIcm) {#Bitmap-java.io.InputStream-boolean-}
```
public Bitmap(InputStream stream, boolean useIcm)
```


Inizializza una nuova istanza della classe [Bitmap](../../com.aspose.drawing/bitmap) dal flusso di dati specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| flusso | java.io.InputStream | Il flusso di dati utilizzato per caricare l'immagine. |
| useIcm | boolean | `true` per utilizzare la correzione del colore per questo [Bitmap](../../com.aspose.drawing/bitmap); altrimenti, `false`. |

### Bitmap(int width, int height, int format) {#Bitmap-int-int-int-}
```
public Bitmap(int width, int height, int format)
```


Inizializza una nuova istanza della classe [Bitmap](../../com.aspose.drawing/bitmap) con la dimensione e il formato specificati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| width | int | La larghezza, in pixel, del nuovo [Bitmap](../../com.aspose.drawing/bitmap). |
| height | int | L'altezza, in pixel, del nuovo [Bitmap](../../com.aspose.drawing/bitmap). |
| format | int | L'enumerazione `PixelFormat`([Image.getPixelFormat](../../com.aspose.drawing/image\#getPixelFormat)) per il nuovo [Bitmap](../../com.aspose.drawing/bitmap). |

### Bitmap(int width, int height, int stride, int format, int[] data) {#Bitmap-int-int-int-int-int---}
```
public Bitmap(int width, int height, int stride, int format, int[] data)
```


Inizializza una nuova istanza della classe [Bitmap](../../com.aspose.drawing/bitmap) con la dimensione e i dati pixel specificati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| width | int | La larghezza, in pixel, del nuovo [Bitmap](../../com.aspose.drawing/bitmap). |
| height | int | L'altezza, in pixel, del nuovo [Bitmap](../../com.aspose.drawing/bitmap). |
| stride | int | L'offset in byte tra l'inizio di una riga di scansione e la successiva, deve essere un multiplo di quattro. |
| format | int | L'enumerazione `PixelFormat`([Image.getPixelFormat](../../com.aspose.drawing/image\#getPixelFormat)) per il nuovo [Bitmap](../../com.aspose.drawing/bitmap). |
| dati | int[] | I dati dei pixel. |

### Bitmap(Image original) {#Bitmap-com.aspose.drawing.Image-}
```
public Bitmap(Image original)
```


Inizializza una nuova istanza della classe [Bitmap](../../com.aspose.drawing/bitmap) dall'immagine esistente specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| original | [Image](../../com.aspose.drawing/image) | L'[Image](../../com.aspose.drawing/image) da cui creare il nuovo [Bitmap](../../com.aspose.drawing/bitmap). |

### Bitmap(Image original, Size newSize) {#Bitmap-com.aspose.drawing.Image-com.aspose.drawing.Size-}
```
public Bitmap(Image original, Size newSize)
```


Inizializza una nuova istanza della classe [Bitmap](../../com.aspose.drawing/bitmap) dall'immagine esistente specificata, scalata alla dimensione specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| original | [Image](../../com.aspose.drawing/image) | L'[Image](../../com.aspose.drawing/image) da cui creare il nuovo [Bitmap](../../com.aspose.drawing/bitmap) |
| newSize | [Size](../../com.aspose.drawing/size) | La struttura `Size`([Image.getSize](../../com.aspose.drawing/image\#getSize)) che rappresenta le dimensioni del nuovo [Bitmap](../../com.aspose.drawing/bitmap). |

### Bitmap(Image original, int width, int height) {#Bitmap-com.aspose.drawing.Image-int-int-}
```
public Bitmap(Image original, int width, int height)
```


Inizializza una nuova istanza della classe [Bitmap](../../com.aspose.drawing/bitmap) dall'immagine esistente specificata, scalata alla dimensione specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| original | [Image](../../com.aspose.drawing/image) | L'[Image](../../com.aspose.drawing/image) da cui creare il nuovo [Bitmap](../../com.aspose.drawing/bitmap). |
| width | int | La larghezza, in pixel, del nuovo [Bitmap](../../com.aspose.drawing/bitmap). |
| height | int | L'altezza, in pixel, del nuovo [Bitmap](../../com.aspose.drawing/bitmap). |

### getWidth() {#getWidth--}
```
public int getWidth()
```


Restituisce la larghezza, in pixel, di questo Bitmap.

**Returns:**
int
### getHeight() {#getHeight--}
```
public int getHeight()
```


Restituisce l'altezza, in pixel, di questo Bitmap.

**Returns:**
int
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
### deepClone(Rectangle rect, int format) {#deepClone-com.aspose.drawing.Rectangle-int-}
```
public final Bitmap deepClone(Rectangle rect, int format)
```


Crea una copia della sezione di questo [Bitmap](../../com.aspose.drawing/bitmap) definita dalla struttura [Rectangle](../../com.aspose.drawing/rectangle) e con un `PixelFormat`([Image.getPixelFormat](../../com.aspose.drawing/image\#getPixelFormat)) specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | Definisce la porzione di questo [Bitmap](../../com.aspose.drawing/bitmap) da copiare. Le coordinate sono relative a questo [Bitmap](../../com.aspose.drawing/bitmap). |
| format | int | Specifica l'enumerazione `PixelFormat`([Image.getPixelFormat](../../com.aspose.drawing/image\#getPixelFormat)) per il [Bitmap](../../com.aspose.drawing/bitmap) di destinazione. |

**Returns:**
[Bitmap](../../com.aspose.drawing/bitmap) - The new [Bitmap](../../com.aspose.drawing/bitmap) that this method creates.
### deepClone(RectangleF rect, int format) {#deepClone-com.aspose.drawing.RectangleF-int-}
```
public final Bitmap deepClone(RectangleF rect, int format)
```


Crea una copia della sezione di questo [Bitmap](../../com.aspose.drawing/bitmap) definita con una enumerazione [PixelFormat](../../com.aspose.drawing.imaging/pixelformat) specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | Definisce la porzione di questo [Bitmap](../../com.aspose.drawing/bitmap) da copiare. |
| format | int | Specifica l'enumerazione [PixelFormat](../../com.aspose.drawing.imaging/pixelformat) per il [Bitmap](../../com.aspose.drawing/bitmap) di destinazione. |

**Returns:**
[Bitmap](../../com.aspose.drawing/bitmap) - The [Bitmap](../../com.aspose.drawing/bitmap) that this method creates.
### setResolution(float xDpi, float yDpi) {#setResolution-float-float-}
```
public final void setResolution(float xDpi, float yDpi)
```


Imposta la risoluzione per questo [Bitmap](../../com.aspose.drawing/bitmap).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| xDpi | float | La risoluzione orizzontale, in punti per pollice, del [Bitmap](../../com.aspose.drawing/bitmap). |
| yDpi | float | La risoluzione verticale, in punti per pollice, del [Bitmap](../../com.aspose.drawing/bitmap). |

### lockBits(Rectangle rect, int flags, int format) {#lockBits-com.aspose.drawing.Rectangle-int-int-}
```
public final BitmapData lockBits(Rectangle rect, int flags, int format)
```


Blocca un [Bitmap](../../com.aspose.drawing/bitmap) nella memoria di sistema.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | Una struttura [Rectangle](../../com.aspose.drawing/rectangle) che specifica la porzione del [Bitmap](../../com.aspose.drawing/bitmap) da bloccare. |
| flags | int | Un'enumerazione [ImageLockMode](../../com.aspose.drawing.imaging/imagelockmode) che specifica il livello di accesso (lettura/scrittura) per il [Bitmap](../../com.aspose.drawing/bitmap). |
| format | int | Un'enumerazione `PixelFormat`([Image.getPixelFormat](../../com.aspose.drawing/image\#getPixelFormat)) che specifica il formato dei dati di questo [Bitmap](../../com.aspose.drawing/bitmap). |

**Returns:**
[BitmapData](../../com.aspose.drawing.imaging/bitmapdata) - A [BitmapData](../../com.aspose.drawing.imaging/bitmapdata) containing information about this lock operation.
### unlockBits(BitmapData bitmapData) {#unlockBits-com.aspose.drawing.imaging.BitmapData-}
```
public final void unlockBits(BitmapData bitmapData)
```


Sblocca questo [Bitmap](../../com.aspose.drawing/bitmap) dalla memoria di sistema.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| bitmapData | [BitmapData](../../com.aspose.drawing.imaging/bitmapdata) | Un [BitmapData](../../com.aspose.drawing.imaging/bitmapdata) che specifica le informazioni sull'operazione di blocco. |

### getPixel(int x, int y) {#getPixel-int-int-}
```
public final Color getPixel(int x, int y)
```


Ottiene il colore del pixel specificato in questo [Bitmap](../../com.aspose.drawing/bitmap).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | int | La coordinata x del pixel da recuperare. |
| y | int | La coordinata y del pixel da recuperare. |

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) structure that represents the color of the specified pixel.
### setPixel(int x, int y, Color color) {#setPixel-int-int-com.aspose.drawing.Color-}
```
public final void setPixel(int x, int y, Color color)
```


Imposta il colore del pixel specificato in questo [Bitmap](../../com.aspose.drawing/bitmap).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | int | La coordinata x del pixel da impostare. |
| y | int | La coordinata y del pixel da impostare. |
| color | [Color](../../com.aspose.drawing/color) | Una struttura [Color](../../com.aspose.drawing/color) che rappresenta il colore da assegnare al pixel specificato. |

### readArgb32Pixels(int[] pixels) {#readArgb32Pixels-int---}
```
public final void readArgb32Pixels(int[] pixels)
```


Legge i pixel del bitmap in formato ARGB32 nell'array fornito.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pixel | int[] | Array per inserire i pixel del bitmap. Deve avere capacità sufficiente. |

### writeArgb32Pixels(int[] pixels) {#writeArgb32Pixels-int---}
```
public final void writeArgb32Pixels(int[] pixels)
```


Scrive i pixel nel bitmap.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pixel | int[] | Array con i pixel di origine in formato ARGB32. Deve avere lunghezza sufficiente. |

### makeTransparent() {#makeTransparent--}
```
public final void makeTransparent()
```


Rende trasparente il colore specificato per questo [Bitmap](../../com.aspose.drawing/bitmap).

### makeTransparent(Color transparentColor) {#makeTransparent-com.aspose.drawing.Color-}
```
public final void makeTransparent(Color transparentColor)
```


Rende trasparente il colore specificato per questo [Bitmap](../../com.aspose.drawing/bitmap).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| transparentColor | [Color](../../com.aspose.drawing/color) | La struttura [Color](../../com.aspose.drawing/color) che rappresenta il colore da rendere trasparente. |

### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


Questo metodo ruota, capovolge o ruota e capovolge l'[Image](../../com.aspose.drawing/image).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rotateFlipType | int | Un membro [RotateFlipType](../../com.aspose.drawing/rotatefliptype) che specifica il tipo di rotazione e ribaltamento da applicare all'immagine. |

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

