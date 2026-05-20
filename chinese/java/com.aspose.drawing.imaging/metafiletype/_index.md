---
title: MetafileType
second_title: Aspose.Drawing for Java API 参考
description: 指定元文件的类型。
type: docs
weight: 33
url: /zh/java/com.aspose.drawing.imaging/metafiletype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class MetafileType extends System.Enum
```

指定元文件的类型。
## 字段

| 字段 | 描述 |
| --- | --- |
| [Invalid](#Invalid) | 指定 GDI+ 未识别的元文件格式。 |
| [Wmf](#Wmf) | 指定 WMF（Windows Metafile）文件。 |
| [WmfPlaceable](#WmfPlaceable) | 指定前面带有可放置元文件头的 WMF（Windows Metafile）文件。 |
| [Emf](#Emf) | 指定增强型元文件（EMF）文件。 |
| [EmfPlusOnly](#EmfPlusOnly) | 指定 EMF+ 文件。 |
| [EmfPlusDual](#EmfPlusDual) | 指定 EMF+ Dual 文件。 |
### Invalid {#Invalid}
```
public static final int Invalid
```


指定 GDI+ 未识别的元文件格式。

### Wmf {#Wmf}
```
public static final int Wmf
```


指定 WMF（Windows Metafile）文件。此类文件仅包含 GDI 记录。

### WmfPlaceable {#WmfPlaceable}
```
public static final int WmfPlaceable
```


指定前面带有可放置元文件头的 WMF（Windows Metafile）文件。

### Emf {#Emf}
```
public static final int Emf
```


指定增强型元文件（EMF）文件。此类文件仅包含 GDI 记录。

### EmfPlusOnly {#EmfPlusOnly}
```
public static final int EmfPlusOnly
```


指定 EMF+ 文件。此类文件仅包含 GDI+ 记录，必须使用 GDI+ 显示。使用 GDI 显示这些记录可能导致不可预期的结果。

### EmfPlusDual {#EmfPlusDual}
```
public static final int EmfPlusDual
```


指定 EMF+ Dual 文件。此类文件包含 GDI+ 记录以及替代的 GDI 记录，可使用 GDI 或 GDI+ 任意一种方式显示。使用 GDI 显示记录可能导致一定的质量下降。

