---
title: DigitSubstitutionLanguage
second_title: Справочник по API Aspose.Drawing для .NET
description: Получает язык используемый при замене западных цифр местными цифрами.
type: docs
weight: 50
url: /ru/net/system.drawing/stringformat/digitsubstitutionlanguage/
---
## StringFormat.DigitSubstitutionLanguage property

Получает язык, используемый при замене западных цифр местными цифрами.

```csharp
public int DigitSubstitutionLanguage { get; }
```

### Возвращаемое значение

Идентификатор языка поддержки национальных языков (NLS), определяющий язык, который будет использоваться при замене западных цифр местными цифрами. Вы можете пройтиLCID собственностьCultureInfo объект как идентификатор языка NLS. Например, предположим, что вы создаетеCultureInfoобъект, передав строку "ar-EG" вCultureInfo конструктор. Если вы пройдетеLCID property этогоCultureInfo объект вместе с.Traditional to [`SetDigitSubstitution`](../setdigitsubstitution) метод, то арабо-индийские цифры будут заменены на западных цифр во время отображения.

### Смотрите также

* class [StringFormat](../../stringformat)
* пространство имен [System.Drawing](../../stringformat)
* сборка [Aspose.Drawing](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Drawing.dll -->
