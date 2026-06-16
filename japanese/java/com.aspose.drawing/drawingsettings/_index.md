---
title: DrawingSettings
second_title: Aspose.Drawing for Java API リファレンス
description: まだ完全に実装されていない機能を使用する場合に、描画ライブラリの動作を調整できるようにします。
type: docs
weight: 19
url: /ja/java/com.aspose.drawing/drawingsettings/
---
**Inheritance:**
java.lang.Object
```
public final class DrawingSettings
```

まだ完全に実装されていない機能を使用する場合に、描画ライブラリの動作を調整できるようにします。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [DrawingSettings()](#DrawingSettings--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getStrictMode()](#getStrictMode--) | 未実装機能のより厳格な捕捉が有効かどうかを示す値を取得します。 |
| [setStrictMode(boolean value)](#setStrictMode-boolean-) | 未実装機能のより厳格な捕捉が有効かどうかを示す値を設定します。 |
### DrawingSettings() {#DrawingSettings--}
```
public DrawingSettings()
```


### getStrictMode() {#getStrictMode--}
```
public static boolean getStrictMode()
```


未実装機能のより厳格な捕捉が有効かどうかを示す値を取得します。

--------------------

true に設定すると、現在の実装で正しく動作しない機能/パラメーターを使用した場合、ライブラリは NotImplementedException をスローします。false に設定すると、いくつかのパラメーターが無視され、ユーザー プログラムが動作できるようになります。その場合、描画結果は GDI+ と比較して異なる見た目になる可能性があります。

**Returns:**
boolean - 未実装機能のより厳格な捕捉が有効かどうかを示す値。
### setStrictMode(boolean value) {#setStrictMode-boolean-}
```
public static void setStrictMode(boolean value)
```


未実装機能のより厳格な捕捉が有効かどうかを示す値を設定します。

--------------------

true に設定すると、現在の実装で正しく動作しない機能/パラメーターを使用した場合、ライブラリは NotImplementedException をスローします。false に設定すると、いくつかのパラメーターが無視され、ユーザー プログラムが動作できるようになります。その場合、描画結果は GDI+ と比較して異なる見た目になる可能性があります。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean | 未実装機能のより厳格な捕捉が有効かどうかを示す値。 |

