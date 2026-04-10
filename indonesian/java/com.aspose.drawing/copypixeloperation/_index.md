---
title: CopyPixelOperation
second_title: Referensi API Aspose.Drawing for Java
description: Menentukan bagaimana warna sumber dalam operasi menyalin piksel digabungkan dengan warna tujuan untuk menghasilkan warna akhir.
type: docs
weight: 18
url: /id/java/com.aspose.drawing/copypixeloperation/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class CopyPixelOperation extends System.Enum
```

Menentukan bagaimana warna sumber dalam operasi menyalin piksel digabungkan dengan warna tujuan untuk menghasilkan warna akhir.
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [NoMirrorBitmap](#NoMirrorBitmap) | Bitmap tidak dicerminkan. |
| [Blackness](#Blackness) | Area tujuan diisi dengan menggunakan warna yang terkait dengan indeks 0 dalam palet fisik. |
| [NotSourceErase](#NotSourceErase) | Warna sumber dan tujuan digabungkan menggunakan operator Boolean `OR`, dan kemudian warna hasilnya dibalik. |
| [NotSourceCopy](#NotSourceCopy) | Area sumber yang dibalik disalin ke tujuan. |
| [SourceErase](#SourceErase) | Warna terbalik dari area tujuan digabungkan dengan warna area sumber menggunakan operator Boolean `AND`. |
| [DestinationInvert](#DestinationInvert) | Area tujuan dibalik. |
| [PatInvert](#PatInvert) | Warna kuas yang saat ini dipilih dalam konteks perangkat tujuan digabungkan dengan warna tujuan menggunakan operator Boolean `XOR`. |
| [SourceInvert](#SourceInvert) | Warna area sumber dan tujuan digabungkan menggunakan operator Boolean `XOR`. |
| [SourceAnd](#SourceAnd) | Warna area sumber dan tujuan digabungkan menggunakan operator Boolean `AND`. |
| [MergePaint](#MergePaint) | Warna area sumber yang dibalik digabungkan dengan warna area tujuan menggunakan operator Boolean `OR`. |
| [MergeCopy](#MergeCopy) | Warna area sumber digabungkan dengan warna kuas yang dipilih dalam konteks perangkat tujuan menggunakan operator Boolean `AND`. |
| [SourceCopy](#SourceCopy) | Area sumber disalin langsung ke area tujuan. |
| [SourcePaint](#SourcePaint) | Warna area sumber dan tujuan digabungkan menggunakan operator Boolean `OR`. |
| [PatCopy](#PatCopy) | Kuas yang saat ini dipilih dalam konteks perangkat tujuan disalin ke bitmap tujuan. |
| [PatPaint](#PatPaint) | Warna kuas yang saat ini dipilih dalam konteks perangkat tujuan digabungkan dengan warna area sumber yang dibalik menggunakan operator Boolean `OR`. |
| [Whiteness](#Whiteness) | Area tujuan diisi dengan menggunakan warna yang terkait dengan indeks 1 dalam palet fisik. |
| [CaptureBlt](#CaptureBlt) | Jendela yang dilapisi di atas jendela Anda termasuk dalam gambar hasil. |
### NoMirrorBitmap {#NoMirrorBitmap}
```
public static final int NoMirrorBitmap
```


Bitmap tidak dicerminkan.

### Blackness {#Blackness}
```
public static final int Blackness
```


Area tujuan diisi dengan menggunakan warna yang terkait dengan indeks 0 dalam palet fisik. (Warna ini adalah hitam untuk palet fisik default.)

### NotSourceErase {#NotSourceErase}
```
public static final int NotSourceErase
```


Warna sumber dan tujuan digabungkan menggunakan operator Boolean `OR`, dan kemudian warna hasilnya dibalik.

### NotSourceCopy {#NotSourceCopy}
```
public static final int NotSourceCopy
```


Area sumber yang dibalik disalin ke tujuan.

### SourceErase {#SourceErase}
```
public static final int SourceErase
```


Warna terbalik dari area tujuan digabungkan dengan warna area sumber menggunakan operator Boolean `AND`.

### DestinationInvert {#DestinationInvert}
```
public static final int DestinationInvert
```


Area tujuan dibalik.

### PatInvert {#PatInvert}
```
public static final int PatInvert
```


Warna kuas yang saat ini dipilih dalam konteks perangkat tujuan digabungkan dengan warna tujuan menggunakan operator Boolean `XOR`.

### SourceInvert {#SourceInvert}
```
public static final int SourceInvert
```


Warna area sumber dan tujuan digabungkan menggunakan operator Boolean `XOR`.

### SourceAnd {#SourceAnd}
```
public static final int SourceAnd
```


Warna area sumber dan tujuan digabungkan menggunakan operator Boolean `AND`.

### MergePaint {#MergePaint}
```
public static final int MergePaint
```


Warna area sumber yang dibalik digabungkan dengan warna area tujuan menggunakan operator Boolean `OR`.

### MergeCopy {#MergeCopy}
```
public static final int MergeCopy
```


Warna area sumber digabungkan dengan warna kuas yang dipilih dalam konteks perangkat tujuan menggunakan operator Boolean `AND`.

### SourceCopy {#SourceCopy}
```
public static final int SourceCopy
```


Area sumber disalin langsung ke area tujuan.

### SourcePaint {#SourcePaint}
```
public static final int SourcePaint
```


Warna area sumber dan tujuan digabungkan menggunakan operator Boolean `OR`.

### PatCopy {#PatCopy}
```
public static final int PatCopy
```


Kuas yang saat ini dipilih dalam konteks perangkat tujuan disalin ke bitmap tujuan.

### PatPaint {#PatPaint}
```
public static final int PatPaint
```


Warna kuas yang saat ini dipilih dalam konteks perangkat tujuan digabungkan dengan warna area sumber yang terbalik menggunakan operator Boolean `OR`. Hasil operasi ini digabungkan dengan warna area tujuan menggunakan operator Boolean `OR`.

### Whiteness {#Whiteness}
```
public static final int Whiteness
```


Area tujuan diisi dengan menggunakan warna yang terkait dengan indeks 1 dalam palet fisik. (Warna ini berwarna putih untuk palet fisik default.)

### CaptureBlt {#CaptureBlt}
```
public static final int CaptureBlt
```


Jendela yang ditumpuk di atas jendela Anda termasuk dalam gambar yang dihasilkan. Secara default, gambar hanya berisi jendela Anda. Perhatikan bahwa ini umumnya tidak dapat digunakan untuk konteks perangkat pencetakan.

