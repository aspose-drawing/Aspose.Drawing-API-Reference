---
title: StringFormatFlags
second_title: Referensi API Aspose.Drawing for Java
description: Menentukan informasi tampilan dan tata letak untuk string teks.
type: docs
weight: 48
url: /id/java/com.aspose.drawing/stringformatflags/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class StringFormatFlags extends System.Enum
```

Menentukan informasi tampilan dan tata letak untuk string teks.
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [DirectionRightToLeft](#DirectionRightToLeft) | Teks ditampilkan dari kanan ke kiri. |
| [DirectionVertical](#DirectionVertical) | Teks disejajarkan secara vertikal. |
| [FitBlackBox](#FitBlackBox) | Bagian-bagian karakter diizinkan melampaui persegi panjang tata letak string. |
| [DisplayFormatControl](#DisplayFormatControl) | Karakter kontrol seperti tanda kiri-ke-kanan ditampilkan dalam output dengan glif representatif. |
| [NoFontFallback](#NoFontFallback) | Cadangan ke font alternatif untuk karakter yang tidak didukung dalam font yang diminta dinonaktifkan. |
| [MeasureTrailingSpaces](#MeasureTrailingSpaces) | Menyertakan spasi akhir di akhir setiap baris. |
| [NoWrap](#NoWrap) | Pembungkus teks antar baris saat memformat dalam persegi panjang dinonaktifkan. |
| [LineLimit](#LineLimit) | Hanya baris lengkap yang ditata dalam persegi panjang pemformatan. |
| [NoClip](#NoClip) | Bagian glyph yang melampaui, dan teks yang tidak dibungkus yang mencapai luar persegi panjang pemformatan diizinkan untuk ditampilkan. |
| [ExactAlignment](#ExactAlignment) | Penyelarasan yang tepat, padding yang benar GDI+ |
### DirectionRightToLeft {#DirectionRightToLeft}
```
public static final int DirectionRightToLeft
```


Teks ditampilkan dari kanan ke kiri.

### DirectionVertical {#DirectionVertical}
```
public static final int DirectionVertical
```


Teks disejajarkan secara vertikal.

### FitBlackBox {#FitBlackBox}
```
public static final int FitBlackBox
```


Bagian-bagian karakter diizinkan melampaui persegi panjang tata letak string. Secara default, karakter diposisikan ulang untuk menghindari melampaui.

### DisplayFormatControl {#DisplayFormatControl}
```
public static final int DisplayFormatControl
```


Karakter kontrol seperti tanda kiri-ke-kanan ditampilkan dalam output dengan glif representatif.

### NoFontFallback {#NoFontFallback}
```
public static final int NoFontFallback
```


Cadangan ke font alternatif untuk karakter yang tidak didukung dalam font yang diminta dinonaktifkan. Setiap karakter yang hilang ditampilkan dengan glif font yang hilang, biasanya berupa kotak terbuka.

### MeasureTrailingSpaces {#MeasureTrailingSpaces}
```
public static final int MeasureTrailingSpaces
```


Menyertakan spasi akhir di akhir setiap baris. Secara default, persegi panjang batas yang dikembalikan oleh metode MeasureString tidak menyertakan spasi di akhir setiap baris. Atur flag ini untuk menyertakan spasi tersebut dalam pengukuran.

### NoWrap {#NoWrap}
```
public static final int NoWrap
```


Pembungkus teks antar baris saat memformat dalam persegi panjang dinonaktifkan. Flag ini diasumsikan ketika sebuah titik diberikan alih-alih persegi panjang, atau ketika persegi panjang yang ditentukan memiliki panjang baris nol.

### LineLimit {#LineLimit}
```
public static final int LineLimit
```


Hanya baris lengkap yang ditempatkan dalam persegi format. Secara default tata letak berlanjut hingga akhir teks, atau hingga tidak ada lagi baris yang terlihat sebagai hasil pemotongan, mana yang terjadi lebih dulu. Perhatikan bahwa pengaturan default memungkinkan baris terakhir sebagian tertutup oleh persegi format yang bukan kelipatan penuh dari tinggi baris. Untuk memastikan hanya baris penuh yang terlihat, tentukan nilai ini dan hati-hati menyediakan persegi format setidaknya setinggi tinggi satu baris.

### NoClip {#NoClip}
```
public static final int NoClip
```


Bagian glyph yang menjorok keluar, dan teks yang tidak terbungkus yang mencapai di luar persegi format diizinkan untuk ditampilkan. Secara default semua teks dan bagian glyph yang mencapai di luar persegi format dipotong.

### ExactAlignment {#ExactAlignment}
```
public static final int ExactAlignment
```


Penyelarasan yang tepat, padding yang benar GDI+

