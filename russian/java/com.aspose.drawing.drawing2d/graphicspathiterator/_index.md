---
title: GraphicsPathIterator
second_title: Справочник API Aspose.Drawing для Java
description: Обеспечивает возможность перебора подпутей в  и тестировать типы фигур, содержащихся в каждом подпуте.
type: docs
weight: 24
url: /ru/java/com.aspose.drawing.drawing2d/graphicspathiterator/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public final class GraphicsPathIterator implements System.IDisposable
```

Обеспечивает возможность перебора подпутей в [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) и проверки типов фигур, содержащихся в каждой подпуте. Этот класс не может быть наследован.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [GraphicsPathIterator(GraphicsPath path)](#GraphicsPathIterator-com.aspose.drawing.drawing2d.GraphicsPath-) | Инициализирует новый экземпляр класса [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator). |
## Методы

| Метод | Описание |
| --- | --- |
| [getCount()](#getCount--) | Возвращает количество точек в пути. |
| [getSubpathCount()](#getSubpathCount--) | Возвращает количество подпутей в пути. |
| [dispose()](#dispose--) | Выполняет задачи, определённые приложением, связанные с освобождением, выпуском или сбросом неуправляемых ресурсов. |
| [copyData(PointF[][] points, byte[][] types, int startIndex, int endIndex)](#copyData-com.aspose.drawing.PointF-----byte-----int-int-) | Копирует массивы свойств GraphicsPath.PathPoints и GraphicsPath.PathTypes связанного [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) в два указанных массива. |
| [enumerate(PointF[][] points, byte[][] types)](#enumerate-com.aspose.drawing.PointF-----byte-----) | Копирует массивы свойств GraphicsPath.PathPoints и GraphicsPath.PathTypes связанного [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) в два указанных массива. |
| [hasCurve()](#hasCurve--) | Указывает, содержит ли путь, связанный с этим [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator), кривую. |
| [nextMarker(int[] startIndex, int[] endIndex)](#nextMarker-int---int---) | Перемещает [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) к следующему маркеру в пути и возвращает начальный и конечный индексы через параметры [out]. |
| [nextMarker(GraphicsPath path)](#nextMarker-com.aspose.drawing.drawing2d.GraphicsPath-) | Этот объект [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) связан с объектом [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath). |
| [nextPathType(byte[] pathType, int[] startIndex, int[] endIndex)](#nextPathType-byte---int---int---) | Возвращает начальный и конечный индексы следующей группы точек данных, имеющих одинаковый тип. |
| [nextSubpath(int[] startIndex, int[] endIndex, boolean[] isClosed)](#nextSubpath-int---int---boolean---) | Перемещает [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) к следующей подпуте в пути. |
| [nextSubpath(GraphicsPath path, boolean[] isClosed)](#nextSubpath-com.aspose.drawing.drawing2d.GraphicsPath-boolean---) | Возвращает следующую фигуру (подпуть) из связанного пути этого [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator). |
| [rewind()](#rewind--) | Перематывает этот [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) к началу его связанного пути. |
### GraphicsPathIterator(GraphicsPath path) {#GraphicsPathIterator-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public GraphicsPathIterator(GraphicsPath path)
```


Инициализирует новый экземпляр класса [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | Объект [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath), для которого инициализируется этот вспомогательный класс. |

### getCount() {#getCount--}
```
public int getCount()
```


Возвращает количество точек в пути.

**Returns:**
int — количество точек в пути.
### getSubpathCount() {#getSubpathCount--}
```
public int getSubpathCount()
```


Возвращает количество подпутей в пути.

**Returns:**
int — количество подпутей в пути.
### dispose() {#dispose--}
```
public void dispose()
```


Выполняет задачи, определённые приложением, связанные с освобождением, выпуском или сбросом неуправляемых ресурсов.

### copyData(PointF[][] points, byte[][] types, int startIndex, int endIndex) {#copyData-com.aspose.drawing.PointF-----byte-----int-int-}
```
public int copyData(PointF[][] points, byte[][] types, int startIndex, int endIndex)
```


Копирует массивы свойств GraphicsPath.PathPoints и GraphicsPath.PathTypes связанного [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) в два указанных массива.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.drawing/pointf) | После возврата содержит массив структур System.Drawing.PointF, представляющих точки в пути. |
| типы | byte[][] | После возврата содержит массив байтов, представляющий типы точек в пути. |
| startIndex | int | Указывает начальный индекс массивов. |
| endIndex | int | Указывает конечный индекс массивов. |

**Returns:**
int — количество скопированных точек.
### enumerate(PointF[][] points, byte[][] types) {#enumerate-com.aspose.drawing.PointF-----byte-----}
```
public int enumerate(PointF[][] points, byte[][] types)
```


Копирует массивы свойств GraphicsPath.PathPoints и GraphicsPath.PathTypes связанного [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) в два указанных массива.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.drawing/pointf) | После возврата содержит массив структур System.Drawing.PointF, представляющих точки в пути. |
| типы | byte[][] | После возврата содержит массив байтов, представляющий типы точек в пути. |

**Returns:**
int — количество скопированных точек.
### hasCurve() {#hasCurve--}
```
public boolean hasCurve()
```


Указывает, содержит ли путь, связанный с этим [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator), кривую.

**Returns:**
boolean - Этот метод возвращает true, если текущий подпуть содержит кривую; в противном случае — false.
### nextMarker(int[] startIndex, int[] endIndex) {#nextMarker-int---int---}
```
public int nextMarker(int[] startIndex, int[] endIndex)
```


Перемещает [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) к следующему маркеру в пути и возвращает начальный и конечный индексы через параметры [out].

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| startIndex | int[] | [out] Целочисленная ссылка, переданная в этот параметр, получает индекс точки, которая начинается подпуть. |
| endIndex | int[] | [out] Целочисленная ссылка, переданная в этот параметр, получает индекс точки, которая завершает подпуть, на который указывает startIndex. |

**Returns:**
int - Количество точек между этим маркером и следующим.
### nextMarker(GraphicsPath path) {#nextMarker-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public int nextMarker(GraphicsPath path)
```


Этот объект [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) имеет связанный объект [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath). Этот метод перемещает связанный [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) к следующему маркеру в его пути и копирует все точки, находящиеся между текущим маркером и следующим маркером (или концом пути), во второй объект [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath), переданный в параметр.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | Объект [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath), в который будут скопированы точки. |

**Returns:**
int - Количество точек между этим маркером и следующим.
### nextPathType(byte[] pathType, int[] startIndex, int[] endIndex) {#nextPathType-byte---int---int---}
```
public int nextPathType(byte[] pathType, int[] startIndex, int[] endIndex)
```


Возвращает начальный и конечный индексы следующей группы точек данных, имеющих одинаковый тип.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pathType | byte[] | [out] Принимает тип точки, общий для всех точек в группе. Возможные типы можно получить из перечисления [PathPointType](../../com.aspose.drawing.drawing2d/pathpointtype). |
| startIndex | int[] | [out] Принимает начальный индекс группы точек. |
| endIndex | int[] | [out] Принимает конечный индекс группы точек. |

**Returns:**
int - Этот метод возвращает количество точек данных в группе. Если в пути больше нет групп, метод возвращает 0.
### nextSubpath(int[] startIndex, int[] endIndex, boolean[] isClosed) {#nextSubpath-int---int---boolean---}
```
public int nextSubpath(int[] startIndex, int[] endIndex, boolean[] isClosed)
```


Перемещает [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) к следующему подпутю в пути. Начальный и конечный индексы следующего подпути находятся в параметрах [out].

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| startIndex | int[] | [out] Принимает начальный индекс следующего подпути. |
| endIndex | int[] | [out] Принимает конечный индекс следующего подпути. |
| isClosed | boolean[] | [out] Указывает, закрыт ли подпуть. |

**Returns:**
int - Количество точек данных в полученной фигуре (подпути). Если больше нет фигур для получения, возвращается ноль.
### nextSubpath(GraphicsPath path, boolean[] isClosed) {#nextSubpath-com.aspose.drawing.drawing2d.GraphicsPath-boolean---}
```
public int nextSubpath(GraphicsPath path, boolean[] isClosed)
```


Возвращает следующую фигуру (подпуть) из связанного пути этого [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | Объект [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath), у которого точки данных должны быть установлены в соответствии с точками данных полученной фигуры (подпути) для этого итератора. |
| isClosed | boolean[] | [out] Указывает, закрыт ли текущий подпуть. Значение true, если фигура закрыта, иначе false. |

**Returns:**
int - Количество точек данных в полученной фигуре (подпути). Если больше нет фигур для получения, возвращается ноль.
### rewind() {#rewind--}
```
public void rewind()
```


Перематывает этот [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) к началу его связанного пути.

