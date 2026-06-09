---
title: LineJoin
second_title: Referensi API Aspose.Drawing for Java
description: Menentukan cara menggabungkan segmen garis atau kurva berurutan dalam subpath gambar yang terdapat dalam objek GraphicsPath.
type: docs
weight: 30
url: /id/java/com.aspose.drawing.drawing2d/linejoin/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class LineJoin extends System.Enum
```

Menentukan cara menggabungkan segmen garis atau kurva berurutan dalam sebuah gambar (subpath) yang terdapat dalam objek GraphicsPath.
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [Miter](#Miter) | Menentukan sambungan miter. |
| [Bevel](#Bevel) | Menentukan sambungan bevel. |
| [Round](#Round) | Menentukan sambungan melingkar. |
| [MiterClipped](#MiterClipped) | Menentukan sambungan miter. |
### Miter {#Miter}
```
public static final int Miter
```


Menentukan sambungan miter. Ini menghasilkan sudut tajam atau sudut terpotong, tergantung apakah panjang miter melebihi batas miter.

--------------------

Saat ini sambungan Miter sebenarnya berfungsi sebagai MiterClipped.

### Bevel {#Bevel}
```
public static final int Bevel
```


Menentukan sambungan bevel. Ini menghasilkan sudut diagonal.

### Round {#Round}
```
public static final int Round
```


Menentukan sambungan melingkar. Ini menghasilkan busur melingkar yang halus di antara garis-garis.

### MiterClipped {#MiterClipped}
```
public static final int MiterClipped
```


Menentukan sambungan miter. Ini menghasilkan sudut tajam atau sudut bevel, tergantung apakah panjang miter melebihi batas miter.

