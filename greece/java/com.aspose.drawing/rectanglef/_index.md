---
title: RectangleF
second_title: Αναφορά API του Aspose.Drawing for Java
description: Stores a set of four floating-point numbers that represent the location and size of a rectangle.
type: docs
weight: 39
url: /el/java/com.aspose.drawing/rectanglef/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable, java.lang.Cloneable
```
public class RectangleF extends Struct<RectangleF> implements System.IEquatable<RectangleF>, Cloneable
```

Αποθηκεύει ένα σύνολο τεσσάρων αριθμών κινητής υποδιαστολής που αντιπροσωπεύουν τη θέση και το μέγεθος ενός ορθογωνίου. Για πιο προχωρημένες λειτουργίες περιοχής, χρησιμοποιήστε ένα αντικείμενο Region.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [RectangleF()](#RectangleF--) |  |
| [RectangleF(PointF location, SizeF size)](#RectangleF-com.aspose.drawing.PointF-com.aspose.drawing.SizeF-) | Αρχικοποιεί ένα νέο αντίτυπο της δομής RectangleF με την καθορισμένη θέση και μέγεθος. |
| [RectangleF(float x, float y, float width, float height)](#RectangleF-float-float-float-float-) | Αρχικοποιεί ένα νέο αντίτυπο της δομής RectangleF με την καθορισμένη θέση και μέγεθος. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [fromPoints(PointF point1, PointF point2)](#fromPoints-com.aspose.drawing.PointF-com.aspose.drawing.PointF-) | Δημιουργεί ένα νέο ορθογώνιο από δύο σημεία. |
| [to_RectangleF(Rectangle r)](#to-RectangleF-com.aspose.drawing.Rectangle-) | Μετατρέπει τη συγκεκριμένη δομή Rectangle σε δομή RectangleF. |
| [op_Equality(RectangleF left, RectangleF right)](#op-Equality-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-) | Δοκιμάζει αν δύο δομές [RectangleF](../../com.aspose.drawing/rectanglef) έχουν ίση θέση και μέγεθος. |
| [op_Inequality(RectangleF left, RectangleF right)](#op-Inequality-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-) | Δοκιμάζει αν δύο δομές [RectangleF](../../com.aspose.drawing/rectanglef) διαφέρουν στη θέση ή στο μέγεθος. |
| [fromLTRB(float left, float top, float right, float bottom)](#fromLTRB-float-float-float-float-) | Δημιουργεί μια δομή RectangleF με την πάνω-αριστερή γωνία και την κάτω-δεξιά γωνία στις καθορισμένες θέσεις. |
| [inflate(RectangleF rect, float x, float y)](#inflate-com.aspose.drawing.RectangleF-float-float-) | Δημιουργεί και επιστρέφει ένα φουσκωμένο αντίγραφο της καθορισμένης δομής [RectangleF](../../com.aspose.drawing/rectanglef). |
| [intersect(RectangleF a, RectangleF b)](#intersect-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-) | Επιστρέφει μια δομή [RectangleF](../../com.aspose.drawing/rectanglef) που αντιπροσωπεύει τη διατομή δύο ορθογωνίων. |
| [union(RectangleF a, RectangleF b)](#union-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-) | Δημιουργεί το μικρότερο δυνατό τρίτο ορθογώνιο που μπορεί να περιέχει και τα δύο ορθογώνια που σχηματίζουν ένωση. |
| [isEquals(RectangleF obj1, RectangleF obj2)](#isEquals-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-) |  |
| [getEmpty()](#getEmpty--) |  |
| [isEmpty()](#isEmpty--) | Λαμβάνει μια τιμή που υποδεικνύει αν η ιδιότητα `RectangleF.Width` ή `RectangleF.Height` αυτής της [RectangleF](../../com.aspose.drawing/rectanglef) έχει τιμή μηδέν. |
| [getX()](#getX--) | Λαμβάνει τη συντεταγμένη x της πάνω-αριστερής γωνίας αυτής της δομής RectangleF. |
| [setX(float value)](#setX-float-) | Ορίζει τη συντεταγμένη x της πάνω-αριστερής γωνίας αυτής της δομής RectangleF. |
| [getY()](#getY--) | Λαμβάνει τη συντεταγμένη x της πάνω-αριστερής γωνίας αυτής της δομής RectangleF. |
| [setY(float value)](#setY-float-) | Ορίζει τη συντεταγμένη x της πάνω-αριστερής γωνίας αυτής της δομής RectangleF. |
| [getLocation()](#getLocation--) | Λαμβάνει τις συντεταγμένες της πάνω-αριστερής γωνίας αυτής της δομής [RectangleF](../../com.aspose.drawing/rectanglef). |
| [setLocation(PointF value)](#setLocation-com.aspose.drawing.PointF-) | Ορίζει τις συντεταγμένες της επάνω αριστερής γωνίας αυτής της δομής [RectangleF](../../com.aspose.drawing/rectanglef). |
| [getWidth()](#getWidth--) | Λαμβάνει το πλάτος αυτής της δομής RectangleF. |
| [setWidth(float value)](#setWidth-float-) | Ορίζει το πλάτος αυτής της δομής RectangleF. |
| [getHeight()](#getHeight--) | Λαμβάνει το ύψος αυτής της δομής RectangleF. |
| [setHeight(float value)](#setHeight-float-) | Ορίζει το ύψος αυτής της δομής RectangleF. |
| [getSize()](#getSize--) | Λαμβάνει το μέγεθος αυτής της [RectangleF](../../com.aspose.drawing/rectanglef). |
| [setSize(SizeF value)](#setSize-com.aspose.drawing.SizeF-) | Ορίζει το μέγεθος αυτής της [RectangleF](../../com.aspose.drawing/rectanglef). |
| [getLeft()](#getLeft--) | Λαμβάνει τη συντεταγμένη x της αριστερής άκρης αυτής της δομής RectangleF. |
| [getTop()](#getTop--) | Λαμβάνει τη συντεταγμένη y της επάνω άκρης αυτής της δομής RectangleF. |
| [getRight()](#getRight--) | Λαμβάνει τη συντεταγμένη x που είναι το άθροισμα του X και του Width αυτής της δομής RectangleF. |
| [getBottom()](#getBottom--) | Λαμβάνει τη συντεταγμένη y που είναι το άθροισμα του Y και του Height αυτής της δομής RectangleF. |
| [toString()](#toString--) |  |
| [inflate(float x, float y)](#inflate-float-float-) | Μεγεθύνει αυτή τη δομή [RectangleF](../../com.aspose.drawing/rectanglef) κατά το καθορισμένο ποσό. |
| [inflate(SizeF size)](#inflate-com.aspose.drawing.SizeF-) | Μεγεθύνει αυτή τη [RectangleF](../../com.aspose.drawing/rectanglef) κατά το καθορισμένο ποσό. |
| [intersect(RectangleF rect)](#intersect-com.aspose.drawing.RectangleF-) | Αντικαθιστά αυτή τη δομή [RectangleF](../../com.aspose.drawing/rectanglef) με τη διατομή της με την καθορισμένη δομή [RectangleF](../../com.aspose.drawing/rectanglef). |
| [intersectsWith(RectangleF rect)](#intersectsWith-com.aspose.drawing.RectangleF-) | Καθορίζει αν αυτό το παραλληλόγραμμο τέμνει το `rect`. |
| [offset(PointF pos)](#offset-com.aspose.drawing.PointF-) | Ρυθμίζει τη θέση αυτού του παραλληλόγραμμου κατά το καθορισμένο ποσό. |
| [offset(float x, float y)](#offset-float-float-) | Ρυθμίζει τη θέση αυτού του παραλληλόγραμμου κατά το καθορισμένο ποσό. |
| [contains(float x, float y)](#contains-float-float-) | Καθορίζει αν το καθορισμένο σημείο περιέχεται μέσα σε αυτή τη δομή [RectangleF](../../com.aspose.drawing/rectanglef). |
| [contains(PointF pt)](#contains-com.aspose.drawing.PointF-) | Καθορίζει αν το καθορισμένο σημείο περιέχεται μέσα σε αυτή τη δομή [RectangleF](../../com.aspose.drawing/rectanglef). |
| [contains(RectangleF rect)](#contains-com.aspose.drawing.RectangleF-) | Καθορίζει αν η περιοχή παραλληλόγραμμου που αντιπροσωπεύεται από το `rect` περιέχεται πλήρως μέσα σε αυτή τη δομή [RectangleF](../../com.aspose.drawing/rectanglef). |
| [equals(Object obj)](#equals-java.lang.Object-) | Καθορίζει αν το καθορισμένο Object είναι ίσο με αυτήν την instance. |
| [hashCode()](#hashCode--) | Επιστρέφει έναν κωδικό κατακερματισμού για αυτήν την instance. |
| [equals(RectangleF other)](#equals-com.aspose.drawing.RectangleF-) | Δοκιμάζει αν άλλη δομή [RectangleF](../../com.aspose.drawing/rectanglef) έχει την ίδια θέση και μέγεθος με αυτή τη δομή [RectangleF](../../com.aspose.drawing/rectanglef). |
| [CloneTo(RectangleF that)](#CloneTo-com.aspose.drawing.RectangleF-) |  |
| [Clone()](#Clone--) |  |
| [clone()](#clone--) |  |
### RectangleF() {#RectangleF--}
```
public RectangleF()
```


### RectangleF(PointF location, SizeF size) {#RectangleF-com.aspose.drawing.PointF-com.aspose.drawing.SizeF-}
```
public RectangleF(PointF location, SizeF size)
```


Αρχικοποιεί ένα νέο αντίτυπο της δομής RectangleF με την καθορισμένη θέση και μέγεθος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| location | [PointF](../../com.aspose.drawing/pointf) | Ένα PointF που αντιπροσωπεύει την επάνω αριστερή γωνία της περιοχής παραλληλόγραμμου. |
| size | [SizeF](../../com.aspose.drawing/sizef) | Ένα SizeF που αντιπροσωπεύει το πλάτος και το ύψος της περιοχής παραλληλόγραμμου. |

### RectangleF(float x, float y, float width, float height) {#RectangleF-float-float-float-float-}
```
public RectangleF(float x, float y, float width, float height)
```


Αρχικοποιεί ένα νέο αντίτυπο της δομής RectangleF με την καθορισμένη θέση και μέγεθος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | float | Η συντεταγμένη x της επάνω αριστερής γωνίας του παραλληλόγραμμου. |
| y | float | Η συντεταγμένη y της επάνω αριστερής γωνίας του ορθογωνίου. |
| width | float | Το πλάτος του ορθογωνίου. |
| height | float | Το ύψος του ορθογωνίου. |

### fromPoints(PointF point1, PointF point2) {#fromPoints-com.aspose.drawing.PointF-com.aspose.drawing.PointF-}
```
public static RectangleF fromPoints(PointF point1, PointF point2)
```


Δημιουργεί ένα νέο ορθογώνιο από δύο σημεία. Το δημιουργημένο ορθογώνιο θα κανονικοποιηθεί με το (αριστερό,επάνω) μικρότερο από το (δεξί,κάτω).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| point1 | [PointF](../../com.aspose.drawing/pointf) | Το πρώτο σημείο. |
| point2 | [PointF](../../com.aspose.drawing/pointf) | Το δεύτερο σημείο. |

**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef) - A newly created rectangle.
### to_RectangleF(Rectangle r) {#to-RectangleF-com.aspose.drawing.Rectangle-}
```
public static RectangleF to_RectangleF(Rectangle r)
```


Μετατρέπει τη συγκεκριμένη δομή Rectangle σε δομή RectangleF.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| r | [Rectangle](../../com.aspose.drawing/rectangle) | Η δομή Rectangle προς μετατροπή. |

**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef) - The RectangleF structure that is converted from the specified Rectangle structure.
### op_Equality(RectangleF left, RectangleF right) {#op-Equality-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-}
```
public static boolean op_Equality(RectangleF left, RectangleF right)
```


Δοκιμάζει αν δύο δομές [RectangleF](../../com.aspose.drawing/rectanglef) έχουν ίση θέση και μέγεθος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| left | [RectangleF](../../com.aspose.drawing/rectanglef) | Η δομή [RectangleF](../../com.aspose.drawing/rectanglef) που βρίσκεται αριστερά του τελεστή ισότητας. |
| right | [RectangleF](../../com.aspose.drawing/rectanglef) | Η δομή [RectangleF](../../com.aspose.drawing/rectanglef) που βρίσκεται δεξιά του τελεστή ισότητας. |

**Returns:**
boolean - Αυτός ο τελεστής επιστρέφει true εάν οι δύο καθορισμένες δομές [RectangleF](../../com.aspose.drawing/rectanglef) έχουν ίσες τις ιδιότητες `RectangleF.X`, `RectangleF.Y`, `RectangleF.Width` και `RectangleF.Height`.
### op_Inequality(RectangleF left, RectangleF right) {#op-Inequality-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-}
```
public static boolean op_Inequality(RectangleF left, RectangleF right)
```


Δοκιμάζει αν δύο δομές [RectangleF](../../com.aspose.drawing/rectanglef) διαφέρουν στη θέση ή στο μέγεθος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| left | [RectangleF](../../com.aspose.drawing/rectanglef) | Η δομή [RectangleF](../../com.aspose.drawing/rectanglef) που βρίσκεται αριστερά του τελεστή ανισότητας. |
| right | [RectangleF](../../com.aspose.drawing/rectanglef) | Η δομή [RectangleF](../../com.aspose.drawing/rectanglef) που βρίσκεται δεξιά του τελεστή ανισότητας. |

**Returns:**
boolean - Αυτός ο τελεστής επιστρέφει true εάν οποιαδήποτε από τις ιδιότητες `RectangleF.X`, `RectangleF.Y`, `RectangleF.Width` ή `RectangleF.Height` των δύο δομών [Rectangle](../../com.aspose.drawing/rectangle) είναι διαφορετική· διαφορετικά false.
### fromLTRB(float left, float top, float right, float bottom) {#fromLTRB-float-float-float-float-}
```
public static RectangleF fromLTRB(float left, float top, float right, float bottom)
```


Δημιουργεί μια δομή RectangleF με την πάνω-αριστερή γωνία και την κάτω-δεξιά γωνία στις καθορισμένες θέσεις.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| αριστερά | float | Η συντεταγμένη x της επάνω αριστερής γωνίας της ορθογώνιας περιοχής. |
| επάνω | float | Η συντεταγμένη y της επάνω αριστερής γωνίας της ορθογώνιας περιοχής. |
| δεξιά | float | Η συντεταγμένη x της κάτω δεξιάς γωνίας της ορθογώνιας περιοχής. |
| κάτω | float | Η συντεταγμένη y της κάτω δεξιάς γωνίας της ορθογώνιας περιοχής. |

**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef) - The new RectangleF that this method creates.
### inflate(RectangleF rect, float x, float y) {#inflate-com.aspose.drawing.RectangleF-float-float-}
```
public static RectangleF inflate(RectangleF rect, float x, float y)
```


Δημιουργεί και επιστρέφει ένα φουσκωμένο αντίγραφο της καθορισμένης δομής [RectangleF](../../com.aspose.drawing/rectanglef). Το αντίγραφο φουσκώνεται κατά το καθορισμένο ποσό. Το αρχικό ορθογώνιο παραμένει αμετάβλητο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | Η [RectangleF](../../com.aspose.drawing/rectanglef) που θα αντιγραφεί. Αυτό το ορθογώνιο δεν τροποποιείται. |
| x | float | Το ποσό για την οριζόντια φούσκωση του αντιγράφου του ορθογωνίου. |
| y | float | Το ποσό για την επέκταση κατακόρυφα του αντιγράφου του ορθογωνίου. |

**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef) - The inflated [RectangleF](../../com.aspose.drawing/rectanglef).
### intersect(RectangleF a, RectangleF b) {#intersect-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-}
```
public static RectangleF intersect(RectangleF a, RectangleF b)
```


Επιστρέφει μια δομή [RectangleF](../../com.aspose.drawing/rectanglef) που αντιπροσωπεύει την τομή δύο ορθογωνίων. Εάν δεν υπάρχει τομή, επιστρέφεται ένα κενό [RectangleF](../../com.aspose.drawing/rectanglef).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| a | [RectangleF](../../com.aspose.drawing/rectanglef) | Πρώτο ορθογώνιο για τομή. |
| b | [RectangleF](../../com.aspose.drawing/rectanglef) | Δεύτερο ορθογώνιο για τομή. |

**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef) - A third [RectangleF](../../com.aspose.drawing/rectanglef) structure the size of which represents the overlapped area of the two specified rectangles.
### union(RectangleF a, RectangleF b) {#union-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-}
```
public static RectangleF union(RectangleF a, RectangleF b)
```


Δημιουργεί το μικρότερο δυνατό τρίτο ορθογώνιο που μπορεί να περιέχει και τα δύο ορθογώνια που σχηματίζουν ένωση.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| a | [RectangleF](../../com.aspose.drawing/rectanglef) | Πρώτο ορθογώνιο για ένωση. |
| b | [RectangleF](../../com.aspose.drawing/rectanglef) | Δεύτερο ορθογώνιο για ένωση. |

**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef) - A third [RectangleF](../../com.aspose.drawing/rectanglef) structure that contains both of the two rectangles that form the union.
### isEquals(RectangleF obj1, RectangleF obj2) {#isEquals-com.aspose.drawing.RectangleF-com.aspose.drawing.RectangleF-}
```
public static boolean isEquals(RectangleF obj1, RectangleF obj2)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj1 | [RectangleF](../../com.aspose.drawing/rectanglef) |  |
| obj2 | [RectangleF](../../com.aspose.drawing/rectanglef) |  |

**Returns:**
boolean
### getEmpty() {#getEmpty--}
```
public static RectangleF getEmpty()
```




**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef)
### isEmpty() {#isEmpty--}
```
public final boolean isEmpty()
```


Λαμβάνει μια τιμή που υποδεικνύει αν η ιδιότητα `RectangleF.Width` ή `RectangleF.Height` αυτής της [RectangleF](../../com.aspose.drawing/rectanglef) έχει τιμή μηδέν.

**Returns:**
boolean - Αυτή η ιδιότητα επιστρέφει true εάν η ιδιότητα `RectangleF.Width` ή `P:RectangleF.Height` αυτού του [RectangleF](../../com.aspose.drawing/rectanglef) έχει τιμή μηδέν· διαφορετικά, false.
### getX() {#getX--}
```
public final float getX()
```


Λαμβάνει τη συντεταγμένη x της πάνω-αριστερής γωνίας αυτής της δομής RectangleF.

**Returns:**
float - η συντεταγμένη x της επάνω αριστερής γωνίας αυτής της δομής RectangleF.
### setX(float value) {#setX-float-}
```
public final void setX(float value)
```


Ορίζει τη συντεταγμένη x της πάνω-αριστερής γωνίας αυτής της δομής RectangleF.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float | η συντεταγμένη x της επάνω αριστερής γωνίας αυτής της δομής RectangleF. |

### getY() {#getY--}
```
public final float getY()
```


Λαμβάνει τη συντεταγμένη x της πάνω-αριστερής γωνίας αυτής της δομής RectangleF.

**Returns:**
float - η συντεταγμένη x της επάνω αριστερής γωνίας αυτής της δομής RectangleF.
### setY(float value) {#setY-float-}
```
public final void setY(float value)
```


Ορίζει τη συντεταγμένη x της πάνω-αριστερής γωνίας αυτής της δομής RectangleF.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float | η συντεταγμένη x της επάνω αριστερής γωνίας αυτής της δομής RectangleF. |

### getLocation() {#getLocation--}
```
public final PointF getLocation()
```


Λαμβάνει τις συντεταγμένες της πάνω-αριστερής γωνίας αυτής της δομής [RectangleF](../../com.aspose.drawing/rectanglef).

**Returns:**
[PointF](../../com.aspose.drawing/pointf) - A [PointF](../../com.aspose.drawing/pointf) that represents the upper-left corner of this [RectangleF](../../com.aspose.drawing/rectanglef) structure.
### setLocation(PointF value) {#setLocation-com.aspose.drawing.PointF-}
```
public final void setLocation(PointF value)
```


Ορίζει τις συντεταγμένες της επάνω αριστερής γωνίας αυτής της δομής [RectangleF](../../com.aspose.drawing/rectanglef).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [PointF](../../com.aspose.drawing/pointf) | οι συντεταγμένες της επάνω αριστερής γωνίας αυτής της δομής [RectangleF](../../com.aspose.drawing/rectanglef). |

### getWidth() {#getWidth--}
```
public final float getWidth()
```


Λαμβάνει το πλάτος αυτής της δομής RectangleF.

**Returns:**
float - το πλάτος αυτής της δομής RectangleF.
### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```


Ορίζει το πλάτος αυτής της δομής RectangleF.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float | το πλάτος αυτής της δομής RectangleF. |

### getHeight() {#getHeight--}
```
public final float getHeight()
```


Λαμβάνει το ύψος αυτής της δομής RectangleF.

**Returns:**
float - το ύψος αυτής της δομής RectangleF.
### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```


Ορίζει το ύψος αυτής της δομής RectangleF.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float | το ύψος αυτής της δομής RectangleF. |

### getSize() {#getSize--}
```
public final SizeF getSize()
```


Λαμβάνει το μέγεθος αυτής της [RectangleF](../../com.aspose.drawing/rectanglef).

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - A [SizeF](../../com.aspose.drawing/sizef) that represents the width and height of this [RectangleF](../../com.aspose.drawing/rectanglef) structure.
### setSize(SizeF value) {#setSize-com.aspose.drawing.SizeF-}
```
public final void setSize(SizeF value)
```


Ορίζει το μέγεθος αυτής της [RectangleF](../../com.aspose.drawing/rectanglef).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.drawing/sizef) | το μέγεθος αυτής της [RectangleF](../../com.aspose.drawing/rectanglef). |

### getLeft() {#getLeft--}
```
public final float getLeft()
```


Λαμβάνει τη συντεταγμένη x της αριστερής άκρης αυτής της δομής RectangleF.

**Returns:**
float - η συντεταγμένη x της αριστερής άκρης αυτής της δομής RectangleF.
### getTop() {#getTop--}
```
public final float getTop()
```


Λαμβάνει τη συντεταγμένη y της επάνω άκρης αυτής της δομής RectangleF.

**Returns:**
float - η συντεταγμένη y της άνω άκρης αυτής της δομής RectangleF.
### getRight() {#getRight--}
```
public final float getRight()
```


Λαμβάνει τη συντεταγμένη x που είναι το άθροισμα του X και του Width αυτής της δομής RectangleF.

**Returns:**
float - η συντεταγμένη x που είναι το άθροισμα των X και Width αυτής της δομής RectangleF.
### getBottom() {#getBottom--}
```
public final float getBottom()
```


Λαμβάνει τη συντεταγμένη y που είναι το άθροισμα του Y και του Height αυτής της δομής RectangleF.

**Returns:**
float - η συντεταγμένη y που είναι το άθροισμα των Y και Height αυτής της δομής RectangleF.
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### inflate(float x, float y) {#inflate-float-float-}
```
public final void inflate(float x, float y)
```


Μεγεθύνει αυτή τη δομή [RectangleF](../../com.aspose.drawing/rectanglef) κατά το καθορισμένο ποσό.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | float | Το ποσό για την επέκταση αυτής της δομής [RectangleF](../../com.aspose.drawing/rectanglef) οριζόντια. |
| y | float | Το ποσό για την επέκταση αυτής της δομής [RectangleF](../../com.aspose.drawing/rectanglef) κατακόρυφα. |

### inflate(SizeF size) {#inflate-com.aspose.drawing.SizeF-}
```
public final void inflate(SizeF size)
```


Μεγεθύνει αυτή τη [RectangleF](../../com.aspose.drawing/rectanglef) κατά το καθορισμένο ποσό.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.drawing/sizef) | Το ποσό για την επέκταση αυτού του ορθογωνίου. |

### intersect(RectangleF rect) {#intersect-com.aspose.drawing.RectangleF-}
```
public final void intersect(RectangleF rect)
```


Αντικαθιστά αυτή τη δομή [RectangleF](../../com.aspose.drawing/rectanglef) με τη διατομή της με την καθορισμένη δομή [RectangleF](../../com.aspose.drawing/rectanglef).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | Το ορθογώνιο για τομή. |

### intersectsWith(RectangleF rect) {#intersectsWith-com.aspose.drawing.RectangleF-}
```
public final boolean intersectsWith(RectangleF rect)
```


Καθορίζει αν αυτό το παραλληλόγραμμο τέμνει το `rect`.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | Το ορθογώνιο για δοκιμή. |

**Returns:**
boolean - Αυτή η μέθοδος επιστρέφει true εάν υπάρχει οποιαδήποτε τομή.
### offset(PointF pos) {#offset-com.aspose.drawing.PointF-}
```
public final void offset(PointF pos)
```


Ρυθμίζει τη θέση αυτού του παραλληλόγραμμου κατά το καθορισμένο ποσό.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pos | [PointF](../../com.aspose.drawing/pointf) | Το ποσό για μετατόπιση της θέσης. |

### offset(float x, float y) {#offset-float-float-}
```
public final void offset(float x, float y)
```


Ρυθμίζει τη θέση αυτού του παραλληλόγραμμου κατά το καθορισμένο ποσό.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | float | Το ποσό για μετατόπιση της θέσης οριζόντια. |
| y | float | Το ποσό για μετατόπιση της θέσης κάθετα. |

### contains(float x, float y) {#contains-float-float-}
```
public final boolean contains(float x, float y)
```


Καθορίζει αν το καθορισμένο σημείο περιέχεται μέσα σε αυτή τη δομή [RectangleF](../../com.aspose.drawing/rectanglef).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | float | Η συντεταγμένη x του σημείου προς δοκιμή. |
| y | float | Η συντεταγμένη y του σημείου προς δοκιμή. |

**Returns:**
boolean - Αυτή η μέθοδος επιστρέφει `true` εάν το σημείο που ορίζεται από x και y περιέχεται μέσα σε αυτή τη δομή [RectangleF](../../com.aspose.drawing/rectanglef); διαφορετικά `false`.
### contains(PointF pt) {#contains-com.aspose.drawing.PointF-}
```
public final boolean contains(PointF pt)
```


Καθορίζει αν το καθορισμένο σημείο περιέχεται μέσα σε αυτή τη δομή [RectangleF](../../com.aspose.drawing/rectanglef).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pt | [PointF](../../com.aspose.drawing/pointf) | Το [PointF](../../com.aspose.drawing/pointf) προς δοκιμή. |

**Returns:**
boolean - Αυτή η μέθοδος επιστρέφει `true` εάν το σημείο που αντιπροσωπεύεται από την παράμετρο pt περιέχεται μέσα σε αυτή τη δομή [RectangleF](../../com.aspose.drawing/rectanglef); διαφορετικά `false`.
### contains(RectangleF rect) {#contains-com.aspose.drawing.RectangleF-}
```
public final boolean contains(RectangleF rect)
```


Καθορίζει αν η περιοχή παραλληλόγραμμου που αντιπροσωπεύεται από το `rect` περιέχεται πλήρως μέσα σε αυτή τη δομή [RectangleF](../../com.aspose.drawing/rectanglef).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | Το [RectangleF](../../com.aspose.drawing/rectanglef) προς δοκιμή. |

**Returns:**
boolean - Αυτή η μέθοδος επιστρέφει `true` εάν η ορθογώνια περιοχή που αντιπροσωπεύεται από το `rect` περιέχεται πλήρως μέσα στην ορθογώνια περιοχή που αντιπροσωπεύεται από αυτή τη [RectangleF](../../com.aspose.drawing/rectanglef); διαφορετικά `false`.
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
### hashCode() {#hashCode--}
```
public int hashCode()
```


Επιστρέφει έναν κωδικό κατακερματισμού για αυτήν την instance.

**Returns:**
int - Ένας κωδικός κατακερματισμού για αυτήν την παρουσία, κατάλληλος για χρήση σε αλγόριθμους κατακερματισμού και δομές δεδομένων όπως ένας πίνακας κατακερματισμού.
### equals(RectangleF other) {#equals-com.aspose.drawing.RectangleF-}
```
public final boolean equals(RectangleF other)
```


Δοκιμάζει αν άλλη δομή [RectangleF](../../com.aspose.drawing/rectanglef) έχει την ίδια θέση και μέγεθος με αυτή τη δομή [RectangleF](../../com.aspose.drawing/rectanglef).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| other | [RectangleF](../../com.aspose.drawing/rectanglef) | Άλλο ορθογώνιο για δοκιμή |

**Returns:**
boolean - Αυτή η μέθοδος επιστρέφει `true` εάν η άλλη δομή [RectangleF](../../com.aspose.drawing/rectanglef) και οι ιδιότητές της X, Y, Width και Height είναι ίσες με τις αντίστοιχες ιδιότητες αυτής της δομής [RectangleF](../../com.aspose.drawing/rectanglef); διαφορετικά, `false`.
### CloneTo(RectangleF that) {#CloneTo-com.aspose.drawing.RectangleF-}
```
public void CloneTo(RectangleF that)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| that | [RectangleF](../../com.aspose.drawing/rectanglef) |  |

### Clone() {#Clone--}
```
public RectangleF Clone()
```




**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef)
### clone() {#clone--}
```
public Object clone()
```




**Returns:**
java.lang.Object
