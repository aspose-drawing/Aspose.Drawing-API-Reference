---
title: HatchStyle
second_title: مرجع API لـ Aspose.Drawing للـ Java
description: يحدد الأنماط المختلفة المتاحة لكائنات.
type: docs
weight: 27
url: /ar/java/com.aspose.drawing.drawing2d/hatchstyle/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class HatchStyle extends System.Enum
```

يحدد الأنماط المختلفة المتاحة لكائنات [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush).
## الحقول

| حقل | الوصف |
| --- | --- |
| [Horizontal](#Horizontal) | نمط من الخطوط الأفقية. |
| [Vertical](#Vertical) | نمط من الخطوط العمودية. |
| [ForwardDiagonal](#ForwardDiagonal) | نمط من الخطوط على القطر من الزاوية العليا اليسرى إلى الزاوية السفلى اليمنى. |
| [BackwardDiagonal](#BackwardDiagonal) | نمط من الخطوط على القطر من الزاوية العليا اليمنى إلى الزاوية السفلى اليسرى. |
| [Cross](#Cross) | يحدد الخطوط الأفقية والعمودية التي تتقاطع. |
| [DiagonalCross](#DiagonalCross) | نمط من الخطوط القطرية المتقاطعة. |
| [Percent05](#Percent05) | يحدد تعبئة بنسبة 5٪. |
| [Percent10](#Percent10) | يحدد تعبئة بنسبة 10٪. |
| [Percent20](#Percent20) | يحدد تعبئة بنسبة 20٪. |
| [Percent25](#Percent25) | يحدد تعبئة بنسبة 25٪. |
| [Percent30](#Percent30) | يحدد تعبئة بنسبة 30٪. |
| [Percent40](#Percent40) | يحدد تعبئة بنسبة 40٪. |
| [Percent50](#Percent50) | يحدد تعبئة بنسبة 50٪. |
| [Percent60](#Percent60) | يحدد تعبئة بنسبة 60٪. |
| [Percent70](#Percent70) | يحدد تعبئة بنسبة 70٪. |
| [Percent75](#Percent75) | يحدد تعبئة بنسبة 75٪. |
| [Percent80](#Percent80) | يحدد تعبئة بنسبة 80٪. |
| [Percent90](#Percent90) | يحدد تعبئة بنسبة 90٪. |
| [LightDownwardDiagonal](#LightDownwardDiagonal) | يحدد خطوطًا قطرية تميل إلى اليمين من النقاط العليا إلى النقاط السفلى وتكون المسافات بينها أقرب بنسبة 50٪ مقارنةً بـ `System.Drawing.drawing2d.HatchStyle.ForwardDiagonal`، لكنها غير مضادة للتنعيم. |
| [LightUpwardDiagonal](#LightUpwardDiagonal) | يحدد خطوطًا قطرية تميل إلى اليسار من النقاط العليا إلى النقاط السفلى وتكون المسافات بينها أقرب بنسبة 50٪ مقارنةً بـ `System.Drawing.drawing2d.HatchStyle.BackwardDiagonal`، لكنها غير مضادة للتنعيم. |
| [DarkDownwardDiagonal](#DarkDownwardDiagonal) | يحدد خطوطًا قطرية تميل إلى اليمين من النقاط العليا إلى النقاط السفلى، وتكون المسافات بينها أقرب بنسبة 50٪، وتكون عرضها ضعف عرض `System.Drawing.drawing2d.HatchStyle.ForwardDiagonal`. |
| [DarkUpwardDiagonal](#DarkUpwardDiagonal) | يحدد خطوطًا قطرية تميل إلى اليسار من النقاط العليا إلى النقاط السفلى، وتكون المسافات بينها أقرب بنسبة 50٪ مقارنةً بـ `System.Drawing.drawing2d.HatchStyle.BackwardDiagonal`، وتكون عرضها ضعف عرضه، لكن الخطوط غير مضادة للتنعيم. |
| [WideDownwardDiagonal](#WideDownwardDiagonal) | يحدد خطوطًا قطرية تميل إلى اليمين من النقاط العليا إلى النقاط السفلى، وتملك نفس المسافة كما في نمط التعبئة `System.Drawing.drawing2d.HatchStyle.ForwardDiagonal`، وتكون عرضها ثلاثة أضعاف عرضه، لكنها غير مضادة للتنعيم. |
| [WideUpwardDiagonal](#WideUpwardDiagonal) | يحدد خطوطًا قطرية تميل إلى اليسار من النقاط العليا إلى النقاط السفلى، وتملك نفس المسافة كما في نمط التعبئة `System.Drawing.drawing2d.HatchStyle.BackwardDiagonal`، وتكون عرضها ثلاثة أضعاف عرضه، لكنها غير مضادة للتنعيم. |
| [LightVertical](#LightVertical) | يحدد خطوطًا عمودية تكون المسافات بينها أقرب بنسبة 50٪ مقارنةً بـ `System.Drawing.drawing2d.HatchStyle.Vertical`. |
| [LightHorizontal](#LightHorizontal) | يحدد خطوطًا أفقية تكون المسافات بينها أقرب بنسبة 50٪ مقارنةً بـ `System.Drawing.drawing2d.HatchStyle.Horizontal`. |
| [NarrowVertical](#NarrowVertical) | يحدد خطوطًا عمودية تكون المسافات بينها أقرب بنسبة 75٪ مقارنةً بنمط التعبئة `System.Drawing.drawing2d.HatchStyle.Vertical` (أو أقرب بنسبة 25٪ مقارنةً بـ `System.Drawing.drawing2d.HatchStyle.LightVertical`). |
| [NarrowHorizontal](#NarrowHorizontal) | يحدد الخطوط الأفقية التي تكون المسافة بينها أقرب بنسبة 75٪ مقارنةً بنمط التمويه `System.Drawing.drawing2d.HatchStyle.Horizontal` (أو أقرب بنسبة 25٪ مقارنةً بـ `System.Drawing.drawing2d.HatchStyle.LightHorizontal`). |
| [DarkVertical](#DarkVertical) | يحدد الخطوط العمودية التي تكون المسافة بينها أقرب بنسبة 50٪ مقارنةً بـ `System.Drawing.drawing2d.HatchStyle.Vertical` وتكون ضعف عرضها. |
| [DarkHorizontal](#DarkHorizontal) | يحدد الخطوط الأفقية التي تكون المسافة بينها أقرب بنسبة 50٪ مقارنةً بـ `System.Drawing.drawing2d.HatchStyle.Horizontal` وتكون ضعف عرض `System.Drawing.drawing2d.HatchStyle.Horizontal`. |
| [DashedDownwardDiagonal](#DashedDownwardDiagonal) | يحدد الخطوط القطرية المتقطعة التي تميل إلى اليمين من النقاط العلوية إلى النقاط السفلية. |
| [DashedUpwardDiagonal](#DashedUpwardDiagonal) | يحدد الخطوط القطرية المتقطعة التي تميل إلى اليسار من النقاط العلوية إلى النقاط السفلية. |
| [DashedHorizontal](#DashedHorizontal) | يحدد الخطوط الأفقية المتقطعة. |
| [DashedVertical](#DashedVertical) | يحدد الخطوط العمودية المتقطعة. |
| [SmallConfetti](#SmallConfetti) | يحدد نمط التمويه الذي له مظهر القُرصات. |
| [LargeConfetti](#LargeConfetti) | يحدد نمط التمويه الذي له مظهر القُرصات، ويتكون من قطع أكبر من `System.Drawing.drawing2d.HatchStyle.SmallConfetti`. |
| [ZigZag](#ZigZag) | يحدد الخطوط الأفقية التي تتكون من متعرجات. |
| [Wave](#Wave) | يحدد الخطوط الأفقية التي تتكون من علامة المد. |
| [DiagonalBrick](#DiagonalBrick) | يحدد نمط التمويه الذي له مظهر الطوب المتراكم الذي يميل إلى اليسار من النقاط العلوية إلى النقاط السفلية. |
| [HorizontalBrick](#HorizontalBrick) | يحدد نمط التمويه الذي له مظهر الطوب المتراكم أفقياً. |
| [Weave](#Weave) | يحدد نمط التمويه الذي له مظهر مادة منسوجة. |
| [Plaid](#Plaid) | يحدد نمط التمويه الذي له مظهر قماش مخطط. |
| [Divot](#Divot) | يحدد نمط التمويه الذي له مظهر الحفر الصغيرة. |
| [DottedGrid](#DottedGrid) | يحدد الخطوط الأفقية والعمودية، كل منها مكوّن من نقاط، والتي تتقاطع. |
| [DottedDiamond](#DottedDiamond) | يحدد الخطوط القطرية الأمامية والخلفية، كل منها مكوّن من نقاط، والتي تتقاطع. |
| [Shingle](#Shingle) | يحدد نمط التمويه الذي له مظهر القوب المتراكم قطرياً والتي تميل إلى اليمين من النقاط العلوية إلى النقاط السفلية. |
| [Trellis](#Trellis) | يحدد نمط التمويه الذي له مظهر شبكة تعريش. |
| [Sphere](#Sphere) | يحدد نمط التمويه الذي له مظهر كرات موضوعة بجوار بعضها البعض. |
| [SmallGrid](#SmallGrid) | يحدد الخطوط الأفقية والعمودية التي تتقاطع وتكون المسافة بينها أقرب بنسبة 50٪ مقارنةً بنمط التمويه `System.Drawing.drawing2d.HatchStyle.Cross`. |
| [SmallCheckerBoard](#SmallCheckerBoard) | يحدد نمط التمويه الذي له مظهر لوحة شطرنج. |
| [LargeCheckerBoard](#LargeCheckerBoard) | يحدد نمط التمويه الذي له مظهر لوحة شطرنج بمربعات ضعف حجم `System.Drawing.drawing2d.HatchStyle.SmallCheckerBoard`. |
| [OutlinedDiamond](#OutlinedDiamond) | يحدد الخطوط القطرية الأمامية والخلفية التي تتقاطع ولكنها غير مضادة للتنعيم. |
| [SolidDiamond](#SolidDiamond) | يحدد نمط تعبئة له مظهر لوحة شطرنج موضوعة قطريًا. |
| [LargeGrid](#LargeGrid) | يحدد نمط التعبئة `System.Drawing.drawing2d.HatchStyle.Cross`. |
| [Min](#Min) | يحدد نمط التعبئة `System.Drawing.drawing2d.HatchStyle.Horizontal`. |
| [Max](#Max) | يحدد نمط التعبئة `System.Drawing.drawing2d.HatchStyle.SolidDiamond`. |
### Horizontal {#Horizontal}
```
public static final int Horizontal
```


نمط من الخطوط الأفقية.

### Vertical {#Vertical}
```
public static final int Vertical
```


نمط من الخطوط العمودية.

### ForwardDiagonal {#ForwardDiagonal}
```
public static final int ForwardDiagonal
```


نمط من الخطوط على القطر من الزاوية العليا اليسرى إلى الزاوية السفلى اليمنى.

### BackwardDiagonal {#BackwardDiagonal}
```
public static final int BackwardDiagonal
```


نمط من الخطوط على القطر من الزاوية العليا اليمنى إلى الزاوية السفلى اليسرى.

### Cross {#Cross}
```
public static final int Cross
```


يحدد الخطوط الأفقية والعمودية التي تتقاطع.

### DiagonalCross {#DiagonalCross}
```
public static final int DiagonalCross
```


نمط من الخطوط القطرية المتقاطعة.

### Percent05 {#Percent05}
```
public static final int Percent05
```


يحدد تعبئة بنسبة 5٪. نسبة لون المقدمة إلى لون الخلفية هي 5:100.

### Percent10 {#Percent10}
```
public static final int Percent10
```


يحدد تعبئة بنسبة 10٪. نسبة لون المقدمة إلى لون الخلفية هي 10:100.

### Percent20 {#Percent20}
```
public static final int Percent20
```


يحدد تعبئة بنسبة 20٪. نسبة لون المقدمة إلى لون الخلفية هي 20:100.

### Percent25 {#Percent25}
```
public static final int Percent25
```


يحدد تعبئة بنسبة 25٪. نسبة لون المقدمة إلى لون الخلفية هي 25:100.

### Percent30 {#Percent30}
```
public static final int Percent30
```


يحدد تعبئة بنسبة 30٪. نسبة لون المقدمة إلى لون الخلفية هي 30:100.

### Percent40 {#Percent40}
```
public static final int Percent40
```


يحدد تعبئة بنسبة 40٪. نسبة لون المقدمة إلى لون الخلفية هي 40:100.

### Percent50 {#Percent50}
```
public static final int Percent50
```


يحدد تعبئة بنسبة 50٪. نسبة لون المقدمة إلى لون الخلفية هي 50:100.

### Percent60 {#Percent60}
```
public static final int Percent60
```


يحدد تعبئة بنسبة 60٪. نسبة لون المقدمة إلى لون الخلفية هي 60:100.

### Percent70 {#Percent70}
```
public static final int Percent70
```


يحدد تعبئة بنسبة 70٪. نسبة لون المقدمة إلى لون الخلفية هي 70:100.

### Percent75 {#Percent75}
```
public static final int Percent75
```


يحدد تعبئة بنسبة 75٪. نسبة لون المقدمة إلى لون الخلفية هي 75:100.

### Percent80 {#Percent80}
```
public static final int Percent80
```


يحدد تعبئة بنسبة 80٪. نسبة لون المقدمة إلى لون الخلفية هي 80:100.

### Percent90 {#Percent90}
```
public static final int Percent90
```


يحدد تعبئة بنسبة 90٪. نسبة لون المقدمة إلى لون الخلفية هي 90:100.

### LightDownwardDiagonal {#LightDownwardDiagonal}
```
public static final int LightDownwardDiagonal
```


يحدد خطوطًا قطرية تميل إلى اليمين من النقاط العليا إلى النقاط السفلى وتكون المسافات بينها أقرب بنسبة 50٪ مقارنةً بـ `System.Drawing.drawing2d.HatchStyle.ForwardDiagonal`، لكنها غير مضادة للتنعيم.

### LightUpwardDiagonal {#LightUpwardDiagonal}
```
public static final int LightUpwardDiagonal
```


يحدد خطوطًا قطرية تميل إلى اليسار من النقاط العليا إلى النقاط السفلى وتكون المسافات بينها أقرب بنسبة 50٪ مقارنةً بـ `System.Drawing.drawing2d.HatchStyle.BackwardDiagonal`، لكنها غير مضادة للتنعيم.

### DarkDownwardDiagonal {#DarkDownwardDiagonal}
```
public static final int DarkDownwardDiagonal
```


يحدد خطوطًا قطرية تميل إلى اليمين من النقاط العليا إلى النقاط السفلى، وتكون المسافة بينها أقرب بنسبة 50٪ مقارنةً، وعرضها ضعف عرض `System.Drawing.drawing2d.HatchStyle.ForwardDiagonal`. هذا النمط غير مضاد للتنعيم.

### DarkUpwardDiagonal {#DarkUpwardDiagonal}
```
public static final int DarkUpwardDiagonal
```


يحدد خطوطًا قطرية تميل إلى اليسار من النقاط العليا إلى النقاط السفلى، وتكون المسافات بينها أقرب بنسبة 50٪ مقارنةً بـ `System.Drawing.drawing2d.HatchStyle.BackwardDiagonal`، وتكون عرضها ضعف عرضه، لكن الخطوط غير مضادة للتنعيم.

### WideDownwardDiagonal {#WideDownwardDiagonal}
```
public static final int WideDownwardDiagonal
```


يحدد خطوطًا قطرية تميل إلى اليمين من النقاط العليا إلى النقاط السفلى، وتملك نفس المسافة كما في نمط التعبئة `System.Drawing.drawing2d.HatchStyle.ForwardDiagonal`، وتكون عرضها ثلاثة أضعاف عرضه، لكنها غير مضادة للتنعيم.

### WideUpwardDiagonal {#WideUpwardDiagonal}
```
public static final int WideUpwardDiagonal
```


يحدد خطوطًا قطرية تميل إلى اليسار من النقاط العليا إلى النقاط السفلى، وتملك نفس المسافة كما في نمط التعبئة `System.Drawing.drawing2d.HatchStyle.BackwardDiagonal`، وتكون عرضها ثلاثة أضعاف عرضه، لكنها غير مضادة للتنعيم.

### LightVertical {#LightVertical}
```
public static final int LightVertical
```


يحدد خطوطًا عمودية تكون المسافات بينها أقرب بنسبة 50٪ مقارنةً بـ `System.Drawing.drawing2d.HatchStyle.Vertical`.

### LightHorizontal {#LightHorizontal}
```
public static final int LightHorizontal
```


يحدد خطوطًا أفقية تكون المسافات بينها أقرب بنسبة 50٪ مقارنةً بـ `System.Drawing.drawing2d.HatchStyle.Horizontal`.

### NarrowVertical {#NarrowVertical}
```
public static final int NarrowVertical
```


يحدد خطوطًا عمودية تكون المسافات بينها أقرب بنسبة 75٪ مقارنةً بنمط التعبئة `System.Drawing.drawing2d.HatchStyle.Vertical` (أو أقرب بنسبة 25٪ مقارنةً بـ `System.Drawing.drawing2d.HatchStyle.LightVertical`).

### NarrowHorizontal {#NarrowHorizontal}
```
public static final int NarrowHorizontal
```


يحدد الخطوط الأفقية التي تكون المسافة بينها أقرب بنسبة 75٪ مقارنةً بنمط التمويه `System.Drawing.drawing2d.HatchStyle.Horizontal` (أو أقرب بنسبة 25٪ مقارنةً بـ `System.Drawing.drawing2d.HatchStyle.LightHorizontal`).

### DarkVertical {#DarkVertical}
```
public static final int DarkVertical
```


يحدد الخطوط العمودية التي تكون المسافة بينها أقرب بنسبة 50٪ مقارنةً بـ `System.Drawing.drawing2d.HatchStyle.Vertical` وتكون ضعف عرضها.

### DarkHorizontal {#DarkHorizontal}
```
public static final int DarkHorizontal
```


يحدد الخطوط الأفقية التي تكون المسافة بينها أقرب بنسبة 50٪ مقارنةً بـ `System.Drawing.drawing2d.HatchStyle.Horizontal` وتكون ضعف عرض `System.Drawing.drawing2d.HatchStyle.Horizontal`.

### DashedDownwardDiagonal {#DashedDownwardDiagonal}
```
public static final int DashedDownwardDiagonal
```


يحدد الخطوط القطرية المتقطعة التي تميل إلى اليمين من النقاط العلوية إلى النقاط السفلية.

### DashedUpwardDiagonal {#DashedUpwardDiagonal}
```
public static final int DashedUpwardDiagonal
```


يحدد الخطوط القطرية المتقطعة التي تميل إلى اليسار من النقاط العلوية إلى النقاط السفلية.

### DashedHorizontal {#DashedHorizontal}
```
public static final int DashedHorizontal
```


يحدد الخطوط الأفقية المتقطعة.

### DashedVertical {#DashedVertical}
```
public static final int DashedVertical
```


يحدد الخطوط العمودية المتقطعة.

### SmallConfetti {#SmallConfetti}
```
public static final int SmallConfetti
```


يحدد نمط التمويه الذي له مظهر القُرصات.

### LargeConfetti {#LargeConfetti}
```
public static final int LargeConfetti
```


يحدد نمط التمويه الذي له مظهر القُرصات، ويتكون من قطع أكبر من `System.Drawing.drawing2d.HatchStyle.SmallConfetti`.

### ZigZag {#ZigZag}
```
public static final int ZigZag
```


يحدد الخطوط الأفقية التي تتكون من متعرجات.

### Wave {#Wave}
```
public static final int Wave
```


يحدد الخطوط الأفقية التي تتكون من علامة المد.

### DiagonalBrick {#DiagonalBrick}
```
public static final int DiagonalBrick
```


يحدد نمط التمويه الذي له مظهر الطوب المتراكم الذي يميل إلى اليسار من النقاط العلوية إلى النقاط السفلية.

### HorizontalBrick {#HorizontalBrick}
```
public static final int HorizontalBrick
```


يحدد نمط التمويه الذي له مظهر الطوب المتراكم أفقياً.

### Weave {#Weave}
```
public static final int Weave
```


يحدد نمط التمويه الذي له مظهر مادة منسوجة.

### Plaid {#Plaid}
```
public static final int Plaid
```


يحدد نمط التمويه الذي له مظهر قماش مخطط.

### Divot {#Divot}
```
public static final int Divot
```


يحدد نمط التمويه الذي له مظهر الحفر الصغيرة.

### DottedGrid {#DottedGrid}
```
public static final int DottedGrid
```


يحدد الخطوط الأفقية والعمودية، كل منها مكوّن من نقاط، والتي تتقاطع.

### DottedDiamond {#DottedDiamond}
```
public static final int DottedDiamond
```


يحدد الخطوط القطرية الأمامية والخلفية، كل منها مكوّن من نقاط، والتي تتقاطع.

### Shingle {#Shingle}
```
public static final int Shingle
```


يحدد نمط التمويه الذي له مظهر القوب المتراكم قطرياً والتي تميل إلى اليمين من النقاط العلوية إلى النقاط السفلية.

### Trellis {#Trellis}
```
public static final int Trellis
```


يحدد نمط التمويه الذي له مظهر شبكة تعريش.

### Sphere {#Sphere}
```
public static final int Sphere
```


يحدد نمط التمويه الذي له مظهر كرات موضوعة بجوار بعضها البعض.

### SmallGrid {#SmallGrid}
```
public static final int SmallGrid
```


يحدد الخطوط الأفقية والعمودية التي تتقاطع وتكون المسافة بينها أقرب بنسبة 50٪ مقارنةً بنمط التمويه `System.Drawing.drawing2d.HatchStyle.Cross`.

### SmallCheckerBoard {#SmallCheckerBoard}
```
public static final int SmallCheckerBoard
```


يحدد نمط التمويه الذي له مظهر لوحة شطرنج.

### LargeCheckerBoard {#LargeCheckerBoard}
```
public static final int LargeCheckerBoard
```


يحدد نمط التمويه الذي له مظهر لوحة شطرنج بمربعات ضعف حجم `System.Drawing.drawing2d.HatchStyle.SmallCheckerBoard`.

### OutlinedDiamond {#OutlinedDiamond}
```
public static final int OutlinedDiamond
```


يحدد الخطوط القطرية الأمامية والخلفية التي تتقاطع ولكنها غير مضادة للتنعيم.

### SolidDiamond {#SolidDiamond}
```
public static final int SolidDiamond
```


يحدد نمط تعبئة له مظهر لوحة شطرنج موضوعة قطريًا.

### LargeGrid {#LargeGrid}
```
public static final int LargeGrid
```


يحدد نمط التعبئة `System.Drawing.drawing2d.HatchStyle.Cross`.

### Min {#Min}
```
public static final int Min
```


يحدد نمط التعبئة `System.Drawing.drawing2d.HatchStyle.Horizontal`.

### Max {#Max}
```
public static final int Max
```


يحدد نمط التعبئة `System.Drawing.drawing2d.HatchStyle.SolidDiamond`.

