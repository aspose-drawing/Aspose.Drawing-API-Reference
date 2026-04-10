---
title: Metafile
second_title: Referensi API Aspose.Drawing for Java
description: Mendefinisikan metafile grafis.
type: docs
weight: 30
url: /id/java/com.aspose.drawing.imaging/metafile/
---
**Inheritance:**
java.lang.Object, [com.aspose.drawing.Image](../../com.aspose.drawing/image)
```
public final class Metafile extends Image
```

Menentukan sebuah metafile grafis. Sebuah metafile berisi rekaman yang menggambarkan urutan operasi grafis yang dapat direkam (dibuat) dan diputar kembali (ditampilkan). Kelas ini tidak dapat diwariskan.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [Metafile(byte[] henhmetafile, boolean deleteEmf)](#Metafile-byte---boolean-) | Menginisialisasi sebuah instance baru dari kelas [Metafile](../../com.aspose.drawing.imaging/metafile) dari handle yang ditentukan. |
| [Metafile(byte[] referenceHdc, int emfType)](#Metafile-byte---int-) | Menginisialisasi sebuah instance baru dari kelas [Metafile](../../com.aspose.drawing.imaging/metafile) dari handle yang ditentukan ke konteks perangkat dan enumerasi [EmfType](../../com.aspose.drawing.imaging/emftype) yang menentukan format dari [Metafile](../../com.aspose.drawing.imaging/metafile). |
| [Metafile(String filename)](#Metafile-java.lang.String-) | Menginisialisasi sebuah instance baru dari kelas [Metafile](../../com.aspose.drawing.imaging/metafile) dari nama file yang ditentukan. |
| [Metafile(String filename, byte[] referenceHdc)](#Metafile-java.lang.String-byte---) | Menginisialisasi sebuah instance baru dari kelas [Metafile](../../com.aspose.drawing.imaging/metafile) dari nama file yang ditentukan. |
| [Metafile(InputStream stream)](#Metafile-java.io.InputStream-) | Menginisialisasi sebuah instance baru dari kelas [Metafile](../../com.aspose.drawing.imaging/metafile) dari aliran data yang ditentukan. |
| [Metafile(InputStream stream, byte[] referenceHdc)](#Metafile-java.io.InputStream-byte---) | Menginisialisasi sebuah instance baru dari kelas [Metafile](../../com.aspose.drawing.imaging/metafile) dari aliran data yang ditentukan dan sebuah handle Windows ke konteks perangkat. |
| [Metafile(System.IO.Stream stream, int type)](#Metafile-com.aspose.ms.System.IO.Stream-int-) | Menginisialisasi sebuah instance baru dari kelas [Metafile](../../com.aspose.drawing.imaging/metafile) dari aliran data yang ditentukan dan sebuah handle Windows ke konteks perangkat. |
| [Metafile(InputStream stream, byte[] referenceHdc, int type)](#Metafile-java.io.InputStream-byte---int-) | Menginisialisasi sebuah instance baru dari kelas [Metafile](../../com.aspose.drawing.imaging/metafile) dari aliran data yang ditentukan, sebuah handle Windows ke konteks perangkat, dan enumerasi [EmfType](../../com.aspose.drawing.imaging/emftype) yang menentukan format dari [Metafile](../../com.aspose.drawing.imaging/metafile). |
| [Metafile(InputStream stream, byte[] referenceHdc, RectangleF frameRect, int frameUnit, int type)](#Metafile-java.io.InputStream-byte---com.aspose.drawing.RectangleF-int-int-) | Menginisialisasi sebuah instance baru dari kelas [Metafile](../../com.aspose.drawing.imaging/metafile) dari aliran data yang ditentukan, sebuah handle Windows ke konteks perangkat, dan enumerasi [EmfType](../../com.aspose.drawing.imaging/emftype) yang menentukan format dari [Metafile](../../com.aspose.drawing.imaging/metafile). |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getWidth()](#getWidth--) | Mendapatkan lebar, dalam piksel, dari [Metafile](../../com.aspose.drawing.imaging/metafile). |
| [getHeight()](#getHeight--) | Mendapatkan tinggi, dalam piksel, dari [Metafile](../../com.aspose.drawing.imaging/metafile). |
| [getRawFormat()](#getRawFormat--) | Mendapatkan format berkas dari [Image](../../com.aspose.drawing/image). |
| [getPixelFormat()](#getPixelFormat--) | Mendapatkan format piksel untuk [Image](../../com.aspose.drawing/image). |
| [getPalette()](#getPalette--) | Mendapatkan atau mengatur palet warna yang digunakan untuk [Image](../../com.aspose.drawing/image). |
| [setPalette(ColorPalette value)](#setPalette-com.aspose.drawing.imaging.ColorPalette-) | Mendapatkan atau mengatur palet warna yang digunakan untuk [Image](../../com.aspose.drawing/image). |
| [getFrameDimensionsList()](#getFrameDimensionsList--) | Mendapatkan array GUID yang mewakili dimensi frame dalam [Image](../../com.aspose.drawing/image). |
| [getPropertyIdList()](#getPropertyIdList--) | Mendapatkan ID dari item properti yang disimpan dalam [Image](../../com.aspose.drawing/image). |
| [getPropertyItems()](#getPropertyItems--) | Mendapatkan semua item properti (potongan metadata) yang disimpan dalam [Image](../../com.aspose.drawing/image). |
| [getMetafileHeader(InputStream stream)](#getMetafileHeader-java.io.InputStream-) | Mengembalikan [MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) yang terkait dengan [Metafile](../../com.aspose.drawing.imaging/metafile) yang ditentukan. |
| [getMetafileHeader(String fileName)](#getMetafileHeader-java.lang.String-) | Mengembalikan [MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) yang terkait dengan [Metafile](../../com.aspose.drawing.imaging/metafile) yang ditentukan. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | Metode ini memutar, membalik, atau memutar dan membalik [Image](../../com.aspose.drawing/image). |
| [getHenhmetafile()](#getHenhmetafile--) | Mengembalikan sebuah handle Windows ke [Metafile](../../com.aspose.drawing.imaging/metafile) yang ditingkatkan. |
| [playRecord(int recordType, int flags, int dataSize, byte[] dataArray)](#playRecord-int-int-int-byte---) | Memutar sebuah rekaman metafile individu. |
| [getMetafileHeader()](#getMetafileHeader--) | Mengembalikan [MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) yang terkait dengan [Metafile](../../com.aspose.drawing.imaging/metafile) ini. |
| [getPropertyItem(int propid)](#getPropertyItem-int-) | Mendapatkan item properti yang ditentukan dari [Image](../../com.aspose.drawing/image). |
| [removePropertyItem(int propid)](#removePropertyItem-int-) | Menghapus item properti yang ditentukan dari [Image](../../com.aspose.drawing/image). |
| [setPropertyItem(PropertyItem propitem)](#setPropertyItem-com.aspose.drawing.imaging.PropertyItem-) | Menyimpan sebuah item properti (potongan metadata) dalam [Image](../../com.aspose.drawing/image). |
### Metafile(byte[] henhmetafile, boolean deleteEmf) {#Metafile-byte---boolean-}
```
public Metafile(byte[] henhmetafile, boolean deleteEmf)
```


Menginisialisasi sebuah instance baru dari kelas [Metafile](../../com.aspose.drawing.imaging/metafile) dari handle yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| henhmetafile | byte[] | Pegangan ke metafile yang ditingkatkan. |
| deleteEmf | boolean | true untuk menghapus pegangan metafile yang ditingkatkan ketika [Metafile](../../com.aspose.drawing.imaging/metafile) dihapus; jika tidak, false. |

### Metafile(byte[] referenceHdc, int emfType) {#Metafile-byte---int-}
```
public Metafile(byte[] referenceHdc, int emfType)
```


Menginisialisasi sebuah instance baru dari kelas [Metafile](../../com.aspose.drawing.imaging/metafile) dari handle yang ditentukan ke konteks perangkat dan enumerasi [EmfType](../../com.aspose.drawing.imaging/emftype) yang menentukan format dari [Metafile](../../com.aspose.drawing.imaging/metafile).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| referenceHdc | byte[] | Pegangan ke konteks perangkat. |
| emfType | int | Sebuah [EmfType](../../com.aspose.drawing.imaging/emftype) yang menentukan format dari [Metafile](../../com.aspose.drawing.imaging/metafile). |

### Metafile(String filename) {#Metafile-java.lang.String-}
```
public Metafile(String filename)
```


Menginisialisasi sebuah instance baru dari kelas [Metafile](../../com.aspose.drawing.imaging/metafile) dari nama file yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filename | java.lang.String | String yang mewakili nama file dari mana membuat [Metafile](../../com.aspose.drawing.imaging/metafile). |

### Metafile(String filename, byte[] referenceHdc) {#Metafile-java.lang.String-byte---}
```
public Metafile(String filename, byte[] referenceHdc)
```


Menginisialisasi sebuah instance baru dari kelas [Metafile](../../com.aspose.drawing.imaging/metafile) dari nama file yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filename | java.lang.String | String yang mewakili nama file dari mana membuat [Metafile](../../com.aspose.drawing.imaging/metafile). |
| referenceHdc | byte[] | Pegangan Windows ke konteks perangkat. |

### Metafile(InputStream stream) {#Metafile-java.io.InputStream-}
```
public Metafile(InputStream stream)
```


Menginisialisasi sebuah instance baru dari kelas [Metafile](../../com.aspose.drawing.imaging/metafile) dari aliran data yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | java.io.InputStream | InputStream yang digunakan untuk membuat [Metafile](../../com.aspose.drawing.imaging/metafile) yang baru. |

### Metafile(InputStream stream, byte[] referenceHdc) {#Metafile-java.io.InputStream-byte---}
```
public Metafile(InputStream stream, byte[] referenceHdc)
```


Menginisialisasi instance baru dari kelas [Metafile](../../com.aspose.drawing.imaging/metafile) dari aliran data yang ditentukan dan pegangan Windows ke konteks perangkat. />.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | java.io.InputStream | InputStream yang berisi data untuk [Metafile](../../com.aspose.drawing.imaging/metafile). |
| referenceHdc | byte[] | Pegangan Windows ke konteks perangkat dari objek [Metafile](../../com.aspose.drawing.imaging/metafile). |

### Metafile(System.IO.Stream stream, int type) {#Metafile-com.aspose.ms.System.IO.Stream-int-}
```
public Metafile(System.IO.Stream stream, int type)
```


Menginisialisasi instance baru dari kelas [Metafile](../../com.aspose.drawing.imaging/metafile) dari aliran data yang ditentukan dan pegangan Windows ke konteks perangkat. />.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | InputStream yang berisi data untuk [Metafile](../../com.aspose.drawing.imaging/metafile). |
| tipe | int | harus berupa int 1. |

### Metafile(InputStream stream, byte[] referenceHdc, int type) {#Metafile-java.io.InputStream-byte---int-}
```
public Metafile(InputStream stream, byte[] referenceHdc, int type)
```


Menginisialisasi sebuah instance baru dari kelas [Metafile](../../com.aspose.drawing.imaging/metafile) dari aliran data yang ditentukan, sebuah handle Windows ke konteks perangkat, dan enumerasi [EmfType](../../com.aspose.drawing.imaging/emftype) yang menentukan format dari [Metafile](../../com.aspose.drawing.imaging/metafile).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | java.io.InputStream | InputStream yang berisi data untuk [Metafile](../../com.aspose.drawing.imaging/metafile). |
| referenceHdc | byte[] | Pegangan Windows ke konteks perangkat. |
| type | int | Sebuah [EmfType](../../com.aspose.drawing.imaging/emftype) yang menentukan format dari [Metafile](../../com.aspose.drawing.imaging/metafile). |

### Metafile(InputStream stream, byte[] referenceHdc, RectangleF frameRect, int frameUnit, int type) {#Metafile-java.io.InputStream-byte---com.aspose.drawing.RectangleF-int-int-}
```
public Metafile(InputStream stream, byte[] referenceHdc, RectangleF frameRect, int frameUnit, int type)
```


Menginisialisasi sebuah instance baru dari kelas [Metafile](../../com.aspose.drawing.imaging/metafile) dari aliran data yang ditentukan, sebuah handle Windows ke konteks perangkat, dan enumerasi [EmfType](../../com.aspose.drawing.imaging/emftype) yang menentukan format dari [Metafile](../../com.aspose.drawing.imaging/metafile).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | java.io.InputStream | InputStream yang berisi data untuk [Metafile](../../com.aspose.drawing.imaging/metafile). |
| referenceHdc | byte[] | Pegangan Windows ke konteks perangkat. |
| frameRect | [RectangleF](../../com.aspose.drawing/rectanglef) | Sebuah [Rectangle](../../com.aspose.drawing/rectangle) yang mewakili persegi panjang yang membatasi [Metafile](../../com.aspose.drawing.imaging/metafile) yang baru. |
| frameUnit | int | Sebuah [MetafileFrameUnit](../../com.aspose.drawing.imaging/metafileframeunit) yang menentukan satuan ukuran untuk frameRect. |
| type | int | Sebuah [EmfType](../../com.aspose.drawing.imaging/emftype) yang menentukan format dari [Metafile](../../com.aspose.drawing.imaging/metafile). |

### getWidth() {#getWidth--}
```
public int getWidth()
```


Mendapatkan lebar, dalam piksel, dari [Metafile](../../com.aspose.drawing.imaging/metafile).

**Returns:**
int
### getHeight() {#getHeight--}
```
public int getHeight()
```


Mendapatkan tinggi, dalam piksel, dari [Metafile](../../com.aspose.drawing.imaging/metafile).

**Returns:**
int - tinggi, dalam piksel, dari [Metafile](../../com.aspose.drawing.imaging/metafile).
### getRawFormat() {#getRawFormat--}
```
public ImageFormat getRawFormat()
```


Mendapatkan format berkas dari [Image](../../com.aspose.drawing/image).

**Returns:**
[ImageFormat](../../com.aspose.drawing.imaging/imageformat) - The [ImageFormat](../../com.aspose.drawing.imaging/imageformat) that represents the file format of this [Image](../../com.aspose.drawing/image).
### getPixelFormat() {#getPixelFormat--}
```
public int getPixelFormat()
```


Mendapatkan format piksel untuk [Image](../../com.aspose.drawing/image).

**Returns:**
int - Sebuah `PixelFormat`([Image.getPixelFormat](../../com.aspose.drawing/image\#getPixelFormat)) yang mewakili format piksel untuk [Image](../../com.aspose.drawing/image).
### getPalette() {#getPalette--}
```
public ColorPalette getPalette()
```


Mendapatkan atau mengatur palet warna yang digunakan untuk [Image](../../com.aspose.drawing/image).

**Returns:**
[ColorPalette](../../com.aspose.drawing.imaging/colorpalette) - A [ColorPalette](../../com.aspose.drawing.imaging/colorpalette) that represents the color palette used for this [Image](../../com.aspose.drawing/image).
### setPalette(ColorPalette value) {#setPalette-com.aspose.drawing.imaging.ColorPalette-}
```
public void setPalette(ColorPalette value)
```


Mendapatkan atau mengatur palet warna yang digunakan untuk [Image](../../com.aspose.drawing/image).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [ColorPalette](../../com.aspose.drawing.imaging/colorpalette) |  |

### getFrameDimensionsList() {#getFrameDimensionsList--}
```
public UUID[] getFrameDimensionsList()
```


Mendapatkan array GUID yang mewakili dimensi frame dalam [Image](../../com.aspose.drawing/image).

**Returns:**
java.util.UUID[] - Sebuah array GUID yang menentukan dimensi frame dalam [Image](../../com.aspose.drawing/image) dari yang paling signifikan hingga paling tidak signifikan.
### getPropertyIdList() {#getPropertyIdList--}
```
public int[] getPropertyIdList()
```


Mendapatkan ID dari item properti yang disimpan dalam [Image](../../com.aspose.drawing/image).

**Returns:**
int[] - Sebuah array ID properti, satu untuk setiap item properti yang disimpan dalam gambar ini.
### getPropertyItems() {#getPropertyItems--}
```
public PropertyItem[] getPropertyItems()
```


Mendapatkan semua item properti (potongan metadata) yang disimpan dalam [Image](../../com.aspose.drawing/image).

**Returns:**
com.aspose.drawing.imaging.PropertyItem[] - Sebuah array objek [PropertyItem](../../com.aspose.drawing.imaging/propertyitem), satu untuk setiap item properti yang disimpan dalam gambar.
### getMetafileHeader(InputStream stream) {#getMetafileHeader-java.io.InputStream-}
```
public static MetafileHeader getMetafileHeader(InputStream stream)
```


Mengembalikan [MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) yang terkait dengan [Metafile](../../com.aspose.drawing.imaging/metafile) yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | java.io.InputStream | InputStream yang berisi [Metafile](../../com.aspose.drawing.imaging/metafile) untuk mana header diambil. |

**Returns:**
[MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) - The [MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) associated with the specified [Metafile](../../com.aspose.drawing.imaging/metafile).
### getMetafileHeader(String fileName) {#getMetafileHeader-java.lang.String-}
```
public static MetafileHeader getMetafileHeader(String fileName)
```


Mengembalikan [MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) yang terkait dengan [Metafile](../../com.aspose.drawing.imaging/metafile) yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fileName | java.lang.String | String yang berisi nama [Metafile](../../com.aspose.drawing.imaging/metafile) untuk mana header diambil. |

**Returns:**
[MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) - The [MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) associated with the specified [Metafile](../../com.aspose.drawing.imaging/metafile).
### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


Metode ini memutar, membalik, atau memutar dan membalik [Image](../../com.aspose.drawing/image).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rotateFlipType | int | Anggota [RotateFlipType](../../com.aspose.drawing/rotatefliptype) yang menentukan jenis rotasi dan flip yang akan diterapkan pada gambar. |

### getHenhmetafile() {#getHenhmetafile--}
```
public System.IntPtr getHenhmetafile()
```


Mengembalikan sebuah handle Windows ke [Metafile](../../com.aspose.drawing.imaging/metafile) yang ditingkatkan.

**Returns:**
com.aspose.ms.System.IntPtr - Sebuah pegangan Windows ke [Metafile](../../com.aspose.drawing.imaging/metafile) yang ditingkatkan ini.
### playRecord(int recordType, int flags, int dataSize, byte[] dataArray) {#playRecord-int-int-int-byte---}
```
public void playRecord(int recordType, int flags, int dataSize, byte[] dataArray)
```


Memutar sebuah rekaman metafile individu.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| recordType | int | Elemen dari [EmfPlusRecordType](../../com.aspose.drawing.imaging/emfplusrecordtype) yang menentukan jenis rekaman metafile yang sedang diputar. |
| flags | int | Serangkaian flag yang menentukan atribut rekaman. |
| dataSize | int | Jumlah byte dalam data rekaman. |
| dataArray | byte[] | Sebuah array byte yang berisi data rekaman. |

### getMetafileHeader() {#getMetafileHeader--}
```
public MetafileHeader getMetafileHeader()
```


Mengembalikan [MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) yang terkait dengan [Metafile](../../com.aspose.drawing.imaging/metafile) ini.

**Returns:**
[MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) - The [MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) associated with this [Metafile](../../com.aspose.drawing.imaging/metafile).
### getPropertyItem(int propid) {#getPropertyItem-int-}
```
public PropertyItem getPropertyItem(int propid)
```


Mendapatkan item properti yang ditentukan dari [Image](../../com.aspose.drawing/image).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| propid | int | ID dari item properti yang akan diambil. |

**Returns:**
[PropertyItem](../../com.aspose.drawing.imaging/propertyitem) - The [PropertyItem](../../com.aspose.drawing.imaging/propertyitem) this method gets.
### removePropertyItem(int propid) {#removePropertyItem-int-}
```
public void removePropertyItem(int propid)
```


Menghapus item properti yang ditentukan dari [Image](../../com.aspose.drawing/image).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| propid | int | ID dari item properti yang akan dihapus. |

### setPropertyItem(PropertyItem propitem) {#setPropertyItem-com.aspose.drawing.imaging.PropertyItem-}
```
public void setPropertyItem(PropertyItem propitem)
```


Menyimpan sebuah item properti (potongan metadata) dalam [Image](../../com.aspose.drawing/image).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| propitem | [PropertyItem](../../com.aspose.drawing.imaging/propertyitem) | [PropertyItem](../../com.aspose.drawing.imaging/propertyitem) yang akan disimpan. |

