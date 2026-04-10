---
title: Graphics.EnumerateMetafileProc
second_title: Aspose.Drawing for Java API リファレンス
description: 
type: docs
weight: 11
url: /ja/java/com.aspose.drawing/graphics.enumeratemetafileproc/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate
```
public abstract static class Graphics.EnumerateMetafileProc extends System.MulticastDelegate
```
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [EnumerateMetafileProc()](#EnumerateMetafileProc--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [invoke(int recordType, int flags, int dataSize, System.IntPtr data, PlayRecordCallback callbackData)](#invoke-int-int-int-com.aspose.ms.System.IntPtr-com.aspose.drawing.imaging.PlayRecordCallback-) | `EnumerateMetafile` メソッド用のコールバックメソッドを提供します。 |
| [beginInvoke(int recordType, int flags, int dataSize, System.IntPtr data, PlayRecordCallback callbackData, System.AsyncCallback callback, Object state)](#beginInvoke-int-int-int-com.aspose.ms.System.IntPtr-com.aspose.drawing.imaging.PlayRecordCallback-com.aspose.ms.System.AsyncCallback-java.lang.Object-) |  |
### EnumerateMetafileProc() {#EnumerateMetafileProc--}
```
public EnumerateMetafileProc()
```


### invoke(int recordType, int flags, int dataSize, System.IntPtr data, PlayRecordCallback callbackData) {#invoke-int-int-int-com.aspose.ms.System.IntPtr-com.aspose.drawing.imaging.PlayRecordCallback-}
```
public abstract boolean invoke(int recordType, int flags, int dataSize, System.IntPtr data, PlayRecordCallback callbackData)
```


`EnumerateMetafile` メソッド用のコールバックメソッドを提供します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| recordType | int | [EmfPlusRecordType](../../com.aspose.drawing.imaging/emfplusrecordtype) 列挙体のメンバーで、メタファイルレコードのタイプを指定します。 |
| flags | int | レコードの属性を指定するフラグの集合。 |
| dataSize | int | レコードデータのバイト数。 |
| データ | com.aspose.ms.System.IntPtr | レコードデータを含むバッファへのポインタ。 |
| callbackData | [PlayRecordCallback](../../com.aspose.drawing.imaging/playrecordcallback) | この引数は使用されません。 |

**Returns:**
boolean - レコードの列挙を続行したい場合は true を返し、そうでなければ false を返します。
### beginInvoke(int recordType, int flags, int dataSize, System.IntPtr data, PlayRecordCallback callbackData, System.AsyncCallback callback, Object state) {#beginInvoke-int-int-int-com.aspose.ms.System.IntPtr-com.aspose.drawing.imaging.PlayRecordCallback-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginInvoke(int recordType, int flags, int dataSize, System.IntPtr data, PlayRecordCallback callbackData, System.AsyncCallback callback, Object state)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| recordType | int |  |
| flags | int |  |
| dataSize | int |  |
| データ | com.aspose.ms.System.IntPtr |  |
| callbackData | [PlayRecordCallback](../../com.aspose.drawing.imaging/playrecordcallback) |  |
| callback | com.aspose.ms.System.AsyncCallback |  |
| state | java.lang.Object |  |

**Returns:**
com.aspose.ms.System.IAsyncResult
