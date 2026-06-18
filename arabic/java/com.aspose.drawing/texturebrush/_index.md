---
title: TextureBrush
second_title: مرجع API لـ Aspose.Drawing للـ Java
description: كل خاصية في فئة TextureBrush هي كائن Brush يستخدم صورة لملء داخل الشكل.
type: docs
weight: 53
url: /ar/java/com.aspose.drawing/texturebrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.drawing.Brush](../../com.aspose.drawing/brush)
```
public final class TextureBrush extends Brush
```

كل خاصية في فئة TextureBrush هي كائن Brush يستخدم صورة لملء داخل الشكل. لا يمكن وراثة هذه الفئة.
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [TextureBrush(Image bitmap)](#TextureBrush-com.aspose.drawing.Image-) | ينشئ مثيلاً جديداً من الفئة [TextureBrush](../../com.aspose.drawing/texturebrush) التي تستخدم الصورة المحددة. |
| [TextureBrush(Image image, int wrapMode)](#TextureBrush-com.aspose.drawing.Image-int-) | ينشئ مثيلاً جديداً من الفئة [TextureBrush](../../com.aspose.drawing/texturebrush) التي تستخدم الصورة المحددة ووضع الالتفاف. |
| [TextureBrush(Image image, int wrapMode, RectangleF dstRect)](#TextureBrush-com.aspose.drawing.Image-int-com.aspose.drawing.RectangleF-) | ينشئ مثيلاً جديداً من الفئة [TextureBrush](../../com.aspose.drawing/texturebrush) التي تستخدم الصورة المحددة، وضع الالتفاف، والمستطيل المحيط. |
| [TextureBrush(Image image, RectangleF dstRect)](#TextureBrush-com.aspose.drawing.Image-com.aspose.drawing.RectangleF-) | يُنشئ مثيلاً جديدًا من الفئة [TextureBrush](../../com.aspose.drawing/texturebrush) التي تستخدم الصورة المحددة، ومستطيل الإحاطة. |
| [TextureBrush(Image image, RectangleF dstRect, ImageAttributes imageAttr)](#TextureBrush-com.aspose.drawing.Image-com.aspose.drawing.RectangleF-com.aspose.drawing.imaging.ImageAttributes-) | يُنشئ مثيلاً جديدًا من الفئة [TextureBrush](../../com.aspose.drawing/texturebrush) التي تستخدم الصورة المحددة، ومستطيل الإحاطة، وسمات الصورة. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getImage()](#getImage--) | يحصل على كائن Image المرتبط بهذا الكائن TextureBrush. |
| [getTransform()](#getTransform--) | يحصل على نسخة من كائن Matrix الذي يحدد تحويلًا هندسيًا محليًا للصورة المرتبطة بهذا الكائن TextureBrush. |
| [setTransform(Matrix value)](#setTransform-com.aspose.drawing.drawing2d.Matrix-) | يضبط نسخة من كائن Matrix الذي يحدد تحويلًا هندسيًا محليًا للصورة المرتبطة بهذا الكائن TextureBrush. |
| [getWrapMode()](#getWrapMode--) | يحصل على تعداد WrapMode الذي يحدد وضع الالتفاف لهذا الكائن TextureBrush. |
| [setWrapMode(int value)](#setWrapMode-int-) | يضبط تعداد WrapMode الذي يحدد وضع الالتفاف لهذا الكائن TextureBrush. |
| [deepClone()](#deepClone--) | ينشئ نسخة مطابقة من هذا الكائن [TextureBrush](../../com.aspose.drawing/texturebrush). |
| [resetTransform()](#resetTransform--) | يعيد تعيين خاصية Transform لهذا الكائن [TextureBrush](../../com.aspose.drawing/texturebrush) إلى الهوية. |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-) | يضرب كائن [Matrix](../../com.aspose.drawing.drawing2d/matrix) الذي يمثل التحويل الهندسي المحلي لهذا الكائن [TextureBrush](../../com.aspose.drawing/texturebrush) بكائن [Matrix](../../com.aspose.drawing.drawing2d/matrix) المحدد عن طريق إلحاق كائن [Matrix](../../com.aspose.drawing.drawing2d/matrix) المحدد في البداية. |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-int-) | يضرب كائن [Matrix](../../com.aspose.drawing.drawing2d/matrix) الذي يمثل التحويل الهندسي المحلي لهذا الكائن [TextureBrush](../../com.aspose.drawing/texturebrush) بكائن [Matrix](../../com.aspose.drawing.drawing2d/matrix) المحدد وفق الترتيب المحدد. |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | ينقل التحويل الهندسي المحلي لهذا الكائن [TextureBrush](../../com.aspose.drawing/texturebrush) بالأبعاد المحددة. |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | ينقل التحويل الهندسي المحلي لهذا الكائن [TextureBrush](../../com.aspose.drawing/texturebrush) بالأبعاد المحددة وفق الترتيب المحدد. |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | يقوم بتكبير التحويل الهندسي المحلي لهذا الكائن [TextureBrush](../../com.aspose.drawing/texturebrush) بالقيم المحددة. |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | يقوم بتكبير التحويل الهندسي المحلي لهذا الكائن [TextureBrush](../../com.aspose.drawing/texturebrush) بالقيم المحددة وفق الترتيب المحدد. |
| [rotateTransform(float angle)](#rotateTransform-float-) | يدور التحويل الهندسي المحلي لهذا الكائن [TextureBrush](../../com.aspose.drawing/texturebrush) بالكمية المحددة. |
| [rotateTransform(float angle, int order)](#rotateTransform-float-int-) | يدور التحويل الهندسي المحلي لهذا الكائن [TextureBrush](../../com.aspose.drawing/texturebrush) بالكمية المحددة وفق الترتيب المحدد. |
### TextureBrush(Image bitmap) {#TextureBrush-com.aspose.drawing.Image-}
```
public TextureBrush(Image bitmap)
```


ينشئ مثيلاً جديداً من الفئة [TextureBrush](../../com.aspose.drawing/texturebrush) التي تستخدم الصورة المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| bitmap | [Image](../../com.aspose.drawing/image) | كائن `Image`([.getImage](../../null/\#getImage)) الذي يستخدمه هذا الكائن [TextureBrush](../../com.aspose.drawing/texturebrush) لملء الداخل. |

### TextureBrush(Image image, int wrapMode) {#TextureBrush-com.aspose.drawing.Image-int-}
```
public TextureBrush(Image image, int wrapMode)
```


ينشئ مثيلاً جديداً من الفئة [TextureBrush](../../com.aspose.drawing/texturebrush) التي تستخدم الصورة المحددة ووضع الالتفاف.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| image | [Image](../../com.aspose.drawing/image) | الصورة. |
| wrapMode | int | `WrapMode`([.getWrapMode](../../null/\#getWrapMode)/[.setWrapMode(int)](../../null/\#setWrapMode-int-)) تعداد يحدد كيفية تجانب هذا الكائن [TextureBrush](../../com.aspose.drawing/texturebrush). |

### TextureBrush(Image image, int wrapMode, RectangleF dstRect) {#TextureBrush-com.aspose.drawing.Image-int-com.aspose.drawing.RectangleF-}
```
public TextureBrush(Image image, int wrapMode, RectangleF dstRect)
```


ينشئ مثيلاً جديداً من الفئة [TextureBrush](../../com.aspose.drawing/texturebrush) التي تستخدم الصورة المحددة، وضع الالتفاف، والمستطيل المحيط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| image | [Image](../../com.aspose.drawing/image) | الصورة. |
| wrapMode | int | `WrapMode`([.getWrapMode](../../null/\#getWrapMode)/[.setWrapMode(int)](../../null/\#setWrapMode-int-)) تعداد يحدد كيفية تجانب هذا الكائن [TextureBrush](../../com.aspose.drawing/texturebrush). |
| dstRect | [RectangleF](../../com.aspose.drawing/rectanglef) | [RectangleF](../../com.aspose.drawing/rectanglef) بنية تمثل مستطيل الإحاطة لهذا الكائن [TextureBrush](../../com.aspose.drawing/texturebrush). |

### TextureBrush(Image image, RectangleF dstRect) {#TextureBrush-com.aspose.drawing.Image-com.aspose.drawing.RectangleF-}
```
public TextureBrush(Image image, RectangleF dstRect)
```


يُنشئ مثيلاً جديدًا من الفئة [TextureBrush](../../com.aspose.drawing/texturebrush) التي تستخدم الصورة المحددة، ومستطيل الإحاطة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| image | [Image](../../com.aspose.drawing/image) | كائن `Image`([.getImage](../../null/\#getImage)) الذي يستخدمه هذا الكائن [TextureBrush](../../com.aspose.drawing/texturebrush) لملء الداخل. |
| dstRect | [RectangleF](../../com.aspose.drawing/rectanglef) | [RectangleF](../../com.aspose.drawing/rectanglef) بنية تمثل مستطيل الإحاطة لهذا الكائن [TextureBrush](../../com.aspose.drawing/texturebrush). |

### TextureBrush(Image image, RectangleF dstRect, ImageAttributes imageAttr) {#TextureBrush-com.aspose.drawing.Image-com.aspose.drawing.RectangleF-com.aspose.drawing.imaging.ImageAttributes-}
```
public TextureBrush(Image image, RectangleF dstRect, ImageAttributes imageAttr)
```


يُنشئ مثيلاً جديدًا من الفئة [TextureBrush](../../com.aspose.drawing/texturebrush) التي تستخدم الصورة المحددة، ومستطيل الإحاطة، وسمات الصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| image | [Image](../../com.aspose.drawing/image) | كائن Image الذي يستخدمه هذا الكائن TextureBrush لملء الداخل. |
| dstRect | [RectangleF](../../com.aspose.drawing/rectanglef) | بنية RectangleF تمثل مستطيل الإحاطة لهذا الكائن TextureBrush. |
| imageAttr | [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes) | كائن ImageAttributes يحتوي على معلومات إضافية حول الصورة المستخدمة بواسطة هذا الكائن TextureBrush. |

### getImage() {#getImage--}
```
public Image getImage()
```


يحصل على كائن Image المرتبط بهذا الكائن TextureBrush.

**Returns:**
[Image](../../com.aspose.drawing/image) - the Image object associated with this TextureBrush object.
### getTransform() {#getTransform--}
```
public Matrix getTransform()
```


يحصل على نسخة من كائن Matrix الذي يحدد تحويلًا هندسيًا محليًا للصورة المرتبطة بهذا الكائن TextureBrush.

**Returns:**
[Matrix](../../com.aspose.drawing.drawing2d/matrix) - a copy of the Matrix object that defines a local geometric transformation for the image associated with this TextureBrush object.
### setTransform(Matrix value) {#setTransform-com.aspose.drawing.drawing2d.Matrix-}
```
public void setTransform(Matrix value)
```


يضبط نسخة من كائن Matrix الذي يحدد تحويلًا هندسيًا محليًا للصورة المرتبطة بهذا الكائن TextureBrush.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | نسخة من كائن Matrix الذي يحدد تحويلًا هندسيًا محليًا للصورة المرتبطة بهذا الكائن TextureBrush. |

### getWrapMode() {#getWrapMode--}
```
public int getWrapMode()
```


يحصل على تعداد WrapMode الذي يحدد وضع الالتفاف لهذا الكائن TextureBrush.

**Returns:**
int - تعداد WrapMode الذي يحدد وضع الالتفاف لهذا الكائن TextureBrush.
### setWrapMode(int value) {#setWrapMode-int-}
```
public void setWrapMode(int value)
```


يضبط تعداد WrapMode الذي يحدد وضع الالتفاف لهذا الكائن TextureBrush.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int | تعداد WrapMode الذي يحدد وضع الالتفاف لهذا الكائن TextureBrush. |

### deepClone() {#deepClone--}
```
public Object deepClone()
```


ينشئ نسخة مطابقة من هذا الكائن [TextureBrush](../../com.aspose.drawing/texturebrush).

**Returns:**
java.lang.Object - الكائن [TextureBrush](../../com.aspose.drawing/texturebrush) الذي تنشئه هذه الطريقة، محول إلى كائن Object.
### resetTransform() {#resetTransform--}
```
public void resetTransform()
```


يعيد تعيين خاصية Transform لهذا الكائن [TextureBrush](../../com.aspose.drawing/texturebrush) إلى الهوية.

### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-}
```
public void multiplyTransform(Matrix matrix)
```


يضرب كائن [Matrix](../../com.aspose.drawing.drawing2d/matrix) الذي يمثل التحويل الهندسي المحلي لهذا الكائن [TextureBrush](../../com.aspose.drawing/texturebrush) بكائن [Matrix](../../com.aspose.drawing.drawing2d/matrix) المحدد عن طريق إلحاق كائن [Matrix](../../com.aspose.drawing.drawing2d/matrix) المحدد في البداية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | الكائن [Matrix](../../com.aspose.drawing.drawing2d/matrix) الذي يُستخدم لضرب التحويل الهندسي. |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-int-}
```
public void multiplyTransform(Matrix matrix, int order)
```


يضرب كائن [Matrix](../../com.aspose.drawing.drawing2d/matrix) الذي يمثل التحويل الهندسي المحلي لهذا الكائن [TextureBrush](../../com.aspose.drawing/texturebrush) بكائن [Matrix](../../com.aspose.drawing.drawing2d/matrix) المحدد وفق الترتيب المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | الكائن [Matrix](../../com.aspose.drawing.drawing2d/matrix) الذي يُستخدم لضرب التحويل الهندسي. |
| order | int | تعداد [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder) الذي يحدد الترتيب الذي يتم به ضرب المصفوفتين. |

### translateTransform(float dx, float dy) {#translateTransform-float-float-}
```
public void translateTransform(float dx, float dy)
```


يُترجم التحويل الهندسي المحلي لهذا الكائن [TextureBrush](../../com.aspose.drawing/texturebrush) بالأبعاد المحددة. تُضيف هذه الطريقة الترجمة إلى التحويل في البداية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| dx | float | البُعد الذي يُترجم به التحويل في الاتجاه x. |
| dy | float | البُعد الذي يُترجم به التحويل في الاتجاه y. |

### translateTransform(float dx, float dy, int order) {#translateTransform-float-float-int-}
```
public void translateTransform(float dx, float dy, int order)
```


ينقل التحويل الهندسي المحلي لهذا الكائن [TextureBrush](../../com.aspose.drawing/texturebrush) بالأبعاد المحددة وفق الترتيب المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| dx | float | البُعد الذي يُترجم به التحويل في الاتجاه x. |
| dy | float | البُعد الذي يُترجم به التحويل في الاتجاه y. |
| ترتيب | int | الترتيب (إضافة في البداية أو في النهاية) الذي يُطبق فيه الترجمة. |

### scaleTransform(float sx, float sy) {#scaleTransform-float-float-}
```
public void scaleTransform(float sx, float sy)
```


يقوم بتكبير التحويل الهندسي المحلي لهذا الكائن [TextureBrush](../../com.aspose.drawing/texturebrush) بالقيم المحددة. تُضيف هذه الطريقة مصفوفة التكبير إلى التحويل في البداية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| sx | float | القيمة التي يُكَبَّر بها التحويل في الاتجاه x. |
| sy | float | القيمة التي يُكَبَّر بها التحويل في الاتجاه y. |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public void scaleTransform(float sx, float sy, int order)
```


يقوم بتكبير التحويل الهندسي المحلي لهذا الكائن [TextureBrush](../../com.aspose.drawing/texturebrush) بالقيم المحددة وفق الترتيب المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| sx | float | القيمة التي يُكَبَّر بها التحويل في الاتجاه x. |
| sy | float | القيمة التي يُكَبَّر بها التحويل في الاتجاه y. |
| order | int | تعداد [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder) الذي يحدد ما إذا كان سيتم إلحاق مصفوفة التكبير أو إضافتها في البداية. |

### rotateTransform(float angle) {#rotateTransform-float-}
```
public void rotateTransform(float angle)
```


يدور التحويل الهندسي المحلي لهذا الكائن [TextureBrush](../../com.aspose.drawing/texturebrush) بالكمية المحددة. تُضيف هذه الطريقة دورانًا إلى التحويل في البداية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| زاوية | float | زاوية الدوران. |

### rotateTransform(float angle, int order) {#rotateTransform-float-int-}
```
public void rotateTransform(float angle, int order)
```


يدور التحويل الهندسي المحلي لهذا الكائن [TextureBrush](../../com.aspose.drawing/texturebrush) بالكمية المحددة وفق الترتيب المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| زاوية | float | زاوية الدوران. |
| order | int | تعداد [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder) الذي يحدد ما إذا كان سيتم إلحاق مصفوفة الدوران أو إضافتها في البداية. |

