---
title: LinearGradientBrush
second_title: مرجع API لـ Aspose.Drawing للـ Java
description: يغلف  مع تدرج خطي.
type: docs
weight: 31
url: /ar/java/com.aspose.drawing.drawing2d/lineargradientbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.drawing.Brush](../../com.aspose.drawing/brush)
```
public final class LinearGradientBrush extends Brush
```

يغلف [Brush](../../com.aspose.drawing/brush) مع تدرج خطي. لا يمكن توريث هذه الفئة.
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [LinearGradientBrush(PointF point1, PointF point2, Color color1, Color color2)](#LinearGradientBrush-com.aspose.drawing.PointF-com.aspose.drawing.PointF-com.aspose.drawing.Color-com.aspose.drawing.Color-) | ينشئ مثيلاً جديدًا من الفئة [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) مع النقاط والألوان المحددة. |
| [LinearGradientBrush(Point point1, Point point2, Color color1, Color color2)](#LinearGradientBrush-com.aspose.drawing.Point-com.aspose.drawing.Point-com.aspose.drawing.Color-com.aspose.drawing.Color-) | ينشئ مثيلاً جديدًا من الفئة [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) مع النقاط والألوان المحددة. |
| [LinearGradientBrush(RectangleF rect, Color color1, Color color2, int linearGradientMode)](#LinearGradientBrush-com.aspose.drawing.RectangleF-com.aspose.drawing.Color-com.aspose.drawing.Color-int-) | ينشئ مثيلاً جديدًا من الفئة [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) استنادًا إلى مستطيل، وألوان البداية والنهاية، ووضعية الاتجاه. |
| [LinearGradientBrush(Rectangle rect, Color color1, Color color2, int linearGradientMode)](#LinearGradientBrush-com.aspose.drawing.Rectangle-com.aspose.drawing.Color-com.aspose.drawing.Color-int-) | ينشئ مثيلاً جديدًا من الفئة [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) استنادًا إلى مستطيل، وألوان البداية والنهاية، والاتجاه. |
| [LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle)](#LinearGradientBrush-com.aspose.drawing.RectangleF-com.aspose.drawing.Color-com.aspose.drawing.Color-float-) | ينشئ مثيلاً جديدًا من الفئة [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) استنادًا إلى مستطيل، وألوان البداية والنهاية، وزاوية الاتجاه. |
| [LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle, boolean isAngleScaleable)](#LinearGradientBrush-com.aspose.drawing.RectangleF-com.aspose.drawing.Color-com.aspose.drawing.Color-float-boolean-) | ينشئ مثيلاً جديدًا من الفئة [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) استنادًا إلى مستطيل، وألوان البداية والنهاية، وزاوية الاتجاه. |
| [LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle)](#LinearGradientBrush-com.aspose.drawing.Rectangle-com.aspose.drawing.Color-com.aspose.drawing.Color-float-) | ينشئ مثيلاً جديدًا من الفئة [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) استنادًا إلى مستطيل، وألوان البداية والنهاية، وزاوية الاتجاه. |
| [LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle, boolean isAngleScaleable)](#LinearGradientBrush-com.aspose.drawing.Rectangle-com.aspose.drawing.Color-com.aspose.drawing.Color-float-boolean-) | ينشئ مثيلاً جديدًا من الفئة [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) استنادًا إلى مستطيل، وألوان البداية والنهاية، وزاوية الاتجاه. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getLinearColors()](#getLinearColors--) | يحصل أو يضبط ألوان البداية والنهاية للتدرج. |
| [setLinearColors(Color[] value)](#setLinearColors-com.aspose.drawing.Color---) | يحصل أو يضبط ألوان البداية والنهاية للتدرج. |
| [getRectangle()](#getRectangle--) | يحصل على منطقة مستطيلة تحدد نقاط البداية والنهاية للتدرج. |
| [getGammaCorrection()](#getGammaCorrection--) | يحصل أو يضبط قيمة تشير إلى ما إذا كان تصحيح غاما مفعلاً لهذا [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush). |
| [setGammaCorrection(boolean value)](#setGammaCorrection-boolean-) | يحصل أو يضبط قيمة تشير إلى ما إذا كان تصحيح غاما مفعلاً لهذا [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush). |
| [getBlend()](#getBlend--) | يحصل أو يضبط `Blend`([.getBlend](../../null/\#getBlend)/[.setBlend(Blend)](../../null/\#setBlend-Blend-)) الذي يحدد المواقع والعوامل التي تعرف انخفاضًا مخصصًا للتدرج. |
| [setBlend(Blend value)](#setBlend-com.aspose.drawing.drawing2d.Blend-) | يحصل أو يضبط `Blend`([.getBlend](../../null/\#getBlend)/[.setBlend(Blend)](../../null/\#setBlend-Blend-)) الذي يحدد المواقع والعوامل التي تعرف انخفاضًا مخصصًا للتدرج. |
| [getInterpolationColors()](#getInterpolationColors--) | يحصل أو يضبط [ColorBlend](../../com.aspose.drawing.drawing2d/colorblend) الذي يحدد تدرجًا خطيًا متعدد الألوان. |
| [setInterpolationColors(ColorBlend value)](#setInterpolationColors-com.aspose.drawing.drawing2d.ColorBlend-) | يحصل أو يضبط [ColorBlend](../../com.aspose.drawing.drawing2d/colorblend) الذي يحدد تدرجًا خطيًا متعدد الألوان. |
| [getWrapMode()](#getWrapMode--) | يحصل أو يضبط تعداد `WrapMode` الذي يشير إلى وضع الالتفاف لهذا [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush). |
| [setWrapMode(int value)](#setWrapMode-int-) | يحصل أو يضبط تعداد `WrapMode` الذي يشير إلى وضع الالتفاف لهذا [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush). |
| [getTransform()](#getTransform--) | يحصل أو يضبط نسخة من [Matrix](../../com.aspose.drawing.drawing2d/matrix) التي تحدد تحويلًا هندسيًا محليًا لهذا [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush). |
| [setTransform(Matrix value)](#setTransform-com.aspose.drawing.drawing2d.Matrix-) | يحصل أو يضبط نسخة من [Matrix](../../com.aspose.drawing.drawing2d/matrix) التي تحدد تحويلًا هندسيًا محليًا لهذا [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush). |
| [deepClone()](#deepClone--) | ينشئ نسخة مطابقة تمامًا من هذا [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush). |
| [setSigmaBellShape(float focus)](#setSigmaBellShape-float-) | ينشئ انخفاضًا للتدرج بناءً على منحنى على شكل جرس. |
| [setSigmaBellShape(float focus, float scale)](#setSigmaBellShape-float-float-) | ينشئ انخفاضًا للتدرج بناءً على منحنى على شكل جرس. |
| [setBlendTriangularShape(float focus)](#setBlendTriangularShape-float-) | ينشئ تدرجًا خطيًا بلون مركزي وانخفاضًا خطيًا إلى لون واحد في كلا الطرفين. |
| [setBlendTriangularShape(float focus, float scale)](#setBlendTriangularShape-float-float-) | ينشئ تدرجًا خطيًا بلون مركزي وانخفاضًا خطيًا إلى لون واحد في كلا الطرفين. |
| [resetTransform()](#resetTransform--) | يعيد تعيين الخاصية `LinearGradientBrush.Transform` إلى الهوية. |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-) | يضرب [Matrix](../../com.aspose.drawing.drawing2d/matrix) الذي يمثل التحويل الهندسي المحلي لهذا [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) بالمصفوفة [Matrix](../../com.aspose.drawing.drawing2d/matrix) المحددة عن طريق إلحاق المصفوفة [Matrix](../../com.aspose.drawing.drawing2d/matrix) المحددة في البداية. |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-int-) | يضرب [Matrix](../../com.aspose.drawing.drawing2d/matrix) الذي يمثل التحويل الهندسي المحلي لهذا [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) بالمصفوفة [Matrix](../../com.aspose.drawing.drawing2d/matrix) المحددة بالترتيب المحدد. |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | يترجم التحويل الهندسي المحلي بالأبعاد المحددة. |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | يترجم التحويل الهندسي المحلي بالأبعاد المحددة بالترتيب المحدد. |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | يقوم بتوسيع التحويل الهندسي المحلي بالمقادير المحددة. |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | يقوم بتوسيع التحويل الهندسي المحلي بالمقادير المحددة بالترتيب المحدد. |
| [rotateTransform(float angle)](#rotateTransform-float-) | يدور التحويل الهندسي المحلي بالمقدار المحدد. |
| [rotateTransform(float angle, int order)](#rotateTransform-float-int-) | يدور التحويل الهندسي المحلي بالمقدار المحدد بالترتيب المحدد. |
### LinearGradientBrush(PointF point1, PointF point2, Color color1, Color color2) {#LinearGradientBrush-com.aspose.drawing.PointF-com.aspose.drawing.PointF-com.aspose.drawing.Color-com.aspose.drawing.Color-}
```
public LinearGradientBrush(PointF point1, PointF point2, Color color1, Color color2)
```


ينشئ مثيلاً جديدًا من الفئة [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) مع النقاط والألوان المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| point1 | [PointF](../../com.aspose.drawing/pointf) | هيكلية [PointF](../../com.aspose.drawing/pointf) التي تمثل نقطة البداية للتدرج الخطي. |
| point2 | [PointF](../../com.aspose.drawing/pointf) | هيكلية [PointF](../../com.aspose.drawing/pointf) التي تمثل نقطة النهاية للتدرج الخطي. |
| color1 | [Color](../../com.aspose.drawing/color) | هيكلية [Color](../../com.aspose.drawing/color) التي تمثل اللون الابتدائي للتدرج الخطي. |
| color2 | [Color](../../com.aspose.drawing/color) | هيكلية [Color](../../com.aspose.drawing/color) التي تمثل اللون النهائي للتدرج الخطي. |

### LinearGradientBrush(Point point1, Point point2, Color color1, Color color2) {#LinearGradientBrush-com.aspose.drawing.Point-com.aspose.drawing.Point-com.aspose.drawing.Color-com.aspose.drawing.Color-}
```
public LinearGradientBrush(Point point1, Point point2, Color color1, Color color2)
```


ينشئ مثيلاً جديدًا من الفئة [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) مع النقاط والألوان المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.drawing/point) | هيكلية [Point](../../com.aspose.drawing/point) التي تمثل نقطة البداية للتدرج الخطي. |
| point2 | [Point](../../com.aspose.drawing/point) | هيكلية [Point](../../com.aspose.drawing/point) التي تمثل نقطة النهاية للتدرج الخطي. |
| color1 | [Color](../../com.aspose.drawing/color) | هيكلية [Color](../../com.aspose.drawing/color) التي تمثل اللون الابتدائي للتدرج الخطي. |
| color2 | [Color](../../com.aspose.drawing/color) | هيكلية [Color](../../com.aspose.drawing/color) التي تمثل اللون النهائي للتدرج الخطي. |

### LinearGradientBrush(RectangleF rect, Color color1, Color color2, int linearGradientMode) {#LinearGradientBrush-com.aspose.drawing.RectangleF-com.aspose.drawing.Color-com.aspose.drawing.Color-int-}
```
public LinearGradientBrush(RectangleF rect, Color color1, Color color2, int linearGradientMode)
```


ينشئ مثيلاً جديدًا من الفئة [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) استنادًا إلى مستطيل، وألوان البداية والنهاية، ووضعية الاتجاه.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | هيكلية [RectangleF](../../com.aspose.drawing/rectanglef) التي تحدد حدود التدرج الخطي. |
| color1 | [Color](../../com.aspose.drawing/color) | هيكلية [Color](../../com.aspose.drawing/color) التي تمثل اللون الابتدائي للتدرج. |
| color2 | [Color](../../com.aspose.drawing/color) | هيكل [Color](../../com.aspose.drawing/color) يمثل اللون النهائي للتدرج. |
| linearGradientMode | int | عنصر تعداد [LinearGradientMode](../../com.aspose.drawing.drawing2d/lineargradientmode) يحدد اتجاه التدرج. يحدد الاتجاه نقاط البداية والنهاية للتدرج. على سبيل المثال، LinearGradientMode.ForwardDiagonal يحدد أن نقطة البداية هي الزاوية العلوية اليسرى للمستطيل ونقطة النهاية هي الزاوية السفلية اليمنى للمستطيل. |

### LinearGradientBrush(Rectangle rect, Color color1, Color color2, int linearGradientMode) {#LinearGradientBrush-com.aspose.drawing.Rectangle-com.aspose.drawing.Color-com.aspose.drawing.Color-int-}
```
public LinearGradientBrush(Rectangle rect, Color color1, Color color2, int linearGradientMode)
```


ينشئ مثيلاً جديدًا من الفئة [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) استنادًا إلى مستطيل، وألوان البداية والنهاية، والاتجاه.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | هيكل `Rectangle`([.getRectangle](../../null/\#getRectangle)) يحدد حدود التدرج الخطي. |
| color1 | [Color](../../com.aspose.drawing/color) | هيكلية [Color](../../com.aspose.drawing/color) التي تمثل اللون الابتدائي للتدرج. |
| color2 | [Color](../../com.aspose.drawing/color) | هيكل [Color](../../com.aspose.drawing/color) يمثل اللون النهائي للتدرج. |
| linearGradientMode | int | عنصر تعداد [LinearGradientMode](../../com.aspose.drawing.drawing2d/lineargradientmode) يحدد اتجاه التدرج. يحدد الاتجاه نقاط البداية والنهاية للتدرج. على سبيل المثال، LinearGradientMode.ForwardDiagonal يحدد أن نقطة البداية هي الزاوية العلوية اليسرى للمستطيل ونقطة النهاية هي الزاوية السفلية اليمنى للمستطيل. |

### LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle) {#LinearGradientBrush-com.aspose.drawing.RectangleF-com.aspose.drawing.Color-com.aspose.drawing.Color-float-}
```
public LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle)
```


ينشئ مثيلاً جديدًا من الفئة [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) استنادًا إلى مستطيل، وألوان البداية والنهاية، وزاوية الاتجاه.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | هيكلية [RectangleF](../../com.aspose.drawing/rectanglef) التي تحدد حدود التدرج الخطي. |
| color1 | [Color](../../com.aspose.drawing/color) | هيكلية [Color](../../com.aspose.drawing/color) التي تمثل اللون الابتدائي للتدرج. |
| color2 | [Color](../../com.aspose.drawing/color) | هيكل [Color](../../com.aspose.drawing/color) يمثل اللون النهائي للتدرج. |
| زاوية | float | الزاوية، مقاسة بالدرجات في اتجاه عقارب الساعة من المحور السيني، لخط اتجاه التدرج. |

### LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle, boolean isAngleScaleable) {#LinearGradientBrush-com.aspose.drawing.RectangleF-com.aspose.drawing.Color-com.aspose.drawing.Color-float-boolean-}
```
public LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle, boolean isAngleScaleable)
```


ينشئ مثيلاً جديدًا من الفئة [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) استنادًا إلى مستطيل، وألوان البداية والنهاية، وزاوية الاتجاه.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | هيكلية [RectangleF](../../com.aspose.drawing/rectanglef) التي تحدد حدود التدرج الخطي. |
| color1 | [Color](../../com.aspose.drawing/color) | هيكلية [Color](../../com.aspose.drawing/color) التي تمثل اللون الابتدائي للتدرج. |
| color2 | [Color](../../com.aspose.drawing/color) | هيكل [Color](../../com.aspose.drawing/color) يمثل اللون النهائي للتدرج. |
| زاوية | float | الزاوية، مقاسة بالدرجات في اتجاه عقارب الساعة من المحور السيني، لخط اتجاه التدرج. |
| isAngleScaleable | boolean | عيّنها إلى true لتحديد أن الزاوية تتأثر بالتحويل المرتبط بـ [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush)؛ وإلا فاجعلها false. |

### LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle) {#LinearGradientBrush-com.aspose.drawing.Rectangle-com.aspose.drawing.Color-com.aspose.drawing.Color-float-}
```
public LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle)
```


ينشئ مثيلاً جديدًا من الفئة [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) استنادًا إلى مستطيل، وألوان البداية والنهاية، وزاوية الاتجاه.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | هيكل `Rectangle`([.getRectangle](../../null/\#getRectangle)) يحدد حدود التدرج الخطي. |
| color1 | [Color](../../com.aspose.drawing/color) | هيكلية [Color](../../com.aspose.drawing/color) التي تمثل اللون الابتدائي للتدرج. |
| color2 | [Color](../../com.aspose.drawing/color) | هيكل [Color](../../com.aspose.drawing/color) يمثل اللون النهائي للتدرج. |
| زاوية | float | الزاوية، مقاسة بالدرجات في اتجاه عقارب الساعة من المحور السيني، لخط اتجاه التدرج. |

### LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle, boolean isAngleScaleable) {#LinearGradientBrush-com.aspose.drawing.Rectangle-com.aspose.drawing.Color-com.aspose.drawing.Color-float-boolean-}
```
public LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle, boolean isAngleScaleable)
```


ينشئ مثيلاً جديدًا من الفئة [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) استنادًا إلى مستطيل، وألوان البداية والنهاية، وزاوية الاتجاه.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | هيكل `Rectangle`([.getRectangle](../../null/\#getRectangle)) يحدد حدود التدرج الخطي. |
| color1 | [Color](../../com.aspose.drawing/color) | هيكلية [Color](../../com.aspose.drawing/color) التي تمثل اللون الابتدائي للتدرج. |
| color2 | [Color](../../com.aspose.drawing/color) | هيكل [Color](../../com.aspose.drawing/color) يمثل اللون النهائي للتدرج. |
| زاوية | float | الزاوية، مقاسة بالدرجات في اتجاه عقارب الساعة من المحور السيني، لخط اتجاه التدرج. |
| isAngleScaleable | boolean | عيّنها إلى true لتحديد أن الزاوية تتأثر بالتحويل المرتبط بـ [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush)؛ وإلا فاجعلها false. |

### getLinearColors() {#getLinearColors--}
```
public Color[] getLinearColors()
```


يحصل أو يضبط ألوان البداية والنهاية للتدرج.

**Returns:**
com.aspose.drawing.Color[]
### setLinearColors(Color[] value) {#setLinearColors-com.aspose.drawing.Color---}
```
public void setLinearColors(Color[] value)
```


يحصل أو يضبط ألوان البداية والنهاية للتدرج.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Color\[\]](../../com.aspose.drawing/color) |  |

### getRectangle() {#getRectangle--}
```
public RectangleF getRectangle()
```


يحصل على منطقة مستطيلة تحدد نقاط البداية والنهاية للتدرج.

**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef)
### getGammaCorrection() {#getGammaCorrection--}
```
public boolean getGammaCorrection()
```


يحصل أو يضبط قيمة تشير إلى ما إذا كان تصحيح غاما مفعلاً لهذا [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush).

**Returns:**
boolean
### setGammaCorrection(boolean value) {#setGammaCorrection-boolean-}
```
public void setGammaCorrection(boolean value)
```


يحصل أو يضبط قيمة تشير إلى ما إذا كان تصحيح غاما مفعلاً لهذا [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getBlend() {#getBlend--}
```
public Blend getBlend()
```


يحصل أو يضبط `Blend`([.getBlend](../../null/\#getBlend)/[.setBlend(Blend)](../../null/\#setBlend-Blend-)) الذي يحدد المواقع والعوامل التي تعرف انخفاضًا مخصصًا للتدرج.

**Returns:**
[Blend](../../com.aspose.drawing.drawing2d/blend)
### setBlend(Blend value) {#setBlend-com.aspose.drawing.drawing2d.Blend-}
```
public void setBlend(Blend value)
```


يحصل أو يضبط `Blend`([.getBlend](../../null/\#getBlend)/[.setBlend(Blend)](../../null/\#setBlend-Blend-)) الذي يحدد المواقع والعوامل التي تعرف انخفاضًا مخصصًا للتدرج.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Blend](../../com.aspose.drawing.drawing2d/blend) |  |

### getInterpolationColors() {#getInterpolationColors--}
```
public ColorBlend getInterpolationColors()
```


يحصل أو يضبط [ColorBlend](../../com.aspose.drawing.drawing2d/colorblend) الذي يحدد تدرجًا خطيًا متعدد الألوان.

**Returns:**
[ColorBlend](../../com.aspose.drawing.drawing2d/colorblend)
### setInterpolationColors(ColorBlend value) {#setInterpolationColors-com.aspose.drawing.drawing2d.ColorBlend-}
```
public void setInterpolationColors(ColorBlend value)
```


يحصل أو يضبط [ColorBlend](../../com.aspose.drawing.drawing2d/colorblend) الذي يحدد تدرجًا خطيًا متعدد الألوان.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [ColorBlend](../../com.aspose.drawing.drawing2d/colorblend) |  |

### getWrapMode() {#getWrapMode--}
```
public int getWrapMode()
```


يحصل أو يضبط تعداد `WrapMode` الذي يشير إلى وضع الالتفاف لهذا [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush).

**Returns:**
int
### setWrapMode(int value) {#setWrapMode-int-}
```
public void setWrapMode(int value)
```


يحصل أو يضبط تعداد `WrapMode` الذي يشير إلى وضع الالتفاف لهذا [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getTransform() {#getTransform--}
```
public Matrix getTransform()
```


يحصل أو يضبط نسخة من [Matrix](../../com.aspose.drawing.drawing2d/matrix) التي تحدد تحويلًا هندسيًا محليًا لهذا [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush).

**Returns:**
[Matrix](../../com.aspose.drawing.drawing2d/matrix)
### setTransform(Matrix value) {#setTransform-com.aspose.drawing.drawing2d.Matrix-}
```
public void setTransform(Matrix value)
```


يحصل أو يضبط نسخة من [Matrix](../../com.aspose.drawing.drawing2d/matrix) التي تحدد تحويلًا هندسيًا محليًا لهذا [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.drawing.drawing2d/matrix) |  |

### deepClone() {#deepClone--}
```
public Object deepClone()
```


ينشئ نسخة مطابقة تمامًا من هذا [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush).

**Returns:**
java.lang.Object - الـ [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) الذي تُنشئه هذه الطريقة، مُحوَّل إلى كائن.
### setSigmaBellShape(float focus) {#setSigmaBellShape-float-}
```
public void setSigmaBellShape(float focus)
```


ينشئ انخفاضًا للتدرج بناءً على منحنى على شكل جرس.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| focus | float | قيمة تتراوح بين 0 و 1 تحدد مركز التدرج (النقطة التي يختلط فيها اللونان الابتدائي والنهائي بالتساوي). |

### setSigmaBellShape(float focus, float scale) {#setSigmaBellShape-float-float-}
```
public void setSigmaBellShape(float focus, float scale)
```


ينشئ انخفاضًا للتدرج بناءً على منحنى على شكل جرس.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| focus | float | قيمة تتراوح بين 0 و 1 تحدد مركز التدرج (النقطة التي يتكون فيها التدرج من اللون النهائي فقط). |
| مقياس | float | قيمة تتراوح بين 0 و 1 تحدد مدى سرعة انخفاض الألوان من `focus`. |

### setBlendTriangularShape(float focus) {#setBlendTriangularShape-float-}
```
public void setBlendTriangularShape(float focus)
```


ينشئ تدرجًا خطيًا بلون مركزي وانخفاضًا خطيًا إلى لون واحد في كلا الطرفين.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| focus | float | قيمة تتراوح بين 0 و 1 تحدد مركز التدرج (النقطة التي يتكون فيها التدرج من اللون النهائي فقط). |

### setBlendTriangularShape(float focus, float scale) {#setBlendTriangularShape-float-float-}
```
public void setBlendTriangularShape(float focus, float scale)
```


ينشئ تدرجًا خطيًا بلون مركزي وانخفاضًا خطيًا إلى لون واحد في كلا الطرفين.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| focus | float | قيمة تتراوح بين 0 و 1 تحدد مركز التدرج (النقطة التي يتكون فيها التدرج من اللون النهائي فقط). |
| مقياس | float | قيمة تتراوح بين 0 و 1 تحدد مدى سرعة انخفاض الألوان من اللون الابتدائي إلى `focus` (اللون النهائي). |

### resetTransform() {#resetTransform--}
```
public void resetTransform()
```


يعيد تعيين الخاصية `LinearGradientBrush.Transform` إلى الهوية.

### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-}
```
public void multiplyTransform(Matrix matrix)
```


يضرب [Matrix](../../com.aspose.drawing.drawing2d/matrix) الذي يمثل التحويل الهندسي المحلي لهذا [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) بالمصفوفة [Matrix](../../com.aspose.drawing.drawing2d/matrix) المحددة عن طريق إلحاق المصفوفة [Matrix](../../com.aspose.drawing.drawing2d/matrix) المحددة في البداية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | الـ [Matrix](../../com.aspose.drawing.drawing2d/matrix) التي يُضرب بها التحويل الهندسي. |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-int-}
```
public void multiplyTransform(Matrix matrix, int order)
```


يضرب [Matrix](../../com.aspose.drawing.drawing2d/matrix) الذي يمثل التحويل الهندسي المحلي لهذا [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) بالمصفوفة [Matrix](../../com.aspose.drawing.drawing2d/matrix) المحددة بالترتيب المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | الـ [Matrix](../../com.aspose.drawing.drawing2d/matrix) التي يُضرب بها التحويل الهندسي. |
| order | int | ـ [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder) يحدد ترتيب ضرب المصفوفتين. |

### translateTransform(float dx, float dy) {#translateTransform-float-float-}
```
public void translateTransform(float dx, float dy)
```


يُترجم التحويل الهندسي المحلي بالأبعاد المحددة. تُضيف هذه الطريقة الترجمة إلى التحويل في البداية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| dx | float | قيمة الترجمة في المحور x. |
| dy | float | قيمة الترجمة في المحور y. |

### translateTransform(float dx, float dy, int order) {#translateTransform-float-float-int-}
```
public void translateTransform(float dx, float dy, int order)
```


يترجم التحويل الهندسي المحلي بالأبعاد المحددة بالترتيب المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| dx | float | قيمة الترجمة في المحور x. |
| dy | float | قيمة الترجمة في المحور y. |
| ترتيب | int | الترتيب (إضافة في البداية أو في النهاية) الذي يُطبق فيه الترجمة. |

### scaleTransform(float sx, float sy) {#scaleTransform-float-float-}
```
public void scaleTransform(float sx, float sy)
```


يقوم بتكبير التحويل الهندسي المحلي بالمقادير المحددة. تقوم هذه الطريقة بإلحاق مصفوفة التكبير في بداية التحويل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| sx | float | المقدار الذي يتم به تكبير التحويل في اتجاه المحور x. |
| sy | float | المقدار الذي يتم به تكبير التحويل في اتجاه المحور y. |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public void scaleTransform(float sx, float sy, int order)
```


يقوم بتوسيع التحويل الهندسي المحلي بالمقادير المحددة بالترتيب المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| sx | float | المقدار الذي يتم به تكبير التحويل في اتجاه المحور x. |
| sy | float | المقدار الذي يتم به تكبير التحويل في اتجاه المحور y. |
| order | int | [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder) الذي يحدد ما إذا كان سيتم إلحاق أو إلحاق مسبق لمصفوفة التكبير. |

### rotateTransform(float angle) {#rotateTransform-float-}
```
public void rotateTransform(float angle)
```


يدور التحويل الهندسي المحلي بالمقدار المحدد. تقوم هذه الطريقة بإلحاق مصفوفة الدوران في بداية التحويل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| زاوية | float | زاوية الدوران. |

### rotateTransform(float angle, int order) {#rotateTransform-float-int-}
```
public void rotateTransform(float angle, int order)
```


يدور التحويل الهندسي المحلي بالمقدار المحدد بالترتيب المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| زاوية | float | زاوية الدوران. |
| order | int | [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder) الذي يحدد ما إذا كان سيتم إلحاق أو إلحاق مسبق لمصفوفة الدوران. |

