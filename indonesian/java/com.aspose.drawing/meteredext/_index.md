---
title: MeteredExt
second_title: Referensi API Aspose.Drawing for Java
description: Menyediakan metode untuk mengatur kunci bermeter.
type: docs
weight: 33
url: /id/java/com.aspose.drawing/meteredext/
---
**Inheritance:**
java.lang.Object, [com.aspose.drawing.dynabic.metered.Metered](../../com.aspose.drawing.dynabic.metered/metered)

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public final class MeteredExt extends Metered implements System.IDisposable
```

Menyediakan metode untuk mengatur kunci bermeter.

--------------------

> ```
> In this example, an attempt will be made to set metered public and private key
>  
>  `
>  
>  [C#]
>  Metered matered = new Metered();
>  matered.SetMeteredKey("PublicKey", "PrivateKey");
>  [Visual Basic]
>  Dim matered As Metered = New Metered
>  matered.SetMeteredKey("PublicKey", "PrivateKey")
>  
>  `
>  
>  `
>  the component jar file:
>  
>  Metered matered = new Metered();
>  matered.setMeteredKey("PublicKey", "PrivateKey");
>  
>  `
> ```
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [MeteredExt()](#MeteredExt--) | Menginisialisasi instance baru dari kelas [Metered](../../com.aspose.drawing.dynabic.metered/metered). |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getConsumptionQuantity()](#getConsumptionQuantity--) | Mendapatkan ukuran file konsumsi. |
| [getConsumptionCredit()](#getConsumptionCredit--) | Mendapatkan kredit konsumsi. |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | Mengatur kunci publik dan privat metered |
| [dispose()](#dispose--) | Melakukan tugas yang ditentukan aplikasi terkait dengan membebaskan, melepaskan, atau mereset sumber daya yang tidak dikelola. |
### MeteredExt() {#MeteredExt--}
```
public MeteredExt()
```


Menginisialisasi instance baru dari kelas [Metered](../../com.aspose.drawing.dynabic.metered/metered).

### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static BigDecimal getConsumptionQuantity()
```


Mendapatkan ukuran file konsumsi.

**Returns:**
java.math.BigDecimal - Mengembalikan kuantitas konsumsi
### getConsumptionCredit() {#getConsumptionCredit--}
```
public static BigDecimal getConsumptionCredit()
```


Mendapatkan kredit konsumsi.

**Returns:**
java.math.BigDecimal - Mengembalikan kuantitas konsumsi
### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public void setMeteredKey(String publicKey, String privateKey)
```


Mengatur kunci publik dan privat metered

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| publicKey | java.lang.String | kunci publik |
| privateKey | java.lang.String | kunci privat |

### dispose() {#dispose--}
```
public void dispose()
```


Melakukan tugas yang ditentukan aplikasi terkait dengan membebaskan, melepaskan, atau mereset sumber daya yang tidak dikelola.

