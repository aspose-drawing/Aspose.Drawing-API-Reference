---
title: Rectangle
second_title: Aspose.Drawing for Java API संदर्भ
description: चार पूर्णांकों का एक सेट संग्रहीत करता है जो आयत के स्थान और आकार को दर्शाते हैं।
type: docs
weight: 38
url: /hi/java/com.aspose.drawing/rectangle/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable, java.lang.Cloneable
```
public class Rectangle extends Struct<Rectangle> implements System.IEquatable<Rectangle>, Cloneable
```

चार पूर्णांकों का एक सेट संग्रहीत करता है जो आयत के स्थान और आकार को दर्शाते हैं।
## निर्माता

| निर्माता | विवरण |
| --- | --- |
| [Rectangle()](#Rectangle--) |  |
| [Rectangle(int x, int y, int width, int height)](#Rectangle-int-int-int-int-) | निर्दिष्ट स्थान और आकार के साथ Rectangle संरचना का नया उदाहरण प्रारंभ करता है। |
| [Rectangle(Point location, Size size)](#Rectangle-com.aspose.drawing.Point-com.aspose.drawing.Size-) | निर्दिष्ट स्थान और आकार के साथ [Rectangle](../../com.aspose.drawing/rectangle) संरचना का नया उदाहरण प्रारंभ करता है। |
## मेथड्स

| विधि | विवरण |
| --- | --- |
| [fromLTRB(int left, int top, int right, int bottom)](#fromLTRB-int-int-int-int-) | निर्दिष्ट किनारा स्थानों के साथ एक [Rectangle](../../com.aspose.drawing/rectangle) संरचना बनाता है। |
| [intersect(Rectangle a, Rectangle b)](#intersect-com.aspose.drawing.Rectangle-com.aspose.drawing.Rectangle-) | दो अन्य [Rectangle](../../com.aspose.drawing/rectangle) संरचनाओं के प्रतिच्छेदन को दर्शाने वाली तीसरी [Rectangle](../../com.aspose.drawing/rectangle) संरचना लौटाता है। |
| [op_Equality(Rectangle left, Rectangle right)](#op-Equality-com.aspose.drawing.Rectangle-com.aspose.drawing.Rectangle-) | जाँचता है कि क्या दो [Rectangle](../../com.aspose.drawing/rectangle) संरचनाओं का स्थान और आकार समान है। |
| [op_Inequality(Rectangle left, Rectangle right)](#op-Inequality-com.aspose.drawing.Rectangle-com.aspose.drawing.Rectangle-) | जाँचता है कि क्या दो [Rectangle](../../com.aspose.drawing/rectangle) संरचनाओं का स्थान या आकार अलग है। |
| [ceiling(RectangleF value)](#ceiling-com.aspose.drawing.RectangleF-) | निर्दिष्ट [RectangleF](../../com.aspose.drawing/rectanglef) संरचना को [Rectangle](../../com.aspose.drawing/rectangle) संरचना में परिवर्तित करता है, [RectangleF](../../com.aspose.drawing/rectanglef) मानों को अगले उच्च पूर्णांक मान तक गोल करके। |
| [truncate(RectangleF value)](#truncate-com.aspose.drawing.RectangleF-) | निर्दिष्ट [RectangleF](../../com.aspose.drawing/rectanglef) को [Rectangle](../../com.aspose.drawing/rectangle) में परिवर्तित करता है, [RectangleF](../../com.aspose.drawing/rectanglef) मानों को काटकर। |
| [round(RectangleF value)](#round-com.aspose.drawing.RectangleF-) | निर्दिष्ट [RectangleF](../../com.aspose.drawing/rectanglef) को [Rectangle](../../com.aspose.drawing/rectangle) में परिवर्तित करता है, [RectangleF](../../com.aspose.drawing/rectanglef) मानों को निकटतम पूर्णांक मान तक गोल करके। |
| [union(Rectangle a, Rectangle b)](#union-com.aspose.drawing.Rectangle-com.aspose.drawing.Rectangle-) | दो [Rectangle](../../com.aspose.drawing/rectangle) संरचनाओं के संघ को सम्मिलित करने वाली एक [Rectangle](../../com.aspose.drawing/rectangle) संरचना प्राप्त करता है। |
| [inflate(Rectangle rect, int x, int y)](#inflate-com.aspose.drawing.Rectangle-int-int-) |  |
| [isEquals(Rectangle obj1, Rectangle obj2)](#isEquals-com.aspose.drawing.Rectangle-com.aspose.drawing.Rectangle-) |  |
| [fromPoints(Point point1, Point point2)](#fromPoints-com.aspose.drawing.Point-com.aspose.drawing.Point-) | दो बिंदुओं से एक नया आयत बनाता है। |
| [getEmpty()](#getEmpty--) | `Rectangle` संरचना का नया उदाहरण प्राप्त करता है जिसमें `Rectangle.X`, `Rectangle.Y`, `Rectangle.Width` और `Rectangle.Height` मान शून्य पर सेट होते हैं। |
| [getX()](#getX--) | इस Rectangle संरचना के ऊपरी-बाएँ कोने का x-निर्देशांक प्राप्त करता है। |
| [setX(int value)](#setX-int-) | इस Rectangle संरचना के ऊपरी-बाएँ कोने का x-निर्देशांक सेट करता है। |
| [getY()](#getY--) | इस Rectangle संरचना के ऊपरी-बाएँ कोने का y-निर्देशांक प्राप्त करता है। |
| [setY(int value)](#setY-int-) | इस Rectangle संरचना के ऊपरी-बाएँ कोने का y-निर्देशांक सेट करता है। |
| [getLocation()](#getLocation--) | इस [Rectangle](../../com.aspose.drawing/rectangle) संरचना के ऊपरी-बाएँ कोने के निर्देशांक प्राप्त करता है। |
| [setLocation(Point value)](#setLocation-com.aspose.drawing.Point-) | इस [Rectangle](../../com.aspose.drawing/rectangle) संरचना के ऊपर-बाएँ कोने के निर्देशांक सेट करता है। |
| [getWidth()](#getWidth--) | इस Rectangle संरचना की चौड़ाई प्राप्त करता है। |
| [setWidth(int value)](#setWidth-int-) | इस Rectangle संरचना की चौड़ाई सेट करता है। |
| [getHeight()](#getHeight--) | इस Rectangle संरचना की ऊँचाई प्राप्त करता है। |
| [setHeight(int value)](#setHeight-int-) | इस Rectangle संरचना की ऊँचाई सेट करता है। |
| [getSize()](#getSize--) | इस [Rectangle](../../com.aspose.drawing/rectangle) का आकार प्राप्त करता है। |
| [setSize(Size value)](#setSize-com.aspose.drawing.Size-) | इस [Rectangle](../../com.aspose.drawing/rectangle) का आकार सेट करता है। |
| [getLeft()](#getLeft--) | इस Rectangle संरचना के बाएँ किनारे का x-निर्देशांक प्राप्त करता है। |
| [getTop()](#getTop--) | इस Rectangle संरचना के शीर्ष किनारे का y-निर्देशांक प्राप्त करता है। |
| [getRight()](#getRight--) | इस Rectangle संरचना के X और Width प्रॉपर्टी मानों के योग के रूप में x-निर्देशांक प्राप्त करता है। |
| [getBottom()](#getBottom--) | इस Rectangle संरचना के Y और Height प्रॉपर्टी मानों के योग के रूप में y-निर्देशांक प्राप्त करता है। |
| [isEmpty()](#isEmpty--) | एक मान प्राप्त करता है जो दर्शाता है कि इस [Rectangle](../../com.aspose.drawing/rectangle) की सभी संख्यात्मक प्रॉपर्टी का मान शून्य है या नहीं। |
| [equals(Object obj)](#equals-java.lang.Object-) | परीक्षण करता है कि क्या obj इस [Rectangle](../../com.aspose.drawing/rectangle) संरचना के समान स्थान और आकार वाला [Rectangle](../../com.aspose.drawing/rectangle) संरचना है। |
| [hashCode()](#hashCode--) | इस [Rectangle](../../com.aspose.drawing/rectangle) संरचना के लिए हैश कोड लौटाता है। |
| [toString()](#toString--) |  |
| [intersect(Rectangle rect)](#intersect-com.aspose.drawing.Rectangle-) | इस [Rectangle](../../com.aspose.drawing/rectangle) को स्वयं और निर्दिष्ट [Rectangle](../../com.aspose.drawing/rectangle) के प्रतिच्छेदन से बदलता है। |
| [inflate(int width, int height)](#inflate-int-int-) | इस [Rectangle](../../com.aspose.drawing/rectangle) को निर्दिष्ट मात्रा से बड़ा करता है। |
| [inflate(Size size)](#inflate-com.aspose.drawing.Size-) | इस [Rectangle](../../com.aspose.drawing/rectangle) को निर्दिष्ट मात्रा से बड़ा करता है। |
| [contains(int x, int y)](#contains-int-int-) | निर्धारित करता है कि निर्दिष्ट बिंदु इस [Rectangle](../../com.aspose.drawing/rectangle) संरचना के भीतर स्थित है या नहीं। |
| [contains(Point pt)](#contains-com.aspose.drawing.Point-) | निर्धारित करता है कि निर्दिष्ट बिंदु इस [Rectangle](../../com.aspose.drawing/rectangle) संरचना के भीतर स्थित है या नहीं। |
| [contains(Rectangle rect)](#contains-com.aspose.drawing.Rectangle-) |  |
| [intersectsWith(Rectangle rect)](#intersectsWith-com.aspose.drawing.Rectangle-) | निर्धारित करता है कि यह आयत `rect` के साथ प्रतिच्छेद करता है या नहीं। |
| [offset(int x, int y)](#offset-int-int-) | निर्दिष्ट मात्रा से इस आयत का स्थान समायोजित करता है। |
| [offset(Point pos)](#offset-com.aspose.drawing.Point-) | निर्दिष्ट मात्रा से इस आयत का स्थान समायोजित करता है। |
| [equals(Rectangle other)](#equals-com.aspose.drawing.Rectangle-) | परीक्षण करता है कि क्या अन्य [Rectangle](../../com.aspose.drawing/rectangle) संरचना का स्थान और आकार इस [Rectangle](../../com.aspose.drawing/rectangle) संरचना के समान है। |
| [CloneTo(Rectangle that)](#CloneTo-com.aspose.drawing.Rectangle-) |  |
| [Clone()](#Clone--) |  |
| [clone()](#clone--) |  |
| [normalize()](#normalize--) | आयत को सामान्यीकृत करता है, इसकी चौड़ाई और ऊँचाई को सकारात्मक बनाकर, बाएँ को दाएँ से कम और शीर्ष को नीचे से कम करता है। |
### Rectangle() {#Rectangle--}
```
public Rectangle()
```


### Rectangle(int x, int y, int width, int height) {#Rectangle-int-int-int-int-}
```
public Rectangle(int x, int y, int width, int height)
```


निर्दिष्ट स्थान और आकार के साथ Rectangle संरचना का नया उदाहरण प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | int | आयत के ऊपर-बाएँ कोने का x-निर्देशांक। |
| y | int | आयत के ऊपर-बाएँ कोने का y-निर्देशांक। |
| चौड़ाई | int | आयत की चौड़ाई। |
| ऊँचाई | int | आयत की ऊँचाई। |

### Rectangle(Point location, Size size) {#Rectangle-com.aspose.drawing.Point-com.aspose.drawing.Size-}
```
public Rectangle(Point location, Size size)
```


निर्दिष्ट स्थान और आकार के साथ [Rectangle](../../com.aspose.drawing/rectangle) संरचना का नया उदाहरण प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| location | [Point](../../com.aspose.drawing/point) | एक [Point](../../com.aspose.drawing/point) जो आयताकार क्षेत्र के ऊपर-बाएँ कोने को दर्शाता है। |
| size | [Size](../../com.aspose.drawing/size) | एक `Size`([.getSize](../../null/\#getSize)/[.setSize(Size)](../../null/\#setSize-Size-)) जो आयताकार क्षेत्र की चौड़ाई और ऊँचाई को दर्शाता है। |

### fromLTRB(int left, int top, int right, int bottom) {#fromLTRB-int-int-int-int-}
```
public static Rectangle fromLTRB(int left, int top, int right, int bottom)
```


निर्दिष्ट किनारा स्थानों के साथ एक [Rectangle](../../com.aspose.drawing/rectangle) संरचना बनाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| left | int | इस [Rectangle](../../com.aspose.drawing/rectangle) संरचना के ऊपर-बाएँ कोने का x-निर्देशांक। |
| top | int | इस [Rectangle](../../com.aspose.drawing/rectangle) संरचना के ऊपर-बाएँ कोने का y-निर्देशांक। |
| right | int | इस [Rectangle](../../com.aspose.drawing/rectangle) संरचना के नीचे-दाएँ कोने का x-निर्देशांक। |
| bottom | int | इस [Rectangle](../../com.aspose.drawing/rectangle) संरचना के नीचे-दाएँ कोने का y-निर्देशांक। |

**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle) - The new [Rectangle](../../com.aspose.drawing/rectangle) that this method creates.
### intersect(Rectangle a, Rectangle b) {#intersect-com.aspose.drawing.Rectangle-com.aspose.drawing.Rectangle-}
```
public static Rectangle intersect(Rectangle a, Rectangle b)
```


तीसरा [Rectangle](../../com.aspose.drawing/rectangle) संरचना लौटाता है जो दो अन्य [Rectangle](../../com.aspose.drawing/rectangle) संरचनाओं के प्रतिच्छेदन का प्रतिनिधित्व करता है। यदि कोई प्रतिच्छेदन नहीं है, तो एक खाली [Rectangle](../../com.aspose.drawing/rectangle) लौटाया जाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| a | [Rectangle](../../com.aspose.drawing/rectangle) | पहला आयत जिसका प्रतिच्छेदन होना है। |
| b | [Rectangle](../../com.aspose.drawing/rectangle) | दूसरा आयत जिसका प्रतिच्छेदन होना है। |

**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle) - A [Rectangle](../../com.aspose.drawing/rectangle) that represents the intersection of `a` and `b`.
### op_Equality(Rectangle left, Rectangle right) {#op-Equality-com.aspose.drawing.Rectangle-com.aspose.drawing.Rectangle-}
```
public static boolean op_Equality(Rectangle left, Rectangle right)
```


जाँचता है कि क्या दो [Rectangle](../../com.aspose.drawing/rectangle) संरचनाओं का स्थान और आकार समान है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| left | [Rectangle](../../com.aspose.drawing/rectangle) | समानता ऑपरेटर के बाएँ स्थित [Rectangle](../../com.aspose.drawing/rectangle) संरचना। |
| right | [Rectangle](../../com.aspose.drawing/rectangle) | समानता ऑपरेटर के दाएँ स्थित [Rectangle](../../com.aspose.drawing/rectangle) संरचना। |

**Returns:**
boolean - यह ऑपरेटर `true` लौटाता है यदि दो [Rectangle](../../com.aspose.drawing/rectangle) संरचनाओं के X, Y, Width, और Height गुण समान हों।
### op_Inequality(Rectangle left, Rectangle right) {#op-Inequality-com.aspose.drawing.Rectangle-com.aspose.drawing.Rectangle-}
```
public static boolean op_Inequality(Rectangle left, Rectangle right)
```


जाँचता है कि क्या दो [Rectangle](../../com.aspose.drawing/rectangle) संरचनाओं का स्थान या आकार अलग है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| left | [Rectangle](../../com.aspose.drawing/rectangle) | असमानता ऑपरेटर के बाएँ स्थित [Rectangle](../../com.aspose.drawing/rectangle) संरचना। |
| right | [Rectangle](../../com.aspose.drawing/rectangle) | असमानता ऑपरेटर के दाएँ स्थित [Rectangle](../../com.aspose.drawing/rectangle) संरचना। |

**Returns:**
boolean - यह ऑपरेटर `true` लौटाता है यदि दो [Rectangle](../../com.aspose.drawing/rectangle) संरचनाओं के X, Y, Width या Height गुणों में से कोई भी असमान हो; अन्यथा `false`।
### ceiling(RectangleF value) {#ceiling-com.aspose.drawing.RectangleF-}
```
public static Rectangle ceiling(RectangleF value)
```


निर्दिष्ट [RectangleF](../../com.aspose.drawing/rectanglef) संरचना को [Rectangle](../../com.aspose.drawing/rectangle) संरचना में परिवर्तित करता है, [RectangleF](../../com.aspose.drawing/rectanglef) मानों को अगले उच्च पूर्णांक मान तक गोल करके।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.drawing/rectanglef) | परिवर्तित करने के लिए [RectangleF](../../com.aspose.drawing/rectanglef) संरचना। |

**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle) - Returns a [Rectangle](../../com.aspose.drawing/rectangle).
### truncate(RectangleF value) {#truncate-com.aspose.drawing.RectangleF-}
```
public static Rectangle truncate(RectangleF value)
```


निर्दिष्ट [RectangleF](../../com.aspose.drawing/rectanglef) को [Rectangle](../../com.aspose.drawing/rectangle) में परिवर्तित करता है, [RectangleF](../../com.aspose.drawing/rectanglef) मानों को काटकर।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.drawing/rectanglef) | परिवर्तित करने के लिए [RectangleF](../../com.aspose.drawing/rectanglef)। |

**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle) - The truncated value of the [Rectangle](../../com.aspose.drawing/rectangle).
### round(RectangleF value) {#round-com.aspose.drawing.RectangleF-}
```
public static Rectangle round(RectangleF value)
```


निर्दिष्ट [RectangleF](../../com.aspose.drawing/rectanglef) को [Rectangle](../../com.aspose.drawing/rectangle) में परिवर्तित करता है, [RectangleF](../../com.aspose.drawing/rectanglef) मानों को निकटतम पूर्णांक मान तक गोल करके।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.drawing/rectanglef) | परिवर्तित करने के लिए [RectangleF](../../com.aspose.drawing/rectanglef)। |

**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle) - A [Rectangle](../../com.aspose.drawing/rectangle).
### union(Rectangle a, Rectangle b) {#union-com.aspose.drawing.Rectangle-com.aspose.drawing.Rectangle-}
```
public static Rectangle union(Rectangle a, Rectangle b)
```


दो [Rectangle](../../com.aspose.drawing/rectangle) संरचनाओं के संघ को सम्मिलित करने वाली एक [Rectangle](../../com.aspose.drawing/rectangle) संरचना प्राप्त करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| a | [Rectangle](../../com.aspose.drawing/rectangle) | पहला आयत जो मिलाया जाना है। |
| b | [Rectangle](../../com.aspose.drawing/rectangle) | दूसरा आयत जो मिलाया जाना है। |

**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle) - A [Rectangle](../../com.aspose.drawing/rectangle) structure that bounds the union of the two [Rectangle](../../com.aspose.drawing/rectangle) structures.
### inflate(Rectangle rect, int x, int y) {#inflate-com.aspose.drawing.Rectangle-int-int-}
```
public static Rectangle inflate(Rectangle rect, int x, int y)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) |  |
| x | int |  |
| y | int |  |

**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle)
### isEquals(Rectangle obj1, Rectangle obj2) {#isEquals-com.aspose.drawing.Rectangle-com.aspose.drawing.Rectangle-}
```
public static boolean isEquals(Rectangle obj1, Rectangle obj2)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj1 | [Rectangle](../../com.aspose.drawing/rectangle) |  |
| obj2 | [Rectangle](../../com.aspose.drawing/rectangle) |  |

**Returns:**
boolean
### fromPoints(Point point1, Point point2) {#fromPoints-com.aspose.drawing.Point-com.aspose.drawing.Point-}
```
public static Rectangle fromPoints(Point point1, Point point2)
```


दो बिंदुओं से एक नया आयत बनाता है। निर्मित आयत को (बाएँ,ऊपर) (दाएँ,नीचे) से कम होने के अनुसार सामान्यीकृत किया जाएगा।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.drawing/point) | पहला बिंदु। |
| point2 | [Point](../../com.aspose.drawing/point) | दूसरा बिंदु। |

**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle) - A newly created rectangle.
### getEmpty() {#getEmpty--}
```
public static Rectangle getEmpty()
```


`Rectangle` संरचना का नया उदाहरण प्राप्त करता है जिसमें `Rectangle.X`, `Rectangle.Y`, `Rectangle.Width` और `Rectangle.Height` मान शून्य पर सेट होते हैं।

**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle)
### getX() {#getX--}
```
public final int getX()
```


इस Rectangle संरचना के ऊपरी-बाएँ कोने का x-निर्देशांक प्राप्त करता है।

**Returns:**
int - इस Rectangle संरचना के ऊपरी-बाएँ कोने का x-निर्देशांक।
### setX(int value) {#setX-int-}
```
public final void setX(int value)
```


इस Rectangle संरचना के ऊपरी-बाएँ कोने का x-निर्देशांक सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int | इस Rectangle संरचना के ऊपरी-बाएँ कोने का x-निर्देशांक। |

### getY() {#getY--}
```
public final int getY()
```


इस Rectangle संरचना के ऊपरी-बाएँ कोने का y-निर्देशांक प्राप्त करता है।

**Returns:**
int - इस Rectangle संरचना के ऊपरी-बाएँ कोने का y-निर्देशांक।
### setY(int value) {#setY-int-}
```
public final void setY(int value)
```


इस Rectangle संरचना के ऊपरी-बाएँ कोने का y-निर्देशांक सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int | इस Rectangle संरचना के ऊपरी-बाएँ कोने का y-निर्देशांक। |

### getLocation() {#getLocation--}
```
public final Point getLocation()
```


इस [Rectangle](../../com.aspose.drawing/rectangle) संरचना के ऊपरी-बाएँ कोने के निर्देशांक प्राप्त करता है।

**Returns:**
[Point](../../com.aspose.drawing/point) - the coordinates of the upper-left corner of this [Rectangle](../../com.aspose.drawing/rectangle) structure.
### setLocation(Point value) {#setLocation-com.aspose.drawing.Point-}
```
public final void setLocation(Point value)
```


इस [Rectangle](../../com.aspose.drawing/rectangle) संरचना के ऊपर-बाएँ कोने के निर्देशांक सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [Point](../../com.aspose.drawing/point) | इस [Rectangle](../../com.aspose.drawing/rectangle) संरचना के ऊपरी-बाएँ कोने के निर्देशांक। |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


इस Rectangle संरचना की चौड़ाई प्राप्त करता है।

**Returns:**
int - इस Rectangle संरचना की चौड़ाई।
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


इस Rectangle संरचना की चौड़ाई सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int | इस Rectangle संरचना की चौड़ाई। |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


इस Rectangle संरचना की ऊँचाई प्राप्त करता है।

**Returns:**
int - इस Rectangle संरचना की ऊँचाई।
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


इस Rectangle संरचना की ऊँचाई सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int | इस Rectangle संरचना की ऊँचाई। |

### getSize() {#getSize--}
```
public final Size getSize()
```


इस [Rectangle](../../com.aspose.drawing/rectangle) का आकार प्राप्त करता है।

**Returns:**
[Size](../../com.aspose.drawing/size) - the size of this [Rectangle](../../com.aspose.drawing/rectangle).
### setSize(Size value) {#setSize-com.aspose.drawing.Size-}
```
public final void setSize(Size value)
```


इस [Rectangle](../../com.aspose.drawing/rectangle) का आकार सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [Size](../../com.aspose.drawing/size) | इस [Rectangle](../../com.aspose.drawing/rectangle) का आकार। |

### getLeft() {#getLeft--}
```
public final int getLeft()
```


इस Rectangle संरचना के बाएँ किनारे का x-निर्देशांक प्राप्त करता है।

**Returns:**
int - इस Rectangle संरचना के बाएँ किनारे का x-निर्देशांक।
### getTop() {#getTop--}
```
public final int getTop()
```


इस Rectangle संरचना के शीर्ष किनारे का y-निर्देशांक प्राप्त करता है।

**Returns:**
int - इस Rectangle संरचना के शीर्ष किनारे का y-निर्देशांक।
### getRight() {#getRight--}
```
public final int getRight()
```


इस Rectangle संरचना के X और Width प्रॉपर्टी मानों के योग के रूप में x-निर्देशांक प्राप्त करता है।

**Returns:**
int - इस Rectangle संरचना के X और Width गुण मानों का योग जो x-निर्देशांक बनाता है।
### getBottom() {#getBottom--}
```
public final int getBottom()
```


इस Rectangle संरचना के Y और Height प्रॉपर्टी मानों के योग के रूप में y-निर्देशांक प्राप्त करता है।

**Returns:**
int - इस Rectangle संरचना के Y और Height गुण मानों का योग जो y-निर्देशांक बनाता है।
### isEmpty() {#isEmpty--}
```
public final boolean isEmpty()
```


एक मान प्राप्त करता है जो दर्शाता है कि इस [Rectangle](../../com.aspose.drawing/rectangle) की सभी संख्यात्मक प्रॉपर्टी का मान शून्य है या नहीं।

**Returns:**
boolean - यह प्रॉपर्टी `true` लौटाती है यदि इस [Rectangle](../../com.aspose.drawing/rectangle) की `Rectangle.Width`, `Rectangle.Height`, `Rectangle.X`, और `Rectangle.Y` प्रॉपर्टी सभी शून्य हों; अन्यथा, `false`.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


परीक्षण करता है कि क्या obj इस [Rectangle](../../com.aspose.drawing/rectangle) संरचना के समान स्थान और आकार वाला [Rectangle](../../com.aspose.drawing/rectangle) संरचना है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | java.lang.Object | परीक्षण करने के लिए ऑब्जेक्ट। |

**Returns:**
boolean - यह मेथड `true` लौटाता है यदि obj एक [Rectangle](../../com.aspose.drawing/rectangle) स्ट्रक्चर है और उसके X, Y, Width, और Height प्रॉपर्टी इस [Rectangle](../../com.aspose.drawing/rectangle) स्ट्रक्चर की संबंधित प्रॉपर्टी के बराबर हैं; अन्यथा, `false`.
### hashCode() {#hashCode--}
```
public int hashCode()
```


इस [Rectangle](../../com.aspose.drawing/rectangle) स्ट्रक्चर के लिए हैश कोड लौटाता है। हैश कोड के उपयोग के बारे में जानकारी के लिए, GetHashCode देखें।

**Returns:**
int - एक पूर्णांक जो इस आयत के हैश कोड को दर्शाता है।
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### intersect(Rectangle rect) {#intersect-com.aspose.drawing.Rectangle-}
```
public final void intersect(Rectangle rect)
```


इस [Rectangle](../../com.aspose.drawing/rectangle) को स्वयं और निर्दिष्ट [Rectangle](../../com.aspose.drawing/rectangle) के प्रतिच्छेदन से बदलता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | वह [Rectangle](../../com.aspose.drawing/rectangle) जिसके साथ प्रतिच्छेदन करना है। |

### inflate(int width, int height) {#inflate-int-int-}
```
public final void inflate(int width, int height)
```


इस [Rectangle](../../com.aspose.drawing/rectangle) को निर्दिष्ट मात्रा से बड़ा करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| width | int | इस [Rectangle](../../com.aspose.drawing/rectangle) को क्षैतिज रूप से फैलाने की मात्रा। |
| height | int | इस [Rectangle](../../com.aspose.drawing/rectangle) को लंबवत रूप से फैलाने की मात्रा। |

### inflate(Size size) {#inflate-com.aspose.drawing.Size-}
```
public final void inflate(Size size)
```


इस [Rectangle](../../com.aspose.drawing/rectangle) को निर्दिष्ट मात्रा से बड़ा करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| size | [Size](../../com.aspose.drawing/size) | इस [Rectangle](../../com.aspose.drawing/rectangle) को फैलाने का आकार। |

### contains(int x, int y) {#contains-int-int-}
```
public final boolean contains(int x, int y)
```


निर्धारित करता है कि निर्दिष्ट बिंदु इस [Rectangle](../../com.aspose.drawing/rectangle) संरचना के भीतर स्थित है या नहीं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | int | जाँचने वाले बिंदु का x-निर्देशांक। |
| y | int | परीक्षण बिंदु का y-निर्देशांक। |

**Returns:**
boolean - यह मेथड `true` लौटाता है यदि `x` और `y` द्वारा परिभाषित बिंदु इस [Rectangle](../../com.aspose.drawing/rectangle) स्ट्रक्चर के भीतर स्थित है; अन्यथा `false`।
### contains(Point pt) {#contains-com.aspose.drawing.Point-}
```
public final boolean contains(Point pt)
```


निर्धारित करता है कि निर्दिष्ट बिंदु इस [Rectangle](../../com.aspose.drawing/rectangle) संरचना के भीतर स्थित है या नहीं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pt | [Point](../../com.aspose.drawing/point) | जाँचने के लिए [Point](../../com.aspose.drawing/point)। |

**Returns:**
boolean - यह मेथड `true` लौटाता है यदि `pt` द्वारा दर्शाया गया बिंदु इस [Rectangle](../../com.aspose.drawing/rectangle) स्ट्रक्चर के भीतर है; अन्यथा `false`।
### contains(Rectangle rect) {#contains-com.aspose.drawing.Rectangle-}
```
public final boolean contains(Rectangle rect)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) |  |

**Returns:**
boolean
### intersectsWith(Rectangle rect) {#intersectsWith-com.aspose.drawing.Rectangle-}
```
public final boolean intersectsWith(Rectangle rect)
```


निर्धारित करता है कि यह आयत `rect` के साथ प्रतिच्छेद करता है या नहीं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | परीक्षण के लिए आयत। |

**Returns:**
boolean - यह मेथड true लौटाता है यदि कोई भी प्रतिच्छेदन है, अन्यथा false।
### offset(int x, int y) {#offset-int-int-}
```
public final void offset(int x, int y)
```


निर्दिष्ट मात्रा से इस आयत का स्थान समायोजित करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | int | क्षैतिज ऑफसेट। |
| y | int | लंबवत ऑफसेट। |

### offset(Point pos) {#offset-com.aspose.drawing.Point-}
```
public final void offset(Point pos)
```


निर्दिष्ट मात्रा से इस आयत का स्थान समायोजित करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pos | [Point](../../com.aspose.drawing/point) | ऑफ़सेट। |

### equals(Rectangle other) {#equals-com.aspose.drawing.Rectangle-}
```
public final boolean equals(Rectangle other)
```


परीक्षण करता है कि क्या अन्य [Rectangle](../../com.aspose.drawing/rectangle) संरचना का स्थान और आकार इस [Rectangle](../../com.aspose.drawing/rectangle) संरचना के समान है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| other | [Rectangle](../../com.aspose.drawing/rectangle) | परीक्षण के लिए अन्य आयत। |

**Returns:**
boolean - यह मेथड `true` लौटाता है यदि अन्य [Rectangle](../../com.aspose.drawing/rectangle) स्ट्रक्चर और उसकी X, Y, Width, और Height प्रॉपर्टी इस [Rectangle](../../com.aspose.drawing/rectangle) स्ट्रक्चर की संबंधित प्रॉपर्टी के बराबर हैं; अन्यथा, `false`।
### CloneTo(Rectangle that) {#CloneTo-com.aspose.drawing.Rectangle-}
```
public void CloneTo(Rectangle that)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| that | [Rectangle](../../com.aspose.drawing/rectangle) |  |

### Clone() {#Clone--}
```
public Rectangle Clone()
```




**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle)
### clone() {#clone--}
```
public Object clone()
```




**Returns:**
java.lang.Object
### normalize() {#normalize--}
```
public void normalize()
```


आयत को सामान्यीकृत करता है, इसकी चौड़ाई और ऊँचाई को सकारात्मक बनाकर, बाएँ को दाएँ से कम और शीर्ष को नीचे से कम करता है।

