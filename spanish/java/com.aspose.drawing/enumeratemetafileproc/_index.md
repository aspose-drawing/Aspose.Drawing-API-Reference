---
title: Graphics.EnumerateMetafileProc
second_title: Referencia de la API de Aspose.Drawing para Java
description: 
type: docs
weight: 11
url: /es/java/com.aspose.drawing/graphics.enumeratemetafileproc/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate
```
public abstract static class Graphics.EnumerateMetafileProc extends System.MulticastDelegate
```
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EnumerateMetafileProc()](#EnumerateMetafileProc--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [invoke(int recordType, int flags, int dataSize, System.IntPtr data, PlayRecordCallback callbackData)](#invoke-int-int-int-com.aspose.ms.System.IntPtr-com.aspose.drawing.imaging.PlayRecordCallback-) | Proporciona un método de devolución de llamada para el método `EnumerateMetafile`. |
| [beginInvoke(int recordType, int flags, int dataSize, System.IntPtr data, PlayRecordCallback callbackData, System.AsyncCallback callback, Object state)](#beginInvoke-int-int-int-com.aspose.ms.System.IntPtr-com.aspose.drawing.imaging.PlayRecordCallback-com.aspose.ms.System.AsyncCallback-java.lang.Object-) |  |
### EnumerateMetafileProc() {#EnumerateMetafileProc--}
```
public EnumerateMetafileProc()
```


### invoke(int recordType, int flags, int dataSize, System.IntPtr data, PlayRecordCallback callbackData) {#invoke-int-int-int-com.aspose.ms.System.IntPtr-com.aspose.drawing.imaging.PlayRecordCallback-}
```
public abstract boolean invoke(int recordType, int flags, int dataSize, System.IntPtr data, PlayRecordCallback callbackData)
```


Proporciona un método de devolución de llamada para el método `EnumerateMetafile`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| recordType | int | Miembro de la enumeración [EmfPlusRecordType](../../com.aspose.drawing.imaging/emfplusrecordtype) que especifica el tipo de registro de metafile. |
| flags | int | Conjunto de indicadores que especifican atributos del registro. |
| dataSize | int | Número de bytes en los datos del registro. |
| datos | com.aspose.ms.System.IntPtr | Puntero a un búfer que contiene los datos del registro. |
| callbackData | [PlayRecordCallback](../../com.aspose.drawing.imaging/playrecordcallback) | El argumento no se utiliza. |

**Returns:**
boolean - Devuelve true si desea continuar enumerando los registros; de lo contrario, false.
### beginInvoke(int recordType, int flags, int dataSize, System.IntPtr data, PlayRecordCallback callbackData, System.AsyncCallback callback, Object state) {#beginInvoke-int-int-int-com.aspose.ms.System.IntPtr-com.aspose.drawing.imaging.PlayRecordCallback-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginInvoke(int recordType, int flags, int dataSize, System.IntPtr data, PlayRecordCallback callbackData, System.AsyncCallback callback, Object state)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| recordType | int |  |
| flags | int |  |
| dataSize | int |  |
| datos | com.aspose.ms.System.IntPtr |  |
| callbackData | [PlayRecordCallback](../../com.aspose.drawing.imaging/playrecordcallback) |  |
| callback | com.aspose.ms.System.AsyncCallback |  |
| state | java.lang.Object |  |

**Returns:**
com.aspose.ms.System.IAsyncResult
