---
title: CustomLineCap
second_title: Αναφορά API του Aspose.Drawing for Java
description: Ενσωματώνει ένα προσαρμοσμένο άκρο γραμμής ορισμένο από τον χρήστη.
type: docs
weight: 17
url: /el/java/com.aspose.drawing.drawing2d/customlinecap/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public class CustomLineCap implements System.IDisposable
```

Ενσωματώνει ένα προσαρμοσμένο άκρο γραμμής ορισμένο από τον χρήστη.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath)](#CustomLineCap-com.aspose.drawing.drawing2d.GraphicsPath-com.aspose.drawing.drawing2d.GraphicsPath-) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) με το καθορισμένο περίγραμμα και γέμισμα. |
| [CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap)](#CustomLineCap-com.aspose.drawing.drawing2d.GraphicsPath-com.aspose.drawing.drawing2d.GraphicsPath-int-) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) από την καθορισμένη υπάρχουσα απαρίθμηση [LineCap](../../com.aspose.drawing.drawing2d/linecap) με το καθορισμένο περίγραμμα και γέμισμα. |
| [CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap, float baseInset)](#CustomLineCap-com.aspose.drawing.drawing2d.GraphicsPath-com.aspose.drawing.drawing2d.GraphicsPath-int-float-) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) από την καθορισμένη υπάρχουσα απαρίθμηση [LineCap](../../com.aspose.drawing.drawing2d/linecap) με το καθορισμένο περίγραμμα, γέμισμα και εσωτερική απόσταση. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getStrokeJoin()](#getStrokeJoin--) | Λαμβάνει ή ορίζει την απαρίθμηση [LineJoin](../../com.aspose.drawing.drawing2d/linejoin) που καθορίζει πώς ενώνονται οι γραμμές που συνθέτουν αυτό το αντικείμενο [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap). |
| [setStrokeJoin(int value)](#setStrokeJoin-int-) | Λαμβάνει ή ορίζει την απαρίθμηση [LineJoin](../../com.aspose.drawing.drawing2d/linejoin) που καθορίζει πώς ενώνονται οι γραμμές που συνθέτουν αυτό το αντικείμενο [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap). |
| [getBaseCap()](#getBaseCap--) | Λαμβάνει ή ορίζει την απαρίθμηση [LineCap](../../com.aspose.drawing.drawing2d/linecap) στην οποία βασίζεται αυτό το [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap). |
| [setBaseCap(int value)](#setBaseCap-int-) | Λαμβάνει ή ορίζει την απαρίθμηση [LineCap](../../com.aspose.drawing.drawing2d/linecap) στην οποία βασίζεται αυτό το [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap). |
| [getBaseInset()](#getBaseInset--) | Λαμβάνει ή ορίζει την απόσταση μεταξύ του καπέλου και της γραμμής. |
| [setBaseInset(float value)](#setBaseInset-float-) | Λαμβάνει ή ορίζει την απόσταση μεταξύ του καπέλου και της γραμμής. |
| [getWidthScale()](#getWidthScale--) | Λαμβάνει ή ορίζει το ποσό με το οποίο κλιμακώνεται αυτό το αντικείμενο κλάσης [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) σε σχέση με το πλάτος του αντικειμένου [Pen](../../com.aspose.drawing/pen). |
| [setWidthScale(float value)](#setWidthScale-float-) | Λαμβάνει ή ορίζει το ποσό με το οποίο κλιμακώνεται αυτό το αντικείμενο κλάσης [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) σε σχέση με το πλάτος του αντικειμένου [Pen](../../com.aspose.drawing/pen). |
| [dispose()](#dispose--) | Απελευθερώνει όλους τους πόρους που χρησιμοποιούνται από αυτό το αντικείμενο [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap). |
| [deepClone()](#deepClone--) | Δημιουργεί ένα ακριβές αντίγραφο αυτού του [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap). |
| [setStrokeCaps(int startCap, int endCap)](#setStrokeCaps-int-int-) | Ορίζει τα καπάκια που χρησιμοποιούνται για την έναρξη και το τέλος των γραμμών που αποτελούν αυτό το προσαρμοσμένο καπάκι. |
| [getStrokeCaps(int[] startCap, int[] endCap)](#getStrokeCaps-int---int---) | Λαμβάνει τα καπάκια που χρησιμοποιούνται για την έναρξη και το τέλος των γραμμών που αποτελούν αυτό το προσαρμοσμένο καπάκι. |
| [getFillPath()](#getFillPath--) |  |
| [getStrokePath()](#getStrokePath--) | Λαμβάνει το αντικείμενο που ορίζει το περίγραμμα του προσαρμοσμένου καπάκιου. |
### CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath) {#CustomLineCap-com.aspose.drawing.drawing2d.GraphicsPath-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath)
```


Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) με το καθορισμένο περίγραμμα και γέμισμα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fillPath | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | Ένα αντικείμενο [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) που ορίζει τη γέμιση για το προσαρμοσμένο καπάκι. |
| strokePath | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | Ένα αντικείμενο [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) που ορίζει το περίγραμμα του προσαρμοσμένου καπάκιου. |

### CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap) {#CustomLineCap-com.aspose.drawing.drawing2d.GraphicsPath-com.aspose.drawing.drawing2d.GraphicsPath-int-}
```
public CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap)
```


Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) από την καθορισμένη υπάρχουσα απαρίθμηση [LineCap](../../com.aspose.drawing.drawing2d/linecap) με το καθορισμένο περίγραμμα και γέμισμα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fillPath | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | Ένα αντικείμενο [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) που ορίζει τη γέμιση για το προσαρμοσμένο καπάκι. |
| strokePath | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | Ένα αντικείμενο [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) που ορίζει το περίγραμμα του προσαρμοσμένου καπάκιου. |
| baseCap | int | Το καπάκι γραμμής από το οποίο δημιουργείται το προσαρμοσμένο καπάκι. |

### CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap, float baseInset) {#CustomLineCap-com.aspose.drawing.drawing2d.GraphicsPath-com.aspose.drawing.drawing2d.GraphicsPath-int-float-}
```
public CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap, float baseInset)
```


Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) από την καθορισμένη υπάρχουσα απαρίθμηση [LineCap](../../com.aspose.drawing.drawing2d/linecap) με το καθορισμένο περίγραμμα, γέμισμα και εσωτερική απόσταση.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fillPath | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | Ένα αντικείμενο [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) που ορίζει τη γέμιση για το προσαρμοσμένο καπάκι. |
| strokePath | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | Ένα αντικείμενο [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) που ορίζει το περίγραμμα του προσαρμοσμένου καπάκιου. |
| baseCap | int | Το καπάκι γραμμής από το οποίο δημιουργείται το προσαρμοσμένο καπάκι. |
| baseInset | float | Η απόσταση μεταξύ του καπάκιου και της γραμμής. |

### getStrokeJoin() {#getStrokeJoin--}
```
public final int getStrokeJoin()
```


Λαμβάνει ή ορίζει την απαρίθμηση [LineJoin](../../com.aspose.drawing.drawing2d/linejoin) που καθορίζει πώς ενώνονται οι γραμμές που συνθέτουν αυτό το αντικείμενο [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap).

**Returns:**
int
### setStrokeJoin(int value) {#setStrokeJoin-int-}
```
public final void setStrokeJoin(int value)
```


Λαμβάνει ή ορίζει την απαρίθμηση [LineJoin](../../com.aspose.drawing.drawing2d/linejoin) που καθορίζει πώς ενώνονται οι γραμμές που συνθέτουν αυτό το αντικείμενο [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getBaseCap() {#getBaseCap--}
```
public final int getBaseCap()
```


Λαμβάνει ή ορίζει την απαρίθμηση [LineCap](../../com.aspose.drawing.drawing2d/linecap) στην οποία βασίζεται αυτό το [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap).

**Returns:**
int
### setBaseCap(int value) {#setBaseCap-int-}
```
public final void setBaseCap(int value)
```


Λαμβάνει ή ορίζει την απαρίθμηση [LineCap](../../com.aspose.drawing.drawing2d/linecap) στην οποία βασίζεται αυτό το [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getBaseInset() {#getBaseInset--}
```
public final float getBaseInset()
```


Λαμβάνει ή ορίζει την απόσταση μεταξύ του καπέλου και της γραμμής.

**Returns:**
float
### setBaseInset(float value) {#setBaseInset-float-}
```
public final void setBaseInset(float value)
```


Λαμβάνει ή ορίζει την απόσταση μεταξύ του καπέλου και της γραμμής.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |

### getWidthScale() {#getWidthScale--}
```
public final float getWidthScale()
```


Λαμβάνει ή ορίζει το ποσό με το οποίο κλιμακώνεται αυτό το αντικείμενο κλάσης [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) σε σχέση με το πλάτος του αντικειμένου [Pen](../../com.aspose.drawing/pen).

**Returns:**
float
### setWidthScale(float value) {#setWidthScale-float-}
```
public final void setWidthScale(float value)
```


Λαμβάνει ή ορίζει το ποσό με το οποίο κλιμακώνεται αυτό το αντικείμενο κλάσης [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) σε σχέση με το πλάτος του αντικειμένου [Pen](../../com.aspose.drawing/pen).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |

### dispose() {#dispose--}
```
public final void dispose()
```


Απελευθερώνει όλους τους πόρους που χρησιμοποιούνται από αυτό το αντικείμενο [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap).

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Δημιουργεί ένα ακριβές αντίγραφο αυτού του [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap).

**Returns:**
java.lang.Object - Το [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) που δημιουργεί αυτή η μέθοδος, μετατρεπόμενο σε αντικείμενο.
### setStrokeCaps(int startCap, int endCap) {#setStrokeCaps-int-int-}
```
public final void setStrokeCaps(int startCap, int endCap)
```


Ορίζει τα καπάκια που χρησιμοποιούνται για την έναρξη και το τέλος των γραμμών που αποτελούν αυτό το προσαρμοσμένο καπάκι.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| startCap | int | Η απαρίθμηση [LineCap](../../com.aspose.drawing.drawing2d/linecap) που χρησιμοποιείται στην αρχή μιας γραμμής μέσα σε αυτό το καπάκι. |
| endCap | int | Η απαρίθμηση [LineCap](../../com.aspose.drawing.drawing2d/linecap) που χρησιμοποιείται στο τέλος μιας γραμμής μέσα σε αυτό το καπάκι. |

### getStrokeCaps(int[] startCap, int[] endCap) {#getStrokeCaps-int---int---}
```
public final void getStrokeCaps(int[] startCap, int[] endCap)
```


Λαμβάνει τα καπάκια που χρησιμοποιούνται για την έναρξη και το τέλος των γραμμών που αποτελούν αυτό το προσαρμοσμένο καπάκι.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| startCap | int[] | Η απαρίθμηση [LineCap](../../com.aspose.drawing.drawing2d/linecap) που χρησιμοποιείται στην αρχή μιας γραμμής μέσα σε αυτό το καπάκι. |
| endCap | int[] | Η απαρίθμηση [LineCap](../../com.aspose.drawing.drawing2d/linecap) που χρησιμοποιείται στο τέλος μιας γραμμής μέσα σε αυτό το καπάκι. |

### getFillPath() {#getFillPath--}
```
public GraphicsPath getFillPath()
```




**Returns:**
[GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath)
### getStrokePath() {#getStrokePath--}
```
public GraphicsPath getStrokePath()
```


Λαμβάνει το αντικείμενο που ορίζει το περίγραμμα του προσαρμοσμένου καπάκιου.

**Returns:**
[GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) - The object that defines the outline of the custom cap.
