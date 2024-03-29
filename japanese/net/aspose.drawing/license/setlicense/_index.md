---
title: License.SetLicense
second_title: Aspose.Drawing for .NET API リファレンス
description: License 方法. コンポーネントのライセンスを取得します
type: docs
weight: 20
url: /ja/net/aspose.drawing/license/setlicense/
---
## SetLicense(string) {#setlicense_1}

コンポーネントのライセンスを取得します。

```csharp
public void SetLicense(string licenseName)
```

### 備考

次の場所でライセンスを見つけようとします。

1. 明示的なパス。

2. Aspose コンポーネント アセンブリを含むフォルダー。

3. クライアントの呼び出しアセンブリを含むフォルダー。

4. エントリ (スタートアップ) アセンブリを含むフォルダー。

5. クライアントの呼び出しアセンブリに埋め込まれたリソース。

**ノート：**.NET Compact Framework では、次の場所でのみライセンスを見つけようとします。

1. 明示的なパス。

2. クライアントの呼び出しアセンブリに埋め込まれたリソース。

2. Aspose コンポーネント JAR ファイルを含むフォルダー。

3. クライアントの呼び出し JAR ファイルを含むフォルダー。

### 例

この例では、 を含むフォルダーで MyLicense.lic という名前のライセンス ファイルを検索しようとします。 呼び出しアセンブリを含むフォルダー内のコンポーネント、 エントリ アセンブリのフォルダー内、および呼び出しアセンブリの埋め込みリソース内のコンポーネント.

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");


[Visual Basic]

Dim license As License = New License
license.SetLicense("MyLicense.lic")
```

コンポーネント jar ファイル:

```csharp
License license = new License();
license.setLicense("MyLicense.lic");
```

完全または短いファイル名にすることができますまたは埋め込みリソースの名前. 空の文字列を使用して、評価モードに切り替えます。

### 関連項目

* class [License](../)
* 名前空間 [Aspose.Drawing](../../license/)
* 組み立て [Aspose.Drawing](../../../)

---

## SetLicense(Stream) {#setlicense}

コンポーネントのライセンスを取得します。

```csharp
public void SetLicense(Stream stream)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| stream | Stream | ライセンスを含むストリーム。 |

### 備考

このメソッドを使用して、ストリームからライセンスをロードします。

### 例

```csharp
[C#]

License license = new License();
license.SetLicense(myStream);


[Visual Basic]

Dim license as License = new License
license.SetLicense(myStream)

License license = new License();
license.setLicense(myStream);
```

### 関連項目

* class [License](../)
* 名前空間 [Aspose.Drawing](../../license/)
* 組み立て [Aspose.Drawing](../../../)


