---
title: GraphicsPathIterator
second_title: Référence de l'API Aspose.Drawing pour Java
description: Fournit la capacité d'itérer à travers les sous‑chemins dans un  et de tester les types de formes contenues dans chaque sous‑chemin.
type: docs
weight: 24
url: /fr/java/com.aspose.drawing.drawing2d/graphicspathiterator/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public final class GraphicsPathIterator implements System.IDisposable
```

Fournit la capacité d'itérer à travers les sous‑chemins d'un [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) et de tester les types de formes contenus dans chaque sous‑chemin. Cette classe ne peut pas être héritée.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [GraphicsPathIterator(GraphicsPath path)](#GraphicsPathIterator-com.aspose.drawing.drawing2d.GraphicsPath-) | Initialise une nouvelle instance de la classe [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator). |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getCount()](#getCount--) | Obtient le nombre de points dans le chemin. |
| [getSubpathCount()](#getSubpathCount--) | Obtient le nombre de sous‑chemins dans le chemin. |
| [dispose()](#dispose--) | Effectue les tâches définies par l'application associées à la libération, la remise ou la réinitialisation des ressources non gérées. |
| [copyData(PointF[][] points, byte[][] types, int startIndex, int endIndex)](#copyData-com.aspose.drawing.PointF-----byte-----int-int-) | Copie les tableaux de la propriété GraphicsPath.PathPoints et de la propriété GraphicsPath.PathTypes du [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) associé dans les deux tableaux spécifiés. |
| [enumerate(PointF[][] points, byte[][] types)](#enumerate-com.aspose.drawing.PointF-----byte-----) | Copie les tableaux de la propriété GraphicsPath.PathPoints et de la propriété GraphicsPath.PathTypes du [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) associé dans les deux tableaux spécifiés. |
| [hasCurve()](#hasCurve--) | Indique si le chemin associé à ce [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) contient une courbe. |
| [nextMarker(int[] startIndex, int[] endIndex)](#nextMarker-int---int---) | Incrémente le [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) vers le marqueur suivant dans le chemin et renvoie les index de début et de fin via les paramètres [out]. |
| [nextMarker(GraphicsPath path)](#nextMarker-com.aspose.drawing.drawing2d.GraphicsPath-) | Cet objet [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) possède un objet [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) qui lui est associé. |
| [nextPathType(byte[] pathType, int[] startIndex, int[] endIndex)](#nextPathType-byte---int---int---) | Obtient l'index de départ et l'index de fin du prochain groupe de points de données qui ont tous le même type. |
| [nextSubpath(int[] startIndex, int[] endIndex, boolean[] isClosed)](#nextSubpath-int---int---boolean---) | Déplace le [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) vers le sous‑chemin suivant dans le chemin. |
| [nextSubpath(GraphicsPath path, boolean[] isClosed)](#nextSubpath-com.aspose.drawing.drawing2d.GraphicsPath-boolean---) | Obtient la figure suivante (sous‑chemin) à partir du chemin associé de ce [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator). |
| [rewind()](#rewind--) | Rembobine ce [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) au début de son chemin associé. |
### GraphicsPathIterator(GraphicsPath path) {#GraphicsPathIterator-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public GraphicsPathIterator(GraphicsPath path)
```


Initialise une nouvelle instance de la classe [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | L'objet [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) pour lequel cette classe d'assistance doit être initialisée. |

### getCount() {#getCount--}
```
public int getCount()
```


Obtient le nombre de points dans le chemin.

**Returns:**
int - le nombre de points dans le chemin.
### getSubpathCount() {#getSubpathCount--}
```
public int getSubpathCount()
```


Obtient le nombre de sous‑chemins dans le chemin.

**Returns:**
int - le nombre de sous‑chemins dans le chemin.
### dispose() {#dispose--}
```
public void dispose()
```


Effectue les tâches définies par l'application associées à la libération, la remise ou la réinitialisation des ressources non gérées.

### copyData(PointF[][] points, byte[][] types, int startIndex, int endIndex) {#copyData-com.aspose.drawing.PointF-----byte-----int-int-}
```
public int copyData(PointF[][] points, byte[][] types, int startIndex, int endIndex)
```


Copie les tableaux de la propriété GraphicsPath.PathPoints et de la propriété GraphicsPath.PathTypes du [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) associé dans les deux tableaux spécifiés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.drawing/pointf) | À la sortie, contient un tableau de structures System.Drawing.PointF qui représente les points du chemin. |
| types | byte[][] | À la sortie, contient un tableau d'octets qui représente les types de points du chemin. |
| startIndex | int | Spécifie l'index de départ des tableaux. |
| endIndex | int | Spécifie l'index de fin des tableaux. |

**Returns:**
int - Le nombre de points copiés.
### enumerate(PointF[][] points, byte[][] types) {#enumerate-com.aspose.drawing.PointF-----byte-----}
```
public int enumerate(PointF[][] points, byte[][] types)
```


Copie les tableaux de la propriété GraphicsPath.PathPoints et de la propriété GraphicsPath.PathTypes du [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) associé dans les deux tableaux spécifiés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.drawing/pointf) | À la sortie, contient un tableau de structures System.Drawing.PointF qui représente les points du chemin. |
| types | byte[][] | À la sortie, contient un tableau d'octets qui représente les types de points du chemin. |

**Returns:**
int - Le nombre de points copiés.
### hasCurve() {#hasCurve--}
```
public boolean hasCurve()
```


Indique si le chemin associé à ce [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) contient une courbe.

**Returns:**
boolean - Cette méthode renvoie true si le sous‑chemin actuel contient une courbe ; sinon, false.
### nextMarker(int[] startIndex, int[] endIndex) {#nextMarker-int---int---}
```
public int nextMarker(int[] startIndex, int[] endIndex)
```


Incrémente le [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) vers le marqueur suivant dans le chemin et renvoie les index de début et de fin via les paramètres [out].

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| startIndex | int[] | [out] La référence entière fournie à ce paramètre reçoit l'index du point qui démarre un sous‑chemin. |
| endIndex | int[] | [out] La référence entière fournie à ce paramètre reçoit l'index du point qui termine le sous‑chemin auquel pointe startIndex. |

**Returns:**
int - Le nombre de points entre ce marqueur et le suivant.
### nextMarker(GraphicsPath path) {#nextMarker-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public int nextMarker(GraphicsPath path)
```


Cet objet [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) possède un objet [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) qui lui est associé. Cette méthode incrémente le [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) associé vers le marqueur suivant dans son tracé et copie tous les points compris entre le marqueur actuel et le marqueur suivant (ou la fin du tracé) dans un second objet [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) passé en paramètre.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | L'objet [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) vers lequel les points seront copiés. |

**Returns:**
int - Le nombre de points entre ce marqueur et le suivant.
### nextPathType(byte[] pathType, int[] startIndex, int[] endIndex) {#nextPathType-byte---int---int---}
```
public int nextPathType(byte[] pathType, int[] startIndex, int[] endIndex)
```


Obtient l'index de départ et l'index de fin du prochain groupe de points de données qui ont tous le même type.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pathType | byte[] | [out] Reçoit le type de point partagé par tous les points du groupe. Les types possibles peuvent être récupérés dans l'énumération [PathPointType](../../com.aspose.drawing.drawing2d/pathpointtype). |
| startIndex | int[] | [out] Reçoit l'index de départ du groupe de points. |
| endIndex | int[] | [out] Reçoit l'index de fin du groupe de points. |

**Returns:**
int - Cette méthode renvoie le nombre de points de données dans le groupe. S'il n'y a plus de groupes dans le tracé, cette méthode renvoie 0.
### nextSubpath(int[] startIndex, int[] endIndex, boolean[] isClosed) {#nextSubpath-int---int---boolean---}
```
public int nextSubpath(int[] startIndex, int[] endIndex, boolean[] isClosed)
```


Déplace le [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) vers le sous‑chemin suivant dans le tracé. L'index de début et l'index de fin du sous‑chemin suivant sont contenus dans les paramètres [out].

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| startIndex | int[] | [out] Reçoit l'index de départ du sous‑chemin suivant. |
| endIndex | int[] | [out] Reçoit l'index de fin du sous‑chemin suivant. |
| isClosed | boolean[] | [out] Indique si le sous‑chemin est fermé. |

**Returns:**
int - Le nombre de points de données dans la figure (sous‑chemin) récupérée. S'il n'y a plus de figures à récupérer, zéro est renvoyé.
### nextSubpath(GraphicsPath path, boolean[] isClosed) {#nextSubpath-com.aspose.drawing.drawing2d.GraphicsPath-boolean---}
```
public int nextSubpath(GraphicsPath path, boolean[] isClosed)
```


Obtient la figure suivante (sous‑chemin) à partir du chemin associé de ce [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | Un [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) dont les points de données doivent être définis pour correspondre aux points de données de la figure (sous‑chemin) récupérée pour cet itérateur. |
| isClosed | boolean[] | [out] Indique si le sous‑chemin actuel est fermé. C'est true si la figure est fermée, sinon c'est false. |

**Returns:**
int - Le nombre de points de données dans la figure (sous‑chemin) récupérée. S'il n'y a plus de figures à récupérer, zéro est renvoyé.
### rewind() {#rewind--}
```
public void rewind()
```


Rembobine ce [GraphicsPathIterator](../../com.aspose.drawing.drawing2d/graphicspathiterator) au début de son chemin associé.

