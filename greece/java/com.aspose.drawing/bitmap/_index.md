---
title: Bitmap
second_title: Αναφορά API του Aspose.Drawing for Java
description: Αποτυπώνει ένα bitmap που αποτελείται από τα δεδομένα εικονοστοιχείων για μια γραφική εικόνα και τις ιδιότητές του.
type: docs
weight: 10
url: /el/java/com.aspose.drawing/bitmap/
---
**Inheritance:**
java.lang.Object, [com.aspose.drawing.Image](../../com.aspose.drawing/image)
```
public class Bitmap extends Image
```

Αποτυπώνει ένα bitmap, το οποίο αποτελείται από τα δεδομένα εικονοστοιχείων για μια γραφική εικόνα και τις ιδιότητές του. Ένα [Bitmap](../../com.aspose.drawing/bitmap) είναι ένα αντικείμενο που χρησιμοποιείται για εργασία με εικόνες που ορίζονται από δεδομένα εικονοστοιχείων.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [Bitmap(int width, int height)](#Bitmap-int-int-) | Αρχικοποιεί μια νέα παρουσία της κλάσης [Bitmap](../../com.aspose.drawing/bitmap) με το καθορισμένο μέγεθος. |
| [Bitmap(String filename)](#Bitmap-java.lang.String-) | Αρχικοποιεί μια νέα παρουσία της κλάσης [Bitmap](../../com.aspose.drawing/bitmap) από το καθορισμένο αρχείο. |
| [Bitmap(String filename, boolean useIcm)](#Bitmap-java.lang.String-boolean-) | Αρχικοποιεί μια νέα παρουσία της κλάσης [Bitmap](../../com.aspose.drawing/bitmap) από το καθορισμένο αρχείο. |
| [Bitmap(InputStream stream)](#Bitmap-java.io.InputStream-) | Αρχικοποιεί μια νέα παρουσία της κλάσης [Bitmap](../../com.aspose.drawing/bitmap) από το καθορισμένο ρεύμα δεδομένων. |
| [Bitmap(InputStream stream, boolean useIcm)](#Bitmap-java.io.InputStream-boolean-) | Αρχικοποιεί μια νέα παρουσία της κλάσης [Bitmap](../../com.aspose.drawing/bitmap) από το καθορισμένο ρεύμα δεδομένων. |
| [Bitmap(int width, int height, int format)](#Bitmap-int-int-int-) | Αρχικοποιεί μια νέα παρουσία της κλάσης [Bitmap](../../com.aspose.drawing/bitmap) με το καθορισμένο μέγεθος και μορφή. |
| [Bitmap(int width, int height, int stride, int format, int[] data)](#Bitmap-int-int-int-int-int---) | Αρχικοποιεί μια νέα παρουσία της κλάσης [Bitmap](../../com.aspose.drawing/bitmap) με το καθορισμένο μέγεθος και δεδομένα εικονοστοιχείων. |
| [Bitmap(Image original)](#Bitmap-com.aspose.drawing.Image-) | Αρχικοποιεί μια νέα παρουσία της κλάσης [Bitmap](../../com.aspose.drawing/bitmap) από την καθορισμένη υπάρχουσα εικόνα. |
| [Bitmap(Image original, Size newSize)](#Bitmap-com.aspose.drawing.Image-com.aspose.drawing.Size-) | Αρχικοποιεί μια νέα παρουσία της κλάσης [Bitmap](../../com.aspose.drawing/bitmap) από την καθορισμένη υπάρχουσα εικόνα, κλιμακωμένη στο καθορισμένο μέγεθος. |
| [Bitmap(Image original, int width, int height)](#Bitmap-com.aspose.drawing.Image-int-int-) | Αρχικοποιεί μια νέα παρουσία της κλάσης [Bitmap](../../com.aspose.drawing/bitmap) από την καθορισμένη υπάρχουσα εικόνα, κλιμακωμένη στο καθορισμένο μέγεθος. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getWidth()](#getWidth--) | Επιστρέφει το πλάτος, σε εικονοστοιχεία, αυτού του Bitmap. |
| [getHeight()](#getHeight--) | Επιστρέφει το ύψος, σε εικονοστοιχεία, αυτού του Bitmap. |
| [getRawFormat()](#getRawFormat--) | Λαμβάνει τη μορφή αρχείου αυτού του [Image](../../com.aspose.drawing/image). |
| [getPixelFormat()](#getPixelFormat--) | Λαμβάνει τη μορφή εικονοστοιχείου για αυτό το [Image](../../com.aspose.drawing/image). |
| [getPalette()](#getPalette--) | Λαμβάνει ή ορίζει την παλέτα χρωμάτων που χρησιμοποιείται για αυτό το [Image](../../com.aspose.drawing/image). |
| [setPalette(ColorPalette value)](#setPalette-com.aspose.drawing.imaging.ColorPalette-) | Λαμβάνει ή ορίζει την παλέτα χρωμάτων που χρησιμοποιείται για αυτό το [Image](../../com.aspose.drawing/image). |
| [getFrameDimensionsList()](#getFrameDimensionsList--) | Λαμβάνει έναν πίνακα GUID που αντιπροσωπεύουν τις διαστάσεις των πλαισίων εντός αυτού του [Image](../../com.aspose.drawing/image). |
| [getPropertyIdList()](#getPropertyIdList--) | Λαμβάνει τα αναγνωριστικά των στοιχείων ιδιοτήτων που αποθηκεύονται σε αυτό το [Image](../../com.aspose.drawing/image). |
| [getPropertyItems()](#getPropertyItems--) | Λαμβάνει όλα τα στοιχεία ιδιοτήτων (τμήματα μεταδεδομένων) που αποθηκεύονται σε αυτό το [Image](../../com.aspose.drawing/image). |
| [deepClone(Rectangle rect, int format)](#deepClone-com.aspose.drawing.Rectangle-int-) | Δημιουργεί ένα αντίγραφο του τμήματος αυτού του [Bitmap](../../com.aspose.drawing/bitmap) που ορίζεται από τη δομή [Rectangle](../../com.aspose.drawing/rectangle) και με καθορισμένο `PixelFormat`([Image.getPixelFormat](../../com.aspose.drawing/image\#getPixelFormat)) αρίθμηση. |
| [deepClone(RectangleF rect, int format)](#deepClone-com.aspose.drawing.RectangleF-int-) | Δημιουργεί ένα αντίγραφο του τμήματος αυτού του [Bitmap](../../com.aspose.drawing/bitmap) που ορίζεται με καθορισμένο [PixelFormat](../../com.aspose.drawing.imaging/pixelformat) αρίθμηση. |
| [setResolution(float xDpi, float yDpi)](#setResolution-float-float-) | Ορίζει την ανάλυση για αυτό το [Bitmap](../../com.aspose.drawing/bitmap). |
| [lockBits(Rectangle rect, int flags, int format)](#lockBits-com.aspose.drawing.Rectangle-int-int-) | Κλειδώνει ένα [Bitmap](../../com.aspose.drawing/bitmap) στη μνήμη του συστήματος. |
| [unlockBits(BitmapData bitmapData)](#unlockBits-com.aspose.drawing.imaging.BitmapData-) | Ξεκλειδώνει αυτό το [Bitmap](../../com.aspose.drawing/bitmap) από τη μνήμη του συστήματος. |
| [getPixel(int x, int y)](#getPixel-int-int-) | Λαμβάνει το χρώμα του καθορισμένου pixel σε αυτό το [Bitmap](../../com.aspose.drawing/bitmap). |
| [setPixel(int x, int y, Color color)](#setPixel-int-int-com.aspose.drawing.Color-) | Ορίζει το χρώμα του καθορισμένου pixel σε αυτό το [Bitmap](../../com.aspose.drawing/bitmap). |
| [readArgb32Pixels(int[] pixels)](#readArgb32Pixels-int---) | Διαβάζει τα pixel του bitmap σε μορφή ARGB32 σε έναν δοσμένο πίνακα. |
| [writeArgb32Pixels(int[] pixels)](#writeArgb32Pixels-int---) | Γράφει pixel στο bitmap. |
| [makeTransparent()](#makeTransparent--) | Κάνει το καθορισμένο χρώμα διαφανές για αυτό το [Bitmap](../../com.aspose.drawing/bitmap). |
| [makeTransparent(Color transparentColor)](#makeTransparent-com.aspose.drawing.Color-) | Κάνει το καθορισμένο χρώμα διαφανές για αυτό το [Bitmap](../../com.aspose.drawing/bitmap). |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | Αυτή η μέθοδος περιστρέφει, αναστρέφει ή περιστρέφει και αναστρέφει το [Image](../../com.aspose.drawing/image). |
| [getPropertyItem(int propid)](#getPropertyItem-int-) | Λαμβάνει το καθορισμένο στοιχείο ιδιότητας από αυτό το [Image](../../com.aspose.drawing/image). |
| [removePropertyItem(int propid)](#removePropertyItem-int-) | Αφαιρεί το καθορισμένο στοιχείο ιδιότητας από αυτό το [Image](../../com.aspose.drawing/image). |
| [setPropertyItem(PropertyItem propitem)](#setPropertyItem-com.aspose.drawing.imaging.PropertyItem-) | Αποθηκεύει ένα στοιχείο ιδιότητας (τμήμα μεταδεδομένων) σε αυτό το [Image](../../com.aspose.drawing/image). |
### Bitmap(int width, int height) {#Bitmap-int-int-}
```
public Bitmap(int width, int height)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [Bitmap](../../com.aspose.drawing/bitmap) με το καθορισμένο μέγεθος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| width | int | Το πλάτος, σε pixel, του νέου Bitmap. |
|  | height | int | Το ύψος, σε pixel, του νέου Bitmap. |

--------------------

Η μόνη υποστηριζόμενη εσωτερική μορφή bitmap αυτή τη στιγμή είναι ισοδύναμη με `PixelFormat.Format32bppPArgb`. |

### Bitmap(String filename) {#Bitmap-java.lang.String-}
```
public Bitmap(String filename)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [Bitmap](../../com.aspose.drawing/bitmap) από το καθορισμένο αρχείο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filename | java.lang.String | Το όνομα του αρχείου bitmap. |

### Bitmap(String filename, boolean useIcm) {#Bitmap-java.lang.String-boolean-}
```
public Bitmap(String filename, boolean useIcm)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [Bitmap](../../com.aspose.drawing/bitmap) από το καθορισμένο αρχείο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filename | java.lang.String | Το όνομα του αρχείου bitmap. |
| useIcm | boolean | true για χρήση διόρθωσης χρώματος σε αυτό το [Bitmap](../../com.aspose.drawing/bitmap); διαφορετικά, false. |

### Bitmap(InputStream stream) {#Bitmap-java.io.InputStream-}
```
public Bitmap(InputStream stream)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [Bitmap](../../com.aspose.drawing/bitmap) από το καθορισμένο ρεύμα δεδομένων.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.InputStream | Η ροή δεδομένων που χρησιμοποιείται για τη φόρτωση της εικόνας. |

### Bitmap(InputStream stream, boolean useIcm) {#Bitmap-java.io.InputStream-boolean-}
```
public Bitmap(InputStream stream, boolean useIcm)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [Bitmap](../../com.aspose.drawing/bitmap) από το καθορισμένο ρεύμα δεδομένων.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.InputStream | Η ροή δεδομένων που χρησιμοποιείται για τη φόρτωση της εικόνας. |
| useIcm | boolean | `true` για χρήση διόρθωσης χρώματος σε αυτό το [Bitmap](../../com.aspose.drawing/bitmap); διαφορετικά, `false`. |

### Bitmap(int width, int height, int format) {#Bitmap-int-int-int-}
```
public Bitmap(int width, int height, int format)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [Bitmap](../../com.aspose.drawing/bitmap) με το καθορισμένο μέγεθος και μορφή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| width | int | Το πλάτος, σε pixel, του νέου [Bitmap](../../com.aspose.drawing/bitmap). |
| height | int | Το ύψος, σε pixel, του νέου [Bitmap](../../com.aspose.drawing/bitmap). |
| format | int | Η απαρίθμηση `PixelFormat`([Image.getPixelFormat](../../com.aspose.drawing/image\#getPixelFormat)) για το νέο [Bitmap](../../com.aspose.drawing/bitmap). |

### Bitmap(int width, int height, int stride, int format, int[] data) {#Bitmap-int-int-int-int-int---}
```
public Bitmap(int width, int height, int stride, int format, int[] data)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [Bitmap](../../com.aspose.drawing/bitmap) με το καθορισμένο μέγεθος και δεδομένα εικονοστοιχείων.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| width | int | Το πλάτος, σε pixel, του νέου [Bitmap](../../com.aspose.drawing/bitmap). |
| height | int | Το ύψος, σε pixel, του νέου [Bitmap](../../com.aspose.drawing/bitmap). |
| stride | int | Η μετατόπιση σε byte μεταξύ της αρχής μιας γραμμής σάρωσης και της επόμενης, πρέπει να είναι πολλαπλάσιο του τεσσάρων. |
| format | int | Η απαρίθμηση `PixelFormat`([Image.getPixelFormat](../../com.aspose.drawing/image\#getPixelFormat)) για το νέο [Bitmap](../../com.aspose.drawing/bitmap). |
| δεδομένα | int[] | Τα δεδομένα pixel. |

### Bitmap(Image original) {#Bitmap-com.aspose.drawing.Image-}
```
public Bitmap(Image original)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [Bitmap](../../com.aspose.drawing/bitmap) από την καθορισμένη υπάρχουσα εικόνα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| original | [Image](../../com.aspose.drawing/image) | Το [Image](../../com.aspose.drawing/image) από το οποίο δημιουργείται το νέο [Bitmap](../../com.aspose.drawing/bitmap). |

### Bitmap(Image original, Size newSize) {#Bitmap-com.aspose.drawing.Image-com.aspose.drawing.Size-}
```
public Bitmap(Image original, Size newSize)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [Bitmap](../../com.aspose.drawing/bitmap) από την καθορισμένη υπάρχουσα εικόνα, κλιμακωμένη στο καθορισμένο μέγεθος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| original | [Image](../../com.aspose.drawing/image) | Το [Image](../../com.aspose.drawing/image) από το οποίο δημιουργείται το νέο [Bitmap](../../com.aspose.drawing/bitmap) |
| newSize | [Size](../../com.aspose.drawing/size) | Η δομή `Size`([Image.getSize](../../com.aspose.drawing/image\#getSize)) που αντιπροσωπεύει το μέγεθος του νέου [Bitmap](../../com.aspose.drawing/bitmap). |

### Bitmap(Image original, int width, int height) {#Bitmap-com.aspose.drawing.Image-int-int-}
```
public Bitmap(Image original, int width, int height)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [Bitmap](../../com.aspose.drawing/bitmap) από την καθορισμένη υπάρχουσα εικόνα, κλιμακωμένη στο καθορισμένο μέγεθος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| original | [Image](../../com.aspose.drawing/image) | Το [Image](../../com.aspose.drawing/image) από το οποίο δημιουργείται το νέο [Bitmap](../../com.aspose.drawing/bitmap). |
| width | int | Το πλάτος, σε pixel, του νέου [Bitmap](../../com.aspose.drawing/bitmap). |
| height | int | Το ύψος, σε pixel, του νέου [Bitmap](../../com.aspose.drawing/bitmap). |

### getWidth() {#getWidth--}
```
public int getWidth()
```


Επιστρέφει το πλάτος, σε εικονοστοιχεία, αυτού του Bitmap.

**Returns:**
int
### getHeight() {#getHeight--}
```
public int getHeight()
```


Επιστρέφει το ύψος, σε εικονοστοιχεία, αυτού του Bitmap.

**Returns:**
int
### getRawFormat() {#getRawFormat--}
```
public ImageFormat getRawFormat()
```


Λαμβάνει τη μορφή αρχείου αυτού του [Image](../../com.aspose.drawing/image).

**Returns:**
[ImageFormat](../../com.aspose.drawing.imaging/imageformat) - The [ImageFormat](../../com.aspose.drawing.imaging/imageformat) that represents the file format of this [Image](../../com.aspose.drawing/image).
### getPixelFormat() {#getPixelFormat--}
```
public int getPixelFormat()
```


Λαμβάνει τη μορφή εικονοστοιχείου για αυτό το [Image](../../com.aspose.drawing/image).

**Returns:**
int - Ένα `PixelFormat`([Image.getPixelFormat](../../com.aspose.drawing/image\#getPixelFormat)) που αντιπροσωπεύει τη μορφή εικονοστοιχείου για αυτό το [Image](../../com.aspose.drawing/image).
### getPalette() {#getPalette--}
```
public ColorPalette getPalette()
```


Λαμβάνει ή ορίζει την παλέτα χρωμάτων που χρησιμοποιείται για αυτό το [Image](../../com.aspose.drawing/image).

**Returns:**
[ColorPalette](../../com.aspose.drawing.imaging/colorpalette) - A [ColorPalette](../../com.aspose.drawing.imaging/colorpalette) that represents the color palette used for this [Image](../../com.aspose.drawing/image).
### setPalette(ColorPalette value) {#setPalette-com.aspose.drawing.imaging.ColorPalette-}
```
public void setPalette(ColorPalette value)
```


Λαμβάνει ή ορίζει την παλέτα χρωμάτων που χρησιμοποιείται για αυτό το [Image](../../com.aspose.drawing/image).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [ColorPalette](../../com.aspose.drawing.imaging/colorpalette) |  |

### getFrameDimensionsList() {#getFrameDimensionsList--}
```
public UUID[] getFrameDimensionsList()
```


Λαμβάνει έναν πίνακα GUID που αντιπροσωπεύουν τις διαστάσεις των πλαισίων εντός αυτού του [Image](../../com.aspose.drawing/image).

**Returns:**
java.util.UUID[] - Ένας πίνακας GUID που καθορίζουν τις διαστάσεις των πλαισίων μέσα σε αυτό το [Image](../../com.aspose.drawing/image) από το πιο σημαντικό στο λιγότερο σημαντικό.
### getPropertyIdList() {#getPropertyIdList--}
```
public int[] getPropertyIdList()
```


Λαμβάνει τα αναγνωριστικά των στοιχείων ιδιοτήτων που αποθηκεύονται σε αυτό το [Image](../../com.aspose.drawing/image).

**Returns:**
int[] - Ένας πίνακας των αναγνωριστικών ιδιοτήτων, ένας για κάθε στοιχείο ιδιότητας που αποθηκεύεται σε αυτήν την εικόνα.
### getPropertyItems() {#getPropertyItems--}
```
public PropertyItem[] getPropertyItems()
```


Λαμβάνει όλα τα στοιχεία ιδιοτήτων (τμήματα μεταδεδομένων) που αποθηκεύονται σε αυτό το [Image](../../com.aspose.drawing/image).

**Returns:**
com.aspose.drawing.imaging.PropertyItem[] - Ένας πίνακας αντικειμένων [PropertyItem](../../com.aspose.drawing.imaging/propertyitem) , ένας για κάθε στοιχείο ιδιότητας που αποθηκεύεται στην εικόνα.
### deepClone(Rectangle rect, int format) {#deepClone-com.aspose.drawing.Rectangle-int-}
```
public final Bitmap deepClone(Rectangle rect, int format)
```


Δημιουργεί ένα αντίγραφο του τμήματος αυτού του [Bitmap](../../com.aspose.drawing/bitmap) που ορίζεται από τη δομή [Rectangle](../../com.aspose.drawing/rectangle) και με καθορισμένο `PixelFormat`([Image.getPixelFormat](../../com.aspose.drawing/image\#getPixelFormat)) αρίθμηση.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | Ορίζει το τμήμα αυτού του [Bitmap](../../com.aspose.drawing/bitmap) που θα αντιγραφεί. Οι συντεταγμένες είναι σχετικές με αυτό το [Bitmap](../../com.aspose.drawing/bitmap). |
| format | int | Καθορίζει την απαρίθμηση `PixelFormat`([Image.getPixelFormat](../../com.aspose.drawing/image\#getPixelFormat)) για το προορισμό [Bitmap](../../com.aspose.drawing/bitmap). |

**Returns:**
[Bitmap](../../com.aspose.drawing/bitmap) - The new [Bitmap](../../com.aspose.drawing/bitmap) that this method creates.
### deepClone(RectangleF rect, int format) {#deepClone-com.aspose.drawing.RectangleF-int-}
```
public final Bitmap deepClone(RectangleF rect, int format)
```


Δημιουργεί ένα αντίγραφο του τμήματος αυτού του [Bitmap](../../com.aspose.drawing/bitmap) που ορίζεται με καθορισμένο [PixelFormat](../../com.aspose.drawing.imaging/pixelformat) αρίθμηση.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | Ορίζει το τμήμα αυτού του [Bitmap](../../com.aspose.drawing/bitmap) που θα αντιγραφεί. |
| format | int | Καθορίζει την απαρίθμηση [PixelFormat](../../com.aspose.drawing.imaging/pixelformat) για το προορισμό [Bitmap](../../com.aspose.drawing/bitmap). |

**Returns:**
[Bitmap](../../com.aspose.drawing/bitmap) - The [Bitmap](../../com.aspose.drawing/bitmap) that this method creates.
### setResolution(float xDpi, float yDpi) {#setResolution-float-float-}
```
public final void setResolution(float xDpi, float yDpi)
```


Ορίζει την ανάλυση για αυτό το [Bitmap](../../com.aspose.drawing/bitmap).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| xDpi | float | Η οριζόντια ανάλυση, σε κουκκίδες ανά ίντσα, του [Bitmap](../../com.aspose.drawing/bitmap). |
| yDpi | float | Η κάθετη ανάλυση, σε κουκκίδες ανά ίντσα, του [Bitmap](../../com.aspose.drawing/bitmap). |

### lockBits(Rectangle rect, int flags, int format) {#lockBits-com.aspose.drawing.Rectangle-int-int-}
```
public final BitmapData lockBits(Rectangle rect, int flags, int format)
```


Κλειδώνει ένα [Bitmap](../../com.aspose.drawing/bitmap) στη μνήμη του συστήματος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | Μια δομή [Rectangle](../../com.aspose.drawing/rectangle) που καθορίζει το τμήμα του [Bitmap](../../com.aspose.drawing/bitmap) που θα κλειδωθεί. |
| flags | int | Μια απαρίθμηση [ImageLockMode](../../com.aspose.drawing.imaging/imagelockmode) που καθορίζει το επίπεδο πρόσβασης (ανάγνωση/εγγραφή) για το [Bitmap](../../com.aspose.drawing/bitmap). |
| format | int | Μια απαρίθμηση `PixelFormat`([Image.getPixelFormat](../../com.aspose.drawing/image\#getPixelFormat)) που καθορίζει τη μορφή δεδομένων αυτού του [Bitmap](../../com.aspose.drawing/bitmap). |

**Returns:**
[BitmapData](../../com.aspose.drawing.imaging/bitmapdata) - A [BitmapData](../../com.aspose.drawing.imaging/bitmapdata) containing information about this lock operation.
### unlockBits(BitmapData bitmapData) {#unlockBits-com.aspose.drawing.imaging.BitmapData-}
```
public final void unlockBits(BitmapData bitmapData)
```


Ξεκλειδώνει αυτό το [Bitmap](../../com.aspose.drawing/bitmap) από τη μνήμη του συστήματος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| bitmapData | [BitmapData](../../com.aspose.drawing.imaging/bitmapdata) | Ένα [BitmapData](../../com.aspose.drawing.imaging/bitmapdata) που καθορίζει πληροφορίες σχετικά με τη λειτουργία κλειδώματος. |

### getPixel(int x, int y) {#getPixel-int-int-}
```
public final Color getPixel(int x, int y)
```


Λαμβάνει το χρώμα του καθορισμένου pixel σε αυτό το [Bitmap](../../com.aspose.drawing/bitmap).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | int | Η συντεταγμένη x του pixel που θα ανακτηθεί. |
| y | int | Η συντεταγμένη y του pixel που θα ανακτηθεί. |

**Returns:**
[Color](../../com.aspose.drawing/color) - A [Color](../../com.aspose.drawing/color) structure that represents the color of the specified pixel.
### setPixel(int x, int y, Color color) {#setPixel-int-int-com.aspose.drawing.Color-}
```
public final void setPixel(int x, int y, Color color)
```


Ορίζει το χρώμα του καθορισμένου pixel σε αυτό το [Bitmap](../../com.aspose.drawing/bitmap).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | int | Η συντεταγμένη x του pixel που θα οριστεί. |
| y | int | Η συντεταγμένη y του pixel που θα οριστεί. |
| color | [Color](../../com.aspose.drawing/color) | Μια δομή [Color](../../com.aspose.drawing/color) που αντιπροσωπεύει το χρώμα που θα εκχωρηθεί στο συγκεκριμένο pixel. |

### readArgb32Pixels(int[] pixels) {#readArgb32Pixels-int---}
```
public final void readArgb32Pixels(int[] pixels)
```


Διαβάζει τα pixel του bitmap σε μορφή ARGB32 σε έναν δοσμένο πίνακα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pixel | int[] | Πίνακας για την τοποθέτηση pixel bitmap. Πρέπει να έχει επαρκή χωρητικότητα. |

### writeArgb32Pixels(int[] pixels) {#writeArgb32Pixels-int---}
```
public final void writeArgb32Pixels(int[] pixels)
```


Γράφει pixel στο bitmap.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pixel | int[] | Πίνακας με πηγές pixel σε μορφή ARGB32. Πρέπει να έχει επαρκές μήκος. |

### makeTransparent() {#makeTransparent--}
```
public final void makeTransparent()
```


Κάνει το καθορισμένο χρώμα διαφανές για αυτό το [Bitmap](../../com.aspose.drawing/bitmap).

### makeTransparent(Color transparentColor) {#makeTransparent-com.aspose.drawing.Color-}
```
public final void makeTransparent(Color transparentColor)
```


Κάνει το καθορισμένο χρώμα διαφανές για αυτό το [Bitmap](../../com.aspose.drawing/bitmap).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| transparentColor | [Color](../../com.aspose.drawing/color) | Η δομή [Color](../../com.aspose.drawing/color) που αντιπροσωπεύει το χρώμα που θα γίνει διαφανές. |

### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


Αυτή η μέθοδος περιστρέφει, αναστρέφει ή περιστρέφει και αναστρέφει το [Image](../../com.aspose.drawing/image).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rotateFlipType | int | Ένα μέλος [RotateFlipType](../../com.aspose.drawing/rotatefliptype) που καθορίζει τον τύπο περιστροφής και αναστροφής που θα εφαρμοστεί στην εικόνα. |

### getPropertyItem(int propid) {#getPropertyItem-int-}
```
public PropertyItem getPropertyItem(int propid)
```


Λαμβάνει το καθορισμένο στοιχείο ιδιότητας από αυτό το [Image](../../com.aspose.drawing/image).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| propid | int | Το αναγνωριστικό του στοιχείου ιδιότητας για λήψη. |

**Returns:**
[PropertyItem](../../com.aspose.drawing.imaging/propertyitem) - The [PropertyItem](../../com.aspose.drawing.imaging/propertyitem) this method gets.
### removePropertyItem(int propid) {#removePropertyItem-int-}
```
public void removePropertyItem(int propid)
```


Αφαιρεί το καθορισμένο στοιχείο ιδιότητας από αυτό το [Image](../../com.aspose.drawing/image).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| propid | int | Το αναγνωριστικό του στοιχείου ιδιότητας για αφαίρεση. |

### setPropertyItem(PropertyItem propitem) {#setPropertyItem-com.aspose.drawing.imaging.PropertyItem-}
```
public void setPropertyItem(PropertyItem propitem)
```


Αποθηκεύει ένα στοιχείο ιδιότητας (τμήμα μεταδεδομένων) σε αυτό το [Image](../../com.aspose.drawing/image).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| propitem | [PropertyItem](../../com.aspose.drawing.imaging/propertyitem) | Το [PropertyItem](../../com.aspose.drawing.imaging/propertyitem) που θα αποθηκευτεί. |

