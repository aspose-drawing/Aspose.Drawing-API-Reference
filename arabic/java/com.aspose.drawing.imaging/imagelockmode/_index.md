---
title: ImageLockMode
second_title: مرجع API لـ Aspose.Drawing للـ Java
description: يحدد العلامات التي يتم تمريرها إلى معلمة العلامات في طريقة  .
type: docs
weight: 28
url: /ar/java/com.aspose.drawing.imaging/imagelockmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ImageLockMode extends System.Enum
```

يحدد العلامات التي يتم تمريرها إلى معلمة العلامات في طريقة [Bitmap.lockBits(Rectangle, int, int)](../../com.aspose.drawing/bitmap\#lockBits-Rectangle--int--int-). تقوم طريقة [Bitmap.lockBits(Rectangle, int, int)](../../com.aspose.drawing/bitmap\#lockBits-Rectangle--int--int-) بقفل جزء من الصورة بحيث يمكنك قراءة أو كتابة بيانات البكسل.
## الحقول

| حقل | الوصف |
| --- | --- |
| [ReadOnly](#ReadOnly) | يحدد أن جزءًا من الصورة مقفل للقراءة. |
| [WriteOnly](#WriteOnly) | يحدد أن جزءًا من الصورة مقفل للكتابة. |
| [ReadWrite](#ReadWrite) | يحدد أن جزءًا من الصورة مقفل للقراءة أو الكتابة. |
| [UserInputBuffer](#UserInputBuffer) | يحدد أن المخزن المؤقت المستخدم لقراءة أو كتابة بيانات البكسل مخصص من قبل المستخدم. |
### ReadOnly {#ReadOnly}
```
public static final int ReadOnly
```


يحدد أن جزءًا من الصورة مقفل للقراءة.

### WriteOnly {#WriteOnly}
```
public static final int WriteOnly
```


يحدد أن جزءًا من الصورة مقفل للكتابة.

### ReadWrite {#ReadWrite}
```
public static final int ReadWrite
```


يحدد أن جزءًا من الصورة مقفل للقراءة أو الكتابة.

### UserInputBuffer {#UserInputBuffer}
```
public static final int UserInputBuffer
```


يحدد أن المخزن المؤقت المستخدم لقراءة أو كتابة بيانات البكسل مخصص من قبل المستخدم. إذا تم تعيين هذه العلامة، فإن معلمة `flags` في طريقة [Bitmap.lockBits(Rectangle, int, int)](../../com.aspose.drawing/bitmap\#lockBits-Rectangle--int--int-) تعمل كمعلمة إدخال (وقد تعمل كمعلمة إخراج أيضًا). إذا تم إلغاء تعيين هذه العلامة، فإن معلمة `flags` تعمل كمعلمة إخراج فقط.

