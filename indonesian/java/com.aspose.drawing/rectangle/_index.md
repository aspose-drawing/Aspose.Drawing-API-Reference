---
title: Rectangle
second_title: Referensi API Aspose.Drawing for Java
description: Menyimpan sekumpulan empat integer yang mewakili lokasi dan ukuran sebuah persegi panjang.
type: docs
weight: 38
url: /id/java/com.aspose.drawing/rectangle/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable, java.lang.Cloneable
```
public class Rectangle extends Struct<Rectangle> implements System.IEquatable<Rectangle>, Cloneable
```

Menyimpan sekumpulan empat integer yang mewakili lokasi dan ukuran sebuah persegi panjang.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [Rectangle()](#Rectangle--) |  |
| [Rectangle(int x, int y, int width, int height)](#Rectangle-int-int-int-int-) | Menginisialisasi instance baru dari struktur Rectangle dengan lokasi dan ukuran yang ditentukan. |
| [Rectangle(Point location, Size size)](#Rectangle-com.aspose.drawing.Point-com.aspose.drawing.Size-) | Menginisialisasi instance baru dari struct [Rectangle](../../com.aspose.drawing/rectangle) dengan lokasi dan ukuran yang ditentukan. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [fromLTRB(int left, int top, int right, int bottom)](#fromLTRB-int-int-int-int-) | Membuat struktur [Rectangle](../../com.aspose.drawing/rectangle) dengan lokasi tepi yang ditentukan. |
| [intersect(Rectangle a, Rectangle b)](#intersect-com.aspose.drawing.Rectangle-com.aspose.drawing.Rectangle-) | Mengembalikan struktur [Rectangle](../../com.aspose.drawing/rectangle) ketiga yang mewakili irisan dari dua struktur [Rectangle](../../com.aspose.drawing/rectangle) lainnya. |
| [op_Equality(Rectangle left, Rectangle right)](#op-Equality-com.aspose.drawing.Rectangle-com.aspose.drawing.Rectangle-) | Menguji apakah dua struktur [Rectangle](../../com.aspose.drawing/rectangle) memiliki lokasi dan ukuran yang sama. |
| [op_Inequality(Rectangle left, Rectangle right)](#op-Inequality-com.aspose.drawing.Rectangle-com.aspose.drawing.Rectangle-) | Menguji apakah dua struktur [Rectangle](../../com.aspose.drawing/rectangle) berbeda dalam lokasi atau ukuran. |
| [ceiling(RectangleF value)](#ceiling-com.aspose.drawing.RectangleF-) | Mengonversi struktur [RectangleF](../../com.aspose.drawing/rectanglef) yang ditentukan menjadi struktur [Rectangle](../../com.aspose.drawing/rectangle) dengan membulatkan nilai [RectangleF](../../com.aspose.drawing/rectanglef) ke nilai integer berikutnya yang lebih tinggi. |
| [truncate(RectangleF value)](#truncate-com.aspose.drawing.RectangleF-) | Mengonversi [RectangleF](../../com.aspose.drawing/rectanglef) yang ditentukan menjadi [Rectangle](../../com.aspose.drawing/rectangle) dengan memotong nilai [RectangleF](../../com.aspose.drawing/rectanglef). |
| [round(RectangleF value)](#round-com.aspose.drawing.RectangleF-) | Mengonversi [RectangleF](../../com.aspose.drawing/rectanglef) yang ditentukan menjadi [Rectangle](../../com.aspose.drawing/rectangle) dengan membulatkan nilai [RectangleF](../../com.aspose.drawing/rectanglef) ke nilai integer terdekat. |
| [union(Rectangle a, Rectangle b)](#union-com.aspose.drawing.Rectangle-com.aspose.drawing.Rectangle-) | Mendapatkan struktur [Rectangle](../../com.aspose.drawing/rectangle) yang berisi gabungan dari dua struktur [Rectangle](../../com.aspose.drawing/rectangle). |
| [inflate(Rectangle rect, int x, int y)](#inflate-com.aspose.drawing.Rectangle-int-int-) |  |
| [isEquals(Rectangle obj1, Rectangle obj2)](#isEquals-com.aspose.drawing.Rectangle-com.aspose.drawing.Rectangle-) |  |
| [fromPoints(Point point1, Point point2)](#fromPoints-com.aspose.drawing.Point-com.aspose.drawing.Point-) | Membuat persegi panjang baru dari dua titik. |
| [getEmpty()](#getEmpty--) | Mendapatkan instance baru dari struktur `Rectangle` yang nilai `Rectangle.X`, `Rectangle.Y`, `Rectangle.Width`, dan `Rectangle.Height`‑nya diatur ke nol. |
| [getX()](#getX--) | Mendapatkan koordinat x dari sudut kiri atas struktur Rectangle ini. |
| [setX(int value)](#setX-int-) | Mengatur koordinat x dari sudut kiri atas struktur Rectangle ini. |
| [getY()](#getY--) | Mendapatkan koordinat y dari sudut kiri atas struktur Rectangle ini. |
| [setY(int value)](#setY-int-) | Mengatur koordinat y dari sudut kiri atas struktur Rectangle ini. |
| [getLocation()](#getLocation--) | Mendapatkan koordinat sudut kiri atas dari struktur [Rectangle](../../com.aspose.drawing/rectangle) ini. |
| [setLocation(Point value)](#setLocation-com.aspose.drawing.Point-) | Mengatur koordinat sudut kiri atas dari struktur [Rectangle](../../com.aspose.drawing/rectangle) ini. |
| [getWidth()](#getWidth--) | Mendapatkan lebar dari struktur Rectangle ini. |
| [setWidth(int value)](#setWidth-int-) | Mengatur lebar dari struktur Rectangle ini. |
| [getHeight()](#getHeight--) | Mendapatkan tinggi dari struktur Rectangle ini. |
| [setHeight(int value)](#setHeight-int-) | Mengatur tinggi dari struktur Rectangle ini. |
| [getSize()](#getSize--) | Mendapatkan ukuran dari [Rectangle](../../com.aspose.drawing/rectangle) ini. |
| [setSize(Size value)](#setSize-com.aspose.drawing.Size-) | Mengatur ukuran dari [Rectangle](../../com.aspose.drawing/rectangle) ini. |
| [getLeft()](#getLeft--) | Mendapatkan koordinat x dari tepi kiri struktur Rectangle ini. |
| [getTop()](#getTop--) | Mendapatkan koordinat y dari tepi atas struktur Rectangle ini. |
| [getRight()](#getRight--) | Mendapatkan koordinat x yang merupakan hasil penjumlahan nilai properti X dan Width dari struktur Rectangle ini. |
| [getBottom()](#getBottom--) | Mendapatkan koordinat y yang merupakan hasil penjumlahan nilai properti Y dan Height dari struktur Rectangle ini. |
| [isEmpty()](#isEmpty--) | Mendapatkan nilai yang menunjukkan apakah semua properti numerik dari [Rectangle](../../com.aspose.drawing/rectangle) ini memiliki nilai nol. |
| [equals(Object obj)](#equals-java.lang.Object-) | Menguji apakah obj adalah struktur [Rectangle](../../com.aspose.drawing/rectangle) dengan lokasi dan ukuran yang sama dengan struktur [Rectangle](../../com.aspose.drawing/rectangle) ini. |
| [hashCode()](#hashCode--) | Mengembalikan kode hash untuk struktur [Rectangle](../../com.aspose.drawing/rectangle) ini. |
| [toString()](#toString--) |  |
| [intersect(Rectangle rect)](#intersect-com.aspose.drawing.Rectangle-) | Mengganti [Rectangle](../../com.aspose.drawing/rectangle) ini dengan irisan antara dirinya sendiri dan [Rectangle](../../com.aspose.drawing/rectangle) yang ditentukan. |
| [inflate(int width, int height)](#inflate-int-int-) | Memperbesar [Rectangle](../../com.aspose.drawing/rectangle) ini sebesar jumlah yang ditentukan. |
| [inflate(Size size)](#inflate-com.aspose.drawing.Size-) | Memperbesar [Rectangle](../../com.aspose.drawing/rectangle) ini sebesar jumlah yang ditentukan. |
| [contains(int x, int y)](#contains-int-int-) | Menentukan apakah titik yang ditentukan berada di dalam struktur [Rectangle](../../com.aspose.drawing/rectangle) ini. |
| [contains(Point pt)](#contains-com.aspose.drawing.Point-) | Menentukan apakah titik yang ditentukan berada di dalam struktur [Rectangle](../../com.aspose.drawing/rectangle) ini. |
| [contains(Rectangle rect)](#contains-com.aspose.drawing.Rectangle-) |  |
| [intersectsWith(Rectangle rect)](#intersectsWith-com.aspose.drawing.Rectangle-) | Menentukan apakah persegi panjang ini berpotongan dengan `rect`. |
| [offset(int x, int y)](#offset-int-int-) | Menyesuaikan lokasi persegi panjang ini sebesar jumlah yang ditentukan. |
| [offset(Point pos)](#offset-com.aspose.drawing.Point-) | Menyesuaikan lokasi persegi panjang ini sebesar jumlah yang ditentukan. |
| [equals(Rectangle other)](#equals-com.aspose.drawing.Rectangle-) | Menguji apakah struktur [Rectangle](../../com.aspose.drawing/rectangle) lain memiliki lokasi dan ukuran yang sama dengan struktur [Rectangle](../../com.aspose.drawing/rectangle) ini. |
| [CloneTo(Rectangle that)](#CloneTo-com.aspose.drawing.Rectangle-) |  |
| [Clone()](#Clone--) |  |
| [clone()](#clone--) |  |
| [normalize()](#normalize--) | Menormalkan persegi panjang dengan membuat lebar dan tinggi menjadi positif, kiri lebih kecil dari kanan, dan atas lebih kecil dari bawah. |
### Rectangle() {#Rectangle--}
```
public Rectangle()
```


### Rectangle(int x, int y, int width, int height) {#Rectangle-int-int-int-int-}
```
public Rectangle(int x, int y, int width, int height)
```


Menginisialisasi instance baru dari struktur Rectangle dengan lokasi dan ukuran yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | int | Koordinat x dari sudut kiri atas persegi panjang. |
| y | int | Koordinat y dari sudut kiri atas persegi panjang. |
| lebar | int | Lebar persegi panjang. |
| tinggi | int | Tinggi persegi panjang. |

### Rectangle(Point location, Size size) {#Rectangle-com.aspose.drawing.Point-com.aspose.drawing.Size-}
```
public Rectangle(Point location, Size size)
```


Menginisialisasi instance baru dari struct [Rectangle](../../com.aspose.drawing/rectangle) dengan lokasi dan ukuran yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| location | [Point](../../com.aspose.drawing/point) | Sebuah [Point](../../com.aspose.drawing/point) yang mewakili sudut kiri atas dari wilayah persegi panjang. |
| size | [Size](../../com.aspose.drawing/size) | Sebuah `Size`([.getSize](../../null/\#getSize)/[.setSize(Size)](../../null/\#setSize-Size-)) yang mewakili lebar dan tinggi dari wilayah persegi panjang. |

### fromLTRB(int left, int top, int right, int bottom) {#fromLTRB-int-int-int-int-}
```
public static Rectangle fromLTRB(int left, int top, int right, int bottom)
```


Membuat struktur [Rectangle](../../com.aspose.drawing/rectangle) dengan lokasi tepi yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| left | int | Koordinat x dari sudut kiri atas dari struktur [Rectangle](../../com.aspose.drawing/rectangle) ini. |
| top | int | Koordinat y dari sudut kiri atas dari struktur [Rectangle](../../com.aspose.drawing/rectangle) ini. |
| right | int | Koordinat x dari sudut kanan bawah dari struktur [Rectangle](../../com.aspose.drawing/rectangle) ini. |
| bottom | int | Koordinat y dari sudut kanan bawah dari struktur [Rectangle](../../com.aspose.drawing/rectangle) ini. |

**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle) - The new [Rectangle](../../com.aspose.drawing/rectangle) that this method creates.
### intersect(Rectangle a, Rectangle b) {#intersect-com.aspose.drawing.Rectangle-com.aspose.drawing.Rectangle-}
```
public static Rectangle intersect(Rectangle a, Rectangle b)
```


Mengembalikan struktur [Rectangle](../../com.aspose.drawing/rectangle) ketiga yang mewakili irisan dari dua struktur [Rectangle](../../com.aspose.drawing/rectangle) lainnya. Jika tidak ada irisan, sebuah [Rectangle](../../com.aspose.drawing/rectangle) kosong dikembalikan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| a | [Rectangle](../../com.aspose.drawing/rectangle) | Persegi panjang pertama untuk diiris. |
| b | [Rectangle](../../com.aspose.drawing/rectangle) | Persegi panjang kedua untuk diiris. |

**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle) - A [Rectangle](../../com.aspose.drawing/rectangle) that represents the intersection of `a` and `b`.
### op_Equality(Rectangle left, Rectangle right) {#op-Equality-com.aspose.drawing.Rectangle-com.aspose.drawing.Rectangle-}
```
public static boolean op_Equality(Rectangle left, Rectangle right)
```


Menguji apakah dua struktur [Rectangle](../../com.aspose.drawing/rectangle) memiliki lokasi dan ukuran yang sama.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| left | [Rectangle](../../com.aspose.drawing/rectangle) | Struktur [Rectangle](../../com.aspose.drawing/rectangle) yang berada di sebelah kiri operator kesamaan. |
| right | [Rectangle](../../com.aspose.drawing/rectangle) | Struktur [Rectangle](../../com.aspose.drawing/rectangle) yang berada di sebelah kanan operator kesamaan. |

**Returns:**
boolean - Operator ini mengembalikan `true` jika dua struktur [Rectangle](../../com.aspose.drawing/rectangle) memiliki properti X, Y, Width, dan Height yang sama.
### op_Inequality(Rectangle left, Rectangle right) {#op-Inequality-com.aspose.drawing.Rectangle-com.aspose.drawing.Rectangle-}
```
public static boolean op_Inequality(Rectangle left, Rectangle right)
```


Menguji apakah dua struktur [Rectangle](../../com.aspose.drawing/rectangle) berbeda dalam lokasi atau ukuran.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| left | [Rectangle](../../com.aspose.drawing/rectangle) | Struktur [Rectangle](../../com.aspose.drawing/rectangle) yang berada di sebelah kiri operator ketidaksamaan. |
| right | [Rectangle](../../com.aspose.drawing/rectangle) | Struktur [Rectangle](../../com.aspose.drawing/rectangle) yang berada di sebelah kanan operator ketidaksamaan. |

**Returns:**
boolean - Operator ini mengembalikan `true` jika salah satu properti X, Y, Width, atau Height dari dua struktur [Rectangle](../../com.aspose.drawing/rectangle) tidak sama; selain itu `false`.
### ceiling(RectangleF value) {#ceiling-com.aspose.drawing.RectangleF-}
```
public static Rectangle ceiling(RectangleF value)
```


Mengonversi struktur [RectangleF](../../com.aspose.drawing/rectanglef) yang ditentukan menjadi struktur [Rectangle](../../com.aspose.drawing/rectangle) dengan membulatkan nilai [RectangleF](../../com.aspose.drawing/rectanglef) ke nilai integer berikutnya yang lebih tinggi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.drawing/rectanglef) | Struktur [RectangleF](../../com.aspose.drawing/rectanglef) yang akan dikonversi. |

**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle) - Returns a [Rectangle](../../com.aspose.drawing/rectangle).
### truncate(RectangleF value) {#truncate-com.aspose.drawing.RectangleF-}
```
public static Rectangle truncate(RectangleF value)
```


Mengonversi [RectangleF](../../com.aspose.drawing/rectanglef) yang ditentukan menjadi [Rectangle](../../com.aspose.drawing/rectangle) dengan memotong nilai [RectangleF](../../com.aspose.drawing/rectanglef).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.drawing/rectanglef) | [RectangleF](../../com.aspose.drawing/rectanglef) yang akan dikonversi. |

**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle) - The truncated value of the [Rectangle](../../com.aspose.drawing/rectangle).
### round(RectangleF value) {#round-com.aspose.drawing.RectangleF-}
```
public static Rectangle round(RectangleF value)
```


Mengonversi [RectangleF](../../com.aspose.drawing/rectanglef) yang ditentukan menjadi [Rectangle](../../com.aspose.drawing/rectangle) dengan membulatkan nilai [RectangleF](../../com.aspose.drawing/rectanglef) ke nilai integer terdekat.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.drawing/rectanglef) | [RectangleF](../../com.aspose.drawing/rectanglef) yang akan dikonversi. |

**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle) - A [Rectangle](../../com.aspose.drawing/rectangle).
### union(Rectangle a, Rectangle b) {#union-com.aspose.drawing.Rectangle-com.aspose.drawing.Rectangle-}
```
public static Rectangle union(Rectangle a, Rectangle b)
```


Mendapatkan struktur [Rectangle](../../com.aspose.drawing/rectangle) yang berisi gabungan dari dua struktur [Rectangle](../../com.aspose.drawing/rectangle).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| a | [Rectangle](../../com.aspose.drawing/rectangle) | Persegi panjang pertama untuk digabungkan. |
| b | [Rectangle](../../com.aspose.drawing/rectangle) | Persegi panjang kedua untuk digabungkan. |

**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle) - A [Rectangle](../../com.aspose.drawing/rectangle) structure that bounds the union of the two [Rectangle](../../com.aspose.drawing/rectangle) structures.
### inflate(Rectangle rect, int x, int y) {#inflate-com.aspose.drawing.Rectangle-int-int-}
```
public static Rectangle inflate(Rectangle rect, int x, int y)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) |  |
| x | int |  |
| y | int |  |

**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle)
### isEquals(Rectangle obj1, Rectangle obj2) {#isEquals-com.aspose.drawing.Rectangle-com.aspose.drawing.Rectangle-}
```
public static boolean isEquals(Rectangle obj1, Rectangle obj2)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj1 | [Rectangle](../../com.aspose.drawing/rectangle) |  |
| obj2 | [Rectangle](../../com.aspose.drawing/rectangle) |  |

**Returns:**
boolean
### fromPoints(Point point1, Point point2) {#fromPoints-com.aspose.drawing.Point-com.aspose.drawing.Point-}
```
public static Rectangle fromPoints(Point point1, Point point2)
```


Membuat persegi panjang baru dari dua titik. Persegi panjang yang dibuat akan dinormalisasi dengan (kiri,atas) lebih rendah daripada (kanan,bawah).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.drawing/point) | Titik pertama. |
| point2 | [Point](../../com.aspose.drawing/point) | Titik kedua. |

**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle) - A newly created rectangle.
### getEmpty() {#getEmpty--}
```
public static Rectangle getEmpty()
```


Mendapatkan instance baru dari struktur `Rectangle` yang nilai `Rectangle.X`, `Rectangle.Y`, `Rectangle.Width`, dan `Rectangle.Height`‑nya diatur ke nol.

**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle)
### getX() {#getX--}
```
public final int getX()
```


Mendapatkan koordinat x dari sudut kiri atas struktur Rectangle ini.

**Returns:**
int - koordinat x dari sudut kiri atas struktur Rectangle ini.
### setX(int value) {#setX-int-}
```
public final void setX(int value)
```


Mengatur koordinat x dari sudut kiri atas struktur Rectangle ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int | koordinat x dari sudut kiri atas struktur Rectangle ini. |

### getY() {#getY--}
```
public final int getY()
```


Mendapatkan koordinat y dari sudut kiri atas struktur Rectangle ini.

**Returns:**
int - koordinat y dari sudut kiri atas struktur Rectangle ini.
### setY(int value) {#setY-int-}
```
public final void setY(int value)
```


Mengatur koordinat y dari sudut kiri atas struktur Rectangle ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int | koordinat y dari sudut kiri atas struktur Rectangle ini. |

### getLocation() {#getLocation--}
```
public final Point getLocation()
```


Mendapatkan koordinat sudut kiri atas dari struktur [Rectangle](../../com.aspose.drawing/rectangle) ini.

**Returns:**
[Point](../../com.aspose.drawing/point) - the coordinates of the upper-left corner of this [Rectangle](../../com.aspose.drawing/rectangle) structure.
### setLocation(Point value) {#setLocation-com.aspose.drawing.Point-}
```
public final void setLocation(Point value)
```


Mengatur koordinat sudut kiri atas dari struktur [Rectangle](../../com.aspose.drawing/rectangle) ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Point](../../com.aspose.drawing/point) | koordinat sudut kiri atas dari struktur [Rectangle](../../com.aspose.drawing/rectangle) ini. |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Mendapatkan lebar dari struktur Rectangle ini.

**Returns:**
int - lebar dari struktur Rectangle ini.
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Mengatur lebar dari struktur Rectangle ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int | lebar dari struktur Rectangle ini. |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Mendapatkan tinggi dari struktur Rectangle ini.

**Returns:**
int - tinggi dari struktur Rectangle ini.
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Mengatur tinggi dari struktur Rectangle ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int | tinggi dari struktur Rectangle ini. |

### getSize() {#getSize--}
```
public final Size getSize()
```


Mendapatkan ukuran dari [Rectangle](../../com.aspose.drawing/rectangle) ini.

**Returns:**
[Size](../../com.aspose.drawing/size) - the size of this [Rectangle](../../com.aspose.drawing/rectangle).
### setSize(Size value) {#setSize-com.aspose.drawing.Size-}
```
public final void setSize(Size value)
```


Mengatur ukuran dari [Rectangle](../../com.aspose.drawing/rectangle) ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Size](../../com.aspose.drawing/size) | ukuran dari [Rectangle](../../com.aspose.drawing/rectangle) ini. |

### getLeft() {#getLeft--}
```
public final int getLeft()
```


Mendapatkan koordinat x dari tepi kiri struktur Rectangle ini.

**Returns:**
int - koordinat x dari tepi kiri struktur Rectangle ini.
### getTop() {#getTop--}
```
public final int getTop()
```


Mendapatkan koordinat y dari tepi atas struktur Rectangle ini.

**Returns:**
int - koordinat y dari tepi atas struktur Rectangle ini.
### getRight() {#getRight--}
```
public final int getRight()
```


Mendapatkan koordinat x yang merupakan hasil penjumlahan nilai properti X dan Width dari struktur Rectangle ini.

**Returns:**
int - koordinat x yang merupakan hasil penjumlahan nilai properti X dan Width dari struktur Rectangle ini.
### getBottom() {#getBottom--}
```
public final int getBottom()
```


Mendapatkan koordinat y yang merupakan hasil penjumlahan nilai properti Y dan Height dari struktur Rectangle ini.

**Returns:**
int - koordinat y yang merupakan hasil penjumlahan nilai properti Y dan Height dari struktur Rectangle ini.
### isEmpty() {#isEmpty--}
```
public final boolean isEmpty()
```


Mendapatkan nilai yang menunjukkan apakah semua properti numerik dari [Rectangle](../../com.aspose.drawing/rectangle) ini memiliki nilai nol.

**Returns:**
boolean - Properti ini mengembalikan `true` jika properti `Rectangle.Width`, `Rectangle.Height`, `Rectangle.X`, dan `Rectangle.Y` dari [Rectangle](../../com.aspose.drawing/rectangle) ini semuanya bernilai nol; selainnya, `false`.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Menguji apakah obj adalah struktur [Rectangle](../../com.aspose.drawing/rectangle) dengan lokasi dan ukuran yang sama dengan struktur [Rectangle](../../com.aspose.drawing/rectangle) ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | java.lang.Object | Objek yang akan diuji. |

**Returns:**
boolean - Metode ini mengembalikan `true` jika obj adalah struktur [Rectangle](../../com.aspose.drawing/rectangle) dan properti X, Y, Width, serta Height‑nya sama dengan properti yang bersesuaian pada struktur [Rectangle](../../com.aspose.drawing/rectangle) ini; selainnya, `false`.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Mengembalikan kode hash untuk struktur [Rectangle](../../com.aspose.drawing/rectangle) ini. Untuk informasi tentang penggunaan kode hash, lihat GetHashCode.

**Returns:**
int - Bilangan bulat yang mewakili kode hash untuk persegi panjang ini.
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### intersect(Rectangle rect) {#intersect-com.aspose.drawing.Rectangle-}
```
public final void intersect(Rectangle rect)
```


Mengganti [Rectangle](../../com.aspose.drawing/rectangle) ini dengan irisan antara dirinya sendiri dan [Rectangle](../../com.aspose.drawing/rectangle) yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | [Rectangle](../../com.aspose.drawing/rectangle) yang akan diinterseksikan. |

### inflate(int width, int height) {#inflate-int-int-}
```
public final void inflate(int width, int height)
```


Memperbesar [Rectangle](../../com.aspose.drawing/rectangle) ini sebesar jumlah yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| width | int | Jumlah untuk memperluas [Rectangle](../../com.aspose.drawing/rectangle) ini secara horizontal. |
| height | int | Jumlah untuk memperluas [Rectangle](../../com.aspose.drawing/rectangle) ini secara vertikal. |

### inflate(Size size) {#inflate-com.aspose.drawing.Size-}
```
public final void inflate(Size size)
```


Memperbesar [Rectangle](../../com.aspose.drawing/rectangle) ini sebesar jumlah yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| size | [Size](../../com.aspose.drawing/size) | Ukuran untuk memperluas [Rectangle](../../com.aspose.drawing/rectangle) ini. |

### contains(int x, int y) {#contains-int-int-}
```
public final boolean contains(int x, int y)
```


Menentukan apakah titik yang ditentukan berada di dalam struktur [Rectangle](../../com.aspose.drawing/rectangle) ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | int | Koordinat x dari titik yang akan diuji. |
| y | int | Koordinat y dari titik yang akan diuji. |

**Returns:**
boolean - Metode ini mengembalikan `true` jika titik yang didefinisikan oleh `x` dan `y` berada di dalam struktur [Rectangle](../../com.aspose.drawing/rectangle) ini; selainnya `false`.
### contains(Point pt) {#contains-com.aspose.drawing.Point-}
```
public final boolean contains(Point pt)
```


Menentukan apakah titik yang ditentukan berada di dalam struktur [Rectangle](../../com.aspose.drawing/rectangle) ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pt | [Point](../../com.aspose.drawing/point) | [Point](../../com.aspose.drawing/point) yang akan diuji. |

**Returns:**
boolean - Metode ini mengembalikan `true` jika titik yang direpresentasikan oleh `pt` berada di dalam struktur [Rectangle](../../com.aspose.drawing/rectangle) ini; selainnya `false`.
### contains(Rectangle rect) {#contains-com.aspose.drawing.Rectangle-}
```
public final boolean contains(Rectangle rect)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) |  |

**Returns:**
boolean
### intersectsWith(Rectangle rect) {#intersectsWith-com.aspose.drawing.Rectangle-}
```
public final boolean intersectsWith(Rectangle rect)
```


Menentukan apakah persegi panjang ini berpotongan dengan `rect`.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | Persegi panjang untuk diuji. |

**Returns:**
boolean - Metode ini mengembalikan true jika ada interseksi apa pun, selainnya false.
### offset(int x, int y) {#offset-int-int-}
```
public final void offset(int x, int y)
```


Menyesuaikan lokasi persegi panjang ini sebesar jumlah yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | int | Offset horizontal. |
| y | int | Offset vertikal. |

### offset(Point pos) {#offset-com.aspose.drawing.Point-}
```
public final void offset(Point pos)
```


Menyesuaikan lokasi persegi panjang ini sebesar jumlah yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pos | [Point](../../com.aspose.drawing/point) | Offset. |

### equals(Rectangle other) {#equals-com.aspose.drawing.Rectangle-}
```
public final boolean equals(Rectangle other)
```


Menguji apakah struktur [Rectangle](../../com.aspose.drawing/rectangle) lain memiliki lokasi dan ukuran yang sama dengan struktur [Rectangle](../../com.aspose.drawing/rectangle) ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| other | [Rectangle](../../com.aspose.drawing/rectangle) | Persegi panjang lain untuk diuji |

**Returns:**
boolean - Metode ini mengembalikan `true` jika struktur [Rectangle](../../com.aspose.drawing/rectangle) lain dan properti X, Y, Width, serta Height‑nya sama dengan properti yang bersesuaian pada struktur [Rectangle](../../com.aspose.drawing/rectangle) ini; selainnya, `false`.
### CloneTo(Rectangle that) {#CloneTo-com.aspose.drawing.Rectangle-}
```
public void CloneTo(Rectangle that)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| that | [Rectangle](../../com.aspose.drawing/rectangle) |  |

### Clone() {#Clone--}
```
public Rectangle Clone()
```




**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle)
### clone() {#clone--}
```
public Object clone()
```




**Returns:**
java.lang.Object
### normalize() {#normalize--}
```
public void normalize()
```


Menormalkan persegi panjang dengan membuat lebar dan tinggi menjadi positif, kiri lebih kecil dari kanan, dan atas lebih kecil dari bawah.

