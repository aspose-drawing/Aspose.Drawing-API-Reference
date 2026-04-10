---
title: Region
second_title: Αναφορά API του Aspose.Drawing for Java
description: Describes the interior of a graphics shape composed of rectangles and paths.
type: docs
weight: 40
url: /el/java/com.aspose.drawing/region/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public final class Region implements System.IDisposable
```

Περιγράφει το εσωτερικό ενός γραφικού σχήματος που αποτελείται από ορθογώνια και διαδρομές. Αυτή η κλάση δεν μπορεί να κληρονομηθεί.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [Region()](#Region--) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [Region](../../com.aspose.drawing/region). |
| [Region(RectangleF rect)](#Region-com.aspose.drawing.RectangleF-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [Region](../../com.aspose.drawing/region) από τη συγκεκριμένη δομή [RectangleF](../../com.aspose.drawing/rectanglef). |
| [Region(Rectangle rect)](#Region-com.aspose.drawing.Rectangle-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [Region](../../com.aspose.drawing/region) από τη συγκεκριμένη δομή [Rectangle](../../com.aspose.drawing/rectangle). |
| [Region(GraphicsPath path)](#Region-com.aspose.drawing.drawing2d.GraphicsPath-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [Region](../../com.aspose.drawing/region) με το καθορισμένο [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath). |
| [Region(RegionData rgnData)](#Region-com.aspose.drawing.drawing2d.RegionData-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [Region](../../com.aspose.drawing/region) από τα καθορισμένα δεδομένα. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [dispose()](#dispose--) | Απελευθερώνει όλους τους πόρους που χρησιμοποιούνται από αυτό το [Region](../../com.aspose.drawing/region). |
| [equals(Region region, Graphics g)](#equals-com.aspose.drawing.Region-com.aspose.drawing.Graphics-) | Δοκιμάζει εάν το καθορισμένο [Region](../../com.aspose.drawing/region) είναι ταυτόσημο με αυτό το [Region](../../com.aspose.drawing/region) στην καθορισμένη επιφάνεια σχεδίασης. |
| [deepClone()](#deepClone--) | Δημιουργεί ένα ακριβές αντίγραφο αυτού του [Region](../../com.aspose.drawing/region). |
| [makeInfinite()](#makeInfinite--) | Αρχικοποιεί αυτό το αντικείμενο [Region](../../com.aspose.drawing/region) σε ένα άπειρο εσωτερικό. |
| [makeEmpty()](#makeEmpty--) | Αρχικοποιεί αυτό το [Region](../../com.aspose.drawing/region) σε ένα κενό εσωτερικό. |
| [intersect(RectangleF rect)](#intersect-com.aspose.drawing.RectangleF-) | Ενημερώνει αυτό το [Region](../../com.aspose.drawing/region) στην τομή του με τη καθορισμένη δομή [RectangleF](../../com.aspose.drawing/rectanglef). |
| [intersect(Rectangle rect)](#intersect-com.aspose.drawing.Rectangle-) | Ενημερώνει αυτό το [Region](../../com.aspose.drawing/region) στην τομή του με τη καθορισμένη δομή [Rectangle](../../com.aspose.drawing/rectangle). |
| [intersect(GraphicsPath path)](#intersect-com.aspose.drawing.drawing2d.GraphicsPath-) | Ενημερώνει αυτό το [Region](../../com.aspose.drawing/region) στην τομή του με το καθορισμένο [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath). |
| [intersect(Region region)](#intersect-com.aspose.drawing.Region-) | Ενημερώνει αυτό το [Region](../../com.aspose.drawing/region) στην τομή του με το καθορισμένο [Region](../../com.aspose.drawing/region). |
| [union(RectangleF rect)](#union-com.aspose.drawing.RectangleF-) | Ενημερώνει αυτό το [Region](../../com.aspose.drawing/region) στην ένωση του με τη καθορισμένη δομή [RectangleF](../../com.aspose.drawing/rectanglef). |
| [union(Rectangle rect)](#union-com.aspose.drawing.Rectangle-) | Ενημερώνει αυτό το [Region](../../com.aspose.drawing/region) στην ένωση του με τη καθορισμένη δομή [Rectangle](../../com.aspose.drawing/rectangle). |
| [union(GraphicsPath path)](#union-com.aspose.drawing.drawing2d.GraphicsPath-) | Ενημερώνει αυτό το [Region](../../com.aspose.drawing/region) στην ένωση του με το καθορισμένο [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath). |
| [union(Region region)](#union-com.aspose.drawing.Region-) | Ενημερώνει αυτό το [Region](../../com.aspose.drawing/region) στην ένωση του με το καθορισμένο [Region](../../com.aspose.drawing/region). |
| [getRegionData()](#getRegionData--) | Επιστρέφει ένα [RegionData](../../com.aspose.drawing.drawing2d/regiondata) που αντιπροσωπεύει τις πληροφορίες που περιγράφουν αυτό το [Region](../../com.aspose.drawing/region). |
| [xor(RectangleF rect)](#xor-com.aspose.drawing.RectangleF-) | Ενημερώνει αυτό το [Region](../../com.aspose.drawing/region) στην ένωση με αφαίρεση της τομής του με τη καθορισμένη δομή [RectangleF](../../com.aspose.drawing/rectanglef). |
| [xor(Rectangle rect)](#xor-com.aspose.drawing.Rectangle-) | Ενημερώνει αυτό το [Region](../../com.aspose.drawing/region) στην ένωση με αφαίρεση της τομής του με τη καθορισμένη δομή [Rectangle](../../com.aspose.drawing/rectangle). |
| [xor(GraphicsPath path)](#xor-com.aspose.drawing.drawing2d.GraphicsPath-) | Ενημερώνει αυτό το [Region](../../com.aspose.drawing/region) στην ένωση με αφαίρεση της τομής του με το καθορισμένο [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath). |
| [xor(Region region)](#xor-com.aspose.drawing.Region-) | Ενημερώνει αυτό το [Region](../../com.aspose.drawing/region) στην ένωση με αφαίρεση της τομής του με το καθορισμένο [Region](../../com.aspose.drawing/region). |
| [exclude(RectangleF rect)](#exclude-com.aspose.drawing.RectangleF-) | Ενημερώνει αυτό το [Region](../../com.aspose.drawing/region) ώστε να περιέχει μόνο το τμήμα του εσωτερικού του που δεν τέμνει τη καθορισμένη δομή [RectangleF](../../com.aspose.drawing/rectanglef). |
| [exclude(Rectangle rect)](#exclude-com.aspose.drawing.Rectangle-) | Ενημερώνει αυτό το [Region](../../com.aspose.drawing/region) ώστε να περιέχει μόνο το τμήμα του εσωτερικού του που δεν τέμνει τη καθορισμένη δομή [Rectangle](../../com.aspose.drawing/rectangle). |
| [exclude(GraphicsPath path)](#exclude-com.aspose.drawing.drawing2d.GraphicsPath-) | Ενημερώνει αυτό το [Region](../../com.aspose.drawing/region) ώστε να περιέχει μόνο το τμήμα του εσωτερικού του που δεν τέμνει το καθορισμένο [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath). |
| [exclude(Region region)](#exclude-com.aspose.drawing.Region-) | Ενημερώνει αυτό το [Region](../../com.aspose.drawing/region) ώστε να περιέχει μόνο το τμήμα του εσωτερικού του που δεν τέμνει το καθορισμένο [Region](../../com.aspose.drawing/region). |
| [complement(RectangleF rect)](#complement-com.aspose.drawing.RectangleF-) | Ενημερώνει αυτό το [Region](../../com.aspose.drawing/region) ώστε να περιέχει το τμήμα της καθορισμένης δομής [RectangleF](../../com.aspose.drawing/rectanglef) που δεν τέμνει αυτό το [Region](../../com.aspose.drawing/region). |
| [complement(Rectangle rect)](#complement-com.aspose.drawing.Rectangle-) | Ενημερώνει αυτό το [Region](../../com.aspose.drawing/region) ώστε να περιέχει το τμήμα της καθορισμένης δομής [Rectangle](../../com.aspose.drawing/rectangle) που δεν τέμνει αυτό το [Region](../../com.aspose.drawing/region). |
| [complement(GraphicsPath path)](#complement-com.aspose.drawing.drawing2d.GraphicsPath-) | Ενημερώνει αυτό το [Region](../../com.aspose.drawing/region) ώστε να περιέχει το τμήμα του καθορισμένου [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) που δεν τέμνει αυτό το [Region](../../com.aspose.drawing/region). |
| [complement(Region region)](#complement-com.aspose.drawing.Region-) | Updates this [Region](../../com.aspose.drawing/region) to contain the portion of the specified [Region](../../com.aspose.drawing/region) that does not intersect with this [Region](../../com.aspose.drawing/region). |
| [translate(float dx, float dy)](#translate-float-float-) | Offsets the coordinates of this [Region](../../com.aspose.drawing/region) by the specified amount. |
| [translate(int dx, int dy)](#translate-int-int-) | Offsets the coordinates of this [Region](../../com.aspose.drawing/region) by the specified amount. |
| [transform(Matrix matrix)](#transform-com.aspose.drawing.drawing2d.Matrix-) | Transforms this [Region](../../com.aspose.drawing/region) by the specified [Matrix](../../com.aspose.drawing.drawing2d/matrix). |
| [getBounds(Graphics g)](#getBounds-com.aspose.drawing.Graphics-) | Gets a [RectangleF](../../com.aspose.drawing/rectanglef) structure that represents a rectangle that bounds this [Region](../../com.aspose.drawing/region) on the drawing surface of a [Graphics](../../com.aspose.drawing/graphics) object. |
| [getRegionScans(Matrix matrix)](#getRegionScans-com.aspose.drawing.drawing2d.Matrix-) | Returns an array of [RectangleF](../../com.aspose.drawing/rectanglef) structures that approximate this [Region](../../com.aspose.drawing/region) after the specified matrix transformation is applied. |
| [isEmpty(Graphics g)](#isEmpty-com.aspose.drawing.Graphics-) | Tests whether this [Region](../../com.aspose.drawing/region) has an empty interior on the specified drawing surface. |
| [isInfinite(Graphics g)](#isInfinite-com.aspose.drawing.Graphics-) | Tests whether this [Region](../../com.aspose.drawing/region) has an infinite interior on the specified drawing surface. |
| [isVisible(float x, float y)](#isVisible-float-float-) | Tests whether the specified point is contained within this [Region](../../com.aspose.drawing/region). |
| [isVisible(PointF point)](#isVisible-com.aspose.drawing.PointF-) | Tests whether the specified [PointF](../../com.aspose.drawing/pointf) structure is contained within this [Region](../../com.aspose.drawing/region). |
| [isVisible(float x, float y, Graphics g)](#isVisible-float-float-com.aspose.drawing.Graphics-) | Tests whether the specified point is contained within this [Region](../../com.aspose.drawing/region) when drawn using the specified [Graphics](../../com.aspose.drawing/graphics). |
| [isVisible(PointF point, Graphics g)](#isVisible-com.aspose.drawing.PointF-com.aspose.drawing.Graphics-) | Tests whether the specified [PointF](../../com.aspose.drawing/pointf) structure is contained within this [Region](../../com.aspose.drawing/region) when drawn using the specified [Graphics](../../com.aspose.drawing/graphics). |
| [isVisible(float x, float y, float width, float height)](#isVisible-float-float-float-float-) | Tests whether any portion of the specified rectangle is contained within this [Region](../../com.aspose.drawing/region). |
| [isVisible(RectangleF rect)](#isVisible-com.aspose.drawing.RectangleF-) | Tests whether any portion of the specified [RectangleF](../../com.aspose.drawing/rectanglef) structure is contained within this [Region](../../com.aspose.drawing/region). |
| [isVisible(float x, float y, float width, float height, Graphics g)](#isVisible-float-float-float-float-com.aspose.drawing.Graphics-) | Tests whether any portion of the specified rectangle is contained within this [Region](../../com.aspose.drawing/region) when drawn using the specified [Graphics](../../com.aspose.drawing/graphics). |
| [isVisible(RectangleF rect, Graphics g)](#isVisible-com.aspose.drawing.RectangleF-com.aspose.drawing.Graphics-) | Tests whether any portion of the specified [RectangleF](../../com.aspose.drawing/rectanglef) structure is contained within this [Region](../../com.aspose.drawing/region) when drawn using the specified [Graphics](../../com.aspose.drawing/graphics). |
| [isVisible(int x, int y, Graphics g)](#isVisible-int-int-com.aspose.drawing.Graphics-) | Tests whether the specified point is contained within this [Region](../../com.aspose.drawing/region) object when drawn using the specified [Graphics](../../com.aspose.drawing/graphics) object. |
| [isVisible(Point point)](#isVisible-com.aspose.drawing.Point-) | Tests whether the specified [Point](../../com.aspose.drawing/point) structure is contained within this [Region](../../com.aspose.drawing/region). |
| [isVisible(Point point, Graphics g)](#isVisible-com.aspose.drawing.Point-com.aspose.drawing.Graphics-) | Tests whether the specified [Point](../../com.aspose.drawing/point) structure is contained within this [Region](../../com.aspose.drawing/region) when drawn using the specified [Graphics](../../com.aspose.drawing/graphics). |
| [isVisible(int x, int y, int width, int height)](#isVisible-int-int-int-int-) | Tests whether any portion of the specified rectangle is contained within this [Region](../../com.aspose.drawing/region). |
| [isVisible(Rectangle rect)](#isVisible-com.aspose.drawing.Rectangle-) | Tests whether any portion of the specified [Rectangle](../../com.aspose.drawing/rectangle) structure is contained within this [Region](../../com.aspose.drawing/region). |
| [isVisible(int x, int y, int width, int height, Graphics g)](#isVisible-int-int-int-int-com.aspose.drawing.Graphics-) | Tests whether any portion of the specified rectangle is contained within this [Region](../../com.aspose.drawing/region) when drawn using the specified [Graphics](../../com.aspose.drawing/graphics). |
| [isVisible(Rectangle rect, Graphics g)](#isVisible-com.aspose.drawing.Rectangle-com.aspose.drawing.Graphics-) | Tests whether any portion of the specified [Rectangle](../../com.aspose.drawing/rectangle) structure is contained within this [Region](../../com.aspose.drawing/region) when drawn using the specified [Graphics](../../com.aspose.drawing/graphics). |
### Region() {#Region--}
```
public Region()
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [Region](../../com.aspose.drawing/region).

### Region(RectangleF rect) {#Region-com.aspose.drawing.RectangleF-}
```
public Region(RectangleF rect)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [Region](../../com.aspose.drawing/region) από τη συγκεκριμένη δομή [RectangleF](../../com.aspose.drawing/rectanglef).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | A [RectangleF](../../com.aspose.drawing/rectanglef) structure that defines the interior of the new [Region](../../com.aspose.drawing/region). |

### Region(Rectangle rect) {#Region-com.aspose.drawing.Rectangle-}
```
public Region(Rectangle rect)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [Region](../../com.aspose.drawing/region) από τη συγκεκριμένη δομή [Rectangle](../../com.aspose.drawing/rectangle).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | A [Rectangle](../../com.aspose.drawing/rectangle) structure that defines the interior of the new [Region](../../com.aspose.drawing/region). |

### Region(GraphicsPath path) {#Region-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public Region(GraphicsPath path)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [Region](../../com.aspose.drawing/region) με το καθορισμένο [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | A [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) that defines the new [Region](../../com.aspose.drawing/region). |

### Region(RegionData rgnData) {#Region-com.aspose.drawing.drawing2d.RegionData-}
```
public Region(RegionData rgnData)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [Region](../../com.aspose.drawing/region) από τα καθορισμένα δεδομένα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rgnData | [RegionData](../../com.aspose.drawing.drawing2d/regiondata) | A [RegionData](../../com.aspose.drawing.drawing2d/regiondata) that defines the interior of the new [Region](../../com.aspose.drawing/region). |

### dispose() {#dispose--}
```
public void dispose()
```


Απελευθερώνει όλους τους πόρους που χρησιμοποιούνται από αυτό το [Region](../../com.aspose.drawing/region).

### equals(Region region, Graphics g) {#equals-com.aspose.drawing.Region-com.aspose.drawing.Graphics-}
```
public boolean equals(Region region, Graphics g)
```


Δοκιμάζει εάν το καθορισμένο [Region](../../com.aspose.drawing/region) είναι ταυτόσημο με αυτό το [Region](../../com.aspose.drawing/region) στην καθορισμένη επιφάνεια σχεδίασης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| region | [Region](../../com.aspose.drawing/region) | The [Region](../../com.aspose.drawing/region) to test. |
| g | [Graphics](../../com.aspose.drawing/graphics) | Ένα [Graphics](../../com.aspose.drawing/graphics) που αντιπροσωπεύει μια επιφάνεια σχεδίασης. |

**Returns:**
boolean - true εάν το εσωτερικό της περιοχής είναι ταυτόσημο με το εσωτερικό αυτής της περιοχής όταν εφαρμόζεται ο μετασχηματισμός που συσχετίζεται με την παράμετρο `g`; διαφορετικά, false.
### deepClone() {#deepClone--}
```
public Region deepClone()
```


Δημιουργεί ένα ακριβές αντίγραφο αυτού του [Region](../../com.aspose.drawing/region).

**Returns:**
[Region](../../com.aspose.drawing/region) - The [Region](../../com.aspose.drawing/region) that this method creates.
### makeInfinite() {#makeInfinite--}
```
public void makeInfinite()
```


Αρχικοποιεί αυτό το αντικείμενο [Region](../../com.aspose.drawing/region) σε ένα άπειρο εσωτερικό.

### makeEmpty() {#makeEmpty--}
```
public void makeEmpty()
```


Αρχικοποιεί αυτό το [Region](../../com.aspose.drawing/region) σε ένα κενό εσωτερικό.

### intersect(RectangleF rect) {#intersect-com.aspose.drawing.RectangleF-}
```
public void intersect(RectangleF rect)
```


Ενημερώνει αυτό το [Region](../../com.aspose.drawing/region) στην τομή του με τη καθορισμένη δομή [RectangleF](../../com.aspose.drawing/rectanglef).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | Η δομή [RectangleF](../../com.aspose.drawing/rectanglef) για τομή με αυτήν την [Region](../../com.aspose.drawing/region). |

### intersect(Rectangle rect) {#intersect-com.aspose.drawing.Rectangle-}
```
public void intersect(Rectangle rect)
```


Ενημερώνει αυτό το [Region](../../com.aspose.drawing/region) στην τομή του με τη καθορισμένη δομή [Rectangle](../../com.aspose.drawing/rectangle).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | Η δομή [Rectangle](../../com.aspose.drawing/rectangle) για τομή με αυτήν την [Region](../../com.aspose.drawing/region). |

### intersect(GraphicsPath path) {#intersect-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public void intersect(GraphicsPath path)
```


Ενημερώνει αυτό το [Region](../../com.aspose.drawing/region) στην τομή του με το καθορισμένο [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | Η [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) για τομή με αυτήν την [Region](../../com.aspose.drawing/region). |

### intersect(Region region) {#intersect-com.aspose.drawing.Region-}
```
public void intersect(Region region)
```


Ενημερώνει αυτό το [Region](../../com.aspose.drawing/region) στην τομή του με το καθορισμένο [Region](../../com.aspose.drawing/region).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| region | [Region](../../com.aspose.drawing/region) | Η [Region](../../com.aspose.drawing/region) για τομή με αυτήν την [Region](../../com.aspose.drawing/region). |

### union(RectangleF rect) {#union-com.aspose.drawing.RectangleF-}
```
public void union(RectangleF rect)
```


Ενημερώνει αυτό το [Region](../../com.aspose.drawing/region) στην ένωση του με τη καθορισμένη δομή [RectangleF](../../com.aspose.drawing/rectanglef).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | rect | [RectangleF](../../com.aspose.drawing/rectanglef) | Η δομή [RectangleF](../../com.aspose.drawing/rectanglef) για ένωση με αυτήν την [Region](../../com.aspose.drawing/region). |

--------------------

Η ένωση αφήνει την άπειρη περιοχή ως άπειρη. |

### union(Rectangle rect) {#union-com.aspose.drawing.Rectangle-}
```
public void union(Rectangle rect)
```


Ενημερώνει αυτό το [Region](../../com.aspose.drawing/region) στην ένωση του με τη καθορισμένη δομή [Rectangle](../../com.aspose.drawing/rectangle).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | rect | [Rectangle](../../com.aspose.drawing/rectangle) | Η δομή [Rectangle](../../com.aspose.drawing/rectangle) για ένωση με αυτήν την [Region](../../com.aspose.drawing/region). |

--------------------

Η ένωση αφήνει την άπειρη περιοχή ως άπειρη. |

### union(GraphicsPath path) {#union-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public void union(GraphicsPath path)
```


Ενημερώνει αυτό το [Region](../../com.aspose.drawing/region) στην ένωση του με το καθορισμένο [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | Η [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) για ένωση με αυτήν την [Region](../../com.aspose.drawing/region). |

--------------------

Η ένωση αφήνει την άπειρη περιοχή ως άπειρη. |

### union(Region region) {#union-com.aspose.drawing.Region-}
```
public void union(Region region)
```


Ενημερώνει αυτό το [Region](../../com.aspose.drawing/region) στην ένωση του με το καθορισμένο [Region](../../com.aspose.drawing/region).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | region | [Region](../../com.aspose.drawing/region) | Η [Region](../../com.aspose.drawing/region) για ένωση με αυτήν την [Region](../../com.aspose.drawing/region). |

--------------------

Η ένωση αφήνει την άπειρη περιοχή ως άπειρη. |

### getRegionData() {#getRegionData--}
```
public RegionData getRegionData()
```


Επιστρέφει ένα [RegionData](../../com.aspose.drawing.drawing2d/regiondata) που αντιπροσωπεύει τις πληροφορίες που περιγράφουν αυτό το [Region](../../com.aspose.drawing/region).

**Returns:**
[RegionData](../../com.aspose.drawing.drawing2d/regiondata) - A [RegionData](../../com.aspose.drawing.drawing2d/regiondata) that represents the information that describes this [Region](../../com.aspose.drawing/region).
### xor(RectangleF rect) {#xor-com.aspose.drawing.RectangleF-}
```
public void xor(RectangleF rect)
```


Ενημερώνει αυτό το [Region](../../com.aspose.drawing/region) στην ένωση με αφαίρεση της τομής του με τη καθορισμένη δομή [RectangleF](../../com.aspose.drawing/rectanglef).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | Η δομή [RectangleF](../../com.aspose.drawing/rectanglef) για `M:Region.Xor(Drawing2D.GraphicsPath)` με αυτήν την [Region](../../com.aspose.drawing/region). |

### xor(Rectangle rect) {#xor-com.aspose.drawing.Rectangle-}
```
public void xor(Rectangle rect)
```


Ενημερώνει αυτό το [Region](../../com.aspose.drawing/region) στην ένωση με αφαίρεση της τομής του με τη καθορισμένη δομή [Rectangle](../../com.aspose.drawing/rectangle).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | Η δομή [Rectangle](../../com.aspose.drawing/rectangle) για `M:Region.Xor(Rectangle)` με αυτήν την [Region](../../com.aspose.drawing/region). |

### xor(GraphicsPath path) {#xor-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public void xor(GraphicsPath path)
```


Ενημερώνει αυτό το [Region](../../com.aspose.drawing/region) στην ένωση με αφαίρεση της τομής του με το καθορισμένο [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | Η [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) για `M:Region.Xor(GraphicsPath)` με αυτήν την [Region](../../com.aspose.drawing/region). |

### xor(Region region) {#xor-com.aspose.drawing.Region-}
```
public void xor(Region region)
```


Ενημερώνει αυτό το [Region](../../com.aspose.drawing/region) στην ένωση με αφαίρεση της τομής του με το καθορισμένο [Region](../../com.aspose.drawing/region).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| region | [Region](../../com.aspose.drawing/region) | Η [Region](../../com.aspose.drawing/region) για `M:Region.Xor(Region)` με αυτήν την [Region](../../com.aspose.drawing/region). |

### exclude(RectangleF rect) {#exclude-com.aspose.drawing.RectangleF-}
```
public void exclude(RectangleF rect)
```


Ενημερώνει αυτό το [Region](../../com.aspose.drawing/region) ώστε να περιέχει μόνο το τμήμα του εσωτερικού του που δεν τέμνει τη καθορισμένη δομή [RectangleF](../../com.aspose.drawing/rectanglef).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | Η δομή [RectangleF](../../com.aspose.drawing/rectanglef) για εξαίρεση από αυτήν την [Region](../../com.aspose.drawing/region). |

### exclude(Rectangle rect) {#exclude-com.aspose.drawing.Rectangle-}
```
public void exclude(Rectangle rect)
```


Ενημερώνει αυτό το [Region](../../com.aspose.drawing/region) ώστε να περιέχει μόνο το τμήμα του εσωτερικού του που δεν τέμνει τη καθορισμένη δομή [Rectangle](../../com.aspose.drawing/rectangle).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | Η δομή [Rectangle](../../com.aspose.drawing/rectangle) για εξαίρεση από αυτήν την [Region](../../com.aspose.drawing/region). |

### exclude(GraphicsPath path) {#exclude-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public void exclude(GraphicsPath path)
```


Ενημερώνει αυτό το [Region](../../com.aspose.drawing/region) ώστε να περιέχει μόνο το τμήμα του εσωτερικού του που δεν τέμνει το καθορισμένο [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | Η [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) για εξαίρεση από αυτήν την [Region](../../com.aspose.drawing/region). |

### exclude(Region region) {#exclude-com.aspose.drawing.Region-}
```
public void exclude(Region region)
```


Ενημερώνει αυτό το [Region](../../com.aspose.drawing/region) ώστε να περιέχει μόνο το τμήμα του εσωτερικού του που δεν τέμνει το καθορισμένο [Region](../../com.aspose.drawing/region).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| region | [Region](../../com.aspose.drawing/region) | Η [Region](../../com.aspose.drawing/region) για εξαίρεση από αυτήν την [Region](../../com.aspose.drawing/region). |

### complement(RectangleF rect) {#complement-com.aspose.drawing.RectangleF-}
```
public void complement(RectangleF rect)
```


Ενημερώνει αυτό το [Region](../../com.aspose.drawing/region) ώστε να περιέχει το τμήμα της καθορισμένης δομής [RectangleF](../../com.aspose.drawing/rectanglef) που δεν τέμνει αυτό το [Region](../../com.aspose.drawing/region).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | Η δομή [RectangleF](../../com.aspose.drawing/rectanglef) για συμπλήρωση αυτής της [Region](../../com.aspose.drawing/region). |

### complement(Rectangle rect) {#complement-com.aspose.drawing.Rectangle-}
```
public void complement(Rectangle rect)
```


Ενημερώνει αυτό το [Region](../../com.aspose.drawing/region) ώστε να περιέχει το τμήμα της καθορισμένης δομής [Rectangle](../../com.aspose.drawing/rectangle) που δεν τέμνει αυτό το [Region](../../com.aspose.drawing/region).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | Η δομή [Rectangle](../../com.aspose.drawing/rectangle) για συμπλήρωση αυτής της [Region](../../com.aspose.drawing/region). |

### complement(GraphicsPath path) {#complement-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public void complement(GraphicsPath path)
```


Ενημερώνει αυτό το [Region](../../com.aspose.drawing/region) ώστε να περιέχει το τμήμα του καθορισμένου [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) που δεν τέμνει αυτό το [Region](../../com.aspose.drawing/region).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | Η [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) για συμπλήρωση αυτής της [Region](../../com.aspose.drawing/region). |

### complement(Region region) {#complement-com.aspose.drawing.Region-}
```
public void complement(Region region)
```


Updates this [Region](../../com.aspose.drawing/region) to contain the portion of the specified [Region](../../com.aspose.drawing/region) that does not intersect with this [Region](../../com.aspose.drawing/region).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| region | [Region](../../com.aspose.drawing/region) | Το αντικείμενο [Region](../../com.aspose.drawing/region) για συμπλήρωση αυτού του αντικειμένου [Region](../../com.aspose.drawing/region). |

### translate(float dx, float dy) {#translate-float-float-}
```
public void translate(float dx, float dy)
```


Offsets the coordinates of this [Region](../../com.aspose.drawing/region) by the specified amount.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| dx | float | Το ποσό για οριζόντια μετατόπιση αυτής της [Region](../../com.aspose.drawing/region). |
| dy | float | Το ποσό για κάθετη μετατόπιση αυτής της [Region](../../com.aspose.drawing/region). |

### translate(int dx, int dy) {#translate-int-int-}
```
public void translate(int dx, int dy)
```


Offsets the coordinates of this [Region](../../com.aspose.drawing/region) by the specified amount.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| dx | int | Το ποσό για μετατόπιση αυτού του [Region](../../com.aspose.drawing/region) οριζόντια |
| dy | int | Το ποσό για κάθετη μετατόπιση αυτής της [Region](../../com.aspose.drawing/region). |

### transform(Matrix matrix) {#transform-com.aspose.drawing.drawing2d.Matrix-}
```
public void transform(Matrix matrix)
```


Transforms this [Region](../../com.aspose.drawing/region) by the specified [Matrix](../../com.aspose.drawing.drawing2d/matrix).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | Η [Matrix](../../com.aspose.drawing.drawing2d/matrix) με την οποία θα μετασχηματιστεί αυτό το [Region](../../com.aspose.drawing/region). |

### getBounds(Graphics g) {#getBounds-com.aspose.drawing.Graphics-}
```
public RectangleF getBounds(Graphics g)
```


Gets a [RectangleF](../../com.aspose.drawing/rectanglef) structure that represents a rectangle that bounds this [Region](../../com.aspose.drawing/region) on the drawing surface of a [Graphics](../../com.aspose.drawing/graphics) object.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| g | [Graphics](../../com.aspose.drawing/graphics) | Το [Graphics](../../com.aspose.drawing/graphics) στο οποίο σχεδιάζεται αυτό το [Region](../../com.aspose.drawing/region). |

**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef) - A [RectangleF](../../com.aspose.drawing/rectanglef) structure that represents the bounding rectangle for this [Region](../../com.aspose.drawing/region) on the specified drawing surface.
### getRegionScans(Matrix matrix) {#getRegionScans-com.aspose.drawing.drawing2d.Matrix-}
```
public RectangleF[] getRegionScans(Matrix matrix)
```


Returns an array of [RectangleF](../../com.aspose.drawing/rectanglef) structures that approximate this [Region](../../com.aspose.drawing/region) after the specified matrix transformation is applied.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | Ένα [Matrix](../../com.aspose.drawing.drawing2d/matrix) που αντιπροσωπεύει μια γεωμετρική μεταστροφή για εφαρμογή στην περιοχή. |

**Returns:**
com.aspose.drawing.RectangleF[] - Ένας πίνακας από δομές [RectangleF](../../com.aspose.drawing/rectanglef) που προσεγγίζουν αυτό το [Region](../../com.aspose.drawing/region) μετά την εφαρμογή της καθορισμένης μεταστροφής matrix.
### isEmpty(Graphics g) {#isEmpty-com.aspose.drawing.Graphics-}
```
public boolean isEmpty(Graphics g)
```


Tests whether this [Region](../../com.aspose.drawing/region) has an empty interior on the specified drawing surface.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| g | [Graphics](../../com.aspose.drawing/graphics) | Ένα [Graphics](../../com.aspose.drawing/graphics) που αντιπροσωπεύει μια επιφάνεια σχεδίασης. |

**Returns:**
boolean - true εάν το εσωτερικό αυτού του [Region](../../com.aspose.drawing/region) είναι κενό όταν εφαρμόζεται η μεταστροφή που σχετίζεται με `g`; διαφορετικά, false.
### isInfinite(Graphics g) {#isInfinite-com.aspose.drawing.Graphics-}
```
public boolean isInfinite(Graphics g)
```


Tests whether this [Region](../../com.aspose.drawing/region) has an infinite interior on the specified drawing surface.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| g | [Graphics](../../com.aspose.drawing/graphics) | Ένα [Graphics](../../com.aspose.drawing/graphics) που αντιπροσωπεύει μια επιφάνεια σχεδίασης. |

**Returns:**
boolean - true εάν το εσωτερικό αυτού του [Region](../../com.aspose.drawing/region) είναι άπειρο όταν εφαρμόζεται η μεταστροφή που σχετίζεται με `g`; διαφορετικά, false.
### isVisible(float x, float y) {#isVisible-float-float-}
```
public boolean isVisible(float x, float y)
```


Tests whether the specified point is contained within this [Region](../../com.aspose.drawing/region).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | float | Η συντεταγμένη x του σημείου που θα δοκιμαστεί. |
| y | float | Η συντεταγμένη y του σημείου προς δοκιμή. |

**Returns:**
boolean - true όταν το καθορισμένο σημείο περιέχεται μέσα σε αυτό το [Region](../../com.aspose.drawing/region); διαφορετικά, false.
### isVisible(PointF point) {#isVisible-com.aspose.drawing.PointF-}
```
public boolean isVisible(PointF point)
```


Tests whether the specified [PointF](../../com.aspose.drawing/pointf) structure is contained within this [Region](../../com.aspose.drawing/region).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| point | [PointF](../../com.aspose.drawing/pointf) | Η δομή [PointF](../../com.aspose.drawing/pointf) για δοκιμή. |

**Returns:**
boolean - true όταν το `point` περιέχεται μέσα σε αυτό το [Region](../../com.aspose.drawing/region); διαφορετικά, false.
### isVisible(float x, float y, Graphics g) {#isVisible-float-float-com.aspose.drawing.Graphics-}
```
public boolean isVisible(float x, float y, Graphics g)
```


Tests whether the specified point is contained within this [Region](../../com.aspose.drawing/region) when drawn using the specified [Graphics](../../com.aspose.drawing/graphics).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | float | Η συντεταγμένη x του σημείου που θα δοκιμαστεί. |
| y | float | Η συντεταγμένη y του σημείου προς δοκιμή. |
| g | [Graphics](../../com.aspose.drawing/graphics) | Ένα [Graphics](../../com.aspose.drawing/graphics) που αντιπροσωπεύει ένα γραφικό περιβάλλον. |

**Returns:**
boolean - true όταν το καθορισμένο σημείο περιέχεται μέσα σε αυτό το [Region](../../com.aspose.drawing/region); διαφορετικά, false.
### isVisible(PointF point, Graphics g) {#isVisible-com.aspose.drawing.PointF-com.aspose.drawing.Graphics-}
```
public boolean isVisible(PointF point, Graphics g)
```


Tests whether the specified [PointF](../../com.aspose.drawing/pointf) structure is contained within this [Region](../../com.aspose.drawing/region) when drawn using the specified [Graphics](../../com.aspose.drawing/graphics).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| point | [PointF](../../com.aspose.drawing/pointf) | Η δομή [PointF](../../com.aspose.drawing/pointf) για δοκιμή. |
| g | [Graphics](../../com.aspose.drawing/graphics) | Ένα [Graphics](../../com.aspose.drawing/graphics) που αντιπροσωπεύει ένα γραφικό περιβάλλον. |

**Returns:**
boolean - true όταν το `point` περιέχεται μέσα σε αυτό το [Region](../../com.aspose.drawing/region); διαφορετικά, false.
### isVisible(float x, float y, float width, float height) {#isVisible-float-float-float-float-}
```
public boolean isVisible(float x, float y, float width, float height)
```


Tests whether any portion of the specified rectangle is contained within this [Region](../../com.aspose.drawing/region).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | float | Η συντεταγμένη x του επάνω αριστερού γωνιακού σημείου του ορθογωνίου για δοκιμή. |
| y | float | Η συντεταγμένη y του επάνω αριστερού γωνιακού σημείου του ορθογωνίου για δοκιμή. |
| width | float | Το πλάτος του ορθογωνίου για δοκιμή. |
| height | float | Το ύψος του ορθογωνίου για δοκιμή. |

**Returns:**
boolean - true όταν οποιοδήποτε τμήμα του καθορισμένου ορθογωνίου περιέχεται μέσα σε αυτό το αντικείμενο [Region](../../com.aspose.drawing/region); διαφορετικά, false.
### isVisible(RectangleF rect) {#isVisible-com.aspose.drawing.RectangleF-}
```
public boolean isVisible(RectangleF rect)
```


Tests whether any portion of the specified [RectangleF](../../com.aspose.drawing/rectanglef) structure is contained within this [Region](../../com.aspose.drawing/region).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | Η δομή [RectangleF](../../com.aspose.drawing/rectanglef) για δοκιμή. |

**Returns:**
boolean - true όταν οποιοδήποτε τμήμα του `rect` περιέχεται μέσα σε αυτό το [Region](../../com.aspose.drawing/region); διαφορετικά, false.
### isVisible(float x, float y, float width, float height, Graphics g) {#isVisible-float-float-float-float-com.aspose.drawing.Graphics-}
```
public boolean isVisible(float x, float y, float width, float height, Graphics g)
```


Tests whether any portion of the specified rectangle is contained within this [Region](../../com.aspose.drawing/region) when drawn using the specified [Graphics](../../com.aspose.drawing/graphics).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | float | Η συντεταγμένη x του επάνω αριστερού γωνιακού σημείου του ορθογωνίου για δοκιμή. |
| y | float | Η συντεταγμένη y του επάνω αριστερού γωνιακού σημείου του ορθογωνίου για δοκιμή. |
| width | float | Το πλάτος του ορθογωνίου για δοκιμή. |
| height | float | Το ύψος του ορθογωνίου για δοκιμή. |
| g | [Graphics](../../com.aspose.drawing/graphics) | Ένα [Graphics](../../com.aspose.drawing/graphics) που αντιπροσωπεύει ένα γραφικό περιβάλλον. |

**Returns:**
boolean - true όταν οποιοδήποτε τμήμα του καθορισμένου ορθογωνίου περιέχεται μέσα σε αυτό το [Region](../../com.aspose.drawing/region); διαφορετικά, false.
### isVisible(RectangleF rect, Graphics g) {#isVisible-com.aspose.drawing.RectangleF-com.aspose.drawing.Graphics-}
```
public boolean isVisible(RectangleF rect, Graphics g)
```


Tests whether any portion of the specified [RectangleF](../../com.aspose.drawing/rectanglef) structure is contained within this [Region](../../com.aspose.drawing/region) when drawn using the specified [Graphics](../../com.aspose.drawing/graphics).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | Η δομή [RectangleF](../../com.aspose.drawing/rectanglef) για δοκιμή. |
| g | [Graphics](../../com.aspose.drawing/graphics) | Ένα [Graphics](../../com.aspose.drawing/graphics) που αντιπροσωπεύει ένα γραφικό περιβάλλον. |

**Returns:**
boolean - true όταν το `rect` περιέχεται μέσα σε αυτό το [Region](../../com.aspose.drawing/region); διαφορετικά, false.
### isVisible(int x, int y, Graphics g) {#isVisible-int-int-com.aspose.drawing.Graphics-}
```
public boolean isVisible(int x, int y, Graphics g)
```


Tests whether the specified point is contained within this [Region](../../com.aspose.drawing/region) object when drawn using the specified [Graphics](../../com.aspose.drawing/graphics) object.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | int | Η συντεταγμένη x του σημείου που θα δοκιμαστεί. |
| y | int | Η συντεταγμένη y του σημείου προς δοκιμή. |
| g | [Graphics](../../com.aspose.drawing/graphics) | Ένα [Graphics](../../com.aspose.drawing/graphics) που αντιπροσωπεύει ένα γραφικό περιβάλλον. |

**Returns:**
boolean - true όταν το καθορισμένο σημείο περιέχεται μέσα σε αυτό το [Region](../../com.aspose.drawing/region); διαφορετικά, false.
### isVisible(Point point) {#isVisible-com.aspose.drawing.Point-}
```
public boolean isVisible(Point point)
```


Tests whether the specified [Point](../../com.aspose.drawing/point) structure is contained within this [Region](../../com.aspose.drawing/region).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| point | [Point](../../com.aspose.drawing/point) | Η δομή [Point](../../com.aspose.drawing/point) για δοκιμή. |

**Returns:**
boolean - true όταν το `point` περιέχεται μέσα σε αυτό το [Region](../../com.aspose.drawing/region); διαφορετικά, false.
### isVisible(Point point, Graphics g) {#isVisible-com.aspose.drawing.Point-com.aspose.drawing.Graphics-}
```
public boolean isVisible(Point point, Graphics g)
```


Tests whether the specified [Point](../../com.aspose.drawing/point) structure is contained within this [Region](../../com.aspose.drawing/region) when drawn using the specified [Graphics](../../com.aspose.drawing/graphics).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| point | [Point](../../com.aspose.drawing/point) | Η δομή [Point](../../com.aspose.drawing/point) για δοκιμή. |
| g | [Graphics](../../com.aspose.drawing/graphics) | Ένα [Graphics](../../com.aspose.drawing/graphics) που αντιπροσωπεύει ένα γραφικό περιβάλλον. |

**Returns:**
boolean - true όταν το `point` περιέχεται μέσα σε αυτό το [Region](../../com.aspose.drawing/region); διαφορετικά, false.
### isVisible(int x, int y, int width, int height) {#isVisible-int-int-int-int-}
```
public boolean isVisible(int x, int y, int width, int height)
```


Tests whether any portion of the specified rectangle is contained within this [Region](../../com.aspose.drawing/region).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | int | Η συντεταγμένη x του επάνω αριστερού γωνιακού σημείου του ορθογωνίου για δοκιμή. |
| y | int | Η συντεταγμένη y του επάνω αριστερού γωνιακού σημείου του ορθογωνίου για δοκιμή. |
| width | int | Το πλάτος του ορθογωνίου για δοκιμή. |
| height | int | Το ύψος του ορθογωνίου για δοκιμή. |

**Returns:**
boolean - true όταν οποιοδήποτε τμήμα του καθορισμένου ορθογωνίου περιέχεται μέσα σε αυτό το [Region](../../com.aspose.drawing/region); διαφορετικά, false.
### isVisible(Rectangle rect) {#isVisible-com.aspose.drawing.Rectangle-}
```
public boolean isVisible(Rectangle rect)
```


Tests whether any portion of the specified [Rectangle](../../com.aspose.drawing/rectangle) structure is contained within this [Region](../../com.aspose.drawing/region).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | Η δομή [Rectangle](../../com.aspose.drawing/rectangle) για δοκιμή. |

**Returns:**
boolean - Αυτή η μέθοδος επιστρέφει true όταν οποιοδήποτε τμήμα του `rect` περιέχεται μέσα σε αυτό το [Region](../../com.aspose.drawing/region); διαφορετικά, false.
### isVisible(int x, int y, int width, int height, Graphics g) {#isVisible-int-int-int-int-com.aspose.drawing.Graphics-}
```
public boolean isVisible(int x, int y, int width, int height, Graphics g)
```


Tests whether any portion of the specified rectangle is contained within this [Region](../../com.aspose.drawing/region) when drawn using the specified [Graphics](../../com.aspose.drawing/graphics).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | int | Η συντεταγμένη x του επάνω αριστερού γωνιακού σημείου του ορθογωνίου για δοκιμή. |
| y | int | Η συντεταγμένη y του επάνω αριστερού γωνιακού σημείου του ορθογωνίου για δοκιμή. |
| width | int | Το πλάτος του ορθογωνίου για δοκιμή. |
| height | int | Το ύψος του ορθογωνίου για δοκιμή. |
| g | [Graphics](../../com.aspose.drawing/graphics) | Ένα [Graphics](../../com.aspose.drawing/graphics) που αντιπροσωπεύει ένα γραφικό περιβάλλον. |

**Returns:**
boolean - true όταν οποιοδήποτε τμήμα του καθορισμένου ορθογωνίου περιέχεται μέσα σε αυτό το [Region](../../com.aspose.drawing/region); διαφορετικά, false.
### isVisible(Rectangle rect, Graphics g) {#isVisible-com.aspose.drawing.Rectangle-com.aspose.drawing.Graphics-}
```
public boolean isVisible(Rectangle rect, Graphics g)
```


Tests whether any portion of the specified [Rectangle](../../com.aspose.drawing/rectangle) structure is contained within this [Region](../../com.aspose.drawing/region) when drawn using the specified [Graphics](../../com.aspose.drawing/graphics).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | Η δομή [Rectangle](../../com.aspose.drawing/rectangle) για δοκιμή. |
| g | [Graphics](../../com.aspose.drawing/graphics) | Ένα [Graphics](../../com.aspose.drawing/graphics) που αντιπροσωπεύει ένα γραφικό περιβάλλον. |

**Returns:**
boolean - true όταν οποιοδήποτε τμήμα του `rect` περιέχεται μέσα σε αυτό το [Region](../../com.aspose.drawing/region); διαφορετικά, false.
