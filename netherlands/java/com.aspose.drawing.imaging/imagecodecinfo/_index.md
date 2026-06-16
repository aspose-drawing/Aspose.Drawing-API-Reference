---
title: ImageCodecInfo
second_title: Aspose.Drawing voor Java API-referentie
description: De klasse biedt de benodigde opslagleden en methoden om alle relevante informatie over de geïnstalleerde beeldcoders en -decoders, codecs genoemd, op te halen.
type: docs
weight: 25
url: /nl/java/com.aspose.drawing.imaging/imagecodecinfo/
---
**Inheritance:**
java.lang.Object
```
public final class ImageCodecInfo
```

De [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo) klasse biedt de benodigde opslagleden en methoden om alle relevante informatie over de geïnstalleerde afbeeldingencoders en -decoders (genaamd codecs) op te halen. Niet erfbaar.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [ImageCodecInfo()](#ImageCodecInfo--) | Initialiseert een nieuw exemplaar van de [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo) klasse. |
| [ImageCodecInfo(UUID clsid, String codecName, String filenameExtension, String formatDescription, UUID formatID, String mimeType, int version)](#ImageCodecInfo-java.util.UUID-java.lang.String-java.lang.String-java.lang.String-java.util.UUID-java.lang.String-int-) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getClsid()](#getClsid--) | Haalt een java.util.UUID-structuur op die een GUID bevat die een specifiek codec identificeert. |
| [setClsid(UUID value)](#setClsid-java.util.UUID-) | Stelt een java.util.UUID-structuur in die een GUID bevat die een specifiek codec identificeert. |
| [getFormatID()](#getFormatID--) | Haalt een java.util.UUID-structuur op die een GUID bevat die het formaat van het codec identificeert. |
| [setFormatID(UUID value)](#setFormatID-java.util.UUID-) | Stelt een java.util.UUID-structuur in die een GUID bevat die het formaat van het codec identificeert. |
| [getCodecName()](#getCodecName--) | Haalt op of stelt een tekenreeks in die de naam van het codec bevat. |
| [setCodecName(String value)](#setCodecName-java.lang.String-) | Haalt op of stelt een tekenreeks in die de naam van het codec bevat. |
| [getFormatDescription()](#getFormatDescription--) | Haalt op of stelt een tekenreeks in die het bestandsformaat van het codec beschrijft. |
| [setFormatDescription(String value)](#setFormatDescription-java.lang.String-) | Haalt op of stelt een tekenreeks in die het bestandsformaat van het codec beschrijft. |
| [getFilenameExtension()](#getFilenameExtension--) | Haalt op of stelt een tekenreeks in die de bestandsextensie(s) bevat die in het codec worden gebruikt. |
| [setFilenameExtension(String value)](#setFilenameExtension-java.lang.String-) | Haalt op of stelt een tekenreeks in die de bestandsextensie(s) bevat die in het codec worden gebruikt. |
| [getMimeType()](#getMimeType--) | Haalt op of stelt een tekenreeks in die het Multipurpose Internet Mail Extensions (MIME)-type van het codec bevat. |
| [setMimeType(String value)](#setMimeType-java.lang.String-) | Haalt op of stelt een tekenreeks in die het Multipurpose Internet Mail Extensions (MIME)-type van het codec bevat. |
| [getVersion()](#getVersion--) | Haalt op of stelt het versienummer van het codec in. |
| [setVersion(int value)](#setVersion-int-) | Haalt op of stelt het versienummer van het codec in. |
| [getSignaturePatterns()](#getSignaturePatterns--) | Haalt op of stelt een tweedimensionale array van bytes in die de handtekening van het codec weergeeft. |
| [setSignaturePatterns(byte[][] value)](#setSignaturePatterns-byte-----) | Haalt op of stelt een tweedimensionale array van bytes in die de handtekening van het codec weergeeft. |
| [getSignatureMasks()](#getSignatureMasks--) | Haalt op of stelt een tweedimensionale array van bytes in die als filter kan worden gebruikt. |
| [setSignatureMasks(byte[][] value)](#setSignatureMasks-byte-----) | Haalt op of stelt een tweedimensionale array van bytes in die als filter kan worden gebruikt. |
| [getImageDecoders()](#getImageDecoders--) | Retourneert een array van [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo)-objecten die informatie bevatten over de in GDI+ ingebouwde afbeeldingdecoders. |
| [getImageEncoders()](#getImageEncoders--) | Retourneert een array van [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo)-objecten die informatie bevatten over de in GDI+ ingebouwde afbeeldingencoders. |
### ImageCodecInfo() {#ImageCodecInfo--}
```
public ImageCodecInfo()
```


Initialiseert een nieuw exemplaar van de [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo) klasse.

### ImageCodecInfo(UUID clsid, String codecName, String filenameExtension, String formatDescription, UUID formatID, String mimeType, int version) {#ImageCodecInfo-java.util.UUID-java.lang.String-java.lang.String-java.lang.String-java.util.UUID-java.lang.String-int-}
```
public ImageCodecInfo(UUID clsid, String codecName, String filenameExtension, String formatDescription, UUID formatID, String mimeType, int version)
```


**Parameters:**
| Parameter | Type | Beschrijving |
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


Haalt een java.util.UUID-structuur op die een GUID bevat die een specifiek codec identificeert.

**Returns:**
java.util.UUID - een java.util.UUID
### setClsid(UUID value) {#setClsid-java.util.UUID-}
```
public void setClsid(UUID value)
```


Stelt een java.util.UUID-structuur in die een GUID bevat die een specifiek codec identificeert.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.util.UUID | een java.util.UUID |

### getFormatID() {#getFormatID--}
```
public UUID getFormatID()
```


Haalt een java.util.UUID-structuur op die een GUID bevat die het formaat van het codec identificeert.

**Returns:**
java.util.UUID - een java.util.UUID
### setFormatID(UUID value) {#setFormatID-java.util.UUID-}
```
public void setFormatID(UUID value)
```


Stelt een java.util.UUID-structuur in die een GUID bevat die het formaat van het codec identificeert.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.util.UUID | een java.util.UUID |

### getCodecName() {#getCodecName--}
```
public String getCodecName()
```


Haalt op of stelt een tekenreeks in die de naam van het codec bevat.

**Returns:**
java.lang.String
### setCodecName(String value) {#setCodecName-java.lang.String-}
```
public void setCodecName(String value)
```


Haalt op of stelt een tekenreeks in die de naam van het codec bevat.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getFormatDescription() {#getFormatDescription--}
```
public String getFormatDescription()
```


Haalt op of stelt een tekenreeks in die het bestandsformaat van het codec beschrijft.

**Returns:**
java.lang.String
### setFormatDescription(String value) {#setFormatDescription-java.lang.String-}
```
public void setFormatDescription(String value)
```


Haalt op of stelt een tekenreeks in die het bestandsformaat van het codec beschrijft.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getFilenameExtension() {#getFilenameExtension--}
```
public String getFilenameExtension()
```


Haalt de tekenreeks op of stelt deze in die de bestandsextensie(s) bevat die in de codec worden gebruikt. De extensies worden gescheiden door puntkomma's.

**Returns:**
java.lang.String
### setFilenameExtension(String value) {#setFilenameExtension-java.lang.String-}
```
public void setFilenameExtension(String value)
```


Haalt de tekenreeks op of stelt deze in die de bestandsextensie(s) bevat die in de codec worden gebruikt. De extensies worden gescheiden door puntkomma's.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getMimeType() {#getMimeType--}
```
public String getMimeType()
```


Haalt op of stelt een tekenreeks in die het Multipurpose Internet Mail Extensions (MIME)-type van het codec bevat.

**Returns:**
java.lang.String
### setMimeType(String value) {#setMimeType-java.lang.String-}
```
public void setMimeType(String value)
```


Haalt op of stelt een tekenreeks in die het Multipurpose Internet Mail Extensions (MIME)-type van het codec bevat.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getVersion() {#getVersion--}
```
public int getVersion()
```


Haalt op of stelt het versienummer van het codec in.

**Returns:**
int
### setVersion(int value) {#setVersion-int-}
```
public void setVersion(int value)
```


Haalt op of stelt het versienummer van het codec in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getSignaturePatterns() {#getSignaturePatterns--}
```
public byte[][] getSignaturePatterns()
```


Haalt op of stelt een tweedimensionale array van bytes in die de handtekening van het codec weergeeft.

**Returns:**
byte[][]
### setSignaturePatterns(byte[][] value) {#setSignaturePatterns-byte-----}
```
public void setSignaturePatterns(byte[][] value)
```


Haalt op of stelt een tweedimensionale array van bytes in die de handtekening van het codec weergeeft.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte[][] |  |

### getSignatureMasks() {#getSignatureMasks--}
```
public byte[][] getSignatureMasks()
```


Haalt op of stelt een tweedimensionale array van bytes in die als filter kan worden gebruikt.

**Returns:**
byte[][]
### setSignatureMasks(byte[][] value) {#setSignatureMasks-byte-----}
```
public void setSignatureMasks(byte[][] value)
```


Haalt op of stelt een tweedimensionale array van bytes in die als filter kan worden gebruikt.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte[][] |  |

### getImageDecoders() {#getImageDecoders--}
```
public static ImageCodecInfo[] getImageDecoders()
```


Retourneert een array van [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo)-objecten die informatie bevatten over de in GDI+ ingebouwde afbeeldingdecoders.

**Returns:**
com.aspose.drawing.imaging.ImageCodecInfo[] - Een array van [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo) objecten. Elk [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo) object in de array bevat informatie over een van de ingebouwde afbeeldingsdecoders.
### getImageEncoders() {#getImageEncoders--}
```
public static ImageCodecInfo[] getImageEncoders()
```


Retourneert een array van [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo)-objecten die informatie bevatten over de in GDI+ ingebouwde afbeeldingencoders.

**Returns:**
com.aspose.drawing.imaging.ImageCodecInfo[] - Een array van [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo) objecten. Elk [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo) object in de array bevat informatie over een van de ingebouwde afbeeldingsencoders.
