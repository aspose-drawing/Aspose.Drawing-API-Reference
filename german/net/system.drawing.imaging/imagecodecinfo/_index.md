---
title: ImageCodecInfo
second_title: Aspose.Drawing für .NET-API-Referenz
description: DieImageCodecInfo Die Klasse stellt die notwendigen Speicherelemente und Methoden bereit um alle relevanten Informationen über die installierten Bildcodierer und decodierer als Codecs bezeichnet abzurufen . Nicht vererbbar.
type: docs
weight: 750
url: /de/net/system.drawing.imaging/imagecodecinfo/
---
## ImageCodecInfo class

DieImageCodecInfo Die Klasse stellt die notwendigen Speicherelemente und Methoden bereit, um alle relevanten Informationen über die installierten Bildcodierer und -decodierer (als Codecs bezeichnet) abzurufen . Nicht vererbbar.

```csharp
public sealed class ImageCodecInfo
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Clsid](../../system.drawing.imaging/imagecodecinfo/clsid) { get; set; } | Holt oder setzt aGuid Struktur, die eine GUID enthält, die einen bestimmten Codec identifiziert. |
| [CodecName](../../system.drawing.imaging/imagecodecinfo/codecname) { get; set; } | Ruft eine Zeichenfolge ab oder legt sie fest, die den Namen des Codecs enthält. |
| [FilenameExtension](../../system.drawing.imaging/imagecodecinfo/filenameextension) { get; set; } | Ruft eine Zeichenfolge ab oder legt sie fest, die die Dateinamenerweiterung(en) enthält, die im Codec verwendet werden. Die Erweiterungen werden durch Semikolons getrennt. |
| [FormatDescription](../../system.drawing.imaging/imagecodecinfo/formatdescription) { get; set; } | Ruft eine Zeichenfolge ab oder legt sie fest, die das Dateiformat des Codecs beschreibt. |
| [FormatID](../../system.drawing.imaging/imagecodecinfo/formatid) { get; set; } | Holt oder setzt aGuid Struktur, die eine GUID enthält, die das Format des Codecs identifiziert. |
| [MimeType](../../system.drawing.imaging/imagecodecinfo/mimetype) { get; set; } | Ruft eine Zeichenfolge ab oder legt eine Zeichenfolge fest, die den MIME-Typ (Multipurpose Internet Mail Extensions) des Codecs enthält. |
| [SignatureMasks](../../system.drawing.imaging/imagecodecinfo/signaturemasks) { get; set; } | Ruft ein zweidimensionales Byte-Array ab oder legt es fest, das als Filter verwendet werden kann. |
| [SignaturePatterns](../../system.drawing.imaging/imagecodecinfo/signaturepatterns) { get; set; } | Ruft ein zweidimensionales Array von Bytes ab oder legt es fest, das die Signatur des Codecs darstellt. |
| [Version](../../system.drawing.imaging/imagecodecinfo/version) { get; set; } | Ruft die Versionsnummer des Codecs ab oder setzt sie. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [GetImageDecoders](../../system.drawing.imaging/imagecodecinfo/getimagedecoders)() | Gibt ein Array von zurückImageCodecInfo Objekte, die Informationen über die in GDI+ integrierten Bilddecoder enthalten. |
| static [GetImageEncoders](../../system.drawing.imaging/imagecodecinfo/getimageencoders)() | Gibt ein Array von zurückImageCodecInfoObjekte, die Informationen über die in GDI+ integrierten Bildcodierer enthalten. |

### Siehe auch

* namensraum [System.Drawing.Imaging](../../system.drawing.imaging)
* Montage [Aspose.Drawing](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Drawing.dll -->
