---
title: Graphics.DrawImageAbort
second_title: Référence de l'API Aspose.Drawing pour Java
description: 
type: docs
weight: 10
url: /fr/java/com.aspose.drawing/graphics.drawimageabort/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate
```
public abstract static class Graphics.DrawImageAbort extends System.MulticastDelegate
```
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [DrawImageAbort()](#DrawImageAbort--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [invoke(System.IntPtr callbackdata)](#invoke-com.aspose.ms.System.IntPtr-) | Fournit une méthode de rappel pour décider quand la méthode `DrawImage` doit annuler prématurément l'exécution et arrêter le dessin d'une image. |
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


Fournit une méthode de rappel pour décider quand la méthode `DrawImage` doit annuler prématurément l'exécution et arrêter le dessin d'une image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| callbackdata | com.aspose.ms.System.IntPtr | Pointeur interne qui spécifie les données pour la méthode de rappel. Ce paramètre n'est pas transmis par toutes les surcharges de `DrawImage`. Vous pouvez tester son absence en vérifiant la valeur `System.IntPtr.Zero`. |

**Returns:**
booléen - Cette méthode renvoie true si elle décide que la méthode `DrawImage` doit arrêter prématurément l'exécution. Sinon elle renvoie false pour indiquer que la méthode `DrawImage` doit poursuivre l'exécution.
### beginInvoke(System.IntPtr callbackdata, System.AsyncCallback callback, Object state) {#beginInvoke-com.aspose.ms.System.IntPtr-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginInvoke(System.IntPtr callbackdata, System.AsyncCallback callback, Object state)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| callbackdata | com.aspose.ms.System.IntPtr |  |
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
