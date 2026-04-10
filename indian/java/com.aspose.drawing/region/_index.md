---
title: Region
second_title: Aspose.Drawing for Java API संदर्भ
description: आयतों और पाथों से बनी ग्राफ़िक्स आकृति के अंदरूनी भाग का वर्णन करता है।
type: docs
weight: 40
url: /hi/java/com.aspose.drawing/region/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public final class Region implements System.IDisposable
```

आयतों और पाथ्स से निर्मित ग्राफ़िक्स आकार के अंदरूनी भाग का वर्णन करता है। इस क्लास को विरासत में नहीं लिया जा सकता।
## निर्माता

| निर्माता | विवरण |
| --- | --- |
| [Region()](#Region--) | [Region](../../com.aspose.drawing/region) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [Region(RectangleF rect)](#Region-com.aspose.drawing.RectangleF-) | निर्दिष्ट [RectangleF](../../com.aspose.drawing/rectanglef) संरचना से [Region](../../com.aspose.drawing/region) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [Region(Rectangle rect)](#Region-com.aspose.drawing.Rectangle-) | निर्दिष्ट [Rectangle](../../com.aspose.drawing/rectangle) संरचना से [Region](../../com.aspose.drawing/region) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [Region(GraphicsPath path)](#Region-com.aspose.drawing.drawing2d.GraphicsPath-) | निर्दिष्ट [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) के साथ [Region](../../com.aspose.drawing/region) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [Region(RegionData rgnData)](#Region-com.aspose.drawing.drawing2d.RegionData-) | निर्दिष्ट डेटा से [Region](../../com.aspose.drawing/region) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
## मेथड्स

| विधि | विवरण |
| --- | --- |
| [dispose()](#dispose--) | इस [Region](../../com.aspose.drawing/region) द्वारा उपयोग किए गए सभी संसाधनों को रिलीज़ करता है। |
| [equals(Region region, Graphics g)](#equals-com.aspose.drawing.Region-com.aspose.drawing.Graphics-) | जाँचता है कि निर्दिष्ट [Region](../../com.aspose.drawing/region) निर्दिष्ट ड्रॉइंग सतह पर इस [Region](../../com.aspose.drawing/region) के समान है या नहीं। |
| [deepClone()](#deepClone--) | इस [Region](../../com.aspose.drawing/region) की एक सटीक प्रतिलिपि बनाता है। |
| [makeInfinite()](#makeInfinite--) | इस [Region](../../com.aspose.drawing/region) ऑब्जेक्ट को अनंत आंतरिक भाग में प्रारंभ करता है। |
| [makeEmpty()](#makeEmpty--) | इस [Region](../../com.aspose.drawing/region) को खाली आंतरिक भाग में प्रारंभ करता है। |
| [intersect(RectangleF rect)](#intersect-com.aspose.drawing.RectangleF-) | इस [Region](../../com.aspose.drawing/region) को स्वयं और निर्दिष्ट [RectangleF](../../com.aspose.drawing/rectanglef) संरचना के प्रतिच्छेदन में अपडेट करता है। |
| [intersect(Rectangle rect)](#intersect-com.aspose.drawing.Rectangle-) | इस [Region](../../com.aspose.drawing/region) को स्वयं और निर्दिष्ट [Rectangle](../../com.aspose.drawing/rectangle) संरचना के प्रतिच्छेदन में अपडेट करता है। |
| [intersect(GraphicsPath path)](#intersect-com.aspose.drawing.drawing2d.GraphicsPath-) | इस [Region](../../com.aspose.drawing/region) को स्वयं और निर्दिष्ट [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) के प्रतिच्छेदन में अपडेट करता है। |
| [intersect(Region region)](#intersect-com.aspose.drawing.Region-) | इस [Region](../../com.aspose.drawing/region) को स्वयं और निर्दिष्ट [Region](../../com.aspose.drawing/region) के प्रतिच्छेदन में अपडेट करता है। |
| [union(RectangleF rect)](#union-com.aspose.drawing.RectangleF-) | इस [Region](../../com.aspose.drawing/region) को स्वयं और निर्दिष्ट [RectangleF](../../com.aspose.drawing/rectanglef) संरचना के संघ में अपडेट करता है। |
| [union(Rectangle rect)](#union-com.aspose.drawing.Rectangle-) | इस [Region](../../com.aspose.drawing/region) को स्वयं और निर्दिष्ट [Rectangle](../../com.aspose.drawing/rectangle) संरचना के संघ में अपडेट करता है। |
| [union(GraphicsPath path)](#union-com.aspose.drawing.drawing2d.GraphicsPath-) | इस [Region](../../com.aspose.drawing/region) को स्वयं और निर्दिष्ट [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) के संघ में अपडेट करता है। |
| [union(Region region)](#union-com.aspose.drawing.Region-) | इस [Region](../../com.aspose.drawing/region) को स्वयं और निर्दिष्ट [Region](../../com.aspose.drawing/region) के संघ में अपडेट करता है। |
| [getRegionData()](#getRegionData--) | एक [RegionData](../../com.aspose.drawing.drawing2d/regiondata) लौटाता है जो इस [Region](../../com.aspose.drawing/region) का वर्णन करने वाली जानकारी को दर्शाता है। |
| [xor(RectangleF rect)](#xor-com.aspose.drawing.RectangleF-) | इस [Region](../../com.aspose.drawing/region) को स्वयं और निर्दिष्ट [RectangleF](../../com.aspose.drawing/rectanglef) संरचना के प्रतिच्छेदन को घटाकर संघ में अपडेट करता है। |
| [xor(Rectangle rect)](#xor-com.aspose.drawing.Rectangle-) | इस [Region](../../com.aspose.drawing/region) को स्वयं और निर्दिष्ट [Rectangle](../../com.aspose.drawing/rectangle) संरचना के प्रतिच्छेदन को घटाकर संघ में अपडेट करता है। |
| [xor(GraphicsPath path)](#xor-com.aspose.drawing.drawing2d.GraphicsPath-) | इस [Region](../../com.aspose.drawing/region) को स्वयं और निर्दिष्ट [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) के प्रतिच्छेदन को घटाकर संघ में अपडेट करता है। |
| [xor(Region region)](#xor-com.aspose.drawing.Region-) | इस [Region](../../com.aspose.drawing/region) को स्वयं और निर्दिष्ट [Region](../../com.aspose.drawing/region) के प्रतिच्छेदन को घटाकर संघ में अपडेट करता है। |
| [exclude(RectangleF rect)](#exclude-com.aspose.drawing.RectangleF-) | इस [Region](../../com.aspose.drawing/region) को केवल उसके आंतरिक भाग के उस हिस्से को रखने के लिए अपडेट करता है जो निर्दिष्ट [RectangleF](../../com.aspose.drawing/rectanglef) संरचना के साथ प्रतिच्छेद नहीं करता। |
| [exclude(Rectangle rect)](#exclude-com.aspose.drawing.Rectangle-) | इस [Region](../../com.aspose.drawing/region) को केवल उसके आंतरिक भाग के उस हिस्से को रखने के लिए अपडेट करता है जो निर्दिष्ट [Rectangle](../../com.aspose.drawing/rectangle) संरचना के साथ प्रतिच्छेद नहीं करता। |
| [exclude(GraphicsPath path)](#exclude-com.aspose.drawing.drawing2d.GraphicsPath-) | इस [Region](../../com.aspose.drawing/region) को केवल उसके आंतरिक भाग के उस हिस्से को रखने के लिए अपडेट करता है जो निर्दिष्ट [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) के साथ प्रतिच्छेद नहीं करता। |
| [exclude(Region region)](#exclude-com.aspose.drawing.Region-) | इस [Region](../../com.aspose.drawing/region) को केवल उसके आंतरिक भाग के उस हिस्से को रखने के लिए अपडेट करता है जो निर्दिष्ट [Region](../../com.aspose.drawing/region) के साथ प्रतिच्छेद नहीं करता। |
| [complement(RectangleF rect)](#complement-com.aspose.drawing.RectangleF-) | इस [Region](../../com.aspose.drawing/region) को निर्दिष्ट [RectangleF](../../com.aspose.drawing/rectanglef) संरचना के उस हिस्से को रखने के लिए अपडेट करता है जो इस [Region](../../com.aspose.drawing/region) के साथ प्रतिच्छेद नहीं करता। |
| [complement(Rectangle rect)](#complement-com.aspose.drawing.Rectangle-) | इस [Region](../../com.aspose.drawing/region) को निर्दिष्ट [Rectangle](../../com.aspose.drawing/rectangle) संरचना के उस हिस्से को रखने के लिए अपडेट करता है जो इस [Region](../../com.aspose.drawing/region) के साथ प्रतिच्छेद नहीं करता। |
| [complement(GraphicsPath path)](#complement-com.aspose.drawing.drawing2d.GraphicsPath-) | इस [Region](../../com.aspose.drawing/region) को निर्दिष्ट [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) के उस हिस्से को रखने के लिए अपडेट करता है जो इस [Region](../../com.aspose.drawing/region) के साथ प्रतिच्छेद नहीं करता। |
| [complement(Region region)](#complement-com.aspose.drawing.Region-) | इस [Region](../../com.aspose.drawing/region) को अपडेट करता है ताकि यह निर्दिष्ट [Region](../../com.aspose.drawing/region) के उस भाग को शामिल करे जो इस [Region](../../com.aspose.drawing/region) के साथ प्रतिच्छेद नहीं करता है। |
| [translate(float dx, float dy)](#translate-float-float-) | इस [Region](../../com.aspose.drawing/region) के निर्देशांक को निर्दिष्ट मात्रा द्वारा ऑफसेट करता है। |
| [translate(int dx, int dy)](#translate-int-int-) | इस [Region](../../com.aspose.drawing/region) के निर्देशांक को निर्दिष्ट मात्रा द्वारा ऑफसेट करता है। |
| [transform(Matrix matrix)](#transform-com.aspose.drawing.drawing2d.Matrix-) | इस [Region](../../com.aspose.drawing/region) को निर्दिष्ट [Matrix](../../com.aspose.drawing.drawing2d/matrix) द्वारा रूपांतरित करता है। |
| [getBounds(Graphics g)](#getBounds-com.aspose.drawing.Graphics-) | एक [RectangleF](../../com.aspose.drawing/rectanglef) संरचना प्राप्त करता है जो उस आयत को दर्शाती है जो इस [Region](../../com.aspose.drawing/region) को एक [Graphics](../../com.aspose.drawing/graphics) वस्तु की ड्राइंग सतह पर सीमित करती है। |
| [getRegionScans(Matrix matrix)](#getRegionScans-com.aspose.drawing.drawing2d.Matrix-) | एक एरे लौटाता है जिसमें [RectangleF](../../com.aspose.drawing/rectanglef) संरचनाएँ होती हैं जो निर्दिष्ट मैट्रिक्स रूपांतरण लागू होने के बाद इस [Region](../../com.aspose.drawing/region) का अनुमान लगाती हैं। |
| [isEmpty(Graphics g)](#isEmpty-com.aspose.drawing.Graphics-) | परीक्षण करता है कि क्या यह [Region](../../com.aspose.drawing/region) निर्दिष्ट ड्राइंग सतह पर खाली आंतरिक भाग रखता है। |
| [isInfinite(Graphics g)](#isInfinite-com.aspose.drawing.Graphics-) | परीक्षण करता है कि क्या यह [Region](../../com.aspose.drawing/region) निर्दिष्ट ड्राइंग सतह पर अनंत आंतरिक भाग रखता है। |
| [isVisible(float x, float y)](#isVisible-float-float-) | परीक्षण करता है कि क्या निर्दिष्ट बिंदु इस [Region](../../com.aspose.drawing/region) के भीतर स्थित है। |
| [isVisible(PointF point)](#isVisible-com.aspose.drawing.PointF-) | परीक्षण करता है कि क्या निर्दिष्ट [PointF](../../com.aspose.drawing/pointf) संरचना इस [Region](../../com.aspose.drawing/region) के भीतर स्थित है। |
| [isVisible(float x, float y, Graphics g)](#isVisible-float-float-com.aspose.drawing.Graphics-) | परीक्षण करता है कि क्या निर्दिष्ट बिंदु इस [Region](../../com.aspose.drawing/region) के भीतर स्थित है जब इसे निर्दिष्ट [Graphics](../../com.aspose.drawing/graphics) का उपयोग करके चित्रित किया जाता है। |
| [isVisible(PointF point, Graphics g)](#isVisible-com.aspose.drawing.PointF-com.aspose.drawing.Graphics-) | परीक्षण करता है कि क्या निर्दिष्ट [PointF](../../com.aspose.drawing/pointf) संरचना इस [Region](../../com.aspose.drawing/region) के भीतर स्थित है जब इसे निर्दिष्ट [Graphics](../../com.aspose.drawing/graphics) का उपयोग करके चित्रित किया जाता है। |
| [isVisible(float x, float y, float width, float height)](#isVisible-float-float-float-float-) | परीक्षण करता है कि क्या निर्दिष्ट आयत का कोई भी भाग इस [Region](../../com.aspose.drawing/region) के भीतर स्थित है। |
| [isVisible(RectangleF rect)](#isVisible-com.aspose.drawing.RectangleF-) | परीक्षण करता है कि क्या निर्दिष्ट [RectangleF](../../com.aspose.drawing/rectanglef) संरचना का कोई भी भाग इस [Region](../../com.aspose.drawing/region) के भीतर स्थित है। |
| [isVisible(float x, float y, float width, float height, Graphics g)](#isVisible-float-float-float-float-com.aspose.drawing.Graphics-) | परीक्षण करता है कि क्या निर्दिष्ट आयत का कोई भी भाग इस [Region](../../com.aspose.drawing/region) के भीतर स्थित है जब इसे निर्दिष्ट [Graphics](../../com.aspose.drawing/graphics) का उपयोग करके चित्रित किया जाता है। |
| [isVisible(RectangleF rect, Graphics g)](#isVisible-com.aspose.drawing.RectangleF-com.aspose.drawing.Graphics-) | परीक्षण करता है कि क्या निर्दिष्ट [RectangleF](../../com.aspose.drawing/rectanglef) संरचना का कोई भी भाग इस [Region](../../com.aspose.drawing/region) के भीतर स्थित है जब इसे निर्दिष्ट [Graphics](../../com.aspose.drawing/graphics) का उपयोग करके चित्रित किया जाता है। |
| [isVisible(int x, int y, Graphics g)](#isVisible-int-int-com.aspose.drawing.Graphics-) | परीक्षण करता है कि क्या निर्दिष्ट बिंदु इस [Region](../../com.aspose.drawing/region) वस्तु के भीतर स्थित है जब इसे निर्दिष्ट [Graphics](../../com.aspose.drawing/graphics) वस्तु का उपयोग करके चित्रित किया जाता है। |
| [isVisible(Point point)](#isVisible-com.aspose.drawing.Point-) | परीक्षण करता है कि क्या निर्दिष्ट [Point](../../com.aspose.drawing/point) संरचना इस [Region](../../com.aspose.drawing/region) के भीतर स्थित है। |
| [isVisible(Point point, Graphics g)](#isVisible-com.aspose.drawing.Point-com.aspose.drawing.Graphics-) | परीक्षण करता है कि क्या निर्दिष्ट [Point](../../com.aspose.drawing/point) संरचना इस [Region](../../com.aspose.drawing/region) के भीतर स्थित है जब इसे निर्दिष्ट [Graphics](../../com.aspose.drawing/graphics) का उपयोग करके चित्रित किया जाता है। |
| [isVisible(int x, int y, int width, int height)](#isVisible-int-int-int-int-) | परीक्षण करता है कि क्या निर्दिष्ट आयत का कोई भी भाग इस [Region](../../com.aspose.drawing/region) के भीतर स्थित है। |
| [isVisible(Rectangle rect)](#isVisible-com.aspose.drawing.Rectangle-) | परीक्षण करता है कि क्या निर्दिष्ट [Rectangle](../../com.aspose.drawing/rectangle) संरचना का कोई भी भाग इस [Region](../../com.aspose.drawing/region) के भीतर स्थित है। |
| [isVisible(int x, int y, int width, int height, Graphics g)](#isVisible-int-int-int-int-com.aspose.drawing.Graphics-) | परीक्षण करता है कि क्या निर्दिष्ट आयत का कोई भी भाग इस [Region](../../com.aspose.drawing/region) के भीतर स्थित है जब इसे निर्दिष्ट [Graphics](../../com.aspose.drawing/graphics) का उपयोग करके चित्रित किया जाता है। |
| [isVisible(Rectangle rect, Graphics g)](#isVisible-com.aspose.drawing.Rectangle-com.aspose.drawing.Graphics-) | परीक्षण करता है कि क्या निर्दिष्ट [Rectangle](../../com.aspose.drawing/rectangle) संरचना का कोई भी भाग इस [Region](../../com.aspose.drawing/region) के भीतर स्थित है जब इसे निर्दिष्ट [Graphics](../../com.aspose.drawing/graphics) का उपयोग करके चित्रित किया जाता है। |
### Region() {#Region--}
```
public Region()
```


[Region](../../com.aspose.drawing/region) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

### Region(RectangleF rect) {#Region-com.aspose.drawing.RectangleF-}
```
public Region(RectangleF rect)
```


निर्दिष्ट [RectangleF](../../com.aspose.drawing/rectanglef) संरचना से [Region](../../com.aspose.drawing/region) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | एक [RectangleF](../../com.aspose.drawing/rectanglef) संरचना जो नए [Region](../../com.aspose.drawing/region) के आंतरिक भाग को परिभाषित करती है। |

### Region(Rectangle rect) {#Region-com.aspose.drawing.Rectangle-}
```
public Region(Rectangle rect)
```


निर्दिष्ट [Rectangle](../../com.aspose.drawing/rectangle) संरचना से [Region](../../com.aspose.drawing/region) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | एक [Rectangle](../../com.aspose.drawing/rectangle) संरचना जो नए [Region](../../com.aspose.drawing/region) के आंतरिक भाग को परिभाषित करती है। |

### Region(GraphicsPath path) {#Region-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public Region(GraphicsPath path)
```


निर्दिष्ट [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) के साथ [Region](../../com.aspose.drawing/region) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | एक [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) जो नए [Region](../../com.aspose.drawing/region) को परिभाषित करता है। |

### Region(RegionData rgnData) {#Region-com.aspose.drawing.drawing2d.RegionData-}
```
public Region(RegionData rgnData)
```


निर्दिष्ट डेटा से [Region](../../com.aspose.drawing/region) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rgnData | [RegionData](../../com.aspose.drawing.drawing2d/regiondata) | एक [RegionData](../../com.aspose.drawing.drawing2d/regiondata) जो नए [Region](../../com.aspose.drawing/region) के आंतरिक भाग को परिभाषित करता है। |

### dispose() {#dispose--}
```
public void dispose()
```


इस [Region](../../com.aspose.drawing/region) द्वारा उपयोग किए गए सभी संसाधनों को रिलीज़ करता है।

### equals(Region region, Graphics g) {#equals-com.aspose.drawing.Region-com.aspose.drawing.Graphics-}
```
public boolean equals(Region region, Graphics g)
```


जाँचता है कि निर्दिष्ट [Region](../../com.aspose.drawing/region) निर्दिष्ट ड्रॉइंग सतह पर इस [Region](../../com.aspose.drawing/region) के समान है या नहीं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| region | [Region](../../com.aspose.drawing/region) | परीक्षण करने के लिए [Region](../../com.aspose.drawing/region)। |
| g | [Graphics](../../com.aspose.drawing/graphics) | एक [Graphics](../../com.aspose.drawing/graphics) जो एक ड्रॉइंग सतह का प्रतिनिधित्व करता है। |

**Returns:**
बूलियन - सत्य यदि क्षेत्र का आंतरिक भाग इस क्षेत्र के आंतरिक भाग के समान हो जब `g` पैरामीटर से जुड़ी रूपांतरण लागू की जाती है; अन्यथा, असत्य।
### deepClone() {#deepClone--}
```
public Region deepClone()
```


इस [Region](../../com.aspose.drawing/region) की एक सटीक प्रतिलिपि बनाता है।

**Returns:**
[Region](../../com.aspose.drawing/region) - The [Region](../../com.aspose.drawing/region) that this method creates.
### makeInfinite() {#makeInfinite--}
```
public void makeInfinite()
```


इस [Region](../../com.aspose.drawing/region) ऑब्जेक्ट को अनंत आंतरिक भाग में प्रारंभ करता है।

### makeEmpty() {#makeEmpty--}
```
public void makeEmpty()
```


इस [Region](../../com.aspose.drawing/region) को खाली आंतरिक भाग में प्रारंभ करता है।

### intersect(RectangleF rect) {#intersect-com.aspose.drawing.RectangleF-}
```
public void intersect(RectangleF rect)
```


इस [Region](../../com.aspose.drawing/region) को स्वयं और निर्दिष्ट [RectangleF](../../com.aspose.drawing/rectanglef) संरचना के प्रतिच्छेदन में अपडेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | यह [RectangleF](../../com.aspose.drawing/rectanglef) संरचना इस [Region](../../com.aspose.drawing/region) के साथ प्रतिच्छेद करने के लिए है। |

### intersect(Rectangle rect) {#intersect-com.aspose.drawing.Rectangle-}
```
public void intersect(Rectangle rect)
```


इस [Region](../../com.aspose.drawing/region) को स्वयं और निर्दिष्ट [Rectangle](../../com.aspose.drawing/rectangle) संरचना के प्रतिच्छेदन में अपडेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | यह [Rectangle](../../com.aspose.drawing/rectangle) संरचना इस [Region](../../com.aspose.drawing/region) के साथ प्रतिच्छेद करने के लिए है। |

### intersect(GraphicsPath path) {#intersect-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public void intersect(GraphicsPath path)
```


इस [Region](../../com.aspose.drawing/region) को स्वयं और निर्दिष्ट [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) के प्रतिच्छेदन में अपडेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | यह [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) इस [Region](../../com.aspose.drawing/region) के साथ प्रतिच्छेद करने के लिए है। |

### intersect(Region region) {#intersect-com.aspose.drawing.Region-}
```
public void intersect(Region region)
```


इस [Region](../../com.aspose.drawing/region) को स्वयं और निर्दिष्ट [Region](../../com.aspose.drawing/region) के प्रतिच्छेदन में अपडेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| region | [Region](../../com.aspose.drawing/region) | यह [Region](../../com.aspose.drawing/region) इस [Region](../../com.aspose.drawing/region) के साथ प्रतिच्छेद करने के लिए है। |

### union(RectangleF rect) {#union-com.aspose.drawing.RectangleF-}
```
public void union(RectangleF rect)
```


इस [Region](../../com.aspose.drawing/region) को स्वयं और निर्दिष्ट [RectangleF](../../com.aspose.drawing/rectanglef) संरचना के संघ में अपडेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | rect | [RectangleF](../../com.aspose.drawing/rectanglef) | यह [RectangleF](../../com.aspose.drawing/rectanglef) संरचना इस [Region](../../com.aspose.drawing/region) के साथ मिलाने के लिए है। |

--------------------

संघटन अनंत क्षेत्र को अनंत ही रखता है। |

### union(Rectangle rect) {#union-com.aspose.drawing.Rectangle-}
```
public void union(Rectangle rect)
```


इस [Region](../../com.aspose.drawing/region) को स्वयं और निर्दिष्ट [Rectangle](../../com.aspose.drawing/rectangle) संरचना के संघ में अपडेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | rect | [Rectangle](../../com.aspose.drawing/rectangle) | यह [Rectangle](../../com.aspose.drawing/rectangle) संरचना इस [Region](../../com.aspose.drawing/region) के साथ मिलाने के लिए है। |

--------------------

संघटन अनंत क्षेत्र को अनंत ही रखता है। |

### union(GraphicsPath path) {#union-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public void union(GraphicsPath path)
```


इस [Region](../../com.aspose.drawing/region) को स्वयं और निर्दिष्ट [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) के संघ में अपडेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | यह [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) इस [Region](../../com.aspose.drawing/region) के साथ मिलाने के लिए है। |

--------------------

संघटन अनंत क्षेत्र को अनंत ही रखता है। |

### union(Region region) {#union-com.aspose.drawing.Region-}
```
public void union(Region region)
```


इस [Region](../../com.aspose.drawing/region) को स्वयं और निर्दिष्ट [Region](../../com.aspose.drawing/region) के संघ में अपडेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | region | [Region](../../com.aspose.drawing/region) | यह [Region](../../com.aspose.drawing/region) इस [Region](../../com.aspose.drawing/region) के साथ मिलाने के लिए है। |

--------------------

संघटन अनंत क्षेत्र को अनंत ही रखता है। |

### getRegionData() {#getRegionData--}
```
public RegionData getRegionData()
```


एक [RegionData](../../com.aspose.drawing.drawing2d/regiondata) लौटाता है जो इस [Region](../../com.aspose.drawing/region) का वर्णन करने वाली जानकारी को दर्शाता है।

**Returns:**
[RegionData](../../com.aspose.drawing.drawing2d/regiondata) - A [RegionData](../../com.aspose.drawing.drawing2d/regiondata) that represents the information that describes this [Region](../../com.aspose.drawing/region).
### xor(RectangleF rect) {#xor-com.aspose.drawing.RectangleF-}
```
public void xor(RectangleF rect)
```


इस [Region](../../com.aspose.drawing/region) को स्वयं और निर्दिष्ट [RectangleF](../../com.aspose.drawing/rectanglef) संरचना के प्रतिच्छेदन को घटाकर संघ में अपडेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | यह [RectangleF](../../com.aspose.drawing/rectanglef) संरचना इस [Region](../../com.aspose.drawing/region) के साथ `M:Region.Xor(Drawing2D.GraphicsPath)` करने के लिए है। |

### xor(Rectangle rect) {#xor-com.aspose.drawing.Rectangle-}
```
public void xor(Rectangle rect)
```


इस [Region](../../com.aspose.drawing/region) को स्वयं और निर्दिष्ट [Rectangle](../../com.aspose.drawing/rectangle) संरचना के प्रतिच्छेदन को घटाकर संघ में अपडेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | यह [Rectangle](../../com.aspose.drawing/rectangle) संरचना इस [Region](../../com.aspose.drawing/region) के साथ `M:Region.Xor(Rectangle)` करने के लिए है। |

### xor(GraphicsPath path) {#xor-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public void xor(GraphicsPath path)
```


इस [Region](../../com.aspose.drawing/region) को स्वयं और निर्दिष्ट [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) के प्रतिच्छेदन को घटाकर संघ में अपडेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | यह [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) इस [Region](../../com.aspose.drawing/region) के साथ `M:Region.Xor(GraphicsPath)` करने के लिए है। |

### xor(Region region) {#xor-com.aspose.drawing.Region-}
```
public void xor(Region region)
```


इस [Region](../../com.aspose.drawing/region) को स्वयं और निर्दिष्ट [Region](../../com.aspose.drawing/region) के प्रतिच्छेदन को घटाकर संघ में अपडेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| region | [Region](../../com.aspose.drawing/region) | यह [Region](../../com.aspose.drawing/region) इस [Region](../../com.aspose.drawing/region) के साथ `M:Region.Xor(Region)` करने के लिए है। |

### exclude(RectangleF rect) {#exclude-com.aspose.drawing.RectangleF-}
```
public void exclude(RectangleF rect)
```


इस [Region](../../com.aspose.drawing/region) को केवल उसके आंतरिक भाग के उस हिस्से को रखने के लिए अपडेट करता है जो निर्दिष्ट [RectangleF](../../com.aspose.drawing/rectanglef) संरचना के साथ प्रतिच्छेद नहीं करता।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | यह [RectangleF](../../com.aspose.drawing/rectanglef) संरचना इस [Region](../../com.aspose.drawing/region) से बाहर करने के लिए है। |

### exclude(Rectangle rect) {#exclude-com.aspose.drawing.Rectangle-}
```
public void exclude(Rectangle rect)
```


इस [Region](../../com.aspose.drawing/region) को केवल उसके आंतरिक भाग के उस हिस्से को रखने के लिए अपडेट करता है जो निर्दिष्ट [Rectangle](../../com.aspose.drawing/rectangle) संरचना के साथ प्रतिच्छेद नहीं करता।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | यह [Rectangle](../../com.aspose.drawing/rectangle) संरचना इस [Region](../../com.aspose.drawing/region) से बाहर करने के लिए है। |

### exclude(GraphicsPath path) {#exclude-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public void exclude(GraphicsPath path)
```


इस [Region](../../com.aspose.drawing/region) को केवल उसके आंतरिक भाग के उस हिस्से को रखने के लिए अपडेट करता है जो निर्दिष्ट [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) के साथ प्रतिच्छेद नहीं करता।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | यह [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) इस [Region](../../com.aspose.drawing/region) से बाहर करने के लिए है। |

### exclude(Region region) {#exclude-com.aspose.drawing.Region-}
```
public void exclude(Region region)
```


इस [Region](../../com.aspose.drawing/region) को केवल उसके आंतरिक भाग के उस हिस्से को रखने के लिए अपडेट करता है जो निर्दिष्ट [Region](../../com.aspose.drawing/region) के साथ प्रतिच्छेद नहीं करता।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| region | [Region](../../com.aspose.drawing/region) | यह [Region](../../com.aspose.drawing/region) इस [Region](../../com.aspose.drawing/region) से बाहर करने के लिए है। |

### complement(RectangleF rect) {#complement-com.aspose.drawing.RectangleF-}
```
public void complement(RectangleF rect)
```


इस [Region](../../com.aspose.drawing/region) को निर्दिष्ट [RectangleF](../../com.aspose.drawing/rectanglef) संरचना के उस हिस्से को रखने के लिए अपडेट करता है जो इस [Region](../../com.aspose.drawing/region) के साथ प्रतिच्छेद नहीं करता।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | यह [RectangleF](../../com.aspose.drawing/rectanglef) संरचना इस [Region](../../com.aspose.drawing/region) को पूरक करने के लिए है। |

### complement(Rectangle rect) {#complement-com.aspose.drawing.Rectangle-}
```
public void complement(Rectangle rect)
```


इस [Region](../../com.aspose.drawing/region) को निर्दिष्ट [Rectangle](../../com.aspose.drawing/rectangle) संरचना के उस हिस्से को रखने के लिए अपडेट करता है जो इस [Region](../../com.aspose.drawing/region) के साथ प्रतिच्छेद नहीं करता।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | यह [Rectangle](../../com.aspose.drawing/rectangle) संरचना इस [Region](../../com.aspose.drawing/region) को पूरक करने के लिए है। |

### complement(GraphicsPath path) {#complement-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public void complement(GraphicsPath path)
```


इस [Region](../../com.aspose.drawing/region) को निर्दिष्ट [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) के उस हिस्से को रखने के लिए अपडेट करता है जो इस [Region](../../com.aspose.drawing/region) के साथ प्रतिच्छेद नहीं करता।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | यह [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) इस [Region](../../com.aspose.drawing/region) को पूरक करने के लिए है। |

### complement(Region region) {#complement-com.aspose.drawing.Region-}
```
public void complement(Region region)
```


इस [Region](../../com.aspose.drawing/region) को अपडेट करता है ताकि यह निर्दिष्ट [Region](../../com.aspose.drawing/region) के उस भाग को शामिल करे जो इस [Region](../../com.aspose.drawing/region) के साथ प्रतिच्छेद नहीं करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| region | [Region](../../com.aspose.drawing/region) | यह [Region](../../com.aspose.drawing/region) ऑब्जेक्ट इस [Region](../../com.aspose.drawing/region) ऑब्जेक्ट को पूरक करने के लिए है। |

### translate(float dx, float dy) {#translate-float-float-}
```
public void translate(float dx, float dy)
```


इस [Region](../../com.aspose.drawing/region) के निर्देशांक को निर्दिष्ट मात्रा द्वारा ऑफसेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| dx | float | इस [Region](../../com.aspose.drawing/region) को क्षैतिज रूप से ऑफसेट करने की मात्रा। |
| dy | float | इस [Region](../../com.aspose.drawing/region) को लंबवत रूप से ऑफसेट करने की मात्रा। |

### translate(int dx, int dy) {#translate-int-int-}
```
public void translate(int dx, int dy)
```


इस [Region](../../com.aspose.drawing/region) के निर्देशांक को निर्दिष्ट मात्रा द्वारा ऑफसेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| dx | int | इस [Region](../../com.aspose.drawing/region) को क्षैतिज रूप से ऑफसेट करने की मात्रा |
| dy | int | इस [Region](../../com.aspose.drawing/region) को लंबवत रूप से ऑफसेट करने की मात्रा। |

### transform(Matrix matrix) {#transform-com.aspose.drawing.drawing2d.Matrix-}
```
public void transform(Matrix matrix)
```


इस [Region](../../com.aspose.drawing/region) को निर्दिष्ट [Matrix](../../com.aspose.drawing.drawing2d/matrix) द्वारा रूपांतरित करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | इस [Region](../../com.aspose.drawing/region) को परिवर्तित करने के लिए उपयोग किया जाने वाला [Matrix](../../com.aspose.drawing.drawing2d/matrix)। |

### getBounds(Graphics g) {#getBounds-com.aspose.drawing.Graphics-}
```
public RectangleF getBounds(Graphics g)
```


एक [RectangleF](../../com.aspose.drawing/rectanglef) संरचना प्राप्त करता है जो उस आयत को दर्शाती है जो इस [Region](../../com.aspose.drawing/region) को एक [Graphics](../../com.aspose.drawing/graphics) वस्तु की ड्राइंग सतह पर सीमित करती है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| g | [Graphics](../../com.aspose.drawing/graphics) | जिस [Graphics](../../com.aspose.drawing/graphics) पर यह [Region](../../com.aspose.drawing/region) चित्रित किया गया है। |

**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef) - A [RectangleF](../../com.aspose.drawing/rectanglef) structure that represents the bounding rectangle for this [Region](../../com.aspose.drawing/region) on the specified drawing surface.
### getRegionScans(Matrix matrix) {#getRegionScans-com.aspose.drawing.drawing2d.Matrix-}
```
public RectangleF[] getRegionScans(Matrix matrix)
```


एक एरे लौटाता है जिसमें [RectangleF](../../com.aspose.drawing/rectanglef) संरचनाएँ होती हैं जो निर्दिष्ट मैट्रिक्स रूपांतरण लागू होने के बाद इस [Region](../../com.aspose.drawing/region) का अनुमान लगाती हैं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | एक [Matrix](../../com.aspose.drawing.drawing2d/matrix) जो क्षेत्र पर लागू करने के लिए ज्यामितीय परिवर्तन का प्रतिनिधित्व करता है। |

**Returns:**
com.aspose.drawing.RectangleF[] - एक एरे जिसमें [RectangleF](../../com.aspose.drawing/rectanglef) संरचनाएँ हैं जो निर्दिष्ट मैट्रिक्स परिवर्तन लागू होने के बाद इस [Region](../../com.aspose.drawing/region) का अनुमान लगाती हैं।
### isEmpty(Graphics g) {#isEmpty-com.aspose.drawing.Graphics-}
```
public boolean isEmpty(Graphics g)
```


परीक्षण करता है कि क्या यह [Region](../../com.aspose.drawing/region) निर्दिष्ट ड्राइंग सतह पर खाली आंतरिक भाग रखता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| g | [Graphics](../../com.aspose.drawing/graphics) | एक [Graphics](../../com.aspose.drawing/graphics) जो एक ड्रॉइंग सतह का प्रतिनिधित्व करता है। |

**Returns:**
boolean - `g` के साथ जुड़े परिवर्तन को लागू करने पर यदि इस [Region](../../com.aspose.drawing/region) का अंतःस्थ भाग खाली है तो true; अन्यथा false।
### isInfinite(Graphics g) {#isInfinite-com.aspose.drawing.Graphics-}
```
public boolean isInfinite(Graphics g)
```


परीक्षण करता है कि क्या यह [Region](../../com.aspose.drawing/region) निर्दिष्ट ड्राइंग सतह पर अनंत आंतरिक भाग रखता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| g | [Graphics](../../com.aspose.drawing/graphics) | एक [Graphics](../../com.aspose.drawing/graphics) जो एक ड्रॉइंग सतह का प्रतिनिधित्व करता है। |

**Returns:**
boolean - `g` के साथ जुड़े परिवर्तन को लागू करने पर यदि इस [Region](../../com.aspose.drawing/region) का अंतःस्थ भाग अनंत है तो true; अन्यथा false।
### isVisible(float x, float y) {#isVisible-float-float-}
```
public boolean isVisible(float x, float y)
```


परीक्षण करता है कि क्या निर्दिष्ट बिंदु इस [Region](../../com.aspose.drawing/region) के भीतर स्थित है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | फ़्लोट | जाँचने वाले बिंदु का x-निर्देशांक। |
| y | फ़्लोट | परीक्षण बिंदु का y-निर्देशांक। |

**Returns:**
boolean - जब निर्दिष्ट बिंदु इस [Region](../../com.aspose.drawing/region) के भीतर हो तो true; अन्यथा false।
### isVisible(PointF point) {#isVisible-com.aspose.drawing.PointF-}
```
public boolean isVisible(PointF point)
```


परीक्षण करता है कि क्या निर्दिष्ट [PointF](../../com.aspose.drawing/pointf) संरचना इस [Region](../../com.aspose.drawing/region) के भीतर स्थित है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| point | [PointF](../../com.aspose.drawing/pointf) | परीक्षण करने के लिए [PointF](../../com.aspose.drawing/pointf) संरचना। |

**Returns:**
boolean - जब `point` इस [Region](../../com.aspose.drawing/region) के भीतर हो तो true; अन्यथा false।
### isVisible(float x, float y, Graphics g) {#isVisible-float-float-com.aspose.drawing.Graphics-}
```
public boolean isVisible(float x, float y, Graphics g)
```


परीक्षण करता है कि क्या निर्दिष्ट बिंदु इस [Region](../../com.aspose.drawing/region) के भीतर स्थित है जब इसे निर्दिष्ट [Graphics](../../com.aspose.drawing/graphics) का उपयोग करके चित्रित किया जाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | फ़्लोट | जाँचने वाले बिंदु का x-निर्देशांक। |
| y | फ़्लोट | परीक्षण बिंदु का y-निर्देशांक। |
| g | [Graphics](../../com.aspose.drawing/graphics) | एक [Graphics](../../com.aspose.drawing/graphics) जो ग्राफ़िक्स संदर्भ का प्रतिनिधित्व करता है। |

**Returns:**
boolean - जब निर्दिष्ट बिंदु इस [Region](../../com.aspose.drawing/region) के भीतर हो तो true; अन्यथा false।
### isVisible(PointF point, Graphics g) {#isVisible-com.aspose.drawing.PointF-com.aspose.drawing.Graphics-}
```
public boolean isVisible(PointF point, Graphics g)
```


परीक्षण करता है कि क्या निर्दिष्ट [PointF](../../com.aspose.drawing/pointf) संरचना इस [Region](../../com.aspose.drawing/region) के भीतर स्थित है जब इसे निर्दिष्ट [Graphics](../../com.aspose.drawing/graphics) का उपयोग करके चित्रित किया जाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| point | [PointF](../../com.aspose.drawing/pointf) | परीक्षण करने के लिए [PointF](../../com.aspose.drawing/pointf) संरचना। |
| g | [Graphics](../../com.aspose.drawing/graphics) | एक [Graphics](../../com.aspose.drawing/graphics) जो ग्राफ़िक्स संदर्भ का प्रतिनिधित्व करता है। |

**Returns:**
boolean - जब `point` इस [Region](../../com.aspose.drawing/region) के भीतर हो तो true; अन्यथा false।
### isVisible(float x, float y, float width, float height) {#isVisible-float-float-float-float-}
```
public boolean isVisible(float x, float y, float width, float height)
```


परीक्षण करता है कि क्या निर्दिष्ट आयत का कोई भी भाग इस [Region](../../com.aspose.drawing/region) के भीतर स्थित है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | फ़्लोट | परीक्षण करने वाले आयत के ऊपर-बाएँ कोने का x-निर्देशांक। |
| y | फ़्लोट | परीक्षण करने वाले आयत के ऊपर-बाएँ कोने का y-निर्देशांक। |
| चौड़ाई | फ़्लोट | परीक्षण करने वाले आयत की चौड़ाई। |
| ऊँचाई | फ़्लोट | परीक्षण करने वाले आयत की ऊँचाई। |

**Returns:**
boolean - जब निर्दिष्ट आयत का कोई भी भाग इस [Region](../../com.aspose.drawing/region) वस्तु के भीतर हो तो true; अन्यथा false।
### isVisible(RectangleF rect) {#isVisible-com.aspose.drawing.RectangleF-}
```
public boolean isVisible(RectangleF rect)
```


परीक्षण करता है कि क्या निर्दिष्ट [RectangleF](../../com.aspose.drawing/rectanglef) संरचना का कोई भी भाग इस [Region](../../com.aspose.drawing/region) के भीतर स्थित है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | परीक्षण करने के लिए [RectangleF](../../com.aspose.drawing/rectanglef) संरचना। |

**Returns:**
boolean - जब `rect` का कोई भी भाग इस [Region](../../com.aspose.drawing/region) के भीतर हो तो true; अन्यथा false।
### isVisible(float x, float y, float width, float height, Graphics g) {#isVisible-float-float-float-float-com.aspose.drawing.Graphics-}
```
public boolean isVisible(float x, float y, float width, float height, Graphics g)
```


परीक्षण करता है कि क्या निर्दिष्ट आयत का कोई भी भाग इस [Region](../../com.aspose.drawing/region) के भीतर स्थित है जब इसे निर्दिष्ट [Graphics](../../com.aspose.drawing/graphics) का उपयोग करके चित्रित किया जाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | फ़्लोट | परीक्षण करने वाले आयत के ऊपर-बाएँ कोने का x-निर्देशांक। |
| y | फ़्लोट | परीक्षण करने वाले आयत के ऊपर-बाएँ कोने का y-निर्देशांक। |
| चौड़ाई | फ़्लोट | परीक्षण करने वाले आयत की चौड़ाई। |
| ऊँचाई | फ़्लोट | परीक्षण करने वाले आयत की ऊँचाई। |
| g | [Graphics](../../com.aspose.drawing/graphics) | एक [Graphics](../../com.aspose.drawing/graphics) जो ग्राफ़िक्स संदर्भ का प्रतिनिधित्व करता है। |

**Returns:**
boolean - जब निर्दिष्ट आयत का कोई भी भाग इस [Region](../../com.aspose.drawing/region) के भीतर हो तो true; अन्यथा false।
### isVisible(RectangleF rect, Graphics g) {#isVisible-com.aspose.drawing.RectangleF-com.aspose.drawing.Graphics-}
```
public boolean isVisible(RectangleF rect, Graphics g)
```


परीक्षण करता है कि क्या निर्दिष्ट [RectangleF](../../com.aspose.drawing/rectanglef) संरचना का कोई भी भाग इस [Region](../../com.aspose.drawing/region) के भीतर स्थित है जब इसे निर्दिष्ट [Graphics](../../com.aspose.drawing/graphics) का उपयोग करके चित्रित किया जाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | परीक्षण करने के लिए [RectangleF](../../com.aspose.drawing/rectanglef) संरचना। |
| g | [Graphics](../../com.aspose.drawing/graphics) | एक [Graphics](../../com.aspose.drawing/graphics) जो ग्राफ़िक्स संदर्भ का प्रतिनिधित्व करता है। |

**Returns:**
boolean - जब `rect` इस [Region](../../com.aspose.drawing/region) के भीतर हो तो true; अन्यथा false।
### isVisible(int x, int y, Graphics g) {#isVisible-int-int-com.aspose.drawing.Graphics-}
```
public boolean isVisible(int x, int y, Graphics g)
```


परीक्षण करता है कि क्या निर्दिष्ट बिंदु इस [Region](../../com.aspose.drawing/region) वस्तु के भीतर स्थित है जब इसे निर्दिष्ट [Graphics](../../com.aspose.drawing/graphics) वस्तु का उपयोग करके चित्रित किया जाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | int | जाँचने वाले बिंदु का x-निर्देशांक। |
| y | int | परीक्षण बिंदु का y-निर्देशांक। |
| g | [Graphics](../../com.aspose.drawing/graphics) | एक [Graphics](../../com.aspose.drawing/graphics) जो ग्राफ़िक्स संदर्भ का प्रतिनिधित्व करता है। |

**Returns:**
boolean - जब निर्दिष्ट बिंदु इस [Region](../../com.aspose.drawing/region) के भीतर हो तो true; अन्यथा false।
### isVisible(Point point) {#isVisible-com.aspose.drawing.Point-}
```
public boolean isVisible(Point point)
```


परीक्षण करता है कि क्या निर्दिष्ट [Point](../../com.aspose.drawing/point) संरचना इस [Region](../../com.aspose.drawing/region) के भीतर स्थित है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| point | [Point](../../com.aspose.drawing/point) | परीक्षण करने के लिए [Point](../../com.aspose.drawing/point) संरचना। |

**Returns:**
boolean - जब `point` इस [Region](../../com.aspose.drawing/region) के भीतर हो तो true; अन्यथा false।
### isVisible(Point point, Graphics g) {#isVisible-com.aspose.drawing.Point-com.aspose.drawing.Graphics-}
```
public boolean isVisible(Point point, Graphics g)
```


परीक्षण करता है कि क्या निर्दिष्ट [Point](../../com.aspose.drawing/point) संरचना इस [Region](../../com.aspose.drawing/region) के भीतर स्थित है जब इसे निर्दिष्ट [Graphics](../../com.aspose.drawing/graphics) का उपयोग करके चित्रित किया जाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| point | [Point](../../com.aspose.drawing/point) | परीक्षण करने के लिए [Point](../../com.aspose.drawing/point) संरचना। |
| g | [Graphics](../../com.aspose.drawing/graphics) | एक [Graphics](../../com.aspose.drawing/graphics) जो ग्राफ़िक्स संदर्भ का प्रतिनिधित्व करता है। |

**Returns:**
boolean - जब `point` इस [Region](../../com.aspose.drawing/region) के भीतर हो तो true; अन्यथा false।
### isVisible(int x, int y, int width, int height) {#isVisible-int-int-int-int-}
```
public boolean isVisible(int x, int y, int width, int height)
```


परीक्षण करता है कि क्या निर्दिष्ट आयत का कोई भी भाग इस [Region](../../com.aspose.drawing/region) के भीतर स्थित है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | int | परीक्षण करने वाले आयत के ऊपर-बाएँ कोने का x-निर्देशांक। |
| y | int | परीक्षण करने वाले आयत के ऊपर-बाएँ कोने का y-निर्देशांक। |
| चौड़ाई | int | परीक्षण करने वाले आयत की चौड़ाई। |
| ऊँचाई | int | परीक्षण करने वाले आयत की ऊँचाई। |

**Returns:**
boolean - जब निर्दिष्ट आयत का कोई भी भाग इस [Region](../../com.aspose.drawing/region) के भीतर हो तो true; अन्यथा false।
### isVisible(Rectangle rect) {#isVisible-com.aspose.drawing.Rectangle-}
```
public boolean isVisible(Rectangle rect)
```


परीक्षण करता है कि क्या निर्दिष्ट [Rectangle](../../com.aspose.drawing/rectangle) संरचना का कोई भी भाग इस [Region](../../com.aspose.drawing/region) के भीतर स्थित है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | परीक्षण करने के लिए [Rectangle](../../com.aspose.drawing/rectangle) संरचना। |

**Returns:**
boolean - यह विधि true लौटाती है जब `rect` का कोई भी भाग इस [Region](../../com.aspose.drawing/region) के भीतर हो; अन्यथा false।
### isVisible(int x, int y, int width, int height, Graphics g) {#isVisible-int-int-int-int-com.aspose.drawing.Graphics-}
```
public boolean isVisible(int x, int y, int width, int height, Graphics g)
```


परीक्षण करता है कि क्या निर्दिष्ट आयत का कोई भी भाग इस [Region](../../com.aspose.drawing/region) के भीतर स्थित है जब इसे निर्दिष्ट [Graphics](../../com.aspose.drawing/graphics) का उपयोग करके चित्रित किया जाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | int | परीक्षण करने वाले आयत के ऊपर-बाएँ कोने का x-निर्देशांक। |
| y | int | परीक्षण करने वाले आयत के ऊपर-बाएँ कोने का y-निर्देशांक। |
| चौड़ाई | int | परीक्षण करने वाले आयत की चौड़ाई। |
| ऊँचाई | int | परीक्षण करने वाले आयत की ऊँचाई। |
| g | [Graphics](../../com.aspose.drawing/graphics) | एक [Graphics](../../com.aspose.drawing/graphics) जो ग्राफ़िक्स संदर्भ का प्रतिनिधित्व करता है। |

**Returns:**
boolean - जब निर्दिष्ट आयत का कोई भी भाग इस [Region](../../com.aspose.drawing/region) के भीतर हो तो true; अन्यथा false।
### isVisible(Rectangle rect, Graphics g) {#isVisible-com.aspose.drawing.Rectangle-com.aspose.drawing.Graphics-}
```
public boolean isVisible(Rectangle rect, Graphics g)
```


परीक्षण करता है कि क्या निर्दिष्ट [Rectangle](../../com.aspose.drawing/rectangle) संरचना का कोई भी भाग इस [Region](../../com.aspose.drawing/region) के भीतर स्थित है जब इसे निर्दिष्ट [Graphics](../../com.aspose.drawing/graphics) का उपयोग करके चित्रित किया जाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | परीक्षण करने के लिए [Rectangle](../../com.aspose.drawing/rectangle) संरचना। |
| g | [Graphics](../../com.aspose.drawing/graphics) | एक [Graphics](../../com.aspose.drawing/graphics) जो ग्राफ़िक्स संदर्भ का प्रतिनिधित्व करता है। |

**Returns:**
boolean - जब `rect` का कोई भी भाग इस [Region](../../com.aspose.drawing/region) के भीतर हो तो true; अन्यथा false।
