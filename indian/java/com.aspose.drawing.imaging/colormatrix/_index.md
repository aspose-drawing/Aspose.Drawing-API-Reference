---
title: ColorMatrix
second_title: Aspose.Drawing for Java API संदर्भ
description: RGBA स्थान के निर्देशांक शामिल करने वाला 5 x 5 मैट्रिक्स परिभाषित करता है।
type: docs
weight: 14
url: /hi/java/com.aspose.drawing.imaging/colormatrix/
---
**Inheritance:**
java.lang.Object
```
public final class ColorMatrix
```

RGBA स्पेस के निर्देशांक शामिल करने वाला 5 x 5 मैट्रिक्स परिभाषित करता है। [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes) क्लास की कई विधियां रंग मैट्रिक्स का उपयोग करके छवि के रंगों को समायोजित करती हैं। इस क्लास को विरासत में नहीं लिया जा सकता।
## निर्माता

| निर्माता | विवरण |
| --- | --- |
| [ColorMatrix()](#ColorMatrix--) | [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) क्लास का नया इंस्टेंस प्रारंभ करता है। |
| [ColorMatrix(float[][] newColorMatrix)](#ColorMatrix-float-----) | [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) क्लास का नया इंस्टेंस निर्दिष्ट मैट्रिक्स `newColorMatrix` के तत्वों का उपयोग करके प्रारंभ करता है। |
## मेथड्स

| विधि | विवरण |
| --- | --- |
| [getMatrix00()](#getMatrix00--) | इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की 0 (शून्य) पंक्ति और 0 कॉलम पर तत्व प्राप्त करता है। |
| [setMatrix00(float value)](#setMatrix00-float-) | इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की 0 (शून्य) पंक्ति और 0 कॉलम पर तत्व सेट करता है। |
| [getMatrix01()](#getMatrix01--) | इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की 0 (शून्य) पंक्ति और प्रथम कॉलम पर तत्व प्राप्त करता है। |
| [setMatrix01(float value)](#setMatrix01-float-) | इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की 0 (शून्य) पंक्ति और प्रथम कॉलम पर तत्व सेट करता है। |
| [getMatrix02()](#getMatrix02--) | इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की 0 (शून्य) पंक्ति और द्वितीय कॉलम पर तत्व प्राप्त करता है। |
| [setMatrix02(float value)](#setMatrix02-float-) | इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की 0 (शून्य) पंक्ति और द्वितीय कॉलम पर तत्व सेट करता है। |
| [getMatrix03()](#getMatrix03--) | इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की 0 (शून्य) पंक्ति और तृतीय कॉलम पर तत्व प्राप्त करता है। |
| [setMatrix03(float value)](#setMatrix03-float-) | इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की 0 (zero) पंक्ति और तीसरे कॉलम में तत्व सेट करता है। |
| [getMatrix04()](#getMatrix04--) | इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की 0 (zero) पंक्ति और चौथे कॉलम में तत्व प्राप्त करता है। |
| [setMatrix04(float value)](#setMatrix04-float-) | इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की 0 (zero) पंक्ति और चौथे कॉलम में तत्व सेट करता है। |
| [getMatrix10()](#getMatrix10--) | इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की पहली पंक्ति और 0 (zero) कॉलम में तत्व प्राप्त करता है। |
| [setMatrix10(float value)](#setMatrix10-float-) | इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की पहली पंक्ति और 0 (zero) कॉलम में तत्व सेट करता है। |
| [getMatrix11()](#getMatrix11--) | इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की पहली पंक्ति और पहले कॉलम में तत्व प्राप्त करता है। |
| [setMatrix11(float value)](#setMatrix11-float-) | इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की पहली पंक्ति और पहले कॉलम में तत्व सेट करता है। |
| [getMatrix12()](#getMatrix12--) | इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की पहली पंक्ति और दूसरे कॉलम में तत्व प्राप्त करता है। |
| [setMatrix12(float value)](#setMatrix12-float-) | इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की पहली पंक्ति और दूसरे कॉलम में तत्व सेट करता है। |
| [getMatrix13()](#getMatrix13--) | इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की पहली पंक्ति और तीसरे कॉलम में तत्व प्राप्त करता है। |
| [setMatrix13(float value)](#setMatrix13-float-) | इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की पहली पंक्ति और तीसरे कॉलम में तत्व सेट करता है। |
| [getMatrix14()](#getMatrix14--) | इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की पहली पंक्ति और चौथे कॉलम में तत्व प्राप्त करता है। |
| [setMatrix14(float value)](#setMatrix14-float-) | इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की पहली पंक्ति और चौथे कॉलम में तत्व सेट करता है। |
| [getMatrix20()](#getMatrix20--) | इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की दूसरी पंक्ति और 0 (zero) कॉलम में तत्व प्राप्त करता है। |
| [setMatrix20(float value)](#setMatrix20-float-) | इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की दूसरी पंक्ति और 0 (zero) कॉलम में तत्व सेट करता है। |
| [getMatrix21()](#getMatrix21--) | इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की दूसरी पंक्ति और पहले कॉलम में तत्व प्राप्त करता है। |
| [setMatrix21(float value)](#setMatrix21-float-) | इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की दूसरी पंक्ति और पहले कॉलम में तत्व सेट करता है। |
| [getMatrix22()](#getMatrix22--) | इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की दूसरी पंक्ति और दूसरे कॉलम में तत्व प्राप्त करता है। |
| [setMatrix22(float value)](#setMatrix22-float-) | इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की दूसरी पंक्ति और दूसरे कॉलम में तत्व सेट करता है। |
| [getMatrix23()](#getMatrix23--) | इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की दूसरी पंक्ति और तीसरे कॉलम में तत्व प्राप्त करता है। |
| [setMatrix23(float value)](#setMatrix23-float-) | इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की दूसरी पंक्ति और तीसरे कॉलम में तत्व सेट करता है। |
| [getMatrix24()](#getMatrix24--) | इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की दूसरी पंक्ति और चौथे कॉलम में तत्व प्राप्त करता है। |
| [setMatrix24(float value)](#setMatrix24-float-) | इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की दूसरी पंक्ति और चौथे कॉलम में तत्व सेट करता है। |
| [getMatrix30()](#getMatrix30--) | इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की तीसरी पंक्ति और 0 (zero) कॉलम में तत्व प्राप्त करता है। |
| [setMatrix30(float value)](#setMatrix30-float-) | इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की तीसरी पंक्ति और 0 (zero) कॉलम में तत्व सेट करता है। |
| [getMatrix31()](#getMatrix31--) | इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की तीसरी पंक्ति और पहले कॉलम में तत्व प्राप्त करता है। |
| [setMatrix31(float value)](#setMatrix31-float-) | इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की तीसरी पंक्ति और पहले कॉलम में तत्व सेट करता है। |
| [getMatrix32()](#getMatrix32--) | इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की तीसरी पंक्ति और दूसरे कॉलम में तत्व प्राप्त करता है। |
| [setMatrix32(float value)](#setMatrix32-float-) | इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की तीसरी पंक्ति और दूसरे कॉलम में तत्व सेट करता है। |
| [getMatrix33()](#getMatrix33--) | इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की तीसरी पंक्ति और तीसरे कॉलम में तत्व प्राप्त करता है। |
| [setMatrix33(float value)](#setMatrix33-float-) | इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की तीसरी पंक्ति और तीसरे कॉलम में तत्व सेट करता है। |
| [getMatrix34()](#getMatrix34--) | इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की तीसरी पंक्ति और चौथे कॉलम में तत्व प्राप्त करता है। |
| [setMatrix34(float value)](#setMatrix34-float-) | इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की तीसरी पंक्ति और चौथे कॉलम में तत्व सेट करता है। |
| [getMatrix40()](#getMatrix40--) | इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की चौथी पंक्ति और 0 (शून्य) कॉलम में तत्व प्राप्त करता है। |
| [setMatrix40(float value)](#setMatrix40-float-) | इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की चौथी पंक्ति और 0 (शून्य) कॉलम में तत्व सेट करता है। |
| [getMatrix41()](#getMatrix41--) | इस `.ColorMatrix` की चौथी पंक्ति और पहले कॉलम में तत्व प्राप्त करता है। |
| [setMatrix41(float value)](#setMatrix41-float-) | इस `.ColorMatrix` की चौथी पंक्ति और पहले कॉलम में तत्व सेट करता है। |
| [getMatrix42()](#getMatrix42--) | इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की चौथी पंक्ति और दूसरे कॉलम में तत्व प्राप्त करता है। |
| [setMatrix42(float value)](#setMatrix42-float-) | इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की चौथी पंक्ति और दूसरे कॉलम में तत्व सेट करता है। |
| [getMatrix43()](#getMatrix43--) | इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की चौथी पंक्ति और तीसरे कॉलम में तत्व प्राप्त करता है। |
| [setMatrix43(float value)](#setMatrix43-float-) | इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की चौथी पंक्ति और तीसरे कॉलम में तत्व सेट करता है। |
| [getMatrix44()](#getMatrix44--) | इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की चौथी पंक्ति और चौथे कॉलम में तत्व प्राप्त करता है। |
| [setMatrix44(float value)](#setMatrix44-float-) | इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की चौथी पंक्ति और चौथे कॉलम में तत्व सेट करता है। |
| [get_Item(int row, int column)](#get-Item-int-int-) | निर्दिष्ट पंक्ति और कॉलम में तत्व को [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) में प्राप्त करता है। |
| [set_Item(int row, int column, float value)](#set-Item-int-int-float-) | निर्दिष्ट पंक्ति और कॉलम में तत्व को [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) में सेट करता है। |
### ColorMatrix() {#ColorMatrix--}
```
public ColorMatrix()
```


[ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) क्लास का नया इंस्टेंस प्रारंभ करता है।

### ColorMatrix(float[][] newColorMatrix) {#ColorMatrix-float-----}
```
public ColorMatrix(float[][] newColorMatrix)
```


[ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) क्लास का नया इंस्टेंस निर्दिष्ट मैट्रिक्स `newColorMatrix` के तत्वों का उपयोग करके प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| newColorMatrix | float[][] | नए [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) के तत्वों के मान। |

### getMatrix00() {#getMatrix00--}
```
public float getMatrix00()
```


इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की 0 (शून्य) पंक्ति और 0 कॉलम पर तत्व प्राप्त करता है।

**Returns:**
float - इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की 0 (शून्य) पंक्ति और 0 कॉलम में तत्व।
### setMatrix00(float value) {#setMatrix00-float-}
```
public void setMatrix00(float value)
```


इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की 0 (शून्य) पंक्ति और 0 कॉलम पर तत्व सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float | इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की 0 (शून्य) पंक्ति और 0 कॉलम में तत्व। |

### getMatrix01() {#getMatrix01--}
```
public float getMatrix01()
```


इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की 0 (शून्य) पंक्ति और प्रथम कॉलम पर तत्व प्राप्त करता है।

**Returns:**
float - इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की 0 (शून्य) पंक्ति और पहले कॉलम में तत्व।
### setMatrix01(float value) {#setMatrix01-float-}
```
public void setMatrix01(float value)
```


इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की 0 (शून्य) पंक्ति और प्रथम कॉलम पर तत्व सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float | इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की 0 (शून्य) पंक्ति और पहले कॉलम में तत्व। |

### getMatrix02() {#getMatrix02--}
```
public float getMatrix02()
```


इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की 0 (शून्य) पंक्ति और द्वितीय कॉलम पर तत्व प्राप्त करता है।

**Returns:**
float - इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की 0 (शून्य) पंक्ति और दूसरे कॉलम में तत्व।
### setMatrix02(float value) {#setMatrix02-float-}
```
public void setMatrix02(float value)
```


इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की 0 (शून्य) पंक्ति और द्वितीय कॉलम पर तत्व सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float | इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की 0 (शून्य) पंक्ति और दूसरे कॉलम में तत्व। |

### getMatrix03() {#getMatrix03--}
```
public float getMatrix03()
```


इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की 0 (शून्य) पंक्ति और तृतीय कॉलम पर तत्व प्राप्त करता है।

**Returns:**
float - इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की 0 (शून्य) पंक्ति और तीसरे कॉलम में तत्व।
### setMatrix03(float value) {#setMatrix03-float-}
```
public void setMatrix03(float value)
```


इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की 0 (zero) पंक्ति और तीसरे कॉलम में तत्व सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float | इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की 0 (शून्य) पंक्ति और तीसरे कॉलम में तत्व। |

### getMatrix04() {#getMatrix04--}
```
public float getMatrix04()
```


इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की 0 (zero) पंक्ति और चौथे कॉलम में तत्व प्राप्त करता है।

**Returns:**
float - इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की 0 (शून्य) पंक्ति और चौथे कॉलम में तत्व।
### setMatrix04(float value) {#setMatrix04-float-}
```
public void setMatrix04(float value)
```


इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की 0 (zero) पंक्ति और चौथे कॉलम में तत्व सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float | इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की 0 (शून्य) पंक्ति और चौथे कॉलम में तत्व। |

### getMatrix10() {#getMatrix10--}
```
public float getMatrix10()
```


इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की पहली पंक्ति और 0 (zero) कॉलम में तत्व प्राप्त करता है।

**Returns:**
float - इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की पहली पंक्ति और 0 (शून्य) कॉलम में तत्व।
### setMatrix10(float value) {#setMatrix10-float-}
```
public void setMatrix10(float value)
```


इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की पहली पंक्ति और 0 (zero) कॉलम में तत्व सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float | इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की पहली पंक्ति और 0 (शून्य) कॉलम में तत्व। |

### getMatrix11() {#getMatrix11--}
```
public float getMatrix11()
```


इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की पहली पंक्ति और पहले कॉलम में तत्व प्राप्त करता है।

**Returns:**
float - इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की पहली पंक्ति और पहले कॉलम में तत्व।
### setMatrix11(float value) {#setMatrix11-float-}
```
public void setMatrix11(float value)
```


इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की पहली पंक्ति और पहले कॉलम में तत्व सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float | इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की पहली पंक्ति और पहले कॉलम में तत्व। |

### getMatrix12() {#getMatrix12--}
```
public float getMatrix12()
```


इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की पहली पंक्ति और दूसरे कॉलम में तत्व प्राप्त करता है।

**Returns:**
float - इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की पहली पंक्ति और दूसरे कॉलम में तत्व।
### setMatrix12(float value) {#setMatrix12-float-}
```
public void setMatrix12(float value)
```


इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की पहली पंक्ति और दूसरे कॉलम में तत्व सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float | इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की पहली पंक्ति और दूसरे कॉलम में तत्व। |

### getMatrix13() {#getMatrix13--}
```
public float getMatrix13()
```


इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की पहली पंक्ति और तीसरे कॉलम में तत्व प्राप्त करता है।

**Returns:**
float - इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की पहली पंक्ति और तीसरे कॉलम में तत्व।
### setMatrix13(float value) {#setMatrix13-float-}
```
public void setMatrix13(float value)
```


इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की पहली पंक्ति और तीसरे कॉलम में तत्व सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float | इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की पहली पंक्ति और तीसरे कॉलम में तत्व। |

### getMatrix14() {#getMatrix14--}
```
public float getMatrix14()
```


इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की पहली पंक्ति और चौथे कॉलम में तत्व प्राप्त करता है।

**Returns:**
float - इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की पहली पंक्ति और चौथे कॉलम में तत्व।
### setMatrix14(float value) {#setMatrix14-float-}
```
public void setMatrix14(float value)
```


इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की पहली पंक्ति और चौथे कॉलम में तत्व सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float | इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की पहली पंक्ति और चौथे कॉलम में तत्व। |

### getMatrix20() {#getMatrix20--}
```
public float getMatrix20()
```


इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की दूसरी पंक्ति और 0 (zero) कॉलम में तत्व प्राप्त करता है।

**Returns:**
float - इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की दूसरी पंक्ति और 0 (शून्य) कॉलम में तत्व।
### setMatrix20(float value) {#setMatrix20-float-}
```
public void setMatrix20(float value)
```


इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की दूसरी पंक्ति और 0 (zero) कॉलम में तत्व सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float | इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की दूसरी पंक्ति और 0 (शून्य) कॉलम में तत्व। |

### getMatrix21() {#getMatrix21--}
```
public float getMatrix21()
```


इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की दूसरी पंक्ति और पहले कॉलम में तत्व प्राप्त करता है।

**Returns:**
float - इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की दूसरी पंक्ति और पहले कॉलम में तत्व।
### setMatrix21(float value) {#setMatrix21-float-}
```
public void setMatrix21(float value)
```


इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की दूसरी पंक्ति और पहले कॉलम में तत्व सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float | इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की दूसरी पंक्ति और पहले कॉलम में तत्व। |

### getMatrix22() {#getMatrix22--}
```
public float getMatrix22()
```


इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की दूसरी पंक्ति और दूसरे कॉलम में तत्व प्राप्त करता है।

**Returns:**
float - इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की दूसरी पंक्ति और दूसरे कॉलम में तत्व।
### setMatrix22(float value) {#setMatrix22-float-}
```
public void setMatrix22(float value)
```


इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की दूसरी पंक्ति और दूसरे कॉलम में तत्व सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float | इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की दूसरी पंक्ति और दूसरे कॉलम में तत्व। |

### getMatrix23() {#getMatrix23--}
```
public float getMatrix23()
```


इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की दूसरी पंक्ति और तीसरे कॉलम में तत्व प्राप्त करता है।

**Returns:**
float - इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की दूसरी पंक्ति और तीसरे कॉलम में तत्व।
### setMatrix23(float value) {#setMatrix23-float-}
```
public void setMatrix23(float value)
```


इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की दूसरी पंक्ति और तीसरे कॉलम में तत्व सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float | इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की दूसरी पंक्ति और तीसरे कॉलम में तत्व। |

### getMatrix24() {#getMatrix24--}
```
public float getMatrix24()
```


इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की दूसरी पंक्ति और चौथे कॉलम में तत्व प्राप्त करता है।

**Returns:**
float - इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की दूसरी पंक्ति और चौथे कॉलम में तत्व।
### setMatrix24(float value) {#setMatrix24-float-}
```
public void setMatrix24(float value)
```


इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की दूसरी पंक्ति और चौथे कॉलम में तत्व सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float | इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की दूसरी पंक्ति और चौथे कॉलम में तत्व। |

### getMatrix30() {#getMatrix30--}
```
public float getMatrix30()
```


इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की तीसरी पंक्ति और 0 (zero) कॉलम में तत्व प्राप्त करता है।

**Returns:**
float - इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की तीसरी पंक्ति और 0 (शून्य) कॉलम में तत्व।
### setMatrix30(float value) {#setMatrix30-float-}
```
public void setMatrix30(float value)
```


इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की तीसरी पंक्ति और 0 (zero) कॉलम में तत्व सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float | इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की तीसरी पंक्ति और 0 (शून्य) कॉलम में तत्व। |

### getMatrix31() {#getMatrix31--}
```
public float getMatrix31()
```


इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की तीसरी पंक्ति और पहले कॉलम में तत्व प्राप्त करता है।

**Returns:**
float - इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की तीसरी पंक्ति और पहले कॉलम में तत्व।
### setMatrix31(float value) {#setMatrix31-float-}
```
public void setMatrix31(float value)
```


इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की तीसरी पंक्ति और पहले कॉलम में तत्व सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float | इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की तीसरी पंक्ति और पहले कॉलम में तत्व। |

### getMatrix32() {#getMatrix32--}
```
public float getMatrix32()
```


इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की तीसरी पंक्ति और दूसरे कॉलम में तत्व प्राप्त करता है।

**Returns:**
float - इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की तीसरी पंक्ति और दूसरे कॉलम में तत्व।
### setMatrix32(float value) {#setMatrix32-float-}
```
public void setMatrix32(float value)
```


इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की तीसरी पंक्ति और दूसरे कॉलम में तत्व सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float | इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की तीसरी पंक्ति और दूसरे कॉलम में तत्व। |

### getMatrix33() {#getMatrix33--}
```
public float getMatrix33()
```


इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की तीसरी पंक्ति और तीसरे कॉलम में तत्व प्राप्त करता है।

**Returns:**
float - इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की तीसरी पंक्ति और तीसरे कॉलम में तत्व।
### setMatrix33(float value) {#setMatrix33-float-}
```
public void setMatrix33(float value)
```


इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की तीसरी पंक्ति और तीसरे कॉलम में तत्व सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float | इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की तीसरी पंक्ति और तीसरे कॉलम में तत्व। |

### getMatrix34() {#getMatrix34--}
```
public float getMatrix34()
```


इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की तीसरी पंक्ति और चौथे कॉलम में तत्व प्राप्त करता है।

**Returns:**
float - इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की तीसरी पंक्ति और चौथे कॉलम में तत्व।
### setMatrix34(float value) {#setMatrix34-float-}
```
public void setMatrix34(float value)
```


इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की तीसरी पंक्ति और चौथे कॉलम में तत्व सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float | इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की तीसरी पंक्ति और चौथे कॉलम में तत्व। |

### getMatrix40() {#getMatrix40--}
```
public float getMatrix40()
```


इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की चौथी पंक्ति और 0 (शून्य) कॉलम में तत्व प्राप्त करता है।

**Returns:**
float - इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की चौथी पंक्ति और 0 (शून्य) कॉलम में तत्व।
### setMatrix40(float value) {#setMatrix40-float-}
```
public void setMatrix40(float value)
```


इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की चौथी पंक्ति और 0 (शून्य) कॉलम में तत्व सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float | इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की चौथी पंक्ति और 0 (शून्य) कॉलम में तत्व। |

### getMatrix41() {#getMatrix41--}
```
public float getMatrix41()
```


इस `.ColorMatrix` की चौथी पंक्ति और पहले कॉलम में तत्व प्राप्त करता है।

**Returns:**
float - इस `.ColorMatrix` की चौथी पंक्ति और पहले कॉलम में तत्व।
### setMatrix41(float value) {#setMatrix41-float-}
```
public void setMatrix41(float value)
```


इस `.ColorMatrix` की चौथी पंक्ति और पहले कॉलम में तत्व सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | फ़्लोट | इस `.ColorMatrix` की चौथी पंक्ति और पहले कॉलम में तत्व। |

### getMatrix42() {#getMatrix42--}
```
public float getMatrix42()
```


इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की चौथी पंक्ति और दूसरे कॉलम में तत्व प्राप्त करता है।

**Returns:**
float - इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की चौथी पंक्ति और दूसरे कॉलम में तत्व।
### setMatrix42(float value) {#setMatrix42-float-}
```
public void setMatrix42(float value)
```


इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की चौथी पंक्ति और दूसरे कॉलम में तत्व सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float | इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की चौथी पंक्ति और दूसरे कॉलम में तत्व। |

### getMatrix43() {#getMatrix43--}
```
public float getMatrix43()
```


इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की चौथी पंक्ति और तीसरे कॉलम में तत्व प्राप्त करता है।

**Returns:**
float - इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की चौथी पंक्ति और तीसरे कॉलम में तत्व।
### setMatrix43(float value) {#setMatrix43-float-}
```
public void setMatrix43(float value)
```


इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की चौथी पंक्ति और तीसरे कॉलम में तत्व सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float | इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की चौथी पंक्ति और तीसरे कॉलम में तत्व। |

### getMatrix44() {#getMatrix44--}
```
public float getMatrix44()
```


इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की चौथी पंक्ति और चौथे कॉलम में तत्व प्राप्त करता है।

**Returns:**
float - इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की चौथी पंक्ति और चौथे कॉलम में तत्व।
### setMatrix44(float value) {#setMatrix44-float-}
```
public void setMatrix44(float value)
```


इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की चौथी पंक्ति और चौथे कॉलम में तत्व सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float | इस [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) की चौथी पंक्ति और चौथे कॉलम में तत्व। |

### get_Item(int row, int column) {#get-Item-int-int-}
```
public float get_Item(int row, int column)
```


निर्दिष्ट पंक्ति और कॉलम में तत्व को [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) में प्राप्त करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| पंक्ति | int | तत्व की पंक्ति। |
| कॉलम | int | तत्व का कॉलम। |

**Returns:**
float - निर्दिष्ट पंक्ति और स्तंभ में तत्व।
### set_Item(int row, int column, float value) {#set-Item-int-int-float-}
```
public void set_Item(int row, int column, float value)
```


निर्दिष्ट पंक्ति और कॉलम में तत्व को [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) में सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| पंक्ति | int | तत्व की पंक्ति। |
| कॉलम | int | तत्व का कॉलम। |
| value | float | निर्दिष्ट पंक्ति और स्तंभ में तत्व [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

