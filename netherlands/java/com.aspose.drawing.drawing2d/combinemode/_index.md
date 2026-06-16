---
title: CombineMode
second_title: Aspose.Drawing voor Java API-referentie
description: Specificeert hoe verschillende knipregio's kunnen worden gecombineerd.
type: docs
weight: 13
url: /nl/java/com.aspose.drawing.drawing2d/combinemode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class CombineMode extends System.Enum
```

Specificeert hoe verschillende knipregio's kunnen worden gecombineerd.
## Velden

| Veld | Beschrijving |
| --- | --- |
| [Replace](#Replace) | Een knipgebied wordt vervangen door een ander. |
| [Intersect](#Intersect) | Twee knipgebieden worden gecombineerd door hun intersectie te nemen. |
| [Union](#Union) | Twee knipgebieden worden gecombineerd door de unie van beide te nemen. |
| [Xor](#Xor) | Twee knipgebieden worden gecombineerd door alleen de gebieden te nemen die door het ene of het andere gebied worden omsloten, maar niet beide. |
| [Exclude](#Exclude) | Specificeert dat het bestaande gebied wordt vervangen door het resultaat van het verwijderen van het nieuwe gebied uit het bestaande gebied. |
| [Complement](#Complement) | Specificeert dat het bestaande gebied wordt vervangen door het resultaat van het verwijderen van het bestaande gebied uit het nieuwe gebied. |
### Replace {#Replace}
```
public static final int Replace
```


Een knipgebied wordt vervangen door een ander.

### Intersect {#Intersect}
```
public static final int Intersect
```


Twee knipgebieden worden gecombineerd door hun intersectie te nemen.

### Union {#Union}
```
public static final int Union
```


Twee knipgebieden worden gecombineerd door de unie van beide te nemen.

### Xor {#Xor}
```
public static final int Xor
```


Twee knipgebieden worden gecombineerd door alleen de gebieden te nemen die door het ene of het andere gebied worden omsloten, maar niet beide.

### Exclude {#Exclude}
```
public static final int Exclude
```


Specificeert dat het bestaande gebied wordt vervangen door het resultaat van het verwijderen van het nieuwe gebied uit het bestaande gebied. Anders gezegd, het nieuwe gebied wordt uitgesloten van het bestaande gebied.

### Complement {#Complement}
```
public static final int Complement
```


Specificeert dat het bestaande gebied wordt vervangen door het resultaat van het verwijderen van het bestaande gebied uit het nieuwe gebied. Anders gezegd, het bestaande gebied wordt uitgesloten van het nieuwe gebied.

