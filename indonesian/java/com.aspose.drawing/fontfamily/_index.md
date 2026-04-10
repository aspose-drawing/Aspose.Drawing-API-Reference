---
title: FontFamily
second_title: Referensi API Aspose.Drawing for Java
description: Mendefinisikan sekelompok tipe huruf yang memiliki desain dasar serupa dan variasi tertentu dalam gaya.
type: docs
weight: 24
url: /id/java/com.aspose.drawing/fontfamily/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public final class FontFamily implements System.IDisposable
```

Mendefinisikan sekumpulan tipe huruf yang memiliki desain dasar serupa dan variasi tertentu dalam gaya. Kelas ini tidak dapat diwarisi.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [FontFamily(String name)](#FontFamily-java.lang.String-) | Menginisialisasi instance baru dari kelas [FontFamily](../../com.aspose.drawing/fontfamily) dengan nama yang ditentukan. |
| [FontFamily(String name, FontCollection fontCollection)](#FontFamily-java.lang.String-com.aspose.drawing.FontCollection-) | Menginisialisasi instance baru dari kelas [FontFamily](../../com.aspose.drawing/fontfamily). |
| [FontFamily(String name, FontFamilyDefinition definition)](#FontFamily-java.lang.String-com.aspose.drawing.FontFamilyDefinition-) | Menginisialisasi instance baru dari kelas [FontFamily](../../com.aspose.drawing/fontfamily). |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getFamilies()](#getFamilies--) | Mengambil sebuah array yang berisi semua objek [FontFamily](../../com.aspose.drawing/fontfamily) yang terkait dengan konteks grafis saat ini. |
| [getGenericSansSerif()](#getGenericSansSerif--) | Mengambil objek [FontFamily](../../com.aspose.drawing/fontfamily) sans serif generik. |
| [getGenericSerif()](#getGenericSerif--) | Mengambil [FontFamily](../../com.aspose.drawing/fontfamily) serif generik. |
| [getGenericMonospace()](#getGenericMonospace--) | Mengambil [FontFamily](../../com.aspose.drawing/fontfamily) monospace generik. |
| [getName()](#getName--) | Mengambil nama dari [FontFamily](../../com.aspose.drawing/fontfamily) ini. |
| [dispose()](#dispose--) | Menghapus semua sumber daya yang digunakan oleh [FontFamily](../../com.aspose.drawing/fontfamily) ini. |
| [getName(int language)](#getName-int-) | Mengembalikan nama, dalam bahasa yang ditentukan, dari [FontFamily](../../com.aspose.drawing/fontfamily) ini. |
| [isStyleAvailable(int style)](#isStyleAvailable-int-) | Indicates whether the specified [FontStyle](../../com.aspose.drawing/fontstyle) enumeration is available. |
| [getEmHeight(int style)](#getEmHeight-int-) | Gets the height, in font design units, of the EM square for the specified style. |
| [getCellAscent(int style)](#getCellAscent-int-) | Returns the cell ascent, in design units, of the [FontFamily](../../com.aspose.drawing/fontfamily) of the specified style. |
| [getCellDescent(int style)](#getCellDescent-int-) | Returns the cell descent, in design units, of the [FontFamily](../../com.aspose.drawing/fontfamily) of the specified style. |
| [hashCode()](#hashCode--) | Gets a hash code for this [FontFamily](../../com.aspose.drawing/fontfamily). |
| [equals(Object obj)](#equals-java.lang.Object-) | Indicates whether the specified object is a [FontFamily](../../com.aspose.drawing/fontfamily) and is identical to this [FontFamily](../../com.aspose.drawing/fontfamily). |
| [getLineSpacing(int style)](#getLineSpacing-int-) | Returns the line spacing, in design units, of the [FontFamily](../../com.aspose.drawing/fontfamily) of the specified style. |
### FontFamily(String name) {#FontFamily-java.lang.String-}
```
public FontFamily(String name)
```


Menginisialisasi instance baru dari kelas [FontFamily](../../com.aspose.drawing/fontfamily) dengan nama yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | java.lang.String | The name of the new [FontFamily](../../com.aspose.drawing/fontfamily). |

### FontFamily(String name, FontCollection fontCollection) {#FontFamily-java.lang.String-com.aspose.drawing.FontCollection-}
```
public FontFamily(String name, FontCollection fontCollection)
```


Menginisialisasi instance baru dari kelas [FontFamily](../../com.aspose.drawing/fontfamily).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | java.lang.String | The name of the font family. |
| fontCollection | [FontCollection](../../com.aspose.drawing/fontcollection) | The font collection. |

### FontFamily(String name, FontFamilyDefinition definition) {#FontFamily-java.lang.String-com.aspose.drawing.FontFamilyDefinition-}
```
public FontFamily(String name, FontFamilyDefinition definition)
```


Menginisialisasi instance baru dari kelas [FontFamily](../../com.aspose.drawing/fontfamily).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | java.lang.String | The name of the font family. |
| definition | [FontFamilyDefinition](../../com.aspose.drawing/fontfamilydefinition) | The definition. |

### getFamilies() {#getFamilies--}
```
public static FontFamily[] getFamilies()
```


Mengambil sebuah array yang berisi semua objek [FontFamily](../../com.aspose.drawing/fontfamily) yang terkait dengan konteks grafis saat ini.

**Returns:**
com.aspose.drawing.FontFamily[] - An array of [FontFamily](../../com.aspose.drawing/fontfamily) objects associated with the current graphics context.
### getGenericSansSerif() {#getGenericSansSerif--}
```
public static FontFamily getGenericSansSerif()
```


Mengambil objek [FontFamily](../../com.aspose.drawing/fontfamily) sans serif generik.

**Returns:**
[FontFamily](../../com.aspose.drawing/fontfamily) - A [FontFamily](../../com.aspose.drawing/fontfamily) object that represents a generic sans serif font.
### getGenericSerif() {#getGenericSerif--}
```
public static FontFamily getGenericSerif()
```


Mengambil [FontFamily](../../com.aspose.drawing/fontfamily) serif generik.

**Returns:**
[FontFamily](../../com.aspose.drawing/fontfamily) - A [FontFamily](../../com.aspose.drawing/fontfamily) that represents a generic serif font.
### getGenericMonospace() {#getGenericMonospace--}
```
public static FontFamily getGenericMonospace()
```


Mengambil [FontFamily](../../com.aspose.drawing/fontfamily) monospace generik.

**Returns:**
[FontFamily](../../com.aspose.drawing/fontfamily) - A [FontFamily](../../com.aspose.drawing/fontfamily) that represents a generic monospace font.
### getName() {#getName--}
```
public String getName()
```


Mengambil nama dari [FontFamily](../../com.aspose.drawing/fontfamily) ini.

**Returns:**
java.lang.String - A String that represents the name of this [FontFamily](../../com.aspose.drawing/fontfamily).
### dispose() {#dispose--}
```
public void dispose()
```


Menghapus semua sumber daya yang digunakan oleh [FontFamily](../../com.aspose.drawing/fontfamily) ini.

### getName(int language) {#getName-int-}
```
public String getName(int language)
```


Mengembalikan nama, dalam bahasa yang ditentukan, dari [FontFamily](../../com.aspose.drawing/fontfamily) ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| bahasa | int | The language in which the name is returned. |

**Returns:**
java.lang.String - A String that represents the name, in the specified language, of this [FontFamily](../../com.aspose.drawing/fontfamily).
### isStyleAvailable(int style) {#isStyleAvailable-int-}
```
public boolean isStyleAvailable(int style)
```


Indicates whether the specified [FontStyle](../../com.aspose.drawing/fontstyle) enumeration is available.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| style | int | The [FontStyle](../../com.aspose.drawing/fontstyle) to test. |

**Returns:**
boolean - true if the specified [FontStyle](../../com.aspose.drawing/fontstyle) is available; otherwise, false.
### getEmHeight(int style) {#getEmHeight-int-}
```
public int getEmHeight(int style)
```


Gets the height, in font design units, of the EM square for the specified style.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| style | int | The [FontStyle](../../com.aspose.drawing/fontstyle) for which to get the EM height. |

**Returns:**
int - The height of the EM square.
### getCellAscent(int style) {#getCellAscent-int-}
```
public int getCellAscent(int style)
```


Returns the cell ascent, in design units, of the [FontFamily](../../com.aspose.drawing/fontfamily) of the specified style.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| style | int | A [FontStyle](../../com.aspose.drawing/fontstyle) that contains style information for the font. |

**Returns:**
int - The cell ascent for this [FontFamily](../../com.aspose.drawing/fontfamily) that uses the specified [FontStyle](../../com.aspose.drawing/fontstyle).
### getCellDescent(int style) {#getCellDescent-int-}
```
public int getCellDescent(int style)
```


Returns the cell descent, in design units, of the [FontFamily](../../com.aspose.drawing/fontfamily) of the specified style.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| style | int | A [FontStyle](../../com.aspose.drawing/fontstyle) that contains style information for the font. |

**Returns:**
int - The cell descent metric for this [FontFamily](../../com.aspose.drawing/fontfamily) that uses the specified [FontStyle](../../com.aspose.drawing/fontstyle).
### hashCode() {#hashCode--}
```
public int hashCode()
```


Gets a hash code for this [FontFamily](../../com.aspose.drawing/fontfamily).

**Returns:**
int - The hash code for this [FontFamily](../../com.aspose.drawing/fontfamily).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Indicates whether the specified object is a [FontFamily](../../com.aspose.drawing/fontfamily) and is identical to this [FontFamily](../../com.aspose.drawing/fontfamily).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | java.lang.Object | Objek yang akan diuji. |

**Returns:**
boolean - `true` if `obj` is a [FontFamily](../../com.aspose.drawing/fontfamily) and is identical to this [FontFamily](../../com.aspose.drawing/fontfamily); otherwise, `false`.
### getLineSpacing(int style) {#getLineSpacing-int-}
```
public int getLineSpacing(int style)
```


Mengembalikan jarak baris, dalam satuan desain, dari [FontFamily](../../com.aspose.drawing/fontfamily) dari gaya yang ditentukan. Jarak baris adalah jarak vertikal antara garis dasar dua baris teks yang berurutan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| style | int | [FontStyle](../../com.aspose.drawing/fontstyle) yang akan diterapkan. |

**Returns:**
int - Jarak antara dua baris teks yang berurutan.
