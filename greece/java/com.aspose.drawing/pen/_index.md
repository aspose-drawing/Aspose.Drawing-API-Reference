---
title: Στυλό
second_title: Αναφορά API του Aspose.Drawing for Java
description: Defines an object used to draw lines and curves.
type: docs
weight: 34
url: /el/java/com.aspose.drawing/pen/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public class Pen implements System.IDisposable
```

Defines an object used to draw lines and curves.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [Pen(Color color)](#Pen-com.aspose.drawing.Color-) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [Pen](../../com.aspose.drawing/pen) με το καθορισμένο `Color`([.getColor](../../null/\#getColor)/[.setColor(Color)](../../null/\#setColor-Color-)). |
| [Pen(Brush brush, float width)](#Pen-com.aspose.drawing.Brush-float-) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης Pen με το καθορισμένο Brush και Width. |
| [Pen(Brush brush)](#Pen-com.aspose.drawing.Brush-) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [Pen](../../com.aspose.drawing/pen) με το καθορισμένο `Brush`([.getBrush](../../null/\#getBrush)/[.setBrush(Brush)](../../null/\#setBrush-Brush-)). |
| [Pen(Color color, float width)](#Pen-com.aspose.drawing.Color-float-) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης Pen με τις καθορισμένες ιδιότητες Color και Width. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getColor()](#getColor--) | Αποκτά ή ορίζει το χρώμα αυτού του [Pen](../../com.aspose.drawing/pen). |
| [setColor(Color value)](#setColor-com.aspose.drawing.Color-) | Αποκτά ή ορίζει το χρώμα αυτού του [Pen](../../com.aspose.drawing/pen). |
| [getBrush()](#getBrush--) | Αποκτά ή ορίζει το Brush που καθορίζει τα χαρακτηριστικά αυτού του [Pen](../../com.aspose.drawing/pen). |
| [setBrush(Brush value)](#setBrush-com.aspose.drawing.Brush-) | Αποκτά ή ορίζει το Brush που καθορίζει τα χαρακτηριστικά αυτού του [Pen](../../com.aspose.drawing/pen). |
| [getCompoundArray()](#getCompoundArray--) | Αποκτά ή ορίζει έναν πίνακα τιμών που καθορίζει ένα σύνθετο στυλό. |
| [setCompoundArray(float[] value)](#setCompoundArray-float---) | Αποκτά ή ορίζει έναν πίνακα τιμών που καθορίζει ένα σύνθετο στυλό. |
| [getWidth()](#getWidth--) | Αποκτά ή ορίζει το πλάτος αυτού του Pen, σε μονάδες του αντικειμένου Graphics που χρησιμοποιείται για το σχεδιασμό. |
| [setWidth(float value)](#setWidth-float-) | Αποκτά ή ορίζει το πλάτος αυτού του Pen, σε μονάδες του αντικειμένου Graphics που χρησιμοποιείται για το σχεδιασμό. |
| [getStartCap()](#getStartCap--) | Αποκτά ή ορίζει το στυλ άκρου που χρησιμοποιείται στην αρχή των γραμμών που σχεδιάζονται με αυτό το Pen. |
| [setStartCap(int value)](#setStartCap-int-) | Αποκτά ή ορίζει το στυλ άκρου που χρησιμοποιείται στην αρχή των γραμμών που σχεδιάζονται με αυτό το Pen. |
| [getEndCap()](#getEndCap--) | Αποκτά ή ορίζει το στυλ άκρου που χρησιμοποιείται στο τέλος των γραμμών που σχεδιάζονται με αυτό το Pen. |
| [setEndCap(int value)](#setEndCap-int-) | Αποκτά ή ορίζει το στυλ άκρου που χρησιμοποιείται στο τέλος των γραμμών που σχεδιάζονται με αυτό το Pen. |
| [getLineJoin()](#getLineJoin--) | Αποκτά ή ορίζει το στυλ σύνδεσης για τα άκρα δύο διαδοχικών γραμμών που σχεδιάζονται με αυτό το Pen. |
| [setLineJoin(int value)](#setLineJoin-int-) | Αποκτά ή ορίζει το στυλ σύνδεσης για τα άκρα δύο διαδοχικών γραμμών που σχεδιάζονται με αυτό το Pen. |
| [getMiterLimit()](#getMiterLimit--) | Αποκτά ή ορίζει το όριο του πάχους της σύνδεσης σε γωνία μύτης. |
| [setMiterLimit(float value)](#setMiterLimit-float-) | Αποκτά ή ορίζει το όριο του πάχους της σύνδεσης σε γωνία μύτης. |
| [getAlignment()](#getAlignment--) | Αποκτά ή ορίζει την ευθυγράμμιση για αυτό το [Pen](../../com.aspose.drawing/pen). |
| [setAlignment(int value)](#setAlignment-int-) | Αποκτά ή ορίζει την ευθυγράμμιση για αυτό το [Pen](../../com.aspose.drawing/pen). |
| [getTransform()](#getTransform--) | Αποκτά ή ορίζει ένα αντίγραφο του γεωμετρικού μετασχηματισμού για αυτό το [Pen](../../com.aspose.drawing/pen). |
| [setTransform(Matrix value)](#setTransform-com.aspose.drawing.drawing2d.Matrix-) | Αποκτά ή ορίζει ένα αντίγραφο του γεωμετρικού μετασχηματισμού για αυτό το [Pen](../../com.aspose.drawing/pen). |
| [getCustomStartCap()](#getCustomStartCap--) | Αποκτά ή ορίζει ένα προσαρμοσμένο άκρο για χρήση στην αρχή των γραμμών που σχεδιάζονται με αυτό το [Pen](../../com.aspose.drawing/pen). |
| [setCustomStartCap(CustomLineCap value)](#setCustomStartCap-com.aspose.drawing.drawing2d.CustomLineCap-) | Αποκτά ή ορίζει ένα προσαρμοσμένο άκρο για χρήση στην αρχή των γραμμών που σχεδιάζονται με αυτό το [Pen](../../com.aspose.drawing/pen). |
| [getCustomEndCap()](#getCustomEndCap--) | Αποκτά ή ορίζει ένα προσαρμοσμένο άκρο για χρήση στο τέλος των γραμμών που σχεδιάζονται με αυτό το [Pen](../../com.aspose.drawing/pen). |
| [setCustomEndCap(CustomLineCap value)](#setCustomEndCap-com.aspose.drawing.drawing2d.CustomLineCap-) | Αποκτά ή ορίζει ένα προσαρμοσμένο άκρο για χρήση στο τέλος των γραμμών που σχεδιάζονται με αυτό το [Pen](../../com.aspose.drawing/pen). |
| [getDashCap()](#getDashCap--) | Αποκτά ή ορίζει το στυλ άκρου που χρησιμοποιείται στο τέλος των παύλων που σχηματίζουν τις διακεκομμένες γραμμές που σχεδιάζονται με αυτό το [Pen](../../com.aspose.drawing/pen). |
| [setDashCap(int value)](#setDashCap-int-) | Αποκτά ή ορίζει το στυλ άκρου που χρησιμοποιείται στο τέλος των παύλων που σχηματίζουν τις διακεκομμένες γραμμές που σχεδιάζονται με αυτό το [Pen](../../com.aspose.drawing/pen). |
| [getDashOffset()](#getDashOffset--) | Αποκτά ή ορίζει την απόσταση από την αρχή μιας γραμμής μέχρι την αρχή του μοτίβου παύλας. |
| [setDashOffset(float value)](#setDashOffset-float-) | Αποκτά ή ορίζει την απόσταση από την αρχή μιας γραμμής μέχρι την αρχή του μοτίβου παύλας. |
| [getDashPattern()](#getDashPattern--) | Αποκτά ή ορίζει έναν πίνακα προσαρμοσμένων παύλων και κενών. |
| [setDashPattern(float[] value)](#setDashPattern-float---) | Αποκτά ή ορίζει έναν πίνακα προσαρμοσμένων παύλων και κενών. |
| [getDashStyle()](#getDashStyle--) | Αποκτά ή ορίζει το στυλ που χρησιμοποιείται για διακεκομμένες γραμμές που σχεδιάζονται με αυτό το [Pen](../../com.aspose.drawing/pen). |
| [setDashStyle(int value)](#setDashStyle-int-) | Αποκτά ή ορίζει το στυλ που χρησιμοποιείται για διακεκομμένες γραμμές που σχεδιάζονται με αυτό το [Pen](../../com.aspose.drawing/pen). |
| [getPenType()](#getPenType--) | Αποκτά το στυλ των γραμμών που σχεδιάζονται με αυτό το Pen. |
| [dispose()](#dispose--) | Απελευθερώνει όλους τους πόρους που χρησιμοποιούνται από αυτό το Pen. |
| [deepClone()](#deepClone--) | Δημιουργεί ένα ακριβές αντίγραφο αυτού του [Pen](../../com.aspose.drawing/pen). |
| [setLineCap(int startCap, int endCap, int dashCap)](#setLineCap-int-int-int-) | Ορίζει τις τιμές που καθορίζουν το στυλ του άκρου που χρησιμοποιείται για το τέλος των γραμμών που σχεδιάζονται από αυτό το [Pen](../../com.aspose.drawing/pen). |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | Κλιμακώνει τον τοπικό γεωμετρικό μετασχηματισμό με τους καθορισμένους παράγοντες. |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | Κλιμακώνει τον τοπικό γεωμετρικό μετασχηματισμό με τους καθορισμένους παράγοντες με τη συγκεκριμένη σειρά. |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | Μετατοπίζει τον τοπικό γεωμετρικό μετασχηματισμό κατά τις καθορισμένες διαστάσεις. |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | Μετατοπίζει τον τοπικό γεωμετρικό μετασχηματισμό κατά τις καθορισμένες διαστάσεις με τη συγκεκριμένη σειρά. |
| [rotateTransform(float angle)](#rotateTransform-float-) | Περιστρέφει τον τοπικό γεωμετρικό μετασχηματισμό κατά τη καθορισμένη γωνία. |
| [rotateTransform(float angle, int order)](#rotateTransform-float-int-) | Περιστρέφει τον τοπικό γεωμετρικό μετασχηματισμό κατά τη καθορισμένη γωνία με τη συγκεκριμένη σειρά. |
| [resetTransform()](#resetTransform--) | Επαναφέρει τον πίνακα γεωμετρικού μετασχηματισμού για αυτό το [Pen](../../com.aspose.drawing/pen) στην ταυτότητα. |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-) | Πολλαπλασιάζει τον πίνακα μετασχηματισμού για αυτό το [Pen](../../com.aspose.drawing/pen) με την καθορισμένη [Matrix](../../com.aspose.drawing.drawing2d/matrix). |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-int-) | Πολλαπλασιάζει τον πίνακα μετασχηματισμού για αυτό το [Pen](../../com.aspose.drawing/pen) με την καθορισμένη [Matrix](../../com.aspose.drawing.drawing2d/matrix) με τη συγκεκριμένη σειρά. |
### Pen(Color color) {#Pen-com.aspose.drawing.Color-}
```
public Pen(Color color)
```


Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [Pen](../../com.aspose.drawing/pen) με το καθορισμένο `Color`([.getColor](../../null/\#getColor)/[.setColor(Color)](../../null/\#setColor-Color-)).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| color | [Color](../../com.aspose.drawing/color) | Ένα `Color`([.getColor](../../null/\#getColor)/[.setColor(Color)](../../null/\#setColor-Color-)) που καθορίζει τις ιδιότητες γεμίσματος αυτού του [Pen](../../com.aspose.drawing/pen). |

### Pen(Brush brush, float width) {#Pen-com.aspose.drawing.Brush-float-}
```
public Pen(Brush brush, float width)
```


Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης Pen με το καθορισμένο Brush και Width.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.drawing/brush) | Ένα Brush που καθορίζει τα χαρακτηριστικά αυτού του Pen. |
| width | float | Το πλάτος του νέου Pen. |

### Pen(Brush brush) {#Pen-com.aspose.drawing.Brush-}
```
public Pen(Brush brush)
```


Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [Pen](../../com.aspose.drawing/pen) με το καθορισμένο `Brush`([.getBrush](../../null/\#getBrush)/[.setBrush(Brush)](../../null/\#setBrush-Brush-)).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.drawing/brush) | Ένα `Brush`([.getBrush](../../null/\#getBrush)/[.setBrush(Brush)](../../null/\#setBrush-Brush-)) που καθορίζει τις ιδιότητες γεμίσματος αυτού του [Pen](../../com.aspose.drawing/pen). |

### Pen(Color color, float width) {#Pen-com.aspose.drawing.Color-float-}
```
public Pen(Color color, float width)
```


Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης Pen με τις καθορισμένες ιδιότητες Color και Width.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| color | [Color](../../com.aspose.drawing/color) | Μια δομή Color που υποδεικνύει το χρώμα αυτού του Pen. |
| width | float | Μια τιμή που υποδεικνύει το πλάτος αυτού του Pen. |

### getColor() {#getColor--}
```
public final Color getColor()
```


Αποκτά ή ορίζει το χρώμα αυτού του [Pen](../../com.aspose.drawing/pen).

Τιμή: Μια δομή `Color`([.getColor](../../null/\#getColor)/[.setColor(Color)](../../null/\#setColor-Color-)) που αντιπροσωπεύει το χρώμα αυτού του [Pen](../../com.aspose.drawing/pen).

**Returns:**
[Color](../../com.aspose.drawing/color)
### setColor(Color value) {#setColor-com.aspose.drawing.Color-}
```
public final void setColor(Color value)
```


Αποκτά ή ορίζει το χρώμα αυτού του [Pen](../../com.aspose.drawing/pen).

Τιμή: Μια δομή `Color`([.getColor](../../null/\#getColor)/[.setColor(Color)](../../null/\#setColor-Color-)) που αντιπροσωπεύει το χρώμα αυτού του [Pen](../../com.aspose.drawing/pen).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Color](../../com.aspose.drawing/color) |  |

### getBrush() {#getBrush--}
```
public final Brush getBrush()
```


Αποκτά ή ορίζει το Brush που καθορίζει τα χαρακτηριστικά αυτού του [Pen](../../com.aspose.drawing/pen).

**Returns:**
[Brush](../../com.aspose.drawing/brush)
### setBrush(Brush value) {#setBrush-com.aspose.drawing.Brush-}
```
public final void setBrush(Brush value)
```


Αποκτά ή ορίζει το Brush που καθορίζει τα χαρακτηριστικά αυτού του [Pen](../../com.aspose.drawing/pen).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Brush](../../com.aspose.drawing/brush) |  |

### getCompoundArray() {#getCompoundArray--}
```
public final float[] getCompoundArray()
```


Ανακτά ή ορίζει έναν πίνακα τιμών που καθορίζει ένα σύνθετο στυλό. Ένα σύνθετο στυλό σχεδιάζει μια σύνθετη γραμμή που αποτελείται από παράλληλες γραμμές και κενά.

**Returns:**
float[] - Ένας πίνακας πραγματικών αριθμών που καθορίζει το σύνθετο σύνολο. Τα στοιχεία του πίνακα πρέπει να είναι σε αυξανόμενη σειρά, όχι μικρότερα από 0 και όχι μεγαλύτερα από 1.
### setCompoundArray(float[] value) {#setCompoundArray-float---}
```
public final void setCompoundArray(float[] value)
```


Ανακτά ή ορίζει έναν πίνακα τιμών που καθορίζει ένα σύνθετο στυλό. Ένα σύνθετο στυλό σχεδιάζει μια σύνθετη γραμμή που αποτελείται από παράλληλες γραμμές και κενά.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float[] |  |

### getWidth() {#getWidth--}
```
public final float getWidth()
```


Αποκτά ή ορίζει το πλάτος αυτού του Pen, σε μονάδες του αντικειμένου Graphics που χρησιμοποιείται για το σχεδιασμό.

**Returns:**
float
### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```


Αποκτά ή ορίζει το πλάτος αυτού του Pen, σε μονάδες του αντικειμένου Graphics που χρησιμοποιείται για το σχεδιασμό.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |

### getStartCap() {#getStartCap--}
```
public final int getStartCap()
```


Αποκτά ή ορίζει το στυλ άκρου που χρησιμοποιείται στην αρχή των γραμμών που σχεδιάζονται με αυτό το Pen.

**Returns:**
int
### setStartCap(int value) {#setStartCap-int-}
```
public final void setStartCap(int value)
```


Αποκτά ή ορίζει το στυλ άκρου που χρησιμοποιείται στην αρχή των γραμμών που σχεδιάζονται με αυτό το Pen.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getEndCap() {#getEndCap--}
```
public final int getEndCap()
```


Αποκτά ή ορίζει το στυλ άκρου που χρησιμοποιείται στο τέλος των γραμμών που σχεδιάζονται με αυτό το Pen.

**Returns:**
int
### setEndCap(int value) {#setEndCap-int-}
```
public final void setEndCap(int value)
```


Αποκτά ή ορίζει το στυλ άκρου που χρησιμοποιείται στο τέλος των γραμμών που σχεδιάζονται με αυτό το Pen.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getLineJoin() {#getLineJoin--}
```
public final int getLineJoin()
```


Αποκτά ή ορίζει το στυλ σύνδεσης για τα άκρα δύο διαδοχικών γραμμών που σχεδιάζονται με αυτό το Pen.

--------------------

Προς το παρόν η ένωση Miter λειτουργεί στην πραγματικότητα ως MiterClipped.

**Returns:**
int
### setLineJoin(int value) {#setLineJoin-int-}
```
public final void setLineJoin(int value)
```


Αποκτά ή ορίζει το στυλ σύνδεσης για τα άκρα δύο διαδοχικών γραμμών που σχεδιάζονται με αυτό το Pen.

--------------------

Προς το παρόν η ένωση Miter λειτουργεί στην πραγματικότητα ως MiterClipped.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getMiterLimit() {#getMiterLimit--}
```
public final float getMiterLimit()
```


Αποκτά ή ορίζει το όριο του πάχους της σύνδεσης σε γωνία μύτης.

**Returns:**
float
### setMiterLimit(float value) {#setMiterLimit-float-}
```
public final void setMiterLimit(float value)
```


Αποκτά ή ορίζει το όριο του πάχους της σύνδεσης σε γωνία μύτης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |

### getAlignment() {#getAlignment--}
```
public final int getAlignment()
```


Αποκτά ή ορίζει την ευθυγράμμιση για αυτό το [Pen](../../com.aspose.drawing/pen).

**Returns:**
int - Ένα [PenAlignment](../../com.aspose.drawing.drawing2d/penalignment) που αντιπροσωπεύει την ευθυγράμμιση για αυτό το [Pen](../../com.aspose.drawing/pen).
### setAlignment(int value) {#setAlignment-int-}
```
public final void setAlignment(int value)
```


Αποκτά ή ορίζει την ευθυγράμμιση για αυτό το [Pen](../../com.aspose.drawing/pen).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getTransform() {#getTransform--}
```
public final Matrix getTransform()
```


Αποκτά ή ορίζει ένα αντίγραφο του γεωμετρικού μετασχηματισμού για αυτό το [Pen](../../com.aspose.drawing/pen).

Τιμή: Ένα αντίγραφο του [Matrix](../../com.aspose.drawing.drawing2d/matrix) που αντιπροσωπεύει τον γεωμετρικό μετασχηματισμό για αυτό το [Pen](../../com.aspose.drawing/pen).

**Returns:**
[Matrix](../../com.aspose.drawing.drawing2d/matrix)
### setTransform(Matrix value) {#setTransform-com.aspose.drawing.drawing2d.Matrix-}
```
public final void setTransform(Matrix value)
```


Αποκτά ή ορίζει ένα αντίγραφο του γεωμετρικού μετασχηματισμού για αυτό το [Pen](../../com.aspose.drawing/pen).

Τιμή: Ένα αντίγραφο του [Matrix](../../com.aspose.drawing.drawing2d/matrix) που αντιπροσωπεύει τον γεωμετρικό μετασχηματισμό για αυτό το [Pen](../../com.aspose.drawing/pen).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.drawing.drawing2d/matrix) |  |

### getCustomStartCap() {#getCustomStartCap--}
```
public final CustomLineCap getCustomStartCap()
```


Αποκτά ή ορίζει ένα προσαρμοσμένο άκρο για χρήση στην αρχή των γραμμών που σχεδιάζονται με αυτό το [Pen](../../com.aspose.drawing/pen).

**Returns:**
[CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) - A [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) that represents the cap used at the beginning of lines drawn with this [Pen](../../com.aspose.drawing/pen).
### setCustomStartCap(CustomLineCap value) {#setCustomStartCap-com.aspose.drawing.drawing2d.CustomLineCap-}
```
public final void setCustomStartCap(CustomLineCap value)
```


Αποκτά ή ορίζει ένα προσαρμοσμένο άκρο για χρήση στην αρχή των γραμμών που σχεδιάζονται με αυτό το [Pen](../../com.aspose.drawing/pen).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) |  |

### getCustomEndCap() {#getCustomEndCap--}
```
public final CustomLineCap getCustomEndCap()
```


Αποκτά ή ορίζει ένα προσαρμοσμένο άκρο για χρήση στο τέλος των γραμμών που σχεδιάζονται με αυτό το [Pen](../../com.aspose.drawing/pen).

**Returns:**
[CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) - A [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) that represents the cap used at the end of lines drawn with this [Pen](../../com.aspose.drawing/pen).
### setCustomEndCap(CustomLineCap value) {#setCustomEndCap-com.aspose.drawing.drawing2d.CustomLineCap-}
```
public final void setCustomEndCap(CustomLineCap value)
```


Αποκτά ή ορίζει ένα προσαρμοσμένο άκρο για χρήση στο τέλος των γραμμών που σχεδιάζονται με αυτό το [Pen](../../com.aspose.drawing/pen).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) |  |

### getDashCap() {#getDashCap--}
```
public final int getDashCap()
```


Αποκτά ή ορίζει το στυλ άκρου που χρησιμοποιείται στο τέλος των παύλων που σχηματίζουν τις διακεκομμένες γραμμές που σχεδιάζονται με αυτό το [Pen](../../com.aspose.drawing/pen).

**Returns:**
int - Μία από τις τιμές `DashCap`([.getDashCap](../../null/\#getDashCap)/[.setDashCap(int)](../../null/\#setDashCap-int-)) που αντιπροσωπεύει το στυλ άκρου που χρησιμοποιείται στην αρχή και το τέλος των παύλων που αποτελούν τις διακεκομμένες γραμμές που σχεδιάζονται με αυτό το [Pen](../../com.aspose.drawing/pen).
### setDashCap(int value) {#setDashCap-int-}
```
public final void setDashCap(int value)
```


Αποκτά ή ορίζει το στυλ άκρου που χρησιμοποιείται στο τέλος των παύλων που σχηματίζουν τις διακεκομμένες γραμμές που σχεδιάζονται με αυτό το [Pen](../../com.aspose.drawing/pen).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getDashOffset() {#getDashOffset--}
```
public final float getDashOffset()
```


Αποκτά ή ορίζει την απόσταση από την αρχή μιας γραμμής μέχρι την αρχή του μοτίβου παύλας.

**Returns:**
float - Η απόσταση από την αρχή μιας γραμμής μέχρι την αρχή του μοτίβου παύλας.
### setDashOffset(float value) {#setDashOffset-float-}
```
public final void setDashOffset(float value)
```


Αποκτά ή ορίζει την απόσταση από την αρχή μιας γραμμής μέχρι την αρχή του μοτίβου παύλας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |

### getDashPattern() {#getDashPattern--}
```
public final float[] getDashPattern()
```


Αποκτά ή ορίζει έναν πίνακα προσαρμοσμένων παύλων και κενών.

**Returns:**
float[] - Ένας πίνακας πραγματικών αριθμών που καθορίζει τα μήκη των εναλλασσόμενων παύλων και κενών σε διακεκομμένες γραμμές.
### setDashPattern(float[] value) {#setDashPattern-float---}
```
public final void setDashPattern(float[] value)
```


Αποκτά ή ορίζει έναν πίνακα προσαρμοσμένων παύλων και κενών.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float[] |  |

### getDashStyle() {#getDashStyle--}
```
public final int getDashStyle()
```


Αποκτά ή ορίζει το στυλ που χρησιμοποιείται για διακεκομμένες γραμμές που σχεδιάζονται με αυτό το [Pen](../../com.aspose.drawing/pen).

**Returns:**
int - Ένα `DashStyle`([.getDashStyle](../../null/\#getDashStyle)/[.setDashStyle(int)](../../null/\#setDashStyle-int-)) που αντιπροσωπεύει το στυλ που χρησιμοποιείται για διακεκομμένες γραμμές που σχεδιάζονται με αυτό το [Pen](../../com.aspose.drawing/pen).
### setDashStyle(int value) {#setDashStyle-int-}
```
public final void setDashStyle(int value)
```


Αποκτά ή ορίζει το στυλ που χρησιμοποιείται για διακεκομμένες γραμμές που σχεδιάζονται με αυτό το [Pen](../../com.aspose.drawing/pen).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getPenType() {#getPenType--}
```
public final int getPenType()
```


Αποκτά το στυλ των γραμμών που σχεδιάζονται με αυτό το Pen.

Τιμή: Ένα `PenType`([.getPenType](../../null/\#getPenType)) απαρίθμηση που καθορίζει το στυλ των γραμμών που σχεδιάζονται με αυτό το [Pen](../../com.aspose.drawing/pen).

**Returns:**
int
### dispose() {#dispose--}
```
public final void dispose()
```


Απελευθερώνει όλους τους πόρους που χρησιμοποιούνται από αυτό το Pen.

--------------------

Αυτή η μέθοδος στην πραγματικότητα δεν κάνει τίποτα. Είναι μόνο για συμβατότητα με το API του System.Drawing.

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Δημιουργεί ένα ακριβές αντίγραφο αυτού του [Pen](../../com.aspose.drawing/pen).

**Returns:**
java.lang.Object - Ένα αντικείμενο που μπορεί να μετατραπεί σε ένα [Pen](../../com.aspose.drawing/pen).
### setLineCap(int startCap, int endCap, int dashCap) {#setLineCap-int-int-int-}
```
public final void setLineCap(int startCap, int endCap, int dashCap)
```


Ορίζει τις τιμές που καθορίζουν το στυλ του άκρου που χρησιμοποιείται για το τέλος των γραμμών που σχεδιάζονται από αυτό το [Pen](../../com.aspose.drawing/pen).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| startCap | int | Ένα [LineCap](../../com.aspose.drawing.drawing2d/linecap) που αντιπροσωπεύει το στυλ άκρου που χρησιμοποιείται στην αρχή των γραμμών που σχεδιάζονται με αυτό το [Pen](../../com.aspose.drawing/pen). |
| endCap | int | Ένα [LineCap](../../com.aspose.drawing.drawing2d/linecap) που αντιπροσωπεύει το στυλ άκρου που χρησιμοποιείται στο τέλος των γραμμών που σχεδιάζονται με αυτό το [Pen](../../com.aspose.drawing/pen). |
| dashCap | int | Ένα [LineCap](../../com.aspose.drawing.drawing2d/linecap) που αντιπροσωπεύει το στυλ άκρου που χρησιμοποιείται στην αρχή ή στο τέλος των διακεκομμένων γραμμών που σχεδιάζονται με αυτό το [Pen](../../com.aspose.drawing/pen). |

### scaleTransform(float sx, float sy) {#scaleTransform-float-float-}
```
public final void scaleTransform(float sx, float sy)
```


Κλιμακώνει τη τοπική γεωμετρική μετασχηματισμό με τους καθορισμένους παράγοντες. Αυτή η μέθοδος προσθέτει το πλέγμα κλιμάκωσης στην αρχή του μετασχηματισμού.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sx | float | Ο παράγοντας με τον οποίο θα κλιμακώσετε τον μετασχηματισμό στην κατεύθυνση του άξονα x. |
| sy | float | Ο παράγοντας με τον οποίο θα κλιμακώσετε τον μετασχηματισμό στην κατεύθυνση του άξονα y. |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public final void scaleTransform(float sx, float sy, int order)
```


Κλιμακώνει τον τοπικό γεωμετρικό μετασχηματισμό με τους καθορισμένους παράγοντες με τη συγκεκριμένη σειρά.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sx | float | Ο παράγοντας με τον οποίο θα κλιμακώσετε τον μετασχηματισμό στην κατεύθυνση του άξονα x. |
| sy | float | Ο παράγοντας με τον οποίο θα κλιμακώσετε τον μετασχηματισμό στην κατεύθυνση του άξονα y. |
| order | int | Ένα [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder) που καθορίζει αν θα προσαρτηθεί ή θα προστεθεί το πλέγμα κλιμάκωσης. |

### translateTransform(float dx, float dy) {#translateTransform-float-float-}
```
public final void translateTransform(float dx, float dy)
```


Μετακινεί τη τοπική γεωμετρική μετασχηματισμό με τις καθορισμένες διαστάσεις. Αυτή η μέθοδος προσθέτει τη μετάφραση στην αρχή του μετασχηματισμού.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| dx | float | Η τιμή της μετάφρασης στον άξονα x. |
| dy | float | Η τιμή της μετάφρασης στον άξονα y. |

### translateTransform(float dx, float dy, int order) {#translateTransform-float-float-int-}
```
public final void translateTransform(float dx, float dy, int order)
```


Μετατοπίζει τον τοπικό γεωμετρικό μετασχηματισμό κατά τις καθορισμένες διαστάσεις με τη συγκεκριμένη σειρά.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| dx | float | Η τιμή της μετάφρασης στον άξονα x. |
| dy | float | Η τιμή της μετάφρασης στον άξονα y. |
| order | int | Η σειρά (prepend ή append) με την οποία εφαρμόζεται η μετάφραση. |

### rotateTransform(float angle) {#rotateTransform-float-}
```
public final void rotateTransform(float angle)
```


Περιστρέφει τη τοπική γεωμετρική μετασχηματισμό με την καθορισμένη γωνία. Αυτή η μέθοδος προσθέτει την περιστροφή στην αρχή του μετασχηματισμού.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| γωνία | float | Η γωνία της περιστροφής. |

### rotateTransform(float angle, int order) {#rotateTransform-float-int-}
```
public final void rotateTransform(float angle, int order)
```


Περιστρέφει τον τοπικό γεωμετρικό μετασχηματισμό κατά τη καθορισμένη γωνία με τη συγκεκριμένη σειρά.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| γωνία | float | Η γωνία της περιστροφής. |
| order | int | Ένα [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder) που καθορίζει αν θα προσαρτηθεί ή θα προστεθεί το πλέγμα περιστροφής. |

### resetTransform() {#resetTransform--}
```
public final void resetTransform()
```


Επαναφέρει τον πίνακα γεωμετρικού μετασχηματισμού για αυτό το [Pen](../../com.aspose.drawing/pen) στην ταυτότητα.

### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-}
```
public final void multiplyTransform(Matrix matrix)
```


Πολλαπλασιάζει τον πίνακα μετασχηματισμού για αυτό το [Pen](../../com.aspose.drawing/pen) με την καθορισμένη [Matrix](../../com.aspose.drawing.drawing2d/matrix).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | Το αντικείμενο [Matrix](../../com.aspose.drawing.drawing2d/matrix) με το οποίο θα πολλαπλασιάσετε το πλέγμα μετασχηματισμού. |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-int-}
```
public final void multiplyTransform(Matrix matrix, int order)
```


Πολλαπλασιάζει τον πίνακα μετασχηματισμού για αυτό το [Pen](../../com.aspose.drawing/pen) με την καθορισμένη [Matrix](../../com.aspose.drawing.drawing2d/matrix) με τη συγκεκριμένη σειρά.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | Το java.awt.geom.AffineTransform με το οποίο θα πολλαπλασιάσετε το πλέγμα μετασχηματισμού. |
| order | int | Η σειρά με την οποία θα εκτελεστεί η λειτουργία πολλαπλασιασμού. |

