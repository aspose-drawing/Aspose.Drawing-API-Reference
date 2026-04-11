---
title: ImageCodecInfo
second_title: Справочник API Aspose.Drawing для Java
description: Класс предоставляет необходимые члены хранения и методы для получения всей соответствующей информации об установленных кодеках изображений — кодировщиках и декодировщиках.
type: docs
weight: 25
url: /ru/java/com.aspose.drawing.imaging/imagecodecinfo/
---
**Inheritance:**
java.lang.Object
```
public final class ImageCodecInfo
```

Класс [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo) предоставляет необходимые члены хранения и методы для получения всей соответствующей информации об установленных кодировщиках и декодировщиках изображений (называемых кодеками). Не наследуемый.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [ImageCodecInfo()](#ImageCodecInfo--) | Инициализирует новый экземпляр класса [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo). |
| [ImageCodecInfo(UUID clsid, String codecName, String filenameExtension, String formatDescription, UUID formatID, String mimeType, int version)](#ImageCodecInfo-java.util.UUID-java.lang.String-java.lang.String-java.lang.String-java.util.UUID-java.lang.String-int-) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getClsid()](#getClsid--) | Возвращает структуру java.util.UUID, содержащую GUID, идентифицирующий конкретный кодек. |
| [setClsid(UUID value)](#setClsid-java.util.UUID-) | Устанавливает структуру java.util.UUID, содержащую GUID, идентифицирующий конкретный кодек. |
| [getFormatID()](#getFormatID--) | Возвращает структуру java.util.UUID, содержащую GUID, идентифицирующий формат кодека. |
| [setFormatID(UUID value)](#setFormatID-java.util.UUID-) | Устанавливает структуру java.util.UUID, содержащую GUID, идентифицирующий формат кодека. |
| [getCodecName()](#getCodecName--) | Получает или задает строку, содержащую название кодека. |
| [setCodecName(String value)](#setCodecName-java.lang.String-) | Получает или задает строку, содержащую название кодека. |
| [getFormatDescription()](#getFormatDescription--) | Получает или задает строку, описывающую файловый формат кодека. |
| [setFormatDescription(String value)](#setFormatDescription-java.lang.String-) | Получает или задает строку, описывающую файловый формат кодека. |
| [getFilenameExtension()](#getFilenameExtension--) | Получает или задает строку, содержащую расширения имени файла, используемые в кодеке. |
| [setFilenameExtension(String value)](#setFilenameExtension-java.lang.String-) | Получает или задает строку, содержащую расширения имени файла, используемые в кодеке. |
| [getMimeType()](#getMimeType--) | Получает или задает строку, содержащую тип MIME (Multipurpose Internet Mail Extensions) кодека. |
| [setMimeType(String value)](#setMimeType-java.lang.String-) | Получает или задает строку, содержащую тип MIME (Multipurpose Internet Mail Extensions) кодека. |
| [getVersion()](#getVersion--) | Получает или задает номер версии кодека. |
| [setVersion(int value)](#setVersion-int-) | Получает или задает номер версии кодека. |
| [getSignaturePatterns()](#getSignaturePatterns--) | Получает или задает двумерный массив байтов, представляющий сигнатуру кодека. |
| [setSignaturePatterns(byte[][] value)](#setSignaturePatterns-byte-----) | Получает или задает двумерный массив байтов, представляющий сигнатуру кодека. |
| [getSignatureMasks()](#getSignatureMasks--) | Получает или задает двумерный массив байтов, который может использоваться в качестве фильтра. |
| [setSignatureMasks(byte[][] value)](#setSignatureMasks-byte-----) | Получает или задает двумерный массив байтов, который может использоваться в качестве фильтра. |
| [getImageDecoders()](#getImageDecoders--) | Возвращает массив объектов [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo), содержащих информацию о декодерах изображений, встроенных в GDI+. |
| [getImageEncoders()](#getImageEncoders--) | Возвращает массив объектов [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo), содержащих информацию о кодировщиках изображений, встроенных в GDI+. |
### ImageCodecInfo() {#ImageCodecInfo--}
```
public ImageCodecInfo()
```


Инициализирует новый экземпляр класса [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo).

### ImageCodecInfo(UUID clsid, String codecName, String filenameExtension, String formatDescription, UUID formatID, String mimeType, int version) {#ImageCodecInfo-java.util.UUID-java.lang.String-java.lang.String-java.lang.String-java.util.UUID-java.lang.String-int-}
```
public ImageCodecInfo(UUID clsid, String codecName, String filenameExtension, String formatDescription, UUID formatID, String mimeType, int version)
```


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| clsid | java.util.UUID |  |
| codecName | java.lang.String |  |
| filenameExtension | java.lang.String |  |
| formatDescription | java.lang.String |  |
| formatID | java.util.UUID |  |
| mimeType | java.lang.String |  |
| version | int |  |

### getClsid() {#getClsid--}
```
public UUID getClsid()
```


Возвращает структуру java.util.UUID, содержащую GUID, идентифицирующий конкретный кодек.

**Returns:**
java.util.UUID - java.util.UUID
### setClsid(UUID value) {#setClsid-java.util.UUID-}
```
public void setClsid(UUID value)
```


Устанавливает структуру java.util.UUID, содержащую GUID, идентифицирующий конкретный кодек.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.util.UUID | java.util.UUID |

### getFormatID() {#getFormatID--}
```
public UUID getFormatID()
```


Возвращает структуру java.util.UUID, содержащую GUID, идентифицирующий формат кодека.

**Returns:**
java.util.UUID - java.util.UUID
### setFormatID(UUID value) {#setFormatID-java.util.UUID-}
```
public void setFormatID(UUID value)
```


Устанавливает структуру java.util.UUID, содержащую GUID, идентифицирующий формат кодека.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.util.UUID | java.util.UUID |

### getCodecName() {#getCodecName--}
```
public String getCodecName()
```


Получает или задает строку, содержащую название кодека.

**Returns:**
java.lang.String
### setCodecName(String value) {#setCodecName-java.lang.String-}
```
public void setCodecName(String value)
```


Получает или задает строку, содержащую название кодека.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getFormatDescription() {#getFormatDescription--}
```
public String getFormatDescription()
```


Получает или задает строку, описывающую файловый формат кодека.

**Returns:**
java.lang.String
### setFormatDescription(String value) {#setFormatDescription-java.lang.String-}
```
public void setFormatDescription(String value)
```


Получает или задает строку, описывающую файловый формат кодека.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getFilenameExtension() {#getFilenameExtension--}
```
public String getFilenameExtension()
```


Получает или задает строку, содержащую расширения имени файла, используемые в кодеке. Расширения разделяются точками с запятой.

**Returns:**
java.lang.String
### setFilenameExtension(String value) {#setFilenameExtension-java.lang.String-}
```
public void setFilenameExtension(String value)
```


Получает или задает строку, содержащую расширения имени файла, используемые в кодеке. Расширения разделяются точками с запятой.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getMimeType() {#getMimeType--}
```
public String getMimeType()
```


Получает или задает строку, содержащую тип MIME (Multipurpose Internet Mail Extensions) кодека.

**Returns:**
java.lang.String
### setMimeType(String value) {#setMimeType-java.lang.String-}
```
public void setMimeType(String value)
```


Получает или задает строку, содержащую тип MIME (Multipurpose Internet Mail Extensions) кодека.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getVersion() {#getVersion--}
```
public int getVersion()
```


Получает или задает номер версии кодека.

**Returns:**
int
### setVersion(int value) {#setVersion-int-}
```
public void setVersion(int value)
```


Получает или задает номер версии кодека.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getSignaturePatterns() {#getSignaturePatterns--}
```
public byte[][] getSignaturePatterns()
```


Получает или задает двумерный массив байтов, представляющий сигнатуру кодека.

**Returns:**
byte[][]
### setSignaturePatterns(byte[][] value) {#setSignaturePatterns-byte-----}
```
public void setSignaturePatterns(byte[][] value)
```


Получает или задает двумерный массив байтов, представляющий сигнатуру кодека.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte[][] |  |

### getSignatureMasks() {#getSignatureMasks--}
```
public byte[][] getSignatureMasks()
```


Получает или задает двумерный массив байтов, который может использоваться в качестве фильтра.

**Returns:**
byte[][]
### setSignatureMasks(byte[][] value) {#setSignatureMasks-byte-----}
```
public void setSignatureMasks(byte[][] value)
```


Получает или задает двумерный массив байтов, который может использоваться в качестве фильтра.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte[][] |  |

### getImageDecoders() {#getImageDecoders--}
```
public static ImageCodecInfo[] getImageDecoders()
```


Возвращает массив объектов [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo), содержащих информацию о декодерах изображений, встроенных в GDI+.

**Returns:**
com.aspose.drawing.imaging.ImageCodecInfo[] — массив объектов [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo). Каждый объект [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo) в массиве содержит информацию об одном из встроенных декодеров изображений.
### getImageEncoders() {#getImageEncoders--}
```
public static ImageCodecInfo[] getImageEncoders()
```


Возвращает массив объектов [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo), содержащих информацию о кодировщиках изображений, встроенных в GDI+.

**Returns:**
com.aspose.drawing.imaging.ImageCodecInfo[] — массив объектов [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo). Каждый объект [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo) в массиве содержит информацию об одном из встроенных кодировщиков изображений.
