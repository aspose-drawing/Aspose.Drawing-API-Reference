---
title: Font
second_title: Aspose.Drawing for Java API संदर्भ
description: पाठ के लिए एक विशिष्ट स्वरूप परिभाषित करता है जिसमें फ़ॉन्ट फ़ेस, आकार और शैली के गुण शामिल होते हैं।
type: docs
weight: 21
url: /hi/java/com.aspose.drawing/font/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public final class Font implements System.IDisposable
```

पाठ के लिए एक विशिष्ट स्वरूप परिभाषित करता है, जिसमें फ़ॉन्ट फ़ेस, आकार और शैली के गुण शामिल हैं। इस क्लास को विरासत में नहीं लिया जा सकता।
## निर्माता

| निर्माता | विवरण |
| --- | --- |
| [Font(Font prototype, int newStyle)](#Font-com.aspose.drawing.Font-int-) | नए [Font](../../com.aspose.drawing/font) क्लास का एक नया इंस्टेंस आरंभ करता है, जो निर्दिष्ट मौजूदा [Font](../../com.aspose.drawing/font) और [FontStyle](../../com.aspose.drawing/fontstyle) एन्यूमरेशन का उपयोग करता है। |
| [Font(FontFamily family, float emSize)](#Font-com.aspose.drawing.FontFamily-float-) | Initializes a new instance of the [Font](../../com.aspose.drawing/font) class. |
| [Font(FontFamily family, float emSize, int style)](#Font-com.aspose.drawing.FontFamily-float-int-) | Initializes a new instance of the [Font](../../com.aspose.drawing/font) class using a specified size and style.. |
| [Font(FontFamily family, float emSize, int style, int unit)](#Font-com.aspose.drawing.FontFamily-float-int-int-) | Initializes a new instance of the [Font](../../com.aspose.drawing/font) class using a specified size, style, and unit. |
| [Font(FontFamily family, float emSize, int style, int unit, byte gdiCharSet)](#Font-com.aspose.drawing.FontFamily-float-int-int-byte-) | Initializes a new instance of the [Font](../../com.aspose.drawing/font) class using a specified size, style, unit, and character set.. |
| [Font(FontFamily family, float emSize, int style, int unit, byte gdiCharSet, boolean gdiVerticalFont)](#Font-com.aspose.drawing.FontFamily-float-int-int-byte-boolean-) | Initializes a new instance of the [Font](../../com.aspose.drawing/font) class using a specified size, style, unit, and character set.. |
| [Font(String familyName, float emSize)](#Font-java.lang.String-float-) | Initializes a new instance of the [Font](../../com.aspose.drawing/font) class using a specified size. |
| [Font(String familyName, float emSize, int style)](#Font-java.lang.String-float-int-) | Initializes a new instance of the [Font](../../com.aspose.drawing/font) class using a specified size and style. |
| [Font(String familyName, float emSize, int style, int unit)](#Font-java.lang.String-float-int-int-) | Initializes a new instance of the [Font](../../com.aspose.drawing/font) class using a specified size, style, and unit. |
| [Font(String familyName, float emSize, int style, int unit, byte gdiCharSet)](#Font-java.lang.String-float-int-int-byte-) | Initializes a new instance of the [Font](../../com.aspose.drawing/font) class using a specified size, style, unit, and character set. |
| [Font(String familyName, float emSize, int style, int unit, byte gdiCharSet, boolean gdiVerticalFont)](#Font-java.lang.String-float-int-int-byte-boolean-) | Initializes a new instance of the [Font](../../com.aspose.drawing/font) class using the specified size, style, unit, and character set. |
## मेथड्स

| विधि | विवरण |
| --- | --- |
| [getFontFamily()](#getFontFamily--) | Gets the `FontFamily`([.getFontFamily](../../null/\#getFontFamily)) associated with this [Font](../../com.aspose.drawing/font). |
| [getBold()](#getBold--) | Gets a value indicating whether this [Font](../../com.aspose.drawing/font) is bold. |
| [getGdiCharSet()](#getGdiCharSet--) | Gets a byte value that specifies the GDI character set that this [Font](../../com.aspose.drawing/font) uses. |
| [getGdiVerticalFont()](#getGdiVerticalFont--) | Gets a value indicating whether this [Font](../../com.aspose.drawing/font) is derived from a GDI vertical font.. |
| [getItalic()](#getItalic--) | Gets a value indicating whether this [Font](../../com.aspose.drawing/font) is italic. |
| [getName()](#getName--) | Gets the face name of this [Font](../../com.aspose.drawing/font). |
| [getStrikeout()](#getStrikeout--) | Gets a value indicating whether this [Font](../../com.aspose.drawing/font) specifies a horizontal line through the font. |
| [getUnderline()](#getUnderline--) | Gets a value indicating whether this [Font](../../com.aspose.drawing/font) is underlined. |
| [getStyle()](#getStyle--) | Gets style information for this [Font](../../com.aspose.drawing/font). |
| [getSize()](#getSize--) | Gets the em-size of this [Font](../../com.aspose.drawing/font) measured in the units specified by the `Font.Unit` property. |
| [getSizeInPoints()](#getSizeInPoints--) | Gets the em-size, in points, of this [Font](../../com.aspose.drawing/font). |
| [getUnit()](#getUnit--) | Gets the unit of measure for this [Font](../../com.aspose.drawing/font). |
| [getHeight_Rename_Namesake()](#getHeight-Rename-Namesake--) | Gets the line spacing of this font. |
| [isSystemFont()](#isSystemFont--) | Gets a value indicating whether the font is a member of [SystemFonts](../../com.aspose.drawing/systemfonts). |
| [getSystemFontName()](#getSystemFontName--) | Gets the name of the system font if the IsSystemFont property returns true. |
| [getOriginalFontName()](#getOriginalFontName--) | Gets the name of the font originally specified. |
| [deepClone()](#deepClone--) | Creates an exact copy of this [Font](../../com.aspose.drawing/font). |
| [equals(Object obj)](#equals-java.lang.Object-) | निर्दिष्ट वस्तु एक [Font](../../com.aspose.drawing/font) है या नहीं, और क्या इसके `FontFamily`([.getFontFamily](../../null/\#getFontFamily)), `M:GdiVerticalFont`, `M:GdiCharSet`, `M:Style`, `M:Size`, और `M:Unit` प्रॉपर्टी मान इस [Font](../../com.aspose.drawing/font) के समान हैं। |
| [hashCode()](#hashCode--) | इस [Font](../../com.aspose.drawing/font) के लिए हैश कोड प्राप्त करता है। |
| [getHeight()](#getHeight--) | इस फ़ॉन्ट की पंक्ति अंतराल, पिक्सेल में, लौटाता है। |
| [getHeight(Graphics graphics)](#getHeight-com.aspose.drawing.Graphics-) | निर्दिष्ट [Graphics](../../com.aspose.drawing/graphics) की वर्तमान इकाई में इस फ़ॉन्ट की पंक्ति अंतराल लौटाता है। |
| [getHeight(float dpi)](#getHeight-float-) | निर्दिष्ट ऊर्ध्वाधर रिज़ॉल्यूशन वाले डिवाइस पर खींचे जाने पर इस [Font](../../com.aspose.drawing/font) की ऊँचाई, पिक्सेल में, लौटाता है। |
| [dispose()](#dispose--) | इस [Font](../../com.aspose.drawing/font) द्वारा उपयोग किए गए सभी संसाधनों को मुक्त करता है। |
| [toString()](#toString--) | इस [Font](../../com.aspose.drawing/font) का मानव-पठनीय स्ट्रिंग प्रतिनिधित्व लौटाता है। |
| [getCharacterSet()](#getCharacterSet--) | उस बाइट मान को प्राप्त करता है जो यह निर्दिष्ट करता है कि यह `Font` कौन सा कैरेक्टर सेट उपयोग करता है। |
### Font(Font prototype, int newStyle) {#Font-com.aspose.drawing.Font-int-}
```
public Font(Font prototype, int newStyle)
```


नए [Font](../../com.aspose.drawing/font) क्लास का एक नया इंस्टेंस आरंभ करता है, जो निर्दिष्ट मौजूदा [Font](../../com.aspose.drawing/font) और [FontStyle](../../com.aspose.drawing/fontstyle) एन्यूमरेशन का उपयोग करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| prototype | [Font](../../com.aspose.drawing/font) | नए [Font](../../com.aspose.drawing/font) को बनाने के लिए मौजूदा [Font](../../com.aspose.drawing/font)। |
| newStyle | int | नए [Font](../../com.aspose.drawing/font) पर लागू करने के लिए [FontStyle](../../com.aspose.drawing/fontstyle)। कई [FontStyle](../../com.aspose.drawing/fontstyle) मानों को OR ऑपरेटर के साथ संयोजित किया जा सकता है। |

### Font(FontFamily family, float emSize) {#Font-com.aspose.drawing.FontFamily-float-}
```
public Font(FontFamily family, float emSize)
```


Initializes a new instance of the [Font](../../com.aspose.drawing/font) class.

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| family | [FontFamily](../../com.aspose.drawing/fontfamily) | नए [Font](../../com.aspose.drawing/font) का `FontFamily`([.getFontFamily](../../null/\#getFontFamily))। |
| emSize | फ़्लोट | नए फ़ॉन्ट का em-size, पॉइंट्स में। |

### Font(FontFamily family, float emSize, int style) {#Font-com.aspose.drawing.FontFamily-float-int-}
```
public Font(FontFamily family, float emSize, int style)
```


Initializes a new instance of the [Font](../../com.aspose.drawing/font) class using a specified size and style..

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| family | [FontFamily](../../com.aspose.drawing/fontfamily) | नए [Font](../../com.aspose.drawing/font) का `FontFamily`([.getFontFamily](../../null/\#getFontFamily))। |
| emSize | फ़्लोट | नए फ़ॉन्ट का em-size, पॉइंट्स में। |
| style | int | नए फ़ॉन्ट का [FontStyle](../../com.aspose.drawing/fontstyle)। |

### Font(FontFamily family, float emSize, int style, int unit) {#Font-com.aspose.drawing.FontFamily-float-int-int-}
```
public Font(FontFamily family, float emSize, int style, int unit)
```


Initializes a new instance of the [Font](../../com.aspose.drawing/font) class using a specified size, style, and unit.

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| family | [FontFamily](../../com.aspose.drawing/fontfamily) | नए [Font](../../com.aspose.drawing/font) का `FontFamily`([.getFontFamily](../../null/\#getFontFamily))। |
| emSize | फ़्लोट | `unit` पैरामीटर द्वारा निर्दिष्ट इकाइयों में नए फ़ॉन्ट का em-size। |
| style | int | नए फ़ॉन्ट का [FontStyle](../../com.aspose.drawing/fontstyle)। |
| unit | int | नए फ़ॉन्ट का [GraphicsUnit](../../com.aspose.drawing/graphicsunit)। |

### Font(FontFamily family, float emSize, int style, int unit, byte gdiCharSet) {#Font-com.aspose.drawing.FontFamily-float-int-int-byte-}
```
public Font(FontFamily family, float emSize, int style, int unit, byte gdiCharSet)
```


Initializes a new instance of the [Font](../../com.aspose.drawing/font) class using a specified size, style, unit, and character set..

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| family | [FontFamily](../../com.aspose.drawing/fontfamily) | नए [Font](../../com.aspose.drawing/font) का `FontFamily`([.getFontFamily](../../null/\#getFontFamily))। |
| emSize | फ़्लोट | `unit` पैरामीटर द्वारा निर्दिष्ट इकाइयों में नए फ़ॉन्ट का em-size। |
| style | int | नए फ़ॉन्ट का [FontStyle](../../com.aspose.drawing/fontstyle)। |
| unit | int | नए फ़ॉन्ट का [GraphicsUnit](../../com.aspose.drawing/graphicsunit)। |
| gdiCharSet | byte | नए फ़ॉन्ट के लिए उपयोग करने वाला GDI कैरेक्टर सेट। |

### Font(FontFamily family, float emSize, int style, int unit, byte gdiCharSet, boolean gdiVerticalFont) {#Font-com.aspose.drawing.FontFamily-float-int-int-byte-boolean-}
```
public Font(FontFamily family, float emSize, int style, int unit, byte gdiCharSet, boolean gdiVerticalFont)
```


Initializes a new instance of the [Font](../../com.aspose.drawing/font) class using a specified size, style, unit, and character set..

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| family | [FontFamily](../../com.aspose.drawing/fontfamily) | नए [Font](../../com.aspose.drawing/font) का `FontFamily`([.getFontFamily](../../null/\#getFontFamily))। |
| emSize | फ़्लोट | `unit` पैरामीटर द्वारा निर्दिष्ट इकाइयों में नए फ़ॉन्ट का em-size। |
| style | int | नए फ़ॉन्ट का [FontStyle](../../com.aspose.drawing/fontstyle)। |
| unit | int | नए फ़ॉन्ट का [GraphicsUnit](../../com.aspose.drawing/graphicsunit)। |
| gdiCharSet | byte | नए फ़ॉन्ट के लिए उपयोग करने वाला GDI कैरेक्टर सेट। |
| gdiVerticalFont | boolean | यह बूलियन मान दर्शाता है कि नया फ़ॉन्ट GDI वर्टिकल फ़ॉन्ट से व्युत्पन्न है या नहीं। |

### Font(String familyName, float emSize) {#Font-java.lang.String-float-}
```
public Font(String familyName, float emSize)
```


Initializes a new instance of the [Font](../../com.aspose.drawing/font) class using a specified size.

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| familyName | java.lang.String | नए [Font](../../com.aspose.drawing/font) के लिए FontFamily का स्ट्रिंग प्रतिनिधित्व। |
| emSize | फ़्लोट | नए फ़ॉन्ट का em-size, पॉइंट्स में। |

### Font(String familyName, float emSize, int style) {#Font-java.lang.String-float-int-}
```
public Font(String familyName, float emSize, int style)
```


Initializes a new instance of the [Font](../../com.aspose.drawing/font) class using a specified size and style.

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| familyName | java.lang.String | नए [Font](../../com.aspose.drawing/font) के लिए FontFamily का स्ट्रिंग प्रतिनिधित्व। |
| emSize | फ़्लोट | नए फ़ॉन्ट का em-size, पॉइंट्स में। |
| style | int | नए फ़ॉन्ट का [FontStyle](../../com.aspose.drawing/fontstyle)। |

### Font(String familyName, float emSize, int style, int unit) {#Font-java.lang.String-float-int-int-}
```
public Font(String familyName, float emSize, int style, int unit)
```


Initializes a new instance of the [Font](../../com.aspose.drawing/font) class using a specified size, style, and unit.

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| familyName | java.lang.String | नए [Font](../../com.aspose.drawing/font) के लिए `FontFamily`([.getFontFamily](../../null/\#getFontFamily)) का स्ट्रिंग प्रतिनिधित्व। |
| emSize | फ़्लोट | `unit` पैरामीटर द्वारा निर्दिष्ट इकाइयों में नए फ़ॉन्ट का em-size। |
| style | int | नए फ़ॉन्ट का [FontStyle](../../com.aspose.drawing/fontstyle)। |
| unit | int | नए फ़ॉन्ट का [GraphicsUnit](../../com.aspose.drawing/graphicsunit)। |

### Font(String familyName, float emSize, int style, int unit, byte gdiCharSet) {#Font-java.lang.String-float-int-int-byte-}
```
public Font(String familyName, float emSize, int style, int unit, byte gdiCharSet)
```


Initializes a new instance of the [Font](../../com.aspose.drawing/font) class using a specified size, style, unit, and character set.

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| familyName | java.lang.String | नए [Font](../../com.aspose.drawing/font) के लिए FontFamily का स्ट्रिंग प्रतिनिधित्व। |
| emSize | फ़्लोट | `unit` पैरामीटर द्वारा निर्दिष्ट इकाइयों में नए फ़ॉन्ट का em-size। |
| style | int | नए फ़ॉन्ट का [FontStyle](../../com.aspose.drawing/fontstyle)। |
| unit | int | नए फ़ॉन्ट का [GraphicsUnit](../../com.aspose.drawing/graphicsunit)। |
| gdiCharSet | byte | इस फ़ॉन्ट के लिए उपयोग करने वाला GDI कैरेक्टर सेट निर्दिष्ट करने वाला बाइट। |

### Font(String familyName, float emSize, int style, int unit, byte gdiCharSet, boolean gdiVerticalFont) {#Font-java.lang.String-float-int-int-byte-boolean-}
```
public Font(String familyName, float emSize, int style, int unit, byte gdiCharSet, boolean gdiVerticalFont)
```


Initializes a new instance of the [Font](../../com.aspose.drawing/font) class using the specified size, style, unit, and character set.

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| familyName | java.lang.String | नए [Font](../../com.aspose.drawing/font) के लिए FontFamily का स्ट्रिंग प्रतिनिधित्व। |
| emSize | फ़्लोट | `unit` पैरामीटर द्वारा निर्दिष्ट इकाइयों में नए फ़ॉन्ट का em-size। |
| style | int | नए फ़ॉन्ट का [FontStyle](../../com.aspose.drawing/fontstyle)। |
| unit | int | नए फ़ॉन्ट का [GraphicsUnit](../../com.aspose.drawing/graphicsunit)। |
| gdiCharSet | byte | इस फ़ॉन्ट के लिए उपयोग करने वाला GDI कैरेक्टर सेट निर्दिष्ट करने वाला बाइट। |
| gdiVerticalFont | boolean | यह बूलियन मान दर्शाता है कि नया [Font](../../com.aspose.drawing/font) GDI वर्टिकल फ़ॉन्ट से व्युत्पन्न है या नहीं। |

### getFontFamily() {#getFontFamily--}
```
public FontFamily getFontFamily()
```


Gets the `FontFamily`([.getFontFamily](../../null/\#getFontFamily)) associated with this [Font](../../com.aspose.drawing/font).

**Returns:**
[FontFamily](../../com.aspose.drawing/fontfamily) - The `FontFamily`([.getFontFamily](../../null/\#getFontFamily)) associated with this [Font](../../com.aspose.drawing/font).
### getBold() {#getBold--}
```
public boolean getBold()
```


Gets a value indicating whether this [Font](../../com.aspose.drawing/font) is bold.

**Returns:**
boolean - यह मान दर्शाता है कि यह [Font](../../com.aspose.drawing/font) बोल्ड है।
### getGdiCharSet() {#getGdiCharSet--}
```
public byte getGdiCharSet()
```


Gets a byte value that specifies the GDI character set that this [Font](../../com.aspose.drawing/font) uses.

**Returns:**
byte - एक बाइट मान जो उस GDI कैरेक्टर सेट को निर्दिष्ट करता है जिसका यह [Font](../../com.aspose.drawing/font) उपयोग करता है।
### getGdiVerticalFont() {#getGdiVerticalFont--}
```
public boolean getGdiVerticalFont()
```


Gets a value indicating whether this [Font](../../com.aspose.drawing/font) is derived from a GDI vertical font..

मान: यदि यह [Font](../../com.aspose.drawing/font) GDI वर्टिकल फ़ॉन्ट से व्युत्पन्न है तो `true`; अन्यथा `false`।

**Returns:**
boolean - यह मान दर्शाता है कि यह [Font](../../com.aspose.drawing/font) GDI वर्टिकल फ़ॉन्ट से व्युत्पन्न है या नहीं।
### getItalic() {#getItalic--}
```
public boolean getItalic()
```


Gets a value indicating whether this [Font](../../com.aspose.drawing/font) is italic.

**Returns:**
boolean - यह मान दर्शाता है कि यह [Font](../../com.aspose.drawing/font) इटैलिक है या नहीं।
### getName() {#getName--}
```
public String getName()
```


Gets the face name of this [Font](../../com.aspose.drawing/font).

**Returns:**
java.lang.String - इस [Font](../../com.aspose.drawing/font) का फेस नाम।
### getStrikeout() {#getStrikeout--}
```
public boolean getStrikeout()
```


Gets a value indicating whether this [Font](../../com.aspose.drawing/font) specifies a horizontal line through the font.

**Returns:**
boolean - यह मान दर्शाता है कि यह [Font](../../com.aspose.drawing/font) फ़ॉन्ट के ऊपर एक क्षैतिज रेखा निर्दिष्ट करता है या नहीं।
### getUnderline() {#getUnderline--}
```
public boolean getUnderline()
```


Gets a value indicating whether this [Font](../../com.aspose.drawing/font) is underlined.

**Returns:**
boolean - यह मान दर्शाता है कि यह [Font](../../com.aspose.drawing/font) अंडरलाइन है या नहीं।
### getStyle() {#getStyle--}
```
public int getStyle()
```


Gets style information for this [Font](../../com.aspose.drawing/font).

**Returns:**
int - इस [Font](../../com.aspose.drawing/font) के लिए शैली जानकारी।
### getSize() {#getSize--}
```
public float getSize()
```


Gets the em-size of this [Font](../../com.aspose.drawing/font) measured in the units specified by the `Font.Unit` property.

**Returns:**
float - इस [Font](../../com.aspose.drawing/font) का इम-साइज़, जिसे \{@code Font द्वारा निर्दिष्ट इकाइयों में मापा गया है।
### getSizeInPoints() {#getSizeInPoints--}
```
public float getSizeInPoints()
```


Gets the em-size, in points, of this [Font](../../com.aspose.drawing/font).

**Returns:**
float - इस [Font](../../com.aspose.drawing/font) का इम-साइज़, पॉइंट्स में।
### getUnit() {#getUnit--}
```
public int getUnit()
```


Gets the unit of measure for this [Font](../../com.aspose.drawing/font).

**Returns:**
int - इस [Font](../../com.aspose.drawing/font) के लिए माप इकाई।
### getHeight_Rename_Namesake() {#getHeight-Rename-Namesake--}
```
public int getHeight_Rename_Namesake()
```


Gets the line spacing of this font.

मान: इस फ़ॉन्ट की लाइन स्पेसिंग, पिक्सेल में।

**Returns:**
int - इस फ़ॉन्ट की लाइन स्पेसिंग।
### isSystemFont() {#isSystemFont--}
```
public boolean isSystemFont()
```


Gets a value indicating whether the font is a member of [SystemFonts](../../com.aspose.drawing/systemfonts).

मान: यदि फ़ॉन्ट [SystemFonts](../../com.aspose.drawing/systemfonts) का सदस्य है तो `true`; अन्यथा `false`।

**Returns:**
boolean - यह मान दर्शाता है कि फ़ॉन्ट [SystemFonts](../../com.aspose.drawing/systemfonts) का सदस्य है या नहीं।
### getSystemFontName() {#getSystemFontName--}
```
public String getSystemFontName()
```


Gets the name of the system font if the IsSystemFont property returns true.

मान: सिस्टम फ़ॉन्ट का नाम, यदि IsSystemFont true लौटाता है; अन्यथा, एक खाली स्ट्रिंग (\"\").

**Returns:**
java.lang.String - सिस्टम फ़ॉन्ट का नाम यदि IsSystemFont प्रॉपर्टी true लौटाती है।
### getOriginalFontName() {#getOriginalFontName--}
```
public String getOriginalFontName()
```


Gets the name of the font originally specified.

मान: वह स्ट्रिंग जो मूल रूप से निर्दिष्ट फ़ॉन्ट के नाम को दर्शाती है।

**Returns:**
java.lang.String - मूल रूप से निर्दिष्ट फ़ॉन्ट का नाम।
### deepClone() {#deepClone--}
```
public Font deepClone()
```


Creates an exact copy of this [Font](../../com.aspose.drawing/font).

**Returns:**
[Font](../../com.aspose.drawing/font) - The [Font](../../com.aspose.drawing/font) this method creates, cast as an Object.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


निर्दिष्ट वस्तु एक [Font](../../com.aspose.drawing/font) है या नहीं, और क्या इसके `FontFamily`([.getFontFamily](../../null/\#getFontFamily)), `M:GdiVerticalFont`, `M:GdiCharSet`, `M:Style`, `M:Size`, और `M:Unit` प्रॉपर्टी मान इस [Font](../../com.aspose.drawing/font) के समान हैं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | java.lang.Object | परीक्षण करने के लिए ऑब्जेक्ट। |

**Returns:**
boolean - `true` यदि obj पैरामीटर एक [Font](../../com.aspose.drawing/font) है और इस [Font](../../com.aspose.drawing/font) के समान `FontFamily`([.getFontFamily](../../null/\#getFontFamily)), `M:GdiVerticalFont`, `M:GdiCharSet`, `M:Style`, `M:Size`, और `M:Unit` प्रॉपर्टी मान रखता है; अन्यथा, `false`।
### hashCode() {#hashCode--}
```
public int hashCode()
```


इस [Font](../../com.aspose.drawing/font) के लिए हैश कोड प्राप्त करता है।

**Returns:**
int - इस [Font](../../com.aspose.drawing/font) का हैश कोड।
### getHeight() {#getHeight--}
```
public int getHeight()
```


इस फ़ॉन्ट की पंक्ति अंतराल, पिक्सेल में, लौटाता है।

**Returns:**
int - इस फ़ॉन्ट की लाइन स्पेसिंग, पिक्सेल में।
### getHeight(Graphics graphics) {#getHeight-com.aspose.drawing.Graphics-}
```
public float getHeight(Graphics graphics)
```


निर्दिष्ट [Graphics](../../com.aspose.drawing/graphics) की वर्तमान इकाई में इस फ़ॉन्ट की पंक्ति अंतराल लौटाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| graphics | [Graphics](../../com.aspose.drawing/graphics) | एक [Graphics](../../com.aspose.drawing/graphics) जो डिस्प्ले डिवाइस की वर्टिकल रेजोल्यूशन, डॉट्स प्रति इंच में, तथा पेज यूनिट और पेज स्केल की सेटिंग्स रखता है। |

**Returns:**
float - इस फ़ॉन्ट की लाइन स्पेसिंग, पिक्सेल में।
### getHeight(float dpi) {#getHeight-float-}
```
public int getHeight(float dpi)
```


निर्दिष्ट ऊर्ध्वाधर रिज़ॉल्यूशन वाले डिवाइस पर खींचे जाने पर इस [Font](../../com.aspose.drawing/font) की ऊँचाई, पिक्सेल में, लौटाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| dpi | फ़्लोट | फ़ॉन्ट की ऊँचाई की गणना करने के लिए उपयोग किया जाने वाला ऊर्ध्वाधर रिज़ॉल्यूशन, डॉट्स प्रति इंच में। |

**Returns:**
int - इस [Font](../../com.aspose.drawing/font) की ऊँचाई, पिक्सेल में।
### dispose() {#dispose--}
```
public void dispose()
```


इस [Font](../../com.aspose.drawing/font) द्वारा उपयोग किए गए सभी संसाधनों को मुक्त करता है।

### toString() {#toString--}
```
public String toString()
```


इस [Font](../../com.aspose.drawing/font) का मानव-पठनीय स्ट्रिंग प्रतिनिधित्व लौटाता है।

**Returns:**
java.lang.String - एक स्ट्रिंग जो इस [Font](../../com.aspose.drawing/font) को दर्शाती है।
### getCharacterSet() {#getCharacterSet--}
```
public int getCharacterSet()
```


उस बाइट मान को प्राप्त करता है जो यह निर्दिष्ट करता है कि यह `Font` कौन सा कैरेक्टर सेट उपयोग करता है।

**Returns:**
int - एक कैरेक्टर सेट जिसे यह `Font` उपयोग करता है।
