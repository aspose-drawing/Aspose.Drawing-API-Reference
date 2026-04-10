---
title: PixelFormat
second_title: Aspose.Drawing for Java API リファレンス
description: 画像内の各ピクセルのカラー データの形式を指定します。
type: docs
weight: 34
url: /ja/java/com.aspose.drawing.imaging/pixelformat/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PixelFormat extends System.Enum
```

画像内の各ピクセルのカラー データの形式を指定します。
## フィールド

| フィールド | 説明 |
| --- | --- |
| [Indexed](#Indexed) | ピクセルデータはカラーインデックス値を含みます。これは、個々のカラー値ではなく、システムのカラーテーブル内の色へのインデックスであることを意味します。 |
| [Gdi](#Gdi) | ピクセルデータは GDI カラーを含みます。 |
| [Alpha](#Alpha) | ピクセルデータは事前乗算されていないアルファ値を含みます。 |
| [PAlpha](#PAlpha) | ピクセルフォーマットは事前乗算されたアルファ値を含みます。 |
| [Extended](#Extended) | 予約済みの値。 |
| [Canonical](#Canonical) | 1 ピクセルあたり 32 ビットのデフォルトピクセルフォーマットです。 |
| [Undefined](#Undefined) | ピクセルフォーマットは未定義です。 |
| [DontCare](#DontCare) | ピクセルフォーマットは指定されていません。 |
| [Format1bppIndexed](#Format1bppIndexed) | ピクセルフォーマットが 1 ビット/ピクセルで、インデックスカラーを使用することを指定します。 |
| [Format4bppIndexed](#Format4bppIndexed) | フォーマットが 4 ビット/ピクセルのインデックスカラーであることを指定します。 |
| [Format8bppIndexed](#Format8bppIndexed) | フォーマットが 8 ビット/ピクセルのインデックスカラーであることを指定します。 |
| [Format16bppGrayScale](#Format16bppGrayScale) | ピクセルフォーマットは 1 ピクセルあたり 16 ビットです。 |
| [Format16bppRgb555](#Format16bppRgb555) | フォーマットが 16 ビット/ピクセルで、赤、緑、青の各成分に 5 ビットずつ使用されることを指定します。 |
| [Format16bppRgb565](#Format16bppRgb565) | フォーマットが 16 ビット/ピクセルで、赤成分に 5 ビット、緑成分に 6 ビット、青成分に 5 ビット使用されることを指定します。 |
| [Format16bppArgb1555](#Format16bppArgb1555) | ピクセルフォーマットは 1 ピクセルあたり 16 ビットです。 |
| [Format24bppRgb](#Format24bppRgb) | フォーマットがピクセルあたり24ビットであることを指定します。赤、緑、青の各コンポーネントに8ビットずつ使用されます。 |
| [Format32bppRgb](#Format32bppRgb) | フォーマットがピクセルあたり32ビットであることを指定します。赤、緑、青の各コンポーネントに8ビットずつ使用されます。 |
| [Format32bppArgb](#Format32bppArgb) | フォーマットがピクセルあたり32ビットであることを指定します。アルファ、赤、緑、青の各コンポーネントに8ビットずつ使用されます。 |
| [Format32bppPArgb](#Format32bppPArgb) | フォーマットがピクセルあたり32ビットであることを指定します。アルファ、赤、緑、青の各コンポーネントに8ビットずつ使用されます。 |
| [Format48bppRgb](#Format48bppRgb) | フォーマットがピクセルあたり48ビットであることを指定します。赤、緑、青の各コンポーネントに16ビットずつ使用されます。 |
| [Format64bppArgb](#Format64bppArgb) | フォーマットがピクセルあたり64ビットであることを指定します。アルファ、赤、緑、青の各コンポーネントに16ビットずつ使用されます。 |
| [Format64bppPArgb](#Format64bppPArgb) | フォーマットがピクセルあたり64ビットであることを指定します。アルファ、赤、緑、青の各コンポーネントに16ビットずつ使用されます。 |
| [Max](#Max) | The maximum value for this enumeration. |
### Indexed {#Indexed}
```
public static final int Indexed
```


ピクセルデータはカラーインデックス値を含みます。これは、個々のカラー値ではなく、システムのカラーテーブル内の色へのインデックスであることを意味します。

### Gdi {#Gdi}
```
public static final int Gdi
```


ピクセルデータは GDI カラーを含みます。

### Alpha {#Alpha}
```
public static final int Alpha
```


ピクセルデータは事前乗算されていないアルファ値を含みます。

### PAlpha {#PAlpha}
```
public static final int PAlpha
```


ピクセルフォーマットは事前乗算されたアルファ値を含みます。

### Extended {#Extended}
```
public static final int Extended
```


予約済みの値。

### Canonical {#Canonical}
```
public static final int Canonical
```


デフォルトのピクセルフォーマットはピクセルあたり32ビットです。このフォーマットは24ビットの色深度と8ビットのアルファチャンネルを指定します。

### Undefined {#Undefined}
```
public static final int Undefined
```


ピクセルフォーマットは未定義です。

### DontCare {#DontCare}
```
public static final int DontCare
```


ピクセルフォーマットは指定されていません。

### Format1bppIndexed {#Format1bppIndexed}
```
public static final int Format1bppIndexed
```


ピクセルフォーマットがピクセルあたり1ビットで、インデックスカラーを使用することを指定します。そのため、カラーテーブルには2色が含まれます。

### Format4bppIndexed {#Format4bppIndexed}
```
public static final int Format4bppIndexed
```


フォーマットが 4 ビット/ピクセルのインデックスカラーであることを指定します。

### Format8bppIndexed {#Format8bppIndexed}
```
public static final int Format8bppIndexed
```


フォーマットがピクセルあたり8ビットのインデックス形式であることを指定します。そのため、カラーテーブルには256色が含まれます。

### Format16bppGrayScale {#Format16bppGrayScale}
```
public static final int Format16bppGrayScale
```


ピクセルフォーマットはピクセルあたり16ビットです。カラー情報は65,536段階のグレースケールを指定します。

### Format16bppRgb555 {#Format16bppRgb555}
```
public static final int Format16bppRgb555
```


フォーマットがピクセルあたり16ビットで、赤、緑、青の各コンポーネントに5ビットずつ使用されることを指定します。残りのビットは使用されません。

### Format16bppRgb565 {#Format16bppRgb565}
```
public static final int Format16bppRgb565
```


フォーマットが 16 ビット/ピクセルで、赤成分に 5 ビット、緑成分に 6 ビット、青成分に 5 ビット使用されることを指定します。

### Format16bppArgb1555 {#Format16bppArgb1555}
```
public static final int Format16bppArgb1555
```


ピクセルフォーマットはピクセルあたり16ビットです。カラー情報は32,768色の階調を指定し、そのうち赤が5ビット、緑が5ビット、青が5ビット、アルファが1ビットです。

### Format24bppRgb {#Format24bppRgb}
```
public static final int Format24bppRgb
```


フォーマットがピクセルあたり24ビットであることを指定します。赤、緑、青の各コンポーネントに8ビットずつ使用されます。

### Format32bppRgb {#Format32bppRgb}
```
public static final int Format32bppRgb
```


フォーマットがピクセルあたり32ビットで、赤、緑、青の各コンポーネントに8ビットずつ使用されることを指定します。残りの8ビットは使用されません。

### Format32bppArgb {#Format32bppArgb}
```
public static final int Format32bppArgb
```


フォーマットがピクセルあたり32ビットであることを指定します。アルファ、赤、緑、青の各コンポーネントに8ビットずつ使用されます。

### Format32bppPArgb {#Format32bppPArgb}
```
public static final int Format32bppPArgb
```


フォーマットがピクセルあたり32ビットで、アルファ、赤、緑、青の各コンポーネントに8ビットずつ使用されることを指定します。赤、緑、青のコンポーネントはアルファコンポーネントに従って事前乗算されます。

### Format48bppRgb {#Format48bppRgb}
```
public static final int Format48bppRgb
```


フォーマットがピクセルあたり48ビットであることを指定します。赤、緑、青の各コンポーネントに16ビットずつ使用されます。

### Format64bppArgb {#Format64bppArgb}
```
public static final int Format64bppArgb
```


フォーマットがピクセルあたり64ビットであることを指定します。アルファ、赤、緑、青の各コンポーネントに16ビットずつ使用されます。

### Format64bppPArgb {#Format64bppPArgb}
```
public static final int Format64bppPArgb
```


フォーマットがピクセルあたり64ビットで、アルファ、赤、緑、青の各コンポーネントに16ビットずつ使用されることを指定します。赤、緑、青のコンポーネントはアルファコンポーネントに従って事前乗算されます。

### Max {#Max}
```
public static final int Max
```


The maximum value for this enumeration.

