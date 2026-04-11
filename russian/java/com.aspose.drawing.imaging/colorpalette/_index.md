---
title: ColorPalette
second_title: Справочник API Aspose.Drawing для Java
description: Определяет массив цветов, составляющих цветовую палитру.
type: docs
weight: 16
url: /ru/java/com.aspose.drawing.imaging/colorpalette/
---
**Inheritance:**
java.lang.Object
```
public final class ColorPalette
```

Определяет массив цветов, составляющих цветовую палитру. Цвета представлены в виде 32‑битных ARGB‑цветов. Не наследуемый.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [ColorPalette(int count)](#ColorPalette-int-) | Инициализирует новый экземпляр класса `ColorPalette` и свойство IsCompactPalette имеет значение false. |
## Методы

| Метод | Описание |
| --- | --- |
| [getEntries()](#getEntries--) | Возвращает массив структур `com.aspose.drawing.Color`. |
| [isCompactPalette()](#isCompactPalette--) | Получает или задает значение, указывающее, используется ли компактная палитра. |
| [getFlags()](#getFlags--) |  |
| [setFlags(int flags)](#setFlags-int-) |  |
| [setEntries(int i, Color color)](#setEntries-int-com.aspose.drawing.Color-) |  |
### ColorPalette(int count) {#ColorPalette-int-}
```
public ColorPalette(int count)
```


Инициализирует новый экземпляр класса `ColorPalette` и свойство IsCompactPalette имеет значение false.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| count | int | Элементы цветовой палитры. |

### getEntries() {#getEntries--}
```
public Color[] getEntries()
```


Возвращает массив структур `com.aspose.drawing.Color`.

**Returns:**
com.aspose.drawing.Color[] — Элементы. Массив структур `com.aspose.drawing.Color`, составляющих эту `Aspose.Imaging.ColorPalette`.
### isCompactPalette() {#isCompactPalette--}
```
public boolean isCompactPalette()
```


Получает или задает значение, указывающее, используется ли компактная палитра.

**Returns:**
boolean — `true`, если используется компактная палитра; иначе `false`.

Компактная палитра означает, что изображение будет содержать только указанные элементы палитры, если это возможно, другими словами изображение будет более компактным и займет меньше места; в противном случае будет 2^BitsPerPixel элементов, и изображение зарезервирует больше места для всех возможных элементов палитры. Установка этого значения в true и изменение элементов палитры могут привести к потере производительности, поскольку может происходить перемещение данных, поэтому используйте это с осторожностью.
### getFlags() {#getFlags--}
```
public int getFlags()
```




**Returns:**
int
### setFlags(int flags) {#setFlags-int-}
```
public void setFlags(int flags)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| flags | int |  |

### setEntries(int i, Color color) {#setEntries-int-com.aspose.drawing.Color-}
```
public void setEntries(int i, Color color)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| i | int |  |
| color | [Color](../../com.aspose.drawing/color) |  |

