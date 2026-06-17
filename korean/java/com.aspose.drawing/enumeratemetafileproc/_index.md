---
title: Graphics.EnumerateMetafileProc
second_title: Aspose.Drawing for Java API 참조
description: 
type: docs
weight: 11
url: /ko/java/com.aspose.drawing/graphics.enumeratemetafileproc/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate
```
public abstract static class Graphics.EnumerateMetafileProc extends System.MulticastDelegate
```
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [EnumerateMetafileProc()](#EnumerateMetafileProc--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [invoke(int recordType, int flags, int dataSize, System.IntPtr data, PlayRecordCallback callbackData)](#invoke-int-int-int-com.aspose.ms.System.IntPtr-com.aspose.drawing.imaging.PlayRecordCallback-) | `EnumerateMetafile` 메서드에 대한 콜백 메서드를 제공합니다. |
| [beginInvoke(int recordType, int flags, int dataSize, System.IntPtr data, PlayRecordCallback callbackData, System.AsyncCallback callback, Object state)](#beginInvoke-int-int-int-com.aspose.ms.System.IntPtr-com.aspose.drawing.imaging.PlayRecordCallback-com.aspose.ms.System.AsyncCallback-java.lang.Object-) |  |
### EnumerateMetafileProc() {#EnumerateMetafileProc--}
```
public EnumerateMetafileProc()
```


### invoke(int recordType, int flags, int dataSize, System.IntPtr data, PlayRecordCallback callbackData) {#invoke-int-int-int-com.aspose.ms.System.IntPtr-com.aspose.drawing.imaging.PlayRecordCallback-}
```
public abstract boolean invoke(int recordType, int flags, int dataSize, System.IntPtr data, PlayRecordCallback callbackData)
```


`EnumerateMetafile` 메서드에 대한 콜백 메서드를 제공합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| recordType | int | [EmfPlusRecordType](../../com.aspose.drawing.imaging/emfplusrecordtype) 열거형의 멤버로, 메타파일 레코드의 유형을 지정합니다. |
| flags | int | 레코드의 속성을 지정하는 플래그 집합. |
| dataSize | int | 레코드 데이터의 바이트 수. |
| 데이터 | com.aspose.ms.System.IntPtr | 레코드 데이터를 포함하는 버퍼에 대한 포인터입니다. |
| callbackData | [PlayRecordCallback](../../com.aspose.drawing.imaging/playrecordcallback) | 이 인수는 사용되지 않습니다. |

**Returns:**
boolean - 레코드 열거를 계속하려면 true를 반환하고, 그렇지 않으면 false를 반환합니다.
### beginInvoke(int recordType, int flags, int dataSize, System.IntPtr data, PlayRecordCallback callbackData, System.AsyncCallback callback, Object state) {#beginInvoke-int-int-int-com.aspose.ms.System.IntPtr-com.aspose.drawing.imaging.PlayRecordCallback-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginInvoke(int recordType, int flags, int dataSize, System.IntPtr data, PlayRecordCallback callbackData, System.AsyncCallback callback, Object state)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| recordType | int |  |
| flags | int |  |
| dataSize | int |  |
| 데이터 | com.aspose.ms.System.IntPtr |  |
| callbackData | [PlayRecordCallback](../../com.aspose.drawing.imaging/playrecordcallback) |  |
| callback | com.aspose.ms.System.AsyncCallback |  |
| state | java.lang.Object |  |

**Returns:**
com.aspose.ms.System.IAsyncResult
