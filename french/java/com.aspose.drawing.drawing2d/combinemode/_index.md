---
title: CombineMode
second_title: Référence de l'API Aspose.Drawing pour Java
description: Spécifie comment différentes régions de découpage peuvent être combinées.
type: docs
weight: 13
url: /fr/java/com.aspose.drawing.drawing2d/combinemode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class CombineMode extends System.Enum
```

Spécifie comment différentes régions de découpage peuvent être combinées.
## Champs

| Champ | Description |
| --- | --- |
| [Replace](#Replace) | Une région de découpage est remplacée par une autre. |
| [Intersect](#Intersect) | Deux régions de découpage sont combinées en prenant leur intersection. |
| [Union](#Union) | Deux régions de découpage sont combinées en prenant l'union des deux. |
| [Xor](#Xor) | Deux régions de découpage sont combinées en ne conservant que les zones enfermées par l'une ou l'autre région, mais pas les deux. |
| [Exclude](#Exclude) | Spécifie que la région existante est remplacée par le résultat de la suppression de la nouvelle région de la région existante. |
| [Complement](#Complement) | Spécifie que la région existante est remplacée par le résultat de la suppression de la région existante de la nouvelle région. |
### Replace {#Replace}
```
public static final int Replace
```


Une région de découpage est remplacée par une autre.

### Intersect {#Intersect}
```
public static final int Intersect
```


Deux régions de découpage sont combinées en prenant leur intersection.

### Union {#Union}
```
public static final int Union
```


Deux régions de découpage sont combinées en prenant l'union des deux.

### Xor {#Xor}
```
public static final int Xor
```


Deux régions de découpage sont combinées en ne conservant que les zones enfermées par l'une ou l'autre région, mais pas les deux.

### Exclude {#Exclude}
```
public static final int Exclude
```


Spécifie que la région existante est remplacée par le résultat de la suppression de la nouvelle région de la région existante. Dit autrement, la nouvelle région est exclue de la région existante.

### Complement {#Complement}
```
public static final int Complement
```


Spécifie que la région existante est remplacée par le résultat de la suppression de la région existante de la nouvelle région. Dit autrement, la région existante est exclue de la nouvelle région.

