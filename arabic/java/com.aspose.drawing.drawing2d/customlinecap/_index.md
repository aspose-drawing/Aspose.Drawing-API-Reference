---
title: CustomLineCap
second_title: مرجع API لـ Aspose.Drawing للـ Java
description: يغلف طرف خط مخصص معرف من قبل المستخدم.
type: docs
weight: 17
url: /ar/java/com.aspose.drawing.drawing2d/customlinecap/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public class CustomLineCap implements System.IDisposable
```

يغلف طرف خط مخصص معرف من قبل المستخدم.
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath)](#CustomLineCap-com.aspose.drawing.drawing2d.GraphicsPath-com.aspose.drawing.drawing2d.GraphicsPath-) | ينشئ مثيلاً جديداً من الفئة [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) مع المخطط والملء المحددين. |
| [CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap)](#CustomLineCap-com.aspose.drawing.drawing2d.GraphicsPath-com.aspose.drawing.drawing2d.GraphicsPath-int-) | ينشئ مثيلاً جديداً من الفئة [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) استناداً إلى تعداد [LineCap](../../com.aspose.drawing.drawing2d/linecap) الموجود المحدد، مع المخطط والملء المحددين. |
| [CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap, float baseInset)](#CustomLineCap-com.aspose.drawing.drawing2d.GraphicsPath-com.aspose.drawing.drawing2d.GraphicsPath-int-float-) | ينشئ مثيلاً جديداً من الفئة [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) استناداً إلى تعداد [LineCap](../../com.aspose.drawing.drawing2d/linecap) الموجود المحدد، مع المخطط والملء والداخلية المحددة. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getStrokeJoin()](#getStrokeJoin--) | يحصل أو يعيّن تعداد [LineJoin](../../com.aspose.drawing.drawing2d/linejoin) الذي يحدد كيفية ربط الخطوط التي تُكوّن كائن [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap). |
| [setStrokeJoin(int value)](#setStrokeJoin-int-) | يحصل أو يعيّن تعداد [LineJoin](../../com.aspose.drawing.drawing2d/linejoin) الذي يحدد كيفية ربط الخطوط التي تُكوّن كائن [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap). |
| [getBaseCap()](#getBaseCap--) | يحصل أو يعيّن تعداد [LineCap](../../com.aspose.drawing.drawing2d/linecap) الذي يُبنى عليه هذا الـ[CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap). |
| [setBaseCap(int value)](#setBaseCap-int-) | يحصل أو يعيّن تعداد [LineCap](../../com.aspose.drawing.drawing2d/linecap) الذي يُبنى عليه هذا الـ[CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap). |
| [getBaseInset()](#getBaseInset--) | يحصل أو يعيّن المسافة بين الغطاء والخط. |
| [setBaseInset(float value)](#setBaseInset-float-) | يحصل أو يعيّن المسافة بين الغطاء والخط. |
| [getWidthScale()](#getWidthScale--) | يحصل أو يعيّن مقدار التحجيم لهذا كائن الفئة [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) بالنسبة إلى عرض كائن [Pen](../../com.aspose.drawing/pen). |
| [setWidthScale(float value)](#setWidthScale-float-) | يحصل أو يعيّن مقدار التحجيم لهذا كائن الفئة [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) بالنسبة إلى عرض كائن [Pen](../../com.aspose.drawing/pen). |
| [dispose()](#dispose--) | يطلق جميع الموارد المستخدمة من قبل كائن [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap). |
| [deepClone()](#deepClone--) | ينشئ نسخة مطابقة تماماً من هذا الـ[CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap). |
| [setStrokeCaps(int startCap, int endCap)](#setStrokeCaps-int-int-) | يضبط القمم المستخدمة لبدء وإنهاء الخطوط التي تشكل هذه القمة المخصصة. |
| [getStrokeCaps(int[] startCap, int[] endCap)](#getStrokeCaps-int---int---) | يحصل على القمم المستخدمة لبدء وإنهاء الخطوط التي تشكل هذه القمة المخصصة. |
| [getFillPath()](#getFillPath--) |  |
| [getStrokePath()](#getStrokePath--) | يحصل على الكائن الذي يحدد مخطط القمة المخصصة. |
### CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath) {#CustomLineCap-com.aspose.drawing.drawing2d.GraphicsPath-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath)
```


ينشئ مثيلاً جديداً من الفئة [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) مع المخطط والملء المحددين.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fillPath | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | كائن [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) يحدد التعبئة للقمة المخصصة. |
| strokePath | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | كائن [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) يحدد مخطط القمة المخصصة. |

### CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap) {#CustomLineCap-com.aspose.drawing.drawing2d.GraphicsPath-com.aspose.drawing.drawing2d.GraphicsPath-int-}
```
public CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap)
```


ينشئ مثيلاً جديداً من الفئة [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) استناداً إلى تعداد [LineCap](../../com.aspose.drawing.drawing2d/linecap) الموجود المحدد، مع المخطط والملء المحددين.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fillPath | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | كائن [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) يحدد التعبئة للقمة المخصصة. |
| strokePath | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | كائن [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) يحدد مخطط القمة المخصصة. |
| baseCap | int | قمة الخط التي يُنشأ منها القمة المخصصة. |

### CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap, float baseInset) {#CustomLineCap-com.aspose.drawing.drawing2d.GraphicsPath-com.aspose.drawing.drawing2d.GraphicsPath-int-float-}
```
public CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap, float baseInset)
```


ينشئ مثيلاً جديداً من الفئة [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) استناداً إلى تعداد [LineCap](../../com.aspose.drawing.drawing2d/linecap) الموجود المحدد، مع المخطط والملء والداخلية المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fillPath | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | كائن [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) يحدد التعبئة للقمة المخصصة. |
| strokePath | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | كائن [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) يحدد مخطط القمة المخصصة. |
| baseCap | int | قمة الخط التي يُنشأ منها القمة المخصصة. |
| baseInset | float | المسافة بين القمة والخط. |

### getStrokeJoin() {#getStrokeJoin--}
```
public final int getStrokeJoin()
```


يحصل أو يعيّن تعداد [LineJoin](../../com.aspose.drawing.drawing2d/linejoin) الذي يحدد كيفية ربط الخطوط التي تُكوّن كائن [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap).

**Returns:**
int
### setStrokeJoin(int value) {#setStrokeJoin-int-}
```
public final void setStrokeJoin(int value)
```


يحصل أو يعيّن تعداد [LineJoin](../../com.aspose.drawing.drawing2d/linejoin) الذي يحدد كيفية ربط الخطوط التي تُكوّن كائن [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getBaseCap() {#getBaseCap--}
```
public final int getBaseCap()
```


يحصل أو يعيّن تعداد [LineCap](../../com.aspose.drawing.drawing2d/linecap) الذي يُبنى عليه هذا الـ[CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap).

**Returns:**
int
### setBaseCap(int value) {#setBaseCap-int-}
```
public final void setBaseCap(int value)
```


يحصل أو يعيّن تعداد [LineCap](../../com.aspose.drawing.drawing2d/linecap) الذي يُبنى عليه هذا الـ[CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getBaseInset() {#getBaseInset--}
```
public final float getBaseInset()
```


يحصل أو يعيّن المسافة بين الغطاء والخط.

**Returns:**
float
### setBaseInset(float value) {#setBaseInset-float-}
```
public final void setBaseInset(float value)
```


يحصل أو يعيّن المسافة بين الغطاء والخط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getWidthScale() {#getWidthScale--}
```
public final float getWidthScale()
```


يحصل أو يعيّن مقدار التحجيم لهذا كائن الفئة [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) بالنسبة إلى عرض كائن [Pen](../../com.aspose.drawing/pen).

**Returns:**
float
### setWidthScale(float value) {#setWidthScale-float-}
```
public final void setWidthScale(float value)
```


يحصل أو يعيّن مقدار التحجيم لهذا كائن الفئة [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) بالنسبة إلى عرض كائن [Pen](../../com.aspose.drawing/pen).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | float |  |

### dispose() {#dispose--}
```
public final void dispose()
```


يطلق جميع الموارد المستخدمة من قبل كائن [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap).

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


ينشئ نسخة مطابقة تماماً من هذا الـ[CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap).

**Returns:**
java.lang.Object - الـ [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) الذي تُنشئه هذه الطريقة، محولًا إلى كائن.
### setStrokeCaps(int startCap, int endCap) {#setStrokeCaps-int-int-}
```
public final void setStrokeCaps(int startCap, int endCap)
```


يضبط القمم المستخدمة لبدء وإنهاء الخطوط التي تشكل هذه القمة المخصصة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| startCap | int | التعداد [LineCap](../../com.aspose.drawing.drawing2d/linecap) المستخدم في بداية الخط داخل هذه القمة. |
| endCap | int | التعداد [LineCap](../../com.aspose.drawing.drawing2d/linecap) المستخدم في نهاية الخط داخل هذه القمة. |

### getStrokeCaps(int[] startCap, int[] endCap) {#getStrokeCaps-int---int---}
```
public final void getStrokeCaps(int[] startCap, int[] endCap)
```


يحصل على القمم المستخدمة لبدء وإنهاء الخطوط التي تشكل هذه القمة المخصصة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| startCap | int[] | التعداد [LineCap](../../com.aspose.drawing.drawing2d/linecap) المستخدم في بداية الخط داخل هذه القمة. |
| endCap | int[] | التعداد [LineCap](../../com.aspose.drawing.drawing2d/linecap) المستخدم في نهاية الخط داخل هذه القمة. |

### getFillPath() {#getFillPath--}
```
public GraphicsPath getFillPath()
```




**Returns:**
[GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath)
### getStrokePath() {#getStrokePath--}
```
public GraphicsPath getStrokePath()
```


يحصل على الكائن الذي يحدد مخطط القمة المخصصة.

**Returns:**
[GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) - The object that defines the outline of the custom cap.
