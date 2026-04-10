---
title: قلم
second_title: مرجع API لـ Aspose.Drawing للـ Java
description: يعرّف كائنًا يُستخدم لرسم الخطوط والمنحنيات.
type: docs
weight: 34
url: /ar/java/com.aspose.drawing/pen/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public class Pen implements System.IDisposable
```

يعرّف كائنًا يُستخدم لرسم الخطوط والمنحنيات.
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [Pen(Color color)](#Pen-com.aspose.drawing.Color-) | ينشئ مثيلاً جديدًا من فئة [Pen](../../com.aspose.drawing/pen) مع `Color` المحدد ([.getColor](../../null/\#getColor)/[.setColor(Color)](../../null/\#setColor-Color-)). |
| [Pen(Brush brush, float width)](#Pen-com.aspose.drawing.Brush-float-) | ينشئ مثيلاً جديدًا من فئة Pen مع الـ Brush والعرض المحددين. |
| [Pen(Brush brush)](#Pen-com.aspose.drawing.Brush-) | ينشئ مثيلاً جديدًا من فئة [Pen](../../com.aspose.drawing/pen) مع `Brush` المحدد ([.getBrush](../../null/\#getBrush)/[.setBrush(Brush)](../../null/\#setBrush-Brush-)). |
| [Pen(Color color, float width)](#Pen-com.aspose.drawing.Color-float-) | ينشئ مثيلاً جديدًا من فئة Pen مع خصائص Color والعرض المحددة. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getColor()](#getColor--) | يحصل أو يضبط لون هذا [Pen](../../com.aspose.drawing/pen). |
| [setColor(Color value)](#setColor-com.aspose.drawing.Color-) | يحصل أو يضبط لون هذا [Pen](../../com.aspose.drawing/pen). |
| [getBrush()](#getBrush--) | يحصل أو يضبط الـ Brush الذي يحدد سمات هذا [Pen](../../com.aspose.drawing/pen). |
| [setBrush(Brush value)](#setBrush-com.aspose.drawing.Brush-) | يحصل أو يضبط الـ Brush الذي يحدد سمات هذا [Pen](../../com.aspose.drawing/pen). |
| [getCompoundArray()](#getCompoundArray--) | يحصل أو يضبط مصفوفة القيم التي تحدد قلمًا مركبًا. |
| [setCompoundArray(float[] value)](#setCompoundArray-float---) | يحصل أو يضبط مصفوفة القيم التي تحدد قلمًا مركبًا. |
| [getWidth()](#getWidth--) | يحصل أو يضبط عرض هذا Pen، بوحدات كائن Graphics المستخدم للرسم. |
| [setWidth(float value)](#setWidth-float-) | يحصل أو يضبط عرض هذا Pen، بوحدات كائن Graphics المستخدم للرسم. |
| [getStartCap()](#getStartCap--) | يحصل أو يضبط نمط الغطاء المستخدم في بداية الخطوط المرسومة بهذا Pen. |
| [setStartCap(int value)](#setStartCap-int-) | يحصل أو يضبط نمط الغطاء المستخدم في بداية الخطوط المرسومة بهذا Pen. |
| [getEndCap()](#getEndCap--) | يحصل أو يضبط نمط الغطاء المستخدم في نهاية الخطوط المرسومة بهذا Pen. |
| [setEndCap(int value)](#setEndCap-int-) | يحصل أو يضبط نمط الغطاء المستخدم في نهاية الخطوط المرسومة بهذا Pen. |
| [getLineJoin()](#getLineJoin--) | يحصل أو يضبط نمط الوصل لنهايات خطين متتاليين مرسومين بهذا Pen. |
| [setLineJoin(int value)](#setLineJoin-int-) | يحصل أو يضبط نمط الوصل لنهايات خطين متتاليين مرسومين بهذا Pen. |
| [getMiterLimit()](#getMiterLimit--) | يحصل أو يضبط حد سمك الوصل عند زاوية ميتيرية. |
| [setMiterLimit(float value)](#setMiterLimit-float-) | يحصل أو يضبط حد سمك الوصل عند زاوية ميتيرية. |
| [getAlignment()](#getAlignment--) | يحصل أو يضبط المحاذاة لهذا [Pen](../../com.aspose.drawing/pen). |
| [setAlignment(int value)](#setAlignment-int-) | يحصل أو يضبط المحاذاة لهذا [Pen](../../com.aspose.drawing/pen). |
| [getTransform()](#getTransform--) | يحصل أو يضبط نسخة من التحويل الهندسي لهذا [Pen](../../com.aspose.drawing/pen). |
| [setTransform(Matrix value)](#setTransform-com.aspose.drawing.drawing2d.Matrix-) | يحصل أو يضبط نسخة من التحويل الهندسي لهذا [Pen](../../com.aspose.drawing/pen). |
| [getCustomStartCap()](#getCustomStartCap--) | يحصل أو يضبط غطاءً مخصصًا لاستخدامه في بداية الخطوط المرسومة بهذا [Pen](../../com.aspose.drawing/pen). |
| [setCustomStartCap(CustomLineCap value)](#setCustomStartCap-com.aspose.drawing.drawing2d.CustomLineCap-) | يحصل أو يضبط غطاءً مخصصًا لاستخدامه في بداية الخطوط المرسومة بهذا [Pen](../../com.aspose.drawing/pen). |
| [getCustomEndCap()](#getCustomEndCap--) | يحصل أو يضبط غطاءً مخصصًا لاستخدامه في نهاية الخطوط المرسومة بهذا [Pen](../../com.aspose.drawing/pen). |
| [setCustomEndCap(CustomLineCap value)](#setCustomEndCap-com.aspose.drawing.drawing2d.CustomLineCap-) | يحصل أو يضبط غطاءً مخصصًا لاستخدامه في نهاية الخطوط المرسومة بهذا [Pen](../../com.aspose.drawing/pen). |
| [getDashCap()](#getDashCap--) | يحصل أو يضبط نمط الغطاء المستخدم في نهاية الشرطات التي تشكل الخطوط المتقطعة المرسومة بهذا [Pen](../../com.aspose.drawing/pen). |
| [setDashCap(int value)](#setDashCap-int-) | يحصل أو يضبط نمط الغطاء المستخدم في نهاية الشرطات التي تشكل الخطوط المتقطعة المرسومة بهذا [Pen](../../com.aspose.drawing/pen). |
| [getDashOffset()](#getDashOffset--) | يحصل أو يضبط المسافة من بداية الخط إلى بداية نمط الشرط. |
| [setDashOffset(float value)](#setDashOffset-float-) | يحصل أو يضبط المسافة من بداية الخط إلى بداية نمط الشرط. |
| [getDashPattern()](#getDashPattern--) | يحصل أو يضبط مصفوفة من الشرطات والمسافات المخصصة. |
| [setDashPattern(float[] value)](#setDashPattern-float---) | يحصل أو يضبط مصفوفة من الشرطات والمسافات المخصصة. |
| [getDashStyle()](#getDashStyle--) | يحصل أو يضبط النمط المستخدم للخطوط المتقطعة المرسومة بهذا [Pen](../../com.aspose.drawing/pen). |
| [setDashStyle(int value)](#setDashStyle-int-) | يحصل أو يضبط النمط المستخدم للخطوط المتقطعة المرسومة بهذا [Pen](../../com.aspose.drawing/pen). |
| [getPenType()](#getPenType--) | يحصل على نمط الخطوط المرسومة بهذا Pen. |
| [dispose()](#dispose--) | يطلق جميع الموارد المستخدمة بواسطة هذا Pen. |
| [deepClone()](#deepClone--) | ينشئ نسخة مطابقة تمامًا من هذا [Pen](../../com.aspose.drawing/pen). |
| [setLineCap(int startCap, int endCap, int dashCap)](#setLineCap-int-int-int-) | يضبط القيم التي تحدد نمط الغطاء المستخدم لإنهاء الخطوط المرسومة بواسطة هذا [Pen](../../com.aspose.drawing/pen). |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | يقوم بتكبير التحويل الهندسي المحلي بالعوامل المحددة. |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | يقوم بتكبير التحويل الهندسي المحلي بالعوامل المحددة بالترتيب المحدد. |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | ينقل التحويل الهندسي المحلي بالأبعاد المحددة. |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | ينقل التحويل الهندسي المحلي بالأبعاد المحددة بالترتيب المحدد. |
| [rotateTransform(float angle)](#rotateTransform-float-) | يدور التحويل الهندسي المحلي بالزاوية المحددة. |
| [rotateTransform(float angle, int order)](#rotateTransform-float-int-) | يدور التحويل الهندسي المحلي بالزاوية المحددة بالترتيب المحدد. |
| [resetTransform()](#resetTransform--) | يعيد تعيين مصفوفة التحويل الهندسي لهذا [Pen](../../com.aspose.drawing/pen) إلى هوية. |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-) | يضرب مصفوفة التحويل لهذا [Pen](../../com.aspose.drawing/pen) بالمصفوفة المحددة [Matrix](../../com.aspose.drawing.drawing2d/matrix). |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-int-) | يضرب مصفوفة التحويل لهذا [Pen](../../com.aspose.drawing/pen) بالمصفوفة المحددة [Matrix](../../com.aspose.drawing.drawing2d/matrix) بالترتيب المحدد. |
### Pen(Color color) {#Pen-com.aspose.drawing.Color-}
```
public Pen(Color color)
```


ينشئ مثيلاً جديدًا من فئة [Pen](../../com.aspose.drawing/pen) مع `Color` المحدد ([.getColor](../../null/\#getColor)/[.setColor(Color)](../../null/\#setColor-Color-)).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| color | [Color](../../com.aspose.drawing/color) | ‏`Color`([.getColor](../../null/\#getColor)/[.setColor(Color)](../../null/\#setColor-Color-)) التي تحدد خصائص التعبئة لهذا [Pen](../../com.aspose.drawing/pen). |

### Pen(Brush brush, float width) {#Pen-com.aspose.drawing.Brush-float-}
```
public Pen(Brush brush, float width)
```


ينشئ مثيلاً جديدًا من فئة Pen مع الـ Brush والعرض المحددين.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.drawing/brush) | ‏Brush التي تحدد خصائص هذا Pen. |
| العرض | float | عرض الـ Pen الجديد. |

### Pen(Brush brush) {#Pen-com.aspose.drawing.Brush-}
```
public Pen(Brush brush)
```


ينشئ مثيلاً جديدًا من فئة [Pen](../../com.aspose.drawing/pen) مع `Brush` المحدد ([.getBrush](../../null/\#getBrush)/[.setBrush(Brush)](../../null/\#setBrush-Brush-)).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.drawing/brush) | ‏`Brush`([.getBrush](../../null/\#getBrush)/[.setBrush(Brush)](../../null/\#setBrush-Brush-)) التي تحدد خصائص التعبئة لهذا [Pen](../../com.aspose.drawing/pen). |

### Pen(Color color, float width) {#Pen-com.aspose.drawing.Color-float-}
```
public Pen(Color color, float width)
```


ينشئ مثيلاً جديدًا من فئة Pen مع خصائص Color والعرض المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| color | [Color](../../com.aspose.drawing/color) | ‏Color هيكل يحدد لون هذا Pen. |
| العرض | float | قيمة تشير إلى عرض هذا Pen. |

### getColor() {#getColor--}
```
public final Color getColor()
```


يحصل أو يضبط لون هذا [Pen](../../com.aspose.drawing/pen).

القيمة: ‏`Color`([.getColor](../../null/\#getColor)/[.setColor(Color)](../../null/\#setColor-Color-)) هيكل يمثل لون هذا [Pen](../../com.aspose.drawing/pen).

**Returns:**
[Color](../../com.aspose.drawing/color)
### setColor(Color value) {#setColor-com.aspose.drawing.Color-}
```
public final void setColor(Color value)
```


يحصل أو يضبط لون هذا [Pen](../../com.aspose.drawing/pen).

القيمة: ‏`Color`([.getColor](../../null/\#getColor)/[.setColor(Color)](../../null/\#setColor-Color-)) هيكل يمثل لون هذا [Pen](../../com.aspose.drawing/pen).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Color](../../com.aspose.drawing/color) |  |

### getBrush() {#getBrush--}
```
public final Brush getBrush()
```


يحصل أو يضبط الـ Brush الذي يحدد سمات هذا [Pen](../../com.aspose.drawing/pen).

**Returns:**
[Brush](../../com.aspose.drawing/brush)
### setBrush(Brush value) {#setBrush-com.aspose.drawing.Brush-}
```
public final void setBrush(Brush value)
```


يحصل أو يضبط الـ Brush الذي يحدد سمات هذا [Pen](../../com.aspose.drawing/pen).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Brush](../../com.aspose.drawing/brush) |  |

### getCompoundArray() {#getCompoundArray--}
```
public final float[] getCompoundArray()
```


يحصل أو يضبط مصفوفة من القيم التي تحدد قلم مركب. القلم المركب يرسم خطًا مركبًا مكوّنًا من خطوط متوازية ومسافات.

**Returns:**
float[] - مصفوفة من الأعداد الحقيقية التي تحدد مصفوفة المركب. يجب أن تكون العناصر في المصفوفة بترتيب تصاعدي، لا تقل عن 0، ولا تزيد عن 1.
### setCompoundArray(float[] value) {#setCompoundArray-float---}
```
public final void setCompoundArray(float[] value)
```


يحصل أو يضبط مصفوفة من القيم التي تحدد قلم مركب. القلم المركب يرسم خطًا مركبًا مكوّنًا من خطوط متوازية ومسافات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | float[] |  |

### getWidth() {#getWidth--}
```
public final float getWidth()
```


يحصل أو يضبط عرض هذا Pen، بوحدات كائن Graphics المستخدم للرسم.

**Returns:**
float
### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```


يحصل أو يضبط عرض هذا Pen، بوحدات كائن Graphics المستخدم للرسم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getStartCap() {#getStartCap--}
```
public final int getStartCap()
```


يحصل أو يضبط نمط الغطاء المستخدم في بداية الخطوط المرسومة بهذا Pen.

**Returns:**
int
### setStartCap(int value) {#setStartCap-int-}
```
public final void setStartCap(int value)
```


يحصل أو يضبط نمط الغطاء المستخدم في بداية الخطوط المرسومة بهذا Pen.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getEndCap() {#getEndCap--}
```
public final int getEndCap()
```


يحصل أو يضبط نمط الغطاء المستخدم في نهاية الخطوط المرسومة بهذا Pen.

**Returns:**
int
### setEndCap(int value) {#setEndCap-int-}
```
public final void setEndCap(int value)
```


يحصل أو يضبط نمط الغطاء المستخدم في نهاية الخطوط المرسومة بهذا Pen.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getLineJoin() {#getLineJoin--}
```
public final int getLineJoin()
```


يحصل أو يضبط نمط الوصل لنهايات خطين متتاليين مرسومين بهذا Pen.

--------------------

في الوقت الحالي، تعمل وصلة الميتير فعليًا كـ MiterClipped.

**Returns:**
int
### setLineJoin(int value) {#setLineJoin-int-}
```
public final void setLineJoin(int value)
```


يحصل أو يضبط نمط الوصل لنهايات خطين متتاليين مرسومين بهذا Pen.

--------------------

في الوقت الحالي، تعمل وصلة الميتير فعليًا كـ MiterClipped.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getMiterLimit() {#getMiterLimit--}
```
public final float getMiterLimit()
```


يحصل أو يضبط حد سمك الوصل عند زاوية ميتيرية.

**Returns:**
float
### setMiterLimit(float value) {#setMiterLimit-float-}
```
public final void setMiterLimit(float value)
```


يحصل أو يضبط حد سمك الوصل عند زاوية ميتيرية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getAlignment() {#getAlignment--}
```
public final int getAlignment()
```


يحصل أو يضبط المحاذاة لهذا [Pen](../../com.aspose.drawing/pen).

**Returns:**
int - ‏[PenAlignment](../../com.aspose.drawing.drawing2d/penalignment) التي تمثل المحاذاة لهذا [Pen](../../com.aspose.drawing/pen).
### setAlignment(int value) {#setAlignment-int-}
```
public final void setAlignment(int value)
```


يحصل أو يضبط المحاذاة لهذا [Pen](../../com.aspose.drawing/pen).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getTransform() {#getTransform--}
```
public final Matrix getTransform()
```


يحصل أو يضبط نسخة من التحويل الهندسي لهذا [Pen](../../com.aspose.drawing/pen).

القيمة: نسخة من ‏[Matrix](../../com.aspose.drawing.drawing2d/matrix) التي تمثل التحويل الهندسي لهذا [Pen](../../com.aspose.drawing/pen).

**Returns:**
[Matrix](../../com.aspose.drawing.drawing2d/matrix)
### setTransform(Matrix value) {#setTransform-com.aspose.drawing.drawing2d.Matrix-}
```
public final void setTransform(Matrix value)
```


يحصل أو يضبط نسخة من التحويل الهندسي لهذا [Pen](../../com.aspose.drawing/pen).

القيمة: نسخة من ‏[Matrix](../../com.aspose.drawing.drawing2d/matrix) التي تمثل التحويل الهندسي لهذا [Pen](../../com.aspose.drawing/pen).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.drawing.drawing2d/matrix) |  |

### getCustomStartCap() {#getCustomStartCap--}
```
public final CustomLineCap getCustomStartCap()
```


يحصل أو يضبط غطاءً مخصصًا لاستخدامه في بداية الخطوط المرسومة بهذا [Pen](../../com.aspose.drawing/pen).

**Returns:**
[CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) - A [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) that represents the cap used at the beginning of lines drawn with this [Pen](../../com.aspose.drawing/pen).
### setCustomStartCap(CustomLineCap value) {#setCustomStartCap-com.aspose.drawing.drawing2d.CustomLineCap-}
```
public final void setCustomStartCap(CustomLineCap value)
```


يحصل أو يضبط غطاءً مخصصًا لاستخدامه في بداية الخطوط المرسومة بهذا [Pen](../../com.aspose.drawing/pen).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) |  |

### getCustomEndCap() {#getCustomEndCap--}
```
public final CustomLineCap getCustomEndCap()
```


يحصل أو يضبط غطاءً مخصصًا لاستخدامه في نهاية الخطوط المرسومة بهذا [Pen](../../com.aspose.drawing/pen).

**Returns:**
[CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) - A [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) that represents the cap used at the end of lines drawn with this [Pen](../../com.aspose.drawing/pen).
### setCustomEndCap(CustomLineCap value) {#setCustomEndCap-com.aspose.drawing.drawing2d.CustomLineCap-}
```
public final void setCustomEndCap(CustomLineCap value)
```


يحصل أو يضبط غطاءً مخصصًا لاستخدامه في نهاية الخطوط المرسومة بهذا [Pen](../../com.aspose.drawing/pen).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) |  |

### getDashCap() {#getDashCap--}
```
public final int getDashCap()
```


يحصل أو يضبط نمط الغطاء المستخدم في نهاية الشرطات التي تشكل الخطوط المتقطعة المرسومة بهذا [Pen](../../com.aspose.drawing/pen).

**Returns:**
int - إحدى قيم `DashCap`([.getDashCap](../../null/\#getDashCap)/[.setDashCap(int)](../../null/\#setDashCap-int-)) التي تمثل نمط الغطاء المستخدم في بداية ونهاية الشرطات التي تشكل الخطوط المتقطعة المرسومة بهذا [Pen](../../com.aspose.drawing/pen).
### setDashCap(int value) {#setDashCap-int-}
```
public final void setDashCap(int value)
```


يحصل أو يضبط نمط الغطاء المستخدم في نهاية الشرطات التي تشكل الخطوط المتقطعة المرسومة بهذا [Pen](../../com.aspose.drawing/pen).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getDashOffset() {#getDashOffset--}
```
public final float getDashOffset()
```


يحصل أو يضبط المسافة من بداية الخط إلى بداية نمط الشرط.

**Returns:**
float - المسافة من بداية الخط إلى بداية نمط الشرطة.
### setDashOffset(float value) {#setDashOffset-float-}
```
public final void setDashOffset(float value)
```


يحصل أو يضبط المسافة من بداية الخط إلى بداية نمط الشرط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getDashPattern() {#getDashPattern--}
```
public final float[] getDashPattern()
```


يحصل أو يضبط مصفوفة من الشرطات والمسافات المخصصة.

**Returns:**
float[] - مصفوفة من الأعداد الحقيقية التي تحدد أطوال الشرطات والمسافات المتناوبة في الخطوط المتقطعة.
### setDashPattern(float[] value) {#setDashPattern-float---}
```
public final void setDashPattern(float[] value)
```


يحصل أو يضبط مصفوفة من الشرطات والمسافات المخصصة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | float[] |  |

### getDashStyle() {#getDashStyle--}
```
public final int getDashStyle()
```


يحصل أو يضبط النمط المستخدم للخطوط المتقطعة المرسومة بهذا [Pen](../../com.aspose.drawing/pen).

**Returns:**
int - أ `DashStyle`([.getDashStyle](../../null/\#getDashStyle)/[.setDashStyle(int)](../../null/\#setDashStyle-int-)) التي تمثل النمط المستخدم للخطوط المتقطعة المرسومة بهذا [Pen](../../com.aspose.drawing/pen).
### setDashStyle(int value) {#setDashStyle-int-}
```
public final void setDashStyle(int value)
```


يحصل أو يضبط النمط المستخدم للخطوط المتقطعة المرسومة بهذا [Pen](../../com.aspose.drawing/pen).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getPenType() {#getPenType--}
```
public final int getPenType()
```


يحصل على نمط الخطوط المرسومة بهذا Pen.

القيمة: أ `PenType`([.getPenType](../../null/\#getPenType)) تعداد يحدد نمط الخطوط المرسومة بهذا [Pen](../../com.aspose.drawing/pen).

**Returns:**
int
### dispose() {#dispose--}
```
public final void dispose()
```


يطلق جميع الموارد المستخدمة بواسطة هذا Pen.

--------------------

هذه الطريقة لا تفعل شيئًا فعليًا. إنها فقط للتوافق مع واجهة برمجة تطبيقات System.Drawing.

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


ينشئ نسخة مطابقة تمامًا من هذا [Pen](../../com.aspose.drawing/pen).

**Returns:**
java.lang.Object - كائن يمكن تحويله إلى [Pen](../../com.aspose.drawing/pen).
### setLineCap(int startCap, int endCap, int dashCap) {#setLineCap-int-int-int-}
```
public final void setLineCap(int startCap, int endCap, int dashCap)
```


يضبط القيم التي تحدد نمط الغطاء المستخدم لإنهاء الخطوط المرسومة بواسطة هذا [Pen](../../com.aspose.drawing/pen).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| startCap | int | أ [LineCap](../../com.aspose.drawing.drawing2d/linecap) التي تمثل نمط الغطاء لاستخدامه في بداية الخطوط المرسومة بهذا [Pen](../../com.aspose.drawing/pen). |
| endCap | int | أ [LineCap](../../com.aspose.drawing.drawing2d/linecap) التي تمثل نمط الغطاء لاستخدامه في نهاية الخطوط المرسومة بهذا [Pen](../../com.aspose.drawing/pen). |
| dashCap | int | أ [LineCap](../../com.aspose.drawing.drawing2d/linecap) التي تمثل نمط الغطاء لاستخدامه في بداية أو نهاية الخطوط المتقطعة المرسومة بهذا [Pen](../../com.aspose.drawing/pen). |

### scaleTransform(float sx, float sy) {#scaleTransform-float-float-}
```
public final void scaleTransform(float sx, float sy)
```


يقوم بتكبير التحويل الهندسي المحلي بالعوامل المحددة. هذه الطريقة تسبق مصفوفة التكبير إلى التحويل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| sx | float | العامل الذي يُستخدم لتكبير التحويل في اتجاه المحور س. |
| sy | float | العامل الذي يُستخدم لتكبير التحويل في اتجاه المحور ص. |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public final void scaleTransform(float sx, float sy, int order)
```


يقوم بتكبير التحويل الهندسي المحلي بالعوامل المحددة بالترتيب المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| sx | float | العامل الذي يُستخدم لتكبير التحويل في اتجاه المحور س. |
| sy | float | العامل الذي يُستخدم لتكبير التحويل في اتجاه المحور ص. |
| order | int | [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder) الذي يحدد ما إذا كان سيتم إلحاق أو إلحاق مسبق لمصفوفة التكبير. |

### translateTransform(float dx, float dy) {#translateTransform-float-float-}
```
public final void translateTransform(float dx, float dy)
```


يقوم بترجمة التحويل الهندسي المحلي بالأبعاد المحددة. هذه الطريقة تسبق الترجمة إلى التحويل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| dx | float | قيمة الترجمة في المحور x. |
| dy | float | قيمة الترجمة في المحور y. |

### translateTransform(float dx, float dy, int order) {#translateTransform-float-float-int-}
```
public final void translateTransform(float dx, float dy, int order)
```


ينقل التحويل الهندسي المحلي بالأبعاد المحددة بالترتيب المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| dx | float | قيمة الترجمة في المحور x. |
| dy | float | قيمة الترجمة في المحور y. |
| ترتيب | int | الترتيب (إضافة في البداية أو في النهاية) الذي يُطبق فيه الترجمة. |

### rotateTransform(float angle) {#rotateTransform-float-}
```
public final void rotateTransform(float angle)
```


يقوم بتدوير التحويل الهندسي المحلي بالزاوية المحددة. هذه الطريقة تسبق الدوران إلى التحويل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| زاوية | float | زاوية الدوران. |

### rotateTransform(float angle, int order) {#rotateTransform-float-int-}
```
public final void rotateTransform(float angle, int order)
```


يدور التحويل الهندسي المحلي بالزاوية المحددة بالترتيب المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| زاوية | float | زاوية الدوران. |
| order | int | [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder) الذي يحدد ما إذا كان سيتم إلحاق أو إلحاق مسبق لمصفوفة الدوران. |

### resetTransform() {#resetTransform--}
```
public final void resetTransform()
```


يعيد تعيين مصفوفة التحويل الهندسي لهذا [Pen](../../com.aspose.drawing/pen) إلى هوية.

### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-}
```
public final void multiplyTransform(Matrix matrix)
```


يضرب مصفوفة التحويل لهذا [Pen](../../com.aspose.drawing/pen) بالمصفوفة المحددة [Matrix](../../com.aspose.drawing.drawing2d/matrix).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | الكائن [Matrix](../../com.aspose.drawing.drawing2d/matrix) الذي يُستخدم لضرب مصفوفة التحويل. |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-int-}
```
public final void multiplyTransform(Matrix matrix, int order)
```


يضرب مصفوفة التحويل لهذا [Pen](../../com.aspose.drawing/pen) بالمصفوفة المحددة [Matrix](../../com.aspose.drawing.drawing2d/matrix) بالترتيب المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | الكائن java.awt.geom.AffineTransform الذي يُستخدم لضرب مصفوفة التحويل. |
| ترتيب | int | الترتيب الذي يتم به تنفيذ عملية الضرب. |

