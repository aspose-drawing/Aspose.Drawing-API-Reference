---
title: PixelFormat
second_title: Riferimento API di Aspose.Drawing per Java
description: Specifica il formato dei dati di colore per ogni pixel dell'immagine.
type: docs
weight: 34
url: /it/java/com.aspose.drawing.imaging/pixelformat/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PixelFormat extends System.Enum
```

Specifica il formato dei dati di colore per ogni pixel dell'immagine.
## Campi

| Campo | Descrizione |
| --- | --- |
| [Indexed](#Indexed) | I dati dei pixel contengono valori indicizzati per colore, il che significa che i valori sono un indice ai colori nella tabella dei colori di sistema, anziché valori di colore individuali. |
| [Gdi](#Gdi) | I dati dei pixel contengono colori GDI. |
| [Alpha](#Alpha) | I dati dei pixel contengono valori alfa che non sono premoltiplicati. |
| [PAlpha](#PAlpha) | Il formato dei pixel contiene valori alfa premoltiplicati. |
| [Extended](#Extended) | Valore riservato. |
| [Canonical](#Canonical) | Il formato predefinito dei pixel è di 32 bit per pixel. |
| [Undefined](#Undefined) | Il formato dei pixel è indefinito. |
| [DontCare](#DontCare) | Nessun formato dei pixel è specificato. |
| [Format1bppIndexed](#Format1bppIndexed) | Specifica che il formato dei pixel è di 1 bit per pixel e che utilizza colori indicizzati. |
| [Format4bppIndexed](#Format4bppIndexed) | Specifica che il formato è di 4 bit per pixel, indicizzato. |
| [Format8bppIndexed](#Format8bppIndexed) | Specifica che il formato è di 8 bit per pixel, indicizzato. |
| [Format16bppGrayScale](#Format16bppGrayScale) | Il formato dei pixel è di 16 bit per pixel. |
| [Format16bppRgb555](#Format16bppRgb555) | Specifica che il formato è di 16 bit per pixel; 5 bit ciascuno sono usati per i componenti rosso, verde e blu. |
| [Format16bppRgb565](#Format16bppRgb565) | Specifica che il formato è di 16 bit per pixel; 5 bit sono usati per il componente rosso, 6 bit sono usati per il componente verde e 5 bit sono usati per il componente blu. |
| [Format16bppArgb1555](#Format16bppArgb1555) | Il formato dei pixel è di 16 bit per pixel. |
| [Format24bppRgb](#Format24bppRgb) | Specifica che il formato è di 24 bit per pixel; 8 bit ciascuno sono usati per i componenti rosso, verde e blu. |
| [Format32bppRgb](#Format32bppRgb) | Specifica che il formato è di 32 bit per pixel; 8 bit ciascuno sono usati per i componenti rosso, verde e blu. |
| [Format32bppArgb](#Format32bppArgb) | Specifica che il formato è di 32 bit per pixel; 8 bit ciascuno sono usati per i componenti alpha, rosso, verde e blu. |
| [Format32bppPArgb](#Format32bppPArgb) | Specifica che il formato è di 32 bit per pixel; 8 bit ciascuno sono usati per i componenti alpha, rosso, verde e blu. |
| [Format48bppRgb](#Format48bppRgb) | Specifica che il formato è di 48 bit per pixel; 16 bit ciascuno sono usati per i componenti rosso, verde e blu. |
| [Format64bppArgb](#Format64bppArgb) | Specifica che il formato è di 64 bit per pixel; 16 bit ciascuno sono usati per i componenti alpha, rosso, verde e blu. |
| [Format64bppPArgb](#Format64bppPArgb) | Specifica che il formato è di 64 bit per pixel; 16 bit ciascuno sono usati per i componenti alpha, rosso, verde e blu. |
| [Max](#Max) | Il valore massimo per questa enumerazione. |
### Indexed {#Indexed}
```
public static final int Indexed
```


I dati dei pixel contengono valori indicizzati per colore, il che significa che i valori sono un indice ai colori nella tabella dei colori di sistema, anziché valori di colore individuali.

### Gdi {#Gdi}
```
public static final int Gdi
```


I dati dei pixel contengono colori GDI.

### Alpha {#Alpha}
```
public static final int Alpha
```


I dati dei pixel contengono valori alfa che non sono premoltiplicati.

### PAlpha {#PAlpha}
```
public static final int PAlpha
```


Il formato dei pixel contiene valori alfa premoltiplicati.

### Extended {#Extended}
```
public static final int Extended
```


Valore riservato.

### Canonical {#Canonical}
```
public static final int Canonical
```


Il formato pixel predefinito è di 32 bit per pixel. Il formato specifica una profondità di colore a 24 bit e un canale alpha a 8 bit.

### Undefined {#Undefined}
```
public static final int Undefined
```


Il formato dei pixel è indefinito.

### DontCare {#DontCare}
```
public static final int DontCare
```


Nessun formato dei pixel è specificato.

### Format1bppIndexed {#Format1bppIndexed}
```
public static final int Format1bppIndexed
```


Specifica che il formato pixel è di 1 bit per pixel e che utilizza colori indicizzati. La tavola dei colori contiene quindi due colori.

### Format4bppIndexed {#Format4bppIndexed}
```
public static final int Format4bppIndexed
```


Specifica che il formato è di 4 bit per pixel, indicizzato.

### Format8bppIndexed {#Format8bppIndexed}
```
public static final int Format8bppIndexed
```


Specifica che il formato è di 8 bit per pixel, indicizzato. La tavola dei colori contiene quindi 256 colori.

### Format16bppGrayScale {#Format16bppGrayScale}
```
public static final int Format16bppGrayScale
```


Il formato pixel è di 16 bit per pixel. L'informazione sul colore specifica 65.536 tonalità di grigio.

### Format16bppRgb555 {#Format16bppRgb555}
```
public static final int Format16bppRgb555
```


Specifica che il formato è di 16 bit per pixel; 5 bit ciascuno sono usati per i componenti rosso, verde e blu. Il bit rimanente non è utilizzato.

### Format16bppRgb565 {#Format16bppRgb565}
```
public static final int Format16bppRgb565
```


Specifica che il formato è di 16 bit per pixel; 5 bit sono usati per il componente rosso, 6 bit sono usati per il componente verde e 5 bit sono usati per il componente blu.

### Format16bppArgb1555 {#Format16bppArgb1555}
```
public static final int Format16bppArgb1555
```


Il formato pixel è di 16 bit per pixel. L'informazione sul colore specifica 32.768 tonalità di colore, di cui 5 bit sono rosso, 5 bit sono verde, 5 bit sono blu e 1 bit è alpha.

### Format24bppRgb {#Format24bppRgb}
```
public static final int Format24bppRgb
```


Specifica che il formato è di 24 bit per pixel; 8 bit ciascuno sono usati per i componenti rosso, verde e blu.

### Format32bppRgb {#Format32bppRgb}
```
public static final int Format32bppRgb
```


Specifica che il formato è di 32 bit per pixel; 8 bit ciascuno sono usati per i componenti rosso, verde e blu. Gli 8 bit rimanenti non sono utilizzati.

### Format32bppArgb {#Format32bppArgb}
```
public static final int Format32bppArgb
```


Specifica che il formato è di 32 bit per pixel; 8 bit ciascuno sono usati per i componenti alpha, rosso, verde e blu.

### Format32bppPArgb {#Format32bppPArgb}
```
public static final int Format32bppPArgb
```


Specifica che il formato è di 32 bit per pixel; 8 bit ciascuno sono usati per i componenti alpha, rosso, verde e blu. I componenti rosso, verde e blu sono premoltiplicati in base al componente alpha.

### Format48bppRgb {#Format48bppRgb}
```
public static final int Format48bppRgb
```


Specifica che il formato è di 48 bit per pixel; 16 bit ciascuno sono usati per i componenti rosso, verde e blu.

### Format64bppArgb {#Format64bppArgb}
```
public static final int Format64bppArgb
```


Specifica che il formato è di 64 bit per pixel; 16 bit ciascuno sono usati per i componenti alpha, rosso, verde e blu.

### Format64bppPArgb {#Format64bppPArgb}
```
public static final int Format64bppPArgb
```


Specifica che il formato è di 64 bit per pixel; 16 bit ciascuno sono usati per i componenti alpha, rosso, verde e blu. I componenti rosso, verde e blu sono premoltiplicati in base al componente alpha.

### Max {#Max}
```
public static final int Max
```


Il valore massimo per questa enumerazione.

