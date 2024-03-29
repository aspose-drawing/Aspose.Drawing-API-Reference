---
title: AddCurve
second_title: Aspose.Drawing لمرجع NET API
description: يضيف منحنى خدد إلى الشكل الحالي. يتم استخدام منحنى العمود الفقري الأساسي لأن المنحنى ينتقل عبر كل نقطة في المصفوفة.
type: docs
weight: 110
url: /ar/net/system.drawing.drawing2d/graphicspath/addcurve/
---
## AddCurve(Point[]) {#addcurve_3}

يضيف منحنى خدد إلى الشكل الحالي. يتم استخدام منحنى العمود الفقري الأساسي لأن المنحنى ينتقل عبر كل نقطة في المصفوفة.

```csharp
public void AddCurve(Point[] points)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| points | Point[] | مجموعة منPoint الهياكل التي تمثل النقاط التي تحدد المنحنى. |

### أنظر أيضا

* struct [Point](../../../system.drawing/point)
* class [GraphicsPath](../../graphicspath)
* مساحة الاسم [System.Drawing.Drawing2D](../../graphicspath)
* المجسم [Aspose.Drawing](../../../)

---

## AddCurve(PointF[]) {#addcurve}

يضيف منحنى خدد إلى الشكل الحالي. يتم استخدام منحنى العمود الفقري الأساسي لأن المنحنى ينتقل عبر كل نقطة في المصفوفة.

```csharp
public void AddCurve(PointF[] points)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| points | PointF[] | مجموعة منPointF الهياكل التي تمثل النقاط التي تحدد المنحنى. |

### أنظر أيضا

* struct [PointF](../../../system.drawing/pointf)
* class [GraphicsPath](../../graphicspath)
* مساحة الاسم [System.Drawing.Drawing2D](../../graphicspath)
* المجسم [Aspose.Drawing](../../../)

---

## AddCurve(PointF[], float) {#addcurve_2}

يضيف منحنى خدد إلى الشكل الحالي.

```csharp
public void AddCurve(PointF[] points, float tension)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| points | PointF[] | مصفوفة من هياكل PointF تمثل النقاط التي تحدد المنحنى. |
| tension | Single | قيمة تحدد المقدار الذي ينحني به المنحنى بين نقاط التحكم . القيم الأكبر من 1 تنتج نتائج غير متوقعة. |

### أنظر أيضا

* struct [PointF](../../../system.drawing/pointf)
* class [GraphicsPath](../../graphicspath)
* مساحة الاسم [System.Drawing.Drawing2D](../../graphicspath)
* المجسم [Aspose.Drawing](../../../)

---

## AddCurve(PointF[], int, int, float) {#addcurve_1}

يضيف منحنى خدد إلى الشكل الحالي.

```csharp
public void AddCurve(PointF[] points, int offset, int numberOfSegments, float tension)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| points | PointF[] | مجموعة منPointF الهياكل التي تمثل النقاط التي تحدد المنحنى. |
| offset | Int32 | فهرس العنصر في ملف*points* المصفوفة المستخدمة كنقطة أولى في المنحنى. |
| numberOfSegments | Int32 | عدد المقاطع المستخدمة لرسم المنحنى. يمكن اعتبار المقطع كخط يربط بين نقطتين. |
| tension | Single | قيمة تحدد المقدار الذي ينحني به المنحنى بين نقاط التحكم. تؤدي القيم الأكبر من 1 إلى نتائج غير متوقعة. |

### أنظر أيضا

* struct [PointF](../../../system.drawing/pointf)
* class [GraphicsPath](../../graphicspath)
* مساحة الاسم [System.Drawing.Drawing2D](../../graphicspath)
* المجسم [Aspose.Drawing](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Drawing.dll -->
