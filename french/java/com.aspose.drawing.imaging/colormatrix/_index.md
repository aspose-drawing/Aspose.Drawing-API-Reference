---
title: ColorMatrix
second_title: Référence de l'API Aspose.Drawing pour Java
description: Définit une matrice 5 x 5 qui contient les coordonnées de l'espace RGBA.
type: docs
weight: 14
url: /fr/java/com.aspose.drawing.imaging/colormatrix/
---
**Inheritance:**
java.lang.Object
```
public final class ColorMatrix
```

Définit une matrice 5 x 5 qui contient les coordonnées de l'espace RGBA. Plusieurs méthodes de la classe [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes) ajustent les couleurs d'image en utilisant une matrice de couleur. Cette classe ne peut pas être héritée.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [ColorMatrix()](#ColorMatrix--) | Initialise une nouvelle instance de la classe [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [ColorMatrix(float[][] newColorMatrix)](#ColorMatrix-float-----) | Initialise une nouvelle instance de la classe [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) en utilisant les éléments de la matrice spécifiée `newColorMatrix`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getMatrix00()](#getMatrix00--) | Obtient l'élément à la ligne 0 (zéro) et à la colonne 0 de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix00(float value)](#setMatrix00-float-) | Définit l'élément à la ligne 0 (zéro) et à la colonne 0 de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix01()](#getMatrix01--) | Obtient l'élément à la ligne 0 (zéro) et à la première colonne de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix01(float value)](#setMatrix01-float-) | Définit l'élément à la ligne 0 (zéro) et à la première colonne de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix02()](#getMatrix02--) | Obtient l'élément à la ligne 0 (zéro) et à la deuxième colonne de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix02(float value)](#setMatrix02-float-) | Définit l'élément à la ligne 0 (zéro) et à la deuxième colonne de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix03()](#getMatrix03--) | Obtient l'élément à la ligne 0 (zéro) et à la troisième colonne de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix03(float value)](#setMatrix03-float-) | Définit l'élément à la ligne 0 (zéro) et à la troisième colonne de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix04()](#getMatrix04--) | Obtient l'élément à la ligne 0 (zéro) et à la quatrième colonne de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix04(float value)](#setMatrix04-float-) | Définit l'élément à la ligne 0 (zéro) et à la quatrième colonne de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix10()](#getMatrix10--) | Obtient l'élément à la première ligne et à la colonne 0 (zéro) de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix10(float value)](#setMatrix10-float-) | Définit l'élément à la première ligne et à la colonne 0 (zéro) de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix11()](#getMatrix11--) | Obtient l'élément à la première ligne et à la première colonne de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix11(float value)](#setMatrix11-float-) | Définit l'élément à la première ligne et à la première colonne de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix12()](#getMatrix12--) | Obtient l'élément à la première ligne et à la deuxième colonne de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix12(float value)](#setMatrix12-float-) | Définit l'élément à la première ligne et à la deuxième colonne de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix13()](#getMatrix13--) | Obtient l'élément à la première ligne et à la troisième colonne de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix13(float value)](#setMatrix13-float-) | Définit l'élément à la première ligne et à la troisième colonne de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix14()](#getMatrix14--) | Obtient l'élément à la première ligne et à la quatrième colonne de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix14(float value)](#setMatrix14-float-) | Définit l'élément à la première ligne et à la quatrième colonne de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix20()](#getMatrix20--) | Obtient l'élément à la deuxième ligne et à la colonne 0 (zéro) de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix20(float value)](#setMatrix20-float-) | Définit l'élément à la deuxième ligne et à la colonne 0 (zéro) de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix21()](#getMatrix21--) | Obtient l'élément à la deuxième ligne et à la première colonne de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix21(float value)](#setMatrix21-float-) | Définit l'élément à la deuxième ligne et à la première colonne de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix22()](#getMatrix22--) | Obtient l'élément à la deuxième ligne et à la deuxième colonne de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix22(float value)](#setMatrix22-float-) | Définit l'élément à la deuxième ligne et à la deuxième colonne de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix23()](#getMatrix23--) | Obtient l'élément à la deuxième ligne et à la troisième colonne de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix23(float value)](#setMatrix23-float-) | Définit l'élément à la deuxième ligne et à la troisième colonne de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix24()](#getMatrix24--) | Obtient l'élément à la deuxième ligne et à la quatrième colonne de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix24(float value)](#setMatrix24-float-) | Définit l'élément à la deuxième ligne et à la quatrième colonne de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix30()](#getMatrix30--) | Obtient l'élément à la troisième ligne et à la colonne 0 (zéro) de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix30(float value)](#setMatrix30-float-) | Définit l'élément à la troisième ligne et à la colonne 0 (zéro) de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix31()](#getMatrix31--) | Obtient l'élément à la troisième ligne et à la première colonne de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix31(float value)](#setMatrix31-float-) | Définit l'élément à la troisième ligne et à la première colonne de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix32()](#getMatrix32--) | Obtient l'élément à la troisième ligne et à la deuxième colonne de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix32(float value)](#setMatrix32-float-) | Définit l'élément à la troisième ligne et à la deuxième colonne de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix33()](#getMatrix33--) | Obtient l'élément à la troisième ligne et à la troisième colonne de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix33(float value)](#setMatrix33-float-) | Définit l'élément à la troisième ligne et à la troisième colonne de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix34()](#getMatrix34--) | Obtient l'élément à la troisième ligne et à la quatrième colonne de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix34(float value)](#setMatrix34-float-) | Définit l'élément à la troisième ligne et à la quatrième colonne de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix40()](#getMatrix40--) | Obtient l'élément à la quatrième ligne et à la colonne 0 (zéro) de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix40(float value)](#setMatrix40-float-) | Définit l'élément à la quatrième ligne et à la colonne 0 (zéro) de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix41()](#getMatrix41--) | Obtient l'élément à la quatrième ligne et à la première colonne de ce `.ColorMatrix`. |
| [setMatrix41(float value)](#setMatrix41-float-) | Définit l'élément à la quatrième ligne et à la première colonne de ce `.ColorMatrix`. |
| [getMatrix42()](#getMatrix42--) | Obtient l'élément à la quatrième ligne et à la deuxième colonne de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix42(float value)](#setMatrix42-float-) | Définit l'élément à la quatrième ligne et à la deuxième colonne de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix43()](#getMatrix43--) | Obtient l'élément à la quatrième ligne et à la troisième colonne de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix43(float value)](#setMatrix43-float-) | Définit l'élément à la quatrième ligne et à la troisième colonne de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix44()](#getMatrix44--) | Obtient l'élément à la quatrième ligne et à la quatrième colonne de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix44(float value)](#setMatrix44-float-) | Définit l'élément à la quatrième ligne et à la quatrième colonne de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [get_Item(int row, int column)](#get-Item-int-int-) | Obtient l'élément à la ligne et à la colonne spécifiées dans le [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [set_Item(int row, int column, float value)](#set-Item-int-int-float-) | Définit l'élément à la ligne et à la colonne spécifiées dans le [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
### ColorMatrix() {#ColorMatrix--}
```
public ColorMatrix()
```


Initialise une nouvelle instance de la classe [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

### ColorMatrix(float[][] newColorMatrix) {#ColorMatrix-float-----}
```
public ColorMatrix(float[][] newColorMatrix)
```


Initialise une nouvelle instance de la classe [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) en utilisant les éléments de la matrice spécifiée `newColorMatrix`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| newColorMatrix | float[][] | Les valeurs des éléments pour le nouveau [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix00() {#getMatrix00--}
```
public float getMatrix00()
```


Obtient l'élément à la ligne 0 (zéro) et à la colonne 0 de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - l'élément à la ligne 0 (zéro) et à la colonne 0 de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix00(float value) {#setMatrix00-float-}
```
public void setMatrix00(float value)
```


Définit l'élément à la ligne 0 (zéro) et à la colonne 0 de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float | l'élément à la ligne 0 (zéro) et à la colonne 0 de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix01() {#getMatrix01--}
```
public float getMatrix01()
```


Obtient l'élément à la ligne 0 (zéro) et à la première colonne de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - l'élément à la ligne 0 (zéro) et à la première colonne de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix01(float value) {#setMatrix01-float-}
```
public void setMatrix01(float value)
```


Définit l'élément à la ligne 0 (zéro) et à la première colonne de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float | l'élément à la ligne 0 (zéro) et à la première colonne de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix02() {#getMatrix02--}
```
public float getMatrix02()
```


Obtient l'élément à la ligne 0 (zéro) et à la deuxième colonne de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - l'élément à la ligne 0 (zéro) et à la deuxième colonne de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix02(float value) {#setMatrix02-float-}
```
public void setMatrix02(float value)
```


Définit l'élément à la ligne 0 (zéro) et à la deuxième colonne de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float | l'élément à la ligne 0 (zéro) et à la deuxième colonne de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix03() {#getMatrix03--}
```
public float getMatrix03()
```


Obtient l'élément à la ligne 0 (zéro) et à la troisième colonne de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - l'élément à la ligne 0 (zéro) et à la troisième colonne de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix03(float value) {#setMatrix03-float-}
```
public void setMatrix03(float value)
```


Définit l'élément à la ligne 0 (zéro) et à la troisième colonne de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float | l'élément à la ligne 0 (zéro) et à la troisième colonne de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix04() {#getMatrix04--}
```
public float getMatrix04()
```


Obtient l'élément à la ligne 0 (zéro) et à la quatrième colonne de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - l'élément à la ligne 0 (zéro) et à la quatrième colonne de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix04(float value) {#setMatrix04-float-}
```
public void setMatrix04(float value)
```


Définit l'élément à la ligne 0 (zéro) et à la quatrième colonne de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float | l'élément à la ligne 0 (zéro) et à la quatrième colonne de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix10() {#getMatrix10--}
```
public float getMatrix10()
```


Obtient l'élément à la première ligne et à la colonne 0 (zéro) de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - l'élément à la première ligne et à la colonne 0 (zéro) de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix10(float value) {#setMatrix10-float-}
```
public void setMatrix10(float value)
```


Définit l'élément à la première ligne et à la colonne 0 (zéro) de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float | l'élément à la première ligne et à la colonne 0 (zéro) de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix11() {#getMatrix11--}
```
public float getMatrix11()
```


Obtient l'élément à la première ligne et à la première colonne de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - l'élément à la première ligne et à la première colonne de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix11(float value) {#setMatrix11-float-}
```
public void setMatrix11(float value)
```


Définit l'élément à la première ligne et à la première colonne de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float | l'élément à la première ligne et à la première colonne de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix12() {#getMatrix12--}
```
public float getMatrix12()
```


Obtient l'élément à la première ligne et à la deuxième colonne de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - l'élément à la première ligne et à la deuxième colonne de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix12(float value) {#setMatrix12-float-}
```
public void setMatrix12(float value)
```


Définit l'élément à la première ligne et à la deuxième colonne de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float | l'élément à la première ligne et à la deuxième colonne de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix13() {#getMatrix13--}
```
public float getMatrix13()
```


Obtient l'élément à la première ligne et à la troisième colonne de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - l'élément à la première ligne et à la troisième colonne de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix13(float value) {#setMatrix13-float-}
```
public void setMatrix13(float value)
```


Définit l'élément à la première ligne et à la troisième colonne de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float | l'élément à la première ligne et à la troisième colonne de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix14() {#getMatrix14--}
```
public float getMatrix14()
```


Obtient l'élément à la première ligne et à la quatrième colonne de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - l'élément à la première ligne et à la quatrième colonne de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix14(float value) {#setMatrix14-float-}
```
public void setMatrix14(float value)
```


Définit l'élément à la première ligne et à la quatrième colonne de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float | l'élément à la première ligne et à la quatrième colonne de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix20() {#getMatrix20--}
```
public float getMatrix20()
```


Obtient l'élément à la deuxième ligne et à la colonne 0 (zéro) de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - l'élément à la deuxième ligne et à la colonne 0 (zéro) de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix20(float value) {#setMatrix20-float-}
```
public void setMatrix20(float value)
```


Définit l'élément à la deuxième ligne et à la colonne 0 (zéro) de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float | l'élément à la deuxième ligne et à la colonne 0 (zéro) de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix21() {#getMatrix21--}
```
public float getMatrix21()
```


Obtient l'élément à la deuxième ligne et à la première colonne de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - l'élément à la deuxième ligne et à la première colonne de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix21(float value) {#setMatrix21-float-}
```
public void setMatrix21(float value)
```


Définit l'élément à la deuxième ligne et à la première colonne de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float | l'élément à la deuxième ligne et à la première colonne de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix22() {#getMatrix22--}
```
public float getMatrix22()
```


Obtient l'élément à la deuxième ligne et à la deuxième colonne de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - l'élément à la deuxième ligne et à la deuxième colonne de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix22(float value) {#setMatrix22-float-}
```
public void setMatrix22(float value)
```


Définit l'élément à la deuxième ligne et à la deuxième colonne de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float | l'élément à la deuxième ligne et à la deuxième colonne de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix23() {#getMatrix23--}
```
public float getMatrix23()
```


Obtient l'élément à la deuxième ligne et à la troisième colonne de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - l'élément à la deuxième ligne et à la troisième colonne de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix23(float value) {#setMatrix23-float-}
```
public void setMatrix23(float value)
```


Définit l'élément à la deuxième ligne et à la troisième colonne de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float | l'élément à la deuxième ligne et à la troisième colonne de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix24() {#getMatrix24--}
```
public float getMatrix24()
```


Obtient l'élément à la deuxième ligne et à la quatrième colonne de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - l'élément à la deuxième ligne et à la quatrième colonne de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix24(float value) {#setMatrix24-float-}
```
public void setMatrix24(float value)
```


Définit l'élément à la deuxième ligne et à la quatrième colonne de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float | l'élément de la deuxième ligne et de la quatrième colonne de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix30() {#getMatrix30--}
```
public float getMatrix30()
```


Obtient l'élément à la troisième ligne et à la colonne 0 (zéro) de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - l'élément de la troisième ligne et de la colonne 0 (zéro) de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix30(float value) {#setMatrix30-float-}
```
public void setMatrix30(float value)
```


Définit l'élément à la troisième ligne et à la colonne 0 (zéro) de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float | l'élément de la troisième ligne et de la colonne 0 (zéro) de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix31() {#getMatrix31--}
```
public float getMatrix31()
```


Obtient l'élément à la troisième ligne et à la première colonne de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - l'élément de la troisième ligne et de la première colonne de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix31(float value) {#setMatrix31-float-}
```
public void setMatrix31(float value)
```


Définit l'élément à la troisième ligne et à la première colonne de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float | l'élément de la troisième ligne et de la première colonne de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix32() {#getMatrix32--}
```
public float getMatrix32()
```


Obtient l'élément à la troisième ligne et à la deuxième colonne de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - l'élément de la troisième ligne et de la deuxième colonne de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix32(float value) {#setMatrix32-float-}
```
public void setMatrix32(float value)
```


Définit l'élément à la troisième ligne et à la deuxième colonne de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float | l'élément de la troisième ligne et de la deuxième colonne de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix33() {#getMatrix33--}
```
public float getMatrix33()
```


Obtient l'élément à la troisième ligne et à la troisième colonne de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - l'élément de la troisième ligne et de la troisième colonne de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix33(float value) {#setMatrix33-float-}
```
public void setMatrix33(float value)
```


Définit l'élément à la troisième ligne et à la troisième colonne de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float | l'élément de la troisième ligne et de la troisième colonne de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix34() {#getMatrix34--}
```
public float getMatrix34()
```


Obtient l'élément à la troisième ligne et à la quatrième colonne de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - l'élément de la troisième ligne et de la quatrième colonne de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix34(float value) {#setMatrix34-float-}
```
public void setMatrix34(float value)
```


Définit l'élément à la troisième ligne et à la quatrième colonne de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float | l'élément de la troisième ligne et de la quatrième colonne de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix40() {#getMatrix40--}
```
public float getMatrix40()
```


Obtient l'élément à la quatrième ligne et à la colonne 0 (zéro) de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - l'élément de la quatrième ligne et de la colonne 0 (zéro) de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix40(float value) {#setMatrix40-float-}
```
public void setMatrix40(float value)
```


Définit l'élément à la quatrième ligne et à la colonne 0 (zéro) de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float | l'élément de la quatrième ligne et de la colonne 0 (zéro) de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix41() {#getMatrix41--}
```
public float getMatrix41()
```


Obtient l'élément à la quatrième ligne et à la première colonne de ce `.ColorMatrix`.

**Returns:**
float - l'élément de la quatrième ligne et de la première colonne de ce `.ColorMatrix`.
### setMatrix41(float value) {#setMatrix41-float-}
```
public void setMatrix41(float value)
```


Définit l'élément à la quatrième ligne et à la première colonne de ce `.ColorMatrix`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float | l'élément de la quatrième ligne et de la première colonne de ce `.ColorMatrix`. |

### getMatrix42() {#getMatrix42--}
```
public float getMatrix42()
```


Obtient l'élément à la quatrième ligne et à la deuxième colonne de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - l'élément de la quatrième ligne et de la deuxième colonne de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix42(float value) {#setMatrix42-float-}
```
public void setMatrix42(float value)
```


Définit l'élément à la quatrième ligne et à la deuxième colonne de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float | l'élément de la quatrième ligne et de la deuxième colonne de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix43() {#getMatrix43--}
```
public float getMatrix43()
```


Obtient l'élément à la quatrième ligne et à la troisième colonne de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - l'élément de la quatrième ligne et de la troisième colonne de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix43(float value) {#setMatrix43-float-}
```
public void setMatrix43(float value)
```


Définit l'élément à la quatrième ligne et à la troisième colonne de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float | l'élément de la quatrième ligne et de la troisième colonne de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix44() {#getMatrix44--}
```
public float getMatrix44()
```


Obtient l'élément à la quatrième ligne et à la quatrième colonne de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - l'élément de la quatrième ligne et de la quatrième colonne de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix44(float value) {#setMatrix44-float-}
```
public void setMatrix44(float value)
```


Définit l'élément à la quatrième ligne et à la quatrième colonne de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float | l'élément de la quatrième ligne et de la quatrième colonne de ce [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### get_Item(int row, int column) {#get-Item-int-int-}
```
public float get_Item(int row, int column)
```


Obtient l'élément à la ligne et à la colonne spécifiées dans le [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| ligne | int | La ligne de l'élément. |
| colonne | int | La colonne de l'élément. |

**Returns:**
float - L'élément à la ligne et colonne spécifiées.
### set_Item(int row, int column, float value) {#set-Item-int-int-float-}
```
public void set_Item(int row, int column, float value)
```


Définit l'élément à la ligne et à la colonne spécifiées dans le [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| ligne | int | La ligne de l'élément. |
| colonne | int | La colonne de l'élément. |
| value | float | l'élément à la ligne et colonne spécifiées dans le [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

