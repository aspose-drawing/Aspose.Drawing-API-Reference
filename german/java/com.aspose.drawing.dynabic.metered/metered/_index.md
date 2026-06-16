---
title: Gemessen
second_title: Aspose.Drawing für Java API-Referenz
description: Bietet gemessene Methoden für die Integration.
type: docs
weight: 10
url: /de/java/com.aspose.drawing.dynabic.metered/metered/
---
**Inheritance:**
java.lang.Object
```
public class Metered
```

Bietet gemessene Methoden für die Integration.

In diesem Beispiel wird versucht, den gemessenen öffentlichen und privaten Schlüssel festzulegen

`// the component jar file: Metered matered = new Metered(); matered.setMeteredKey("PublicKey", "PrivateKey"); `
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Metered()](#Metered--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getConsumptionQuantity()](#getConsumptionQuantity--) | Ermittelt die Dateigröße des Verbrauchs |
| [getConsumptionCredit()](#getConsumptionCredit--) | Ermittelt das Verbrauchsguthaben |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | Setzt den metered öffentlichen und privaten Schlüssel |
| [equals(Object obj)](#equals-java.lang.Object-) | Bestimmt, ob das angegebene Objekt dieser Instanz gleich ist. |
### Metered() {#Metered--}
```
public Metered()
```


### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static BigDecimal getConsumptionQuantity()
```


Ermittelt die Dateigröße des Verbrauchs

**Returns:**
java.math.BigDecimal - Verbrauchsdateigröße
### getConsumptionCredit() {#getConsumptionCredit--}
```
public static BigDecimal getConsumptionCredit()
```


Ermittelt das Verbrauchsguthaben

**Returns:**
java.math.BigDecimal - Verbrauchsmenge
### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public void setMeteredKey(String publicKey, String privateKey)
```


Setzt den metered öffentlichen und privaten Schlüssel

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| publicKey | java.lang.String | öffentlicher Schlüssel |
| privateKey | java.lang.String | privater Schlüssel |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bestimmt, ob das angegebene Objekt dieser Instanz gleich ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | java.lang.Object | Das Objekt zum Vergleich mit dieser Instanz. |

**Returns:**
boolean - `true`, wenn das angegebene Objekt dieser Instanz gleich ist; andernfalls `false`.
