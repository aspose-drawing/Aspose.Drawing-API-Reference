---
title: ColorMatrix
second_title: Αναφορά API του Aspose.Drawing for Java
description: Ορίζει έναν πίνακα 5 x 5 που περιέχει τις συντεταγμένες για το χώρο RGBA.
type: docs
weight: 14
url: /el/java/com.aspose.drawing.imaging/colormatrix/
---
**Inheritance:**
java.lang.Object
```
public final class ColorMatrix
```

Ορίζει έναν πίνακα 5 x 5 που περιέχει τις συντεταγμένες για το χώρο RGBA. Πολλές μέθοδοι της κλάσης [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes) προσαρμόζουν τα χρώματα της εικόνας χρησιμοποιώντας έναν πίνακα χρωμάτων. Αυτή η κλάση δεν μπορεί να κληρονομηθεί.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [ColorMatrix()](#ColorMatrix--) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [ColorMatrix(float[][] newColorMatrix)](#ColorMatrix-float-----) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) χρησιμοποιώντας τα στοιχεία του καθορισμένου πίνακα `newColorMatrix`. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getMatrix00()](#getMatrix00--) | Λαμβάνει το στοιχείο στη γραμμή 0 (μηδέν) και στήλη 0 αυτού του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix00(float value)](#setMatrix00-float-) | Ορίζει το στοιχείο στη γραμμή 0 (μηδέν) και στήλη 0 αυτού του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix01()](#getMatrix01--) | Λαμβάνει το στοιχείο στη γραμμή 0 (μηδέν) και πρώτη στήλη αυτού του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix01(float value)](#setMatrix01-float-) | Ορίζει το στοιχείο στη γραμμή 0 (μηδέν) και πρώτη στήλη αυτού του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix02()](#getMatrix02--) | Λαμβάνει το στοιχείο στη γραμμή 0 (μηδέν) και δεύτερη στήλη αυτού του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix02(float value)](#setMatrix02-float-) | Ορίζει το στοιχείο στη γραμμή 0 (μηδέν) και δεύτερη στήλη αυτού του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix03()](#getMatrix03--) | Λαμβάνει το στοιχείο στη γραμμή 0 (μηδέν) και τρίτη στήλη αυτού του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix03(float value)](#setMatrix03-float-) | Ορίζει το στοιχείο στη γραμμή 0 (μηδέν) και στην τρίτη στήλη αυτού του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix04()](#getMatrix04--) | Λαμβάνει το στοιχείο στη γραμμή 0 (μηδέν) και στην τέταρτη στήλη αυτού του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix04(float value)](#setMatrix04-float-) | Ορίζει το στοιχείο στη γραμμή 0 (μηδέν) και στην τέταρτη στήλη αυτού του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix10()](#getMatrix10--) | Λαμβάνει το στοιχείο στην πρώτη γραμμή και στη στήλη 0 (μηδέν) αυτού του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix10(float value)](#setMatrix10-float-) | Ορίζει το στοιχείο στην πρώτη γραμμή και στη στήλη 0 (μηδέν) αυτού του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix11()](#getMatrix11--) | Λαμβάνει το στοιχείο στην πρώτη γραμμή και στην πρώτη στήλη αυτού του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix11(float value)](#setMatrix11-float-) | Ορίζει το στοιχείο στην πρώτη γραμμή και στην πρώτη στήλη αυτού του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix12()](#getMatrix12--) | Λαμβάνει το στοιχείο στην πρώτη γραμμή και στη δεύτερη στήλη αυτού του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix12(float value)](#setMatrix12-float-) | Ορίζει το στοιχείο στην πρώτη γραμμή και στη δεύτερη στήλη αυτού του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix13()](#getMatrix13--) | Λαμβάνει το στοιχείο στην πρώτη γραμμή και στην τρίτη στήλη αυτού του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix13(float value)](#setMatrix13-float-) | Ορίζει το στοιχείο στην πρώτη γραμμή και στην τρίτη στήλη αυτού του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix14()](#getMatrix14--) | Λαμβάνει το στοιχείο στην πρώτη γραμμή και στην τέταρτη στήλη αυτού του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix14(float value)](#setMatrix14-float-) | Ορίζει το στοιχείο στην πρώτη γραμμή και στην τέταρτη στήλη αυτού του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix20()](#getMatrix20--) | Λαμβάνει το στοιχείο στη δεύτερη γραμμή και στη στήλη 0 (μηδέν) αυτού του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix20(float value)](#setMatrix20-float-) | Ορίζει το στοιχείο στη δεύτερη γραμμή και στη στήλη 0 (μηδέν) αυτού του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix21()](#getMatrix21--) | Λαμβάνει το στοιχείο στη δεύτερη γραμμή και στην πρώτη στήλη αυτού του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix21(float value)](#setMatrix21-float-) | Ορίζει το στοιχείο στη δεύτερη γραμμή και στην πρώτη στήλη αυτού του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix22()](#getMatrix22--) | Λαμβάνει το στοιχείο στη δεύτερη γραμμή και στη δεύτερη στήλη αυτού του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix22(float value)](#setMatrix22-float-) | Ορίζει το στοιχείο στη δεύτερη γραμμή και στη δεύτερη στήλη αυτού του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix23()](#getMatrix23--) | Λαμβάνει το στοιχείο στη δεύτερη γραμμή και στην τρίτη στήλη αυτού του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix23(float value)](#setMatrix23-float-) | Ορίζει το στοιχείο στη δεύτερη γραμμή και στην τρίτη στήλη αυτού του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix24()](#getMatrix24--) | Λαμβάνει το στοιχείο στη δεύτερη γραμμή και στην τέταρτη στήλη αυτού του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix24(float value)](#setMatrix24-float-) | Ορίζει το στοιχείο στη δεύτερη γραμμή και στην τέταρτη στήλη αυτού του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix30()](#getMatrix30--) | Λαμβάνει το στοιχείο στην τρίτη γραμμή και στη στήλη 0 (μηδέν) αυτού του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix30(float value)](#setMatrix30-float-) | Ορίζει το στοιχείο στην τρίτη γραμμή και στη στήλη 0 (μηδέν) αυτού του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix31()](#getMatrix31--) | Λαμβάνει το στοιχείο στην τρίτη γραμμή και την πρώτη στήλη αυτού του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix31(float value)](#setMatrix31-float-) | Ορίζει το στοιχείο στην τρίτη γραμμή και την πρώτη στήλη αυτού του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix32()](#getMatrix32--) | Λαμβάνει το στοιχείο στην τρίτη γραμμή και τη δεύτερη στήλη αυτού του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix32(float value)](#setMatrix32-float-) | Ορίζει το στοιχείο στην τρίτη γραμμή και τη δεύτερη στήλη αυτού του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix33()](#getMatrix33--) | Λαμβάνει το στοιχείο στην τρίτη γραμμή και την τρίτη στήλη αυτού του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix33(float value)](#setMatrix33-float-) | Ορίζει το στοιχείο στην τρίτη γραμμή και την τρίτη στήλη αυτού του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix34()](#getMatrix34--) | Λαμβάνει το στοιχείο στην τρίτη γραμμή και την τέταρτη στήλη αυτού του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix34(float value)](#setMatrix34-float-) | Ορίζει το στοιχείο στην τρίτη γραμμή και την τέταρτη στήλη αυτού του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix40()](#getMatrix40--) | Λαμβάνει το στοιχείο στην τέταρτη γραμμή και τη στήλη 0 (μηδέν) αυτού του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix40(float value)](#setMatrix40-float-) | Ορίζει το στοιχείο στην τέταρτη γραμμή και τη στήλη 0 (μηδέν) αυτού του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix41()](#getMatrix41--) | Λαμβάνει το στοιχείο στην τέταρτη γραμμή και την πρώτη στήλη αυτού του `.ColorMatrix`. |
| [setMatrix41(float value)](#setMatrix41-float-) | Ορίζει το στοιχείο στην τέταρτη γραμμή και την πρώτη στήλη αυτού του `.ColorMatrix`. |
| [getMatrix42()](#getMatrix42--) | Λαμβάνει το στοιχείο στην τέταρτη γραμμή και τη δεύτερη στήλη αυτού του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix42(float value)](#setMatrix42-float-) | Ορίζει το στοιχείο στην τέταρτη γραμμή και τη δεύτερη στήλη αυτού του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix43()](#getMatrix43--) | Λαμβάνει το στοιχείο στην τέταρτη γραμμή και την τρίτη στήλη αυτού του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix43(float value)](#setMatrix43-float-) | Ορίζει το στοιχείο στην τέταρτη γραμμή και την τρίτη στήλη αυτού του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [getMatrix44()](#getMatrix44--) | Λαμβάνει το στοιχείο στην τέταρτη γραμμή και την τέταρτη στήλη αυτού του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [setMatrix44(float value)](#setMatrix44-float-) | Ορίζει το στοιχείο στην τέταρτη γραμμή και την τέταρτη στήλη αυτού του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [get_Item(int row, int column)](#get-Item-int-int-) | Λαμβάνει το στοιχείο στη συγκεκριμένη γραμμή και στήλη στο [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
| [set_Item(int row, int column, float value)](#set-Item-int-int-float-) | Ορίζει το στοιχείο στη συγκεκριμένη γραμμή και στήλη στο [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |
### ColorMatrix() {#ColorMatrix--}
```
public ColorMatrix()
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

### ColorMatrix(float[][] newColorMatrix) {#ColorMatrix-float-----}
```
public ColorMatrix(float[][] newColorMatrix)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) χρησιμοποιώντας τα στοιχεία του καθορισμένου πίνακα `newColorMatrix`.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| newColorMatrix | float[][] | Οι τιμές των στοιχείων για το νέο [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix00() {#getMatrix00--}
```
public float getMatrix00()
```


Λαμβάνει το στοιχείο στη γραμμή 0 (μηδέν) και στήλη 0 αυτού του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - το στοιχείο στη γραμμή 0 (μηδέν) και στήλη 0 αυτού του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix00(float value) {#setMatrix00-float-}
```
public void setMatrix00(float value)
```


Ορίζει το στοιχείο στη γραμμή 0 (μηδέν) και στήλη 0 αυτού του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float | το στοιχείο στη γραμμή 0 (μηδέν) και στήλη 0 αυτού του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix01() {#getMatrix01--}
```
public float getMatrix01()
```


Λαμβάνει το στοιχείο στη γραμμή 0 (μηδέν) και πρώτη στήλη αυτού του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - το στοιχείο στη γραμμή 0 (μηδέν) και πρώτη στήλη αυτού του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix01(float value) {#setMatrix01-float-}
```
public void setMatrix01(float value)
```


Ορίζει το στοιχείο στη γραμμή 0 (μηδέν) και πρώτη στήλη αυτού του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float | το στοιχείο στη γραμμή 0 (μηδέν) και πρώτη στήλη αυτού του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix02() {#getMatrix02--}
```
public float getMatrix02()
```


Λαμβάνει το στοιχείο στη γραμμή 0 (μηδέν) και δεύτερη στήλη αυτού του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - το στοιχείο στη 0 (μηδέν) γραμμή και δεύτερη στήλη του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix02(float value) {#setMatrix02-float-}
```
public void setMatrix02(float value)
```


Ορίζει το στοιχείο στη γραμμή 0 (μηδέν) και δεύτερη στήλη αυτού του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float | το στοιχείο στη 0 (μηδέν) γραμμή και δεύτερη στήλη του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix03() {#getMatrix03--}
```
public float getMatrix03()
```


Λαμβάνει το στοιχείο στη γραμμή 0 (μηδέν) και τρίτη στήλη αυτού του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - το στοιχείο στη 0 (μηδέν) γραμμή και τρίτη στήλη του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix03(float value) {#setMatrix03-float-}
```
public void setMatrix03(float value)
```


Ορίζει το στοιχείο στη γραμμή 0 (μηδέν) και στην τρίτη στήλη αυτού του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float | το στοιχείο στη 0 (μηδέν) γραμμή και τρίτη στήλη του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix04() {#getMatrix04--}
```
public float getMatrix04()
```


Λαμβάνει το στοιχείο στη γραμμή 0 (μηδέν) και στην τέταρτη στήλη αυτού του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - το στοιχείο στη 0 (μηδέν) γραμμή και τέταρτη στήλη του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix04(float value) {#setMatrix04-float-}
```
public void setMatrix04(float value)
```


Ορίζει το στοιχείο στη γραμμή 0 (μηδέν) και στην τέταρτη στήλη αυτού του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float | το στοιχείο στη 0 (μηδέν) γραμμή και τέταρτη στήλη του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix10() {#getMatrix10--}
```
public float getMatrix10()
```


Λαμβάνει το στοιχείο στην πρώτη γραμμή και στη στήλη 0 (μηδέν) αυτού του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - το στοιχείο στην πρώτη γραμμή και 0 (μηδέν) στήλη του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix10(float value) {#setMatrix10-float-}
```
public void setMatrix10(float value)
```


Ορίζει το στοιχείο στην πρώτη γραμμή και στη στήλη 0 (μηδέν) αυτού του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float | το στοιχείο στην πρώτη γραμμή και 0 (μηδέν) στήλη του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix11() {#getMatrix11--}
```
public float getMatrix11()
```


Λαμβάνει το στοιχείο στην πρώτη γραμμή και στην πρώτη στήλη αυτού του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - το στοιχείο στην πρώτη γραμμή και πρώτη στήλη του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix11(float value) {#setMatrix11-float-}
```
public void setMatrix11(float value)
```


Ορίζει το στοιχείο στην πρώτη γραμμή και στην πρώτη στήλη αυτού του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float | το στοιχείο στην πρώτη γραμμή και πρώτη στήλη του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix12() {#getMatrix12--}
```
public float getMatrix12()
```


Λαμβάνει το στοιχείο στην πρώτη γραμμή και στη δεύτερη στήλη αυτού του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - το στοιχείο στην πρώτη γραμμή και δεύτερη στήλη του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix12(float value) {#setMatrix12-float-}
```
public void setMatrix12(float value)
```


Ορίζει το στοιχείο στην πρώτη γραμμή και στη δεύτερη στήλη αυτού του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float | το στοιχείο στην πρώτη γραμμή και δεύτερη στήλη του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix13() {#getMatrix13--}
```
public float getMatrix13()
```


Λαμβάνει το στοιχείο στην πρώτη γραμμή και στην τρίτη στήλη αυτού του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - το στοιχείο στην πρώτη γραμμή και τρίτη στήλη του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix13(float value) {#setMatrix13-float-}
```
public void setMatrix13(float value)
```


Ορίζει το στοιχείο στην πρώτη γραμμή και στην τρίτη στήλη αυτού του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float | το στοιχείο στην πρώτη γραμμή και τρίτη στήλη του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix14() {#getMatrix14--}
```
public float getMatrix14()
```


Λαμβάνει το στοιχείο στην πρώτη γραμμή και στην τέταρτη στήλη αυτού του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - το στοιχείο στην πρώτη γραμμή και τέταρτη στήλη του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix14(float value) {#setMatrix14-float-}
```
public void setMatrix14(float value)
```


Ορίζει το στοιχείο στην πρώτη γραμμή και στην τέταρτη στήλη αυτού του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float | το στοιχείο στην πρώτη γραμμή και τέταρτη στήλη του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix20() {#getMatrix20--}
```
public float getMatrix20()
```


Λαμβάνει το στοιχείο στη δεύτερη γραμμή και στη στήλη 0 (μηδέν) αυτού του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - το στοιχείο στη δεύτερη γραμμή και 0 (μηδέν) στήλη του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix20(float value) {#setMatrix20-float-}
```
public void setMatrix20(float value)
```


Ορίζει το στοιχείο στη δεύτερη γραμμή και στη στήλη 0 (μηδέν) αυτού του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float | το στοιχείο στη δεύτερη γραμμή και 0 (μηδέν) στήλη του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix21() {#getMatrix21--}
```
public float getMatrix21()
```


Λαμβάνει το στοιχείο στη δεύτερη γραμμή και στην πρώτη στήλη αυτού του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - το στοιχείο στη δεύτερη γραμμή και πρώτη στήλη του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix21(float value) {#setMatrix21-float-}
```
public void setMatrix21(float value)
```


Ορίζει το στοιχείο στη δεύτερη γραμμή και στην πρώτη στήλη αυτού του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float | το στοιχείο στη δεύτερη γραμμή και πρώτη στήλη του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix22() {#getMatrix22--}
```
public float getMatrix22()
```


Λαμβάνει το στοιχείο στη δεύτερη γραμμή και στη δεύτερη στήλη αυτού του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - το στοιχείο στη δεύτερη γραμμή και δεύτερη στήλη του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix22(float value) {#setMatrix22-float-}
```
public void setMatrix22(float value)
```


Ορίζει το στοιχείο στη δεύτερη γραμμή και στη δεύτερη στήλη αυτού του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float | το στοιχείο στη δεύτερη γραμμή και δεύτερη στήλη του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix23() {#getMatrix23--}
```
public float getMatrix23()
```


Λαμβάνει το στοιχείο στη δεύτερη γραμμή και στην τρίτη στήλη αυτού του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - το στοιχείο στη δεύτερη γραμμή και τρίτη στήλη του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix23(float value) {#setMatrix23-float-}
```
public void setMatrix23(float value)
```


Ορίζει το στοιχείο στη δεύτερη γραμμή και στην τρίτη στήλη αυτού του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float | το στοιχείο στη δεύτερη γραμμή και τρίτη στήλη του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix24() {#getMatrix24--}
```
public float getMatrix24()
```


Λαμβάνει το στοιχείο στη δεύτερη γραμμή και στην τέταρτη στήλη αυτού του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - το στοιχείο στη δεύτερη γραμμή και τέταρτη στήλη του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix24(float value) {#setMatrix24-float-}
```
public void setMatrix24(float value)
```


Ορίζει το στοιχείο στη δεύτερη γραμμή και στην τέταρτη στήλη αυτού του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float | το στοιχείο στη δεύτερη γραμμή και τέταρτη στήλη του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix30() {#getMatrix30--}
```
public float getMatrix30()
```


Λαμβάνει το στοιχείο στην τρίτη γραμμή και στη στήλη 0 (μηδέν) αυτού του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - το στοιχείο στην τρίτη γραμμή και 0 (μηδέν) στήλη του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix30(float value) {#setMatrix30-float-}
```
public void setMatrix30(float value)
```


Ορίζει το στοιχείο στην τρίτη γραμμή και στη στήλη 0 (μηδέν) αυτού του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float | το στοιχείο στην τρίτη γραμμή και 0 (μηδέν) στήλη του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix31() {#getMatrix31--}
```
public float getMatrix31()
```


Λαμβάνει το στοιχείο στην τρίτη γραμμή και την πρώτη στήλη αυτού του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - το στοιχείο στην τρίτη γραμμή και πρώτη στήλη του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix31(float value) {#setMatrix31-float-}
```
public void setMatrix31(float value)
```


Ορίζει το στοιχείο στην τρίτη γραμμή και την πρώτη στήλη αυτού του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float | το στοιχείο στην τρίτη γραμμή και πρώτη στήλη του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix32() {#getMatrix32--}
```
public float getMatrix32()
```


Λαμβάνει το στοιχείο στην τρίτη γραμμή και τη δεύτερη στήλη αυτού του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - το στοιχείο στην τρίτη γραμμή και δεύτερη στήλη του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix32(float value) {#setMatrix32-float-}
```
public void setMatrix32(float value)
```


Ορίζει το στοιχείο στην τρίτη γραμμή και τη δεύτερη στήλη αυτού του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float | το στοιχείο στην τρίτη γραμμή και δεύτερη στήλη του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix33() {#getMatrix33--}
```
public float getMatrix33()
```


Λαμβάνει το στοιχείο στην τρίτη γραμμή και την τρίτη στήλη αυτού του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - το στοιχείο στην τρίτη γραμμή και τρίτη στήλη του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix33(float value) {#setMatrix33-float-}
```
public void setMatrix33(float value)
```


Ορίζει το στοιχείο στην τρίτη γραμμή και την τρίτη στήλη αυτού του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float | το στοιχείο στην τρίτη γραμμή και τρίτη στήλη του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix34() {#getMatrix34--}
```
public float getMatrix34()
```


Λαμβάνει το στοιχείο στην τρίτη γραμμή και την τέταρτη στήλη αυτού του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - το στοιχείο στην τρίτη γραμμή και τέταρτη στήλη του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix34(float value) {#setMatrix34-float-}
```
public void setMatrix34(float value)
```


Ορίζει το στοιχείο στην τρίτη γραμμή και την τέταρτη στήλη αυτού του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float | το στοιχείο στην τρίτη γραμμή και τέταρτη στήλη του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix40() {#getMatrix40--}
```
public float getMatrix40()
```


Λαμβάνει το στοιχείο στην τέταρτη γραμμή και τη στήλη 0 (μηδέν) αυτού του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - το στοιχείο στην τέταρτη γραμμή και 0 (μηδέν) στήλη του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix40(float value) {#setMatrix40-float-}
```
public void setMatrix40(float value)
```


Ορίζει το στοιχείο στην τέταρτη γραμμή και τη στήλη 0 (μηδέν) αυτού του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float | το στοιχείο στην τέταρτη γραμμή και 0 (μηδέν) στήλη του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix41() {#getMatrix41--}
```
public float getMatrix41()
```


Λαμβάνει το στοιχείο στην τέταρτη γραμμή και την πρώτη στήλη αυτού του `.ColorMatrix`.

**Returns:**
float - το στοιχείο στην τέταρτη γραμμή και πρώτη στήλη του `.ColorMatrix`.
### setMatrix41(float value) {#setMatrix41-float-}
```
public void setMatrix41(float value)
```


Ορίζει το στοιχείο στην τέταρτη γραμμή και την πρώτη στήλη αυτού του `.ColorMatrix`.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float | το στοιχείο στην τέταρτη γραμμή και πρώτη στήλη του `.ColorMatrix`. |

### getMatrix42() {#getMatrix42--}
```
public float getMatrix42()
```


Λαμβάνει το στοιχείο στην τέταρτη γραμμή και τη δεύτερη στήλη αυτού του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - το στοιχείο στην τέταρτη γραμμή και δεύτερη στήλη του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix42(float value) {#setMatrix42-float-}
```
public void setMatrix42(float value)
```


Ορίζει το στοιχείο στην τέταρτη γραμμή και τη δεύτερη στήλη αυτού του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float | το στοιχείο στην τέταρτη γραμμή και δεύτερη στήλη του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix43() {#getMatrix43--}
```
public float getMatrix43()
```


Λαμβάνει το στοιχείο στην τέταρτη γραμμή και την τρίτη στήλη αυτού του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - το στοιχείο στην τέταρτη γραμμή και τρίτη στήλη του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix43(float value) {#setMatrix43-float-}
```
public void setMatrix43(float value)
```


Ορίζει το στοιχείο στην τέταρτη γραμμή και την τρίτη στήλη αυτού του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float | το στοιχείο στην τέταρτη γραμμή και τρίτη στήλη του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### getMatrix44() {#getMatrix44--}
```
public float getMatrix44()
```


Λαμβάνει το στοιχείο στην τέταρτη γραμμή και την τέταρτη στήλη αυτού του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Returns:**
float - το στοιχείο στην τέταρτη γραμμή και τέταρτη στήλη του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).
### setMatrix44(float value) {#setMatrix44-float-}
```
public void setMatrix44(float value)
```


Ορίζει το στοιχείο στην τέταρτη γραμμή και την τέταρτη στήλη αυτού του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float | το στοιχείο στην τέταρτη γραμμή και τέταρτη στήλη του [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

### get_Item(int row, int column) {#get-Item-int-int-}
```
public float get_Item(int row, int column)
```


Λαμβάνει το στοιχείο στη συγκεκριμένη γραμμή και στήλη στο [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| γραμμή | int | Η γραμμή του στοιχείου. |
| στήλη | int | Η στήλη του στοιχείου. |

**Returns:**
float - Το στοιχείο στη συγκεκριμένη γραμμή και στήλη.
### set_Item(int row, int column, float value) {#set-Item-int-int-float-}
```
public void set_Item(int row, int column, float value)
```


Ορίζει το στοιχείο στη συγκεκριμένη γραμμή και στήλη στο [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| γραμμή | int | Η γραμμή του στοιχείου. |
| στήλη | int | Η στήλη του στοιχείου. |
| value | float | το στοιχείο στη συγκεκριμένη γραμμή και στήλη στο [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix). |

