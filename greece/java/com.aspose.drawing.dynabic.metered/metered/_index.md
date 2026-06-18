---
title: Μετρημένο
second_title: Αναφορά API του Aspose.Drawing for Java
description: Provides metered methods for integration
type: docs
weight: 10
url: /el/java/com.aspose.drawing.dynabic.metered/metered/
---
**Inheritance:**
java.lang.Object
```
public class Metered
```

Provides metered methods for integration

Σε αυτό το παράδειγμα, θα γίνει προσπάθεια να οριστούν το δημόσιο και το ιδιωτικό κλειδί του metered

`// το αρχείο jar του component: Metered matered = new Metered(); matered.setMeteredKey("PublicKey", "PrivateKey"); `
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [Metered()](#Metered--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getConsumptionQuantity()](#getConsumptionQuantity--) | Λαμβάνει το μέγεθος του αρχείου κατανάλωσης |
| [getConsumptionCredit()](#getConsumptionCredit--) | Λαμβάνει την πίστωση κατανάλωσης |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | Ορίζει το μετρημένο δημόσιο και ιδιωτικό κλειδί. |
| [equals(Object obj)](#equals-java.lang.Object-) | Καθορίζει αν το καθορισμένο Object είναι ίσο με αυτήν την instance. |
### Metered() {#Metered--}
```
public Metered()
```


### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static BigDecimal getConsumptionQuantity()
```


Λαμβάνει το μέγεθος του αρχείου κατανάλωσης

**Returns:**
java.math.BigDecimal - μέγεθος αρχείου κατανάλωσης
### getConsumptionCredit() {#getConsumptionCredit--}
```
public static BigDecimal getConsumptionCredit()
```


Λαμβάνει την πίστωση κατανάλωσης

**Returns:**
java.math.BigDecimal - ποσότητα κατανάλωσης
### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public void setMeteredKey(String publicKey, String privateKey)
```


Ορίζει το μετρημένο δημόσιο και ιδιωτικό κλειδί.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| publicKey | java.lang.String | δημόσιο κλειδί |
| privateKey | java.lang.String | ιδιωτικό κλειδί |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Καθορίζει αν το καθορισμένο Object είναι ίσο με αυτήν την instance.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | java.lang.Object | Το Object για σύγκριση με αυτήν την παρουσία. |

**Returns:**
boolean - `true` εάν το συγκεκριμένο Object είναι ίσο με αυτήν την παρουσία· διαφορετικά, `false`.
