---
title: Image.GetThumbnailImageAbort
second_title: Referencia de la API de Aspose.Drawing para Java
description: Proporciona un método de devolución de llamada para determinar cuándo el método  debe cancelar la ejecución prematuramente.
type: docs
weight: 10
url: /es/java/com.aspose.drawing/image.getthumbnailimageabort/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate
```
public abstract static class Image.GetThumbnailImageAbort extends System.MulticastDelegate
```

Proporciona un método de devolución de llamada para determinar cuándo el método [.getThumbnailImage(int, int, GetThumbnailImageAbort, IntPtr)](../../null/\#getThumbnailImage-int--int--GetThumbnailImageAbort--IntPtr-) debe cancelar la ejecución prematuramente.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [GetThumbnailImageAbort()](#GetThumbnailImageAbort--) |  |
## Métodos

| Método | Descripción |
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
| Parámetro | Tipo | Descripción |
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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| result | com.aspose.ms.System.IAsyncResult |  |

**Returns:**
boolean
