---
title: Size
second_title: Aspose.Drawing لمرجع NET API
description: يخزن زوجًا مرتبًا من الأعداد الصحيحة  عادةً ما يكون عرض المستطيل وارتفاعه.
type: docs
weight: 1080
url: /ar/net/system.drawing/size/
---
## Size structure

يخزن زوجًا مرتبًا من الأعداد الصحيحة ، عادةً ما يكون عرض المستطيل وارتفاعه.

```csharp
public struct Size : IEquatable<Size>
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [Size](size#constructor_1)(Point) | يقوم بتهيئة مثيل جديد لملف[`Size`](../size) هيكل من المحددPoint . |
| [Size](size#constructor)(int, int) | يقوم بتهيئة مثيل جديد لملف[`Size`](../size) هيكل من الأبعاد المحددة. |

## الخصائص

| اسم | وصف |
| --- | --- |
| [Height](../../system.drawing/size/height) { get; set; } | الحصول على أو تحديد المكون الرأسي لهذاSize . |
| [IsEmpty](../../system.drawing/size/isempty) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذاSize يبلغ عرضه وارتفاعه 0. |
| [Width](../../system.drawing/size/width) { get; set; } | الحصول على أو تحديد المكون الأفقي لهذاSize . |

## طُرق

| اسم | وصف |
| --- | --- |
| static [Add](../../system.drawing/size/add)(Size, Size) | إضافة عرض وارتفاع واحدSize هيكل للعرض والارتفاع آخرSize هيكل . |
| static [Ceiling](../../system.drawing/size/ceiling)(SizeF) | تحويل المحددSizeF هيكل لSize هيكل عن طريق تقريب القيم منSize بنية لقيم الأعداد الصحيحة الأعلى التالية. |
| static [Round](../../system.drawing/size/round)(SizeF) | تحويل المحددSizeF هيكل لSize هيكل بتقريب قيمSizeF بنية لأقرب قيم عدد صحيح. |
| static [Subtract](../../system.drawing/size/subtract)(Size, Size) | طرح عرض وارتفاع واحدSize هيكل من العرض والارتفاع آخرSize هيكل . |
| static [Truncate](../../system.drawing/size/truncate)(SizeF) | تحويل المحددSizeF هيكل لSize هيكل باقتطاع قيمSizeF هيكل لقيم الأعداد الصحيحة التالية. |
| override [Equals](../../system.drawing/size/equals#equals_1)(object) | اختبارات لمعرفة ما إذا كان الكائن المحدد بتنسيقSize بنفس أبعاد مثل هذاSize . |
| [Equals](../../system.drawing/size/equals#equals)(Size) | اختبارات أخرى[`Size`](../size) هيكل له نفس الحجم من هذا[`Size`](../size) هيكل . |
| override [GetHashCode](../../system.drawing/size/gethashcode)() | إرجاع رمز تجزئة لهذا الغرضSize هيكل . |
| override [ToString](../../system.drawing/size/tostring)() | تحويل سمات هذا[`Size`](../size) لسلسلة يمكن للبشر قراءتها. |
| [operator +](../../system.drawing/size/op_addition) | إضافة عرض وارتفاع واحدSize هيكل للعرض والارتفاع آخرSize هيكل . |
| [operator /](../../system.drawing/size/op_division#op_division) | تقسيمات[`Size`](../size) بواسطةInt32 المنتجة[`Size`](../size) . (2 operators) |
| [operator ==](../../system.drawing/size/op_equality) | اختبار ما إذا كان اثنانSize الهياكل متساوية. |
| [explicit operator](../../system.drawing/size/op_explicit) | تحويل المحددSize إلى أPoint . |
| [implicit operator](../../system.drawing/size/op_implicit) | تحويل المحددSize إلى أSizeF . |
| [operator !=](../../system.drawing/size/op_inequality) | اختبار ما إذا كان اثنانSize الهياكل مختلفة. |
| [operator *](../../system.drawing/size/op_multiply#op_multiply) | تتكاثر أ[`Size`](../size) بواسطةInt32 المنتجة[`Size`](../size) . (4 operators) |
| [operator -](../../system.drawing/size/op_subtraction) | طرح عرض وارتفاع واحدSize هيكل من العرض والارتفاع آخرSize هيكل . |

## مجالات

| اسم | وصف |
| --- | --- |
| static readonly [Empty](../../system.drawing/size/empty) | يحصل على أSize هيكل يحتوي علىHeight وWidth قيمة 0. |

### أنظر أيضا

* مساحة الاسم [System.Drawing](../../system.drawing)
* المجسم [Aspose.Drawing](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Drawing.dll -->
