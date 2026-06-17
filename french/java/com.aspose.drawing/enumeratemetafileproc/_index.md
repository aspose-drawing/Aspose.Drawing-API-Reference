---
title: Graphics.EnumerateMetafileProc
second_title: Référence de l'API Aspose.Drawing pour Java
description: 
type: docs
weight: 11
url: /fr/java/com.aspose.drawing/graphics.enumeratemetafileproc/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate
```
public abstract static class Graphics.EnumerateMetafileProc extends System.MulticastDelegate
```
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EnumerateMetafileProc()](#EnumerateMetafileProc--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [invoke(int recordType, int flags, int dataSize, System.IntPtr data, PlayRecordCallback callbackData)](#invoke-int-int-int-com.aspose.ms.System.IntPtr-com.aspose.drawing.imaging.PlayRecordCallback-) | Fournit une méthode de rappel pour la méthode `EnumerateMetafile`. |
| [beginInvoke(int recordType, int flags, int dataSize, System.IntPtr data, PlayRecordCallback callbackData, System.AsyncCallback callback, Object state)](#beginInvoke-int-int-int-com.aspose.ms.System.IntPtr-com.aspose.drawing.imaging.PlayRecordCallback-com.aspose.ms.System.AsyncCallback-java.lang.Object-) |  |
### EnumerateMetafileProc() {#EnumerateMetafileProc--}
```
public EnumerateMetafileProc()
```


### invoke(int recordType, int flags, int dataSize, System.IntPtr data, PlayRecordCallback callbackData) {#invoke-int-int-int-com.aspose.ms.System.IntPtr-com.aspose.drawing.imaging.PlayRecordCallback-}
```
public abstract boolean invoke(int recordType, int flags, int dataSize, System.IntPtr data, PlayRecordCallback callbackData)
```


Fournit une méthode de rappel pour la méthode `EnumerateMetafile`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| recordType | int | Membre de l'énumération [EmfPlusRecordType](../../com.aspose.drawing.imaging/emfplusrecordtype) qui spécifie le type d'enregistrement de métafichier. |
| flags | int | Ensemble de drapeaux qui spécifient les attributs de l'enregistrement. |
| dataSize | int | Nombre d'octets dans les données de l'enregistrement. |
| données | com.aspose.ms.System.IntPtr | Pointeur vers un tampon contenant les données d'enregistrement. |
| callbackData | [PlayRecordCallback](../../com.aspose.drawing.imaging/playrecordcallback) | L'argument n'est pas utilisé. |

**Returns:**
boolean - Retourne true si vous voulez continuer à énumérer les enregistrements ; sinon, false.
### beginInvoke(int recordType, int flags, int dataSize, System.IntPtr data, PlayRecordCallback callbackData, System.AsyncCallback callback, Object state) {#beginInvoke-int-int-int-com.aspose.ms.System.IntPtr-com.aspose.drawing.imaging.PlayRecordCallback-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginInvoke(int recordType, int flags, int dataSize, System.IntPtr data, PlayRecordCallback callbackData, System.AsyncCallback callback, Object state)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| recordType | int |  |
| flags | int |  |
| dataSize | int |  |
| données | com.aspose.ms.System.IntPtr |  |
| callbackData | [PlayRecordCallback](../../com.aspose.drawing.imaging/playrecordcallback) |  |
| callback | com.aspose.ms.System.AsyncCallback |  |
| état | java.lang.Object |  |

**Returns:**
com.aspose.ms.System.IAsyncResult
