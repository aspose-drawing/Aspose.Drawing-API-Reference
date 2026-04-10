---
title: MeteredExt
second_title: Αναφορά API του Aspose.Drawing for Java
description: Provides methods to set metered key.
type: docs
weight: 33
url: /el/java/com.aspose.drawing/meteredext/
---
**Inheritance:**
java.lang.Object, [com.aspose.drawing.dynabic.metered.Metered](../../com.aspose.drawing.dynabic.metered/metered)

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public final class MeteredExt extends Metered implements System.IDisposable
```

Provides methods to set metered key.

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
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [MeteredExt()](#MeteredExt--) | Αρχικοποιεί μια νέα παρουσία της κλάσης [Metered](../../com.aspose.drawing.dynabic.metered/metered). |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getConsumptionQuantity()](#getConsumptionQuantity--) | Λαμβάνει το μέγεθος αρχείου κατανάλωσης. |
| [getConsumptionCredit()](#getConsumptionCredit--) | Λαμβάνει το πιστωτικό ποσό κατανάλωσης. |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | Ορίζει το μετρημένο δημόσιο και ιδιωτικό κλειδί. |
| [dispose()](#dispose--) | Εκτελεί εργασίες ορισμένες από την εφαρμογή που σχετίζονται με την απελευθέρωση, την αποδέσμευση ή την επαναφορά μη διαχειριζόμενων πόρων. |
### MeteredExt() {#MeteredExt--}
```
public MeteredExt()
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [Metered](../../com.aspose.drawing.dynabic.metered/metered).

### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static BigDecimal getConsumptionQuantity()
```


Λαμβάνει το μέγεθος αρχείου κατανάλωσης.

**Returns:**
java.math.BigDecimal - Επιστρέφει την ποσότητα κατανάλωσης
### getConsumptionCredit() {#getConsumptionCredit--}
```
public static BigDecimal getConsumptionCredit()
```


Λαμβάνει το πιστωτικό ποσό κατανάλωσης.

**Returns:**
java.math.BigDecimal - Επιστρέφει την ποσότητα κατανάλωσης
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

### dispose() {#dispose--}
```
public void dispose()
```


Εκτελεί εργασίες ορισμένες από την εφαρμογή που σχετίζονται με την απελευθέρωση, την αποδέσμευση ή την επαναφορά μη διαχειριζόμενων πόρων.

