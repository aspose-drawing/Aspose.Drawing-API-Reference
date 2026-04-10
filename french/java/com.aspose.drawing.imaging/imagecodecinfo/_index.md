---
title: ImageCodecInfo
second_title: Référence de l'API Aspose.Drawing pour Java
description: La classe fournit les membres de stockage nécessaires et les méthodes pour récupérer toutes les informations pertinentes sur les encodeurs et décodeurs d'images installés appelés codecs.
type: docs
weight: 25
url: /fr/java/com.aspose.drawing.imaging/imagecodecinfo/
---
**Inheritance:**
java.lang.Object
```
public final class ImageCodecInfo
```

La classe [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo) fournit les membres de stockage nécessaires et les méthodes pour récupérer toutes les informations pertinentes sur les encodeurs et décodeurs d'images installés (appelés codecs). Non héritable.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [ImageCodecInfo()](#ImageCodecInfo--) | Initialise une nouvelle instance de la classe [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo). |
| [ImageCodecInfo(UUID clsid, String codecName, String filenameExtension, String formatDescription, UUID formatID, String mimeType, int version)](#ImageCodecInfo-java.util.UUID-java.lang.String-java.lang.String-java.lang.String-java.util.UUID-java.lang.String-int-) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getClsid()](#getClsid--) | Obtient une structure java.util.UUID qui contient un GUID identifiant un codec spécifique. |
| [setClsid(UUID value)](#setClsid-java.util.UUID-) | Définit une structure java.util.UUID qui contient un GUID identifiant un codec spécifique. |
| [getFormatID()](#getFormatID--) | Obtient une structure java.util.UUID qui contient un GUID identifiant le format du codec. |
| [setFormatID(UUID value)](#setFormatID-java.util.UUID-) | Définit une structure java.util.UUID qui contient un GUID identifiant le format du codec. |
| [getCodecName()](#getCodecName--) | Obtient ou définit une chaîne qui contient le nom du codec. |
| [setCodecName(String value)](#setCodecName-java.lang.String-) | Obtient ou définit une chaîne qui contient le nom du codec. |
| [getFormatDescription()](#getFormatDescription--) | Obtient ou définit une chaîne qui décrit le format de fichier du codec. |
| [setFormatDescription(String value)](#setFormatDescription-java.lang.String-) | Obtient ou définit une chaîne qui décrit le format de fichier du codec. |
| [getFilenameExtension()](#getFilenameExtension--) | Obtient ou définit une chaîne qui contient les extensions de nom de fichier utilisées par le codec. |
| [setFilenameExtension(String value)](#setFilenameExtension-java.lang.String-) | Obtient ou définit une chaîne qui contient les extensions de nom de fichier utilisées par le codec. |
| [getMimeType()](#getMimeType--) | Obtient ou définit une chaîne qui contient le type Multipurpose Internet Mail Extensions (MIME) du codec. |
| [setMimeType(String value)](#setMimeType-java.lang.String-) | Obtient ou définit une chaîne qui contient le type Multipurpose Internet Mail Extensions (MIME) du codec. |
| [getVersion()](#getVersion--) | Obtient ou définit le numéro de version du codec. |
| [setVersion(int value)](#setVersion-int-) | Obtient ou définit le numéro de version du codec. |
| [getSignaturePatterns()](#getSignaturePatterns--) | Obtient ou définit un tableau à deux dimensions d'octets qui représente la signature du codec. |
| [setSignaturePatterns(byte[][] value)](#setSignaturePatterns-byte-----) | Obtient ou définit un tableau à deux dimensions d'octets qui représente la signature du codec. |
| [getSignatureMasks()](#getSignatureMasks--) | Obtient ou définit un tableau à deux dimensions d'octets qui peut être utilisé comme filtre. |
| [setSignatureMasks(byte[][] value)](#setSignatureMasks-byte-----) | Obtient ou définit un tableau à deux dimensions d'octets qui peut être utilisé comme filtre. |
| [getImageDecoders()](#getImageDecoders--) | Renvoie un tableau d'objets [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo) contenant des informations sur les décodeurs d'images intégrés à GDI+. |
| [getImageEncoders()](#getImageEncoders--) | Renvoie un tableau d'objets [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo) contenant des informations sur les encodeurs d'images intégrés à GDI+. |
### ImageCodecInfo() {#ImageCodecInfo--}
```
public ImageCodecInfo()
```


Initialise une nouvelle instance de la classe [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo).

### ImageCodecInfo(UUID clsid, String codecName, String filenameExtension, String formatDescription, UUID formatID, String mimeType, int version) {#ImageCodecInfo-java.util.UUID-java.lang.String-java.lang.String-java.lang.String-java.util.UUID-java.lang.String-int-}
```
public ImageCodecInfo(UUID clsid, String codecName, String filenameExtension, String formatDescription, UUID formatID, String mimeType, int version)
```


**Parameters:**
| Paramètre | Type | Description |
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


Obtient une structure java.util.UUID qui contient un GUID identifiant un codec spécifique.

**Returns:**
java.util.UUID - un java.util.UUID
### setClsid(UUID value) {#setClsid-java.util.UUID-}
```
public void setClsid(UUID value)
```


Définit une structure java.util.UUID qui contient un GUID identifiant un codec spécifique.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.util.UUID | un java.util.UUID |

### getFormatID() {#getFormatID--}
```
public UUID getFormatID()
```


Obtient une structure java.util.UUID qui contient un GUID identifiant le format du codec.

**Returns:**
java.util.UUID - un java.util.UUID
### setFormatID(UUID value) {#setFormatID-java.util.UUID-}
```
public void setFormatID(UUID value)
```


Définit une structure java.util.UUID qui contient un GUID identifiant le format du codec.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.util.UUID | un java.util.UUID |

### getCodecName() {#getCodecName--}
```
public String getCodecName()
```


Obtient ou définit une chaîne qui contient le nom du codec.

**Returns:**
java.lang.String
### setCodecName(String value) {#setCodecName-java.lang.String-}
```
public void setCodecName(String value)
```


Obtient ou définit une chaîne qui contient le nom du codec.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getFormatDescription() {#getFormatDescription--}
```
public String getFormatDescription()
```


Obtient ou définit une chaîne qui décrit le format de fichier du codec.

**Returns:**
java.lang.String
### setFormatDescription(String value) {#setFormatDescription-java.lang.String-}
```
public void setFormatDescription(String value)
```


Obtient ou définit une chaîne qui décrit le format de fichier du codec.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getFilenameExtension() {#getFilenameExtension--}
```
public String getFilenameExtension()
```


Obtient ou définit la chaîne qui contient l(es) extension(s) de nom de fichier utilisées dans le codec. Les extensions sont séparées par des points-virgules.

**Returns:**
java.lang.String
### setFilenameExtension(String value) {#setFilenameExtension-java.lang.String-}
```
public void setFilenameExtension(String value)
```


Obtient ou définit la chaîne qui contient l(es) extension(s) de nom de fichier utilisées dans le codec. Les extensions sont séparées par des points-virgules.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getMimeType() {#getMimeType--}
```
public String getMimeType()
```


Obtient ou définit une chaîne qui contient le type Multipurpose Internet Mail Extensions (MIME) du codec.

**Returns:**
java.lang.String
### setMimeType(String value) {#setMimeType-java.lang.String-}
```
public void setMimeType(String value)
```


Obtient ou définit une chaîne qui contient le type Multipurpose Internet Mail Extensions (MIME) du codec.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getVersion() {#getVersion--}
```
public int getVersion()
```


Obtient ou définit le numéro de version du codec.

**Returns:**
int
### setVersion(int value) {#setVersion-int-}
```
public void setVersion(int value)
```


Obtient ou définit le numéro de version du codec.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSignaturePatterns() {#getSignaturePatterns--}
```
public byte[][] getSignaturePatterns()
```


Obtient ou définit un tableau à deux dimensions d'octets qui représente la signature du codec.

**Returns:**
byte[][]
### setSignaturePatterns(byte[][] value) {#setSignaturePatterns-byte-----}
```
public void setSignaturePatterns(byte[][] value)
```


Obtient ou définit un tableau à deux dimensions d'octets qui représente la signature du codec.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte[][] |  |

### getSignatureMasks() {#getSignatureMasks--}
```
public byte[][] getSignatureMasks()
```


Obtient ou définit un tableau à deux dimensions d'octets qui peut être utilisé comme filtre.

**Returns:**
byte[][]
### setSignatureMasks(byte[][] value) {#setSignatureMasks-byte-----}
```
public void setSignatureMasks(byte[][] value)
```


Obtient ou définit un tableau à deux dimensions d'octets qui peut être utilisé comme filtre.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte[][] |  |

### getImageDecoders() {#getImageDecoders--}
```
public static ImageCodecInfo[] getImageDecoders()
```


Renvoie un tableau d'objets [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo) contenant des informations sur les décodeurs d'images intégrés à GDI+.

**Returns:**
com.aspose.drawing.imaging.ImageCodecInfo[] - Un tableau d'objets [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo). Chaque objet [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo) du tableau contient des informations sur l'un des décodeurs d'images intégrés.
### getImageEncoders() {#getImageEncoders--}
```
public static ImageCodecInfo[] getImageEncoders()
```


Renvoie un tableau d'objets [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo) contenant des informations sur les encodeurs d'images intégrés à GDI+.

**Returns:**
com.aspose.drawing.imaging.ImageCodecInfo[] - Un tableau d'objets [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo). Chaque objet [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo) du tableau contient des informations sur l'un des encodeurs d'images intégrés.
