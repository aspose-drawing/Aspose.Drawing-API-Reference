---
title: FromArgb
second_title: Aspose.Drawing per .NET API Reference
description: Crea aColor struttura da un valore ARGB a 32 bit.
type: docs
weight: 1430
url: /it/net/system.drawing/color/fromargb/
---
## FromArgb(int) {#fromargb}

Crea aColor struttura da un valore ARGB a 32 bit.

```csharp
public static Color FromArgb(int argb)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| argb | Int32 | Un valore che specifica il valore ARGB a 32 bit. |

### Valore di ritorno

IlColor struttura creata da questo metodo.

### Guarda anche

* struct [Color](../../color)
* spazio dei nomi [System.Drawing](../../color)
* assemblea [Aspose.Drawing](../../../)

---

## FromArgb(int, Color) {#fromargb_3}

Crea aColor struttura da quella specificataColorstruttura, ma con il nuovo valore alfa specificato. Sebbene questo metodo consenta di passare un valore a 32 bit per il valore alfa, il valore è limitato a 8 bit.

```csharp
public static Color FromArgb(int alpha, Color baseColor)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| alpha | Int32 | Il valore alfa per il nuovoColor. I valori validi sono compresi tra 0 e 255. |
| baseColor | Color | IlColor da cui creare il nuovoColor. |

### Valore di ritorno

IlColor che questo metodo crea.

### Guarda anche

* struct [Color](../../color)
* spazio dei nomi [System.Drawing](../../color)
* assemblea [Aspose.Drawing](../../../)

---

## FromArgb(int, int, int) {#fromargb_1}

Crea aColor struttura dai valori di colore a 8 bit specificati (rosso, verde e blu). Il valore alfa è implicitamente 255 (completamente opaco). Sebbene questo metodo consenta di passare un valore a 32 bit per ciascun componente di colore, il il valore di ogni componente è limitato a 8 bit.

```csharp
public static Color FromArgb(int red, int green, int blue)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| red | Int32 | Il valore del componente rosso per il nuovoColor. I valori validi sono compresi tra 0 e 255. |
| green | Int32 | Il valore del componente verde per il nuovoColor. I valori validi sono compresi tra 0 e 255. |
| blue | Int32 | Il valore del componente blu per il nuovoColor. I valori validi sono compresi tra 0 e 255. |

### Valore di ritorno

IlColor che questo metodo crea.

### Guarda anche

* struct [Color](../../color)
* spazio dei nomi [System.Drawing](../../color)
* assemblea [Aspose.Drawing](../../../)

---

## FromArgb(int, int, int, int) {#fromargb_2}

Crea una struttura Colore dai quattro valori dei componenti ARGB (alfa, rosso, verde e blu). Sebbene questo metodo consenta di passare un valore a 32 bit per ciascun componente, il valore di ciascun componente è limitato a 8 bit .

```csharp
public static Color FromArgb(int alpha, int red, int green, int blue)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| alpha | Int32 | La componente alfa. I valori validi sono compresi tra 0 e 255. |
| red | Int32 | La componente rossa. I valori validi sono compresi tra 0 e 255. |
| green | Int32 | La componente verde. I valori validi sono compresi tra 0 e 255. |
| blue | Int32 | La componente blu. I valori validi sono compresi tra 0 e 255. |

### Valore di ritorno

Il colore creato da questo metodo.

### Guarda anche

* struct [Color](../../color)
* spazio dei nomi [System.Drawing](../../color)
* assemblea [Aspose.Drawing](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Drawing.dll -->
