---
title: ImageCodecInfo
second_title: Referensi API Aspose.Drawing for Java
description: Kelas ini menyediakan anggota penyimpanan dan metode yang diperlukan untuk mengambil semua informasi relevan tentang enkoder dan dekoder gambar yang terpasang yang disebut codec.
type: docs
weight: 25
url: /id/java/com.aspose.drawing.imaging/imagecodecinfo/
---
**Inheritance:**
java.lang.Object
```
public final class ImageCodecInfo
```

Kelas [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo) menyediakan anggota penyimpanan dan metode yang diperlukan untuk mengambil semua informasi relevan tentang enkoder dan dekoder gambar yang terpasang (disebut codec). Tidak dapat diwariskan.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [ImageCodecInfo()](#ImageCodecInfo--) | Menginisialisasi sebuah instance baru dari kelas [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo). |
| [ImageCodecInfo(UUID clsid, String codecName, String filenameExtension, String formatDescription, UUID formatID, String mimeType, int version)](#ImageCodecInfo-java.util.UUID-java.lang.String-java.lang.String-java.lang.String-java.util.UUID-java.lang.String-int-) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getClsid()](#getClsid--) | Mendapatkan struktur java.util.UUID yang berisi GUID yang mengidentifikasi codec tertentu. |
| [setClsid(UUID value)](#setClsid-java.util.UUID-) | Menetapkan struktur java.util.UUID yang berisi GUID yang mengidentifikasi codec tertentu. |
| [getFormatID()](#getFormatID--) | Mendapatkan struktur java.util.UUID yang berisi GUID yang mengidentifikasi format codec. |
| [setFormatID(UUID value)](#setFormatID-java.util.UUID-) | Menetapkan struktur java.util.UUID yang berisi GUID yang mengidentifikasi format codec. |
| [getCodecName()](#getCodecName--) | Mendapatkan atau menetapkan string yang berisi nama codec. |
| [setCodecName(String value)](#setCodecName-java.lang.String-) | Mendapatkan atau menetapkan string yang berisi nama codec. |
| [getFormatDescription()](#getFormatDescription--) | Mendapatkan atau menetapkan string yang menjelaskan format file codec. |
| [setFormatDescription(String value)](#setFormatDescription-java.lang.String-) | Mendapatkan atau menetapkan string yang menjelaskan format file codec. |
| [getFilenameExtension()](#getFilenameExtension--) | Mendapatkan atau menetapkan string yang berisi ekstensi nama file yang digunakan dalam codec. |
| [setFilenameExtension(String value)](#setFilenameExtension-java.lang.String-) | Mendapatkan atau menetapkan string yang berisi ekstensi nama file yang digunakan dalam codec. |
| [getMimeType()](#getMimeType--) | Mendapatkan atau menetapkan string yang berisi tipe Multipurpose Internet Mail Extensions (MIME) codec. |
| [setMimeType(String value)](#setMimeType-java.lang.String-) | Mendapatkan atau menetapkan string yang berisi tipe Multipurpose Internet Mail Extensions (MIME) codec. |
| [getVersion()](#getVersion--) | Mendapatkan atau menetapkan nomor versi codec. |
| [setVersion(int value)](#setVersion-int-) | Mendapatkan atau menetapkan nomor versi codec. |
| [getSignaturePatterns()](#getSignaturePatterns--) | Mendapatkan atau menetapkan array dua dimensi byte yang mewakili tanda tangan codec. |
| [setSignaturePatterns(byte[][] value)](#setSignaturePatterns-byte-----) | Mendapatkan atau menetapkan array dua dimensi byte yang mewakili tanda tangan codec. |
| [getSignatureMasks()](#getSignatureMasks--) | Mendapatkan atau menetapkan array dua dimensi byte yang dapat digunakan sebagai filter. |
| [setSignatureMasks(byte[][] value)](#setSignatureMasks-byte-----) | Mendapatkan atau menetapkan array dua dimensi byte yang dapat digunakan sebagai filter. |
| [getImageDecoders()](#getImageDecoders--) | Mengembalikan array objek [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo) yang berisi informasi tentang dekoder gambar yang dibangun dalam GDI+. |
| [getImageEncoders()](#getImageEncoders--) | Mengembalikan array objek [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo) yang berisi informasi tentang enkoder gambar yang dibangun dalam GDI+. |
### ImageCodecInfo() {#ImageCodecInfo--}
```
public ImageCodecInfo()
```


Menginisialisasi sebuah instance baru dari kelas [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo).

### ImageCodecInfo(UUID clsid, String codecName, String filenameExtension, String formatDescription, UUID formatID, String mimeType, int version) {#ImageCodecInfo-java.util.UUID-java.lang.String-java.lang.String-java.lang.String-java.util.UUID-java.lang.String-int-}
```
public ImageCodecInfo(UUID clsid, String codecName, String filenameExtension, String formatDescription, UUID formatID, String mimeType, int version)
```


**Parameters:**
| Parameter | Tipe | Deskripsi |
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


Mendapatkan struktur java.util.UUID yang berisi GUID yang mengidentifikasi codec tertentu.

**Returns:**
java.util.UUID - sebuah java.util.UUID
### setClsid(UUID value) {#setClsid-java.util.UUID-}
```
public void setClsid(UUID value)
```


Menetapkan struktur java.util.UUID yang berisi GUID yang mengidentifikasi codec tertentu.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.util.UUID | sebuah java.util.UUID |

### getFormatID() {#getFormatID--}
```
public UUID getFormatID()
```


Mendapatkan struktur java.util.UUID yang berisi GUID yang mengidentifikasi format codec.

**Returns:**
java.util.UUID - sebuah java.util.UUID
### setFormatID(UUID value) {#setFormatID-java.util.UUID-}
```
public void setFormatID(UUID value)
```


Menetapkan struktur java.util.UUID yang berisi GUID yang mengidentifikasi format codec.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.util.UUID | sebuah java.util.UUID |

### getCodecName() {#getCodecName--}
```
public String getCodecName()
```


Mendapatkan atau menetapkan string yang berisi nama codec.

**Returns:**
java.lang.String
### setCodecName(String value) {#setCodecName-java.lang.String-}
```
public void setCodecName(String value)
```


Mendapatkan atau menetapkan string yang berisi nama codec.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |

### getFormatDescription() {#getFormatDescription--}
```
public String getFormatDescription()
```


Mendapatkan atau menetapkan string yang menjelaskan format file codec.

**Returns:**
java.lang.String
### setFormatDescription(String value) {#setFormatDescription-java.lang.String-}
```
public void setFormatDescription(String value)
```


Mendapatkan atau menetapkan string yang menjelaskan format file codec.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |

### getFilenameExtension() {#getFilenameExtension--}
```
public String getFilenameExtension()
```


Mendapatkan atau mengatur string yang berisi ekstensi nama file yang digunakan dalam codec. Ekstensi dipisahkan dengan titik koma.

**Returns:**
java.lang.String
### setFilenameExtension(String value) {#setFilenameExtension-java.lang.String-}
```
public void setFilenameExtension(String value)
```


Mendapatkan atau mengatur string yang berisi ekstensi nama file yang digunakan dalam codec. Ekstensi dipisahkan dengan titik koma.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |

### getMimeType() {#getMimeType--}
```
public String getMimeType()
```


Mendapatkan atau menetapkan string yang berisi tipe Multipurpose Internet Mail Extensions (MIME) codec.

**Returns:**
java.lang.String
### setMimeType(String value) {#setMimeType-java.lang.String-}
```
public void setMimeType(String value)
```


Mendapatkan atau menetapkan string yang berisi tipe Multipurpose Internet Mail Extensions (MIME) codec.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |

### getVersion() {#getVersion--}
```
public int getVersion()
```


Mendapatkan atau menetapkan nomor versi codec.

**Returns:**
int
### setVersion(int value) {#setVersion-int-}
```
public void setVersion(int value)
```


Mendapatkan atau menetapkan nomor versi codec.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getSignaturePatterns() {#getSignaturePatterns--}
```
public byte[][] getSignaturePatterns()
```


Mendapatkan atau menetapkan array dua dimensi byte yang mewakili tanda tangan codec.

**Returns:**
byte[][]
### setSignaturePatterns(byte[][] value) {#setSignaturePatterns-byte-----}
```
public void setSignaturePatterns(byte[][] value)
```


Mendapatkan atau menetapkan array dua dimensi byte yang mewakili tanda tangan codec.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | byte[][] |  |

### getSignatureMasks() {#getSignatureMasks--}
```
public byte[][] getSignatureMasks()
```


Mendapatkan atau menetapkan array dua dimensi byte yang dapat digunakan sebagai filter.

**Returns:**
byte[][]
### setSignatureMasks(byte[][] value) {#setSignatureMasks-byte-----}
```
public void setSignatureMasks(byte[][] value)
```


Mendapatkan atau menetapkan array dua dimensi byte yang dapat digunakan sebagai filter.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | byte[][] |  |

### getImageDecoders() {#getImageDecoders--}
```
public static ImageCodecInfo[] getImageDecoders()
```


Mengembalikan array objek [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo) yang berisi informasi tentang dekoder gambar yang dibangun dalam GDI+.

**Returns:**
com.aspose.drawing.imaging.ImageCodecInfo[] - Sebuah array dari objek [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo). Setiap objek [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo) dalam array berisi informasi tentang salah satu decoder gambar bawaan.
### getImageEncoders() {#getImageEncoders--}
```
public static ImageCodecInfo[] getImageEncoders()
```


Mengembalikan array objek [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo) yang berisi informasi tentang enkoder gambar yang dibangun dalam GDI+.

**Returns:**
com.aspose.drawing.imaging.ImageCodecInfo[] - Sebuah array dari objek [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo). Setiap objek [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo) dalam array berisi informasi tentang salah satu encoder gambar bawaan.
