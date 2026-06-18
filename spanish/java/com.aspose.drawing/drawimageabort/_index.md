---
title: Graphics.DrawImageAbort
second_title: Referencia de la API de Aspose.Drawing para Java
description: 
type: docs
weight: 10
url: /es/java/com.aspose.drawing/graphics.drawimageabort/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate
```
public abstract static class Graphics.DrawImageAbort extends System.MulticastDelegate
```
## Constructores

| Constructor | Descripción |
| --- | --- |
| [DrawImageAbort()](#DrawImageAbort--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [invoke(System.IntPtr callbackdata)](#invoke-com.aspose.ms.System.IntPtr-) | Proporciona un método de devolución de llamada para decidir cuándo el método `DrawImage` debe cancelar prematuramente la ejecución y detener el dibujo de una imagen. |
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


Proporciona un método de devolución de llamada para decidir cuándo el método `DrawImage` debe cancelar prematuramente la ejecución y detener el dibujo de una imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| callbackdata | com.aspose.ms.System.IntPtr | Puntero interno que especifica los datos para el método de devolución de llamada. Este parámetro no se pasa en todas las sobrecargas de `DrawImage`. Puede comprobar su ausencia verificando el valor `System.IntPtr.Zero`. |

**Returns:**
boolean - Este método devuelve true si decide que el método `DrawImage` debe detener la ejecución prematuramente. De lo contrario devuelve false para indicar que el método `DrawImage` debe continuar la ejecución.
### beginInvoke(System.IntPtr callbackdata, System.AsyncCallback callback, Object state) {#beginInvoke-com.aspose.ms.System.IntPtr-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginInvoke(System.IntPtr callbackdata, System.AsyncCallback callback, Object state)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| result | com.aspose.ms.System.IAsyncResult |  |

**Returns:**
boolean
