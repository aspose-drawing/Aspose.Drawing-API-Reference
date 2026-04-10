---
title: StringFormat
second_title: مرجع API لـ Aspose.Drawing للـ Java
description: يحتوي على معلومات تنسيق النص مثل اتجاه المحاذاة وإيقافات التبويب وتعديلات العرض مثل إدراج الثلاث نقاط واستبدال الأرقام الوطنية وميزات OpenType.
type: docs
weight: 47
url: /ar/java/com.aspose.drawing/stringformat/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public final class StringFormat implements System.IDisposable
```

يغلف معلومات تخطيط النص (مثل المحاذاة، الاتجاه وإيقافات الجدولة) وتعديلات العرض (مثل إدراج الحذف الثلاثي واستبدال الأرقام الوطنية) وميزات OpenType. لا يمكن وراثة هذه الفئة.
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [StringFormat()](#StringFormat--) | ينشئ مثيلاً جديدًا للفئة [StringFormat](../../com.aspose.drawing/stringformat). |
| [StringFormat(StringFormat format)](#StringFormat-com.aspose.drawing.StringFormat-) | ينشئ مثيلاً جديدًا للفئة [StringFormat](../../com.aspose.drawing/stringformat) من كائن [StringFormat](../../com.aspose.drawing/stringformat) الموجود المحدد. |
| [StringFormat(int options, int language)](#StringFormat-int-int-) | ينشئ مثيلاً جديدًا للفئة [StringFormat](../../com.aspose.drawing/stringformat) باستخدام تعداد [StringFormatFlags](../../com.aspose.drawing/stringformatflags) المحدد واللغة. |
| [StringFormat(int options)](#StringFormat-int-) | ينشئ مثيلاً جديدًا للفئة [StringFormat](../../com.aspose.drawing/stringformat) باستخدام تعداد [StringFormatFlags](../../com.aspose.drawing/stringformatflags) المحدد. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [setDigitSubstitutionLanguage(int value)](#setDigitSubstitutionLanguage-int-) |  |
| [setDigitSubstitutionMethod(int value)](#setDigitSubstitutionMethod-int-) |  |
| [getFirstTabOffset()](#getFirstTabOffset--) |  |
| [getGenericDefault()](#getGenericDefault--) | يحصل على كائن [StringFormat](../../com.aspose.drawing/stringformat) افتراضي عام. |
| [getGenericTypographic()](#getGenericTypographic--) | يحصل على كائن [StringFormat](../../com.aspose.drawing/stringformat) طباعي عام. |
| [getFormatFlags()](#getFormatFlags--) | يحصل أو يعيّن تعداد [StringFormatFlags](../../com.aspose.drawing/stringformatflags) الذي يحتوي على معلومات التنسيق. |
| [setFormatFlags(int value)](#setFormatFlags-int-) | يحصل أو يعيّن تعداد [StringFormatFlags](../../com.aspose.drawing/stringformatflags) الذي يحتوي على معلومات التنسيق. |
| [getAlignment()](#getAlignment--) | يحصل أو يعيّن معلومات محاذاة النص على المستوى العمودي. |
| [setAlignment(int value)](#setAlignment-int-) | يحصل أو يعيّن معلومات محاذاة النص على المستوى العمودي. |
| [getLineAlignment()](#getLineAlignment--) | يحصل أو يعيّن محاذاة السطر على المستوى الأفقي. |
| [setLineAlignment(int value)](#setLineAlignment-int-) | يحصل أو يعيّن محاذاة السطر على المستوى الأفقي. |
| [getHotkeyPrefix()](#getHotkeyPrefix--) | يحصل أو يعيّن كائن `HotkeyPrefix`([.getHotkeyPrefix](../../null/\#getHotkeyPrefix)/[.setHotkeyPrefix(int)](../../null/\#setHotkeyPrefix-int-)) لهذا الكائن [StringFormat](../../com.aspose.drawing/stringformat). |
| [setHotkeyPrefix(int value)](#setHotkeyPrefix-int-) | يحصل أو يعيّن كائن `HotkeyPrefix`([.getHotkeyPrefix](../../null/\#getHotkeyPrefix)/[.setHotkeyPrefix(int)](../../null/\#setHotkeyPrefix-int-)) لهذا الكائن [StringFormat](../../com.aspose.drawing/stringformat). |
| [getTrimming()](#getTrimming--) | يحصل أو يعيّن تعداد [StringTrimming](../../com.aspose.drawing/stringtrimming) لهذا الكائن [StringFormat](../../com.aspose.drawing/stringformat). |
| [setTrimming(int value)](#setTrimming-int-) | يحصل أو يعيّن تعداد [StringTrimming](../../com.aspose.drawing/stringtrimming) لهذا الكائن [StringFormat](../../com.aspose.drawing/stringformat). |
| [getDigitSubstitutionLanguage()](#getDigitSubstitutionLanguage--) | يحصل على اللغة المستخدمة عندما يتم استبدال الأرقام المحلية بالأرقام الغربية. |
| [getDigitSubstitutionMethod()](#getDigitSubstitutionMethod--) | يحصل على الطريقة المستخدمة لاستبدال الأرقام. |
| [dispose()](#dispose--) | يطلق جميع الموارد المستخدمة بواسطة هذا الكائن [StringFormat](../../com.aspose.drawing/stringformat). |
| [deepClone()](#deepClone--) | ينشئ نسخة مطابقة تمامًا من هذا الكائن [StringFormat](../../com.aspose.drawing/stringformat). |
| [getTabStops(float[] firstTabOffset)](#getTabStops-float---) | يحصل على إيقافات الجدولة لهذا الكائن [StringFormat](../../com.aspose.drawing/stringformat). |
| [getTabStops()](#getTabStops--) | يحصل على مصفوفة من المسافات بين إيقافات الجدولة بالوحدات المحددة بواسطة الخاصية `Aspose.Imaging.getGraphics().PageUnit`. |
| [setTabStops(float firstTabOffset, float[] tabStops)](#setTabStops-float-float---) | يعيّن إيقافات الجدولة لهذا الكائن [StringFormat](../../com.aspose.drawing/stringformat). |
| [setDigitSubstitution(int language, int substitute)](#setDigitSubstitution-int-int-) | يحدد اللغة والطريقة المستخدمة عندما يتم استبدال الأرقام المحلية بالأرقام الغربية. |
| [setMeasurableCharacterRanges(CharacterRange[] ranges)](#setMeasurableCharacterRanges-com.aspose.drawing.CharacterRange---) | يحدد مصفوفة من هياكل [CharacterRange](../../com.aspose.drawing/characterrange) التي تمثل نطاقات الأحرف التي يتم قياسها عبر استدعاء طريقة `MeasureCharacterRanges`. |
### StringFormat() {#StringFormat--}
```
public StringFormat()
```


ينشئ مثيلاً جديدًا للفئة [StringFormat](../../com.aspose.drawing/stringformat).

### StringFormat(StringFormat format) {#StringFormat-com.aspose.drawing.StringFormat-}
```
public StringFormat(StringFormat format)
```


ينشئ مثيلاً جديدًا للفئة [StringFormat](../../com.aspose.drawing/stringformat) من كائن [StringFormat](../../com.aspose.drawing/stringformat) الموجود المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| format | [StringFormat](../../com.aspose.drawing/stringformat) | الكائن [StringFormat](../../com.aspose.drawing/stringformat) الذي يُستخدم لتهيئة الكائن الجديد [StringFormat](../../com.aspose.drawing/stringformat). |

### StringFormat(int options, int language) {#StringFormat-int-int-}
```
public StringFormat(int options, int language)
```


ينشئ مثيلاً جديدًا للفئة [StringFormat](../../com.aspose.drawing/stringformat) باستخدام تعداد [StringFormatFlags](../../com.aspose.drawing/stringformatflags) المحدد واللغة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| options | int | تعداد [StringFormatFlags](../../com.aspose.drawing/stringformatflags) للكائن الجديد [StringFormat](../../com.aspose.drawing/stringformat). |
| اللغة | int | قيمة تشير إلى لغة النص. |

### StringFormat(int options) {#StringFormat-int-}
```
public StringFormat(int options)
```


ينشئ مثيلاً جديدًا للفئة [StringFormat](../../com.aspose.drawing/stringformat) باستخدام تعداد [StringFormatFlags](../../com.aspose.drawing/stringformatflags) المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| options | int | تعداد [StringFormatFlags](../../com.aspose.drawing/stringformatflags) للكائن الجديد [StringFormat](../../com.aspose.drawing/stringformat). |

### setDigitSubstitutionLanguage(int value) {#setDigitSubstitutionLanguage-int-}
```
public void setDigitSubstitutionLanguage(int value)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### setDigitSubstitutionMethod(int value) {#setDigitSubstitutionMethod-int-}
```
public void setDigitSubstitutionMethod(int value)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getFirstTabOffset() {#getFirstTabOffset--}
```
public float getFirstTabOffset()
```




**Returns:**
float
### getGenericDefault() {#getGenericDefault--}
```
public static StringFormat getGenericDefault()
```


يحصل على كائن [StringFormat](../../com.aspose.drawing/stringformat) افتراضي عام.

**Returns:**
[StringFormat](../../com.aspose.drawing/stringformat)
### getGenericTypographic() {#getGenericTypographic--}
```
public static StringFormat getGenericTypographic()
```


يحصل على كائن [StringFormat](../../com.aspose.drawing/stringformat) طباعي عام.

**Returns:**
[StringFormat](../../com.aspose.drawing/stringformat) - A generic typographic [StringFormat](../../com.aspose.drawing/stringformat) object.
### getFormatFlags() {#getFormatFlags--}
```
public int getFormatFlags()
```


يحصل أو يعيّن تعداد [StringFormatFlags](../../com.aspose.drawing/stringformatflags) الذي يحتوي على معلومات التنسيق.

**Returns:**
int
### setFormatFlags(int value) {#setFormatFlags-int-}
```
public void setFormatFlags(int value)
```


يحصل أو يعيّن تعداد [StringFormatFlags](../../com.aspose.drawing/stringformatflags) الذي يحتوي على معلومات التنسيق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getAlignment() {#getAlignment--}
```
public int getAlignment()
```


يحصل أو يعيّن معلومات محاذاة النص على المستوى العمودي.

**Returns:**
int
### setAlignment(int value) {#setAlignment-int-}
```
public void setAlignment(int value)
```


يحصل أو يعيّن معلومات محاذاة النص على المستوى العمودي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getLineAlignment() {#getLineAlignment--}
```
public int getLineAlignment()
```


يحصل أو يعيّن محاذاة السطر على المستوى الأفقي.

**Returns:**
int
### setLineAlignment(int value) {#setLineAlignment-int-}
```
public void setLineAlignment(int value)
```


يحصل أو يعيّن محاذاة السطر على المستوى الأفقي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getHotkeyPrefix() {#getHotkeyPrefix--}
```
public int getHotkeyPrefix()
```


يحصل أو يعيّن كائن `HotkeyPrefix`([.getHotkeyPrefix](../../null/\#getHotkeyPrefix)/[.setHotkeyPrefix(int)](../../null/\#setHotkeyPrefix-int-)) لهذا الكائن [StringFormat](../../com.aspose.drawing/stringformat).

**Returns:**
int
### setHotkeyPrefix(int value) {#setHotkeyPrefix-int-}
```
public void setHotkeyPrefix(int value)
```


يحصل أو يعيّن كائن `HotkeyPrefix`([.getHotkeyPrefix](../../null/\#getHotkeyPrefix)/[.setHotkeyPrefix(int)](../../null/\#setHotkeyPrefix-int-)) لهذا الكائن [StringFormat](../../com.aspose.drawing/stringformat).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getTrimming() {#getTrimming--}
```
public int getTrimming()
```


يحصل أو يعيّن تعداد [StringTrimming](../../com.aspose.drawing/stringtrimming) لهذا الكائن [StringFormat](../../com.aspose.drawing/stringformat).

**Returns:**
int
### setTrimming(int value) {#setTrimming-int-}
```
public void setTrimming(int value)
```


يحصل أو يعيّن تعداد [StringTrimming](../../com.aspose.drawing/stringtrimming) لهذا الكائن [StringFormat](../../com.aspose.drawing/stringformat).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getDigitSubstitutionLanguage() {#getDigitSubstitutionLanguage--}
```
public int getDigitSubstitutionLanguage()
```


يحصل على اللغة المستخدمة عندما يتم استبدال الأرقام المحلية بالأرقام الغربية.

**Returns:**
int - معرف لغة دعم اللغة الوطنية (NLS) الذي يحدد اللغة التي ستُستخدم عندما يتم استبدال الأرقام المحلية بالأرقام الغربية. يمكنك تمرير خاصية `System.Globalization.CultureInfo.LCID` لكائن java.util.Locale كمعرف لغة NLS. على سبيل المثال، افترض أنك أنشأت كائن java.util.Locale بتمرير السلسلة "ar-EG" إلى مُنشئ java.util.Locale. إذا مررت خاصية `System.Globalization.CultureInfo.LCID` لهذا الكائن جنبًا إلى جنب مع `StringDigitSubstitute.Traditional` إلى طريقة [.setDigitSubstitution(int,int)](../../null/\\#setDigitSubstitution-int-int-)، فسيتم استبدال الأرقام العربية-الهندية بالأرقام الغربية عند العرض.
### getDigitSubstitutionMethod() {#getDigitSubstitutionMethod--}
```
public int getDigitSubstitutionMethod()
```


يحصل على الطريقة المستخدمة لاستبدال الأرقام.

**Returns:**
int - قيمة تعداد [StringDigitSubstitute](../../com.aspose.drawing/stringdigitsubstitute) التي تحدد كيفية استبدال الأحرف في سلسلة لا يمكن عرضها لأنها غير مدعومة من الخط الحالي.
### dispose() {#dispose--}
```
public void dispose()
```


يطلق جميع الموارد المستخدمة بواسطة هذا الكائن [StringFormat](../../com.aspose.drawing/stringformat).

### deepClone() {#deepClone--}
```
public StringFormat deepClone()
```


ينشئ نسخة مطابقة تمامًا من هذا الكائن [StringFormat](../../com.aspose.drawing/stringformat).

**Returns:**
[StringFormat](../../com.aspose.drawing/stringformat) - The [StringFormat](../../com.aspose.drawing/stringformat) object this method creates.
### getTabStops(float[] firstTabOffset) {#getTabStops-float---}
```
public float[] getTabStops(float[] firstTabOffset)
```


يحصل على إيقافات الجدولة لهذا الكائن [StringFormat](../../com.aspose.drawing/stringformat).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| firstTabOffset | float[] | عدد المسافات بين بداية سطر النص وأول موضع تبويب. |

**Returns:**
float[] - مصفوفة من المسافات (بعدد المسافات) بين مواضع التبويب.
### getTabStops() {#getTabStops--}
```
public float[] getTabStops()
```


يحصل على مصفوفة من المسافات بين إيقافات الجدولة بالوحدات المحددة بواسطة الخاصية `Aspose.Imaging.getGraphics().PageUnit`.

**Returns:**
float[] - مواضع التبويب.

تم تقديم الخاصية للطريقة التي تم إزالتها GetTabStops.
### setTabStops(float firstTabOffset, float[] tabStops) {#setTabStops-float-float---}
```
public void setTabStops(float firstTabOffset, float[] tabStops)
```


يعيّن إيقافات الجدولة لهذا الكائن [StringFormat](../../com.aspose.drawing/stringformat).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| firstTabOffset | float | عدد المسافات بين بداية سطر النص وأول موضع تبويب. |
| tabStops | float[] | مصفوفة من المسافات بين مواضع التبويب بالوحدات المحددة بواسطة الخاصية Graphics.PageUnit. |

### setDigitSubstitution(int language, int substitute) {#setDigitSubstitution-int-int-}
```
public void setDigitSubstitution(int language, int substitute)
```


يحدد اللغة والطريقة المستخدمة عندما يتم استبدال الأرقام المحلية بالأرقام الغربية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| اللغة | int | معرف لغة دعم اللغة الوطنية (NLS) الذي يحدد اللغة التي ستُستخدم عندما يتم استبدال الأرقام المحلية بالأرقام الغربية. يمكنك تمرير خاصية `System.Globalization.CultureInfo.LCID` لكائن java.util.Locale كمعرف لغة NLS. على سبيل المثال، افترض أنك أنشأت كائن java.util.Locale بتمرير السلسلة `\"ar-EG\"` إلى مُنشئ java.util.Locale. إذا مررت خاصية `System.Globalization.CultureInfo.LCID` لهذا الكائن جنبًا إلى جنب مع `StringDigitSubstitute.Traditional` إلى طريقة `M:StringFormat.SetDigitSubstitution(System.Int32,StringDigitSubstitute)`، فسيتم استبدال الأرقام العربية-الهندية بالأرقام الغربية عند العرض. |
| substitute | int | عنصر من تعداد [StringDigitSubstitute](../../com.aspose.drawing/stringdigitsubstitute) يحدد كيفية عرض الأرقام. |

### setMeasurableCharacterRanges(CharacterRange[] ranges) {#setMeasurableCharacterRanges-com.aspose.drawing.CharacterRange---}
```
public void setMeasurableCharacterRanges(CharacterRange[] ranges)
```


يحدد مصفوفة من هياكل [CharacterRange](../../com.aspose.drawing/characterrange) التي تمثل نطاقات الأحرف التي يتم قياسها عبر استدعاء طريقة `MeasureCharacterRanges`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| ranges | [CharacterRange\[\]](../../com.aspose.drawing/characterrange) | مصفوفة من هياكل [CharacterRange](../../com.aspose.drawing/characterrange) التي تحدد نطاقات الأحرف التي يتم قياسها بواسطة استدعاء طريقة `MeasureCharacterRanges`. |

