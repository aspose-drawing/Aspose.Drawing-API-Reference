---
title: CombineMode
second_title: Aspose.Drawing for Java API リファレンス
description: 異なるクリッピング領域をどのように結合できるかを指定します。
type: docs
weight: 13
url: /ja/java/com.aspose.drawing.drawing2d/combinemode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class CombineMode extends System.Enum
```

異なるクリッピング領域をどのように結合できるかを指定します。
## フィールド

| フィールド | 説明 |
| --- | --- |
| [Replace](#Replace) | 1 つのクリッピング領域が別の領域に置き換えられます。 |
| [Intersect](#Intersect) | 2 つのクリッピング領域は交差部分を取ることで結合されます。 |
| [Union](#Union) | 2 つのクリッピング領域は両方の合併を取ることで結合されます。 |
| [Xor](#Xor) | 2 つのクリッピング領域は、どちらか一方に含まれる領域のみを取り、両方に含まれる領域は除外して結合されます。 |
| [Exclude](#Exclude) | 既存の領域から新しい領域を除いた結果で、既存の領域が置き換えられることを指定します。 |
| [Complement](#Complement) | 新しい領域から既存の領域を除いた結果で、既存の領域が置き換えられることを指定します。 |
### Replace {#Replace}
```
public static final int Replace
```


1 つのクリッピング領域が別の領域に置き換えられます。

### Intersect {#Intersect}
```
public static final int Intersect
```


2 つのクリッピング領域は交差部分を取ることで結合されます。

### Union {#Union}
```
public static final int Union
```


2 つのクリッピング領域は両方の合併を取ることで結合されます。

### Xor {#Xor}
```
public static final int Xor
```


2 つのクリッピング領域は、どちらか一方に含まれる領域のみを取り、両方に含まれる領域は除外して結合されます。

### Exclude {#Exclude}
```
public static final int Exclude
```


既存の領域から新しい領域を除いた結果で、既存の領域が置き換えられることを指定します。別の言い方をすれば、新しい領域は既存の領域から除外されます。

### Complement {#Complement}
```
public static final int Complement
```


新しい領域から既存の領域を除いた結果で、既存の領域が置き換えられることを指定します。別の言い方をすれば、既存の領域は新しい領域から除外されます。

