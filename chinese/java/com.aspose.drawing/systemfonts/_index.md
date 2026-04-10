---
title: SystemFonts
second_title: Aspose.Drawing for Java API 参考
description: 指定在 Windows 显示元素中用于显示文本的字体。
type: docs
weight: 51
url: /zh/java/com.aspose.drawing/systemfonts/
---
**Inheritance:**
java.lang.Object
```
public final class SystemFonts
```

指定在 Windows 显示元素中用于显示文本的字体。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getCaptionFont()](#getCaptionFont--) | 获取一个用于在窗口标题栏中显示文本的 [Font](../../com.aspose.drawing/font)。 |
| [getSmallCaptionFont()](#getSmallCaptionFont--) | 获取一个用于在小窗口（如工具窗口）的标题栏中显示文本的 [Font](../../com.aspose.drawing/font)。 |
| [getMenuFont()](#getMenuFont--) | 获取一个用于菜单的 [Font](../../com.aspose.drawing/font)。 |
| [getStatusFont()](#getStatusFont--) | 获取一个用于在状态栏中显示文本的 [Font](../../com.aspose.drawing/font)。 |
| [getMessageBoxFont()](#getMessageBoxFont--) | 获取一个用于消息框的 [Font](../../com.aspose.drawing/font)。 |
| [getIconTitleFont()](#getIconTitleFont--) | 获取一个用于图标标题的 [Font](../../com.aspose.drawing/font)。 |
| [getDefaultFont()](#getDefaultFont--) | 获取应用程序可用于对话框和窗体的默认字体。 |
| [getDefaultImageFont()](#getDefaultImageFont--) | 获取应用程序可用于对话框和窗体的默认字体。 |
| [getDialogFont()](#getDialogFont--) | 获取应用程序可用于对话框和窗体的字体。 |
| [getFontByName(String systemFontName)](#getFontByName-java.lang.String-) | 返回与指定系统字体名称对应的字体对象。 |
### getCaptionFont() {#getCaptionFont--}
```
public static Font getCaptionFont()
```


获取一个用于在窗口标题栏中显示文本的 [Font](../../com.aspose.drawing/font)。

**Returns:**
[Font](../../com.aspose.drawing/font) - a [Font](../../com.aspose.drawing/font) that is used to display text in the title bars of windows.
### getSmallCaptionFont() {#getSmallCaptionFont--}
```
public static Font getSmallCaptionFont()
```


获取一个用于在小窗口（如工具窗口）的标题栏中显示文本的 [Font](../../com.aspose.drawing/font)。

**Returns:**
[Font](../../com.aspose.drawing/font) - a [Font](../../com.aspose.drawing/font) that is used to display text in the title bars of small windows, such as tool windows.
### getMenuFont() {#getMenuFont--}
```
public static Font getMenuFont()
```


获取一个用于菜单的 [Font](../../com.aspose.drawing/font)。

**Returns:**
[Font](../../com.aspose.drawing/font) - a [Font](../../com.aspose.drawing/font) that is used for menus.
### getStatusFont() {#getStatusFont--}
```
public static Font getStatusFont()
```


获取一个用于在状态栏中显示文本的 [Font](../../com.aspose.drawing/font)。

**Returns:**
[Font](../../com.aspose.drawing/font) - a [Font](../../com.aspose.drawing/font) that is used to display text in the status bar.
### getMessageBoxFont() {#getMessageBoxFont--}
```
public static Font getMessageBoxFont()
```


获取一个用于消息框的 [Font](../../com.aspose.drawing/font)。

**Returns:**
[Font](../../com.aspose.drawing/font) - a [Font](../../com.aspose.drawing/font) that is used for message boxes.
### getIconTitleFont() {#getIconTitleFont--}
```
public static Font getIconTitleFont()
```


获取一个用于图标标题的 [Font](../../com.aspose.drawing/font)。

**Returns:**
[Font](../../com.aspose.drawing/font) - a [Font](../../com.aspose.drawing/font) that is used for icon titles.
### getDefaultFont() {#getDefaultFont--}
```
public static Font getDefaultFont()
```


获取应用程序可用于对话框和窗体的默认字体。

**Returns:**
[Font](../../com.aspose.drawing/font) - The default [Font](../../com.aspose.drawing/font) of the system. The value returned will vary depending on the user's operating system and the local culture setting of their system.
### getDefaultImageFont() {#getDefaultImageFont--}
```
public static Font getDefaultImageFont()
```


获取应用程序可用于对话框和窗体的默认字体。

**Returns:**
[Font](../../com.aspose.imaging/font) - The default [Font](../../com.aspose.drawing/font) of the system. The value returned will vary depending on the user's operating system and the local culture setting of their system.
### getDialogFont() {#getDialogFont--}
```
public static Font getDialogFont()
```


获取应用程序可用于对话框和窗体的字体。

**Returns:**
[Font](../../com.aspose.drawing/font) - A [Font](../../com.aspose.drawing/font) that can be used for dialog boxes and forms, depending on the operating system and local culture setting of the system.
### getFontByName(String systemFontName) {#getFontByName-java.lang.String-}
```
public static Font getFontByName(String systemFontName)
```


返回与指定系统字体名称对应的字体对象。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| systemFontName | java.lang.String | 需要获取字体对象的系统字体名称。 |

**Returns:**
[Font](../../com.aspose.drawing/font) - A [Font](../../com.aspose.drawing/font) if the specified name matches a value in [SystemFonts](../../com.aspose.drawing/systemfonts); otherwise, null.
