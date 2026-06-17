---
title: CombineMode
second_title: Riferimento API di Aspose.Drawing per Java
description: Specifica come le diverse regioni di ritaglio possono essere combinate.
type: docs
weight: 13
url: /it/java/com.aspose.drawing.drawing2d/combinemode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class CombineMode extends System.Enum
```

Specifica come le diverse regioni di ritaglio possono essere combinate.
## Campi

| Campo | Descrizione |
| --- | --- |
| [Replace](#Replace) | Una regione di ritaglio viene sostituita da un'altra. |
| [Intersect](#Intersect) | Due regioni di ritaglio vengono combinate prendendo la loro intersezione. |
| [Union](#Union) | Due regioni di ritaglio vengono combinate prendendo l'unione di entrambe. |
| [Xor](#Xor) | Due regioni di ritaglio vengono combinate prendendo solo le aree racchiuse da una o l'altra regione, ma non da entrambe. |
| [Exclude](#Exclude) | Specifica che la regione esistente viene sostituita dal risultato della nuova regione rimossa dalla regione esistente. |
| [Complement](#Complement) | Specifica che la regione esistente viene sostituita dal risultato della regione esistente rimossa dalla nuova regione. |
### Replace {#Replace}
```
public static final int Replace
```


Una regione di ritaglio viene sostituita da un'altra.

### Intersect {#Intersect}
```
public static final int Intersect
```


Due regioni di ritaglio vengono combinate prendendo la loro intersezione.

### Union {#Union}
```
public static final int Union
```


Due regioni di ritaglio vengono combinate prendendo l'unione di entrambe.

### Xor {#Xor}
```
public static final int Xor
```


Due regioni di ritaglio vengono combinate prendendo solo le aree racchiuse da una o l'altra regione, ma non da entrambe.

### Exclude {#Exclude}
```
public static final int Exclude
```


Specifica che la regione esistente viene sostituita dal risultato della nuova regione rimossa dalla regione esistente. Detto diversamente, la nuova regione è esclusa dalla regione esistente.

### Complement {#Complement}
```
public static final int Complement
```


Specifica che la regione esistente viene sostituita dal risultato della regione esistente rimossa dalla nuova regione. Detto diversamente, la regione esistente è esclusa dalla nuova regione.

