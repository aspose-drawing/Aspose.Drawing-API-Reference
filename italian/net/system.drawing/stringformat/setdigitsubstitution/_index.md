---
title: SetDigitSubstitution
second_title: Aspose.Drawing per .NET API Reference
description: Specifica la lingua e il metodo da utilizzare quando le cifre locali vengono sostituite con quelle occidentali.
type: docs
weight: 140
url: /it/net/system.drawing/stringformat/setdigitsubstitution/
---
## StringFormat.SetDigitSubstitution method

Specifica la lingua e il metodo da utilizzare quando le cifre locali vengono sostituite con quelle occidentali.

```csharp
public void SetDigitSubstitution(int language, StringDigitSubstitute substitute)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| language | Int32 | Un identificatore di lingua NLS (National Language Support) che identifica la lingua che verrà utilizzata quando le cifre locali verranno sostituite con quelle occidentali. È possibile passare ilLCID proprietà di a CultureInfo oggetto come identificatore di lingua NLS. Ad esempio, supponiamo di creare unCultureInfo oggetto by passando la stringa`"ar-EG"` ad unCultureInfo costruttore. Se si passa ilLCID proprietà di quel CultureInfo oggetto insieme a Traditional al Int32,StringDigitSubstitute)metodo, le cifre arabo-indiane verranno sostituite con le cifre occidentali al momento della visualizzazione. |
| substitute | StringDigitSubstitute | Un elemento delStringDigitSubstitute enumerazione che specifica come vengono visualizzate le cifre. |

### Guarda anche

* enum [StringDigitSubstitute](../../stringdigitsubstitute)
* class [StringFormat](../../stringformat)
* spazio dei nomi [System.Drawing](../../stringformat)
* assemblea [Aspose.Drawing](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Drawing.dll -->