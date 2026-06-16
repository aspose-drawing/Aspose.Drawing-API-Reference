---
title: GraphicsPathIterator
second_title: Aspose.Drawing voor Java API-referentie
description: Biedt de mogelijkheid om door subpaden te itereren in een  en de typen vormen te testen die in elk subpad zijn opgenomen.
type: docs
weight: 24
url: /nl/java/com.aspose.drawing.drawing2d/graphicspathiterator/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public final class GraphicsPathIterator implements System.IDisposable
```

Biedt de mogelijkheid om door subpaden in een [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) te itereren en de typen vormen te testen die in elk subpad zijn opgenomen. Deze klasse kan niet worden geërfd.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [GraphicsPathIterator(GraphicsPath path)](#GraphicsPathIterator-com.aspose.drawing.drawing2d.GraphicsPath-) | Initialiseert een nieuw exemplaar van de klasse [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator). |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getCount()](#getCount--) | Haalt het aantal punten in het pad op. |
| [getSubpathCount()](#getSubpathCount--) | Haalt het aantal subpaden in het pad op. |
| [dispose()](#dispose--) | Voert door de toepassing gedefinieerde taken uit die verband houden met het vrijgeven, loslaten of opnieuw instellen van niet-beheerde bronnen. |
| [copyData(PointF[][] points, byte[][] types, int startIndex, int endIndex)](#copyData-com.aspose.drawing.PointF-----byte-----int-int-) | Kopieert de eigenschap GraphicsPath.PathPoints en de eigenschap GraphicsPath.PathTypes arrays van de geassocieerde [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) naar de twee opgegeven arrays. |
| [enumerate(PointF[][] points, byte[][] types)](#enumerate-com.aspose.drawing.PointF-----byte-----) | Kopieert de eigenschap GraphicsPath.PathPoints en de eigenschap GraphicsPath.PathTypes arrays van de geassocieerde [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) naar de twee opgegeven arrays. |
| [hasCurve()](#hasCurve--) | Geeft aan of het pad dat is geassocieerd met deze [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) een curve bevat. |
| [nextMarker(int[] startIndex, int[] endIndex)](#nextMarker-int---int---) | Verhoogt de [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) naar de volgende marker in het pad en retourneert de start- en stopindexen via de [out] parameters. |
| [nextMarker(GraphicsPath path)](#nextMarker-com.aspose.drawing.drawing2d.GraphicsPath-) | Dit [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) object heeft een [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) object dat eraan gekoppeld is. |
| [nextPathType(byte[] pathType, int[] startIndex, int[] endIndex)](#nextPathType-byte---int---int---) | Haalt de startindex en de eindindex op van de volgende groep gegevenspunten die allemaal hetzelfde type hebben. |
| [nextSubpath(int[] startIndex, int[] endIndex, boolean[] isClosed)](#nextSubpath-int---int---boolean---) | Verplaatst de [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) naar het volgende subpad in het pad. |
| [nextSubpath(GraphicsPath path, boolean[] isClosed)](#nextSubpath-com.aspose.drawing.drawing2d.GraphicsPath-boolean---) | Haalt de volgende figuur (subpad) op van het bijbehorende pad van deze [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator). |
| [rewind()](#rewind--) | Spoelt deze [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) terug naar het begin van het bijbehorende pad. |
### GraphicsPathIterator(GraphicsPath path) {#GraphicsPathIterator-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public GraphicsPathIterator(GraphicsPath path)
```


Initialiseert een nieuw exemplaar van de klasse [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | Het [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) object waarvoor deze hulpprogrammaklasse moet worden geïnitialiseerd. |

### getCount() {#getCount--}
```
public int getCount()
```


Haalt het aantal punten in het pad op.

**Returns:**
int - het aantal punten in het pad.
### getSubpathCount() {#getSubpathCount--}
```
public int getSubpathCount()
```


Haalt het aantal subpaden in het pad op.

**Returns:**
int - het aantal subpaden in het pad.
### dispose() {#dispose--}
```
public void dispose()
```


Voert door de toepassing gedefinieerde taken uit die verband houden met het vrijgeven, loslaten of opnieuw instellen van niet-beheerde bronnen.

### copyData(PointF[][] points, byte[][] types, int startIndex, int endIndex) {#copyData-com.aspose.drawing.PointF-----byte-----int-int-}
```
public int copyData(PointF[][] points, byte[][] types, int startIndex, int endIndex)
```


Kopieert de eigenschap GraphicsPath.PathPoints en de eigenschap GraphicsPath.PathTypes arrays van de geassocieerde [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) naar de twee opgegeven arrays.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.drawing/pointf) | Bij terugkeer bevat het een array van System.Drawing.PointF-structuren die de punten in het pad vertegenwoordigen. |
| typen | byte[][] | Bij terugkeer bevat het een array van bytes die de typen punten in het pad vertegenwoordigen. |
| startIndex | int | Specificeert de startindex van de arrays. |
| endIndex | int | Specificeert de eindindex van de arrays. |

**Returns:**
int - Het aantal gekopieerde punten.
### enumerate(PointF[][] points, byte[][] types) {#enumerate-com.aspose.drawing.PointF-----byte-----}
```
public int enumerate(PointF[][] points, byte[][] types)
```


Kopieert de eigenschap GraphicsPath.PathPoints en de eigenschap GraphicsPath.PathTypes arrays van de geassocieerde [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) naar de twee opgegeven arrays.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.drawing/pointf) | Bij terugkeer bevat het een array van System.Drawing.PointF-structuren die de punten in het pad vertegenwoordigen. |
| typen | byte[][] | Bij terugkeer bevat het een array van bytes die de typen punten in het pad vertegenwoordigen. |

**Returns:**
int - Het aantal gekopieerde punten.
### hasCurve() {#hasCurve--}
```
public boolean hasCurve()
```


Geeft aan of het pad dat is geassocieerd met deze [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) een curve bevat.

**Returns:**
boolean - Deze methode retourneert true als het huidige subpad een curve bevat; anders false.
### nextMarker(int[] startIndex, int[] endIndex) {#nextMarker-int---int---}
```
public int nextMarker(int[] startIndex, int[] endIndex)
```


Verhoogt de [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) naar de volgende marker in het pad en retourneert de start- en stopindexen via de [out] parameters.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| startIndex | int[] | [out] De door deze parameter geleverde integer-referentie ontvangt de index van het punt dat een subpad start. |
| endIndex | int[] | [out] De door deze parameter geleverde integer-referentie ontvangt de index van het punt dat het subpad beëindigt waar startIndex naar wijst. |

**Returns:**
int - Het aantal punten tussen deze markering en de volgende.
### nextMarker(GraphicsPath path) {#nextMarker-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public int nextMarker(GraphicsPath path)
```


Dit [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) object heeft een gekoppeld [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) object. Deze methode verhoogt het gekoppelde [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) naar de volgende markering in zijn pad en kopieert alle punten die zich tussen de huidige markering en de volgende markering (of het einde van het pad) bevinden naar een tweede [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) object dat als parameter wordt doorgegeven.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | Het [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) object waar de punten naartoe worden gekopieerd. |

**Returns:**
int - Het aantal punten tussen deze markering en de volgende.
### nextPathType(byte[] pathType, int[] startIndex, int[] endIndex) {#nextPathType-byte---int---int---}
```
public int nextPathType(byte[] pathType, int[] startIndex, int[] endIndex)
```


Haalt de startindex en de eindindex op van de volgende groep gegevenspunten die allemaal hetzelfde type hebben.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pathType | byte[] | [out] Ontvangt het punttype dat door alle punten in de groep wordt gedeeld. Mogelijke types kunnen worden opgehaald uit de [PathPointType](../../com.aspose.drawing.drawing2d/pathpointtype) enumeratie. |
| startIndex | int[] | [out] Ontvangt de startindex van de groep punten. |
| endIndex | int[] | [out] Ontvangt de eindindex van de groep punten. |

**Returns:**
int - Deze methode retourneert het aantal gegevenspunten in de groep. Als er geen groepen meer in het pad zijn, retourneert deze methode 0.
### nextSubpath(int[] startIndex, int[] endIndex, boolean[] isClosed) {#nextSubpath-int---int---boolean---}
```
public int nextSubpath(int[] startIndex, int[] endIndex, boolean[] isClosed)
```


Verplaatst de [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) naar het volgende subpad in het pad. De startindex en eindindex van het volgende subpad staan in de [out] parameters.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| startIndex | int[] | [out] Ontvangt de startindex van het volgende subpad. |
| endIndex | int[] | [out] Ontvangt de eindindex van het volgende subpad. |
| isClosed | boolean[] | [out] Geeft aan of het subpad gesloten is. |

**Returns:**
int - Het aantal gegevenspunten in de opgehaalde figuur (subpad). Als er geen figuren meer zijn om op te halen, wordt nul geretourneerd.
### nextSubpath(GraphicsPath path, boolean[] isClosed) {#nextSubpath-com.aspose.drawing.drawing2d.GraphicsPath-boolean---}
```
public int nextSubpath(GraphicsPath path, boolean[] isClosed)
```


Haalt de volgende figuur (subpad) op van het bijbehorende pad van deze [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | Een [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) waarvan de gegevenspunten worden ingesteld om overeen te komen met de gegevenspunten van de opgehaalde figuur (subpad) voor deze iterator. |
| isClosed | boolean[] | [out] Geeft aan of het huidige subpad gesloten is. Het is true als de figuur gesloten is, anders is het false. |

**Returns:**
int - Het aantal gegevenspunten in de opgehaalde figuur (subpad). Als er geen figuren meer zijn om op te halen, wordt nul geretourneerd.
### rewind() {#rewind--}
```
public void rewind()
```


Spoelt deze [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) terug naar het begin van het bijbehorende pad.

