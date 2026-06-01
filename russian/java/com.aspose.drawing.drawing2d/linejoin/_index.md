---
title: LineJoin
second_title: Справочник API Aspose.Drawing для Java
description: Указывает, как соединять последовательные отрезки линий или кривых в подпути фигуры, содержащейся в объекте GraphicsPath.
type: docs
weight: 30
url: /ru/java/com.aspose.drawing.drawing2d/linejoin/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class LineJoin extends System.Enum
```

Указывает, как соединять последовательные отрезки линий или кривых в фигуре (подпуть), содержащейся в объекте GraphicsPath.
## Поля

| Поле | Описание |
| --- | --- |
| [Miter](#Miter) | Указывает соединение mitered. |
| [Bevel](#Bevel) | Указывает соединение с фаской. |
| [Round](#Round) | Указывает круговое соединение. |
| [MiterClipped](#MiterClipped) | Указывает соединение mitered. |
### Miter {#Miter}
```
public static final int Miter
```


Указывает соединение mitered. Это создает острый угол или обрезанный угол, в зависимости от того, превышает ли длина среза предел miter.

--------------------

В данный момент соединение Miter фактически работает как MiterClipped.

### Bevel {#Bevel}
```
public static final int Bevel
```


Указывает соединение с фаской. Это создает диагональный угол.

### Round {#Round}
```
public static final int Round
```


Указывает круговое соединение. Это создает плавную круглую дугу между линиями.

### MiterClipped {#MiterClipped}
```
public static final int MiterClipped
```


Указывает соединение mitered. Это создает острый угол или фаску, в зависимости от того, превышает ли длина среза предел miter.

