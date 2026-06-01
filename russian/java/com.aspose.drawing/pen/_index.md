---
title: Pen
second_title: Справочник API Aspose.Drawing для Java
description: Определяет объект, используемый для рисования линий и кривых.
type: docs
weight: 34
url: /ru/java/com.aspose.drawing/pen/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public class Pen implements System.IDisposable
```

Определяет объект, используемый для рисования линий и кривых.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Pen(Color color)](#Pen-com.aspose.drawing.Color-) | Создаёт новый экземпляр класса [Pen](../../com.aspose.drawing/pen) с указанным `Color`([.getColor](../../null/\#getColor)/[.setColor(Color)](../../null/\#setColor-Color-)). |
| [Pen(Brush brush, float width)](#Pen-com.aspose.drawing.Brush-float-) | Создаёт новый экземпляр класса Pen с указанными Brush и Width. |
| [Pen(Brush brush)](#Pen-com.aspose.drawing.Brush-) | Создаёт новый экземпляр класса [Pen](../../com.aspose.drawing/pen) с указанным `Brush`([.getBrush](../../null/\#getBrush)/[.setBrush(Brush)](../../null/\#setBrush-Brush-)). |
| [Pen(Color color, float width)](#Pen-com.aspose.drawing.Color-float-) | Создаёт новый экземпляр класса Pen с указанными свойствами Color и Width. |
## Методы

| Метод | Описание |
| --- | --- |
| [getColor()](#getColor--) | Получает или задаёт цвет этого [Pen](../../com.aspose.drawing/pen). |
| [setColor(Color value)](#setColor-com.aspose.drawing.Color-) | Получает или задаёт цвет этого [Pen](../../com.aspose.drawing/pen). |
| [getBrush()](#getBrush--) | Получает или задаёт Brush, определяющий атрибуты этого [Pen](../../com.aspose.drawing/pen). |
| [setBrush(Brush value)](#setBrush-com.aspose.drawing.Brush-) | Получает или задаёт Brush, определяющий атрибуты этого [Pen](../../com.aspose.drawing/pen). |
| [getCompoundArray()](#getCompoundArray--) | Получает или задаёт массив значений, определяющих составное перо. |
| [setCompoundArray(float[] value)](#setCompoundArray-float---) | Получает или задаёт массив значений, определяющих составное перо. |
| [getWidth()](#getWidth--) | Получает или задаёт ширину этого Pen в единицах объекта Graphics, используемого для рисования. |
| [setWidth(float value)](#setWidth-float-) | Получает или задаёт ширину этого Pen в единицах объекта Graphics, используемого для рисования. |
| [getStartCap()](#getStartCap--) | Получает или задаёт стиль заглавия, используемый в начале линий, рисуемых этим Pen. |
| [setStartCap(int value)](#setStartCap-int-) | Получает или задаёт стиль заглавия, используемый в начале линий, рисуемых этим Pen. |
| [getEndCap()](#getEndCap--) | Получает или задаёт стиль заглавия, используемый в конце линий, рисуемых этим Pen. |
| [setEndCap(int value)](#setEndCap-int-) | Получает или задаёт стиль заглавия, используемый в конце линий, рисуемых этим Pen. |
| [getLineJoin()](#getLineJoin--) | Получает или задаёт стиль соединения концов двух последовательных линий, рисуемых этим Pen. |
| [setLineJoin(int value)](#setLineJoin-int-) | Получает или задаёт стиль соединения концов двух последовательных линий, рисуемых этим Pen. |
| [getMiterLimit()](#getMiterLimit--) | Получает или задаёт предел толщины соединения на скошенном угле. |
| [setMiterLimit(float value)](#setMiterLimit-float-) | Получает или задаёт предел толщины соединения на скошенном угле. |
| [getAlignment()](#getAlignment--) | Получает или задаёт выравнивание для этого [Pen](../../com.aspose.drawing/pen). |
| [setAlignment(int value)](#setAlignment-int-) | Получает или задаёт выравнивание для этого [Pen](../../com.aspose.drawing/pen). |
| [getTransform()](#getTransform--) | Получает или задаёт копию геометрического преобразования для этого [Pen](../../com.aspose.drawing/pen). |
| [setTransform(Matrix value)](#setTransform-com.aspose.drawing.drawing2d.Matrix-) | Получает или задаёт копию геометрического преобразования для этого [Pen](../../com.aspose.drawing/pen). |
| [getCustomStartCap()](#getCustomStartCap--) | Получает или задаёт пользовательский заглавный элемент, используемый в начале линий, рисуемых этим [Pen](../../com.aspose.drawing/pen). |
| [setCustomStartCap(CustomLineCap value)](#setCustomStartCap-com.aspose.drawing.drawing2d.CustomLineCap-) | Получает или задаёт пользовательский заглавный элемент, используемый в начале линий, рисуемых этим [Pen](../../com.aspose.drawing/pen). |
| [getCustomEndCap()](#getCustomEndCap--) | Получает или задаёт пользовательский заглавный элемент, используемый в конце линий, рисуемых этим [Pen](../../com.aspose.drawing/pen). |
| [setCustomEndCap(CustomLineCap value)](#setCustomEndCap-com.aspose.drawing.drawing2d.CustomLineCap-) | Получает или задаёт пользовательский заглавный элемент, используемый в конце линий, рисуемых этим [Pen](../../com.aspose.drawing/pen). |
| [getDashCap()](#getDashCap--) | Получает или задаёт стиль заглавия, используемый в конце тире, составляющих пунктирные линии, рисуемые этим [Pen](../../com.aspose.drawing/pen). |
| [setDashCap(int value)](#setDashCap-int-) | Получает или задаёт стиль заглавия, используемый в конце тире, составляющих пунктирные линии, рисуемые этим [Pen](../../com.aspose.drawing/pen). |
| [getDashOffset()](#getDashOffset--) | Получает или задаёт расстояние от начала линии до начала шаблона тире. |
| [setDashOffset(float value)](#setDashOffset-float-) | Получает или задаёт расстояние от начала линии до начала шаблона тире. |
| [getDashPattern()](#getDashPattern--) | Получает или задаёт массив пользовательских тире и пробелов. |
| [setDashPattern(float[] value)](#setDashPattern-float---) | Получает или задаёт массив пользовательских тире и пробелов. |
| [getDashStyle()](#getDashStyle--) | Получает или задаёт стиль, используемый для пунктирных линий, рисуемых этим [Pen](../../com.aspose.drawing/pen). |
| [setDashStyle(int value)](#setDashStyle-int-) | Получает или задаёт стиль, используемый для пунктирных линий, рисуемых этим [Pen](../../com.aspose.drawing/pen). |
| [getPenType()](#getPenType--) | Получает стиль линий, рисуемых этим Pen. |
| [dispose()](#dispose--) | Освобождает все ресурсы, используемые этим Pen. |
| [deepClone()](#deepClone--) | Создает точную копию этого [Pen](../../com.aspose.drawing/pen). |
| [setLineCap(int startCap, int endCap, int dashCap)](#setLineCap-int-int-int-) | Устанавливает значения, определяющие стиль концевика, используемого для завершения линий, нарисованных этим [Pen](../../com.aspose.drawing/pen). |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | Масштабирует локальное геометрическое преобразование на указанные коэффициенты. |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | Масштабирует локальное геометрическое преобразование на указанные коэффициенты в указанном порядке. |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | Перемещает локальное геометрическое преобразование на указанные размеры. |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | Перемещает локальное геометрическое преобразование на указанные размеры в указанном порядке. |
| [rotateTransform(float angle)](#rotateTransform-float-) | Вращает локальное геометрическое преобразование на указанный угол. |
| [rotateTransform(float angle, int order)](#rotateTransform-float-int-) | Вращает локальное геометрическое преобразование на указанный угол в указанном порядке. |
| [resetTransform()](#resetTransform--) | Сбрасывает матрицу геометрического преобразования для этого [Pen](../../com.aspose.drawing/pen) к единичной. |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-) | Умножает матрицу преобразования для этого [Pen](../../com.aspose.drawing/pen) на указанную [Matrix](../../com.aspose.drawing.drawing2d/matrix). |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-int-) | Умножает матрицу преобразования для этого [Pen](../../com.aspose.drawing/pen) на указанную [Matrix](../../com.aspose.drawing.drawing2d/matrix) в указанном порядке. |
### Pen(Color color) {#Pen-com.aspose.drawing.Color-}
```
public Pen(Color color)
```


Создаёт новый экземпляр класса [Pen](../../com.aspose.drawing/pen) с указанным `Color`([.getColor](../../null/\#getColor)/[.setColor(Color)](../../null/\#setColor-Color-)).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| color | [Color](../../com.aspose.drawing/color) | Объект `Color`([.getColor](../../null/\#getColor)/[.setColor(Color)](../../null/\#setColor-Color-)), определяющий свойства заливки этого [Pen](../../com.aspose.drawing/pen). |

### Pen(Brush brush, float width) {#Pen-com.aspose.drawing.Brush-float-}
```
public Pen(Brush brush, float width)
```


Создаёт новый экземпляр класса Pen с указанными Brush и Width.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.drawing/brush) | Кисть, определяющая характеристики этого Pen. |
| width | float | Ширина нового Pen. |

### Pen(Brush brush) {#Pen-com.aspose.drawing.Brush-}
```
public Pen(Brush brush)
```


Создаёт новый экземпляр класса [Pen](../../com.aspose.drawing/pen) с указанным `Brush`([.getBrush](../../null/\#getBrush)/[.setBrush(Brush)](../../null/\#setBrush-Brush-)).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.drawing/brush) | Объект `Brush`([.getBrush](../../null/\#getBrush)/[.setBrush(Brush)](../../null/\#setBrush-Brush-)), определяющий свойства заливки этого [Pen](../../com.aspose.drawing/pen). |

### Pen(Color color, float width) {#Pen-com.aspose.drawing.Color-float-}
```
public Pen(Color color, float width)
```


Создаёт новый экземпляр класса Pen с указанными свойствами Color и Width.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| color | [Color](../../com.aspose.drawing/color) | Структура Color, указывающая цвет этого Pen. |
| width | float | Значение, указывающее ширину этого Pen. |

### getColor() {#getColor--}
```
public final Color getColor()
```


Получает или задаёт цвет этого [Pen](../../com.aspose.drawing/pen).

Значение: Структура `Color`([.getColor](../../null/\#getColor)/[.setColor(Color)](../../null/\#setColor-Color-)), представляющая цвет этого [Pen](../../com.aspose.drawing/pen).

**Returns:**
[Color](../../com.aspose.drawing/color)
### setColor(Color value) {#setColor-com.aspose.drawing.Color-}
```
public final void setColor(Color value)
```


Получает или задаёт цвет этого [Pen](../../com.aspose.drawing/pen).

Значение: Структура `Color`([.getColor](../../null/\#getColor)/[.setColor(Color)](../../null/\#setColor-Color-)), представляющая цвет этого [Pen](../../com.aspose.drawing/pen).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Color](../../com.aspose.drawing/color) |  |

### getBrush() {#getBrush--}
```
public final Brush getBrush()
```


Получает или задаёт Brush, определяющий атрибуты этого [Pen](../../com.aspose.drawing/pen).

**Returns:**
[Brush](../../com.aspose.drawing/brush)
### setBrush(Brush value) {#setBrush-com.aspose.drawing.Brush-}
```
public final void setBrush(Brush value)
```


Получает или задаёт Brush, определяющий атрибуты этого [Pen](../../com.aspose.drawing/pen).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Brush](../../com.aspose.drawing/brush) |  |

### getCompoundArray() {#getCompoundArray--}
```
public final float[] getCompoundArray()
```


Получает или задает массив значений, определяющих составное Pen. Составное Pen рисует составную линию, состоящую из параллельных линий и промежутков.

**Returns:**
float[] — массив действительных чисел, задающий составной массив. Элементы массива должны быть упорядочены по возрастанию, не меньше 0 и не больше 1.
### setCompoundArray(float[] value) {#setCompoundArray-float---}
```
public final void setCompoundArray(float[] value)
```


Получает или задает массив значений, определяющих составное Pen. Составное Pen рисует составную линию, состоящую из параллельных линий и промежутков.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float[] |  |

### getWidth() {#getWidth--}
```
public final float getWidth()
```


Получает или задаёт ширину этого Pen в единицах объекта Graphics, используемого для рисования.

**Returns:**
float
### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```


Получает или задаёт ширину этого Pen в единицах объекта Graphics, используемого для рисования.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getStartCap() {#getStartCap--}
```
public final int getStartCap()
```


Получает или задаёт стиль заглавия, используемый в начале линий, рисуемых этим Pen.

**Returns:**
int
### setStartCap(int value) {#setStartCap-int-}
```
public final void setStartCap(int value)
```


Получает или задаёт стиль заглавия, используемый в начале линий, рисуемых этим Pen.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getEndCap() {#getEndCap--}
```
public final int getEndCap()
```


Получает или задаёт стиль заглавия, используемый в конце линий, рисуемых этим Pen.

**Returns:**
int
### setEndCap(int value) {#setEndCap-int-}
```
public final void setEndCap(int value)
```


Получает или задаёт стиль заглавия, используемый в конце линий, рисуемых этим Pen.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getLineJoin() {#getLineJoin--}
```
public final int getLineJoin()
```


Получает или задаёт стиль соединения концов двух последовательных линий, рисуемых этим Pen.

--------------------

В данный момент соединение Miter фактически работает как MiterClipped.

**Returns:**
int
### setLineJoin(int value) {#setLineJoin-int-}
```
public final void setLineJoin(int value)
```


Получает или задаёт стиль соединения концов двух последовательных линий, рисуемых этим Pen.

--------------------

В данный момент соединение Miter фактически работает как MiterClipped.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getMiterLimit() {#getMiterLimit--}
```
public final float getMiterLimit()
```


Получает или задаёт предел толщины соединения на скошенном угле.

**Returns:**
float
### setMiterLimit(float value) {#setMiterLimit-float-}
```
public final void setMiterLimit(float value)
```


Получает или задаёт предел толщины соединения на скошенном угле.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getAlignment() {#getAlignment--}
```
public final int getAlignment()
```


Получает или задаёт выравнивание для этого [Pen](../../com.aspose.drawing/pen).

**Returns:**
int — объект [PenAlignment](../../com.aspose.drawing.drawing2d/penalignment), представляющий выравнивание для этого [Pen](../../com.aspose.drawing/pen).
### setAlignment(int value) {#setAlignment-int-}
```
public final void setAlignment(int value)
```


Получает или задаёт выравнивание для этого [Pen](../../com.aspose.drawing/pen).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getTransform() {#getTransform--}
```
public final Matrix getTransform()
```


Получает или задаёт копию геометрического преобразования для этого [Pen](../../com.aspose.drawing/pen).

Значение: Копия [Matrix](../../com.aspose.drawing.drawing2d/matrix), представляющая геометрическое преобразование для этого [Pen](../../com.aspose.drawing/pen).

**Returns:**
[Matrix](../../com.aspose.drawing.drawing2d/matrix)
### setTransform(Matrix value) {#setTransform-com.aspose.drawing.drawing2d.Matrix-}
```
public final void setTransform(Matrix value)
```


Получает или задаёт копию геометрического преобразования для этого [Pen](../../com.aspose.drawing/pen).

Значение: Копия [Matrix](../../com.aspose.drawing.drawing2d/matrix), представляющая геометрическое преобразование для этого [Pen](../../com.aspose.drawing/pen).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.drawing.drawing2d/matrix) |  |

### getCustomStartCap() {#getCustomStartCap--}
```
public final CustomLineCap getCustomStartCap()
```


Получает или задаёт пользовательский заглавный элемент, используемый в начале линий, рисуемых этим [Pen](../../com.aspose.drawing/pen).

**Returns:**
[CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) - A [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) that represents the cap used at the beginning of lines drawn with this [Pen](../../com.aspose.drawing/pen).
### setCustomStartCap(CustomLineCap value) {#setCustomStartCap-com.aspose.drawing.drawing2d.CustomLineCap-}
```
public final void setCustomStartCap(CustomLineCap value)
```


Получает или задаёт пользовательский заглавный элемент, используемый в начале линий, рисуемых этим [Pen](../../com.aspose.drawing/pen).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) |  |

### getCustomEndCap() {#getCustomEndCap--}
```
public final CustomLineCap getCustomEndCap()
```


Получает или задаёт пользовательский заглавный элемент, используемый в конце линий, рисуемых этим [Pen](../../com.aspose.drawing/pen).

**Returns:**
[CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) - A [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) that represents the cap used at the end of lines drawn with this [Pen](../../com.aspose.drawing/pen).
### setCustomEndCap(CustomLineCap value) {#setCustomEndCap-com.aspose.drawing.drawing2d.CustomLineCap-}
```
public final void setCustomEndCap(CustomLineCap value)
```


Получает или задаёт пользовательский заглавный элемент, используемый в конце линий, рисуемых этим [Pen](../../com.aspose.drawing/pen).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) |  |

### getDashCap() {#getDashCap--}
```
public final int getDashCap()
```


Получает или задаёт стиль заглавия, используемый в конце тире, составляющих пунктирные линии, рисуемые этим [Pen](../../com.aspose.drawing/pen).

**Returns:**
int — одно из значений `DashCap`([.getDashCap](../../null/\#getDashCap)/[.setDashCap(int)](../../null/\#setDashCap-int-)), представляющее стиль концевика, используемого в начале и в конце штрихов, составляющих пунктирные линии, нарисованные этим [Pen](../../com.aspose.drawing/pen).
### setDashCap(int value) {#setDashCap-int-}
```
public final void setDashCap(int value)
```


Получает или задаёт стиль заглавия, используемый в конце тире, составляющих пунктирные линии, рисуемые этим [Pen](../../com.aspose.drawing/pen).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getDashOffset() {#getDashOffset--}
```
public final float getDashOffset()
```


Получает или задаёт расстояние от начала линии до начала шаблона тире.

**Returns:**
float — расстояние от начала линии до начала шаблона штриха.
### setDashOffset(float value) {#setDashOffset-float-}
```
public final void setDashOffset(float value)
```


Получает или задаёт расстояние от начала линии до начала шаблона тире.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getDashPattern() {#getDashPattern--}
```
public final float[] getDashPattern()
```


Получает или задаёт массив пользовательских тире и пробелов.

**Returns:**
float[] — массив действительных чисел, задающий длины чередующихся штрихов и пробелов в пунктирных линиях.
### setDashPattern(float[] value) {#setDashPattern-float---}
```
public final void setDashPattern(float[] value)
```


Получает или задаёт массив пользовательских тире и пробелов.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float[] |  |

### getDashStyle() {#getDashStyle--}
```
public final int getDashStyle()
```


Получает или задаёт стиль, используемый для пунктирных линий, рисуемых этим [Pen](../../com.aspose.drawing/pen).

**Returns:**
int - `DashStyle`([.getDashStyle](../../null/\#getDashStyle)/[.setDashStyle(int)](../../null/\#setDashStyle-int-)) представляющий стиль, используемый для пунктирных линий, рисуемых этим [Pen](../../com.aspose.drawing/pen).
### setDashStyle(int value) {#setDashStyle-int-}
```
public final void setDashStyle(int value)
```


Получает или задаёт стиль, используемый для пунктирных линий, рисуемых этим [Pen](../../com.aspose.drawing/pen).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getPenType() {#getPenType--}
```
public final int getPenType()
```


Получает стиль линий, рисуемых этим Pen.

Value: `PenType`([.getPenType](../../null/\#getPenType)) перечисление, определяющее стиль линий, рисуемых этим [Pen](../../com.aspose.drawing/pen).

**Returns:**
int
### dispose() {#dispose--}
```
public final void dispose()
```


Освобождает все ресурсы, используемые этим Pen.

--------------------

Этот метод фактически ничего не делает. Он нужен только для совместимости с API System.Drawing.

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Создает точную копию этого [Pen](../../com.aspose.drawing/pen).

**Returns:**
java.lang.Object - Объект, который можно привести к [Pen](../../com.aspose.drawing/pen).
### setLineCap(int startCap, int endCap, int dashCap) {#setLineCap-int-int-int-}
```
public final void setLineCap(int startCap, int endCap, int dashCap)
```


Устанавливает значения, определяющие стиль концевика, используемого для завершения линий, нарисованных этим [Pen](../../com.aspose.drawing/pen).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| startCap | int | A [LineCap](../../com.aspose.drawing.drawing2d/linecap) представляющий стиль заголовка, используемый в начале линий, рисуемых этим [Pen](../../com.aspose.drawing/pen). |
| endCap | int | A [LineCap](../../com.aspose.drawing.drawing2d/linecap) представляющий стиль заголовка, используемый в конце линий, рисуемых этим [Pen](../../com.aspose.drawing/pen). |
| dashCap | int | A [LineCap](../../com.aspose.drawing.drawing2d/linecap) представляющий стиль заголовка, используемый в начале или в конце пунктирных линий, рисуемых этим [Pen](../../com.aspose.drawing/pen). |

### scaleTransform(float sx, float sy) {#scaleTransform-float-float-}
```
public final void scaleTransform(float sx, float sy)
```


Масштабирует локальное геометрическое преобразование на указанные коэффициенты. Этот метод предварительно добавляет матрицу масштабирования к преобразованию.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| sx | float | Коэффициент масштабирования преобразования по оси X. |
| sy | float | Коэффициент масштабирования преобразования по оси Y. |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public final void scaleTransform(float sx, float sy, int order)
```


Масштабирует локальное геометрическое преобразование на указанные коэффициенты в указанном порядке.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| sx | float | Коэффициент масштабирования преобразования по оси X. |
| sy | float | Коэффициент масштабирования преобразования по оси Y. |
| order | int | Объект [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder), указывающий, добавлять ли матрицу масштабирования в конец или в начало. |

### translateTransform(float dx, float dy) {#translateTransform-float-float-}
```
public final void translateTransform(float dx, float dy)
```


Перемещает локальное геометрическое преобразование на указанные размеры. Этот метод предварительно добавляет трансляцию к преобразованию.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| dx | float | Значение трансляции по оси x. |
| dy | float | Значение трансляции по оси y. |

### translateTransform(float dx, float dy, int order) {#translateTransform-float-float-int-}
```
public final void translateTransform(float dx, float dy, int order)
```


Перемещает локальное геометрическое преобразование на указанные размеры в указанном порядке.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| dx | float | Значение трансляции по оси x. |
| dy | float | Значение трансляции по оси y. |
| порядок | int | Порядок (prepend или append), в котором применяется трансляция. |

### rotateTransform(float angle) {#rotateTransform-float-}
```
public final void rotateTransform(float angle)
```


Вращает локальное геометрическое преобразование на указанный угол. Этот метод предварительно добавляет вращение к преобразованию.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| угол | float | Угол вращения. |

### rotateTransform(float angle, int order) {#rotateTransform-float-int-}
```
public final void rotateTransform(float angle, int order)
```


Вращает локальное геометрическое преобразование на указанный угол в указанном порядке.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| угол | float | Угол вращения. |
| order | int | Объект [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder), указывающий, добавлять ли матрицу вращения в конец или в начало. |

### resetTransform() {#resetTransform--}
```
public final void resetTransform()
```


Сбрасывает матрицу геометрического преобразования для этого [Pen](../../com.aspose.drawing/pen) к единичной.

### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-}
```
public final void multiplyTransform(Matrix matrix)
```


Умножает матрицу преобразования для этого [Pen](../../com.aspose.drawing/pen) на указанную [Matrix](../../com.aspose.drawing.drawing2d/matrix).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | [Matrix](../../com.aspose.drawing.drawing2d/matrix) объект, которым умножается матрица преобразования. |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-int-}
```
public final void multiplyTransform(Matrix matrix, int order)
```


Умножает матрицу преобразования для этого [Pen](../../com.aspose.drawing/pen) на указанную [Matrix](../../com.aspose.drawing.drawing2d/matrix) в указанном порядке.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | java.awt.geom.AffineTransform, которым умножается матрица преобразования. |
| порядок | int | Порядок выполнения операции умножения. |

