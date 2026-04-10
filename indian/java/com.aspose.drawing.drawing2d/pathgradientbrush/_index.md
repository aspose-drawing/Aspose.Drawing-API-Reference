---
title: PathGradientBrush
second_title: Aspose.Drawing for Java API संदर्भ
description: एक वस्तु को संलग्न करता है जो ग्रेडिएंट के साथ एक वस्तु के अंदर को भरती है।
type: docs
weight: 36
url: /hi/java/com.aspose.drawing.drawing2d/pathgradientbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.drawing.Brush](../../com.aspose.drawing/brush)
```
public final class PathGradientBrush extends Brush
```

एक [Brush](../../com.aspose.drawing/brush) वस्तु को संलग्न करता है जो ग्रेडिएंट के साथ एक [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) वस्तु के अंदर को भरती है। इस क्लास को विरासत में नहीं लिया जा सकता।
## निर्माता

| निर्माता | विवरण |
| --- | --- |
| [PathGradientBrush(PointF[] points)](#PathGradientBrush-com.aspose.drawing.PointF---) | निर्दिष्ट बिंदुओं के साथ [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) क्लास का एक नया उदाहरण प्रारंभ करता है। |
| [PathGradientBrush(PointF[] points, int wrapMode)](#PathGradientBrush-com.aspose.drawing.PointF---int-) | निर्दिष्ट बिंदुओं और रैप मोड के साथ [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) क्लास का एक नया उदाहरण प्रारंभ करता है। |
| [PathGradientBrush(Point[] points)](#PathGradientBrush-com.aspose.drawing.Point---) | निर्दिष्ट बिंदुओं के साथ [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) क्लास का एक नया उदाहरण प्रारंभ करता है। |
| [PathGradientBrush(Point[] points, int wrapMode)](#PathGradientBrush-com.aspose.drawing.Point---int-) | निर्दिष्ट बिंदुओं और रैप मोड के साथ [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) क्लास का एक नया उदाहरण प्रारंभ करता है। |
| [PathGradientBrush(GraphicsPath path)](#PathGradientBrush-com.aspose.drawing.drawing2d.GraphicsPath-) | निर्दिष्ट पथ के साथ [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) क्लास का एक नया उदाहरण प्रारंभ करता है। |
## मेथड्स

| विधि | विवरण |
| --- | --- |
| [getCenterColor()](#getCenterColor--) | पथ ग्रेडिएंट के केंद्र पर रंग प्राप्त करता है या सेट करता है। |
| [setCenterColor(Color value)](#setCenterColor-com.aspose.drawing.Color-) | पथ ग्रेडिएंट के केंद्र पर रंग प्राप्त करता है या सेट करता है। |
| [getSurroundColors()](#getSurroundColors--) | इस [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) द्वारा भरे गए पथ में बिंदुओं के अनुरूप रंगों की एक सरणी प्राप्त करता है या सेट करता है। |
| [setSurroundColors(Color[] value)](#setSurroundColors-com.aspose.drawing.Color---) | इस [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) द्वारा भरे गए पथ में बिंदुओं के अनुरूप रंगों की एक सरणी प्राप्त करता है या सेट करता है। |
| [getCenterPoint()](#getCenterPoint--) | पथ ग्रेडिएंट के केंद्र बिंदु को प्राप्त करता है या सेट करता है। |
| [setCenterPoint(PointF value)](#setCenterPoint-com.aspose.drawing.PointF-) | पथ ग्रेडिएंट के केंद्र बिंदु को प्राप्त करता है या सेट करता है। |
| [getRectangle()](#getRectangle--) | इस [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) के लिए एक बाउंडिंग आयत प्राप्त करता है। |
| [getBlend()](#getBlend--) | एक `Blend`([.getBlend](../../null/\#getBlend)/[.setBlend(Blend)](../../null/\#setBlend-Blend-)) प्राप्त करता है या सेट करता है जो ग्रेडिएंट के लिए कस्टम फॉलऑफ़ को परिभाषित करने वाले स्थितियों और कारकों को निर्दिष्ट करता है। |
| [setBlend(Blend value)](#setBlend-com.aspose.drawing.drawing2d.Blend-) | एक `Blend`([.getBlend](../../null/\#getBlend)/[.setBlend(Blend)](../../null/\#setBlend-Blend-)) प्राप्त करता है या सेट करता है जो ग्रेडिएंट के लिए कस्टम फॉलऑफ़ को परिभाषित करने वाले स्थितियों और कारकों को निर्दिष्ट करता है। |
| [getInterpolationColors()](#getInterpolationColors--) | एक [ColorBlend](../../com.aspose.drawing.drawing2d/colorblend) प्राप्त करता है या सेट करता है जो बहु-रंगीय रैखिक ग्रेडिएंट को परिभाषित करता है। |
| [setInterpolationColors(ColorBlend value)](#setInterpolationColors-com.aspose.drawing.drawing2d.ColorBlend-) | एक [ColorBlend](../../com.aspose.drawing.drawing2d/colorblend) प्राप्त करता है या सेट करता है जो बहु-रंगीय रैखिक ग्रेडिएंट को परिभाषित करता है। |
| [getTransform()](#getTransform--) | इस [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) के लिए स्थानीय ज्यामितीय रूपांतरण को परिभाषित करने वाले [Matrix](../../com.aspose.drawing.drawing2d/matrix) की एक प्रति प्राप्त करता है या सेट करता है। |
| [setTransform(Matrix value)](#setTransform-com.aspose.drawing.drawing2d.Matrix-) | इस [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) के लिए स्थानीय ज्यामितीय रूपांतरण को परिभाषित करने वाले [Matrix](../../com.aspose.drawing.drawing2d/matrix) की एक प्रति प्राप्त करता है या सेट करता है। |
| [getFocusScales()](#getFocusScales--) | ग्रेडिएंट फ़ॉलऑफ़ के फोकस बिंदु को प्राप्त करता है या सेट करता है। |
| [setFocusScales(PointF value)](#setFocusScales-com.aspose.drawing.PointF-) | ग्रेडिएंट फ़ॉलऑफ़ के फोकस बिंदु को प्राप्त करता है या सेट करता है। |
| [getWrapMode()](#getWrapMode--) | इस [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) के लिए रैप मोड को दर्शाने वाला `WrapMode`([.getWrapMode](../../null/\#getWrapMode)/[.setWrapMode(int)](../../null/\#setWrapMode-int-)) प्राप्त करता है या सेट करता है। |
| [setWrapMode(int value)](#setWrapMode-int-) | इस [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) के लिए रैप मोड को दर्शाने वाला `WrapMode`([.getWrapMode](../../null/\#getWrapMode)/[.setWrapMode(int)](../../null/\#setWrapMode-int-)) प्राप्त करता है या सेट करता है। |
| [deepClone()](#deepClone--) | इस [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) की एक सटीक प्रति बनाता है। |
| [setSigmaBellShape(float focus)](#setSigmaBellShape-float-) | एक ग्रेडिएंट ब्रश बनाता है जो पथ के केंद्र से शुरू होकर पथ की सीमा तक रंग बदलता है। |
| [setSigmaBellShape(float focus, float scale)](#setSigmaBellShape-float-float-) | एक ग्रेडिएंट ब्रश बनाता है जो पथ के केंद्र से शुरू होकर पथ की सीमा तक रंग बदलता है। |
| [setBlendTriangularShape(float focus)](#setBlendTriangularShape-float-) | एक ग्रेडिएंट बनाता है जिसमें केंद्र रंग और एक आसपास के रंग तक रैखिक फ़ॉलऑफ़ होता है। |
| [setBlendTriangularShape(float focus, float scale)](#setBlendTriangularShape-float-float-) | एक ग्रेडिएंट बनाता है जिसमें केंद्र रंग और प्रत्येक आसपास के रंग तक रैखिक गिरावट होती है। |
| [resetTransform()](#resetTransform--) | `PathGradientBrush.Transform` प्रॉपर्टी को पहचान (identity) पर रीसेट करता है। |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-) | ब्रश के ट्रांसफ़ॉर्मेशन मैट्रिक्स को ब्रश के ट्रांसफ़ॉर्मेशन मैट्रिक्स को दूसरे मैट्रिक्स से गुणा करके प्राप्त उत्पाद से अपडेट करता है। |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-int-) | ब्रश के ट्रांसफ़ॉर्मेशन मैट्रिक्स को ब्रश के ट्रांसफ़ॉर्मेशन मैट्रिक्स को दूसरे मैट्रिक्स से गुणा करके प्राप्त उत्पाद से अपडेट करता है। |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | निर्दिष्ट ट्रांसलेशन को स्थानीय ज्यामितीय ट्रांसफ़ॉर्म पर लागू करता है। |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | निर्दिष्ट क्रम में निर्दिष्ट ट्रांसलेशन को स्थानीय ज्यामितीय ट्रांसफ़ॉर्म पर लागू करता है। |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | निर्दिष्ट मात्रा द्वारा स्थानीय ज्यामितीय रूपांतरण को स्केल करता है। |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | निर्दिष्ट क्रम में निर्दिष्ट मात्रा द्वारा स्थानीय ज्यामितीय रूपांतरण को स्केल करता है। |
| [rotateTransform(float angle)](#rotateTransform-float-) | निर्दिष्ट मात्रा द्वारा स्थानीय ज्यामितीय रूपांतरण को घुमाता है। |
| [rotateTransform(float angle, int order)](#rotateTransform-float-int-) | निर्दिष्ट क्रम में निर्दिष्ट मात्रा द्वारा स्थानीय ज्यामितीय रूपांतरण को घुमाता है। |
### PathGradientBrush(PointF[] points) {#PathGradientBrush-com.aspose.drawing.PointF---}
```
public PathGradientBrush(PointF[] points)
```


निर्दिष्ट बिंदुओं के साथ [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) क्लास का एक नया उदाहरण प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.drawing/pointf) | [PointF](../../com.aspose.drawing/pointf) संरचनाओं की एक एरे जो पथ के शीर्ष बिंदुओं को बनाते हुए बिंदुओं का प्रतिनिधित्व करती है। |

### PathGradientBrush(PointF[] points, int wrapMode) {#PathGradientBrush-com.aspose.drawing.PointF---int-}
```
public PathGradientBrush(PointF[] points, int wrapMode)
```


निर्दिष्ट बिंदुओं और रैप मोड के साथ [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) क्लास का एक नया उदाहरण प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.drawing/pointf) | [PointF](../../com.aspose.drawing/pointf) संरचनाओं की एक एरे जो पथ के शीर्ष बिंदुओं को बनाते हुए बिंदुओं का प्रतिनिधित्व करती है। |
| wrapMode | int | `WrapMode`([.getWrapMode](../../null/\#getWrapMode)/[.setWrapMode(int)](../../null/\#setWrapMode-int-)) जो यह निर्दिष्ट करता है कि इस [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) के साथ खींचे गए भराव कैसे टाइल किए जाते हैं। |

### PathGradientBrush(Point[] points) {#PathGradientBrush-com.aspose.drawing.Point---}
```
public PathGradientBrush(Point[] points)
```


निर्दिष्ट बिंदुओं के साथ [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) क्लास का एक नया उदाहरण प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| points | [Point\[\]](../../com.aspose.drawing/point) | [Point](../../com.aspose.drawing/point) संरचनाओं की एक एरे जो पथ के शीर्ष बिंदुओं को बनाते हुए बिंदुओं का प्रतिनिधित्व करती है। |

### PathGradientBrush(Point[] points, int wrapMode) {#PathGradientBrush-com.aspose.drawing.Point---int-}
```
public PathGradientBrush(Point[] points, int wrapMode)
```


निर्दिष्ट बिंदुओं और रैप मोड के साथ [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) क्लास का एक नया उदाहरण प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| points | [Point\[\]](../../com.aspose.drawing/point) | [Point](../../com.aspose.drawing/point) संरचनाओं की एक एरे जो पथ के शीर्ष बिंदुओं को बनाते हुए बिंदुओं का प्रतिनिधित्व करती है। |
| wrapMode | int | `WrapMode`([.getWrapMode](../../null/\#getWrapMode)/[.setWrapMode(int)](../../null/\#setWrapMode-int-)) जो यह निर्दिष्ट करता है कि इस [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) के साथ खींचे गए भराव कैसे टाइल किए जाते हैं। |

### PathGradientBrush(GraphicsPath path) {#PathGradientBrush-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public PathGradientBrush(GraphicsPath path)
```


निर्दिष्ट पथ के साथ [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) क्लास का एक नया उदाहरण प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | यह [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) जो इस [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) द्वारा भरे गए क्षेत्र को परिभाषित करता है। |

### getCenterColor() {#getCenterColor--}
```
public Color getCenterColor()
```


पथ ग्रेडिएंट के केंद्र पर रंग प्राप्त करता है या सेट करता है।

**Returns:**
[Color](../../com.aspose.drawing/color)
### setCenterColor(Color value) {#setCenterColor-com.aspose.drawing.Color-}
```
public void setCenterColor(Color value)
```


पथ ग्रेडिएंट के केंद्र पर रंग प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [Color](../../com.aspose.drawing/color) |  |

### getSurroundColors() {#getSurroundColors--}
```
public Color[] getSurroundColors()
```


इस [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) द्वारा भरे गए पथ में बिंदुओं के अनुरूप रंगों की एक सरणी प्राप्त करता है या सेट करता है।

**Returns:**
com.aspose.drawing.Color[]
### setSurroundColors(Color[] value) {#setSurroundColors-com.aspose.drawing.Color---}
```
public void setSurroundColors(Color[] value)
```


इस [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) द्वारा भरे गए पथ में बिंदुओं के अनुरूप रंगों की एक सरणी प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [Color\[\]](../../com.aspose.drawing/color) |  |

### getCenterPoint() {#getCenterPoint--}
```
public PointF getCenterPoint()
```


पथ ग्रेडिएंट के केंद्र बिंदु को प्राप्त करता है या सेट करता है।

**Returns:**
[PointF](../../com.aspose.drawing/pointf)
### setCenterPoint(PointF value) {#setCenterPoint-com.aspose.drawing.PointF-}
```
public void setCenterPoint(PointF value)
```


पथ ग्रेडिएंट के केंद्र बिंदु को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [PointF](../../com.aspose.drawing/pointf) |  |

### getRectangle() {#getRectangle--}
```
public RectangleF getRectangle()
```


इस [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) के लिए एक बाउंडिंग आयत प्राप्त करता है।

**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef)
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

### getTransform() {#getTransform--}
```
public Matrix getTransform()
```


इस [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) के लिए स्थानीय ज्यामितीय रूपांतरण को परिभाषित करने वाले [Matrix](../../com.aspose.drawing.drawing2d/matrix) की एक प्रति प्राप्त करता है या सेट करता है।

**Returns:**
[Matrix](../../com.aspose.drawing.drawing2d/matrix)
### setTransform(Matrix value) {#setTransform-com.aspose.drawing.drawing2d.Matrix-}
```
public void setTransform(Matrix value)
```


इस [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) के लिए स्थानीय ज्यामितीय रूपांतरण को परिभाषित करने वाले [Matrix](../../com.aspose.drawing.drawing2d/matrix) की एक प्रति प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.drawing.drawing2d/matrix) |  |

### getFocusScales() {#getFocusScales--}
```
public PointF getFocusScales()
```


ग्रेडिएंट फ़ॉलऑफ़ के फोकस बिंदु को प्राप्त करता है या सेट करता है।

**Returns:**
[PointF](../../com.aspose.drawing/pointf)
### setFocusScales(PointF value) {#setFocusScales-com.aspose.drawing.PointF-}
```
public void setFocusScales(PointF value)
```


ग्रेडिएंट फ़ॉलऑफ़ के फोकस बिंदु को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [PointF](../../com.aspose.drawing/pointf) |  |

### getWrapMode() {#getWrapMode--}
```
public int getWrapMode()
```


इस [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) के लिए रैप मोड को दर्शाने वाला `WrapMode`([.getWrapMode](../../null/\#getWrapMode)/[.setWrapMode(int)](../../null/\#setWrapMode-int-)) प्राप्त करता है या सेट करता है।

**Returns:**
int
### setWrapMode(int value) {#setWrapMode-int-}
```
public void setWrapMode(int value)
```


इस [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) के लिए रैप मोड को दर्शाने वाला `WrapMode`([.getWrapMode](../../null/\#getWrapMode)/[.setWrapMode(int)](../../null/\#setWrapMode-int-)) प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### deepClone() {#deepClone--}
```
public Object deepClone()
```


इस [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) की एक सटीक प्रति बनाता है।

**Returns:**
java.lang.Object - वह [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) जिसे यह मेथड बनाता है, जिसे ऑब्जेक्ट के रूप में कास्ट किया गया है।
### setSigmaBellShape(float focus) {#setSigmaBellShape-float-}
```
public void setSigmaBellShape(float focus)
```


एक ग्रेडिएंट ब्रश बनाता है जो पथ के केंद्र से बाहर की ओर रंग बदलता है। रंगों के बीच संक्रमण बेल-आकार की वक्र पर आधारित होता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| फ़ोकस | फ़्लोट | 0 से 1 के बीच का मान जो यह निर्दिष्ट करता है कि पथ के केंद्र से उसकी सीमा तक किसी भी रेडियल पर केंद्र रंग अपनी अधिकतम तीव्रता पर कब होगा। 1 का मान (डिफ़ॉल्ट) अधिकतम तीव्रता को पथ के केंद्र पर रखता है। |

### setSigmaBellShape(float focus, float scale) {#setSigmaBellShape-float-float-}
```
public void setSigmaBellShape(float focus, float scale)
```


एक ग्रेडिएंट ब्रश बनाता है जो पथ के केंद्र से बाहर की ओर रंग बदलता है। रंगों के बीच संक्रमण बेल-आकार की वक्र पर आधारित होता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| फ़ोकस | फ़्लोट | 0 से 1 के बीच का मान जो यह निर्दिष्ट करता है कि पथ के केंद्र से उसकी सीमा तक किसी भी रेडियल पर केंद्र रंग अपनी अधिकतम तीव्रता पर कब होगा। 1 का मान (डिफ़ॉल्ट) अधिकतम तीव्रता को पथ के केंद्र पर रखता है। |
| स्केल | फ़्लोट | 0 से 1 के बीच का मान जो केंद्र रंग की अधिकतम तीव्रता को निर्दिष्ट करता है जो सीमा रंग के साथ मिश्रित होती है। 1 का मान अधिकतम संभव तीव्रता देता है, और यह डिफ़ॉल्ट मान है। |

### setBlendTriangularShape(float focus) {#setBlendTriangularShape-float-}
```
public void setBlendTriangularShape(float focus)
```


एक ग्रेडिएंट बनाता है जिसमें केंद्र रंग और एक आसपास के रंग तक रैखिक फ़ॉलऑफ़ होता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| फ़ोकस | फ़्लोट | 0 से 1 के बीच का मान जो यह निर्दिष्ट करता है कि पथ के केंद्र से उसकी सीमा तक किसी भी रेडियल पर केंद्र रंग अपनी अधिकतम तीव्रता पर कब होगा। 1 का मान (डिफ़ॉल्ट) अधिकतम तीव्रता को पथ के केंद्र पर रखता है। |

### setBlendTriangularShape(float focus, float scale) {#setBlendTriangularShape-float-float-}
```
public void setBlendTriangularShape(float focus, float scale)
```


एक ग्रेडिएंट बनाता है जिसमें केंद्र रंग और प्रत्येक आसपास के रंग तक रैखिक गिरावट होती है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| फ़ोकस | फ़्लोट | 0 से 1 के बीच का मान जो यह निर्दिष्ट करता है कि पथ के केंद्र से उसकी सीमा तक किसी भी रेडियल पर केंद्र रंग अपनी अधिकतम तीव्रता पर कब होगा। 1 का मान (डिफ़ॉल्ट) अधिकतम तीव्रता को पथ के केंद्र पर रखता है। |
| स्केल | फ़्लोट | 0 से 1 के बीच का मान जो केंद्र रंग की अधिकतम तीव्रता को निर्दिष्ट करता है जो सीमा रंग के साथ मिश्रित होती है। 1 का मान अधिकतम संभव तीव्रता देता है, और यह डिफ़ॉल्ट मान है। |

### resetTransform() {#resetTransform--}
```
public void resetTransform()
```


`PathGradientBrush.Transform` प्रॉपर्टी को पहचान (identity) पर रीसेट करता है।

### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-}
```
public void multiplyTransform(Matrix matrix)
```


ब्रश के ट्रांसफ़ॉर्मेशन मैट्रिक्स को ब्रश के ट्रांसफ़ॉर्मेशन मैट्रिक्स को दूसरे मैट्रिक्स से गुणा करके प्राप्त उत्पाद से अपडेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | यह [Matrix](../../com.aspose.drawing.drawing2d/matrix) जो ब्रश के वर्तमान ट्रांसफ़ॉर्मेशन मैट्रिक्स से गुणा किया जाएगा। |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-int-}
```
public void multiplyTransform(Matrix matrix, int order)
```


ब्रश के ट्रांसफ़ॉर्मेशन मैट्रिक्स को ब्रश के ट्रांसफ़ॉर्मेशन मैट्रिक्स को दूसरे मैट्रिक्स से गुणा करके प्राप्त उत्पाद से अपडेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | यह [Matrix](../../com.aspose.drawing.drawing2d/matrix) जो ब्रश के वर्तमान ट्रांसफ़ॉर्मेशन मैट्रिक्स से गुणा किया जाएगा। |
| order | int | एक [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder) जो यह निर्दिष्ट करता है कि दो मैट्रिसेज़ को किस क्रम में गुणा किया जाए। |

### translateTransform(float dx, float dy) {#translateTransform-float-float-}
```
public void translateTransform(float dx, float dy)
```


निर्दिष्ट ट्रांसलेशन को स्थानीय ज्यामितीय ट्रांसफ़ॉर्म पर लागू करता है। यह मेथड ट्रांसलेशन को ट्रांसफ़ॉर्म के पहले जोड़ता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| dx | फ़्लोट | x में अनुवाद का मान। |
| dy | फ़्लोट | y में अनुवाद का मान। |

### translateTransform(float dx, float dy, int order) {#translateTransform-float-float-int-}
```
public void translateTransform(float dx, float dy, int order)
```


निर्दिष्ट क्रम में निर्दिष्ट ट्रांसलेशन को स्थानीय ज्यामितीय ट्रांसफ़ॉर्म पर लागू करता है।

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
| sx | फ़्लोट | x-अक्ष दिशा में ट्रांसफ़ॉर्म स्केल फ़ैक्टर। |
| sy | फ़्लोट | y-अक्ष दिशा में ट्रांसफ़ॉर्म स्केल फ़ैक्टर। |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public void scaleTransform(float sx, float sy, int order)
```


निर्दिष्ट क्रम में निर्दिष्ट मात्रा द्वारा स्थानीय ज्यामितीय रूपांतरण को स्केल करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sx | फ़्लोट | x-अक्ष दिशा में ट्रांसफ़ॉर्म स्केल फ़ैक्टर। |
| sy | फ़्लोट | y-अक्ष दिशा में ट्रांसफ़ॉर्म स्केल फ़ैक्टर। |
| order | int | [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder) जो यह निर्धारित करता है कि स्केलिंग मैट्रिक्स को जोड़ना है या पहले जोड़ना है। |

### rotateTransform(float angle) {#rotateTransform-float-}
```
public void rotateTransform(float angle)
```


स्थानीय ज्यामितीय ट्रांसफ़ॉर्म को निर्दिष्ट मात्रा से घुमाता है। यह मेथड घूर्णन को ट्रांसफ़ॉर्म के पहले जोड़ता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| कोण | फ़्लोट | घूर्णन का कोण (विस्तार)। |

### rotateTransform(float angle, int order) {#rotateTransform-float-int-}
```
public void rotateTransform(float angle, int order)
```


निर्दिष्ट क्रम में निर्दिष्ट मात्रा द्वारा स्थानीय ज्यामितीय रूपांतरण को घुमाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| कोण | फ़्लोट | घूर्णन का कोण (विस्तार)। |
| order | int | [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder) जो यह निर्धारित करता है कि घूर्णन मैट्रिक्स को जोड़ना है या पहले जोड़ना है। |

