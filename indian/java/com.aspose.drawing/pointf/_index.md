---
title: PointF
second_title: Aspose.Drawing for Java API संदर्भ
description: एक क्रमबद्ध जोड़ी फ्लोटिंग-पॉइंट x और y निर्देशांक को दर्शाता है जो दो-आयामी तल में एक बिंदु को परिभाषित करता है।
type: docs
weight: 37
url: /hi/java/com.aspose.drawing/pointf/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable, java.lang.Cloneable
```
public class PointF extends Struct<PointF> implements System.IEquatable<PointF>, Cloneable
```

एक क्रमबद्ध जोड़ी फ्लोटिंग-पॉइंट x और y निर्देशांक को दर्शाता है जो दो-आयामी तल में एक बिंदु को परिभाषित करता है।
## निर्माता

| निर्माता | विवरण |
| --- | --- |
| [PointF()](#PointF--) |  |
| [PointF(float x, float y)](#PointF-float-float-) | निर्दिष्ट निर्देशांक के साथ PointF संरचना का एक नया उदाहरण प्रारंभ करता है। |
## मेथड्स

| विधि | विवरण |
| --- | --- |
| [op_Addition(PointF pt, Size sz)](#op-Addition-com.aspose.drawing.PointF-com.aspose.drawing.Size-) |  |
| [op_Subtraction(PointF pt, Size sz)](#op-Subtraction-com.aspose.drawing.PointF-com.aspose.drawing.Size-) |  |
| [op_Addition(PointF pt, SizeF sz)](#op-Addition-com.aspose.drawing.PointF-com.aspose.drawing.SizeF-) |  |
| [op_Subtraction(PointF pt, SizeF sz)](#op-Subtraction-com.aspose.drawing.PointF-com.aspose.drawing.SizeF-) |  |
| [op_Equality(PointF left, PointF right)](#op-Equality-com.aspose.drawing.PointF-com.aspose.drawing.PointF-) | दो [PointF](../../com.aspose.drawing/pointf) संरचनाओं की तुलना करता है। |
| [op_Inequality(PointF left, PointF right)](#op-Inequality-com.aspose.drawing.PointF-com.aspose.drawing.PointF-) | निर्धारित करता है कि निर्दिष्ट बिंदुओं के निर्देशांक असमान हैं या नहीं। |
| [add(PointF orig, Size size)](#add-com.aspose.drawing.PointF-com.aspose.drawing.Size-) | एक निर्दिष्ट [SizeF](../../com.aspose.drawing/sizef) द्वारा दिए गए [PointF](../../com.aspose.drawing/pointf) को ट्रांसलेट करता है। |
| [subtract(PointF pt, Size sz)](#subtract-com.aspose.drawing.PointF-com.aspose.drawing.Size-) |  |
| [add(PointF orig, SizeF sizeF)](#add-com.aspose.drawing.PointF-com.aspose.drawing.SizeF-) | एक निर्दिष्ट [SizeF](../../com.aspose.drawing/sizef) द्वारा दिए गए [PointF](../../com.aspose.drawing/pointf) को ट्रांसलेट करता है। |
| [subtract(PointF pt, SizeF sz)](#subtract-com.aspose.drawing.PointF-com.aspose.drawing.SizeF-) |  |
| [isEquals(PointF obj1, PointF obj2)](#isEquals-com.aspose.drawing.PointF-com.aspose.drawing.PointF-) |  |
| [getEmpty()](#getEmpty--) |  |
| [isEmpty()](#isEmpty--) | एक मान प्राप्त करता है जो दर्शाता है कि यह [PointF](../../com.aspose.drawing/pointf) खाली है या नहीं। |
| [getX()](#getX--) | इस PointF का x-निर्देशांक प्राप्त करता है। |
| [setX(float value)](#setX-float-) | इस PointF का x-निर्देशांक सेट करता है। |
| [getY()](#getY--) | इस PointF का y-निर्देशांक प्राप्त करता है। |
| [setY(float value)](#setY-float-) | इस PointF का y-निर्देशांक सेट करता है। |
| [equals(Object obj)](#equals-java.lang.Object-) | निर्दिष्ट करता है कि यह [PointF](../../com.aspose.drawing/pointf) निर्दिष्ट ऑब्जेक्ट के समान निर्देशांक रखता है या नहीं। |
| [hashCode()](#hashCode--) | इस इंस्टेंस के लिए एक हैश कोड लौटाता है। |
| [toString()](#toString--) |  |
| [equals(PointF other)](#equals-com.aspose.drawing.PointF-) | परीक्षण करता है कि अन्य [PointF](../../com.aspose.drawing/pointf) संरचना का स्थान इस [PointF](../../com.aspose.drawing/pointf) संरचना के समान है या नहीं। |
| [CloneTo(PointF that)](#CloneTo-com.aspose.drawing.PointF-) |  |
| [Clone()](#Clone--) |  |
| [clone()](#clone--) |  |
### PointF() {#PointF--}
```
public PointF()
```


### PointF(float x, float y) {#PointF-float-float-}
```
public PointF(float x, float y)
```


निर्दिष्ट निर्देशांक के साथ PointF संरचना का एक नया उदाहरण प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | फ़्लोट | बिंदु की क्षैतिज स्थिति। |
| y | फ़्लोट | बिंदु की लंबवत स्थिति। |

### op_Addition(PointF pt, Size sz) {#op-Addition-com.aspose.drawing.PointF-com.aspose.drawing.Size-}
```
public static PointF op_Addition(PointF pt, Size sz)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pt | [PointF](../../com.aspose.drawing/pointf) |  |
| sz | [Size](../../com.aspose.drawing/size) |  |

**Returns:**
[PointF](../../com.aspose.drawing/pointf)
### op_Subtraction(PointF pt, Size sz) {#op-Subtraction-com.aspose.drawing.PointF-com.aspose.drawing.Size-}
```
public static PointF op_Subtraction(PointF pt, Size sz)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pt | [PointF](../../com.aspose.drawing/pointf) |  |
| sz | [Size](../../com.aspose.drawing/size) |  |

**Returns:**
[PointF](../../com.aspose.drawing/pointf)
### op_Addition(PointF pt, SizeF sz) {#op-Addition-com.aspose.drawing.PointF-com.aspose.drawing.SizeF-}
```
public static PointF op_Addition(PointF pt, SizeF sz)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pt | [PointF](../../com.aspose.drawing/pointf) |  |
| sz | [SizeF](../../com.aspose.drawing/sizef) |  |

**Returns:**
[PointF](../../com.aspose.drawing/pointf)
### op_Subtraction(PointF pt, SizeF sz) {#op-Subtraction-com.aspose.drawing.PointF-com.aspose.drawing.SizeF-}
```
public static PointF op_Subtraction(PointF pt, SizeF sz)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pt | [PointF](../../com.aspose.drawing/pointf) |  |
| sz | [SizeF](../../com.aspose.drawing/sizef) |  |

**Returns:**
[PointF](../../com.aspose.drawing/pointf)
### op_Equality(PointF left, PointF right) {#op-Equality-com.aspose.drawing.PointF-com.aspose.drawing.PointF-}
```
public static boolean op_Equality(PointF left, PointF right)
```


दो [PointF](../../com.aspose.drawing/pointf) संरचनाओं की तुलना करता है। परिणाम निर्दिष्ट करता है कि दो [PointF](../../com.aspose.drawing/pointf) संरचनाओं के `PointF.X` और `PointF.Y` गुणों के मान समान हैं या नहीं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| left | [PointF](../../com.aspose.drawing/pointf) | तुलना करने के लिए पहला [PointF](../../com.aspose.drawing/pointf)। |
| right | [PointF](../../com.aspose.drawing/pointf) | तुलना करने के लिए दूसरा [PointF](../../com.aspose.drawing/pointf)। |

**Returns:**
boolean - true यदि बाएँ और दाएँ [PointF](../../com.aspose.drawing/pointf) संरचनाओं के `PointF.X` और `PointF.Y` मान समान हैं; अन्यथा, false.
### op_Inequality(PointF left, PointF right) {#op-Inequality-com.aspose.drawing.PointF-com.aspose.drawing.PointF-}
```
public static boolean op_Inequality(PointF left, PointF right)
```


निर्धारित करता है कि निर्दिष्ट बिंदुओं के निर्देशांक असमान हैं या नहीं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| left | [PointF](../../com.aspose.drawing/pointf) | तुलना करने के लिए पहला [PointF](../../com.aspose.drawing/pointf)। |
| right | [PointF](../../com.aspose.drawing/pointf) | तुलना करने के लिए दूसरा [PointF](../../com.aspose.drawing/pointf)। |

**Returns:**
boolean - true यह संकेत करने के लिए कि `left` और `right` के `PointF.X` और `PointF.Y` मान असमान हैं; अन्यथा, false.
### add(PointF orig, Size size) {#add-com.aspose.drawing.PointF-com.aspose.drawing.Size-}
```
public static PointF add(PointF orig, Size size)
```


एक निर्दिष्ट [SizeF](../../com.aspose.drawing/sizef) द्वारा दिए गए [PointF](../../com.aspose.drawing/pointf) को ट्रांसलेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| orig | [PointF](../../com.aspose.drawing/pointf) | ट्रांसलेट करने के लिए [PointF](../../com.aspose.drawing/pointf)। |
| size | [Size](../../com.aspose.drawing/size) | [Size](../../com.aspose.drawing/size) जो `orig` के निर्देशांक में जोड़ने के लिए संख्याएँ निर्दिष्ट करता है। |

**Returns:**
[PointF](../../com.aspose.drawing/pointf) - The translated [PointF](../../com.aspose.drawing/pointf).
### subtract(PointF pt, Size sz) {#subtract-com.aspose.drawing.PointF-com.aspose.drawing.Size-}
```
public static PointF subtract(PointF pt, Size sz)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pt | [PointF](../../com.aspose.drawing/pointf) |  |
| sz | [Size](../../com.aspose.drawing/size) |  |

**Returns:**
[PointF](../../com.aspose.drawing/pointf)
### add(PointF orig, SizeF sizeF) {#add-com.aspose.drawing.PointF-com.aspose.drawing.SizeF-}
```
public static PointF add(PointF orig, SizeF sizeF)
```


एक निर्दिष्ट [SizeF](../../com.aspose.drawing/sizef) द्वारा दिए गए [PointF](../../com.aspose.drawing/pointf) को ट्रांसलेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| orig | [PointF](../../com.aspose.drawing/pointf) | ट्रांसलेट करने के लिए [PointF](../../com.aspose.drawing/pointf)। |
| sizeF | [SizeF](../../com.aspose.drawing/sizef) | [SizeF](../../com.aspose.drawing/sizef) जो `orig` के निर्देशांक में जोड़ने के लिए संख्याएँ निर्दिष्ट करता है। |

**Returns:**
[PointF](../../com.aspose.drawing/pointf) - The translated [PointF](../../com.aspose.drawing/pointf).
### subtract(PointF pt, SizeF sz) {#subtract-com.aspose.drawing.PointF-com.aspose.drawing.SizeF-}
```
public static PointF subtract(PointF pt, SizeF sz)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pt | [PointF](../../com.aspose.drawing/pointf) |  |
| sz | [SizeF](../../com.aspose.drawing/sizef) |  |

**Returns:**
[PointF](../../com.aspose.drawing/pointf)
### isEquals(PointF obj1, PointF obj2) {#isEquals-com.aspose.drawing.PointF-com.aspose.drawing.PointF-}
```
public static boolean isEquals(PointF obj1, PointF obj2)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj1 | [PointF](../../com.aspose.drawing/pointf) |  |
| obj2 | [PointF](../../com.aspose.drawing/pointf) |  |

**Returns:**
boolean
### getEmpty() {#getEmpty--}
```
public static PointF getEmpty()
```




**Returns:**
[PointF](../../com.aspose.drawing/pointf)
### isEmpty() {#isEmpty--}
```
public final boolean isEmpty()
```


एक मान प्राप्त करता है जो दर्शाता है कि यह [PointF](../../com.aspose.drawing/pointf) खाली है या नहीं।

**Returns:**
boolean - यह मान दर्शाता है कि यह [PointF](../../com.aspose.drawing/pointf) खाली है।
### getX() {#getX--}
```
public final float getX()
```


इस PointF का x-निर्देशांक प्राप्त करता है।

**Returns:**
float - इस PointF का x-निर्देशांक।
### setX(float value) {#setX-float-}
```
public final void setX(float value)
```


इस PointF का x-निर्देशांक सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | फ़्लोट | इस PointF का x-निर्देशांक। |

### getY() {#getY--}
```
public final float getY()
```


इस PointF का y-निर्देशांक प्राप्त करता है।

**Returns:**
float - इस PointF का y-निर्देशांक।
### setY(float value) {#setY-float-}
```
public final void setY(float value)
```


इस PointF का y-निर्देशांक सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | फ़्लोट | इस PointF का y-निर्देशांक। |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


निर्दिष्ट करता है कि यह [PointF](../../com.aspose.drawing/pointf) निर्दिष्ट ऑब्जेक्ट के समान निर्देशांक रखता है या नहीं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | java.lang.Object | परीक्षण करने के लिए ऑब्जेक्ट। |

**Returns:**
boolean - यह विधि true लौटाती है यदि `obj` एक [PointF](../../com.aspose.drawing/pointf) है और इस [Point](../../com.aspose.drawing/point) के समान निर्देशांक रखता है।
### hashCode() {#hashCode--}
```
public int hashCode()
```


इस इंस्टेंस के लिए एक हैश कोड लौटाता है।

**Returns:**
int - इस उदाहरण के लिए एक हैश कोड, जो हैशिंग एल्गोरिदम और हैश टेबल जैसी डेटा संरचनाओं में उपयोग के लिए उपयुक्त है।
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### equals(PointF other) {#equals-com.aspose.drawing.PointF-}
```
public final boolean equals(PointF other)
```


परीक्षण करता है कि अन्य [PointF](../../com.aspose.drawing/pointf) संरचना का स्थान इस [PointF](../../com.aspose.drawing/pointf) संरचना के समान है या नहीं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| other | [PointF](../../com.aspose.drawing/pointf) | परीक्षण के लिए अन्य बिंदु |

**Returns:**
boolean - यह विधि `true` लौटाती है यदि अन्य [PointF](../../com.aspose.drawing/pointf) संरचना और उसकी X तथा Y गुण इस [PointF](../../com.aspose.drawing/pointf) संरचना के संबंधित गुणों के बराबर हैं; अन्यथा, `false`।
### CloneTo(PointF that) {#CloneTo-com.aspose.drawing.PointF-}
```
public void CloneTo(PointF that)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| that | [PointF](../../com.aspose.drawing/pointf) |  |

### Clone() {#Clone--}
```
public PointF Clone()
```




**Returns:**
[PointF](../../com.aspose.drawing/pointf)
### clone() {#clone--}
```
public Object clone()
```




**Returns:**
java.lang.Object
