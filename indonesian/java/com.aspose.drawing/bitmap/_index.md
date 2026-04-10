---
title: Bitmap
second_title: Referensi API Aspose.Drawing for Java
description: Mengkapsulkan bitmap yang terdiri dari data piksel untuk gambar grafis dan atributnya.
type: docs
weight: 10
url: /id/java/com.aspose.drawing/bitmap/
---
**Inheritance:**
java.lang.Object, [com.aspose.drawing.Image](../../com.aspose.drawing/image)
```
public class Bitmap extends Image
```

Mengkapsulkan bitmap, yang terdiri dari data piksel untuk gambar grafis dan atributnya. Sebuah [Bitmap](../../com.aspose.drawing/bitmap) adalah objek yang digunakan untuk bekerja dengan gambar yang didefinisikan oleh data piksel.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [Bitmap(int width, int height)](#Bitmap-int-int-) | Menginisialisasi instansi baru dari kelas [Bitmap](../../com.aspose.drawing/bitmap) dengan ukuran yang ditentukan. |
| [Bitmap(String filename)](#Bitmap-java.lang.String-) | Menginisialisasi instansi baru dari kelas [Bitmap](../../com.aspose.drawing/bitmap) dari file yang ditentukan. |
| [Bitmap(String filename, boolean useIcm)](#Bitmap-java.lang.String-boolean-) | Menginisialisasi instansi baru dari kelas [Bitmap](../../com.aspose.drawing/bitmap) dari file yang ditentukan. |
| [Bitmap(InputStream stream)](#Bitmap-java.io.InputStream-) | Menginisialisasi instansi baru dari kelas [Bitmap](../../com.aspose.drawing/bitmap) dari aliran data yang ditentukan. |
| [Bitmap(InputStream stream, boolean useIcm)](#Bitmap-java.io.InputStream-boolean-) | Menginisialisasi instansi baru dari kelas [Bitmap](../../com.aspose.drawing/bitmap) dari aliran data yang ditentukan. |
| [Bitmap(int width, int height, int format)](#Bitmap-int-int-int-) | Menginisialisasi instansi baru dari kelas [Bitmap](../../com.aspose.drawing/bitmap) dengan ukuran dan format yang ditentukan. |
| [Bitmap(int width, int height, int stride, int format, int[] data)](#Bitmap-int-int-int-int-int---) | Menginisialisasi instansi baru dari kelas [Bitmap](../../com.aspose.drawing/bitmap) dengan ukuran dan data piksel yang ditentukan. |
| [Bitmap(Image original)](#Bitmap-com.aspose.drawing.Image-) | Menginisialisasi instansi baru dari kelas [Bitmap](../../com.aspose.drawing/bitmap) dari gambar yang ada dan ditentukan. |
| [Bitmap(Image original, Size newSize)](#Bitmap-com.aspose.drawing.Image-com.aspose.drawing.Size-) | Menginisialisasi instansi baru dari kelas [Bitmap](../../com.aspose.drawing/bitmap) dari gambar yang ada dan ditentukan, diubah skalanya ke ukuran yang ditentukan. |
| [Bitmap(Image original, int width, int height)](#Bitmap-com.aspose.drawing.Image-int-int-) | Menginisialisasi instansi baru dari kelas [Bitmap](../../com.aspose.drawing/bitmap) dari gambar yang ada dan ditentukan, diubah skalanya ke ukuran yang ditentukan. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getWidth()](#getWidth--) | Mendapatkan lebar, dalam piksel, dari Bitmap ini. |
| [getHeight()](#getHeight--) | Mendapatkan tinggi, dalam piksel, dari Bitmap ini. |
| [getRawFormat()](#getRawFormat--) | Mendapatkan format berkas dari [Image](../../com.aspose.drawing/image). |
| [getPixelFormat()](#getPixelFormat--) | Mendapatkan format piksel untuk [Image](../../com.aspose.drawing/image). |
| [getPalette()](#getPalette--) | Mendapatkan atau mengatur palet warna yang digunakan untuk [Image](../../com.aspose.drawing/image). |
| [setPalette(ColorPalette value)](#setPalette-com.aspose.drawing.imaging.ColorPalette-) | Mendapatkan atau mengatur palet warna yang digunakan untuk [Image](../../com.aspose.drawing/image). |
| [getFrameDimensionsList()](#getFrameDimensionsList--) | Mendapatkan array GUID yang mewakili dimensi frame dalam [Image](../../com.aspose.drawing/image). |
| [getPropertyIdList()](#getPropertyIdList--) | Mendapatkan ID dari item properti yang disimpan dalam [Image](../../com.aspose.drawing/image). |
| [getPropertyItems()](#getPropertyItems--) | Mendapatkan semua item properti (potongan metadata) yang disimpan dalam [Image](../../com.aspose.drawing/image). |
| [deepClone(Rectangle rect, int format)](#deepClone-com.aspose.drawing.Rectangle-int-) | Membuat salinan bagian dari [Bitmap](../../com.aspose.drawing/bitmap) ini yang didefinisikan oleh struktur [Rectangle](../../com.aspose.drawing/rectangle) dan dengan enumerasi `PixelFormat`([Image.getPixelFormat](../../com.aspose.drawing/image\#getPixelFormat)) yang ditentukan. |
| [deepClone(RectangleF rect, int format)](#deepClone-com.aspose.drawing.RectangleF-int-) | Membuat salinan bagian dari [Bitmap](../../com.aspose.drawing/bitmap) ini yang didefinisikan dengan enumerasi [PixelFormat](../../com.aspose.drawing.imaging/pixelformat) yang ditentukan. |
| [setResolution(float xDpi, float yDpi)](#setResolution-float-float-) | Mengatur resolusi untuk [Bitmap](../../com.aspose.drawing/bitmap) ini. |
| [lockBits(Rectangle rect, int flags, int format)](#lockBits-com.aspose.drawing.Rectangle-int-int-) | Mengunci sebuah [Bitmap](../../com.aspose.drawing/bitmap) ke memori sistem. |
| [unlockBits(BitmapData bitmapData)](#unlockBits-com.aspose.drawing.imaging.BitmapData-) | Membuka kunci [Bitmap](../../com.aspose.drawing/bitmap) ini dari memori sistem. |
| [getPixel(int x, int y)](#getPixel-int-int-) | Mendapatkan warna piksel yang ditentukan dalam [Bitmap](../../com.aspose.drawing/bitmap) ini. |
| [setPixel(int x, int y, Color color)](#setPixel-int-int-com.aspose.drawing.Color-) | Mengatur warna piksel yang ditentukan dalam [Bitmap](../../com.aspose.drawing/bitmap) ini. |
| [readArgb32Pixels(int[] pixels)](#readArgb32Pixels-int---) | Membaca piksel bitmap dalam format ARGB32 ke dalam array yang diberikan. |
| [writeArgb32Pixels(int[] pixels)](#writeArgb32Pixels-int---) | Menulis piksel ke bitmap. |
| [makeTransparent()](#makeTransparent--) | Membuat warna yang ditentukan menjadi transparan untuk [Bitmap](../../com.aspose.drawing/bitmap) ini. |
| [makeTransparent(Color transparentColor)](#makeTransparent-com.aspose.drawing.Color-) | Membuat warna yang ditentukan menjadi transparan untuk [Bitmap](../../com.aspose.drawing/bitmap) ini. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | Metode ini memutar, membalik, atau memutar dan membalik [Image](../../com.aspose.drawing/image). |
| [getPropertyItem(int propid)](#getPropertyItem-int-) | Mendapatkan item properti yang ditentukan dari [Image](../../com.aspose.drawing/image). |
| [removePropertyItem(int propid)](#removePropertyItem-int-) | Menghapus item properti yang ditentukan dari [Image](../../com.aspose.drawing/image). |
| [setPropertyItem(PropertyItem propitem)](#setPropertyItem-com.aspose.drawing.imaging.PropertyItem-) | Menyimpan sebuah item properti (potongan metadata) dalam [Image](../../com.aspose.drawing/image). |
### Bitmap(int width, int height) {#Bitmap-int-int-}
```
public Bitmap(int width, int height)
```


Menginisialisasi instansi baru dari kelas [Bitmap](../../com.aspose.drawing/bitmap) dengan ukuran yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| lebar | int | Lebar, dalam piksel, dari Bitmap baru. |
|  | tinggi | int | Tinggi, dalam piksel, dari Bitmap baru. |

--------------------

Satu-satunya format bitmap internal yang didukung saat ini setara dengan `PixelFormat.Format32bppPArgb`. |

### Bitmap(String filename) {#Bitmap-java.lang.String-}
```
public Bitmap(String filename)
```


Menginisialisasi instansi baru dari kelas [Bitmap](../../com.aspose.drawing/bitmap) dari file yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nama file | java.lang.String | Nama berkas bitmap. |

### Bitmap(String filename, boolean useIcm) {#Bitmap-java.lang.String-boolean-}
```
public Bitmap(String filename, boolean useIcm)
```


Menginisialisasi instansi baru dari kelas [Bitmap](../../com.aspose.drawing/bitmap) dari file yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nama file | java.lang.String | Nama berkas bitmap. |
| useIcm | boolean | true untuk menggunakan koreksi warna pada [Bitmap](../../com.aspose.drawing/bitmap) ini; jika tidak, false. |

### Bitmap(InputStream stream) {#Bitmap-java.io.InputStream-}
```
public Bitmap(InputStream stream)
```


Menginisialisasi instansi baru dari kelas [Bitmap](../../com.aspose.drawing/bitmap) dari aliran data yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| aliran | java.io.InputStream | Aliran data yang digunakan untuk memuat gambar. |

### Bitmap(InputStream stream, boolean useIcm) {#Bitmap-java.io.InputStream-boolean-}
```
public Bitmap(InputStream stream, boolean useIcm)
```


Menginisialisasi instansi baru dari kelas [Bitmap](../../com.aspose.drawing/bitmap) dari aliran data yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| aliran | java.io.InputStream | Aliran data yang digunakan untuk memuat gambar. |
| useIcm | boolean | `true` untuk menggunakan koreksi warna pada [Bitmap](../../com.aspose.drawing/bitmap) ini; jika tidak, `false`. |

### Bitmap(int width, int height, int format) {#Bitmap-int-int-int-}
```
public Bitmap(int width, int height, int format)
```


Menginisialisasi instansi baru dari kelas [Bitmap](../../com.aspose.drawing/bitmap) dengan ukuran dan format yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| width | int | Lebar, dalam piksel, dari [Bitmap](../../com.aspose.drawing/bitmap) baru. |
| height | int | Tinggi, dalam piksel, dari [Bitmap](../../com.aspose.drawing/bitmap) baru. |
| format | int | Enumerasi `PixelFormat`([Image.getPixelFormat](../../com.aspose.drawing/image\#getPixelFormat)) untuk [Bitmap](../../com.aspose.drawing/bitmap) baru. |

### Bitmap(int width, int height, int stride, int format, int[] data) {#Bitmap-int-int-int-int-int---}
```
public Bitmap(int width, int height, int stride, int format, int[] data)
```


Menginisialisasi instansi baru dari kelas [Bitmap](../../com.aspose.drawing/bitmap) dengan ukuran dan data piksel yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| width | int | Lebar, dalam piksel, dari [Bitmap](../../com.aspose.drawing/bitmap) baru. |
| height | int | Tinggi, dalam piksel, dari [Bitmap](../../com.aspose.drawing/bitmap) baru. |
| stride | int | Offset byte antara awal satu baris pemindaian dan berikutnya, harus kelipatan empat. |
| format | int | Enumerasi `PixelFormat`([Image.getPixelFormat](../../com.aspose.drawing/image\#getPixelFormat)) untuk [Bitmap](../../com.aspose.drawing/bitmap) baru. |
| data | int[] | Data piksel. |

### Bitmap(Image original) {#Bitmap-com.aspose.drawing.Image-}
```
public Bitmap(Image original)
```


Menginisialisasi instansi baru dari kelas [Bitmap](../../com.aspose.drawing/bitmap) dari gambar yang ada dan ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| original | [Image](../../com.aspose.drawing/image) | Gambar [Image](../../com.aspose.drawing/image) yang digunakan untuk membuat [Bitmap](../../com.aspose.drawing/bitmap) baru. |

### Bitmap(Image original, Size newSize) {#Bitmap-com.aspose.drawing.Image-com.aspose.drawing.Size-}
```
public Bitmap(Image original, Size newSize)
```


Menginisialisasi instansi baru dari kelas [Bitmap](../../com.aspose.drawing/bitmap) dari gambar yang ada dan ditentukan, diubah skalanya ke ukuran yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| original | [Image](../../com.aspose.drawing/image) | Gambar [Image](../../com.aspose.drawing/image) yang digunakan untuk membuat [Bitmap](../../com.aspose.drawing/bitmap) baru. |
| newSize | [Size](../../com.aspose.drawing/size) | Struktur `Size`([Image.getSize](../../com.aspose.drawing/image\#getSize)) yang mewakili ukuran [Bitmap](../../com.aspose.drawing/bitmap) baru. |

### Bitmap(Image original, int width, int height) {#Bitmap-com.aspose.drawing.Image-int-int-}
```
public Bitmap(Image original, int width, int height)
```


Menginisialisasi instansi baru dari kelas [Bitmap](../../com.aspose.drawing/bitmap) dari gambar yang ada dan ditentukan, diubah skalanya ke ukuran yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| original | [Image](../../com.aspose.drawing/image) | Gambar [Image](../../com.aspose.drawing/image) yang digunakan untuk membuat [Bitmap](../../com.aspose.drawing/bitmap) baru. |
| width | int | Lebar, dalam piksel, dari [Bitmap](../../com.aspose.drawing/bitmap) baru. |
| height | int | Tinggi, dalam piksel, dari [Bitmap](../../com.aspose.drawing/bitmap) baru. |

### getWidth() {#getWidth--}
```
public int getWidth()
```


Mendapatkan lebar, dalam piksel, dari Bitmap ini.

**Returns:**
int
### getHeight() {#getHeight--}
```
public int getHeight()
```


Mendapatkan tinggi, dalam piksel, dari Bitmap ini.

**Returns:**
int
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
### deepClone(Rectangle rect, int format) {#deepClone-com.aspose.drawing.Rectangle-int-}
```
public final Bitmap deepClone(Rectangle rect, int format)
```


Membuat salinan bagian dari [Bitmap](../../com.aspose.drawing/bitmap) ini yang didefinisikan oleh struktur [Rectangle](../../com.aspose.drawing/rectangle) dan dengan enumerasi `PixelFormat`([Image.getPixelFormat](../../com.aspose.drawing/image\#getPixelFormat)) yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | Mendefinisikan bagian dari [Bitmap](../../com.aspose.drawing/bitmap) ini yang akan disalin. Koordinat relatif terhadap [Bitmap](../../com.aspose.drawing/bitmap) ini. |
| format | int | Menentukan enumerasi `PixelFormat`([Image.getPixelFormat](../../com.aspose.drawing/image\#getPixelFormat)) untuk [Bitmap](../../com.aspose.drawing/bitmap) tujuan. |

**Returns:**
[Bitmap](../../com.aspose.drawing/bitmap) - The new [Bitmap](../../com.aspose.drawing/bitmap) that this method creates.
### deepClone(RectangleF rect, int format) {#deepClone-com.aspose.drawing.RectangleF-int-}
```
public final Bitmap deepClone(RectangleF rect, int format)
```


Membuat salinan bagian dari [Bitmap](../../com.aspose.drawing/bitmap) ini yang didefinisikan dengan enumerasi [PixelFormat](../../com.aspose.drawing.imaging/pixelformat) yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | Mendefinisikan bagian dari [Bitmap](../../com.aspose.drawing/bitmap) ini yang akan disalin. |
| format | int | Menentukan enumerasi [PixelFormat](../../com.aspose.drawing.imaging/pixelformat) untuk [Bitmap](../../com.aspose.drawing/bitmap) tujuan. |

**Returns:**
[Bitmap](../../com.aspose.drawing/bitmap) - The [Bitmap](../../com.aspose.drawing/bitmap) that this method creates.
### setResolution(float xDpi, float yDpi) {#setResolution-float-float-}
```
public final void setResolution(float xDpi, float yDpi)
```


Mengatur resolusi untuk [Bitmap](../../com.aspose.drawing/bitmap) ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| xDpi | float | Resolusi horizontal, dalam dot per inci, dari [Bitmap](../../com.aspose.drawing/bitmap). |
| yDpi | float | Resolusi vertikal, dalam dot per inci, dari [Bitmap](../../com.aspose.drawing/bitmap). |

### lockBits(Rectangle rect, int flags, int format) {#lockBits-com.aspose.drawing.Rectangle-int-int-}
```
public final BitmapData lockBits(Rectangle rect, int flags, int format)
```


Mengunci sebuah [Bitmap](../../com.aspose.drawing/bitmap) ke memori sistem.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | Sebuah struktur [Rectangle](../../com.aspose.drawing/rectangle) yang menentukan bagian dari [Bitmap](../../com.aspose.drawing/bitmap) yang akan dikunci. |
| flags | int | Enumerasi [ImageLockMode](../../com.aspose.drawing.imaging/imagelockmode) yang menentukan tingkat akses (baca/tulis) untuk [Bitmap](../../com.aspose.drawing/bitmap). |
| format | int | Enumerasi `PixelFormat`([Image.getPixelFormat](../../com.aspose.drawing/image\#getPixelFormat)) yang menentukan format data [Bitmap](../../com.aspose.drawing/bitmap) ini. |

**Returns:**
[BitmapData](../../com.aspose.drawing.imaging/bitmapdata) - A [BitmapData](../../com.aspose.drawing.imaging/bitmapdata) containing information about this lock operation.
### unlockBits(BitmapData bitmapData) {#unlockBits-com.aspose.drawing.imaging.BitmapData-}
```
public final void unlockBits(BitmapData bitmapData)
```


Membuka kunci [Bitmap](../../com.aspose.drawing/bitmap) ini dari memori sistem.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| bitmapData | [BitmapData](../../com.aspose.drawing.imaging/bitmapdata) | [BitmapData](../../com.aspose.drawing.imaging/bitmapdata) yang memberikan informasi tentang operasi penguncian. |

### getPixel(int x, int y) {#getPixel-int-int-}
```
public final Color getPixel(int x, int y)
```


Mendapatkan warna piksel yang ditentukan dalam [Bitmap](../../com.aspose.drawing/bitmap) ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | int | Koordinat x piksel yang akan diambil. |
| y | int | Koordinat y piksel yang akan diambil. |

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) structure that represents the color of the specified pixel.
### setPixel(int x, int y, Color color) {#setPixel-int-int-com.aspose.drawing.Color-}
```
public final void setPixel(int x, int y, Color color)
```


Mengatur warna piksel yang ditentukan dalam [Bitmap](../../com.aspose.drawing/bitmap) ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | int | Koordinat x piksel yang akan diatur. |
| y | int | Koordinat y piksel yang akan diatur. |
| color | [Color](../../com.aspose.drawing/color) | Struktur [Color](../../com.aspose.drawing/color) yang mewakili warna yang akan diberikan ke piksel yang ditentukan. |

### readArgb32Pixels(int[] pixels) {#readArgb32Pixels-int---}
```
public final void readArgb32Pixels(int[] pixels)
```


Membaca piksel bitmap dalam format ARGB32 ke dalam array yang diberikan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| piksel | int[] | Array untuk menempatkan piksel bitmap. Harus memiliki kapasitas yang cukup. |

### writeArgb32Pixels(int[] pixels) {#writeArgb32Pixels-int---}
```
public final void writeArgb32Pixels(int[] pixels)
```


Menulis piksel ke bitmap.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| piksel | int[] | Array dengan piksel sumber dalam format ARGB32. Harus memiliki panjang yang cukup. |

### makeTransparent() {#makeTransparent--}
```
public final void makeTransparent()
```


Membuat warna yang ditentukan menjadi transparan untuk [Bitmap](../../com.aspose.drawing/bitmap) ini.

### makeTransparent(Color transparentColor) {#makeTransparent-com.aspose.drawing.Color-}
```
public final void makeTransparent(Color transparentColor)
```


Membuat warna yang ditentukan menjadi transparan untuk [Bitmap](../../com.aspose.drawing/bitmap) ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| transparentColor | [Color](../../com.aspose.drawing/color) | Struktur [Color](../../com.aspose.drawing/color) yang mewakili warna yang akan dibuat transparan. |

### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


Metode ini memutar, membalik, atau memutar dan membalik [Image](../../com.aspose.drawing/image).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rotateFlipType | int | Anggota [RotateFlipType](../../com.aspose.drawing/rotatefliptype) yang menentukan jenis rotasi dan flip yang akan diterapkan pada gambar. |

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

