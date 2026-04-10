---
title: TextRenderingHint
second_title: Aspose.Drawing for Java API リファレンス
description: テキストレンダリングの品質を指定します。
type: docs
weight: 14
url: /ja/java/com.aspose.drawing.text/textrenderinghint/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class TextRenderingHint extends System.Enum
```

テキストレンダリングの品質を指定します。
## フィールド

| フィールド | 説明 |
| --- | --- |
| [SystemDefault](#SystemDefault) | 各文字はグリフビットマップを使用して描画され、システム既定のレンダリングヒントが適用されます。 |
| [SingleBitPerPixelGridFit](#SingleBitPerPixelGridFit) | 各文字はグリフビットマップを使用して描画されます。 |
| [SingleBitPerPixel](#SingleBitPerPixel) | 各文字はグリフビットマップを使用して描画されます。 |
| [AntiAliasGridFit](#AntiAliasGridFit) | 各文字はヒンティング付きのアンチエイリアスグリフビットマップを使用して描画されます。 |
| [AntiAlias](#AntiAlias) | 各文字はヒンティングなしのアンチエイリアスグリフビットマップを使用して描画されます。 |
| [ClearTypeGridFit](#ClearTypeGridFit) | 各文字はヒンティング付きのグリフClearTypeビットマップを使用して描画されます。 |
### SystemDefault {#SystemDefault}
```
public static final int SystemDefault
```


各文字はグリフビットマップを使用して描画され、システム既定のレンダリングヒントが適用されます。テキストは、ユーザーがシステムで選択したフォントスムージング設定に従って描画されます。

### SingleBitPerPixelGridFit {#SingleBitPerPixelGridFit}
```
public static final int SingleBitPerPixelGridFit
```


各文字はグリフビットマップを使用して描画されます。ヒンティングはステムや曲線上の文字の外観を向上させるために使用されます。

### SingleBitPerPixel {#SingleBitPerPixel}
```
public static final int SingleBitPerPixel
```


各文字はそのグリフビットマップを使用して描画されます。ヒンティングは使用されません。

### AntiAliasGridFit {#AntiAliasGridFit}
```
public static final int AntiAliasGridFit
```


各文字はヒンティング付きのアンチエイリアスされたグリフビットマップを使用して描画されます。アンチエイリアスにより品質が大幅に向上しますが、パフォーマンスコストが高くなります。

### AntiAlias {#AntiAlias}
```
public static final int AntiAlias
```


各文字はヒンティングなしのアンチエイリアスされたグリフビットマップを使用して描画されます。アンチエイリアスにより品質が向上します。ヒンティングがオフになっているため、ステム幅の違いが目立つことがあります。

### ClearTypeGridFit {#ClearTypeGridFit}
```
public static final int ClearTypeGridFit
```


各文字はヒンティング付きのグリフClearTypeビットマップを使用して描画されます。最高品質の設定です。ClearTypeフォント機能を活用するために使用されます。

