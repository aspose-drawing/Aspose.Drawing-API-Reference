---
title: StringFormat
second_title: Referensi API Aspose.Drawing for Java
description: Mengkapsulkan informasi tata letak teks seperti orientasi perataan dan manipulasi tampilan tab stop seperti penyisipan elipsis, substitusi digit nasional, dan fitur OpenType.
type: docs
weight: 47
url: /id/java/com.aspose.drawing/stringformat/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public final class StringFormat implements System.IDisposable
```

Menyatukan informasi tata letak teks (seperti perataan, orientasi, dan tab stop) manipulasi tampilan (seperti penyisipan elipsis dan substitusi digit nasional) serta fitur OpenType. Kelas ini tidak dapat diwarisi.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [StringFormat()](#StringFormat--) | Menginisialisasi sebuah instance baru dari kelas [StringFormat](../../com.aspose.drawing/stringformat). |
| [StringFormat(StringFormat format)](#StringFormat-com.aspose.drawing.StringFormat-) | Menginisialisasi sebuah instance baru dari kelas [StringFormat](../../com.aspose.drawing/stringformat) berdasarkan objek [StringFormat](../../com.aspose.drawing/stringformat) yang ada yang ditentukan. |
| [StringFormat(int options, int language)](#StringFormat-int-int-) | Menginisialisasi sebuah instance baru dari kelas [StringFormat](../../com.aspose.drawing/stringformat) dengan enumerasi [StringFormatFlags](../../com.aspose.drawing/stringformatflags) dan bahasa yang ditentukan. |
| [StringFormat(int options)](#StringFormat-int-) | Menginisialisasi sebuah instance baru dari kelas [StringFormat](../../com.aspose.drawing/stringformat) dengan enumerasi [StringFormatFlags](../../com.aspose.drawing/stringformatflags) yang ditentukan. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [setDigitSubstitutionLanguage(int value)](#setDigitSubstitutionLanguage-int-) |  |
| [setDigitSubstitutionMethod(int value)](#setDigitSubstitutionMethod-int-) |  |
| [getFirstTabOffset()](#getFirstTabOffset--) |  |
| [getGenericDefault()](#getGenericDefault--) | Mendapatkan objek [StringFormat](../../com.aspose.drawing/stringformat) default generik. |
| [getGenericTypographic()](#getGenericTypographic--) | Mendapatkan objek [StringFormat](../../com.aspose.drawing/stringformat) tipografi generik. |
| [getFormatFlags()](#getFormatFlags--) | Mendapatkan atau mengatur enumerasi [StringFormatFlags](../../com.aspose.drawing/stringformatflags) yang berisi informasi pemformatan. |
| [setFormatFlags(int value)](#setFormatFlags-int-) | Mendapatkan atau mengatur enumerasi [StringFormatFlags](../../com.aspose.drawing/stringformatflags) yang berisi informasi pemformatan. |
| [getAlignment()](#getAlignment--) | Mendapatkan atau mengatur informasi perataan teks pada bidang vertikal. |
| [setAlignment(int value)](#setAlignment-int-) | Mendapatkan atau mengatur informasi perataan teks pada bidang vertikal. |
| [getLineAlignment()](#getLineAlignment--) | Mendapatkan atau mengatur perataan baris pada bidang horizontal. |
| [setLineAlignment(int value)](#setLineAlignment-int-) | Mendapatkan atau mengatur perataan baris pada bidang horizontal. |
| [getHotkeyPrefix()](#getHotkeyPrefix--) | Mendapatkan atau mengatur objek `HotkeyPrefix`([.getHotkeyPrefix](../../null/\#getHotkeyPrefix)/[.setHotkeyPrefix(int)](../../null/\#setHotkeyPrefix-int-)) untuk objek [StringFormat](../../com.aspose.drawing/stringformat) ini. |
| [setHotkeyPrefix(int value)](#setHotkeyPrefix-int-) | Mendapatkan atau mengatur objek `HotkeyPrefix`([.getHotkeyPrefix](../../null/\#getHotkeyPrefix)/[.setHotkeyPrefix(int)](../../null/\#setHotkeyPrefix-int-)) untuk objek [StringFormat](../../com.aspose.drawing/stringformat) ini. |
| [getTrimming()](#getTrimming--) | Mendapatkan atau mengatur enumerasi [StringTrimming](../../com.aspose.drawing/stringtrimming) untuk objek [StringFormat](../../com.aspose.drawing/stringformat) ini. |
| [setTrimming(int value)](#setTrimming-int-) | Mendapatkan atau mengatur enumerasi [StringTrimming](../../com.aspose.drawing/stringtrimming) untuk objek [StringFormat](../../com.aspose.drawing/stringformat) ini. |
| [getDigitSubstitutionLanguage()](#getDigitSubstitutionLanguage--) | Mendapatkan bahasa yang digunakan ketika digit lokal digantikan dengan digit barat. |
| [getDigitSubstitutionMethod()](#getDigitSubstitutionMethod--) | Mendapatkan metode yang akan digunakan untuk substitusi digit. |
| [dispose()](#dispose--) | Melepaskan semua sumber daya yang digunakan oleh objek [StringFormat](../../com.aspose.drawing/stringformat) ini. |
| [deepClone()](#deepClone--) | Membuat salinan persis dari objek [StringFormat](../../com.aspose.drawing/stringformat) ini. |
| [getTabStops(float[] firstTabOffset)](#getTabStops-float---) | Mendapatkan tab stop untuk objek [StringFormat](../../com.aspose.drawing/stringformat) ini. |
| [getTabStops()](#getTabStops--) | Mendapatkan array jarak antar tab stop dalam satuan yang ditentukan oleh properti `Aspose.Imaging.getGraphics().PageUnit`. |
| [setTabStops(float firstTabOffset, float[] tabStops)](#setTabStops-float-float---) | Mengatur tab stop untuk objek [StringFormat](../../com.aspose.drawing/stringformat) ini. |
| [setDigitSubstitution(int language, int substitute)](#setDigitSubstitution-int-int-) | Menentukan bahasa dan metode yang akan digunakan ketika digit lokal digantikan dengan digit barat. |
| [setMeasurableCharacterRanges(CharacterRange[] ranges)](#setMeasurableCharacterRanges-com.aspose.drawing.CharacterRange---) | Menentukan array struktur [CharacterRange](../../com.aspose.drawing/characterrange) yang mewakili rentang karakter yang diukur oleh pemanggilan metode `MeasureCharacterRanges`. |
### StringFormat() {#StringFormat--}
```
public StringFormat()
```


Menginisialisasi sebuah instance baru dari kelas [StringFormat](../../com.aspose.drawing/stringformat).

### StringFormat(StringFormat format) {#StringFormat-com.aspose.drawing.StringFormat-}
```
public StringFormat(StringFormat format)
```


Menginisialisasi sebuah instance baru dari kelas [StringFormat](../../com.aspose.drawing/stringformat) berdasarkan objek [StringFormat](../../com.aspose.drawing/stringformat) yang ada yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| format | [StringFormat](../../com.aspose.drawing/stringformat) | Objek [StringFormat](../../com.aspose.drawing/stringformat) yang akan digunakan untuk menginisialisasi objek [StringFormat](../../com.aspose.drawing/stringformat) yang baru. |

### StringFormat(int options, int language) {#StringFormat-int-int-}
```
public StringFormat(int options, int language)
```


Menginisialisasi sebuah instance baru dari kelas [StringFormat](../../com.aspose.drawing/stringformat) dengan enumerasi [StringFormatFlags](../../com.aspose.drawing/stringformatflags) dan bahasa yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| options | int | Enumerasi [StringFormatFlags](../../com.aspose.drawing/stringformatflags) untuk objek [StringFormat](../../com.aspose.drawing/stringformat) yang baru. |
| bahasa | int | Nilai yang menunjukkan bahasa teks. |

### StringFormat(int options) {#StringFormat-int-}
```
public StringFormat(int options)
```


Menginisialisasi sebuah instance baru dari kelas [StringFormat](../../com.aspose.drawing/stringformat) dengan enumerasi [StringFormatFlags](../../com.aspose.drawing/stringformatflags) yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| options | int | Enumerasi [StringFormatFlags](../../com.aspose.drawing/stringformatflags) untuk objek [StringFormat](../../com.aspose.drawing/stringformat) yang baru. |

### setDigitSubstitutionLanguage(int value) {#setDigitSubstitutionLanguage-int-}
```
public void setDigitSubstitutionLanguage(int value)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### setDigitSubstitutionMethod(int value) {#setDigitSubstitutionMethod-int-}
```
public void setDigitSubstitutionMethod(int value)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getFirstTabOffset() {#getFirstTabOffset--}
```
public float getFirstTabOffset()
```




**Returns:**
float
### getGenericDefault() {#getGenericDefault--}
```
public static StringFormat getGenericDefault()
```


Mendapatkan objek [StringFormat](../../com.aspose.drawing/stringformat) default generik.

**Returns:**
[StringFormat](../../com.aspose.drawing/stringformat)
### getGenericTypographic() {#getGenericTypographic--}
```
public static StringFormat getGenericTypographic()
```


Mendapatkan objek [StringFormat](../../com.aspose.drawing/stringformat) tipografi generik.

**Returns:**
[StringFormat](../../com.aspose.drawing/stringformat) - A generic typographic [StringFormat](../../com.aspose.drawing/stringformat) object.
### getFormatFlags() {#getFormatFlags--}
```
public int getFormatFlags()
```


Mendapatkan atau mengatur enumerasi [StringFormatFlags](../../com.aspose.drawing/stringformatflags) yang berisi informasi pemformatan.

**Returns:**
int
### setFormatFlags(int value) {#setFormatFlags-int-}
```
public void setFormatFlags(int value)
```


Mendapatkan atau mengatur enumerasi [StringFormatFlags](../../com.aspose.drawing/stringformatflags) yang berisi informasi pemformatan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getAlignment() {#getAlignment--}
```
public int getAlignment()
```


Mendapatkan atau mengatur informasi perataan teks pada bidang vertikal.

**Returns:**
int
### setAlignment(int value) {#setAlignment-int-}
```
public void setAlignment(int value)
```


Mendapatkan atau mengatur informasi perataan teks pada bidang vertikal.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getLineAlignment() {#getLineAlignment--}
```
public int getLineAlignment()
```


Mendapatkan atau mengatur perataan baris pada bidang horizontal.

**Returns:**
int
### setLineAlignment(int value) {#setLineAlignment-int-}
```
public void setLineAlignment(int value)
```


Mendapatkan atau mengatur perataan baris pada bidang horizontal.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getHotkeyPrefix() {#getHotkeyPrefix--}
```
public int getHotkeyPrefix()
```


Mendapatkan atau mengatur objek `HotkeyPrefix`([.getHotkeyPrefix](../../null/\#getHotkeyPrefix)/[.setHotkeyPrefix(int)](../../null/\#setHotkeyPrefix-int-)) untuk objek [StringFormat](../../com.aspose.drawing/stringformat) ini.

**Returns:**
int
### setHotkeyPrefix(int value) {#setHotkeyPrefix-int-}
```
public void setHotkeyPrefix(int value)
```


Mendapatkan atau mengatur objek `HotkeyPrefix`([.getHotkeyPrefix](../../null/\#getHotkeyPrefix)/[.setHotkeyPrefix(int)](../../null/\#setHotkeyPrefix-int-)) untuk objek [StringFormat](../../com.aspose.drawing/stringformat) ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getTrimming() {#getTrimming--}
```
public int getTrimming()
```


Mendapatkan atau mengatur enumerasi [StringTrimming](../../com.aspose.drawing/stringtrimming) untuk objek [StringFormat](../../com.aspose.drawing/stringformat) ini.

**Returns:**
int
### setTrimming(int value) {#setTrimming-int-}
```
public void setTrimming(int value)
```


Mendapatkan atau mengatur enumerasi [StringTrimming](../../com.aspose.drawing/stringtrimming) untuk objek [StringFormat](../../com.aspose.drawing/stringformat) ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getDigitSubstitutionLanguage() {#getDigitSubstitutionLanguage--}
```
public int getDigitSubstitutionLanguage()
```


Mendapatkan bahasa yang digunakan ketika digit lokal digantikan dengan digit barat.

**Returns:**
int - Sebuah pengidentifikasi bahasa National Language Support (NLS) yang mengidentifikasi bahasa yang akan digunakan ketika digit lokal digantikan dengan digit barat. Anda dapat meneruskan properti `System.Globalization.CultureInfo.LCID` dari objek java.util.Locale sebagai pengidentifikasi bahasa NLS. Misalnya, anggap Anda membuat objek java.util.Locale dengan memberikan string "ar-EG" ke konstruktor java.util.Locale. Jika Anda meneruskan properti `System.Globalization.CultureInfo.LCID` dari objek java.util.Locale tersebut bersama.`StringDigitSubstitute.Traditional` ke metode [.setDigitSubstitution(int,int)](../../null/\#setDigitSubstitution-int-int-), maka digit Arab-Indic akan digantikan dengan digit barat pada saat tampilan.
### getDigitSubstitutionMethod() {#getDigitSubstitutionMethod--}
```
public int getDigitSubstitutionMethod()
```


Mendapatkan metode yang akan digunakan untuk substitusi digit.

**Returns:**
int - Sebuah nilai enumerasi [StringDigitSubstitute](../../com.aspose.drawing/stringdigitsubstitute) yang menentukan cara menggantikan karakter dalam string yang tidak dapat ditampilkan karena tidak didukung oleh font saat ini.
### dispose() {#dispose--}
```
public void dispose()
```


Melepaskan semua sumber daya yang digunakan oleh objek [StringFormat](../../com.aspose.drawing/stringformat) ini.

### deepClone() {#deepClone--}
```
public StringFormat deepClone()
```


Membuat salinan persis dari objek [StringFormat](../../com.aspose.drawing/stringformat) ini.

**Returns:**
[StringFormat](../../com.aspose.drawing/stringformat) - The [StringFormat](../../com.aspose.drawing/stringformat) object this method creates.
### getTabStops(float[] firstTabOffset) {#getTabStops-float---}
```
public float[] getTabStops(float[] firstTabOffset)
```


Mendapatkan tab stop untuk objek [StringFormat](../../com.aspose.drawing/stringformat) ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| firstTabOffset | float[] | Jumlah spasi antara awal baris teks dan tab stop pertama. |

**Returns:**
float[] - Sebuah array jarak (dalam jumlah spasi) antara tab stop.
### getTabStops() {#getTabStops--}
```
public float[] getTabStops()
```


Mendapatkan array jarak antar tab stop dalam satuan yang ditentukan oleh properti `Aspose.Imaging.getGraphics().PageUnit`.

**Returns:**
float[] - Tab stop.

Properti ini diperkenalkan untuk metode GetTabStops yang dihapus.
### setTabStops(float firstTabOffset, float[] tabStops) {#setTabStops-float-float---}
```
public void setTabStops(float firstTabOffset, float[] tabStops)
```


Mengatur tab stop untuk objek [StringFormat](../../com.aspose.drawing/stringformat) ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| firstTabOffset | float | Jumlah spasi antara awal baris teks dan tab stop pertama. |
| tabStops | float[] | Sebuah array jarak antara tab stop dalam satuan yang ditentukan oleh properti Graphics.PageUnit. |

### setDigitSubstitution(int language, int substitute) {#setDigitSubstitution-int-int-}
```
public void setDigitSubstitution(int language, int substitute)
```


Menentukan bahasa dan metode yang akan digunakan ketika digit lokal digantikan dengan digit barat.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| bahasa | int | Sebuah pengidentifikasi bahasa National Language Support (NLS) yang mengidentifikasi bahasa yang akan digunakan ketika digit lokal digantikan dengan digit barat. Anda dapat meneruskan properti `System.Globalization.CultureInfo.LCID` dari objek java.util.Locale sebagai pengidentifikasi bahasa NLS. Misalnya, anggap Anda membuat objek java.util.Locale dengan memberikan string `"ar-EG"` ke konstruktor java.util.Locale. Jika Anda meneruskan properti `System.Globalization.CultureInfo.LCID` dari objek java.util.Locale tersebut bersama `StringDigitSubstitute.Traditional` ke metode `M:StringFormat.SetDigitSubstitution(System.Int32,StringDigitSubstitute)`, maka digit Arab-Indic akan digantikan dengan digit barat pada saat tampilan. |
| substitute | int | Sebuah elemen dari enumerasi [StringDigitSubstitute](../../com.aspose.drawing/stringdigitsubstitute) yang menentukan bagaimana digit ditampilkan. |

### setMeasurableCharacterRanges(CharacterRange[] ranges) {#setMeasurableCharacterRanges-com.aspose.drawing.CharacterRange---}
```
public void setMeasurableCharacterRanges(CharacterRange[] ranges)
```


Menentukan array struktur [CharacterRange](../../com.aspose.drawing/characterrange) yang mewakili rentang karakter yang diukur oleh pemanggilan metode `MeasureCharacterRanges`.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| ranges | [CharacterRange\[\]](../../com.aspose.drawing/characterrange) | Sebuah array struktur [CharacterRange](../../com.aspose.drawing/characterrange) yang menentukan rentang karakter yang diukur oleh pemanggilan metode `MeasureCharacterRanges`. |

