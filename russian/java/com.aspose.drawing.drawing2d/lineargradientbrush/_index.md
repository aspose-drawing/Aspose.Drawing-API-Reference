---
title: LinearGradientBrush
second_title: Справочник API Aspose.Drawing для Java
description: Инкапсулирует  с линейным градиентом.
type: docs
weight: 31
url: /ru/java/com.aspose.drawing.drawing2d/lineargradientbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.drawing.Brush](../../com.aspose.drawing/brush)
```
public final class LinearGradientBrush extends Brush
```

Инкапсулирует [Brush](../../com.aspose.drawing/brush) с линейным градиентом. Этот класс не может быть наследован.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [LinearGradientBrush(PointF point1, PointF point2, Color color1, Color color2)](#LinearGradientBrush-com.aspose.drawing.PointF-com.aspose.drawing.PointF-com.aspose.drawing.Color-com.aspose.drawing.Color-) | Инициализирует новый экземпляр класса [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) с указанными точками и цветами. |
| [LinearGradientBrush(Point point1, Point point2, Color color1, Color color2)](#LinearGradientBrush-com.aspose.drawing.Point-com.aspose.drawing.Point-com.aspose.drawing.Color-com.aspose.drawing.Color-) | Инициализирует новый экземпляр класса [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) с указанными точками и цветами. |
| [LinearGradientBrush(RectangleF rect, Color color1, Color color2, int linearGradientMode)](#LinearGradientBrush-com.aspose.drawing.RectangleF-com.aspose.drawing.Color-com.aspose.drawing.Color-int-) | Инициализирует новый экземпляр класса [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush), основанный на прямоугольнике, начальных и конечных цветах и режиме ориентации. |
| [LinearGradientBrush(Rectangle rect, Color color1, Color color2, int linearGradientMode)](#LinearGradientBrush-com.aspose.drawing.Rectangle-com.aspose.drawing.Color-com.aspose.drawing.Color-int-) | Инициализирует новый экземпляр класса [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush), основанный на прямоугольнике, начальных и конечных цветах и ориентации. |
| [LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle)](#LinearGradientBrush-com.aspose.drawing.RectangleF-com.aspose.drawing.Color-com.aspose.drawing.Color-float-) | Инициализирует новый экземпляр класса [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush), основанный на прямоугольнике, начальных и конечных цветах и угле ориентации. |
| [LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle, boolean isAngleScaleable)](#LinearGradientBrush-com.aspose.drawing.RectangleF-com.aspose.drawing.Color-com.aspose.drawing.Color-float-boolean-) | Инициализирует новый экземпляр класса [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush), основанный на прямоугольнике, начальных и конечных цветах и угле ориентации. |
| [LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle)](#LinearGradientBrush-com.aspose.drawing.Rectangle-com.aspose.drawing.Color-com.aspose.drawing.Color-float-) | Инициализирует новый экземпляр класса [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush), основанный на прямоугольнике, начальных и конечных цветах и угле ориентации. |
| [LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle, boolean isAngleScaleable)](#LinearGradientBrush-com.aspose.drawing.Rectangle-com.aspose.drawing.Color-com.aspose.drawing.Color-float-boolean-) | Инициализирует новый экземпляр класса [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush), основанный на прямоугольнике, начальных и конечных цветах и угле ориентации. |
## Методы

| Метод | Описание |
| --- | --- |
| [getLinearColors()](#getLinearColors--) | Получает или задает начальные и конечные цвета градиента. |
| [setLinearColors(Color[] value)](#setLinearColors-com.aspose.drawing.Color---) | Получает или задает начальные и конечные цвета градиента. |
| [getRectangle()](#getRectangle--) | Получает прямоугольный регион, определяющий начальные и конечные точки градиента. |
| [getGammaCorrection()](#getGammaCorrection--) | Получает или задает значение, указывающее, включена ли коррекция гаммы для этого [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush). |
| [setGammaCorrection(boolean value)](#setGammaCorrection-boolean-) | Получает или задает значение, указывающее, включена ли коррекция гаммы для этого [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush). |
| [getBlend()](#getBlend--) | Получает или задает `Blend`([.getBlend](../../null/\#getBlend)/[.setBlend(Blend)](../../null/\#setBlend-Blend-)), который определяет позиции и коэффициенты, задающие пользовательское затухание градиента. |
| [setBlend(Blend value)](#setBlend-com.aspose.drawing.drawing2d.Blend-) | Получает или задает `Blend`([.getBlend](../../null/\#getBlend)/[.setBlend(Blend)](../../null/\#setBlend-Blend-)), который определяет позиции и коэффициенты, задающие пользовательское затухание градиента. |
| [getInterpolationColors()](#getInterpolationColors--) | Получает или задает [ColorBlend](../../com.aspose.drawing.drawing2d/colorblend), определяющий многоцветный линейный градиент. |
| [setInterpolationColors(ColorBlend value)](#setInterpolationColors-com.aspose.drawing.drawing2d.ColorBlend-) | Получает или задает [ColorBlend](../../com.aspose.drawing.drawing2d/colorblend), определяющий многоцветный линейный градиент. |
| [getWrapMode()](#getWrapMode--) | Получает или задает перечисление `WrapMode`, указывающее режим обтекания для этого [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush). |
| [setWrapMode(int value)](#setWrapMode-int-) | Получает или задает перечисление `WrapMode`, указывающее режим обтекания для этого [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush). |
| [getTransform()](#getTransform--) | Получает или задает копию [Matrix](../../com.aspose.drawing.drawing2d/matrix), определяющую локальное геометрическое преобразование для этого [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush). |
| [setTransform(Matrix value)](#setTransform-com.aspose.drawing.drawing2d.Matrix-) | Получает или задает копию [Matrix](../../com.aspose.drawing.drawing2d/matrix), определяющую локальное геометрическое преобразование для этого [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush). |
| [deepClone()](#deepClone--) | Создает точную копию этого [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush). |
| [setSigmaBellShape(float focus)](#setSigmaBellShape-float-) | Создает затухание градиента, основанное на колоколообразной кривой. |
| [setSigmaBellShape(float focus, float scale)](#setSigmaBellShape-float-float-) | Создает затухание градиента, основанное на колоколообразной кривой. |
| [setBlendTriangularShape(float focus)](#setBlendTriangularShape-float-) | Создает линейный градиент с центральным цветом и линейным затуханием к единому цвету на обоих концах. |
| [setBlendTriangularShape(float focus, float scale)](#setBlendTriangularShape-float-float-) | Создает линейный градиент с центральным цветом и линейным затуханием к единому цвету на обоих концах. |
| [resetTransform()](#resetTransform--) | Сбрасывает свойство `LinearGradientBrush.Transform` к единичному преобразованию. |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-) | Умножает [Matrix](../../com.aspose.drawing.drawing2d/matrix), представляющий локальное геометрическое преобразование этого [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush), на указанный [Matrix](../../com.aspose.drawing.drawing2d/matrix), предваряя указанный [Matrix](../../com.aspose.drawing.drawing2d/matrix). |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-int-) | Умножает [Matrix](../../com.aspose.drawing.drawing2d/matrix), представляющий локальное геометрическое преобразование этого [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush), на указанный [Matrix](../../com.aspose.drawing.drawing2d/matrix) в указанном порядке. |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | Перемещает локальное геометрическое преобразование на указанные размеры. |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | Перемещает локальное геометрическое преобразование на указанные размеры в указанном порядке. |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | Масштабирует локальное геометрическое преобразование на указанные величины. |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | Масштабирует локальное геометрическое преобразование на указанные величины в указанном порядке. |
| [rotateTransform(float angle)](#rotateTransform-float-) | Вращает локальное геометрическое преобразование на указанную величину. |
| [rotateTransform(float angle, int order)](#rotateTransform-float-int-) | Вращает локальное геометрическое преобразование на указанную величину в указанном порядке. |
### LinearGradientBrush(PointF point1, PointF point2, Color color1, Color color2) {#LinearGradientBrush-com.aspose.drawing.PointF-com.aspose.drawing.PointF-com.aspose.drawing.Color-com.aspose.drawing.Color-}
```
public LinearGradientBrush(PointF point1, PointF point2, Color color1, Color color2)
```


Инициализирует новый экземпляр класса [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) с указанными точками и цветами.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| point1 | [PointF](../../com.aspose.drawing/pointf) | Структура [PointF](../../com.aspose.drawing/pointf), представляющая начальную точку линейного градиента. |
| point2 | [PointF](../../com.aspose.drawing/pointf) | Структура [PointF](../../com.aspose.drawing/pointf), представляющая конечную точку линейного градиента. |
| color1 | [Color](../../com.aspose.drawing/color) | Структура [Color](../../com.aspose.drawing/color), представляющая начальный цвет линейного градиента. |
| color2 | [Color](../../com.aspose.drawing/color) | Структура [Color](../../com.aspose.drawing/color), представляющая конечный цвет линейного градиента. |

### LinearGradientBrush(Point point1, Point point2, Color color1, Color color2) {#LinearGradientBrush-com.aspose.drawing.Point-com.aspose.drawing.Point-com.aspose.drawing.Color-com.aspose.drawing.Color-}
```
public LinearGradientBrush(Point point1, Point point2, Color color1, Color color2)
```


Инициализирует новый экземпляр класса [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) с указанными точками и цветами.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.drawing/point) | Структура [Point](../../com.aspose.drawing/point), представляющая начальную точку линейного градиента. |
| point2 | [Point](../../com.aspose.drawing/point) | Структура [Point](../../com.aspose.drawing/point), представляющая конечную точку линейного градиента. |
| color1 | [Color](../../com.aspose.drawing/color) | Структура [Color](../../com.aspose.drawing/color), представляющая начальный цвет линейного градиента. |
| color2 | [Color](../../com.aspose.drawing/color) | Структура [Color](../../com.aspose.drawing/color), представляющая конечный цвет линейного градиента. |

### LinearGradientBrush(RectangleF rect, Color color1, Color color2, int linearGradientMode) {#LinearGradientBrush-com.aspose.drawing.RectangleF-com.aspose.drawing.Color-com.aspose.drawing.Color-int-}
```
public LinearGradientBrush(RectangleF rect, Color color1, Color color2, int linearGradientMode)
```


Инициализирует новый экземпляр класса [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush), основанный на прямоугольнике, начальных и конечных цветах и режиме ориентации.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | Структура [RectangleF](../../com.aspose.drawing/rectanglef), определяющая границы линейного градиента. |
| color1 | [Color](../../com.aspose.drawing/color) | Структура [Color](../../com.aspose.drawing/color), представляющая начальный цвет градиента. |
| color2 | [Color](../../com.aspose.drawing/color) | Структура [Color](../../com.aspose.drawing/color), представляющая конечный цвет градиента. |
| linearGradientMode | int | Элемент перечисления [LinearGradientMode](../../com.aspose.drawing.drawing2d/lineargradientmode), задающий ориентацию градиента. Ориентация определяет начальные и конечные точки градиента. Например, LinearGradientMode.ForwardDiagonal указывает, что начальная точка находится в левом верхнем углу прямоугольника, а конечная — в правом нижнем углу прямоугольника. |

### LinearGradientBrush(Rectangle rect, Color color1, Color color2, int linearGradientMode) {#LinearGradientBrush-com.aspose.drawing.Rectangle-com.aspose.drawing.Color-com.aspose.drawing.Color-int-}
```
public LinearGradientBrush(Rectangle rect, Color color1, Color color2, int linearGradientMode)
```


Инициализирует новый экземпляр класса [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush), основанный на прямоугольнике, начальных и конечных цветах и ориентации.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | Структура `Rectangle`([.getRectangle](../../null/\#getRectangle)), определяющая границы линейного градиента. |
| color1 | [Color](../../com.aspose.drawing/color) | Структура [Color](../../com.aspose.drawing/color), представляющая начальный цвет градиента. |
| color2 | [Color](../../com.aspose.drawing/color) | Структура [Color](../../com.aspose.drawing/color), представляющая конечный цвет градиента. |
| linearGradientMode | int | Элемент перечисления [LinearGradientMode](../../com.aspose.drawing.drawing2d/lineargradientmode), задающий ориентацию градиента. Ориентация определяет начальные и конечные точки градиента. Например, LinearGradientMode.ForwardDiagonal указывает, что начальная точка находится в левом верхнем углу прямоугольника, а конечная — в правом нижнем углу прямоугольника. |

### LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle) {#LinearGradientBrush-com.aspose.drawing.RectangleF-com.aspose.drawing.Color-com.aspose.drawing.Color-float-}
```
public LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle)
```


Инициализирует новый экземпляр класса [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush), основанный на прямоугольнике, начальных и конечных цветах и угле ориентации.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | Структура [RectangleF](../../com.aspose.drawing/rectanglef), определяющая границы линейного градиента. |
| color1 | [Color](../../com.aspose.drawing/color) | Структура [Color](../../com.aspose.drawing/color), представляющая начальный цвет градиента. |
| color2 | [Color](../../com.aspose.drawing/color) | Структура [Color](../../com.aspose.drawing/color), представляющая конечный цвет градиента. |
| угол | float | Угол, измеряемый в градусах по часовой стрелке от оси x, линии ориентации градиента. |

### LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle, boolean isAngleScaleable) {#LinearGradientBrush-com.aspose.drawing.RectangleF-com.aspose.drawing.Color-com.aspose.drawing.Color-float-boolean-}
```
public LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle, boolean isAngleScaleable)
```


Инициализирует новый экземпляр класса [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush), основанный на прямоугольнике, начальных и конечных цветах и угле ориентации.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | Структура [RectangleF](../../com.aspose.drawing/rectanglef), определяющая границы линейного градиента. |
| color1 | [Color](../../com.aspose.drawing/color) | Структура [Color](../../com.aspose.drawing/color), представляющая начальный цвет градиента. |
| color2 | [Color](../../com.aspose.drawing/color) | Структура [Color](../../com.aspose.drawing/color), представляющая конечный цвет градиента. |
| угол | float | Угол, измеряемый в градусах по часовой стрелке от оси x, линии ориентации градиента. |
| isAngleScaleable | boolean | Установите значение true, чтобы указать, что угол зависит от преобразования, связанного с этим [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush); в противном случае — false. |

### LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle) {#LinearGradientBrush-com.aspose.drawing.Rectangle-com.aspose.drawing.Color-com.aspose.drawing.Color-float-}
```
public LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle)
```


Инициализирует новый экземпляр класса [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush), основанный на прямоугольнике, начальных и конечных цветах и угле ориентации.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | Структура `Rectangle`([.getRectangle](../../null/\#getRectangle)), определяющая границы линейного градиента. |
| color1 | [Color](../../com.aspose.drawing/color) | Структура [Color](../../com.aspose.drawing/color), представляющая начальный цвет градиента. |
| color2 | [Color](../../com.aspose.drawing/color) | Структура [Color](../../com.aspose.drawing/color), представляющая конечный цвет градиента. |
| угол | float | Угол, измеряемый в градусах по часовой стрелке от оси x, линии ориентации градиента. |

### LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle, boolean isAngleScaleable) {#LinearGradientBrush-com.aspose.drawing.Rectangle-com.aspose.drawing.Color-com.aspose.drawing.Color-float-boolean-}
```
public LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle, boolean isAngleScaleable)
```


Инициализирует новый экземпляр класса [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush), основанный на прямоугольнике, начальных и конечных цветах и угле ориентации.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | Структура `Rectangle`([.getRectangle](../../null/\#getRectangle)), определяющая границы линейного градиента. |
| color1 | [Color](../../com.aspose.drawing/color) | Структура [Color](../../com.aspose.drawing/color), представляющая начальный цвет градиента. |
| color2 | [Color](../../com.aspose.drawing/color) | Структура [Color](../../com.aspose.drawing/color), представляющая конечный цвет градиента. |
| угол | float | Угол, измеряемый в градусах по часовой стрелке от оси x, линии ориентации градиента. |
| isAngleScaleable | boolean | Установите значение true, чтобы указать, что угол зависит от преобразования, связанного с этим [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush); в противном случае — false. |

### getLinearColors() {#getLinearColors--}
```
public Color[] getLinearColors()
```


Получает или задает начальные и конечные цвета градиента.

**Returns:**
com.aspose.drawing.Color[]
### setLinearColors(Color[] value) {#setLinearColors-com.aspose.drawing.Color---}
```
public void setLinearColors(Color[] value)
```


Получает или задает начальные и конечные цвета градиента.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Color\[\]](../../com.aspose.drawing/color) |  |

### getRectangle() {#getRectangle--}
```
public RectangleF getRectangle()
```


Получает прямоугольный регион, определяющий начальные и конечные точки градиента.

**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef)
### getGammaCorrection() {#getGammaCorrection--}
```
public boolean getGammaCorrection()
```


Получает или задает значение, указывающее, включена ли коррекция гаммы для этого [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush).

**Returns:**
boolean
### setGammaCorrection(boolean value) {#setGammaCorrection-boolean-}
```
public void setGammaCorrection(boolean value)
```


Получает или задает значение, указывающее, включена ли коррекция гаммы для этого [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getBlend() {#getBlend--}
```
public Blend getBlend()
```


Получает или задает `Blend`([.getBlend](../../null/\#getBlend)/[.setBlend(Blend)](../../null/\#setBlend-Blend-)), который определяет позиции и коэффициенты, задающие пользовательское затухание градиента.

**Returns:**
[Blend](../../com.aspose.drawing.drawing2d/blend)
### setBlend(Blend value) {#setBlend-com.aspose.drawing.drawing2d.Blend-}
```
public void setBlend(Blend value)
```


Получает или задает `Blend`([.getBlend](../../null/\#getBlend)/[.setBlend(Blend)](../../null/\#setBlend-Blend-)), который определяет позиции и коэффициенты, задающие пользовательское затухание градиента.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Blend](../../com.aspose.drawing.drawing2d/blend) |  |

### getInterpolationColors() {#getInterpolationColors--}
```
public ColorBlend getInterpolationColors()
```


Получает или задает [ColorBlend](../../com.aspose.drawing.drawing2d/colorblend), определяющий многоцветный линейный градиент.

**Returns:**
[ColorBlend](../../com.aspose.drawing.drawing2d/colorblend)
### setInterpolationColors(ColorBlend value) {#setInterpolationColors-com.aspose.drawing.drawing2d.ColorBlend-}
```
public void setInterpolationColors(ColorBlend value)
```


Получает или задает [ColorBlend](../../com.aspose.drawing.drawing2d/colorblend), определяющий многоцветный линейный градиент.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [ColorBlend](../../com.aspose.drawing.drawing2d/colorblend) |  |

### getWrapMode() {#getWrapMode--}
```
public int getWrapMode()
```


Получает или задает перечисление `WrapMode`, указывающее режим обтекания для этого [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush).

**Returns:**
int
### setWrapMode(int value) {#setWrapMode-int-}
```
public void setWrapMode(int value)
```


Получает или задает перечисление `WrapMode`, указывающее режим обтекания для этого [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getTransform() {#getTransform--}
```
public Matrix getTransform()
```


Получает или задает копию [Matrix](../../com.aspose.drawing.drawing2d/matrix), определяющую локальное геометрическое преобразование для этого [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush).

**Returns:**
[Matrix](../../com.aspose.drawing.drawing2d/matrix)
### setTransform(Matrix value) {#setTransform-com.aspose.drawing.drawing2d.Matrix-}
```
public void setTransform(Matrix value)
```


Получает или задает копию [Matrix](../../com.aspose.drawing.drawing2d/matrix), определяющую локальное геометрическое преобразование для этого [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.drawing.drawing2d/matrix) |  |

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Создает точную копию этого [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush).

**Returns:**
java.lang.Object - [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush), создаваемый этим методом, приведённый к объекту.
### setSigmaBellShape(float focus) {#setSigmaBellShape-float-}
```
public void setSigmaBellShape(float focus)
```


Создает затухание градиента, основанное на колоколообразной кривой.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| фокус | float | Значение от 0 до 1, указывающее центр градиента (точка, где начальный и конечный цвета смешиваются поровну). |

### setSigmaBellShape(float focus, float scale) {#setSigmaBellShape-float-float-}
```
public void setSigmaBellShape(float focus, float scale)
```


Создает затухание градиента, основанное на колоколообразной кривой.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| фокус | float | Значение от 0 до 1, указывающее центр градиента (точка, где градиент состоит только из конечного цвета). |
| масштаб | float | Значение от 0 до 1, определяющее скорость затухания цветов от `focus`. |

### setBlendTriangularShape(float focus) {#setBlendTriangularShape-float-}
```
public void setBlendTriangularShape(float focus)
```


Создает линейный градиент с центральным цветом и линейным затуханием к единому цвету на обоих концах.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| фокус | float | Значение от 0 до 1, указывающее центр градиента (точка, где градиент состоит только из конечного цвета). |

### setBlendTriangularShape(float focus, float scale) {#setBlendTriangularShape-float-float-}
```
public void setBlendTriangularShape(float focus, float scale)
```


Создает линейный градиент с центральным цветом и линейным затуханием к единому цвету на обоих концах.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| фокус | float | Значение от 0 до 1, указывающее центр градиента (точка, где градиент состоит только из конечного цвета). |
| масштаб | float | Значение от 0 до 1, определяющее скорость затухания цветов от начального цвета к `focus` (конечный цвет). |

### resetTransform() {#resetTransform--}
```
public void resetTransform()
```


Сбрасывает свойство `LinearGradientBrush.Transform` к единичному преобразованию.

### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-}
```
public void multiplyTransform(Matrix matrix)
```


Умножает [Matrix](../../com.aspose.drawing.drawing2d/matrix), представляющий локальное геометрическое преобразование этого [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush), на указанный [Matrix](../../com.aspose.drawing.drawing2d/matrix), предваряя указанный [Matrix](../../com.aspose.drawing.drawing2d/matrix).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | Матрица [Matrix](../../com.aspose.drawing.drawing2d/matrix), используемая для умножения геометрического преобразования. |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-int-}
```
public void multiplyTransform(Matrix matrix, int order)
```


Умножает [Matrix](../../com.aspose.drawing.drawing2d/matrix), представляющий локальное геометрическое преобразование этого [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush), на указанный [Matrix](../../com.aspose.drawing.drawing2d/matrix) в указанном порядке.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | Матрица [Matrix](../../com.aspose.drawing.drawing2d/matrix), используемая для умножения геометрического преобразования. |
| order | int | [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder), указывающий порядок умножения двух матриц. |

### translateTransform(float dx, float dy) {#translateTransform-float-float-}
```
public void translateTransform(float dx, float dy)
```


Перемещает локальное геометрическое преобразование на указанные размеры. Этот метод добавляет трансляцию в начало преобразования.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| dx | float | Значение трансляции по оси x. |
| dy | float | Значение трансляции по оси y. |

### translateTransform(float dx, float dy, int order) {#translateTransform-float-float-int-}
```
public void translateTransform(float dx, float dy, int order)
```


Перемещает локальное геометрическое преобразование на указанные размеры в указанном порядке.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| dx | float | Значение трансляции по оси x. |
| dy | float | Значение трансляции по оси y. |
| порядок | int | Порядок (prepend или append), в котором применяется трансляция. |

### scaleTransform(float sx, float sy) {#scaleTransform-float-float-}
```
public void scaleTransform(float sx, float sy)
```


Масштабирует локальное геометрическое преобразование на указанные величины. Этот метод добавляет матрицу масштабирования в начало преобразования.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| sx | float | Величина, на которую следует масштабировать преобразование по оси x. |
| sy | float | Величина, на которую следует масштабировать преобразование по оси y. |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public void scaleTransform(float sx, float sy, int order)
```


Масштабирует локальное геометрическое преобразование на указанные величины в указанном порядке.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| sx | float | Величина, на которую следует масштабировать преобразование по оси x. |
| sy | float | Величина, на которую следует масштабировать преобразование по оси y. |
| order | int | Объект [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder), указывающий, добавлять ли матрицу масштабирования в конец или в начало. |

### rotateTransform(float angle) {#rotateTransform-float-}
```
public void rotateTransform(float angle)
```


Поворачивает локальное геометрическое преобразование на указанную величину. Этот метод добавляет вращение в начало преобразования.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| угол | float | Угол вращения. |

### rotateTransform(float angle, int order) {#rotateTransform-float-int-}
```
public void rotateTransform(float angle, int order)
```


Вращает локальное геометрическое преобразование на указанную величину в указанном порядке.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| угол | float | Угол вращения. |
| order | int | Объект [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder), указывающий, добавлять ли матрицу вращения в конец или в начало. |

