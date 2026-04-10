---
title: PixelFormat
second_title: Αναφορά API του Aspose.Drawing for Java
description: Καθορίζει τη μορφή των δεδομένων χρώματος για κάθε εικονοστοιχείο στην εικόνα.
type: docs
weight: 34
url: /el/java/com.aspose.drawing.imaging/pixelformat/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PixelFormat extends System.Enum
```

Καθορίζει τη μορφή των δεδομένων χρώματος για κάθε εικονοστοιχείο στην εικόνα.
## Fields

| Field | Περιγραφή |
| --- | --- |
| [Indexed](#Indexed) | Τα δεδομένα εικονοστοιχείου περιέχουν τιμές χρωματικού δείκτη, πράγμα που σημαίνει ότι οι τιμές είναι δείκτης σε χρώματα στον πίνακα χρωμάτων του συστήματος, αντί για μεμονωμένες τιμές χρώματος. |
| [Gdi](#Gdi) | Τα δεδομένα εικονοστοιχείου περιέχουν χρώματα GDI. |
| [Alpha](#Alpha) | Τα δεδομένα εικονοστοιχείου περιέχουν τιμές άλφα που δεν είναι προπολλαπλασιασμένες. |
| [PAlpha](#PAlpha) | Η μορφή εικονοστοιχείου περιέχει προπολλαπλασιασμένες τιμές άλφα. |
| [Extended](#Extended) | Δεσμευμένη τιμή. |
| [Canonical](#Canonical) | Η προεπιλεγμένη μορφή εικονοστοιχείου των 32 bit ανά εικονοστοιχείο. |
| [Undefined](#Undefined) | Η μορφή εικονοστοιχείου δεν έχει οριστεί. |
| [DontCare](#DontCare) | Δεν έχει καθοριστεί μορφή εικονοστοιχείου. |
| [Format1bppIndexed](#Format1bppIndexed) | Καθορίζει ότι η μορφή εικονοστοιχείου είναι 1 bit ανά εικονοστοιχείο και ότι χρησιμοποιεί χρώμα με δείκτη. |
| [Format4bppIndexed](#Format4bppIndexed) | Καθορίζει ότι η μορφή είναι 4 bit ανά εικονοστοιχείο, με δείκτη. |
| [Format8bppIndexed](#Format8bppIndexed) | Καθορίζει ότι η μορφή είναι 8 bit ανά εικονοστοιχείο, με δείκτη. |
| [Format16bppGrayScale](#Format16bppGrayScale) | Η μορφή εικονοστοιχείου είναι 16 bit ανά εικονοστοιχείο. |
| [Format16bppRgb555](#Format16bppRgb555) | Καθορίζει ότι η μορφή είναι 16 bit ανά εικονοστοιχείο· 5 bit χρησιμοποιούνται για τα κόκκινα, πράσινα και μπλε συστατικά. |
| [Format16bppRgb565](#Format16bppRgb565) | Καθορίζει ότι η μορφή είναι 16 bit ανά εικονοστοιχείο· 5 bit χρησιμοποιούνται για το κόκκινο συστατικό, 6 bit για το πράσινο συστατικό και 5 bit για το μπλε συστατικό. |
| [Format16bppArgb1555](#Format16bppArgb1555) | Η μορφή εικονοστοιχείου είναι 16 bit ανά εικονοστοιχείο. |
| [Format24bppRgb](#Format24bppRgb) | Καθορίζει ότι η μορφή είναι 24 bit ανά εικονοστοιχείο· 8 bit χρησιμοποιούνται για τα κόκκινα, πράσινα και μπλε συστατικά. |
| [Format32bppRgb](#Format32bppRgb) | Καθορίζει ότι η μορφή είναι 32 bit ανά εικονοστοιχείο· 8 bit χρησιμοποιούνται για τα κόκκινα, πράσινα και μπλε συστατικά. |
| [Format32bppArgb](#Format32bppArgb) | Καθορίζει ότι η μορφή είναι 32 bit ανά εικονοστοιχείο· 8 bit χρησιμοποιούνται για τα άλφα, κόκκινα, πράσινα και μπλε συστατικά. |
| [Format32bppPArgb](#Format32bppPArgb) | Καθορίζει ότι η μορφή είναι 32 bit ανά εικονοστοιχείο· 8 bit χρησιμοποιούνται για τα άλφα, κόκκινα, πράσινα και μπλε συστατικά. |
| [Format48bppRgb](#Format48bppRgb) | Καθορίζει ότι η μορφή είναι 48 bit ανά εικονοστοιχείο· 16 bit χρησιμοποιούνται για τα κόκκινα, πράσινα και μπλε συστατικά. |
| [Format64bppArgb](#Format64bppArgb) | Καθορίζει ότι η μορφή είναι 64 bit ανά εικονοστοιχείο· 16 bit χρησιμοποιούνται για τα άλφα, κόκκινα, πράσινα και μπλε συστατικά. |
| [Format64bppPArgb](#Format64bppPArgb) | Καθορίζει ότι η μορφή είναι 64 bit ανά εικονοστοιχείο· 16 bit χρησιμοποιούνται για τα άλφα, κόκκινα, πράσινα και μπλε συστατικά. |
| [Max](#Max) | Η μέγιστη τιμή για αυτήν την απαρίθμηση. |
### Indexed {#Indexed}
```
public static final int Indexed
```


Τα δεδομένα εικονοστοιχείου περιέχουν τιμές χρωματικού δείκτη, πράγμα που σημαίνει ότι οι τιμές είναι δείκτης σε χρώματα στον πίνακα χρωμάτων του συστήματος, αντί για μεμονωμένες τιμές χρώματος.

### Gdi {#Gdi}
```
public static final int Gdi
```


Τα δεδομένα εικονοστοιχείου περιέχουν χρώματα GDI.

### Alpha {#Alpha}
```
public static final int Alpha
```


Τα δεδομένα εικονοστοιχείου περιέχουν τιμές άλφα που δεν είναι προπολλαπλασιασμένες.

### PAlpha {#PAlpha}
```
public static final int PAlpha
```


Η μορφή εικονοστοιχείου περιέχει προπολλαπλασιασμένες τιμές άλφα.

### Extended {#Extended}
```
public static final int Extended
```


Δεσμευμένη τιμή.

### Canonical {#Canonical}
```
public static final int Canonical
```


Η προεπιλεγμένη μορφή εικονοστοιχείου είναι 32 bit ανά εικονοστοιχείο. Η μορφή καθορίζει βάθος χρώματος 24‑bit και κανάλι άλφα 8‑bit.

### Undefined {#Undefined}
```
public static final int Undefined
```


Η μορφή εικονοστοιχείου δεν έχει οριστεί.

### DontCare {#DontCare}
```
public static final int DontCare
```


Δεν έχει καθοριστεί μορφή εικονοστοιχείου.

### Format1bppIndexed {#Format1bppIndexed}
```
public static final int Format1bppIndexed
```


Καθορίζει ότι η μορφή εικονοστοιχείου είναι 1 bit ανά εικονοστοιχείο και χρησιμοποιεί χρωματική παλέτα. Συνεπώς, ο πίνακας χρωμάτων περιέχει δύο χρώματα.

### Format4bppIndexed {#Format4bppIndexed}
```
public static final int Format4bppIndexed
```


Καθορίζει ότι η μορφή είναι 4 bit ανά εικονοστοιχείο, με δείκτη.

### Format8bppIndexed {#Format8bppIndexed}
```
public static final int Format8bppIndexed
```


Καθορίζει ότι η μορφή είναι 8 bit ανά εικονοστοιχείο, με παλέτα. Συνεπώς, ο πίνακας χρωμάτων περιέχει 256 χρώματα.

### Format16bppGrayScale {#Format16bppGrayScale}
```
public static final int Format16bppGrayScale
```


Η μορφή εικονοστοιχείου είναι 16 bit ανά εικονοστοιχείο. Η πληροφορία χρώματος καθορίζει 65 536 αποχρώσεις του γκρι.

### Format16bppRgb555 {#Format16bppRgb555}
```
public static final int Format16bppRgb555
```


Καθορίζει ότι η μορφή είναι 16 bit ανά εικονοστοιχείο· 5 bit χρησιμοποιούνται για τα κόκκινα, πράσινα και μπλε συστατικά. Το υπόλοιπο bit δεν χρησιμοποιείται.

### Format16bppRgb565 {#Format16bppRgb565}
```
public static final int Format16bppRgb565
```


Καθορίζει ότι η μορφή είναι 16 bit ανά εικονοστοιχείο· 5 bit χρησιμοποιούνται για το κόκκινο συστατικό, 6 bit για το πράσινο συστατικό και 5 bit για το μπλε συστατικό.

### Format16bppArgb1555 {#Format16bppArgb1555}
```
public static final int Format16bppArgb1555
```


Η μορφή εικονοστοιχείου είναι 16 bit ανά εικονοστοιχείο. Η πληροφορία χρώματος καθορίζει 32 768 αποχρώσεις χρώματος, από τις οποίες 5 bit είναι κόκκινα, 5 bit είναι πράσινα, 5 bit είναι μπλε και 1 bit είναι άλφα.

### Format24bppRgb {#Format24bppRgb}
```
public static final int Format24bppRgb
```


Καθορίζει ότι η μορφή είναι 24 bit ανά εικονοστοιχείο· 8 bit χρησιμοποιούνται για τα κόκκινα, πράσινα και μπλε συστατικά.

### Format32bppRgb {#Format32bppRgb}
```
public static final int Format32bppRgb
```


Καθορίζει ότι η μορφή είναι 32 bit ανά εικονοστοιχείο· 8 bit χρησιμοποιούνται για τα κόκκινα, πράσινα και μπλε συστατικά. Τα υπόλοιπα 8 bit δεν χρησιμοποιούνται.

### Format32bppArgb {#Format32bppArgb}
```
public static final int Format32bppArgb
```


Καθορίζει ότι η μορφή είναι 32 bit ανά εικονοστοιχείο· 8 bit χρησιμοποιούνται για τα άλφα, κόκκινα, πράσινα και μπλε συστατικά.

### Format32bppPArgb {#Format32bppPArgb}
```
public static final int Format32bppPArgb
```


Καθορίζει ότι η μορφή είναι 32 bit ανά εικονοστοιχείο· 8 bit χρησιμοποιούνται για τα άλφα, κόκκινα, πράσινα και μπλε συστατικά. Τα κόκκινα, πράσινα και μπλε συστατικά είναι προπολλαπλασιασμένα σύμφωνα με το συστατικό άλφα.

### Format48bppRgb {#Format48bppRgb}
```
public static final int Format48bppRgb
```


Καθορίζει ότι η μορφή είναι 48 bit ανά εικονοστοιχείο· 16 bit χρησιμοποιούνται για τα κόκκινα, πράσινα και μπλε συστατικά.

### Format64bppArgb {#Format64bppArgb}
```
public static final int Format64bppArgb
```


Καθορίζει ότι η μορφή είναι 64 bit ανά εικονοστοιχείο· 16 bit χρησιμοποιούνται για τα άλφα, κόκκινα, πράσινα και μπλε συστατικά.

### Format64bppPArgb {#Format64bppPArgb}
```
public static final int Format64bppPArgb
```


Καθορίζει ότι η μορφή είναι 64 bit ανά εικονοστοιχείο· 16 bit χρησιμοποιούνται για τα άλφα, κόκκινα, πράσινα και μπλε συστατικά. Τα κόκκινα, πράσινα και μπλε συστατικά είναι προπολλαπλασιασμένα σύμφωνα με το συστατικό άλφα.

### Max {#Max}
```
public static final int Max
```


Η μέγιστη τιμή για αυτήν την απαρίθμηση.

