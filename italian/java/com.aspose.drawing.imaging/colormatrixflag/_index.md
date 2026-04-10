---
title: ColorMatrixFlag
second_title: Riferimento API di Aspose.Drawing per Java
description: Specifica i tipi di immagini e colori che saranno influenzati dalle impostazioni di regolazione del colore e della scala di grigi di un .
type: docs
weight: 15
url: /it/java/com.aspose.drawing.imaging/colormatrixflag/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ColorMatrixFlag extends System.Enum
```

Specifica i tipi di immagini e colori che saranno influenzati dalle impostazioni di regolazione del colore e della scala di grigi di un [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes).
## Campi

| Campo | Descrizione |
| --- | --- |
| [Default](#Default) | Tutti i valori di colore, incluse le sfumature di grigio, sono regolati dalla stessa matrice di regolazione del colore. |
| [SkipGrays](#SkipGrays) | Tutti i colori sono regolati, ma le sfumature di grigio non sono regolate. |
| [AltGrays](#AltGrays) | Solo le sfumature di grigio sono regolate. |
### Default {#Default}
```
public static final int Default
```


Tutti i valori di colore, incluse le sfumature di grigio, sono regolati dalla stessa matrice di regolazione del colore.

### SkipGrays {#SkipGrays}
```
public static final int SkipGrays
```


Tutti i colori sono regolati, ma le sfumature di grigio non sono regolate. Una sfumatura di grigio è qualsiasi colore che ha lo stesso valore per i componenti rosso, verde e blu.

### AltGrays {#AltGrays}
```
public static final int AltGrays
```


Solo le sfumature di grigio sono regolate.

