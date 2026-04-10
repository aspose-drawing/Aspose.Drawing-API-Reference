---
title: LinearGradientBrush
second_title: Aspose.Drawing for Java API संदर्भ
description: एक रैखिक ग्रेडिएंट के साथ एक को संलग्न करता है।
type: docs
weight: 31
url: /hi/java/com.aspose.drawing.drawing2d/lineargradientbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.drawing.Brush](../../com.aspose.drawing/brush)
```
public final class LinearGradientBrush extends Brush
```

एक [Brush](../../com.aspose.drawing/brush) को रैखिक ग्रेडिएंट के साथ संलग्न करता है। यह क्लास विरासत में नहीं ली जा सकती।
## निर्माता

| निर्माता | विवरण |
| --- | --- |
| [LinearGradientBrush(PointF point1, PointF point2, Color color1, Color color2)](#LinearGradientBrush-com.aspose.drawing.PointF-com.aspose.drawing.PointF-com.aspose.drawing.Color-com.aspose.drawing.Color-) | निर्दिष्ट बिंदुओं और रंगों के साथ [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है। |
| [LinearGradientBrush(Point point1, Point point2, Color color1, Color color2)](#LinearGradientBrush-com.aspose.drawing.Point-com.aspose.drawing.Point-com.aspose.drawing.Color-com.aspose.drawing.Color-) | निर्दिष्ट बिंदुओं और रंगों के साथ [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है। |
| [LinearGradientBrush(RectangleF rect, Color color1, Color color2, int linearGradientMode)](#LinearGradientBrush-com.aspose.drawing.RectangleF-com.aspose.drawing.Color-com.aspose.drawing.Color-int-) | एक आयत, प्रारंभिक और समाप्ति रंग, और एक अभिविन्यास मोड के आधार पर [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है। |
| [LinearGradientBrush(Rectangle rect, Color color1, Color color2, int linearGradientMode)](#LinearGradientBrush-com.aspose.drawing.Rectangle-com.aspose.drawing.Color-com.aspose.drawing.Color-int-) | एक आयत, प्रारंभिक और समाप्ति रंग, और अभिविन्यास के आधार पर [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है। |
| [LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle)](#LinearGradientBrush-com.aspose.drawing.RectangleF-com.aspose.drawing.Color-com.aspose.drawing.Color-float-) | एक आयत, प्रारंभिक और समाप्ति रंग, और अभिविन्यास कोण के आधार पर [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है। |
| [LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle, boolean isAngleScaleable)](#LinearGradientBrush-com.aspose.drawing.RectangleF-com.aspose.drawing.Color-com.aspose.drawing.Color-float-boolean-) | एक आयत, प्रारंभिक और समाप्ति रंग, और अभिविन्यास कोण के आधार पर [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है। |
| [LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle)](#LinearGradientBrush-com.aspose.drawing.Rectangle-com.aspose.drawing.Color-com.aspose.drawing.Color-float-) | एक आयत, प्रारंभिक और समाप्ति रंग, और अभिविन्यास कोण के आधार पर [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है। |
| [LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle, boolean isAngleScaleable)](#LinearGradientBrush-com.aspose.drawing.Rectangle-com.aspose.drawing.Color-com.aspose.drawing.Color-float-boolean-) | एक आयत, प्रारंभिक और समाप्ति रंग, और अभिविन्यास कोण के आधार पर [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है। |
## मेथड्स

| विधि | विवरण |
| --- | --- |
| [getLinearColors()](#getLinearColors--) | ग्रेडिएंट के प्रारंभिक और समाप्ति रंगों को प्राप्त करता है या सेट करता है। |
| [setLinearColors(Color[] value)](#setLinearColors-com.aspose.drawing.Color---) | ग्रेडिएंट के प्रारंभिक और समाप्ति रंगों को प्राप्त करता है या सेट करता है। |
| [getRectangle()](#getRectangle--) | एक आयताकार रीजन प्राप्त करता है जो ग्रेडिएंट के प्रारंभिक और समाप्ति बिंदुओं को परिभाषित करता है। |
| [getGammaCorrection()](#getGammaCorrection--) | इस [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) के लिए यह दर्शाने वाला मान प्राप्त करता है या सेट करता है कि गामा सुधार सक्षम है या नहीं। |
| [setGammaCorrection(boolean value)](#setGammaCorrection-boolean-) | इस [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) के लिए यह दर्शाने वाला मान प्राप्त करता है या सेट करता है कि गामा सुधार सक्षम है या नहीं। |
| [getBlend()](#getBlend--) | एक `Blend`([.getBlend](../../null/\#getBlend)/[.setBlend(Blend)](../../null/\#setBlend-Blend-)) प्राप्त करता है या सेट करता है जो ग्रेडिएंट के लिए कस्टम फॉलऑफ़ को परिभाषित करने वाले स्थितियों और कारकों को निर्दिष्ट करता है। |
| [setBlend(Blend value)](#setBlend-com.aspose.drawing.drawing2d.Blend-) | एक `Blend`([.getBlend](../../null/\#getBlend)/[.setBlend(Blend)](../../null/\#setBlend-Blend-)) प्राप्त करता है या सेट करता है जो ग्रेडिएंट के लिए कस्टम फॉलऑफ़ को परिभाषित करने वाले स्थितियों और कारकों को निर्दिष्ट करता है। |
| [getInterpolationColors()](#getInterpolationColors--) | एक [ColorBlend](../../com.aspose.drawing.drawing2d/colorblend) प्राप्त करता है या सेट करता है जो बहु-रंगीय रैखिक ग्रेडिएंट को परिभाषित करता है। |
| [setInterpolationColors(ColorBlend value)](#setInterpolationColors-com.aspose.drawing.drawing2d.ColorBlend-) | एक [ColorBlend](../../com.aspose.drawing.drawing2d/colorblend) प्राप्त करता है या सेट करता है जो बहु-रंगीय रैखिक ग्रेडिएंट को परिभाषित करता है। |
| [getWrapMode()](#getWrapMode--) | एक `WrapMode` एनीमरेशन प्राप्त करता है या सेट करता है जो इस [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) के रैप मोड को दर्शाता है। |
| [setWrapMode(int value)](#setWrapMode-int-) | एक `WrapMode` एनीमरेशन प्राप्त करता है या सेट करता है जो इस [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) के रैप मोड को दर्शाता है। |
| [getTransform()](#getTransform--) | एक कॉपी [Matrix](../../com.aspose.drawing.drawing2d/matrix) प्राप्त करता है या सेट करता है जो इस [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) के लिए स्थानीय ज्यामितीय रूपांतरण को परिभाषित करती है। |
| [setTransform(Matrix value)](#setTransform-com.aspose.drawing.drawing2d.Matrix-) | एक कॉपी [Matrix](../../com.aspose.drawing.drawing2d/matrix) प्राप्त करता है या सेट करता है जो इस [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) के लिए स्थानीय ज्यामितीय रूपांतरण को परिभाषित करती है। |
| [deepClone()](#deepClone--) | इस [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) की एक सटीक कॉपी बनाता है। |
| [setSigmaBellShape(float focus)](#setSigmaBellShape-float-) | घंटी-आकार की वक्र पर आधारित ग्रेडिएंट फॉलऑफ़ बनाता है। |
| [setSigmaBellShape(float focus, float scale)](#setSigmaBellShape-float-float-) | घंटी-आकार की वक्र पर आधारित ग्रेडिएंट फॉलऑफ़ बनाता है। |
| [setBlendTriangularShape(float focus)](#setBlendTriangularShape-float-) | एक रैखिक ग्रेडिएंट बनाता है जिसमें मध्य रंग और दोनों सिरों पर एकल रंग की रैखिक फॉलऑफ़ होती है। |
| [setBlendTriangularShape(float focus, float scale)](#setBlendTriangularShape-float-float-) | एक रैखिक ग्रेडिएंट बनाता है जिसमें मध्य रंग और दोनों सिरों पर एकल रंग की रैखिक फॉलऑफ़ होती है। |
| [resetTransform()](#resetTransform--) | `LinearGradientBrush.Transform` प्रॉपर्टी को पहचान (identity) पर रीसेट करता है। |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-) | इस [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) के स्थानीय ज्यामितीय रूपांतरण को दर्शाने वाले [Matrix](../../com.aspose.drawing.drawing2d/matrix) को निर्दिष्ट [Matrix](../../com.aspose.drawing.drawing2d/matrix) द्वारा, निर्दिष्ट [Matrix](../../com.aspose.drawing.drawing2d/matrix) को पहले जोड़कर, गुणा करता है। |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-int-) | इस [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) के स्थानीय ज्यामितीय रूपांतरण को दर्शाने वाले [Matrix](../../com.aspose.drawing.drawing2d/matrix) को निर्दिष्ट [Matrix](../../com.aspose.drawing.drawing2d/matrix) के साथ निर्दिष्ट क्रम में गुणा करता है। |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | निर्दिष्ट आयामों द्वारा स्थानीय ज्यामितीय रूपांतरण को अनुवादित करता है। |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | निर्दिष्ट क्रम में निर्दिष्ट आयामों द्वारा स्थानीय ज्यामितीय रूपांतरण को अनुवादित करता है। |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | निर्दिष्ट मात्रा द्वारा स्थानीय ज्यामितीय रूपांतरण को स्केल करता है। |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | निर्दिष्ट क्रम में निर्दिष्ट मात्रा द्वारा स्थानीय ज्यामितीय रूपांतरण को स्केल करता है। |
| [rotateTransform(float angle)](#rotateTransform-float-) | निर्दिष्ट मात्रा द्वारा स्थानीय ज्यामितीय रूपांतरण को घुमाता है। |
| [rotateTransform(float angle, int order)](#rotateTransform-float-int-) | निर्दिष्ट क्रम में निर्दिष्ट मात्रा द्वारा स्थानीय ज्यामितीय रूपांतरण को घुमाता है। |
### LinearGradientBrush(PointF point1, PointF point2, Color color1, Color color2) {#LinearGradientBrush-com.aspose.drawing.PointF-com.aspose.drawing.PointF-com.aspose.drawing.Color-com.aspose.drawing.Color-}
```
public LinearGradientBrush(PointF point1, PointF point2, Color color1, Color color2)
```


निर्दिष्ट बिंदुओं और रंगों के साथ [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| point1 | [PointF](../../com.aspose.drawing/pointf) | एक [PointF](../../com.aspose.drawing/pointf) संरचना जो रैखिक ग्रेडिएंट के प्रारंभिक बिंदु को दर्शाती है। |
| point2 | [PointF](../../com.aspose.drawing/pointf) | एक [PointF](../../com.aspose.drawing/pointf) संरचना जो रैखिक ग्रेडिएंट के अंत बिंदु को दर्शाती है। |
| color1 | [Color](../../com.aspose.drawing/color) | एक [Color](../../com.aspose.drawing/color) संरचना जो रैखिक ग्रेडिएंट के प्रारंभिक रंग को दर्शाती है। |
| color2 | [Color](../../com.aspose.drawing/color) | एक [Color](../../com.aspose.drawing/color) संरचना जो रैखिक ग्रेडिएंट के समाप्ति रंग को दर्शाती है। |

### LinearGradientBrush(Point point1, Point point2, Color color1, Color color2) {#LinearGradientBrush-com.aspose.drawing.Point-com.aspose.drawing.Point-com.aspose.drawing.Color-com.aspose.drawing.Color-}
```
public LinearGradientBrush(Point point1, Point point2, Color color1, Color color2)
```


निर्दिष्ट बिंदुओं और रंगों के साथ [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.drawing/point) | एक [Point](../../com.aspose.drawing/point) संरचना जो रैखिक ग्रेडिएंट के प्रारंभिक बिंदु को दर्शाती है। |
| point2 | [Point](../../com.aspose.drawing/point) | एक [Point](../../com.aspose.drawing/point) संरचना जो रैखिक ग्रेडिएंट के अंत बिंदु को दर्शाती है। |
| color1 | [Color](../../com.aspose.drawing/color) | एक [Color](../../com.aspose.drawing/color) संरचना जो रैखिक ग्रेडिएंट के प्रारंभिक रंग को दर्शाती है। |
| color2 | [Color](../../com.aspose.drawing/color) | एक [Color](../../com.aspose.drawing/color) संरचना जो रैखिक ग्रेडिएंट के समाप्ति रंग को दर्शाती है। |

### LinearGradientBrush(RectangleF rect, Color color1, Color color2, int linearGradientMode) {#LinearGradientBrush-com.aspose.drawing.RectangleF-com.aspose.drawing.Color-com.aspose.drawing.Color-int-}
```
public LinearGradientBrush(RectangleF rect, Color color1, Color color2, int linearGradientMode)
```


एक आयत, प्रारंभिक और समाप्ति रंग, और एक अभिविन्यास मोड के आधार पर [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | एक [RectangleF](../../com.aspose.drawing/rectanglef) संरचना जो रैखिक ग्रेडिएंट की सीमाओं को निर्दिष्ट करती है। |
| color1 | [Color](../../com.aspose.drawing/color) | एक [Color](../../com.aspose.drawing/color) संरचना जो ग्रेडिएंट के प्रारंभिक रंग को दर्शाती है। |
| color2 | [Color](../../com.aspose.drawing/color) | एक [Color](../../com.aspose.drawing/color) संरचना जो ग्रेडिएंट के अंतिम रंग का प्रतिनिधित्व करती है। |
| linearGradientMode | int | एक [LinearGradientMode](../../com.aspose.drawing.drawing2d/lineargradientmode) enumeration तत्व जो ग्रेडिएंट की अभिविन्यास को निर्दिष्ट करता है। अभिविन्यास ग्रेडिएंट के प्रारंभिक और अंतिम बिंदुओं को निर्धारित करता है। उदाहरण के लिए, LinearGradientMode.ForwardDiagonal यह निर्दिष्ट करता है कि प्रारंभिक बिंदु आयत के ऊपर-बाएँ कोने में है और अंतिम बिंदु नीचे-दाएँ कोने में है। |

### LinearGradientBrush(Rectangle rect, Color color1, Color color2, int linearGradientMode) {#LinearGradientBrush-com.aspose.drawing.Rectangle-com.aspose.drawing.Color-com.aspose.drawing.Color-int-}
```
public LinearGradientBrush(Rectangle rect, Color color1, Color color2, int linearGradientMode)
```


एक आयत, प्रारंभिक और समाप्ति रंग, और अभिविन्यास के आधार पर [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | एक `Rectangle`([.getRectangle](../../null/\#getRectangle)) संरचना जो रैखिक ग्रेडिएंट की सीमाओं को निर्दिष्ट करती है। |
| color1 | [Color](../../com.aspose.drawing/color) | एक [Color](../../com.aspose.drawing/color) संरचना जो ग्रेडिएंट के प्रारंभिक रंग को दर्शाती है। |
| color2 | [Color](../../com.aspose.drawing/color) | एक [Color](../../com.aspose.drawing/color) संरचना जो ग्रेडिएंट के अंतिम रंग का प्रतिनिधित्व करती है। |
| linearGradientMode | int | एक [LinearGradientMode](../../com.aspose.drawing.drawing2d/lineargradientmode) enumeration तत्व जो ग्रेडिएंट की अभिविन्यास को निर्दिष्ट करता है। अभिविन्यास ग्रेडिएंट के प्रारंभिक और अंतिम बिंदुओं को निर्धारित करता है। उदाहरण के लिए, LinearGradientMode.ForwardDiagonal यह निर्दिष्ट करता है कि प्रारंभिक बिंदु आयत के ऊपर-बाएँ कोने में है और अंतिम बिंदु नीचे-दाएँ कोने में है। |

### LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle) {#LinearGradientBrush-com.aspose.drawing.RectangleF-com.aspose.drawing.Color-com.aspose.drawing.Color-float-}
```
public LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle)
```


एक आयत, प्रारंभिक और समाप्ति रंग, और अभिविन्यास कोण के आधार पर [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | एक [RectangleF](../../com.aspose.drawing/rectanglef) संरचना जो रैखिक ग्रेडिएंट की सीमाओं को निर्दिष्ट करती है। |
| color1 | [Color](../../com.aspose.drawing/color) | एक [Color](../../com.aspose.drawing/color) संरचना जो ग्रेडिएंट के प्रारंभिक रंग को दर्शाती है। |
| color2 | [Color](../../com.aspose.drawing/color) | एक [Color](../../com.aspose.drawing/color) संरचना जो ग्रेडिएंट के अंतिम रंग का प्रतिनिधित्व करती है। |
| कोण | फ़्लोट | ग्रेडिएंट की अभिविन्यास रेखा का कोण, जो x-अक्ष से घड़ी की दिशा में डिग्री में मापा जाता है। |

### LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle, boolean isAngleScaleable) {#LinearGradientBrush-com.aspose.drawing.RectangleF-com.aspose.drawing.Color-com.aspose.drawing.Color-float-boolean-}
```
public LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle, boolean isAngleScaleable)
```


एक आयत, प्रारंभिक और समाप्ति रंग, और अभिविन्यास कोण के आधार पर [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | एक [RectangleF](../../com.aspose.drawing/rectanglef) संरचना जो रैखिक ग्रेडिएंट की सीमाओं को निर्दिष्ट करती है। |
| color1 | [Color](../../com.aspose.drawing/color) | एक [Color](../../com.aspose.drawing/color) संरचना जो ग्रेडिएंट के प्रारंभिक रंग को दर्शाती है। |
| color2 | [Color](../../com.aspose.drawing/color) | एक [Color](../../com.aspose.drawing/color) संरचना जो ग्रेडिएंट के अंतिम रंग का प्रतिनिधित्व करती है। |
| कोण | फ़्लोट | ग्रेडिएंट की अभिविन्यास रेखा का कोण, जो x-अक्ष से घड़ी की दिशा में डिग्री में मापा जाता है। |
| isAngleScaleable | boolean | सही (true) सेट करें ताकि यह निर्दिष्ट किया जा सके कि यह कोण इस [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) से जुड़े परिवर्तन द्वारा प्रभावित होता है; अन्यथा, गलत (false)। |

### LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle) {#LinearGradientBrush-com.aspose.drawing.Rectangle-com.aspose.drawing.Color-com.aspose.drawing.Color-float-}
```
public LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle)
```


एक आयत, प्रारंभिक और समाप्ति रंग, और अभिविन्यास कोण के आधार पर [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | एक `Rectangle`([.getRectangle](../../null/\#getRectangle)) संरचना जो रैखिक ग्रेडिएंट की सीमाओं को निर्दिष्ट करती है। |
| color1 | [Color](../../com.aspose.drawing/color) | एक [Color](../../com.aspose.drawing/color) संरचना जो ग्रेडिएंट के प्रारंभिक रंग को दर्शाती है। |
| color2 | [Color](../../com.aspose.drawing/color) | एक [Color](../../com.aspose.drawing/color) संरचना जो ग्रेडिएंट के अंतिम रंग का प्रतिनिधित्व करती है। |
| कोण | फ़्लोट | ग्रेडिएंट की अभिविन्यास रेखा का कोण, जो x-अक्ष से घड़ी की दिशा में डिग्री में मापा जाता है। |

### LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle, boolean isAngleScaleable) {#LinearGradientBrush-com.aspose.drawing.Rectangle-com.aspose.drawing.Color-com.aspose.drawing.Color-float-boolean-}
```
public LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle, boolean isAngleScaleable)
```


एक आयत, प्रारंभिक और समाप्ति रंग, और अभिविन्यास कोण के आधार पर [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | एक `Rectangle`([.getRectangle](../../null/\#getRectangle)) संरचना जो रैखिक ग्रेडिएंट की सीमाओं को निर्दिष्ट करती है। |
| color1 | [Color](../../com.aspose.drawing/color) | एक [Color](../../com.aspose.drawing/color) संरचना जो ग्रेडिएंट के प्रारंभिक रंग को दर्शाती है। |
| color2 | [Color](../../com.aspose.drawing/color) | एक [Color](../../com.aspose.drawing/color) संरचना जो ग्रेडिएंट के अंतिम रंग का प्रतिनिधित्व करती है। |
| कोण | फ़्लोट | ग्रेडिएंट की अभिविन्यास रेखा का कोण, जो x-अक्ष से घड़ी की दिशा में डिग्री में मापा जाता है। |
| isAngleScaleable | boolean | सही (true) सेट करें ताकि यह निर्दिष्ट किया जा सके कि यह कोण इस [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) से जुड़े परिवर्तन द्वारा प्रभावित होता है; अन्यथा, गलत (false)। |

### getLinearColors() {#getLinearColors--}
```
public Color[] getLinearColors()
```


ग्रेडिएंट के प्रारंभिक और समाप्ति रंगों को प्राप्त करता है या सेट करता है।

**Returns:**
com.aspose.drawing.Color[]
### setLinearColors(Color[] value) {#setLinearColors-com.aspose.drawing.Color---}
```
public void setLinearColors(Color[] value)
```


ग्रेडिएंट के प्रारंभिक और समाप्ति रंगों को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [Color\[\]](../../com.aspose.drawing/color) |  |

### getRectangle() {#getRectangle--}
```
public RectangleF getRectangle()
```


एक आयताकार रीजन प्राप्त करता है जो ग्रेडिएंट के प्रारंभिक और समाप्ति बिंदुओं को परिभाषित करता है।

**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef)
### getGammaCorrection() {#getGammaCorrection--}
```
public boolean getGammaCorrection()
```


इस [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) के लिए यह दर्शाने वाला मान प्राप्त करता है या सेट करता है कि गामा सुधार सक्षम है या नहीं।

**Returns:**
boolean
### setGammaCorrection(boolean value) {#setGammaCorrection-boolean-}
```
public void setGammaCorrection(boolean value)
```


इस [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) के लिए यह दर्शाने वाला मान प्राप्त करता है या सेट करता है कि गामा सुधार सक्षम है या नहीं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getBlend() {#getBlend--}
```
public Blend getBlend()
```


एक `Blend`([.getBlend](../../null/\#getBlend)/[.setBlend(Blend)](../../null/\#setBlend-Blend-)) प्राप्त करता है या सेट करता है जो ग्रेडिएंट के लिए कस्टम फॉलऑफ़ को परिभाषित करने वाले स्थितियों और कारकों को निर्दिष्ट करता है।

**Returns:**
[Blend](../../com.aspose.drawing.drawing2d/blend)
### setBlend(Blend value) {#setBlend-com.aspose.drawing.drawing2d.Blend-}
```
public void setBlend(Blend value)
```


एक `Blend`([.getBlend](../../null/\#getBlend)/[.setBlend(Blend)](../../null/\#setBlend-Blend-)) प्राप्त करता है या सेट करता है जो ग्रेडिएंट के लिए कस्टम फॉलऑफ़ को परिभाषित करने वाले स्थितियों और कारकों को निर्दिष्ट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [Blend](../../com.aspose.drawing.drawing2d/blend) |  |

### getInterpolationColors() {#getInterpolationColors--}
```
public ColorBlend getInterpolationColors()
```


एक [ColorBlend](../../com.aspose.drawing.drawing2d/colorblend) प्राप्त करता है या सेट करता है जो बहु-रंगीय रैखिक ग्रेडिएंट को परिभाषित करता है।

**Returns:**
[ColorBlend](../../com.aspose.drawing.drawing2d/colorblend)
### setInterpolationColors(ColorBlend value) {#setInterpolationColors-com.aspose.drawing.drawing2d.ColorBlend-}
```
public void setInterpolationColors(ColorBlend value)
```


एक [ColorBlend](../../com.aspose.drawing.drawing2d/colorblend) प्राप्त करता है या सेट करता है जो बहु-रंगीय रैखिक ग्रेडिएंट को परिभाषित करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [ColorBlend](../../com.aspose.drawing.drawing2d/colorblend) |  |

### getWrapMode() {#getWrapMode--}
```
public int getWrapMode()
```


एक `WrapMode` एनीमरेशन प्राप्त करता है या सेट करता है जो इस [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) के रैप मोड को दर्शाता है।

**Returns:**
int
### setWrapMode(int value) {#setWrapMode-int-}
```
public void setWrapMode(int value)
```


एक `WrapMode` एनीमरेशन प्राप्त करता है या सेट करता है जो इस [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) के रैप मोड को दर्शाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getTransform() {#getTransform--}
```
public Matrix getTransform()
```


एक कॉपी [Matrix](../../com.aspose.drawing.drawing2d/matrix) प्राप्त करता है या सेट करता है जो इस [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) के लिए स्थानीय ज्यामितीय रूपांतरण को परिभाषित करती है।

**Returns:**
[Matrix](../../com.aspose.drawing.drawing2d/matrix)
### setTransform(Matrix value) {#setTransform-com.aspose.drawing.drawing2d.Matrix-}
```
public void setTransform(Matrix value)
```


एक कॉपी [Matrix](../../com.aspose.drawing.drawing2d/matrix) प्राप्त करता है या सेट करता है जो इस [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) के लिए स्थानीय ज्यामितीय रूपांतरण को परिभाषित करती है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.drawing.drawing2d/matrix) |  |

### deepClone() {#deepClone--}
```
public Object deepClone()
```


इस [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) की एक सटीक कॉपी बनाता है।

**Returns:**
java.lang.Object - वह [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) जिसे यह विधि बनाती है, जिसे एक वस्तु (object) के रूप में कास्ट किया गया है।
### setSigmaBellShape(float focus) {#setSigmaBellShape-float-}
```
public void setSigmaBellShape(float focus)
```


घंटी-आकार की वक्र पर आधारित ग्रेडिएंट फॉलऑफ़ बनाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| फ़ोकस | फ़्लोट | 0 से 1 के बीच का मान जो ग्रेडिएंट के केंद्र को निर्दिष्ट करता है (वह बिंदु जहाँ प्रारंभिक रंग और अंतिम रंग समान रूप से मिश्रित होते हैं)। |

### setSigmaBellShape(float focus, float scale) {#setSigmaBellShape-float-float-}
```
public void setSigmaBellShape(float focus, float scale)
```


घंटी-आकार की वक्र पर आधारित ग्रेडिएंट फॉलऑफ़ बनाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| फ़ोकस | फ़्लोट | 0 से 1 के बीच का मान जो ग्रेडिएंट के केंद्र को निर्दिष्ट करता है (वह बिंदु जहाँ ग्रेडिएंट केवल अंतिम रंग से बना होता है)। |
| स्केल | फ़्लोट | 0 से 1 के बीच का मान जो यह निर्धारित करता है कि रंग `फ़ोकस` से कितनी तेज़ी से घटते हैं। |

### setBlendTriangularShape(float focus) {#setBlendTriangularShape-float-}
```
public void setBlendTriangularShape(float focus)
```


एक रैखिक ग्रेडिएंट बनाता है जिसमें मध्य रंग और दोनों सिरों पर एकल रंग की रैखिक फॉलऑफ़ होती है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| फ़ोकस | फ़्लोट | 0 से 1 के बीच का मान जो ग्रेडिएंट के केंद्र को निर्दिष्ट करता है (वह बिंदु जहाँ ग्रेडिएंट केवल अंतिम रंग से बना होता है)। |

### setBlendTriangularShape(float focus, float scale) {#setBlendTriangularShape-float-float-}
```
public void setBlendTriangularShape(float focus, float scale)
```


एक रैखिक ग्रेडिएंट बनाता है जिसमें मध्य रंग और दोनों सिरों पर एकल रंग की रैखिक फॉलऑफ़ होती है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| फ़ोकस | फ़्लोट | 0 से 1 के बीच का मान जो ग्रेडिएंट के केंद्र को निर्दिष्ट करता है (वह बिंदु जहाँ ग्रेडिएंट केवल अंतिम रंग से बना होता है)। |
| स्केल | फ़्लोट | 0 से 1 के बीच का मान जो यह निर्धारित करता है कि रंग प्रारंभिक रंग से `फ़ोकस` (अंतिम रंग) तक कितनी तेज़ी से घटते हैं। |

### resetTransform() {#resetTransform--}
```
public void resetTransform()
```


`LinearGradientBrush.Transform` प्रॉपर्टी को पहचान (identity) पर रीसेट करता है।

### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-}
```
public void multiplyTransform(Matrix matrix)
```


इस [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) के स्थानीय ज्यामितीय रूपांतरण को दर्शाने वाले [Matrix](../../com.aspose.drawing.drawing2d/matrix) को निर्दिष्ट [Matrix](../../com.aspose.drawing.drawing2d/matrix) द्वारा, निर्दिष्ट [Matrix](../../com.aspose.drawing.drawing2d/matrix) को पहले जोड़कर, गुणा करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | ज्यामितीय परिवर्तन को गुणा करने के लिए उपयोग किया जाने वाला [Matrix](../../com.aspose.drawing.drawing2d/matrix)। |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-int-}
```
public void multiplyTransform(Matrix matrix, int order)
```


इस [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) के स्थानीय ज्यामितीय रूपांतरण को दर्शाने वाले [Matrix](../../com.aspose.drawing.drawing2d/matrix) को निर्दिष्ट [Matrix](../../com.aspose.drawing.drawing2d/matrix) के साथ निर्दिष्ट क्रम में गुणा करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | ज्यामितीय परिवर्तन को गुणा करने के लिए उपयोग किया जाने वाला [Matrix](../../com.aspose.drawing.drawing2d/matrix)। |
| order | int | एक [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder) जो यह निर्दिष्ट करता है कि दो मैट्रिसेज़ को किस क्रम में गुणा किया जाए। |

### translateTransform(float dx, float dy) {#translateTransform-float-float-}
```
public void translateTransform(float dx, float dy)
```


निर्दिष्ट आयामों द्वारा स्थानीय ज्यामितीय परिवर्तन को अनुवादित करता है। यह विधि अनुवाद को परिवर्तन के पहले जोड़ती है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| dx | फ़्लोट | x में अनुवाद का मान। |
| dy | फ़्लोट | y में अनुवाद का मान। |

### translateTransform(float dx, float dy, int order) {#translateTransform-float-float-int-}
```
public void translateTransform(float dx, float dy, int order)
```


निर्दिष्ट क्रम में निर्दिष्ट आयामों द्वारा स्थानीय ज्यामितीय रूपांतरण को अनुवादित करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| dx | फ़्लोट | x में अनुवाद का मान। |
| dy | फ़्लोट | y में अनुवाद का मान। |
| क्रम | int | अनुवाद लागू करने का क्रम (पहले जोड़ना या बाद में जोड़ना)। |

### scaleTransform(float sx, float sy) {#scaleTransform-float-float-}
```
public void scaleTransform(float sx, float sy)
```


स्थानीय ज्यामितीय ट्रांसफ़ॉर्म को निर्दिष्ट मानों द्वारा स्केल करता है। यह मेथड स्केलिंग मैट्रिक्स को ट्रांसफ़ॉर्म के पहले जोड़ता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sx | फ़्लोट | x-अक्ष दिशा में ट्रांसफ़ॉर्म को स्केल करने की मात्रा। |
| sy | फ़्लोट | y-अक्ष दिशा में ट्रांसफ़ॉर्म को स्केल करने की मात्रा। |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public void scaleTransform(float sx, float sy, int order)
```


निर्दिष्ट क्रम में निर्दिष्ट मात्रा द्वारा स्थानीय ज्यामितीय रूपांतरण को स्केल करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sx | फ़्लोट | x-अक्ष दिशा में ट्रांसफ़ॉर्म को स्केल करने की मात्रा। |
| sy | फ़्लोट | y-अक्ष दिशा में ट्रांसफ़ॉर्म को स्केल करने की मात्रा। |
| order | int | [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder) जो यह निर्धारित करता है कि स्केलिंग मैट्रिक्स को जोड़ना है या पहले जोड़ना है। |

### rotateTransform(float angle) {#rotateTransform-float-}
```
public void rotateTransform(float angle)
```


स्थानीय ज्यामितीय ट्रांसफ़ॉर्म को निर्दिष्ट मात्रा से घुमाता है। यह मेथड घूर्णन को ट्रांसफ़ॉर्म के पहले जोड़ता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| कोण | फ़्लोट | घूर्णन का कोण। |

### rotateTransform(float angle, int order) {#rotateTransform-float-int-}
```
public void rotateTransform(float angle, int order)
```


निर्दिष्ट क्रम में निर्दिष्ट मात्रा द्वारा स्थानीय ज्यामितीय रूपांतरण को घुमाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| कोण | फ़्लोट | घूर्णन का कोण। |
| order | int | [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder) जो यह निर्धारित करता है कि घूर्णन मैट्रिक्स को जोड़ना है या पहले जोड़ना है। |

