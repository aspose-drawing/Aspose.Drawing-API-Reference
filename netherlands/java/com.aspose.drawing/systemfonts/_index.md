---
title: SystemFonts
second_title: Aspose.Drawing voor Java API-referentie
description: Specificeert de lettertypen die worden gebruikt om tekst weer te geven in Windows‑schermonderdelen.
type: docs
weight: 51
url: /nl/java/com.aspose.drawing/systemfonts/
---
**Inheritance:**
java.lang.Object
```
public final class SystemFonts
```

Specificeert de lettertypen die worden gebruikt om tekst weer te geven in Windows‑schermonderdelen.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getCaptionFont()](#getCaptionFont--) | Haalt een [Font](../../com.aspose.drawing/font) op die wordt gebruikt om tekst weer te geven in de titelbalken van vensters. |
| [getSmallCaptionFont()](#getSmallCaptionFont--) | Haalt een [Font](../../com.aspose.drawing/font) op die wordt gebruikt om tekst weer te geven in de titelbalken van kleine vensters, zoals toolvensters. |
| [getMenuFont()](#getMenuFont--) | Haalt een [Font](../../com.aspose.drawing/font) op die wordt gebruikt voor menu's. |
| [getStatusFont()](#getStatusFont--) | Haalt een [Font](../../com.aspose.drawing/font) op die wordt gebruikt om tekst weer te geven in de statusbalk. |
| [getMessageBoxFont()](#getMessageBoxFont--) | Haalt een [Font](../../com.aspose.drawing/font) op die wordt gebruikt voor berichtvensters. |
| [getIconTitleFont()](#getIconTitleFont--) | Haalt een [Font](../../com.aspose.drawing/font) op die wordt gebruikt voor pictogramtitels. |
| [getDefaultFont()](#getDefaultFont--) | Haalt het standaardlettertype op dat toepassingen kunnen gebruiken voor dialoogvensters en formulieren. |
| [getDefaultImageFont()](#getDefaultImageFont--) | Haalt het standaardlettertype op dat toepassingen kunnen gebruiken voor dialoogvensters en formulieren. |
| [getDialogFont()](#getDialogFont--) | Haalt een lettertype op dat toepassingen kunnen gebruiken voor dialoogvensters en formulieren. |
| [getFontByName(String systemFontName)](#getFontByName-java.lang.String-) | Retourneert een lettertype‑object dat overeenkomt met de opgegeven systeemlettertype‑naam. |
### getCaptionFont() {#getCaptionFont--}
```
public static Font getCaptionFont()
```


Haalt een [Font](../../com.aspose.drawing/font) op die wordt gebruikt om tekst weer te geven in de titelbalken van vensters.

**Returns:**
[Font](../../com.aspose.drawing/font) - a [Font](../../com.aspose.drawing/font) that is used to display text in the title bars of windows.
### getSmallCaptionFont() {#getSmallCaptionFont--}
```
public static Font getSmallCaptionFont()
```


Haalt een [Font](../../com.aspose.drawing/font) op die wordt gebruikt om tekst weer te geven in de titelbalken van kleine vensters, zoals toolvensters.

**Returns:**
[Font](../../com.aspose.drawing/font) - a [Font](../../com.aspose.drawing/font) that is used to display text in the title bars of small windows, such as tool windows.
### getMenuFont() {#getMenuFont--}
```
public static Font getMenuFont()
```


Haalt een [Font](../../com.aspose.drawing/font) op die wordt gebruikt voor menu's.

**Returns:**
[Font](../../com.aspose.drawing/font) - a [Font](../../com.aspose.drawing/font) that is used for menus.
### getStatusFont() {#getStatusFont--}
```
public static Font getStatusFont()
```


Haalt een [Font](../../com.aspose.drawing/font) op die wordt gebruikt om tekst weer te geven in de statusbalk.

**Returns:**
[Font](../../com.aspose.drawing/font) - a [Font](../../com.aspose.drawing/font) that is used to display text in the status bar.
### getMessageBoxFont() {#getMessageBoxFont--}
```
public static Font getMessageBoxFont()
```


Haalt een [Font](../../com.aspose.drawing/font) op die wordt gebruikt voor berichtvensters.

**Returns:**
[Font](../../com.aspose.drawing/font) - a [Font](../../com.aspose.drawing/font) that is used for message boxes.
### getIconTitleFont() {#getIconTitleFont--}
```
public static Font getIconTitleFont()
```


Haalt een [Font](../../com.aspose.drawing/font) op die wordt gebruikt voor pictogramtitels.

**Returns:**
[Font](../../com.aspose.drawing/font) - a [Font](../../com.aspose.drawing/font) that is used for icon titles.
### getDefaultFont() {#getDefaultFont--}
```
public static Font getDefaultFont()
```


Haalt het standaardlettertype op dat toepassingen kunnen gebruiken voor dialoogvensters en formulieren.

**Returns:**
[Font](../../com.aspose.drawing/font) - The default [Font](../../com.aspose.drawing/font) of the system. The value returned will vary depending on the user's operating system and the local culture setting of their system.
### getDefaultImageFont() {#getDefaultImageFont--}
```
public static Font getDefaultImageFont()
```


Haalt het standaardlettertype op dat toepassingen kunnen gebruiken voor dialoogvensters en formulieren.

**Returns:**
[Font](../../com.aspose.imaging/font) - The default [Font](../../com.aspose.drawing/font) of the system. The value returned will vary depending on the user's operating system and the local culture setting of their system.
### getDialogFont() {#getDialogFont--}
```
public static Font getDialogFont()
```


Haalt een lettertype op dat toepassingen kunnen gebruiken voor dialoogvensters en formulieren.

**Returns:**
[Font](../../com.aspose.drawing/font) - A [Font](../../com.aspose.drawing/font) that can be used for dialog boxes and forms, depending on the operating system and local culture setting of the system.
### getFontByName(String systemFontName) {#getFontByName-java.lang.String-}
```
public static Font getFontByName(String systemFontName)
```


Retourneert een lettertype‑object dat overeenkomt met de opgegeven systeemlettertype‑naam.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| systemFontName | java.lang.String | De naam van het systeemlettertype waarvoor je een lettertype‑object nodig hebt. |

**Returns:**
[Font](../../com.aspose.drawing/font) - A [Font](../../com.aspose.drawing/font) if the specified name matches a value in [SystemFonts](../../com.aspose.drawing/systemfonts); otherwise, null.
