---
title: ColorMap
second_title: Справочник API Aspose.Drawing для Java
description: Определяет карту для преобразования цветов.
type: docs
weight: 13
url: /ru/java/com.aspose.drawing.imaging/colormap/
---
**Inheritance:**
java.lang.Object
```
public final class ColorMap
```

Определяет отображение для преобразования цветов. Несколько методов класса [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes) корректируют цвета изображения, используя таблицу переназначения цветов, представляющую собой массив структур [ColorMap](../../com.aspose.drawing.imaging/colormap). Не наследуется.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [ColorMap()](#ColorMap--) | Инициализирует новый экземпляр класса [ColorMap](../../com.aspose.drawing.imaging/colormap). |
## Методы

| Метод | Описание |
| --- | --- |
| [getOldColor()](#getOldColor--) | Получает существующую структуру [Color](../../com.aspose.drawing/color), подлежащую преобразованию. |
| [setOldColor(Color value)](#setOldColor-com.aspose.drawing.Color-) | Устанавливает существующую структуру [Color](../../com.aspose.drawing/color), подлежащую преобразованию. |
| [getNewColor()](#getNewColor--) | Получает новую структуру [Color](../../com.aspose.drawing/color), в которую нужно преобразовать. |
| [setNewColor(Color value)](#setNewColor-com.aspose.drawing.Color-) | Устанавливает новую структуру [Color](../../com.aspose.drawing/color), в которую нужно преобразовать. |
### ColorMap() {#ColorMap--}
```
public ColorMap()
```


Инициализирует новый экземпляр класса [ColorMap](../../com.aspose.drawing.imaging/colormap).

### getOldColor() {#getOldColor--}
```
public Color getOldColor()
```


Получает существующую структуру [Color](../../com.aspose.drawing/color), подлежащую преобразованию.

**Returns:**
[Color](../../com.aspose.drawing/color) - The existing [Color](../../com.aspose.drawing/color) structure to be converted.
### setOldColor(Color value) {#setOldColor-com.aspose.drawing.Color-}
```
public void setOldColor(Color value)
```


Устанавливает существующую структуру [Color](../../com.aspose.drawing/color), подлежащую преобразованию.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Color](../../com.aspose.drawing/color) | существующая структура [Color](../../com.aspose.drawing/color), подлежащая преобразованию. |

### getNewColor() {#getNewColor--}
```
public Color getNewColor()
```


Получает новую структуру [Color](../../com.aspose.drawing/color), в которую нужно преобразовать.

**Returns:**
[Color](../../com.aspose.drawing/color) - The new [Color](../../com.aspose.drawing/color) structure to which to convert.
### setNewColor(Color value) {#setNewColor-com.aspose.drawing.Color-}
```
public void setNewColor(Color value)
```


Устанавливает новую структуру [Color](../../com.aspose.drawing/color), в которую нужно преобразовать.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Color](../../com.aspose.drawing/color) | новая структура [Color](../../com.aspose.drawing/color), в которую нужно преобразовать. |

