---
title: BitmapData
second_title: Referensi API Aspose.Drawing for Java
description: Menentukan atribut gambar bitmap.
type: docs
weight: 10
url: /id/java/com.aspose.drawing.imaging/bitmapdata/
---
**Inheritance:**
java.lang.Object
```
public final class BitmapData
```

Menentukan atribut gambar bitmap. Kelas [BitmapData](../../com.aspose.drawing.imaging/bitmapdata) digunakan oleh metode `E:Bitmap.LockBits` dan `M:Bitmap.UnlockBits(BitmapData)` dari kelas [Bitmap](../../com.aspose.drawing/bitmap). Tidak dapat diwariskan.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [BitmapData()](#BitmapData--) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getWidth()](#getWidth--) | Mendapatkan lebar piksel dari objek [Bitmap](../../com.aspose.drawing/bitmap). |
| [setWidth(int value)](#setWidth-int-) | Mengatur lebar piksel dari objek [Bitmap](../../com.aspose.drawing/bitmap). |
| [getHeight()](#getHeight--) | Mendapatkan tinggi piksel dari objek [Bitmap](../../com.aspose.drawing/bitmap). |
| [setHeight(int value)](#setHeight-int-) | Mengatur tinggi piksel dari objek [Bitmap](../../com.aspose.drawing/bitmap). |
| [getStride()](#getStride--) | Mendapatkan lebar stride (juga disebut lebar scan) dari objek [Bitmap](../../com.aspose.drawing/bitmap). |
| [setStride(int value)](#setStride-int-) | Mengatur lebar stride (juga disebut lebar scan) dari objek [Bitmap](../../com.aspose.drawing/bitmap). |
| [getPixelFormat()](#getPixelFormat--) | Mendapatkan format informasi piksel dalam objek [Bitmap](../../com.aspose.drawing/bitmap) yang mengembalikan objek [BitmapData](../../com.aspose.drawing.imaging/bitmapdata) ini. |
| [setPixelFormat(int value)](#setPixelFormat-int-) | Mengatur format informasi piksel dalam objek [Bitmap](../../com.aspose.drawing/bitmap) yang mengembalikan objek [BitmapData](../../com.aspose.drawing.imaging/bitmapdata) ini. |
| [getScan0()](#getScan0--) | Mendapatkan alamat data piksel pertama dalam bitmap. |
| [setScan0(int[] value)](#setScan0-int---) | Mengatur alamat data piksel pertama dalam bitmap. |
### BitmapData() {#BitmapData--}
```
public BitmapData()
```


### getWidth() {#getWidth--}
```
public int getWidth()
```


Mendapatkan lebar piksel dari objek [Bitmap](../../com.aspose.drawing/bitmap). Ini juga dapat dianggap sebagai jumlah piksel dalam satu baris scan.

**Returns:**
int - Lebar piksel dari objek [Bitmap](../../com.aspose.drawing/bitmap).
### setWidth(int value) {#setWidth-int-}
```
public void setWidth(int value)
```


Mengatur lebar piksel dari objek [Bitmap](../../com.aspose.drawing/bitmap). Ini juga dapat dianggap sebagai jumlah piksel dalam satu baris pemindaian.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int | lebar piksel dari objek [Bitmap](../../com.aspose.drawing/bitmap). |

### getHeight() {#getHeight--}
```
public int getHeight()
```


Mendapatkan tinggi piksel dari objek [Bitmap](../../com.aspose.drawing/bitmap). Juga kadang disebut sebagai jumlah baris pemindaian.

**Returns:**
int - Tinggi piksel dari objek [Bitmap](../../com.aspose.drawing/bitmap).
### setHeight(int value) {#setHeight-int-}
```
public void setHeight(int value)
```


Mengatur tinggi piksel dari objek [Bitmap](../../com.aspose.drawing/bitmap). Juga kadang disebut sebagai jumlah baris pemindaian.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int | tinggi piksel dari objek [Bitmap](../../com.aspose.drawing/bitmap). |

### getStride() {#getStride--}
```
public int getStride()
```


Mendapatkan lebar stride (juga disebut lebar scan) dari objek [Bitmap](../../com.aspose.drawing/bitmap).

**Returns:**
int - Lebar stride, dalam byte, dari objek [Bitmap](../../com.aspose.drawing/bitmap).
### setStride(int value) {#setStride-int-}
```
public void setStride(int value)
```


Mengatur lebar stride (juga disebut lebar scan) dari objek [Bitmap](../../com.aspose.drawing/bitmap).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int | lebar stride (juga disebut lebar pemindaian) dari objek [Bitmap](../../com.aspose.drawing/bitmap). |

### getPixelFormat() {#getPixelFormat--}
```
public int getPixelFormat()
```


Mendapatkan format informasi piksel dalam objek [Bitmap](../../com.aspose.drawing/bitmap) yang mengembalikan objek [BitmapData](../../com.aspose.drawing.imaging/bitmapdata) ini.

**Returns:**
int - Sebuah `PixelFormat`([.getPixelFormat](../../null/\#getPixelFormat)/[.setPixelFormat(int)](../../null/\#setPixelFormat-int-)) yang menentukan format informasi piksel dalam objek [Bitmap](../../com.aspose.drawing/bitmap) yang terkait.
### setPixelFormat(int value) {#setPixelFormat-int-}
```
public void setPixelFormat(int value)
```


Mengatur format informasi piksel dalam objek [Bitmap](../../com.aspose.drawing/bitmap) yang mengembalikan objek [BitmapData](../../com.aspose.drawing.imaging/bitmapdata) ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int | format informasi piksel dalam objek [Bitmap](../../com.aspose.drawing/bitmap) yang mengembalikan objek [BitmapData](../../com.aspose.drawing.imaging/bitmapdata) ini. |

### getScan0() {#getScan0--}
```
public int[] getScan0()
```


Mendapatkan alamat data piksel pertama dalam bitmap. Ini juga dapat dianggap sebagai baris pemindaian pertama dalam bitmap.

**Returns:**
int[] - Alamat data piksel pertama dalam bitmap.
### setScan0(int[] value) {#setScan0-int---}
```
public void setScan0(int[] value)
```


Mengatur alamat data piksel pertama dalam bitmap. Ini juga dapat dianggap sebagai baris pemindaian pertama dalam bitmap.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int[] | alamat data piksel pertama dalam bitmap. |

