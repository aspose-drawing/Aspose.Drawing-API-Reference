---
title: TextureBrush
second_title: Aspose.Drawing for Java API संदर्भ
description: TextureBrush क्लास की प्रत्येक प्रॉपर्टी एक Brush ऑब्जेक्ट होती है जो किसी आकार के अंदरूनी हिस्से को भरने के लिए इमेज का उपयोग करती है।
type: docs
weight: 53
url: /hi/java/com.aspose.drawing/texturebrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.drawing.Brush](../../com.aspose.drawing/brush)
```
public final class TextureBrush extends Brush
```

TextureBrush क्लास की प्रत्येक प्रॉपर्टी एक Brush ऑब्जेक्ट है जो किसी आकृति के भीतर को भरने के लिए छवि का उपयोग करती है। इस क्लास को विरासत में नहीं लिया जा सकता।
## निर्माता

| निर्माता | विवरण |
| --- | --- |
| [TextureBrush(Image bitmap)](#TextureBrush-com.aspose.drawing.Image-) | निर्दिष्ट छवि का उपयोग करने वाले [TextureBrush](../../com.aspose.drawing/texturebrush) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [TextureBrush(Image image, int wrapMode)](#TextureBrush-com.aspose.drawing.Image-int-) | निर्दिष्ट छवि और रैप मोड का उपयोग करने वाले [TextureBrush](../../com.aspose.drawing/texturebrush) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [TextureBrush(Image image, int wrapMode, RectangleF dstRect)](#TextureBrush-com.aspose.drawing.Image-int-com.aspose.drawing.RectangleF-) | निर्दिष्ट छवि, रैप मोड और बाउंडिंग रेक्टैंगल का उपयोग करने वाले [TextureBrush](../../com.aspose.drawing/texturebrush) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [TextureBrush(Image image, RectangleF dstRect)](#TextureBrush-com.aspose.drawing.Image-com.aspose.drawing.RectangleF-) | निर्दिष्ट छवि और बाउंडिंग आयत का उपयोग करने वाले [TextureBrush](../../com.aspose.drawing/texturebrush) वर्ग का नया उदाहरण प्रारंभ करता है। |
| [TextureBrush(Image image, RectangleF dstRect, ImageAttributes imageAttr)](#TextureBrush-com.aspose.drawing.Image-com.aspose.drawing.RectangleF-com.aspose.drawing.imaging.ImageAttributes-) | निर्दिष्ट छवि, बाउंडिंग आयत, और छवि गुणों का उपयोग करने वाले [TextureBrush](../../com.aspose.drawing/texturebrush) वर्ग का नया उदाहरण प्रारंभ करता है। |
## मेथड्स

| विधि | विवरण |
| --- | --- |
| [getImage()](#getImage--) | इस TextureBrush ऑब्जेक्ट से जुड़ी Image वस्तु प्राप्त करता है। |
| [getTransform()](#getTransform--) | इस TextureBrush ऑब्जेक्ट से जुड़ी छवि के लिए स्थानीय ज्यामितीय रूपांतरण निर्धारित करने वाले Matrix ऑब्जेक्ट की एक प्रति प्राप्त करता है। |
| [setTransform(Matrix value)](#setTransform-com.aspose.drawing.drawing2d.Matrix-) | इस TextureBrush ऑब्जेक्ट से जुड़ी छवि के लिए स्थानीय ज्यामितीय रूपांतरण निर्धारित करने वाले Matrix ऑब्जेक्ट की एक प्रति सेट करता है। |
| [getWrapMode()](#getWrapMode--) | इस TextureBrush ऑब्जेक्ट के रैप मोड को दर्शाने वाला WrapMode एन्यूमरेशन प्राप्त करता है। |
| [setWrapMode(int value)](#setWrapMode-int-) | इस TextureBrush ऑब्जेक्ट के रैप मोड को दर्शाने वाला WrapMode एन्यूमरेशन सेट करता है। |
| [deepClone()](#deepClone--) | इस [TextureBrush](../../com.aspose.drawing/texturebrush) ऑब्जेक्ट की एक सटीक प्रति बनाता है। |
| [resetTransform()](#resetTransform--) | इस [TextureBrush](../../com.aspose.drawing/texturebrush) ऑब्जेक्ट की Transform प्रॉपर्टी को पहचान (identity) पर रीसेट करता है। |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-) | इस [TextureBrush](../../com.aspose.drawing/texturebrush) ऑब्जेक्ट के स्थानीय ज्यामितीय रूपांतरण को दर्शाने वाले [Matrix](../../com.aspose.drawing.drawing2d/matrix) ऑब्जेक्ट को निर्दिष्ट [Matrix](../../com.aspose.drawing.drawing2d/matrix) ऑब्जेक्ट से पूर्व जोड़कर (prepend) गुणा करता है। |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-int-) | इस [TextureBrush](../../com.aspose.drawing/texturebrush) ऑब्जेक्ट के स्थानीय ज्यामितीय रूपांतरण को दर्शाने वाले [Matrix](../../com.aspose.drawing.drawing2d/matrix) ऑब्जेक्ट को निर्दिष्ट क्रम में निर्दिष्ट [Matrix](../../com.aspose.drawing.drawing2d/matrix) ऑब्जेक्ट से गुणा करता है। |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | निर्दिष्ट आयामों द्वारा इस [TextureBrush](../../com.aspose.drawing/texturebrush) ऑब्जेक्ट के स्थानीय ज्यामितीय रूपांतरण को अनुवादित करता है। |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | निर्दिष्ट क्रम में निर्दिष्ट आयामों द्वारा इस [TextureBrush](../../com.aspose.drawing/texturebrush) ऑब्जेक्ट के स्थानीय ज्यामितीय रूपांतरण को अनुवादित करता है। |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | निर्दिष्ट मात्राओं द्वारा इस [TextureBrush](../../com.aspose.drawing/texturebrush) ऑब्जेक्ट के स्थानीय ज्यामितीय रूपांतरण को स्केल करता है। |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | निर्दिष्ट क्रम में निर्दिष्ट मात्राओं द्वारा इस [TextureBrush](../../com.aspose.drawing/texturebrush) ऑब्जेक्ट के स्थानीय ज्यामितीय रूपांतरण को स्केल करता है। |
| [rotateTransform(float angle)](#rotateTransform-float-) | निर्दिष्ट मात्रा द्वारा इस [TextureBrush](../../com.aspose.drawing/texturebrush) ऑब्जेक्ट के स्थानीय ज्यामितीय रूपांतरण को घुमाता है। |
| [rotateTransform(float angle, int order)](#rotateTransform-float-int-) | निर्दिष्ट क्रम में निर्दिष्ट मात्रा द्वारा इस [TextureBrush](../../com.aspose.drawing/texturebrush) ऑब्जेक्ट के स्थानीय ज्यामितीय रूपांतरण को घुमाता है। |
### TextureBrush(Image bitmap) {#TextureBrush-com.aspose.drawing.Image-}
```
public TextureBrush(Image bitmap)
```


निर्दिष्ट छवि का उपयोग करने वाले [TextureBrush](../../com.aspose.drawing/texturebrush) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| bitmap | [Image](../../com.aspose.drawing/image) | `Image`([.getImage](../../null/\#getImage)) ऑब्जेक्ट जिसके साथ यह [TextureBrush](../../com.aspose.drawing/texturebrush) ऑब्जेक्ट आंतरिक भागों को भरता है। |

### TextureBrush(Image image, int wrapMode) {#TextureBrush-com.aspose.drawing.Image-int-}
```
public TextureBrush(Image image, int wrapMode)
```


निर्दिष्ट छवि और रैप मोड का उपयोग करने वाले [TextureBrush](../../com.aspose.drawing/texturebrush) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| image | [Image](../../com.aspose.drawing/image) | छवि। |
| wrapMode | int | `WrapMode`([.getWrapMode](../../null/\#getWrapMode)/[.setWrapMode(int)](../../null/\#setWrapMode-int-)) एन्यूमरेशन जो निर्दिष्ट करता है कि यह [TextureBrush](../../com.aspose.drawing/texturebrush) ऑब्जेक्ट कैसे टाइल किया जाता है। |

### TextureBrush(Image image, int wrapMode, RectangleF dstRect) {#TextureBrush-com.aspose.drawing.Image-int-com.aspose.drawing.RectangleF-}
```
public TextureBrush(Image image, int wrapMode, RectangleF dstRect)
```


निर्दिष्ट छवि, रैप मोड और बाउंडिंग रेक्टैंगल का उपयोग करने वाले [TextureBrush](../../com.aspose.drawing/texturebrush) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| image | [Image](../../com.aspose.drawing/image) | छवि। |
| wrapMode | int | `WrapMode`([.getWrapMode](../../null/\#getWrapMode)/[.setWrapMode(int)](../../null/\#setWrapMode-int-)) एन्यूमरेशन जो निर्दिष्ट करता है कि यह [TextureBrush](../../com.aspose.drawing/texturebrush) ऑब्जेक्ट कैसे टाइल किया जाता है। |
| dstRect | [RectangleF](../../com.aspose.drawing/rectanglef) | [RectangleF](../../com.aspose.drawing/rectanglef) संरचना जो इस [TextureBrush](../../com.aspose.drawing/texturebrush) ऑब्जेक्ट के बाउंडिंग आयत को दर्शाती है। |

### TextureBrush(Image image, RectangleF dstRect) {#TextureBrush-com.aspose.drawing.Image-com.aspose.drawing.RectangleF-}
```
public TextureBrush(Image image, RectangleF dstRect)
```


निर्दिष्ट छवि और बाउंडिंग आयत का उपयोग करने वाले [TextureBrush](../../com.aspose.drawing/texturebrush) वर्ग का नया उदाहरण प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| image | [Image](../../com.aspose.drawing/image) | `Image`([.getImage](../../null/\#getImage)) ऑब्जेक्ट जिसके साथ यह [TextureBrush](../../com.aspose.drawing/texturebrush) ऑब्जेक्ट आंतरिक भागों को भरता है। |
| dstRect | [RectangleF](../../com.aspose.drawing/rectanglef) | [RectangleF](../../com.aspose.drawing/rectanglef) संरचना जो इस [TextureBrush](../../com.aspose.drawing/texturebrush) ऑब्जेक्ट के बाउंडिंग आयत को दर्शाती है। |

### TextureBrush(Image image, RectangleF dstRect, ImageAttributes imageAttr) {#TextureBrush-com.aspose.drawing.Image-com.aspose.drawing.RectangleF-com.aspose.drawing.imaging.ImageAttributes-}
```
public TextureBrush(Image image, RectangleF dstRect, ImageAttributes imageAttr)
```


निर्दिष्ट छवि, बाउंडिंग आयत, और छवि गुणों का उपयोग करने वाले [TextureBrush](../../com.aspose.drawing/texturebrush) वर्ग का नया उदाहरण प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| image | [Image](../../com.aspose.drawing/image) | यह TextureBrush ऑब्जेक्ट जिस Image ऑब्जेक्ट के साथ आंतरिक भागों को भरता है। |
| dstRect | [RectangleF](../../com.aspose.drawing/rectanglef) | एक RectangleF संरचना जो इस TextureBrush ऑब्जेक्ट के बाउंडिंग आयत को दर्शाती है। |
| imageAttr | [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes) | एक ImageAttributes ऑब्जेक्ट जो इस TextureBrush ऑब्जेक्ट द्वारा उपयोग की गई छवि के बारे में अतिरिक्त जानकारी रखता है। |

### getImage() {#getImage--}
```
public Image getImage()
```


इस TextureBrush ऑब्जेक्ट से जुड़ी Image वस्तु प्राप्त करता है।

**Returns:**
[Image](../../com.aspose.drawing/image) - the Image object associated with this TextureBrush object.
### getTransform() {#getTransform--}
```
public Matrix getTransform()
```


इस TextureBrush ऑब्जेक्ट से जुड़ी छवि के लिए स्थानीय ज्यामितीय रूपांतरण निर्धारित करने वाले Matrix ऑब्जेक्ट की एक प्रति प्राप्त करता है।

**Returns:**
[Matrix](../../com.aspose.drawing.drawing2d/matrix) - a copy of the Matrix object that defines a local geometric transformation for the image associated with this TextureBrush object.
### setTransform(Matrix value) {#setTransform-com.aspose.drawing.drawing2d.Matrix-}
```
public void setTransform(Matrix value)
```


इस TextureBrush ऑब्जेक्ट से जुड़ी छवि के लिए स्थानीय ज्यामितीय रूपांतरण निर्धारित करने वाले Matrix ऑब्जेक्ट की एक प्रति सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | इस TextureBrush ऑब्जेक्ट से जुड़ी छवि के लिए स्थानीय ज्यामितीय रूपांतरण निर्धारित करने वाले Matrix ऑब्जेक्ट की एक प्रति। |

### getWrapMode() {#getWrapMode--}
```
public int getWrapMode()
```


इस TextureBrush ऑब्जेक्ट के रैप मोड को दर्शाने वाला WrapMode एन्यूमरेशन प्राप्त करता है।

**Returns:**
int - एक WrapMode enumeration जो इस TextureBrush ऑब्जेक्ट के लिए wrap मोड दर्शाता है।
### setWrapMode(int value) {#setWrapMode-int-}
```
public void setWrapMode(int value)
```


इस TextureBrush ऑब्जेक्ट के रैप मोड को दर्शाने वाला WrapMode एन्यूमरेशन सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int | एक WrapMode enumeration जो इस TextureBrush ऑब्जेक्ट के लिए wrap मोड दर्शाता है। |

### deepClone() {#deepClone--}
```
public Object deepClone()
```


इस [TextureBrush](../../com.aspose.drawing/texturebrush) ऑब्जेक्ट की एक सटीक प्रति बनाता है।

**Returns:**
java.lang.Object - वह [TextureBrush](../../com.aspose.drawing/texturebrush) ऑब्जेक्ट जिसे यह मेथड बनाता है, जिसे Object ऑब्जेक्ट के रूप में कास्ट किया गया है।
### resetTransform() {#resetTransform--}
```
public void resetTransform()
```


इस [TextureBrush](../../com.aspose.drawing/texturebrush) ऑब्जेक्ट की Transform प्रॉपर्टी को पहचान (identity) पर रीसेट करता है।

### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-}
```
public void multiplyTransform(Matrix matrix)
```


इस [TextureBrush](../../com.aspose.drawing/texturebrush) ऑब्जेक्ट के स्थानीय ज्यामितीय रूपांतरण को दर्शाने वाले [Matrix](../../com.aspose.drawing.drawing2d/matrix) ऑब्जेक्ट को निर्दिष्ट [Matrix](../../com.aspose.drawing.drawing2d/matrix) ऑब्जेक्ट से पूर्व जोड़कर (prepend) गुणा करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | वह [Matrix](../../com.aspose.drawing.drawing2d/matrix) ऑब्जेक्ट जिससे ज्यामितीय ट्रांसफ़ॉर्मेशन को गुणा किया जाता है। |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-int-}
```
public void multiplyTransform(Matrix matrix, int order)
```


इस [TextureBrush](../../com.aspose.drawing/texturebrush) ऑब्जेक्ट के स्थानीय ज्यामितीय रूपांतरण को दर्शाने वाले [Matrix](../../com.aspose.drawing.drawing2d/matrix) ऑब्जेक्ट को निर्दिष्ट क्रम में निर्दिष्ट [Matrix](../../com.aspose.drawing.drawing2d/matrix) ऑब्जेक्ट से गुणा करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | वह [Matrix](../../com.aspose.drawing.drawing2d/matrix) ऑब्जेक्ट जिससे ज्यामितीय ट्रांसफ़ॉर्मेशन को गुणा किया जाता है। |
| order | int | एक [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder) enumeration जो दो मैट्रिसेज़ को गुणा करने के क्रम को निर्दिष्ट करता है। |

### translateTransform(float dx, float dy) {#translateTransform-float-float-}
```
public void translateTransform(float dx, float dy)
```


इस [TextureBrush](../../com.aspose.drawing/texturebrush) ऑब्जेक्ट के स्थानीय ज्यामितीय ट्रांसफ़ॉर्मेशन को निर्दिष्ट आयामों द्वारा ट्रांसलेट करता है। यह मेथड ट्रांसलेशन को ट्रांसफ़ॉर्मेशन के पहले जोड़ता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| dx | फ़्लोट | ट्रांसफ़ॉर्मेशन को x दिशा में ट्रांसलेट करने के लिए आयाम। |
| dy | फ़्लोट | ट्रांसफ़ॉर्मेशन को y दिशा में ट्रांसलेट करने के लिए आयाम। |

### translateTransform(float dx, float dy, int order) {#translateTransform-float-float-int-}
```
public void translateTransform(float dx, float dy, int order)
```


निर्दिष्ट क्रम में निर्दिष्ट आयामों द्वारा इस [TextureBrush](../../com.aspose.drawing/texturebrush) ऑब्जेक्ट के स्थानीय ज्यामितीय रूपांतरण को अनुवादित करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| dx | फ़्लोट | ट्रांसफ़ॉर्मेशन को x दिशा में ट्रांसलेट करने के लिए आयाम। |
| dy | फ़्लोट | ट्रांसफ़ॉर्मेशन को y दिशा में ट्रांसलेट करने के लिए आयाम। |
| क्रम | int | अनुवाद लागू करने का क्रम (पहले जोड़ना या बाद में जोड़ना)। |

### scaleTransform(float sx, float sy) {#scaleTransform-float-float-}
```
public void scaleTransform(float sx, float sy)
```


निर्दिष्ट मात्रा द्वारा इस [TextureBrush](../../com.aspose.drawing/texturebrush) ऑब्जेक्ट के स्थानीय ज्यामितीय ट्रांसफ़ॉर्मेशन को स्केल करता है। यह मेथड स्केलिंग मैट्रिक्स को ट्रांसफ़ॉर्मेशन के पहले जोड़ता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sx | फ़्लोट | x दिशा में ट्रांसफ़ॉर्मेशन को स्केल करने की मात्रा। |
| sy | फ़्लोट | y दिशा में ट्रांसफ़ॉर्मेशन को स्केल करने की मात्रा। |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public void scaleTransform(float sx, float sy, int order)
```


निर्दिष्ट क्रम में निर्दिष्ट मात्राओं द्वारा इस [TextureBrush](../../com.aspose.drawing/texturebrush) ऑब्जेक्ट के स्थानीय ज्यामितीय रूपांतरण को स्केल करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sx | फ़्लोट | x दिशा में ट्रांसफ़ॉर्मेशन को स्केल करने की मात्रा। |
| sy | फ़्लोट | y दिशा में ट्रांसफ़ॉर्मेशन को स्केल करने की मात्रा। |
| order | int | एक [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder) enumeration जो यह निर्दिष्ट करता है कि स्केलिंग मैट्रिक्स को जोड़ना है या पहले जोड़ना है। |

### rotateTransform(float angle) {#rotateTransform-float-}
```
public void rotateTransform(float angle)
```


निर्दिष्ट मात्रा द्वारा इस [TextureBrush](../../com.aspose.drawing/texturebrush) ऑब्जेक्ट के स्थानीय ज्यामितीय ट्रांसफ़ॉर्मेशन को घुमाता है। यह मेथड रोटेशन को ट्रांसफ़ॉर्मेशन के पहले जोड़ता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| कोण | फ़्लोट | घूर्णन का कोण। |

### rotateTransform(float angle, int order) {#rotateTransform-float-int-}
```
public void rotateTransform(float angle, int order)
```


निर्दिष्ट क्रम में निर्दिष्ट मात्रा द्वारा इस [TextureBrush](../../com.aspose.drawing/texturebrush) ऑब्जेक्ट के स्थानीय ज्यामितीय रूपांतरण को घुमाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| कोण | फ़्लोट | घूर्णन का कोण। |
| order | int | एक [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder) enumeration जो यह निर्दिष्ट करता है कि रोटेशन मैट्रिक्स को जोड़ना है या पहले जोड़ना है। |

