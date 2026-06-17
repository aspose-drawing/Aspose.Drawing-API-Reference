---
title: TextRenderingHint
second_title: Aspose.Drawing för Java API‑referens
description: Anger kvaliteten på textåtergivning.
type: docs
weight: 14
url: /sv/java/com.aspose.drawing.text/textrenderinghint/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class TextRenderingHint extends System.Enum
```

Anger kvaliteten på textåtergivning.
## Fält

| Fält | Beskrivning |
| --- | --- |
| [SystemDefault](#SystemDefault) | Varje tecken ritas med sin glyfbild, med systemets standardrenderingstips. |
| [SingleBitPerPixelGridFit](#SingleBitPerPixelGridFit) | Varje tecken ritas med sin glyfbild. |
| [SingleBitPerPixel](#SingleBitPerPixel) | Varje tecken ritas med sin glyfbild. |
| [AntiAliasGridFit](#AntiAliasGridFit) | Varje tecken ritas med sin kantutjämnade glyfbild med hintning. |
| [AntiAlias](#AntiAlias) | Varje tecken ritas med sin kantutjämnade glyfbild utan hintning. |
| [ClearTypeGridFit](#ClearTypeGridFit) | Varje tecken ritas med sin glyf ClearType-bild med hintning. |
### SystemDefault {#SystemDefault}
```
public static final int SystemDefault
```


Varje tecken ritas med sin glyfbild, med systemets standardrenderingstips. Texten kommer att ritas med de teckensnittsutjämningsinställningar som användaren har valt för systemet.

### SingleBitPerPixelGridFit {#SingleBitPerPixelGridFit}
```
public static final int SingleBitPerPixelGridFit
```


Varje tecken ritas med sin glyfbild. Hintning används för att förbättra teckenutseendet på stjälkar och kurvor.

### SingleBitPerPixel {#SingleBitPerPixel}
```
public static final int SingleBitPerPixel
```


Varje tecken ritas med sin glyf-bitmap. Hintning används inte.

### AntiAliasGridFit {#AntiAliasGridFit}
```
public static final int AntiAliasGridFit
```


Varje tecken ritas med sin antialiasade glyf-bitmap med hintning. Mycket bättre kvalitet på grund av antialiasing, men med högre prestandakostnad.

### AntiAlias {#AntiAlias}
```
public static final int AntiAlias
```


Varje tecken ritas med sin antialiasade glyf-bitmap utan hintning. Bättre kvalitet på grund av antialiasing. Skillnader i stambredd kan märkas eftersom hintning är avstängd.

### ClearTypeGridFit {#ClearTypeGridFit}
```
public static final int ClearTypeGridFit
```


Varje tecken ritas med sin glyf ClearType-bitmap med hintning. Den högsta kvalitetsinställningen. Används för att utnyttja ClearType-typsnittsfunktioner.

