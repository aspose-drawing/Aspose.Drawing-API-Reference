---
title: CopyPixelOperation
second_title: Riferimento API di Aspose.Drawing per Java
description: Determina come il colore sorgente in un'operazione di copia pixel viene combinato con il colore di destinazione per ottenere un colore finale.
type: docs
weight: 18
url: /it/java/com.aspose.drawing/copypixeloperation/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class CopyPixelOperation extends System.Enum
```

Determina come il colore sorgente in un'operazione di copia pixel viene combinato con il colore di destinazione per ottenere un colore finale.
## Campi

| Campo | Descrizione |
| --- | --- |
| [NoMirrorBitmap](#NoMirrorBitmap) | La bitmap non è specchiata. |
| [Blackness](#Blackness) | L'area di destinazione è riempita utilizzando il colore associato all'indice 0 nella palette fisica. |
| [NotSourceErase](#NotSourceErase) | I colori di origine e destinazione sono combinati usando l'operatore booleano `OR`, e quindi il colore risultante viene invertito. |
| [NotSourceCopy](#NotSourceCopy) | L'area di origine invertita è copiata nella destinazione. |
| [SourceErase](#SourceErase) | I colori invertiti dell'area di destinazione sono combinati con i colori dell'area di origine usando l'operatore booleano `AND`. |
| [DestinationInvert](#DestinationInvert) | L'area di destinazione è invertita. |
| [PatInvert](#PatInvert) | I colori del pennello attualmente selezionato nel contesto dispositivo di destinazione sono combinati con i colori della destinazione usando l'operatore booleano `XOR`. |
| [SourceInvert](#SourceInvert) | I colori delle aree di origine e destinazione sono combinati usando l'operatore booleano `XOR`. |
| [SourceAnd](#SourceAnd) | I colori delle aree di origine e destinazione sono combinati usando l'operatore booleano `AND`. |
| [MergePaint](#MergePaint) | I colori dell'area di origine invertita sono uniti ai colori dell'area di destinazione usando l'operatore booleano `OR`. |
| [MergeCopy](#MergeCopy) | I colori dell'area di origine sono uniti ai colori del pennello selezionato nel contesto dispositivo di destinazione usando l'operatore booleano `AND`. |
| [SourceCopy](#SourceCopy) | L'area di origine è copiata direttamente nell'area di destinazione. |
| [SourcePaint](#SourcePaint) | I colori delle aree di origine e destinazione sono combinati usando l'operatore booleano `OR`. |
| [PatCopy](#PatCopy) | Il pennello attualmente selezionato nel contesto dispositivo di destinazione è copiato nella bitmap di destinazione. |
| [PatPaint](#PatPaint) | I colori del pennello attualmente selezionato nel contesto dispositivo di destinazione sono combinati con i colori dell'area di origine invertita usando l'operatore booleano `OR`. |
| [Whiteness](#Whiteness) | L'area di destinazione è riempita utilizzando il colore associato all'indice 1 nella palette fisica. |
| [CaptureBlt](#CaptureBlt) | Le finestre che sono sovrapposte alla tua finestra sono incluse nell'immagine risultante. |
### NoMirrorBitmap {#NoMirrorBitmap}
```
public static final int NoMirrorBitmap
```


La bitmap non è specchiata.

### Blackness {#Blackness}
```
public static final int Blackness
```


L'area di destinazione è riempita utilizzando il colore associato all'indice 0 nella palette fisica. (Questo colore è nero per la palette fisica predefinita.)

### NotSourceErase {#NotSourceErase}
```
public static final int NotSourceErase
```


I colori di origine e destinazione sono combinati usando l'operatore booleano `OR`, e quindi il colore risultante viene invertito.

### NotSourceCopy {#NotSourceCopy}
```
public static final int NotSourceCopy
```


L'area di origine invertita è copiata nella destinazione.

### SourceErase {#SourceErase}
```
public static final int SourceErase
```


I colori invertiti dell'area di destinazione sono combinati con i colori dell'area di origine usando l'operatore booleano `AND`.

### DestinationInvert {#DestinationInvert}
```
public static final int DestinationInvert
```


L'area di destinazione è invertita.

### PatInvert {#PatInvert}
```
public static final int PatInvert
```


I colori del pennello attualmente selezionato nel contesto dispositivo di destinazione sono combinati con i colori della destinazione usando l'operatore booleano `XOR`.

### SourceInvert {#SourceInvert}
```
public static final int SourceInvert
```


I colori delle aree di origine e destinazione sono combinati usando l'operatore booleano `XOR`.

### SourceAnd {#SourceAnd}
```
public static final int SourceAnd
```


I colori delle aree di origine e destinazione sono combinati usando l'operatore booleano `AND`.

### MergePaint {#MergePaint}
```
public static final int MergePaint
```


I colori dell'area di origine invertita sono uniti ai colori dell'area di destinazione usando l'operatore booleano `OR`.

### MergeCopy {#MergeCopy}
```
public static final int MergeCopy
```


I colori dell'area di origine sono uniti ai colori del pennello selezionato nel contesto dispositivo di destinazione usando l'operatore booleano `AND`.

### SourceCopy {#SourceCopy}
```
public static final int SourceCopy
```


L'area di origine è copiata direttamente nell'area di destinazione.

### SourcePaint {#SourcePaint}
```
public static final int SourcePaint
```


I colori delle aree di origine e destinazione sono combinati usando l'operatore booleano `OR`.

### PatCopy {#PatCopy}
```
public static final int PatCopy
```


Il pennello attualmente selezionato nel contesto dispositivo di destinazione è copiato nella bitmap di destinazione.

### PatPaint {#PatPaint}
```
public static final int PatPaint
```


I colori del pennello attualmente selezionato nel contesto del dispositivo di destinazione sono combinati con i colori dell'area sorgente invertita usando l'operatore booleano `OR`. Il risultato di questa operazione è combinato con i colori dell'area di destinazione usando l'operatore booleano `OR`.

### Whiteness {#Whiteness}
```
public static final int Whiteness
```


L'area di destinazione viene riempita usando il colore associato all'indice 1 nella tavolozza fisica. (Questo colore è bianco per la tavolozza fisica predefinita.)

### CaptureBlt {#CaptureBlt}
```
public static final int CaptureBlt
```


Le finestre che sono sovrapposte alla tua finestra sono incluse nell'immagine risultante. Per impostazione predefinita, l'immagine contiene solo la tua finestra. Nota che generalmente questo non può essere usato per i contesti dispositivo di stampa.

