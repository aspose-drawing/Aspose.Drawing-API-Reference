---
title: PixelFormat
second_title: Aspose.Drawing voor Java API-referentie
description: Specificeert het formaat van de kleurgegevens voor elke pixel in de afbeelding.
type: docs
weight: 34
url: /nl/java/com.aspose.drawing.imaging/pixelformat/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PixelFormat extends System.Enum
```

Specificeert het formaat van de kleurgegevens voor elke pixel in de afbeelding.
## Velden

| Veld | Beschrijving |
| --- | --- |
| [Indexed](#Indexed) | De pixelgegevens bevatten kleur-geïndexeerde waarden, wat betekent dat de waarden een index zijn naar kleuren in de systeemtabel voor kleuren, in plaats van individuele kleurwaarden. |
| [Gdi](#Gdi) | De pixelgegevens bevatten GDI-kleuren. |
| [Alpha](#Alpha) | De pixelgegevens bevatten alfawaarden die niet voorvermenigvuldigd zijn. |
| [PAlpha](#PAlpha) | Het pixelformaat bevat voorvermenigvuldigde alfawaarden. |
| [Extended](#Extended) | Gerreserveerde waarde. |
| [Canonical](#Canonical) | Het standaard pixelformaat van 32 bits per pixel. |
| [Undefined](#Undefined) | Het pixelformaat is niet gedefinieerd. |
| [DontCare](#DontCare) | Er is geen pixelformaat opgegeven. |
| [Format1bppIndexed](#Format1bppIndexed) | Specificeert dat het pixelformaat 1 bit per pixel is en dat het geïndexeerde kleuren gebruikt. |
| [Format4bppIndexed](#Format4bppIndexed) | Specificeert dat het formaat 4 bits per pixel is, geïndexeerd. |
| [Format8bppIndexed](#Format8bppIndexed) | Specificeert dat het formaat 8 bits per pixel is, geïndexeerd. |
| [Format16bppGrayScale](#Format16bppGrayScale) | Het pixelformaat is 16 bits per pixel. |
| [Format16bppRgb555](#Format16bppRgb555) | Specificeert dat het formaat 16 bits per pixel is; 5 bits elk worden gebruikt voor de rode, groene en blauwe componenten. |
| [Format16bppRgb565](#Format16bppRgb565) | Specificeert dat het formaat 16 bits per pixel is; 5 bits worden gebruikt voor de rode component, 6 bits voor de groene component en 5 bits voor de blauwe component. |
| [Format16bppArgb1555](#Format16bppArgb1555) | Het pixelformaat is 16 bits per pixel. |
| [Format24bppRgb](#Format24bppRgb) | Geeft aan dat het formaat 24 bits per pixel is; 8 bits per component worden gebruikt voor rood, groen en blauw. |
| [Format32bppRgb](#Format32bppRgb) | Geeft aan dat het formaat 32 bits per pixel is; 8 bits per component worden gebruikt voor rood, groen en blauw. |
| [Format32bppArgb](#Format32bppArgb) | Geeft aan dat het formaat 32 bits per pixel is; 8 bits per component worden gebruikt voor alfa, rood, groen en blauw. |
| [Format32bppPArgb](#Format32bppPArgb) | Geeft aan dat het formaat 32 bits per pixel is; 8 bits per component worden gebruikt voor alfa, rood, groen en blauw. |
| [Format48bppRgb](#Format48bppRgb) | Geeft aan dat het formaat 48 bits per pixel is; 16 bits per component worden gebruikt voor rood, groen en blauw. |
| [Format64bppArgb](#Format64bppArgb) | Geeft aan dat het formaat 64 bits per pixel is; 16 bits per component worden gebruikt voor alfa, rood, groen en blauw. |
| [Format64bppPArgb](#Format64bppPArgb) | Geeft aan dat het formaat 64 bits per pixel is; 16 bits per component worden gebruikt voor alfa, rood, groen en blauw. |
| [Max](#Max) | De maximale waarde voor deze enumeratie. |
### Indexed {#Indexed}
```
public static final int Indexed
```


De pixelgegevens bevatten kleur-geïndexeerde waarden, wat betekent dat de waarden een index zijn naar kleuren in de systeemtabel voor kleuren, in plaats van individuele kleurwaarden.

### Gdi {#Gdi}
```
public static final int Gdi
```


De pixelgegevens bevatten GDI-kleuren.

### Alpha {#Alpha}
```
public static final int Alpha
```


De pixelgegevens bevatten alfawaarden die niet voorvermenigvuldigd zijn.

### PAlpha {#PAlpha}
```
public static final int PAlpha
```


Het pixelformaat bevat voorvermenigvuldigde alfawaarden.

### Extended {#Extended}
```
public static final int Extended
```


Gerreserveerde waarde.

### Canonical {#Canonical}
```
public static final int Canonical
```


Het standaard pixelformaat van 32 bits per pixel. Het formaat specificeert een kleurdiepte van 24 bits en een alfa-kanaal van 8 bits.

### Undefined {#Undefined}
```
public static final int Undefined
```


Het pixelformaat is niet gedefinieerd.

### DontCare {#DontCare}
```
public static final int DontCare
```


Er is geen pixelformaat opgegeven.

### Format1bppIndexed {#Format1bppIndexed}
```
public static final int Format1bppIndexed
```


Geeft aan dat het pixelformaat 1 bit per pixel is en dat het geïndexeerde kleuren gebruikt. De kleurentabel bevat daarom twee kleuren.

### Format4bppIndexed {#Format4bppIndexed}
```
public static final int Format4bppIndexed
```


Specificeert dat het formaat 4 bits per pixel is, geïndexeerd.

### Format8bppIndexed {#Format8bppIndexed}
```
public static final int Format8bppIndexed
```


Geeft aan dat het formaat 8 bits per pixel is, geïndexeerd. De kleurentabel bevat daarom 256 kleuren.

### Format16bppGrayScale {#Format16bppGrayScale}
```
public static final int Format16bppGrayScale
```


Het pixelformaat is 16 bits per pixel. De kleurinformatie specificeert 65.536 grijstinten.

### Format16bppRgb555 {#Format16bppRgb555}
```
public static final int Format16bppRgb555
```


Geeft aan dat het formaat 16 bits per pixel is; 5 bits per component worden gebruikt voor rood, groen en blauw. Het resterende bit wordt niet gebruikt.

### Format16bppRgb565 {#Format16bppRgb565}
```
public static final int Format16bppRgb565
```


Specificeert dat het formaat 16 bits per pixel is; 5 bits worden gebruikt voor de rode component, 6 bits voor de groene component en 5 bits voor de blauwe component.

### Format16bppArgb1555 {#Format16bppArgb1555}
```
public static final int Format16bppArgb1555
```


Het pixelformaat is 16 bits per pixel. De kleurinformatie specificeert 32.768 kleurtinten, waarvan 5 bits rood, 5 bits groen, 5 bits blauw en 1 bit alfa.

### Format24bppRgb {#Format24bppRgb}
```
public static final int Format24bppRgb
```


Geeft aan dat het formaat 24 bits per pixel is; 8 bits per component worden gebruikt voor rood, groen en blauw.

### Format32bppRgb {#Format32bppRgb}
```
public static final int Format32bppRgb
```


Geeft aan dat het formaat 32 bits per pixel is; 8 bits per component worden gebruikt voor rood, groen en blauw. De resterende 8 bits worden niet gebruikt.

### Format32bppArgb {#Format32bppArgb}
```
public static final int Format32bppArgb
```


Geeft aan dat het formaat 32 bits per pixel is; 8 bits per component worden gebruikt voor alfa, rood, groen en blauw.

### Format32bppPArgb {#Format32bppPArgb}
```
public static final int Format32bppPArgb
```


Geeft aan dat het formaat 32 bits per pixel is; 8 bits per component worden gebruikt voor alfa, rood, groen en blauw. De rood-, groen- en blauwcomponenten zijn voorvermenigvuldigd volgens de alfacomponent.

### Format48bppRgb {#Format48bppRgb}
```
public static final int Format48bppRgb
```


Geeft aan dat het formaat 48 bits per pixel is; 16 bits per component worden gebruikt voor rood, groen en blauw.

### Format64bppArgb {#Format64bppArgb}
```
public static final int Format64bppArgb
```


Geeft aan dat het formaat 64 bits per pixel is; 16 bits per component worden gebruikt voor alfa, rood, groen en blauw.

### Format64bppPArgb {#Format64bppPArgb}
```
public static final int Format64bppPArgb
```


Geeft aan dat het formaat 64 bits per pixel is; 16 bits per component worden gebruikt voor alfa, rood, groen en blauw. De rood-, groen- en blauwcomponenten zijn voorvermenigvuldigd volgens de alfacomponent.

### Max {#Max}
```
public static final int Max
```


De maximale waarde voor deze enumeratie.

