---
title: MeteredExt
second_title: Aspose.Drawing für Java API-Referenz
description: Stellt Methoden bereit, um den Metered‑Schlüssel festzulegen.
type: docs
weight: 33
url: /de/java/com.aspose.drawing/meteredext/
---
**Inheritance:**
java.lang.Object, [com.aspose.drawing.dynabic.metered.Metered](../../com.aspose.drawing.dynabic.metered/metered)

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public final class MeteredExt extends Metered implements System.IDisposable
```

Stellt Methoden bereit, um den Metered‑Schlüssel festzulegen.

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
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [MeteredExt()](#MeteredExt--) | Initialisiert eine neue Instanz der [Metered](../../com.aspose.drawing.dynabic.metered/metered) Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getConsumptionQuantity()](#getConsumptionQuantity--) | Ermittelt die Dateigröße des Verbrauchs. |
| [getConsumptionCredit()](#getConsumptionCredit--) | Ermittelt das Verbrauchsguthaben. |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | Setzt den metered öffentlichen und privaten Schlüssel |
| [dispose()](#dispose--) | Führt anwendungsspezifische Aufgaben aus, die mit dem Freigeben, Freisetzen oder Zurücksetzen von nicht verwalteten Ressourcen verbunden sind. |
### MeteredExt() {#MeteredExt--}
```
public MeteredExt()
```


Initialisiert eine neue Instanz der [Metered](../../com.aspose.drawing.dynabic.metered/metered) Klasse.

### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static BigDecimal getConsumptionQuantity()
```


Ermittelt die Dateigröße des Verbrauchs.

**Returns:**
java.math.BigDecimal - Gibt die Verbrauchsmenge zurück
### getConsumptionCredit() {#getConsumptionCredit--}
```
public static BigDecimal getConsumptionCredit()
```


Ermittelt das Verbrauchsguthaben.

**Returns:**
java.math.BigDecimal - Gibt die Verbrauchsmenge zurück
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

### dispose() {#dispose--}
```
public void dispose()
```


Führt anwendungsspezifische Aufgaben aus, die mit dem Freigeben, Freisetzen oder Zurücksetzen von nicht verwalteten Ressourcen verbunden sind.

