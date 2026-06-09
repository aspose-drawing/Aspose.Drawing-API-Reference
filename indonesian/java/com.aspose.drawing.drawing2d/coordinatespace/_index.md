---
title: CoordinateSpace
second_title: Referensi API Aspose.Drawing for Java
description: Menentukan sistem yang digunakan saat mengevaluasi koordinat.
type: docs
weight: 16
url: /id/java/com.aspose.drawing.drawing2d/coordinatespace/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class CoordinateSpace extends System.Enum
```

Menentukan sistem yang digunakan saat mengevaluasi koordinat.
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [World](#World) | Menentukan bahwa koordinat berada dalam konteks koordinat dunia. |
| [Page](#Page) | Menentukan bahwa koordinat berada dalam konteks koordinat halaman. |
| [Device](#Device) | Menentukan bahwa koordinat berada dalam konteks koordinat perangkat. |
### World {#World}
```
public static final int World
```


Menentukan bahwa koordinat berada dalam konteks koordinat dunia. Koordinat dunia digunakan dalam lingkungan nonfisik, seperti lingkungan pemodelan.

### Page {#Page}
```
public static final int Page
```


Menentukan bahwa koordinat berada dalam konteks koordinat halaman. Unitnya didefinisikan oleh properti Graphics.PageUnit, dan harus salah satu elemen dari enumerasi GraphicsUnit.

### Device {#Device}
```
public static final int Device
```


Menentukan bahwa koordinat berada dalam konteks koordinat perangkat. Pada layar komputer, koordinat perangkat biasanya diukur dalam piksel.

