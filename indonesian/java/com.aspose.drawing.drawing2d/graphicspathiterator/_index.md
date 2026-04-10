---
title: GraphicsPathIterator
second_title: Referensi API Aspose.Drawing for Java
description: Menyediakan kemampuan untuk mengiterasi subpath dalam sebuah  dan menguji jenis bentuk yang terdapat dalam setiap subpath.
type: docs
weight: 24
url: /id/java/com.aspose.drawing.drawing2d/graphicspathiterator/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public final class GraphicsPathIterator implements System.IDisposable
```

Menyediakan kemampuan untuk mengiterasi subpath dalam sebuah [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) dan menguji jenis bentuk yang terkandung dalam setiap subpath. Kelas ini tidak dapat diwariskan.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [GraphicsPathIterator(GraphicsPath path)](#GraphicsPathIterator-com.aspose.drawing.drawing2d.GraphicsPath-) | Menginisialisasi instance baru dari kelas [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator). |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getCount()](#getCount--) | Mendapatkan jumlah titik dalam path. |
| [getSubpathCount()](#getSubpathCount--) | Mendapatkan jumlah subpath dalam path. |
| [dispose()](#dispose--) | Melakukan tugas yang ditentukan aplikasi terkait dengan membebaskan, melepaskan, atau mereset sumber daya yang tidak dikelola. |
| [copyData(PointF[][] points, byte[][] types, int startIndex, int endIndex)](#copyData-com.aspose.drawing.PointF-----byte-----int-int-) | Menyalin properti GraphicsPath.PathPoints dan array properti GraphicsPath.PathTypes dari [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) yang terkait ke dalam dua array yang ditentukan. |
| [enumerate(PointF[][] points, byte[][] types)](#enumerate-com.aspose.drawing.PointF-----byte-----) | Menyalin properti GraphicsPath.PathPoints dan array properti GraphicsPath.PathTypes dari [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) yang terkait ke dalam dua array yang ditentukan. |
| [hasCurve()](#hasCurve--) | Menunjukkan apakah path yang terkait dengan [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) ini mengandung kurva. |
| [nextMarker(int[] startIndex, int[] endIndex)](#nextMarker-int---int---) | Meningkatkan [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) ke penanda berikutnya dalam path dan mengembalikan indeks mulai dan berhenti melalui parameter [out]. |
| [nextMarker(GraphicsPath path)](#nextMarker-com.aspose.drawing.drawing2d.GraphicsPath-) | Objek [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) ini memiliki objek [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) yang terkait dengannya. |
| [nextPathType(byte[] pathType, int[] startIndex, int[] endIndex)](#nextPathType-byte---int---int---) | Mendapatkan indeks mulai dan indeks akhir dari grup titik data berikutnya yang semuanya memiliki tipe yang sama. |
| [nextSubpath(int[] startIndex, int[] endIndex, boolean[] isClosed)](#nextSubpath-int---int---boolean---) | Memindahkan [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) ke subpath berikutnya dalam path. |
| [nextSubpath(GraphicsPath path, boolean[] isClosed)](#nextSubpath-com.aspose.drawing.drawing2d.GraphicsPath-boolean---) | Mendapatkan gambar berikutnya (subpath) dari path yang terkait dengan [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) ini. |
| [rewind()](#rewind--) | Membalik kembali [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) ini ke awal path yang terkait. |
### GraphicsPathIterator(GraphicsPath path) {#GraphicsPathIterator-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public GraphicsPathIterator(GraphicsPath path)
```


Menginisialisasi instance baru dari kelas [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | Objek [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) yang akan diinisialisasi untuk kelas pembantu ini. |

### getCount() {#getCount--}
```
public int getCount()
```


Mendapatkan jumlah titik dalam path.

**Returns:**
int - jumlah titik dalam path.
### getSubpathCount() {#getSubpathCount--}
```
public int getSubpathCount()
```


Mendapatkan jumlah subpath dalam path.

**Returns:**
int - jumlah subpath dalam path.
### dispose() {#dispose--}
```
public void dispose()
```


Melakukan tugas yang ditentukan aplikasi terkait dengan membebaskan, melepaskan, atau mereset sumber daya yang tidak dikelola.

### copyData(PointF[][] points, byte[][] types, int startIndex, int endIndex) {#copyData-com.aspose.drawing.PointF-----byte-----int-int-}
```
public int copyData(PointF[][] points, byte[][] types, int startIndex, int endIndex)
```


Menyalin properti GraphicsPath.PathPoints dan array properti GraphicsPath.PathTypes dari [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) yang terkait ke dalam dua array yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.drawing/pointf) | Setelah pengembalian, berisi array struktur System.Drawing.PointF yang mewakili titik-titik dalam path. |
| tipe | byte[][] | Setelah pengembalian, berisi array byte yang mewakili tipe-tipe titik dalam path. |
| startIndex | int | Menentukan indeks mulai dari array. |
| endIndex | int | Menentukan indeks akhir dari array. |

**Returns:**
int - Jumlah titik yang disalin.
### enumerate(PointF[][] points, byte[][] types) {#enumerate-com.aspose.drawing.PointF-----byte-----}
```
public int enumerate(PointF[][] points, byte[][] types)
```


Menyalin properti GraphicsPath.PathPoints dan array properti GraphicsPath.PathTypes dari [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) yang terkait ke dalam dua array yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.drawing/pointf) | Setelah pengembalian, berisi array struktur System.Drawing.PointF yang mewakili titik-titik dalam path. |
| tipe | byte[][] | Setelah pengembalian, berisi array byte yang mewakili tipe-tipe titik dalam path. |

**Returns:**
int - Jumlah titik yang disalin.
### hasCurve() {#hasCurve--}
```
public boolean hasCurve()
```


Menunjukkan apakah path yang terkait dengan [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) ini mengandung kurva.

**Returns:**
boolean - Metode ini mengembalikan true jika subpath saat ini berisi kurva; jika tidak, false.
### nextMarker(int[] startIndex, int[] endIndex) {#nextMarker-int---int---}
```
public int nextMarker(int[] startIndex, int[] endIndex)
```


Meningkatkan [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) ke penanda berikutnya dalam path dan mengembalikan indeks mulai dan berhenti melalui parameter [out].

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| startIndex | int[] | [out] Referensi integer yang diberikan ke parameter ini menerima indeks titik yang memulai sebuah subpath. |
| endIndex | int[] | [out] Referensi integer yang diberikan ke parameter ini menerima indeks titik yang mengakhiri subpath yang ditunjuk oleh startIndex. |

**Returns:**
int - Jumlah titik antara penanda ini dan penanda berikutnya.
### nextMarker(GraphicsPath path) {#nextMarker-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public int nextMarker(GraphicsPath path)
```


Objek [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) ini memiliki objek [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) yang terkait dengannya. Metode ini meningkatkan [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) yang terkait ke penanda berikutnya dalam jalurnya dan menyalin semua titik yang berada di antara penanda saat ini dan penanda berikutnya (atau akhir jalur) ke objek [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) kedua yang diberikan melalui parameter.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | Objek [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) yang akan menjadi tujuan penyalinan titik. |

**Returns:**
int - Jumlah titik antara penanda ini dan penanda berikutnya.
### nextPathType(byte[] pathType, int[] startIndex, int[] endIndex) {#nextPathType-byte---int---int---}
```
public int nextPathType(byte[] pathType, int[] startIndex, int[] endIndex)
```


Mendapatkan indeks mulai dan indeks akhir dari grup titik data berikutnya yang semuanya memiliki tipe yang sama.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pathType | byte[] | [out] Menerima tipe titik yang dibagikan oleh semua titik dalam grup. Tipe yang mungkin dapat diambil dari enumerasi [PathPointType](../../com.aspose.drawing.drawing2d/pathpointtype). |
| startIndex | int[] | [out] Menerima indeks awal dari grup titik. |
| endIndex | int[] | [out] Menerima indeks akhir dari grup titik. |

**Returns:**
int - Metode ini mengembalikan jumlah titik data dalam grup. Jika tidak ada lagi grup dalam jalur, metode ini mengembalikan 0.
### nextSubpath(int[] startIndex, int[] endIndex, boolean[] isClosed) {#nextSubpath-int---int---boolean---}
```
public int nextSubpath(int[] startIndex, int[] endIndex, boolean[] isClosed)
```


Memindahkan [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) ke subpath berikutnya dalam jalur. Indeks awal dan indeks akhir subpath berikutnya terdapat dalam parameter [out].

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| startIndex | int[] | [out] Menerima indeks awal dari subpath berikutnya. |
| endIndex | int[] | [out] Menerima indeks akhir dari subpath berikutnya. |
| isClosed | boolean[] | [out] Menunjukkan apakah subpath ditutup. |

**Returns:**
int - Jumlah titik data dalam gambar (subpath) yang diambil. Jika tidak ada lagi gambar yang dapat diambil, nilai nol dikembalikan.
### nextSubpath(GraphicsPath path, boolean[] isClosed) {#nextSubpath-com.aspose.drawing.drawing2d.GraphicsPath-boolean---}
```
public int nextSubpath(GraphicsPath path, boolean[] isClosed)
```


Mendapatkan gambar berikutnya (subpath) dari path yang terkait dengan [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | Sebuah [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) yang akan memiliki titik datanya disetel agar cocok dengan titik data gambar (subpath) yang diambil untuk iterator ini. |
| isClosed | boolean[] | [out] Menunjukkan apakah subpath saat ini ditutup. Nilainya true jika gambar ditutup, jika tidak false. |

**Returns:**
int - Jumlah titik data dalam gambar (subpath) yang diambil. Jika tidak ada lagi gambar yang dapat diambil, nilai nol dikembalikan.
### rewind() {#rewind--}
```
public void rewind()
```


Membalik kembali [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) ini ke awal path yang terkait.

