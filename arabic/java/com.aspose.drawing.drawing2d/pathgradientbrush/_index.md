---
title: PathGradientBrush
second_title: مرجع API لـ Aspose.Drawing للـ Java
description: يغلف كائنًا يملأ داخل كائن بتدرج لوني.
type: docs
weight: 36
url: /ar/java/com.aspose.drawing.drawing2d/pathgradientbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.drawing.Brush](../../com.aspose.drawing/brush)
```
public final class PathGradientBrush extends Brush
```

يغلف كائن [Brush](../../com.aspose.drawing/brush) يملأ داخل كائن [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) بتدرج لوني. لا يمكن توريث هذه الفئة.
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [PathGradientBrush(PointF[] points)](#PathGradientBrush-com.aspose.drawing.PointF---) | ينشئ مثيلًا جديدًا للفئة [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) بالنقاط المحددة. |
| [PathGradientBrush(PointF[] points, int wrapMode)](#PathGradientBrush-com.aspose.drawing.PointF---int-) | ينشئ مثيلًا جديدًا للفئة [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) بالنقاط المحددة ووضع الالتفاف. |
| [PathGradientBrush(Point[] points)](#PathGradientBrush-com.aspose.drawing.Point---) | ينشئ مثيلًا جديدًا للفئة [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) بالنقاط المحددة. |
| [PathGradientBrush(Point[] points, int wrapMode)](#PathGradientBrush-com.aspose.drawing.Point---int-) | ينشئ مثيلًا جديدًا للفئة [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) بالنقاط المحددة ووضع الالتفاف. |
| [PathGradientBrush(GraphicsPath path)](#PathGradientBrush-com.aspose.drawing.drawing2d.GraphicsPath-) | ينشئ مثيلًا جديدًا للفئة [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) بالمسار المحدد. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getCenterColor()](#getCenterColor--) | يحصل أو يضبط اللون في مركز تدرج المسار. |
| [setCenterColor(Color value)](#setCenterColor-com.aspose.drawing.Color-) | يحصل أو يضبط اللون في مركز تدرج المسار. |
| [getSurroundColors()](#getSurroundColors--) | يحصل أو يضبط مصفوفة من الألوان التي تتطابق مع النقاط في المسار الذي يملأه هذا [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush). |
| [setSurroundColors(Color[] value)](#setSurroundColors-com.aspose.drawing.Color---) | يحصل أو يضبط مصفوفة من الألوان التي تتطابق مع النقاط في المسار الذي يملأه هذا [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush). |
| [getCenterPoint()](#getCenterPoint--) | يحصل أو يضبط نقطة المركز لتدرج المسار. |
| [setCenterPoint(PointF value)](#setCenterPoint-com.aspose.drawing.PointF-) | يحصل أو يضبط نقطة المركز لتدرج المسار. |
| [getRectangle()](#getRectangle--) | يحصل على مستطيل الحد لهذا [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush). |
| [getBlend()](#getBlend--) | يحصل أو يضبط `Blend`([.getBlend](../../null/\#getBlend)/[.setBlend(Blend)](../../null/\#setBlend-Blend-)) الذي يحدد المواقع والعوامل التي تعرف انخفاضًا مخصصًا للتدرج. |
| [setBlend(Blend value)](#setBlend-com.aspose.drawing.drawing2d.Blend-) | يحصل أو يضبط `Blend`([.getBlend](../../null/\#getBlend)/[.setBlend(Blend)](../../null/\#setBlend-Blend-)) الذي يحدد المواقع والعوامل التي تعرف انخفاضًا مخصصًا للتدرج. |
| [getInterpolationColors()](#getInterpolationColors--) | يحصل أو يضبط [ColorBlend](../../com.aspose.drawing.drawing2d/colorblend) الذي يحدد تدرجًا خطيًا متعدد الألوان. |
| [setInterpolationColors(ColorBlend value)](#setInterpolationColors-com.aspose.drawing.drawing2d.ColorBlend-) | يحصل أو يضبط [ColorBlend](../../com.aspose.drawing.drawing2d/colorblend) الذي يحدد تدرجًا خطيًا متعدد الألوان. |
| [getTransform()](#getTransform--) | يحصل أو يضبط نسخة من الـ[Matrix](../../com.aspose.drawing.drawing2d/matrix) التي تحدد تحويلًا هندسيًا محليًا لهذا [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush). |
| [setTransform(Matrix value)](#setTransform-com.aspose.drawing.drawing2d.Matrix-) | يحصل أو يضبط نسخة من الـ[Matrix](../../com.aspose.drawing.drawing2d/matrix) التي تحدد تحويلًا هندسيًا محليًا لهذا [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush). |
| [getFocusScales()](#getFocusScales--) | يحصل أو يضبط نقطة التركيز لتناقص التدرج. |
| [setFocusScales(PointF value)](#setFocusScales-com.aspose.drawing.PointF-) | يحصل أو يضبط نقطة التركيز لتناقص التدرج. |
| [getWrapMode()](#getWrapMode--) | يحصل أو يضبط `WrapMode`([.getWrapMode](../../null/\#getWrapMode)/[.setWrapMode(int)](../../null/\#setWrapMode-int-)) الذي يحدد وضع الالتفاف لهذا [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush). |
| [setWrapMode(int value)](#setWrapMode-int-) | يحصل أو يضبط `WrapMode`([.getWrapMode](../../null/\#getWrapMode)/[.setWrapMode(int)](../../null/\#setWrapMode-int-)) الذي يحدد وضع الالتفاف لهذا [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush). |
| [deepClone()](#deepClone--) | ينشئ نسخة مطابقة تمامًا من هذا [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush). |
| [setSigmaBellShape(float focus)](#setSigmaBellShape-float-) | ينشئ فرشاة تدرج تغير اللون بدءًا من مركز المسار إلى حدوده الخارجية. |
| [setSigmaBellShape(float focus, float scale)](#setSigmaBellShape-float-float-) | ينشئ فرشاة تدرج تغير اللون بدءًا من مركز المسار إلى حدوده الخارجية. |
| [setBlendTriangularShape(float focus)](#setBlendTriangularShape-float-) | ينشئ تدرجًا بلون مركزي وتناقصًا خطيًا إلى لون محيط واحد. |
| [setBlendTriangularShape(float focus, float scale)](#setBlendTriangularShape-float-float-) | ينشئ تدرجًا لونيًا بلون مركزي وتناقصًا خطيًا إلى كل لون محيط. |
| [resetTransform()](#resetTransform--) | يعيد ضبط الخاصية `PathGradientBrush.Transform` إلى الهوية. |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-) | يحدّث مصفوفة التحويل للفرشاة بمنتج مصفوفة التحويل للفرشاة مضروبًا في مصفوفة أخرى. |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-int-) | يحدّث مصفوفة التحويل للفرشاة بمنتج مصفوفة التحويل للفرشاة مضروبًا في مصفوفة أخرى. |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | يطبق الإزاحة المحددة على التحويل الهندسي المحلي. |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | يطبق الإزاحة المحددة على التحويل الهندسي المحلي بالترتيب المحدد. |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | يقوم بتوسيع التحويل الهندسي المحلي بالمقادير المحددة. |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | يقوم بتوسيع التحويل الهندسي المحلي بالمقادير المحددة بالترتيب المحدد. |
| [rotateTransform(float angle)](#rotateTransform-float-) | يدور التحويل الهندسي المحلي بالمقدار المحدد. |
| [rotateTransform(float angle, int order)](#rotateTransform-float-int-) | يدور التحويل الهندسي المحلي بالمقدار المحدد بالترتيب المحدد. |
### PathGradientBrush(PointF[] points) {#PathGradientBrush-com.aspose.drawing.PointF---}
```
public PathGradientBrush(PointF[] points)
```


ينشئ مثيلًا جديدًا للفئة [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) بالنقاط المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.drawing/pointf) | مصفوفة من هياكل [PointF](../../com.aspose.drawing/pointf) التي تمثل النقاط التي تُكوّن رؤوس المسار. |

### PathGradientBrush(PointF[] points, int wrapMode) {#PathGradientBrush-com.aspose.drawing.PointF---int-}
```
public PathGradientBrush(PointF[] points, int wrapMode)
```


ينشئ مثيلًا جديدًا للفئة [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) بالنقاط المحددة ووضع الالتفاف.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.drawing/pointf) | مصفوفة من هياكل [PointF](../../com.aspose.drawing/pointf) التي تمثل النقاط التي تُكوّن رؤوس المسار. |
| wrapMode | int | `WrapMode`([.getWrapMode](../../null/\#getWrapMode)/[.setWrapMode(int)](../../null/\#setWrapMode-int-)) التي تحدد كيفية تجانب التعبئات المرسومة بهذه [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush). |

### PathGradientBrush(Point[] points) {#PathGradientBrush-com.aspose.drawing.Point---}
```
public PathGradientBrush(Point[] points)
```


ينشئ مثيلًا جديدًا للفئة [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) بالنقاط المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| points | [Point\[\]](../../com.aspose.drawing/point) | مصفوفة من هياكل [Point](../../com.aspose.drawing/point) التي تمثل النقاط التي تُكوّن رؤوس المسار. |

### PathGradientBrush(Point[] points, int wrapMode) {#PathGradientBrush-com.aspose.drawing.Point---int-}
```
public PathGradientBrush(Point[] points, int wrapMode)
```


ينشئ مثيلًا جديدًا للفئة [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) بالنقاط المحددة ووضع الالتفاف.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| points | [Point\[\]](../../com.aspose.drawing/point) | مصفوفة من هياكل [Point](../../com.aspose.drawing/point) التي تمثل النقاط التي تُكوّن رؤوس المسار. |
| wrapMode | int | `WrapMode`([.getWrapMode](../../null/\#getWrapMode)/[.setWrapMode(int)](../../null/\#setWrapMode-int-)) التي تحدد كيفية تجانب التعبئات المرسومة بهذه [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush). |

### PathGradientBrush(GraphicsPath path) {#PathGradientBrush-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public PathGradientBrush(GraphicsPath path)
```


ينشئ مثيلًا جديدًا للفئة [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) بالمسار المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) الذي يحدد المنطقة المملوءة بهذه [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush). |

### getCenterColor() {#getCenterColor--}
```
public Color getCenterColor()
```


يحصل أو يضبط اللون في مركز تدرج المسار.

**Returns:**
[Color](../../com.aspose.drawing/color)
### setCenterColor(Color value) {#setCenterColor-com.aspose.drawing.Color-}
```
public void setCenterColor(Color value)
```


يحصل أو يضبط اللون في مركز تدرج المسار.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Color](../../com.aspose.drawing/color) |  |

### getSurroundColors() {#getSurroundColors--}
```
public Color[] getSurroundColors()
```


يحصل أو يضبط مصفوفة من الألوان التي تتطابق مع النقاط في المسار الذي يملأه هذا [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush).

**Returns:**
com.aspose.drawing.Color[]
### setSurroundColors(Color[] value) {#setSurroundColors-com.aspose.drawing.Color---}
```
public void setSurroundColors(Color[] value)
```


يحصل أو يضبط مصفوفة من الألوان التي تتطابق مع النقاط في المسار الذي يملأه هذا [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Color\[\]](../../com.aspose.drawing/color) |  |

### getCenterPoint() {#getCenterPoint--}
```
public PointF getCenterPoint()
```


يحصل أو يضبط نقطة المركز لتدرج المسار.

**Returns:**
[PointF](../../com.aspose.drawing/pointf)
### setCenterPoint(PointF value) {#setCenterPoint-com.aspose.drawing.PointF-}
```
public void setCenterPoint(PointF value)
```


يحصل أو يضبط نقطة المركز لتدرج المسار.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [PointF](../../com.aspose.drawing/pointf) |  |

### getRectangle() {#getRectangle--}
```
public RectangleF getRectangle()
```


يحصل على مستطيل الحد لهذا [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush).

**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef)
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

### getTransform() {#getTransform--}
```
public Matrix getTransform()
```


يحصل أو يضبط نسخة من الـ[Matrix](../../com.aspose.drawing.drawing2d/matrix) التي تحدد تحويلًا هندسيًا محليًا لهذا [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush).

**Returns:**
[Matrix](../../com.aspose.drawing.drawing2d/matrix)
### setTransform(Matrix value) {#setTransform-com.aspose.drawing.drawing2d.Matrix-}
```
public void setTransform(Matrix value)
```


يحصل أو يضبط نسخة من الـ[Matrix](../../com.aspose.drawing.drawing2d/matrix) التي تحدد تحويلًا هندسيًا محليًا لهذا [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.drawing.drawing2d/matrix) |  |

### getFocusScales() {#getFocusScales--}
```
public PointF getFocusScales()
```


يحصل أو يضبط نقطة التركيز لتناقص التدرج.

**Returns:**
[PointF](../../com.aspose.drawing/pointf)
### setFocusScales(PointF value) {#setFocusScales-com.aspose.drawing.PointF-}
```
public void setFocusScales(PointF value)
```


يحصل أو يضبط نقطة التركيز لتناقص التدرج.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [PointF](../../com.aspose.drawing/pointf) |  |

### getWrapMode() {#getWrapMode--}
```
public int getWrapMode()
```


يحصل أو يضبط `WrapMode`([.getWrapMode](../../null/\#getWrapMode)/[.setWrapMode(int)](../../null/\#setWrapMode-int-)) الذي يحدد وضع الالتفاف لهذا [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush).

**Returns:**
int
### setWrapMode(int value) {#setWrapMode-int-}
```
public void setWrapMode(int value)
```


يحصل أو يضبط `WrapMode`([.getWrapMode](../../null/\#getWrapMode)/[.setWrapMode(int)](../../null/\#setWrapMode-int-)) الذي يحدد وضع الالتفاف لهذا [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### deepClone() {#deepClone--}
```
public Object deepClone()
```


ينشئ نسخة مطابقة تمامًا من هذا [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush).

**Returns:**
java.lang.Object - الـ [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) الذي تُنشئه هذه الطريقة، محوَّل إلى كائن.
### setSigmaBellShape(float focus) {#setSigmaBellShape-float-}
```
public void setSigmaBellShape(float focus)
```


ينشئ فرشاة تدرج لوني تغير اللون بدءًا من مركز المسار إلى حدود المسار. الانتقال من لون إلى آخر يعتمد على منحنى على شكل جرس.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| focus | float | قيمة تتراوح بين 0 و 1 تحدد الموضع، على أي شعاع من مركز المسار إلى حدوده، حيث يكون لون المركز بأعلى شدة. القيمة 1 (الافتراضية) تضع أعلى شدة في مركز المسار. |

### setSigmaBellShape(float focus, float scale) {#setSigmaBellShape-float-float-}
```
public void setSigmaBellShape(float focus, float scale)
```


ينشئ فرشاة تدرج لوني تغير اللون بدءًا من مركز المسار إلى حدود المسار. الانتقال من لون إلى آخر يعتمد على منحنى على شكل جرس.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| focus | float | قيمة تتراوح بين 0 و 1 تحدد الموضع، على أي شعاع من مركز المسار إلى حدوده، حيث يكون لون المركز بأعلى شدة. القيمة 1 (الافتراضية) تضع أعلى شدة في مركز المسار. |
| مقياس | float | قيمة تتراوح بين 0 و 1 تحدد أقصى شدة للون المركز الذي يُدمج مع لون الحد. القيمة 1 تُعطي أعلى شدة ممكنة للون المركز، وهي القيمة الافتراضية. |

### setBlendTriangularShape(float focus) {#setBlendTriangularShape-float-}
```
public void setBlendTriangularShape(float focus)
```


ينشئ تدرجًا بلون مركزي وتناقصًا خطيًا إلى لون محيط واحد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| focus | float | قيمة تتراوح بين 0 و 1 تحدد الموضع، على أي شعاع من مركز المسار إلى حدوده، حيث يكون لون المركز بأعلى شدة. القيمة 1 (الافتراضية) تضع أعلى شدة في مركز المسار. |

### setBlendTriangularShape(float focus, float scale) {#setBlendTriangularShape-float-float-}
```
public void setBlendTriangularShape(float focus, float scale)
```


ينشئ تدرجًا لونيًا بلون مركزي وتناقصًا خطيًا إلى كل لون محيط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| focus | float | قيمة تتراوح بين 0 و 1 تحدد الموضع، على أي شعاع من مركز المسار إلى حدوده، حيث يكون لون المركز بأعلى شدة. القيمة 1 (الافتراضية) تضع أعلى شدة في مركز المسار. |
| مقياس | float | قيمة تتراوح بين 0 و 1 تحدد أقصى شدة للون المركز الذي يُدمج مع لون الحد. القيمة 1 تُعطي أعلى شدة ممكنة للون المركز، وهي القيمة الافتراضية. |

### resetTransform() {#resetTransform--}
```
public void resetTransform()
```


يعيد ضبط الخاصية `PathGradientBrush.Transform` إلى الهوية.

### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-}
```
public void multiplyTransform(Matrix matrix)
```


يحدّث مصفوفة التحويل للفرشاة بمنتج مصفوفة التحويل للفرشاة مضروبًا في مصفوفة أخرى.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | [Matrix](../../com.aspose.drawing.drawing2d/matrix) التي ستُضرب في مصفوفة التحويل الحالية للفرشاة. |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-int-}
```
public void multiplyTransform(Matrix matrix, int order)
```


يحدّث مصفوفة التحويل للفرشاة بمنتج مصفوفة التحويل للفرشاة مضروبًا في مصفوفة أخرى.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | [Matrix](../../com.aspose.drawing.drawing2d/matrix) التي ستُضرب في مصفوفة التحويل الحالية للفرشاة. |
| order | int | ـ [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder) يحدد ترتيب ضرب المصفوفتين. |

### translateTransform(float dx, float dy) {#translateTransform-float-float-}
```
public void translateTransform(float dx, float dy)
```


يطبق الإزاحة المحددة على التحويل الهندسي المحلي. تُضيف هذه الطريقة الإزاحة إلى بداية التحويل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| dx | float | قيمة الترجمة في المحور x. |
| dy | float | قيمة الترجمة في المحور y. |

### translateTransform(float dx, float dy, int order) {#translateTransform-float-float-int-}
```
public void translateTransform(float dx, float dy, int order)
```


يطبق الإزاحة المحددة على التحويل الهندسي المحلي بالترتيب المحدد.

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
| sx | float | عامل مقياس التحويل في اتجاه المحور x. |
| sy | float | عامل مقياس التحويل في اتجاه المحور y. |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public void scaleTransform(float sx, float sy, int order)
```


يقوم بتوسيع التحويل الهندسي المحلي بالمقادير المحددة بالترتيب المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| sx | float | عامل مقياس التحويل في اتجاه المحور x. |
| sy | float | عامل مقياس التحويل في اتجاه المحور y. |
| order | int | [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder) الذي يحدد ما إذا كان سيتم إلحاق أو إلحاق مسبق لمصفوفة التكبير. |

### rotateTransform(float angle) {#rotateTransform-float-}
```
public void rotateTransform(float angle)
```


يدور التحويل الهندسي المحلي بالمقدار المحدد. تقوم هذه الطريقة بإلحاق مصفوفة الدوران في بداية التحويل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| زاوية | float | زاوية (المدى) الدوران. |

### rotateTransform(float angle, int order) {#rotateTransform-float-int-}
```
public void rotateTransform(float angle, int order)
```


يدور التحويل الهندسي المحلي بالمقدار المحدد بالترتيب المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| زاوية | float | زاوية (المدى) الدوران. |
| order | int | [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder) الذي يحدد ما إذا كان سيتم إلحاق أو إلحاق مسبق لمصفوفة الدوران. |

