---
title: CopyPixelOperation
second_title: Aspose.Drawing for Java API संदर्भ
description: कॉपी पिक्सेल ऑपरेशन में स्रोत रंग को गंतव्य रंग के साथ कैसे मिलाया जाता है जिससे अंतिम रंग प्राप्त होता है, यह निर्धारित करता है।
type: docs
weight: 18
url: /hi/java/com.aspose.drawing/copypixeloperation/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class CopyPixelOperation extends System.Enum
```

कॉपी पिक्सेल ऑपरेशन में स्रोत रंग को गंतव्य रंग के साथ कैसे मिलाया जाता है जिससे अंतिम रंग प्राप्त होता है, यह निर्धारित करता है।
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [NoMirrorBitmap](#NoMirrorBitmap) | Bitmap को मिरर नहीं किया गया है। |
| [Blackness](#Blackness) | Destination क्षेत्र को भौतिक पैलेट में इंडेक्स 0 से संबंधित रंग का उपयोग करके भरा जाता है। |
| [NotSourceErase](#NotSourceErase) | Source और destination रंगों को Boolean `OR` ऑपरेटर का उपयोग करके संयोजित किया जाता है, और फिर परिणामी रंग को उलटा (इनवर्ट) किया जाता है। |
| [NotSourceCopy](#NotSourceCopy) | उलटा स्रोत क्षेत्र destination में कॉपी किया जाता है। |
| [SourceErase](#SourceErase) | Destination क्षेत्र के उलटे रंगों को source क्षेत्र के रंगों के साथ Boolean `AND` ऑपरेटर का उपयोग करके संयोजित किया जाता है। |
| [DestinationInvert](#DestinationInvert) | Destination क्षेत्र को उलटा (इनवर्ट) किया गया है। |
| [PatInvert](#PatInvert) | Destination डिवाइस कॉन्टेक्स्ट में वर्तमान में चयनित ब्रश के रंगों को destination के रंगों के साथ Boolean `XOR` ऑपरेटर का उपयोग करके संयोजित किया जाता है। |
| [SourceInvert](#SourceInvert) | Source और destination क्षेत्रों के रंगों को Boolean `XOR` ऑपरेटर का उपयोग करके संयोजित किया जाता है। |
| [SourceAnd](#SourceAnd) | Source और destination क्षेत्रों के रंगों को Boolean `AND` ऑपरेटर का उपयोग करके संयोजित किया जाता है। |
| [MergePaint](#MergePaint) | उलटे स्रोत क्षेत्र के रंगों को Boolean `OR` ऑपरेटर का उपयोग करके destination क्षेत्र के रंगों के साथ मिलाया जाता है। |
| [MergeCopy](#MergeCopy) | Source क्षेत्र के रंगों को destination डिवाइस कॉन्टेक्स्ट के चयनित ब्रश के रंगों के साथ Boolean `AND` ऑपरेटर का उपयोग करके मिलाया जाता है। |
| [SourceCopy](#SourceCopy) | Source क्षेत्र को सीधे destination क्षेत्र में कॉपी किया जाता है। |
| [SourcePaint](#SourcePaint) | Source और destination क्षेत्रों के रंगों को Boolean `OR` ऑपरेटर का उपयोग करके संयोजित किया जाता है। |
| [PatCopy](#PatCopy) | Destination डिवाइस कॉन्टेक्स्ट में वर्तमान में चयनित ब्रश को destination bitmap में कॉपी किया जाता है। |
| [PatPaint](#PatPaint) | Destination डिवाइस कॉन्टेक्स्ट में वर्तमान में चयनित ब्रश के रंगों को उलटे स्रोत क्षेत्र के रंगों के साथ Boolean `OR` ऑपरेटर का उपयोग करके संयोजित किया जाता है। |
| [Whiteness](#Whiteness) | Destination क्षेत्र को भौतिक पैलेट में इंडेक्स 1 से संबंधित रंग का उपयोग करके भरा जाता है। |
| [CaptureBlt](#CaptureBlt) | आपकी विंडो के ऊपर परतित विंडो को परिणामी छवि में शामिल किया जाता है। |
### NoMirrorBitmap {#NoMirrorBitmap}
```
public static final int NoMirrorBitmap
```


Bitmap को मिरर नहीं किया गया है।

### Blackness {#Blackness}
```
public static final int Blackness
```


Destination क्षेत्र को भौतिक पैलेट में इंडेक्स 0 से संबंधित रंग का उपयोग करके भरा जाता है। (डिफ़ॉल्ट भौतिक पैलेट के लिए यह रंग काला है।)

### NotSourceErase {#NotSourceErase}
```
public static final int NotSourceErase
```


Source और destination रंगों को Boolean `OR` ऑपरेटर का उपयोग करके संयोजित किया जाता है, और फिर परिणामी रंग को उलटा (इनवर्ट) किया जाता है।

### NotSourceCopy {#NotSourceCopy}
```
public static final int NotSourceCopy
```


उलटा स्रोत क्षेत्र destination में कॉपी किया जाता है।

### SourceErase {#SourceErase}
```
public static final int SourceErase
```


Destination क्षेत्र के उलटे रंगों को source क्षेत्र के रंगों के साथ Boolean `AND` ऑपरेटर का उपयोग करके संयोजित किया जाता है।

### DestinationInvert {#DestinationInvert}
```
public static final int DestinationInvert
```


Destination क्षेत्र को उलटा (इनवर्ट) किया गया है।

### PatInvert {#PatInvert}
```
public static final int PatInvert
```


Destination डिवाइस कॉन्टेक्स्ट में वर्तमान में चयनित ब्रश के रंगों को destination के रंगों के साथ Boolean `XOR` ऑपरेटर का उपयोग करके संयोजित किया जाता है।

### SourceInvert {#SourceInvert}
```
public static final int SourceInvert
```


Source और destination क्षेत्रों के रंगों को Boolean `XOR` ऑपरेटर का उपयोग करके संयोजित किया जाता है।

### SourceAnd {#SourceAnd}
```
public static final int SourceAnd
```


Source और destination क्षेत्रों के रंगों को Boolean `AND` ऑपरेटर का उपयोग करके संयोजित किया जाता है।

### MergePaint {#MergePaint}
```
public static final int MergePaint
```


उलटे स्रोत क्षेत्र के रंगों को Boolean `OR` ऑपरेटर का उपयोग करके destination क्षेत्र के रंगों के साथ मिलाया जाता है।

### MergeCopy {#MergeCopy}
```
public static final int MergeCopy
```


Source क्षेत्र के रंगों को destination डिवाइस कॉन्टेक्स्ट के चयनित ब्रश के रंगों के साथ Boolean `AND` ऑपरेटर का उपयोग करके मिलाया जाता है।

### SourceCopy {#SourceCopy}
```
public static final int SourceCopy
```


Source क्षेत्र को सीधे destination क्षेत्र में कॉपी किया जाता है।

### SourcePaint {#SourcePaint}
```
public static final int SourcePaint
```


Source और destination क्षेत्रों के रंगों को Boolean `OR` ऑपरेटर का उपयोग करके संयोजित किया जाता है।

### PatCopy {#PatCopy}
```
public static final int PatCopy
```


Destination डिवाइस कॉन्टेक्स्ट में वर्तमान में चयनित ब्रश को destination bitmap में कॉपी किया जाता है।

### PatPaint {#PatPaint}
```
public static final int PatPaint
```


गंतव्य डिवाइस कॉन्टेक्स्ट में वर्तमान में चयनित ब्रश के रंगों को उल्टे स्रोत क्षेत्र के रंगों के साथ बूलियन `OR` ऑपरेटर का उपयोग करके मिलाया जाता है। इस ऑपरेशन का परिणाम बूलियन `OR` ऑपरेटर का उपयोग करके गंतव्य क्षेत्र के रंगों के साथ मिलाया जाता है।

### Whiteness {#Whiteness}
```
public static final int Whiteness
```


गंतव्य क्षेत्र को भौतिक पैलेट में सूचकांक 1 से जुड़े रंग का उपयोग करके भरा जाता है। (डिफ़ॉल्ट भौतिक पैलेट के लिए यह रंग सफ़ेद होता है।)

### CaptureBlt {#CaptureBlt}
```
public static final int CaptureBlt
```


आपकी विंडो के ऊपर परतित विंडो को परिणामी छवि में शामिल किया जाता है। डिफ़ॉल्ट रूप से, छवि में केवल आपकी विंडो ही होती है। ध्यान दें कि इसे सामान्यतः प्रिंटिंग डिवाइस कॉन्टेक्स्ट के लिए उपयोग नहीं किया जा सकता।

