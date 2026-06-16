---
title: ColorMatrix
second_title: Aspose.Drawing für Java API-Referenz
description: Definiert eine 5 × 5-Matrix, die die Koordinaten für den RGBA-Raum enthält.
type: docs
weight: 14
url: /de/java/com.aspose.drawing.imaging/colormatrix/
---
**Inheritance:**
java.lang.Object
```
public final class ColorMatrix
```

Definiert eine 5 × 5‑Matrix, die die Koordinaten für den RGBA‑Raum enthält. Mehrere Methoden der [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes) Klasse passen Bildfarben mithilfe einer Farbmatrix an. Diese Klasse kann nicht vererbt werden.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [ColorMatrix()](#ColorMatrix--) | Initialisiert eine neue Instanz der [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) Klasse. |
| [ColorMatrix(float[][] newColorMatrix)](#ColorMatrix-float-----) | Initialisiert eine neue Instanz der [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) Klasse unter Verwendung der Elemente der angegebenen Matrix `newColorMatrix`. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getMatrix00()](#getMatrix00--) | Liest das Element in Zeile 0 (null) und Spalte 0 dieser [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix00(float value)](#setMatrix00-float-) | Setzt das Element in Zeile 0 (null) und Spalte 0 dieser [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix01()](#getMatrix01--) | Liest das Element in Zeile 0 (null) und erster Spalte dieser [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix01(float value)](#setMatrix01-float-) | Setzt das Element in Zeile 0 (null) und erster Spalte dieser [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix02()](#getMatrix02--) | Liest das Element in Zeile 0 (null) und zweiter Spalte dieser [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix02(float value)](#setMatrix02-float-) | Setzt das Element in Zeile 0 (null) und zweiter Spalte dieser [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix03()](#getMatrix03--) | Liest das Element in Zeile 0 (null) und dritter Spalte dieser [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix03(float value)](#setMatrix03-float-) | Setzt das Element in der 0 (null) Zeile und der dritten Spalte dieses [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix04()](#getMatrix04--) | Liest das Element in der 0 (null) Zeile und der vierten Spalte dieses [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix04(float value)](#setMatrix04-float-) | Setzt das Element in der 0 (null) Zeile und der vierten Spalte dieses [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix10()](#getMatrix10--) | Liest das Element in der ersten Zeile und der 0 (null) Spalte dieses [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix10(float value)](#setMatrix10-float-) | Setzt das Element in der ersten Zeile und der 0 (null) Spalte dieses [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix11()](#getMatrix11--) | Liest das Element in der ersten Zeile und der ersten Spalte dieses [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix11(float value)](#setMatrix11-float-) | Setzt das Element in der ersten Zeile und der ersten Spalte dieses [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix12()](#getMatrix12--) | Liest das Element in der ersten Zeile und der zweiten Spalte dieses [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix12(float value)](#setMatrix12-float-) | Setzt das Element in der ersten Zeile und der zweiten Spalte dieses [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix13()](#getMatrix13--) | Liest das Element in der ersten Zeile und der dritten Spalte dieses [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix13(float value)](#setMatrix13-float-) | Setzt das Element in der ersten Zeile und der dritten Spalte dieses [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix14()](#getMatrix14--) | Liest das Element in der ersten Zeile und der vierten Spalte dieses [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix14(float value)](#setMatrix14-float-) | Setzt das Element in der ersten Zeile und der vierten Spalte dieses [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix20()](#getMatrix20--) | Liest das Element in der zweiten Zeile und der 0 (null) Spalte dieses [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix20(float value)](#setMatrix20-float-) | Setzt das Element in der zweiten Zeile und der 0 (null) Spalte dieses [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix21()](#getMatrix21--) | Liest das Element in der zweiten Zeile und der ersten Spalte dieses [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix21(float value)](#setMatrix21-float-) | Setzt das Element in der zweiten Zeile und der ersten Spalte dieses [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix22()](#getMatrix22--) | Liest das Element in der zweiten Zeile und der zweiten Spalte dieses [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix22(float value)](#setMatrix22-float-) | Setzt das Element in der zweiten Zeile und der zweiten Spalte dieses [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix23()](#getMatrix23--) | Liest das Element in der zweiten Zeile und der dritten Spalte dieses [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix23(float value)](#setMatrix23-float-) | Setzt das Element in der zweiten Zeile und der dritten Spalte dieses [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix24()](#getMatrix24--) | Liest das Element in der zweiten Zeile und der vierten Spalte dieses [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix24(float value)](#setMatrix24-float-) | Setzt das Element in der zweiten Zeile und der vierten Spalte dieses [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix30()](#getMatrix30--) | Liest das Element in der dritten Zeile und der 0 (null) Spalte dieses [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix30(float value)](#setMatrix30-float-) | Setzt das Element in der dritten Zeile und der 0 (null) Spalte dieses [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix31()](#getMatrix31--) | Ruft das Element in der dritten Zeile und ersten Spalte dieser [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) ab. |
| [setMatrix31(float value)](#setMatrix31-float-) | Setzt das Element in der dritten Zeile und ersten Spalte dieser [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix32()](#getMatrix32--) | Ruft das Element in der dritten Zeile und zweiten Spalte dieser [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) ab. |
| [setMatrix32(float value)](#setMatrix32-float-) | Setzt das Element in der dritten Zeile und zweiten Spalte dieser [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix33()](#getMatrix33--) | Ruft das Element in der dritten Zeile und dritten Spalte dieser [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) ab. |
| [setMatrix33(float value)](#setMatrix33-float-) | Setzt das Element in der dritten Zeile und dritten Spalte dieser [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix34()](#getMatrix34--) | Ruft das Element in der dritten Zeile und vierten Spalte dieser [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) ab. |
| [setMatrix34(float value)](#setMatrix34-float-) | Setzt das Element in der dritten Zeile und vierten Spalte dieser [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix40()](#getMatrix40--) | Ruft das Element in der vierten Zeile und Spalte 0 (null) dieser [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) ab. |
| [setMatrix40(float value)](#setMatrix40-float-) | Setzt das Element in der vierten Zeile und Spalte 0 (null) dieser [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix41()](#getMatrix41--) | Ruft das Element in der vierten Zeile und ersten Spalte dieser `.ColorMatrix` ab. |
| [setMatrix41(float value)](#setMatrix41-float-) | Setzt das Element in der vierten Zeile und ersten Spalte dieser `.ColorMatrix`. |
| [getMatrix42()](#getMatrix42--) | Ruft das Element in der vierten Zeile und zweiten Spalte dieser [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) ab. |
| [setMatrix42(float value)](#setMatrix42-float-) | Setzt das Element in der vierten Zeile und zweiten Spalte dieser [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix43()](#getMatrix43--) | Ruft das Element in der vierten Zeile und dritten Spalte dieser [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) ab. |
| [setMatrix43(float value)](#setMatrix43-float-) | Setzt das Element in der vierten Zeile und dritten Spalte dieser [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix44()](#getMatrix44--) | Ruft das Element in der vierten Zeile und vierten Spalte dieser [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) ab. |
| [setMatrix44(float value)](#setMatrix44-float-) | Setzt das Element in der vierten Zeile und vierten Spalte dieser [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [get_Item(int row, int column)](#get-Item-int-int-) | Ruft das Element in der angegebenen Zeile und Spalte der [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) ab. |
| [set_Item(int row, int column, float value)](#set-Item-int-int-float-) | Setzt das Element in der angegebenen Zeile und Spalte der [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
### ColorMatrix() {#ColorMatrix--}
```
public ColorMatrix()
```


Initialisiert eine neue Instanz der [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) Klasse.

### ColorMatrix(float[][] newColorMatrix) {#ColorMatrix-float-----}
```
public ColorMatrix(float[][] newColorMatrix)
```


Initialisiert eine neue Instanz der [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) Klasse unter Verwendung der Elemente der angegebenen Matrix `newColorMatrix`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newColorMatrix | float[][] | Die Werte der Elemente für die neue [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix00() {#getMatrix00--}
```
public float getMatrix00()
```


Liest das Element in Zeile 0 (null) und Spalte 0 dieser [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - das Element in Zeile 0 (null) und Spalte 0 dieser [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix00(float value) {#setMatrix00-float-}
```
public void setMatrix00(float value)
```


Setzt das Element in Zeile 0 (null) und Spalte 0 dieser [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float | das Element in Zeile 0 (null) und Spalte 0 dieser [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix01() {#getMatrix01--}
```
public float getMatrix01()
```


Liest das Element in Zeile 0 (null) und erster Spalte dieser [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - das Element in Zeile 0 (null) und erster Spalte dieser [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix01(float value) {#setMatrix01-float-}
```
public void setMatrix01(float value)
```


Setzt das Element in Zeile 0 (null) und erster Spalte dieser [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float | das Element in Zeile 0 (null) und erster Spalte dieser [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix02() {#getMatrix02--}
```
public float getMatrix02()
```


Liest das Element in Zeile 0 (null) und zweiter Spalte dieser [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - das Element in der 0 (null) Zeile und der zweiten Spalte dieser [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix02(float value) {#setMatrix02-float-}
```
public void setMatrix02(float value)
```


Setzt das Element in Zeile 0 (null) und zweiter Spalte dieser [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float | das Element in der 0 (null) Zeile und der zweiten Spalte dieser [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix03() {#getMatrix03--}
```
public float getMatrix03()
```


Liest das Element in Zeile 0 (null) und dritter Spalte dieser [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - das Element in der 0 (null) Zeile und der dritten Spalte dieser [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix03(float value) {#setMatrix03-float-}
```
public void setMatrix03(float value)
```


Setzt das Element in der 0 (null) Zeile und der dritten Spalte dieses [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float | das Element in der 0 (null) Zeile und der dritten Spalte dieser [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix04() {#getMatrix04--}
```
public float getMatrix04()
```


Liest das Element in der 0 (null) Zeile und der vierten Spalte dieses [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - das Element in der 0 (null) Zeile und der vierten Spalte dieser [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix04(float value) {#setMatrix04-float-}
```
public void setMatrix04(float value)
```


Setzt das Element in der 0 (null) Zeile und der vierten Spalte dieses [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float | das Element in der 0 (null) Zeile und der vierten Spalte dieser [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix10() {#getMatrix10--}
```
public float getMatrix10()
```


Liest das Element in der ersten Zeile und der 0 (null) Spalte dieses [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - das Element in der ersten Zeile und der 0 (null) Spalte dieser [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix10(float value) {#setMatrix10-float-}
```
public void setMatrix10(float value)
```


Setzt das Element in der ersten Zeile und der 0 (null) Spalte dieses [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float | das Element in der ersten Zeile und der 0 (null) Spalte dieser [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix11() {#getMatrix11--}
```
public float getMatrix11()
```


Liest das Element in der ersten Zeile und der ersten Spalte dieses [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - das Element in der ersten Zeile und der ersten Spalte dieser [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix11(float value) {#setMatrix11-float-}
```
public void setMatrix11(float value)
```


Setzt das Element in der ersten Zeile und der ersten Spalte dieses [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float | das Element in der ersten Zeile und der ersten Spalte dieser [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix12() {#getMatrix12--}
```
public float getMatrix12()
```


Liest das Element in der ersten Zeile und der zweiten Spalte dieses [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - das Element in der ersten Zeile und der zweiten Spalte dieser [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix12(float value) {#setMatrix12-float-}
```
public void setMatrix12(float value)
```


Setzt das Element in der ersten Zeile und der zweiten Spalte dieses [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float | das Element in der ersten Zeile und der zweiten Spalte dieser [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix13() {#getMatrix13--}
```
public float getMatrix13()
```


Liest das Element in der ersten Zeile und der dritten Spalte dieses [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - das Element in der ersten Zeile und der dritten Spalte dieser [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix13(float value) {#setMatrix13-float-}
```
public void setMatrix13(float value)
```


Setzt das Element in der ersten Zeile und der dritten Spalte dieses [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float | das Element in der ersten Zeile und der dritten Spalte dieser [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix14() {#getMatrix14--}
```
public float getMatrix14()
```


Liest das Element in der ersten Zeile und der vierten Spalte dieses [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - das Element in der ersten Zeile und der vierten Spalte dieser [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix14(float value) {#setMatrix14-float-}
```
public void setMatrix14(float value)
```


Setzt das Element in der ersten Zeile und der vierten Spalte dieses [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float | das Element in der ersten Zeile und der vierten Spalte dieser [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix20() {#getMatrix20--}
```
public float getMatrix20()
```


Liest das Element in der zweiten Zeile und der 0 (null) Spalte dieses [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - das Element in der zweiten Zeile und der 0 (null) Spalte dieser [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix20(float value) {#setMatrix20-float-}
```
public void setMatrix20(float value)
```


Setzt das Element in der zweiten Zeile und der 0 (null) Spalte dieses [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float | das Element in der zweiten Zeile und der 0 (null) Spalte dieser [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix21() {#getMatrix21--}
```
public float getMatrix21()
```


Liest das Element in der zweiten Zeile und der ersten Spalte dieses [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - das Element in der zweiten Zeile und der ersten Spalte dieser [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix21(float value) {#setMatrix21-float-}
```
public void setMatrix21(float value)
```


Setzt das Element in der zweiten Zeile und der ersten Spalte dieses [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float | das Element in der zweiten Zeile und der ersten Spalte dieser [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix22() {#getMatrix22--}
```
public float getMatrix22()
```


Liest das Element in der zweiten Zeile und der zweiten Spalte dieses [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - das Element in der zweiten Zeile und der zweiten Spalte dieser [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix22(float value) {#setMatrix22-float-}
```
public void setMatrix22(float value)
```


Setzt das Element in der zweiten Zeile und der zweiten Spalte dieses [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float | das Element in der zweiten Zeile und der zweiten Spalte dieser [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix23() {#getMatrix23--}
```
public float getMatrix23()
```


Liest das Element in der zweiten Zeile und der dritten Spalte dieses [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - das Element in der zweiten Zeile und der dritten Spalte dieser [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix23(float value) {#setMatrix23-float-}
```
public void setMatrix23(float value)
```


Setzt das Element in der zweiten Zeile und der dritten Spalte dieses [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float | das Element in der zweiten Zeile und der dritten Spalte dieser [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix24() {#getMatrix24--}
```
public float getMatrix24()
```


Liest das Element in der zweiten Zeile und der vierten Spalte dieses [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - das Element in der zweiten Zeile und der vierten Spalte dieser [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix24(float value) {#setMatrix24-float-}
```
public void setMatrix24(float value)
```


Setzt das Element in der zweiten Zeile und der vierten Spalte dieses [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float | das Element in der zweiten Zeile und vierten Spalte dieses [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix30() {#getMatrix30--}
```
public float getMatrix30()
```


Liest das Element in der dritten Zeile und der 0 (null) Spalte dieses [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - das Element in der dritten Zeile und 0 (null) Spalte dieses [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix30(float value) {#setMatrix30-float-}
```
public void setMatrix30(float value)
```


Setzt das Element in der dritten Zeile und der 0 (null) Spalte dieses [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float | das Element in der dritten Zeile und 0 (null) Spalte dieses [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix31() {#getMatrix31--}
```
public float getMatrix31()
```


Ruft das Element in der dritten Zeile und ersten Spalte dieser [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) ab.

**Returns:**
float - das Element in der dritten Zeile und ersten Spalte dieses [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix31(float value) {#setMatrix31-float-}
```
public void setMatrix31(float value)
```


Setzt das Element in der dritten Zeile und ersten Spalte dieser [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float | das Element in der dritten Zeile und ersten Spalte dieses [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix32() {#getMatrix32--}
```
public float getMatrix32()
```


Ruft das Element in der dritten Zeile und zweiten Spalte dieser [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) ab.

**Returns:**
float - das Element in der dritten Zeile und zweiten Spalte dieses [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix32(float value) {#setMatrix32-float-}
```
public void setMatrix32(float value)
```


Setzt das Element in der dritten Zeile und zweiten Spalte dieser [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float | das Element in der dritten Zeile und zweiten Spalte dieses [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix33() {#getMatrix33--}
```
public float getMatrix33()
```


Ruft das Element in der dritten Zeile und dritten Spalte dieser [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) ab.

**Returns:**
float - das Element in der dritten Zeile und dritten Spalte dieses [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix33(float value) {#setMatrix33-float-}
```
public void setMatrix33(float value)
```


Setzt das Element in der dritten Zeile und dritten Spalte dieser [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float | das Element in der dritten Zeile und dritten Spalte dieses [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix34() {#getMatrix34--}
```
public float getMatrix34()
```


Ruft das Element in der dritten Zeile und vierten Spalte dieser [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) ab.

**Returns:**
float - das Element in der dritten Zeile und vierten Spalte dieses [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix34(float value) {#setMatrix34-float-}
```
public void setMatrix34(float value)
```


Setzt das Element in der dritten Zeile und vierten Spalte dieser [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float | das Element in der dritten Zeile und vierten Spalte dieses [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix40() {#getMatrix40--}
```
public float getMatrix40()
```


Ruft das Element in der vierten Zeile und Spalte 0 (null) dieser [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) ab.

**Returns:**
float - das Element in der vierten Zeile und 0 (null) Spalte dieses [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix40(float value) {#setMatrix40-float-}
```
public void setMatrix40(float value)
```


Setzt das Element in der vierten Zeile und Spalte 0 (null) dieser [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float | das Element in der vierten Zeile und 0 (null) Spalte dieses [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix41() {#getMatrix41--}
```
public float getMatrix41()
```


Ruft das Element in der vierten Zeile und ersten Spalte dieser `.ColorMatrix` ab.

**Returns:**
float - das Element in der vierten Zeile und ersten Spalte dieses `.ColorMatrix`.
### setMatrix41(float value) {#setMatrix41-float-}
```
public void setMatrix41(float value)
```


Setzt das Element in der vierten Zeile und ersten Spalte dieser `.ColorMatrix`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float | das Element in der vierten Zeile und ersten Spalte dieses `.ColorMatrix`. |

### getMatrix42() {#getMatrix42--}
```
public float getMatrix42()
```


Ruft das Element in der vierten Zeile und zweiten Spalte dieser [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) ab.

**Returns:**
float - das Element in der vierten Zeile und zweiten Spalte dieses [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix42(float value) {#setMatrix42-float-}
```
public void setMatrix42(float value)
```


Setzt das Element in der vierten Zeile und zweiten Spalte dieser [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float | das Element in der vierten Zeile und zweiten Spalte dieses [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix43() {#getMatrix43--}
```
public float getMatrix43()
```


Ruft das Element in der vierten Zeile und dritten Spalte dieser [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) ab.

**Returns:**
float - das Element in der vierten Zeile und dritten Spalte dieses [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix43(float value) {#setMatrix43-float-}
```
public void setMatrix43(float value)
```


Setzt das Element in der vierten Zeile und dritten Spalte dieser [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float | das Element in der vierten Zeile und dritten Spalte dieses [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix44() {#getMatrix44--}
```
public float getMatrix44()
```


Ruft das Element in der vierten Zeile und vierten Spalte dieser [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) ab.

**Returns:**
float - das Element in der vierten Zeile und vierten Spalte dieses [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix44(float value) {#setMatrix44-float-}
```
public void setMatrix44(float value)
```


Setzt das Element in der vierten Zeile und vierten Spalte dieser [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float | das Element in der vierten Zeile und vierten Spalte dieses [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### get_Item(int row, int column) {#get-Item-int-int-}
```
public float get_Item(int row, int column)
```


Ruft das Element in der angegebenen Zeile und Spalte der [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) ab.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Zeile | int | Die Zeile des Elements. |
| Spalte | int | Die Spalte des Elements. |

**Returns:**
float - Das Element in der angegebenen Zeile und Spalte.
### set_Item(int row, int column, float value) {#set-Item-int-int-float-}
```
public void set_Item(int row, int column, float value)
```


Setzt das Element in der angegebenen Zeile und Spalte der [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Zeile | int | Die Zeile des Elements. |
| Spalte | int | Die Spalte des Elements. |
| value | float | das Element in der angegebenen Zeile und Spalte in der [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

