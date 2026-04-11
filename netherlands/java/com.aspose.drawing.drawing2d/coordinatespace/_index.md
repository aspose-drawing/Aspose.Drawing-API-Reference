---
title: CoordinateSpace
second_title: Aspose.Drawing voor Java API-referentie
description: Specificeert het systeem dat moet worden gebruikt bij het evalueren van coördinaten.
type: docs
weight: 16
url: /nl/java/com.aspose.drawing.drawing2d/coordinatespace/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class CoordinateSpace extends System.Enum
```

Specificeert het systeem dat moet worden gebruikt bij het evalueren van coördinaten.
## Velden

| Veld | Beschrijving |
| --- | --- |
| [World](#World) | Geeft aan dat coördinaten zich in de wereldcoördinaatcontext bevinden. |
| [Page](#Page) | Geeft aan dat coördinaten zich in de paginacoördinaatcontext bevinden. |
| [Device](#Device) | Geeft aan dat coördinaten zich in de apparaatcoördinaatcontext bevinden. |
### World {#World}
```
public static final int World
```


Geeft aan dat coördinaten zich in de wereldcoördinaatcontext bevinden. Wereldcoördinaten worden gebruikt in een niet-fysieke omgeving, zoals een modelleringsomgeving.

### Page {#Page}
```
public static final int Page
```


Geeft aan dat coördinaten zich in de paginacoördinaatcontext bevinden. Hun eenheden worden gedefinieerd door de eigenschap Graphics.PageUnit en moeten een van de elementen van de enumeratie GraphicsUnit zijn.

### Device {#Device}
```
public static final int Device
```


Geeft aan dat coördinaten zich in de apparaatcoördinaatcontext bevinden. Op een computerscherm worden de apparaatcoördinaten meestal gemeten in pixels.

