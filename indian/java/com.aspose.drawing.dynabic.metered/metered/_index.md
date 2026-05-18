---
title: Metered
second_title: Aspose.Drawing for Java API संदर्भ
description: इंटीग्रेशन के लिए मीटरड मेथड्स प्रदान करता है।
type: docs
weight: 10
url: /hi/java/com.aspose.drawing.dynabic.metered/metered/
---
**Inheritance:**
java.lang.Object
```
public class Metered
```

इंटीग्रेशन के लिए मीटरड मेथड्स प्रदान करता है।

इस उदाहरण में, मीटर किए गए सार्वजनिक और निजी कुंजी सेट करने का प्रयास किया जाएगा।

`// the component jar file: Metered matered = new Metered(); matered.setMeteredKey("PublicKey", "PrivateKey"); `
## निर्माता

| निर्माता | विवरण |
| --- | --- |
| [Metered()](#Metered--) |  |
## मेथड्स

| विधि | विवरण |
| --- | --- |
| [getConsumptionQuantity()](#getConsumptionQuantity--) | उपभोग फ़ाइल आकार प्राप्त करता है |
| [getConsumptionCredit()](#getConsumptionCredit--) | उपभोग क्रेडिट प्राप्त करता है |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | मीटरड सार्वजनिक और निजी कुंजी सेट करता है |
| [equals(Object obj)](#equals-java.lang.Object-) | निर्धारित करता है कि निर्दिष्ट ऑब्जेक्ट इस इंस्टेंस के बराबर है या नहीं। |
### Metered() {#Metered--}
```
public Metered()
```


### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static BigDecimal getConsumptionQuantity()
```


उपभोग फ़ाइल आकार प्राप्त करता है

**Returns:**
java.math.BigDecimal - उपभोग फ़ाइल आकार
### getConsumptionCredit() {#getConsumptionCredit--}
```
public static BigDecimal getConsumptionCredit()
```


उपभोग क्रेडिट प्राप्त करता है

**Returns:**
java.math.BigDecimal - उपभोग मात्रा
### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public void setMeteredKey(String publicKey, String privateKey)
```


मीटरड सार्वजनिक और निजी कुंजी सेट करता है

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| publicKey | java.lang.String | सार्वजनिक कुंजी |
| privateKey | java.lang.String | निजी कुंजी |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


निर्धारित करता है कि निर्दिष्ट ऑब्जेक्ट इस इंस्टेंस के बराबर है या नहीं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | java.lang.Object | इस उदाहरण के साथ तुलना करने के लिए ऑब्जेक्ट। |

**Returns:**
boolean - यदि निर्दिष्ट ऑब्जेक्ट इस उदाहरण के बराबर है तो `true`; अन्यथा `false`।
