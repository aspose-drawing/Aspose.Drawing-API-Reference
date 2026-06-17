---
title: CoordinateSpace
second_title: Référence de l'API Aspose.Drawing pour Java
description: Spécifie le système à utiliser lors de l'évaluation des coordonnées.
type: docs
weight: 16
url: /fr/java/com.aspose.drawing.drawing2d/coordinatespace/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class CoordinateSpace extends System.Enum
```

Spécifie le système à utiliser lors de l'évaluation des coordonnées.
## Champs

| Champ | Description |
| --- | --- |
| [World](#World) | Spécifie que les coordonnées sont dans le contexte de coordonnées du monde. |
| [Page](#Page) | Spécifie que les coordonnées sont dans le contexte de coordonnées de la page. |
| [Device](#Device) | Spécifie que les coordonnées sont dans le contexte de coordonnées du dispositif. |
### World {#World}
```
public static final int World
```


Spécifie que les coordonnées sont dans le contexte de coordonnées du monde. Les coordonnées du monde sont utilisées dans un environnement non physique, tel qu'un environnement de modélisation.

### Page {#Page}
```
public static final int Page
```


Spécifie que les coordonnées sont dans le contexte de coordonnées de la page. Leurs unités sont définies par la propriété Graphics.PageUnit et doivent être l'un des éléments de l'énumération GraphicsUnit.

### Device {#Device}
```
public static final int Device
```


Spécifie que les coordonnées sont dans le contexte de coordonnées du dispositif. Sur un écran d'ordinateur, les coordonnées du dispositif sont généralement mesurées en pixels.

