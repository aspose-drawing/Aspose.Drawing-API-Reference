---
title: RectangleF
second_title: Справочник API Aspose.Drawing для Java
description: Хранит набор из четырёх чисел с плавающей запятой, представляющих положение и размер прямоугольника.
type: docs
weight: 39
url: /ru/java/com.aspose.drawing/rectanglef/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable, java.lang.Cloneable
```
public class RectangleF extends Struct<RectangleF> implements System.IEquatable<RectangleF>, Cloneable
```

Сохраняет набор из четырёх чисел с плавающей точкой, представляющих положение и размер прямоугольника. Для более продвинутых функций областей используйте объект Region.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [RectangleF()](#RectangleF--) |  |
| [RectangleF(PointF location, SizeF size)](#RectangleF-com.aspose.drawing.PointF-com.aspose.drawing.SizeF-) | Инициализирует новый экземпляр структуры RectangleF с указанным положением и размером. |
| [RectangleF(float x, float y, float width, float height)](#RectangleF-float-float-float-float-) | Инициализирует новый экземпляр структуры RectangleF с указанным положением и размером. |
## Методы

| Метод | Описание |
| --- | --- |
| [fromPoints(PointF point1, PointF point2)](#fromPoints-com.aspose.drawing.PointF-com.aspose.drawing.PointF-) | Создаёт новый прямоугольник по двум точкам. |
| [to_RectangleF(Rectangle r)](#to-RectangleF-com.aspose.drawing.Rectangle-) | Преобразует указанную структуру Rectangle в структуру RectangleF. |
| [op_Equality(RectangleF left, RectangleF right)](#op-Equality-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-) | Проверяет, имеют ли две структуры [RectangleF](../../com.aspose.drawing/rectanglef) одинаковое положение и размер. |
| [op_Inequality(RectangleF left, RectangleF right)](#op-Inequality-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-) | Проверяет, отличаются ли две структуры [RectangleF](../../com.aspose.drawing/rectanglef) по положению или размеру. |
| [fromLTRB(float left, float top, float right, float bottom)](#fromLTRB-float-float-float-float-) | Создаёт структуру RectangleF с верхним левым и нижним правым углом в указанных позициях. |
| [inflate(RectangleF rect, float x, float y)](#inflate-com.aspose.drawing.RectangleF-float-float-) | Создаёт и возвращает расширенную копию указанной структуры [RectangleF](../../com.aspose.drawing/rectanglef). |
| [intersect(RectangleF a, RectangleF b)](#intersect-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-) | Возвращает структуру [RectangleF](../../com.aspose.drawing/rectanglef), представляющую пересечение двух прямоугольников. |
| [union(RectangleF a, RectangleF b)](#union-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-) | Создаёт наименьший возможный третий прямоугольник, который может содержать оба прямоугольника, образующие объединение. |
| [isEquals(RectangleF obj1, RectangleF obj2)](#isEquals-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-) |  |
| [getEmpty()](#getEmpty--) |  |
| [isEmpty()](#isEmpty--) | Возвращает значение, указывающее, имеет ли свойство `RectangleF.Width` или `RectangleF.Height` этой [RectangleF](../../aspose.drawing/rectanglef) значение ноль. |
| [getX()](#getX--) | Возвращает координату x верхнего левого угла этой структуры RectangleF. |
| [setX(float value)](#setX-float-) | Устанавливает координату x верхнего левого угла этой структуры RectangleF. |
| [getY()](#getY--) | Возвращает координату x верхнего левого угла этой структуры RectangleF. |
| [setY(float value)](#setY-float-) | Устанавливает координату x верхнего левого угла этой структуры RectangleF. |
| [getLocation()](#getLocation--) | Возвращает координаты верхнего левого угла этой структуры [RectangleF](../../com.aspose.drawing/rectanglef). |
| [setLocation(PointF value)](#setLocation-com.aspose.drawing.PointF-) | Устанавливает координаты верхнего левого угла этой структуры [RectangleF](../../com.aspose.drawing/rectanglef). |
| [getWidth()](#getWidth--) | Возвращает ширину этой структуры RectangleF. |
| [setWidth(float value)](#setWidth-float-) | Устанавливает ширину этой структуры RectangleF. |
| [getHeight()](#getHeight--) | Возвращает высоту этой структуры RectangleF. |
| [setHeight(float value)](#setHeight-float-) | Устанавливает высоту этой структуры RectangleF. |
| [getSize()](#getSize--) | Возвращает размер этой [RectangleF](../../com.aspose.drawing/rectanglef). |
| [setSize(SizeF value)](#setSize-com.aspose.drawing.SizeF-) | Устанавливает размер этой [RectangleF](../../com.aspose.drawing/rectanglef). |
| [getLeft()](#getLeft--) | Возвращает координату x левой грани этой структуры RectangleF. |
| [getTop()](#getTop--) | Возвращает координату y верхней грани этой структуры RectangleF. |
| [getRight()](#getRight--) | Возвращает координату x, являющуюся суммой X и Width этой структуры RectangleF. |
| [getBottom()](#getBottom--) | Возвращает координату y, являющуюся суммой Y и Height этой структуры RectangleF. |
| [toString()](#toString--) |  |
| [inflate(float x, float y)](#inflate-float-float-) | Увеличивает эту структуру [RectangleF](../../com.aspose.drawing/rectanglef) на указанную величину. |
| [inflate(SizeF size)](#inflate-com.aspose.drawing.SizeF-) | Увеличивает этот [RectangleF](../../com.aspose.drawing/rectanglef) на указанную величину. |
| [intersect(RectangleF rect)](#intersect-com.aspose.drawing.RectangleF-) | Заменяет эту структуру [RectangleF](../../com.aspose.drawing/rectanglef) на пересечение её с указанной структурой [RectangleF](../../com.aspose.drawing/rectanglef). |
| [intersectsWith(RectangleF rect)](#intersectsWith-com.aspose.drawing.RectangleF-) | Определяет, пересекается ли этот прямоугольник с `rect`. |
| [offset(PointF pos)](#offset-com.aspose.drawing.PointF-) | Корректирует положение этого прямоугольника на указанную величину. |
| [offset(float x, float y)](#offset-float-float-) | Корректирует положение этого прямоугольника на указанную величину. |
| [contains(float x, float y)](#contains-float-float-) | Определяет, содержится ли указанная точка внутри этой структуры [RectangleF](../../com.aspose.drawing/rectanglef). |
| [contains(PointF pt)](#contains-com.aspose.drawing.PointF-) | Определяет, содержится ли указанная точка внутри этой структуры [RectangleF](../../com.aspose.drawing/rectanglef). |
| [contains(RectangleF rect)](#contains-com.aspose.drawing.RectangleF-) | Определяет, полностью ли прямоугольная область, представленная `rect`, содержится внутри этой структуры [RectangleF](../../com.aspose.drawing/rectanglef). |
| [equals(Object obj)](#equals-java.lang.Object-) | Определяет, равен ли указанный объект этому экземпляру. |
| [hashCode()](#hashCode--) | Возвращает хеш-код для этого экземпляра. |
| [equals(RectangleF other)](#equals-com.aspose.drawing.RectangleF-) | Проверяет, имеет ли другая структура [RectangleF](../../com.aspose.drawing/rectanglef) то же расположение и размер, что и эта структура [RectangleF](../../com.aspose.drawing/rectanglef). |
| [CloneTo(RectangleF that)](#CloneTo-com.aspose.drawing.RectangleF-) |  |
| [Clone()](#Clone--) |  |
| [clone()](#clone--) |  |
### RectangleF() {#RectangleF--}
```
public RectangleF()
```


### RectangleF(PointF location, SizeF size) {#RectangleF-com.aspose.drawing.PointF-com.aspose.drawing.SizeF-}
```
public RectangleF(PointF location, SizeF size)
```


Инициализирует новый экземпляр структуры RectangleF с указанным положением и размером.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| location | [PointF](../../com.aspose.drawing/pointf) | Точка PointF, представляющая верхний левый угол прямоугольной области. |
| size | [SizeF](../../com.aspose.drawing/sizef) | Размер SizeF, представляющий ширину и высоту прямоугольной области. |

### RectangleF(float x, float y, float width, float height) {#RectangleF-float-float-float-float-}
```
public RectangleF(float x, float y, float width, float height)
```


Инициализирует новый экземпляр структуры RectangleF с указанным положением и размером.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | float | Координата x верхнего левого угла прямоугольника. |
| y | float | Y‑координата верхнего левого угла прямоугольника. |
| width | float | Ширина прямоугольника. |
| height | float | Высота прямоугольника. |

### fromPoints(PointF point1, PointF point2) {#fromPoints-com.aspose.drawing.PointF-com.aspose.drawing.PointF-}
```
public static RectangleF fromPoints(PointF point1, PointF point2)
```


Создаёт новый прямоугольник из двух точек. Созданный прямоугольник будет нормализован так, чтобы (left,top) были меньше, чем (right,bottom).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| point1 | [PointF](../../com.aspose.drawing/pointf) | Первая точка. |
| point2 | [PointF](../../com.aspose.drawing/pointf) | Вторая точка. |

**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef) - A newly created rectangle.
### to_RectangleF(Rectangle r) {#to-RectangleF-com.aspose.drawing.Rectangle-}
```
public static RectangleF to_RectangleF(Rectangle r)
```


Преобразует указанную структуру Rectangle в структуру RectangleF.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| r | [Rectangle](../../com.aspose.drawing/rectangle) | Структура Rectangle для преобразования. |

**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef) - The RectangleF structure that is converted from the specified Rectangle structure.
### op_Equality(RectangleF left, RectangleF right) {#op-Equality-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-}
```
public static boolean op_Equality(RectangleF left, RectangleF right)
```


Проверяет, имеют ли две структуры [RectangleF](../../com.aspose.drawing/rectanglef) одинаковое положение и размер.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| left | [RectangleF](../../com.aspose.drawing/rectanglef) | Структура [RectangleF](../../com.aspose.drawing/rectanglef), находящаяся слева от оператора равенства. |
| right | [RectangleF](../../com.aspose.drawing/rectanglef) | Структура [RectangleF](../../com.aspose.drawing/rectanglef), находящаяся справа от оператора равенства. |

**Returns:**
boolean — Этот оператор возвращает true, если у двух указанных структур [RectangleF](../../com.aspose.drawing/rectanglef) одинаковые свойства `RectangleF.X`, `RectangleF.Y`, `RectangleF.Width` и `RectangleF.Height`.
### op_Inequality(RectangleF left, RectangleF right) {#op-Inequality-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-}
```
public static boolean op_Inequality(RectangleF left, RectangleF right)
```


Проверяет, отличаются ли две структуры [RectangleF](../../com.aspose.drawing/rectanglef) по положению или размеру.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| left | [RectangleF](../../com.aspose.drawing/rectanglef) | Структура [RectangleF](../../com.aspose.drawing/rectanglef), находящаяся слева от оператора неравенства. |
| right | [RectangleF](../../com.aspose.drawing/rectanglef) | Структура [RectangleF](../../com.aspose.drawing/rectanglef), находящаяся справа от оператора неравенства. |

**Returns:**
boolean — Этот оператор возвращает true, если любое из свойств `RectangleF.X`, `RectangleF.Y`, `RectangleF.Width` или `RectangleF.Height` у двух структур [Rectangle](../../com.aspose.drawing/rectangle) не совпадает; в противном случае — false.
### fromLTRB(float left, float top, float right, float bottom) {#fromLTRB-float-float-float-float-}
```
public static RectangleF fromLTRB(float left, float top, float right, float bottom)
```


Создаёт структуру RectangleF с верхним левым и нижним правым углом в указанных позициях.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| left | float | X‑координата верхнего левого угла прямоугольной области. |
| top | float | Y‑координата верхнего левого угла прямоугольной области. |
| right | float | X‑координата нижнего правого угла прямоугольной области. |
| bottom | float | Y‑координата нижнего правого угла прямоугольной области. |

**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef) - The new RectangleF that this method creates.
### inflate(RectangleF rect, float x, float y) {#inflate-com.aspose.drawing.RectangleF-float-float-}
```
public static RectangleF inflate(RectangleF rect, float x, float y)
```


Создаёт и возвращает увеличенную копию указанной структуры [RectangleF](../../com.aspose.drawing/rectanglef). Копия увеличивается на заданную величину. Исходный прямоугольник остаётся неизменным.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | Структура [RectangleF](../../com.aspose.drawing/rectanglef) для копирования. Этот прямоугольник не изменяется. |
| x | float | Величина, на которую копия прямоугольника будет увеличена по горизонтали. |
| y | float | Величина, на которую нужно расширить копию прямоугольника по вертикали. |

**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef) - The inflated [RectangleF](../../com.aspose.drawing/rectanglef).
### intersect(RectangleF a, RectangleF b) {#intersect-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-}
```
public static RectangleF intersect(RectangleF a, RectangleF b)
```


Возвращает структуру [RectangleF](../../com.aspose.drawing/rectanglef), представляющую пересечение двух прямоугольников. Если пересечения нет, возвращается пустой [RectangleF](../../com.aspose.drawing/rectanglef).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| a | [RectangleF](../../com.aspose.drawing/rectanglef) | Первый прямоугольник для пересечения. |
| b | [RectangleF](../../com.aspose.drawing/rectanglef) | Второй прямоугольник для пересечения. |

**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef) - A third [RectangleF](../../com.aspose.drawing/rectanglef) structure the size of which represents the overlapped area of the two specified rectangles.
### union(RectangleF a, RectangleF b) {#union-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-}
```
public static RectangleF union(RectangleF a, RectangleF b)
```


Создаёт наименьший возможный третий прямоугольник, который может содержать оба прямоугольника, образующие объединение.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| a | [RectangleF](../../com.aspose.drawing/rectanglef) | Первый прямоугольник для объединения. |
| b | [RectangleF](../../com.aspose.drawing/rectanglef) | Второй прямоугольник для объединения. |

**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef) - A third [RectangleF](../../com.aspose.drawing/rectanglef) structure that contains both of the two rectangles that form the union.
### isEquals(RectangleF obj1, RectangleF obj2) {#isEquals-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-}
```
public static boolean isEquals(RectangleF obj1, RectangleF obj2)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj1 | [RectangleF](../../com.aspose.drawing/rectanglef) |  |
| obj2 | [RectangleF](../../com.aspose.drawing/rectanglef) |  |

**Returns:**
boolean
### getEmpty() {#getEmpty--}
```
public static RectangleF getEmpty()
```




**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef)
### isEmpty() {#isEmpty--}
```
public final boolean isEmpty()
```


Возвращает значение, указывающее, имеет ли свойство `RectangleF.Width` или `RectangleF.Height` этой [RectangleF](../../aspose.drawing/rectanglef) значение ноль.

**Returns:**
boolean - Это свойство возвращает true, если свойство `RectangleF.Width` или `P:RectangleF.Height` этой [RectangleF](../../com.aspose.drawing/rectanglef) равно нулю; в противном случае — false.
### getX() {#getX--}
```
public final float getX()
```


Возвращает координату x верхнего левого угла этой структуры RectangleF.

**Returns:**
float - координата x верхнего левого угла этой структуры RectangleF.
### setX(float value) {#setX-float-}
```
public final void setX(float value)
```


Устанавливает координату x верхнего левого угла этой структуры RectangleF.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float | координата x верхнего левого угла этой структуры RectangleF. |

### getY() {#getY--}
```
public final float getY()
```


Возвращает координату x верхнего левого угла этой структуры RectangleF.

**Returns:**
float - координата x верхнего левого угла этой структуры RectangleF.
### setY(float value) {#setY-float-}
```
public final void setY(float value)
```


Устанавливает координату x верхнего левого угла этой структуры RectangleF.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float | координата x верхнего левого угла этой структуры RectangleF. |

### getLocation() {#getLocation--}
```
public final PointF getLocation()
```


Возвращает координаты верхнего левого угла этой структуры [RectangleF](../../com.aspose.drawing/rectanglef).

**Returns:**
[PointF](../../com.aspose.drawing/pointf) - A [PointF](../../com.aspose.drawing/pointf) that represents the upper-left corner of this [RectangleF](../../com.aspose.drawing/rectanglef) structure.
### setLocation(PointF value) {#setLocation-com.aspose.drawing.PointF-}
```
public final void setLocation(PointF value)
```


Устанавливает координаты верхнего левого угла этой структуры [RectangleF](../../com.aspose.drawing/rectanglef).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [PointF](../../com.aspose.drawing/pointf) | координаты верхнего левого угла этой структуры [RectangleF](../../com.aspose.drawing/rectanglef). |

### getWidth() {#getWidth--}
```
public final float getWidth()
```


Возвращает ширину этой структуры RectangleF.

**Returns:**
float - ширина этой структуры RectangleF.
### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```


Устанавливает ширину этой структуры RectangleF.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float | ширина этой структуры RectangleF. |

### getHeight() {#getHeight--}
```
public final float getHeight()
```


Возвращает высоту этой структуры RectangleF.

**Returns:**
float - высота этой структуры RectangleF.
### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```


Устанавливает высоту этой структуры RectangleF.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float | высота этой структуры RectangleF. |

### getSize() {#getSize--}
```
public final SizeF getSize()
```


Возвращает размер этой [RectangleF](../../com.aspose.drawing/rectanglef).

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - A [SizeF](../../com.aspose.drawing/sizef) that represents the width and height of this [RectangleF](../../com.aspose.drawing/rectanglef) structure.
### setSize(SizeF value) {#setSize-com.aspose.drawing.SizeF-}
```
public final void setSize(SizeF value)
```


Устанавливает размер этой [RectangleF](../../com.aspose.drawing/rectanglef).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.drawing/sizef) | размер этой [RectangleF](../../com.aspose.drawing/rectanglef). |

### getLeft() {#getLeft--}
```
public final float getLeft()
```


Возвращает координату x левой грани этой структуры RectangleF.

**Returns:**
float - координата x левого края этой структуры RectangleF.
### getTop() {#getTop--}
```
public final float getTop()
```


Возвращает координату y верхней грани этой структуры RectangleF.

**Returns:**
float - координата y верхнего края этой структуры RectangleF.
### getRight() {#getRight--}
```
public final float getRight()
```


Возвращает координату x, являющуюся суммой X и Width этой структуры RectangleF.

**Returns:**
float - координата x, являющаяся суммой X и Width этой структуры RectangleF.
### getBottom() {#getBottom--}
```
public final float getBottom()
```


Возвращает координату y, являющуюся суммой Y и Height этой структуры RectangleF.

**Returns:**
float - координата y, являющаяся суммой Y и Height этой структуры RectangleF.
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### inflate(float x, float y) {#inflate-float-float-}
```
public final void inflate(float x, float y)
```


Увеличивает эту структуру [RectangleF](../../com.aspose.drawing/rectanglef) на указанную величину.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | float | Величина, на которую нужно расширить эту структуру [RectangleF](../../com.aspose.drawing/rectanglef) по горизонтали. |
| y | float | Величина, на которую нужно расширить эту структуру [RectangleF](../../com.aspose.drawing/rectanglef) по вертикали. |

### inflate(SizeF size) {#inflate-com.aspose.drawing.SizeF-}
```
public final void inflate(SizeF size)
```


Увеличивает этот [RectangleF](../../com.aspose.drawing/rectanglef) на указанную величину.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.drawing/sizef) | Величина, на которую нужно расширить этот прямоугольник. |

### intersect(RectangleF rect) {#intersect-com.aspose.drawing.RectangleF-}
```
public final void intersect(RectangleF rect)
```


Заменяет эту структуру [RectangleF](../../com.aspose.drawing/rectanglef) на пересечение её с указанной структурой [RectangleF](../../com.aspose.drawing/rectanglef).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | Прямоугольник для пересечения. |

### intersectsWith(RectangleF rect) {#intersectsWith-com.aspose.drawing.RectangleF-}
```
public final boolean intersectsWith(RectangleF rect)
```


Определяет, пересекается ли этот прямоугольник с `rect`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | Прямоугольник для проверки. |

**Returns:**
boolean - Этот метод возвращает true, если существует какое-либо пересечение.
### offset(PointF pos) {#offset-com.aspose.drawing.PointF-}
```
public final void offset(PointF pos)
```


Корректирует положение этого прямоугольника на указанную величину.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pos | [PointF](../../com.aspose.drawing/pointf) | Величина смещения местоположения. |

### offset(float x, float y) {#offset-float-float-}
```
public final void offset(float x, float y)
```


Корректирует положение этого прямоугольника на указанную величину.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | float | Величина горизонтального смещения местоположения. |
| y | float | Величина вертикального смещения местоположения. |

### contains(float x, float y) {#contains-float-float-}
```
public final boolean contains(float x, float y)
```


Определяет, содержится ли указанная точка внутри этой структуры [RectangleF](../../com.aspose.drawing/rectanglef).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | float | Координата X точки для проверки. |
| y | float | Координата Y точки для проверки. |

**Returns:**
boolean — Этот метод возвращает `true`, если точка, определённая x и y, находится внутри этой структуры [RectangleF](../../com.aspose.drawing/rectanglef); в противном случае `false`.
### contains(PointF pt) {#contains-com.aspose.drawing.PointF-}
```
public final boolean contains(PointF pt)
```


Определяет, содержится ли указанная точка внутри этой структуры [RectangleF](../../com.aspose.drawing/rectanglef).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pt | [PointF](../../com.aspose.drawing/pointf) | Объект [PointF](../../com.aspose.drawing/pointf) для проверки. |

**Returns:**
boolean — Этот метод возвращает `true`, если точка, представленная параметром pt, находится внутри этой структуры [RectangleF](../../com.aspose.drawing/rectanglef); в противном случае `false`.
### contains(RectangleF rect) {#contains-com.aspose.drawing.RectangleF-}
```
public final boolean contains(RectangleF rect)
```


Определяет, полностью ли прямоугольная область, представленная `rect`, содержится внутри этой структуры [RectangleF](../../com.aspose.drawing/rectanglef).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | Объект [RectangleF](../../com.aspose.drawing/rectanglef) для проверки. |

**Returns:**
boolean — Этот метод возвращает `true`, если прямоугольная область, представленная `rect`, полностью содержится в прямоугольной области, представленной этой [RectangleF](../../com.aspose.drawing/rectanglef); в противном случае `false`.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Определяет, равен ли указанный объект этому экземпляру.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | java.lang.Object | Объект для сравнения с этим экземпляром. |

**Returns:**
boolean — `true`, если указанный объект равен этому экземпляру; в противном случае `false`.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Возвращает хеш-код для этого экземпляра.

**Returns:**
int — Хеш-код для этого экземпляра, подходящий для использования в алгоритмах хеширования и структурах данных, таких как хеш-таблица.
### equals(RectangleF other) {#equals-com.aspose.drawing.RectangleF-}
```
public final boolean equals(RectangleF other)
```


Проверяет, имеет ли другая структура [RectangleF](../../com.aspose.drawing/rectanglef) то же расположение и размер, что и эта структура [RectangleF](../../com.aspose.drawing/rectanglef).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| other | [RectangleF](../../com.aspose.drawing/rectanglef) | Другой прямоугольник для проверки |

**Returns:**
boolean — Этот метод возвращает `true`, если другая структура [RectangleF](../../com.aspose.drawing/rectanglef) и её свойства X, Y, Width и Height равны соответствующим свойствам этой структуры [RectangleF](../../com.aspose.drawing/rectanglef); в противном случае `false`.
### CloneTo(RectangleF that) {#CloneTo-com.aspose.drawing.RectangleF-}
```
public void CloneTo(RectangleF that)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| that | [RectangleF](../../com.aspose.drawing/rectanglef) |  |

### Clone() {#Clone--}
```
public RectangleF Clone()
```




**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef)
### clone() {#clone--}
```
public Object clone()
```




**Returns:**
java.lang.Object
