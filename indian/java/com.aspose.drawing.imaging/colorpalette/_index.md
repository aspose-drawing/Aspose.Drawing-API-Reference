---
title: ColorPalette
second_title: Aspose.Drawing for Java API संदर्भ
description: रंग पैलेट बनाते हुए रंगों की एक सरणी को परिभाषित करता है।
type: docs
weight: 16
url: /hi/java/com.aspose.drawing.imaging/colorpalette/
---
**Inheritance:**
java.lang.Object
```
public final class ColorPalette
```

रंग पैलेट बनाने वाले रंगों की एक एरे को परिभाषित करता है। ये रंग 32-बिट ARGB रंग हैं। विरासत में नहीं मिलते।
## निर्माता

| निर्माता | विवरण |
| --- | --- |
| [ColorPalette(int count)](#ColorPalette-int-) | `ColorPalette` क्लास का नया इंस्टेंस इनिशियलाइज़ करता है और IsCompactPalette false है। |
## मेथड्स

| विधि | विवरण |
| --- | --- |
| [getEntries()](#getEntries--) | `com.aspose.drawing.Color` संरचनाओं की एक एरे प्राप्त करता है। |
| [isCompactPalette()](#isCompactPalette--) | एक मान प्राप्त करता या सेट करता है जो दर्शाता है कि कॉम्पैक्ट पैलेट उपयोग किया गया है या नहीं। |
| [getFlags()](#getFlags--) |  |
| [setFlags(int flags)](#setFlags-int-) |  |
| [setEntries(int i, Color color)](#setEntries-int-com.aspose.drawing.Color-) |  |
### ColorPalette(int count) {#ColorPalette-int-}
```
public ColorPalette(int count)
```


`ColorPalette` क्लास का नया इंस्टेंस इनिशियलाइज़ करता है और IsCompactPalette false है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| count | int | रंग पैलेट प्रविष्टियाँ। |

### getEntries() {#getEntries--}
```
public Color[] getEntries()
```


`com.aspose.drawing.Color` संरचनाओं की एक एरे प्राप्त करता है।

**Returns:**
com.aspose.drawing.Color[] - प्रविष्टियाँ। `com.aspose.drawing.Color` संरचनाओं की एरे जो इस `Aspose.Imaging.ColorPalette` को बनाती है।
### isCompactPalette() {#isCompactPalette--}
```
public boolean isCompactPalette()
```


एक मान प्राप्त करता या सेट करता है जो दर्शाता है कि कॉम्पैक्ट पैलेट उपयोग किया गया है या नहीं।

**Returns:**
boolean - यदि कॉम्पैक्ट पैलेट उपयोग किया गया है तो `true`; अन्यथा `false`।

कॉम्पैक्ट पैलेट का अर्थ है कि छवि केवल निर्दिष्ट पैलेट प्रविष्टियों को ही रखेगी यदि संभव हो, अर्थात् छवि अधिक कॉम्पैक्ट होगी और कम स्थान घेरेंगी; अन्यथा 2^BitsPerPixel प्रविष्टियाँ होंगी और छवि सभी संभावित पैलेट प्रविष्टियों के लिए अधिक स्थान आरक्षित करेगी। इस मान को true सेट करना और पैलेट प्रविष्टियों को बदलना प्रदर्शन पर दंड लगा सकता है क्योंकि डेटा मूवमेंट हो सकता है, इसलिए इसे सावधानीपूर्वक उपयोग करें।
### getFlags() {#getFlags--}
```
public int getFlags()
```




**Returns:**
int
### setFlags(int flags) {#setFlags-int-}
```
public void setFlags(int flags)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| flags | int |  |

### setEntries(int i, Color color) {#setEntries-int-com.aspose.drawing.Color-}
```
public void setEntries(int i, Color color)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| i | int |  |
| color | [Color](../../com.aspose.drawing/color) |  |

