---
title: StringFormatFlags
second_title: Aspose.Drawing for Java API संदर्भ
description: पाठ स्ट्रिंग्स के लिए प्रदर्शन और लेआउट जानकारी को निर्दिष्ट करता है।
type: docs
weight: 48
url: /hi/java/com.aspose.drawing/stringformatflags/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class StringFormatFlags extends System.Enum
```

पाठ स्ट्रिंग्स के लिए प्रदर्शन और लेआउट जानकारी को निर्दिष्ट करता है।
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [DirectionRightToLeft](#DirectionRightToLeft) | पाठ दाएँ से बाएँ प्रदर्शित किया जाता है। |
| [DirectionVertical](#DirectionVertical) | पाठ लंबवत रूप से संरेखित है। |
| [FitBlackBox](#FitBlackBox) | अक्षरों के भागों को स्ट्रिंग के लेआउट आयत से बाहर निकलने की अनुमति है। |
| [DisplayFormatControl](#DisplayFormatControl) | बाएँ‑से‑दाएँ मार्क जैसे नियंत्रण अक्षर आउटपुट में एक प्रतिनिधि ग्लिफ़ के साथ दिखाए जाते हैं। |
| [NoFontFallback](#NoFontFallback) | अनुरोधित फ़ॉन्ट में समर्थित न होने वाले अक्षरों के लिए वैकल्पिक फ़ॉन्ट पर फ़ॉलबैक निष्क्रिय है। |
| [MeasureTrailingSpaces](#MeasureTrailingSpaces) | प्रत्येक पंक्ति के अंत में अंतिम स्पेस शामिल करता है। |
| [NoWrap](#NoWrap) | आयत के भीतर फॉर्मेटिंग करते समय पंक्तियों के बीच टेक्स्ट रैपिंग निष्क्रिय है। |
| [LineLimit](#LineLimit) | केवल पूरी पंक्तियों को फॉर्मेटिंग आयत में व्यवस्थित किया जाता है। |
| [NoClip](#NoClip) | ग्लिफ़ के बाहर निकलने वाले भाग, और अनरैप्ड टेक्स्ट जो फॉर्मेटिंग आयत के बाहर पहुँचता है, दिखाने की अनुमति है। |
| [ExactAlignment](#ExactAlignment) | सटीक संरेखण, सही पैडिंग GDI+ |
### DirectionRightToLeft {#DirectionRightToLeft}
```
public static final int DirectionRightToLeft
```


पाठ दाएँ से बाएँ प्रदर्शित किया जाता है।

### DirectionVertical {#DirectionVertical}
```
public static final int DirectionVertical
```


पाठ लंबवत रूप से संरेखित है।

### FitBlackBox {#FitBlackBox}
```
public static final int FitBlackBox
```


अक्षरों के भागों को स्ट्रिंग के लेआउट आयत से बाहर निकलने की अनुमति है। डिफ़ॉल्ट रूप से, किसी भी ओवरहैंग से बचने के लिए अक्षरों को पुनः स्थित किया जाता है।

### DisplayFormatControl {#DisplayFormatControl}
```
public static final int DisplayFormatControl
```


बाएँ‑से‑दाएँ मार्क जैसे नियंत्रण अक्षर आउटपुट में एक प्रतिनिधि ग्लिफ़ के साथ दिखाए जाते हैं।

### NoFontFallback {#NoFontFallback}
```
public static final int NoFontFallback
```


अनुरोधित फ़ॉन्ट में समर्थित न होने वाले अक्षरों के लिए वैकल्पिक फ़ॉन्ट पर फ़ॉलबैक निष्क्रिय है। कोई भी लापता अक्षर फ़ॉन्ट के लापता ग्लिफ़ के साथ दिखाया जाता है, आमतौर पर एक खुला वर्ग।

### MeasureTrailingSpaces {#MeasureTrailingSpaces}
```
public static final int MeasureTrailingSpaces
```


प्रत्येक पंक्ति के अंत में अंतिम स्पेस शामिल करता है। डिफ़ॉल्ट रूप से MeasureString मेथड द्वारा लौटाए गए बाउंडरी आयत में प्रत्येक पंक्ति के अंत में स्पेस को बाहर रखा जाता है। इस फ़्लैग को सेट करके माप में वह स्पेस शामिल करें।

### NoWrap {#NoWrap}
```
public static final int NoWrap
```


आयत के भीतर फॉर्मेटिंग करते समय पंक्तियों के बीच टेक्स्ट रैपिंग निष्क्रिय है। यह फ़्लैग तब लागू होता है जब आयत के बजाय बिंदु पास किया जाता है, या जब निर्दिष्ट आयत की लाइन लंबाई शून्य होती है।

### LineLimit {#LineLimit}
```
public static final int LineLimit
```


केवल पूरी पंक्तियों को फॉर्मेटिंग आयत में व्यवस्थित किया जाता है। डिफ़ॉल्ट रूप से लेआउट पाठ के अंत तक जारी रहता है, या जब क्लिपिंग के कारण और पंक्तियाँ दिखाई नहीं देतीं, जो भी पहले हो। ध्यान दें कि डिफ़ॉल्ट सेटिंग्स अंतिम पंक्ति को आंशिक रूप से फॉर्मेटिंग आयत द्वारा छिपा सकती हैं, यदि वह पंक्ति की ऊँचाई का पूर्ण गुणक नहीं है। यह सुनिश्चित करने के लिए कि केवल पूरी पंक्तियाँ दिखें, इस मान को निर्दिष्ट करें और कम से कम एक पंक्ति की ऊँचाई के बराबर ऊँची फॉर्मेटिंग आयत प्रदान करने का ध्यान रखें।

### NoClip {#NoClip}
```
public static final int NoClip
```


ग्लिफ़ के लटकते हिस्से और अनरैप्ड टेक्स्ट जो फॉर्मेटिंग आयत के बाहर पहुँचते हैं, दिखाने की अनुमति है। डिफ़ॉल्ट रूप से फॉर्मेटिंग आयत के बाहर पहुँचने वाला सभी टेक्स्ट और ग्लिफ़ भाग क्लिप हो जाते हैं।

### ExactAlignment {#ExactAlignment}
```
public static final int ExactAlignment
```


सटीक संरेखण, सही पैडिंग GDI+

