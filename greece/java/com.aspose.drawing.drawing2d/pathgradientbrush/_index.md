---
title: PathGradientBrush
second_title: Αναφορά API του Aspose.Drawing for Java
description: Περιέχει ένα αντικείμενο που γεμίζει το εσωτερικό ενός αντικειμένου με διαβάθμιση.
type: docs
weight: 36
url: /el/java/com.aspose.drawing.drawing2d/pathgradientbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.drawing.Brush](../../com.aspose.drawing/brush)
```
public final class PathGradientBrush extends Brush
```

Περιέχει ένα αντικείμενο [Brush](../../com.aspose.drawing/brush) που γεμίζει το εσωτερικό ενός αντικειμένου [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) με διαβάθμιση. Αυτή η κλάση δεν μπορεί να κληρονομηθεί.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [PathGradientBrush(PointF[] points)](#PathGradientBrush-com.aspose.drawing.PointF---) | Αρχικοποιεί μια νέα παρουσία της κλάσης [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) με τα καθορισμένα σημεία. |
| [PathGradientBrush(PointF[] points, int wrapMode)](#PathGradientBrush-com.aspose.drawing.PointF---int-) | Αρχικοποιεί μια νέα παρουσία της κλάσης [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) με τα καθορισμένα σημεία και τη λειτουργία περιτύλιξης. |
| [PathGradientBrush(Point[] points)](#PathGradientBrush-com.aspose.drawing.Point---) | Αρχικοποιεί μια νέα παρουσία της κλάσης [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) με τα καθορισμένα σημεία. |
| [PathGradientBrush(Point[] points, int wrapMode)](#PathGradientBrush-com.aspose.drawing.Point---int-) | Αρχικοποιεί μια νέα παρουσία της κλάσης [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) με τα καθορισμένα σημεία και τη λειτουργία περιτύλιξης. |
| [PathGradientBrush(GraphicsPath path)](#PathGradientBrush-com.aspose.drawing.drawing2d.GraphicsPath-) | Αρχικοποιεί μια νέα παρουσία της κλάσης [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) με το καθορισμένο μονοπάτι. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getCenterColor()](#getCenterColor--) | Λαμβάνει ή ορίζει το χρώμα στο κέντρο της διαβάθμισης διαδρομής. |
| [setCenterColor(Color value)](#setCenterColor-com.aspose.drawing.Color-) | Λαμβάνει ή ορίζει το χρώμα στο κέντρο της διαβάθμισης διαδρομής. |
| [getSurroundColors()](#getSurroundColors--) | Λαμβάνει ή ορίζει έναν πίνακα χρωμάτων που αντιστοιχούν στα σημεία της διαδρομής που γεμίζει αυτό το [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush). |
| [setSurroundColors(Color[] value)](#setSurroundColors-com.aspose.drawing.Color---) | Λαμβάνει ή ορίζει έναν πίνακα χρωμάτων που αντιστοιχούν στα σημεία της διαδρομής που γεμίζει αυτό το [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush). |
| [getCenterPoint()](#getCenterPoint--) | Λαμβάνει ή ορίζει το κεντρικό σημείο της διαβάθμισης διαδρομής. |
| [setCenterPoint(PointF value)](#setCenterPoint-com.aspose.drawing.PointF-) | Λαμβάνει ή ορίζει το κεντρικό σημείο της διαβάθμισης διαδρομής. |
| [getRectangle()](#getRectangle--) | Λαμβάνει ένα οριοθετημένο ορθογώνιο για αυτό το [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush). |
| [getBlend()](#getBlend--) | Gets or sets a `Blend`([.getBlend](../../null/\#getBlend)/[.setBlend(Blend)](../../null/\#setBlend-Blend-)) that specifies positions and factors that define a custom falloff for the gradient. |
| [setBlend(Blend value)](#setBlend-com.aspose.drawing.drawing2d.Blend-) | Gets or sets a `Blend`([.getBlend](../../null/\#getBlend)/[.setBlend(Blend)](../../null/\#setBlend-Blend-)) that specifies positions and factors that define a custom falloff for the gradient. |
| [getInterpolationColors()](#getInterpolationColors--) | Gets or sets a [ColorBlend](../../com.aspose.drawing.drawing2d/colorblend) that defines a multicolor linear gradient. |
| [setInterpolationColors(ColorBlend value)](#setInterpolationColors-com.aspose.drawing.drawing2d.ColorBlend-) | Gets or sets a [ColorBlend](../../com.aspose.drawing.drawing2d/colorblend) that defines a multicolor linear gradient. |
| [getTransform()](#getTransform--) | Λαμβάνει ή ορίζει ένα αντίγραφο του [Matrix](../../com.aspose.drawing.drawing2d/matrix) που ορίζει έναν τοπικό γεωμετρικό μετασχηματισμό για αυτό το [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush). |
| [setTransform(Matrix value)](#setTransform-com.aspose.drawing.drawing2d.Matrix-) | Λαμβάνει ή ορίζει ένα αντίγραφο του [Matrix](../../com.aspose.drawing.drawing2d/matrix) που ορίζει έναν τοπικό γεωμετρικό μετασχηματισμό για αυτό το [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush). |
| [getFocusScales()](#getFocusScales--) | Λαμβάνει ή ορίζει το σημείο εστίασης για τη μείωση της διαβάθμισης. |
| [setFocusScales(PointF value)](#setFocusScales-com.aspose.drawing.PointF-) | Λαμβάνει ή ορίζει το σημείο εστίασης για τη μείωση της διαβάθμισης. |
| [getWrapMode()](#getWrapMode--) | Λαμβάνει ή ορίζει ένα `WrapMode`([.getWrapMode](../../null/\#getWrapMode)/[.setWrapMode(int)](../../null/\#setWrapMode-int-)) που υποδεικνύει τη λειτουργία περιτύλιξης για αυτό το [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush). |
| [setWrapMode(int value)](#setWrapMode-int-) | Λαμβάνει ή ορίζει ένα `WrapMode`([.getWrapMode](../../null/\#getWrapMode)/[.setWrapMode(int)](../../null/\#setWrapMode-int-)) που υποδεικνύει τη λειτουργία περιτύλιξης για αυτό το [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush). |
| [deepClone()](#deepClone--) | Δημιουργεί ένα ακριβές αντίγραφο αυτού του [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush). |
| [setSigmaBellShape(float focus)](#setSigmaBellShape-float-) | Δημιουργεί ένα πινέλο διαβάθμισης που αλλάζει χρώμα ξεκινώντας από το κέντρο της διαδρομής προς τα έξω μέχρι το όριο της διαδρομής. |
| [setSigmaBellShape(float focus, float scale)](#setSigmaBellShape-float-float-) | Δημιουργεί ένα πινέλο διαβάθμισης που αλλάζει χρώμα ξεκινώντας από το κέντρο της διαδρομής προς τα έξω μέχρι το όριο της διαδρομής. |
| [setBlendTriangularShape(float focus)](#setBlendTriangularShape-float-) | Δημιουργεί μια διαβάθμιση με κεντρικό χρώμα και γραμμική μείωση προς ένα περιβάλλον χρώμα. |
| [setBlendTriangularShape(float focus, float scale)](#setBlendTriangularShape-float-float-) | Δημιουργεί μια διαβάθμιση με κεντρικό χρώμα και γραμμική εσώλεια προς κάθε γύρω χρώμα. |
| [resetTransform()](#resetTransform--) | Επαναφέρει την ιδιότητα `PathGradientBrush.Transform` στην ταυτότητα. |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-) | Ενημερώνει τον πίνακα μετασχηματισμού του πινέλου με το γινόμενο του πίνακα μετασχηματισμού του πινέλου πολλαπλασιασμένο με έναν άλλο πίνακα. |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-int-) | Ενημερώνει τον πίνακα μετασχηματισμού του πινέλου με το γινόμενο του πίνακα μετασχηματισμού του πινέλου πολλαπλασιασμένο με έναν άλλο πίνακα. |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | Εφαρμόζει τη συγκεκριμένη μετάθεση στον τοπικό γεωμετρικό μετασχηματισμό. |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | Εφαρμόζει τη συγκεκριμένη μετάθεση στον τοπικό γεωμετρικό μετασχηματισμό με την καθορισμένη σειρά. |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | Scales the local geometric transform by the specified amounts. |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | Scales the local geometric transform by the specified amounts in the specified order. |
| [rotateTransform(float angle)](#rotateTransform-float-) | Rotates the local geometric transform by the specified amount. |
| [rotateTransform(float angle, int order)](#rotateTransform-float-int-) | Rotates the local geometric transform by the specified amount in the specified order. |
### PathGradientBrush(PointF[] points) {#PathGradientBrush-com.aspose.drawing.PointF---}
```
public PathGradientBrush(PointF[] points)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) με τα καθορισμένα σημεία.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.drawing/pointf) | Ένας πίνακας δομών [PointF](../../com.aspose.drawing/pointf) που αντιπροσωπεύει τα σημεία που σχηματίζουν τις κορυφές της διαδρομής. |

### PathGradientBrush(PointF[] points, int wrapMode) {#PathGradientBrush-com.aspose.drawing.PointF---int-}
```
public PathGradientBrush(PointF[] points, int wrapMode)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) με τα καθορισμένα σημεία και τη λειτουργία περιτύλιξης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.drawing/pointf) | Ένας πίνακας δομών [PointF](../../com.aspose.drawing/pointf) που αντιπροσωπεύει τα σημεία που σχηματίζουν τις κορυφές της διαδρομής. |
| wrapMode | int | Ένα `WrapMode`([.getWrapMode](../../null/\#getWrapMode)/[.setWrapMode(int)](../../null/\#setWrapMode-int-)) που καθορίζει πώς γεμίσματα που σχεδιάζονται με αυτό το [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) τοποθετούνται σε πλακίδια. |

### PathGradientBrush(Point[] points) {#PathGradientBrush-com.aspose.drawing.Point---}
```
public PathGradientBrush(Point[] points)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) με τα καθορισμένα σημεία.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| points | [Point\[\]](../../com.aspose.drawing/point) | Ένας πίνακας δομών [Point](../../com.aspose.drawing/point) που αντιπροσωπεύει τα σημεία που σχηματίζουν τις κορυφές της διαδρομής. |

### PathGradientBrush(Point[] points, int wrapMode) {#PathGradientBrush-com.aspose.drawing.Point---int-}
```
public PathGradientBrush(Point[] points, int wrapMode)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) με τα καθορισμένα σημεία και τη λειτουργία περιτύλιξης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| points | [Point\[\]](../../com.aspose.drawing/point) | Ένας πίνακας δομών [Point](../../com.aspose.drawing/point) που αντιπροσωπεύει τα σημεία που σχηματίζουν τις κορυφές της διαδρομής. |
| wrapMode | int | Ένα `WrapMode`([.getWrapMode](../../null/\#getWrapMode)/[.setWrapMode(int)](../../null/\#setWrapMode-int-)) που καθορίζει πώς γεμίσματα που σχεδιάζονται με αυτό το [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) τοποθετούνται σε πλακίδια. |

### PathGradientBrush(GraphicsPath path) {#PathGradientBrush-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public PathGradientBrush(GraphicsPath path)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) με το καθορισμένο μονοπάτι.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | Το [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) που ορίζει την περιοχή που γεμίζει αυτό το [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush). |

### getCenterColor() {#getCenterColor--}
```
public Color getCenterColor()
```


Λαμβάνει ή ορίζει το χρώμα στο κέντρο της διαβάθμισης διαδρομής.

**Returns:**
[Color](../../com.aspose.drawing/color)
### setCenterColor(Color value) {#setCenterColor-com.aspose.drawing.Color-}
```
public void setCenterColor(Color value)
```


Λαμβάνει ή ορίζει το χρώμα στο κέντρο της διαβάθμισης διαδρομής.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Color](../../com.aspose.drawing/color) |  |

### getSurroundColors() {#getSurroundColors--}
```
public Color[] getSurroundColors()
```


Λαμβάνει ή ορίζει έναν πίνακα χρωμάτων που αντιστοιχούν στα σημεία της διαδρομής που γεμίζει αυτό το [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush).

**Returns:**
com.aspose.drawing.Color[]
### setSurroundColors(Color[] value) {#setSurroundColors-com.aspose.drawing.Color---}
```
public void setSurroundColors(Color[] value)
```


Λαμβάνει ή ορίζει έναν πίνακα χρωμάτων που αντιστοιχούν στα σημεία της διαδρομής που γεμίζει αυτό το [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Color\[\]](../../com.aspose.drawing/color) |  |

### getCenterPoint() {#getCenterPoint--}
```
public PointF getCenterPoint()
```


Λαμβάνει ή ορίζει το κεντρικό σημείο της διαβάθμισης διαδρομής.

**Returns:**
[PointF](../../com.aspose.drawing/pointf)
### setCenterPoint(PointF value) {#setCenterPoint-com.aspose.drawing.PointF-}
```
public void setCenterPoint(PointF value)
```


Λαμβάνει ή ορίζει το κεντρικό σημείο της διαβάθμισης διαδρομής.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [PointF](../../com.aspose.drawing/pointf) |  |

### getRectangle() {#getRectangle--}
```
public RectangleF getRectangle()
```


Λαμβάνει ένα οριοθετημένο ορθογώνιο για αυτό το [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush).

**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef)
### getBlend() {#getBlend--}
```
public Blend getBlend()
```


Gets or sets a `Blend`([.getBlend](../../null/\#getBlend)/[.setBlend(Blend)](../../null/\#setBlend-Blend-)) that specifies positions and factors that define a custom falloff for the gradient.

**Returns:**
[Blend](../../com.aspose.drawing.drawing2d/blend)
### setBlend(Blend value) {#setBlend-com.aspose.drawing.drawing2d.Blend-}
```
public void setBlend(Blend value)
```


Gets or sets a `Blend`([.getBlend](../../null/\#getBlend)/[.setBlend(Blend)](../../null/\#setBlend-Blend-)) that specifies positions and factors that define a custom falloff for the gradient.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Blend](../../com.aspose.drawing.drawing2d/blend) |  |

### getInterpolationColors() {#getInterpolationColors--}
```
public ColorBlend getInterpolationColors()
```


Gets or sets a [ColorBlend](../../com.aspose.drawing.drawing2d/colorblend) that defines a multicolor linear gradient.

**Returns:**
[ColorBlend](../../com.aspose.drawing.drawing2d/colorblend)
### setInterpolationColors(ColorBlend value) {#setInterpolationColors-com.aspose.drawing.drawing2d.ColorBlend-}
```
public void setInterpolationColors(ColorBlend value)
```


Gets or sets a [ColorBlend](../../com.aspose.drawing.drawing2d/colorblend) that defines a multicolor linear gradient.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [ColorBlend](../../com.aspose.drawing.drawing2d/colorblend) |  |

### getTransform() {#getTransform--}
```
public Matrix getTransform()
```


Λαμβάνει ή ορίζει ένα αντίγραφο του [Matrix](../../com.aspose.drawing.drawing2d/matrix) που ορίζει έναν τοπικό γεωμετρικό μετασχηματισμό για αυτό το [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush).

**Returns:**
[Matrix](../../com.aspose.drawing.drawing2d/matrix)
### setTransform(Matrix value) {#setTransform-com.aspose.drawing.drawing2d.Matrix-}
```
public void setTransform(Matrix value)
```


Λαμβάνει ή ορίζει ένα αντίγραφο του [Matrix](../../com.aspose.drawing.drawing2d/matrix) που ορίζει έναν τοπικό γεωμετρικό μετασχηματισμό για αυτό το [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.drawing.drawing2d/matrix) |  |

### getFocusScales() {#getFocusScales--}
```
public PointF getFocusScales()
```


Λαμβάνει ή ορίζει το σημείο εστίασης για τη μείωση της διαβάθμισης.

**Returns:**
[PointF](../../com.aspose.drawing/pointf)
### setFocusScales(PointF value) {#setFocusScales-com.aspose.drawing.PointF-}
```
public void setFocusScales(PointF value)
```


Λαμβάνει ή ορίζει το σημείο εστίασης για τη μείωση της διαβάθμισης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [PointF](../../com.aspose.drawing/pointf) |  |

### getWrapMode() {#getWrapMode--}
```
public int getWrapMode()
```


Λαμβάνει ή ορίζει ένα `WrapMode`([.getWrapMode](../../null/\#getWrapMode)/[.setWrapMode(int)](../../null/\#setWrapMode-int-)) που υποδεικνύει τη λειτουργία περιτύλιξης για αυτό το [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush).

**Returns:**
int
### setWrapMode(int value) {#setWrapMode-int-}
```
public void setWrapMode(int value)
```


Λαμβάνει ή ορίζει ένα `WrapMode`([.getWrapMode](../../null/\#getWrapMode)/[.setWrapMode(int)](../../null/\#setWrapMode-int-)) που υποδεικνύει τη λειτουργία περιτύλιξης για αυτό το [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Δημιουργεί ένα ακριβές αντίγραφο αυτού του [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush).

**Returns:**
java.lang.Object - Το [PathGradientBrush](../../com.aspose.drawing.drawing2d/pathgradientbrush) που δημιουργεί αυτή η μέθοδος, μετατρεπόμενο σε αντικείμενο.
### setSigmaBellShape(float focus) {#setSigmaBellShape-float-}
```
public void setSigmaBellShape(float focus)
```


Δημιουργεί ένα πινέλο διαβάθμισης που αλλάζει χρώμα ξεκινώντας από το κέντρο της διαδρομής προς τα έξω μέχρι το όριο της διαδρομής. Η μετάβαση από ένα χρώμα σε άλλο βασίζεται σε καμπύλη σχήματος καμπάνας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| focus | float | Μια τιμή από 0 έως 1 που καθορίζει πού, κατά μήκος οποιασδήποτε ακτίνας από το κέντρο της διαδρομής μέχρι το όριό της, το κεντρικό χρώμα θα είναι στη μέγιστη ένταση του. Μια τιμή 1 (η προεπιλογή) τοποθετεί τη μέγιστη ένταση στο κέντρο της διαδρομής. |

### setSigmaBellShape(float focus, float scale) {#setSigmaBellShape-float-float-}
```
public void setSigmaBellShape(float focus, float scale)
```


Δημιουργεί ένα πινέλο διαβάθμισης που αλλάζει χρώμα ξεκινώντας από το κέντρο της διαδρομής προς τα έξω μέχρι το όριο της διαδρομής. Η μετάβαση από ένα χρώμα σε άλλο βασίζεται σε καμπύλη σχήματος καμπάνας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| focus | float | Μια τιμή από 0 έως 1 που καθορίζει πού, κατά μήκος οποιασδήποτε ακτίνας από το κέντρο της διαδρομής μέχρι το όριό της, το κεντρικό χρώμα θα είναι στη μέγιστη ένταση του. Μια τιμή 1 (η προεπιλογή) τοποθετεί τη μέγιστη ένταση στο κέντρο της διαδρομής. |
| κλίμακα | float | Μια τιμή από 0 έως 1 που καθορίζει τη μέγιστη ένταση του κεντρικού χρώματος που αναμιγνύεται με το χρώμα του ορίου. Μια τιμή 1 προκαλεί τη μέγιστη δυνατή ένταση του κεντρικού χρώματος και είναι η προεπιλεγμένη τιμή. |

### setBlendTriangularShape(float focus) {#setBlendTriangularShape-float-}
```
public void setBlendTriangularShape(float focus)
```


Δημιουργεί μια διαβάθμιση με κεντρικό χρώμα και γραμμική μείωση προς ένα περιβάλλον χρώμα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| focus | float | Μια τιμή από 0 έως 1 που καθορίζει πού, κατά μήκος οποιασδήποτε ακτίνας από το κέντρο της διαδρομής μέχρι το όριό της, το κεντρικό χρώμα θα είναι στη μέγιστη ένταση του. Μια τιμή 1 (η προεπιλογή) τοποθετεί τη μέγιστη ένταση στο κέντρο της διαδρομής. |

### setBlendTriangularShape(float focus, float scale) {#setBlendTriangularShape-float-float-}
```
public void setBlendTriangularShape(float focus, float scale)
```


Δημιουργεί μια διαβάθμιση με κεντρικό χρώμα και γραμμική εσώλεια προς κάθε γύρω χρώμα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| focus | float | Μια τιμή από 0 έως 1 που καθορίζει πού, κατά μήκος οποιασδήποτε ακτίνας από το κέντρο της διαδρομής μέχρι το όριό της, το κεντρικό χρώμα θα είναι στη μέγιστη ένταση του. Μια τιμή 1 (η προεπιλογή) τοποθετεί τη μέγιστη ένταση στο κέντρο της διαδρομής. |
| κλίμακα | float | Μια τιμή από 0 έως 1 που καθορίζει τη μέγιστη ένταση του κεντρικού χρώματος που αναμιγνύεται με το χρώμα του ορίου. Μια τιμή 1 προκαλεί τη μέγιστη δυνατή ένταση του κεντρικού χρώματος και είναι η προεπιλεγμένη τιμή. |

### resetTransform() {#resetTransform--}
```
public void resetTransform()
```


Επαναφέρει την ιδιότητα `PathGradientBrush.Transform` στην ταυτότητα.

### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-}
```
public void multiplyTransform(Matrix matrix)
```


Ενημερώνει τον πίνακα μετασχηματισμού του πινέλου με το γινόμενο του πίνακα μετασχηματισμού του πινέλου πολλαπλασιασμένο με έναν άλλο πίνακα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | Ο [Matrix](../../com.aspose.drawing.drawing2d/matrix) που θα πολλαπλασιαστεί με τον τρέχοντα πίνακα μετασχηματισμού του πινέλου. |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-int-}
```
public void multiplyTransform(Matrix matrix, int order)
```


Ενημερώνει τον πίνακα μετασχηματισμού του πινέλου με το γινόμενο του πίνακα μετασχηματισμού του πινέλου πολλαπλασιασμένο με έναν άλλο πίνακα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | Ο [Matrix](../../com.aspose.drawing.drawing2d/matrix) που θα πολλαπλασιαστεί με τον τρέχοντα πίνακα μετασχηματισμού του πινέλου. |
| order | int | Ένα [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder) που καθορίζει με ποια σειρά θα πολλαπλασιαστούν οι δύο μήτρες. |

### translateTransform(float dx, float dy) {#translateTransform-float-float-}
```
public void translateTransform(float dx, float dy)
```


Εφαρμόζει τη συγκεκριμένη μετάθεση στον τοπικό γεωμετρικό μετασχηματισμό. Αυτή η μέθοδος προσθέτει την μετάθεση στην αρχή του μετασχηματισμού.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| dx | float | Η τιμή της μετάφρασης στον άξονα x. |
| dy | float | Η τιμή της μετάφρασης στον άξονα y. |

### translateTransform(float dx, float dy, int order) {#translateTransform-float-float-int-}
```
public void translateTransform(float dx, float dy, int order)
```


Εφαρμόζει τη συγκεκριμένη μετάθεση στον τοπικό γεωμετρικό μετασχηματισμό με την καθορισμένη σειρά.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| dx | float | Η τιμή της μετάφρασης στον άξονα x. |
| dy | float | Η τιμή της μετάφρασης στον άξονα y. |
| order | int | Η σειρά (prepend ή append) με την οποία εφαρμόζεται η μετάφραση. |

### scaleTransform(float sx, float sy) {#scaleTransform-float-float-}
```
public void scaleTransform(float sx, float sy)
```


Κλιμακώνει τη τοπική γεωμετρική μεταμόρφωση κατά τα καθορισμένα ποσά. Αυτή η μέθοδος προσθέτει το πλέγμα κλιμάκωσης στην αρχή του μετασχηματισμού.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sx | float | Ο συντελεστής κλίμακας του μετασχηματισμού στην κατεύθυνση του άξονα x. |
| sy | float | Ο συντελεστής κλίμακας του μετασχηματισμού στην κατεύθυνση του άξονα y. |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public void scaleTransform(float sx, float sy, int order)
```


Scales the local geometric transform by the specified amounts in the specified order.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sx | float | Ο συντελεστής κλίμακας του μετασχηματισμού στην κατεύθυνση του άξονα x. |
| sy | float | Ο συντελεστής κλίμακας του μετασχηματισμού στην κατεύθυνση του άξονα y. |
| order | int | Ένα [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder) που καθορίζει αν θα προσαρτηθεί ή θα προστεθεί το πλέγμα κλιμάκωσης. |

### rotateTransform(float angle) {#rotateTransform-float-}
```
public void rotateTransform(float angle)
```


Περιστρέφει τη τοπική γεωμετρική μεταμόρφωση κατά το καθορισμένο ποσό. Αυτή η μέθοδος προσαρτά την περιστροφή στον μετασχηματισμό.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| γωνία | float | Η γωνία (έκταση) της περιστροφής. |

### rotateTransform(float angle, int order) {#rotateTransform-float-int-}
```
public void rotateTransform(float angle, int order)
```


Rotates the local geometric transform by the specified amount in the specified order.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| γωνία | float | Η γωνία (έκταση) της περιστροφής. |
| order | int | Ένα [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder) που καθορίζει αν θα προσαρτηθεί ή θα προστεθεί το πλέγμα περιστροφής. |

