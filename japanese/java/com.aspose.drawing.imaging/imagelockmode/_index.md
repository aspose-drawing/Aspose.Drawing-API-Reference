---
title: ImageLockMode
second_title: Aspose.Drawing for Java API リファレンス
description: メソッドの flags パラメータに渡されるフラグを指定します。
type: docs
weight: 28
url: /ja/java/com.aspose.drawing.imaging/imagelockmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ImageLockMode extends System.Enum
```

メソッドの flags パラメータに渡されるフラグを指定します。 [Bitmap.lockBits(Rectangle, int, int)](../../com.aspose.drawing/bitmap\#lockBits-Rectangle--int--int-) メソッドは、画像の一部をロックしてピクセルデータを読み書きできるようにします。
## フィールド

| フィールド | 説明 |
| --- | --- |
| [ReadOnly](#ReadOnly) | 画像の一部が読み取り用にロックされていることを指定します。 |
| [WriteOnly](#WriteOnly) | 画像の一部が書き込み用にロックされていることを指定します。 |
| [ReadWrite](#ReadWrite) | 画像の一部が読み取りまたは書き込み用にロックされていることを指定します。 |
| [UserInputBuffer](#UserInputBuffer) | ピクセルデータの読み取りまたは書き込みに使用されるバッファがユーザーによって割り当てられることを指定します。 |
### ReadOnly {#ReadOnly}
```
public static final int ReadOnly
```


画像の一部が読み取り用にロックされていることを指定します。

### WriteOnly {#WriteOnly}
```
public static final int WriteOnly
```


画像の一部が書き込み用にロックされていることを指定します。

### ReadWrite {#ReadWrite}
```
public static final int ReadWrite
```


画像の一部が読み取りまたは書き込み用にロックされていることを指定します。

### UserInputBuffer {#UserInputBuffer}
```
public static final int UserInputBuffer
```


ピクセルデータの読み取りまたは書き込みに使用されるバッファがユーザーによって割り当てられることを指定します。このフラグが設定されている場合、[Bitmap.lockBits(Rectangle, int, int)](../../com.aspose.drawing/bitmap\#lockBits-Rectangle--int--int-) メソッドの `flags` パラメータは入力パラメータとして機能します（必要に応じて出力パラメータになることもあります）。このフラグがクリアされている場合、`flags` パラメータは出力パラメータとしてのみ機能します。

