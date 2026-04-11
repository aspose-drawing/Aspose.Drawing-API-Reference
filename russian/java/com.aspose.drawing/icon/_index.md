---
title: Icon
second_title: Справочник API Aspose.Drawing для Java
description: Представляет значок Windows, который является небольшим растровым изображением, используемым для представления объекта.
type: docs
weight: 29
url: /ru/java/com.aspose.drawing/icon/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.ms.System.IDisposable
```
public final class Icon implements System.ICloneable, System.IDisposable
```

Представляет значок Windows, который является небольшим растровым изображением, используемым для представления объекта. Значки можно рассматривать как прозрачные битмапы, хотя их размер определяется системой.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Icon(String fileName)](#Icon-java.lang.String-) | Создаёт новый экземпляр класса [Icon](../../com.aspose.drawing/icon) из указанного имени файла. |
| [Icon(InputStream stream)](#Icon-java.io.InputStream-) | Создаёт новый экземпляр класса [Icon](../../com.aspose.drawing/icon) из указанного потока данных. |
| [Icon(String fileName, Size size)](#Icon-java.lang.String-com.aspose.drawing.Size-) | Создаёт новый экземпляр класса [Icon](../../com.aspose.drawing/icon) указанного размера из указанного файла. |
| [Icon(Icon original, Size size)](#Icon-com.aspose.drawing.Icon-com.aspose.drawing.Size-) | Создаёт новый экземпляр класса [Icon](../../com.aspose.drawing/icon) и пытается найти версию значка, соответствующую запрошенному размеру. |
| [Icon(Object type, String resource)](#Icon-java.lang.Object-java.lang.String-) | Создаёт новый экземпляр класса [Icon](../../com.aspose.drawing/icon) из ресурса в указанной сборке. |
| [Icon(InputStream stream, Size size)](#Icon-java.io.InputStream-com.aspose.drawing.Size-) | Создаёт новый экземпляр класса [Icon](../../com.aspose.drawing/icon) указанного размера из указанного потока. |
| [Icon(String fileName, int width, int height)](#Icon-java.lang.String-int-int-) | Инициализирует новый экземпляр класса [Icon](../../com.aspose.drawing/icon) с указанной шириной и высотой из указанного файла. |
| [Icon(Icon original, int width, int height)](#Icon-com.aspose.drawing.Icon-int-int-) | Инициализирует новый экземпляр класса [Icon](../../com.aspose.drawing/icon) и пытается найти версию значка, соответствующую запрошенному размеру. |
| [Icon(InputStream stream, int width, int height)](#Icon-java.io.InputStream-int-int-) | Инициализирует новый экземпляр класса [Icon](../../com.aspose.drawing/icon) из указанного потока данных и с указанными шириной и высотой. |
## Методы

| Метод | Описание |
| --- | --- |
| [getHandle()](#getHandle--) | Получает дескриптор для этого [Icon](../../com.aspose.drawing/icon). |
| [getHeight()](#getHeight--) | Получает высоту этого [Icon](../../com.aspose.drawing/icon). |
| [getSize()](#getSize--) | Получает размер этого [Icon](../../com.aspose.drawing/icon). |
| [getWidth()](#getWidth--) | Получает ширину этого [Icon](../../com.aspose.drawing/icon). |
| [extractAssociatedIcon(String filePath)](#extractAssociatedIcon-java.lang.String-) | Возвращает представление значка изображения, содержащегося в указанном файле. |
| [fromHandle(byte[] handle)](#fromHandle-byte---) | Создаёт GDI+ [Icon](../../com.aspose.drawing/icon) из указанного дескриптора Windows для значка (HICON). |
| [deepClone()](#deepClone--) | Клонирует [Icon](../../com.aspose.drawing/icon), создавая дублирующее изображение. |
| [dispose()](#dispose--) | Выполняет задачи, определённые приложением, связанные с освобождением, выпуском или сбросом неуправляемых ресурсов. |
| [save(OutputStream outputStream)](#save-java.io.OutputStream-) | Сохраняет этот [Icon](../../com.aspose.drawing/icon) в указанный выходной java.io.InputStream. |
| [toBitmap()](#toBitmap--) | Преобразует этот [Icon](../../com.aspose.drawing/icon) в GDI+ [Bitmap](../../com.aspose.drawing/bitmap). |
| [toString()](#toString--) | Получает человекочитаемую строку, описывающую [Icon](../../com.aspose.drawing/icon). |
### Icon(String fileName) {#Icon-java.lang.String-}
```
public Icon(String fileName)
```


Создаёт новый экземпляр класса [Icon](../../com.aspose.drawing/icon) из указанного имени файла.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fileName | java.lang.String | Файл, из которого загружается [Icon](../../com.aspose.drawing/icon). |

### Icon(InputStream stream) {#Icon-java.io.InputStream-}
```
public Icon(InputStream stream)
```


Создаёт новый экземпляр класса [Icon](../../com.aspose.drawing/icon) из указанного потока данных.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Поток данных, из которого загружается [Icon](../../com.aspose.drawing/icon). |

### Icon(String fileName, Size size) {#Icon-java.lang.String-com.aspose.drawing.Size-}
```
public Icon(String fileName, Size size)
```


Создаёт новый экземпляр класса [Icon](../../com.aspose.drawing/icon) указанного размера из указанного файла.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fileName | java.lang.String | Имя и путь к файлу, содержащему данные значка. |
| size | [Size](../../com.aspose.drawing/size) | Желаемый размер значка. |

### Icon(Icon original, Size size) {#Icon-com.aspose.drawing.Icon-com.aspose.drawing.Size-}
```
public Icon(Icon original, Size size)
```


Создаёт новый экземпляр класса [Icon](../../com.aspose.drawing/icon) и пытается найти версию значка, соответствующую запрошенному размеру.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| original | [Icon](../../com.aspose.drawing/icon) | [Icon](../../com.aspose.drawing/icon), из которого загружается значок нового размера. |
| size | [Size](../../com.aspose.drawing/size) | Структура `Size`([.getSize](../../null/\#getSize)), указывающая высоту и ширину нового [Icon](../../com.aspose.drawing/icon). |

### Icon(Object type, String resource) {#Icon-java.lang.Object-java.lang.String-}
```
public Icon(Object type, String resource)
```


Создаёт новый экземпляр класса [Icon](../../com.aspose.drawing/icon) из ресурса в указанной сборке.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| тип | java.lang.Object | Тип, указывающий сборку, в которой искать ресурс. |
| ресурс | java.lang.String | Имя ресурса для загрузки. |

### Icon(InputStream stream, Size size) {#Icon-java.io.InputStream-com.aspose.drawing.Size-}
```
public Icon(InputStream stream, Size size)
```


Создаёт новый экземпляр класса [Icon](../../com.aspose.drawing/icon) указанного размера из указанного потока.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Поток, содержащий данные значка. |
| size | [Size](../../com.aspose.drawing/size) | Желаемый размер значка. |

### Icon(String fileName, int width, int height) {#Icon-java.lang.String-int-int-}
```
public Icon(String fileName, int width, int height)
```


Инициализирует новый экземпляр класса [Icon](../../com.aspose.drawing/icon) с указанной шириной и высотой из указанного файла.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fileName | java.lang.String | Имя и путь к файлу, содержащему данные [Icon](../../com.aspose.drawing/icon). |
| width | int | Желаемая ширина [Icon](../../com.aspose.drawing/icon). |
| height | int | Желаемая высота [Icon](../../com.aspose.drawing/icon). |

### Icon(Icon original, int width, int height) {#Icon-com.aspose.drawing.Icon-int-int-}
```
public Icon(Icon original, int width, int height)
```


Инициализирует новый экземпляр класса [Icon](../../com.aspose.drawing/icon) и пытается найти версию значка, соответствующую запрошенному размеру.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| original | [Icon](../../com.aspose.drawing/icon) | Иконка, из которой загружать другой размер. |
| width | int | Ширина новой иконки. |
| height | int | Высота новой иконки. |

### Icon(InputStream stream, int width, int height) {#Icon-java.io.InputStream-int-int-}
```
public Icon(InputStream stream, int width, int height)
```


Инициализирует новый экземпляр класса [Icon](../../com.aspose.drawing/icon) из указанного потока данных и с указанными шириной и высотой.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Поток данных, из которого загружать иконку. |
| width | int | Ширина иконки в пикселях. |
| height | int | Высота иконки в пикселях. |

### getHandle() {#getHandle--}
```
public System.IntPtr getHandle()
```


Получает дескриптор для этой [Icon](../../com.aspose.drawing/icon). Это не копия дескриптора; не освобождайте его.

Значение: Дескриптор Windows для иконки.

**Returns:**
com.aspose.ms.System.IntPtr
### getHeight() {#getHeight--}
```
public int getHeight()
```


Получает высоту этого [Icon](../../com.aspose.drawing/icon).

Значение: Высота этой [Icon](../../com.aspose.drawing/icon).

**Returns:**
int
### getSize() {#getSize--}
```
public Size getSize()
```


Получает размер этого [Icon](../../com.aspose.drawing/icon).

Значение: Структура `Size`([.getSize](../../null/\#getSize)), задающая ширину и высоту этой [Icon](../../com.aspose.drawing/icon).

**Returns:**
[Size](../../com.aspose.drawing/size)
### getWidth() {#getWidth--}
```
public int getWidth()
```


Получает ширину этого [Icon](../../com.aspose.drawing/icon).

Значение: Ширина этой [Icon](../../com.aspose.drawing/icon).

**Returns:**
int
### extractAssociatedIcon(String filePath) {#extractAssociatedIcon-java.lang.String-}
```
public static Icon extractAssociatedIcon(String filePath)
```


Возвращает представление значка изображения, содержащегося в указанном файле.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | java.lang.String | Путь к файлу, содержащему изображение. |

**Returns:**
[Icon](../../com.aspose.drawing/icon) - The [Icon](../../com.aspose.drawing/icon) representation of the image that is contained in the specified file.
### fromHandle(byte[] handle) {#fromHandle-byte---}
```
public static Icon fromHandle(byte[] handle)
```


Создаёт GDI+ [Icon](../../com.aspose.drawing/icon) из указанного дескриптора Windows для значка (HICON).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| дескриптор | byte[] | Дескриптор Windows для иконки. |

**Returns:**
[Icon](../../com.aspose.drawing/icon) - The [Icon](../../com.aspose.drawing/icon) this method creates.
### deepClone() {#deepClone--}
```
public Object deepClone()
```


Клонирует [Icon](../../com.aspose.drawing/icon), создавая дублирующее изображение.

**Returns:**
java.lang.Object — объект, который можно привести к типу [Icon](../../com.aspose.drawing/icon).
### dispose() {#dispose--}
```
public void dispose()
```


Выполняет задачи, определённые приложением, связанные с освобождением, выпуском или сбросом неуправляемых ресурсов.

### save(OutputStream outputStream) {#save-java.io.OutputStream-}
```
public void save(OutputStream outputStream)
```


Сохраняет этот [Icon](../../com.aspose.drawing/icon) в указанный выходной java.io.InputStream.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| outputStream | java.io.OutputStream | java.io.InputStream для сохранения. |

### toBitmap() {#toBitmap--}
```
public Bitmap toBitmap()
```


Преобразует этот [Icon](../../com.aspose.drawing/icon) в GDI+ [Bitmap](../../com.aspose.drawing/bitmap).

**Returns:**
[Bitmap](../../com.aspose.drawing/bitmap) - A [Bitmap](../../com.aspose.drawing/bitmap) that represents the converted [Icon](../../com.aspose.drawing/icon).
### toString() {#toString--}
```
public String toString()
```


Получает человекочитаемую строку, описывающую [Icon](../../com.aspose.drawing/icon).

**Returns:**
java.lang.String — строка, описывающая [Icon](../../com.aspose.drawing/icon).
