---
title: PageSettings
second_title: Referensi API Aspose.Drawing for Java
description: Menentukan pengaturan yang berlaku untuk satu halaman cetak.
type: docs
weight: 10
url: /id/java/com.aspose.drawing.printing/pagesettings/
---
**Inheritance:**
java.lang.Object
```
public class PageSettings
```

Menentukan pengaturan yang berlaku untuk satu halaman tercetak.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [PageSettings()](#PageSettings--) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getBounds()](#getBounds--) | Mengambil ukuran halaman, dengan mempertimbangkan orientasi halaman yang ditentukan oleh properti [PageSettings](../../com.aspose.drawing.printing/pagesettings). |
| [getHardMarginX()](#getHardMarginX--) | Mendapatkan koordinat x, dalam satuan seratus bagian inci, dari margin keras di sisi kiri halaman. |
| [getHardMarginY()](#getHardMarginY--) | Mendapatkan koordinat y, dalam satuan seratus bagian inci, dari margin keras di bagian atas halaman. |
| [getPrinterResolution()](#getPrinterResolution--) | Mendapatkan resolusi printer untuk halaman. |
### PageSettings() {#PageSettings--}
```
public PageSettings()
```


### getBounds() {#getBounds--}
```
public final Rectangle getBounds()
```


Mengambil ukuran halaman, dengan mempertimbangkan orientasi halaman yang ditentukan oleh properti [PageSettings](../../com.aspose.drawing.printing/pagesettings).

**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle) - A [Rectangle](../../com.aspose.drawing/rectangle) that represents the length and width, in hundredths of an inch, of the page.
### getHardMarginX() {#getHardMarginX--}
```
public final float getHardMarginX()
```


Mendapatkan koordinat x, dalam satuan seratus bagian inci, dari margin keras di sisi kiri halaman.

**Returns:**
float - Koordinat x, dalam satuan seratus bagian inci, dari margin keras sebelah kiri.
### getHardMarginY() {#getHardMarginY--}
```
public final float getHardMarginY()
```


Mendapatkan koordinat y, dalam satuan seratus bagian inci, dari margin keras di bagian atas halaman.

**Returns:**
float - Koordinat y, dalam satuan seratus bagian inci, dari margin keras di bagian atas halaman.
### getPrinterResolution() {#getPrinterResolution--}
```
public final PrinterResolution getPrinterResolution()
```


Mendapatkan resolusi printer untuk halaman.

**Returns:**
[PrinterResolution](../../com.aspose.drawing.printing/printerresolution) - A `PrinterResolution`([.getPrinterResolution](../../null/\#getPrinterResolution)) that specifies the printer resolution for the page. The default is the printer's default resolution.
