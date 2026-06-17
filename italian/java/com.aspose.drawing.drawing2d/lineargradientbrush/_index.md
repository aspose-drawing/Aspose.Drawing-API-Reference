---
title: LinearGradientBrush
second_title: Riferimento API di Aspose.Drawing per Java
description: Incapsula un  con un gradiente lineare.
type: docs
weight: 31
url: /it/java/com.aspose.drawing.drawing2d/lineargradientbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.drawing.Brush](../../com.aspose.drawing/brush)
```
public final class LinearGradientBrush extends Brush
```

Incapsula un [Brush](../../com.aspose.drawing/brush) con un gradiente lineare. Questa classe non può essere ereditata.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [LinearGradientBrush(PointF point1, PointF point2, Color color1, Color color2)](#LinearGradientBrush-com.aspose.drawing.PointF-com.aspose.drawing.PointF-com.aspose.drawing.Color-com.aspose.drawing.Color-) | Inizializza una nuova istanza della classe [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) con i punti e i colori specificati. |
| [LinearGradientBrush(Point point1, Point point2, Color color1, Color color2)](#LinearGradientBrush-com.aspose.drawing.Point-com.aspose.drawing.Point-com.aspose.drawing.Color-com.aspose.drawing.Color-) | Inizializza una nuova istanza della classe [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) con i punti e i colori specificati. |
| [LinearGradientBrush(RectangleF rect, Color color1, Color color2, int linearGradientMode)](#LinearGradientBrush-com.aspose.drawing.RectangleF-com.aspose.drawing.Color-com.aspose.drawing.Color-int-) | Inizializza una nuova istanza della classe [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) basata su un rettangolo, colori di inizio e fine, e una modalità di orientamento. |
| [LinearGradientBrush(Rectangle rect, Color color1, Color color2, int linearGradientMode)](#LinearGradientBrush-com.aspose.drawing.Rectangle-com.aspose.drawing.Color-com.aspose.drawing.Color-int-) | Inizializza una nuova istanza della classe [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) basata su un rettangolo, colori di inizio e fine, e orientamento. |
| [LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle)](#LinearGradientBrush-com.aspose.drawing.RectangleF-com.aspose.drawing.Color-com.aspose.drawing.Color-float-) | Inizializza una nuova istanza della classe [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) basata su un rettangolo, colori di inizio e fine, e un angolo di orientamento. |
| [LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle, boolean isAngleScaleable)](#LinearGradientBrush-com.aspose.drawing.RectangleF-com.aspose.drawing.Color-com.aspose.drawing.Color-float-boolean-) | Inizializza una nuova istanza della classe [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) basata su un rettangolo, colori di inizio e fine, e un angolo di orientamento. |
| [LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle)](#LinearGradientBrush-com.aspose.drawing.Rectangle-com.aspose.drawing.Color-com.aspose.drawing.Color-float-) | Inizializza una nuova istanza della classe [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) basata su un rettangolo, colori di inizio e fine, e un angolo di orientamento. |
| [LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle, boolean isAngleScaleable)](#LinearGradientBrush-com.aspose.drawing.Rectangle-com.aspose.drawing.Color-com.aspose.drawing.Color-float-boolean-) | Inizializza una nuova istanza della classe [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) basata su un rettangolo, colori di inizio e fine, e un angolo di orientamento. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getLinearColors()](#getLinearColors--) | Ottiene o imposta i colori di inizio e fine del gradiente. |
| [setLinearColors(Color[] value)](#setLinearColors-com.aspose.drawing.Color---) | Ottiene o imposta i colori di inizio e fine del gradiente. |
| [getRectangle()](#getRectangle--) | Ottiene una regione rettangolare che definisce i punti di inizio e fine del gradiente. |
| [getGammaCorrection()](#getGammaCorrection--) | Ottiene o imposta un valore che indica se la correzione gamma è abilitata per questo [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush). |
| [setGammaCorrection(boolean value)](#setGammaCorrection-boolean-) | Ottiene o imposta un valore che indica se la correzione gamma è abilitata per questo [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush). |
| [getBlend()](#getBlend--) | Ottiene o imposta un `Blend`([.getBlend](../../null/\#getBlend)/[.setBlend(Blend)](../../null/\#setBlend-Blend-)) che specifica le posizioni e i fattori che definiscono una caduta personalizzata per il gradiente. |
| [setBlend(Blend value)](#setBlend-com.aspose.drawing.drawing2d.Blend-) | Ottiene o imposta un `Blend`([.getBlend](../../null/\#getBlend)/[.setBlend(Blend)](../../null/\#setBlend-Blend-)) che specifica le posizioni e i fattori che definiscono una caduta personalizzata per il gradiente. |
| [getInterpolationColors()](#getInterpolationColors--) | Ottiene o imposta un [ColorBlend](../../com.aspose.drawing.drawing2d/colorblend) che definisce un gradiente lineare multicolore. |
| [setInterpolationColors(ColorBlend value)](#setInterpolationColors-com.aspose.drawing.drawing2d.ColorBlend-) | Ottiene o imposta un [ColorBlend](../../com.aspose.drawing.drawing2d/colorblend) che definisce un gradiente lineare multicolore. |
| [getWrapMode()](#getWrapMode--) | Ottiene o imposta un'enumerazione `WrapMode` che indica la modalità di avvolgimento per questo [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush). |
| [setWrapMode(int value)](#setWrapMode-int-) | Ottiene o imposta un'enumerazione `WrapMode` che indica la modalità di avvolgimento per questo [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush). |
| [getTransform()](#getTransform--) | Ottiene o imposta una copia di [Matrix](../../com.aspose.drawing.drawing2d/matrix) che definisce una trasformazione geometrica locale per questo [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush). |
| [setTransform(Matrix value)](#setTransform-com.aspose.drawing.drawing2d.Matrix-) | Ottiene o imposta una copia di [Matrix](../../com.aspose.drawing.drawing2d/matrix) che definisce una trasformazione geometrica locale per questo [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush). |
| [deepClone()](#deepClone--) | Crea una copia esatta di questo [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush). |
| [setSigmaBellShape(float focus)](#setSigmaBellShape-float-) | Crea una caduta del gradiente basata su una curva a campana. |
| [setSigmaBellShape(float focus, float scale)](#setSigmaBellShape-float-float-) | Crea una caduta del gradiente basata su una curva a campana. |
| [setBlendTriangularShape(float focus)](#setBlendTriangularShape-float-) | Crea un gradiente lineare con un colore centrale e una caduta lineare verso un unico colore su entrambe le estremità. |
| [setBlendTriangularShape(float focus, float scale)](#setBlendTriangularShape-float-float-) | Crea un gradiente lineare con un colore centrale e una caduta lineare verso un unico colore su entrambe le estremità. |
| [resetTransform()](#resetTransform--) | Reimposta la proprietà `LinearGradientBrush.Transform` all'identità. |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-) | Moltiplica la [Matrix](../../com.aspose.drawing.drawing2d/matrix) che rappresenta la trasformazione geometrica locale di questo [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) per la [Matrix](../../com.aspose.drawing.drawing2d/matrix) specificata, anteponendo la [Matrix](../../com.aspose.drawing.drawing2d/matrix) specificata. |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-int-) | Moltiplica la [Matrix](../../com.aspose.drawing.drawing2d/matrix) che rappresenta la trasformazione geometrica locale di questo [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) per la [Matrix](../../com.aspose.drawing.drawing2d/matrix) specificata nell'ordine specificato. |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | Trasla la trasformazione geometrica locale per le dimensioni specificate. |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | Trasla la trasformazione geometrica locale per le dimensioni specificate nell'ordine specificato. |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | Scala la trasformazione geometrica locale per le quantità specificate. |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | Scala la trasformazione geometrica locale per le quantità specificate nell'ordine specificato. |
| [rotateTransform(float angle)](#rotateTransform-float-) | Ruota la trasformazione geometrica locale di una quantità specificata. |
| [rotateTransform(float angle, int order)](#rotateTransform-float-int-) | Ruota la trasformazione geometrica locale di una quantità specificata nell'ordine specificato. |
### LinearGradientBrush(PointF point1, PointF point2, Color color1, Color color2) {#LinearGradientBrush-com.aspose.drawing.PointF-com.aspose.drawing.PointF-com.aspose.drawing.Color-com.aspose.drawing.Color-}
```
public LinearGradientBrush(PointF point1, PointF point2, Color color1, Color color2)
```


Inizializza una nuova istanza della classe [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) con i punti e i colori specificati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| point1 | [PointF](../../com.aspose.drawing/pointf) | Una struttura [PointF](../../com.aspose.drawing/pointf) che rappresenta il punto di partenza del gradiente lineare. |
| point2 | [PointF](../../com.aspose.drawing/pointf) | Una struttura [PointF](../../com.aspose.drawing/pointf) che rappresenta il punto finale del gradiente lineare. |
| color1 | [Color](../../com.aspose.drawing/color) | Una struttura [Color](../../com.aspose.drawing/color) che rappresenta il colore iniziale del gradiente lineare. |
| color2 | [Color](../../com.aspose.drawing/color) | Una struttura [Color](../../com.aspose.drawing/color) che rappresenta il colore finale del gradiente lineare. |

### LinearGradientBrush(Point point1, Point point2, Color color1, Color color2) {#LinearGradientBrush-com.aspose.drawing.Point-com.aspose.drawing.Point-com.aspose.drawing.Color-com.aspose.drawing.Color-}
```
public LinearGradientBrush(Point point1, Point point2, Color color1, Color color2)
```


Inizializza una nuova istanza della classe [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) con i punti e i colori specificati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.drawing/point) | Una struttura [Point](../../com.aspose.drawing/point) che rappresenta il punto di partenza del gradiente lineare. |
| point2 | [Point](../../com.aspose.drawing/point) | Una struttura [Point](../../com.aspose.drawing/point) che rappresenta il punto finale del gradiente lineare. |
| color1 | [Color](../../com.aspose.drawing/color) | Una struttura [Color](../../com.aspose.drawing/color) che rappresenta il colore iniziale del gradiente lineare. |
| color2 | [Color](../../com.aspose.drawing/color) | Una struttura [Color](../../com.aspose.drawing/color) che rappresenta il colore finale del gradiente lineare. |

### LinearGradientBrush(RectangleF rect, Color color1, Color color2, int linearGradientMode) {#LinearGradientBrush-com.aspose.drawing.RectangleF-com.aspose.drawing.Color-com.aspose.drawing.Color-int-}
```
public LinearGradientBrush(RectangleF rect, Color color1, Color color2, int linearGradientMode)
```


Inizializza una nuova istanza della classe [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) basata su un rettangolo, colori di inizio e fine, e una modalità di orientamento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | Una struttura [RectangleF](../../com.aspose.drawing/rectanglef) che specifica i limiti del gradiente lineare. |
| color1 | [Color](../../com.aspose.drawing/color) | Una struttura [Color](../../com.aspose.drawing/color) che rappresenta il colore iniziale per il gradiente. |
| color2 | [Color](../../com.aspose.drawing/color) | Una struttura [Color](../../com.aspose.drawing/color) che rappresenta il colore finale per il gradiente. |
| linearGradientMode | int | Un elemento di enumerazione [LinearGradientMode](../../com.aspose.drawing.drawing2d/lineargradientmode) che specifica l'orientamento del gradiente. L'orientamento determina i punti di inizio e fine del gradiente. Ad esempio, LinearGradientMode.ForwardDiagonal specifica che il punto di partenza è l'angolo in alto a sinistra del rettangolo e il punto finale è l'angolo in basso a destra del rettangolo. |

### LinearGradientBrush(Rectangle rect, Color color1, Color color2, int linearGradientMode) {#LinearGradientBrush-com.aspose.drawing.Rectangle-com.aspose.drawing.Color-com.aspose.drawing.Color-int-}
```
public LinearGradientBrush(Rectangle rect, Color color1, Color color2, int linearGradientMode)
```


Inizializza una nuova istanza della classe [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) basata su un rettangolo, colori di inizio e fine, e orientamento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | Una struttura `Rectangle`([.getRectangle](../../null/\#getRectangle)) che specifica i limiti del gradiente lineare. |
| color1 | [Color](../../com.aspose.drawing/color) | Una struttura [Color](../../com.aspose.drawing/color) che rappresenta il colore iniziale per il gradiente. |
| color2 | [Color](../../com.aspose.drawing/color) | Una struttura [Color](../../com.aspose.drawing/color) che rappresenta il colore finale per il gradiente. |
| linearGradientMode | int | Un elemento di enumerazione [LinearGradientMode](../../com.aspose.drawing.drawing2d/lineargradientmode) che specifica l'orientamento del gradiente. L'orientamento determina i punti di inizio e fine del gradiente. Ad esempio, LinearGradientMode.ForwardDiagonal specifica che il punto di partenza è l'angolo in alto a sinistra del rettangolo e il punto finale è l'angolo in basso a destra del rettangolo. |

### LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle) {#LinearGradientBrush-com.aspose.drawing.RectangleF-com.aspose.drawing.Color-com.aspose.drawing.Color-float-}
```
public LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle)
```


Inizializza una nuova istanza della classe [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) basata su un rettangolo, colori di inizio e fine, e un angolo di orientamento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | Una struttura [RectangleF](../../com.aspose.drawing/rectanglef) che specifica i limiti del gradiente lineare. |
| color1 | [Color](../../com.aspose.drawing/color) | Una struttura [Color](../../com.aspose.drawing/color) che rappresenta il colore iniziale per il gradiente. |
| color2 | [Color](../../com.aspose.drawing/color) | Una struttura [Color](../../com.aspose.drawing/color) che rappresenta il colore finale per il gradiente. |
| angolo | float | L'angolo, misurato in gradi in senso orario dall'asse x, della linea di orientamento del gradiente. |

### LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle, boolean isAngleScaleable) {#LinearGradientBrush-com.aspose.drawing.RectangleF-com.aspose.drawing.Color-com.aspose.drawing.Color-float-boolean-}
```
public LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle, boolean isAngleScaleable)
```


Inizializza una nuova istanza della classe [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) basata su un rettangolo, colori di inizio e fine, e un angolo di orientamento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | Una struttura [RectangleF](../../com.aspose.drawing/rectanglef) che specifica i limiti del gradiente lineare. |
| color1 | [Color](../../com.aspose.drawing/color) | Una struttura [Color](../../com.aspose.drawing/color) che rappresenta il colore iniziale per il gradiente. |
| color2 | [Color](../../com.aspose.drawing/color) | Una struttura [Color](../../com.aspose.drawing/color) che rappresenta il colore finale per il gradiente. |
| angolo | float | L'angolo, misurato in gradi in senso orario dall'asse x, della linea di orientamento del gradiente. |
| isAngleScaleable | boolean | Impostare su true per specificare che l'angolo è influenzato dalla trasformazione associata a questo [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush); altrimenti, false. |

### LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle) {#LinearGradientBrush-com.aspose.drawing.Rectangle-com.aspose.drawing.Color-com.aspose.drawing.Color-float-}
```
public LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle)
```


Inizializza una nuova istanza della classe [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) basata su un rettangolo, colori di inizio e fine, e un angolo di orientamento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | Una struttura `Rectangle`([.getRectangle](../../null/\#getRectangle)) che specifica i limiti del gradiente lineare. |
| color1 | [Color](../../com.aspose.drawing/color) | Una struttura [Color](../../com.aspose.drawing/color) che rappresenta il colore iniziale per il gradiente. |
| color2 | [Color](../../com.aspose.drawing/color) | Una struttura [Color](../../com.aspose.drawing/color) che rappresenta il colore finale per il gradiente. |
| angolo | float | L'angolo, misurato in gradi in senso orario dall'asse x, della linea di orientamento del gradiente. |

### LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle, boolean isAngleScaleable) {#LinearGradientBrush-com.aspose.drawing.Rectangle-com.aspose.drawing.Color-com.aspose.drawing.Color-float-boolean-}
```
public LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle, boolean isAngleScaleable)
```


Inizializza una nuova istanza della classe [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) basata su un rettangolo, colori di inizio e fine, e un angolo di orientamento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | Una struttura `Rectangle`([.getRectangle](../../null/\#getRectangle)) che specifica i limiti del gradiente lineare. |
| color1 | [Color](../../com.aspose.drawing/color) | Una struttura [Color](../../com.aspose.drawing/color) che rappresenta il colore iniziale per il gradiente. |
| color2 | [Color](../../com.aspose.drawing/color) | Una struttura [Color](../../com.aspose.drawing/color) che rappresenta il colore finale per il gradiente. |
| angolo | float | L'angolo, misurato in gradi in senso orario dall'asse x, della linea di orientamento del gradiente. |
| isAngleScaleable | boolean | Impostare su true per specificare che l'angolo è influenzato dalla trasformazione associata a questo [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush); altrimenti, false. |

### getLinearColors() {#getLinearColors--}
```
public Color[] getLinearColors()
```


Ottiene o imposta i colori di inizio e fine del gradiente.

**Returns:**
com.aspose.drawing.Color[]
### setLinearColors(Color[] value) {#setLinearColors-com.aspose.drawing.Color---}
```
public void setLinearColors(Color[] value)
```


Ottiene o imposta i colori di inizio e fine del gradiente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Color\[\]](../../com.aspose.drawing/color) |  |

### getRectangle() {#getRectangle--}
```
public RectangleF getRectangle()
```


Ottiene una regione rettangolare che definisce i punti di inizio e fine del gradiente.

**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef)
### getGammaCorrection() {#getGammaCorrection--}
```
public boolean getGammaCorrection()
```


Ottiene o imposta un valore che indica se la correzione gamma è abilitata per questo [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush).

**Returns:**
boolean
### setGammaCorrection(boolean value) {#setGammaCorrection-boolean-}
```
public void setGammaCorrection(boolean value)
```


Ottiene o imposta un valore che indica se la correzione gamma è abilitata per questo [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

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

### getWrapMode() {#getWrapMode--}
```
public int getWrapMode()
```


Ottiene o imposta un'enumerazione `WrapMode` che indica la modalità di avvolgimento per questo [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush).

**Returns:**
int
### setWrapMode(int value) {#setWrapMode-int-}
```
public void setWrapMode(int value)
```


Ottiene o imposta un'enumerazione `WrapMode` che indica la modalità di avvolgimento per questo [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getTransform() {#getTransform--}
```
public Matrix getTransform()
```


Ottiene o imposta una copia di [Matrix](../../com.aspose.drawing.drawing2d/matrix) che definisce una trasformazione geometrica locale per questo [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush).

**Returns:**
[Matrix](../../com.aspose.drawing.drawing2d/matrix)
### setTransform(Matrix value) {#setTransform-com.aspose.drawing.drawing2d.Matrix-}
```
public void setTransform(Matrix value)
```


Ottiene o imposta una copia di [Matrix](../../com.aspose.drawing.drawing2d/matrix) che definisce una trasformazione geometrica locale per questo [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.drawing.drawing2d/matrix) |  |

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Crea una copia esatta di questo [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush).

**Returns:**
java.lang.Object - Il [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) che questo metodo crea, convertito in un oggetto.
### setSigmaBellShape(float focus) {#setSigmaBellShape-float-}
```
public void setSigmaBellShape(float focus)
```


Crea una caduta del gradiente basata su una curva a campana.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| focus | float | Un valore compreso tra 0 e 1 che specifica il centro del gradiente (il punto in cui il colore iniziale e il colore finale sono mescolati in modo uguale). |

### setSigmaBellShape(float focus, float scale) {#setSigmaBellShape-float-float-}
```
public void setSigmaBellShape(float focus, float scale)
```


Crea una caduta del gradiente basata su una curva a campana.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| focus | float | Un valore compreso tra 0 e 1 che specifica il centro del gradiente (il punto in cui il gradiente è composto solo dal colore finale). |
| scala | float | Un valore compreso tra 0 e 1 che specifica la rapidità con cui i colori diminuiscono dal `focus`. |

### setBlendTriangularShape(float focus) {#setBlendTriangularShape-float-}
```
public void setBlendTriangularShape(float focus)
```


Crea un gradiente lineare con un colore centrale e una caduta lineare verso un unico colore su entrambe le estremità.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| focus | float | Un valore compreso tra 0 e 1 che specifica il centro del gradiente (il punto in cui il gradiente è composto solo dal colore finale). |

### setBlendTriangularShape(float focus, float scale) {#setBlendTriangularShape-float-float-}
```
public void setBlendTriangularShape(float focus, float scale)
```


Crea un gradiente lineare con un colore centrale e una caduta lineare verso un unico colore su entrambe le estremità.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| focus | float | Un valore compreso tra 0 e 1 che specifica il centro del gradiente (il punto in cui il gradiente è composto solo dal colore finale). |
| scala | float | Un valore compreso tra 0 e 1 che specifica la rapidità con cui i colori diminuiscono dal colore iniziale al `focus` (colore finale) |

### resetTransform() {#resetTransform--}
```
public void resetTransform()
```


Reimposta la proprietà `LinearGradientBrush.Transform` all'identità.

### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-}
```
public void multiplyTransform(Matrix matrix)
```


Moltiplica la [Matrix](../../com.aspose.drawing.drawing2d/matrix) che rappresenta la trasformazione geometrica locale di questo [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) per la [Matrix](../../com.aspose.drawing.drawing2d/matrix) specificata, anteponendo la [Matrix](../../com.aspose.drawing.drawing2d/matrix) specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | La [Matrix](../../com.aspose.drawing.drawing2d/matrix) con cui moltiplicare la trasformazione geometrica. |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-int-}
```
public void multiplyTransform(Matrix matrix, int order)
```


Moltiplica la [Matrix](../../com.aspose.drawing.drawing2d/matrix) che rappresenta la trasformazione geometrica locale di questo [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) per la [Matrix](../../com.aspose.drawing.drawing2d/matrix) specificata nell'ordine specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | La [Matrix](../../com.aspose.drawing.drawing2d/matrix) con cui moltiplicare la trasformazione geometrica. |
| order | int | Un [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder) che specifica in quale ordine moltiplicare le due matrici. |

### translateTransform(float dx, float dy) {#translateTransform-float-float-}
```
public void translateTransform(float dx, float dy)
```


Trasla la trasformazione geometrica locale delle dimensioni specificate. Questo metodo antepone la traslazione alla trasformazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dx | float | Il valore della traslazione in x. |
| dy | float | Il valore della traslazione in y. |

### translateTransform(float dx, float dy, int order) {#translateTransform-float-float-int-}
```
public void translateTransform(float dx, float dy, int order)
```


Trasla la trasformazione geometrica locale per le dimensioni specificate nell'ordine specificato.

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
| sx | float | La quantità di scala della trasformazione nella direzione dell'asse x. |
| sy | float | La quantità di scala della trasformazione nella direzione dell'asse y. |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public void scaleTransform(float sx, float sy, int order)
```


Scala la trasformazione geometrica locale per le quantità specificate nell'ordine specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sx | float | La quantità di scala della trasformazione nella direzione dell'asse x. |
| sy | float | La quantità di scala della trasformazione nella direzione dell'asse y. |
| order | int | Un [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder) che specifica se aggiungere o anteporre la matrice di scala. |

### rotateTransform(float angle) {#rotateTransform-float-}
```
public void rotateTransform(float angle)
```


Ruota la trasformazione geometrica locale della quantità specificata. Questo metodo antepone la rotazione alla trasformazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| angolo | float | L'angolo di rotazione. |

### rotateTransform(float angle, int order) {#rotateTransform-float-int-}
```
public void rotateTransform(float angle, int order)
```


Ruota la trasformazione geometrica locale di una quantità specificata nell'ordine specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| angolo | float | L'angolo di rotazione. |
| order | int | Un [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder) che specifica se aggiungere o anteporre la matrice di rotazione. |

