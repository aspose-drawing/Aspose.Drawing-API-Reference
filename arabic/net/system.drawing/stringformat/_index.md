---
title: StringFormat
second_title: Aspose.Drawing لمرجع NET API
description: يحتوي على معلومات تخطيط النص مثل المحاذاة والاتجاه وعلامات الجدولة معالجة العرض مثل إدراج القطع واستبدال الأرقام الوطنية وميزات OpenType. لا يمكن توريث هذه الفئة.
type: docs
weight: 1130
url: /ar/net/system.drawing/stringformat/
---
## StringFormat class

يحتوي على معلومات تخطيط النص (مثل المحاذاة والاتجاه وعلامات الجدولة) معالجة العرض (مثل إدراج القطع واستبدال الأرقام الوطنية) وميزات OpenType. لا يمكن توريث هذه الفئة.

```csharp
public sealed class StringFormat : IDisposable
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [StringFormat](stringformat#constructor)() | يقوم بتهيئة مثيل جديد لملف[`StringFormat`](../stringformat) فئة . |
| [StringFormat](stringformat#constructor_1)(StringFormat) | يقوم بتهيئة مثيل جديد لملف[`StringFormat`](../stringformat) class من القائمة المحددةStringFormat الكائن . |
| [StringFormat](stringformat#constructor_2)(StringFormatFlags) | يقوم بتهيئة مثيل جديد لملف[`StringFormat`](../stringformat)فئة مع المحدد StringFormatFlags التعداد . |
| [StringFormat](stringformat#constructor_3)(StringFormatFlags, int) | يقوم بتهيئة مثيل جديد لملف[`StringFormat`](../stringformat) فئة مع المحدد[`StringFormatFlags`](../stringformatflags) التعداد واللغة. |

## الخصائص

| اسم | وصف |
| --- | --- |
| static [GenericDefault](../../system.drawing/stringformat/genericdefault) { get; } | يحصل على افتراضي عامStringFormat الكائن . |
| static [GenericTypographic](../../system.drawing/stringformat/generictypographic) { get; } | يحصل على طباعة عامةStringFormat الكائن . |
| [Alignment](../../system.drawing/stringformat/alignment) { get; set; } | الحصول على معلومات محاذاة النص على المستوى العمودي أو تعيينها. |
| [DigitSubstitutionLanguage](../../system.drawing/stringformat/digitsubstitutionlanguage) { get; } | الحصول على اللغة المستخدمة عند استبدال الأرقام المحلية بالأرقام الغربية. |
| [DigitSubstitutionMethod](../../system.drawing/stringformat/digitsubstitutionmethod) { get; } | يحصل على الطريقة التي سيتم استخدامها لاستبدال الأرقام. |
| [FormatFlags](../../system.drawing/stringformat/formatflags) { get; set; } | يحصل أو يحدد أStringFormatFlags التعداد الذي يحتوي على معلومات التنسيق. |
| [HotkeyPrefix](../../system.drawing/stringformat/hotkeyprefix) { get; set; } | يحصل أو يحدد ملفHotkeyPrefix كائن لهذاStringFormat الكائن . |
| [LineAlignment](../../system.drawing/stringformat/linealignment) { get; set; } | الحصول على محاذاة الخط على المستوى الأفقي أو تعيينها. |
| [Trimming](../../system.drawing/stringformat/trimming) { get; set; } | يحصل أو يحدد ملفStringTrimming تعداد لهذاStringFormat الكائن . |

## طُرق

| اسم | وصف |
| --- | --- |
| [Clone](../../system.drawing/stringformat/clone)() | ينشئ نسخة طبق الأصل من هذا[`StringFormat`](../stringformat) هدف. |
| [Dispose](../../system.drawing/stringformat/dispose)() | يقوم بإصدار كافة الموارد التي يستخدمها هذاStringFormat الكائن . |
| [GetTabStops](../../system.drawing/stringformat/gettabstops)(out float) | يحصل على علامات الجدولة لهذا الغرضStringFormat الكائن . |
| [SetDigitSubstitution](../../system.drawing/stringformat/setdigitsubstitution)(int, StringDigitSubstitute) | يحدد اللغة والطريقة المراد استخدامهما عند استبدال الأرقام المحلية بالأرقام الغربية. |
| [SetMeasurableCharacterRanges](../../system.drawing/stringformat/setmeasurablecharacterranges)(CharacterRange[]) | تحدد مصفوفة منCharacterRange الهياكل التي تمثل نطاقات الأحرف المقاسة بواسطة استدعاء لـMeasureCharacterRanges طريقة . |
| [SetTabStops](../../system.drawing/stringformat/settabstops)(float, float[]) | تعيين علامات الجدولة لهذا الغرضStringFormat الكائن . |

### أنظر أيضا

* مساحة الاسم [System.Drawing](../../system.drawing)
* المجسم [Aspose.Drawing](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Drawing.dll -->
