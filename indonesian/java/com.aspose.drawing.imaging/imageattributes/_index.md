---
title: ImageAttributes
second_title: Referensi API Aspose.Drawing for Java
description: Berisi informasi tentang bagaimana warna bitmap dan metafile dimanipulasi selama rendering.
type: docs
weight: 24
url: /id/java/com.aspose.drawing.imaging/imageattributes/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public final class ImageAttributes implements System.IDisposable
```

Berisi informasi tentang bagaimana warna bitmap dan metafile dimanipulasi selama rendering.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [ImageAttributes()](#ImageAttributes--) | Menginisialisasi instance baru dari kelas [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes). |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [dispose()](#dispose--) | Melepaskan semua sumber daya yang digunakan oleh objek [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes) ini. |
| [deepClone()](#deepClone--) | Membuat salinan persis dari objek [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes) ini. |
| [setColorMatrix(ColorMatrix newColorMatrix)](#setColorMatrix-com.aspose.drawing.imaging.ColorMatrix-) | Mengatur matriks penyesuaian warna untuk kategori default. |
| [setColorMatrix(ColorMatrix newColorMatrix, int flags)](#setColorMatrix-com.aspose.drawing.imaging.ColorMatrix-int-) | Mengatur matriks penyesuaian warna untuk kategori default. |
| [setColorMatrix(ColorMatrix newColorMatrix, int mode, int type)](#setColorMatrix-com.aspose.drawing.imaging.ColorMatrix-int-int-) | Mengatur matriks penyesuaian warna untuk kategori yang ditentukan. |
| [clearColorMatrix()](#clearColorMatrix--) | Menghapus matriks penyesuaian warna untuk kategori default. |
| [clearColorMatrix(int type)](#clearColorMatrix-int-) | Menghapus matriks penyesuaian warna untuk kategori yang ditentukan. |
| [setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix)](#setColorMatrices-com.aspose.drawing.imaging.ColorMatrix-com.aspose.drawing.imaging.ColorMatrix-) | Menetapkan matriks penyesuaian warna dan matriks penyesuaian skala abu-abu untuk kategori default. |
| [setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int flags)](#setColorMatrices-com.aspose.drawing.imaging.ColorMatrix-com.aspose.drawing.imaging.ColorMatrix-int-) | Menetapkan matriks penyesuaian warna dan matriks penyesuaian skala abu-abu untuk kategori default. |
| [setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int mode, int type)](#setColorMatrices-com.aspose.drawing.imaging.ColorMatrix-com.aspose.drawing.imaging.ColorMatrix-int-int-) | Menetapkan matriks penyesuaian warna dan matriks penyesuaian skala abu-abu untuk kategori yang ditentukan. |
| [setThreshold(float threshold)](#setThreshold-float-) | Menetapkan ambang (rentang transparansi) untuk kategori default. |
| [setThreshold(float threshold, int type)](#setThreshold-float-int-) | Menetapkan ambang (rentang transparansi) untuk kategori yang ditentukan. |
| [clearThreshold()](#clearThreshold--) | Menghapus nilai ambang untuk kategori default. |
| [clearThreshold(int type)](#clearThreshold-int-) | Menghapus nilai ambang untuk kategori yang ditentukan. |
| [setGamma(float gamma)](#setGamma-float-) | Menetapkan nilai gamma untuk kategori default. |
| [setGamma(float gamma, int type)](#setGamma-float-int-) | Menetapkan nilai gamma untuk kategori yang ditentukan. |
| [clearGamma()](#clearGamma--) | Menonaktifkan koreksi gamma untuk kategori default. |
| [clearGamma(int type)](#clearGamma-int-) | Menonaktifkan koreksi gamma untuk kategori yang ditentukan. |
| [setNoOp()](#setNoOp--) | Mematikan penyesuaian warna untuk kategori default. |
| [setNoOp(int type)](#setNoOp-int-) | Mematikan penyesuaian warna untuk kategori yang ditentukan. |
| [clearNoOp()](#clearNoOp--) | Menghapus pengaturan NoOp untuk kategori default. |
| [clearNoOp(int type)](#clearNoOp-int-) | Menghapus pengaturan NoOp untuk kategori yang ditentukan. |
| [setColorKey(Color colorLow, Color colorHigh)](#setColorKey-com.aspose.drawing.Color-com.aspose.drawing.Color-) | Menetapkan kunci warna untuk kategori default. |
| [setColorKey(Color colorLow, Color colorHigh, int type)](#setColorKey-com.aspose.drawing.Color-com.aspose.drawing.Color-int-) | Menetapkan kunci warna (rentang transparansi) untuk kategori yang ditentukan. |
| [clearColorKey()](#clearColorKey--) | Menghapus kunci warna (rentang transparansi) untuk kategori default. |
| [clearColorKey(int type)](#clearColorKey-int-) | Menghapus kunci warna (rentang transparansi) untuk kategori yang ditentukan. |
| [setOutputChannel(int flags)](#setOutputChannel-int-) | Menetapkan saluran output CMYK (cyan-magenta-yellow-black) untuk kategori default. |
| [setOutputChannel(int flags, int type)](#setOutputChannel-int-int-) | Menetapkan saluran output CMYK (cyan-magenta-yellow-black) untuk kategori yang ditentukan. |
| [clearOutputChannel()](#clearOutputChannel--) | Menghapus pengaturan saluran output CMYK (cyan-magenta-yellow-black) untuk kategori default. |
| [clearOutputChannel(int type)](#clearOutputChannel-int-) | Menghapus pengaturan saluran output (cyan-magenta-yellow-black) untuk kategori yang ditentukan. |
| [setOutputChannelColorProfile(String colorProfileFilename)](#setOutputChannelColorProfile-java.lang.String-) | Menetapkan berkas profil warna saluran output untuk kategori default. |
| [setOutputChannelColorProfile(String colorProfileFilename, int type)](#setOutputChannelColorProfile-java.lang.String-int-) | Mengatur file profil warna saluran output untuk kategori tertentu. |
| [clearOutputChannelColorProfile()](#clearOutputChannelColorProfile--) | Menghapus pengaturan profil warna saluran output untuk kategori default. |
| [clearOutputChannelColorProfile(int type)](#clearOutputChannelColorProfile-int-) | Menghapus pengaturan profil warna saluran output untuk kategori tertentu. |
| [setRemapTable(ColorMap[] map)](#setRemapTable-com.aspose.drawing.imaging.ColorMap---) | Mengatur tabel remap warna untuk kategori default. |
| [setRemapTable(ColorMap[] map, int type)](#setRemapTable-com.aspose.drawing.imaging.ColorMap---int-) | Mengatur tabel remap warna untuk kategori tertentu. |
| [clearRemapTable()](#clearRemapTable--) | Menghapus tabel remap warna untuk kategori default. |
| [clearRemapTable(int type)](#clearRemapTable-int-) | Menghapus tabel remap warna untuk kategori tertentu. |
| [setBrushRemapTable(ColorMap[] map)](#setBrushRemapTable-com.aspose.drawing.imaging.ColorMap---) | Mengatur tabel remap warna untuk kategori kuas. |
| [clearBrushRemapTable()](#clearBrushRemapTable--) | Menghapus tabel remap warna kuas dari objek [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes) ini. |
| [setWrapMode(int mode)](#setWrapMode-int-) | Mengatur mode pembungkus yang digunakan untuk menentukan cara menempelkan tekstur pada sebuah bentuk, atau pada batas bentuk. |
| [setWrapMode(int mode, Color color)](#setWrapMode-int-com.aspose.drawing.Color-) | Mengatur mode pembungkus dan warna yang digunakan untuk menentukan cara menempelkan tekstur pada sebuah bentuk, atau pada batas bentuk. |
| [setWrapMode(int mode, Color color, boolean clamp)](#setWrapMode-int-com.aspose.drawing.Color-boolean-) | Mengatur mode pembungkus dan warna yang digunakan untuk menentukan cara menempelkan tekstur pada sebuah bentuk, atau pada batas bentuk. |
| [getAdjustedPalette(ColorPalette palette, int type)](#getAdjustedPalette-com.aspose.drawing.imaging.ColorPalette-int-) | Menyesuaikan warna dalam palet sesuai dengan pengaturan penyesuaian untuk kategori tertentu. |
### ImageAttributes() {#ImageAttributes--}
```
public ImageAttributes()
```


Menginisialisasi instance baru dari kelas [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes).

### dispose() {#dispose--}
```
public void dispose()
```


Melepaskan semua sumber daya yang digunakan oleh objek [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes) ini.

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Membuat salinan persis dari objek [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes) ini.

**Returns:**
java.lang.Object - Objek [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes) yang dibuat kelas ini, di-cast sebagai objek.
### setColorMatrix(ColorMatrix newColorMatrix) {#setColorMatrix-com.aspose.drawing.imaging.ColorMatrix-}
```
public void setColorMatrix(ColorMatrix newColorMatrix)
```


Mengatur matriks penyesuaian warna untuk kategori default.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) | Matriks penyesuaian warna. |

### setColorMatrix(ColorMatrix newColorMatrix, int flags) {#setColorMatrix-com.aspose.drawing.imaging.ColorMatrix-int-}
```
public void setColorMatrix(ColorMatrix newColorMatrix, int flags)
```


Mengatur matriks penyesuaian warna untuk kategori default.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) | Matriks penyesuaian warna. |
| flags | int | Elemen dari [ColorMatrixFlag](../../com.aspose.drawing.imaging/colormatrixflag) yang menentukan jenis gambar dan warna yang akan dipengaruhi oleh matriks penyesuaian warna. |

### setColorMatrix(ColorMatrix newColorMatrix, int mode, int type) {#setColorMatrix-com.aspose.drawing.imaging.ColorMatrix-int-int-}
```
public void setColorMatrix(ColorMatrix newColorMatrix, int mode, int type)
```


Mengatur matriks penyesuaian warna untuk kategori yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) | Matriks penyesuaian warna. |
| mode | int | Elemen dari [ColorMatrixFlag](../../com.aspose.drawing.imaging/colormatrixflag) yang menentukan jenis gambar dan warna yang akan dipengaruhi oleh matriks penyesuaian warna. |
| type | int | Elemen dari [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) yang menentukan kategori di mana matriks penyesuaian warna diatur. |

### clearColorMatrix() {#clearColorMatrix--}
```
public void clearColorMatrix()
```


Menghapus matriks penyesuaian warna untuk kategori default.

### clearColorMatrix(int type) {#clearColorMatrix-int-}
```
public void clearColorMatrix(int type)
```


Menghapus matriks penyesuaian warna untuk kategori yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| type | int | Elemen dari [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) yang menentukan kategori di mana matriks penyesuaian warna dihapus. |

### setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix) {#setColorMatrices-com.aspose.drawing.imaging.ColorMatrix-com.aspose.drawing.imaging.ColorMatrix-}
```
public void setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix)
```


Menetapkan matriks penyesuaian warna dan matriks penyesuaian skala abu-abu untuk kategori default.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) | Matriks penyesuaian warna. |
| grayMatrix | [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) | Matriks penyesuaian skala abu-abu. |

### setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int flags) {#setColorMatrices-com.aspose.drawing.imaging.ColorMatrix-com.aspose.drawing.imaging.ColorMatrix-int-}
```
public void setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int flags)
```


Menetapkan matriks penyesuaian warna dan matriks penyesuaian skala abu-abu untuk kategori default.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) | Matriks penyesuaian warna. |
| grayMatrix | [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) | Matriks penyesuaian skala abu-abu. |
| flags | int | Elemen dari [ColorMatrixFlag](../../com.aspose.drawing.imaging/colormatrixflag) yang menentukan jenis gambar dan warna yang akan dipengaruhi oleh matriks penyesuaian warna dan penyesuaian skala abu-abu. |

### setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int mode, int type) {#setColorMatrices-com.aspose.drawing.imaging.ColorMatrix-com.aspose.drawing.imaging.ColorMatrix-int-int-}
```
public void setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int mode, int type)
```


Menetapkan matriks penyesuaian warna dan matriks penyesuaian skala abu-abu untuk kategori yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) | Matriks penyesuaian warna. |
| grayMatrix | [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) | Matriks penyesuaian skala abu-abu. |
| mode | int | Elemen dari [ColorMatrixFlag](../../com.aspose.drawing.imaging/colormatrixflag) yang menentukan jenis gambar dan warna yang akan dipengaruhi oleh matriks penyesuaian warna dan penyesuaian skala abu-abu. |
| type | int | Elemen dari [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) yang menentukan kategori di mana matriks penyesuaian warna dan penyesuaian skala abu-abu diatur. |

### setThreshold(float threshold) {#setThreshold-float-}
```
public void setThreshold(float threshold)
```


Menetapkan ambang (rentang transparansi) untuk kategori default.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| ambang | float | Bilangan riil yang menentukan nilai ambang. |

### setThreshold(float threshold, int type) {#setThreshold-float-int-}
```
public void setThreshold(float threshold, int type)
```


Menetapkan ambang (rentang transparansi) untuk kategori yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| ambang | float | Nilai ambang dari 0,0 hingga 1,0 yang digunakan sebagai titik batas untuk mengurutkan warna yang akan dipetakan ke nilai maksimum atau minimum. |
| type | int | Elemen dari [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) yang menentukan kategori di mana ambang warna diatur. |

### clearThreshold() {#clearThreshold--}
```
public void clearThreshold()
```


Menghapus nilai ambang untuk kategori default.

### clearThreshold(int type) {#clearThreshold-int-}
```
public void clearThreshold(int type)
```


Menghapus nilai ambang untuk kategori yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| type | int | Elemen dari [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) yang menentukan kategori di mana ambang dihapus. |

### setGamma(float gamma) {#setGamma-float-}
```
public void setGamma(float gamma)
```


Menetapkan nilai gamma untuk kategori default.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| gamma | float | Nilai koreksi gamma. |

### setGamma(float gamma, int type) {#setGamma-float-int-}
```
public void setGamma(float gamma, int type)
```


Menetapkan nilai gamma untuk kategori yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| gamma | float | Nilai koreksi gamma. |
| type | int | Elemen dari enumerasi [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) yang menentukan kategori di mana nilai gamma diatur. |

### clearGamma() {#clearGamma--}
```
public void clearGamma()
```


Menonaktifkan koreksi gamma untuk kategori default.

### clearGamma(int type) {#clearGamma-int-}
```
public void clearGamma(int type)
```


Menonaktifkan koreksi gamma untuk kategori yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| type | int | Elemen [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) yang menentukan kategori di mana koreksi gamma dinonaktifkan. |

### setNoOp() {#setNoOp--}
```
public void setNoOp()
```


Mematikan penyesuaian warna untuk kategori default. Anda dapat memanggil metode [.clearNoOp](../../null/\#clearNoOp) untuk mengembalikan pengaturan penyesuaian warna yang ada sebelum pemanggilan metode [.setNoOp](../../null/\#setNoOp).

### setNoOp(int type) {#setNoOp-int-}
```
public void setNoOp(int type)
```


Mematikan penyesuaian warna untuk kategori yang ditentukan. Anda dapat memanggil metode [.clearNoOp](../../null/\#clearNoOp) untuk mengembalikan pengaturan penyesuaian warna yang ada sebelum pemanggilan metode [.setNoOp](../../null/\#setNoOp).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| type | int | Elemen [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) yang menentukan kategori di mana koreksi warna dimatikan. |

### clearNoOp() {#clearNoOp--}
```
public void clearNoOp()
```


Menghapus pengaturan NoOp untuk kategori default.

### clearNoOp(int type) {#clearNoOp-int-}
```
public void clearNoOp(int type)
```


Menghapus pengaturan NoOp untuk kategori yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| type | int | Elemen [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) yang menentukan kategori di mana pengaturan NoOp dibersihkan. |

### setColorKey(Color colorLow, Color colorHigh) {#setColorKey-com.aspose.drawing.Color-com.aspose.drawing.Color-}
```
public void setColorKey(Color colorLow, Color colorHigh)
```


Menetapkan kunci warna untuk kategori default.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| colorLow | [Color](../../com.aspose.drawing/color) | Nilai kunci warna rendah. |
| colorHigh | [Color](../../com.aspose.drawing/color) | Nilai kunci warna tinggi. |

### setColorKey(Color colorLow, Color colorHigh, int type) {#setColorKey-com.aspose.drawing.Color-com.aspose.drawing.Color-int-}
```
public void setColorKey(Color colorLow, Color colorHigh, int type)
```


Menetapkan kunci warna (rentang transparansi) untuk kategori yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| colorLow | [Color](../../com.aspose.drawing/color) | Nilai kunci warna rendah. |
| colorHigh | [Color](../../com.aspose.drawing/color) | Nilai kunci warna tinggi. |
| type | int | Elemen [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) yang menentukan kategori di mana kunci warna diatur. |

### clearColorKey() {#clearColorKey--}
```
public void clearColorKey()
```


Menghapus kunci warna (rentang transparansi) untuk kategori default.

### clearColorKey(int type) {#clearColorKey-int-}
```
public void clearColorKey(int type)
```


Menghapus kunci warna (rentang transparansi) untuk kategori yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| type | int | Elemen [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) yang menentukan kategori di mana kunci warna dibersihkan. |

### setOutputChannel(int flags) {#setOutputChannel-int-}
```
public void setOutputChannel(int flags)
```


Menetapkan saluran output CMYK (cyan-magenta-yellow-black) untuk kategori default.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| flags | int | Elemen [ColorChannelFlag](../../com.aspose.drawing.imaging/colorchannelflag) yang menentukan saluran keluaran. |

### setOutputChannel(int flags, int type) {#setOutputChannel-int-int-}
```
public void setOutputChannel(int flags, int type)
```


Menetapkan saluran output CMYK (cyan-magenta-yellow-black) untuk kategori yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| flags | int | Elemen [ColorChannelFlag](../../com.aspose.drawing.imaging/colorchannelflag) yang menentukan saluran keluaran. |
| type | int | Elemen [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) yang menentukan kategori di mana saluran keluaran diatur. |

### clearOutputChannel() {#clearOutputChannel--}
```
public void clearOutputChannel()
```


Menghapus pengaturan saluran output CMYK (cyan-magenta-yellow-black) untuk kategori default.

### clearOutputChannel(int type) {#clearOutputChannel-int-}
```
public void clearOutputChannel(int type)
```


Menghapus pengaturan saluran output (cyan-magenta-yellow-black) untuk kategori yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| type | int | Elemen [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) yang menentukan kategori di mana pengaturan saluran keluaran dibersihkan. |

### setOutputChannelColorProfile(String colorProfileFilename) {#setOutputChannelColorProfile-java.lang.String-}
```
public void setOutputChannelColorProfile(String colorProfileFilename)
```


Menetapkan berkas profil warna saluran output untuk kategori default.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| colorProfileFilename | java.lang.String | Nama jalur file profil warna. Jika file profil warna berada di direktori %SystemRoot%\\System32\\Spool\\Drivers\\Color, parameter ini dapat berupa nama file. Jika tidak, parameter ini harus berupa nama jalur lengkap. |

### setOutputChannelColorProfile(String colorProfileFilename, int type) {#setOutputChannelColorProfile-java.lang.String-int-}
```
public void setOutputChannelColorProfile(String colorProfileFilename, int type)
```


Mengatur file profil warna saluran output untuk kategori tertentu.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| colorProfileFilename | java.lang.String | Nama jalur file profil warna. Jika file profil warna berada di direktori %SystemRoot%\\System32\\Spool\\Drivers\\Color, parameter ini dapat berupa nama file. Jika tidak, parameter ini harus berupa nama jalur lengkap. |
| type | int | Elemen [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) yang menentukan kategori di mana file profil warna saluran keluaran diatur. |

### clearOutputChannelColorProfile() {#clearOutputChannelColorProfile--}
```
public void clearOutputChannelColorProfile()
```


Menghapus pengaturan profil warna saluran output untuk kategori default.

### clearOutputChannelColorProfile(int type) {#clearOutputChannelColorProfile-int-}
```
public void clearOutputChannelColorProfile(int type)
```


Menghapus pengaturan profil warna saluran output untuk kategori tertentu.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| type | int | Elemen [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) yang menentukan kategori di mana pengaturan profil saluran keluaran dibersihkan. |

### setRemapTable(ColorMap[] map) {#setRemapTable-com.aspose.drawing.imaging.ColorMap---}
```
public void setRemapTable(ColorMap[] map)
```


Mengatur tabel remap warna untuk kategori default.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| map | [ColorMap\[\]](../../com.aspose.drawing.imaging/colormap) | Array pasangan warna bertipe [ColorMap](../../com.aspose.drawing.imaging/colormap). Setiap pasangan warna berisi warna yang ada (nilai pertama) dan warna yang akan dipetakan kepadanya (nilai kedua). |

### setRemapTable(ColorMap[] map, int type) {#setRemapTable-com.aspose.drawing.imaging.ColorMap---int-}
```
public void setRemapTable(ColorMap[] map, int type)
```


Mengatur tabel remap warna untuk kategori tertentu.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| map | [ColorMap\[\]](../../com.aspose.drawing.imaging/colormap) | Array pasangan warna bertipe [ColorMap](../../com.aspose.drawing.imaging/colormap). Setiap pasangan warna berisi warna yang ada (nilai pertama) dan warna yang akan dipetakan kepadanya (nilai kedua). |
| type | int | Elemen [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) yang menentukan kategori di mana tabel pemetaan ulang warna diatur. |

### clearRemapTable() {#clearRemapTable--}
```
public void clearRemapTable()
```


Menghapus tabel remap warna untuk kategori default.

### clearRemapTable(int type) {#clearRemapTable-int-}
```
public void clearRemapTable(int type)
```


Menghapus tabel remap warna untuk kategori tertentu.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| type | int | Elemen [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) yang menentukan kategori di mana tabel pemetaan ulang dibersihkan. |

### setBrushRemapTable(ColorMap[] map) {#setBrushRemapTable-com.aspose.drawing.imaging.ColorMap---}
```
public void setBrushRemapTable(ColorMap[] map)
```


Mengatur tabel remap warna untuk kategori kuas.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| map | [ColorMap\[\]](../../com.aspose.drawing.imaging/colormap) | Array objek [ColorMap](../../com.aspose.drawing.imaging/colormap). |

### clearBrushRemapTable() {#clearBrushRemapTable--}
```
public void clearBrushRemapTable()
```


Menghapus tabel remap warna kuas dari objek [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes) ini.

### setWrapMode(int mode) {#setWrapMode-int-}
```
public void setWrapMode(int mode)
```


Menetapkan mode pembungkus yang digunakan untuk menentukan cara menempelkan tekstur pada sebuah bentuk, atau pada batas bentuk. Tekstur ditempelkan pada bentuk untuk mengisinya ketika tekstur lebih kecil daripada bentuk yang diisi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| mode | int | Elemen [WrapMode](../../com.aspose.drawing.drawing2d/wrapmode) yang menentukan bagaimana salinan berulang gambar digunakan untuk menempelkan area. |

### setWrapMode(int mode, Color color) {#setWrapMode-int-com.aspose.drawing.Color-}
```
public void setWrapMode(int mode, Color color)
```


Mengatur mode pembungkus dan warna yang digunakan untuk menentukan cara menata tekstur di seluruh bentuk, atau pada batas bentuk. Tekstur ditata di seluruh bentuk untuk mengisinya ketika tekstur lebih kecil daripada bentuk yang diisi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| mode | int | Elemen [WrapMode](../../com.aspose.drawing.drawing2d/wrapmode) yang menentukan bagaimana salinan berulang gambar digunakan untuk menempelkan area. |
| color | [Color](../../com.aspose.drawing/color) | Objek [Color](../../com.aspose.drawing/color) yang menentukan warna piksel di luar gambar yang dirender. Warna ini terlihat jika parameter mode diatur ke `WrapMode.Clamp` dan persegi panjang sumber yang diberikan ke `Graphics.DrawImage` lebih besar daripada gambar itu sendiri. |

### setWrapMode(int mode, Color color, boolean clamp) {#setWrapMode-int-com.aspose.drawing.Color-boolean-}
```
public void setWrapMode(int mode, Color color, boolean clamp)
```


Mengatur mode pembungkus dan warna yang digunakan untuk menentukan cara menata tekstur di seluruh bentuk, atau pada batas bentuk. Tekstur ditata di seluruh bentuk untuk mengisinya ketika tekstur lebih kecil daripada bentuk yang diisi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| mode | int | Elemen [WrapMode](../../com.aspose.drawing.drawing2d/wrapmode) yang menentukan bagaimana salinan berulang gambar digunakan untuk menempelkan area. |
| color | [Color](../../com.aspose.drawing/color) | Objek warna yang menentukan warna piksel di luar gambar yang dirender. Warna ini terlihat jika parameter mode diatur ke `WrapMode.Clamp` dan persegi panjang sumber yang diberikan ke `Graphics.DrawImage` lebih besar daripada gambar itu sendiri. |
| clamp | boolean | Parameter ini tidak berpengaruh. Atur ke false. |

### getAdjustedPalette(ColorPalette palette, int type) {#getAdjustedPalette-com.aspose.drawing.imaging.ColorPalette-int-}
```
public void getAdjustedPalette(ColorPalette palette, int type)
```


Menyesuaikan warna dalam palet sesuai dengan pengaturan penyesuaian untuk kategori tertentu.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| palette | [ColorPalette](../../com.aspose.drawing.imaging/colorpalette) | Sebuah [ColorPalette](../../com.aspose.drawing.imaging/colorpalette) yang pada input berisi palet yang akan disesuaikan, dan pada output berisi palet yang telah disesuaikan. |
| type | int | Elemen dari [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) yang menentukan kategori yang pengaturan penyesuaiannya akan diterapkan pada palet. |

