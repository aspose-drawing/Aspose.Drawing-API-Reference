---
title: Graphics.DrawImageAbort
second_title: Aspose.Drawing voor Java API-referentie
description: 
type: docs
weight: 10
url: /nl/java/com.aspose.drawing/graphics.drawimageabort/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate
```
public abstract static class Graphics.DrawImageAbort extends System.MulticastDelegate
```
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [DrawImageAbort()](#DrawImageAbort--) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [invoke(System.IntPtr callbackdata)](#invoke-com.aspose.ms.System.IntPtr-) | Biedt een callback‑methode om te bepalen wanneer de `DrawImage`‑methode voortijdig moet worden geannuleerd en het tekenen van een afbeelding moet stoppen. |
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


Biedt een callback‑methode om te bepalen wanneer de `DrawImage`‑methode voortijdig moet worden geannuleerd en het tekenen van een afbeelding moet stoppen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| callbackdata | com.aspose.ms.System.IntPtr | Interne pointer die gegevens specificeert voor de callback‑methode. Deze parameter wordt niet door alle `DrawImage`‑overloads doorgegeven. Je kunt de afwezigheid testen door te controleren op de waarde `System.IntPtr.Zero`. |

**Returns:**
boolean - Deze methode retourneert true als hij beslist dat de `DrawImage`‑methode voortijdig moet stoppen. Anders retourneert hij false om aan te geven dat de `DrawImage`‑methode moet doorgaan.
### beginInvoke(System.IntPtr callbackdata, System.AsyncCallback callback, Object state) {#beginInvoke-com.aspose.ms.System.IntPtr-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginInvoke(System.IntPtr callbackdata, System.AsyncCallback callback, Object state)
```




**Parameters:**
| Parameter | Type | Beschrijving |
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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| result | com.aspose.ms.System.IAsyncResult |  |

**Returns:**
boolean
