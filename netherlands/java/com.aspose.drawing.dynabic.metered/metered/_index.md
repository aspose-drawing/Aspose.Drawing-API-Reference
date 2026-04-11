---
title: Metered
second_title: Aspose.Drawing voor Java API-referentie
description: Biedt gemeten methoden voor integratie
type: docs
weight: 10
url: /nl/java/com.aspose.drawing.dynabic.metered/metered/
---
**Inheritance:**
java.lang.Object
```
public class Metered
```

Biedt gemeten methoden voor integratie

In dit voorbeeld wordt geprobeerd om de metered publieke en private sleutel in te stellen

`// the component jar file: Metered matered = new Metered(); materd.setMeteredKey("PublicKey", "PrivateKey"); `
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [Metered()](#Metered--) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getConsumptionQuantity()](#getConsumptionQuantity--) | Haalt bestandsgrootte van verbruik op |
| [getConsumptionCredit()](#getConsumptionCredit--) | Haalt verbruikskrediet op |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | Stelt de gemeten openbare en privésleutel in |
| [equals(Object obj)](#equals-java.lang.Object-) | Bepaalt of het opgegeven Object gelijk is aan deze instantie. |
### Metered() {#Metered--}
```
public Metered()
```


### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static BigDecimal getConsumptionQuantity()
```


Haalt bestandsgrootte van verbruik op

**Returns:**
java.math.BigDecimal - verbruik bestandsgrootte
### getConsumptionCredit() {#getConsumptionCredit--}
```
public static BigDecimal getConsumptionCredit()
```


Haalt verbruikskrediet op

**Returns:**
java.math.BigDecimal - verbruik hoeveelheid
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

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bepaalt of het opgegeven Object gelijk is aan deze instantie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | java.lang.Object | Het Object om te vergelijken met deze instantie. |

**Returns:**
boolean - `true` als het opgegeven Object gelijk is aan deze instantie; anders `false`.
