---
title: ImageLockMode
second_title: Référence de l'API Aspose.Drawing pour Java
description: Spécifie les indicateurs qui sont transmis au paramètre flags de la méthode.
type: docs
weight: 28
url: /fr/java/com.aspose.drawing.imaging/imagelockmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ImageLockMode extends System.Enum
```

Spécifie les indicateurs qui sont transmis au paramètre flags de la méthode [Bitmap.lockBits(Rectangle, int, int)](../../com.aspose.drawing/bitmap\#lockBits-Rectangle--int--int-). La méthode [Bitmap.lockBits(Rectangle, int, int)](../../com.aspose.drawing/bitmap\#lockBits-Rectangle--int--int-) verrouille une partie d'une image afin que vous puissiez lire ou écrire les données du pixel.
## Champs

| Champ | Description |
| --- | --- |
| [ReadOnly](#ReadOnly) | Spécifie qu'une partie de l'image est verrouillée en lecture. |
| [WriteOnly](#WriteOnly) | Spécifie qu'une partie de l'image est verrouillée en écriture. |
| [ReadWrite](#ReadWrite) | Spécifie qu'une partie de l'image est verrouillée en lecture ou en écriture. |
| [UserInputBuffer](#UserInputBuffer) | Spécifie que le tampon utilisé pour la lecture ou l'écriture des données du pixel est alloué par l'utilisateur. |
### ReadOnly {#ReadOnly}
```
public static final int ReadOnly
```


Spécifie qu'une partie de l'image est verrouillée en lecture.

### WriteOnly {#WriteOnly}
```
public static final int WriteOnly
```


Spécifie qu'une partie de l'image est verrouillée en écriture.

### ReadWrite {#ReadWrite}
```
public static final int ReadWrite
```


Spécifie qu'une partie de l'image est verrouillée en lecture ou en écriture.

### UserInputBuffer {#UserInputBuffer}
```
public static final int UserInputBuffer
```


Spécifie que le tampon utilisé pour la lecture ou l'écriture des données du pixel est alloué par l'utilisateur. Si cet indicateur est activé, le paramètre `flags` de la méthode [Bitmap.lockBits(Rectangle, int, int)](../../com.aspose.drawing/bitmap\#lockBits-Rectangle--int--int-) sert de paramètre d'entrée (et éventuellement de paramètre de sortie). Si cet indicateur est désactivé, le paramètre `flags` ne sert qu'à la sortie.

