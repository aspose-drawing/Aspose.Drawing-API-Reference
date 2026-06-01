---
title: StringFormat
second_title: Справочник API Aspose.Drawing для Java
description: Инкапсулирует информацию о расположении текста, такую как ориентация выравнивания и отображение табуляций, а также манипуляции отображением, такие как вставка многоточия, замена национальных цифр и функции OpenType.
type: docs
weight: 47
url: /ru/java/com.aspose.drawing/stringformat/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public final class StringFormat implements System.IDisposable
```

Инкапсулирует информацию о размещении текста (например, выравнивание, ориентацию и табуляцию), манипуляции отображением (например, вставку многоточия и замену национальных цифр) и функции OpenType. Этот класс не может быть наследован.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [StringFormat()](#StringFormat--) | Инициализирует новый экземпляр класса [StringFormat](../../com.aspose.drawing/stringformat). |
| [StringFormat(StringFormat format)](#StringFormat-com.aspose.drawing.StringFormat-) | Инициализирует новый экземпляр класса [StringFormat](../../com.aspose.drawing/stringformat) из указанного существующего объекта [StringFormat](../../com.aspose.drawing/stringformat). |
| [StringFormat(int options, int language)](#StringFormat-int-int-) | Инициализирует новый экземпляр класса [StringFormat](../../com.aspose.drawing/stringformat) с указанным перечислением [StringFormatFlags](../../com.aspose.drawing/stringformatflags) и языком. |
| [StringFormat(int options)](#StringFormat-int-) | Инициализирует новый экземпляр класса [StringFormat](../../com.aspose.drawing/stringformat) с указанным перечислением [StringFormatFlags](../../com.aspose.drawing/stringformatflags). |
## Методы

| Метод | Описание |
| --- | --- |
| [setDigitSubstitutionLanguage(int value)](#setDigitSubstitutionLanguage-int-) |  |
| [setDigitSubstitutionMethod(int value)](#setDigitSubstitutionMethod-int-) |  |
| [getFirstTabOffset()](#getFirstTabOffset--) |  |
| [getGenericDefault()](#getGenericDefault--) | Получает универсальный объект [StringFormat](../../com.aspose.drawing/stringformat) по умолчанию. |
| [getGenericTypographic()](#getGenericTypographic--) | Получает универсальный типографический объект [StringFormat](../../com.aspose.drawing/stringformat). |
| [getFormatFlags()](#getFormatFlags--) | Получает или задает перечисление [StringFormatFlags](../../com.aspose.drawing/stringformatflags), содержащее информацию о форматировании. |
| [setFormatFlags(int value)](#setFormatFlags-int-) | Получает или задает перечисление [StringFormatFlags](../../com.aspose.drawing/stringformatflags), содержащее информацию о форматировании. |
| [getAlignment()](#getAlignment--) | Получает или задает информацию о выравнивании текста по вертикали. |
| [setAlignment(int value)](#setAlignment-int-) | Получает или задает информацию о выравнивании текста по вертикали. |
| [getLineAlignment()](#getLineAlignment--) | Получает или задает выравнивание строк по горизонтали. |
| [setLineAlignment(int value)](#setLineAlignment-int-) | Получает или задает выравнивание строк по горизонтали. |
| [getHotkeyPrefix()](#getHotkeyPrefix--) | Получает или задает объект `HotkeyPrefix`([.getHotkeyPrefix](../../null/\#getHotkeyPrefix)/[.setHotkeyPrefix(int)](../../null/\#setHotkeyPrefix-int-)) для этого объекта [StringFormat](../../com.aspose.drawing/stringformat). |
| [setHotkeyPrefix(int value)](#setHotkeyPrefix-int-) | Получает или задает объект `HotkeyPrefix`([.getHotkeyPrefix](../../null/\#getHotkeyPrefix)/[.setHotkeyPrefix(int)](../../null/\#setHotkeyPrefix-int-)) для этого объекта [StringFormat](../../com.aspose.drawing/stringformat). |
| [getTrimming()](#getTrimming--) | Получает или задает перечисление [StringTrimming](../../com.aspose.drawing/stringtrimming) для этого объекта [StringFormat](../../com.aspose.drawing/stringformat). |
| [setTrimming(int value)](#setTrimming-int-) | Получает или задает перечисление [StringTrimming](../../com.aspose.drawing/stringtrimming) для этого объекта [StringFormat](../../com.aspose.drawing/stringformat). |
| [getDigitSubstitutionLanguage()](#getDigitSubstitutionLanguage--) | Получает язык, используемый при замене локальных цифр на западные. |
| [getDigitSubstitutionMethod()](#getDigitSubstitutionMethod--) | Получает метод, используемый для замены цифр. |
| [dispose()](#dispose--) | Освобождает все ресурсы, используемые этим объектом [StringFormat](../../com.aspose.drawing/stringformat). |
| [deepClone()](#deepClone--) | Создает точную копию этого объекта [StringFormat](../../com.aspose.drawing/stringformat). |
| [getTabStops(float[] firstTabOffset)](#getTabStops-float---) | Получает позиции табуляции для этого объекта [StringFormat](../../com.aspose.drawing/stringformat). |
| [getTabStops()](#getTabStops--) | Получает массив расстояний между позициями табуляции в единицах, указанных свойством `Aspose.Imaging.getGraphics().PageUnit`. |
| [setTabStops(float firstTabOffset, float[] tabStops)](#setTabStops-float-float---) | Устанавливает позиции табуляции для этого объекта [StringFormat](../../com.aspose.drawing/stringformat). |
| [setDigitSubstitution(int language, int substitute)](#setDigitSubstitution-int-int-) | Указывает язык и метод, используемые при замене локальных цифр на западные. |
| [setMeasurableCharacterRanges(CharacterRange[] ranges)](#setMeasurableCharacterRanges-com.aspose.drawing.CharacterRange---) | Указывает массив структур [CharacterRange](../../com.aspose.drawing/characterrange), представляющих диапазоны символов, измеряемые вызовом метода `MeasureCharacterRanges`. |
### StringFormat() {#StringFormat--}
```
public StringFormat()
```


Инициализирует новый экземпляр класса [StringFormat](../../com.aspose.drawing/stringformat).

### StringFormat(StringFormat format) {#StringFormat-com.aspose.drawing.StringFormat-}
```
public StringFormat(StringFormat format)
```


Инициализирует новый экземпляр класса [StringFormat](../../com.aspose.drawing/stringformat) из указанного существующего объекта [StringFormat](../../com.aspose.drawing/stringformat).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| format | [StringFormat](../../com.aspose.drawing/stringformat) | Объект [StringFormat](../../com.aspose.drawing/stringformat), из которого инициализируется новый объект [StringFormat](../../com.aspose.drawing/stringformat). |

### StringFormat(int options, int language) {#StringFormat-int-int-}
```
public StringFormat(int options, int language)
```


Инициализирует новый экземпляр класса [StringFormat](../../com.aspose.drawing/stringformat) с указанным перечислением [StringFormatFlags](../../com.aspose.drawing/stringformatflags) и языком.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| options | int | Перечисление [StringFormatFlags](../../com.aspose.drawing/stringformatflags) для нового объекта [StringFormat](../../com.aspose.drawing/stringformat). |
| язык | int | Значение, указывающее язык текста. |

### StringFormat(int options) {#StringFormat-int-}
```
public StringFormat(int options)
```


Инициализирует новый экземпляр класса [StringFormat](../../com.aspose.drawing/stringformat) с указанным перечислением [StringFormatFlags](../../com.aspose.drawing/stringformatflags).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| options | int | Перечисление [StringFormatFlags](../../com.aspose.drawing/stringformatflags) для нового объекта [StringFormat](../../com.aspose.drawing/stringformat). |

### setDigitSubstitutionLanguage(int value) {#setDigitSubstitutionLanguage-int-}
```
public void setDigitSubstitutionLanguage(int value)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### setDigitSubstitutionMethod(int value) {#setDigitSubstitutionMethod-int-}
```
public void setDigitSubstitutionMethod(int value)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getFirstTabOffset() {#getFirstTabOffset--}
```
public float getFirstTabOffset()
```




**Returns:**
float
### getGenericDefault() {#getGenericDefault--}
```
public static StringFormat getGenericDefault()
```


Получает универсальный объект [StringFormat](../../com.aspose.drawing/stringformat) по умолчанию.

**Returns:**
[StringFormat](../../com.aspose.drawing/stringformat)
### getGenericTypographic() {#getGenericTypographic--}
```
public static StringFormat getGenericTypographic()
```


Получает универсальный типографический объект [StringFormat](../../com.aspose.drawing/stringformat).

**Returns:**
[StringFormat](../../com.aspose.drawing/stringformat) - A generic typographic [StringFormat](../../com.aspose.drawing/stringformat) object.
### getFormatFlags() {#getFormatFlags--}
```
public int getFormatFlags()
```


Получает или задает перечисление [StringFormatFlags](../../com.aspose.drawing/stringformatflags), содержащее информацию о форматировании.

**Returns:**
int
### setFormatFlags(int value) {#setFormatFlags-int-}
```
public void setFormatFlags(int value)
```


Получает или задает перечисление [StringFormatFlags](../../com.aspose.drawing/stringformatflags), содержащее информацию о форматировании.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getAlignment() {#getAlignment--}
```
public int getAlignment()
```


Получает или задает информацию о выравнивании текста по вертикали.

**Returns:**
int
### setAlignment(int value) {#setAlignment-int-}
```
public void setAlignment(int value)
```


Получает или задает информацию о выравнивании текста по вертикали.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getLineAlignment() {#getLineAlignment--}
```
public int getLineAlignment()
```


Получает или задает выравнивание строк по горизонтали.

**Returns:**
int
### setLineAlignment(int value) {#setLineAlignment-int-}
```
public void setLineAlignment(int value)
```


Получает или задает выравнивание строк по горизонтали.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getHotkeyPrefix() {#getHotkeyPrefix--}
```
public int getHotkeyPrefix()
```


Получает или задает объект `HotkeyPrefix`([.getHotkeyPrefix](../../null/\#getHotkeyPrefix)/[.setHotkeyPrefix(int)](../../null/\#setHotkeyPrefix-int-)) для этого объекта [StringFormat](../../com.aspose.drawing/stringformat).

**Returns:**
int
### setHotkeyPrefix(int value) {#setHotkeyPrefix-int-}
```
public void setHotkeyPrefix(int value)
```


Получает или задает объект `HotkeyPrefix`([.getHotkeyPrefix](../../null/\#getHotkeyPrefix)/[.setHotkeyPrefix(int)](../../null/\#setHotkeyPrefix-int-)) для этого объекта [StringFormat](../../com.aspose.drawing/stringformat).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getTrimming() {#getTrimming--}
```
public int getTrimming()
```


Получает или задает перечисление [StringTrimming](../../com.aspose.drawing/stringtrimming) для этого объекта [StringFormat](../../com.aspose.drawing/stringformat).

**Returns:**
int
### setTrimming(int value) {#setTrimming-int-}
```
public void setTrimming(int value)
```


Получает или задает перечисление [StringTrimming](../../com.aspose.drawing/stringtrimming) для этого объекта [StringFormat](../../com.aspose.drawing/stringformat).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getDigitSubstitutionLanguage() {#getDigitSubstitutionLanguage--}
```
public int getDigitSubstitutionLanguage()
```


Получает язык, используемый при замене локальных цифр на западные.

**Returns:**
int - Идентификатор языка National Language Support (NLS), который определяет язык, используемый при замене локальных цифр на западные. Вы можете передать свойство `System.Globalization.CultureInfo.LCID` объекта java.util.Locale в качестве идентификатора языка NLS. Например, предположим, что вы создаёте объект java.util.Locale, передавая строку \"ar-EG\" в конструктор java.util.Locale. Если вы передадите свойство `System.Globalization.CultureInfo.LCID` этого объекта java.util.Locale вместе с `StringDigitSubstitute.Traditional` в метод [.setDigitSubstitution(int,int)](../../null/\\#setDigitSubstitution-int-int-), то арабско‑индийские цифры будут заменены на западные цифры во время отображения.
### getDigitSubstitutionMethod() {#getDigitSubstitutionMethod--}
```
public int getDigitSubstitutionMethod()
```


Получает метод, используемый для замены цифр.

**Returns:**
int - Значение перечисления [StringDigitSubstitute](../../com.aspose.drawing/stringdigitsubstitute), которое определяет, как заменять символы в строке, которые не могут быть отображены, потому что текущий шрифт их не поддерживает.
### dispose() {#dispose--}
```
public void dispose()
```


Освобождает все ресурсы, используемые этим объектом [StringFormat](../../com.aspose.drawing/stringformat).

### deepClone() {#deepClone--}
```
public StringFormat deepClone()
```


Создает точную копию этого объекта [StringFormat](../../com.aspose.drawing/stringformat).

**Returns:**
[StringFormat](../../com.aspose.drawing/stringformat) - The [StringFormat](../../com.aspose.drawing/stringformat) object this method creates.
### getTabStops(float[] firstTabOffset) {#getTabStops-float---}
```
public float[] getTabStops(float[] firstTabOffset)
```


Получает позиции табуляции для этого объекта [StringFormat](../../com.aspose.drawing/stringformat).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| firstTabOffset | float[] | Количество пробелов между началом строки текста и первой табуляцией. |

**Returns:**
float[] - Массив расстояний (в количестве пробелов) между табуляциями.
### getTabStops() {#getTabStops--}
```
public float[] getTabStops()
```


Получает массив расстояний между позициями табуляции в единицах, указанных свойством `Aspose.Imaging.getGraphics().PageUnit`.

**Returns:**
float[] - Табуляции.

Свойство введено вместо удалённого метода GetTabStops.
### setTabStops(float firstTabOffset, float[] tabStops) {#setTabStops-float-float---}
```
public void setTabStops(float firstTabOffset, float[] tabStops)
```


Устанавливает позиции табуляции для этого объекта [StringFormat](../../com.aspose.drawing/stringformat).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| firstTabOffset | float | Количество пробелов между началом строки текста и первой табуляцией. |
| tabStops | float[] | Массив расстояний между табуляциями в единицах, указанных свойством Graphics.PageUnit. |

### setDigitSubstitution(int language, int substitute) {#setDigitSubstitution-int-int-}
```
public void setDigitSubstitution(int language, int substitute)
```


Указывает язык и метод, используемые при замене локальных цифр на западные.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| язык | int | Идентификатор языка National Language Support (NLS), который определяет язык, используемый при замене локальных цифр на западные. Вы можете передать свойство `System.Globalization.CultureInfo.LCID` объекта java.util.Locale в качестве идентификатора языка NLS. Например, предположим, что вы создаёте объект java.util.Locale, передавая строку `\"ar-EG\"` в конструктор java.util.Locale. Если вы передадите свойство `System.Globalization.CultureInfo.LCID` этого объекта java.util.Locale вместе с `StringDigitSubstitute.Traditional` в метод `M:StringFormat.SetDigitSubstitution(System.Int32,StringDigitSubstitute)`, то арабско‑индийские цифры будут заменены на западные цифры во время отображения. |
| substitute | int | Элемент перечисления [StringDigitSubstitute](../../com.aspose.drawing/stringdigitsubstitute), который определяет, как отображаются цифры. |

### setMeasurableCharacterRanges(CharacterRange[] ranges) {#setMeasurableCharacterRanges-com.aspose.drawing.CharacterRange---}
```
public void setMeasurableCharacterRanges(CharacterRange[] ranges)
```


Указывает массив структур [CharacterRange](../../com.aspose.drawing/characterrange), представляющих диапазоны символов, измеряемые вызовом метода `MeasureCharacterRanges`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| ranges | [CharacterRange\[\]](../../com.aspose.drawing/characterrange) | Массив структур [CharacterRange](../../com.aspose.drawing/characterrange), который задаёт диапазоны символов, измеряемые вызовом метода `MeasureCharacterRanges`. |

