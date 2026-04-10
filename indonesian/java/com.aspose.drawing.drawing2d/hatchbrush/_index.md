---
title: HatchBrush
second_title: Referensi API Aspose.Drawing for Java
description: Mendefinisikan kuas persegi panjang dengan gaya hatch, warna latar depan, dan warna latar belakang.
type: docs
weight: 26
url: /id/java/com.aspose.drawing.drawing2d/hatchbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.drawing.Brush](../../com.aspose.drawing/brush)
```
public final class HatchBrush extends Brush
```

Mendefinisikan kuas persegi panjang dengan gaya hatch, warna latar depan, dan warna latar belakang. Kelas ini tidak dapat diwariskan.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [HatchBrush(int hatchstyle, Color foreColor)](#HatchBrush-int-com.aspose.drawing.Color-) | Menginisialisasi instance baru dari kelas [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) dengan enumerasi `HatchStyle`([.getHatchStyle](../../null/\#getHatchStyle)) yang ditentukan dan warna latar depan. |
| [HatchBrush(int hatchstyle, Color foreColor, Color backColor)](#HatchBrush-int-com.aspose.drawing.Color-com.aspose.drawing.Color-) | Menginisialisasi instance baru dari kelas [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) dengan enumerasi `HatchStyle`([.getHatchStyle](../../null/\#getHatchStyle)) yang ditentukan, warna latar depan, dan warna latar belakang. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getHatchStyle()](#getHatchStyle--) | Mendapatkan gaya hatch dari objek [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush). |
| [getForegroundColor()](#getForegroundColor--) | Mendapatkan warna garis hatch yang digambar oleh objek [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush). |
| [getBackgroundColor()](#getBackgroundColor--) | Mendapatkan warna ruang di antara garis hatch yang digambar oleh objek [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush). |
| [deepClone()](#deepClone--) | Membuat salinan persis dari objek [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush). |
### HatchBrush(int hatchstyle, Color foreColor) {#HatchBrush-int-com.aspose.drawing.Color-}
```
public HatchBrush(int hatchstyle, Color foreColor)
```


Menginisialisasi instance baru dari kelas [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) dengan enumerasi `HatchStyle`([.getHatchStyle](../../null/\#getHatchStyle)) yang ditentukan dan warna latar depan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| hatchstyle | int | Salah satu nilai `HatchStyle`([.getHatchStyle](../../null/\#getHatchStyle)) yang mewakili pola yang digambar oleh [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush). |
| foreColor | [Color](../../com.aspose.drawing/color) | Struktur [Color](../../com.aspose.drawing/color) yang mewakili warna garis yang digambar oleh [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush). |

### HatchBrush(int hatchstyle, Color foreColor, Color backColor) {#HatchBrush-int-com.aspose.drawing.Color-com.aspose.drawing.Color-}
```
public HatchBrush(int hatchstyle, Color foreColor, Color backColor)
```


Menginisialisasi instance baru dari kelas [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) dengan enumerasi `HatchStyle`([.getHatchStyle](../../null/\#getHatchStyle)) yang ditentukan, warna latar depan, dan warna latar belakang.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| hatchstyle | int | Salah satu nilai `HatchStyle`([.getHatchStyle](../../null/\#getHatchStyle)) yang mewakili pola yang digambar oleh [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush). |
| foreColor | [Color](../../com.aspose.drawing/color) | Struktur [Color](../../com.aspose.drawing/color) yang mewakili warna garis yang digambar oleh [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush). |
| backColor | [Color](../../com.aspose.drawing/color) | Struktur [Color](../../com.aspose.drawing/color) yang mewakili warna ruang di antara garis yang digambar oleh [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush). |

### getHatchStyle() {#getHatchStyle--}
```
public int getHatchStyle()
```


Mendapatkan gaya hatch dari objek [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush).

**Returns:**
int - gaya hatch dari objek [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush).
### getForegroundColor() {#getForegroundColor--}
```
public Color getForegroundColor()
```


Mendapatkan warna garis hatch yang digambar oleh objek [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush).

**Returns:**
[Color](../../com.aspose.drawing/color) - the color of hatch lines drawn by this [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) object.
### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Mendapatkan warna ruang di antara garis hatch yang digambar oleh objek [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush).

**Returns:**
[Color](../../com.aspose.drawing/color) - the color of spaces between the hatch lines drawn by this [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) object.
### deepClone() {#deepClone--}
```
public Object deepClone()
```


Membuat salinan persis dari objek [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush).

**Returns:**
java.lang.Object - [HatchBrush](../../com.aspose.drawing.drawing2d/hatchbrush) yang dibuat oleh metode ini, dikast sebagai objek.
