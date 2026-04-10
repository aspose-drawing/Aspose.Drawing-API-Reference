---
title: SystemFonts
second_title: Aspose.Drawing für Java API-Referenz
description: Gibt die Schriften an, die zur Anzeige von Text in Windows-Anzeigeelementen verwendet werden.
type: docs
weight: 51
url: /de/java/com.aspose.drawing/systemfonts/
---
**Inheritance:**
java.lang.Object
```
public final class SystemFonts
```

Gibt die Schriften an, die zur Anzeige von Text in Windows-Anzeigeelementen verwendet werden.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getCaptionFont()](#getCaptionFont--) | Ruft eine [Font](../../com.aspose.drawing/font) ab, die verwendet wird, um Text in den Titelleisten von Fenstern anzuzeigen. |
| [getSmallCaptionFont()](#getSmallCaptionFont--) | Ruft eine [Font](../../com.aspose.drawing/font) ab, die verwendet wird, um Text in den Titelleisten kleiner Fenster, wie z. B. Werkzeugfenstern, anzuzeigen. |
| [getMenuFont()](#getMenuFont--) | Ruft eine [Font](../../com.aspose.drawing/font) ab, die für Menüs verwendet wird. |
| [getStatusFont()](#getStatusFont--) | Ruft eine [Font](../../com.aspose.drawing/font) ab, die verwendet wird, um Text in der Statusleiste anzuzeigen. |
| [getMessageBoxFont()](#getMessageBoxFont--) | Ruft eine [Font](../../com.aspose.drawing/font) ab, die für Meldungsfelder verwendet wird. |
| [getIconTitleFont()](#getIconTitleFont--) | Ruft eine [Font](../../com.aspose.drawing/font) ab, die für Symboltitel verwendet wird. |
| [getDefaultFont()](#getDefaultFont--) | Ruft die Standardschriftart ab, die Anwendungen für Dialogfelder und Formulare verwenden können. |
| [getDefaultImageFont()](#getDefaultImageFont--) | Ruft die Standardschriftart ab, die Anwendungen für Dialogfelder und Formulare verwenden können. |
| [getDialogFont()](#getDialogFont--) | Ruft eine Schriftart ab, die Anwendungen für Dialogfelder und Formulare verwenden können. |
| [getFontByName(String systemFontName)](#getFontByName-java.lang.String-) | Gibt ein Schriftartobjekt zurück, das dem angegebenen Systemschriftartnamen entspricht. |
### getCaptionFont() {#getCaptionFont--}
```
public static Font getCaptionFont()
```


Ruft eine [Font](../../com.aspose.drawing/font) ab, die verwendet wird, um Text in den Titelleisten von Fenstern anzuzeigen.

**Returns:**
[Font](../../com.aspose.drawing/font) - a [Font](../../com.aspose.drawing/font) that is used to display text in the title bars of windows.
### getSmallCaptionFont() {#getSmallCaptionFont--}
```
public static Font getSmallCaptionFont()
```


Ruft eine [Font](../../com.aspose.drawing/font) ab, die verwendet wird, um Text in den Titelleisten kleiner Fenster, wie z. B. Werkzeugfenstern, anzuzeigen.

**Returns:**
[Font](../../com.aspose.drawing/font) - a [Font](../../com.aspose.drawing/font) that is used to display text in the title bars of small windows, such as tool windows.
### getMenuFont() {#getMenuFont--}
```
public static Font getMenuFont()
```


Ruft eine [Font](../../com.aspose.drawing/font) ab, die für Menüs verwendet wird.

**Returns:**
[Font](../../com.aspose.drawing/font) - a [Font](../../com.aspose.drawing/font) that is used for menus.
### getStatusFont() {#getStatusFont--}
```
public static Font getStatusFont()
```


Ruft eine [Font](../../com.aspose.drawing/font) ab, die verwendet wird, um Text in der Statusleiste anzuzeigen.

**Returns:**
[Font](../../com.aspose.drawing/font) - a [Font](../../com.aspose.drawing/font) that is used to display text in the status bar.
### getMessageBoxFont() {#getMessageBoxFont--}
```
public static Font getMessageBoxFont()
```


Ruft eine [Font](../../com.aspose.drawing/font) ab, die für Meldungsfelder verwendet wird.

**Returns:**
[Font](../../com.aspose.drawing/font) - a [Font](../../com.aspose.drawing/font) that is used for message boxes.
### getIconTitleFont() {#getIconTitleFont--}
```
public static Font getIconTitleFont()
```


Ruft eine [Font](../../com.aspose.drawing/font) ab, die für Symboltitel verwendet wird.

**Returns:**
[Font](../../com.aspose.drawing/font) - a [Font](../../com.aspose.drawing/font) that is used for icon titles.
### getDefaultFont() {#getDefaultFont--}
```
public static Font getDefaultFont()
```


Ruft die Standardschriftart ab, die Anwendungen für Dialogfelder und Formulare verwenden können.

**Returns:**
[Font](../../com.aspose.drawing/font) - The default [Font](../../com.aspose.drawing/font) of the system. The value returned will vary depending on the user's operating system and the local culture setting of their system.
### getDefaultImageFont() {#getDefaultImageFont--}
```
public static Font getDefaultImageFont()
```


Ruft die Standardschriftart ab, die Anwendungen für Dialogfelder und Formulare verwenden können.

**Returns:**
[Font](../../com.aspose.imaging/font) - The default [Font](../../com.aspose.drawing/font) of the system. The value returned will vary depending on the user's operating system and the local culture setting of their system.
### getDialogFont() {#getDialogFont--}
```
public static Font getDialogFont()
```


Ruft eine Schriftart ab, die Anwendungen für Dialogfelder und Formulare verwenden können.

**Returns:**
[Font](../../com.aspose.drawing/font) - A [Font](../../com.aspose.drawing/font) that can be used for dialog boxes and forms, depending on the operating system and local culture setting of the system.
### getFontByName(String systemFontName) {#getFontByName-java.lang.String-}
```
public static Font getFontByName(String systemFontName)
```


Gibt ein Schriftartobjekt zurück, das dem angegebenen Systemschriftartnamen entspricht.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| systemFontName | java.lang.String | Der Name der Systemschriftart, für die Sie ein Schriftartobjekt benötigen. |

**Returns:**
[Font](../../com.aspose.drawing/font) - A [Font](../../com.aspose.drawing/font) if the specified name matches a value in [SystemFonts](../../com.aspose.drawing/systemfonts); otherwise, null.
