---
title: Icon
second_title: Αναφορά API του Aspose.Drawing for Java
description: Αντιπροσωπεύει ένα εικονίδιο Windows που είναι μια μικρή bitmap εικόνα που χρησιμοποιείται για την αναπαράσταση ενός αντικειμένου.
type: docs
weight: 29
url: /el/java/com.aspose.drawing/icon/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.ms.System.IDisposable
```
public final class Icon implements System.ICloneable, System.IDisposable
```

Αντιπροσωπεύει ένα εικονίδιο Windows, το οποίο είναι μια μικρή bitmap εικόνα που χρησιμοποιείται για την αναπαράσταση ενός αντικειμένου. Τα εικονίδια μπορούν να θεωρηθούν ως διαφανή bitmap, αν και το μέγεθός τους καθορίζεται από το σύστημα.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [Icon(String fileName)](#Icon-java.lang.String-) | Αρχικοποιεί μια νέα παρουσία της κλάσης [Icon](../../com.aspose.drawing/icon) από το καθορισμένο όνομα αρχείου. |
| [Icon(InputStream stream)](#Icon-java.io.InputStream-) | Αρχικοποιεί μια νέα παρουσία της κλάσης [Icon](../../com.aspose.drawing/icon) από τη συγκεκριμένη ροή δεδομένων. |
| [Icon(String fileName, Size size)](#Icon-java.lang.String-com.aspose.drawing.Size-) | Αρχικοποιεί μια νέα παρουσία της κλάσης [Icon](../../com.aspose.drawing/icon) του καθορισμένου μεγέθους από το καθορισμένο αρχείο. |
| [Icon(Icon original, Size size)](#Icon-com.aspose.drawing.Icon-com.aspose.drawing.Size-) | Αρχικοποιεί μια νέα παρουσία της κλάσης [Icon](../../com.aspose.drawing/icon) και προσπαθεί να βρει μια έκδοση του εικονιδίου που ταιριάζει στο ζητούμενο μέγεθος. |
| [Icon(Object type, String resource)](#Icon-java.lang.Object-java.lang.String-) | Αρχικοποιεί μια νέα παρουσία της κλάσης [Icon](../../com.aspose.drawing/icon) από έναν πόρο στην καθορισμένη συναρμολόγηση. |
| [Icon(InputStream stream, Size size)](#Icon-java.io.InputStream-com.aspose.drawing.Size-) | Αρχικοποιεί μια νέα παρουσία της κλάσης [Icon](../../com.aspose.drawing/icon) του καθορισμένου μεγέθους από τη συγκεκριμένη ροή. |
| [Icon(String fileName, int width, int height)](#Icon-java.lang.String-int-int-) | Αρχικοποιεί μια νέα παρουσία της κλάσης [Icon](../../com.aspose.drawing/icon) με το καθορισμένο πλάτος και ύψος από το καθορισμένο αρχείο. |
| [Icon(Icon original, int width, int height)](#Icon-com.aspose.drawing.Icon-int-int-) | Αρχικοποιεί μια νέα παρουσία της κλάσης [Icon](../../com.aspose.drawing/icon) και προσπαθεί να βρει μια έκδοση του εικονιδίου που ταιριάζει στο ζητούμενο μέγεθος. |
| [Icon(InputStream stream, int width, int height)](#Icon-java.io.InputStream-int-int-) | Αρχικοποιεί μια νέα παρουσία της κλάσης [Icon](../../com.aspose.drawing/icon) από το καθορισμένο ροή δεδομένων και με το καθορισμένο πλάτος και ύψος. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getHandle()](#getHandle--) | Αποκτά το αναγνωριστικό (handle) για αυτό το [Icon](../../com.aspose.drawing/icon). |
| [getHeight()](#getHeight--) | Αποκτά το ύψος αυτού του [Icon](../../com.aspose.drawing/icon). |
| [getSize()](#getSize--) | Αποκτά το μέγεθος αυτού του [Icon](../../com.aspose.drawing/icon). |
| [getWidth()](#getWidth--) | Αποκτά το πλάτος αυτού του [Icon](../../com.aspose.drawing/icon). |
| [extractAssociatedIcon(String filePath)](#extractAssociatedIcon-java.lang.String-) | Επιστρέφει μια αναπαράσταση εικονιδίου μιας εικόνας που περιέχεται στο καθορισμένο αρχείο. |
| [fromHandle(byte[] handle)](#fromHandle-byte---) | Δημιουργεί ένα GDI+ [Icon](../../com.aspose.drawing/icon) από το καθορισμένο αναγνωριστικό Windows για ένα εικονίδιο (HICON). |
| [deepClone()](#deepClone--) | Κλωνοποιεί το [Icon](../../com.aspose.drawing/icon), δημιουργώντας μια αντίγραφο εικόνας. |
| [dispose()](#dispose--) | Εκτελεί εργασίες ορισμένες από την εφαρμογή που σχετίζονται με την απελευθέρωση, την αποδέσμευση ή την επαναφορά μη διαχειριζόμενων πόρων. |
| [save(OutputStream outputStream)](#save-java.io.OutputStream-) | Αποθηκεύει αυτό το [Icon](../../com.aspose.drawing/icon) στην καθορισμένη έξοδο java.io.InputStream. |
| [toBitmap()](#toBitmap--) | Μετατρέπει αυτό το [Icon](../../com.aspose.drawing/icon) σε ένα GDI+ [Bitmap](../../com.aspose.drawing/bitmap). |
| [toString()](#toString--) | Αποκτά μια αναγνώσιμη από άνθρωπο συμβολοσειρά που περιγράφει το [Icon](../../com.aspose.drawing/icon). |
### Icon(String fileName) {#Icon-java.lang.String-}
```
public Icon(String fileName)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [Icon](../../com.aspose.drawing/icon) από το καθορισμένο όνομα αρχείου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fileName | java.lang.String | Το αρχείο από το οποίο θα φορτωθεί το [Icon](../../com.aspose.drawing/icon). |

### Icon(InputStream stream) {#Icon-java.io.InputStream-}
```
public Icon(InputStream stream)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [Icon](../../com.aspose.drawing/icon) από τη συγκεκριμένη ροή δεδομένων.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.InputStream | Η ροή δεδομένων από την οποία θα φορτωθεί το [Icon](../../com.aspose.drawing/icon). |

### Icon(String fileName, Size size) {#Icon-java.lang.String-com.aspose.drawing.Size-}
```
public Icon(String fileName, Size size)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [Icon](../../com.aspose.drawing/icon) του καθορισμένου μεγέθους από το καθορισμένο αρχείο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fileName | java.lang.String | Το όνομα και η διαδρομή του αρχείου που περιέχει τα δεδομένα του εικονιδίου. |
| size | [Size](../../com.aspose.drawing/size) | Το επιθυμητό μέγεθος του εικονιδίου. |

### Icon(Icon original, Size size) {#Icon-com.aspose.drawing.Icon-com.aspose.drawing.Size-}
```
public Icon(Icon original, Size size)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [Icon](../../com.aspose.drawing/icon) και προσπαθεί να βρει μια έκδοση του εικονιδίου που ταιριάζει στο ζητούμενο μέγεθος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| original | [Icon](../../com.aspose.drawing/icon) | Το [Icon](../../com.aspose.drawing/icon) από το οποίο θα φορτωθεί το νεομεγέθους εικονίδιο. |
| size | [Size](../../com.aspose.drawing/size) | Μια δομή `Size`([.getSize](../../null/\#getSize)) που καθορίζει το ύψος και το πλάτος του νέου [Icon](../../com.aspose.drawing/icon). |

### Icon(Object type, String resource) {#Icon-java.lang.Object-java.lang.String-}
```
public Icon(Object type, String resource)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [Icon](../../com.aspose.drawing/icon) από έναν πόρο στην καθορισμένη συναρμολόγηση.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τύπος | java.lang.Object | Ένας Type που καθορίζει τη συναρμολόγηση στην οποία θα αναζητηθεί ο πόρος. |
| πόρος | java.lang.String | Το όνομα του πόρου για φόρτωση. |

### Icon(InputStream stream, Size size) {#Icon-java.io.InputStream-com.aspose.drawing.Size-}
```
public Icon(InputStream stream, Size size)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [Icon](../../com.aspose.drawing/icon) του καθορισμένου μεγέθους από τη συγκεκριμένη ροή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.InputStream | Η ροή που περιέχει τα δεδομένα του εικονιδίου. |
| size | [Size](../../com.aspose.drawing/size) | Το επιθυμητό μέγεθος του εικονιδίου. |

### Icon(String fileName, int width, int height) {#Icon-java.lang.String-int-int-}
```
public Icon(String fileName, int width, int height)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [Icon](../../com.aspose.drawing/icon) με το καθορισμένο πλάτος και ύψος από το καθορισμένο αρχείο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fileName | java.lang.String | Το όνομα και η διαδρομή του αρχείου που περιέχει τα δεδομένα του [Icon](../../com.aspose.drawing/icon). |
| width | int | Το επιθυμητό πλάτος του [Icon](../../com.aspose.drawing/icon). |
| height | int | Το επιθυμητό ύψος του [Icon](../../com.aspose.drawing/icon). |

### Icon(Icon original, int width, int height) {#Icon-com.aspose.drawing.Icon-int-int-}
```
public Icon(Icon original, int width, int height)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [Icon](../../com.aspose.drawing/icon) και προσπαθεί να βρει μια έκδοση του εικονιδίου που ταιριάζει στο ζητούμενο μέγεθος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| original | [Icon](../../com.aspose.drawing/icon) | Το εικονίδιο από το οποίο θα φορτωθεί το διαφορετικό μέγεθος. |
| width | int | Το πλάτος του νέου εικονιδίου. |
| height | int | Το ύψος του νέου εικονιδίου. |

### Icon(InputStream stream, int width, int height) {#Icon-java.io.InputStream-int-int-}
```
public Icon(InputStream stream, int width, int height)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [Icon](../../com.aspose.drawing/icon) από το καθορισμένο ροή δεδομένων και με το καθορισμένο πλάτος και ύψος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.InputStream | Η ροή δεδομένων από την οποία θα φορτωθεί το εικονίδιο. |
| width | int | Το πλάτος, σε εικονοστοιχεία, του εικονιδίου. |
| height | int | Το ύψος, σε εικονοστοιχεία, του εικονιδίου. |

### getHandle() {#getHandle--}
```
public System.IntPtr getHandle()
```


Αποκτά το αναγνωριστικό (handle) για αυτό το [Icon](../../com.aspose.drawing/icon). Αυτό δεν είναι αντίγραφο του αναγνωριστικού· μην το ελευθερώσετε.

Τιμή: Το Windows handle για το εικονίδιο.

**Returns:**
com.aspose.ms.System.IntPtr
### getHeight() {#getHeight--}
```
public int getHeight()
```


Αποκτά το ύψος αυτού του [Icon](../../com.aspose.drawing/icon).

Τιμή: Το ύψος αυτού του [Icon](../../com.aspose.drawing/icon).

**Returns:**
int
### getSize() {#getSize--}
```
public Size getSize()
```


Αποκτά το μέγεθος αυτού του [Icon](../../com.aspose.drawing/icon).

Τιμή: Μια δομή `Size`([.getSize](../../null/\#getSize)) που καθορίζει το πλάτος και το ύψος αυτού του [Icon](../../com.aspose.drawing/icon).

**Returns:**
[Size](../../com.aspose.drawing/size)
### getWidth() {#getWidth--}
```
public int getWidth()
```


Αποκτά το πλάτος αυτού του [Icon](../../com.aspose.drawing/icon).

Τιμή: Το πλάτος αυτού του [Icon](../../com.aspose.drawing/icon).

**Returns:**
int
### extractAssociatedIcon(String filePath) {#extractAssociatedIcon-java.lang.String-}
```
public static Icon extractAssociatedIcon(String filePath)
```


Επιστρέφει μια αναπαράσταση εικονιδίου μιας εικόνας που περιέχεται στο καθορισμένο αρχείο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePath | java.lang.String | Η διαδρομή προς το αρχείο που περιέχει μια εικόνα. |

**Returns:**
[Icon](../../com.aspose.drawing/icon) - The [Icon](../../com.aspose.drawing/icon) representation of the image that is contained in the specified file.
### fromHandle(byte[] handle) {#fromHandle-byte---}
```
public static Icon fromHandle(byte[] handle)
```


Δημιουργεί ένα GDI+ [Icon](../../com.aspose.drawing/icon) από το καθορισμένο αναγνωριστικό Windows για ένα εικονίδιο (HICON).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| handle | byte[] | Ένα Windows handle για ένα εικονίδιο. |

**Returns:**
[Icon](../../com.aspose.drawing/icon) - The [Icon](../../com.aspose.drawing/icon) this method creates.
### deepClone() {#deepClone--}
```
public Object deepClone()
```


Κλωνοποιεί το [Icon](../../com.aspose.drawing/icon), δημιουργώντας μια αντίγραφο εικόνας.

**Returns:**
java.lang.Object - Ένα αντικείμενο που μπορεί να μετατραπεί σε [Icon](../../com.aspose.drawing/icon).
### dispose() {#dispose--}
```
public void dispose()
```


Εκτελεί εργασίες ορισμένες από την εφαρμογή που σχετίζονται με την απελευθέρωση, την αποδέσμευση ή την επαναφορά μη διαχειριζόμενων πόρων.

### save(OutputStream outputStream) {#save-java.io.OutputStream-}
```
public void save(OutputStream outputStream)
```


Αποθηκεύει αυτό το [Icon](../../com.aspose.drawing/icon) στην καθορισμένη έξοδο java.io.InputStream.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| outputStream | java.io.OutputStream | Το java.io.InputStream στο οποίο θα αποθηκευτεί. |

### toBitmap() {#toBitmap--}
```
public Bitmap toBitmap()
```


Μετατρέπει αυτό το [Icon](../../com.aspose.drawing/icon) σε ένα GDI+ [Bitmap](../../com.aspose.drawing/bitmap).

**Returns:**
[Bitmap](../../com.aspose.drawing/bitmap) - A [Bitmap](../../com.aspose.drawing/bitmap) that represents the converted [Icon](../../com.aspose.drawing/icon).
### toString() {#toString--}
```
public String toString()
```


Αποκτά μια αναγνώσιμη από άνθρωπο συμβολοσειρά που περιγράφει το [Icon](../../com.aspose.drawing/icon).

**Returns:**
java.lang.String - Μια συμβολοσειρά που περιγράφει το [Icon](../../com.aspose.drawing/icon).
