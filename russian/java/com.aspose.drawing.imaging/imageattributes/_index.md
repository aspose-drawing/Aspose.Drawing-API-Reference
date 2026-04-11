---
title: ImageAttributes
second_title: Справочник API Aspose.Drawing для Java
description: Содержит информацию о том, как цвета растрового изображения и метафайла обрабатываются во время рендеринга.
type: docs
weight: 24
url: /ru/java/com.aspose.drawing.imaging/imageattributes/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public final class ImageAttributes implements System.IDisposable
```

Содержит информацию о том, как цвета растрового изображения и метафайла обрабатываются во время рендеринга.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [ImageAttributes()](#ImageAttributes--) | Инициализирует новый экземпляр класса [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes). |
## Методы

| Метод | Описание |
| --- | --- |
| [dispose()](#dispose--) | Освобождает все ресурсы, используемые этим объектом [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes). |
| [deepClone()](#deepClone--) | Создаёт точную копию этого объекта [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes). |
| [setColorMatrix(ColorMatrix newColorMatrix)](#setColorMatrix-com.aspose.drawing.imaging.ColorMatrix-) | Устанавливает матрицу коррекции цвета для категории по умолчанию. |
| [setColorMatrix(ColorMatrix newColorMatrix, int flags)](#setColorMatrix-com.aspose.drawing.imaging.ColorMatrix-int-) | Устанавливает матрицу коррекции цвета для категории по умолчанию. |
| [setColorMatrix(ColorMatrix newColorMatrix, int mode, int type)](#setColorMatrix-com.aspose.drawing.imaging.ColorMatrix-int-int-) | Устанавливает матрицу коррекции цвета для указанной категории. |
| [clearColorMatrix()](#clearColorMatrix--) | Очищает матрицу коррекции цвета для категории по умолчанию. |
| [clearColorMatrix(int type)](#clearColorMatrix-int-) | Очищает матрицу коррекции цвета для указанной категории. |
| [setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix)](#setColorMatrices-com.aspose.drawing.imaging.ColorMatrix-com.aspose.drawing.imaging.ColorMatrix-) | Устанавливает матрицу коррекции цвета и матрицу коррекции градаций серого для категории по умолчанию. |
| [setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int flags)](#setColorMatrices-com.aspose.drawing.imaging.ColorMatrix-com.aspose.drawing.imaging.ColorMatrix-int-) | Устанавливает матрицу коррекции цвета и матрицу коррекции градаций серого для категории по умолчанию. |
| [setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int mode, int type)](#setColorMatrices-com.aspose.drawing.imaging.ColorMatrix-com.aspose.drawing.imaging.ColorMatrix-int-int-) | Устанавливает матрицу коррекции цвета и матрицу коррекции градаций серого для указанной категории. |
| [setThreshold(float threshold)](#setThreshold-float-) | Устанавливает порог (диапазон прозрачности) для категории по умолчанию. |
| [setThreshold(float threshold, int type)](#setThreshold-float-int-) | Устанавливает порог (диапазон прозрачности) для указанной категории. |
| [clearThreshold()](#clearThreshold--) | Очищает значение порога для категории по умолчанию. |
| [clearThreshold(int type)](#clearThreshold-int-) | Очищает значение порога для указанной категории. |
| [setGamma(float gamma)](#setGamma-float-) | Устанавливает значение гаммы для категории по умолчанию. |
| [setGamma(float gamma, int type)](#setGamma-float-int-) | Устанавливает значение гаммы для указанной категории. |
| [clearGamma()](#clearGamma--) | Отключает коррекцию гаммы для категории по умолчанию. |
| [clearGamma(int type)](#clearGamma-int-) | Отключает коррекцию гаммы для указанной категории. |
| [setNoOp()](#setNoOp--) | Выключает коррекцию цвета для категории по умолчанию. |
| [setNoOp(int type)](#setNoOp-int-) | Выключает коррекцию цвета для указанной категории. |
| [clearNoOp()](#clearNoOp--) | Очищает настройку NoOp для категории по умолчанию. |
| [clearNoOp(int type)](#clearNoOp-int-) | Очищает настройку NoOp для указанной категории. |
| [setColorKey(Color colorLow, Color colorHigh)](#setColorKey-com.aspose.drawing.Color-com.aspose.drawing.Color-) | Устанавливает цветовой ключ для категории по умолчанию. |
| [setColorKey(Color colorLow, Color colorHigh, int type)](#setColorKey-com.aspose.drawing.Color-com.aspose.drawing.Color-int-) | Устанавливает цветовой ключ (диапазон прозрачности) для указанной категории. |
| [clearColorKey()](#clearColorKey--) | Очищает цветовой ключ (диапазон прозрачности) для категории по умолчанию. |
| [clearColorKey(int type)](#clearColorKey-int-) | Очищает цветовой ключ (диапазон прозрачности) для указанной категории. |
| [setOutputChannel(int flags)](#setOutputChannel-int-) | Устанавливает выходной канал CMYK (cyan-magenta-yellow-black) для категории по умолчанию. |
| [setOutputChannel(int flags, int type)](#setOutputChannel-int-int-) | Устанавливает выходной канал CMYK (cyan-magenta-yellow-black) для указанной категории. |
| [clearOutputChannel()](#clearOutputChannel--) | Очищает настройку выходного канала CMYK (cyan-magenta-yellow-black) для категории по умолчанию. |
| [clearOutputChannel(int type)](#clearOutputChannel-int-) | Очищает настройку выходного канала (cyan-magenta-yellow-black) для указанной категории. |
| [setOutputChannelColorProfile(String colorProfileFilename)](#setOutputChannelColorProfile-java.lang.String-) | Устанавливает файл цветового профиля выходного канала для категории по умолчанию. |
| [setOutputChannelColorProfile(String colorProfileFilename, int type)](#setOutputChannelColorProfile-java.lang.String-int-) | Устанавливает файл цветового профиля выходного канала для указанной категории. |
| [clearOutputChannelColorProfile()](#clearOutputChannelColorProfile--) | Очищает настройку цветового профиля выходного канала для категории по умолчанию. |
| [clearOutputChannelColorProfile(int type)](#clearOutputChannelColorProfile-int-) | Очищает настройку цветового профиля выходного канала для указанной категории. |
| [setRemapTable(ColorMap[] map)](#setRemapTable-com.aspose.drawing.imaging.ColorMap---) | Устанавливает таблицу переназначения цветов для категории по умолчанию. |
| [setRemapTable(ColorMap[] map, int type)](#setRemapTable-com.aspose.drawing.imaging.ColorMap---int-) | Устанавливает таблицу переназначения цветов для указанной категории. |
| [clearRemapTable()](#clearRemapTable--) | Очищает таблицу переназначения цветов для категории по умолчанию. |
| [clearRemapTable(int type)](#clearRemapTable-int-) | Очищает таблицу переназначения цветов для указанной категории. |
| [setBrushRemapTable(ColorMap[] map)](#setBrushRemapTable-com.aspose.drawing.imaging.ColorMap---) | Устанавливает таблицу переназначения цветов для категории кисти. |
| [clearBrushRemapTable()](#clearBrushRemapTable--) | Очищает таблицу переназначения цветов кисти этого объекта [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes). |
| [setWrapMode(int mode)](#setWrapMode-int-) | Устанавливает режим обтекания, который используется для определения способа размещения текстуры по фигуре или на границах фигуры. |
| [setWrapMode(int mode, Color color)](#setWrapMode-int-com.aspose.drawing.Color-) | Устанавливает режим обтекания и цвет, используемые для определения способа размещения текстуры по фигуре или на границах фигуры. |
| [setWrapMode(int mode, Color color, boolean clamp)](#setWrapMode-int-com.aspose.drawing.Color-boolean-) | Устанавливает режим обтекания и цвет, используемые для определения способа размещения текстуры по фигуре или на границах фигуры. |
| [getAdjustedPalette(ColorPalette palette, int type)](#getAdjustedPalette-com.aspose.drawing.imaging.ColorPalette-int-) | Регулирует цвета в палитре в соответствии с настройками коррекции указанной категории. |
### ImageAttributes() {#ImageAttributes--}
```
public ImageAttributes()
```


Инициализирует новый экземпляр класса [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes).

### dispose() {#dispose--}
```
public void dispose()
```


Освобождает все ресурсы, используемые этим объектом [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes).

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Создаёт точную копию этого объекта [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes).

**Returns:**
java.lang.Object — объект [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes), создаваемый этим классом, приведённый к типу object.
### setColorMatrix(ColorMatrix newColorMatrix) {#setColorMatrix-com.aspose.drawing.imaging.ColorMatrix-}
```
public void setColorMatrix(ColorMatrix newColorMatrix)
```


Устанавливает матрицу коррекции цвета для категории по умолчанию.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) | Матрица коррекции цвета. |

### setColorMatrix(ColorMatrix newColorMatrix, int flags) {#setColorMatrix-com.aspose.drawing.imaging.ColorMatrix-int-}
```
public void setColorMatrix(ColorMatrix newColorMatrix, int flags)
```


Устанавливает матрицу коррекции цвета для категории по умолчанию.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) | Матрица коррекции цвета. |
| flags | int | Элемент [ColorMatrixFlag](../../com.aspose.drawing.imaging/colormatrixflag), который указывает тип изображения и цвета, которые будут затронуты матрицей коррекции цвета. |

### setColorMatrix(ColorMatrix newColorMatrix, int mode, int type) {#setColorMatrix-com.aspose.drawing.imaging.ColorMatrix-int-int-}
```
public void setColorMatrix(ColorMatrix newColorMatrix, int mode, int type)
```


Устанавливает матрицу коррекции цвета для указанной категории.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) | Матрица коррекции цвета. |
| mode | int | Элемент [ColorMatrixFlag](../../com.aspose.drawing.imaging/colormatrixflag), который указывает тип изображения и цвета, которые будут затронуты матрицей коррекции цвета. |
| type | int | Элемент [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype), который указывает категорию, для которой устанавливается матрица коррекции цвета. |

### clearColorMatrix() {#clearColorMatrix--}
```
public void clearColorMatrix()
```


Очищает матрицу коррекции цвета для категории по умолчанию.

### clearColorMatrix(int type) {#clearColorMatrix-int-}
```
public void clearColorMatrix(int type)
```


Очищает матрицу коррекции цвета для указанной категории.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| type | int | Элемент [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype), который указывает категорию, для которой очищается матрица коррекции цвета. |

### setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix) {#setColorMatrices-com.aspose.drawing.imaging.ColorMatrix-com.aspose.drawing.imaging.ColorMatrix-}
```
public void setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix)
```


Устанавливает матрицу коррекции цвета и матрицу коррекции градаций серого для категории по умолчанию.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) | Матрица коррекции цвета. |
| grayMatrix | [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) | Матрица коррекции оттенков серого. |

### setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int flags) {#setColorMatrices-com.aspose.drawing.imaging.ColorMatrix-com.aspose.drawing.imaging.ColorMatrix-int-}
```
public void setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int flags)
```


Устанавливает матрицу коррекции цвета и матрицу коррекции градаций серого для категории по умолчанию.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) | Матрица коррекции цвета. |
| grayMatrix | [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) | Матрица коррекции оттенков серого. |
| flags | int | Элемент [ColorMatrixFlag](../../com.aspose.drawing.imaging/colormatrixflag), который указывает тип изображения и цвета, которые будут затронуты матрицами коррекции цвета и оттенков серого. |

### setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int mode, int type) {#setColorMatrices-com.aspose.drawing.imaging.ColorMatrix-com.aspose.drawing.imaging.ColorMatrix-int-int-}
```
public void setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int mode, int type)
```


Устанавливает матрицу коррекции цвета и матрицу коррекции градаций серого для указанной категории.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) | Матрица коррекции цвета. |
| grayMatrix | [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) | Матрица коррекции оттенков серого. |
| mode | int | Элемент [ColorMatrixFlag](../../com.aspose.drawing.imaging/colormatrixflag), который указывает тип изображения и цвета, которые будут затронуты матрицами коррекции цвета и оттенков серого. |
| type | int | Элемент [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype), который указывает категорию, для которой устанавливаются матрицы коррекции цвета и оттенков серого. |

### setThreshold(float threshold) {#setThreshold-float-}
```
public void setThreshold(float threshold)
```


Устанавливает порог (диапазон прозрачности) для категории по умолчанию.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| порог | float | Вещественное число, которое задаёт значение порога. |

### setThreshold(float threshold, int type) {#setThreshold-float-int-}
```
public void setThreshold(float threshold, int type)
```


Устанавливает порог (диапазон прозрачности) для указанной категории.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| порог | float | Значение порога от 0,0 до 1,0, которое используется в качестве точки разрыва для сортировки цветов, которые будут сопоставлены либо с максимальным, либо с минимальным значением. |
| type | int | Элемент [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype), который указывает категорию, для которой задаётся порог цвета. |

### clearThreshold() {#clearThreshold--}
```
public void clearThreshold()
```


Очищает значение порога для категории по умолчанию.

### clearThreshold(int type) {#clearThreshold-int-}
```
public void clearThreshold(int type)
```


Очищает значение порога для указанной категории.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| type | int | Элемент [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype), который указывает категорию, для которой очищается порог. |

### setGamma(float gamma) {#setGamma-float-}
```
public void setGamma(float gamma)
```


Устанавливает значение гаммы для категории по умолчанию.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| гамма | float | Значение коррекции гаммы. |

### setGamma(float gamma, int type) {#setGamma-float-int-}
```
public void setGamma(float gamma, int type)
```


Устанавливает значение гаммы для указанной категории.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| гамма | float | Значение коррекции гаммы. |
| type | int | Элемент перечисления [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype), который указывает категорию, для которой задаётся значение гаммы. |

### clearGamma() {#clearGamma--}
```
public void clearGamma()
```


Отключает коррекцию гаммы для категории по умолчанию.

### clearGamma(int type) {#clearGamma-int-}
```
public void clearGamma(int type)
```


Отключает коррекцию гаммы для указанной категории.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| type | int | Элемент [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype), который указывает категорию, для которой отключена коррекция гаммы. |

### setNoOp() {#setNoOp--}
```
public void setNoOp()
```


Отключает коррекцию цвета для категории по умолчанию. Вы можете вызвать метод [.clearNoOp](../../null/\#clearNoOp), чтобы восстановить настройки коррекции цвета, которые были активны до вызова метода [.setNoOp](../../null/\#setNoOp).

### setNoOp(int type) {#setNoOp-int-}
```
public void setNoOp(int type)
```


Отключает коррекцию цвета для указанной категории. Вы можете вызвать метод [.clearNoOp](../../null/\#clearNoOp), чтобы восстановить настройки коррекции цвета, которые были активны до вызова метода [.setNoOp](../../null/\#setNoOp).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| type | int | Элемент [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype), который указывает категорию, для которой отключена коррекция цвета. |

### clearNoOp() {#clearNoOp--}
```
public void clearNoOp()
```


Очищает настройку NoOp для категории по умолчанию.

### clearNoOp(int type) {#clearNoOp-int-}
```
public void clearNoOp(int type)
```


Очищает настройку NoOp для указанной категории.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| type | int | Элемент [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype), который указывает категорию, для которой сбрасывается настройка NoOp. |

### setColorKey(Color colorLow, Color colorHigh) {#setColorKey-com.aspose.drawing.Color-com.aspose.drawing.Color-}
```
public void setColorKey(Color colorLow, Color colorHigh)
```


Устанавливает цветовой ключ для категории по умолчанию.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| colorLow | [Color](../../com.aspose.drawing/color) | Низкое значение цветового ключа. |
| colorHigh | [Color](../../com.aspose.drawing/color) | Высокое значение цветового ключа. |

### setColorKey(Color colorLow, Color colorHigh, int type) {#setColorKey-com.aspose.drawing.Color-com.aspose.drawing.Color-int-}
```
public void setColorKey(Color colorLow, Color colorHigh, int type)
```


Устанавливает цветовой ключ (диапазон прозрачности) для указанной категории.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| colorLow | [Color](../../com.aspose.drawing/color) | Низкое значение цветового ключа. |
| colorHigh | [Color](../../com.aspose.drawing/color) | Высокое значение цветового ключа. |
| type | int | Элемент [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype), который указывает категорию, для которой задаётся цветовой ключ. |

### clearColorKey() {#clearColorKey--}
```
public void clearColorKey()
```


Очищает цветовой ключ (диапазон прозрачности) для категории по умолчанию.

### clearColorKey(int type) {#clearColorKey-int-}
```
public void clearColorKey(int type)
```


Очищает цветовой ключ (диапазон прозрачности) для указанной категории.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| type | int | Элемент [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype), который указывает категорию, для которой сбрасывается цветовой ключ. |

### setOutputChannel(int flags) {#setOutputChannel-int-}
```
public void setOutputChannel(int flags)
```


Устанавливает выходной канал CMYK (cyan-magenta-yellow-black) для категории по умолчанию.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| flags | int | Элемент [ColorChannelFlag](../../com.aspose.drawing.imaging/colorchannelflag), который указывает выходной канал. |

### setOutputChannel(int flags, int type) {#setOutputChannel-int-int-}
```
public void setOutputChannel(int flags, int type)
```


Устанавливает выходной канал CMYK (cyan-magenta-yellow-black) для указанной категории.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| flags | int | Элемент [ColorChannelFlag](../../com.aspose.drawing.imaging/colorchannelflag), который указывает выходной канал. |
| type | int | Элемент [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype), который указывает категорию, для которой задаётся выходной канал. |

### clearOutputChannel() {#clearOutputChannel--}
```
public void clearOutputChannel()
```


Очищает настройку выходного канала CMYK (cyan-magenta-yellow-black) для категории по умолчанию.

### clearOutputChannel(int type) {#clearOutputChannel-int-}
```
public void clearOutputChannel(int type)
```


Очищает настройку выходного канала (cyan-magenta-yellow-black) для указанной категории.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| type | int | Элемент [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype), который указывает категорию, для которой сбрасывается настройка выходного канала. |

### setOutputChannelColorProfile(String colorProfileFilename) {#setOutputChannelColorProfile-java.lang.String-}
```
public void setOutputChannelColorProfile(String colorProfileFilename)
```


Устанавливает файл цветового профиля выходного канала для категории по умолчанию.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| colorProfileFilename | java.lang.String | Путь к файлу цветового профиля. Если файл цветового профиля находится в каталоге %SystemRoot%\\System32\\Spool\\Drivers\\Color, этот параметр может быть именем файла. В противном случае параметр должен содержать полностью квалифицированный путь. |

### setOutputChannelColorProfile(String colorProfileFilename, int type) {#setOutputChannelColorProfile-java.lang.String-int-}
```
public void setOutputChannelColorProfile(String colorProfileFilename, int type)
```


Устанавливает файл цветового профиля выходного канала для указанной категории.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| colorProfileFilename | java.lang.String | Путь к файлу цветового профиля. Если файл цветового профиля находится в каталоге %SystemRoot%\\System32\\Spool\\Drivers\\Color, этот параметр может быть именем файла. В противном случае параметр должен содержать полностью квалифицированный путь. |
| type | int | Элемент [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype), который указывает категорию, для которой задаётся файл цветового профиля выходного канала. |

### clearOutputChannelColorProfile() {#clearOutputChannelColorProfile--}
```
public void clearOutputChannelColorProfile()
```


Очищает настройку цветового профиля выходного канала для категории по умолчанию.

### clearOutputChannelColorProfile(int type) {#clearOutputChannelColorProfile-int-}
```
public void clearOutputChannelColorProfile(int type)
```


Очищает настройку цветового профиля выходного канала для указанной категории.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| type | int | Элемент [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype), который указывает категорию, для которой сбрасывается настройка профиля выходного канала. |

### setRemapTable(ColorMap[] map) {#setRemapTable-com.aspose.drawing.imaging.ColorMap---}
```
public void setRemapTable(ColorMap[] map)
```


Устанавливает таблицу переназначения цветов для категории по умолчанию.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| map | [ColorMap\[\]](../../com.aspose.drawing.imaging/colormap) | Массив пар цветов типа [ColorMap](../../com.aspose.drawing.imaging/colormap). Каждая пара содержит существующий цвет (первое значение) и цвет, к которому он будет преобразован (второе значение). |

### setRemapTable(ColorMap[] map, int type) {#setRemapTable-com.aspose.drawing.imaging.ColorMap---int-}
```
public void setRemapTable(ColorMap[] map, int type)
```


Устанавливает таблицу переназначения цветов для указанной категории.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| map | [ColorMap\[\]](../../com.aspose.drawing.imaging/colormap) | Массив пар цветов типа [ColorMap](../../com.aspose.drawing.imaging/colormap). Каждая пара содержит существующий цвет (первое значение) и цвет, к которому он будет преобразован (второе значение). |
| type | int | Элемент [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype), который указывает категорию, для которой задаётся таблица переопределения цветов. |

### clearRemapTable() {#clearRemapTable--}
```
public void clearRemapTable()
```


Очищает таблицу переназначения цветов для категории по умолчанию.

### clearRemapTable(int type) {#clearRemapTable-int-}
```
public void clearRemapTable(int type)
```


Очищает таблицу переназначения цветов для указанной категории.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| type | int | Элемент [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype), который указывает категорию, для которой сбрасывается таблица переопределения. |

### setBrushRemapTable(ColorMap[] map) {#setBrushRemapTable-com.aspose.drawing.imaging.ColorMap---}
```
public void setBrushRemapTable(ColorMap[] map)
```


Устанавливает таблицу переназначения цветов для категории кисти.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| map | [ColorMap\[\]](../../com.aspose.drawing.imaging/colormap) | Массив объектов [ColorMap](../../com.aspose.drawing.imaging/colormap). |

### clearBrushRemapTable() {#clearBrushRemapTable--}
```
public void clearBrushRemapTable()
```


Очищает таблицу переназначения цветов кисти этого объекта [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes).

### setWrapMode(int mode) {#setWrapMode-int-}
```
public void setWrapMode(int mode)
```


Устанавливает режим обтекания, который используется для определения того, как заполнять текстуру по поверхности фигуры или вдоль её границ. Текстура заполняет фигуру плиткой, когда её размер меньше размера заполняемой фигуры.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| mode | int | Элемент [WrapMode](../../com.aspose.drawing.drawing2d/wrapmode), который указывает, как повторяющиеся копии изображения используются для заполнения области плиткой. |

### setWrapMode(int mode, Color color) {#setWrapMode-int-com.aspose.drawing.Color-}
```
public void setWrapMode(int mode, Color color)
```


Устанавливает режим обтекания и цвет, используемые для определения того, как размещать текстуру по фигуре или на её границах. Текстура размещается по фигуре, чтобы заполнить её, когда текстура меньше фигуры, которую она заполняет.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| mode | int | Элемент [WrapMode](../../com.aspose.drawing.drawing2d/wrapmode), который указывает, как повторяющиеся копии изображения используются для заполнения области плиткой. |
| color | [Color](../../com.aspose.drawing/color) | Объект [Color](../../com.aspose.drawing/color), который указывает цвет пикселей за пределами отрисованного изображения. Этот цвет виден, если параметр режима установлен в `WrapMode.Clamp` и исходный прямоугольник, переданный в `Graphics.DrawImage`, больше самого изображения. |

### setWrapMode(int mode, Color color, boolean clamp) {#setWrapMode-int-com.aspose.drawing.Color-boolean-}
```
public void setWrapMode(int mode, Color color, boolean clamp)
```


Устанавливает режим обтекания и цвет, используемые для определения того, как размещать текстуру по фигуре или на её границах. Текстура размещается по фигуре, чтобы заполнить её, когда текстура меньше фигуры, которую она заполняет.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| mode | int | Элемент [WrapMode](../../com.aspose.drawing.drawing2d/wrapmode), который указывает, как повторяющиеся копии изображения используются для заполнения области плиткой. |
| color | [Color](../../com.aspose.drawing/color) | Объект цвета, который указывает цвет пикселей за пределами отрисованного изображения. Этот цвет виден, если параметр режима установлен в `WrapMode.Clamp` и исходный прямоугольник, переданный в `Graphics.DrawImage`, больше самого изображения. |
| clamp | boolean | Этот параметр не оказывает влияния. Установите его в false. |

### getAdjustedPalette(ColorPalette palette, int type) {#getAdjustedPalette-com.aspose.drawing.imaging.ColorPalette-int-}
```
public void getAdjustedPalette(ColorPalette palette, int type)
```


Регулирует цвета в палитре в соответствии с настройками коррекции указанной категории.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| palette | [ColorPalette](../../com.aspose.drawing.imaging/colorpalette) | Объект [ColorPalette](../../com.aspose.drawing.imaging/colorpalette), который на входе содержит палитру для корректировки, а на выходе содержит скорректированную палитру. |
| type | int | Элемент [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype), который указывает категорию, настройки которой будут применены к палитре. |

