---
title: MetafileType
second_title: Referensi API Aspose.Drawing for Java
description: Menentukan jenis-jenis metafile.
type: docs
weight: 33
url: /id/java/com.aspose.drawing.imaging/metafiletype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class MetafileType extends System.Enum
```

Menentukan jenis-jenis metafile.
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [Invalid](#Invalid) | Menentukan format metafile yang tidak dikenali dalam GDI+. |
| [Wmf](#Wmf) | Menentukan file WMF (Windows Metafile). |
| [WmfPlaceable](#WmfPlaceable) | Menentukan file WMF (Windows Metafile) yang memiliki header metafile yang dapat diposisikan di depannya. |
| [Emf](#Emf) | Menentukan file Enhanced Metafile (EMF). |
| [EmfPlusOnly](#EmfPlusOnly) | Menentukan file EMF+. |
| [EmfPlusDual](#EmfPlusDual) | Menentukan file EMF+ Dual. |
### Invalid {#Invalid}
```
public static final int Invalid
```


Menentukan format metafile yang tidak dikenali dalam GDI+.

### Wmf {#Wmf}
```
public static final int Wmf
```


Menentukan file WMF (Windows Metafile). File semacam itu hanya berisi rekaman GDI.

### WmfPlaceable {#WmfPlaceable}
```
public static final int WmfPlaceable
```


Menentukan file WMF (Windows Metafile) yang memiliki header metafile yang dapat diposisikan di depannya.

### Emf {#Emf}
```
public static final int Emf
```


Menentukan file Enhanced Metafile (EMF). File semacam itu hanya berisi rekaman GDI.

### EmfPlusOnly {#EmfPlusOnly}
```
public static final int EmfPlusOnly
```


Menentukan file EMF+. File semacam itu hanya berisi rekaman GDI+ dan harus ditampilkan menggunakan GDI+. Menampilkan rekaman menggunakan GDI dapat menyebabkan hasil yang tidak dapat diprediksi.

### EmfPlusDual {#EmfPlusDual}
```
public static final int EmfPlusDual
```


Menentukan file EMF+ Dual. File semacam itu berisi rekaman GDI+ bersama dengan rekaman GDI alternatif dan dapat ditampilkan menggunakan GDI atau GDI+. Menampilkan rekaman menggunakan GDI dapat menyebabkan penurunan kualitas tertentu.

