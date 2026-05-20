---
title: EmfType
second_title: Aspose.Drawing for Java API 参考
description: 指定放置在增强型图元文件（EMF）中的记录的性质。
type: docs
weight: 18
url: /zh/java/com.aspose.drawing.imaging/emftype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfType extends System.Enum
```

指定放置在增强型图元文件（EMF）中的记录的性质。此枚举在 [Metafile](../../com.aspose.drawing.imaging/metafile) 类的多个构造函数中使用。
## 字段

| 字段 | 描述 |
| --- | --- |
| [EmfOnly](#EmfOnly) | 指定元文件中的所有记录都是 EMF 记录，可由 GDI 或 GDI+ 显示。 |
| [EmfPlusOnly](#EmfPlusOnly) | 指定元文件中的所有记录都是 EMF+ 记录，可由 GDI+ 显示，但不能由 GDI 显示。 |
| [EmfPlusDual](#EmfPlusDual) | 指定元文件中的所有 EMF+ 记录都关联到另一个 EMF 记录。 |
### EmfOnly {#EmfOnly}
```
public static final int EmfOnly
```


指定元文件中的所有记录都是 EMF 记录，可由 GDI 或 GDI+ 显示。

### EmfPlusOnly {#EmfPlusOnly}
```
public static final int EmfPlusOnly
```


指定元文件中的所有记录都是 EMF+ 记录，可由 GDI+ 显示，但不能由 GDI 显示。

### EmfPlusDual {#EmfPlusDual}
```
public static final int EmfPlusDual
```


指定元文件中的所有 EMF+ 记录都关联到另一个 EMF 记录。类型为 `EmfType.EmfPlusDual` 的元文件可由 GDI 或 GDI+ 显示。

