---
title: SystemFonts
second_title: Referencia de la API de Aspose.Drawing para Java
description: Especifica las fuentes utilizadas para mostrar texto en los elementos de pantalla de Windows.
type: docs
weight: 51
url: /es/java/com.aspose.drawing/systemfonts/
---
**Inheritance:**
java.lang.Object
```
public final class SystemFonts
```

Especifica las fuentes utilizadas para mostrar texto en los elementos de pantalla de Windows.
## Métodos

| Método | Descripción |
| --- | --- |
| [getCaptionFont()](#getCaptionFont--) | Obtiene un [Font](../../com.aspose.drawing/font) que se usa para mostrar texto en las barras de título de las ventanas. |
| [getSmallCaptionFont()](#getSmallCaptionFont--) | Obtiene un [Font](../../com.aspose.drawing/font) que se usa para mostrar texto en las barras de título de ventanas pequeñas, como ventanas de herramientas. |
| [getMenuFont()](#getMenuFont--) | Obtiene un [Font](../../com.aspose.drawing/font) que se usa para menús. |
| [getStatusFont()](#getStatusFont--) | Obtiene un [Font](../../com.aspose.drawing/font) que se usa para mostrar texto en la barra de estado. |
| [getMessageBoxFont()](#getMessageBoxFont--) | Obtiene un [Font](../../com.aspose.drawing/font) que se usa para cuadros de mensaje. |
| [getIconTitleFont()](#getIconTitleFont--) | Obtiene un [Font](../../com.aspose.drawing/font) que se usa para títulos de iconos. |
| [getDefaultFont()](#getDefaultFont--) | Obtiene la fuente predeterminada que las aplicaciones pueden usar para cuadros de diálogo y formularios. |
| [getDefaultImageFont()](#getDefaultImageFont--) | Obtiene la fuente predeterminada que las aplicaciones pueden usar para cuadros de diálogo y formularios. |
| [getDialogFont()](#getDialogFont--) | Obtiene una fuente que las aplicaciones pueden usar para cuadros de diálogo y formularios. |
| [getFontByName(String systemFontName)](#getFontByName-java.lang.String-) | Devuelve un objeto de fuente que corresponde al nombre de fuente del sistema especificado. |
### getCaptionFont() {#getCaptionFont--}
```
public static Font getCaptionFont()
```


Obtiene un [Font](../../com.aspose.drawing/font) que se usa para mostrar texto en las barras de título de las ventanas.

**Returns:**
[Font](../../com.aspose.drawing/font) - a [Font](../../com.aspose.drawing/font) that is used to display text in the title bars of windows.
### getSmallCaptionFont() {#getSmallCaptionFont--}
```
public static Font getSmallCaptionFont()
```


Obtiene un [Font](../../com.aspose.drawing/font) que se usa para mostrar texto en las barras de título de ventanas pequeñas, como ventanas de herramientas.

**Returns:**
[Font](../../com.aspose.drawing/font) - a [Font](../../com.aspose.drawing/font) that is used to display text in the title bars of small windows, such as tool windows.
### getMenuFont() {#getMenuFont--}
```
public static Font getMenuFont()
```


Obtiene un [Font](../../com.aspose.drawing/font) que se usa para menús.

**Returns:**
[Font](../../com.aspose.drawing/font) - a [Font](../../com.aspose.drawing/font) that is used for menus.
### getStatusFont() {#getStatusFont--}
```
public static Font getStatusFont()
```


Obtiene un [Font](../../com.aspose.drawing/font) que se usa para mostrar texto en la barra de estado.

**Returns:**
[Font](../../com.aspose.drawing/font) - a [Font](../../com.aspose.drawing/font) that is used to display text in the status bar.
### getMessageBoxFont() {#getMessageBoxFont--}
```
public static Font getMessageBoxFont()
```


Obtiene un [Font](../../com.aspose.drawing/font) que se usa para cuadros de mensaje.

**Returns:**
[Font](../../com.aspose.drawing/font) - a [Font](../../com.aspose.drawing/font) that is used for message boxes.
### getIconTitleFont() {#getIconTitleFont--}
```
public static Font getIconTitleFont()
```


Obtiene un [Font](../../com.aspose.drawing/font) que se usa para títulos de iconos.

**Returns:**
[Font](../../com.aspose.drawing/font) - a [Font](../../com.aspose.drawing/font) that is used for icon titles.
### getDefaultFont() {#getDefaultFont--}
```
public static Font getDefaultFont()
```


Obtiene la fuente predeterminada que las aplicaciones pueden usar para cuadros de diálogo y formularios.

**Returns:**
[Font](../../com.aspose.drawing/font) - The default [Font](../../com.aspose.drawing/font) of the system. The value returned will vary depending on the user's operating system and the local culture setting of their system.
### getDefaultImageFont() {#getDefaultImageFont--}
```
public static Font getDefaultImageFont()
```


Obtiene la fuente predeterminada que las aplicaciones pueden usar para cuadros de diálogo y formularios.

**Returns:**
[Font](../../com.aspose.imaging/font) - The default [Font](../../com.aspose.drawing/font) of the system. The value returned will vary depending on the user's operating system and the local culture setting of their system.
### getDialogFont() {#getDialogFont--}
```
public static Font getDialogFont()
```


Obtiene una fuente que las aplicaciones pueden usar para cuadros de diálogo y formularios.

**Returns:**
[Font](../../com.aspose.drawing/font) - A [Font](../../com.aspose.drawing/font) that can be used for dialog boxes and forms, depending on the operating system and local culture setting of the system.
### getFontByName(String systemFontName) {#getFontByName-java.lang.String-}
```
public static Font getFontByName(String systemFontName)
```


Devuelve un objeto de fuente que corresponde al nombre de fuente del sistema especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| systemFontName | java.lang.String | El nombre de la fuente del sistema para la que necesita un objeto de fuente. |

**Returns:**
[Font](../../com.aspose.drawing/font) - A [Font](../../com.aspose.drawing/font) if the specified name matches a value in [SystemFonts](../../com.aspose.drawing/systemfonts); otherwise, null.
