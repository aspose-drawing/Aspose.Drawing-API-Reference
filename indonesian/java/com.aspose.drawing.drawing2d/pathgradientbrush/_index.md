---
title: PathGradientBrush
second_title: Referensi API Aspose.Drawing for Java
description: Mengkapsulkan objek yang mengisi interior objek dengan gradien.
type: docs
weight: 36
url: /id/java/com.aspose.drawing.drawing2d/pathgradientbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.drawing.Brush](../../com.aspose.drawing/brush)
```
public final class PathGradientBrush extends Brush
```

Mengkapsulkan objek [Brush](../../com.aspose.drawing/brush) yang mengisi interior objek [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) dengan gradien. Kelas ini tidak dapat diwarisi.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [PathGradientBrush(PointF[] points)](#PathGradientBrush-com.aspose.drawing.PointF---) | Menginisialisasi instance baru dari kelas [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) dengan titik‑titik yang ditentukan. |
| [PathGradientBrush(PointF[] points, int wrapMode)](#PathGradientBrush-com.aspose.drawing.PointF---int-) | Menginisialisasi instance baru dari kelas [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) dengan titik‑titik dan mode pembungkus yang ditentukan. |
| [PathGradientBrush(Point[] points)](#PathGradientBrush-com.aspose.drawing.Point---) | Menginisialisasi instance baru dari kelas [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) dengan titik‑titik yang ditentukan. |
| [PathGradientBrush(Point[] points, int wrapMode)](#PathGradientBrush-com.aspose.drawing.Point---int-) | Menginisialisasi instance baru dari kelas [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) dengan titik‑titik dan mode pembungkus yang ditentukan. |
| [PathGradientBrush(GraphicsPath path)](#PathGradientBrush-com.aspose.drawing.drawing2d.GraphicsPath-) | Menginisialisasi instance baru dari kelas [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) dengan jalur yang ditentukan. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getCenterColor()](#getCenterColor--) | Mendapatkan atau mengatur warna di tengah gradien jalur. |
| [setCenterColor(Color value)](#setCenterColor-com.aspose.drawing.Color-) | Mendapatkan atau mengatur warna di tengah gradien jalur. |
| [getSurroundColors()](#getSurroundColors--) | Mendapatkan atau mengatur array warna yang sesuai dengan titik‑titik dalam jalur yang diisi oleh [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) ini. |
| [setSurroundColors(Color[] value)](#setSurroundColors-com.aspose.drawing.Color---) | Mendapatkan atau mengatur array warna yang sesuai dengan titik‑titik dalam jalur yang diisi oleh [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) ini. |
| [getCenterPoint()](#getCenterPoint--) | Mendapatkan atau mengatur titik tengah gradien jalur. |
| [setCenterPoint(PointF value)](#setCenterPoint-com.aspose.drawing.PointF-) | Mendapatkan atau mengatur titik tengah gradien jalur. |
| [getRectangle()](#getRectangle--) | Mendapatkan persegi panjang pembatas untuk [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) ini. |
| [getBlend()](#getBlend--) | Mendapatkan atau mengatur `Blend`([.getBlend](../../null/#getBlend)/[.setBlend(Blend)](../../null/#setBlend-Blend-)) yang menentukan posisi dan faktor yang mendefinisikan penurunan khusus untuk gradien. |
| [setBlend(Blend value)](#setBlend-com.aspose.drawing.drawing2d.Blend-) | Mendapatkan atau mengatur `Blend`([.getBlend](../../null/#getBlend)/[.setBlend(Blend)](../../null/#setBlend-Blend-)) yang menentukan posisi dan faktor yang mendefinisikan penurunan khusus untuk gradien. |
| [getInterpolationColors()](#getInterpolationColors--) | Mendapatkan atau mengatur [ColorBlend](../../com.aspose.drawing.drawing2d/colorblend) yang mendefinisikan gradien linear multiwarna. |
| [setInterpolationColors(ColorBlend value)](#setInterpolationColors-com.aspose.drawing.drawing2d.ColorBlend-) | Mendapatkan atau mengatur [ColorBlend](../../com.aspose.drawing.drawing2d/colorblend) yang mendefinisikan gradien linear multiwarna. |
| [getTransform()](#getTransform--) | Mendapatkan atau mengatur salinan [Matrix](../../com.aspose.drawing.drawing2d/matrix) yang mendefinisikan transformasi geometrik lokal untuk [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) ini. |
| [setTransform(Matrix value)](#setTransform-com.aspose.drawing.drawing2d.Matrix-) | Mendapatkan atau mengatur salinan [Matrix](../../com.aspose.drawing.drawing2d/matrix) yang mendefinisikan transformasi geometrik lokal untuk [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) ini. |
| [getFocusScales()](#getFocusScales--) | Mendapatkan atau mengatur titik fokus untuk penurunan gradien. |
| [setFocusScales(PointF value)](#setFocusScales-com.aspose.drawing.PointF-) | Mendapatkan atau mengatur titik fokus untuk penurunan gradien. |
| [getWrapMode()](#getWrapMode--) | Mendapatkan atau mengatur `WrapMode`([.getWrapMode](../../null/\#getWrapMode)/[.setWrapMode(int)](../../null/\#setWrapMode-int-)) yang menunjukkan mode pembungkus untuk [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) ini. |
| [setWrapMode(int value)](#setWrapMode-int-) | Mendapatkan atau mengatur `WrapMode`([.getWrapMode](../../null/\#getWrapMode)/[.setWrapMode(int)](../../null/\#setWrapMode-int-)) yang menunjukkan mode pembungkus untuk [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) ini. |
| [deepClone()](#deepClone--) | Membuat salinan persis dari [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) ini. |
| [setSigmaBellShape(float focus)](#setSigmaBellShape-float-) | Membuat kuas gradien yang mengubah warna mulai dari tengah jalur ke arah batas jalur. |
| [setSigmaBellShape(float focus, float scale)](#setSigmaBellShape-float-float-) | Membuat kuas gradien yang mengubah warna mulai dari tengah jalur ke arah batas jalur. |
| [setBlendTriangularShape(float focus)](#setBlendTriangularShape-float-) | Membuat gradien dengan warna tengah dan penurunan linear ke satu warna di sekitarnya. |
| [setBlendTriangularShape(float focus, float scale)](#setBlendTriangularShape-float-float-) | Membuat gradien dengan warna pusat dan penurunan linear ke setiap warna di sekitarnya. |
| [resetTransform()](#resetTransform--) | Mengatur ulang properti `PathGradientBrush.Transform` ke identitas. |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-) | Memperbarui matriks transformasi kuas dengan hasil perkalian matriks transformasi kuas dengan matriks lain. |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-int-) | Memperbarui matriks transformasi kuas dengan hasil perkalian matriks transformasi kuas dengan matriks lain. |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | Menerapkan translasi yang ditentukan ke transformasi geometrik lokal. |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | Menerapkan translasi yang ditentukan ke transformasi geometrik lokal dalam urutan yang ditentukan. |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | Menskalakan transformasi geometris lokal dengan jumlah yang ditentukan. |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | Menskalakan transformasi geometris lokal dengan jumlah yang ditentukan dalam urutan yang ditentukan. |
| [rotateTransform(float angle)](#rotateTransform-float-) | Memutar transformasi geometris lokal dengan jumlah yang ditentukan. |
| [rotateTransform(float angle, int order)](#rotateTransform-float-int-) | Memutar transformasi geometris lokal dengan jumlah yang ditentukan dalam urutan yang ditentukan. |
### PathGradientBrush(PointF[] points) {#PathGradientBrush-com.aspose.drawing.PointF---}
```
public PathGradientBrush(PointF[] points)
```


Menginisialisasi instance baru dari kelas [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) dengan titik‑titik yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.drawing/pointf) | Array dari struktur [PointF](../../com.aspose.drawing/pointf) yang mewakili titik-titik yang membentuk simpul-simpul jalur. |

### PathGradientBrush(PointF[] points, int wrapMode) {#PathGradientBrush-com.aspose.drawing.PointF---int-}
```
public PathGradientBrush(PointF[] points, int wrapMode)
```


Menginisialisasi instance baru dari kelas [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) dengan titik‑titik dan mode pembungkus yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.drawing/pointf) | Array dari struktur [PointF](../../com.aspose.drawing/pointf) yang mewakili titik-titik yang membentuk simpul-simpul jalur. |
| wrapMode | int | Sebuah `WrapMode`([.getWrapMode](../../null/\#getWrapMode)/[.setWrapMode(int)](../../null/\#setWrapMode-int-)) yang menentukan bagaimana isian yang digambar dengan [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) ini ditata ubin. |

### PathGradientBrush(Point[] points) {#PathGradientBrush-com.aspose.drawing.Point---}
```
public PathGradientBrush(Point[] points)
```


Menginisialisasi instance baru dari kelas [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) dengan titik‑titik yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| points | [Point\[\]](../../com.aspose.drawing/point) | Array dari struktur [Point](../../com.aspose.drawing/point) yang mewakili titik-titik yang membentuk simpul-simpul jalur. |

### PathGradientBrush(Point[] points, int wrapMode) {#PathGradientBrush-com.aspose.drawing.Point---int-}
```
public PathGradientBrush(Point[] points, int wrapMode)
```


Menginisialisasi instance baru dari kelas [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) dengan titik‑titik dan mode pembungkus yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| points | [Point\[\]](../../com.aspose.drawing/point) | Array dari struktur [Point](../../com.aspose.drawing/point) yang mewakili titik-titik yang membentuk simpul-simpul jalur. |
| wrapMode | int | Sebuah `WrapMode`([.getWrapMode](../../null/\#getWrapMode)/[.setWrapMode(int)](../../null/\#setWrapMode-int-)) yang menentukan bagaimana isian yang digambar dengan [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) ini ditata ubin. |

### PathGradientBrush(GraphicsPath path) {#PathGradientBrush-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public PathGradientBrush(GraphicsPath path)
```


Menginisialisasi instance baru dari kelas [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) dengan jalur yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) yang mendefinisikan area yang diisi oleh [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) ini. |

### getCenterColor() {#getCenterColor--}
```
public Color getCenterColor()
```


Mendapatkan atau mengatur warna di tengah gradien jalur.

**Returns:**
[Color](../../com.aspose.drawing/color)
### setCenterColor(Color value) {#setCenterColor-com.aspose.drawing.Color-}
```
public void setCenterColor(Color value)
```


Mendapatkan atau mengatur warna di tengah gradien jalur.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Color](../../com.aspose.drawing/color) |  |

### getSurroundColors() {#getSurroundColors--}
```
public Color[] getSurroundColors()
```


Mendapatkan atau mengatur array warna yang sesuai dengan titik‑titik dalam jalur yang diisi oleh [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) ini.

**Returns:**
com.aspose.drawing.Color[]
### setSurroundColors(Color[] value) {#setSurroundColors-com.aspose.drawing.Color---}
```
public void setSurroundColors(Color[] value)
```


Mendapatkan atau mengatur array warna yang sesuai dengan titik‑titik dalam jalur yang diisi oleh [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Color\[\]](../../com.aspose.drawing/color) |  |

### getCenterPoint() {#getCenterPoint--}
```
public PointF getCenterPoint()
```


Mendapatkan atau mengatur titik tengah gradien jalur.

**Returns:**
[PointF](../../com.aspose.drawing/pointf)
### setCenterPoint(PointF value) {#setCenterPoint-com.aspose.drawing.PointF-}
```
public void setCenterPoint(PointF value)
```


Mendapatkan atau mengatur titik tengah gradien jalur.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [PointF](../../com.aspose.drawing/pointf) |  |

### getRectangle() {#getRectangle--}
```
public RectangleF getRectangle()
```


Mendapatkan persegi panjang pembatas untuk [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) ini.

**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef)
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

### getTransform() {#getTransform--}
```
public Matrix getTransform()
```


Mendapatkan atau mengatur salinan [Matrix](../../com.aspose.drawing.drawing2d/matrix) yang mendefinisikan transformasi geometrik lokal untuk [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) ini.

**Returns:**
[Matrix](../../com.aspose.drawing.drawing2d/matrix)
### setTransform(Matrix value) {#setTransform-com.aspose.drawing.drawing2d.Matrix-}
```
public void setTransform(Matrix value)
```


Mendapatkan atau mengatur salinan [Matrix](../../com.aspose.drawing.drawing2d/matrix) yang mendefinisikan transformasi geometrik lokal untuk [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.drawing.drawing2d/matrix) |  |

### getFocusScales() {#getFocusScales--}
```
public PointF getFocusScales()
```


Mendapatkan atau mengatur titik fokus untuk penurunan gradien.

**Returns:**
[PointF](../../com.aspose.drawing/pointf)
### setFocusScales(PointF value) {#setFocusScales-com.aspose.drawing.PointF-}
```
public void setFocusScales(PointF value)
```


Mendapatkan atau mengatur titik fokus untuk penurunan gradien.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [PointF](../../com.aspose.drawing/pointf) |  |

### getWrapMode() {#getWrapMode--}
```
public int getWrapMode()
```


Mendapatkan atau mengatur `WrapMode`([.getWrapMode](../../null/\#getWrapMode)/[.setWrapMode(int)](../../null/\#setWrapMode-int-)) yang menunjukkan mode pembungkus untuk [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) ini.

**Returns:**
int
### setWrapMode(int value) {#setWrapMode-int-}
```
public void setWrapMode(int value)
```


Mendapatkan atau mengatur `WrapMode`([.getWrapMode](../../null/\#getWrapMode)/[.setWrapMode(int)](../../null/\#setWrapMode-int-)) yang menunjukkan mode pembungkus untuk [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Membuat salinan persis dari [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) ini.

**Returns:**
java.lang.Object - [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) yang dibuat oleh metode ini, di-cast sebagai objek.
### setSigmaBellShape(float focus) {#setSigmaBellShape-float-}
```
public void setSigmaBellShape(float focus)
```


Membuat kuas gradien yang mengubah warna mulai dari pusat jalur ke luar hingga batas jalur. Transisi dari satu warna ke warna lain didasarkan pada kurva berbentuk lonceng.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fokus | float | Nilai antara 0 hingga 1 yang menentukan di mana, sepanjang radial apa pun dari pusat jalur ke batas jalur, warna pusat akan berada pada intensitas tertinggi. Nilai 1 (default) menempatkan intensitas tertinggi di pusat jalur. |

### setSigmaBellShape(float focus, float scale) {#setSigmaBellShape-float-float-}
```
public void setSigmaBellShape(float focus, float scale)
```


Membuat kuas gradien yang mengubah warna mulai dari pusat jalur ke luar hingga batas jalur. Transisi dari satu warna ke warna lain didasarkan pada kurva berbentuk lonceng.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fokus | float | Nilai antara 0 hingga 1 yang menentukan di mana, sepanjang radial apa pun dari pusat jalur ke batas jalur, warna pusat akan berada pada intensitas tertinggi. Nilai 1 (default) menempatkan intensitas tertinggi di pusat jalur. |
| skala | float | Nilai antara 0 hingga 1 yang menentukan intensitas maksimum warna pusat yang dicampur dengan warna batas. Nilai 1 menghasilkan intensitas tertinggi yang mungkin dari warna pusat, dan itu adalah nilai default. |

### setBlendTriangularShape(float focus) {#setBlendTriangularShape-float-}
```
public void setBlendTriangularShape(float focus)
```


Membuat gradien dengan warna tengah dan penurunan linear ke satu warna di sekitarnya.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fokus | float | Nilai antara 0 hingga 1 yang menentukan di mana, sepanjang radial apa pun dari pusat jalur ke batas jalur, warna pusat akan berada pada intensitas tertinggi. Nilai 1 (default) menempatkan intensitas tertinggi di pusat jalur. |

### setBlendTriangularShape(float focus, float scale) {#setBlendTriangularShape-float-float-}
```
public void setBlendTriangularShape(float focus, float scale)
```


Membuat gradien dengan warna pusat dan penurunan linear ke setiap warna di sekitarnya.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fokus | float | Nilai antara 0 hingga 1 yang menentukan di mana, sepanjang radial apa pun dari pusat jalur ke batas jalur, warna pusat akan berada pada intensitas tertinggi. Nilai 1 (default) menempatkan intensitas tertinggi di pusat jalur. |
| skala | float | Nilai antara 0 hingga 1 yang menentukan intensitas maksimum warna pusat yang dicampur dengan warna batas. Nilai 1 menghasilkan intensitas tertinggi yang mungkin dari warna pusat, dan itu adalah nilai default. |

### resetTransform() {#resetTransform--}
```
public void resetTransform()
```


Mengatur ulang properti `PathGradientBrush.Transform` ke identitas.

### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-}
```
public void multiplyTransform(Matrix matrix)
```


Memperbarui matriks transformasi kuas dengan hasil perkalian matriks transformasi kuas dengan matriks lain.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | [Matrix](../../com.aspose.drawing.drawing2d/matrix) yang akan dikalikan dengan matriks transformasi kuas saat ini. |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-int-}
```
public void multiplyTransform(Matrix matrix, int order)
```


Memperbarui matriks transformasi kuas dengan hasil perkalian matriks transformasi kuas dengan matriks lain.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | [Matrix](../../com.aspose.drawing.drawing2d/matrix) yang akan dikalikan dengan matriks transformasi kuas saat ini. |
| order | int | Sebuah [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder) yang menentukan urutan pengalian dua matriks. |

### translateTransform(float dx, float dy) {#translateTransform-float-float-}
```
public void translateTransform(float dx, float dy)
```


Menerapkan translasi yang ditentukan ke transformasi geometrik lokal. Metode ini menambahkan translasi di depan transformasi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| dx | float | Nilai translasi pada sumbu x. |
| dy | float | Nilai translasi pada sumbu y. |

### translateTransform(float dx, float dy, int order) {#translateTransform-float-float-int-}
```
public void translateTransform(float dx, float dy, int order)
```


Menerapkan translasi yang ditentukan ke transformasi geometrik lokal dalam urutan yang ditentukan.

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
| sx | float | Faktor skala transformasi pada arah sumbu x. |
| sy | float | Faktor skala transformasi pada arah sumbu y. |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public void scaleTransform(float sx, float sy, int order)
```


Menskalakan transformasi geometris lokal dengan jumlah yang ditentukan dalam urutan yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sx | float | Faktor skala transformasi pada arah sumbu x. |
| sy | float | Faktor skala transformasi pada arah sumbu y. |
| order | int | Sebuah [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder) yang menentukan apakah akan menambahkan atau menempatkan di depan matriks skala. |

### rotateTransform(float angle) {#rotateTransform-float-}
```
public void rotateTransform(float angle)
```


Memutar transformasi geometris lokal dengan jumlah yang ditentukan. Metode ini menambahkan rotasi ke depan transformasi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sudut | float | Sudut (rentang) rotasi. |

### rotateTransform(float angle, int order) {#rotateTransform-float-int-}
```
public void rotateTransform(float angle, int order)
```


Memutar transformasi geometris lokal dengan jumlah yang ditentukan dalam urutan yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sudut | float | Sudut (rentang) rotasi. |
| order | int | Sebuah [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder) yang menentukan apakah akan menambahkan atau menempatkan di depan matriks rotasi. |

