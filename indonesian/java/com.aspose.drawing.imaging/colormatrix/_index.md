---
title: ColorMatrix
second_title: Referensi API Aspose.Drawing for Java
description: Mendefinisikan matriks 5 x 5 yang berisi koordinat untuk ruang RGBA.
type: docs
weight: 14
url: /id/java/com.aspose.drawing.imaging/colormatrix/
---
**Inheritance:**
java.lang.Object
```
public final class ColorMatrix
```

Menentukan matriks 5 x 5 yang berisi koordinat untuk ruang RGBA. Beberapa metode dari kelas [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes) menyesuaikan warna gambar dengan menggunakan matriks warna. Kelas ini tidak dapat diwariskan.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [ColorMatrix()](#ColorMatrix--) | Menginisialisasi instance baru dari kelas [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [ColorMatrix(float[][] newColorMatrix)](#ColorMatrix-float-----) | Menginisialisasi instance baru dari kelas [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) menggunakan elemen-elemen dalam matriks yang ditentukan `newColorMatrix`. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getMatrix00()](#getMatrix00--) | Mendapatkan elemen pada baris 0 (nol) dan kolom 0 dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) ini. |
| [setMatrix00(float value)](#setMatrix00-float-) | Mengatur elemen pada baris 0 (nol) dan kolom 0 dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) ini. |
| [getMatrix01()](#getMatrix01--) | Mendapatkan elemen pada baris 0 (nol) dan kolom pertama dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) ini. |
| [setMatrix01(float value)](#setMatrix01-float-) | Mengatur elemen pada baris 0 (nol) dan kolom pertama dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) ini. |
| [getMatrix02()](#getMatrix02--) | Mendapatkan elemen pada baris 0 (nol) dan kolom kedua dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) ini. |
| [setMatrix02(float value)](#setMatrix02-float-) | Mengatur elemen pada baris 0 (nol) dan kolom kedua dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) ini. |
| [getMatrix03()](#getMatrix03--) | Mendapatkan elemen pada baris 0 (nol) dan kolom ketiga dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) ini. |
| [setMatrix03(float value)](#setMatrix03-float-) | Mengatur elemen pada baris ke-0 (nol) dan kolom ketiga dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix04()](#getMatrix04--) | Mendapatkan elemen pada baris ke-0 (nol) dan kolom keempat dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix04(float value)](#setMatrix04-float-) | Mengatur elemen pada baris ke-0 (nol) dan kolom keempat dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix10()](#getMatrix10--) | Mendapatkan elemen pada baris pertama dan kolom ke-0 (nol) dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix10(float value)](#setMatrix10-float-) | Mengatur elemen pada baris pertama dan kolom ke-0 (nol) dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix11()](#getMatrix11--) | Mendapatkan elemen pada baris pertama dan kolom pertama dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix11(float value)](#setMatrix11-float-) | Mengatur elemen pada baris pertama dan kolom pertama dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix12()](#getMatrix12--) | Mendapatkan elemen pada baris pertama dan kolom kedua dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix12(float value)](#setMatrix12-float-) | Mengatur elemen pada baris pertama dan kolom kedua dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix13()](#getMatrix13--) | Mendapatkan elemen pada baris pertama dan kolom ketiga dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix13(float value)](#setMatrix13-float-) | Mengatur elemen pada baris pertama dan kolom ketiga dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix14()](#getMatrix14--) | Mendapatkan elemen pada baris pertama dan kolom keempat dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix14(float value)](#setMatrix14-float-) | Mengatur elemen pada baris pertama dan kolom keempat dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix20()](#getMatrix20--) | Mendapatkan elemen pada baris kedua dan kolom ke-0 (nol) dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix20(float value)](#setMatrix20-float-) | Mengatur elemen pada baris kedua dan kolom ke-0 (nol) dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix21()](#getMatrix21--) | Mendapatkan elemen pada baris kedua dan kolom pertama dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix21(float value)](#setMatrix21-float-) | Mengatur elemen pada baris kedua dan kolom pertama dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix22()](#getMatrix22--) | Mendapatkan elemen pada baris kedua dan kolom kedua dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix22(float value)](#setMatrix22-float-) | Mengatur elemen pada baris kedua dan kolom kedua dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix23()](#getMatrix23--) | Mendapatkan elemen pada baris kedua dan kolom ketiga dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix23(float value)](#setMatrix23-float-) | Mengatur elemen pada baris kedua dan kolom ketiga dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix24()](#getMatrix24--) | Mendapatkan elemen pada baris kedua dan kolom keempat dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix24(float value)](#setMatrix24-float-) | Mengatur elemen pada baris kedua dan kolom keempat dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix30()](#getMatrix30--) | Mendapatkan elemen pada baris ketiga dan kolom ke-0 (nol) dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix30(float value)](#setMatrix30-float-) | Mengatur elemen pada baris ketiga dan kolom ke-0 (nol) dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix31()](#getMatrix31--) | Mendapatkan elemen pada baris ketiga dan kolom pertama dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix31(float value)](#setMatrix31-float-) | Mengatur elemen pada baris ketiga dan kolom pertama dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix32()](#getMatrix32--) | Mendapatkan elemen pada baris ketiga dan kolom kedua dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix32(float value)](#setMatrix32-float-) | Mengatur elemen pada baris ketiga dan kolom kedua dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix33()](#getMatrix33--) | Mendapatkan elemen pada baris ketiga dan kolom ketiga dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix33(float value)](#setMatrix33-float-) | Mengatur elemen pada baris ketiga dan kolom ketiga dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix34()](#getMatrix34--) | Mendapatkan elemen pada baris ketiga dan kolom keempat dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix34(float value)](#setMatrix34-float-) | Mengatur elemen pada baris ketiga dan kolom keempat dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix40()](#getMatrix40--) | Mendapatkan elemen pada baris keempat dan kolom 0 (nol) dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix40(float value)](#setMatrix40-float-) | Mengatur elemen pada baris keempat dan kolom 0 (nol) dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix41()](#getMatrix41--) | Mendapatkan elemen pada baris keempat dan kolom pertama dari `.ColorMatrix`. |
| [setMatrix41(float value)](#setMatrix41-float-) | Mengatur elemen pada baris keempat dan kolom pertama dari `.ColorMatrix`. |
| [getMatrix42()](#getMatrix42--) | Mendapatkan elemen pada baris keempat dan kolom kedua dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix42(float value)](#setMatrix42-float-) | Mengatur elemen pada baris keempat dan kolom kedua dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix43()](#getMatrix43--) | Mendapatkan elemen pada baris keempat dan kolom ketiga dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix43(float value)](#setMatrix43-float-) | Mengatur elemen pada baris keempat dan kolom ketiga dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix44()](#getMatrix44--) | Mendapatkan elemen pada baris keempat dan kolom keempat dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix44(float value)](#setMatrix44-float-) | Mengatur elemen pada baris keempat dan kolom keempat dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [get_Item(int row, int column)](#get-Item-int-int-) | Mendapatkan elemen pada baris dan kolom yang ditentukan dalam [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [set_Item(int row, int column, float value)](#set-Item-int-int-float-) | Mengatur elemen pada baris dan kolom yang ditentukan dalam [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
### ColorMatrix() {#ColorMatrix--}
```
public ColorMatrix()
```


Menginisialisasi instance baru dari kelas [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

### ColorMatrix(float[][] newColorMatrix) {#ColorMatrix-float-----}
```
public ColorMatrix(float[][] newColorMatrix)
```


Menginisialisasi instance baru dari kelas [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) menggunakan elemen-elemen dalam matriks yang ditentukan `newColorMatrix`.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| newColorMatrix | float[][] | Nilai-nilai elemen untuk [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) baru. |

### getMatrix00() {#getMatrix00--}
```
public float getMatrix00()
```


Mendapatkan elemen pada baris 0 (nol) dan kolom 0 dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) ini.

**Returns:**
float - elemen pada baris 0 (nol) dan kolom 0 dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix00(float value) {#setMatrix00-float-}
```
public void setMatrix00(float value)
```


Mengatur elemen pada baris 0 (nol) dan kolom 0 dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float | elemen pada baris 0 (nol) dan kolom 0 dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix01() {#getMatrix01--}
```
public float getMatrix01()
```


Mendapatkan elemen pada baris 0 (nol) dan kolom pertama dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) ini.

**Returns:**
float - elemen pada baris 0 (nol) dan kolom pertama dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix01(float value) {#setMatrix01-float-}
```
public void setMatrix01(float value)
```


Mengatur elemen pada baris 0 (nol) dan kolom pertama dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float | elemen pada baris 0 (nol) dan kolom pertama dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix02() {#getMatrix02--}
```
public float getMatrix02()
```


Mendapatkan elemen pada baris 0 (nol) dan kolom kedua dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) ini.

**Returns:**
float - elemen pada baris 0 (nol) dan kolom kedua dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix02(float value) {#setMatrix02-float-}
```
public void setMatrix02(float value)
```


Mengatur elemen pada baris 0 (nol) dan kolom kedua dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float | elemen pada baris 0 (nol) dan kolom kedua dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix03() {#getMatrix03--}
```
public float getMatrix03()
```


Mendapatkan elemen pada baris 0 (nol) dan kolom ketiga dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) ini.

**Returns:**
float - elemen pada baris 0 (nol) dan kolom ketiga dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix03(float value) {#setMatrix03-float-}
```
public void setMatrix03(float value)
```


Mengatur elemen pada baris ke-0 (nol) dan kolom ketiga dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float | elemen pada baris 0 (nol) dan kolom ketiga dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix04() {#getMatrix04--}
```
public float getMatrix04()
```


Mendapatkan elemen pada baris ke-0 (nol) dan kolom keempat dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - elemen pada baris 0 (nol) dan kolom keempat dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix04(float value) {#setMatrix04-float-}
```
public void setMatrix04(float value)
```


Mengatur elemen pada baris ke-0 (nol) dan kolom keempat dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float | elemen pada baris 0 (nol) dan kolom keempat dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix10() {#getMatrix10--}
```
public float getMatrix10()
```


Mendapatkan elemen pada baris pertama dan kolom ke-0 (nol) dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - elemen pada baris pertama dan kolom 0 (nol) dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix10(float value) {#setMatrix10-float-}
```
public void setMatrix10(float value)
```


Mengatur elemen pada baris pertama dan kolom ke-0 (nol) dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float | elemen pada baris pertama dan kolom 0 (nol) dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix11() {#getMatrix11--}
```
public float getMatrix11()
```


Mendapatkan elemen pada baris pertama dan kolom pertama dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - elemen pada baris pertama dan kolom pertama dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix11(float value) {#setMatrix11-float-}
```
public void setMatrix11(float value)
```


Mengatur elemen pada baris pertama dan kolom pertama dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float | elemen pada baris pertama dan kolom pertama dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix12() {#getMatrix12--}
```
public float getMatrix12()
```


Mendapatkan elemen pada baris pertama dan kolom kedua dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - elemen pada baris pertama dan kolom kedua dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix12(float value) {#setMatrix12-float-}
```
public void setMatrix12(float value)
```


Mengatur elemen pada baris pertama dan kolom kedua dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float | elemen pada baris pertama dan kolom kedua dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix13() {#getMatrix13--}
```
public float getMatrix13()
```


Mendapatkan elemen pada baris pertama dan kolom ketiga dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - elemen pada baris pertama dan kolom ketiga dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix13(float value) {#setMatrix13-float-}
```
public void setMatrix13(float value)
```


Mengatur elemen pada baris pertama dan kolom ketiga dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float | elemen pada baris pertama dan kolom ketiga dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix14() {#getMatrix14--}
```
public float getMatrix14()
```


Mendapatkan elemen pada baris pertama dan kolom keempat dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - elemen pada baris pertama dan kolom keempat dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix14(float value) {#setMatrix14-float-}
```
public void setMatrix14(float value)
```


Mengatur elemen pada baris pertama dan kolom keempat dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float | elemen pada baris pertama dan kolom keempat dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix20() {#getMatrix20--}
```
public float getMatrix20()
```


Mendapatkan elemen pada baris kedua dan kolom ke-0 (nol) dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - elemen pada baris kedua dan kolom 0 (nol) dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix20(float value) {#setMatrix20-float-}
```
public void setMatrix20(float value)
```


Mengatur elemen pada baris kedua dan kolom ke-0 (nol) dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float | elemen pada baris kedua dan kolom 0 (nol) dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix21() {#getMatrix21--}
```
public float getMatrix21()
```


Mendapatkan elemen pada baris kedua dan kolom pertama dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - elemen pada baris kedua dan kolom pertama dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix21(float value) {#setMatrix21-float-}
```
public void setMatrix21(float value)
```


Mengatur elemen pada baris kedua dan kolom pertama dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float | elemen pada baris kedua dan kolom pertama dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix22() {#getMatrix22--}
```
public float getMatrix22()
```


Mendapatkan elemen pada baris kedua dan kolom kedua dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - elemen pada baris kedua dan kolom kedua dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix22(float value) {#setMatrix22-float-}
```
public void setMatrix22(float value)
```


Mengatur elemen pada baris kedua dan kolom kedua dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float | elemen pada baris kedua dan kolom kedua dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix23() {#getMatrix23--}
```
public float getMatrix23()
```


Mendapatkan elemen pada baris kedua dan kolom ketiga dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - elemen pada baris kedua dan kolom ketiga dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix23(float value) {#setMatrix23-float-}
```
public void setMatrix23(float value)
```


Mengatur elemen pada baris kedua dan kolom ketiga dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float | elemen pada baris kedua dan kolom ketiga dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix24() {#getMatrix24--}
```
public float getMatrix24()
```


Mendapatkan elemen pada baris kedua dan kolom keempat dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - elemen pada baris kedua dan kolom keempat dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix24(float value) {#setMatrix24-float-}
```
public void setMatrix24(float value)
```


Mengatur elemen pada baris kedua dan kolom keempat dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float | elemen pada baris kedua dan kolom keempat dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) ini. |

### getMatrix30() {#getMatrix30--}
```
public float getMatrix30()
```


Mendapatkan elemen pada baris ketiga dan kolom ke-0 (nol) dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - elemen pada baris ketiga dan kolom 0 (nol) dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) ini.
### setMatrix30(float value) {#setMatrix30-float-}
```
public void setMatrix30(float value)
```


Mengatur elemen pada baris ketiga dan kolom ke-0 (nol) dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float | elemen pada baris ketiga dan kolom 0 (nol) dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) ini. |

### getMatrix31() {#getMatrix31--}
```
public float getMatrix31()
```


Mendapatkan elemen pada baris ketiga dan kolom pertama dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - elemen pada baris ketiga dan kolom pertama dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) ini.
### setMatrix31(float value) {#setMatrix31-float-}
```
public void setMatrix31(float value)
```


Mengatur elemen pada baris ketiga dan kolom pertama dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float | elemen pada baris ketiga dan kolom pertama dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) ini. |

### getMatrix32() {#getMatrix32--}
```
public float getMatrix32()
```


Mendapatkan elemen pada baris ketiga dan kolom kedua dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - elemen pada baris ketiga dan kolom kedua dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) ini.
### setMatrix32(float value) {#setMatrix32-float-}
```
public void setMatrix32(float value)
```


Mengatur elemen pada baris ketiga dan kolom kedua dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float | elemen pada baris ketiga dan kolom kedua dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) ini. |

### getMatrix33() {#getMatrix33--}
```
public float getMatrix33()
```


Mendapatkan elemen pada baris ketiga dan kolom ketiga dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - elemen pada baris ketiga dan kolom ketiga dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) ini.
### setMatrix33(float value) {#setMatrix33-float-}
```
public void setMatrix33(float value)
```


Mengatur elemen pada baris ketiga dan kolom ketiga dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float | elemen pada baris ketiga dan kolom ketiga dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) ini. |

### getMatrix34() {#getMatrix34--}
```
public float getMatrix34()
```


Mendapatkan elemen pada baris ketiga dan kolom keempat dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - elemen pada baris ketiga dan kolom keempat dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) ini.
### setMatrix34(float value) {#setMatrix34-float-}
```
public void setMatrix34(float value)
```


Mengatur elemen pada baris ketiga dan kolom keempat dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float | elemen pada baris ketiga dan kolom keempat dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) ini. |

### getMatrix40() {#getMatrix40--}
```
public float getMatrix40()
```


Mendapatkan elemen pada baris keempat dan kolom 0 (nol) dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - elemen pada baris keempat dan kolom 0 (nol) dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) ini.
### setMatrix40(float value) {#setMatrix40-float-}
```
public void setMatrix40(float value)
```


Mengatur elemen pada baris keempat dan kolom 0 (nol) dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float | elemen pada baris keempat dan kolom 0 (nol) dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) ini. |

### getMatrix41() {#getMatrix41--}
```
public float getMatrix41()
```


Mendapatkan elemen pada baris keempat dan kolom pertama dari `.ColorMatrix`.

**Returns:**
float - elemen pada baris keempat dan kolom pertama dari `.ColorMatrix`.
### setMatrix41(float value) {#setMatrix41-float-}
```
public void setMatrix41(float value)
```


Mengatur elemen pada baris keempat dan kolom pertama dari `.ColorMatrix`.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float | elemen pada baris keempat dan kolom pertama dari `.ColorMatrix`. |

### getMatrix42() {#getMatrix42--}
```
public float getMatrix42()
```


Mendapatkan elemen pada baris keempat dan kolom kedua dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - elemen pada baris keempat dan kolom kedua dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) ini.
### setMatrix42(float value) {#setMatrix42-float-}
```
public void setMatrix42(float value)
```


Mengatur elemen pada baris keempat dan kolom kedua dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float | elemen pada baris keempat dan kolom kedua dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) ini. |

### getMatrix43() {#getMatrix43--}
```
public float getMatrix43()
```


Mendapatkan elemen pada baris keempat dan kolom ketiga dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - elemen pada baris keempat dan kolom ketiga dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) ini.
### setMatrix43(float value) {#setMatrix43-float-}
```
public void setMatrix43(float value)
```


Mengatur elemen pada baris keempat dan kolom ketiga dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float | elemen pada baris keempat dan kolom ketiga dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) ini. |

### getMatrix44() {#getMatrix44--}
```
public float getMatrix44()
```


Mendapatkan elemen pada baris keempat dan kolom keempat dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - elemen pada baris keempat dan kolom keempat dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) ini.
### setMatrix44(float value) {#setMatrix44-float-}
```
public void setMatrix44(float value)
```


Mengatur elemen pada baris keempat dan kolom keempat dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float | elemen pada baris keempat dan kolom keempat dari [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) ini. |

### get_Item(int row, int column) {#get-Item-int-int-}
```
public float get_Item(int row, int column)
```


Mendapatkan elemen pada baris dan kolom yang ditentukan dalam [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| baris | int | Baris elemen. |
| kolom | int | Kolom elemen. |

**Returns:**
float - Elemen pada baris dan kolom yang ditentukan.
### set_Item(int row, int column, float value) {#set-Item-int-int-float-}
```
public void set_Item(int row, int column, float value)
```


Mengatur elemen pada baris dan kolom yang ditentukan dalam [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| baris | int | Baris elemen. |
| kolom | int | Kolom elemen. |
| value | float | elemen pada baris dan kolom yang ditentukan dalam [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

