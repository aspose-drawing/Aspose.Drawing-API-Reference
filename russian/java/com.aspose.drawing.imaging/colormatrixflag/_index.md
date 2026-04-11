---
title: ColorMatrixFlag
second_title: Справочник API Aspose.Drawing для Java
description: Указывает типы изображений и цветов, которые будут затронуты настройками регулировки цвета и градаций серого.
type: docs
weight: 15
url: /ru/java/com.aspose.drawing.imaging/colormatrixflag/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ColorMatrixFlag extends System.Enum
```

Указывает типы изображений и цветов, которые будут затронуты настройками регулировки цвета и градаций серого объекта [ImageAttributes](../../com.aspose.drawing.imaging/imageattributes).
## Поля

| Поле | Описание |
| --- | --- |
| [Default](#Default) | Все значения цвета, включая серые оттенки, регулируются одной и той же матрицей регулировки цвета. |
| [SkipGrays](#SkipGrays) | Все цвета регулируются, но серые оттенки не регулируются. |
| [AltGrays](#AltGrays) | Регулируются только серые оттенки. |
### Default {#Default}
```
public static final int Default
```


Все значения цвета, включая серые оттенки, регулируются одной и той же матрицей регулировки цвета.

### SkipGrays {#SkipGrays}
```
public static final int SkipGrays
```


Все цвета регулируются, но серые оттенки не регулируются. Серый оттенок — любой цвет, у которого одинаковые значения красного, зелёного и синего компонентов.

### AltGrays {#AltGrays}
```
public static final int AltGrays
```


Регулируются только серые оттенки.

