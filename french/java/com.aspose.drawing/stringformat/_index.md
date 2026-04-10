---
title: StringFormat
second_title: Référence de l'API Aspose.Drawing pour Java
description: Encapsule les informations de mise en page du texte telles que l'orientation d'alignement et les manipulations d'affichage des tabulations, comme l'insertion d'ellipses, la substitution de chiffres nationaux et les fonctionnalités OpenType.
type: docs
weight: 47
url: /fr/java/com.aspose.drawing/stringformat/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public final class StringFormat implements System.IDisposable
```

Encapsule les informations de mise en page du texte (telles que l'alignement, l'orientation et les tabulations) les manipulations d'affichage (telles que l'insertion d'ellipse et la substitution de chiffres nationaux) et les fonctionnalités OpenType. Cette classe ne peut pas être héritée.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [StringFormat()](#StringFormat--) | Initialise une nouvelle instance de la classe [StringFormat](../../com.aspose.drawing/stringformat). |
| [StringFormat(StringFormat format)](#StringFormat-com.aspose.drawing.StringFormat-) | Initialise une nouvelle instance de la classe [StringFormat](../../com.aspose.drawing/stringformat) à partir de l'objet [StringFormat](../../com.aspose.drawing/stringformat) existant spécifié. |
| [StringFormat(int options, int language)](#StringFormat-int-int-) | Initialise une nouvelle instance de la classe [StringFormat](../../com.aspose.drawing/stringformat) avec l'énumération [StringFormatFlags](../../com.aspose.drawing/stringformatflags) spécifiée et la langue. |
| [StringFormat(int options)](#StringFormat-int-) | Initialise une nouvelle instance de la classe [StringFormat](../../com.aspose.drawing/stringformat) avec l'énumération [StringFormatFlags](../../com.aspose.drawing/stringformatflags) spécifiée. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [setDigitSubstitutionLanguage(int value)](#setDigitSubstitutionLanguage-int-) |  |
| [setDigitSubstitutionMethod(int value)](#setDigitSubstitutionMethod-int-) |  |
| [getFirstTabOffset()](#getFirstTabOffset--) |  |
| [getGenericDefault()](#getGenericDefault--) | Obtient un objet [StringFormat](../../com.aspose.drawing/stringformat) générique par défaut. |
| [getGenericTypographic()](#getGenericTypographic--) | Obtient un objet [StringFormat](../../com.aspose.drawing/stringformat) typographique générique. |
| [getFormatFlags()](#getFormatFlags--) | Obtient ou définit une énumération [StringFormatFlags](../../com.aspose.drawing/stringformatflags) qui contient des informations de formatage. |
| [setFormatFlags(int value)](#setFormatFlags-int-) | Obtient ou définit une énumération [StringFormatFlags](../../com.aspose.drawing/stringformatflags) qui contient des informations de formatage. |
| [getAlignment()](#getAlignment--) | Obtient ou définit les informations d'alignement du texte sur le plan vertical. |
| [setAlignment(int value)](#setAlignment-int-) | Obtient ou définit les informations d'alignement du texte sur le plan vertical. |
| [getLineAlignment()](#getLineAlignment--) | Obtient ou définit l'alignement de ligne sur le plan horizontal. |
| [setLineAlignment(int value)](#setLineAlignment-int-) | Obtient ou définit l'alignement de ligne sur le plan horizontal. |
| [getHotkeyPrefix()](#getHotkeyPrefix--) | Obtient ou définit l'objet `HotkeyPrefix`([.getHotkeyPrefix](../../null/\#getHotkeyPrefix)/[.setHotkeyPrefix(int)](../../null/\#setHotkeyPrefix-int-)) pour cet objet [StringFormat](../../com.aspose.drawing/stringformat). |
| [setHotkeyPrefix(int value)](#setHotkeyPrefix-int-) | Obtient ou définit l'objet `HotkeyPrefix`([.getHotkeyPrefix](../../null/\#getHotkeyPrefix)/[.setHotkeyPrefix(int)](../../null/\#setHotkeyPrefix-int-)) pour cet objet [StringFormat](../../com.aspose.drawing/stringformat). |
| [getTrimming()](#getTrimming--) | Obtient ou définit l'énumération [StringTrimming](../../com.aspose.drawing/stringtrimming) pour cet objet [StringFormat](../../com.aspose.drawing/stringformat). |
| [setTrimming(int value)](#setTrimming-int-) | Obtient ou définit l'énumération [StringTrimming](../../com.aspose.drawing/stringtrimming) pour cet objet [StringFormat](../../com.aspose.drawing/stringformat). |
| [getDigitSubstitutionLanguage()](#getDigitSubstitutionLanguage--) | Obtient la langue utilisée lorsque les chiffres locaux sont substitués aux chiffres occidentaux. |
| [getDigitSubstitutionMethod()](#getDigitSubstitutionMethod--) | Obtient la méthode à utiliser pour la substitution de chiffres. |
| [dispose()](#dispose--) | Libère toutes les ressources utilisées par cet objet [StringFormat](../../com.aspose.drawing/stringformat). |
| [deepClone()](#deepClone--) | Crée une copie exacte de cet objet [StringFormat](../../com.aspose.drawing/stringformat). |
| [getTabStops(float[] firstTabOffset)](#getTabStops-float---) | Obtient les tabulations pour cet objet [StringFormat](../../com.aspose.drawing/stringformat). |
| [getTabStops()](#getTabStops--) | Obtient un tableau de distances entre les tabulations dans les unités spécifiées par la propriété `Aspose.Imaging.getGraphics().PageUnit`. |
| [setTabStops(float firstTabOffset, float[] tabStops)](#setTabStops-float-float---) | Définit les tabulations pour cet objet [StringFormat](../../com.aspose.drawing/stringformat). |
| [setDigitSubstitution(int language, int substitute)](#setDigitSubstitution-int-int-) | Spécifie la langue et la méthode à utiliser lorsque les chiffres locaux sont substitués aux chiffres occidentaux. |
| [setMeasurableCharacterRanges(CharacterRange[] ranges)](#setMeasurableCharacterRanges-com.aspose.drawing.CharacterRange---) | Spécifie un tableau de structures [CharacterRange](../../com.aspose.drawing/characterrange) qui représentent les plages de caractères mesurées par un appel à la méthode `MeasureCharacterRanges`. |
### StringFormat() {#StringFormat--}
```
public StringFormat()
```


Initialise une nouvelle instance de la classe [StringFormat](../../com.aspose.drawing/stringformat).

### StringFormat(StringFormat format) {#StringFormat-com.aspose.drawing.StringFormat-}
```
public StringFormat(StringFormat format)
```


Initialise une nouvelle instance de la classe [StringFormat](../../com.aspose.drawing/stringformat) à partir de l'objet [StringFormat](../../com.aspose.drawing/stringformat) existant spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| format | [StringFormat](../../com.aspose.drawing/stringformat) | L'objet [StringFormat](../../com.aspose.drawing/stringformat) à partir duquel initialiser le nouvel objet [StringFormat](../../com.aspose.drawing/stringformat). |

### StringFormat(int options, int language) {#StringFormat-int-int-}
```
public StringFormat(int options, int language)
```


Initialise une nouvelle instance de la classe [StringFormat](../../com.aspose.drawing/stringformat) avec l'énumération [StringFormatFlags](../../com.aspose.drawing/stringformatflags) spécifiée et la langue.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| options | int | L'énumération [StringFormatFlags](../../com.aspose.drawing/stringformatflags) pour le nouvel objet [StringFormat](../../com.aspose.drawing/stringformat). |
| langue | int | Une valeur qui indique la langue du texte. |

### StringFormat(int options) {#StringFormat-int-}
```
public StringFormat(int options)
```


Initialise une nouvelle instance de la classe [StringFormat](../../com.aspose.drawing/stringformat) avec l'énumération [StringFormatFlags](../../com.aspose.drawing/stringformatflags) spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| options | int | L'énumération [StringFormatFlags](../../com.aspose.drawing/stringformatflags) pour le nouvel objet [StringFormat](../../com.aspose.drawing/stringformat). |

### setDigitSubstitutionLanguage(int value) {#setDigitSubstitutionLanguage-int-}
```
public void setDigitSubstitutionLanguage(int value)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### setDigitSubstitutionMethod(int value) {#setDigitSubstitutionMethod-int-}
```
public void setDigitSubstitutionMethod(int value)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getFirstTabOffset() {#getFirstTabOffset--}
```
public float getFirstTabOffset()
```




**Returns:**
float
### getGenericDefault() {#getGenericDefault--}
```
public static StringFormat getGenericDefault()
```


Obtient un objet [StringFormat](../../com.aspose.drawing/stringformat) générique par défaut.

**Returns:**
[StringFormat](../../com.aspose.drawing/stringformat)
### getGenericTypographic() {#getGenericTypographic--}
```
public static StringFormat getGenericTypographic()
```


Obtient un objet [StringFormat](../../com.aspose.drawing/stringformat) typographique générique.

**Returns:**
[StringFormat](../../com.aspose.drawing/stringformat) - A generic typographic [StringFormat](../../com.aspose.drawing/stringformat) object.
### getFormatFlags() {#getFormatFlags--}
```
public int getFormatFlags()
```


Obtient ou définit une énumération [StringFormatFlags](../../com.aspose.drawing/stringformatflags) qui contient des informations de formatage.

**Returns:**
int
### setFormatFlags(int value) {#setFormatFlags-int-}
```
public void setFormatFlags(int value)
```


Obtient ou définit une énumération [StringFormatFlags](../../com.aspose.drawing/stringformatflags) qui contient des informations de formatage.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getAlignment() {#getAlignment--}
```
public int getAlignment()
```


Obtient ou définit les informations d'alignement du texte sur le plan vertical.

**Returns:**
int
### setAlignment(int value) {#setAlignment-int-}
```
public void setAlignment(int value)
```


Obtient ou définit les informations d'alignement du texte sur le plan vertical.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getLineAlignment() {#getLineAlignment--}
```
public int getLineAlignment()
```


Obtient ou définit l'alignement de ligne sur le plan horizontal.

**Returns:**
int
### setLineAlignment(int value) {#setLineAlignment-int-}
```
public void setLineAlignment(int value)
```


Obtient ou définit l'alignement de ligne sur le plan horizontal.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getHotkeyPrefix() {#getHotkeyPrefix--}
```
public int getHotkeyPrefix()
```


Obtient ou définit l'objet `HotkeyPrefix`([.getHotkeyPrefix](../../null/\#getHotkeyPrefix)/[.setHotkeyPrefix(int)](../../null/\#setHotkeyPrefix-int-)) pour cet objet [StringFormat](../../com.aspose.drawing/stringformat).

**Returns:**
int
### setHotkeyPrefix(int value) {#setHotkeyPrefix-int-}
```
public void setHotkeyPrefix(int value)
```


Obtient ou définit l'objet `HotkeyPrefix`([.getHotkeyPrefix](../../null/\#getHotkeyPrefix)/[.setHotkeyPrefix(int)](../../null/\#setHotkeyPrefix-int-)) pour cet objet [StringFormat](../../com.aspose.drawing/stringformat).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getTrimming() {#getTrimming--}
```
public int getTrimming()
```


Obtient ou définit l'énumération [StringTrimming](../../com.aspose.drawing/stringtrimming) pour cet objet [StringFormat](../../com.aspose.drawing/stringformat).

**Returns:**
int
### setTrimming(int value) {#setTrimming-int-}
```
public void setTrimming(int value)
```


Obtient ou définit l'énumération [StringTrimming](../../com.aspose.drawing/stringtrimming) pour cet objet [StringFormat](../../com.aspose.drawing/stringformat).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getDigitSubstitutionLanguage() {#getDigitSubstitutionLanguage--}
```
public int getDigitSubstitutionLanguage()
```


Obtient la langue utilisée lorsque les chiffres locaux sont substitués aux chiffres occidentaux.

**Returns:**
int - Un identifiant de langue du support linguistique national (NLS) qui identifie la langue qui sera utilisée lorsque les chiffres locaux sont substitués aux chiffres occidentaux. Vous pouvez transmettre la propriété `System.Globalization.CultureInfo.LCID` d'un objet java.util.Locale comme identifiant de langue NLS. Par exemple, supposons que vous créez un objet java.util.Locale en passant la chaîne \"ar-EG\" au constructeur java.util.Locale. Si vous transmettez la propriété `System.Globalization.CultureInfo.LCID` de cet objet java.util.Locale ainsi que `StringDigitSubstitute.Traditional` à la méthode [.setDigitSubstitution(int,int)](../../null/\\#setDigitSubstitution-int-int-), alors les chiffres arabo-indien seront substitués aux chiffres occidentaux au moment de l'affichage.
### getDigitSubstitutionMethod() {#getDigitSubstitutionMethod--}
```
public int getDigitSubstitutionMethod()
```


Obtient la méthode à utiliser pour la substitution de chiffres.

**Returns:**
int - Une valeur d'énumération [StringDigitSubstitute](../../com.aspose.drawing/stringdigitsubstitute) qui spécifie comment substituer les caractères d'une chaîne qui ne peuvent pas être affichés parce qu'ils ne sont pas pris en charge par la police actuelle.
### dispose() {#dispose--}
```
public void dispose()
```


Libère toutes les ressources utilisées par cet objet [StringFormat](../../com.aspose.drawing/stringformat).

### deepClone() {#deepClone--}
```
public StringFormat deepClone()
```


Crée une copie exacte de cet objet [StringFormat](../../com.aspose.drawing/stringformat).

**Returns:**
[StringFormat](../../com.aspose.drawing/stringformat) - The [StringFormat](../../com.aspose.drawing/stringformat) object this method creates.
### getTabStops(float[] firstTabOffset) {#getTabStops-float---}
```
public float[] getTabStops(float[] firstTabOffset)
```


Obtient les tabulations pour cet objet [StringFormat](../../com.aspose.drawing/stringformat).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| firstTabOffset | float[] | Le nombre d'espaces entre le début d'une ligne de texte et le premier arrêt de tabulation. |

**Returns:**
float[] - Un tableau de distances (en nombre d'espaces) entre les arrêts de tabulation.
### getTabStops() {#getTabStops--}
```
public float[] getTabStops()
```


Obtient un tableau de distances entre les tabulations dans les unités spécifiées par la propriété `Aspose.Imaging.getGraphics().PageUnit`.

**Returns:**
float[] - Les arrêts de tabulation.

La propriété est introduite pour la méthode supprimée GetTabStops.
### setTabStops(float firstTabOffset, float[] tabStops) {#setTabStops-float-float---}
```
public void setTabStops(float firstTabOffset, float[] tabStops)
```


Définit les tabulations pour cet objet [StringFormat](../../com.aspose.drawing/stringformat).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| firstTabOffset | float | Le nombre d'espaces entre le début d'une ligne de texte et le premier arrêt de tabulation. |
| tabStops | float[] | Un tableau de distances entre les arrêts de tabulation dans les unités spécifiées par la propriété Graphics.PageUnit. |

### setDigitSubstitution(int language, int substitute) {#setDigitSubstitution-int-int-}
```
public void setDigitSubstitution(int language, int substitute)
```


Spécifie la langue et la méthode à utiliser lorsque les chiffres locaux sont substitués aux chiffres occidentaux.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| langue | int | Un identifiant de langue du support linguistique national (NLS) qui identifie la langue qui sera utilisée lorsque les chiffres locaux sont substitués aux chiffres occidentaux. Vous pouvez transmettre la propriété `System.Globalization.CultureInfo.LCID` d'un objet java.util.Locale comme identifiant de langue NLS. Par exemple, supposons que vous créez un objet java.util.Locale en passant la chaîne `\"ar-EG\"` au constructeur java.util.Locale. Si vous transmettez la propriété `System.Globalization.CultureInfo.LCID` de cet objet java.util.Locale ainsi que `StringDigitSubstitute.Traditional` à la méthode `M:StringFormat.SetDigitSubstitution(System.Int32,StringDigitSubstitute)`, alors les chiffres arabo-indien seront substitués aux chiffres occidentaux au moment de l'affichage. |
| substitute | int | Un élément de l'énumération [StringDigitSubstitute](../../com.aspose.drawing/stringdigitsubstitute) qui spécifie comment les chiffres sont affichés. |

### setMeasurableCharacterRanges(CharacterRange[] ranges) {#setMeasurableCharacterRanges-com.aspose.drawing.CharacterRange---}
```
public void setMeasurableCharacterRanges(CharacterRange[] ranges)
```


Spécifie un tableau de structures [CharacterRange](../../com.aspose.drawing/characterrange) qui représentent les plages de caractères mesurées par un appel à la méthode `MeasureCharacterRanges`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| ranges | [CharacterRange\[\]](../../com.aspose.drawing/characterrange) | Un tableau de structures [CharacterRange](../../com.aspose.drawing/characterrange) qui spécifient les plages de caractères mesurées par un appel à la méthode `MeasureCharacterRanges`. |

