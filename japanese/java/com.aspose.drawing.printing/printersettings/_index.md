---
title: PrinterSettings
second_title: Aspose.Drawing for Java API リファレンス
description: Windows Forms アプリケーションから印刷する際に、ドキュメントがどのように印刷されるか、印刷するプリンターを含む情報を指定します。
type: docs
weight: 16
url: /ja/java/com.aspose.drawing.printing/printersettings/
---
**Inheritance:**
java.lang.Object
```
public class PrinterSettings
```

Windows Forms アプリケーションから印刷する際に、印刷するプリンターを含む、ドキュメントがどのように印刷されるかに関する情報を指定します。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [PrinterSettings()](#PrinterSettings--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getFromPage()](#getFromPage--) | 印刷する最初のページ番号を取得します。 |
| [getPrintRange()](#getPrintRange--) | ユーザーが印刷するよう指定したページ番号を取得します。 |
| [getToPage()](#getToPage--) | 印刷する最後のページ番号を取得します。 |
| [getPrinterName()](#getPrinterName--) | 使用するプリンターの名前を取得します。 |
| [setPrinterName(String value)](#setPrinterName-java.lang.String-) | 使用するプリンターの名前を設定します。 |
### PrinterSettings() {#PrinterSettings--}
```
public PrinterSettings()
```


### getFromPage() {#getFromPage--}
```
public static int getFromPage()
```


印刷する最初のページ番号を取得します。

**Returns:**
int - 印刷する最初のページ番号。
### getPrintRange() {#getPrintRange--}
```
public static int getPrintRange()
```


ユーザーが印刷するよう指定したページ番号を取得します。

**Returns:**
int - `PrintRange`([.getPrintRange](../../null/\#getPrintRange)) のいずれかの値。
### getToPage() {#getToPage--}
```
public static int getToPage()
```


印刷する最後のページ番号を取得します。

**Returns:**
int - 印刷する最後のページ番号。
### getPrinterName() {#getPrinterName--}
```
public final String getPrinterName()
```


使用するプリンターの名前を取得します。

**Returns:**
java.lang.String - 使用するプリンターの名前。
### setPrinterName(String value) {#setPrinterName-java.lang.String-}
```
public final void setPrinterName(String value)
```


使用するプリンターの名前を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String | 使用するプリンターの名前。 |

