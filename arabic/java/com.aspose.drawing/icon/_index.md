---
title: أيقونة
second_title: مرجع API لـ Aspose.Drawing للـ Java
description: يمثل أيقونة Windows وهي صورة نقطية صغيرة تُستخدم لتمثيل كائن.
type: docs
weight: 29
url: /ar/java/com.aspose.drawing/icon/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.ms.System.IDisposable
```
public final class Icon implements System.ICloneable, System.IDisposable
```

يمثل أيقونة Windows، وهي صورة نقطية صغيرة تُستخدم لتمثيل كائن. يمكن اعتبار الأيقونات كصور نقطية شفافة، رغم أن حجمها يحدده النظام.
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [Icon(String fileName)](#Icon-java.lang.String-) | ينشئ مثيلاً جديداً من الفئة [Icon](../../com.aspose.drawing/icon) باستخدام اسم الملف المحدد. |
| [Icon(InputStream stream)](#Icon-java.io.InputStream-) | ينشئ مثيلاً جديداً من الفئة [Icon](../../com.aspose.drawing/icon) باستخدام تدفق البيانات المحدد. |
| [Icon(String fileName, Size size)](#Icon-java.lang.String-com.aspose.drawing.Size-) | ينشئ مثيلاً جديداً من الفئة [Icon](../../com.aspose.drawing/icon) بالحجم المحدد من الملف المحدد. |
| [Icon(Icon original, Size size)](#Icon-com.aspose.drawing.Icon-com.aspose.drawing.Size-) | ينشئ مثيلاً جديداً من الفئة [Icon](../../com.aspose.drawing/icon) ويحاول العثور على نسخة من الأيقونة تطابق الحجم المطلوب. |
| [Icon(Object type, String resource)](#Icon-java.lang.Object-java.lang.String-) | ينشئ مثيلاً جديداً من الفئة [Icon](../../com.aspose.drawing/icon) من مورد في التجميع المحدد. |
| [Icon(InputStream stream, Size size)](#Icon-java.io.InputStream-com.aspose.drawing.Size-) | ينشئ مثيلاً جديداً من الفئة [Icon](../../com.aspose.drawing/icon) بالحجم المحدد من التدفق المحدد. |
| [Icon(String fileName, int width, int height)](#Icon-java.lang.String-int-int-) | يُنشئ مثيلاً جديدًا لفئة [Icon](../../com.aspose.drawing/icon) بالعرض والارتفاع المحددين من الملف المحدد. |
| [Icon(Icon original, int width, int height)](#Icon-com.aspose.drawing.Icon-int-int-) | يُنشئ مثيلاً جديدًا لفئة [Icon](../../com.aspose.drawing/icon) ويحاول العثور على نسخة من الأيقونة تطابق الحجم المطلوب.. |
| [Icon(InputStream stream, int width, int height)](#Icon-java.io.InputStream-int-int-) | يُنشئ مثيلاً جديدًا لفئة [Icon](../../com.aspose.drawing/icon) من تدفق البيانات المحدد وبالعرض والارتفاع المحددين. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getHandle()](#getHandle--) | يحصل على المؤشر لهذا [Icon](../../com.aspose.drawing/icon). |
| [getHeight()](#getHeight--) | يحصل على ارتفاع هذا [Icon](../../com.aspose.drawing/icon). |
| [getSize()](#getSize--) | يحصل على حجم هذا [Icon](../../com.aspose.drawing/icon). |
| [getWidth()](#getWidth--) | يحصل على عرض هذا [Icon](../../com.aspose.drawing/icon). |
| [extractAssociatedIcon(String filePath)](#extractAssociatedIcon-java.lang.String-) | يرجع تمثيلًا أيقونيًا لصورة موجودة في الملف المحدد. |
| [fromHandle(byte[] handle)](#fromHandle-byte---) | ينشئ [Icon](../../com.aspose.drawing/icon) من نوع GDI+ من المؤشر Windows المحدد إلى أيقونة (HICON). |
| [deepClone()](#deepClone--) | ينسخ الـ [Icon](../../com.aspose.drawing/icon)، مُنشئًا صورة مكررة. |
| [dispose()](#dispose--) | ينفّذ مهامًا محددة من قبل التطبيق مرتبطة بتحرير أو إطلاق أو إعادة تعيين الموارد غير المُدارة. |
| [save(OutputStream outputStream)](#save-java.io.OutputStream-) | يحفظ هذا [Icon](../../com.aspose.drawing/icon) إلى java.io.InputStream الإخراج المحدد. |
| [toBitmap()](#toBitmap--) | يحوّل هذا [Icon](../../com.aspose.drawing/icon) إلى [Bitmap](../../com.aspose.drawing/bitmap) من نوع GDI+. |
| [toString()](#toString--) | يحصل على سلسلة قابلة للقراءة تصف الـ [Icon](../../com.aspose.drawing/icon). |
### Icon(String fileName) {#Icon-java.lang.String-}
```
public Icon(String fileName)
```


ينشئ مثيلاً جديداً من الفئة [Icon](../../com.aspose.drawing/icon) باستخدام اسم الملف المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fileName | java.lang.String | الملف الذي يُحمَّل منه الـ [Icon](../../com.aspose.drawing/icon). |

### Icon(InputStream stream) {#Icon-java.io.InputStream-}
```
public Icon(InputStream stream)
```


ينشئ مثيلاً جديداً من الفئة [Icon](../../com.aspose.drawing/icon) باستخدام تدفق البيانات المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | java.io.InputStream | تدفق البيانات الذي يُحمَّل منه الـ [Icon](../../com.aspose.drawing/icon). |

### Icon(String fileName, Size size) {#Icon-java.lang.String-com.aspose.drawing.Size-}
```
public Icon(String fileName, Size size)
```


ينشئ مثيلاً جديداً من الفئة [Icon](../../com.aspose.drawing/icon) بالحجم المحدد من الملف المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fileName | java.lang.String | الاسم والمسار إلى الملف الذي يحتوي على بيانات الأيقونة. |
| size | [Size](../../com.aspose.drawing/size) | الحجم المطلوب للأيقونة. |

### Icon(Icon original, Size size) {#Icon-com.aspose.drawing.Icon-com.aspose.drawing.Size-}
```
public Icon(Icon original, Size size)
```


ينشئ مثيلاً جديداً من الفئة [Icon](../../com.aspose.drawing/icon) ويحاول العثور على نسخة من الأيقونة تطابق الحجم المطلوب.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| original | [Icon](../../com.aspose.drawing/icon) | الـ [Icon](../../com.aspose.drawing/icon) الذي يُحمَّل منه الأيقونة ذات الحجم الجديد. |
| size | [Size](../../com.aspose.drawing/size) | هيكل `Size`([.getSize](../../null/\#getSize)) يحدد الارتفاع والعرض للـ [Icon](../../com.aspose.drawing/icon) الجديد. |

### Icon(Object type, String resource) {#Icon-java.lang.Object-java.lang.String-}
```
public Icon(Object type, String resource)
```


ينشئ مثيلاً جديداً من الفئة [Icon](../../com.aspose.drawing/icon) من مورد في التجميع المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| type | java.lang.Object | نوع يحدد التجميع الذي يُبحث فيه عن المورد. |
| المورد | java.lang.String | اسم المورد للتحميل. |

### Icon(InputStream stream, Size size) {#Icon-java.io.InputStream-com.aspose.drawing.Size-}
```
public Icon(InputStream stream, Size size)
```


ينشئ مثيلاً جديداً من الفئة [Icon](../../com.aspose.drawing/icon) بالحجم المحدد من التدفق المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| دفق | java.io.InputStream | التدفق الذي يحتوي على بيانات الأيقونة. |
| size | [Size](../../com.aspose.drawing/size) | الحجم المطلوب للأيقونة. |

### Icon(String fileName, int width, int height) {#Icon-java.lang.String-int-int-}
```
public Icon(String fileName, int width, int height)
```


يُنشئ مثيلاً جديدًا لفئة [Icon](../../com.aspose.drawing/icon) بالعرض والارتفاع المحددين من الملف المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fileName | java.lang.String | الاسم والمسار إلى الملف الذي يحتوي على بيانات الـ [Icon](../../com.aspose.drawing/icon). |
| width | int | العرض المطلوب للـ [Icon](../../com.aspose.drawing/icon). |
| height | int | الارتفاع المطلوب لـ [Icon](../../com.aspose.drawing/icon). |

### Icon(Icon original, int width, int height) {#Icon-com.aspose.drawing.Icon-int-int-}
```
public Icon(Icon original, int width, int height)
```


يُنشئ مثيلاً جديدًا لفئة [Icon](../../com.aspose.drawing/icon) ويحاول العثور على نسخة من الأيقونة تطابق الحجم المطلوب..

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| original | [Icon](../../com.aspose.drawing/icon) | الأيقونة التي يتم تحميل الحجم المختلف منها. |
| العرض | int | عرض الأيقونة الجديدة. |
| الارتفاع | int | ارتفاع الأيقونة الجديدة. |

### Icon(InputStream stream, int width, int height) {#Icon-java.io.InputStream-int-int-}
```
public Icon(InputStream stream, int width, int height)
```


يُنشئ مثيلاً جديدًا لفئة [Icon](../../com.aspose.drawing/icon) من تدفق البيانات المحدد وبالعرض والارتفاع المحددين.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| دفق | java.io.InputStream | دفق البيانات الذي يتم منه تحميل الأيقونة. |
| العرض | int | العرض، بوحدات البكسل، للأيقونة. |
| الارتفاع | int | الارتفاع، بوحدات البكسل، للأيقونة. |

### getHandle() {#getHandle--}
```
public System.IntPtr getHandle()
```


يحصل على المقبض لهذا [Icon](../../com.aspose.drawing/icon). هذا ليس نسخة من المقبض؛ لا تقم بتحريره.

القيمة: مقبض Windows للأيقونة.

**Returns:**
com.aspose.ms.System.IntPtr
### getHeight() {#getHeight--}
```
public int getHeight()
```


يحصل على ارتفاع هذا [Icon](../../com.aspose.drawing/icon).

القيمة: ارتفاع هذا [Icon](../../com.aspose.drawing/icon).

**Returns:**
int
### getSize() {#getSize--}
```
public Size getSize()
```


يحصل على حجم هذا [Icon](../../com.aspose.drawing/icon).

القيمة: بنية `Size`([.getSize](../../null/\#getSize)) التي تحدد العرض والارتفاع لهذا [Icon](../../com.aspose.drawing/icon).

**Returns:**
[Size](../../com.aspose.drawing/size)
### getWidth() {#getWidth--}
```
public int getWidth()
```


يحصل على عرض هذا [Icon](../../com.aspose.drawing/icon).

القيمة: عرض هذا [Icon](../../com.aspose.drawing/icon).

**Returns:**
int
### extractAssociatedIcon(String filePath) {#extractAssociatedIcon-java.lang.String-}
```
public static Icon extractAssociatedIcon(String filePath)
```


يرجع تمثيلًا أيقونيًا لصورة موجودة في الملف المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| filePath | java.lang.String | المسار إلى الملف الذي يحتوي على صورة. |

**Returns:**
[Icon](../../com.aspose.drawing/icon) - The [Icon](../../com.aspose.drawing/icon) representation of the image that is contained in the specified file.
### fromHandle(byte[] handle) {#fromHandle-byte---}
```
public static Icon fromHandle(byte[] handle)
```


ينشئ [Icon](../../com.aspose.drawing/icon) من نوع GDI+ من المؤشر Windows المحدد إلى أيقونة (HICON).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| handle | byte[] | مقبض Windows إلى أيقونة. |

**Returns:**
[Icon](../../com.aspose.drawing/icon) - The [Icon](../../com.aspose.drawing/icon) this method creates.
### deepClone() {#deepClone--}
```
public Object deepClone()
```


ينسخ الـ [Icon](../../com.aspose.drawing/icon)، مُنشئًا صورة مكررة.

**Returns:**
java.lang.Object - كائن يمكن تحويله إلى [Icon](../../com.aspose.drawing/icon).
### dispose() {#dispose--}
```
public void dispose()
```


ينفّذ مهامًا محددة من قبل التطبيق مرتبطة بتحرير أو إطلاق أو إعادة تعيين الموارد غير المُدارة.

### save(OutputStream outputStream) {#save-java.io.OutputStream-}
```
public void save(OutputStream outputStream)
```


يحفظ هذا [Icon](../../com.aspose.drawing/icon) إلى java.io.InputStream الإخراج المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| outputStream | java.io.OutputStream | دفق الإدخال java.io.InputStream للحفظ إليه. |

### toBitmap() {#toBitmap--}
```
public Bitmap toBitmap()
```


يحوّل هذا [Icon](../../com.aspose.drawing/icon) إلى [Bitmap](../../com.aspose.drawing/bitmap) من نوع GDI+.

**Returns:**
[Bitmap](../../com.aspose.drawing/bitmap) - A [Bitmap](../../com.aspose.drawing/bitmap) that represents the converted [Icon](../../com.aspose.drawing/icon).
### toString() {#toString--}
```
public String toString()
```


يحصل على سلسلة قابلة للقراءة تصف الـ [Icon](../../com.aspose.drawing/icon).

**Returns:**
java.lang.String - سلسلة تصف [Icon](../../com.aspose.drawing/icon).
