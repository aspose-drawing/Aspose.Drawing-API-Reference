---
title: CharacterRange
second_title: Referensi API Aspose.Drawing for Java
description: Menentukan rentang posisi karakter dalam sebuah string.
type: docs
weight: 13
url: /id/java/com.aspose.drawing/characterrange/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
java.lang.Cloneable
```
public class CharacterRange extends Struct<CharacterRange> implements Cloneable
```

Menentukan rentang posisi karakter dalam sebuah string.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [CharacterRange()](#CharacterRange--) |  |
| [CharacterRange(int first, int length)](#CharacterRange-int-int-) | Menginisialisasi instance baru dari struct [CharacterRange](../../com.aspose.drawing/characterrange), yang menentukan rentang posisi karakter dalam sebuah string. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getFirst()](#getFirst--) | Mendapatkan atau mengatur posisi dalam string dari karakter pertama dari [CharacterRange](../../com.aspose.drawing/characterrange). |
| [setFirst(int value)](#setFirst-int-) | Mendapatkan atau mengatur posisi dalam string dari karakter pertama dari [CharacterRange](../../com.aspose.drawing/characterrange). |
| [getLength()](#getLength--) | Mendapatkan atau mengatur jumlah posisi dalam [CharacterRange](../../com.aspose.drawing/characterrange). |
| [setLength(int value)](#setLength-int-) | Mendapatkan atau mengatur jumlah posisi dalam [CharacterRange](../../com.aspose.drawing/characterrange). |
| [op_Equality(CharacterRange cr1, CharacterRange cr2)](#op-Equality-com.aspose.drawing.CharacterRange-com.aspose.drawing.CharacterRange-) | Membandingkan dua objek [CharacterRange](../../com.aspose.drawing/characterrange). |
| [op_Inequality(CharacterRange cr1, CharacterRange cr2)](#op-Inequality-com.aspose.drawing.CharacterRange-com.aspose.drawing.CharacterRange-) | Membandingkan dua objek [CharacterRange](../../com.aspose.drawing/characterrange). |
| [equals(Object obj)](#equals-java.lang.Object-) | Mendapatkan nilai yang menunjukkan apakah objek ini setara dengan objek yang ditentukan. |
| [hashCode()](#hashCode--) | Mengembalikan kode hash untuk instance ini. |
| [CloneTo(CharacterRange that)](#CloneTo-com.aspose.drawing.CharacterRange-) |  |
| [Clone()](#Clone--) |  |
| [clone()](#clone--) |  |
### CharacterRange() {#CharacterRange--}
```
public CharacterRange()
```


### CharacterRange(int first, int length) {#CharacterRange-int-int-}
```
public CharacterRange(int first, int length)
```


Menginisialisasi instance baru dari struct [CharacterRange](../../com.aspose.drawing/characterrange), yang menentukan rentang posisi karakter dalam sebuah string.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pertama | int | Posisi karakter pertama dalam rentang. Misalnya, jika First diatur ke 0, posisi pertama dari rentang adalah posisi 0 dalam string. |
| panjang | int | Jumlah posisi dalam rentang. |

### getFirst() {#getFirst--}
```
public final int getFirst()
```


Mendapatkan atau mengatur posisi dalam string dari karakter pertama dari [CharacterRange](../../com.aspose.drawing/characterrange).

Nilai: Posisi pertama dari [CharacterRange](../../com.aspose.drawing/characterrange).

**Returns:**
int
### setFirst(int value) {#setFirst-int-}
```
public final void setFirst(int value)
```


Mendapatkan atau mengatur posisi dalam string dari karakter pertama dari [CharacterRange](../../com.aspose.drawing/characterrange).

Nilai: Posisi pertama dari [CharacterRange](../../com.aspose.drawing/characterrange).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getLength() {#getLength--}
```
public final int getLength()
```


Mendapatkan atau mengatur jumlah posisi dalam [CharacterRange](../../com.aspose.drawing/characterrange).

Nilai: Jumlah posisi dalam [CharacterRange](../../com.aspose.drawing/characterrange).

**Returns:**
int
### setLength(int value) {#setLength-int-}
```
public final void setLength(int value)
```


Mendapatkan atau mengatur jumlah posisi dalam [CharacterRange](../../com.aspose.drawing/characterrange).

Nilai: Jumlah posisi dalam [CharacterRange](../../com.aspose.drawing/characterrange).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### op_Equality(CharacterRange cr1, CharacterRange cr2) {#op-Equality-com.aspose.drawing.CharacterRange-com.aspose.drawing.CharacterRange-}
```
public static boolean op_Equality(CharacterRange cr1, CharacterRange cr2)
```


Membandingkan dua objek [CharacterRange](../../com.aspose.drawing/characterrange). Mendapatkan nilai yang menunjukkan apakah nilai First dan Length dari dua objek [CharacterRange](../../com.aspose.drawing/characterrange) adalah sama.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| cr1 | [CharacterRange](../../com.aspose.drawing/characterrange) | Sebuah [CharacterRange](../../com.aspose.drawing/characterrange) untuk dibandingkan kesetaraannya. |
| cr2 | [CharacterRange](../../com.aspose.drawing/characterrange) | Sebuah [CharacterRange](../../com.aspose.drawing/characterrange) untuk dibandingkan kesetaraannya. |

**Returns:**
boolean - `true` untuk menunjukkan dua objek CharacterRange memiliki nilai First dan Length yang sama; jika tidak, `false`.
### op_Inequality(CharacterRange cr1, CharacterRange cr2) {#op-Inequality-com.aspose.drawing.CharacterRange-com.aspose.drawing.CharacterRange-}
```
public static boolean op_Inequality(CharacterRange cr1, CharacterRange cr2)
```


Membandingkan dua objek [CharacterRange](../../com.aspose.drawing/characterrange). Mendapatkan nilai yang menunjukkan apakah nilai First atau Length dari dua objek [CharacterRange](../../com.aspose.drawing/characterrange) tidak sama.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| cr1 | [CharacterRange](../../com.aspose.drawing/characterrange) | Sebuah [CharacterRange](../../com.aspose.drawing/characterrange) untuk dibandingkan ketidaksamaannya. |
| cr2 | [CharacterRange](../../com.aspose.drawing/characterrange) | Sebuah [CharacterRange](../../com.aspose.drawing/characterrange) untuk dibandingkan ketidaksamaannya. |

**Returns:**
boolean - `true` untuk menunjukkan bahwa nilai First atau Length dari dua objek CharacterRange berbeda; jika tidak, `false`.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Mendapatkan nilai yang menunjukkan apakah objek ini setara dengan objek yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | java.lang.Object | Objek untuk dibandingkan kesetaraannya.. |

**Returns:**
boolean - `true` untuk menunjukkan objek yang ditentukan adalah sebuah instance dengan nilai First dan Length yang sama dengan instance ini; jika tidak, `false`.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Mengembalikan kode hash untuk instance ini.

**Returns:**
int - Sebuah integer bertanda 32-bit yang merupakan kode hash untuk instance ini.
### CloneTo(CharacterRange that) {#CloneTo-com.aspose.drawing.CharacterRange-}
```
public void CloneTo(CharacterRange that)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| that | [CharacterRange](../../com.aspose.drawing/characterrange) |  |

### Clone() {#Clone--}
```
public CharacterRange Clone()
```




**Returns:**
[CharacterRange](../../com.aspose.drawing/characterrange)
### clone() {#clone--}
```
public Object clone()
```




**Returns:**
java.lang.Object
