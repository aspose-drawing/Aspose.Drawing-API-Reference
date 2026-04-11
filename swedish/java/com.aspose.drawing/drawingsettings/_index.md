---
title: DrawingSettings
second_title: Aspose.Drawing för Java API‑referens
description: Tillåter att justera beteendet hos ritbiblioteket vid användning av vissa funktioner som ännu inte är helt implementerade.
type: docs
weight: 19
url: /sv/java/com.aspose.drawing/drawingsettings/
---
**Inheritance:**
java.lang.Object
```
public final class DrawingSettings
```

Tillåter att justera beteendet hos ritbiblioteket vid användning av vissa funktioner som ännu inte är helt implementerade.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [DrawingSettings()](#DrawingSettings--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getStrictMode()](#getStrictMode--) | Hämtar ett värde som indikerar om den striktare fångsten av ej implementerade funktioner är aktiverad. |
| [setStrictMode(boolean value)](#setStrictMode-boolean-) | Ställer in ett värde som indikerar om den striktare fångsten av ej implementerade funktioner är aktiverad. |
### DrawingSettings() {#DrawingSettings--}
```
public DrawingSettings()
```


### getStrictMode() {#getStrictMode--}
```
public static boolean getStrictMode()
```


Hämtar ett värde som indikerar om den striktare fångsten av ej implementerade funktioner är aktiverad.

--------------------

Om den är satt till true, i fall av att använda funktioner/parametrar som inte fungerar korrekt i den aktuella implementationen kommer biblioteket att kasta NotImplementedException. Om den är satt till false kan vissa parametrar ignoreras för att ge användarprogrammet en chans att fungera. I så fall kan ritresultaten se annorlunda ut jämfört med GDI+.

**Returns:**
boolean – ett värde som indikerar om den striktare fångsten av ej implementerade funktioner är aktiverad.
### setStrictMode(boolean value) {#setStrictMode-boolean-}
```
public static void setStrictMode(boolean value)
```


Ställer in ett värde som indikerar om den striktare fångsten av ej implementerade funktioner är aktiverad.

--------------------

Om den är satt till true, i fall av att använda funktioner/parametrar som inte fungerar korrekt i den aktuella implementationen kommer biblioteket att kasta NotImplementedException. Om den är satt till false kan vissa parametrar ignoreras för att ge användarprogrammet en chans att fungera. I så fall kan ritresultaten se annorlunda ut jämfört med GDI+.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean | ett värde som indikerar om den striktare fångsten av ej implementerade funktioner är aktiverad. |

