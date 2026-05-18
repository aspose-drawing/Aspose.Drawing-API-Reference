---
title: RectangleF
second_title: Aspose.Drawing for Java API संदर्भ
description: चार फ्लोटिंग-पॉइंट संख्याओं का एक सेट संग्रहीत करता है जो आयत के स्थान और आकार को दर्शाते हैं।
type: docs
weight: 39
url: /hi/java/com.aspose.drawing/rectanglef/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable, java.lang.Cloneable
```
public class RectangleF extends Struct<RectangleF> implements System.IEquatable<RectangleF>, Cloneable
```

एक आयत की स्थिति और आकार को दर्शाने वाले चार फ्लोटिंग-पॉइंट संख्याओं का सेट संग्रहीत करता है। अधिक उन्नत रीजन फ़ंक्शनों के लिए, Region ऑब्जेक्ट का उपयोग करें।
## निर्माता

| निर्माता | विवरण |
| --- | --- |
| [RectangleF()](#RectangleF--) |  |
| [RectangleF(PointF location, SizeF size)](#RectangleF-com.aspose.drawing.PointF-com.aspose.drawing.SizeF-) | निर्दिष्ट स्थिति और आकार के साथ RectangleF संरचना का नया उदाहरण प्रारंभ करता है। |
| [RectangleF(float x, float y, float width, float height)](#RectangleF-float-float-float-float-) | निर्दिष्ट स्थिति और आकार के साथ RectangleF संरचना का नया उदाहरण प्रारंभ करता है। |
## मेथड्स

| विधि | विवरण |
| --- | --- |
| [fromPoints(PointF point1, PointF point2)](#fromPoints-com.aspose.drawing.PointF-com.aspose.drawing.PointF-) | दो बिंदुओं से एक नया आयत बनाता है। |
| [to_RectangleF(Rectangle r)](#to-RectangleF-com.aspose.drawing.Rectangle-) | निर्दिष्ट Rectangle संरचना को RectangleF संरचना में परिवर्तित करता है। |
| [op_Equality(RectangleF left, RectangleF right)](#op-Equality-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-) | जाँचता है कि दो [RectangleF](../../com.aspose.drawing/rectanglef) संरचनाओं की स्थिति और आकार समान हैं या नहीं। |
| [op_Inequality(RectangleF left, RectangleF right)](#op-Inequality-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-) | जाँचता है कि दो [RectangleF](../../com.aspose.drawing/rectanglef) संरचनाओं की स्थिति या आकार में अंतर है या नहीं। |
| [fromLTRB(float left, float top, float right, float bottom)](#fromLTRB-float-float-float-float-) | निर्दिष्ट स्थानों पर ऊपरी-बाएँ और निचले-दाएँ कोने के साथ RectangleF संरचना बनाता है। |
| [inflate(RectangleF rect, float x, float y)](#inflate-com.aspose.drawing.RectangleF-float-float-) | निर्दिष्ट [RectangleF](../../com.aspose.drawing/rectanglef) संरचना की फुली हुई प्रति बनाता और लौटाता है। |
| [intersect(RectangleF a, RectangleF b)](#intersect-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-) | दो आयतों के प्रतिच्छेदन को दर्शाने वाली [RectangleF](../../com.aspose.drawing/rectanglef) संरचना लौटाता है। |
| [union(RectangleF a, RectangleF b)](#union-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-) | दो आयतों के संघ को समाहित करने वाला सबसे छोटा संभावित तीसरा आयत बनाता है। |
| [isEquals(RectangleF obj1, RectangleF obj2)](#isEquals-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-) |  |
| [getEmpty()](#getEmpty--) |  |
| [isEmpty()](#isEmpty--) | प्राप्त करता है वह मान जो दर्शाता है कि इस [RectangleF](../../aspose.drawing/rectanglef) की `RectangleF.Width` या `RectangleF.Height` प्रॉपर्टी का मान शून्य है या नहीं। |
| [getX()](#getX--) | इस RectangleF संरचना के ऊपरी-बाएँ कोने का x-निर्देशांक प्राप्त करता है। |
| [setX(float value)](#setX-float-) | इस RectangleF संरचना के ऊपरी-बाएँ कोने का x-निर्देशांक सेट करता है। |
| [getY()](#getY--) | इस RectangleF संरचना के ऊपरी-बाएँ कोने का x-निर्देशांक प्राप्त करता है। |
| [setY(float value)](#setY-float-) | इस RectangleF संरचना के ऊपरी-बाएँ कोने का x-निर्देशांक सेट करता है। |
| [getLocation()](#getLocation--) | इस [RectangleF](../../aspose.drawing/rectanglef) संरचना के ऊपरी-बाएँ कोने के निर्देशांक प्राप्त करता है। |
| [setLocation(PointF value)](#setLocation-com.aspose.drawing.PointF-) | इस [RectangleF](../../com.aspose.drawing/rectanglef) संरचना के ऊपर-बाएँ कोने के निर्देशांक सेट करता है। |
| [getWidth()](#getWidth--) | इस RectangleF संरचना की चौड़ाई प्राप्त करता है। |
| [setWidth(float value)](#setWidth-float-) | इस RectangleF संरचना की चौड़ाई सेट करता है। |
| [getHeight()](#getHeight--) | इस RectangleF संरचना की ऊँचाई प्राप्त करता है। |
| [setHeight(float value)](#setHeight-float-) | इस RectangleF संरचना की ऊँचाई सेट करता है। |
| [getSize()](#getSize--) | इस [RectangleF](../../com.aspose.drawing/rectanglef) का आकार प्राप्त करता है। |
| [setSize(SizeF value)](#setSize-com.aspose.drawing.SizeF-) | इस [RectangleF](../../com.aspose.drawing/rectanglef) का आकार सेट करता है। |
| [getLeft()](#getLeft--) | इस RectangleF संरचना के बाएँ किनारे का x-निर्देशांक प्राप्त करता है। |
| [getTop()](#getTop--) | इस RectangleF संरचना के शीर्ष किनारे का y-निर्देशांक प्राप्त करता है। |
| [getRight()](#getRight--) | इस RectangleF संरचना के X और Width का योग होने वाला x-निर्देशांक प्राप्त करता है। |
| [getBottom()](#getBottom--) | इस RectangleF संरचना के Y और Height का योग होने वाला y-निर्देशांक प्राप्त करता है। |
| [toString()](#toString--) |  |
| [inflate(float x, float y)](#inflate-float-float-) | निर्दिष्ट मात्रा से इस [RectangleF](../../com.aspose.drawing/rectanglef) संरचना को विस्तारित करता है। |
| [inflate(SizeF size)](#inflate-com.aspose.drawing.SizeF-) | निर्दिष्ट मात्रा से इस [RectangleF](../../com.aspose.drawing/rectanglef) को विस्तारित करता है। |
| [intersect(RectangleF rect)](#intersect-com.aspose.drawing.RectangleF-) | इस [RectangleF](../../com.aspose.drawing/rectanglef) संरचना को स्वयं और निर्दिष्ट [RectangleF](../../com.aspose.drawing/rectanglef) संरचना के प्रतिच्छेदन से बदलता है। |
| [intersectsWith(RectangleF rect)](#intersectsWith-com.aspose.drawing.RectangleF-) | निर्धारित करता है कि यह आयत `rect` के साथ प्रतिच्छेद करता है या नहीं। |
| [offset(PointF pos)](#offset-com.aspose.drawing.PointF-) | निर्दिष्ट मात्रा से इस आयत का स्थान समायोजित करता है। |
| [offset(float x, float y)](#offset-float-float-) | निर्दिष्ट मात्रा से इस आयत का स्थान समायोजित करता है। |
| [contains(float x, float y)](#contains-float-float-) | निर्धारित करता है कि निर्दिष्ट बिंदु इस [RectangleF](../../com.aspose.drawing/rectanglef) संरचना के भीतर सम्मिलित है या नहीं। |
| [contains(PointF pt)](#contains-com.aspose.drawing.PointF-) | निर्धारित करता है कि निर्दिष्ट बिंदु इस [RectangleF](../../com.aspose.drawing/rectanglef) संरचना के भीतर सम्मिलित है या नहीं। |
| [contains(RectangleF rect)](#contains-com.aspose.drawing.RectangleF-) | निर्धारित करता है कि `rect` द्वारा प्रतिनिधित्व किया गया आयताकार क्षेत्र पूरी तरह से इस [RectangleF](../../com.aspose.drawing/rectanglef) संरचना के भीतर सम्मिलित है या नहीं। |
| [equals(Object obj)](#equals-java.lang.Object-) | निर्धारित करता है कि निर्दिष्ट ऑब्जेक्ट इस इंस्टेंस के बराबर है या नहीं। |
| [hashCode()](#hashCode--) | इस इंस्टेंस के लिए एक हैश कोड लौटाता है। |
| [equals(RectangleF other)](#equals-com.aspose.drawing.RectangleF-) | परीक्षण करता है कि अन्य [RectangleF](../../com.aspose.drawing/rectanglef) संरचना का स्थान और आकार इस [RectangleF](../../com.aspose.drawing/rectanglef) संरचना के समान है या नहीं। |
| [CloneTo(RectangleF that)](#CloneTo-com.aspose.drawing.RectangleF-) |  |
| [Clone()](#Clone--) |  |
| [clone()](#clone--) |  |
### RectangleF() {#RectangleF--}
```
public RectangleF()
```


### RectangleF(PointF location, SizeF size) {#RectangleF-com.aspose.drawing.PointF-com.aspose.drawing.SizeF-}
```
public RectangleF(PointF location, SizeF size)
```


निर्दिष्ट स्थिति और आकार के साथ RectangleF संरचना का नया उदाहरण प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| location | [PointF](../../com.aspose.drawing/pointf) | एक PointF जो आयताकार क्षेत्र के ऊपर-बाएँ कोने का प्रतिनिधित्व करता है। |
| size | [SizeF](../../com.aspose.drawing/sizef) | एक SizeF जो आयताकार क्षेत्र की चौड़ाई और ऊँचाई का प्रतिनिधित्व करता है। |

### RectangleF(float x, float y, float width, float height) {#RectangleF-float-float-float-float-}
```
public RectangleF(float x, float y, float width, float height)
```


निर्दिष्ट स्थिति और आकार के साथ RectangleF संरचना का नया उदाहरण प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | फ़्लोट | आयत के ऊपर-बाएँ कोने का x-निर्देशांक। |
| y | फ़्लोट | आयत के ऊपर-बाएँ कोने का y-निर्देशांक। |
| चौड़ाई | फ़्लोट | आयत की चौड़ाई। |
| ऊँचाई | फ़्लोट | आयत की ऊँचाई। |

### fromPoints(PointF point1, PointF point2) {#fromPoints-com.aspose.drawing.PointF-com.aspose.drawing.PointF-}
```
public static RectangleF fromPoints(PointF point1, PointF point2)
```


दो बिंदुओं से एक नया आयत बनाता है। निर्मित आयत को (बाएँ,ऊपर) (दाएँ,नीचे) से कम होने के अनुसार सामान्यीकृत किया जाएगा।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| point1 | [PointF](../../com.aspose.drawing/pointf) | पहला बिंदु। |
| point2 | [PointF](../../com.aspose.drawing/pointf) | दूसरा बिंदु। |

**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef) - A newly created rectangle.
### to_RectangleF(Rectangle r) {#to-RectangleF-com.aspose.drawing.Rectangle-}
```
public static RectangleF to_RectangleF(Rectangle r)
```


निर्दिष्ट Rectangle संरचना को RectangleF संरचना में परिवर्तित करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| r | [Rectangle](../../com.aspose.drawing/rectangle) | परिवर्तित करने के लिए Rectangle संरचना। |

**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef) - The RectangleF structure that is converted from the specified Rectangle structure.
### op_Equality(RectangleF left, RectangleF right) {#op-Equality-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-}
```
public static boolean op_Equality(RectangleF left, RectangleF right)
```


जाँचता है कि दो [RectangleF](../../com.aspose.drawing/rectanglef) संरचनाओं की स्थिति और आकार समान हैं या नहीं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| left | [RectangleF](../../com.aspose.drawing/rectanglef) | समानता ऑपरेटर के बाएँ स्थित [RectangleF](../../com.aspose.drawing/rectanglef) संरचना। |
| right | [RectangleF](../../com.aspose.drawing/rectanglef) | समानता ऑपरेटर के दाएँ स्थित [RectangleF](../../com.aspose.drawing/rectanglef) संरचना। |

**Returns:**
boolean - यह ऑपरेटर true लौटाता है यदि दो निर्दिष्ट [RectangleF](../../com.aspose.drawing/rectanglef) संरचनाओं के `RectangleF.X`, `RectangleF.Y`, `RectangleF.Width`, और `RectangleF.Height` गुण समान हों।
### op_Inequality(RectangleF left, RectangleF right) {#op-Inequality-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-}
```
public static boolean op_Inequality(RectangleF left, RectangleF right)
```


जाँचता है कि दो [RectangleF](../../com.aspose.drawing/rectanglef) संरचनाओं की स्थिति या आकार में अंतर है या नहीं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| left | [RectangleF](../../com.aspose.drawing/rectanglef) | असमानता ऑपरेटर के बाएँ स्थित [RectangleF](../../com.aspose.drawing/rectanglef) संरचना। |
| right | [RectangleF](../../com.aspose.drawing/rectanglef) | असमानता ऑपरेटर के दाएँ स्थित [RectangleF](../../com.aspose.drawing/rectanglef) संरचना। |

**Returns:**
boolean - यह ऑपरेटर true लौटाता है यदि दो [Rectangle](../../com.aspose.drawing/rectangle) संरचनाओं के `RectangleF.X`, `RectangleF.Y`, `RectangleF.Width`, या `RectangleF.Height` गुणों में से कोई भी असमान हो; अन्यथा false।
### fromLTRB(float left, float top, float right, float bottom) {#fromLTRB-float-float-float-float-}
```
public static RectangleF fromLTRB(float left, float top, float right, float bottom)
```


निर्दिष्ट स्थानों पर ऊपरी-बाएँ और निचले-दाएँ कोने के साथ RectangleF संरचना बनाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| बाएँ | फ़्लोट | आयताकार क्षेत्र के ऊपर-बाएँ कोने का x-निर्देशांक। |
| ऊपर | फ़्लोट | आयताकार क्षेत्र के ऊपर-बाएँ कोने का y-निर्देशांक। |
| दाएँ | फ़्लोट | आयताकार क्षेत्र के नीचे-दाएँ कोने का x-निर्देशांक। |
| नीचे | फ़्लोट | आयताकार क्षेत्र के नीचे-दाएँ कोने का y-निर्देशांक। |

**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef) - The new RectangleF that this method creates.
### inflate(RectangleF rect, float x, float y) {#inflate-com.aspose.drawing.RectangleF-float-float-}
```
public static RectangleF inflate(RectangleF rect, float x, float y)
```


निर्दिष्ट [RectangleF](../../com.aspose.drawing/rectanglef) संरचना की एक विस्तारित प्रति बनाता और लौटाता है। प्रति को निर्दिष्ट मात्रा से विस्तारित किया जाता है। मूल आयत अपरिवर्तित रहती है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | कॉपी की जाने वाली [RectangleF](../../com.aspose.drawing/rectanglef) संरचना। यह आयत संशोधित नहीं की जाती। |
| x | फ़्लोट | आयत की प्रति को क्षैतिज रूप से विस्तारित करने की मात्रा। |
| y | फ़्लोट | आयत की प्रति को ऊर्ध्वाधर रूप से फुलाने की मात्रा। |

**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef) - The inflated [RectangleF](../../com.aspose.drawing/rectanglef).
### intersect(RectangleF a, RectangleF b) {#intersect-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-}
```
public static RectangleF intersect(RectangleF a, RectangleF b)
```


दो आयतों के प्रतिच्छेदन को दर्शाने वाली एक [RectangleF](../../com.aspose.drawing/rectanglef) संरचना लौटाता है। यदि कोई प्रतिच्छेदन नहीं है, तो एक खाली [RectangleF](../../com.aspose.drawing/rectanglef) लौटाया जाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| a | [RectangleF](../../com.aspose.drawing/rectanglef) | पहला आयत जिसका प्रतिच्छेदन होना है। |
| b | [RectangleF](../../com.aspose.drawing/rectanglef) | दूसरा आयत जिसका प्रतिच्छेदन होना है। |

**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef) - A third [RectangleF](../../com.aspose.drawing/rectanglef) structure the size of which represents the overlapped area of the two specified rectangles.
### union(RectangleF a, RectangleF b) {#union-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-}
```
public static RectangleF union(RectangleF a, RectangleF b)
```


दो आयतों के संघ को समाहित करने वाला सबसे छोटा संभावित तीसरा आयत बनाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| a | [RectangleF](../../com.aspose.drawing/rectanglef) | पहला आयत जिसका संघ होना है। |
| b | [RectangleF](../../com.aspose.drawing/rectanglef) | दूसरा आयत जिसका संघ होना है। |

**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef) - A third [RectangleF](../../com.aspose.drawing/rectanglef) structure that contains both of the two rectangles that form the union.
### isEquals(RectangleF obj1, RectangleF obj2) {#isEquals-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-}
```
public static boolean isEquals(RectangleF obj1, RectangleF obj2)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj1 | [RectangleF](../../com.aspose.drawing/rectanglef) |  |
| obj2 | [RectangleF](../../com.aspose.drawing/rectanglef) |  |

**Returns:**
boolean
### getEmpty() {#getEmpty--}
```
public static RectangleF getEmpty()
```




**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef)
### isEmpty() {#isEmpty--}
```
public final boolean isEmpty()
```


प्राप्त करता है वह मान जो दर्शाता है कि इस [RectangleF](../../aspose.drawing/rectanglef) की `RectangleF.Width` या `RectangleF.Height` प्रॉपर्टी का मान शून्य है या नहीं।

**Returns:**
boolean - यह गुण true लौटाता है यदि इस [RectangleF](../../com.aspose.drawing/rectanglef) की `RectangleF.Width` या `P:RectangleF.Height` गुण का मान शून्य है; अन्यथा false।
### getX() {#getX--}
```
public final float getX()
```


इस RectangleF संरचना के ऊपरी-बाएँ कोने का x-निर्देशांक प्राप्त करता है।

**Returns:**
float - इस RectangleF संरचना के ऊपर-बाएँ कोने का x-निर्देशांक।
### setX(float value) {#setX-float-}
```
public final void setX(float value)
```


इस RectangleF संरचना के ऊपरी-बाएँ कोने का x-निर्देशांक सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | फ़्लोट | इस RectangleF संरचना के ऊपर-बाएँ कोने का x-निर्देशांक। |

### getY() {#getY--}
```
public final float getY()
```


इस RectangleF संरचना के ऊपरी-बाएँ कोने का x-निर्देशांक प्राप्त करता है।

**Returns:**
float - इस RectangleF संरचना के ऊपर-बाएँ कोने का x-निर्देशांक।
### setY(float value) {#setY-float-}
```
public final void setY(float value)
```


इस RectangleF संरचना के ऊपरी-बाएँ कोने का x-निर्देशांक सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | फ़्लोट | इस RectangleF संरचना के ऊपर-बाएँ कोने का x-निर्देशांक। |

### getLocation() {#getLocation--}
```
public final PointF getLocation()
```


इस [RectangleF](../../aspose.drawing/rectanglef) संरचना के ऊपरी-बाएँ कोने के निर्देशांक प्राप्त करता है।

**Returns:**
[PointF](../../com.aspose.drawing/pointf) - A [PointF](../../com.aspose.drawing/pointf) that represents the upper-left corner of this [RectangleF](../../com.aspose.drawing/rectanglef) structure.
### setLocation(PointF value) {#setLocation-com.aspose.drawing.PointF-}
```
public final void setLocation(PointF value)
```


इस [RectangleF](../../com.aspose.drawing/rectanglef) संरचना के ऊपर-बाएँ कोने के निर्देशांक सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [PointF](../../com.aspose.drawing/pointf) | इस [RectangleF](../../com.aspose.drawing/rectanglef) संरचना के ऊपर-बाएँ कोने के निर्देशांक। |

### getWidth() {#getWidth--}
```
public final float getWidth()
```


इस RectangleF संरचना की चौड़ाई प्राप्त करता है।

**Returns:**
float - इस RectangleF संरचना की चौड़ाई।
### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```


इस RectangleF संरचना की चौड़ाई सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | फ़्लोट | इस RectangleF संरचना की चौड़ाई। |

### getHeight() {#getHeight--}
```
public final float getHeight()
```


इस RectangleF संरचना की ऊँचाई प्राप्त करता है।

**Returns:**
float - इस RectangleF संरचना की ऊँचाई।
### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```


इस RectangleF संरचना की ऊँचाई सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | फ़्लोट | इस RectangleF संरचना की ऊँचाई। |

### getSize() {#getSize--}
```
public final SizeF getSize()
```


इस [RectangleF](../../com.aspose.drawing/rectanglef) का आकार प्राप्त करता है।

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - A [SizeF](../../com.aspose.drawing/sizef) that represents the width and height of this [RectangleF](../../com.aspose.drawing/rectanglef) structure.
### setSize(SizeF value) {#setSize-com.aspose.drawing.SizeF-}
```
public final void setSize(SizeF value)
```


इस [RectangleF](../../com.aspose.drawing/rectanglef) का आकार सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.drawing/sizef) | इस [RectangleF](../../com.aspose.drawing/rectanglef) का आकार। |

### getLeft() {#getLeft--}
```
public final float getLeft()
```


इस RectangleF संरचना के बाएँ किनारे का x-निर्देशांक प्राप्त करता है।

**Returns:**
float - इस RectangleF संरचना के बाएँ किनारे का x-निर्देशांक।
### getTop() {#getTop--}
```
public final float getTop()
```


इस RectangleF संरचना के शीर्ष किनारे का y-निर्देशांक प्राप्त करता है।

**Returns:**
float - इस RectangleF संरचना के शीर्ष किनारे का y-निर्देशांक।
### getRight() {#getRight--}
```
public final float getRight()
```


इस RectangleF संरचना के X और Width का योग होने वाला x-निर्देशांक प्राप्त करता है।

**Returns:**
float - इस RectangleF संरचना के X और Width का योग होने वाला x-निर्देशांक।
### getBottom() {#getBottom--}
```
public final float getBottom()
```


इस RectangleF संरचना के Y और Height का योग होने वाला y-निर्देशांक प्राप्त करता है।

**Returns:**
float - इस RectangleF संरचना के Y और Height का योग होने वाला y-निर्देशांक।
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### inflate(float x, float y) {#inflate-float-float-}
```
public final void inflate(float x, float y)
```


निर्दिष्ट मात्रा से इस [RectangleF](../../com.aspose.drawing/rectanglef) संरचना को विस्तारित करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | float | इस [RectangleF](../../com.aspose.drawing/rectanglef) संरचना को क्षैतिज रूप से फुलाने की मात्रा। |
| y | float | इस [RectangleF](../../com.aspose.drawing/rectanglef) संरचना को ऊर्ध्वाधर रूप से फुलाने की मात्रा। |

### inflate(SizeF size) {#inflate-com.aspose.drawing.SizeF-}
```
public final void inflate(SizeF size)
```


निर्दिष्ट मात्रा से इस [RectangleF](../../com.aspose.drawing/rectanglef) को विस्तारित करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.drawing/sizef) | इस आयत को फुलाने की मात्रा। |

### intersect(RectangleF rect) {#intersect-com.aspose.drawing.RectangleF-}
```
public final void intersect(RectangleF rect)
```


इस [RectangleF](../../com.aspose.drawing/rectanglef) संरचना को स्वयं और निर्दिष्ट [RectangleF](../../com.aspose.drawing/rectanglef) संरचना के प्रतिच्छेदन से बदलता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | प्रतिच्छेदन के लिए आयत। |

### intersectsWith(RectangleF rect) {#intersectsWith-com.aspose.drawing.RectangleF-}
```
public final boolean intersectsWith(RectangleF rect)
```


निर्धारित करता है कि यह आयत `rect` के साथ प्रतिच्छेद करता है या नहीं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | परीक्षण के लिए आयत। |

**Returns:**
boolean - यह विधि true लौटाती है यदि कोई भी प्रतिच्छेदन हो।
### offset(PointF pos) {#offset-com.aspose.drawing.PointF-}
```
public final void offset(PointF pos)
```


निर्दिष्ट मात्रा से इस आयत का स्थान समायोजित करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pos | [PointF](../../com.aspose.drawing/pointf) | स्थान को ऑफसेट करने की मात्रा। |

### offset(float x, float y) {#offset-float-float-}
```
public final void offset(float x, float y)
```


निर्दिष्ट मात्रा से इस आयत का स्थान समायोजित करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | फ़्लोट | स्थान को क्षैतिज रूप से ऑफसेट करने की मात्रा। |
| y | फ़्लोट | स्थान को लंबवत रूप से ऑफसेट करने की मात्रा। |

### contains(float x, float y) {#contains-float-float-}
```
public final boolean contains(float x, float y)
```


निर्धारित करता है कि निर्दिष्ट बिंदु इस [RectangleF](../../com.aspose.drawing/rectanglef) संरचना के भीतर सम्मिलित है या नहीं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | फ़्लोट | परीक्षण बिंदु का x-निर्देशांक। |
| y | फ़्लोट | परीक्षण बिंदु का y-निर्देशांक। |

**Returns:**
boolean - यह विधि `true` लौटाती है यदि x और y द्वारा परिभाषित बिंदु इस [RectangleF](../../com.aspose.drawing/rectanglef) संरचना के भीतर स्थित है; अन्यथा `false`।
### contains(PointF pt) {#contains-com.aspose.drawing.PointF-}
```
public final boolean contains(PointF pt)
```


निर्धारित करता है कि निर्दिष्ट बिंदु इस [RectangleF](../../com.aspose.drawing/rectanglef) संरचना के भीतर सम्मिलित है या नहीं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pt | [PointF](../../com.aspose.drawing/pointf) | परीक्षण के लिए [PointF](../../com.aspose.drawing/pointf)। |

**Returns:**
boolean - यह विधि `true` लौटाती है यदि pt पैरामीटर द्वारा प्रतिनिधित्व किया गया बिंदु इस [RectangleF](../../com.aspose.drawing/rectanglef) संरचना के भीतर स्थित है; अन्यथा `false`।
### contains(RectangleF rect) {#contains-com.aspose.drawing.RectangleF-}
```
public final boolean contains(RectangleF rect)
```


निर्धारित करता है कि `rect` द्वारा प्रतिनिधित्व किया गया आयताकार क्षेत्र पूरी तरह से इस [RectangleF](../../com.aspose.drawing/rectanglef) संरचना के भीतर सम्मिलित है या नहीं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | परीक्षण के लिए [RectangleF](../../com.aspose.drawing/rectanglef)। |

**Returns:**
boolean - यह विधि `true` लौटाती है यदि `rect` द्वारा प्रतिनिधित्व किया गया आयताकार क्षेत्र पूरी तरह से इस [RectangleF](../../com.aspose.drawing/rectanglef) द्वारा प्रतिनिधित्व किए गए आयताकार क्षेत्र के भीतर स्थित है; अन्यथा `false`।
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


निर्धारित करता है कि निर्दिष्ट ऑब्जेक्ट इस इंस्टेंस के बराबर है या नहीं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | java.lang.Object | इस उदाहरण के साथ तुलना करने के लिए ऑब्जेक्ट। |

**Returns:**
boolean - यदि निर्दिष्ट ऑब्जेक्ट इस उदाहरण के बराबर है तो `true`; अन्यथा `false`।
### hashCode() {#hashCode--}
```
public int hashCode()
```


इस इंस्टेंस के लिए एक हैश कोड लौटाता है।

**Returns:**
int - इस उदाहरण के लिए एक हैश कोड, जो हैशिंग एल्गोरिदम और हैश टेबल जैसी डेटा संरचनाओं में उपयोग के लिए उपयुक्त है।
### equals(RectangleF other) {#equals-com.aspose.drawing.RectangleF-}
```
public final boolean equals(RectangleF other)
```


परीक्षण करता है कि अन्य [RectangleF](../../com.aspose.drawing/rectanglef) संरचना का स्थान और आकार इस [RectangleF](../../com.aspose.drawing/rectanglef) संरचना के समान है या नहीं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| other | [RectangleF](../../com.aspose.drawing/rectanglef) | परीक्षण के लिए अन्य आयत। |

**Returns:**
boolean - यह विधि `true` लौटाती है यदि अन्य [RectangleF](../../com.aspose.drawing/rectanglef) संरचना और उसके X, Y, Width, और Height गुण इस [RectangleF](../../com.aspose.drawing/rectanglef) संरचना के संबंधित गुणों के बराबर हैं; अन्यथा `false`।
### CloneTo(RectangleF that) {#CloneTo-com.aspose.drawing.RectangleF-}
```
public void CloneTo(RectangleF that)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| that | [RectangleF](../../com.aspose.drawing/rectanglef) |  |

### Clone() {#Clone--}
```
public RectangleF Clone()
```




**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef)
### clone() {#clone--}
```
public Object clone()
```




**Returns:**
java.lang.Object
