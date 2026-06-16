---
title: LineJoin
second_title: Aspose.Drawing voor Java API-referentie
description: Specificeert hoe opeenvolgende lijn- of krommesegmenten in een figuur-subpad binnen een GraphicsPath-object worden samengevoegd.
type: docs
weight: 30
url: /nl/java/com.aspose.drawing.drawing2d/linejoin/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class LineJoin extends System.Enum
```

Specificeert hoe opeenvolgende lijn- of krommesegmenten in een figuur (subpad) die zich bevindt in een GraphicsPath-object, worden samengevoegd.
## Velden

| Veld | Beschrijving |
| --- | --- |
| [Miter](#Miter) | Specificeert een verstekverbinding. |
| [Bevel](#Bevel) | Specificeert een afgeschuinde verbinding. |
| [Round](#Round) | Specificeert een ronde verbinding. |
| [MiterClipped](#MiterClipped) | Specificeert een verstekverbinding. |
### Miter {#Miter}
```
public static final int Miter
```


Specificeert een verstekverbinding. Dit resulteert in een scherpe hoek of een afgekapt hoek, afhankelijk van of de lengte van de verstek de versteklimiet overschrijdt.

--------------------

Op dit moment werkt de verstekverbinding eigenlijk als MiterClipped.

### Bevel {#Bevel}
```
public static final int Bevel
```


Specificeert een afgeschuinde verbinding. Dit resulteert in een diagonale hoek.

### Round {#Round}
```
public static final int Round
```


Specificeert een ronde verbinding. Dit resulteert in een vloeiende, ronde boog tussen de lijnen.

### MiterClipped {#MiterClipped}
```
public static final int MiterClipped
```


Specificeert een verstekverbinding. Dit resulteert in een scherpe hoek of een afgeschuinde hoek, afhankelijk van of de lengte van de verstek de versteklimiet overschrijdt.

