---
title: CustomLineCap
second_title: Referensi API Aspose.Drawing for Java
description: Mengkapsulkan penutup garis khusus yang didefinisikan pengguna.
type: docs
weight: 17
url: /id/java/com.aspose.drawing.drawing2d/customlinecap/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public class CustomLineCap implements System.IDisposable
```

Mengkapsulkan penutup garis khusus yang didefinisikan pengguna.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath)](#CustomLineCap-com.aspose.drawing.drawing2d.GraphicsPath-com.aspose.drawing.drawing2d.GraphicsPath-) | Menginisialisasi instance baru dari kelas [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) dengan garis luar dan isi yang ditentukan. |
| [CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap)](#CustomLineCap-com.aspose.drawing.drawing2d.GraphicsPath-com.aspose.drawing.drawing2d.GraphicsPath-int-) | Menginisialisasi instance baru dari kelas [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) dari enumerasi [LineCap](../../com.aspose.drawing.drawing2d/linecap) yang ada dengan garis luar dan isi yang ditentukan. |
| [CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap, float baseInset)](#CustomLineCap-com.aspose.drawing.drawing2d.GraphicsPath-com.aspose.drawing.drawing2d.GraphicsPath-int-float-) | Menginisialisasi instance baru dari kelas [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) dari enumerasi [LineCap](../../com.aspose.drawing.drawing2d/linecap) yang ada dengan garis luar, isi, dan inset yang ditentukan. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getStrokeJoin()](#getStrokeJoin--) | Mendapatkan atau mengatur enumerasi [LineJoin](../../com.aspose.drawing.drawing2d/linejoin) yang menentukan bagaimana garis-garis yang menyusun objek [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) ini digabungkan. |
| [setStrokeJoin(int value)](#setStrokeJoin-int-) | Mendapatkan atau mengatur enumerasi [LineJoin](../../com.aspose.drawing.drawing2d/linejoin) yang menentukan bagaimana garis-garis yang menyusun objek [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) ini digabungkan. |
| [getBaseCap()](#getBaseCap--) | Mendapatkan atau mengatur enumerasi [LineCap](../../com.aspose.drawing.drawing2d/linecap) yang menjadi dasar [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) ini. |
| [setBaseCap(int value)](#setBaseCap-int-) | Mendapatkan atau mengatur enumerasi [LineCap](../../com.aspose.drawing.drawing2d/linecap) yang menjadi dasar [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) ini. |
| [getBaseInset()](#getBaseInset--) | Mendapatkan atau mengatur jarak antara cap dan garis. |
| [setBaseInset(float value)](#setBaseInset-float-) | Mendapatkan atau mengatur jarak antara cap dan garis. |
| [getWidthScale()](#getWidthScale--) | Mendapatkan atau mengatur jumlah skala objek Kelas [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) ini relatif terhadap lebar objek [Pen](../../com.aspose.drawing/pen). |
| [setWidthScale(float value)](#setWidthScale-float-) | Mendapatkan atau mengatur jumlah skala objek Kelas [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) ini relatif terhadap lebar objek [Pen](../../com.aspose.drawing/pen). |
| [dispose()](#dispose--) | Melepaskan semua sumber daya yang digunakan oleh objek [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) ini. |
| [deepClone()](#deepClone--) | Membuat salinan persis dari [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) ini. |
| [setStrokeCaps(int startCap, int endCap)](#setStrokeCaps-int-int-) | Mengatur penutup yang digunakan untuk memulai dan mengakhiri garis yang membentuk penutup khusus ini. |
| [getStrokeCaps(int[] startCap, int[] endCap)](#getStrokeCaps-int---int---) | Mendapatkan penutup yang digunakan untuk memulai dan mengakhiri garis yang membentuk penutup khusus ini. |
| [getFillPath()](#getFillPath--) |  |
| [getStrokePath()](#getStrokePath--) | Mendapatkan objek yang mendefinisikan kontur penutup khusus. |
### CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath) {#CustomLineCap-com.aspose.drawing.drawing2d.GraphicsPath-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath)
```


Menginisialisasi instance baru dari kelas [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) dengan garis luar dan isi yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fillPath | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | Objek [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) yang mendefinisikan isian untuk penutup khusus. |
| strokePath | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | Objek [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) yang mendefinisikan kontur penutup khusus. |

### CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap) {#CustomLineCap-com.aspose.drawing.drawing2d.GraphicsPath-com.aspose.drawing.drawing2d.GraphicsPath-int-}
```
public CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap)
```


Menginisialisasi instance baru dari kelas [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) dari enumerasi [LineCap](../../com.aspose.drawing.drawing2d/linecap) yang ada dengan garis luar dan isi yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fillPath | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | Objek [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) yang mendefinisikan isian untuk penutup khusus. |
| strokePath | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | Objek [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) yang mendefinisikan kontur penutup khusus. |
| baseCap | int | Penutup garis yang digunakan untuk membuat penutup khusus. |

### CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap, float baseInset) {#CustomLineCap-com.aspose.drawing.drawing2d.GraphicsPath-com.aspose.drawing.drawing2d.GraphicsPath-int-float-}
```
public CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap, float baseInset)
```


Menginisialisasi instance baru dari kelas [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) dari enumerasi [LineCap](../../com.aspose.drawing.drawing2d/linecap) yang ada dengan garis luar, isi, dan inset yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fillPath | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | Objek [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) yang mendefinisikan isian untuk penutup khusus. |
| strokePath | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | Objek [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) yang mendefinisikan kontur penutup khusus. |
| baseCap | int | Penutup garis yang digunakan untuk membuat penutup khusus. |
| baseInset | float | Jarak antara penutup dan garis. |

### getStrokeJoin() {#getStrokeJoin--}
```
public final int getStrokeJoin()
```


Mendapatkan atau mengatur enumerasi [LineJoin](../../com.aspose.drawing.drawing2d/linejoin) yang menentukan bagaimana garis-garis yang menyusun objek [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) ini digabungkan.

**Returns:**
int
### setStrokeJoin(int value) {#setStrokeJoin-int-}
```
public final void setStrokeJoin(int value)
```


Mendapatkan atau mengatur enumerasi [LineJoin](../../com.aspose.drawing.drawing2d/linejoin) yang menentukan bagaimana garis-garis yang menyusun objek [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) ini digabungkan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getBaseCap() {#getBaseCap--}
```
public final int getBaseCap()
```


Mendapatkan atau mengatur enumerasi [LineCap](../../com.aspose.drawing.drawing2d/linecap) yang menjadi dasar [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) ini.

**Returns:**
int
### setBaseCap(int value) {#setBaseCap-int-}
```
public final void setBaseCap(int value)
```


Mendapatkan atau mengatur enumerasi [LineCap](../../com.aspose.drawing.drawing2d/linecap) yang menjadi dasar [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getBaseInset() {#getBaseInset--}
```
public final float getBaseInset()
```


Mendapatkan atau mengatur jarak antara cap dan garis.

**Returns:**
float
### setBaseInset(float value) {#setBaseInset-float-}
```
public final void setBaseInset(float value)
```


Mendapatkan atau mengatur jarak antara cap dan garis.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float |  |

### getWidthScale() {#getWidthScale--}
```
public final float getWidthScale()
```


Mendapatkan atau mengatur jumlah skala objek Kelas [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) ini relatif terhadap lebar objek [Pen](../../com.aspose.drawing/pen).

**Returns:**
float
### setWidthScale(float value) {#setWidthScale-float-}
```
public final void setWidthScale(float value)
```


Mendapatkan atau mengatur jumlah skala objek Kelas [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) ini relatif terhadap lebar objek [Pen](../../com.aspose.drawing/pen).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float |  |

### dispose() {#dispose--}
```
public final void dispose()
```


Melepaskan semua sumber daya yang digunakan oleh objek [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) ini.

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Membuat salinan persis dari [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) ini.

**Returns:**
java.lang.Object - [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) yang dibuat oleh metode ini, di-cast sebagai objek.
### setStrokeCaps(int startCap, int endCap) {#setStrokeCaps-int-int-}
```
public final void setStrokeCaps(int startCap, int endCap)
```


Mengatur penutup yang digunakan untuk memulai dan mengakhiri garis yang membentuk penutup khusus ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| startCap | int | [LineCap](../../com.aspose.drawing.drawing2d/linecap) enumerasi yang digunakan pada awal garis dalam penutup ini. |
| endCap | int | [LineCap](../../com.aspose.drawing.drawing2d/linecap) enumerasi yang digunakan pada akhir garis dalam penutup ini. |

### getStrokeCaps(int[] startCap, int[] endCap) {#getStrokeCaps-int---int---}
```
public final void getStrokeCaps(int[] startCap, int[] endCap)
```


Mendapatkan penutup yang digunakan untuk memulai dan mengakhiri garis yang membentuk penutup khusus ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| startCap | int[] | [LineCap](../../com.aspose.drawing.drawing2d/linecap) enumerasi yang digunakan pada awal garis dalam penutup ini. |
| endCap | int[] | [LineCap](../../com.aspose.drawing.drawing2d/linecap) enumerasi yang digunakan pada akhir garis dalam penutup ini. |

### getFillPath() {#getFillPath--}
```
public GraphicsPath getFillPath()
```




**Returns:**
[GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath)
### getStrokePath() {#getStrokePath--}
```
public GraphicsPath getStrokePath()
```


Mendapatkan objek yang mendefinisikan kontur penutup khusus.

**Returns:**
[GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) - The object that defines the outline of the custom cap.
