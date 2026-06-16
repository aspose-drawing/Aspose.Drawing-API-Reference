---
title: MeteredExt
second_title: Aspose.Drawing voor Java API-referentie
description: Biedt methoden om de gemeten sleutel in te stellen.
type: docs
weight: 33
url: /nl/java/com.aspose.drawing/meteredext/
---
**Inheritance:**
java.lang.Object, [com.aspose.drawing.dynabic.metered.Metered](../../com.aspose.drawing.dynabic.metered/metered)

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public final class MeteredExt extends Metered implements System.IDisposable
```

Biedt methoden om de gemeten sleutel in te stellen.

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
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [MeteredExt()](#MeteredExt--) | Initialiseert een nieuw exemplaar van de [Metered](../../com.aspose.drawing.dynabic.metered/metered) klasse. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getConsumptionQuantity()](#getConsumptionQuantity--) | Haalt de bestandsgrootte van het verbruik op. |
| [getConsumptionCredit()](#getConsumptionCredit--) | Haalt het verbruikskrediet op. |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | Stelt de gemeten openbare en privésleutel in |
| [dispose()](#dispose--) | Voert door de toepassing gedefinieerde taken uit die verband houden met het vrijgeven, loslaten of opnieuw instellen van niet-beheerde bronnen. |
### MeteredExt() {#MeteredExt--}
```
public MeteredExt()
```


Initialiseert een nieuw exemplaar van de [Metered](../../com.aspose.drawing.dynabic.metered/metered) klasse.

### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static BigDecimal getConsumptionQuantity()
```


Haalt de bestandsgrootte van het verbruik op.

**Returns:**
java.math.BigDecimal - Retourneert de verbruikshoeveelheid
### getConsumptionCredit() {#getConsumptionCredit--}
```
public static BigDecimal getConsumptionCredit()
```


Haalt het verbruikskrediet op.

**Returns:**
java.math.BigDecimal - Retourneert de verbruikshoeveelheid
### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public void setMeteredKey(String publicKey, String privateKey)
```


Stelt de gemeten openbare en privésleutel in

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| publicKey | java.lang.String | openbare sleutel |
| privateKey | java.lang.String | privésleutel |

### dispose() {#dispose--}
```
public void dispose()
```


Voert door de toepassing gedefinieerde taken uit die verband houden met het vrijgeven, loslaten of opnieuw instellen van niet-beheerde bronnen.

