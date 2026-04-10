---
title: InterpolationMode
second_title: Referensi API Aspose.Drawing for Java
description: Enum InterpolationMode menentukan algoritma yang digunakan ketika gambar diubah skala atau diputar.
type: docs
weight: 28
url: /id/java/com.aspose.drawing.drawing2d/interpolationmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class InterpolationMode extends System.Enum
```

Enum InterpolationMode menentukan algoritma yang digunakan ketika gambar diubah skala atau diputar.
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [Invalid](#Invalid) | Setara dengan elemen Invalid dari enumerasi QualityMode. |
| [Default](#Default) | Menentukan mode default. |
| [Low](#Low) | Menentukan interpolasi kualitas rendah. |
| [High](#High) | Menentukan interpolasi kualitas tinggi. |
| [Bilinear](#Bilinear) | Menentukan interpolasi bilinear. |
| [Bicubic](#Bicubic) | Menentukan interpolasi bikubik. |
| [NearestNeighbor](#NearestNeighbor) | Menentukan interpolasi tetangga terdekat. |
| [HighQualityBilinear](#HighQualityBilinear) | Menentukan interpolasi bilinear berkualitas tinggi. |
| [HighQualityBicubic](#HighQualityBicubic) | Menentukan interpolasi bikubik berkualitas tinggi. |
### Invalid {#Invalid}
```
public static final int Invalid
```


Setara dengan elemen Invalid dari enumerasi QualityMode.

### Default {#Default}
```
public static final int Default
```


Menentukan mode default.

### Low {#Low}
```
public static final int Low
```


Menentukan interpolasi kualitas rendah.

### High {#High}
```
public static final int High
```


Menentukan interpolasi kualitas tinggi.

### Bilinear {#Bilinear}
```
public static final int Bilinear
```


Menentukan interpolasi bilinear. Tidak ada pra‑penyaringan yang dilakukan. Mode ini tidak cocok untuk memperkecil gambar di bawah 50 persen dari ukuran aslinya.

### Bicubic {#Bicubic}
```
public static final int Bicubic
```


Menentukan interpolasi bikubik. Tidak ada pra‑penyaringan yang dilakukan. Mode ini tidak cocok untuk memperkecil gambar di bawah 25 persen dari ukuran aslinya.

### NearestNeighbor {#NearestNeighbor}
```
public static final int NearestNeighbor
```


Menentukan interpolasi tetangga terdekat.

### HighQualityBilinear {#HighQualityBilinear}
```
public static final int HighQualityBilinear
```


Menentukan interpolasi bilinear berkualitas tinggi. Pra‑penyaringan dilakukan untuk memastikan pengecilan berkualitas tinggi.

### HighQualityBicubic {#HighQualityBicubic}
```
public static final int HighQualityBicubic
```


Menentukan interpolasi bikubik berkualitas tinggi. Pra‑penyaringan dilakukan untuk memastikan pengecilan berkualitas tinggi. Mode ini menghasilkan gambar yang diubah dengan kualitas tertinggi.

