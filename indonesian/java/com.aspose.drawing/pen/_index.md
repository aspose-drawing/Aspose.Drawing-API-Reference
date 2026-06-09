---
title: Pen
second_title: Referensi API Aspose.Drawing for Java
description: Mendefinisikan objek yang digunakan untuk menggambar garis dan kurva.
type: docs
weight: 34
url: /id/java/com.aspose.drawing/pen/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public class Pen implements System.IDisposable
```

Mendefinisikan objek yang digunakan untuk menggambar garis dan kurva.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [Pen(Color color)](#Pen-com.aspose.drawing.Color-) | Menginisialisasi instance baru dari kelas [Pen](../../com.aspose.drawing/pen) dengan `Color` yang ditentukan([.getColor](../../null/\#getColor)/[.setColor(Color)](../../null/\#setColor-Color-)). |
| [Pen(Brush brush, float width)](#Pen-com.aspose.drawing.Brush-float-) | Menginisialisasi instance baru dari kelas Pen dengan Brush dan Width yang ditentukan. |
| [Pen(Brush brush)](#Pen-com.aspose.drawing.Brush-) | Menginisialisasi instance baru dari kelas [Pen](../../com.aspose.drawing/pen) dengan `Brush` yang ditentukan([.getBrush](../../null/\#getBrush)/[.setBrush(Brush)](../../null/\#setBrush-Brush-)). |
| [Pen(Color color, float width)](#Pen-com.aspose.drawing.Color-float-) | Menginisialisasi instance baru dari kelas Pen dengan properti Color dan Width yang ditentukan. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getColor()](#getColor--) | Mendapatkan atau mengatur warna dari [Pen](../../com.aspose.drawing/pen) ini. |
| [setColor(Color value)](#setColor-com.aspose.drawing.Color-) | Mendapatkan atau mengatur warna dari [Pen](../../com.aspose.drawing/pen) ini. |
| [getBrush()](#getBrush--) | Mendapatkan atau mengatur Brush yang menentukan atribut dari [Pen](../../com.aspose.drawing/pen) ini. |
| [setBrush(Brush value)](#setBrush-com.aspose.drawing.Brush-) | Mendapatkan atau mengatur Brush yang menentukan atribut dari [Pen](../../com.aspose.drawing/pen) ini. |
| [getCompoundArray()](#getCompoundArray--) | Mendapatkan atau mengatur array nilai yang menentukan pena gabungan. |
| [setCompoundArray(float[] value)](#setCompoundArray-float---) | Mendapatkan atau mengatur array nilai yang menentukan pena gabungan. |
| [getWidth()](#getWidth--) | Mendapatkan atau mengatur lebar Pen ini, dalam satuan objek Graphics yang digunakan untuk menggambar. |
| [setWidth(float value)](#setWidth-float-) | Mendapatkan atau mengatur lebar Pen ini, dalam satuan objek Graphics yang digunakan untuk menggambar. |
| [getStartCap()](#getStartCap--) | Mendapatkan atau mengatur gaya cap yang digunakan di awal garis yang digambar dengan Pen ini. |
| [setStartCap(int value)](#setStartCap-int-) | Mendapatkan atau mengatur gaya cap yang digunakan di awal garis yang digambar dengan Pen ini. |
| [getEndCap()](#getEndCap--) | Mendapatkan atau mengatur gaya cap yang digunakan di akhir garis yang digambar dengan Pen ini. |
| [setEndCap(int value)](#setEndCap-int-) | Mendapatkan atau mengatur gaya cap yang digunakan di akhir garis yang digambar dengan Pen ini. |
| [getLineJoin()](#getLineJoin--) | Mendapatkan atau mengatur gaya sambungan untuk ujung dua garis berurutan yang digambar dengan Pen ini. |
| [setLineJoin(int value)](#setLineJoin-int-) | Mendapatkan atau mengatur gaya sambungan untuk ujung dua garis berurutan yang digambar dengan Pen ini. |
| [getMiterLimit()](#getMiterLimit--) | Mendapatkan atau mengatur batas ketebalan sambungan pada sudut miter. |
| [setMiterLimit(float value)](#setMiterLimit-float-) | Mendapatkan atau mengatur batas ketebalan sambungan pada sudut miter. |
| [getAlignment()](#getAlignment--) | Mendapatkan atau mengatur perataan untuk [Pen](../../com.aspose.drawing/pen) ini. |
| [setAlignment(int value)](#setAlignment-int-) | Mendapatkan atau mengatur perataan untuk [Pen](../../com.aspose.drawing/pen) ini. |
| [getTransform()](#getTransform--) | Mendapatkan atau mengatur salinan transformasi geometrik untuk [Pen](../../com.aspose.drawing/pen) ini. |
| [setTransform(Matrix value)](#setTransform-com.aspose.drawing.drawing2d.Matrix-) | Mendapatkan atau mengatur salinan transformasi geometrik untuk [Pen](../../com.aspose.drawing/pen) ini. |
| [getCustomStartCap()](#getCustomStartCap--) | Mendapatkan atau mengatur cap khusus yang digunakan di awal garis yang digambar dengan [Pen](../../com.aspose.drawing/pen) ini. |
| [setCustomStartCap(CustomLineCap value)](#setCustomStartCap-com.aspose.drawing.drawing2d.CustomLineCap-) | Mendapatkan atau mengatur cap khusus yang digunakan di awal garis yang digambar dengan [Pen](../../com.aspose.drawing/pen) ini. |
| [getCustomEndCap()](#getCustomEndCap--) | Mendapatkan atau mengatur cap khusus yang digunakan di akhir garis yang digambar dengan [Pen](../../com.aspose.drawing/pen) ini. |
| [setCustomEndCap(CustomLineCap value)](#setCustomEndCap-com.aspose.drawing.drawing2d.CustomLineCap-) | Mendapatkan atau mengatur cap khusus yang digunakan di akhir garis yang digambar dengan [Pen](../../com.aspose.drawing/pen) ini. |
| [getDashCap()](#getDashCap--) | Mendapatkan atau mengatur gaya cap yang digunakan di akhir garis putus-putus yang membentuk garis dash yang digambar dengan [Pen](../../com.aspose.drawing/pen) ini. |
| [setDashCap(int value)](#setDashCap-int-) | Mendapatkan atau mengatur gaya cap yang digunakan di akhir garis putus-putus yang membentuk garis dash yang digambar dengan [Pen](../../com.aspose.drawing/pen) ini. |
| [getDashOffset()](#getDashOffset--) | Mendapatkan atau mengatur jarak dari awal garis ke permulaan pola dash. |
| [setDashOffset(float value)](#setDashOffset-float-) | Mendapatkan atau mengatur jarak dari awal garis ke permulaan pola dash. |
| [getDashPattern()](#getDashPattern--) | Mendapatkan atau mengatur array dash khusus dan spasi. |
| [setDashPattern(float[] value)](#setDashPattern-float---) | Mendapatkan atau mengatur array dash khusus dan spasi. |
| [getDashStyle()](#getDashStyle--) | Mendapatkan atau mengatur gaya yang digunakan untuk garis putus-putus yang digambar dengan [Pen](../../com.aspose.drawing/pen) ini. |
| [setDashStyle(int value)](#setDashStyle-int-) | Mendapatkan atau mengatur gaya yang digunakan untuk garis putus-putus yang digambar dengan [Pen](../../com.aspose.drawing/pen) ini. |
| [getPenType()](#getPenType--) | Mendapatkan gaya garis yang digambar dengan Pen ini. |
| [dispose()](#dispose--) | Melepaskan semua sumber daya yang digunakan oleh Pen ini. |
| [deepClone()](#deepClone--) | Membuat salinan persis dari [Pen](../../com.aspose.drawing/pen) ini. |
| [setLineCap(int startCap, int endCap, int dashCap)](#setLineCap-int-int-int-) | Mengatur nilai yang menentukan gaya cap yang digunakan untuk mengakhiri garis yang digambar oleh [Pen](../../com.aspose.drawing/pen) ini. |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | Menskalakan transformasi geometrik lokal dengan faktor yang ditentukan. |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | Menskalakan transformasi geometrik lokal dengan faktor yang ditentukan dalam urutan yang ditentukan. |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | Menerjemahkan transformasi geometrik lokal dengan dimensi yang ditentukan. |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | Menerjemahkan transformasi geometrik lokal dengan dimensi yang ditentukan dalam urutan yang ditentukan. |
| [rotateTransform(float angle)](#rotateTransform-float-) | Memutar transformasi geometrik lokal dengan sudut yang ditentukan. |
| [rotateTransform(float angle, int order)](#rotateTransform-float-int-) | Memutar transformasi geometrik lokal dengan sudut yang ditentukan dalam urutan yang ditentukan. |
| [resetTransform()](#resetTransform--) | Mengatur ulang matriks transformasi geometrik untuk [Pen](../../com.aspose.drawing/pen) ini menjadi identitas. |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-) | Mengalikan matriks transformasi untuk [Pen](../../com.aspose.drawing/pen) ini dengan [Matrix](../../com.aspose.drawing.drawing2d/matrix) yang ditentukan. |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-int-) | Mengalikan matriks transformasi untuk [Pen](../../com.aspose.drawing/pen) ini dengan [Matrix](../../com.aspose.drawing.drawing2d/matrix) yang ditentukan dalam urutan yang ditentukan. |
### Pen(Color color) {#Pen-com.aspose.drawing.Color-}
```
public Pen(Color color)
```


Menginisialisasi instance baru dari kelas [Pen](../../com.aspose.drawing/pen) dengan `Color` yang ditentukan([.getColor](../../null/\#getColor)/[.setColor(Color)](../../null/\#setColor-Color-)).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| color | [Color](../../com.aspose.drawing/color) | Sebuah `Color`([.getColor](../../null/\#getColor)/[.setColor(Color)](../../null/\#setColor-Color-)) yang menentukan properti isi dari [Pen](../../com.aspose.drawing/pen) ini. |

### Pen(Brush brush, float width) {#Pen-com.aspose.drawing.Brush-float-}
```
public Pen(Brush brush, float width)
```


Menginisialisasi instance baru dari kelas Pen dengan Brush dan Width yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.drawing/brush) | Sebuah Brush yang menentukan karakteristik dari Pen ini. |
| lebar | float | Lebar Pen baru. |

### Pen(Brush brush) {#Pen-com.aspose.drawing.Brush-}
```
public Pen(Brush brush)
```


Menginisialisasi instance baru dari kelas [Pen](../../com.aspose.drawing/pen) dengan `Brush` yang ditentukan([.getBrush](../../null/\#getBrush)/[.setBrush(Brush)](../../null/\#setBrush-Brush-)).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.drawing/brush) | Sebuah `Brush`([.getBrush](../../null/\#getBrush)/[.setBrush(Brush)](../../null/\#setBrush-Brush-)) yang menentukan properti isi dari [Pen](../../com.aspose.drawing/pen) ini. |

### Pen(Color color, float width) {#Pen-com.aspose.drawing.Color-float-}
```
public Pen(Color color, float width)
```


Menginisialisasi instance baru dari kelas Pen dengan properti Color dan Width yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| color | [Color](../../com.aspose.drawing/color) | Struktur Color yang menunjukkan warna Pen ini. |
| lebar | float | Nilai yang menunjukkan lebar Pen ini. |

### getColor() {#getColor--}
```
public final Color getColor()
```


Mendapatkan atau mengatur warna dari [Pen](../../com.aspose.drawing/pen) ini.

Nilai: Struktur `Color`([.getColor](../../null/\#getColor)/[.setColor(Color)](../../null/\#setColor-Color-)) yang mewakili warna [Pen](../../com.aspose.drawing/pen).

**Returns:**
[Color](../../com.aspose.drawing/color)
### setColor(Color value) {#setColor-com.aspose.drawing.Color-}
```
public final void setColor(Color value)
```


Mendapatkan atau mengatur warna dari [Pen](../../com.aspose.drawing/pen) ini.

Nilai: Struktur `Color`([.getColor](../../null/\#getColor)/[.setColor(Color)](../../null/\#setColor-Color-)) yang mewakili warna [Pen](../../com.aspose.drawing/pen).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Color](../../com.aspose.drawing/color) |  |

### getBrush() {#getBrush--}
```
public final Brush getBrush()
```


Mendapatkan atau mengatur Brush yang menentukan atribut dari [Pen](../../com.aspose.drawing/pen) ini.

**Returns:**
[Brush](../../com.aspose.drawing/brush)
### setBrush(Brush value) {#setBrush-com.aspose.drawing.Brush-}
```
public final void setBrush(Brush value)
```


Mendapatkan atau mengatur Brush yang menentukan atribut dari [Pen](../../com.aspose.drawing/pen) ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Brush](../../com.aspose.drawing/brush) |  |

### getCompoundArray() {#getCompoundArray--}
```
public final float[] getCompoundArray()
```


Mendapatkan atau mengatur array nilai yang menentukan pena komposit. Pena komposit menggambar garis komposit yang terdiri dari garis paralel dan ruang.

**Returns:**
float[] - Array angka real yang menentukan array komposit. Elemen dalam array harus dalam urutan meningkat, tidak kurang dari 0, dan tidak lebih dari 1.
### setCompoundArray(float[] value) {#setCompoundArray-float---}
```
public final void setCompoundArray(float[] value)
```


Mendapatkan atau mengatur array nilai yang menentukan pena komposit. Pena komposit menggambar garis komposit yang terdiri dari garis paralel dan ruang.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float[] |  |

### getWidth() {#getWidth--}
```
public final float getWidth()
```


Mendapatkan atau mengatur lebar Pen ini, dalam satuan objek Graphics yang digunakan untuk menggambar.

**Returns:**
float
### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```


Mendapatkan atau mengatur lebar Pen ini, dalam satuan objek Graphics yang digunakan untuk menggambar.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float |  |

### getStartCap() {#getStartCap--}
```
public final int getStartCap()
```


Mendapatkan atau mengatur gaya cap yang digunakan di awal garis yang digambar dengan Pen ini.

**Returns:**
int
### setStartCap(int value) {#setStartCap-int-}
```
public final void setStartCap(int value)
```


Mendapatkan atau mengatur gaya cap yang digunakan di awal garis yang digambar dengan Pen ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getEndCap() {#getEndCap--}
```
public final int getEndCap()
```


Mendapatkan atau mengatur gaya cap yang digunakan di akhir garis yang digambar dengan Pen ini.

**Returns:**
int
### setEndCap(int value) {#setEndCap-int-}
```
public final void setEndCap(int value)
```


Mendapatkan atau mengatur gaya cap yang digunakan di akhir garis yang digambar dengan Pen ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getLineJoin() {#getLineJoin--}
```
public final int getLineJoin()
```


Mendapatkan atau mengatur gaya sambungan untuk ujung dua garis berurutan yang digambar dengan Pen ini.

--------------------

Saat ini sambungan Miter sebenarnya berfungsi sebagai MiterClipped.

**Returns:**
int
### setLineJoin(int value) {#setLineJoin-int-}
```
public final void setLineJoin(int value)
```


Mendapatkan atau mengatur gaya sambungan untuk ujung dua garis berurutan yang digambar dengan Pen ini.

--------------------

Saat ini sambungan Miter sebenarnya berfungsi sebagai MiterClipped.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getMiterLimit() {#getMiterLimit--}
```
public final float getMiterLimit()
```


Mendapatkan atau mengatur batas ketebalan sambungan pada sudut miter.

**Returns:**
float
### setMiterLimit(float value) {#setMiterLimit-float-}
```
public final void setMiterLimit(float value)
```


Mendapatkan atau mengatur batas ketebalan sambungan pada sudut miter.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float |  |

### getAlignment() {#getAlignment--}
```
public final int getAlignment()
```


Mendapatkan atau mengatur perataan untuk [Pen](../../com.aspose.drawing/pen) ini.

**Returns:**
int - Sebuah [PenAlignment](../../com.aspose.drawing.drawing2d/penalignment) yang mewakili perataan untuk [Pen](../../com.aspose.drawing/pen).
### setAlignment(int value) {#setAlignment-int-}
```
public final void setAlignment(int value)
```


Mendapatkan atau mengatur perataan untuk [Pen](../../com.aspose.drawing/pen) ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getTransform() {#getTransform--}
```
public final Matrix getTransform()
```


Mendapatkan atau mengatur salinan transformasi geometrik untuk [Pen](../../com.aspose.drawing/pen) ini.

Nilai: Salinan [Matrix](../../com.aspose.drawing.drawing2d/matrix) yang mewakili transformasi geometrik untuk [Pen](../../com.aspose.drawing/pen).

**Returns:**
[Matrix](../../com.aspose.drawing.drawing2d/matrix)
### setTransform(Matrix value) {#setTransform-com.aspose.drawing.drawing2d.Matrix-}
```
public final void setTransform(Matrix value)
```


Mendapatkan atau mengatur salinan transformasi geometrik untuk [Pen](../../com.aspose.drawing/pen) ini.

Nilai: Salinan [Matrix](../../com.aspose.drawing.drawing2d/matrix) yang mewakili transformasi geometrik untuk [Pen](../../com.aspose.drawing/pen).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.drawing.drawing2d/matrix) |  |

### getCustomStartCap() {#getCustomStartCap--}
```
public final CustomLineCap getCustomStartCap()
```


Mendapatkan atau mengatur cap khusus yang digunakan di awal garis yang digambar dengan [Pen](../../com.aspose.drawing/pen) ini.

**Returns:**
[CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) - A [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) that represents the cap used at the beginning of lines drawn with this [Pen](../../com.aspose.drawing/pen).
### setCustomStartCap(CustomLineCap value) {#setCustomStartCap-com.aspose.drawing.drawing2d.CustomLineCap-}
```
public final void setCustomStartCap(CustomLineCap value)
```


Mendapatkan atau mengatur cap khusus yang digunakan di awal garis yang digambar dengan [Pen](../../com.aspose.drawing/pen) ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) |  |

### getCustomEndCap() {#getCustomEndCap--}
```
public final CustomLineCap getCustomEndCap()
```


Mendapatkan atau mengatur cap khusus yang digunakan di akhir garis yang digambar dengan [Pen](../../com.aspose.drawing/pen) ini.

**Returns:**
[CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) - A [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) that represents the cap used at the end of lines drawn with this [Pen](../../com.aspose.drawing/pen).
### setCustomEndCap(CustomLineCap value) {#setCustomEndCap-com.aspose.drawing.drawing2d.CustomLineCap-}
```
public final void setCustomEndCap(CustomLineCap value)
```


Mendapatkan atau mengatur cap khusus yang digunakan di akhir garis yang digambar dengan [Pen](../../com.aspose.drawing/pen) ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) |  |

### getDashCap() {#getDashCap--}
```
public final int getDashCap()
```


Mendapatkan atau mengatur gaya cap yang digunakan di akhir garis putus-putus yang membentuk garis dash yang digambar dengan [Pen](../../com.aspose.drawing/pen) ini.

**Returns:**
int - Salah satu nilai `DashCap`([.getDashCap](../../null/\#getDashCap)/[.setDashCap(int)](../../null/\#setDashCap-int-)) yang mewakili gaya cap yang digunakan di awal dan akhir garis putus-putus yang membentuk garis bergaris yang digambar dengan [Pen](../../com.aspose.drawing/pen).
### setDashCap(int value) {#setDashCap-int-}
```
public final void setDashCap(int value)
```


Mendapatkan atau mengatur gaya cap yang digunakan di akhir garis putus-putus yang membentuk garis dash yang digambar dengan [Pen](../../com.aspose.drawing/pen) ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getDashOffset() {#getDashOffset--}
```
public final float getDashOffset()
```


Mendapatkan atau mengatur jarak dari awal garis ke permulaan pola dash.

**Returns:**
float - Jarak dari awal garis ke awal pola dash.
### setDashOffset(float value) {#setDashOffset-float-}
```
public final void setDashOffset(float value)
```


Mendapatkan atau mengatur jarak dari awal garis ke permulaan pola dash.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float |  |

### getDashPattern() {#getDashPattern--}
```
public final float[] getDashPattern()
```


Mendapatkan atau mengatur array dash khusus dan spasi.

**Returns:**
float[] - Array angka real yang menentukan panjang dash dan spasi bergantian dalam garis putus-putus.
### setDashPattern(float[] value) {#setDashPattern-float---}
```
public final void setDashPattern(float[] value)
```


Mendapatkan atau mengatur array dash khusus dan spasi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float[] |  |

### getDashStyle() {#getDashStyle--}
```
public final int getDashStyle()
```


Mendapatkan atau mengatur gaya yang digunakan untuk garis putus-putus yang digambar dengan [Pen](../../com.aspose.drawing/pen) ini.

**Returns:**
int - Sebuah `DashStyle`([.getDashStyle](../../null/\#getDashStyle)/[.setDashStyle(int)](../../null/\#setDashStyle-int-)) yang mewakili gaya yang digunakan untuk garis putus‑putus yang digambar dengan [Pen](../../com.aspose.drawing/pen).
### setDashStyle(int value) {#setDashStyle-int-}
```
public final void setDashStyle(int value)
```


Mendapatkan atau mengatur gaya yang digunakan untuk garis putus-putus yang digambar dengan [Pen](../../com.aspose.drawing/pen) ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getPenType() {#getPenType--}
```
public final int getPenType()
```


Mendapatkan gaya garis yang digambar dengan Pen ini.

Nilai: Sebuah enumerasi `PenType`([.getPenType](../../null/\#getPenType)) yang menentukan gaya garis yang digambar dengan [Pen](../../com.aspose.drawing/pen).

**Returns:**
int
### dispose() {#dispose--}
```
public final void dispose()
```


Melepaskan semua sumber daya yang digunakan oleh Pen ini.

--------------------

Metode ini sebenarnya tidak melakukan apa-apa. Ini hanya untuk kompatibilitas dengan API System.Drawing.

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Membuat salinan persis dari [Pen](../../com.aspose.drawing/pen) ini.

**Returns:**
java.lang.Object - Sebuah Objek yang dapat di‑cast menjadi [Pen](../../com.aspose.drawing/pen).
### setLineCap(int startCap, int endCap, int dashCap) {#setLineCap-int-int-int-}
```
public final void setLineCap(int startCap, int endCap, int dashCap)
```


Mengatur nilai yang menentukan gaya cap yang digunakan untuk mengakhiri garis yang digambar oleh [Pen](../../com.aspose.drawing/pen) ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| startCap | int | Sebuah [LineCap](../../com.aspose.drawing.drawing2d/linecap) yang mewakili gaya tutup yang digunakan di awal garis yang digambar dengan [Pen](../../com.aspose.drawing/pen). |
| endCap | int | Sebuah [LineCap](../../com.aspose.drawing.drawing2d/linecap) yang mewakili gaya tutup yang digunakan di akhir garis yang digambar dengan [Pen](../../com.aspose.drawing/pen). |
| dashCap | int | Sebuah [LineCap](../../com.aspose.drawing.drawing2d/linecap) yang mewakili gaya tutup yang digunakan di awal atau akhir garis putus‑putus yang digambar dengan [Pen](../../com.aspose.drawing/pen). |

### scaleTransform(float sx, float sy) {#scaleTransform-float-float-}
```
public final void scaleTransform(float sx, float sy)
```


Menskalakan transformasi geometrik lokal dengan faktor yang ditentukan. Metode ini menambahkan matriks skala ke depan transformasi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sx | float | Faktor yang digunakan untuk menskalakan transformasi pada arah sumbu x. |
| sy | float | Faktor yang digunakan untuk menskalakan transformasi pada arah sumbu y. |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public final void scaleTransform(float sx, float sy, int order)
```


Menskalakan transformasi geometrik lokal dengan faktor yang ditentukan dalam urutan yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sx | float | Faktor yang digunakan untuk menskalakan transformasi pada arah sumbu x. |
| sy | float | Faktor yang digunakan untuk menskalakan transformasi pada arah sumbu y. |
| order | int | Sebuah [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder) yang menentukan apakah akan menambahkan atau menempatkan di depan matriks skala. |

### translateTransform(float dx, float dy) {#translateTransform-float-float-}
```
public final void translateTransform(float dx, float dy)
```


Mentranslasi transformasi geometrik lokal dengan dimensi yang ditentukan. Metode ini menambahkan translasi ke depan transformasi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| dx | float | Nilai translasi pada sumbu x. |
| dy | float | Nilai translasi pada sumbu y. |

### translateTransform(float dx, float dy, int order) {#translateTransform-float-float-int-}
```
public final void translateTransform(float dx, float dy, int order)
```


Menerjemahkan transformasi geometrik lokal dengan dimensi yang ditentukan dalam urutan yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| dx | float | Nilai translasi pada sumbu x. |
| dy | float | Nilai translasi pada sumbu y. |
| urutan | int | Urutan (prepend atau append) dalam menerapkan translasi. |

### rotateTransform(float angle) {#rotateTransform-float-}
```
public final void rotateTransform(float angle)
```


Memutar transformasi geometrik lokal dengan sudut yang ditentukan. Metode ini menambahkan rotasi ke depan transformasi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sudut | float | Sudut rotasi. |

### rotateTransform(float angle, int order) {#rotateTransform-float-int-}
```
public final void rotateTransform(float angle, int order)
```


Memutar transformasi geometrik lokal dengan sudut yang ditentukan dalam urutan yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sudut | float | Sudut rotasi. |
| order | int | Sebuah [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder) yang menentukan apakah akan menambahkan atau menempatkan di depan matriks rotasi. |

### resetTransform() {#resetTransform--}
```
public final void resetTransform()
```


Mengatur ulang matriks transformasi geometrik untuk [Pen](../../com.aspose.drawing/pen) ini menjadi identitas.

### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-}
```
public final void multiplyTransform(Matrix matrix)
```


Mengalikan matriks transformasi untuk [Pen](../../com.aspose.drawing/pen) ini dengan [Matrix](../../com.aspose.drawing.drawing2d/matrix) yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | Objek [Matrix](../../com.aspose.drawing.drawing2d/matrix) yang digunakan untuk mengalikan matriks transformasi. |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-int-}
```
public final void multiplyTransform(Matrix matrix, int order)
```


Mengalikan matriks transformasi untuk [Pen](../../com.aspose.drawing/pen) ini dengan [Matrix](../../com.aspose.drawing.drawing2d/matrix) yang ditentukan dalam urutan yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | java.awt.geom.AffineTransform yang digunakan untuk mengalikan matriks transformasi. |
| urutan | int | Urutan di mana operasi perkalian harus dilakukan. |

