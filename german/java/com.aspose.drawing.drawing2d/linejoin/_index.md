---
title: LineJoin
second_title: Aspose.Drawing für Java API-Referenz
description: Gibt an, wie aufeinanderfolgende Linien- oder Kurvensegmente in einem Teilpfad einer Figur, die in einem GraphicsPath-Objekt enthalten ist, verbunden werden.
type: docs
weight: 30
url: /de/java/com.aspose.drawing.drawing2d/linejoin/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class LineJoin extends System.Enum
```

Gibt an, wie aufeinanderfolgende Linien- oder Kurvensegmente in einer Figur (Unterpfad), die in einem GraphicsPath-Objekt enthalten ist, verbunden werden.
## Felder

| Feld | Beschreibung |
| --- | --- |
| [Miter](#Miter) | Gibt eine Gehrungsschnittverbindung an. |
| [Bevel](#Bevel) | Gibt eine abgeschrägte Verbindung an. |
| [Round](#Round) | Gibt eine runde Verbindung an. |
| [MiterClipped](#MiterClipped) | Gibt eine Gehrungsschnittverbindung an. |
### Miter {#Miter}
```
public static final int Miter
```


Gibt eine Gehrungsschnittverbindung an. Dies erzeugt eine spitze Ecke oder eine abgeschnittene Ecke, abhängig davon, ob die Länge der Gehrung das Gehrungslimit überschreitet.

--------------------

Derzeit funktioniert die Gehrungsschnittverbindung tatsächlich wie MiterClipped.

### Bevel {#Bevel}
```
public static final int Bevel
```


Gibt eine abgeschrägte Verbindung an. Dies erzeugt eine diagonale Ecke.

### Round {#Round}
```
public static final int Round
```


Gibt eine runde Verbindung an. Dies erzeugt einen glatten, kreisförmigen Bogen zwischen den Linien.

### MiterClipped {#MiterClipped}
```
public static final int MiterClipped
```


Gibt eine Gehrungsschnittverbindung an. Dies erzeugt eine spitze Ecke oder eine abgeschrägte Ecke, abhängig davon, ob die Länge der Gehrung das Gehrungslimit überschreitet.

