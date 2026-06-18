---
title: LinearGradientBrush
second_title: Αναφορά API του Aspose.Drawing for Java
description: Περιλαμβάνει ένα  με γραμμική διαβάθμιση.
type: docs
weight: 31
url: /el/java/com.aspose.drawing.drawing2d/lineargradientbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.drawing.Brush](../../com.aspose.drawing/brush)
```
public final class LinearGradientBrush extends Brush
```

Περιλαμβάνει ένα [Brush](../../com.aspose.drawing/brush) με γραμμική διαβάθμιση. Αυτή η κλάση δεν μπορεί να κληρονομηθεί.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [LinearGradientBrush(PointF point1, PointF point2, Color color1, Color color2)](#LinearGradientBrush-com.aspose.drawing.PointF-com.aspose.drawing.PointF-com.aspose.drawing.Color-com.aspose.drawing.Color-) | Αρχικοποιεί μια νέα παρουσία της κλάσης [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) με τα καθορισμένα σημεία και χρώματα. |
| [LinearGradientBrush(Point point1, Point point2, Color color1, Color color2)](#LinearGradientBrush-com.aspose.drawing.Point-com.aspose.drawing.Point-com.aspose.drawing.Color-com.aspose.drawing.Color-) | Αρχικοποιεί μια νέα παρουσία της κλάσης [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) με τα καθορισμένα σημεία και χρώματα. |
| [LinearGradientBrush(RectangleF rect, Color color1, Color color2, int linearGradientMode)](#LinearGradientBrush-com.aspose.drawing.RectangleF-com.aspose.drawing.Color-com.aspose.drawing.Color-int-) | Αρχικοποιεί μια νέα παρουσία της κλάσης [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) βασισμένη σε ένα ορθογώνιο, αρχικά και τελικά χρώματα, και μια λειτουργία προσανατολισμού. |
| [LinearGradientBrush(Rectangle rect, Color color1, Color color2, int linearGradientMode)](#LinearGradientBrush-com.aspose.drawing.Rectangle-com.aspose.drawing.Color-com.aspose.drawing.Color-int-) | Αρχικοποιεί μια νέα παρουσία της κλάσης [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) βασισμένη σε ένα ορθογώνιο, αρχικά και τελικά χρώματα, και προσανατολισμό. |
| [LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle)](#LinearGradientBrush-com.aspose.drawing.RectangleF-com.aspose.drawing.Color-com.aspose.drawing.Color-float-) | Αρχικοποιεί μια νέα παρουσία της κλάσης [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) βασισμένη σε ένα ορθογώνιο, αρχικά και τελικά χρώματα, και γωνία προσανατολισμού. |
| [LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle, boolean isAngleScaleable)](#LinearGradientBrush-com.aspose.drawing.RectangleF-com.aspose.drawing.Color-com.aspose.drawing.Color-float-boolean-) | Αρχικοποιεί μια νέα παρουσία της κλάσης [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) βασισμένη σε ένα ορθογώνιο, αρχικά και τελικά χρώματα, και γωνία προσανατολισμού. |
| [LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle)](#LinearGradientBrush-com.aspose.drawing.Rectangle-com.aspose.drawing.Color-com.aspose.drawing.Color-float-) | Αρχικοποιεί μια νέα παρουσία της κλάσης [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) βασισμένη σε ένα ορθογώνιο, αρχικά και τελικά χρώματα, και γωνία προσανατολισμού. |
| [LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle, boolean isAngleScaleable)](#LinearGradientBrush-com.aspose.drawing.Rectangle-com.aspose.drawing.Color-com.aspose.drawing.Color-float-boolean-) | Αρχικοποιεί μια νέα παρουσία της κλάσης [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) βασισμένη σε ένα ορθογώνιο, αρχικά και τελικά χρώματα, και γωνία προσανατολισμού. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getLinearColors()](#getLinearColors--) | Λαμβάνει ή ορίζει τα αρχικά και τελικά χρώματα της διαβάθμισης. |
| [setLinearColors(Color[] value)](#setLinearColors-com.aspose.drawing.Color---) | Λαμβάνει ή ορίζει τα αρχικά και τελικά χρώματα της διαβάθμισης. |
| [getRectangle()](#getRectangle--) | Λαμβάνει μια ορθογώνια περιοχή που ορίζει τα αρχικά και τελικά σημεία της διαβάθμισης. |
| [getGammaCorrection()](#getGammaCorrection--) | Gets or sets a value indicating whether gamma correction is enabled for this [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush). |
| [setGammaCorrection(boolean value)](#setGammaCorrection-boolean-) | Gets or sets a value indicating whether gamma correction is enabled for this [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush). |
| [getBlend()](#getBlend--) | Gets or sets a `Blend`([.getBlend](../../null/\#getBlend)/[.setBlend(Blend)](../../null/\#setBlend-Blend-)) that specifies positions and factors that define a custom falloff for the gradient. |
| [setBlend(Blend value)](#setBlend-com.aspose.drawing.drawing2d.Blend-) | Gets or sets a `Blend`([.getBlend](../../null/\#getBlend)/[.setBlend(Blend)](../../null/\#setBlend-Blend-)) that specifies positions and factors that define a custom falloff for the gradient. |
| [getInterpolationColors()](#getInterpolationColors--) | Gets or sets a [ColorBlend](../../com.aspose.drawing.drawing2d/colorblend) that defines a multicolor linear gradient. |
| [setInterpolationColors(ColorBlend value)](#setInterpolationColors-com.aspose.drawing.drawing2d.ColorBlend-) | Gets or sets a [ColorBlend](../../com.aspose.drawing.drawing2d/colorblend) that defines a multicolor linear gradient. |
| [getWrapMode()](#getWrapMode--) | Gets or sets a `WrapMode` enumeration that indicates the wrap mode for this [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush). |
| [setWrapMode(int value)](#setWrapMode-int-) | Gets or sets a `WrapMode` enumeration that indicates the wrap mode for this [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush). |
| [getTransform()](#getTransform--) | Gets or sets a copy [Matrix](../../com.aspose.drawing.drawing2d/matrix) that defines a local geometric transform for this [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush). |
| [setTransform(Matrix value)](#setTransform-com.aspose.drawing.drawing2d.Matrix-) | Gets or sets a copy [Matrix](../../com.aspose.drawing.drawing2d/matrix) that defines a local geometric transform for this [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush). |
| [deepClone()](#deepClone--) | Creates an exact copy of this [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush). |
| [setSigmaBellShape(float focus)](#setSigmaBellShape-float-) | Creates a gradient falloff based on a bell-shaped curve. |
| [setSigmaBellShape(float focus, float scale)](#setSigmaBellShape-float-float-) | Creates a gradient falloff based on a bell-shaped curve. |
| [setBlendTriangularShape(float focus)](#setBlendTriangularShape-float-) | Creates a linear gradient with a center color and a linear falloff to a single color on both ends. |
| [setBlendTriangularShape(float focus, float scale)](#setBlendTriangularShape-float-float-) | Creates a linear gradient with a center color and a linear falloff to a single color on both ends. |
| [resetTransform()](#resetTransform--) | Resets the `LinearGradientBrush.Transform` property to identity. |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-) | Multiplies the [Matrix](../../com.aspose.drawing.drawing2d/matrix) that represents the local geometric transform of this [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) by the specified [Matrix](../../com.aspose.drawing.drawing2d/matrix) by prepending the specified [Matrix](../../com.aspose.drawing.drawing2d/matrix). |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-int-) | Multiplies the [Matrix](../../com.aspose.drawing.drawing2d/matrix) that represents the local geometric transform of this [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) by the specified [Matrix](../../com.aspose.drawing.drawing2d/matrix) in the specified order. |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | Translates the local geometric transform by the specified dimensions. |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | Translates the local geometric transform by the specified dimensions in the specified order. |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | Scales the local geometric transform by the specified amounts. |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | Scales the local geometric transform by the specified amounts in the specified order. |
| [rotateTransform(float angle)](#rotateTransform-float-) | Rotates the local geometric transform by the specified amount. |
| [rotateTransform(float angle, int order)](#rotateTransform-float-int-) | Rotates the local geometric transform by the specified amount in the specified order. |
### LinearGradientBrush(PointF point1, PointF point2, Color color1, Color color2) {#LinearGradientBrush-com.aspose.drawing.PointF-com.aspose.drawing.PointF-com.aspose.drawing.Color-com.aspose.drawing.Color-}
```
public LinearGradientBrush(PointF point1, PointF point2, Color color1, Color color2)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) με τα καθορισμένα σημεία και χρώματα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| point1 | [PointF](../../com.aspose.drawing/pointf) | A [PointF](../../com.aspose.drawing/pointf) structure that represents the starting point of the linear gradient. |
| point2 | [PointF](../../com.aspose.drawing/pointf) | A [PointF](../../com.aspose.drawing/pointf) structure that represents the endpoint of the linear gradient. |
| color1 | [Color](../../com.aspose.drawing/color) | A [Color](../../com.aspose.drawing/color) structure that represents the starting color of the linear gradient. |
| color2 | [Color](../../com.aspose.drawing/color) | A [Color](../../com.aspose.drawing/color) structure that represents the ending color of the linear gradient. |

### LinearGradientBrush(Point point1, Point point2, Color color1, Color color2) {#LinearGradientBrush-com.aspose.drawing.Point-com.aspose.drawing.Point-com.aspose.drawing.Color-com.aspose.drawing.Color-}
```
public LinearGradientBrush(Point point1, Point point2, Color color1, Color color2)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) με τα καθορισμένα σημεία και χρώματα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.drawing/point) | A [Point](../../com.aspose.drawing/point) structure that represents the starting point of the linear gradient. |
| point2 | [Point](../../com.aspose.drawing/point) | A [Point](../../com.aspose.drawing/point) structure that represents the endpoint of the linear gradient. |
| color1 | [Color](../../com.aspose.drawing/color) | A [Color](../../com.aspose.drawing/color) structure that represents the starting color of the linear gradient. |
| color2 | [Color](../../com.aspose.drawing/color) | A [Color](../../com.aspose.drawing/color) structure that represents the ending color of the linear gradient. |

### LinearGradientBrush(RectangleF rect, Color color1, Color color2, int linearGradientMode) {#LinearGradientBrush-com.aspose.drawing.RectangleF-com.aspose.drawing.Color-com.aspose.drawing.Color-int-}
```
public LinearGradientBrush(RectangleF rect, Color color1, Color color2, int linearGradientMode)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) βασισμένη σε ένα ορθογώνιο, αρχικά και τελικά χρώματα, και μια λειτουργία προσανατολισμού.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | A [RectangleF](../../com.aspose.drawing/rectanglef) structure that specifies the bounds of the linear gradient. |
| color1 | [Color](../../com.aspose.drawing/color) | A [Color](../../com.aspose.drawing/color) structure that represents the starting color for the gradient. |
| color2 | [Color](../../com.aspose.drawing/color) | Μια δομή [Color](../../com.aspose.drawing/color) που αντιπροσωπεύει το τελικό χρώμα για τη διαβάθμιση. |
| linearGradientMode | int | Ένα στοιχείο απαρίθμησης [LinearGradientMode](../../com.aspose.drawing.drawing2d/lineargradientmode) που καθορίζει τον προσανατολισμό της διαβάθμισης. Ο προσανατολισμός καθορίζει τα αρχικά και τελικά σημεία της διαβάθμισης. Για παράδειγμα, το LinearGradientMode.ForwardDiagonal καθορίζει ότι το αρχικό σημείο είναι η πάνω αριστερή γωνία του ορθογωνίου και το τελικό σημείο είναι η κάτω δεξιά γωνία του ορθογωνίου. |

### LinearGradientBrush(Rectangle rect, Color color1, Color color2, int linearGradientMode) {#LinearGradientBrush-com.aspose.drawing.Rectangle-com.aspose.drawing.Color-com.aspose.drawing.Color-int-}
```
public LinearGradientBrush(Rectangle rect, Color color1, Color color2, int linearGradientMode)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) βασισμένη σε ένα ορθογώνιο, αρχικά και τελικά χρώματα, και προσανατολισμό.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | Μια δομή `Rectangle`([.getRectangle](../../null/\#getRectangle)) που καθορίζει τα όρια της γραμμικής διαβάθμισης. |
| color1 | [Color](../../com.aspose.drawing/color) | A [Color](../../com.aspose.drawing/color) structure that represents the starting color for the gradient. |
| color2 | [Color](../../com.aspose.drawing/color) | Μια δομή [Color](../../com.aspose.drawing/color) που αντιπροσωπεύει το τελικό χρώμα για τη διαβάθμιση. |
| linearGradientMode | int | Ένα στοιχείο απαρίθμησης [LinearGradientMode](../../com.aspose.drawing.drawing2d/lineargradientmode) που καθορίζει τον προσανατολισμό της διαβάθμισης. Ο προσανατολισμός καθορίζει τα αρχικά και τελικά σημεία της διαβάθμισης. Για παράδειγμα, το LinearGradientMode.ForwardDiagonal καθορίζει ότι το αρχικό σημείο είναι η πάνω αριστερή γωνία του ορθογωνίου και το τελικό σημείο είναι η κάτω δεξιά γωνία του ορθογωνίου. |

### LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle) {#LinearGradientBrush-com.aspose.drawing.RectangleF-com.aspose.drawing.Color-com.aspose.drawing.Color-float-}
```
public LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) βασισμένη σε ένα ορθογώνιο, αρχικά και τελικά χρώματα, και γωνία προσανατολισμού.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | A [RectangleF](../../com.aspose.drawing/rectanglef) structure that specifies the bounds of the linear gradient. |
| color1 | [Color](../../com.aspose.drawing/color) | A [Color](../../com.aspose.drawing/color) structure that represents the starting color for the gradient. |
| color2 | [Color](../../com.aspose.drawing/color) | Μια δομή [Color](../../com.aspose.drawing/color) που αντιπροσωπεύει το τελικό χρώμα για τη διαβάθμιση. |
| γωνία | float | Η γωνία, μετρημένη σε μοίρες δεξιόστροφα από τον άξονα x, της γραμμής προσανατολισμού της διαβάθμισης. |

### LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle, boolean isAngleScaleable) {#LinearGradientBrush-com.aspose.drawing.RectangleF-com.aspose.drawing.Color-com.aspose.drawing.Color-float-boolean-}
```
public LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle, boolean isAngleScaleable)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) βασισμένη σε ένα ορθογώνιο, αρχικά και τελικά χρώματα, και γωνία προσανατολισμού.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | A [RectangleF](../../com.aspose.drawing/rectanglef) structure that specifies the bounds of the linear gradient. |
| color1 | [Color](../../com.aspose.drawing/color) | A [Color](../../com.aspose.drawing/color) structure that represents the starting color for the gradient. |
| color2 | [Color](../../com.aspose.drawing/color) | Μια δομή [Color](../../com.aspose.drawing/color) που αντιπροσωπεύει το τελικό χρώμα για τη διαβάθμιση. |
| γωνία | float | Η γωνία, μετρημένη σε μοίρες δεξιόστροφα από τον άξονα x, της γραμμής προσανατολισμού της διαβάθμισης. |
| isAngleScaleable | boolean | Ορίστε σε true για να καθορίσετε ότι η γωνία επηρεάζεται από τον μετασχηματισμό που σχετίζεται με αυτό το [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush); διαφορετικά, false. |

### LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle) {#LinearGradientBrush-com.aspose.drawing.Rectangle-com.aspose.drawing.Color-com.aspose.drawing.Color-float-}
```
public LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) βασισμένη σε ένα ορθογώνιο, αρχικά και τελικά χρώματα, και γωνία προσανατολισμού.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | Μια δομή `Rectangle`([.getRectangle](../../null/\#getRectangle)) που καθορίζει τα όρια της γραμμικής διαβάθμισης. |
| color1 | [Color](../../com.aspose.drawing/color) | A [Color](../../com.aspose.drawing/color) structure that represents the starting color for the gradient. |
| color2 | [Color](../../com.aspose.drawing/color) | Μια δομή [Color](../../com.aspose.drawing/color) που αντιπροσωπεύει το τελικό χρώμα για τη διαβάθμιση. |
| γωνία | float | Η γωνία, μετρημένη σε μοίρες δεξιόστροφα από τον άξονα x, της γραμμής προσανατολισμού της διαβάθμισης. |

### LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle, boolean isAngleScaleable) {#LinearGradientBrush-com.aspose.drawing.Rectangle-com.aspose.drawing.Color-com.aspose.drawing.Color-float-boolean-}
```
public LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle, boolean isAngleScaleable)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) βασισμένη σε ένα ορθογώνιο, αρχικά και τελικά χρώματα, και γωνία προσανατολισμού.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | Μια δομή `Rectangle`([.getRectangle](../../null/\#getRectangle)) που καθορίζει τα όρια της γραμμικής διαβάθμισης. |
| color1 | [Color](../../com.aspose.drawing/color) | A [Color](../../com.aspose.drawing/color) structure that represents the starting color for the gradient. |
| color2 | [Color](../../com.aspose.drawing/color) | Μια δομή [Color](../../com.aspose.drawing/color) που αντιπροσωπεύει το τελικό χρώμα για τη διαβάθμιση. |
| γωνία | float | Η γωνία, μετρημένη σε μοίρες δεξιόστροφα από τον άξονα x, της γραμμής προσανατολισμού της διαβάθμισης. |
| isAngleScaleable | boolean | Ορίστε σε true για να καθορίσετε ότι η γωνία επηρεάζεται από τον μετασχηματισμό που σχετίζεται με αυτό το [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush); διαφορετικά, false. |

### getLinearColors() {#getLinearColors--}
```
public Color[] getLinearColors()
```


Λαμβάνει ή ορίζει τα αρχικά και τελικά χρώματα της διαβάθμισης.

**Returns:**
com.aspose.drawing.Color[]
### setLinearColors(Color[] value) {#setLinearColors-com.aspose.drawing.Color---}
```
public void setLinearColors(Color[] value)
```


Λαμβάνει ή ορίζει τα αρχικά και τελικά χρώματα της διαβάθμισης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Color\[\]](../../com.aspose.drawing/color) |  |

### getRectangle() {#getRectangle--}
```
public RectangleF getRectangle()
```


Λαμβάνει μια ορθογώνια περιοχή που ορίζει τα αρχικά και τελικά σημεία της διαβάθμισης.

**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef)
### getGammaCorrection() {#getGammaCorrection--}
```
public boolean getGammaCorrection()
```


Gets or sets a value indicating whether gamma correction is enabled for this [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush).

**Returns:**
boolean
### setGammaCorrection(boolean value) {#setGammaCorrection-boolean-}
```
public void setGammaCorrection(boolean value)
```


Gets or sets a value indicating whether gamma correction is enabled for this [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

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

### getWrapMode() {#getWrapMode--}
```
public int getWrapMode()
```


Gets or sets a `WrapMode` enumeration that indicates the wrap mode for this [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush).

**Returns:**
int
### setWrapMode(int value) {#setWrapMode-int-}
```
public void setWrapMode(int value)
```


Gets or sets a `WrapMode` enumeration that indicates the wrap mode for this [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getTransform() {#getTransform--}
```
public Matrix getTransform()
```


Gets or sets a copy [Matrix](../../com.aspose.drawing.drawing2d/matrix) that defines a local geometric transform for this [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush).

**Returns:**
[Matrix](../../com.aspose.drawing.drawing2d/matrix)
### setTransform(Matrix value) {#setTransform-com.aspose.drawing.drawing2d.Matrix-}
```
public void setTransform(Matrix value)
```


Gets or sets a copy [Matrix](../../com.aspose.drawing.drawing2d/matrix) that defines a local geometric transform for this [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.drawing.drawing2d/matrix) |  |

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Creates an exact copy of this [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush).

**Returns:**
java.lang.Object - Το [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) που δημιουργεί αυτή η μέθοδος, μετατρεπόμενο σε αντικείμενο.
### setSigmaBellShape(float focus) {#setSigmaBellShape-float-}
```
public void setSigmaBellShape(float focus)
```


Creates a gradient falloff based on a bell-shaped curve.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| focus | float | Μια τιμή από 0 έως 1 που καθορίζει το κέντρο της διαβάθμισης (το σημείο όπου το αρχικό χρώμα και το τελικό χρώμα αναμειγνύονται εξίσου). |

### setSigmaBellShape(float focus, float scale) {#setSigmaBellShape-float-float-}
```
public void setSigmaBellShape(float focus, float scale)
```


Creates a gradient falloff based on a bell-shaped curve.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| focus | float | Μια τιμή από 0 έως 1 που καθορίζει το κέντρο της διαβάθμισης (το σημείο όπου η διαβάθμιση αποτελείται μόνο από το τελικό χρώμα). |
| κλίμακα | float | Μια τιμή από 0 έως 1 που καθορίζει πόσο γρήγορα μειώνονται τα χρώματα από το `focus`. |

### setBlendTriangularShape(float focus) {#setBlendTriangularShape-float-}
```
public void setBlendTriangularShape(float focus)
```


Creates a linear gradient with a center color and a linear falloff to a single color on both ends.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| focus | float | Μια τιμή από 0 έως 1 που καθορίζει το κέντρο της διαβάθμισης (το σημείο όπου η διαβάθμιση αποτελείται μόνο από το τελικό χρώμα). |

### setBlendTriangularShape(float focus, float scale) {#setBlendTriangularShape-float-float-}
```
public void setBlendTriangularShape(float focus, float scale)
```


Creates a linear gradient with a center color and a linear falloff to a single color on both ends.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| focus | float | Μια τιμή από 0 έως 1 που καθορίζει το κέντρο της διαβάθμισης (το σημείο όπου η διαβάθμιση αποτελείται μόνο από το τελικό χρώμα). |
| κλίμακα | float | Μια τιμή από 0 έως 1 που καθορίζει πόσο γρήγορα μειώνονται τα χρώματα από το αρχικό χρώμα προς το `focus` (τελικό χρώμα). |

### resetTransform() {#resetTransform--}
```
public void resetTransform()
```


Resets the `LinearGradientBrush.Transform` property to identity.

### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-}
```
public void multiplyTransform(Matrix matrix)
```


Multiplies the [Matrix](../../com.aspose.drawing.drawing2d/matrix) that represents the local geometric transform of this [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) by the specified [Matrix](../../com.aspose.drawing.drawing2d/matrix) by prepending the specified [Matrix](../../com.aspose.drawing.drawing2d/matrix).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | Η [Matrix](../../com.aspose.drawing.drawing2d/matrix) με την οποία θα πολλαπλασιαστεί ο γεωμετρικός μετασχηματισμός. |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.drawing.drawing2d.Matrix-int-}
```
public void multiplyTransform(Matrix matrix, int order)
```


Multiplies the [Matrix](../../com.aspose.drawing.drawing2d/matrix) that represents the local geometric transform of this [LinearGradientBrush](../../com.aspose.drawing.drawing2d/lineargradientbrush) by the specified [Matrix](../../com.aspose.drawing.drawing2d/matrix) in the specified order.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | Η [Matrix](../../com.aspose.drawing.drawing2d/matrix) με την οποία θα πολλαπλασιαστεί ο γεωμετρικός μετασχηματισμός. |
| order | int | Ένα [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder) που καθορίζει με ποια σειρά θα πολλαπλασιαστούν οι δύο μήτρες. |

### translateTransform(float dx, float dy) {#translateTransform-float-float-}
```
public void translateTransform(float dx, float dy)
```


Μεταφράζει τον τοπικό γεωμετρικό μετασχηματισμό κατά τις καθορισμένες διαστάσεις. Αυτή η μέθοδος προσθέτει την μετάφραση στην αρχή του μετασχηματισμού.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| dx | float | Η τιμή της μετάφρασης στον άξονα x. |
| dy | float | Η τιμή της μετάφρασης στον άξονα y. |

### translateTransform(float dx, float dy, int order) {#translateTransform-float-float-int-}
```
public void translateTransform(float dx, float dy, int order)
```


Translates the local geometric transform by the specified dimensions in the specified order.

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
| sx | float | Το ποσό κατά το οποίο κλιμακώνεται ο μετασχηματισμός στην κατεύθυνση του άξονα x. |
| sy | float | Το ποσό κατά το οποίο κλιμακώνεται ο μετασχηματισμός στην κατεύθυνση του άξονα y. |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public void scaleTransform(float sx, float sy, int order)
```


Scales the local geometric transform by the specified amounts in the specified order.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sx | float | Το ποσό κατά το οποίο κλιμακώνεται ο μετασχηματισμός στην κατεύθυνση του άξονα x. |
| sy | float | Το ποσό κατά το οποίο κλιμακώνεται ο μετασχηματισμός στην κατεύθυνση του άξονα y. |
| order | int | Ένα [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder) που καθορίζει αν θα προσαρτηθεί ή θα προστεθεί το πλέγμα κλιμάκωσης. |

### rotateTransform(float angle) {#rotateTransform-float-}
```
public void rotateTransform(float angle)
```


Περιστρέφει τη τοπική γεωμετρική μεταμόρφωση κατά το καθορισμένο ποσό. Αυτή η μέθοδος προσαρτά την περιστροφή στον μετασχηματισμό.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| γωνία | float | Η γωνία της περιστροφής. |

### rotateTransform(float angle, int order) {#rotateTransform-float-int-}
```
public void rotateTransform(float angle, int order)
```


Rotates the local geometric transform by the specified amount in the specified order.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| γωνία | float | Η γωνία της περιστροφής. |
| order | int | Ένα [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder) που καθορίζει αν θα προσαρτηθεί ή θα προστεθεί το πλέγμα περιστροφής. |

