---
title: StringFormat
second_title: Aspose.Drawing för .NET API Referens
description: Kapslar in textlayoutinformation som justering orientering och tabbstopp visningsmanipulationer såsom infogning av ellipser och nationell siffrorsättning och OpenTypefunktioner. Denna klass kan inte ärvas.
type: docs
weight: 1130
url: /sv/net/system.drawing/stringformat/
---
## StringFormat class

Kapslar in textlayoutinformation (som justering, orientering och tabbstopp) visningsmanipulationer (såsom infogning av ellipser och nationell siffrorsättning) och OpenType-funktioner. Denna klass kan inte ärvas.

```csharp
public sealed class StringFormat : IDisposable
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [StringFormat](stringformat#constructor)() | Initierar en ny instans av[`StringFormat`](../stringformat) class. |
| [StringFormat](stringformat#constructor_1)(StringFormat) | Initierar en ny instans av[`StringFormat`](../stringformat) class från den angivna befintligaStringFormat objekt. |
| [StringFormat](stringformat#constructor_2)(StringFormatFlags) | Initierar en ny instans av[`StringFormat`](../stringformat)klass med specificerad StringFormatFlags uppräkning. |
| [StringFormat](stringformat#constructor_3)(StringFormatFlags, int) | Initierar en ny instans av[`StringFormat`](../stringformat) klass med den angivna[`StringFormatFlags`](../stringformatflags) uppräkning och språk. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| static [GenericDefault](../../system.drawing/stringformat/genericdefault) { get; } | Får en generisk standardStringFormat objekt. |
| static [GenericTypographic](../../system.drawing/stringformat/generictypographic) { get; } | Får en generisk typografiStringFormat objekt. |
| [Alignment](../../system.drawing/stringformat/alignment) { get; set; } | Hämtar eller ställer in textjusteringsinformation på det vertikala planet. |
| [DigitSubstitutionLanguage](../../system.drawing/stringformat/digitsubstitutionlanguage) { get; } | Hämtar språket som används när lokala siffror ersätts med västerländska siffror. |
| [DigitSubstitutionMethod](../../system.drawing/stringformat/digitsubstitutionmethod) { get; } | Hämtar metoden som ska användas för siffersubstitution. |
| [FormatFlags](../../system.drawing/stringformat/formatflags) { get; set; } | Hämtar eller sätter enStringFormatFlags uppräkning som innehåller formateringsinformation. |
| [HotkeyPrefix](../../system.drawing/stringformat/hotkeyprefix) { get; set; } | Hämtar eller ställer inHotkeyPrefix objekt för dettaStringFormat objekt. |
| [LineAlignment](../../system.drawing/stringformat/linealignment) { get; set; } | Hämtar eller ställer in linjeinriktningen på horisontalplanet. |
| [Trimming](../../system.drawing/stringformat/trimming) { get; set; } | Hämtar eller ställer inStringTrimming uppräkning för dettaStringFormat objekt. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [Clone](../../system.drawing/stringformat/clone)() | Skapar en exakt kopia av detta[`StringFormat`](../stringformat) objekt. |
| [Dispose](../../system.drawing/stringformat/dispose)() | Frigör alla resurser som används av dettaStringFormat objekt. |
| [GetTabStops](../../system.drawing/stringformat/gettabstops)(out float) | Får tabbstopp för dettaStringFormat objekt. |
| [SetDigitSubstitution](../../system.drawing/stringformat/setdigitsubstitution)(int, StringDigitSubstitute) | Anger språket och metoden som ska användas när lokala siffror ersätts med västerländska siffror. |
| [SetMeasurableCharacterRanges](../../system.drawing/stringformat/setmeasurablecharacterranges)(CharacterRange[]) | Anger en array avCharacterRange strukturer som representerar intervallen för tecken som mäts av ett anrop tillMeasureCharacterRanges metod. |
| [SetTabStops](../../system.drawing/stringformat/settabstops)(float, float[]) | Ställer in tabbstopp för dettaStringFormat objekt. |

### Se även

* namnutrymme [System.Drawing](../../system.drawing)
* hopsättning [Aspose.Drawing](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Drawing.dll -->