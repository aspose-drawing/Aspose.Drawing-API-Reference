---
title: PathData
second_title: Αναφορά API του Aspose.Drawing for Java
description: Περιέχει τα γραφικά δεδομένα που αποτελούν ένα αντικείμενο.
type: docs
weight: 35
url: /el/java/com.aspose.drawing.drawing2d/pathdata/
---
**Inheritance:**
java.lang.Object
```
public final class PathData
```

Περιέχει τα γραφικά δεδομένα που αποτελούν ένα αντικείμενο [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath). Αυτή η κλάση δεν μπορεί να κληρονομηθεί.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [PathData()](#PathData--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getPoints()](#getPoints--) | Λαμβάνει έναν πίνακα από δομές [PointF](../../com.aspose.drawing/pointf) που αντιπροσωπεύουν τα σημεία μέσω των οποίων κατασκευάζεται η διαδρομή. |
| [setPoints(PointF[] value)](#setPoints-com.aspose.drawing.PointF---) | Ορίζει έναν πίνακα από δομές [PointF](../../com.aspose.drawing/pointf) που αντιπροσωπεύουν τα σημεία μέσω των οποίων κατασκευάζεται η διαδρομή. |
| [getTypes()](#getTypes--) | Λαμβάνει τους τύπους των αντίστοιχων σημείων στη διαδρομή. |
| [setTypes(byte[] value)](#setTypes-byte---) | Ορίζει τους τύπους των αντίστοιχων σημείων στη διαδρομή. |
### PathData() {#PathData--}
```
public PathData()
```


### getPoints() {#getPoints--}
```
public PointF[] getPoints()
```


Λαμβάνει έναν πίνακα από δομές [PointF](../../com.aspose.drawing/pointf) που αντιπροσωπεύουν τα σημεία μέσω των οποίων κατασκευάζεται η διαδρομή.

Value: TAn πίνακας από αντικείμενα [PointF](../../com.aspose.drawing/pointf) που αντιπροσωπεύουν τα σημεία μέσω των οποίων κατασκευάζεται η διαδρομή.

**Returns:**
com.aspose.drawing.PointF[] - ένας πίνακας από δομές [PointF](../../com.aspose.drawing/pointf) που αντιπροσωπεύουν τα σημεία μέσω των οποίων κατασκευάζεται η διαδρομή.
### setPoints(PointF[] value) {#setPoints-com.aspose.drawing.PointF---}
```
public void setPoints(PointF[] value)
```


Ορίζει έναν πίνακα από δομές [PointF](../../com.aspose.drawing/pointf) που αντιπροσωπεύουν τα σημεία μέσω των οποίων κατασκευάζεται η διαδρομή.

Value: TAn πίνακας από αντικείμενα [PointF](../../com.aspose.drawing/pointf) που αντιπροσωπεύουν τα σημεία μέσω των οποίων κατασκευάζεται η διαδρομή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [PointF\[\]](../../com.aspose.drawing/pointf) | ένας πίνακας από δομές [PointF](../../com.aspose.drawing/pointf) που αντιπροσωπεύουν τα σημεία μέσω των οποίων κατασκευάζεται η διαδρομή. |

### getTypes() {#getTypes--}
```
public byte[] getTypes()
```


Λαμβάνει τους τύπους των αντίστοιχων σημείων στη διαδρομή.

Value: Ένας πίνακας από bytes που καθορίζουν τους τύπους των αντίστοιχων σημείων στη διαδρομή.

**Returns:**
byte[] - οι τύποι των αντίστοιχων σημείων στη διαδρομή.
### setTypes(byte[] value) {#setTypes-byte---}
```
public void setTypes(byte[] value)
```


Ορίζει τους τύπους των αντίστοιχων σημείων στη διαδρομή.

Value: Ένας πίνακας από bytes που καθορίζουν τους τύπους των αντίστοιχων σημείων στη διαδρομή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte[] | the types of the corresponding points in the path. |

