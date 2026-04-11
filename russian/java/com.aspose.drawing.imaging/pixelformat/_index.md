---
title: PixelFormat
second_title: Справочник API Aspose.Drawing для Java
description: Указывает формат цветовых данных для каждого пикселя изображения.
type: docs
weight: 34
url: /ru/java/com.aspose.drawing.imaging/pixelformat/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PixelFormat extends System.Enum
```

Указывает формат цветовых данных для каждого пикселя изображения.
## Поля

| Поле | Описание |
| --- | --- |
| [Indexed](#Indexed) | Пиксельные данные содержат значения, индексированные по цвету, что означает, что эти значения являются индексом в таблице системных цветов, а не отдельными цветовыми значениями. |
| [Gdi](#Gdi) | Пиксельные данные содержат цвета GDI. |
| [Alpha](#Alpha) | Пиксельные данные содержат альфа‑значения, которые не предумножены. |
| [PAlpha](#PAlpha) | Формат пикселей содержит предумноженные альфа‑значения. |
| [Extended](#Extended) | Зарезервированное значение. |
| [Canonical](#Canonical) | Стандартный формат пикселей — 32 бита на пиксель. |
| [Undefined](#Undefined) | Формат пикселей не определён. |
| [DontCare](#DontCare) | Формат пикселей не указан. |
| [Format1bppIndexed](#Format1bppIndexed) | Указывает, что формат пикселей — 1 бит на пиксель и используется индексированный цвет. |
| [Format4bppIndexed](#Format4bppIndexed) | Указывает, что формат — 4 бита на пиксель, индексированный. |
| [Format8bppIndexed](#Format8bppIndexed) | Указывает, что формат — 8 бит на пиксель, индексированный. |
| [Format16bppGrayScale](#Format16bppGrayScale) | Формат пикселей — 16 бит на пиксель. |
| [Format16bppRgb555](#Format16bppRgb555) | Указывает, что формат — 16 бит на пиксель; по 5 бит используется для красного, зелёного и синего компонентов. |
| [Format16bppRgb565](#Format16bppRgb565) | Указывает, что формат — 16 бит на пиксель; 5 бит используется для красного компонента, 6 бит — для зелёного, и 5 бит — для синего компонента. |
| [Format16bppArgb1555](#Format16bppArgb1555) | Формат пикселей — 16 бит на пиксель. |
| [Format24bppRgb](#Format24bppRgb) | Указывает, что формат — 24 бита на пиксель; по 8 бит используется для компонентов красного, зелёного и синего. |
| [Format32bppRgb](#Format32bppRgb) | Указывает, что формат — 32 бита на пиксель; по 8 бит используется для компонентов красного, зелёного и синего. |
| [Format32bppArgb](#Format32bppArgb) | Указывает, что формат — 32 бита на пиксель; по 8 бит используется для компонентов альфа, красного, зелёного и синего. |
| [Format32bppPArgb](#Format32bppPArgb) | Указывает, что формат — 32 бита на пиксель; по 8 бит используется для компонентов альфа, красного, зелёного и синего. |
| [Format48bppRgb](#Format48bppRgb) | Указывает, что формат — 48 бит на пиксель; по 16 бит используется для компонентов красного, зелёного и синего. |
| [Format64bppArgb](#Format64bppArgb) | Указывает, что формат — 64 бита на пиксель; по 16 бит используется для компонентов альфа, красного, зелёного и синего. |
| [Format64bppPArgb](#Format64bppPArgb) | Указывает, что формат — 64 бита на пиксель; по 16 бит используется для компонентов альфа, красного, зелёного и синего. |
| [Max](#Max) | Максимальное значение для этого перечисления. |
### Indexed {#Indexed}
```
public static final int Indexed
```


Пиксельные данные содержат значения, индексированные по цвету, что означает, что эти значения являются индексом в таблице системных цветов, а не отдельными цветовыми значениями.

### Gdi {#Gdi}
```
public static final int Gdi
```


Пиксельные данные содержат цвета GDI.

### Alpha {#Alpha}
```
public static final int Alpha
```


Пиксельные данные содержат альфа‑значения, которые не предумножены.

### PAlpha {#PAlpha}
```
public static final int PAlpha
```


Формат пикселей содержит предумноженные альфа‑значения.

### Extended {#Extended}
```
public static final int Extended
```


Зарезервированное значение.

### Canonical {#Canonical}
```
public static final int Canonical
```


Стандартный формат пикселей — 32 бита на пиксель. Формат задаёт 24-битную глубину цвета и 8-битный альфа‑канал.

### Undefined {#Undefined}
```
public static final int Undefined
```


Формат пикселей не определён.

### DontCare {#DontCare}
```
public static final int DontCare
```


Формат пикселей не указан.

### Format1bppIndexed {#Format1bppIndexed}
```
public static final int Format1bppIndexed
```


Указывает, что формат пикселей — 1 бит на пиксель и использует индексированный цвет. Поэтому таблица цветов содержит два цвета.

### Format4bppIndexed {#Format4bppIndexed}
```
public static final int Format4bppIndexed
```


Указывает, что формат — 4 бита на пиксель, индексированный.

### Format8bppIndexed {#Format8bppIndexed}
```
public static final int Format8bppIndexed
```


Указывает, что формат — 8 бит на пиксель, индексированный. Поэтому таблица цветов содержит 256 цветов.

### Format16bppGrayScale {#Format16bppGrayScale}
```
public static final int Format16bppGrayScale
```


Формат пикселей — 16 бит на пиксель. Информация о цвете задаёт 65536 оттенков серого.

### Format16bppRgb555 {#Format16bppRgb555}
```
public static final int Format16bppRgb555
```


Указывает, что формат — 16 бит на пиксель; по 5 бит используется для компонентов красного, зелёного и синего. Оставшийся бит не используется.

### Format16bppRgb565 {#Format16bppRgb565}
```
public static final int Format16bppRgb565
```


Указывает, что формат — 16 бит на пиксель; 5 бит используется для красного компонента, 6 бит — для зелёного, и 5 бит — для синего компонента.

### Format16bppArgb1555 {#Format16bppArgb1555}
```
public static final int Format16bppArgb1555
```


Формат пикселей — 16 бит на пиксель. Информация о цвете задаёт 32 768 оттенков цвета, из которых 5 бит — красный, 5 бит — зелёный, 5 бит — синий и 1 бит — альфа.

### Format24bppRgb {#Format24bppRgb}
```
public static final int Format24bppRgb
```


Указывает, что формат — 24 бита на пиксель; по 8 бит используется для компонентов красного, зелёного и синего.

### Format32bppRgb {#Format32bppRgb}
```
public static final int Format32bppRgb
```


Указывает, что формат — 32 бита на пиксель; по 8 бит используется для компонентов красного, зелёного и синего. Оставшиеся 8 бит не используются.

### Format32bppArgb {#Format32bppArgb}
```
public static final int Format32bppArgb
```


Указывает, что формат — 32 бита на пиксель; по 8 бит используется для компонентов альфа, красного, зелёного и синего.

### Format32bppPArgb {#Format32bppPArgb}
```
public static final int Format32bppPArgb
```


Указывает, что формат — 32 бита на пиксель; по 8 бит используется для компонентов альфа, красного, зелёного и синего. Компоненты красного, зелёного и синего предварительно умножены на альфа‑компонент.

### Format48bppRgb {#Format48bppRgb}
```
public static final int Format48bppRgb
```


Указывает, что формат — 48 бит на пиксель; по 16 бит используется для компонентов красного, зелёного и синего.

### Format64bppArgb {#Format64bppArgb}
```
public static final int Format64bppArgb
```


Указывает, что формат — 64 бита на пиксель; по 16 бит используется для компонентов альфа, красного, зелёного и синего.

### Format64bppPArgb {#Format64bppPArgb}
```
public static final int Format64bppPArgb
```


Указывает, что формат — 64 бита на пиксель; по 16 бит используется для компонентов альфа, красного, зелёного и синего. Компоненты красного, зелёного и синего предварительно умножены на альфа‑компонент.

### Max {#Max}
```
public static final int Max
```


Максимальное значение для этого перечисления.

