---
title: Image.GetThumbnailImageAbort
second_title: Référence de l'API Aspose.Drawing pour Java
description: Fournit une méthode de rappel permettant de déterminer quand la méthode  doit annuler prématurément l'exécution.
type: docs
weight: 10
url: /fr/java/com.aspose.drawing/image.getthumbnailimageabort/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate
```
public abstract static class Image.GetThumbnailImageAbort extends System.MulticastDelegate
```

Fournit une méthode de rappel permettant de déterminer quand la méthode [.getThumbnailImage(int, int, GetThumbnailImageAbort, IntPtr)](../../null/\#getThumbnailImage-int--int--GetThumbnailImageAbort--IntPtr-) doit annuler prématurément l'exécution.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [GetThumbnailImageAbort()](#GetThumbnailImageAbort--) |  |
## Méthodes

| Méthode | Description |
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
| Paramètre | Type | Description |
| --- | --- | --- |
| callback | com.aspose.ms.System.AsyncCallback |  |
| état | java.lang.Object |  |

**Returns:**
com.aspose.ms.System.IAsyncResult
### endInvoke(System.IAsyncResult result) {#endInvoke-com.aspose.ms.System.IAsyncResult-}
```
public final boolean endInvoke(System.IAsyncResult result)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| résultat | com.aspose.ms.System.IAsyncResult |  |

**Returns:**
boolean
