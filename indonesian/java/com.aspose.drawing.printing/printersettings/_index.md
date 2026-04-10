---
title: PrinterSettings
second_title: Referensi API Aspose.Drawing for Java
description: Menentukan informasi tentang cara dokumen dicetak termasuk printer yang mencetaknya saat mencetak dari aplikasi Windows Forms.
type: docs
weight: 16
url: /id/java/com.aspose.drawing.printing/printersettings/
---
**Inheritance:**
java.lang.Object
```
public class PrinterSettings
```

Menentukan informasi tentang bagaimana dokumen dicetak, termasuk printer yang mencetaknya, saat mencetak dari aplikasi Windows Forms.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [PrinterSettings()](#PrinterSettings--) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getFromPage()](#getFromPage--) | Mendapatkan nomor halaman dari halaman pertama yang akan dicetak. |
| [getPrintRange()](#getPrintRange--) | Mendapatkan nomor halaman yang telah ditentukan pengguna untuk dicetak. |
| [getToPage()](#getToPage--) | Mendapatkan nomor halaman terakhir yang akan dicetak. |
| [getPrinterName()](#getPrinterName--) | Mendapatkan nama printer yang akan digunakan. |
| [setPrinterName(String value)](#setPrinterName-java.lang.String-) | Mengatur nama printer yang akan digunakan. |
### PrinterSettings() {#PrinterSettings--}
```
public PrinterSettings()
```


### getFromPage() {#getFromPage--}
```
public static int getFromPage()
```


Mendapatkan nomor halaman dari halaman pertama yang akan dicetak.

**Returns:**
int - Nomor halaman dari halaman pertama yang akan dicetak.
### getPrintRange() {#getPrintRange--}
```
public static int getPrintRange()
```


Mendapatkan nomor halaman yang telah ditentukan pengguna untuk dicetak.

**Returns:**
int - Salah satu nilai `PrintRange`([.getPrintRange](../../null/\#getPrintRange)).
### getToPage() {#getToPage--}
```
public static int getToPage()
```


Mendapatkan nomor halaman terakhir yang akan dicetak.

**Returns:**
int - Nomor halaman terakhir yang akan dicetak.
### getPrinterName() {#getPrinterName--}
```
public final String getPrinterName()
```


Mendapatkan nama printer yang akan digunakan.

**Returns:**
java.lang.String - Nama printer yang akan digunakan.
### setPrinterName(String value) {#setPrinterName-java.lang.String-}
```
public final void setPrinterName(String value)
```


Mengatur nama printer yang akan digunakan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String | nama printer yang akan digunakan. |

