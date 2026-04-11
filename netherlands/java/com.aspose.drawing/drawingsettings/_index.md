---
title: DrawingSettings
second_title: Aspose.Drawing voor Java API-referentie
description: Staat toe het gedrag van de tekenbibliotheek aan te passen in het geval van het gebruik van enkele functies die nog niet volledig zijn geïmplementeerd.
type: docs
weight: 19
url: /nl/java/com.aspose.drawing/drawingsettings/
---
**Inheritance:**
java.lang.Object
```
public final class DrawingSettings
```

Staat toe het gedrag van de tekenbibliotheek aan te passen in het geval van het gebruik van enkele functies die nog niet volledig zijn geïmplementeerd.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [DrawingSettings()](#DrawingSettings--) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getStrictMode()](#getStrictMode--) | Haalt een waarde op die aangeeft of het strengere afvangen van niet‑geïmplementeerde functies is ingeschakeld. |
| [setStrictMode(boolean value)](#setStrictMode-boolean-) | Stelt een waarde in die aangeeft of het strengere afvangen van niet‑geïmplementeerde functies is ingeschakeld. |
### DrawingSettings() {#DrawingSettings--}
```
public DrawingSettings()
```


### getStrictMode() {#getStrictMode--}
```
public static boolean getStrictMode()
```


Haalt een waarde op die aangeeft of het strengere afvangen van niet‑geïmplementeerde functies is ingeschakeld.

--------------------

Als dit op true wordt gezet, zal de bibliotheek bij het gebruik van functies/parameters die niet correct werken in de huidige implementatie een NotImplementedException werpen. Als dit op false wordt gezet, kunnen sommige parameters worden genegeerd om het gebruikersprogramma de kans te geven te werken. In dat geval kunnen de tekenresultaten er anders uitzien vergeleken met GDI+.

**Returns:**
boolean - een waarde die aangeeft of het strengere afvangen van niet‑geïmplementeerde functies is ingeschakeld.
### setStrictMode(boolean value) {#setStrictMode-boolean-}
```
public static void setStrictMode(boolean value)
```


Stelt een waarde in die aangeeft of het strengere afvangen van niet‑geïmplementeerde functies is ingeschakeld.

--------------------

Als dit op true wordt gezet, zal de bibliotheek bij het gebruik van functies/parameters die niet correct werken in de huidige implementatie een NotImplementedException werpen. Als dit op false wordt gezet, kunnen sommige parameters worden genegeerd om het gebruikersprogramma de kans te geven te werken. In dat geval kunnen de tekenresultaten er anders uitzien vergeleken met GDI+.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean | een waarde die aangeeft of het strengere afvangen van niet‑geïmplementeerde functies is ingeschakeld. |

