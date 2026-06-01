---
title: ColorTranslator
second_title: Справочник API Aspose.Drawing для Java
description: Преобразует цвета в структуры GDI и из них.
type: docs
weight: 16
url: /ru/java/com.aspose.drawing/colortranslator/
---
**Inheritance:**
java.lang.Object
```
public final class ColorTranslator
```

Преобразует цвета в структуры GDI+ [Color](../../com.aspose.drawing/color) и из них. Этот класс не может быть наследован.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [ColorTranslator()](#ColorTranslator--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [fromHtml(String htmlColor)](#fromHtml-java.lang.String-) | Преобразует представление цвета в формате HTML в структуру GDI+ [Color](../../com.aspose.drawing/color). |
| [toHtml(Color c)](#toHtml-com.aspose.drawing.Color-) | Преобразует указанную структуру [Color](../../com.aspose.drawing/color) в строковое представление цвета HTML. |
| [fromWin32(int win32Color)](#fromWin32-int-) | Преобразует значение цвета Windows в структуру GDI+ [Color](../../com.aspose.drawing/color). |
| [fromOle(int oleColor)](#fromOle-int-) | Преобразует значение цвета OLE в структуру GDI+ [Color](../../com.aspose.drawing/color). |
| [toWin32(Color c)](#toWin32-com.aspose.drawing.Color-) | Преобразует структуру [Color](../../com.aspose.drawing/color) в представление цвета Win32. |
| [toOle(Color c)](#toOle-com.aspose.drawing.Color-) | Преобразует структуру [Color](../../com.aspose.drawing/color) в представление цвета OLE. |
### ColorTranslator() {#ColorTranslator--}
```
public ColorTranslator()
```


### fromHtml(String htmlColor) {#fromHtml-java.lang.String-}
```
public static Color fromHtml(String htmlColor)
```


Преобразует представление цвета в формате HTML в структуру GDI+ [Color](../../com.aspose.drawing/color).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| htmlColor | java.lang.String | Строковое представление цвета Html для преобразования. |

**Returns:**
[Color](../../com.aspose.drawing/color) - The [Color](../../com.aspose.drawing/color) structure that represents the translated HTML color or `Empty` if htmlColor is null.
### toHtml(Color c) {#toHtml-com.aspose.drawing.Color-}
```
public static String toHtml(Color c)
```


Преобразует указанную структуру [Color](../../com.aspose.drawing/color) в строковое представление цвета HTML.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| c | [Color](../../com.aspose.drawing/color) | Структура [Color](../../com.aspose.drawing/color) для перевода. |

**Returns:**
java.lang.String — строка, представляющая HTML‑цвет.
### fromWin32(int win32Color) {#fromWin32-int-}
```
public static Color fromWin32(int win32Color)
```


Преобразует значение цвета Windows в структуру GDI+ [Color](../../com.aspose.drawing/color).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| win32Color | int | Windows‑цвет для перевода. |

**Returns:**
[Color](../../com.aspose.drawing/color) - The [Color](../../com.aspose.drawing/color) structure that represents the translated Windows color.
### fromOle(int oleColor) {#fromOle-int-}
```
public static Color fromOle(int oleColor)
```


Преобразует значение цвета OLE в структуру GDI+ [Color](../../com.aspose.drawing/color).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| oleColor | int | OLE‑цвет для перевода. |

**Returns:**
[Color](../../com.aspose.drawing/color) - The [Color](../../com.aspose.drawing/color) structure that represents the translated OLE color.
### toWin32(Color c) {#toWin32-com.aspose.drawing.Color-}
```
public static int toWin32(Color c)
```


Преобразует структуру [Color](../../com.aspose.drawing/color) в представление цвета Win32.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| c | [Color](../../com.aspose.drawing/color) | Структура [Color](../../com.aspose.drawing/color) для преобразования. |

**Returns:**
int — значение, представляющее формат Win32 цвета.
### toOle(Color c) {#toOle-com.aspose.drawing.Color-}
```
public static int toOle(Color c)
```


Преобразует структуру [Color](../../com.aspose.drawing/color) в представление цвета OLE.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| c | [Color](../../com.aspose.drawing/color) | Структура [Color](../../com.aspose.drawing/color) для преобразования. |

**Returns:**
int — значение, представляющее формат OLE цвета.
