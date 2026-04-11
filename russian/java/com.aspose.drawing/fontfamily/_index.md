---
title: FontFamily
second_title: Справочник API Aspose.Drawing для Java
description: Определяет группу гарнитур, имеющих схожий базовый дизайн и определённые вариации в стилях.
type: docs
weight: 24
url: /ru/java/com.aspose.drawing/fontfamily/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public final class FontFamily implements System.IDisposable
```

Определяет группу гарнитур шрифтов с похожим базовым дизайном и некоторыми вариациями стилей. Этот класс нельзя наследовать.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [FontFamily(String name)](#FontFamily-java.lang.String-) | Создаёт новый экземпляр класса [FontFamily](../../com.aspose.drawing/fontfamily) с указанным именем. |
| [FontFamily(String name, FontCollection fontCollection)](#FontFamily-java.lang.String-com.aspose.drawing.FontCollection-) | Создаёт новый экземпляр класса [FontFamily](../../com.aspose.drawing/fontfamily). |
| [FontFamily(String name, FontFamilyDefinition definition)](#FontFamily-java.lang.String-com.aspose.drawing.FontFamilyDefinition-) | Создаёт новый экземпляр класса [FontFamily](../../com.aspose.drawing/fontfamily). |
## Методы

| Метод | Описание |
| --- | --- |
| [getFamilies()](#getFamilies--) | Возвращает массив, содержащий все объекты [FontFamily](../../com.aspose.drawing/fontfamily), связанные с текущим графическим контекстом. |
| [getGenericSansSerif()](#getGenericSansSerif--) | Возвращает объект общего без засечек [FontFamily](../../com.aspose.drawing/fontfamily). |
| [getGenericSerif()](#getGenericSerif--) | Возвращает объект общей гарнитуры с засечками [FontFamily](../../com.aspose.drawing/fontfamily). |
| [getGenericMonospace()](#getGenericMonospace--) | Возвращает объект общей моноширинной [FontFamily](../../com.aspose.drawing/fontfamily). |
| [getName()](#getName--) | Возвращает имя этой [FontFamily](../../com.aspose.drawing/fontfamily). |
| [dispose()](#dispose--) | Освобождает все ресурсы, используемые этим объектом [FontFamily](../../com.aspose.drawing/fontfamily). |
| [getName(int language)](#getName-int-) | Возвращает имя этой [FontFamily](../../com.aspose.drawing/fontfamily) на указанном языке. |
| [isStyleAvailable(int style)](#isStyleAvailable-int-) | Указывает, доступно ли указанное перечисление [FontStyle](../../com.aspose.drawing/fontstyle). |
| [getEmHeight(int style)](#getEmHeight-int-) | Получает высоту, в единицах проектирования шрифта, квадрата EM для указанного стиля. |
| [getCellAscent(int style)](#getCellAscent-int-) | Возвращает подъем ячейки, в единицах проектирования, [FontFamily](../../com.aspose.drawing/fontfamily) указанного стиля. |
| [getCellDescent(int style)](#getCellDescent-int-) | Возвращает спад ячейки, в единицах проектирования, [FontFamily](../../com.aspose.drawing/fontfamily) указанного стиля. |
| [hashCode()](#hashCode--) | Получает хеш-код для этой [FontFamily](../../com.aspose.drawing/fontfamily). |
| [equals(Object obj)](#equals-java.lang.Object-) | Указывает, является ли указанный объект [FontFamily](../../com.aspose.drawing/fontfamily) и идентичен этой [FontFamily](../../com.aspose.drawing/fontfamily). |
| [getLineSpacing(int style)](#getLineSpacing-int-) | Возвращает межстрочный интервал, в единицах проектирования, [FontFamily](../../com.aspose.drawing/fontfamily) указанного стиля. |
### FontFamily(String name) {#FontFamily-java.lang.String-}
```
public FontFamily(String name)
```


Создаёт новый экземпляр класса [FontFamily](../../com.aspose.drawing/fontfamily) с указанным именем.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Имя нового [FontFamily](../../com.aspose.drawing/fontfamily). |

### FontFamily(String name, FontCollection fontCollection) {#FontFamily-java.lang.String-com.aspose.drawing.FontCollection-}
```
public FontFamily(String name, FontCollection fontCollection)
```


Создаёт новый экземпляр класса [FontFamily](../../com.aspose.drawing/fontfamily).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| имя | java.lang.String | Имя семейства шрифтов. |
| fontCollection | [FontCollection](../../com.aspose.drawing/fontcollection) | Коллекция шрифтов. |

### FontFamily(String name, FontFamilyDefinition definition) {#FontFamily-java.lang.String-com.aspose.drawing.FontFamilyDefinition-}
```
public FontFamily(String name, FontFamilyDefinition definition)
```


Создаёт новый экземпляр класса [FontFamily](../../com.aspose.drawing/fontfamily).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| имя | java.lang.String | Имя семейства шрифтов. |
| definition | [FontFamilyDefinition](../../com.aspose.drawing/fontfamilydefinition) | Определение. |

### getFamilies() {#getFamilies--}
```
public static FontFamily[] getFamilies()
```


Возвращает массив, содержащий все объекты [FontFamily](../../com.aspose.drawing/fontfamily), связанные с текущим графическим контекстом.

**Returns:**
com.aspose.drawing.FontFamily[] - Массив объектов [FontFamily](../../com.aspose.drawing/fontfamily), связанных с текущим графическим контекстом.
### getGenericSansSerif() {#getGenericSansSerif--}
```
public static FontFamily getGenericSansSerif()
```


Возвращает объект общего без засечек [FontFamily](../../com.aspose.drawing/fontfamily).

**Returns:**
[FontFamily](../../com.aspose.drawing/fontfamily) - A [FontFamily](../../com.aspose.drawing/fontfamily) object that represents a generic sans serif font.
### getGenericSerif() {#getGenericSerif--}
```
public static FontFamily getGenericSerif()
```


Возвращает объект общей гарнитуры с засечками [FontFamily](../../com.aspose.drawing/fontfamily).

**Returns:**
[FontFamily](../../com.aspose.drawing/fontfamily) - A [FontFamily](../../com.aspose.drawing/fontfamily) that represents a generic serif font.
### getGenericMonospace() {#getGenericMonospace--}
```
public static FontFamily getGenericMonospace()
```


Возвращает объект общей моноширинной [FontFamily](../../com.aspose.drawing/fontfamily).

**Returns:**
[FontFamily](../../com.aspose.drawing/fontfamily) - A [FontFamily](../../com.aspose.drawing/fontfamily) that represents a generic monospace font.
### getName() {#getName--}
```
public String getName()
```


Возвращает имя этой [FontFamily](../../com.aspose.drawing/fontfamily).

**Returns:**
java.lang.String - Строка, представляющая имя этой [FontFamily](../../com.aspose.drawing/fontfamily).
### dispose() {#dispose--}
```
public void dispose()
```


Освобождает все ресурсы, используемые этим объектом [FontFamily](../../com.aspose.drawing/fontfamily).

### getName(int language) {#getName-int-}
```
public String getName(int language)
```


Возвращает имя этой [FontFamily](../../com.aspose.drawing/fontfamily) на указанном языке.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| язык | int | Язык, на котором возвращается имя. |

**Returns:**
java.lang.String - Строка, представляющая имя, на указанном языке, этой [FontFamily](../../com.aspose.drawing/fontfamily).
### isStyleAvailable(int style) {#isStyleAvailable-int-}
```
public boolean isStyleAvailable(int style)
```


Указывает, доступно ли указанное перечисление [FontStyle](../../com.aspose.drawing/fontstyle).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| style | int | Тестируемый [FontStyle](../../com.aspose.drawing/fontstyle). |

**Returns:**
boolean - true, если указанное [FontStyle](../../com.aspose.drawing/fontstyle) доступно; иначе false.
### getEmHeight(int style) {#getEmHeight-int-}
```
public int getEmHeight(int style)
```


Получает высоту, в единицах проектирования шрифта, квадрата EM для указанного стиля.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| style | int | Для получения высоты EM указанного [FontStyle](../../com.aspose.drawing/fontstyle). |

**Returns:**
int - Высота квадрата EM.
### getCellAscent(int style) {#getCellAscent-int-}
```
public int getCellAscent(int style)
```


Возвращает подъем ячейки, в единицах проектирования, [FontFamily](../../com.aspose.drawing/fontfamily) указанного стиля.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| style | int | [FontStyle](../../com.aspose.drawing/fontstyle) — объект, содержащий информацию о стиле шрифта. |

**Returns:**
int - Подъем ячейки для этой [FontFamily](../../com.aspose.drawing/fontfamily), использующей указанный [FontStyle](../../com.aspose.drawing/fontstyle).
### getCellDescent(int style) {#getCellDescent-int-}
```
public int getCellDescent(int style)
```


Возвращает спад ячейки, в единицах проектирования, [FontFamily](../../com.aspose.drawing/fontfamily) указанного стиля.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| style | int | [FontStyle](../../com.aspose.drawing/fontstyle) — объект, содержащий информацию о стиле шрифта. |

**Returns:**
int - Показатель спада ячейки для этой [FontFamily](../../com.aspose.drawing/fontfamily), использующей указанный [FontStyle](../../com.aspose.drawing/fontstyle).
### hashCode() {#hashCode--}
```
public int hashCode()
```


Получает хеш-код для этой [FontFamily](../../com.aspose.drawing/fontfamily).

**Returns:**
int - Хеш-код для этой [FontFamily](../../com.aspose.drawing/fontfamily).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Указывает, является ли указанный объект [FontFamily](../../com.aspose.drawing/fontfamily) и идентичен этой [FontFamily](../../com.aspose.drawing/fontfamily).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | java.lang.Object | Объект для тестирования. |

**Returns:**
boolean - `true`, если `obj` является [FontFamily](../../com.aspose.drawing/fontfamily) и идентичен этой [FontFamily](../../com.aspose.drawing/fontfamily); иначе `false`.
### getLineSpacing(int style) {#getLineSpacing-int-}
```
public int getLineSpacing(int style)
```


Возвращает межстрочный интервал, в единицах дизайна, для [FontFamily](../../com.aspose.drawing/fontfamily) указанного стиля. Межстрочный интервал — это вертикальное расстояние между базовыми линиями двух последовательных строк текста.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| style | int | Стиль [FontStyle](../../com.aspose.drawing/fontstyle), который следует применить. |

**Returns:**
int — расстояние между двумя последовательными строками текста.
