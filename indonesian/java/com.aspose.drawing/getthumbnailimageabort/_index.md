---
title: Image.GetThumbnailImageAbort
second_title: Referensi API Aspose.Drawing for Java
description: Menyediakan metode callback untuk menentukan kapan metode  harus dibatalkan secara prematur.
type: docs
weight: 10
url: /id/java/com.aspose.drawing/image.getthumbnailimageabort/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate
```
public abstract static class Image.GetThumbnailImageAbort extends System.MulticastDelegate
```

Menyediakan metode callback untuk menentukan kapan metode [.getThumbnailImage(int, int, GetThumbnailImageAbort, IntPtr)](../../null/\#getThumbnailImage-int--int--GetThumbnailImageAbort--IntPtr-) harus dibatalkan secara prematur.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [GetThumbnailImageAbort()](#GetThumbnailImageAbort--) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [invoke()](#invoke--) |  |
| [beginInvoke(System.AsyncCallback callback, Object state)](#beginInvoke-com.aspose.ms.System.AsyncCallback-java.lang.Object-) |  |
| [endInvoke(System.IAsyncResult result)](#endInvoke-com.aspose.ms.System.IAsyncResult-) |  |
### GetThumbnailImageAbort() {#GetThumbnailImageAbort--}
```
public GetThumbnailImageAbort()
```


### invoke() {#invoke--}
```
public abstract boolean invoke()
```




**Returns:**
boolean
### beginInvoke(System.AsyncCallback callback, Object state) {#beginInvoke-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginInvoke(System.AsyncCallback callback, Object state)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| callback | com.aspose.ms.System.AsyncCallback |  |
| state | java.lang.Object |  |

**Returns:**
com.aspose.ms.System.IAsyncResult
### endInvoke(System.IAsyncResult result) {#endInvoke-com.aspose.ms.System.IAsyncResult-}
```
public final boolean endInvoke(System.IAsyncResult result)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| result | com.aspose.ms.System.IAsyncResult |  |

**Returns:**
boolean
