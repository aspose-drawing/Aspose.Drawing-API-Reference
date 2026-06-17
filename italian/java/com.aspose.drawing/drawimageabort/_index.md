---
title: Graphics.DrawImageAbort
second_title: Riferimento API di Aspose.Drawing per Java
description: 
type: docs
weight: 10
url: /it/java/com.aspose.drawing/graphics.drawimageabort/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate
```
public abstract static class Graphics.DrawImageAbort extends System.MulticastDelegate
```
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [DrawImageAbort()](#DrawImageAbort--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [invoke(System.IntPtr callbackdata)](#invoke-com.aspose.ms.System.IntPtr-) | Fornisce un metodo di callback per decidere quando il metodo `DrawImage` dovrebbe annullare prematuramente l'esecuzione e interrompere il disegno di un'immagine. |
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


Fornisce un metodo di callback per decidere quando il metodo `DrawImage` dovrebbe annullare prematuramente l'esecuzione e interrompere il disegno di un'immagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| callbackdata | com.aspose.ms.System.IntPtr | Puntatore interno che specifica i dati per il metodo di callback. Questo parametro non viene passato da tutte le overload di `DrawImage`. È possibile verificare la sua assenza controllando il valore `System.IntPtr.Zero`. |

**Returns:**
boolean - Questo metodo restituisce true se decide che il metodo `DrawImage` debba interrompere prematuramente l'esecuzione. Altrimenti restituisce false per indicare che il metodo `DrawImage` deve continuare l'esecuzione.
### beginInvoke(System.IntPtr callbackdata, System.AsyncCallback callback, Object state) {#beginInvoke-com.aspose.ms.System.IntPtr-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginInvoke(System.IntPtr callbackdata, System.AsyncCallback callback, Object state)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| result | com.aspose.ms.System.IAsyncResult |  |

**Returns:**
boolean
