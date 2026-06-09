---
title: TextureBrush
second_title: Referensi API Aspose.Drawing for Java
description: Setiap properti dari kelas TextureBrush adalah objek Brush yang menggunakan gambar untuk mengisi interior sebuah bentuk.
type: docs
weight: 53
url: /id/java/com.aspose.drawing/texturebrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.drawing.Brush](../../com.aspose.drawing/brush)
```
public final class TextureBrush extends Brush
```

Setiap properti dari kelas TextureBrush adalah objek Brush yang menggunakan gambar untuk mengisi interior sebuah bentuk. Kelas ini tidak dapat diwariskan.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [TextureBrush(Image bitmap)](#TextureBrush-com.aspose.drawing.Image-) | Menginisialisasi instance baru dari kelas [TextureBrush](../../com.aspose.drawing/texturebrush) yang menggunakan gambar yang ditentukan. |
| [TextureBrush(Image image, int wrapMode)](#TextureBrush-com.aspose.drawing.Image-int-) | Menginisialisasi instance baru dari kelas [TextureBrush](../../com.aspose.drawing/texturebrush) yang menggunakan gambar dan mode pembungkus yang ditentukan. |
| [TextureBrush(Image image, int wrapMode, RectangleF dstRect)](#TextureBrush-com.aspose.drawing.Image-int-com.aspose.drawing.RectangleF-) | Menginisialisasi instance baru dari kelas [TextureBrush](../../com.aspose.drawing/texturebrush) yang menggunakan gambar, mode pembungkus, dan persegi panjang pembatas yang ditentukan. |
| [TextureBrush(Image image, RectangleF dstRect)](#TextureBrush-com.aspose.drawing.Image-com.aspose.drawing.RectangleF-) | Menginisialisasi sebuah instance baru dari kelas [TextureBrush](../../com.aspose.drawing/texturebrush) yang menggunakan gambar yang ditentukan, dan persegi panjang pembatas. |
| [TextureBrush(Image image, RectangleF dstRect, ImageAttributes imageAttr)](#TextureBrush-com.aspose.drawing.Image-com.aspose.drawing.RectangleF-com.aspose.drawing.imaging.ImageAttributes-) | Menginisialisasi sebuah instance baru dari kelas [TextureBrush](../../com.aspose.drawing/texturebrush) yang menggunakan gambar yang ditentukan, persegi panjang pembatas, dan atribut gambar. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getImage()](#getImage--) | Mendapatkan objek Image yang terkait dengan objek TextureBrush ini. |
| [getTransform()](#getTransform--) | Mendapatkan salinan objek Matrix yang mendefinisikan transformasi geometris lokal untuk gambar yang terkait dengan objek TextureBrush ini. |
| [setTransform(Matrix value)](#setTransform-com.aspose.drawing.drawing2d.Matrix-) | Menetapkan salinan objek Matrix yang mendefinisikan transformasi geometris lokal untuk gambar yang terkait dengan objek TextureBrush ini. |
| [getWrapMode()](#getWrapMode--) | Mendapatkan enumerasi WrapMode yang menunjukkan mode pembungkus untuk objek TextureBrush ini. |
| [setWrapMode(int value)](#setWrapMode-int-) | Menetapkan enumerasi WrapMode yang menunjukkan mode pembungkus untuk objek TextureBrush ini. |
| [deepClone()](#deepClone--) | Membuat salinan persis dari objek [TextureBrush](../../com.aspose.drawing/texturebrush) ini. |
| [resetTransform()](#resetTransform--) | Mengatur ulang properti Transform dari objek [TextureBrush](../../com.aspose.drawing/texturebrush) ini ke identitas. |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-) | Mengalikan objek [Matrix](../../com.aspose.drawing.drawing2d/matrix) yang merepresentasikan transformasi geometris lokal dari objek [TextureBrush](../../com.aspose.drawing/texturebrush) ini dengan objek [Matrix](../../com.aspose.drawing.drawing2d/matrix) yang ditentukan dengan menambahkan objek [Matrix](../../com.aspose.drawing.drawing2d/matrix) yang ditentukan di depan. |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-int-) | Mengalikan objek [Matrix](../../com.aspose.drawing.drawing2d/matrix) yang merepresentasikan transformasi geometris lokal dari objek [TextureBrush](../../com.aspose.drawing/texturebrush) ini dengan objek [Matrix](../../com.aspose.drawing.drawing2d/matrix) yang ditentukan dalam urutan yang ditentukan. |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | Mentranslasi transformasi geometris lokal dari objek [TextureBrush](../../com.aspose.drawing/texturebrush) ini dengan dimensi yang ditentukan. |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | Mentranslasi transformasi geometris lokal dari objek [TextureBrush](../../com.aspose.drawing/texturebrush) ini dengan dimensi yang ditentukan dalam urutan yang ditentukan. |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | Menskalakan transformasi geometris lokal dari objek [TextureBrush](../../com.aspose.drawing/texturebrush) ini dengan jumlah yang ditentukan. |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | Menskalakan transformasi geometris lokal dari objek [TextureBrush](../../com.aspose.drawing/texturebrush) ini dengan jumlah yang ditentukan dalam urutan yang ditentukan. |
| [rotateTransform(float angle)](#rotateTransform-float-) | Memutar transformasi geometris lokal dari objek [TextureBrush](../../com.aspose.drawing/texturebrush) ini dengan jumlah yang ditentukan. |
| [rotateTransform(float angle, int order)](#rotateTransform-float-int-) | Memutar transformasi geometris lokal dari objek [TextureBrush](../../com.aspose.drawing/texturebrush) ini dengan jumlah yang ditentukan dalam urutan yang ditentukan. |
### TextureBrush(Image bitmap) {#TextureBrush-com.aspose.drawing.Image-}
```
public TextureBrush(Image bitmap)
```


Menginisialisasi instance baru dari kelas [TextureBrush](../../com.aspose.drawing/texturebrush) yang menggunakan gambar yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| bitmap | [Image](../../com.aspose.drawing/image) | Objek `Image`([.getImage](../../null/\#getImage)) yang digunakan oleh objek [TextureBrush](../../com.aspose.drawing/texturebrush) ini untuk mengisi interior. |

### TextureBrush(Image image, int wrapMode) {#TextureBrush-com.aspose.drawing.Image-int-}
```
public TextureBrush(Image image, int wrapMode)
```


Menginisialisasi instance baru dari kelas [TextureBrush](../../com.aspose.drawing/texturebrush) yang menggunakan gambar dan mode pembungkus yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| image | [Image](../../com.aspose.drawing/image) | Gambar. |
| wrapMode | int | Sebuah enumerasi `WrapMode`([.getWrapMode](../../null/\#getWrapMode)/[.setWrapMode(int)](../../null/\#setWrapMode-int-)) yang menentukan bagaimana objek [TextureBrush](../../com.aspose.drawing/texturebrush) ini ditata ubin. |

### TextureBrush(Image image, int wrapMode, RectangleF dstRect) {#TextureBrush-com.aspose.drawing.Image-int-com.aspose.drawing.RectangleF-}
```
public TextureBrush(Image image, int wrapMode, RectangleF dstRect)
```


Menginisialisasi instance baru dari kelas [TextureBrush](../../com.aspose.drawing/texturebrush) yang menggunakan gambar, mode pembungkus, dan persegi panjang pembatas yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| image | [Image](../../com.aspose.drawing/image) | Gambar. |
| wrapMode | int | Sebuah enumerasi `WrapMode`([.getWrapMode](../../null/\#getWrapMode)/[.setWrapMode(int)](../../null/\#setWrapMode-int-)) yang menentukan bagaimana objek [TextureBrush](../../com.aspose.drawing/texturebrush) ini ditata ubin. |
| dstRect | [RectangleF](../../com.aspose.drawing/rectanglef) | Sebuah struktur [RectangleF](../../com.aspose.drawing/rectanglef) yang merepresentasikan persegi panjang pembatas untuk objek [TextureBrush](../../com.aspose.drawing/texturebrush) ini. |

### TextureBrush(Image image, RectangleF dstRect) {#TextureBrush-com.aspose.drawing.Image-com.aspose.drawing.RectangleF-}
```
public TextureBrush(Image image, RectangleF dstRect)
```


Menginisialisasi sebuah instance baru dari kelas [TextureBrush](../../com.aspose.drawing/texturebrush) yang menggunakan gambar yang ditentukan, dan persegi panjang pembatas.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| image | [Image](../../com.aspose.drawing/image) | Objek `Image`([.getImage](../../null/\#getImage)) yang digunakan oleh objek [TextureBrush](../../com.aspose.drawing/texturebrush) ini untuk mengisi interior. |
| dstRect | [RectangleF](../../com.aspose.drawing/rectanglef) | Sebuah struktur [RectangleF](../../com.aspose.drawing/rectanglef) yang merepresentasikan persegi panjang pembatas untuk objek [TextureBrush](../../com.aspose.drawing/texturebrush) ini. |

### TextureBrush(Image image, RectangleF dstRect, ImageAttributes imageAttr) {#TextureBrush-com.aspose.drawing.Image-com.aspose.drawing.RectangleF-com.aspose.drawing.imaging.ImageAttributes-}
```
public TextureBrush(Image image, RectangleF dstRect, ImageAttributes imageAttr)
```


Menginisialisasi sebuah instance baru dari kelas [TextureBrush](../../com.aspose.drawing/texturebrush) yang menggunakan gambar yang ditentukan, persegi panjang pembatas, dan atribut gambar.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| image | [Image](../../com.aspose.drawing/image) | Objek Image yang digunakan oleh objek TextureBrush ini untuk mengisi interior. |
| dstRect | [RectangleF](../../com.aspose.drawing/rectanglef) | Sebuah struktur RectangleF yang merepresentasikan persegi panjang pembatas untuk objek TextureBrush ini. |
| imageAttr | [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes) | Objek ImageAttributes yang berisi informasi tambahan tentang gambar yang digunakan oleh objek TextureBrush ini. |

### getImage() {#getImage--}
```
public Image getImage()
```


Mendapatkan objek Image yang terkait dengan objek TextureBrush ini.

**Returns:**
[Image](../../com.aspose.drawing/image) - the Image object associated with this TextureBrush object.
### getTransform() {#getTransform--}
```
public Matrix getTransform()
```


Mendapatkan salinan objek Matrix yang mendefinisikan transformasi geometris lokal untuk gambar yang terkait dengan objek TextureBrush ini.

**Returns:**
[Matrix](../../com.aspose.drawing.drawing2d/matrix) - a copy of the Matrix object that defines a local geometric transformation for the image associated with this TextureBrush object.
### setTransform(Matrix value) {#setTransform-com.aspose.drawing.drawing2d.Matrix-}
```
public void setTransform(Matrix value)
```


Menetapkan salinan objek Matrix yang mendefinisikan transformasi geometris lokal untuk gambar yang terkait dengan objek TextureBrush ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | salinan objek Matrix yang mendefinisikan transformasi geometris lokal untuk gambar yang terkait dengan objek TextureBrush ini. |

### getWrapMode() {#getWrapMode--}
```
public int getWrapMode()
```


Mendapatkan enumerasi WrapMode yang menunjukkan mode pembungkus untuk objek TextureBrush ini.

**Returns:**
int - sebuah enumerasi WrapMode yang menunjukkan mode pembungkus untuk objek TextureBrush ini.
### setWrapMode(int value) {#setWrapMode-int-}
```
public void setWrapMode(int value)
```


Menetapkan enumerasi WrapMode yang menunjukkan mode pembungkus untuk objek TextureBrush ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int | sebuah enumerasi WrapMode yang menunjukkan mode pembungkus untuk objek TextureBrush ini. |

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Membuat salinan persis dari objek [TextureBrush](../../com.aspose.drawing/texturebrush) ini.

**Returns:**
java.lang.Object - Objek [TextureBrush](../../com.aspose.drawing/texturebrush) yang dibuat metode ini, di-cast sebagai objek Object.
### resetTransform() {#resetTransform--}
```
public void resetTransform()
```


Mengatur ulang properti Transform dari objek [TextureBrush](../../com.aspose.drawing/texturebrush) ini ke identitas.

### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-}
```
public void multiplyTransform(Matrix matrix)
```


Mengalikan objek [Matrix](../../com.aspose.drawing.drawing2d/matrix) yang merepresentasikan transformasi geometris lokal dari objek [TextureBrush](../../com.aspose.drawing/texturebrush) ini dengan objek [Matrix](../../com.aspose.drawing.drawing2d/matrix) yang ditentukan dengan menambahkan objek [Matrix](../../com.aspose.drawing.drawing2d/matrix) yang ditentukan di depan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | Objek [Matrix](../../com.aspose.drawing.drawing2d/matrix) yang digunakan untuk mengalikan transformasi geometris. |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-int-}
```
public void multiplyTransform(Matrix matrix, int order)
```


Mengalikan objek [Matrix](../../com.aspose.drawing.drawing2d/matrix) yang merepresentasikan transformasi geometris lokal dari objek [TextureBrush](../../com.aspose.drawing/texturebrush) ini dengan objek [Matrix](../../com.aspose.drawing.drawing2d/matrix) yang ditentukan dalam urutan yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | Objek [Matrix](../../com.aspose.drawing.drawing2d/matrix) yang digunakan untuk mengalikan transformasi geometris. |
| order | int | Sebuah enumerasi [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder) yang menentukan urutan pengalian kedua matriks. |

### translateTransform(float dx, float dy) {#translateTransform-float-float-}
```
public void translateTransform(float dx, float dy)
```


Menerjemahkan transformasi geometris lokal dari objek [TextureBrush](../../com.aspose.drawing/texturebrush) ini dengan dimensi yang ditentukan. Metode ini menambahkan translasi ke transformasi di depan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| dx | float | Dimensi yang digunakan untuk mentranslasi transformasi pada arah x. |
| dy | float | Dimensi yang digunakan untuk mentranslasi transformasi pada arah y. |

### translateTransform(float dx, float dy, int order) {#translateTransform-float-float-int-}
```
public void translateTransform(float dx, float dy, int order)
```


Mentranslasi transformasi geometris lokal dari objek [TextureBrush](../../com.aspose.drawing/texturebrush) ini dengan dimensi yang ditentukan dalam urutan yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| dx | float | Dimensi yang digunakan untuk mentranslasi transformasi pada arah x. |
| dy | float | Dimensi yang digunakan untuk mentranslasi transformasi pada arah y. |
| urutan | int | Urutan (prepend atau append) dalam menerapkan translasi. |

### scaleTransform(float sx, float sy) {#scaleTransform-float-float-}
```
public void scaleTransform(float sx, float sy)
```


Menskalakan transformasi geometris lokal dari objek [TextureBrush](../../com.aspose.drawing/texturebrush) ini dengan jumlah yang ditentukan. Metode ini menambahkan matriks skala ke transformasi di depan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sx | float | Jumlah yang digunakan untuk menskalakan transformasi pada arah x. |
| sy | float | Jumlah yang digunakan untuk menskalakan transformasi pada arah y. |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public void scaleTransform(float sx, float sy, int order)
```


Menskalakan transformasi geometris lokal dari objek [TextureBrush](../../com.aspose.drawing/texturebrush) ini dengan jumlah yang ditentukan dalam urutan yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sx | float | Jumlah yang digunakan untuk menskalakan transformasi pada arah x. |
| sy | float | Jumlah yang digunakan untuk menskalakan transformasi pada arah y. |
| order | int | Sebuah enumerasi [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder) yang menentukan apakah akan menambahkan atau menyisipkan matriks skala. |

### rotateTransform(float angle) {#rotateTransform-float-}
```
public void rotateTransform(float angle)
```


Memutar transformasi geometris lokal dari objek [TextureBrush](../../com.aspose.drawing/texturebrush) ini dengan jumlah yang ditentukan. Metode ini menambahkan rotasi ke transformasi di depan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sudut | float | Sudut rotasi. |

### rotateTransform(float angle, int order) {#rotateTransform-float-int-}
```
public void rotateTransform(float angle, int order)
```


Memutar transformasi geometris lokal dari objek [TextureBrush](../../com.aspose.drawing/texturebrush) ini dengan jumlah yang ditentukan dalam urutan yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sudut | float | Sudut rotasi. |
| order | int | Sebuah enumerasi [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder) yang menentukan apakah akan menambahkan atau menyisipkan matriks rotasi. |

