---
title: Graphics.EnumerateMetafileProc
second_title: Referensi API Aspose.Drawing for Java
description: 
type: docs
weight: 11
url: /id/java/com.aspose.drawing/graphics.enumeratemetafileproc/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate
```
public abstract static class Graphics.EnumerateMetafileProc extends System.MulticastDelegate
```
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [EnumerateMetafileProc()](#EnumerateMetafileProc--) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [invoke(int recordType, int flags, int dataSize, System.IntPtr data, PlayRecordCallback callbackData)](#invoke-int-int-int-com.aspose.ms.System.IntPtr-com.aspose.drawing.imaging.PlayRecordCallback-) | Menyediakan metode callback untuk metode `EnumerateMetafile`. |
| [beginInvoke(int recordType, int flags, int dataSize, System.IntPtr data, PlayRecordCallback callbackData, System.AsyncCallback callback, Object state)](#beginInvoke-int-int-int-com.aspose.ms.System.IntPtr-com.aspose.drawing.imaging.PlayRecordCallback-com.aspose.ms.System.AsyncCallback-java.lang.Object-) |  |
### EnumerateMetafileProc() {#EnumerateMetafileProc--}
```
public EnumerateMetafileProc()
```


### invoke(int recordType, int flags, int dataSize, System.IntPtr data, PlayRecordCallback callbackData) {#invoke-int-int-int-com.aspose.ms.System.IntPtr-com.aspose.drawing.imaging.PlayRecordCallback-}
```
public abstract boolean invoke(int recordType, int flags, int dataSize, System.IntPtr data, PlayRecordCallback callbackData)
```


Menyediakan metode callback untuk metode `EnumerateMetafile`.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| recordType | int | Anggota enumerasi [EmfPlusRecordType](../../com.aspose.drawing.imaging/emfplusrecordtype) yang menentukan tipe rekaman metafile. |
| flags | int | Set flag yang menentukan atribut rekaman. |
| dataSize | int | Jumlah byte dalam data rekaman. |
| data | com.aspose.ms.System.IntPtr | Penunjuk ke buffer yang berisi data rekaman. |
| callbackData | [PlayRecordCallback](../../com.aspose.drawing.imaging/playrecordcallback) | Argumen tidak digunakan. |

**Returns:**
boolean - Kembalikan true jika Anda ingin melanjutkan enumerasi rekaman; jika tidak, false.
### beginInvoke(int recordType, int flags, int dataSize, System.IntPtr data, PlayRecordCallback callbackData, System.AsyncCallback callback, Object state) {#beginInvoke-int-int-int-com.aspose.ms.System.IntPtr-com.aspose.drawing.imaging.PlayRecordCallback-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginInvoke(int recordType, int flags, int dataSize, System.IntPtr data, PlayRecordCallback callbackData, System.AsyncCallback callback, Object state)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| recordType | int |  |
| flags | int |  |
| dataSize | int |  |
| data | com.aspose.ms.System.IntPtr |  |
| callbackData | [PlayRecordCallback](../../com.aspose.drawing.imaging/playrecordcallback) |  |
| callback | com.aspose.ms.System.AsyncCallback |  |
| state | java.lang.Object |  |

**Returns:**
com.aspose.ms.System.IAsyncResult
