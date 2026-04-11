---
title: SystemFonts
second_title: Aspose.Drawing för Java API‑referens
description: Anger vilka teckensnitt som används för att visa text i Windows‑display‑element.
type: docs
weight: 51
url: /sv/java/com.aspose.drawing/systemfonts/
---
**Inheritance:**
java.lang.Object
```
public final class SystemFonts
```

Anger vilka teckensnitt som används för att visa text i Windows‑display‑element.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getCaptionFont()](#getCaptionFont--) | Hämtar ett [Font](../../com.aspose.drawing/font) som används för att visa text i fönstrens titelrader. |
| [getSmallCaptionFont()](#getSmallCaptionFont--) | Hämtar ett [Font](../../com.aspose.drawing/font) som används för att visa text i de små fönstrens titelrader, såsom verktygsfönster. |
| [getMenuFont()](#getMenuFont--) | Hämtar ett [Font](../../com.aspose.drawing/font) som används för menyer. |
| [getStatusFont()](#getStatusFont--) | Hämtar ett [Font](../../com.aspose.drawing/font) som används för att visa text i statusfältet. |
| [getMessageBoxFont()](#getMessageBoxFont--) | Hämtar ett [Font](../../com.aspose.drawing/font) som används för meddelanderutor. |
| [getIconTitleFont()](#getIconTitleFont--) | Hämtar ett [Font](../../com.aspose.drawing/font) som används för ikontitlar. |
| [getDefaultFont()](#getDefaultFont--) | Hämtar standardfonten som program kan använda för dialogrutor och formulär. |
| [getDefaultImageFont()](#getDefaultImageFont--) | Hämtar standardfonten som program kan använda för dialogrutor och formulär. |
| [getDialogFont()](#getDialogFont--) | Hämtar ett font som program kan använda för dialogrutor och formulär. |
| [getFontByName(String systemFontName)](#getFontByName-java.lang.String-) | Returnerar ett font‑objekt som motsvarar det angivna systemfontnamnet. |
### getCaptionFont() {#getCaptionFont--}
```
public static Font getCaptionFont()
```


Hämtar ett [Font](../../com.aspose.drawing/font) som används för att visa text i fönstrens titelrader.

**Returns:**
[Font](../../com.aspose.drawing/font) - a [Font](../../com.aspose.drawing/font) that is used to display text in the title bars of windows.
### getSmallCaptionFont() {#getSmallCaptionFont--}
```
public static Font getSmallCaptionFont()
```


Hämtar ett [Font](../../com.aspose.drawing/font) som används för att visa text i de små fönstrens titelrader, såsom verktygsfönster.

**Returns:**
[Font](../../com.aspose.drawing/font) - a [Font](../../com.aspose.drawing/font) that is used to display text in the title bars of small windows, such as tool windows.
### getMenuFont() {#getMenuFont--}
```
public static Font getMenuFont()
```


Hämtar ett [Font](../../com.aspose.drawing/font) som används för menyer.

**Returns:**
[Font](../../com.aspose.drawing/font) - a [Font](../../com.aspose.drawing/font) that is used for menus.
### getStatusFont() {#getStatusFont--}
```
public static Font getStatusFont()
```


Hämtar ett [Font](../../com.aspose.drawing/font) som används för att visa text i statusfältet.

**Returns:**
[Font](../../com.aspose.drawing/font) - a [Font](../../com.aspose.drawing/font) that is used to display text in the status bar.
### getMessageBoxFont() {#getMessageBoxFont--}
```
public static Font getMessageBoxFont()
```


Hämtar ett [Font](../../com.aspose.drawing/font) som används för meddelanderutor.

**Returns:**
[Font](../../com.aspose.drawing/font) - a [Font](../../com.aspose.drawing/font) that is used for message boxes.
### getIconTitleFont() {#getIconTitleFont--}
```
public static Font getIconTitleFont()
```


Hämtar ett [Font](../../com.aspose.drawing/font) som används för ikontitlar.

**Returns:**
[Font](../../com.aspose.drawing/font) - a [Font](../../com.aspose.drawing/font) that is used for icon titles.
### getDefaultFont() {#getDefaultFont--}
```
public static Font getDefaultFont()
```


Hämtar standardfonten som program kan använda för dialogrutor och formulär.

**Returns:**
[Font](../../com.aspose.drawing/font) - The default [Font](../../com.aspose.drawing/font) of the system. The value returned will vary depending on the user's operating system and the local culture setting of their system.
### getDefaultImageFont() {#getDefaultImageFont--}
```
public static Font getDefaultImageFont()
```


Hämtar standardfonten som program kan använda för dialogrutor och formulär.

**Returns:**
[Font](../../com.aspose.imaging/font) - The default [Font](../../com.aspose.drawing/font) of the system. The value returned will vary depending on the user's operating system and the local culture setting of their system.
### getDialogFont() {#getDialogFont--}
```
public static Font getDialogFont()
```


Hämtar ett font som program kan använda för dialogrutor och formulär.

**Returns:**
[Font](../../com.aspose.drawing/font) - A [Font](../../com.aspose.drawing/font) that can be used for dialog boxes and forms, depending on the operating system and local culture setting of the system.
### getFontByName(String systemFontName) {#getFontByName-java.lang.String-}
```
public static Font getFontByName(String systemFontName)
```


Returnerar ett font‑objekt som motsvarar det angivna systemfontnamnet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| systemFontName | java.lang.String | Namnet på systemfonten som du behöver ett font‑objekt för. |

**Returns:**
[Font](../../com.aspose.drawing/font) - A [Font](../../com.aspose.drawing/font) if the specified name matches a value in [SystemFonts](../../com.aspose.drawing/systemfonts); otherwise, null.
