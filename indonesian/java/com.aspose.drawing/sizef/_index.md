---
title: SizeF
second_title: Referensi API Aspose.Drawing for Java
description: Menyimpan sepasang nilai floating-point yang biasanya mewakili lebar dan tinggi sebuah persegi panjang.
type: docs
weight: 43
url: /id/java/com.aspose.drawing/sizef/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable, java.lang.Cloneable
```
public class SizeF extends Struct<SizeF> implements System.IEquatable<SizeF>, Cloneable
```

Menyimpan pasangan terurut dari angka floating-point, biasanya lebar dan tinggi sebuah persegi panjang.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [SizeF()](#SizeF--) |  |
| [SizeF(float width, float height)](#SizeF-float-float-) | Menginisialisasi instance baru dari struktur SizeF dengan dimensi yang ditentukan. |
| [SizeF(PointF pt)](#SizeF-com.aspose.drawing.PointF-) | Menginisialisasi instance baru dari struct [SizeF](../../com.aspose.drawing/sizef). |
| [SizeF(SizeF size)](#SizeF-com.aspose.drawing.SizeF-) | Menginisialisasi instance baru dari struct [SizeF](../../com.aspose.drawing/sizef). |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [op_Equality(SizeF sz1, SizeF sz2)](#op-Equality-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-) | Menguji apakah dua struktur [SizeF](../../com.aspose.drawing/sizef) sama. |
| [op_Inequality(SizeF sz1, SizeF sz2)](#op-Inequality-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-) | Menguji apakah dua struktur [SizeF](../../com.aspose.drawing/sizef) berbeda. |
| [add(SizeF sz1, SizeF sz2)](#add-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-) | Menambahkan lebar dan tinggi satu struktur [SizeF](../../com.aspose.drawing/sizef) ke lebar dan tinggi struktur [SizeF](../../com.aspose.drawing/sizef) lainnya. |
| [subtract(SizeF sz1, SizeF sz2)](#subtract-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-) | Mengurangi lebar dan tinggi satu struktur [SizeF](../../com.aspose.drawing/sizef) dari lebar dan tinggi struktur [SizeF](../../com.aspose.drawing/sizef) lainnya. |
| [op_Addition(SizeF sz1, SizeF sz2)](#op-Addition-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-) | Menambahkan lebar dan tinggi satu struktur [SizeF](../../com.aspose.drawing/sizef) ke lebar dan tinggi struktur [SizeF](../../com.aspose.drawing/sizef) lainnya. |
| [op_Subtraction(SizeF sz1, SizeF sz2)](#op-Subtraction-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-) | Mengurangi lebar dan tinggi satu struktur [SizeF](../../com.aspose.drawing/sizef) dari lebar dan tinggi struktur [SizeF](../../com.aspose.drawing/sizef) lainnya. |
| [op_Multiply(float left, SizeF right)](#op-Multiply-float-com.aspose.drawing.SizeF-) | Mengalikan [SizeF](../../com.aspose.drawing/sizef) dengan `float` menghasilkan [SizeF](../../com.aspose.drawing/sizef). |
| [op_Multiply(SizeF left, float right)](#op-Multiply-com.aspose.drawing.SizeF-float-) | Mengalikan [SizeF](../../com.aspose.drawing/sizef) dengan `float` menghasilkan [SizeF](../../com.aspose.drawing/sizef). |
| [op_Division(SizeF left, float right)](#op-Division-com.aspose.drawing.SizeF-float-) | Membagi [SizeF](../../com.aspose.drawing/sizef) dengan `float` menghasilkan [SizeF](../../com.aspose.drawing/sizef). |
| [to_PointF(SizeF size)](#to-PointF-com.aspose.drawing.SizeF-) |  |
| [isEquals(SizeF obj1, SizeF obj2)](#isEquals-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-) |  |
| [getEmpty()](#getEmpty--) |  |
| [isEmpty()](#isEmpty--) | Mendapatkan nilai yang menunjukkan apakah struktur [SizeF](../../com.aspose.drawing/sizef) ini memiliki lebar dan tinggi nol. |
| [getWidth()](#getWidth--) | Mendapatkan komponen horizontal dari struktur SizeF ini. |
| [setWidth(float value)](#setWidth-float-) | Mengatur komponen horizontal dari struktur SizeF ini. |
| [getHeight()](#getHeight--) | Mendapatkan komponen vertikal dari struktur SizeF ini. |
| [setHeight(float value)](#setHeight-float-) | Mengatur komponen vertikal dari struktur SizeF ini. |
| [hashCode()](#hashCode--) | Mengembalikan kode hash untuk struktur [SizeF](../../com.aspose.drawing/sizef) ini. |
| [toString()](#toString--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Menguji apakah objek yang ditentukan adalah struktur [SizeF](../../com.aspose.drawing/sizef) dengan dimensi yang sama dengan struktur [SizeF](../../com.aspose.drawing/sizef) ini. |
| [toSize()](#toSize--) | Mengonversi struktur [SizeF](../../com.aspose.drawing/sizef) menjadi struktur [Size](../../com.aspose.drawing/size). |
| [toPointF()](#toPointF--) | Mengonversi struktur [SizeF](../../com.aspose.drawing/sizef) menjadi struktur [PointF](../../com.aspose.drawing/pointf). |
| [equals(SizeF other)](#equals-com.aspose.drawing.SizeF-) | Menguji apakah struktur [SizeF](../../com.aspose.drawing/sizef) lain memiliki ukuran yang sama dengan struktur [SizeF](../../com.aspose.drawing/sizef) ini. |
| [CloneTo(SizeF that)](#CloneTo-com.aspose.drawing.SizeF-) |  |
| [Clone()](#Clone--) |  |
| [clone()](#clone--) |  |
### SizeF() {#SizeF--}
```
public SizeF()
```


### SizeF(float width, float height) {#SizeF-float-float-}
```
public SizeF(float width, float height)
```


Menginisialisasi instance baru dari struktur SizeF dengan dimensi yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| lebar | float | Komponen lebar dari struktur SizeF baru. |
| tinggi | float | Komponen tinggi dari struktur SizeF baru. |

### SizeF(PointF pt) {#SizeF-com.aspose.drawing.PointF-}
```
public SizeF(PointF pt)
```


Menginisialisasi instance baru dari struct [SizeF](../../com.aspose.drawing/sizef).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pt | [PointF](../../com.aspose.drawing/pointf) | Struktur [PointF](../../com.aspose.drawing/pointf) yang digunakan untuk menginisialisasi struktur [SizeF](../../com.aspose.drawing/sizef) ini. |

### SizeF(SizeF size) {#SizeF-com.aspose.drawing.SizeF-}
```
public SizeF(SizeF size)
```


Menginisialisasi instance baru dari struct [SizeF](../../com.aspose.drawing/sizef).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.drawing/sizef) | Struktur [SizeF](../../com.aspose.drawing/sizef) yang digunakan untuk membuat struktur [SizeF](../../com.aspose.drawing/sizef) baru. |

### op_Equality(SizeF sz1, SizeF sz2) {#op-Equality-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-}
```
public static boolean op_Equality(SizeF sz1, SizeF sz2)
```


Menguji apakah dua struktur [SizeF](../../com.aspose.drawing/sizef) sama.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sz1 | [SizeF](../../com.aspose.drawing/sizef) | Struktur [SizeF](../../com.aspose.drawing/sizef) di sisi kiri operator kesamaan. |
| sz2 | [SizeF](../../com.aspose.drawing/sizef) | Struktur [SizeF](../../com.aspose.drawing/sizef) di sisi kanan operator kesamaan. |

**Returns:**
boolean - Operator ini mengembalikan true jika `sz1` dan `sz2` memiliki lebar dan tinggi yang sama; jika tidak, false.
### op_Inequality(SizeF sz1, SizeF sz2) {#op-Inequality-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-}
```
public static boolean op_Inequality(SizeF sz1, SizeF sz2)
```


Menguji apakah dua struktur [SizeF](../../com.aspose.drawing/sizef) berbeda.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sz1 | [SizeF](../../com.aspose.drawing/sizef) | Struktur [SizeF](../../com.aspose.drawing/sizef) di sisi kiri operator ketidaksamaan. |
| sz2 | [SizeF](../../com.aspose.drawing/sizef) | Struktur [SizeF](../../com.aspose.drawing/sizef) di sisi kanan operator ketidaksamaan. |

**Returns:**
boolean - Operator ini mengembalikan true jika `sz1` dan `sz2` berbeda baik dalam lebar maupun tinggi; false jika `sz1` dan `sz2` sama.
### add(SizeF sz1, SizeF sz2) {#add-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-}
```
public static SizeF add(SizeF sz1, SizeF sz2)
```


Menambahkan lebar dan tinggi satu struktur [SizeF](../../com.aspose.drawing/sizef) ke lebar dan tinggi struktur [SizeF](../../com.aspose.drawing/sizef) lainnya.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sz1 | [SizeF](../../com.aspose.drawing/sizef) | Struktur [SizeF](../../com.aspose.drawing/sizef) pertama yang akan ditambahkan. |
| sz2 | [SizeF](../../com.aspose.drawing/sizef) | Struktur [SizeF](../../com.aspose.drawing/sizef) kedua yang akan ditambahkan. |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - A [SizeF](../../com.aspose.drawing/sizef) structure that is the result of the addition operation.
### subtract(SizeF sz1, SizeF sz2) {#subtract-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-}
```
public static SizeF subtract(SizeF sz1, SizeF sz2)
```


Mengurangi lebar dan tinggi satu struktur [SizeF](../../com.aspose.drawing/sizef) dari lebar dan tinggi struktur [SizeF](../../com.aspose.drawing/sizef) lainnya.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sz1 | [SizeF](../../com.aspose.drawing/sizef) | Struktur [SizeF](../../com.aspose.drawing/sizef) di sisi kiri operator pengurangan. |
| sz2 | [SizeF](../../com.aspose.drawing/sizef) | Struktur [SizeF](../../com.aspose.drawing/sizef) di sisi kanan operator pengurangan. |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - A [SizeF](../../com.aspose.drawing/sizef) structure that is a result of the subtraction operation.
### op_Addition(SizeF sz1, SizeF sz2) {#op-Addition-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-}
```
public static SizeF op_Addition(SizeF sz1, SizeF sz2)
```


Menambahkan lebar dan tinggi satu struktur [SizeF](../../com.aspose.drawing/sizef) ke lebar dan tinggi struktur [SizeF](../../com.aspose.drawing/sizef) lainnya.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sz1 | [SizeF](../../com.aspose.drawing/sizef) | Struktur [SizeF](../../com.aspose.drawing/sizef) pertama yang akan ditambahkan. |
| sz2 | [SizeF](../../com.aspose.drawing/sizef) | Struktur [SizeF](../../com.aspose.drawing/sizef) kedua yang akan ditambahkan. |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - A [Size](../../com.aspose.drawing/size) structure that is the result of the addition operation.
### op_Subtraction(SizeF sz1, SizeF sz2) {#op-Subtraction-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-}
```
public static SizeF op_Subtraction(SizeF sz1, SizeF sz2)
```


Mengurangi lebar dan tinggi satu struktur [SizeF](../../com.aspose.drawing/sizef) dari lebar dan tinggi struktur [SizeF](../../com.aspose.drawing/sizef) lainnya.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sz1 | [SizeF](../../com.aspose.drawing/sizef) | Struktur [SizeF](../../com.aspose.drawing/sizef) di sisi kiri operator pengurangan. |
| sz2 | [SizeF](../../com.aspose.drawing/sizef) | Struktur [SizeF](../../com.aspose.drawing/sizef) di sisi kanan operator pengurangan. |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - A [SizeF](../../com.aspose.drawing/sizef) that is the result of the subtraction operation.
### op_Multiply(float left, SizeF right) {#op-Multiply-float-com.aspose.drawing.SizeF-}
```
public static SizeF op_Multiply(float left, SizeF right)
```


Mengalikan [SizeF](../../com.aspose.drawing/sizef) dengan `float` menghasilkan [SizeF](../../com.aspose.drawing/sizef).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| kiri | float | Pengganda bertipe `float`. |
| right | [SizeF](../../com.aspose.drawing/sizef) | Pengali dengan tipe [SizeF](../../com.aspose.drawing/sizef). |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - Product of type [SizeF](../../com.aspose.drawing/sizef).
### op_Multiply(SizeF left, float right) {#op-Multiply-com.aspose.drawing.SizeF-float-}
```
public static SizeF op_Multiply(SizeF left, float right)
```


Mengalikan [SizeF](../../com.aspose.drawing/sizef) dengan `float` menghasilkan [SizeF](../../com.aspose.drawing/sizef).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| left | [SizeF](../../com.aspose.drawing/sizef) | Pengali dengan tipe [SizeF](../../com.aspose.drawing/sizef). |
| kanan | float | Pengganda bertipe `float`. |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - Product of type [SizeF](../../com.aspose.drawing/sizef).
### op_Division(SizeF left, float right) {#op-Division-com.aspose.drawing.SizeF-float-}
```
public static SizeF op_Division(SizeF left, float right)
```


Membagi [SizeF](../../com.aspose.drawing/sizef) dengan `float` menghasilkan [SizeF](../../com.aspose.drawing/sizef).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| left | [SizeF](../../com.aspose.drawing/sizef) | Pembilang dengan tipe [SizeF](../../com.aspose.drawing/sizef). |
| kanan | float | Divisor bertipe `int`. |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - Result of type [SizeF](../../com.aspose.drawing/sizef).
### to_PointF(SizeF size) {#to-PointF-com.aspose.drawing.SizeF-}
```
public static PointF to_PointF(SizeF size)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.drawing/sizef) |  |

**Returns:**
[PointF](../../com.aspose.drawing/pointf)
### isEquals(SizeF obj1, SizeF obj2) {#isEquals-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-}
```
public static boolean isEquals(SizeF obj1, SizeF obj2)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj1 | [SizeF](../../com.aspose.drawing/sizef) |  |
| obj2 | [SizeF](../../com.aspose.drawing/sizef) |  |

**Returns:**
boolean
### getEmpty() {#getEmpty--}
```
public static SizeF getEmpty()
```




**Returns:**
[SizeF](../../com.aspose.drawing/sizef)
### isEmpty() {#isEmpty--}
```
public final boolean isEmpty()
```


Mendapatkan nilai yang menunjukkan apakah struktur [SizeF](../../com.aspose.drawing/sizef) ini memiliki lebar dan tinggi nol.

**Returns:**
boolean - nilai yang menunjukkan apakah struktur [SizeF](../../com.aspose.drawing/sizef) ini memiliki lebar dan tinggi nol.
### getWidth() {#getWidth--}
```
public final float getWidth()
```


Mendapatkan komponen horizontal dari struktur SizeF ini.

**Returns:**
float - komponen horizontal dari struktur SizeF ini.
### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```


Mengatur komponen horizontal dari struktur SizeF ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float | komponen horizontal dari struktur SizeF ini. |

### getHeight() {#getHeight--}
```
public final float getHeight()
```


Mendapatkan komponen vertikal dari struktur SizeF ini.

**Returns:**
float - komponen vertikal dari struktur SizeF ini.
### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```


Mengatur komponen vertikal dari struktur SizeF ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float | komponen vertikal dari struktur SizeF ini. |

### hashCode() {#hashCode--}
```
public int hashCode()
```


Mengembalikan kode hash untuk struktur [SizeF](../../com.aspose.drawing/sizef) ini.

**Returns:**
int - Nilai integer yang menentukan nilai hash untuk struktur [SizeF](../../com.aspose.drawing/sizef) ini.
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


Menguji apakah objek yang ditentukan adalah struktur [SizeF](../../com.aspose.drawing/sizef) dengan dimensi yang sama dengan struktur [SizeF](../../com.aspose.drawing/sizef) ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | java.lang.Object | Objek yang akan diuji. |

**Returns:**
boolean - Metode ini mengembalikan `true` jika obj adalah [SizeF](../../com.aspose.drawing/sizef) dan memiliki lebar serta tinggi yang sama dengan SizeF ini; jika tidak, `false`.
### toSize() {#toSize--}
```
public final Size toSize()
```


Mengonversi struktur [SizeF](../../com.aspose.drawing/sizef) menjadi struktur [Size](../../com.aspose.drawing/size).

**Returns:**
[Size](../../com.aspose.drawing/size) - Returns a [Size](../../com.aspose.drawing/size) structure.
### toPointF() {#toPointF--}
```
public final PointF toPointF()
```


Mengonversi struktur [SizeF](../../com.aspose.drawing/sizef) menjadi struktur [PointF](../../com.aspose.drawing/pointf).

**Returns:**
[PointF](../../com.aspose.drawing/pointf) - Returns a [PointF](../../com.aspose.drawing/pointf) structure.
### equals(SizeF other) {#equals-com.aspose.drawing.SizeF-}
```
public final boolean equals(SizeF other)
```


Menguji apakah struktur [SizeF](../../com.aspose.drawing/sizef) lain memiliki ukuran yang sama dengan struktur [SizeF](../../com.aspose.drawing/sizef) ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| other | [SizeF](../../com.aspose.drawing/sizef) | Ukuran lain untuk diuji |

**Returns:**
boolean - Metode ini mengembalikan `true` jika struktur [SizeF](../../com.aspose.drawing/sizef) lain dan properti Width serta Height-nya sama dengan properti yang bersesuaian pada struktur [SizeF](../../com.aspose.drawing/sizef) ini; jika tidak, `false`.
### CloneTo(SizeF that) {#CloneTo-com.aspose.drawing.SizeF-}
```
public void CloneTo(SizeF that)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| that | [SizeF](../../com.aspose.drawing/sizef) |  |

### Clone() {#Clone--}
```
public SizeF Clone()
```




**Returns:**
[SizeF](../../com.aspose.drawing/sizef)
### clone() {#clone--}
```
public Object clone()
```




**Returns:**
java.lang.Object
