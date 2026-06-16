---
title: CopyPixelOperation
second_title: Aspose.Drawing voor Java API-referentie
description: Bepaalt hoe de bronkleur in een kopieer-pixeloperatie wordt gecombineerd met de doelkleur om een eindkleur te verkrijgen.
type: docs
weight: 18
url: /nl/java/com.aspose.drawing/copypixeloperation/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class CopyPixelOperation extends System.Enum
```

Bepaalt hoe de bronkleur in een kopieer-pixeloperatie wordt gecombineerd met de doelkleur om een eindkleur te verkrijgen.
## Velden

| Veld | Beschrijving |
| --- | --- |
| [NoMirrorBitmap](#NoMirrorBitmap) | De bitmap is niet gespiegeld. |
| [Blackness](#Blackness) | Het bestemmingsgebied wordt gevuld met de kleur die geassocieerd is met index 0 in het fysieke palet. |
| [NotSourceErase](#NotSourceErase) | De bron- en bestemmingskleuren worden gecombineerd met de Booleaanse `OR`-operator, waarna de resulterende kleur wordt geïnverteerd. |
| [NotSourceCopy](#NotSourceCopy) | Het geïnverteerde brongebied wordt gekopieerd naar de bestemming. |
| [SourceErase](#SourceErase) | De geïnverteerde kleuren van het bestemmingsgebied worden gecombineerd met de kleuren van het brongebied met de Booleaanse `AND`-operator. |
| [DestinationInvert](#DestinationInvert) | Het bestemmingsgebied wordt geïnverteerd. |
| [PatInvert](#PatInvert) | De kleuren van de momenteel geselecteerde penseel in de bestemmingsapparaatcontext worden gecombineerd met de kleuren van de bestemming met de Booleaanse `XOR`-operator. |
| [SourceInvert](#SourceInvert) | De kleuren van de bron- en bestemmingsgebieden worden gecombineerd met de Booleaanse `XOR`-operator. |
| [SourceAnd](#SourceAnd) | De kleuren van de bron- en bestemmingsgebieden worden gecombineerd met de Booleaanse `AND`-operator. |
| [MergePaint](#MergePaint) | De kleuren van het geïnverteerde brongebied worden samengevoegd met de kleuren van het bestemmingsgebied door gebruik te maken van de Booleaanse `OR`-operator. |
| [MergeCopy](#MergeCopy) | De kleuren van het brongebied worden samengevoegd met de kleuren van de geselecteerde penseel van de bestemmingsapparaatcontext met de Booleaanse `AND`-operator. |
| [SourceCopy](#SourceCopy) | Het brongebied wordt rechtstreeks gekopieerd naar het bestemmingsgebied. |
| [SourcePaint](#SourcePaint) | De kleuren van de bron- en bestemmingsgebieden worden gecombineerd met de Booleaanse `OR`-operator. |
| [PatCopy](#PatCopy) | De momenteel geselecteerde penseel in de bestemmingsapparaatcontext wordt gekopieerd naar de bestemmingsbitmap. |
| [PatPaint](#PatPaint) | De kleuren van de momenteel geselecteerde penseel in de bestemmingsapparaatcontext worden gecombineerd met de kleuren van het geïnverteerde brongebied met de Booleaanse `OR`-operator. |
| [Whiteness](#Whiteness) | Het bestemmingsgebied wordt gevuld met de kleur die geassocieerd is met index 1 in het fysieke palet. |
| [CaptureBlt](#CaptureBlt) | Vensters die bovenop uw venster zijn gestapeld, worden opgenomen in de resulterende afbeelding. |
### NoMirrorBitmap {#NoMirrorBitmap}
```
public static final int NoMirrorBitmap
```


De bitmap is niet gespiegeld.

### Blackness {#Blackness}
```
public static final int Blackness
```


Het bestemmingsgebied wordt gevuld met de kleur die geassocieerd is met index 0 in het fysieke palet. (Deze kleur is zwart voor het standaard fysieke palet.)

### NotSourceErase {#NotSourceErase}
```
public static final int NotSourceErase
```


De bron- en bestemmingskleuren worden gecombineerd met de Booleaanse `OR`-operator, waarna de resulterende kleur wordt geïnverteerd.

### NotSourceCopy {#NotSourceCopy}
```
public static final int NotSourceCopy
```


Het geïnverteerde brongebied wordt gekopieerd naar de bestemming.

### SourceErase {#SourceErase}
```
public static final int SourceErase
```


De geïnverteerde kleuren van het bestemmingsgebied worden gecombineerd met de kleuren van het brongebied met de Booleaanse `AND`-operator.

### DestinationInvert {#DestinationInvert}
```
public static final int DestinationInvert
```


Het bestemmingsgebied wordt geïnverteerd.

### PatInvert {#PatInvert}
```
public static final int PatInvert
```


De kleuren van de momenteel geselecteerde penseel in de bestemmingsapparaatcontext worden gecombineerd met de kleuren van de bestemming met de Booleaanse `XOR`-operator.

### SourceInvert {#SourceInvert}
```
public static final int SourceInvert
```


De kleuren van de bron- en bestemmingsgebieden worden gecombineerd met de Booleaanse `XOR`-operator.

### SourceAnd {#SourceAnd}
```
public static final int SourceAnd
```


De kleuren van de bron- en bestemmingsgebieden worden gecombineerd met de Booleaanse `AND`-operator.

### MergePaint {#MergePaint}
```
public static final int MergePaint
```


De kleuren van het geïnverteerde brongebied worden samengevoegd met de kleuren van het bestemmingsgebied door gebruik te maken van de Booleaanse `OR`-operator.

### MergeCopy {#MergeCopy}
```
public static final int MergeCopy
```


De kleuren van het brongebied worden samengevoegd met de kleuren van de geselecteerde penseel van de bestemmingsapparaatcontext met de Booleaanse `AND`-operator.

### SourceCopy {#SourceCopy}
```
public static final int SourceCopy
```


Het brongebied wordt rechtstreeks gekopieerd naar het bestemmingsgebied.

### SourcePaint {#SourcePaint}
```
public static final int SourcePaint
```


De kleuren van de bron- en bestemmingsgebieden worden gecombineerd met de Booleaanse `OR`-operator.

### PatCopy {#PatCopy}
```
public static final int PatCopy
```


De momenteel geselecteerde penseel in de bestemmingsapparaatcontext wordt gekopieerd naar de bestemmingsbitmap.

### PatPaint {#PatPaint}
```
public static final int PatPaint
```


De kleuren van het penseel dat momenteel is geselecteerd in de bestemmings‑apparaatcontext worden gecombineerd met de kleuren van het omgekeerde brongebied met behulp van de Booleaanse `OR`‑operator. Het resultaat van deze bewerking wordt gecombineerd met de kleuren van het bestemmingsgebied met behulp van de Booleaanse `OR`‑operator.

### Whiteness {#Whiteness}
```
public static final int Whiteness
```


Het bestemmingsgebied wordt gevuld met de kleur die is gekoppeld aan index 1 in het fysieke palet. (Deze kleur is wit voor het standaard fysieke palet.)

### CaptureBlt {#CaptureBlt}
```
public static final int CaptureBlt
```


Vensters die bovenop uw venster zijn gestapeld, worden opgenomen in de resulterende afbeelding. Standaard bevat de afbeelding alleen uw venster. Merk op dat dit over het algemeen niet kan worden gebruikt voor afdruk‑apparaatcontexten.

