---
title: PointF
second_title: Αναφορά API του Aspose.Drawing for Java
description: Represents an ordered pair of floating-point x- and y-coordinates that defines a point in a two-dimensional plane.
type: docs
weight: 37
url: /el/java/com.aspose.drawing/pointf/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable, java.lang.Cloneable
```
public class PointF extends Struct<PointF> implements System.IEquatable<PointF>, Cloneable
```

Represents an ordered pair of floating-point x- and y-coordinates that defines a point in a two-dimensional plane.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [PointF()](#PointF--) |  |
| [PointF(float x, float y)](#PointF-float-float-) | Αρχικοποιεί ένα νέο στιγμιότυπο της δομής PointF με τις καθορισμένες συντεταγμένες. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [op_Addition(PointF pt, Size sz)](#op-Addition-com.aspose.drawing.PointF-com.aspose.drawing.Size-) |  |
| [op_Subtraction(PointF pt, Size sz)](#op-Subtraction-com.aspose.drawing.PointF-com.aspose.drawing.Size-) |  |
| [op_Addition(PointF pt, SizeF sz)](#op-Addition-com.aspose.drawing.PointF-com.aspose.drawing.SizeF-) |  |
| [op_Subtraction(PointF pt, SizeF sz)](#op-Subtraction-com.aspose.drawing.PointF-com.aspose.drawing.SizeF-) |  |
| [op_Equality(PointF left, PointF right)](#op-Equality-com.aspose.drawing.PointF-com.aspose.drawing.PointF-) | Συγκρίνει δύο δομές [PointF](../../com.aspose.drawing/pointf). |
| [op_Inequality(PointF left, PointF right)](#op-Inequality-com.aspose.drawing.PointF-com.aspose.drawing.PointF-) | Καθορίζει εάν οι συντεταγμένες των καθορισμένων σημείων δεν είναι ίσες. |
| [add(PointF orig, Size size)](#add-com.aspose.drawing.PointF-com.aspose.drawing.Size-) | Μεταφράζει ένα δεδομένο [PointF](../../com.aspose.drawing/pointf) κατά ένα καθορισμένο [SizeF](../../com.aspose.drawing/sizef). |
| [subtract(PointF pt, Size sz)](#subtract-com.aspose.drawing.PointF-com.aspose.drawing.Size-) |  |
| [add(PointF orig, SizeF sizeF)](#add-com.aspose.drawing.PointF-com.aspose.drawing.SizeF-) | Μεταφράζει ένα δεδομένο [PointF](../../com.aspose.drawing/pointf) κατά ένα καθορισμένο [SizeF](../../com.aspose.drawing/sizef). |
| [subtract(PointF pt, SizeF sz)](#subtract-com.aspose.drawing.PointF-com.aspose.drawing.SizeF-) |  |
| [isEquals(PointF obj1, PointF obj2)](#isEquals-com.aspose.drawing.PointF-com.aspose.drawing.PointF-) |  |
| [getEmpty()](#getEmpty--) |  |
| [isEmpty()](#isEmpty--) | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτό το [PointF](../../com.aspose.drawing/pointf) είναι κενό. |
| [getX()](#getX--) | Λαμβάνει τη συντεταγμένη x αυτού του PointF. |
| [setX(float value)](#setX-float-) | Ορίζει τη συντεταγμένη x αυτού του PointF. |
| [getY()](#getY--) | Λαμβάνει τη συντεταγμένη y αυτού του PointF. |
| [setY(float value)](#setY-float-) | Ορίζει τη συντεταγμένη y αυτού του PointF. |
| [equals(Object obj)](#equals-java.lang.Object-) | Καθορίζει εάν αυτό το [PointF](../../com.aspose.drawing/pointf) περιέχει τις ίδιες συντεταγμένες με το καθορισμένο Object. |
| [hashCode()](#hashCode--) | Επιστρέφει έναν κωδικό κατακερματισμού για αυτήν την instance. |
| [toString()](#toString--) |  |
| [equals(PointF other)](#equals-com.aspose.drawing.PointF-) | Δοκιμάζει εάν η άλλη δομή [PointF](../../com.aspose.drawing/pointf) έχει την ίδια θέση με αυτή τη δομή [PointF](../../com.aspose.drawing/pointf). |
| [CloneTo(PointF that)](#CloneTo-com.aspose.drawing.PointF-) |  |
| [Clone()](#Clone--) |  |
| [clone()](#clone--) |  |
### PointF() {#PointF--}
```
public PointF()
```


### PointF(float x, float y) {#PointF-float-float-}
```
public PointF(float x, float y)
```


Αρχικοποιεί ένα νέο στιγμιότυπο της δομής PointF με τις καθορισμένες συντεταγμένες.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | float | Η οριζόντια θέση του σημείου. |
| y | float | Η κάθετη θέση του σημείου. |

### op_Addition(PointF pt, Size sz) {#op-Addition-com.aspose.drawing.PointF-com.aspose.drawing.Size-}
```
public static PointF op_Addition(PointF pt, Size sz)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pt | [PointF](../../com.aspose.drawing/pointf) |  |
| sz | [Size](../../com.aspose.drawing/size) |  |

**Returns:**
[PointF](../../com.aspose.drawing/pointf)
### op_Subtraction(PointF pt, Size sz) {#op-Subtraction-com.aspose.drawing.PointF-com.aspose.drawing.Size-}
```
public static PointF op_Subtraction(PointF pt, Size sz)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pt | [PointF](../../com.aspose.drawing/pointf) |  |
| sz | [Size](../../com.aspose.drawing/size) |  |

**Returns:**
[PointF](../../com.aspose.drawing/pointf)
### op_Addition(PointF pt, SizeF sz) {#op-Addition-com.aspose.drawing.PointF-com.aspose.drawing.SizeF-}
```
public static PointF op_Addition(PointF pt, SizeF sz)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pt | [PointF](../../com.aspose.drawing/pointf) |  |
| sz | [SizeF](../../com.aspose.drawing/sizef) |  |

**Returns:**
[PointF](../../com.aspose.drawing/pointf)
### op_Subtraction(PointF pt, SizeF sz) {#op-Subtraction-com.aspose.drawing.PointF-com.aspose.drawing.SizeF-}
```
public static PointF op_Subtraction(PointF pt, SizeF sz)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pt | [PointF](../../com.aspose.drawing/pointf) |  |
| sz | [SizeF](../../com.aspose.drawing/sizef) |  |

**Returns:**
[PointF](../../com.aspose.drawing/pointf)
### op_Equality(PointF left, PointF right) {#op-Equality-com.aspose.drawing.PointF-com.aspose.drawing.PointF-}
```
public static boolean op_Equality(PointF left, PointF right)
```


Συγκρίνει δύο δομές [PointF](../../com.aspose.drawing/pointf). Το αποτέλεσμα καθορίζει εάν οι τιμές των ιδιοτήτων `PointF.X` και `PointF.Y` των δύο δομών [PointF](../../com.aspose.drawing/pointf) είναι ίσες.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| left | [PointF](../../com.aspose.drawing/pointf) | Πρώτο [PointF](../../com.aspose.drawing/pointf) για σύγκριση. |
| right | [PointF](../../com.aspose.drawing/pointf) | Δεύτερο [PointF](../../com.aspose.drawing/pointf) για σύγκριση. |

**Returns:**
boolean - true εάν οι τιμές `PointF.X` και `PointF.Y` των αριστερών και δεξιών δομών [PointF](../../com.aspose.drawing/pointf) είναι ίσες· διαφορετικά, false.
### op_Inequality(PointF left, PointF right) {#op-Inequality-com.aspose.drawing.PointF-com.aspose.drawing.PointF-}
```
public static boolean op_Inequality(PointF left, PointF right)
```


Καθορίζει εάν οι συντεταγμένες των καθορισμένων σημείων δεν είναι ίσες.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| left | [PointF](../../com.aspose.drawing/pointf) | Πρώτο [PointF](../../com.aspose.drawing/pointf) για σύγκριση. |
| right | [PointF](../../com.aspose.drawing/pointf) | Δεύτερο [PointF](../../com.aspose.drawing/pointf) για σύγκριση. |

**Returns:**
boolean - true για να υποδείξει ότι οι τιμές `PointF.X` και `PointF.Y` του `left` και του `right` δεν είναι ίσες· διαφορετικά, false.
### add(PointF orig, Size size) {#add-com.aspose.drawing.PointF-com.aspose.drawing.Size-}
```
public static PointF add(PointF orig, Size size)
```


Μεταφράζει ένα δεδομένο [PointF](../../com.aspose.drawing/pointf) κατά ένα καθορισμένο [SizeF](../../com.aspose.drawing/sizef).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| orig | [PointF](../../com.aspose.drawing/pointf) | Το [PointF](../../com.aspose.drawing/pointf) για μετάφραση. |
| size | [Size](../../com.aspose.drawing/size) | Το [Size](../../com.aspose.drawing/size) που καθορίζει τους αριθμούς που θα προστεθούν στις συντεταγμένες του `orig`. |

**Returns:**
[PointF](../../com.aspose.drawing/pointf) - The translated [PointF](../../com.aspose.drawing/pointf).
### subtract(PointF pt, Size sz) {#subtract-com.aspose.drawing.PointF-com.aspose.drawing.Size-}
```
public static PointF subtract(PointF pt, Size sz)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pt | [PointF](../../com.aspose.drawing/pointf) |  |
| sz | [Size](../../com.aspose.drawing/size) |  |

**Returns:**
[PointF](../../com.aspose.drawing/pointf)
### add(PointF orig, SizeF sizeF) {#add-com.aspose.drawing.PointF-com.aspose.drawing.SizeF-}
```
public static PointF add(PointF orig, SizeF sizeF)
```


Μεταφράζει ένα δεδομένο [PointF](../../com.aspose.drawing/pointf) κατά ένα καθορισμένο [SizeF](../../com.aspose.drawing/sizef).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| orig | [PointF](../../com.aspose.drawing/pointf) | Το [PointF](../../com.aspose.drawing/pointf) για μετάφραση. |
| sizeF | [SizeF](../../com.aspose.drawing/sizef) | Το [SizeF](../../com.aspose.drawing/sizef) που καθορίζει τους αριθμούς που θα προστεθούν στις συντεταγμένες του `orig`. |

**Returns:**
[PointF](../../com.aspose.drawing/pointf) - The translated [PointF](../../com.aspose.drawing/pointf).
### subtract(PointF pt, SizeF sz) {#subtract-com.aspose.drawing.PointF-com.aspose.drawing.SizeF-}
```
public static PointF subtract(PointF pt, SizeF sz)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pt | [PointF](../../com.aspose.drawing/pointf) |  |
| sz | [SizeF](../../com.aspose.drawing/sizef) |  |

**Returns:**
[PointF](../../com.aspose.drawing/pointf)
### isEquals(PointF obj1, PointF obj2) {#isEquals-com.aspose.drawing.PointF-com.aspose.drawing.PointF-}
```
public static boolean isEquals(PointF obj1, PointF obj2)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj1 | [PointF](../../com.aspose.drawing/pointf) |  |
| obj2 | [PointF](../../com.aspose.drawing/pointf) |  |

**Returns:**
boolean
### getEmpty() {#getEmpty--}
```
public static PointF getEmpty()
```




**Returns:**
[PointF](../../com.aspose.drawing/pointf)
### isEmpty() {#isEmpty--}
```
public final boolean isEmpty()
```


Λαμβάνει μια τιμή που υποδεικνύει εάν αυτό το [PointF](../../com.aspose.drawing/pointf) είναι κενό.

**Returns:**
boolean - μια τιμή που υποδεικνύει εάν αυτό το [PointF](../../com.aspose.drawing/pointf) είναι κενό.
### getX() {#getX--}
```
public final float getX()
```


Λαμβάνει τη συντεταγμένη x αυτού του PointF.

**Returns:**
float - η συντεταγμένη x αυτού του PointF.
### setX(float value) {#setX-float-}
```
public final void setX(float value)
```


Ορίζει τη συντεταγμένη x αυτού του PointF.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float | η συντεταγμένη x αυτού του PointF. |

### getY() {#getY--}
```
public final float getY()
```


Λαμβάνει τη συντεταγμένη y αυτού του PointF.

**Returns:**
float - η συντεταγμένη y αυτού του PointF.
### setY(float value) {#setY-float-}
```
public final void setY(float value)
```


Ορίζει τη συντεταγμένη y αυτού του PointF.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float | η συντεταγμένη y αυτού του PointF. |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Καθορίζει εάν αυτό το [PointF](../../com.aspose.drawing/pointf) περιέχει τις ίδιες συντεταγμένες με το καθορισμένο Object.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | java.lang.Object | Το Object για δοκιμή. |

**Returns:**
boolean - Αυτή η μέθοδος επιστρέφει true εάν το `obj` είναι ένα [PointF](../../com.aspose.drawing/pointf) και έχει τις ίδιες συντεταγμένες με αυτό το [Point](../../com.aspose.drawing/point).
### hashCode() {#hashCode--}
```
public int hashCode()
```


Επιστρέφει έναν κωδικό κατακερματισμού για αυτήν την instance.

**Returns:**
int - Ένας κωδικός κατακερματισμού για αυτήν την παρουσία, κατάλληλος για χρήση σε αλγόριθμους κατακερματισμού και δομές δεδομένων όπως ένας πίνακας κατακερματισμού.
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### equals(PointF other) {#equals-com.aspose.drawing.PointF-}
```
public final boolean equals(PointF other)
```


Δοκιμάζει εάν η άλλη δομή [PointF](../../com.aspose.drawing/pointf) έχει την ίδια θέση με αυτή τη δομή [PointF](../../com.aspose.drawing/pointf).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| other | [PointF](../../com.aspose.drawing/pointf) | Άλλο σημείο για δοκιμή |

**Returns:**
boolean - Αυτή η μέθοδος επιστρέφει `true` εάν η άλλη δομή [PointF](../../com.aspose.drawing/pointf) και οι ιδιότητές της X και Y είναι ίσες με τις αντίστοιχες ιδιότητες αυτής της δομής [PointF](../../com.aspose.drawing/pointf); διαφορετικά, `false`.
### CloneTo(PointF that) {#CloneTo-com.aspose.drawing.PointF-}
```
public void CloneTo(PointF that)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| that | [PointF](../../com.aspose.drawing/pointf) |  |

### Clone() {#Clone--}
```
public PointF Clone()
```




**Returns:**
[PointF](../../com.aspose.drawing/pointf)
### clone() {#clone--}
```
public Object clone()
```




**Returns:**
java.lang.Object
