---
title: PrintPageEventArgs
second_title: Referensi API Aspose.Drawing for Java
description: Menyediakan data untuk peristiwa EPrintDocument.PrintPage.
type: docs
weight: 13
url: /id/java/com.aspose.drawing.printing/printpageeventargs/
---
**Inheritance:**
java.lang.Object
```
public class PrintPageEventArgs
```

Menyediakan data untuk peristiwa `E:PrintDocument.PrintPage`.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [PrintPageEventArgs()](#PrintPageEventArgs--) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getGraphics()](#getGraphics--) | Mendapatkan `Graphics`([.getGraphics](../../null/\#getGraphics)) yang digunakan untuk melukis halaman. |
| [hasMorePages()](#hasMorePages--) | Mendapatkan nilai yang menunjukkan apakah halaman tambahan harus dicetak. |
| [setMorePages(boolean value)](#setMorePages-boolean-) | Mengatur nilai yang menunjukkan apakah halaman tambahan harus dicetak. |
| [getPageSettings()](#getPageSettings--) | Mendapatkan pengaturan halaman untuk halaman saat ini. |
### PrintPageEventArgs() {#PrintPageEventArgs--}
```
public PrintPageEventArgs()
```


### getGraphics() {#getGraphics--}
```
public final Graphics getGraphics()
```


Mendapatkan `Graphics`([.getGraphics](../../null/\#getGraphics)) yang digunakan untuk melukis halaman.

**Returns:**
[Graphics](../../com.aspose.drawing/graphics) - The `Graphics`([.getGraphics](../../null/\#getGraphics)) used to paint the page.
### hasMorePages() {#hasMorePages--}
```
public final boolean hasMorePages()
```


Mendapatkan nilai yang menunjukkan apakah halaman tambahan harus dicetak.

**Returns:**
boolean - `true` jika halaman tambahan harus dicetak; jika tidak, false. Nilai default adalah `false`.
### setMorePages(boolean value) {#setMorePages-boolean-}
```
public final void setMorePages(boolean value)
```


Mengatur nilai yang menunjukkan apakah halaman tambahan harus dicetak.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean | nilai yang menunjukkan apakah halaman tambahan harus dicetak. |

### getPageSettings() {#getPageSettings--}
```
public final PageSettings getPageSettings()
```


Mendapatkan pengaturan halaman untuk halaman saat ini.

**Returns:**
[PageSettings](../../com.aspose.drawing.printing/pagesettings) - The page settings for the current page.
