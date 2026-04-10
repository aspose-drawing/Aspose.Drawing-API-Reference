---
title: MeteredExt
second_title: Aspose.Drawing for Java API संदर्भ
description: मीटरयुक्त कुंजी सेट करने के लिए मेथड प्रदान करता है।
type: docs
weight: 33
url: /hi/java/com.aspose.drawing/meteredext/
---
**Inheritance:**
java.lang.Object, [com.aspose.drawing.dynabic.metered.Metered](../../com.aspose.drawing.dynabic.metered/metered)

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public final class MeteredExt extends Metered implements System.IDisposable
```

मीटरयुक्त कुंजी सेट करने के लिए मेथड प्रदान करता है।

--------------------

> ```
> In this example, an attempt will be made to set metered public and private key
>  
>  `
>  
>  [C#]
>  Metered matered = new Metered();
>  matered.SetMeteredKey("PublicKey", "PrivateKey");
>  [Visual Basic]
>  Dim matered As Metered = New Metered
>  matered.SetMeteredKey("PublicKey", "PrivateKey")
>  
>  `
>  
>  `
>  the component jar file:
>  
>  Metered matered = new Metered();
>  matered.setMeteredKey("PublicKey", "PrivateKey");
>  
>  `
> ```
## निर्माता

| निर्माता | विवरण |
| --- | --- |
| [MeteredExt()](#MeteredExt--) | नए [Metered](../../com.aspose.drawing.dynabic.metered/metered) क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है। |
## मेथड्स

| विधि | विवरण |
| --- | --- |
| [getConsumptionQuantity()](#getConsumptionQuantity--) | उपभोग फ़ाइल आकार प्राप्त करता है। |
| [getConsumptionCredit()](#getConsumptionCredit--) | उपभोग क्रेडिट प्राप्त करता है। |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | मीटरड सार्वजनिक और निजी कुंजी सेट करता है |
| [dispose()](#dispose--) | अनुप्रयोग-परिभाषित कार्यों को निष्पादित करता है जो अनप्रबंधित संसाधनों को मुक्त करने, रिलीज़ करने या रीसेट करने से संबंधित हैं। |
### MeteredExt() {#MeteredExt--}
```
public MeteredExt()
```


नए [Metered](../../com.aspose.drawing.dynabic.metered/metered) क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है।

### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static BigDecimal getConsumptionQuantity()
```


उपभोग फ़ाइल आकार प्राप्त करता है।

**Returns:**
java.math.BigDecimal - उपभोग मात्रा लौटाता है
### getConsumptionCredit() {#getConsumptionCredit--}
```
public static BigDecimal getConsumptionCredit()
```


उपभोग क्रेडिट प्राप्त करता है।

**Returns:**
java.math.BigDecimal - उपभोग मात्रा लौटाता है
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

### dispose() {#dispose--}
```
public void dispose()
```


अनुप्रयोग-परिभाषित कार्यों को निष्पादित करता है जो अनप्रबंधित संसाधनों को मुक्त करने, रिलीज़ करने या रीसेट करने से संबंधित हैं।

