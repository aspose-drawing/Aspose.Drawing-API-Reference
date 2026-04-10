---
title: PrivateFontCollection
second_title: Aspose.Drawing for Java API リファレンス
description: クライアントアプリケーションが提供するフォントファイルから構築されたフォントファミリのコレクションを提供します。
type: docs
weight: 13
url: /ja/java/com.aspose.drawing.text/privatefontcollection/
---
**Inheritance:**
java.lang.Object、[com.aspose.drawing.FontCollection](../../com.aspose.drawing/fontcollection)
```
public final class PrivateFontCollection extends FontCollection
```

クライアントアプリケーションが提供するフォントファイルから構築されたフォントファミリのコレクションを提供します。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [PrivateFontCollection()](#PrivateFontCollection--) | 新しい [PrivateFontCollection](../../com.aspose.drawing.text/privatefontcollection) クラスのインスタンスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [addFontFile(String filename)](#addFontFile-java.lang.String-) | 指定されたファイルからフォントをこの [PrivateFontCollection](../../com.aspose.drawing.text/privatefontcollection) に追加します。 |
| [addMemoryFont(byte[] memory, int length)](#addMemoryFont-byte---int-) | システムメモリに格納されたフォントをこの [PrivateFontCollection](../../com.aspose.drawing.text/privatefontcollection) に追加します。 |
### PrivateFontCollection() {#PrivateFontCollection--}
```
public PrivateFontCollection()
```


新しい [PrivateFontCollection](../../com.aspose.drawing.text/privatefontcollection) クラスのインスタンスを初期化します。

### addFontFile(String filename) {#addFontFile-java.lang.String-}
```
public void addFontFile(String filename)
```


指定されたファイルからフォントをこの [PrivateFontCollection](../../com.aspose.drawing.text/privatefontcollection) に追加します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| ファイル名 | java.lang.String | 追加するフォントのファイル名を含む文字列です。 |

### addMemoryFont(byte[] memory, int length) {#addMemoryFont-byte---int-}
```
public void addMemoryFont(byte[] memory, int length)
```


システムメモリに格納されたフォントをこの [PrivateFontCollection](../../com.aspose.drawing.text/privatefontcollection) に追加します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| メモリ | byte[] | 追加するフォントのメモリアドレスです。 |
| length | int | 追加するフォントのメモリ長です。 |

