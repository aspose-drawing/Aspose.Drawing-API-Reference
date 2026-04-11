---
title: ImageCodecInfo
second_title: Referencia de la API de Aspose.Drawing para Java
description: La clase proporciona los miembros de almacenamiento y métodos necesarios para recuperar toda la información pertinente sobre los codificadores y decodificadores de imágenes instalados, llamados codecs.
type: docs
weight: 25
url: /es/java/com.aspose.drawing.imaging/imagecodecinfo/
---
**Inheritance:**
java.lang.Object
```
public final class ImageCodecInfo
```

La clase [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo) proporciona los miembros y métodos de almacenamiento necesarios para obtener toda la información pertinente sobre los codificadores y decodificadores de imágenes instalados (llamados códecs). No heredable.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [ImageCodecInfo()](#ImageCodecInfo--) | Inicializa una nueva instancia de la clase [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo). |
| [ImageCodecInfo(UUID clsid, String codecName, String filenameExtension, String formatDescription, UUID formatID, String mimeType, int version)](#ImageCodecInfo-java.util.UUID-java.lang.String-java.lang.String-java.lang.String-java.util.UUID-java.lang.String-int-) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [getClsid()](#getClsid--) | Obtiene una estructura java.util.UUID que contiene un GUID que identifica un códec específico. |
| [setClsid(UUID value)](#setClsid-java.util.UUID-) | Establece una estructura java.util.UUID que contiene un GUID que identifica un códec específico. |
| [getFormatID()](#getFormatID--) | Obtiene una estructura java.util.UUID que contiene un GUID que identifica el formato del códec. |
| [setFormatID(UUID value)](#setFormatID-java.util.UUID-) | Establece una estructura java.util.UUID que contiene un GUID que identifica el formato del códec. |
| [getCodecName()](#getCodecName--) | Obtiene o establece una cadena que contiene el nombre del códec. |
| [setCodecName(String value)](#setCodecName-java.lang.String-) | Obtiene o establece una cadena que contiene el nombre del códec. |
| [getFormatDescription()](#getFormatDescription--) | Obtiene o establece una cadena que describe el formato de archivo del códec. |
| [setFormatDescription(String value)](#setFormatDescription-java.lang.String-) | Obtiene o establece una cadena que describe el formato de archivo del códec. |
| [getFilenameExtension()](#getFilenameExtension--) | Obtiene o establece una cadena que contiene la(s) extensión(es) de nombre de archivo usadas en el códec. |
| [setFilenameExtension(String value)](#setFilenameExtension-java.lang.String-) | Obtiene o establece una cadena que contiene la(s) extensión(es) de nombre de archivo usadas en el códec. |
| [getMimeType()](#getMimeType--) | Obtiene o establece una cadena que contiene el tipo Multipurpose Internet Mail Extensions (MIME) del códec. |
| [setMimeType(String value)](#setMimeType-java.lang.String-) | Obtiene o establece una cadena que contiene el tipo Multipurpose Internet Mail Extensions (MIME) del códec. |
| [getVersion()](#getVersion--) | Obtiene o establece el número de versión del códec. |
| [setVersion(int value)](#setVersion-int-) | Obtiene o establece el número de versión del códec. |
| [getSignaturePatterns()](#getSignaturePatterns--) | Obtiene o establece una matriz bidimensional de bytes que representa la firma del códec. |
| [setSignaturePatterns(byte[][] value)](#setSignaturePatterns-byte-----) | Obtiene o establece una matriz bidimensional de bytes que representa la firma del códec. |
| [getSignatureMasks()](#getSignatureMasks--) | Obtiene o establece una matriz bidimensional de bytes que puede usarse como filtro. |
| [setSignatureMasks(byte[][] value)](#setSignatureMasks-byte-----) | Obtiene o establece una matriz bidimensional de bytes que puede usarse como filtro. |
| [getImageDecoders()](#getImageDecoders--) | Devuelve una matriz de objetos [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo) que contienen información sobre los decodificadores de imágenes incorporados en GDI+. |
| [getImageEncoders()](#getImageEncoders--) | Devuelve una matriz de objetos [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo) que contienen información sobre los codificadores de imágenes incorporados en GDI+. |
### ImageCodecInfo() {#ImageCodecInfo--}
```
public ImageCodecInfo()
```


Inicializa una nueva instancia de la clase [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo).

### ImageCodecInfo(UUID clsid, String codecName, String filenameExtension, String formatDescription, UUID formatID, String mimeType, int version) {#ImageCodecInfo-java.util.UUID-java.lang.String-java.lang.String-java.lang.String-java.util.UUID-java.lang.String-int-}
```
public ImageCodecInfo(UUID clsid, String codecName, String filenameExtension, String formatDescription, UUID formatID, String mimeType, int version)
```


**Parameters:**
| Parámetro | Tipo | Descripción |
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


Obtiene una estructura java.util.UUID que contiene un GUID que identifica un códec específico.

**Returns:**
java.util.UUID - un java.util.UUID
### setClsid(UUID value) {#setClsid-java.util.UUID-}
```
public void setClsid(UUID value)
```


Establece una estructura java.util.UUID que contiene un GUID que identifica un códec específico.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.util.UUID | un java.util.UUID |

### getFormatID() {#getFormatID--}
```
public UUID getFormatID()
```


Obtiene una estructura java.util.UUID que contiene un GUID que identifica el formato del códec.

**Returns:**
java.util.UUID - un java.util.UUID
### setFormatID(UUID value) {#setFormatID-java.util.UUID-}
```
public void setFormatID(UUID value)
```


Establece una estructura java.util.UUID que contiene un GUID que identifica el formato del códec.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.util.UUID | un java.util.UUID |

### getCodecName() {#getCodecName--}
```
public String getCodecName()
```


Obtiene o establece una cadena que contiene el nombre del códec.

**Returns:**
java.lang.String
### setCodecName(String value) {#setCodecName-java.lang.String-}
```
public void setCodecName(String value)
```


Obtiene o establece una cadena que contiene el nombre del códec.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |

### getFormatDescription() {#getFormatDescription--}
```
public String getFormatDescription()
```


Obtiene o establece una cadena que describe el formato de archivo del códec.

**Returns:**
java.lang.String
### setFormatDescription(String value) {#setFormatDescription-java.lang.String-}
```
public void setFormatDescription(String value)
```


Obtiene o establece una cadena que describe el formato de archivo del códec.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |

### getFilenameExtension() {#getFilenameExtension--}
```
public String getFilenameExtension()
```


Obtiene o establece la cadena que contiene la(s) extensión(es) de nombre de archivo utilizadas en el códec. Las extensiones están separadas por puntos y comas.

**Returns:**
java.lang.String
### setFilenameExtension(String value) {#setFilenameExtension-java.lang.String-}
```
public void setFilenameExtension(String value)
```


Obtiene o establece la cadena que contiene la(s) extensión(es) de nombre de archivo utilizadas en el códec. Las extensiones están separadas por puntos y comas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |

### getMimeType() {#getMimeType--}
```
public String getMimeType()
```


Obtiene o establece una cadena que contiene el tipo Multipurpose Internet Mail Extensions (MIME) del códec.

**Returns:**
java.lang.String
### setMimeType(String value) {#setMimeType-java.lang.String-}
```
public void setMimeType(String value)
```


Obtiene o establece una cadena que contiene el tipo Multipurpose Internet Mail Extensions (MIME) del códec.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |

### getVersion() {#getVersion--}
```
public int getVersion()
```


Obtiene o establece el número de versión del códec.

**Returns:**
int
### setVersion(int value) {#setVersion-int-}
```
public void setVersion(int value)
```


Obtiene o establece el número de versión del códec.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getSignaturePatterns() {#getSignaturePatterns--}
```
public byte[][] getSignaturePatterns()
```


Obtiene o establece una matriz bidimensional de bytes que representa la firma del códec.

**Returns:**
byte[][]
### setSignaturePatterns(byte[][] value) {#setSignaturePatterns-byte-----}
```
public void setSignaturePatterns(byte[][] value)
```


Obtiene o establece una matriz bidimensional de bytes que representa la firma del códec.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | byte[][] |  |

### getSignatureMasks() {#getSignatureMasks--}
```
public byte[][] getSignatureMasks()
```


Obtiene o establece una matriz bidimensional de bytes que puede usarse como filtro.

**Returns:**
byte[][]
### setSignatureMasks(byte[][] value) {#setSignatureMasks-byte-----}
```
public void setSignatureMasks(byte[][] value)
```


Obtiene o establece una matriz bidimensional de bytes que puede usarse como filtro.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | byte[][] |  |

### getImageDecoders() {#getImageDecoders--}
```
public static ImageCodecInfo[] getImageDecoders()
```


Devuelve una matriz de objetos [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo) que contienen información sobre los decodificadores de imágenes incorporados en GDI+.

**Returns:**
com.aspose.drawing.imaging.ImageCodecInfo[] - Una matriz de objetos [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo). Cada objeto [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo) en la matriz contiene información sobre uno de los decodificadores de imagen incorporados.
### getImageEncoders() {#getImageEncoders--}
```
public static ImageCodecInfo[] getImageEncoders()
```


Devuelve una matriz de objetos [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo) que contienen información sobre los codificadores de imágenes incorporados en GDI+.

**Returns:**
com.aspose.drawing.imaging.ImageCodecInfo[] - Una matriz de objetos [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo). Cada objeto [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo) en la matriz contiene información sobre uno de los codificadores de imagen incorporados.
