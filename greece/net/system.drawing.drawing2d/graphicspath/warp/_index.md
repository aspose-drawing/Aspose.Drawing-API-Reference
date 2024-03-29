---
title: GraphicsPath.Warp
second_title: Aspose.Drawing for .NET API Reference
description: GraphicsPath μέθοδος. Εφαρμόζει έναν μετασχηματισμό στημόνι που ορίζεται από ένα ορθογώνιο και ένα παραλληλόγραμμο σε αυτόGraphicsPath .
type: docs
weight: 350
url: /el/net/system.drawing.drawing2d/graphicspath/warp/
---
## Warp(PointF[], RectangleF) {#warp}

Εφαρμόζει έναν μετασχηματισμό στημόνι, που ορίζεται από ένα ορθογώνιο και ένα παραλληλόγραμμο, σε αυτό[`GraphicsPath`](../) .

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| destPoints | PointF[] | Μια σειρά απόPointF δομές που ορίζουν ένα παραλληλόγραμμο στο οποίο το ορθογώνιο ορίζεται από*srcRect*Το μετασχηματίζεται. Ο πίνακας μπορεί να περιέχει τρία ή τέσσερα στοιχεία. Εάν ο πίνακας περιέχει τρία στοιχεία, η κάτω δεξιά γωνία του παραλληλογράμμου υπονοείται από τα τρία πρώτα σημεία. |
| srcRect | RectangleF | ΕΝΑRectangleF που αντιπροσωπεύει το ορθογώνιο που μετατρέπεται στο παραλληλόγραμμο που ορίζεται από*destPoints* . |

### Δείτε επίσης

* struct [PointF](../../../system.drawing/pointf/)
* struct [RectangleF](../../../system.drawing/rectanglef/)
* class [GraphicsPath](../)
* χώρος ονομάτων [System.Drawing.Drawing2D](../../graphicspath/)
* συνέλευση [Aspose.Drawing](../../../)

---

## Warp(PointF[], RectangleF, Matrix) {#warp_1}

Εφαρμόζει έναν μετασχηματισμό στημόνι, που ορίζεται από ένα ορθογώνιο και ένα παραλληλόγραμμο, σε αυτό[`GraphicsPath`](../).

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| destPoints | PointF[] | Μια σειρά απόPointF δομές που ορίζουν ένα παραλληλόγραμμο στο οποίο το ορθογώνιο ορίζεται από*srcRect* Το μετασχηματίζεται. Ο πίνακας μπορεί να περιέχει τρία ή τέσσερα στοιχεία. Εάν ο πίνακας περιέχει τρία στοιχεία, η κάτω δεξιά γωνία του παραλληλογράμμου υπονοείται από τα τρία πρώτα σημεία. |
| srcRect | RectangleF | ΕΝΑRectangleF που αντιπροσωπεύει το ορθογώνιο που μετατρέπεται στο παραλληλόγραμμο που ορίζεται από*destPoints* . |
| matrix | Matrix | ΕΝΑ[`Matrix`](../../matrix/) που καθορίζει έναν γεωμετρικό μετασχηματισμό που θα εφαρμοστεί στη διαδρομή. |

### Δείτε επίσης

* struct [PointF](../../../system.drawing/pointf/)
* struct [RectangleF](../../../system.drawing/rectanglef/)
* class [Matrix](../../matrix/)
* class [GraphicsPath](../)
* χώρος ονομάτων [System.Drawing.Drawing2D](../../graphicspath/)
* συνέλευση [Aspose.Drawing](../../../)

---

## Warp(PointF[], RectangleF, Matrix, WarpMode) {#warp_2}

Εφαρμόζει έναν μετασχηματισμό στημόνι, που ορίζεται από ένα ορθογώνιο και ένα παραλληλόγραμμο, σε αυτό[`GraphicsPath`](../).

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, WarpMode warpMode)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| destPoints | PointF[] | Μια σειρά απόPointF δομές που ορίζει ένα παραλληλόγραμμο στο οποίο το ορθογώνιο ορίζεται από*srcRect*Το μετασχηματίζεται. Ο πίνακας μπορεί να περιέχει τρία ή τέσσερα στοιχεία. Εάν ο πίνακας περιέχει τρία στοιχεία, η κάτω δεξιά γωνία του παραλληλογράμμου υπονοείται από τα τρία πρώτα σημεία. |
| srcRect | RectangleF | ΕΝΑRectangleF που αντιπροσωπεύει το ορθογώνιο που μετατρέπεται στο παραλληλόγραμμο που ορίζεται από*destPoints* . |
| matrix | Matrix | ΕΝΑ[`Matrix`](../../matrix/) που καθορίζει έναν γεωμετρικό μετασχηματισμό που θα εφαρμοστεί στη διαδρομή. |
| warpMode | WarpMode | ΕΝΑ[`WarpMode`](../../warpmode/) απαρίθμηση που καθορίζει εάν αυτή η λειτουργία παραμόρφωσης χρησιμοποιεί προοπτική ή διγραμμική λειτουργία. |

### Δείτε επίσης

* struct [PointF](../../../system.drawing/pointf/)
* struct [RectangleF](../../../system.drawing/rectanglef/)
* class [Matrix](../../matrix/)
* enum [WarpMode](../../warpmode/)
* class [GraphicsPath](../)
* χώρος ονομάτων [System.Drawing.Drawing2D](../../graphicspath/)
* συνέλευση [Aspose.Drawing](../../../)

---

## Warp(PointF[], RectangleF, Matrix, WarpMode, float) {#warp_3}

Εφαρμόζει έναν μετασχηματισμό στημόνι, που ορίζεται από ένα ορθογώνιο και ένα παραλληλόγραμμο, σε αυτό[`GraphicsPath`](../).

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, WarpMode warpMode, 
    float flatness)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| destPoints | PointF[] | Μια σειρά απόPointF δομές που ορίζουν ένα παραλληλόγραμμο στο οποίο το ορθογώνιο ορίζεται από*srcRect*Το μετασχηματίζεται. Ο πίνακας μπορεί να περιέχει τρία ή τέσσερα στοιχεία. Εάν ο πίνακας περιέχει τρία στοιχεία, η κάτω δεξιά γωνία του παραλληλογράμμου υπονοείται από τα τρία πρώτα σημεία. |
| srcRect | RectangleF | ΕΝΑRectangleF που αντιπροσωπεύει το ορθογώνιο που μετατρέπεται στο παραλληλόγραμμο που ορίζεται από*destPoints* . |
| matrix | Matrix | ΕΝΑ[`Matrix`](../../matrix/) που καθορίζει έναν γεωμετρικό μετασχηματισμό που θα εφαρμοστεί στη διαδρομή. |
| warpMode | WarpMode | ΕΝΑ[`WarpMode`](../../warpmode/) απαρίθμηση που καθορίζει εάν αυτή η λειτουργία παραμόρφωσης χρησιμοποιεί προοπτική ή διγραμμική λειτουργία. |
| flatness | Single | Μια τιμή από το 0 έως το 1 που καθορίζει πόσο επίπεδη είναι η διαδρομή που προκύπτει. Για περισσότερες πληροφορίες, δείτε το[`Flatten`](../flatten/) μεθόδους. |

### Δείτε επίσης

* struct [PointF](../../../system.drawing/pointf/)
* struct [RectangleF](../../../system.drawing/rectanglef/)
* class [Matrix](../../matrix/)
* enum [WarpMode](../../warpmode/)
* class [GraphicsPath](../)
* χώρος ονομάτων [System.Drawing.Drawing2D](../../graphicspath/)
* συνέλευση [Aspose.Drawing](../../../)


