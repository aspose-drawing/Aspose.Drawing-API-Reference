---
title: MeteredExt
second_title: Référence de l'API Aspose.Drawing pour Java
description: Fournit des méthodes pour définir la clé mesurée.
type: docs
weight: 33
url: /fr/java/com.aspose.drawing/meteredext/
---
**Inheritance:**
java.lang.Object, [com.aspose.drawing.dynabic.metered.Metered](../../com.aspose.drawing.dynabic.metered/metered)

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public final class MeteredExt extends Metered implements System.IDisposable
```

Fournit des méthodes pour définir la clé mesurée.

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
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [MeteredExt()](#MeteredExt--) | Initialise une nouvelle instance de la classe [Metered](../../com.aspose.drawing.dynabic.metered/metered). |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getConsumptionQuantity()](#getConsumptionQuantity--) | Obtient la taille du fichier de consommation. |
| [getConsumptionCredit()](#getConsumptionCredit--) | Obtient le crédit de consommation. |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | Définit la clé publique et privée mesurée |
| [dispose()](#dispose--) | Effectue les tâches définies par l'application associées à la libération, la remise ou la réinitialisation des ressources non gérées. |
### MeteredExt() {#MeteredExt--}
```
public MeteredExt()
```


Initialise une nouvelle instance de la classe [Metered](../../com.aspose.drawing.dynabic.metered/metered).

### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static BigDecimal getConsumptionQuantity()
```


Obtient la taille du fichier de consommation.

**Returns:**
java.math.BigDecimal - Retourne la quantité de consommation
### getConsumptionCredit() {#getConsumptionCredit--}
```
public static BigDecimal getConsumptionCredit()
```


Obtient le crédit de consommation.

**Returns:**
java.math.BigDecimal - Retourne la quantité de consommation
### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public void setMeteredKey(String publicKey, String privateKey)
```


Définit la clé publique et privée mesurée

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| publicKey | java.lang.String | clé publique |
| privateKey | java.lang.String | clé privée |

### dispose() {#dispose--}
```
public void dispose()
```


Effectue les tâches définies par l'application associées à la libération, la remise ou la réinitialisation des ressources non gérées.

