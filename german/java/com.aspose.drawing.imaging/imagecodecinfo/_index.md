---
title: ImageCodecInfo
second_title: Aspose.Drawing für Java API-Referenz
description: Die Klasse stellt die notwendigen Speicher‑mitglieder und Methoden bereit, um alle relevanten Informationen über die installierten Bild‑Encoder und -Decoder, sogenannte Codecs, abzurufen.
type: docs
weight: 25
url: /de/java/com.aspose.drawing.imaging/imagecodecinfo/
---
**Inheritance:**
java.lang.Object
```
public final class ImageCodecInfo
```

Die [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo)-Klasse stellt die erforderlichen Speicher­mitglieder und Methoden bereit, um alle relevanten Informationen über die installierten Bild‑Encoder und -Decoder (sogenannte Codecs) abzurufen. Nicht vererbbar.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [ImageCodecInfo()](#ImageCodecInfo--) | Initialisiert eine neue Instanz der [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo)-Klasse. |
| [ImageCodecInfo(UUID clsid, String codecName, String filenameExtension, String formatDescription, UUID formatID, String mimeType, int version)](#ImageCodecInfo-java.util.UUID-java.lang.String-java.lang.String-java.lang.String-java.util.UUID-java.lang.String-int-) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getClsid()](#getClsid--) | Liefert eine java.util.UUID‑Struktur, die eine GUID enthält, die einen bestimmten Codec identifiziert. |
| [setClsid(UUID value)](#setClsid-java.util.UUID-) | Setzt eine java.util.UUID‑Struktur, die eine GUID enthält, die einen bestimmten Codec identifiziert. |
| [getFormatID()](#getFormatID--) | Liefert eine java.util.UUID‑Struktur, die eine GUID enthält, die das Format des Codecs identifiziert. |
| [setFormatID(UUID value)](#setFormatID-java.util.UUID-) | Setzt eine java.util.UUID‑Struktur, die eine GUID enthält, die das Format des Codecs identifiziert. |
| [getCodecName()](#getCodecName--) | Liefert oder setzt eine Zeichenkette, die den Namen des Codecs enthält. |
| [setCodecName(String value)](#setCodecName-java.lang.String-) | Liefert oder setzt eine Zeichenkette, die den Namen des Codecs enthält. |
| [getFormatDescription()](#getFormatDescription--) | Liefert oder setzt eine Zeichenkette, die das Dateiformat des Codecs beschreibt. |
| [setFormatDescription(String value)](#setFormatDescription-java.lang.String-) | Liefert oder setzt eine Zeichenkette, die das Dateiformat des Codecs beschreibt. |
| [getFilenameExtension()](#getFilenameExtension--) | Liefert oder setzt eine Zeichenkette, die die Dateierweiterung(en) enthält, die im Codec verwendet werden. |
| [setFilenameExtension(String value)](#setFilenameExtension-java.lang.String-) | Liefert oder setzt eine Zeichenkette, die die Dateierweiterung(en) enthält, die im Codec verwendet werden. |
| [getMimeType()](#getMimeType--) | Liefert oder setzt eine Zeichenkette, die den Multipurpose Internet Mail Extensions (MIME)-Typ des Codecs enthält. |
| [setMimeType(String value)](#setMimeType-java.lang.String-) | Liefert oder setzt eine Zeichenkette, die den Multipurpose Internet Mail Extensions (MIME)-Typ des Codecs enthält. |
| [getVersion()](#getVersion--) | Liefert oder setzt die Versionsnummer des Codecs. |
| [setVersion(int value)](#setVersion-int-) | Liefert oder setzt die Versionsnummer des Codecs. |
| [getSignaturePatterns()](#getSignaturePatterns--) | Liefert oder setzt ein zweidimensionales Byte‑Array, das die Signatur des Codecs darstellt. |
| [setSignaturePatterns(byte[][] value)](#setSignaturePatterns-byte-----) | Liefert oder setzt ein zweidimensionales Byte‑Array, das die Signatur des Codecs darstellt. |
| [getSignatureMasks()](#getSignatureMasks--) | Liefert oder setzt ein zweidimensionales Byte‑Array, das als Filter verwendet werden kann. |
| [setSignatureMasks(byte[][] value)](#setSignatureMasks-byte-----) | Liefert oder setzt ein zweidimensionales Byte‑Array, das als Filter verwendet werden kann. |
| [getImageDecoders()](#getImageDecoders--) | Gibt ein Array von [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo)-Objekten zurück, das Informationen über die in GDI+ integrierten Bild‑Decoder enthält. |
| [getImageEncoders()](#getImageEncoders--) | Gibt ein Array von [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo)-Objekten zurück, das Informationen über die in GDI+ integrierten Bild‑Encoder enthält. |
### ImageCodecInfo() {#ImageCodecInfo--}
```
public ImageCodecInfo()
```


Initialisiert eine neue Instanz der [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo)-Klasse.

### ImageCodecInfo(UUID clsid, String codecName, String filenameExtension, String formatDescription, UUID formatID, String mimeType, int version) {#ImageCodecInfo-java.util.UUID-java.lang.String-java.lang.String-java.lang.String-java.util.UUID-java.lang.String-int-}
```
public ImageCodecInfo(UUID clsid, String codecName, String filenameExtension, String formatDescription, UUID formatID, String mimeType, int version)
```


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| clsid | java.util.UUID |  |
| codecName | java.lang.String |  |
| filenameExtension | java.lang.String |  |
| formatDescription | java.lang.String |  |
| formatID | java.util.UUID |  |
| mimeType | java.lang.String |  |
| version | int |  |

### getClsid() {#getClsid--}
```
public UUID getClsid()
```


Liefert eine java.util.UUID‑Struktur, die eine GUID enthält, die einen bestimmten Codec identifiziert.

**Returns:**
java.util.UUID - ein java.util.UUID
### setClsid(UUID value) {#setClsid-java.util.UUID-}
```
public void setClsid(UUID value)
```


Setzt eine java.util.UUID‑Struktur, die eine GUID enthält, die einen bestimmten Codec identifiziert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.util.UUID | ein java.util.UUID |

### getFormatID() {#getFormatID--}
```
public UUID getFormatID()
```


Liefert eine java.util.UUID‑Struktur, die eine GUID enthält, die das Format des Codecs identifiziert.

**Returns:**
java.util.UUID - ein java.util.UUID
### setFormatID(UUID value) {#setFormatID-java.util.UUID-}
```
public void setFormatID(UUID value)
```


Setzt eine java.util.UUID‑Struktur, die eine GUID enthält, die das Format des Codecs identifiziert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.util.UUID | ein java.util.UUID |

### getCodecName() {#getCodecName--}
```
public String getCodecName()
```


Liefert oder setzt eine Zeichenkette, die den Namen des Codecs enthält.

**Returns:**
java.lang.String
### setCodecName(String value) {#setCodecName-java.lang.String-}
```
public void setCodecName(String value)
```


Liefert oder setzt eine Zeichenkette, die den Namen des Codecs enthält.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |

### getFormatDescription() {#getFormatDescription--}
```
public String getFormatDescription()
```


Liefert oder setzt eine Zeichenkette, die das Dateiformat des Codecs beschreibt.

**Returns:**
java.lang.String
### setFormatDescription(String value) {#setFormatDescription-java.lang.String-}
```
public void setFormatDescription(String value)
```


Liefert oder setzt eine Zeichenkette, die das Dateiformat des Codecs beschreibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |

### getFilenameExtension() {#getFilenameExtension--}
```
public String getFilenameExtension()
```


Liest oder setzt die Zeichenkette, die die Dateinamenerweiterung(en) enthält, die im Codec verwendet werden. Die Erweiterungen sind durch Semikolons getrennt.

**Returns:**
java.lang.String
### setFilenameExtension(String value) {#setFilenameExtension-java.lang.String-}
```
public void setFilenameExtension(String value)
```


Liest oder setzt die Zeichenkette, die die Dateinamenerweiterung(en) enthält, die im Codec verwendet werden. Die Erweiterungen sind durch Semikolons getrennt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |

### getMimeType() {#getMimeType--}
```
public String getMimeType()
```


Liefert oder setzt eine Zeichenkette, die den Multipurpose Internet Mail Extensions (MIME)-Typ des Codecs enthält.

**Returns:**
java.lang.String
### setMimeType(String value) {#setMimeType-java.lang.String-}
```
public void setMimeType(String value)
```


Liefert oder setzt eine Zeichenkette, die den Multipurpose Internet Mail Extensions (MIME)-Typ des Codecs enthält.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |

### getVersion() {#getVersion--}
```
public int getVersion()
```


Liefert oder setzt die Versionsnummer des Codecs.

**Returns:**
int
### setVersion(int value) {#setVersion-int-}
```
public void setVersion(int value)
```


Liefert oder setzt die Versionsnummer des Codecs.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getSignaturePatterns() {#getSignaturePatterns--}
```
public byte[][] getSignaturePatterns()
```


Liefert oder setzt ein zweidimensionales Byte‑Array, das die Signatur des Codecs darstellt.

**Returns:**
byte[][]
### setSignaturePatterns(byte[][] value) {#setSignaturePatterns-byte-----}
```
public void setSignaturePatterns(byte[][] value)
```


Liefert oder setzt ein zweidimensionales Byte‑Array, das die Signatur des Codecs darstellt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte[][] |  |

### getSignatureMasks() {#getSignatureMasks--}
```
public byte[][] getSignatureMasks()
```


Liefert oder setzt ein zweidimensionales Byte‑Array, das als Filter verwendet werden kann.

**Returns:**
byte[][]
### setSignatureMasks(byte[][] value) {#setSignatureMasks-byte-----}
```
public void setSignatureMasks(byte[][] value)
```


Liefert oder setzt ein zweidimensionales Byte‑Array, das als Filter verwendet werden kann.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte[][] |  |

### getImageDecoders() {#getImageDecoders--}
```
public static ImageCodecInfo[] getImageDecoders()
```


Gibt ein Array von [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo)-Objekten zurück, das Informationen über die in GDI+ integrierten Bild‑Decoder enthält.

**Returns:**
com.aspose.drawing.imaging.ImageCodecInfo[] - Ein Array von [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo)-Objekten. Jedes [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo)-Objekt im Array enthält Informationen über einen der integrierten Bilddecoder.
### getImageEncoders() {#getImageEncoders--}
```
public static ImageCodecInfo[] getImageEncoders()
```


Gibt ein Array von [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo)-Objekten zurück, das Informationen über die in GDI+ integrierten Bild‑Encoder enthält.

**Returns:**
com.aspose.drawing.imaging.ImageCodecInfo[] - Ein Array von [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo)-Objekten. Jedes [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo)-Objekt im Array enthält Informationen über einen der integrierten Bildencoder.
