---
title: StringFormat
second_title: Aspose.Drawing for Java API संदर्भ
description: पाठ लेआउट जानकारी को संलग्न करता है जैसे संरेखण दिशा, टैब स्टॉप्स, डिस्प्ले हेरफेर जैसे एलिप्सिस डालना, राष्ट्रीय अंक प्रतिस्थापन और OpenType सुविधाएँ।
type: docs
weight: 47
url: /hi/java/com.aspose.drawing/stringformat/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public final class StringFormat implements System.IDisposable
```

पाठ लेआउट जानकारी (जैसे संरेखण, अभिविन्यास और टैब स्टॉप) और प्रदर्शन हेरफेर (जैसे एलिप्सिस सम्मिलन और राष्ट्रीय अंक प्रतिस्थापन) तथा OpenType सुविधाओं को संलग्न करता है। इस क्लास को विरासत में नहीं लिया जा सकता।
## निर्माता

| निर्माता | विवरण |
| --- | --- |
| [StringFormat()](#StringFormat--) | नए [StringFormat](../../com.aspose.drawing/stringformat) क्लास का एक नया उदाहरण आरंभ करता है। |
| [StringFormat(StringFormat format)](#StringFormat-com.aspose.drawing.StringFormat-) | निर्दिष्ट मौजूदा [StringFormat](../../com.aspose.drawing/stringformat) ऑब्जेक्ट से नए [StringFormat](../../com.aspose.drawing/stringformat) क्लास का एक नया उदाहरण आरंभ करता है। |
| [StringFormat(int options, int language)](#StringFormat-int-int-) | निर्दिष्ट [StringFormatFlags](../../com.aspose.drawing/stringformatflags) एन्न्यूमरेशन और भाषा के साथ नए [StringFormat](../../com.aspose.drawing/stringformat) क्लास का एक नया उदाहरण आरंभ करता है। |
| [StringFormat(int options)](#StringFormat-int-) | निर्दिष्ट [StringFormatFlags](../../com.aspose.drawing/stringformatflags) एन्न्यूमरेशन के साथ नए [StringFormat](../../com.aspose.drawing/stringformat) क्लास का एक नया उदाहरण आरंभ करता है। |
## मेथड्स

| विधि | विवरण |
| --- | --- |
| [setDigitSubstitutionLanguage(int value)](#setDigitSubstitutionLanguage-int-) |  |
| [setDigitSubstitutionMethod(int value)](#setDigitSubstitutionMethod-int-) |  |
| [getFirstTabOffset()](#getFirstTabOffset--) |  |
| [getGenericDefault()](#getGenericDefault--) | एक सामान्य डिफ़ॉल्ट [StringFormat](../../com.aspose.drawing/stringformat) ऑब्जेक्ट प्राप्त करता है। |
| [getGenericTypographic()](#getGenericTypographic--) | एक सामान्य टाइपोग्राफिक [StringFormat](../../com.aspose.drawing/stringformat) ऑब्जेक्ट प्राप्त करता है। |
| [getFormatFlags()](#getFormatFlags--) | [StringFormatFlags](../../com.aspose.drawing/stringformatflags) एन्न्यूमरेशन जो फ़ॉर्मेटिंग जानकारी रखता है, उसे प्राप्त या सेट करता है। |
| [setFormatFlags(int value)](#setFormatFlags-int-) | [StringFormatFlags](../../com.aspose.drawing/stringformatflags) एन्न्यूमरेशन जो फ़ॉर्मेटिंग जानकारी रखता है, उसे प्राप्त या सेट करता है। |
| [getAlignment()](#getAlignment--) | ऊर्ध्वाधर तल पर पाठ संरेखण जानकारी को प्राप्त या सेट करता है। |
| [setAlignment(int value)](#setAlignment-int-) | ऊर्ध्वाधर तल पर पाठ संरेखण जानकारी को प्राप्त या सेट करता है। |
| [getLineAlignment()](#getLineAlignment--) | क्षैतिज तल पर लाइन संरेखण को प्राप्त या सेट करता है। |
| [setLineAlignment(int value)](#setLineAlignment-int-) | क्षैतिज तल पर लाइन संरेखण को प्राप्त या सेट करता है। |
| [getHotkeyPrefix()](#getHotkeyPrefix--) | इस [StringFormat](../../com.aspose.drawing/stringformat) ऑब्जेक्ट के लिए `HotkeyPrefix`([.getHotkeyPrefix](../../null/\#getHotkeyPrefix)/[.setHotkeyPrefix(int)](../../null/\#setHotkeyPrefix-int-)) ऑब्जेक्ट को प्राप्त या सेट करता है। |
| [setHotkeyPrefix(int value)](#setHotkeyPrefix-int-) | इस [StringFormat](../../com.aspose.drawing/stringformat) ऑब्जेक्ट के लिए `HotkeyPrefix`([.getHotkeyPrefix](../../null/\#getHotkeyPrefix)/[.setHotkeyPrefix(int)](../../null/\#setHotkeyPrefix-int-)) ऑब्जेक्ट को प्राप्त या सेट करता है। |
| [getTrimming()](#getTrimming--) | इस [StringFormat](../../com.aspose.drawing/stringformat) ऑब्जेक्ट के लिए [StringTrimming](../../com.aspose.drawing/stringtrimming) एन्न्यूमरेशन को प्राप्त या सेट करता है। |
| [setTrimming(int value)](#setTrimming-int-) | इस [StringFormat](../../com.aspose.drawing/stringformat) ऑब्जेक्ट के लिए [StringTrimming](../../com.aspose.drawing/stringtrimming) एन्न्यूमरेशन को प्राप्त या सेट करता है। |
| [getDigitSubstitutionLanguage()](#getDigitSubstitutionLanguage--) | उस भाषा को प्राप्त करता है जिसका उपयोग स्थानीय अंकों को पश्चिमी अंकों के स्थान पर प्रतिस्थापित करने पर किया जाता है। |
| [getDigitSubstitutionMethod()](#getDigitSubstitutionMethod--) | अंक प्रतिस्थापन के लिए उपयोग की जाने वाली विधि को प्राप्त करता है। |
| [dispose()](#dispose--) | इस [StringFormat](../../com.aspose.drawing/stringformat) ऑब्जेक्ट द्वारा उपयोग किए गए सभी संसाधनों को मुक्त करता है। |
| [deepClone()](#deepClone--) | इस [StringFormat](../../com.aspose.drawing/stringformat) ऑब्जेक्ट की एक सटीक प्रति बनाता है। |
| [getTabStops(float[] firstTabOffset)](#getTabStops-float---) | इस [StringFormat](../../com.aspose.drawing/stringformat) ऑब्जेक्ट के टैब स्टॉप्स को प्राप्त करता है। |
| [getTabStops()](#getTabStops--) | `Aspose.Imaging.getGraphics().PageUnit` प्रॉपर्टी द्वारा निर्दिष्ट इकाइयों में टैब स्टॉप्स के बीच की दूरी की एक सरणी प्राप्त करता है। |
| [setTabStops(float firstTabOffset, float[] tabStops)](#setTabStops-float-float---) | इस [StringFormat](../../com.aspose.drawing/stringformat) ऑब्जेक्ट के लिए टैब स्टॉप्स सेट करता है। |
| [setDigitSubstitution(int language, int substitute)](#setDigitSubstitution-int-int-) | स्थानीय अंकों को पश्चिमी अंकों के स्थान पर प्रतिस्थापित करने पर उपयोग की जाने वाली भाषा और विधि को निर्दिष्ट करता है। |
| [setMeasurableCharacterRanges(CharacterRange[] ranges)](#setMeasurableCharacterRanges-com.aspose.drawing.CharacterRange---) | `MeasureCharacterRanges` विधि के कॉल द्वारा मापे गए अक्षर रेंजों को दर्शाने वाले [CharacterRange](../../com.aspose.drawing/characterrange) संरचनाओं की एक सरणी को निर्दिष्ट करता है। |
### StringFormat() {#StringFormat--}
```
public StringFormat()
```


नए [StringFormat](../../com.aspose.drawing/stringformat) क्लास का एक नया उदाहरण आरंभ करता है।

### StringFormat(StringFormat format) {#StringFormat-com.aspose.drawing.StringFormat-}
```
public StringFormat(StringFormat format)
```


निर्दिष्ट मौजूदा [StringFormat](../../com.aspose.drawing/stringformat) ऑब्जेक्ट से नए [StringFormat](../../com.aspose.drawing/stringformat) क्लास का एक नया उदाहरण आरंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| format | [StringFormat](../../com.aspose.drawing/stringformat) | नए [StringFormat](../../com.aspose.drawing/stringformat) ऑब्जेक्ट को आरंभ करने के लिए उपयोग किया जाने वाला [StringFormat](../../com.aspose.drawing/stringformat) ऑब्जेक्ट। |

### StringFormat(int options, int language) {#StringFormat-int-int-}
```
public StringFormat(int options, int language)
```


निर्दिष्ट [StringFormatFlags](../../com.aspose.drawing/stringformatflags) एन्न्यूमरेशन और भाषा के साथ नए [StringFormat](../../com.aspose.drawing/stringformat) क्लास का एक नया उदाहरण आरंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| options | int | नए [StringFormat](../../com.aspose.drawing/stringformat) ऑब्जेक्ट के लिए [StringFormatFlags](../../com.aspose.drawing/stringformatflags) एन्न्यूमरेशन। |
| भाषा | int | एक मान जो पाठ की भाषा को दर्शाता है। |

### StringFormat(int options) {#StringFormat-int-}
```
public StringFormat(int options)
```


निर्दिष्ट [StringFormatFlags](../../com.aspose.drawing/stringformatflags) एन्न्यूमरेशन के साथ नए [StringFormat](../../com.aspose.drawing/stringformat) क्लास का एक नया उदाहरण आरंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| options | int | नए [StringFormat](../../com.aspose.drawing/stringformat) ऑब्जेक्ट के लिए [StringFormatFlags](../../com.aspose.drawing/stringformatflags) एन्न्यूमरेशन। |

### setDigitSubstitutionLanguage(int value) {#setDigitSubstitutionLanguage-int-}
```
public void setDigitSubstitutionLanguage(int value)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### setDigitSubstitutionMethod(int value) {#setDigitSubstitutionMethod-int-}
```
public void setDigitSubstitutionMethod(int value)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getFirstTabOffset() {#getFirstTabOffset--}
```
public float getFirstTabOffset()
```




**Returns:**
फ़्लोट
### getGenericDefault() {#getGenericDefault--}
```
public static StringFormat getGenericDefault()
```


एक सामान्य डिफ़ॉल्ट [StringFormat](../../com.aspose.drawing/stringformat) ऑब्जेक्ट प्राप्त करता है।

**Returns:**
[StringFormat](../../com.aspose.drawing/stringformat)
### getGenericTypographic() {#getGenericTypographic--}
```
public static StringFormat getGenericTypographic()
```


एक सामान्य टाइपोग्राफिक [StringFormat](../../com.aspose.drawing/stringformat) ऑब्जेक्ट प्राप्त करता है।

**Returns:**
[StringFormat](../../com.aspose.drawing/stringformat) - A generic typographic [StringFormat](../../com.aspose.drawing/stringformat) object.
### getFormatFlags() {#getFormatFlags--}
```
public int getFormatFlags()
```


[StringFormatFlags](../../com.aspose.drawing/stringformatflags) एन्न्यूमरेशन जो फ़ॉर्मेटिंग जानकारी रखता है, उसे प्राप्त या सेट करता है।

**Returns:**
int
### setFormatFlags(int value) {#setFormatFlags-int-}
```
public void setFormatFlags(int value)
```


[StringFormatFlags](../../com.aspose.drawing/stringformatflags) एन्न्यूमरेशन जो फ़ॉर्मेटिंग जानकारी रखता है, उसे प्राप्त या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getAlignment() {#getAlignment--}
```
public int getAlignment()
```


ऊर्ध्वाधर तल पर पाठ संरेखण जानकारी को प्राप्त या सेट करता है।

**Returns:**
int
### setAlignment(int value) {#setAlignment-int-}
```
public void setAlignment(int value)
```


ऊर्ध्वाधर तल पर पाठ संरेखण जानकारी को प्राप्त या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getLineAlignment() {#getLineAlignment--}
```
public int getLineAlignment()
```


क्षैतिज तल पर लाइन संरेखण को प्राप्त या सेट करता है।

**Returns:**
int
### setLineAlignment(int value) {#setLineAlignment-int-}
```
public void setLineAlignment(int value)
```


क्षैतिज तल पर लाइन संरेखण को प्राप्त या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getHotkeyPrefix() {#getHotkeyPrefix--}
```
public int getHotkeyPrefix()
```


इस [StringFormat](../../com.aspose.drawing/stringformat) ऑब्जेक्ट के लिए `HotkeyPrefix`([.getHotkeyPrefix](../../null/\#getHotkeyPrefix)/[.setHotkeyPrefix(int)](../../null/\#setHotkeyPrefix-int-)) ऑब्जेक्ट को प्राप्त या सेट करता है।

**Returns:**
int
### setHotkeyPrefix(int value) {#setHotkeyPrefix-int-}
```
public void setHotkeyPrefix(int value)
```


इस [StringFormat](../../com.aspose.drawing/stringformat) ऑब्जेक्ट के लिए `HotkeyPrefix`([.getHotkeyPrefix](../../null/\#getHotkeyPrefix)/[.setHotkeyPrefix(int)](../../null/\#setHotkeyPrefix-int-)) ऑब्जेक्ट को प्राप्त या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getTrimming() {#getTrimming--}
```
public int getTrimming()
```


इस [StringFormat](../../com.aspose.drawing/stringformat) ऑब्जेक्ट के लिए [StringTrimming](../../com.aspose.drawing/stringtrimming) एन्न्यूमरेशन को प्राप्त या सेट करता है।

**Returns:**
int
### setTrimming(int value) {#setTrimming-int-}
```
public void setTrimming(int value)
```


इस [StringFormat](../../com.aspose.drawing/stringformat) ऑब्जेक्ट के लिए [StringTrimming](../../com.aspose.drawing/stringtrimming) एन्न्यूमरेशन को प्राप्त या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getDigitSubstitutionLanguage() {#getDigitSubstitutionLanguage--}
```
public int getDigitSubstitutionLanguage()
```


उस भाषा को प्राप्त करता है जिसका उपयोग स्थानीय अंकों को पश्चिमी अंकों के स्थान पर प्रतिस्थापित करने पर किया जाता है।

**Returns:**
int - एक राष्ट्रीय भाषा समर्थन (NLS) भाषा पहचानकर्ता जो उस भाषा को पहचानता है जिसका उपयोग स्थानीय अंकों को पश्चिमी अंकों के साथ बदलने पर किया जाएगा। आप `System.Globalization.CultureInfo.LCID` प्रॉपर्टी को एक java.util.Locale ऑब्जेक्ट की NLS भाषा पहचानकर्ता के रूप में पास कर सकते हैं। उदाहरण के लिए, मान लीजिए आप एक java.util.Locale ऑब्जेक्ट बनाते हैं और स्ट्रिंग "ar-EG" को java.util.Locale कंस्ट्रक्टर में पास करते हैं। यदि आप उस java.util.Locale ऑब्जेक्ट की `System.Globalization.CultureInfo.LCID` प्रॉपर्टी को `StringDigitSubstitute.Traditional` के साथ [.setDigitSubstitution(int,int)](../../null/\\#setDigitSubstitution-int-int-) मेथड को पास करते हैं, तो अरबी-इंडिक अंक प्रदर्शन समय पर पश्चिमी अंकों के स्थान पर प्रतिस्थापित हो जाएंगे।
### getDigitSubstitutionMethod() {#getDigitSubstitutionMethod--}
```
public int getDigitSubstitutionMethod()
```


अंक प्रतिस्थापन के लिए उपयोग की जाने वाली विधि को प्राप्त करता है।

**Returns:**
int - एक [StringDigitSubstitute](../../com.aspose.drawing/stringdigitsubstitute) एनीमरेशन मान जो यह निर्दिष्ट करता है कि उन अक्षरों को कैसे प्रतिस्थापित किया जाए जो वर्तमान फ़ॉन्ट द्वारा समर्थित न होने के कारण स्ट्रिंग में प्रदर्शित नहीं हो सकते।
### dispose() {#dispose--}
```
public void dispose()
```


इस [StringFormat](../../com.aspose.drawing/stringformat) ऑब्जेक्ट द्वारा उपयोग किए गए सभी संसाधनों को मुक्त करता है।

### deepClone() {#deepClone--}
```
public StringFormat deepClone()
```


इस [StringFormat](../../com.aspose.drawing/stringformat) ऑब्जेक्ट की एक सटीक प्रति बनाता है।

**Returns:**
[StringFormat](../../com.aspose.drawing/stringformat) - The [StringFormat](../../com.aspose.drawing/stringformat) object this method creates.
### getTabStops(float[] firstTabOffset) {#getTabStops-float---}
```
public float[] getTabStops(float[] firstTabOffset)
```


इस [StringFormat](../../com.aspose.drawing/stringformat) ऑब्जेक्ट के टैब स्टॉप्स को प्राप्त करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| firstTabOffset | float[] | टेक्स्ट लाइन की शुरुआत और पहले टैब स्टॉप के बीच के स्पेसेस की संख्या। |

**Returns:**
float[] - टैब स्टॉप्स के बीच की दूरी (स्पेसेस की संख्या में) का एक एरे।
### getTabStops() {#getTabStops--}
```
public float[] getTabStops()
```


`Aspose.Imaging.getGraphics().PageUnit` प्रॉपर्टी द्वारा निर्दिष्ट इकाइयों में टैब स्टॉप्स के बीच की दूरी की एक सरणी प्राप्त करता है।

**Returns:**
float[] - टैब स्टॉप्स।

यह प्रॉपर्टी हटाए गए मेथड GetTabStops के लिए पेश की गई है।
### setTabStops(float firstTabOffset, float[] tabStops) {#setTabStops-float-float---}
```
public void setTabStops(float firstTabOffset, float[] tabStops)
```


इस [StringFormat](../../com.aspose.drawing/stringformat) ऑब्जेक्ट के लिए टैब स्टॉप्स सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| firstTabOffset | फ़्लोट | टेक्स्ट की लाइन की शुरुआत और पहले टैब स्टॉप के बीच के स्पेसेस की संख्या। |
| tabStops | float[] | टैब स्टॉप्स के बीच की दूरी का एक एरे, जो यूनिट्स Graphics.PageUnit प्रॉपर्टी द्वारा निर्दिष्ट होते हैं। |

### setDigitSubstitution(int language, int substitute) {#setDigitSubstitution-int-int-}
```
public void setDigitSubstitution(int language, int substitute)
```


स्थानीय अंकों को पश्चिमी अंकों के स्थान पर प्रतिस्थापित करने पर उपयोग की जाने वाली भाषा और विधि को निर्दिष्ट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| भाषा | int | int - एक राष्ट्रीय भाषा समर्थन (NLS) भाषा पहचानकर्ता जो उस भाषा को पहचानता है जिसका उपयोग स्थानीय अंकों को पश्चिमी अंकों के साथ बदलने पर किया जाएगा। आप `System.Globalization.CultureInfo.LCID` प्रॉपर्टी को एक java.util.Locale ऑब्जेक्ट की NLS भाषा पहचानकर्ता के रूप में पास कर सकते हैं। उदाहरण के लिए, मान लीजिए आप एक java.util.Locale ऑब्जेक्ट बनाते हैं और स्ट्रिंग `"ar-EG"` को java.util.Locale कंस्ट्रक्टर में पास करते हैं। यदि आप उस java.util.Locale ऑब्जेक्ट की `System.Globalization.CultureInfo.LCID` प्रॉपर्टी को `StringDigitSubstitute.Traditional` के साथ `M:StringFormat.SetDigitSubstitution(System.Int32,StringDigitSubstitute)` मेथड को पास करते हैं, तो अरबी-इंडिक अंक प्रदर्शन समय पर पश्चिमी अंकों के स्थान पर प्रतिस्थापित हो जाएंगे। |
| substitute | int | एक [StringDigitSubstitute](../../com.aspose.drawing/stringdigitsubstitute) एनीमरेशन का तत्व जो यह निर्दिष्ट करता है कि अंक कैसे प्रदर्शित किए जाएँ। |

### setMeasurableCharacterRanges(CharacterRange[] ranges) {#setMeasurableCharacterRanges-com.aspose.drawing.CharacterRange---}
```
public void setMeasurableCharacterRanges(CharacterRange[] ranges)
```


`MeasureCharacterRanges` विधि के कॉल द्वारा मापे गए अक्षर रेंजों को दर्शाने वाले [CharacterRange](../../com.aspose.drawing/characterrange) संरचनाओं की एक सरणी को निर्दिष्ट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| ranges | [CharacterRange\[\]](../../com.aspose.drawing/characterrange) | एक एरे जिसमें [CharacterRange](../../com.aspose.drawing/characterrange) संरचनाएँ होती हैं जो `MeasureCharacterRanges` मेथड के कॉल द्वारा मापे गए अक्षरों की रेंज को निर्दिष्ट करती हैं। |

