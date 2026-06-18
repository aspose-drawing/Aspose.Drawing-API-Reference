---
title: ColorPalette
second_title: Αναφορά API του Aspose.Drawing for Java
description: Ορίζει έναν πίνακα χρωμάτων που αποτελούν μια παλέτα χρωμάτων.
type: docs
weight: 16
url: /el/java/com.aspose.drawing.imaging/colorpalette/
---
**Inheritance:**
java.lang.Object
```
public final class ColorPalette
```

Ορίζει έναν πίνακα χρωμάτων που αποτελούν μια παλέτα χρωμάτων. Τα χρώματα είναι 32-bit ARGB χρώματα. Δεν κληρονομείται.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [ColorPalette(int count)](#ColorPalette-int-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης `ColorPalette` και το IsCompactPalette είναι ψευδές. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getEntries()](#getEntries--) | Λαμβάνει έναν πίνακα δομών `com.aspose.drawing.Color`. |
| [isCompactPalette()](#isCompactPalette--) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν χρησιμοποιείται συμπαγής παλέτα. |
| [getFlags()](#getFlags--) |  |
| [setFlags(int flags)](#setFlags-int-) |  |
| [setEntries(int i, Color color)](#setEntries-int-com.aspose.drawing.Color-) |  |
### ColorPalette(int count) {#ColorPalette-int-}
```
public ColorPalette(int count)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης `ColorPalette` και το IsCompactPalette είναι ψευδές.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| count | int | Οι καταχωρίσεις της παλέτας χρωμάτων. |

### getEntries() {#getEntries--}
```
public Color[] getEntries()
```


Λαμβάνει έναν πίνακα δομών `com.aspose.drawing.Color`.

**Returns:**
com.aspose.drawing.Color[] - Οι καταχωρίσεις. Ο πίνακας δομών `com.aspose.drawing.Color` που αποτελούν αυτήν την `Aspose.Imaging.ColorPalette`.
### isCompactPalette() {#isCompactPalette--}
```
public boolean isCompactPalette()
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν χρησιμοποιείται συμπαγής παλέτα.

**Returns:**
boolean - `true` εάν χρησιμοποιείται συμπαγής παλέτα· διαφορετικά, `false`.

Η συμπαγής παλέτα σημαίνει ότι η εικόνα θα περιέχει μόνο τις καθορισμένες καταχωρίσεις παλέτας εάν είναι δυνατόν, ή με άλλα λόγια η εικόνα θα είναι πιο συμπαγής και θα καταλαμβάνει λιγότερο χώρο· διαφορετικά θα υπάρχουν καταχωρίσεις 2^BitsPerPixel και η εικόνα θα διατηρεί περισσότερο χώρο για όλες τις πιθανές καταχωρίσεις παλέτας. Ο καθορισμός αυτής της τιμής σε true και η αλλαγή των καταχωρίσεων της παλέτας μπορεί να προκαλέσει ποινή απόδοσης, καθώς μπορεί να συμβεί μετακίνηση δεδομένων, επομένως χρησιμοποιήστε το προσεκτικά.
### getFlags() {#getFlags--}
```
public int getFlags()
```




**Returns:**
int
### setFlags(int flags) {#setFlags-int-}
```
public void setFlags(int flags)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| flags | int |  |

### setEntries(int i, Color color) {#setEntries-int-com.aspose.drawing.Color-}
```
public void setEntries(int i, Color color)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| i | int |  |
| color | [Color](../../com.aspose.drawing/color) |  |

