---
title: Image.GetThumbnailImageAbort
second_title: Aspose.Drawing voor Java API-referentie
description: Biedt een callback-methode om te bepalen wanneer de methode voortijdig moet worden geannuleerd.
type: docs
weight: 10
url: /nl/java/com.aspose.drawing/image.getthumbnailimageabort/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate
```
public abstract static class Image.GetThumbnailImageAbort extends System.MulticastDelegate
```

Biedt een callback-methode om te bepalen wanneer de [.getThumbnailImage(int, int, GetThumbnailImageAbort, IntPtr)](../../null/\#getThumbnailImage-int--int--GetThumbnailImageAbort--IntPtr-) methode voortijdig moet worden geannuleerd.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [GetThumbnailImageAbort()](#GetThumbnailImageAbort--) |  |
## Methoden

| Methode | Beschrijving |
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
| Parameter | Type | Beschrijving |
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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| result | com.aspose.ms.System.IAsyncResult |  |

**Returns:**
boolean
