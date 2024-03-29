---
title: Warp
second_title: Aspose.Drawing لمرجع NET API
description: يطبق تحويل الالتواء  المحدد بواسطة مستطيل ومتوازي أضلاع  على هذاGraphicsPathsystem.drawing.drawing2d/graphicspath .
type: docs
weight: 350
url: /ar/net/system.drawing.drawing2d/graphicspath/warp/
---
## Warp(PointF[], RectangleF) {#warp}

يطبق تحويل الالتواء ، المحدد بواسطة مستطيل ومتوازي أضلاع ، على هذا[`GraphicsPath`](../../graphicspath) .

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| destPoints | PointF[] | مصفوفة منPointF الهياكل التي تحدد متوازي الأضلاع الذي يحدده المستطيل*srcRect* يتحول. يمكن أن تحتوي المصفوفة على ثلاثة أو أربعة عناصر. إذا كانت المصفوفة تحتوي على ثلاثة عناصر ، فإن الزاوية اليمنى السفلية من متوازي الأضلاع تكون ضمنية بالنقاط الثلاث الأولى. |
| srcRect | RectangleF | أRectangleF الذي يمثل المستطيل المحول إلى متوازي الأضلاع المحدد بواسطة*destPoints* . |

### أنظر أيضا

* struct [PointF](../../../system.drawing/pointf)
* struct [RectangleF](../../../system.drawing/rectanglef)
* class [GraphicsPath](../../graphicspath)
* مساحة الاسم [System.Drawing.Drawing2D](../../graphicspath)
* المجسم [Aspose.Drawing](../../../)

---

## Warp(PointF[], RectangleF, Matrix) {#warp_1}

يطبق تحويل الالتواء ، المحدد بواسطة مستطيل ومتوازي أضلاع ، على هذا[`GraphicsPath`](../../graphicspath).

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| destPoints | PointF[] | مصفوفة منPointF الهياكل التي تحدد متوازي الأضلاع الذي يحدده المستطيل*srcRect* يتحول. يمكن أن تحتوي المصفوفة على ثلاثة أو أربعة عناصر. إذا كانت المصفوفة تحتوي على ثلاثة عناصر ، فإن الزاوية اليمنى السفلية من متوازي الأضلاع تكون ضمنية بالنقاط الثلاث الأولى. |
| srcRect | RectangleF | أRectangleF الذي يمثل المستطيل المحول إلى متوازي الأضلاع المحدد بواسطة*destPoints* . |
| matrix | Matrix | أ[`Matrix`](../../matrix) يحدد تحويلًا هندسيًا لتطبيقه على المسار. |

### أنظر أيضا

* struct [PointF](../../../system.drawing/pointf)
* struct [RectangleF](../../../system.drawing/rectanglef)
* class [Matrix](../../matrix)
* class [GraphicsPath](../../graphicspath)
* مساحة الاسم [System.Drawing.Drawing2D](../../graphicspath)
* المجسم [Aspose.Drawing](../../../)

---

## Warp(PointF[], RectangleF, Matrix, WarpMode) {#warp_2}

يطبق تحويل الالتواء ، المحدد بواسطة مستطيل ومتوازي أضلاع ، على هذا[`GraphicsPath`](../../graphicspath).

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, WarpMode warpMode)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| destPoints | PointF[] | مصفوفة منPointF الهياكل التي تحدد متوازي الأضلاع الذي يحدده المستطيل*srcRect* يتحول. يمكن أن تحتوي المصفوفة على ثلاثة أو أربعة عناصر . إذا كانت المصفوفة تحتوي على ثلاثة عناصر ، فسيتم تضمين الزاوية اليمنى السفلية من متوازي الأضلاع في النقاط الثلاث الأولى. |
| srcRect | RectangleF | أRectangleF الذي يمثل المستطيل المحول إلى متوازي الأضلاع المحدد بواسطة*destPoints* . |
| matrix | Matrix | أ[`Matrix`](../../matrix) يحدد تحويلًا هندسيًا لتطبيقه على المسار. |
| warpMode | WarpMode | أ[`WarpMode`](../../warpmode) التعداد الذي يحدد ما إذا كانت عملية الالتواء تستخدم الوضع المنظور أو الوضع ثنائي الخطوط. |

### أنظر أيضا

* struct [PointF](../../../system.drawing/pointf)
* struct [RectangleF](../../../system.drawing/rectanglef)
* class [Matrix](../../matrix)
* enum [WarpMode](../../warpmode)
* class [GraphicsPath](../../graphicspath)
* مساحة الاسم [System.Drawing.Drawing2D](../../graphicspath)
* المجسم [Aspose.Drawing](../../../)

---

## Warp(PointF[], RectangleF, Matrix, WarpMode, float) {#warp_3}

يطبق تحويل الالتواء ، المحدد بواسطة مستطيل ومتوازي أضلاع ، على هذا[`GraphicsPath`](../../graphicspath).

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, WarpMode warpMode, 
    float flatness)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| destPoints | PointF[] | مصفوفة منPointF الهياكل التي تحدد متوازي الأضلاع الذي يحدده المستطيل*srcRect* يتحول. يمكن أن تحتوي المصفوفة على ثلاثة أو أربعة عناصر . إذا كانت المصفوفة تحتوي على ثلاثة عناصر ، فسيتم تضمين الزاوية اليمنى السفلية من متوازي الأضلاع في النقاط الثلاث الأولى. |
| srcRect | RectangleF | أRectangleF الذي يمثل المستطيل المحول إلى متوازي الأضلاع المحدد بواسطة*destPoints* . |
| matrix | Matrix | أ[`Matrix`](../../matrix) يحدد تحويلًا هندسيًا لتطبيقه على المسار. |
| warpMode | WarpMode | أ[`WarpMode`](../../warpmode) التعداد الذي يحدد ما إذا كانت عملية الالتواء تستخدم الوضع المنظور أو الوضع ثنائي الخطوط. |
| flatness | Single | قيمة من 0 إلى 1 تحدد مدى استواء المسار الناتج. لمزيد من المعلومات ، راجع[`Flatten`](../flatten) طُرق. |

### أنظر أيضا

* struct [PointF](../../../system.drawing/pointf)
* struct [RectangleF](../../../system.drawing/rectanglef)
* class [Matrix](../../matrix)
* enum [WarpMode](../../warpmode)
* class [GraphicsPath](../../graphicspath)
* مساحة الاسم [System.Drawing.Drawing2D](../../graphicspath)
* المجسم [Aspose.Drawing](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Drawing.dll -->
