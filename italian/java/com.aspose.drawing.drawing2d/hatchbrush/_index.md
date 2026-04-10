---
title: HatchBrush
second_title: Riferimento API di Aspose.Drawing per Java
description: Definisce un pennello rettangolare con uno stile a trama, un colore di primo piano e un colore di sfondo.
type: docs
weight: 26
url: /it/java/com.aspose.drawing.drawing2d/hatchbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.drawing.Brush](../../com.aspose.drawing/brush)
```
public final class HatchBrush extends Brush
```

Definisce un pennello rettangolare con uno stile a trama, un colore di primo piano e un colore di sfondo. Questa classe non può essere ereditata.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [HatchBrush(int hatchstyle, Color foreColor)](#HatchBrush-int-com.aspose.drawing.Color-) | Inizializza una nuova istanza della classe [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) con l'enumerazione `HatchStyle`([.getHatchStyle](../../null/\#getHatchStyle)) specificata e il colore di primo piano. |
| [HatchBrush(int hatchstyle, Color foreColor, Color backColor)](#HatchBrush-int-com.aspose.drawing.Color-com.aspose.drawing.Color-) | Inizializza una nuova istanza della classe [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) con l'enumerazione `HatchStyle`([.getHatchStyle](../../null/\#getHatchStyle)) specificata, il colore di primo piano e il colore di sfondo. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getHatchStyle()](#getHatchStyle--) | Restituisce lo stile a trama di questo oggetto [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush). |
| [getForegroundColor()](#getForegroundColor--) | Restituisce il colore delle linee a trama disegnate da questo oggetto [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush). |
| [getBackgroundColor()](#getBackgroundColor--) | Restituisce il colore degli spazi tra le linee a trama disegnate da questo oggetto [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush). |
| [deepClone()](#deepClone--) | Crea una copia esatta di questo oggetto [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush). |
### HatchBrush(int hatchstyle, Color foreColor) {#HatchBrush-int-com.aspose.drawing.Color-}
```
public HatchBrush(int hatchstyle, Color foreColor)
```


Inizializza una nuova istanza della classe [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) con l'enumerazione `HatchStyle`([.getHatchStyle](../../null/\#getHatchStyle)) specificata e il colore di primo piano.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| hatchstyle | int | Uno dei valori `HatchStyle`([.getHatchStyle](../../null/\#getHatchStyle)) che rappresenta il modello disegnato da questo [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush). |
| foreColor | [Color](../../com.aspose.drawing/color) | La struttura [Color](../../com.aspose.drawing/color) che rappresenta il colore delle linee disegnate da questo [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush). |

### HatchBrush(int hatchstyle, Color foreColor, Color backColor) {#HatchBrush-int-com.aspose.drawing.Color-com.aspose.drawing.Color-}
```
public HatchBrush(int hatchstyle, Color foreColor, Color backColor)
```


Inizializza una nuova istanza della classe [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) con l'enumerazione `HatchStyle`([.getHatchStyle](../../null/\#getHatchStyle)) specificata, il colore di primo piano e il colore di sfondo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| hatchstyle | int | Uno dei valori `HatchStyle`([.getHatchStyle](../../null/\#getHatchStyle)) che rappresenta il modello disegnato da questo [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush). |
| foreColor | [Color](../../com.aspose.drawing/color) | La struttura [Color](../../com.aspose.drawing/color) che rappresenta il colore delle linee disegnate da questo [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush). |
| backColor | [Color](../../com.aspose.drawing/color) | La struttura [Color](../../com.aspose.drawing/color) che rappresenta il colore degli spazi tra le linee disegnate da questo [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush). |

### getHatchStyle() {#getHatchStyle--}
```
public int getHatchStyle()
```


Restituisce lo stile a trama di questo oggetto [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush).

**Returns:**
int - lo stile a trama di questo oggetto [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush).
### getForegroundColor() {#getForegroundColor--}
```
public Color getForegroundColor()
```


Restituisce il colore delle linee a trama disegnate da questo oggetto [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush).

**Returns:**
[Color](../../com.aspose.drawing/color) - the color of hatch lines drawn by this [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) object.
### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Restituisce il colore degli spazi tra le linee a trama disegnate da questo oggetto [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush).

**Returns:**
[Color](../../com.aspose.drawing/color) - the color of spaces between the hatch lines drawn by this [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) object.
### deepClone() {#deepClone--}
```
public Object deepClone()
```


Crea una copia esatta di questo oggetto [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush).

**Returns:**
java.lang.Object - Il [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) che questo metodo crea, convertito in un oggetto.
