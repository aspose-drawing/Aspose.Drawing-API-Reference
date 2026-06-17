---
title: Pen
second_title: Riferimento API di Aspose.Drawing per Java
description: Definisce un oggetto utilizzato per disegnare linee e curve.
type: docs
weight: 34
url: /it/java/com.aspose.drawing/pen/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public class Pen implements System.IDisposable
```

Definisce un oggetto utilizzato per disegnare linee e curve.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Pen(Color color)](#Pen-com.aspose.drawing.Color-) | Inizializza una nuova istanza della classe [Pen](../../com.aspose.drawing/pen) con il `Color` specificato([.getColor](../../null/\#getColor)/[.setColor(Color)](../../null/\#setColor-Color-)). |
| [Pen(Brush brush, float width)](#Pen-com.aspose.drawing.Brush-float-) | Inizializza una nuova istanza della classe Pen con il Brush e la Width specificati. |
| [Pen(Brush brush)](#Pen-com.aspose.drawing.Brush-) | Inizializza una nuova istanza della classe [Pen](../../com.aspose.drawing/pen) con il `Brush` specificato([.getBrush](../../null/\#getBrush)/[.setBrush(Brush)](../../null/\#setBrush-Brush-)). |
| [Pen(Color color, float width)](#Pen-com.aspose.drawing.Color-float-) | Inizializza una nuova istanza della classe Pen con le proprietà Color e Width specificate. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getColor()](#getColor--) | Ottiene o imposta il colore di questo [Pen](../../com.aspose.drawing/pen). |
| [setColor(Color value)](#setColor-com.aspose.drawing.Color-) | Ottiene o imposta il colore di questo [Pen](../../com.aspose.drawing/pen). |
| [getBrush()](#getBrush--) | Ottiene o imposta il Brush che determina gli attributi di questo [Pen](../../com.aspose.drawing/pen). |
| [setBrush(Brush value)](#setBrush-com.aspose.drawing.Brush-) | Ottiene o imposta il Brush che determina gli attributi di questo [Pen](../../com.aspose.drawing/pen). |
| [getCompoundArray()](#getCompoundArray--) | Ottiene o imposta un array di valori che specifica una penna composta. |
| [setCompoundArray(float[] value)](#setCompoundArray-float---) | Ottiene o imposta un array di valori che specifica una penna composta. |
| [getWidth()](#getWidth--) | Ottiene o imposta la larghezza di questo Pen, nelle unità dell'oggetto Graphics utilizzato per il disegno. |
| [setWidth(float value)](#setWidth-float-) | Ottiene o imposta la larghezza di questo Pen, nelle unità dell'oggetto Graphics utilizzato per il disegno. |
| [getStartCap()](#getStartCap--) | Ottiene o imposta lo stile di cap usato all'inizio delle linee disegnate con questo Pen. |
| [setStartCap(int value)](#setStartCap-int-) | Ottiene o imposta lo stile di cap usato all'inizio delle linee disegnate con questo Pen. |
| [getEndCap()](#getEndCap--) | Ottiene o imposta lo stile di cap usato alla fine delle linee disegnate con questo Pen. |
| [setEndCap(int value)](#setEndCap-int-) | Ottiene o imposta lo stile di cap usato alla fine delle linee disegnate con questo Pen. |
| [getLineJoin()](#getLineJoin--) | Ottiene o imposta lo stile di join per le estremità di due linee consecutive disegnate con questo Pen. |
| [setLineJoin(int value)](#setLineJoin-int-) | Ottiene o imposta lo stile di join per le estremità di due linee consecutive disegnate con questo Pen. |
| [getMiterLimit()](#getMiterLimit--) | Ottiene o imposta il limite dello spessore del join su un angolo a spigolo. |
| [setMiterLimit(float value)](#setMiterLimit-float-) | Ottiene o imposta il limite dello spessore del join su un angolo a spigolo. |
| [getAlignment()](#getAlignment--) | Ottiene o imposta l'allineamento per questo [Pen](../../com.aspose.drawing/pen). |
| [setAlignment(int value)](#setAlignment-int-) | Ottiene o imposta l'allineamento per questo [Pen](../../com.aspose.drawing/pen). |
| [getTransform()](#getTransform--) | Ottiene o imposta una copia della trasformazione geometrica per questo [Pen](../../com.aspose.drawing/pen). |
| [setTransform(Matrix value)](#setTransform-com.aspose.drawing.drawing2d.Matrix-) | Ottiene o imposta una copia della trasformazione geometrica per questo [Pen](../../com.aspose.drawing/pen). |
| [getCustomStartCap()](#getCustomStartCap--) | Ottiene o imposta un cap personalizzato da usare all'inizio delle linee disegnate con questo [Pen](../../com.aspose.drawing/pen). |
| [setCustomStartCap(CustomLineCap value)](#setCustomStartCap-com.aspose.drawing.drawing2d.CustomLineCap-) | Ottiene o imposta un cap personalizzato da usare all'inizio delle linee disegnate con questo [Pen](../../com.aspose.drawing/pen). |
| [getCustomEndCap()](#getCustomEndCap--) | Ottiene o imposta un cap personalizzato da usare alla fine delle linee disegnate con questo [Pen](../../com.aspose.drawing/pen). |
| [setCustomEndCap(CustomLineCap value)](#setCustomEndCap-com.aspose.drawing.drawing2d.CustomLineCap-) | Ottiene o imposta un cap personalizzato da usare alla fine delle linee disegnate con questo [Pen](../../com.aspose.drawing/pen). |
| [getDashCap()](#getDashCap--) | Ottiene o imposta lo stile di cap usato alla fine dei trattini che compongono le linee tratteggiate disegnate con questo [Pen](../../com.aspose.drawing/pen). |
| [setDashCap(int value)](#setDashCap-int-) | Ottiene o imposta lo stile di cap usato alla fine dei trattini che compongono le linee tratteggiate disegnate con questo [Pen](../../com.aspose.drawing/pen). |
| [getDashOffset()](#getDashOffset--) | Ottiene o imposta la distanza dall'inizio di una linea all'inizio di un modello di trattino. |
| [setDashOffset(float value)](#setDashOffset-float-) | Ottiene o imposta la distanza dall'inizio di una linea all'inizio di un modello di trattino. |
| [getDashPattern()](#getDashPattern--) | Ottiene o imposta un array di trattini e spazi personalizzati. |
| [setDashPattern(float[] value)](#setDashPattern-float---) | Ottiene o imposta un array di trattini e spazi personalizzati. |
| [getDashStyle()](#getDashStyle--) | Ottiene o imposta lo stile usato per le linee tratteggiate disegnate con questo [Pen](../../com.aspose.drawing/pen). |
| [setDashStyle(int value)](#setDashStyle-int-) | Ottiene o imposta lo stile usato per le linee tratteggiate disegnate con questo [Pen](../../com.aspose.drawing/pen). |
| [getPenType()](#getPenType--) | Ottiene lo stile delle linee disegnate con questo Pen. |
| [dispose()](#dispose--) | Rilascia tutte le risorse utilizzate da questo Pen. |
| [deepClone()](#deepClone--) | Crea una copia esatta di questo [Pen](../../com.aspose.drawing/pen). |
| [setLineCap(int startCap, int endCap, int dashCap)](#setLineCap-int-int-int-) | Imposta i valori che determinano lo stile del cap usato per terminare le linee disegnate da questo [Pen](../../com.aspose.drawing/pen). |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | Scala la trasformazione geometrica locale per i fattori specificati. |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | Scala la trasformazione geometrica locale per i fattori specificati nell'ordine specificato. |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | Trasla la trasformazione geometrica locale per le dimensioni specificate. |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | Trasla la trasformazione geometrica locale per le dimensioni specificate nell'ordine specificato. |
| [rotateTransform(float angle)](#rotateTransform-float-) | Ruota la trasformazione geometrica locale per l'angolo specificato. |
| [rotateTransform(float angle, int order)](#rotateTransform-float-int-) | Ruota la trasformazione geometrica locale per l'angolo specificato nell'ordine specificato. |
| [resetTransform()](#resetTransform--) | Reimposta la matrice di trasformazione geometrica per questo [Pen](../../com.aspose.drawing/pen) all'identità. |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-) | Moltiplica la matrice di trasformazione per questo [Pen](../../com.aspose.drawing/pen) per la [Matrix](../../com.aspose.drawing.drawing2d/matrix) specificata. |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-int-) | Moltiplica la matrice di trasformazione per questo [Pen](../../com.aspose.drawing/pen) per la [Matrix](../../com.aspose.drawing.drawing2d/matrix) specificata nell'ordine specificato. |
### Pen(Color color) {#Pen-com.aspose.drawing.Color-}
```
public Pen(Color color)
```


Inizializza una nuova istanza della classe [Pen](../../com.aspose.drawing/pen) con il `Color` specificato([.getColor](../../null/\#getColor)/[.setColor(Color)](../../null/\#setColor-Color-)).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| color | [Color](../../com.aspose.drawing/color) | Un `Color`([.getColor](../../null/\#getColor)/[.setColor(Color)](../../null/\#setColor-Color-)) che determina le proprietà di riempimento di questo [Pen](../../com.aspose.drawing/pen). |

### Pen(Brush brush, float width) {#Pen-com.aspose.drawing.Brush-float-}
```
public Pen(Brush brush, float width)
```


Inizializza una nuova istanza della classe Pen con il Brush e la Width specificati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.drawing/brush) | Un Brush che determina le caratteristiche di questo Pen. |
| width | float | La larghezza del nuovo Pen. |

### Pen(Brush brush) {#Pen-com.aspose.drawing.Brush-}
```
public Pen(Brush brush)
```


Inizializza una nuova istanza della classe [Pen](../../com.aspose.drawing/pen) con il `Brush` specificato([.getBrush](../../null/\#getBrush)/[.setBrush(Brush)](../../null/\#setBrush-Brush-)).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.drawing/brush) | Un `Brush`([.getBrush](../../null/\#getBrush)/[.setBrush(Brush)](../../null/\#setBrush-Brush-)) che determina le proprietà di riempimento di questo [Pen](../../com.aspose.drawing/pen). |

### Pen(Color color, float width) {#Pen-com.aspose.drawing.Color-float-}
```
public Pen(Color color, float width)
```


Inizializza una nuova istanza della classe Pen con le proprietà Color e Width specificate.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| color | [Color](../../com.aspose.drawing/color) | Una struttura Color che indica il colore di questo Pen. |
| width | float | Un valore che indica la larghezza di questo Pen. |

### getColor() {#getColor--}
```
public final Color getColor()
```


Ottiene o imposta il colore di questo [Pen](../../com.aspose.drawing/pen).

Valore: Una struttura `Color`([.getColor](../../null/\#getColor)/[.setColor(Color)](../../null/\#setColor-Color-)) che rappresenta il colore di questo [Pen](../../com.aspose.drawing/pen).

**Returns:**
[Color](../../com.aspose.drawing/color)
### setColor(Color value) {#setColor-com.aspose.drawing.Color-}
```
public final void setColor(Color value)
```


Ottiene o imposta il colore di questo [Pen](../../com.aspose.drawing/pen).

Valore: Una struttura `Color`([.getColor](../../null/\#getColor)/[.setColor(Color)](../../null/\#setColor-Color-)) che rappresenta il colore di questo [Pen](../../com.aspose.drawing/pen).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Color](../../com.aspose.drawing/color) |  |

### getBrush() {#getBrush--}
```
public final Brush getBrush()
```


Ottiene o imposta il Brush che determina gli attributi di questo [Pen](../../com.aspose.drawing/pen).

**Returns:**
[Brush](../../com.aspose.drawing/brush)
### setBrush(Brush value) {#setBrush-com.aspose.drawing.Brush-}
```
public final void setBrush(Brush value)
```


Ottiene o imposta il Brush che determina gli attributi di questo [Pen](../../com.aspose.drawing/pen).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Brush](../../com.aspose.drawing/brush) |  |

### getCompoundArray() {#getCompoundArray--}
```
public final float[] getCompoundArray()
```


Ottiene o imposta un array di valori che specifica una penna composta. Una penna composta disegna una linea composta formata da linee parallele e spazi.

**Returns:**
float[] - Un array di numeri reali che specifica l'array composto. Gli elementi nell'array devono essere in ordine crescente, non inferiori a 0 e non superiori a 1.
### setCompoundArray(float[] value) {#setCompoundArray-float---}
```
public final void setCompoundArray(float[] value)
```


Ottiene o imposta un array di valori che specifica una penna composta. Una penna composta disegna una linea composta formata da linee parallele e spazi.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float[] |  |

### getWidth() {#getWidth--}
```
public final float getWidth()
```


Ottiene o imposta la larghezza di questo Pen, nelle unità dell'oggetto Graphics utilizzato per il disegno.

**Returns:**
float
### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```


Ottiene o imposta la larghezza di questo Pen, nelle unità dell'oggetto Graphics utilizzato per il disegno.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float |  |

### getStartCap() {#getStartCap--}
```
public final int getStartCap()
```


Ottiene o imposta lo stile di cap usato all'inizio delle linee disegnate con questo Pen.

**Returns:**
int
### setStartCap(int value) {#setStartCap-int-}
```
public final void setStartCap(int value)
```


Ottiene o imposta lo stile di cap usato all'inizio delle linee disegnate con questo Pen.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getEndCap() {#getEndCap--}
```
public final int getEndCap()
```


Ottiene o imposta lo stile di cap usato alla fine delle linee disegnate con questo Pen.

**Returns:**
int
### setEndCap(int value) {#setEndCap-int-}
```
public final void setEndCap(int value)
```


Ottiene o imposta lo stile di cap usato alla fine delle linee disegnate con questo Pen.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getLineJoin() {#getLineJoin--}
```
public final int getLineJoin()
```


Ottiene o imposta lo stile di join per le estremità di due linee consecutive disegnate con questo Pen.

--------------------

Al momento la giunzione a spigolo funziona effettivamente come MiterClipped.

**Returns:**
int
### setLineJoin(int value) {#setLineJoin-int-}
```
public final void setLineJoin(int value)
```


Ottiene o imposta lo stile di join per le estremità di due linee consecutive disegnate con questo Pen.

--------------------

Al momento la giunzione a spigolo funziona effettivamente come MiterClipped.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getMiterLimit() {#getMiterLimit--}
```
public final float getMiterLimit()
```


Ottiene o imposta il limite dello spessore del join su un angolo a spigolo.

**Returns:**
float
### setMiterLimit(float value) {#setMiterLimit-float-}
```
public final void setMiterLimit(float value)
```


Ottiene o imposta il limite dello spessore del join su un angolo a spigolo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float |  |

### getAlignment() {#getAlignment--}
```
public final int getAlignment()
```


Ottiene o imposta l'allineamento per questo [Pen](../../com.aspose.drawing/pen).

**Returns:**
int - Un [PenAlignment](../../com.aspose.drawing.drawing2d/penalignment) che rappresenta l'allineamento per questo [Pen](../../com.aspose.drawing/pen).
### setAlignment(int value) {#setAlignment-int-}
```
public final void setAlignment(int value)
```


Ottiene o imposta l'allineamento per questo [Pen](../../com.aspose.drawing/pen).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getTransform() {#getTransform--}
```
public final Matrix getTransform()
```


Ottiene o imposta una copia della trasformazione geometrica per questo [Pen](../../com.aspose.drawing/pen).

Valore: Una copia della [Matrix](../../com.aspose.drawing.drawing2d/matrix) che rappresenta la trasformazione geometrica per questo [Pen](../../com.aspose.drawing/pen).

**Returns:**
[Matrix](../../com.aspose.drawing.drawing2d/matrix)
### setTransform(Matrix value) {#setTransform-com.aspose.drawing.drawing2d.Matrix-}
```
public final void setTransform(Matrix value)
```


Ottiene o imposta una copia della trasformazione geometrica per questo [Pen](../../com.aspose.drawing/pen).

Valore: Una copia della [Matrix](../../com.aspose.drawing.drawing2d/matrix) che rappresenta la trasformazione geometrica per questo [Pen](../../com.aspose.drawing/pen).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.drawing.drawing2d/matrix) |  |

### getCustomStartCap() {#getCustomStartCap--}
```
public final CustomLineCap getCustomStartCap()
```


Ottiene o imposta un cap personalizzato da usare all'inizio delle linee disegnate con questo [Pen](../../com.aspose.drawing/pen).

**Returns:**
[CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) - A [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) that represents the cap used at the beginning of lines drawn with this [Pen](../../com.aspose.drawing/pen).
### setCustomStartCap(CustomLineCap value) {#setCustomStartCap-com.aspose.drawing.drawing2d.CustomLineCap-}
```
public final void setCustomStartCap(CustomLineCap value)
```


Ottiene o imposta un cap personalizzato da usare all'inizio delle linee disegnate con questo [Pen](../../com.aspose.drawing/pen).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) |  |

### getCustomEndCap() {#getCustomEndCap--}
```
public final CustomLineCap getCustomEndCap()
```


Ottiene o imposta un cap personalizzato da usare alla fine delle linee disegnate con questo [Pen](../../com.aspose.drawing/pen).

**Returns:**
[CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) - A [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) that represents the cap used at the end of lines drawn with this [Pen](../../com.aspose.drawing/pen).
### setCustomEndCap(CustomLineCap value) {#setCustomEndCap-com.aspose.drawing.drawing2d.CustomLineCap-}
```
public final void setCustomEndCap(CustomLineCap value)
```


Ottiene o imposta un cap personalizzato da usare alla fine delle linee disegnate con questo [Pen](../../com.aspose.drawing/pen).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) |  |

### getDashCap() {#getDashCap--}
```
public final int getDashCap()
```


Ottiene o imposta lo stile di cap usato alla fine dei trattini che compongono le linee tratteggiate disegnate con questo [Pen](../../com.aspose.drawing/pen).

**Returns:**
int - Uno dei valori `DashCap`([.getDashCap](../../null/\#getDashCap)/[.setDashCap(int)](../../null/\#setDashCap-int-)) che rappresenta lo stile del cap usato all'inizio e alla fine dei trattini che compongono le linee tratteggiate disegnate con questo [Pen](../../com.aspose.drawing/pen).
### setDashCap(int value) {#setDashCap-int-}
```
public final void setDashCap(int value)
```


Ottiene o imposta lo stile di cap usato alla fine dei trattini che compongono le linee tratteggiate disegnate con questo [Pen](../../com.aspose.drawing/pen).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getDashOffset() {#getDashOffset--}
```
public final float getDashOffset()
```


Ottiene o imposta la distanza dall'inizio di una linea all'inizio di un modello di trattino.

**Returns:**
float - La distanza dall'inizio di una linea all'inizio di un modello di tratto.
### setDashOffset(float value) {#setDashOffset-float-}
```
public final void setDashOffset(float value)
```


Ottiene o imposta la distanza dall'inizio di una linea all'inizio di un modello di trattino.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float |  |

### getDashPattern() {#getDashPattern--}
```
public final float[] getDashPattern()
```


Ottiene o imposta un array di trattini e spazi personalizzati.

**Returns:**
float[] - Un array di numeri reali che specifica le lunghezze di trattini e spazi alternati nelle linee tratteggiate.
### setDashPattern(float[] value) {#setDashPattern-float---}
```
public final void setDashPattern(float[] value)
```


Ottiene o imposta un array di trattini e spazi personalizzati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float[] |  |

### getDashStyle() {#getDashStyle--}
```
public final int getDashStyle()
```


Ottiene o imposta lo stile usato per le linee tratteggiate disegnate con questo [Pen](../../com.aspose.drawing/pen).

**Returns:**
int - Un `DashStyle`([.getDashStyle](../../null/\#getDashStyle)/[.setDashStyle(int)](../../null/\#setDashStyle-int-)) che rappresenta lo stile usato per le linee tratteggiate disegnate con questo [Pen](../../com.aspose.drawing/pen).
### setDashStyle(int value) {#setDashStyle-int-}
```
public final void setDashStyle(int value)
```


Ottiene o imposta lo stile usato per le linee tratteggiate disegnate con questo [Pen](../../com.aspose.drawing/pen).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getPenType() {#getPenType--}
```
public final int getPenType()
```


Ottiene lo stile delle linee disegnate con questo Pen.

Valore: Un'enumerazione `PenType`([.getPenType](../../null/\#getPenType)) che specifica lo stile delle linee disegnate con questo [Pen](../../com.aspose.drawing/pen).

**Returns:**
int
### dispose() {#dispose--}
```
public final void dispose()
```


Rilascia tutte le risorse utilizzate da questo Pen.

--------------------

Questo metodo in realtà non fa nulla. È solo per compatibilità con l'API System.Drawing.

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Crea una copia esatta di questo [Pen](../../com.aspose.drawing/pen).

**Returns:**
java.lang.Object - Un oggetto che può essere convertito in un [Pen](../../com.aspose.drawing/pen).
### setLineCap(int startCap, int endCap, int dashCap) {#setLineCap-int-int-int-}
```
public final void setLineCap(int startCap, int endCap, int dashCap)
```


Imposta i valori che determinano lo stile del cap usato per terminare le linee disegnate da questo [Pen](../../com.aspose.drawing/pen).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| startCap | int | Un [LineCap](../../com.aspose.drawing.drawing2d/linecap) che rappresenta lo stile di estremità da usare all'inizio delle linee disegnate con questo [Pen](../../com.aspose.drawing/pen). |
| endCap | int | Un [LineCap](../../com.aspose.drawing.drawing2d/linecap) che rappresenta lo stile di estremità da usare alla fine delle linee disegnate con questo [Pen](../../com.aspose.drawing/pen). |
| dashCap | int | Un [LineCap](../../com.aspose.drawing.drawing2d/linecap) che rappresenta lo stile di estremità da usare all'inizio o alla fine delle linee tratteggiate disegnate con questo [Pen](../../com.aspose.drawing/pen). |

### scaleTransform(float sx, float sy) {#scaleTransform-float-float-}
```
public final void scaleTransform(float sx, float sy)
```


Scala la trasformazione geometrica locale dei fattori specificati. Questo metodo antepone la matrice di scala alla trasformazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sx | float | Il fattore con cui scalare la trasformazione nella direzione dell'asse x. |
| sy | float | Il fattore con cui scalare la trasformazione nella direzione dell'asse y. |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public final void scaleTransform(float sx, float sy, int order)
```


Scala la trasformazione geometrica locale per i fattori specificati nell'ordine specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sx | float | Il fattore con cui scalare la trasformazione nella direzione dell'asse x. |
| sy | float | Il fattore con cui scalare la trasformazione nella direzione dell'asse y. |
| order | int | Un [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder) che specifica se aggiungere o anteporre la matrice di scala. |

### translateTransform(float dx, float dy) {#translateTransform-float-float-}
```
public final void translateTransform(float dx, float dy)
```


Trasla la trasformazione geometrica locale delle dimensioni specificate. Questo metodo antepone la traslazione alla trasformazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dx | float | Il valore della traslazione in x. |
| dy | float | Il valore della traslazione in y. |

### translateTransform(float dx, float dy, int order) {#translateTransform-float-float-int-}
```
public final void translateTransform(float dx, float dy, int order)
```


Trasla la trasformazione geometrica locale per le dimensioni specificate nell'ordine specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dx | float | Il valore della traslazione in x. |
| dy | float | Il valore della traslazione in y. |
| ordine | int | L'ordine (anteporre o aggiungere) con cui applicare la traslazione. |

### rotateTransform(float angle) {#rotateTransform-float-}
```
public final void rotateTransform(float angle)
```


Ruota la trasformazione geometrica locale dell'angolo specificato. Questo metodo antepone la rotazione alla trasformazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| angolo | float | L'angolo di rotazione. |

### rotateTransform(float angle, int order) {#rotateTransform-float-int-}
```
public final void rotateTransform(float angle, int order)
```


Ruota la trasformazione geometrica locale per l'angolo specificato nell'ordine specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| angolo | float | L'angolo di rotazione. |
| order | int | Un [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder) che specifica se aggiungere o anteporre la matrice di rotazione. |

### resetTransform() {#resetTransform--}
```
public final void resetTransform()
```


Reimposta la matrice di trasformazione geometrica per questo [Pen](../../com.aspose.drawing/pen) all'identità.

### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-}
```
public final void multiplyTransform(Matrix matrix)
```


Moltiplica la matrice di trasformazione per questo [Pen](../../com.aspose.drawing/pen) per la [Matrix](../../com.aspose.drawing.drawing2d/matrix) specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | L'oggetto [Matrix](../../com.aspose.drawing.drawing2d/matrix) con cui moltiplicare la matrice di trasformazione. |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-int-}
```
public final void multiplyTransform(Matrix matrix, int order)
```


Moltiplica la matrice di trasformazione per questo [Pen](../../com.aspose.drawing/pen) per la [Matrix](../../com.aspose.drawing.drawing2d/matrix) specificata nell'ordine specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | Il java.awt.geom.AffineTransform con cui moltiplicare la matrice di trasformazione. |
| ordine | int | L'ordine con cui eseguire l'operazione di moltiplicazione. |

