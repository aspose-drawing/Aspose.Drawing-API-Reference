---
title: Graphics.DrawImageAbort
second_title: Referensi API Aspose.Drawing for Java
description: 
type: docs
weight: 10
url: /id/java/com.aspose.drawing/graphics.drawimageabort/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate
```
public abstract static class Graphics.DrawImageAbort extends System.MulticastDelegate
```
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [DrawImageAbort()](#DrawImageAbort--) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [invoke(System.IntPtr callbackdata)](#invoke-com.aspose.ms.System.IntPtr-) | Menyediakan metode callback untuk menentukan kapan metode `DrawImage` harus membatalkan eksekusi secara prematur dan menghentikan proses menggambar gambar. |
| [beginInvoke(System.IntPtr callbackdata, System.AsyncCallback callback, Object state)](#beginInvoke-com.aspose.ms.System.IntPtr-com.aspose.ms.System.AsyncCallback-java.lang.Object-) |  |
| [endInvoke(System.IAsyncResult result)](#endInvoke-com.aspose.ms.System.IAsyncResult-) |  |
### DrawImageAbort() {#DrawImageAbort--}
```
public DrawImageAbort()
```


### invoke(System.IntPtr callbackdata) {#invoke-com.aspose.ms.System.IntPtr-}
```
public abstract boolean invoke(System.IntPtr callbackdata)
```


Menyediakan metode callback untuk menentukan kapan metode `DrawImage` harus membatalkan eksekusi secara prematur dan menghentikan proses menggambar gambar.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| callbackdata | com.aspose.ms.System.IntPtr | Penunjuk internal yang menentukan data untuk metode callback. Parameter ini tidak diberikan oleh semua overload `DrawImage`. Anda dapat menguji ketidakhadirannya dengan memeriksa nilai `System.IntPtr.Zero`. |

**Returns:**
boolean - Metode ini mengembalikan true jika memutuskan bahwa metode `DrawImage` harus menghentikan eksekusi lebih awal. Jika tidak, ia mengembalikan false untuk menunjukkan bahwa metode `DrawImage` harus melanjutkan eksekusi.
### beginInvoke(System.IntPtr callbackdata, System.AsyncCallback callback, Object state) {#beginInvoke-com.aspose.ms.System.IntPtr-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginInvoke(System.IntPtr callbackdata, System.AsyncCallback callback, Object state)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| callbackdata | com.aspose.ms.System.IntPtr |  |
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
