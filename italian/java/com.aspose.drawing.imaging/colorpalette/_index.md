---
title: ColorPalette
second_title: Riferimento API di Aspose.Drawing per Java
description: Definisce un array di colori che compongono una tavolozza di colori.
type: docs
weight: 16
url: /it/java/com.aspose.drawing.imaging/colorpalette/
---
**Inheritance:**
java.lang.Object
```
public final class ColorPalette
```

Definisce un array di colori che compongono una tavolozza di colori. I colori sono ARGB a 32 bit. Non ereditabile.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [ColorPalette(int count)](#ColorPalette-int-) | Inizializza una nuova istanza della classe `ColorPalette` e IsCompactPalette è false. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getEntries()](#getEntries--) | Restituisce un array di strutture `com.aspose.drawing.Color`. |
| [isCompactPalette()](#isCompactPalette--) | Ottiene o imposta un valore che indica se è usata una tavolozza compatta. |
| [getFlags()](#getFlags--) |  |
| [setFlags(int flags)](#setFlags-int-) |  |
| [setEntries(int i, Color color)](#setEntries-int-com.aspose.drawing.Color-) |  |
### ColorPalette(int count) {#ColorPalette-int-}
```
public ColorPalette(int count)
```


Inizializza una nuova istanza della classe `ColorPalette` e IsCompactPalette è false.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| count | int | Le voci della tavolozza di colori. |

### getEntries() {#getEntries--}
```
public Color[] getEntries()
```


Restituisce un array di strutture `com.aspose.drawing.Color`.

**Returns:**
com.aspose.drawing.Color[] - Le voci. L'array di strutture `com.aspose.drawing.Color` che compongono questo `Aspose.Imaging.ColorPalette`.
### isCompactPalette() {#isCompactPalette--}
```
public boolean isCompactPalette()
```


Ottiene o imposta un valore che indica se è usata una tavolozza compatta.

**Returns:**
boolean - `true` se è usata una tavolozza compatta; altrimenti, `false`.

Una tavolozza compatta significa che l'immagine conterrà solo le voci di tavolozza specificate, se possibile, o, in altre parole, l'immagine sarà più compatta e occuperà meno spazio; altrimenti ci saranno 2^BitsPerPixel voci e l'immagine riserverà più spazio per tutte le possibili voci di tavolozza. Impostare questo valore su true e modificare le voci della tavolozza può comportare una penalità di prestazioni poiché potrebbe verificarsi lo spostamento dei dati, quindi usalo con attenzione.
### getFlags() {#getFlags--}
```
public int getFlags()
```




**Returns:**
int
### setFlags(int flags) {#setFlags-int-}
```
public void setFlags(int flags)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| flags | int |  |

### setEntries(int i, Color color) {#setEntries-int-com.aspose.drawing.Color-}
```
public void setEntries(int i, Color color)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| i | int |  |
| color | [Color](../../com.aspose.drawing/color) |  |

