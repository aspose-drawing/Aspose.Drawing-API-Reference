---
title: CustomLineCap
second_title: Справочник API Aspose.Drawing для Java
description: Инкапсулирует пользовательскую определённую заглушку линии.
type: docs
weight: 17
url: /ru/java/com.aspose.drawing.drawing2d/customlinecap/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public class CustomLineCap implements System.IDisposable
```

Инкапсулирует пользовательскую определённую заглушку линии.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath)](#CustomLineCap-com.aspose.drawing.drawing2d.GraphicsPath-com.aspose.drawing.drawing2d.GraphicsPath-) | Инициализирует новый экземпляр класса [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) с указанным контуром и заливкой. |
| [CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap)](#CustomLineCap-com.aspose.drawing.drawing2d.GraphicsPath-com.aspose.drawing.drawing2d.GraphicsPath-int-) | Инициализирует новый экземпляр класса [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) из указанного существующего перечисления [LineCap](../../com.aspose.drawing.drawing2d/linecap) с указанным контуром и заливкой. |
| [CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap, float baseInset)](#CustomLineCap-com.aspose.drawing.drawing2d.GraphicsPath-com.aspose.drawing.drawing2d.GraphicsPath-int-float-) | Инициализирует новый экземпляр класса [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) из указанного существующего перечисления [LineCap](../../com.aspose.drawing.drawing2d/linecap) с указанным контуром, заливкой и отступом. |
## Методы

| Метод | Описание |
| --- | --- |
| [getStrokeJoin()](#getStrokeJoin--) | Получает или задает перечисление [LineJoin](../../com.aspose.drawing.drawing2d/linejoin), определяющее, как соединяются линии, составляющие объект [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap). |
| [setStrokeJoin(int value)](#setStrokeJoin-int-) | Получает или задает перечисление [LineJoin](../../com.aspose.drawing.drawing2d/linejoin), определяющее, как соединяются линии, составляющие объект [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap). |
| [getBaseCap()](#getBaseCap--) | Получает или задает перечисление [LineCap](../../com.aspose.drawing.drawing2d/linecap), на котором основан этот [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap). |
| [setBaseCap(int value)](#setBaseCap-int-) | Получает или задает перечисление [LineCap](../../com.aspose.drawing.drawing2d/linecap), на котором основан этот [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap). |
| [getBaseInset()](#getBaseInset--) | Получает или задает расстояние между наконечником и линией. |
| [setBaseInset(float value)](#setBaseInset-float-) | Получает или задает расстояние между наконечником и линией. |
| [getWidthScale()](#getWidthScale--) | Получает или задает величину, на которую следует масштабировать объект класса [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) относительно ширины объекта [Pen](../../com.aspose.drawing/pen). |
| [setWidthScale(float value)](#setWidthScale-float-) | Получает или задает величину, на которую следует масштабировать объект класса [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) относительно ширины объекта [Pen](../../com.aspose.drawing/pen). |
| [dispose()](#dispose--) | Освобождает все ресурсы, используемые этим объектом [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap). |
| [deepClone()](#deepClone--) | Создаёт точную копию этого [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap). |
| [setStrokeCaps(int startCap, int endCap)](#setStrokeCaps-int-int-) | Устанавливает заглушки, используемые для начала и окончания линий, составляющих эту пользовательскую заглушку. |
| [getStrokeCaps(int[] startCap, int[] endCap)](#getStrokeCaps-int---int---) | Получает заглушки, используемые для начала и окончания линий, составляющих эту пользовательскую заглушку. |
| [getFillPath()](#getFillPath--) |  |
| [getStrokePath()](#getStrokePath--) | Получает объект, определяющий контур пользовательской заглушки. |
### CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath) {#CustomLineCap-com.aspose.drawing.drawing2d.GraphicsPath-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath)
```


Инициализирует новый экземпляр класса [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) с указанным контуром и заливкой.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fillPath | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | Объект [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath), определяющий заливку пользовательской заглушки. |
| strokePath | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | Объект [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath), определяющий контур пользовательской заглушки. |

### CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap) {#CustomLineCap-com.aspose.drawing.drawing2d.GraphicsPath-com.aspose.drawing.drawing2d.GraphicsPath-int-}
```
public CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap)
```


Инициализирует новый экземпляр класса [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) из указанного существующего перечисления [LineCap](../../com.aspose.drawing.drawing2d/linecap) с указанным контуром и заливкой.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fillPath | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | Объект [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath), определяющий заливку пользовательской заглушки. |
| strokePath | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | Объект [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath), определяющий контур пользовательской заглушки. |
| baseCap | int | Заглушка линии, из которой создаётся пользовательская заглушка. |

### CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap, float baseInset) {#CustomLineCap-com.aspose.drawing.drawing2d.GraphicsPath-com.aspose.drawing.drawing2d.GraphicsPath-int-float-}
```
public CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap, float baseInset)
```


Инициализирует новый экземпляр класса [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) из указанного существующего перечисления [LineCap](../../com.aspose.drawing.drawing2d/linecap) с указанным контуром, заливкой и отступом.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fillPath | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | Объект [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath), определяющий заливку пользовательской заглушки. |
| strokePath | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | Объект [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath), определяющий контур пользовательской заглушки. |
| baseCap | int | Заглушка линии, из которой создаётся пользовательская заглушка. |
| baseInset | float | Расстояние между заглушкой и линией. |

### getStrokeJoin() {#getStrokeJoin--}
```
public final int getStrokeJoin()
```


Получает или задает перечисление [LineJoin](../../com.aspose.drawing.drawing2d/linejoin), определяющее, как соединяются линии, составляющие объект [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap).

**Returns:**
int
### setStrokeJoin(int value) {#setStrokeJoin-int-}
```
public final void setStrokeJoin(int value)
```


Получает или задает перечисление [LineJoin](../../com.aspose.drawing.drawing2d/linejoin), определяющее, как соединяются линии, составляющие объект [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getBaseCap() {#getBaseCap--}
```
public final int getBaseCap()
```


Получает или задает перечисление [LineCap](../../com.aspose.drawing.drawing2d/linecap), на котором основан этот [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap).

**Returns:**
int
### setBaseCap(int value) {#setBaseCap-int-}
```
public final void setBaseCap(int value)
```


Получает или задает перечисление [LineCap](../../com.aspose.drawing.drawing2d/linecap), на котором основан этот [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getBaseInset() {#getBaseInset--}
```
public final float getBaseInset()
```


Получает или задает расстояние между наконечником и линией.

**Returns:**
float
### setBaseInset(float value) {#setBaseInset-float-}
```
public final void setBaseInset(float value)
```


Получает или задает расстояние между наконечником и линией.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getWidthScale() {#getWidthScale--}
```
public final float getWidthScale()
```


Получает или задает величину, на которую следует масштабировать объект класса [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) относительно ширины объекта [Pen](../../com.aspose.drawing/pen).

**Returns:**
float
### setWidthScale(float value) {#setWidthScale-float-}
```
public final void setWidthScale(float value)
```


Получает или задает величину, на которую следует масштабировать объект класса [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) относительно ширины объекта [Pen](../../com.aspose.drawing/pen).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### dispose() {#dispose--}
```
public final void dispose()
```


Освобождает все ресурсы, используемые этим объектом [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap).

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Создаёт точную копию этого [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap).

**Returns:**
java.lang.Object - объект [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap), создаваемый этим методом, приведённый к типу object.
### setStrokeCaps(int startCap, int endCap) {#setStrokeCaps-int-int-}
```
public final void setStrokeCaps(int startCap, int endCap)
```


Устанавливает заглушки, используемые для начала и окончания линий, составляющих эту пользовательскую заглушку.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| startCap | int | Перечисление [LineCap](../../com.aspose.drawing.drawing2d/linecap), используемое в начале линии внутри этой заглушки. |
| endCap | int | Перечисление [LineCap](../../com.aspose.drawing.drawing2d/linecap), используемое в конце линии внутри этой заглушки. |

### getStrokeCaps(int[] startCap, int[] endCap) {#getStrokeCaps-int---int---}
```
public final void getStrokeCaps(int[] startCap, int[] endCap)
```


Получает заглушки, используемые для начала и окончания линий, составляющих эту пользовательскую заглушку.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| startCap | int[] | Перечисление [LineCap](../../com.aspose.drawing.drawing2d/linecap), используемое в начале линии внутри этой заглушки. |
| endCap | int[] | Перечисление [LineCap](../../com.aspose.drawing.drawing2d/linecap), используемое в конце линии внутри этой заглушки. |

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


Получает объект, определяющий контур пользовательской заглушки.

**Returns:**
[GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) - The object that defines the outline of the custom cap.
