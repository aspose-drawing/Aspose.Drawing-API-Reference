---
title: DrawingSettings
second_title: Référence de l'API Aspose.Drawing pour Java
description: Permet d'ajuster le comportement de la bibliothèque de dessin en cas d'utilisation de certaines fonctionnalités qui ne sont pas encore entièrement implémentées.
type: docs
weight: 19
url: /fr/java/com.aspose.drawing/drawingsettings/
---
**Inheritance:**
java.lang.Object
```
public final class DrawingSettings
```

Permet d'ajuster le comportement de la bibliothèque de dessin en cas d'utilisation de certaines fonctionnalités qui ne sont pas encore entièrement implémentées.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [DrawingSettings()](#DrawingSettings--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getStrictMode()](#getStrictMode--) | Obtient une valeur indiquant si la capture plus stricte des fonctionnalités non implémentées est activée. |
| [setStrictMode(boolean value)](#setStrictMode-boolean-) | Définit une valeur indiquant si la capture plus stricte des fonctionnalités non implémentées est activée. |
### DrawingSettings() {#DrawingSettings--}
```
public DrawingSettings()
```


### getStrictMode() {#getStrictMode--}
```
public static boolean getStrictMode()
```


Obtient une valeur indiquant si la capture plus stricte des fonctionnalités non implémentées est activée.

--------------------

Si la valeur est vraie, en cas d'utilisation de fonctionnalités/paramètres qui ne fonctionnent pas correctement dans l'implémentation actuelle, la bibliothèque lèvera une NotImplementedException. Si la valeur est fausse, certains paramètres peuvent être ignorés afin de permettre au programme de l'utilisateur de fonctionner. Dans ce cas, les résultats du rendu peuvent différer de ceux de GDI+.

**Returns:**
boolean - une valeur indiquant si la capture plus stricte des fonctionnalités non implémentées est activée.
### setStrictMode(boolean value) {#setStrictMode-boolean-}
```
public static void setStrictMode(boolean value)
```


Définit une valeur indiquant si la capture plus stricte des fonctionnalités non implémentées est activée.

--------------------

Si la valeur est vraie, en cas d'utilisation de fonctionnalités/paramètres qui ne fonctionnent pas correctement dans l'implémentation actuelle, la bibliothèque lèvera une NotImplementedException. Si la valeur est fausse, certains paramètres peuvent être ignorés afin de permettre au programme de l'utilisateur de fonctionner. Dans ce cas, les résultats du rendu peuvent différer de ceux de GDI+.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean | une valeur indiquant si la capture plus stricte des fonctionnalités non implémentées est activée. |

