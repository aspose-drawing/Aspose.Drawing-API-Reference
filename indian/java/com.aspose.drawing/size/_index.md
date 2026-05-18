---
title: Size
second_title: Aspose.Drawing for Java API संदर्भ
description: आमतौर पर एक आयत की चौड़ाई और ऊँचाई को दर्शाने वाले पूर्णांकों की क्रमबद्ध जोड़ी को संग्रहीत करता है।
type: docs
weight: 42
url: /hi/java/com.aspose.drawing/size/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable, java.lang.Cloneable
```
public class Size extends Struct<Size> implements System.IEquatable<Size>, Cloneable
```

एक क्रमबद्ध पूर्णांक जोड़ी संग्रहीत करता है, आमतौर पर आयत की चौड़ाई और ऊँचाई।
## निर्माता

| निर्माता | विवरण |
| --- | --- |
| [Size()](#Size--) |  |
| [Size(Point pt)](#Size-com.aspose.drawing.Point-) | निर्दिष्ट [Point](../../com.aspose.drawing/point) से नई [Size](../../com.aspose.drawing/size) स्ट्रक्ट की एक नई इंस्टेंस को प्रारंभ करता है। |
| [Size(int width, int height)](#Size-int-int-) | निर्दिष्ट आयामों से नई [Size](../../com.aspose.drawing/size) स्ट्रक्ट की एक नई इंस्टेंस को प्रारंभ करता है। |
## मेथड्स

| विधि | विवरण |
| --- | --- |
| [to_SizeF(Size p)](#to-SizeF-com.aspose.drawing.Size-) | निर्दिष्ट [Size](../../com.aspose.drawing/size) को [SizeF](../../com.aspose.drawing/sizef) में परिवर्तित करता है। |
| [op_Addition(Size sz1, Size sz2)](#op-Addition-com.aspose.drawing.Size-com.aspose.drawing.Size-) | एक [Size](../../com.aspose.drawing/size) संरचना की चौड़ाई और ऊँचाई को दूसरी [Size](../../com.aspose.drawing/size) संरचना की चौड़ाई और ऊँचाई में जोड़ता है। |
| [op_Subtraction(Size sz1, Size sz2)](#op-Subtraction-com.aspose.drawing.Size-com.aspose.drawing.Size-) | एक [Size](../../com.aspose.drawing/size) संरचना की चौड़ाई और ऊँचाई को दूसरी [Size](../../com.aspose.drawing/size) संरचना की चौड़ाई और ऊँचाई से घटाता है। |
| [op_Multiply(int left, Size right)](#op-Multiply-int-com.aspose.drawing.Size-) | एक [Size](../../com.aspose.drawing/size) को `int` से गुणा करता है और [Size](../../com.aspose.drawing/size) उत्पन्न करता है। |
| [op_Multiply(Size left, int right)](#op-Multiply-com.aspose.drawing.Size-int-) | [Size](../../com.aspose.drawing/size) को `int` से गुणा करता है और [Size](../../com.aspose.drawing/size) उत्पन्न करता है। |
| [op_Division(Size left, int right)](#op-Division-com.aspose.drawing.Size-int-) | [Size](../../com.aspose.drawing/size) को `int` से विभाजित करता है और [Size](../../com.aspose.drawing/size) उत्पन्न करता है। |
| [op_Multiply(float left, Size right)](#op-Multiply-float-com.aspose.drawing.Size-) | [Size](../../com.aspose.drawing/size) को `float` से गुणा करता है और [SizeF](../../com.aspose.drawing/sizef) उत्पन्न करता है। |
| [op_Multiply(Size left, float right)](#op-Multiply-com.aspose.drawing.Size-float-) | [Size](../../com.aspose.drawing/size) को `float` से गुणा करता है और [SizeF](../../com.aspose.drawing/sizef) उत्पन्न करता है। |
| [op_Division(Size left, float right)](#op-Division-com.aspose.drawing.Size-float-) | एक `float` द्वारा [Size](../../com.aspose.drawing/size) को विभाजित करता है और [SizeF](../../com.aspose.drawing/sizef) उत्पन्न करता है। |
| [op_Equality(Size sz1, Size sz2)](#op-Equality-com.aspose.drawing.Size-com.aspose.drawing.Size-) | जाँचता है कि दो [Size](../../com.aspose.drawing/size) संरचनाएँ समान हैं या नहीं। |
| [op_Inequality(Size sz1, Size sz2)](#op-Inequality-com.aspose.drawing.Size-com.aspose.drawing.Size-) | जाँचता है कि दो [Size](../../com.aspose.drawing/size) संरचनाएँ अलग हैं या नहीं। |
| [to_Point(Size size)](#to-Point-com.aspose.drawing.Size-) | निर्दिष्ट [Size](../../com.aspose.drawing/size) को एक [Point](../../com.aspose.drawing/point) में परिवर्तित करता है। |
| [add(Size sz1, Size sz2)](#add-com.aspose.drawing.Size-com.aspose.drawing.Size-) | एक [Size](../../com.aspose.drawing/size) संरचना की चौड़ाई और ऊँचाई को दूसरी [Size](../../com.aspose.drawing/size) संरचना की चौड़ाई और ऊँचाई में जोड़ता है। |
| [ceiling(SizeF value)](#ceiling-com.aspose.drawing.SizeF-) | निर्दिष्ट [SizeF](../../com.aspose.drawing/sizef) संरचना को [Size](../../com.aspose.drawing/size) संरचना में परिवर्तित करता है, [Size](../../com.aspose.drawing/size) संरचना के मानों को अगले बड़े पूर्णांक मान तक गोल करके। |
| [subtract(Size sz1, Size sz2)](#subtract-com.aspose.drawing.Size-com.aspose.drawing.Size-) | एक [Size](../../com.aspose.drawing/size) संरचना की चौड़ाई और ऊँचाई को दूसरी [Size](../../com.aspose.drawing/size) संरचना की चौड़ाई और ऊँचाई से घटाता है। |
| [truncate(SizeF value)](#truncate-com.aspose.drawing.SizeF-) | निर्दिष्ट [SizeF](../../com.aspose.drawing/sizef) संरचना को [Size](../../com.aspose.drawing/size) संरचना में परिवर्तित करता है, [SizeF](../../com.aspose.drawing/sizef) संरचना के मानों को अगले छोटे पूर्णांक मान तक काटकर। |
| [round(SizeF value)](#round-com.aspose.drawing.SizeF-) | निर्दिष्ट [SizeF](../../com.aspose.drawing/sizef) संरचना को [Size](../../com.aspose.drawing/size) संरचना में परिवर्तित करता है, [SizeF](../../com.aspose.drawing/sizef) संरचना के मानों को निकटतम पूर्णांक मान तक गोल करके। |
| [isEquals(Size obj1, Size obj2)](#isEquals-com.aspose.drawing.Size-com.aspose.drawing.Size-) |  |
| [getEmpty()](#getEmpty--) |  |
| [isEmpty()](#isEmpty--) | एक मान प्राप्त करता है जो दर्शाता है कि यह [Size](../../com.aspose.drawing/size) की चौड़ाई और ऊँचाई 0 है या नहीं। |
| [getWidth()](#getWidth--) | इस [Size](../../com.aspose.drawing/size) का क्षैतिज घटक प्राप्त करता है। |
| [setWidth(int value)](#setWidth-int-) | इस [Size](../../com.aspose.drawing/size) का क्षैतिज घटक सेट करता है। |
| [getHeight()](#getHeight--) | इस [Size](../../com.aspose.drawing/size) का लंबवत घटक प्राप्त करता है। |
| [setHeight(int value)](#setHeight-int-) | इस [Size](../../com.aspose.drawing/size) का लंबवत घटक सेट करता है। |
| [equals(Object obj)](#equals-java.lang.Object-) | जाँचता है कि क्या निर्दिष्ट वस्तु एक [Size](../../com.aspose.drawing/size) है जिसका आयाम इस [Size](../../com.aspose.drawing/size) के समान है। |
| [hashCode()](#hashCode--) | इस [Size](../../com.aspose.drawing/size) संरचना के लिए एक हैश कोड लौटाता है। |
| [toString()](#toString--) |  |
| [equals(Size other)](#equals-com.aspose.drawing.Size-) | जाँचता है कि क्या अन्य [Size](../../com.aspose.drawing/size) संरचना का आकार इस [Size](../../com.aspose.drawing/size) संरचना के समान है। |
| [CloneTo(Size that)](#CloneTo-com.aspose.drawing.Size-) |  |
| [Clone()](#Clone--) |  |
| [clone()](#clone--) |  |
### Size() {#Size--}
```
public Size()
```


### Size(Point pt) {#Size-com.aspose.drawing.Point-}
```
public Size(Point pt)
```


निर्दिष्ट [Point](../../com.aspose.drawing/point) से नई [Size](../../com.aspose.drawing/size) स्ट्रक्ट की एक नई इंस्टेंस को प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pt | [Point](../../com.aspose.drawing/point) | वह [Point](../../com.aspose.drawing/point) जिससे इस [Size](../../com.aspose.drawing/size) को आरंभ किया जाता है। |

### Size(int width, int height) {#Size-int-int-}
```
public Size(int width, int height)
```


निर्दिष्ट आयामों से नई [Size](../../com.aspose.drawing/size) स्ट्रक्ट की एक नई इंस्टेंस को प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| width | int | नए [Size](../../com.aspose.drawing/size) का चौड़ाई घटक। |
| height | int | नए [Size](../../com.aspose.drawing/size) का ऊँचाई घटक। |

### to_SizeF(Size p) {#to-SizeF-com.aspose.drawing.Size-}
```
public static SizeF to_SizeF(Size p)
```


निर्दिष्ट [Size](../../com.aspose.drawing/size) को [SizeF](../../com.aspose.drawing/sizef) में परिवर्तित करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| p | [Size](../../com.aspose.drawing/size) | परिवर्तित करने के लिए [Size](../../com.aspose.drawing/size)। |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - The [SizeF](../../com.aspose.drawing/sizef) structure to which this operator converts.
### op_Addition(Size sz1, Size sz2) {#op-Addition-com.aspose.drawing.Size-com.aspose.drawing.Size-}
```
public static Size op_Addition(Size sz1, Size sz2)
```


एक [Size](../../com.aspose.drawing/size) संरचना की चौड़ाई और ऊँचाई को दूसरी [Size](../../com.aspose.drawing/size) संरचना की चौड़ाई और ऊँचाई में जोड़ता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sz1 | [Size](../../com.aspose.drawing/size) | पहला जोड़ने वाला [Size](../../com.aspose.drawing/size)। |
| sz2 | [Size](../../com.aspose.drawing/size) | दूसरा जोड़ने वाला [Size](../../com.aspose.drawing/size)। |

**Returns:**
[Size](../../com.aspose.drawing/size) - A [Size](../../com.aspose.drawing/size) structure that is the result of the addition operation.
### op_Subtraction(Size sz1, Size sz2) {#op-Subtraction-com.aspose.drawing.Size-com.aspose.drawing.Size-}
```
public static Size op_Subtraction(Size sz1, Size sz2)
```


एक [Size](../../com.aspose.drawing/size) संरचना की चौड़ाई और ऊँचाई को दूसरी [Size](../../com.aspose.drawing/size) संरचना की चौड़ाई और ऊँचाई से घटाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sz1 | [Size](../../com.aspose.drawing/size) | घटाव ऑपरेटर के बाएँ पक्ष पर स्थित [Size](../../com.aspose.drawing/size) संरचना। |
| sz2 | [Size](../../com.aspose.drawing/size) | घटाव ऑपरेटर के दाएँ पक्ष पर स्थित [Size](../../com.aspose.drawing/size) संरचना। |

**Returns:**
[Size](../../com.aspose.drawing/size) - A [Size](../../com.aspose.drawing/size) structure that is the result of the subtraction operation.
### op_Multiply(int left, Size right) {#op-Multiply-int-com.aspose.drawing.Size-}
```
public static Size op_Multiply(int left, Size right)
```


एक [Size](../../com.aspose.drawing/size) को `int` से गुणा करता है और [Size](../../com.aspose.drawing/size) उत्पन्न करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| बाएँ | int | `int` प्रकार का गुणक। |
| right | [Size](../../com.aspose.drawing/size) | [Size](../../com.aspose.drawing/size) प्रकार का गुणांक। |

**Returns:**
[Size](../../com.aspose.drawing/size) - Product of type [Size](../../com.aspose.drawing/size).
### op_Multiply(Size left, int right) {#op-Multiply-com.aspose.drawing.Size-int-}
```
public static Size op_Multiply(Size left, int right)
```


[Size](../../com.aspose.drawing/size) को `int` से गुणा करता है और [Size](../../com.aspose.drawing/size) उत्पन्न करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| left | [Size](../../com.aspose.drawing/size) | [Size](../../com.aspose.drawing/size) प्रकार का गुणांक। |
| दाएँ | int | `int` प्रकार का गुणक। |

**Returns:**
[Size](../../com.aspose.drawing/size) - Product of type [Size](../../com.aspose.drawing/size).
### op_Division(Size left, int right) {#op-Division-com.aspose.drawing.Size-int-}
```
public static Size op_Division(Size left, int right)
```


[Size](../../com.aspose.drawing/size) को `int` से विभाजित करता है और [Size](../../com.aspose.drawing/size) उत्पन्न करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| left | [Size](../../com.aspose.drawing/size) | डिविडेंड का प्रकार [Size](../../com.aspose.drawing/size) है। |
| दाएँ | int | डिवाइज़र का प्रकार `int` है। |

**Returns:**
[Size](../../com.aspose.drawing/size) - Result of type [Size](../../com.aspose.drawing/size).
### op_Multiply(float left, Size right) {#op-Multiply-float-com.aspose.drawing.Size-}
```
public static SizeF op_Multiply(float left, Size right)
```


[Size](../../com.aspose.drawing/size) को `float` से गुणा करता है और [SizeF](../../com.aspose.drawing/sizef) उत्पन्न करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| बाएँ | फ़्लोट | मल्टिप्लायर का प्रकार `float` है। |
| right | [Size](../../com.aspose.drawing/size) | [Size](../../com.aspose.drawing/size) प्रकार का गुणांक। |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - Product of type [SizeF](../../com.aspose.drawing/sizef).
### op_Multiply(Size left, float right) {#op-Multiply-com.aspose.drawing.Size-float-}
```
public static SizeF op_Multiply(Size left, float right)
```


[Size](../../com.aspose.drawing/size) को `float` से गुणा करता है और [SizeF](../../com.aspose.drawing/sizef) उत्पन्न करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| left | [Size](../../com.aspose.drawing/size) | [Size](../../com.aspose.drawing/size) प्रकार का गुणांक। |
| दाएँ | फ़्लोट | मल्टिप्लायर का प्रकार `float` है। |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - Product of type [SizeF](../../com.aspose.drawing/sizef).
### op_Division(Size left, float right) {#op-Division-com.aspose.drawing.Size-float-}
```
public static SizeF op_Division(Size left, float right)
```


एक `float` द्वारा [Size](../../com.aspose.drawing/size) को विभाजित करता है और [SizeF](../../com.aspose.drawing/sizef) उत्पन्न करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| left | [Size](../../com.aspose.drawing/size) | डिविडेंड का प्रकार [Size](../../com.aspose.drawing/size) है। |
| दाएँ | फ़्लोट | डिवाइज़र का प्रकार `int` है। |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - Result of type [SizeF](../../com.aspose.drawing/sizef).
### op_Equality(Size sz1, Size sz2) {#op-Equality-com.aspose.drawing.Size-com.aspose.drawing.Size-}
```
public static boolean op_Equality(Size sz1, Size sz2)
```


जाँचता है कि दो [Size](../../com.aspose.drawing/size) संरचनाएँ समान हैं या नहीं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sz1 | [Size](../../com.aspose.drawing/size) | समानता ऑपरेटर के बाएँ पक्ष में स्थित [Size](../../com.aspose.drawing/size) संरचना। |
| sz2 | [Size](../../com.aspose.drawing/size) | समानता ऑपरेटर के दाएँ पक्ष में स्थित [Size](../../com.aspose.drawing/size) संरचना। |

**Returns:**
बूलियन - `sz1` और `sz2` की चौड़ाई और ऊँचाई समान होने पर true; अन्यथा false।
### op_Inequality(Size sz1, Size sz2) {#op-Inequality-com.aspose.drawing.Size-com.aspose.drawing.Size-}
```
public static boolean op_Inequality(Size sz1, Size sz2)
```


जाँचता है कि दो [Size](../../com.aspose.drawing/size) संरचनाएँ अलग हैं या नहीं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sz1 | [Size](../../com.aspose.drawing/size) | असमानता ऑपरेटर के बाएँ पक्ष में स्थित [Size](../../com.aspose.drawing/size) संरचना। |
| sz2 | [Size](../../com.aspose.drawing/size) | असमानता ऑपरेटर के दाएँ पक्ष में स्थित [Size](../../com.aspose.drawing/size) संरचना। |

**Returns:**
बूलियन - यदि `sz1` और `sz2` की चौड़ाई या ऊँचाई में कोई अंतर है तो true; यदि `sz1` और `sz2` समान हैं तो false।
### to_Point(Size size) {#to-Point-com.aspose.drawing.Size-}
```
public static Point to_Point(Size size)
```


निर्दिष्ट [Size](../../com.aspose.drawing/size) को एक [Point](../../com.aspose.drawing/point) में परिवर्तित करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| size | [Size](../../com.aspose.drawing/size) | परिवर्तित करने के लिए [Size](../../com.aspose.drawing/size)। |

**Returns:**
[Point](../../com.aspose.drawing/point) - The [Point](../../com.aspose.drawing/point) structure to which this operator converts.
### add(Size sz1, Size sz2) {#add-com.aspose.drawing.Size-com.aspose.drawing.Size-}
```
public static Size add(Size sz1, Size sz2)
```


एक [Size](../../com.aspose.drawing/size) संरचना की चौड़ाई और ऊँचाई को दूसरी [Size](../../com.aspose.drawing/size) संरचना की चौड़ाई और ऊँचाई में जोड़ता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sz1 | [Size](../../com.aspose.drawing/size) | पहला जोड़ने वाला [Size](../../com.aspose.drawing/size)। |
| sz2 | [Size](../../com.aspose.drawing/size) | दूसरा जोड़ने वाला [Size](../../com.aspose.drawing/size)। |

**Returns:**
[Size](../../com.aspose.drawing/size) - A [Size](../../com.aspose.drawing/size) structure that is the result of the addition operation.
### ceiling(SizeF value) {#ceiling-com.aspose.drawing.SizeF-}
```
public static Size ceiling(SizeF value)
```


निर्दिष्ट [SizeF](../../com.aspose.drawing/sizef) संरचना को [Size](../../com.aspose.drawing/size) संरचना में परिवर्तित करता है, [Size](../../com.aspose.drawing/size) संरचना के मानों को अगले बड़े पूर्णांक मान तक गोल करके।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.drawing/sizef) | [SizeF](../../com.aspose.drawing/sizef) संरचना को बदलने के लिए। |

**Returns:**
[Size](../../com.aspose.drawing/size) - The [Size](../../com.aspose.drawing/size) structure this method converts to.
### subtract(Size sz1, Size sz2) {#subtract-com.aspose.drawing.Size-com.aspose.drawing.Size-}
```
public static Size subtract(Size sz1, Size sz2)
```


एक [Size](../../com.aspose.drawing/size) संरचना की चौड़ाई और ऊँचाई को दूसरी [Size](../../com.aspose.drawing/size) संरचना की चौड़ाई और ऊँचाई से घटाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sz1 | [Size](../../com.aspose.drawing/size) | घटाव ऑपरेटर के बाएँ पक्ष पर स्थित [Size](../../com.aspose.drawing/size) संरचना। |
| sz2 | [Size](../../com.aspose.drawing/size) | घटाव ऑपरेटर के दाएँ पक्ष पर स्थित [Size](../../com.aspose.drawing/size) संरचना। |

**Returns:**
[Size](../../com.aspose.drawing/size) - The [Size](../../com.aspose.drawing/size) that is a result of the subtraction operation.
### truncate(SizeF value) {#truncate-com.aspose.drawing.SizeF-}
```
public static Size truncate(SizeF value)
```


निर्दिष्ट [SizeF](../../com.aspose.drawing/sizef) संरचना को [Size](../../com.aspose.drawing/size) संरचना में परिवर्तित करता है, [SizeF](../../com.aspose.drawing/sizef) संरचना के मानों को अगले छोटे पूर्णांक मान तक काटकर।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.drawing/sizef) | [SizeF](../../com.aspose.drawing/sizef) संरचना को बदलने के लिए। |

**Returns:**
[Size](../../com.aspose.drawing/size) - The [Size](../../com.aspose.drawing/size) structure this method converts to.
### round(SizeF value) {#round-com.aspose.drawing.SizeF-}
```
public static Size round(SizeF value)
```


निर्दिष्ट [SizeF](../../com.aspose.drawing/sizef) संरचना को [Size](../../com.aspose.drawing/size) संरचना में परिवर्तित करता है, [SizeF](../../com.aspose.drawing/sizef) संरचना के मानों को निकटतम पूर्णांक मान तक गोल करके।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.drawing/sizef) | [SizeF](../../com.aspose.drawing/sizef) संरचना को बदलने के लिए। |

**Returns:**
[Size](../../com.aspose.drawing/size) - The [Size](../../com.aspose.drawing/size) structure this method converts to.
### isEquals(Size obj1, Size obj2) {#isEquals-com.aspose.drawing.Size-com.aspose.drawing.Size-}
```
public static boolean isEquals(Size obj1, Size obj2)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj1 | [Size](../../com.aspose.drawing/size) |  |
| obj2 | [Size](../../com.aspose.drawing/size) |  |

**Returns:**
boolean
### getEmpty() {#getEmpty--}
```
public static Size getEmpty()
```




**Returns:**
[Size](../../com.aspose.drawing/size)
### isEmpty() {#isEmpty--}
```
public final boolean isEmpty()
```


एक मान प्राप्त करता है जो दर्शाता है कि यह [Size](../../com.aspose.drawing/size) की चौड़ाई और ऊँचाई 0 है या नहीं।

**Returns:**
बूलियन - यह दर्शाने वाला मान कि यह [Size](../../com.aspose.drawing/size) की चौड़ाई और ऊँचाई 0 है या नहीं।
### getWidth() {#getWidth--}
```
public final int getWidth()
```


इस [Size](../../com.aspose.drawing/size) का क्षैतिज घटक प्राप्त करता है।

**Returns:**
int - इस [Size](../../com.aspose.drawing/size) का क्षैतिज घटक।
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


इस [Size](../../com.aspose.drawing/size) का क्षैतिज घटक सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int | इस [Size](../../com.aspose.drawing/size) का क्षैतिज घटक। |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


इस [Size](../../com.aspose.drawing/size) का लंबवत घटक प्राप्त करता है।

**Returns:**
int - इस [Size](../../com.aspose.drawing/size) का लंबवत घटक।
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


इस [Size](../../com.aspose.drawing/size) का लंबवत घटक सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int | इस [Size](../../com.aspose.drawing/size) का लंबवत घटक। |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


जाँचता है कि क्या निर्दिष्ट वस्तु एक [Size](../../com.aspose.drawing/size) है जिसका आयाम इस [Size](../../com.aspose.drawing/size) के समान है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | java.lang.Object | परीक्षण करने के लिए ऑब्जेक्ट। |

**Returns:**
बूलियन - यदि `obj` एक [Size](../../com.aspose.drawing/size) है और इसकी चौड़ाई व ऊँचाई इस [Size](../../com.aspose.drawing/size) के समान हैं तो true; अन्यथा false।
### hashCode() {#hashCode--}
```
public int hashCode()
```


इस [Size](../../com.aspose.drawing/size) संरचना के लिए एक हैश कोड लौटाता है।

**Returns:**
int - एक पूर्णांक मान जो इस [Size](../../com.aspose.drawing/size) संरचना के लिए हैश मान निर्दिष्ट करता है।
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### equals(Size other) {#equals-com.aspose.drawing.Size-}
```
public final boolean equals(Size other)
```


जाँचता है कि क्या अन्य [Size](../../com.aspose.drawing/size) संरचना का आकार इस [Size](../../com.aspose.drawing/size) संरचना के समान है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| other | [Size](../../com.aspose.drawing/size) | परीक्षण के लिए अन्य आकार |

**Returns:**
बूलियन - यह मेथड `true` लौटाता है यदि अन्य [Size](../../com.aspose.drawing/size) संरचना और उसकी Width तथा Height प्रॉपर्टी इस [Size](../../com.aspose.drawing/size) संरचना की संबंधित प्रॉपर्टी के समान हैं; अन्यथा `false`।
### CloneTo(Size that) {#CloneTo-com.aspose.drawing.Size-}
```
public void CloneTo(Size that)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| that | [Size](../../com.aspose.drawing/size) |  |

### Clone() {#Clone--}
```
public Size Clone()
```




**Returns:**
[Size](../../com.aspose.drawing/size)
### clone() {#clone--}
```
public Size clone()
```




**Returns:**
[Size](../../com.aspose.drawing/size)
