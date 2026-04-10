---
title: SystemFonts
second_title: Referensi API Aspose.Drawing for Java
description: Menentukan font yang digunakan untuk menampilkan teks dalam elemen tampilan Windows.
type: docs
weight: 51
url: /id/java/com.aspose.drawing/systemfonts/
---
**Inheritance:**
java.lang.Object
```
public final class SystemFonts
```

Menentukan font yang digunakan untuk menampilkan teks dalam elemen tampilan Windows.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getCaptionFont()](#getCaptionFont--) | Mendapatkan sebuah [Font](../../com.aspose.drawing/font) yang digunakan untuk menampilkan teks di bilah judul jendela. |
| [getSmallCaptionFont()](#getSmallCaptionFont--) | Mendapatkan sebuah [Font](../../com.aspose.drawing/font) yang digunakan untuk menampilkan teks di bilah judul jendela kecil, seperti jendela alat. |
| [getMenuFont()](#getMenuFont--) | Mendapatkan sebuah [Font](../../com.aspose.drawing/font) yang digunakan untuk menu. |
| [getStatusFont()](#getStatusFont--) | Mendapatkan sebuah [Font](../../com.aspose.drawing/font) yang digunakan untuk menampilkan teks di bilah status. |
| [getMessageBoxFont()](#getMessageBoxFont--) | Mendapatkan sebuah [Font](../../com.aspose.drawing/font) yang digunakan untuk kotak pesan. |
| [getIconTitleFont()](#getIconTitleFont--) | Mendapatkan sebuah [Font](../../com.aspose.drawing/font) yang digunakan untuk judul ikon. |
| [getDefaultFont()](#getDefaultFont--) | Mendapatkan font default yang dapat digunakan aplikasi untuk kotak dialog dan formulir. |
| [getDefaultImageFont()](#getDefaultImageFont--) | Mendapatkan font default yang dapat digunakan aplikasi untuk kotak dialog dan formulir. |
| [getDialogFont()](#getDialogFont--) | Mendapatkan font yang dapat digunakan aplikasi untuk kotak dialog dan formulir. |
| [getFontByName(String systemFontName)](#getFontByName-java.lang.String-) | Mengembalikan objek font yang sesuai dengan nama font sistem yang ditentukan. |
### getCaptionFont() {#getCaptionFont--}
```
public static Font getCaptionFont()
```


Mendapatkan sebuah [Font](../../com.aspose.drawing/font) yang digunakan untuk menampilkan teks di bilah judul jendela.

**Returns:**
[Font](../../com.aspose.drawing/font) - a [Font](../../com.aspose.drawing/font) that is used to display text in the title bars of windows.
### getSmallCaptionFont() {#getSmallCaptionFont--}
```
public static Font getSmallCaptionFont()
```


Mendapatkan sebuah [Font](../../com.aspose.drawing/font) yang digunakan untuk menampilkan teks di bilah judul jendela kecil, seperti jendela alat.

**Returns:**
[Font](../../com.aspose.drawing/font) - a [Font](../../com.aspose.drawing/font) that is used to display text in the title bars of small windows, such as tool windows.
### getMenuFont() {#getMenuFont--}
```
public static Font getMenuFont()
```


Mendapatkan sebuah [Font](../../com.aspose.drawing/font) yang digunakan untuk menu.

**Returns:**
[Font](../../com.aspose.drawing/font) - a [Font](../../com.aspose.drawing/font) that is used for menus.
### getStatusFont() {#getStatusFont--}
```
public static Font getStatusFont()
```


Mendapatkan sebuah [Font](../../com.aspose.drawing/font) yang digunakan untuk menampilkan teks di bilah status.

**Returns:**
[Font](../../com.aspose.drawing/font) - a [Font](../../com.aspose.drawing/font) that is used to display text in the status bar.
### getMessageBoxFont() {#getMessageBoxFont--}
```
public static Font getMessageBoxFont()
```


Mendapatkan sebuah [Font](../../com.aspose.drawing/font) yang digunakan untuk kotak pesan.

**Returns:**
[Font](../../com.aspose.drawing/font) - a [Font](../../com.aspose.drawing/font) that is used for message boxes.
### getIconTitleFont() {#getIconTitleFont--}
```
public static Font getIconTitleFont()
```


Mendapatkan sebuah [Font](../../com.aspose.drawing/font) yang digunakan untuk judul ikon.

**Returns:**
[Font](../../com.aspose.drawing/font) - a [Font](../../com.aspose.drawing/font) that is used for icon titles.
### getDefaultFont() {#getDefaultFont--}
```
public static Font getDefaultFont()
```


Mendapatkan font default yang dapat digunakan aplikasi untuk kotak dialog dan formulir.

**Returns:**
[Font](../../com.aspose.drawing/font) - The default [Font](../../com.aspose.drawing/font) of the system. The value returned will vary depending on the user's operating system and the local culture setting of their system.
### getDefaultImageFont() {#getDefaultImageFont--}
```
public static Font getDefaultImageFont()
```


Mendapatkan font default yang dapat digunakan aplikasi untuk kotak dialog dan formulir.

**Returns:**
[Font](../../com.aspose.imaging/font) - The default [Font](../../com.aspose.drawing/font) of the system. The value returned will vary depending on the user's operating system and the local culture setting of their system.
### getDialogFont() {#getDialogFont--}
```
public static Font getDialogFont()
```


Mendapatkan font yang dapat digunakan aplikasi untuk kotak dialog dan formulir.

**Returns:**
[Font](../../com.aspose.drawing/font) - A [Font](../../com.aspose.drawing/font) that can be used for dialog boxes and forms, depending on the operating system and local culture setting of the system.
### getFontByName(String systemFontName) {#getFontByName-java.lang.String-}
```
public static Font getFontByName(String systemFontName)
```


Mengembalikan objek font yang sesuai dengan nama font sistem yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| systemFontName | java.lang.String | Nama font sistem yang Anda butuhkan untuk objek font. |

**Returns:**
[Font](../../com.aspose.drawing/font) - A [Font](../../com.aspose.drawing/font) if the specified name matches a value in [SystemFonts](../../com.aspose.drawing/systemfonts); otherwise, null.
