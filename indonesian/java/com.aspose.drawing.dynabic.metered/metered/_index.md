---
title: Metered
second_title: Referensi API Aspose.Drawing for Java
description: Menyediakan metode bermeter untuk integrasi.
type: docs
weight: 10
url: /id/java/com.aspose.drawing.dynabic.metered/metered/
---
**Inheritance:**
java.lang.Object
```
public class Metered
```

Menyediakan metode bermeter untuk integrasi.

Dalam contoh ini, akan dilakukan percobaan untuk mengatur kunci publik dan privat metered

`// the component jar file: Metered matered = new Metered(); matered.setMeteredKey("PublicKey", "PrivateKey"); `
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [Metered()](#Metered--) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getConsumptionQuantity()](#getConsumptionQuantity--) | Mendapatkan ukuran file konsumsi |
| [getConsumptionCredit()](#getConsumptionCredit--) | Mendapatkan kredit konsumsi |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | Mengatur kunci publik dan privat metered |
| [equals(Object obj)](#equals-java.lang.Object-) | Menentukan apakah Objek yang ditentukan, sama dengan instance ini. |
### Metered() {#Metered--}
```
public Metered()
```


### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static BigDecimal getConsumptionQuantity()
```


Mendapatkan ukuran file konsumsi

**Returns:**
java.math.BigDecimal - ukuran file konsumsi
### getConsumptionCredit() {#getConsumptionCredit--}
```
public static BigDecimal getConsumptionCredit()
```


Mendapatkan kredit konsumsi

**Returns:**
java.math.BigDecimal - kuantitas konsumsi
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

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Menentukan apakah Objek yang ditentukan, sama dengan instance ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | java.lang.Object | Objek untuk dibandingkan dengan instance ini. |

**Returns:**
boolean - `true` jika Objek yang ditentukan sama dengan instance ini; jika tidak, `false`.
