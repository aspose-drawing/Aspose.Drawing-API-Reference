---
title: StringFormatFlags
second_title: Справочник API Aspose.Drawing для Java
description: Указывает информацию о отображении и расположении текстовых строк.
type: docs
weight: 48
url: /ru/java/com.aspose.drawing/stringformatflags/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class StringFormatFlags extends System.Enum
```

Указывает информацию о отображении и расположении текстовых строк.
## Поля

| Поле | Описание |
| --- | --- |
| [DirectionRightToLeft](#DirectionRightToLeft) | Текст отображается справа налево. |
| [DirectionVertical](#DirectionVertical) | Текст выровнен по вертикали. |
| [FitBlackBox](#FitBlackBox) | Разрешено, чтобы части символов выступали за пределы прямоугольника размещения строки. |
| [DisplayFormatControl](#DisplayFormatControl) | Управляющие символы, такие как маркер слева направо, отображаются в выводе с соответствующим глифом. |
| [NoFontFallback](#NoFontFallback) | Отключено использование альтернативных шрифтов для символов, не поддерживаемых запрошенным шрифтом. |
| [MeasureTrailingSpaces](#MeasureTrailingSpaces) | Включает завершающий пробел в конце каждой строки. |
| [NoWrap](#NoWrap) | Перенос текста между строками при форматировании внутри прямоугольника отключён. |
| [LineLimit](#LineLimit) | В прямоугольнике форматирования размещаются только целые строки. |
| [NoClip](#NoClip) | Разрешено отображать выступающие части глифов и не перенесённый текст, выходящий за пределы прямоугольника форматирования. |
| [ExactAlignment](#ExactAlignment) | Точное выравнивание, правильный отступ GDI+ |
### DirectionRightToLeft {#DirectionRightToLeft}
```
public static final int DirectionRightToLeft
```


Текст отображается справа налево.

### DirectionVertical {#DirectionVertical}
```
public static final int DirectionVertical
```


Текст выровнен по вертикали.

### FitBlackBox {#FitBlackBox}
```
public static final int FitBlackBox
```


Разрешено, чтобы части символов выступали за пределы прямоугольника размещения строки. По умолчанию символы переустанавливаются, чтобы избежать любого выступания.

### DisplayFormatControl {#DisplayFormatControl}
```
public static final int DisplayFormatControl
```


Управляющие символы, такие как маркер слева направо, отображаются в выводе с соответствующим глифом.

### NoFontFallback {#NoFontFallback}
```
public static final int NoFontFallback
```


Отключено использование альтернативных шрифтов для символов, не поддерживаемых запрошенным шрифтом. Любые отсутствующие символы отображаются глифом отсутствующего шрифта, обычно открытым квадратом.

### MeasureTrailingSpaces {#MeasureTrailingSpaces}
```
public static final int MeasureTrailingSpaces
```


Включает завершающий пробел в конце каждой строки. По умолчанию ограничивающий прямоугольник, возвращаемый методом MeasureString, исключает пробел в конце каждой строки. Установите этот флаг, чтобы включить этот пробел в измерения.

### NoWrap {#NoWrap}
```
public static final int NoWrap
```


Перенос текста между строками при форматировании внутри прямоугольника отключён. Этот флаг подразумевается, когда вместо прямоугольника передаётся точка или когда указанный прямоугольник имеет нулевую длину строки.

### LineLimit {#LineLimit}
```
public static final int LineLimit
```


Только полные строки размещаются в прямоугольнике форматирования. По умолчанию размещение продолжается до конца текста или пока из‑за обрезки не будет видно больше строк, в зависимости от того, что наступит первым. Обратите внимание, что настройки по умолчанию позволяют последней строке быть частично скрытой прямоугольником форматирования, высота которого не является целым кратным высоте строки. Чтобы гарантировать отображение только полных строк, укажите это значение и убедитесь, что прямоугольник форматирования имеет высоту не менее высоты одной строки.

### NoClip {#NoClip}
```
public static final int NoClip
```


Выпирающие части глифов и не переносимый текст, выходящие за пределы прямоугольника форматирования, допускаются к отображению. По умолчанию весь текст и части глифов, выходящие за пределы прямоугольника форматирования, обрезаются.

### ExactAlignment {#ExactAlignment}
```
public static final int ExactAlignment
```


Точное выравнивание, правильный отступ GDI+

