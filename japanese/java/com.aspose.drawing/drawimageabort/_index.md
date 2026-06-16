---
title: Graphics.DrawImageAbort
second_title: Aspose.Drawing for Java API リファレンス
description: 
type: docs
weight: 10
url: /ja/java/com.aspose.drawing/graphics.drawimageabort/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate
```
public abstract static class Graphics.DrawImageAbort extends System.MulticastDelegate
```
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [DrawImageAbort()](#DrawImageAbort--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [invoke(System.IntPtr callbackdata)](#invoke-com.aspose.ms.System.IntPtr-) | Provides a callback method for deciding when the `DrawImage` method should prematurely cancel execution and stop drawing an image. |
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


Provides a callback method for deciding when the `DrawImage` method should prematurely cancel execution and stop drawing an image.

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| callbackdata | com.aspose.ms.System.IntPtr | コールバックメソッドのデータを指定する内部ポインタです。このパラメータはすべての `DrawImage` オーバーロードで渡されるわけではありません。その不在を確認するには、値 `System.IntPtr.Zero` をチェックできます。 |

**Returns:**
boolean - このメソッドは、`DrawImage` メソッドの実行を早期に停止すべきと判断した場合に true を返します。そうでない場合は、`DrawImage` メソッドを継続すべきことを示すために false を返します。
### beginInvoke(System.IntPtr callbackdata, System.AsyncCallback callback, Object state) {#beginInvoke-com.aspose.ms.System.IntPtr-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginInvoke(System.IntPtr callbackdata, System.AsyncCallback callback, Object state)
```




**Parameters:**
| パラメーター | 型 | 説明 |
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
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| result | com.aspose.ms.System.IAsyncResult |  |

**Returns:**
boolean
