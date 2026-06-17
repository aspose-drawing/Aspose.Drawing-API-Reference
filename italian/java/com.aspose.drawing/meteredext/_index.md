---
title: MeteredExt
second_title: Riferimento API di Aspose.Drawing per Java
description: Fornisce metodi per impostare la chiave misurata.
type: docs
weight: 33
url: /it/java/com.aspose.drawing/meteredext/
---
**Inheritance:**
java.lang.Object, [com.aspose.drawing.dynabic.metered.Metered](../../com.aspose.drawing.dynabic.metered/metered)

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public final class MeteredExt extends Metered implements System.IDisposable
```

Fornisce metodi per impostare la chiave misurata.

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
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [MeteredExt()](#MeteredExt--) | Inizializza una nuova istanza della classe [Metered](../../com.aspose.drawing.dynabic.metered/metered). |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getConsumptionQuantity()](#getConsumptionQuantity--) | Ottiene la dimensione del file di consumo. |
| [getConsumptionCredit()](#getConsumptionCredit--) | Ottiene il credito di consumo. |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | Imposta la chiave pubblica e privata del metered |
| [dispose()](#dispose--) | Esegue attività definite dall'applicazione associate al rilascio, alla liberazione o al reset delle risorse non gestite. |
### MeteredExt() {#MeteredExt--}
```
public MeteredExt()
```


Inizializza una nuova istanza della classe [Metered](../../com.aspose.drawing.dynabic.metered/metered).

### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static BigDecimal getConsumptionQuantity()
```


Ottiene la dimensione del file di consumo.

**Returns:**
java.math.BigDecimal - Restituisce la quantità di consumo
### getConsumptionCredit() {#getConsumptionCredit--}
```
public static BigDecimal getConsumptionCredit()
```


Ottiene il credito di consumo.

**Returns:**
java.math.BigDecimal - Restituisce la quantità di consumo
### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public void setMeteredKey(String publicKey, String privateKey)
```


Imposta la chiave pubblica e privata del metered

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| publicKey | java.lang.String | chiave pubblica |
| privateKey | java.lang.String | chiave privata |

### dispose() {#dispose--}
```
public void dispose()
```


Esegue attività definite dall'applicazione associate al rilascio, alla liberazione o al reset delle risorse non gestite.

