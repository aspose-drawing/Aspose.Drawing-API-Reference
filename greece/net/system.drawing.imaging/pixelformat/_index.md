---
title: Enum PixelFormat
second_title: Aspose.Drawing for .NET API Reference
description: System.Drawing.Imaging.PixelFormat αρίθμηση. Καθορίζει τη μορφή των δεδομένων χρώματος για κάθε pixel στην εικόνα.
type: docs
weight: 850
url: /el/net/system.drawing.imaging/pixelformat/
---
## PixelFormat enumeration

Καθορίζει τη μορφή των δεδομένων χρώματος για κάθε pixel στην εικόνα.

```csharp
public enum PixelFormat
```

### Αξίες

| Ονομα | αξία | Περιγραφή |
| --- | --- | --- |
| Indexed | `65536` | Τα δεδομένα εικονοστοιχείων περιέχουν τιμές με ευρετήριο χρώματος, πράγμα που σημαίνει ότι οι τιμές είναι ένας δείκτης χρωμάτων στον πίνακα χρωμάτων του συστήματος, σε αντίθεση με μεμονωμένες τιμές χρώματος. |
| Gdi | `131072` | Τα δεδομένα pixel περιέχουν χρώματα GDI. |
| Alpha | `262144` | Τα δεδομένα εικονοστοιχείων περιέχουν τιμές άλφα που δεν έχουν προπολλαπλασιαστεί. |
| PAlpha | `524288` | Η μορφή pixel περιέχει προπολλαπλασιασμένες τιμές άλφα. |
| Extended | `1048576` | Δεσμευμένη τιμή. |
| Canonical | `2097152` | Η προεπιλεγμένη μορφή pixel των 32 bit ανά pixel. Η μορφή καθορίζει βάθος χρώματος 24 bit και ένα κανάλι άλφα 8 bit. |
| Undefined | `0` | Η μορφή pixel δεν έχει καθοριστεί. |
| DontCare | `0` | Δεν έχει καθοριστεί μορφή pixel. |
| Format1bppIndexed | `196865` | Καθορίζει ότι η μορφή pixel είναι 1 bit ανά εικονοστοιχείο και ότι χρησιμοποιεί χρώμα με ευρετήριο. Επομένως, ο πίνακας χρωμάτων έχει δύο χρώματα. |
| Format4bppIndexed | `197634` | Καθορίζει ότι η μορφή είναι 4 bit ανά pixel, με ευρετήριο. |
| Format8bppIndexed | `198659` | Καθορίζει ότι η μορφή είναι 8 bit ανά pixel, με ευρετήριο. Επομένως, ο πίνακας χρωμάτων έχει 256 χρώματα. |
| Format16bppGrayScale | `1052676` | Η μορφή pixel είναι 16 bit ανά pixel. Οι πληροφορίες χρώματος καθορίζουν 65536 αποχρώσεις του γκρι. |
| Format16bppRgb555 | `135173` | Καθορίζει ότι η μορφή είναι 16 bit ανά pixel. 5 bit το καθένα χρησιμοποιούνται για τα κόκκινα, πράσινα και μπλε στοιχεία. Το υπόλοιπο bit δεν χρησιμοποιείται. |
| Format16bppRgb565 | `135174` | Καθορίζει ότι η μορφή είναι 16 bit ανά pixel. Χρησιμοποιούνται 5 bit για το κόκκινο στοιχείο, 6 bit για το πράσινο στοιχείο και 5 bit για το μπλε στοιχείο. |
| Format16bppArgb1555 | `397319` | Η μορφή pixel είναι 16 bit ανά pixel. Οι πληροφορίες χρώματος καθορίζουν 32.768 αποχρώσεις χρώματος, εκ των οποίων 5 bit είναι κόκκινο, 5 bit είναι πράσινο, 5 bit είναι μπλε και 1 bit είναι άλφα. |
| Format24bppRgb | `137224` | Καθορίζει ότι η μορφή είναι 24 bit ανά pixel. 8 bit το καθένα χρησιμοποιούνται για τα κόκκινα, πράσινο και μπλε στοιχεία. |
| Format32bppRgb | `139273` | Καθορίζει ότι η μορφή είναι 32 bit ανά pixel. 8 bit το καθένα χρησιμοποιούνται για τα κόκκινα, πράσινα και μπλε στοιχεία. Τα υπόλοιπα 8 bit δεν χρησιμοποιούνται. |
| Format32bppArgb | `2498570` | Καθορίζει ότι η μορφή είναι 32 bit ανά pixel. 8 bit το καθένα χρησιμοποιούνται για τα στοιχεία άλφα, κόκκινο, πράσινο και μπλε. |
| Format32bppPArgb | `925707` | Καθορίζει ότι η μορφή είναι 32 bit ανά pixel. 8 bit το καθένα χρησιμοποιούνται για τα στοιχεία άλφα, κόκκινο, πράσινο και μπλε. Τα κόκκινα, πράσινα και μπλε στοιχεία προπολλαπλασιάζονται, σύμφωνα με το στοιχείο άλφα. |
| Format48bppRgb | `1060876` | Καθορίζει ότι η μορφή είναι 48 bit ανά pixel. 16 bit το καθένα χρησιμοποιούνται για τα κόκκινα, πράσινο και μπλε στοιχεία. |
| Format64bppArgb | `3424269` | Καθορίζει ότι η μορφή είναι 64 bit ανά pixel. 16 bit το καθένα χρησιμοποιούνται για τα στοιχεία άλφα, κόκκινο, πράσινο και μπλε. |
| Format64bppPArgb | `1851406` | Καθορίζει ότι η μορφή είναι 64 bit ανά pixel. 16 bit το καθένα χρησιμοποιούνται για τα στοιχεία άλφα, κόκκινο, πράσινο και μπλε. Τα κόκκινα, πράσινα και μπλε στοιχεία είναι προπολλαπλασιασμένα σύμφωνα με το στοιχείο άλφα. |
| Max | `15` | Η μέγιστη τιμή για αυτήν την απαρίθμηση. |

### Δείτε επίσης

* χώρος ονομάτων [System.Drawing.Imaging](../../system.drawing.imaging/)
* συνέλευση [Aspose.Drawing](../../)


