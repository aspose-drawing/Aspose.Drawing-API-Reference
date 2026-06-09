---
title: PixelFormat
second_title: Referensi API Aspose.Drawing for Java
description: Menentukan format data warna untuk setiap piksel dalam gambar.
type: docs
weight: 34
url: /id/java/com.aspose.drawing.imaging/pixelformat/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PixelFormat extends System.Enum
```

Menentukan format data warna untuk setiap piksel dalam gambar.
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [Indexed](#Indexed) | Data piksel berisi nilai berindeks warna, yang berarti nilai tersebut adalah indeks ke warna dalam tabel warna sistem, bukan nilai warna individual. |
| [Gdi](#Gdi) | Data piksel berisi warna GDI. |
| [Alpha](#Alpha) | Data piksel berisi nilai alfa yang tidak dipra‑kali. |
| [PAlpha](#PAlpha) | Format piksel berisi nilai alfa yang dipra‑kali. |
| [Extended](#Extended) | Nilai yang dicadangkan. |
| [Canonical](#Canonical) | Format piksel default sebesar 32 bit per piksel. |
| [Undefined](#Undefined) | Format piksel tidak terdefinisi. |
| [DontCare](#DontCare) | Tidak ada format piksel yang ditentukan. |
| [Format1bppIndexed](#Format1bppIndexed) | Menentukan bahwa format piksel adalah 1 bit per piksel dan menggunakan warna berindeks. |
| [Format4bppIndexed](#Format4bppIndexed) | Menentukan bahwa formatnya adalah 4 bit per piksel, berindeks. |
| [Format8bppIndexed](#Format8bppIndexed) | Menentukan bahwa formatnya adalah 8 bit per piksel, berindeks. |
| [Format16bppGrayScale](#Format16bppGrayScale) | Format piksel adalah 16 bit per piksel. |
| [Format16bppRgb555](#Format16bppRgb555) | Menentukan bahwa formatnya adalah 16 bit per piksel; masing‑masing 5 bit digunakan untuk komponen merah, hijau, dan biru. |
| [Format16bppRgb565](#Format16bppRgb565) | Menentukan bahwa formatnya adalah 16 bit per piksel; 5 bit digunakan untuk komponen merah, 6 bit digunakan untuk komponen hijau, dan 5 bit digunakan untuk komponen biru. |
| [Format16bppArgb1555](#Format16bppArgb1555) | Format piksel adalah 16 bit per piksel. |
| [Format24bppRgb](#Format24bppRgb) | Menentukan bahwa formatnya adalah 24 bit per piksel; 8 bit masing-masing digunakan untuk komponen merah, hijau, dan biru. |
| [Format32bppRgb](#Format32bppRgb) | Menentukan bahwa formatnya adalah 32 bit per piksel; 8 bit masing-masing digunakan untuk komponen merah, hijau, dan biru. |
| [Format32bppArgb](#Format32bppArgb) | Menentukan bahwa formatnya adalah 32 bit per piksel; 8 bit masing-masing digunakan untuk komponen alfa, merah, hijau, dan biru. |
| [Format32bppPArgb](#Format32bppPArgb) | Menentukan bahwa formatnya adalah 32 bit per piksel; 8 bit masing-masing digunakan untuk komponen alfa, merah, hijau, dan biru. |
| [Format48bppRgb](#Format48bppRgb) | Menentukan bahwa formatnya adalah 48 bit per piksel; 16 bit masing-masing digunakan untuk komponen merah, hijau, dan biru. |
| [Format64bppArgb](#Format64bppArgb) | Menentukan bahwa formatnya adalah 64 bit per piksel; 16 bit masing-masing digunakan untuk komponen alfa, merah, hijau, dan biru. |
| [Format64bppPArgb](#Format64bppPArgb) | Menentukan bahwa formatnya adalah 64 bit per piksel; 16 bit masing-masing digunakan untuk komponen alfa, merah, hijau, dan biru. |
| [Max](#Max) | Nilai maksimum untuk enumerasi ini. |
### Indexed {#Indexed}
```
public static final int Indexed
```


Data piksel berisi nilai berindeks warna, yang berarti nilai tersebut adalah indeks ke warna dalam tabel warna sistem, bukan nilai warna individual.

### Gdi {#Gdi}
```
public static final int Gdi
```


Data piksel berisi warna GDI.

### Alpha {#Alpha}
```
public static final int Alpha
```


Data piksel berisi nilai alfa yang tidak dipra‑kali.

### PAlpha {#PAlpha}
```
public static final int PAlpha
```


Format piksel berisi nilai alfa yang dipra‑kali.

### Extended {#Extended}
```
public static final int Extended
```


Nilai yang dicadangkan.

### Canonical {#Canonical}
```
public static final int Canonical
```


Format piksel default adalah 32 bit per piksel. Format ini menentukan kedalaman warna 24-bit dan saluran alfa 8-bit.

### Undefined {#Undefined}
```
public static final int Undefined
```


Format piksel tidak terdefinisi.

### DontCare {#DontCare}
```
public static final int DontCare
```


Tidak ada format piksel yang ditentukan.

### Format1bppIndexed {#Format1bppIndexed}
```
public static final int Format1bppIndexed
```


Menentukan bahwa format piksel adalah 1 bit per piksel dan menggunakan warna terindeks. Oleh karena itu tabel warna memiliki dua warna.

### Format4bppIndexed {#Format4bppIndexed}
```
public static final int Format4bppIndexed
```


Menentukan bahwa formatnya adalah 4 bit per piksel, berindeks.

### Format8bppIndexed {#Format8bppIndexed}
```
public static final int Format8bppIndexed
```


Menentukan bahwa formatnya adalah 8 bit per piksel, terindeks. Oleh karena itu tabel warna memiliki 256 warna.

### Format16bppGrayScale {#Format16bppGrayScale}
```
public static final int Format16bppGrayScale
```


Format piksel adalah 16 bit per piksel. Informasi warna menentukan 65536 nuansa abu-abu.

### Format16bppRgb555 {#Format16bppRgb555}
```
public static final int Format16bppRgb555
```


Menentukan bahwa formatnya adalah 16 bit per piksel; 5 bit masing-masing digunakan untuk komponen merah, hijau, dan biru. Bit yang tersisa tidak digunakan.

### Format16bppRgb565 {#Format16bppRgb565}
```
public static final int Format16bppRgb565
```


Menentukan bahwa formatnya adalah 16 bit per piksel; 5 bit digunakan untuk komponen merah, 6 bit digunakan untuk komponen hijau, dan 5 bit digunakan untuk komponen biru.

### Format16bppArgb1555 {#Format16bppArgb1555}
```
public static final int Format16bppArgb1555
```


Format piksel adalah 16 bit per piksel. Informasi warna menentukan 32768 nuansa warna, di mana 5 bit untuk merah, 5 bit untuk hijau, 5 bit untuk biru, dan 1 bit untuk alfa.

### Format24bppRgb {#Format24bppRgb}
```
public static final int Format24bppRgb
```


Menentukan bahwa formatnya adalah 24 bit per piksel; 8 bit masing-masing digunakan untuk komponen merah, hijau, dan biru.

### Format32bppRgb {#Format32bppRgb}
```
public static final int Format32bppRgb
```


Menentukan bahwa formatnya adalah 32 bit per piksel; 8 bit masing-masing digunakan untuk komponen merah, hijau, dan biru. 8 bit yang tersisa tidak digunakan.

### Format32bppArgb {#Format32bppArgb}
```
public static final int Format32bppArgb
```


Menentukan bahwa formatnya adalah 32 bit per piksel; 8 bit masing-masing digunakan untuk komponen alfa, merah, hijau, dan biru.

### Format32bppPArgb {#Format32bppPArgb}
```
public static final int Format32bppPArgb
```


Menentukan bahwa formatnya adalah 32 bit per piksel; 8 bit masing-masing digunakan untuk komponen alfa, merah, hijau, dan biru. Komponen merah, hijau, dan biru dipremultiplikasi menurut komponen alfa.

### Format48bppRgb {#Format48bppRgb}
```
public static final int Format48bppRgb
```


Menentukan bahwa formatnya adalah 48 bit per piksel; 16 bit masing-masing digunakan untuk komponen merah, hijau, dan biru.

### Format64bppArgb {#Format64bppArgb}
```
public static final int Format64bppArgb
```


Menentukan bahwa formatnya adalah 64 bit per piksel; 16 bit masing-masing digunakan untuk komponen alfa, merah, hijau, dan biru.

### Format64bppPArgb {#Format64bppPArgb}
```
public static final int Format64bppPArgb
```


Menentukan bahwa formatnya adalah 64 bit per piksel; 16 bit masing-masing digunakan untuk komponen alfa, merah, hijau, dan biru. Komponen merah, hijau, dan biru dipremultiplikasi menurut komponen alfa.

### Max {#Max}
```
public static final int Max
```


Nilai maksimum untuk enumerasi ini.

