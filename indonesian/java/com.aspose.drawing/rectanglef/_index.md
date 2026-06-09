---
title: RectangleF
second_title: Referensi API Aspose.Drawing for Java
description: Menyimpan sekumpulan empat angka floating-point yang mewakili lokasi dan ukuran sebuah persegi panjang.
type: docs
weight: 39
url: /id/java/com.aspose.drawing/rectanglef/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable, java.lang.Cloneable
```
public class RectangleF extends Struct<RectangleF> implements System.IEquatable<RectangleF>, Cloneable
```

Menyimpan sekumpulan empat angka floating-point yang mewakili lokasi dan ukuran sebuah persegi panjang. Untuk fungsi wilayah yang lebih maju, gunakan objek Region.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [RectangleF()](#RectangleF--) |  |
| [RectangleF(PointF location, SizeF size)](#RectangleF-com.aspose.drawing.PointF-com.aspose.drawing.SizeF-) | Menginisialisasi instance baru dari struktur RectangleF dengan lokasi dan ukuran yang ditentukan. |
| [RectangleF(float x, float y, float width, float height)](#RectangleF-float-float-float-float-) | Menginisialisasi instance baru dari struktur RectangleF dengan lokasi dan ukuran yang ditentukan. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [fromPoints(PointF point1, PointF point2)](#fromPoints-com.aspose.drawing.PointF-com.aspose.drawing.PointF-) | Membuat persegi panjang baru dari dua titik. |
| [to_RectangleF(Rectangle r)](#to-RectangleF-com.aspose.drawing.Rectangle-) | Mengonversi struktur Rectangle yang ditentukan menjadi struktur RectangleF. |
| [op_Equality(RectangleF left, RectangleF right)](#op-Equality-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-) | Menguji apakah dua struktur [RectangleF](../../com.aspose.drawing/rectanglef) memiliki lokasi dan ukuran yang sama. |
| [op_Inequality(RectangleF left, RectangleF right)](#op-Inequality-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-) | Menguji apakah dua struktur [RectangleF](../../com.aspose.drawing/rectanglef) berbeda dalam lokasi atau ukuran. |
| [fromLTRB(float left, float top, float right, float bottom)](#fromLTRB-float-float-float-float-) | Membuat struktur RectangleF dengan sudut kiri-atas dan sudut kanan-bawah pada lokasi yang ditentukan. |
| [inflate(RectangleF rect, float x, float y)](#inflate-com.aspose.drawing.RectangleF-float-float-) | Membuat dan mengembalikan salinan yang diperbesar dari struktur [RectangleF](../../com.aspose.drawing/rectanglef) yang ditentukan. |
| [intersect(RectangleF a, RectangleF b)](#intersect-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-) | Mengembalikan struktur [RectangleF](../../com.aspose.drawing/rectanglef) yang mewakili irisan dua persegi panjang. |
| [union(RectangleF a, RectangleF b)](#union-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-) | Membuat persegi panjang ketiga terkecil yang dapat memuat kedua persegi panjang yang membentuk gabungan. |
| [isEquals(RectangleF obj1, RectangleF obj2)](#isEquals-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-) |  |
| [getEmpty()](#getEmpty--) |  |
| [isEmpty()](#isEmpty--) | Mendapatkan nilai yang menunjukkan apakah properti `RectangleF.Width` atau `RectangleF.Height` dari [RectangleF](../../com.aspose.drawing/rectanglef) ini memiliki nilai nol. |
| [getX()](#getX--) | Mendapatkan koordinat x dari sudut kiri-atas struktur RectangleF ini. |
| [setX(float value)](#setX-float-) | Mengatur koordinat x dari sudut kiri-atas struktur RectangleF ini. |
| [getY()](#getY--) | Mendapatkan koordinat x dari sudut kiri-atas struktur RectangleF ini. |
| [setY(float value)](#setY-float-) | Mengatur koordinat x dari sudut kiri-atas struktur RectangleF ini. |
| [getLocation()](#getLocation--) | Mendapatkan koordinat sudut kiri-atas dari struktur [RectangleF](../../com.aspose.drawing/rectanglef) ini. |
| [setLocation(PointF value)](#setLocation-com.aspose.drawing.PointF-) | Mengatur koordinat sudut kiri atas dari struktur [RectangleF](../../com.aspose.drawing/rectanglef) ini. |
| [getWidth()](#getWidth--) | Mendapatkan lebar dari struktur RectangleF ini. |
| [setWidth(float value)](#setWidth-float-) | Mengatur lebar dari struktur RectangleF ini. |
| [getHeight()](#getHeight--) | Mendapatkan tinggi dari struktur RectangleF ini. |
| [setHeight(float value)](#setHeight-float-) | Mengatur tinggi dari struktur RectangleF ini. |
| [getSize()](#getSize--) | Mendapatkan ukuran dari [RectangleF](../../com.aspose.drawing/rectanglef) ini. |
| [setSize(SizeF value)](#setSize-com.aspose.drawing.SizeF-) | Mengatur ukuran dari [RectangleF](../../com.aspose.drawing/rectanglef) ini. |
| [getLeft()](#getLeft--) | Mendapatkan koordinat x dari tepi kiri struktur RectangleF ini. |
| [getTop()](#getTop--) | Mendapatkan koordinat y dari tepi atas struktur RectangleF ini. |
| [getRight()](#getRight--) | Mendapatkan koordinat x yang merupakan hasil penjumlahan X dan Width dari struktur RectangleF ini. |
| [getBottom()](#getBottom--) | Mendapatkan koordinat y yang merupakan hasil penjumlahan Y dan Height dari struktur RectangleF ini. |
| [toString()](#toString--) |  |
| [inflate(float x, float y)](#inflate-float-float-) | Mengembangkan struktur [RectangleF](../../com.aspose.drawing/rectanglef) ini sebesar jumlah yang ditentukan. |
| [inflate(SizeF size)](#inflate-com.aspose.drawing.SizeF-) | Mengembangkan [RectangleF](../../com.aspose.drawing/rectanglef) ini sebesar jumlah yang ditentukan. |
| [intersect(RectangleF rect)](#intersect-com.aspose.drawing.RectangleF-) | Mengganti struktur [RectangleF](../../com.aspose.drawing/rectanglef) ini dengan irisan antara dirinya sendiri dan struktur [RectangleF](../../com.aspose.drawing/rectanglef) yang ditentukan. |
| [intersectsWith(RectangleF rect)](#intersectsWith-com.aspose.drawing.RectangleF-) | Menentukan apakah persegi panjang ini berpotongan dengan `rect`. |
| [offset(PointF pos)](#offset-com.aspose.drawing.PointF-) | Menyesuaikan lokasi persegi panjang ini sebesar jumlah yang ditentukan. |
| [offset(float x, float y)](#offset-float-float-) | Menyesuaikan lokasi persegi panjang ini sebesar jumlah yang ditentukan. |
| [contains(float x, float y)](#contains-float-float-) | Menentukan apakah titik yang ditentukan berada di dalam struktur [RectangleF](../../com.aspose.drawing/rectanglef) ini. |
| [contains(PointF pt)](#contains-com.aspose.drawing.PointF-) | Menentukan apakah titik yang ditentukan berada di dalam struktur [RectangleF](../../com.aspose.drawing/rectanglef) ini. |
| [contains(RectangleF rect)](#contains-com.aspose.drawing.RectangleF-) | Menentukan apakah wilayah persegi panjang yang direpresentasikan oleh `rect` sepenuhnya berada di dalam struktur [RectangleF](../../com.aspose.drawing/rectanglef) ini. |
| [equals(Object obj)](#equals-java.lang.Object-) | Menentukan apakah Objek yang ditentukan, sama dengan instance ini. |
| [hashCode()](#hashCode--) | Mengembalikan kode hash untuk instance ini. |
| [equals(RectangleF other)](#equals-com.aspose.drawing.RectangleF-) | Menguji apakah struktur [RectangleF](../../com.aspose.drawing/rectanglef) lain memiliki lokasi dan ukuran yang sama dengan struktur [RectangleF](../../com.aspose.drawing/rectanglef) ini. |
| [CloneTo(RectangleF that)](#CloneTo-com.aspose.drawing.RectangleF-) |  |
| [Clone()](#Clone--) |  |
| [clone()](#clone--) |  |
### RectangleF() {#RectangleF--}
```
public RectangleF()
```


### RectangleF(PointF location, SizeF size) {#RectangleF-com.aspose.drawing.PointF-com.aspose.drawing.SizeF-}
```
public RectangleF(PointF location, SizeF size)
```


Menginisialisasi instance baru dari struktur RectangleF dengan lokasi dan ukuran yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| location | [PointF](../../com.aspose.drawing/pointf) | PointF yang merepresentasikan sudut kiri atas wilayah persegi panjang. |
| size | [SizeF](../../com.aspose.drawing/sizef) | SizeF yang merepresentasikan lebar dan tinggi wilayah persegi panjang. |

### RectangleF(float x, float y, float width, float height) {#RectangleF-float-float-float-float-}
```
public RectangleF(float x, float y, float width, float height)
```


Menginisialisasi instance baru dari struktur RectangleF dengan lokasi dan ukuran yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | float | Koordinat x dari sudut kiri atas persegi panjang. |
| y | float | Koordinat y dari sudut kiri atas persegi panjang. |
| lebar | float | Lebar persegi panjang. |
| tinggi | float | Tinggi persegi panjang. |

### fromPoints(PointF point1, PointF point2) {#fromPoints-com.aspose.drawing.PointF-com.aspose.drawing.PointF-}
```
public static RectangleF fromPoints(PointF point1, PointF point2)
```


Membuat persegi panjang baru dari dua titik. Persegi panjang yang dibuat akan dinormalisasi dengan (kiri,atas) lebih rendah daripada (kanan,bawah).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| point1 | [PointF](../../com.aspose.drawing/pointf) | Titik pertama. |
| point2 | [PointF](../../com.aspose.drawing/pointf) | Titik kedua. |

**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef) - A newly created rectangle.
### to_RectangleF(Rectangle r) {#to-RectangleF-com.aspose.drawing.Rectangle-}
```
public static RectangleF to_RectangleF(Rectangle r)
```


Mengonversi struktur Rectangle yang ditentukan menjadi struktur RectangleF.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| r | [Rectangle](../../com.aspose.drawing/rectangle) | Struktur Rectangle untuk dikonversi. |

**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef) - The RectangleF structure that is converted from the specified Rectangle structure.
### op_Equality(RectangleF left, RectangleF right) {#op-Equality-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-}
```
public static boolean op_Equality(RectangleF left, RectangleF right)
```


Menguji apakah dua struktur [RectangleF](../../com.aspose.drawing/rectanglef) memiliki lokasi dan ukuran yang sama.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| left | [RectangleF](../../com.aspose.drawing/rectanglef) | Struktur [RectangleF](../../com.aspose.drawing/rectanglef) yang berada di sebelah kiri operator kesetaraan. |
| right | [RectangleF](../../com.aspose.drawing/rectanglef) | Struktur [RectangleF](../../com.aspose.drawing/rectanglef) yang berada di sebelah kanan operator kesetaraan. |

**Returns:**
boolean - Operator ini mengembalikan true jika dua struktur [RectangleF](../../com.aspose.drawing/rectanglef) yang ditentukan memiliki properti `RectangleF.X`, `RectangleF.Y`, `RectangleF.Width`, dan `RectangleF.Height` yang sama.
### op_Inequality(RectangleF left, RectangleF right) {#op-Inequality-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-}
```
public static boolean op_Inequality(RectangleF left, RectangleF right)
```


Menguji apakah dua struktur [RectangleF](../../com.aspose.drawing/rectanglef) berbeda dalam lokasi atau ukuran.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| left | [RectangleF](../../com.aspose.drawing/rectanglef) | Struktur [RectangleF](../../com.aspose.drawing/rectanglef) yang berada di sebelah kiri operator ketidaksamaan. |
| right | [RectangleF](../../com.aspose.drawing/rectanglef) | Struktur [RectangleF](../../com.aspose.drawing/rectanglef) yang berada di sebelah kanan operator ketidaksamaan. |

**Returns:**
boolean - Operator ini mengembalikan true jika salah satu properti `RectangleF.X`, `RectangleF.Y`, `RectangleF.Width`, atau `RectangleF.Height` dari dua struktur [Rectangle](../../com.aspose.drawing/rectangle) tidak sama; jika tidak false.
### fromLTRB(float left, float top, float right, float bottom) {#fromLTRB-float-float-float-float-}
```
public static RectangleF fromLTRB(float left, float top, float right, float bottom)
```


Membuat struktur RectangleF dengan sudut kiri-atas dan sudut kanan-bawah pada lokasi yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| kiri | float | Koordinat x dari sudut kiri atas wilayah persegi panjang. |
| atas | float | Koordinat y dari sudut kiri atas wilayah persegi panjang. |
| kanan | float | Koordinat x dari sudut kanan bawah wilayah persegi panjang. |
| bawah | float | Koordinat y dari sudut kanan bawah wilayah persegi panjang. |

**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef) - The new RectangleF that this method creates.
### inflate(RectangleF rect, float x, float y) {#inflate-com.aspose.drawing.RectangleF-float-float-}
```
public static RectangleF inflate(RectangleF rect, float x, float y)
```


Membuat dan mengembalikan salinan yang diperbesar dari struktur [RectangleF](../../com.aspose.drawing/rectanglef) yang ditentukan. Salinan tersebut diperbesar sebesar jumlah yang ditentukan. Persegi panjang asli tetap tidak berubah.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | [RectangleF](../../com.aspose.drawing/rectanglef) yang akan disalin. Persegi panjang ini tidak diubah. |
| x | float | Jumlah untuk memperbesar salinan persegi panjang secara horizontal. |
| y | float | Jumlah untuk memperbesar salinan persegi panjang secara vertikal. |

**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef) - The inflated [RectangleF](../../com.aspose.drawing/rectanglef).
### intersect(RectangleF a, RectangleF b) {#intersect-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-}
```
public static RectangleF intersect(RectangleF a, RectangleF b)
```


Mengembalikan struktur [RectangleF](../../com.aspose.drawing/rectanglef) yang mewakili irisan dua persegi panjang. Jika tidak ada irisan, sebuah [RectangleF](../../com.aspose.drawing/rectanglef) kosong dikembalikan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| a | [RectangleF](../../com.aspose.drawing/rectanglef) | Persegi panjang pertama untuk diiris. |
| b | [RectangleF](../../com.aspose.drawing/rectanglef) | Persegi panjang kedua untuk diiris. |

**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef) - A third [RectangleF](../../com.aspose.drawing/rectanglef) structure the size of which represents the overlapped area of the two specified rectangles.
### union(RectangleF a, RectangleF b) {#union-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-}
```
public static RectangleF union(RectangleF a, RectangleF b)
```


Membuat persegi panjang ketiga terkecil yang dapat memuat kedua persegi panjang yang membentuk gabungan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| a | [RectangleF](../../com.aspose.drawing/rectanglef) | Persegi panjang pertama untuk digabungkan. |
| b | [RectangleF](../../com.aspose.drawing/rectanglef) | Persegi panjang kedua untuk digabungkan. |

**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef) - A third [RectangleF](../../com.aspose.drawing/rectanglef) structure that contains both of the two rectangles that form the union.
### isEquals(RectangleF obj1, RectangleF obj2) {#isEquals-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-}
```
public static boolean isEquals(RectangleF obj1, RectangleF obj2)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj1 | [RectangleF](../../com.aspose.drawing/rectanglef) |  |
| obj2 | [RectangleF](../../com.aspose.drawing/rectanglef) |  |

**Returns:**
boolean
### getEmpty() {#getEmpty--}
```
public static RectangleF getEmpty()
```




**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef)
### isEmpty() {#isEmpty--}
```
public final boolean isEmpty()
```


Mendapatkan nilai yang menunjukkan apakah properti `RectangleF.Width` atau `RectangleF.Height` dari [RectangleF](../../com.aspose.drawing/rectanglef) ini memiliki nilai nol.

**Returns:**
boolean - Properti ini mengembalikan true jika properti `RectangleF.Width` atau `P:RectangleF.Height` dari [RectangleF](../../com.aspose.drawing/rectanglef) ini memiliki nilai nol; jika tidak, false.
### getX() {#getX--}
```
public final float getX()
```


Mendapatkan koordinat x dari sudut kiri-atas struktur RectangleF ini.

**Returns:**
float - koordinat x dari sudut kiri atas struktur RectangleF ini.
### setX(float value) {#setX-float-}
```
public final void setX(float value)
```


Mengatur koordinat x dari sudut kiri-atas struktur RectangleF ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float | koordinat x dari sudut kiri atas struktur RectangleF ini. |

### getY() {#getY--}
```
public final float getY()
```


Mendapatkan koordinat x dari sudut kiri-atas struktur RectangleF ini.

**Returns:**
float - koordinat x dari sudut kiri atas struktur RectangleF ini.
### setY(float value) {#setY-float-}
```
public final void setY(float value)
```


Mengatur koordinat x dari sudut kiri-atas struktur RectangleF ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float | koordinat x dari sudut kiri atas struktur RectangleF ini. |

### getLocation() {#getLocation--}
```
public final PointF getLocation()
```


Mendapatkan koordinat sudut kiri-atas dari struktur [RectangleF](../../com.aspose.drawing/rectanglef) ini.

**Returns:**
[PointF](../../com.aspose.drawing/pointf) - A [PointF](../../com.aspose.drawing/pointf) that represents the upper-left corner of this [RectangleF](../../com.aspose.drawing/rectanglef) structure.
### setLocation(PointF value) {#setLocation-com.aspose.drawing.PointF-}
```
public final void setLocation(PointF value)
```


Mengatur koordinat sudut kiri atas dari struktur [RectangleF](../../com.aspose.drawing/rectanglef) ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [PointF](../../com.aspose.drawing/pointf) | koordinat sudut kiri atas struktur [RectangleF](../../com.aspose.drawing/rectanglef) ini. |

### getWidth() {#getWidth--}
```
public final float getWidth()
```


Mendapatkan lebar dari struktur RectangleF ini.

**Returns:**
float - lebar dari struktur RectangleF ini.
### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```


Mengatur lebar dari struktur RectangleF ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float | lebar dari struktur RectangleF ini. |

### getHeight() {#getHeight--}
```
public final float getHeight()
```


Mendapatkan tinggi dari struktur RectangleF ini.

**Returns:**
float - tinggi dari struktur RectangleF ini.
### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```


Mengatur tinggi dari struktur RectangleF ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float | tinggi dari struktur RectangleF ini. |

### getSize() {#getSize--}
```
public final SizeF getSize()
```


Mendapatkan ukuran dari [RectangleF](../../com.aspose.drawing/rectanglef) ini.

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - A [SizeF](../../com.aspose.drawing/sizef) that represents the width and height of this [RectangleF](../../com.aspose.drawing/rectanglef) structure.
### setSize(SizeF value) {#setSize-com.aspose.drawing.SizeF-}
```
public final void setSize(SizeF value)
```


Mengatur ukuran dari [RectangleF](../../com.aspose.drawing/rectanglef) ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.drawing/sizef) | ukuran dari [RectangleF](../../com.aspose.drawing/rectanglef) ini. |

### getLeft() {#getLeft--}
```
public final float getLeft()
```


Mendapatkan koordinat x dari tepi kiri struktur RectangleF ini.

**Returns:**
float - koordinat x dari tepi kiri struktur RectangleF ini.
### getTop() {#getTop--}
```
public final float getTop()
```


Mendapatkan koordinat y dari tepi atas struktur RectangleF ini.

**Returns:**
float - koordinat y dari tepi atas struktur RectangleF ini.
### getRight() {#getRight--}
```
public final float getRight()
```


Mendapatkan koordinat x yang merupakan hasil penjumlahan X dan Width dari struktur RectangleF ini.

**Returns:**
float - koordinat x yang merupakan hasil penjumlahan X dan Width dari struktur RectangleF ini.
### getBottom() {#getBottom--}
```
public final float getBottom()
```


Mendapatkan koordinat y yang merupakan hasil penjumlahan Y dan Height dari struktur RectangleF ini.

**Returns:**
float - koordinat y yang merupakan hasil penjumlahan Y dan Height dari struktur RectangleF ini.
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### inflate(float x, float y) {#inflate-float-float-}
```
public final void inflate(float x, float y)
```


Mengembangkan struktur [RectangleF](../../com.aspose.drawing/rectanglef) ini sebesar jumlah yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | float | Jumlah untuk memperbesar struktur [RectangleF](../../com.aspose.drawing/rectanglef) ini secara horizontal. |
| y | float | Jumlah untuk memperbesar struktur [RectangleF](../../com.aspose.drawing/rectanglef) ini secara vertikal. |

### inflate(SizeF size) {#inflate-com.aspose.drawing.SizeF-}
```
public final void inflate(SizeF size)
```


Mengembangkan [RectangleF](../../com.aspose.drawing/rectanglef) ini sebesar jumlah yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.drawing/sizef) | Jumlah untuk memperbesar persegi panjang ini. |

### intersect(RectangleF rect) {#intersect-com.aspose.drawing.RectangleF-}
```
public final void intersect(RectangleF rect)
```


Mengganti struktur [RectangleF](../../com.aspose.drawing/rectanglef) ini dengan irisan antara dirinya sendiri dan struktur [RectangleF](../../com.aspose.drawing/rectanglef) yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | Persegi panjang untuk diiris. |

### intersectsWith(RectangleF rect) {#intersectsWith-com.aspose.drawing.RectangleF-}
```
public final boolean intersectsWith(RectangleF rect)
```


Menentukan apakah persegi panjang ini berpotongan dengan `rect`.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | Persegi panjang untuk diuji. |

**Returns:**
boolean - Metode ini mengembalikan true jika ada irisan apapun.
### offset(PointF pos) {#offset-com.aspose.drawing.PointF-}
```
public final void offset(PointF pos)
```


Menyesuaikan lokasi persegi panjang ini sebesar jumlah yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pos | [PointF](../../com.aspose.drawing/pointf) | Jumlah untuk menggeser lokasi. |

### offset(float x, float y) {#offset-float-float-}
```
public final void offset(float x, float y)
```


Menyesuaikan lokasi persegi panjang ini sebesar jumlah yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | float | Jumlah untuk menggeser lokasi secara horizontal. |
| y | float | Jumlah untuk menggeser lokasi secara vertikal. |

### contains(float x, float y) {#contains-float-float-}
```
public final boolean contains(float x, float y)
```


Menentukan apakah titik yang ditentukan berada di dalam struktur [RectangleF](../../com.aspose.drawing/rectanglef) ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | float | Koordinat x dari titik yang akan diuji. |
| y | float | Koordinat y dari titik yang akan diuji. |

**Returns:**
boolean - Metode ini mengembalikan `true` jika titik yang didefinisikan oleh x dan y berada dalam struktur [RectangleF](../../com.aspose.drawing/rectanglef) ini; jika tidak `false`.
### contains(PointF pt) {#contains-com.aspose.drawing.PointF-}
```
public final boolean contains(PointF pt)
```


Menentukan apakah titik yang ditentukan berada di dalam struktur [RectangleF](../../com.aspose.drawing/rectanglef) ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pt | [PointF](../../com.aspose.drawing/pointf) | [PointF](../../com.aspose.drawing/pointf) yang akan diuji. |

**Returns:**
boolean - Metode ini mengembalikan `true` jika titik yang direpresentasikan oleh parameter pt berada dalam struktur [RectangleF](../../com.aspose.drawing/rectanglef) ini; jika tidak `false`.
### contains(RectangleF rect) {#contains-com.aspose.drawing.RectangleF-}
```
public final boolean contains(RectangleF rect)
```


Menentukan apakah wilayah persegi panjang yang direpresentasikan oleh `rect` sepenuhnya berada di dalam struktur [RectangleF](../../com.aspose.drawing/rectanglef) ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | [RectangleF](../../com.aspose.drawing/rectanglef) yang akan diuji. |

**Returns:**
boolean - Metode ini mengembalikan `true` jika wilayah persegi panjang yang direpresentasikan oleh `rect` sepenuhnya berada dalam wilayah persegi panjang yang direpresentasikan oleh [RectangleF](../../com.aspose.drawing/rectanglef) ini; jika tidak `false`.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Menentukan apakah Objek yang ditentukan, sama dengan instance ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | java.lang.Object | Objek untuk dibandingkan dengan instance ini. |

**Returns:**
boolean - `true` jika Objek yang ditentukan sama dengan instance ini; jika tidak, `false`.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Mengembalikan kode hash untuk instance ini.

**Returns:**
int - Kode hash untuk instance ini, cocok untuk digunakan dalam algoritma hashing dan struktur data seperti tabel hash.
### equals(RectangleF other) {#equals-com.aspose.drawing.RectangleF-}
```
public final boolean equals(RectangleF other)
```


Menguji apakah struktur [RectangleF](../../com.aspose.drawing/rectanglef) lain memiliki lokasi dan ukuran yang sama dengan struktur [RectangleF](../../com.aspose.drawing/rectanglef) ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| other | [RectangleF](../../com.aspose.drawing/rectanglef) | Persegi panjang lain untuk diuji |

**Returns:**
boolean - Metode ini mengembalikan `true` jika struktur [RectangleF](../../com.aspose.drawing/rectanglef) lain dan properti X, Y, Width, serta Height-nya sama dengan properti yang bersesuaian pada struktur [RectangleF](../../com.aspose.drawing/rectanglef) ini; jika tidak, `false`.
### CloneTo(RectangleF that) {#CloneTo-com.aspose.drawing.RectangleF-}
```
public void CloneTo(RectangleF that)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| that | [RectangleF](../../com.aspose.drawing/rectanglef) |  |

### Clone() {#Clone--}
```
public RectangleF Clone()
```




**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef)
### clone() {#clone--}
```
public Object clone()
```




**Returns:**
java.lang.Object
