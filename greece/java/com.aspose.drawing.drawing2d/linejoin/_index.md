---
title: LineJoin
second_title: Αναφορά API του Aspose.Drawing for Java
description: Καθορίζει πώς να ενώνονται διαδοχικά τμήματα γραμμής ή καμπύλης σε υποδιαδρομή σχήματος που περιέχεται σε αντικείμενο GraphicsPath.
type: docs
weight: 30
url: /el/java/com.aspose.drawing.drawing2d/linejoin/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class LineJoin extends System.Enum
```

Καθορίζει πώς να συνδέονται διαδοχικά τμήματα γραμμής ή καμπύλης σε ένα σχήμα (υποδιαδρομή) που περιέχεται σε αντικείμενο GraphicsPath.
## Fields

| Field | Περιγραφή |
| --- | --- |
| [Miter](#Miter) | Καθορίζει μια ένωση τύπου mitered. |
| [Bevel](#Bevel) | Καθορίζει μια ένωση τύπου beveled. |
| [Round](#Round) | Καθορίζει μια ένωση τύπου circular. |
| [MiterClipped](#MiterClipped) | Καθορίζει μια ένωση τύπου mitered. |
### Miter {#Miter}
```
public static final int Miter
```


Καθορίζει μια ένωση τύπου mitered. Αυτό δημιουργεί μια αιχμηρή γωνία ή μια αποκομμένη γωνία, ανάλογα με το αν το μήκος του μύτη υπερβαίνει το όριο του μύτη.

--------------------

Προς το παρόν η ένωση Miter λειτουργεί στην πραγματικότητα ως MiterClipped.

### Bevel {#Bevel}
```
public static final int Bevel
```


Καθορίζει μια ένωση τύπου beveled. Αυτό δημιουργεί μια διαγώνια γωνία.

### Round {#Round}
```
public static final int Round
```


Καθορίζει μια ένωση τύπου circular. Αυτό δημιουργεί μια ομαλή, κυκλική καμπύλη μεταξύ των γραμμών.

### MiterClipped {#MiterClipped}
```
public static final int MiterClipped
```


Καθορίζει μια ένωση τύπου mitered. Αυτό δημιουργεί μια αιχμηρή γωνία ή μια λοξή γωνία, ανάλογα με το αν το μήκος του μύτη υπερβαίνει το όριο του μύτη.

