---
title: बिटमैप
second_title: Aspose.Drawing for Java API संदर्भ
description: एक बिटमैप को संलग्न करता है जिसमें ग्राफ़िक्स छवि के पिक्सेल डेटा और उसकी विशेषताएँ होती हैं।
type: docs
weight: 10
url: /hi/java/com.aspose.drawing/bitmap/
---
**Inheritance:**
java.lang.Object, [com.aspose.drawing.Image](../../com.aspose.drawing/image)
```
public class Bitmap extends Image
```

एक बिटमैप को संलग्न करता है, जिसमें ग्राफ़िक्स छवि के पिक्सेल डेटा और उसकी विशेषताएँ होती हैं। एक [Bitmap](../../com.aspose.drawing/bitmap) वह ऑब्जेक्ट है जिसका उपयोग पिक्सेल डेटा द्वारा परिभाषित छवियों के साथ काम करने के लिए किया जाता है।
## निर्माता

| निर्माता | विवरण |
| --- | --- |
| [Bitmap(int width, int height)](#Bitmap-int-int-) | निर्दिष्ट आकार के साथ [Bitmap](../../com.aspose.drawing/bitmap) क्लास का एक नया इंस्टेंस प्रारंभ करता है। |
| [Bitmap(String filename)](#Bitmap-java.lang.String-) | निर्दिष्ट फ़ाइल से [Bitmap](../../com.aspose.drawing/bitmap) क्लास का एक नया इंस्टेंस प्रारंभ करता है। |
| [Bitmap(String filename, boolean useIcm)](#Bitmap-java.lang.String-boolean-) | निर्दिष्ट फ़ाइल से [Bitmap](../../com.aspose.drawing/bitmap) क्लास का एक नया इंस्टेंस प्रारंभ करता है। |
| [Bitmap(InputStream stream)](#Bitmap-java.io.InputStream-) | निर्दिष्ट डेटा स्ट्रीम से [Bitmap](../../com.aspose.drawing/bitmap) क्लास का एक नया इंस्टेंस प्रारंभ करता है। |
| [Bitmap(InputStream stream, boolean useIcm)](#Bitmap-java.io.InputStream-boolean-) | निर्दिष्ट डेटा स्ट्रीम से [Bitmap](../../com.aspose.drawing/bitmap) क्लास का एक नया इंस्टेंस प्रारंभ करता है। |
| [Bitmap(int width, int height, int format)](#Bitmap-int-int-int-) | निर्दिष्ट आकार और फ़ॉर्मेट के साथ [Bitmap](../../com.aspose.drawing/bitmap) क्लास का एक नया इंस्टेंस प्रारंभ करता है। |
| [Bitmap(int width, int height, int stride, int format, int[] data)](#Bitmap-int-int-int-int-int---) | निर्दिष्ट आकार और पिक्सेल डेटा के साथ [Bitmap](../../com.aspose.drawing/bitmap) क्लास का एक नया इंस्टेंस प्रारंभ करता है। |
| [Bitmap(Image original)](#Bitmap-com.aspose.drawing.Image-) | निर्दिष्ट मौजूदा छवि से [Bitmap](../../com.aspose.drawing/bitmap) क्लास का एक नया इंस्टेंस प्रारंभ करता है। |
| [Bitmap(Image original, Size newSize)](#Bitmap-com.aspose.drawing.Image-com.aspose.drawing.Size-) | निर्दिष्ट मौजूदा छवि से, निर्दिष्ट आकार में स्केल करके, [Bitmap](../../com.aspose.drawing/bitmap) क्लास का एक नया इंस्टेंस प्रारंभ करता है। |
| [Bitmap(Image original, int width, int height)](#Bitmap-com.aspose.drawing.Image-int-int-) | निर्दिष्ट मौजूदा छवि से, निर्दिष्ट आकार में स्केल करके, [Bitmap](../../com.aspose.drawing/bitmap) क्लास का एक नया इंस्टेंस प्रारंभ करता है। |
## मेथड्स

| विधि | विवरण |
| --- | --- |
| [getWidth()](#getWidth--) | इस Bitmap की चौड़ाई, पिक्सेल में, प्राप्त करता है। |
| [getHeight()](#getHeight--) | इस Bitmap की ऊँचाई, पिक्सेल में, प्राप्त करता है। |
| [getRawFormat()](#getRawFormat--) | इस [Image](../../com.aspose.drawing/image) का फ़ाइल फ़ॉर्मेट प्राप्त करता है। |
| [getPixelFormat()](#getPixelFormat--) | इस [Image](../../com.aspose.drawing/image) का पिक्सेल फ़ॉर्मेट प्राप्त करता है। |
| [getPalette()](#getPalette--) | इस [Image](../../com.aspose.drawing/image) के लिए उपयोग किए जाने वाले रंग पैलेट को प्राप्त करता है या सेट करता है। |
| [setPalette(ColorPalette value)](#setPalette-com.aspose.drawing.imaging.ColorPalette-) | इस [Image](../../com.aspose.drawing/image) के लिए उपयोग किए जाने वाले रंग पैलेट को प्राप्त करता है या सेट करता है। |
| [getFrameDimensionsList()](#getFrameDimensionsList--) | इस [Image](../../com.aspose.drawing/image) के भीतर फ्रेमों के आयामों को दर्शाने वाले GUIDs की एक सरणी प्राप्त करता है। |
| [getPropertyIdList()](#getPropertyIdList--) | इस [Image](../../com.aspose.drawing/image) में संग्रहीत प्रॉपर्टी आइटम्स के IDs प्राप्त करता है। |
| [getPropertyItems()](#getPropertyItems--) | इस [Image](../../com.aspose.drawing/image) में संग्रहीत सभी प्रॉपर्टी आइटम्स (मेटाडेटा के टुकड़े) प्राप्त करता है। |
| [deepClone(Rectangle rect, int format)](#deepClone-com.aspose.drawing.Rectangle-int-) | इस [Bitmap](../../com.aspose.drawing/bitmap) के उस भाग की एक कॉपी बनाता है जो [Rectangle](../../com.aspose.drawing/rectangle) संरचना द्वारा परिभाषित है और निर्दिष्ट `PixelFormat`([Image.getPixelFormat](../../com.aspose.drawing/image\#getPixelFormat)) एनेमरेशन के साथ। |
| [deepClone(RectangleF rect, int format)](#deepClone-com.aspose.drawing.RectangleF-int-) | निर्दिष्ट [PixelFormat](../../com.aspose.drawing.imaging/pixelformat) एनेमरेशन के साथ परिभाषित इस [Bitmap](../../com.aspose.drawing/bitmap) के भाग की एक कॉपी बनाता है। |
| [setResolution(float xDpi, float yDpi)](#setResolution-float-float-) | इस [Bitmap](../../com.aspose.drawing/bitmap) के लिए रिज़ॉल्यूशन सेट करता है। |
| [lockBits(Rectangle rect, int flags, int format)](#lockBits-com.aspose.drawing.Rectangle-int-int-) | सिस्टम मेमोरी में एक [Bitmap](../../com.aspose.drawing/bitmap) को लॉक करता है। |
| [unlockBits(BitmapData bitmapData)](#unlockBits-com.aspose.drawing.imaging.BitmapData-) | सिस्टम मेमोरी से इस [Bitmap](../../com.aspose.drawing/bitmap) को अनलॉक करता है। |
| [getPixel(int x, int y)](#getPixel-int-int-) | इस [Bitmap](../../com.aspose.drawing/bitmap) में निर्दिष्ट पिक्सेल का रंग प्राप्त करता है। |
| [setPixel(int x, int y, Color color)](#setPixel-int-int-com.aspose.drawing.Color-) | इस [Bitmap](../../com.aspose.drawing/bitmap) में निर्दिष्ट पिक्सेल का रंग सेट करता है। |
| [readArgb32Pixels(int[] pixels)](#readArgb32Pixels-int---) | दिए गए एरे में ARGB32 फ़ॉर्मेट में बिटमैप पिक्सेल पढ़ता है। |
| [writeArgb32Pixels(int[] pixels)](#writeArgb32Pixels-int---) | बिटमैप में पिक्सेल लिखता है। |
| [makeTransparent()](#makeTransparent--) | इस [Bitmap](../../com.aspose.drawing/bitmap) के लिए निर्दिष्ट रंग को पारदर्शी बनाता है। |
| [makeTransparent(Color transparentColor)](#makeTransparent-com.aspose.drawing.Color-) | इस [Bitmap](../../com.aspose.drawing/bitmap) के लिए निर्दिष्ट रंग को पारदर्शी बनाता है। |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | यह मेथड [Image](../../com.aspose.drawing/image) को घुमाता, उलटता, या घुमाकर उलटता है। |
| [getPropertyItem(int propid)](#getPropertyItem-int-) | इस [Image](../../com.aspose.drawing/image) से निर्दिष्ट प्रॉपर्टी आइटम प्राप्त करता है। |
| [removePropertyItem(int propid)](#removePropertyItem-int-) | इस [Image](../../com.aspose.drawing/image) से निर्दिष्ट प्रॉपर्टी आइटम को हटाता है। |
| [setPropertyItem(PropertyItem propitem)](#setPropertyItem-com.aspose.drawing.imaging.PropertyItem-) | इस [Image](../../com.aspose.drawing/image) में एक प्रॉपर्टी आइटम (मेटाडेटा का टुकड़ा) संग्रहीत करता है। |
### Bitmap(int width, int height) {#Bitmap-int-int-}
```
public Bitmap(int width, int height)
```


निर्दिष्ट आकार के साथ [Bitmap](../../com.aspose.drawing/bitmap) क्लास का एक नया इंस्टेंस प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| चौड़ाई | int | नए Bitmap की चौड़ाई, पिक्सेल में। |
|  | ऊँचाई | int | नए Bitmap की ऊँचाई, पिक्सेल में। |

--------------------

वर्तमान में समर्थित एकमात्र आंतरिक बिटमैप फ़ॉर्मेट `PixelFormat.Format32bppPArgb` के बराबर है। |

### Bitmap(String filename) {#Bitmap-java.lang.String-}
```
public Bitmap(String filename)
```


निर्दिष्ट फ़ाइल से [Bitmap](../../com.aspose.drawing/bitmap) क्लास का एक नया इंस्टेंस प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| फ़ाइलनाम | java.lang.String | बिटमैप फ़ाइल का नाम। |

### Bitmap(String filename, boolean useIcm) {#Bitmap-java.lang.String-boolean-}
```
public Bitmap(String filename, boolean useIcm)
```


निर्दिष्ट फ़ाइल से [Bitmap](../../com.aspose.drawing/bitmap) क्लास का एक नया इंस्टेंस प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| फ़ाइलनाम | java.lang.String | बिटमैप फ़ाइल का नाम। |
| useIcm | boolean | इस [Bitmap](../../com.aspose.drawing/bitmap) के लिए रंग सुधार उपयोग करने हेतु true; अन्यथा false। |

### Bitmap(InputStream stream) {#Bitmap-java.io.InputStream-}
```
public Bitmap(InputStream stream)
```


निर्दिष्ट डेटा स्ट्रीम से [Bitmap](../../com.aspose.drawing/bitmap) क्लास का एक नया इंस्टेंस प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| स्ट्रीम | java.io.InputStream | इमेज लोड करने के लिए उपयोग किया गया डेटा स्ट्रीम। |

### Bitmap(InputStream stream, boolean useIcm) {#Bitmap-java.io.InputStream-boolean-}
```
public Bitmap(InputStream stream, boolean useIcm)
```


निर्दिष्ट डेटा स्ट्रीम से [Bitmap](../../com.aspose.drawing/bitmap) क्लास का एक नया इंस्टेंस प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| स्ट्रीम | java.io.InputStream | इमेज लोड करने के लिए उपयोग किया गया डेटा स्ट्रीम। |
| useIcm | boolean | `true` इस [Bitmap](../../com.aspose.drawing/bitmap) के लिए रंग सुधार उपयोग करने हेतु; अन्यथा `false`। |

### Bitmap(int width, int height, int format) {#Bitmap-int-int-int-}
```
public Bitmap(int width, int height, int format)
```


निर्दिष्ट आकार और फ़ॉर्मेट के साथ [Bitmap](../../com.aspose.drawing/bitmap) क्लास का एक नया इंस्टेंस प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| width | int | नए [Bitmap](../../com.aspose.drawing/bitmap) की चौड़ाई, पिक्सेल में। |
| height | int | नए [Bitmap](../../com.aspose.drawing/bitmap) की ऊँचाई, पिक्सेल में। |
| format | int | नए [Bitmap](../../com.aspose.drawing/bitmap) के लिए `PixelFormat`([Image.getPixelFormat](../../com.aspose.drawing/image\#getPixelFormat)) एन्यूमरेशन। |

### Bitmap(int width, int height, int stride, int format, int[] data) {#Bitmap-int-int-int-int-int---}
```
public Bitmap(int width, int height, int stride, int format, int[] data)
```


निर्दिष्ट आकार और पिक्सेल डेटा के साथ [Bitmap](../../com.aspose.drawing/bitmap) क्लास का एक नया इंस्टेंस प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| width | int | नए [Bitmap](../../com.aspose.drawing/bitmap) की चौड़ाई, पिक्सेल में। |
| height | int | नए [Bitmap](../../com.aspose.drawing/bitmap) की ऊँचाई, पिक्सेल में। |
| स्ट्राइड | int | एक स्कैन लाइन की शुरुआत और अगले के बीच बाइट ऑफ़सेट, जो चार का गुणज होना चाहिए। |
| format | int | नए [Bitmap](../../com.aspose.drawing/bitmap) के लिए `PixelFormat`([Image.getPixelFormat](../../com.aspose.drawing/image\#getPixelFormat)) एन्यूमरेशन। |
| डेटा | int[] | पिक्सेल डेटा। |

### Bitmap(Image original) {#Bitmap-com.aspose.drawing.Image-}
```
public Bitmap(Image original)
```


निर्दिष्ट मौजूदा छवि से [Bitmap](../../com.aspose.drawing/bitmap) क्लास का एक नया इंस्टेंस प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| original | [Image](../../com.aspose.drawing/image) | नए [Bitmap](../../com.aspose.drawing/bitmap) को बनाने के लिए स्रोत [Image](../../com.aspose.drawing/image)। |

### Bitmap(Image original, Size newSize) {#Bitmap-com.aspose.drawing.Image-com.aspose.drawing.Size-}
```
public Bitmap(Image original, Size newSize)
```


निर्दिष्ट मौजूदा छवि से, निर्दिष्ट आकार में स्केल करके, [Bitmap](../../com.aspose.drawing/bitmap) क्लास का एक नया इंस्टेंस प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| original | [Image](../../com.aspose.drawing/image) | नए [Bitmap](../../com.aspose.drawing/bitmap) को बनाने के लिए स्रोत [Image](../../com.aspose.drawing/image) |
| newSize | [Size](../../com.aspose.drawing/size) | यह `Size`([Image.getSize](../../com.aspose.drawing/image\#getSize)) संरचना जो नए [Bitmap](../../com.aspose.drawing/bitmap) का आकार दर्शाती है। |

### Bitmap(Image original, int width, int height) {#Bitmap-com.aspose.drawing.Image-int-int-}
```
public Bitmap(Image original, int width, int height)
```


निर्दिष्ट मौजूदा छवि से, निर्दिष्ट आकार में स्केल करके, [Bitmap](../../com.aspose.drawing/bitmap) क्लास का एक नया इंस्टेंस प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| original | [Image](../../com.aspose.drawing/image) | नए [Bitmap](../../com.aspose.drawing/bitmap) को बनाने के लिए स्रोत [Image](../../com.aspose.drawing/image)। |
| width | int | नए [Bitmap](../../com.aspose.drawing/bitmap) की चौड़ाई, पिक्सेल में। |
| height | int | नए [Bitmap](../../com.aspose.drawing/bitmap) की ऊँचाई, पिक्सेल में। |

### getWidth() {#getWidth--}
```
public int getWidth()
```


इस Bitmap की चौड़ाई, पिक्सेल में, प्राप्त करता है।

**Returns:**
int
### getHeight() {#getHeight--}
```
public int getHeight()
```


इस Bitmap की ऊँचाई, पिक्सेल में, प्राप्त करता है।

**Returns:**
int
### getRawFormat() {#getRawFormat--}
```
public ImageFormat getRawFormat()
```


इस [Image](../../com.aspose.drawing/image) का फ़ाइल फ़ॉर्मेट प्राप्त करता है।

**Returns:**
[ImageFormat](../../com.aspose.drawing.imaging/imageformat) - The [ImageFormat](../../com.aspose.drawing.imaging/imageformat) that represents the file format of this [Image](../../com.aspose.drawing/image).
### getPixelFormat() {#getPixelFormat--}
```
public int getPixelFormat()
```


इस [Image](../../com.aspose.drawing/image) का पिक्सेल फ़ॉर्मेट प्राप्त करता है।

**Returns:**
int - एक `PixelFormat`([Image.getPixelFormat](../../com.aspose.drawing/image\#getPixelFormat)) जो इस [Image](../../com.aspose.drawing/image) के पिक्सेल फ़ॉर्मेट को दर्शाता है।
### getPalette() {#getPalette--}
```
public ColorPalette getPalette()
```


इस [Image](../../com.aspose.drawing/image) के लिए उपयोग किए जाने वाले रंग पैलेट को प्राप्त करता है या सेट करता है।

**Returns:**
[ColorPalette](../../com.aspose.drawing.imaging/colorpalette) - A [ColorPalette](../../com.aspose.drawing.imaging/colorpalette) that represents the color palette used for this [Image](../../com.aspose.drawing/image).
### setPalette(ColorPalette value) {#setPalette-com.aspose.drawing.imaging.ColorPalette-}
```
public void setPalette(ColorPalette value)
```


इस [Image](../../com.aspose.drawing/image) के लिए उपयोग किए जाने वाले रंग पैलेट को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [ColorPalette](../../com.aspose.drawing.imaging/colorpalette) |  |

### getFrameDimensionsList() {#getFrameDimensionsList--}
```
public UUID[] getFrameDimensionsList()
```


इस [Image](../../com.aspose.drawing/image) के भीतर फ्रेमों के आयामों को दर्शाने वाले GUIDs की एक सरणी प्राप्त करता है।

**Returns:**
java.util.UUID[] - GUIDs की एक एरे जो इस [Image](../../com.aspose.drawing/image) के फ्रेमों के आयामों को सबसे महत्वपूर्ण से कम महत्वपूर्ण तक निर्दिष्ट करती है।
### getPropertyIdList() {#getPropertyIdList--}
```
public int[] getPropertyIdList()
```


इस [Image](../../com.aspose.drawing/image) में संग्रहीत प्रॉपर्टी आइटम्स के IDs प्राप्त करता है।

**Returns:**
int[] - प्रॉपर्टी IDs की एरे, प्रत्येक प्रॉपर्टी आइटम के लिए एक, जो इस इमेज में संग्रहीत है।
### getPropertyItems() {#getPropertyItems--}
```
public PropertyItem[] getPropertyItems()
```


इस [Image](../../com.aspose.drawing/image) में संग्रहीत सभी प्रॉपर्टी आइटम्स (मेटाडेटा के टुकड़े) प्राप्त करता है।

**Returns:**
com.aspose.drawing.imaging.PropertyItem[] - [PropertyItem](../../com.aspose.drawing.imaging/propertyitem) ऑब्जेक्ट्स की एरे, प्रत्येक प्रॉपर्टी आइटम के लिए एक, जो इमेज में संग्रहीत है।
### deepClone(Rectangle rect, int format) {#deepClone-com.aspose.drawing.Rectangle-int-}
```
public final Bitmap deepClone(Rectangle rect, int format)
```


इस [Bitmap](../../com.aspose.drawing/bitmap) के उस भाग की एक कॉपी बनाता है जो [Rectangle](../../com.aspose.drawing/rectangle) संरचना द्वारा परिभाषित है और निर्दिष्ट `PixelFormat`([Image.getPixelFormat](../../com.aspose.drawing/image\#getPixelFormat)) एनेमरेशन के साथ।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | इस [Bitmap](../../com.aspose.drawing/bitmap) के उस भाग को परिभाषित करता है जिसे कॉपी किया जाना है। निर्देशांक इस [Bitmap](../../com.aspose.drawing/bitmap) के सापेक्ष हैं। |
| format | int | `PixelFormat`([Image.getPixelFormat](../../com.aspose.drawing/image\#getPixelFormat)) enumeration गंतव्य [Bitmap](../../com.aspose.drawing/bitmap) के लिए निर्दिष्ट करता है। |

**Returns:**
[Bitmap](../../com.aspose.drawing/bitmap) - The new [Bitmap](../../com.aspose.drawing/bitmap) that this method creates.
### deepClone(RectangleF rect, int format) {#deepClone-com.aspose.drawing.RectangleF-int-}
```
public final Bitmap deepClone(RectangleF rect, int format)
```


निर्दिष्ट [PixelFormat](../../com.aspose.drawing.imaging/pixelformat) एनेमरेशन के साथ परिभाषित इस [Bitmap](../../com.aspose.drawing/bitmap) के भाग की एक कॉपी बनाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | इस [Bitmap](../../com.aspose.drawing/bitmap) के उस भाग को परिभाषित करता है जिसे कॉपी किया जाना है। |
| format | int | [PixelFormat](../../com.aspose.drawing.imaging/pixelformat) enumeration गंतव्य [Bitmap](../../com.aspose.drawing/bitmap) के लिए निर्दिष्ट करता है। |

**Returns:**
[Bitmap](../../com.aspose.drawing/bitmap) - The [Bitmap](../../com.aspose.drawing/bitmap) that this method creates.
### setResolution(float xDpi, float yDpi) {#setResolution-float-float-}
```
public final void setResolution(float xDpi, float yDpi)
```


इस [Bitmap](../../com.aspose.drawing/bitmap) के लिए रिज़ॉल्यूशन सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| xDpi | float | यह [Bitmap](../../com.aspose.drawing/bitmap) की क्षैतिज रिज़ॉल्यूशन, डॉट्स प्रति इंच में है। |
| yDpi | float | यह [Bitmap](../../com.aspose.drawing/bitmap) की लंबवत रिज़ॉल्यूशन, डॉट्स प्रति इंच में है। |

### lockBits(Rectangle rect, int flags, int format) {#lockBits-com.aspose.drawing.Rectangle-int-int-}
```
public final BitmapData lockBits(Rectangle rect, int flags, int format)
```


सिस्टम मेमोरी में एक [Bitmap](../../com.aspose.drawing/bitmap) को लॉक करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | एक [Rectangle](../../com.aspose.drawing/rectangle) संरचना जो [Bitmap](../../com.aspose.drawing/bitmap) के उस भाग को निर्दिष्ट करती है जिसे लॉक किया जाना है। |
| flags | int | एक [ImageLockMode](../../com.aspose.drawing.imaging/imagelockmode) enumeration जो [Bitmap](../../com.aspose.drawing/bitmap) के लिए एक्सेस स्तर (पढ़ना/लिखना) निर्दिष्ट करती है। |
| format | int | `PixelFormat`([Image.getPixelFormat](../../com.aspose.drawing/image\#getPixelFormat)) enumeration इस [Bitmap](../../com.aspose.drawing/bitmap) के डेटा फ़ॉर्मेट को निर्दिष्ट करती है। |

**Returns:**
[BitmapData](../../com.aspose.drawing.imaging/bitmapdata) - A [BitmapData](../../com.aspose.drawing.imaging/bitmapdata) containing information about this lock operation.
### unlockBits(BitmapData bitmapData) {#unlockBits-com.aspose.drawing.imaging.BitmapData-}
```
public final void unlockBits(BitmapData bitmapData)
```


सिस्टम मेमोरी से इस [Bitmap](../../com.aspose.drawing/bitmap) को अनलॉक करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| bitmapData | [BitmapData](../../com.aspose.drawing.imaging/bitmapdata) | एक [BitmapData](../../com.aspose.drawing.imaging/bitmapdata) जो लॉक ऑपरेशन के बारे में जानकारी निर्दिष्ट करता है। |

### getPixel(int x, int y) {#getPixel-int-int-}
```
public final Color getPixel(int x, int y)
```


इस [Bitmap](../../com.aspose.drawing/bitmap) में निर्दिष्ट पिक्सेल का रंग प्राप्त करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | int | पिक्सेल को प्राप्त करने के लिए x-निर्देशांक। |
| y | int | पिक्सेल को प्राप्त करने के लिए y-निर्देशांक। |

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) structure that represents the color of the specified pixel.
### setPixel(int x, int y, Color color) {#setPixel-int-int-com.aspose.drawing.Color-}
```
public final void setPixel(int x, int y, Color color)
```


इस [Bitmap](../../com.aspose.drawing/bitmap) में निर्दिष्ट पिक्सेल का रंग सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | int | पिक्सेल को सेट करने के लिए x-निर्देशांक। |
| y | int | पिक्सेल को सेट करने के लिए y-निर्देशांक। |
| color | [Color](../../com.aspose.drawing/color) | एक [Color](../../com.aspose.drawing/color) संरचना जो निर्दिष्ट पिक्सेल को सौंपे जाने वाले रंग को दर्शाती है। |

### readArgb32Pixels(int[] pixels) {#readArgb32Pixels-int---}
```
public final void readArgb32Pixels(int[] pixels)
```


दिए गए एरे में ARGB32 फ़ॉर्मेट में बिटमैप पिक्सेल पढ़ता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| पिक्सेल | int[] | बिटमैप पिक्सेल रखने के लिए एरे। इसमें पर्याप्त क्षमता होनी चाहिए। |

### writeArgb32Pixels(int[] pixels) {#writeArgb32Pixels-int---}
```
public final void writeArgb32Pixels(int[] pixels)
```


बिटमैप में पिक्सेल लिखता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| पिक्सेल | int[] | ARGB32 फ़ॉर्मेट में स्रोत पिक्सेल वाला एरे। इसमें पर्याप्त लंबाई होनी चाहिए। |

### makeTransparent() {#makeTransparent--}
```
public final void makeTransparent()
```


इस [Bitmap](../../com.aspose.drawing/bitmap) के लिए निर्दिष्ट रंग को पारदर्शी बनाता है।

### makeTransparent(Color transparentColor) {#makeTransparent-com.aspose.drawing.Color-}
```
public final void makeTransparent(Color transparentColor)
```


इस [Bitmap](../../com.aspose.drawing/bitmap) के लिए निर्दिष्ट रंग को पारदर्शी बनाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| transparentColor | [Color](../../com.aspose.drawing/color) | यह [Color](../../com.aspose.drawing/color) संरचना जो पारदर्शी बनाने के लिए रंग को दर्शाती है। |

### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


यह मेथड [Image](../../com.aspose.drawing/image) को घुमाता, उलटता, या घुमाकर उलटता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rotateFlipType | int | एक [RotateFlipType](../../com.aspose.drawing/rotatefliptype) सदस्य जो इमेज पर लागू होने वाले रोटेशन और फ्लिप के प्रकार को निर्दिष्ट करता है। |

### getPropertyItem(int propid) {#getPropertyItem-int-}
```
public PropertyItem getPropertyItem(int propid)
```


इस [Image](../../com.aspose.drawing/image) से निर्दिष्ट प्रॉपर्टी आइटम प्राप्त करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| propid | int | प्राप्त करने के लिए प्रॉपर्टी आइटम की आईडी। |

**Returns:**
[PropertyItem](../../com.aspose.drawing.imaging/propertyitem) - The [PropertyItem](../../com.aspose.drawing.imaging/propertyitem) this method gets.
### removePropertyItem(int propid) {#removePropertyItem-int-}
```
public void removePropertyItem(int propid)
```


इस [Image](../../com.aspose.drawing/image) से निर्दिष्ट प्रॉपर्टी आइटम को हटाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| propid | int | हटाने के लिए प्रॉपर्टी आइटम की आईडी। |

### setPropertyItem(PropertyItem propitem) {#setPropertyItem-com.aspose.drawing.imaging.PropertyItem-}
```
public void setPropertyItem(PropertyItem propitem)
```


इस [Image](../../com.aspose.drawing/image) में एक प्रॉपर्टी आइटम (मेटाडेटा का टुकड़ा) संग्रहीत करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| propitem | [PropertyItem](../../com.aspose.drawing.imaging/propertyitem) | सहेजे जाने वाले [PropertyItem](../../com.aspose.drawing.imaging/propertyitem)। |

