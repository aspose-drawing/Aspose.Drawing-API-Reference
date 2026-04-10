---
title: CustomLineCap
second_title: Aspose.Drawing für Java API-Referenz
description: Kapselt einen benutzerdefinierten, vom Nutzer definierten Linienabschluss.
type: docs
weight: 17
url: /de/java/com.aspose.drawing.drawing2d/customlinecap/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public class CustomLineCap implements System.IDisposable
```

Kapselt einen benutzerdefinierten, vom Nutzer definierten Linienabschluss.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath)](#CustomLineCap-com.aspose.drawing.drawing2d.GraphicsPath-com.aspose.drawing.drawing2d.GraphicsPath-) | Initialisiert eine neue Instanz der Klasse [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) mit der angegebenen Kontur und Füllung. |
| [CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap)](#CustomLineCap-com.aspose.drawing.drawing2d.GraphicsPath-com.aspose.drawing.drawing2d.GraphicsPath-int-) | Initialisiert eine neue Instanz der Klasse [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) aus der angegebenen vorhandenen Aufzählung [LineCap](../../com.aspose.drawing.drawing2d/linecap) mit der angegebenen Kontur und Füllung. |
| [CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap, float baseInset)](#CustomLineCap-com.aspose.drawing.drawing2d.GraphicsPath-com.aspose.drawing.drawing2d.GraphicsPath-int-float-) | Initialisiert eine neue Instanz der Klasse [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) aus der angegebenen vorhandenen Aufzählung [LineCap](../../com.aspose.drawing.drawing2d/linecap) mit der angegebenen Kontur, Füllung und Einrückung. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getStrokeJoin()](#getStrokeJoin--) | Liest oder setzt die [LineJoin](../../com.aspose.drawing.drawing2d/linejoin)-Aufzählung, die bestimmt, wie Linien, die dieses [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap)-Objekt bilden, verbunden werden. |
| [setStrokeJoin(int value)](#setStrokeJoin-int-) | Liest oder setzt die [LineJoin](../../com.aspose.drawing.drawing2d/linejoin)-Aufzählung, die bestimmt, wie Linien, die dieses [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap)-Objekt bilden, verbunden werden. |
| [getBaseCap()](#getBaseCap--) | Liest oder setzt die [LineCap](../../com.aspose.drawing.drawing2d/linecap)-Aufzählung, auf der dieses [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) basiert. |
| [setBaseCap(int value)](#setBaseCap-int-) | Liest oder setzt die [LineCap](../../com.aspose.drawing.drawing2d/linecap)-Aufzählung, auf der dieses [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) basiert. |
| [getBaseInset()](#getBaseInset--) | Liest oder setzt den Abstand zwischen der Kappe und der Linie. |
| [setBaseInset(float value)](#setBaseInset-float-) | Liest oder setzt den Abstand zwischen der Kappe und der Linie. |
| [getWidthScale()](#getWidthScale--) | Liest oder setzt den Betrag, um den dieses [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap)-Klassenobjekt in Bezug auf die Breite des [Pen](../../com.aspose.drawing/pen)-Objekts skaliert wird. |
| [setWidthScale(float value)](#setWidthScale-float-) | Liest oder setzt den Betrag, um den dieses [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap)-Klassenobjekt in Bezug auf die Breite des [Pen](../../com.aspose.drawing/pen)-Objekts skaliert wird. |
| [dispose()](#dispose--) | Gibt alle von diesem [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap)-Objekt verwendeten Ressourcen frei. |
| [deepClone()](#deepClone--) | Erstellt eine exakte Kopie dieses [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap). |
| [setStrokeCaps(int startCap, int endCap)](#setStrokeCaps-int-int-) | Legt die Caps fest, die zum Starten und Beenden von Linien verwendet werden, aus denen dieses benutzerdefinierte Cap besteht. |
| [getStrokeCaps(int[] startCap, int[] endCap)](#getStrokeCaps-int---int---) | Liefert die Caps, die zum Starten und Beenden von Linien verwendet werden, aus denen dieses benutzerdefinierte Cap besteht. |
| [getFillPath()](#getFillPath--) |  |
| [getStrokePath()](#getStrokePath--) | Liefert das Objekt, das die Kontur des benutzerdefinierten Caps definiert. |
### CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath) {#CustomLineCap-com.aspose.drawing.drawing2d.GraphicsPath-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath)
```


Initialisiert eine neue Instanz der Klasse [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) mit der angegebenen Kontur und Füllung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fillPath | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | Ein [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath)-Objekt, das die Füllung für das benutzerdefinierte Cap definiert. |
| strokePath | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | Ein [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath)-Objekt, das die Kontur des benutzerdefinierten Caps definiert. |

### CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap) {#CustomLineCap-com.aspose.drawing.drawing2d.GraphicsPath-com.aspose.drawing.drawing2d.GraphicsPath-int-}
```
public CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap)
```


Initialisiert eine neue Instanz der Klasse [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) aus der angegebenen vorhandenen Aufzählung [LineCap](../../com.aspose.drawing.drawing2d/linecap) mit der angegebenen Kontur und Füllung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fillPath | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | Ein [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath)-Objekt, das die Füllung für das benutzerdefinierte Cap definiert. |
| strokePath | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | Ein [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath)-Objekt, das die Kontur des benutzerdefinierten Caps definiert. |
| baseCap | int | Das Linien‑Cap, aus dem das benutzerdefinierte Cap erstellt wird. |

### CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap, float baseInset) {#CustomLineCap-com.aspose.drawing.drawing2d.GraphicsPath-com.aspose.drawing.drawing2d.GraphicsPath-int-float-}
```
public CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap, float baseInset)
```


Initialisiert eine neue Instanz der Klasse [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) aus der angegebenen vorhandenen Aufzählung [LineCap](../../com.aspose.drawing.drawing2d/linecap) mit der angegebenen Kontur, Füllung und Einrückung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fillPath | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | Ein [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath)-Objekt, das die Füllung für das benutzerdefinierte Cap definiert. |
| strokePath | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | Ein [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath)-Objekt, das die Kontur des benutzerdefinierten Caps definiert. |
| baseCap | int | Das Linien‑Cap, aus dem das benutzerdefinierte Cap erstellt wird. |
| baseInset | float | Der Abstand zwischen dem Cap und der Linie. |

### getStrokeJoin() {#getStrokeJoin--}
```
public final int getStrokeJoin()
```


Liest oder setzt die [LineJoin](../../com.aspose.drawing.drawing2d/linejoin)-Aufzählung, die bestimmt, wie Linien, die dieses [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap)-Objekt bilden, verbunden werden.

**Returns:**
int
### setStrokeJoin(int value) {#setStrokeJoin-int-}
```
public final void setStrokeJoin(int value)
```


Liest oder setzt die [LineJoin](../../com.aspose.drawing.drawing2d/linejoin)-Aufzählung, die bestimmt, wie Linien, die dieses [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap)-Objekt bilden, verbunden werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getBaseCap() {#getBaseCap--}
```
public final int getBaseCap()
```


Liest oder setzt die [LineCap](../../com.aspose.drawing.drawing2d/linecap)-Aufzählung, auf der dieses [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) basiert.

**Returns:**
int
### setBaseCap(int value) {#setBaseCap-int-}
```
public final void setBaseCap(int value)
```


Liest oder setzt die [LineCap](../../com.aspose.drawing.drawing2d/linecap)-Aufzählung, auf der dieses [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) basiert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getBaseInset() {#getBaseInset--}
```
public final float getBaseInset()
```


Liest oder setzt den Abstand zwischen der Kappe und der Linie.

**Returns:**
float
### setBaseInset(float value) {#setBaseInset-float-}
```
public final void setBaseInset(float value)
```


Liest oder setzt den Abstand zwischen der Kappe und der Linie.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |

### getWidthScale() {#getWidthScale--}
```
public final float getWidthScale()
```


Liest oder setzt den Betrag, um den dieses [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap)-Klassenobjekt in Bezug auf die Breite des [Pen](../../com.aspose.drawing/pen)-Objekts skaliert wird.

**Returns:**
float
### setWidthScale(float value) {#setWidthScale-float-}
```
public final void setWidthScale(float value)
```


Liest oder setzt den Betrag, um den dieses [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap)-Klassenobjekt in Bezug auf die Breite des [Pen](../../com.aspose.drawing/pen)-Objekts skaliert wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |

### dispose() {#dispose--}
```
public final void dispose()
```


Gibt alle von diesem [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap)-Objekt verwendeten Ressourcen frei.

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Erstellt eine exakte Kopie dieses [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap).

**Returns:**
java.lang.Object – Das [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap), das diese Methode erstellt, als Objekt umgewandelt.
### setStrokeCaps(int startCap, int endCap) {#setStrokeCaps-int-int-}
```
public final void setStrokeCaps(int startCap, int endCap)
```


Legt die Caps fest, die zum Starten und Beenden von Linien verwendet werden, aus denen dieses benutzerdefinierte Cap besteht.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| startCap | int | Die [LineCap](../../com.aspose.drawing.drawing2d/linecap)-Aufzählung, die am Anfang einer Linie innerhalb dieses Caps verwendet wird. |
| endCap | int | Die [LineCap](../../com.aspose.drawing.drawing2d/linecap)-Aufzählung, die am Ende einer Linie innerhalb dieses Caps verwendet wird. |

### getStrokeCaps(int[] startCap, int[] endCap) {#getStrokeCaps-int---int---}
```
public final void getStrokeCaps(int[] startCap, int[] endCap)
```


Liefert die Caps, die zum Starten und Beenden von Linien verwendet werden, aus denen dieses benutzerdefinierte Cap besteht.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| startCap | int[] | Die [LineCap](../../com.aspose.drawing.drawing2d/linecap)-Aufzählung, die am Anfang einer Linie innerhalb dieses Caps verwendet wird. |
| endCap | int[] | Die [LineCap](../../com.aspose.drawing.drawing2d/linecap)-Aufzählung, die am Ende einer Linie innerhalb dieses Caps verwendet wird. |

### getFillPath() {#getFillPath--}
```
public GraphicsPath getFillPath()
```




**Returns:**
[GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath)
### getStrokePath() {#getStrokePath--}
```
public GraphicsPath getStrokePath()
```


Liefert das Objekt, das die Kontur des benutzerdefinierten Caps definiert.

**Returns:**
[GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) - The object that defines the outline of the custom cap.
