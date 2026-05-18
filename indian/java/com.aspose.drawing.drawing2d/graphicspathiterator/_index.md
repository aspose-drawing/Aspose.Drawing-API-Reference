---
title: GraphicsPathIterator
second_title: Aspose.Drawing for Java API संदर्भ
description: एक GraphicsPath में सबपाथ्स के माध्यम से इटरेट करने और प्रत्येक सबपाथ में मौजूद आकारों के प्रकार का परीक्षण करने की क्षमता प्रदान करता है।
type: docs
weight: 24
url: /hi/java/com.aspose.drawing.drawing2d/graphicspathiterator/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public final class GraphicsPathIterator implements System.IDisposable
```

एक [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) के उपमार्गों के माध्यम से पुनरावृत्ति करने और प्रत्येक उपमार्ग में शामिल आकृतियों के प्रकारों का परीक्षण करने की क्षमता प्रदान करता है। इस वर्ग को विरासत में नहीं लिया जा सकता है।
## निर्माता

| निर्माता | विवरण |
| --- | --- |
| [GraphicsPathIterator(GraphicsPath path)](#GraphicsPathIterator-com.aspose.drawing.drawing2d.GraphicsPath-) | [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) वर्ग का एक नया उदाहरण प्रारंभ करता है। |
## मेथड्स

| विधि | विवरण |
| --- | --- |
| [getCount()](#getCount--) | पथ में बिंदुओं की संख्या प्राप्त करता है। |
| [getSubpathCount()](#getSubpathCount--) | पथ में उपमार्गों की संख्या प्राप्त करता है। |
| [dispose()](#dispose--) | अनुप्रयोग-परिभाषित कार्यों को निष्पादित करता है जो अनप्रबंधित संसाधनों को मुक्त करने, रिलीज़ करने या रीसेट करने से संबंधित हैं। |
| [copyData(PointF[][] points, byte[][] types, int startIndex, int endIndex)](#copyData-com.aspose.drawing.PointF-----byte-----int-int-) | संबंधित [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) की GraphicsPath.PathPoints प्रॉपर्टी और GraphicsPath.PathTypes प्रॉपर्टी एरे को दो निर्दिष्ट एरे में कॉपी करता है। |
| [enumerate(PointF[][] points, byte[][] types)](#enumerate-com.aspose.drawing.PointF-----byte-----) | संबंधित [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) की GraphicsPath.PathPoints प्रॉपर्टी और GraphicsPath.PathTypes प्रॉपर्टी एरे को दो निर्दिष्ट एरे में कॉपी करता है। |
| [hasCurve()](#hasCurve--) | यह दर्शाता है कि इस [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) से जुड़ा पथ एक वक्र शामिल करता है या नहीं। |
| [nextMarker(int[] startIndex, int[] endIndex)](#nextMarker-int---int---) | [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) को पथ में अगले मार्कर पर बढ़ाता है और [out] पैरामीटर के माध्यम से प्रारंभ और समाप्ति सूचकांक लौटाता है। |
| [nextMarker(GraphicsPath path)](#nextMarker-com.aspose.drawing.drawing2d.GraphicsPath-) | यह [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) ऑब्जेक्ट एक [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) ऑब्जेक्ट से जुड़ा हुआ है। |
| [nextPathType(byte[] pathType, int[] startIndex, int[] endIndex)](#nextPathType-byte---int---int---) | सभी समान प्रकार के अगले डेटा बिंदुओं के समूह के प्रारंभिक और समाप्ति सूचकांक प्राप्त करता है। |
| [nextSubpath(int[] startIndex, int[] endIndex, boolean[] isClosed)](#nextSubpath-int---int---boolean---) | [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) को पथ में अगले उपमार्ग पर ले जाता है। |
| [nextSubpath(GraphicsPath path, boolean[] isClosed)](#nextSubpath-com.aspose.drawing.drawing2d.GraphicsPath-boolean---) | इस [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) के संबंधित पथ से अगला आकृति (उपमार्ग) प्राप्त करता है। |
| [rewind()](#rewind--) | इस [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) को उसके संबंधित पथ की शुरुआत पर रीवाइंड करता है। |
### GraphicsPathIterator(GraphicsPath path) {#GraphicsPathIterator-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public GraphicsPathIterator(GraphicsPath path)
```


[GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) वर्ग का एक नया उदाहरण प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | वह [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) ऑब्जेक्ट जिसके लिए इस सहायक वर्ग को प्रारंभ किया जाना है। |

### getCount() {#getCount--}
```
public int getCount()
```


पथ में बिंदुओं की संख्या प्राप्त करता है।

**Returns:**
int - पथ में बिंदुओं की संख्या।
### getSubpathCount() {#getSubpathCount--}
```
public int getSubpathCount()
```


पथ में उपमार्गों की संख्या प्राप्त करता है।

**Returns:**
int - पथ में उपमार्गों की संख्या।
### dispose() {#dispose--}
```
public void dispose()
```


अनुप्रयोग-परिभाषित कार्यों को निष्पादित करता है जो अनप्रबंधित संसाधनों को मुक्त करने, रिलीज़ करने या रीसेट करने से संबंधित हैं।

### copyData(PointF[][] points, byte[][] types, int startIndex, int endIndex) {#copyData-com.aspose.drawing.PointF-----byte-----int-int-}
```
public int copyData(PointF[][] points, byte[][] types, int startIndex, int endIndex)
```


संबंधित [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) की GraphicsPath.PathPoints प्रॉपर्टी और GraphicsPath.PathTypes प्रॉपर्टी एरे को दो निर्दिष्ट एरे में कॉपी करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.drawing/pointf) | रिटर्न पर, यह System.Drawing.PointF संरचनाओं की एक एरे रखता है जो पथ में बिंदुओं का प्रतिनिधित्व करती है। |
| प्रकार | byte[][] | रिटर्न पर, यह बाइट्स की एक एरे रखता है जो पथ में बिंदुओं के प्रकारों का प्रतिनिधित्व करती है। |
| startIndex | int | एरे के प्रारंभिक सूचकांक को निर्दिष्ट करता है। |
| endIndex | int | एरे के समाप्ति सूचकांक को निर्दिष्ट करता है। |

**Returns:**
int - कॉपी किए गए बिंदुओं की संख्या।
### enumerate(PointF[][] points, byte[][] types) {#enumerate-com.aspose.drawing.PointF-----byte-----}
```
public int enumerate(PointF[][] points, byte[][] types)
```


संबंधित [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) की GraphicsPath.PathPoints प्रॉपर्टी और GraphicsPath.PathTypes प्रॉपर्टी एरे को दो निर्दिष्ट एरे में कॉपी करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.drawing/pointf) | रिटर्न पर, यह System.Drawing.PointF संरचनाओं की एक एरे रखता है जो पथ में बिंदुओं का प्रतिनिधित्व करती है। |
| प्रकार | byte[][] | रिटर्न पर, यह बाइट्स की एक एरे रखता है जो पथ में बिंदुओं के प्रकारों का प्रतिनिधित्व करती है। |

**Returns:**
int - कॉपी किए गए बिंदुओं की संख्या।
### hasCurve() {#hasCurve--}
```
public boolean hasCurve()
```


यह दर्शाता है कि इस [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) से जुड़ा पथ एक वक्र शामिल करता है या नहीं।

**Returns:**
boolean - यह विधि true लौटाती है यदि वर्तमान उपपथ में एक वक्र है; अन्यथा false.
### nextMarker(int[] startIndex, int[] endIndex) {#nextMarker-int---int---}
```
public int nextMarker(int[] startIndex, int[] endIndex)
```


[GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) को पथ में अगले मार्कर पर बढ़ाता है और [out] पैरामीटर के माध्यम से प्रारंभ और समाप्ति सूचकांक लौटाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| startIndex | int[] | [out] यह पैरामीटर को प्रदान किया गया पूर्णांक संदर्भ उस बिंदु का सूचकांक प्राप्त करता है जो एक उपपथ की शुरुआत करता है। |
| endIndex | int[] | [out] यह पैरामीटर को प्रदान किया गया पूर्णांक संदर्भ उस बिंदु का सूचकांक प्राप्त करता है जो उस उपपथ को समाप्त करता है, जिसका प्रारंभिक सूचकांक startIndex द्वारा दर्शाया गया है। |

**Returns:**
int - इस मार्कर और अगले के बीच बिंदुओं की संख्या।
### nextMarker(GraphicsPath path) {#nextMarker-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public int nextMarker(GraphicsPath path)
```


यह [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) वस्तु के साथ एक [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) वस्तु जुड़ी हुई है। यह विधि जुड़े हुए [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) को उसके पथ में अगले मार्कर तक बढ़ाती है और वर्तमान मार्कर और अगले मार्कर (या पथ के अंत) के बीच स्थित सभी बिंदुओं को दूसरे [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) वस्तु में कॉपी करती है जो पैरामीटर के रूप में पास किया गया है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | वह [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) वस्तु जिसमें बिंदु कॉपी किए जाएंगे। |

**Returns:**
int - इस मार्कर और अगले के बीच बिंदुओं की संख्या।
### nextPathType(byte[] pathType, int[] startIndex, int[] endIndex) {#nextPathType-byte---int---int---}
```
public int nextPathType(byte[] pathType, int[] startIndex, int[] endIndex)
```


सभी समान प्रकार के अगले डेटा बिंदुओं के समूह के प्रारंभिक और समाप्ति सूचकांक प्राप्त करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pathType | byte[] | [out] समूह में सभी बिंदुओं द्वारा साझा किए गए बिंदु प्रकार को प्राप्त करता है। संभावित प्रकार [PathPointType](../../com.aspose.drawing.drawing2d/pathpointtype) enumeration से प्राप्त किए जा सकते हैं। |
| startIndex | int[] | [out] बिंदुओं के समूह का प्रारंभिक सूचकांक प्राप्त करता है। |
| endIndex | int[] | [out] बिंदुओं के समूह का समाप्ति सूचकांक प्राप्त करता है। |

**Returns:**
int - यह विधि समूह में डेटा बिंदुओं की संख्या लौटाती है। यदि पथ में और समूह नहीं हैं, तो यह विधि 0 लौटाती है।
### nextSubpath(int[] startIndex, int[] endIndex, boolean[] isClosed) {#nextSubpath-int---int---boolean---}
```
public int nextSubpath(int[] startIndex, int[] endIndex, boolean[] isClosed)
```


[GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) को पथ में अगले उपपथ पर ले जाता है। अगले उपपथ का प्रारंभिक और समाप्ति सूचकांक [out] पैरामीटर में होते हैं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| startIndex | int[] | [out] अगले उपपथ का प्रारंभिक सूचकांक प्राप्त करता है। |
| endIndex | int[] | [out] अगले उपपथ का समाप्ति सूचकांक प्राप्त करता है। |
| isClosed | boolean[] | [out] दर्शाता है कि उपपथ बंद है या नहीं। |

**Returns:**
int - प्राप्त आकृति (उपपथ) में डेटा बिंदुओं की संख्या। यदि और आकृतियाँ प्राप्त करने के लिए नहीं हैं, तो शून्य लौटाया जाता है।
### nextSubpath(GraphicsPath path, boolean[] isClosed) {#nextSubpath-com.aspose.drawing.drawing2d.GraphicsPath-boolean---}
```
public int nextSubpath(GraphicsPath path, boolean[] isClosed)
```


इस [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) के संबंधित पथ से अगला आकृति (उपमार्ग) प्राप्त करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | एक [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) जिसका डेटा बिंदु इस इटररेटर के लिए प्राप्त आकृति (उपपथ) के डेटा बिंदुओं के साथ मेल खाने के लिए सेट किया जाएगा। |
| isClosed | boolean[] | [out] दर्शाता है कि वर्तमान उपपथ बंद है या नहीं। यदि आकृति बंद है तो यह true है, अन्यथा false। |

**Returns:**
int - प्राप्त आकृति (उपपथ) में डेटा बिंदुओं की संख्या। यदि और आकृतियाँ प्राप्त करने के लिए नहीं हैं, तो शून्य लौटाया जाता है।
### rewind() {#rewind--}
```
public void rewind()
```


इस [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) को उसके संबंधित पथ की शुरुआत पर रीवाइंड करता है।

