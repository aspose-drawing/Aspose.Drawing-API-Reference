---
title: Mesuré
second_title: Référence de l'API Aspose.Drawing pour Java
description: Fournit des méthodes mesurées pour l'intégration
type: docs
weight: 10
url: /fr/java/com.aspose.drawing.dynabic.metered/metered/
---
**Inheritance:**
java.lang.Object
```
public class Metered
```

Fournit des méthodes mesurées pour l'intégration

Dans cet exemple, une tentative sera faite pour définir la clé publique et privée mesurée

`// the component jar file: Metered matered = new Metered(); matered.setMeteredKey("PublicKey", "PrivateKey"); `
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Metered()](#Metered--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getConsumptionQuantity()](#getConsumptionQuantity--) | Obtient la taille du fichier de consommation |
| [getConsumptionCredit()](#getConsumptionCredit--) | Obtient le crédit de consommation |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | Définit la clé publique et privée mesurée |
| [equals(Object obj)](#equals-java.lang.Object-) | Détermine si l'objet spécifié est égal à cette instance. |
### Metered() {#Metered--}
```
public Metered()
```


### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static BigDecimal getConsumptionQuantity()
```


Obtient la taille du fichier de consommation

**Returns:**
java.math.BigDecimal - taille du fichier de consommation
### getConsumptionCredit() {#getConsumptionCredit--}
```
public static BigDecimal getConsumptionCredit()
```


Obtient le crédit de consommation

**Returns:**
java.math.BigDecimal - quantité de consommation
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

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Détermine si l'objet spécifié est égal à cette instance.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | L'objet à comparer avec cette instance. |

**Returns:**
booléen - `true` si l'objet spécifié est égal à cette instance ; sinon, `false`.
