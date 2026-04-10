---
title: PrivateFontCollection
second_title: Aspose.Drawing for Java API 参考
description: 提供一个由客户端应用程序提供的字体文件构建的字体系列集合。
type: docs
weight: 13
url: /zh/java/com.aspose.drawing.text/privatefontcollection/
---
**Inheritance:**
java.lang.Object，[com.aspose.drawing.FontCollection](../../com.aspose.drawing/fontcollection)
```
public final class PrivateFontCollection extends FontCollection
```

提供一个由客户端应用程序提供的字体文件构建的字体系列集合。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PrivateFontCollection()](#PrivateFontCollection--) | 初始化一个新的 [PrivateFontCollection](../../com.aspose.drawing.text/privatefontcollection) 类的实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [addFontFile(String filename)](#addFontFile-java.lang.String-) | 将指定文件中的字体添加到此 [PrivateFontCollection](../../com.aspose.drawing.text/privatefontcollection)。 |
| [addMemoryFont(byte[] memory, int length)](#addMemoryFont-byte---int-) | 将系统内存中的字体添加到此 [PrivateFontCollection](../../com.aspose.drawing.text/privatefontcollection)。 |
### PrivateFontCollection() {#PrivateFontCollection--}
```
public PrivateFontCollection()
```


初始化一个新的 [PrivateFontCollection](../../com.aspose.drawing.text/privatefontcollection) 类的实例。

### addFontFile(String filename) {#addFontFile-java.lang.String-}
```
public void addFontFile(String filename)
```


将指定文件中的字体添加到此 [PrivateFontCollection](../../com.aspose.drawing.text/privatefontcollection)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 文件名 | java.lang.String | 一个包含要添加的字体文件名的字符串。 |

### addMemoryFont(byte[] memory, int length) {#addMemoryFont-byte---int-}
```
public void addMemoryFont(byte[] memory, int length)
```


将系统内存中的字体添加到此 [PrivateFontCollection](../../com.aspose.drawing.text/privatefontcollection)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 内存 | byte[] | 要添加的字体的内存地址。 |
| length | int | 要添加的字体的内存长度。 |

