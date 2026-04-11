---
title: CopyPixelOperation
second_title: Aspose.Drawing för Java API‑referens
description: Bestämmer hur källfärgen i en kopiera-pixel-operation kombineras med destinationsfärgen för att resultera i en slutgiltig färg.
type: docs
weight: 18
url: /sv/java/com.aspose.drawing/copypixeloperation/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class CopyPixelOperation extends System.Enum
```

Bestämmer hur källfärgen i en kopiera-pixel-operation kombineras med destinationsfärgen för att resultera i en slutgiltig färg.
## Fält

| Fält | Beskrivning |
| --- | --- |
| [NoMirrorBitmap](#NoMirrorBitmap) | Bitmapen är inte speglad. |
| [Blackness](#Blackness) | Destinationsområdet fylls genom att använda färgen som är associerad med index 0 i den fysiska paletten. |
| [NotSourceErase](#NotSourceErase) | Käll- och destinationsfärgerna kombineras med den booleska `OR`‑operatorn, och den resulterande färgen inverteras sedan. |
| [NotSourceCopy](#NotSourceCopy) | Det inverterade källområdet kopieras till destinationen. |
| [SourceErase](#SourceErase) | De inverterade färgerna i destinationsområdet kombineras med färgerna i källområdet med den booleska `AND`‑operatorn. |
| [DestinationInvert](#DestinationInvert) | Destinationsområdet inverteras. |
| [PatInvert](#PatInvert) | Färgerna på den för närvarande valda penseln i destinationsenhetens kontext kombineras med färgerna i destinationen med den booleska `XOR`‑operatorn. |
| [SourceInvert](#SourceInvert) | Färgerna i käll- och destinationsområdena kombineras med den booleska `XOR`‑operatorn. |
| [SourceAnd](#SourceAnd) | Färgerna i käll- och destinationsområdena kombineras med den booleska `AND`‑operatorn. |
| [MergePaint](#MergePaint) | Färgerna i det inverterade källområdet slås samman med färgerna i destinationsområdet genom att använda den booleska `OR`‑operatorn. |
| [MergeCopy](#MergeCopy) | Färgerna i källområdet slås samman med färgerna i den valda penseln i destinationsenhetens kontext med den booleska `AND`‑operatorn. |
| [SourceCopy](#SourceCopy) | Källområdet kopieras direkt till destinationsområdet. |
| [SourcePaint](#SourcePaint) | Färgerna i käll- och destinationsområdena kombineras med den booleska `OR`‑operatorn. |
| [PatCopy](#PatCopy) | Den för närvarande valda penseln i destinationsenhetens kontext kopieras till destinations‑bitmapen. |
| [PatPaint](#PatPaint) | Färgerna på den för närvarande valda penseln i destinationsenhetens kontext kombineras med färgerna i det inverterade källområdet med den booleska `OR`‑operatorn. |
| [Whiteness](#Whiteness) | Destinationsområdet fylls genom att använda färgen som är associerad med index 1 i den fysiska paletten. |
| [CaptureBlt](#CaptureBlt) | Fönster som är lagerlagda ovanpå ditt fönster inkluderas i den resulterande bilden. |
### NoMirrorBitmap {#NoMirrorBitmap}
```
public static final int NoMirrorBitmap
```


Bitmapen är inte speglad.

### Blackness {#Blackness}
```
public static final int Blackness
```


Destinationsområdet fylls genom att använda färgen som är associerad med index 0 i den fysiska paletten. (Denna färg är svart för den standardfysiska paletten.)

### NotSourceErase {#NotSourceErase}
```
public static final int NotSourceErase
```


Käll- och destinationsfärgerna kombineras med den booleska `OR`‑operatorn, och den resulterande färgen inverteras sedan.

### NotSourceCopy {#NotSourceCopy}
```
public static final int NotSourceCopy
```


Det inverterade källområdet kopieras till destinationen.

### SourceErase {#SourceErase}
```
public static final int SourceErase
```


De inverterade färgerna i destinationsområdet kombineras med färgerna i källområdet med den booleska `AND`‑operatorn.

### DestinationInvert {#DestinationInvert}
```
public static final int DestinationInvert
```


Destinationsområdet inverteras.

### PatInvert {#PatInvert}
```
public static final int PatInvert
```


Färgerna på den för närvarande valda penseln i destinationsenhetens kontext kombineras med färgerna i destinationen med den booleska `XOR`‑operatorn.

### SourceInvert {#SourceInvert}
```
public static final int SourceInvert
```


Färgerna i käll- och destinationsområdena kombineras med den booleska `XOR`‑operatorn.

### SourceAnd {#SourceAnd}
```
public static final int SourceAnd
```


Färgerna i käll- och destinationsområdena kombineras med den booleska `AND`‑operatorn.

### MergePaint {#MergePaint}
```
public static final int MergePaint
```


Färgerna i det inverterade källområdet slås samman med färgerna i destinationsområdet genom att använda den booleska `OR`‑operatorn.

### MergeCopy {#MergeCopy}
```
public static final int MergeCopy
```


Färgerna i källområdet slås samman med färgerna i den valda penseln i destinationsenhetens kontext med den booleska `AND`‑operatorn.

### SourceCopy {#SourceCopy}
```
public static final int SourceCopy
```


Källområdet kopieras direkt till destinationsområdet.

### SourcePaint {#SourcePaint}
```
public static final int SourcePaint
```


Färgerna i käll- och destinationsområdena kombineras med den booleska `OR`‑operatorn.

### PatCopy {#PatCopy}
```
public static final int PatCopy
```


Den för närvarande valda penseln i destinationsenhetens kontext kopieras till destinations‑bitmapen.

### PatPaint {#PatPaint}
```
public static final int PatPaint
```


Färgerna på den pensel som för närvarande är vald i destinationsenhetens kontext kombineras med färgerna i det inverterade källområdet med den booleska `OR`-operatorn. Resultatet av denna operation kombineras med färgerna i destinationsområdet med den booleska `OR`-operatorn.

### Whiteness {#Whiteness}
```
public static final int Whiteness
```


Destinationsområdet fylls genom att använda färgen som är associerad med index 1 i den fysiska paletten. (Denna färg är vit för standardpaletten.)

### CaptureBlt {#CaptureBlt}
```
public static final int CaptureBlt
```


Fönster som är lagerlagda ovanpå ditt fönster inkluderas i den resulterande bilden. Som standard innehåller bilden endast ditt fönster. Observera att detta generellt inte kan användas för utskriftsenhetens kontexter.

