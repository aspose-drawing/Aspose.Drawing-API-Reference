---
title: Matrix
second_title: Referensi API Aspose.Drawing for Java
description: Mengkapsulkan matriks afine 3x3 yang merepresentasikan transformasi geometris.
type: docs
weight: 33
url: /id/java/com.aspose.drawing.drawing2d/matrix/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public final class Matrix implements System.IDisposable
```

Mengkapsulkan matriks afine 3x3 yang mewakili transformasi geometris. Kelas ini tidak dapat diwariskan.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [Matrix()](#Matrix--) | Menginisialisasi instance baru dari kelas Matrix sebagai matriks identitas. |
| [Matrix(float m11, float m12, float m21, float m22, float dx, float dy)](#Matrix-float-float-float-float-float-float-) | Menginisialisasi instance baru dari kelas Matrix dengan elemen yang ditentukan. |
| [Matrix(Rectangle rect, Point[] plgpts)](#Matrix-com.aspose.drawing.Rectangle-com.aspose.drawing.Point---) | Menginisialisasi instance baru dari kelas [Matrix](../../com.aspose.drawing.drawing2d/matrix) ke transformasi geometris yang didefinisikan oleh persegi panjang dan array titik yang ditentukan. |
| [Matrix(RectangleF rect, PointF[] plgpts)](#Matrix-com.aspose.drawing.RectangleF-com.aspose.drawing.PointF---) | Menginisialisasi instance baru dari kelas [Matrix](../../com.aspose.drawing.drawing2d/matrix) ke transformasi geometris yang didefinisikan oleh persegi panjang dan array titik yang ditentukan. |
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [IdentityTransform](#IdentityTransform) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getElements()](#getElements--) | Mendapatkan array nilai floating-point yang mewakili elemen-elemen Matrix ini. |
| [isIdentity()](#isIdentity--) | Mendapatkan nilai yang menunjukkan apakah Matrix ini adalah matriks identitas. |
| [isInvertible()](#isInvertible--) | Mendapatkan nilai yang menunjukkan apakah Matrix ini dapat dibalik. |
| [getOffsetX()](#getOffsetX--) | Mendapatkan nilai translasi x (nilai dx, atau elemen pada baris ketiga dan kolom pertama) dari Matrix ini. |
| [getOffsetY()](#getOffsetY--) | Mendapatkan nilai translasi y (nilai `dy`, atau elemen pada baris ketiga dan kolom kedua) dari Matrix ini. |
| [dispose()](#dispose--) | Melepaskan semua sumber daya yang digunakan oleh Matrix ini. |
| [deepClone()](#deepClone--) | Membuat salinan persis dari Matrix ini. |
| [invert()](#invert--) | Membalik Matrix ini, jika dapat dibalik. |
| [translate(float offsetX, float offsetY)](#translate-float-float-) | Menerapkan vektor translasi yang ditentukan (offsetX dan offsetY) ke Matrix ini dengan menambahkan vektor translasi di depan. |
| [translate(float offsetX, float offsetY, int order)](#translate-float-float-int-) | Menerapkan vektor translasi yang ditentukan ke Matrix ini dalam urutan yang ditentukan. |
| [transformVectors(PointF[] pts)](#transformVectors-com.aspose.drawing.PointF---) | Mengalikan setiap vektor dalam array dengan matrix. |
| [scale(float scaleX, float scaleY)](#scale-float-float-) | Menerapkan vektor skala yang ditentukan ke Matrix ini dengan menambahkan vektor skala di depan. |
| [scale(float scaleX, float scaleY, int order)](#scale-float-float-int-) | Menerapkan vektor skala yang ditentukan (scaleX dan scaleY) ke Matrix ini menggunakan urutan yang ditentukan. |
| [shear(float shearX, float shearY)](#shear-float-float-) | Menerapkan vektor shear yang ditentukan ke Matrix ini dengan menambahkan transformasi shear di depan. |
| [shear(float shearX, float shearY, int order)](#shear-float-float-int-) | Menerapkan vektor shear yang ditentukan ke Matrix ini dalam urutan yang ditentukan. |
| [rotateAt(float angle, PointF point)](#rotateAt-float-com.aspose.drawing.PointF-) | Menerapkan rotasi searah jarum jam ke Matrix ini di sekitar titik yang ditentukan dalam parameter point, dan dengan menambahkan rotasi di depan. |
| [rotateAt(float angle, PointF point, int order)](#rotateAt-float-com.aspose.drawing.PointF-int-) | Menerapkan rotasi searah jarum jam sekitar titik yang ditentukan ke Matrix ini dalam urutan yang ditentukan. |
| [transformPoints(PointF[] pts)](#transformPoints-com.aspose.drawing.PointF---) | Menerapkan transformasi geometrik yang diwakili oleh [Matrix](../../com.aspose.drawing.drawing2d/matrix) ini ke array titik yang ditentukan. |
| [transformPoints(Point[] pts)](#transformPoints-com.aspose.drawing.Point---) | Menerapkan transformasi geometrik yang diwakili oleh [Matrix](../../com.aspose.drawing.drawing2d/matrix) ini ke array titik yang ditentukan. |
| [multiply(Matrix matrix)](#multiply-com.aspose.drawing.drawing2d.Matrix-) | Mengalikan [Matrix](../../com.aspose.drawing.drawing2d/matrix) ini dengan matrix yang ditentukan dalam parameter `matrix`, dengan menambahkan [Matrix](../../com.aspose.drawing.drawing2d/matrix) yang ditentukan di depan. |
| [multiply(Matrix matrix, int order)](#multiply-com.aspose.drawing.drawing2d.Matrix-int-) | Mengalikan [Matrix](../../com.aspose.drawing.drawing2d/matrix) ini dengan matrix yang ditentukan dalam parameter `matrix`, dan dalam urutan yang ditentukan dalam parameter `order`. |
| [rotate(float angle)](#rotate-float-) | Tambahkan di depan [Matrix](../../com.aspose.drawing.drawing2d/matrix) ini rotasi searah jarum jam, di sekitar asal dan dengan sudut yang ditentukan. |
| [rotate(float angle, int order)](#rotate-float-int-) | Menerapkan rotasi searah jarum jam dengan jumlah yang ditentukan dalam parameter angle, di sekitar asal (koordinat x dan y nol) untuk [Matrix](../../com.aspose.drawing.drawing2d/matrix) ini. |
| [reset()](#reset--) | Mengatur ulang [Matrix](../../com.aspose.drawing.drawing2d/matrix) ini sehingga memiliki elemen-elemen matrix identitas. |
### Matrix() {#Matrix--}
```
public Matrix()
```


Menginisialisasi instance baru dari kelas Matrix sebagai matriks identitas.

### Matrix(float m11, float m12, float m21, float m22, float dx, float dy) {#Matrix-float-float-float-float-float-float-}
```
public Matrix(float m11, float m12, float m21, float m22, float dx, float dy)
```


Menginisialisasi instance baru dari kelas Matrix dengan elemen yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| m11 | float | Nilai pada baris pertama dan kolom pertama dari Matrix baru. |
| m12 | float | Nilai pada baris pertama dan kolom kedua dari Matrix baru. |
| m21 | float | Nilai pada baris kedua dan kolom pertama dari Matrix baru. |
| m22 | float | Nilai pada baris kedua dan kolom kedua dari Matrix baru. |
| dx | float | Nilai pada baris ketiga dan kolom pertama dari Matrix baru. |
| dy | float | Nilai pada baris ketiga dan kolom kedua dari Matrix baru. |

### Matrix(Rectangle rect, Point[] plgpts) {#Matrix-com.aspose.drawing.Rectangle-com.aspose.drawing.Point---}
```
public Matrix(Rectangle rect, Point[] plgpts)
```


Menginisialisasi instance baru dari kelas [Matrix](../../com.aspose.drawing.drawing2d/matrix) ke transformasi geometris yang didefinisikan oleh persegi panjang dan array titik yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | Sebuah struktur [Rectangle](../../com.aspose.drawing/rectangle) yang mewakili persegi panjang yang akan diubah. |
| plgpts | [Point\[\]](../../com.aspose.drawing/point) | Array berisi tiga struktur [Point](../../com.aspose.drawing/point) yang mewakili titik-titik sebuah paralelogram tempat sudut kiri atas, kanan atas, dan kiri bawah persegi panjang akan diubah. Sudut kanan bawah paralelogram diimplikasikan oleh tiga sudut pertama. |

### Matrix(RectangleF rect, PointF[] plgpts) {#Matrix-com.aspose.drawing.RectangleF-com.aspose.drawing.PointF---}
```
public Matrix(RectangleF rect, PointF[] plgpts)
```


Menginisialisasi instance baru dari kelas [Matrix](../../com.aspose.drawing.drawing2d/matrix) ke transformasi geometris yang didefinisikan oleh persegi panjang dan array titik yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | Sebuah struktur [RectangleF](../../com.aspose.drawing/rectanglef) yang mewakili persegi panjang yang akan diubah. |
| plgpts | [PointF\[\]](../../com.aspose.drawing/pointf) | Array berisi tiga struktur [PointF](../../com.aspose.drawing/pointf) yang mewakili titik-titik sebuah paralelogram tempat sudut kiri atas, kanan atas, dan kiri bawah persegi panjang akan diubah. Sudut kanan bawah paralelogram diimplikasikan oleh tiga sudut pertama. |

### IdentityTransform {#IdentityTransform}
```
public static final Matrix IdentityTransform
```


### getElements() {#getElements--}
```
public float[] getElements()
```


Mendapatkan array nilai floating-point yang mewakili elemen-elemen Matrix ini.

**Returns:**
float[] - sebuah array nilai floating-point yang mewakili elemen-elemen Matrix ini.
### isIdentity() {#isIdentity--}
```
public boolean isIdentity()
```


Mendapatkan nilai yang menunjukkan apakah Matrix ini adalah matriks identitas.

**Returns:**
boolean - nilai yang menunjukkan apakah Matrix ini adalah matrix identitas.
### isInvertible() {#isInvertible--}
```
public boolean isInvertible()
```


Mendapatkan nilai yang menunjukkan apakah Matrix ini dapat dibalik.

**Returns:**
boolean - nilai yang menunjukkan apakah Matrix ini dapat diinverskan.
### getOffsetX() {#getOffsetX--}
```
public float getOffsetX()
```


Mendapatkan nilai translasi x (nilai dx, atau elemen pada baris ketiga dan kolom pertama) dari Matrix ini.

**Returns:**
float - nilai translasi x (nilai dx, atau elemen pada baris ketiga dan kolom pertama) dari Matrix ini.
### getOffsetY() {#getOffsetY--}
```
public float getOffsetY()
```


Mendapatkan nilai translasi y (nilai `dy`, atau elemen pada baris ketiga dan kolom kedua) dari Matrix ini.

**Returns:**
float - nilai translasi y (nilai `dy`, atau elemen pada baris ketiga dan kolom kedua) dari Matrix ini.
### dispose() {#dispose--}
```
public void dispose()
```


Melepaskan semua sumber daya yang digunakan oleh Matrix ini.

--------------------

Metode ini sebenarnya tidak melakukan apa-apa. Ini hanya untuk kompatibilitas dengan API System.Drawing.

### deepClone() {#deepClone--}
```
public Matrix deepClone()
```


Membuat salinan persis dari Matrix ini.

**Returns:**
[Matrix](../../com.aspose.drawing.drawing2d/matrix) - The Matrix that this method creates.
### invert() {#invert--}
```
public void invert()
```


Membalik Matrix ini, jika dapat dibalik.

### translate(float offsetX, float offsetY) {#translate-float-float-}
```
public void translate(float offsetX, float offsetY)
```


Menerapkan vektor translasi yang ditentukan (offsetX dan offsetY) ke Matrix ini dengan menambahkan vektor translasi di depan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| offsetX | float | Nilai x yang digunakan untuk mentranslasi Matrix ini. |
| offsetY | float | Nilai y yang digunakan untuk mentranslasi Matrix ini. |

### translate(float offsetX, float offsetY, int order) {#translate-float-float-int-}
```
public void translate(float offsetX, float offsetY, int order)
```


Menerapkan vektor translasi yang ditentukan ke Matrix ini dalam urutan yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| offsetX | float | Nilai x yang digunakan untuk mentranslasi Matrix ini. |
| offsetY | float | Nilai y yang digunakan untuk mentranslasi Matrix ini. |
| urutan | int | Sebuah MatrixOrder yang menentukan urutan (append atau prepend) penerapan translasi pada Matrix ini. |

### transformVectors(PointF[] pts) {#transformVectors-com.aspose.drawing.PointF---}
```
public void transformVectors(PointF[] pts)
```


Mengalikan setiap vektor dalam array dengan matrix. Elemen translasi matrix ini (baris ketiga) diabaikan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pts | [PointF\[\]](../../com.aspose.drawing/pointf) | Array berisi struktur [PointF](../../com.aspose.drawing/pointf) yang mewakili titik-titik yang akan diubah. |

### scale(float scaleX, float scaleY) {#scale-float-float-}
```
public void scale(float scaleX, float scaleY)
```


Menerapkan vektor skala yang ditentukan ke Matrix ini dengan menambahkan vektor skala di depan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| scaleX | float | Nilai yang digunakan untuk menskalakan Matrix ini pada arah sumbu x. |
| scaleY | float | Nilai yang digunakan untuk menskalakan Matrix ini pada arah sumbu y. |

### scale(float scaleX, float scaleY, int order) {#scale-float-float-int-}
```
public void scale(float scaleX, float scaleY, int order)
```


Menerapkan vektor skala yang ditentukan (scaleX dan scaleY) ke Matrix ini menggunakan urutan yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| scaleX | float | Nilai yang digunakan untuk menskalakan Matrix ini pada arah sumbu x. |
| scaleY | float | Nilai yang digunakan untuk menskalakan Matrix ini pada arah sumbu y. |
| urutan | int | Sebuah MatrixOrder yang menentukan urutan (tambahkan atau sisipkan) di mana vektor skala diterapkan pada Matrix ini. |

### shear(float shearX, float shearY) {#shear-float-float-}
```
public void shear(float shearX, float shearY)
```


Menerapkan vektor shear yang ditentukan ke Matrix ini dengan menambahkan transformasi shear di depan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| shearX | float | Faktor geser horizontal. |
| shearY | float | Faktor geser vertikal. |

### shear(float shearX, float shearY, int order) {#shear-float-float-int-}
```
public void shear(float shearX, float shearY, int order)
```


Menerapkan vektor shear yang ditentukan ke Matrix ini dalam urutan yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| shearX | float | Faktor geser horizontal. |
| shearY | float | Faktor geser vertikal. |
| urutan | int | Sebuah MatrixOrder yang menentukan urutan (tambahkan atau sisipkan) di mana geser diterapkan. |

### rotateAt(float angle, PointF point) {#rotateAt-float-com.aspose.drawing.PointF-}
```
public void rotateAt(float angle, PointF point)
```


Menerapkan rotasi searah jarum jam ke Matrix ini di sekitar titik yang ditentukan dalam parameter point, dan dengan menambahkan rotasi di depan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sudut | float | Sudut (rentang) rotasi, dalam derajat. |
| point | [PointF](../../com.aspose.drawing/pointf) | Sebuah PointF yang mewakili pusat rotasi. |

### rotateAt(float angle, PointF point, int order) {#rotateAt-float-com.aspose.drawing.PointF-int-}
```
public void rotateAt(float angle, PointF point, int order)
```


Menerapkan rotasi searah jarum jam sekitar titik yang ditentukan ke Matrix ini dalam urutan yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sudut | float | Sudut rotasi, dalam derajat. |
| point | [PointF](../../com.aspose.drawing/pointf) | Sebuah PointF yang mewakili pusat rotasi. |
| urutan | int | Sebuah MatrixOrder yang menentukan urutan (tambahkan atau sisipkan) di mana rotasi diterapkan. |

### transformPoints(PointF[] pts) {#transformPoints-com.aspose.drawing.PointF---}
```
public void transformPoints(PointF[] pts)
```


Menerapkan transformasi geometrik yang diwakili oleh [Matrix](../../com.aspose.drawing.drawing2d/matrix) ini ke array titik yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pts | [PointF\[\]](../../com.aspose.drawing/pointf) | Array berisi struktur [PointF](../../com.aspose.drawing/pointf) yang mewakili titik-titik yang akan diubah. |

### transformPoints(Point[] pts) {#transformPoints-com.aspose.drawing.Point---}
```
public void transformPoints(Point[] pts)
```


Menerapkan transformasi geometrik yang diwakili oleh [Matrix](../../com.aspose.drawing.drawing2d/matrix) ini ke array titik yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pts | [Point\[\]](../../com.aspose.drawing/point) | Sebuah array struktur [Point](../../com.aspose.drawing/point) yang mewakili titik-titik yang akan diubah. |

### multiply(Matrix matrix) {#multiply-com.aspose.drawing.drawing2d.Matrix-}
```
public void multiply(Matrix matrix)
```


Mengalikan [Matrix](../../com.aspose.drawing.drawing2d/matrix) ini dengan matrix yang ditentukan dalam parameter `matrix`, dengan menambahkan [Matrix](../../com.aspose.drawing.drawing2d/matrix) yang ditentukan di depan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | [Matrix](../../com.aspose.drawing.drawing2d/matrix) yang akan mengalikan [Matrix](../../com.aspose.drawing.drawing2d/matrix) ini. |

### multiply(Matrix matrix, int order) {#multiply-com.aspose.drawing.drawing2d.Matrix-int-}
```
public void multiply(Matrix matrix, int order)
```


Mengalikan [Matrix](../../com.aspose.drawing.drawing2d/matrix) ini dengan matrix yang ditentukan dalam parameter `matrix`, dan dalam urutan yang ditentukan dalam parameter `order`.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | [Matrix](../../com.aspose.drawing.drawing2d/matrix) yang akan mengalikan [Matrix](../../com.aspose.drawing.drawing2d/matrix) ini. |
| order | int | [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder) yang mewakili urutan perkalian. |

### rotate(float angle) {#rotate-float-}
```
public void rotate(float angle)
```


Tambahkan di depan [Matrix](../../com.aspose.drawing.drawing2d/matrix) ini rotasi searah jarum jam, di sekitar asal dan dengan sudut yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sudut | float | Sudut rotasi, dalam derajat. |

### rotate(float angle, int order) {#rotate-float-int-}
```
public void rotate(float angle, int order)
```


Menerapkan rotasi searah jarum jam dengan jumlah yang ditentukan dalam parameter angle, di sekitar asal (koordinat x dan y nol) untuk [Matrix](../../com.aspose.drawing.drawing2d/matrix) ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sudut | float | Sudut rotasi, dalam derajat. |
| order | int | Sebuah [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder) yang menentukan urutan (tambahkan atau sisipkan) di mana rotasi diterapkan pada [Matrix](../../com.aspose.drawing.drawing2d/matrix) ini. |

### reset() {#reset--}
```
public void reset()
```


Mengatur ulang [Matrix](../../com.aspose.drawing.drawing2d/matrix) ini sehingga memiliki elemen-elemen matrix identitas.

