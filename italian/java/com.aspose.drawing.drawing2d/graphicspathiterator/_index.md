---
title: GraphicsPathIterator
second_title: Riferimento API di Aspose.Drawing per Java
description: Fornisce la capacità di iterare attraverso i sottopercorsi in un GraphicsPath e testare i tipi di forme contenute in ciascun sottopercorso.
type: docs
weight: 24
url: /it/java/com.aspose.drawing.drawing2d/graphicspathiterator/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public final class GraphicsPathIterator implements System.IDisposable
```

Fornisce la possibilità di iterare attraverso i sottopercorsi in un [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) e testare i tipi di forme contenute in ciascun sottopercorso. Questa classe non può essere ereditata.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [GraphicsPathIterator(GraphicsPath path)](#GraphicsPathIterator-com.aspose.drawing.drawing2d.GraphicsPath-) | Inizializza una nuova istanza della classe [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator). |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getCount()](#getCount--) | Ottiene il numero di punti nel percorso. |
| [getSubpathCount()](#getSubpathCount--) | Ottiene il numero di sottopercorsi nel percorso. |
| [dispose()](#dispose--) | Esegue attività definite dall'applicazione associate al rilascio, alla liberazione o al reset delle risorse non gestite. |
| [copyData(PointF[][] points, byte[][] types, int startIndex, int endIndex)](#copyData-com.aspose.drawing.PointF-----byte-----int-int-) | Copia gli array della proprietà GraphicsPath.PathPoints e della proprietà GraphicsPath.PathTypes del [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) associato nei due array specificati. |
| [enumerate(PointF[][] points, byte[][] types)](#enumerate-com.aspose.drawing.PointF-----byte-----) | Copia gli array della proprietà GraphicsPath.PathPoints e della proprietà GraphicsPath.PathTypes del [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) associato nei due array specificati. |
| [hasCurve()](#hasCurve--) | Indica se il percorso associato a questo [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) contiene una curva. |
| [nextMarker(int[] startIndex, int[] endIndex)](#nextMarker-int---int---) | Incrementa il [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) al marcatore successivo nel percorso e restituisce gli indici di inizio e fine tramite i parametri [out]. |
| [nextMarker(GraphicsPath path)](#nextMarker-com.aspose.drawing.drawing2d.GraphicsPath-) | Questo oggetto [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) ha un oggetto [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) associato. |
| [nextPathType(byte[] pathType, int[] startIndex, int[] endIndex)](#nextPathType-byte---int---int---) | Ottiene l'indice di partenza e l'indice di fine del prossimo gruppo di punti dati che hanno tutti lo stesso tipo. |
| [nextSubpath(int[] startIndex, int[] endIndex, boolean[] isClosed)](#nextSubpath-int---int---boolean---) | Sposta il [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) al prossimo sottopercorso nel percorso. |
| [nextSubpath(GraphicsPath path, boolean[] isClosed)](#nextSubpath-com.aspose.drawing.drawing2d.GraphicsPath-boolean---) | Ottiene la figura successiva (sottopercorso) dal percorso associato di questo [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator). |
| [rewind()](#rewind--) | Riporta indietro questo [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) all'inizio del suo percorso associato. |
### GraphicsPathIterator(GraphicsPath path) {#GraphicsPathIterator-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public GraphicsPathIterator(GraphicsPath path)
```


Inizializza una nuova istanza della classe [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | L'oggetto [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) per il quale questa classe di supporto deve essere inizializzata. |

### getCount() {#getCount--}
```
public int getCount()
```


Ottiene il numero di punti nel percorso.

**Returns:**
int - il numero di punti nel percorso.
### getSubpathCount() {#getSubpathCount--}
```
public int getSubpathCount()
```


Ottiene il numero di sottopercorsi nel percorso.

**Returns:**
int - il numero di sottopercorsi nel percorso.
### dispose() {#dispose--}
```
public void dispose()
```


Esegue attività definite dall'applicazione associate al rilascio, alla liberazione o al reset delle risorse non gestite.

### copyData(PointF[][] points, byte[][] types, int startIndex, int endIndex) {#copyData-com.aspose.drawing.PointF-----byte-----int-int-}
```
public int copyData(PointF[][] points, byte[][] types, int startIndex, int endIndex)
```


Copia gli array della proprietà GraphicsPath.PathPoints e della proprietà GraphicsPath.PathTypes del [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) associato nei due array specificati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.drawing/pointf) | Al ritorno, contiene un array di strutture System.Drawing.PointF che rappresentano i punti nel percorso. |
| tipi | byte[][] | Al ritorno, contiene un array di byte che rappresenta i tipi di punti nel percorso. |
| startIndex | int | Specifica l'indice di partenza degli array. |
| endIndex | int | Specifica l'indice di fine degli array. |

**Returns:**
int - Il numero di punti copiati.
### enumerate(PointF[][] points, byte[][] types) {#enumerate-com.aspose.drawing.PointF-----byte-----}
```
public int enumerate(PointF[][] points, byte[][] types)
```


Copia gli array della proprietà GraphicsPath.PathPoints e della proprietà GraphicsPath.PathTypes del [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) associato nei due array specificati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.drawing/pointf) | Al ritorno, contiene un array di strutture System.Drawing.PointF che rappresentano i punti nel percorso. |
| tipi | byte[][] | Al ritorno, contiene un array di byte che rappresenta i tipi di punti nel percorso. |

**Returns:**
int - Il numero di punti copiati.
### hasCurve() {#hasCurve--}
```
public boolean hasCurve()
```


Indica se il percorso associato a questo [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) contiene una curva.

**Returns:**
boolean - Questo metodo restituisce true se il sotto-percorso corrente contiene una curva; altrimenti, false.
### nextMarker(int[] startIndex, int[] endIndex) {#nextMarker-int---int---}
```
public int nextMarker(int[] startIndex, int[] endIndex)
```


Incrementa il [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) al marcatore successivo nel percorso e restituisce gli indici di inizio e fine tramite i parametri [out].

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| startIndex | int[] | [out] Il riferimento intero fornito a questo parametro riceve l'indice del punto che avvia un sotto-percorso. |
| endIndex | int[] | [out] Il riferimento intero fornito a questo parametro riceve l'indice del punto che termina il sotto-percorso a cui punta startIndex. |

**Returns:**
int - Il numero di punti tra questo marcatore e il successivo.
### nextMarker(GraphicsPath path) {#nextMarker-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public int nextMarker(GraphicsPath path)
```


Questo oggetto [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) ha un oggetto [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) associato. Questo metodo incrementa il [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) associato al marcatore successivo nel suo percorso e copia tutti i punti contenuti tra il marcatore corrente e il marcatore successivo (o la fine del percorso) in un secondo oggetto [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) passato come parametro.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | L'oggetto [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) a cui verranno copiati i punti. |

**Returns:**
int - Il numero di punti tra questo marcatore e il successivo.
### nextPathType(byte[] pathType, int[] startIndex, int[] endIndex) {#nextPathType-byte---int---int---}
```
public int nextPathType(byte[] pathType, int[] startIndex, int[] endIndex)
```


Ottiene l'indice di partenza e l'indice di fine del prossimo gruppo di punti dati che hanno tutti lo stesso tipo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pathType | byte[] | [out] Riceve il tipo di punto condiviso da tutti i punti del gruppo. I possibili tipi possono essere recuperati dall'enumerazione [PathPointType](../../com.aspose.drawing.drawing2d/pathpointtype). |
| startIndex | int[] | [out] Riceve l'indice iniziale del gruppo di punti. |
| endIndex | int[] | [out] Riceve l'indice finale del gruppo di punti. |

**Returns:**
int - Questo metodo restituisce il numero di punti dati nel gruppo. Se non ci sono più gruppi nel percorso, questo metodo restituisce 0.
### nextSubpath(int[] startIndex, int[] endIndex, boolean[] isClosed) {#nextSubpath-int---int---boolean---}
```
public int nextSubpath(int[] startIndex, int[] endIndex, boolean[] isClosed)
```


Sposta il [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) al prossimo sotto-percorso nel percorso. L'indice di inizio e l'indice di fine del prossimo sotto-percorso sono contenuti nei parametri [out].

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| startIndex | int[] | [out] Riceve l'indice iniziale del prossimo sotto-percorso. |
| endIndex | int[] | [out] Riceve l'indice finale del prossimo sotto-percorso. |
| isClosed | boolean[] | [out] Indica se il sotto-percorso è chiuso. |

**Returns:**
int - Il numero di punti dati nella figura (sotto-percorso) recuperata. Se non ci sono più figure da recuperare, viene restituito zero.
### nextSubpath(GraphicsPath path, boolean[] isClosed) {#nextSubpath-com.aspose.drawing.drawing2d.GraphicsPath-boolean---}
```
public int nextSubpath(GraphicsPath path, boolean[] isClosed)
```


Ottiene la figura successiva (sottopercorso) dal percorso associato di questo [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | Un [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) il cui punti dati devono essere impostati per corrispondere ai punti dati della figura (sotto-percorso) recuperata per questo iteratore. |
| isClosed | boolean[] | [out] Indica se il sotto-percorso corrente è chiuso. È true se la figura è chiusa, altrimenti è false. |

**Returns:**
int - Il numero di punti dati nella figura (sotto-percorso) recuperata. Se non ci sono più figure da recuperare, viene restituito zero.
### rewind() {#rewind--}
```
public void rewind()
```


Riporta indietro questo [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) all'inizio del suo percorso associato.

