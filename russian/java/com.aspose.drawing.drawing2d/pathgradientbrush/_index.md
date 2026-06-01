---
title: PathGradientBrush
second_title: Справочник API Aspose.Drawing для Java
description: Инкапсулирует объект, который заполняет внутреннюю часть другого объекта градиентом.
type: docs
weight: 36
url: /ru/java/com.aspose.drawing.drawing2d/pathgradientbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.drawing.Brush](../../com.aspose.drawing/brush)
```
public final class PathGradientBrush extends Brush
```

Инкапсулирует объект [Brush](../../com.aspose.drawing/brush), который заполняет внутреннюю часть объекта [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) градиентом. Этот класс не может быть унаследован.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [PathGradientBrush(PointF[] points)](#PathGradientBrush-com.aspose.drawing.PointF---) | Инициализирует новый экземпляр класса [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) с указанными точками. |
| [PathGradientBrush(PointF[] points, int wrapMode)](#PathGradientBrush-com.aspose.drawing.PointF---int-) | Инициализирует новый экземпляр класса [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) с указанными точками и режимом обтекания. |
| [PathGradientBrush(Point[] points)](#PathGradientBrush-com.aspose.drawing.Point---) | Инициализирует новый экземпляр класса [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) с указанными точками. |
| [PathGradientBrush(Point[] points, int wrapMode)](#PathGradientBrush-com.aspose.drawing.Point---int-) | Инициализирует новый экземпляр класса [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) с указанными точками и режимом обтекания. |
| [PathGradientBrush(GraphicsPath path)](#PathGradientBrush-com.aspose.drawing.drawing2d.GraphicsPath-) | Инициализирует новый экземпляр класса [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) с указанным путем. |
## Методы

| Метод | Описание |
| --- | --- |
| [getCenterColor()](#getCenterColor--) | Получает или задает цвет в центре градиента пути. |
| [setCenterColor(Color value)](#setCenterColor-com.aspose.drawing.Color-) | Получает или задает цвет в центре градиента пути. |
| [getSurroundColors()](#getSurroundColors--) | Получает или задает массив цветов, соответствующих точкам пути, который заполняет этот [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush). |
| [setSurroundColors(Color[] value)](#setSurroundColors-com.aspose.drawing.Color---) | Получает или задает массив цветов, соответствующих точкам пути, который заполняет этот [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush). |
| [getCenterPoint()](#getCenterPoint--) | Получает или задает центральную точку градиента пути. |
| [setCenterPoint(PointF value)](#setCenterPoint-com.aspose.drawing.PointF-) | Получает или задает центральную точку градиента пути. |
| [getRectangle()](#getRectangle--) | Получает ограничивающий прямоугольник для этого [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush). |
| [getBlend()](#getBlend--) | Получает или задает `Blend`([.getBlend](../../null/\#getBlend)/[.setBlend(Blend)](../../null/\#setBlend-Blend-)), который определяет позиции и коэффициенты, задающие пользовательское затухание градиента. |
| [setBlend(Blend value)](#setBlend-com.aspose.drawing.drawing2d.Blend-) | Получает или задает `Blend`([.getBlend](../../null/\#getBlend)/[.setBlend(Blend)](../../null/\#setBlend-Blend-)), который определяет позиции и коэффициенты, задающие пользовательское затухание градиента. |
| [getInterpolationColors()](#getInterpolationColors--) | Получает или задает [ColorBlend](../../com.aspose.drawing.drawing2d/colorblend), определяющий многоцветный линейный градиент. |
| [setInterpolationColors(ColorBlend value)](#setInterpolationColors-com.aspose.drawing.drawing2d.ColorBlend-) | Получает или задает [ColorBlend](../../com.aspose.drawing.drawing2d/colorblend), определяющий многоцветный линейный градиент. |
| [getTransform()](#getTransform--) | Получает или задает копию [Matrix](../../com.aspose.drawing.drawing2d/matrix), определяющую локальное геометрическое преобразование для этого [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush). |
| [setTransform(Matrix value)](#setTransform-com.aspose.drawing.drawing2d.Matrix-) | Получает или задает копию [Matrix](../../com.aspose.drawing.drawing2d/matrix), определяющую локальное геометрическое преобразование для этого [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush). |
| [getFocusScales()](#getFocusScales--) | Получает или задает точку фокуса для уменьшения градиента. |
| [setFocusScales(PointF value)](#setFocusScales-com.aspose.drawing.PointF-) | Получает или задает точку фокуса для уменьшения градиента. |
| [getWrapMode()](#getWrapMode--) | Получает или задает `WrapMode`([.getWrapMode](../../null/\#getWrapMode)/[.setWrapMode(int)](../../null/\#setWrapMode-int-)), который указывает режим обтекания для этого [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush). |
| [setWrapMode(int value)](#setWrapMode-int-) | Получает или задает `WrapMode`([.getWrapMode](../../null/\#getWrapMode)/[.setWrapMode(int)](../../null/\#setWrapMode-int-)), который указывает режим обтекания для этого [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush). |
| [deepClone()](#deepClone--) | Создает точную копию этого [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush). |
| [setSigmaBellShape(float focus)](#setSigmaBellShape-float-) | Создает градиентную кисть, меняющую цвет, начиная от центра пути и распространяясь к его границе. |
| [setSigmaBellShape(float focus, float scale)](#setSigmaBellShape-float-float-) | Создает градиентную кисть, меняющую цвет, начиная от центра пути и распространяясь к его границе. |
| [setBlendTriangularShape(float focus)](#setBlendTriangularShape-float-) | Создает градиент с центральным цветом и линейным переходом к одному окружающему цвету. |
| [setBlendTriangularShape(float focus, float scale)](#setBlendTriangularShape-float-float-) | Создает градиент с центральным цветом и линейным спадом к каждому окружающему цвету. |
| [resetTransform()](#resetTransform--) | Сбрасывает свойство `PathGradientBrush.Transform` к единичному. |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-) | Обновляет матрицу преобразования кисти произведением матрицы преобразования кисти, умноженной на другую матрицу. |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-int-) | Обновляет матрицу преобразования кисти произведением матрицы преобразования кисти, умноженной на другую матрицу. |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | Применяет указанное смещение к локальному геометрическому преобразованию. |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | Применяет указанное смещение к локальному геометрическому преобразованию в указанном порядке. |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | Масштабирует локальное геометрическое преобразование на указанные величины. |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | Масштабирует локальное геометрическое преобразование на указанные величины в указанном порядке. |
| [rotateTransform(float angle)](#rotateTransform-float-) | Вращает локальное геометрическое преобразование на указанную величину. |
| [rotateTransform(float angle, int order)](#rotateTransform-float-int-) | Вращает локальное геометрическое преобразование на указанную величину в указанном порядке. |
### PathGradientBrush(PointF[] points) {#PathGradientBrush-com.aspose.drawing.PointF---}
```
public PathGradientBrush(PointF[] points)
```


Инициализирует новый экземпляр класса [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) с указанными точками.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.drawing/pointf) | Массив структур [PointF](../../com.aspose.drawing/pointf), представляющих точки, образующие вершины пути. |

### PathGradientBrush(PointF[] points, int wrapMode) {#PathGradientBrush-com.aspose.drawing.PointF---int-}
```
public PathGradientBrush(PointF[] points, int wrapMode)
```


Инициализирует новый экземпляр класса [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) с указанными точками и режимом обтекания.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.drawing/pointf) | Массив структур [PointF](../../com.aspose.drawing/pointf), представляющих точки, образующие вершины пути. |
| wrapMode | int | `WrapMode`([.getWrapMode](../../null/\#getWrapMode)/[.setWrapMode(int)](../../null/\#setWrapMode-int-)), определяющий, как заполняемые области, нарисованные с помощью этого [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush), будут чередоваться. |

### PathGradientBrush(Point[] points) {#PathGradientBrush-com.aspose.drawing.Point---}
```
public PathGradientBrush(Point[] points)
```


Инициализирует новый экземпляр класса [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) с указанными точками.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| points | [Point\[\]](../../com.aspose.drawing/point) | Массив структур [Point](../../com.aspose.drawing/point), представляющих точки, образующие вершины пути. |

### PathGradientBrush(Point[] points, int wrapMode) {#PathGradientBrush-com.aspose.drawing.Point---int-}
```
public PathGradientBrush(Point[] points, int wrapMode)
```


Инициализирует новый экземпляр класса [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) с указанными точками и режимом обтекания.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| points | [Point\[\]](../../com.aspose.drawing/point) | Массив структур [Point](../../com.aspose.drawing/point), представляющих точки, образующие вершины пути. |
| wrapMode | int | `WrapMode`([.getWrapMode](../../null/\#getWrapMode)/[.setWrapMode(int)](../../null/\#setWrapMode-int-)), определяющий, как заполняемые области, нарисованные с помощью этого [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush), будут чередоваться. |

### PathGradientBrush(GraphicsPath path) {#PathGradientBrush-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public PathGradientBrush(GraphicsPath path)
```


Инициализирует новый экземпляр класса [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) с указанным путем.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | Объект [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) определяет область, заполняемую этим [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush). |

### getCenterColor() {#getCenterColor--}
```
public Color getCenterColor()
```


Получает или задает цвет в центре градиента пути.

**Returns:**
[Color](../../com.aspose.drawing/color)
### setCenterColor(Color value) {#setCenterColor-com.aspose.drawing.Color-}
```
public void setCenterColor(Color value)
```


Получает или задает цвет в центре градиента пути.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Color](../../com.aspose.drawing/color) |  |

### getSurroundColors() {#getSurroundColors--}
```
public Color[] getSurroundColors()
```


Получает или задает массив цветов, соответствующих точкам пути, который заполняет этот [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush).

**Returns:**
com.aspose.drawing.Color[]
### setSurroundColors(Color[] value) {#setSurroundColors-com.aspose.drawing.Color---}
```
public void setSurroundColors(Color[] value)
```


Получает или задает массив цветов, соответствующих точкам пути, который заполняет этот [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Color\[\]](../../com.aspose.drawing/color) |  |

### getCenterPoint() {#getCenterPoint--}
```
public PointF getCenterPoint()
```


Получает или задает центральную точку градиента пути.

**Returns:**
[PointF](../../com.aspose.drawing/pointf)
### setCenterPoint(PointF value) {#setCenterPoint-com.aspose.drawing.PointF-}
```
public void setCenterPoint(PointF value)
```


Получает или задает центральную точку градиента пути.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [PointF](../../com.aspose.drawing/pointf) |  |

### getRectangle() {#getRectangle--}
```
public RectangleF getRectangle()
```


Получает ограничивающий прямоугольник для этого [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush).

**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef)
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

### getTransform() {#getTransform--}
```
public Matrix getTransform()
```


Получает или задает копию [Matrix](../../com.aspose.drawing.drawing2d/matrix), определяющую локальное геометрическое преобразование для этого [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush).

**Returns:**
[Matrix](../../com.aspose.drawing.drawing2d/matrix)
### setTransform(Matrix value) {#setTransform-com.aspose.drawing.drawing2d.Matrix-}
```
public void setTransform(Matrix value)
```


Получает или задает копию [Matrix](../../com.aspose.drawing.drawing2d/matrix), определяющую локальное геометрическое преобразование для этого [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.drawing.drawing2d/matrix) |  |

### getFocusScales() {#getFocusScales--}
```
public PointF getFocusScales()
```


Получает или задает точку фокуса для уменьшения градиента.

**Returns:**
[PointF](../../com.aspose.drawing/pointf)
### setFocusScales(PointF value) {#setFocusScales-com.aspose.drawing.PointF-}
```
public void setFocusScales(PointF value)
```


Получает или задает точку фокуса для уменьшения градиента.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [PointF](../../com.aspose.drawing/pointf) |  |

### getWrapMode() {#getWrapMode--}
```
public int getWrapMode()
```


Получает или задает `WrapMode`([.getWrapMode](../../null/\#getWrapMode)/[.setWrapMode(int)](../../null/\#setWrapMode-int-)), который указывает режим обтекания для этого [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush).

**Returns:**
int
### setWrapMode(int value) {#setWrapMode-int-}
```
public void setWrapMode(int value)
```


Получает или задает `WrapMode`([.getWrapMode](../../null/\#getWrapMode)/[.setWrapMode(int)](../../null/\#setWrapMode-int-)), который указывает режим обтекания для этого [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Создает точную копию этого [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush).

**Returns:**
java.lang.Object — объект [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush), создаваемый этим методом, приведённый к типу object.
### setSigmaBellShape(float focus) {#setSigmaBellShape-float-}
```
public void setSigmaBellShape(float focus)
```


Создает градиентную кисть, меняющую цвет, начиная от центра пути к его границе. Переход от одного цвета к другому основан на колоколообразной кривой.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| фокус | float | Значение от 0 до 1, указывающее, где вдоль любого радиала от центра пути к его границе центральный цвет будет иметь наибольшую интенсивность. Значение 1 (по умолчанию) размещает максимальную интенсивность в центре пути. |

### setSigmaBellShape(float focus, float scale) {#setSigmaBellShape-float-float-}
```
public void setSigmaBellShape(float focus, float scale)
```


Создает градиентную кисть, меняющую цвет, начиная от центра пути к его границе. Переход от одного цвета к другому основан на колоколообразной кривой.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| фокус | float | Значение от 0 до 1, указывающее, где вдоль любого радиала от центра пути к его границе центральный цвет будет иметь наибольшую интенсивность. Значение 1 (по умолчанию) размещает максимальную интенсивность в центре пути. |
| масштаб | float | Значение от 0 до 1, определяющее максимальную интенсивность центрального цвета, смешиваемого с граничным цветом. Значение 1 задаёт наивысшую возможную интенсивность центрального цвета и является значением по умолчанию. |

### setBlendTriangularShape(float focus) {#setBlendTriangularShape-float-}
```
public void setBlendTriangularShape(float focus)
```


Создает градиент с центральным цветом и линейным переходом к одному окружающему цвету.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| фокус | float | Значение от 0 до 1, указывающее, где вдоль любого радиала от центра пути к его границе центральный цвет будет иметь наибольшую интенсивность. Значение 1 (по умолчанию) размещает максимальную интенсивность в центре пути. |

### setBlendTriangularShape(float focus, float scale) {#setBlendTriangularShape-float-float-}
```
public void setBlendTriangularShape(float focus, float scale)
```


Создает градиент с центральным цветом и линейным спадом к каждому окружающему цвету.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| фокус | float | Значение от 0 до 1, указывающее, где вдоль любого радиала от центра пути к его границе центральный цвет будет иметь наибольшую интенсивность. Значение 1 (по умолчанию) размещает максимальную интенсивность в центре пути. |
| масштаб | float | Значение от 0 до 1, определяющее максимальную интенсивность центрального цвета, смешиваемого с граничным цветом. Значение 1 задаёт наивысшую возможную интенсивность центрального цвета и является значением по умолчанию. |

### resetTransform() {#resetTransform--}
```
public void resetTransform()
```


Сбрасывает свойство `PathGradientBrush.Transform` к единичному.

### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-}
```
public void multiplyTransform(Matrix matrix)
```


Обновляет матрицу преобразования кисти произведением матрицы преобразования кисти, умноженной на другую матрицу.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | [Matrix](../../com.aspose.drawing.drawing2d/matrix), который будет умножен на текущую матрицу преобразования кисти. |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-int-}
```
public void multiplyTransform(Matrix matrix, int order)
```


Обновляет матрицу преобразования кисти произведением матрицы преобразования кисти, умноженной на другую матрицу.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | [Matrix](../../com.aspose.drawing.drawing2d/matrix), который будет умножен на текущую матрицу преобразования кисти. |
| order | int | [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder), указывающий порядок умножения двух матриц. |

### translateTransform(float dx, float dy) {#translateTransform-float-float-}
```
public void translateTransform(float dx, float dy)
```


Применяет указанное смещение к локальному геометрическому преобразованию. Этот метод добавляет смещение в начало преобразования.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| dx | float | Значение трансляции по оси x. |
| dy | float | Значение трансляции по оси y. |

### translateTransform(float dx, float dy, int order) {#translateTransform-float-float-int-}
```
public void translateTransform(float dx, float dy, int order)
```


Применяет указанное смещение к локальному геометрическому преобразованию в указанном порядке.

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
| sx | float | Коэффициент масштабирования преобразования по оси X. |
| sy | float | Коэффициент масштабирования преобразования по оси Y. |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public void scaleTransform(float sx, float sy, int order)
```


Масштабирует локальное геометрическое преобразование на указанные величины в указанном порядке.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| sx | float | Коэффициент масштабирования преобразования по оси X. |
| sy | float | Коэффициент масштабирования преобразования по оси Y. |
| order | int | Объект [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder), указывающий, добавлять ли матрицу масштабирования в конец или в начало. |

### rotateTransform(float angle) {#rotateTransform-float-}
```
public void rotateTransform(float angle)
```


Поворачивает локальное геометрическое преобразование на указанную величину. Этот метод добавляет вращение в начало преобразования.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| угол | float | Угол (размах) вращения. |

### rotateTransform(float angle, int order) {#rotateTransform-float-int-}
```
public void rotateTransform(float angle, int order)
```


Вращает локальное геометрическое преобразование на указанную величину в указанном порядке.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| угол | float | Угол (размах) вращения. |
| order | int | Объект [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder), указывающий, добавлять ли матрицу вращения в конец или в начало. |

