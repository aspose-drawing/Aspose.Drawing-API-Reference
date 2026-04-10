---
title: CustomLineCap
second_title: Référence de l'API Aspose.Drawing pour Java
description: Encapsule un embout de ligne personnalisé défini par l'utilisateur.
type: docs
weight: 17
url: /fr/java/com.aspose.drawing.drawing2d/customlinecap/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public class CustomLineCap implements System.IDisposable
```

Encapsule un embout de ligne personnalisé défini par l'utilisateur.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath)](#CustomLineCap-com.aspose.drawing.drawing2d.GraphicsPath-com.aspose.drawing.drawing2d.GraphicsPath-) | Initialise une nouvelle instance de la classe [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) avec le contour et le remplissage spécifiés. |
| [CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap)](#CustomLineCap-com.aspose.drawing.drawing2d.GraphicsPath-com.aspose.drawing.drawing2d.GraphicsPath-int-) | Initialise une nouvelle instance de la classe [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) à partir de l'énumération [LineCap](../../com.aspose.drawing.drawing2d/linecap) existante spécifiée, avec le contour et le remplissage spécifiés. |
| [CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap, float baseInset)](#CustomLineCap-com.aspose.drawing.drawing2d.GraphicsPath-com.aspose.drawing.drawing2d.GraphicsPath-int-float-) | Initialise une nouvelle instance de la classe [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) à partir de l'énumération [LineCap](../../com.aspose.drawing.drawing2d/linecap) existante spécifiée, avec le contour, le remplissage et l'encastrement spécifiés. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getStrokeJoin()](#getStrokeJoin--) | Obtient ou définit l'énumération [LineJoin](../../com.aspose.drawing.drawing2d/linejoin) qui détermine comment les lignes qui composent cet objet [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) sont jointes. |
| [setStrokeJoin(int value)](#setStrokeJoin-int-) | Obtient ou définit l'énumération [LineJoin](../../com.aspose.drawing.drawing2d/linejoin) qui détermine comment les lignes qui composent cet objet [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) sont jointes. |
| [getBaseCap()](#getBaseCap--) | Obtient ou définit l'énumération [LineCap](../../com.aspose.drawing.drawing2d/linecap) sur laquelle ce [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) est basé. |
| [setBaseCap(int value)](#setBaseCap-int-) | Obtient ou définit l'énumération [LineCap](../../com.aspose.drawing.drawing2d/linecap) sur laquelle ce [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) est basé. |
| [getBaseInset()](#getBaseInset--) | Obtient ou définit la distance entre le capuchon et la ligne. |
| [setBaseInset(float value)](#setBaseInset-float-) | Obtient ou définit la distance entre le capuchon et la ligne. |
| [getWidthScale()](#getWidthScale--) | Obtient ou définit la quantité par laquelle mettre à l'échelle cet objet de classe [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) par rapport à la largeur de l'objet [Pen](../../com.aspose.drawing/pen). |
| [setWidthScale(float value)](#setWidthScale-float-) | Obtient ou définit la quantité par laquelle mettre à l'échelle cet objet de classe [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) par rapport à la largeur de l'objet [Pen](../../com.aspose.drawing/pen). |
| [dispose()](#dispose--) | Libère toutes les ressources utilisées par cet objet [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap). |
| [deepClone()](#deepClone--) | Crée une copie exacte de ce [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap). |
| [setStrokeCaps(int startCap, int endCap)](#setStrokeCaps-int-int-) | Définit les caps utilisés pour commencer et terminer les lignes qui composent ce cap personnalisé. |
| [getStrokeCaps(int[] startCap, int[] endCap)](#getStrokeCaps-int---int---) | Obtient les caps utilisés pour commencer et terminer les lignes qui composent ce cap personnalisé. |
| [getFillPath()](#getFillPath--) |  |
| [getStrokePath()](#getStrokePath--) | Obtient l'objet qui définit le contour de ce cap personnalisé. |
### CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath) {#CustomLineCap-com.aspose.drawing.drawing2d.GraphicsPath-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath)
```


Initialise une nouvelle instance de la classe [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) avec le contour et le remplissage spécifiés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fillPath | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | Un objet [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) qui définit le remplissage du cap personnalisé. |
| strokePath | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | Un objet [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) qui définit le contour du cap personnalisé. |

### CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap) {#CustomLineCap-com.aspose.drawing.drawing2d.GraphicsPath-com.aspose.drawing.drawing2d.GraphicsPath-int-}
```
public CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap)
```


Initialise une nouvelle instance de la classe [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) à partir de l'énumération [LineCap](../../com.aspose.drawing.drawing2d/linecap) existante spécifiée, avec le contour et le remplissage spécifiés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fillPath | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | Un objet [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) qui définit le remplissage du cap personnalisé. |
| strokePath | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | Un objet [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) qui définit le contour du cap personnalisé. |
| baseCap | int | Le cap de ligne à partir duquel créer le cap personnalisé. |

### CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap, float baseInset) {#CustomLineCap-com.aspose.drawing.drawing2d.GraphicsPath-com.aspose.drawing.drawing2d.GraphicsPath-int-float-}
```
public CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap, float baseInset)
```


Initialise une nouvelle instance de la classe [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) à partir de l'énumération [LineCap](../../com.aspose.drawing.drawing2d/linecap) existante spécifiée, avec le contour, le remplissage et l'encastrement spécifiés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fillPath | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | Un objet [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) qui définit le remplissage du cap personnalisé. |
| strokePath | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | Un objet [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) qui définit le contour du cap personnalisé. |
| baseCap | int | Le cap de ligne à partir duquel créer le cap personnalisé. |
| baseInset | float | La distance entre le cap et la ligne. |

### getStrokeJoin() {#getStrokeJoin--}
```
public final int getStrokeJoin()
```


Obtient ou définit l'énumération [LineJoin](../../com.aspose.drawing.drawing2d/linejoin) qui détermine comment les lignes qui composent cet objet [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) sont jointes.

**Returns:**
int
### setStrokeJoin(int value) {#setStrokeJoin-int-}
```
public final void setStrokeJoin(int value)
```


Obtient ou définit l'énumération [LineJoin](../../com.aspose.drawing.drawing2d/linejoin) qui détermine comment les lignes qui composent cet objet [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) sont jointes.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getBaseCap() {#getBaseCap--}
```
public final int getBaseCap()
```


Obtient ou définit l'énumération [LineCap](../../com.aspose.drawing.drawing2d/linecap) sur laquelle ce [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) est basé.

**Returns:**
int
### setBaseCap(int value) {#setBaseCap-int-}
```
public final void setBaseCap(int value)
```


Obtient ou définit l'énumération [LineCap](../../com.aspose.drawing.drawing2d/linecap) sur laquelle ce [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) est basé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getBaseInset() {#getBaseInset--}
```
public final float getBaseInset()
```


Obtient ou définit la distance entre le capuchon et la ligne.

**Returns:**
float
### setBaseInset(float value) {#setBaseInset-float-}
```
public final void setBaseInset(float value)
```


Obtient ou définit la distance entre le capuchon et la ligne.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |

### getWidthScale() {#getWidthScale--}
```
public final float getWidthScale()
```


Obtient ou définit la quantité par laquelle mettre à l'échelle cet objet de classe [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) par rapport à la largeur de l'objet [Pen](../../com.aspose.drawing/pen).

**Returns:**
float
### setWidthScale(float value) {#setWidthScale-float-}
```
public final void setWidthScale(float value)
```


Obtient ou définit la quantité par laquelle mettre à l'échelle cet objet de classe [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) par rapport à la largeur de l'objet [Pen](../../com.aspose.drawing/pen).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |

### dispose() {#dispose--}
```
public final void dispose()
```


Libère toutes les ressources utilisées par cet objet [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap).

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Crée une copie exacte de ce [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap).

**Returns:**
java.lang.Object - Le [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) que cette méthode crée, casté en tant qu'objet.
### setStrokeCaps(int startCap, int endCap) {#setStrokeCaps-int-int-}
```
public final void setStrokeCaps(int startCap, int endCap)
```


Définit les caps utilisés pour commencer et terminer les lignes qui composent ce cap personnalisé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| startCap | int | L'énumération [LineCap](../../com.aspose.drawing.drawing2d/linecap) utilisée au début d'une ligne dans ce cap. |
| endCap | int | L'énumération [LineCap](../../com.aspose.drawing.drawing2d/linecap) utilisée à la fin d'une ligne dans ce cap. |

### getStrokeCaps(int[] startCap, int[] endCap) {#getStrokeCaps-int---int---}
```
public final void getStrokeCaps(int[] startCap, int[] endCap)
```


Obtient les caps utilisés pour commencer et terminer les lignes qui composent ce cap personnalisé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| startCap | int[] | L'énumération [LineCap](../../com.aspose.drawing.drawing2d/linecap) utilisée au début d'une ligne dans ce cap. |
| endCap | int[] | L'énumération [LineCap](../../com.aspose.drawing.drawing2d/linecap) utilisée à la fin d'une ligne dans ce cap. |

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


Obtient l'objet qui définit le contour de ce cap personnalisé.

**Returns:**
[GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) - The object that defines the outline of the custom cap.
