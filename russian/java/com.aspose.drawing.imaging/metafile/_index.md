---
title: Метaфайл
second_title: Справочник API Aspose.Drawing для Java
description: Определяет графический метафайл.
type: docs
weight: 30
url: /ru/java/com.aspose.drawing.imaging/metafile/
---
**Inheritance:**
java.lang.Object, [com.aspose.drawing.Image](../../com.aspose.drawing/image)
```
public final class Metafile extends Image
```

Определяет графический метафайл. Метафайл содержит записи, описывающие последовательность графических операций, которые могут быть записаны (созданы) и воспроизведены (отображены). Этот класс не наследуем.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Metafile(byte[] henhmetafile, boolean deleteEmf)](#Metafile-byte---boolean-) | Инициализирует новый экземпляр класса [Metafile](../../com.aspose.drawing.imaging/metafile) из указанного дескриптора. |
| [Metafile(byte[] referenceHdc, int emfType)](#Metafile-byte---int-) | Инициализирует новый экземпляр класса [Metafile](../../com.aspose.drawing.imaging/metafile) из указанного дескриптора контекста устройства и перечисления [EmfType](../../com.aspose.drawing.imaging/emftype), которое определяет формат [Metafile](../../com.aspose.drawing.imaging/metafile). |
| [Metafile(String filename)](#Metafile-java.lang.String-) | Инициализирует новый экземпляр класса [Metafile](../../com.aspose.drawing.imaging/metafile) из указанного имени файла. |
| [Metafile(String filename, byte[] referenceHdc)](#Metafile-java.lang.String-byte---) | Инициализирует новый экземпляр класса [Metafile](../../com.aspose.drawing.imaging/metafile) из указанного имени файла. |
| [Metafile(InputStream stream)](#Metafile-java.io.InputStream-) | Инициализирует новый экземпляр класса [Metafile](../../com.aspose.drawing.imaging/metafile) из указанного потока данных. |
| [Metafile(InputStream stream, byte[] referenceHdc)](#Metafile-java.io.InputStream-byte---) | Инициализирует новый экземпляр класса [Metafile](../../com.aspose.drawing.imaging/metafile) из указанного потока данных и дескриптора Windows контекста устройства. |
| [Metafile(System.IO.Stream stream, int type)](#Metafile-com.aspose.ms.System.IO.Stream-int-) | Инициализирует новый экземпляр класса [Metafile](../../com.aspose.drawing.imaging/metafile) из указанного потока данных и дескриптора Windows контекста устройства. |
| [Metafile(InputStream stream, byte[] referenceHdc, int type)](#Metafile-java.io.InputStream-byte---int-) | Инициализирует новый экземпляр класса [Metafile](../../com.aspose.drawing.imaging/metafile) из указанного потока данных, дескриптора Windows контекста устройства и перечисления [EmfType](../../com.aspose.drawing.imaging/emftype), которое определяет формат [Metafile](../../com.aspose.drawing.imaging/metafile). |
| [Metafile(InputStream stream, byte[] referenceHdc, RectangleF frameRect, int frameUnit, int type)](#Metafile-java.io.InputStream-byte---com.aspose.drawing.RectangleF-int-int-) | Инициализирует новый экземпляр класса [Metafile](../../com.aspose.drawing.imaging/metafile) из указанного потока данных, дескриптора Windows контекста устройства и перечисления [EmfType](../../com.aspose.drawing.imaging/emftype), которое определяет формат [Metafile](../../com.aspose.drawing.imaging/metafile). |
## Методы

| Метод | Описание |
| --- | --- |
| [getWidth()](#getWidth--) | Получает ширину в пикселях этого [Metafile](../../com.aspose.drawing.imaging/metafile). |
| [getHeight()](#getHeight--) | Получает высоту в пикселях этого [Metafile](../../com.aspose.drawing.imaging/metafile). |
| [getRawFormat()](#getRawFormat--) | Получает формат файла этого [Image](../../com.aspose.drawing/image). |
| [getPixelFormat()](#getPixelFormat--) | Получает пиксельный формат этого [Image](../../com.aspose.drawing/image). |
| [getPalette()](#getPalette--) | Получает или задает цветовую палитру, используемую для этого [Image](../../com.aspose.drawing/image). |
| [setPalette(ColorPalette value)](#setPalette-com.aspose.drawing.imaging.ColorPalette-) | Получает или задает цветовую палитру, используемую для этого [Image](../../com.aspose.drawing/image). |
| [getFrameDimensionsList()](#getFrameDimensionsList--) | Получает массив GUID, представляющих размеры кадров внутри этого [Image](../../com.aspose.drawing/image). |
| [getPropertyIdList()](#getPropertyIdList--) | Получает идентификаторы элементов свойств, хранящихся в этом [Image](../../com.aspose.drawing/image). |
| [getPropertyItems()](#getPropertyItems--) | Получает все элементы свойств (части метаданных), хранящиеся в этом [Image](../../com.aspose.drawing/image). |
| [getMetafileHeader(InputStream stream)](#getMetafileHeader-java.io.InputStream-) | Возвращает [MetafileHeader](../../com.aspose.drawing.imaging/metafileheader), связанный с указанным [Metafile](../../com.aspose.drawing.imaging/metafile). |
| [getMetafileHeader(String fileName)](#getMetafileHeader-java.lang.String-) | Возвращает [MetafileHeader](../../com.aspose.drawing.imaging/metafileheader), связанный с указанным [Metafile](../../com.aspose.drawing.imaging/metafile). |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | Этот метод вращает, отражает или вращает и отражает [Image](../../com.aspose.drawing/image). |
| [getHenhmetafile()](#getHenhmetafile--) | Возвращает дескриптор Windows для расширенного [Metafile](../../com.aspose.drawing.imaging/metafile). |
| [playRecord(int recordType, int flags, int dataSize, byte[] dataArray)](#playRecord-int-int-int-byte---) | Воспроизводит отдельную запись метафайла. |
| [getMetafileHeader()](#getMetafileHeader--) | Возвращает [MetafileHeader](../../com.aspose.drawing.imaging/metafileheader), связанный с этим [Metafile](../../com.aspose.drawing.imaging/metafile). |
| [getPropertyItem(int propid)](#getPropertyItem-int-) | Получает указанный элемент свойства из этого [Image](../../com.aspose.drawing/image). |
| [removePropertyItem(int propid)](#removePropertyItem-int-) | Удаляет указанный элемент свойства из этого [Image](../../com.aspose.drawing/image). |
| [setPropertyItem(PropertyItem propitem)](#setPropertyItem-com.aspose.drawing.imaging.PropertyItem-) | Сохраняет элемент свойства (часть метаданных) в этом [Image](../../com.aspose.drawing/image). |
### Metafile(byte[] henhmetafile, boolean deleteEmf) {#Metafile-byte---boolean-}
```
public Metafile(byte[] henhmetafile, boolean deleteEmf)
```


Инициализирует новый экземпляр класса [Metafile](../../com.aspose.drawing.imaging/metafile) из указанного дескриптора.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| henhmetafile | byte[] | Дескриптор расширенного метафайла. |
| deleteEmf | boolean | true, чтобы удалить дескриптор расширенного метафайла, когда удаляется [Metafile](../../com.aspose.drawing.imaging/metafile); в противном случае — false. |

### Metafile(byte[] referenceHdc, int emfType) {#Metafile-byte---int-}
```
public Metafile(byte[] referenceHdc, int emfType)
```


Инициализирует новый экземпляр класса [Metafile](../../com.aspose.drawing.imaging/metafile) из указанного дескриптора контекста устройства и перечисления [EmfType](../../com.aspose.drawing.imaging/emftype), которое определяет формат [Metafile](../../com.aspose.drawing.imaging/metafile).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| referenceHdc | byte[] | Дескриптор контекста устройства. |
| emfType | int | Объект [EmfType](../../com.aspose.drawing.imaging/emftype), определяющий формат [Metafile](../../com.aspose.drawing.imaging/metafile). |

### Metafile(String filename) {#Metafile-java.lang.String-}
```
public Metafile(String filename)
```


Инициализирует новый экземпляр класса [Metafile](../../com.aspose.drawing.imaging/metafile) из указанного имени файла.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| filename | java.lang.String | Строка, представляющая имя файла, из которого создаётся новый [Metafile](../../com.aspose.drawing.imaging/metafile). |

### Metafile(String filename, byte[] referenceHdc) {#Metafile-java.lang.String-byte---}
```
public Metafile(String filename, byte[] referenceHdc)
```


Инициализирует новый экземпляр класса [Metafile](../../com.aspose.drawing.imaging/metafile) из указанного имени файла.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| filename | java.lang.String | Строка, представляющая имя файла, из которого создаётся новый [Metafile](../../com.aspose.drawing.imaging/metafile). |
| referenceHdc | byte[] | Windows‑дескриптор контекста устройства. |

### Metafile(InputStream stream) {#Metafile-java.io.InputStream-}
```
public Metafile(InputStream stream)
```


Инициализирует новый экземпляр класса [Metafile](../../com.aspose.drawing.imaging/metafile) из указанного потока данных.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | InputStream, из которого создаётся новый [Metafile](../../com.aspose.drawing.imaging/metafile). |

### Metafile(InputStream stream, byte[] referenceHdc) {#Metafile-java.io.InputStream-byte---}
```
public Metafile(InputStream stream, byte[] referenceHdc)
```


Инициализирует новый экземпляр класса [Metafile](../../com.aspose.drawing.imaging/metafile) из указанного потока данных и Windows‑дескриптора контекста устройства. />.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | InputStream, содержащий данные для этого [Metafile](../../com.aspose.drawing.imaging/metafile). |
| referenceHdc | byte[] | Windows‑дескриптор контекста устройства объекта [Metafile](../../com.aspose.drawing.imaging/metafile). |

### Metafile(System.IO.Stream stream, int type) {#Metafile-com.aspose.ms.System.IO.Stream-int-}
```
public Metafile(System.IO.Stream stream, int type)
```


Инициализирует новый экземпляр класса [Metafile](../../com.aspose.drawing.imaging/metafile) из указанного потока данных и Windows‑дескриптора контекста устройства. />.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | InputStream, содержащий данные для этого [Metafile](../../com.aspose.drawing.imaging/metafile). |
| тип | int | должно быть int 1. |

### Metafile(InputStream stream, byte[] referenceHdc, int type) {#Metafile-java.io.InputStream-byte---int-}
```
public Metafile(InputStream stream, byte[] referenceHdc, int type)
```


Инициализирует новый экземпляр класса [Metafile](../../com.aspose.drawing.imaging/metafile) из указанного потока данных, дескриптора Windows контекста устройства и перечисления [EmfType](../../com.aspose.drawing.imaging/emftype), которое определяет формат [Metafile](../../com.aspose.drawing.imaging/metafile).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | InputStream, содержащий данные для этого [Metafile](../../com.aspose.drawing.imaging/metafile). |
| referenceHdc | byte[] | Windows‑дескриптор контекста устройства. |
| type | int | Объект [EmfType](../../com.aspose.drawing.imaging/emftype), определяющий формат [Metafile](../../com.aspose.drawing.imaging/metafile). |

### Metafile(InputStream stream, byte[] referenceHdc, RectangleF frameRect, int frameUnit, int type) {#Metafile-java.io.InputStream-byte---com.aspose.drawing.RectangleF-int-int-}
```
public Metafile(InputStream stream, byte[] referenceHdc, RectangleF frameRect, int frameUnit, int type)
```


Инициализирует новый экземпляр класса [Metafile](../../com.aspose.drawing.imaging/metafile) из указанного потока данных, дескриптора Windows контекста устройства и перечисления [EmfType](../../com.aspose.drawing.imaging/emftype), которое определяет формат [Metafile](../../com.aspose.drawing.imaging/metafile).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | InputStream, содержащий данные для этого [Metafile](../../com.aspose.drawing.imaging/metafile). |
| referenceHdc | byte[] | Windows‑дескриптор контекста устройства. |
| frameRect | [RectangleF](../../com.aspose.drawing/rectanglef) | Объект [Rectangle](../../com.aspose.drawing/rectangle), представляющий прямоугольник, ограничивающий новый [Metafile](../../com.aspose.drawing.imaging/metafile). |
| frameUnit | int | Объект [MetafileFrameUnit](../../com.aspose.drawing.imaging/metafileframeunit), определяющий единицу измерения для frameRect. |
| type | int | Объект [EmfType](../../com.aspose.drawing.imaging/emftype), определяющий формат [Metafile](../../com.aspose.drawing.imaging/metafile). |

### getWidth() {#getWidth--}
```
public int getWidth()
```


Получает ширину в пикселях этого [Metafile](../../com.aspose.drawing.imaging/metafile).

**Returns:**
int
### getHeight() {#getHeight--}
```
public int getHeight()
```


Получает высоту в пикселях этого [Metafile](../../com.aspose.drawing.imaging/metafile).

**Returns:**
int — высота в пикселях этого [Metafile](../../com.aspose.drawing.imaging/metafile).
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
### getMetafileHeader(InputStream stream) {#getMetafileHeader-java.io.InputStream-}
```
public static MetafileHeader getMetafileHeader(InputStream stream)
```


Возвращает [MetafileHeader](../../com.aspose.drawing.imaging/metafileheader), связанный с указанным [Metafile](../../com.aspose.drawing.imaging/metafile).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | InputStream, содержащий [Metafile](../../com.aspose.drawing.imaging/metafile), для которого извлекается заголовок. |

**Returns:**
[MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) - The [MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) associated with the specified [Metafile](../../com.aspose.drawing.imaging/metafile).
### getMetafileHeader(String fileName) {#getMetafileHeader-java.lang.String-}
```
public static MetafileHeader getMetafileHeader(String fileName)
```


Возвращает [MetafileHeader](../../com.aspose.drawing.imaging/metafileheader), связанный с указанным [Metafile](../../com.aspose.drawing.imaging/metafile).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fileName | java.lang.String | Строка, содержащая имя [Metafile](../../com.aspose.drawing.imaging/metafile), для которого извлекается заголовок. |

**Returns:**
[MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) - The [MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) associated with the specified [Metafile](../../com.aspose.drawing.imaging/metafile).
### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


Этот метод вращает, отражает или вращает и отражает [Image](../../com.aspose.drawing/image).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rotateFlipType | int | Элемент [RotateFlipType](../../com.aspose.drawing/rotatefliptype), определяющий тип вращения и отражения, применяемый к изображению. |

### getHenhmetafile() {#getHenhmetafile--}
```
public System.IntPtr getHenhmetafile()
```


Возвращает дескриптор Windows для расширенного [Metafile](../../com.aspose.drawing.imaging/metafile).

**Returns:**
com.aspose.ms.System.IntPtr — Windows‑дескриптор этого расширенного [Metafile](../../com.aspose.drawing.imaging/metafile).
### playRecord(int recordType, int flags, int dataSize, byte[] dataArray) {#playRecord-int-int-int-byte---}
```
public void playRecord(int recordType, int flags, int dataSize, byte[] dataArray)
```


Воспроизводит отдельную запись метафайла.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| recordType | int | Элемент [EmfPlusRecordType](../../com.aspose.drawing.imaging/emfplusrecordtype), который указывает тип воспроизводимой записи метафайла. |
| flags | int | Набор флагов, определяющих атрибуты записи. |
| dataSize | int | Количество байтов в данных записи. |
| dataArray | byte[] | Массив байтов, содержащий данные записи. |

### getMetafileHeader() {#getMetafileHeader--}
```
public MetafileHeader getMetafileHeader()
```


Возвращает [MetafileHeader](../../com.aspose.drawing.imaging/metafileheader), связанный с этим [Metafile](../../com.aspose.drawing.imaging/metafile).

**Returns:**
[MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) - The [MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) associated with this [Metafile](../../com.aspose.drawing.imaging/metafile).
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

