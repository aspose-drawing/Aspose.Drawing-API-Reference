---
title: Font
second_title: Αναφορά API του Aspose.Drawing for Java
description: Ορίζει μια συγκεκριμένη μορφή για κείμενο, συμπεριλαμβανομένων του τύπου γραμματοσειράς, του μεγέθους και των χαρακτηριστικών στυλ.
type: docs
weight: 21
url: /el/java/com.aspose.drawing/font/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public final class Font implements System.IDisposable
```

Ορίζει μια συγκεκριμένη μορφή για κείμενο, συμπεριλαμβανομένων του τύπου γραμματοσειράς, του μεγέθους και των χαρακτηριστικών στυλ. Αυτή η κλάση δεν μπορεί να κληρονομηθεί.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [Font(Font prototype, int newStyle)](#Font-com.aspose.drawing.Font-int-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [Font](../../com.aspose.drawing/font) που χρησιμοποιεί τη συγκεκριμένη υπάρχουσα [Font](../../com.aspose.drawing/font) και την απαρίθμηση [FontStyle](../../com.aspose.drawing/fontstyle). |
| [Font(FontFamily family, float emSize)](#Font-com.aspose.drawing.FontFamily-float-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [Font](../../com.aspose.drawing/font) class. |
| [Font(FontFamily family, float emSize, int style)](#Font-com.aspose.drawing.FontFamily-float-int-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [Font](../../com.aspose.drawing/font) class χρησιμοποιώντας καθορισμένο μέγεθος και στυλ.. |
| [Font(FontFamily family, float emSize, int style, int unit)](#Font-com.aspose.drawing.FontFamily-float-int-int-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [Font](../../com.aspose.drawing/font) class χρησιμοποιώντας καθορισμένο μέγεθος, στυλ και μονάδα. |
| [Font(FontFamily family, float emSize, int style, int unit, byte gdiCharSet)](#Font-com.aspose.drawing.FontFamily-float-int-int-byte-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [Font](../../com.aspose.drawing/font) class χρησιμοποιώντας καθορισμένο μέγεθος, στυλ, μονάδα και σύνολο χαρακτήρων.. |
| [Font(FontFamily family, float emSize, int style, int unit, byte gdiCharSet, boolean gdiVerticalFont)](#Font-com.aspose.drawing.FontFamily-float-int-int-byte-boolean-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [Font](../../com.aspose.drawing/font) class χρησιμοποιώντας καθορισμένο μέγεθος, στυλ, μονάδα και σύνολο χαρακτήρων.. |
| [Font(String familyName, float emSize)](#Font-java.lang.String-float-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [Font](../../com.aspose.drawing/font) class χρησιμοποιώντας καθορισμένο μέγεθος. |
| [Font(String familyName, float emSize, int style)](#Font-java.lang.String-float-int-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [Font](../../com.aspose.drawing/font) class χρησιμοποιώντας καθορισμένο μέγεθος και στυλ. |
| [Font(String familyName, float emSize, int style, int unit)](#Font-java.lang.String-float-int-int-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [Font](../../com.aspose.drawing/font) class χρησιμοποιώντας καθορισμένο μέγεθος, στυλ και μονάδα. |
| [Font(String familyName, float emSize, int style, int unit, byte gdiCharSet)](#Font-java.lang.String-float-int-int-byte-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [Font](../../com.aspose.drawing/font) class χρησιμοποιώντας καθορισμένο μέγεθος, στυλ, μονάδα και σύνολο χαρακτήρων. |
| [Font(String familyName, float emSize, int style, int unit, byte gdiCharSet, boolean gdiVerticalFont)](#Font-java.lang.String-float-int-int-byte-boolean-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [Font](../../com.aspose.drawing/font) class χρησιμοποιώντας το καθορισμένο μέγεθος, στυλ, μονάδα και σύνολο χαρακτήρων. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getFontFamily()](#getFontFamily--) | Λαμβάνει το `FontFamily`([.getFontFamily](../../null/\#getFontFamily)) που σχετίζεται με αυτό το [Font](../../com.aspose.drawing/font). |
| [getBold()](#getBold--) | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτό το [Font](../../com.aspose.drawing/font) είναι έντονο. |
| [getGdiCharSet()](#getGdiCharSet--) | Λαμβάνει μια τιμή byte που καθορίζει το σύνολο χαρακτήρων GDI που χρησιμοποιεί αυτό το [Font](../../com.aspose.drawing/font). |
| [getGdiVerticalFont()](#getGdiVerticalFont--) | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτό το [Font](../../com.aspose.drawing/font) προέρχεται από κάθετο γραμματοσειρά GDI.. |
| [getItalic()](#getItalic--) | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτό το [Font](../../com.aspose.drawing/font) είναι πλάγιο. |
| [getName()](#getName--) | Λαμβάνει το όνομα προσώπου αυτής της [Font](../../com.aspose.drawing/font). |
| [getStrikeout()](#getStrikeout--) | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτό το [Font](../../com.aspose.drawing/font) καθορίζει οριζόντια γραμμή διαμέσου της γραμματοσειράς. |
| [getUnderline()](#getUnderline--) | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτό το [Font](../../com.aspose.drawing/font) είναι υπογραμμισμένο. |
| [getStyle()](#getStyle--) | Λαμβάνει πληροφορίες στυλ για αυτό το [Font](../../com.aspose.drawing/font). |
| [getSize()](#getSize--) | Λαμβάνει το μέγεθος em αυτής της [Font](../../com.aspose.drawing/font) μετρημένο στις μονάδες που καθορίζονται από την ιδιότητα `Font.Unit`. |
| [getSizeInPoints()](#getSizeInPoints--) | Λαμβάνει το μέγεθος em, σε σημεία, αυτής της [Font](../../com.aspose.drawing/font). |
| [getUnit()](#getUnit--) | Λαμβάνει τη μονάδα μέτρησης για αυτή τη [Font](../../com.aspose.drawing/font). |
| [getHeight_Rename_Namesake()](#getHeight-Rename-Namesake--) | Λαμβάνει το διάστημα γραμμής αυτής της γραμματοσειράς. |
| [isSystemFont()](#isSystemFont--) | Λαμβάνει μια τιμή που υποδεικνύει εάν η γραμματοσειρά είναι μέλος του [SystemFonts](../../com.aspose.drawing/systemfonts). |
| [getSystemFontName()](#getSystemFontName--) | Λαμβάνει το όνομα της συστημικής γραμματοσειράς εάν η ιδιότητα IsSystemFont επιστρέφει true. |
| [getOriginalFontName()](#getOriginalFontName--) | Λαμβάνει το όνομα της αρχικά καθορισμένης γραμματοσειράς. |
| [deepClone()](#deepClone--) | Δημιουργεί ένα ακριβές αντίγραφο αυτής της [Font](../../com.aspose.drawing/font). |
| [equals(Object obj)](#equals-java.lang.Object-) | Δείχνει εάν το καθορισμένο αντικείμενο είναι ένα [Font](../../com.aspose.drawing/font) και έχει τις ίδιες τιμές ιδιοτήτων `FontFamily`([.getFontFamily](../../null/\#getFontFamily)), `M:GdiVerticalFont`, `M:GdiCharSet`, `M:Style`, `M:Size` και `M:Unit` όπως αυτό το [Font](../../com.aspose.drawing/font). |
| [hashCode()](#hashCode--) | Λαμβάνει τον κωδικό κατακερματισμού για αυτό το [Font](../../com.aspose.drawing/font). |
| [getHeight()](#getHeight--) | Επιστρέφει το διάστημα γραμμής, σε εικονοστοιχεία, αυτής της γραμματοσειράς. |
| [getHeight(Graphics graphics)](#getHeight-com.aspose.drawing.Graphics-) | Επιστρέφει το διάστημα γραμμής, στη τρέχουσα μονάδα ενός καθορισμένου [Graphics](../../com.aspose.drawing/graphics), αυτής της γραμματοσειράς. |
| [getHeight(float dpi)](#getHeight-float-) | Επιστρέφει το ύψος, σε εικονοστοιχεία, αυτού του [Font](../../com.aspose.drawing/font) όταν σχεδιάζεται σε συσκευή με την καθορισμένη κάθετη ανάλυση. |
| [dispose()](#dispose--) | Απελευθερώνει όλους τους πόρους που χρησιμοποιούνται από αυτό το [Font](../../com.aspose.drawing/font). |
| [toString()](#toString--) | Επιστρέφει μια αναγνώσιμη από άνθρωπο αναπαράσταση συμβολοσειράς αυτού του [Font](../../com.aspose.drawing/font). |
| [getCharacterSet()](#getCharacterSet--) | Λαμβάνει μια τιμή byte που καθορίζει το σύνολο χαρακτήρων που χρησιμοποιεί αυτό το `Font`. |
### Font(Font prototype, int newStyle) {#Font-com.aspose.drawing.Font-int-}
```
public Font(Font prototype, int newStyle)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [Font](../../com.aspose.drawing/font) που χρησιμοποιεί τη συγκεκριμένη υπάρχουσα [Font](../../com.aspose.drawing/font) και την απαρίθμηση [FontStyle](../../com.aspose.drawing/fontstyle).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| prototype | [Font](../../com.aspose.drawing/font) | Η υπάρχουσα [Font](../../com.aspose.drawing/font) από την οποία θα δημιουργηθεί η νέα [Font](../../com.aspose.drawing/font). |
| newStyle | int | Το [FontStyle](../../com.aspose.drawing/fontstyle) που θα εφαρμοστεί στη νέα [Font](../../com.aspose.drawing/font). Πολλαπλές τιμές της απαρίθμησης [FontStyle](../../com.aspose.drawing/fontstyle) μπορούν να συνδυαστούν με τον τελεστή OR. |

### Font(FontFamily family, float emSize) {#Font-com.aspose.drawing.FontFamily-float-}
```
public Font(FontFamily family, float emSize)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [Font](../../com.aspose.drawing/font) class.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| family | [FontFamily](../../com.aspose.drawing/fontfamily) | Το `FontFamily`([.getFontFamily](../../null/\#getFontFamily)) της νέας [Font](../../com.aspose.drawing/font). |
| emSize | float | Το em-size, σε σημεία, της νέας γραμματοσειράς. |

### Font(FontFamily family, float emSize, int style) {#Font-com.aspose.drawing.FontFamily-float-int-}
```
public Font(FontFamily family, float emSize, int style)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [Font](../../com.aspose.drawing/font) class χρησιμοποιώντας καθορισμένο μέγεθος και στυλ..

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| family | [FontFamily](../../com.aspose.drawing/fontfamily) | Το `FontFamily`([.getFontFamily](../../null/\#getFontFamily)) της νέας [Font](../../com.aspose.drawing/font). |
| emSize | float | Το em-size, σε σημεία, της νέας γραμματοσειράς. |
| style | int | Το [FontStyle](../../com.aspose.drawing/fontstyle) της νέας γραμματοσειράς. |

### Font(FontFamily family, float emSize, int style, int unit) {#Font-com.aspose.drawing.FontFamily-float-int-int-}
```
public Font(FontFamily family, float emSize, int style, int unit)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [Font](../../com.aspose.drawing/font) class χρησιμοποιώντας καθορισμένο μέγεθος, στυλ και μονάδα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| family | [FontFamily](../../com.aspose.drawing/fontfamily) | Το `FontFamily`([.getFontFamily](../../null/\#getFontFamily)) της νέας [Font](../../com.aspose.drawing/font). |
| emSize | float | Το em-size της νέας γραμματοσειράς στις μονάδες που καθορίζονται από την παράμετρο `unit`. |
| style | int | Το [FontStyle](../../com.aspose.drawing/fontstyle) της νέας γραμματοσειράς. |
| unit | int | Το [GraphicsUnit](../../com.aspose.drawing/graphicsunit) της νέας γραμματοσειράς. |

### Font(FontFamily family, float emSize, int style, int unit, byte gdiCharSet) {#Font-com.aspose.drawing.FontFamily-float-int-int-byte-}
```
public Font(FontFamily family, float emSize, int style, int unit, byte gdiCharSet)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [Font](../../com.aspose.drawing/font) class χρησιμοποιώντας καθορισμένο μέγεθος, στυλ, μονάδα και σύνολο χαρακτήρων..

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| family | [FontFamily](../../com.aspose.drawing/fontfamily) | Το `FontFamily`([.getFontFamily](../../null/\#getFontFamily)) της νέας [Font](../../com.aspose.drawing/font). |
| emSize | float | Το em-size της νέας γραμματοσειράς στις μονάδες που καθορίζονται από την παράμετρο `unit`. |
| style | int | Το [FontStyle](../../com.aspose.drawing/fontstyle) της νέας γραμματοσειράς. |
| unit | int | Το [GraphicsUnit](../../com.aspose.drawing/graphicsunit) της νέας γραμματοσειράς. |
| gdiCharSet | byte | Σύνολο χαρακτήρων GDI που θα χρησιμοποιηθεί για τη νέα γραμματοσειρά. |

### Font(FontFamily family, float emSize, int style, int unit, byte gdiCharSet, boolean gdiVerticalFont) {#Font-com.aspose.drawing.FontFamily-float-int-int-byte-boolean-}
```
public Font(FontFamily family, float emSize, int style, int unit, byte gdiCharSet, boolean gdiVerticalFont)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [Font](../../com.aspose.drawing/font) class χρησιμοποιώντας καθορισμένο μέγεθος, στυλ, μονάδα και σύνολο χαρακτήρων..

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| family | [FontFamily](../../com.aspose.drawing/fontfamily) | Το `FontFamily`([.getFontFamily](../../null/\#getFontFamily)) της νέας [Font](../../com.aspose.drawing/font). |
| emSize | float | Το em-size της νέας γραμματοσειράς στις μονάδες που καθορίζονται από την παράμετρο `unit`. |
| style | int | Το [FontStyle](../../com.aspose.drawing/fontstyle) της νέας γραμματοσειράς. |
| unit | int | Το [GraphicsUnit](../../com.aspose.drawing/graphicsunit) της νέας γραμματοσειράς. |
| gdiCharSet | byte | Σύνολο χαρακτήρων GDI που θα χρησιμοποιηθεί για τη νέα γραμματοσειρά. |
| gdiVerticalFont | boolean | Μια τιμή Boolean που υποδεικνύει εάν η νέα γραμματοσειρά προέρχεται από μια κάθετη γραμματοσειρά GDI. |

### Font(String familyName, float emSize) {#Font-java.lang.String-float-}
```
public Font(String familyName, float emSize)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [Font](../../com.aspose.drawing/font) class χρησιμοποιώντας καθορισμένο μέγεθος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| familyName | java.lang.String | Μια αναπαράσταση συμβολοσειράς του FontFamily για τη νέα [Font](../../com.aspose.drawing/font). |
| emSize | float | Το em-size, σε σημεία, της νέας γραμματοσειράς. |

### Font(String familyName, float emSize, int style) {#Font-java.lang.String-float-int-}
```
public Font(String familyName, float emSize, int style)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [Font](../../com.aspose.drawing/font) class χρησιμοποιώντας καθορισμένο μέγεθος και στυλ.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| familyName | java.lang.String | Μια αναπαράσταση συμβολοσειράς του FontFamily για τη νέα [Font](../../com.aspose.drawing/font). |
| emSize | float | Το em-size, σε σημεία, της νέας γραμματοσειράς. |
| style | int | Το [FontStyle](../../com.aspose.drawing/fontstyle) της νέας γραμματοσειράς. |

### Font(String familyName, float emSize, int style, int unit) {#Font-java.lang.String-float-int-int-}
```
public Font(String familyName, float emSize, int style, int unit)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [Font](../../com.aspose.drawing/font) class χρησιμοποιώντας καθορισμένο μέγεθος, στυλ και μονάδα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| familyName | java.lang.String | Μια αναπαράσταση συμβολοσειράς του `FontFamily`([.getFontFamily](../../null/\#getFontFamily)) για τη νέα [Font](../../com.aspose.drawing/font). |
| emSize | float | Το em-size της νέας γραμματοσειράς στις μονάδες που καθορίζονται από την παράμετρο `unit`. |
| style | int | Το [FontStyle](../../com.aspose.drawing/fontstyle) της νέας γραμματοσειράς. |
| unit | int | Το [GraphicsUnit](../../com.aspose.drawing/graphicsunit) της νέας γραμματοσειράς. |

### Font(String familyName, float emSize, int style, int unit, byte gdiCharSet) {#Font-java.lang.String-float-int-int-byte-}
```
public Font(String familyName, float emSize, int style, int unit, byte gdiCharSet)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [Font](../../com.aspose.drawing/font) class χρησιμοποιώντας καθορισμένο μέγεθος, στυλ, μονάδα και σύνολο χαρακτήρων.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| familyName | java.lang.String | Μια αναπαράσταση συμβολοσειράς του FontFamily για τη νέα [Font](../../com.aspose.drawing/font). |
| emSize | float | Το em-size της νέας γραμματοσειράς στις μονάδες που καθορίζονται από την παράμετρο `unit`. |
| style | int | Το [FontStyle](../../com.aspose.drawing/fontstyle) της νέας γραμματοσειράς. |
| unit | int | Το [GraphicsUnit](../../com.aspose.drawing/graphicsunit) της νέας γραμματοσειράς. |
| gdiCharSet | byte | Ένα byte που καθορίζει ένα σύνολο χαρακτήρων GDI για αυτή τη γραμματοσειρά. |

### Font(String familyName, float emSize, int style, int unit, byte gdiCharSet, boolean gdiVerticalFont) {#Font-java.lang.String-float-int-int-byte-boolean-}
```
public Font(String familyName, float emSize, int style, int unit, byte gdiCharSet, boolean gdiVerticalFont)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [Font](../../com.aspose.drawing/font) class χρησιμοποιώντας το καθορισμένο μέγεθος, στυλ, μονάδα και σύνολο χαρακτήρων.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| familyName | java.lang.String | Μια αναπαράσταση συμβολοσειράς του FontFamily για τη νέα [Font](../../com.aspose.drawing/font). |
| emSize | float | Το em-size της νέας γραμματοσειράς στις μονάδες που καθορίζονται από την παράμετρο `unit`. |
| style | int | Το [FontStyle](../../com.aspose.drawing/fontstyle) της νέας γραμματοσειράς. |
| unit | int | Το [GraphicsUnit](../../com.aspose.drawing/graphicsunit) της νέας γραμματοσειράς. |
| gdiCharSet | byte | Ένα byte που καθορίζει ένα σύνολο χαρακτήρων GDI για αυτή τη γραμματοσειρά. |
| gdiVerticalFont | boolean | Μια τιμή Boolean που υποδεικνύει εάν η νέα [Font](../../com.aspose.drawing/font) προέρχεται από μια κάθετη γραμματοσειρά GDI. |

### getFontFamily() {#getFontFamily--}
```
public FontFamily getFontFamily()
```


Λαμβάνει το `FontFamily`([.getFontFamily](../../null/\#getFontFamily)) που σχετίζεται με αυτό το [Font](../../com.aspose.drawing/font).

**Returns:**
[FontFamily](../../com.aspose.drawing/fontfamily) - The `FontFamily`([.getFontFamily](../../null/\#getFontFamily)) associated with this [Font](../../com.aspose.drawing/font).
### getBold() {#getBold--}
```
public boolean getBold()
```


Λαμβάνει μια τιμή που υποδεικνύει εάν αυτό το [Font](../../com.aspose.drawing/font) είναι έντονο.

**Returns:**
boolean - τιμή που υποδεικνύει εάν αυτό το [Font](../../com.aspose.drawing/font) είναι έντονο.
### getGdiCharSet() {#getGdiCharSet--}
```
public byte getGdiCharSet()
```


Λαμβάνει μια τιμή byte που καθορίζει το σύνολο χαρακτήρων GDI που χρησιμοποιεί αυτό το [Font](../../com.aspose.drawing/font).

**Returns:**
byte - Μια τιμή byte που καθορίζει το σύνολο χαρακτήρων GDI που χρησιμοποιεί αυτό το [Font](../../com.aspose.drawing/font).
### getGdiVerticalFont() {#getGdiVerticalFont--}
```
public boolean getGdiVerticalFont()
```


Λαμβάνει μια τιμή που υποδεικνύει εάν αυτό το [Font](../../com.aspose.drawing/font) προέρχεται από κάθετο γραμματοσειρά GDI..

Τιμή: `true` εάν αυτό το [Font](../../com.aspose.drawing/font) προέρχεται από κάθετο γραμματοσειρά GDI· διαφορετικά, `false`.

**Returns:**
boolean - τιμή που υποδεικνύει εάν αυτό το [Font](../../com.aspose.drawing/font) προέρχεται από κάθετο γραμματοσειρά GDI.
### getItalic() {#getItalic--}
```
public boolean getItalic()
```


Λαμβάνει μια τιμή που υποδεικνύει εάν αυτό το [Font](../../com.aspose.drawing/font) είναι πλάγιο.

**Returns:**
boolean - τιμή που υποδεικνύει εάν αυτό το [Font](../../com.aspose.drawing/font) είναι πλάγιο.
### getName() {#getName--}
```
public String getName()
```


Λαμβάνει το όνομα προσώπου αυτής της [Font](../../com.aspose.drawing/font).

**Returns:**
java.lang.String - το όνομα γραμματοσειράς αυτής της [Font](../../com.aspose.drawing/font).
### getStrikeout() {#getStrikeout--}
```
public boolean getStrikeout()
```


Λαμβάνει μια τιμή που υποδεικνύει εάν αυτό το [Font](../../com.aspose.drawing/font) καθορίζει οριζόντια γραμμή διαμέσου της γραμματοσειράς.

**Returns:**
boolean - τιμή που υποδεικνύει εάν αυτό το [Font](../../com.aspose.drawing/font) καθορίζει οριζόντια γραμμή διαμέσου της γραμματοσειράς.
### getUnderline() {#getUnderline--}
```
public boolean getUnderline()
```


Λαμβάνει μια τιμή που υποδεικνύει εάν αυτό το [Font](../../com.aspose.drawing/font) είναι υπογραμμισμένο.

**Returns:**
boolean - τιμή που υποδεικνύει εάν αυτό το [Font](../../com.aspose.drawing/font) είναι υπογραμμισμένο.
### getStyle() {#getStyle--}
```
public int getStyle()
```


Λαμβάνει πληροφορίες στυλ για αυτό το [Font](../../com.aspose.drawing/font).

**Returns:**
int - πληροφορίες στυλ για αυτό το [Font](../../com.aspose.drawing/font).
### getSize() {#getSize--}
```
public float getSize()
```


Λαμβάνει το μέγεθος em αυτής της [Font](../../com.aspose.drawing/font) μετρημένο στις μονάδες που καθορίζονται από την ιδιότητα `Font.Unit`.

**Returns:**
float - το μέγεθος em αυτής της [Font](../../com.aspose.drawing/font) μετρημένο στις μονάδες που καθορίζονται από το \{@code Font.
### getSizeInPoints() {#getSizeInPoints--}
```
public float getSizeInPoints()
```


Λαμβάνει το μέγεθος em, σε σημεία, αυτής της [Font](../../com.aspose.drawing/font).

**Returns:**
float - Το μέγεθος em, σε πόντους, αυτής της [Font](../../com.aspose.drawing/font).
### getUnit() {#getUnit--}
```
public int getUnit()
```


Λαμβάνει τη μονάδα μέτρησης για αυτή τη [Font](../../com.aspose.drawing/font).

**Returns:**
int - η μονάδα μέτρησης για αυτή τη [Font](../../com.aspose.drawing/font).
### getHeight_Rename_Namesake() {#getHeight-Rename-Namesake--}
```
public int getHeight_Rename_Namesake()
```


Λαμβάνει το διάστημα γραμμής αυτής της γραμματοσειράς.

Τιμή: Η απόσταση γραμμής, σε εικονοστοιχεία, αυτής της γραμματοσειράς.

**Returns:**
int - η απόσταση γραμμής αυτής της γραμματοσειράς.
### isSystemFont() {#isSystemFont--}
```
public boolean isSystemFont()
```


Λαμβάνει μια τιμή που υποδεικνύει εάν η γραμματοσειρά είναι μέλος του [SystemFonts](../../com.aspose.drawing/systemfonts).

Τιμή: `true` εάν η γραμματοσειρά είναι μέλος του [SystemFonts](../../com.aspose.drawing/systemfonts); διαφορετικά, `false`.

**Returns:**
boolean - τιμή που υποδεικνύει εάν η γραμματοσειρά είναι μέλος του [SystemFonts](../../com.aspose.drawing/systemfonts).
### getSystemFontName() {#getSystemFontName--}
```
public String getSystemFontName()
```


Λαμβάνει το όνομα της συστημικής γραμματοσειράς εάν η ιδιότητα IsSystemFont επιστρέφει true.

Τιμή: Το όνομα της συστημικής γραμματοσειράς, εάν το IsSystemFont επιστρέφει true· διαφορετικά, μια κενή συμβολοσειρά (\"\").

**Returns:**
java.lang.String - το όνομα της συστημικής γραμματοσειράς εάν η ιδιότητα IsSystemFont επιστρέφει true.
### getOriginalFontName() {#getOriginalFontName--}
```
public String getOriginalFontName()
```


Λαμβάνει το όνομα της αρχικά καθορισμένης γραμματοσειράς.

Τιμή: Η συμβολοσειρά που αντιπροσωπεύει το όνομα της αρχικά καθορισμένης γραμματοσειράς.

**Returns:**
java.lang.String - το όνομα της αρχικά καθορισμένης γραμματοσειράς.
### deepClone() {#deepClone--}
```
public Font deepClone()
```


Δημιουργεί ένα ακριβές αντίγραφο αυτής της [Font](../../com.aspose.drawing/font).

**Returns:**
[Font](../../com.aspose.drawing/font) - The [Font](../../com.aspose.drawing/font) this method creates, cast as an Object.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Δείχνει εάν το καθορισμένο αντικείμενο είναι ένα [Font](../../com.aspose.drawing/font) και έχει τις ίδιες τιμές ιδιοτήτων `FontFamily`([.getFontFamily](../../null/\#getFontFamily)), `M:GdiVerticalFont`, `M:GdiCharSet`, `M:Style`, `M:Size` και `M:Unit` όπως αυτό το [Font](../../com.aspose.drawing/font).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | java.lang.Object | Το αντικείμενο προς δοκιμή. |

**Returns:**
boolean - `true` εάν η παράμετρος obj είναι μια [Font](../../com.aspose.drawing/font) και έχει τις ίδιες τιμές ιδιοτήτων `FontFamily`([.getFontFamily](../../null/\#getFontFamily)), `M:GdiVerticalFont`, `M:GdiCharSet`, `M:Style`, `M:Size` και `M:Unit` με αυτή τη [Font](../../com.aspose.drawing/font); διαφορετικά, `false`.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Λαμβάνει τον κωδικό κατακερματισμού για αυτό το [Font](../../com.aspose.drawing/font).

**Returns:**
int - Ο κωδικός κατακερματισμού για αυτή τη [Font](../../com.aspose.drawing/font).
### getHeight() {#getHeight--}
```
public int getHeight()
```


Επιστρέφει το διάστημα γραμμής, σε εικονοστοιχεία, αυτής της γραμματοσειράς.

**Returns:**
int - Η απόσταση γραμμής, σε εικονοστοιχεία, αυτής της γραμματοσειράς.
### getHeight(Graphics graphics) {#getHeight-com.aspose.drawing.Graphics-}
```
public float getHeight(Graphics graphics)
```


Επιστρέφει το διάστημα γραμμής, στη τρέχουσα μονάδα ενός καθορισμένου [Graphics](../../com.aspose.drawing/graphics), αυτής της γραμματοσειράς.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| graphics | [Graphics](../../com.aspose.drawing/graphics) | Ένα [Graphics](../../com.aspose.drawing/graphics) που περιέχει την κάθετη ανάλυση, σε κουκκίδες ανά ίντσα, της συσκευής εμφάνισης καθώς και τις ρυθμίσεις για τη μονάδα σελίδας και την κλίμακα σελίδας. |

**Returns:**
float - Η απόσταση γραμμής, σε εικονοστοιχεία, αυτής της γραμματοσειράς.
### getHeight(float dpi) {#getHeight-float-}
```
public int getHeight(float dpi)
```


Επιστρέφει το ύψος, σε εικονοστοιχεία, αυτού του [Font](../../com.aspose.drawing/font) όταν σχεδιάζεται σε συσκευή με την καθορισμένη κάθετη ανάλυση.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| dpi | float | Η κάθετη ανάλυση, σε κουκκίδες ανά ίντσα, που χρησιμοποιείται για τον υπολογισμό του ύψους της γραμματοσειράς. |

**Returns:**
int - Το ύψος, σε εικονοστοιχεία, αυτής της [Font](../../com.aspose.drawing/font).
### dispose() {#dispose--}
```
public void dispose()
```


Απελευθερώνει όλους τους πόρους που χρησιμοποιούνται από αυτό το [Font](../../com.aspose.drawing/font).

### toString() {#toString--}
```
public String toString()
```


Επιστρέφει μια αναγνώσιμη από άνθρωπο αναπαράσταση συμβολοσειράς αυτού του [Font](../../com.aspose.drawing/font).

**Returns:**
java.lang.String - Μια συμβολοσειρά που αντιπροσωπεύει αυτή τη [Font](../../com.aspose.drawing/font).
### getCharacterSet() {#getCharacterSet--}
```
public int getCharacterSet()
```


Λαμβάνει μια τιμή byte που καθορίζει το σύνολο χαρακτήρων που χρησιμοποιεί αυτό το `Font`.

**Returns:**
int - Ένα σύνολο χαρακτήρων που χρησιμοποιεί αυτό το `Font`.
