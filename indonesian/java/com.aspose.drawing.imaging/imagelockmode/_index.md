---
title: ImageLockMode
second_title: Referensi API Aspose.Drawing for Java
description: Menentukan flag yang diteruskan ke parameter flags dari metode.
type: docs
weight: 28
url: /id/java/com.aspose.drawing.imaging/imagelockmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ImageLockMode extends System.Enum
```

Menentukan flag yang diteruskan ke parameter flags dari metode [Bitmap.lockBits(Rectangle, int, int)](../../com.aspose.drawing/bitmap\#lockBits-Rectangle--int--int-). Metode [Bitmap.lockBits(Rectangle, int, int)](../../com.aspose.drawing/bitmap\#lockBits-Rectangle--int--int-) mengunci sebagian gambar sehingga Anda dapat membaca atau menulis data piksel.
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [ReadOnly](#ReadOnly) | Menentukan bahwa sebagian gambar dikunci untuk pembacaan. |
| [WriteOnly](#WriteOnly) | Menentukan bahwa sebagian gambar dikunci untuk penulisan. |
| [ReadWrite](#ReadWrite) | Menentukan bahwa sebagian gambar dikunci untuk pembacaan atau penulisan. |
| [UserInputBuffer](#UserInputBuffer) | Menentukan bahwa buffer yang digunakan untuk membaca atau menulis data piksel dialokasikan oleh pengguna. |
### ReadOnly {#ReadOnly}
```
public static final int ReadOnly
```


Menentukan bahwa sebagian gambar dikunci untuk pembacaan.

### WriteOnly {#WriteOnly}
```
public static final int WriteOnly
```


Menentukan bahwa sebagian gambar dikunci untuk penulisan.

### ReadWrite {#ReadWrite}
```
public static final int ReadWrite
```


Menentukan bahwa sebagian gambar dikunci untuk pembacaan atau penulisan.

### UserInputBuffer {#UserInputBuffer}
```
public static final int UserInputBuffer
```


Menentukan bahwa buffer yang digunakan untuk membaca atau menulis data piksel dialokasikan oleh pengguna. Jika flag ini diatur, parameter `flags` dari metode [Bitmap.lockBits(Rectangle, int, int)](../../com.aspose.drawing/bitmap\#lockBits-Rectangle--int--int-) berfungsi sebagai parameter input (dan mungkin juga sebagai parameter output). Jika flag ini dibersihkan, maka parameter `flags` hanya berfungsi sebagai parameter output.

