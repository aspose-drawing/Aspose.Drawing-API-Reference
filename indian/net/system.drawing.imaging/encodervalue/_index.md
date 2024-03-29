---
title: Enum EncoderValue
second_title: .NET API संदर्भ के लिए Aspose.Drawing
description: System.Drawing.Imaging.EncoderValue एनुम. क उपयग क उपयग करते समय जेपईज य टआईएफएफ छव एन्कडर क परत पैरमटर मन नर्दष्ट करने के लए कय जत हैEncoderParameters यEncoderParameters तरके.
type: docs
weight: 720
url: /hi/net/system.drawing.imaging/encodervalue/
---
## EncoderValue enumeration

का उपयोग का उपयोग करते समय जेपीईजी या टीआईएफएफ छवि एन्कोडर को पारित पैरामीटर मान निर्दिष्ट करने के लिए किया जाता हैEncoderParameters) याEncoderParameters) तरीके.

```csharp
public enum EncoderValue
```

### मान

| नाम | कीमत | विवरण |
| --- | --- | --- |
| ColorTypeCMYK | `0` | GDI+ संस्करण 1.0 में उपयोग नहीं किया गया। |
| ColorTypeYCCK | `1` | GDI+ संस्करण 1.0 में उपयोग नहीं किया गया। |
| CompressionLZW | `2` | LZW संपीड़न योजना निर्दिष्ट करता है। टीआईएफएफ एन्कोडर को संपीड़न श्रेणी से संबंधित पैरामीटर के रूप में पारित किया जा सकता है। |
| CompressionCCITT3 | `3` | CCITT3 संपीड़न योजना निर्दिष्ट करता है। टीआईएफएफ एन्कोडर को संपीड़न श्रेणी से संबंधित पैरामीटर के रूप में पारित किया जा सकता है। |
| CompressionCCITT4 | `4` | CCITT4 संपीड़न योजना निर्दिष्ट करता है। टीआईएफएफ एन्कोडर को संपीड़न श्रेणी से संबंधित पैरामीटर के रूप में पारित किया जा सकता है। |
| CompressionRle | `5` | आरएलई संपीड़न योजना निर्दिष्ट करता है। टीआईएफएफ एन्कोडर को संपीड़न श्रेणी से संबंधित पैरामीटर के रूप में पारित किया जा सकता है। |
| CompressionNone | `6` | कोई संपीड़न निर्दिष्ट नहीं करता है। टीआईएफएफ एन्कोडर को संपीड़न श्रेणी से संबंधित पैरामीटर के रूप में पारित किया जा सकता है। |
| ScanMethodInterlaced | `7` | GDI+ संस्करण 1.0 में उपयोग नहीं किया गया। |
| ScanMethodNonInterlaced | `8` | GDI+ संस्करण 1.0 में उपयोग नहीं किया गया। |
| VersionGif87 | `9` | GDI+ संस्करण 1.0 में उपयोग नहीं किया गया। |
| VersionGif89 | `10` | GDI+ संस्करण 1.0 में उपयोग नहीं किया गया। |
| RenderProgressive | `11` | GDI+ संस्करण 1.0 में उपयोग नहीं किया गया। |
| RenderNonProgressive | `12` | GDI+ संस्करण 1.0 में उपयोग नहीं किया गया। |
| TransformRotate90 | `13` | निर्दिष्ट करता है कि छवि को उसके केंद्र के बारे में दक्षिणावर्त 90 डिग्री घुमाया जाना है। जेपीईजी एनकोडर को एक पैरामीटर के रूप में पारित किया जा सकता है जो परिवर्तन श्रेणी से संबंधित है। |
| TransformRotate180 | `14` | निर्दिष्ट करता है कि छवि को उसके केंद्र के बारे में 180 डिग्री घुमाया जाना है। जेपीईजी एनकोडर को एक पैरामीटर के रूप में पारित किया जा सकता है जो परिवर्तन श्रेणी से संबंधित है। |
| TransformRotate270 | `15` | निर्दिष्ट करता है कि छवि को उसके केंद्र के बारे में दक्षिणावर्त 270 डिग्री घुमाया जाना है। जेपीईजी एनकोडर को एक पैरामीटर के रूप में पारित किया जा सकता है जो परिवर्तन श्रेणी से संबंधित है। |
| TransformFlipHorizontal | `16` | निर्दिष्ट करता है कि छवि को क्षैतिज रूप से फ़्लिप किया जाना है (ऊर्ध्वाधर अक्ष के बारे में)। जेपीईजी एनकोडर को एक पैरामीटर के रूप में पारित किया जा सकता है जो परिवर्तन श्रेणी से संबंधित है। |
| TransformFlipVertical | `17` | निर्दिष्ट करता है कि छवि को लंबवत फ़्लिप किया जाना है (क्षैतिज अक्ष के बारे में)। जेपीईजी एनकोडर को एक पैरामीटर के रूप में पारित किया जा सकता है जो परिवर्तन श्रेणी से संबंधित है। |
| MultiFrame | `18` | निर्दिष्ट करता है कि छवि में एक से अधिक फ़्रेम (पृष्ठ) हैं। TIFF एनकोडर को एक पैरामीटर के रूप में पास किया जा सकता है जो सेव फ़्लैग श्रेणी से संबंधित है। |
| LastFrame | `19` | एक बहु-फ़्रेम छवि में अंतिम फ़्रेम निर्दिष्ट करता है। TIFF एनकोडर को एक पैरामीटर के रूप में पास किया जा सकता है जो सेव फ़्लैग श्रेणी से संबंधित है। |
| Flush | `20` | निर्दिष्ट करता है कि एक बहु-फ़्रेम फ़ाइल या स्ट्रीम को बंद किया जाना चाहिए। TIFF एनकोडर को एक पैरामीटर के रूप में पास किया जा सकता है जो सेव फ़्लैग श्रेणी से संबंधित है। |
| FrameDimensionTime | `21` | GDI+ संस्करण 1.0 में उपयोग नहीं किया गया। |
| FrameDimensionResolution | `22` | GDI+ संस्करण 1.0 में उपयोग नहीं किया गया। |
| FrameDimensionPage | `23` | निर्दिष्ट करता है कि एक छवि के पृष्ठ आयाम में एक फ्रेम जोड़ा जाना है। TIFF एनकोडर को एक पैरामीटर के रूप में पास किया जा सकता है जो सेव फ़्लैग श्रेणी से संबंधित है। |

### यह सभी देखें

* नाम स्थान [System.Drawing.Imaging](../../system.drawing.imaging/)
* सभा [Aspose.Drawing](../../)


