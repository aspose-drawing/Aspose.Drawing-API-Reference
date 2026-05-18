---
title: SizeF
second_title: Aspose.Drawing for Java API संदर्भ
description: आयत की चौड़ाई और ऊँचाई के रूप में आमतौर पर उपयोग किए जाने वाले फ्लोटिंग-पॉइंट संख्याओं की क्रमबद्ध जोड़ी को संग्रहीत करता है।
type: docs
weight: 43
url: /hi/java/com.aspose.drawing/sizef/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable, java.lang.Cloneable
```
public class SizeF extends Struct<SizeF> implements System.IEquatable<SizeF>, Cloneable
```

एक क्रमबद्ध फ्लोटिंग-पॉइंट संख्याओं की जोड़ी संग्रहीत करता है, आमतौर पर आयत की चौड़ाई और ऊँचाई।
## निर्माता

| निर्माता | विवरण |
| --- | --- |
| [SizeF()](#SizeF--) |  |
| [SizeF(float width, float height)](#SizeF-float-float-) | निर्दिष्ट आयामों से SizeF स्ट्रक्चर का नया इंस्टेंस प्रारंभ करता है। |
| [SizeF(PointF pt)](#SizeF-com.aspose.drawing.PointF-) | नए [SizeF](../../com.aspose.drawing/sizef) स्ट्रक्चर का इंस्टेंस प्रारंभ करता है। |
| [SizeF(SizeF size)](#SizeF-com.aspose.drawing.SizeF-) | नए [SizeF](../../com.aspose.drawing/sizef) स्ट्रक्चर का इंस्टेंस प्रारंभ करता है। |
## मेथड्स

| विधि | विवरण |
| --- | --- |
| [op_Equality(SizeF sz1, SizeF sz2)](#op-Equality-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-) | जाँचता है कि दो [SizeF](../../com.aspose.drawing/sizef) स्ट्रक्चर समान हैं या नहीं। |
| [op_Inequality(SizeF sz1, SizeF sz2)](#op-Inequality-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-) | जाँचता है कि दो [SizeF](../../com.aspose.drawing/sizef) स्ट्रक्चर अलग हैं या नहीं। |
| [add(SizeF sz1, SizeF sz2)](#add-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-) | एक [SizeF](../../com.aspose.drawing/sizef) स्ट्रक्चर की चौड़ाई और ऊँचाई को दूसरे [SizeF](../../com.aspose.drawing/sizef) स्ट्रक्चर की चौड़ाई और ऊँचाई में जोड़ता है। |
| [subtract(SizeF sz1, SizeF sz2)](#subtract-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-) | एक [SizeF](../../com.aspose.drawing/sizef) स्ट्रक्चर की चौड़ाई और ऊँचाई को दूसरे [SizeF](../../com.aspose.drawing/sizef) स्ट्रक्चर की चौड़ाई और ऊँचाई से घटाता है। |
| [op_Addition(SizeF sz1, SizeF sz2)](#op-Addition-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-) | एक [SizeF](../../com.aspose.drawing/sizef) स्ट्रक्चर की चौड़ाई और ऊँचाई को दूसरे [SizeF](../../com.aspose.drawing/sizef) स्ट्रक्चर की चौड़ाई और ऊँचाई में जोड़ता है। |
| [op_Subtraction(SizeF sz1, SizeF sz2)](#op-Subtraction-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-) | एक [SizeF](../../com.aspose.drawing/sizef) स्ट्रक्चर की चौड़ाई और ऊँचाई को दूसरे [SizeF](../../com.aspose.drawing/sizef) स्ट्रक्चर की चौड़ाई और ऊँचाई से घटाता है। |
| [op_Multiply(float left, SizeF right)](#op-Multiply-float-com.aspose.drawing.SizeF-) | एक `float` द्वारा [SizeF](../../com.aspose.drawing/sizef) को गुणा करके [SizeF](../../com.aspose.drawing/sizef) उत्पन्न करता है। |
| [op_Multiply(SizeF left, float right)](#op-Multiply-com.aspose.drawing.SizeF-float-) | एक `float` द्वारा [SizeF](../../com.aspose.drawing/sizef) को गुणा करके [SizeF](../../com.aspose.drawing/sizef) उत्पन्न करता है। |
| [op_Division(SizeF left, float right)](#op-Division-com.aspose.drawing.SizeF-float-) | एक `float` द्वारा [SizeF](../../com.aspose.drawing/sizef) को विभाजित करके [SizeF](../../com.aspose.drawing/sizef) उत्पन्न करता है। |
| [to_PointF(SizeF size)](#to-PointF-com.aspose.drawing.SizeF-) |  |
| [isEquals(SizeF obj1, SizeF obj2)](#isEquals-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-) |  |
| [getEmpty()](#getEmpty--) |  |
| [isEmpty()](#isEmpty--) | एक मान प्राप्त करता है जो दर्शाता है कि यह [SizeF](../../com.aspose.drawing/sizef) संरचना की चौड़ाई और ऊँचाई शून्य है या नहीं। |
| [getWidth()](#getWidth--) | इस SizeF संरचना का क्षैतिज घटक प्राप्त करता है। |
| [setWidth(float value)](#setWidth-float-) | इस SizeF संरचना का क्षैतिज घटक सेट करता है। |
| [getHeight()](#getHeight--) | इस SizeF संरचना का लंबवत घटक प्राप्त करता है। |
| [setHeight(float value)](#setHeight-float-) | इस SizeF संरचना का लंबवत घटक सेट करता है। |
| [hashCode()](#hashCode--) | इस [SizeF](../../com.aspose.drawing/sizef) संरचना के लिए एक हैश कोड लौटाता है। |
| [toString()](#toString--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | परीक्षण करता है कि निर्दिष्ट ऑब्जेक्ट इस [SizeF](../../com.aspose.drawing/sizef) संरचना के समान आयामों वाला [SizeF](../../com.aspose.drawing/sizef) संरचना है या नहीं। |
| [toSize()](#toSize--) | [SizeF](../../com.aspose.drawing/sizef) संरचना को [Size](../../com.aspose.drawing/size) संरचना में परिवर्तित करता है। |
| [toPointF()](#toPointF--) | [SizeF](../../com.aspose.drawing/sizef) संरचना को [PointF](../../com.aspose.drawing/pointf) संरचना में परिवर्तित करता है। |
| [equals(SizeF other)](#equals-com.aspose.drawing.SizeF-) | परीक्षण करता है कि अन्य [SizeF](../../com.aspose.drawing/sizef) संरचना का आकार इस [SizeF](../../com.aspose.drawing/sizef) संरचना के समान है या नहीं। |
| [CloneTo(SizeF that)](#CloneTo-com.aspose.drawing.SizeF-) |  |
| [Clone()](#Clone--) |  |
| [clone()](#clone--) |  |
### SizeF() {#SizeF--}
```
public SizeF()
```


### SizeF(float width, float height) {#SizeF-float-float-}
```
public SizeF(float width, float height)
```


निर्दिष्ट आयामों से SizeF स्ट्रक्चर का नया इंस्टेंस प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| चौड़ाई | फ़्लोट | नए SizeF संरचना का चौड़ाई घटक। |
| ऊँचाई | फ़्लोट | नए SizeF संरचना का ऊँचाई घटक। |

### SizeF(PointF pt) {#SizeF-com.aspose.drawing.PointF-}
```
public SizeF(PointF pt)
```


नए [SizeF](../../com.aspose.drawing/sizef) स्ट्रक्चर का इंस्टेंस प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pt | [PointF](../../com.aspose.drawing/pointf) | यह [SizeF](../../com.aspose.drawing/sizef) संरचना को आरंभ करने के लिए उपयोग की जाने वाली [PointF](../../com.aspose.drawing/pointf) संरचना। |

### SizeF(SizeF size) {#SizeF-com.aspose.drawing.SizeF-}
```
public SizeF(SizeF size)
```


नए [SizeF](../../com.aspose.drawing/sizef) स्ट्रक्चर का इंस्टेंस प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.drawing/sizef) | नए [SizeF](../../com.aspose.drawing/sizef) संरचना को बनाने के लिए उपयोग की जाने वाली [SizeF](../../com.aspose.drawing/sizef) संरचना। |

### op_Equality(SizeF sz1, SizeF sz2) {#op-Equality-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-}
```
public static boolean op_Equality(SizeF sz1, SizeF sz2)
```


जाँचता है कि दो [SizeF](../../com.aspose.drawing/sizef) स्ट्रक्चर समान हैं या नहीं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sz1 | [SizeF](../../com.aspose.drawing/sizef) | समानता ऑपरेटर के बाएँ पक्ष की [SizeF](../../com.aspose.drawing/sizef) संरचना। |
| sz2 | [SizeF](../../com.aspose.drawing/sizef) | समानता ऑपरेटर के दाएँ पक्ष की [SizeF](../../com.aspose.drawing/sizef) संरचना। |

**Returns:**
boolean - यह ऑपरेटर `sz1` और `sz2` की चौड़ाई और ऊँचाई समान होने पर true लौटाता है; अन्यथा false।
### op_Inequality(SizeF sz1, SizeF sz2) {#op-Inequality-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-}
```
public static boolean op_Inequality(SizeF sz1, SizeF sz2)
```


जाँचता है कि दो [SizeF](../../com.aspose.drawing/sizef) स्ट्रक्चर अलग हैं या नहीं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sz1 | [SizeF](../../com.aspose.drawing/sizef) | असमानता ऑपरेटर के बाएँ पक्ष की [SizeF](../../com.aspose.drawing/sizef) संरचना। |
| sz2 | [SizeF](../../com.aspose.drawing/sizef) | असमानता ऑपरेटर के दाएँ पक्ष की [SizeF](../../com.aspose.drawing/sizef) संरचना। |

**Returns:**
boolean - यह ऑपरेटर `sz1` और `sz2` में चौड़ाई या ऊँचाई में अंतर होने पर true लौटाता है; यदि `sz1` और `sz2` समान हैं तो false।
### add(SizeF sz1, SizeF sz2) {#add-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-}
```
public static SizeF add(SizeF sz1, SizeF sz2)
```


एक [SizeF](../../com.aspose.drawing/sizef) स्ट्रक्चर की चौड़ाई और ऊँचाई को दूसरे [SizeF](../../com.aspose.drawing/sizef) स्ट्रक्चर की चौड़ाई और ऊँचाई में जोड़ता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sz1 | [SizeF](../../com.aspose.drawing/sizef) | पहली जोड़ने वाली [SizeF](../../com.aspose.drawing/sizef) संरचना। |
| sz2 | [SizeF](../../com.aspose.drawing/sizef) | दूसरी जोड़ने वाली [SizeF](../../com.aspose.drawing/sizef) संरचना। |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - A [SizeF](../../com.aspose.drawing/sizef) structure that is the result of the addition operation.
### subtract(SizeF sz1, SizeF sz2) {#subtract-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-}
```
public static SizeF subtract(SizeF sz1, SizeF sz2)
```


एक [SizeF](../../com.aspose.drawing/sizef) स्ट्रक्चर की चौड़ाई और ऊँचाई को दूसरे [SizeF](../../com.aspose.drawing/sizef) स्ट्रक्चर की चौड़ाई और ऊँचाई से घटाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sz1 | [SizeF](../../com.aspose.drawing/sizef) | घटाव ऑपरेटर के बाएँ पक्ष की [SizeF](../../com.aspose.drawing/sizef) संरचना। |
| sz2 | [SizeF](../../com.aspose.drawing/sizef) | वियोजन ऑपरेटर के दाएँ पक्ष में स्थित [SizeF](../../com.aspose.drawing/sizef) संरचना। |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - A [SizeF](../../com.aspose.drawing/sizef) structure that is a result of the subtraction operation.
### op_Addition(SizeF sz1, SizeF sz2) {#op-Addition-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-}
```
public static SizeF op_Addition(SizeF sz1, SizeF sz2)
```


एक [SizeF](../../com.aspose.drawing/sizef) स्ट्रक्चर की चौड़ाई और ऊँचाई को दूसरे [SizeF](../../com.aspose.drawing/sizef) स्ट्रक्चर की चौड़ाई और ऊँचाई में जोड़ता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sz1 | [SizeF](../../com.aspose.drawing/sizef) | पहली जोड़ने वाली [SizeF](../../com.aspose.drawing/sizef) संरचना। |
| sz2 | [SizeF](../../com.aspose.drawing/sizef) | दूसरी जोड़ने वाली [SizeF](../../com.aspose.drawing/sizef) संरचना। |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - A [Size](../../com.aspose.drawing/size) structure that is the result of the addition operation.
### op_Subtraction(SizeF sz1, SizeF sz2) {#op-Subtraction-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-}
```
public static SizeF op_Subtraction(SizeF sz1, SizeF sz2)
```


एक [SizeF](../../com.aspose.drawing/sizef) स्ट्रक्चर की चौड़ाई और ऊँचाई को दूसरे [SizeF](../../com.aspose.drawing/sizef) स्ट्रक्चर की चौड़ाई और ऊँचाई से घटाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sz1 | [SizeF](../../com.aspose.drawing/sizef) | घटाव ऑपरेटर के बाएँ पक्ष की [SizeF](../../com.aspose.drawing/sizef) संरचना। |
| sz2 | [SizeF](../../com.aspose.drawing/sizef) | वियोजन ऑपरेटर के दाएँ पक्ष में स्थित [SizeF](../../com.aspose.drawing/sizef) संरचना। |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - A [SizeF](../../com.aspose.drawing/sizef) that is the result of the subtraction operation.
### op_Multiply(float left, SizeF right) {#op-Multiply-float-com.aspose.drawing.SizeF-}
```
public static SizeF op_Multiply(float left, SizeF right)
```


एक `float` द्वारा [SizeF](../../com.aspose.drawing/sizef) को गुणा करके [SizeF](../../com.aspose.drawing/sizef) उत्पन्न करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| बाएँ | फ़्लोट | मल्टिप्लायर का प्रकार `float` है। |
| right | [SizeF](../../com.aspose.drawing/sizef) | [SizeF](../../com.aspose.drawing/sizef) प्रकार का गुणक। |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - Product of type [SizeF](../../com.aspose.drawing/sizef).
### op_Multiply(SizeF left, float right) {#op-Multiply-com.aspose.drawing.SizeF-float-}
```
public static SizeF op_Multiply(SizeF left, float right)
```


एक `float` द्वारा [SizeF](../../com.aspose.drawing/sizef) को गुणा करके [SizeF](../../com.aspose.drawing/sizef) उत्पन्न करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| left | [SizeF](../../com.aspose.drawing/sizef) | [SizeF](../../com.aspose.drawing/sizef) प्रकार का गुणक। |
| दाएँ | फ़्लोट | मल्टिप्लायर का प्रकार `float` है। |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - Product of type [SizeF](../../com.aspose.drawing/sizef).
### op_Division(SizeF left, float right) {#op-Division-com.aspose.drawing.SizeF-float-}
```
public static SizeF op_Division(SizeF left, float right)
```


एक `float` द्वारा [SizeF](../../com.aspose.drawing/sizef) को विभाजित करके [SizeF](../../com.aspose.drawing/sizef) उत्पन्न करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| left | [SizeF](../../com.aspose.drawing/sizef) | [SizeF](../../com.aspose.drawing/sizef) प्रकार का भाजक। |
| दाएँ | फ़्लोट | डिवाइज़र का प्रकार `int` है। |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - Result of type [SizeF](../../com.aspose.drawing/sizef).
### to_PointF(SizeF size) {#to-PointF-com.aspose.drawing.SizeF-}
```
public static PointF to_PointF(SizeF size)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.drawing/sizef) |  |

**Returns:**
[PointF](../../com.aspose.drawing/pointf)
### isEquals(SizeF obj1, SizeF obj2) {#isEquals-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-}
```
public static boolean isEquals(SizeF obj1, SizeF obj2)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj1 | [SizeF](../../com.aspose.drawing/sizef) |  |
| obj2 | [SizeF](../../com.aspose.drawing/sizef) |  |

**Returns:**
boolean
### getEmpty() {#getEmpty--}
```
public static SizeF getEmpty()
```




**Returns:**
[SizeF](../../com.aspose.drawing/sizef)
### isEmpty() {#isEmpty--}
```
public final boolean isEmpty()
```


एक मान प्राप्त करता है जो दर्शाता है कि यह [SizeF](../../com.aspose.drawing/sizef) संरचना की चौड़ाई और ऊँचाई शून्य है या नहीं।

**Returns:**
boolean - एक मान जो दर्शाता है कि यह [SizeF](../../com.aspose.drawing/sizef) संरचना की चौड़ाई और ऊँचाई शून्य है या नहीं।
### getWidth() {#getWidth--}
```
public final float getWidth()
```


इस SizeF संरचना का क्षैतिज घटक प्राप्त करता है।

**Returns:**
float - इस SizeF संरचना का क्षैतिज घटक।
### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```


इस SizeF संरचना का क्षैतिज घटक सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | फ़्लोट | इस SizeF संरचना का क्षैतिज घटक। |

### getHeight() {#getHeight--}
```
public final float getHeight()
```


इस SizeF संरचना का लंबवत घटक प्राप्त करता है।

**Returns:**
float - इस SizeF संरचना का लंबवत घटक।
### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```


इस SizeF संरचना का लंबवत घटक सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | फ़्लोट | इस SizeF संरचना का लंबवत घटक। |

### hashCode() {#hashCode--}
```
public int hashCode()
```


इस [SizeF](../../com.aspose.drawing/sizef) संरचना के लिए एक हैश कोड लौटाता है।

**Returns:**
int - एक पूर्णांक मान जो इस [SizeF](../../com.aspose.drawing/sizef) संरचना के लिए हैश मान निर्दिष्ट करता है।
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


परीक्षण करता है कि निर्दिष्ट ऑब्जेक्ट इस [SizeF](../../com.aspose.drawing/sizef) संरचना के समान आयामों वाला [SizeF](../../com.aspose.drawing/sizef) संरचना है या नहीं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | java.lang.Object | परीक्षण करने के लिए ऑब्जेक्ट। |

**Returns:**
boolean - यह विधि `true` लौटाती है यदि obj एक [SizeF](../../com.aspose.drawing/sizef) है और इसकी चौड़ाई तथा ऊँचाई इस SizeF के समान है; अन्यथा, `false`।
### toSize() {#toSize--}
```
public final Size toSize()
```


[SizeF](../../com.aspose.drawing/sizef) संरचना को [Size](../../com.aspose.drawing/size) संरचना में परिवर्तित करता है।

**Returns:**
[Size](../../com.aspose.drawing/size) - Returns a [Size](../../com.aspose.drawing/size) structure.
### toPointF() {#toPointF--}
```
public final PointF toPointF()
```


[SizeF](../../com.aspose.drawing/sizef) संरचना को [PointF](../../com.aspose.drawing/pointf) संरचना में परिवर्तित करता है।

**Returns:**
[PointF](../../com.aspose.drawing/pointf) - Returns a [PointF](../../com.aspose.drawing/pointf) structure.
### equals(SizeF other) {#equals-com.aspose.drawing.SizeF-}
```
public final boolean equals(SizeF other)
```


परीक्षण करता है कि अन्य [SizeF](../../com.aspose.drawing/sizef) संरचना का आकार इस [SizeF](../../com.aspose.drawing/sizef) संरचना के समान है या नहीं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| other | [SizeF](../../com.aspose.drawing/sizef) | परीक्षण के लिए अन्य आकार |

**Returns:**
boolean - यह विधि `true` लौटाती है यदि अन्य [SizeF](../../com.aspose.drawing/sizef) संरचना और उसकी Width तथा Height गुण इस [SizeF](../../com.aspose.drawing/sizef) संरचना के संबंधित गुणों के बराबर हैं; अन्यथा, `false`।
### CloneTo(SizeF that) {#CloneTo-com.aspose.drawing.SizeF-}
```
public void CloneTo(SizeF that)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| that | [SizeF](../../com.aspose.drawing/sizef) |  |

### Clone() {#Clone--}
```
public SizeF Clone()
```




**Returns:**
[SizeF](../../com.aspose.drawing/sizef)
### clone() {#clone--}
```
public Object clone()
```




**Returns:**
java.lang.Object
