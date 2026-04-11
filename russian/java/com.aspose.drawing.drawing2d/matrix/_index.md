---
title: Matrix
second_title: Справочник API Aspose.Drawing для Java
description: Инкапсулирует аффинную матрицу 3×3, представляющую геометрическое преобразование.
type: docs
weight: 33
url: /ru/java/com.aspose.drawing.drawing2d/matrix/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public final class Matrix implements System.IDisposable
```

Инкапсулирует аффинную матрицу 3×3, представляющую геометрическое преобразование. Этот класс не может быть наследован.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Matrix()](#Matrix--) | Инициализирует новый экземпляр класса Matrix как единичную матрицу. |
| [Matrix(float m11, float m12, float m21, float m22, float dx, float dy)](#Matrix-float-float-float-float-float-float-) | Инициализирует новый экземпляр класса Matrix с указанными элементами. |
| [Matrix(Rectangle rect, Point[] plgpts)](#Matrix-com.aspose.drawing.Rectangle-com.aspose.drawing.Point---) | Инициализирует новый экземпляр класса [Matrix](../../com.aspose.drawing.drawing2d/matrix) в геометрическое преобразование, определённое указанным прямоугольником и массивом точек. |
| [Matrix(RectangleF rect, PointF[] plgpts)](#Matrix-com.aspose.drawing.RectangleF-com.aspose.drawing.PointF---) | Инициализирует новый экземпляр класса [Matrix](../../com.aspose.drawing.drawing2d/matrix) в геометрическое преобразование, определённое указанным прямоугольником и массивом точек. |
## Поля

| Поле | Описание |
| --- | --- |
| [IdentityTransform](#IdentityTransform) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getElements()](#getElements--) | Возвращает массив чисел с плавающей запятой, представляющих элементы этой матрицы. |
| [isIdentity()](#isIdentity--) | Возвращает значение, указывающее, является ли эта матрица единичной. |
| [isInvertible()](#isInvertible--) | Возвращает значение, указывающее, является ли эта матрица обратимой. |
| [getOffsetX()](#getOffsetX--) | Получает значение трансляции по оси x (значение dx или элемент в третьей строке и первом столбце) этой Matrix. |
| [getOffsetY()](#getOffsetY--) | Получает значение трансляции по оси y (значение `dy` или элемент в третьей строке и втором столбце) этой Matrix. |
| [dispose()](#dispose--) | Освобождает все ресурсы, используемые этой Matrix. |
| [deepClone()](#deepClone--) | Создаёт точную копию этой Matrix. |
| [invert()](#invert--) | Инвертирует эту Matrix, если она обратима. |
| [translate(float offsetX, float offsetY)](#translate-float-float-) | Применяет указанный вектор трансляции (offsetX и offsetY) к этой Matrix, предварительно добавляя вектор трансляции. |
| [translate(float offsetX, float offsetY, int order)](#translate-float-float-int-) | Применяет указанный вектор трансляции к этой Matrix в указанном порядке. |
| [transformVectors(PointF[] pts)](#transformVectors-com.aspose.drawing.PointF---) | Умножает каждый вектор в массиве на матрицу. |
| [scale(float scaleX, float scaleY)](#scale-float-float-) | Применяет указанный вектор масштабирования к этой Matrix, предварительно добавляя вектор масштабирования. |
| [scale(float scaleX, float scaleY, int order)](#scale-float-float-int-) | Применяет указанный вектор масштабирования (scaleX и scaleY) к этой Matrix, используя указанный порядок. |
| [shear(float shearX, float shearY)](#shear-float-float-) | Применяет указанный вектор сдвига к этой Matrix, предварительно добавляя трансформацию сдвига. |
| [shear(float shearX, float shearY, int order)](#shear-float-float-int-) | Применяет указанный вектор сдвига к этой Matrix в указанном порядке. |
| [rotateAt(float angle, PointF point)](#rotateAt-float-com.aspose.drawing.PointF-) | Применяет вращение по часовой стрелке к этой Matrix вокруг точки, указанной в параметре point, предварительно добавляя вращение. |
| [rotateAt(float angle, PointF point, int order)](#rotateAt-float-com.aspose.drawing.PointF-int-) | Применяет вращение по часовой стрелке вокруг указанной точки к этой Matrix в указанном порядке. |
| [transformPoints(PointF[] pts)](#transformPoints-com.aspose.drawing.PointF---) | Применяет геометрическое преобразование, представленное этой [Matrix](../../com.aspose.drawing.drawing2d/matrix), к указанному массиву точек. |
| [transformPoints(Point[] pts)](#transformPoints-com.aspose.drawing.Point---) | Применяет геометрическое преобразование, представленное этой [Matrix](../../com.aspose.drawing.drawing2d/matrix), к указанному массиву точек. |
| [multiply(Matrix matrix)](#multiply-com.aspose.drawing.drawing2d.Matrix-) | Умножает эту [Matrix](../../com.aspose.drawing.drawing2d/matrix) на матрицу, указанную в параметре `matrix`, предварительно добавляя указанную [Matrix](../../com.aspose.drawing.drawing2d/matrix). |
| [multiply(Matrix matrix, int order)](#multiply-com.aspose.drawing.drawing2d.Matrix-int-) | Умножает эту [Matrix](../../com.aspose.drawing.drawing2d/matrix) на матрицу, указанную в параметре `matrix`, и в порядке, указанном в параметре `order`. |
| [rotate(float angle)](#rotate-float-) | Предварительно добавить к этой [Matrix](../../com.aspose.drawing.drawing2d/matrix) вращение по часовой стрелке вокруг начала координат с указанным углом. |
| [rotate(float angle, int order)](#rotate-float-int-) | Применяет вращение по часовой стрелке на угол, указанный в параметре angle, вокруг начала координат (ноль по x и y) для этой [Matrix](../../com.aspose.drawing.drawing2d/matrix). |
| [reset()](#reset--) | Сбрасывает эту [Matrix](../../com.aspose.drawing.drawing2d/matrix), чтобы она имела элементы единичной матрицы. |
### Matrix() {#Matrix--}
```
public Matrix()
```


Инициализирует новый экземпляр класса Matrix как единичную матрицу.

### Matrix(float m11, float m12, float m21, float m22, float dx, float dy) {#Matrix-float-float-float-float-float-float-}
```
public Matrix(float m11, float m12, float m21, float m22, float dx, float dy)
```


Инициализирует новый экземпляр класса Matrix с указанными элементами.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| m11 | float | Значение в первой строке и первом столбце новой Matrix. |
| m12 | float | Значение в первой строке и втором столбце новой Matrix. |
| m21 | float | Значение во второй строке и первом столбце новой матрицы. |
| m22 | float | Значение во второй строке и втором столбце новой матрицы. |
| dx | float | Значение в третьей строке и первом столбце новой матрицы. |
| dy | float | Значение в третьей строке и втором столбце новой матрицы. |

### Matrix(Rectangle rect, Point[] plgpts) {#Matrix-com.aspose.drawing.Rectangle-com.aspose.drawing.Point---}
```
public Matrix(Rectangle rect, Point[] plgpts)
```


Инициализирует новый экземпляр класса [Matrix](../../com.aspose.drawing.drawing2d/matrix) в геометрическое преобразование, определённое указанным прямоугольником и массивом точек.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | Структура [Rectangle](../../com.aspose.drawing/rectangle), представляющая прямоугольник, который будет преобразован. |
| plgpts | [Point\[\]](../../com.aspose.drawing/point) | Массив из трёх структур [Point](../../com.aspose.drawing/point), представляющих точки параллелограмма, в который будут преобразованы верхний‑левый, верхний‑правый и нижний‑левый углы прямоугольника. Нижний‑правый угол параллелограмма подразумевается первыми тремя углами. |

### Matrix(RectangleF rect, PointF[] plgpts) {#Matrix-com.aspose.drawing.RectangleF-com.aspose.drawing.PointF---}
```
public Matrix(RectangleF rect, PointF[] plgpts)
```


Инициализирует новый экземпляр класса [Matrix](../../com.aspose.drawing.drawing2d/matrix) в геометрическое преобразование, определённое указанным прямоугольником и массивом точек.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.drawing/rectanglef) | Структура [RectangleF](../../com.aspose.drawing/rectanglef), представляющая прямоугольник, который будет преобразован. |
| plgpts | [PointF\[\]](../../com.aspose.drawing/pointf) | Массив из трёх структур [PointF](../../com.aspose.drawing/pointf), представляющих точки параллелограмма, в который будут преобразованы верхний‑левый, верхний‑правый и нижний‑левый углы прямоугольника. Нижний‑правый угол параллелограмма подразумевается первыми тремя углами. |

### IdentityTransform {#IdentityTransform}
```
public static final Matrix IdentityTransform
```


### getElements() {#getElements--}
```
public float[] getElements()
```


Возвращает массив чисел с плавающей запятой, представляющих элементы этой матрицы.

**Returns:**
float[] — массив чисел с плавающей запятой, представляющий элементы этой матрицы.
### isIdentity() {#isIdentity--}
```
public boolean isIdentity()
```


Возвращает значение, указывающее, является ли эта матрица единичной.

**Returns:**
boolean — значение, указывающее, является ли эта матрица единичной.
### isInvertible() {#isInvertible--}
```
public boolean isInvertible()
```


Возвращает значение, указывающее, является ли эта матрица обратимой.

**Returns:**
boolean — значение, указывающее, обратима ли эта матрица.
### getOffsetX() {#getOffsetX--}
```
public float getOffsetX()
```


Получает значение трансляции по оси x (значение dx или элемент в третьей строке и первом столбце) этой Matrix.

**Returns:**
float — значение трансляции по оси x (значение dx, или элемент в третьей строке и первом столбце) этой матрицы.
### getOffsetY() {#getOffsetY--}
```
public float getOffsetY()
```


Получает значение трансляции по оси y (значение `dy` или элемент в третьей строке и втором столбце) этой Matrix.

**Returns:**
float — значение трансляции по оси y (значение `dy`, или элемент в третьей строке и втором столбце) этой матрицы.
### dispose() {#dispose--}
```
public void dispose()
```


Освобождает все ресурсы, используемые этой Matrix.

--------------------

Этот метод фактически ничего не делает. Он нужен только для совместимости с API System.Drawing.

### deepClone() {#deepClone--}
```
public Matrix deepClone()
```


Создаёт точную копию этой Matrix.

**Returns:**
[Matrix](../../com.aspose.drawing.drawing2d/matrix) - The Matrix that this method creates.
### invert() {#invert--}
```
public void invert()
```


Инвертирует эту Matrix, если она обратима.

### translate(float offsetX, float offsetY) {#translate-float-float-}
```
public void translate(float offsetX, float offsetY)
```


Применяет указанный вектор трансляции (offsetX и offsetY) к этой Matrix, предварительно добавляя вектор трансляции.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| offsetX | float | Значение x, на которое следует трансформировать эту матрицу. |
| offsetY | float | Значение y, на которое следует трансформировать эту матрицу. |

### translate(float offsetX, float offsetY, int order) {#translate-float-float-int-}
```
public void translate(float offsetX, float offsetY, int order)
```


Применяет указанный вектор трансляции к этой Matrix в указанном порядке.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| offsetX | float | Значение x, на которое следует трансформировать эту матрицу. |
| offsetY | float | Значение y, на которое следует трансформировать эту матрицу. |
| порядок | int | MatrixOrder, указывающий порядок (добавление в конец или в начало), в котором трансляция применяется к этой матрице. |

### transformVectors(PointF[] pts) {#transformVectors-com.aspose.drawing.PointF---}
```
public void transformVectors(PointF[] pts)
```


Умножает каждый вектор в массиве на матрицу. Элементы трансляции этой матрицы (третья строка) игнорируются.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pts | [PointF\[\]](../../com.aspose.drawing/pointf) | Массив структур [PointF](../../com.aspose.drawing/pointf), представляющих точки для преобразования. |

### scale(float scaleX, float scaleY) {#scale-float-float-}
```
public void scale(float scaleX, float scaleY)
```


Применяет указанный вектор масштабирования к этой Matrix, предварительно добавляя вектор масштабирования.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| scaleX | float | Значение, на которое следует масштабировать эту матрицу по оси x. |
| scaleY | float | Значение, на которое следует масштабировать эту Matrix по оси y. |

### scale(float scaleX, float scaleY, int order) {#scale-float-float-int-}
```
public void scale(float scaleX, float scaleY, int order)
```


Применяет указанный вектор масштабирования (scaleX и scaleY) к этой Matrix, используя указанный порядок.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| scaleX | float | Значение, на которое следует масштабировать эту матрицу по оси x. |
| scaleY | float | Значение, на которое следует масштабировать эту Matrix по оси y. |
| порядок | int | MatrixOrder, который указывает порядок (добавление в конец или в начало), в котором вектор масштабирования применяется к этой Matrix. |

### shear(float shearX, float shearY) {#shear-float-float-}
```
public void shear(float shearX, float shearY)
```


Применяет указанный вектор сдвига к этой Matrix, предварительно добавляя трансформацию сдвига.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| shearX | float | Горизонтальный коэффициент сдвига. |
| shearY | float | Вертикальный коэффициент сдвига. |

### shear(float shearX, float shearY, int order) {#shear-float-float-int-}
```
public void shear(float shearX, float shearY, int order)
```


Применяет указанный вектор сдвига к этой Matrix в указанном порядке.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| shearX | float | Горизонтальный коэффициент сдвига. |
| shearY | float | Вертикальный коэффициент сдвига. |
| порядок | int | MatrixOrder, который указывает порядок (добавление в конец или в начало), в котором применяется сдвиг. |

### rotateAt(float angle, PointF point) {#rotateAt-float-com.aspose.drawing.PointF-}
```
public void rotateAt(float angle, PointF point)
```


Применяет вращение по часовой стрелке к этой Matrix вокруг точки, указанной в параметре point, предварительно добавляя вращение.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| угол | float | Угол (размах) вращения в градусах. |
| point | [PointF](../../com.aspose.drawing/pointf) | PointF, представляющий центр вращения. |

### rotateAt(float angle, PointF point, int order) {#rotateAt-float-com.aspose.drawing.PointF-int-}
```
public void rotateAt(float angle, PointF point, int order)
```


Применяет вращение по часовой стрелке вокруг указанной точки к этой Matrix в указанном порядке.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| угол | float | Угол вращения в градусах. |
| point | [PointF](../../com.aspose.drawing/pointf) | PointF, представляющий центр вращения. |
| порядок | int | MatrixOrder, который указывает порядок (добавление в конец или в начало), в котором применяется вращение. |

### transformPoints(PointF[] pts) {#transformPoints-com.aspose.drawing.PointF---}
```
public void transformPoints(PointF[] pts)
```


Применяет геометрическое преобразование, представленное этой [Matrix](../../com.aspose.drawing.drawing2d/matrix), к указанному массиву точек.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pts | [PointF\[\]](../../com.aspose.drawing/pointf) | Массив структур [PointF](../../com.aspose.drawing/pointf), представляющих точки для преобразования. |

### transformPoints(Point[] pts) {#transformPoints-com.aspose.drawing.Point---}
```
public void transformPoints(Point[] pts)
```


Применяет геометрическое преобразование, представленное этой [Matrix](../../com.aspose.drawing.drawing2d/matrix), к указанному массиву точек.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pts | [Point\[\]](../../com.aspose.drawing/point) | Массив структур [Point](../../com.aspose.drawing/point), представляющих точки для преобразования. |

### multiply(Matrix matrix) {#multiply-com.aspose.drawing.drawing2d.Matrix-}
```
public void multiply(Matrix matrix)
```


Умножает эту [Matrix](../../com.aspose.drawing.drawing2d/matrix) на матрицу, указанную в параметре `matrix`, предварительно добавляя указанную [Matrix](../../com.aspose.drawing.drawing2d/matrix).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | Матрица [Matrix](../../com.aspose.drawing.drawing2d/matrix), на которую умножается эта [Matrix](../../com.aspose.drawing.drawing2d/matrix). |

### multiply(Matrix matrix, int order) {#multiply-com.aspose.drawing.drawing2d.Matrix-int-}
```
public void multiply(Matrix matrix, int order)
```


Умножает эту [Matrix](../../com.aspose.drawing.drawing2d/matrix) на матрицу, указанную в параметре `matrix`, и в порядке, указанном в параметре `order`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.drawing.drawing2d/matrix) | Матрица [Matrix](../../com.aspose.drawing.drawing2d/matrix), на которую умножается эта [Matrix](../../com.aspose.drawing.drawing2d/matrix). |
| order | int | MatrixOrder [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder), представляющий порядок умножения. |

### rotate(float angle) {#rotate-float-}
```
public void rotate(float angle)
```


Предварительно добавить к этой [Matrix](../../com.aspose.drawing.drawing2d/matrix) вращение по часовой стрелке вокруг начала координат с указанным углом.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| угол | float | Угол вращения в градусах. |

### rotate(float angle, int order) {#rotate-float-int-}
```
public void rotate(float angle, int order)
```


Применяет вращение по часовой стрелке на угол, указанный в параметре angle, вокруг начала координат (ноль по x и y) для этой [Matrix](../../com.aspose.drawing.drawing2d/matrix).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| угол | float | Угол вращения в градусах. |
| order | int | MatrixOrder [MatrixOrder](../../com.aspose.drawing.drawing2d/matrixorder) который указывает порядок (добавление в конец или в начало), в котором вращение применяется к этой [Matrix](../../com.aspose.drawing.drawing2d/matrix). |

### reset() {#reset--}
```
public void reset()
```


Сбрасывает эту [Matrix](../../com.aspose.drawing.drawing2d/matrix), чтобы она имела элементы единичной матрицы.

