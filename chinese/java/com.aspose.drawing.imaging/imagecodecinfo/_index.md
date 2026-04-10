---
title: ImageCodecInfo
second_title: Aspose.Drawing for Java API 参考
description: 该类提供必要的存储成员和方法，以检索有关已安装的图像编码器和解码器（称为编解码器）的所有相关信息。
type: docs
weight: 25
url: /zh/java/com.aspose.drawing.imaging/imagecodecinfo/
---
**Inheritance:**
java.lang.Object
```
public final class ImageCodecInfo
```

该 [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo) 类提供必要的存储成员和方法，以检索有关已安装图像编码器和解码器（称为编解码器）的所有相关信息。不可继承。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ImageCodecInfo()](#ImageCodecInfo--) | 初始化一个新的 [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo) 类实例。 |
| [ImageCodecInfo(UUID clsid, String codecName, String filenameExtension, String formatDescription, UUID formatID, String mimeType, int version)](#ImageCodecInfo-java.util.UUID-java.lang.String-java.lang.String-java.lang.String-java.util.UUID-java.lang.String-int-) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getClsid()](#getClsid--) | 获取一个包含标识特定编解码器的 GUID 的 java.util.UUID 结构。 |
| [setClsid(UUID value)](#setClsid-java.util.UUID-) | 设置一个包含标识特定编解码器的 GUID 的 java.util.UUID 结构。 |
| [getFormatID()](#getFormatID--) | 获取一个包含标识编解码器格式的 GUID 的 java.util.UUID 结构。 |
| [setFormatID(UUID value)](#setFormatID-java.util.UUID-) | 设置一个包含标识编解码器格式的 GUID 的 java.util.UUID 结构。 |
| [getCodecName()](#getCodecName--) | 获取或设置一个包含编解码器名称的字符串。 |
| [setCodecName(String value)](#setCodecName-java.lang.String-) | 获取或设置一个包含编解码器名称的字符串。 |
| [getFormatDescription()](#getFormatDescription--) | 获取或设置一个描述编解码器文件格式的字符串。 |
| [setFormatDescription(String value)](#setFormatDescription-java.lang.String-) | 获取或设置一个描述编解码器文件格式的字符串。 |
| [getFilenameExtension()](#getFilenameExtension--) | 获取或设置一个包含编解码器使用的文件扩展名的字符串。 |
| [setFilenameExtension(String value)](#setFilenameExtension-java.lang.String-) | 获取或设置一个包含编解码器使用的文件扩展名的字符串。 |
| [getMimeType()](#getMimeType--) | 获取或设置一个包含编解码器的多用途互联网邮件扩展 (MIME) 类型的字符串。 |
| [setMimeType(String value)](#setMimeType-java.lang.String-) | 获取或设置一个包含编解码器的多用途互联网邮件扩展 (MIME) 类型的字符串。 |
| [getVersion()](#getVersion--) | 获取或设置编解码器的版本号。 |
| [setVersion(int value)](#setVersion-int-) | 获取或设置编解码器的版本号。 |
| [getSignaturePatterns()](#getSignaturePatterns--) | 获取或设置一个表示编解码器签名的二维字节数组。 |
| [setSignaturePatterns(byte[][] value)](#setSignaturePatterns-byte-----) | 获取或设置一个表示编解码器签名的二维字节数组。 |
| [getSignatureMasks()](#getSignatureMasks--) | 获取或设置一个可用作过滤器的二维字节数组。 |
| [setSignatureMasks(byte[][] value)](#setSignatureMasks-byte-----) | 获取或设置一个可用作过滤器的二维字节数组。 |
| [getImageDecoders()](#getImageDecoders--) | 返回一个包含关于 GDI+ 内置图像解码器信息的 [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo) 对象数组。 |
| [getImageEncoders()](#getImageEncoders--) | 返回一个包含关于 GDI+ 内置图像编码器信息的 [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo) 对象数组。 |
### ImageCodecInfo() {#ImageCodecInfo--}
```
public ImageCodecInfo()
```


初始化一个新的 [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo) 类实例。

### ImageCodecInfo(UUID clsid, String codecName, String filenameExtension, String formatDescription, UUID formatID, String mimeType, int version) {#ImageCodecInfo-java.util.UUID-java.lang.String-java.lang.String-java.lang.String-java.util.UUID-java.lang.String-int-}
```
public ImageCodecInfo(UUID clsid, String codecName, String filenameExtension, String formatDescription, UUID formatID, String mimeType, int version)
```


**Parameters:**
| 参数 | 类型 | 描述 |
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


获取一个包含标识特定编解码器的 GUID 的 java.util.UUID 结构。

**Returns:**
java.util.UUID - 一个 java.util.UUID
### setClsid(UUID value) {#setClsid-java.util.UUID-}
```
public void setClsid(UUID value)
```


设置一个包含标识特定编解码器的 GUID 的 java.util.UUID 结构。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.util.UUID | 一个 java.util.UUID |

### getFormatID() {#getFormatID--}
```
public UUID getFormatID()
```


获取一个包含标识编解码器格式的 GUID 的 java.util.UUID 结构。

**Returns:**
java.util.UUID - 一个 java.util.UUID
### setFormatID(UUID value) {#setFormatID-java.util.UUID-}
```
public void setFormatID(UUID value)
```


设置一个包含标识编解码器格式的 GUID 的 java.util.UUID 结构。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.util.UUID | 一个 java.util.UUID |

### getCodecName() {#getCodecName--}
```
public String getCodecName()
```


获取或设置一个包含编解码器名称的字符串。

**Returns:**
java.lang.String
### setCodecName(String value) {#setCodecName-java.lang.String-}
```
public void setCodecName(String value)
```


获取或设置一个包含编解码器名称的字符串。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getFormatDescription() {#getFormatDescription--}
```
public String getFormatDescription()
```


获取或设置一个描述编解码器文件格式的字符串。

**Returns:**
java.lang.String
### setFormatDescription(String value) {#setFormatDescription-java.lang.String-}
```
public void setFormatDescription(String value)
```


获取或设置一个描述编解码器文件格式的字符串。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getFilenameExtension() {#getFilenameExtension--}
```
public String getFilenameExtension()
```


获取或设置包含在编解码器中使用的文件名扩展名的字符串。扩展名之间用分号分隔。

**Returns:**
java.lang.String
### setFilenameExtension(String value) {#setFilenameExtension-java.lang.String-}
```
public void setFilenameExtension(String value)
```


获取或设置包含在编解码器中使用的文件名扩展名的字符串。扩展名之间用分号分隔。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getMimeType() {#getMimeType--}
```
public String getMimeType()
```


获取或设置一个包含编解码器的多用途互联网邮件扩展 (MIME) 类型的字符串。

**Returns:**
java.lang.String
### setMimeType(String value) {#setMimeType-java.lang.String-}
```
public void setMimeType(String value)
```


获取或设置一个包含编解码器的多用途互联网邮件扩展 (MIME) 类型的字符串。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getVersion() {#getVersion--}
```
public int getVersion()
```


获取或设置编解码器的版本号。

**Returns:**
int
### setVersion(int value) {#setVersion-int-}
```
public void setVersion(int value)
```


获取或设置编解码器的版本号。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getSignaturePatterns() {#getSignaturePatterns--}
```
public byte[][] getSignaturePatterns()
```


获取或设置一个表示编解码器签名的二维字节数组。

**Returns:**
byte[][]
### setSignaturePatterns(byte[][] value) {#setSignaturePatterns-byte-----}
```
public void setSignaturePatterns(byte[][] value)
```


获取或设置一个表示编解码器签名的二维字节数组。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte[][] |  |

### getSignatureMasks() {#getSignatureMasks--}
```
public byte[][] getSignatureMasks()
```


获取或设置一个可用作过滤器的二维字节数组。

**Returns:**
byte[][]
### setSignatureMasks(byte[][] value) {#setSignatureMasks-byte-----}
```
public void setSignatureMasks(byte[][] value)
```


获取或设置一个可用作过滤器的二维字节数组。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte[][] |  |

### getImageDecoders() {#getImageDecoders--}
```
public static ImageCodecInfo[] getImageDecoders()
```


返回一个包含关于 GDI+ 内置图像解码器信息的 [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo) 对象数组。

**Returns:**
com.aspose.drawing.imaging.ImageCodecInfo[] - 一个由 [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo) 对象组成的数组。数组中的每个 [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo) 对象包含有关内置图像解码器之一的信息。
### getImageEncoders() {#getImageEncoders--}
```
public static ImageCodecInfo[] getImageEncoders()
```


返回一个包含关于 GDI+ 内置图像编码器信息的 [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo) 对象数组。

**Returns:**
com.aspose.drawing.imaging.ImageCodecInfo[] - 一个由 [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo) 对象组成的数组。数组中的每个 [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo) 对象包含有关内置图像编码器之一的信息。
