---
title: Matrix
second_title: Aspose.Drawing for Java API संदर्भ
description: एक 3-बाय-3 अफाइन मैट्रिक्स को संलग्न करता है जो एक ज्यामितीय रूपांतरण का प्रतिनिधित्व करता है।
type: docs
weight: 33
url: /hi/java/com.aspose.drawing.drawing2d/matrix/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public final class Matrix implements System.IDisposable
```

एक 3x3 अफाइन मैट्रिक्स को संलग्न करता है जो एक ज्यामितीय रूपांतरण का प्रतिनिधित्व करता है। यह क्लास विरासत में नहीं ली जा सकती।
## निर्माता

| निर्माता | विवरण |
| --- | --- |
| [Matrix()](#Matrix--) | Matrix क्लास का एक नया इंस्टेंस पहचान मैट्रिक्स के रूप में आरंभ करता है। |
| [Matrix(float m11, float m12, float m21, float m22, float dx, float dy)](#Matrix-float-float-float-float-float-float-) | Matrix क्लास का एक नया इंस्टेंस निर्दिष्ट तत्वों के साथ आरंभ करता है। |
| [Matrix(Rectangle rect, Point[] plgpts)](#Matrix-com.aspose.drawing.Rectangle-com.aspose.drawing.Point---) | निर्दिष्ट आयत और बिंदुओं की सरणी द्वारा परिभाषित ज्यामितीय रूपांतरण के लिए [Matrix](../../com.aspose.drawing.drawing2d/matrix) क्लास का एक नया इंस्टेंस आरंभ करता है। |
| [Matrix(RectangleF rect, PointF[] plgpts)](#Matrix-com.aspose.drawing.RectangleF-com.aspose.drawing.PointF---) | निर्दिष्ट आयत और बिंदुओं की सरणी द्वारा परिभाषित ज्यामितीय रूपांतरण के लिए [Matrix](../../com.aspose.drawing.drawing2d/matrix) क्लास का एक नया इंस्टेंस आरंभ करता है। |
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [IdentityTransform](#IdentityTransform) |  |
## मेथड्स

| विधि | विवरण |
| --- | --- |
| [getElements()](#getElements--) | इस Matrix के तत्वों को दर्शाने वाले फ्लोटिंग पॉइंट मानों की एक सरणी प्राप्त करता है। |
| [isIdentity()](#isIdentity--) | एक मान प्राप्त करता है जो दर्शाता है कि यह Matrix पहचान मैट्रिक्स है या नहीं। |
| [isInvertible()](#isInvertible--) | एक मान प्राप्त करता है जो दर्शाता है कि यह Matrix उलटा किया जा सकता है या नहीं। |
| [getOffsetX()](#getOffsetX--) | इस Matrix का x ट्रांसलेशन मान प्राप्त करता है (dx मान, या तीसरी पंक्ति और पहले स्तंभ में तत्व)। |
| [getOffsetY()](#getOffsetY--) | इस Matrix का y ट्रांसलेशन मान प्राप्त करता है (`dy` मान, या तीसरी पंक्ति और दूसरे स्तंभ में तत्व)। |
| [dispose()](#dispose--) | इस Matrix द्वारा उपयोग किए गए सभी संसाधनों को मुक्त करता है। |
| [deepClone()](#deepClone--) | इस Matrix की एक सटीक प्रतिलिपि बनाता है। |
| [invert()](#invert--) | यदि यह उलटा किया जा सकता है, तो इस Matrix को उलटता है। |
| [translate(float offsetX, float offsetY)](#translate-float-float-) | निर्दिष्ट ट्रांसलेशन वेक्टर (offsetX और offsetY) को इस Matrix पर ट्रांसलेशन वेक्टर को पहले जोड़कर लागू करता है। |
| [translate(float offsetX, float offsetY, int order)](#translate-float-float-int-) | निर्दिष्ट क्रम में इस Matrix पर निर्दिष्ट ट्रांसलेशन वेक्टर लागू करता है। |
| [transformVectors(PointF[] pts)](#transformVectors-com.aspose.drawing.PointF---) | एक सरणी में प्रत्येक वेक्टर को matrix द्वारा गुणा करता है। |
| [scale(float scaleX, float scaleY)](#scale-float-float-) | निर्दिष्ट स्केल वेक्टर को इस Matrix पर स्केल वेक्टर को पहले जोड़कर लागू करता है। |
| [scale(float scaleX, float scaleY, int order)](#scale-float-float-int-) | निर्दिष्ट क्रम का उपयोग करके इस Matrix पर निर्दिष्ट स्केल वेक्टर (scaleX और scaleY) लागू करता है। |
| [shear(float shearX, float shearY)](#shear-float-float-) | निर्दिष्ट शीयर वेक्टर को इस Matrix पर शीयर ट्रांसफ़ॉर्मेशन को पहले जोड़कर लागू करता है। |
| [shear(float shearX, float shearY, int order)](#shear-float-float-int-) | निर्दिष्ट क्रम में इस Matrix पर निर्दिष्ट शीयर वेक्टर लागू करता है। |
| [rotateAt(float angle, PointF point)](#rotateAt-float-com.aspose.drawing.PointF-) | पॉइंट पैरामीटर में निर्दिष्ट बिंदु के चारों ओर इस Matrix पर घड़ी की दिशा में घूर्णन लागू करता है, और घूर्णन को पहले जोड़कर। |
| [rotateAt(float angle, PointF point, int order)](#rotateAt-float-com.aspose.drawing.PointF-int-) | निर्दिष्ट क्रम में निर्दिष्ट बिंदु के बारे में इस Matrix पर घड़ी की दिशा में घूर्णन लागू करता है। |
| [transformPoints(PointF[] pts)](#transformPoints-com.aspose.drawing.PointF---) | इस [Matrix](../../com.aspose.drawing.drawing2d/matrix) द्वारा प्रतिनिधित्व किए गए ज्यामितीय रूपांतरण को निर्दिष्ट बिंदुओं की सरणी पर लागू करता है। |
| [transformPoints(Point[] pts)](#transformPoints-com.aspose.drawing.Point---) | इस [Matrix](../../com.aspose.drawing.drawing2d/matrix) द्वारा प्रतिनिधित्व किए गए ज्यामितीय रूपांतरण को निर्दिष्ट बिंदुओं की सरणी पर लागू करता है। |
| [multiply(Matrix matrix)](#multiply-com.aspose.drawing.drawing2d.Matrix-) | इस [Matrix](../../com.aspose.drawing.drawing2d/matrix) को `matrix` पैरामीटर में निर्दिष्ट matrix द्वारा, निर्दिष्ट [Matrix](../../com.aspose.drawing.drawing2d/matrix) को पहले जोड़कर गुणा करता है। |
| [multiply(Matrix matrix, int order)](#multiply-com.aspose.drawing.drawing2d.Matrix-int-) | इस [Matrix](../../com.aspose.drawing.drawing2d/matrix) को `matrix` पैरामीटर में निर्दिष्ट matrix द्वारा, और `order` पैरामीटर में निर्दिष्ट क्रम में गुणा करता है। |
| [rotate(float angle)](#rotate-float-) | इस [Matrix](../../com.aspose.drawing.drawing2d/matrix) में मूल बिंदु के चारों ओर और निर्दिष्ट कोण द्वारा घड़ी की दिशा में घूर्णन को पहले जोड़ें। |
| [rotate(float angle, int order)](#rotate-float-int-) | कोण पैरामीटर में निर्दिष्ट मात्रा के घड़ी की दिशा में घूर्णन को मूल बिंदु (शून्य x और y निर्देशांक) के चारों ओर इस [Matrix](../../com.aspose.drawing.drawing2d/matrix) के लिए लागू करता है। |
| [reset()](#reset--) | इस [Matrix](../../com.aspose.drawing.drawing2d/matrix) को पहचान मैट्रिक्स के तत्वों के साथ रीसेट करता है। |
### Matrix() {#Matrix--}
```
public Matrix()
```


Matrix क्लास का एक नया इंस्टेंस पहचान मैट्रिक्स के रूप में आरंभ करता है।

### Matrix(float m11, float m12, float m21, float m22, float dx, float dy) {#Matrix-float-float-float-float-float-float-}
```
public Matrix(float m11, float m12, float m21, float m22, float dx, float dy)
```


Matrix क्लास का एक नया इंस्टेंस निर्दिष्ट तत्वों के साथ आरंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| m11 | फ़्लोट | नए Matrix की पहली पंक्ति और पहले स्तंभ में मान। |
| m12 | फ़्लोट | नए Matrix की पहली पंक्ति और दूसरे स्तंभ में मान। |
| m21 | फ़्लोट | नए मैट्रिक्स की दूसरी पंक्ति और पहले कॉलम में मान। |
| m22 | फ़्लोट | नए मैट्रिक्स की दूसरी पंक्ति और दूसरे कॉलम में मान। |
| dx | फ़्लोट | नए मैट्रिक्स की तीसरी पंक्ति और पहले कॉलम में मान। |
| dy | फ़्लोट | नए मैट्रिक्स की तीसरी पंक्ति और दूसरे कॉलम में मान। |

### Matrix(Rectangle rect, Point[] plgpts) {#Matrix-com.aspose.drawing.Rectangle-com.aspose.drawing.Point---}
```
public Matrix(Rectangle rect, Point[] plgpts)
```


निर्दिष्ट आयत और बिंदुओं की सरणी द्वारा परिभाषित ज्यामितीय रूपांतरण के लिए [Matrix](../../com.aspose.drawing.drawing2d/matrix) क्लास का एक नया इंस्टेंस आरंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | एक [Rectangle](../../com.aspose.drawing/rectangle) संरचना जो परिवर्तित किए जाने वाले आयत को दर्शाती है। |
| plgpts | [Point\[\]](../../com.aspose.drawing/point) | तीन [Point](../../com.aspose.drawing/point) संरचनाओं की एक सरणी जो उस समानांतर चतुर्भुज के बिंदुओं को दर्शाती है, जिसमें आयत के ऊपर-बाएँ, ऊपर-दाएँ और नीचे-बाएँ कोनों को परिवर्तित किया जाएगा। समानांतर चतुर्भुज का नीचे-दायाँ कोना पहले तीन कोनों द्वारा निहित है। |

### Matrix(RectangleF rect, PointF[] plgpts) {#Matrix-com.aspose.drawing.RectangleF-com.aspose.drawing.PointF---}
```
public Matrix(RectangleF rect, PointF[] plgpts)
```


निर्दिष्ट आयत और बिंदुओं की सरणी द्वारा परिभाषित ज्यामितीय रूपांतरण के लिए [Matrix](../../com.aspose.drawing.drawing2d/matrix) क्लास का एक नया इंस्टेंस आरंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | एक [RectangleF](../../com.aspose.drawing/rectanglef) संरचना जो परिवर्तित किए जाने वाले आयत को दर्शाती है। |
| plgpts | [PointF\[\]](../../com.aspose.drawing/pointf) | तीन [PointF](../../com.aspose.drawing/pointf) संरचनाओं की एक सरणी जो उस समानांतर चतुर्भुज के बिंदुओं को दर्शाती है, जिसमें आयत के ऊपर-बाएँ, ऊपर-दाएँ और नीचे-बाएँ कोनों को परिवर्तित किया जाएगा। समानांतर चतुर्भुज का नीचे-दायाँ कोना पहले तीन कोनों द्वारा निहित है। |

### IdentityTransform {#IdentityTransform}
```
public static final Matrix IdentityTransform
```


### getElements() {#getElements--}
```
public float[] getElements()
```


इस Matrix के तत्वों को दर्शाने वाले फ्लोटिंग पॉइंट मानों की एक सरणी प्राप्त करता है।

**Returns:**
float[] - फ्लोटिंग-पॉइंट मानों की एक सरणी जो इस मैट्रिक्स के तत्वों को दर्शाती है।
### isIdentity() {#isIdentity--}
```
public boolean isIdentity()
```


एक मान प्राप्त करता है जो दर्शाता है कि यह Matrix पहचान मैट्रिक्स है या नहीं।

**Returns:**
boolean - एक मान जो दर्शाता है कि यह मैट्रिक्स पहचान (identity) मैट्रिक्स है या नहीं।
### isInvertible() {#isInvertible--}
```
public boolean isInvertible()
```


एक मान प्राप्त करता है जो दर्शाता है कि यह Matrix उलटा किया जा सकता है या नहीं।

**Returns:**
boolean - एक मान जो दर्शाता है कि यह मैट्रिक्स उलटा (invertible) किया जा सकता है या नहीं।
### getOffsetX() {#getOffsetX--}
```
public float getOffsetX()
```


इस Matrix का x ट्रांसलेशन मान प्राप्त करता है (dx मान, या तीसरी पंक्ति और पहले स्तंभ में तत्व)।

**Returns:**
float - इस मैट्रिक्स का x अनुवाद मान (dx मान, या तीसरी पंक्ति और पहले कॉलम में तत्व)।
### getOffsetY() {#getOffsetY--}
```
public float getOffsetY()
```


इस Matrix का y ट्रांसलेशन मान प्राप्त करता है (`dy` मान, या तीसरी पंक्ति और दूसरे स्तंभ में तत्व)।

**Returns:**
float - इस मैट्रिक्स का y अनुवाद मान ( `dy` मान, या तीसरी पंक्ति और दूसरे कॉलम में तत्व)।
### dispose() {#dispose--}
```
public void dispose()
```


इस Matrix द्वारा उपयोग किए गए सभी संसाधनों को मुक्त करता है।

--------------------

यह मेथड वास्तव में कुछ नहीं करता। यह केवल System.Drawing API के साथ संगतता के लिए है।

### deepClone() {#deepClone--}
```
public Matrix deepClone()
```


इस Matrix की एक सटीक प्रतिलिपि बनाता है।

**Returns:**
[Matrix](../../com.aspose.drawing.drawing2d/matrix) - The Matrix that this method creates.
### invert() {#invert--}
```
public void invert()
```


यदि यह उलटा किया जा सकता है, तो इस Matrix को उलटता है।

### translate(float offsetX, float offsetY) {#translate-float-float-}
```
public void translate(float offsetX, float offsetY)
```


निर्दिष्ट ट्रांसलेशन वेक्टर (offsetX और offsetY) को इस Matrix पर ट्रांसलेशन वेक्टर को पहले जोड़कर लागू करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| offsetX | फ़्लोट | इस मैट्रिक्स को अनुवादित करने के लिए x मान। |
| offsetY | फ़्लोट | इस मैट्रिक्स को अनुवादित करने के लिए y मान। |

### translate(float offsetX, float offsetY, int order) {#translate-float-float-int-}
```
public void translate(float offsetX, float offsetY, int order)
```


निर्दिष्ट क्रम में इस Matrix पर निर्दिष्ट ट्रांसलेशन वेक्टर लागू करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| offsetX | फ़्लोट | इस मैट्रिक्स को अनुवादित करने के लिए x मान। |
| offsetY | फ़्लोट | इस मैट्रिक्स को अनुवादित करने के लिए y मान। |
| क्रम | int | एक MatrixOrder जो इस मैट्रिक्स पर अनुवाद लागू करने के क्रम (append या prepend) को निर्दिष्ट करता है। |

### transformVectors(PointF[] pts) {#transformVectors-com.aspose.drawing.PointF---}
```
public void transformVectors(PointF[] pts)
```


एक सरणी में प्रत्येक वेक्टर को मैट्रिक्स से गुणा करता है। इस मैट्रिक्स के अनुवाद तत्व (तीसरी पंक्ति) को नजरअंदाज किया जाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pts | [PointF\[\]](../../com.aspose.drawing/pointf) | [PointF](../../com.aspose.drawing/pointf) संरचनाओं की एक सरणी जो परिवर्तित किए जाने वाले बिंदुओं को दर्शाती है। |

### scale(float scaleX, float scaleY) {#scale-float-float-}
```
public void scale(float scaleX, float scaleY)
```


निर्दिष्ट स्केल वेक्टर को इस Matrix पर स्केल वेक्टर को पहले जोड़कर लागू करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| scaleX | फ़्लोट | इस मैट्रिक्स को x-अक्ष दिशा में स्केल करने का मान। |
| scaleY | फ़्लोट | y‑अक्ष दिशा में इस मैट्रिक्स को स्केल करने के लिए मान। |

### scale(float scaleX, float scaleY, int order) {#scale-float-float-int-}
```
public void scale(float scaleX, float scaleY, int order)
```


निर्दिष्ट क्रम का उपयोग करके इस Matrix पर निर्दिष्ट स्केल वेक्टर (scaleX और scaleY) लागू करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| scaleX | फ़्लोट | इस मैट्रिक्स को x-अक्ष दिशा में स्केल करने का मान। |
| scaleY | फ़्लोट | y‑अक्ष दिशा में इस मैट्रिक्स को स्केल करने के लिए मान। |
| क्रम | int | एक MatrixOrder जो यह निर्दिष्ट करता है कि स्केल वेक्टर इस मैट्रिक्स पर किस क्रम (ऐपेंड या प्रीपेंड) में लागू किया जाता है। |

### shear(float shearX, float shearY) {#shear-float-float-}
```
public void shear(float shearX, float shearY)
```


निर्दिष्ट शीयर वेक्टर को इस Matrix पर शीयर ट्रांसफ़ॉर्मेशन को पहले जोड़कर लागू करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| shearX | फ़्लोट | क्षैतिज शियर कारक। |
| shearY | फ़्लोट | ऊर्ध्वाधर शियर कारक। |

### shear(float shearX, float shearY, int order) {#shear-float-float-int-}
```
public void shear(float shearX, float shearY, int order)
```


निर्दिष्ट क्रम में इस Matrix पर निर्दिष्ट शीयर वेक्टर लागू करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| shearX | फ़्लोट | क्षैतिज शियर कारक। |
| shearY | फ़्लोट | ऊर्ध्वाधर शियर कारक। |
| क्रम | int | एक MatrixOrder जो यह निर्दिष्ट करता है कि शियर किस क्रम (ऐपेंड या प्रीपेंड) में लागू किया जाता है। |

### rotateAt(float angle, PointF point) {#rotateAt-float-com.aspose.drawing.PointF-}
```
public void rotateAt(float angle, PointF point)
```


पॉइंट पैरामीटर में निर्दिष्ट बिंदु के चारों ओर इस Matrix पर घड़ी की दिशा में घूर्णन लागू करता है, और घूर्णन को पहले जोड़कर।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| कोण | फ़्लोट | घूर्णन का कोण (परिमाण), डिग्री में। |
| point | [PointF](../../com.aspose.drawing/pointf) | एक PointF जो घूर्णन के केंद्र को दर्शाता है। |

### rotateAt(float angle, PointF point, int order) {#rotateAt-float-com.aspose.drawing.PointF-int-}
```
public void rotateAt(float angle, PointF point, int order)
```


निर्दिष्ट क्रम में निर्दिष्ट बिंदु के बारे में इस Matrix पर घड़ी की दिशा में घूर्णन लागू करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| कोण | फ़्लोट | घूर्णन का कोण, डिग्री में। |
| point | [PointF](../../com.aspose.drawing/pointf) | एक PointF जो घूर्णन के केंद्र को दर्शाता है। |
| क्रम | int | एक MatrixOrder जो यह निर्दिष्ट करता है कि घूर्णन किस क्रम (ऐपेंड या प्रीपेंड) में लागू किया जाता है। |

### transformPoints(PointF[] pts) {#transformPoints-com.aspose.drawing.PointF---}
```
public void transformPoints(PointF[] pts)
```


इस [Matrix](../../com.aspose.drawing.drawing2d/matrix) द्वारा प्रतिनिधित्व किए गए ज्यामितीय रूपांतरण को निर्दिष्ट बिंदुओं की सरणी पर लागू करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pts | [PointF\[\]](../../com.aspose.drawing/pointf) | [PointF](../../com.aspose.drawing/pointf) संरचनाओं की एक सरणी जो परिवर्तित किए जाने वाले बिंदुओं को दर्शाती है। |

### transformPoints(Point[] pts) {#transformPoints-com.aspose.drawing.Point---}
```
public void transformPoints(Point[] pts)
```


इस [Matrix](../../com.aspose.drawing.drawing2d/matrix) द्वारा प्रतिनिधित्व किए गए ज्यामितीय रूपांतरण को निर्दिष्ट बिंदुओं की सरणी पर लागू करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pts | [Point\[\]](../../com.aspose.drawing/point) | एक एरे जिसमें [Point](../../com.aspose.drawing/point) संरचनाएँ हैं जो रूपांतरित करने वाले बिंदुओं को दर्शाती हैं। |

### multiply(Matrix matrix) {#multiply-com.aspose.drawing.drawing2d.Matrix-}
```
public void multiply(Matrix matrix)
```


इस [Matrix](../../com.aspose.drawing.drawing2d/matrix) को `matrix` पैरामीटर में निर्दिष्ट matrix द्वारा, निर्दिष्ट [Matrix](../../com.aspose.drawing.drawing2d/matrix) को पहले जोड़कर गुणा करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | वह [Matrix](../../com.aspose.drawing.drawing2d/matrix) जिससे इस [Matrix](../../com.aspose.drawing.drawing2d/matrix) को गुणा किया जाना है। |

### multiply(Matrix matrix, int order) {#multiply-com.aspose.drawing.drawing2d.Matrix-int-}
```
public void multiply(Matrix matrix, int order)
```


इस [Matrix](../../com.aspose.drawing.drawing2d/matrix) को `matrix` पैरामीटर में निर्दिष्ट matrix द्वारा, और `order` पैरामीटर में निर्दिष्ट क्रम में गुणा करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | वह [Matrix](../../com.aspose.drawing.drawing2d/matrix) जिससे इस [Matrix](../../com.aspose.drawing.drawing2d/matrix) को गुणा किया जाना है। |
| order | int | वह [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder) जो गुणा के क्रम को दर्शाता है। |

### rotate(float angle) {#rotate-float-}
```
public void rotate(float angle)
```


इस [Matrix](../../com.aspose.drawing.drawing2d/matrix) में मूल बिंदु के चारों ओर और निर्दिष्ट कोण द्वारा घड़ी की दिशा में घूर्णन को पहले जोड़ें।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| कोण | फ़्लोट | घूर्णन का कोण, डिग्री में। |

### rotate(float angle, int order) {#rotate-float-int-}
```
public void rotate(float angle, int order)
```


कोण पैरामीटर में निर्दिष्ट मात्रा के घड़ी की दिशा में घूर्णन को मूल बिंदु (शून्य x और y निर्देशांक) के चारों ओर इस [Matrix](../../com.aspose.drawing.drawing2d/matrix) के लिए लागू करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| कोण | फ़्लोट | घूर्णन का कोण, डिग्री में। |
| order | int | एक [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder) जो यह निर्दिष्ट करता है कि इस [Matrix](../../com.aspose.drawing.drawing2d/matrix) पर घूर्णन किस क्रम (ऐपेंड या प्रीपेंड) में लागू किया जाता है। |

### reset() {#reset--}
```
public void reset()
```


इस [Matrix](../../com.aspose.drawing.drawing2d/matrix) को पहचान मैट्रिक्स के तत्वों के साथ रीसेट करता है।

