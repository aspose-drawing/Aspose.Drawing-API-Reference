---
title: Graphics.EnumerateMetafileProc
second_title: Справочник API Aspose.Drawing для Java
description: 
type: docs
weight: 11
url: /ru/java/com.aspose.drawing/graphics.enumeratemetafileproc/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate
```
public abstract static class Graphics.EnumerateMetafileProc extends System.MulticastDelegate
```
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EnumerateMetafileProc()](#EnumerateMetafileProc--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [invoke(int recordType, int flags, int dataSize, System.IntPtr data, PlayRecordCallback callbackData)](#invoke-int-int-int-com.aspose.ms.System.IntPtr-com.aspose.drawing.imaging.PlayRecordCallback-) | Предоставляет метод обратного вызова для метода `EnumerateMetafile`. |
| [beginInvoke(int recordType, int flags, int dataSize, System.IntPtr data, PlayRecordCallback callbackData, System.AsyncCallback callback, Object state)](#beginInvoke-int-int-int-com.aspose.ms.System.IntPtr-com.aspose.drawing.imaging.PlayRecordCallback-com.aspose.ms.System.AsyncCallback-java.lang.Object-) |  |
### EnumerateMetafileProc() {#EnumerateMetafileProc--}
```
public EnumerateMetafileProc()
```


### invoke(int recordType, int flags, int dataSize, System.IntPtr data, PlayRecordCallback callbackData) {#invoke-int-int-int-com.aspose.ms.System.IntPtr-com.aspose.drawing.imaging.PlayRecordCallback-}
```
public abstract boolean invoke(int recordType, int flags, int dataSize, System.IntPtr data, PlayRecordCallback callbackData)
```


Предоставляет метод обратного вызова для метода `EnumerateMetafile`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| recordType | int | Элемент перечисления [EmfPlusRecordType](../../com.aspose.drawing.imaging/emfplusrecordtype), определяющий тип записи метафайла. |
| flags | int | Набор флагов, определяющих атрибуты записи. |
| dataSize | int | Количество байтов в данных записи. |
| данные | com.aspose.ms.System.IntPtr | Указатель на буфер, содержащий данные записи. |
| callbackData | [PlayRecordCallback](../../com.aspose.drawing.imaging/playrecordcallback) | Аргумент не используется. |

**Returns:**
boolean — верните true, если хотите продолжать перечисление записей; иначе — false.
### beginInvoke(int recordType, int flags, int dataSize, System.IntPtr data, PlayRecordCallback callbackData, System.AsyncCallback callback, Object state) {#beginInvoke-int-int-int-com.aspose.ms.System.IntPtr-com.aspose.drawing.imaging.PlayRecordCallback-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginInvoke(int recordType, int flags, int dataSize, System.IntPtr data, PlayRecordCallback callbackData, System.AsyncCallback callback, Object state)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| recordType | int |  |
| flags | int |  |
| dataSize | int |  |
| данные | com.aspose.ms.System.IntPtr |  |
| callbackData | [PlayRecordCallback](../../com.aspose.drawing.imaging/playrecordcallback) |  |
| callback | com.aspose.ms.System.AsyncCallback |  |
| state | java.lang.Object |  |

**Returns:**
com.aspose.ms.System.IAsyncResult
