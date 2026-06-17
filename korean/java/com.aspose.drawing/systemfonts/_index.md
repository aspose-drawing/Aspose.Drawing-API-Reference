---
title: 시스템 글꼴
second_title: Aspose.Drawing for Java API 참조
description: Windows 디스플레이 요소에 텍스트를 표시하는 데 사용되는 글꼴을 지정합니다.
type: docs
weight: 51
url: /ko/java/com.aspose.drawing/systemfonts/
---
**Inheritance:**
java.lang.Object
```
public final class SystemFonts
```

Windows 디스플레이 요소에 텍스트를 표시하는 데 사용되는 글꼴을 지정합니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getCaptionFont()](#getCaptionFont--) | 윈도우의 제목 표시줄에 텍스트를 표시하는 데 사용되는 [Font](../../com.aspose.drawing/font)을 가져옵니다. |
| [getSmallCaptionFont()](#getSmallCaptionFont--) | 도구 창과 같은 작은 창의 제목 표시줄에 텍스트를 표시하는 데 사용되는 [Font](../../com.aspose.drawing/font)을 가져옵니다. |
| [getMenuFont()](#getMenuFont--) | 메뉴에 사용되는 [Font](../../com.aspose.drawing/font)을 가져옵니다. |
| [getStatusFont()](#getStatusFont--) | 상태 표시줄에 텍스트를 표시하는 데 사용되는 [Font](../../com.aspose.drawing/font)을 가져옵니다. |
| [getMessageBoxFont()](#getMessageBoxFont--) | 메시지 상자에 사용되는 [Font](../../com.aspose.drawing/font)을 가져옵니다. |
| [getIconTitleFont()](#getIconTitleFont--) | 아이콘 제목에 사용되는 [Font](../../com.aspose.drawing/font)을 가져옵니다. |
| [getDefaultFont()](#getDefaultFont--) | 응용 프로그램이 대화 상자와 폼에 사용할 수 있는 기본 글꼴을 가져옵니다. |
| [getDefaultImageFont()](#getDefaultImageFont--) | 응용 프로그램이 대화 상자와 폼에 사용할 수 있는 기본 글꼴을 가져옵니다. |
| [getDialogFont()](#getDialogFont--) | 응용 프로그램이 대화 상자와 폼에 사용할 수 있는 글꼴을 가져옵니다. |
| [getFontByName(String systemFontName)](#getFontByName-java.lang.String-) | 지정된 시스템 글꼴 이름에 해당하는 글꼴 객체를 반환합니다. |
### getCaptionFont() {#getCaptionFont--}
```
public static Font getCaptionFont()
```


윈도우의 제목 표시줄에 텍스트를 표시하는 데 사용되는 [Font](../../com.aspose.drawing/font)을 가져옵니다.

**Returns:**
[Font](../../com.aspose.drawing/font) - a [Font](../../com.aspose.drawing/font) that is used to display text in the title bars of windows.
### getSmallCaptionFont() {#getSmallCaptionFont--}
```
public static Font getSmallCaptionFont()
```


도구 창과 같은 작은 창의 제목 표시줄에 텍스트를 표시하는 데 사용되는 [Font](../../com.aspose.drawing/font)을 가져옵니다.

**Returns:**
[Font](../../com.aspose.drawing/font) - a [Font](../../com.aspose.drawing/font) that is used to display text in the title bars of small windows, such as tool windows.
### getMenuFont() {#getMenuFont--}
```
public static Font getMenuFont()
```


메뉴에 사용되는 [Font](../../com.aspose.drawing/font)을 가져옵니다.

**Returns:**
[Font](../../com.aspose.drawing/font) - a [Font](../../com.aspose.drawing/font) that is used for menus.
### getStatusFont() {#getStatusFont--}
```
public static Font getStatusFont()
```


상태 표시줄에 텍스트를 표시하는 데 사용되는 [Font](../../com.aspose.drawing/font)을 가져옵니다.

**Returns:**
[Font](../../com.aspose.drawing/font) - a [Font](../../com.aspose.drawing/font) that is used to display text in the status bar.
### getMessageBoxFont() {#getMessageBoxFont--}
```
public static Font getMessageBoxFont()
```


메시지 상자에 사용되는 [Font](../../com.aspose.drawing/font)을 가져옵니다.

**Returns:**
[Font](../../com.aspose.drawing/font) - a [Font](../../com.aspose.drawing/font) that is used for message boxes.
### getIconTitleFont() {#getIconTitleFont--}
```
public static Font getIconTitleFont()
```


아이콘 제목에 사용되는 [Font](../../com.aspose.drawing/font)을 가져옵니다.

**Returns:**
[Font](../../com.aspose.drawing/font) - a [Font](../../com.aspose.drawing/font) that is used for icon titles.
### getDefaultFont() {#getDefaultFont--}
```
public static Font getDefaultFont()
```


응용 프로그램이 대화 상자와 폼에 사용할 수 있는 기본 글꼴을 가져옵니다.

**Returns:**
[Font](../../com.aspose.drawing/font) - The default [Font](../../com.aspose.drawing/font) of the system. The value returned will vary depending on the user's operating system and the local culture setting of their system.
### getDefaultImageFont() {#getDefaultImageFont--}
```
public static Font getDefaultImageFont()
```


응용 프로그램이 대화 상자와 폼에 사용할 수 있는 기본 글꼴을 가져옵니다.

**Returns:**
[Font](../../com.aspose.imaging/font) - The default [Font](../../com.aspose.drawing/font) of the system. The value returned will vary depending on the user's operating system and the local culture setting of their system.
### getDialogFont() {#getDialogFont--}
```
public static Font getDialogFont()
```


응용 프로그램이 대화 상자와 폼에 사용할 수 있는 글꼴을 가져옵니다.

**Returns:**
[Font](../../com.aspose.drawing/font) - A [Font](../../com.aspose.drawing/font) that can be used for dialog boxes and forms, depending on the operating system and local culture setting of the system.
### getFontByName(String systemFontName) {#getFontByName-java.lang.String-}
```
public static Font getFontByName(String systemFontName)
```


지정된 시스템 글꼴 이름에 해당하는 글꼴 객체를 반환합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| systemFontName | java.lang.String | 글꼴 객체가 필요한 시스템 글꼴의 이름입니다. |

**Returns:**
[Font](../../com.aspose.drawing/font) - A [Font](../../com.aspose.drawing/font) if the specified name matches a value in [SystemFonts](../../com.aspose.drawing/systemfonts); otherwise, null.
