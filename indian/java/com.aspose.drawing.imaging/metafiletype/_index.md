---
title: MetafileType
second_title: Aspose.Drawing for Java API संदर्भ
description: मेटाफाइल के प्रकारों को निर्दिष्ट करता है।
type: docs
weight: 33
url: /hi/java/com.aspose.drawing.imaging/metafiletype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class MetafileType extends System.Enum
```

मेटाफाइल के प्रकारों को निर्दिष्ट करता है।
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [Invalid](#Invalid) | GDI+ में पहचाना न जाने वाला मेटाफाइल फ़ॉर्मेट निर्दिष्ट करता है। |
| [Wmf](#Wmf) | WMF (Windows Metafile) फ़ाइल निर्दिष्ट करता है। |
| [WmfPlaceable](#WmfPlaceable) | WMF (Windows Metafile) फ़ाइल निर्दिष्ट करता है, जिसके सामने एक प्लेसएबल मेटाफाइल हेडर होता है। |
| [Emf](#Emf) | Enhanced Metafile (EMF) फ़ाइल निर्दिष्ट करता है। |
| [EmfPlusOnly](#EmfPlusOnly) | EMF+ फ़ाइल निर्दिष्ट करता है। |
| [EmfPlusDual](#EmfPlusDual) | EMF+ Dual फ़ाइल निर्दिष्ट करता है। |
### Invalid {#Invalid}
```
public static final int Invalid
```


GDI+ में पहचाना न जाने वाला मेटाफाइल फ़ॉर्मेट निर्दिष्ट करता है।

### Wmf {#Wmf}
```
public static final int Wmf
```


WMF (Windows Metafile) फ़ाइल निर्दिष्ट करता है। ऐसी फ़ाइल में केवल GDI रिकॉर्ड होते हैं।

### WmfPlaceable {#WmfPlaceable}
```
public static final int WmfPlaceable
```


WMF (Windows Metafile) फ़ाइल निर्दिष्ट करता है, जिसके सामने एक प्लेसएबल मेटाफाइल हेडर होता है।

### Emf {#Emf}
```
public static final int Emf
```


Enhanced Metafile (EMF) फ़ाइल निर्दिष्ट करता है। ऐसी फ़ाइल में केवल GDI रिकॉर्ड होते हैं।

### EmfPlusOnly {#EmfPlusOnly}
```
public static final int EmfPlusOnly
```


EMF+ फ़ाइल निर्दिष्ट करता है। ऐसी फ़ाइल में केवल GDI+ रिकॉर्ड होते हैं और इसे GDI+ का उपयोग करके प्रदर्शित किया जाना चाहिए। GDI का उपयोग करके रिकॉर्ड प्रदर्शित करने से अप्रत्याशित परिणाम हो सकते हैं।

### EmfPlusDual {#EmfPlusDual}
```
public static final int EmfPlusDual
```


EMF+ Dual फ़ाइल निर्दिष्ट करता है। ऐसी फ़ाइल में GDI+ रिकॉर्ड के साथ वैकल्पिक GDI रिकॉर्ड भी होते हैं और इसे GDI या GDI+ में से किसी का उपयोग करके प्रदर्शित किया जा सकता है। GDI का उपयोग करके रिकॉर्ड प्रदर्शित करने से कुछ गुणवत्ता में गिरावट आ सकती है।

