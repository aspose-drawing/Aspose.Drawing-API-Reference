---
title: Bitmap
second_title: Справочник API Aspose.Drawing для Java
description: Инкапсулирует bitmap, который состоит из пиксельных данных графического изображения и его атрибутов.
type: docs
weight: 10
url: /ru/java/com.aspose.drawing/bitmap/
---
**Inheritance:**
java.lang.Object, [com.aspose.drawing.Image](../../com.aspose.drawing/image)
```
public class Bitmap extends Image
```

Инкапсулирует bitmap, который состоит из пиксельных данных графического изображения и его атрибутов. [Bitmap](../../com.aspose.drawing/bitmap) — это объект, используемый для работы с изображениями, определёнными пиксельными данными.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Bitmap(int width, int height)](#Bitmap-int-int-) | Инициализирует новый экземпляр класса [Bitmap](../../com.aspose.drawing/bitmap) с указанным размером. |
| [Bitmap(String filename)](#Bitmap-java.lang.String-) | Инициализирует новый экземпляр класса [Bitmap](../../com.aspose.drawing/bitmap) из указанного файла. |
| [Bitmap(String filename, boolean useIcm)](#Bitmap-java.lang.String-boolean-) | Инициализирует новый экземпляр класса [Bitmap](../../com.aspose.drawing/bitmap) из указанного файла. |
| [Bitmap(InputStream stream)](#Bitmap-java.io.InputStream-) | Инициализирует новый экземпляр класса [Bitmap](../../com.aspose.drawing/bitmap) из указанного потока данных. |
| [Bitmap(InputStream stream, boolean useIcm)](#Bitmap-java.io.InputStream-boolean-) | Инициализирует новый экземпляр класса [Bitmap](../../com.aspose.drawing/bitmap) из указанного потока данных. |
| [Bitmap(int width, int height, int format)](#Bitmap-int-int-int-) | Инициализирует новый экземпляр класса [Bitmap](../../com.aspose.drawing/bitmap) с указанным размером и форматом. |
| [Bitmap(int width, int height, int stride, int format, int[] data)](#Bitmap-int-int-int-int-int---) | Инициализирует новый экземпляр класса [Bitmap](../../com.aspose.drawing/bitmap) с указанным размером и пиксельными данными. |
| [Bitmap(Image original)](#Bitmap-com.aspose.drawing.Image-) | Инициализирует новый экземпляр класса [Bitmap](../../com.aspose.drawing/bitmap) из указанного существующего изображения. |
| [Bitmap(Image original, Size newSize)](#Bitmap-com.aspose.drawing.Image-com.aspose.drawing.Size-) | Инициализирует новый экземпляр класса [Bitmap](../../com.aspose.drawing/bitmap) из указанного существующего изображения, масштабированного до указанного размера. |
| [Bitmap(Image original, int width, int height)](#Bitmap-com.aspose.drawing.Image-int-int-) | Инициализирует новый экземпляр класса [Bitmap](../../com.aspose.drawing/bitmap) из указанного существующего изображения, масштабированного до указанного размера. |
## Методы

| Метод | Описание |
| --- | --- |
| [getWidth()](#getWidth--) | Получает ширину, в пикселях, этого Bitmap. |
| [getHeight()](#getHeight--) | Получает высоту, в пикселях, этого Bitmap. |
| [getRawFormat()](#getRawFormat--) | Получает формат файла этого [Image](../../com.aspose.drawing/image). |
| [getPixelFormat()](#getPixelFormat--) | Получает пиксельный формат этого [Image](../../com.aspose.drawing/image). |
| [getPalette()](#getPalette--) | Получает или задает цветовую палитру, используемую для этого [Image](../../com.aspose.drawing/image). |
| [setPalette(ColorPalette value)](#setPalette-com.aspose.drawing.imaging.ColorPalette-) | Получает или задает цветовую палитру, используемую для этого [Image](../../com.aspose.drawing/image). |
| [getFrameDimensionsList()](#getFrameDimensionsList--) | Получает массив GUID, представляющих размеры кадров внутри этого [Image](../../com.aspose.drawing/image). |
| [getPropertyIdList()](#getPropertyIdList--) | Получает идентификаторы элементов свойств, хранящихся в этом [Image](../../com.aspose.drawing/image). |
| [getPropertyItems()](#getPropertyItems--) | Получает все элементы свойств (части метаданных), хранящиеся в этом [Image](../../com.aspose.drawing/image). |
| [deepClone(Rectangle rect, int format)](#deepClone-com.aspose.drawing.Rectangle-int-) | Создаёт копию части этого [Bitmap](../../com.aspose.drawing/bitmap), определённой структурой [Rectangle](../../com.aspose.drawing/rectangle) и с указанным перечислением `PixelFormat`([Image.getPixelFormat](../../com.aspose.drawing/image\#getPixelFormat)). |
| [deepClone(RectangleF rect, int format)](#deepClone-com.aspose.drawing.RectangleF-int-) | Создаёт копию части этого [Bitmap](../../com.aspose.drawing/bitmap), определённой с указанным перечислением [PixelFormat](../../com.aspose.drawing.imaging/pixelformat). |
| [setResolution(float xDpi, float yDpi)](#setResolution-float-float-) | Устанавливает разрешение для этого [Bitmap](../../com.aspose.drawing/bitmap). |
| [lockBits(Rectangle rect, int flags, int format)](#lockBits-com.aspose.drawing.Rectangle-int-int-) | Блокирует [Bitmap](../../com.aspose.drawing/bitmap) в системной памяти. |
| [unlockBits(BitmapData bitmapData)](#unlockBits-com.aspose.drawing.imaging.BitmapData-) | Разблокирует этот [Bitmap](../../com.aspose.drawing/bitmap) из системной памяти. |
| [getPixel(int x, int y)](#getPixel-int-int-) | Получает цвет указанного пикселя в этом [Bitmap](../../com.aspose.drawing/bitmap). |
| [setPixel(int x, int y, Color color)](#setPixel-int-int-com.aspose.drawing.Color-) | Устанавливает цвет указанного пикселя в этом [Bitmap](../../com.aspose.drawing/bitmap). |
| [readArgb32Pixels(int[] pixels)](#readArgb32Pixels-int---) | Считывает пиксели bitmap в формате ARGB32 в заданный массив. |
| [writeArgb32Pixels(int[] pixels)](#writeArgb32Pixels-int---) | Записывает пиксели в bitmap. |
| [makeTransparent()](#makeTransparent--) | Делает указанный цвет прозрачным для этого [Bitmap](../../com.aspose.drawing/bitmap). |
| [makeTransparent(Color transparentColor)](#makeTransparent-com.aspose.drawing.Color-) | Делает указанный цвет прозрачным для этого [Bitmap](../../com.aspose.drawing/bitmap). |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | Этот метод вращает, отражает или вращает и отражает [Image](../../com.aspose.drawing/image). |
| [getPropertyItem(int propid)](#getPropertyItem-int-) | Получает указанный элемент свойства из этого [Image](../../com.aspose.drawing/image). |
| [removePropertyItem(int propid)](#removePropertyItem-int-) | Удаляет указанный элемент свойства из этого [Image](../../com.aspose.drawing/image). |
| [setPropertyItem(PropertyItem propitem)](#setPropertyItem-com.aspose.drawing.imaging.PropertyItem-) | Сохраняет элемент свойства (часть метаданных) в этом [Image](../../com.aspose.drawing/image). |
### Bitmap(int width, int height) {#Bitmap-int-int-}
```
public Bitmap(int width, int height)
```


Инициализирует новый экземпляр класса [Bitmap](../../com.aspose.drawing/bitmap) с указанным размером.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| width | int | Ширина, в пикселях, нового Bitmap. |
|  | height | int | Высота, в пикселях, нового Bitmap. |

--------------------

Единственный поддерживаемый внутренний формат bitmap на данный момент эквивалентен `PixelFormat.Format32bppPArgb`. |

### Bitmap(String filename) {#Bitmap-java.lang.String-}
```
public Bitmap(String filename)
```


Инициализирует новый экземпляр класса [Bitmap](../../com.aspose.drawing/bitmap) из указанного файла.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| filename | java.lang.String | Имя файла bitmap. |

### Bitmap(String filename, boolean useIcm) {#Bitmap-java.lang.String-boolean-}
```
public Bitmap(String filename, boolean useIcm)
```


Инициализирует новый экземпляр класса [Bitmap](../../com.aspose.drawing/bitmap) из указанного файла.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| filename | java.lang.String | Имя файла bitmap. |
| useIcm | boolean | true, чтобы использовать коррекцию цвета для этого [Bitmap](../../com.aspose.drawing/bitmap); иначе false. |

### Bitmap(InputStream stream) {#Bitmap-java.io.InputStream-}
```
public Bitmap(InputStream stream)
```


Инициализирует новый экземпляр класса [Bitmap](../../com.aspose.drawing/bitmap) из указанного потока данных.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Поток данных, используемый для загрузки изображения. |

### Bitmap(InputStream stream, boolean useIcm) {#Bitmap-java.io.InputStream-boolean-}
```
public Bitmap(InputStream stream, boolean useIcm)
```


Инициализирует новый экземпляр класса [Bitmap](../../com.aspose.drawing/bitmap) из указанного потока данных.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Поток данных, используемый для загрузки изображения. |
| useIcm | boolean | `true` чтобы использовать коррекцию цвета для этого [Bitmap](../../com.aspose.drawing/bitmap); иначе `false`. |

### Bitmap(int width, int height, int format) {#Bitmap-int-int-int-}
```
public Bitmap(int width, int height, int format)
```


Инициализирует новый экземпляр класса [Bitmap](../../com.aspose.drawing/bitmap) с указанным размером и форматом.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| width | int | Ширина, в пикселях, нового [Bitmap](../../com.aspose.drawing/bitmap). |
| height | int | Высота, в пикселях, нового [Bitmap](../../com.aspose.drawing/bitmap). |
| format | int | Перечисление `PixelFormat`([Image.getPixelFormat](../../com.aspose.drawing/image\#getPixelFormat)) для нового [Bitmap](../../com.aspose.drawing/bitmap). |

### Bitmap(int width, int height, int stride, int format, int[] data) {#Bitmap-int-int-int-int-int---}
```
public Bitmap(int width, int height, int stride, int format, int[] data)
```


Инициализирует новый экземпляр класса [Bitmap](../../com.aspose.drawing/bitmap) с указанным размером и пиксельными данными.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| width | int | Ширина, в пикселях, нового [Bitmap](../../com.aspose.drawing/bitmap). |
| height | int | Высота, в пикселях, нового [Bitmap](../../com.aspose.drawing/bitmap). |
| stride | int | Смещение в байтах между началом одной строки сканирования и следующей, должно быть кратным четырём. |
| format | int | Перечисление `PixelFormat`([Image.getPixelFormat](../../com.aspose.drawing/image\#getPixelFormat)) для нового [Bitmap](../../com.aspose.drawing/bitmap). |
| данные | int[] | Данные пикселей. |

### Bitmap(Image original) {#Bitmap-com.aspose.drawing.Image-}
```
public Bitmap(Image original)
```


Инициализирует новый экземпляр класса [Bitmap](../../com.aspose.drawing/bitmap) из указанного существующего изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| original | [Image](../../com.aspose.drawing/image) | Из [Image](../../com.aspose.drawing/image), из которого создать новый [Bitmap](../../com.aspose.drawing/bitmap). |

### Bitmap(Image original, Size newSize) {#Bitmap-com.aspose.drawing.Image-com.aspose.drawing.Size-}
```
public Bitmap(Image original, Size newSize)
```


Инициализирует новый экземпляр класса [Bitmap](../../com.aspose.drawing/bitmap) из указанного существующего изображения, масштабированного до указанного размера.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| original | [Image](../../com.aspose.drawing/image) | Из [Image](../../com.aspose.drawing/image), из которого создать новый [Bitmap](../../com.aspose.drawing/bitmap). |
| newSize | [Size](../../com.aspose.drawing/size) | Структура `Size`([Image.getSize](../../com.aspose.drawing/image\#getSize)) представляет размер нового [Bitmap](../../com.aspose.drawing/bitmap). |

### Bitmap(Image original, int width, int height) {#Bitmap-com.aspose.drawing.Image-int-int-}
```
public Bitmap(Image original, int width, int height)
```


Инициализирует новый экземпляр класса [Bitmap](../../com.aspose.drawing/bitmap) из указанного существующего изображения, масштабированного до указанного размера.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| original | [Image](../../com.aspose.drawing/image) | Из [Image](../../com.aspose.drawing/image), из которого создать новый [Bitmap](../../com.aspose.drawing/bitmap). |
| width | int | Ширина, в пикселях, нового [Bitmap](../../com.aspose.drawing/bitmap). |
| height | int | Высота, в пикселях, нового [Bitmap](../../com.aspose.drawing/bitmap). |

### getWidth() {#getWidth--}
```
public int getWidth()
```


Получает ширину, в пикселях, этого Bitmap.

**Returns:**
int
### getHeight() {#getHeight--}
```
public int getHeight()
```


Получает высоту, в пикселях, этого Bitmap.

**Returns:**
int
### getRawFormat() {#getRawFormat--}
```
public ImageFormat getRawFormat()
```


Получает формат файла этого [Image](../../com.aspose.drawing/image).

**Returns:**
[ImageFormat](../../com.aspose.drawing.imaging/imageformat) - The [ImageFormat](../../com.aspose.drawing.imaging/imageformat) that represents the file format of this [Image](../../com.aspose.drawing/image).
### getPixelFormat() {#getPixelFormat--}
```
public int getPixelFormat()
```


Получает пиксельный формат этого [Image](../../com.aspose.drawing/image).

**Returns:**
int — `PixelFormat`([Image.getPixelFormat](../../com.aspose.drawing/image\#getPixelFormat)) , представляющий формат пикселей для этого [Image](../../com.aspose.drawing/image).
### getPalette() {#getPalette--}
```
public ColorPalette getPalette()
```


Получает или задает цветовую палитру, используемую для этого [Image](../../com.aspose.drawing/image).

**Returns:**
[ColorPalette](../../com.aspose.drawing.imaging/colorpalette) - A [ColorPalette](../../com.aspose.drawing.imaging/colorpalette) that represents the color palette used for this [Image](../../com.aspose.drawing/image).
### setPalette(ColorPalette value) {#setPalette-com.aspose.drawing.imaging.ColorPalette-}
```
public void setPalette(ColorPalette value)
```


Получает или задает цветовую палитру, используемую для этого [Image](../../com.aspose.drawing/image).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [ColorPalette](../../com.aspose.drawing.imaging/colorpalette) |  |

### getFrameDimensionsList() {#getFrameDimensionsList--}
```
public UUID[] getFrameDimensionsList()
```


Получает массив GUID, представляющих размеры кадров внутри этого [Image](../../com.aspose.drawing/image).

**Returns:**
java.util.UUID[] — массив GUID, определяющих размеры кадров внутри этого [Image](../../com.aspose.drawing/image) от старшего к младшему.
### getPropertyIdList() {#getPropertyIdList--}
```
public int[] getPropertyIdList()
```


Получает идентификаторы элементов свойств, хранящихся в этом [Image](../../com.aspose.drawing/image).

**Returns:**
int[] — массив идентификаторов свойств, по одному для каждого свойства, хранящегося в этом изображении.
### getPropertyItems() {#getPropertyItems--}
```
public PropertyItem[] getPropertyItems()
```


Получает все элементы свойств (части метаданных), хранящиеся в этом [Image](../../com.aspose.drawing/image).

**Returns:**
com.aspose.drawing.imaging.PropertyItem[] — массив объектов [PropertyItem](../../com.aspose.drawing.imaging/propertyitem), по одному для каждого свойства, хранящегося в изображении.
### deepClone(Rectangle rect, int format) {#deepClone-com.aspose.drawing.Rectangle-int-}
```
public final Bitmap deepClone(Rectangle rect, int format)
```


Создаёт копию части этого [Bitmap](../../com.aspose.drawing/bitmap), определённой структурой [Rectangle](../../com.aspose.drawing/rectangle) и с указанным перечислением `PixelFormat`([Image.getPixelFormat](../../com.aspose.drawing/image\#getPixelFormat)).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | Определяет часть этого [Bitmap](../../com.aspose.drawing/bitmap) для копирования. Координаты относительно этого [Bitmap](../../com.aspose.drawing/bitmap). |
| format | int | Указывает перечисление `PixelFormat`([Image.getPixelFormat](../../com.aspose.drawing/image\#getPixelFormat)) для целевого [Bitmap](../../com.aspose.drawing/bitmap). |

**Returns:**
[Bitmap](../../com.aspose.drawing/bitmap) - The new [Bitmap](../../com.aspose.drawing/bitmap) that this method creates.
### deepClone(RectangleF rect, int format) {#deepClone-com.aspose.drawing.RectangleF-int-}
```
public final Bitmap deepClone(RectangleF rect, int format)
```


Создаёт копию части этого [Bitmap](../../com.aspose.drawing/bitmap), определённой с указанным перечислением [PixelFormat](../../com.aspose.drawing.imaging/pixelformat).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | Определяет часть этого [Bitmap](../../com.aspose.drawing/bitmap) для копирования. |
| format | int | Указывает перечисление [PixelFormat](../../com.aspose.drawing.imaging/pixelformat) для целевого [Bitmap](../../com.aspose.drawing/bitmap). |

**Returns:**
[Bitmap](../../com.aspose.drawing/bitmap) - The [Bitmap](../../com.aspose.drawing/bitmap) that this method creates.
### setResolution(float xDpi, float yDpi) {#setResolution-float-float-}
```
public final void setResolution(float xDpi, float yDpi)
```


Устанавливает разрешение для этого [Bitmap](../../com.aspose.drawing/bitmap).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| xDpi | float | Горизонтальное разрешение в точках на дюйм для [Bitmap](../../com.aspose.drawing/bitmap). |
| yDpi | float | Вертикальное разрешение в точках на дюйм для [Bitmap](../../com.aspose.drawing/bitmap). |

### lockBits(Rectangle rect, int flags, int format) {#lockBits-com.aspose.drawing.Rectangle-int-int-}
```
public final BitmapData lockBits(Rectangle rect, int flags, int format)
```


Блокирует [Bitmap](../../com.aspose.drawing/bitmap) в системной памяти.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | Структура [Rectangle](../../com.aspose.drawing/rectangle) указывает часть [Bitmap](../../com.aspose.drawing/bitmap), которую следует заблокировать. |
| flags | int | Перечисление [ImageLockMode](../../com.aspose.drawing.imaging/imagelockmode) указывает уровень доступа (чтение/запись) для [Bitmap](../../com.aspose.drawing/bitmap). |
| format | int | Перечисление `PixelFormat`([Image.getPixelFormat](../../com.aspose.drawing/image\#getPixelFormat)) указывает формат данных этого [Bitmap](../../com.aspose.drawing/bitmap). |

**Returns:**
[BitmapData](../../com.aspose.drawing.imaging/bitmapdata) - A [BitmapData](../../com.aspose.drawing.imaging/bitmapdata) containing information about this lock operation.
### unlockBits(BitmapData bitmapData) {#unlockBits-com.aspose.drawing.imaging.BitmapData-}
```
public final void unlockBits(BitmapData bitmapData)
```


Разблокирует этот [Bitmap](../../com.aspose.drawing/bitmap) из системной памяти.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| bitmapData | [BitmapData](../../com.aspose.drawing.imaging/bitmapdata) | [BitmapData](../../com.aspose.drawing.imaging/bitmapdata) указывает информацию о операции блокировки. |

### getPixel(int x, int y) {#getPixel-int-int-}
```
public final Color getPixel(int x, int y)
```


Получает цвет указанного пикселя в этом [Bitmap](../../com.aspose.drawing/bitmap).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | int | Координата x пикселя для получения. |
| y | int | Координата y пикселя для получения. |

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) structure that represents the color of the specified pixel.
### setPixel(int x, int y, Color color) {#setPixel-int-int-com.aspose.drawing.Color-}
```
public final void setPixel(int x, int y, Color color)
```


Устанавливает цвет указанного пикселя в этом [Bitmap](../../com.aspose.drawing/bitmap).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | int | Координата x пикселя для установки. |
| y | int | Координата y пикселя для установки. |
| color | [Color](../../com.aspose.drawing/color) | Структура [Color](../../com.aspose.drawing/color) представляет цвет, который следует назначить указанному пикселю. |

### readArgb32Pixels(int[] pixels) {#readArgb32Pixels-int---}
```
public final void readArgb32Pixels(int[] pixels)
```


Считывает пиксели bitmap в формате ARGB32 в заданный массив.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| пиксели | int[] | Массив для размещения пикселей bitmap. Должен иметь достаточную ёмкость. |

### writeArgb32Pixels(int[] pixels) {#writeArgb32Pixels-int---}
```
public final void writeArgb32Pixels(int[] pixels)
```


Записывает пиксели в bitmap.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| пиксели | int[] | Массив с исходными пикселями в формате ARGB32. Должен иметь достаточную длину. |

### makeTransparent() {#makeTransparent--}
```
public final void makeTransparent()
```


Делает указанный цвет прозрачным для этого [Bitmap](../../com.aspose.drawing/bitmap).

### makeTransparent(Color transparentColor) {#makeTransparent-com.aspose.drawing.Color-}
```
public final void makeTransparent(Color transparentColor)
```


Делает указанный цвет прозрачным для этого [Bitmap](../../com.aspose.drawing/bitmap).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| transparentColor | [Color](../../com.aspose.drawing/color) | Структура [Color](../../com.aspose.drawing/color) представляет цвет, который будет сделан прозрачным. |

### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


Этот метод вращает, отражает или вращает и отражает [Image](../../com.aspose.drawing/image).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rotateFlipType | int | Элемент [RotateFlipType](../../com.aspose.drawing/rotatefliptype), определяющий тип вращения и отражения, применяемый к изображению. |

### getPropertyItem(int propid) {#getPropertyItem-int-}
```
public PropertyItem getPropertyItem(int propid)
```


Получает указанный элемент свойства из этого [Image](../../com.aspose.drawing/image).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| propid | int | Идентификатор свойства, которое нужно получить. |

**Returns:**
[PropertyItem](../../com.aspose.drawing.imaging/propertyitem) - The [PropertyItem](../../com.aspose.drawing.imaging/propertyitem) this method gets.
### removePropertyItem(int propid) {#removePropertyItem-int-}
```
public void removePropertyItem(int propid)
```


Удаляет указанный элемент свойства из этого [Image](../../com.aspose.drawing/image).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| propid | int | Идентификатор свойства, которое нужно удалить. |

### setPropertyItem(PropertyItem propitem) {#setPropertyItem-com.aspose.drawing.imaging.PropertyItem-}
```
public void setPropertyItem(PropertyItem propitem)
```


Сохраняет элемент свойства (часть метаданных) в этом [Image](../../com.aspose.drawing/image).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| propitem | [PropertyItem](../../com.aspose.drawing.imaging/propertyitem) | Объект [PropertyItem](../../com.aspose.drawing.imaging/propertyitem), который будет сохранён. |

