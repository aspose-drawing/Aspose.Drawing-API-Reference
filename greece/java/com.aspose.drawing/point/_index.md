---
title: Point
second_title: Αναφορά API του Aspose.Drawing for Java
description: Represents an ordered pair of integer x- and y-coordinates that defines a point in a two-dimensional plane.
type: docs
weight: 36
url: /el/java/com.aspose.drawing/point/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable, java.lang.Cloneable
```
public class Point extends Struct<Point> implements System.IEquatable<Point>, Cloneable
```

Represents an ordered pair of integer x- and y-coordinates that defines a point in a two-dimensional plane.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [Point()](#Point--) |  |
| [Point(int x, int y)](#Point-int-int-) | Αρχικοποιεί μια νέα παρουσία της δομής [Point](../../com.aspose.drawing/point) με τις καθορισμένες συντεταγμένες. |
| [Point(Size sz)](#Point-com.aspose.drawing.Size-) |  |
| [Point(int dw)](#Point-int-) | Αρχικοποιεί μια νέα παρουσία της δομής [Point](../../com.aspose.drawing/point) χρησιμοποιώντας συντεταγμένες που καθορίζονται από μια ακέραια τιμή. |
## Fields

| Field | Περιγραφή |
| --- | --- |
| [EMPTY](#EMPTY) | Αναπαριστά ένα [Point](../../com.aspose.drawing/point) που έχει τιμές `Point.X` και `Point.Y` ορισμένες στο μηδέν. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [to_PointF(Point p)](#to-PointF-com.aspose.drawing.Point-) | Μετατρέπει τη συγκεκριμένη δομή [Point](../../com.aspose.drawing/point) σε δομή [PointF](../../com.aspose.drawing/pointf). |
| [to_Size(Point p)](#to-Size-com.aspose.drawing.Point-) |  |
| [op_Addition(Point pt, Size sz)](#op-Addition-com.aspose.drawing.Point-com.aspose.drawing.Size-) |  |
| [op_Subtraction(Point pt, Size sz)](#op-Subtraction-com.aspose.drawing.Point-com.aspose.drawing.Size-) |  |
| [op_Equality(Point left, Point right)](#op-Equality-com.aspose.drawing.Point-com.aspose.drawing.Point-) | Συγκρίνει δύο αντικείμενα [Point](../../com.aspose.drawing/point). |
| [op_Inequality(Point left, Point right)](#op-Inequality-com.aspose.drawing.Point-com.aspose.drawing.Point-) | Συγκρίνει δύο αντικείμενα [Point](../../com.aspose.drawing/point). |
| [add(Point pt, Size sz)](#add-com.aspose.drawing.Point-com.aspose.drawing.Size-) | Προσθέτει το καθορισμένο [Size](../../com.aspose.drawing/size) στο καθορισμένο [Point](../../com.aspose.drawing/point). |
| [subtract(Point pt, Size sz)](#subtract-com.aspose.drawing.Point-com.aspose.drawing.Size-) |  |
| [ceiling(PointF value)](#ceiling-com.aspose.drawing.PointF-) |  |
| [truncate(PointF value)](#truncate-com.aspose.drawing.PointF-) | Μετατρέπει ένα PointF σε Point εκτελώντας μια λειτουργία αποκοπής σε όλες τις συντεταγμένες. |
| [round(PointF value)](#round-com.aspose.drawing.PointF-) | Μετατρέπει τη συγκεκριμένη [PointF](../../com.aspose.drawing/pointf) σε αντικείμενο Point στρογγυλοποιώντας τις τιμές του [Point](../../com.aspose.drawing/point) στο πλησιέστερο ακέραιο. |
| [isEquals(Point obj1, Point obj2)](#isEquals-com.aspose.drawing.Point-com.aspose.drawing.Point-) |  |
| [getEmpty()](#getEmpty--) |  |
| [getX()](#getX--) | Αποκτά τη συντεταγμένη x αυτού του Point. |
| [setX(int value)](#setX-int-) | Ορίζει τη συντεταγμένη x αυτού του Point. |
| [getY()](#getY--) | Αποκτά τη συντεταγμένη y αυτού του Point. |
| [setY(int value)](#setY-int-) | Ορίζει τη συντεταγμένη y αυτού του Point. |
| [isEmpty()](#isEmpty--) | Αποκτά μια τιμή που υποδεικνύει εάν αυτό το [Point](../../com.aspose.drawing/point) είναι κενό. |
| [hashCode()](#hashCode--) | Επιστρέφει έναν κωδικό κατακερματισμού για αυτό το [Point](../../com.aspose.drawing/point). |
| [toString()](#toString--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Καθορίζει εάν αυτό το [Point](../../com.aspose.drawing/point) περιέχει τις ίδιες συντεταγμένες με το καθορισμένο Object. |
| [offset(int dx, int dy)](#offset-int-int-) | Μετατοπίζει αυτό το [Point](../../com.aspose.drawing/point) κατά το καθορισμένο ποσό. |
| [offset(Point p)](#offset-com.aspose.drawing.Point-) | Μετατοπίζει αυτό το [Point](../../com.aspose.drawing/point) κατά το καθορισμένο [Point](../../com.aspose.drawing/point). |
| [equals(Point other)](#equals-com.aspose.drawing.Point-) | Δοκιμάζει εάν η άλλη δομή [Point](../../com.aspose.drawing/point) έχει την ίδια θέση με αυτή τη δομή [Point](../../com.aspose.drawing/point). |
| [CloneTo(Point that)](#CloneTo-com.aspose.drawing.Point-) |  |
| [Clone()](#Clone--) |  |
| [clone()](#clone--) |  |
### Point() {#Point--}
```
public Point()
```


### Point(int x, int y) {#Point-int-int-}
```
public Point(int x, int y)
```


Αρχικοποιεί μια νέα παρουσία της δομής [Point](../../com.aspose.drawing/point) με τις καθορισμένες συντεταγμένες.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | int | Η οριζόντια θέση του σημείου. |
| y | int | Η κάθετη θέση του σημείου. |

### Point(Size sz) {#Point-com.aspose.drawing.Size-}
```
public Point(Size sz)
```


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sz | [Size](../../com.aspose.drawing/size) |  |

### Point(int dw) {#Point-int-}
```
public Point(int dw)
```


Αρχικοποιεί μια νέα παρουσία της δομής [Point](../../com.aspose.drawing/point) χρησιμοποιώντας συντεταγμένες που καθορίζονται από μια ακέραια τιμή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| dw | int | Η ακέραια τιμή. |

### EMPTY {#EMPTY}
```
public static final Point EMPTY
```


Αναπαριστά ένα [Point](../../com.aspose.drawing/point) που έχει τιμές `Point.X` και `Point.Y` ορισμένες στο μηδέν.

### to_PointF(Point p) {#to-PointF-com.aspose.drawing.Point-}
```
public static PointF to_PointF(Point p)
```


Μετατρέπει τη συγκεκριμένη δομή [Point](../../com.aspose.drawing/point) σε δομή [PointF](../../com.aspose.drawing/pointf).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| p | [Point](../../com.aspose.drawing/point) | Το [Point](../../com.aspose.drawing/point) που θα μετατραπεί. |

**Returns:**
[PointF](../../com.aspose.drawing/pointf) - The [PointF](../../com.aspose.drawing/pointf) that results from the conversion.
### to_Size(Point p) {#to-Size-com.aspose.drawing.Point-}
```
public static Size to_Size(Point p)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| p | [Point](../../com.aspose.drawing/point) |  |

**Returns:**
[Size](../../com.aspose.drawing/size)
### op_Addition(Point pt, Size sz) {#op-Addition-com.aspose.drawing.Point-com.aspose.drawing.Size-}
```
public static Point op_Addition(Point pt, Size sz)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pt | [Point](../../com.aspose.drawing/point) |  |
| sz | [Size](../../com.aspose.drawing/size) |  |

**Returns:**
[Point](../../com.aspose.drawing/point)
### op_Subtraction(Point pt, Size sz) {#op-Subtraction-com.aspose.drawing.Point-com.aspose.drawing.Size-}
```
public static Point op_Subtraction(Point pt, Size sz)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pt | [Point](../../com.aspose.drawing/point) |  |
| sz | [Size](../../com.aspose.drawing/size) |  |

**Returns:**
[Point](../../com.aspose.drawing/point)
### op_Equality(Point left, Point right) {#op-Equality-com.aspose.drawing.Point-com.aspose.drawing.Point-}
```
public static boolean op_Equality(Point left, Point right)
```


Συγκρίνει δύο αντικείμενα [Point](../../com.aspose.drawing/point). Το αποτέλεσμα καθορίζει αν οι τιμές των ιδιοτήτων `Point.X` και `Point.Y` των δύο αντικειμένων [Point](../../com.aspose.drawing/point) είναι ίσες.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| left | [Point](../../com.aspose.drawing/point) | Πρώτο [Point](../../com.aspose.drawing/point) για σύγκριση. |
| right | [Point](../../com.aspose.drawing/point) | Δεύτερο [Point](../../com.aspose.drawing/point) για σύγκριση. |

**Returns:**
boolean - true εάν οι τιμές `Point.X` και `Point.Y` των `left` και `right` είναι ίσες· διαφορετικά, false.
### op_Inequality(Point left, Point right) {#op-Inequality-com.aspose.drawing.Point-com.aspose.drawing.Point-}
```
public static boolean op_Inequality(Point left, Point right)
```


Συγκρίνει δύο αντικείμενα [Point](../../com.aspose.drawing/point). Το αποτέλεσμα καθορίζει αν οι τιμές των ιδιοτήτων `Point.X` ή `Point.Y` των δύο αντικειμένων [Point](../../com.aspose.drawing/point) είναι διαφορετικές.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| left | [Point](../../com.aspose.drawing/point) | Πρώτο [Point](../../com.aspose.drawing/point) για σύγκριση. |
| right | [Point](../../com.aspose.drawing/point) | Δεύτερο [Point](../../com.aspose.drawing/point) για σύγκριση. |

**Returns:**
boolean - true εάν οι τιμές είτε των ιδιοτήτων `Point.X` είτε των ιδιοτήτων `Point.Y` των `left` και `right` διαφέρουν· διαφορετικά, false.
### add(Point pt, Size sz) {#add-com.aspose.drawing.Point-com.aspose.drawing.Size-}
```
public static Point add(Point pt, Size sz)
```


Προσθέτει το καθορισμένο [Size](../../com.aspose.drawing/size) στο καθορισμένο [Point](../../com.aspose.drawing/point).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pt | [Point](../../com.aspose.drawing/point) | Το [Point](../../com.aspose.drawing/point) προς προσθήκη. |
| sz | [Size](../../com.aspose.drawing/size) | Το [Size](../../com.aspose.drawing/size) προς προσθήκη. |

**Returns:**
[Point](../../com.aspose.drawing/point) - The [Point](../../com.aspose.drawing/point) that is the result of the addition operation.
### subtract(Point pt, Size sz) {#subtract-com.aspose.drawing.Point-com.aspose.drawing.Size-}
```
public static Point subtract(Point pt, Size sz)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pt | [Point](../../com.aspose.drawing/point) |  |
| sz | [Size](../../com.aspose.drawing/size) |  |

**Returns:**
[Point](../../com.aspose.drawing/point)
### ceiling(PointF value) {#ceiling-com.aspose.drawing.PointF-}
```
public static Point ceiling(PointF value)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [PointF](../../com.aspose.drawing/pointf) |  |

**Returns:**
[Point](../../com.aspose.drawing/point)
### truncate(PointF value) {#truncate-com.aspose.drawing.PointF-}
```
public static Point truncate(PointF value)
```


Μετατρέπει ένα PointF σε Point εκτελώντας μια λειτουργία αποκοπής σε όλες τις συντεταγμένες.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [PointF](../../com.aspose.drawing/pointf) | Το [PointF](../../com.aspose.drawing/pointf) προς αποκοπή. |

**Returns:**
[Point](../../com.aspose.drawing/point) - The [Point](../../com.aspose.drawing/point) that is the result of the truncate operation.
### round(PointF value) {#round-com.aspose.drawing.PointF-}
```
public static Point round(PointF value)
```


Μετατρέπει τη συγκεκριμένη [PointF](../../com.aspose.drawing/pointf) σε αντικείμενο Point στρογγυλοποιώντας τις τιμές του [Point](../../com.aspose.drawing/point) στο πλησιέστερο ακέραιο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [PointF](../../com.aspose.drawing/pointf) | Το [PointF](../../com.aspose.drawing/pointf) προς μετατροπή. |

**Returns:**
[Point](../../com.aspose.drawing/point) - The [Point](../../com.aspose.drawing/point) this method converts to.
### isEquals(Point obj1, Point obj2) {#isEquals-com.aspose.drawing.Point-com.aspose.drawing.Point-}
```
public static boolean isEquals(Point obj1, Point obj2)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj1 | [Point](../../com.aspose.drawing/point) |  |
| obj2 | [Point](../../com.aspose.drawing/point) |  |

**Returns:**
boolean
### getEmpty() {#getEmpty--}
```
public static Point getEmpty()
```




**Returns:**
[Point](../../com.aspose.drawing/point)
### getX() {#getX--}
```
public final int getX()
```


Αποκτά τη συντεταγμένη x αυτού του Point.

**Returns:**
int - η συντεταγμένη x αυτού του Point.
### setX(int value) {#setX-int-}
```
public final void setX(int value)
```


Ορίζει τη συντεταγμένη x αυτού του Point.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int | η συντεταγμένη x αυτού του Point. |

### getY() {#getY--}
```
public final int getY()
```


Αποκτά τη συντεταγμένη y αυτού του Point.

**Returns:**
int - η συντεταγμένη y αυτού του Point.
### setY(int value) {#setY-int-}
```
public final void setY(int value)
```


Ορίζει τη συντεταγμένη y αυτού του Point.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int | η συντεταγμένη y αυτού του Point. |

### isEmpty() {#isEmpty--}
```
public final boolean isEmpty()
```


Αποκτά μια τιμή που υποδεικνύει εάν αυτό το [Point](../../com.aspose.drawing/point) είναι κενό.

Τιμή: `true` εάν και τα X και Y είναι 0· διαφορετικά, `false`.

**Returns:**
boolean - μια τιμή που υποδεικνύει εάν αυτό το [Point](../../com.aspose.drawing/point) είναι κενό.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Επιστρέφει έναν κωδικό κατακερματισμού για αυτό το [Point](../../com.aspose.drawing/point).

**Returns:**
int - Μια ακέραια τιμή που καθορίζει μια τιμή κατακερματισμού για αυτό το [Point](../../com.aspose.drawing/point).
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Καθορίζει εάν αυτό το [Point](../../com.aspose.drawing/point) περιέχει τις ίδιες συντεταγμένες με το καθορισμένο Object.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | java.lang.Object | Το Object για δοκιμή. |

**Returns:**
boolean - `true` εάν το obj είναι Point και έχει τις ίδιες συντεταγμένες με αυτό το [Point](../../com.aspose.drawing/point).
### offset(int dx, int dy) {#offset-int-int-}
```
public final void offset(int dx, int dy)
```


Μετατοπίζει αυτό το [Point](../../com.aspose.drawing/point) κατά το καθορισμένο ποσό.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| dx | int | Το ποσό για μετατόπιση της συντεταγμένης x. |
| dy | int | Το ποσό για μετατόπιση της συντεταγμένης y. |

### offset(Point p) {#offset-com.aspose.drawing.Point-}
```
public final void offset(Point p)
```


Μετατοπίζει αυτό το [Point](../../com.aspose.drawing/point) κατά το καθορισμένο [Point](../../com.aspose.drawing/point).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| p | [Point](../../com.aspose.drawing/point) | Το [Point](../../com.aspose.drawing/point) που χρησιμοποιείται για μετατόπιση αυτού του [Point](../../com.aspose.drawing/point). |

### equals(Point other) {#equals-com.aspose.drawing.Point-}
```
public final boolean equals(Point other)
```


Δοκιμάζει εάν η άλλη δομή [Point](../../com.aspose.drawing/point) έχει την ίδια θέση με αυτή τη δομή [Point](../../com.aspose.drawing/point).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| other | [Point](../../com.aspose.drawing/point) | Άλλο σημείο για δοκιμή |

**Returns:**
boolean - Αυτή η μέθοδος επιστρέφει `true` εάν η άλλη δομή [Point](../../com.aspose.drawing/point) και οι ιδιότητές της X και Y είναι ίσες με τις αντίστοιχες ιδιότητες της δομής αυτού του [Point](../../com.aspose.drawing/point); διαφορετικά, `false`.
### CloneTo(Point that) {#CloneTo-com.aspose.drawing.Point-}
```
public void CloneTo(Point that)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| that | [Point](../../com.aspose.drawing/point) |  |

### Clone() {#Clone--}
```
public Point Clone()
```




**Returns:**
[Point](../../com.aspose.drawing/point)
### clone() {#clone--}
```
public Object clone()
```




**Returns:**
java.lang.Object
