---
title: LinearGradientBrush
second_title: Referensi API Aspose.Drawing for Java
description: Mengkapsulkan  dengan gradien linier.
type: docs
weight: 31
url: /id/java/com.aspose.drawing.drawing2d/lineargradientbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.drawing.Brush](../../com.aspose.drawing/brush)
```
public final class LinearGradientBrush extends Brush
```

Mengkapsulkan [Brush](../../com.aspose.drawing/brush) dengan gradien linier. Kelas ini tidak dapat diwariskan.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [LinearGradientBrush(PointF point1, PointF point2, Color color1, Color color2)](#LinearGradientBrush-com.aspose.drawing.PointF-com.aspose.drawing.PointF-com.aspose.drawing.Color-com.aspose.drawing.Color-) | Menginisialisasi instance baru dari kelas [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) dengan titik dan warna yang ditentukan. |
| [LinearGradientBrush(Point point1, Point point2, Color color1, Color color2)](#LinearGradientBrush-com.aspose.drawing.Point-com.aspose.drawing.Point-com.aspose.drawing.Color-com.aspose.drawing.Color-) | Menginisialisasi instance baru dari kelas [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) dengan titik dan warna yang ditentukan. |
| [LinearGradientBrush(RectangleF rect, Color color1, Color color2, int linearGradientMode)](#LinearGradientBrush-com.aspose.drawing.RectangleF-com.aspose.drawing.Color-com.aspose.drawing.Color-int-) | Menginisialisasi instance baru dari kelas [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) berdasarkan persegi panjang, warna awal dan akhir, serta mode orientasi. |
| [LinearGradientBrush(Rectangle rect, Color color1, Color color2, int linearGradientMode)](#LinearGradientBrush-com.aspose.drawing.Rectangle-com.aspose.drawing.Color-com.aspose.drawing.Color-int-) | Menginisialisasi instance baru dari kelas [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) berdasarkan persegi panjang, warna awal dan akhir, serta orientasi. |
| [LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle)](#LinearGradientBrush-com.aspose.drawing.RectangleF-com.aspose.drawing.Color-com.aspose.drawing.Color-float-) | Menginisialisasi instance baru dari kelas [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) berdasarkan persegi panjang, warna awal dan akhir, serta sudut orientasi. |
| [LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle, boolean isAngleScaleable)](#LinearGradientBrush-com.aspose.drawing.RectangleF-com.aspose.drawing.Color-com.aspose.drawing.Color-float-boolean-) | Menginisialisasi instance baru dari kelas [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) berdasarkan persegi panjang, warna awal dan akhir, serta sudut orientasi. |
| [LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle)](#LinearGradientBrush-com.aspose.drawing.Rectangle-com.aspose.drawing.Color-com.aspose.drawing.Color-float-) | Menginisialisasi instance baru dari kelas [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) berdasarkan persegi panjang, warna awal dan akhir, serta sudut orientasi. |
| [LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle, boolean isAngleScaleable)](#LinearGradientBrush-com.aspose.drawing.Rectangle-com.aspose.drawing.Color-com.aspose.drawing.Color-float-boolean-) | Menginisialisasi instance baru dari kelas [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) berdasarkan persegi panjang, warna awal dan akhir, serta sudut orientasi. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getLinearColors()](#getLinearColors--) | Mendapatkan atau mengatur warna awal dan akhir gradien. |
| [setLinearColors(Color[] value)](#setLinearColors-com.aspose.drawing.Color---) | Mendapatkan atau mengatur warna awal dan akhir gradien. |
| [getRectangle()](#getRectangle--) | Mendapatkan wilayah persegi panjang yang menentukan titik awal dan akhir gradien. |
| [getGammaCorrection()](#getGammaCorrection--) | Mendapatkan atau mengatur nilai yang menunjukkan apakah koreksi gamma diaktifkan untuk [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush). |
| [setGammaCorrection(boolean value)](#setGammaCorrection-boolean-) | Mendapatkan atau mengatur nilai yang menunjukkan apakah koreksi gamma diaktifkan untuk [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush). |
| [getBlend()](#getBlend--) | Mendapatkan atau mengatur `Blend`([.getBlend](../../null/#getBlend)/[.setBlend(Blend)](../../null/#setBlend-Blend-)) yang menentukan posisi dan faktor yang mendefinisikan penurunan khusus untuk gradien. |
| [setBlend(Blend value)](#setBlend-com.aspose.drawing.drawing2d.Blend-) | Mendapatkan atau mengatur `Blend`([.getBlend](../../null/#getBlend)/[.setBlend(Blend)](../../null/#setBlend-Blend-)) yang menentukan posisi dan faktor yang mendefinisikan penurunan khusus untuk gradien. |
| [getInterpolationColors()](#getInterpolationColors--) | Mendapatkan atau mengatur [ColorBlend](../../com.aspose.drawing.drawing2d/colorblend) yang mendefinisikan gradien linear multiwarna. |
| [setInterpolationColors(ColorBlend value)](#setInterpolationColors-com.aspose.drawing.drawing2d.ColorBlend-) | Mendapatkan atau mengatur [ColorBlend](../../com.aspose.drawing.drawing2d/colorblend) yang mendefinisikan gradien linear multiwarna. |
| [getWrapMode()](#getWrapMode--) | Mendapatkan atau mengatur enumerasi `WrapMode` yang menunjukkan mode pembungkus untuk [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush). |
| [setWrapMode(int value)](#setWrapMode-int-) | Mendapatkan atau mengatur enumerasi `WrapMode` yang menunjukkan mode pembungkus untuk [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush). |
| [getTransform()](#getTransform--) | Mendapatkan atau mengatur salinan [Matrix](../../com.aspose.drawing.drawing2d/matrix) yang mendefinisikan transformasi geometris lokal untuk [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush). |
| [setTransform(Matrix value)](#setTransform-com.aspose.drawing.drawing2d.Matrix-) | Mendapatkan atau mengatur salinan [Matrix](../../com.aspose.drawing.drawing2d/matrix) yang mendefinisikan transformasi geometris lokal untuk [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush). |
| [deepClone()](#deepClone--) | Membuat salinan tepat dari [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush). |
| [setSigmaBellShape(float focus)](#setSigmaBellShape-float-) | Membuat penurunan gradien berdasarkan kurva berbentuk lonceng. |
| [setSigmaBellShape(float focus, float scale)](#setSigmaBellShape-float-float-) | Membuat penurunan gradien berdasarkan kurva berbentuk lonceng. |
| [setBlendTriangularShape(float focus)](#setBlendTriangularShape-float-) | Membuat gradien linear dengan warna tengah dan penurunan linear ke satu warna di kedua ujung. |
| [setBlendTriangularShape(float focus, float scale)](#setBlendTriangularShape-float-float-) | Membuat gradien linear dengan warna tengah dan penurunan linear ke satu warna di kedua ujung. |
| [resetTransform()](#resetTransform--) | Mengatur ulang properti `LinearGradientBrush.Transform` ke identitas. |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-) | Mengalikan [Matrix](../../com.aspose.drawing.drawing2d/matrix) yang mewakili transformasi geometris lokal dari [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) dengan [Matrix](../../com.aspose.drawing.drawing2d/matrix) yang ditentukan dengan menambahkan [Matrix](../../com.aspose.drawing.drawing2d/matrix) yang ditentukan di depan. |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-int-) | Mengalikan [Matrix](../../com.aspose.drawing.drawing2d/matrix) yang mewakili transformasi geometris lokal dari [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) dengan [Matrix](../../com.aspose.drawing.drawing2d/matrix) yang ditentukan dalam urutan yang ditentukan. |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | Menerjemahkan transformasi geometris lokal dengan dimensi yang ditentukan. |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | Menerjemahkan transformasi geometris lokal dengan dimensi yang ditentukan dalam urutan yang ditentukan. |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | Menskalakan transformasi geometris lokal dengan jumlah yang ditentukan. |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | Menskalakan transformasi geometris lokal dengan jumlah yang ditentukan dalam urutan yang ditentukan. |
| [rotateTransform(float angle)](#rotateTransform-float-) | Memutar transformasi geometris lokal dengan jumlah yang ditentukan. |
| [rotateTransform(float angle, int order)](#rotateTransform-float-int-) | Memutar transformasi geometris lokal dengan jumlah yang ditentukan dalam urutan yang ditentukan. |
### LinearGradientBrush(PointF point1, PointF point2, Color color1, Color color2) {#LinearGradientBrush-com.aspose.drawing.PointF-com.aspose.drawing.PointF-com.aspose.drawing.Color-com.aspose.drawing.Color-}
```
public LinearGradientBrush(PointF point1, PointF point2, Color color1, Color color2)
```


Menginisialisasi instance baru dari kelas [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) dengan titik dan warna yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| point1 | [PointF](../../com.aspose.drawing/pointf) | Sebuah struktur [PointF](../../com.aspose.drawing/pointf) yang mewakili titik awal gradien linear. |
| point2 | [PointF](../../com.aspose.drawing/pointf) | Sebuah struktur [PointF](../../com.aspose.drawing/pointf) yang mewakili titik akhir gradien linear. |
| color1 | [Color](../../com.aspose.drawing/color) | Sebuah struktur [Color](../../com.aspose.drawing/color) yang mewakili warna awal gradien linear. |
| color2 | [Color](../../com.aspose.drawing/color) | Sebuah struktur [Color](../../com.aspose.drawing/color) yang mewakili warna akhir gradien linear. |

### LinearGradientBrush(Point point1, Point point2, Color color1, Color color2) {#LinearGradientBrush-com.aspose.drawing.Point-com.aspose.drawing.Point-com.aspose.drawing.Color-com.aspose.drawing.Color-}
```
public LinearGradientBrush(Point point1, Point point2, Color color1, Color color2)
```


Menginisialisasi instance baru dari kelas [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) dengan titik dan warna yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.drawing/point) | Sebuah struktur [Point](../../com.aspose.drawing/point) yang mewakili titik awal gradien linear. |
| point2 | [Point](../../com.aspose.drawing/point) | Sebuah struktur [Point](../../com.aspose.drawing/point) yang mewakili titik akhir gradien linear. |
| color1 | [Color](../../com.aspose.drawing/color) | Sebuah struktur [Color](../../com.aspose.drawing/color) yang mewakili warna awal gradien linear. |
| color2 | [Color](../../com.aspose.drawing/color) | Sebuah struktur [Color](../../com.aspose.drawing/color) yang mewakili warna akhir gradien linear. |

### LinearGradientBrush(RectangleF rect, Color color1, Color color2, int linearGradientMode) {#LinearGradientBrush-com.aspose.drawing.RectangleF-com.aspose.drawing.Color-com.aspose.drawing.Color-int-}
```
public LinearGradientBrush(RectangleF rect, Color color1, Color color2, int linearGradientMode)
```


Menginisialisasi instance baru dari kelas [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) berdasarkan persegi panjang, warna awal dan akhir, serta mode orientasi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | Sebuah struktur [RectangleF](../../com.aspose.drawing/rectanglef) yang menentukan batas gradien linear. |
| color1 | [Color](../../com.aspose.drawing/color) | Sebuah struktur [Color](../../com.aspose.drawing/color) yang mewakili warna awal untuk gradien. |
| color2 | [Color](../../com.aspose.drawing/color) | Sebuah struktur [Color](../../com.aspose.drawing/color) yang mewakili warna akhir untuk gradien. |
| linearGradientMode | int | Elemen enumerasi [LinearGradientMode](../../com.aspose.drawing.drawing2d/lineargradientmode) yang menentukan orientasi gradien. Orientasi menentukan titik awal dan titik akhir gradien. Misalnya, LinearGradientMode.ForwardDiagonal menentukan bahwa titik awal berada di sudut kiri atas persegi panjang dan titik akhir berada di sudut kanan bawah persegi panjang. |

### LinearGradientBrush(Rectangle rect, Color color1, Color color2, int linearGradientMode) {#LinearGradientBrush-com.aspose.drawing.Rectangle-com.aspose.drawing.Color-com.aspose.drawing.Color-int-}
```
public LinearGradientBrush(Rectangle rect, Color color1, Color color2, int linearGradientMode)
```


Menginisialisasi instance baru dari kelas [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) berdasarkan persegi panjang, warna awal dan akhir, serta orientasi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | Sebuah struktur `Rectangle`([.getRectangle](../../null/\#getRectangle)) yang menentukan batas gradien linier. |
| color1 | [Color](../../com.aspose.drawing/color) | Sebuah struktur [Color](../../com.aspose.drawing/color) yang mewakili warna awal untuk gradien. |
| color2 | [Color](../../com.aspose.drawing/color) | Sebuah struktur [Color](../../com.aspose.drawing/color) yang mewakili warna akhir untuk gradien. |
| linearGradientMode | int | Elemen enumerasi [LinearGradientMode](../../com.aspose.drawing.drawing2d/lineargradientmode) yang menentukan orientasi gradien. Orientasi menentukan titik awal dan titik akhir gradien. Misalnya, LinearGradientMode.ForwardDiagonal menentukan bahwa titik awal berada di sudut kiri atas persegi panjang dan titik akhir berada di sudut kanan bawah persegi panjang. |

### LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle) {#LinearGradientBrush-com.aspose.drawing.RectangleF-com.aspose.drawing.Color-com.aspose.drawing.Color-float-}
```
public LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle)
```


Menginisialisasi instance baru dari kelas [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) berdasarkan persegi panjang, warna awal dan akhir, serta sudut orientasi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | Sebuah struktur [RectangleF](../../com.aspose.drawing/rectanglef) yang menentukan batas gradien linear. |
| color1 | [Color](../../com.aspose.drawing/color) | Sebuah struktur [Color](../../com.aspose.drawing/color) yang mewakili warna awal untuk gradien. |
| color2 | [Color](../../com.aspose.drawing/color) | Sebuah struktur [Color](../../com.aspose.drawing/color) yang mewakili warna akhir untuk gradien. |
| sudut | float | Sudut, diukur dalam derajat searah jarum jam dari sumbu x, dari garis orientasi gradien. |

### LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle, boolean isAngleScaleable) {#LinearGradientBrush-com.aspose.drawing.RectangleF-com.aspose.drawing.Color-com.aspose.drawing.Color-float-boolean-}
```
public LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle, boolean isAngleScaleable)
```


Menginisialisasi instance baru dari kelas [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) berdasarkan persegi panjang, warna awal dan akhir, serta sudut orientasi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | Sebuah struktur [RectangleF](../../com.aspose.drawing/rectanglef) yang menentukan batas gradien linear. |
| color1 | [Color](../../com.aspose.drawing/color) | Sebuah struktur [Color](../../com.aspose.drawing/color) yang mewakili warna awal untuk gradien. |
| color2 | [Color](../../com.aspose.drawing/color) | Sebuah struktur [Color](../../com.aspose.drawing/color) yang mewakili warna akhir untuk gradien. |
| sudut | float | Sudut, diukur dalam derajat searah jarum jam dari sumbu x, dari garis orientasi gradien. |
| isAngleScaleable | boolean | Atur ke true untuk menentukan bahwa sudut dipengaruhi oleh transformasi yang terkait dengan [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) ini; jika tidak, false. |

### LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle) {#LinearGradientBrush-com.aspose.drawing.Rectangle-com.aspose.drawing.Color-com.aspose.drawing.Color-float-}
```
public LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle)
```


Menginisialisasi instance baru dari kelas [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) berdasarkan persegi panjang, warna awal dan akhir, serta sudut orientasi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | Sebuah struktur `Rectangle`([.getRectangle](../../null/\#getRectangle)) yang menentukan batas gradien linier. |
| color1 | [Color](../../com.aspose.drawing/color) | Sebuah struktur [Color](../../com.aspose.drawing/color) yang mewakili warna awal untuk gradien. |
| color2 | [Color](../../com.aspose.drawing/color) | Sebuah struktur [Color](../../com.aspose.drawing/color) yang mewakili warna akhir untuk gradien. |
| sudut | float | Sudut, diukur dalam derajat searah jarum jam dari sumbu x, dari garis orientasi gradien. |

### LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle, boolean isAngleScaleable) {#LinearGradientBrush-com.aspose.drawing.Rectangle-com.aspose.drawing.Color-com.aspose.drawing.Color-float-boolean-}
```
public LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle, boolean isAngleScaleable)
```


Menginisialisasi instance baru dari kelas [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) berdasarkan persegi panjang, warna awal dan akhir, serta sudut orientasi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | Sebuah struktur `Rectangle`([.getRectangle](../../null/\#getRectangle)) yang menentukan batas gradien linier. |
| color1 | [Color](../../com.aspose.drawing/color) | Sebuah struktur [Color](../../com.aspose.drawing/color) yang mewakili warna awal untuk gradien. |
| color2 | [Color](../../com.aspose.drawing/color) | Sebuah struktur [Color](../../com.aspose.drawing/color) yang mewakili warna akhir untuk gradien. |
| sudut | float | Sudut, diukur dalam derajat searah jarum jam dari sumbu x, dari garis orientasi gradien. |
| isAngleScaleable | boolean | Atur ke true untuk menentukan bahwa sudut dipengaruhi oleh transformasi yang terkait dengan [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) ini; jika tidak, false. |

### getLinearColors() {#getLinearColors--}
```
public Color[] getLinearColors()
```


Mendapatkan atau mengatur warna awal dan akhir gradien.

**Returns:**
com.aspose.drawing.Color[]
### setLinearColors(Color[] value) {#setLinearColors-com.aspose.drawing.Color---}
```
public void setLinearColors(Color[] value)
```


Mendapatkan atau mengatur warna awal dan akhir gradien.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Color\[\]](../../com.aspose.drawing/color) |  |

### getRectangle() {#getRectangle--}
```
public RectangleF getRectangle()
```


Mendapatkan wilayah persegi panjang yang menentukan titik awal dan akhir gradien.

**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef)
### getGammaCorrection() {#getGammaCorrection--}
```
public boolean getGammaCorrection()
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah koreksi gamma diaktifkan untuk [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush).

**Returns:**
boolean
### setGammaCorrection(boolean value) {#setGammaCorrection-boolean-}
```
public void setGammaCorrection(boolean value)
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah koreksi gamma diaktifkan untuk [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getBlend() {#getBlend--}
```
public Blend getBlend()
```


Mendapatkan atau mengatur `Blend`([.getBlend](../../null/#getBlend)/[.setBlend(Blend)](../../null/#setBlend-Blend-)) yang menentukan posisi dan faktor yang mendefinisikan penurunan khusus untuk gradien.

**Returns:**
[Blend](../../com.aspose.drawing.drawing2d/blend)
### setBlend(Blend value) {#setBlend-com.aspose.drawing.drawing2d.Blend-}
```
public void setBlend(Blend value)
```


Mendapatkan atau mengatur `Blend`([.getBlend](../../null/#getBlend)/[.setBlend(Blend)](../../null/#setBlend-Blend-)) yang menentukan posisi dan faktor yang mendefinisikan penurunan khusus untuk gradien.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Blend](../../com.aspose.drawing.drawing2d/blend) |  |

### getInterpolationColors() {#getInterpolationColors--}
```
public ColorBlend getInterpolationColors()
```


Mendapatkan atau mengatur [ColorBlend](../../com.aspose.drawing.drawing2d/colorblend) yang mendefinisikan gradien linear multiwarna.

**Returns:**
[ColorBlend](../../com.aspose.drawing.drawing2d/colorblend)
### setInterpolationColors(ColorBlend value) {#setInterpolationColors-com.aspose.drawing.drawing2d.ColorBlend-}
```
public void setInterpolationColors(ColorBlend value)
```


Mendapatkan atau mengatur [ColorBlend](../../com.aspose.drawing.drawing2d/colorblend) yang mendefinisikan gradien linear multiwarna.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [ColorBlend](../../com.aspose.drawing.drawing2d/colorblend) |  |

### getWrapMode() {#getWrapMode--}
```
public int getWrapMode()
```


Mendapatkan atau mengatur enumerasi `WrapMode` yang menunjukkan mode pembungkus untuk [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush).

**Returns:**
int
### setWrapMode(int value) {#setWrapMode-int-}
```
public void setWrapMode(int value)
```


Mendapatkan atau mengatur enumerasi `WrapMode` yang menunjukkan mode pembungkus untuk [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getTransform() {#getTransform--}
```
public Matrix getTransform()
```


Mendapatkan atau mengatur salinan [Matrix](../../com.aspose.drawing.drawing2d/matrix) yang mendefinisikan transformasi geometris lokal untuk [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush).

**Returns:**
[Matrix](../../com.aspose.drawing.drawing2d/matrix)
### setTransform(Matrix value) {#setTransform-com.aspose.drawing.drawing2d.Matrix-}
```
public void setTransform(Matrix value)
```


Mendapatkan atau mengatur salinan [Matrix](../../com.aspose.drawing.drawing2d/matrix) yang mendefinisikan transformasi geometris lokal untuk [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.drawing.drawing2d/matrix) |  |

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Membuat salinan tepat dari [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush).

**Returns:**
java.lang.Object - [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) yang dibuat oleh metode ini, di-cast sebagai objek.
### setSigmaBellShape(float focus) {#setSigmaBellShape-float-}
```
public void setSigmaBellShape(float focus)
```


Membuat penurunan gradien berdasarkan kurva berbentuk lonceng.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fokus | float | Nilai antara 0 hingga 1 yang menentukan pusat gradien (titik di mana warna awal dan warna akhir tercampur secara merata). |

### setSigmaBellShape(float focus, float scale) {#setSigmaBellShape-float-float-}
```
public void setSigmaBellShape(float focus, float scale)
```


Membuat penurunan gradien berdasarkan kurva berbentuk lonceng.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fokus | float | Nilai antara 0 hingga 1 yang menentukan pusat gradien (titik di mana gradien terdiri hanya dari warna akhir). |
| skala | float | Nilai antara 0 hingga 1 yang menentukan seberapa cepat warna berkurang dari `fokus`. |

### setBlendTriangularShape(float focus) {#setBlendTriangularShape-float-}
```
public void setBlendTriangularShape(float focus)
```


Membuat gradien linear dengan warna tengah dan penurunan linear ke satu warna di kedua ujung.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fokus | float | Nilai antara 0 hingga 1 yang menentukan pusat gradien (titik di mana gradien terdiri hanya dari warna akhir). |

### setBlendTriangularShape(float focus, float scale) {#setBlendTriangularShape-float-float-}
```
public void setBlendTriangularShape(float focus, float scale)
```


Membuat gradien linear dengan warna tengah dan penurunan linear ke satu warna di kedua ujung.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fokus | float | Nilai antara 0 hingga 1 yang menentukan pusat gradien (titik di mana gradien terdiri hanya dari warna akhir). |
| skala | float | Nilai antara 0 hingga 1 yang menentukan seberapa cepat warna berkurang dari warna awal ke `fokus` (warna akhir) |

### resetTransform() {#resetTransform--}
```
public void resetTransform()
```


Mengatur ulang properti `LinearGradientBrush.Transform` ke identitas.

### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-}
```
public void multiplyTransform(Matrix matrix)
```


Mengalikan [Matrix](../../com.aspose.drawing.drawing2d/matrix) yang mewakili transformasi geometris lokal dari [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) dengan [Matrix](../../com.aspose.drawing.drawing2d/matrix) yang ditentukan dengan menambahkan [Matrix](../../com.aspose.drawing.drawing2d/matrix) yang ditentukan di depan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | [Matrix](../../com.aspose.drawing.drawing2d/matrix) yang digunakan untuk mengalikan transformasi geometrik. |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-int-}
```
public void multiplyTransform(Matrix matrix, int order)
```


Mengalikan [Matrix](../../com.aspose.drawing.drawing2d/matrix) yang mewakili transformasi geometris lokal dari [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) dengan [Matrix](../../com.aspose.drawing.drawing2d/matrix) yang ditentukan dalam urutan yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | [Matrix](../../com.aspose.drawing.drawing2d/matrix) yang digunakan untuk mengalikan transformasi geometrik. |
| order | int | Sebuah [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder) yang menentukan urutan pengalian dua matriks. |

### translateTransform(float dx, float dy) {#translateTransform-float-float-}
```
public void translateTransform(float dx, float dy)
```


Menerjemahkan transformasi geometrik lokal dengan dimensi yang ditentukan. Metode ini menambahkan translasi ke depan transformasi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| dx | float | Nilai translasi pada sumbu x. |
| dy | float | Nilai translasi pada sumbu y. |

### translateTransform(float dx, float dy, int order) {#translateTransform-float-float-int-}
```
public void translateTransform(float dx, float dy, int order)
```


Menerjemahkan transformasi geometris lokal dengan dimensi yang ditentukan dalam urutan yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| dx | float | Nilai translasi pada sumbu x. |
| dy | float | Nilai translasi pada sumbu y. |
| urutan | int | Urutan (prepend atau append) dalam menerapkan translasi. |

### scaleTransform(float sx, float sy) {#scaleTransform-float-float-}
```
public void scaleTransform(float sx, float sy)
```


Menskala transformasi geometris lokal dengan jumlah yang ditentukan. Metode ini menambahkan matriks skala ke depan transformasi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sx | float | Jumlah yang digunakan untuk menskala transformasi pada arah sumbu x. |
| sy | float | Jumlah yang digunakan untuk menskala transformasi pada arah sumbu y. |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public void scaleTransform(float sx, float sy, int order)
```


Menskalakan transformasi geometris lokal dengan jumlah yang ditentukan dalam urutan yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sx | float | Jumlah yang digunakan untuk menskala transformasi pada arah sumbu x. |
| sy | float | Jumlah yang digunakan untuk menskala transformasi pada arah sumbu y. |
| order | int | Sebuah [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder) yang menentukan apakah akan menambahkan atau menempatkan di depan matriks skala. |

### rotateTransform(float angle) {#rotateTransform-float-}
```
public void rotateTransform(float angle)
```


Memutar transformasi geometris lokal dengan jumlah yang ditentukan. Metode ini menambahkan rotasi ke depan transformasi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sudut | float | Sudut rotasi. |

### rotateTransform(float angle, int order) {#rotateTransform-float-int-}
```
public void rotateTransform(float angle, int order)
```


Memutar transformasi geometris lokal dengan jumlah yang ditentukan dalam urutan yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sudut | float | Sudut rotasi. |
| order | int | Sebuah [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder) yang menentukan apakah akan menambahkan atau menempatkan di depan matriks rotasi. |

