---
title: SetDigitSubstitution
second_title: Référence de l'API Aspose.Drawing pour .NET
description: Spécifie la langue et la méthode à utiliser lorsque des chiffres locaux sont remplacés par des chiffres occidentaux.
type: docs
weight: 140
url: /fr/net/system.drawing/stringformat/setdigitsubstitution/
---
## StringFormat.SetDigitSubstitution method

Spécifie la langue et la méthode à utiliser lorsque des chiffres locaux sont remplacés par des chiffres occidentaux.

```csharp
public void SetDigitSubstitution(int language, StringDigitSubstitute substitute)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| language | Int32 | Un identifiant de langue National Language Support (NLS) qui identifie la langue qui sera utilisée lorsque des chiffres locaux seront remplacés par des chiffres occidentaux. Vous pouvez passer leLCID propriété de a CultureInfo objet comme identifiant de langue NLS. Par exemple, supposons que vous créez unCultureInfo objet by passant la chaîne`"ar-EG"` à unCultureInfo constructeur. Si vous passez leLCID propriété de that CultureInfo objet avec Traditional au Int32,StringDigitSubstitute)méthode, puis les chiffres arabo-indiens seront remplacés par les chiffres occidentaux au moment de l'affichage. |
| substitute | StringDigitSubstitute | Un élément de laStringDigitSubstitute énumération qui spécifie comment les chiffres sont affichés. |

### Voir également

* enum [StringDigitSubstitute](../../stringdigitsubstitute)
* class [StringFormat](../../stringformat)
* espace de noms [System.Drawing](../../stringformat)
* Assemblée [Aspose.Drawing](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Drawing.dll -->
