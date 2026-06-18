---
title: Region
second_title: مرجع API لـ Aspose.Drawing للـ Java
description: يصف داخل الشكل الرسومي المكوّن من مستطيلات ومسارات.
type: docs
weight: 40
url: /ar/java/com.aspose.drawing/region/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public final class Region implements System.IDisposable
```

يصف داخل الشكل الرسومي المكوّن من مستطيلات ومسارات. لا يمكن وراثة هذه الفئة.
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [Region()](#Region--) | ينشئ مثيلًا جديدًا من الفئة [Region](../../com.aspose.drawing/region). |
| [Region(RectangleF rect)](#Region-com.aspose.drawing.RectangleF-) | ينشئ مثيلًا جديدًا من الفئة [Region](../../com.aspose.drawing/region) من الهيكل [RectangleF](../../com.aspose.drawing/rectanglef) المحدد. |
| [Region(Rectangle rect)](#Region-com.aspose.drawing.Rectangle-) | ينشئ مثيلًا جديدًا من الفئة [Region](../../com.aspose.drawing/region) من الهيكل [Rectangle](../../com.aspose.drawing/rectangle) المحدد. |
| [Region(GraphicsPath path)](#Region-com.aspose.drawing.drawing2d.GraphicsPath-) | ينشئ مثيلًا جديدًا من الفئة [Region](../../com.aspose.drawing/region) باستخدام [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) المحدد. |
| [Region(RegionData rgnData)](#Region-com.aspose.drawing.drawing2d.RegionData-) | ينشئ مثيلًا جديدًا من الفئة [Region](../../com.aspose.drawing/region) من البيانات المحددة. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [dispose()](#dispose--) | يطلق جميع الموارد المستخدمة من قبل هذا [Region](../../com.aspose.drawing/region). |
| [equals(Region region, Graphics g)](#equals-com.aspose.drawing.Region-com.aspose.drawing.Graphics-) | يفحص ما إذا كان [Region](../../com.aspose.drawing/region) المحدد مطابقًا لهذا [Region](../../com.aspose.drawing/region) على سطح الرسم المحدد. |
| [deepClone()](#deepClone--) | ينشئ نسخة مطابقة تمامًا من هذا [Region](../../com.aspose.drawing/region). |
| [makeInfinite()](#makeInfinite--) | يُهيئ كائن [Region](../../com.aspose.drawing/region) هذا إلى داخل لا نهائي. |
| [makeEmpty()](#makeEmpty--) | يُهيئ هذا [Region](../../com.aspose.drawing/region) إلى داخل فارغ. |
| [intersect(RectangleF rect)](#intersect-com.aspose.drawing.RectangleF-) | يُحدّث هذا [Region](../../com.aspose.drawing/region) إلى تقاطع نفسه مع بنية [RectangleF](../../com.aspose.drawing/rectanglef) المحددة. |
| [intersect(Rectangle rect)](#intersect-com.aspose.drawing.Rectangle-) | يُحدّث هذا [Region](../../com.aspose.drawing/region) إلى تقاطع نفسه مع بنية [Rectangle](../../com.aspose.drawing/rectangle) المحددة. |
| [intersect(GraphicsPath path)](#intersect-com.aspose.drawing.drawing2d.GraphicsPath-) | يُحدّث هذا [Region](../../com.aspose.drawing/region) إلى تقاطع نفسه مع [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) المحدد. |
| [intersect(Region region)](#intersect-com.aspose.drawing.Region-) | يُحدّث هذا [Region](../../com.aspose.drawing/region) إلى تقاطع نفسه مع [Region](../../com.aspose.drawing/region) المحدد. |
| [union(RectangleF rect)](#union-com.aspose.drawing.RectangleF-) | يُحدّث هذا [Region](../../com.aspose.drawing/region) إلى اتحاد نفسه مع بنية [RectangleF](../../com.aspose.drawing/rectanglef) المحددة. |
| [union(Rectangle rect)](#union-com.aspose.drawing.Rectangle-) | يُحدّث هذا [Region](../../com.aspose.drawing/region) إلى اتحاد نفسه مع بنية [Rectangle](../../com.aspose.drawing/rectangle) المحددة. |
| [union(GraphicsPath path)](#union-com.aspose.drawing.drawing2d.GraphicsPath-) | يُحدّث هذا [Region](../../com.aspose.drawing/region) إلى اتحاد نفسه مع [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) المحدد. |
| [union(Region region)](#union-com.aspose.drawing.Region-) | يُحدّث هذا [Region](../../com.aspose.drawing/region) إلى اتحاد نفسه مع [Region](../../com.aspose.drawing/region) المحدد. |
| [getRegionData()](#getRegionData--) | يرجع [RegionData](../../com.aspose.drawing.drawing2d/regiondata) الذي يمثل المعلومات التي تصف هذا [Region](../../com.aspose.drawing/region). |
| [xor(RectangleF rect)](#xor-com.aspose.drawing.RectangleF-) | يُحدّث هذا [Region](../../com.aspose.drawing/region) إلى اتحاد ناقص تقاطع نفسه مع بنية [RectangleF](../../com.aspose.drawing/rectanglef) المحددة. |
| [xor(Rectangle rect)](#xor-com.aspose.drawing.Rectangle-) | يُحدّث هذا [Region](../../com.aspose.drawing/region) إلى اتحاد ناقص تقاطع نفسه مع بنية [Rectangle](../../com.aspose.drawing/rectangle) المحددة. |
| [xor(GraphicsPath path)](#xor-com.aspose.drawing.drawing2d.GraphicsPath-) | يُحدّث هذا [Region](../../com.aspose.drawing/region) إلى اتحاد ناقص تقاطع نفسه مع [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) المحدد. |
| [xor(Region region)](#xor-com.aspose.drawing.Region-) | يُحدّث هذا [Region](../../com.aspose.drawing/region) إلى اتحاد ناقص تقاطع نفسه مع [Region](../../com.aspose.drawing/region) المحدد. |
| [exclude(RectangleF rect)](#exclude-com.aspose.drawing.RectangleF-) | يُحدّث هذا [Region](../../com.aspose.drawing/region) ليحتوي فقط على الجزء من داخلته الذي لا يتقاطع مع بنية [RectangleF](../../com.aspose.drawing/rectanglef) المحددة. |
| [exclude(Rectangle rect)](#exclude-com.aspose.drawing.Rectangle-) | يُحدّث هذا [Region](../../com.aspose.drawing/region) ليحتوي فقط على الجزء من داخلته الذي لا يتقاطع مع بنية [Rectangle](../../com.aspose.drawing/rectangle) المحددة. |
| [exclude(GraphicsPath path)](#exclude-com.aspose.drawing.drawing2d.GraphicsPath-) | يُحدّث هذا [Region](../../com.aspose.drawing/region) ليحتوي فقط على الجزء من داخلته الذي لا يتقاطع مع [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) المحدد. |
| [exclude(Region region)](#exclude-com.aspose.drawing.Region-) | يُحدّث هذا [Region](../../com.aspose.drawing/region) ليحتوي فقط على الجزء من داخلته الذي لا يتقاطع مع [Region](../../com.aspose.drawing/region) المحدد. |
| [complement(RectangleF rect)](#complement-com.aspose.drawing.RectangleF-) | يُحدّث هذا [Region](../../com.aspose.drawing/region) ليحتوي على الجزء من بنية [RectangleF](../../com.aspose.drawing/rectanglef) المحددة الذي لا يتقاطع مع هذا [Region](../../com.aspose.drawing/region). |
| [complement(Rectangle rect)](#complement-com.aspose.drawing.Rectangle-) | يُحدّث هذا [Region](../../com.aspose.drawing/region) ليحتوي على الجزء من بنية [Rectangle](../../com.aspose.drawing/rectangle) المحددة الذي لا يتقاطع مع هذا [Region](../../com.aspose.drawing/region). |
| [complement(GraphicsPath path)](#complement-com.aspose.drawing.drawing2d.GraphicsPath-) | يُحدّث هذا [Region](../../com.aspose.drawing/region) ليحتوي على الجزء من [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) المحدد الذي لا يتقاطع مع هذا [Region](../../com.aspose.drawing/region). |
| [complement(Region region)](#complement-com.aspose.drawing.Region-) | يقوم بتحديث هذا [Region](../../com.aspose.drawing/region) ليحتوي على الجزء من الـ[Region](../../com.aspose.drawing/region) المحدد الذي لا يتقاطع مع هذا [Region](../../com.aspose.drawing/region). |
| [translate(float dx, float dy)](#translate-float-float-) | يُزِح إحداثيات هذا [Region](../../com.aspose.drawing/region) بالمقدار المحدد. |
| [translate(int dx, int dy)](#translate-int-int-) | يُزِح إحداثيات هذا [Region](../../com.aspose.drawing/region) بالمقدار المحدد. |
| [transform(Matrix matrix)](#transform-com.aspose.drawing.drawing2d.Matrix-) | يحوِّل هذا [Region](../../com.aspose.drawing/region) باستخدام الـ[Matrix](../../com.aspose.drawing.drawing2d/matrix) المحدد. |
| [getBounds(Graphics g)](#getBounds-com.aspose.drawing.Graphics-) | يحصل على بنية [RectangleF](../../com.aspose.drawing/rectanglef) تمثل مستطيل يحدّ هذا [Region](../../com.aspose.drawing/region) على سطح الرسم لكائن [Graphics](../../com.aspose.drawing/graphics). |
| [getRegionScans(Matrix matrix)](#getRegionScans-com.aspose.drawing.drawing2d.Matrix-) | يرجع مصفوفة من بنى [RectangleF](../../com.aspose.drawing/rectanglef) التي تقرب هذا [Region](../../com.aspose.drawing/region) بعد تطبيق تحويل المصفوفة المحدد. |
| [isEmpty(Graphics g)](#isEmpty-com.aspose.drawing.Graphics-) | يفحص ما إذا كان لهذا [Region](../../com.aspose.drawing/region) داخل فارغ على سطح الرسم المحدد. |
| [isInfinite(Graphics g)](#isInfinite-com.aspose.drawing.Graphics-) | يفحص ما إذا كان لهذا [Region](../../com.aspose.drawing/region) داخل لا نهائي على سطح الرسم المحدد. |
| [isVisible(float x, float y)](#isVisible-float-float-) | يفحص ما إذا كانت النقطة المحددة موجودة داخل هذا [Region](../../com.aspose.drawing/region). |
| [isVisible(PointF point)](#isVisible-com.aspose.drawing.PointF-) | يفحص ما إذا كانت بنية [PointF](../../com.aspose.drawing/pointf) المحددة موجودة داخل هذا [Region](../../com.aspose.drawing/region). |
| [isVisible(float x, float y, Graphics g)](#isVisible-float-float-com.aspose.drawing.Graphics-) | يفحص ما إذا كانت النقطة المحددة موجودة داخل هذا [Region](../../com.aspose.drawing/region) عند رسمها باستخدام الـ[Graphics](../../com.aspose.drawing/graphics) المحدد. |
| [isVisible(PointF point, Graphics g)](#isVisible-com.aspose.drawing.PointF-com.aspose.drawing.Graphics-) | يفحص ما إذا كانت بنية [PointF](../../com.aspose.drawing/pointf) المحددة موجودة داخل هذا [Region](../../com.aspose.drawing/region) عند رسمها باستخدام الـ[Graphics](../../com.aspose.drawing/graphics) المحدد. |
| [isVisible(float x, float y, float width, float height)](#isVisible-float-float-float-float-) | يفحص ما إذا كان أي جزء من المستطيل المحدد موجودًا داخل هذا [Region](../../com.aspose.drawing/region). |
| [isVisible(RectangleF rect)](#isVisible-com.aspose.drawing.RectangleF-) | يفحص ما إذا كان أي جزء من بنية [RectangleF](../../com.aspose.drawing/rectanglef) المحددة موجودًا داخل هذا [Region](../../com.aspose.drawing/region). |
| [isVisible(float x, float y, float width, float height, Graphics g)](#isVisible-float-float-float-float-com.aspose.drawing.Graphics-) | يفحص ما إذا كان أي جزء من المستطيل المحدد موجودًا داخل هذا [Region](../../com.aspose.drawing/region) عند رسمه باستخدام الـ[Graphics](../../com.aspose.drawing/graphics) المحدد. |
| [isVisible(RectangleF rect, Graphics g)](#isVisible-com.aspose.drawing.RectangleF-com.aspose.drawing.Graphics-) | يفحص ما إذا كان أي جزء من بنية [RectangleF](../../com.aspose.drawing/rectanglef) المحددة موجودًا داخل هذا [Region](../../com.aspose.drawing/region) عند رسمه باستخدام الـ[Graphics](../../com.aspose.drawing/graphics) المحدد. |
| [isVisible(int x, int y, Graphics g)](#isVisible-int-int-com.aspose.drawing.Graphics-) | يفحص ما إذا كانت النقطة المحددة موجودة داخل كائن [Region](../../com.aspose.drawing/region) عند رسمه باستخدام كائن الـ[Graphics](../../com.aspose.drawing/graphics) المحدد. |
| [isVisible(Point point)](#isVisible-com.aspose.drawing.Point-) | يفحص ما إذا كانت بنية [Point](../../com.aspose.drawing/point) المحددة موجودة داخل هذا [Region](../../com.aspose.drawing/region). |
| [isVisible(Point point, Graphics g)](#isVisible-com.aspose.drawing.Point-com.aspose.drawing.Graphics-) | يفحص ما إذا كانت بنية [Point](../../com.aspose.drawing/point) المحددة موجودة داخل هذا [Region](../../com.aspose.drawing/region) عند رسمها باستخدام الـ[Graphics](../../com.aspose.drawing/graphics) المحدد. |
| [isVisible(int x, int y, int width, int height)](#isVisible-int-int-int-int-) | يفحص ما إذا كان أي جزء من المستطيل المحدد موجودًا داخل هذا [Region](../../com.aspose.drawing/region). |
| [isVisible(Rectangle rect)](#isVisible-com.aspose.drawing.Rectangle-) | يفحص ما إذا كان أي جزء من بنية [Rectangle](../../com.aspose.drawing/rectangle) المحددة موجودًا داخل هذا [Region](../../com.aspose.drawing/region). |
| [isVisible(int x, int y, int width, int height, Graphics g)](#isVisible-int-int-int-int-com.aspose.drawing.Graphics-) | يفحص ما إذا كان أي جزء من المستطيل المحدد موجودًا داخل هذا [Region](../../com.aspose.drawing/region) عند رسمه باستخدام الـ[Graphics](../../com.aspose.drawing/graphics) المحدد. |
| [isVisible(Rectangle rect, Graphics g)](#isVisible-com.aspose.drawing.Rectangle-com.aspose.drawing.Graphics-) | يفحص ما إذا كان أي جزء من بنية [Rectangle](../../com.aspose.drawing/rectangle) المحددة موجودًا داخل هذا [Region](../../com.aspose.drawing/region) عند رسمه باستخدام الـ[Graphics](../../com.aspose.drawing/graphics) المحدد. |
### Region() {#Region--}
```
public Region()
```


ينشئ مثيلًا جديدًا من الفئة [Region](../../com.aspose.drawing/region).

### Region(RectangleF rect) {#Region-com.aspose.drawing.RectangleF-}
```
public Region(RectangleF rect)
```


ينشئ مثيلًا جديدًا من الفئة [Region](../../com.aspose.drawing/region) من الهيكل [RectangleF](../../com.aspose.drawing/rectanglef) المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | بنية [RectangleF](../../com.aspose.drawing/rectanglef) التي تحدد داخل الـ[Region](../../com.aspose.drawing/region) الجديد. |

### Region(Rectangle rect) {#Region-com.aspose.drawing.Rectangle-}
```
public Region(Rectangle rect)
```


ينشئ مثيلًا جديدًا من الفئة [Region](../../com.aspose.drawing/region) من الهيكل [Rectangle](../../com.aspose.drawing/rectangle) المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | بنية [Rectangle](../../com.aspose.drawing/rectangle) التي تحدد داخل الـ[Region](../../com.aspose.drawing/region) الجديد. |

### Region(GraphicsPath path) {#Region-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public Region(GraphicsPath path)
```


ينشئ مثيلًا جديدًا من الفئة [Region](../../com.aspose.drawing/region) باستخدام [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) الذي يحدد الـ[Region](../../com.aspose.drawing/region) الجديد. |

### Region(RegionData rgnData) {#Region-com.aspose.drawing.drawing2d.RegionData-}
```
public Region(RegionData rgnData)
```


ينشئ مثيلًا جديدًا من الفئة [Region](../../com.aspose.drawing/region) من البيانات المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rgnData | [RegionData](../../com.aspose.drawing.drawing2d/regiondata) | [RegionData](../../com.aspose.drawing.drawing2d/regiondata) الذي يحدد داخل الـ[Region](../../com.aspose.drawing/region) الجديد. |

### dispose() {#dispose--}
```
public void dispose()
```


يطلق جميع الموارد المستخدمة من قبل هذا [Region](../../com.aspose.drawing/region).

### equals(Region region, Graphics g) {#equals-com.aspose.drawing.Region-com.aspose.drawing.Graphics-}
```
public boolean equals(Region region, Graphics g)
```


يفحص ما إذا كان [Region](../../com.aspose.drawing/region) المحدد مطابقًا لهذا [Region](../../com.aspose.drawing/region) على سطح الرسم المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| region | [Region](../../com.aspose.drawing/region) | الـ[Region](../../com.aspose.drawing/region) للاختبار. |
| g | [Graphics](../../com.aspose.drawing/graphics) | عنصر [Graphics](../../com.aspose.drawing/graphics) يمثل سطح رسم. |

**Returns:**
منطقي - true إذا كان داخل المنطقة مطابقة لداخل هذه المنطقة عندما يُطبق التحويل المرتبط بالمعامل `g`؛ وإلا false.
### deepClone() {#deepClone--}
```
public Region deepClone()
```


ينشئ نسخة مطابقة تمامًا من هذا [Region](../../com.aspose.drawing/region).

**Returns:**
[Region](../../com.aspose.drawing/region) - The [Region](../../com.aspose.drawing/region) that this method creates.
### makeInfinite() {#makeInfinite--}
```
public void makeInfinite()
```


يُهيئ كائن [Region](../../com.aspose.drawing/region) هذا إلى داخل لا نهائي.

### makeEmpty() {#makeEmpty--}
```
public void makeEmpty()
```


يُهيئ هذا [Region](../../com.aspose.drawing/region) إلى داخل فارغ.

### intersect(RectangleF rect) {#intersect-com.aspose.drawing.RectangleF-}
```
public void intersect(RectangleF rect)
```


يُحدّث هذا [Region](../../com.aspose.drawing/region) إلى تقاطع نفسه مع بنية [RectangleF](../../com.aspose.drawing/rectanglef) المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | الـ [RectangleF](../../com.aspose.drawing/rectanglef) بنية للتقاطع مع هذه [Region](../../com.aspose.drawing/region). |

### intersect(Rectangle rect) {#intersect-com.aspose.drawing.Rectangle-}
```
public void intersect(Rectangle rect)
```


يُحدّث هذا [Region](../../com.aspose.drawing/region) إلى تقاطع نفسه مع بنية [Rectangle](../../com.aspose.drawing/rectangle) المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | الـ [Rectangle](../../com.aspose.drawing/rectangle) بنية للتقاطع مع هذه [Region](../../com.aspose.drawing/region). |

### intersect(GraphicsPath path) {#intersect-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public void intersect(GraphicsPath path)
```


يُحدّث هذا [Region](../../com.aspose.drawing/region) إلى تقاطع نفسه مع [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | الـ [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) للتقاطع مع هذه [Region](../../com.aspose.drawing/region). |

### intersect(Region region) {#intersect-com.aspose.drawing.Region-}
```
public void intersect(Region region)
```


يُحدّث هذا [Region](../../com.aspose.drawing/region) إلى تقاطع نفسه مع [Region](../../com.aspose.drawing/region) المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| region | [Region](../../com.aspose.drawing/region) | الـ [Region](../../com.aspose.drawing/region) للتقاطع مع هذه [Region](../../com.aspose.drawing/region). |

### union(RectangleF rect) {#union-com.aspose.drawing.RectangleF-}
```
public void union(RectangleF rect)
```


يُحدّث هذا [Region](../../com.aspose.drawing/region) إلى اتحاد نفسه مع بنية [RectangleF](../../com.aspose.drawing/rectanglef) المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | rect | [RectangleF](../../com.aspose.drawing/rectanglef) | الـ [RectangleF](../../com.aspose.drawing/rectanglef) بنية للاتحاد مع هذه [Region](../../com.aspose.drawing/region). |

--------------------

الاتحاد يترك المنطقة اللانهائية كمنطقة لا نهائية. |

### union(Rectangle rect) {#union-com.aspose.drawing.Rectangle-}
```
public void union(Rectangle rect)
```


يُحدّث هذا [Region](../../com.aspose.drawing/region) إلى اتحاد نفسه مع بنية [Rectangle](../../com.aspose.drawing/rectangle) المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | rect | [Rectangle](../../com.aspose.drawing/rectangle) | الـ [Rectangle](../../com.aspose.drawing/rectangle) بنية للاتحاد مع هذه [Region](../../com.aspose.drawing/region). |

--------------------

الاتحاد يترك المنطقة اللانهائية كمنطقة لا نهائية. |

### union(GraphicsPath path) {#union-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public void union(GraphicsPath path)
```


يُحدّث هذا [Region](../../com.aspose.drawing/region) إلى اتحاد نفسه مع [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | الـ [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) للاتحاد مع هذه [Region](../../com.aspose.drawing/region). |

--------------------

الاتحاد يترك المنطقة اللانهائية كمنطقة لا نهائية. |

### union(Region region) {#union-com.aspose.drawing.Region-}
```
public void union(Region region)
```


يُحدّث هذا [Region](../../com.aspose.drawing/region) إلى اتحاد نفسه مع [Region](../../com.aspose.drawing/region) المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | region | [Region](../../com.aspose.drawing/region) | الـ [Region](../../com.aspose.drawing/region) للاتحاد مع هذه [Region](../../com.aspose.drawing/region). |

--------------------

الاتحاد يترك المنطقة اللانهائية كمنطقة لا نهائية. |

### getRegionData() {#getRegionData--}
```
public RegionData getRegionData()
```


يرجع [RegionData](../../com.aspose.drawing.drawing2d/regiondata) الذي يمثل المعلومات التي تصف هذا [Region](../../com.aspose.drawing/region).

**Returns:**
[RegionData](../../com.aspose.drawing.drawing2d/regiondata) - A [RegionData](../../com.aspose.drawing.drawing2d/regiondata) that represents the information that describes this [Region](../../com.aspose.drawing/region).
### xor(RectangleF rect) {#xor-com.aspose.drawing.RectangleF-}
```
public void xor(RectangleF rect)
```


يُحدّث هذا [Region](../../com.aspose.drawing/region) إلى اتحاد ناقص تقاطع نفسه مع بنية [RectangleF](../../com.aspose.drawing/rectanglef) المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | الـ [RectangleF](../../com.aspose.drawing/rectanglef) بنية للقيام بـ `M:Region.Xor(Drawing2D.GraphicsPath)` مع هذه [Region](../../com.aspose.drawing/region). |

### xor(Rectangle rect) {#xor-com.aspose.drawing.Rectangle-}
```
public void xor(Rectangle rect)
```


يُحدّث هذا [Region](../../com.aspose.drawing/region) إلى اتحاد ناقص تقاطع نفسه مع بنية [Rectangle](../../com.aspose.drawing/rectangle) المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | الـ [Rectangle](../../com.aspose.drawing/rectangle) بنية للقيام بـ `M:Region.Xor(Rectangle)` مع هذه [Region](../../com.aspose.drawing/region). |

### xor(GraphicsPath path) {#xor-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public void xor(GraphicsPath path)
```


يُحدّث هذا [Region](../../com.aspose.drawing/region) إلى اتحاد ناقص تقاطع نفسه مع [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | الـ [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) للقيام بـ `M:Region.Xor(GraphicsPath)` مع هذه [Region](../../com.aspose.drawing/region). |

### xor(Region region) {#xor-com.aspose.drawing.Region-}
```
public void xor(Region region)
```


يُحدّث هذا [Region](../../com.aspose.drawing/region) إلى اتحاد ناقص تقاطع نفسه مع [Region](../../com.aspose.drawing/region) المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| region | [Region](../../com.aspose.drawing/region) | الـ [Region](../../com.aspose.drawing/region) للقيام بـ `M:Region.Xor(Region)` مع هذه [Region](../../com.aspose.drawing/region). |

### exclude(RectangleF rect) {#exclude-com.aspose.drawing.RectangleF-}
```
public void exclude(RectangleF rect)
```


يُحدّث هذا [Region](../../com.aspose.drawing/region) ليحتوي فقط على الجزء من داخلته الذي لا يتقاطع مع بنية [RectangleF](../../com.aspose.drawing/rectanglef) المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | الـ [RectangleF](../../com.aspose.drawing/rectanglef) بنية لاستبعادها من هذه [Region](../../com.aspose.drawing/region). |

### exclude(Rectangle rect) {#exclude-com.aspose.drawing.Rectangle-}
```
public void exclude(Rectangle rect)
```


يُحدّث هذا [Region](../../com.aspose.drawing/region) ليحتوي فقط على الجزء من داخلته الذي لا يتقاطع مع بنية [Rectangle](../../com.aspose.drawing/rectangle) المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | الـ [Rectangle](../../com.aspose.drawing/rectangle) بنية لاستبعادها من هذه [Region](../../com.aspose.drawing/region). |

### exclude(GraphicsPath path) {#exclude-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public void exclude(GraphicsPath path)
```


يُحدّث هذا [Region](../../com.aspose.drawing/region) ليحتوي فقط على الجزء من داخلته الذي لا يتقاطع مع [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | الـ [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) لاستبعادها من هذه [Region](../../com.aspose.drawing/region). |

### exclude(Region region) {#exclude-com.aspose.drawing.Region-}
```
public void exclude(Region region)
```


يُحدّث هذا [Region](../../com.aspose.drawing/region) ليحتوي فقط على الجزء من داخلته الذي لا يتقاطع مع [Region](../../com.aspose.drawing/region) المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| region | [Region](../../com.aspose.drawing/region) | الـ [Region](../../com.aspose.drawing/region) لاستبعادها من هذه [Region](../../com.aspose.drawing/region). |

### complement(RectangleF rect) {#complement-com.aspose.drawing.RectangleF-}
```
public void complement(RectangleF rect)
```


يُحدّث هذا [Region](../../com.aspose.drawing/region) ليحتوي على الجزء من بنية [RectangleF](../../com.aspose.drawing/rectanglef) المحددة الذي لا يتقاطع مع هذا [Region](../../com.aspose.drawing/region).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | الـ [RectangleF](../../com.aspose.drawing/rectanglef) بنية لتكملة هذه [Region](../../com.aspose.drawing/region). |

### complement(Rectangle rect) {#complement-com.aspose.drawing.Rectangle-}
```
public void complement(Rectangle rect)
```


يُحدّث هذا [Region](../../com.aspose.drawing/region) ليحتوي على الجزء من بنية [Rectangle](../../com.aspose.drawing/rectangle) المحددة الذي لا يتقاطع مع هذا [Region](../../com.aspose.drawing/region).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | الـ [Rectangle](../../com.aspose.drawing/rectangle) بنية لتكملة هذه [Region](../../com.aspose.drawing/region). |

### complement(GraphicsPath path) {#complement-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public void complement(GraphicsPath path)
```


يُحدّث هذا [Region](../../com.aspose.drawing/region) ليحتوي على الجزء من [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) المحدد الذي لا يتقاطع مع هذا [Region](../../com.aspose.drawing/region).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | الـ [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) لتكملة هذه [Region](../../com.aspose.drawing/region). |

### complement(Region region) {#complement-com.aspose.drawing.Region-}
```
public void complement(Region region)
```


يقوم بتحديث هذا [Region](../../com.aspose.drawing/region) ليحتوي على الجزء من الـ[Region](../../com.aspose.drawing/region) المحدد الذي لا يتقاطع مع هذا [Region](../../com.aspose.drawing/region).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| region | [Region](../../com.aspose.drawing/region) | كائن الـ [Region](../../com.aspose.drawing/region) لتكملة كائن هذه [Region](../../com.aspose.drawing/region). |

### translate(float dx, float dy) {#translate-float-float-}
```
public void translate(float dx, float dy)
```


يُزِح إحداثيات هذا [Region](../../com.aspose.drawing/region) بالمقدار المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| dx | float | القيمة لإزاحة هذه [Region](../../com.aspose.drawing/region) أفقياً. |
| dy | float | القيمة لإزاحة هذه [Region](../../com.aspose.drawing/region) رأسياً. |

### translate(int dx, int dy) {#translate-int-int-}
```
public void translate(int dx, int dy)
```


يُزِح إحداثيات هذا [Region](../../com.aspose.drawing/region) بالمقدار المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| dx | int | المقدار لإزاحة هذه [Region](../../com.aspose.drawing/region) أفقياً |
| dy | int | القيمة لإزاحة هذه [Region](../../com.aspose.drawing/region) رأسياً. |

### transform(Matrix matrix) {#transform-com.aspose.drawing.drawing2d.Matrix-}
```
public void transform(Matrix matrix)
```


يحوِّل هذا [Region](../../com.aspose.drawing/region) باستخدام الـ[Matrix](../../com.aspose.drawing.drawing2d/matrix) المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | الـ[Matrix](../../com.aspose.drawing.drawing2d/matrix) التي يتم من خلالها تحويل هذه [Region](../../com.aspose.drawing/region). |

### getBounds(Graphics g) {#getBounds-com.aspose.drawing.Graphics-}
```
public RectangleF getBounds(Graphics g)
```


يحصل على بنية [RectangleF](../../com.aspose.drawing/rectanglef) تمثل مستطيل يحدّ هذا [Region](../../com.aspose.drawing/region) على سطح الرسم لكائن [Graphics](../../com.aspose.drawing/graphics).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| g | [Graphics](../../com.aspose.drawing/graphics) | الـ[Graphics](../../com.aspose.drawing/graphics) التي يتم رسم هذه [Region](../../com.aspose.drawing/region) عليها. |

**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef) - A [RectangleF](../../com.aspose.drawing/rectanglef) structure that represents the bounding rectangle for this [Region](../../com.aspose.drawing/region) on the specified drawing surface.
### getRegionScans(Matrix matrix) {#getRegionScans-com.aspose.drawing.drawing2d.Matrix-}
```
public RectangleF[] getRegionScans(Matrix matrix)
```


يرجع مصفوفة من بنى [RectangleF](../../com.aspose.drawing/rectanglef) التي تقرب هذا [Region](../../com.aspose.drawing/region) بعد تطبيق تحويل المصفوفة المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | [Matrix](../../com.aspose.drawing.drawing2d/matrix) تمثل تحويلًا هندسيًا لتطبيقه على المنطقة. |

**Returns:**
com.aspose.drawing.RectangleF[] - مصفوفة من هياكل [RectangleF](../../com.aspose.drawing/rectanglef) التي تقرب هذه [Region](../../com.aspose.drawing/region) بعد تطبيق تحويل المصفوفة المحدد.
### isEmpty(Graphics g) {#isEmpty-com.aspose.drawing.Graphics-}
```
public boolean isEmpty(Graphics g)
```


يفحص ما إذا كان لهذا [Region](../../com.aspose.drawing/region) داخل فارغ على سطح الرسم المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| g | [Graphics](../../com.aspose.drawing/graphics) | عنصر [Graphics](../../com.aspose.drawing/graphics) يمثل سطح رسم. |

**Returns:**
boolean - true إذا كان داخل هذه [Region](../../com.aspose.drawing/region) فارغًا عند تطبيق التحويل المرتبط بـ `g`؛ وإلا false.
### isInfinite(Graphics g) {#isInfinite-com.aspose.drawing.Graphics-}
```
public boolean isInfinite(Graphics g)
```


يفحص ما إذا كان لهذا [Region](../../com.aspose.drawing/region) داخل لا نهائي على سطح الرسم المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| g | [Graphics](../../com.aspose.drawing/graphics) | عنصر [Graphics](../../com.aspose.drawing/graphics) يمثل سطح رسم. |

**Returns:**
boolean - true إذا كان داخل هذه [Region](../../com.aspose.drawing/region) لا نهائيًا عند تطبيق التحويل المرتبط بـ `g`؛ وإلا false.
### isVisible(float x, float y) {#isVisible-float-float-}
```
public boolean isVisible(float x, float y)
```


يفحص ما إذا كانت النقطة المحددة موجودة داخل هذا [Region](../../com.aspose.drawing/region).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| x | float | الإحداثي x للنقطة المراد اختبارها. |
| y | float | الإحداثي الصادي للنقطة لاختبارها. |

**Returns:**
boolean - true عندما تكون النقطة المحددة داخل هذه [Region](../../com.aspose.drawing/region)؛ وإلا false.
### isVisible(PointF point) {#isVisible-com.aspose.drawing.PointF-}
```
public boolean isVisible(PointF point)
```


يفحص ما إذا كانت بنية [PointF](../../com.aspose.drawing/pointf) المحددة موجودة داخل هذا [Region](../../com.aspose.drawing/region).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| point | [PointF](../../com.aspose.drawing/pointf) | الـ[PointF](../../com.aspose.drawing/pointf) الهيكل للاختبار. |

**Returns:**
boolean - true عندما تكون `point` داخل هذه [Region](../../com.aspose.drawing/region)؛ وإلا false.
### isVisible(float x, float y, Graphics g) {#isVisible-float-float-com.aspose.drawing.Graphics-}
```
public boolean isVisible(float x, float y, Graphics g)
```


يفحص ما إذا كانت النقطة المحددة موجودة داخل هذا [Region](../../com.aspose.drawing/region) عند رسمها باستخدام الـ[Graphics](../../com.aspose.drawing/graphics) المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| x | float | الإحداثي x للنقطة المراد اختبارها. |
| y | float | الإحداثي الصادي للنقطة لاختبارها. |
| g | [Graphics](../../com.aspose.drawing/graphics) | [Graphics](../../com.aspose.drawing/graphics) تمثل سياق رسومي. |

**Returns:**
boolean - true عندما تكون النقطة المحددة داخل هذه [Region](../../com.aspose.drawing/region)؛ وإلا false.
### isVisible(PointF point, Graphics g) {#isVisible-com.aspose.drawing.PointF-com.aspose.drawing.Graphics-}
```
public boolean isVisible(PointF point, Graphics g)
```


يفحص ما إذا كانت بنية [PointF](../../com.aspose.drawing/pointf) المحددة موجودة داخل هذا [Region](../../com.aspose.drawing/region) عند رسمها باستخدام الـ[Graphics](../../com.aspose.drawing/graphics) المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| point | [PointF](../../com.aspose.drawing/pointf) | الـ[PointF](../../com.aspose.drawing/pointf) الهيكل للاختبار. |
| g | [Graphics](../../com.aspose.drawing/graphics) | [Graphics](../../com.aspose.drawing/graphics) تمثل سياق رسومي. |

**Returns:**
boolean - true عندما تكون `point` داخل هذه [Region](../../com.aspose.drawing/region)؛ وإلا false.
### isVisible(float x, float y, float width, float height) {#isVisible-float-float-float-float-}
```
public boolean isVisible(float x, float y, float width, float height)
```


يفحص ما إذا كان أي جزء من المستطيل المحدد موجودًا داخل هذا [Region](../../com.aspose.drawing/region).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| x | float | الإحداثي x للزاوية العلوية اليسرى للمستطيل للاختبار. |
| y | float | الإحداثي y للزاوية العلوية اليسرى للمستطيل للاختبار. |
| العرض | float | العرض للمستطيل للاختبار. |
| الارتفاع | float | الارتفاع للمستطيل للاختبار. |

**Returns:**
boolean - true عندما يكون أي جزء من المستطيل المحدد داخل كائن [Region](../../com.aspose.drawing/region) هذا؛ وإلا false.
### isVisible(RectangleF rect) {#isVisible-com.aspose.drawing.RectangleF-}
```
public boolean isVisible(RectangleF rect)
```


يفحص ما إذا كان أي جزء من بنية [RectangleF](../../com.aspose.drawing/rectanglef) المحددة موجودًا داخل هذا [Region](../../com.aspose.drawing/region).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | الـ[RectangleF](../../com.aspose.drawing/rectanglef) لاختبار. |

**Returns:**
boolean - true عندما يكون أي جزء من `rect` داخل هذه [Region](../../com.aspose.drawing/region)؛ وإلا false.
### isVisible(float x, float y, float width, float height, Graphics g) {#isVisible-float-float-float-float-com.aspose.drawing.Graphics-}
```
public boolean isVisible(float x, float y, float width, float height, Graphics g)
```


يفحص ما إذا كان أي جزء من المستطيل المحدد موجودًا داخل هذا [Region](../../com.aspose.drawing/region) عند رسمه باستخدام الـ[Graphics](../../com.aspose.drawing/graphics) المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| x | float | الإحداثي x للزاوية العلوية اليسرى للمستطيل للاختبار. |
| y | float | الإحداثي y للزاوية العلوية اليسرى للمستطيل للاختبار. |
| العرض | float | العرض للمستطيل للاختبار. |
| الارتفاع | float | الارتفاع للمستطيل للاختبار. |
| g | [Graphics](../../com.aspose.drawing/graphics) | [Graphics](../../com.aspose.drawing/graphics) تمثل سياق رسومي. |

**Returns:**
boolean - true عندما يكون أي جزء من المستطيل المحدد داخل هذه [Region](../../com.aspose.drawing/region)؛ وإلا false.
### isVisible(RectangleF rect, Graphics g) {#isVisible-com.aspose.drawing.RectangleF-com.aspose.drawing.Graphics-}
```
public boolean isVisible(RectangleF rect, Graphics g)
```


يفحص ما إذا كان أي جزء من بنية [RectangleF](../../com.aspose.drawing/rectanglef) المحددة موجودًا داخل هذا [Region](../../com.aspose.drawing/region) عند رسمه باستخدام الـ[Graphics](../../com.aspose.drawing/graphics) المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | الـ[RectangleF](../../com.aspose.drawing/rectanglef) لاختبار. |
| g | [Graphics](../../com.aspose.drawing/graphics) | [Graphics](../../com.aspose.drawing/graphics) تمثل سياق رسومي. |

**Returns:**
boolean - true عندما يكون `rect` داخل هذه [Region](../../com.aspose.drawing/region)؛ وإلا false.
### isVisible(int x, int y, Graphics g) {#isVisible-int-int-com.aspose.drawing.Graphics-}
```
public boolean isVisible(int x, int y, Graphics g)
```


يفحص ما إذا كانت النقطة المحددة موجودة داخل كائن [Region](../../com.aspose.drawing/region) عند رسمه باستخدام كائن الـ[Graphics](../../com.aspose.drawing/graphics) المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| x | int | الإحداثي x للنقطة المراد اختبارها. |
| y | int | الإحداثي الصادي للنقطة لاختبارها. |
| g | [Graphics](../../com.aspose.drawing/graphics) | [Graphics](../../com.aspose.drawing/graphics) تمثل سياق رسومي. |

**Returns:**
boolean - true عندما تكون النقطة المحددة داخل هذه [Region](../../com.aspose.drawing/region)؛ وإلا false.
### isVisible(Point point) {#isVisible-com.aspose.drawing.Point-}
```
public boolean isVisible(Point point)
```


يفحص ما إذا كانت بنية [Point](../../com.aspose.drawing/point) المحددة موجودة داخل هذا [Region](../../com.aspose.drawing/region).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| point | [Point](../../com.aspose.drawing/point) | الـ[Point](../../com.aspose.drawing/point) لاختبار. |

**Returns:**
boolean - true عندما تكون `point` داخل هذه [Region](../../com.aspose.drawing/region)؛ وإلا false.
### isVisible(Point point, Graphics g) {#isVisible-com.aspose.drawing.Point-com.aspose.drawing.Graphics-}
```
public boolean isVisible(Point point, Graphics g)
```


يفحص ما إذا كانت بنية [Point](../../com.aspose.drawing/point) المحددة موجودة داخل هذا [Region](../../com.aspose.drawing/region) عند رسمها باستخدام الـ[Graphics](../../com.aspose.drawing/graphics) المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| point | [Point](../../com.aspose.drawing/point) | الـ[Point](../../com.aspose.drawing/point) لاختبار. |
| g | [Graphics](../../com.aspose.drawing/graphics) | [Graphics](../../com.aspose.drawing/graphics) تمثل سياق رسومي. |

**Returns:**
boolean - true عندما تكون `point` داخل هذه [Region](../../com.aspose.drawing/region)؛ وإلا false.
### isVisible(int x, int y, int width, int height) {#isVisible-int-int-int-int-}
```
public boolean isVisible(int x, int y, int width, int height)
```


يفحص ما إذا كان أي جزء من المستطيل المحدد موجودًا داخل هذا [Region](../../com.aspose.drawing/region).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| x | int | الإحداثي x للزاوية العلوية اليسرى للمستطيل للاختبار. |
| y | int | الإحداثي y للزاوية العلوية اليسرى للمستطيل للاختبار. |
| العرض | int | العرض للمستطيل للاختبار. |
| الارتفاع | int | الارتفاع للمستطيل للاختبار. |

**Returns:**
boolean - true عندما يكون أي جزء من المستطيل المحدد داخل هذه [Region](../../com.aspose.drawing/region)؛ وإلا false.
### isVisible(Rectangle rect) {#isVisible-com.aspose.drawing.Rectangle-}
```
public boolean isVisible(Rectangle rect)
```


يفحص ما إذا كان أي جزء من بنية [Rectangle](../../com.aspose.drawing/rectangle) المحددة موجودًا داخل هذا [Region](../../com.aspose.drawing/region).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | الـ[Rectangle](../../com.aspose.drawing/rectangle) لاختبار. |

**Returns:**
boolean - تُعيد هذه الطريقة true عندما يكون أي جزء من `rect` داخل هذه [Region](../../com.aspose.drawing/region)؛ وإلا false.
### isVisible(int x, int y, int width, int height, Graphics g) {#isVisible-int-int-int-int-com.aspose.drawing.Graphics-}
```
public boolean isVisible(int x, int y, int width, int height, Graphics g)
```


يفحص ما إذا كان أي جزء من المستطيل المحدد موجودًا داخل هذا [Region](../../com.aspose.drawing/region) عند رسمه باستخدام الـ[Graphics](../../com.aspose.drawing/graphics) المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| x | int | الإحداثي x للزاوية العلوية اليسرى للمستطيل للاختبار. |
| y | int | الإحداثي y للزاوية العلوية اليسرى للمستطيل للاختبار. |
| العرض | int | العرض للمستطيل للاختبار. |
| الارتفاع | int | الارتفاع للمستطيل للاختبار. |
| g | [Graphics](../../com.aspose.drawing/graphics) | [Graphics](../../com.aspose.drawing/graphics) تمثل سياق رسومي. |

**Returns:**
boolean - true عندما يكون أي جزء من المستطيل المحدد داخل هذه [Region](../../com.aspose.drawing/region)؛ وإلا false.
### isVisible(Rectangle rect, Graphics g) {#isVisible-com.aspose.drawing.Rectangle-com.aspose.drawing.Graphics-}
```
public boolean isVisible(Rectangle rect, Graphics g)
```


يفحص ما إذا كان أي جزء من بنية [Rectangle](../../com.aspose.drawing/rectangle) المحددة موجودًا داخل هذا [Region](../../com.aspose.drawing/region) عند رسمه باستخدام الـ[Graphics](../../com.aspose.drawing/graphics) المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | الـ[Rectangle](../../com.aspose.drawing/rectangle) لاختبار. |
| g | [Graphics](../../com.aspose.drawing/graphics) | [Graphics](../../com.aspose.drawing/graphics) تمثل سياق رسومي. |

**Returns:**
boolean - true عندما يكون أي جزء من `rect` داخل هذه [Region](../../com.aspose.drawing/region)؛ وإلا false.
