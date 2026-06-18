---
title: Graphics.DrawImageAbort
second_title: Αναφορά API του Aspose.Drawing for Java
description: 
type: docs
weight: 10
url: /el/java/com.aspose.drawing/graphics.drawimageabort/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate
```
public abstract static class Graphics.DrawImageAbort extends System.MulticastDelegate
```
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [DrawImageAbort()](#DrawImageAbort--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [invoke(System.IntPtr callbackdata)](#invoke-com.aspose.ms.System.IntPtr-) | Παρέχει μια μέθοδο επανάκλησης για να αποφασίσει πότε η μέθοδος `DrawImage` πρέπει να ακυρώσει πρόωρα την εκτέλεση και να σταματήσει τη σχεδίαση μιας εικόνας. |
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


Παρέχει μια μέθοδο επανάκλησης για να αποφασίσει πότε η μέθοδος `DrawImage` πρέπει να ακυρώσει πρόωρα την εκτέλεση και να σταματήσει τη σχεδίαση μιας εικόνας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| callbackdata | com.aspose.ms.System.IntPtr | Εσωτερικός δείκτης που καθορίζει δεδομένα για τη μέθοδο callback. Αυτή η παράμετρος δεν περνάται από όλες τις υπερφορτώσεις του `DrawImage`. Μπορείτε να ελέγξετε την απουσία της ελέγχοντας την τιμή `System.IntPtr.Zero`. |

**Returns:**
boolean - Αυτή η μέθοδος επιστρέφει true εάν αποφασίσει ότι η μέθοδος `DrawImage` πρέπει να σταματήσει πρόωρα την εκτέλεση. Διαφορετικά επιστρέφει false για να υποδείξει ότι η μέθοδος `DrawImage` πρέπει να συνεχίσει την εκτέλεση.
### beginInvoke(System.IntPtr callbackdata, System.AsyncCallback callback, Object state) {#beginInvoke-com.aspose.ms.System.IntPtr-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginInvoke(System.IntPtr callbackdata, System.AsyncCallback callback, Object state)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
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
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| result | com.aspose.ms.System.IAsyncResult |  |

**Returns:**
boolean
