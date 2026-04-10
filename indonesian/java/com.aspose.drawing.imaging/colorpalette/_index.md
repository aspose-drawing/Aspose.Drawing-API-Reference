---
title: ColorPalette
second_title: Referensi API Aspose.Drawing for Java
description: Mendefinisikan array warna yang membentuk palet warna.
type: docs
weight: 16
url: /id/java/com.aspose.drawing.imaging/colorpalette/
---
**Inheritance:**
java.lang.Object
```
public final class ColorPalette
```

Mendefinisikan array warna yang membentuk palet warna. Warna-warna tersebut adalah warna ARGB 32-bit. Tidak dapat diwariskan.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [ColorPalette(int count)](#ColorPalette-int-) | Menginisialisasi instance baru dari kelas `ColorPalette` dan IsCompactPalette bernilai false. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getEntries()](#getEntries--) | Mendapatkan array struktur `com.aspose.drawing.Color`. |
| [isCompactPalette()](#isCompactPalette--) | Mendapatkan atau mengatur nilai yang menunjukkan apakah palet kompak digunakan. |
| [getFlags()](#getFlags--) |  |
| [setFlags(int flags)](#setFlags-int-) |  |
| [setEntries(int i, Color color)](#setEntries-int-com.aspose.drawing.Color-) |  |
### ColorPalette(int count) {#ColorPalette-int-}
```
public ColorPalette(int count)
```


Menginisialisasi instance baru dari kelas `ColorPalette` dan IsCompactPalette bernilai false.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| count | int | Entri palet warna. |

### getEntries() {#getEntries--}
```
public Color[] getEntries()
```


Mendapatkan array struktur `com.aspose.drawing.Color`.

**Returns:**
com.aspose.drawing.Color[] - Entri. Array struktur `com.aspose.drawing.Color` yang membentuk `Aspose.Imaging.ColorPalette` ini.
### isCompactPalette() {#isCompactPalette--}
```
public boolean isCompactPalette()
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah palet kompak digunakan.

**Returns:**
boolean - `true` jika palet kompak digunakan; jika tidak, `false`.

Palet kompak berarti gambar hanya akan berisi entri palet yang ditentukan jika memungkinkan, atau dengan kata lain gambar akan lebih kompak dan memakan ruang lebih sedikit; jika tidak, akan ada entri 2^BitsPerPixel dan gambar akan menyisakan lebih banyak ruang untuk semua kemungkinan entri palet. Menetapkan nilai ini ke true dan mengubah entri palet dapat menyebabkan penalti kinerja karena pergerakan data dapat terjadi, jadi gunakan dengan hati-hati.
### getFlags() {#getFlags--}
```
public int getFlags()
```




**Returns:**
int
### setFlags(int flags) {#setFlags-int-}
```
public void setFlags(int flags)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| flags | int |  |

### setEntries(int i, Color color) {#setEntries-int-com.aspose.drawing.Color-}
```
public void setEntries(int i, Color color)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| i | int |  |
| color | [Color](../../com.aspose.drawing/color) |  |

