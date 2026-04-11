---
title: GraphicsPathIterator
second_title: Aspose.Drawing för Java API‑referens
description: Tillhandahåller möjligheten att iterera genom delvägar i en  och testa typerna av former som finns i varje delväg.
type: docs
weight: 24
url: /sv/java/com.aspose.drawing.drawing2d/graphicspathiterator/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public final class GraphicsPathIterator implements System.IDisposable
```

Tillhandahåller möjligheten att iterera genom delvägar i en [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) och testa typerna av former som finns i varje delväg. Denna klass kan inte ärvas.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [GraphicsPathIterator(GraphicsPath path)](#GraphicsPathIterator-com.aspose.drawing.drawing2d.GraphicsPath-) | Initierar en ny instans av klassen [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator). |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getCount()](#getCount--) | Hämtar antalet punkter i vägen. |
| [getSubpathCount()](#getSubpathCount--) | Hämtar antalet delvägar i vägen. |
| [dispose()](#dispose--) | Utför applikationsdefinierade uppgifter som är relaterade till att frigöra, släppa eller återställa ohanterade resurser. |
| [copyData(PointF[][] points, byte[][] types, int startIndex, int endIndex)](#copyData-com.aspose.drawing.PointF-----byte-----int-int-) | Kopierar egenskapsarrayerna GraphicsPath.PathPoints och GraphicsPath.PathTypes för den associerade [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) till de två angivna arrayerna. |
| [enumerate(PointF[][] points, byte[][] types)](#enumerate-com.aspose.drawing.PointF-----byte-----) | Kopierar egenskapsarrayerna GraphicsPath.PathPoints och GraphicsPath.PathTypes för den associerade [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) till de två angivna arrayerna. |
| [hasCurve()](#hasCurve--) | Anger om vägen som är associerad med denna [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) innehåller en kurva. |
| [nextMarker(int[] startIndex, int[] endIndex)](#nextMarker-int---int---) | Ökar [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) till nästa markör i vägen och returnerar start- och stoppindex via [out] parametrarna. |
| [nextMarker(GraphicsPath path)](#nextMarker-com.aspose.drawing.drawing2d.GraphicsPath-) | Detta [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator)-objekt har ett [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath)-objekt associerat med sig. |
| [nextPathType(byte[] pathType, int[] startIndex, int[] endIndex)](#nextPathType-byte---int---int---) | Hämtar startindex och slutindex för nästa grupp datapunkter som alla har samma typ. |
| [nextSubpath(int[] startIndex, int[] endIndex, boolean[] isClosed)](#nextSubpath-int---int---boolean---) | Flyttar [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) till nästa delväg i vägen. |
| [nextSubpath(GraphicsPath path, boolean[] isClosed)](#nextSubpath-com.aspose.drawing.drawing2d.GraphicsPath-boolean---) | Hämtar nästa figur (delväg) från den associerade vägen för denna [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator). |
| [rewind()](#rewind--) | Spolar tillbaka detta [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) till början av dess associerade väg. |
### GraphicsPathIterator(GraphicsPath path) {#GraphicsPathIterator-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public GraphicsPathIterator(GraphicsPath path)
```


Initierar en ny instans av klassen [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath)-objektet som denna hjälparklass ska initieras för. |

### getCount() {#getCount--}
```
public int getCount()
```


Hämtar antalet punkter i vägen.

**Returns:**
int - antalet punkter i vägen.
### getSubpathCount() {#getSubpathCount--}
```
public int getSubpathCount()
```


Hämtar antalet delvägar i vägen.

**Returns:**
int - antalet delvägar i vägen.
### dispose() {#dispose--}
```
public void dispose()
```


Utför applikationsdefinierade uppgifter som är relaterade till att frigöra, släppa eller återställa ohanterade resurser.

### copyData(PointF[][] points, byte[][] types, int startIndex, int endIndex) {#copyData-com.aspose.drawing.PointF-----byte-----int-int-}
```
public int copyData(PointF[][] points, byte[][] types, int startIndex, int endIndex)
```


Kopierar egenskapsarrayerna GraphicsPath.PathPoints och GraphicsPath.PathTypes för den associerade [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) till de två angivna arrayerna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.drawing/pointf) | Vid återgång innehåller den en array av System.Drawing.PointF-strukturer som representerar punkterna i vägen. |
| typer | byte[][] | Vid återgång innehåller den en array av byte-värden som representerar typerna av punkter i vägen. |
| startIndex | int | Anger startindex för arrayerna. |
| endIndex | int | Anger slutindex för arrayerna. |

**Returns:**
int - antalet kopierade punkter.
### enumerate(PointF[][] points, byte[][] types) {#enumerate-com.aspose.drawing.PointF-----byte-----}
```
public int enumerate(PointF[][] points, byte[][] types)
```


Kopierar egenskapsarrayerna GraphicsPath.PathPoints och GraphicsPath.PathTypes för den associerade [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) till de två angivna arrayerna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.drawing/pointf) | Vid återgång innehåller den en array av System.Drawing.PointF-strukturer som representerar punkterna i vägen. |
| typer | byte[][] | Vid återgång innehåller den en array av byte-värden som representerar typerna av punkter i vägen. |

**Returns:**
int - antalet kopierade punkter.
### hasCurve() {#hasCurve--}
```
public boolean hasCurve()
```


Anger om vägen som är associerad med denna [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) innehåller en kurva.

**Returns:**
boolean - Denna metod returnerar true om den aktuella delvägen innehåller en kurva; annars false.
### nextMarker(int[] startIndex, int[] endIndex) {#nextMarker-int---int---}
```
public int nextMarker(int[] startIndex, int[] endIndex)
```


Ökar [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) till nästa markör i vägen och returnerar start- och stoppindex via [out] parametrarna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| startIndex | int[] | [out] Det heltalsreferens som tillhandahålls till denna parameter får indexet för den punkt som startar en delväg. |
| endIndex | int[] | [out] Det heltalsreferens som tillhandahålls till denna parameter får indexet för den punkt som avslutar den delväg som startIndex pekar på. |

**Returns:**
int - Antalet punkter mellan denna markör och nästa.
### nextMarker(GraphicsPath path) {#nextMarker-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public int nextMarker(GraphicsPath path)
```


Detta [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator)-objekt har ett [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath)-objekt associerat med sig. Denna metod ökar det associerade [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) till nästa markör i dess bana och kopierar alla punkter som finns mellan den aktuella markören och nästa markör (eller slutet av banan) till ett andra [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath)-objekt som skickas in som parameter.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | Det [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath)-objektet som punkterna kommer att kopieras till. |

**Returns:**
int - Antalet punkter mellan denna markör och nästa.
### nextPathType(byte[] pathType, int[] startIndex, int[] endIndex) {#nextPathType-byte---int---int---}
```
public int nextPathType(byte[] pathType, int[] startIndex, int[] endIndex)
```


Hämtar startindex och slutindex för nästa grupp datapunkter som alla har samma typ.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pathType | byte[] | [out] Tar emot punkttypen som delas av alla punkter i gruppen. Möjliga typer kan hämtas från [PathPointType](../../com.aspose.drawing.drawing2d/pathpointtype)-enumerationen. |
| startIndex | int[] | [out] Tar emot startindexet för gruppen av punkter. |
| endIndex | int[] | [out] Tar emot slutindexet för gruppen av punkter. |

**Returns:**
int - Denna metod returnerar antalet datapunkter i gruppen. Om det inte finns fler grupper i banan returnerar metoden 0.
### nextSubpath(int[] startIndex, int[] endIndex, boolean[] isClosed) {#nextSubpath-int---int---boolean---}
```
public int nextSubpath(int[] startIndex, int[] endIndex, boolean[] isClosed)
```


Flyttar [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) till nästa delväg i banan. Startindexet och slutindexet för nästa delväg finns i [out]-parametrarna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| startIndex | int[] | [out] Tar emot startindexet för nästa delväg. |
| endIndex | int[] | [out] Tar emot slutindexet för nästa delväg. |
| isClosed | boolean[] | [out] Anger om delvägen är sluten. |

**Returns:**
int - Antalet datapunkter i den hämtade figuren (delväg). Om det inte finns fler figurer att hämta returneras noll.
### nextSubpath(GraphicsPath path, boolean[] isClosed) {#nextSubpath-com.aspose.drawing.drawing2d.GraphicsPath-boolean---}
```
public int nextSubpath(GraphicsPath path, boolean[] isClosed)
```


Hämtar nästa figur (delväg) från den associerade vägen för denna [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | Ett [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) som ska ha sina datapunkter satta för att matcha datapunkterna i den hämtade figuren (delväg) för denna iterator. |
| isClosed | boolean[] | [out] Anger om den aktuella delvägen är sluten. Den är true om figuren är sluten, annars false. |

**Returns:**
int - Antalet datapunkter i den hämtade figuren (delväg). Om det inte finns fler figurer att hämta returneras noll.
### rewind() {#rewind--}
```
public void rewind()
```


Spolar tillbaka detta [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) till början av dess associerade väg.

