---
title: CustomLineCap
second_title: Aspose.Drawing for Java API संदर्भ
description: एक कस्टम उपयोगकर्ता-परिभाषित लाइन कैप को संलग्न करता है।
type: docs
weight: 17
url: /hi/java/com.aspose.drawing.drawing2d/customlinecap/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public class CustomLineCap implements System.IDisposable
```

एक कस्टम उपयोगकर्ता-परिभाषित लाइन कैप को संलग्न करता है।
## निर्माता

| निर्माता | विवरण |
| --- | --- |
| [CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath)](#CustomLineCap-com.aspose.drawing.drawing2d.GraphicsPath-com.aspose.drawing.drawing2d.GraphicsPath-) | निर्दिष्ट रूपरेखा और भराव के साथ [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) वर्ग का नया उदाहरण प्रारंभ करता है। |
| [CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap)](#CustomLineCap-com.aspose.drawing.drawing2d.GraphicsPath-com.aspose.drawing.drawing2d.GraphicsPath-int-) | निर्दिष्ट रूपरेखा और भराव के साथ निर्दिष्ट मौजूदा [LineCap](../../com.aspose.drawing.drawing2d/linecap) enumeration से [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) वर्ग का नया उदाहरण प्रारंभ करता है। |
| [CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap, float baseInset)](#CustomLineCap-com.aspose.drawing.drawing2d.GraphicsPath-com.aspose.drawing.drawing2d.GraphicsPath-int-float-) | निर्दिष्ट रूपरेखा, भराव और इनसेट के साथ निर्दिष्ट मौजूदा [LineCap](../../com.aspose.drawing.drawing2d/linecap) enumeration से [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) वर्ग का नया उदाहरण प्रारंभ करता है। |
## मेथड्स

| विधि | विवरण |
| --- | --- |
| [getStrokeJoin()](#getStrokeJoin--) | इस [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) वस्तु को बनाते हुए रेखाओं के जुड़ने के तरीके को निर्धारित करने वाले [LineJoin](../../com.aspose.drawing.drawing2d/linejoin) enumeration को प्राप्त करता है या सेट करता है। |
| [setStrokeJoin(int value)](#setStrokeJoin-int-) | इस [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) वस्तु को बनाते हुए रेखाओं के जुड़ने के तरीके को निर्धारित करने वाले [LineJoin](../../com.aspose.drawing.drawing2d/linejoin) enumeration को प्राप्त करता है या सेट करता है। |
| [getBaseCap()](#getBaseCap--) | इस [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) के आधार पर रहने वाले [LineCap](../../com.aspose.drawing.drawing2d/linecap) enumeration को प्राप्त करता है या सेट करता है। |
| [setBaseCap(int value)](#setBaseCap-int-) | इस [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) के आधार पर रहने वाले [LineCap](../../com.aspose.drawing.drawing2d/linecap) enumeration को प्राप्त करता है या सेट करता है। |
| [getBaseInset()](#getBaseInset--) | कैप और रेखा के बीच की दूरी को प्राप्त करता है या सेट करता है। |
| [setBaseInset(float value)](#setBaseInset-float-) | कैप और रेखा के बीच की दूरी को प्राप्त करता है या सेट करता है। |
| [getWidthScale()](#getWidthScale--) | इस [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) क्लास वस्तु को [Pen](../../com.aspose.drawing/pen) वस्तु की चौड़ाई के सापेक्ष स्केल करने की मात्रा को प्राप्त करता है या सेट करता है। |
| [setWidthScale(float value)](#setWidthScale-float-) | इस [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) क्लास वस्तु को [Pen](../../com.aspose.drawing/pen) वस्तु की चौड़ाई के सापेक्ष स्केल करने की मात्रा को प्राप्त करता है या सेट करता है। |
| [dispose()](#dispose--) | इस [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) वस्तु द्वारा उपयोग किए गए सभी संसाधनों को मुक्त करता है। |
| [deepClone()](#deepClone--) | इस [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) की एक सटीक प्रति बनाता है। |
| [setStrokeCaps(int startCap, int endCap)](#setStrokeCaps-int-int-) | इस कस्टम कैप को बनाने वाली लाइनों की शुरुआत और अंत में उपयोग किए जाने वाले कैप सेट करता है। |
| [getStrokeCaps(int[] startCap, int[] endCap)](#getStrokeCaps-int---int---) | इस कस्टम कैप को बनाने वाली लाइनों की शुरुआत और अंत में उपयोग किए जाने वाले कैप प्राप्त करता है। |
| [getFillPath()](#getFillPath--) |  |
| [getStrokePath()](#getStrokePath--) | कस्टम कैप की रूपरेखा को परिभाषित करने वाले ऑब्जेक्ट को प्राप्त करता है। |
### CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath) {#CustomLineCap-com.aspose.drawing.drawing2d.GraphicsPath-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath)
```


निर्दिष्ट रूपरेखा और भराव के साथ [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) वर्ग का नया उदाहरण प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fillPath | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | एक [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) ऑब्जेक्ट जो कस्टम कैप के भराव को परिभाषित करता है। |
| strokePath | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | एक [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) ऑब्जेक्ट जो कस्टम कैप की रूपरेखा को परिभाषित करता है। |

### CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap) {#CustomLineCap-com.aspose.drawing.drawing2d.GraphicsPath-com.aspose.drawing.drawing2d.GraphicsPath-int-}
```
public CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap)
```


निर्दिष्ट रूपरेखा और भराव के साथ निर्दिष्ट मौजूदा [LineCap](../../com.aspose.drawing.drawing2d/linecap) enumeration से [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) वर्ग का नया उदाहरण प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fillPath | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | एक [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) ऑब्जेक्ट जो कस्टम कैप के भराव को परिभाषित करता है। |
| strokePath | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | एक [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) ऑब्जेक्ट जो कस्टम कैप की रूपरेखा को परिभाषित करता है। |
| baseCap | int | वह लाइन कैप जिससे कस्टम कैप बनाया जाता है। |

### CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap, float baseInset) {#CustomLineCap-com.aspose.drawing.drawing2d.GraphicsPath-com.aspose.drawing.drawing2d.GraphicsPath-int-float-}
```
public CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap, float baseInset)
```


निर्दिष्ट रूपरेखा, भराव और इनसेट के साथ निर्दिष्ट मौजूदा [LineCap](../../com.aspose.drawing.drawing2d/linecap) enumeration से [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) वर्ग का नया उदाहरण प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fillPath | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | एक [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) ऑब्जेक्ट जो कस्टम कैप के भराव को परिभाषित करता है। |
| strokePath | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | एक [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) ऑब्जेक्ट जो कस्टम कैप की रूपरेखा को परिभाषित करता है। |
| baseCap | int | वह लाइन कैप जिससे कस्टम कैप बनाया जाता है। |
| baseInset | फ़्लोट | कैप और लाइन के बीच की दूरी। |

### getStrokeJoin() {#getStrokeJoin--}
```
public final int getStrokeJoin()
```


इस [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) वस्तु को बनाते हुए रेखाओं के जुड़ने के तरीके को निर्धारित करने वाले [LineJoin](../../com.aspose.drawing.drawing2d/linejoin) enumeration को प्राप्त करता है या सेट करता है।

**Returns:**
int
### setStrokeJoin(int value) {#setStrokeJoin-int-}
```
public final void setStrokeJoin(int value)
```


इस [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) वस्तु को बनाते हुए रेखाओं के जुड़ने के तरीके को निर्धारित करने वाले [LineJoin](../../com.aspose.drawing.drawing2d/linejoin) enumeration को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getBaseCap() {#getBaseCap--}
```
public final int getBaseCap()
```


इस [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) के आधार पर रहने वाले [LineCap](../../com.aspose.drawing.drawing2d/linecap) enumeration को प्राप्त करता है या सेट करता है।

**Returns:**
int
### setBaseCap(int value) {#setBaseCap-int-}
```
public final void setBaseCap(int value)
```


इस [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) के आधार पर रहने वाले [LineCap](../../com.aspose.drawing.drawing2d/linecap) enumeration को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getBaseInset() {#getBaseInset--}
```
public final float getBaseInset()
```


कैप और रेखा के बीच की दूरी को प्राप्त करता है या सेट करता है।

**Returns:**
फ़्लोट
### setBaseInset(float value) {#setBaseInset-float-}
```
public final void setBaseInset(float value)
```


कैप और रेखा के बीच की दूरी को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | फ़्लोट |  |

### getWidthScale() {#getWidthScale--}
```
public final float getWidthScale()
```


इस [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) क्लास वस्तु को [Pen](../../com.aspose.drawing/pen) वस्तु की चौड़ाई के सापेक्ष स्केल करने की मात्रा को प्राप्त करता है या सेट करता है।

**Returns:**
फ़्लोट
### setWidthScale(float value) {#setWidthScale-float-}
```
public final void setWidthScale(float value)
```


इस [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) क्लास वस्तु को [Pen](../../com.aspose.drawing/pen) वस्तु की चौड़ाई के सापेक्ष स्केल करने की मात्रा को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | फ़्लोट |  |

### dispose() {#dispose--}
```
public final void dispose()
```


इस [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) वस्तु द्वारा उपयोग किए गए सभी संसाधनों को मुक्त करता है।

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


इस [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) की एक सटीक प्रति बनाता है।

**Returns:**
java.lang.Object - वह [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) जिसे यह मेथड बनाता है, ऑब्जेक्ट के रूप में कास्ट किया गया।
### setStrokeCaps(int startCap, int endCap) {#setStrokeCaps-int-int-}
```
public final void setStrokeCaps(int startCap, int endCap)
```


इस कस्टम कैप को बनाने वाली लाइनों की शुरुआत और अंत में उपयोग किए जाने वाले कैप सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| startCap | int | यह कैप के भीतर लाइन की शुरुआत में उपयोग किया जाने वाला [LineCap](../../com.aspose.drawing.drawing2d/linecap) एनेमरेशन। |
| endCap | int | यह कैप के भीतर लाइन के अंत में उपयोग किया जाने वाला [LineCap](../../com.aspose.drawing.drawing2d/linecap) एनेमरेशन। |

### getStrokeCaps(int[] startCap, int[] endCap) {#getStrokeCaps-int---int---}
```
public final void getStrokeCaps(int[] startCap, int[] endCap)
```


इस कस्टम कैप को बनाने वाली लाइनों की शुरुआत और अंत में उपयोग किए जाने वाले कैप प्राप्त करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| startCap | int[] | यह कैप के भीतर लाइन की शुरुआत में उपयोग किया जाने वाला [LineCap](../../com.aspose.drawing.drawing2d/linecap) एनेमरेशन। |
| endCap | int[] | यह कैप के भीतर लाइन के अंत में उपयोग किया जाने वाला [LineCap](../../com.aspose.drawing.drawing2d/linecap) एनेमरेशन। |

### getFillPath() {#getFillPath--}
```
public GraphicsPath getFillPath()
```




**Returns:**
[GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath)
### getStrokePath() {#getStrokePath--}
```
public GraphicsPath getStrokePath()
```


कस्टम कैप की रूपरेखा को परिभाषित करने वाले ऑब्जेक्ट को प्राप्त करता है।

**Returns:**
[GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) - The object that defines the outline of the custom cap.
