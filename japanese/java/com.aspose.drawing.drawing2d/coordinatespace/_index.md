---
title: 座標空間
second_title: Aspose.Drawing for Java API リファレンス
description: 座標を評価する際に使用するシステムを指定します。
type: docs
weight: 16
url: /ja/java/com.aspose.drawing.drawing2d/coordinatespace/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class CoordinateSpace extends System.Enum
```

座標を評価する際に使用するシステムを指定します。
## フィールド

| フィールド | 説明 |
| --- | --- |
| [World](#World) | 座標がワールド座標コンテキストにあることを指定します。 |
| [Page](#Page) | 座標がページ座標コンテキストにあることを指定します。 |
| [Device](#Device) | 座標がデバイス座標コンテキストにあることを指定します。 |
### World {#World}
```
public static final int World
```


座標がワールド座標コンテキストにあることを指定します。ワールド座標は、モデリング環境などの非物理的環境で使用されます。

### Page {#Page}
```
public static final int Page
```


座標がページ座標コンテキストにあることを指定します。単位は Graphics.PageUnit プロパティで定義され、GraphicsUnit 列挙体の要素のいずれかでなければなりません。

### Device {#Device}
```
public static final int Device
```


座標がデバイス座標コンテキストにあることを指定します。コンピューター画面上では、デバイス座標は通常ピクセルで測定されます。

