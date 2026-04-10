---
title: License
second_title: Aspose.Drawing for Java API संदर्भ
description: घटक को लाइसेंस करने के लिए मेथड प्रदान करता है।
type: docs
weight: 32
url: /hi/java/com.aspose.drawing/license/
---
**Inheritance:**
java.lang.Object
```
public class License
```

घटक को लाइसेंस करने के लिए मेथड प्रदान करता है।

--------------------

> ```
> In this example, an attempt will be made to find a license file named MyLicense.lic
>  in the folder that contains
>  `
>  the component, in the folder that contains the calling assembly,
>  in the folder of the entry assembly and then in the embedded resources of the calling assembly.
>  
>  [C#]
>  License license = new License();
>  license.SetLicense("MyLicense.lic");
>  
>  `
> ```
## निर्माता

| निर्माता | विवरण |
| --- | --- |
| [License()](#License--) | इस क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है। |
## मेथड्स

| विधि | विवरण |
| --- | --- |
| [setLicense(String licenseName)](#setLicense-java.lang.String-) | घटक को लाइसेंस देता है। |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream-) | घटक को लाइसेंस देता है। |
### License() {#License--}
```
public License()
```


इस क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है।

--------------------

> ```
> In this example, an attempt will be made to find a license file named MyLicense.lic
>  in the folder that contains
>  `
>  the component, in the folder that contains the calling assembly,
>  in the folder of the entry assembly and then in the embedded resources of the calling assembly.
>  
>  [C#]
>  License license = new License();
>  license.SetLicense("MyLicense.lic");
>  [Visual Basic]
>  Dim license As license = New license
>  License.SetLicense("MyLicense.lic")
>  
>  `
>  `
>  the component jar file:
>  
>  License license = new License();
>  license.setLicense("MyLicense.lic");
>  
>  `
> ```

### setLicense(String licenseName) {#setLicense-java.lang.String-}
```
public final void setLicense(String licenseName)
```


घटक को लाइसेंस देता है।

--------------------

> ```
> In this example, an attempt will be made to find a license file named MyLicense.lic
>  in the folder that contains
>  `
>  the component, in the folder that contains the calling assembly,
>  in the folder of the entry assembly and then in the embedded resources of the calling assembly.
>  
>  [C#]
>  License license = new License();
>  license.SetLicense("MyLicense.lic");
>  [Visual Basic]
>  Dim license As License = New License
>  license.SetLicense("MyLicense.lic")
>  
>  `
>  `
>  the component jar file:
>  
>  License license = new License();
>  license.setLicense("MyLicense.lic");
>  
>  `
> ```

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | licenseName | java.lang.String | पूर्ण या छोटा फ़ाइल नाम` या एम्बेडेड रिसोर्स का नाम` हो सकता है। मूल्यांकन मोड में स्विच करने के लिए खाली स्ट्रिंग का उपयोग करें। |

--------------------

KKKCODEB

लाइसेंस को निम्नलिखित स्थानों में खोजने का प्रयास करता है:

KKKCODEE KKKCODEB

1. स्पष्ट पथ।

KKKCODEE KKKCODEB

2. वह फ़ोल्डर जिसमें Aspose घटक असेंबली शामिल है।

3. वह फ़ोल्डर जिसमें क्लाइंट की कॉलिंग असेंबली शामिल है।

4. वह फ़ोल्डर जिसमें एंट्री (स्टार्टअप) असेंबली शामिल है।

5. क्लाइंट की कॉलिंग असेंबली में एक एम्बेडेड रिसोर्स।

**Note:**On the .NET Compact Framework, tries to find the license only in these locations:

1. स्पष्ट पथ।

2. क्लाइंट की कॉलिंग असेंबली में एक एम्बेडेड रिसोर्स।

KKKCODEE KKKCODEB

2. वह फ़ोल्डर जिसमें Aspose घटक JAR फ़ाइल शामिल है।

3. वह फ़ोल्डर जिसमें क्लाइंट की कॉलिंग JAR फ़ाइल शामिल है।

KKKCODEE |

### setLicense(InputStream stream) {#setLicense-java.io.InputStream-}
```
public final void setLicense(InputStream stream)
```


घटक को लाइसेंस देता है।

--------------------

> ```
> `
>  [C#]
>  License license = new License();
>  license.SetLicense(myStream);
>  [Visual Basic]
>  Dim license as License = new License
>  license.SetLicense(myStream)
>  `
>  `
>  License license = new License();
>  license.setLicense(myStream);
>  `
> ```

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | स्ट्रीम | java.io.InputStream | एक स्ट्रीम जिसमें लाइसेंस शामिल है। |

--------------------

KKKCODEB

स्ट्रीम से लाइसेंस लोड करने के लिए इस मेथड का उपयोग करें।

KKKCODEE

`void setLicense(java.io.InputStream stream)` |

