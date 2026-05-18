---
title: PrinterSettings
second_title: Aspose.Drawing for Java API संदर्भ
description: एक दस्तावेज़ कैसे प्रिंट किया जाता है, इस बारे में जानकारी निर्दिष्ट करता है, जिसमें वह प्रिंटर शामिल है जो Windows Forms एप्लिकेशन से प्रिंट करते समय इसे प्रिंट करता है।
type: docs
weight: 16
url: /hi/java/com.aspose.drawing.printing/printersettings/
---
**Inheritance:**
java.lang.Object
```
public class PrinterSettings
```

विंडोज़ फ़ॉर्म्स एप्लिकेशन से प्रिंट करते समय दस्तावेज़ कैसे प्रिंट होता है, जिसमें उसे प्रिंट करने वाला प्रिंटर शामिल है, इस बारे में जानकारी निर्दिष्ट करता है।
## निर्माता

| निर्माता | विवरण |
| --- | --- |
| [PrinterSettings()](#PrinterSettings--) |  |
## मेथड्स

| विधि | विवरण |
| --- | --- |
| [getFromPage()](#getFromPage--) | प्रिंट करने के लिए पहले पृष्ठ का पृष्ठ संख्या प्राप्त करता है। |
| [getPrintRange()](#getPrintRange--) | उपयोगकर्ता द्वारा निर्दिष्ट किए गए प्रिंट किए जाने वाले पृष्ठ संख्याएँ प्राप्त करता है। |
| [getToPage()](#getToPage--) | प्रिंट करने के लिए अंतिम पृष्ठ की संख्या प्राप्त करता है। |
| [getPrinterName()](#getPrinterName--) | उपयोग करने वाले प्रिंटर का नाम प्राप्त करता है। |
| [setPrinterName(String value)](#setPrinterName-java.lang.String-) | उपयोग करने वाले प्रिंटर का नाम सेट करता है। |
### PrinterSettings() {#PrinterSettings--}
```
public PrinterSettings()
```


### getFromPage() {#getFromPage--}
```
public static int getFromPage()
```


प्रिंट करने के लिए पहले पृष्ठ का पृष्ठ संख्या प्राप्त करता है।

**Returns:**
int - प्रिंट करने के लिए पहले पृष्ठ की पृष्ठ संख्या।
### getPrintRange() {#getPrintRange--}
```
public static int getPrintRange()
```


उपयोगकर्ता द्वारा निर्दिष्ट किए गए प्रिंट किए जाने वाले पृष्ठ संख्याएँ प्राप्त करता है।

**Returns:**
int - `PrintRange`([.getPrintRange](../../null/\#getPrintRange)) मानों में से एक।
### getToPage() {#getToPage--}
```
public static int getToPage()
```


प्रिंट करने के लिए अंतिम पृष्ठ की संख्या प्राप्त करता है।

**Returns:**
int - प्रिंट करने के लिए अंतिम पृष्ठ की संख्या।
### getPrinterName() {#getPrinterName--}
```
public final String getPrinterName()
```


उपयोग करने वाले प्रिंटर का नाम प्राप्त करता है।

**Returns:**
java.lang.String - उपयोग करने वाले प्रिंटर का नाम।
### setPrinterName(String value) {#setPrinterName-java.lang.String-}
```
public final void setPrinterName(String value)
```


उपयोग करने वाले प्रिंटर का नाम सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String | उपयोग करने वाले प्रिंटर का नाम। |

