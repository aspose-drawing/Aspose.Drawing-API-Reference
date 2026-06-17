---
title: SystemFonts
second_title: Riferimento API di Aspose.Drawing per Java
description: Specifica i caratteri utilizzati per visualizzare il testo negli elementi di visualizzazione di Windows.
type: docs
weight: 51
url: /it/java/com.aspose.drawing/systemfonts/
---
**Inheritance:**
java.lang.Object
```
public final class SystemFonts
```

Specifica i caratteri utilizzati per visualizzare il testo negli elementi di visualizzazione di Windows.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getCaptionFont()](#getCaptionFont--) | Ottiene un [Font](../../com.aspose.drawing/font) utilizzato per visualizzare il testo nelle barre del titolo delle finestre. |
| [getSmallCaptionFont()](#getSmallCaptionFont--) | Ottiene un [Font](../../com.aspose.drawing/font) utilizzato per visualizzare il testo nelle barre del titolo delle piccole finestre, come le finestre degli strumenti. |
| [getMenuFont()](#getMenuFont--) | Ottiene un [Font](../../com.aspose.drawing/font) utilizzato per i menu. |
| [getStatusFont()](#getStatusFont--) | Ottiene un [Font](../../com.aspose.drawing/font) utilizzato per visualizzare il testo nella barra di stato. |
| [getMessageBoxFont()](#getMessageBoxFont--) | Ottiene un [Font](../../com.aspose.drawing/font) utilizzato per le finestre di messaggio. |
| [getIconTitleFont()](#getIconTitleFont--) | Ottiene un [Font](../../com.aspose.drawing/font) utilizzato per i titoli delle icone. |
| [getDefaultFont()](#getDefaultFont--) | Ottiene il font predefinito che le applicazioni possono utilizzare per finestre di dialogo e moduli. |
| [getDefaultImageFont()](#getDefaultImageFont--) | Ottiene il font predefinito che le applicazioni possono utilizzare per finestre di dialogo e moduli. |
| [getDialogFont()](#getDialogFont--) | Ottiene un font che le applicazioni possono utilizzare per finestre di dialogo e moduli. |
| [getFontByName(String systemFontName)](#getFontByName-java.lang.String-) | Restituisce un oggetto font che corrisponde al nome del font di sistema specificato. |
### getCaptionFont() {#getCaptionFont--}
```
public static Font getCaptionFont()
```


Ottiene un [Font](../../com.aspose.drawing/font) utilizzato per visualizzare il testo nelle barre del titolo delle finestre.

**Returns:**
[Font](../../com.aspose.drawing/font) - a [Font](../../com.aspose.drawing/font) that is used to display text in the title bars of windows.
### getSmallCaptionFont() {#getSmallCaptionFont--}
```
public static Font getSmallCaptionFont()
```


Ottiene un [Font](../../com.aspose.drawing/font) utilizzato per visualizzare il testo nelle barre del titolo delle piccole finestre, come le finestre degli strumenti.

**Returns:**
[Font](../../com.aspose.drawing/font) - a [Font](../../com.aspose.drawing/font) that is used to display text in the title bars of small windows, such as tool windows.
### getMenuFont() {#getMenuFont--}
```
public static Font getMenuFont()
```


Ottiene un [Font](../../com.aspose.drawing/font) utilizzato per i menu.

**Returns:**
[Font](../../com.aspose.drawing/font) - a [Font](../../com.aspose.drawing/font) that is used for menus.
### getStatusFont() {#getStatusFont--}
```
public static Font getStatusFont()
```


Ottiene un [Font](../../com.aspose.drawing/font) utilizzato per visualizzare il testo nella barra di stato.

**Returns:**
[Font](../../com.aspose.drawing/font) - a [Font](../../com.aspose.drawing/font) that is used to display text in the status bar.
### getMessageBoxFont() {#getMessageBoxFont--}
```
public static Font getMessageBoxFont()
```


Ottiene un [Font](../../com.aspose.drawing/font) utilizzato per le finestre di messaggio.

**Returns:**
[Font](../../com.aspose.drawing/font) - a [Font](../../com.aspose.drawing/font) that is used for message boxes.
### getIconTitleFont() {#getIconTitleFont--}
```
public static Font getIconTitleFont()
```


Ottiene un [Font](../../com.aspose.drawing/font) utilizzato per i titoli delle icone.

**Returns:**
[Font](../../com.aspose.drawing/font) - a [Font](../../com.aspose.drawing/font) that is used for icon titles.
### getDefaultFont() {#getDefaultFont--}
```
public static Font getDefaultFont()
```


Ottiene il font predefinito che le applicazioni possono utilizzare per finestre di dialogo e moduli.

**Returns:**
[Font](../../com.aspose.drawing/font) - The default [Font](../../com.aspose.drawing/font) of the system. The value returned will vary depending on the user's operating system and the local culture setting of their system.
### getDefaultImageFont() {#getDefaultImageFont--}
```
public static Font getDefaultImageFont()
```


Ottiene il font predefinito che le applicazioni possono utilizzare per finestre di dialogo e moduli.

**Returns:**
[Font](../../com.aspose.imaging/font) - The default [Font](../../com.aspose.drawing/font) of the system. The value returned will vary depending on the user's operating system and the local culture setting of their system.
### getDialogFont() {#getDialogFont--}
```
public static Font getDialogFont()
```


Ottiene un font che le applicazioni possono utilizzare per finestre di dialogo e moduli.

**Returns:**
[Font](../../com.aspose.drawing/font) - A [Font](../../com.aspose.drawing/font) that can be used for dialog boxes and forms, depending on the operating system and local culture setting of the system.
### getFontByName(String systemFontName) {#getFontByName-java.lang.String-}
```
public static Font getFontByName(String systemFontName)
```


Restituisce un oggetto font che corrisponde al nome del font di sistema specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| systemFontName | java.lang.String | Il nome del font di sistema per il quale è necessario un oggetto font. |

**Returns:**
[Font](../../com.aspose.drawing/font) - A [Font](../../com.aspose.drawing/font) if the specified name matches a value in [SystemFonts](../../com.aspose.drawing/systemfonts); otherwise, null.
