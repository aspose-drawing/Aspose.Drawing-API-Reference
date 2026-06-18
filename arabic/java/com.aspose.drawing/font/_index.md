---
title: Font
second_title: مرجع API لـ Aspose.Drawing للـ Java
description: يحدد تنسيقًا معينًا للنص بما في ذلك نوع الخط وحجمه وسمات النمط.
type: docs
weight: 21
url: /ar/java/com.aspose.drawing/font/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public final class Font implements System.IDisposable
```

يحدد تنسيقًا معينًا للنص، بما في ذلك نوع الخط، والحجم، وسمات النمط. لا يمكن وراثة هذه الفئة.
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [Font(Font prototype, int newStyle)](#Font-com.aspose.drawing.Font-int-) | يُنشئ مثيلًا جديدًا من الفئة [Font](../../com.aspose.drawing/font) باستخدام [Font](../../com.aspose.drawing/font) الموجود المحدد وتعداد [FontStyle](../../com.aspose.drawing/fontstyle). |
| [Font(FontFamily family, float emSize)](#Font-com.aspose.drawing.FontFamily-float-) | يُهيئ نسخة جديدة من الفئة [Font](../../com.aspose.drawing/font) class. |
| [Font(FontFamily family, float emSize, int style)](#Font-com.aspose.drawing.FontFamily-float-int-) | يُهيئ نسخة جديدة من الفئة [Font](../../com.aspose.drawing/font) باستخدام حجم ونمط محددين.. |
| [Font(FontFamily family, float emSize, int style, int unit)](#Font-com.aspose.drawing.FontFamily-float-int-int-) | يُهيئ نسخة جديدة من الفئة [Font](../../com.aspose.drawing/font) باستخدام حجم ونمط ووحدة محددين. |
| [Font(FontFamily family, float emSize, int style, int unit, byte gdiCharSet)](#Font-com.aspose.drawing.FontFamily-float-int-int-byte-) | يُهيئ نسخة جديدة من الفئة [Font](../../com.aspose.drawing/font) باستخدام حجم ونمط ووحدة ومجموعة أحرف محددة.. |
| [Font(FontFamily family, float emSize, int style, int unit, byte gdiCharSet, boolean gdiVerticalFont)](#Font-com.aspose.drawing.FontFamily-float-int-int-byte-boolean-) | يُهيئ نسخة جديدة من الفئة [Font](../../com.aspose.drawing/font) باستخدام حجم ونمط ووحدة ومجموعة أحرف محددة.. |
| [Font(String familyName, float emSize)](#Font-java.lang.String-float-) | يُهيئ نسخة جديدة من الفئة [Font](../../com.aspose.drawing/font) باستخدام حجم محدد. |
| [Font(String familyName, float emSize, int style)](#Font-java.lang.String-float-int-) | يُهيئ نسخة جديدة من الفئة [Font](../../com.aspose.drawing/font) باستخدام حجم ونمط محددين. |
| [Font(String familyName, float emSize, int style, int unit)](#Font-java.lang.String-float-int-int-) | يُهيئ نسخة جديدة من الفئة [Font](../../com.aspose.drawing/font) باستخدام حجم ونمط ووحدة محددين. |
| [Font(String familyName, float emSize, int style, int unit, byte gdiCharSet)](#Font-java.lang.String-float-int-int-byte-) | يُهيئ نسخة جديدة من الفئة [Font](../../com.aspose.drawing/font) باستخدام حجم ونمط ووحدة ومجموعة أحرف محددة. |
| [Font(String familyName, float emSize, int style, int unit, byte gdiCharSet, boolean gdiVerticalFont)](#Font-java.lang.String-float-int-int-byte-boolean-) | يُهيئ نسخة جديدة من الفئة [Font](../../com.aspose.drawing/font) باستخدام الحجم والنمط والوحدة ومجموعة الأحرف المحددة. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getFontFamily()](#getFontFamily--) | يحصل على `FontFamily`([.getFontFamily](../../null/\#getFontFamily)) المرتبط بهذه [Font](../../com.aspose.drawing/font). |
| [getBold()](#getBold--) | يحصل على قيمة تشير إلى ما إذا كانت هذه [Font](../../com.aspose.drawing/font) عريضة. |
| [getGdiCharSet()](#getGdiCharSet--) | يحصل على قيمة بايت تحدد مجموعة أحرف GDI التي تستخدمها هذه [Font](../../com.aspose.drawing/font). |
| [getGdiVerticalFont()](#getGdiVerticalFont--) | يحصل على قيمة تشير إلى ما إذا كانت هذه [Font](../../com.aspose.drawing/font) مستمدة من خط عمودي GDI.. |
| [getItalic()](#getItalic--) | يحصل على قيمة تشير إلى ما إذا كانت هذه [Font](../../com.aspose.drawing/font) مائلة. |
| [getName()](#getName--) | يحصل على اسم الوجه لهذه [Font](../../com.aspose.drawing/font). |
| [getStrikeout()](#getStrikeout--) | يحصل على قيمة تشير إلى ما إذا كانت هذه [Font](../../com.aspose.drawing/font) تحدد خطًا أفقيًا عبر الخط. |
| [getUnderline()](#getUnderline--) | يحصل على قيمة تشير إلى ما إذا كانت هذه [Font](../../com.aspose.drawing/font) مسطّرة. |
| [getStyle()](#getStyle--) | يحصل على معلومات النمط لهذه [Font](../../com.aspose.drawing/font). |
| [getSize()](#getSize--) | يحصل على حجم الـ em لهذه [Font](../../com.aspose.drawing/font) مقاسًا بالوحدات المحددة بواسطة الخاصية `Font.Unit`. |
| [getSizeInPoints()](#getSizeInPoints--) | يحصل على حجم الـ em، بالنقاط، لهذه [Font](../../com.aspose.drawing/font). |
| [getUnit()](#getUnit--) | يحصل على وحدة القياس لهذه [Font](../../com.aspose.drawing/font). |
| [getHeight_Rename_Namesake()](#getHeight-Rename-Namesake--) | يحصل على تباعد الأسطر لهذا الخط. |
| [isSystemFont()](#isSystemFont--) | يحصل على قيمة تشير إلى ما إذا كان الخط عضوًا في [SystemFonts](../../com.aspose.drawing/systemfonts). |
| [getSystemFontName()](#getSystemFontName--) | يحصل على اسم الخط النظامي إذا كانت الخاصية IsSystemFont تُعيد true. |
| [getOriginalFontName()](#getOriginalFontName--) | يحصل على اسم الخط المحدد أصلاً. |
| [deepClone()](#deepClone--) | ينشئ نسخة مطابقة تمامًا من هذه [Font](../../com.aspose.drawing/font). |
| [equals(Object obj)](#equals-java.lang.Object-) | يشير إلى ما إذا كان الكائن المحدد هو [Font](../../com.aspose.drawing/font) وله نفس قيم خصائص `FontFamily`([.getFontFamily](../../null/\#getFontFamily))، `M:GdiVerticalFont`، `M:GdiCharSet`، `M:Style`، `M:Size`، و `M:Unit` كما هو [Font](../../com.aspose.drawing/font). |
| [hashCode()](#hashCode--) | يحصل على قيمة التجزئة لهذا [Font](../../com.aspose.drawing/font). |
| [getHeight()](#getHeight--) | يعيد تباعد السطر، بوحدات البكسل، لهذا الخط. |
| [getHeight(Graphics graphics)](#getHeight-com.aspose.drawing.Graphics-) | يعيد تباعد السطر، بالوحدة الحالية لكائن [Graphics](../../com.aspose.drawing/graphics) المحدد، لهذا الخط. |
| [getHeight(float dpi)](#getHeight-float-) | يعيد الارتفاع، بوحدات البكسل، لهذا [Font](../../com.aspose.drawing/font) عند رسمه على جهاز بدقة عمودية محددة. |
| [dispose()](#dispose--) | يطلق جميع الموارد المستخدمة من قبل هذا [Font](../../com.aspose.drawing/font). |
| [toString()](#toString--) | يعيد تمثيلًا نصيًا قابلًا للقراءة للإنسان لهذا [Font](../../com.aspose.drawing/font). |
| [getCharacterSet()](#getCharacterSet--) | يحصل على قيمة بايت تحدد مجموعة الأحرف التي يستخدمها هذا `Font`. |
### Font(Font prototype, int newStyle) {#Font-com.aspose.drawing.Font-int-}
```
public Font(Font prototype, int newStyle)
```


يُنشئ مثيلًا جديدًا من الفئة [Font](../../com.aspose.drawing/font) باستخدام [Font](../../com.aspose.drawing/font) الموجود المحدد وتعداد [FontStyle](../../com.aspose.drawing/fontstyle).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| prototype | [Font](../../com.aspose.drawing/font) | [Font](../../com.aspose.drawing/font) الموجود الذي يُنشأ منه [Font](../../com.aspose.drawing/font) الجديد. |
| newStyle | int | [FontStyle](../../com.aspose.drawing/fontstyle) الذي سيُطبق على [Font](../../com.aspose.drawing/font) الجديد. يمكن دمج قيم متعددة من تعداد [FontStyle](../../com.aspose.drawing/fontstyle) باستخدام عامل OR. |

### Font(FontFamily family, float emSize) {#Font-com.aspose.drawing.FontFamily-float-}
```
public Font(FontFamily family, float emSize)
```


يُهيئ نسخة جديدة من الفئة [Font](../../com.aspose.drawing/font) class.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| family | [FontFamily](../../com.aspose.drawing/fontfamily) | `FontFamily`([.getFontFamily](../../null/\#getFontFamily)) للـ [Font](../../com.aspose.drawing/font) الجديد. |
| emSize | float | حجم الـ em، بالنقاط، للخط الجديد. |

### Font(FontFamily family, float emSize, int style) {#Font-com.aspose.drawing.FontFamily-float-int-}
```
public Font(FontFamily family, float emSize, int style)
```


يُهيئ نسخة جديدة من الفئة [Font](../../com.aspose.drawing/font) باستخدام حجم ونمط محددين..

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| family | [FontFamily](../../com.aspose.drawing/fontfamily) | `FontFamily`([.getFontFamily](../../null/\#getFontFamily)) للـ [Font](../../com.aspose.drawing/font) الجديد. |
| emSize | float | حجم الـ em، بالنقاط، للخط الجديد. |
| style | int | [FontStyle](../../com.aspose.drawing/fontstyle) للخط الجديد. |

### Font(FontFamily family, float emSize, int style, int unit) {#Font-com.aspose.drawing.FontFamily-float-int-int-}
```
public Font(FontFamily family, float emSize, int style, int unit)
```


يُهيئ نسخة جديدة من الفئة [Font](../../com.aspose.drawing/font) باستخدام حجم ونمط ووحدة محددين.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| family | [FontFamily](../../com.aspose.drawing/fontfamily) | `FontFamily`([.getFontFamily](../../null/\#getFontFamily)) للـ [Font](../../com.aspose.drawing/font) الجديد. |
| emSize | float | حجم الـ em للخط الجديد بالوحدات المحددة بواسطة معامل `unit`. |
| style | int | [FontStyle](../../com.aspose.drawing/fontstyle) للخط الجديد. |
| unit | int | [GraphicsUnit](../../com.aspose.drawing/graphicsunit) للخط الجديد. |

### Font(FontFamily family, float emSize, int style, int unit, byte gdiCharSet) {#Font-com.aspose.drawing.FontFamily-float-int-int-byte-}
```
public Font(FontFamily family, float emSize, int style, int unit, byte gdiCharSet)
```


يُهيئ نسخة جديدة من الفئة [Font](../../com.aspose.drawing/font) باستخدام حجم ونمط ووحدة ومجموعة أحرف محددة..

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| family | [FontFamily](../../com.aspose.drawing/fontfamily) | `FontFamily`([.getFontFamily](../../null/\#getFontFamily)) للـ [Font](../../com.aspose.drawing/font) الجديد. |
| emSize | float | حجم الـ em للخط الجديد بالوحدات المحددة بواسطة معامل `unit`. |
| style | int | [FontStyle](../../com.aspose.drawing/fontstyle) للخط الجديد. |
| unit | int | [GraphicsUnit](../../com.aspose.drawing/graphicsunit) للخط الجديد. |
| gdiCharSet | byte | مجموعة أحرف GDI لاستخدامها مع الخط الجديد. |

### Font(FontFamily family, float emSize, int style, int unit, byte gdiCharSet, boolean gdiVerticalFont) {#Font-com.aspose.drawing.FontFamily-float-int-int-byte-boolean-}
```
public Font(FontFamily family, float emSize, int style, int unit, byte gdiCharSet, boolean gdiVerticalFont)
```


يُهيئ نسخة جديدة من الفئة [Font](../../com.aspose.drawing/font) باستخدام حجم ونمط ووحدة ومجموعة أحرف محددة..

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| family | [FontFamily](../../com.aspose.drawing/fontfamily) | `FontFamily`([.getFontFamily](../../null/\#getFontFamily)) للـ [Font](../../com.aspose.drawing/font) الجديد. |
| emSize | float | حجم الـ em للخط الجديد بالوحدات المحددة بواسطة معامل `unit`. |
| style | int | [FontStyle](../../com.aspose.drawing/fontstyle) للخط الجديد. |
| unit | int | [GraphicsUnit](../../com.aspose.drawing/graphicsunit) للخط الجديد. |
| gdiCharSet | byte | مجموعة أحرف GDI لاستخدامها مع الخط الجديد. |
| gdiVerticalFont | boolean | قيمة منطقية تشير إلى ما إذا كان الخط الجديد مشتقًا من خط عمودي GDI. |

### Font(String familyName, float emSize) {#Font-java.lang.String-float-}
```
public Font(String familyName, float emSize)
```


يُهيئ نسخة جديدة من الفئة [Font](../../com.aspose.drawing/font) باستخدام حجم محدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| familyName | java.lang.String | تمثيل نصي لسلسلة FontFamily للـ [Font](../../com.aspose.drawing/font) الجديد. |
| emSize | float | حجم الـ em، بالنقاط، للخط الجديد. |

### Font(String familyName, float emSize, int style) {#Font-java.lang.String-float-int-}
```
public Font(String familyName, float emSize, int style)
```


يُهيئ نسخة جديدة من الفئة [Font](../../com.aspose.drawing/font) باستخدام حجم ونمط محددين.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| familyName | java.lang.String | تمثيل نصي لسلسلة FontFamily للـ [Font](../../com.aspose.drawing/font) الجديد. |
| emSize | float | حجم الـ em، بالنقاط، للخط الجديد. |
| style | int | [FontStyle](../../com.aspose.drawing/fontstyle) للخط الجديد. |

### Font(String familyName, float emSize, int style, int unit) {#Font-java.lang.String-float-int-int-}
```
public Font(String familyName, float emSize, int style, int unit)
```


يُهيئ نسخة جديدة من الفئة [Font](../../com.aspose.drawing/font) باستخدام حجم ونمط ووحدة محددين.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| familyName | java.lang.String | تمثيل نصي لـ `FontFamily`([.getFontFamily](../../null/\#getFontFamily)) للـ [Font](../../com.aspose.drawing/font) الجديد. |
| emSize | float | حجم الـ em للخط الجديد بالوحدات المحددة بواسطة معامل `unit`. |
| style | int | [FontStyle](../../com.aspose.drawing/fontstyle) للخط الجديد. |
| unit | int | [GraphicsUnit](../../com.aspose.drawing/graphicsunit) للخط الجديد. |

### Font(String familyName, float emSize, int style, int unit, byte gdiCharSet) {#Font-java.lang.String-float-int-int-byte-}
```
public Font(String familyName, float emSize, int style, int unit, byte gdiCharSet)
```


يُهيئ نسخة جديدة من الفئة [Font](../../com.aspose.drawing/font) باستخدام حجم ونمط ووحدة ومجموعة أحرف محددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| familyName | java.lang.String | تمثيل نصي لسلسلة FontFamily للـ [Font](../../com.aspose.drawing/font) الجديد. |
| emSize | float | حجم الـ em للخط الجديد بالوحدات المحددة بواسطة معامل `unit`. |
| style | int | [FontStyle](../../com.aspose.drawing/fontstyle) للخط الجديد. |
| unit | int | [GraphicsUnit](../../com.aspose.drawing/graphicsunit) للخط الجديد. |
| gdiCharSet | byte | بايت يحدد مجموعة أحرف GDI لاستخدامها مع هذا الخط. |

### Font(String familyName, float emSize, int style, int unit, byte gdiCharSet, boolean gdiVerticalFont) {#Font-java.lang.String-float-int-int-byte-boolean-}
```
public Font(String familyName, float emSize, int style, int unit, byte gdiCharSet, boolean gdiVerticalFont)
```


يُهيئ نسخة جديدة من الفئة [Font](../../com.aspose.drawing/font) باستخدام الحجم والنمط والوحدة ومجموعة الأحرف المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| familyName | java.lang.String | تمثيل نصي لسلسلة FontFamily للـ [Font](../../com.aspose.drawing/font) الجديد. |
| emSize | float | حجم الـ em للخط الجديد بالوحدات المحددة بواسطة معامل `unit`. |
| style | int | [FontStyle](../../com.aspose.drawing/fontstyle) للخط الجديد. |
| unit | int | [GraphicsUnit](../../com.aspose.drawing/graphicsunit) للخط الجديد. |
| gdiCharSet | byte | بايت يحدد مجموعة أحرف GDI لاستخدامها مع هذا الخط. |
| gdiVerticalFont | boolean | قيمة منطقية تشير إلى ما إذا كان الـ [Font](../../com.aspose.drawing/font) الجديد مشتقًا من خط عمودي GDI. |

### getFontFamily() {#getFontFamily--}
```
public FontFamily getFontFamily()
```


يحصل على `FontFamily`([.getFontFamily](../../null/\#getFontFamily)) المرتبط بهذه [Font](../../com.aspose.drawing/font).

**Returns:**
[FontFamily](../../com.aspose.drawing/fontfamily) - The `FontFamily`([.getFontFamily](../../null/\#getFontFamily)) associated with this [Font](../../com.aspose.drawing/font).
### getBold() {#getBold--}
```
public boolean getBold()
```


يحصل على قيمة تشير إلى ما إذا كانت هذه [Font](../../com.aspose.drawing/font) عريضة.

**Returns:**
boolean - قيمة تشير إلى ما إذا كان هذا [Font](../../com.aspose.drawing/font) غامقًا.
### getGdiCharSet() {#getGdiCharSet--}
```
public byte getGdiCharSet()
```


يحصل على قيمة بايت تحدد مجموعة أحرف GDI التي تستخدمها هذه [Font](../../com.aspose.drawing/font).

**Returns:**
byte - قيمة بايت تحدد مجموعة أحرف GDI التي يستخدمها هذا [Font](../../com.aspose.drawing/font).
### getGdiVerticalFont() {#getGdiVerticalFont--}
```
public boolean getGdiVerticalFont()
```


يحصل على قيمة تشير إلى ما إذا كانت هذه [Font](../../com.aspose.drawing/font) مستمدة من خط عمودي GDI..

القيمة: `true` إذا كان هذا [Font](../../com.aspose.drawing/font) مشتقًا من خط عمودي GDI؛ وإلا `false`.

**Returns:**
boolean - قيمة تشير إلى ما إذا كان هذا [Font](../../com.aspose.drawing/font) مشتقًا من خط عمودي GDI.
### getItalic() {#getItalic--}
```
public boolean getItalic()
```


يحصل على قيمة تشير إلى ما إذا كانت هذه [Font](../../com.aspose.drawing/font) مائلة.

**Returns:**
boolean - قيمة تشير إلى ما إذا كان هذا [Font](../../com.aspose.drawing/font) مائلًا.
### getName() {#getName--}
```
public String getName()
```


يحصل على اسم الوجه لهذه [Font](../../com.aspose.drawing/font).

**Returns:**
java.lang.String - اسم الوجه لهذا [Font](../../com.aspose.drawing/font).
### getStrikeout() {#getStrikeout--}
```
public boolean getStrikeout()
```


يحصل على قيمة تشير إلى ما إذا كانت هذه [Font](../../com.aspose.drawing/font) تحدد خطًا أفقيًا عبر الخط.

**Returns:**
boolean - قيمة تشير إلى ما إذا كان هذا [Font](../../com.aspose.drawing/font) يحدد خطًا أفقيًا عبر الخط.
### getUnderline() {#getUnderline--}
```
public boolean getUnderline()
```


يحصل على قيمة تشير إلى ما إذا كانت هذه [Font](../../com.aspose.drawing/font) مسطّرة.

**Returns:**
boolean - قيمة تشير إلى ما إذا كان هذا [Font](../../com.aspose.drawing/font) تحته خط.
### getStyle() {#getStyle--}
```
public int getStyle()
```


يحصل على معلومات النمط لهذه [Font](../../com.aspose.drawing/font).

**Returns:**
int - معلومات النمط لهذا [Font](../../com.aspose.drawing/font).
### getSize() {#getSize--}
```
public float getSize()
```


يحصل على حجم الـ em لهذه [Font](../../com.aspose.drawing/font) مقاسًا بالوحدات المحددة بواسطة الخاصية `Font.Unit`.

**Returns:**
float - حجم الـ em لهذا [Font](../../com.aspose.drawing/font) مقاسًا بالوحدات المحددة بواسطة \{@code Font.
### getSizeInPoints() {#getSizeInPoints--}
```
public float getSizeInPoints()
```


يحصل على حجم الـ em، بالنقاط، لهذه [Font](../../com.aspose.drawing/font).

**Returns:**
float - حجم الـ em، بالنقاط، لهذا [Font](../../com.aspose.drawing/font).
### getUnit() {#getUnit--}
```
public int getUnit()
```


يحصل على وحدة القياس لهذه [Font](../../com.aspose.drawing/font).

**Returns:**
int - وحدة القياس لهذا [Font](../../com.aspose.drawing/font).
### getHeight_Rename_Namesake() {#getHeight-Rename-Namesake--}
```
public int getHeight_Rename_Namesake()
```


يحصل على تباعد الأسطر لهذا الخط.

القيمة: تباعد السطر، بالبكسل، لهذا الخط.

**Returns:**
int - تباعد السطر لهذا الخط.
### isSystemFont() {#isSystemFont--}
```
public boolean isSystemFont()
```


يحصل على قيمة تشير إلى ما إذا كان الخط عضوًا في [SystemFonts](../../com.aspose.drawing/systemfonts).

القيمة: `true` إذا كان الخط عضوًا في [SystemFonts](../../com.aspose.drawing/systemfonts)؛ وإلا `false`.

**Returns:**
boolean - قيمة تشير إلى ما إذا كان الخط عضوًا في [SystemFonts](../../com.aspose.drawing/systemfonts).
### getSystemFontName() {#getSystemFontName--}
```
public String getSystemFontName()
```


يحصل على اسم الخط النظامي إذا كانت الخاصية IsSystemFont تُعيد true.

القيمة: اسم الخط النظامي إذا أعادت الخاصية IsSystemFont القيمة true؛ وإلا سلسلة فارغة ("").

**Returns:**
java.lang.String - اسم الخط النظامي إذا أعادت الخاصية IsSystemFont القيمة true.
### getOriginalFontName() {#getOriginalFontName--}
```
public String getOriginalFontName()
```


يحصل على اسم الخط المحدد أصلاً.

القيمة: السلسلة التي تمثل اسم الخط المحدد أصلاً.

**Returns:**
java.lang.String - اسم الخط المحدد أصلاً.
### deepClone() {#deepClone--}
```
public Font deepClone()
```


ينشئ نسخة مطابقة تمامًا من هذه [Font](../../com.aspose.drawing/font).

**Returns:**
[Font](../../com.aspose.drawing/font) - The [Font](../../com.aspose.drawing/font) this method creates, cast as an Object.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


يشير إلى ما إذا كان الكائن المحدد هو [Font](../../com.aspose.drawing/font) وله نفس قيم خصائص `FontFamily`([.getFontFamily](../../null/\#getFontFamily))، `M:GdiVerticalFont`، `M:GdiCharSet`، `M:Style`، `M:Size`، و `M:Unit` كما هو [Font](../../com.aspose.drawing/font).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| obj | java.lang.Object | الكائن المراد اختباره. |

**Returns:**
boolean - `true` إذا كان معامل obj هو [Font](../../com.aspose.drawing/font) وله نفس قيم الخصائص `FontFamily`([.getFontFamily](../../null/\#getFontFamily))، `M:GdiVerticalFont`، `M:GdiCharSet`، `M:Style`، `M:Size`، و `M:Unit` كما في هذا [Font](../../com.aspose.drawing/font)؛ وإلا `false`.
### hashCode() {#hashCode--}
```
public int hashCode()
```


يحصل على قيمة التجزئة لهذا [Font](../../com.aspose.drawing/font).

**Returns:**
int - رمز التجزئة لهذا [Font](../../com.aspose.drawing/font).
### getHeight() {#getHeight--}
```
public int getHeight()
```


يعيد تباعد السطر، بوحدات البكسل، لهذا الخط.

**Returns:**
int - تباعد السطر، بالبكسل، لهذا الخط.
### getHeight(Graphics graphics) {#getHeight-com.aspose.drawing.Graphics-}
```
public float getHeight(Graphics graphics)
```


يعيد تباعد السطر، بالوحدة الحالية لكائن [Graphics](../../com.aspose.drawing/graphics) المحدد، لهذا الخط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| graphics | [Graphics](../../com.aspose.drawing/graphics) | [Graphics](../../com.aspose.drawing/graphics) التي تحتفظ بالدقة العمودية، بالنقطة في البوصة، لجهاز العرض بالإضافة إلى إعدادات وحدة الصفحة ومقياس الصفحة. |

**Returns:**
float - تباعد السطر، بالبكسل، لهذا الخط.
### getHeight(float dpi) {#getHeight-float-}
```
public int getHeight(float dpi)
```


يعيد الارتفاع، بوحدات البكسل، لهذا [Font](../../com.aspose.drawing/font) عند رسمه على جهاز بدقة عمودية محددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| dpi | float | الدقة العمودية، بوحدة النقاط في البوصة، المستخدمة لحساب ارتفاع الخط. |

**Returns:**
int - الارتفاع، بوحدة البكسل، لهذا [Font](../../com.aspose.drawing/font).
### dispose() {#dispose--}
```
public void dispose()
```


يطلق جميع الموارد المستخدمة من قبل هذا [Font](../../com.aspose.drawing/font).

### toString() {#toString--}
```
public String toString()
```


يعيد تمثيلًا نصيًا قابلًا للقراءة للإنسان لهذا [Font](../../com.aspose.drawing/font).

**Returns:**
java.lang.String - سلسلة تمثل هذا [Font](../../com.aspose.drawing/font).
### getCharacterSet() {#getCharacterSet--}
```
public int getCharacterSet()
```


يحصل على قيمة بايت تحدد مجموعة الأحرف التي يستخدمها هذا `Font`.

**Returns:**
int - مجموعة الأحرف التي يستخدمها هذا `Font`.
