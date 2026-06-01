---
title: Font
second_title: Справочник API Aspose.Drawing для Java
description: Определяет конкретный формат текста, включая гарнитуру шрифта, размер и атрибуты стиля.
type: docs
weight: 21
url: /ru/java/com.aspose.drawing/font/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public final class Font implements System.IDisposable
```

Определяет конкретный формат текста, включая гарнитуру шрифта, размер и атрибуты стиля. Этот класс не может быть наследован.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Font(Font prototype, int newStyle)](#Font-com.aspose.drawing.Font-int-) | Инициализирует новый экземпляр класса [Font](../../com.aspose.drawing/font), использующий указанный существующий [Font](../../com.aspose.drawing/font) и перечисление [FontStyle](../../com.aspose.drawing/fontstyle). |
| [Font(FontFamily family, float emSize)](#Font-com.aspose.drawing.FontFamily-float-) | Инициализирует новый экземпляр класса [Font](../../com.aspose.drawing/font). |
| [Font(FontFamily family, float emSize, int style)](#Font-com.aspose.drawing.FontFamily-float-int-) | Инициализирует новый экземпляр класса [Font](../../com.aspose.drawing/font), используя указанный размер и стиль.. |
| [Font(FontFamily family, float emSize, int style, int unit)](#Font-com.aspose.drawing.FontFamily-float-int-int-) | Инициализирует новый экземпляр класса [Font](../../com.aspose.drawing/font), используя указанные размер, стиль и единицу измерения. |
| [Font(FontFamily family, float emSize, int style, int unit, byte gdiCharSet)](#Font-com.aspose.drawing.FontFamily-float-int-int-byte-) | Инициализирует новый экземпляр класса [Font](../../com.aspose.drawing/font), используя указанные размер, стиль, единицу измерения и набор символов.. |
| [Font(FontFamily family, float emSize, int style, int unit, byte gdiCharSet, boolean gdiVerticalFont)](#Font-com.aspose.drawing.FontFamily-float-int-int-byte-boolean-) | Инициализирует новый экземпляр класса [Font](../../com.aspose.drawing/font), используя указанные размер, стиль, единицу измерения и набор символов.. |
| [Font(String familyName, float emSize)](#Font-java.lang.String-float-) | Инициализирует новый экземпляр класса [Font](../../com.aspose.drawing/font), используя указанный размер. |
| [Font(String familyName, float emSize, int style)](#Font-java.lang.String-float-int-) | Инициализирует новый экземпляр класса [Font](../../com.aspose.drawing/font), используя указанный размер и стиль. |
| [Font(String familyName, float emSize, int style, int unit)](#Font-java.lang.String-float-int-int-) | Инициализирует новый экземпляр класса [Font](../../com.aspose.drawing/font), используя указанные размер, стиль и единицу измерения. |
| [Font(String familyName, float emSize, int style, int unit, byte gdiCharSet)](#Font-java.lang.String-float-int-int-byte-) | Инициализирует новый экземпляр класса [Font](../../com.aspose.drawing/font), используя указанные размер, стиль, единицу измерения и набор символов. |
| [Font(String familyName, float emSize, int style, int unit, byte gdiCharSet, boolean gdiVerticalFont)](#Font-java.lang.String-float-int-int-byte-boolean-) | Инициализирует новый экземпляр класса [Font](../../com.aspose.drawing/font), используя указанные размер, стиль, единицу измерения и набор символов. |
## Методы

| Метод | Описание |
| --- | --- |
| [getFontFamily()](#getFontFamily--) | Возвращает `FontFamily`([.getFontFamily](../../null/\#getFontFamily)), связанную с этим [Font](../../com.aspose.drawing/font). |
| [getBold()](#getBold--) | Возвращает значение, указывающее, является ли этот [Font](../../com.aspose.drawing/font) полужирным. |
| [getGdiCharSet()](#getGdiCharSet--) | Возвращает байтовое значение, определяющее набор символов GDI, используемый этим [Font](../../com.aspose.drawing/font). |
| [getGdiVerticalFont()](#getGdiVerticalFont--) | Возвращает значение, указывающее, получен ли этот [Font](../../com.aspose.drawing/font) из вертикального шрифта GDI.. |
| [getItalic()](#getItalic--) | Возвращает значение, указывающее, является ли этот [Font](../../com.aspose.drawing/font) курсивным. |
| [getName()](#getName--) | Возвращает название гарнитуры этого [Font](../../com.aspose.drawing/font). |
| [getStrikeout()](#getStrikeout--) | Возвращает значение, указывающее, задаёт ли этот [Font](../../com.aspose.drawing/font) горизонтальную линию через шрифт. |
| [getUnderline()](#getUnderline--) | Возвращает значение, указывающее, подчёркнут ли этот [Font](../../com.aspose.drawing/font). |
| [getStyle()](#getStyle--) | Возвращает информацию о стиле этого [Font](../../com.aspose.drawing/font). |
| [getSize()](#getSize--) | Возвращает размер em этого [Font](../../com.aspose.drawing/font), измеренный в единицах, указанных свойством `Font.Unit`. |
| [getSizeInPoints()](#getSizeInPoints--) | Возвращает размер em в пунктах этого [Font](../../com.aspose.drawing/font). |
| [getUnit()](#getUnit--) | Возвращает единицу измерения этого [Font](../../com.aspose.drawing/font). |
| [getHeight_Rename_Namesake()](#getHeight-Rename-Namesake--) | Возвращает межстрочный интервал этого шрифта. |
| [isSystemFont()](#isSystemFont--) | Возвращает значение, указывающее, является ли шрифт членом [SystemFonts](../../com.aspose.drawing/systemfonts). |
| [getSystemFontName()](#getSystemFontName--) | Возвращает название системного шрифта, если свойство IsSystemFont возвращает true. |
| [getOriginalFontName()](#getOriginalFontName--) | Возвращает оригинальное название шрифта. |
| [deepClone()](#deepClone--) | Создаёт точную копию этого [Font](../../com.aspose.drawing/font). |
| [equals(Object obj)](#equals-java.lang.Object-) | Указывает, является ли указанный объект [Font](../../com.aspose.drawing/font) и имеет ли такие же значения свойств `FontFamily`([.getFontFamily](../../null/\#getFontFamily)), `M:GdiVerticalFont`, `M:GdiCharSet`, `M:Style`, `M:Size` и `M:Unit`, как этот [Font](../../com.aspose.drawing/font). |
| [hashCode()](#hashCode--) | Получает хеш-код для этого [Font](../../com.aspose.drawing/font). |
| [getHeight()](#getHeight--) | Возвращает межстрочный интервал в пикселях этого шрифта. |
| [getHeight(Graphics graphics)](#getHeight-com.aspose.drawing.Graphics-) | Возвращает межстрочный интервал в текущей единице измерения указанного [Graphics](../../com.aspose.drawing/graphics) для этого шрифта. |
| [getHeight(float dpi)](#getHeight-float-) | Возвращает высоту в пикселях этого [Font](../../com.aspose.drawing/font), когда он отрисовывается на устройстве с указанным вертикальным разрешением. |
| [dispose()](#dispose--) | Освобождает все ресурсы, используемые этим [Font](../../com.aspose.drawing/font). |
| [toString()](#toString--) | Возвращает человекочитаемое строковое представление этого [Font](../../com.aspose.drawing/font). |
| [getCharacterSet()](#getCharacterSet--) | Получает байтовое значение, указывающее набор символов, используемый этим `Font`. |
### Font(Font prototype, int newStyle) {#Font-com.aspose.drawing.Font-int-}
```
public Font(Font prototype, int newStyle)
```


Инициализирует новый экземпляр класса [Font](../../com.aspose.drawing/font), использующий указанный существующий [Font](../../com.aspose.drawing/font) и перечисление [FontStyle](../../com.aspose.drawing/fontstyle).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| prototype | [Font](../../com.aspose.drawing/font) | Существующий [Font](../../com.aspose.drawing/font), из которого будет создан новый [Font](../../com.aspose.drawing/font). |
| newStyle | int | Стиль [FontStyle](../../com.aspose.drawing/fontstyle), который следует применить к новому [Font](../../com.aspose.drawing/font). Несколько значений перечисления [FontStyle](../../com.aspose.drawing/fontstyle) могут быть объединены оператором OR. |

### Font(FontFamily family, float emSize) {#Font-com.aspose.drawing.FontFamily-float-}
```
public Font(FontFamily family, float emSize)
```


Инициализирует новый экземпляр класса [Font](../../com.aspose.drawing/font).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| family | [FontFamily](../../com.aspose.drawing/fontfamily) | `FontFamily`([.getFontFamily](../../null/\#getFontFamily)) нового [Font](../../com.aspose.drawing/font). |
| emSize | float | em-size, в пунктах, нового шрифта. |

### Font(FontFamily family, float emSize, int style) {#Font-com.aspose.drawing.FontFamily-float-int-}
```
public Font(FontFamily family, float emSize, int style)
```


Инициализирует новый экземпляр класса [Font](../../com.aspose.drawing/font), используя указанный размер и стиль..

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| family | [FontFamily](../../com.aspose.drawing/fontfamily) | `FontFamily`([.getFontFamily](../../null/\#getFontFamily)) нового [Font](../../com.aspose.drawing/font). |
| emSize | float | em-size, в пунктах, нового шрифта. |
| style | int | Стиль [FontStyle](../../com.aspose.drawing/fontstyle) нового шрифта. |

### Font(FontFamily family, float emSize, int style, int unit) {#Font-com.aspose.drawing.FontFamily-float-int-int-}
```
public Font(FontFamily family, float emSize, int style, int unit)
```


Инициализирует новый экземпляр класса [Font](../../com.aspose.drawing/font), используя указанные размер, стиль и единицу измерения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| family | [FontFamily](../../com.aspose.drawing/fontfamily) | `FontFamily`([.getFontFamily](../../null/\#getFontFamily)) нового [Font](../../com.aspose.drawing/font). |
| emSize | float | em-size нового шрифта в единицах, указанных параметром `unit`. |
| style | int | Стиль [FontStyle](../../com.aspose.drawing/fontstyle) нового шрифта. |
| unit | int | Единица измерения [GraphicsUnit](../../com.aspose.drawing/graphicsunit) нового шрифта. |

### Font(FontFamily family, float emSize, int style, int unit, byte gdiCharSet) {#Font-com.aspose.drawing.FontFamily-float-int-int-byte-}
```
public Font(FontFamily family, float emSize, int style, int unit, byte gdiCharSet)
```


Инициализирует новый экземпляр класса [Font](../../com.aspose.drawing/font), используя указанные размер, стиль, единицу измерения и набор символов..

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| family | [FontFamily](../../com.aspose.drawing/fontfamily) | `FontFamily`([.getFontFamily](../../null/\#getFontFamily)) нового [Font](../../com.aspose.drawing/font). |
| emSize | float | em-size нового шрифта в единицах, указанных параметром `unit`. |
| style | int | Стиль [FontStyle](../../com.aspose.drawing/fontstyle) нового шрифта. |
| unit | int | Единица измерения [GraphicsUnit](../../com.aspose.drawing/graphicsunit) нового шрифта. |
| gdiCharSet | byte | Набор символов GDI, используемый для нового шрифта. |

### Font(FontFamily family, float emSize, int style, int unit, byte gdiCharSet, boolean gdiVerticalFont) {#Font-com.aspose.drawing.FontFamily-float-int-int-byte-boolean-}
```
public Font(FontFamily family, float emSize, int style, int unit, byte gdiCharSet, boolean gdiVerticalFont)
```


Инициализирует новый экземпляр класса [Font](../../com.aspose.drawing/font), используя указанные размер, стиль, единицу измерения и набор символов..

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| family | [FontFamily](../../com.aspose.drawing/fontfamily) | `FontFamily`([.getFontFamily](../../null/\#getFontFamily)) нового [Font](../../com.aspose.drawing/font). |
| emSize | float | em-size нового шрифта в единицах, указанных параметром `unit`. |
| style | int | Стиль [FontStyle](../../com.aspose.drawing/fontstyle) нового шрифта. |
| unit | int | Единица измерения [GraphicsUnit](../../com.aspose.drawing/graphicsunit) нового шрифта. |
| gdiCharSet | byte | Набор символов GDI, используемый для нового шрифта. |
| gdiVerticalFont | boolean | Булево значение, указывающее, является ли новый шрифт производным от вертикального шрифта GDI. |

### Font(String familyName, float emSize) {#Font-java.lang.String-float-}
```
public Font(String familyName, float emSize)
```


Инициализирует новый экземпляр класса [Font](../../com.aspose.drawing/font), используя указанный размер.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| familyName | java.lang.String | Строковое представление FontFamily нового [Font](../../com.aspose.drawing/font). |
| emSize | float | em-size, в пунктах, нового шрифта. |

### Font(String familyName, float emSize, int style) {#Font-java.lang.String-float-int-}
```
public Font(String familyName, float emSize, int style)
```


Инициализирует новый экземпляр класса [Font](../../com.aspose.drawing/font), используя указанный размер и стиль.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| familyName | java.lang.String | Строковое представление FontFamily нового [Font](../../com.aspose.drawing/font). |
| emSize | float | em-size, в пунктах, нового шрифта. |
| style | int | Стиль [FontStyle](../../com.aspose.drawing/fontstyle) нового шрифта. |

### Font(String familyName, float emSize, int style, int unit) {#Font-java.lang.String-float-int-int-}
```
public Font(String familyName, float emSize, int style, int unit)
```


Инициализирует новый экземпляр класса [Font](../../com.aspose.drawing/font), используя указанные размер, стиль и единицу измерения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| familyName | java.lang.String | Строковое представление `FontFamily`([.getFontFamily](../../null/\#getFontFamily)) нового [Font](../../com.aspose.drawing/font). |
| emSize | float | em-size нового шрифта в единицах, указанных параметром `unit`. |
| style | int | Стиль [FontStyle](../../com.aspose.drawing/fontstyle) нового шрифта. |
| unit | int | Единица измерения [GraphicsUnit](../../com.aspose.drawing/graphicsunit) нового шрифта. |

### Font(String familyName, float emSize, int style, int unit, byte gdiCharSet) {#Font-java.lang.String-float-int-int-byte-}
```
public Font(String familyName, float emSize, int style, int unit, byte gdiCharSet)
```


Инициализирует новый экземпляр класса [Font](../../com.aspose.drawing/font), используя указанные размер, стиль, единицу измерения и набор символов.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| familyName | java.lang.String | Строковое представление FontFamily нового [Font](../../com.aspose.drawing/font). |
| emSize | float | em-size нового шрифта в единицах, указанных параметром `unit`. |
| style | int | Стиль [FontStyle](../../com.aspose.drawing/fontstyle) нового шрифта. |
| unit | int | Единица измерения [GraphicsUnit](../../com.aspose.drawing/graphicsunit) нового шрифта. |
| gdiCharSet | byte | Байт, указывающий набор символов GDI, используемый для этого шрифта. |

### Font(String familyName, float emSize, int style, int unit, byte gdiCharSet, boolean gdiVerticalFont) {#Font-java.lang.String-float-int-int-byte-boolean-}
```
public Font(String familyName, float emSize, int style, int unit, byte gdiCharSet, boolean gdiVerticalFont)
```


Инициализирует новый экземпляр класса [Font](../../com.aspose.drawing/font), используя указанные размер, стиль, единицу измерения и набор символов.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| familyName | java.lang.String | Строковое представление FontFamily нового [Font](../../com.aspose.drawing/font). |
| emSize | float | em-size нового шрифта в единицах, указанных параметром `unit`. |
| style | int | Стиль [FontStyle](../../com.aspose.drawing/fontstyle) нового шрифта. |
| unit | int | Единица измерения [GraphicsUnit](../../com.aspose.drawing/graphicsunit) нового шрифта. |
| gdiCharSet | byte | Байт, указывающий набор символов GDI, используемый для этого шрифта. |
| gdiVerticalFont | boolean | Булево значение, указывающее, является ли новый [Font](../../com.aspose.drawing/font) производным от вертикального шрифта GDI. |

### getFontFamily() {#getFontFamily--}
```
public FontFamily getFontFamily()
```


Возвращает `FontFamily`([.getFontFamily](../../null/\#getFontFamily)), связанную с этим [Font](../../com.aspose.drawing/font).

**Returns:**
[FontFamily](../../com.aspose.drawing/fontfamily) - The `FontFamily`([.getFontFamily](../../null/\#getFontFamily)) associated with this [Font](../../com.aspose.drawing/font).
### getBold() {#getBold--}
```
public boolean getBold()
```


Возвращает значение, указывающее, является ли этот [Font](../../com.aspose.drawing/font) полужирным.

**Returns:**
boolean - значение, указывающее, является ли этот [Font](../../com.aspose.drawing/font) полужирным.
### getGdiCharSet() {#getGdiCharSet--}
```
public byte getGdiCharSet()
```


Возвращает байтовое значение, определяющее набор символов GDI, используемый этим [Font](../../com.aspose.drawing/font).

**Returns:**
byte - байтовое значение, указывающее набор символов GDI, который использует этот [Font](../../com.aspose.drawing/font).
### getGdiVerticalFont() {#getGdiVerticalFont--}
```
public boolean getGdiVerticalFont()
```


Возвращает значение, указывающее, получен ли этот [Font](../../com.aspose.drawing/font) из вертикального шрифта GDI..

Значение: `true`, если этот [Font](../../com.aspose.drawing/font) получен из вертикального шрифта GDI; в противном случае `false`.

**Returns:**
boolean - значение, указывающее, получен ли этот [Font](../../com.aspose.drawing/font) из вертикального шрифта GDI.
### getItalic() {#getItalic--}
```
public boolean getItalic()
```


Возвращает значение, указывающее, является ли этот [Font](../../com.aspose.drawing/font) курсивным.

**Returns:**
boolean - значение, указывающее, является ли этот [Font](../../com.aspose.drawing/font) курсивным.
### getName() {#getName--}
```
public String getName()
```


Возвращает название гарнитуры этого [Font](../../com.aspose.drawing/font).

**Returns:**
java.lang.String - название гарнитуры этого [Font](../../com.aspose.drawing/font).
### getStrikeout() {#getStrikeout--}
```
public boolean getStrikeout()
```


Возвращает значение, указывающее, задаёт ли этот [Font](../../com.aspose.drawing/font) горизонтальную линию через шрифт.

**Returns:**
boolean - значение, указывающее, задает ли этот [Font](../../com.aspose.drawing/font) горизонтальную линию через шрифт.
### getUnderline() {#getUnderline--}
```
public boolean getUnderline()
```


Возвращает значение, указывающее, подчёркнут ли этот [Font](../../com.aspose.drawing/font).

**Returns:**
boolean - значение, указывающее, подчёркнут ли этот [Font](../../com.aspose.drawing/font).
### getStyle() {#getStyle--}
```
public int getStyle()
```


Возвращает информацию о стиле этого [Font](../../com.aspose.drawing/font).

**Returns:**
int - информация о стиле этого [Font](../../com.aspose.drawing/font).
### getSize() {#getSize--}
```
public float getSize()
```


Возвращает размер em этого [Font](../../com.aspose.drawing/font), измеренный в единицах, указанных свойством `Font.Unit`.

**Returns:**
float - размер em этого [Font](../../com.aspose.drawing/font), измеренный в единицах, указанных в \{@code Font.
### getSizeInPoints() {#getSizeInPoints--}
```
public float getSizeInPoints()
```


Возвращает размер em в пунктах этого [Font](../../com.aspose.drawing/font).

**Returns:**
float - размер em в пунктах этого [Font](../../com.aspose.drawing/font).
### getUnit() {#getUnit--}
```
public int getUnit()
```


Возвращает единицу измерения этого [Font](../../com.aspose.drawing/font).

**Returns:**
int - единица измерения этого [Font](../../com.aspose.drawing/font).
### getHeight_Rename_Namesake() {#getHeight-Rename-Namesake--}
```
public int getHeight_Rename_Namesake()
```


Возвращает межстрочный интервал этого шрифта.

Значение: межстрочный интервал в пикселях этого шрифта.

**Returns:**
int - межстрочный интервал этого шрифта.
### isSystemFont() {#isSystemFont--}
```
public boolean isSystemFont()
```


Возвращает значение, указывающее, является ли шрифт членом [SystemFonts](../../com.aspose.drawing/systemfonts).

Значение: `true`, если шрифт является членом [SystemFonts](../../com.aspose.drawing/systemfonts); в противном случае `false`.

**Returns:**
boolean - значение, указывающее, является ли шрифт членом [SystemFonts](../../com.aspose.drawing/systemfonts).
### getSystemFontName() {#getSystemFontName--}
```
public String getSystemFontName()
```


Возвращает название системного шрифта, если свойство IsSystemFont возвращает true.

Значение: имя системного шрифта, если IsSystemFont возвращает true; в противном случае пустая строка (\"\").

**Returns:**
java.lang.String - имя системного шрифта, если свойство IsSystemFont возвращает true.
### getOriginalFontName() {#getOriginalFontName--}
```
public String getOriginalFontName()
```


Возвращает оригинальное название шрифта.

Значение: строка, представляющая имя изначально указанного шрифта.

**Returns:**
java.lang.String - имя изначально указанного шрифта.
### deepClone() {#deepClone--}
```
public Font deepClone()
```


Создаёт точную копию этого [Font](../../com.aspose.drawing/font).

**Returns:**
[Font](../../com.aspose.drawing/font) - The [Font](../../com.aspose.drawing/font) this method creates, cast as an Object.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Указывает, является ли указанный объект [Font](../../com.aspose.drawing/font) и имеет ли такие же значения свойств `FontFamily`([.getFontFamily](../../null/\#getFontFamily)), `M:GdiVerticalFont`, `M:GdiCharSet`, `M:Style`, `M:Size` и `M:Unit`, как этот [Font](../../com.aspose.drawing/font).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | java.lang.Object | Объект для тестирования. |

**Returns:**
boolean - `true`, если параметр obj является [Font](../../com.aspose.drawing/font) и имеет такие же значения свойств `FontFamily`([.getFontFamily](../../null/\#getFontFamily)), `M:GdiVerticalFont`, `M:GdiCharSet`, `M:Style`, `M:Size` и `M:Unit`, как у этого [Font](../../com.aspose.drawing/font); в противном случае `false`.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Получает хеш-код для этого [Font](../../com.aspose.drawing/font).

**Returns:**
int - хеш-код этого [Font](../../com.aspose.drawing/font).
### getHeight() {#getHeight--}
```
public int getHeight()
```


Возвращает межстрочный интервал в пикселях этого шрифта.

**Returns:**
int - межстрочный интервал в пикселях этого шрифта.
### getHeight(Graphics graphics) {#getHeight-com.aspose.drawing.Graphics-}
```
public float getHeight(Graphics graphics)
```


Возвращает межстрочный интервал в текущей единице измерения указанного [Graphics](../../com.aspose.drawing/graphics) для этого шрифта.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| graphics | [Graphics](../../com.aspose.drawing/graphics) | Объект [Graphics](../../com.aspose.drawing/graphics), содержащий вертикальное разрешение дисплейного устройства в точках на дюйм, а также настройки единицы страницы и масштаба страницы. |

**Returns:**
float - межстрочный интервал в пикселях этого шрифта.
### getHeight(float dpi) {#getHeight-float-}
```
public int getHeight(float dpi)
```


Возвращает высоту в пикселях этого [Font](../../com.aspose.drawing/font), когда он отрисовывается на устройстве с указанным вертикальным разрешением.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| dpi | float | Вертикальное разрешение в точках на дюйм, используемое для расчёта высоты шрифта. |

**Returns:**
int - Высота в пикселях этого [Font](../../com.aspose.drawing/font).
### dispose() {#dispose--}
```
public void dispose()
```


Освобождает все ресурсы, используемые этим [Font](../../com.aspose.drawing/font).

### toString() {#toString--}
```
public String toString()
```


Возвращает человекочитаемое строковое представление этого [Font](../../com.aspose.drawing/font).

**Returns:**
java.lang.String - Строка, представляющая этот [Font](../../com.aspose.drawing/font).
### getCharacterSet() {#getCharacterSet--}
```
public int getCharacterSet()
```


Получает байтовое значение, указывающее набор символов, используемый этим `Font`.

**Returns:**
int - Набор символов, который использует этот `Font`.
