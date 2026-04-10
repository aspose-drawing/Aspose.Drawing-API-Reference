---
title: TextRenderingHint
second_title: Aspose.Drawing for Java API 参考
description: 指定文本渲染的质量。
type: docs
weight: 14
url: /zh/java/com.aspose.drawing.text/textrenderinghint/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class TextRenderingHint extends System.Enum
```

指定文本渲染的质量。
## 字段

| 字段 | 描述 |
| --- | --- |
| [SystemDefault](#SystemDefault) | 每个字符使用其字形位图绘制，使用系统默认的渲染提示。 |
| [SingleBitPerPixelGridFit](#SingleBitPerPixelGridFit) | 每个字符使用其字形位图绘制。 |
| [SingleBitPerPixel](#SingleBitPerPixel) | 每个字符使用其字形位图绘制。 |
| [AntiAliasGridFit](#AntiAliasGridFit) | 每个字符使用带提示的抗锯齿字形位图绘制。 |
| [AntiAlias](#AntiAlias) | 每个字符使用无提示的抗锯齿字形位图绘制。 |
| [ClearTypeGridFit](#ClearTypeGridFit) | 每个字符使用带提示的 ClearType 字形位图绘制。 |
### SystemDefault {#SystemDefault}
```
public static final int SystemDefault
```


每个字符使用其字形位图绘制，使用系统默认的渲染提示。文本将按照用户为系统选择的任何字体平滑设置进行绘制。

### SingleBitPerPixelGridFit {#SingleBitPerPixelGridFit}
```
public static final int SingleBitPerPixelGridFit
```


每个字符使用其字形位图绘制。提示用于改善字符在笔画和曲线上的外观。

### SingleBitPerPixel {#SingleBitPerPixel}
```
public static final int SingleBitPerPixel
```


每个字符使用其字形位图绘制。不使用 Hinting。

### AntiAliasGridFit {#AntiAliasGridFit}
```
public static final int AntiAliasGridFit
```


每个字符使用其带有 Hinting 的抗锯齿字形位图绘制。由于抗锯齿，质量大幅提升，但性能开销更高。

### AntiAlias {#AntiAlias}
```
public static final int AntiAlias
```


每个字符使用其未使用 Hinting 的抗锯齿字形位图绘制。由于抗锯齿，质量更好。由于关闭 Hinting，可能会注意到笔画宽度差异。

### ClearTypeGridFit {#ClearTypeGridFit}
```
public static final int ClearTypeGridFit
```


每个字符使用其带有 Hinting 的 ClearType 字形位图绘制。最高质量设置。用于利用 ClearType 字体特性。

