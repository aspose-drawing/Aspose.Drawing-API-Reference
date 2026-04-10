---
title: Image.GetThumbnailImageAbort
second_title: Riferimento API di Aspose.Drawing per Java
description: Fornisce un metodo di callback per determinare quando il metodo dovrebbe annullare prematuramente l'esecuzione.
type: docs
weight: 10
url: /it/java/com.aspose.drawing/image.getthumbnailimageabort/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate
```
public abstract static class Image.GetThumbnailImageAbort extends System.MulticastDelegate
```

Fornisce un metodo di callback per determinare quando il metodo [.getThumbnailImage(int, int, GetThumbnailImageAbort, IntPtr)](../../null/\#getThumbnailImage-int--int--GetThumbnailImageAbort--IntPtr-) dovrebbe annullare prematuramente l'esecuzione.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [GetThumbnailImageAbort()](#GetThumbnailImageAbort--) |  |
## Metodi

| Metodo | Descrizione |
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
| Parametro | Tipo | Descrizione |
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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| result | com.aspose.ms.System.IAsyncResult |  |

**Returns:**
boolean
