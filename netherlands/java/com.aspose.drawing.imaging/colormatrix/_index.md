---
title: ColorMatrix
second_title: Aspose.Drawing voor Java API-referentie
description: Definieert een 5 x 5 matrix die de coördinaten voor de RGBA-ruimte bevat.
type: docs
weight: 14
url: /nl/java/com.aspose.drawing.imaging/colormatrix/
---
**Inheritance:**
java.lang.Object
```
public final class ColorMatrix
```

Definieert een 5 x 5 matrix die de coördinaten voor de RGBA-ruimte bevat. Verschillende methoden van de [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes) klasse passen afbeeldingskleuren aan door een kleurmatrix te gebruiken. Deze klasse kan niet worden geërfd.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [ColorMatrix()](#ColorMatrix--) | Initialiseert een nieuw exemplaar van de [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) klasse. |
| [ColorMatrix(float[][] newColorMatrix)](#ColorMatrix-float-----) | Initialiseert een nieuw exemplaar van de [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) klasse met behulp van de elementen in de opgegeven matrix `newColorMatrix`. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getMatrix00()](#getMatrix00--) | Haalt het element op in rij 0 (nul) en kolom 0 van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix00(float value)](#setMatrix00-float-) | Stelt het element in op rij 0 (nul) en kolom 0 van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix01()](#getMatrix01--) | Haalt het element op in rij 0 (nul) en eerste kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix01(float value)](#setMatrix01-float-) | Stelt het element in op rij 0 (nul) en eerste kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix02()](#getMatrix02--) | Haalt het element op in rij 0 (nul) en tweede kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix02(float value)](#setMatrix02-float-) | Stelt het element in op rij 0 (nul) en tweede kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix03()](#getMatrix03--) | Haalt het element op in rij 0 (nul) en derde kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix03(float value)](#setMatrix03-float-) | Stelt het element in op de 0 (nul) rij en derde kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix04()](#getMatrix04--) | Haalt het element op op de 0 (nul) rij en vierde kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix04(float value)](#setMatrix04-float-) | Stelt het element in op de 0 (nul) rij en vierde kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix10()](#getMatrix10--) | Haalt het element op op de eerste rij en 0 (nul) kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix10(float value)](#setMatrix10-float-) | Stelt het element in op de eerste rij en 0 (nul) kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix11()](#getMatrix11--) | Haalt het element op op de eerste rij en eerste kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix11(float value)](#setMatrix11-float-) | Stelt het element in op de eerste rij en eerste kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix12()](#getMatrix12--) | Haalt het element op op de eerste rij en tweede kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix12(float value)](#setMatrix12-float-) | Stelt het element in op de eerste rij en tweede kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix13()](#getMatrix13--) | Haalt het element op op de eerste rij en derde kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix13(float value)](#setMatrix13-float-) | Stelt het element in op de eerste rij en derde kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix14()](#getMatrix14--) | Haalt het element op op de eerste rij en vierde kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix14(float value)](#setMatrix14-float-) | Stelt het element in op de eerste rij en vierde kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix20()](#getMatrix20--) | Haalt het element op op de tweede rij en 0 (nul) kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix20(float value)](#setMatrix20-float-) | Stelt het element in op de tweede rij en 0 (nul) kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix21()](#getMatrix21--) | Haalt het element op op de tweede rij en eerste kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix21(float value)](#setMatrix21-float-) | Stelt het element in op de tweede rij en eerste kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix22()](#getMatrix22--) | Haalt het element op op de tweede rij en tweede kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix22(float value)](#setMatrix22-float-) | Stelt het element in op de tweede rij en tweede kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix23()](#getMatrix23--) | Haalt het element op op de tweede rij en derde kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix23(float value)](#setMatrix23-float-) | Stelt het element in op de tweede rij en derde kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix24()](#getMatrix24--) | Haalt het element op op de tweede rij en vierde kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix24(float value)](#setMatrix24-float-) | Stelt het element in op de tweede rij en vierde kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix30()](#getMatrix30--) | Haalt het element op op de derde rij en 0 (nul) kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix30(float value)](#setMatrix30-float-) | Stelt het element in op de derde rij en 0 (nul) kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix31()](#getMatrix31--) | Haalt het element op in de derde rij en eerste kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix31(float value)](#setMatrix31-float-) | Stelt het element in op de derde rij en eerste kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix32()](#getMatrix32--) | Haalt het element op in de derde rij en tweede kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix32(float value)](#setMatrix32-float-) | Stelt het element in op de derde rij en tweede kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix33()](#getMatrix33--) | Haalt het element op in de derde rij en derde kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix33(float value)](#setMatrix33-float-) | Stelt het element in op de derde rij en derde kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix34()](#getMatrix34--) | Haalt het element op in de derde rij en vierde kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix34(float value)](#setMatrix34-float-) | Stelt het element in op de derde rij en vierde kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix40()](#getMatrix40--) | Haalt het element op in de vierde rij en 0 (nul) kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix40(float value)](#setMatrix40-float-) | Stelt het element in op de vierde rij en 0 (nul) kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix41()](#getMatrix41--) | Haalt het element op in de vierde rij en eerste kolom van deze `.ColorMatrix`. |
| [setMatrix41(float value)](#setMatrix41-float-) | Stelt het element in op de vierde rij en eerste kolom van deze `.ColorMatrix`. |
| [getMatrix42()](#getMatrix42--) | Haalt het element op in de vierde rij en tweede kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix42(float value)](#setMatrix42-float-) | Stelt het element in op de vierde rij en tweede kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix43()](#getMatrix43--) | Haalt het element op in de vierde rij en derde kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix43(float value)](#setMatrix43-float-) | Stelt het element in op de vierde rij en derde kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix44()](#getMatrix44--) | Haalt het element op in de vierde rij en vierde kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix44(float value)](#setMatrix44-float-) | Stelt het element in op de vierde rij en vierde kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [get_Item(int row, int column)](#get-Item-int-int-) | Haalt het element op in de opgegeven rij en kolom in de [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [set_Item(int row, int column, float value)](#set-Item-int-int-float-) | Stelt het element in op de opgegeven rij en kolom in de [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
### ColorMatrix() {#ColorMatrix--}
```
public ColorMatrix()
```


Initialiseert een nieuw exemplaar van de [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) klasse.

### ColorMatrix(float[][] newColorMatrix) {#ColorMatrix-float-----}
```
public ColorMatrix(float[][] newColorMatrix)
```


Initialiseert een nieuw exemplaar van de [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) klasse met behulp van de elementen in de opgegeven matrix `newColorMatrix`.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| newColorMatrix | float[][] | De waarden van de elementen voor de nieuwe [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix00() {#getMatrix00--}
```
public float getMatrix00()
```


Haalt het element op in rij 0 (nul) en kolom 0 van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - het element in de 0 (nul) rij en 0 kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix00(float value) {#setMatrix00-float-}
```
public void setMatrix00(float value)
```


Stelt het element in op rij 0 (nul) en kolom 0 van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float | het element in de 0 (nul) rij en 0 kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix01() {#getMatrix01--}
```
public float getMatrix01()
```


Haalt het element op in rij 0 (nul) en eerste kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - het element in de 0 (nul) rij en eerste kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix01(float value) {#setMatrix01-float-}
```
public void setMatrix01(float value)
```


Stelt het element in op rij 0 (nul) en eerste kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float | het element in de 0 (nul) rij en eerste kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix02() {#getMatrix02--}
```
public float getMatrix02()
```


Haalt het element op in rij 0 (nul) en tweede kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - het element op de 0 (nul) rij en tweede kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix02(float value) {#setMatrix02-float-}
```
public void setMatrix02(float value)
```


Stelt het element in op rij 0 (nul) en tweede kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float | het element op de 0 (nul) rij en tweede kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix03() {#getMatrix03--}
```
public float getMatrix03()
```


Haalt het element op in rij 0 (nul) en derde kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - het element op de 0 (nul) rij en derde kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix03(float value) {#setMatrix03-float-}
```
public void setMatrix03(float value)
```


Stelt het element in op de 0 (nul) rij en derde kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float | het element op de 0 (nul) rij en derde kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix04() {#getMatrix04--}
```
public float getMatrix04()
```


Haalt het element op op de 0 (nul) rij en vierde kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - het element op de 0 (nul) rij en vierde kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix04(float value) {#setMatrix04-float-}
```
public void setMatrix04(float value)
```


Stelt het element in op de 0 (nul) rij en vierde kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float | het element op de 0 (nul) rij en vierde kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix10() {#getMatrix10--}
```
public float getMatrix10()
```


Haalt het element op op de eerste rij en 0 (nul) kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - het element op de eerste rij en 0 (nul) kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix10(float value) {#setMatrix10-float-}
```
public void setMatrix10(float value)
```


Stelt het element in op de eerste rij en 0 (nul) kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float | het element op de eerste rij en 0 (nul) kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix11() {#getMatrix11--}
```
public float getMatrix11()
```


Haalt het element op op de eerste rij en eerste kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - het element op de eerste rij en eerste kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix11(float value) {#setMatrix11-float-}
```
public void setMatrix11(float value)
```


Stelt het element in op de eerste rij en eerste kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float | het element op de eerste rij en eerste kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix12() {#getMatrix12--}
```
public float getMatrix12()
```


Haalt het element op op de eerste rij en tweede kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - het element op de eerste rij en tweede kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix12(float value) {#setMatrix12-float-}
```
public void setMatrix12(float value)
```


Stelt het element in op de eerste rij en tweede kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float | het element op de eerste rij en tweede kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix13() {#getMatrix13--}
```
public float getMatrix13()
```


Haalt het element op op de eerste rij en derde kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - het element op de eerste rij en derde kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix13(float value) {#setMatrix13-float-}
```
public void setMatrix13(float value)
```


Stelt het element in op de eerste rij en derde kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float | het element op de eerste rij en derde kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix14() {#getMatrix14--}
```
public float getMatrix14()
```


Haalt het element op op de eerste rij en vierde kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - het element op de eerste rij en vierde kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix14(float value) {#setMatrix14-float-}
```
public void setMatrix14(float value)
```


Stelt het element in op de eerste rij en vierde kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float | het element op de eerste rij en vierde kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix20() {#getMatrix20--}
```
public float getMatrix20()
```


Haalt het element op op de tweede rij en 0 (nul) kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - het element op de tweede rij en 0 (nul) kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix20(float value) {#setMatrix20-float-}
```
public void setMatrix20(float value)
```


Stelt het element in op de tweede rij en 0 (nul) kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float | het element op de tweede rij en 0 (nul) kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix21() {#getMatrix21--}
```
public float getMatrix21()
```


Haalt het element op op de tweede rij en eerste kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - het element op de tweede rij en eerste kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix21(float value) {#setMatrix21-float-}
```
public void setMatrix21(float value)
```


Stelt het element in op de tweede rij en eerste kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float | het element op de tweede rij en eerste kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix22() {#getMatrix22--}
```
public float getMatrix22()
```


Haalt het element op op de tweede rij en tweede kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - het element op de tweede rij en tweede kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix22(float value) {#setMatrix22-float-}
```
public void setMatrix22(float value)
```


Stelt het element in op de tweede rij en tweede kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float | het element op de tweede rij en tweede kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix23() {#getMatrix23--}
```
public float getMatrix23()
```


Haalt het element op op de tweede rij en derde kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - het element op de tweede rij en derde kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix23(float value) {#setMatrix23-float-}
```
public void setMatrix23(float value)
```


Stelt het element in op de tweede rij en derde kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float | het element op de tweede rij en derde kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix24() {#getMatrix24--}
```
public float getMatrix24()
```


Haalt het element op op de tweede rij en vierde kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - het element op de tweede rij en vierde kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix24(float value) {#setMatrix24-float-}
```
public void setMatrix24(float value)
```


Stelt het element in op de tweede rij en vierde kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float | het element op de tweede rij en vierde kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix30() {#getMatrix30--}
```
public float getMatrix30()
```


Haalt het element op op de derde rij en 0 (nul) kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - het element op de derde rij en 0 (nul) kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix30(float value) {#setMatrix30-float-}
```
public void setMatrix30(float value)
```


Stelt het element in op de derde rij en 0 (nul) kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float | het element op de derde rij en 0 (nul) kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix31() {#getMatrix31--}
```
public float getMatrix31()
```


Haalt het element op in de derde rij en eerste kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - het element op de derde rij en eerste kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix31(float value) {#setMatrix31-float-}
```
public void setMatrix31(float value)
```


Stelt het element in op de derde rij en eerste kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float | het element op de derde rij en eerste kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix32() {#getMatrix32--}
```
public float getMatrix32()
```


Haalt het element op in de derde rij en tweede kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - het element op de derde rij en tweede kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix32(float value) {#setMatrix32-float-}
```
public void setMatrix32(float value)
```


Stelt het element in op de derde rij en tweede kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float | het element op de derde rij en tweede kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix33() {#getMatrix33--}
```
public float getMatrix33()
```


Haalt het element op in de derde rij en derde kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - het element op de derde rij en derde kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix33(float value) {#setMatrix33-float-}
```
public void setMatrix33(float value)
```


Stelt het element in op de derde rij en derde kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float | het element op de derde rij en derde kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix34() {#getMatrix34--}
```
public float getMatrix34()
```


Haalt het element op in de derde rij en vierde kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - het element op de derde rij en vierde kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix34(float value) {#setMatrix34-float-}
```
public void setMatrix34(float value)
```


Stelt het element in op de derde rij en vierde kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float | het element op de derde rij en vierde kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix40() {#getMatrix40--}
```
public float getMatrix40()
```


Haalt het element op in de vierde rij en 0 (nul) kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - het element op de vierde rij en 0 (nul) kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix40(float value) {#setMatrix40-float-}
```
public void setMatrix40(float value)
```


Stelt het element in op de vierde rij en 0 (nul) kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float | het element op de vierde rij en 0 (nul) kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix41() {#getMatrix41--}
```
public float getMatrix41()
```


Haalt het element op in de vierde rij en eerste kolom van deze `.ColorMatrix`.

**Returns:**
float - het element op de vierde rij en eerste kolom van deze `.ColorMatrix`.
### setMatrix41(float value) {#setMatrix41-float-}
```
public void setMatrix41(float value)
```


Stelt het element in op de vierde rij en eerste kolom van deze `.ColorMatrix`.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float | het element op de vierde rij en eerste kolom van deze `.ColorMatrix`. |

### getMatrix42() {#getMatrix42--}
```
public float getMatrix42()
```


Haalt het element op in de vierde rij en tweede kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - het element op de vierde rij en tweede kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix42(float value) {#setMatrix42-float-}
```
public void setMatrix42(float value)
```


Stelt het element in op de vierde rij en tweede kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float | het element op de vierde rij en tweede kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix43() {#getMatrix43--}
```
public float getMatrix43()
```


Haalt het element op in de vierde rij en derde kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - het element op de vierde rij en derde kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix43(float value) {#setMatrix43-float-}
```
public void setMatrix43(float value)
```


Stelt het element in op de vierde rij en derde kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float | het element op de vierde rij en derde kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix44() {#getMatrix44--}
```
public float getMatrix44()
```


Haalt het element op in de vierde rij en vierde kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - het element op de vierde rij en vierde kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix44(float value) {#setMatrix44-float-}
```
public void setMatrix44(float value)
```


Stelt het element in op de vierde rij en vierde kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float | het element op de vierde rij en vierde kolom van deze [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### get_Item(int row, int column) {#get-Item-int-int-}
```
public float get_Item(int row, int column)
```


Haalt het element op in de opgegeven rij en kolom in de [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rij | int | De rij van het element. |
| kolom | int | De kolom van het element. |

**Returns:**
float - Het element op de opgegeven rij en kolom.
### set_Item(int row, int column, float value) {#set-Item-int-int-float-}
```
public void set_Item(int row, int column, float value)
```


Stelt het element in op de opgegeven rij en kolom in de [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rij | int | De rij van het element. |
| kolom | int | De kolom van het element. |
| value | float | het element op de opgegeven rij en kolom in de [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

