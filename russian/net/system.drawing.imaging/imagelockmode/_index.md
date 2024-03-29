---
title: ImageLockMode
second_title: Справочник по API Aspose.Drawing для .NET
description: Определяет флаги которые передаются в параметр flagsLockBits../system.drawing/bitmap/lockbits метод. LockBits../system.drawing/bitmap/lockbits метод блокирует часть изображения  чтобы вы могли читать или записывать данные пикселей.
type: docs
weight: 780
url: /ru/net/system.drawing.imaging/imagelockmode/
---
## ImageLockMode enumeration

Определяет флаги, которые передаются в параметр flags[`LockBits`](../../system.drawing/bitmap/lockbits) метод. [`LockBits`](../../system.drawing/bitmap/lockbits) метод блокирует часть изображения , чтобы вы могли читать или записывать данные пикселей.

```csharp
public enum ImageLockMode
```

### Ценности

| Имя | Ценность | Описание |
| --- | --- | --- |
| ReadOnly | `1` | Указывает, что часть изображения заблокирована для чтения. |
| WriteOnly | `2` | Указывает, что часть изображения заблокирована для записи. |
| ReadWrite | `3` | Указывает, что часть изображения заблокирована для чтения или записи. |
| UserInputBuffer | `4` | Указывает, что буфер, используемый для чтения или записи данных пикселей, выделяется пользователем. Если этот флаг установлен,*flags* параметр[`LockBits`](../../system.drawing/bitmap/lockbits) служит входным параметром (и, возможно, выходным параметром). Если этот флаг снят, то*flags* параметр служит только выходным параметром. |

### Смотрите также

* пространство имен [System.Drawing.Imaging](../../system.drawing.imaging)
* сборка [Aspose.Drawing](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Drawing.dll -->
