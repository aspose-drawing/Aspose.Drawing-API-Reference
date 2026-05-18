---
title: पेन
second_title: Aspose.Drawing for Java API संदर्भ
description: रेखाएँ और वक्र खींचने के लिए उपयोग किए जाने वाले ऑब्जेक्ट को परिभाषित करता है।
type: docs
weight: 34
url: /hi/java/com.aspose.drawing/pen/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public class Pen implements System.IDisposable
```

रेखाएँ और वक्र खींचने के लिए उपयोग किए जाने वाले ऑब्जेक्ट को परिभाषित करता है।
## निर्माता

| निर्माता | विवरण |
| --- | --- |
| [Pen(Color color)](#Pen-com.aspose.drawing.Color-) | निर्दिष्ट `Color`([.getColor](../../null/\#getColor)/[.setColor(Color)](../../null/\#setColor-Color-)) के साथ [Pen](../../com.aspose.drawing/pen) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [Pen(Brush brush, float width)](#Pen-com.aspose.drawing.Brush-float-) | निर्दिष्ट Brush और Width के साथ Pen क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [Pen(Brush brush)](#Pen-com.aspose.drawing.Brush-) | निर्दिष्ट `Brush`([.getBrush](../../null/\#getBrush)/[.setBrush(Brush)](../../null/\#setBrush-Brush-)) के साथ [Pen](../../com.aspose.drawing/pen) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [Pen(Color color, float width)](#Pen-com.aspose.drawing.Color-float-) | निर्दिष्ट Color और Width प्रॉपर्टीज़ के साथ Pen क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
## मेथड्स

| विधि | विवरण |
| --- | --- |
| [getColor()](#getColor--) | इस [Pen](../../com.aspose.drawing/pen) का रंग प्राप्त करता है या सेट करता है। |
| [setColor(Color value)](#setColor-com.aspose.drawing.Color-) | इस [Pen](../../com.aspose.drawing/pen) का रंग प्राप्त करता है या सेट करता है। |
| [getBrush()](#getBrush--) | इस [Pen](../../com.aspose.drawing/pen) के गुण निर्धारित करने वाले Brush को प्राप्त करता है या सेट करता है। |
| [setBrush(Brush value)](#setBrush-com.aspose.drawing.Brush-) | इस [Pen](../../com.aspose.drawing/pen) के गुण निर्धारित करने वाले Brush को प्राप्त करता है या सेट करता है। |
| [getCompoundArray()](#getCompoundArray--) | एक कॉम्पाउंड पेन को निर्दिष्ट करने वाले मानों की एरे को प्राप्त करता है या सेट करता है। |
| [setCompoundArray(float[] value)](#setCompoundArray-float---) | एक कॉम्पाउंड पेन को निर्दिष्ट करने वाले मानों की एरे को प्राप्त करता है या सेट करता है। |
| [getWidth()](#getWidth--) | ड्रॉइंग के लिए उपयोग किए गए Graphics ऑब्जेक्ट की इकाइयों में इस Pen की चौड़ाई को प्राप्त करता है या सेट करता है। |
| [setWidth(float value)](#setWidth-float-) | ड्रॉइंग के लिए उपयोग किए गए Graphics ऑब्जेक्ट की इकाइयों में इस Pen की चौड़ाई को प्राप्त करता है या सेट करता है। |
| [getStartCap()](#getStartCap--) | इस Pen से खींची गई लाइनों की शुरुआत में उपयोग किए जाने वाले कैप स्टाइल को प्राप्त करता है या सेट करता है। |
| [setStartCap(int value)](#setStartCap-int-) | इस Pen से खींची गई लाइनों की शुरुआत में उपयोग किए जाने वाले कैप स्टाइल को प्राप्त करता है या सेट करता है। |
| [getEndCap()](#getEndCap--) | इस Pen से खींची गई लाइनों के अंत में उपयोग किए जाने वाले कैप स्टाइल को प्राप्त करता है या सेट करता है। |
| [setEndCap(int value)](#setEndCap-int-) | इस Pen से खींची गई लाइनों के अंत में उपयोग किए जाने वाले कैप स्टाइल को प्राप्त करता है या सेट करता है। |
| [getLineJoin()](#getLineJoin--) | इस Pen से खींची गई दो क्रमिक लाइनों के अंत के लिए जॉइन स्टाइल को प्राप्त करता है या सेट करता है। |
| [setLineJoin(int value)](#setLineJoin-int-) | इस Pen से खींची गई दो क्रमिक लाइनों के अंत के लिए जॉइन स्टाइल को प्राप्त करता है या सेट करता है। |
| [getMiterLimit()](#getMiterLimit--) | माइटर्ड कोने पर जॉइन की मोटाई की सीमा को प्राप्त करता है या सेट करता है। |
| [setMiterLimit(float value)](#setMiterLimit-float-) | माइटर्ड कोने पर जॉइन की मोटाई की सीमा को प्राप्त करता है या सेट करता है। |
| [getAlignment()](#getAlignment--) | इस [Pen](../../com.aspose.drawing/pen) के लिए संरेखण को प्राप्त करता है या सेट करता है। |
| [setAlignment(int value)](#setAlignment-int-) | इस [Pen](../../com.aspose.drawing/pen) के लिए संरेखण को प्राप्त करता है या सेट करता है। |
| [getTransform()](#getTransform--) | इस [Pen](../../com.aspose.drawing/pen) के ज्यामितीय ट्रांसफ़ॉर्मेशन की एक कॉपी को प्राप्त करता है या सेट करता है। |
| [setTransform(Matrix value)](#setTransform-com.aspose.drawing.drawing2d.Matrix-) | इस [Pen](../../com.aspose.drawing/pen) के ज्यामितीय ट्रांसफ़ॉर्मेशन की एक कॉपी को प्राप्त करता है या सेट करता है। |
| [getCustomStartCap()](#getCustomStartCap--) | इस [Pen](../../com.aspose.drawing/pen) से खींची गई लाइनों की शुरुआत में उपयोग करने के लिए एक कस्टम कैप को प्राप्त करता है या सेट करता है। |
| [setCustomStartCap(CustomLineCap value)](#setCustomStartCap-com.aspose.drawing.drawing2d.CustomLineCap-) | इस [Pen](../../com.aspose.drawing/pen) से खींची गई लाइनों की शुरुआत में उपयोग करने के लिए एक कस्टम कैप को प्राप्त करता है या सेट करता है। |
| [getCustomEndCap()](#getCustomEndCap--) | इस [Pen](../../com.aspose.drawing/pen) से खींची गई लाइनों के अंत में उपयोग करने के लिए एक कस्टम कैप को प्राप्त करता है या सेट करता है। |
| [setCustomEndCap(CustomLineCap value)](#setCustomEndCap-com.aspose.drawing.drawing2d.CustomLineCap-) | इस [Pen](../../com.aspose.drawing/pen) से खींची गई लाइनों के अंत में उपयोग करने के लिए एक कस्टम कैप को प्राप्त करता है या सेट करता है। |
| [getDashCap()](#getDashCap--) | इस [Pen](../../com.aspose.drawing/pen) से खींची गई डैश्ड लाइनों को बनाते डैश के अंत में उपयोग किए जाने वाले कैप स्टाइल को प्राप्त करता है या सेट करता है। |
| [setDashCap(int value)](#setDashCap-int-) | इस [Pen](../../com.aspose.drawing/pen) से खींची गई डैश्ड लाइनों को बनाते डैश के अंत में उपयोग किए जाने वाले कैप स्टाइल को प्राप्त करता है या सेट करता है। |
| [getDashOffset()](#getDashOffset--) | एक लाइन की शुरुआत से डैश पैटर्न की शुरुआत तक की दूरी को प्राप्त करता है या सेट करता है। |
| [setDashOffset(float value)](#setDashOffset-float-) | एक लाइन की शुरुआत से डैश पैटर्न की शुरुआत तक की दूरी को प्राप्त करता है या सेट करता है। |
| [getDashPattern()](#getDashPattern--) | कस्टम डैश और स्पेस की एरे को प्राप्त करता है या सेट करता है। |
| [setDashPattern(float[] value)](#setDashPattern-float---) | कस्टम डैश और स्पेस की एरे को प्राप्त करता है या सेट करता है। |
| [getDashStyle()](#getDashStyle--) | इस [Pen](../../com.aspose.drawing/pen) से खींची गई डैश्ड लाइनों के लिए उपयोग किए जाने वाले स्टाइल को प्राप्त करता है या सेट करता है। |
| [setDashStyle(int value)](#setDashStyle-int-) | इस [Pen](../../com.aspose.drawing/pen) से खींची गई डैश्ड लाइनों के लिए उपयोग किए जाने वाले स्टाइल को प्राप्त करता है या सेट करता है। |
| [getPenType()](#getPenType--) | इस Pen से खींची गई लाइनों के स्टाइल को प्राप्त करता है। |
| [dispose()](#dispose--) | इस Pen द्वारा उपयोग किए गए सभी संसाधनों को रिलीज़ करता है। |
| [deepClone()](#deepClone--) | इस [Pen](../../com.aspose.drawing/pen) की सटीक प्रतिलिपि बनाता है। |
| [setLineCap(int startCap, int endCap, int dashCap)](#setLineCap-int-int-int-) | इस [Pen](../../com.aspose.drawing/pen) द्वारा खींची गई लाइनों के अंत में उपयोग किए जाने वाले कैप की शैली निर्धारित करने वाले मान सेट करता है। |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | निर्दिष्ट गुणकों द्वारा स्थानीय ज्यामितीय रूपांतरण को स्केल करता है। |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | निर्दिष्ट क्रम में निर्दिष्ट गुणकों द्वारा स्थानीय ज्यामितीय रूपांतरण को स्केल करता है। |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | निर्दिष्ट आयामों द्वारा स्थानीय ज्यामितीय रूपांतरण को ट्रांसलेट करता है। |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | निर्दिष्ट क्रम में निर्दिष्ट आयामों द्वारा स्थानीय ज्यामितीय रूपांतरण को ट्रांसलेट करता है। |
| [rotateTransform(float angle)](#rotateTransform-float-) | निर्दिष्ट कोण द्वारा स्थानीय ज्यामितीय रूपांतरण को घुमाता है। |
| [rotateTransform(float angle, int order)](#rotateTransform-float-int-) | निर्दिष्ट क्रम में निर्दिष्ट कोण द्वारा स्थानीय ज्यामितीय रूपांतरण को घुमाता है। |
| [resetTransform()](#resetTransform--) | इस [Pen](../../com.aspose.drawing/pen) के लिए ज्यामितीय रूपांतरण मैट्रिक्स को पहचान (identity) पर रीसेट करता है। |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-) | इस [Pen](../../com.aspose.drawing/pen) के रूपांतरण मैट्रिक्स को निर्दिष्ट [Matrix](../../com.aspose.drawing.drawing2d/matrix) से गुणा करता है। |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-int-) | इस [Pen](../../com.aspose.drawing/pen) के रूपांतरण मैट्रिक्स को निर्दिष्ट क्रम में निर्दिष्ट [Matrix](../../com.aspose.drawing.drawing2d/matrix) से गुणा करता है। |
### Pen(Color color) {#Pen-com.aspose.drawing.Color-}
```
public Pen(Color color)
```


निर्दिष्ट `Color`([.getColor](../../null/\#getColor)/[.setColor(Color)](../../null/\#setColor-Color-)) के साथ [Pen](../../com.aspose.drawing/pen) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| color | [Color](../../com.aspose.drawing/color) | एक `Color`([.getColor](../../null/\#getColor)/[.setColor(Color)](../../null/\#setColor-Color-)) जो इस [Pen](../../com.aspose.drawing/pen) की भराव गुणों को निर्धारित करता है। |

### Pen(Brush brush, float width) {#Pen-com.aspose.drawing.Brush-float-}
```
public Pen(Brush brush, float width)
```


निर्दिष्ट Brush और Width के साथ Pen क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.drawing/brush) | एक Brush जो इस Pen की विशेषताओं को निर्धारित करता है। |
| चौड़ाई | फ़्लोट | नए Pen की चौड़ाई। |

### Pen(Brush brush) {#Pen-com.aspose.drawing.Brush-}
```
public Pen(Brush brush)
```


निर्दिष्ट `Brush`([.getBrush](../../null/\#getBrush)/[.setBrush(Brush)](../../null/\#setBrush-Brush-)) के साथ [Pen](../../com.aspose.drawing/pen) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.drawing/brush) | एक `Brush`([.getBrush](../../null/\#getBrush)/[.setBrush(Brush)](../../null/\#setBrush-Brush-)) जो इस [Pen](../../com.aspose.drawing/pen) की भराव गुणों को निर्धारित करता है। |

### Pen(Color color, float width) {#Pen-com.aspose.drawing.Color-float-}
```
public Pen(Color color, float width)
```


निर्दिष्ट Color और Width प्रॉपर्टीज़ के साथ Pen क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| color | [Color](../../com.aspose.drawing/color) | एक Color संरचना जो इस Pen का रंग दर्शाती है। |
| चौड़ाई | फ़्लोट | एक मान जो इस Pen की चौड़ाई को दर्शाता है। |

### getColor() {#getColor--}
```
public final Color getColor()
```


इस [Pen](../../com.aspose.drawing/pen) का रंग प्राप्त करता है या सेट करता है।

मान: एक `Color`([.getColor](../../null/\#getColor)/[.setColor(Color)](../../null/\#setColor-Color-)) संरचना जो इस [Pen](../../com.aspose.drawing/pen) का रंग दर्शाती है।

**Returns:**
[Color](../../com.aspose.drawing/color)
### setColor(Color value) {#setColor-com.aspose.drawing.Color-}
```
public final void setColor(Color value)
```


इस [Pen](../../com.aspose.drawing/pen) का रंग प्राप्त करता है या सेट करता है।

मान: एक `Color`([.getColor](../../null/\#getColor)/[.setColor(Color)](../../null/\#setColor-Color-)) संरचना जो इस [Pen](../../com.aspose.drawing/pen) का रंग दर्शाती है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [Color](../../com.aspose.drawing/color) |  |

### getBrush() {#getBrush--}
```
public final Brush getBrush()
```


इस [Pen](../../com.aspose.drawing/pen) के गुण निर्धारित करने वाले Brush को प्राप्त करता है या सेट करता है।

**Returns:**
[Brush](../../com.aspose.drawing/brush)
### setBrush(Brush value) {#setBrush-com.aspose.drawing.Brush-}
```
public final void setBrush(Brush value)
```


इस [Pen](../../com.aspose.drawing/pen) के गुण निर्धारित करने वाले Brush को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [Brush](../../com.aspose.drawing/brush) |  |

### getCompoundArray() {#getCompoundArray--}
```
public final float[] getCompoundArray()
```


एक एरे मान प्राप्त करता है या सेट करता है जो एक compound pen को निर्दिष्ट करता है। एक compound pen समानांतर लाइनों और अंतरालों से बनी एक संयुक्त रेखा बनाता है।

**Returns:**
float[] - वास्तविक संख्याओं का एक एरे जो compound एरे को निर्दिष्ट करता है। एरे के तत्व बढ़ते क्रम में होने चाहिए, 0 से कम नहीं और 1 से अधिक नहीं।
### setCompoundArray(float[] value) {#setCompoundArray-float---}
```
public final void setCompoundArray(float[] value)
```


एक एरे मान प्राप्त करता है या सेट करता है जो एक compound pen को निर्दिष्ट करता है। एक compound pen समानांतर लाइनों और अंतरालों से बनी एक संयुक्त रेखा बनाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float[] |  |

### getWidth() {#getWidth--}
```
public final float getWidth()
```


ड्रॉइंग के लिए उपयोग किए गए Graphics ऑब्जेक्ट की इकाइयों में इस Pen की चौड़ाई को प्राप्त करता है या सेट करता है।

**Returns:**
फ़्लोट
### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```


ड्रॉइंग के लिए उपयोग किए गए Graphics ऑब्जेक्ट की इकाइयों में इस Pen की चौड़ाई को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | फ़्लोट |  |

### getStartCap() {#getStartCap--}
```
public final int getStartCap()
```


इस Pen से खींची गई लाइनों की शुरुआत में उपयोग किए जाने वाले कैप स्टाइल को प्राप्त करता है या सेट करता है।

**Returns:**
int
### setStartCap(int value) {#setStartCap-int-}
```
public final void setStartCap(int value)
```


इस Pen से खींची गई लाइनों की शुरुआत में उपयोग किए जाने वाले कैप स्टाइल को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getEndCap() {#getEndCap--}
```
public final int getEndCap()
```


इस Pen से खींची गई लाइनों के अंत में उपयोग किए जाने वाले कैप स्टाइल को प्राप्त करता है या सेट करता है।

**Returns:**
int
### setEndCap(int value) {#setEndCap-int-}
```
public final void setEndCap(int value)
```


इस Pen से खींची गई लाइनों के अंत में उपयोग किए जाने वाले कैप स्टाइल को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getLineJoin() {#getLineJoin--}
```
public final int getLineJoin()
```


इस Pen से खींची गई दो क्रमिक लाइनों के अंत के लिए जॉइन स्टाइल को प्राप्त करता है या सेट करता है।

--------------------

वर्तमान में मिटर जॉइन वास्तव में MiterClipped की तरह काम करता है।

**Returns:**
int
### setLineJoin(int value) {#setLineJoin-int-}
```
public final void setLineJoin(int value)
```


इस Pen से खींची गई दो क्रमिक लाइनों के अंत के लिए जॉइन स्टाइल को प्राप्त करता है या सेट करता है।

--------------------

वर्तमान में मिटर जॉइन वास्तव में MiterClipped की तरह काम करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getMiterLimit() {#getMiterLimit--}
```
public final float getMiterLimit()
```


माइटर्ड कोने पर जॉइन की मोटाई की सीमा को प्राप्त करता है या सेट करता है।

**Returns:**
फ़्लोट
### setMiterLimit(float value) {#setMiterLimit-float-}
```
public final void setMiterLimit(float value)
```


माइटर्ड कोने पर जॉइन की मोटाई की सीमा को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | फ़्लोट |  |

### getAlignment() {#getAlignment--}
```
public final int getAlignment()
```


इस [Pen](../../com.aspose.drawing/pen) के लिए संरेखण को प्राप्त करता है या सेट करता है।

**Returns:**
int - एक [PenAlignment](../../com.aspose.drawing.drawing2d/penalignment) जो इस [Pen](../../com.aspose.drawing/pen) के लिए संरेखण दर्शाता है।
### setAlignment(int value) {#setAlignment-int-}
```
public final void setAlignment(int value)
```


इस [Pen](../../com.aspose.drawing/pen) के लिए संरेखण को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getTransform() {#getTransform--}
```
public final Matrix getTransform()
```


इस [Pen](../../com.aspose.drawing/pen) के ज्यामितीय ट्रांसफ़ॉर्मेशन की एक कॉपी को प्राप्त करता है या सेट करता है।

मान: एक प्रतिलिपि [Matrix](../../com.aspose.drawing.drawing2d/matrix) की जो इस [Pen](../../com.aspose.drawing/pen) के लिए ज्यामितीय रूपांतरण को दर्शाती है।

**Returns:**
[Matrix](../../com.aspose.drawing.drawing2d/matrix)
### setTransform(Matrix value) {#setTransform-com.aspose.drawing.drawing2d.Matrix-}
```
public final void setTransform(Matrix value)
```


इस [Pen](../../com.aspose.drawing/pen) के ज्यामितीय ट्रांसफ़ॉर्मेशन की एक कॉपी को प्राप्त करता है या सेट करता है।

मान: एक प्रतिलिपि [Matrix](../../com.aspose.drawing.drawing2d/matrix) की जो इस [Pen](../../com.aspose.drawing/pen) के लिए ज्यामितीय रूपांतरण को दर्शाती है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.drawing.drawing2d/matrix) |  |

### getCustomStartCap() {#getCustomStartCap--}
```
public final CustomLineCap getCustomStartCap()
```


इस [Pen](../../com.aspose.drawing/pen) से खींची गई लाइनों की शुरुआत में उपयोग करने के लिए एक कस्टम कैप को प्राप्त करता है या सेट करता है।

**Returns:**
[CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) - A [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) that represents the cap used at the beginning of lines drawn with this [Pen](../../com.aspose.drawing/pen).
### setCustomStartCap(CustomLineCap value) {#setCustomStartCap-com.aspose.drawing.drawing2d.CustomLineCap-}
```
public final void setCustomStartCap(CustomLineCap value)
```


इस [Pen](../../com.aspose.drawing/pen) से खींची गई लाइनों की शुरुआत में उपयोग करने के लिए एक कस्टम कैप को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) |  |

### getCustomEndCap() {#getCustomEndCap--}
```
public final CustomLineCap getCustomEndCap()
```


इस [Pen](../../com.aspose.drawing/pen) से खींची गई लाइनों के अंत में उपयोग करने के लिए एक कस्टम कैप को प्राप्त करता है या सेट करता है।

**Returns:**
[CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) - A [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) that represents the cap used at the end of lines drawn with this [Pen](../../com.aspose.drawing/pen).
### setCustomEndCap(CustomLineCap value) {#setCustomEndCap-com.aspose.drawing.drawing2d.CustomLineCap-}
```
public final void setCustomEndCap(CustomLineCap value)
```


इस [Pen](../../com.aspose.drawing/pen) से खींची गई लाइनों के अंत में उपयोग करने के लिए एक कस्टम कैप को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) |  |

### getDashCap() {#getDashCap--}
```
public final int getDashCap()
```


इस [Pen](../../com.aspose.drawing/pen) से खींची गई डैश्ड लाइनों को बनाते डैश के अंत में उपयोग किए जाने वाले कैप स्टाइल को प्राप्त करता है या सेट करता है।

**Returns:**
int - `DashCap`([.getDashCap](../../null/\#getDashCap)/[.setDashCap(int)](../../null/\#setDashCap-int-)) मानों में से एक जो इस [Pen](../../com.aspose.drawing/pen) द्वारा खींची गई डैश वाली लाइनों के डैश के प्रारंभ और अंत में उपयोग किए जाने वाले कैप शैली को दर्शाता है।
### setDashCap(int value) {#setDashCap-int-}
```
public final void setDashCap(int value)
```


इस [Pen](../../com.aspose.drawing/pen) से खींची गई डैश्ड लाइनों को बनाते डैश के अंत में उपयोग किए जाने वाले कैप स्टाइल को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getDashOffset() {#getDashOffset--}
```
public final float getDashOffset()
```


एक लाइन की शुरुआत से डैश पैटर्न की शुरुआत तक की दूरी को प्राप्त करता है या सेट करता है।

**Returns:**
float - एक रेखा की शुरुआत से डैश पैटर्न की शुरुआत तक की दूरी।
### setDashOffset(float value) {#setDashOffset-float-}
```
public final void setDashOffset(float value)
```


एक लाइन की शुरुआत से डैश पैटर्न की शुरुआत तक की दूरी को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | फ़्लोट |  |

### getDashPattern() {#getDashPattern--}
```
public final float[] getDashPattern()
```


कस्टम डैश और स्पेस की एरे को प्राप्त करता है या सेट करता है।

**Returns:**
float[] - वास्तविक संख्याओं का एक एरे जो डैश वाली लाइनों में वैकल्पिक डैश और स्पेस की लंबाई को निर्दिष्ट करता है।
### setDashPattern(float[] value) {#setDashPattern-float---}
```
public final void setDashPattern(float[] value)
```


कस्टम डैश और स्पेस की एरे को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float[] |  |

### getDashStyle() {#getDashStyle--}
```
public final int getDashStyle()
```


इस [Pen](../../com.aspose.drawing/pen) से खींची गई डैश्ड लाइनों के लिए उपयोग किए जाने वाले स्टाइल को प्राप्त करता है या सेट करता है।

**Returns:**
int - एक `DashStyle`([.getDashStyle](../../null/\#getDashStyle)/[.setDashStyle(int)](../../null/\#setDashStyle-int-)) जो इस [Pen](../../com.aspose.drawing/pen) द्वारा खींची गई डैश्ड लाइनों के लिए उपयोग की जाने वाली शैली का प्रतिनिधित्व करता है।
### setDashStyle(int value) {#setDashStyle-int-}
```
public final void setDashStyle(int value)
```


इस [Pen](../../com.aspose.drawing/pen) से खींची गई डैश्ड लाइनों के लिए उपयोग किए जाने वाले स्टाइल को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getPenType() {#getPenType--}
```
public final int getPenType()
```


इस Pen से खींची गई लाइनों के स्टाइल को प्राप्त करता है।

मान: एक `PenType`([.getPenType](../../null/\#getPenType)) enumeration जो इस [Pen](../../com.aspose.drawing/pen) द्वारा खींची गई लाइनों की शैली निर्दिष्ट करता है।

**Returns:**
int
### dispose() {#dispose--}
```
public final void dispose()
```


इस Pen द्वारा उपयोग किए गए सभी संसाधनों को रिलीज़ करता है।

--------------------

यह मेथड वास्तव में कुछ नहीं करता। यह केवल System.Drawing API के साथ संगतता के लिए है।

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


इस [Pen](../../com.aspose.drawing/pen) की सटीक प्रतिलिपि बनाता है।

**Returns:**
java.lang.Object - एक ऑब्जेक्ट जिसे एक [Pen](../../com.aspose.drawing/pen) में कास्ट किया जा सकता है।
### setLineCap(int startCap, int endCap, int dashCap) {#setLineCap-int-int-int-}
```
public final void setLineCap(int startCap, int endCap, int dashCap)
```


इस [Pen](../../com.aspose.drawing/pen) द्वारा खींची गई लाइनों के अंत में उपयोग किए जाने वाले कैप की शैली निर्धारित करने वाले मान सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| startCap | int | एक [LineCap](../../com.aspose.drawing.drawing2d/linecap) जो इस [Pen](../../com.aspose.drawing/pen) द्वारा खींची गई लाइनों की शुरुआत में उपयोग किए जाने वाले कैप शैली का प्रतिनिधित्व करता है। |
| endCap | int | एक [LineCap](../../com.aspose.drawing.drawing2d/linecap) जो इस [Pen](../../com.aspose.drawing/pen) द्वारा खींची गई लाइनों के अंत में उपयोग किए जाने वाले कैप शैली का प्रतिनिधित्व करता है। |
| dashCap | int | एक [LineCap](../../com.aspose.drawing.drawing2d/linecap) जो इस [Pen](../../com.aspose.drawing/pen) द्वारा खींची गई डैश्ड लाइनों की शुरुआत या अंत में उपयोग किए जाने वाले कैप शैली का प्रतिनिधित्व करता है। |

### scaleTransform(float sx, float sy) {#scaleTransform-float-float-}
```
public final void scaleTransform(float sx, float sy)
```


स्थानीय ज्यामितीय रूपांतरण को निर्दिष्ट गुणकों द्वारा स्केल करता है। यह मेथड स्केलिंग मैट्रिक्स को रूपांतरण के पहले जोड़ता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sx | फ़्लोट | x‑अक्ष दिशा में रूपांतरण को स्केल करने के लिए गुणक। |
| sy | फ़्लोट | y‑अक्ष दिशा में रूपांतरण को स्केल करने के लिए गुणक। |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public final void scaleTransform(float sx, float sy, int order)
```


निर्दिष्ट क्रम में निर्दिष्ट गुणकों द्वारा स्थानीय ज्यामितीय रूपांतरण को स्केल करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sx | फ़्लोट | x‑अक्ष दिशा में रूपांतरण को स्केल करने के लिए गुणक। |
| sy | फ़्लोट | y‑अक्ष दिशा में रूपांतरण को स्केल करने के लिए गुणक। |
| order | int | [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder) जो यह निर्धारित करता है कि स्केलिंग मैट्रिक्स को जोड़ना है या पहले जोड़ना है। |

### translateTransform(float dx, float dy) {#translateTransform-float-float-}
```
public final void translateTransform(float dx, float dy)
```


स्थानीय ज्यामितीय रूपांतरण को निर्दिष्ट आयामों द्वारा ट्रांसलेट करता है। यह मेथड ट्रांसलेशन को रूपांतरण के पहले जोड़ता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| dx | फ़्लोट | x में अनुवाद का मान। |
| dy | फ़्लोट | y में अनुवाद का मान। |

### translateTransform(float dx, float dy, int order) {#translateTransform-float-float-int-}
```
public final void translateTransform(float dx, float dy, int order)
```


निर्दिष्ट क्रम में निर्दिष्ट आयामों द्वारा स्थानीय ज्यामितीय रूपांतरण को ट्रांसलेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| dx | फ़्लोट | x में अनुवाद का मान। |
| dy | फ़्लोट | y में अनुवाद का मान। |
| क्रम | int | अनुवाद लागू करने का क्रम (पहले जोड़ना या बाद में जोड़ना)। |

### rotateTransform(float angle) {#rotateTransform-float-}
```
public final void rotateTransform(float angle)
```


स्थानीय ज्यामितीय रूपांतरण को निर्दिष्ट कोण द्वारा घुमाता है। यह मेथड रोटेशन को रूपांतरण के पहले जोड़ता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| कोण | फ़्लोट | घूर्णन का कोण। |

### rotateTransform(float angle, int order) {#rotateTransform-float-int-}
```
public final void rotateTransform(float angle, int order)
```


निर्दिष्ट क्रम में निर्दिष्ट कोण द्वारा स्थानीय ज्यामितीय रूपांतरण को घुमाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| कोण | फ़्लोट | घूर्णन का कोण। |
| order | int | [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder) जो यह निर्धारित करता है कि घूर्णन मैट्रिक्स को जोड़ना है या पहले जोड़ना है। |

### resetTransform() {#resetTransform--}
```
public final void resetTransform()
```


इस [Pen](../../com.aspose.drawing/pen) के लिए ज्यामितीय रूपांतरण मैट्रिक्स को पहचान (identity) पर रीसेट करता है।

### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-}
```
public final void multiplyTransform(Matrix matrix)
```


इस [Pen](../../com.aspose.drawing/pen) के रूपांतरण मैट्रिक्स को निर्दिष्ट [Matrix](../../com.aspose.drawing.drawing2d/matrix) से गुणा करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | रूपांतरण मैट्रिक्स को गुणा करने के लिए [Matrix](../../com.aspose.drawing.drawing2d/matrix) ऑब्जेक्ट। |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-int-}
```
public final void multiplyTransform(Matrix matrix, int order)
```


इस [Pen](../../com.aspose.drawing/pen) के रूपांतरण मैट्रिक्स को निर्दिष्ट क्रम में निर्दिष्ट [Matrix](../../com.aspose.drawing.drawing2d/matrix) से गुणा करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | रूपांतरण मैट्रिक्स को गुणा करने के लिए java.awt.geom.AffineTransform। |
| क्रम | int | गुणा ऑपरेशन को करने का क्रम। |

