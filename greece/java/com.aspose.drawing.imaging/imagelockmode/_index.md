---
title: ImageLockMode
second_title: Αναφορά API του Aspose.Drawing for Java
description: Καθορίζει τις σημαίες που περνιούνται στην παράμετρο flags της μεθόδου.
type: docs
weight: 28
url: /el/java/com.aspose.drawing.imaging/imagelockmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ImageLockMode extends System.Enum
```

Καθορίζει τις σημαίες που περνιούνται στην παράμετρο flags της μεθόδου [Bitmap.lockBits(Rectangle, int, int)](../../com.aspose.drawing/bitmap\#lockBits-Rectangle--int--int-). Η μέθοδος [Bitmap.lockBits(Rectangle, int, int)](../../com.aspose.drawing/bitmap\#lockBits-Rectangle--int--int-) κλειδώνει ένα τμήμα της εικόνας ώστε να μπορείτε να διαβάσετε ή να γράψετε τα δεδομένα εικονοστοιχείου.
## Fields

| Field | Περιγραφή |
| --- | --- |
| [ReadOnly](#ReadOnly) | Καθορίζει ότι ένα τμήμα της εικόνας είναι κλειδωμένο για ανάγνωση. |
| [WriteOnly](#WriteOnly) | Καθορίζει ότι ένα τμήμα της εικόνας είναι κλειδωμένο για εγγραφή. |
| [ReadWrite](#ReadWrite) | Καθορίζει ότι ένα τμήμα της εικόνας είναι κλειδωμένο για ανάγνωση ή εγγραφή. |
| [UserInputBuffer](#UserInputBuffer) | Καθορίζει ότι το buffer που χρησιμοποιείται για την ανάγνωση ή την εγγραφή δεδομένων εικονοστοιχείου εκχωρείται από τον χρήστη. |
### ReadOnly {#ReadOnly}
```
public static final int ReadOnly
```


Καθορίζει ότι ένα τμήμα της εικόνας είναι κλειδωμένο για ανάγνωση.

### WriteOnly {#WriteOnly}
```
public static final int WriteOnly
```


Καθορίζει ότι ένα τμήμα της εικόνας είναι κλειδωμένο για εγγραφή.

### ReadWrite {#ReadWrite}
```
public static final int ReadWrite
```


Καθορίζει ότι ένα τμήμα της εικόνας είναι κλειδωμένο για ανάγνωση ή εγγραφή.

### UserInputBuffer {#UserInputBuffer}
```
public static final int UserInputBuffer
```


Καθορίζει ότι το buffer που χρησιμοποιείται για την ανάγνωση ή την εγγραφή δεδομένων εικονοστοιχείου εκχωρείται από τον χρήστη. Εάν αυτή η σημαία είναι ορισμένη, η παράμετρος `flags` της μεθόδου [Bitmap.lockBits(Rectangle, int, int)](../../com.aspose.drawing/bitmap\#lockBits-Rectangle--int--int-) λειτουργεί ως παράμετρος εισόδου (και ενδεχομένως ως παράμετρος εξόδου). Εάν αυτή η σημαία είναι καθαρισμένη, τότε η παράμετρος `flags` λειτουργεί μόνο ως παράμετρος εξόδου.

