---
title: Icon
second_title: Aspose.Drawing for Java API 参考
description: 表示 Windows 图标，它是用于表示对象的小位图图像。
type: docs
weight: 29
url: /zh/java/com.aspose.drawing/icon/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.ms.System.IDisposable
```
public final class Icon implements System.ICloneable, System.IDisposable
```

表示 Windows 图标，它是用于表示对象的小位图图像。图标可以被视为透明位图，尽管其大小由系统决定。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Icon(String fileName)](#Icon-java.lang.String-) | 从指定的文件名初始化 [Icon](../../com.aspose.drawing/icon) 类的新实例。 |
| [Icon(InputStream stream)](#Icon-java.io.InputStream-) | 从指定的数据流初始化 [Icon](../../com.aspose.drawing/icon) 类的新实例。 |
| [Icon(String fileName, Size size)](#Icon-java.lang.String-com.aspose.drawing.Size-) | 从指定的文件中以指定的大小初始化 [Icon](../../com.aspose.drawing/icon) 类的新实例。 |
| [Icon(Icon original, Size size)](#Icon-com.aspose.drawing.Icon-com.aspose.drawing.Size-) | 初始化 [Icon](../../com.aspose.drawing/icon) 类的新实例，并尝试查找与请求大小匹配的图标版本。 |
| [Icon(Object type, String resource)](#Icon-java.lang.Object-java.lang.String-) | 从指定程序集中的资源初始化 [Icon](../../com.aspose.drawing/icon) 类的新实例。 |
| [Icon(InputStream stream, Size size)](#Icon-java.io.InputStream-com.aspose.drawing.Size-) | 从指定的流中以指定的大小初始化 [Icon](../../com.aspose.drawing/icon) 类的新实例。 |
| [Icon(String fileName, int width, int height)](#Icon-java.lang.String-int-int-) | 从指定文件中使用指定的宽度和高度初始化 [Icon](../../com.aspose.drawing/icon) 类的新实例。 |
| [Icon(Icon original, int width, int height)](#Icon-com.aspose.drawing.Icon-int-int-) | 初始化 [Icon](../../com.aspose.drawing/icon) 类的新实例，并尝试查找与请求尺寸匹配的图标版本。 |
| [Icon(InputStream stream, int width, int height)](#Icon-java.io.InputStream-int-int-) | 从指定的数据流中，并使用指定的宽度和高度，初始化 [Icon](../../com.aspose.drawing/icon) 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getHandle()](#getHandle--) | 获取此 [Icon](../../com.aspose.drawing/icon) 的句柄。 |
| [getHeight()](#getHeight--) | 获取此 [Icon](../../com.aspose.drawing/icon) 的高度。 |
| [getSize()](#getSize--) | 获取此 [Icon](../../com.aspose.drawing/icon) 的大小。 |
| [getWidth()](#getWidth--) | 获取此 [Icon](../../com.aspose.drawing/icon) 的宽度。 |
| [extractAssociatedIcon(String filePath)](#extractAssociatedIcon-java.lang.String-) | 返回指定文件中包含的图像的图标表示。 |
| [fromHandle(byte[] handle)](#fromHandle-byte---) | 从指定的 Windows 图标句柄 (HICON) 创建 GDI+ [Icon](../../com.aspose.drawing/icon)。 |
| [deepClone()](#deepClone--) | 克隆 [Icon](../../com.aspose.drawing/icon)，创建一个重复的图像。 |
| [dispose()](#dispose--) | 执行与释放、释放或重置非托管资源相关的应用程序定义任务。 |
| [save(OutputStream outputStream)](#save-java.io.OutputStream-) | 将此 [Icon](../../com.aspose.drawing/icon) 保存到指定的输出 java.io.InputStream。 |
| [toBitmap()](#toBitmap--) | 将此 [Icon](../../com.aspose.drawing/icon) 转换为 GDI+ [Bitmap](../../com.aspose.drawing/bitmap)。 |
| [toString()](#toString--) | 获取描述 [Icon](../../com.aspose.drawing/icon) 的可读字符串。 |
### Icon(String fileName) {#Icon-java.lang.String-}
```
public Icon(String fileName)
```


从指定的文件名初始化 [Icon](../../com.aspose.drawing/icon) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileName | java.lang.String | 要加载 [Icon](../../com.aspose.drawing/icon) 的文件。 |

### Icon(InputStream stream) {#Icon-java.io.InputStream-}
```
public Icon(InputStream stream)
```


从指定的数据流初始化 [Icon](../../com.aspose.drawing/icon) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.InputStream | 用于加载 [Icon](../../com.aspose.drawing/icon) 的数据流。 |

### Icon(String fileName, Size size) {#Icon-java.lang.String-com.aspose.drawing.Size-}
```
public Icon(String fileName, Size size)
```


从指定的文件中以指定的大小初始化 [Icon](../../com.aspose.drawing/icon) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileName | java.lang.String | 包含图标数据的文件的名称和路径。 |
| size | [Size](../../com.aspose.drawing/size) | 所需的图标大小。 |

### Icon(Icon original, Size size) {#Icon-com.aspose.drawing.Icon-com.aspose.drawing.Size-}
```
public Icon(Icon original, Size size)
```


初始化 [Icon](../../com.aspose.drawing/icon) 类的新实例，并尝试查找与请求大小匹配的图标版本。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| original | [Icon](../../com.aspose.drawing/icon) | 用于加载新尺寸图标的 [Icon](../../com.aspose.drawing/icon)。 |
| size | [Size](../../com.aspose.drawing/size) | 一个 `Size`([.getSize](../../null/\\#getSize)) 结构，指定新 [Icon](../../com.aspose.drawing/icon) 的高度和宽度。 |

### Icon(Object type, String resource) {#Icon-java.lang.Object-java.lang.String-}
```
public Icon(Object type, String resource)
```


从指定程序集中的资源初始化 [Icon](../../com.aspose.drawing/icon) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| type | java.lang.Object | 一个指定要在其中查找资源的程序集的 Type。 |
| 资源 | java.lang.String | 要加载的资源名称。 |

### Icon(InputStream stream, Size size) {#Icon-java.io.InputStream-com.aspose.drawing.Size-}
```
public Icon(InputStream stream, Size size)
```


从指定的流中以指定的大小初始化 [Icon](../../com.aspose.drawing/icon) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | java.io.InputStream | 包含图标数据的流。 |
| size | [Size](../../com.aspose.drawing/size) | 所需的图标大小。 |

### Icon(String fileName, int width, int height) {#Icon-java.lang.String-int-int-}
```
public Icon(String fileName, int width, int height)
```


从指定文件中使用指定的宽度和高度初始化 [Icon](../../com.aspose.drawing/icon) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileName | java.lang.String | 包含 [Icon](../../com.aspose.drawing/icon) 数据的文件的名称和路径。 |
| width | int | 所需的 [Icon](../../com.aspose.drawing/icon) 宽度。 |
| height | int | 所需的 [Icon](../../com.aspose.drawing/icon) 的高度。 |

### Icon(Icon original, int width, int height) {#Icon-com.aspose.drawing.Icon-int-int-}
```
public Icon(Icon original, int width, int height)
```


初始化 [Icon](../../com.aspose.drawing/icon) 类的新实例，并尝试查找与请求尺寸匹配的图标版本。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| original | [Icon](../../com.aspose.drawing/icon) | 用于加载不同尺寸的图标。 |
| 宽度 | int | 新图标的宽度。 |
| 高度 | int | 新图标的高度。 |

### Icon(InputStream stream, int width, int height) {#Icon-java.io.InputStream-int-int-}
```
public Icon(InputStream stream, int width, int height)
```


从指定的数据流中，并使用指定的宽度和高度，初始化 [Icon](../../com.aspose.drawing/icon) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | java.io.InputStream | 用于加载图标的数据流。 |
| 宽度 | int | 图标的宽度（像素）。 |
| 高度 | int | 图标的高度（像素）。 |

### getHandle() {#getHandle--}
```
public System.IntPtr getHandle()
```


获取此 [Icon](../../com.aspose.drawing/icon) 的句柄。这不是句柄的副本；请勿释放它。

值：图标的 Windows 句柄。

**Returns:**
com.aspose.ms.System.IntPtr
### getHeight() {#getHeight--}
```
public int getHeight()
```


获取此 [Icon](../../com.aspose.drawing/icon) 的高度。

值：此 [Icon](../../com.aspose.drawing/icon) 的高度。

**Returns:**
int
### getSize() {#getSize--}
```
public Size getSize()
```


获取此 [Icon](../../com.aspose.drawing/icon) 的大小。

值：一个 `Size`([.getSize](../../null/\#getSize)) 结构，指定此 [Icon](../../com.aspose.drawing/icon) 的宽度和高度。

**Returns:**
[Size](../../com.aspose.drawing/size)
### getWidth() {#getWidth--}
```
public int getWidth()
```


获取此 [Icon](../../com.aspose.drawing/icon) 的宽度。

值：此 [Icon](../../com.aspose.drawing/icon) 的宽度。

**Returns:**
int
### extractAssociatedIcon(String filePath) {#extractAssociatedIcon-java.lang.String-}
```
public static Icon extractAssociatedIcon(String filePath)
```


返回指定文件中包含的图像的图标表示。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filePath | java.lang.String | 包含图像的文件路径。 |

**Returns:**
[Icon](../../com.aspose.drawing/icon) - The [Icon](../../com.aspose.drawing/icon) representation of the image that is contained in the specified file.
### fromHandle(byte[] handle) {#fromHandle-byte---}
```
public static Icon fromHandle(byte[] handle)
```


从指定的 Windows 图标句柄 (HICON) 创建 GDI+ [Icon](../../com.aspose.drawing/icon)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| handle | byte[] | 指向图标的 Windows 句柄。 |

**Returns:**
[Icon](../../com.aspose.drawing/icon) - The [Icon](../../com.aspose.drawing/icon) this method creates.
### deepClone() {#deepClone--}
```
public Object deepClone()
```


克隆 [Icon](../../com.aspose.drawing/icon)，创建一个重复的图像。

**Returns:**
java.lang.Object - 可以强制转换为 [Icon](../../com.aspose.drawing/icon) 的对象。
### dispose() {#dispose--}
```
public void dispose()
```


执行与释放、释放或重置非托管资源相关的应用程序定义任务。

### save(OutputStream outputStream) {#save-java.io.OutputStream-}
```
public void save(OutputStream outputStream)
```


将此 [Icon](../../com.aspose.drawing/icon) 保存到指定的输出 java.io.InputStream。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| outputStream | java.io.OutputStream | 要保存到的 java.io.InputStream。 |

### toBitmap() {#toBitmap--}
```
public Bitmap toBitmap()
```


将此 [Icon](../../com.aspose.drawing/icon) 转换为 GDI+ [Bitmap](../../com.aspose.drawing/bitmap)。

**Returns:**
[Bitmap](../../com.aspose.drawing/bitmap) - A [Bitmap](../../com.aspose.drawing/bitmap) that represents the converted [Icon](../../com.aspose.drawing/icon).
### toString() {#toString--}
```
public String toString()
```


获取描述 [Icon](../../com.aspose.drawing/icon) 的可读字符串。

**Returns:**
java.lang.String - 描述 [Icon](../../com.aspose.drawing/icon) 的字符串。
