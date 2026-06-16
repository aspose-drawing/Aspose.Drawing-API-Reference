---
title: MetafileType
second_title: Aspose.Drawing for Java API リファレンス
description: メタファイルのタイプを指定します。
type: docs
weight: 33
url: /ja/java/com.aspose.drawing.imaging/metafiletype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class MetafileType extends System.Enum
```

メタファイルのタイプを指定します。
## フィールド

| フィールド | 説明 |
| --- | --- |
| [Invalid](#Invalid) | GDI+ で認識されないメタファイル形式を指定します。 |
| [Wmf](#Wmf) | WMF（Windows Metafile）ファイルを指定します。 |
| [WmfPlaceable](#WmfPlaceable) | 先頭にプレース可能メタファイルヘッダーがある WMF（Windows Metafile）ファイルを指定します。 |
| [Emf](#Emf) | 拡張メタファイル（EMF）ファイルを指定します。 |
| [EmfPlusOnly](#EmfPlusOnly) | EMF+ ファイルを指定します。 |
| [EmfPlusDual](#EmfPlusDual) | EMF+ Dual ファイルを指定します。 |
### Invalid {#Invalid}
```
public static final int Invalid
```


GDI+ で認識されないメタファイル形式を指定します。

### Wmf {#Wmf}
```
public static final int Wmf
```


WMF（Windows Metafile）ファイルを指定します。このようなファイルは GDI レコードのみを含みます。

### WmfPlaceable {#WmfPlaceable}
```
public static final int WmfPlaceable
```


先頭にプレース可能メタファイルヘッダーがある WMF（Windows Metafile）ファイルを指定します。

### Emf {#Emf}
```
public static final int Emf
```


拡張メタファイル（EMF）ファイルを指定します。このようなファイルは GDI レコードのみを含みます。

### EmfPlusOnly {#EmfPlusOnly}
```
public static final int EmfPlusOnly
```


EMF+ ファイルを指定します。このファイルは GDI+ レコードのみを含み、GDI+ を使用して表示する必要があります。GDI を使用してレコードを表示すると、予測できない結果になる可能性があります。

### EmfPlusDual {#EmfPlusDual}
```
public static final int EmfPlusDual
```


EMF+ Dual ファイルを指定します。このファイルは GDI+ レコードと代替の GDI レコードの両方を含み、GDI または GDI+ のいずれかを使用して表示できます。GDI を使用してレコードを表示すると、品質が若干低下する可能性があります。

