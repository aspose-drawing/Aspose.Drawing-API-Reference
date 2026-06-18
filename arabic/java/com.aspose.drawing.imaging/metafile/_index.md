---
title: ملف تعريف رسومي
second_title: مرجع API لـ Aspose.Drawing للـ Java
description: يعرف ملف ميتا رسومي.
type: docs
weight: 30
url: /ar/java/com.aspose.drawing.imaging/metafile/
---
**Inheritance:**
java.lang.Object, [com.aspose.drawing.Image](../../com.aspose.drawing/image)
```
public final class Metafile extends Image
```

يعرف ملف تعريف رسومي. يحتوي ملف التعريف على سجلات تصف تسلسل عمليات الرسومات التي يمكن تسجيلها (إنشاؤها) وتشغيلها (عرضها). هذه الفئة غير قابلة للوراثة.
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [Metafile(byte[] henhmetafile, boolean deleteEmf)](#Metafile-byte---boolean-) | ينشئ مثيلاً جديدًا من الفئة [Metafile](../../com.aspose.drawing.imaging/metafile) باستخدام المقبض المحدد. |
| [Metafile(byte[] referenceHdc, int emfType)](#Metafile-byte---int-) | ينشئ مثيلاً جديدًا من الفئة [Metafile](../../com.aspose.drawing.imaging/metafile) باستخدام المقبض المحدد لسياق الجهاز وعدد تعداد [EmfType](../../com.aspose.drawing.imaging/emftype) الذي يحدد تنسيق الـ [Metafile](../../com.aspose.drawing.imaging/metafile). |
| [Metafile(String filename)](#Metafile-java.lang.String-) | ينشئ مثيلاً جديدًا من الفئة [Metafile](../../com.aspose.drawing.imaging/metafile) باستخدام اسم الملف المحدد. |
| [Metafile(String filename, byte[] referenceHdc)](#Metafile-java.lang.String-byte---) | ينشئ مثيلاً جديدًا من الفئة [Metafile](../../com.aspose.drawing.imaging/metafile) باستخدام اسم الملف المحدد. |
| [Metafile(InputStream stream)](#Metafile-java.io.InputStream-) | ينشئ مثيلاً جديدًا من الفئة [Metafile](../../com.aspose.drawing.imaging/metafile) باستخدام تدفق البيانات المحدد. |
| [Metafile(InputStream stream, byte[] referenceHdc)](#Metafile-java.io.InputStream-byte---) | ينشئ مثيلاً جديدًا من الفئة [Metafile](../../com.aspose.drawing.imaging/metafile) باستخدام تدفق البيانات المحدد ومقبض Windows لسياق الجهاز. |
| [Metafile(System.IO.Stream stream, int type)](#Metafile-com.aspose.ms.System.IO.Stream-int-) | ينشئ مثيلاً جديدًا من الفئة [Metafile](../../com.aspose.drawing.imaging/metafile) باستخدام تدفق البيانات المحدد ومقبض Windows لسياق الجهاز. |
| [Metafile(InputStream stream, byte[] referenceHdc, int type)](#Metafile-java.io.InputStream-byte---int-) | ينشئ مثيلاً جديدًا من الفئة [Metafile](../../com.aspose.drawing.imaging/metafile) باستخدام تدفق البيانات المحدد، ومقبض Windows لسياق الجهاز، وعدد تعداد [EmfType](../../com.aspose.drawing.imaging/emftype) الذي يحدد تنسيق الـ [Metafile](../../com.aspose.drawing.imaging/metafile). |
| [Metafile(InputStream stream, byte[] referenceHdc, RectangleF frameRect, int frameUnit, int type)](#Metafile-java.io.InputStream-byte---com.aspose.drawing.RectangleF-int-int-) | ينشئ مثيلاً جديدًا من الفئة [Metafile](../../com.aspose.drawing.imaging/metafile) باستخدام تدفق البيانات المحدد، ومقبض Windows لسياق الجهاز، وعدد تعداد [EmfType](../../com.aspose.drawing.imaging/emftype) الذي يحدد تنسيق الـ [Metafile](../../com.aspose.drawing.imaging/metafile). |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getWidth()](#getWidth--) | يعيد عرض هذا الـ [Metafile](../../com.aspose.drawing.imaging/metafile) بوحدة البكسل. |
| [getHeight()](#getHeight--) | يعيد ارتفاع هذا الـ [Metafile](../../com.aspose.drawing.imaging/metafile) بوحدة البكسل. |
| [getRawFormat()](#getRawFormat--) | يعيد تنسيق الملف لهذا الـ [Image](../../com.aspose.drawing/image). |
| [getPixelFormat()](#getPixelFormat--) | يعيد تنسيق البكسل لهذا الـ [Image](../../com.aspose.drawing/image). |
| [getPalette()](#getPalette--) | يحصل أو يضبط لوحة الألوان المستخدمة لهذا الـ [Image](../../com.aspose.drawing/image). |
| [setPalette(ColorPalette value)](#setPalette-com.aspose.drawing.imaging.ColorPalette-) | يحصل أو يضبط لوحة الألوان المستخدمة لهذا الـ [Image](../../com.aspose.drawing/image). |
| [getFrameDimensionsList()](#getFrameDimensionsList--) | يعيد مصفوفة من GUIDs التي تمثل أبعاد الإطارات داخل هذا الـ [Image](../../com.aspose.drawing/image). |
| [getPropertyIdList()](#getPropertyIdList--) | يعيد معرفات عناصر الخاصية المخزنة في هذا الـ [Image](../../com.aspose.drawing/image). |
| [getPropertyItems()](#getPropertyItems--) | يعيد جميع عناصر الخاصية (قطع من البيانات الوصفية) المخزنة في هذا الـ [Image](../../com.aspose.drawing/image). |
| [getMetafileHeader(InputStream stream)](#getMetafileHeader-java.io.InputStream-) | يعيد الـ [MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) المرتبط بالـ [Metafile](../../com.aspose.drawing.imaging/metafile) المحدد. |
| [getMetafileHeader(String fileName)](#getMetafileHeader-java.lang.String-) | يعيد الـ [MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) المرتبط بالـ [Metafile](../../com.aspose.drawing.imaging/metafile) المحدد. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | تقوم هذه الطريقة بتدوير، أو قلب، أو تدوير وقلب الـ [Image](../../com.aspose.drawing/image). |
| [getHenhmetafile()](#getHenhmetafile--) | يعيد مقبض Windows إلى ملف تعريف رسومي محسّن [Metafile](../../com.aspose.drawing.imaging/metafile). |
| [playRecord(int recordType, int flags, int dataSize, byte[] dataArray)](#playRecord-int-int-int-byte---) | يشغّل سجل ملف تعريف رسومي فردي. |
| [getMetafileHeader()](#getMetafileHeader--) | يعيد الـ [MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) المرتبط بهذا الـ [Metafile](../../com.aspose.drawing.imaging/metafile). |
| [getPropertyItem(int propid)](#getPropertyItem-int-) | يعيد عنصر الخاصية المحدد من هذا الـ [Image](../../com.aspose.drawing/image). |
| [removePropertyItem(int propid)](#removePropertyItem-int-) | يزيل عنصر الخاصية المحدد من هذا الـ [Image](../../com.aspose.drawing/image). |
| [setPropertyItem(PropertyItem propitem)](#setPropertyItem-com.aspose.drawing.imaging.PropertyItem-) | يخزن عنصر خاصية (قطعة من البيانات الوصفية) في هذا الـ [Image](../../com.aspose.drawing/image). |
### Metafile(byte[] henhmetafile, boolean deleteEmf) {#Metafile-byte---boolean-}
```
public Metafile(byte[] henhmetafile, boolean deleteEmf)
```


ينشئ مثيلاً جديدًا من الفئة [Metafile](../../com.aspose.drawing.imaging/metafile) باستخدام المقبض المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| henhmetafile | byte[] | مقبض إلى ملف ميتافيل محسّن. |
| deleteEmf | boolean | true لحذف مقبض ملف الميتافيل المحسّن عندما يتم حذف الـ [Metafile](../../com.aspose.drawing.imaging/metafile)؛ وإلا false. |

### Metafile(byte[] referenceHdc, int emfType) {#Metafile-byte---int-}
```
public Metafile(byte[] referenceHdc, int emfType)
```


ينشئ مثيلاً جديدًا من الفئة [Metafile](../../com.aspose.drawing.imaging/metafile) باستخدام المقبض المحدد لسياق الجهاز وعدد تعداد [EmfType](../../com.aspose.drawing.imaging/emftype) الذي يحدد تنسيق الـ [Metafile](../../com.aspose.drawing.imaging/metafile).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| referenceHdc | byte[] | المقبض إلى سياق الجهاز. |
| emfType | int | نوع [EmfType](../../com.aspose.drawing.imaging/emftype) يحدد تنسيق الـ [Metafile](../../com.aspose.drawing.imaging/metafile). |

### Metafile(String filename) {#Metafile-java.lang.String-}
```
public Metafile(String filename)
```


ينشئ مثيلاً جديدًا من الفئة [Metafile](../../com.aspose.drawing.imaging/metafile) باستخدام اسم الملف المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| filename | java.lang.String | سلسلة تمثل اسم الملف الذي يُنشأ منه الـ [Metafile](../../com.aspose.drawing.imaging/metafile) الجديد. |

### Metafile(String filename, byte[] referenceHdc) {#Metafile-java.lang.String-byte---}
```
public Metafile(String filename, byte[] referenceHdc)
```


ينشئ مثيلاً جديدًا من الفئة [Metafile](../../com.aspose.drawing.imaging/metafile) باستخدام اسم الملف المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| filename | java.lang.String | سلسلة تمثل اسم الملف الذي يُنشأ منه الـ [Metafile](../../com.aspose.drawing.imaging/metafile) الجديد. |
| referenceHdc | byte[] | مقبض Windows إلى سياق الجهاز. |

### Metafile(InputStream stream) {#Metafile-java.io.InputStream-}
```
public Metafile(InputStream stream)
```


ينشئ مثيلاً جديدًا من الفئة [Metafile](../../com.aspose.drawing.imaging/metafile) باستخدام تدفق البيانات المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | java.io.InputStream | دفق الإدخال الذي يُنشأ منه الـ [Metafile](../../com.aspose.drawing.imaging/metafile) الجديد. |

### Metafile(InputStream stream, byte[] referenceHdc) {#Metafile-java.io.InputStream-byte---}
```
public Metafile(InputStream stream, byte[] referenceHdc)
```


يُهيئ نسخة جديدة من فئة الـ [Metafile](../../com.aspose.drawing.imaging/metafile) من دفق البيانات المحدد ومقبض Windows إلى سياق الجهاز. />.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | java.io.InputStream | دفق إدخال يحتوي على البيانات لهذا الـ [Metafile](../../com.aspose.drawing.imaging/metafile). |
| referenceHdc | byte[] | مقبض Windows إلى سياق الجهاز لكائن الـ [Metafile](../../com.aspose.drawing.imaging/metafile). |

### Metafile(System.IO.Stream stream, int type) {#Metafile-com.aspose.ms.System.IO.Stream-int-}
```
public Metafile(System.IO.Stream stream, int type)
```


يُهيئ نسخة جديدة من فئة الـ [Metafile](../../com.aspose.drawing.imaging/metafile) من دفق البيانات المحدد ومقبض Windows إلى سياق الجهاز. />.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | دفق إدخال يحتوي على البيانات لهذا الـ [Metafile](../../com.aspose.drawing.imaging/metafile). |
| type | int | يجب أن يكون int 1. |

### Metafile(InputStream stream, byte[] referenceHdc, int type) {#Metafile-java.io.InputStream-byte---int-}
```
public Metafile(InputStream stream, byte[] referenceHdc, int type)
```


ينشئ مثيلاً جديدًا من الفئة [Metafile](../../com.aspose.drawing.imaging/metafile) باستخدام تدفق البيانات المحدد، ومقبض Windows لسياق الجهاز، وعدد تعداد [EmfType](../../com.aspose.drawing.imaging/emftype) الذي يحدد تنسيق الـ [Metafile](../../com.aspose.drawing.imaging/metafile).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | java.io.InputStream | دفق إدخال يحتوي على البيانات لهذا الـ [Metafile](../../com.aspose.drawing.imaging/metafile). |
| referenceHdc | byte[] | مقبض Windows إلى سياق الجهاز. |
| type | int | نوع [EmfType](../../com.aspose.drawing.imaging/emftype) يحدد تنسيق الـ [Metafile](../../com.aspose.drawing.imaging/metafile). |

### Metafile(InputStream stream, byte[] referenceHdc, RectangleF frameRect, int frameUnit, int type) {#Metafile-java.io.InputStream-byte---com.aspose.drawing.RectangleF-int-int-}
```
public Metafile(InputStream stream, byte[] referenceHdc, RectangleF frameRect, int frameUnit, int type)
```


ينشئ مثيلاً جديدًا من الفئة [Metafile](../../com.aspose.drawing.imaging/metafile) باستخدام تدفق البيانات المحدد، ومقبض Windows لسياق الجهاز، وعدد تعداد [EmfType](../../com.aspose.drawing.imaging/emftype) الذي يحدد تنسيق الـ [Metafile](../../com.aspose.drawing.imaging/metafile).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | java.io.InputStream | دفق إدخال يحتوي على البيانات لهذا الـ [Metafile](../../com.aspose.drawing.imaging/metafile). |
| referenceHdc | byte[] | مقبض Windows إلى سياق الجهاز. |
| frameRect | [RectangleF](../../com.aspose.drawing/rectanglef) | مستطيل [Rectangle](../../com.aspose.drawing/rectangle) يمثل المستطيل الذي يحد الـ [Metafile](../../com.aspose.drawing.imaging/metafile) الجديد. |
| frameUnit | int | وحدة [MetafileFrameUnit](../../com.aspose.drawing.imaging/metafileframeunit) التي تحدد وحدة القياس لـ frameRect. |
| type | int | نوع [EmfType](../../com.aspose.drawing.imaging/emftype) يحدد تنسيق الـ [Metafile](../../com.aspose.drawing.imaging/metafile). |

### getWidth() {#getWidth--}
```
public int getWidth()
```


يعيد عرض هذا الـ [Metafile](../../com.aspose.drawing.imaging/metafile) بوحدة البكسل.

**Returns:**
int
### getHeight() {#getHeight--}
```
public int getHeight()
```


يعيد ارتفاع هذا الـ [Metafile](../../com.aspose.drawing.imaging/metafile) بوحدة البكسل.

**Returns:**
int - الارتفاع، بوحدات البكسل، لهذا الـ [Metafile](../../com.aspose.drawing.imaging/metafile).
### getRawFormat() {#getRawFormat--}
```
public ImageFormat getRawFormat()
```


يعيد تنسيق الملف لهذا الـ [Image](../../com.aspose.drawing/image).

**Returns:**
[ImageFormat](../../com.aspose.drawing.imaging/imageformat) - The [ImageFormat](../../com.aspose.drawing.imaging/imageformat) that represents the file format of this [Image](../../com.aspose.drawing/image).
### getPixelFormat() {#getPixelFormat--}
```
public int getPixelFormat()
```


يعيد تنسيق البكسل لهذا الـ [Image](../../com.aspose.drawing/image).

**Returns:**
int - `PixelFormat`([Image.getPixelFormat](../../com.aspose.drawing/image\#getPixelFormat)) الذي يمثل تنسيق البكسل لهذا الـ [Image](../../com.aspose.drawing/image).
### getPalette() {#getPalette--}
```
public ColorPalette getPalette()
```


يحصل أو يضبط لوحة الألوان المستخدمة لهذا الـ [Image](../../com.aspose.drawing/image).

**Returns:**
[ColorPalette](../../com.aspose.drawing.imaging/colorpalette) - A [ColorPalette](../../com.aspose.drawing.imaging/colorpalette) that represents the color palette used for this [Image](../../com.aspose.drawing/image).
### setPalette(ColorPalette value) {#setPalette-com.aspose.drawing.imaging.ColorPalette-}
```
public void setPalette(ColorPalette value)
```


يحصل أو يضبط لوحة الألوان المستخدمة لهذا الـ [Image](../../com.aspose.drawing/image).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [ColorPalette](../../com.aspose.drawing.imaging/colorpalette) |  |

### getFrameDimensionsList() {#getFrameDimensionsList--}
```
public UUID[] getFrameDimensionsList()
```


يعيد مصفوفة من GUIDs التي تمثل أبعاد الإطارات داخل هذا الـ [Image](../../com.aspose.drawing/image).

**Returns:**
java.util.UUID[] - مصفوفة من GUIDs التي تحدد أبعاد الإطارات داخل هذا الـ [Image](../../com.aspose.drawing/image) من الأكثر أهمية إلى الأقل.
### getPropertyIdList() {#getPropertyIdList--}
```
public int[] getPropertyIdList()
```


يعيد معرفات عناصر الخاصية المخزنة في هذا الـ [Image](../../com.aspose.drawing/image).

**Returns:**
int[] - مصفوفة من معرفات الخصائص، واحدة لكل عنصر خاصية مخزن في هذه الصورة.
### getPropertyItems() {#getPropertyItems--}
```
public PropertyItem[] getPropertyItems()
```


يعيد جميع عناصر الخاصية (قطع من البيانات الوصفية) المخزنة في هذا الـ [Image](../../com.aspose.drawing/image).

**Returns:**
com.aspose.drawing.imaging.PropertyItem[] - مصفوفة من كائنات [PropertyItem](../../com.aspose.drawing.imaging/propertyitem) ، واحدة لكل عنصر خاصية مخزن في الصورة.
### getMetafileHeader(InputStream stream) {#getMetafileHeader-java.io.InputStream-}
```
public static MetafileHeader getMetafileHeader(InputStream stream)
```


يعيد الـ [MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) المرتبط بالـ [Metafile](../../com.aspose.drawing.imaging/metafile) المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | java.io.InputStream | دفق إدخال يحتوي على الـ [Metafile](../../com.aspose.drawing.imaging/metafile) الذي يتم استرجاع رأسه. |

**Returns:**
[MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) - The [MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) associated with the specified [Metafile](../../com.aspose.drawing.imaging/metafile).
### getMetafileHeader(String fileName) {#getMetafileHeader-java.lang.String-}
```
public static MetafileHeader getMetafileHeader(String fileName)
```


يعيد الـ [MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) المرتبط بالـ [Metafile](../../com.aspose.drawing.imaging/metafile) المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fileName | java.lang.String | سلسلة تحتوي على اسم الـ [Metafile](../../com.aspose.drawing.imaging/metafile) الذي يتم استرجاع رأسه. |

**Returns:**
[MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) - The [MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) associated with the specified [Metafile](../../com.aspose.drawing.imaging/metafile).
### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


تقوم هذه الطريقة بتدوير، أو قلب، أو تدوير وقلب الـ [Image](../../com.aspose.drawing/image).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rotateFlipType | int | عضو [RotateFlipType](../../com.aspose.drawing/rotatefliptype) يحدد نوع الدوران والقلب لتطبيقه على الصورة. |

### getHenhmetafile() {#getHenhmetafile--}
```
public System.IntPtr getHenhmetafile()
```


يعيد مقبض Windows إلى ملف تعريف رسومي محسّن [Metafile](../../com.aspose.drawing.imaging/metafile).

**Returns:**
com.aspose.ms.System.IntPtr - مقبض Windows لهذا الـ [Metafile](../../com.aspose.drawing.imaging/metafile) المحسّن.
### playRecord(int recordType, int flags, int dataSize, byte[] dataArray) {#playRecord-int-int-int-byte---}
```
public void playRecord(int recordType, int flags, int dataSize, byte[] dataArray)
```


يشغّل سجل ملف تعريف رسومي فردي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| recordType | int | عنصر من [EmfPlusRecordType](../../com.aspose.drawing.imaging/emfplusrecordtype) يحدد نوع سجل الميتافايل الذي يتم تشغيله. |
| flags | int | مجموعة من العلامات التي تحدد سمات السجل. |
| dataSize | int | عدد البايتات في بيانات السجل. |
| dataArray | byte[] | مصفوفة من البايتات تحتوي على بيانات السجل. |

### getMetafileHeader() {#getMetafileHeader--}
```
public MetafileHeader getMetafileHeader()
```


يعيد الـ [MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) المرتبط بهذا الـ [Metafile](../../com.aspose.drawing.imaging/metafile).

**Returns:**
[MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) - The [MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) associated with this [Metafile](../../com.aspose.drawing.imaging/metafile).
### getPropertyItem(int propid) {#getPropertyItem-int-}
```
public PropertyItem getPropertyItem(int propid)
```


يعيد عنصر الخاصية المحدد من هذا الـ [Image](../../com.aspose.drawing/image).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| propid | int | معرف عنصر الخاصية للحصول عليه. |

**Returns:**
[PropertyItem](../../com.aspose.drawing.imaging/propertyitem) - The [PropertyItem](../../com.aspose.drawing.imaging/propertyitem) this method gets.
### removePropertyItem(int propid) {#removePropertyItem-int-}
```
public void removePropertyItem(int propid)
```


يزيل عنصر الخاصية المحدد من هذا الـ [Image](../../com.aspose.drawing/image).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| propid | int | معرف عنصر الخاصية لإزالته. |

### setPropertyItem(PropertyItem propitem) {#setPropertyItem-com.aspose.drawing.imaging.PropertyItem-}
```
public void setPropertyItem(PropertyItem propitem)
```


يخزن عنصر خاصية (قطعة من البيانات الوصفية) في هذا الـ [Image](../../com.aspose.drawing/image).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| propitem | [PropertyItem](../../com.aspose.drawing.imaging/propertyitem) | عنصر [PropertyItem](../../com.aspose.drawing.imaging/propertyitem) الذي سيتم تخزينه. |

