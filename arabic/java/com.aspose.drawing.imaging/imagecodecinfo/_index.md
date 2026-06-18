---
title: ImageCodecInfo
second_title: مرجع API لـ Aspose.Drawing للـ Java
description: The  class provides the necessary storage members and methods to retrieve all pertinent information about the installed image encoders and decoders called codecs.
type: docs
weight: 25
url: /ar/java/com.aspose.drawing.imaging/imagecodecinfo/
---
**Inheritance:**
java.lang.Object
```
public final class ImageCodecInfo
```

الفئة [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo) توفر الأعضاء وطرق التخزين اللازمة لاسترجاع جميع المعلومات ذات الصلة حول المشفرات والمفككات الصور المثبتة (المعروفة باسم codecs). غير قابلة للوراثة.
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [ImageCodecInfo()](#ImageCodecInfo--) | ينشئ مثيلاً جديداً من الفئة [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo). |
| [ImageCodecInfo(UUID clsid, String codecName, String filenameExtension, String formatDescription, UUID formatID, String mimeType, int version)](#ImageCodecInfo-java.util.UUID-java.lang.String-java.lang.String-java.lang.String-java.util.UUID-java.lang.String-int-) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getClsid()](#getClsid--) | يحصل على بنية java.util.UUID تحتوي على GUID يحدد مشفرًا معينًا. |
| [setClsid(UUID value)](#setClsid-java.util.UUID-) | يضبط بنية java.util.UUID تحتوي على GUID يحدد مشفرًا معينًا. |
| [getFormatID()](#getFormatID--) | يحصل على بنية java.util.UUID تحتوي على GUID يحدد تنسيق المشفر. |
| [setFormatID(UUID value)](#setFormatID-java.util.UUID-) | يضبط بنية java.util.UUID تحتوي على GUID يحدد تنسيق المشفر. |
| [getCodecName()](#getCodecName--) | يحصل أو يضبط سلسلة تحتوي على اسم المشفر. |
| [setCodecName(String value)](#setCodecName-java.lang.String-) | يحصل أو يضبط سلسلة تحتوي على اسم المشفر. |
| [getFormatDescription()](#getFormatDescription--) | يحصل أو يضبط سلسلة تصف تنسيق ملف المشفر. |
| [setFormatDescription(String value)](#setFormatDescription-java.lang.String-) | يحصل أو يضبط سلسلة تصف تنسيق ملف المشفر. |
| [getFilenameExtension()](#getFilenameExtension--) | يحصل أو يضبط سلسلة تحتوي على امتداد(ات) اسم الملف المستخدمة في المشفر. |
| [setFilenameExtension(String value)](#setFilenameExtension-java.lang.String-) | يحصل أو يضبط سلسلة تحتوي على امتداد(ات) اسم الملف المستخدمة في المشفر. |
| [getMimeType()](#getMimeType--) | يحصل أو يضبط سلسلة تحتوي على نوع MIME (Multipurpose Internet Mail Extensions) للمشفر. |
| [setMimeType(String value)](#setMimeType-java.lang.String-) | يحصل أو يضبط سلسلة تحتوي على نوع MIME (Multipurpose Internet Mail Extensions) للمشفر. |
| [getVersion()](#getVersion--) | يحصل أو يضبط رقم إصدار المشفر. |
| [setVersion(int value)](#setVersion-int-) | يحصل أو يضبط رقم إصدار المشفر. |
| [getSignaturePatterns()](#getSignaturePatterns--) | يحصل أو يضبط مصفوفة ثنائية الأبعاد من البايتات تمثل توقيع المشفر. |
| [setSignaturePatterns(byte[][] value)](#setSignaturePatterns-byte-----) | يحصل أو يضبط مصفوفة ثنائية الأبعاد من البايتات تمثل توقيع المشفر. |
| [getSignatureMasks()](#getSignatureMasks--) | يحصل أو يضبط مصفوفة ثنائية الأبعاد من البايتات يمكن استخدامها كمرشح. |
| [setSignatureMasks(byte[][] value)](#setSignatureMasks-byte-----) | يحصل أو يضبط مصفوفة ثنائية الأبعاد من البايتات يمكن استخدامها كمرشح. |
| [getImageDecoders()](#getImageDecoders--) | يرجع مصفوفة من كائنات [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo) التي تحتوي على معلومات حول مفككات الصور المدمجة في GDI+. |
| [getImageEncoders()](#getImageEncoders--) | يرجع مصفوفة من كائنات [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo) التي تحتوي على معلومات حول مشفرات الصور المدمجة في GDI+. |
### ImageCodecInfo() {#ImageCodecInfo--}
```
public ImageCodecInfo()
```


ينشئ مثيلاً جديداً من الفئة [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo).

### ImageCodecInfo(UUID clsid, String codecName, String filenameExtension, String formatDescription, UUID formatID, String mimeType, int version) {#ImageCodecInfo-java.util.UUID-java.lang.String-java.lang.String-java.lang.String-java.util.UUID-java.lang.String-int-}
```
public ImageCodecInfo(UUID clsid, String codecName, String filenameExtension, String formatDescription, UUID formatID, String mimeType, int version)
```


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| clsid | java.util.UUID |  |
| codecName | java.lang.String |  |
| filenameExtension | java.lang.String |  |
| formatDescription | java.lang.String |  |
| formatID | java.util.UUID |  |
| mimeType | java.lang.String |  |
| version | int |  |

### getClsid() {#getClsid--}
```
public UUID getClsid()
```


يحصل على بنية java.util.UUID تحتوي على GUID يحدد مشفرًا معينًا.

**Returns:**
java.util.UUID - java.util.UUID واحد
### setClsid(UUID value) {#setClsid-java.util.UUID-}
```
public void setClsid(UUID value)
```


يضبط بنية java.util.UUID تحتوي على GUID يحدد مشفرًا معينًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | java.util.UUID | java.util.UUID واحد |

### getFormatID() {#getFormatID--}
```
public UUID getFormatID()
```


يحصل على بنية java.util.UUID تحتوي على GUID يحدد تنسيق المشفر.

**Returns:**
java.util.UUID - java.util.UUID واحد
### setFormatID(UUID value) {#setFormatID-java.util.UUID-}
```
public void setFormatID(UUID value)
```


يضبط بنية java.util.UUID تحتوي على GUID يحدد تنسيق المشفر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | java.util.UUID | java.util.UUID واحد |

### getCodecName() {#getCodecName--}
```
public String getCodecName()
```


يحصل أو يضبط سلسلة تحتوي على اسم المشفر.

**Returns:**
java.lang.String
### setCodecName(String value) {#setCodecName-java.lang.String-}
```
public void setCodecName(String value)
```


يحصل أو يضبط سلسلة تحتوي على اسم المشفر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getFormatDescription() {#getFormatDescription--}
```
public String getFormatDescription()
```


يحصل أو يضبط سلسلة تصف تنسيق ملف المشفر.

**Returns:**
java.lang.String
### setFormatDescription(String value) {#setFormatDescription-java.lang.String-}
```
public void setFormatDescription(String value)
```


يحصل أو يضبط سلسلة تصف تنسيق ملف المشفر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getFilenameExtension() {#getFilenameExtension--}
```
public String getFilenameExtension()
```


يحصل أو يعيّن السلسلة التي تحتوي على امتداد(ات) اسم الملف المستخدمة في برنامج الترميز. يتم فصل الامتدادات بفواصل منقوطة.

**Returns:**
java.lang.String
### setFilenameExtension(String value) {#setFilenameExtension-java.lang.String-}
```
public void setFilenameExtension(String value)
```


يحصل أو يعيّن السلسلة التي تحتوي على امتداد(ات) اسم الملف المستخدمة في برنامج الترميز. يتم فصل الامتدادات بفواصل منقوطة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getMimeType() {#getMimeType--}
```
public String getMimeType()
```


يحصل أو يضبط سلسلة تحتوي على نوع MIME (Multipurpose Internet Mail Extensions) للمشفر.

**Returns:**
java.lang.String
### setMimeType(String value) {#setMimeType-java.lang.String-}
```
public void setMimeType(String value)
```


يحصل أو يضبط سلسلة تحتوي على نوع MIME (Multipurpose Internet Mail Extensions) للمشفر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getVersion() {#getVersion--}
```
public int getVersion()
```


يحصل أو يضبط رقم إصدار المشفر.

**Returns:**
int
### setVersion(int value) {#setVersion-int-}
```
public void setVersion(int value)
```


يحصل أو يضبط رقم إصدار المشفر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getSignaturePatterns() {#getSignaturePatterns--}
```
public byte[][] getSignaturePatterns()
```


يحصل أو يضبط مصفوفة ثنائية الأبعاد من البايتات تمثل توقيع المشفر.

**Returns:**
byte[][]
### setSignaturePatterns(byte[][] value) {#setSignaturePatterns-byte-----}
```
public void setSignaturePatterns(byte[][] value)
```


يحصل أو يضبط مصفوفة ثنائية الأبعاد من البايتات تمثل توقيع المشفر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | byte[][] |  |

### getSignatureMasks() {#getSignatureMasks--}
```
public byte[][] getSignatureMasks()
```


يحصل أو يضبط مصفوفة ثنائية الأبعاد من البايتات يمكن استخدامها كمرشح.

**Returns:**
byte[][]
### setSignatureMasks(byte[][] value) {#setSignatureMasks-byte-----}
```
public void setSignatureMasks(byte[][] value)
```


يحصل أو يضبط مصفوفة ثنائية الأبعاد من البايتات يمكن استخدامها كمرشح.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | byte[][] |  |

### getImageDecoders() {#getImageDecoders--}
```
public static ImageCodecInfo[] getImageDecoders()
```


يرجع مصفوفة من كائنات [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo) التي تحتوي على معلومات حول مفككات الصور المدمجة في GDI+.

**Returns:**
com.aspose.drawing.imaging.ImageCodecInfo[] - مصفوفة من كائنات [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo). كل كائن [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo) في المصفوفة يحتوي على معلومات حول أحد مفككات الترميز المدمجة للصور.
### getImageEncoders() {#getImageEncoders--}
```
public static ImageCodecInfo[] getImageEncoders()
```


يرجع مصفوفة من كائنات [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo) التي تحتوي على معلومات حول مشفرات الصور المدمجة في GDI+.

**Returns:**
com.aspose.drawing.imaging.ImageCodecInfo[] - مصفوفة من كائنات [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo). كل كائن [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo) في المصفوفة يحتوي على معلومات حول أحد مشفرات الصور المدمجة.
