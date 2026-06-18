---
title: FontFamilyDefinition
second_title: Αναφορά API του Aspose.Drawing for Java
description: Ο ορισμός της οικογένειας γραμματοσειρών.
type: docs
weight: 25
url: /el/java/com.aspose.drawing/fontfamilydefinition/
---
**Inheritance:**
java.lang.Object
```
public class FontFamilyDefinition
```

Ο ορισμός της οικογένειας γραμματοσειρών.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [FontFamilyDefinition()](#FontFamilyDefinition--) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [FontFamilyDefinition](../../com.aspose.drawing/fontfamilydefinition). |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [addFontDefinition(int style, FontDefinitionExt fontDef)](#addFontDefinition-int-com.aspose.drawing.FontDefinitionExt-) | Προσθέτει τον ορισμό γραμματοσειράς στην οικογένεια γραμματοσειρών. |
| [getFontDefinition(int style)](#getFontDefinition-int-) | Αποκτά τον ορισμό γραμματοσειράς από την οικογένεια για συγκεκριμένο στυλ. |
| [matchesLocalizedFamilyName(String localizedFamilyName)](#matchesLocalizedFamilyName-java.lang.String-) | Ταιριάζει τα τοπικοποιημένα ονόματα οικογένειας σε αυτήν την οικογένεια. |
| [getFamilyName()](#getFamilyName--) | Αποκτά ένα όνομα οικογένειας αυτής της οικογένειας. |
### FontFamilyDefinition() {#FontFamilyDefinition--}
```
public FontFamilyDefinition()
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [FontFamilyDefinition](../../com.aspose.drawing/fontfamilydefinition).

### addFontDefinition(int style, FontDefinitionExt fontDef) {#addFontDefinition-int-com.aspose.drawing.FontDefinitionExt-}
```
public final void addFontDefinition(int style, FontDefinitionExt fontDef)
```


Προσθέτει τον ορισμό γραμματοσειράς στην οικογένεια γραμματοσειρών.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| στυλ | int | Το στυλ. |
| fontDef | [FontDefinitionExt](../../com.aspose.drawing/fontdefinitionext) | Ο ορισμός γραμματοσειράς. |

### getFontDefinition(int style) {#getFontDefinition-int-}
```
public final FontDefinitionExt getFontDefinition(int style)
```


Αποκτά τον ορισμό γραμματοσειράς από την οικογένεια για συγκεκριμένο στυλ.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| στυλ | int | Το στυλ. |

**Returns:**
[FontDefinitionExt](../../com.aspose.drawing/fontdefinitionext) - Returns font definition if exist for specified style, null otherwise.
### matchesLocalizedFamilyName(String localizedFamilyName) {#matchesLocalizedFamilyName-java.lang.String-}
```
public final boolean matchesLocalizedFamilyName(String localizedFamilyName)
```


Ταιριάζει τα τοπικοποιημένα ονόματα οικογένειας σε αυτήν την οικογένεια.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| localizedFamilyName | java.lang.String | Το τοπικοποιημένο όνομα οικογένειας. |

**Returns:**
boolean - true εάν αυτή η οικογένεια περιλαμβάνει το τοπικοποιημένο όνομα οικογένειας.
### getFamilyName() {#getFamilyName--}
```
public final String getFamilyName()
```


Αποκτά ένα όνομα οικογένειας αυτής της οικογένειας.

**Returns:**
java.lang.String - Το όνομα οικογένειας, ή null για μια κενή οικογένεια.
