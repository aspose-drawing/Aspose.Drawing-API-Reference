---
title: TextureBrush
second_title: Αναφορά API του Aspose.Drawing for Java
description: Each property of the TextureBrush class is a Brush object that uses an image to fill the interior of a shape.
type: docs
weight: 53
url: /el/java/com.aspose.drawing/texturebrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.drawing.Brush](../../com.aspose.drawing/brush)
```
public final class TextureBrush extends Brush
```

Κάθε ιδιότητα της κλάσης TextureBrush είναι ένα αντικείμενο Brush που χρησιμοποιεί μια εικόνα για να γεμίσει το εσωτερικό ενός σχήματος. Αυτή η κλάση δεν μπορεί να κληρονομηθεί.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [TextureBrush(Image bitmap)](#TextureBrush-com.aspose.drawing.Image-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [TextureBrush](../../com.aspose.drawing/texturebrush) που χρησιμοποιεί την καθορισμένη εικόνα. |
| [TextureBrush(Image image, int wrapMode)](#TextureBrush-com.aspose.drawing.Image-int-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [TextureBrush](../../com.aspose.drawing/texturebrush) που χρησιμοποιεί την καθορισμένη εικόνα και τη λειτουργία περιτύλιξης. |
| [TextureBrush(Image image, int wrapMode, RectangleF dstRect)](#TextureBrush-com.aspose.drawing.Image-int-com.aspose.drawing.RectangleF-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [TextureBrush](../../com.aspose.drawing/texturebrush) που χρησιμοποιεί την καθορισμένη εικόνα, τη λειτουργία περιτύλιξης και το οριοθετημένο ορθογώνιο. |
| [TextureBrush(Image image, RectangleF dstRect)](#TextureBrush-com.aspose.drawing.Image-com.aspose.drawing.RectangleF-) | Αρχικοποιεί μια νέα παρουσία της κλάσης [TextureBrush](../../com.aspose.drawing/texturebrush) που χρησιμοποιεί την καθορισμένη εικόνα και το ορθογώνιο περιγράμματος. |
| [TextureBrush(Image image, RectangleF dstRect, ImageAttributes imageAttr)](#TextureBrush-com.aspose.drawing.Image-com.aspose.drawing.RectangleF-com.aspose.drawing.imaging.ImageAttributes-) | Αρχικοποιεί μια νέα παρουσία της κλάσης [TextureBrush](../../com.aspose.drawing/texturebrush) που χρησιμοποιεί την καθορισμένη εικόνα, το ορθογώνιο περιγράμματος και τις ιδιότητες εικόνας. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getImage()](#getImage--) | Αποκτά το αντικείμενο Image που σχετίζεται με αυτό το αντικείμενο TextureBrush. |
| [getTransform()](#getTransform--) | Αποκτά ένα αντίγραφο του αντικειμένου Matrix που ορίζει μια τοπική γεωμετρική μετασχηματισμό για την εικόνα που σχετίζεται με αυτό το αντικείμενο TextureBrush. |
| [setTransform(Matrix value)](#setTransform-com.aspose.drawing.drawing2d.Matrix-) | Ορίζει ένα αντίγραφο του αντικειμένου Matrix που ορίζει μια τοπική γεωμετρική μετασχηματισμό για την εικόνα που σχετίζεται με αυτό το αντικείμενο TextureBrush. |
| [getWrapMode()](#getWrapMode--) | Αποκτά μια απαρίθμηση WrapMode που υποδεικνύει τη λειτουργία περιτύλιξης για αυτό το αντικείμενο TextureBrush. |
| [setWrapMode(int value)](#setWrapMode-int-) | Ορίζει μια απαρίθμηση WrapMode που υποδεικνύει τη λειτουργία περιτύλιξης για αυτό το αντικείμενο TextureBrush. |
| [deepClone()](#deepClone--) | Δημιουργεί ένα ακριβές αντίγραφο αυτού του αντικειμένου [TextureBrush](../../com.aspose.drawing/texturebrush). |
| [resetTransform()](#resetTransform--) | Επαναφέρει την ιδιότητα Transform αυτού του αντικειμένου [TextureBrush](../../com.aspose.drawing/texturebrush) στην ταυτότητα. |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-) | Πολλαπλασιάζει το αντικείμενο [Matrix](../../com.aspose.drawing.drawing2d/matrix) που αντιπροσωπεύει τη τοπική γεωμετρική μετασχηματισμό αυτού του αντικειμένου [TextureBrush](../../com.aspose.drawing/texturebrush) με το καθορισμένο αντικείμενο [Matrix](../../com.aspose.drawing.drawing2d/matrix) προσθέτοντας στην αρχή το καθορισμένο αντικείμενο [Matrix](../../com.aspose.drawing.drawing2d/matrix). |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-int-) | Πολλαπλασιάζει το αντικείμενο [Matrix](../../com.aspose.drawing.drawing2d/matrix) που αντιπροσωπεύει τη τοπική γεωμετρική μετασχηματισμό αυτού του αντικειμένου [TextureBrush](../../com.aspose.drawing/texturebrush) με το καθορισμένο αντικείμενο [Matrix](../../com.aspose.drawing.drawing2d/matrix) στη καθορισμένη σειρά. |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | Μετατοπίζει τη τοπική γεωμετρική μετασχηματισμό αυτού του αντικειμένου [TextureBrush](../../com.aspose.drawing/texturebrush) κατά τις καθορισμένες διαστάσεις. |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | Μετατοπίζει τη τοπική γεωμετρική μετασχηματισμό αυτού του αντικειμένου [TextureBrush](../../com.aspose.drawing/texturebrush) κατά τις καθορισμένες διαστάσεις στη καθορισμένη σειρά. |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | Κλιμακώνει τη τοπική γεωμετρική μετασχηματισμό αυτού του αντικειμένου [TextureBrush](../../com.aspose.drawing/texturebrush) κατά τα καθορισμένα ποσά. |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | Κλιμακώνει τη τοπική γεωμετρική μετασχηματισμό αυτού του αντικειμένου [TextureBrush](../../com.aspose.drawing/texturebrush) κατά τα καθορισμένα ποσά στη καθορισμένη σειρά. |
| [rotateTransform(float angle)](#rotateTransform-float-) | Περιστρέφει τη τοπική γεωμετρική μετασχηματισμό αυτού του αντικειμένου [TextureBrush](../../com.aspose.drawing/texturebrush) κατά το καθορισμένο ποσό. |
| [rotateTransform(float angle, int order)](#rotateTransform-float-int-) | Περιστρέφει τη τοπική γεωμετρική μετασχηματισμό αυτού του αντικειμένου [TextureBrush](../../com.aspose.drawing/texturebrush) κατά το καθορισμένο ποσό στη καθορισμένη σειρά. |
### TextureBrush(Image bitmap) {#TextureBrush-com.aspose.drawing.Image-}
```
public TextureBrush(Image bitmap)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [TextureBrush](../../com.aspose.drawing/texturebrush) που χρησιμοποιεί την καθορισμένη εικόνα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| bitmap | [Image](../../com.aspose.drawing/image) | Το αντικείμενο `Image`([.getImage](../../null/\#getImage)) με το οποίο αυτό το αντικείμενο [TextureBrush](../../com.aspose.drawing/texturebrush) γεμίζει τα εσωτερικά. |

### TextureBrush(Image image, int wrapMode) {#TextureBrush-com.aspose.drawing.Image-int-}
```
public TextureBrush(Image image, int wrapMode)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [TextureBrush](../../com.aspose.drawing/texturebrush) που χρησιμοποιεί την καθορισμένη εικόνα και τη λειτουργία περιτύλιξης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| image | [Image](../../com.aspose.drawing/image) | Η εικόνα. |
| wrapMode | int | Μια απαρίθμηση `WrapMode`([.getWrapMode](../../null/\#getWrapMode)/[.setWrapMode(int)](../../null/\#setWrapMode-int-)) που καθορίζει πώς αυτό το αντικείμενο [TextureBrush](../../com.aspose.drawing/texturebrush) τοποθετείται σε πλακίδια. |

### TextureBrush(Image image, int wrapMode, RectangleF dstRect) {#TextureBrush-com.aspose.drawing.Image-int-com.aspose.drawing.RectangleF-}
```
public TextureBrush(Image image, int wrapMode, RectangleF dstRect)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [TextureBrush](../../com.aspose.drawing/texturebrush) που χρησιμοποιεί την καθορισμένη εικόνα, τη λειτουργία περιτύλιξης και το οριοθετημένο ορθογώνιο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| image | [Image](../../com.aspose.drawing/image) | Η εικόνα. |
| wrapMode | int | Μια απαρίθμηση `WrapMode`([.getWrapMode](../../null/\#getWrapMode)/[.setWrapMode(int)](../../null/\#setWrapMode-int-)) που καθορίζει πώς αυτό το αντικείμενο [TextureBrush](../../com.aspose.drawing/texturebrush) τοποθετείται σε πλακίδια. |
| dstRect | [RectangleF](../../com.aspose.drawing/rectanglef) | Μια δομή [RectangleF](../../com.aspose.drawing/rectanglef) που αντιπροσωπεύει το ορθογώνιο περιγράμματος για αυτό το αντικείμενο [TextureBrush](../../com.aspose.drawing/texturebrush). |

### TextureBrush(Image image, RectangleF dstRect) {#TextureBrush-com.aspose.drawing.Image-com.aspose.drawing.RectangleF-}
```
public TextureBrush(Image image, RectangleF dstRect)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [TextureBrush](../../com.aspose.drawing/texturebrush) που χρησιμοποιεί την καθορισμένη εικόνα και το ορθογώνιο περιγράμματος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| image | [Image](../../com.aspose.drawing/image) | Το αντικείμενο `Image`([.getImage](../../null/\#getImage)) με το οποίο αυτό το αντικείμενο [TextureBrush](../../com.aspose.drawing/texturebrush) γεμίζει τα εσωτερικά. |
| dstRect | [RectangleF](../../com.aspose.drawing/rectanglef) | Μια δομή [RectangleF](../../com.aspose.drawing/rectanglef) που αντιπροσωπεύει το ορθογώνιο περιγράμματος για αυτό το αντικείμενο [TextureBrush](../../com.aspose.drawing/texturebrush). |

### TextureBrush(Image image, RectangleF dstRect, ImageAttributes imageAttr) {#TextureBrush-com.aspose.drawing.Image-com.aspose.drawing.RectangleF-com.aspose.drawing.imaging.ImageAttributes-}
```
public TextureBrush(Image image, RectangleF dstRect, ImageAttributes imageAttr)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [TextureBrush](../../com.aspose.drawing/texturebrush) που χρησιμοποιεί την καθορισμένη εικόνα, το ορθογώνιο περιγράμματος και τις ιδιότητες εικόνας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| image | [Image](../../com.aspose.drawing/image) | Το αντικείμενο Image με το οποίο αυτό το αντικείμενο TextureBrush γεμίζει τα εσωτερικά. |
| dstRect | [RectangleF](../../com.aspose.drawing/rectanglef) | Μια δομή RectangleF που αντιπροσωπεύει το ορθογώνιο περιγράμματος για αυτό το αντικείμενο TextureBrush. |
| imageAttr | [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes) | Ένα αντικείμενο ImageAttributes που περιέχει πρόσθετες πληροφορίες σχετικά με την εικόνα που χρησιμοποιείται από αυτό το αντικείμενο TextureBrush. |

### getImage() {#getImage--}
```
public Image getImage()
```


Αποκτά το αντικείμενο Image που σχετίζεται με αυτό το αντικείμενο TextureBrush.

**Returns:**
[Image](../../com.aspose.drawing/image) - the Image object associated with this TextureBrush object.
### getTransform() {#getTransform--}
```
public Matrix getTransform()
```


Αποκτά ένα αντίγραφο του αντικειμένου Matrix που ορίζει μια τοπική γεωμετρική μετασχηματισμό για την εικόνα που σχετίζεται με αυτό το αντικείμενο TextureBrush.

**Returns:**
[Matrix](../../com.aspose.drawing.drawing2d/matrix) - a copy of the Matrix object that defines a local geometric transformation for the image associated with this TextureBrush object.
### setTransform(Matrix value) {#setTransform-com.aspose.drawing.drawing2d.Matrix-}
```
public void setTransform(Matrix value)
```


Ορίζει ένα αντίγραφο του αντικειμένου Matrix που ορίζει μια τοπική γεωμετρική μετασχηματισμό για την εικόνα που σχετίζεται με αυτό το αντικείμενο TextureBrush.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | ένα αντίγραφο του αντικειμένου Matrix που ορίζει μια τοπική γεωμετρική μετασχηματισμό για την εικόνα που σχετίζεται με αυτό το αντικείμενο TextureBrush. |

### getWrapMode() {#getWrapMode--}
```
public int getWrapMode()
```


Αποκτά μια απαρίθμηση WrapMode που υποδεικνύει τη λειτουργία περιτύλιξης για αυτό το αντικείμενο TextureBrush.

**Returns:**
int - μια απαρίθμηση WrapMode που υποδεικνύει τη λειτουργία περιτύλιξης για αυτό το αντικείμενο TextureBrush.
### setWrapMode(int value) {#setWrapMode-int-}
```
public void setWrapMode(int value)
```


Ορίζει μια απαρίθμηση WrapMode που υποδεικνύει τη λειτουργία περιτύλιξης για αυτό το αντικείμενο TextureBrush.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int | μια απαρίθμηση WrapMode που υποδεικνύει τη λειτουργία περιτύλιξης για αυτό το αντικείμενο TextureBrush. |

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Δημιουργεί ένα ακριβές αντίγραφο αυτού του αντικειμένου [TextureBrush](../../com.aspose.drawing/texturebrush).

**Returns:**
java.lang.Object - Το αντικείμενο [TextureBrush](../../com.aspose.drawing/texturebrush) που δημιουργεί αυτή η μέθοδος, μετατρεπόμενο σε αντικείμενο Object.
### resetTransform() {#resetTransform--}
```
public void resetTransform()
```


Επαναφέρει την ιδιότητα Transform αυτού του αντικειμένου [TextureBrush](../../com.aspose.drawing/texturebrush) στην ταυτότητα.

### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-}
```
public void multiplyTransform(Matrix matrix)
```


Πολλαπλασιάζει το αντικείμενο [Matrix](../../com.aspose.drawing.drawing2d/matrix) που αντιπροσωπεύει τη τοπική γεωμετρική μετασχηματισμό αυτού του αντικειμένου [TextureBrush](../../com.aspose.drawing/texturebrush) με το καθορισμένο αντικείμενο [Matrix](../../com.aspose.drawing.drawing2d/matrix) προσθέτοντας στην αρχή το καθορισμένο αντικείμενο [Matrix](../../com.aspose.drawing.drawing2d/matrix).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | Το αντικείμενο [Matrix](../../com.aspose.drawing.drawing2d/matrix) με το οποίο θα πολλαπλασιαστεί η γεωμετρική μετασχηματισμός. |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-int-}
```
public void multiplyTransform(Matrix matrix, int order)
```


Πολλαπλασιάζει το αντικείμενο [Matrix](../../com.aspose.drawing.drawing2d/matrix) που αντιπροσωπεύει τη τοπική γεωμετρική μετασχηματισμό αυτού του αντικειμένου [TextureBrush](../../com.aspose.drawing/texturebrush) με το καθορισμένο αντικείμενο [Matrix](../../com.aspose.drawing.drawing2d/matrix) στη καθορισμένη σειρά.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | Το αντικείμενο [Matrix](../../com.aspose.drawing.drawing2d/matrix) με το οποίο θα πολλαπλασιαστεί η γεωμετρική μετασχηματισμός. |
| order | int | Μια απαρίθμηση [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder) που καθορίζει τη σειρά με την οποία θα πολλαπλασιαστούν οι δύο πίνακες. |

### translateTransform(float dx, float dy) {#translateTransform-float-float-}
```
public void translateTransform(float dx, float dy)
```


Μετατοπίζει την τοπική γεωμετρική μετασχηματισμό αυτού του αντικειμένου [TextureBrush](../../com.aspose.drawing/texturebrush) με τις καθορισμένες διαστάσεις. Αυτή η μέθοδος προσθέτει τη μετάφραση στον μετασχηματισμό.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| dx | float | Η διάσταση κατά την οποία θα μετατοπιστεί ο μετασχηματισμός στην κατεύθυνση x. |
| dy | float | Η διάσταση κατά την οποία θα μετατοπιστεί ο μετασχηματισμός στην κατεύθυνση y. |

### translateTransform(float dx, float dy, int order) {#translateTransform-float-float-int-}
```
public void translateTransform(float dx, float dy, int order)
```


Μετατοπίζει τη τοπική γεωμετρική μετασχηματισμό αυτού του αντικειμένου [TextureBrush](../../com.aspose.drawing/texturebrush) κατά τις καθορισμένες διαστάσεις στη καθορισμένη σειρά.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| dx | float | Η διάσταση κατά την οποία θα μετατοπιστεί ο μετασχηματισμός στην κατεύθυνση x. |
| dy | float | Η διάσταση κατά την οποία θα μετατοπιστεί ο μετασχηματισμός στην κατεύθυνση y. |
| order | int | Η σειρά (prepend ή append) με την οποία εφαρμόζεται η μετάφραση. |

### scaleTransform(float sx, float sy) {#scaleTransform-float-float-}
```
public void scaleTransform(float sx, float sy)
```


Κλιμακώνει την τοπική γεωμετρική μετασχηματισμό αυτού του αντικειμένου [TextureBrush](../../com.aspose.drawing/texturebrush) με τις καθορισμένες ποσότητες. Αυτή η μέθοδος προσθέτει τον πίνακα κλιμάκωσης στον μετασχηματισμό.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sx | float | Το μέγεθος κατά το οποίο θα κλιμακωθεί ο μετασχηματισμός στην κατεύθυνση x. |
| sy | float | Το μέγεθος κατά το οποίο θα κλιμακωθεί ο μετασχηματισμός στην κατεύθυνση y. |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public void scaleTransform(float sx, float sy, int order)
```


Κλιμακώνει τη τοπική γεωμετρική μετασχηματισμό αυτού του αντικειμένου [TextureBrush](../../com.aspose.drawing/texturebrush) κατά τα καθορισμένα ποσά στη καθορισμένη σειρά.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sx | float | Το μέγεθος κατά το οποίο θα κλιμακωθεί ο μετασχηματισμός στην κατεύθυνση x. |
| sy | float | Το μέγεθος κατά το οποίο θα κλιμακωθεί ο μετασχηματισμός στην κατεύθυνση y. |
| order | int | Μια απαρίθμηση [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder) που καθορίζει αν θα προσαρτηθεί ή θα προταθεί ο πίνακας κλιμάκωσης. |

### rotateTransform(float angle) {#rotateTransform-float-}
```
public void rotateTransform(float angle)
```


Περιστρέφει την τοπική γεωμετρική μετασχηματισμό αυτού του αντικειμένου [TextureBrush](../../com.aspose.drawing/texturebrush) με την καθορισμένη ποσότητα. Αυτή η μέθοδος προσθέτει την περιστροφή στον μετασχηματισμό.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| γωνία | float | Η γωνία της περιστροφής. |

### rotateTransform(float angle, int order) {#rotateTransform-float-int-}
```
public void rotateTransform(float angle, int order)
```


Περιστρέφει τη τοπική γεωμετρική μετασχηματισμό αυτού του αντικειμένου [TextureBrush](../../com.aspose.drawing/texturebrush) κατά το καθορισμένο ποσό στη καθορισμένη σειρά.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| γωνία | float | Η γωνία της περιστροφής. |
| order | int | Μια απαρίθμηση [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder) που καθορίζει αν θα προσαρτηθεί ή θα προταθεί ο πίνακας περιστροφής. |

