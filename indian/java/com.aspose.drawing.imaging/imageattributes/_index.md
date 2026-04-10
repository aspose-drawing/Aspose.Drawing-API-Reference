---
title: ImageAttributes
second_title: Aspose.Drawing for Java API संदर्भ
description: रेंडरिंग के दौरान बिटमैप और मेटाफाइल रंगों को कैसे संशोधित किया जाता है, इस बारे में जानकारी शामिल करता है।
type: docs
weight: 24
url: /hi/java/com.aspose.drawing.imaging/imageattributes/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public final class ImageAttributes implements System.IDisposable
```

रेंडरिंग के दौरान बिटमैप और मेटाफाइल रंगों को कैसे संशोधित किया जाता है, इस बारे में जानकारी शामिल करता है।
## निर्माता

| निर्माता | विवरण |
| --- | --- |
| [ImageAttributes()](#ImageAttributes--) | [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes) क्लास का नया इंस्टेंस प्रारंभ करता है। |
## मेथड्स

| विधि | विवरण |
| --- | --- |
| [dispose()](#dispose--) | इस [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes) ऑब्जेक्ट द्वारा उपयोग किए गए सभी संसाधनों को मुक्त करता है। |
| [deepClone()](#deepClone--) | इस [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes) ऑब्जेक्ट की एक सटीक प्रति बनाता है। |
| [setColorMatrix(ColorMatrix newColorMatrix)](#setColorMatrix-com.aspose.drawing.imaging.ColorMatrix-) | डिफ़ॉल्ट श्रेणी के लिए रंग-समायोजन मैट्रिक्स सेट करता है। |
| [setColorMatrix(ColorMatrix newColorMatrix, int flags)](#setColorMatrix-com.aspose.drawing.imaging.ColorMatrix-int-) | डिफ़ॉल्ट श्रेणी के लिए रंग-समायोजन मैट्रिक्स सेट करता है। |
| [setColorMatrix(ColorMatrix newColorMatrix, int mode, int type)](#setColorMatrix-com.aspose.drawing.imaging.ColorMatrix-int-int-) | निर्दिष्ट श्रेणी के लिए रंग-समायोजन मैट्रिक्स सेट करता है। |
| [clearColorMatrix()](#clearColorMatrix--) | डिफ़ॉल्ट श्रेणी के लिए color-adjustment matrix को साफ़ करता है। |
| [clearColorMatrix(int type)](#clearColorMatrix-int-) | निर्दिष्ट श्रेणी के लिए color-adjustment matrix को साफ़ करता है। |
| [setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix)](#setColorMatrices-com.aspose.drawing.imaging.ColorMatrix-com.aspose.drawing.imaging.ColorMatrix-) | डिफ़ॉल्ट श्रेणी के लिए color-adjustment matrix और grayscale-adjustment matrix सेट करता है। |
| [setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int flags)](#setColorMatrices-com.aspose.drawing.imaging.ColorMatrix-com.aspose.drawing.imaging.ColorMatrix-int-) | डिफ़ॉल्ट श्रेणी के लिए color-adjustment matrix और grayscale-adjustment matrix सेट करता है। |
| [setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int mode, int type)](#setColorMatrices-com.aspose.drawing.imaging.ColorMatrix-com.aspose.drawing.imaging.ColorMatrix-int-int-) | निर्दिष्ट श्रेणी के लिए color-adjustment matrix और grayscale-adjustment matrix सेट करता है। |
| [setThreshold(float threshold)](#setThreshold-float-) | डिफ़ॉल्ट श्रेणी के लिए थ्रेशहोल्ड (पारदर्शिता रेंज) सेट करता है। |
| [setThreshold(float threshold, int type)](#setThreshold-float-int-) | निर्दिष्ट श्रेणी के लिए थ्रेशहोल्ड (पारदर्शिता रेंज) सेट करता है। |
| [clearThreshold()](#clearThreshold--) | डिफ़ॉल्ट श्रेणी के लिए थ्रेशहोल्ड मान को साफ़ करता है। |
| [clearThreshold(int type)](#clearThreshold-int-) | निर्दिष्ट श्रेणी के लिए थ्रेशहोल्ड मान को साफ़ करता है। |
| [setGamma(float gamma)](#setGamma-float-) | डिफ़ॉल्ट श्रेणी के लिए गामा मान सेट करता है। |
| [setGamma(float gamma, int type)](#setGamma-float-int-) | निर्दिष्ट श्रेणी के लिए गामा मान सेट करता है। |
| [clearGamma()](#clearGamma--) | डिफ़ॉल्ट श्रेणी के लिए गामा सुधार को निष्क्रिय करता है। |
| [clearGamma(int type)](#clearGamma-int-) | निर्दिष्ट श्रेणी के लिए गामा सुधार को निष्क्रिय करता है। |
| [setNoOp()](#setNoOp--) | डिफ़ॉल्ट श्रेणी के लिए रंग समायोजन को बंद करता है। |
| [setNoOp(int type)](#setNoOp-int-) | निर्दिष्ट श्रेणी के लिए रंग समायोजन को बंद करता है। |
| [clearNoOp()](#clearNoOp--) | डिफ़ॉल्ट श्रेणी के लिए NoOp सेटिंग को साफ़ करता है। |
| [clearNoOp(int type)](#clearNoOp-int-) | निर्दिष्ट श्रेणी के लिए NoOp सेटिंग को साफ़ करता है। |
| [setColorKey(Color colorLow, Color colorHigh)](#setColorKey-com.aspose.drawing.Color-com.aspose.drawing.Color-) | डिफ़ॉल्ट श्रेणी के लिए कलर की सेट करता है। |
| [setColorKey(Color colorLow, Color colorHigh, int type)](#setColorKey-com.aspose.drawing.Color-com.aspose.drawing.Color-int-) | निर्दिष्ट श्रेणी के लिए कलर की (पारदर्शिता रेंज) सेट करता है। |
| [clearColorKey()](#clearColorKey--) | डिफ़ॉल्ट श्रेणी के लिए कलर की (पारदर्शिता रेंज) को साफ़ करता है। |
| [clearColorKey(int type)](#clearColorKey-int-) | निर्दिष्ट श्रेणी के लिए कलर की (पारदर्शिता रेंज) को साफ़ करता है। |
| [setOutputChannel(int flags)](#setOutputChannel-int-) | डिफ़ॉल्ट श्रेणी के लिए CMYK (सियान-मैजेंटा-येलो-ब्लैक) आउटपुट चैनल सेट करता है। |
| [setOutputChannel(int flags, int type)](#setOutputChannel-int-int-) | निर्दिष्ट श्रेणी के लिए CMYK (सियान-मैजेंटा-येलो-ब्लैक) आउटपुट चैनल सेट करता है। |
| [clearOutputChannel()](#clearOutputChannel--) | डिफ़ॉल्ट श्रेणी के लिए CMYK (सियान-मैजेंटा-येलो-ब्लैक) आउटपुट चैनल सेटिंग को साफ़ करता है। |
| [clearOutputChannel(int type)](#clearOutputChannel-int-) | निर्दिष्ट श्रेणी के लिए (सियान-मैजेंटा-येलो-ब्लैक) आउटपुट चैनल सेटिंग को साफ़ करता है। |
| [setOutputChannelColorProfile(String colorProfileFilename)](#setOutputChannelColorProfile-java.lang.String-) | डिफ़ॉल्ट श्रेणी के लिए आउटपुट चैनल कलर-प्रोफ़ाइल फ़ाइल सेट करता है। |
| [setOutputChannelColorProfile(String colorProfileFilename, int type)](#setOutputChannelColorProfile-java.lang.String-int-) | निर्दिष्ट श्रेणी के लिए आउटपुट चैनल कलर‑प्रोफ़ाइल फ़ाइल सेट करता है। |
| [clearOutputChannelColorProfile()](#clearOutputChannelColorProfile--) | डिफ़ॉल्ट श्रेणी के लिए आउटपुट चैनल कलर प्रोफ़ाइल सेटिंग को साफ़ करता है। |
| [clearOutputChannelColorProfile(int type)](#clearOutputChannelColorProfile-int-) | निर्दिष्ट श्रेणी के लिए आउटपुट चैनल कलर प्रोफ़ाइल सेटिंग को साफ़ करता है। |
| [setRemapTable(ColorMap[] map)](#setRemapTable-com.aspose.drawing.imaging.ColorMap---) | डिफ़ॉल्ट श्रेणी के लिए कलर‑रीमैप तालिका सेट करता है। |
| [setRemapTable(ColorMap[] map, int type)](#setRemapTable-com.aspose.drawing.imaging.ColorMap---int-) | निर्दिष्ट श्रेणी के लिए कलर‑रीमैप तालिका सेट करता है। |
| [clearRemapTable()](#clearRemapTable--) | डिफ़ॉल्ट श्रेणी के लिए कलर‑रीमैप तालिका को साफ़ करता है। |
| [clearRemapTable(int type)](#clearRemapTable-int-) | निर्दिष्ट श्रेणी के लिए कलर‑रीमैप तालिका को साफ़ करता है। |
| [setBrushRemapTable(ColorMap[] map)](#setBrushRemapTable-com.aspose.drawing.imaging.ColorMap---) | ब्रश श्रेणी के लिए कलर‑रीमैप तालिका सेट करता है। |
| [clearBrushRemapTable()](#clearBrushRemapTable--) | इस [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes) ऑब्जेक्ट की ब्रश कलर‑रीमैप तालिका को साफ़ करता है। |
| [setWrapMode(int mode)](#setWrapMode-int-) | रैप मोड सेट करता है जिसका उपयोग यह तय करने के लिए किया जाता है कि टेक्सचर को आकार के ऊपर या आकार की सीमाओं पर कैसे टाइल किया जाए। |
| [setWrapMode(int mode, Color color)](#setWrapMode-int-com.aspose.drawing.Color-) | रैप मोड और रंग सेट करता है जिसका उपयोग यह तय करने के लिए किया जाता है कि टेक्सचर को आकार के ऊपर या आकार की सीमाओं पर कैसे टाइल किया जाए। |
| [setWrapMode(int mode, Color color, boolean clamp)](#setWrapMode-int-com.aspose.drawing.Color-boolean-) | रैप मोड और रंग सेट करता है जिसका उपयोग यह तय करने के लिए किया जाता है कि टेक्सचर को आकार के ऊपर या आकार की सीमाओं पर कैसे टाइल किया जाए। |
| [getAdjustedPalette(ColorPalette palette, int type)](#getAdjustedPalette-com.aspose.drawing.imaging.ColorPalette-int-) | निर्दिष्ट श्रेणी की समायोजन सेटिंग्स के अनुसार पैलेट में रंगों को समायोजित करता है। |
### ImageAttributes() {#ImageAttributes--}
```
public ImageAttributes()
```


[ImageAttributes](../../com.aspose.drawing.imaging/imageattributes) क्लास का नया इंस्टेंस प्रारंभ करता है।

### dispose() {#dispose--}
```
public void dispose()
```


इस [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes) ऑब्जेक्ट द्वारा उपयोग किए गए सभी संसाधनों को मुक्त करता है।

### deepClone() {#deepClone--}
```
public Object deepClone()
```


इस [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes) ऑब्जेक्ट की एक सटीक प्रति बनाता है।

**Returns:**
java.lang.Object - यह क्लास द्वारा निर्मित [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes) ऑब्जेक्ट, जिसे ऑब्जेक्ट के रूप में कास्ट किया गया है।
### setColorMatrix(ColorMatrix newColorMatrix) {#setColorMatrix-com.aspose.drawing.imaging.ColorMatrix-}
```
public void setColorMatrix(ColorMatrix newColorMatrix)
```


डिफ़ॉल्ट श्रेणी के लिए रंग-समायोजन मैट्रिक्स सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) | कलर‑एडजस्टमेंट मैट्रिक्स। |

### setColorMatrix(ColorMatrix newColorMatrix, int flags) {#setColorMatrix-com.aspose.drawing.imaging.ColorMatrix-int-}
```
public void setColorMatrix(ColorMatrix newColorMatrix, int flags)
```


डिफ़ॉल्ट श्रेणी के लिए रंग-समायोजन मैट्रिक्स सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) | कलर‑एडजस्टमेंट मैट्रिक्स। |
| flags | int | [ColorMatrixFlag](../../com.aspose.drawing.imaging/colormatrixflag) का एक तत्व जो उस इमेज और रंग के प्रकार को निर्दिष्ट करता है जिस पर कलर‑एडजस्टमेंट मैट्रिक्स का प्रभाव पड़ेगा। |

### setColorMatrix(ColorMatrix newColorMatrix, int mode, int type) {#setColorMatrix-com.aspose.drawing.imaging.ColorMatrix-int-int-}
```
public void setColorMatrix(ColorMatrix newColorMatrix, int mode, int type)
```


निर्दिष्ट श्रेणी के लिए रंग-समायोजन मैट्रिक्स सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) | कलर‑एडजस्टमेंट मैट्रिक्स। |
| mode | int | [ColorMatrixFlag](../../com.aspose.drawing.imaging/colormatrixflag) का एक तत्व जो उस इमेज और रंग के प्रकार को निर्दिष्ट करता है जिस पर कलर‑एडजस्टमेंट मैट्रिक्स का प्रभाव पड़ेगा। |
| type | int | [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) का एक तत्व जो उस श्रेणी को निर्दिष्ट करता है जिसके लिए कलर‑एडजस्टमेंट मैट्रिक्स सेट किया गया है। |

### clearColorMatrix() {#clearColorMatrix--}
```
public void clearColorMatrix()
```


डिफ़ॉल्ट श्रेणी के लिए color-adjustment matrix को साफ़ करता है।

### clearColorMatrix(int type) {#clearColorMatrix-int-}
```
public void clearColorMatrix(int type)
```


निर्दिष्ट श्रेणी के लिए color-adjustment matrix को साफ़ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| type | int | [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) का एक तत्व जो उस श्रेणी को निर्दिष्ट करता है जिसके लिए कलर‑एडजस्टमेंट मैट्रिक्स को साफ़ किया गया है। |

### setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix) {#setColorMatrices-com.aspose.drawing.imaging.ColorMatrix-com.aspose.drawing.imaging.ColorMatrix-}
```
public void setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix)
```


डिफ़ॉल्ट श्रेणी के लिए color-adjustment matrix और grayscale-adjustment matrix सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) | कलर‑एडजस्टमेंट मैट्रिक्स। |
| grayMatrix | [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) | ग्रेस्केल‑एडजस्टमेंट मैट्रिक्स। |

### setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int flags) {#setColorMatrices-com.aspose.drawing.imaging.ColorMatrix-com.aspose.drawing.imaging.ColorMatrix-int-}
```
public void setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int flags)
```


डिफ़ॉल्ट श्रेणी के लिए color-adjustment matrix और grayscale-adjustment matrix सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) | कलर‑एडजस्टमेंट मैट्रिक्स। |
| grayMatrix | [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) | ग्रेस्केल‑एडजस्टमेंट मैट्रिक्स। |
| flags | int | [ColorMatrixFlag](../../com.aspose.drawing.imaging/colormatrixflag) का एक तत्व जो उस इमेज और रंग के प्रकार को निर्दिष्ट करता है जिस पर कलर‑एडजस्टमेंट और ग्रेस्केल‑एडजस्टमेंट मैट्रिक्स का प्रभाव पड़ेगा। |

### setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int mode, int type) {#setColorMatrices-com.aspose.drawing.imaging.ColorMatrix-com.aspose.drawing.imaging.ColorMatrix-int-int-}
```
public void setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int mode, int type)
```


निर्दिष्ट श्रेणी के लिए color-adjustment matrix और grayscale-adjustment matrix सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) | कलर‑एडजस्टमेंट मैट्रिक्स। |
| grayMatrix | [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) | ग्रेस्केल‑एडजस्टमेंट मैट्रिक्स। |
| mode | int | [ColorMatrixFlag](../../com.aspose.drawing.imaging/colormatrixflag) का एक तत्व जो उस इमेज और रंग के प्रकार को निर्दिष्ट करता है जिस पर कलर‑एडजस्टमेंट और ग्रेस्केल‑एडजस्टमेंट मैट्रिक्स का प्रभाव पड़ेगा। |
| type | int | [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) का एक तत्व जो उस श्रेणी को निर्दिष्ट करता है जिसके लिए कलर‑एडजस्टमेंट और ग्रेस्केल‑एडजस्टमेंट मैट्रिक्स सेट किए गए हैं। |

### setThreshold(float threshold) {#setThreshold-float-}
```
public void setThreshold(float threshold)
```


डिफ़ॉल्ट श्रेणी के लिए थ्रेशहोल्ड (पारदर्शिता रेंज) सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| थ्रेशहोल्ड | फ़्लोट | एक वास्तविक संख्या जो थ्रेशहोल्ड मान निर्दिष्ट करती है। |

### setThreshold(float threshold, int type) {#setThreshold-float-int-}
```
public void setThreshold(float threshold, int type)
```


निर्दिष्ट श्रेणी के लिए थ्रेशहोल्ड (पारदर्शिता रेंज) सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| थ्रेशहोल्ड | फ़्लोट | 0.0 से 1.0 के बीच का थ्रेशहोल्ड मान, जिसका उपयोग रंगों को इस प्रकार क्रमबद्ध करने के लिए किया जाता है कि उन्हें अधिकतम या न्यूनतम मान में मैप किया जाए। |
| type | int | [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) का एक तत्व जो उस श्रेणी को निर्दिष्ट करता है जिसके लिए कलर थ्रेशहोल्ड सेट किया गया है। |

### clearThreshold() {#clearThreshold--}
```
public void clearThreshold()
```


डिफ़ॉल्ट श्रेणी के लिए थ्रेशहोल्ड मान को साफ़ करता है।

### clearThreshold(int type) {#clearThreshold-int-}
```
public void clearThreshold(int type)
```


निर्दिष्ट श्रेणी के लिए थ्रेशहोल्ड मान को साफ़ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| type | int | [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) का एक तत्व जो उस श्रेणी को निर्दिष्ट करता है जिसके लिए थ्रेशहोल्ड को साफ़ किया गया है। |

### setGamma(float gamma) {#setGamma-float-}
```
public void setGamma(float gamma)
```


डिफ़ॉल्ट श्रेणी के लिए गामा मान सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| गामा | फ़्लोट | गामा सुधार मान। |

### setGamma(float gamma, int type) {#setGamma-float-int-}
```
public void setGamma(float gamma, int type)
```


निर्दिष्ट श्रेणी के लिए गामा मान सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| गामा | फ़्लोट | गामा सुधार मान। |
| type | int | एक तत्व [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) एन्यूमरेशन का जो उस वर्ग को निर्दिष्ट करता है जिसके लिए गामा मान सेट किया जाता है। |

### clearGamma() {#clearGamma--}
```
public void clearGamma()
```


डिफ़ॉल्ट श्रेणी के लिए गामा सुधार को निष्क्रिय करता है।

### clearGamma(int type) {#clearGamma-int-}
```
public void clearGamma(int type)
```


निर्दिष्ट श्रेणी के लिए गामा सुधार को निष्क्रिय करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| type | int | एक तत्व [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) जो उस वर्ग को निर्दिष्ट करता है जिसके लिए गामा सुधार अक्षम किया गया है। |

### setNoOp() {#setNoOp--}
```
public void setNoOp()
```


डिफ़ॉल्ट वर्ग के लिए रंग समायोजन को बंद करता है। आप [.clearNoOp](../../null/\#clearNoOp) मेथड को कॉल करके उन रंग‑समायोजन सेटिंग्स को पुनर्स्थापित कर सकते हैं जो [.setNoOp](../../null/\#setNoOp) मेथड को कॉल करने से पहले लागू थीं।

### setNoOp(int type) {#setNoOp-int-}
```
public void setNoOp(int type)
```


निर्दिष्ट वर्ग के लिए रंग समायोजन को बंद करता है। आप [.clearNoOp](../../null/\#clearNoOp) मेथड को कॉल करके उन रंग‑समायोजन सेटिंग्स को पुनर्स्थापित कर सकते हैं जो [.setNoOp](../../null/\#setNoOp) मेथड को कॉल करने से पहले लागू थीं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| type | int | एक तत्व [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) जो उस वर्ग को निर्दिष्ट करता है जिसके लिए रंग सुधार बंद किया गया है। |

### clearNoOp() {#clearNoOp--}
```
public void clearNoOp()
```


डिफ़ॉल्ट श्रेणी के लिए NoOp सेटिंग को साफ़ करता है।

### clearNoOp(int type) {#clearNoOp-int-}
```
public void clearNoOp(int type)
```


निर्दिष्ट श्रेणी के लिए NoOp सेटिंग को साफ़ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| type | int | एक तत्व [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) जो उस वर्ग को निर्दिष्ट करता है जिसके लिए NoOp सेटिंग साफ़ की गई है। |

### setColorKey(Color colorLow, Color colorHigh) {#setColorKey-com.aspose.drawing.Color-com.aspose.drawing.Color-}
```
public void setColorKey(Color colorLow, Color colorHigh)
```


डिफ़ॉल्ट श्रेणी के लिए कलर की सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| colorLow | [Color](../../com.aspose.drawing/color) | निम्न रंग‑की मान। |
| colorHigh | [Color](../../com.aspose.drawing/color) | उच्च रंग‑की मान। |

### setColorKey(Color colorLow, Color colorHigh, int type) {#setColorKey-com.aspose.drawing.Color-com.aspose.drawing.Color-int-}
```
public void setColorKey(Color colorLow, Color colorHigh, int type)
```


निर्दिष्ट श्रेणी के लिए कलर की (पारदर्शिता रेंज) सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| colorLow | [Color](../../com.aspose.drawing/color) | निम्न रंग‑की मान। |
| colorHigh | [Color](../../com.aspose.drawing/color) | उच्च रंग‑की मान। |
| type | int | एक तत्व [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) जो उस वर्ग को निर्दिष्ट करता है जिसके लिए रंग‑की सेट किया गया है। |

### clearColorKey() {#clearColorKey--}
```
public void clearColorKey()
```


डिफ़ॉल्ट श्रेणी के लिए कलर की (पारदर्शिता रेंज) को साफ़ करता है।

### clearColorKey(int type) {#clearColorKey-int-}
```
public void clearColorKey(int type)
```


निर्दिष्ट श्रेणी के लिए कलर की (पारदर्शिता रेंज) को साफ़ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| type | int | एक तत्व [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) जो उस वर्ग को निर्दिष्ट करता है जिसके लिए रंग‑की साफ़ की गई है। |

### setOutputChannel(int flags) {#setOutputChannel-int-}
```
public void setOutputChannel(int flags)
```


डिफ़ॉल्ट श्रेणी के लिए CMYK (सियान-मैजेंटा-येलो-ब्लैक) आउटपुट चैनल सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| flags | int | एक तत्व [ColorChannelFlag](../../com.aspose.drawing.imaging/colorchannelflag) जो आउटपुट चैनल को निर्दिष्ट करता है। |

### setOutputChannel(int flags, int type) {#setOutputChannel-int-int-}
```
public void setOutputChannel(int flags, int type)
```


निर्दिष्ट श्रेणी के लिए CMYK (सियान-मैजेंटा-येलो-ब्लैक) आउटपुट चैनल सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| flags | int | एक तत्व [ColorChannelFlag](../../com.aspose.drawing.imaging/colorchannelflag) जो आउटपुट चैनल को निर्दिष्ट करता है। |
| type | int | एक तत्व [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) जो उस वर्ग को निर्दिष्ट करता है जिसके लिए आउटपुट चैनल सेट किया गया है। |

### clearOutputChannel() {#clearOutputChannel--}
```
public void clearOutputChannel()
```


डिफ़ॉल्ट श्रेणी के लिए CMYK (सियान-मैजेंटा-येलो-ब्लैक) आउटपुट चैनल सेटिंग को साफ़ करता है।

### clearOutputChannel(int type) {#clearOutputChannel-int-}
```
public void clearOutputChannel(int type)
```


निर्दिष्ट श्रेणी के लिए (सियान-मैजेंटा-येलो-ब्लैक) आउटपुट चैनल सेटिंग को साफ़ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| type | int | एक तत्व [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) जो उस वर्ग को निर्दिष्ट करता है जिसके लिए आउटपुट चैनल सेटिंग साफ़ की गई है। |

### setOutputChannelColorProfile(String colorProfileFilename) {#setOutputChannelColorProfile-java.lang.String-}
```
public void setOutputChannelColorProfile(String colorProfileFilename)
```


डिफ़ॉल्ट श्रेणी के लिए आउटपुट चैनल कलर-प्रोफ़ाइल फ़ाइल सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| colorProfileFilename | java.lang.String | एक रंग‑प्रोफ़ाइल फ़ाइल का पथ नाम। यदि रंग‑प्रोफ़ाइल फ़ाइल %SystemRoot%\\System32\\Spool\\Drivers\\Color निर्देशिका में है, तो यह पैरामीटर फ़ाइल नाम हो सकता है। अन्यथा, इस पैरामीटर को पूर्ण पथ नाम होना चाहिए। |

### setOutputChannelColorProfile(String colorProfileFilename, int type) {#setOutputChannelColorProfile-java.lang.String-int-}
```
public void setOutputChannelColorProfile(String colorProfileFilename, int type)
```


निर्दिष्ट श्रेणी के लिए आउटपुट चैनल कलर‑प्रोफ़ाइल फ़ाइल सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| colorProfileFilename | java.lang.String | एक रंग‑प्रोफ़ाइल फ़ाइल का पथ नाम। यदि रंग‑प्रोफ़ाइल फ़ाइल %SystemRoot%\\System32\\Spool\\Drivers\\Color निर्देशिका में है, तो यह पैरामीटर फ़ाइल नाम हो सकता है। अन्यथा, इस पैरामीटर को पूर्ण पथ नाम होना चाहिए। |
| type | int | एक तत्व [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) जो उस वर्ग को निर्दिष्ट करता है जिसके लिए आउटपुट चैनल रंग‑प्रोफ़ाइल फ़ाइल सेट की गई है। |

### clearOutputChannelColorProfile() {#clearOutputChannelColorProfile--}
```
public void clearOutputChannelColorProfile()
```


डिफ़ॉल्ट श्रेणी के लिए आउटपुट चैनल कलर प्रोफ़ाइल सेटिंग को साफ़ करता है।

### clearOutputChannelColorProfile(int type) {#clearOutputChannelColorProfile-int-}
```
public void clearOutputChannelColorProfile(int type)
```


निर्दिष्ट श्रेणी के लिए आउटपुट चैनल कलर प्रोफ़ाइल सेटिंग को साफ़ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| type | int | एक तत्व [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) जो उस वर्ग को निर्दिष्ट करता है जिसके लिए आउटपुट चैनल प्रोफ़ाइल सेटिंग साफ़ की गई है। |

### setRemapTable(ColorMap[] map) {#setRemapTable-com.aspose.drawing.imaging.ColorMap---}
```
public void setRemapTable(ColorMap[] map)
```


डिफ़ॉल्ट श्रेणी के लिए कलर‑रीमैप तालिका सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| map | [ColorMap\[\]](../../com.aspose.drawing.imaging/colormap) | एक एरे जिसमें [ColorMap](../../com.aspose.drawing.imaging/colormap) प्रकार के रंग जोड़े होते हैं। प्रत्येक रंग जोड़े में एक मौजूदा रंग (पहला मान) और वह रंग (दूसरा मान) होता है जिसमें इसे मैप किया जाएगा। |

### setRemapTable(ColorMap[] map, int type) {#setRemapTable-com.aspose.drawing.imaging.ColorMap---int-}
```
public void setRemapTable(ColorMap[] map, int type)
```


निर्दिष्ट श्रेणी के लिए कलर‑रीमैप तालिका सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| map | [ColorMap\[\]](../../com.aspose.drawing.imaging/colormap) | एक एरे जिसमें [ColorMap](../../com.aspose.drawing.imaging/colormap) प्रकार के रंग जोड़े होते हैं। प्रत्येक रंग जोड़े में एक मौजूदा रंग (पहला मान) और वह रंग (दूसरा मान) होता है जिसमें इसे मैप किया जाएगा। |
| type | int | एक तत्व [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) जो उस वर्ग को निर्दिष्ट करता है जिसके लिए रंग‑रीमैप तालिका सेट की गई है। |

### clearRemapTable() {#clearRemapTable--}
```
public void clearRemapTable()
```


डिफ़ॉल्ट श्रेणी के लिए कलर‑रीमैप तालिका को साफ़ करता है।

### clearRemapTable(int type) {#clearRemapTable-int-}
```
public void clearRemapTable(int type)
```


निर्दिष्ट श्रेणी के लिए कलर‑रीमैप तालिका को साफ़ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| type | int | एक तत्व [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) जो उस वर्ग को निर्दिष्ट करता है जिसके लिए रीमैप तालिका साफ़ की गई है। |

### setBrushRemapTable(ColorMap[] map) {#setBrushRemapTable-com.aspose.drawing.imaging.ColorMap---}
```
public void setBrushRemapTable(ColorMap[] map)
```


ब्रश श्रेणी के लिए कलर‑रीमैप तालिका सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| map | [ColorMap\[\]](../../com.aspose.drawing.imaging/colormap) | [ColorMap](../../com.aspose.drawing.imaging/colormap) वस्तुओं की एक एरे। |

### clearBrushRemapTable() {#clearBrushRemapTable--}
```
public void clearBrushRemapTable()
```


इस [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes) ऑब्जेक्ट की ब्रश कलर‑रीमैप तालिका को साफ़ करता है।

### setWrapMode(int mode) {#setWrapMode-int-}
```
public void setWrapMode(int mode)
```


रैप मोड सेट करता है जो यह तय करने के लिए उपयोग किया जाता है कि टेक्सचर को आकार के ऊपर या आकार की सीमाओं पर कैसे टाइल किया जाए। जब टेक्सचर आकार से छोटा हो तो उसे भरने के लिए आकार के ऊपर टाइल किया जाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| mode | int | एक तत्व [WrapMode](../../com.aspose.drawing.drawing2d/wrapmode) जो यह निर्दिष्ट करता है कि छवि की दोहराई गई प्रतियों का उपयोग क्षेत्र को टाइल करने के लिए कैसे किया जाता है। |

### setWrapMode(int mode, Color color) {#setWrapMode-int-com.aspose.drawing.Color-}
```
public void setWrapMode(int mode, Color color)
```


रैप मोड और रंग सेट करता है जिसका उपयोग यह तय करने के लिए किया जाता है कि टेक्सचर को आकार के ऊपर या आकार की सीमाओं पर कैसे टाइल किया जाए। जब टेक्सचर आकार से छोटा हो तो उसे भरने के लिए टेक्सचर को आकार के ऊपर टाइल किया जाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| mode | int | एक तत्व [WrapMode](../../com.aspose.drawing.drawing2d/wrapmode) जो यह निर्दिष्ट करता है कि छवि की दोहराई गई प्रतियों का उपयोग क्षेत्र को टाइल करने के लिए कैसे किया जाता है। |
| color | [Color](../../com.aspose.drawing/color) | एक [Color](../../com.aspose.drawing/color) ऑब्जेक्ट जो रेंडर की गई छवि के बाहर के पिक्सेल का रंग निर्दिष्ट करता है। यह रंग तब दिखाई देता है जब मोड पैरामीटर `WrapMode.Clamp` पर सेट हो और `Graphics.DrawImage` को पास किया गया स्रोत आयत छवि से बड़ा हो। |

### setWrapMode(int mode, Color color, boolean clamp) {#setWrapMode-int-com.aspose.drawing.Color-boolean-}
```
public void setWrapMode(int mode, Color color, boolean clamp)
```


रैप मोड और रंग सेट करता है जिसका उपयोग यह तय करने के लिए किया जाता है कि टेक्सचर को आकार के ऊपर या आकार की सीमाओं पर कैसे टाइल किया जाए। जब टेक्सचर आकार से छोटा हो तो उसे भरने के लिए टेक्सचर को आकार के ऊपर टाइल किया जाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| mode | int | एक तत्व [WrapMode](../../com.aspose.drawing.drawing2d/wrapmode) जो यह निर्दिष्ट करता है कि छवि की दोहराई गई प्रतियों का उपयोग क्षेत्र को टाइल करने के लिए कैसे किया जाता है। |
| color | [Color](../../com.aspose.drawing/color) | एक रंग ऑब्जेक्ट जो रेंडर की गई छवि के बाहर के पिक्सेल का रंग निर्दिष्ट करता है। यह रंग तब दिखाई देता है जब मोड पैरामीटर `WrapMode.Clamp` पर सेट हो और `Graphics.DrawImage` को पास किया गया स्रोत आयत छवि से बड़ा हो। |
| clamp | boolean | इस पैरामीटर का कोई प्रभाव नहीं है। इसे false सेट करें। |

### getAdjustedPalette(ColorPalette palette, int type) {#getAdjustedPalette-com.aspose.drawing.imaging.ColorPalette-int-}
```
public void getAdjustedPalette(ColorPalette palette, int type)
```


निर्दिष्ट श्रेणी की समायोजन सेटिंग्स के अनुसार पैलेट में रंगों को समायोजित करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| palette | [ColorPalette](../../com.aspose.drawing.imaging/colorpalette) | एक [ColorPalette](../../com.aspose.drawing.imaging/colorpalette) जो इनपुट में समायोजित करने के लिए पैलेट रखता है, और आउटपुट में समायोजित पैलेट रखता है। |
| type | int | [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) का एक तत्व जो वह श्रेणी निर्दिष्ट करता है जिसके समायोजन सेटिंग्स पैलेट पर लागू किए जाएंगे। |

