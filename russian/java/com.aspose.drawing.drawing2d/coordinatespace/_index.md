---
title: CoordinateSpace
second_title: Справочник API Aspose.Drawing для Java
description: Указывает систему, используемую при вычислении координат.
type: docs
weight: 16
url: /ru/java/com.aspose.drawing.drawing2d/coordinatespace/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class CoordinateSpace extends System.Enum
```

Указывает систему, используемую при вычислении координат.
## Поля

| Поле | Описание |
| --- | --- |
| [World](#World) | Указывает, что координаты находятся в контексте мировых координат. |
| [Page](#Page) | Указывает, что координаты находятся в контексте координат страницы. |
| [Device](#Device) | Указывает, что координаты находятся в контексте координат устройства. |
### World {#World}
```
public static final int World
```


Указывает, что координаты находятся в контексте мировых координат. Мировые координаты используются в нефизической среде, например в среде моделирования.

### Page {#Page}
```
public static final int Page
```


Указывает, что координаты находятся в контексте координат страницы. Их единицы измерения определяются свойством Graphics.PageUnit и должны быть одним из элементов перечисления GraphicsUnit.

### Device {#Device}
```
public static final int Device
```


Указывает, что координаты находятся в контексте координат устройства. На экране компьютера координаты устройства обычно измеряются в пикселях.

