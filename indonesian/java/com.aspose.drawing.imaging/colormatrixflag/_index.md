---
title: ColorMatrixFlag
second_title: Referensi API Aspose.Drawing for Java
description: Menentukan jenis gambar dan warna yang akan dipengaruhi oleh pengaturan penyesuaian warna dan skala abu-abu dari sebuah .
type: docs
weight: 15
url: /id/java/com.aspose.drawing.imaging/colormatrixflag/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ColorMatrixFlag extends System.Enum
```

Menentukan jenis gambar dan warna yang akan dipengaruhi oleh pengaturan penyesuaian warna dan skala abu-abu dari sebuah [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes).
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [Default](#Default) | Semua nilai warna, termasuk nuansa abu-abu, disesuaikan oleh matriks penyesuaian warna yang sama. |
| [SkipGrays](#SkipGrays) | Semua warna disesuaikan, tetapi nuansa abu-abu tidak disesuaikan. |
| [AltGrays](#AltGrays) | Hanya nuansa abu-abu yang disesuaikan. |
### Default {#Default}
```
public static final int Default
```


Semua nilai warna, termasuk nuansa abu-abu, disesuaikan oleh matriks penyesuaian warna yang sama.

### SkipGrays {#SkipGrays}
```
public static final int SkipGrays
```


Semua warna disesuaikan, tetapi nuansa abu-abu tidak disesuaikan. Nuansa abu-abu adalah warna apa pun yang memiliki nilai yang sama untuk komponen merah, hijau, dan birunya.

### AltGrays {#AltGrays}
```
public static final int AltGrays
```


Hanya nuansa abu-abu yang disesuaikan.

