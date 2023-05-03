---
title: Size
second_title: Aspose.Drawing per .NET API Reference
description: Memorizza una coppia ordinata di numeri interi in genere la larghezza e laltezza di un rettangolo.
type: docs
weight: 1080
url: /it/net/system.drawing/size/
---
## Size structure

Memorizza una coppia ordinata di numeri interi, in genere la larghezza e l'altezza di un rettangolo.

```csharp
public struct Size : IEquatable<Size>
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [Size](size#constructor_1)(Point) | Inizializza una nuova istanza di[`Size`](../size) struct dal specificatoPoint . |
| [Size](size#constructor)(int, int) | Inizializza una nuova istanza di[`Size`](../size) struct dalle dimensioni specificate. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Height](../../system.drawing/size/height) { get; set; } | Ottiene o imposta il componente verticale di questoSize . |
| [IsEmpty](../../system.drawing/size/isempty) { get; } | Ottiene un valore che indica se questoSize ha larghezza e altezza di 0. |
| [Width](../../system.drawing/size/width) { get; set; } | Ottiene o imposta il componente orizzontale di questoSize . |

## Metodi

| Nome | Descrizione |
| --- | --- |
| static [Add](../../system.drawing/size/add)(Size, Size) | Aggiunge la larghezza e l'altezza di unoSize struttura alla larghezza e all'altezza di un'altraSize struttura. |
| static [Ceiling](../../system.drawing/size/ceiling)(SizeF) | Converte l'oggetto specificatoSizeF struttura ad aSize struttura arrotondando i valori diSize struttura ai successivi valori interi superiori. |
| static [Round](../../system.drawing/size/round)(SizeF) | Converte l'oggetto specificatoSizeF struttura ad aSize struttura arrotondando i valori diSizeF struttura ai valori interi più vicini. |
| static [Subtract](../../system.drawing/size/subtract)(Size, Size) | Sottrae la larghezza e l'altezza di unoSize struttura dalla larghezza e altezza di un'altraSize struttura. |
| static [Truncate](../../system.drawing/size/truncate)(SizeF) | Converte l'oggetto specificatoSizeF struttura ad aSize struttura troncando i valori diSizeF struttura ai successivi valori interi inferiori. |
| override [Equals](../../system.drawing/size/equals#equals_1)(object) | Verifica se l'oggetto specificato è aSize con le stesse dimensioni di questoSize . |
| [Equals](../../system.drawing/size/equals#equals)(Size) | Verifica se altro[`Size`](../size) struttura ha le stesse dimensioni di questo[`Size`](../size) struttura. |
| override [GetHashCode](../../system.drawing/size/gethashcode)() | Restituisce un codice hash per questoSize struttura. |
| override [ToString](../../system.drawing/size/tostring)() | Converte gli attributi di questo[`Size`](../size) in una stringa leggibile dall'uomo. |
| [operator +](../../system.drawing/size/op_addition) | Aggiunge la larghezza e l'altezza di unoSize struttura alla larghezza e all'altezza di un'altraSize struttura. |
| [operator /](../../system.drawing/size/op_division#op_division) | Divide[`Size`](../size) da unInt32 produrre[`Size`](../size) . (2 operators) |
| [operator ==](../../system.drawing/size/op_equality) | Verifica se dueSize le strutture sono uguali. |
| [explicit operator](../../system.drawing/size/op_explicit) | Converte l'oggetto specificatoSize ad unPoint . |
| [implicit operator](../../system.drawing/size/op_implicit) | Converte l'oggetto specificatoSize ad unSizeF . |
| [operator !=](../../system.drawing/size/op_inequality) | Verifica se dueSize le strutture sono diverse. |
| [operator *](../../system.drawing/size/op_multiply#op_multiply) | Moltiplica a[`Size`](../size) da unInt32 produrre[`Size`](../size) . (4 operators) |
| [operator -](../../system.drawing/size/op_subtraction) | Sottrae la larghezza e l'altezza di unoSize struttura dalla larghezza e altezza di un'altraSize struttura. |

## Campi

| Nome | Descrizione |
| --- | --- |
| static readonly [Empty](../../system.drawing/size/empty) | Ottiene aSize struttura che ha aHeight eWidth valore di 0. |

### Guarda anche

* spazio dei nomi [System.Drawing](../../system.drawing)
* assemblea [Aspose.Drawing](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Drawing.dll -->