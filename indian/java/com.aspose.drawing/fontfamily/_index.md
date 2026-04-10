---
title: FontFamily
second_title: Aspose.Drawing for Java API संदर्भ
description: एक समान मूल डिज़ाइन और शैली में कुछ विविधताओं वाले टाइपफ़ेस के समूह को परिभाषित करता है।
type: docs
weight: 24
url: /hi/java/com.aspose.drawing/fontfamily/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public final class FontFamily implements System.IDisposable
```

एक समूह को परिभाषित करता है जिसमें समान मूल डिज़ाइन और शैलियों में कुछ विविधताएँ वाले टाइप फ़ेस होते हैं। इस क्लास को विरासत में नहीं लिया जा सकता।
## निर्माता

| निर्माता | विवरण |
| --- | --- |
| [FontFamily(String name)](#FontFamily-java.lang.String-) | निर्दिष्ट नाम के साथ [FontFamily](../../com.aspose.drawing/fontfamily) क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है। |
| [FontFamily(String name, FontCollection fontCollection)](#FontFamily-java.lang.String-com.aspose.drawing.FontCollection-) | [FontFamily](../../com.aspose.drawing/fontfamily) क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है। |
| [FontFamily(String name, FontFamilyDefinition definition)](#FontFamily-java.lang.String-com.aspose.drawing.FontFamilyDefinition-) | [FontFamily](../../com.aspose.drawing/fontfamily) क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है। |
## मेथड्स

| विधि | विवरण |
| --- | --- |
| [getFamilies()](#getFamilies--) | एक एरे प्राप्त करता है जिसमें वर्तमान ग्राफ़िक्स कॉन्टेक्स्ट से जुड़े सभी [FontFamily](../../com.aspose.drawing/fontfamily) ऑब्जेक्ट्स होते हैं। |
| [getGenericSansSerif()](#getGenericSansSerif--) | एक सामान्य sans serif [FontFamily](../../com.aspose.drawing/fontfamily) ऑब्जेक्ट प्राप्त करता है। |
| [getGenericSerif()](#getGenericSerif--) | एक सामान्य serif [FontFamily](../../com.aspose.drawing/fontfamily) प्राप्त करता है। |
| [getGenericMonospace()](#getGenericMonospace--) | एक सामान्य monospace [FontFamily](../../com.aspose.drawing/fontfamily) प्राप्त करता है। |
| [getName()](#getName--) | इस [FontFamily](../../com.aspose.drawing/fontfamily) का नाम प्राप्त करता है। |
| [dispose()](#dispose--) | इस [FontFamily](../../com.aspose.drawing/fontfamily) द्वारा उपयोग किए गए सभी संसाधनों को रिलीज़ करता है। |
| [getName(int language)](#getName-int-) | निर्दिष्ट भाषा में इस [FontFamily](../../com.aspose.drawing/fontfamily) का नाम लौटाता है। |
| [isStyleAvailable(int style)](#isStyleAvailable-int-) | निर्दिष्ट [FontStyle](../../com.aspose.drawing/fontstyle) enumeration उपलब्ध है या नहीं दर्शाता है। |
| [getEmHeight(int style)](#getEmHeight-int-) | निर्दिष्ट शैली के लिए EM वर्ग की ऊँचाई, फ़ॉन्ट डिज़ाइन इकाइयों में, प्राप्त करता है। |
| [getCellAscent(int style)](#getCellAscent-int-) | निर्दिष्ट शैली के [FontFamily](../../com.aspose.drawing/fontfamily) की सेल आरोहण, डिज़ाइन इकाइयों में, लौटाता है। |
| [getCellDescent(int style)](#getCellDescent-int-) | निर्दिष्ट शैली के [FontFamily](../../com.aspose.drawing/fontfamily) की सेल अवरोहण, डिज़ाइन इकाइयों में, लौटाता है। |
| [hashCode()](#hashCode--) | इस [FontFamily](../../com.aspose.drawing/fontfamily) के लिए हैश कोड प्राप्त करता है। |
| [equals(Object obj)](#equals-java.lang.Object-) | निर्दिष्ट ऑब्जेक्ट एक [FontFamily](../../com.aspose.drawing/fontfamily) है और यह [FontFamily](../../com.aspose.drawing/fontfamily) के समान है या नहीं दर्शाता है। |
| [getLineSpacing(int style)](#getLineSpacing-int-) | निर्दिष्ट शैली के [FontFamily](../../com.aspose.drawing/fontfamily) की लाइन स्पेसिंग, डिज़ाइन इकाइयों में, लौटाता है। |
### FontFamily(String name) {#FontFamily-java.lang.String-}
```
public FontFamily(String name)
```


निर्दिष्ट नाम के साथ [FontFamily](../../com.aspose.drawing/fontfamily) क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | java.lang.String | नए [FontFamily](../../com.aspose.drawing/fontfamily) का नाम। |

### FontFamily(String name, FontCollection fontCollection) {#FontFamily-java.lang.String-com.aspose.drawing.FontCollection-}
```
public FontFamily(String name, FontCollection fontCollection)
```


[FontFamily](../../com.aspose.drawing/fontfamily) क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| नाम | java.lang.String | फ़ॉन्ट परिवार का नाम। |
| fontCollection | [FontCollection](../../com.aspose.drawing/fontcollection) | फ़ॉन्ट संग्रह। |

### FontFamily(String name, FontFamilyDefinition definition) {#FontFamily-java.lang.String-com.aspose.drawing.FontFamilyDefinition-}
```
public FontFamily(String name, FontFamilyDefinition definition)
```


[FontFamily](../../com.aspose.drawing/fontfamily) क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| नाम | java.lang.String | फ़ॉन्ट परिवार का नाम। |
| definition | [FontFamilyDefinition](../../com.aspose.drawing/fontfamilydefinition) | परिभाषा। |

### getFamilies() {#getFamilies--}
```
public static FontFamily[] getFamilies()
```


एक एरे प्राप्त करता है जिसमें वर्तमान ग्राफ़िक्स कॉन्टेक्स्ट से जुड़े सभी [FontFamily](../../com.aspose.drawing/fontfamily) ऑब्जेक्ट्स होते हैं।

**Returns:**
com.aspose.drawing.FontFamily[] - वर्तमान ग्राफ़िक्स संदर्भ से जुड़े [FontFamily](../../com.aspose.drawing/fontfamily) ऑब्जेक्ट्स की एक सरणी।
### getGenericSansSerif() {#getGenericSansSerif--}
```
public static FontFamily getGenericSansSerif()
```


एक सामान्य sans serif [FontFamily](../../com.aspose.drawing/fontfamily) ऑब्जेक्ट प्राप्त करता है।

**Returns:**
[FontFamily](../../com.aspose.drawing/fontfamily) - A [FontFamily](../../com.aspose.drawing/fontfamily) object that represents a generic sans serif font.
### getGenericSerif() {#getGenericSerif--}
```
public static FontFamily getGenericSerif()
```


एक सामान्य serif [FontFamily](../../com.aspose.drawing/fontfamily) प्राप्त करता है।

**Returns:**
[FontFamily](../../com.aspose.drawing/fontfamily) - A [FontFamily](../../com.aspose.drawing/fontfamily) that represents a generic serif font.
### getGenericMonospace() {#getGenericMonospace--}
```
public static FontFamily getGenericMonospace()
```


एक सामान्य monospace [FontFamily](../../com.aspose.drawing/fontfamily) प्राप्त करता है।

**Returns:**
[FontFamily](../../com.aspose.drawing/fontfamily) - A [FontFamily](../../com.aspose.drawing/fontfamily) that represents a generic monospace font.
### getName() {#getName--}
```
public String getName()
```


इस [FontFamily](../../com.aspose.drawing/fontfamily) का नाम प्राप्त करता है।

**Returns:**
java.lang.String - एक स्ट्रिंग जो इस [FontFamily](../../com.aspose.drawing/fontfamily) का नाम दर्शाती है।
### dispose() {#dispose--}
```
public void dispose()
```


इस [FontFamily](../../com.aspose.drawing/fontfamily) द्वारा उपयोग किए गए सभी संसाधनों को रिलीज़ करता है।

### getName(int language) {#getName-int-}
```
public String getName(int language)
```


निर्दिष्ट भाषा में इस [FontFamily](../../com.aspose.drawing/fontfamily) का नाम लौटाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| भाषा | int | जिस भाषा में नाम लौटाया जाता है। |

**Returns:**
java.lang.String - एक स्ट्रिंग जो निर्दिष्ट भाषा में इस [FontFamily](../../com.aspose.drawing/fontfamily) का नाम दर्शाती है।
### isStyleAvailable(int style) {#isStyleAvailable-int-}
```
public boolean isStyleAvailable(int style)
```


निर्दिष्ट [FontStyle](../../com.aspose.drawing/fontstyle) enumeration उपलब्ध है या नहीं दर्शाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| style | int | परीक्षण करने के लिए [FontStyle](../../com.aspose.drawing/fontstyle)। |

**Returns:**
boolean - यदि निर्दिष्ट [FontStyle](../../com.aspose.drawing/fontstyle) उपलब्ध है तो true; अन्यथा false।
### getEmHeight(int style) {#getEmHeight-int-}
```
public int getEmHeight(int style)
```


निर्दिष्ट शैली के लिए EM वर्ग की ऊँचाई, फ़ॉन्ट डिज़ाइन इकाइयों में, प्राप्त करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| style | int | जिस [FontStyle](../../com.aspose.drawing/fontstyle) के लिए EM ऊँचाई प्राप्त करनी है। |

**Returns:**
int - EM वर्ग की ऊँचाई।
### getCellAscent(int style) {#getCellAscent-int-}
```
public int getCellAscent(int style)
```


निर्दिष्ट शैली के [FontFamily](../../com.aspose.drawing/fontfamily) की सेल आरोहण, डिज़ाइन इकाइयों में, लौटाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| style | int | एक [FontStyle](../../com.aspose.drawing/fontstyle) जो फ़ॉन्ट के लिए शैली जानकारी रखता है। |

**Returns:**
int - इस [FontFamily](../../com.aspose.drawing/fontfamily) के लिए सेल आरोहण जो निर्दिष्ट [FontStyle](../../com.aspose.drawing/fontstyle) का उपयोग करता है।
### getCellDescent(int style) {#getCellDescent-int-}
```
public int getCellDescent(int style)
```


निर्दिष्ट शैली के [FontFamily](../../com.aspose.drawing/fontfamily) की सेल अवरोहण, डिज़ाइन इकाइयों में, लौटाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| style | int | एक [FontStyle](../../com.aspose.drawing/fontstyle) जो फ़ॉन्ट के लिए शैली जानकारी रखता है। |

**Returns:**
int - इस [FontFamily](../../com.aspose.drawing/fontfamily) के लिए सेल अवरोहण मीट्रिक जो निर्दिष्ट [FontStyle](../../com.aspose.drawing/fontstyle) का उपयोग करता है।
### hashCode() {#hashCode--}
```
public int hashCode()
```


इस [FontFamily](../../com.aspose.drawing/fontfamily) के लिए हैश कोड प्राप्त करता है।

**Returns:**
int - इस [FontFamily](../../com.aspose.drawing/fontfamily) का हैश कोड।
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


निर्दिष्ट ऑब्जेक्ट एक [FontFamily](../../com.aspose.drawing/fontfamily) है और यह [FontFamily](../../com.aspose.drawing/fontfamily) के समान है या नहीं दर्शाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | java.lang.Object | परीक्षण करने के लिए ऑब्जेक्ट। |

**Returns:**
boolean - यदि `obj` एक [FontFamily](../../com.aspose.drawing/fontfamily) है और यह इस [FontFamily](../../com.aspose.drawing/fontfamily) के समान है तो `true`; अन्यथा `false`।
### getLineSpacing(int style) {#getLineSpacing-int-}
```
public int getLineSpacing(int style)
```


निर्दिष्ट शैली के [FontFamily](../../com.aspose.drawing/fontfamily) की लाइन स्पेसिंग, डिज़ाइन इकाइयों में, लौटाता है। लाइन स्पेसिंग दो क्रमिक टेक्स्ट लाइनों की बेस लाइनों के बीच की लंबवत दूरी है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| style | int | लागू करने के लिए [FontStyle](../../com.aspose.drawing/fontstyle)। |

**Returns:**
int - दो क्रमिक टेक्स्ट लाइनों के बीच की दूरी।
