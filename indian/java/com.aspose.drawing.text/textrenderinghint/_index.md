---
title: TextRenderingHint
second_title: Aspose.Drawing for Java API संदर्भ
description: टेक्स्ट रेंडरिंग की गुणवत्ता को निर्दिष्ट करता है।
type: docs
weight: 14
url: /hi/java/com.aspose.drawing.text/textrenderinghint/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class TextRenderingHint extends System.Enum
```

टेक्स्ट रेंडरिंग की गुणवत्ता को निर्दिष्ट करता है।
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [SystemDefault](#SystemDefault) | प्रत्येक अक्षर को उसके ग्लिफ़ बिटमैप का उपयोग करके, सिस्टम डिफ़ॉल्ट रेंडरिंग संकेत के साथ खींचा जाता है। |
| [SingleBitPerPixelGridFit](#SingleBitPerPixelGridFit) | प्रत्येक अक्षर को उसके ग्लिफ़ बिटमैप का उपयोग करके खींचा जाता है। |
| [SingleBitPerPixel](#SingleBitPerPixel) | प्रत्येक अक्षर को उसके ग्लिफ़ बिटमैप का उपयोग करके खींचा जाता है। |
| [AntiAliasGridFit](#AntiAliasGridFit) | प्रत्येक अक्षर को उसके एंटी‑एलायस्ड ग्लिफ़ बिटमैप का उपयोग करके, हिंटिंग के साथ खींचा जाता है। |
| [AntiAlias](#AntiAlias) | प्रत्येक अक्षर को उसके एंटी‑एलायस्ड ग्लिफ़ बिटमैप का उपयोग करके, बिना हिंटिंग के खींचा जाता है। |
| [ClearTypeGridFit](#ClearTypeGridFit) | प्रत्येक अक्षर को उसके ग्लिफ़ क्लियरटाइप बिटमैप का उपयोग करके, हिंटिंग के साथ खींचा जाता है। |
### SystemDefault {#SystemDefault}
```
public static final int SystemDefault
```


प्रत्येक अक्षर को उसके ग्लिफ़ बिटमैप का उपयोग करके, सिस्टम डिफ़ॉल्ट रेंडरिंग संकेत के साथ खींचा जाता है। पाठ को सिस्टम के लिए उपयोगकर्ता द्वारा चुनी गई किसी भी फ़ॉन्ट‑स्मूथिंग सेटिंग्स के अनुसार खींचा जाएगा।

### SingleBitPerPixelGridFit {#SingleBitPerPixelGridFit}
```
public static final int SingleBitPerPixelGridFit
```


प्रत्येक अक्षर को उसके ग्लिफ़ बिटमैप का उपयोग करके खींचा जाता है। हिंटिंग का उपयोग स्टेम और वक्रता पर अक्षर की उपस्थिति को सुधारने के लिए किया जाता है।

### SingleBitPerPixel {#SingleBitPerPixel}
```
public static final int SingleBitPerPixel
```


प्रत्येक अक्षर को उसके ग्लिफ़ बिटमैप का उपयोग करके बनाया जाता है। हिंटिंग का उपयोग नहीं किया गया है।

### AntiAliasGridFit {#AntiAliasGridFit}
```
public static final int AntiAliasGridFit
```


प्रत्येक अक्षर को उसके एंटीएलायस्ड ग्लिफ़ बिटमैप के साथ हिंटिंग का उपयोग करके बनाया जाता है। एंटीएलायसिंग के कारण बहुत बेहतर गुणवत्ता मिलती है, लेकिन उच्च प्रदर्शन लागत पर।

### AntiAlias {#AntiAlias}
```
public static final int AntiAlias
```


प्रत्येक अक्षर को उसके एंटीएलायस्ड ग्लिफ़ बिटमैप का उपयोग करके बिना हिंटिंग के बनाया जाता है। एंटीएलायसिंग के कारण बेहतर गुणवत्ता मिलती है। स्टेम की चौड़ाई में अंतर दिखाई दे सकता है क्योंकि हिंटिंग बंद है।

### ClearTypeGridFit {#ClearTypeGridFit}
```
public static final int ClearTypeGridFit
```


प्रत्येक अक्षर को उसके ग्लिफ़ ClearType बिटमैप के साथ हिंटिंग का उपयोग करके बनाया जाता है। यह सबसे उच्च गुणवत्ता सेटिंग है। ClearType फ़ॉन्ट सुविधाओं का लाभ उठाने के लिए उपयोग किया जाता है।

