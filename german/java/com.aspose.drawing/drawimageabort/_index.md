---
title: Graphics.DrawImageAbort
second_title: Aspose.Drawing für Java API-Referenz
description: 
type: docs
weight: 10
url: /de/java/com.aspose.drawing/graphics.drawimageabort/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate
```
public abstract static class Graphics.DrawImageAbort extends System.MulticastDelegate
```
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [DrawImageAbort()](#DrawImageAbort--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [invoke(System.IntPtr callbackdata)](#invoke-com.aspose.ms.System.IntPtr-) | Stellt eine Rückrufmethode bereit, um zu entscheiden, wann die `DrawImage`‑Methode die Ausführung vorzeitig abbrechen und das Zeichnen eines Bildes stoppen soll. |
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


Stellt eine Rückrufmethode bereit, um zu entscheiden, wann die `DrawImage`‑Methode die Ausführung vorzeitig abbrechen und das Zeichnen eines Bildes stoppen soll.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| callbackdata | com.aspose.ms.System.IntPtr | Interner Zeiger, der Daten für die Callback-Methode angibt. Dieser Parameter wird nicht von allen `DrawImage`-Überladungen übergeben. Sie können seine Abwesenheit testen, indem Sie den Wert `System.IntPtr.Zero` prüfen. |

**Returns:**
bool - Diese Methode gibt true zurück, wenn sie entscheidet, dass die `DrawImage`-Methode die Ausführung vorzeitig stoppen soll. Andernfalls gibt sie false zurück, um anzuzeigen, dass die `DrawImage`-Methode die Ausführung fortsetzen soll.
### beginInvoke(System.IntPtr callbackdata, System.AsyncCallback callback, Object state) {#beginInvoke-com.aspose.ms.System.IntPtr-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginInvoke(System.IntPtr callbackdata, System.AsyncCallback callback, Object state)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| result | com.aspose.ms.System.IAsyncResult |  |

**Returns:**
boolean
