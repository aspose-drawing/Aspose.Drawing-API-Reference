---
title: PageSettings
second_title: Aspose.Drawing for Java API संदर्भ
description: ऐसे सेटिंग्स को निर्दिष्ट करता है जो एकल मुद्रित पृष्ठ पर लागू होते हैं।
type: docs
weight: 10
url: /hi/java/com.aspose.drawing.printing/pagesettings/
---
**Inheritance:**
java.lang.Object
```
public class PageSettings
```

एकल, मुद्रित पृष्ठ पर लागू होने वाली सेटिंग्स को निर्दिष्ट करता है।
## निर्माता

| निर्माता | विवरण |
| --- | --- |
| [PageSettings()](#PageSettings--) |  |
## मेथड्स

| विधि | विवरण |
| --- | --- |
| [getBounds()](#getBounds--) | पृष्ठ का आकार प्राप्त करता है, जिसमें [PageSettings](../../com.aspose.drawing.printing/pagesettings) प्रॉपर्टी द्वारा निर्दिष्ट पृष्ठ अभिविन्यास को ध्यान में रखा जाता है। |
| [getHardMarginX()](#getHardMarginX--) | पृष्ठ के बाएँ तरफ़ हार्ड मार्जिन का x-निर्देशांक, इंच के सैकड़ों हिस्सों में, प्राप्त करता है। |
| [getHardMarginY()](#getHardMarginY--) | पृष्ठ के शीर्ष पर हार्ड मार्जिन का y-निर्देशांक, इंच के सैकड़ों हिस्सों में, प्राप्त करता है। |
| [getPrinterResolution()](#getPrinterResolution--) | पृष्ठ के लिए प्रिंटर रिज़ॉल्यूशन प्राप्त करता है। |
### PageSettings() {#PageSettings--}
```
public PageSettings()
```


### getBounds() {#getBounds--}
```
public final Rectangle getBounds()
```


पृष्ठ का आकार प्राप्त करता है, जिसमें [PageSettings](../../com.aspose.drawing.printing/pagesettings) प्रॉपर्टी द्वारा निर्दिष्ट पृष्ठ अभिविन्यास को ध्यान में रखा जाता है।

**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle) - A [Rectangle](../../com.aspose.drawing/rectangle) that represents the length and width, in hundredths of an inch, of the page.
### getHardMarginX() {#getHardMarginX--}
```
public final float getHardMarginX()
```


पृष्ठ के बाएँ तरफ़ हार्ड मार्जिन का x-निर्देशांक, इंच के सैकड़ों हिस्सों में, प्राप्त करता है।

**Returns:**
float - बाएँ‑हाथ हार्ड मार्जिन का x-निर्देशांक, इंच के सैकड़ों हिस्सों में।
### getHardMarginY() {#getHardMarginY--}
```
public final float getHardMarginY()
```


पृष्ठ के शीर्ष पर हार्ड मार्जिन का y-निर्देशांक, इंच के सैकड़ों हिस्सों में, प्राप्त करता है।

**Returns:**
float - पृष्ठ के शीर्ष पर हार्ड मार्जिन का y-निर्देशांक, इंच के सैकड़ों हिस्सों में।
### getPrinterResolution() {#getPrinterResolution--}
```
public final PrinterResolution getPrinterResolution()
```


पृष्ठ के लिए प्रिंटर रिज़ॉल्यूशन प्राप्त करता है।

**Returns:**
[PrinterResolution](../../com.aspose.drawing.printing/printerresolution) - A `PrinterResolution`([.getPrinterResolution](../../null/\#getPrinterResolution)) that specifies the printer resolution for the page. The default is the printer's default resolution.
