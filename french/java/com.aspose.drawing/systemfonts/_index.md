---
title: SystemFonts
second_title: Référence de l'API Aspose.Drawing pour Java
description: Spécifie les polices utilisées pour afficher le texte dans les éléments d'affichage Windows.
type: docs
weight: 51
url: /fr/java/com.aspose.drawing/systemfonts/
---
**Inheritance:**
java.lang.Object
```
public final class SystemFonts
```

Spécifie les polices utilisées pour afficher le texte dans les éléments d'affichage Windows.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getCaptionFont()](#getCaptionFont--) | Obtient une [Font](../../com.aspose.drawing/font) qui est utilisée pour afficher du texte dans les barres de titre des fenêtres. |
| [getSmallCaptionFont()](#getSmallCaptionFont--) | Obtient une [Font](../../com.aspose.drawing/font) qui est utilisée pour afficher du texte dans les barres de titre des petites fenêtres, comme les fenêtres d'outils. |
| [getMenuFont()](#getMenuFont--) | Obtient une [Font](../../com.aspose.drawing/font) qui est utilisée pour les menus. |
| [getStatusFont()](#getStatusFont--) | Obtient une [Font](../../com.aspose.drawing/font) qui est utilisée pour afficher du texte dans la barre d'état. |
| [getMessageBoxFont()](#getMessageBoxFont--) | Obtient une [Font](../../com.aspose.drawing/font) qui est utilisée pour les boîtes de message. |
| [getIconTitleFont()](#getIconTitleFont--) | Obtient une [Font](../../com.aspose.drawing/font) qui est utilisée pour les titres d'icônes. |
| [getDefaultFont()](#getDefaultFont--) | Obtient la police par défaut que les applications peuvent utiliser pour les boîtes de dialogue et les formulaires. |
| [getDefaultImageFont()](#getDefaultImageFont--) | Obtient la police par défaut que les applications peuvent utiliser pour les boîtes de dialogue et les formulaires. |
| [getDialogFont()](#getDialogFont--) | Obtient une police que les applications peuvent utiliser pour les boîtes de dialogue et les formulaires. |
| [getFontByName(String systemFontName)](#getFontByName-java.lang.String-) | Renvoie un objet police qui correspond au nom de police système spécifié. |
### getCaptionFont() {#getCaptionFont--}
```
public static Font getCaptionFont()
```


Obtient une [Font](../../com.aspose.drawing/font) qui est utilisée pour afficher du texte dans les barres de titre des fenêtres.

**Returns:**
[Font](../../com.aspose.drawing/font) - a [Font](../../com.aspose.drawing/font) that is used to display text in the title bars of windows.
### getSmallCaptionFont() {#getSmallCaptionFont--}
```
public static Font getSmallCaptionFont()
```


Obtient une [Font](../../com.aspose.drawing/font) qui est utilisée pour afficher du texte dans les barres de titre des petites fenêtres, comme les fenêtres d'outils.

**Returns:**
[Font](../../com.aspose.drawing/font) - a [Font](../../com.aspose.drawing/font) that is used to display text in the title bars of small windows, such as tool windows.
### getMenuFont() {#getMenuFont--}
```
public static Font getMenuFont()
```


Obtient une [Font](../../com.aspose.drawing/font) qui est utilisée pour les menus.

**Returns:**
[Font](../../com.aspose.drawing/font) - a [Font](../../com.aspose.drawing/font) that is used for menus.
### getStatusFont() {#getStatusFont--}
```
public static Font getStatusFont()
```


Obtient une [Font](../../com.aspose.drawing/font) qui est utilisée pour afficher du texte dans la barre d'état.

**Returns:**
[Font](../../com.aspose.drawing/font) - a [Font](../../com.aspose.drawing/font) that is used to display text in the status bar.
### getMessageBoxFont() {#getMessageBoxFont--}
```
public static Font getMessageBoxFont()
```


Obtient une [Font](../../com.aspose.drawing/font) qui est utilisée pour les boîtes de message.

**Returns:**
[Font](../../com.aspose.drawing/font) - a [Font](../../com.aspose.drawing/font) that is used for message boxes.
### getIconTitleFont() {#getIconTitleFont--}
```
public static Font getIconTitleFont()
```


Obtient une [Font](../../com.aspose.drawing/font) qui est utilisée pour les titres d'icônes.

**Returns:**
[Font](../../com.aspose.drawing/font) - a [Font](../../com.aspose.drawing/font) that is used for icon titles.
### getDefaultFont() {#getDefaultFont--}
```
public static Font getDefaultFont()
```


Obtient la police par défaut que les applications peuvent utiliser pour les boîtes de dialogue et les formulaires.

**Returns:**
[Font](../../com.aspose.drawing/font) - The default [Font](../../com.aspose.drawing/font) of the system. The value returned will vary depending on the user's operating system and the local culture setting of their system.
### getDefaultImageFont() {#getDefaultImageFont--}
```
public static Font getDefaultImageFont()
```


Obtient la police par défaut que les applications peuvent utiliser pour les boîtes de dialogue et les formulaires.

**Returns:**
[Font](../../com.aspose.imaging/font) - The default [Font](../../com.aspose.drawing/font) of the system. The value returned will vary depending on the user's operating system and the local culture setting of their system.
### getDialogFont() {#getDialogFont--}
```
public static Font getDialogFont()
```


Obtient une police que les applications peuvent utiliser pour les boîtes de dialogue et les formulaires.

**Returns:**
[Font](../../com.aspose.drawing/font) - A [Font](../../com.aspose.drawing/font) that can be used for dialog boxes and forms, depending on the operating system and local culture setting of the system.
### getFontByName(String systemFontName) {#getFontByName-java.lang.String-}
```
public static Font getFontByName(String systemFontName)
```


Renvoie un objet police qui correspond au nom de police système spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| systemFontName | java.lang.String | Le nom de la police système pour laquelle vous avez besoin d'un objet police. |

**Returns:**
[Font](../../com.aspose.drawing/font) - A [Font](../../com.aspose.drawing/font) if the specified name matches a value in [SystemFonts](../../com.aspose.drawing/systemfonts); otherwise, null.
