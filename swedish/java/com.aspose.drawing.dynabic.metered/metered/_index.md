---
title: Måttad
second_title: Aspose.Drawing för Java API‑referens
description: Tillhandahåller mätade metoder för integration
type: docs
weight: 10
url: /sv/java/com.aspose.drawing.dynabic.metered/metered/
---
**Inheritance:**
java.lang.Object
```
public class Metered
```

Tillhandahåller mätade metoder för integration

I det här exemplet kommer ett försök att ställa in den meterade offentliga och privata nyckeln.

`// komponentens jar-fil: Metered matered = new Metered(); matered.setMeteredKey("PublicKey", "PrivateKey"); `
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [Metered()](#Metered--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getConsumptionQuantity()](#getConsumptionQuantity--) | Hämtar förbrukningsfilens storlek |
| [getConsumptionCredit()](#getConsumptionCredit--) | Hämtar förbrukningskredit |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | Ställer in mätad offentlig och privat nyckel |
| [equals(Object obj)](#equals-java.lang.Object-) | Avgör om det angivna Object är lika med denna instans. |
### Metered() {#Metered--}
```
public Metered()
```


### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static BigDecimal getConsumptionQuantity()
```


Hämtar förbrukningsfilens storlek

**Returns:**
java.math.BigDecimal - förbrukningsfilens storlek
### getConsumptionCredit() {#getConsumptionCredit--}
```
public static BigDecimal getConsumptionCredit()
```


Hämtar förbrukningskredit

**Returns:**
java.math.BigDecimal - förbrukningskvantitet
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

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Avgör om det angivna Object är lika med denna instans.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | java.lang.Object | Objektet att jämföra med denna instans. |

**Returns:**
boolean - `true` om det angivna objektet är lika med denna instans; annars `false`.
