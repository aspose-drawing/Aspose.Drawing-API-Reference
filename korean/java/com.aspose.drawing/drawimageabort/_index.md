---
title: Graphics.DrawImageAbort
second_title: Aspose.Drawing for Java API 참조
description: 
type: docs
weight: 10
url: /ko/java/com.aspose.drawing/graphics.drawimageabort/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate
```
public abstract static class Graphics.DrawImageAbort extends System.MulticastDelegate
```
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [DrawImageAbort()](#DrawImageAbort--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [invoke(System.IntPtr callbackdata)](#invoke-com.aspose.ms.System.IntPtr-) | `DrawImage` 메서드가 실행을 조기에 취소하고 이미지를 그리는 것을 중단해야 하는 시점을 결정하기 위한 콜백 메서드를 제공합니다. |
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


`DrawImage` 메서드가 실행을 조기에 취소하고 이미지를 그리는 것을 중단해야 하는 시점을 결정하기 위한 콜백 메서드를 제공합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| callbackdata | com.aspose.ms.System.IntPtr | 콜백 메서드에 대한 데이터를 지정하는 내부 포인터입니다. 이 매개변수는 모든 `DrawImage` 오버로드에 전달되지 않습니다. `System.IntPtr.Zero` 값을 확인하여 해당 포인터가 없는지 테스트할 수 있습니다. |

**Returns:**
boolean - 이 메서드는 `DrawImage` 메서드를 조기에 중단해야 한다고 판단되면 true를 반환합니다. 그렇지 않으면 `DrawImage` 메서드가 계속 실행되어야 함을 나타내기 위해 false를 반환합니다.
### beginInvoke(System.IntPtr callbackdata, System.AsyncCallback callback, Object state) {#beginInvoke-com.aspose.ms.System.IntPtr-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginInvoke(System.IntPtr callbackdata, System.AsyncCallback callback, Object state)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
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
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| result | com.aspose.ms.System.IAsyncResult |  |

**Returns:**
boolean
