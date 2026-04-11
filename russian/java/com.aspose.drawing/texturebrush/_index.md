---
title: TextureBrush
second_title: Справочник API Aspose.Drawing для Java
description: Каждое свойство класса TextureBrush представляет собой объект Brush, который использует изображение для заполнения внутренней части фигуры.
type: docs
weight: 53
url: /ru/java/com.aspose.drawing/texturebrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.drawing.Brush](../../com.aspose.drawing/brush)
```
public final class TextureBrush extends Brush
```

Каждое свойство класса TextureBrush является объектом Brush, который использует изображение для заполнения внутренней части фигуры. Этот класс не может быть унаследован.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [TextureBrush(Image bitmap)](#TextureBrush-com.aspose.drawing.Image-) | Инициализирует новый экземпляр класса [TextureBrush](../../com.aspose.drawing/texturebrush), использующий указанное изображение. |
| [TextureBrush(Image image, int wrapMode)](#TextureBrush-com.aspose.drawing.Image-int-) | Инициализирует новый экземпляр класса [TextureBrush](../../com.aspose.drawing/texturebrush), использующий указанное изображение и режим обтекания. |
| [TextureBrush(Image image, int wrapMode, RectangleF dstRect)](#TextureBrush-com.aspose.drawing.Image-int-com.aspose.drawing.RectangleF-) | Инициализирует новый экземпляр класса [TextureBrush](../../com.aspose.drawing/texturebrush), использующий указанное изображение, режим обтекания и ограничивающий прямоугольник. |
| [TextureBrush(Image image, RectangleF dstRect)](#TextureBrush-com.aspose.drawing.Image-com.aspose.drawing.RectangleF-) | Инициализирует новый экземпляр класса [TextureBrush](../../com.aspose.drawing/texturebrush), который использует указанное изображение и ограничивающий прямоугольник. |
| [TextureBrush(Image image, RectangleF dstRect, ImageAttributes imageAttr)](#TextureBrush-com.aspose.drawing.Image-com.aspose.drawing.RectangleF-com.aspose.drawing.imaging.ImageAttributes-) | Инициализирует новый экземпляр класса [TextureBrush](../../com.aspose.drawing/texturebrush), который использует указанное изображение, ограничивающий прямоугольник и атрибуты изображения. |
## Методы

| Метод | Описание |
| --- | --- |
| [getImage()](#getImage--) | Возвращает объект `Image`, связанный с этим объектом TextureBrush. |
| [getTransform()](#getTransform--) | Возвращает копию объекта `Matrix`, определяющего локальное геометрическое преобразование изображения, связанного с этим объектом TextureBrush. |
| [setTransform(Matrix value)](#setTransform-com.aspose.drawing.drawing2d.Matrix-) | Устанавливает копию объекта `Matrix`, определяющего локальное геометрическое преобразование изображения, связанного с этим объектом TextureBrush. |
| [getWrapMode()](#getWrapMode--) | Возвращает перечисление `WrapMode`, указывающее режим обтекания для этого объекта TextureBrush. |
| [setWrapMode(int value)](#setWrapMode-int-) | Устанавливает перечисление `WrapMode`, указывающее режим обтекания для этого объекта TextureBrush. |
| [deepClone()](#deepClone--) | Создаёт точную копию этого объекта [TextureBrush](../../com.aspose.drawing/texturebrush). |
| [resetTransform()](#resetTransform--) | Сбрасывает свойство Transform объекта [TextureBrush](../../com.aspose.drawing/texturebrush) к единичному. |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-) | Умножает объект [Matrix](../../com.aspose.drawing.drawing2d/matrix), представляющий локальное геометрическое преобразование этого объекта [TextureBrush](../../com.aspose.drawing/texturebrush), на указанный объект [Matrix](../../com.aspose.drawing.drawing2d/matrix), предварительно добавляя указанный объект [Matrix](../../com.aspose.drawing.drawing2d/matrix). |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-int-) | Умножает объект [Matrix](../../com.aspose.drawing.drawing2d/matrix), представляющий локальное геометрическое преобразование этого объекта [TextureBrush](../../com.aspose.drawing/texturebrush), на указанный объект [Matrix](../../com.aspose.drawing.drawing2d/matrix) в указанном порядке. |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | Перемещает локальное геометрическое преобразование этого объекта [TextureBrush](../../com.aspose.drawing/texturebrush) на указанные размеры. |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | Перемещает локальное геометрическое преобразование этого объекта [TextureBrush](../../com.aspose.drawing/texturebrush) на указанные размеры в указанном порядке. |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | Масштабирует локальное геометрическое преобразование этого объекта [TextureBrush](../../com.aspose.drawing/texturebrush) на указанные величины. |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | Масштабирует локальное геометрическое преобразование этого объекта [TextureBrush](../../com.aspose.drawing/texturebrush) на указанные величины в указанном порядке. |
| [rotateTransform(float angle)](#rotateTransform-float-) | Поворачивает локальное геометрическое преобразование этого объекта [TextureBrush](../../com.aspose.drawing/texturebrush) на указанную величину. |
| [rotateTransform(float angle, int order)](#rotateTransform-float-int-) | Поворачивает локальное геометрическое преобразование этого объекта [TextureBrush](../../com.aspose.drawing/texturebrush) на указанную величину в указанном порядке. |
### TextureBrush(Image bitmap) {#TextureBrush-com.aspose.drawing.Image-}
```
public TextureBrush(Image bitmap)
```


Инициализирует новый экземпляр класса [TextureBrush](../../com.aspose.drawing/texturebrush), использующий указанное изображение.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| bitmap | [Image](../../com.aspose.drawing/image) | Объект `Image`([.getImage](../../null/\#getImage)), которым этот объект [TextureBrush](../../com.aspose.drawing/texturebrush) заполняет внутренние области. |

### TextureBrush(Image image, int wrapMode) {#TextureBrush-com.aspose.drawing.Image-int-}
```
public TextureBrush(Image image, int wrapMode)
```


Инициализирует новый экземпляр класса [TextureBrush](../../com.aspose.drawing/texturebrush), использующий указанное изображение и режим обтекания.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| image | [Image](../../com.aspose.drawing/image) | Изображение. |
| wrapMode | int | Перечисление `WrapMode`([.getWrapMode](../../null/\#getWrapMode)/[.setWrapMode(int)](../../null/\#setWrapMode-int-)), которое определяет, как этот объект [TextureBrush](../../com.aspose.drawing/texturebrush) заполняет плиткой. |

### TextureBrush(Image image, int wrapMode, RectangleF dstRect) {#TextureBrush-com.aspose.drawing.Image-int-com.aspose.drawing.RectangleF-}
```
public TextureBrush(Image image, int wrapMode, RectangleF dstRect)
```


Инициализирует новый экземпляр класса [TextureBrush](../../com.aspose.drawing/texturebrush), использующий указанное изображение, режим обтекания и ограничивающий прямоугольник.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| image | [Image](../../com.aspose.drawing/image) | Изображение. |
| wrapMode | int | Перечисление `WrapMode`([.getWrapMode](../../null/\#getWrapMode)/[.setWrapMode(int)](../../null/\#setWrapMode-int-)), которое определяет, как этот объект [TextureBrush](../../com.aspose.drawing/texturebrush) заполняет плиткой. |
| dstRect | [RectangleF](../../com.aspose.drawing/rectanglef) | Структура [RectangleF](../../com.aspose.drawing/rectanglef), представляющая ограничивающий прямоугольник для этого объекта [TextureBrush](../../com.aspose.drawing/texturebrush). |

### TextureBrush(Image image, RectangleF dstRect) {#TextureBrush-com.aspose.drawing.Image-com.aspose.drawing.RectangleF-}
```
public TextureBrush(Image image, RectangleF dstRect)
```


Инициализирует новый экземпляр класса [TextureBrush](../../com.aspose.drawing/texturebrush), который использует указанное изображение и ограничивающий прямоугольник.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| image | [Image](../../com.aspose.drawing/image) | Объект `Image`([.getImage](../../null/\#getImage)), которым этот объект [TextureBrush](../../com.aspose.drawing/texturebrush) заполняет внутренние области. |
| dstRect | [RectangleF](../../com.aspose.drawing/rectanglef) | Структура [RectangleF](../../com.aspose.drawing/rectanglef), представляющая ограничивающий прямоугольник для этого объекта [TextureBrush](../../com.aspose.drawing/texturebrush). |

### TextureBrush(Image image, RectangleF dstRect, ImageAttributes imageAttr) {#TextureBrush-com.aspose.drawing.Image-com.aspose.drawing.RectangleF-com.aspose.drawing.imaging.ImageAttributes-}
```
public TextureBrush(Image image, RectangleF dstRect, ImageAttributes imageAttr)
```


Инициализирует новый экземпляр класса [TextureBrush](../../com.aspose.drawing/texturebrush), который использует указанное изображение, ограничивающий прямоугольник и атрибуты изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| image | [Image](../../com.aspose.drawing/image) | Объект Image, которым этот объект TextureBrush заполняет внутренние области. |
| dstRect | [RectangleF](../../com.aspose.drawing/rectanglef) | Структура RectangleF, представляющая ограничивающий прямоугольник для этого объекта TextureBrush. |
| imageAttr | [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes) | Объект ImageAttributes, содержащий дополнительную информацию об изображении, используемом этим объектом TextureBrush. |

### getImage() {#getImage--}
```
public Image getImage()
```


Возвращает объект `Image`, связанный с этим объектом TextureBrush.

**Returns:**
[Image](../../com.aspose.drawing/image) - the Image object associated with this TextureBrush object.
### getTransform() {#getTransform--}
```
public Matrix getTransform()
```


Возвращает копию объекта `Matrix`, определяющего локальное геометрическое преобразование изображения, связанного с этим объектом TextureBrush.

**Returns:**
[Matrix](../../com.aspose.drawing.drawing2d/matrix) - a copy of the Matrix object that defines a local geometric transformation for the image associated with this TextureBrush object.
### setTransform(Matrix value) {#setTransform-com.aspose.drawing.drawing2d.Matrix-}
```
public void setTransform(Matrix value)
```


Устанавливает копию объекта `Matrix`, определяющего локальное геометрическое преобразование изображения, связанного с этим объектом TextureBrush.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | копия объекта `Matrix`, определяющего локальное геометрическое преобразование изображения, связанного с этим объектом TextureBrush. |

### getWrapMode() {#getWrapMode--}
```
public int getWrapMode()
```


Возвращает перечисление `WrapMode`, указывающее режим обтекания для этого объекта TextureBrush.

**Returns:**
int — перечисление WrapMode, указывающее режим обтекания для этого объекта TextureBrush.
### setWrapMode(int value) {#setWrapMode-int-}
```
public void setWrapMode(int value)
```


Устанавливает перечисление `WrapMode`, указывающее режим обтекания для этого объекта TextureBrush.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | перечисление WrapMode, указывающее режим обтекания для этого объекта TextureBrush. |

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Создаёт точную копию этого объекта [TextureBrush](../../com.aspose.drawing/texturebrush).

**Returns:**
java.lang.Object — объект [TextureBrush](../../com.aspose.drawing/texturebrush), создаваемый этим методом, приведённый к типу Object.
### resetTransform() {#resetTransform--}
```
public void resetTransform()
```


Сбрасывает свойство Transform объекта [TextureBrush](../../com.aspose.drawing/texturebrush) к единичному.

### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-}
```
public void multiplyTransform(Matrix matrix)
```


Умножает объект [Matrix](../../com.aspose.drawing.drawing2d/matrix), представляющий локальное геометрическое преобразование этого объекта [TextureBrush](../../com.aspose.drawing/texturebrush), на указанный объект [Matrix](../../com.aspose.drawing.drawing2d/matrix), предварительно добавляя указанный объект [Matrix](../../com.aspose.drawing.drawing2d/matrix).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | Объект [Matrix](../../com.aspose.drawing.drawing2d/matrix), которым умножается геометрическое преобразование. |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-int-}
```
public void multiplyTransform(Matrix matrix, int order)
```


Умножает объект [Matrix](../../com.aspose.drawing.drawing2d/matrix), представляющий локальное геометрическое преобразование этого объекта [TextureBrush](../../com.aspose.drawing/texturebrush), на указанный объект [Matrix](../../com.aspose.drawing.drawing2d/matrix) в указанном порядке.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | Объект [Matrix](../../com.aspose.drawing.drawing2d/matrix), которым умножается геометрическое преобразование. |
| order | int | Перечисление [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder), указывающее порядок умножения двух матриц. |

### translateTransform(float dx, float dy) {#translateTransform-float-float-}
```
public void translateTransform(float dx, float dy)
```


Перемещает локальное геометрическое преобразование этого объекта [TextureBrush](../../com.aspose.drawing/texturebrush) на указанные размеры. Этот метод добавляет трансляцию в начало преобразования.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| dx | float | Размер, на который следует переместить преобразование по оси x. |
| dy | float | Размер, на который следует переместить преобразование по оси y. |

### translateTransform(float dx, float dy, int order) {#translateTransform-float-float-int-}
```
public void translateTransform(float dx, float dy, int order)
```


Перемещает локальное геометрическое преобразование этого объекта [TextureBrush](../../com.aspose.drawing/texturebrush) на указанные размеры в указанном порядке.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| dx | float | Размер, на который следует переместить преобразование по оси x. |
| dy | float | Размер, на который следует переместить преобразование по оси y. |
| порядок | int | Порядок (prepend или append), в котором применяется трансляция. |

### scaleTransform(float sx, float sy) {#scaleTransform-float-float-}
```
public void scaleTransform(float sx, float sy)
```


Масштабирует локальное геометрическое преобразование этого объекта [TextureBrush](../../com.aspose.drawing/texturebrush) на указанные величины. Этот метод добавляет матрицу масштабирования в начало преобразования.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| sx | float | Величина, на которую следует масштабировать преобразование по оси x. |
| sy | float | Величина, на которую следует масштабировать преобразование по оси y. |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public void scaleTransform(float sx, float sy, int order)
```


Масштабирует локальное геометрическое преобразование этого объекта [TextureBrush](../../com.aspose.drawing/texturebrush) на указанные величины в указанном порядке.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| sx | float | Величина, на которую следует масштабировать преобразование по оси x. |
| sy | float | Величина, на которую следует масштабировать преобразование по оси y. |
| order | int | Перечисление [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder), указывающее, добавлять ли матрицу масштабирования в конец или в начало. |

### rotateTransform(float angle) {#rotateTransform-float-}
```
public void rotateTransform(float angle)
```


Поворачивает локальное геометрическое преобразование этого объекта [TextureBrush](../../com.aspose.drawing/texturebrush) на указанную величину. Этот метод добавляет вращение в начало преобразования.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| угол | float | Угол вращения. |

### rotateTransform(float angle, int order) {#rotateTransform-float-int-}
```
public void rotateTransform(float angle, int order)
```


Поворачивает локальное геометрическое преобразование этого объекта [TextureBrush](../../com.aspose.drawing/texturebrush) на указанную величину в указанном порядке.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| угол | float | Угол вращения. |
| order | int | Перечисление [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder), указывающее, добавлять ли матрицу вращения в конец или в начало. |

