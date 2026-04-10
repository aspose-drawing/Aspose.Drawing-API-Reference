---
title: बिंदु
second_title: Aspose.Drawing for Java API संदर्भ
description: एक क्रमबद्ध जोड़ी पूर्णांक x और y निर्देशांक को दर्शाता है जो दो-आयामी तल में एक बिंदु को परिभाषित करता है।
type: docs
weight: 36
url: /hi/java/com.aspose.drawing/point/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable, java.lang.Cloneable
```
public class Point extends Struct<Point> implements System.IEquatable<Point>, Cloneable
```

एक क्रमबद्ध जोड़ी पूर्णांक x और y निर्देशांक को दर्शाता है जो दो-आयामी तल में एक बिंदु को परिभाषित करता है।
## निर्माता

| निर्माता | विवरण |
| --- | --- |
| [Point()](#Point--) |  |
| [Point(int x, int y)](#Point-int-int-) | निर्दिष्ट निर्देशांक के साथ [Point](../../com.aspose.drawing/point) स्ट्रक्ट का नया उदाहरण आरंभ करता है। |
| [Point(Size sz)](#Point-com.aspose.drawing.Size-) |  |
| [Point(int dw)](#Point-int-) | पूर्णांक मान द्वारा निर्दिष्ट निर्देशांक का उपयोग करके [Point](../../com.aspose.drawing/point) स्ट्रक्ट का नया उदाहरण आरंभ करता है। |
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [EMPTY](#EMPTY) | [Point](../../com.aspose.drawing/point) को दर्शाता है जिसकी `Point.X` और `Point.Y` मान शून्य पर सेट हैं। |
## मेथड्स

| विधि | विवरण |
| --- | --- |
| [to_PointF(Point p)](#to-PointF-com.aspose.drawing.Point-) | निर्दिष्ट [Point](../../com.aspose.drawing/point) संरचना को [PointF](../../com.aspose.drawing/pointf) संरचना में परिवर्तित करता है। |
| [to_Size(Point p)](#to-Size-com.aspose.drawing.Point-) |  |
| [op_Addition(Point pt, Size sz)](#op-Addition-com.aspose.drawing.Point-com.aspose.drawing.Size-) |  |
| [op_Subtraction(Point pt, Size sz)](#op-Subtraction-com.aspose.drawing.Point-com.aspose.drawing.Size-) |  |
| [op_Equality(Point left, Point right)](#op-Equality-com.aspose.drawing.Point-com.aspose.drawing.Point-) | दो [Point](../../com.aspose.drawing/point) ऑब्जेक्ट्स की तुलना करता है। |
| [op_Inequality(Point left, Point right)](#op-Inequality-com.aspose.drawing.Point-com.aspose.drawing.Point-) | दो [Point](../../com.aspose.drawing/point) ऑब्जेक्ट्स की तुलना करता है। |
| [add(Point pt, Size sz)](#add-com.aspose.drawing.Point-com.aspose.drawing.Size-) | निर्दिष्ट [Size](../../com.aspose.drawing/size) को निर्दिष्ट [Point](../../com.aspose.drawing/point) में जोड़ता है। |
| [subtract(Point pt, Size sz)](#subtract-com.aspose.drawing.Point-com.aspose.drawing.Size-) |  |
| [ceiling(PointF value)](#ceiling-com.aspose.drawing.PointF-) |  |
| [truncate(PointF value)](#truncate-com.aspose.drawing.PointF-) | सभी निर्देशांकों पर ट्रंकेट ऑपरेशन करके PointF को Point में परिवर्तित करता है। |
| [round(PointF value)](#round-com.aspose.drawing.PointF-) | निर्दिष्ट [PointF](../../com.aspose.drawing/pointf) को [Point](../../com.aspose.drawing/point) मानों को निकटतम पूर्णांक तक गोल करके Point ऑब्जेक्ट में परिवर्तित करता है। |
| [isEquals(Point obj1, Point obj2)](#isEquals-com.aspose.drawing.Point-com.aspose.drawing.Point-) |  |
| [getEmpty()](#getEmpty--) |  |
| [getX()](#getX--) | इस Point का x-निर्देशांक प्राप्त करता है। |
| [setX(int value)](#setX-int-) | इस Point का x-निर्देशांक सेट करता है। |
| [getY()](#getY--) | इस Point का y-निर्देशांक प्राप्त करता है। |
| [setY(int value)](#setY-int-) | इस Point का y-निर्देशांक सेट करता है। |
| [isEmpty()](#isEmpty--) | इस [Point](../../com.aspose.drawing/point) के खाली होने का संकेत देने वाला मान प्राप्त करता है। |
| [hashCode()](#hashCode--) | इस [Point](../../com.aspose.drawing/point) के लिए हैश कोड लौटाता है। |
| [toString()](#toString--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | निर्दिष्ट ऑब्जेक्ट के समान निर्देशांक इस [Point](../../com.aspose.drawing/point) में हैं या नहीं, यह निर्दिष्ट करता है। |
| [offset(int dx, int dy)](#offset-int-int-) | निर्दिष्ट मात्रा द्वारा इस [Point](../../com.aspose.drawing/point) को स्थानांतरित करता है। |
| [offset(Point p)](#offset-com.aspose.drawing.Point-) | निर्दिष्ट [Point](../../com.aspose.drawing/point) द्वारा इस [Point](../../com.aspose.drawing/point) को स्थानांतरित करता है। |
| [equals(Point other)](#equals-com.aspose.drawing.Point-) | जाँचता है कि अन्य [Point](../../com.aspose.drawing/point) संरचना का स्थान इस [Point](../../com.aspose.drawing/point) संरचना के समान है या नहीं। |
| [CloneTo(Point that)](#CloneTo-com.aspose.drawing.Point-) |  |
| [Clone()](#Clone--) |  |
| [clone()](#clone--) |  |
### Point() {#Point--}
```
public Point()
```


### Point(int x, int y) {#Point-int-int-}
```
public Point(int x, int y)
```


निर्दिष्ट निर्देशांक के साथ [Point](../../com.aspose.drawing/point) स्ट्रक्ट का नया उदाहरण आरंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | int | बिंदु की क्षैतिज स्थिति। |
| y | int | बिंदु की लंबवत स्थिति। |

### Point(Size sz) {#Point-com.aspose.drawing.Size-}
```
public Point(Size sz)
```


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sz | [Size](../../com.aspose.drawing/size) |  |

### Point(int dw) {#Point-int-}
```
public Point(int dw)
```


पूर्णांक मान द्वारा निर्दिष्ट निर्देशांक का उपयोग करके [Point](../../com.aspose.drawing/point) स्ट्रक्ट का नया उदाहरण आरंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| dw | int | पूर्णांक मान। |

### EMPTY {#EMPTY}
```
public static final Point EMPTY
```


[Point](../../com.aspose.drawing/point) को दर्शाता है जिसकी `Point.X` और `Point.Y` मान शून्य पर सेट हैं।

### to_PointF(Point p) {#to-PointF-com.aspose.drawing.Point-}
```
public static PointF to_PointF(Point p)
```


निर्दिष्ट [Point](../../com.aspose.drawing/point) संरचना को [PointF](../../com.aspose.drawing/pointf) संरचना में परिवर्तित करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| p | [Point](../../com.aspose.drawing/point) | परिवर्तित करने के लिए [Point](../../com.aspose.drawing/point)। |

**Returns:**
[PointF](../../com.aspose.drawing/pointf) - The [PointF](../../com.aspose.drawing/pointf) that results from the conversion.
### to_Size(Point p) {#to-Size-com.aspose.drawing.Point-}
```
public static Size to_Size(Point p)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| p | [Point](../../com.aspose.drawing/point) |  |

**Returns:**
[Size](../../com.aspose.drawing/size)
### op_Addition(Point pt, Size sz) {#op-Addition-com.aspose.drawing.Point-com.aspose.drawing.Size-}
```
public static Point op_Addition(Point pt, Size sz)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pt | [Point](../../com.aspose.drawing/point) |  |
| sz | [Size](../../com.aspose.drawing/size) |  |

**Returns:**
[Point](../../com.aspose.drawing/point)
### op_Subtraction(Point pt, Size sz) {#op-Subtraction-com.aspose.drawing.Point-com.aspose.drawing.Size-}
```
public static Point op_Subtraction(Point pt, Size sz)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pt | [Point](../../com.aspose.drawing/point) |  |
| sz | [Size](../../com.aspose.drawing/size) |  |

**Returns:**
[Point](../../com.aspose.drawing/point)
### op_Equality(Point left, Point right) {#op-Equality-com.aspose.drawing.Point-com.aspose.drawing.Point-}
```
public static boolean op_Equality(Point left, Point right)
```


दो [Point](../../com.aspose.drawing/point) ऑब्जेक्ट्स की तुलना करता है। परिणाम यह निर्दिष्ट करता है कि दो [Point](../../com.aspose.drawing/point) ऑब्जेक्ट्स की `Point.X` और `Point.Y` प्रॉपर्टीज़ के मान समान हैं या नहीं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| left | [Point](../../com.aspose.drawing/point) | पहला तुलना करने के लिए [Point](../../com.aspose.drawing/point)। |
| right | [Point](../../com.aspose.drawing/point) | दूसरा तुलना करने के लिए [Point](../../com.aspose.drawing/point)। |

**Returns:**
boolean - `true` यदि `left` और `right` के `Point.X` और `Point.Y` मान समान हैं; अन्यथा `false`।
### op_Inequality(Point left, Point right) {#op-Inequality-com.aspose.drawing.Point-com.aspose.drawing.Point-}
```
public static boolean op_Inequality(Point left, Point right)
```


दो [Point](../../com.aspose.drawing/point) ऑब्जेक्ट्स की तुलना करता है। परिणाम यह निर्दिष्ट करता है कि दो [Point](../../com.aspose.drawing/point) ऑब्जेक्ट्स की `Point.X` या `Point.Y` प्रॉपर्टीज़ के मान असमान हैं या नहीं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| left | [Point](../../com.aspose.drawing/point) | पहला तुलना करने के लिए [Point](../../com.aspose.drawing/point)। |
| right | [Point](../../com.aspose.drawing/point) | दूसरा तुलना करने के लिए [Point](../../com.aspose.drawing/point)। |

**Returns:**
boolean - `true` यदि `left` और `right` की `Point.X` या `Point.Y` प्रॉपर्टीज़ में से किसी का मान अलग है; अन्यथा `false`।
### add(Point pt, Size sz) {#add-com.aspose.drawing.Point-com.aspose.drawing.Size-}
```
public static Point add(Point pt, Size sz)
```


निर्दिष्ट [Size](../../com.aspose.drawing/size) को निर्दिष्ट [Point](../../com.aspose.drawing/point) में जोड़ता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pt | [Point](../../com.aspose.drawing/point) | जोड़ने के लिए [Point](../../com.aspose.drawing/point)। |
| sz | [Size](../../com.aspose.drawing/size) | जोड़ने के लिए [Size](../../com.aspose.drawing/size) |

**Returns:**
[Point](../../com.aspose.drawing/point) - The [Point](../../com.aspose.drawing/point) that is the result of the addition operation.
### subtract(Point pt, Size sz) {#subtract-com.aspose.drawing.Point-com.aspose.drawing.Size-}
```
public static Point subtract(Point pt, Size sz)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pt | [Point](../../com.aspose.drawing/point) |  |
| sz | [Size](../../com.aspose.drawing/size) |  |

**Returns:**
[Point](../../com.aspose.drawing/point)
### ceiling(PointF value) {#ceiling-com.aspose.drawing.PointF-}
```
public static Point ceiling(PointF value)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [PointF](../../com.aspose.drawing/pointf) |  |

**Returns:**
[Point](../../com.aspose.drawing/point)
### truncate(PointF value) {#truncate-com.aspose.drawing.PointF-}
```
public static Point truncate(PointF value)
```


सभी निर्देशांकों पर ट्रंकेट ऑपरेशन करके PointF को Point में परिवर्तित करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [PointF](../../com.aspose.drawing/pointf) | कट करने के लिए [PointF](../../com.aspose.drawing/pointf)। |

**Returns:**
[Point](../../com.aspose.drawing/point) - The [Point](../../com.aspose.drawing/point) that is the result of the truncate operation.
### round(PointF value) {#round-com.aspose.drawing.PointF-}
```
public static Point round(PointF value)
```


निर्दिष्ट [PointF](../../com.aspose.drawing/pointf) को [Point](../../com.aspose.drawing/point) मानों को निकटतम पूर्णांक तक गोल करके Point ऑब्जेक्ट में परिवर्तित करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [PointF](../../com.aspose.drawing/pointf) | परिवर्तित करने के लिए [PointF](../../com.aspose.drawing/pointf)। |

**Returns:**
[Point](../../com.aspose.drawing/point) - The [Point](../../com.aspose.drawing/point) this method converts to.
### isEquals(Point obj1, Point obj2) {#isEquals-com.aspose.drawing.Point-com.aspose.drawing.Point-}
```
public static boolean isEquals(Point obj1, Point obj2)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj1 | [Point](../../com.aspose.drawing/point) |  |
| obj2 | [Point](../../com.aspose.drawing/point) |  |

**Returns:**
boolean
### getEmpty() {#getEmpty--}
```
public static Point getEmpty()
```




**Returns:**
[Point](../../com.aspose.drawing/point)
### getX() {#getX--}
```
public final int getX()
```


इस Point का x-निर्देशांक प्राप्त करता है।

**Returns:**
int - इस Point का x-निर्देशांक।
### setX(int value) {#setX-int-}
```
public final void setX(int value)
```


इस Point का x-निर्देशांक सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int | इस Point का x-निर्देशांक। |

### getY() {#getY--}
```
public final int getY()
```


इस Point का y-निर्देशांक प्राप्त करता है।

**Returns:**
int - इस Point का y-निर्देशांक।
### setY(int value) {#setY-int-}
```
public final void setY(int value)
```


इस Point का y-निर्देशांक सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int | इस Point का y-निर्देशांक। |

### isEmpty() {#isEmpty--}
```
public final boolean isEmpty()
```


इस [Point](../../com.aspose.drawing/point) के खाली होने का संकेत देने वाला मान प्राप्त करता है।

मान: यदि X और Y दोनों 0 हैं तो `true`; अन्यथा `false`।

**Returns:**
boolean - एक मान जो यह दर्शाता है कि यह [Point](../../com.aspose.drawing/point) खाली है या नहीं।
### hashCode() {#hashCode--}
```
public int hashCode()
```


इस [Point](../../com.aspose.drawing/point) के लिए हैश कोड लौटाता है।

**Returns:**
int - एक पूर्णांक मान जो इस [Point](../../com.aspose.drawing/point) के लिए हैश मान निर्दिष्ट करता है।
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


निर्दिष्ट ऑब्जेक्ट के समान निर्देशांक इस [Point](../../com.aspose.drawing/point) में हैं या नहीं, यह निर्दिष्ट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | java.lang.Object | परीक्षण करने के लिए ऑब्जेक्ट। |

**Returns:**
boolean - `true` यदि obj एक Point है और इस [Point](../../com.aspose.drawing/point) के समान निर्देशांक रखता है।
### offset(int dx, int dy) {#offset-int-int-}
```
public final void offset(int dx, int dy)
```


निर्दिष्ट मात्रा द्वारा इस [Point](../../com.aspose.drawing/point) को स्थानांतरित करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| dx | int | x-निर्देशांक को ऑफसेट करने की मात्रा। |
| dy | int | y-निर्देशांक को ऑफसेट करने की मात्रा। |

### offset(Point p) {#offset-com.aspose.drawing.Point-}
```
public final void offset(Point p)
```


निर्दिष्ट [Point](../../com.aspose.drawing/point) द्वारा इस [Point](../../com.aspose.drawing/point) को स्थानांतरित करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| p | [Point](../../com.aspose.drawing/point) | यह [Point](../../com.aspose.drawing/point) इस [Point](../../com.aspose.drawing/point) को ऑफसेट करने के लिए उपयोग किया गया। |

### equals(Point other) {#equals-com.aspose.drawing.Point-}
```
public final boolean equals(Point other)
```


जाँचता है कि अन्य [Point](../../com.aspose.drawing/point) संरचना का स्थान इस [Point](../../com.aspose.drawing/point) संरचना के समान है या नहीं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| other | [Point](../../com.aspose.drawing/point) | परीक्षण के लिए अन्य बिंदु |

**Returns:**
boolean - यह मेथड `true` लौटाता है यदि अन्य [Point](../../com.aspose.drawing/point) संरचना और उसकी X और Y प्रॉपर्टीज़ इस [Point](../../com.aspose.drawing/point) संरचना की संबंधित प्रॉपर्टीज़ के बराबर हैं; अन्यथा `false`।
### CloneTo(Point that) {#CloneTo-com.aspose.drawing.Point-}
```
public void CloneTo(Point that)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| that | [Point](../../com.aspose.drawing/point) |  |

### Clone() {#Clone--}
```
public Point Clone()
```




**Returns:**
[Point](../../com.aspose.drawing/point)
### clone() {#clone--}
```
public Object clone()
```




**Returns:**
java.lang.Object
