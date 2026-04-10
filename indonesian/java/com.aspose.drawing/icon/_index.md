---
title: Icon
second_title: Referensi API Aspose.Drawing for Java
description: Mewakili ikon Windows yang merupakan gambar bitmap kecil yang digunakan untuk mewakili sebuah objek.
type: docs
weight: 29
url: /id/java/com.aspose.drawing/icon/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.ms.System.IDisposable
```
public final class Icon implements System.ICloneable, System.IDisposable
```

Mewakili ikon Windows, yang merupakan gambar bitmap kecil yang digunakan untuk mewakili sebuah objek. Ikon dapat dianggap sebagai bitmap transparan, meskipun ukurannya ditentukan oleh sistem.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [Icon(String fileName)](#Icon-java.lang.String-) | Menginisialisasi instance baru dari kelas [Icon](../../com.aspose.drawing/icon) dari nama file yang ditentukan. |
| [Icon(InputStream stream)](#Icon-java.io.InputStream-) | Menginisialisasi instance baru dari kelas [Icon](../../com.aspose.drawing/icon) dari aliran data yang ditentukan. |
| [Icon(String fileName, Size size)](#Icon-java.lang.String-com.aspose.drawing.Size-) | Menginisialisasi instance baru dari kelas [Icon](../../com.aspose.drawing/icon) dengan ukuran yang ditentukan dari file yang ditentukan. |
| [Icon(Icon original, Size size)](#Icon-com.aspose.drawing.Icon-com.aspose.drawing.Size-) | Menginisialisasi instance baru dari kelas [Icon](../../com.aspose.drawing/icon) dan mencoba menemukan versi ikon yang sesuai dengan ukuran yang diminta. |
| [Icon(Object type, String resource)](#Icon-java.lang.Object-java.lang.String-) | Menginisialisasi instance baru dari kelas [Icon](../../com.aspose.drawing/icon) dari sumber daya dalam assembly yang ditentukan. |
| [Icon(InputStream stream, Size size)](#Icon-java.io.InputStream-com.aspose.drawing.Size-) | Menginisialisasi instance baru dari kelas [Icon](../../com.aspose.drawing/icon) dengan ukuran yang ditentukan dari aliran yang ditentukan. |
| [Icon(String fileName, int width, int height)](#Icon-java.lang.String-int-int-) | Menginisialisasi instance baru dari kelas [Icon](../../com.aspose.drawing/icon) dengan lebar dan tinggi yang ditentukan dari file yang ditentukan. |
| [Icon(Icon original, int width, int height)](#Icon-com.aspose.drawing.Icon-int-int-) | Menginisialisasi instance baru dari kelas [Icon](../../com.aspose.drawing/icon) dan berusaha menemukan versi ikon yang cocok dengan ukuran yang diminta.. |
| [Icon(InputStream stream, int width, int height)](#Icon-java.io.InputStream-int-int-) | Menginisialisasi instance baru dari kelas [Icon](../../com.aspose.drawing/icon) dari aliran data yang ditentukan dan dengan lebar serta tinggi yang ditentukan. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getHandle()](#getHandle--) | Mendapatkan handle untuk [Icon](../../com.aspose.drawing/icon) ini. |
| [getHeight()](#getHeight--) | Mendapatkan tinggi dari [Icon](../../com.aspose.drawing/icon) ini. |
| [getSize()](#getSize--) | Mendapatkan ukuran dari [Icon](../../com.aspose.drawing/icon) ini. |
| [getWidth()](#getWidth--) | Mendapatkan lebar dari [Icon](../../com.aspose.drawing/icon) ini. |
| [extractAssociatedIcon(String filePath)](#extractAssociatedIcon-java.lang.String-) | Mengembalikan representasi ikon dari gambar yang terdapat dalam file yang ditentukan. |
| [fromHandle(byte[] handle)](#fromHandle-byte---) | Membuat [Icon](../../com.aspose.drawing/icon) GDI+ dari handle Windows yang ditentukan ke sebuah ikon (HICON). |
| [deepClone()](#deepClone--) | Mengkloning [Icon](../../com.aspose.drawing/icon), membuat gambar duplikat. |
| [dispose()](#dispose--) | Melakukan tugas yang ditentukan aplikasi terkait dengan membebaskan, melepaskan, atau mereset sumber daya yang tidak dikelola. |
| [save(OutputStream outputStream)](#save-java.io.OutputStream-) | Menyimpan [Icon](../../com.aspose.drawing/icon) ini ke java.io.InputStream keluaran yang ditentukan. |
| [toBitmap()](#toBitmap--) | Mengonversi [Icon](../../com.aspose.drawing/icon) ini ke [Bitmap](../../com.aspose.drawing/bitmap) GDI+. |
| [toString()](#toString--) | Mendapatkan string yang dapat dibaca manusia yang menjelaskan [Icon](../../com.aspose.drawing/icon). |
### Icon(String fileName) {#Icon-java.lang.String-}
```
public Icon(String fileName)
```


Menginisialisasi instance baru dari kelas [Icon](../../com.aspose.drawing/icon) dari nama file yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fileName | java.lang.String | File untuk memuat [Icon](../../com.aspose.drawing/icon) dari. |

### Icon(InputStream stream) {#Icon-java.io.InputStream-}
```
public Icon(InputStream stream)
```


Menginisialisasi instance baru dari kelas [Icon](../../com.aspose.drawing/icon) dari aliran data yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | java.io.InputStream | Aliran data dari mana memuat [Icon](../../com.aspose.drawing/icon). |

### Icon(String fileName, Size size) {#Icon-java.lang.String-com.aspose.drawing.Size-}
```
public Icon(String fileName, Size size)
```


Menginisialisasi instance baru dari kelas [Icon](../../com.aspose.drawing/icon) dengan ukuran yang ditentukan dari file yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fileName | java.lang.String | Nama dan jalur ke file yang berisi data ikon. |
| size | [Size](../../com.aspose.drawing/size) | Ukuran yang diinginkan untuk ikon. |

### Icon(Icon original, Size size) {#Icon-com.aspose.drawing.Icon-com.aspose.drawing.Size-}
```
public Icon(Icon original, Size size)
```


Menginisialisasi instance baru dari kelas [Icon](../../com.aspose.drawing/icon) dan mencoba menemukan versi ikon yang sesuai dengan ukuran yang diminta.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| original | [Icon](../../com.aspose.drawing/icon) | [Icon](../../com.aspose.drawing/icon) yang akan dimuat ikon berukuran baru. |
| size | [Size](../../com.aspose.drawing/size) | Struktur `Size`([.getSize](../../null/\#getSize)) yang menentukan tinggi dan lebar dari [Icon](../../com.aspose.drawing/icon) baru. |

### Icon(Object type, String resource) {#Icon-java.lang.Object-java.lang.String-}
```
public Icon(Object type, String resource)
```


Menginisialisasi instance baru dari kelas [Icon](../../com.aspose.drawing/icon) dari sumber daya dalam assembly yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| tipe | java.lang.Object | Tipe yang menentukan assembly tempat mencari sumber daya. |
| sumber daya | java.lang.String | Nama sumber daya yang akan dimuat. |

### Icon(InputStream stream, Size size) {#Icon-java.io.InputStream-com.aspose.drawing.Size-}
```
public Icon(InputStream stream, Size size)
```


Menginisialisasi instance baru dari kelas [Icon](../../com.aspose.drawing/icon) dengan ukuran yang ditentukan dari aliran yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| aliran | java.io.InputStream | Aliran yang berisi data ikon. |
| size | [Size](../../com.aspose.drawing/size) | Ukuran yang diinginkan untuk ikon. |

### Icon(String fileName, int width, int height) {#Icon-java.lang.String-int-int-}
```
public Icon(String fileName, int width, int height)
```


Menginisialisasi instance baru dari kelas [Icon](../../com.aspose.drawing/icon) dengan lebar dan tinggi yang ditentukan dari file yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fileName | java.lang.String | Nama dan jalur ke file yang berisi data [Icon](../../com.aspose.drawing/icon). |
| width | int | Lebar yang diinginkan untuk [Icon](../../com.aspose.drawing/icon). |
| height | int | Tinggi yang diinginkan dari [Icon](../../com.aspose.drawing/icon). |

### Icon(Icon original, int width, int height) {#Icon-com.aspose.drawing.Icon-int-int-}
```
public Icon(Icon original, int width, int height)
```


Menginisialisasi instance baru dari kelas [Icon](../../com.aspose.drawing/icon) dan berusaha menemukan versi ikon yang cocok dengan ukuran yang diminta..

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| original | [Icon](../../com.aspose.drawing/icon) | Ikon untuk memuat ukuran yang berbeda. |
| lebar | int | Lebar ikon baru. |
| tinggi | int | Tinggi ikon baru. |

### Icon(InputStream stream, int width, int height) {#Icon-java.io.InputStream-int-int-}
```
public Icon(InputStream stream, int width, int height)
```


Menginisialisasi instance baru dari kelas [Icon](../../com.aspose.drawing/icon) dari aliran data yang ditentukan dan dengan lebar serta tinggi yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| aliran | java.io.InputStream | Aliran data yang digunakan untuk memuat ikon. |
| lebar | int | Lebar, dalam piksel, dari ikon. |
| tinggi | int | Tinggi, dalam piksel, dari ikon. |

### getHandle() {#getHandle--}
```
public System.IntPtr getHandle()
```


Mendapatkan handle untuk [Icon](../../com.aspose.drawing/icon) ini. Ini bukan salinan handle; jangan membebaskannya.

Nilai: Handle Windows untuk ikon.

**Returns:**
com.aspose.ms.System.IntPtr
### getHeight() {#getHeight--}
```
public int getHeight()
```


Mendapatkan tinggi dari [Icon](../../com.aspose.drawing/icon) ini.

Nilai: Tinggi [Icon](../../com.aspose.drawing/icon) ini.

**Returns:**
int
### getSize() {#getSize--}
```
public Size getSize()
```


Mendapatkan ukuran dari [Icon](../../com.aspose.drawing/icon) ini.

Nilai: Struktur `Size`([.getSize](../../null/\#getSize)) yang menentukan lebar dan tinggi [Icon](../../com.aspose.drawing/icon) ini.

**Returns:**
[Size](../../com.aspose.drawing/size)
### getWidth() {#getWidth--}
```
public int getWidth()
```


Mendapatkan lebar dari [Icon](../../com.aspose.drawing/icon) ini.

Nilai: Lebar [Icon](../../com.aspose.drawing/icon) ini.

**Returns:**
int
### extractAssociatedIcon(String filePath) {#extractAssociatedIcon-java.lang.String-}
```
public static Icon extractAssociatedIcon(String filePath)
```


Mengembalikan representasi ikon dari gambar yang terdapat dalam file yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filePath | java.lang.String | Jalur ke file yang berisi gambar. |

**Returns:**
[Icon](../../com.aspose.drawing/icon) - The [Icon](../../com.aspose.drawing/icon) representation of the image that is contained in the specified file.
### fromHandle(byte[] handle) {#fromHandle-byte---}
```
public static Icon fromHandle(byte[] handle)
```


Membuat [Icon](../../com.aspose.drawing/icon) GDI+ dari handle Windows yang ditentukan ke sebuah ikon (HICON).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| handle | byte[] | Handle Windows ke sebuah ikon. |

**Returns:**
[Icon](../../com.aspose.drawing/icon) - The [Icon](../../com.aspose.drawing/icon) this method creates.
### deepClone() {#deepClone--}
```
public Object deepClone()
```


Mengkloning [Icon](../../com.aspose.drawing/icon), membuat gambar duplikat.

**Returns:**
java.lang.Object - Objek yang dapat di-cast menjadi [Icon](../../com.aspose.drawing/icon).
### dispose() {#dispose--}
```
public void dispose()
```


Melakukan tugas yang ditentukan aplikasi terkait dengan membebaskan, melepaskan, atau mereset sumber daya yang tidak dikelola.

### save(OutputStream outputStream) {#save-java.io.OutputStream-}
```
public void save(OutputStream outputStream)
```


Menyimpan [Icon](../../com.aspose.drawing/icon) ini ke java.io.InputStream keluaran yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| outputStream | java.io.OutputStream | java.io.InputStream untuk disimpan ke. |

### toBitmap() {#toBitmap--}
```
public Bitmap toBitmap()
```


Mengonversi [Icon](../../com.aspose.drawing/icon) ini ke [Bitmap](../../com.aspose.drawing/bitmap) GDI+.

**Returns:**
[Bitmap](../../com.aspose.drawing/bitmap) - A [Bitmap](../../com.aspose.drawing/bitmap) that represents the converted [Icon](../../com.aspose.drawing/icon).
### toString() {#toString--}
```
public String toString()
```


Mendapatkan string yang dapat dibaca manusia yang menjelaskan [Icon](../../com.aspose.drawing/icon).

**Returns:**
java.lang.String - String yang menggambarkan [Icon](../../com.aspose.drawing/icon).
