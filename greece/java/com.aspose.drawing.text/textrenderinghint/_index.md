---
title: TextRenderingHint
second_title: Αναφορά API του Aspose.Drawing for Java
description: Specifies the quality of text rendering.
type: docs
weight: 14
url: /el/java/com.aspose.drawing.text/textrenderinghint/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class TextRenderingHint extends System.Enum
```

Specifies the quality of text rendering.
## Fields

| Field | Περιγραφή |
| --- | --- |
| [SystemDefault](#SystemDefault) | Κάθε χαρακτήρας σχεδιάζεται χρησιμοποιώντας το bitmap του glyph του, με την προεπιλεγμένη υπόδειξη απόδοσης του συστήματος. |
| [SingleBitPerPixelGridFit](#SingleBitPerPixelGridFit) | Κάθε χαρακτήρας σχεδιάζεται χρησιμοποιώντας το bitmap του glyph του. |
| [SingleBitPerPixel](#SingleBitPerPixel) | Κάθε χαρακτήρας σχεδιάζεται χρησιμοποιώντας το bitmap του glyph του. |
| [AntiAliasGridFit](#AntiAliasGridFit) | Κάθε χαρακτήρας σχεδιάζεται χρησιμοποιώντας το antialiased bitmap του glyph με υπόδειξη. |
| [AntiAlias](#AntiAlias) | Κάθε χαρακτήρας σχεδιάζεται χρησιμοποιώντας το antialiased bitmap του glyph χωρίς υπόδειξη. |
| [ClearTypeGridFit](#ClearTypeGridFit) | Κάθε χαρακτήρας σχεδιάζεται χρησιμοποιώντας το bitmap ClearType του glyph με υπόδειξη. |
### SystemDefault {#SystemDefault}
```
public static final int SystemDefault
```


Κάθε χαρακτήρας σχεδιάζεται χρησιμοποιώντας το bitmap του glyph, με την προεπιλεγμένη υπόδειξη απόδοσης του συστήματος. Το κείμενο θα σχεδιαστεί χρησιμοποιώντας τις ρυθμίσεις εξομάλυνσης γραμματοσειράς που έχει επιλέξει ο χρήστης για το σύστημα.

### SingleBitPerPixelGridFit {#SingleBitPerPixelGridFit}
```
public static final int SingleBitPerPixelGridFit
```


Κάθε χαρακτήρας σχεδιάζεται χρησιμοποιώντας το bitmap του glyph. Η υπόδειξη χρησιμοποιείται για τη βελτίωση της εμφάνισης των χαρακτήρων σε στελέχη και καμπυλότητες.

### SingleBitPerPixel {#SingleBitPerPixel}
```
public static final int SingleBitPerPixel
```


Κάθε χαρακτήρας σχεδιάζεται χρησιμοποιώντας το bitmap γλύφου του. Η υποδείξη δεν χρησιμοποιείται.

### AntiAliasGridFit {#AntiAliasGridFit}
```
public static final int AntiAliasGridFit
```


Κάθε χαρακτήρας σχεδιάζεται χρησιμοποιώντας το antialiased bitmap γλύφου του με υποδείξη. Πολλά καλύτερη ποιότητα λόγω antialiasing, αλλά με υψηλότερο κόστος απόδοσης.

### AntiAlias {#AntiAlias}
```
public static final int AntiAlias
```


Κάθε χαρακτήρας σχεδιάζεται χρησιμοποιώντας το antialiased bitmap γλύφου του χωρίς υποδείξη. Καλύτερη ποιότητα λόγω antialiasing. Οι διαφορές στο πλάτος των στελεχών μπορεί να είναι εμφανείς επειδή η υποδείξη είναι απενεργοποιημένη.

### ClearTypeGridFit {#ClearTypeGridFit}
```
public static final int ClearTypeGridFit
```


Κάθε χαρακτήρας σχεδιάζεται χρησιμοποιώντας το glyph ClearType bitmap του με υποδείξη. Η ρύθμιση με την υψηλότερη ποιότητα. Χρησιμοποιείται για να εκμεταλλευτεί τις δυνατότητες γραμματοσειράς ClearType.

