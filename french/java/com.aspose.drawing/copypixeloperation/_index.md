---
title: CopyPixelOperation
second_title: Référence de l'API Aspose.Drawing pour Java
description: Détermine comment la couleur source dans une opération de copie de pixel est combinée avec la couleur de destination pour obtenir une couleur finale.
type: docs
weight: 18
url: /fr/java/com.aspose.drawing/copypixeloperation/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class CopyPixelOperation extends System.Enum
```

Détermine comment la couleur source dans une opération de copie de pixel est combinée avec la couleur de destination pour obtenir une couleur finale.
## Champs

| Champ | Description |
| --- | --- |
| [NoMirrorBitmap](#NoMirrorBitmap) | Le bitmap n'est pas reflété. |
| [Blackness](#Blackness) | La zone de destination est remplie en utilisant la couleur associée à l'index 0 dans la palette physique. |
| [NotSourceErase](#NotSourceErase) | Les couleurs source et destination sont combinées en utilisant l'opérateur booléen `OR`, puis la couleur résultante est inversée. |
| [NotSourceCopy](#NotSourceCopy) | La zone source inversée est copiée vers la destination. |
| [SourceErase](#SourceErase) | Les couleurs inversées de la zone de destination sont combinées avec les couleurs de la zone source en utilisant l'opérateur booléen `AND`. |
| [DestinationInvert](#DestinationInvert) | La zone de destination est inversée. |
| [PatInvert](#PatInvert) | Les couleurs du pinceau actuellement sélectionné dans le contexte de périphérique de destination sont combinées avec les couleurs de la destination en utilisant l'opérateur booléen `XOR`. |
| [SourceInvert](#SourceInvert) | Les couleurs des zones source et destination sont combinées en utilisant l'opérateur booléen `XOR`. |
| [SourceAnd](#SourceAnd) | Les couleurs des zones source et destination sont combinées en utilisant l'opérateur booléen `AND`. |
| [MergePaint](#MergePaint) | Les couleurs de la zone source inversée sont fusionnées avec les couleurs de la zone de destination en utilisant l'opérateur booléen `OR`. |
| [MergeCopy](#MergeCopy) | Les couleurs de la zone source sont fusionnées avec les couleurs du pinceau sélectionné du contexte de périphérique de destination en utilisant l'opérateur booléen `AND`. |
| [SourceCopy](#SourceCopy) | La zone source est copiée directement vers la zone de destination. |
| [SourcePaint](#SourcePaint) | Les couleurs des zones source et destination sont combinées en utilisant l'opérateur booléen `OR`. |
| [PatCopy](#PatCopy) | Le pinceau actuellement sélectionné dans le contexte de périphérique de destination est copié vers le bitmap de destination. |
| [PatPaint](#PatPaint) | Les couleurs du pinceau actuellement sélectionné dans le contexte de périphérique de destination sont combinées avec les couleurs de la zone source inversée en utilisant l'opérateur booléen `OR`. |
| [Whiteness](#Whiteness) | La zone de destination est remplie en utilisant la couleur associée à l'index 1 dans la palette physique. |
| [CaptureBlt](#CaptureBlt) | Les fenêtres superposées au-dessus de votre fenêtre sont incluses dans l'image résultante. |
### NoMirrorBitmap {#NoMirrorBitmap}
```
public static final int NoMirrorBitmap
```


Le bitmap n'est pas reflété.

### Blackness {#Blackness}
```
public static final int Blackness
```


La zone de destination est remplie en utilisant la couleur associée à l'index 0 dans la palette physique. (Cette couleur est noire pour la palette physique par défaut.)

### NotSourceErase {#NotSourceErase}
```
public static final int NotSourceErase
```


Les couleurs source et destination sont combinées en utilisant l'opérateur booléen `OR`, puis la couleur résultante est inversée.

### NotSourceCopy {#NotSourceCopy}
```
public static final int NotSourceCopy
```


La zone source inversée est copiée vers la destination.

### SourceErase {#SourceErase}
```
public static final int SourceErase
```


Les couleurs inversées de la zone de destination sont combinées avec les couleurs de la zone source en utilisant l'opérateur booléen `AND`.

### DestinationInvert {#DestinationInvert}
```
public static final int DestinationInvert
```


La zone de destination est inversée.

### PatInvert {#PatInvert}
```
public static final int PatInvert
```


Les couleurs du pinceau actuellement sélectionné dans le contexte de périphérique de destination sont combinées avec les couleurs de la destination en utilisant l'opérateur booléen `XOR`.

### SourceInvert {#SourceInvert}
```
public static final int SourceInvert
```


Les couleurs des zones source et destination sont combinées en utilisant l'opérateur booléen `XOR`.

### SourceAnd {#SourceAnd}
```
public static final int SourceAnd
```


Les couleurs des zones source et destination sont combinées en utilisant l'opérateur booléen `AND`.

### MergePaint {#MergePaint}
```
public static final int MergePaint
```


Les couleurs de la zone source inversée sont fusionnées avec les couleurs de la zone de destination en utilisant l'opérateur booléen `OR`.

### MergeCopy {#MergeCopy}
```
public static final int MergeCopy
```


Les couleurs de la zone source sont fusionnées avec les couleurs du pinceau sélectionné du contexte de périphérique de destination en utilisant l'opérateur booléen `AND`.

### SourceCopy {#SourceCopy}
```
public static final int SourceCopy
```


La zone source est copiée directement vers la zone de destination.

### SourcePaint {#SourcePaint}
```
public static final int SourcePaint
```


Les couleurs des zones source et destination sont combinées en utilisant l'opérateur booléen `OR`.

### PatCopy {#PatCopy}
```
public static final int PatCopy
```


Le pinceau actuellement sélectionné dans le contexte de périphérique de destination est copié vers le bitmap de destination.

### PatPaint {#PatPaint}
```
public static final int PatPaint
```


Les couleurs du pinceau actuellement sélectionnées dans le contexte de périphérique de destination sont combinées avec les couleurs de la zone source inversée en utilisant l'opérateur booléen `OR`. Le résultat de cette opération est combiné avec les couleurs de la zone de destination en utilisant l'opérateur booléen `OR`.

### Whiteness {#Whiteness}
```
public static final int Whiteness
```


La zone de destination est remplie en utilisant la couleur associée à l'index 1 dans la palette physique. (Cette couleur est blanche pour la palette physique par défaut.)

### CaptureBlt {#CaptureBlt}
```
public static final int CaptureBlt
```


Les fenêtres superposées au-dessus de votre fenêtre sont incluses dans l'image résultante. Par défaut, l'image ne contient que votre fenêtre. Notez que cela ne peut généralement pas être utilisé pour les contextes de périphérique d'impression.

