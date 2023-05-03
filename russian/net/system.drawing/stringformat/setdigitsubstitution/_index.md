---
title: SetDigitSubstitution
second_title: Справочник по API Aspose.Drawing для .NET
description: Указывает язык и метод которые будут использоваться при замене западных цифр местными цифрами.
type: docs
weight: 140
url: /ru/net/system.drawing/stringformat/setdigitsubstitution/
---
## StringFormat.SetDigitSubstitution method

Указывает язык и метод, которые будут использоваться при замене западных цифр местными цифрами.

```csharp
public void SetDigitSubstitution(int language, StringDigitSubstitute substitute)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| language | Int32 | Идентификатор языка поддержки национальных языков (NLS), определяющий язык, который будет использоваться при замене западных цифр местными цифрами. Вы можете передатьLCID свойство a CultureInfo объект в качестве идентификатора языка NLS. Например, предположим, что вы создаетеCultureInfo объект by , передавая строку`"Ар-ЭГ"` кCultureInfo конструктор. Если вы пройдетеLCID свойство that CultureInfo объект вместе с Traditional к Int32,StringDigitSubstitute)метод, , то арабо-индийские цифры будут заменены западными цифрами во время отображения. |
| substitute | StringDigitSubstitute | ЭлементStringDigitSubstitute перечисление, определяющее способ отображения цифр. |

### Смотрите также

* enum [StringDigitSubstitute](../../stringdigitsubstitute)
* class [StringFormat](../../stringformat)
* пространство имен [System.Drawing](../../stringformat)
* сборка [Aspose.Drawing](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Drawing.dll -->