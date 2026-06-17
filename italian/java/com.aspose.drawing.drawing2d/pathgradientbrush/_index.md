---
title: PathGradientBrush
second_title: Riferimento API di Aspose.Drawing per Java
description: Incapsula un oggetto che riempie l'interno di un oggetto con un gradiente.
type: docs
weight: 36
url: /it/java/com.aspose.drawing.drawing2d/pathgradientbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.drawing.Brush](../../com.aspose.drawing/brush)
```
public final class PathGradientBrush extends Brush
```

Incapsula un oggetto [Brush](../../com.aspose.drawing/brush) che riempie l'interno di un oggetto [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) con un gradiente. Questa classe non può essere ereditata.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [PathGradientBrush(PointF[] points)](#PathGradientBrush-com.aspose.drawing.PointF---) | Inizializza una nuova istanza della classe [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) con i punti specificati. |
| [PathGradientBrush(PointF[] points, int wrapMode)](#PathGradientBrush-com.aspose.drawing.PointF---int-) | Inizializza una nuova istanza della classe [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) con i punti specificati e la modalità di avvolgimento. |
| [PathGradientBrush(Point[] points)](#PathGradientBrush-com.aspose.drawing.Point---) | Inizializza una nuova istanza della classe [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) con i punti specificati. |
| [PathGradientBrush(Point[] points, int wrapMode)](#PathGradientBrush-com.aspose.drawing.Point---int-) | Inizializza una nuova istanza della classe [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) con i punti specificati e la modalità di avvolgimento. |
| [PathGradientBrush(GraphicsPath path)](#PathGradientBrush-com.aspose.drawing.drawing2d.GraphicsPath-) | Inizializza una nuova istanza della classe [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) con il percorso specificato. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getCenterColor()](#getCenterColor--) | Ottiene o imposta il colore al centro del gradiente del percorso. |
| [setCenterColor(Color value)](#setCenterColor-com.aspose.drawing.Color-) | Ottiene o imposta il colore al centro del gradiente del percorso. |
| [getSurroundColors()](#getSurroundColors--) | Ottiene o imposta un array di colori che corrispondono ai punti nel percorso che questo [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) riempie. |
| [setSurroundColors(Color[] value)](#setSurroundColors-com.aspose.drawing.Color---) | Ottiene o imposta un array di colori che corrispondono ai punti nel percorso che questo [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) riempie. |
| [getCenterPoint()](#getCenterPoint--) | Ottiene o imposta il punto centrale del gradiente del percorso. |
| [setCenterPoint(PointF value)](#setCenterPoint-com.aspose.drawing.PointF-) | Ottiene o imposta il punto centrale del gradiente del percorso. |
| [getRectangle()](#getRectangle--) | Ottiene un rettangolo di delimitazione per questo [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush). |
| [getBlend()](#getBlend--) | Ottiene o imposta un `Blend`([.getBlend](../../null/\#getBlend)/[.setBlend(Blend)](../../null/\#setBlend-Blend-)) che specifica le posizioni e i fattori che definiscono una caduta personalizzata per il gradiente. |
| [setBlend(Blend value)](#setBlend-com.aspose.drawing.drawing2d.Blend-) | Ottiene o imposta un `Blend`([.getBlend](../../null/\#getBlend)/[.setBlend(Blend)](../../null/\#setBlend-Blend-)) che specifica le posizioni e i fattori che definiscono una caduta personalizzata per il gradiente. |
| [getInterpolationColors()](#getInterpolationColors--) | Ottiene o imposta un [ColorBlend](../../com.aspose.drawing.drawing2d/colorblend) che definisce un gradiente lineare multicolore. |
| [setInterpolationColors(ColorBlend value)](#setInterpolationColors-com.aspose.drawing.drawing2d.ColorBlend-) | Ottiene o imposta un [ColorBlend](../../com.aspose.drawing.drawing2d/colorblend) che definisce un gradiente lineare multicolore. |
| [getTransform()](#getTransform--) | Ottiene o imposta una copia della [Matrix](../../com.aspose.drawing.drawing2d/matrix) che definisce una trasformazione geometrica locale per questo [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush). |
| [setTransform(Matrix value)](#setTransform-com.aspose.drawing.drawing2d.Matrix-) | Ottiene o imposta una copia della [Matrix](../../com.aspose.drawing.drawing2d/matrix) che definisce una trasformazione geometrica locale per questo [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush). |
| [getFocusScales()](#getFocusScales--) | Ottiene o imposta il punto focale per la caduta del gradiente. |
| [setFocusScales(PointF value)](#setFocusScales-com.aspose.drawing.PointF-) | Ottiene o imposta il punto focale per la caduta del gradiente. |
| [getWrapMode()](#getWrapMode--) | Ottiene o imposta un `WrapMode`([.getWrapMode](../../null/\#getWrapMode)/[.setWrapMode(int)](../../null/\#setWrapMode-int-)) che indica la modalità di avvolgimento per questo [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush). |
| [setWrapMode(int value)](#setWrapMode-int-) | Ottiene o imposta un `WrapMode`([.getWrapMode](../../null/\#getWrapMode)/[.setWrapMode(int)](../../null/\#setWrapMode-int-)) che indica la modalità di avvolgimento per questo [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush). |
| [deepClone()](#deepClone--) | Crea una copia esatta di questo [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush). |
| [setSigmaBellShape(float focus)](#setSigmaBellShape-float-) | Crea un pennello gradiente che cambia colore partendo dal centro del percorso verso il bordo del percorso. |
| [setSigmaBellShape(float focus, float scale)](#setSigmaBellShape-float-float-) | Crea un pennello gradiente che cambia colore partendo dal centro del percorso verso il bordo del percorso. |
| [setBlendTriangularShape(float focus)](#setBlendTriangularShape-float-) | Crea un gradiente con un colore centrale e una caduta lineare verso un colore circostante. |
| [setBlendTriangularShape(float focus, float scale)](#setBlendTriangularShape-float-float-) | Crea un gradiente con un colore centrale e una caduta lineare verso ciascun colore circostante. |
| [resetTransform()](#resetTransform--) | Reimposta la proprietà `PathGradientBrush.Transform` a identità. |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-) | Aggiorna la matrice di trasformazione del pennello con il prodotto della matrice di trasformazione del pennello moltiplicata per un'altra matrice. |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-int-) | Aggiorna la matrice di trasformazione del pennello con il prodotto della matrice di trasformazione del pennello moltiplicata per un'altra matrice. |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | Applica la traslazione specificata alla trasformazione geometrica locale. |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | Applica la traslazione specificata alla trasformazione geometrica locale nell'ordine specificato. |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | Scala la trasformazione geometrica locale per le quantità specificate. |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | Scala la trasformazione geometrica locale per le quantità specificate nell'ordine specificato. |
| [rotateTransform(float angle)](#rotateTransform-float-) | Ruota la trasformazione geometrica locale di una quantità specificata. |
| [rotateTransform(float angle, int order)](#rotateTransform-float-int-) | Ruota la trasformazione geometrica locale di una quantità specificata nell'ordine specificato. |
### PathGradientBrush(PointF[] points) {#PathGradientBrush-com.aspose.drawing.PointF---}
```
public PathGradientBrush(PointF[] points)
```


Inizializza una nuova istanza della classe [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) con i punti specificati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.drawing/pointf) | Un array di strutture [PointF](../../com.aspose.drawing/pointf) che rappresentano i punti che costituiscono i vertici del percorso. |

### PathGradientBrush(PointF[] points, int wrapMode) {#PathGradientBrush-com.aspose.drawing.PointF---int-}
```
public PathGradientBrush(PointF[] points, int wrapMode)
```


Inizializza una nuova istanza della classe [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) con i punti specificati e la modalità di avvolgimento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.drawing/pointf) | Un array di strutture [PointF](../../com.aspose.drawing/pointf) che rappresentano i punti che costituiscono i vertici del percorso. |
| wrapMode | int | Un `WrapMode`([.getWrapMode](../../null/\#getWrapMode)/[.setWrapMode(int)](../../null/\#setWrapMode-int-)) che specifica come vengono ripetuti i riempimenti disegnati con questo [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush). |

### PathGradientBrush(Point[] points) {#PathGradientBrush-com.aspose.drawing.Point---}
```
public PathGradientBrush(Point[] points)
```


Inizializza una nuova istanza della classe [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) con i punti specificati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| points | [Point\[\]](../../com.aspose.drawing/point) | Un array di strutture [Point](../../com.aspose.drawing/point) che rappresentano i punti che costituiscono i vertici del percorso. |

### PathGradientBrush(Point[] points, int wrapMode) {#PathGradientBrush-com.aspose.drawing.Point---int-}
```
public PathGradientBrush(Point[] points, int wrapMode)
```


Inizializza una nuova istanza della classe [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) con i punti specificati e la modalità di avvolgimento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| points | [Point\[\]](../../com.aspose.drawing/point) | Un array di strutture [Point](../../com.aspose.drawing/point) che rappresentano i punti che costituiscono i vertici del percorso. |
| wrapMode | int | Un `WrapMode`([.getWrapMode](../../null/\#getWrapMode)/[.setWrapMode(int)](../../null/\#setWrapMode-int-)) che specifica come vengono ripetuti i riempimenti disegnati con questo [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush). |

### PathGradientBrush(GraphicsPath path) {#PathGradientBrush-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public PathGradientBrush(GraphicsPath path)
```


Inizializza una nuova istanza della classe [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) con il percorso specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | Il [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) che definisce l'area riempita da questo [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush). |

### getCenterColor() {#getCenterColor--}
```
public Color getCenterColor()
```


Ottiene o imposta il colore al centro del gradiente del percorso.

**Returns:**
[Color](../../com.aspose.drawing/color)
### setCenterColor(Color value) {#setCenterColor-com.aspose.drawing.Color-}
```
public void setCenterColor(Color value)
```


Ottiene o imposta il colore al centro del gradiente del percorso.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Color](../../com.aspose.drawing/color) |  |

### getSurroundColors() {#getSurroundColors--}
```
public Color[] getSurroundColors()
```


Ottiene o imposta un array di colori che corrispondono ai punti nel percorso che questo [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) riempie.

**Returns:**
com.aspose.drawing.Color[]
### setSurroundColors(Color[] value) {#setSurroundColors-com.aspose.drawing.Color---}
```
public void setSurroundColors(Color[] value)
```


Ottiene o imposta un array di colori che corrispondono ai punti nel percorso che questo [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) riempie.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Color\[\]](../../com.aspose.drawing/color) |  |

### getCenterPoint() {#getCenterPoint--}
```
public PointF getCenterPoint()
```


Ottiene o imposta il punto centrale del gradiente del percorso.

**Returns:**
[PointF](../../com.aspose.drawing/pointf)
### setCenterPoint(PointF value) {#setCenterPoint-com.aspose.drawing.PointF-}
```
public void setCenterPoint(PointF value)
```


Ottiene o imposta il punto centrale del gradiente del percorso.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [PointF](../../com.aspose.drawing/pointf) |  |

### getRectangle() {#getRectangle--}
```
public RectangleF getRectangle()
```


Ottiene un rettangolo di delimitazione per questo [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush).

**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef)
### getBlend() {#getBlend--}
```
public Blend getBlend()
```


Ottiene o imposta un `Blend`([.getBlend](../../null/\#getBlend)/[.setBlend(Blend)](../../null/\#setBlend-Blend-)) che specifica le posizioni e i fattori che definiscono una caduta personalizzata per il gradiente.

**Returns:**
[Blend](../../com.aspose.drawing.drawing2d/blend)
### setBlend(Blend value) {#setBlend-com.aspose.drawing.drawing2d.Blend-}
```
public void setBlend(Blend value)
```


Ottiene o imposta un `Blend`([.getBlend](../../null/\#getBlend)/[.setBlend(Blend)](../../null/\#setBlend-Blend-)) che specifica le posizioni e i fattori che definiscono una caduta personalizzata per il gradiente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Blend](../../com.aspose.drawing.drawing2d/blend) |  |

### getInterpolationColors() {#getInterpolationColors--}
```
public ColorBlend getInterpolationColors()
```


Ottiene o imposta un [ColorBlend](../../com.aspose.drawing.drawing2d/colorblend) che definisce un gradiente lineare multicolore.

**Returns:**
[ColorBlend](../../com.aspose.drawing.drawing2d/colorblend)
### setInterpolationColors(ColorBlend value) {#setInterpolationColors-com.aspose.drawing.drawing2d.ColorBlend-}
```
public void setInterpolationColors(ColorBlend value)
```


Ottiene o imposta un [ColorBlend](../../com.aspose.drawing.drawing2d/colorblend) che definisce un gradiente lineare multicolore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [ColorBlend](../../com.aspose.drawing.drawing2d/colorblend) |  |

### getTransform() {#getTransform--}
```
public Matrix getTransform()
```


Ottiene o imposta una copia della [Matrix](../../com.aspose.drawing.drawing2d/matrix) che definisce una trasformazione geometrica locale per questo [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush).

**Returns:**
[Matrix](../../com.aspose.drawing.drawing2d/matrix)
### setTransform(Matrix value) {#setTransform-com.aspose.drawing.drawing2d.Matrix-}
```
public void setTransform(Matrix value)
```


Ottiene o imposta una copia della [Matrix](../../com.aspose.drawing.drawing2d/matrix) che definisce una trasformazione geometrica locale per questo [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.drawing.drawing2d/matrix) |  |

### getFocusScales() {#getFocusScales--}
```
public PointF getFocusScales()
```


Ottiene o imposta il punto focale per la caduta del gradiente.

**Returns:**
[PointF](../../com.aspose.drawing/pointf)
### setFocusScales(PointF value) {#setFocusScales-com.aspose.drawing.PointF-}
```
public void setFocusScales(PointF value)
```


Ottiene o imposta il punto focale per la caduta del gradiente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [PointF](../../com.aspose.drawing/pointf) |  |

### getWrapMode() {#getWrapMode--}
```
public int getWrapMode()
```


Ottiene o imposta un `WrapMode`([.getWrapMode](../../null/\#getWrapMode)/[.setWrapMode(int)](../../null/\#setWrapMode-int-)) che indica la modalità di avvolgimento per questo [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush).

**Returns:**
int
### setWrapMode(int value) {#setWrapMode-int-}
```
public void setWrapMode(int value)
```


Ottiene o imposta un `WrapMode`([.getWrapMode](../../null/\#getWrapMode)/[.setWrapMode(int)](../../null/\#setWrapMode-int-)) che indica la modalità di avvolgimento per questo [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Crea una copia esatta di questo [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush).

**Returns:**
java.lang.Object - Il [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) che questo metodo crea, convertito in oggetto.
### setSigmaBellShape(float focus) {#setSigmaBellShape-float-}
```
public void setSigmaBellShape(float focus)
```


Crea un pennello gradiente che cambia colore partendo dal centro del percorso verso il bordo del percorso. La transizione da un colore all'altro è basata su una curva a forma di campana.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| focus | float | Un valore da 0 a 1 che specifica dove, lungo qualsiasi radiale dal centro del percorso al bordo del percorso, il colore centrale avrà la massima intensità. Un valore di 1 (predefinito) posiziona la massima intensità al centro del percorso. |

### setSigmaBellShape(float focus, float scale) {#setSigmaBellShape-float-float-}
```
public void setSigmaBellShape(float focus, float scale)
```


Crea un pennello gradiente che cambia colore partendo dal centro del percorso verso il bordo del percorso. La transizione da un colore all'altro è basata su una curva a forma di campana.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| focus | float | Un valore da 0 a 1 che specifica dove, lungo qualsiasi radiale dal centro del percorso al bordo del percorso, il colore centrale avrà la massima intensità. Un valore di 1 (predefinito) posiziona la massima intensità al centro del percorso. |
| scala | float | Un valore da 0 a 1 che specifica l'intensità massima del colore centrale che viene mescolato con il colore del bordo. Un valore di 1 genera l'intensità più alta possibile del colore centrale ed è il valore predefinito. |

### setBlendTriangularShape(float focus) {#setBlendTriangularShape-float-}
```
public void setBlendTriangularShape(float focus)
```


Crea un gradiente con un colore centrale e una caduta lineare verso un colore circostante.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| focus | float | Un valore da 0 a 1 che specifica dove, lungo qualsiasi radiale dal centro del percorso al bordo del percorso, il colore centrale avrà la massima intensità. Un valore di 1 (predefinito) posiziona la massima intensità al centro del percorso. |

### setBlendTriangularShape(float focus, float scale) {#setBlendTriangularShape-float-float-}
```
public void setBlendTriangularShape(float focus, float scale)
```


Crea un gradiente con un colore centrale e una caduta lineare verso ciascun colore circostante.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| focus | float | Un valore da 0 a 1 che specifica dove, lungo qualsiasi radiale dal centro del percorso al bordo del percorso, il colore centrale avrà la massima intensità. Un valore di 1 (predefinito) posiziona la massima intensità al centro del percorso. |
| scala | float | Un valore da 0 a 1 che specifica l'intensità massima del colore centrale che viene mescolato con il colore del bordo. Un valore di 1 genera l'intensità più alta possibile del colore centrale ed è il valore predefinito. |

### resetTransform() {#resetTransform--}
```
public void resetTransform()
```


Reimposta la proprietà `PathGradientBrush.Transform` a identità.

### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-}
```
public void multiplyTransform(Matrix matrix)
```


Aggiorna la matrice di trasformazione del pennello con il prodotto della matrice di trasformazione del pennello moltiplicata per un'altra matrice.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | La [Matrix](../../com.aspose.drawing.drawing2d/matrix) che verrà moltiplicata per la matrice di trasformazione corrente del pennello. |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-int-}
```
public void multiplyTransform(Matrix matrix, int order)
```


Aggiorna la matrice di trasformazione del pennello con il prodotto della matrice di trasformazione del pennello moltiplicata per un'altra matrice.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | La [Matrix](../../com.aspose.drawing.drawing2d/matrix) che verrà moltiplicata per la matrice di trasformazione corrente del pennello. |
| order | int | Un [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder) che specifica in quale ordine moltiplicare le due matrici. |

### translateTransform(float dx, float dy) {#translateTransform-float-float-}
```
public void translateTransform(float dx, float dy)
```


Applica la traslazione specificata alla trasformazione geometrica locale. Questo metodo antepone la traslazione alla trasformazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dx | float | Il valore della traslazione in x. |
| dy | float | Il valore della traslazione in y. |

### translateTransform(float dx, float dy, int order) {#translateTransform-float-float-int-}
```
public void translateTransform(float dx, float dy, int order)
```


Applica la traslazione specificata alla trasformazione geometrica locale nell'ordine specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dx | float | Il valore della traslazione in x. |
| dy | float | Il valore della traslazione in y. |
| ordine | int | L'ordine (anteporre o aggiungere) con cui applicare la traslazione. |

### scaleTransform(float sx, float sy) {#scaleTransform-float-float-}
```
public void scaleTransform(float sx, float sy)
```


Scala la trasformazione geometrica locale di quantità specificate. Questo metodo antepone la matrice di scala alla trasformazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sx | float | Il fattore di scala della trasformazione nella direzione dell'asse x. |
| sy | float | Il fattore di scala della trasformazione nella direzione dell'asse y. |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public void scaleTransform(float sx, float sy, int order)
```


Scala la trasformazione geometrica locale per le quantità specificate nell'ordine specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sx | float | Il fattore di scala della trasformazione nella direzione dell'asse x. |
| sy | float | Il fattore di scala della trasformazione nella direzione dell'asse y. |
| order | int | Un [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder) che specifica se aggiungere o anteporre la matrice di scala. |

### rotateTransform(float angle) {#rotateTransform-float-}
```
public void rotateTransform(float angle)
```


Ruota la trasformazione geometrica locale della quantità specificata. Questo metodo antepone la rotazione alla trasformazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| angolo | float | L'angolo (estensione) di rotazione. |

### rotateTransform(float angle, int order) {#rotateTransform-float-int-}
```
public void rotateTransform(float angle, int order)
```


Ruota la trasformazione geometrica locale di una quantità specificata nell'ordine specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| angolo | float | L'angolo (estensione) di rotazione. |
| order | int | Un [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder) che specifica se aggiungere o anteporre la matrice di rotazione. |

