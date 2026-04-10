---
title: ColorTranslator
second_title: Aspose.Drawing for Java API संदर्भ
description: रंगों को GDI संरचनाओं से और उनमें अनुवादित करता है।
type: docs
weight: 16
url: /hi/java/com.aspose.drawing/colortranslator/
---
**Inheritance:**
java.lang.Object
```
public final class ColorTranslator
```

रंगों को GDI+ [Color](../../com.aspose.drawing/color) संरचनाओं से और उनमें अनुवादित करता है। यह क्लास विरासत में नहीं ली जा सकती।
## निर्माता

| निर्माता | विवरण |
| --- | --- |
| [ColorTranslator()](#ColorTranslator--) |  |
## मेथड्स

| विधि | विवरण |
| --- | --- |
| [fromHtml(String htmlColor)](#fromHtml-java.lang.String-) | HTML रंग प्रतिनिधित्व को GDI+ [Color](../../com.aspose.drawing/color) संरचना में अनुवादित करता है। |
| [toHtml(Color c)](#toHtml-com.aspose.drawing.Color-) | निर्दिष्ट [Color](../../com.aspose.drawing/color) संरचना को HTML स्ट्रिंग रंग प्रतिनिधित्व में अनुवादित करता है। |
| [fromWin32(int win32Color)](#fromWin32-int-) | Windows रंग मान को GDI+ [Color](../../com.aspose.drawing/color) संरचना में अनुवादित करता है। |
| [fromOle(int oleColor)](#fromOle-int-) | OLE रंग मान को GDI+ [Color](../../com.aspose.drawing/color) संरचना में अनुवादित करता है। |
| [toWin32(Color c)](#toWin32-com.aspose.drawing.Color-) | [Color](../../com.aspose.drawing/color) संरचना को Win32 रंग प्रस्तुति में परिवर्तित करता है। |
| [toOle(Color c)](#toOle-com.aspose.drawing.Color-) | [Color](../../com.aspose.drawing/color) संरचना को OLE रंग प्रस्तुति में परिवर्तित करता है। |
### ColorTranslator() {#ColorTranslator--}
```
public ColorTranslator()
```


### fromHtml(String htmlColor) {#fromHtml-java.lang.String-}
```
public static Color fromHtml(String htmlColor)
```


HTML रंग प्रतिनिधित्व को GDI+ [Color](../../com.aspose.drawing/color) संरचना में अनुवादित करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| htmlColor | java.lang.String | अनुवाद करने के लिए Html रंग की स्ट्रिंग प्रतिनिधित्व। |

**Returns:**
[Color](../../com.aspose.drawing/color) - The [Color](../../com.aspose.drawing/color) structure that represents the translated HTML color or `Empty` if htmlColor is null.
### toHtml(Color c) {#toHtml-com.aspose.drawing.Color-}
```
public static String toHtml(Color c)
```


निर्दिष्ट [Color](../../com.aspose.drawing/color) संरचना को HTML स्ट्रिंग रंग प्रतिनिधित्व में अनुवादित करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| c | [Color](../../com.aspose.drawing/color) | अनुवाद करने हेतु [Color](../../com.aspose.drawing/color) संरचना। |

**Returns:**
java.lang.String - वह स्ट्रिंग जो HTML रंग का प्रतिनिधित्व करती है।
### fromWin32(int win32Color) {#fromWin32-int-}
```
public static Color fromWin32(int win32Color)
```


Windows रंग मान को GDI+ [Color](../../com.aspose.drawing/color) संरचना में अनुवादित करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| win32Color | int | अनुवाद करने हेतु Windows रंग। |

**Returns:**
[Color](../../com.aspose.drawing/color) - The [Color](../../com.aspose.drawing/color) structure that represents the translated Windows color.
### fromOle(int oleColor) {#fromOle-int-}
```
public static Color fromOle(int oleColor)
```


OLE रंग मान को GDI+ [Color](../../com.aspose.drawing/color) संरचना में अनुवादित करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| oleColor | int | अनुवाद करने हेतु OLE रंग। |

**Returns:**
[Color](../../com.aspose.drawing/color) - The [Color](../../com.aspose.drawing/color) structure that represents the translated OLE color.
### toWin32(Color c) {#toWin32-com.aspose.drawing.Color-}
```
public static int toWin32(Color c)
```


[Color](../../com.aspose.drawing/color) संरचना को Win32 रंग प्रस्तुति में परिवर्तित करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| c | [Color](../../com.aspose.drawing/color) | परिवर्तित करने के लिए [Color](../../com.aspose.drawing/color) संरचना। |

**Returns:**
int - वह मान जो Win32 स्वरूप के रंग को दर्शाता है।
### toOle(Color c) {#toOle-com.aspose.drawing.Color-}
```
public static int toOle(Color c)
```


[Color](../../com.aspose.drawing/color) संरचना को OLE रंग प्रस्तुति में परिवर्तित करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| c | [Color](../../com.aspose.drawing/color) | परिवर्तित करने के लिए [Color](../../com.aspose.drawing/color) संरचना। |

**Returns:**
int - वह मान जो OLE स्वरूप के रंग को दर्शाता है।
