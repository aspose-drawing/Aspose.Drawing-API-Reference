---
title: ImageCodecInfo
second_title: Αναφορά API του Aspose.Drawing for Java
description: Η κλάση παρέχει τα απαραίτητα μέλη αποθήκευσης και μεθόδους για την ανάκτηση όλων των σχετικών πληροφοριών σχετικά με τους εγκατεστημένους κωδικοποιητές και αποκωδικοποιητές εικόνας που ονομάζονται codecs.
type: docs
weight: 25
url: /el/java/com.aspose.drawing.imaging/imagecodecinfo/
---
**Inheritance:**
java.lang.Object
```
public final class ImageCodecInfo
```

Η κλάση [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo) παρέχει τα απαραίτητα μέλη αποθήκευσης και μεθόδους για την ανάκτηση όλων των σχετικών πληροφοριών σχετικά με τους εγκατεστημένους κωδικοποιητές και αποκωδικοποιητές εικόνας (που ονομάζονται codecs). Δεν είναι κληρονομήσιμη.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [ImageCodecInfo()](#ImageCodecInfo--) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo). |
| [ImageCodecInfo(UUID clsid, String codecName, String filenameExtension, String formatDescription, UUID formatID, String mimeType, int version)](#ImageCodecInfo-java.util.UUID-java.lang.String-java.lang.String-java.lang.String-java.util.UUID-java.lang.String-int-) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getClsid()](#getClsid--) | Λαμβάνει μια δομή java.util.UUID που περιέχει ένα GUID που αναγνωρίζει έναν συγκεκριμένο codec. |
| [setClsid(UUID value)](#setClsid-java.util.UUID-) | Ορίζει μια δομή java.util.UUID που περιέχει ένα GUID που αναγνωρίζει έναν συγκεκριμένο codec. |
| [getFormatID()](#getFormatID--) | Λαμβάνει μια δομή java.util.UUID που περιέχει ένα GUID που αναγνωρίζει τη μορφή του codec. |
| [setFormatID(UUID value)](#setFormatID-java.util.UUID-) | Ορίζει μια δομή java.util.UUID που περιέχει ένα GUID που αναγνωρίζει τη μορφή του codec. |
| [getCodecName()](#getCodecName--) | Λαμβάνει ή ορίζει μια συμβολοσειρά που περιέχει το όνομα του codec. |
| [setCodecName(String value)](#setCodecName-java.lang.String-) | Λαμβάνει ή ορίζει μια συμβολοσειρά που περιέχει το όνομα του codec. |
| [getFormatDescription()](#getFormatDescription--) | Λαμβάνει ή ορίζει μια συμβολοσειρά που περιγράφει τη μορφή αρχείου του codec. |
| [setFormatDescription(String value)](#setFormatDescription-java.lang.String-) | Λαμβάνει ή ορίζει μια συμβολοσειρά που περιγράφει τη μορφή αρχείου του codec. |
| [getFilenameExtension()](#getFilenameExtension--) | Λαμβάνει ή ορίζει μια συμβολοσειρά που περιέχει τις επεκτάσεις ονόματος αρχείου που χρησιμοποιούνται στο codec. |
| [setFilenameExtension(String value)](#setFilenameExtension-java.lang.String-) | Λαμβάνει ή ορίζει μια συμβολοσειρά που περιέχει τις επεκτάσεις ονόματος αρχείου που χρησιμοποιούνται στο codec. |
| [getMimeType()](#getMimeType--) | Λαμβάνει ή ορίζει μια συμβολοσειρά που περιέχει τον τύπο Multipurpose Internet Mail Extensions (MIME) του codec. |
| [setMimeType(String value)](#setMimeType-java.lang.String-) | Λαμβάνει ή ορίζει μια συμβολοσειρά που περιέχει τον τύπο Multipurpose Internet Mail Extensions (MIME) του codec. |
| [getVersion()](#getVersion--) | Λαμβάνει ή ορίζει τον αριθμό έκδοσης του codec. |
| [setVersion(int value)](#setVersion-int-) | Λαμβάνει ή ορίζει τον αριθμό έκδοσης του codec. |
| [getSignaturePatterns()](#getSignaturePatterns--) | Λαμβάνει ή ορίζει έναν δισδιάστατο πίνακα byte που αντιπροσωπεύει την υπογραφή του codec. |
| [setSignaturePatterns(byte[][] value)](#setSignaturePatterns-byte-----) | Λαμβάνει ή ορίζει έναν δισδιάστατο πίνακα byte που αντιπροσωπεύει την υπογραφή του codec. |
| [getSignatureMasks()](#getSignatureMasks--) | Λαμβάνει ή ορίζει έναν δισδιάστατο πίνακα byte που μπορεί να χρησιμοποιηθεί ως φίλτρο. |
| [setSignatureMasks(byte[][] value)](#setSignatureMasks-byte-----) | Λαμβάνει ή ορίζει έναν δισδιάστατο πίνακα byte που μπορεί να χρησιμοποιηθεί ως φίλτρο. |
| [getImageDecoders()](#getImageDecoders--) | Επιστρέφει έναν πίνακα αντικειμένων [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo) που περιέχουν πληροφορίες για τους αποκωδικοποιητές εικόνας που είναι ενσωματωμένοι στο GDI+. |
| [getImageEncoders()](#getImageEncoders--) | Επιστρέφει έναν πίνακα αντικειμένων [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo) που περιέχουν πληροφορίες για τους κωδικοποιητές εικόνας που είναι ενσωματωμένοι στο GDI+. |
### ImageCodecInfo() {#ImageCodecInfo--}
```
public ImageCodecInfo()
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo).

### ImageCodecInfo(UUID clsid, String codecName, String filenameExtension, String formatDescription, UUID formatID, String mimeType, int version) {#ImageCodecInfo-java.util.UUID-java.lang.String-java.lang.String-java.lang.String-java.util.UUID-java.lang.String-int-}
```
public ImageCodecInfo(UUID clsid, String codecName, String filenameExtension, String formatDescription, UUID formatID, String mimeType, int version)
```


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| clsid | java.util.UUID |  |
| codecName | java.lang.String |  |
| filenameExtension | java.lang.String |  |
| formatDescription | java.lang.String |  |
| formatID | java.util.UUID |  |
| mimeType | java.lang.String |  |
| version | int |  |

### getClsid() {#getClsid--}
```
public UUID getClsid()
```


Λαμβάνει μια δομή java.util.UUID που περιέχει ένα GUID που αναγνωρίζει έναν συγκεκριμένο codec.

**Returns:**
java.util.UUID - ένα java.util.UUID
### setClsid(UUID value) {#setClsid-java.util.UUID-}
```
public void setClsid(UUID value)
```


Ορίζει μια δομή java.util.UUID που περιέχει ένα GUID που αναγνωρίζει έναν συγκεκριμένο codec.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.util.UUID | ένα java.util.UUID |

### getFormatID() {#getFormatID--}
```
public UUID getFormatID()
```


Λαμβάνει μια δομή java.util.UUID που περιέχει ένα GUID που αναγνωρίζει τη μορφή του codec.

**Returns:**
java.util.UUID - ένα java.util.UUID
### setFormatID(UUID value) {#setFormatID-java.util.UUID-}
```
public void setFormatID(UUID value)
```


Ορίζει μια δομή java.util.UUID που περιέχει ένα GUID που αναγνωρίζει τη μορφή του codec.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.util.UUID | ένα java.util.UUID |

### getCodecName() {#getCodecName--}
```
public String getCodecName()
```


Λαμβάνει ή ορίζει μια συμβολοσειρά που περιέχει το όνομα του codec.

**Returns:**
java.lang.String
### setCodecName(String value) {#setCodecName-java.lang.String-}
```
public void setCodecName(String value)
```


Λαμβάνει ή ορίζει μια συμβολοσειρά που περιέχει το όνομα του codec.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getFormatDescription() {#getFormatDescription--}
```
public String getFormatDescription()
```


Λαμβάνει ή ορίζει μια συμβολοσειρά που περιγράφει τη μορφή αρχείου του codec.

**Returns:**
java.lang.String
### setFormatDescription(String value) {#setFormatDescription-java.lang.String-}
```
public void setFormatDescription(String value)
```


Λαμβάνει ή ορίζει μια συμβολοσειρά που περιγράφει τη μορφή αρχείου του codec.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getFilenameExtension() {#getFilenameExtension--}
```
public String getFilenameExtension()
```


Λαμβάνει ή ορίζει τη συμβολοσειρά που περιέχει τις καταλήξεις του ονόματος αρχείου που χρησιμοποιούνται στον κωδικοποιητή. Οι καταλήξεις διαχωρίζονται με σημείο‑κόμμα.

**Returns:**
java.lang.String
### setFilenameExtension(String value) {#setFilenameExtension-java.lang.String-}
```
public void setFilenameExtension(String value)
```


Λαμβάνει ή ορίζει τη συμβολοσειρά που περιέχει τις καταλήξεις του ονόματος αρχείου που χρησιμοποιούνται στον κωδικοποιητή. Οι καταλήξεις διαχωρίζονται με σημείο‑κόμμα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getMimeType() {#getMimeType--}
```
public String getMimeType()
```


Λαμβάνει ή ορίζει μια συμβολοσειρά που περιέχει τον τύπο Multipurpose Internet Mail Extensions (MIME) του codec.

**Returns:**
java.lang.String
### setMimeType(String value) {#setMimeType-java.lang.String-}
```
public void setMimeType(String value)
```


Λαμβάνει ή ορίζει μια συμβολοσειρά που περιέχει τον τύπο Multipurpose Internet Mail Extensions (MIME) του codec.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getVersion() {#getVersion--}
```
public int getVersion()
```


Λαμβάνει ή ορίζει τον αριθμό έκδοσης του codec.

**Returns:**
int
### setVersion(int value) {#setVersion-int-}
```
public void setVersion(int value)
```


Λαμβάνει ή ορίζει τον αριθμό έκδοσης του codec.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getSignaturePatterns() {#getSignaturePatterns--}
```
public byte[][] getSignaturePatterns()
```


Λαμβάνει ή ορίζει έναν δισδιάστατο πίνακα byte που αντιπροσωπεύει την υπογραφή του codec.

**Returns:**
byte[][]
### setSignaturePatterns(byte[][] value) {#setSignaturePatterns-byte-----}
```
public void setSignaturePatterns(byte[][] value)
```


Λαμβάνει ή ορίζει έναν δισδιάστατο πίνακα byte που αντιπροσωπεύει την υπογραφή του codec.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte[][] |  |

### getSignatureMasks() {#getSignatureMasks--}
```
public byte[][] getSignatureMasks()
```


Λαμβάνει ή ορίζει έναν δισδιάστατο πίνακα byte που μπορεί να χρησιμοποιηθεί ως φίλτρο.

**Returns:**
byte[][]
### setSignatureMasks(byte[][] value) {#setSignatureMasks-byte-----}
```
public void setSignatureMasks(byte[][] value)
```


Λαμβάνει ή ορίζει έναν δισδιάστατο πίνακα byte που μπορεί να χρησιμοποιηθεί ως φίλτρο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte[][] |  |

### getImageDecoders() {#getImageDecoders--}
```
public static ImageCodecInfo[] getImageDecoders()
```


Επιστρέφει έναν πίνακα αντικειμένων [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo) που περιέχουν πληροφορίες για τους αποκωδικοποιητές εικόνας που είναι ενσωματωμένοι στο GDI+.

**Returns:**
com.aspose.drawing.imaging.ImageCodecInfo[] - Ένας πίνακας αντικειμένων [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo). Κάθε αντικείμενο [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo) στον πίνακα περιέχει πληροφορίες για έναν από τους ενσωματωμένους αποκωδικοποιητές εικόνας.
### getImageEncoders() {#getImageEncoders--}
```
public static ImageCodecInfo[] getImageEncoders()
```


Επιστρέφει έναν πίνακα αντικειμένων [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo) που περιέχουν πληροφορίες για τους κωδικοποιητές εικόνας που είναι ενσωματωμένοι στο GDI+.

**Returns:**
com.aspose.drawing.imaging.ImageCodecInfo[] - Ένας πίνακας αντικειμένων [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo). Κάθε αντικείμενο [ImageCodecInfo](../../com.aspose.drawing.imaging/imagecodecinfo) στον πίνακα περιέχει πληροφορίες για έναν από τους ενσωματωμένους κωδικοποιητές εικόνας.
