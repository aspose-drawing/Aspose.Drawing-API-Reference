---
title: GraphicsPathIterator
second_title: Αναφορά API του Aspose.Drawing for Java
description: Provides the ability to iterate through subpaths in a  and test the types of shapes contained in each subpath.
type: docs
weight: 24
url: /el/java/com.aspose.drawing.drawing2d/graphicspathiterator/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public final class GraphicsPathIterator implements System.IDisposable
```

Παρέχει τη δυνατότητα επανάληψης μέσω των υποδιαδρομών σε ένα [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) και δοκιμής των τύπων των σχημάτων που περιέχονται σε κάθε υποδιαδρομή. Αυτή η κλάση δεν μπορεί να κληρονομηθεί.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [GraphicsPathIterator(GraphicsPath path)](#GraphicsPathIterator-com.aspose.drawing.drawing2d.GraphicsPath-) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator). |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getCount()](#getCount--) | Λαμβάνει τον αριθμό των σημείων στη διαδρομή. |
| [getSubpathCount()](#getSubpathCount--) | Λαμβάνει τον αριθμό των υποδιαδρομών στη διαδρομή. |
| [dispose()](#dispose--) | Εκτελεί εργασίες ορισμένες από την εφαρμογή που σχετίζονται με την απελευθέρωση, την αποδέσμευση ή την επαναφορά μη διαχειριζόμενων πόρων. |
| [copyData(PointF[][] points, byte[][] types, int startIndex, int endIndex)](#copyData-com.aspose.drawing.PointF-----byte-----int-int-) | Αντιγράφει τις ιδιότητες GraphicsPath.PathPoints και GraphicsPath.PathTypes καθώς και τις αντίστοιχες πίνακες του συνδεδεμένου [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) στους δύο καθορισμένους πίνακες. |
| [enumerate(PointF[][] points, byte[][] types)](#enumerate-com.aspose.drawing.PointF-----byte-----) | Αντιγράφει τις ιδιότητες GraphicsPath.PathPoints και GraphicsPath.PathTypes καθώς και τις αντίστοιχες πίνακες του συνδεδεμένου [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) στους δύο καθορισμένους πίνακες. |
| [hasCurve()](#hasCurve--) | Δείχνει εάν η διαδρομή που σχετίζεται με αυτόν τον [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) περιέχει καμπύλη. |
| [nextMarker(int[] startIndex, int[] endIndex)](#nextMarker-int---int---) | Αυξάνει τον [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) στον επόμενο δείκτη στη διαδρομή και επιστρέφει τα αρχικά και τελικά ευρετήρια μέσω των παραμέτρων [out]. |
| [nextMarker(GraphicsPath path)](#nextMarker-com.aspose.drawing.drawing2d.GraphicsPath-) | Αυτό το αντικείμενο [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) έχει ένα αντικείμενο [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) συνδεδεμένο με αυτό. |
| [nextPathType(byte[] pathType, int[] startIndex, int[] endIndex)](#nextPathType-byte---int---int---) | Λαμβάνει το αρχικό ευρετήριο και το τελικό ευρετήριο της επόμενης ομάδας σημείων δεδομένων που έχουν όλους τον ίδιο τύπο. |
| [nextSubpath(int[] startIndex, int[] endIndex, boolean[] isClosed)](#nextSubpath-int---int---boolean---) | Μετακινεί τον [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) στην επόμενη υποδιαδρομή στη διαδρομή. |
| [nextSubpath(GraphicsPath path, boolean[] isClosed)](#nextSubpath-com.aspose.drawing.drawing2d.GraphicsPath-boolean---) | Λαμβάνει το επόμενο σχήμα (υποδιαδρομή) από τη συνδεδεμένη διαδρομή αυτού του [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator). |
| [rewind()](#rewind--) | Επαναφέρει αυτόν τον [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) στην αρχή της συνδεδεμένης του διαδρομής. |
### GraphicsPathIterator(GraphicsPath path) {#GraphicsPathIterator-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public GraphicsPathIterator(GraphicsPath path)
```


Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | Το αντικείμενο [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) για το οποίο πρέπει να αρχικοποιηθεί αυτή η βοηθητική κλάση. |

### getCount() {#getCount--}
```
public int getCount()
```


Λαμβάνει τον αριθμό των σημείων στη διαδρομή.

**Returns:**
int - ο αριθμός των σημείων στη διαδρομή.
### getSubpathCount() {#getSubpathCount--}
```
public int getSubpathCount()
```


Λαμβάνει τον αριθμό των υποδιαδρομών στη διαδρομή.

**Returns:**
int - ο αριθμός των υποδιαδρομών στη διαδρομή.
### dispose() {#dispose--}
```
public void dispose()
```


Εκτελεί εργασίες ορισμένες από την εφαρμογή που σχετίζονται με την απελευθέρωση, την αποδέσμευση ή την επαναφορά μη διαχειριζόμενων πόρων.

### copyData(PointF[][] points, byte[][] types, int startIndex, int endIndex) {#copyData-com.aspose.drawing.PointF-----byte-----int-int-}
```
public int copyData(PointF[][] points, byte[][] types, int startIndex, int endIndex)
```


Αντιγράφει τις ιδιότητες GraphicsPath.PathPoints και GraphicsPath.PathTypes καθώς και τις αντίστοιχες πίνακες του συνδεδεμένου [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) στους δύο καθορισμένους πίνακες.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.drawing/pointf) | Κατά την επιστροφή, περιέχει έναν πίνακα δομών System.Drawing.PointF που αντιπροσωπεύουν τα σημεία στη διαδρομή. |
| τύποι | byte[][] | Κατά την επιστροφή, περιέχει έναν πίνακα byte που αντιπροσωπεύει τους τύπους των σημείων στη διαδρομή. |
| startIndex | int | Καθορίζει το αρχικό ευρετήριο των πινάκων. |
| endIndex | int | Καθορίζει το τελικό ευρετήριο των πινάκων. |

**Returns:**
int - Ο αριθμός των αντιγραμμένων σημείων.
### enumerate(PointF[][] points, byte[][] types) {#enumerate-com.aspose.drawing.PointF-----byte-----}
```
public int enumerate(PointF[][] points, byte[][] types)
```


Αντιγράφει τις ιδιότητες GraphicsPath.PathPoints και GraphicsPath.PathTypes καθώς και τις αντίστοιχες πίνακες του συνδεδεμένου [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) στους δύο καθορισμένους πίνακες.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.drawing/pointf) | Κατά την επιστροφή, περιέχει έναν πίνακα δομών System.Drawing.PointF που αντιπροσωπεύουν τα σημεία στη διαδρομή. |
| τύποι | byte[][] | Κατά την επιστροφή, περιέχει έναν πίνακα byte που αντιπροσωπεύει τους τύπους των σημείων στη διαδρομή. |

**Returns:**
int - Ο αριθμός των αντιγραμμένων σημείων.
### hasCurve() {#hasCurve--}
```
public boolean hasCurve()
```


Δείχνει εάν η διαδρομή που σχετίζεται με αυτόν τον [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) περιέχει καμπύλη.

**Returns:**
boolean - Αυτή η μέθοδος επιστρέφει true εάν η τρέχουσα υποδιαδρομή περιέχει καμπύλη· διαφορετικά, false.
### nextMarker(int[] startIndex, int[] endIndex) {#nextMarker-int---int---}
```
public int nextMarker(int[] startIndex, int[] endIndex)
```


Αυξάνει τον [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) στον επόμενο δείκτη στη διαδρομή και επιστρέφει τα αρχικά και τελικά ευρετήρια μέσω των παραμέτρων [out].

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| startIndex | int[] | [out] Η αναφορά ακέραιου που παρέχεται σε αυτήν την παράμετρο λαμβάνει το δείκτη του σημείου που ξεκινά μια υποδιαδρομή. |
| endIndex | int[] | [out] Η αναφορά ακέραιου που παρέχεται σε αυτήν την παράμετρο λαμβάνει το δείκτη του σημείου που τερματίζει την υποδιαδρομή στην οποία δείχνει το startIndex. |

**Returns:**
int - Ο αριθμός των σημείων μεταξύ αυτού του δείκτη και του επόμενου.
### nextMarker(GraphicsPath path) {#nextMarker-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public int nextMarker(GraphicsPath path)
```


Αυτό το αντικείμενο [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) έχει ένα αντικείμενο [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) συσχετισμένο με αυτό. Αυτή η μέθοδος αυξάνει το συσχετισμένο [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) στον επόμενο δείκτη στην διαδρομή του και αντιγράφει όλα τα σημεία που περιέχονται μεταξύ του τρέχοντος δείκτη και του επόμενου δείκτη (ή του τέλους της διαδρομής) σε ένα δεύτερο αντικείμενο [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) που περνιέται ως παράμετρος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | Το αντικείμενο [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) στο οποίο θα αντιγραφούν τα σημεία. |

**Returns:**
int - Ο αριθμός των σημείων μεταξύ αυτού του δείκτη και του επόμενου.
### nextPathType(byte[] pathType, int[] startIndex, int[] endIndex) {#nextPathType-byte---int---int---}
```
public int nextPathType(byte[] pathType, int[] startIndex, int[] endIndex)
```


Λαμβάνει το αρχικό ευρετήριο και το τελικό ευρετήριο της επόμενης ομάδας σημείων δεδομένων που έχουν όλους τον ίδιο τύπο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pathType | byte[] | [out] Λαμβάνει τον τύπο σημείου που μοιράζεται από όλα τα σημεία στην ομάδα. Οι πιθανές τιμές μπορούν να ανακτηθούν από την απαρίθμηση [PathPointType](../../com.aspose.drawing.drawing2d/pathpointtype). |
| startIndex | int[] | [out] Λαμβάνει το αρχικό δείκτη της ομάδας σημείων. |
| endIndex | int[] | [out] Λαμβάνει το τελικό δείκτη της ομάδας σημείων. |

**Returns:**
int - Αυτή η μέθοδος επιστρέφει τον αριθμό των σημείων δεδομένων στην ομάδα. Εάν δεν υπάρχουν άλλες ομάδες στην διαδρομή, αυτή η μέθοδος επιστρέφει 0.
### nextSubpath(int[] startIndex, int[] endIndex, boolean[] isClosed) {#nextSubpath-int---int---boolean---}
```
public int nextSubpath(int[] startIndex, int[] endIndex, boolean[] isClosed)
```


Μετακινεί το [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) στην επόμενη υποδιαδρομή στη διαδρομή. Ο αρχικός δείκτης και ο τελικός δείκτης της επόμενης υποδιαδρομής περιέχονται στις παραμέτρους [out].

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| startIndex | int[] | [out] Λαμβάνει το αρχικό δείκτη της επόμενης υποδιαδρομής. |
| endIndex | int[] | [out] Λαμβάνει το τελικό δείκτη της επόμενης υποδιαδρομής. |
| isClosed | boolean[] | [out] Δείχνει εάν η υποδιαδρομή είναι κλειστή. |

**Returns:**
int - Ο αριθμός των σημείων δεδομένων στη ληφθείσα μορφή (υποδιαδρομή). Εάν δεν υπάρχουν άλλες μορφές για ανάκτηση, επιστρέφεται μηδέν.
### nextSubpath(GraphicsPath path, boolean[] isClosed) {#nextSubpath-com.aspose.drawing.drawing2d.GraphicsPath-boolean---}
```
public int nextSubpath(GraphicsPath path, boolean[] isClosed)
```


Λαμβάνει το επόμενο σχήμα (υποδιαδρομή) από τη συνδεδεμένη διαδρομή αυτού του [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | Ένα [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) το οποίο θα έχει τα σημεία δεδομένων του ρυθμισμένα ώστε να ταιριάζουν με τα σημεία δεδομένων της ληφθείσας μορφής (υποδιαδρομής) για αυτόν τον επαναλήπτη. |
| isClosed | boolean[] | [out] Δείχνει εάν η τρέχουσα υποδιαδρομή είναι κλειστή. Είναι true εάν η μορφή είναι κλειστή, διαφορετικά είναι false. |

**Returns:**
int - Ο αριθμός των σημείων δεδομένων στη ληφθείσα μορφή (υποδιαδρομή). Εάν δεν υπάρχουν άλλες μορφές για ανάκτηση, επιστρέφεται μηδέν.
### rewind() {#rewind--}
```
public void rewind()
```


Επαναφέρει αυτόν τον [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) στην αρχή της συνδεδεμένης του διαδρομής.

