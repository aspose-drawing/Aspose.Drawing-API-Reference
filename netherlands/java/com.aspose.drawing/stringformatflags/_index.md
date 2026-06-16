---
title: StringFormatFlags
second_title: Aspose.Drawing voor Java API-referentie
description: Specificeert de weergave‑ en lay-outinformatie voor tekstreeksen.
type: docs
weight: 48
url: /nl/java/com.aspose.drawing/stringformatflags/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class StringFormatFlags extends System.Enum
```

Specificeert de weergave‑ en lay-outinformatie voor tekstreeksen.
## Velden

| Veld | Beschrijving |
| --- | --- |
| [DirectionRightToLeft](#DirectionRightToLeft) | Tekst wordt van rechts naar links weergegeven. |
| [DirectionVertical](#DirectionVertical) | Tekst is verticaal uitgelijnd. |
| [FitBlackBox](#FitBlackBox) | Delen van tekens mogen over de lay-outrechthoek van de string uitsteken. |
| [DisplayFormatControl](#DisplayFormatControl) | Controlekarakters zoals het links-naar-rechts teken worden in de uitvoer weergegeven met een representatief glyf. |
| [NoFontFallback](#NoFontFallback) | Terugvallen op alternatieve lettertypen voor tekens die niet worden ondersteund door het aangevraagde lettertype is uitgeschakeld. |
| [MeasureTrailingSpaces](#MeasureTrailingSpaces) | Bevat de afsluitende spatie aan het einde van elke regel. |
| [NoWrap](#NoWrap) | Tekstomslag tussen regels bij opmaken binnen een rechthoek is uitgeschakeld. |
| [LineLimit](#LineLimit) | Alleen volledige regels worden opgemaakt in de opmaakrechthoek. |
| [NoClip](#NoClip) | Uitschietende delen van glyfen, en niet-omgeslagen tekst die buiten de opmaakrechthoek valt, mogen worden weergegeven. |
| [ExactAlignment](#ExactAlignment) | De exacte uitlijning, correcte opvulling GDI+ |
### DirectionRightToLeft {#DirectionRightToLeft}
```
public static final int DirectionRightToLeft
```


Tekst wordt van rechts naar links weergegeven.

### DirectionVertical {#DirectionVertical}
```
public static final int DirectionVertical
```


Tekst is verticaal uitgelijnd.

### FitBlackBox {#FitBlackBox}
```
public static final int FitBlackBox
```


Delen van tekens mogen over de lay-outrechthoek van de string uitsteken. Standaard worden tekens verplaatst om elke uitstulping te voorkomen.

### DisplayFormatControl {#DisplayFormatControl}
```
public static final int DisplayFormatControl
```


Controlekarakters zoals het links-naar-rechts teken worden in de uitvoer weergegeven met een representatief glyf.

### NoFontFallback {#NoFontFallback}
```
public static final int NoFontFallback
```


Terugvallen op alternatieve lettertypen voor tekens die niet worden ondersteund door het aangevraagde lettertype is uitgeschakeld. Ontbrekende tekens worden weergegeven met het ontbrekende glyf van het lettertype, meestal een open vierkant.

### MeasureTrailingSpaces {#MeasureTrailingSpaces}
```
public static final int MeasureTrailingSpaces
```


Bevat de afsluitende spatie aan het einde van elke regel. Standaard sluit de begrenzingsrechthoek die door de MeasureString-methode wordt geretourneerd de spatie aan het einde van elke regel uit. Stel deze vlag in om die spatie bij de meting op te nemen.

### NoWrap {#NoWrap}
```
public static final int NoWrap
```


Tekstomslag tussen regels bij opmaken binnen een rechthoek is uitgeschakeld. Deze vlag wordt geïmpliceerd wanneer een punt wordt doorgegeven in plaats van een rechthoek, of wanneer de opgegeven rechthoek een nul-lengte heeft.

### LineLimit {#LineLimit}
```
public static final int LineLimit
```


Alleen volledige regels worden geplaatst in de opmaakrechthoek. Standaard wordt de lay-out voortgezet tot het einde van de tekst, of tot er geen regels meer zichtbaar zijn als gevolg van afkappen, afhankelijk van wat het eerst gebeurt. Merk op dat de standaardinstellingen toestaan dat de laatste regel gedeeltelijk wordt verborgen door een opmaakrechthoek die geen geheel veelvoud is van de regelhoogte. Om ervoor te zorgen dat alleen volledige regels worden weergegeven, specificeer deze waarde en zorg ervoor dat u een opmaakrechthoek opgeeft die minstens zo hoog is als de hoogte van één regel.

### NoClip {#NoClip}
```
public static final int NoClip
```


Uitschietende delen van glyphs en niet-omgeslagen tekst die buiten de opmaakrechthoek uitsteken, mogen worden weergegeven. Standaard worden alle tekst- en glyph‑delen die buiten de opmaakrechthoek komen, afgeknipt.

### ExactAlignment {#ExactAlignment}
```
public static final int ExactAlignment
```


De exacte uitlijning, correcte opvulling GDI+

