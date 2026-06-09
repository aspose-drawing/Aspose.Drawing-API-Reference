---
title: TextRenderingHint
second_title: Referensi API Aspose.Drawing for Java
description: Menentukan kualitas rendering teks.
type: docs
weight: 14
url: /id/java/com.aspose.drawing.text/textrenderinghint/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class TextRenderingHint extends System.Enum
```

Menentukan kualitas rendering teks.
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [SystemDefault](#SystemDefault) | Setiap karakter digambar menggunakan bitmap glifnya, dengan petunjuk rendering default sistem. |
| [SingleBitPerPixelGridFit](#SingleBitPerPixelGridFit) | Setiap karakter digambar menggunakan bitmap glifnya. |
| [SingleBitPerPixel](#SingleBitPerPixel) | Setiap karakter digambar menggunakan bitmap glifnya. |
| [AntiAliasGridFit](#AntiAliasGridFit) | Setiap karakter digambar menggunakan bitmap glif anti-aliased dengan hinting. |
| [AntiAlias](#AntiAlias) | Setiap karakter digambar menggunakan bitmap glif anti-aliased tanpa hinting. |
| [ClearTypeGridFit](#ClearTypeGridFit) | Setiap karakter digambar menggunakan bitmap glif ClearType dengan hinting. |
### SystemDefault {#SystemDefault}
```
public static final int SystemDefault
```


Setiap karakter digambar menggunakan bitmap glifnya, dengan petunjuk rendering default sistem. Teks akan digambar menggunakan pengaturan penyamaran font apa pun yang dipilih pengguna untuk sistem.

### SingleBitPerPixelGridFit {#SingleBitPerPixelGridFit}
```
public static final int SingleBitPerPixelGridFit
```


Setiap karakter digambar menggunakan bitmap glifnya. Hinting digunakan untuk meningkatkan tampilan karakter pada batang dan kelengkungan.

### SingleBitPerPixel {#SingleBitPerPixel}
```
public static final int SingleBitPerPixel
```


Setiap karakter digambar menggunakan bitmap glifnya. Hinting tidak digunakan.

### AntiAliasGridFit {#AntiAliasGridFit}
```
public static final int AntiAliasGridFit
```


Setiap karakter digambar menggunakan bitmap glif anti-aliased dengan hinting. Kualitas jauh lebih baik karena anti-aliasing, tetapi dengan biaya kinerja yang lebih tinggi.

### AntiAlias {#AntiAlias}
```
public static final int AntiAlias
```


Setiap karakter digambar menggunakan bitmap glif anti-aliased tanpa hinting. Kualitas lebih baik karena anti-aliasing. Perbedaan lebar batang dapat terlihat karena hinting dimatikan.

### ClearTypeGridFit {#ClearTypeGridFit}
```
public static final int ClearTypeGridFit
```


Setiap karakter digambar menggunakan bitmap glif ClearType dengan hinting. Pengaturan kualitas tertinggi. Digunakan untuk memanfaatkan fitur font ClearType.

