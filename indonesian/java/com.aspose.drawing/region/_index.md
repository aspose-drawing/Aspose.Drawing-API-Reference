---
title: Region
second_title: Referensi API Aspose.Drawing for Java
description: Mendeskripsikan interior bentuk grafis yang terdiri dari persegi panjang dan jalur.
type: docs
weight: 40
url: /id/java/com.aspose.drawing/region/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public final class Region implements System.IDisposable
```

Mendeskripsikan interior bentuk grafis yang terdiri dari persegi panjang dan jalur. Kelas ini tidak dapat diwariskan.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [Region()](#Region--) | Menginisialisasi instance baru dari kelas [Region](../../com.aspose.drawing/region). |
| [Region(RectangleF rect)](#Region-com.aspose.drawing.RectangleF-) | Menginisialisasi instance baru dari kelas [Region](../../com.aspose.drawing/region) menggunakan struktur [RectangleF](../../com.aspose.drawing/rectanglef) yang ditentukan. |
| [Region(Rectangle rect)](#Region-com.aspose.drawing.Rectangle-) | Menginisialisasi instance baru dari kelas [Region](../../com.aspose.drawing/region) menggunakan struktur [Rectangle](../../com.aspose.drawing/rectangle) yang ditentukan. |
| [Region(GraphicsPath path)](#Region-com.aspose.drawing.drawing2d.GraphicsPath-) | Menginisialisasi instance baru dari kelas [Region](../../com.aspose.drawing/region) dengan [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) yang ditentukan. |
| [Region(RegionData rgnData)](#Region-com.aspose.drawing.drawing2d.RegionData-) | Menginisialisasi instance baru dari kelas [Region](../../com.aspose.drawing/region) dari data yang ditentukan. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [dispose()](#dispose--) | Melepaskan semua sumber daya yang digunakan oleh [Region](../../com.aspose.drawing/region) ini. |
| [equals(Region region, Graphics g)](#equals-com.aspose.drawing.Region-com.aspose.drawing.Graphics-) | Menguji apakah [Region](../../com.aspose.drawing/region) yang ditentukan identik dengan [Region](../../com.aspose.drawing/region) ini pada permukaan gambar yang ditentukan. |
| [deepClone()](#deepClone--) | Membuat salinan tepat dari [Region](../../com.aspose.drawing/region) ini. |
| [makeInfinite()](#makeInfinite--) | Menginisialisasi objek [Region](../../com.aspose.drawing/region) ini menjadi interior tak terbatas. |
| [makeEmpty()](#makeEmpty--) | Menginisialisasi [Region](../../com.aspose.drawing/region) ini menjadi interior kosong. |
| [intersect(RectangleF rect)](#intersect-com.aspose.drawing.RectangleF-) | Memperbarui [Region](../../com.aspose.drawing/region) ini menjadi irisan dirinya dengan struktur [RectangleF](../../com.aspose.drawing/rectanglef) yang ditentukan. |
| [intersect(Rectangle rect)](#intersect-com.aspose.drawing.Rectangle-) | Memperbarui [Region](../../com.aspose.drawing/region) ini menjadi irisan dirinya dengan struktur [Rectangle](../../com.aspose.drawing/rectangle) yang ditentukan. |
| [intersect(GraphicsPath path)](#intersect-com.aspose.drawing.drawing2d.GraphicsPath-) | Memperbarui [Region](../../com.aspose.drawing/region) ini menjadi irisan dirinya dengan [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) yang ditentukan. |
| [intersect(Region region)](#intersect-com.aspose.drawing.Region-) | Memperbarui [Region](../../com.aspose.drawing/region) ini menjadi irisan dirinya dengan [Region](../../com.aspose.drawing/region) yang ditentukan. |
| [union(RectangleF rect)](#union-com.aspose.drawing.RectangleF-) | Memperbarui [Region](../../com.aspose.drawing/region) ini menjadi gabungan dirinya dengan struktur [RectangleF](../../com.aspose.drawing/rectanglef) yang ditentukan. |
| [union(Rectangle rect)](#union-com.aspose.drawing.Rectangle-) | Memperbarui [Region](../../com.aspose.drawing/region) ini menjadi gabungan dirinya dengan struktur [Rectangle](../../com.aspose.drawing/rectangle) yang ditentukan. |
| [union(GraphicsPath path)](#union-com.aspose.drawing.drawing2d.GraphicsPath-) | Memperbarui [Region](../../com.aspose.drawing/region) ini menjadi gabungan dirinya dengan [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) yang ditentukan. |
| [union(Region region)](#union-com.aspose.drawing.Region-) | Memperbarui [Region](../../com.aspose.drawing/region) ini menjadi gabungan dirinya dengan [Region](../../com.aspose.drawing/region) yang ditentukan. |
| [getRegionData()](#getRegionData--) | Mengembalikan [RegionData](../../com.aspose.drawing.drawing2d/regiondata) yang mewakili informasi yang menggambarkan [Region](../../com.aspose.drawing/region) ini. |
| [xor(RectangleF rect)](#xor-com.aspose.drawing.RectangleF-) | Memperbarui [Region](../../com.aspose.drawing/region) ini menjadi gabungan dikurangi irisan dirinya dengan struktur [RectangleF](../../com.aspose.drawing/rectanglef) yang ditentukan. |
| [xor(Rectangle rect)](#xor-com.aspose.drawing.Rectangle-) | Memperbarui [Region](../../com.aspose.drawing/region) ini menjadi gabungan dikurangi irisan dirinya dengan struktur [Rectangle](../../com.aspose.drawing/rectangle) yang ditentukan. |
| [xor(GraphicsPath path)](#xor-com.aspose.drawing.drawing2d.GraphicsPath-) | Memperbarui [Region](../../com.aspose.drawing/region) ini menjadi gabungan dikurangi irisan dirinya dengan [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) yang ditentukan. |
| [xor(Region region)](#xor-com.aspose.drawing.Region-) | Memperbarui [Region](../../com.aspose.drawing/region) ini menjadi gabungan dikurangi irisan dirinya dengan [Region](../../com.aspose.drawing/region) yang ditentukan. |
| [exclude(RectangleF rect)](#exclude-com.aspose.drawing.RectangleF-) | Memperbarui [Region](../../com.aspose.drawing/region) ini agar hanya berisi bagian interiornya yang tidak beririsan dengan struktur [RectangleF](../../com.aspose.drawing/rectanglef) yang ditentukan. |
| [exclude(Rectangle rect)](#exclude-com.aspose.drawing.Rectangle-) | Memperbarui [Region](../../com.aspose.drawing/region) ini agar hanya berisi bagian interiornya yang tidak beririsan dengan struktur [Rectangle](../../com.aspose.drawing/rectangle) yang ditentukan. |
| [exclude(GraphicsPath path)](#exclude-com.aspose.drawing.drawing2d.GraphicsPath-) | Memperbarui [Region](../../com.aspose.drawing/region) ini agar hanya berisi bagian interiornya yang tidak beririsan dengan [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) yang ditentukan. |
| [exclude(Region region)](#exclude-com.aspose.drawing.Region-) | Memperbarui [Region](../../com.aspose.drawing/region) ini agar hanya berisi bagian interiornya yang tidak beririsan dengan [Region](../../com.aspose.drawing/region) yang ditentukan. |
| [complement(RectangleF rect)](#complement-com.aspose.drawing.RectangleF-) | Memperbarui [Region](../../com.aspose.drawing/region) ini agar berisi bagian dari struktur [RectangleF](../../com.aspose.drawing/rectanglef) yang tidak beririsan dengan [Region](../../com.aspose.drawing/region) ini. |
| [complement(Rectangle rect)](#complement-com.aspose.drawing.Rectangle-) | Memperbarui [Region](../../com.aspose.drawing/region) ini agar berisi bagian dari struktur [Rectangle](../../com.aspose.drawing/rectangle) yang tidak beririsan dengan [Region](../../com.aspose.drawing/region) ini. |
| [complement(GraphicsPath path)](#complement-com.aspose.drawing.drawing2d.GraphicsPath-) | Memperbarui [Region](../../com.aspose.drawing/region) ini agar berisi bagian dari [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) yang tidak beririsan dengan [Region](../../com.aspose.drawing/region) ini. |
| [complement(Region region)](#complement-com.aspose.drawing.Region-) | Memperbarui [Region](../../com.aspose.drawing/region) ini untuk berisi bagian dari [Region](../../com.aspose.drawing/region) yang ditentukan yang tidak berpotongan dengan [Region](../../com.aspose.drawing/region) ini. |
| [translate(float dx, float dy)](#translate-float-float-) | Menggeser koordinat [Region](../../com.aspose.drawing/region) ini sebesar jumlah yang ditentukan. |
| [translate(int dx, int dy)](#translate-int-int-) | Menggeser koordinat [Region](../../com.aspose.drawing/region) ini sebesar jumlah yang ditentukan. |
| [transform(Matrix matrix)](#transform-com.aspose.drawing.drawing2d.Matrix-) | Mentransformasikan [Region](../../com.aspose.drawing/region) ini dengan [Matrix](../../com.aspose.drawing.drawing2d/matrix) yang ditentukan. |
| [getBounds(Graphics g)](#getBounds-com.aspose.drawing.Graphics-) | Mendapatkan struktur [RectangleF](../../com.aspose.drawing/rectanglef) yang mewakili persegi panjang yang membatasi [Region](../../com.aspose.drawing/region) ini pada permukaan gambar dari objek [Graphics](../../com.aspose.drawing/graphics). |
| [getRegionScans(Matrix matrix)](#getRegionScans-com.aspose.drawing.drawing2d.Matrix-) | Mengembalikan array struktur [RectangleF](../../com.aspose.drawing/rectanglef) yang mendekati [Region](../../com.aspose.drawing/region) ini setelah transformasi matriks yang ditentukan diterapkan. |
| [isEmpty(Graphics g)](#isEmpty-com.aspose.drawing.Graphics-) | Menguji apakah [Region](../../com.aspose.drawing/region) ini memiliki interior kosong pada permukaan gambar yang ditentukan. |
| [isInfinite(Graphics g)](#isInfinite-com.aspose.drawing.Graphics-) | Menguji apakah [Region](../../com.aspose.drawing/region) ini memiliki interior tak terbatas pada permukaan gambar yang ditentukan. |
| [isVisible(float x, float y)](#isVisible-float-float-) | Menguji apakah titik yang ditentukan berada di dalam [Region](../../com.aspose.drawing/region) ini. |
| [isVisible(PointF point)](#isVisible-com.aspose.drawing.PointF-) | Menguji apakah struktur [PointF](../../com.aspose.drawing/pointf) yang ditentukan berada di dalam [Region](../../com.aspose.drawing/region) ini. |
| [isVisible(float x, float y, Graphics g)](#isVisible-float-float-com.aspose.drawing.Graphics-) | Menguji apakah titik yang ditentukan berada di dalam [Region](../../com.aspose.drawing/region) ini ketika digambar menggunakan [Graphics](../../com.aspose.drawing/graphics) yang ditentukan. |
| [isVisible(PointF point, Graphics g)](#isVisible-com.aspose.drawing.PointF-com.aspose.drawing.Graphics-) | Menguji apakah struktur [PointF](../../com.aspose.drawing/pointf) yang ditentukan berada di dalam [Region](../../com.aspose.drawing/region) ini ketika digambar menggunakan [Graphics](../../com.aspose.drawing/graphics) yang ditentukan. |
| [isVisible(float x, float y, float width, float height)](#isVisible-float-float-float-float-) | Menguji apakah bagian mana pun dari persegi panjang yang ditentukan berada di dalam [Region](../../com.aspose.drawing/region) ini. |
| [isVisible(RectangleF rect)](#isVisible-com.aspose.drawing.RectangleF-) | Menguji apakah bagian mana pun dari struktur [RectangleF](../../com.aspose.drawing/rectanglef) yang ditentukan berada di dalam [Region](../../com.aspose.drawing/region) ini. |
| [isVisible(float x, float y, float width, float height, Graphics g)](#isVisible-float-float-float-float-com.aspose.drawing.Graphics-) | Menguji apakah bagian mana pun dari persegi panjang yang ditentukan berada di dalam [Region](../../com.aspose.drawing/region) ini ketika digambar menggunakan [Graphics](../../com.aspose.drawing/graphics) yang ditentukan. |
| [isVisible(RectangleF rect, Graphics g)](#isVisible-com.aspose.drawing.RectangleF-com.aspose.drawing.Graphics-) | Menguji apakah bagian mana pun dari struktur [RectangleF](../../com.aspose.drawing/rectanglef) yang ditentukan berada di dalam [Region](../../com.aspose.drawing/region) ini ketika digambar menggunakan [Graphics](../../com.aspose.drawing/graphics) yang ditentukan. |
| [isVisible(int x, int y, Graphics g)](#isVisible-int-int-com.aspose.drawing.Graphics-) | Menguji apakah titik yang ditentukan berada di dalam objek [Region](../../com.aspose.drawing/region) ini ketika digambar menggunakan objek [Graphics](../../com.aspose.drawing/graphics) yang ditentukan. |
| [isVisible(Point point)](#isVisible-com.aspose.drawing.Point-) | Menguji apakah struktur [Point](../../com.aspose.drawing/point) yang ditentukan berada di dalam [Region](../../com.aspose.drawing/region) ini. |
| [isVisible(Point point, Graphics g)](#isVisible-com.aspose.drawing.Point-com.aspose.drawing.Graphics-) | Menguji apakah struktur [Point](../../com.aspose.drawing/point) yang ditentukan berada di dalam [Region](../../com.aspose.drawing/region) ini ketika digambar menggunakan [Graphics](../../com.aspose.drawing/graphics) yang ditentukan. |
| [isVisible(int x, int y, int width, int height)](#isVisible-int-int-int-int-) | Menguji apakah bagian mana pun dari persegi panjang yang ditentukan berada di dalam [Region](../../com.aspose.drawing/region) ini. |
| [isVisible(Rectangle rect)](#isVisible-com.aspose.drawing.Rectangle-) | Menguji apakah bagian mana pun dari struktur [Rectangle](../../com.aspose.drawing/rectangle) yang ditentukan berada di dalam [Region](../../com.aspose.drawing/region) ini. |
| [isVisible(int x, int y, int width, int height, Graphics g)](#isVisible-int-int-int-int-com.aspose.drawing.Graphics-) | Menguji apakah bagian mana pun dari persegi panjang yang ditentukan berada di dalam [Region](../../com.aspose.drawing/region) ini ketika digambar menggunakan [Graphics](../../com.aspose.drawing/graphics) yang ditentukan. |
| [isVisible(Rectangle rect, Graphics g)](#isVisible-com.aspose.drawing.Rectangle-com.aspose.drawing.Graphics-) | Menguji apakah bagian mana pun dari struktur [Rectangle](../../com.aspose.drawing/rectangle) yang ditentukan berada di dalam [Region](../../com.aspose.drawing/region) ini ketika digambar menggunakan [Graphics](../../com.aspose.drawing/graphics) yang ditentukan. |
### Region() {#Region--}
```
public Region()
```


Menginisialisasi instance baru dari kelas [Region](../../com.aspose.drawing/region).

### Region(RectangleF rect) {#Region-com.aspose.drawing.RectangleF-}
```
public Region(RectangleF rect)
```


Menginisialisasi instance baru dari kelas [Region](../../com.aspose.drawing/region) menggunakan struktur [RectangleF](../../com.aspose.drawing/rectanglef) yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | Sebuah struktur [RectangleF](../../com.aspose.drawing/rectanglef) yang mendefinisikan interior [Region](../../com.aspose.drawing/region) baru. |

### Region(Rectangle rect) {#Region-com.aspose.drawing.Rectangle-}
```
public Region(Rectangle rect)
```


Menginisialisasi instance baru dari kelas [Region](../../com.aspose.drawing/region) menggunakan struktur [Rectangle](../../com.aspose.drawing/rectangle) yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | Sebuah struktur [Rectangle](../../com.aspose.drawing/rectangle) yang mendefinisikan interior [Region](../../com.aspose.drawing/region) baru. |

### Region(GraphicsPath path) {#Region-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public Region(GraphicsPath path)
```


Menginisialisasi instance baru dari kelas [Region](../../com.aspose.drawing/region) dengan [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | Sebuah [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) yang mendefinisikan [Region](../../com.aspose.drawing/region) baru. |

### Region(RegionData rgnData) {#Region-com.aspose.drawing.drawing2d.RegionData-}
```
public Region(RegionData rgnData)
```


Menginisialisasi instance baru dari kelas [Region](../../com.aspose.drawing/region) dari data yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rgnData | [RegionData](../../com.aspose.drawing.drawing2d/regiondata) | Sebuah [RegionData](../../com.aspose.drawing.drawing2d/regiondata) yang mendefinisikan interior [Region](../../com.aspose.drawing/region) baru. |

### dispose() {#dispose--}
```
public void dispose()
```


Melepaskan semua sumber daya yang digunakan oleh [Region](../../com.aspose.drawing/region) ini.

### equals(Region region, Graphics g) {#equals-com.aspose.drawing.Region-com.aspose.drawing.Graphics-}
```
public boolean equals(Region region, Graphics g)
```


Menguji apakah [Region](../../com.aspose.drawing/region) yang ditentukan identik dengan [Region](../../com.aspose.drawing/region) ini pada permukaan gambar yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| region | [Region](../../com.aspose.drawing/region) | [Region](../../com.aspose.drawing/region) yang akan diuji. |
| g | [Graphics](../../com.aspose.drawing/graphics) | Sebuah [Graphics](../../com.aspose.drawing/graphics) yang mewakili permukaan gambar. |

**Returns:**
boolean - true jika interior wilayah identik dengan interior wilayah ini ketika transformasi yang terkait dengan parameter `g` diterapkan; jika tidak, false.
### deepClone() {#deepClone--}
```
public Region deepClone()
```


Membuat salinan tepat dari [Region](../../com.aspose.drawing/region) ini.

**Returns:**
[Region](../../com.aspose.drawing/region) - The [Region](../../com.aspose.drawing/region) that this method creates.
### makeInfinite() {#makeInfinite--}
```
public void makeInfinite()
```


Menginisialisasi objek [Region](../../com.aspose.drawing/region) ini menjadi interior tak terbatas.

### makeEmpty() {#makeEmpty--}
```
public void makeEmpty()
```


Menginisialisasi [Region](../../com.aspose.drawing/region) ini menjadi interior kosong.

### intersect(RectangleF rect) {#intersect-com.aspose.drawing.RectangleF-}
```
public void intersect(RectangleF rect)
```


Memperbarui [Region](../../com.aspose.drawing/region) ini menjadi irisan dirinya dengan struktur [RectangleF](../../com.aspose.drawing/rectanglef) yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | Struktur [RectangleF](../../com.aspose.drawing/rectanglef) untuk berpotongan dengan [Region](../../com.aspose.drawing/region) ini. |

### intersect(Rectangle rect) {#intersect-com.aspose.drawing.Rectangle-}
```
public void intersect(Rectangle rect)
```


Memperbarui [Region](../../com.aspose.drawing/region) ini menjadi irisan dirinya dengan struktur [Rectangle](../../com.aspose.drawing/rectangle) yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | Struktur [Rectangle](../../com.aspose.drawing/rectangle) untuk berpotongan dengan [Region](../../com.aspose.drawing/region) ini. |

### intersect(GraphicsPath path) {#intersect-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public void intersect(GraphicsPath path)
```


Memperbarui [Region](../../com.aspose.drawing/region) ini menjadi irisan dirinya dengan [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | Path [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) untuk berpotongan dengan [Region](../../com.aspose.drawing/region) ini. |

### intersect(Region region) {#intersect-com.aspose.drawing.Region-}
```
public void intersect(Region region)
```


Memperbarui [Region](../../com.aspose.drawing/region) ini menjadi irisan dirinya dengan [Region](../../com.aspose.drawing/region) yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| region | [Region](../../com.aspose.drawing/region) | Wilayah [Region](../../com.aspose.drawing/region) untuk berpotongan dengan [Region](../../com.aspose.drawing/region) ini. |

### union(RectangleF rect) {#union-com.aspose.drawing.RectangleF-}
```
public void union(RectangleF rect)
```


Memperbarui [Region](../../com.aspose.drawing/region) ini menjadi gabungan dirinya dengan struktur [RectangleF](../../com.aspose.drawing/rectanglef) yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | rect | [RectangleF](../../com.aspose.drawing/rectanglef) | Struktur [RectangleF](../../com.aspose.drawing/rectanglef) untuk digabungkan dengan [Region](../../com.aspose.drawing/region) ini. |

--------------------

Penggabungan meninggalkan wilayah tak hingga tetap tak hingga. |

### union(Rectangle rect) {#union-com.aspose.drawing.Rectangle-}
```
public void union(Rectangle rect)
```


Memperbarui [Region](../../com.aspose.drawing/region) ini menjadi gabungan dirinya dengan struktur [Rectangle](../../com.aspose.drawing/rectangle) yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | rect | [Rectangle](../../com.aspose.drawing/rectangle) | Struktur [Rectangle](../../com.aspose.drawing/rectangle) untuk digabungkan dengan [Region](../../com.aspose.drawing/region) ini. |

--------------------

Penggabungan meninggalkan wilayah tak hingga tetap tak hingga. |

### union(GraphicsPath path) {#union-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public void union(GraphicsPath path)
```


Memperbarui [Region](../../com.aspose.drawing/region) ini menjadi gabungan dirinya dengan [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | Path [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) untuk digabungkan dengan [Region](../../com.aspose.drawing/region) ini. |

--------------------

Penggabungan meninggalkan wilayah tak hingga tetap tak hingga. |

### union(Region region) {#union-com.aspose.drawing.Region-}
```
public void union(Region region)
```


Memperbarui [Region](../../com.aspose.drawing/region) ini menjadi gabungan dirinya dengan [Region](../../com.aspose.drawing/region) yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | region | [Region](../../com.aspose.drawing/region) | Wilayah [Region](../../com.aspose.drawing/region) untuk digabungkan dengan [Region](../../com.aspose.drawing/region) ini. |

--------------------

Penggabungan meninggalkan wilayah tak hingga tetap tak hingga. |

### getRegionData() {#getRegionData--}
```
public RegionData getRegionData()
```


Mengembalikan [RegionData](../../com.aspose.drawing.drawing2d/regiondata) yang mewakili informasi yang menggambarkan [Region](../../com.aspose.drawing/region) ini.

**Returns:**
[RegionData](../../com.aspose.drawing.drawing2d/regiondata) - A [RegionData](../../com.aspose.drawing.drawing2d/regiondata) that represents the information that describes this [Region](../../com.aspose.drawing/region).
### xor(RectangleF rect) {#xor-com.aspose.drawing.RectangleF-}
```
public void xor(RectangleF rect)
```


Memperbarui [Region](../../com.aspose.drawing/region) ini menjadi gabungan dikurangi irisan dirinya dengan struktur [RectangleF](../../com.aspose.drawing/rectanglef) yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | Struktur [RectangleF](../../com.aspose.drawing/rectanglef) untuk `M:Region.Xor(Drawing2D.GraphicsPath)` dengan [Region](../../com.aspose.drawing/region) ini. |

### xor(Rectangle rect) {#xor-com.aspose.drawing.Rectangle-}
```
public void xor(Rectangle rect)
```


Memperbarui [Region](../../com.aspose.drawing/region) ini menjadi gabungan dikurangi irisan dirinya dengan struktur [Rectangle](../../com.aspose.drawing/rectangle) yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | Struktur [Rectangle](../../com.aspose.drawing/rectangle) untuk `M:Region.Xor(Rectangle)` dengan [Region](../../com.aspose.drawing/region) ini. |

### xor(GraphicsPath path) {#xor-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public void xor(GraphicsPath path)
```


Memperbarui [Region](../../com.aspose.drawing/region) ini menjadi gabungan dikurangi irisan dirinya dengan [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | Path [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) untuk `M:Region.Xor(GraphicsPath)` dengan [Region](../../com.aspose.drawing/region) ini. |

### xor(Region region) {#xor-com.aspose.drawing.Region-}
```
public void xor(Region region)
```


Memperbarui [Region](../../com.aspose.drawing/region) ini menjadi gabungan dikurangi irisan dirinya dengan [Region](../../com.aspose.drawing/region) yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| region | [Region](../../com.aspose.drawing/region) | Wilayah [Region](../../com.aspose.drawing/region) untuk `M:Region.Xor(Region)` dengan [Region](../../com.aspose.drawing/region) ini. |

### exclude(RectangleF rect) {#exclude-com.aspose.drawing.RectangleF-}
```
public void exclude(RectangleF rect)
```


Memperbarui [Region](../../com.aspose.drawing/region) ini agar hanya berisi bagian interiornya yang tidak beririsan dengan struktur [RectangleF](../../com.aspose.drawing/rectanglef) yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | Struktur [RectangleF](../../com.aspose.drawing/rectanglef) untuk dikecualikan dari [Region](../../com.aspose.drawing/region) ini. |

### exclude(Rectangle rect) {#exclude-com.aspose.drawing.Rectangle-}
```
public void exclude(Rectangle rect)
```


Memperbarui [Region](../../com.aspose.drawing/region) ini agar hanya berisi bagian interiornya yang tidak beririsan dengan struktur [Rectangle](../../com.aspose.drawing/rectangle) yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | Struktur [Rectangle](../../com.aspose.drawing/rectangle) untuk dikecualikan dari [Region](../../com.aspose.drawing/region) ini. |

### exclude(GraphicsPath path) {#exclude-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public void exclude(GraphicsPath path)
```


Memperbarui [Region](../../com.aspose.drawing/region) ini agar hanya berisi bagian interiornya yang tidak beririsan dengan [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | Path [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) untuk dikecualikan dari [Region](../../com.aspose.drawing/region) ini. |

### exclude(Region region) {#exclude-com.aspose.drawing.Region-}
```
public void exclude(Region region)
```


Memperbarui [Region](../../com.aspose.drawing/region) ini agar hanya berisi bagian interiornya yang tidak beririsan dengan [Region](../../com.aspose.drawing/region) yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| region | [Region](../../com.aspose.drawing/region) | Wilayah [Region](../../com.aspose.drawing/region) untuk dikecualikan dari [Region](../../com.aspose.drawing/region) ini. |

### complement(RectangleF rect) {#complement-com.aspose.drawing.RectangleF-}
```
public void complement(RectangleF rect)
```


Memperbarui [Region](../../com.aspose.drawing/region) ini agar berisi bagian dari struktur [RectangleF](../../com.aspose.drawing/rectanglef) yang tidak beririsan dengan [Region](../../com.aspose.drawing/region) ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | Struktur [RectangleF](../../com.aspose.drawing/rectanglef) untuk melengkapi [Region](../../com.aspose.drawing/region) ini. |

### complement(Rectangle rect) {#complement-com.aspose.drawing.Rectangle-}
```
public void complement(Rectangle rect)
```


Memperbarui [Region](../../com.aspose.drawing/region) ini agar berisi bagian dari struktur [Rectangle](../../com.aspose.drawing/rectangle) yang tidak beririsan dengan [Region](../../com.aspose.drawing/region) ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | Struktur [Rectangle](../../com.aspose.drawing/rectangle) untuk melengkapi [Region](../../com.aspose.drawing/region) ini. |

### complement(GraphicsPath path) {#complement-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public void complement(GraphicsPath path)
```


Memperbarui [Region](../../com.aspose.drawing/region) ini agar berisi bagian dari [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) yang tidak beririsan dengan [Region](../../com.aspose.drawing/region) ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | Path [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) untuk melengkapi [Region](../../com.aspose.drawing/region) ini. |

### complement(Region region) {#complement-com.aspose.drawing.Region-}
```
public void complement(Region region)
```


Memperbarui [Region](../../com.aspose.drawing/region) ini untuk berisi bagian dari [Region](../../com.aspose.drawing/region) yang ditentukan yang tidak berpotongan dengan [Region](../../com.aspose.drawing/region) ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| region | [Region](../../com.aspose.drawing/region) | Objek [Region](../../com.aspose.drawing/region) untuk melengkapi objek [Region](../../com.aspose.drawing/region) ini. |

### translate(float dx, float dy) {#translate-float-float-}
```
public void translate(float dx, float dy)
```


Menggeser koordinat [Region](../../com.aspose.drawing/region) ini sebesar jumlah yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| dx | float | Jumlah offset secara horizontal untuk [Region](../../com.aspose.drawing/region) ini. |
| dy | float | Jumlah offset secara vertikal untuk [Region](../../com.aspose.drawing/region) ini. |

### translate(int dx, int dy) {#translate-int-int-}
```
public void translate(int dx, int dy)
```


Menggeser koordinat [Region](../../com.aspose.drawing/region) ini sebesar jumlah yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| dx | int | Jumlah untuk menggeser [Region](../../com.aspose.drawing/region) ini secara horizontal |
| dy | int | Jumlah offset secara vertikal untuk [Region](../../com.aspose.drawing/region) ini. |

### transform(Matrix matrix) {#transform-com.aspose.drawing.drawing2d.Matrix-}
```
public void transform(Matrix matrix)
```


Mentransformasikan [Region](../../com.aspose.drawing/region) ini dengan [Matrix](../../com.aspose.drawing.drawing2d/matrix) yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | [Matrix](../../com.aspose.drawing.drawing2d/matrix) yang digunakan untuk mentransformasi [Region](../../com.aspose.drawing/region) ini. |

### getBounds(Graphics g) {#getBounds-com.aspose.drawing.Graphics-}
```
public RectangleF getBounds(Graphics g)
```


Mendapatkan struktur [RectangleF](../../com.aspose.drawing/rectanglef) yang mewakili persegi panjang yang membatasi [Region](../../com.aspose.drawing/region) ini pada permukaan gambar dari objek [Graphics](../../com.aspose.drawing/graphics).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| g | [Graphics](../../com.aspose.drawing/graphics) | [Graphics](../../com.aspose.drawing/graphics) tempat [Region](../../com.aspose.drawing/region) ini digambar. |

**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef) - A [RectangleF](../../com.aspose.drawing/rectanglef) structure that represents the bounding rectangle for this [Region](../../com.aspose.drawing/region) on the specified drawing surface.
### getRegionScans(Matrix matrix) {#getRegionScans-com.aspose.drawing.drawing2d.Matrix-}
```
public RectangleF[] getRegionScans(Matrix matrix)
```


Mengembalikan array struktur [RectangleF](../../com.aspose.drawing/rectanglef) yang mendekati [Region](../../com.aspose.drawing/region) ini setelah transformasi matriks yang ditentukan diterapkan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | [Matrix](../../com.aspose.drawing.drawing2d/matrix) yang mewakili transformasi geometris untuk diterapkan pada region. |

**Returns:**
com.aspose.drawing.RectangleF[] - Sebuah array struktur [RectangleF](../../com.aspose.drawing/rectanglef) yang memperkirakan [Region](../../com.aspose.drawing/region) ini setelah transformasi matriks yang ditentukan diterapkan.
### isEmpty(Graphics g) {#isEmpty-com.aspose.drawing.Graphics-}
```
public boolean isEmpty(Graphics g)
```


Menguji apakah [Region](../../com.aspose.drawing/region) ini memiliki interior kosong pada permukaan gambar yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| g | [Graphics](../../com.aspose.drawing/graphics) | Sebuah [Graphics](../../com.aspose.drawing/graphics) yang mewakili permukaan gambar. |

**Returns:**
boolean - true jika interior [Region](../../com.aspose.drawing/region) ini kosong ketika transformasi yang terkait dengan `g` diterapkan; jika tidak, false.
### isInfinite(Graphics g) {#isInfinite-com.aspose.drawing.Graphics-}
```
public boolean isInfinite(Graphics g)
```


Menguji apakah [Region](../../com.aspose.drawing/region) ini memiliki interior tak terbatas pada permukaan gambar yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| g | [Graphics](../../com.aspose.drawing/graphics) | Sebuah [Graphics](../../com.aspose.drawing/graphics) yang mewakili permukaan gambar. |

**Returns:**
boolean - true jika interior [Region](../../com.aspose.drawing/region) ini tak berhingga ketika transformasi yang terkait dengan `g` diterapkan; jika tidak, false.
### isVisible(float x, float y) {#isVisible-float-float-}
```
public boolean isVisible(float x, float y)
```


Menguji apakah titik yang ditentukan berada di dalam [Region](../../com.aspose.drawing/region) ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | float | Koordinat x dari titik yang akan diuji. |
| y | float | Koordinat y dari titik yang akan diuji. |

**Returns:**
boolean - true ketika titik yang ditentukan berada di dalam [Region](../../com.aspose.drawing/region) ini; jika tidak, false.
### isVisible(PointF point) {#isVisible-com.aspose.drawing.PointF-}
```
public boolean isVisible(PointF point)
```


Menguji apakah struktur [PointF](../../com.aspose.drawing/pointf) yang ditentukan berada di dalam [Region](../../com.aspose.drawing/region) ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| point | [PointF](../../com.aspose.drawing/pointf) | Struktur [PointF](../../com.aspose.drawing/pointf) untuk diuji. |

**Returns:**
boolean - true ketika `point` berada di dalam [Region](../../com.aspose.drawing/region) ini; jika tidak, false.
### isVisible(float x, float y, Graphics g) {#isVisible-float-float-com.aspose.drawing.Graphics-}
```
public boolean isVisible(float x, float y, Graphics g)
```


Menguji apakah titik yang ditentukan berada di dalam [Region](../../com.aspose.drawing/region) ini ketika digambar menggunakan [Graphics](../../com.aspose.drawing/graphics) yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | float | Koordinat x dari titik yang akan diuji. |
| y | float | Koordinat y dari titik yang akan diuji. |
| g | [Graphics](../../com.aspose.drawing/graphics) | [Graphics](../../com.aspose.drawing/graphics) yang mewakili konteks grafis. |

**Returns:**
boolean - true ketika titik yang ditentukan berada di dalam [Region](../../com.aspose.drawing/region) ini; jika tidak, false.
### isVisible(PointF point, Graphics g) {#isVisible-com.aspose.drawing.PointF-com.aspose.drawing.Graphics-}
```
public boolean isVisible(PointF point, Graphics g)
```


Menguji apakah struktur [PointF](../../com.aspose.drawing/pointf) yang ditentukan berada di dalam [Region](../../com.aspose.drawing/region) ini ketika digambar menggunakan [Graphics](../../com.aspose.drawing/graphics) yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| point | [PointF](../../com.aspose.drawing/pointf) | Struktur [PointF](../../com.aspose.drawing/pointf) untuk diuji. |
| g | [Graphics](../../com.aspose.drawing/graphics) | [Graphics](../../com.aspose.drawing/graphics) yang mewakili konteks grafis. |

**Returns:**
boolean - true ketika `point` berada di dalam [Region](../../com.aspose.drawing/region) ini; jika tidak, false.
### isVisible(float x, float y, float width, float height) {#isVisible-float-float-float-float-}
```
public boolean isVisible(float x, float y, float width, float height)
```


Menguji apakah bagian mana pun dari persegi panjang yang ditentukan berada di dalam [Region](../../com.aspose.drawing/region) ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | float | Koordinat x dari sudut kiri atas persegi panjang yang akan diuji. |
| y | float | Koordinat y dari sudut kiri atas persegi panjang yang akan diuji. |
| lebar | float | Lebar persegi panjang yang akan diuji. |
| tinggi | float | Tinggi persegi panjang yang akan diuji. |

**Returns:**
boolean - true ketika bagian mana pun dari persegi panjang yang ditentukan berada di dalam objek [Region](../../com.aspose.drawing/region) ini; jika tidak, false.
### isVisible(RectangleF rect) {#isVisible-com.aspose.drawing.RectangleF-}
```
public boolean isVisible(RectangleF rect)
```


Menguji apakah bagian mana pun dari struktur [RectangleF](../../com.aspose.drawing/rectanglef) yang ditentukan berada di dalam [Region](../../com.aspose.drawing/region) ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | Struktur [RectangleF](../../com.aspose.drawing/rectanglef) untuk diuji. |

**Returns:**
boolean - true ketika bagian mana pun dari `rect` berada di dalam [Region](../../com.aspose.drawing/region) ini; jika tidak, false.
### isVisible(float x, float y, float width, float height, Graphics g) {#isVisible-float-float-float-float-com.aspose.drawing.Graphics-}
```
public boolean isVisible(float x, float y, float width, float height, Graphics g)
```


Menguji apakah bagian mana pun dari persegi panjang yang ditentukan berada di dalam [Region](../../com.aspose.drawing/region) ini ketika digambar menggunakan [Graphics](../../com.aspose.drawing/graphics) yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | float | Koordinat x dari sudut kiri atas persegi panjang yang akan diuji. |
| y | float | Koordinat y dari sudut kiri atas persegi panjang yang akan diuji. |
| lebar | float | Lebar persegi panjang yang akan diuji. |
| tinggi | float | Tinggi persegi panjang yang akan diuji. |
| g | [Graphics](../../com.aspose.drawing/graphics) | [Graphics](../../com.aspose.drawing/graphics) yang mewakili konteks grafis. |

**Returns:**
boolean - true ketika bagian mana pun dari persegi panjang yang ditentukan berada di dalam [Region](../../com.aspose.drawing/region) ini; jika tidak, false.
### isVisible(RectangleF rect, Graphics g) {#isVisible-com.aspose.drawing.RectangleF-com.aspose.drawing.Graphics-}
```
public boolean isVisible(RectangleF rect, Graphics g)
```


Menguji apakah bagian mana pun dari struktur [RectangleF](../../com.aspose.drawing/rectanglef) yang ditentukan berada di dalam [Region](../../com.aspose.drawing/region) ini ketika digambar menggunakan [Graphics](../../com.aspose.drawing/graphics) yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | Struktur [RectangleF](../../com.aspose.drawing/rectanglef) untuk diuji. |
| g | [Graphics](../../com.aspose.drawing/graphics) | [Graphics](../../com.aspose.drawing/graphics) yang mewakili konteks grafis. |

**Returns:**
boolean - true ketika `rect` berada di dalam [Region](../../com.aspose.drawing/region) ini; jika tidak, false.
### isVisible(int x, int y, Graphics g) {#isVisible-int-int-com.aspose.drawing.Graphics-}
```
public boolean isVisible(int x, int y, Graphics g)
```


Menguji apakah titik yang ditentukan berada di dalam objek [Region](../../com.aspose.drawing/region) ini ketika digambar menggunakan objek [Graphics](../../com.aspose.drawing/graphics) yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | int | Koordinat x dari titik yang akan diuji. |
| y | int | Koordinat y dari titik yang akan diuji. |
| g | [Graphics](../../com.aspose.drawing/graphics) | [Graphics](../../com.aspose.drawing/graphics) yang mewakili konteks grafis. |

**Returns:**
boolean - true ketika titik yang ditentukan berada di dalam [Region](../../com.aspose.drawing/region) ini; jika tidak, false.
### isVisible(Point point) {#isVisible-com.aspose.drawing.Point-}
```
public boolean isVisible(Point point)
```


Menguji apakah struktur [Point](../../com.aspose.drawing/point) yang ditentukan berada di dalam [Region](../../com.aspose.drawing/region) ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| point | [Point](../../com.aspose.drawing/point) | Struktur [Point](../../com.aspose.drawing/point) untuk diuji. |

**Returns:**
boolean - true ketika `point` berada di dalam [Region](../../com.aspose.drawing/region) ini; jika tidak, false.
### isVisible(Point point, Graphics g) {#isVisible-com.aspose.drawing.Point-com.aspose.drawing.Graphics-}
```
public boolean isVisible(Point point, Graphics g)
```


Menguji apakah struktur [Point](../../com.aspose.drawing/point) yang ditentukan berada di dalam [Region](../../com.aspose.drawing/region) ini ketika digambar menggunakan [Graphics](../../com.aspose.drawing/graphics) yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| point | [Point](../../com.aspose.drawing/point) | Struktur [Point](../../com.aspose.drawing/point) untuk diuji. |
| g | [Graphics](../../com.aspose.drawing/graphics) | [Graphics](../../com.aspose.drawing/graphics) yang mewakili konteks grafis. |

**Returns:**
boolean - true ketika `point` berada di dalam [Region](../../com.aspose.drawing/region) ini; jika tidak, false.
### isVisible(int x, int y, int width, int height) {#isVisible-int-int-int-int-}
```
public boolean isVisible(int x, int y, int width, int height)
```


Menguji apakah bagian mana pun dari persegi panjang yang ditentukan berada di dalam [Region](../../com.aspose.drawing/region) ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | int | Koordinat x dari sudut kiri atas persegi panjang yang akan diuji. |
| y | int | Koordinat y dari sudut kiri atas persegi panjang yang akan diuji. |
| lebar | int | Lebar persegi panjang yang akan diuji. |
| tinggi | int | Tinggi persegi panjang yang akan diuji. |

**Returns:**
boolean - true ketika bagian mana pun dari persegi panjang yang ditentukan berada di dalam [Region](../../com.aspose.drawing/region) ini; jika tidak, false.
### isVisible(Rectangle rect) {#isVisible-com.aspose.drawing.Rectangle-}
```
public boolean isVisible(Rectangle rect)
```


Menguji apakah bagian mana pun dari struktur [Rectangle](../../com.aspose.drawing/rectangle) yang ditentukan berada di dalam [Region](../../com.aspose.drawing/region) ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | Struktur [Rectangle](../../com.aspose.drawing/rectangle) untuk diuji. |

**Returns:**
boolean - Metode ini mengembalikan true ketika bagian mana pun dari `rect` berada di dalam [Region](../../com.aspose.drawing/region) ini; jika tidak, false.
### isVisible(int x, int y, int width, int height, Graphics g) {#isVisible-int-int-int-int-com.aspose.drawing.Graphics-}
```
public boolean isVisible(int x, int y, int width, int height, Graphics g)
```


Menguji apakah bagian mana pun dari persegi panjang yang ditentukan berada di dalam [Region](../../com.aspose.drawing/region) ini ketika digambar menggunakan [Graphics](../../com.aspose.drawing/graphics) yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | int | Koordinat x dari sudut kiri atas persegi panjang yang akan diuji. |
| y | int | Koordinat y dari sudut kiri atas persegi panjang yang akan diuji. |
| lebar | int | Lebar persegi panjang yang akan diuji. |
| tinggi | int | Tinggi persegi panjang yang akan diuji. |
| g | [Graphics](../../com.aspose.drawing/graphics) | [Graphics](../../com.aspose.drawing/graphics) yang mewakili konteks grafis. |

**Returns:**
boolean - true ketika bagian mana pun dari persegi panjang yang ditentukan berada di dalam [Region](../../com.aspose.drawing/region) ini; jika tidak, false.
### isVisible(Rectangle rect, Graphics g) {#isVisible-com.aspose.drawing.Rectangle-com.aspose.drawing.Graphics-}
```
public boolean isVisible(Rectangle rect, Graphics g)
```


Menguji apakah bagian mana pun dari struktur [Rectangle](../../com.aspose.drawing/rectangle) yang ditentukan berada di dalam [Region](../../com.aspose.drawing/region) ini ketika digambar menggunakan [Graphics](../../com.aspose.drawing/graphics) yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | Struktur [Rectangle](../../com.aspose.drawing/rectangle) untuk diuji. |
| g | [Graphics](../../com.aspose.drawing/graphics) | [Graphics](../../com.aspose.drawing/graphics) yang mewakili konteks grafis. |

**Returns:**
boolean - true ketika bagian mana pun dari `rect` berada di dalam [Region](../../com.aspose.drawing/region) ini; jika tidak, false.
