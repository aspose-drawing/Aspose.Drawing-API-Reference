---
title: GraphicsPathIterator
second_title: Aspose.Drawing für Java API-Referenz
description: Bietet die Möglichkeit, durch Unterpfade zu iterieren und die in jedem Unterpfad enthaltenen Formtypen zu testen.
type: docs
weight: 24
url: /de/java/com.aspose.drawing.drawing2d/graphicspathiterator/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public final class GraphicsPathIterator implements System.IDisposable
```

Bietet die Möglichkeit, durch Unterpfade in einem [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) zu iterieren und die Typen der in jedem Unterpfad enthaltenen Formen zu testen. Diese Klasse kann nicht abgeleitet werden.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [GraphicsPathIterator(GraphicsPath path)](#GraphicsPathIterator-com.aspose.drawing.drawing2d.GraphicsPath-) | Initialisiert eine neue Instanz der Klasse [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator). |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getCount()](#getCount--) | Gibt die Anzahl der Punkte im Pfad zurück. |
| [getSubpathCount()](#getSubpathCount--) | Gibt die Anzahl der Unterpfade im Pfad zurück. |
| [dispose()](#dispose--) | Führt anwendungsspezifische Aufgaben aus, die mit dem Freigeben, Freisetzen oder Zurücksetzen von nicht verwalteten Ressourcen verbunden sind. |
| [copyData(PointF[][] points, byte[][] types, int startIndex, int endIndex)](#copyData-com.aspose.drawing.PointF-----byte-----int-int-) | Kopiert die Eigenschaften GraphicsPath.PathPoints und GraphicsPath.PathTypes des zugehörigen [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) in die beiden angegebenen Arrays. |
| [enumerate(PointF[][] points, byte[][] types)](#enumerate-com.aspose.drawing.PointF-----byte-----) | Kopiert die Eigenschaften GraphicsPath.PathPoints und GraphicsPath.PathTypes des zugehörigen [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) in die beiden angegebenen Arrays. |
| [hasCurve()](#hasCurve--) | Gibt an, ob der mit diesem [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) verbundene Pfad eine Kurve enthält. |
| [nextMarker(int[] startIndex, int[] endIndex)](#nextMarker-int---int---) | Erhöht den [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) zum nächsten Marker im Pfad und gibt die Start‑ und Stopp‑Indizes über die [out]-Parameter zurück. |
| [nextMarker(GraphicsPath path)](#nextMarker-com.aspose.drawing.drawing2d.GraphicsPath-) | Dieses [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator)-Objekt hat ein zugehöriges [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath)-Objekt. |
| [nextPathType(byte[] pathType, int[] startIndex, int[] endIndex)](#nextPathType-byte---int---int---) | Gibt den Startindex und den Endindex der nächsten Gruppe von Datenpunkten zurück, die alle denselben Typ haben. |
| [nextSubpath(int[] startIndex, int[] endIndex, boolean[] isClosed)](#nextSubpath-int---int---boolean---) | Bewegt den [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) zum nächsten Unterpfad im Pfad. |
| [nextSubpath(GraphicsPath path, boolean[] isClosed)](#nextSubpath-com.aspose.drawing.drawing2d.GraphicsPath-boolean---) | Gibt die nächste Figur (Unterpfad) aus dem zugehörigen Pfad dieses [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) zurück. |
| [rewind()](#rewind--) | Spult diesen [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) zum Anfang seines zugehörigen Pfads zurück. |
### GraphicsPathIterator(GraphicsPath path) {#GraphicsPathIterator-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public GraphicsPathIterator(GraphicsPath path)
```


Initialisiert eine neue Instanz der Klasse [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | Das [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath)-Objekt, für das diese Hilfsklasse initialisiert werden soll. |

### getCount() {#getCount--}
```
public int getCount()
```


Gibt die Anzahl der Punkte im Pfad zurück.

**Returns:**
int - die Anzahl der Punkte im Pfad.
### getSubpathCount() {#getSubpathCount--}
```
public int getSubpathCount()
```


Gibt die Anzahl der Unterpfade im Pfad zurück.

**Returns:**
int - die Anzahl der Unterpfade im Pfad.
### dispose() {#dispose--}
```
public void dispose()
```


Führt anwendungsspezifische Aufgaben aus, die mit dem Freigeben, Freisetzen oder Zurücksetzen von nicht verwalteten Ressourcen verbunden sind.

### copyData(PointF[][] points, byte[][] types, int startIndex, int endIndex) {#copyData-com.aspose.drawing.PointF-----byte-----int-int-}
```
public int copyData(PointF[][] points, byte[][] types, int startIndex, int endIndex)
```


Kopiert die Eigenschaften GraphicsPath.PathPoints und GraphicsPath.PathTypes des zugehörigen [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) in die beiden angegebenen Arrays.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.drawing/pointf) | Bei Rückkehr enthält es ein Array von System.Drawing.PointF-Strukturen, das die Punkte im Pfad darstellt. |
| Typen | byte[][] | Bei Rückkehr enthält es ein Array von Bytes, das die Typen der Punkte im Pfad darstellt. |
| startIndex | int | Gibt den Startindex der Arrays an. |
| endIndex | int | Gibt den Endindex der Arrays an. |

**Returns:**
int - die Anzahl der kopierten Punkte.
### enumerate(PointF[][] points, byte[][] types) {#enumerate-com.aspose.drawing.PointF-----byte-----}
```
public int enumerate(PointF[][] points, byte[][] types)
```


Kopiert die Eigenschaften GraphicsPath.PathPoints und GraphicsPath.PathTypes des zugehörigen [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) in die beiden angegebenen Arrays.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.drawing/pointf) | Bei Rückkehr enthält es ein Array von System.Drawing.PointF-Strukturen, das die Punkte im Pfad darstellt. |
| Typen | byte[][] | Bei Rückkehr enthält es ein Array von Bytes, das die Typen der Punkte im Pfad darstellt. |

**Returns:**
int - die Anzahl der kopierten Punkte.
### hasCurve() {#hasCurve--}
```
public boolean hasCurve()
```


Gibt an, ob der mit diesem [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) verbundene Pfad eine Kurve enthält.

**Returns:**
boolean - Diese Methode gibt true zurück, wenn der aktuelle Unterpfad eine Kurve enthält; andernfalls false.
### nextMarker(int[] startIndex, int[] endIndex) {#nextMarker-int---int---}
```
public int nextMarker(int[] startIndex, int[] endIndex)
```


Erhöht den [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) zum nächsten Marker im Pfad und gibt die Start‑ und Stopp‑Indizes über die [out]-Parameter zurück.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| startIndex | int[] | [out] Die an diesen Parameter übergebene Integer-Referenz erhält den Index des Punktes, der einen Unterpfad startet. |
| endIndex | int[] | [out] Die an diesen Parameter übergebene Integer-Referenz erhält den Index des Punktes, der den Unterpfad beendet, auf den startIndex zeigt. |

**Returns:**
int - Die Anzahl der Punkte zwischen diesem Marker und dem nächsten.
### nextMarker(GraphicsPath path) {#nextMarker-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public int nextMarker(GraphicsPath path)
```


Dieses [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator)-Objekt hat ein zugehöriges [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath)-Objekt. Diese Methode erhöht das zugehörige [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) zum nächsten Marker in seinem Pfad und kopiert alle zwischen dem aktuellen Marker und dem nächsten Marker (oder dem Pfadende) enthaltenen Punkte in ein zweites [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath)-Objekt, das als Parameter übergeben wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | Das [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath)-Objekt, in das die Punkte kopiert werden. |

**Returns:**
int - Die Anzahl der Punkte zwischen diesem Marker und dem nächsten.
### nextPathType(byte[] pathType, int[] startIndex, int[] endIndex) {#nextPathType-byte---int---int---}
```
public int nextPathType(byte[] pathType, int[] startIndex, int[] endIndex)
```


Gibt den Startindex und den Endindex der nächsten Gruppe von Datenpunkten zurück, die alle denselben Typ haben.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pathType | byte[] | [out] Empfängt den Punkttyp, der von allen Punkten in der Gruppe gemeinsam verwendet wird. Mögliche Typen können aus der Aufzählung [PathPointType](../../com.aspose.drawing.drawing2d/pathpointtype) abgerufen werden. |
| startIndex | int[] | [out] Empfängt den Startindex der Punktgruppe. |
| endIndex | int[] | [out] Empfängt den Endindex der Punktgruppe. |

**Returns:**
int - Diese Methode gibt die Anzahl der Datenpunkte in der Gruppe zurück. Wenn es keine weiteren Gruppen im Pfad gibt, gibt diese Methode 0 zurück.
### nextSubpath(int[] startIndex, int[] endIndex, boolean[] isClosed) {#nextSubpath-int---int---boolean---}
```
public int nextSubpath(int[] startIndex, int[] endIndex, boolean[] isClosed)
```


Bewegt den [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) zum nächsten Unterpfad im Pfad. Der Start- und Endindex des nächsten Unterpfads sind in den [out]-Parametern enthalten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| startIndex | int[] | [out] Empfängt den Startindex des nächsten Unterpfads. |
| endIndex | int[] | [out] Empfängt den Endindex des nächsten Unterpfads. |
| isClosed | boolean[] | [out] Gibt an, ob der Unterpfad geschlossen ist. |

**Returns:**
int - Die Anzahl der Datenpunkte in der abgerufenen Figur (Unterpfad). Wenn keine weiteren Figuren mehr abgerufen werden können, wird 0 zurückgegeben.
### nextSubpath(GraphicsPath path, boolean[] isClosed) {#nextSubpath-com.aspose.drawing.drawing2d.GraphicsPath-boolean---}
```
public int nextSubpath(GraphicsPath path, boolean[] isClosed)
```


Gibt die nächste Figur (Unterpfad) aus dem zugehörigen Pfad dieses [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) zurück.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | Ein [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath), dessen Datenpunkte so gesetzt werden sollen, dass sie den Datenpunkten der abgerufenen Figur (Unterpfad) dieses Iterators entsprechen. |
| isClosed | boolean[] | [out] Gibt an, ob der aktuelle Unterpfad geschlossen ist. Sie ist true, wenn die Figur geschlossen ist, andernfalls false. |

**Returns:**
int - Die Anzahl der Datenpunkte in der abgerufenen Figur (Unterpfad). Wenn keine weiteren Figuren mehr abgerufen werden können, wird 0 zurückgegeben.
### rewind() {#rewind--}
```
public void rewind()
```


Spult diesen [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) zum Anfang seines zugehörigen Pfads zurück.

