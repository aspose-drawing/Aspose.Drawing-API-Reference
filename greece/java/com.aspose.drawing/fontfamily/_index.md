---
title: FontFamily
second_title: Αναφορά API του Aspose.Drawing for Java
description: Ορίζει μια ομάδα τύπων γραμματοσειρών που έχουν παρόμοιο βασικό σχέδιο και ορισμένες παραλλαγές σε στυλ.
type: docs
weight: 24
url: /el/java/com.aspose.drawing/fontfamily/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public final class FontFamily implements System.IDisposable
```

Ορίζει μια ομάδα γραμματοσειρών που έχουν παρόμοιο βασικό σχέδιο και ορισμένες παραλλαγές σε στυλ. Αυτή η κλάση δεν μπορεί να κληρονομηθεί.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [FontFamily(String name)](#FontFamily-java.lang.String-) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [FontFamily](../../com.aspose.drawing/fontfamily) με το καθορισμένο όνομα. |
| [FontFamily(String name, FontCollection fontCollection)](#FontFamily-java.lang.String-com.aspose.drawing.FontCollection-) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [FontFamily](../../com.aspose.drawing/fontfamily). |
| [FontFamily(String name, FontFamilyDefinition definition)](#FontFamily-java.lang.String-com.aspose.drawing.FontFamilyDefinition-) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [FontFamily](../../com.aspose.drawing/fontfamily). |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getFamilies()](#getFamilies--) | Επιστρέφει έναν πίνακα που περιέχει όλα τα αντικείμενα [FontFamily](../../com.aspose.drawing/fontfamily) που σχετίζονται με το τρέχον πλαίσιο γραφικών. |
| [getGenericSansSerif()](#getGenericSansSerif--) | Επιστρέφει ένα γενικό αντικείμενο sans serif [FontFamily](../../com.aspose.drawing/fontfamily). |
| [getGenericSerif()](#getGenericSerif--) | Επιστρέφει ένα γενικό αντικείμενο serif [FontFamily](../../com.aspose.drawing/fontfamily). |
| [getGenericMonospace()](#getGenericMonospace--) | Επιστρέφει ένα γενικό αντικείμενο monospace [FontFamily](../../com.aspose.drawing/fontfamily). |
| [getName()](#getName--) | Επιστρέφει το όνομα αυτού του [FontFamily](../../com.aspose.drawing/fontfamily). |
| [dispose()](#dispose--) | Απελευθερώνει όλους τους πόρους που χρησιμοποιούνται από αυτό το [FontFamily](../../com.aspose.drawing/fontfamily). |
| [getName(int language)](#getName-int-) | Επιστρέφει το όνομα, στην καθορισμένη γλώσσα, αυτού του [FontFamily](../../com.aspose.drawing/fontfamily). |
| [isStyleAvailable(int style)](#isStyleAvailable-int-) | Δείχνει εάν η καθορισμένη απαρίθμηση [FontStyle](../../com.aspose.drawing/fontstyle) είναι διαθέσιμη. |
| [getEmHeight(int style)](#getEmHeight-int-) | Λαμβάνει το ύψος, σε μονάδες σχεδίασης γραμματοσειράς, του τετραγώνου EM για το καθορισμένο στυλ. |
| [getCellAscent(int style)](#getCellAscent-int-) | Επιστρέφει την άνοδο κελιού, σε μονάδες σχεδίασης, του [FontFamily](../../com.aspose.drawing/fontfamily) του καθορισμένου στυλ. |
| [getCellDescent(int style)](#getCellDescent-int-) | Επιστρέφει την κάθοδο κελιού, σε μονάδες σχεδίασης, του [FontFamily](../../com.aspose.drawing/fontfamily) του καθορισμένου στυλ. |
| [hashCode()](#hashCode--) | Λαμβάνει έναν κωδικό κατακερματισμού για αυτό το [FontFamily](../../com.aspose.drawing/fontfamily). |
| [equals(Object obj)](#equals-java.lang.Object-) | Δείχνει εάν το καθορισμένο αντικείμενο είναι ένα [FontFamily](../../com.aspose.drawing/fontfamily) και είναι ταυτόσημο με αυτό το [FontFamily](../../com.aspose.drawing/fontfamily). |
| [getLineSpacing(int style)](#getLineSpacing-int-) | Επιστρέφει το διάστημα γραμμής, σε μονάδες σχεδίασης, του [FontFamily](../../com.aspose.drawing/fontfamily) του καθορισμένου στυλ. |
### FontFamily(String name) {#FontFamily-java.lang.String-}
```
public FontFamily(String name)
```


Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [FontFamily](../../com.aspose.drawing/fontfamily) με το καθορισμένο όνομα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | java.lang.String | Το όνομα του νέου [FontFamily](../../com.aspose.drawing/fontfamily). |

### FontFamily(String name, FontCollection fontCollection) {#FontFamily-java.lang.String-com.aspose.drawing.FontCollection-}
```
public FontFamily(String name, FontCollection fontCollection)
```


Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [FontFamily](../../com.aspose.drawing/fontfamily).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| όνομα | java.lang.String | Το όνομα της οικογένειας γραμματοσειρών. |
| fontCollection | [FontCollection](../../com.aspose.drawing/fontcollection) | Η συλλογή γραμματοσειρών. |

### FontFamily(String name, FontFamilyDefinition definition) {#FontFamily-java.lang.String-com.aspose.drawing.FontFamilyDefinition-}
```
public FontFamily(String name, FontFamilyDefinition definition)
```


Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [FontFamily](../../com.aspose.drawing/fontfamily).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| όνομα | java.lang.String | Το όνομα της οικογένειας γραμματοσειρών. |
| definition | [FontFamilyDefinition](../../com.aspose.drawing/fontfamilydefinition) | Ο ορισμός. |

### getFamilies() {#getFamilies--}
```
public static FontFamily[] getFamilies()
```


Επιστρέφει έναν πίνακα που περιέχει όλα τα αντικείμενα [FontFamily](../../com.aspose.drawing/fontfamily) που σχετίζονται με το τρέχον πλαίσιο γραφικών.

**Returns:**
com.aspose.drawing.FontFamily[] - Ένας πίνακας αντικειμένων [FontFamily](../../com.aspose.drawing/fontfamily) που σχετίζονται με το τρέχον πλαίσιο γραφικών.
### getGenericSansSerif() {#getGenericSansSerif--}
```
public static FontFamily getGenericSansSerif()
```


Επιστρέφει ένα γενικό αντικείμενο sans serif [FontFamily](../../com.aspose.drawing/fontfamily).

**Returns:**
[FontFamily](../../com.aspose.drawing/fontfamily) - A [FontFamily](../../com.aspose.drawing/fontfamily) object that represents a generic sans serif font.
### getGenericSerif() {#getGenericSerif--}
```
public static FontFamily getGenericSerif()
```


Επιστρέφει ένα γενικό αντικείμενο serif [FontFamily](../../com.aspose.drawing/fontfamily).

**Returns:**
[FontFamily](../../com.aspose.drawing/fontfamily) - A [FontFamily](../../com.aspose.drawing/fontfamily) that represents a generic serif font.
### getGenericMonospace() {#getGenericMonospace--}
```
public static FontFamily getGenericMonospace()
```


Επιστρέφει ένα γενικό αντικείμενο monospace [FontFamily](../../com.aspose.drawing/fontfamily).

**Returns:**
[FontFamily](../../com.aspose.drawing/fontfamily) - A [FontFamily](../../com.aspose.drawing/fontfamily) that represents a generic monospace font.
### getName() {#getName--}
```
public String getName()
```


Επιστρέφει το όνομα αυτού του [FontFamily](../../com.aspose.drawing/fontfamily).

**Returns:**
java.lang.String - Ένα String που αντιπροσωπεύει το όνομα αυτού του [FontFamily](../../com.aspose.drawing/fontfamily).
### dispose() {#dispose--}
```
public void dispose()
```


Απελευθερώνει όλους τους πόρους που χρησιμοποιούνται από αυτό το [FontFamily](../../com.aspose.drawing/fontfamily).

### getName(int language) {#getName-int-}
```
public String getName(int language)
```


Επιστρέφει το όνομα, στην καθορισμένη γλώσσα, αυτού του [FontFamily](../../com.aspose.drawing/fontfamily).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| γλώσσα | int | Η γλώσσα στην οποία επιστρέφεται το όνομα. |

**Returns:**
java.lang.String - Ένα String που αντιπροσωπεύει το όνομα, στην καθορισμένη γλώσσα, αυτού του [FontFamily](../../com.aspose.drawing/fontfamily).
### isStyleAvailable(int style) {#isStyleAvailable-int-}
```
public boolean isStyleAvailable(int style)
```


Δείχνει εάν η καθορισμένη απαρίθμηση [FontStyle](../../com.aspose.drawing/fontstyle) είναι διαθέσιμη.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| style | int | Το [FontStyle](../../com.aspose.drawing/fontstyle) προς δοκιμή. |

**Returns:**
boolean - true εάν το καθορισμένο [FontStyle](../../com.aspose.drawing/fontstyle) είναι διαθέσιμο· διαφορετικά, false.
### getEmHeight(int style) {#getEmHeight-int-}
```
public int getEmHeight(int style)
```


Λαμβάνει το ύψος, σε μονάδες σχεδίασης γραμματοσειράς, του τετραγώνου EM για το καθορισμένο στυλ.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| style | int | Το [FontStyle](../../com.aspose.drawing/fontstyle) για το οποίο θα ληφθεί το ύψος EM. |

**Returns:**
int - Το ύψος του τετραγώνου EM.
### getCellAscent(int style) {#getCellAscent-int-}
```
public int getCellAscent(int style)
```


Επιστρέφει την άνοδο κελιού, σε μονάδες σχεδίασης, του [FontFamily](../../com.aspose.drawing/fontfamily) του καθορισμένου στυλ.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| style | int | Ένα [FontStyle](../../com.aspose.drawing/fontstyle) που περιέχει πληροφορίες στυλ για τη γραμματοσειρά. |

**Returns:**
int - Η άνοδος κελιού για αυτό το [FontFamily](../../com.aspose.drawing/fontfamily) που χρησιμοποιεί το καθορισμένο [FontStyle](../../com.aspose.drawing/fontstyle).
### getCellDescent(int style) {#getCellDescent-int-}
```
public int getCellDescent(int style)
```


Επιστρέφει την κάθοδο κελιού, σε μονάδες σχεδίασης, του [FontFamily](../../com.aspose.drawing/fontfamily) του καθορισμένου στυλ.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| style | int | Ένα [FontStyle](../../com.aspose.drawing/fontstyle) που περιέχει πληροφορίες στυλ για τη γραμματοσειρά. |

**Returns:**
int - Η μέτρηση κάθοδος κελιού για αυτό το [FontFamily](../../com.aspose.drawing/fontfamily) που χρησιμοποιεί το καθορισμένο [FontStyle](../../com.aspose.drawing/fontstyle).
### hashCode() {#hashCode--}
```
public int hashCode()
```


Λαμβάνει έναν κωδικό κατακερματισμού για αυτό το [FontFamily](../../com.aspose.drawing/fontfamily).

**Returns:**
int - Ο κωδικός κατακερματισμού για αυτό το [FontFamily](../../com.aspose.drawing/fontfamily).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Δείχνει εάν το καθορισμένο αντικείμενο είναι ένα [FontFamily](../../com.aspose.drawing/fontfamily) και είναι ταυτόσημο με αυτό το [FontFamily](../../com.aspose.drawing/fontfamily).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | java.lang.Object | Το αντικείμενο προς δοκιμή. |

**Returns:**
boolean - `true` εάν το `obj` είναι ένα [FontFamily](../../com.aspose.drawing/fontfamily) και είναι ταυτόσημο με αυτό το [FontFamily](../../com.aspose.drawing/fontfamily); διαφορετικά, `false`.
### getLineSpacing(int style) {#getLineSpacing-int-}
```
public int getLineSpacing(int style)
```


Επιστρέφει το διάστημα γραμμής, σε μονάδες σχεδίασης, του [FontFamily](../../com.aspose.drawing/fontfamily) του καθορισμένου στυλ. Το διάστημα γραμμής είναι η κάθετη απόσταση μεταξύ των βασικών γραμμών δύο διαδοχικών γραμμών κειμένου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| style | int | Το [FontStyle](../../com.aspose.drawing/fontstyle) που θα εφαρμοστεί. |

**Returns:**
int - Η απόσταση μεταξύ δύο διαδοχικών γραμμών κειμένου.
