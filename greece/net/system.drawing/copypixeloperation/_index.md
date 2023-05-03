---
title: Enum CopyPixelOperation
second_title: Aspose.Drawing for .NET API Reference
description: System.Drawing.CopyPixelOperation αρίθμηση. Καθορίζει πώς το χρώμα προέλευσης σε μια λειτουργία εικονοστοιχείων αντιγραφής συνδυάζεται με το χρώμα προορισμού για να οδηγήσει σε ένα τελικό χρώμα.
type: docs
weight: 120
url: /el/net/system.drawing/copypixeloperation/
---
## CopyPixelOperation enumeration

Καθορίζει πώς το χρώμα προέλευσης σε μια λειτουργία εικονοστοιχείων αντιγραφής συνδυάζεται με το χρώμα προορισμού για να οδηγήσει σε ένα τελικό χρώμα.

```csharp
public enum CopyPixelOperation
```

### Αξίες

| Ονομα | αξία | Περιγραφή |
| --- | --- | --- |
| NoMirrorBitmap | `-2147483648` | Το bitmap δεν αντικατοπτρίζεται. |
| Blackness | `66` | Η περιοχή προορισμού συμπληρώνεται χρησιμοποιώντας το χρώμα που σχετίζεται με το δείκτη 0 στη φυσική παλέτα. (Αυτό το χρώμα είναι μαύρο για την προεπιλεγμένη φυσική παλέτα.) |
| NotSourceErase | `1114278` | Τα χρώματα προέλευσης και προορισμού συνδυάζονται χρησιμοποιώντας το Boolean`Ή` τελεστής, και στη συνέχεια το προκύπτον χρώμα αντιστρέφεται. |
| NotSourceCopy | `3342344` | Η περιοχή ανεστραμμένης πηγής αντιγράφεται στον προορισμό. |
| SourceErase | `4457256` | Τα ανεστραμμένα χρώματα της περιοχής προορισμού συνδυάζονται με τα χρώματα της περιοχής προέλευσης χρησιμοποιώντας το Boolean`ΚΑΙ` χειριστής. |
| DestinationInvert | `5570569` | Η περιοχή προορισμού είναι ανεστραμμένη. |
| PatInvert | `5898313` | Τα χρώματα του πινέλου που επιλέγονται αυτήν τη στιγμή στο περιβάλλον της συσκευής προορισμού συνδυάζονται με τα χρώματα του προορισμού χρησιμοποιούν το Boolean`XOR` χειριστής. |
| SourceInvert | `6684742` | Τα χρώματα των περιοχών πηγής και προορισμού συνδυάζονται χρησιμοποιώντας το Boolean`XOR` χειριστής. |
| SourceAnd | `8913094` | Τα χρώματα των περιοχών πηγής και προορισμού συνδυάζονται χρησιμοποιώντας το Boolean`ΚΑΙ` χειριστής. |
| MergePaint | `12255782` | Τα χρώματα της περιοχής ανεστραμμένης πηγής συγχωνεύονται με τα χρώματα της περιοχής προορισμού χρησιμοποιώντας το Boolean`Ή` χειριστής. |
| MergeCopy | `12583114` | Τα χρώματα της περιοχής προέλευσης συγχωνεύονται με τα χρώματα του επιλεγμένου πινέλου του περιβάλλοντος της συσκευής προορισμού χρησιμοποιώντας το Boolean`ΚΑΙ` χειριστής. |
| SourceCopy | `13369376` | Η περιοχή προέλευσης αντιγράφεται απευθείας στην περιοχή προορισμού. |
| SourcePaint | `15597702` | Τα χρώματα των περιοχών πηγής και προορισμού συνδυάζονται χρησιμοποιώντας το Boolean`Ή` χειριστής. |
| PatCopy | `15728673` | Το πινέλο που έχει επιλεγεί αυτήν τη στιγμή στο περιβάλλον της συσκευής προορισμού αντιγράφεται στο bitmap προορισμού. |
| PatPaint | `16452105` | Τα χρώματα του πινέλου που επιλέγονται αυτήν τη στιγμή στο περιβάλλον της συσκευής προορισμού συνδυάζονται με τα χρώματα της περιοχής ανεστραμμένης πηγής χρησιμοποιώντας το Boolean`Ή` χειριστής. Το αποτέλεσμα αυτής της λειτουργίας συνδυάζεται με τα χρώματα της περιοχής προορισμού χρησιμοποιώντας το Boolean`Ή` χειριστής. |
| Whiteness | `16711778` | Η περιοχή προορισμού συμπληρώνεται χρησιμοποιώντας το χρώμα που σχετίζεται με το ευρετήριο 1 στη φυσική παλέτα. (Αυτό το χρώμα είναι λευκό για την προεπιλεγμένη φυσική παλέτα.) |
| CaptureBlt | `1073741824` | Τα Windows που είναι τοποθετημένα στο επάνω μέρος του παραθύρου σας περιλαμβάνονται στην εικόνα που προκύπτει. Από προεπιλογή, η εικόνα περιέχει μόνο το παράθυρό σας. Λάβετε υπόψη ότι αυτό γενικά δεν μπορεί να χρησιμοποιηθεί για την εκτύπωση περιεχομένων συσκευών. |

### Δείτε επίσης

* χώρος ονομάτων [System.Drawing](../../system.drawing/)
* συνέλευση [Aspose.Drawing](../../)

