---
title: FontFamily
second_title: مرجع API لـ Aspose.Drawing للـ Java
description: يعرّف مجموعة من الأنماط التي لها تصميم أساسي مشابه وبعض الاختلافات في الأنماط.
type: docs
weight: 24
url: /ar/java/com.aspose.drawing/fontfamily/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public final class FontFamily implements System.IDisposable
```

يُعرّف مجموعة من الخطوط التي لها تصميم أساسي مشابه وبعض الاختلافات في الأنماط. لا يمكن وراثة هذه الفئة.
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [FontFamily(String name)](#FontFamily-java.lang.String-) | ينشئ مثيلًا جديدًا من الفئة [FontFamily](../../com.aspose.drawing/fontfamily) بالاسم المحدد. |
| [FontFamily(String name, FontCollection fontCollection)](#FontFamily-java.lang.String-com.aspose.drawing.FontCollection-) | ينشئ مثيلًا جديدًا من الفئة [FontFamily](../../com.aspose.drawing/fontfamily). |
| [FontFamily(String name, FontFamilyDefinition definition)](#FontFamily-java.lang.String-com.aspose.drawing.FontFamilyDefinition-) | ينشئ مثيلًا جديدًا من الفئة [FontFamily](../../com.aspose.drawing/fontfamily). |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getFamilies()](#getFamilies--) | يحصل على مصفوفة تحتوي على جميع كائنات [FontFamily](../../com.aspose.drawing/fontfamily) المرتبطة بسياق الرسومات الحالي. |
| [getGenericSansSerif()](#getGenericSansSerif--) | يحصل على كائن [FontFamily](../../com.aspose.drawing/fontfamily) عام من نوع sans serif. |
| [getGenericSerif()](#getGenericSerif--) | يحصل على كائن [FontFamily](../../com.aspose.drawing/fontfamily) عام من نوع serif. |
| [getGenericMonospace()](#getGenericMonospace--) | يحصل على كائن [FontFamily](../../com.aspose.drawing/fontfamily) عام من نوع monospace. |
| [getName()](#getName--) | يحصل على اسم هذه [FontFamily](../../com.aspose.drawing/fontfamily). |
| [dispose()](#dispose--) | يطلق جميع الموارد المستخدمة من قبل هذه [FontFamily](../../com.aspose.drawing/fontfamily). |
| [getName(int language)](#getName-int-) | يعيد الاسم، باللغة المحددة، لهذه [FontFamily](../../com.aspose.drawing/fontfamily). |
| [isStyleAvailable(int style)](#isStyleAvailable-int-) | يشير إلى ما إذا كان تعداد [FontStyle](../../com.aspose.drawing/fontstyle) المحدد متاحًا. |
| [getEmHeight(int style)](#getEmHeight-int-) | يحصل على الارتفاع، بوحدات تصميم الخط، لمربع EM للنمط المحدد. |
| [getCellAscent(int style)](#getCellAscent-int-) | يعيد ارتفاع الخلية الصاعد، بوحدات التصميم، لـ [FontFamily](../../com.aspose.drawing/fontfamily) الخاص بالنمط المحدد. |
| [getCellDescent(int style)](#getCellDescent-int-) | يعيد انخفاض الخلية، بوحدات التصميم، لـ [FontFamily](../../com.aspose.drawing/fontfamily) الخاص بالنمط المحدد. |
| [hashCode()](#hashCode--) | يحصل على قيمة تجزئة لهذا [FontFamily](../../com.aspose.drawing/fontfamily). |
| [equals(Object obj)](#equals-java.lang.Object-) | يشير إلى ما إذا كان الكائن المحدد هو [FontFamily](../../com.aspose.drawing/fontfamily) ويتطابق مع هذا [FontFamily](../../com.aspose.drawing/fontfamily). |
| [getLineSpacing(int style)](#getLineSpacing-int-) | يعيد تباعد الأسطر، بوحدات التصميم، لـ [FontFamily](../../com.aspose.drawing/fontfamily) الخاص بالنمط المحدد. |
### FontFamily(String name) {#FontFamily-java.lang.String-}
```
public FontFamily(String name)
```


ينشئ مثيلًا جديدًا من الفئة [FontFamily](../../com.aspose.drawing/fontfamily) بالاسم المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| name | java.lang.String | اسم [FontFamily](../../com.aspose.drawing/fontfamily) الجديد. |

### FontFamily(String name, FontCollection fontCollection) {#FontFamily-java.lang.String-com.aspose.drawing.FontCollection-}
```
public FontFamily(String name, FontCollection fontCollection)
```


ينشئ مثيلًا جديدًا من الفئة [FontFamily](../../com.aspose.drawing/fontfamily).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الاسم | java.lang.String | اسم عائلة الخط. |
| fontCollection | [FontCollection](../../com.aspose.drawing/fontcollection) | مجموعة الخطوط. |

### FontFamily(String name, FontFamilyDefinition definition) {#FontFamily-java.lang.String-com.aspose.drawing.FontFamilyDefinition-}
```
public FontFamily(String name, FontFamilyDefinition definition)
```


ينشئ مثيلًا جديدًا من الفئة [FontFamily](../../com.aspose.drawing/fontfamily).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الاسم | java.lang.String | اسم عائلة الخط. |
| definition | [FontFamilyDefinition](../../com.aspose.drawing/fontfamilydefinition) | التعريف. |

### getFamilies() {#getFamilies--}
```
public static FontFamily[] getFamilies()
```


يحصل على مصفوفة تحتوي على جميع كائنات [FontFamily](../../com.aspose.drawing/fontfamily) المرتبطة بسياق الرسومات الحالي.

**Returns:**
com.aspose.drawing.FontFamily[] - مصفوفة من كائنات [FontFamily](../../com.aspose.drawing/fontfamily) المرتبطة بسياق الرسومات الحالي.
### getGenericSansSerif() {#getGenericSansSerif--}
```
public static FontFamily getGenericSansSerif()
```


يحصل على كائن [FontFamily](../../com.aspose.drawing/fontfamily) عام من نوع sans serif.

**Returns:**
[FontFamily](../../com.aspose.drawing/fontfamily) - A [FontFamily](../../com.aspose.drawing/fontfamily) object that represents a generic sans serif font.
### getGenericSerif() {#getGenericSerif--}
```
public static FontFamily getGenericSerif()
```


يحصل على كائن [FontFamily](../../com.aspose.drawing/fontfamily) عام من نوع serif.

**Returns:**
[FontFamily](../../com.aspose.drawing/fontfamily) - A [FontFamily](../../com.aspose.drawing/fontfamily) that represents a generic serif font.
### getGenericMonospace() {#getGenericMonospace--}
```
public static FontFamily getGenericMonospace()
```


يحصل على كائن [FontFamily](../../com.aspose.drawing/fontfamily) عام من نوع monospace.

**Returns:**
[FontFamily](../../com.aspose.drawing/fontfamily) - A [FontFamily](../../com.aspose.drawing/fontfamily) that represents a generic monospace font.
### getName() {#getName--}
```
public String getName()
```


يحصل على اسم هذه [FontFamily](../../com.aspose.drawing/fontfamily).

**Returns:**
java.lang.String - سلسلة تمثل اسم هذا [FontFamily](../../com.aspose.drawing/fontfamily).
### dispose() {#dispose--}
```
public void dispose()
```


يطلق جميع الموارد المستخدمة من قبل هذه [FontFamily](../../com.aspose.drawing/fontfamily).

### getName(int language) {#getName-int-}
```
public String getName(int language)
```


يعيد الاسم، باللغة المحددة، لهذه [FontFamily](../../com.aspose.drawing/fontfamily).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| اللغة | int | اللغة التي يُرجع بها الاسم. |

**Returns:**
java.lang.String - سلسلة تمثل الاسم، باللغة المحددة، لهذا [FontFamily](../../com.aspose.drawing/fontfamily).
### isStyleAvailable(int style) {#isStyleAvailable-int-}
```
public boolean isStyleAvailable(int style)
```


يشير إلى ما إذا كان تعداد [FontStyle](../../com.aspose.drawing/fontstyle) المحدد متاحًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| style | int | الـ [FontStyle](../../com.aspose.drawing/fontstyle) لاختباره. |

**Returns:**
boolean - true إذا كان [FontStyle](../../com.aspose.drawing/fontstyle) المحدد متاحًا؛ وإلا false.
### getEmHeight(int style) {#getEmHeight-int-}
```
public int getEmHeight(int style)
```


يحصل على الارتفاع، بوحدات تصميم الخط، لمربع EM للنمط المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| style | int | الـ [FontStyle](../../com.aspose.drawing/fontstyle) الذي تريد الحصول على ارتفاع EM له. |

**Returns:**
int - ارتفاع مربع EM.
### getCellAscent(int style) {#getCellAscent-int-}
```
public int getCellAscent(int style)
```


يعيد ارتفاع الخلية الصاعد، بوحدات التصميم، لـ [FontFamily](../../com.aspose.drawing/fontfamily) الخاص بالنمط المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| style | int | ـ [FontStyle](../../com.aspose.drawing/fontstyle) يحتوي على معلومات النمط للخط. |

**Returns:**
int - ارتفاع الخلية الصاعد لهذا [FontFamily](../../com.aspose.drawing/fontfamily) الذي يستخدم [FontStyle](../../com.aspose.drawing/fontstyle) المحدد.
### getCellDescent(int style) {#getCellDescent-int-}
```
public int getCellDescent(int style)
```


يعيد انخفاض الخلية، بوحدات التصميم، لـ [FontFamily](../../com.aspose.drawing/fontfamily) الخاص بالنمط المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| style | int | ـ [FontStyle](../../com.aspose.drawing/fontstyle) يحتوي على معلومات النمط للخط. |

**Returns:**
int - مقياس انخفاض الخلية لهذا [FontFamily](../../com.aspose.drawing/fontfamily) الذي يستخدم [FontStyle](../../com.aspose.drawing/fontstyle) المحدد.
### hashCode() {#hashCode--}
```
public int hashCode()
```


يحصل على قيمة تجزئة لهذا [FontFamily](../../com.aspose.drawing/fontfamily).

**Returns:**
int - قيمة التجزئة لهذا [FontFamily](../../com.aspose.drawing/fontfamily).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


يشير إلى ما إذا كان الكائن المحدد هو [FontFamily](../../com.aspose.drawing/fontfamily) ويتطابق مع هذا [FontFamily](../../com.aspose.drawing/fontfamily).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| obj | java.lang.Object | الكائن المراد اختباره. |

**Returns:**
boolean - `true` إذا كان `obj` هو [FontFamily](../../com.aspose.drawing/fontfamily) ويتطابق مع هذا [FontFamily](../../com.aspose.drawing/fontfamily)؛ وإلا `false`.
### getLineSpacing(int style) {#getLineSpacing-int-}
```
public int getLineSpacing(int style)
```


يعيد تباعد السطر، بوحدات التصميم، لـ [FontFamily](../../com.aspose.drawing/fontfamily) الخاص بالنمط المحدد. تباعد السطر هو المسافة العمودية بين الخطوط الأساسية لسطرين متتاليين من النص.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| style | int | [FontStyle](../../com.aspose.drawing/fontstyle) الذي سيتم تطبيقه. |

**Returns:**
int - المسافة بين سطرين متتاليين من النص.
