---
title: Metered
second_title: Aspose.Drawing for Java API リファレンス
description: 統合用のメータリングメソッドを提供します。
type: docs
weight: 10
url: /ja/java/com.aspose.drawing.dynabic.metered/metered/
---
**Inheritance:**
java.lang.Object
```
public class Metered
```

統合用のメータリングメソッドを提供します。

この例では、metered の公開鍵と秘密鍵を設定しようとします。

`// the component jar file: Metered matered = new Metered(); matered.setMeteredKey("PublicKey", "PrivateKey"); `
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [Metered()](#Metered--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getConsumptionQuantity()](#getConsumptionQuantity--) | 消費ファイルサイズを取得します |
| [getConsumptionCredit()](#getConsumptionCredit--) | 消費クレジットを取得します |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | Sets metered public and private key |
| [equals(Object obj)](#equals-java.lang.Object-) | 指定された Object がこのインスタンスと等しいかどうかを判定します。 |
### Metered() {#Metered--}
```
public Metered()
```


### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static BigDecimal getConsumptionQuantity()
```


消費ファイルサイズを取得します

**Returns:**
java.math.BigDecimal - 消費ファイルサイズ
### getConsumptionCredit() {#getConsumptionCredit--}
```
public static BigDecimal getConsumptionCredit()
```


消費クレジットを取得します

**Returns:**
java.math.BigDecimal - 消費数量
### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public void setMeteredKey(String publicKey, String privateKey)
```


Sets metered public and private key

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| publicKey | java.lang.String | public key |
| privateKey | java.lang.String | private key |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


指定された Object がこのインスタンスと等しいかどうかを判定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| obj | java.lang.Object | このインスタンスと比較する Object。 |

**Returns:**
boolean - 指定された Object がこのインスタンスと等しい場合は `true`、それ以外は `false`。
