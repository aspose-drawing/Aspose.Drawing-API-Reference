---
title: Matrix
second_title: Riferimento API di Aspose.Drawing per Java
description: Incapsula una matrice affine 3x3 che rappresenta una trasformazione geometrica.
type: docs
weight: 33
url: /it/java/com.aspose.drawing.drawing2d/matrix/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public final class Matrix implements System.IDisposable
```

Incapsula una matrice affine 3x3 che rappresenta una trasformazione geometrica. Questa classe non può essere ereditata.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Matrix()](#Matrix--) | Inizializza una nuova istanza della classe Matrix come matrice identità. |
| [Matrix(float m11, float m12, float m21, float m22, float dx, float dy)](#Matrix-float-float-float-float-float-float-) | Inizializza una nuova istanza della classe Matrix con gli elementi specificati. |
| [Matrix(Rectangle rect, Point[] plgpts)](#Matrix-com.aspose.drawing.Rectangle-com.aspose.drawing.Point---) | Inizializza una nuova istanza della classe [Matrix](../../com.aspose.drawing.drawing2d/matrix) con la trasformazione geometrica definita dal rettangolo specificato e dall'array di punti. |
| [Matrix(RectangleF rect, PointF[] plgpts)](#Matrix-com.aspose.drawing.RectangleF-com.aspose.drawing.PointF---) | Inizializza una nuova istanza della classe [Matrix](../../com.aspose.drawing.drawing2d/matrix) con la trasformazione geometrica definita dal rettangolo specificato e dall'array di punti. |
## Campi

| Campo | Descrizione |
| --- | --- |
| [IdentityTransform](#IdentityTransform) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getElements()](#getElements--) | Restituisce un array di valori a virgola mobile che rappresenta gli elementi di questa Matrix. |
| [isIdentity()](#isIdentity--) | Restituisce un valore che indica se questa Matrix è la matrice identità. |
| [isInvertible()](#isInvertible--) | Restituisce un valore che indica se questa Matrix è invertibile. |
| [getOffsetX()](#getOffsetX--) | Ottiene il valore di traslazione x (il valore dx, o l'elemento nella terza riga e prima colonna) di questa Matrix. |
| [getOffsetY()](#getOffsetY--) | Ottiene il valore di traslazione y (il valore `dy`, o l'elemento nella terza riga e seconda colonna) di questa Matrix. |
| [dispose()](#dispose--) | Rilascia tutte le risorse utilizzate da questa Matrix. |
| [deepClone()](#deepClone--) | Crea una copia esatta di questa Matrix. |
| [invert()](#invert--) | Inverte questa Matrix, se è invertibile. |
| [translate(float offsetX, float offsetY)](#translate-float-float-) | Applica il vettore di traslazione specificato (offsetX e offsetY) a questa Matrix preponendo il vettore di traslazione. |
| [translate(float offsetX, float offsetY, int order)](#translate-float-float-int-) | Applica il vettore di traslazione specificato a questa Matrix nell'ordine specificato. |
| [transformVectors(PointF[] pts)](#transformVectors-com.aspose.drawing.PointF---) | Moltiplica ogni vettore in un array per la matrix. |
| [scale(float scaleX, float scaleY)](#scale-float-float-) | Applica il vettore di scala specificato a questa Matrix preponendo il vettore di scala. |
| [scale(float scaleX, float scaleY, int order)](#scale-float-float-int-) | Applica il vettore di scala specificato (scaleX e scaleY) a questa Matrix usando l'ordine specificato. |
| [shear(float shearX, float shearY)](#shear-float-float-) | Applica il vettore di taglio specificato a questa Matrix preponendo la trasformazione di taglio. |
| [shear(float shearX, float shearY, int order)](#shear-float-float-int-) | Applica il vettore di taglio specificato a questa Matrix nell'ordine specificato. |
| [rotateAt(float angle, PointF point)](#rotateAt-float-com.aspose.drawing.PointF-) | Applica una rotazione in senso orario a questa Matrix attorno al punto specificato nel parametro point, e preponendo la rotazione. |
| [rotateAt(float angle, PointF point, int order)](#rotateAt-float-com.aspose.drawing.PointF-int-) | Applica una rotazione in senso orario attorno al punto specificato a questa Matrix nell'ordine specificato. |
| [transformPoints(PointF[] pts)](#transformPoints-com.aspose.drawing.PointF---) | Applica la trasformazione geometrica rappresentata da questa [Matrix](../../com.aspose.drawing.drawing2d/matrix) a un array di punti specificato. |
| [transformPoints(Point[] pts)](#transformPoints-com.aspose.drawing.Point---) | Applica la trasformazione geometrica rappresentata da questa [Matrix](../../com.aspose.drawing.drawing2d/matrix) a un array di punti specificato. |
| [multiply(Matrix matrix)](#multiply-com.aspose.drawing.drawing2d.Matrix-) | Moltiplica questa [Matrix](../../com.aspose.drawing.drawing2d/matrix) per la matrix specificata nel parametro `matrix`, preponendo la [Matrix](../../com.aspose.drawing.drawing2d/matrix) specificata. |
| [multiply(Matrix matrix, int order)](#multiply-com.aspose.drawing.drawing2d.Matrix-int-) | Moltiplica questa [Matrix](../../com.aspose.drawing.drawing2d/matrix) per la matrix specificata nel parametro `matrix`, e nell'ordine specificato nel parametro `order`. |
| [rotate(float angle)](#rotate-float-) | Preponi a questa [Matrix](../../com.aspose.drawing.drawing2d/matrix) una rotazione in senso orario, attorno all'origine e con l'angolo specificato. |
| [rotate(float angle, int order)](#rotate-float-int-) | Applica una rotazione in senso orario di un valore specificato nel parametro angle, attorno all'origine (coordinate x e y zero) per questa [Matrix](../../com.aspose.drawing.drawing2d/matrix). |
| [reset()](#reset--) | Reimposta questa [Matrix](../../com.aspose.drawing.drawing2d/matrix) per avere gli elementi della matrix identità. |
### Matrix() {#Matrix--}
```
public Matrix()
```


Inizializza una nuova istanza della classe Matrix come matrice identità.

### Matrix(float m11, float m12, float m21, float m22, float dx, float dy) {#Matrix-float-float-float-float-float-float-}
```
public Matrix(float m11, float m12, float m21, float m22, float dx, float dy)
```


Inizializza una nuova istanza della classe Matrix con gli elementi specificati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| m11 | float | Il valore nella prima riga e prima colonna della nuova Matrix. |
| m12 | float | Il valore nella prima riga e seconda colonna della nuova Matrix. |
| m21 | float | Il valore nella seconda riga e nella prima colonna della nuova Matrice. |
| m22 | float | Il valore nella seconda riga e nella seconda colonna della nuova Matrice. |
| dx | float | Il valore nella terza riga e nella prima colonna della nuova Matrice. |
| dy | float | Il valore nella terza riga e nella seconda colonna della nuova Matrice. |

### Matrix(Rectangle rect, Point[] plgpts) {#Matrix-com.aspose.drawing.Rectangle-com.aspose.drawing.Point---}
```
public Matrix(Rectangle rect, Point[] plgpts)
```


Inizializza una nuova istanza della classe [Matrix](../../com.aspose.drawing.drawing2d/matrix) con la trasformazione geometrica definita dal rettangolo specificato e dall'array di punti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | Una struttura [Rectangle](../../com.aspose.drawing/rectangle) che rappresenta il rettangolo da trasformare. |
| plgpts | [Point\[\]](../../com.aspose.drawing/point) | Un array di tre strutture [Point](../../com.aspose.drawing/point) che rappresentano i punti di un parallelogramma a cui devono essere trasformati gli angoli superiore sinistro, superiore destro e inferiore sinistro del rettangolo. L'angolo inferiore destro del parallelogramma è implicito dai primi tre angoli. |

### Matrix(RectangleF rect, PointF[] plgpts) {#Matrix-com.aspose.drawing.RectangleF-com.aspose.drawing.PointF---}
```
public Matrix(RectangleF rect, PointF[] plgpts)
```


Inizializza una nuova istanza della classe [Matrix](../../com.aspose.drawing.drawing2d/matrix) con la trasformazione geometrica definita dal rettangolo specificato e dall'array di punti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | Una struttura [RectangleF](../../com.aspose.drawing/rectanglef) che rappresenta il rettangolo da trasformare. |
| plgpts | [PointF\[\]](../../com.aspose.drawing/pointf) | Un array di tre strutture [PointF](../../com.aspose.drawing/pointf) che rappresentano i punti di un parallelogramma a cui devono essere trasformati gli angoli superiore sinistro, superiore destro e inferiore sinistro del rettangolo. L'angolo inferiore destro del parallelogramma è implicito dai primi tre angoli. |

### IdentityTransform {#IdentityTransform}
```
public static final Matrix IdentityTransform
```


### getElements() {#getElements--}
```
public float[] getElements()
```


Restituisce un array di valori a virgola mobile che rappresenta gli elementi di questa Matrix.

**Returns:**
float[] - un array di valori a virgola mobile che rappresenta gli elementi di questa Matrice.
### isIdentity() {#isIdentity--}
```
public boolean isIdentity()
```


Restituisce un valore che indica se questa Matrix è la matrice identità.

**Returns:**
boolean - un valore che indica se questa Matrice è la matrice identità.
### isInvertible() {#isInvertible--}
```
public boolean isInvertible()
```


Restituisce un valore che indica se questa Matrix è invertibile.

**Returns:**
boolean - un valore che indica se questa Matrice è invertibile.
### getOffsetX() {#getOffsetX--}
```
public float getOffsetX()
```


Ottiene il valore di traslazione x (il valore dx, o l'elemento nella terza riga e prima colonna) di questa Matrix.

**Returns:**
float - il valore di traslazione x (il valore dx, o l'elemento nella terza riga e nella prima colonna) di questa Matrice.
### getOffsetY() {#getOffsetY--}
```
public float getOffsetY()
```


Ottiene il valore di traslazione y (il valore `dy`, o l'elemento nella terza riga e seconda colonna) di questa Matrix.

**Returns:**
float - il valore di traslazione y (il valore `dy`, o l'elemento nella terza riga e nella seconda colonna) di questa Matrice.
### dispose() {#dispose--}
```
public void dispose()
```


Rilascia tutte le risorse utilizzate da questa Matrix.

--------------------

Questo metodo in realtà non fa nulla. È solo per compatibilità con l'API System.Drawing.

### deepClone() {#deepClone--}
```
public Matrix deepClone()
```


Crea una copia esatta di questa Matrix.

**Returns:**
[Matrix](../../com.aspose.drawing.drawing2d/matrix) - The Matrix that this method creates.
### invert() {#invert--}
```
public void invert()
```


Inverte questa Matrix, se è invertibile.

### translate(float offsetX, float offsetY) {#translate-float-float-}
```
public void translate(float offsetX, float offsetY)
```


Applica il vettore di traslazione specificato (offsetX e offsetY) a questa Matrix preponendo il vettore di traslazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| offsetX | float | Il valore x con cui traslare questa Matrice. |
| offsetY | float | Il valore y con cui traslare questa Matrice. |

### translate(float offsetX, float offsetY, int order) {#translate-float-float-int-}
```
public void translate(float offsetX, float offsetY, int order)
```


Applica il vettore di traslazione specificato a questa Matrix nell'ordine specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| offsetX | float | Il valore x con cui traslare questa Matrice. |
| offsetY | float | Il valore y con cui traslare questa Matrice. |
| ordine | int | Un MatrixOrder che specifica l'ordine (append o prepend) con cui la traslazione viene applicata a questa Matrice. |

### transformVectors(PointF[] pts) {#transformVectors-com.aspose.drawing.PointF---}
```
public void transformVectors(PointF[] pts)
```


Moltiplica ogni vettore in un array per la matrice. Gli elementi di traslazione di questa matrice (terza riga) sono ignorati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pts | [PointF\[\]](../../com.aspose.drawing/pointf) | Un array di strutture [PointF](../../com.aspose.drawing/pointf) che rappresentano i punti da trasformare. |

### scale(float scaleX, float scaleY) {#scale-float-float-}
```
public void scale(float scaleX, float scaleY)
```


Applica il vettore di scala specificato a questa Matrix preponendo il vettore di scala.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| scaleX | float | Il valore con cui scalare questa Matrice nella direzione dell'asse x. |
| scaleY | float | Il valore con cui scalare questa Matrix nella direzione dell'asse y. |

### scale(float scaleX, float scaleY, int order) {#scale-float-float-int-}
```
public void scale(float scaleX, float scaleY, int order)
```


Applica il vettore di scala specificato (scaleX e scaleY) a questa Matrix usando l'ordine specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| scaleX | float | Il valore con cui scalare questa Matrice nella direzione dell'asse x. |
| scaleY | float | Il valore con cui scalare questa Matrix nella direzione dell'asse y. |
| ordine | int | Un MatrixOrder che specifica l'ordine (append o prepend) con cui il vettore di scala viene applicato a questa Matrix. |

### shear(float shearX, float shearY) {#shear-float-float-}
```
public void shear(float shearX, float shearY)
```


Applica il vettore di taglio specificato a questa Matrix preponendo la trasformazione di taglio.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| shearX | float | Il fattore di shear orizzontale. |
| shearY | float | Il fattore di shear verticale. |

### shear(float shearX, float shearY, int order) {#shear-float-float-int-}
```
public void shear(float shearX, float shearY, int order)
```


Applica il vettore di taglio specificato a questa Matrix nell'ordine specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| shearX | float | Il fattore di shear orizzontale. |
| shearY | float | Il fattore di shear verticale. |
| ordine | int | Un MatrixOrder che specifica l'ordine (append o prepend) con cui viene applicato lo shear. |

### rotateAt(float angle, PointF point) {#rotateAt-float-com.aspose.drawing.PointF-}
```
public void rotateAt(float angle, PointF point)
```


Applica una rotazione in senso orario a questa Matrix attorno al punto specificato nel parametro point, e preponendo la rotazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| angolo | float | L'angolo (estensione) della rotazione, in gradi. |
| point | [PointF](../../com.aspose.drawing/pointf) | Un PointF che rappresenta il centro della rotazione. |

### rotateAt(float angle, PointF point, int order) {#rotateAt-float-com.aspose.drawing.PointF-int-}
```
public void rotateAt(float angle, PointF point, int order)
```


Applica una rotazione in senso orario attorno al punto specificato a questa Matrix nell'ordine specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| angolo | float | L'angolo della rotazione, in gradi. |
| point | [PointF](../../com.aspose.drawing/pointf) | Un PointF che rappresenta il centro della rotazione. |
| ordine | int | Un MatrixOrder che specifica l'ordine (append o prepend) con cui viene applicata la rotazione. |

### transformPoints(PointF[] pts) {#transformPoints-com.aspose.drawing.PointF---}
```
public void transformPoints(PointF[] pts)
```


Applica la trasformazione geometrica rappresentata da questa [Matrix](../../com.aspose.drawing.drawing2d/matrix) a un array di punti specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pts | [PointF\[\]](../../com.aspose.drawing/pointf) | Un array di strutture [PointF](../../com.aspose.drawing/pointf) che rappresentano i punti da trasformare. |

### transformPoints(Point[] pts) {#transformPoints-com.aspose.drawing.Point---}
```
public void transformPoints(Point[] pts)
```


Applica la trasformazione geometrica rappresentata da questa [Matrix](../../com.aspose.drawing.drawing2d/matrix) a un array di punti specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pts | [Point\[\]](../../com.aspose.drawing/point) | Un array di strutture [Point](../../com.aspose.drawing/point) che rappresenta i punti da trasformare. |

### multiply(Matrix matrix) {#multiply-com.aspose.drawing.drawing2d.Matrix-}
```
public void multiply(Matrix matrix)
```


Moltiplica questa [Matrix](../../com.aspose.drawing.drawing2d/matrix) per la matrix specificata nel parametro `matrix`, preponendo la [Matrix](../../com.aspose.drawing.drawing2d/matrix) specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | La [Matrix](../../com.aspose.drawing.drawing2d/matrix) con cui questa [Matrix](../../com.aspose.drawing.drawing2d/matrix) deve essere moltiplicata. |

### multiply(Matrix matrix, int order) {#multiply-com.aspose.drawing.drawing2d.Matrix-int-}
```
public void multiply(Matrix matrix, int order)
```


Moltiplica questa [Matrix](../../com.aspose.drawing.drawing2d/matrix) per la matrix specificata nel parametro `matrix`, e nell'ordine specificato nel parametro `order`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | La [Matrix](../../com.aspose.drawing.drawing2d/matrix) con cui questa [Matrix](../../com.aspose.drawing.drawing2d/matrix) deve essere moltiplicata. |
| order | int | Il [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder) che rappresenta l'ordine della moltiplicazione. |

### rotate(float angle) {#rotate-float-}
```
public void rotate(float angle)
```


Preponi a questa [Matrix](../../com.aspose.drawing.drawing2d/matrix) una rotazione in senso orario, attorno all'origine e con l'angolo specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| angolo | float | L'angolo della rotazione, in gradi. |

### rotate(float angle, int order) {#rotate-float-int-}
```
public void rotate(float angle, int order)
```


Applica una rotazione in senso orario di un valore specificato nel parametro angle, attorno all'origine (coordinate x e y zero) per questa [Matrix](../../com.aspose.drawing.drawing2d/matrix).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| angolo | float | L'angolo della rotazione, in gradi. |
| order | int | Un [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder) che specifica l'ordine (append o prepend) con cui la rotazione viene applicata a questa [Matrix](../../com.aspose.drawing.drawing2d/matrix). |

### reset() {#reset--}
```
public void reset()
```


Reimposta questa [Matrix](../../com.aspose.drawing.drawing2d/matrix) per avere gli elementi della matrix identità.

