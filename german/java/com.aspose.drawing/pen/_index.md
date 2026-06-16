---
title: Stift
second_title: Aspose.Drawing für Java API-Referenz
description: Definiert ein Objekt, das zum Zeichnen von Linien und Kurven verwendet wird.
type: docs
weight: 34
url: /de/java/com.aspose.drawing/pen/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public class Pen implements System.IDisposable
```

Definiert ein Objekt, das zum Zeichnen von Linien und Kurven verwendet wird.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Pen(Color color)](#Pen-com.aspose.drawing.Color-) | Initialisiert eine neue Instanz der [Pen](../../com.aspose.drawing/pen)-Klasse mit der angegebenen `Color`([.getColor](../../null/\#getColor)/[.setColor(Color)](../../null/\#setColor-Color-)). |
| [Pen(Brush brush, float width)](#Pen-com.aspose.drawing.Brush-float-) | Initialisiert eine neue Instanz der Pen‑Klasse mit dem angegebenen Brush und Width. |
| [Pen(Brush brush)](#Pen-com.aspose.drawing.Brush-) | Initialisiert eine neue Instanz der [Pen](../../com.aspose.drawing/pen)-Klasse mit dem angegebenen `Brush`([.getBrush](../../null/\#getBrush)/[.setBrush(Brush)](../../null/\#setBrush-Brush-)). |
| [Pen(Color color, float width)](#Pen-com.aspose.drawing.Color-float-) | Initialisiert eine neue Instanz der Pen‑Klasse mit den angegebenen Color‑ und Width‑Eigenschaften. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getColor()](#getColor--) | Liest oder setzt die Farbe dieses [Pen](../../com.aspose.drawing/pen). |
| [setColor(Color value)](#setColor-com.aspose.drawing.Color-) | Liest oder setzt die Farbe dieses [Pen](../../com.aspose.drawing/pen). |
| [getBrush()](#getBrush--) | Liest oder setzt den Brush, der die Attribute dieses [Pen](../../com.aspose.drawing/pen) bestimmt. |
| [setBrush(Brush value)](#setBrush-com.aspose.drawing.Brush-) | Liest oder setzt den Brush, der die Attribute dieses [Pen](../../com.aspose.drawing/pen) bestimmt. |
| [getCompoundArray()](#getCompoundArray--) | Liest oder setzt ein Array von Werten, das einen zusammengesetzten Stift spezifiziert. |
| [setCompoundArray(float[] value)](#setCompoundArray-float---) | Liest oder setzt ein Array von Werten, das einen zusammengesetzten Stift spezifiziert. |
| [getWidth()](#getWidth--) | Liest oder setzt die Breite dieses Pen, in Einheiten des zum Zeichnen verwendeten Graphics‑Objekts. |
| [setWidth(float value)](#setWidth-float-) | Liest oder setzt die Breite dieses Pen, in Einheiten des zum Zeichnen verwendeten Graphics‑Objekts. |
| [getStartCap()](#getStartCap--) | Liest oder setzt den Cap‑Stil, der am Anfang von mit diesem Pen gezeichneten Linien verwendet wird. |
| [setStartCap(int value)](#setStartCap-int-) | Liest oder setzt den Cap‑Stil, der am Anfang von mit diesem Pen gezeichneten Linien verwendet wird. |
| [getEndCap()](#getEndCap--) | Liest oder setzt den Cap‑Stil, der am Ende von mit diesem Pen gezeichneten Linien verwendet wird. |
| [setEndCap(int value)](#setEndCap-int-) | Liest oder setzt den Cap‑Stil, der am Ende von mit diesem Pen gezeichneten Linien verwendet wird. |
| [getLineJoin()](#getLineJoin--) | Liest oder setzt den Join‑Stil für die Enden von zwei aufeinanderfolgenden Linien, die mit diesem Pen gezeichnet werden. |
| [setLineJoin(int value)](#setLineJoin-int-) | Liest oder setzt den Join‑Stil für die Enden von zwei aufeinanderfolgenden Linien, die mit diesem Pen gezeichnet werden. |
| [getMiterLimit()](#getMiterLimit--) | Liest oder setzt die Grenze der Dicke der Verbindung an einer Gehrungsecke. |
| [setMiterLimit(float value)](#setMiterLimit-float-) | Liest oder setzt die Grenze der Dicke der Verbindung an einer Gehrungsecke. |
| [getAlignment()](#getAlignment--) | Liest oder setzt die Ausrichtung für diesen [Pen](../../com.aspose.drawing/pen). |
| [setAlignment(int value)](#setAlignment-int-) | Liest oder setzt die Ausrichtung für diesen [Pen](../../com.aspose.drawing/pen). |
| [getTransform()](#getTransform--) | Liest oder setzt eine Kopie der geometrischen Transformation für diesen [Pen](../../com.aspose.drawing/pen). |
| [setTransform(Matrix value)](#setTransform-com.aspose.drawing.drawing2d.Matrix-) | Liest oder setzt eine Kopie der geometrischen Transformation für diesen [Pen](../../com.aspose.drawing/pen). |
| [getCustomStartCap()](#getCustomStartCap--) | Liest oder setzt einen benutzerdefinierten Cap, der am Anfang von mit diesem [Pen](../../com.aspose.drawing/pen) gezeichneten Linien verwendet wird. |
| [setCustomStartCap(CustomLineCap value)](#setCustomStartCap-com.aspose.drawing.drawing2d.CustomLineCap-) | Liest oder setzt einen benutzerdefinierten Cap, der am Anfang von mit diesem [Pen](../../com.aspose.drawing/pen) gezeichneten Linien verwendet wird. |
| [getCustomEndCap()](#getCustomEndCap--) | Liest oder setzt einen benutzerdefinierten Cap, der am Ende von mit diesem [Pen](../../com.aspose.drawing/pen) gezeichneten Linien verwendet wird. |
| [setCustomEndCap(CustomLineCap value)](#setCustomEndCap-com.aspose.drawing.drawing2d.CustomLineCap-) | Liest oder setzt einen benutzerdefinierten Cap, der am Ende von mit diesem [Pen](../../com.aspose.drawing/pen) gezeichneten Linien verwendet wird. |
| [getDashCap()](#getDashCap--) | Liest oder setzt den Cap‑Stil, der am Ende der Striche verwendet wird, aus denen mit diesem [Pen](../../com.aspose.drawing/pen) gezeichnete gestrichelte Linien bestehen. |
| [setDashCap(int value)](#setDashCap-int-) | Liest oder setzt den Cap‑Stil, der am Ende der Striche verwendet wird, aus denen mit diesem [Pen](../../com.aspose.drawing/pen) gezeichnete gestrichelte Linien bestehen. |
| [getDashOffset()](#getDashOffset--) | Liest oder setzt den Abstand vom Beginn einer Linie bis zum Anfang eines Strichmusters. |
| [setDashOffset(float value)](#setDashOffset-float-) | Liest oder setzt den Abstand vom Beginn einer Linie bis zum Anfang eines Strichmusters. |
| [getDashPattern()](#getDashPattern--) | Liest oder setzt ein Array benutzerdefinierter Striche und Lücken. |
| [setDashPattern(float[] value)](#setDashPattern-float---) | Liest oder setzt ein Array benutzerdefinierter Striche und Lücken. |
| [getDashStyle()](#getDashStyle--) | Liest oder setzt den Stil, der für mit diesem [Pen](../../com.aspose.drawing/pen) gezeichnete gestrichelte Linien verwendet wird. |
| [setDashStyle(int value)](#setDashStyle-int-) | Liest oder setzt den Stil, der für mit diesem [Pen](../../com.aspose.drawing/pen) gezeichnete gestrichelte Linien verwendet wird. |
| [getPenType()](#getPenType--) | Liest den Stil der mit diesem Pen gezeichneten Linien. |
| [dispose()](#dispose--) | Gibt alle von diesem Pen verwendeten Ressourcen frei. |
| [deepClone()](#deepClone--) | Erstellt eine exakte Kopie dieses [Pen](../../com.aspose.drawing/pen). |
| [setLineCap(int startCap, int endCap, int dashCap)](#setLineCap-int-int-int-) | Setzt die Werte, die den Stil der Endkappe bestimmen, die zum Abschluss von Linien verwendet wird, die von diesem [Pen](../../com.aspose.drawing/pen) gezeichnet werden. |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | Skaliert die lokale geometrische Transformation um die angegebenen Faktoren. |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | Skaliert die lokale geometrische Transformation um die angegebenen Faktoren in der angegebenen Reihenfolge. |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | Verschiebt die lokale geometrische Transformation um die angegebenen Dimensionen. |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | Verschiebt die lokale geometrische Transformation um die angegebenen Dimensionen in der angegebenen Reihenfolge. |
| [rotateTransform(float angle)](#rotateTransform-float-) | Dreht die lokale geometrische Transformation um den angegebenen Winkel. |
| [rotateTransform(float angle, int order)](#rotateTransform-float-int-) | Dreht die lokale geometrische Transformation um den angegebenen Winkel in der angegebenen Reihenfolge. |
| [resetTransform()](#resetTransform--) | Setzt die geometrische Transformationsmatrix für diesen [Pen](../../com.aspose.drawing/pen) auf die Identität zurück. |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-) | Multipliziert die Transformationsmatrix für diesen [Pen](../../com.aspose.drawing/pen) mit der angegebenen [Matrix](../../com.aspose.drawing.drawing2d/matrix). |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-int-) | Multipliziert die Transformationsmatrix für diesen [Pen](../../com.aspose.drawing/pen) mit der angegebenen [Matrix](../../com.aspose.drawing.drawing2d/matrix) in der angegebenen Reihenfolge. |
### Pen(Color color) {#Pen-com.aspose.drawing.Color-}
```
public Pen(Color color)
```


Initialisiert eine neue Instanz der [Pen](../../com.aspose.drawing/pen)-Klasse mit der angegebenen `Color`([.getColor](../../null/\#getColor)/[.setColor(Color)](../../null/\#setColor-Color-)).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| color | [Color](../../com.aspose.drawing/color) | Ein `Color`([.getColor](../../null/\#getColor)/[.setColor(Color)](../../null/\#setColor-Color-)), das die Fülleigenschaften dieses [Pen](../../com.aspose.drawing/pen) bestimmt. |

### Pen(Brush brush, float width) {#Pen-com.aspose.drawing.Brush-float-}
```
public Pen(Brush brush, float width)
```


Initialisiert eine neue Instanz der Pen‑Klasse mit dem angegebenen Brush und Width.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.drawing/brush) | Ein Brush, der die Eigenschaften dieses Pen bestimmt. |
| Breite | float | Die Breite des neuen Pen. |

### Pen(Brush brush) {#Pen-com.aspose.drawing.Brush-}
```
public Pen(Brush brush)
```


Initialisiert eine neue Instanz der [Pen](../../com.aspose.drawing/pen)-Klasse mit dem angegebenen `Brush`([.getBrush](../../null/\#getBrush)/[.setBrush(Brush)](../../null/\#setBrush-Brush-)).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.drawing/brush) | Ein `Brush`([.getBrush](../../null/\#getBrush)/[.setBrush(Brush)](../../null/\#setBrush-Brush-)), das die Fülleigenschaften dieses [Pen](../../com.aspose.drawing/pen) bestimmt. |

### Pen(Color color, float width) {#Pen-com.aspose.drawing.Color-float-}
```
public Pen(Color color, float width)
```


Initialisiert eine neue Instanz der Pen‑Klasse mit den angegebenen Color‑ und Width‑Eigenschaften.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| color | [Color](../../com.aspose.drawing/color) | Eine Color-Struktur, die die Farbe dieses Pen angibt. |
| Breite | float | Ein Wert, der die Breite dieses Pen angibt. |

### getColor() {#getColor--}
```
public final Color getColor()
```


Liest oder setzt die Farbe dieses [Pen](../../com.aspose.drawing/pen).

Wert: Eine `Color`([.getColor](../../null/\#getColor)/[.setColor(Color)](../../null/\#setColor-Color-))-Struktur, die die Farbe dieses [Pen](../../com.aspose.drawing/pen) darstellt.

**Returns:**
[Color](../../com.aspose.drawing/color)
### setColor(Color value) {#setColor-com.aspose.drawing.Color-}
```
public final void setColor(Color value)
```


Liest oder setzt die Farbe dieses [Pen](../../com.aspose.drawing/pen).

Wert: Eine `Color`([.getColor](../../null/\#getColor)/[.setColor(Color)](../../null/\#setColor-Color-))-Struktur, die die Farbe dieses [Pen](../../com.aspose.drawing/pen) darstellt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Color](../../com.aspose.drawing/color) |  |

### getBrush() {#getBrush--}
```
public final Brush getBrush()
```


Liest oder setzt den Brush, der die Attribute dieses [Pen](../../com.aspose.drawing/pen) bestimmt.

**Returns:**
[Brush](../../com.aspose.drawing/brush)
### setBrush(Brush value) {#setBrush-com.aspose.drawing.Brush-}
```
public final void setBrush(Brush value)
```


Liest oder setzt den Brush, der die Attribute dieses [Pen](../../com.aspose.drawing/pen) bestimmt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Brush](../../com.aspose.drawing/brush) |  |

### getCompoundArray() {#getCompoundArray--}
```
public final float[] getCompoundArray()
```


Liest oder setzt ein Array von Werten, das einen zusammengesetzten Pen angibt. Ein zusammengesetzter Pen zeichnet eine zusammengesetzte Linie, die aus parallelen Linien und Zwischenräumen besteht.

**Returns:**
float[] - Ein Array von reellen Zahlen, das das zusammengesetzte Array angibt. Die Elemente im Array müssen in aufsteigender Reihenfolge sein, nicht kleiner als 0 und nicht größer als 1.
### setCompoundArray(float[] value) {#setCompoundArray-float---}
```
public final void setCompoundArray(float[] value)
```


Liest oder setzt ein Array von Werten, das einen zusammengesetzten Pen angibt. Ein zusammengesetzter Pen zeichnet eine zusammengesetzte Linie, die aus parallelen Linien und Zwischenräumen besteht.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float[] |  |

### getWidth() {#getWidth--}
```
public final float getWidth()
```


Liest oder setzt die Breite dieses Pen, in Einheiten des zum Zeichnen verwendeten Graphics‑Objekts.

**Returns:**
float
### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```


Liest oder setzt die Breite dieses Pen, in Einheiten des zum Zeichnen verwendeten Graphics‑Objekts.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |

### getStartCap() {#getStartCap--}
```
public final int getStartCap()
```


Liest oder setzt den Cap‑Stil, der am Anfang von mit diesem Pen gezeichneten Linien verwendet wird.

**Returns:**
int
### setStartCap(int value) {#setStartCap-int-}
```
public final void setStartCap(int value)
```


Liest oder setzt den Cap‑Stil, der am Anfang von mit diesem Pen gezeichneten Linien verwendet wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getEndCap() {#getEndCap--}
```
public final int getEndCap()
```


Liest oder setzt den Cap‑Stil, der am Ende von mit diesem Pen gezeichneten Linien verwendet wird.

**Returns:**
int
### setEndCap(int value) {#setEndCap-int-}
```
public final void setEndCap(int value)
```


Liest oder setzt den Cap‑Stil, der am Ende von mit diesem Pen gezeichneten Linien verwendet wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getLineJoin() {#getLineJoin--}
```
public final int getLineJoin()
```


Liest oder setzt den Join‑Stil für die Enden von zwei aufeinanderfolgenden Linien, die mit diesem Pen gezeichnet werden.

--------------------

Derzeit funktioniert die Gehrungsschnittverbindung tatsächlich wie MiterClipped.

**Returns:**
int
### setLineJoin(int value) {#setLineJoin-int-}
```
public final void setLineJoin(int value)
```


Liest oder setzt den Join‑Stil für die Enden von zwei aufeinanderfolgenden Linien, die mit diesem Pen gezeichnet werden.

--------------------

Derzeit funktioniert die Gehrungsschnittverbindung tatsächlich wie MiterClipped.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getMiterLimit() {#getMiterLimit--}
```
public final float getMiterLimit()
```


Liest oder setzt die Grenze der Dicke der Verbindung an einer Gehrungsecke.

**Returns:**
float
### setMiterLimit(float value) {#setMiterLimit-float-}
```
public final void setMiterLimit(float value)
```


Liest oder setzt die Grenze der Dicke der Verbindung an einer Gehrungsecke.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |

### getAlignment() {#getAlignment--}
```
public final int getAlignment()
```


Liest oder setzt die Ausrichtung für diesen [Pen](../../com.aspose.drawing/pen).

**Returns:**
int - Ein [PenAlignment](../../com.aspose.drawing.drawing2d/penalignment), das die Ausrichtung für diesen [Pen](../../com.aspose.drawing/pen) darstellt.
### setAlignment(int value) {#setAlignment-int-}
```
public final void setAlignment(int value)
```


Liest oder setzt die Ausrichtung für diesen [Pen](../../com.aspose.drawing/pen).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getTransform() {#getTransform--}
```
public final Matrix getTransform()
```


Liest oder setzt eine Kopie der geometrischen Transformation für diesen [Pen](../../com.aspose.drawing/pen).

Wert: Eine Kopie der [Matrix](../../com.aspose.drawing.drawing2d/matrix), die die geometrische Transformation für diesen [Pen](../../com.aspose.drawing/pen) darstellt.

**Returns:**
[Matrix](../../com.aspose.drawing.drawing2d/matrix)
### setTransform(Matrix value) {#setTransform-com.aspose.drawing.drawing2d.Matrix-}
```
public final void setTransform(Matrix value)
```


Liest oder setzt eine Kopie der geometrischen Transformation für diesen [Pen](../../com.aspose.drawing/pen).

Wert: Eine Kopie der [Matrix](../../com.aspose.drawing.drawing2d/matrix), die die geometrische Transformation für diesen [Pen](../../com.aspose.drawing/pen) darstellt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.drawing.drawing2d/matrix) |  |

### getCustomStartCap() {#getCustomStartCap--}
```
public final CustomLineCap getCustomStartCap()
```


Liest oder setzt einen benutzerdefinierten Cap, der am Anfang von mit diesem [Pen](../../com.aspose.drawing/pen) gezeichneten Linien verwendet wird.

**Returns:**
[CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) - A [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) that represents the cap used at the beginning of lines drawn with this [Pen](../../com.aspose.drawing/pen).
### setCustomStartCap(CustomLineCap value) {#setCustomStartCap-com.aspose.drawing.drawing2d.CustomLineCap-}
```
public final void setCustomStartCap(CustomLineCap value)
```


Liest oder setzt einen benutzerdefinierten Cap, der am Anfang von mit diesem [Pen](../../com.aspose.drawing/pen) gezeichneten Linien verwendet wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) |  |

### getCustomEndCap() {#getCustomEndCap--}
```
public final CustomLineCap getCustomEndCap()
```


Liest oder setzt einen benutzerdefinierten Cap, der am Ende von mit diesem [Pen](../../com.aspose.drawing/pen) gezeichneten Linien verwendet wird.

**Returns:**
[CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) - A [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) that represents the cap used at the end of lines drawn with this [Pen](../../com.aspose.drawing/pen).
### setCustomEndCap(CustomLineCap value) {#setCustomEndCap-com.aspose.drawing.drawing2d.CustomLineCap-}
```
public final void setCustomEndCap(CustomLineCap value)
```


Liest oder setzt einen benutzerdefinierten Cap, der am Ende von mit diesem [Pen](../../com.aspose.drawing/pen) gezeichneten Linien verwendet wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) |  |

### getDashCap() {#getDashCap--}
```
public final int getDashCap()
```


Liest oder setzt den Cap‑Stil, der am Ende der Striche verwendet wird, aus denen mit diesem [Pen](../../com.aspose.drawing/pen) gezeichnete gestrichelte Linien bestehen.

**Returns:**
int - Einer der `DashCap`([.getDashCap](../../null/\#getDashCap)/[.setDashCap(int)](../../null/\#setDashCap-int-))-Werte, der den Kappenstil am Anfang und Ende der Striche darstellt, aus denen gestrichelte Linien bestehen, die mit diesem [Pen](../../com.aspose.drawing/pen) gezeichnet werden.
### setDashCap(int value) {#setDashCap-int-}
```
public final void setDashCap(int value)
```


Liest oder setzt den Cap‑Stil, der am Ende der Striche verwendet wird, aus denen mit diesem [Pen](../../com.aspose.drawing/pen) gezeichnete gestrichelte Linien bestehen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getDashOffset() {#getDashOffset--}
```
public final float getDashOffset()
```


Liest oder setzt den Abstand vom Beginn einer Linie bis zum Anfang eines Strichmusters.

**Returns:**
float - Der Abstand vom Start einer Linie bis zum Beginn eines Strichmusters.
### setDashOffset(float value) {#setDashOffset-float-}
```
public final void setDashOffset(float value)
```


Liest oder setzt den Abstand vom Beginn einer Linie bis zum Anfang eines Strichmusters.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |

### getDashPattern() {#getDashPattern--}
```
public final float[] getDashPattern()
```


Liest oder setzt ein Array benutzerdefinierter Striche und Lücken.

**Returns:**
float[] - Ein Array von reellen Zahlen, das die Längen abwechselnder Striche und Lücken in gestrichelten Linien angibt.
### setDashPattern(float[] value) {#setDashPattern-float---}
```
public final void setDashPattern(float[] value)
```


Liest oder setzt ein Array benutzerdefinierter Striche und Lücken.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float[] |  |

### getDashStyle() {#getDashStyle--}
```
public final int getDashStyle()
```


Liest oder setzt den Stil, der für mit diesem [Pen](../../com.aspose.drawing/pen) gezeichnete gestrichelte Linien verwendet wird.

**Returns:**
int - Ein `DashStyle`([.getDashStyle](../../null/\#getDashStyle)/[.setDashStyle(int)](../../null/\#setDashStyle-int-)) der den Stil für gestrichelte Linien darstellt, die mit diesem [Pen](../../com.aspose.drawing/pen) gezeichnet werden.
### setDashStyle(int value) {#setDashStyle-int-}
```
public final void setDashStyle(int value)
```


Liest oder setzt den Stil, der für mit diesem [Pen](../../com.aspose.drawing/pen) gezeichnete gestrichelte Linien verwendet wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getPenType() {#getPenType--}
```
public final int getPenType()
```


Liest den Stil der mit diesem Pen gezeichneten Linien.

Wert: Eine `PenType`([.getPenType](../../null/\#getPenType)) Aufzählung, die den Stil der mit diesem [Pen](../../com.aspose.drawing/pen) gezeichneten Linien festlegt.

**Returns:**
int
### dispose() {#dispose--}
```
public final void dispose()
```


Gibt alle von diesem Pen verwendeten Ressourcen frei.

--------------------

Diese Methode tut tatsächlich nichts. Sie dient nur der Kompatibilität mit der System.Drawing-API.

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Erstellt eine exakte Kopie dieses [Pen](../../com.aspose.drawing/pen).

**Returns:**
java.lang.Object - Ein Objekt, das in einen [Pen](../../com.aspose.drawing/pen) umgewandelt werden kann.
### setLineCap(int startCap, int endCap, int dashCap) {#setLineCap-int-int-int-}
```
public final void setLineCap(int startCap, int endCap, int dashCap)
```


Setzt die Werte, die den Stil der Endkappe bestimmen, die zum Abschluss von Linien verwendet wird, die von diesem [Pen](../../com.aspose.drawing/pen) gezeichnet werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| startCap | int | Ein [LineCap](../../com.aspose.drawing.drawing2d/linecap), der den Kap-Stil darstellt, der am Anfang von Linien verwendet wird, die mit diesem [Pen](../../com.aspose.drawing/pen) gezeichnet werden. |
| endCap | int | Ein [LineCap](../../com.aspose.drawing.drawing2d/linecap), der den Kap-Stil darstellt, der am Ende von Linien verwendet wird, die mit diesem [Pen](../../com.aspose.drawing/pen) gezeichnet werden. |
| dashCap | int | Ein [LineCap](../../com.aspose.drawing.drawing2d/linecap), der den Kap-Stil darstellt, der am Anfang oder Ende von gestrichelten Linien verwendet wird, die mit diesem [Pen](../../com.aspose.drawing/pen) gezeichnet werden. |

### scaleTransform(float sx, float sy) {#scaleTransform-float-float-}
```
public final void scaleTransform(float sx, float sy)
```


Skaliert die lokale geometrische Transformation um die angegebenen Faktoren. Diese Methode fügt die Skalierungsmatrix der Transformation voran.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sx | float | Der Faktor, um den die Transformation in x‑Richtung skaliert wird. |
| sy | float | Der Faktor, um den die Transformation in y‑Richtung skaliert wird. |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public final void scaleTransform(float sx, float sy, int order)
```


Skaliert die lokale geometrische Transformation um die angegebenen Faktoren in der angegebenen Reihenfolge.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sx | float | Der Faktor, um den die Transformation in x‑Richtung skaliert wird. |
| sy | float | Der Faktor, um den die Transformation in y‑Richtung skaliert wird. |
| order | int | Ein [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder), das angibt, ob die Skalierungsmatrix angehängt oder vorangestellt wird. |

### translateTransform(float dx, float dy) {#translateTransform-float-float-}
```
public final void translateTransform(float dx, float dy)
```


Verschiebt die lokale geometrische Transformation um die angegebenen Dimensionen. Diese Methode fügt die Translation der Transformation voran.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| dx | float | Der Wert der Verschiebung in x. |
| dy | float | Der Wert der Verschiebung in y. |

### translateTransform(float dx, float dy, int order) {#translateTransform-float-float-int-}
```
public final void translateTransform(float dx, float dy, int order)
```


Verschiebt die lokale geometrische Transformation um die angegebenen Dimensionen in der angegebenen Reihenfolge.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| dx | float | Der Wert der Verschiebung in x. |
| dy | float | Der Wert der Verschiebung in y. |
| Reihenfolge | int | Die Reihenfolge (voranstellen oder anhängen), in der die Verschiebung angewendet wird. |

### rotateTransform(float angle) {#rotateTransform-float-}
```
public final void rotateTransform(float angle)
```


Dreht die lokale geometrische Transformation um den angegebenen Winkel. Diese Methode fügt die Rotation der Transformation voran.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Winkel | float | Der Rotationswinkel. |

### rotateTransform(float angle, int order) {#rotateTransform-float-int-}
```
public final void rotateTransform(float angle, int order)
```


Dreht die lokale geometrische Transformation um den angegebenen Winkel in der angegebenen Reihenfolge.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Winkel | float | Der Rotationswinkel. |
| order | int | Ein [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder), das angibt, ob die Rotationsmatrix angehängt oder vorangestellt wird. |

### resetTransform() {#resetTransform--}
```
public final void resetTransform()
```


Setzt die geometrische Transformationsmatrix für diesen [Pen](../../com.aspose.drawing/pen) auf die Identität zurück.

### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-}
```
public final void multiplyTransform(Matrix matrix)
```


Multipliziert die Transformationsmatrix für diesen [Pen](../../com.aspose.drawing/pen) mit der angegebenen [Matrix](../../com.aspose.drawing.drawing2d/matrix).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | Das [Matrix](../../com.aspose.drawing.drawing2d/matrix)-Objekt, mit dem die Transformationsmatrix multipliziert wird. |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-int-}
```
public final void multiplyTransform(Matrix matrix, int order)
```


Multipliziert die Transformationsmatrix für diesen [Pen](../../com.aspose.drawing/pen) mit der angegebenen [Matrix](../../com.aspose.drawing.drawing2d/matrix) in der angegebenen Reihenfolge.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | Das java.awt.geom.AffineTransform, mit dem die Transformationsmatrix multipliziert wird. |
| Reihenfolge | int | Die Reihenfolge, in der die Multiplikationsoperation ausgeführt wird. |

