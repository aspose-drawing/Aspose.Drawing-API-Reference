---
title: ImageCodecInfo
second_title: Aspose.Drawing för Java API‑referens
description: Klassen tillhandahåller de nödvändiga lagringsmedlemmarna och metoderna för att hämta all relevant information om de installerade bildkodarna och avkodarna som kallas codecs.
type: docs
weight: 25
url: /sv/java/com.aspose.drawing.imaging/imagecodecinfo/
---
**Inheritance:**
java.lang.Object
```
public final class ImageCodecInfo
```

Klassen [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo) tillhandahåller de nödvändiga lagringsmedlemmarna och metoderna för att hämta all relevant information om de installerade bildkodarna och avkodarna (kallade codecs). Kan inte ärvas.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [ImageCodecInfo()](#ImageCodecInfo--) | Initierar en ny instans av klassen [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo). |
| [ImageCodecInfo(UUID clsid, String codecName, String filenameExtension, String formatDescription, UUID formatID, String mimeType, int version)](#ImageCodecInfo-java.util.UUID-java.lang.String-java.lang.String-java.lang.String-java.util.UUID-java.lang.String-int-) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getClsid()](#getClsid--) | Hämtar en java.util.UUID-struktur som innehåller en GUID som identifierar en specifik codec. |
| [setClsid(UUID value)](#setClsid-java.util.UUID-) | Ställer in en java.util.UUID-struktur som innehåller en GUID som identifierar en specifik codec. |
| [getFormatID()](#getFormatID--) | Hämtar en java.util.UUID-struktur som innehåller en GUID som identifierar codecens format. |
| [setFormatID(UUID value)](#setFormatID-java.util.UUID-) | Ställer in en java.util.UUID-struktur som innehåller en GUID som identifierar codecens format. |
| [getCodecName()](#getCodecName--) | Hämtar eller anger en sträng som innehåller codecens namn. |
| [setCodecName(String value)](#setCodecName-java.lang.String-) | Hämtar eller anger en sträng som innehåller codecens namn. |
| [getFormatDescription()](#getFormatDescription--) | Hämtar eller anger en sträng som beskriver codecens filformat. |
| [setFormatDescription(String value)](#setFormatDescription-java.lang.String-) | Hämtar eller anger en sträng som beskriver codecens filformat. |
| [getFilenameExtension()](#getFilenameExtension--) | Hämtar eller anger en sträng som innehåller filnamnstillägget/tilläggen som används i codec. |
| [setFilenameExtension(String value)](#setFilenameExtension-java.lang.String-) | Hämtar eller anger en sträng som innehåller filnamnstillägget/tilläggen som används i codec. |
| [getMimeType()](#getMimeType--) | Hämtar eller anger en sträng som innehåller codecens Multipurpose Internet Mail Extensions (MIME)-typ. |
| [setMimeType(String value)](#setMimeType-java.lang.String-) | Hämtar eller anger en sträng som innehåller codecens Multipurpose Internet Mail Extensions (MIME)-typ. |
| [getVersion()](#getVersion--) | Hämtar eller anger versionsnumret för codec. |
| [setVersion(int value)](#setVersion-int-) | Hämtar eller anger versionsnumret för codec. |
| [getSignaturePatterns()](#getSignaturePatterns--) | Hämtar eller anger en tvådimensionell byte-array som representerar codecens signatur. |
| [setSignaturePatterns(byte[][] value)](#setSignaturePatterns-byte-----) | Hämtar eller anger en tvådimensionell byte-array som representerar codecens signatur. |
| [getSignatureMasks()](#getSignatureMasks--) | Hämtar eller anger en tvådimensionell byte-array som kan användas som filter. |
| [setSignatureMasks(byte[][] value)](#setSignatureMasks-byte-----) | Hämtar eller anger en tvådimensionell byte-array som kan användas som filter. |
| [getImageDecoders()](#getImageDecoders--) | Returnerar en array av [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo)-objekt som innehåller information om bildavkodarna som är inbyggda i GDI+. |
| [getImageEncoders()](#getImageEncoders--) | Returnerar en array av [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo)-objekt som innehåller information om bildkodarna som är inbyggda i GDI+. |
### ImageCodecInfo() {#ImageCodecInfo--}
```
public ImageCodecInfo()
```


Initierar en ny instans av klassen [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo).

### ImageCodecInfo(UUID clsid, String codecName, String filenameExtension, String formatDescription, UUID formatID, String mimeType, int version) {#ImageCodecInfo-java.util.UUID-java.lang.String-java.lang.String-java.lang.String-java.util.UUID-java.lang.String-int-}
```
public ImageCodecInfo(UUID clsid, String codecName, String filenameExtension, String formatDescription, UUID formatID, String mimeType, int version)
```


**Parameters:**
| Parameter | Typ | Beskrivning |
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


Hämtar en java.util.UUID-struktur som innehåller en GUID som identifierar en specifik codec.

**Returns:**
java.util.UUID - en java.util.UUID
### setClsid(UUID value) {#setClsid-java.util.UUID-}
```
public void setClsid(UUID value)
```


Ställer in en java.util.UUID-struktur som innehåller en GUID som identifierar en specifik codec.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.util.UUID | en java.util.UUID |

### getFormatID() {#getFormatID--}
```
public UUID getFormatID()
```


Hämtar en java.util.UUID-struktur som innehåller en GUID som identifierar codecens format.

**Returns:**
java.util.UUID - en java.util.UUID
### setFormatID(UUID value) {#setFormatID-java.util.UUID-}
```
public void setFormatID(UUID value)
```


Ställer in en java.util.UUID-struktur som innehåller en GUID som identifierar codecens format.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.util.UUID | en java.util.UUID |

### getCodecName() {#getCodecName--}
```
public String getCodecName()
```


Hämtar eller anger en sträng som innehåller codecens namn.

**Returns:**
java.lang.String
### setCodecName(String value) {#setCodecName-java.lang.String-}
```
public void setCodecName(String value)
```


Hämtar eller anger en sträng som innehåller codecens namn.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |

### getFormatDescription() {#getFormatDescription--}
```
public String getFormatDescription()
```


Hämtar eller anger en sträng som beskriver codecens filformat.

**Returns:**
java.lang.String
### setFormatDescription(String value) {#setFormatDescription-java.lang.String-}
```
public void setFormatDescription(String value)
```


Hämtar eller anger en sträng som beskriver codecens filformat.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |

### getFilenameExtension() {#getFilenameExtension--}
```
public String getFilenameExtension()
```


Hämtar eller anger en sträng som innehåller filnamnstillägget eller tilläggen som används i kodeken. Tilläggen är separerade med semikolon.

**Returns:**
java.lang.String
### setFilenameExtension(String value) {#setFilenameExtension-java.lang.String-}
```
public void setFilenameExtension(String value)
```


Hämtar eller anger en sträng som innehåller filnamnstillägget eller tilläggen som används i kodeken. Tilläggen är separerade med semikolon.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |

### getMimeType() {#getMimeType--}
```
public String getMimeType()
```


Hämtar eller anger en sträng som innehåller codecens Multipurpose Internet Mail Extensions (MIME)-typ.

**Returns:**
java.lang.String
### setMimeType(String value) {#setMimeType-java.lang.String-}
```
public void setMimeType(String value)
```


Hämtar eller anger en sträng som innehåller codecens Multipurpose Internet Mail Extensions (MIME)-typ.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |

### getVersion() {#getVersion--}
```
public int getVersion()
```


Hämtar eller anger versionsnumret för codec.

**Returns:**
int
### setVersion(int value) {#setVersion-int-}
```
public void setVersion(int value)
```


Hämtar eller anger versionsnumret för codec.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getSignaturePatterns() {#getSignaturePatterns--}
```
public byte[][] getSignaturePatterns()
```


Hämtar eller anger en tvådimensionell byte-array som representerar codecens signatur.

**Returns:**
byte[][]
### setSignaturePatterns(byte[][] value) {#setSignaturePatterns-byte-----}
```
public void setSignaturePatterns(byte[][] value)
```


Hämtar eller anger en tvådimensionell byte-array som representerar codecens signatur.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte[][] |  |

### getSignatureMasks() {#getSignatureMasks--}
```
public byte[][] getSignatureMasks()
```


Hämtar eller anger en tvådimensionell byte-array som kan användas som filter.

**Returns:**
byte[][]
### setSignatureMasks(byte[][] value) {#setSignatureMasks-byte-----}
```
public void setSignatureMasks(byte[][] value)
```


Hämtar eller anger en tvådimensionell byte-array som kan användas som filter.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte[][] |  |

### getImageDecoders() {#getImageDecoders--}
```
public static ImageCodecInfo[] getImageDecoders()
```


Returnerar en array av [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo)-objekt som innehåller information om bildavkodarna som är inbyggda i GDI+.

**Returns:**
com.aspose.drawing.imaging.ImageCodecInfo[] - En array av [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo)-objekt. Varje [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo)-objekt i arrayen innehåller information om en av de inbyggda bildavkodarna.
### getImageEncoders() {#getImageEncoders--}
```
public static ImageCodecInfo[] getImageEncoders()
```


Returnerar en array av [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo)-objekt som innehåller information om bildkodarna som är inbyggda i GDI+.

**Returns:**
com.aspose.drawing.imaging.ImageCodecInfo[] - En array av [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo)-objekt. Varje [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo)-objekt i arrayen innehåller information om en av de inbyggda bildkodarna.
