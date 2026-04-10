---
title: Matrix
second_title: مرجع API لـ Aspose.Drawing للـ Java
description: يحتوي على مصفوفة إقليدية 3×3 تمثل تحويلًا هندسيًا.
type: docs
weight: 33
url: /ar/java/com.aspose.drawing.drawing2d/matrix/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public final class Matrix implements System.IDisposable
```

يحتوي على مصفوفة إقليدية 3×3 تمثل تحويلًا هندسيًا. لا يمكن وراثة هذه الفئة.
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [Matrix()](#Matrix--) | ينشئ مثيلًا جديدًا من فئة Matrix كمصفوفة هوية. |
| [Matrix(float m11, float m12, float m21, float m22, float dx, float dy)](#Matrix-float-float-float-float-float-float-) | ينشئ مثيلًا جديدًا من فئة Matrix بالعناصر المحددة. |
| [Matrix(Rectangle rect, Point[] plgpts)](#Matrix-com.aspose.drawing.Rectangle-com.aspose.drawing.Point---) | ينشئ مثيلًا جديدًا من فئة [Matrix](../../com.aspose.drawing.drawing2d/matrix) للتحويل الهندسي المحدد بواسطة المستطيل المحدد ومصفوفة النقاط. |
| [Matrix(RectangleF rect, PointF[] plgpts)](#Matrix-com.aspose.drawing.RectangleF-com.aspose.drawing.PointF---) | ينشئ مثيلًا جديدًا من فئة [Matrix](../../com.aspose.drawing.drawing2d/matrix) للتحويل الهندسي المحدد بواسطة المستطيل المحدد ومصفوفة النقاط. |
## الحقول

| حقل | الوصف |
| --- | --- |
| [IdentityTransform](#IdentityTransform) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getElements()](#getElements--) | يحصل على مصفوفة من القيم العشرية تمثل عناصر هذه المصفوفة. |
| [isIdentity()](#isIdentity--) | يحصل على قيمة تشير إلى ما إذا كانت هذه المصفوفة هي مصفوفة الهوية. |
| [isInvertible()](#isInvertible--) | يحصل على قيمة تشير إلى ما إذا كانت هذه المصفوفة قابلة للعكس. |
| [getOffsetX()](#getOffsetX--) | يحصل على قيمة الإزاحة x (قيمة dx، أو العنصر في الصف الثالث والعمود الأول) لهذه Matrix. |
| [getOffsetY()](#getOffsetY--) | يحصل على قيمة الإزاحة y (قيمة `dy`، أو العنصر في الصف الثالث والعمود الثاني) لهذه Matrix. |
| [dispose()](#dispose--) | يطلق جميع الموارد المستخدمة بواسطة هذه Matrix. |
| [deepClone()](#deepClone--) | ينشئ نسخة مطابقة تمامًا من هذه Matrix. |
| [invert()](#invert--) | يعكس هذه Matrix إذا كانت قابلة للعكس. |
| [translate(float offsetX, float offsetY)](#translate-float-float-) | يطبق متجه الإزاحة المحدد (offsetX و offsetY) على هذه Matrix عن طريق إلحاق متجه الإزاحة في البداية. |
| [translate(float offsetX, float offsetY, int order)](#translate-float-float-int-) | يطبق متجه الإزاحة المحدد على هذه Matrix بالترتيب المحدد. |
| [transformVectors(PointF[] pts)](#transformVectors-com.aspose.drawing.PointF---) | يضرب كل متجه في مصفوفة في الـ matrix. |
| [scale(float scaleX, float scaleY)](#scale-float-float-) | يطبق متجه المقياس المحدد على هذه Matrix عن طريق إلحاق متجه المقياس في البداية. |
| [scale(float scaleX, float scaleY, int order)](#scale-float-float-int-) | يطبق متجه المقياس المحدد (scaleX و scaleY) على هذه Matrix باستخدام الترتيب المحدد. |
| [shear(float shearX, float shearY)](#shear-float-float-) | يطبق متجه القص المحدد على هذه Matrix عن طريق إلحاق تحويل القص في البداية. |
| [shear(float shearX, float shearY, int order)](#shear-float-float-int-) | يطبق متجه القص المحدد على هذه Matrix بالترتيب المحدد. |
| [rotateAt(float angle, PointF point)](#rotateAt-float-com.aspose.drawing.PointF-) | يطبق دورانًا باتجاه عقارب الساعة على هذه Matrix حول النقطة المحددة في معامل point، وعن طريق إلحاق الدوران في البداية. |
| [rotateAt(float angle, PointF point, int order)](#rotateAt-float-com.aspose.drawing.PointF-int-) | يطبق دورانًا باتجاه عقارب الساعة حول النقطة المحددة على هذه Matrix بالترتيب المحدد. |
| [transformPoints(PointF[] pts)](#transformPoints-com.aspose.drawing.PointF---) | يطبق التحويل الهندسي الممثل بواسطة هذه [Matrix](../../com.aspose.drawing.drawing2d/matrix) على مصفوفة محددة من النقاط. |
| [transformPoints(Point[] pts)](#transformPoints-com.aspose.drawing.Point---) | يطبق التحويل الهندسي الممثل بواسطة هذه [Matrix](../../com.aspose.drawing.drawing2d/matrix) على مصفوفة محددة من النقاط. |
| [multiply(Matrix matrix)](#multiply-com.aspose.drawing.drawing2d.Matrix-) | يضرب هذه [Matrix](../../com.aspose.drawing.drawing2d/matrix) في الـ matrix المحدد في معامل `matrix`، عن طريق إلحاق الـ [Matrix](../../com.aspose.drawing.drawing2d/matrix) المحدد في البداية. |
| [multiply(Matrix matrix, int order)](#multiply-com.aspose.drawing.drawing2d.Matrix-int-) | يضرب هذه [Matrix](../../com.aspose.drawing.drawing2d/matrix) في الـ matrix المحدد في معامل `matrix`، وبالترتيب المحدد في معامل `order`. |
| [rotate(float angle)](#rotate-float-) | ألحِق إلى هذه [Matrix](../../com.aspose.drawing.drawing2d/matrix) دورانًا باتجاه عقارب الساعة، حول الأصل وبالزاوية المحددة. |
| [rotate(float angle, int order)](#rotate-float-int-) | يطبق دورانًا باتجاه عقارب الساعة بمقدار محدد في معامل الزاوية، حول الأصل (إحداثيات x و y صفر) لهذه [Matrix](../../com.aspose.drawing.drawing2d/matrix). |
| [reset()](#reset--) | يعيد ضبط هذه [Matrix](../../com.aspose.drawing.drawing2d/matrix) لتحتوي على عناصر مصفوفة الهوية. |
### Matrix() {#Matrix--}
```
public Matrix()
```


ينشئ مثيلًا جديدًا من فئة Matrix كمصفوفة هوية.

### Matrix(float m11, float m12, float m21, float m22, float dx, float dy) {#Matrix-float-float-float-float-float-float-}
```
public Matrix(float m11, float m12, float m21, float m22, float dx, float dy)
```


ينشئ مثيلًا جديدًا من فئة Matrix بالعناصر المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| m11 | float | القيمة في الصف الأول والعمود الأول من الـ Matrix الجديد. |
| m12 | float | القيمة في الصف الأول والعمود الثاني من الـ Matrix الجديد. |
| m21 | float | القيمة في الصف الثاني والعمود الأول للمصفوفة الجديدة. |
| m22 | float | القيمة في الصف الثاني والعمود الثاني للمصفوفة الجديدة. |
| dx | float | القيمة في الصف الثالث والعمود الأول للمصفوفة الجديدة. |
| dy | float | القيمة في الصف الثالث والعمود الثاني للمصفوفة الجديدة. |

### Matrix(Rectangle rect, Point[] plgpts) {#Matrix-com.aspose.drawing.Rectangle-com.aspose.drawing.Point---}
```
public Matrix(Rectangle rect, Point[] plgpts)
```


ينشئ مثيلًا جديدًا من فئة [Matrix](../../com.aspose.drawing.drawing2d/matrix) للتحويل الهندسي المحدد بواسطة المستطيل المحدد ومصفوفة النقاط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | هيكل [Rectangle](../../com.aspose.drawing/rectangle) يمثل المستطيل الذي سيتم تحويله. |
| plgpts | [Point\[\]](../../com.aspose.drawing/point) | مصفوفة من ثلاثة هياكل [Point](../../com.aspose.drawing/point) تمثل نقاط متوازي أضلاع يتم تحويل الزوايا العليا اليسرى والعليا اليمنى والسفلى اليسرى للمستطيل إليها. الزاوية السفلى اليمنى للمتوازي أضلاع مفترضة بناءً على الثلاث زوايا الأولى. |

### Matrix(RectangleF rect, PointF[] plgpts) {#Matrix-com.aspose.drawing.RectangleF-com.aspose.drawing.PointF---}
```
public Matrix(RectangleF rect, PointF[] plgpts)
```


ينشئ مثيلًا جديدًا من فئة [Matrix](../../com.aspose.drawing.drawing2d/matrix) للتحويل الهندسي المحدد بواسطة المستطيل المحدد ومصفوفة النقاط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | هيكل [RectangleF](../../com.aspose.drawing/rectanglef) يمثل المستطيل الذي سيتم تحويله. |
| plgpts | [PointF\[\]](../../com.aspose.drawing/pointf) | مصفوفة من ثلاثة هياكل [PointF](../../com.aspose.drawing/pointf) تمثل نقاط متوازي أضلاع يتم تحويل الزوايا العليا اليسرى والعليا اليمنى والسفلى اليسرى للمستطيل إليها. الزاوية السفلى اليمنى للمتوازي أضلاع مفترضة بناءً على الثلاث زوايا الأولى. |

### IdentityTransform {#IdentityTransform}
```
public static final Matrix IdentityTransform
```


### getElements() {#getElements--}
```
public float[] getElements()
```


يحصل على مصفوفة من القيم العشرية تمثل عناصر هذه المصفوفة.

**Returns:**
float[] - مصفوفة من القيم العائمة تمثل عناصر هذه المصفوفة.
### isIdentity() {#isIdentity--}
```
public boolean isIdentity()
```


يحصل على قيمة تشير إلى ما إذا كانت هذه المصفوفة هي مصفوفة الهوية.

**Returns:**
boolean - قيمة تشير إلى ما إذا كانت هذه المصفوفة هي مصفوفة الهوية.
### isInvertible() {#isInvertible--}
```
public boolean isInvertible()
```


يحصل على قيمة تشير إلى ما إذا كانت هذه المصفوفة قابلة للعكس.

**Returns:**
boolean - قيمة تشير إلى ما إذا كانت هذه المصفوفة قابلة للعكس.
### getOffsetX() {#getOffsetX--}
```
public float getOffsetX()
```


يحصل على قيمة الإزاحة x (قيمة dx، أو العنصر في الصف الثالث والعمود الأول) لهذه Matrix.

**Returns:**
float - قيمة الإزاحة في الاتجاه x (قيمة dx، أو العنصر في الصف الثالث والعمود الأول) لهذه المصفوفة.
### getOffsetY() {#getOffsetY--}
```
public float getOffsetY()
```


يحصل على قيمة الإزاحة y (قيمة `dy`، أو العنصر في الصف الثالث والعمود الثاني) لهذه Matrix.

**Returns:**
float - قيمة الإزاحة في الاتجاه y (القيمة `dy`، أو العنصر في الصف الثالث والعمود الثاني) لهذه المصفوفة.
### dispose() {#dispose--}
```
public void dispose()
```


يطلق جميع الموارد المستخدمة بواسطة هذه Matrix.

--------------------

هذه الطريقة لا تفعل شيئًا فعليًا. إنها فقط للتوافق مع واجهة برمجة تطبيقات System.Drawing.

### deepClone() {#deepClone--}
```
public Matrix deepClone()
```


ينشئ نسخة مطابقة تمامًا من هذه Matrix.

**Returns:**
[Matrix](../../com.aspose.drawing.drawing2d/matrix) - The Matrix that this method creates.
### invert() {#invert--}
```
public void invert()
```


يعكس هذه Matrix إذا كانت قابلة للعكس.

### translate(float offsetX, float offsetY) {#translate-float-float-}
```
public void translate(float offsetX, float offsetY)
```


يطبق متجه الإزاحة المحدد (offsetX و offsetY) على هذه Matrix عن طريق إلحاق متجه الإزاحة في البداية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| offsetX | float | قيمة x التي يتم بواسطتها إزاحة هذه المصفوفة. |
| offsetY | float | قيمة y التي يتم بواسطتها إزاحة هذه المصفوفة. |

### translate(float offsetX, float offsetY, int order) {#translate-float-float-int-}
```
public void translate(float offsetX, float offsetY, int order)
```


يطبق متجه الإزاحة المحدد على هذه Matrix بالترتيب المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| offsetX | float | قيمة x التي يتم بواسطتها إزاحة هذه المصفوفة. |
| offsetY | float | قيمة y التي يتم بواسطتها إزاحة هذه المصفوفة. |
| ترتيب | int | MatrixOrder الذي يحدد الترتيب (append أو prepend) الذي تُطبق به الإزاحة على هذه المصفوفة. |

### transformVectors(PointF[] pts) {#transformVectors-com.aspose.drawing.PointF---}
```
public void transformVectors(PointF[] pts)
```


يضرب كل متجه في مصفوفة بالمصفوفة. يتم تجاهل عناصر الإزاحة في هذه المصفوفة (الصف الثالث).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pts | [PointF\[\]](../../com.aspose.drawing/pointf) | مصفوفة من هياكل [PointF](../../com.aspose.drawing/pointf) تمثل النقاط التي سيتم تحويلها. |

### scale(float scaleX, float scaleY) {#scale-float-float-}
```
public void scale(float scaleX, float scaleY)
```


يطبق متجه المقياس المحدد على هذه Matrix عن طريق إلحاق متجه المقياس في البداية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| scaleX | float | القيمة التي يتم بها تكبير هذه المصفوفة في اتجاه المحور x. |
| scaleY | float | القيمة التي يتم من خلالها تحجيم هذه Matrix في اتجاه المحور ص. |

### scale(float scaleX, float scaleY, int order) {#scale-float-float-int-}
```
public void scale(float scaleX, float scaleY, int order)
```


يطبق متجه المقياس المحدد (scaleX و scaleY) على هذه Matrix باستخدام الترتيب المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| scaleX | float | القيمة التي يتم بها تكبير هذه المصفوفة في اتجاه المحور x. |
| scaleY | float | القيمة التي يتم من خلالها تحجيم هذه Matrix في اتجاه المحور ص. |
| ترتيب | int | كائن MatrixOrder يحدد الترتيب (إلحاق أو إلحاق مسبق) الذي يُطبق فيه متجه التحجيم على هذه Matrix. |

### shear(float shearX, float shearY) {#shear-float-float-}
```
public void shear(float shearX, float shearY)
```


يطبق متجه القص المحدد على هذه Matrix عن طريق إلحاق تحويل القص في البداية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| shearX | float | عامل القص الأفقي. |
| shearY | float | عامل القص العمودي. |

### shear(float shearX, float shearY, int order) {#shear-float-float-int-}
```
public void shear(float shearX, float shearY, int order)
```


يطبق متجه القص المحدد على هذه Matrix بالترتيب المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| shearX | float | عامل القص الأفقي. |
| shearY | float | عامل القص العمودي. |
| ترتيب | int | كائن MatrixOrder يحدد الترتيب (إلحاق أو إلحاق مسبق) الذي يُطبق فيه القص. |

### rotateAt(float angle, PointF point) {#rotateAt-float-com.aspose.drawing.PointF-}
```
public void rotateAt(float angle, PointF point)
```


يطبق دورانًا باتجاه عقارب الساعة على هذه Matrix حول النقطة المحددة في معامل point، وعن طريق إلحاق الدوران في البداية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| زاوية | float | زاوية (المد) الدوران، بالدرجات. |
| point | [PointF](../../com.aspose.drawing/pointf) | كائن PointF يمثل مركز الدوران. |

### rotateAt(float angle, PointF point, int order) {#rotateAt-float-com.aspose.drawing.PointF-int-}
```
public void rotateAt(float angle, PointF point, int order)
```


يطبق دورانًا باتجاه عقارب الساعة حول النقطة المحددة على هذه Matrix بالترتيب المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| زاوية | float | زاوية الدوران، بالدرجات. |
| point | [PointF](../../com.aspose.drawing/pointf) | كائن PointF يمثل مركز الدوران. |
| ترتيب | int | كائن MatrixOrder يحدد الترتيب (إلحاق أو إلحاق مسبق) الذي يُطبق فيه الدوران. |

### transformPoints(PointF[] pts) {#transformPoints-com.aspose.drawing.PointF---}
```
public void transformPoints(PointF[] pts)
```


يطبق التحويل الهندسي الممثل بواسطة هذه [Matrix](../../com.aspose.drawing.drawing2d/matrix) على مصفوفة محددة من النقاط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pts | [PointF\[\]](../../com.aspose.drawing/pointf) | مصفوفة من هياكل [PointF](../../com.aspose.drawing/pointf) تمثل النقاط التي سيتم تحويلها. |

### transformPoints(Point[] pts) {#transformPoints-com.aspose.drawing.Point---}
```
public void transformPoints(Point[] pts)
```


يطبق التحويل الهندسي الممثل بواسطة هذه [Matrix](../../com.aspose.drawing.drawing2d/matrix) على مصفوفة محددة من النقاط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pts | [Point\[\]](../../com.aspose.drawing/point) | مصفوفة من هياكل [Point](../../com.aspose.drawing/point) التي تمثل النقاط المراد تحويلها. |

### multiply(Matrix matrix) {#multiply-com.aspose.drawing.drawing2d.Matrix-}
```
public void multiply(Matrix matrix)
```


يضرب هذه [Matrix](../../com.aspose.drawing.drawing2d/matrix) في الـ matrix المحدد في معامل `matrix`، عن طريق إلحاق الـ [Matrix](../../com.aspose.drawing.drawing2d/matrix) المحدد في البداية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | الـ[Matrix](../../com.aspose.drawing.drawing2d/matrix) التي سيُضرب بها هذا الـ[Matrix](../../com.aspose.drawing.drawing2d/matrix). |

### multiply(Matrix matrix, int order) {#multiply-com.aspose.drawing.drawing2d.Matrix-int-}
```
public void multiply(Matrix matrix, int order)
```


يضرب هذه [Matrix](../../com.aspose.drawing.drawing2d/matrix) في الـ matrix المحدد في معامل `matrix`، وبالترتيب المحدد في معامل `order`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | الـ[Matrix](../../com.aspose.drawing.drawing2d/matrix) التي سيُضرب بها هذا الـ[Matrix](../../com.aspose.drawing.drawing2d/matrix). |
| order | int | الـ[MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder) التي تمثل ترتيب الضرب. |

### rotate(float angle) {#rotate-float-}
```
public void rotate(float angle)
```


ألحِق إلى هذه [Matrix](../../com.aspose.drawing.drawing2d/matrix) دورانًا باتجاه عقارب الساعة، حول الأصل وبالزاوية المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| زاوية | float | زاوية الدوران، بالدرجات. |

### rotate(float angle, int order) {#rotate-float-int-}
```
public void rotate(float angle, int order)
```


يطبق دورانًا باتجاه عقارب الساعة بمقدار محدد في معامل الزاوية، حول الأصل (إحداثيات x و y صفر) لهذه [Matrix](../../com.aspose.drawing.drawing2d/matrix).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| زاوية | float | زاوية الدوران، بالدرجات. |
| order | int | كائن [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder) يحدد الترتيب (إلحاق أو إلحاق مسبق) الذي يُطبق فيه الدوران على هذا الـ[Matrix](../../com.aspose.drawing.drawing2d/matrix). |

### reset() {#reset--}
```
public void reset()
```


يعيد ضبط هذه [Matrix](../../com.aspose.drawing.drawing2d/matrix) لتحتوي على عناصر مصفوفة الهوية.

