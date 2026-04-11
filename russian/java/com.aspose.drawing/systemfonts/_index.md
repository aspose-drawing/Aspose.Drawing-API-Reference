---
title: SystemFonts
second_title: Справочник API Aspose.Drawing для Java
description: Указывает шрифты, используемые для отображения текста в элементах отображения Windows.
type: docs
weight: 51
url: /ru/java/com.aspose.drawing/systemfonts/
---
**Inheritance:**
java.lang.Object
```
public final class SystemFonts
```

Указывает шрифты, используемые для отображения текста в элементах отображения Windows.
## Методы

| Метод | Описание |
| --- | --- |
| [getCaptionFont()](#getCaptionFont--) | Получает [Font](../../com.aspose.drawing/font), который используется для отображения текста в заголовках окон. |
| [getSmallCaptionFont()](#getSmallCaptionFont--) | Получает [Font](../../com.aspose.drawing/font), который используется для отображения текста в заголовках небольших окон, таких как панель инструментов. |
| [getMenuFont()](#getMenuFont--) | Получает [Font](../../com.aspose.drawing/font), который используется для меню. |
| [getStatusFont()](#getStatusFont--) | Получает [Font](../../com.aspose.drawing/font), который используется для отображения текста в строке состояния. |
| [getMessageBoxFont()](#getMessageBoxFont--) | Получает [Font](../../com.aspose.drawing/font), который используется для диалоговых окон сообщений. |
| [getIconTitleFont()](#getIconTitleFont--) | Получает [Font](../../com.aspose.drawing/font), который используется для заголовков значков. |
| [getDefaultFont()](#getDefaultFont--) | Получает шрифт по умолчанию, который приложения могут использовать для диалоговых окон и форм. |
| [getDefaultImageFont()](#getDefaultImageFont--) | Получает шрифт по умолчанию, который приложения могут использовать для диалоговых окон и форм. |
| [getDialogFont()](#getDialogFont--) | Получает шрифт, который приложения могут использовать для диалоговых окон и форм. |
| [getFontByName(String systemFontName)](#getFontByName-java.lang.String-) | Возвращает объект шрифта, соответствующий указанному системному имени шрифта. |
### getCaptionFont() {#getCaptionFont--}
```
public static Font getCaptionFont()
```


Получает [Font](../../com.aspose.drawing/font), который используется для отображения текста в заголовках окон.

**Returns:**
[Font](../../com.aspose.drawing/font) - a [Font](../../com.aspose.drawing/font) that is used to display text in the title bars of windows.
### getSmallCaptionFont() {#getSmallCaptionFont--}
```
public static Font getSmallCaptionFont()
```


Получает [Font](../../com.aspose.drawing/font), который используется для отображения текста в заголовках небольших окон, таких как панель инструментов.

**Returns:**
[Font](../../com.aspose.drawing/font) - a [Font](../../com.aspose.drawing/font) that is used to display text in the title bars of small windows, such as tool windows.
### getMenuFont() {#getMenuFont--}
```
public static Font getMenuFont()
```


Получает [Font](../../com.aspose.drawing/font), который используется для меню.

**Returns:**
[Font](../../com.aspose.drawing/font) - a [Font](../../com.aspose.drawing/font) that is used for menus.
### getStatusFont() {#getStatusFont--}
```
public static Font getStatusFont()
```


Получает [Font](../../com.aspose.drawing/font), который используется для отображения текста в строке состояния.

**Returns:**
[Font](../../com.aspose.drawing/font) - a [Font](../../com.aspose.drawing/font) that is used to display text in the status bar.
### getMessageBoxFont() {#getMessageBoxFont--}
```
public static Font getMessageBoxFont()
```


Получает [Font](../../com.aspose.drawing/font), который используется для диалоговых окон сообщений.

**Returns:**
[Font](../../com.aspose.drawing/font) - a [Font](../../com.aspose.drawing/font) that is used for message boxes.
### getIconTitleFont() {#getIconTitleFont--}
```
public static Font getIconTitleFont()
```


Получает [Font](../../com.aspose.drawing/font), который используется для заголовков значков.

**Returns:**
[Font](../../com.aspose.drawing/font) - a [Font](../../com.aspose.drawing/font) that is used for icon titles.
### getDefaultFont() {#getDefaultFont--}
```
public static Font getDefaultFont()
```


Получает шрифт по умолчанию, который приложения могут использовать для диалоговых окон и форм.

**Returns:**
[Font](../../com.aspose.drawing/font) - The default [Font](../../com.aspose.drawing/font) of the system. The value returned will vary depending on the user's operating system and the local culture setting of their system.
### getDefaultImageFont() {#getDefaultImageFont--}
```
public static Font getDefaultImageFont()
```


Получает шрифт по умолчанию, который приложения могут использовать для диалоговых окон и форм.

**Returns:**
[Font](../../com.aspose.imaging/font) - The default [Font](../../com.aspose.drawing/font) of the system. The value returned will vary depending on the user's operating system and the local culture setting of their system.
### getDialogFont() {#getDialogFont--}
```
public static Font getDialogFont()
```


Получает шрифт, который приложения могут использовать для диалоговых окон и форм.

**Returns:**
[Font](../../com.aspose.drawing/font) - A [Font](../../com.aspose.drawing/font) that can be used for dialog boxes and forms, depending on the operating system and local culture setting of the system.
### getFontByName(String systemFontName) {#getFontByName-java.lang.String-}
```
public static Font getFontByName(String systemFontName)
```


Возвращает объект шрифта, соответствующий указанному системному имени шрифта.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| systemFontName | java.lang.String | Имя системного шрифта, для которого требуется объект шрифта. |

**Returns:**
[Font](../../com.aspose.drawing/font) - A [Font](../../com.aspose.drawing/font) if the specified name matches a value in [SystemFonts](../../com.aspose.drawing/systemfonts); otherwise, null.
