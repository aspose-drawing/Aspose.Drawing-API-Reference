---
title: StringFormatFlags
second_title: Aspose.Drawing för Java API‑referens
description: Anger visnings- och layoutinformation för textsträngar.
type: docs
weight: 48
url: /sv/java/com.aspose.drawing/stringformatflags/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class StringFormatFlags extends System.Enum
```

Anger visnings- och layoutinformation för textsträngar.
## Fält

| Fält | Beskrivning |
| --- | --- |
| [DirectionRightToLeft](#DirectionRightToLeft) | Text visas från höger till vänster. |
| [DirectionVertical](#DirectionVertical) | Text är vertikalt justerad. |
| [FitBlackBox](#FitBlackBox) | Delar av tecken får överskjuta strängens layoutrektangel. |
| [DisplayFormatControl](#DisplayFormatControl) | Kontrolltecken såsom vänster-till-höger-markering visas i utdata med ett representativt glyf. |
| [NoFontFallback](#NoFontFallback) | Reserv till alternativa teckensnitt för tecken som inte stöds i det begärda teckensnittet är inaktiverad. |
| [MeasureTrailingSpaces](#MeasureTrailingSpaces) | Inkluderar efterföljande mellanslag i slutet av varje rad. |
| [NoWrap](#NoWrap) | Textbrytning mellan rader vid formatering inom en rektangel är inaktiverad. |
| [LineLimit](#LineLimit) | Endast hela rader läggs ut i formateringsrektangeln. |
| [NoClip](#NoClip) | Överskjutande delar av glyfer och oinsvept text som når utanför formateringsrektangeln får visas. |
| [ExactAlignment](#ExactAlignment) | Den exakta justeringen, korrekt padding GDI+ |
### DirectionRightToLeft {#DirectionRightToLeft}
```
public static final int DirectionRightToLeft
```


Text visas från höger till vänster.

### DirectionVertical {#DirectionVertical}
```
public static final int DirectionVertical
```


Text är vertikalt justerad.

### FitBlackBox {#FitBlackBox}
```
public static final int FitBlackBox
```


Delar av tecken får överskjuta strängens layoutrektangel. Som standard omplaceras tecken för att undvika någon överskjutning.

### DisplayFormatControl {#DisplayFormatControl}
```
public static final int DisplayFormatControl
```


Kontrolltecken såsom vänster-till-höger-markering visas i utdata med ett representativt glyf.

### NoFontFallback {#NoFontFallback}
```
public static final int NoFontFallback
```


Reserv till alternativa teckensnitt för tecken som inte stöds i det begärda teckensnittet är inaktiverad. Alla saknade tecken visas med teckensnittets saknade glyf, vanligtvis en öppen fyrkant.

### MeasureTrailingSpaces {#MeasureTrailingSpaces}
```
public static final int MeasureTrailingSpaces
```


Inkluderar efterföljande mellanslag i slutet av varje rad. Som standard exkluderar gränsrektangeln som returneras av MeasureString‑metoden mellanslaget i slutet av varje rad. Ställ in detta flagg för att inkludera det mellanslaget i mätningen.

### NoWrap {#NoWrap}
```
public static final int NoWrap
```


Textbrytning mellan rader vid formatering inom en rektangel är inaktiverad. Detta flagg antas när en punkt skickas istället för en rektangel, eller när den angivna rektangeln har en noll linjelängd.

### LineLimit {#LineLimit}
```
public static final int LineLimit
```


Endast hela rader läggs ut i formateringsrektangeln. Som standard fortsätter layouten tills slutet av texten, eller tills inga fler rader är synliga som ett resultat av beskärning, vilket som kommer först. Observera att standardinställningarna tillåter den sista raden att delvis döljas av en formateringsrektangel som inte är ett helt multipel av radens höjd. För att säkerställa att endast hela rader visas, ange detta värde och var noga med att tillhandahålla en formateringsrektangel som är minst lika hög som höjden på en rad.

### NoClip {#NoClip}
```
public static final int NoClip
```


Utskjutande delar av glyfer och oindelad text som sträcker sig utanför formateringsrektangeln får visas. Som standard klipps all text och glyfdelar som sträcker sig utanför formateringsrektangeln.

### ExactAlignment {#ExactAlignment}
```
public static final int ExactAlignment
```


Den exakta justeringen, korrekt padding GDI+

