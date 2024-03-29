---
title: ImageFlags
second_title: Справочник по API Aspose.Drawing для .NET
description: Определяет атрибуты пиксельных данных содержащихся вImage../system.drawing/image объект. Свойство Flags возвращает член этого перечисления. Это перечисление имеет атрибут FlagsAttribute который позволяет побитовую комбинацию значений его элементов.
type: docs
weight: 760
url: /ru/net/system.drawing.imaging/imageflags/
---
## ImageFlags enumeration

Определяет атрибуты пиксельных данных, содержащихся в[`Image`](../../system.drawing/image) объект. Свойство Flags возвращает член этого перечисления. Это перечисление имеет атрибут FlagsAttribute, который позволяет побитовую комбинацию значений его элементов.

```csharp
[Flags]
public enum ImageFlags
```

### Ценности

| Имя | Ценность | Описание |
| --- | --- | --- |
| None | `0` | Информация о формате отсутствует |
| Scalable | `1` | Пиксельные данные масштабируются. |
| HasAlpha | `2` | Пиксельные данные содержат информацию об альфа-канале. |
| HasTranslucent | `4` | Указывает, что пиксельные данные имеют альфа-значения, отличные от 0 (прозрачный) и 255 (непрозрачный) |
| PartiallyScalable | `8` | Пиксельные данные частично масштабируются, но есть некоторые ограничения. |
| ColorSpaceRgb | `10` | Пиксельные данные используют цветовое пространство RGB. |
| ColorSpaceCmyk | `20` | Пиксельные данные используют цветовое пространство CMYK. |
| ColorSpaceGray | `40` | Пиксельные данные представлены в оттенках серого. |
| ColorSpaceYcbcr | `80` | Указывает, что изображение хранится с использованием цветового пространства YCBCR. |
| ColorSpaceYcck | `100` | Указывает, что изображение сохраняется с использованием цветового пространства YCCK. |
| HasRealDpi | `1000` | Указывает, что информация о количестве точек на дюйм сохраняется в изображении. |
| HasRealPixelSize | `2000` | Указывает, что размер пикселя сохраняется в изображении. |
| ReadOnly | `10000` | Данные пикселей доступны только для чтения. |
| Caching | `20000` | Данные пикселей можно кэшировать для более быстрого доступа. |

### Смотрите также

* пространство имен [System.Drawing.Imaging](../../system.drawing.imaging)
* сборка [Aspose.Drawing](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Drawing.dll -->
