---
title: PrivateFontCollection
second_title: Справочник API Aspose.Drawing для Java
description: Предоставляет коллекцию семейств шрифтов, построенных из файлов шрифтов, предоставляемых клиентским приложением.
type: docs
weight: 13
url: /ru/java/com.aspose.drawing.text/privatefontcollection/
---
**Inheritance:**
java.lang.Object, [com.aspose.drawing.FontCollection](../../com.aspose.drawing/fontcollection)
```
public final class PrivateFontCollection extends FontCollection
```

Предоставляет коллекцию семейств шрифтов, построенных из файлов шрифтов, предоставляемых клиентским приложением.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [PrivateFontCollection()](#PrivateFontCollection--) | Инициализирует новый экземпляр класса [PrivateFontCollection](../../com.aspose.drawing.text/privatefontcollection). |
## Методы

| Метод | Описание |
| --- | --- |
| [addFontFile(String filename)](#addFontFile-java.lang.String-) | Добавляет шрифт из указанного файла в эту [PrivateFontCollection](../../com.aspose.drawing.text/privatefontcollection). |
| [addMemoryFont(byte[] memory, int length)](#addMemoryFont-byte---int-) | Добавляет шрифт, находящийся в системной памяти, в эту [PrivateFontCollection](../../com.aspose.drawing.text/privatefontcollection). |
### PrivateFontCollection() {#PrivateFontCollection--}
```
public PrivateFontCollection()
```


Инициализирует новый экземпляр класса [PrivateFontCollection](../../com.aspose.drawing.text/privatefontcollection).

### addFontFile(String filename) {#addFontFile-java.lang.String-}
```
public void addFontFile(String filename)
```


Добавляет шрифт из указанного файла в эту [PrivateFontCollection](../../com.aspose.drawing.text/privatefontcollection).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| filename | java.lang.String | Строка, содержащая имя файла шрифта для добавления. |

### addMemoryFont(byte[] memory, int length) {#addMemoryFont-byte---int-}
```
public void addMemoryFont(byte[] memory, int length)
```


Добавляет шрифт, находящийся в системной памяти, в эту [PrivateFontCollection](../../com.aspose.drawing.text/privatefontcollection).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| память | byte[] | Адрес памяти шрифта для добавления. |
| length | int | Длина памяти шрифта для добавления. |

