---
title: BitmapData
second_title: Αναφορά API του Aspose.Drawing for Java
description: Καθορίζει τα χαρακτηριστικά μιας bitmap εικόνας.
type: docs
weight: 10
url: /el/java/com.aspose.drawing.imaging/bitmapdata/
---
**Inheritance:**
java.lang.Object
```
public final class BitmapData
```

Καθορίζει τα χαρακτηριστικά μιας bitmap εικόνας. Η κλάση [BitmapData](../../com.aspose.drawing.imaging/bitmapdata) χρησιμοποιείται από τις μεθόδους `E:Bitmap.LockBits` και `M:Bitmap.UnlockBits(BitmapData)` της κλάσης [Bitmap](../../com.aspose.drawing/bitmap). Δεν είναι κληρονομήσιμη.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [BitmapData()](#BitmapData--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getWidth()](#getWidth--) | Λαμβάνει το πλάτος σε pixel του αντικειμένου [Bitmap](../../com.aspose.drawing/bitmap). |
| [setWidth(int value)](#setWidth-int-) | Ορίζει το πλάτος σε pixel του αντικειμένου [Bitmap](../../com.aspose.drawing/bitmap). |
| [getHeight()](#getHeight--) | Λαμβάνει το ύψος σε pixel του αντικειμένου [Bitmap](../../com.aspose.drawing/bitmap). |
| [setHeight(int value)](#setHeight-int-) | Ορίζει το ύψος σε pixel του αντικειμένου [Bitmap](../../com.aspose.drawing/bitmap). |
| [getStride()](#getStride--) | Λαμβάνει το πλάτος stride (επίσης ονομάζεται πλάτος σάρωσης) του αντικειμένου [Bitmap](../../com.aspose.drawing/bitmap). |
| [setStride(int value)](#setStride-int-) | Ορίζει το πλάτος stride (επίσης ονομάζεται πλάτος σάρωσης) του αντικειμένου [Bitmap](../../com.aspose.drawing/bitmap). |
| [getPixelFormat()](#getPixelFormat--) | Λαμβάνει τη μορφή των πληροφοριών pixel στο αντικείμενο [Bitmap](../../com.aspose.drawing/bitmap) που επέστρεψε αυτό το αντικείμενο [BitmapData](../../com.aspose.drawing.imaging/bitmapdata). |
| [setPixelFormat(int value)](#setPixelFormat-int-) | Ορίζει τη μορφή των πληροφοριών pixel στο αντικείμενο [Bitmap](../../com.aspose.drawing/bitmap) που επέστρεψε αυτό το αντικείμενο [BitmapData](../../com.aspose.drawing.imaging/bitmapdata). |
| [getScan0()](#getScan0--) | Λαμβάνει τη διεύθυνση των πρώτων δεδομένων pixel στο bitmap. |
| [setScan0(int[] value)](#setScan0-int---) | Ορίζει τη διεύθυνση των πρώτων δεδομένων pixel στο bitmap. |
### BitmapData() {#BitmapData--}
```
public BitmapData()
```


### getWidth() {#getWidth--}
```
public int getWidth()
```


Λαμβάνει το πλάτος σε pixel του αντικειμένου [Bitmap](../../com.aspose.drawing/bitmap). Αυτό μπορεί επίσης να θεωρηθεί ως ο αριθμός των pixel σε μία γραμμή σάρωσης.

**Returns:**
int - Το πλάτος εικονοστοιχείου του αντικειμένου [Bitmap](../../com.aspose.drawing/bitmap).
### setWidth(int value) {#setWidth-int-}
```
public void setWidth(int value)
```


Ορίζει το πλάτος εικονοστοιχείου του αντικειμένου [Bitmap](../../com.aspose.drawing/bitmap). Αυτό μπορεί επίσης να θεωρηθεί ως ο αριθμός των εικονοστοιχείων σε μία γραμμή σάρωσης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int | το πλάτος εικονοστοιχείου του αντικειμένου [Bitmap](../../com.aspose.drawing/bitmap). |

### getHeight() {#getHeight--}
```
public int getHeight()
```


Αποκτά το ύψος εικονοστοιχείου του αντικειμένου [Bitmap](../../com.aspose.drawing/bitmap). Επίσης μερικές φορές αναφέρεται ως ο αριθμός των γραμμών σάρωσης.

**Returns:**
int - Το ύψος εικονοστοιχείου του αντικειμένου [Bitmap](../../com.aspose.drawing/bitmap).
### setHeight(int value) {#setHeight-int-}
```
public void setHeight(int value)
```


Ορίζει το ύψος εικονοστοιχείου του αντικειμένου [Bitmap](../../com.aspose.drawing/bitmap). Επίσης μερικές φορές αναφέρεται ως ο αριθμός των γραμμών σάρωσης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int | το ύψος εικονοστοιχείου του αντικειμένου [Bitmap](../../com.aspose.drawing/bitmap). |

### getStride() {#getStride--}
```
public int getStride()
```


Λαμβάνει το πλάτος stride (επίσης ονομάζεται πλάτος σάρωσης) του αντικειμένου [Bitmap](../../com.aspose.drawing/bitmap).

**Returns:**
int - Το πλάτος βήματος (stride), σε byte, του αντικειμένου [Bitmap](../../com.aspose.drawing/bitmap).
### setStride(int value) {#setStride-int-}
```
public void setStride(int value)
```


Ορίζει το πλάτος stride (επίσης ονομάζεται πλάτος σάρωσης) του αντικειμένου [Bitmap](../../com.aspose.drawing/bitmap).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int | το πλάτος βήματος (επίσης ονομάζεται πλάτος σάρωσης) του αντικειμένου [Bitmap](../../com.aspose.drawing/bitmap). |

### getPixelFormat() {#getPixelFormat--}
```
public int getPixelFormat()
```


Λαμβάνει τη μορφή των πληροφοριών pixel στο αντικείμενο [Bitmap](../../com.aspose.drawing/bitmap) που επέστρεψε αυτό το αντικείμενο [BitmapData](../../com.aspose.drawing.imaging/bitmapdata).

**Returns:**
int - Ένα `PixelFormat`([.getPixelFormat](../../null/\#getPixelFormat)/[.setPixelFormat(int)](../../null/\#setPixelFormat-int-)) που καθορίζει τη μορφή των πληροφοριών εικονοστοιχείου στο σχετικό αντικείμενο [Bitmap](../../com.aspose.drawing/bitmap).
### setPixelFormat(int value) {#setPixelFormat-int-}
```
public void setPixelFormat(int value)
```


Ορίζει τη μορφή των πληροφοριών pixel στο αντικείμενο [Bitmap](../../com.aspose.drawing/bitmap) που επέστρεψε αυτό το αντικείμενο [BitmapData](../../com.aspose.drawing.imaging/bitmapdata).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int | η μορφή των πληροφοριών εικονοστοιχείου στο αντικείμενο [Bitmap](../../com.aspose.drawing/bitmap) που επέστρεψε αυτό το αντικείμενο [BitmapData](../../com.aspose.drawing.imaging/bitmapdata). |

### getScan0() {#getScan0--}
```
public int[] getScan0()
```


Αποκτά τη διεύθυνση των πρώτων δεδομένων εικονοστοιχείου στο bitmap. Αυτό μπορεί επίσης να θεωρηθεί ως η πρώτη γραμμή σάρωσης στο bitmap.

**Returns:**
int[] - Η διεύθυνση των πρώτων δεδομένων εικονοστοιχείου στο bitmap.
### setScan0(int[] value) {#setScan0-int---}
```
public void setScan0(int[] value)
```


Ορίζει τη διεύθυνση των πρώτων δεδομένων εικονοστοιχείου στο bitmap. Αυτό μπορεί επίσης να θεωρηθεί ως η πρώτη γραμμή σάρωσης στο bitmap.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int[] | η διεύθυνση των πρώτων δεδομένων εικονοστοιχείου στο bitmap. |

