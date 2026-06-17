---
title: MeteredExt
second_title: Aspose.Drawing för Java API‑referens
description: Tillhandahåller metoder för att ställa in mätad nyckel.
type: docs
weight: 33
url: /sv/java/com.aspose.drawing/meteredext/
---
**Inheritance:**
java.lang.Object, [com.aspose.drawing.dynabic.metered.Metered](../../com.aspose.drawing.dynabic.metered/metered)

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public final class MeteredExt extends Metered implements System.IDisposable
```

Tillhandahåller metoder för att ställa in mätad nyckel.

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
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [MeteredExt()](#MeteredExt--) | Initierar en ny instans av klassen [Metered](../../com.aspose.drawing.dynabic.metered/metered). |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getConsumptionQuantity()](#getConsumptionQuantity--) | Hämtar förbrukningsfilens storlek. |
| [getConsumptionCredit()](#getConsumptionCredit--) | Hämtar förbrukningskredit. |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | Ställer in mätad offentlig och privat nyckel |
| [dispose()](#dispose--) | Utför applikationsdefinierade uppgifter som är relaterade till att frigöra, släppa eller återställa ohanterade resurser. |
### MeteredExt() {#MeteredExt--}
```
public MeteredExt()
```


Initierar en ny instans av klassen [Metered](../../com.aspose.drawing.dynabic.metered/metered).

### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static BigDecimal getConsumptionQuantity()
```


Hämtar förbrukningsfilens storlek.

**Returns:**
java.math.BigDecimal - Returnerar förbrukningskvantitet
### getConsumptionCredit() {#getConsumptionCredit--}
```
public static BigDecimal getConsumptionCredit()
```


Hämtar förbrukningskredit.

**Returns:**
java.math.BigDecimal - Returnerar förbrukningskvantitet
### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public void setMeteredKey(String publicKey, String privateKey)
```


Ställer in mätad offentlig och privat nyckel

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| publicKey | java.lang.String | offentlig nyckel |
| privateKey | java.lang.String | privat nyckel |

### dispose() {#dispose--}
```
public void dispose()
```


Utför applikationsdefinierade uppgifter som är relaterade till att frigöra, släppa eller återställa ohanterade resurser.

