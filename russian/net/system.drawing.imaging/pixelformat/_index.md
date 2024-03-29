---
title: PixelFormat
second_title: Справочник по API Aspose.Drawing для .NET
description: Определяет формат данных о цвете для каждого пикселя изображения.
type: docs
weight: 850
url: /ru/net/system.drawing.imaging/pixelformat/
---
## PixelFormat enumeration

Определяет формат данных о цвете для каждого пикселя изображения.

```csharp
public enum PixelFormat
```

### Ценности

| Имя | Ценность | Описание |
| --- | --- | --- |
| Indexed | `65536` | Пиксельные данные содержат индексированные по цвету значения, что означает, что значения являются индексом цветов в системной таблице цветов , а не значениями отдельных цветов. |
| Gdi | `131072` | Пиксельные данные содержат цвета GDI. |
| Alpha | `262144` | Данные пикселей содержат альфа-значения, которые не умножаются предварительно. |
| PAlpha | `524288` | Формат пикселей содержит предварительно умноженные альфа-значения. |
| Extended | `1048576` | Зарезервированное значение. |
| Canonical | `2097152` | Формат пикселей по умолчанию: 32 бита на пиксель. Формат определяет 24-битную глубину цвета и 8-битный альфа-канал. |
| Undefined | `0` | Формат пикселей не определен. |
| DontCare | `0` | Формат пикселей не указан. |
| Format1bppIndexed | `196865` | Указывает, что формат пикселя составляет 1 бит на пиксель и что он использует индексированный цвет. Таким образом, таблица цветов содержит два цвета. |
| Format4bppIndexed | `197634` | Указывает, что формат — 4 бита на пиксель, индексированный. |
| Format8bppIndexed | `198659` | Указывает, что формат — 8 бит на пиксель, индексированный. Таким образом, таблица цветов содержит 256 цветов. |
| Format16bppGrayScale | `1052676` | Формат пикселя — 16 бит на пиксель. Информация о цвете указывает 65536 оттенков серого. |
| Format16bppRgb555 | `135173` | Указывает, что формат составляет 16 бит на пиксель; по 5 бит используются для красного, зеленого и синего компонентов. Оставшийся бит не используется. |
| Format16bppRgb565 | `135174` | Указывает, что формат составляет 16 бит на пиксель; 5 бит используются для красного компонента, 6 бит используются для зеленого компонента и 5 бит используются для синего компонента. |
| Format16bppArgb1555 | `397319` | Пиксельный формат — 16 бит на пиксель. Информация о цвете определяет 32 768 оттенков цвета, , из которых 5 бит — красный, 5 бит — зеленый, 5 бит — синий и 1 бит — альфа. |
| Format24bppRgb | `137224` | Указывает, что формат составляет 24 бита на пиксель; 8 бит используются для красного, зеленого и синего компонентов. |
| Format32bppRgb | `139273` | Указывает, что формат составляет 32 бита на пиксель; По 8 бит используются для красного, зеленого и синего компонентов. Остальные 8 бит не используются. |
| Format32bppArgb | `2498570` | Указывает, что формат составляет 32 бита на пиксель; 8 бит используются для альфа, красного, зеленого и синего компонентов. |
| Format32bppPArgb | `925707` | Указывает, что формат составляет 32 бита на пиксель; 8 бит используются для альфа, красного, зеленого и синего компонентов. Красная, зеленая и синяя составляющие предварительно умножаются, в соответствии с альфа-компонентой. |
| Format48bppRgb | `1060876` | Указывает, что формат составляет 48 бит на пиксель; 16 бит используются для красного, зеленого и синего компонентов. |
| Format64bppArgb | `3424269` | Указывает, что формат составляет 64 бита на пиксель; 16 бит используются для альфа, красного, зеленого и синего компонентов. |
| Format64bppPArgb | `1851406` | Указывает, что формат составляет 64 бита на пиксель; 16 бит используются для альфа, красного, зеленого и синего компонентов. Красная, зеленая и синяя составляющие предварительно умножаются в соответствии с альфа-компонентом. |
| Max | `15` | Максимальное значение для этого перечисления. |

### Смотрите также

* пространство имен [System.Drawing.Imaging](../../system.drawing.imaging)
* сборка [Aspose.Drawing](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Drawing.dll -->
