---
title: StringFormat
second_title: Αναφορά API του Aspose.Drawing for Java
description: Περιλαμβάνει πληροφορίες διάταξης κειμένου όπως προσανατολισμός στοίχισης και διακοπές καρτέλας, χειρισμούς εμφάνισης όπως εισαγωγή έλλειψης και αντικατάσταση εθνικών ψηφίων και χαρακτηριστικά OpenType.
type: docs
weight: 47
url: /el/java/com.aspose.drawing/stringformat/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public final class StringFormat implements System.IDisposable
```

Περιλαμβάνει πληροφορίες διάταξης κειμένου (όπως στοίχιση, προσανατολισμό και διακοπές στήλης) χειρισμούς εμφάνισης (όπως εισαγωγή ελλειπτικών και εθνική αντικατάσταση ψηφίων) και δυνατότητες OpenType. Αυτή η κλάση δεν μπορεί να κληρονομηθεί.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [StringFormat()](#StringFormat--) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [StringFormat](../../com.aspose.drawing/stringformat). |
| [StringFormat(StringFormat format)](#StringFormat-com.aspose.drawing.StringFormat-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [StringFormat](../../com.aspose.drawing/stringformat) από το καθορισμένο υπάρχον αντικείμενο [StringFormat](../../com.aspose.drawing/stringformat). |
| [StringFormat(int options, int language)](#StringFormat-int-int-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [StringFormat](../../com.aspose.drawing/stringformat) με την καθορισμένη απαρίθμηση [StringFormatFlags](../../com.aspose.drawing/stringformatflags) και γλώσσα. |
| [StringFormat(int options)](#StringFormat-int-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [StringFormat](../../com.aspose.drawing/stringformat) με την καθορισμένη απαρίθμηση [StringFormatFlags](../../com.aspose.drawing/stringformatflags). |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [setDigitSubstitutionLanguage(int value)](#setDigitSubstitutionLanguage-int-) |  |
| [setDigitSubstitutionMethod(int value)](#setDigitSubstitutionMethod-int-) |  |
| [getFirstTabOffset()](#getFirstTabOffset--) |  |
| [getGenericDefault()](#getGenericDefault--) | Λαμβάνει ένα γενικό προεπιλεγμένο αντικείμενο [StringFormat](../../com.aspose.drawing/stringformat). |
| [getGenericTypographic()](#getGenericTypographic--) | Λαμβάνει ένα γενικό τυπογραφικό αντικείμενο [StringFormat](../../com.aspose.drawing/stringformat). |
| [getFormatFlags()](#getFormatFlags--) | Λαμβάνει ή ορίζει μια απαρίθμηση [StringFormatFlags](../../com.aspose.drawing/stringformatflags) που περιέχει πληροφορίες μορφοποίησης. |
| [setFormatFlags(int value)](#setFormatFlags-int-) | Λαμβάνει ή ορίζει μια απαρίθμηση [StringFormatFlags](../../com.aspose.drawing/stringformatflags) που περιέχει πληροφορίες μορφοποίησης. |
| [getAlignment()](#getAlignment--) | Λαμβάνει ή ορίζει πληροφορίες στοίχισης κειμένου στον κατακόρυφο άξονα. |
| [setAlignment(int value)](#setAlignment-int-) | Λαμβάνει ή ορίζει πληροφορίες στοίχισης κειμένου στον κατακόρυφο άξονα. |
| [getLineAlignment()](#getLineAlignment--) | Λαμβάνει ή ορίζει τη στοίχιση γραμμής στον οριζόντιο άξονα. |
| [setLineAlignment(int value)](#setLineAlignment-int-) | Λαμβάνει ή ορίζει τη στοίχιση γραμμής στον οριζόντιο άξονα. |
| [getHotkeyPrefix()](#getHotkeyPrefix--) | Λαμβάνει ή ορίζει το αντικείμενο `HotkeyPrefix`([.getHotkeyPrefix](../../null/\#getHotkeyPrefix)/[.setHotkeyPrefix(int)](../../null/\#setHotkeyPrefix-int-)) για αυτό το αντικείμενο [StringFormat](../../com.aspose.drawing/stringformat). |
| [setHotkeyPrefix(int value)](#setHotkeyPrefix-int-) | Λαμβάνει ή ορίζει το αντικείμενο `HotkeyPrefix`([.getHotkeyPrefix](../../null/\#getHotkeyPrefix)/[.setHotkeyPrefix(int)](../../null/\#setHotkeyPrefix-int-)) για αυτό το αντικείμενο [StringFormat](../../com.aspose.drawing/stringformat). |
| [getTrimming()](#getTrimming--) | Λαμβάνει ή ορίζει την απαρίθμηση [StringTrimming](../../com.aspose.drawing/stringtrimming) για αυτό το αντικείμενο [StringFormat](../../com.aspose.drawing/stringformat). |
| [setTrimming(int value)](#setTrimming-int-) | Λαμβάνει ή ορίζει την απαρίθμηση [StringTrimming](../../com.aspose.drawing/stringtrimming) για αυτό το αντικείμενο [StringFormat](../../com.aspose.drawing/stringformat). |
| [getDigitSubstitutionLanguage()](#getDigitSubstitutionLanguage--) | Λαμβάνει τη γλώσσα που χρησιμοποιείται όταν τα τοπικά ψηφία αντικαθίστανται από δυτικά ψηφία. |
| [getDigitSubstitutionMethod()](#getDigitSubstitutionMethod--) | Λαμβάνει τη μέθοδο που θα χρησιμοποιηθεί για την αντικατάσταση ψηφίων. |
| [dispose()](#dispose--) | Απελευθερώνει όλους τους πόρους που χρησιμοποιούνται από αυτό το αντικείμενο [StringFormat](../../com.aspose.drawing/stringformat). |
| [deepClone()](#deepClone--) | Δημιουργεί ένα ακριβές αντίγραφο αυτού του αντικειμένου [StringFormat](../../com.aspose.drawing/stringformat). |
| [getTabStops(float[] firstTabOffset)](#getTabStops-float---) | Λαμβάνει τις διακοπές στήλης για αυτό το αντικείμενο [StringFormat](../../com.aspose.drawing/stringformat). |
| [getTabStops()](#getTabStops--) | Λαμβάνει έναν πίνακα αποστάσεων μεταξύ των διακοπών στήλης στις μονάδες που καθορίζονται από την ιδιότητα `Aspose.Imaging.getGraphics().PageUnit`. |
| [setTabStops(float firstTabOffset, float[] tabStops)](#setTabStops-float-float---) | Ορίζει τις διακοπές στήλης για αυτό το αντικείμενο [StringFormat](../../com.aspose.drawing/stringformat). |
| [setDigitSubstitution(int language, int substitute)](#setDigitSubstitution-int-int-) | Καθορίζει τη γλώσσα και τη μέθοδο που θα χρησιμοποιηθούν όταν τα τοπικά ψηφία αντικαθίστανται από δυτικά ψηφία. |
| [setMeasurableCharacterRanges(CharacterRange[] ranges)](#setMeasurableCharacterRanges-com.aspose.drawing.CharacterRange---) | Καθορίζει έναν πίνακα δομών [CharacterRange](../../com.aspose.drawing/characterrange) που αντιπροσωπεύουν τις περιοχές χαρακτήρων που μετρώνται με μια κλήση στη μέθοδο `MeasureCharacterRanges`. |
### StringFormat() {#StringFormat--}
```
public StringFormat()
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [StringFormat](../../com.aspose.drawing/stringformat).

### StringFormat(StringFormat format) {#StringFormat-com.aspose.drawing.StringFormat-}
```
public StringFormat(StringFormat format)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [StringFormat](../../com.aspose.drawing/stringformat) από το καθορισμένο υπάρχον αντικείμενο [StringFormat](../../com.aspose.drawing/stringformat).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| format | [StringFormat](../../com.aspose.drawing/stringformat) | Το αντικείμενο [StringFormat](../../com.aspose.drawing/stringformat) από το οποίο θα αρχικοποιηθεί το νέο αντικείμενο [StringFormat](../../com.aspose.drawing/stringformat). |

### StringFormat(int options, int language) {#StringFormat-int-int-}
```
public StringFormat(int options, int language)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [StringFormat](../../com.aspose.drawing/stringformat) με την καθορισμένη απαρίθμηση [StringFormatFlags](../../com.aspose.drawing/stringformatflags) και γλώσσα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| options | int | Η απαρίθμηση [StringFormatFlags](../../com.aspose.drawing/stringformatflags) για το νέο αντικείμενο [StringFormat](../../com.aspose.drawing/stringformat). |
| γλώσσα | int | Μια τιμή που υποδεικνύει τη γλώσσα του κειμένου. |

### StringFormat(int options) {#StringFormat-int-}
```
public StringFormat(int options)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [StringFormat](../../com.aspose.drawing/stringformat) με την καθορισμένη απαρίθμηση [StringFormatFlags](../../com.aspose.drawing/stringformatflags).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| options | int | Η απαρίθμηση [StringFormatFlags](../../com.aspose.drawing/stringformatflags) για το νέο αντικείμενο [StringFormat](../../com.aspose.drawing/stringformat). |

### setDigitSubstitutionLanguage(int value) {#setDigitSubstitutionLanguage-int-}
```
public void setDigitSubstitutionLanguage(int value)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### setDigitSubstitutionMethod(int value) {#setDigitSubstitutionMethod-int-}
```
public void setDigitSubstitutionMethod(int value)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getFirstTabOffset() {#getFirstTabOffset--}
```
public float getFirstTabOffset()
```




**Returns:**
float
### getGenericDefault() {#getGenericDefault--}
```
public static StringFormat getGenericDefault()
```


Λαμβάνει ένα γενικό προεπιλεγμένο αντικείμενο [StringFormat](../../com.aspose.drawing/stringformat).

**Returns:**
[StringFormat](../../com.aspose.drawing/stringformat)
### getGenericTypographic() {#getGenericTypographic--}
```
public static StringFormat getGenericTypographic()
```


Λαμβάνει ένα γενικό τυπογραφικό αντικείμενο [StringFormat](../../com.aspose.drawing/stringformat).

**Returns:**
[StringFormat](../../com.aspose.drawing/stringformat) - A generic typographic [StringFormat](../../com.aspose.drawing/stringformat) object.
### getFormatFlags() {#getFormatFlags--}
```
public int getFormatFlags()
```


Λαμβάνει ή ορίζει μια απαρίθμηση [StringFormatFlags](../../com.aspose.drawing/stringformatflags) που περιέχει πληροφορίες μορφοποίησης.

**Returns:**
int
### setFormatFlags(int value) {#setFormatFlags-int-}
```
public void setFormatFlags(int value)
```


Λαμβάνει ή ορίζει μια απαρίθμηση [StringFormatFlags](../../com.aspose.drawing/stringformatflags) που περιέχει πληροφορίες μορφοποίησης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getAlignment() {#getAlignment--}
```
public int getAlignment()
```


Λαμβάνει ή ορίζει πληροφορίες στοίχισης κειμένου στον κατακόρυφο άξονα.

**Returns:**
int
### setAlignment(int value) {#setAlignment-int-}
```
public void setAlignment(int value)
```


Λαμβάνει ή ορίζει πληροφορίες στοίχισης κειμένου στον κατακόρυφο άξονα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getLineAlignment() {#getLineAlignment--}
```
public int getLineAlignment()
```


Λαμβάνει ή ορίζει τη στοίχιση γραμμής στον οριζόντιο άξονα.

**Returns:**
int
### setLineAlignment(int value) {#setLineAlignment-int-}
```
public void setLineAlignment(int value)
```


Λαμβάνει ή ορίζει τη στοίχιση γραμμής στον οριζόντιο άξονα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getHotkeyPrefix() {#getHotkeyPrefix--}
```
public int getHotkeyPrefix()
```


Λαμβάνει ή ορίζει το αντικείμενο `HotkeyPrefix`([.getHotkeyPrefix](../../null/\#getHotkeyPrefix)/[.setHotkeyPrefix(int)](../../null/\#setHotkeyPrefix-int-)) για αυτό το αντικείμενο [StringFormat](../../com.aspose.drawing/stringformat).

**Returns:**
int
### setHotkeyPrefix(int value) {#setHotkeyPrefix-int-}
```
public void setHotkeyPrefix(int value)
```


Λαμβάνει ή ορίζει το αντικείμενο `HotkeyPrefix`([.getHotkeyPrefix](../../null/\#getHotkeyPrefix)/[.setHotkeyPrefix(int)](../../null/\#setHotkeyPrefix-int-)) για αυτό το αντικείμενο [StringFormat](../../com.aspose.drawing/stringformat).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getTrimming() {#getTrimming--}
```
public int getTrimming()
```


Λαμβάνει ή ορίζει την απαρίθμηση [StringTrimming](../../com.aspose.drawing/stringtrimming) για αυτό το αντικείμενο [StringFormat](../../com.aspose.drawing/stringformat).

**Returns:**
int
### setTrimming(int value) {#setTrimming-int-}
```
public void setTrimming(int value)
```


Λαμβάνει ή ορίζει την απαρίθμηση [StringTrimming](../../com.aspose.drawing/stringtrimming) για αυτό το αντικείμενο [StringFormat](../../com.aspose.drawing/stringformat).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getDigitSubstitutionLanguage() {#getDigitSubstitutionLanguage--}
```
public int getDigitSubstitutionLanguage()
```


Λαμβάνει τη γλώσσα που χρησιμοποιείται όταν τα τοπικά ψηφία αντικαθίστανται από δυτικά ψηφία.

**Returns:**
int - Ένα αναγνωριστικό γλώσσας National Language Support (NLS) που προσδιορίζει τη γλώσσα που θα χρησιμοποιηθεί όταν οι τοπικοί ψηφία αντικατασταθούν από δυτικά ψηφία. Μπορείτε να περάσετε την ιδιότητα `System.Globalization.CultureInfo.LCID` ενός αντικειμένου java.util.Locale ως το αναγνωριστικό γλώσσας NLS. Για παράδειγμα, υποθέστε ότι δημιουργείτε ένα αντικείμενο java.util.Locale περνώντας τη συμβολοσειρά "ar-EG" σε έναν κατασκευαστή java.util.Locale. Εάν περάσετε την ιδιότητα `System.Globalization.CultureInfo.LCID` αυτού του αντικειμένου java.util.Locale μαζί με`StringDigitSubstitute.Traditional` στη μέθοδο [.setDigitSubstitution(int,int)](../../null/\#setDigitSubstitution-int-int-), τότε τα αραβικά-ινδικά ψηφία θα αντικατασταθούν από δυτικά ψηφία κατά την εμφάνιση.
### getDigitSubstitutionMethod() {#getDigitSubstitutionMethod--}
```
public int getDigitSubstitutionMethod()
```


Λαμβάνει τη μέθοδο που θα χρησιμοποιηθεί για την αντικατάσταση ψηφίων.

**Returns:**
int - Μια τιμή απαρίθμησης [StringDigitSubstitute](../../com.aspose.drawing/stringdigitsubstitute) που καθορίζει πώς να αντικαταστήσετε χαρακτήρες σε μια συμβολοσειρά που δεν μπορεί να εμφανιστεί επειδή δεν υποστηρίζονται από την τρέχουσα γραμματοσειρά.
### dispose() {#dispose--}
```
public void dispose()
```


Απελευθερώνει όλους τους πόρους που χρησιμοποιούνται από αυτό το αντικείμενο [StringFormat](../../com.aspose.drawing/stringformat).

### deepClone() {#deepClone--}
```
public StringFormat deepClone()
```


Δημιουργεί ένα ακριβές αντίγραφο αυτού του αντικειμένου [StringFormat](../../com.aspose.drawing/stringformat).

**Returns:**
[StringFormat](../../com.aspose.drawing/stringformat) - The [StringFormat](../../com.aspose.drawing/stringformat) object this method creates.
### getTabStops(float[] firstTabOffset) {#getTabStops-float---}
```
public float[] getTabStops(float[] firstTabOffset)
```


Λαμβάνει τις διακοπές στήλης για αυτό το αντικείμενο [StringFormat](../../com.aspose.drawing/stringformat).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| firstTabOffset | float[] | Ο αριθμός των κενών μεταξύ της αρχής μιας γραμμής κειμένου και της πρώτης στάσης στηλοθέτη. |

**Returns:**
float[] - Ένας πίνακας αποστάσεων (σε αριθμό κενών) μεταξύ των στάσεων του στηλοθέτη.
### getTabStops() {#getTabStops--}
```
public float[] getTabStops()
```


Λαμβάνει έναν πίνακα αποστάσεων μεταξύ των διακοπών στήλης στις μονάδες που καθορίζονται από την ιδιότητα `Aspose.Imaging.getGraphics().PageUnit`.

**Returns:**
float[] - Οι στάσεις του στηλοθέτη.

Η ιδιότητα εισάγεται για την αφαιρεμένη μέθοδο GetTabStops.
### setTabStops(float firstTabOffset, float[] tabStops) {#setTabStops-float-float---}
```
public void setTabStops(float firstTabOffset, float[] tabStops)
```


Ορίζει τις διακοπές στήλης για αυτό το αντικείμενο [StringFormat](../../com.aspose.drawing/stringformat).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| firstTabOffset | float | Ο αριθμός των κενών μεταξύ της αρχής μιας γραμμής κειμένου και της πρώτης στάσης του στηλοθέτη. |
| tabStops | float[] | Ένας πίνακας αποστάσεων μεταξύ των στάσεων του στηλοθέτη στις μονάδες που καθορίζονται από την ιδιότητα Graphics.PageUnit. |

### setDigitSubstitution(int language, int substitute) {#setDigitSubstitution-int-int-}
```
public void setDigitSubstitution(int language, int substitute)
```


Καθορίζει τη γλώσσα και τη μέθοδο που θα χρησιμοποιηθούν όταν τα τοπικά ψηφία αντικαθίστανται από δυτικά ψηφία.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| γλώσσα | int | Ένα αναγνωριστικό γλώσσας National Language Support (NLS) που προσδιορίζει τη γλώσσα που θα χρησιμοποιηθεί όταν οι τοπικοί ψηφία αντικατασταθούν από δυτικά ψηφία. Μπορείτε να περάσετε την ιδιότητα `System.Globalization.CultureInfo.LCID` ενός αντικειμένου java.util.Locale ως το αναγνωριστικό γλώσσας NLS. Για παράδειγμα, υποθέστε ότι δημιουργείτε ένα αντικείμενο java.util.Locale περνώντας τη συμβολοσειρά `\"ar-EG\"` σε έναν κατασκευαστή java.util.Locale. Εάν περάσετε την ιδιότητα `System.Globalization.CultureInfo.LCID` αυτού του αντικειμένου java.util.Locale μαζί με `StringDigitSubstitute.Traditional` στη μέθοδο `M:StringFormat.SetDigitSubstitution(System.Int32,StringDigitSubstitute)`, τότε τα αραβικά-ινδικά ψηφία θα αντικατασταθούν από δυτικά ψηφία κατά την εμφάνιση. |
| substitute | int | Ένα στοιχείο της απαρίθμησης [StringDigitSubstitute](../../com.aspose.drawing/stringdigitsubstitute) που καθορίζει πώς εμφανίζονται τα ψηφία. |

### setMeasurableCharacterRanges(CharacterRange[] ranges) {#setMeasurableCharacterRanges-com.aspose.drawing.CharacterRange---}
```
public void setMeasurableCharacterRanges(CharacterRange[] ranges)
```


Καθορίζει έναν πίνακα δομών [CharacterRange](../../com.aspose.drawing/characterrange) που αντιπροσωπεύουν τις περιοχές χαρακτήρων που μετρώνται με μια κλήση στη μέθοδο `MeasureCharacterRanges`.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| ranges | [CharacterRange\[\]](../../com.aspose.drawing/characterrange) | Ένας πίνακας δομών [CharacterRange](../../com.aspose.drawing/characterrange) που καθορίζουν τα εύρη χαρακτήρων που μετρώνται με μια κλήση στη μέθοδο `MeasureCharacterRanges`. |

