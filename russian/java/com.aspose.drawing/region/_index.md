---
title: Region
second_title: Справочник API Aspose.Drawing для Java
description: Описывает внутреннюю часть графической формы, состоящей из прямоугольников и путей.
type: docs
weight: 40
url: /ru/java/com.aspose.drawing/region/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public final class Region implements System.IDisposable
```

Описывает внутреннюю часть графической фигуры, состоящей из прямоугольников и путей. Этот класс не может быть наследован.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Region()](#Region--) | Инициализирует новый экземпляр класса [Region](../../com.aspose.drawing/region). |
| [Region(RectangleF rect)](#Region-com.aspose.drawing.RectangleF-) | Инициализирует новый экземпляр класса [Region](../../com.aspose.drawing/region) из указанной структуры [RectangleF](../../com.aspose.drawing/rectanglef). |
| [Region(Rectangle rect)](#Region-com.aspose.drawing.Rectangle-) | Инициализирует новый экземпляр класса [Region](../../com.aspose.drawing/region) из указанной структуры [Rectangle](../../com.aspose.drawing/rectangle). |
| [Region(GraphicsPath path)](#Region-com.aspose.drawing.drawing2d.GraphicsPath-) | Инициализирует новый экземпляр класса [Region](../../com.aspose.drawing/region) с указанным [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath). |
| [Region(RegionData rgnData)](#Region-com.aspose.drawing.drawing2d.RegionData-) | Инициализирует новый экземпляр класса [Region](../../com.aspose.drawing/region) из указанных данных. |
## Методы

| Метод | Описание |
| --- | --- |
| [dispose()](#dispose--) | Освобождает все ресурсы, используемые этим [Region](../../com.aspose.drawing/region). |
| [equals(Region region, Graphics g)](#equals-com.aspose.drawing.Region-com.aspose.drawing.Graphics-) | Проверяет, идентичен ли указанный [Region](../../com.aspose.drawing/region) этому [Region](../../com.aspose.drawing/region) на указанной поверхности рисования. |
| [deepClone()](#deepClone--) | Создаёт точную копию этого [Region](../../com.aspose.drawing/region). |
| [makeInfinite()](#makeInfinite--) | Инициализирует объект [Region](../../com.aspose.drawing/region) бесконечным внутренним пространством. |
| [makeEmpty()](#makeEmpty--) | Инициализирует этот [Region](../../com.aspose.drawing/region) пустым внутренним пространством. |
| [intersect(RectangleF rect)](#intersect-com.aspose.drawing.RectangleF-) | Обновляет этот [Region](../../com.aspose.drawing/region), задавая его пересечение с указанной структурой [RectangleF](../../com.aspose.drawing/rectanglef). |
| [intersect(Rectangle rect)](#intersect-com.aspose.drawing.Rectangle-) | Обновляет этот [Region](../../com.aspose.drawing/region), задавая его пересечение с указанной структурой [Rectangle](../../com.aspose.drawing/rectangle). |
| [intersect(GraphicsPath path)](#intersect-com.aspose.drawing.drawing2d.GraphicsPath-) | Обновляет этот [Region](../../com.aspose.drawing/region), задавая его пересечение с указанным [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath). |
| [intersect(Region region)](#intersect-com.aspose.drawing.Region-) | Обновляет этот [Region](../../com.aspose.drawing/region), задавая его пересечение с указанным [Region](../../com.aspose.drawing/region). |
| [union(RectangleF rect)](#union-com.aspose.drawing.RectangleF-) | Обновляет этот [Region](../../com.aspose.drawing/region), задавая его объединение с указанной структурой [RectangleF](../../com.aspose.drawing/rectanglef). |
| [union(Rectangle rect)](#union-com.aspose.drawing.Rectangle-) | Обновляет этот [Region](../../com.aspose.drawing/region), задавая его объединение с указанной структурой [Rectangle](../../com.aspose.drawing/rectangle). |
| [union(GraphicsPath path)](#union-com.aspose.drawing.drawing2d.GraphicsPath-) | Обновляет этот [Region](../../com.aspose.drawing/region), задавая его объединение с указанным [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath). |
| [union(Region region)](#union-com.aspose.drawing.Region-) | Обновляет этот [Region](../../com.aspose.drawing/region), задавая его объединение с указанным [Region](../../com.aspose.drawing/region). |
| [getRegionData()](#getRegionData--) | Возвращает объект [RegionData](../../com.aspose.drawing.drawing2d/regiondata), представляющий информацию, описывающую этот [Region](../../com.aspose.drawing/region). |
| [xor(RectangleF rect)](#xor-com.aspose.drawing.RectangleF-) | Обновляет этот [Region](../../com.aspose.drawing/region), задавая его объединение за вычетом пересечения с указанной структурой [RectangleF](../../com.aspose.drawing/rectanglef). |
| [xor(Rectangle rect)](#xor-com.aspose.drawing.Rectangle-) | Обновляет этот [Region](../../com.aspose.drawing/region), задавая его объединение за вычетом пересечения с указанной структурой [Rectangle](../../com.aspose.drawing/rectangle). |
| [xor(GraphicsPath path)](#xor-com.aspose.drawing.drawing2d.GraphicsPath-) | Обновляет этот [Region](../../com.aspose.drawing/region), задавая его объединение за вычетом пересечения с указанным [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath). |
| [xor(Region region)](#xor-com.aspose.drawing.Region-) | Обновляет этот [Region](../../com.aspose.drawing/region), задавая его объединение за вычетом пересечения с указанным [Region](../../com.aspose.drawing/region). |
| [exclude(RectangleF rect)](#exclude-com.aspose.drawing.RectangleF-) | Обновляет этот [Region](../../com.aspose.drawing/region), оставляя только ту часть его внутреннего пространства, которая не пересекается с указанной структурой [RectangleF](../../com.aspose.drawing/rectanglef). |
| [exclude(Rectangle rect)](#exclude-com.aspose.drawing.Rectangle-) | Обновляет этот [Region](../../com.aspose.drawing/region), оставляя только ту часть его внутреннего пространства, которая не пересекается с указанной структурой [Rectangle](../../com.aspose.drawing/rectangle). |
| [exclude(GraphicsPath path)](#exclude-com.aspose.drawing.drawing2d.GraphicsPath-) | Обновляет этот [Region](../../com.aspose.drawing/region), оставляя только ту часть его внутреннего пространства, которая не пересекается с указанным [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath). |
| [exclude(Region region)](#exclude-com.aspose.drawing.Region-) | Обновляет этот [Region](../../com.aspose.drawing/region), оставляя только ту часть его внутреннего пространства, которая не пересекается с указанным [Region](../../com.aspose.drawing/region). |
| [complement(RectangleF rect)](#complement-com.aspose.drawing.RectangleF-) | Обновляет этот [Region](../../com.aspose.drawing/region), оставляя часть указанной структуры [RectangleF](../../com.aspose.drawing/rectanglef), которая не пересекается с этим [Region](../../com.aspose.drawing/region). |
| [complement(Rectangle rect)](#complement-com.aspose.drawing.Rectangle-) | Обновляет этот [Region](../../com.aspose.drawing/region), оставляя часть указанной структуры [Rectangle](../../com.aspose.drawing/rectangle), которая не пересекается с этим [Region](../../com.aspose.drawing/region). |
| [complement(GraphicsPath path)](#complement-com.aspose.drawing.drawing2d.GraphicsPath-) | Обновляет этот [Region](../../com.aspose.drawing/region), оставляя часть указанного [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath), которая не пересекается с этим [Region](../../com.aspose.drawing/region). |
| [complement(Region region)](#complement-com.aspose.drawing.Region-) | Обновляет этот [Region](../../com.aspose.drawing/region) так, чтобы он содержал часть указанного [Region](../../com.aspose.drawing/region), которая не пересекается с этим [Region](../../com.aspose.drawing/region). |
| [translate(float dx, float dy)](#translate-float-float-) | Смещает координаты этого [Region](../../com.aspose.drawing/region) на указанную величину. |
| [translate(int dx, int dy)](#translate-int-int-) | Смещает координаты этого [Region](../../com.aspose.drawing/region) на указанную величину. |
| [transform(Matrix matrix)](#transform-com.aspose.drawing.drawing2d.Matrix-) | Преобразует этот [Region](../../com.aspose.drawing/region) с помощью указанной [Matrix](../../com.aspose.drawing.drawing2d/matrix). |
| [getBounds(Graphics g)](#getBounds-com.aspose.drawing.Graphics-) | Получает структуру [RectangleF](../../com.aspose.drawing/rectanglef), представляющую прямоугольник, ограничивающий этот [Region](../../com.aspose.drawing/region) на поверхности рисования объекта [Graphics](../../com.aspose.drawing/graphics). |
| [getRegionScans(Matrix matrix)](#getRegionScans-com.aspose.drawing.drawing2d.Matrix-) | Возвращает массив структур [RectangleF](../../com.aspose.drawing/rectanglef), приближающих этот [Region](../../com.aspose.drawing/region) после применения указанного преобразования матрицы. |
| [isEmpty(Graphics g)](#isEmpty-com.aspose.drawing.Graphics-) | Проверяет, имеет ли этот [Region](../../com.aspose.drawing/region) пустой внутренний участок на указанной поверхности рисования. |
| [isInfinite(Graphics g)](#isInfinite-com.aspose.drawing.Graphics-) | Проверяет, имеет ли этот [Region](../../com.aspose.drawing/region) бесконечный внутренний участок на указанной поверхности рисования. |
| [isVisible(float x, float y)](#isVisible-float-float-) | Проверяет, содержится ли указанная точка внутри этого [Region](../../com.aspose.drawing/region). |
| [isVisible(PointF point)](#isVisible-com.aspose.drawing.PointF-) | Проверяет, содержится ли указанная структура [PointF](../../com.aspose.drawing/pointf) внутри этого [Region](../../com.aspose.drawing/region). |
| [isVisible(float x, float y, Graphics g)](#isVisible-float-float-com.aspose.drawing.Graphics-) | Проверяет, содержится ли указанная точка внутри этого [Region](../../com.aspose.drawing/region), когда он отрисовывается с использованием указанного [Graphics](../../com.aspose.drawing/graphics). |
| [isVisible(PointF point, Graphics g)](#isVisible-com.aspose.drawing.PointF-com.aspose.drawing.Graphics-) | Проверяет, содержится ли указанная структура [PointF](../../com.aspose.drawing/pointf) внутри этого [Region](../../com.aspose.drawing/region), когда он отрисовывается с использованием указанного [Graphics](../../com.aspose.drawing/graphics). |
| [isVisible(float x, float y, float width, float height)](#isVisible-float-float-float-float-) | Проверяет, содержится ли какая‑либо часть указанного прямоугольника внутри этого [Region](../../com.aspose.drawing/region). |
| [isVisible(RectangleF rect)](#isVisible-com.aspose.drawing.RectangleF-) | Проверяет, содержится ли какая‑либо часть указанной структуры [RectangleF](../../com.aspose.drawing/rectanglef) внутри этого [Region](../../com.aspose.drawing/region). |
| [isVisible(float x, float y, float width, float height, Graphics g)](#isVisible-float-float-float-float-com.aspose.drawing.Graphics-) | Проверяет, содержится ли какая‑либо часть указанного прямоугольника внутри этого [Region](../../com.aspose.drawing/region), когда он отрисовывается с использованием указанного [Graphics](../../com.aspose.drawing/graphics). |
| [isVisible(RectangleF rect, Graphics g)](#isVisible-com.aspose.drawing.RectangleF-com.aspose.drawing.Graphics-) | Проверяет, содержится ли какая‑либо часть указанной структуры [RectangleF](../../com.aspose.drawing/rectanglef) внутри этого [Region](../../com.aspose.drawing/region), когда он отрисовывается с использованием указанного [Graphics](../../com.aspose.drawing/graphics). |
| [isVisible(int x, int y, Graphics g)](#isVisible-int-int-com.aspose.drawing.Graphics-) | Проверяет, содержится ли указанная точка внутри объекта [Region](../../com.aspose.drawing/region), когда он отрисовывается с использованием указанного объекта [Graphics](../../com.aspose.drawing/graphics). |
| [isVisible(Point point)](#isVisible-com.aspose.drawing.Point-) | Проверяет, содержится ли указанная структура [Point](../../com.aspose.drawing/point) внутри этого [Region](../../com.aspose.drawing/region). |
| [isVisible(Point point, Graphics g)](#isVisible-com.aspose.drawing.Point-com.aspose.drawing.Graphics-) | Проверяет, содержится ли указанная структура [Point](../../com.aspose.drawing/point) внутри этого [Region](../../com.aspose.drawing/region), когда он отрисовывается с использованием указанного [Graphics](../../com.aspose.drawing/graphics). |
| [isVisible(int x, int y, int width, int height)](#isVisible-int-int-int-int-) | Проверяет, содержится ли какая‑либо часть указанного прямоугольника внутри этого [Region](../../com.aspose.drawing/region). |
| [isVisible(Rectangle rect)](#isVisible-com.aspose.drawing.Rectangle-) | Проверяет, содержится ли какая‑либо часть указанной структуры [Rectangle](../../com.aspose.drawing/rectangle) внутри этого [Region](../../com.aspose.drawing/region). |
| [isVisible(int x, int y, int width, int height, Graphics g)](#isVisible-int-int-int-int-com.aspose.drawing.Graphics-) | Проверяет, содержится ли какая‑либо часть указанного прямоугольника внутри этого [Region](../../com.aspose.drawing/region), когда он отрисовывается с использованием указанного [Graphics](../../com.aspose.drawing/graphics). |
| [isVisible(Rectangle rect, Graphics g)](#isVisible-com.aspose.drawing.Rectangle-com.aspose.drawing.Graphics-) | Проверяет, содержится ли какая‑либо часть указанной структуры [Rectangle](../../com.aspose.drawing/rectangle) внутри этого [Region](../../com.aspose.drawing/region), когда он отрисовывается с использованием указанного [Graphics](../../com.aspose.drawing/graphics). |
### Region() {#Region--}
```
public Region()
```


Инициализирует новый экземпляр класса [Region](../../com.aspose.drawing/region).

### Region(RectangleF rect) {#Region-com.aspose.drawing.RectangleF-}
```
public Region(RectangleF rect)
```


Инициализирует новый экземпляр класса [Region](../../com.aspose.drawing/region) из указанной структуры [RectangleF](../../com.aspose.drawing/rectanglef).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | Структура [RectangleF](../../com.aspose.drawing/rectanglef), определяющая внутреннюю часть нового [Region](../../com.aspose.drawing/region). |

### Region(Rectangle rect) {#Region-com.aspose.drawing.Rectangle-}
```
public Region(Rectangle rect)
```


Инициализирует новый экземпляр класса [Region](../../com.aspose.drawing/region) из указанной структуры [Rectangle](../../com.aspose.drawing/rectangle).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | Структура [Rectangle](../../com.aspose.drawing/rectangle), определяющая внутреннюю часть нового [Region](../../com.aspose.drawing/region). |

### Region(GraphicsPath path) {#Region-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public Region(GraphicsPath path)
```


Инициализирует новый экземпляр класса [Region](../../com.aspose.drawing/region) с указанным [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | Объект [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath), определяющий новый [Region](../../com.aspose.drawing/region). |

### Region(RegionData rgnData) {#Region-com.aspose.drawing.drawing2d.RegionData-}
```
public Region(RegionData rgnData)
```


Инициализирует новый экземпляр класса [Region](../../com.aspose.drawing/region) из указанных данных.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rgnData | [RegionData](../../com.aspose.drawing.drawing2d/regiondata) | Объект [RegionData](../../com.aspose.drawing.drawing2d/regiondata), определяющий внутреннюю часть нового [Region](../../com.aspose.drawing/region). |

### dispose() {#dispose--}
```
public void dispose()
```


Освобождает все ресурсы, используемые этим [Region](../../com.aspose.drawing/region).

### equals(Region region, Graphics g) {#equals-com.aspose.drawing.Region-com.aspose.drawing.Graphics-}
```
public boolean equals(Region region, Graphics g)
```


Проверяет, идентичен ли указанный [Region](../../com.aspose.drawing/region) этому [Region](../../com.aspose.drawing/region) на указанной поверхности рисования.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| region | [Region](../../com.aspose.drawing/region) | Тестируемый [Region](../../com.aspose.drawing/region). |
| g | [Graphics](../../com.aspose.drawing/graphics) | Объект [Graphics](../../com.aspose.drawing/graphics), представляющий поверхность для рисования. |

**Returns:**
boolean — true, если внутреннее пространство региона идентично внутреннему пространству этого региона при применении преобразования, связанного с параметром `g`; в противном случае — false.
### deepClone() {#deepClone--}
```
public Region deepClone()
```


Создаёт точную копию этого [Region](../../com.aspose.drawing/region).

**Returns:**
[Region](../../com.aspose.drawing/region) - The [Region](../../com.aspose.drawing/region) that this method creates.
### makeInfinite() {#makeInfinite--}
```
public void makeInfinite()
```


Инициализирует объект [Region](../../com.aspose.drawing/region) бесконечным внутренним пространством.

### makeEmpty() {#makeEmpty--}
```
public void makeEmpty()
```


Инициализирует этот [Region](../../com.aspose.drawing/region) пустым внутренним пространством.

### intersect(RectangleF rect) {#intersect-com.aspose.drawing.RectangleF-}
```
public void intersect(RectangleF rect)
```


Обновляет этот [Region](../../com.aspose.drawing/region), задавая его пересечение с указанной структурой [RectangleF](../../com.aspose.drawing/rectanglef).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | Структура [RectangleF](../../com.aspose.drawing/rectanglef) для пересечения с этим [Region](../../com.aspose.drawing/region). |

### intersect(Rectangle rect) {#intersect-com.aspose.drawing.Rectangle-}
```
public void intersect(Rectangle rect)
```


Обновляет этот [Region](../../com.aspose.drawing/region), задавая его пересечение с указанной структурой [Rectangle](../../com.aspose.drawing/rectangle).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | Структура [Rectangle](../../com.aspose.drawing/rectangle) для пересечения с этим [Region](../../com.aspose.drawing/region). |

### intersect(GraphicsPath path) {#intersect-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public void intersect(GraphicsPath path)
```


Обновляет этот [Region](../../com.aspose.drawing/region), задавая его пересечение с указанным [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | Объект [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) для пересечения с этим [Region](../../com.aspose.drawing/region). |

### intersect(Region region) {#intersect-com.aspose.drawing.Region-}
```
public void intersect(Region region)
```


Обновляет этот [Region](../../com.aspose.drawing/region), задавая его пересечение с указанным [Region](../../com.aspose.drawing/region).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| region | [Region](../../com.aspose.drawing/region) | [Region](../../com.aspose.drawing/region) для пересечения с этим [Region](../../com.aspose.drawing/region). |

### union(RectangleF rect) {#union-com.aspose.drawing.RectangleF-}
```
public void union(RectangleF rect)
```


Обновляет этот [Region](../../com.aspose.drawing/region), задавая его объединение с указанной структурой [RectangleF](../../com.aspose.drawing/rectanglef).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | rect | [RectangleF](../../com.aspose.drawing/rectanglef) | Структура [RectangleF](../../com.aspose.drawing/rectanglef) для объединения с этим [Region](../../com.aspose.drawing/region). |

--------------------

Объединение оставляет бесконечный регион бесконечным. |

### union(Rectangle rect) {#union-com.aspose.drawing.Rectangle-}
```
public void union(Rectangle rect)
```


Обновляет этот [Region](../../com.aspose.drawing/region), задавая его объединение с указанной структурой [Rectangle](../../com.aspose.drawing/rectangle).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | rect | [Rectangle](../../com.aspose.drawing/rectangle) | Структура [Rectangle](../../com.aspose.drawing/rectangle) для объединения с этим [Region](../../com.aspose.drawing/region). |

--------------------

Объединение оставляет бесконечный регион бесконечным. |

### union(GraphicsPath path) {#union-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public void union(GraphicsPath path)
```


Обновляет этот [Region](../../com.aspose.drawing/region), задавая его объединение с указанным [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | Объект [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) для объединения с этим [Region](../../com.aspose.drawing/region). |

--------------------

Объединение оставляет бесконечный регион бесконечным. |

### union(Region region) {#union-com.aspose.drawing.Region-}
```
public void union(Region region)
```


Обновляет этот [Region](../../com.aspose.drawing/region), задавая его объединение с указанным [Region](../../com.aspose.drawing/region).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | region | [Region](../../com.aspose.drawing/region) | [Region](../../com.aspose.drawing/region) для объединения с этим [Region](../../com.aspose.drawing/region). |

--------------------

Объединение оставляет бесконечный регион бесконечным. |

### getRegionData() {#getRegionData--}
```
public RegionData getRegionData()
```


Возвращает объект [RegionData](../../com.aspose.drawing.drawing2d/regiondata), представляющий информацию, описывающую этот [Region](../../com.aspose.drawing/region).

**Returns:**
[RegionData](../../com.aspose.drawing.drawing2d/regiondata) - A [RegionData](../../com.aspose.drawing.drawing2d/regiondata) that represents the information that describes this [Region](../../com.aspose.drawing/region).
### xor(RectangleF rect) {#xor-com.aspose.drawing.RectangleF-}
```
public void xor(RectangleF rect)
```


Обновляет этот [Region](../../com.aspose.drawing/region), задавая его объединение за вычетом пересечения с указанной структурой [RectangleF](../../com.aspose.drawing/rectanglef).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | Структура [RectangleF](../../com.aspose.drawing/rectanglef) для `M:Region.Xor(Drawing2D.GraphicsPath)` с этим [Region](../../com.aspose.drawing/region). |

### xor(Rectangle rect) {#xor-com.aspose.drawing.Rectangle-}
```
public void xor(Rectangle rect)
```


Обновляет этот [Region](../../com.aspose.drawing/region), задавая его объединение за вычетом пересечения с указанной структурой [Rectangle](../../com.aspose.drawing/rectangle).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | Структура [Rectangle](../../com.aspose.drawing/rectangle) для `M:Region.Xor(Rectangle)` с этим [Region](../../com.aspose.drawing/region). |

### xor(GraphicsPath path) {#xor-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public void xor(GraphicsPath path)
```


Обновляет этот [Region](../../com.aspose.drawing/region), задавая его объединение за вычетом пересечения с указанным [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | Объект [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) для `M:Region.Xor(GraphicsPath)` с этим [Region](../../com.aspose.drawing/region). |

### xor(Region region) {#xor-com.aspose.drawing.Region-}
```
public void xor(Region region)
```


Обновляет этот [Region](../../com.aspose.drawing/region), задавая его объединение за вычетом пересечения с указанным [Region](../../com.aspose.drawing/region).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| region | [Region](../../com.aspose.drawing/region) | [Region](../../com.aspose.drawing/region) для `M:Region.Xor(Region)` с этим [Region](../../com.aspose.drawing/region). |

### exclude(RectangleF rect) {#exclude-com.aspose.drawing.RectangleF-}
```
public void exclude(RectangleF rect)
```


Обновляет этот [Region](../../com.aspose.drawing/region), оставляя только ту часть его внутреннего пространства, которая не пересекается с указанной структурой [RectangleF](../../com.aspose.drawing/rectanglef).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | Структура [RectangleF](../../com.aspose.drawing/rectanglef) для исключения из этого [Region](../../com.aspose.drawing/region). |

### exclude(Rectangle rect) {#exclude-com.aspose.drawing.Rectangle-}
```
public void exclude(Rectangle rect)
```


Обновляет этот [Region](../../com.aspose.drawing/region), оставляя только ту часть его внутреннего пространства, которая не пересекается с указанной структурой [Rectangle](../../com.aspose.drawing/rectangle).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | Структура [Rectangle](../../com.aspose.drawing/rectangle) для исключения из этого [Region](../../com.aspose.drawing/region). |

### exclude(GraphicsPath path) {#exclude-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public void exclude(GraphicsPath path)
```


Обновляет этот [Region](../../com.aspose.drawing/region), оставляя только ту часть его внутреннего пространства, которая не пересекается с указанным [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | Объект [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) для исключения из этого [Region](../../com.aspose.drawing/region). |

### exclude(Region region) {#exclude-com.aspose.drawing.Region-}
```
public void exclude(Region region)
```


Обновляет этот [Region](../../com.aspose.drawing/region), оставляя только ту часть его внутреннего пространства, которая не пересекается с указанным [Region](../../com.aspose.drawing/region).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| region | [Region](../../com.aspose.drawing/region) | [Region](../../com.aspose.drawing/region) для исключения из этого [Region](../../com.aspose.drawing/region). |

### complement(RectangleF rect) {#complement-com.aspose.drawing.RectangleF-}
```
public void complement(RectangleF rect)
```


Обновляет этот [Region](../../com.aspose.drawing/region), оставляя часть указанной структуры [RectangleF](../../com.aspose.drawing/rectanglef), которая не пересекается с этим [Region](../../com.aspose.drawing/region).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | Структура [RectangleF](../../com.aspose.drawing/rectanglef) для дополнения этого [Region](../../com.aspose.drawing/region). |

### complement(Rectangle rect) {#complement-com.aspose.drawing.Rectangle-}
```
public void complement(Rectangle rect)
```


Обновляет этот [Region](../../com.aspose.drawing/region), оставляя часть указанной структуры [Rectangle](../../com.aspose.drawing/rectangle), которая не пересекается с этим [Region](../../com.aspose.drawing/region).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | Структура [Rectangle](../../com.aspose.drawing/rectangle) для дополнения этого [Region](../../com.aspose.drawing/region). |

### complement(GraphicsPath path) {#complement-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public void complement(GraphicsPath path)
```


Обновляет этот [Region](../../com.aspose.drawing/region), оставляя часть указанного [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath), которая не пересекается с этим [Region](../../com.aspose.drawing/region).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | Объект [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) для дополнения этого [Region](../../com.aspose.drawing/region). |

### complement(Region region) {#complement-com.aspose.drawing.Region-}
```
public void complement(Region region)
```


Обновляет этот [Region](../../com.aspose.drawing/region) так, чтобы он содержал часть указанного [Region](../../com.aspose.drawing/region), которая не пересекается с этим [Region](../../com.aspose.drawing/region).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| region | [Region](../../com.aspose.drawing/region) | Объект [Region](../../com.aspose.drawing/region) для дополнения этого объекта [Region](../../com.aspose.drawing/region). |

### translate(float dx, float dy) {#translate-float-float-}
```
public void translate(float dx, float dy)
```


Смещает координаты этого [Region](../../com.aspose.drawing/region) на указанную величину.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| dx | float | Величина смещения этого [Region](../../com.aspose.drawing/region) по горизонтали. |
| dy | float | Величина смещения этого [Region](../../com.aspose.drawing/region) по вертикали. |

### translate(int dx, int dy) {#translate-int-int-}
```
public void translate(int dx, int dy)
```


Смещает координаты этого [Region](../../com.aspose.drawing/region) на указанную величину.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| dx | int | Величина смещения этой [Region](../../com.aspose.drawing/region) по горизонтали |
| dy | int | Величина смещения этого [Region](../../com.aspose.drawing/region) по вертикали. |

### transform(Matrix matrix) {#transform-com.aspose.drawing.drawing2d.Matrix-}
```
public void transform(Matrix matrix)
```


Преобразует этот [Region](../../com.aspose.drawing/region) с помощью указанной [Matrix](../../com.aspose.drawing.drawing2d/matrix).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | Матрица [Matrix](../../com.aspose.drawing.drawing2d/matrix), с помощью которой преобразовать эту [Region](../../com.aspose.drawing/region). |

### getBounds(Graphics g) {#getBounds-com.aspose.drawing.Graphics-}
```
public RectangleF getBounds(Graphics g)
```


Получает структуру [RectangleF](../../com.aspose.drawing/rectanglef), представляющую прямоугольник, ограничивающий этот [Region](../../com.aspose.drawing/region) на поверхности рисования объекта [Graphics](../../com.aspose.drawing/graphics).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| g | [Graphics](../../com.aspose.drawing/graphics) | Графический объект [Graphics](../../com.aspose.drawing/graphics), на котором рисуется эта [Region](../../com.aspose.drawing/region). |

**Returns:**
[RectangleF](../../com.aspose.drawing/rectanglef) - A [RectangleF](../../com.aspose.drawing/rectanglef) structure that represents the bounding rectangle for this [Region](../../com.aspose.drawing/region) on the specified drawing surface.
### getRegionScans(Matrix matrix) {#getRegionScans-com.aspose.drawing.drawing2d.Matrix-}
```
public RectangleF[] getRegionScans(Matrix matrix)
```


Возвращает массив структур [RectangleF](../../com.aspose.drawing/rectanglef), приближающих этот [Region](../../com.aspose.drawing/region) после применения указанного преобразования матрицы.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | Матрица [Matrix](../../com.aspose.drawing.drawing2d/matrix), представляющая геометрическое преобразование, применяемое к региону. |

**Returns:**
com.aspose.drawing.RectangleF[] — массив структур [RectangleF](../../com.aspose.drawing/rectanglef), приближающих эту [Region](../../com.aspose.drawing/region) после применения указанного преобразования матрицы.
### isEmpty(Graphics g) {#isEmpty-com.aspose.drawing.Graphics-}
```
public boolean isEmpty(Graphics g)
```


Проверяет, имеет ли этот [Region](../../com.aspose.drawing/region) пустой внутренний участок на указанной поверхности рисования.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| g | [Graphics](../../com.aspose.drawing/graphics) | Объект [Graphics](../../com.aspose.drawing/graphics), представляющий поверхность для рисования. |

**Returns:**
boolean — true, если внутреннее пространство этой [Region](../../com.aspose.drawing/region) пусто при применении преобразования, связанного с `g`; иначе false.
### isInfinite(Graphics g) {#isInfinite-com.aspose.drawing.Graphics-}
```
public boolean isInfinite(Graphics g)
```


Проверяет, имеет ли этот [Region](../../com.aspose.drawing/region) бесконечный внутренний участок на указанной поверхности рисования.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| g | [Graphics](../../com.aspose.drawing/graphics) | Объект [Graphics](../../com.aspose.drawing/graphics), представляющий поверхность для рисования. |

**Returns:**
boolean — true, если внутреннее пространство этой [Region](../../com.aspose.drawing/region) бесконечно при применении преобразования, связанного с `g`; иначе false.
### isVisible(float x, float y) {#isVisible-float-float-}
```
public boolean isVisible(float x, float y)
```


Проверяет, содержится ли указанная точка внутри этого [Region](../../com.aspose.drawing/region).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | float | Координата x точки, которую нужно проверить. |
| y | float | Координата Y точки для проверки. |

**Returns:**
boolean — true, когда указанная точка находится внутри этой [Region](../../com.aspose.drawing/region); иначе false.
### isVisible(PointF point) {#isVisible-com.aspose.drawing.PointF-}
```
public boolean isVisible(PointF point)
```


Проверяет, содержится ли указанная структура [PointF](../../com.aspose.drawing/pointf) внутри этого [Region](../../com.aspose.drawing/region).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| point | [PointF](../../com.aspose.drawing/pointf) | Структура [PointF](../../com.aspose.drawing/pointf) для проверки. |

**Returns:**
boolean — true, когда `point` находится внутри этой [Region](../../com.aspose.drawing/region); иначе false.
### isVisible(float x, float y, Graphics g) {#isVisible-float-float-com.aspose.drawing.Graphics-}
```
public boolean isVisible(float x, float y, Graphics g)
```


Проверяет, содержится ли указанная точка внутри этого [Region](../../com.aspose.drawing/region), когда он отрисовывается с использованием указанного [Graphics](../../com.aspose.drawing/graphics).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | float | Координата x точки, которую нужно проверить. |
| y | float | Координата Y точки для проверки. |
| g | [Graphics](../../com.aspose.drawing/graphics) | Объект [Graphics](../../com.aspose.drawing/graphics), представляющий графический контекст. |

**Returns:**
boolean — true, когда указанная точка находится внутри этой [Region](../../com.aspose.drawing/region); иначе false.
### isVisible(PointF point, Graphics g) {#isVisible-com.aspose.drawing.PointF-com.aspose.drawing.Graphics-}
```
public boolean isVisible(PointF point, Graphics g)
```


Проверяет, содержится ли указанная структура [PointF](../../com.aspose.drawing/pointf) внутри этого [Region](../../com.aspose.drawing/region), когда он отрисовывается с использованием указанного [Graphics](../../com.aspose.drawing/graphics).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| point | [PointF](../../com.aspose.drawing/pointf) | Структура [PointF](../../com.aspose.drawing/pointf) для проверки. |
| g | [Graphics](../../com.aspose.drawing/graphics) | Объект [Graphics](../../com.aspose.drawing/graphics), представляющий графический контекст. |

**Returns:**
boolean — true, когда `point` находится внутри этой [Region](../../com.aspose.drawing/region); иначе false.
### isVisible(float x, float y, float width, float height) {#isVisible-float-float-float-float-}
```
public boolean isVisible(float x, float y, float width, float height)
```


Проверяет, содержится ли какая‑либо часть указанного прямоугольника внутри этого [Region](../../com.aspose.drawing/region).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | float | Координата x левого верхнего угла проверяемого прямоугольника. |
| y | float | Координата y левого верхнего угла проверяемого прямоугольника. |
| width | float | Ширина проверяемого прямоугольника. |
| height | float | Высота проверяемого прямоугольника. |

**Returns:**
boolean — true, когда любая часть указанного прямоугольника находится внутри объекта [Region](../../com.aspose.drawing/region); иначе false.
### isVisible(RectangleF rect) {#isVisible-com.aspose.drawing.RectangleF-}
```
public boolean isVisible(RectangleF rect)
```


Проверяет, содержится ли какая‑либо часть указанной структуры [RectangleF](../../com.aspose.drawing/rectanglef) внутри этого [Region](../../com.aspose.drawing/region).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | Структура [RectangleF](../../com.aspose.drawing/rectanglef) для проверки. |

**Returns:**
boolean — true, когда любая часть `rect` находится внутри этой [Region](../../com.aspose.drawing/region); иначе false.
### isVisible(float x, float y, float width, float height, Graphics g) {#isVisible-float-float-float-float-com.aspose.drawing.Graphics-}
```
public boolean isVisible(float x, float y, float width, float height, Graphics g)
```


Проверяет, содержится ли какая‑либо часть указанного прямоугольника внутри этого [Region](../../com.aspose.drawing/region), когда он отрисовывается с использованием указанного [Graphics](../../com.aspose.drawing/graphics).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | float | Координата x левого верхнего угла проверяемого прямоугольника. |
| y | float | Координата y левого верхнего угла проверяемого прямоугольника. |
| width | float | Ширина проверяемого прямоугольника. |
| height | float | Высота проверяемого прямоугольника. |
| g | [Graphics](../../com.aspose.drawing/graphics) | Объект [Graphics](../../com.aspose.drawing/graphics), представляющий графический контекст. |

**Returns:**
boolean — true, когда любая часть указанного прямоугольника находится внутри этой [Region](../../com.aspose.drawing/region); иначе false.
### isVisible(RectangleF rect, Graphics g) {#isVisible-com.aspose.drawing.RectangleF-com.aspose.drawing.Graphics-}
```
public boolean isVisible(RectangleF rect, Graphics g)
```


Проверяет, содержится ли какая‑либо часть указанной структуры [RectangleF](../../com.aspose.drawing/rectanglef) внутри этого [Region](../../com.aspose.drawing/region), когда он отрисовывается с использованием указанного [Graphics](../../com.aspose.drawing/graphics).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | Структура [RectangleF](../../com.aspose.drawing/rectanglef) для проверки. |
| g | [Graphics](../../com.aspose.drawing/graphics) | Объект [Graphics](../../com.aspose.drawing/graphics), представляющий графический контекст. |

**Returns:**
boolean — true, когда `rect` находится внутри этой [Region](../../com.aspose.drawing/region); иначе false.
### isVisible(int x, int y, Graphics g) {#isVisible-int-int-com.aspose.drawing.Graphics-}
```
public boolean isVisible(int x, int y, Graphics g)
```


Проверяет, содержится ли указанная точка внутри объекта [Region](../../com.aspose.drawing/region), когда он отрисовывается с использованием указанного объекта [Graphics](../../com.aspose.drawing/graphics).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | int | Координата x точки, которую нужно проверить. |
| y | int | Координата Y точки для проверки. |
| g | [Graphics](../../com.aspose.drawing/graphics) | Объект [Graphics](../../com.aspose.drawing/graphics), представляющий графический контекст. |

**Returns:**
boolean — true, когда указанная точка находится внутри этой [Region](../../com.aspose.drawing/region); иначе false.
### isVisible(Point point) {#isVisible-com.aspose.drawing.Point-}
```
public boolean isVisible(Point point)
```


Проверяет, содержится ли указанная структура [Point](../../com.aspose.drawing/point) внутри этого [Region](../../com.aspose.drawing/region).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| point | [Point](../../com.aspose.drawing/point) | Структура [Point](../../com.aspose.drawing/point) для проверки. |

**Returns:**
boolean — true, когда `point` находится внутри этой [Region](../../com.aspose.drawing/region); иначе false.
### isVisible(Point point, Graphics g) {#isVisible-com.aspose.drawing.Point-com.aspose.drawing.Graphics-}
```
public boolean isVisible(Point point, Graphics g)
```


Проверяет, содержится ли указанная структура [Point](../../com.aspose.drawing/point) внутри этого [Region](../../com.aspose.drawing/region), когда он отрисовывается с использованием указанного [Graphics](../../com.aspose.drawing/graphics).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| point | [Point](../../com.aspose.drawing/point) | Структура [Point](../../com.aspose.drawing/point) для проверки. |
| g | [Graphics](../../com.aspose.drawing/graphics) | Объект [Graphics](../../com.aspose.drawing/graphics), представляющий графический контекст. |

**Returns:**
boolean — true, когда `point` находится внутри этой [Region](../../com.aspose.drawing/region); иначе false.
### isVisible(int x, int y, int width, int height) {#isVisible-int-int-int-int-}
```
public boolean isVisible(int x, int y, int width, int height)
```


Проверяет, содержится ли какая‑либо часть указанного прямоугольника внутри этого [Region](../../com.aspose.drawing/region).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | int | Координата x левого верхнего угла проверяемого прямоугольника. |
| y | int | Координата y левого верхнего угла проверяемого прямоугольника. |
| width | int | Ширина проверяемого прямоугольника. |
| height | int | Высота проверяемого прямоугольника. |

**Returns:**
boolean — true, когда любая часть указанного прямоугольника находится внутри этой [Region](../../com.aspose.drawing/region); иначе false.
### isVisible(Rectangle rect) {#isVisible-com.aspose.drawing.Rectangle-}
```
public boolean isVisible(Rectangle rect)
```


Проверяет, содержится ли какая‑либо часть указанной структуры [Rectangle](../../com.aspose.drawing/rectangle) внутри этого [Region](../../com.aspose.drawing/region).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | Структура [Rectangle](../../com.aspose.drawing/rectangle) для проверки. |

**Returns:**
boolean — Этот метод возвращает true, когда любая часть `rect` находится внутри этой [Region](../../com.aspose.drawing/region); иначе false.
### isVisible(int x, int y, int width, int height, Graphics g) {#isVisible-int-int-int-int-com.aspose.drawing.Graphics-}
```
public boolean isVisible(int x, int y, int width, int height, Graphics g)
```


Проверяет, содержится ли какая‑либо часть указанного прямоугольника внутри этого [Region](../../com.aspose.drawing/region), когда он отрисовывается с использованием указанного [Graphics](../../com.aspose.drawing/graphics).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | int | Координата x левого верхнего угла проверяемого прямоугольника. |
| y | int | Координата y левого верхнего угла проверяемого прямоугольника. |
| width | int | Ширина проверяемого прямоугольника. |
| height | int | Высота проверяемого прямоугольника. |
| g | [Graphics](../../com.aspose.drawing/graphics) | Объект [Graphics](../../com.aspose.drawing/graphics), представляющий графический контекст. |

**Returns:**
boolean — true, когда любая часть указанного прямоугольника находится внутри этой [Region](../../com.aspose.drawing/region); иначе false.
### isVisible(Rectangle rect, Graphics g) {#isVisible-com.aspose.drawing.Rectangle-com.aspose.drawing.Graphics-}
```
public boolean isVisible(Rectangle rect, Graphics g)
```


Проверяет, содержится ли какая‑либо часть указанной структуры [Rectangle](../../com.aspose.drawing/rectangle) внутри этого [Region](../../com.aspose.drawing/region), когда он отрисовывается с использованием указанного [Graphics](../../com.aspose.drawing/graphics).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | Структура [Rectangle](../../com.aspose.drawing/rectangle) для проверки. |
| g | [Graphics](../../com.aspose.drawing/graphics) | Объект [Graphics](../../com.aspose.drawing/graphics), представляющий графический контекст. |

**Returns:**
boolean — true, когда любая часть `rect` находится внутри этой [Region](../../com.aspose.drawing/region); иначе false.
