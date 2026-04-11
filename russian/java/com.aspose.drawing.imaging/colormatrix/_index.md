---
title: ColorMatrix
second_title: Справочник API Aspose.Drawing для Java
description: Определяет матрицу 5 x 5, содержащую координаты для пространства RGBA.
type: docs
weight: 14
url: /ru/java/com.aspose.drawing.imaging/colormatrix/
---
**Inheritance:**
java.lang.Object
```
public final class ColorMatrix
```

Определяет матрицу 5 x 5, содержащую координаты для пространства RGBA. Несколько методов класса [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes) корректируют цвета изображения с помощью цветовой матрицы. Этот класс не может быть наследован.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [ColorMatrix()](#ColorMatrix--) | Инициализирует новый экземпляр класса [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [ColorMatrix(float[][] newColorMatrix)](#ColorMatrix-float-----) | Инициализирует новый экземпляр класса [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix), используя элементы указанной матрицы `newColorMatrix`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getMatrix00()](#getMatrix00--) | Получает элемент в 0‑й (ноль) строке и 0‑м столбце этой [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix00(float value)](#setMatrix00-float-) | Устанавливает элемент в 0‑й (ноль) строке и 0‑м столбце этой [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix01()](#getMatrix01--) | Получает элемент в 0‑й (ноль) строке и первом столбце этой [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix01(float value)](#setMatrix01-float-) | Устанавливает элемент в 0‑й (ноль) строке и первом столбце этой [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix02()](#getMatrix02--) | Получает элемент в 0‑й (ноль) строке и втором столбце этой [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix02(float value)](#setMatrix02-float-) | Устанавливает элемент в 0‑й (ноль) строке и втором столбце этой [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix03()](#getMatrix03--) | Получает элемент в 0‑й (ноль) строке и третьем столбце этой [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix03(float value)](#setMatrix03-float-) | Устанавливает элемент в 0 (ноль) строке и третьем столбце этого [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix04()](#getMatrix04--) | Получает элемент в 0 (ноль) строке и четвертом столбце этого [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix04(float value)](#setMatrix04-float-) | Устанавливает элемент в 0 (ноль) строке и четвертом столбце этого [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix10()](#getMatrix10--) | Получает элемент в первой строке и 0 (ноль) столбце этого [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix10(float value)](#setMatrix10-float-) | Устанавливает элемент в первой строке и 0 (ноль) столбце этого [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix11()](#getMatrix11--) | Получает элемент в первой строке и первом столбце этого [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix11(float value)](#setMatrix11-float-) | Устанавливает элемент в первой строке и первом столбце этого [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix12()](#getMatrix12--) | Получает элемент в первой строке и втором столбце этого [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix12(float value)](#setMatrix12-float-) | Устанавливает элемент в первой строке и втором столбце этого [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix13()](#getMatrix13--) | Получает элемент в первой строке и третьем столбце этого [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix13(float value)](#setMatrix13-float-) | Устанавливает элемент в первой строке и третьем столбце этого [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix14()](#getMatrix14--) | Получает элемент в первой строке и четвертом столбце этого [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix14(float value)](#setMatrix14-float-) | Устанавливает элемент в первой строке и четвертом столбце этого [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix20()](#getMatrix20--) | Получает элемент во второй строке и 0 (ноль) столбце этого [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix20(float value)](#setMatrix20-float-) | Устанавливает элемент во второй строке и 0 (ноль) столбце этого [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix21()](#getMatrix21--) | Получает элемент во второй строке и первом столбце этого [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix21(float value)](#setMatrix21-float-) | Устанавливает элемент во второй строке и первом столбце этого [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix22()](#getMatrix22--) | Получает элемент во второй строке и втором столбце этого [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix22(float value)](#setMatrix22-float-) | Устанавливает элемент во второй строке и втором столбце этого [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix23()](#getMatrix23--) | Получает элемент во второй строке и третьем столбце этого [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix23(float value)](#setMatrix23-float-) | Устанавливает элемент во второй строке и третьем столбце этого [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix24()](#getMatrix24--) | Получает элемент во второй строке и четвертом столбце этого [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix24(float value)](#setMatrix24-float-) | Устанавливает элемент во второй строке и четвертом столбце этого [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix30()](#getMatrix30--) | Получает элемент в третьей строке и 0 (ноль) столбце этого [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix30(float value)](#setMatrix30-float-) | Устанавливает элемент в третьей строке и 0 (ноль) столбце этого [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix31()](#getMatrix31--) | Получает элемент в третьей строке и первом столбце этой [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix31(float value)](#setMatrix31-float-) | Устанавливает элемент в третьей строке и первом столбце этой [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix32()](#getMatrix32--) | Получает элемент в третьей строке и втором столбце этой [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix32(float value)](#setMatrix32-float-) | Устанавливает элемент в третьей строке и втором столбце этой [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix33()](#getMatrix33--) | Получает элемент в третьей строке и третьем столбце этой [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix33(float value)](#setMatrix33-float-) | Устанавливает элемент в третьей строке и третьем столбце этой [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix34()](#getMatrix34--) | Получает элемент в третьей строке и четвертом столбце этой [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix34(float value)](#setMatrix34-float-) | Устанавливает элемент в третьей строке и четвертом столбце этой [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix40()](#getMatrix40--) | Получает элемент в четвертой строке и столбце 0 (ноль) этой [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix40(float value)](#setMatrix40-float-) | Устанавливает элемент в четвертой строке и столбце 0 (ноль) этой [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix41()](#getMatrix41--) | Получает элемент в четвертой строке и первом столбце этого `.ColorMatrix`. |
| [setMatrix41(float value)](#setMatrix41-float-) | Устанавливает элемент в четвертой строке и первом столбце этого `.ColorMatrix`. |
| [getMatrix42()](#getMatrix42--) | Получает элемент в четвертой строке и втором столбце этой [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix42(float value)](#setMatrix42-float-) | Устанавливает элемент в четвертой строке и втором столбце этой [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix43()](#getMatrix43--) | Получает элемент в четвертой строке и третьем столбце этой [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix43(float value)](#setMatrix43-float-) | Устанавливает элемент в четвертой строке и третьем столбце этой [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix44()](#getMatrix44--) | Получает элемент в четвертой строке и четвертом столбце этой [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix44(float value)](#setMatrix44-float-) | Устанавливает элемент в четвертой строке и четвертом столбце этой [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [get_Item(int row, int column)](#get-Item-int-int-) | Получает элемент в указанной строке и столбце в [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [set_Item(int row, int column, float value)](#set-Item-int-int-float-) | Устанавливает элемент в указанной строке и столбце в [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
### ColorMatrix() {#ColorMatrix--}
```
public ColorMatrix()
```


Инициализирует новый экземпляр класса [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

### ColorMatrix(float[][] newColorMatrix) {#ColorMatrix-float-----}
```
public ColorMatrix(float[][] newColorMatrix)
```


Инициализирует новый экземпляр класса [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix), используя элементы указанной матрицы `newColorMatrix`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| newColorMatrix | float[][] | Значения элементов нового [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix00() {#getMatrix00--}
```
public float getMatrix00()
```


Получает элемент в 0‑й (ноль) строке и 0‑м столбце этой [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float — элемент в строке 0 (ноль) и столбце 0 этой [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix00(float value) {#setMatrix00-float-}
```
public void setMatrix00(float value)
```


Устанавливает элемент в 0‑й (ноль) строке и 0‑м столбце этой [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float | элемент в строке 0 (ноль) и столбце 0 этой [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix01() {#getMatrix01--}
```
public float getMatrix01()
```


Получает элемент в 0‑й (ноль) строке и первом столбце этой [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float — элемент в строке 0 (ноль) и первом столбце этой [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix01(float value) {#setMatrix01-float-}
```
public void setMatrix01(float value)
```


Устанавливает элемент в 0‑й (ноль) строке и первом столбце этой [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float | элемент в строке 0 (ноль) и первом столбце этой [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix02() {#getMatrix02--}
```
public float getMatrix02()
```


Получает элемент в 0‑й (ноль) строке и втором столбце этой [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - элемент в 0 (ноль) строке и втором столбце этой [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix02(float value) {#setMatrix02-float-}
```
public void setMatrix02(float value)
```


Устанавливает элемент в 0‑й (ноль) строке и втором столбце этой [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float | элемент в 0 (ноль) строке и втором столбце этой [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix03() {#getMatrix03--}
```
public float getMatrix03()
```


Получает элемент в 0‑й (ноль) строке и третьем столбце этой [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - элемент в 0 (ноль) строке и третьем столбце этой [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix03(float value) {#setMatrix03-float-}
```
public void setMatrix03(float value)
```


Устанавливает элемент в 0 (ноль) строке и третьем столбце этого [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float | элемент в 0 (ноль) строке и третьем столбце этой [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix04() {#getMatrix04--}
```
public float getMatrix04()
```


Получает элемент в 0 (ноль) строке и четвертом столбце этого [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - элемент в 0 (ноль) строке и четвертом столбце этой [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix04(float value) {#setMatrix04-float-}
```
public void setMatrix04(float value)
```


Устанавливает элемент в 0 (ноль) строке и четвертом столбце этого [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float | элемент в 0 (ноль) строке и четвертом столбце этой [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix10() {#getMatrix10--}
```
public float getMatrix10()
```


Получает элемент в первой строке и 0 (ноль) столбце этого [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - элемент в первой строке и 0 (ноль) столбце этой [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix10(float value) {#setMatrix10-float-}
```
public void setMatrix10(float value)
```


Устанавливает элемент в первой строке и 0 (ноль) столбце этого [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float | элемент в первой строке и 0 (ноль) столбце этой [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix11() {#getMatrix11--}
```
public float getMatrix11()
```


Получает элемент в первой строке и первом столбце этого [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - элемент в первой строке и первом столбце этой [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix11(float value) {#setMatrix11-float-}
```
public void setMatrix11(float value)
```


Устанавливает элемент в первой строке и первом столбце этого [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float | элемент в первой строке и первом столбце этой [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix12() {#getMatrix12--}
```
public float getMatrix12()
```


Получает элемент в первой строке и втором столбце этого [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - элемент в первой строке и втором столбце этой [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix12(float value) {#setMatrix12-float-}
```
public void setMatrix12(float value)
```


Устанавливает элемент в первой строке и втором столбце этого [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float | элемент в первой строке и втором столбце этой [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix13() {#getMatrix13--}
```
public float getMatrix13()
```


Получает элемент в первой строке и третьем столбце этого [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - элемент в первой строке и третьем столбце этой [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix13(float value) {#setMatrix13-float-}
```
public void setMatrix13(float value)
```


Устанавливает элемент в первой строке и третьем столбце этого [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float | элемент в первой строке и третьем столбце этой [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix14() {#getMatrix14--}
```
public float getMatrix14()
```


Получает элемент в первой строке и четвертом столбце этого [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - элемент в первой строке и четвертом столбце этой [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix14(float value) {#setMatrix14-float-}
```
public void setMatrix14(float value)
```


Устанавливает элемент в первой строке и четвертом столбце этого [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float | элемент в первой строке и четвертом столбце этой [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix20() {#getMatrix20--}
```
public float getMatrix20()
```


Получает элемент во второй строке и 0 (ноль) столбце этого [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - элемент во второй строке и 0 (ноль) столбце этой [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix20(float value) {#setMatrix20-float-}
```
public void setMatrix20(float value)
```


Устанавливает элемент во второй строке и 0 (ноль) столбце этого [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float | элемент во второй строке и 0 (ноль) столбце этой [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix21() {#getMatrix21--}
```
public float getMatrix21()
```


Получает элемент во второй строке и первом столбце этого [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - элемент во второй строке и первом столбце этой [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix21(float value) {#setMatrix21-float-}
```
public void setMatrix21(float value)
```


Устанавливает элемент во второй строке и первом столбце этого [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float | элемент во второй строке и первом столбце этой [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix22() {#getMatrix22--}
```
public float getMatrix22()
```


Получает элемент во второй строке и втором столбце этого [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - элемент во второй строке и втором столбце этой [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix22(float value) {#setMatrix22-float-}
```
public void setMatrix22(float value)
```


Устанавливает элемент во второй строке и втором столбце этого [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float | элемент во второй строке и втором столбце этой [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix23() {#getMatrix23--}
```
public float getMatrix23()
```


Получает элемент во второй строке и третьем столбце этого [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - элемент во второй строке и третьем столбце этой [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix23(float value) {#setMatrix23-float-}
```
public void setMatrix23(float value)
```


Устанавливает элемент во второй строке и третьем столбце этого [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float | элемент во второй строке и третьем столбце этой [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix24() {#getMatrix24--}
```
public float getMatrix24()
```


Получает элемент во второй строке и четвертом столбце этого [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - элемент во второй строке и четвертом столбце этой [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix24(float value) {#setMatrix24-float-}
```
public void setMatrix24(float value)
```


Устанавливает элемент во второй строке и четвертом столбце этого [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float | элемент во второй строке и четвертом столбце этого [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix30() {#getMatrix30--}
```
public float getMatrix30()
```


Получает элемент в третьей строке и 0 (ноль) столбце этого [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - элемент в третьей строке и 0 (ноль) столбце этого [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix30(float value) {#setMatrix30-float-}
```
public void setMatrix30(float value)
```


Устанавливает элемент в третьей строке и 0 (ноль) столбце этого [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float | элемент в третьей строке и 0 (ноль) столбце этого [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix31() {#getMatrix31--}
```
public float getMatrix31()
```


Получает элемент в третьей строке и первом столбце этой [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - элемент в третьей строке и первом столбце этого [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix31(float value) {#setMatrix31-float-}
```
public void setMatrix31(float value)
```


Устанавливает элемент в третьей строке и первом столбце этой [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float | элемент в третьей строке и первом столбце этого [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix32() {#getMatrix32--}
```
public float getMatrix32()
```


Получает элемент в третьей строке и втором столбце этой [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - элемент в третьей строке и втором столбце этого [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix32(float value) {#setMatrix32-float-}
```
public void setMatrix32(float value)
```


Устанавливает элемент в третьей строке и втором столбце этой [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float | элемент в третьей строке и втором столбце этого [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix33() {#getMatrix33--}
```
public float getMatrix33()
```


Получает элемент в третьей строке и третьем столбце этой [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - элемент в третьей строке и третьем столбце этого [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix33(float value) {#setMatrix33-float-}
```
public void setMatrix33(float value)
```


Устанавливает элемент в третьей строке и третьем столбце этой [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float | элемент в третьей строке и третьем столбце этого [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix34() {#getMatrix34--}
```
public float getMatrix34()
```


Получает элемент в третьей строке и четвертом столбце этой [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - элемент в третьей строке и четвертом столбце этого [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix34(float value) {#setMatrix34-float-}
```
public void setMatrix34(float value)
```


Устанавливает элемент в третьей строке и четвертом столбце этой [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float | элемент в третьей строке и четвертом столбце этого [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix40() {#getMatrix40--}
```
public float getMatrix40()
```


Получает элемент в четвертой строке и столбце 0 (ноль) этой [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - элемент в четвертой строке и 0 (ноль) столбце этого [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix40(float value) {#setMatrix40-float-}
```
public void setMatrix40(float value)
```


Устанавливает элемент в четвертой строке и столбце 0 (ноль) этой [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float | элемент в четвертой строке и 0 (ноль) столбце этого [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix41() {#getMatrix41--}
```
public float getMatrix41()
```


Получает элемент в четвертой строке и первом столбце этого `.ColorMatrix`.

**Returns:**
float - элемент в четвертой строке и первом столбце этого `.ColorMatrix`.
### setMatrix41(float value) {#setMatrix41-float-}
```
public void setMatrix41(float value)
```


Устанавливает элемент в четвертой строке и первом столбце этого `.ColorMatrix`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float | элемент в четвертой строке и первом столбце этого `.ColorMatrix`. |

### getMatrix42() {#getMatrix42--}
```
public float getMatrix42()
```


Получает элемент в четвертой строке и втором столбце этой [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - элемент в четвертой строке и втором столбце этого [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix42(float value) {#setMatrix42-float-}
```
public void setMatrix42(float value)
```


Устанавливает элемент в четвертой строке и втором столбце этой [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float | элемент в четвертой строке и втором столбце этого [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix43() {#getMatrix43--}
```
public float getMatrix43()
```


Получает элемент в четвертой строке и третьем столбце этой [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - элемент в четвертой строке и третьем столбце этого [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix43(float value) {#setMatrix43-float-}
```
public void setMatrix43(float value)
```


Устанавливает элемент в четвертой строке и третьем столбце этой [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float | элемент в четвертой строке и третьем столбце этого [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix44() {#getMatrix44--}
```
public float getMatrix44()
```


Получает элемент в четвертой строке и четвертом столбце этой [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - элемент в четвертой строке и четвертом столбце этого [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix44(float value) {#setMatrix44-float-}
```
public void setMatrix44(float value)
```


Устанавливает элемент в четвертой строке и четвертом столбце этой [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float | элемент в четвертой строке и четвертом столбце этого [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### get_Item(int row, int column) {#get-Item-int-int-}
```
public float get_Item(int row, int column)
```


Получает элемент в указанной строке и столбце в [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| строка | int | Строка элемента. |
| столбец | int | Столбец элемента. |

**Returns:**
float - Элемент в указанной строке и столбце.
### set_Item(int row, int column, float value) {#set-Item-int-int-float-}
```
public void set_Item(int row, int column, float value)
```


Устанавливает элемент в указанной строке и столбце в [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| строка | int | Строка элемента. |
| столбец | int | Столбец элемента. |
| value | float | элемент в указанной строке и столбце в [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

