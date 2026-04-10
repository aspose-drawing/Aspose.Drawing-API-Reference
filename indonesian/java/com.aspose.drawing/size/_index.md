---
title: Size
second_title: Referensi API Aspose.Drawing for Java
description: Menyimpan sepasang bilangan bulat berurutan yang biasanya merupakan lebar dan tinggi sebuah persegi panjang.
type: docs
weight: 42
url: /id/java/com.aspose.drawing/size/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable, java.lang.Cloneable
```
public class Size extends Struct<Size> implements System.IEquatable<Size>, Cloneable
```

Menyimpan pasangan terurut dari integer, biasanya lebar dan tinggi sebuah persegi panjang.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [Size()](#Size--) |  |
| [Size(Point pt)](#Size-com.aspose.drawing.Point-) | Menginisialisasi instance baru dari struct [Size](../../com.aspose.drawing/size) dari [Point](../../com.aspose.drawing/point) yang ditentukan. |
| [Size(int width, int height)](#Size-int-int-) | Menginisialisasi instance baru dari struct [Size](../../com.aspose.drawing/size) dari dimensi yang ditentukan. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [to_SizeF(Size p)](#to-SizeF-com.aspose.drawing.Size-) | Mengonversi [Size](../../com.aspose.drawing/size) yang ditentukan menjadi [SizeF](../../com.aspose.drawing/sizef). |
| [op_Addition(Size sz1, Size sz2)](#op-Addition-com.aspose.drawing.Size-com.aspose.drawing.Size-) | Menambahkan lebar dan tinggi satu struktur [Size](../../com.aspose.drawing/size) ke lebar dan tinggi struktur [Size](../../com.aspose.drawing/size) lainnya. |
| [op_Subtraction(Size sz1, Size sz2)](#op-Subtraction-com.aspose.drawing.Size-com.aspose.drawing.Size-) | Mengurangi lebar dan tinggi satu struktur [Size](../../com.aspose.drawing/size) dari lebar dan tinggi struktur [Size](../../com.aspose.drawing/size) lainnya. |
| [op_Multiply(int left, Size right)](#op-Multiply-int-com.aspose.drawing.Size-) | Mengalikan sebuah [Size](../../com.aspose.drawing/size) dengan `int` menghasilkan [Size](../../com.aspose.drawing/size). |
| [op_Multiply(Size left, int right)](#op-Multiply-com.aspose.drawing.Size-int-) | Mengalikan [Size](../../com.aspose.drawing/size) dengan `int` menghasilkan [Size](../../com.aspose.drawing/size). |
| [op_Division(Size left, int right)](#op-Division-com.aspose.drawing.Size-int-) | Membagi [Size](../../com.aspose.drawing/size) dengan `int` menghasilkan [Size](../../com.aspose.drawing/size). |
| [op_Multiply(float left, Size right)](#op-Multiply-float-com.aspose.drawing.Size-) | Mengalikan [Size](../../com.aspose.drawing/size) dengan `float` menghasilkan [SizeF](../../com.aspose.drawing/sizef). |
| [op_Multiply(Size left, float right)](#op-Multiply-com.aspose.drawing.Size-float-) | Mengalikan [Size](../../com.aspose.drawing/size) dengan `float` menghasilkan [SizeF](../../com.aspose.drawing/sizef). |
| [op_Division(Size left, float right)](#op-Division-com.aspose.drawing.Size-float-) | Membagi [Size](../../com.aspose.drawing/size) dengan `float` menghasilkan [SizeF](../../com.aspose.drawing/sizef). |
| [op_Equality(Size sz1, Size sz2)](#op-Equality-com.aspose.drawing.Size-com.aspose.drawing.Size-) | Memeriksa apakah dua struktur [Size](../../com.aspose.drawing/size) sama. |
| [op_Inequality(Size sz1, Size sz2)](#op-Inequality-com.aspose.drawing.Size-com.aspose.drawing.Size-) | Memeriksa apakah dua struktur [Size](../../com.aspose.drawing/size) berbeda. |
| [to_Point(Size size)](#to-Point-com.aspose.drawing.Size-) | Mengonversi [Size](../../com.aspose.drawing/size) yang ditentukan menjadi [Point](../../com.aspose.drawing/point). |
| [add(Size sz1, Size sz2)](#add-com.aspose.drawing.Size-com.aspose.drawing.Size-) | Menambahkan lebar dan tinggi satu struktur [Size](../../com.aspose.drawing/size) ke lebar dan tinggi struktur [Size](../../com.aspose.drawing/size) lainnya. |
| [ceiling(SizeF value)](#ceiling-com.aspose.drawing.SizeF-) | Mengonversi struktur [SizeF](../../com.aspose.drawing/sizef) yang ditentukan menjadi struktur [Size](../../com.aspose.drawing/size) dengan membulatkan nilai-nilai struktur [Size](../../com.aspose.drawing/size) ke nilai integer berikutnya yang lebih tinggi. |
| [subtract(Size sz1, Size sz2)](#subtract-com.aspose.drawing.Size-com.aspose.drawing.Size-) | Mengurangi lebar dan tinggi satu struktur [Size](../../com.aspose.drawing/size) dari lebar dan tinggi struktur [Size](../../com.aspose.drawing/size) lainnya. |
| [truncate(SizeF value)](#truncate-com.aspose.drawing.SizeF-) | Mengonversi struktur [SizeF](../../com.aspose.drawing/sizef) yang ditentukan menjadi struktur [Size](../../com.aspose.drawing/size) dengan memotong nilai-nilai struktur [SizeF](../../com.aspose.drawing/sizef) ke nilai integer berikutnya yang lebih rendah. |
| [round(SizeF value)](#round-com.aspose.drawing.SizeF-) | Mengonversi struktur [SizeF](../../com.aspose.drawing/sizef) yang ditentukan menjadi struktur [Size](../../com.aspose.drawing/size) dengan membulatkan nilai-nilai struktur [SizeF](../../com.aspose.drawing/sizef) ke nilai integer terdekat. |
| [isEquals(Size obj1, Size obj2)](#isEquals-com.aspose.drawing.Size-com.aspose.drawing.Size-) |  |
| [getEmpty()](#getEmpty--) |  |
| [isEmpty()](#isEmpty--) | Mengambil nilai yang menunjukkan apakah [Size](../../com.aspose.drawing/size) ini memiliki lebar dan tinggi 0. |
| [getWidth()](#getWidth--) | Mengambil komponen horizontal dari [Size](../../com.aspose.drawing/size) ini. |
| [setWidth(int value)](#setWidth-int-) | Mengatur komponen horizontal dari [Size](../../com.aspose.drawing/size) ini. |
| [getHeight()](#getHeight--) | Mengambil komponen vertikal dari [Size](../../com.aspose.drawing/size) ini. |
| [setHeight(int value)](#setHeight-int-) | Mengatur komponen vertikal dari [Size](../../com.aspose.drawing/size) ini. |
| [equals(Object obj)](#equals-java.lang.Object-) | Memeriksa apakah objek yang ditentukan adalah [Size](../../com.aspose.drawing/size) dengan dimensi yang sama dengan [Size](../../com.aspose.drawing/size) ini. |
| [hashCode()](#hashCode--) | Mengembalikan kode hash untuk struktur [Size](../../com.aspose.drawing/size) ini. |
| [toString()](#toString--) |  |
| [equals(Size other)](#equals-com.aspose.drawing.Size-) | Memeriksa apakah struktur [Size](../../com.aspose.drawing/size) lain memiliki ukuran yang sama dengan struktur [Size](../../com.aspose.drawing/size) ini. |
| [CloneTo(Size that)](#CloneTo-com.aspose.drawing.Size-) |  |
| [Clone()](#Clone--) |  |
| [clone()](#clone--) |  |
### Size() {#Size--}
```
public Size()
```


### Size(Point pt) {#Size-com.aspose.drawing.Point-}
```
public Size(Point pt)
```


Menginisialisasi instance baru dari struct [Size](../../com.aspose.drawing/size) dari [Point](../../com.aspose.drawing/point) yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pt | [Point](../../com.aspose.drawing/point) | [Point](../../com.aspose.drawing/point) yang digunakan untuk menginisialisasi [Size](../../com.aspose.drawing/size) ini. |

### Size(int width, int height) {#Size-int-int-}
```
public Size(int width, int height)
```


Menginisialisasi instance baru dari struct [Size](../../com.aspose.drawing/size) dari dimensi yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| width | int | Komponen lebar dari [Size](../../com.aspose.drawing/size) baru. |
| height | int | Komponen tinggi dari [Size](../../com.aspose.drawing/size) baru. |

### to_SizeF(Size p) {#to-SizeF-com.aspose.drawing.Size-}
```
public static SizeF to_SizeF(Size p)
```


Mengonversi [Size](../../com.aspose.drawing/size) yang ditentukan menjadi [SizeF](../../com.aspose.drawing/sizef).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| p | [Size](../../com.aspose.drawing/size) | [Size](../../com.aspose.drawing/size) yang akan dikonversi. |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - The [SizeF](../../com.aspose.drawing/sizef) structure to which this operator converts.
### op_Addition(Size sz1, Size sz2) {#op-Addition-com.aspose.drawing.Size-com.aspose.drawing.Size-}
```
public static Size op_Addition(Size sz1, Size sz2)
```


Menambahkan lebar dan tinggi satu struktur [Size](../../com.aspose.drawing/size) ke lebar dan tinggi struktur [Size](../../com.aspose.drawing/size) lainnya.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sz1 | [Size](../../com.aspose.drawing/size) | [Size](../../com.aspose.drawing/size) pertama yang akan ditambahkan. |
| sz2 | [Size](../../com.aspose.drawing/size) | [Size](../../com.aspose.drawing/size) kedua yang akan ditambahkan. |

**Returns:**
[Size](../../com.aspose.drawing/size) - A [Size](../../com.aspose.drawing/size) structure that is the result of the addition operation.
### op_Subtraction(Size sz1, Size sz2) {#op-Subtraction-com.aspose.drawing.Size-com.aspose.drawing.Size-}
```
public static Size op_Subtraction(Size sz1, Size sz2)
```


Mengurangi lebar dan tinggi satu struktur [Size](../../com.aspose.drawing/size) dari lebar dan tinggi struktur [Size](../../com.aspose.drawing/size) lainnya.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sz1 | [Size](../../com.aspose.drawing/size) | Struktur [Size](../../com.aspose.drawing/size) di sisi kiri operator pengurangan. |
| sz2 | [Size](../../com.aspose.drawing/size) | Struktur [Size](../../com.aspose.drawing/size) di sisi kanan operator pengurangan. |

**Returns:**
[Size](../../com.aspose.drawing/size) - A [Size](../../com.aspose.drawing/size) structure that is the result of the subtraction operation.
### op_Multiply(int left, Size right) {#op-Multiply-int-com.aspose.drawing.Size-}
```
public static Size op_Multiply(int left, Size right)
```


Mengalikan sebuah [Size](../../com.aspose.drawing/size) dengan `int` menghasilkan [Size](../../com.aspose.drawing/size).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| kiri | int | Pengganda bertipe `int`. |
| right | [Size](../../com.aspose.drawing/size) | Pengkali bertipe [Size](../../com.aspose.drawing/size). |

**Returns:**
[Size](../../com.aspose.drawing/size) - Product of type [Size](../../com.aspose.drawing/size).
### op_Multiply(Size left, int right) {#op-Multiply-com.aspose.drawing.Size-int-}
```
public static Size op_Multiply(Size left, int right)
```


Mengalikan [Size](../../com.aspose.drawing/size) dengan `int` menghasilkan [Size](../../com.aspose.drawing/size).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| left | [Size](../../com.aspose.drawing/size) | Pengkali bertipe [Size](../../com.aspose.drawing/size). |
| kanan | int | Pengganda bertipe `int`. |

**Returns:**
[Size](../../com.aspose.drawing/size) - Product of type [Size](../../com.aspose.drawing/size).
### op_Division(Size left, int right) {#op-Division-com.aspose.drawing.Size-int-}
```
public static Size op_Division(Size left, int right)
```


Membagi [Size](../../com.aspose.drawing/size) dengan `int` menghasilkan [Size](../../com.aspose.drawing/size).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| left | [Size](../../com.aspose.drawing/size) | Dividen bertipe [Size](../../com.aspose.drawing/size). |
| kanan | int | Divisor bertipe `int`. |

**Returns:**
[Size](../../com.aspose.drawing/size) - Result of type [Size](../../com.aspose.drawing/size).
### op_Multiply(float left, Size right) {#op-Multiply-float-com.aspose.drawing.Size-}
```
public static SizeF op_Multiply(float left, Size right)
```


Mengalikan [Size](../../com.aspose.drawing/size) dengan `float` menghasilkan [SizeF](../../com.aspose.drawing/sizef).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| kiri | float | Pengganda bertipe `float`. |
| right | [Size](../../com.aspose.drawing/size) | Pengkali bertipe [Size](../../com.aspose.drawing/size). |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - Product of type [SizeF](../../com.aspose.drawing/sizef).
### op_Multiply(Size left, float right) {#op-Multiply-com.aspose.drawing.Size-float-}
```
public static SizeF op_Multiply(Size left, float right)
```


Mengalikan [Size](../../com.aspose.drawing/size) dengan `float` menghasilkan [SizeF](../../com.aspose.drawing/sizef).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| left | [Size](../../com.aspose.drawing/size) | Pengkali bertipe [Size](../../com.aspose.drawing/size). |
| kanan | float | Pengganda bertipe `float`. |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - Product of type [SizeF](../../com.aspose.drawing/sizef).
### op_Division(Size left, float right) {#op-Division-com.aspose.drawing.Size-float-}
```
public static SizeF op_Division(Size left, float right)
```


Membagi [Size](../../com.aspose.drawing/size) dengan `float` menghasilkan [SizeF](../../com.aspose.drawing/sizef).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| left | [Size](../../com.aspose.drawing/size) | Dividen bertipe [Size](../../com.aspose.drawing/size). |
| kanan | float | Divisor bertipe `int`. |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - Result of type [SizeF](../../com.aspose.drawing/sizef).
### op_Equality(Size sz1, Size sz2) {#op-Equality-com.aspose.drawing.Size-com.aspose.drawing.Size-}
```
public static boolean op_Equality(Size sz1, Size sz2)
```


Memeriksa apakah dua struktur [Size](../../com.aspose.drawing/size) sama.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sz1 | [Size](../../com.aspose.drawing/size) | Struktur [Size](../../com.aspose.drawing/size) pada sisi kiri operator kesamaan. |
| sz2 | [Size](../../com.aspose.drawing/size) | Struktur [Size](../../com.aspose.drawing/size) pada sisi kanan operator kesamaan. |

**Returns:**
boolean - true jika `sz1` dan `sz2` memiliki lebar dan tinggi yang sama; jika tidak, false.
### op_Inequality(Size sz1, Size sz2) {#op-Inequality-com.aspose.drawing.Size-com.aspose.drawing.Size-}
```
public static boolean op_Inequality(Size sz1, Size sz2)
```


Memeriksa apakah dua struktur [Size](../../com.aspose.drawing/size) berbeda.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sz1 | [Size](../../com.aspose.drawing/size) | Struktur [Size](../../com.aspose.drawing/size) pada sisi kiri operator ketidaksamaan. |
| sz2 | [Size](../../com.aspose.drawing/size) | Struktur [Size](../../com.aspose.drawing/size) pada sisi kanan operator ketidaksamaan. |

**Returns:**
boolean - true jika `sz1` dan `sz2` berbeda baik dalam lebar maupun tinggi; false jika `sz1` dan `sz2` sama.
### to_Point(Size size) {#to-Point-com.aspose.drawing.Size-}
```
public static Point to_Point(Size size)
```


Mengonversi [Size](../../com.aspose.drawing/size) yang ditentukan menjadi [Point](../../com.aspose.drawing/point).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| size | [Size](../../com.aspose.drawing/size) | [Size](../../com.aspose.drawing/size) yang akan dikonversi. |

**Returns:**
[Point](../../com.aspose.drawing/point) - The [Point](../../com.aspose.drawing/point) structure to which this operator converts.
### add(Size sz1, Size sz2) {#add-com.aspose.drawing.Size-com.aspose.drawing.Size-}
```
public static Size add(Size sz1, Size sz2)
```


Menambahkan lebar dan tinggi satu struktur [Size](../../com.aspose.drawing/size) ke lebar dan tinggi struktur [Size](../../com.aspose.drawing/size) lainnya.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sz1 | [Size](../../com.aspose.drawing/size) | [Size](../../com.aspose.drawing/size) pertama yang akan ditambahkan. |
| sz2 | [Size](../../com.aspose.drawing/size) | [Size](../../com.aspose.drawing/size) kedua yang akan ditambahkan. |

**Returns:**
[Size](../../com.aspose.drawing/size) - A [Size](../../com.aspose.drawing/size) structure that is the result of the addition operation.
### ceiling(SizeF value) {#ceiling-com.aspose.drawing.SizeF-}
```
public static Size ceiling(SizeF value)
```


Mengonversi struktur [SizeF](../../com.aspose.drawing/sizef) yang ditentukan menjadi struktur [Size](../../com.aspose.drawing/size) dengan membulatkan nilai-nilai struktur [Size](../../com.aspose.drawing/size) ke nilai integer berikutnya yang lebih tinggi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.drawing/sizef) | Struktur [SizeF](../../com.aspose.drawing/sizef) untuk dikonversi. |

**Returns:**
[Size](../../com.aspose.drawing/size) - The [Size](../../com.aspose.drawing/size) structure this method converts to.
### subtract(Size sz1, Size sz2) {#subtract-com.aspose.drawing.Size-com.aspose.drawing.Size-}
```
public static Size subtract(Size sz1, Size sz2)
```


Mengurangi lebar dan tinggi satu struktur [Size](../../com.aspose.drawing/size) dari lebar dan tinggi struktur [Size](../../com.aspose.drawing/size) lainnya.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sz1 | [Size](../../com.aspose.drawing/size) | Struktur [Size](../../com.aspose.drawing/size) di sisi kiri operator pengurangan. |
| sz2 | [Size](../../com.aspose.drawing/size) | Struktur [Size](../../com.aspose.drawing/size) di sisi kanan operator pengurangan. |

**Returns:**
[Size](../../com.aspose.drawing/size) - The [Size](../../com.aspose.drawing/size) that is a result of the subtraction operation.
### truncate(SizeF value) {#truncate-com.aspose.drawing.SizeF-}
```
public static Size truncate(SizeF value)
```


Mengonversi struktur [SizeF](../../com.aspose.drawing/sizef) yang ditentukan menjadi struktur [Size](../../com.aspose.drawing/size) dengan memotong nilai-nilai struktur [SizeF](../../com.aspose.drawing/sizef) ke nilai integer berikutnya yang lebih rendah.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.drawing/sizef) | Struktur [SizeF](../../com.aspose.drawing/sizef) untuk dikonversi. |

**Returns:**
[Size](../../com.aspose.drawing/size) - The [Size](../../com.aspose.drawing/size) structure this method converts to.
### round(SizeF value) {#round-com.aspose.drawing.SizeF-}
```
public static Size round(SizeF value)
```


Mengonversi struktur [SizeF](../../com.aspose.drawing/sizef) yang ditentukan menjadi struktur [Size](../../com.aspose.drawing/size) dengan membulatkan nilai-nilai struktur [SizeF](../../com.aspose.drawing/sizef) ke nilai integer terdekat.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.drawing/sizef) | Struktur [SizeF](../../com.aspose.drawing/sizef) untuk dikonversi. |

**Returns:**
[Size](../../com.aspose.drawing/size) - The [Size](../../com.aspose.drawing/size) structure this method converts to.
### isEquals(Size obj1, Size obj2) {#isEquals-com.aspose.drawing.Size-com.aspose.drawing.Size-}
```
public static boolean isEquals(Size obj1, Size obj2)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj1 | [Size](../../com.aspose.drawing/size) |  |
| obj2 | [Size](../../com.aspose.drawing/size) |  |

**Returns:**
boolean
### getEmpty() {#getEmpty--}
```
public static Size getEmpty()
```




**Returns:**
[Size](../../com.aspose.drawing/size)
### isEmpty() {#isEmpty--}
```
public final boolean isEmpty()
```


Mengambil nilai yang menunjukkan apakah [Size](../../com.aspose.drawing/size) ini memiliki lebar dan tinggi 0.

**Returns:**
boolean - nilai yang menunjukkan apakah [Size](../../com.aspose.drawing/size) ini memiliki lebar dan tinggi 0.
### getWidth() {#getWidth--}
```
public final int getWidth()
```


Mengambil komponen horizontal dari [Size](../../com.aspose.drawing/size) ini.

**Returns:**
int - komponen horizontal dari [Size](../../com.aspose.drawing/size) ini.
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Mengatur komponen horizontal dari [Size](../../com.aspose.drawing/size) ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int | komponen horizontal dari [Size](../../com.aspose.drawing/size) ini. |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Mengambil komponen vertikal dari [Size](../../com.aspose.drawing/size) ini.

**Returns:**
int - komponen vertikal dari [Size](../../com.aspose.drawing/size) ini.
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Mengatur komponen vertikal dari [Size](../../com.aspose.drawing/size) ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int | komponen vertikal dari [Size](../../com.aspose.drawing/size) ini. |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Memeriksa apakah objek yang ditentukan adalah [Size](../../com.aspose.drawing/size) dengan dimensi yang sama dengan [Size](../../com.aspose.drawing/size) ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | java.lang.Object | Objek yang akan diuji. |

**Returns:**
boolean - true jika `obj` adalah [Size](../../com.aspose.drawing/size) dan memiliki lebar serta tinggi yang sama dengan [Size](../../com.aspose.drawing/size) ini; jika tidak, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Mengembalikan kode hash untuk struktur [Size](../../com.aspose.drawing/size) ini.

**Returns:**
int - Nilai integer yang menentukan nilai hash untuk struktur [Size](../../com.aspose.drawing/size) ini.
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### equals(Size other) {#equals-com.aspose.drawing.Size-}
```
public final boolean equals(Size other)
```


Memeriksa apakah struktur [Size](../../com.aspose.drawing/size) lain memiliki ukuran yang sama dengan struktur [Size](../../com.aspose.drawing/size) ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| other | [Size](../../com.aspose.drawing/size) | Ukuran lain untuk diuji |

**Returns:**
boolean - Metode ini mengembalikan `true` jika struktur [Size](../../com.aspose.drawing/size) lain dan properti Width serta Height-nya sama dengan properti yang bersesuaian pada struktur [Size](../../com.aspose.drawing/size) ini; jika tidak, `false`.
### CloneTo(Size that) {#CloneTo-com.aspose.drawing.Size-}
```
public void CloneTo(Size that)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| that | [Size](../../com.aspose.drawing/size) |  |

### Clone() {#Clone--}
```
public Size Clone()
```




**Returns:**
[Size](../../com.aspose.drawing/size)
### clone() {#clone--}
```
public Size clone()
```




**Returns:**
[Size](../../com.aspose.drawing/size)
