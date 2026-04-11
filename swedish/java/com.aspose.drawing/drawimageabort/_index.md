---
title: Graphics.DrawImageAbort
second_title: Aspose.Drawing för Java API‑referens
description: 
type: docs
weight: 10
url: /sv/java/com.aspose.drawing/graphics.drawimageabort/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate
```
public abstract static class Graphics.DrawImageAbort extends System.MulticastDelegate
```
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [DrawImageAbort()](#DrawImageAbort--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [invoke(System.IntPtr callbackdata)](#invoke-com.aspose.ms.System.IntPtr-) | Tillhandahåller en återuppringningsmetod för att avgöra när `DrawImage`-metoden ska avbryta körningen i förtid och sluta rita en bild. |
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


Tillhandahåller en återuppringningsmetod för att avgöra när `DrawImage`-metoden ska avbryta körningen i förtid och sluta rita en bild.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| callbackdata | com.aspose.ms.System.IntPtr | Intern pekare som specificerar data för återuppringningsmetoden. Denna parameter skickas inte av alla `DrawImage`-överladdningar. Du kan testa dess frånvaro genom att kontrollera värdet `System.IntPtr.Zero`. |

**Returns:**
boolean - Denna metod returnerar true om den beslutar att `DrawImage`-metoden ska avbrytas i förtid. Annars returnerar den false för att indikera att `DrawImage`-metoden ska fortsätta köras.
### beginInvoke(System.IntPtr callbackdata, System.AsyncCallback callback, Object state) {#beginInvoke-com.aspose.ms.System.IntPtr-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginInvoke(System.IntPtr callbackdata, System.AsyncCallback callback, Object state)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| callbackdata | com.aspose.ms.System.IntPtr |  |
| återanrop | com.aspose.ms.System.AsyncCallback |  |
| tillstånd | java.lang.Object |  |

**Returns:**
com.aspose.ms.System.IAsyncResult
### endInvoke(System.IAsyncResult result) {#endInvoke-com.aspose.ms.System.IAsyncResult-}
```
public final boolean endInvoke(System.IAsyncResult result)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| resultat | com.aspose.ms.System.IAsyncResult |  |

**Returns:**
boolean
