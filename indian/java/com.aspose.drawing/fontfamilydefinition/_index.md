---
title: FontFamilyDefinition
second_title: Aspose.Drawing for Java API संदर्भ
description: फ़ॉन्ट फ़ैमिली की परिभाषा।
type: docs
weight: 25
url: /hi/java/com.aspose.drawing/fontfamilydefinition/
---
**Inheritance:**
java.lang.Object
```
public class FontFamilyDefinition
```

फ़ॉन्ट फ़ैमिली की परिभाषा।
## निर्माता

| निर्माता | विवरण |
| --- | --- |
| [FontFamilyDefinition()](#FontFamilyDefinition--) | एक नया उदाहरण प्रारंभ करता है [FontFamilyDefinition](../../com.aspose.drawing/fontfamilydefinition) क्लास का। |
## मेथड्स

| विधि | विवरण |
| --- | --- |
| [addFontDefinition(int style, FontDefinitionExt fontDef)](#addFontDefinition-int-com.aspose.drawing.FontDefinitionExt-) | फ़ॉन्ट परिभाषा को फ़ॉन्ट परिवार में जोड़ता है। |
| [getFontDefinition(int style)](#getFontDefinition-int-) | विशिष्ट शैली के लिए परिवार से फ़ॉन्ट परिभाषा प्राप्त करता है। |
| [matchesLocalizedFamilyName(String localizedFamilyName)](#matchesLocalizedFamilyName-java.lang.String-) | इस परिवार में स्थानीयकृत परिवार नामों से मेल खाता है। |
| [getFamilyName()](#getFamilyName--) | इस परिवार का एक परिवार नाम प्राप्त करता है। |
### FontFamilyDefinition() {#FontFamilyDefinition--}
```
public FontFamilyDefinition()
```


एक नया उदाहरण प्रारंभ करता है [FontFamilyDefinition](../../com.aspose.drawing/fontfamilydefinition) क्लास का।

### addFontDefinition(int style, FontDefinitionExt fontDef) {#addFontDefinition-int-com.aspose.drawing.FontDefinitionExt-}
```
public final void addFontDefinition(int style, FontDefinitionExt fontDef)
```


फ़ॉन्ट परिभाषा को फ़ॉन्ट परिवार में जोड़ता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| style | int | शैली। |
| fontDef | [FontDefinitionExt](../../com.aspose.drawing/fontdefinitionext) | फ़ॉन्ट परिभाषा। |

### getFontDefinition(int style) {#getFontDefinition-int-}
```
public final FontDefinitionExt getFontDefinition(int style)
```


विशिष्ट शैली के लिए परिवार से फ़ॉन्ट परिभाषा प्राप्त करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| style | int | शैली। |

**Returns:**
[FontDefinitionExt](../../com.aspose.drawing/fontdefinitionext) - Returns font definition if exist for specified style, null otherwise.
### matchesLocalizedFamilyName(String localizedFamilyName) {#matchesLocalizedFamilyName-java.lang.String-}
```
public final boolean matchesLocalizedFamilyName(String localizedFamilyName)
```


इस परिवार में स्थानीयकृत परिवार नामों से मेल खाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| localizedFamilyName | java.lang.String | स्थानीयकृत परिवार नाम। |

**Returns:**
boolean - true यदि यह परिवार स्थानीयकृत परिवार नाम शामिल करता है।
### getFamilyName() {#getFamilyName--}
```
public final String getFamilyName()
```


इस परिवार का एक परिवार नाम प्राप्त करता है।

**Returns:**
java.lang.String - परिवार नाम, या खाली परिवार के लिए null।
