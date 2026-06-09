---
title: DrawingSettings
second_title: Referensi API Aspose.Drawing for Java
description: Memungkinkan penyesuaian perilaku pustaka gambar bila menggunakan beberapa fitur yang belum sepenuhnya diimplementasikan.
type: docs
weight: 19
url: /id/java/com.aspose.drawing/drawingsettings/
---
**Inheritance:**
java.lang.Object
```
public final class DrawingSettings
```

Memungkinkan penyesuaian perilaku pustaka gambar bila menggunakan beberapa fitur yang belum sepenuhnya diimplementasikan.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [DrawingSettings()](#DrawingSettings--) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getStrictMode()](#getStrictMode--) | Mendapatkan nilai yang menunjukkan apakah penangkapan lebih ketat terhadap fitur yang belum diimplementasikan diaktifkan. |
| [setStrictMode(boolean value)](#setStrictMode-boolean-) | Mengatur nilai yang menunjukkan apakah penangkapan lebih ketat terhadap fitur yang belum diimplementasikan diaktifkan. |
### DrawingSettings() {#DrawingSettings--}
```
public DrawingSettings()
```


### getStrictMode() {#getStrictMode--}
```
public static boolean getStrictMode()
```


Mendapatkan nilai yang menunjukkan apakah penangkapan lebih ketat terhadap fitur yang belum diimplementasikan diaktifkan.

--------------------

Jika disetel ke true, dalam kasus penggunaan fitur/parameter yang tidak berfungsi dengan benar dalam implementasi saat ini, perpustakaan akan melempar NotImplementedException. Jika disetel ke false, beberapa parameter dapat diabaikan untuk memberi kesempatan program pengguna berjalan. Dalam hal ini hasil gambar mungkin terlihat berbeda dibandingkan dengan GDI+.

**Returns:**
boolean - nilai yang menunjukkan apakah penangkapan lebih ketat terhadap fitur yang belum diimplementasikan diaktifkan.
### setStrictMode(boolean value) {#setStrictMode-boolean-}
```
public static void setStrictMode(boolean value)
```


Mengatur nilai yang menunjukkan apakah penangkapan lebih ketat terhadap fitur yang belum diimplementasikan diaktifkan.

--------------------

Jika disetel ke true, dalam kasus penggunaan fitur/parameter yang tidak berfungsi dengan benar dalam implementasi saat ini, perpustakaan akan melempar NotImplementedException. Jika disetel ke false, beberapa parameter dapat diabaikan untuk memberi kesempatan program pengguna berjalan. Dalam hal ini hasil gambar mungkin terlihat berbeda dibandingkan dengan GDI+.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean | nilai yang menunjukkan apakah penangkapan lebih ketat terhadap fitur yang belum diimplementasikan diaktifkan. |

