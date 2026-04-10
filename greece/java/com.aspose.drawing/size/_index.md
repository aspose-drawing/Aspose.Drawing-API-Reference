---
title: Size
second_title: Αναφορά API του Aspose.Drawing for Java
description: Αποθηκεύει ένα ταξινομημένο ζεύγος ακεραίων, συνήθως το πλάτος και το ύψος ενός ορθογωνίου.
type: docs
weight: 42
url: /el/java/com.aspose.drawing/size/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable, java.lang.Cloneable
```
public class Size extends Struct<Size> implements System.IEquatable<Size>, Cloneable
```

Stores an ordered pair of integers, typically the width and height of a rectangle.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [Size()](#Size--) |  |
| [Size(Point pt)](#Size-com.aspose.drawing.Point-) | Αρχικοποιεί μια νέα παρουσία της δομής [Size](../../com.aspose.drawing/size) από το καθορισμένο [Point](../../com.aspose.drawing/point). |
| [Size(int width, int height)](#Size-int-int-) | Αρχικοποιεί μια νέα παρουσία της δομής [Size](../../com.aspose.drawing/size) από τις καθορισμένες διαστάσεις. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [to_SizeF(Size p)](#to-SizeF-com.aspose.drawing.Size-) | Μετατρέπει το καθορισμένο [Size](../../com.aspose.drawing/size) σε [SizeF](../../com.aspose.drawing/sizef). |
| [op_Addition(Size sz1, Size sz2)](#op-Addition-com.aspose.drawing.Size-com.aspose.drawing.Size-) | Προσθέτει το πλάτος και το ύψος μιας δομής [Size](../../com.aspose.drawing/size) στο πλάτος και το ύψος μιας άλλης δομής [Size](../../com.aspose.drawing/size). |
| [op_Subtraction(Size sz1, Size sz2)](#op-Subtraction-com.aspose.drawing.Size-com.aspose.drawing.Size-) | Αφαιρεί το πλάτος και το ύψος μιας δομής [Size](../../com.aspose.drawing/size) από το πλάτος και το ύψος μιας άλλης δομής [Size](../../com.aspose.drawing/size). |
| [op_Multiply(int left, Size right)](#op-Multiply-int-com.aspose.drawing.Size-) | Πολλαπλασιάζει ένα [Size](../../com.aspose.drawing/size) με έναν `int` παράγοντας [Size](../../com.aspose.drawing/size). |
| [op_Multiply(Size left, int right)](#op-Multiply-com.aspose.drawing.Size-int-) | Πολλαπλασιάζει το [Size](../../com.aspose.drawing/size) με έναν `int` παράγοντας [Size](../../com.aspose.drawing/size). |
| [op_Division(Size left, int right)](#op-Division-com.aspose.drawing.Size-int-) | Διαιρεί το [Size](../../com.aspose.drawing/size) με έναν `int` παράγοντας [Size](../../com.aspose.drawing/size). |
| [op_Multiply(float left, Size right)](#op-Multiply-float-com.aspose.drawing.Size-) | Πολλαπλασιάζει το [Size](../../com.aspose.drawing/size) με ένα `float` παράγοντας [SizeF](../../com.aspose.drawing/sizef). |
| [op_Multiply(Size left, float right)](#op-Multiply-com.aspose.drawing.Size-float-) | Πολλαπλασιάζει το [Size](../../com.aspose.drawing/size) με ένα `float` παράγοντας [SizeF](../../com.aspose.drawing/sizef). |
| [op_Division(Size left, float right)](#op-Division-com.aspose.drawing.Size-float-) | Διαιρεί το [Size](../../com.aspose.drawing/size) με έναν `float` παράγοντας το [SizeF](../../com.aspose.drawing/sizef). |
| [op_Equality(Size sz1, Size sz2)](#op-Equality-com.aspose.drawing.Size-com.aspose.drawing.Size-) | Δοκιμάζει εάν δύο δομές [Size](../../com.aspose.drawing/size) είναι ίσες. |
| [op_Inequality(Size sz1, Size sz2)](#op-Inequality-com.aspose.drawing.Size-com.aspose.drawing.Size-) | Δοκιμάζει εάν δύο δομές [Size](../../com.aspose.drawing/size) είναι διαφορετικές. |
| [to_Point(Size size)](#to-Point-com.aspose.drawing.Size-) | Μετατρέπει το καθορισμένο [Size](../../com.aspose.drawing/size) σε ένα [Point](../../com.aspose.drawing/point). |
| [add(Size sz1, Size sz2)](#add-com.aspose.drawing.Size-com.aspose.drawing.Size-) | Προσθέτει το πλάτος και το ύψος μιας δομής [Size](../../com.aspose.drawing/size) στο πλάτος και το ύψος μιας άλλης δομής [Size](../../com.aspose.drawing/size). |
| [ceiling(SizeF value)](#ceiling-com.aspose.drawing.SizeF-) | Μετατρέπει τη δομή [SizeF](../../com.aspose.drawing/sizef) σε δομή [Size](../../com.aspose.drawing/size) στρογγυλοποιώντας τις τιμές της δομής [Size](../../com.aspose.drawing/size) προς τα επόμενα μεγαλύτερα ακέραια. |
| [subtract(Size sz1, Size sz2)](#subtract-com.aspose.drawing.Size-com.aspose.drawing.Size-) | Αφαιρεί το πλάτος και το ύψος μιας δομής [Size](../../com.aspose.drawing/size) από το πλάτος και το ύψος μιας άλλης δομής [Size](../../com.aspose.drawing/size). |
| [truncate(SizeF value)](#truncate-com.aspose.drawing.SizeF-) | Μετατρέπει τη δομή [SizeF](../../com.aspose.drawing/sizef) σε δομή [Size](../../com.aspose.drawing/size) περικόπτοντας τις τιμές της δομής [SizeF](../../com.aspose.drawing/sizef) προς τα επόμενα χαμηλότερα ακέραια. |
| [round(SizeF value)](#round-com.aspose.drawing.SizeF-) | Μετατρέπει τη δομή [SizeF](../../com.aspose.drawing/sizef) σε δομή [Size](../../com.aspose.drawing/size) στρογγυλοποιώντας τις τιμές της δομής [SizeF](../../com.aspose.drawing/sizef) στο πλησιέστερο ακέραιο. |
| [isEquals(Size obj1, Size obj2)](#isEquals-com.aspose.drawing.Size-com.aspose.drawing.Size-) |  |
| [getEmpty()](#getEmpty--) |  |
| [isEmpty()](#isEmpty--) | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτό το [Size](../../com.aspose.drawing/size) έχει πλάτος και ύψος 0. |
| [getWidth()](#getWidth--) | Λαμβάνει το οριζόντιο συστατικό αυτού του [Size](../../com.aspose.drawing/size). |
| [setWidth(int value)](#setWidth-int-) | Ορίζει το οριζόντιο συστατικό αυτού του [Size](../../com.aspose.drawing/size). |
| [getHeight()](#getHeight--) | Λαμβάνει το κάθετο συστατικό αυτού του [Size](../../com.aspose.drawing/size). |
| [setHeight(int value)](#setHeight-int-) | Ορίζει το κάθετο συστατικό αυτού του [Size](../../com.aspose.drawing/size). |
| [equals(Object obj)](#equals-java.lang.Object-) | Δοκιμάζει αν το καθορισμένο αντικείμενο είναι ένα [Size](../../com.aspose.drawing/size) με τις ίδιες διαστάσεις με αυτό το [Size](../../com.aspose.drawing/size). |
| [hashCode()](#hashCode--) | Επιστρέφει έναν κωδικό κατακερματισμού για αυτή τη δομή [Size](../../com.aspose.drawing/size). |
| [toString()](#toString--) |  |
| [equals(Size other)](#equals-com.aspose.drawing.Size-) | Δοκιμάζει εάν άλλη δομή [Size](../../com.aspose.drawing/size) έχει το ίδιο μέγεθος με αυτή τη δομή [Size](../../com.aspose.drawing/size). |
| [CloneTo(Size that)](#CloneTo-com.aspose.drawing.Size-) |  |
| [Clone()](#Clone--) |  |
| [clone()](#clone--) |  |
### Size() {#Size--}
```
public Size()
```


### Size(Point pt) {#Size-com.aspose.drawing.Point-}
```
public Size(Point pt)
```


Αρχικοποιεί μια νέα παρουσία της δομής [Size](../../com.aspose.drawing/size) από το καθορισμένο [Point](../../com.aspose.drawing/point).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pt | [Point](../../com.aspose.drawing/point) | Το [Point](../../com.aspose.drawing/point) από το οποίο θα αρχικοποιηθεί αυτό το [Size](../../com.aspose.drawing/size). |

### Size(int width, int height) {#Size-int-int-}
```
public Size(int width, int height)
```


Αρχικοποιεί μια νέα παρουσία της δομής [Size](../../com.aspose.drawing/size) από τις καθορισμένες διαστάσεις.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| width | int | Το συστατικό πλάτους του νέου [Size](../../com.aspose.drawing/size). |
| height | int | Το συστατικό ύψους του νέου [Size](../../com.aspose.drawing/size). |

### to_SizeF(Size p) {#to-SizeF-com.aspose.drawing.Size-}
```
public static SizeF to_SizeF(Size p)
```


Μετατρέπει το καθορισμένο [Size](../../com.aspose.drawing/size) σε [SizeF](../../com.aspose.drawing/sizef).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| p | [Size](../../com.aspose.drawing/size) | Το [Size](../../com.aspose.drawing/size) προς μετατροπή. |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - The [SizeF](../../com.aspose.drawing/sizef) structure to which this operator converts.
### op_Addition(Size sz1, Size sz2) {#op-Addition-com.aspose.drawing.Size-com.aspose.drawing.Size-}
```
public static Size op_Addition(Size sz1, Size sz2)
```


Προσθέτει το πλάτος και το ύψος μιας δομής [Size](../../com.aspose.drawing/size) στο πλάτος και το ύψος μιας άλλης δομής [Size](../../com.aspose.drawing/size).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sz1 | [Size](../../com.aspose.drawing/size) | Το πρώτο [Size](../../com.aspose.drawing/size) προς προσθήκη. |
| sz2 | [Size](../../com.aspose.drawing/size) | Το δεύτερο [Size](../../com.aspose.drawing/size) προς προσθήκη. |

**Returns:**
[Size](../../com.aspose.drawing/size) - A [Size](../../com.aspose.drawing/size) structure that is the result of the addition operation.
### op_Subtraction(Size sz1, Size sz2) {#op-Subtraction-com.aspose.drawing.Size-com.aspose.drawing.Size-}
```
public static Size op_Subtraction(Size sz1, Size sz2)
```


Αφαιρεί το πλάτος και το ύψος μιας δομής [Size](../../com.aspose.drawing/size) από το πλάτος και το ύψος μιας άλλης δομής [Size](../../com.aspose.drawing/size).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sz1 | [Size](../../com.aspose.drawing/size) | Η δομή [Size](../../com.aspose.drawing/size) στην αριστερή πλευρά του τελεστή αφαίρεσης. |
| sz2 | [Size](../../com.aspose.drawing/size) | Η δομή [Size](../../com.aspose.drawing/size) στη δεξιά πλευρά του τελεστή αφαίρεσης. |

**Returns:**
[Size](../../com.aspose.drawing/size) - A [Size](../../com.aspose.drawing/size) structure that is the result of the subtraction operation.
### op_Multiply(int left, Size right) {#op-Multiply-int-com.aspose.drawing.Size-}
```
public static Size op_Multiply(int left, Size right)
```


Πολλαπλασιάζει ένα [Size](../../com.aspose.drawing/size) με έναν `int` παράγοντας [Size](../../com.aspose.drawing/size).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| αριστερά | int | Πολλαπλασιαστής τύπου `int`. |
| right | [Size](../../com.aspose.drawing/size) | Πολλαπλασιαζόμενος τύπου [Size](../../com.aspose.drawing/size). |

**Returns:**
[Size](../../com.aspose.drawing/size) - Product of type [Size](../../com.aspose.drawing/size).
### op_Multiply(Size left, int right) {#op-Multiply-com.aspose.drawing.Size-int-}
```
public static Size op_Multiply(Size left, int right)
```


Πολλαπλασιάζει το [Size](../../com.aspose.drawing/size) με έναν `int` παράγοντας [Size](../../com.aspose.drawing/size).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| left | [Size](../../com.aspose.drawing/size) | Πολλαπλασιαζόμενος τύπου [Size](../../com.aspose.drawing/size). |
| δεξιά | int | Πολλαπλασιαστής τύπου `int`. |

**Returns:**
[Size](../../com.aspose.drawing/size) - Product of type [Size](../../com.aspose.drawing/size).
### op_Division(Size left, int right) {#op-Division-com.aspose.drawing.Size-int-}
```
public static Size op_Division(Size left, int right)
```


Διαιρεί το [Size](../../com.aspose.drawing/size) με έναν `int` παράγοντας [Size](../../com.aspose.drawing/size).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| left | [Size](../../com.aspose.drawing/size) | Διαιρετέος τύπου [Size](../../com.aspose.drawing/size). |
| δεξιά | int | Διαιρέτης τύπου `int`. |

**Returns:**
[Size](../../com.aspose.drawing/size) - Result of type [Size](../../com.aspose.drawing/size).
### op_Multiply(float left, Size right) {#op-Multiply-float-com.aspose.drawing.Size-}
```
public static SizeF op_Multiply(float left, Size right)
```


Πολλαπλασιάζει το [Size](../../com.aspose.drawing/size) με ένα `float` παράγοντας [SizeF](../../com.aspose.drawing/sizef).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| αριστερά | float | Πολλαπλασιαστής τύπου `float`. |
| right | [Size](../../com.aspose.drawing/size) | Πολλαπλασιαζόμενος τύπου [Size](../../com.aspose.drawing/size). |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - Product of type [SizeF](../../com.aspose.drawing/sizef).
### op_Multiply(Size left, float right) {#op-Multiply-com.aspose.drawing.Size-float-}
```
public static SizeF op_Multiply(Size left, float right)
```


Πολλαπλασιάζει το [Size](../../com.aspose.drawing/size) με ένα `float` παράγοντας [SizeF](../../com.aspose.drawing/sizef).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| left | [Size](../../com.aspose.drawing/size) | Πολλαπλασιαζόμενος τύπου [Size](../../com.aspose.drawing/size). |
| δεξιά | float | Πολλαπλασιαστής τύπου `float`. |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - Product of type [SizeF](../../com.aspose.drawing/sizef).
### op_Division(Size left, float right) {#op-Division-com.aspose.drawing.Size-float-}
```
public static SizeF op_Division(Size left, float right)
```


Διαιρεί το [Size](../../com.aspose.drawing/size) με έναν `float` παράγοντας το [SizeF](../../com.aspose.drawing/sizef).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| left | [Size](../../com.aspose.drawing/size) | Διαιρετέος τύπου [Size](../../com.aspose.drawing/size). |
| δεξιά | float | Διαιρέτης τύπου `int`. |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - Result of type [SizeF](../../com.aspose.drawing/sizef).
### op_Equality(Size sz1, Size sz2) {#op-Equality-com.aspose.drawing.Size-com.aspose.drawing.Size-}
```
public static boolean op_Equality(Size sz1, Size sz2)
```


Δοκιμάζει εάν δύο δομές [Size](../../com.aspose.drawing/size) είναι ίσες.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sz1 | [Size](../../com.aspose.drawing/size) | Η δομή [Size](../../com.aspose.drawing/size) στα αριστερά του τελεστή ισότητας. |
| sz2 | [Size](../../com.aspose.drawing/size) | Η δομή [Size](../../com.aspose.drawing/size) στα δεξιά του τελεστή ισότητας. |

**Returns:**
boolean - true εάν `sz1` και `sz2` έχουν ίσο πλάτος και ύψος· διαφορετικά, false.
### op_Inequality(Size sz1, Size sz2) {#op-Inequality-com.aspose.drawing.Size-com.aspose.drawing.Size-}
```
public static boolean op_Inequality(Size sz1, Size sz2)
```


Δοκιμάζει εάν δύο δομές [Size](../../com.aspose.drawing/size) είναι διαφορετικές.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sz1 | [Size](../../com.aspose.drawing/size) | Η δομή [Size](../../com.aspose.drawing/size) στα αριστερά του τελεστή ανισότητας. |
| sz2 | [Size](../../com.aspose.drawing/size) | Η δομή [Size](../../com.aspose.drawing/size) στα δεξιά του τελεστή ανισότητας. |

**Returns:**
boolean - true εάν `sz1` και `sz2` διαφέρουν είτε στο πλάτος είτε στο ύψος· false εάν `sz1` και `sz2` είναι ίσα.
### to_Point(Size size) {#to-Point-com.aspose.drawing.Size-}
```
public static Point to_Point(Size size)
```


Μετατρέπει το καθορισμένο [Size](../../com.aspose.drawing/size) σε ένα [Point](../../com.aspose.drawing/point).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| size | [Size](../../com.aspose.drawing/size) | Το [Size](../../com.aspose.drawing/size) προς μετατροπή. |

**Returns:**
[Point](../../com.aspose.drawing/point) - The [Point](../../com.aspose.drawing/point) structure to which this operator converts.
### add(Size sz1, Size sz2) {#add-com.aspose.drawing.Size-com.aspose.drawing.Size-}
```
public static Size add(Size sz1, Size sz2)
```


Προσθέτει το πλάτος και το ύψος μιας δομής [Size](../../com.aspose.drawing/size) στο πλάτος και το ύψος μιας άλλης δομής [Size](../../com.aspose.drawing/size).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sz1 | [Size](../../com.aspose.drawing/size) | Το πρώτο [Size](../../com.aspose.drawing/size) προς προσθήκη. |
| sz2 | [Size](../../com.aspose.drawing/size) | Το δεύτερο [Size](../../com.aspose.drawing/size) προς προσθήκη. |

**Returns:**
[Size](../../com.aspose.drawing/size) - A [Size](../../com.aspose.drawing/size) structure that is the result of the addition operation.
### ceiling(SizeF value) {#ceiling-com.aspose.drawing.SizeF-}
```
public static Size ceiling(SizeF value)
```


Μετατρέπει τη δομή [SizeF](../../com.aspose.drawing/sizef) σε δομή [Size](../../com.aspose.drawing/size) στρογγυλοποιώντας τις τιμές της δομής [Size](../../com.aspose.drawing/size) προς τα επόμενα μεγαλύτερα ακέραια.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.drawing/sizef) | Η δομή [SizeF](../../com.aspose.drawing/sizef) για μετατροπή. |

**Returns:**
[Size](../../com.aspose.drawing/size) - The [Size](../../com.aspose.drawing/size) structure this method converts to.
### subtract(Size sz1, Size sz2) {#subtract-com.aspose.drawing.Size-com.aspose.drawing.Size-}
```
public static Size subtract(Size sz1, Size sz2)
```


Αφαιρεί το πλάτος και το ύψος μιας δομής [Size](../../com.aspose.drawing/size) από το πλάτος και το ύψος μιας άλλης δομής [Size](../../com.aspose.drawing/size).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sz1 | [Size](../../com.aspose.drawing/size) | Η δομή [Size](../../com.aspose.drawing/size) στην αριστερή πλευρά του τελεστή αφαίρεσης. |
| sz2 | [Size](../../com.aspose.drawing/size) | Η δομή [Size](../../com.aspose.drawing/size) στη δεξιά πλευρά του τελεστή αφαίρεσης. |

**Returns:**
[Size](../../com.aspose.drawing/size) - The [Size](../../com.aspose.drawing/size) that is a result of the subtraction operation.
### truncate(SizeF value) {#truncate-com.aspose.drawing.SizeF-}
```
public static Size truncate(SizeF value)
```


Μετατρέπει τη δομή [SizeF](../../com.aspose.drawing/sizef) σε δομή [Size](../../com.aspose.drawing/size) περικόπτοντας τις τιμές της δομής [SizeF](../../com.aspose.drawing/sizef) προς τα επόμενα χαμηλότερα ακέραια.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.drawing/sizef) | Η δομή [SizeF](../../com.aspose.drawing/sizef) για μετατροπή. |

**Returns:**
[Size](../../com.aspose.drawing/size) - The [Size](../../com.aspose.drawing/size) structure this method converts to.
### round(SizeF value) {#round-com.aspose.drawing.SizeF-}
```
public static Size round(SizeF value)
```


Μετατρέπει τη δομή [SizeF](../../com.aspose.drawing/sizef) σε δομή [Size](../../com.aspose.drawing/size) στρογγυλοποιώντας τις τιμές της δομής [SizeF](../../com.aspose.drawing/sizef) στο πλησιέστερο ακέραιο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.drawing/sizef) | Η δομή [SizeF](../../com.aspose.drawing/sizef) για μετατροπή. |

**Returns:**
[Size](../../com.aspose.drawing/size) - The [Size](../../com.aspose.drawing/size) structure this method converts to.
### isEquals(Size obj1, Size obj2) {#isEquals-com.aspose.drawing.Size-com.aspose.drawing.Size-}
```
public static boolean isEquals(Size obj1, Size obj2)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj1 | [Size](../../com.aspose.drawing/size) |  |
| obj2 | [Size](../../com.aspose.drawing/size) |  |

**Returns:**
boolean
### getEmpty() {#getEmpty--}
```
public static Size getEmpty()
```




**Returns:**
[Size](../../com.aspose.drawing/size)
### isEmpty() {#isEmpty--}
```
public final boolean isEmpty()
```


Λαμβάνει μια τιμή που υποδεικνύει εάν αυτό το [Size](../../com.aspose.drawing/size) έχει πλάτος και ύψος 0.

**Returns:**
boolean - τιμή που υποδεικνύει εάν αυτό το [Size](../../com.aspose.drawing/size) έχει πλάτος και ύψος 0.
### getWidth() {#getWidth--}
```
public final int getWidth()
```


Λαμβάνει το οριζόντιο συστατικό αυτού του [Size](../../com.aspose.drawing/size).

**Returns:**
int - η οριζόντια συνιστώσα αυτού του [Size](../../com.aspose.drawing/size).
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Ορίζει το οριζόντιο συστατικό αυτού του [Size](../../com.aspose.drawing/size).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int | η οριζόντια συνιστώσα αυτού του [Size](../../com.aspose.drawing/size). |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Λαμβάνει το κάθετο συστατικό αυτού του [Size](../../com.aspose.drawing/size).

**Returns:**
int - η κάθετη συνιστώσα αυτού του [Size](../../com.aspose.drawing/size).
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Ορίζει το κάθετο συστατικό αυτού του [Size](../../com.aspose.drawing/size).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int | η κάθετη συνιστώσα αυτού του [Size](../../com.aspose.drawing/size). |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Δοκιμάζει αν το καθορισμένο αντικείμενο είναι ένα [Size](../../com.aspose.drawing/size) με τις ίδιες διαστάσεις με αυτό το [Size](../../com.aspose.drawing/size).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | java.lang.Object | Το Object για δοκιμή. |

**Returns:**
boolean - true εάν `obj` είναι ένα [Size](../../com.aspose.drawing/size) και έχει το ίδιο πλάτος και ύψος με αυτό το [Size](../../com.aspose.drawing/size); διαφορετικά, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Επιστρέφει έναν κωδικό κατακερματισμού για αυτή τη δομή [Size](../../com.aspose.drawing/size).

**Returns:**
int - Μια ακέραια τιμή που καθορίζει μια τιμή κατακερματισμού για αυτή τη δομή [Size](../../com.aspose.drawing/size).
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### equals(Size other) {#equals-com.aspose.drawing.Size-}
```
public final boolean equals(Size other)
```


Δοκιμάζει εάν άλλη δομή [Size](../../com.aspose.drawing/size) έχει το ίδιο μέγεθος με αυτή τη δομή [Size](../../com.aspose.drawing/size).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| other | [Size](../../com.aspose.drawing/size) | Άλλο μέγεθος για δοκιμή |

**Returns:**
boolean - Αυτή η μέθοδος επιστρέφει `true` εάν η άλλη δομή [Size](../../com.aspose.drawing/size) και οι ιδιότητές της Width και Height είναι ίσες με τις αντίστοιχες ιδιότητες αυτής της δομής [Size](../../com.aspose.drawing/size); διαφορετικά, `false`.
### CloneTo(Size that) {#CloneTo-com.aspose.drawing.Size-}
```
public void CloneTo(Size that)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| that | [Size](../../com.aspose.drawing/size) |  |

### Clone() {#Clone--}
```
public Size Clone()
```




**Returns:**
[Size](../../com.aspose.drawing/size)
### clone() {#clone--}
```
public Size clone()
```




**Returns:**
[Size](../../com.aspose.drawing/size)
