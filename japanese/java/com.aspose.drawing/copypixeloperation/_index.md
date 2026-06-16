---
title: CopyPixelOperation
second_title: Aspose.Drawing for Java API リファレンス
description: コピー ピクセル操作におけるソースカラーが、宛先カラーとどのように合成されて最終カラーになるかを決定します。
type: docs
weight: 18
url: /ja/java/com.aspose.drawing/copypixeloperation/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class CopyPixelOperation extends System.Enum
```

コピー ピクセル操作におけるソースカラーが、宛先カラーとどのように合成されて最終カラーになるかを決定します。
## フィールド

| フィールド | 説明 |
| --- | --- |
| [NoMirrorBitmap](#NoMirrorBitmap) | ビットマップは鏡像化されていません。 |
| [Blackness](#Blackness) | 物理パレットのインデックス 0 に対応する色を使用して、宛先領域が塗りつぶされます。 |
| [NotSourceErase](#NotSourceErase) | ソースと宛先の色はブール `OR` 演算子で結合され、その結果の色が反転されます。 |
| [NotSourceCopy](#NotSourceCopy) | 反転されたソース領域が宛先にコピーされます。 |
| [SourceErase](#SourceErase) | 宛先領域の反転された色は、ブール `AND` 演算子を使用してソース領域の色と結合されます。 |
| [DestinationInvert](#DestinationInvert) | 宛先領域が反転されます。 |
| [PatInvert](#PatInvert) | 宛先デバイスコンテキストで現在選択されているブラシの色は、ブール `XOR` 演算子を使用して宛先の色と結合されます。 |
| [SourceInvert](#SourceInvert) | ソース領域と宛先領域の色は、ブール `XOR` 演算子で結合されます。 |
| [SourceAnd](#SourceAnd) | ソース領域と宛先領域の色は、ブール `AND` 演算子で結合されます。 |
| [MergePaint](#MergePaint) | 反転されたソース領域の色は、ブール `OR` 演算子を使用して宛先領域の色とマージされます。 |
| [MergeCopy](#MergeCopy) | ソース領域の色は、ブール `AND` 演算子を使用して宛先デバイスコンテキストで選択されたブラシの色とマージされます。 |
| [SourceCopy](#SourceCopy) | ソース領域が直接宛先領域にコピーされます。 |
| [SourcePaint](#SourcePaint) | ソース領域と宛先領域の色は、ブール `OR` 演算子で結合されます。 |
| [PatCopy](#PatCopy) | 宛先デバイスコンテキストで現在選択されているブラシが、宛先ビットマップにコピーされます。 |
| [PatPaint](#PatPaint) | 宛先デバイスコンテキストで現在選択されているブラシの色は、ブール `OR` 演算子を使用して反転されたソース領域の色と結合されます。 |
| [Whiteness](#Whiteness) | 物理パレットのインデックス 1 に対応する色を使用して、宛先領域が塗りつぶされます。 |
| [CaptureBlt](#CaptureBlt) | ウィンドウの上にレイヤーされたウィンドウも、結果の画像に含まれます。 |
### NoMirrorBitmap {#NoMirrorBitmap}
```
public static final int NoMirrorBitmap
```


ビットマップは鏡像化されていません。

### Blackness {#Blackness}
```
public static final int Blackness
```


物理パレットのインデックス 0 に対応する色を使用して、宛先領域が塗りつぶされます。（この色はデフォルトの物理パレットでは黒です。）

### NotSourceErase {#NotSourceErase}
```
public static final int NotSourceErase
```


ソースと宛先の色はブール `OR` 演算子で結合され、その結果の色が反転されます。

### NotSourceCopy {#NotSourceCopy}
```
public static final int NotSourceCopy
```


反転されたソース領域が宛先にコピーされます。

### SourceErase {#SourceErase}
```
public static final int SourceErase
```


宛先領域の反転された色は、ブール `AND` 演算子を使用してソース領域の色と結合されます。

### DestinationInvert {#DestinationInvert}
```
public static final int DestinationInvert
```


宛先領域が反転されます。

### PatInvert {#PatInvert}
```
public static final int PatInvert
```


宛先デバイスコンテキストで現在選択されているブラシの色は、ブール `XOR` 演算子を使用して宛先の色と結合されます。

### SourceInvert {#SourceInvert}
```
public static final int SourceInvert
```


ソース領域と宛先領域の色は、ブール `XOR` 演算子で結合されます。

### SourceAnd {#SourceAnd}
```
public static final int SourceAnd
```


ソース領域と宛先領域の色は、ブール `AND` 演算子で結合されます。

### MergePaint {#MergePaint}
```
public static final int MergePaint
```


反転されたソース領域の色は、ブール `OR` 演算子を使用して宛先領域の色とマージされます。

### MergeCopy {#MergeCopy}
```
public static final int MergeCopy
```


ソース領域の色は、ブール `AND` 演算子を使用して宛先デバイスコンテキストで選択されたブラシの色とマージされます。

### SourceCopy {#SourceCopy}
```
public static final int SourceCopy
```


ソース領域が直接宛先領域にコピーされます。

### SourcePaint {#SourcePaint}
```
public static final int SourcePaint
```


ソース領域と宛先領域の色は、ブール `OR` 演算子で結合されます。

### PatCopy {#PatCopy}
```
public static final int PatCopy
```


宛先デバイスコンテキストで現在選択されているブラシが、宛先ビットマップにコピーされます。

### PatPaint {#PatPaint}
```
public static final int PatPaint
```


The colors of the brush currently selected in the destination device context are combined with the colors of the inverted source area using the Boolean `OR` operator. The result of this operation is combined with the colors of the destination area using the Boolean `OR` operator.

### Whiteness {#Whiteness}
```
public static final int Whiteness
```


The destination area is filled by using the color associated with index 1 in the physical palette. (This color is white for the default physical palette.)

### CaptureBlt {#CaptureBlt}
```
public static final int CaptureBlt
```


Windows that are layered on top of your window are included in the resulting image. By default, the image contains only your window. Note that this generally cannot be used for printing device contexts.

