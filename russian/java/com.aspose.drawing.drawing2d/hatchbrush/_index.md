---
title: HatchBrush
second_title: Справочник API Aspose.Drawing для Java
description: Определяет прямоугольную кисть со стилем штриховки, цветом переднего плана и цветом фона.
type: docs
weight: 26
url: /ru/java/com.aspose.drawing.drawing2d/hatchbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.drawing.Brush](../../com.aspose.drawing/brush)
```
public final class HatchBrush extends Brush
```

Определяет прямоугольную кисть со стилем штриховки, цветом переднего плана и цветом фона. Этот класс нельзя наследовать.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [HatchBrush(int hatchstyle, Color foreColor)](#HatchBrush-int-com.aspose.drawing.Color-) | Инициализирует новый экземпляр класса [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) с указанным перечислением `HatchStyle`([.getHatchStyle](../../null/\#getHatchStyle)) и цветом переднего плана. |
| [HatchBrush(int hatchstyle, Color foreColor, Color backColor)](#HatchBrush-int-com.aspose.drawing.Color-com.aspose.drawing.Color-) | Инициализирует новый экземпляр класса [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) с указанным перечислением `HatchStyle`([.getHatchStyle](../../null/\#getHatchStyle)), цветом переднего плана и цветом фона. |
## Методы

| Метод | Описание |
| --- | --- |
| [getHatchStyle()](#getHatchStyle--) | Получает стиль штриховки этого объекта [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush). |
| [getForegroundColor()](#getForegroundColor--) | Получает цвет линий штриховки, рисуемых этим объектом [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush). |
| [getBackgroundColor()](#getBackgroundColor--) | Получает цвет промежутков между линиями штриховки, рисуемыми этим объектом [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush). |
| [deepClone()](#deepClone--) | Создаёт точную копию этого объекта [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush). |
### HatchBrush(int hatchstyle, Color foreColor) {#HatchBrush-int-com.aspose.drawing.Color-}
```
public HatchBrush(int hatchstyle, Color foreColor)
```


Инициализирует новый экземпляр класса [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) с указанным перечислением `HatchStyle`([.getHatchStyle](../../null/\#getHatchStyle)) и цветом переднего плана.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| hatchstyle | int | Одно из значений `HatchStyle`([.getHatchStyle](../../null/\#getHatchStyle)), представляющих узор, рисуемый этим [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush). |
| foreColor | [Color](../../com.aspose.drawing/color) | Структура [Color](../../com.aspose.drawing/color), представляющая цвет линий, рисуемых этим [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush). |

### HatchBrush(int hatchstyle, Color foreColor, Color backColor) {#HatchBrush-int-com.aspose.drawing.Color-com.aspose.drawing.Color-}
```
public HatchBrush(int hatchstyle, Color foreColor, Color backColor)
```


Инициализирует новый экземпляр класса [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) с указанным перечислением `HatchStyle`([.getHatchStyle](../../null/\#getHatchStyle)), цветом переднего плана и цветом фона.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| hatchstyle | int | Одно из значений `HatchStyle`([.getHatchStyle](../../null/\#getHatchStyle)), представляющих узор, рисуемый этим [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush). |
| foreColor | [Color](../../com.aspose.drawing/color) | Структура [Color](../../com.aspose.drawing/color), представляющая цвет линий, рисуемых этим [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush). |
| backColor | [Color](../../com.aspose.drawing/color) | Структура [Color](../../com.aspose.drawing/color), представляющая цвет промежутков между линиями, рисуемыми этим [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush). |

### getHatchStyle() {#getHatchStyle--}
```
public int getHatchStyle()
```


Получает стиль штриховки этого объекта [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush).

**Returns:**
int — стиль штриховки этого объекта [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush).
### getForegroundColor() {#getForegroundColor--}
```
public Color getForegroundColor()
```


Получает цвет линий штриховки, рисуемых этим объектом [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush).

**Returns:**
[Color](../../com.aspose.drawing/color) - the color of hatch lines drawn by this [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) object.
### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Получает цвет промежутков между линиями штриховки, рисуемыми этим объектом [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush).

**Returns:**
[Color](../../com.aspose.drawing/color) - the color of spaces between the hatch lines drawn by this [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) object.
### deepClone() {#deepClone--}
```
public Object deepClone()
```


Создаёт точную копию этого объекта [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush).

**Returns:**
java.lang.Object — объект [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush), создаваемый этим методом, приведённый к типу object.
