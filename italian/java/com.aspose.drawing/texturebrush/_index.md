---
title: TextureBrush
second_title: Riferimento API di Aspose.Drawing per Java
description: Ogni proprietà della classe TextureBrush è un oggetto Brush che utilizza un'immagine per riempire l'interno di una forma.
type: docs
weight: 53
url: /it/java/com.aspose.drawing/texturebrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.drawing.Brush](../../com.aspose.drawing/brush)
```
public final class TextureBrush extends Brush
```

Ogni proprietà della classe TextureBrush è un oggetto Brush che utilizza un'immagine per riempire l'interno di una forma. Questa classe non può essere ereditata.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [TextureBrush(Image bitmap)](#TextureBrush-com.aspose.drawing.Image-) | Inizializza una nuova istanza della classe [TextureBrush](../../com.aspose.drawing/texturebrush) che utilizza l'immagine specificata. |
| [TextureBrush(Image image, int wrapMode)](#TextureBrush-com.aspose.drawing.Image-int-) | Inizializza una nuova istanza della classe [TextureBrush](../../com.aspose.drawing/texturebrush) che utilizza l'immagine specificata e la modalità di avvolgimento. |
| [TextureBrush(Image image, int wrapMode, RectangleF dstRect)](#TextureBrush-com.aspose.drawing.Image-int-com.aspose.drawing.RectangleF-) | Inizializza una nuova istanza della classe [TextureBrush](../../com.aspose.drawing/texturebrush) che utilizza l'immagine specificata, la modalità di avvolgimento e il rettangolo di delimitazione. |
| [TextureBrush(Image image, RectangleF dstRect)](#TextureBrush-com.aspose.drawing.Image-com.aspose.drawing.RectangleF-) | Inizializza una nuova istanza della classe [TextureBrush](../../com.aspose.drawing/texturebrush) che utilizza l'immagine specificata e il rettangolo di delimitazione. |
| [TextureBrush(Image image, RectangleF dstRect, ImageAttributes imageAttr)](#TextureBrush-com.aspose.drawing.Image-com.aspose.drawing.RectangleF-com.aspose.drawing.imaging.ImageAttributes-) | Inizializza una nuova istanza della classe [TextureBrush](../../com.aspose.drawing/texturebrush) che utilizza l'immagine specificata, il rettangolo di delimitazione e gli attributi dell'immagine. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getImage()](#getImage--) | Restituisce l'oggetto Image associato a questo oggetto TextureBrush. |
| [getTransform()](#getTransform--) | Restituisce una copia dell'oggetto Matrix che definisce una trasformazione geometrica locale per l'immagine associata a questo oggetto TextureBrush. |
| [setTransform(Matrix value)](#setTransform-com.aspose.drawing.drawing2d.Matrix-) | Imposta una copia dell'oggetto Matrix che definisce una trasformazione geometrica locale per l'immagine associata a questo oggetto TextureBrush. |
| [getWrapMode()](#getWrapMode--) | Restituisce un'enumerazione WrapMode che indica la modalità di avvolgimento per questo oggetto TextureBrush. |
| [setWrapMode(int value)](#setWrapMode-int-) | Imposta un'enumerazione WrapMode che indica la modalità di avvolgimento per questo oggetto TextureBrush. |
| [deepClone()](#deepClone--) | Crea una copia esatta di questo oggetto [TextureBrush](../../com.aspose.drawing/texturebrush). |
| [resetTransform()](#resetTransform--) | Reimposta la proprietà Transform di questo oggetto [TextureBrush](../../com.aspose.drawing/texturebrush) all'identità. |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-) | Moltiplica l'oggetto [Matrix](../../com.aspose.drawing.drawing2d/matrix) che rappresenta la trasformazione geometrica locale di questo oggetto [TextureBrush](../../com.aspose.drawing/texturebrush) per l'oggetto [Matrix](../../com.aspose.drawing.drawing2d/matrix) specificato, anteponendo l'oggetto [Matrix](../../com.aspose.drawing.drawing2d/matrix) specificato. |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-int-) | Moltiplica l'oggetto [Matrix](../../com.aspose.drawing.drawing2d/matrix) che rappresenta la trasformazione geometrica locale di questo oggetto [TextureBrush](../../com.aspose.drawing/texturebrush) per l'oggetto [Matrix](../../com.aspose.drawing.drawing2d/matrix) specificato nell'ordine specificato. |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | Trasla la trasformazione geometrica locale di questo oggetto [TextureBrush](../../com.aspose.drawing/texturebrush) delle dimensioni specificate. |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | Trasla la trasformazione geometrica locale di questo oggetto [TextureBrush](../../com.aspose.drawing/texturebrush) delle dimensioni specificate nell'ordine specificato. |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | Scala la trasformazione geometrica locale di questo oggetto [TextureBrush](../../com.aspose.drawing/texturebrush) delle quantità specificate. |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | Scala la trasformazione geometrica locale di questo oggetto [TextureBrush](../../com.aspose.drawing/texturebrush) delle quantità specificate nell'ordine specificato. |
| [rotateTransform(float angle)](#rotateTransform-float-) | Ruota la trasformazione geometrica locale di questo oggetto [TextureBrush](../../com.aspose.drawing/texturebrush) dell'angolo specificato. |
| [rotateTransform(float angle, int order)](#rotateTransform-float-int-) | Ruota la trasformazione geometrica locale di questo oggetto [TextureBrush](../../com.aspose.drawing/texturebrush) dell'angolo specificato nell'ordine specificato. |
### TextureBrush(Image bitmap) {#TextureBrush-com.aspose.drawing.Image-}
```
public TextureBrush(Image bitmap)
```


Inizializza una nuova istanza della classe [TextureBrush](../../com.aspose.drawing/texturebrush) che utilizza l'immagine specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| bitmap | [Image](../../com.aspose.drawing/image) | L'oggetto `Image`([.getImage](../../null/\#getImage)) con cui questo oggetto [TextureBrush](../../com.aspose.drawing/texturebrush) riempie gli interni. |

### TextureBrush(Image image, int wrapMode) {#TextureBrush-com.aspose.drawing.Image-int-}
```
public TextureBrush(Image image, int wrapMode)
```


Inizializza una nuova istanza della classe [TextureBrush](../../com.aspose.drawing/texturebrush) che utilizza l'immagine specificata e la modalità di avvolgimento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| image | [Image](../../com.aspose.drawing/image) | L'immagine. |
| wrapMode | int | Un'enumerazione `WrapMode`([.getWrapMode](../../null/\#getWrapMode)/[.setWrapMode(int)](../../null/\#setWrapMode-int-)) che specifica come questo oggetto [TextureBrush](../../com.aspose.drawing/texturebrush) è tassellato. |

### TextureBrush(Image image, int wrapMode, RectangleF dstRect) {#TextureBrush-com.aspose.drawing.Image-int-com.aspose.drawing.RectangleF-}
```
public TextureBrush(Image image, int wrapMode, RectangleF dstRect)
```


Inizializza una nuova istanza della classe [TextureBrush](../../com.aspose.drawing/texturebrush) che utilizza l'immagine specificata, la modalità di avvolgimento e il rettangolo di delimitazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| image | [Image](../../com.aspose.drawing/image) | L'immagine. |
| wrapMode | int | Un'enumerazione `WrapMode`([.getWrapMode](../../null/\#getWrapMode)/[.setWrapMode(int)](../../null/\#setWrapMode-int-)) che specifica come questo oggetto [TextureBrush](../../com.aspose.drawing/texturebrush) è tassellato. |
| dstRect | [RectangleF](../../com.aspose.drawing/rectanglef) | Una struttura [RectangleF](../../com.aspose.drawing/rectanglef) che rappresenta il rettangolo di delimitazione per questo oggetto [TextureBrush](../../com.aspose.drawing/texturebrush). |

### TextureBrush(Image image, RectangleF dstRect) {#TextureBrush-com.aspose.drawing.Image-com.aspose.drawing.RectangleF-}
```
public TextureBrush(Image image, RectangleF dstRect)
```


Inizializza una nuova istanza della classe [TextureBrush](../../com.aspose.drawing/texturebrush) che utilizza l'immagine specificata e il rettangolo di delimitazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| image | [Image](../../com.aspose.drawing/image) | L'oggetto `Image`([.getImage](../../null/\#getImage)) con cui questo oggetto [TextureBrush](../../com.aspose.drawing/texturebrush) riempie gli interni. |
| dstRect | [RectangleF](../../com.aspose.drawing/rectanglef) | Una struttura [RectangleF](../../com.aspose.drawing/rectanglef) che rappresenta il rettangolo di delimitazione per questo oggetto [TextureBrush](../../com.aspose.drawing/texturebrush). |

### TextureBrush(Image image, RectangleF dstRect, ImageAttributes imageAttr) {#TextureBrush-com.aspose.drawing.Image-com.aspose.drawing.RectangleF-com.aspose.drawing.imaging.ImageAttributes-}
```
public TextureBrush(Image image, RectangleF dstRect, ImageAttributes imageAttr)
```


Inizializza una nuova istanza della classe [TextureBrush](../../com.aspose.drawing/texturebrush) che utilizza l'immagine specificata, il rettangolo di delimitazione e gli attributi dell'immagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| image | [Image](../../com.aspose.drawing/image) | L'oggetto Image con cui questo oggetto TextureBrush riempie gli interni. |
| dstRect | [RectangleF](../../com.aspose.drawing/rectanglef) | Una struttura RectangleF che rappresenta il rettangolo di delimitazione per questo oggetto TextureBrush. |
| imageAttr | [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes) | Un oggetto ImageAttributes che contiene informazioni aggiuntive sull'immagine utilizzata da questo oggetto TextureBrush. |

### getImage() {#getImage--}
```
public Image getImage()
```


Restituisce l'oggetto Image associato a questo oggetto TextureBrush.

**Returns:**
[Image](../../com.aspose.drawing/image) - the Image object associated with this TextureBrush object.
### getTransform() {#getTransform--}
```
public Matrix getTransform()
```


Restituisce una copia dell'oggetto Matrix che definisce una trasformazione geometrica locale per l'immagine associata a questo oggetto TextureBrush.

**Returns:**
[Matrix](../../com.aspose.drawing.drawing2d/matrix) - a copy of the Matrix object that defines a local geometric transformation for the image associated with this TextureBrush object.
### setTransform(Matrix value) {#setTransform-com.aspose.drawing.drawing2d.Matrix-}
```
public void setTransform(Matrix value)
```


Imposta una copia dell'oggetto Matrix che definisce una trasformazione geometrica locale per l'immagine associata a questo oggetto TextureBrush.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | una copia dell'oggetto Matrix che definisce una trasformazione geometrica locale per l'immagine associata a questo oggetto TextureBrush. |

### getWrapMode() {#getWrapMode--}
```
public int getWrapMode()
```


Restituisce un'enumerazione WrapMode che indica la modalità di avvolgimento per questo oggetto TextureBrush.

**Returns:**
int - un'enumerazione WrapMode che indica la modalità di avvolgimento per questo oggetto TextureBrush.
### setWrapMode(int value) {#setWrapMode-int-}
```
public void setWrapMode(int value)
```


Imposta un'enumerazione WrapMode che indica la modalità di avvolgimento per questo oggetto TextureBrush.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int | un'enumerazione WrapMode che indica la modalità di avvolgimento per questo oggetto TextureBrush. |

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Crea una copia esatta di questo oggetto [TextureBrush](../../com.aspose.drawing/texturebrush).

**Returns:**
java.lang.Object - L'oggetto [TextureBrush](../../com.aspose.drawing/texturebrush) che questo metodo crea, convertito in un oggetto Object.
### resetTransform() {#resetTransform--}
```
public void resetTransform()
```


Reimposta la proprietà Transform di questo oggetto [TextureBrush](../../com.aspose.drawing/texturebrush) all'identità.

### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-}
```
public void multiplyTransform(Matrix matrix)
```


Moltiplica l'oggetto [Matrix](../../com.aspose.drawing.drawing2d/matrix) che rappresenta la trasformazione geometrica locale di questo oggetto [TextureBrush](../../com.aspose.drawing/texturebrush) per l'oggetto [Matrix](../../com.aspose.drawing.drawing2d/matrix) specificato, anteponendo l'oggetto [Matrix](../../com.aspose.drawing.drawing2d/matrix) specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | L'oggetto [Matrix](../../com.aspose.drawing.drawing2d/matrix) con cui moltiplicare la trasformazione geometrica. |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-int-}
```
public void multiplyTransform(Matrix matrix, int order)
```


Moltiplica l'oggetto [Matrix](../../com.aspose.drawing.drawing2d/matrix) che rappresenta la trasformazione geometrica locale di questo oggetto [TextureBrush](../../com.aspose.drawing/texturebrush) per l'oggetto [Matrix](../../com.aspose.drawing.drawing2d/matrix) specificato nell'ordine specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | L'oggetto [Matrix](../../com.aspose.drawing.drawing2d/matrix) con cui moltiplicare la trasformazione geometrica. |
| order | int | Un'enumerazione [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder) che specifica l'ordine in cui moltiplicare le due matrici. |

### translateTransform(float dx, float dy) {#translateTransform-float-float-}
```
public void translateTransform(float dx, float dy)
```


Trasla la trasformazione geometrica locale di questo oggetto [TextureBrush](../../com.aspose.drawing/texturebrush) secondo le dimensioni specificate. Questo metodo antepone la traslazione alla trasformazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dx | float | La dimensione con cui traslare la trasformazione nella direzione x. |
| dy | float | La dimensione con cui traslare la trasformazione nella direzione y. |

### translateTransform(float dx, float dy, int order) {#translateTransform-float-float-int-}
```
public void translateTransform(float dx, float dy, int order)
```


Trasla la trasformazione geometrica locale di questo oggetto [TextureBrush](../../com.aspose.drawing/texturebrush) delle dimensioni specificate nell'ordine specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dx | float | La dimensione con cui traslare la trasformazione nella direzione x. |
| dy | float | La dimensione con cui traslare la trasformazione nella direzione y. |
| ordine | int | L'ordine (anteporre o aggiungere) con cui applicare la traslazione. |

### scaleTransform(float sx, float sy) {#scaleTransform-float-float-}
```
public void scaleTransform(float sx, float sy)
```


Scala la trasformazione geometrica locale di questo oggetto [TextureBrush](../../com.aspose.drawing/texturebrush) secondo le quantità specificate. Questo metodo antepone la matrice di scala alla trasformazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sx | float | La quantità con cui scalare la trasformazione nella direzione x. |
| sy | float | La quantità con cui scalare la trasformazione nella direzione y. |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public void scaleTransform(float sx, float sy, int order)
```


Scala la trasformazione geometrica locale di questo oggetto [TextureBrush](../../com.aspose.drawing/texturebrush) delle quantità specificate nell'ordine specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sx | float | La quantità con cui scalare la trasformazione nella direzione x. |
| sy | float | La quantità con cui scalare la trasformazione nella direzione y. |
| order | int | Un'enumerazione [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder) che specifica se aggiungere o anteporre la matrice di scala. |

### rotateTransform(float angle) {#rotateTransform-float-}
```
public void rotateTransform(float angle)
```


Ruota la trasformazione geometrica locale di questo oggetto [TextureBrush](../../com.aspose.drawing/texturebrush) secondo l'angolo specificato. Questo metodo antepone la rotazione alla trasformazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| angolo | float | L'angolo di rotazione. |

### rotateTransform(float angle, int order) {#rotateTransform-float-int-}
```
public void rotateTransform(float angle, int order)
```


Ruota la trasformazione geometrica locale di questo oggetto [TextureBrush](../../com.aspose.drawing/texturebrush) dell'angolo specificato nell'ordine specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| angolo | float | L'angolo di rotazione. |
| order | int | Un'enumerazione [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder) che specifica se aggiungere o anteporre la matrice di rotazione. |

