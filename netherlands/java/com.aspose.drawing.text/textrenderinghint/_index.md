---
title: TextRenderingHint
second_title: Aspose.Drawing voor Java API-referentie
description: Specificeert de kwaliteit van tekstweergave.
type: docs
weight: 14
url: /nl/java/com.aspose.drawing.text/textrenderinghint/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class TextRenderingHint extends System.Enum
```

Specificeert de kwaliteit van tekstweergave.
## Velden

| Veld | Beschrijving |
| --- | --- |
| [SystemDefault](#SystemDefault) | Elk teken wordt getekend met behulp van zijn glyph bitmap, met de standaard renderhint van het systeem. |
| [SingleBitPerPixelGridFit](#SingleBitPerPixelGridFit) | Elk teken wordt getekend met behulp van zijn glyph bitmap. |
| [SingleBitPerPixel](#SingleBitPerPixel) | Elk teken wordt getekend met behulp van zijn glyph bitmap. |
| [AntiAliasGridFit](#AntiAliasGridFit) | Elk teken wordt getekend met behulp van zijn antialiased glyph bitmap met hinting. |
| [AntiAlias](#AntiAlias) | Elk teken wordt getekend met behulp van zijn antialiased glyph bitmap zonder hinting. |
| [ClearTypeGridFit](#ClearTypeGridFit) | Elk teken wordt getekend met behulp van zijn glyph ClearType bitmap met hinting. |
### SystemDefault {#SystemDefault}
```
public static final int SystemDefault
```


Elk teken wordt getekend met behulp van zijn glyph bitmap, met de standaard renderhint van het systeem. De tekst wordt getekend met de font-smoothing instellingen die de gebruiker voor het systeem heeft geselecteerd.

### SingleBitPerPixelGridFit {#SingleBitPerPixelGridFit}
```
public static final int SingleBitPerPixelGridFit
```


Elk teken wordt getekend met behulp van zijn glyph bitmap. Hinting wordt gebruikt om de weergave van tekens op stammen en krommingen te verbeteren.

### SingleBitPerPixel {#SingleBitPerPixel}
```
public static final int SingleBitPerPixel
```


Elk teken wordt getekend met behulp van zijn glyph-bitmap. Hinting wordt niet gebruikt.

### AntiAliasGridFit {#AntiAliasGridFit}
```
public static final int AntiAliasGridFit
```


Elk teken wordt getekend met behulp van zijn anti‑aliased glyph-bitmap met hinting. Veel betere kwaliteit dankzij antialiasing, maar tegen een hogere prestatiekost.

### AntiAlias {#AntiAlias}
```
public static final int AntiAlias
```


Elk teken wordt getekend met behulp van zijn anti‑aliased glyph-bitmap zonder hinting. Betere kwaliteit dankzij antialiasing. Verschillen in stempeldikte kunnen merkbaar zijn omdat hinting is uitgeschakeld.

### ClearTypeGridFit {#ClearTypeGridFit}
```
public static final int ClearTypeGridFit
```


Elk teken wordt getekend met behulp van zijn glyph ClearType-bitmap met hinting. De hoogste kwaliteitinstelling. Gebruikt om voordeel te halen uit ClearType-lettertypefuncties.

