---
title: DrawingSettings
second_title: Aspose.Drawing für Java API-Referenz
description: Ermöglicht die Anpassung des Verhaltens der Zeichenbibliothek, falls einige Funktionen verwendet werden, die noch nicht vollständig implementiert sind.
type: docs
weight: 19
url: /de/java/com.aspose.drawing/drawingsettings/
---
**Inheritance:**
java.lang.Object
```
public final class DrawingSettings
```

Ermöglicht die Anpassung des Verhaltens der Zeichenbibliothek, falls einige Funktionen verwendet werden, die noch nicht vollständig implementiert sind.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [DrawingSettings()](#DrawingSettings--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getStrictMode()](#getStrictMode--) | Ermittelt einen Wert, der angibt, ob das strengere Abfangen nicht implementierter Funktionen aktiviert ist. |
| [setStrictMode(boolean value)](#setStrictMode-boolean-) | Legt einen Wert fest, der angibt, ob das strengere Abfangen nicht implementierter Funktionen aktiviert ist. |
### DrawingSettings() {#DrawingSettings--}
```
public DrawingSettings()
```


### getStrictMode() {#getStrictMode--}
```
public static boolean getStrictMode()
```


Ermittelt einen Wert, der angibt, ob das strengere Abfangen nicht implementierter Funktionen aktiviert ist.

--------------------

Wenn auf true gesetzt, wird bei Verwendung von Funktionen/Parametern, die in der aktuellen Implementierung nicht korrekt funktionieren, die Bibliothek eine NotImplementedException auslösen. Wenn auf false gesetzt, können einige Parameter ignoriert werden, um dem Benutzerprogramm die Möglichkeit zu geben, zu funktionieren. In diesem Fall können die Zeichnungsergebnisse im Vergleich zu GDI+ anders aussehen.

**Returns:**
boolean – ein Wert, der angibt, ob das strengere Abfangen nicht implementierter Funktionen aktiviert ist.
### setStrictMode(boolean value) {#setStrictMode-boolean-}
```
public static void setStrictMode(boolean value)
```


Legt einen Wert fest, der angibt, ob das strengere Abfangen nicht implementierter Funktionen aktiviert ist.

--------------------

Wenn auf true gesetzt, wird bei Verwendung von Funktionen/Parametern, die in der aktuellen Implementierung nicht korrekt funktionieren, die Bibliothek eine NotImplementedException auslösen. Wenn auf false gesetzt, können einige Parameter ignoriert werden, um dem Benutzerprogramm die Möglichkeit zu geben, zu funktionieren. In diesem Fall können die Zeichnungsergebnisse im Vergleich zu GDI+ anders aussehen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean | ein Wert, der angibt, ob das strengere Abfangen nicht implementierter Funktionen aktiviert ist. |

