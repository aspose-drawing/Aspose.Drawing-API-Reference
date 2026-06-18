---
title: Matrix
second_title: Αναφορά API του Aspose.Drawing for Java
description: Ενσωματώνει έναν 3x3 αφινικό πίνακα που αντιπροσωπεύει γεωμετρικό μετασχηματισμό.
type: docs
weight: 33
url: /el/java/com.aspose.drawing.drawing2d/matrix/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public final class Matrix implements System.IDisposable
```

Περιέχει έναν 3-by-3 affine πίνακα που αντιπροσωπεύει έναν γεωμετρικό μετασχηματισμό. Αυτή η κλάση δεν μπορεί να κληρονομηθεί.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [Matrix()](#Matrix--) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης Matrix ως τον μοναδιαίο πίνακα. |
| [Matrix(float m11, float m12, float m21, float m22, float dx, float dy)](#Matrix-float-float-float-float-float-float-) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης Matrix με τα καθορισμένα στοιχεία. |
| [Matrix(Rectangle rect, Point[] plgpts)](#Matrix-com.aspose.drawing.Rectangle-com.aspose.drawing.Point---) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [Matrix](../../com.aspose.drawing.drawing2d/matrix) στον γεωμετρικό μετασχηματισμό που ορίζεται από το καθορισμένο ορθογώνιο και τον πίνακα σημείων. |
| [Matrix(RectangleF rect, PointF[] plgpts)](#Matrix-com.aspose.drawing.RectangleF-com.aspose.drawing.PointF---) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [Matrix](../../com.aspose.drawing.drawing2d/matrix) στον γεωμετρικό μετασχηματισμό που ορίζεται από το καθορισμένο ορθογώνιο και τον πίνακα σημείων. |
## Fields

| Field | Περιγραφή |
| --- | --- |
| [IdentityTransform](#IdentityTransform) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getElements()](#getElements--) | Επιστρέφει έναν πίνακα τιμών κινητής υποδιαστολής που αντιπροσωπεύει τα στοιχεία αυτού του Matrix. |
| [isIdentity()](#isIdentity--) | Επιστρέφει μια τιμή που υποδεικνύει εάν αυτό το Matrix είναι ο μοναδιαίος πίνακας. |
| [isInvertible()](#isInvertible--) | Επιστρέφει μια τιμή που υποδεικνύει εάν αυτό το Matrix είναι αντιστρέψιμο. |
| [getOffsetX()](#getOffsetX--) | Λαμβάνει την τιμή μετάφρασης x (την τιμή dx ή το στοιχείο στην τρίτη γραμμή και πρώτη στήλη) αυτού του Matrix. |
| [getOffsetY()](#getOffsetY--) | Λαμβάνει την τιμή μετάφρασης y (την τιμή `dy` ή το στοιχείο στην τρίτη γραμμή και δεύτερη στήλη) αυτού του Matrix. |
| [dispose()](#dispose--) | Απελευθερώνει όλους τους πόρους που χρησιμοποιούνται από αυτό το Matrix. |
| [deepClone()](#deepClone--) | Δημιουργεί ένα ακριβές αντίγραφο αυτού του Matrix. |
| [invert()](#invert--) | Αντιστρέφει αυτό το Matrix, εάν είναι αντιστρέψιμο. |
| [translate(float offsetX, float offsetY)](#translate-float-float-) | Εφαρμόζει το καθορισμένο διάνυσμα μετάφρασης (offsetX και offsetY) σε αυτό το Matrix προσθέτοντας το διάνυσμα μετάφρασης στην αρχή. |
| [translate(float offsetX, float offsetY, int order)](#translate-float-float-int-) | Εφαρμόζει το καθορισμένο διάνυσμα μετάφρασης σε αυτό το Matrix με τη καθορισμένη σειρά. |
| [transformVectors(PointF[] pts)](#transformVectors-com.aspose.drawing.PointF---) | Πολλαπλασιάζει κάθε διάνυσμα σε έναν πίνακα με το matrix. |
| [scale(float scaleX, float scaleY)](#scale-float-float-) | Εφαρμόζει το καθορισμένο διάνυσμα κλίμακας σε αυτό το Matrix προσθέτοντας το διάνυσμα κλίμακας στην αρχή. |
| [scale(float scaleX, float scaleY, int order)](#scale-float-float-int-) | Εφαρμόζει το καθορισμένο διάνυσμα κλίμακας (scaleX και scaleY) σε αυτό το Matrix χρησιμοποιώντας τη καθορισμένη σειρά. |
| [shear(float shearX, float shearY)](#shear-float-float-) | Εφαρμόζει το καθορισμένο διάνυσμα shear σε αυτό το Matrix προσθέτοντας τη μετασχηματισμό shear στην αρχή. |
| [shear(float shearX, float shearY, int order)](#shear-float-float-int-) | Εφαρμόζει το καθορισμένο διάνυσμα shear σε αυτό το Matrix με τη καθορισμένη σειρά. |
| [rotateAt(float angle, PointF point)](#rotateAt-float-com.aspose.drawing.PointF-) | Εφαρμόζει μια δεξιόστροφη περιστροφή σε αυτό το Matrix γύρω από το σημείο που καθορίζεται στην παράμετρο point, και προσθέτοντας την περιστροφή στην αρχή. |
| [rotateAt(float angle, PointF point, int order)](#rotateAt-float-com.aspose.drawing.PointF-int-) | Εφαρμόζει μια δεξιόστροφη περιστροφή γύρω από το καθορισμένο σημείο σε αυτό το Matrix με τη καθορισμένη σειρά. |
| [transformPoints(PointF[] pts)](#transformPoints-com.aspose.drawing.PointF---) | Εφαρμόζει τον γεωμετρικό μετασχηματισμό που αντιπροσωπεύεται από αυτό το [Matrix](../../com.aspose.drawing.drawing2d/matrix) σε έναν καθορισμένο πίνακα σημείων. |
| [transformPoints(Point[] pts)](#transformPoints-com.aspose.drawing.Point---) | Εφαρμόζει τον γεωμετρικό μετασχηματισμό που αντιπροσωπεύεται από αυτό το [Matrix](../../com.aspose.drawing.drawing2d/matrix) σε έναν καθορισμένο πίνακα σημείων. |
| [multiply(Matrix matrix)](#multiply-com.aspose.drawing.drawing2d.Matrix-) | Πολλαπλασιάζει αυτό το [Matrix](../../com.aspose.drawing.drawing2d/matrix) με το matrix που καθορίζεται στην παράμετρο `matrix`, προσθέτοντας το καθορισμένο [Matrix](../../com.aspose.drawing.drawing2d/matrix) στην αρχή. |
| [multiply(Matrix matrix, int order)](#multiply-com.aspose.drawing.drawing2d.Matrix-int-) | Πολλαπλασιάζει αυτό το [Matrix](../../com.aspose.drawing.drawing2d/matrix) με το matrix που καθορίζεται στην παράμετρο `matrix`, και με τη σειρά που καθορίζεται στην παράμετρο `order`. |
| [rotate(float angle)](#rotate-float-) | Προσθέτει στην αρχή αυτού του [Matrix](../../com.aspose.drawing.drawing2d/matrix) μια δεξιόστροφη περιστροφή, γύρω από το αρχικό σημείο και με την καθορισμένη γωνία. |
| [rotate(float angle, int order)](#rotate-float-int-) | Εφαρμόζει μια δεξιόστροφη περιστροφή με ποσό που καθορίζεται στην παράμετρο angle, γύρω από το αρχικό σημείο (συντεταγμένες μηδέν x και y) για αυτό το [Matrix](../../com.aspose.drawing.drawing2d/matrix). |
| [reset()](#reset--) | Επαναφέρει αυτό το [Matrix](../../com.aspose.drawing.drawing2d/matrix) ώστε να έχει τα στοιχεία του identity matrix. |
### Matrix() {#Matrix--}
```
public Matrix()
```


Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης Matrix ως τον μοναδιαίο πίνακα.

### Matrix(float m11, float m12, float m21, float m22, float dx, float dy) {#Matrix-float-float-float-float-float-float-}
```
public Matrix(float m11, float m12, float m21, float m22, float dx, float dy)
```


Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης Matrix με τα καθορισμένα στοιχεία.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| m11 | float | Η τιμή στην πρώτη γραμμή και πρώτη στήλη του νέου Matrix. |
| m12 | float | Η τιμή στην πρώτη γραμμή και δεύτερη στήλη του νέου Matrix. |
| m21 | float | Η τιμή στη δεύτερη γραμμή και στην πρώτη στήλη του νέου Matrix. |
| m22 | float | Η τιμή στη δεύτερη γραμμή και στη δεύτερη στήλη του νέου Matrix. |
| dx | float | Η τιμή στην τρίτη γραμμή και στην πρώτη στήλη του νέου Matrix. |
| dy | float | Η τιμή στην τρίτη γραμμή και στη δεύτερη στήλη του νέου Matrix. |

### Matrix(Rectangle rect, Point[] plgpts) {#Matrix-com.aspose.drawing.Rectangle-com.aspose.drawing.Point---}
```
public Matrix(Rectangle rect, Point[] plgpts)
```


Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [Matrix](../../com.aspose.drawing.drawing2d/matrix) στον γεωμετρικό μετασχηματισμό που ορίζεται από το καθορισμένο ορθογώνιο και τον πίνακα σημείων.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | Μια δομή [Rectangle](../../com.aspose.drawing/rectangle) που αντιπροσωπεύει το ορθογώνιο που θα μετασχηματιστεί. |
| plgpts | [Point\[\]](../../com.aspose.drawing/point) | Ένας πίνακας τριών δομών [Point](../../com.aspose.drawing/point) που αντιπροσωπεύει τα σημεία ενός παραλληλογράμμου στο οποίο θα μετατραπούν οι άνω-αριστερές, άνω-δεξιές και κάτω-αριστερές γωνίες του ορθογωνίου. Η κάτω-δεξιά γωνία του παραλληλογράμμου προκύπτει από τις πρώτες τρεις γωνίες. |

### Matrix(RectangleF rect, PointF[] plgpts) {#Matrix-com.aspose.drawing.RectangleF-com.aspose.drawing.PointF---}
```
public Matrix(RectangleF rect, PointF[] plgpts)
```


Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [Matrix](../../com.aspose.drawing.drawing2d/matrix) στον γεωμετρικό μετασχηματισμό που ορίζεται από το καθορισμένο ορθογώνιο και τον πίνακα σημείων.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | Μια δομή [RectangleF](../../com.aspose.drawing/rectanglef) που αντιπροσωπεύει το ορθογώνιο που θα μετασχηματιστεί. |
| plgpts | [PointF\[\]](../../com.aspose.drawing/pointf) | Ένας πίνακας τριών δομών [PointF](../../com.aspose.drawing/pointf) που αντιπροσωπεύει τα σημεία ενός παραλληλογράμμου στο οποίο θα μετατραπούν οι άνω-αριστερές, άνω-δεξιές και κάτω-αριστερές γωνίες του ορθογωνίου. Η κάτω-δεξιά γωνία του παραλληλογράμμου προκύπτει από τις πρώτες τρεις γωνίες. |

### IdentityTransform {#IdentityTransform}
```
public static final Matrix IdentityTransform
```


### getElements() {#getElements--}
```
public float[] getElements()
```


Επιστρέφει έναν πίνακα τιμών κινητής υποδιαστολής που αντιπροσωπεύει τα στοιχεία αυτού του Matrix.

**Returns:**
float[] - ένας πίνακας τιμών κινητής υποδιαστολής που αντιπροσωπεύει τα στοιχεία αυτού του Matrix.
### isIdentity() {#isIdentity--}
```
public boolean isIdentity()
```


Επιστρέφει μια τιμή που υποδεικνύει εάν αυτό το Matrix είναι ο μοναδιαίος πίνακας.

**Returns:**
boolean - μια τιμή που υποδεικνύει αν αυτό το Matrix είναι ο μοναδιαίος πίνακας.
### isInvertible() {#isInvertible--}
```
public boolean isInvertible()
```


Επιστρέφει μια τιμή που υποδεικνύει εάν αυτό το Matrix είναι αντιστρέψιμο.

**Returns:**
boolean - μια τιμή που υποδεικνύει αν αυτό το Matrix είναι αντιστρέψιμο.
### getOffsetX() {#getOffsetX--}
```
public float getOffsetX()
```


Λαμβάνει την τιμή μετάφρασης x (την τιμή dx ή το στοιχείο στην τρίτη γραμμή και πρώτη στήλη) αυτού του Matrix.

**Returns:**
float - η τιμή μετάφρασης x (η τιμή dx, ή το στοιχείο στην τρίτη γραμμή και πρώτη στήλη) του αυτού του Matrix.
### getOffsetY() {#getOffsetY--}
```
public float getOffsetY()
```


Λαμβάνει την τιμή μετάφρασης y (την τιμή `dy` ή το στοιχείο στην τρίτη γραμμή και δεύτερη στήλη) αυτού του Matrix.

**Returns:**
float - η τιμή μετάφρασης y (η τιμή `dy`, ή το στοιχείο στην τρίτη γραμμή και δεύτερη στήλη) του αυτού του Matrix.
### dispose() {#dispose--}
```
public void dispose()
```


Απελευθερώνει όλους τους πόρους που χρησιμοποιούνται από αυτό το Matrix.

--------------------

Αυτή η μέθοδος στην πραγματικότητα δεν κάνει τίποτα. Είναι μόνο για συμβατότητα με το API του System.Drawing.

### deepClone() {#deepClone--}
```
public Matrix deepClone()
```


Δημιουργεί ένα ακριβές αντίγραφο αυτού του Matrix.

**Returns:**
[Matrix](../../com.aspose.drawing.drawing2d/matrix) - The Matrix that this method creates.
### invert() {#invert--}
```
public void invert()
```


Αντιστρέφει αυτό το Matrix, εάν είναι αντιστρέψιμο.

### translate(float offsetX, float offsetY) {#translate-float-float-}
```
public void translate(float offsetX, float offsetY)
```


Εφαρμόζει το καθορισμένο διάνυσμα μετάφρασης (offsetX και offsetY) σε αυτό το Matrix προσθέτοντας το διάνυσμα μετάφρασης στην αρχή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| offsetX | float | Η τιμή x κατά την οποία θα μεταφραστεί αυτό το Matrix. |
| offsetY | float | Η τιμή y κατά την οποία θα μεταφραστεί αυτό το Matrix. |

### translate(float offsetX, float offsetY, int order) {#translate-float-float-int-}
```
public void translate(float offsetX, float offsetY, int order)
```


Εφαρμόζει το καθορισμένο διάνυσμα μετάφρασης σε αυτό το Matrix με τη καθορισμένη σειρά.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| offsetX | float | Η τιμή x κατά την οποία θα μεταφραστεί αυτό το Matrix. |
| offsetY | float | Η τιμή y κατά την οποία θα μεταφραστεί αυτό το Matrix. |
| order | int | Ένα MatrixOrder που καθορίζει τη σειρά (προσθήκη ή προεγγραφή) με την οποία η μετάφραση εφαρμόζεται σε αυτό το Matrix. |

### transformVectors(PointF[] pts) {#transformVectors-com.aspose.drawing.PointF---}
```
public void transformVectors(PointF[] pts)
```


Πολλαπλασιάζει κάθε διάνυσμα σε έναν πίνακα με το matrix. Τα στοιχεία μετάφρασης αυτού του matrix (τρίτη γραμμή) αγνοούνται.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pts | [PointF\[\]](../../com.aspose.drawing/pointf) | Ένας πίνακας δομών [PointF](../../com.aspose.drawing/pointf) που αντιπροσωπεύει τα σημεία προς μετασχηματισμό. |

### scale(float scaleX, float scaleY) {#scale-float-float-}
```
public void scale(float scaleX, float scaleY)
```


Εφαρμόζει το καθορισμένο διάνυσμα κλίμακας σε αυτό το Matrix προσθέτοντας το διάνυσμα κλίμακας στην αρχή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| scaleX | float | Η τιμή με την οποία θα κλιμακωθεί αυτό το Matrix στην κατεύθυνση του άξονα x. |
| scaleY | float | Η τιμή με την οποία κλιμακώνεται αυτό το Matrix στην κατεύθυνση του άξονα y. |

### scale(float scaleX, float scaleY, int order) {#scale-float-float-int-}
```
public void scale(float scaleX, float scaleY, int order)
```


Εφαρμόζει το καθορισμένο διάνυσμα κλίμακας (scaleX και scaleY) σε αυτό το Matrix χρησιμοποιώντας τη καθορισμένη σειρά.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| scaleX | float | Η τιμή με την οποία θα κλιμακωθεί αυτό το Matrix στην κατεύθυνση του άξονα x. |
| scaleY | float | Η τιμή με την οποία κλιμακώνεται αυτό το Matrix στην κατεύθυνση του άξονα y. |
| order | int | Ένα MatrixOrder που καθορίζει τη σειρά (προσθήκη ή προεξαγωγή) με την οποία εφαρμόζεται το διανύσμα κλίμακας σε αυτό το Matrix. |

### shear(float shearX, float shearY) {#shear-float-float-}
```
public void shear(float shearX, float shearY)
```


Εφαρμόζει το καθορισμένο διάνυσμα shear σε αυτό το Matrix προσθέτοντας τη μετασχηματισμό shear στην αρχή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| shearX | float | Ο οριζόντιος συντελεστής παραμόρφωσης. |
| shearY | float | Ο κάθετος συντελεστής παραμόρφωσης. |

### shear(float shearX, float shearY, int order) {#shear-float-float-int-}
```
public void shear(float shearX, float shearY, int order)
```


Εφαρμόζει το καθορισμένο διάνυσμα shear σε αυτό το Matrix με τη καθορισμένη σειρά.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| shearX | float | Ο οριζόντιος συντελεστής παραμόρφωσης. |
| shearY | float | Ο κάθετος συντελεστής παραμόρφωσης. |
| order | int | Ένα MatrixOrder που καθορίζει τη σειρά (προσθήκη ή προεξαγωγή) με την οποία εφαρμόζεται η παραμόρφωση. |

### rotateAt(float angle, PointF point) {#rotateAt-float-com.aspose.drawing.PointF-}
```
public void rotateAt(float angle, PointF point)
```


Εφαρμόζει μια δεξιόστροφη περιστροφή σε αυτό το Matrix γύρω από το σημείο που καθορίζεται στην παράμετρο point, και προσθέτοντας την περιστροφή στην αρχή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| γωνία | float | Η γωνία (έκταση) της περιστροφής, σε μοίρες. |
| point | [PointF](../../com.aspose.drawing/pointf) | Ένα PointF που αντιπροσωπεύει το κέντρο της περιστροφής. |

### rotateAt(float angle, PointF point, int order) {#rotateAt-float-com.aspose.drawing.PointF-int-}
```
public void rotateAt(float angle, PointF point, int order)
```


Εφαρμόζει μια δεξιόστροφη περιστροφή γύρω από το καθορισμένο σημείο σε αυτό το Matrix με τη καθορισμένη σειρά.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| γωνία | float | Η γωνία της περιστροφής, σε μοίρες. |
| point | [PointF](../../com.aspose.drawing/pointf) | Ένα PointF που αντιπροσωπεύει το κέντρο της περιστροφής. |
| order | int | Ένα MatrixOrder που καθορίζει τη σειρά (προσθήκη ή προεξαγωγή) με την οποία εφαρμόζεται η περιστροφή. |

### transformPoints(PointF[] pts) {#transformPoints-com.aspose.drawing.PointF---}
```
public void transformPoints(PointF[] pts)
```


Εφαρμόζει τον γεωμετρικό μετασχηματισμό που αντιπροσωπεύεται από αυτό το [Matrix](../../com.aspose.drawing.drawing2d/matrix) σε έναν καθορισμένο πίνακα σημείων.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pts | [PointF\[\]](../../com.aspose.drawing/pointf) | Ένας πίνακας δομών [PointF](../../com.aspose.drawing/pointf) που αντιπροσωπεύει τα σημεία προς μετασχηματισμό. |

### transformPoints(Point[] pts) {#transformPoints-com.aspose.drawing.Point---}
```
public void transformPoints(Point[] pts)
```


Εφαρμόζει τον γεωμετρικό μετασχηματισμό που αντιπροσωπεύεται από αυτό το [Matrix](../../com.aspose.drawing.drawing2d/matrix) σε έναν καθορισμένο πίνακα σημείων.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pts | [Point\[\]](../../com.aspose.drawing/point) | Ένας πίνακας δομών [Point](../../com.aspose.drawing/point) που αντιπροσωπεύει τα σημεία προς μετασχηματισμό. |

### multiply(Matrix matrix) {#multiply-com.aspose.drawing.drawing2d.Matrix-}
```
public void multiply(Matrix matrix)
```


Πολλαπλασιάζει αυτό το [Matrix](../../com.aspose.drawing.drawing2d/matrix) με το matrix που καθορίζεται στην παράμετρο `matrix`, προσθέτοντας το καθορισμένο [Matrix](../../com.aspose.drawing.drawing2d/matrix) στην αρχή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | Το [Matrix](../../com.aspose.drawing.drawing2d/matrix) με το οποίο πρέπει να πολλαπλασιαστεί αυτό το [Matrix](../../com.aspose.drawing.drawing2d/matrix). |

### multiply(Matrix matrix, int order) {#multiply-com.aspose.drawing.drawing2d.Matrix-int-}
```
public void multiply(Matrix matrix, int order)
```


Πολλαπλασιάζει αυτό το [Matrix](../../com.aspose.drawing.drawing2d/matrix) με το matrix που καθορίζεται στην παράμετρο `matrix`, και με τη σειρά που καθορίζεται στην παράμετρο `order`.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | Το [Matrix](../../com.aspose.drawing.drawing2d/matrix) με το οποίο πρέπει να πολλαπλασιαστεί αυτό το [Matrix](../../com.aspose.drawing.drawing2d/matrix). |
| order | int | Το [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder) που αντιπροσωπεύει τη σειρά του πολλαπλασιασμού. |

### rotate(float angle) {#rotate-float-}
```
public void rotate(float angle)
```


Προσθέτει στην αρχή αυτού του [Matrix](../../com.aspose.drawing.drawing2d/matrix) μια δεξιόστροφη περιστροφή, γύρω από το αρχικό σημείο και με την καθορισμένη γωνία.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| γωνία | float | Η γωνία της περιστροφής, σε μοίρες. |

### rotate(float angle, int order) {#rotate-float-int-}
```
public void rotate(float angle, int order)
```


Εφαρμόζει μια δεξιόστροφη περιστροφή με ποσό που καθορίζεται στην παράμετρο angle, γύρω από το αρχικό σημείο (συντεταγμένες μηδέν x και y) για αυτό το [Matrix](../../com.aspose.drawing.drawing2d/matrix).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| γωνία | float | Η γωνία της περιστροφής, σε μοίρες. |
| order | int | Ένα [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder) που καθορίζει τη σειρά (προσθήκη ή προεξαγωγή) με την οποία εφαρμόζεται η περιστροφή σε αυτό το [Matrix](../../com.aspose.drawing.drawing2d/matrix). |

### reset() {#reset--}
```
public void reset()
```


Επαναφέρει αυτό το [Matrix](../../com.aspose.drawing.drawing2d/matrix) ώστε να έχει τα στοιχεία του identity matrix.

