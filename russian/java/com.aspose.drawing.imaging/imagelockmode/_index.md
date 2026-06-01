---
title: ImageLockMode
second_title: Справочник API Aspose.Drawing для Java
description: Указывает флаги, которые передаются параметру flags метода .
type: docs
weight: 28
url: /ru/java/com.aspose.drawing.imaging/imagelockmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ImageLockMode extends System.Enum
```

Указывает флаги, которые передаются параметру flags метода [Bitmap.lockBits(Rectangle, int, int)](../../com.aspose.drawing/bitmap\#lockBits-Rectangle--int--int-). Метод [Bitmap.lockBits(Rectangle, int, int)](../../com.aspose.drawing/bitmap\#lockBits-Rectangle--int--int-) блокирует часть изображения, чтобы вы могли читать или записывать данные пикселей.
## Поля

| Поле | Описание |
| --- | --- |
| [ReadOnly](#ReadOnly) | Указывает, что часть изображения заблокирована для чтения. |
| [WriteOnly](#WriteOnly) | Указывает, что часть изображения заблокирована для записи. |
| [ReadWrite](#ReadWrite) | Указывает, что часть изображения заблокирована для чтения или записи. |
| [UserInputBuffer](#UserInputBuffer) | Указывает, что буфер, используемый для чтения или записи данных пикселей, выделяется пользователем. |
### ReadOnly {#ReadOnly}
```
public static final int ReadOnly
```


Указывает, что часть изображения заблокирована для чтения.

### WriteOnly {#WriteOnly}
```
public static final int WriteOnly
```


Указывает, что часть изображения заблокирована для записи.

### ReadWrite {#ReadWrite}
```
public static final int ReadWrite
```


Указывает, что часть изображения заблокирована для чтения или записи.

### UserInputBuffer {#UserInputBuffer}
```
public static final int UserInputBuffer
```


Указывает, что буфер, используемый для чтения или записи данных пикселей, выделяется пользователем. Если этот флаг установлен, параметр `flags` метода [Bitmap.lockBits(Rectangle, int, int)](../../com.aspose.drawing/bitmap\#lockBits-Rectangle--int--int-) служит входным параметром (и возможно выходным). Если этот флаг сброшен, то параметр `flags` служит только выходным параметром.

