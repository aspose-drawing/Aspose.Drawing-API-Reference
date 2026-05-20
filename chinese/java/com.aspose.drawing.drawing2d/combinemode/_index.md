---
title: CombineMode
second_title: Aspose.Drawing for Java API 参考
description: 指定不同裁剪区域的组合方式。
type: docs
weight: 13
url: /zh/java/com.aspose.drawing.drawing2d/combinemode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class CombineMode extends System.Enum
```

指定不同裁剪区域的组合方式。
## 字段

| 字段 | 描述 |
| --- | --- |
| [Replace](#Replace) | 一个裁剪区域被另一个替换。 |
| [Intersect](#Intersect) | 两个裁剪区域通过取它们的交集进行组合。 |
| [Union](#Union) | 两个裁剪区域通过取它们的并集进行组合。 |
| [Xor](#Xor) | 两个裁剪区域通过仅取被其中一个区域包围的区域（而非两者都包含的区域）进行组合。 |
| [Exclude](#Exclude) | 指定将现有区域替换为从现有区域中移除新区域后的结果。 |
| [Complement](#Complement) | 指定将现有区域替换为从新区域中移除现有区域后的结果。 |
### Replace {#Replace}
```
public static final int Replace
```


一个裁剪区域被另一个替换。

### Intersect {#Intersect}
```
public static final int Intersect
```


两个裁剪区域通过取它们的交集进行组合。

### Union {#Union}
```
public static final int Union
```


两个裁剪区域通过取它们的并集进行组合。

### Xor {#Xor}
```
public static final int Xor
```


两个裁剪区域通过仅取被其中一个区域包围的区域（而非两者都包含的区域）进行组合。

### Exclude {#Exclude}
```
public static final int Exclude
```


指定将现有区域替换为从现有区域中移除新区域后的结果。换句话说，新区域从现有区域中被排除。

### Complement {#Complement}
```
public static final int Complement
```


指定将现有区域替换为从新区域中移除现有区域后的结果。换句话说，现有区域从新区域中被排除。

