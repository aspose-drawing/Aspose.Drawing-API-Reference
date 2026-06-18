---
title: ImageAttributes
second_title: Αναφορά API του Aspose.Drawing for Java
description: Περιέχει πληροφορίες σχετικά με το πώς τα χρώματα bitmap και metafile χειρίζονται κατά τη διαδικασία απόδοσης.
type: docs
weight: 24
url: /el/java/com.aspose.drawing.imaging/imageattributes/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public final class ImageAttributes implements System.IDisposable
```

Περιέχει πληροφορίες σχετικά με το πώς τα χρώματα bitmap και metafile χειρίζονται κατά τη διαδικασία απόδοσης.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [ImageAttributes()](#ImageAttributes--) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes). |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [dispose()](#dispose--) | Απελευθερώνει όλους τους πόρους που χρησιμοποιεί αυτό το αντικείμενο [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes). |
| [deepClone()](#deepClone--) | Δημιουργεί ένα ακριβές αντίγραφο αυτού του αντικειμένου [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes). |
| [setColorMatrix(ColorMatrix newColorMatrix)](#setColorMatrix-com.aspose.drawing.imaging.ColorMatrix-) | Ορίζει τον πίνακα προσαρμογής χρώματος για την προεπιλεγμένη κατηγορία. |
| [setColorMatrix(ColorMatrix newColorMatrix, int flags)](#setColorMatrix-com.aspose.drawing.imaging.ColorMatrix-int-) | Ορίζει τον πίνακα προσαρμογής χρώματος για την προεπιλεγμένη κατηγορία. |
| [setColorMatrix(ColorMatrix newColorMatrix, int mode, int type)](#setColorMatrix-com.aspose.drawing.imaging.ColorMatrix-int-int-) | Ορίζει τον πίνακα προσαρμογής χρώματος για μια καθορισμένη κατηγορία. |
| [clearColorMatrix()](#clearColorMatrix--) | Καθαρίζει τον πίνακα προσαρμογής χρώματος για την προεπιλεγμένη κατηγορία. |
| [clearColorMatrix(int type)](#clearColorMatrix-int-) | Καθαρίζει τον πίνακα προσαρμογής χρώματος για μια καθορισμένη κατηγορία. |
| [setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix)](#setColorMatrices-com.aspose.drawing.imaging.ColorMatrix-com.aspose.drawing.imaging.ColorMatrix-) | Ορίζει τον πίνακα προσαρμογής χρώματος και τον πίνακα προσαρμογής κλίμακας του γκρι για την προεπιλεγμένη κατηγορία. |
| [setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int flags)](#setColorMatrices-com.aspose.drawing.imaging.ColorMatrix-com.aspose.drawing.imaging.ColorMatrix-int-) | Ορίζει τον πίνακα προσαρμογής χρώματος και τον πίνακα προσαρμογής κλίμακας του γκρι για την προεπιλεγμένη κατηγορία. |
| [setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int mode, int type)](#setColorMatrices-com.aspose.drawing.imaging.ColorMatrix-com.aspose.drawing.imaging.ColorMatrix-int-int-) | Ορίζει τον πίνακα προσαρμογής χρώματος και τον πίνακα προσαρμογής κλίμακας του γκρι για μια καθορισμένη κατηγορία. |
| [setThreshold(float threshold)](#setThreshold-float-) | Ορίζει το όριο (εύρος διαφάνειας) για την προεπιλεγμένη κατηγορία. |
| [setThreshold(float threshold, int type)](#setThreshold-float-int-) | Ορίζει το όριο (εύρος διαφάνειας) για μια καθορισμένη κατηγορία. |
| [clearThreshold()](#clearThreshold--) | Καθαρίζει την τιμή του ορίου για την προεπιλεγμένη κατηγορία. |
| [clearThreshold(int type)](#clearThreshold-int-) | Καθαρίζει την τιμή του ορίου για μια καθορισμένη κατηγορία. |
| [setGamma(float gamma)](#setGamma-float-) | Ορίζει την τιμή γάμμα για την προεπιλεγμένη κατηγορία. |
| [setGamma(float gamma, int type)](#setGamma-float-int-) | Ορίζει την τιμή γάμμα για μια καθορισμένη κατηγορία. |
| [clearGamma()](#clearGamma--) | Απενεργοποιεί τη διόρθωση γάμμα για την προεπιλεγμένη κατηγορία. |
| [clearGamma(int type)](#clearGamma-int-) | Απενεργοποιεί τη διόρθωση γάμμα για μια καθορισμένη κατηγορία. |
| [setNoOp()](#setNoOp--) | Απενεργοποιεί την προσαρμογή χρώματος για την προεπιλεγμένη κατηγορία. |
| [setNoOp(int type)](#setNoOp-int-) | Απενεργοποιεί την προσαρμογή χρώματος για μια καθορισμένη κατηγορία. |
| [clearNoOp()](#clearNoOp--) | Καθαρίζει τη ρύθμιση NoOp για την προεπιλεγμένη κατηγορία. |
| [clearNoOp(int type)](#clearNoOp-int-) | Καθαρίζει τη ρύθμιση NoOp για μια καθορισμένη κατηγορία. |
| [setColorKey(Color colorLow, Color colorHigh)](#setColorKey-com.aspose.drawing.Color-com.aspose.drawing.Color-) | Ορίζει το κλειδί χρώματος για την προεπιλεγμένη κατηγορία. |
| [setColorKey(Color colorLow, Color colorHigh, int type)](#setColorKey-com.aspose.drawing.Color-com.aspose.drawing.Color-int-) | Ορίζει το κλειδί χρώματος (εύρος διαφάνειας) για μια καθορισμένη κατηγορία. |
| [clearColorKey()](#clearColorKey--) | Καθαρίζει το κλειδί χρώματος (εύρος διαφάνειας) για την προεπιλεγμένη κατηγορία. |
| [clearColorKey(int type)](#clearColorKey-int-) | Καθαρίζει το κλειδί χρώματος (εύρος διαφάνειας) για μια καθορισμένη κατηγορία. |
| [setOutputChannel(int flags)](#setOutputChannel-int-) | Ορίζει το κανάλι εξόδου CMYK (κυανό-ματζέντα-κίτρινο-μαύρο) για την προεπιλεγμένη κατηγορία. |
| [setOutputChannel(int flags, int type)](#setOutputChannel-int-int-) | Ορίζει το κανάλι εξόδου CMYK (κυανό-ματζέντα-κίτρινο-μαύρο) για μια καθορισμένη κατηγορία. |
| [clearOutputChannel()](#clearOutputChannel--) | Καθαρίζει τη ρύθμιση του καναλιού εξόδου CMYK (κυανό-ματζέντα-κίτρινο-μαύρο) για την προεπιλεγμένη κατηγορία. |
| [clearOutputChannel(int type)](#clearOutputChannel-int-) | Καθαρίζει τη ρύθμιση του (κυανό-ματζέντα-κίτρινο-μαύρο) καναλιού εξόδου για μια καθορισμένη κατηγορία. |
| [setOutputChannelColorProfile(String colorProfileFilename)](#setOutputChannelColorProfile-java.lang.String-) | Ορίζει το αρχείο προφίλ χρώματος του καναλιού εξόδου για την προεπιλεγμένη κατηγορία. |
| [setOutputChannelColorProfile(String colorProfileFilename, int type)](#setOutputChannelColorProfile-java.lang.String-int-) | Ορίζει το αρχείο προφίλ χρώματος του καναλιού εξόδου για μια καθορισμένη κατηγορία. |
| [clearOutputChannelColorProfile()](#clearOutputChannelColorProfile--) | Καθαρίζει τη ρύθμιση προφίλ χρώματος του καναλιού εξόδου για την προεπιλεγμένη κατηγορία. |
| [clearOutputChannelColorProfile(int type)](#clearOutputChannelColorProfile-int-) | Καθαρίζει τη ρύθμιση προφίλ χρώματος του καναλιού εξόδου για μια καθορισμένη κατηγορία. |
| [setRemapTable(ColorMap[] map)](#setRemapTable-com.aspose.drawing.imaging.ColorMap---) | Ορίζει τον πίνακα επαναχαρτογράφησης χρώματος για την προεπιλεγμένη κατηγορία. |
| [setRemapTable(ColorMap[] map, int type)](#setRemapTable-com.aspose.drawing.imaging.ColorMap---int-) | Ορίζει τον πίνακα επαναχαρτογράφησης χρώματος για μια καθορισμένη κατηγορία. |
| [clearRemapTable()](#clearRemapTable--) | Καθαρίζει τον πίνακα επαναχαρτογράφησης χρώματος για την προεπιλεγμένη κατηγορία. |
| [clearRemapTable(int type)](#clearRemapTable-int-) | Καθαρίζει τον πίνακα επαναχαρτογράφησης χρώματος για μια καθορισμένη κατηγορία. |
| [setBrushRemapTable(ColorMap[] map)](#setBrushRemapTable-com.aspose.drawing.imaging.ColorMap---) | Ορίζει τον πίνακα επαναχαρτογράφησης χρώματος για την κατηγορία πινέλου. |
| [clearBrushRemapTable()](#clearBrushRemapTable--) | Καθαρίζει τον πίνακα επαναχαρτογράφησης χρώματος πινέλου αυτού του αντικειμένου [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes). |
| [setWrapMode(int mode)](#setWrapMode-int-) | Ορίζει τη λειτουργία περιτύλιξης που χρησιμοποιείται για να αποφασίσει πώς θα τοποθετηθεί ένα υφή σε ένα σχήμα ή στα όρια του σχήματος. |
| [setWrapMode(int mode, Color color)](#setWrapMode-int-com.aspose.drawing.Color-) | Ορίζει τη λειτουργία περιτύλιξης και το χρώμα που χρησιμοποιούνται για να αποφασίσουν πώς θα τοποθετηθεί ένα υφή σε ένα σχήμα ή στα όρια του σχήματος. |
| [setWrapMode(int mode, Color color, boolean clamp)](#setWrapMode-int-com.aspose.drawing.Color-boolean-) | Ορίζει τη λειτουργία περιτύλιξης και το χρώμα που χρησιμοποιούνται για να αποφασίσουν πώς θα τοποθετηθεί ένα υφή σε ένα σχήμα ή στα όρια του σχήματος. |
| [getAdjustedPalette(ColorPalette palette, int type)](#getAdjustedPalette-com.aspose.drawing.imaging.ColorPalette-int-) | Ρυθμίζει τα χρώματα σε μια παλέτα σύμφωνα με τις ρυθμίσεις προσαρμογής μιας καθορισμένης κατηγορίας. |
### ImageAttributes() {#ImageAttributes--}
```
public ImageAttributes()
```


Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes).

### dispose() {#dispose--}
```
public void dispose()
```


Απελευθερώνει όλους τους πόρους που χρησιμοποιεί αυτό το αντικείμενο [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes).

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Δημιουργεί ένα ακριβές αντίγραφο αυτού του αντικειμένου [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes).

**Returns:**
java.lang.Object - Το αντικείμενο [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes) που δημιουργεί αυτή η κλάση, μετατρεπόμενο σε αντικείμενο.
### setColorMatrix(ColorMatrix newColorMatrix) {#setColorMatrix-com.aspose.drawing.imaging.ColorMatrix-}
```
public void setColorMatrix(ColorMatrix newColorMatrix)
```


Ορίζει τον πίνακα προσαρμογής χρώματος για την προεπιλεγμένη κατηγορία.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) | Ο πίνακας προσαρμογής χρώματος. |

### setColorMatrix(ColorMatrix newColorMatrix, int flags) {#setColorMatrix-com.aspose.drawing.imaging.ColorMatrix-int-}
```
public void setColorMatrix(ColorMatrix newColorMatrix, int flags)
```


Ορίζει τον πίνακα προσαρμογής χρώματος για την προεπιλεγμένη κατηγορία.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) | Ο πίνακας προσαρμογής χρώματος. |
| flags | int | Ένα στοιχείο του [ColorMatrixFlag](../../com.aspose.drawing.imaging/colormatrixflag) που καθορίζει τον τύπο της εικόνας και του χρώματος που θα επηρεαστούν από τον πίνακα προσαρμογής χρώματος. |

### setColorMatrix(ColorMatrix newColorMatrix, int mode, int type) {#setColorMatrix-com.aspose.drawing.imaging.ColorMatrix-int-int-}
```
public void setColorMatrix(ColorMatrix newColorMatrix, int mode, int type)
```


Ορίζει τον πίνακα προσαρμογής χρώματος για μια καθορισμένη κατηγορία.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) | Ο πίνακας προσαρμογής χρώματος. |
| mode | int | Ένα στοιχείο του [ColorMatrixFlag](../../com.aspose.drawing.imaging/colormatrixflag) που καθορίζει τον τύπο της εικόνας και του χρώματος που θα επηρεαστούν από τον πίνακα προσαρμογής χρώματος. |
| type | int | Ένα στοιχείο του [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) που καθορίζει την κατηγορία για την οποία ορίζεται ο πίνακας προσαρμογής χρώματος. |

### clearColorMatrix() {#clearColorMatrix--}
```
public void clearColorMatrix()
```


Καθαρίζει τον πίνακα προσαρμογής χρώματος για την προεπιλεγμένη κατηγορία.

### clearColorMatrix(int type) {#clearColorMatrix-int-}
```
public void clearColorMatrix(int type)
```


Καθαρίζει τον πίνακα προσαρμογής χρώματος για μια καθορισμένη κατηγορία.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| type | int | Ένα στοιχείο του [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) που καθορίζει την κατηγορία για την οποία καθαρίζεται ο πίνακας προσαρμογής χρώματος. |

### setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix) {#setColorMatrices-com.aspose.drawing.imaging.ColorMatrix-com.aspose.drawing.imaging.ColorMatrix-}
```
public void setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix)
```


Ορίζει τον πίνακα προσαρμογής χρώματος και τον πίνακα προσαρμογής κλίμακας του γκρι για την προεπιλεγμένη κατηγορία.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) | Ο πίνακας προσαρμογής χρώματος. |
| grayMatrix | [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) | Ο πίνακας προσαρμογής κλίμακας του γκρι. |

### setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int flags) {#setColorMatrices-com.aspose.drawing.imaging.ColorMatrix-com.aspose.drawing.imaging.ColorMatrix-int-}
```
public void setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int flags)
```


Ορίζει τον πίνακα προσαρμογής χρώματος και τον πίνακα προσαρμογής κλίμακας του γκρι για την προεπιλεγμένη κατηγορία.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) | Ο πίνακας προσαρμογής χρώματος. |
| grayMatrix | [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) | Ο πίνακας προσαρμογής κλίμακας του γκρι. |
| flags | int | Ένα στοιχείο του [ColorMatrixFlag](../../com.aspose.drawing.imaging/colormatrixflag) που καθορίζει τον τύπο της εικόνας και του χρώματος που θα επηρεαστούν από τους πίνακες προσαρμογής χρώματος και κλίμακας του γκρι. |

### setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int mode, int type) {#setColorMatrices-com.aspose.drawing.imaging.ColorMatrix-com.aspose.drawing.imaging.ColorMatrix-int-int-}
```
public void setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int mode, int type)
```


Ορίζει τον πίνακα προσαρμογής χρώματος και τον πίνακα προσαρμογής κλίμακας του γκρι για μια καθορισμένη κατηγορία.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) | Ο πίνακας προσαρμογής χρώματος. |
| grayMatrix | [ColorMatrix](../../com.aspose.drawing.imaging/colormatrix) | Ο πίνακας προσαρμογής κλίμακας του γκρι. |
| mode | int | Ένα στοιχείο του [ColorMatrixFlag](../../com.aspose.drawing.imaging/colormatrixflag) που καθορίζει τον τύπο της εικόνας και του χρώματος που θα επηρεαστούν από τους πίνακες προσαρμογής χρώματος και κλίμακας του γκρι. |
| type | int | Ένα στοιχείο του [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) που καθορίζει την κατηγορία για την οποία ορίζονται οι πίνακες προσαρμογής χρώματος και κλίμακας του γκρι. |

### setThreshold(float threshold) {#setThreshold-float-}
```
public void setThreshold(float threshold)
```


Ορίζει το όριο (εύρος διαφάνειας) για την προεπιλεγμένη κατηγορία.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| κατώφλι | float | Ένας πραγματικός αριθμός που καθορίζει την τιμή του κατωφλίου. |

### setThreshold(float threshold, int type) {#setThreshold-float-int-}
```
public void setThreshold(float threshold, int type)
```


Ορίζει το όριο (εύρος διαφάνειας) για μια καθορισμένη κατηγορία.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| κατώφλι | float | Μια τιμή κατωφλίου από 0,0 έως 1,0 που χρησιμοποιείται ως σημείο διακοπής για την ταξινόμηση χρωμάτων που θα αντιστοιχιστούν είτε σε μέγιστη είτε σε ελάχιστη τιμή. |
| type | int | Ένα στοιχείο του [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) που καθορίζει την κατηγορία για την οποία ορίζεται το κατώφλι χρώματος. |

### clearThreshold() {#clearThreshold--}
```
public void clearThreshold()
```


Καθαρίζει την τιμή του ορίου για την προεπιλεγμένη κατηγορία.

### clearThreshold(int type) {#clearThreshold-int-}
```
public void clearThreshold(int type)
```


Καθαρίζει την τιμή του ορίου για μια καθορισμένη κατηγορία.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| type | int | Ένα στοιχείο του [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) που καθορίζει την κατηγορία για την οποία καθαρίζεται το κατώφλι. |

### setGamma(float gamma) {#setGamma-float-}
```
public void setGamma(float gamma)
```


Ορίζει την τιμή γάμμα για την προεπιλεγμένη κατηγορία.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| γάμμα | float | Η τιμή διόρθωσης γάμμα. |

### setGamma(float gamma, int type) {#setGamma-float-int-}
```
public void setGamma(float gamma, int type)
```


Ορίζει την τιμή γάμμα για μια καθορισμένη κατηγορία.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| γάμμα | float | Η τιμή διόρθωσης γάμμα. |
| type | int | Ένα στοιχείο της απαρίθμησης [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) που καθορίζει την κατηγορία για την οποία ορίζεται η τιμή γάμμα. |

### clearGamma() {#clearGamma--}
```
public void clearGamma()
```


Απενεργοποιεί τη διόρθωση γάμμα για την προεπιλεγμένη κατηγορία.

### clearGamma(int type) {#clearGamma-int-}
```
public void clearGamma(int type)
```


Απενεργοποιεί τη διόρθωση γάμμα για μια καθορισμένη κατηγορία.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| type | int | Ένα στοιχείο του [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) που καθορίζει την κατηγορία για την οποία η διόρθωση γάμμα είναι απενεργοποιημένη. |

### setNoOp() {#setNoOp--}
```
public void setNoOp()
```


Απενεργοποιεί τη ρύθμιση χρώματος για την προεπιλεγμένη κατηγορία. Μπορείτε να καλέσετε τη μέθοδο [.clearNoOp](../../null/\#clearNoOp) για να επαναφέρετε τις ρυθμίσεις ρύθμισης χρώματος που υπήρχαν πριν από την κλήση της μεθόδου [.setNoOp](../../null/\#setNoOp).

### setNoOp(int type) {#setNoOp-int-}
```
public void setNoOp(int type)
```


Απενεργοποιεί τη ρύθμιση χρώματος για μια καθορισμένη κατηγορία. Μπορείτε να καλέσετε τη μέθοδο [.clearNoOp](../../null/\#clearNoOp) για να επαναφέρετε τις ρυθμίσεις ρύθμισης χρώματος που υπήρχαν πριν από την κλήση της μεθόδου [.setNoOp](../../null/\#setNoOp).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| type | int | Ένα στοιχείο του [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) που καθορίζει την κατηγορία για την οποία η διόρθωση χρώματος είναι απενεργοποιημένη. |

### clearNoOp() {#clearNoOp--}
```
public void clearNoOp()
```


Καθαρίζει τη ρύθμιση NoOp για την προεπιλεγμένη κατηγορία.

### clearNoOp(int type) {#clearNoOp-int-}
```
public void clearNoOp(int type)
```


Καθαρίζει τη ρύθμιση NoOp για μια καθορισμένη κατηγορία.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| type | int | Ένα στοιχείο του [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) που καθορίζει την κατηγορία για την οποία η ρύθμιση NoOp έχει διαγραφεί. |

### setColorKey(Color colorLow, Color colorHigh) {#setColorKey-com.aspose.drawing.Color-com.aspose.drawing.Color-}
```
public void setColorKey(Color colorLow, Color colorHigh)
```


Ορίζει το κλειδί χρώματος για την προεπιλεγμένη κατηγορία.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| colorLow | [Color](../../com.aspose.drawing/color) | Η χαμηλή τιμή χρωματικού κλειδιού. |
| colorHigh | [Color](../../com.aspose.drawing/color) | Η υψηλή τιμή χρωματικού κλειδιού. |

### setColorKey(Color colorLow, Color colorHigh, int type) {#setColorKey-com.aspose.drawing.Color-com.aspose.drawing.Color-int-}
```
public void setColorKey(Color colorLow, Color colorHigh, int type)
```


Ορίζει το κλειδί χρώματος (εύρος διαφάνειας) για μια καθορισμένη κατηγορία.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| colorLow | [Color](../../com.aspose.drawing/color) | Η χαμηλή τιμή χρωματικού κλειδιού. |
| colorHigh | [Color](../../com.aspose.drawing/color) | Η υψηλή τιμή χρωματικού κλειδιού. |
| type | int | Ένα στοιχείο του [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) που καθορίζει την κατηγορία για την οποία ορίζεται το χρωματικό κλειδί. |

### clearColorKey() {#clearColorKey--}
```
public void clearColorKey()
```


Καθαρίζει το κλειδί χρώματος (εύρος διαφάνειας) για την προεπιλεγμένη κατηγορία.

### clearColorKey(int type) {#clearColorKey-int-}
```
public void clearColorKey(int type)
```


Καθαρίζει το κλειδί χρώματος (εύρος διαφάνειας) για μια καθορισμένη κατηγορία.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| type | int | Ένα στοιχείο του [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) που καθορίζει την κατηγορία για την οποία το χρωματικό κλειδί έχει διαγραφεί. |

### setOutputChannel(int flags) {#setOutputChannel-int-}
```
public void setOutputChannel(int flags)
```


Ορίζει το κανάλι εξόδου CMYK (κυανό-ματζέντα-κίτρινο-μαύρο) για την προεπιλεγμένη κατηγορία.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| flags | int | Ένα στοιχείο του [ColorChannelFlag](../../com.aspose.drawing.imaging/colorchannelflag) που καθορίζει το κανάλι εξόδου. |

### setOutputChannel(int flags, int type) {#setOutputChannel-int-int-}
```
public void setOutputChannel(int flags, int type)
```


Ορίζει το κανάλι εξόδου CMYK (κυανό-ματζέντα-κίτρινο-μαύρο) για μια καθορισμένη κατηγορία.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| flags | int | Ένα στοιχείο του [ColorChannelFlag](../../com.aspose.drawing.imaging/colorchannelflag) που καθορίζει το κανάλι εξόδου. |
| type | int | Ένα στοιχείο του [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) που καθορίζει την κατηγορία για την οποία ορίζεται το κανάλι εξόδου. |

### clearOutputChannel() {#clearOutputChannel--}
```
public void clearOutputChannel()
```


Καθαρίζει τη ρύθμιση του καναλιού εξόδου CMYK (κυανό-ματζέντα-κίτρινο-μαύρο) για την προεπιλεγμένη κατηγορία.

### clearOutputChannel(int type) {#clearOutputChannel-int-}
```
public void clearOutputChannel(int type)
```


Καθαρίζει τη ρύθμιση του (κυανό-ματζέντα-κίτρινο-μαύρο) καναλιού εξόδου για μια καθορισμένη κατηγορία.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| type | int | Ένα στοιχείο του [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) που καθορίζει την κατηγορία για την οποία η ρύθμιση του καναλιού εξόδου έχει διαγραφεί. |

### setOutputChannelColorProfile(String colorProfileFilename) {#setOutputChannelColorProfile-java.lang.String-}
```
public void setOutputChannelColorProfile(String colorProfileFilename)
```


Ορίζει το αρχείο προφίλ χρώματος του καναλιού εξόδου για την προεπιλεγμένη κατηγορία.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| colorProfileFilename | java.lang.String | Το όνομα διαδρομής ενός αρχείου προφίλ χρώματος. Εάν το αρχείο προφίλ χρώματος βρίσκεται στον κατάλογο %SystemRoot%\\System32\\Spool\\Drivers\\Color, αυτή η παράμετρος μπορεί να είναι το όνομα του αρχείου. Διαφορετικά, αυτή η παράμετρος πρέπει να είναι το πλήρως καθορισμένο όνομα διαδρομής. |

### setOutputChannelColorProfile(String colorProfileFilename, int type) {#setOutputChannelColorProfile-java.lang.String-int-}
```
public void setOutputChannelColorProfile(String colorProfileFilename, int type)
```


Ορίζει το αρχείο προφίλ χρώματος του καναλιού εξόδου για μια καθορισμένη κατηγορία.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| colorProfileFilename | java.lang.String | Το όνομα διαδρομής ενός αρχείου προφίλ χρώματος. Εάν το αρχείο προφίλ χρώματος βρίσκεται στον κατάλογο %SystemRoot%\\System32\\Spool\\Drivers\\Color, αυτή η παράμετρος μπορεί να είναι το όνομα του αρχείου. Διαφορετικά, αυτή η παράμετρος πρέπει να είναι το πλήρως καθορισμένο όνομα διαδρομής. |
| type | int | Ένα στοιχείο του [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) που καθορίζει την κατηγορία για την οποία ορίζεται το αρχείο προφίλ χρώματος του καναλιού εξόδου. |

### clearOutputChannelColorProfile() {#clearOutputChannelColorProfile--}
```
public void clearOutputChannelColorProfile()
```


Καθαρίζει τη ρύθμιση προφίλ χρώματος του καναλιού εξόδου για την προεπιλεγμένη κατηγορία.

### clearOutputChannelColorProfile(int type) {#clearOutputChannelColorProfile-int-}
```
public void clearOutputChannelColorProfile(int type)
```


Καθαρίζει τη ρύθμιση προφίλ χρώματος του καναλιού εξόδου για μια καθορισμένη κατηγορία.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| type | int | Ένα στοιχείο του [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) που καθορίζει την κατηγορία για την οποία η ρύθμιση προφίλ του καναλιού εξόδου έχει διαγραφεί. |

### setRemapTable(ColorMap[] map) {#setRemapTable-com.aspose.drawing.imaging.ColorMap---}
```
public void setRemapTable(ColorMap[] map)
```


Ορίζει τον πίνακα επαναχαρτογράφησης χρώματος για την προεπιλεγμένη κατηγορία.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| map | [ColorMap\[\]](../../com.aspose.drawing.imaging/colormap) | Ένας πίνακας ζευγών χρωμάτων τύπου [ColorMap](../../com.aspose.drawing.imaging/colormap). Κάθε ζεύγος χρωμάτων περιέχει ένα υπάρχον χρώμα (την πρώτη τιμή) και το χρώμα στο οποίο θα αντιστοιχιστεί (τη δεύτερη τιμή). |

### setRemapTable(ColorMap[] map, int type) {#setRemapTable-com.aspose.drawing.imaging.ColorMap---int-}
```
public void setRemapTable(ColorMap[] map, int type)
```


Ορίζει τον πίνακα επαναχαρτογράφησης χρώματος για μια καθορισμένη κατηγορία.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| map | [ColorMap\[\]](../../com.aspose.drawing.imaging/colormap) | Ένας πίνακας ζευγών χρωμάτων τύπου [ColorMap](../../com.aspose.drawing.imaging/colormap). Κάθε ζεύγος χρωμάτων περιέχει ένα υπάρχον χρώμα (την πρώτη τιμή) και το χρώμα στο οποίο θα αντιστοιχιστεί (τη δεύτερη τιμή). |
| type | int | Ένα στοιχείο του [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) που καθορίζει την κατηγορία για την οποία ορίζεται ο πίνακας επαναχαρτογράφησης χρώματος. |

### clearRemapTable() {#clearRemapTable--}
```
public void clearRemapTable()
```


Καθαρίζει τον πίνακα επαναχαρτογράφησης χρώματος για την προεπιλεγμένη κατηγορία.

### clearRemapTable(int type) {#clearRemapTable-int-}
```
public void clearRemapTable(int type)
```


Καθαρίζει τον πίνακα επαναχαρτογράφησης χρώματος για μια καθορισμένη κατηγορία.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| type | int | Ένα στοιχείο του [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) που καθορίζει την κατηγορία για την οποία ο πίνακας επαναχαρτογράφησης έχει διαγραφεί. |

### setBrushRemapTable(ColorMap[] map) {#setBrushRemapTable-com.aspose.drawing.imaging.ColorMap---}
```
public void setBrushRemapTable(ColorMap[] map)
```


Ορίζει τον πίνακα επαναχαρτογράφησης χρώματος για την κατηγορία πινέλου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| map | [ColorMap\[\]](../../com.aspose.drawing.imaging/colormap) | Ένας πίνακας αντικειμένων [ColorMap](../../com.aspose.drawing.imaging/colormap). |

### clearBrushRemapTable() {#clearBrushRemapTable--}
```
public void clearBrushRemapTable()
```


Καθαρίζει τον πίνακα επαναχαρτογράφησης χρώματος πινέλου αυτού του αντικειμένου [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes).

### setWrapMode(int mode) {#setWrapMode-int-}
```
public void setWrapMode(int mode)
```


Ορίζει τη λειτουργία περιτύλιξης που χρησιμοποιείται για να αποφασίσει πώς θα τοποθετηθεί μια υφή πάνω σε ένα σχήμα ή στα όρια του σχήματος. Μια υφή τοποθετείται επαναλαμβανόμενα πάνω σε ένα σχήμα για να το γεμίσει όταν η υφή είναι μικρότερη από το σχήμα που γεμίζει.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| mode | int | Ένα στοιχείο του [WrapMode](../../com.aspose.drawing.drawing2d/wrapmode) που καθορίζει πώς χρησιμοποιούνται αντίγραφα μιας εικόνας για την επικάλυψη μιας περιοχής. |

### setWrapMode(int mode, Color color) {#setWrapMode-int-com.aspose.drawing.Color-}
```
public void setWrapMode(int mode, Color color)
```


Ορίζει τη λειτουργία περιτύλιξης και το χρώμα που χρησιμοποιείται για να αποφασίσει πώς να τοποθετηθεί ένα υφή σε ένα σχήμα, ή στα όρια του σχήματος. Μια υφή τοποθετείται σε ένα σχήμα για να το γεμίσει όταν η υφή είναι μικρότερη από το σχήμα που γεμίζει.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| mode | int | Ένα στοιχείο του [WrapMode](../../com.aspose.drawing.drawing2d/wrapmode) που καθορίζει πώς χρησιμοποιούνται αντίγραφα μιας εικόνας για την επικάλυψη μιας περιοχής. |
| color | [Color](../../com.aspose.drawing/color) | Ένα αντικείμενο [Color](../../com.aspose.drawing/color) που καθορίζει το χρώμα των εικονοστοιχείων εκτός μιας αποδιδόμενης εικόνας. Αυτό το χρώμα είναι ορατό εάν η παράμετρος λειτουργίας οριστεί σε `WrapMode.Clamp` και το ορθογώνιο πηγή που περνιέται στο `Graphics.DrawImage` είναι μεγαλύτερο από την ίδια την εικόνα. |

### setWrapMode(int mode, Color color, boolean clamp) {#setWrapMode-int-com.aspose.drawing.Color-boolean-}
```
public void setWrapMode(int mode, Color color, boolean clamp)
```


Ορίζει τη λειτουργία περιτύλιξης και το χρώμα που χρησιμοποιείται για να αποφασίσει πώς να τοποθετηθεί ένα υφή σε ένα σχήμα, ή στα όρια του σχήματος. Μια υφή τοποθετείται σε ένα σχήμα για να το γεμίσει όταν η υφή είναι μικρότερη από το σχήμα που γεμίζει.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| mode | int | Ένα στοιχείο του [WrapMode](../../com.aspose.drawing.drawing2d/wrapmode) που καθορίζει πώς χρησιμοποιούνται αντίγραφα μιας εικόνας για την επικάλυψη μιας περιοχής. |
| color | [Color](../../com.aspose.drawing/color) | Ένα αντικείμενο χρώματος που καθορίζει το χρώμα των εικονοστοιχείων εκτός μιας αποδιδόμενης εικόνας. Αυτό το χρώμα είναι ορατό εάν η παράμετρος λειτουργίας οριστεί σε `WrapMode.Clamp` και το ορθογώνιο πηγή που περνιέται στο `Graphics.DrawImage` είναι μεγαλύτερο από την ίδια την εικόνα. |
| clamp | boolean | Αυτή η παράμετρος δεν έχει καμία επίδραση. Ορίστε την σε false. |

### getAdjustedPalette(ColorPalette palette, int type) {#getAdjustedPalette-com.aspose.drawing.imaging.ColorPalette-int-}
```
public void getAdjustedPalette(ColorPalette palette, int type)
```


Ρυθμίζει τα χρώματα σε μια παλέτα σύμφωνα με τις ρυθμίσεις προσαρμογής μιας καθορισμένης κατηγορίας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| palette | [ColorPalette](../../com.aspose.drawing.imaging/colorpalette) | Ένα [ColorPalette](../../com.aspose.drawing.imaging/colorpalette) που στην είσοδο περιέχει την παλέτα που θα προσαρμοστεί και στην έξοδο περιέχει την προσαρμοσμένη παλέτα. |
| type | int | Ένα στοιχείο του [ColorAdjustType](../../com.aspose.drawing.imaging/coloradjusttype) που καθορίζει την κατηγορία των ρυθμίσεων προσαρμογής που θα εφαρμοστούν στην παλέτα. |

