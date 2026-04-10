---
title: Μετααρχείο
second_title: Αναφορά API του Aspose.Drawing for Java
description: Ορίζει ένα γραφικό metafile.
type: docs
weight: 30
url: /el/java/com.aspose.drawing.imaging/metafile/
---
**Inheritance:**
java.lang.Object, [com.aspose.drawing.Image](../../com.aspose.drawing/image)
```
public final class Metafile extends Image
```

Ορίζει ένα γραφικό μετααρχείο. Ένα μετααρχείο περιέχει εγγραφές που περιγράφουν μια ακολουθία λειτουργιών γραφικών που μπορούν να καταγραφούν (να δημιουργηθούν) και να αναπαραχθούν (να εμφανιστούν). Αυτή η κλάση δεν είναι κληρονομήσιμη.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [Metafile(byte[] henhmetafile, boolean deleteEmf)](#Metafile-byte---boolean-) | Αρχικοποιεί μια νέα παρουσία της κλάσης [Metafile](../../com.aspose.drawing.imaging/metafile) από το καθορισμένο χειριστή. |
| [Metafile(byte[] referenceHdc, int emfType)](#Metafile-byte---int-) | Αρχικοποιεί μια νέα παρουσία της κλάσης [Metafile](../../com.aspose.drawing.imaging/metafile) από το καθορισμένο χειριστή προς ένα περιβάλλον συσκευής και μια απαρίθμηση [EmfType](../../com.aspose.drawing.imaging/emftype) που καθορίζει τη μορφή του [Metafile](../../com.aspose.drawing.imaging/metafile). |
| [Metafile(String filename)](#Metafile-java.lang.String-) | Αρχικοποιεί μια νέα παρουσία της κλάσης [Metafile](../../com.aspose.drawing.imaging/metafile) από το καθορισμένο όνομα αρχείου. |
| [Metafile(String filename, byte[] referenceHdc)](#Metafile-java.lang.String-byte---) | Αρχικοποιεί μια νέα παρουσία της κλάσης [Metafile](../../com.aspose.drawing.imaging/metafile) από το καθορισμένο όνομα αρχείου. |
| [Metafile(InputStream stream)](#Metafile-java.io.InputStream-) | Αρχικοποιεί μια νέα παρουσία της κλάσης [Metafile](../../com.aspose.drawing.imaging/metafile) από τη καθορισμένη ροή δεδομένων. |
| [Metafile(InputStream stream, byte[] referenceHdc)](#Metafile-java.io.InputStream-byte---) | Αρχικοποιεί μια νέα παρουσία της κλάσης [Metafile](../../com.aspose.drawing.imaging/metafile) από τη καθορισμένη ροή δεδομένων και έναν χειριστή Windows προς ένα περιβάλλον συσκευής. |
| [Metafile(System.IO.Stream stream, int type)](#Metafile-com.aspose.ms.System.IO.Stream-int-) | Αρχικοποιεί μια νέα παρουσία της κλάσης [Metafile](../../com.aspose.drawing.imaging/metafile) από τη καθορισμένη ροή δεδομένων και έναν χειριστή Windows προς ένα περιβάλλον συσκευής. |
| [Metafile(InputStream stream, byte[] referenceHdc, int type)](#Metafile-java.io.InputStream-byte---int-) | Αρχικοποιεί μια νέα παρουσία της κλάσης [Metafile](../../com.aspose.drawing.imaging/metafile) από τη καθορισμένη ροή δεδομένων, έναν χειριστή Windows προς ένα περιβάλλον συσκευής και μια απαρίθμηση [EmfType](../../com.aspose.drawing.imaging/emftype) που καθορίζει τη μορφή του [Metafile](../../com.aspose.drawing.imaging/metafile). |
| [Metafile(InputStream stream, byte[] referenceHdc, RectangleF frameRect, int frameUnit, int type)](#Metafile-java.io.InputStream-byte---com.aspose.drawing.RectangleF-int-int-) | Αρχικοποιεί μια νέα παρουσία της κλάσης [Metafile](../../com.aspose.drawing.imaging/metafile) από τη καθορισμένη ροή δεδομένων, έναν χειριστή Windows προς ένα περιβάλλον συσκευής και μια απαρίθμηση [EmfType](../../com.aspose.drawing.imaging/emftype) που καθορίζει τη μορφή του [Metafile](../../com.aspose.drawing.imaging/metafile). |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getWidth()](#getWidth--) | Λαμβάνει το πλάτος, σε εικονοστοιχεία, αυτού του [Metafile](../../com.aspose.drawing.imaging/metafile). |
| [getHeight()](#getHeight--) | Λαμβάνει το ύψος, σε εικονοστοιχεία, αυτού του [Metafile](../../com.aspose.drawing.imaging/metafile). |
| [getRawFormat()](#getRawFormat--) | Λαμβάνει τη μορφή αρχείου αυτού του [Image](../../com.aspose.drawing/image). |
| [getPixelFormat()](#getPixelFormat--) | Λαμβάνει τη μορφή εικονοστοιχείου για αυτό το [Image](../../com.aspose.drawing/image). |
| [getPalette()](#getPalette--) | Λαμβάνει ή ορίζει την παλέτα χρωμάτων που χρησιμοποιείται για αυτό το [Image](../../com.aspose.drawing/image). |
| [setPalette(ColorPalette value)](#setPalette-com.aspose.drawing.imaging.ColorPalette-) | Λαμβάνει ή ορίζει την παλέτα χρωμάτων που χρησιμοποιείται για αυτό το [Image](../../com.aspose.drawing/image). |
| [getFrameDimensionsList()](#getFrameDimensionsList--) | Λαμβάνει έναν πίνακα GUID που αντιπροσωπεύουν τις διαστάσεις των πλαισίων εντός αυτού του [Image](../../com.aspose.drawing/image). |
| [getPropertyIdList()](#getPropertyIdList--) | Λαμβάνει τα αναγνωριστικά των στοιχείων ιδιοτήτων που αποθηκεύονται σε αυτό το [Image](../../com.aspose.drawing/image). |
| [getPropertyItems()](#getPropertyItems--) | Λαμβάνει όλα τα στοιχεία ιδιοτήτων (τμήματα μεταδεδομένων) που αποθηκεύονται σε αυτό το [Image](../../com.aspose.drawing/image). |
| [getMetafileHeader(InputStream stream)](#getMetafileHeader-java.io.InputStream-) | Επιστρέφει το [MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) που σχετίζεται με το καθορισμένο [Metafile](../../com.aspose.drawing.imaging/metafile). |
| [getMetafileHeader(String fileName)](#getMetafileHeader-java.lang.String-) | Επιστρέφει το [MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) που σχετίζεται με το καθορισμένο [Metafile](../../com.aspose.drawing.imaging/metafile). |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | Αυτή η μέθοδος περιστρέφει, αναστρέφει ή περιστρέφει και αναστρέφει το [Image](../../com.aspose.drawing/image). |
| [getHenhmetafile()](#getHenhmetafile--) | Επιστρέφει έναν χειριστή Windows σε ένα βελτιωμένο [Metafile](../../com.aspose.drawing.imaging/metafile). |
| [playRecord(int recordType, int flags, int dataSize, byte[] dataArray)](#playRecord-int-int-int-byte---) | Αναπαράγει μια μεμονωμένη εγγραφή μετααρχείου. |
| [getMetafileHeader()](#getMetafileHeader--) | Επιστρέφει το [MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) που σχετίζεται με αυτό το [Metafile](../../com.aspose.drawing.imaging/metafile). |
| [getPropertyItem(int propid)](#getPropertyItem-int-) | Λαμβάνει το καθορισμένο στοιχείο ιδιότητας από αυτό το [Image](../../com.aspose.drawing/image). |
| [removePropertyItem(int propid)](#removePropertyItem-int-) | Αφαιρεί το καθορισμένο στοιχείο ιδιότητας από αυτό το [Image](../../com.aspose.drawing/image). |
| [setPropertyItem(PropertyItem propitem)](#setPropertyItem-com.aspose.drawing.imaging.PropertyItem-) | Αποθηκεύει ένα στοιχείο ιδιότητας (τμήμα μεταδεδομένων) σε αυτό το [Image](../../com.aspose.drawing/image). |
### Metafile(byte[] henhmetafile, boolean deleteEmf) {#Metafile-byte---boolean-}
```
public Metafile(byte[] henhmetafile, boolean deleteEmf)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [Metafile](../../com.aspose.drawing.imaging/metafile) από το καθορισμένο χειριστή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| henhmetafile | byte[] | Μια αναφορά σε ένα βελτιωμένο μετααρχείο. |
| deleteEmf | boolean | αληθές για τη διαγραφή της αναφοράς του βελτιωμένου μετααρχείου όταν το [Metafile](../../com.aspose.drawing.imaging/metafile) διαγραφεί· διαφορετικά, ψευδές. |

### Metafile(byte[] referenceHdc, int emfType) {#Metafile-byte---int-}
```
public Metafile(byte[] referenceHdc, int emfType)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [Metafile](../../com.aspose.drawing.imaging/metafile) από το καθορισμένο χειριστή προς ένα περιβάλλον συσκευής και μια απαρίθμηση [EmfType](../../com.aspose.drawing.imaging/emftype) που καθορίζει τη μορφή του [Metafile](../../com.aspose.drawing.imaging/metafile).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| referenceHdc | byte[] | Η αναφορά σε ένα περιβάλλον συσκευής. |
| emfType | int | Ένα [EmfType](../../com.aspose.drawing.imaging/emftype) που καθορίζει τη μορφή του [Metafile](../../com.aspose.drawing.imaging/metafile). |

### Metafile(String filename) {#Metafile-java.lang.String-}
```
public Metafile(String filename)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [Metafile](../../com.aspose.drawing.imaging/metafile) από το καθορισμένο όνομα αρχείου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filename | java.lang.String | Μια συμβολοσειρά που αντιπροσωπεύει το όνομα αρχείου από το οποίο θα δημιουργηθεί το νέο [Metafile](../../com.aspose.drawing.imaging/metafile). |

### Metafile(String filename, byte[] referenceHdc) {#Metafile-java.lang.String-byte---}
```
public Metafile(String filename, byte[] referenceHdc)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [Metafile](../../com.aspose.drawing.imaging/metafile) από το καθορισμένο όνομα αρχείου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filename | java.lang.String | Μια συμβολοσειρά που αντιπροσωπεύει το όνομα αρχείου από το οποίο θα δημιουργηθεί το νέο [Metafile](../../com.aspose.drawing.imaging/metafile). |
| referenceHdc | byte[] | Μια αναφορά Windows σε ένα περιβάλλον συσκευής. |

### Metafile(InputStream stream) {#Metafile-java.io.InputStream-}
```
public Metafile(InputStream stream)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [Metafile](../../com.aspose.drawing.imaging/metafile) από τη καθορισμένη ροή δεδομένων.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.InputStream | Το InputStream από το οποίο θα δημιουργηθεί το νέο [Metafile](../../com.aspose.drawing.imaging/metafile). |

### Metafile(InputStream stream, byte[] referenceHdc) {#Metafile-java.io.InputStream-byte---}
```
public Metafile(InputStream stream, byte[] referenceHdc)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [Metafile](../../com.aspose.drawing.imaging/metafile) από τη συγκεκριμένη ροή δεδομένων και μια αναφορά Windows σε ένα περιβάλλον συσκευής. />.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.InputStream | Ένα InputStream που περιέχει τα δεδομένα για αυτό το [Metafile](../../com.aspose.drawing.imaging/metafile). |
| referenceHdc | byte[] | Μια αναφορά Windows σε ένα περιβάλλον συσκευής του αντικειμένου [Metafile](../../com.aspose.drawing.imaging/metafile). |

### Metafile(System.IO.Stream stream, int type) {#Metafile-com.aspose.ms.System.IO.Stream-int-}
```
public Metafile(System.IO.Stream stream, int type)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [Metafile](../../com.aspose.drawing.imaging/metafile) από τη συγκεκριμένη ροή δεδομένων και μια αναφορά Windows σε ένα περιβάλλον συσκευής. />.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | Ένα InputStream που περιέχει τα δεδομένα για αυτό το [Metafile](../../com.aspose.drawing.imaging/metafile). |
| τύπος | int | πρέπει να είναι int 1. |

### Metafile(InputStream stream, byte[] referenceHdc, int type) {#Metafile-java.io.InputStream-byte---int-}
```
public Metafile(InputStream stream, byte[] referenceHdc, int type)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [Metafile](../../com.aspose.drawing.imaging/metafile) από τη καθορισμένη ροή δεδομένων, έναν χειριστή Windows προς ένα περιβάλλον συσκευής και μια απαρίθμηση [EmfType](../../com.aspose.drawing.imaging/emftype) που καθορίζει τη μορφή του [Metafile](../../com.aspose.drawing.imaging/metafile).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.InputStream | Ένα InputStream που περιέχει τα δεδομένα για αυτό το [Metafile](../../com.aspose.drawing.imaging/metafile). |
| referenceHdc | byte[] | Μια αναφορά Windows σε ένα περιβάλλον συσκευής. |
| type | int | Ένα [EmfType](../../com.aspose.drawing.imaging/emftype) που καθορίζει τη μορφή του [Metafile](../../com.aspose.drawing.imaging/metafile). |

### Metafile(InputStream stream, byte[] referenceHdc, RectangleF frameRect, int frameUnit, int type) {#Metafile-java.io.InputStream-byte---com.aspose.drawing.RectangleF-int-int-}
```
public Metafile(InputStream stream, byte[] referenceHdc, RectangleF frameRect, int frameUnit, int type)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [Metafile](../../com.aspose.drawing.imaging/metafile) από τη καθορισμένη ροή δεδομένων, έναν χειριστή Windows προς ένα περιβάλλον συσκευής και μια απαρίθμηση [EmfType](../../com.aspose.drawing.imaging/emftype) που καθορίζει τη μορφή του [Metafile](../../com.aspose.drawing.imaging/metafile).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.InputStream | Ένα InputStream που περιέχει τα δεδομένα για αυτό το [Metafile](../../com.aspose.drawing.imaging/metafile). |
| referenceHdc | byte[] | Μια αναφορά Windows σε ένα περιβάλλον συσκευής. |
| frameRect | [RectangleF](../../com.aspose.drawing/rectanglef) | Ένα [Rectangle](../../com.aspose.drawing/rectangle) που αντιπροσωπεύει το ορθογώνιο που περιβάλλει το νέο [Metafile](../../com.aspose.drawing.imaging/metafile). |
| frameUnit | int | Ένα [MetafileFrameUnit](../../com.aspose.drawing.imaging/metafileframeunit) που καθορίζει τη μονάδα μέτρησης για το frameRect. |
| type | int | Ένα [EmfType](../../com.aspose.drawing.imaging/emftype) που καθορίζει τη μορφή του [Metafile](../../com.aspose.drawing.imaging/metafile). |

### getWidth() {#getWidth--}
```
public int getWidth()
```


Λαμβάνει το πλάτος, σε εικονοστοιχεία, αυτού του [Metafile](../../com.aspose.drawing.imaging/metafile).

**Returns:**
int
### getHeight() {#getHeight--}
```
public int getHeight()
```


Λαμβάνει το ύψος, σε εικονοστοιχεία, αυτού του [Metafile](../../com.aspose.drawing.imaging/metafile).

**Returns:**
int - το ύψος, σε εικονοστοιχεία, του [Metafile](../../com.aspose.drawing.imaging/metafile).
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
### getMetafileHeader(InputStream stream) {#getMetafileHeader-java.io.InputStream-}
```
public static MetafileHeader getMetafileHeader(InputStream stream)
```


Επιστρέφει το [MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) που σχετίζεται με το καθορισμένο [Metafile](../../com.aspose.drawing.imaging/metafile).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.InputStream | Ένα InputStream που περιέχει το [Metafile](../../com.aspose.drawing.imaging/metafile) για το οποίο ανακτάται μια κεφαλίδα. |

**Returns:**
[MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) - The [MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) associated with the specified [Metafile](../../com.aspose.drawing.imaging/metafile).
### getMetafileHeader(String fileName) {#getMetafileHeader-java.lang.String-}
```
public static MetafileHeader getMetafileHeader(String fileName)
```


Επιστρέφει το [MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) που σχετίζεται με το καθορισμένο [Metafile](../../com.aspose.drawing.imaging/metafile).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fileName | java.lang.String | Μια συμβολοσειρά που περιέχει το όνομα του [Metafile](../../com.aspose.drawing.imaging/metafile) για το οποίο ανακτάται μια κεφαλίδα. |

**Returns:**
[MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) - The [MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) associated with the specified [Metafile](../../com.aspose.drawing.imaging/metafile).
### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


Αυτή η μέθοδος περιστρέφει, αναστρέφει ή περιστρέφει και αναστρέφει το [Image](../../com.aspose.drawing/image).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rotateFlipType | int | Ένα μέλος [RotateFlipType](../../com.aspose.drawing/rotatefliptype) που καθορίζει τον τύπο περιστροφής και αναστροφής που θα εφαρμοστεί στην εικόνα. |

### getHenhmetafile() {#getHenhmetafile--}
```
public System.IntPtr getHenhmetafile()
```


Επιστρέφει έναν χειριστή Windows σε ένα βελτιωμένο [Metafile](../../com.aspose.drawing.imaging/metafile).

**Returns:**
com.aspose.ms.System.IntPtr - Μια αναφορά Windows σε αυτό το βελτιωμένο [Metafile](../../com.aspose.drawing.imaging/metafile).
### playRecord(int recordType, int flags, int dataSize, byte[] dataArray) {#playRecord-int-int-int-byte---}
```
public void playRecord(int recordType, int flags, int dataSize, byte[] dataArray)
```


Αναπαράγει μια μεμονωμένη εγγραφή μετααρχείου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| recordType | int | Στοιχείο του [EmfPlusRecordType](../../com.aspose.drawing.imaging/emfplusrecordtype) που καθορίζει τον τύπο της εγγραφής μετααρχειοτύπου που εκτελείται. |
| flags | int | Ένα σύνολο σημαιών που καθορίζουν τα χαρακτηριστικά της εγγραφής. |
| dataSize | int | Ο αριθμός των byte στα δεδομένα της εγγραφής. |
| dataArray | byte[] | Ένας πίνακας byte που περιέχει τα δεδομένα της εγγραφής. |

### getMetafileHeader() {#getMetafileHeader--}
```
public MetafileHeader getMetafileHeader()
```


Επιστρέφει το [MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) που σχετίζεται με αυτό το [Metafile](../../com.aspose.drawing.imaging/metafile).

**Returns:**
[MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) - The [MetafileHeader](../../com.aspose.drawing.imaging/metafileheader) associated with this [Metafile](../../com.aspose.drawing.imaging/metafile).
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

