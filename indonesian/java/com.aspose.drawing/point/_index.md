---
title: Point
second_title: Referensi API Aspose.Drawing for Java
description: Mewakili pasangan terurut dari koordinat x dan y bertipe integer yang mendefinisikan sebuah titik dalam bidang dua dimensi.
type: docs
weight: 36
url: /id/java/com.aspose.drawing/point/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable, java.lang.Cloneable
```
public class Point extends Struct<Point> implements System.IEquatable<Point>, Cloneable
```

Mewakili pasangan terurut dari koordinat x dan y bertipe integer yang mendefinisikan sebuah titik dalam bidang dua dimensi.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [Point()](#Point--) |  |
| [Point(int x, int y)](#Point-int-int-) | Menginisialisasi sebuah instance baru dari struct [Point](../../com.aspose.drawing/point) dengan koordinat yang ditentukan. |
| [Point(Size sz)](#Point-com.aspose.drawing.Size-) |  |
| [Point(int dw)](#Point-int-) | Menginisialisasi sebuah instance baru dari struct [Point](../../com.aspose.drawing/point) menggunakan koordinat yang ditentukan oleh nilai integer. |
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [EMPTY](#EMPTY) | Mewakili sebuah [Point](../../com.aspose.drawing/point) yang memiliki nilai `Point.X` dan `Point.Y` diatur ke nol. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [to_PointF(Point p)](#to-PointF-com.aspose.drawing.Point-) | Mengonversi struktur [Point](../../com.aspose.drawing/point) yang ditentukan menjadi struktur [PointF](../../com.aspose.drawing/pointf). |
| [to_Size(Point p)](#to-Size-com.aspose.drawing.Point-) |  |
| [op_Addition(Point pt, Size sz)](#op-Addition-com.aspose.drawing.Point-com.aspose.drawing.Size-) |  |
| [op_Subtraction(Point pt, Size sz)](#op-Subtraction-com.aspose.drawing.Point-com.aspose.drawing.Size-) |  |
| [op_Equality(Point left, Point right)](#op-Equality-com.aspose.drawing.Point-com.aspose.drawing.Point-) | Membandingkan dua objek [Point](../../com.aspose.drawing/point). |
| [op_Inequality(Point left, Point right)](#op-Inequality-com.aspose.drawing.Point-com.aspose.drawing.Point-) | Membandingkan dua objek [Point](../../com.aspose.drawing/point). |
| [add(Point pt, Size sz)](#add-com.aspose.drawing.Point-com.aspose.drawing.Size-) | Menambahkan [Size](../../com.aspose.drawing/size) yang ditentukan ke [Point](../../com.aspose.drawing/point) yang ditentukan. |
| [subtract(Point pt, Size sz)](#subtract-com.aspose.drawing.Point-com.aspose.drawing.Size-) |  |
| [ceiling(PointF value)](#ceiling-com.aspose.drawing.PointF-) |  |
| [truncate(PointF value)](#truncate-com.aspose.drawing.PointF-) | Mengonversi PointF menjadi Point dengan melakukan operasi pemotongan pada semua koordinat. |
| [round(PointF value)](#round-com.aspose.drawing.PointF-) | Mengonversi [PointF](../../com.aspose.drawing/pointf) yang ditentukan menjadi objek Point dengan membulatkan nilai [Point](../../com.aspose.drawing/point) ke bilangan bulat terdekat. |
| [isEquals(Point obj1, Point obj2)](#isEquals-com.aspose.drawing.Point-com.aspose.drawing.Point-) |  |
| [getEmpty()](#getEmpty--) |  |
| [getX()](#getX--) | Mendapatkan koordinat x dari Point ini. |
| [setX(int value)](#setX-int-) | Mengatur koordinat x dari Point ini. |
| [getY()](#getY--) | Mendapatkan koordinat y dari Point ini. |
| [setY(int value)](#setY-int-) | Mengatur koordinat y dari Point ini. |
| [isEmpty()](#isEmpty--) | Mendapatkan nilai yang menunjukkan apakah [Point](../../com.aspose.drawing/point) ini kosong. |
| [hashCode()](#hashCode--) | Mengembalikan kode hash untuk [Point](../../com.aspose.drawing/point) ini. |
| [toString()](#toString--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Menentukan apakah [Point](../../com.aspose.drawing/point) ini berisi koordinat yang sama dengan Objek yang ditentukan. |
| [offset(int dx, int dy)](#offset-int-int-) | Menerjemahkan [Point](../../com.aspose.drawing/point) ini dengan jumlah yang ditentukan. |
| [offset(Point p)](#offset-com.aspose.drawing.Point-) | Menerjemahkan [Point](../../com.aspose.drawing/point) ini dengan [Point](../../com.aspose.drawing/point) yang ditentukan. |
| [equals(Point other)](#equals-com.aspose.drawing.Point-) | Menguji apakah struktur [Point](../../com.aspose.drawing/point) lain memiliki lokasi yang sama dengan struktur [Point](../../com.aspose.drawing/point) ini. |
| [CloneTo(Point that)](#CloneTo-com.aspose.drawing.Point-) |  |
| [Clone()](#Clone--) |  |
| [clone()](#clone--) |  |
### Point() {#Point--}
```
public Point()
```


### Point(int x, int y) {#Point-int-int-}
```
public Point(int x, int y)
```


Menginisialisasi sebuah instance baru dari struct [Point](../../com.aspose.drawing/point) dengan koordinat yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | int | Posisi horizontal titik. |
| y | int | Posisi vertikal titik. |

### Point(Size sz) {#Point-com.aspose.drawing.Size-}
```
public Point(Size sz)
```


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sz | [Size](../../com.aspose.drawing/size) |  |

### Point(int dw) {#Point-int-}
```
public Point(int dw)
```


Menginisialisasi sebuah instance baru dari struct [Point](../../com.aspose.drawing/point) menggunakan koordinat yang ditentukan oleh nilai integer.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| dw | int | Nilai integer. |

### EMPTY {#EMPTY}
```
public static final Point EMPTY
```


Mewakili sebuah [Point](../../com.aspose.drawing/point) yang memiliki nilai `Point.X` dan `Point.Y` diatur ke nol.

### to_PointF(Point p) {#to-PointF-com.aspose.drawing.Point-}
```
public static PointF to_PointF(Point p)
```


Mengonversi struktur [Point](../../com.aspose.drawing/point) yang ditentukan menjadi struktur [PointF](../../com.aspose.drawing/pointf).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| p | [Point](../../com.aspose.drawing/point) | [Point](../../com.aspose.drawing/point) yang akan dikonversi. |

**Returns:**
[PointF](../../com.aspose.drawing/pointf) - The [PointF](../../com.aspose.drawing/pointf) that results from the conversion.
### to_Size(Point p) {#to-Size-com.aspose.drawing.Point-}
```
public static Size to_Size(Point p)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| p | [Point](../../com.aspose.drawing/point) |  |

**Returns:**
[Size](../../com.aspose.drawing/size)
### op_Addition(Point pt, Size sz) {#op-Addition-com.aspose.drawing.Point-com.aspose.drawing.Size-}
```
public static Point op_Addition(Point pt, Size sz)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pt | [Point](../../com.aspose.drawing/point) |  |
| sz | [Size](../../com.aspose.drawing/size) |  |

**Returns:**
[Point](../../com.aspose.drawing/point)
### op_Subtraction(Point pt, Size sz) {#op-Subtraction-com.aspose.drawing.Point-com.aspose.drawing.Size-}
```
public static Point op_Subtraction(Point pt, Size sz)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pt | [Point](../../com.aspose.drawing/point) |  |
| sz | [Size](../../com.aspose.drawing/size) |  |

**Returns:**
[Point](../../com.aspose.drawing/point)
### op_Equality(Point left, Point right) {#op-Equality-com.aspose.drawing.Point-com.aspose.drawing.Point-}
```
public static boolean op_Equality(Point left, Point right)
```


Membandingkan dua objek [Point](../../com.aspose.drawing/point). Hasilnya menentukan apakah nilai properti `Point.X` dan `Point.Y` dari dua objek [Point](../../com.aspose.drawing/point) tersebut sama.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| left | [Point](../../com.aspose.drawing/point) | Pertama [Point](../../com.aspose.drawing/point) untuk dibandingkan. |
| right | [Point](../../com.aspose.drawing/point) | Kedua [Point](../../com.aspose.drawing/point) untuk dibandingkan. |

**Returns:**
boolean - true jika nilai `Point.X` dan `Point.Y` dari `left` dan `right` sama; selain itu, false.
### op_Inequality(Point left, Point right) {#op-Inequality-com.aspose.drawing.Point-com.aspose.drawing.Point-}
```
public static boolean op_Inequality(Point left, Point right)
```


Membandingkan dua objek [Point](../../com.aspose.drawing/point). Hasilnya menentukan apakah nilai properti `Point.X` atau `Point.Y` dari dua objek [Point](../../com.aspose.drawing/point) tersebut tidak sama.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| left | [Point](../../com.aspose.drawing/point) | Pertama [Point](../../com.aspose.drawing/point) untuk dibandingkan. |
| right | [Point](../../com.aspose.drawing/point) | Kedua [Point](../../com.aspose.drawing/point) untuk dibandingkan. |

**Returns:**
boolean - true jika nilai properti `Point.X` atau `Point.Y` dari `left` dan `right` berbeda; selain itu, false.
### add(Point pt, Size sz) {#add-com.aspose.drawing.Point-com.aspose.drawing.Size-}
```
public static Point add(Point pt, Size sz)
```


Menambahkan [Size](../../com.aspose.drawing/size) yang ditentukan ke [Point](../../com.aspose.drawing/point) yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pt | [Point](../../com.aspose.drawing/point) | Objek [Point](../../com.aspose.drawing/point) yang akan ditambahkan. |
| sz | [Size](../../com.aspose.drawing/size) | Objek [Size](../../com.aspose.drawing/size) yang akan ditambahkan |

**Returns:**
[Point](../../com.aspose.drawing/point) - The [Point](../../com.aspose.drawing/point) that is the result of the addition operation.
### subtract(Point pt, Size sz) {#subtract-com.aspose.drawing.Point-com.aspose.drawing.Size-}
```
public static Point subtract(Point pt, Size sz)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pt | [Point](../../com.aspose.drawing/point) |  |
| sz | [Size](../../com.aspose.drawing/size) |  |

**Returns:**
[Point](../../com.aspose.drawing/point)
### ceiling(PointF value) {#ceiling-com.aspose.drawing.PointF-}
```
public static Point ceiling(PointF value)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [PointF](../../com.aspose.drawing/pointf) |  |

**Returns:**
[Point](../../com.aspose.drawing/point)
### truncate(PointF value) {#truncate-com.aspose.drawing.PointF-}
```
public static Point truncate(PointF value)
```


Mengonversi PointF menjadi Point dengan melakukan operasi pemotongan pada semua koordinat.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [PointF](../../com.aspose.drawing/pointf) | Objek [PointF](../../com.aspose.drawing/pointf) yang akan dipotong. |

**Returns:**
[Point](../../com.aspose.drawing/point) - The [Point](../../com.aspose.drawing/point) that is the result of the truncate operation.
### round(PointF value) {#round-com.aspose.drawing.PointF-}
```
public static Point round(PointF value)
```


Mengonversi [PointF](../../com.aspose.drawing/pointf) yang ditentukan menjadi objek Point dengan membulatkan nilai [Point](../../com.aspose.drawing/point) ke bilangan bulat terdekat.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [PointF](../../com.aspose.drawing/pointf) | Objek [PointF](../../com.aspose.drawing/pointf) yang akan dikonversi. |

**Returns:**
[Point](../../com.aspose.drawing/point) - The [Point](../../com.aspose.drawing/point) this method converts to.
### isEquals(Point obj1, Point obj2) {#isEquals-com.aspose.drawing.Point-com.aspose.drawing.Point-}
```
public static boolean isEquals(Point obj1, Point obj2)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj1 | [Point](../../com.aspose.drawing/point) |  |
| obj2 | [Point](../../com.aspose.drawing/point) |  |

**Returns:**
boolean
### getEmpty() {#getEmpty--}
```
public static Point getEmpty()
```




**Returns:**
[Point](../../com.aspose.drawing/point)
### getX() {#getX--}
```
public final int getX()
```


Mendapatkan koordinat x dari Point ini.

**Returns:**
int - koordinat x dari Point ini.
### setX(int value) {#setX-int-}
```
public final void setX(int value)
```


Mengatur koordinat x dari Point ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int | koordinat x dari Point ini. |

### getY() {#getY--}
```
public final int getY()
```


Mendapatkan koordinat y dari Point ini.

**Returns:**
int - koordinat y dari Point ini.
### setY(int value) {#setY-int-}
```
public final void setY(int value)
```


Mengatur koordinat y dari Point ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int | koordinat y dari Point ini. |

### isEmpty() {#isEmpty--}
```
public final boolean isEmpty()
```


Mendapatkan nilai yang menunjukkan apakah [Point](../../com.aspose.drawing/point) ini kosong.

Nilai: `true` jika X dan Y keduanya 0; selain itu, `false`.

**Returns:**
boolean - nilai yang menunjukkan apakah [Point](../../com.aspose.drawing/point) ini kosong.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Mengembalikan kode hash untuk [Point](../../com.aspose.drawing/point) ini.

**Returns:**
int - Nilai integer yang menentukan nilai hash untuk [Point](../../com.aspose.drawing/point) ini.
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Menentukan apakah [Point](../../com.aspose.drawing/point) ini berisi koordinat yang sama dengan Objek yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | java.lang.Object | Objek yang akan diuji. |

**Returns:**
boolean - `true` jika obj adalah Point dan memiliki koordinat yang sama dengan [Point](../../com.aspose.drawing/point) ini.
### offset(int dx, int dy) {#offset-int-int-}
```
public final void offset(int dx, int dy)
```


Menerjemahkan [Point](../../com.aspose.drawing/point) ini dengan jumlah yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| dx | int | Jumlah untuk menggeser koordinat x. |
| dy | int | Jumlah untuk menggeser koordinat y. |

### offset(Point p) {#offset-com.aspose.drawing.Point-}
```
public final void offset(Point p)
```


Menerjemahkan [Point](../../com.aspose.drawing/point) ini dengan [Point](../../com.aspose.drawing/point) yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| p | [Point](../../com.aspose.drawing/point) | Objek [Point](../../com.aspose.drawing/point) yang digunakan untuk menggeser [Point](../../com.aspose.drawing/point) ini. |

### equals(Point other) {#equals-com.aspose.drawing.Point-}
```
public final boolean equals(Point other)
```


Menguji apakah struktur [Point](../../com.aspose.drawing/point) lain memiliki lokasi yang sama dengan struktur [Point](../../com.aspose.drawing/point) ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| other | [Point](../../com.aspose.drawing/point) | Titik lain untuk diuji |

**Returns:**
boolean - Metode ini mengembalikan `true` jika struktur [Point](../../com.aspose.drawing/point) lain dan properti X serta Y‑nya sama dengan properti yang bersesuaian pada struktur [Point](../../com.aspose.drawing/point) ini; selain itu, `false`.
### CloneTo(Point that) {#CloneTo-com.aspose.drawing.Point-}
```
public void CloneTo(Point that)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| that | [Point](../../com.aspose.drawing/point) |  |

### Clone() {#Clone--}
```
public Point Clone()
```




**Returns:**
[Point](../../com.aspose.drawing/point)
### clone() {#clone--}
```
public Object clone()
```




**Returns:**
java.lang.Object
