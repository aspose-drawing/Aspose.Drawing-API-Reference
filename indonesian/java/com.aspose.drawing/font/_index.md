---
title: Font
second_title: Referensi API Aspose.Drawing for Java
description: Mendefinisikan format tertentu untuk teks termasuk jenis huruf, ukuran, dan atribut gaya.
type: docs
weight: 21
url: /id/java/com.aspose.drawing/font/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public final class Font implements System.IDisposable
```

Mendefinisikan format tertentu untuk teks, termasuk jenis huruf, ukuran, dan atribut gaya. Kelas ini tidak dapat diwariskan.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [Font(Font prototype, int newStyle)](#Font-com.aspose.drawing.Font-int-) | Menginisialisasi instance baru dari kelas [Font](../../com.aspose.drawing/font) yang menggunakan [Font](../../com.aspose.drawing/font) dan enumerasi [FontStyle](../../com.aspose.drawing/fontstyle) yang sudah ada. |
| [Font(FontFamily family, float emSize)](#Font-com.aspose.drawing.FontFamily-float-) | Menginisialisasi instance baru dari kelas [Font](../../com.aspose.drawing/font). |
| [Font(FontFamily family, float emSize, int style)](#Font-com.aspose.drawing.FontFamily-float-int-) | Menginisialisasi instance baru dari kelas [Font](../../com.aspose.drawing/font) menggunakan ukuran dan gaya yang ditentukan.. |
| [Font(FontFamily family, float emSize, int style, int unit)](#Font-com.aspose.drawing.FontFamily-float-int-int-) | Menginisialisasi instance baru dari kelas [Font](../../com.aspose.drawing/font) menggunakan ukuran, gaya, dan unit yang ditentukan. |
| [Font(FontFamily family, float emSize, int style, int unit, byte gdiCharSet)](#Font-com.aspose.drawing.FontFamily-float-int-int-byte-) | Menginisialisasi instance baru dari kelas [Font](../../com.aspose.drawing/font) menggunakan ukuran, gaya, unit, dan set karakter yang ditentukan.. |
| [Font(FontFamily family, float emSize, int style, int unit, byte gdiCharSet, boolean gdiVerticalFont)](#Font-com.aspose.drawing.FontFamily-float-int-int-byte-boolean-) | Menginisialisasi instance baru dari kelas [Font](../../com.aspose.drawing/font) menggunakan ukuran, gaya, unit, dan set karakter yang ditentukan.. |
| [Font(String familyName, float emSize)](#Font-java.lang.String-float-) | Menginisialisasi instance baru dari kelas [Font](../../com.aspose.drawing/font) menggunakan ukuran yang ditentukan. |
| [Font(String familyName, float emSize, int style)](#Font-java.lang.String-float-int-) | Menginisialisasi instance baru dari kelas [Font](../../com.aspose.drawing/font) menggunakan ukuran dan gaya yang ditentukan. |
| [Font(String familyName, float emSize, int style, int unit)](#Font-java.lang.String-float-int-int-) | Menginisialisasi instance baru dari kelas [Font](../../com.aspose.drawing/font) menggunakan ukuran, gaya, dan unit yang ditentukan. |
| [Font(String familyName, float emSize, int style, int unit, byte gdiCharSet)](#Font-java.lang.String-float-int-int-byte-) | Menginisialisasi instance baru dari kelas [Font](../../com.aspose.drawing/font) menggunakan ukuran, gaya, unit, dan set karakter yang ditentukan. |
| [Font(String familyName, float emSize, int style, int unit, byte gdiCharSet, boolean gdiVerticalFont)](#Font-java.lang.String-float-int-int-byte-boolean-) | Menginisialisasi instance baru dari kelas [Font](../../com.aspose.drawing/font) menggunakan ukuran, gaya, unit, dan set karakter yang ditentukan. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getFontFamily()](#getFontFamily--) | Mendapatkan `FontFamily`([.getFontFamily](../../null/\#getFontFamily)) yang terkait dengan [Font](../../com.aspose.drawing/font) ini. |
| [getBold()](#getBold--) | Mendapatkan nilai yang menunjukkan apakah [Font](../../com.aspose.drawing/font) ini tebal. |
| [getGdiCharSet()](#getGdiCharSet--) | Mendapatkan nilai byte yang menentukan set karakter GDI yang digunakan oleh [Font](../../com.aspose.drawing/font) ini. |
| [getGdiVerticalFont()](#getGdiVerticalFont--) | Mendapatkan nilai yang menunjukkan apakah [Font](../../com.aspose.drawing/font) ini diturunkan dari font vertikal GDI.. |
| [getItalic()](#getItalic--) | Mendapatkan nilai yang menunjukkan apakah [Font](../../com.aspose.drawing/font) ini miring. |
| [getName()](#getName--) | Mendapatkan nama wajah (face name) dari [Font](../../com.aspose.drawing/font) ini. |
| [getStrikeout()](#getStrikeout--) | Mendapatkan nilai yang menunjukkan apakah [Font](../../com.aspose.drawing/font) ini memiliki garis horizontal melalui font. |
| [getUnderline()](#getUnderline--) | Mendapatkan nilai yang menunjukkan apakah [Font](../../com.aspose.drawing/font) ini bergaris bawah. |
| [getStyle()](#getStyle--) | Mendapatkan informasi gaya untuk [Font](../../com.aspose.drawing/font) ini. |
| [getSize()](#getSize--) | Mendapatkan ukuran em dari [Font](../../com.aspose.drawing/font) ini yang diukur dalam unit yang ditentukan oleh properti `Font.Unit`. |
| [getSizeInPoints()](#getSizeInPoints--) | Mendapatkan ukuran em, dalam poin, dari [Font](../../com.aspose.drawing/font) ini. |
| [getUnit()](#getUnit--) | Mendapatkan satuan ukuran untuk [Font](../../com.aspose.drawing/font) ini. |
| [getHeight_Rename_Namesake()](#getHeight-Rename-Namesake--) | Mendapatkan jarak baris (line spacing) dari font ini. |
| [isSystemFont()](#isSystemFont--) | Mendapatkan nilai yang menunjukkan apakah font ini merupakan anggota dari [SystemFonts](../../com.aspose.drawing/systemfonts). |
| [getSystemFontName()](#getSystemFontName--) | Mendapatkan nama font sistem jika properti IsSystemFont mengembalikan true. |
| [getOriginalFontName()](#getOriginalFontName--) | Mendapatkan nama font yang awalnya ditentukan. |
| [deepClone()](#deepClone--) | Membuat salinan persis dari [Font](../../com.aspose.drawing/font) ini. |
| [equals(Object obj)](#equals-java.lang.Object-) | Menunjukkan apakah objek yang ditentukan adalah [Font](../../com.aspose.drawing/font) dan memiliki nilai properti `FontFamily`([.getFontFamily](../../null/\#getFontFamily)), `M:GdiVerticalFont`, `M:GdiCharSet`, `M:Style`, `M:Size`, dan `M:Unit` yang sama dengan [Font](../../com.aspose.drawing/font). |
| [hashCode()](#hashCode--) | Mendapatkan kode hash untuk [Font](../../com.aspose.drawing/font). |
| [getHeight()](#getHeight--) | Mengembalikan jarak baris, dalam piksel, dari font ini. |
| [getHeight(Graphics graphics)](#getHeight-com.aspose.drawing.Graphics-) | Mengembalikan jarak baris, dalam satuan saat ini dari [Graphics](../../com.aspose.drawing/graphics), untuk font ini. |
| [getHeight(float dpi)](#getHeight-float-) | Mengembalikan tinggi, dalam piksel, dari [Font](../../com.aspose.drawing/font) ketika digambar ke perangkat dengan resolusi vertikal yang ditentukan. |
| [dispose()](#dispose--) | Melepaskan semua sumber daya yang digunakan oleh [Font](../../com.aspose.drawing/font). |
| [toString()](#toString--) | Mengembalikan representasi string yang dapat dibaca manusia dari [Font](../../com.aspose.drawing/font). |
| [getCharacterSet()](#getCharacterSet--) | Mendapatkan nilai byte yang menentukan set karakter yang digunakan oleh `Font` ini. |
### Font(Font prototype, int newStyle) {#Font-com.aspose.drawing.Font-int-}
```
public Font(Font prototype, int newStyle)
```


Menginisialisasi instance baru dari kelas [Font](../../com.aspose.drawing/font) yang menggunakan [Font](../../com.aspose.drawing/font) dan enumerasi [FontStyle](../../com.aspose.drawing/fontstyle) yang sudah ada.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| prototype | [Font](../../com.aspose.drawing/font) | Font yang ada [Font](../../com.aspose.drawing/font) yang akan digunakan untuk membuat [Font](../../com.aspose.drawing/font) baru. |
| newStyle | int | [FontStyle](../../com.aspose.drawing/fontstyle) yang akan diterapkan pada [Font](../../com.aspose.drawing/font) baru. Beberapa nilai enumerasi [FontStyle](../../com.aspose.drawing/fontstyle) dapat digabungkan dengan operator OR. |

### Font(FontFamily family, float emSize) {#Font-com.aspose.drawing.FontFamily-float-}
```
public Font(FontFamily family, float emSize)
```


Menginisialisasi instance baru dari kelas [Font](../../com.aspose.drawing/font).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| family | [FontFamily](../../com.aspose.drawing/fontfamily) | `FontFamily`([.getFontFamily](../../null/\#getFontFamily)) dari [Font](../../com.aspose.drawing/font) baru. |
| emSize | float | Ukuran em, dalam poin, dari font baru. |

### Font(FontFamily family, float emSize, int style) {#Font-com.aspose.drawing.FontFamily-float-int-}
```
public Font(FontFamily family, float emSize, int style)
```


Menginisialisasi instance baru dari kelas [Font](../../com.aspose.drawing/font) menggunakan ukuran dan gaya yang ditentukan..

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| family | [FontFamily](../../com.aspose.drawing/fontfamily) | `FontFamily`([.getFontFamily](../../null/\#getFontFamily)) dari [Font](../../com.aspose.drawing/font) baru. |
| emSize | float | Ukuran em, dalam poin, dari font baru. |
| style | int | [FontStyle](../../com.aspose.drawing/fontstyle) dari font baru. |

### Font(FontFamily family, float emSize, int style, int unit) {#Font-com.aspose.drawing.FontFamily-float-int-int-}
```
public Font(FontFamily family, float emSize, int style, int unit)
```


Menginisialisasi instance baru dari kelas [Font](../../com.aspose.drawing/font) menggunakan ukuran, gaya, dan unit yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| family | [FontFamily](../../com.aspose.drawing/fontfamily) | `FontFamily`([.getFontFamily](../../null/\#getFontFamily)) dari [Font](../../com.aspose.drawing/font) baru. |
| emSize | float | Ukuran em dari font baru dalam satuan yang ditentukan oleh parameter `unit`. |
| style | int | [FontStyle](../../com.aspose.drawing/fontstyle) dari font baru. |
| unit | int | [GraphicsUnit](../../com.aspose.drawing/graphicsunit) dari font baru. |

### Font(FontFamily family, float emSize, int style, int unit, byte gdiCharSet) {#Font-com.aspose.drawing.FontFamily-float-int-int-byte-}
```
public Font(FontFamily family, float emSize, int style, int unit, byte gdiCharSet)
```


Menginisialisasi instance baru dari kelas [Font](../../com.aspose.drawing/font) menggunakan ukuran, gaya, unit, dan set karakter yang ditentukan..

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| family | [FontFamily](../../com.aspose.drawing/fontfamily) | `FontFamily`([.getFontFamily](../../null/\#getFontFamily)) dari [Font](../../com.aspose.drawing/font) baru. |
| emSize | float | Ukuran em dari font baru dalam satuan yang ditentukan oleh parameter `unit`. |
| style | int | [FontStyle](../../com.aspose.drawing/fontstyle) dari font baru. |
| unit | int | [GraphicsUnit](../../com.aspose.drawing/graphicsunit) dari font baru. |
| gdiCharSet | byte | Set karakter GDI yang akan digunakan untuk font baru. |

### Font(FontFamily family, float emSize, int style, int unit, byte gdiCharSet, boolean gdiVerticalFont) {#Font-com.aspose.drawing.FontFamily-float-int-int-byte-boolean-}
```
public Font(FontFamily family, float emSize, int style, int unit, byte gdiCharSet, boolean gdiVerticalFont)
```


Menginisialisasi instance baru dari kelas [Font](../../com.aspose.drawing/font) menggunakan ukuran, gaya, unit, dan set karakter yang ditentukan..

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| family | [FontFamily](../../com.aspose.drawing/fontfamily) | `FontFamily`([.getFontFamily](../../null/\#getFontFamily)) dari [Font](../../com.aspose.drawing/font) baru. |
| emSize | float | Ukuran em dari font baru dalam satuan yang ditentukan oleh parameter `unit`. |
| style | int | [FontStyle](../../com.aspose.drawing/fontstyle) dari font baru. |
| unit | int | [GraphicsUnit](../../com.aspose.drawing/graphicsunit) dari font baru. |
| gdiCharSet | byte | Set karakter GDI yang akan digunakan untuk font baru. |
| gdiVerticalFont | boolean | Nilai Boolean yang menunjukkan apakah font baru diturunkan dari font vertikal GDI. |

### Font(String familyName, float emSize) {#Font-java.lang.String-float-}
```
public Font(String familyName, float emSize)
```


Menginisialisasi instance baru dari kelas [Font](../../com.aspose.drawing/font) menggunakan ukuran yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| familyName | java.lang.String | Representasi string dari FontFamily untuk [Font](../../com.aspose.drawing/font) baru. |
| emSize | float | Ukuran em, dalam poin, dari font baru. |

### Font(String familyName, float emSize, int style) {#Font-java.lang.String-float-int-}
```
public Font(String familyName, float emSize, int style)
```


Menginisialisasi instance baru dari kelas [Font](../../com.aspose.drawing/font) menggunakan ukuran dan gaya yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| familyName | java.lang.String | Representasi string dari FontFamily untuk [Font](../../com.aspose.drawing/font) baru. |
| emSize | float | Ukuran em, dalam poin, dari font baru. |
| style | int | [FontStyle](../../com.aspose.drawing/fontstyle) dari font baru. |

### Font(String familyName, float emSize, int style, int unit) {#Font-java.lang.String-float-int-int-}
```
public Font(String familyName, float emSize, int style, int unit)
```


Menginisialisasi instance baru dari kelas [Font](../../com.aspose.drawing/font) menggunakan ukuran, gaya, dan unit yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| familyName | java.lang.String | Representasi string dari `FontFamily`([.getFontFamily](../../null/\#getFontFamily)) untuk [Font](../../com.aspose.drawing/font) baru. |
| emSize | float | Ukuran em dari font baru dalam satuan yang ditentukan oleh parameter `unit`. |
| style | int | [FontStyle](../../com.aspose.drawing/fontstyle) dari font baru. |
| unit | int | [GraphicsUnit](../../com.aspose.drawing/graphicsunit) dari font baru. |

### Font(String familyName, float emSize, int style, int unit, byte gdiCharSet) {#Font-java.lang.String-float-int-int-byte-}
```
public Font(String familyName, float emSize, int style, int unit, byte gdiCharSet)
```


Menginisialisasi instance baru dari kelas [Font](../../com.aspose.drawing/font) menggunakan ukuran, gaya, unit, dan set karakter yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| familyName | java.lang.String | Representasi string dari FontFamily untuk [Font](../../com.aspose.drawing/font) baru. |
| emSize | float | Ukuran em dari font baru dalam satuan yang ditentukan oleh parameter `unit`. |
| style | int | [FontStyle](../../com.aspose.drawing/fontstyle) dari font baru. |
| unit | int | [GraphicsUnit](../../com.aspose.drawing/graphicsunit) dari font baru. |
| gdiCharSet | byte | Byte yang menentukan set karakter GDI yang akan digunakan untuk font ini. |

### Font(String familyName, float emSize, int style, int unit, byte gdiCharSet, boolean gdiVerticalFont) {#Font-java.lang.String-float-int-int-byte-boolean-}
```
public Font(String familyName, float emSize, int style, int unit, byte gdiCharSet, boolean gdiVerticalFont)
```


Menginisialisasi instance baru dari kelas [Font](../../com.aspose.drawing/font) menggunakan ukuran, gaya, unit, dan set karakter yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| familyName | java.lang.String | Representasi string dari FontFamily untuk [Font](../../com.aspose.drawing/font) baru. |
| emSize | float | Ukuran em dari font baru dalam satuan yang ditentukan oleh parameter `unit`. |
| style | int | [FontStyle](../../com.aspose.drawing/fontstyle) dari font baru. |
| unit | int | [GraphicsUnit](../../com.aspose.drawing/graphicsunit) dari font baru. |
| gdiCharSet | byte | Byte yang menentukan set karakter GDI yang akan digunakan untuk font ini. |
| gdiVerticalFont | boolean | Nilai Boolean yang menunjukkan apakah [Font](../../com.aspose.drawing/font) baru diturunkan dari font vertikal GDI. |

### getFontFamily() {#getFontFamily--}
```
public FontFamily getFontFamily()
```


Mendapatkan `FontFamily`([.getFontFamily](../../null/\#getFontFamily)) yang terkait dengan [Font](../../com.aspose.drawing/font) ini.

**Returns:**
[FontFamily](../../com.aspose.drawing/fontfamily) - The `FontFamily`([.getFontFamily](../../null/\#getFontFamily)) associated with this [Font](../../com.aspose.drawing/font).
### getBold() {#getBold--}
```
public boolean getBold()
```


Mendapatkan nilai yang menunjukkan apakah [Font](../../com.aspose.drawing/font) ini tebal.

**Returns:**
boolean - nilai yang menunjukkan apakah [Font](../../com.aspose.drawing/font) ini tebal.
### getGdiCharSet() {#getGdiCharSet--}
```
public byte getGdiCharSet()
```


Mendapatkan nilai byte yang menentukan set karakter GDI yang digunakan oleh [Font](../../com.aspose.drawing/font) ini.

**Returns:**
byte - Nilai byte yang menentukan set karakter GDI yang digunakan oleh [Font](../../com.aspose.drawing/font) ini.
### getGdiVerticalFont() {#getGdiVerticalFont--}
```
public boolean getGdiVerticalFont()
```


Mendapatkan nilai yang menunjukkan apakah [Font](../../com.aspose.drawing/font) ini diturunkan dari font vertikal GDI..

Nilai: `true` jika [Font](../../com.aspose.drawing/font) ini diturunkan dari font vertikal GDI; jika tidak, `false`.

**Returns:**
boolean - nilai yang menunjukkan apakah [Font](../../com.aspose.drawing/font) ini diturunkan dari font vertikal GDI.
### getItalic() {#getItalic--}
```
public boolean getItalic()
```


Mendapatkan nilai yang menunjukkan apakah [Font](../../com.aspose.drawing/font) ini miring.

**Returns:**
boolean - nilai yang menunjukkan apakah [Font](../../com.aspose.drawing/font) ini miring.
### getName() {#getName--}
```
public String getName()
```


Mendapatkan nama wajah (face name) dari [Font](../../com.aspose.drawing/font) ini.

**Returns:**
java.lang.String - nama jenis huruf dari [Font](../../com.aspose.drawing/font) ini.
### getStrikeout() {#getStrikeout--}
```
public boolean getStrikeout()
```


Mendapatkan nilai yang menunjukkan apakah [Font](../../com.aspose.drawing/font) ini memiliki garis horizontal melalui font.

**Returns:**
boolean - nilai yang menunjukkan apakah [Font](../../com.aspose.drawing/font) ini memiliki garis horizontal melalui huruf.
### getUnderline() {#getUnderline--}
```
public boolean getUnderline()
```


Mendapatkan nilai yang menunjukkan apakah [Font](../../com.aspose.drawing/font) ini bergaris bawah.

**Returns:**
boolean - nilai yang menunjukkan apakah [Font](../../com.aspose.drawing/font) ini digarisbawahi.
### getStyle() {#getStyle--}
```
public int getStyle()
```


Mendapatkan informasi gaya untuk [Font](../../com.aspose.drawing/font) ini.

**Returns:**
int - informasi gaya untuk [Font](../../com.aspose.drawing/font) ini.
### getSize() {#getSize--}
```
public float getSize()
```


Mendapatkan ukuran em dari [Font](../../com.aspose.drawing/font) ini yang diukur dalam unit yang ditentukan oleh properti `Font.Unit`.

**Returns:**
float - ukuran em dari [Font](../../com.aspose.drawing/font) ini diukur dalam satuan yang ditentukan oleh \\{@code Font.
### getSizeInPoints() {#getSizeInPoints--}
```
public float getSizeInPoints()
```


Mendapatkan ukuran em, dalam poin, dari [Font](../../com.aspose.drawing/font) ini.

**Returns:**
float - Ukuran em, dalam poin, dari [Font](../../com.aspose.drawing/font) ini.
### getUnit() {#getUnit--}
```
public int getUnit()
```


Mendapatkan satuan ukuran untuk [Font](../../com.aspose.drawing/font) ini.

**Returns:**
int - satuan ukuran untuk [Font](../../com.aspose.drawing/font) ini.
### getHeight_Rename_Namesake() {#getHeight-Rename-Namesake--}
```
public int getHeight_Rename_Namesake()
```


Mendapatkan jarak baris (line spacing) dari font ini.

Nilai: Jarak baris, dalam piksel, dari font ini.

**Returns:**
int - jarak baris dari font ini.
### isSystemFont() {#isSystemFont--}
```
public boolean isSystemFont()
```


Mendapatkan nilai yang menunjukkan apakah font ini merupakan anggota dari [SystemFonts](../../com.aspose.drawing/systemfonts).

Nilai: `true` jika font merupakan anggota [SystemFonts](../../com.aspose.drawing/systemfonts); jika tidak, `false`.

**Returns:**
boolean - nilai yang menunjukkan apakah font merupakan anggota [SystemFonts](../../com.aspose.drawing/systemfonts).
### getSystemFontName() {#getSystemFontName--}
```
public String getSystemFontName()
```


Mendapatkan nama font sistem jika properti IsSystemFont mengembalikan true.

Nilai: Nama font sistem, jika IsSystemFont mengembalikan true; jika tidak, string kosong ("").

**Returns:**
java.lang.String - nama font sistem jika properti IsSystemFont mengembalikan true.
### getOriginalFontName() {#getOriginalFontName--}
```
public String getOriginalFontName()
```


Mendapatkan nama font yang awalnya ditentukan.

Nilai: String yang mewakili nama font yang awalnya ditentukan.

**Returns:**
java.lang.String - nama font yang awalnya ditentukan.
### deepClone() {#deepClone--}
```
public Font deepClone()
```


Membuat salinan persis dari [Font](../../com.aspose.drawing/font) ini.

**Returns:**
[Font](../../com.aspose.drawing/font) - The [Font](../../com.aspose.drawing/font) this method creates, cast as an Object.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Menunjukkan apakah objek yang ditentukan adalah [Font](../../com.aspose.drawing/font) dan memiliki nilai properti `FontFamily`([.getFontFamily](../../null/\#getFontFamily)), `M:GdiVerticalFont`, `M:GdiCharSet`, `M:Style`, `M:Size`, dan `M:Unit` yang sama dengan [Font](../../com.aspose.drawing/font).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | java.lang.Object | Objek yang akan diuji. |

**Returns:**
boolean - `true` jika parameter obj adalah sebuah [Font](../../com.aspose.drawing/font) dan memiliki nilai properti `FontFamily`([.getFontFamily](../../null/\\#getFontFamily)), `M:GdiVerticalFont`, `M:GdiCharSet`, `M:Style`, `M:Size`, dan `M:Unit` yang sama dengan [Font](../../com.aspose.drawing/font) ini; jika tidak, `false`.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Mendapatkan kode hash untuk [Font](../../com.aspose.drawing/font).

**Returns:**
int - Kode hash untuk [Font](../../com.aspose.drawing/font) ini.
### getHeight() {#getHeight--}
```
public int getHeight()
```


Mengembalikan jarak baris, dalam piksel, dari font ini.

**Returns:**
int - Jarak baris, dalam piksel, dari font ini.
### getHeight(Graphics graphics) {#getHeight-com.aspose.drawing.Graphics-}
```
public float getHeight(Graphics graphics)
```


Mengembalikan jarak baris, dalam satuan saat ini dari [Graphics](../../com.aspose.drawing/graphics), untuk font ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| graphics | [Graphics](../../com.aspose.drawing/graphics) | Sebuah [Graphics](../../com.aspose.drawing/graphics) yang menyimpan resolusi vertikal, dalam dot per inci, dari perangkat tampilan serta pengaturan untuk satuan halaman dan skala halaman. |

**Returns:**
float - Jarak baris, dalam piksel, dari font ini.
### getHeight(float dpi) {#getHeight-float-}
```
public int getHeight(float dpi)
```


Mengembalikan tinggi, dalam piksel, dari [Font](../../com.aspose.drawing/font) ketika digambar ke perangkat dengan resolusi vertikal yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| dpi | float | Resolusi vertikal, dalam titik per inci, yang digunakan untuk menghitung tinggi font. |

**Returns:**
int - Tinggi, dalam piksel, dari [Font](../../com.aspose.drawing/font) ini.
### dispose() {#dispose--}
```
public void dispose()
```


Melepaskan semua sumber daya yang digunakan oleh [Font](../../com.aspose.drawing/font).

### toString() {#toString--}
```
public String toString()
```


Mengembalikan representasi string yang dapat dibaca manusia dari [Font](../../com.aspose.drawing/font).

**Returns:**
java.lang.String - String yang mewakili [Font](../../com.aspose.drawing/font) ini.
### getCharacterSet() {#getCharacterSet--}
```
public int getCharacterSet()
```


Mendapatkan nilai byte yang menentukan set karakter yang digunakan oleh `Font` ini.

**Returns:**
int - Set karakter yang digunakan `Font` ini.
