---
title: DrawingSettings
second_title: Riferimento API di Aspose.Drawing per Java
description: Consente di regolare il comportamento della libreria di disegno nel caso di utilizzo di alcune funzionalità non ancora implementate completamente.
type: docs
weight: 19
url: /it/java/com.aspose.drawing/drawingsettings/
---
**Inheritance:**
java.lang.Object
```
public final class DrawingSettings
```

Consente di regolare il comportamento della libreria di disegno nel caso di utilizzo di alcune funzionalità non ancora implementate completamente.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [DrawingSettings()](#DrawingSettings--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getStrictMode()](#getStrictMode--) | Restituisce un valore che indica se il rilevamento più rigoroso delle funzionalità non implementate è abilitato. |
| [setStrictMode(boolean value)](#setStrictMode-boolean-) | Imposta un valore che indica se il rilevamento più rigoroso delle funzionalità non implementate è abilitato. |
### DrawingSettings() {#DrawingSettings--}
```
public DrawingSettings()
```


### getStrictMode() {#getStrictMode--}
```
public static boolean getStrictMode()
```


Restituisce un valore che indica se il rilevamento più rigoroso delle funzionalità non implementate è abilitato.

--------------------

Se impostato su true, nel caso di utilizzo di funzionalità/parametri che non funzionano correttamente nell'implementazione corrente, la libreria lancerà NotImplementedException. Se impostato su false, alcuni parametri potrebbero essere ignorati per consentire al programma dell'utente di funzionare. In tal caso i risultati del disegno potrebbero apparire diversi rispetto a GDI+.

**Returns:**
boolean - un valore che indica se il rilevamento più rigoroso delle funzionalità non implementate è abilitato.
### setStrictMode(boolean value) {#setStrictMode-boolean-}
```
public static void setStrictMode(boolean value)
```


Imposta un valore che indica se il rilevamento più rigoroso delle funzionalità non implementate è abilitato.

--------------------

Se impostato su true, nel caso di utilizzo di funzionalità/parametri che non funzionano correttamente nell'implementazione corrente, la libreria lancerà NotImplementedException. Se impostato su false, alcuni parametri potrebbero essere ignorati per consentire al programma dell'utente di funzionare. In tal caso i risultati del disegno potrebbero apparire diversi rispetto a GDI+.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean | un valore che indica se il rilevamento più rigoroso delle funzionalità non implementate è abilitato. |

