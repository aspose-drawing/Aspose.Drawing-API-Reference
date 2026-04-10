---
title: SizeF
second_title: Αναφορά API του Aspose.Drawing for Java
description: Αποθηκεύει ένα ζεύγος αριθμών κινητής υποδιαστολής, συνήθως το πλάτος και το ύψος ενός ορθογωνίου.
type: docs
weight: 43
url: /el/java/com.aspose.drawing/sizef/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable, java.lang.Cloneable
```
public class SizeF extends Struct<SizeF> implements System.IEquatable<SizeF>, Cloneable
```

Stores an ordered pair of floating-point numbers, typically the width and height of a rectangle.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [SizeF()](#SizeF--) |  |
| [SizeF(float width, float height)](#SizeF-float-float-) | Αρχικοποιεί μια νέα παρουσία της δομής SizeF από τις καθορισμένες διαστάσεις. |
| [SizeF(PointF pt)](#SizeF-com.aspose.drawing.PointF-) | Αρχικοποιεί μια νέα παρουσία της δομής [SizeF](../../com.aspose.drawing/sizef). |
| [SizeF(SizeF size)](#SizeF-com.aspose.drawing.SizeF-) | Αρχικοποιεί μια νέα παρουσία της δομής [SizeF](../../com.aspose.drawing/sizef). |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [op_Equality(SizeF sz1, SizeF sz2)](#op-Equality-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-) | Δοκιμάζει εάν δύο δομές [SizeF](../../com.aspose.drawing/sizef) είναι ίσες. |
| [op_Inequality(SizeF sz1, SizeF sz2)](#op-Inequality-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-) | Δοκιμάζει εάν δύο δομές [SizeF](../../com.aspose.drawing/sizef) είναι διαφορετικές. |
| [add(SizeF sz1, SizeF sz2)](#add-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-) | Προσθέτει το πλάτος και το ύψος μιας δομής [SizeF](../../com.aspose.drawing/sizef) στο πλάτος και το ύψος μιας άλλης δομής [SizeF](../../com.aspose.drawing/sizef). |
| [subtract(SizeF sz1, SizeF sz2)](#subtract-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-) | Αφαιρεί το πλάτος και το ύψος μιας δομής [SizeF](../../com.aspose.drawing/sizef) από το πλάτος και το ύψος μιας άλλης δομής [SizeF](../../com.aspose.drawing/sizef). |
| [op_Addition(SizeF sz1, SizeF sz2)](#op-Addition-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-) | Προσθέτει το πλάτος και το ύψος μιας δομής [SizeF](../../com.aspose.drawing/sizef) στο πλάτος και το ύψος μιας άλλης δομής [SizeF](../../com.aspose.drawing/sizef). |
| [op_Subtraction(SizeF sz1, SizeF sz2)](#op-Subtraction-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-) | Αφαιρεί το πλάτος και το ύψος μιας δομής [SizeF](../../com.aspose.drawing/sizef) από το πλάτος και το ύψος μιας άλλης δομής [SizeF](../../com.aspose.drawing/sizef). |
| [op_Multiply(float left, SizeF right)](#op-Multiply-float-com.aspose.drawing.SizeF-) | Πολλαπλασιάζει το [SizeF](../../com.aspose.drawing/sizef) με ένα `float` παράγοντας το [SizeF](../../com.aspose.drawing/sizef). |
| [op_Multiply(SizeF left, float right)](#op-Multiply-com.aspose.drawing.SizeF-float-) | Πολλαπλασιάζει το [SizeF](../../com.aspose.drawing/sizef) με ένα `float` παράγοντας το [SizeF](../../com.aspose.drawing/sizef). |
| [op_Division(SizeF left, float right)](#op-Division-com.aspose.drawing.SizeF-float-) | Διαιρεί το [SizeF](../../com.aspose.drawing/sizef) με ένα `float` παράγοντας το [SizeF](../../com.aspose.drawing/sizef). |
| [to_PointF(SizeF size)](#to-PointF-com.aspose.drawing.SizeF-) |  |
| [isEquals(SizeF obj1, SizeF obj2)](#isEquals-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-) |  |
| [getEmpty()](#getEmpty--) |  |
| [isEmpty()](#isEmpty--) | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η δομή [SizeF](../../com.aspose.drawing/sizef) έχει μηδενικό πλάτος και ύψος. |
| [getWidth()](#getWidth--) | Λαμβάνει το οριζόντιο συστατικό αυτής της δομής SizeF. |
| [setWidth(float value)](#setWidth-float-) | Ορίζει το οριζόντιο συστατικό αυτής της δομής SizeF. |
| [getHeight()](#getHeight--) | Λαμβάνει το κατακόρυφο συστατικό αυτής της δομής SizeF. |
| [setHeight(float value)](#setHeight-float-) | Ορίζει το κατακόρυφο συστατικό αυτής της δομής SizeF. |
| [hashCode()](#hashCode--) | Επιστρέφει έναν κωδικό κατακερματισμού για αυτή τη δομή [SizeF](../../com.aspose.drawing/sizef). |
| [toString()](#toString--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Δοκιμάζει αν το καθορισμένο αντικείμενο είναι μια δομή [SizeF](../../com.aspose.drawing/sizef) με τις ίδιες διαστάσεις με αυτή τη δομή [SizeF](../../com.aspose.drawing/sizef). |
| [toSize()](#toSize--) | Μετατρέπει μια δομή [SizeF](../../com.aspose.drawing/sizef) σε μια δομή [Size](../../com.aspose.drawing/size). |
| [toPointF()](#toPointF--) | Μετατρέπει μια δομή [SizeF](../../com.aspose.drawing/sizef) σε μια δομή [PointF](../../com.aspose.drawing/pointf). |
| [equals(SizeF other)](#equals-com.aspose.drawing.SizeF-) | Δοκιμάζει εάν άλλη δομή [SizeF](../../com.aspose.drawing/sizef) έχει το ίδιο μέγεθος με αυτή τη δομή [SizeF](../../com.aspose.drawing/sizef). |
| [CloneTo(SizeF that)](#CloneTo-com.aspose.drawing.SizeF-) |  |
| [Clone()](#Clone--) |  |
| [clone()](#clone--) |  |
### SizeF() {#SizeF--}
```
public SizeF()
```


### SizeF(float width, float height) {#SizeF-float-float-}
```
public SizeF(float width, float height)
```


Αρχικοποιεί μια νέα παρουσία της δομής SizeF από τις καθορισμένες διαστάσεις.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| width | float | Το συστατικό πλάτους της νέας δομής SizeF. |
| height | float | Το συστατικό ύψους της νέας δομής SizeF. |

### SizeF(PointF pt) {#SizeF-com.aspose.drawing.PointF-}
```
public SizeF(PointF pt)
```


Αρχικοποιεί μια νέα παρουσία της δομής [SizeF](../../com.aspose.drawing/sizef).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pt | [PointF](../../com.aspose.drawing/pointf) | Η δομή [PointF](../../com.aspose.drawing/pointf) από την οποία θα αρχικοποιηθεί αυτή η δομή [SizeF](../../com.aspose.drawing/sizef). |

### SizeF(SizeF size) {#SizeF-com.aspose.drawing.SizeF-}
```
public SizeF(SizeF size)
```


Αρχικοποιεί μια νέα παρουσία της δομής [SizeF](../../com.aspose.drawing/sizef).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.drawing/sizef) | Η δομή [SizeF](../../com.aspose.drawing/sizef) από την οποία θα δημιουργηθεί η νέα δομή [SizeF](../../com.aspose.drawing/sizef). |

### op_Equality(SizeF sz1, SizeF sz2) {#op-Equality-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-}
```
public static boolean op_Equality(SizeF sz1, SizeF sz2)
```


Δοκιμάζει εάν δύο δομές [SizeF](../../com.aspose.drawing/sizef) είναι ίσες.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sz1 | [SizeF](../../com.aspose.drawing/sizef) | Η δομή [SizeF](../../com.aspose.drawing/sizef) στην αριστερή πλευρά του τελεστή ισότητας. |
| sz2 | [SizeF](../../com.aspose.drawing/sizef) | Η δομή [SizeF](../../com.aspose.drawing/sizef) στη δεξιά πλευρά του τελεστή ισότητας. |

**Returns:**
boolean - Αυτός ο τελεστής επιστρέφει true εάν τα `sz1` και `sz2` έχουν ίσο πλάτος και ύψος· διαφορετικά, false.
### op_Inequality(SizeF sz1, SizeF sz2) {#op-Inequality-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-}
```
public static boolean op_Inequality(SizeF sz1, SizeF sz2)
```


Δοκιμάζει εάν δύο δομές [SizeF](../../com.aspose.drawing/sizef) είναι διαφορετικές.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sz1 | [SizeF](../../com.aspose.drawing/sizef) | Η δομή [SizeF](../../com.aspose.drawing/sizef) στην αριστερή πλευρά του τελεστή ανισότητας. |
| sz2 | [SizeF](../../com.aspose.drawing/sizef) | Η δομή [SizeF](../../com.aspose.drawing/sizef) στη δεξιά πλευρά του τελεστή ανισότητας. |

**Returns:**
boolean - Αυτός ο τελεστής επιστρέφει true εάν τα `sz1` και `sz2` διαφέρουν είτε στο πλάτος είτε στο ύψος· false εάν τα `sz1` και `sz2` είναι ίσα.
### add(SizeF sz1, SizeF sz2) {#add-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-}
```
public static SizeF add(SizeF sz1, SizeF sz2)
```


Προσθέτει το πλάτος και το ύψος μιας δομής [SizeF](../../com.aspose.drawing/sizef) στο πλάτος και το ύψος μιας άλλης δομής [SizeF](../../com.aspose.drawing/sizef).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sz1 | [SizeF](../../com.aspose.drawing/sizef) | Η πρώτη δομή [SizeF](../../com.aspose.drawing/sizef) για προσθήκη. |
| sz2 | [SizeF](../../com.aspose.drawing/sizef) | Η δεύτερη δομή [SizeF](../../com.aspose.drawing/sizef) για προσθήκη. |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - A [SizeF](../../com.aspose.drawing/sizef) structure that is the result of the addition operation.
### subtract(SizeF sz1, SizeF sz2) {#subtract-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-}
```
public static SizeF subtract(SizeF sz1, SizeF sz2)
```


Αφαιρεί το πλάτος και το ύψος μιας δομής [SizeF](../../com.aspose.drawing/sizef) από το πλάτος και το ύψος μιας άλλης δομής [SizeF](../../com.aspose.drawing/sizef).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sz1 | [SizeF](../../com.aspose.drawing/sizef) | Η δομή [SizeF](../../com.aspose.drawing/sizef) στην αριστερή πλευρά του τελεστή αφαίρεσης. |
| sz2 | [SizeF](../../com.aspose.drawing/sizef) | Η [SizeF](../../com.aspose.drawing/sizef) δομή στη δεξιά πλευρά του τελεστή αφαίρεσης. |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - A [SizeF](../../com.aspose.drawing/sizef) structure that is a result of the subtraction operation.
### op_Addition(SizeF sz1, SizeF sz2) {#op-Addition-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-}
```
public static SizeF op_Addition(SizeF sz1, SizeF sz2)
```


Προσθέτει το πλάτος και το ύψος μιας δομής [SizeF](../../com.aspose.drawing/sizef) στο πλάτος και το ύψος μιας άλλης δομής [SizeF](../../com.aspose.drawing/sizef).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sz1 | [SizeF](../../com.aspose.drawing/sizef) | Η πρώτη δομή [SizeF](../../com.aspose.drawing/sizef) για προσθήκη. |
| sz2 | [SizeF](../../com.aspose.drawing/sizef) | Η δεύτερη δομή [SizeF](../../com.aspose.drawing/sizef) για προσθήκη. |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - A [Size](../../com.aspose.drawing/size) structure that is the result of the addition operation.
### op_Subtraction(SizeF sz1, SizeF sz2) {#op-Subtraction-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-}
```
public static SizeF op_Subtraction(SizeF sz1, SizeF sz2)
```


Αφαιρεί το πλάτος και το ύψος μιας δομής [SizeF](../../com.aspose.drawing/sizef) από το πλάτος και το ύψος μιας άλλης δομής [SizeF](../../com.aspose.drawing/sizef).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sz1 | [SizeF](../../com.aspose.drawing/sizef) | Η δομή [SizeF](../../com.aspose.drawing/sizef) στην αριστερή πλευρά του τελεστή αφαίρεσης. |
| sz2 | [SizeF](../../com.aspose.drawing/sizef) | Η [SizeF](../../com.aspose.drawing/sizef) δομή στη δεξιά πλευρά του τελεστή αφαίρεσης. |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - A [SizeF](../../com.aspose.drawing/sizef) that is the result of the subtraction operation.
### op_Multiply(float left, SizeF right) {#op-Multiply-float-com.aspose.drawing.SizeF-}
```
public static SizeF op_Multiply(float left, SizeF right)
```


Πολλαπλασιάζει το [SizeF](../../com.aspose.drawing/sizef) με ένα `float` παράγοντας το [SizeF](../../com.aspose.drawing/sizef).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| αριστερά | float | Πολλαπλασιαστής τύπου `float`. |
| right | [SizeF](../../com.aspose.drawing/sizef) | Πολλαπλασιαστής τύπου [SizeF](../../com.aspose.drawing/sizef). |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - Product of type [SizeF](../../com.aspose.drawing/sizef).
### op_Multiply(SizeF left, float right) {#op-Multiply-com.aspose.drawing.SizeF-float-}
```
public static SizeF op_Multiply(SizeF left, float right)
```


Πολλαπλασιάζει το [SizeF](../../com.aspose.drawing/sizef) με ένα `float` παράγοντας το [SizeF](../../com.aspose.drawing/sizef).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| left | [SizeF](../../com.aspose.drawing/sizef) | Πολλαπλασιαστής τύπου [SizeF](../../com.aspose.drawing/sizef). |
| δεξιά | float | Πολλαπλασιαστής τύπου `float`. |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - Product of type [SizeF](../../com.aspose.drawing/sizef).
### op_Division(SizeF left, float right) {#op-Division-com.aspose.drawing.SizeF-float-}
```
public static SizeF op_Division(SizeF left, float right)
```


Διαιρεί το [SizeF](../../com.aspose.drawing/sizef) με ένα `float` παράγοντας το [SizeF](../../com.aspose.drawing/sizef).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| left | [SizeF](../../com.aspose.drawing/sizef) | Διανυψιζόμενος τύπου [SizeF](../../com.aspose.drawing/sizef). |
| δεξιά | float | Διαιρέτης τύπου `int`. |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - Result of type [SizeF](../../com.aspose.drawing/sizef).
### to_PointF(SizeF size) {#to-PointF-com.aspose.drawing.SizeF-}
```
public static PointF to_PointF(SizeF size)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.drawing/sizef) |  |

**Returns:**
[PointF](../../com.aspose.drawing/pointf)
### isEquals(SizeF obj1, SizeF obj2) {#isEquals-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-}
```
public static boolean isEquals(SizeF obj1, SizeF obj2)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj1 | [SizeF](../../com.aspose.drawing/sizef) |  |
| obj2 | [SizeF](../../com.aspose.drawing/sizef) |  |

**Returns:**
boolean
### getEmpty() {#getEmpty--}
```
public static SizeF getEmpty()
```




**Returns:**
[SizeF](../../com.aspose.drawing/sizef)
### isEmpty() {#isEmpty--}
```
public final boolean isEmpty()
```


Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η δομή [SizeF](../../com.aspose.drawing/sizef) έχει μηδενικό πλάτος και ύψος.

**Returns:**
boolean - μια τιμή που υποδεικνύει εάν αυτή η [SizeF](../../com.aspose.drawing/sizef) δομή έχει μηδενικό πλάτος και ύψος.
### getWidth() {#getWidth--}
```
public final float getWidth()
```


Λαμβάνει το οριζόντιο συστατικό αυτής της δομής SizeF.

**Returns:**
float - το οριζόντιο συστατικό αυτής της δομής SizeF.
### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```


Ορίζει το οριζόντιο συστατικό αυτής της δομής SizeF.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float | το οριζόντιο συστατικό αυτής της δομής SizeF. |

### getHeight() {#getHeight--}
```
public final float getHeight()
```


Λαμβάνει το κατακόρυφο συστατικό αυτής της δομής SizeF.

**Returns:**
float - το κάθετο συστατικό αυτής της δομής SizeF.
### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```


Ορίζει το κατακόρυφο συστατικό αυτής της δομής SizeF.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float | το κάθετο συστατικό αυτής της δομής SizeF. |

### hashCode() {#hashCode--}
```
public int hashCode()
```


Επιστρέφει έναν κωδικό κατακερματισμού για αυτή τη δομή [SizeF](../../com.aspose.drawing/sizef).

**Returns:**
int - Μια ακέραια τιμή που καθορίζει μια τιμή κατακερματισμού για αυτή τη [SizeF](../../com.aspose.drawing/sizef) δομή.
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


Δοκιμάζει αν το καθορισμένο αντικείμενο είναι μια δομή [SizeF](../../com.aspose.drawing/sizef) με τις ίδιες διαστάσεις με αυτή τη δομή [SizeF](../../com.aspose.drawing/sizef).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | java.lang.Object | Το Object για δοκιμή. |

**Returns:**
boolean - Αυτή η μέθοδος επιστρέφει `true` εάν το obj είναι ένα [SizeF](../../com.aspose.drawing/sizef) και έχει το ίδιο πλάτος και ύψος με αυτό το SizeF· διαφορετικά, `false`.
### toSize() {#toSize--}
```
public final Size toSize()
```


Μετατρέπει μια δομή [SizeF](../../com.aspose.drawing/sizef) σε μια δομή [Size](../../com.aspose.drawing/size).

**Returns:**
[Size](../../com.aspose.drawing/size) - Returns a [Size](../../com.aspose.drawing/size) structure.
### toPointF() {#toPointF--}
```
public final PointF toPointF()
```


Μετατρέπει μια δομή [SizeF](../../com.aspose.drawing/sizef) σε μια δομή [PointF](../../com.aspose.drawing/pointf).

**Returns:**
[PointF](../../com.aspose.drawing/pointf) - Returns a [PointF](../../com.aspose.drawing/pointf) structure.
### equals(SizeF other) {#equals-com.aspose.drawing.SizeF-}
```
public final boolean equals(SizeF other)
```


Δοκιμάζει εάν άλλη δομή [SizeF](../../com.aspose.drawing/sizef) έχει το ίδιο μέγεθος με αυτή τη δομή [SizeF](../../com.aspose.drawing/sizef).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| other | [SizeF](../../com.aspose.drawing/sizef) | Άλλο μέγεθος για δοκιμή |

**Returns:**
boolean - Αυτή η μέθοδος επιστρέφει `true` εάν η άλλη [SizeF](../../com.aspose.drawing/sizef) δομή και οι ιδιότητές της Width και Height είναι ίσες με τις αντίστοιχες ιδιότητες αυτής της [SizeF](../../com.aspose.drawing/sizef) δομής· διαφορετικά, `false`.
### CloneTo(SizeF that) {#CloneTo-com.aspose.drawing.SizeF-}
```
public void CloneTo(SizeF that)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| that | [SizeF](../../com.aspose.drawing/sizef) |  |

### Clone() {#Clone--}
```
public SizeF Clone()
```




**Returns:**
[SizeF](../../com.aspose.drawing/sizef)
### clone() {#clone--}
```
public Object clone()
```




**Returns:**
java.lang.Object
