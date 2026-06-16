---
title: ColorMatrixFlag
second_title: Aspose.Drawing for Java API リファレンス
description: カラーおよびグレースケール調整設定の影響を受ける画像と色のタイプを指定します。
type: docs
weight: 15
url: /ja/java/com.aspose.drawing.imaging/colormatrixflag/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ColorMatrixFlag extends System.Enum
```

カラーおよびグレースケール調整設定の影響を受ける画像と色のタイプを、[ImageAttributes](../../com.aspose.drawing.imaging/imageattributes) で指定します。
## フィールド

| フィールド | 説明 |
| --- | --- |
| [Default](#Default) | グレーの色調を含むすべてのカラー値は、同じカラー調整マトリックスで調整されます。 |
| [SkipGrays](#SkipGrays) | すべての色が調整されますが、グレーの色調は調整されません。 |
| [AltGrays](#AltGrays) | グレーの色調のみが調整されます。 |
### Default {#Default}
```
public static final int Default
```


グレーの色調を含むすべてのカラー値は、同じカラー調整マトリックスで調整されます。

### SkipGrays {#SkipGrays}
```
public static final int SkipGrays
```


すべての色が調整されますが、グレーの色調は調整されません。グレーの色調とは、赤、緑、青の各成分の値が同じである任意の色を指します。

### AltGrays {#AltGrays}
```
public static final int AltGrays
```


グレーの色調のみが調整されます。

