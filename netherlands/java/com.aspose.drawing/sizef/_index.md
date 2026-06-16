---
title: SizeF
second_title: Aspose.Drawing voor Java API-referentie
description: Slaat een geordend paar zwevende-kommagetallen op, meestal de breedte en hoogte van een rechthoek.
type: docs
weight: 43
url: /nl/java/com.aspose.drawing/sizef/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable, java.lang.Cloneable
```
public class SizeF extends Struct<SizeF> implements System.IEquatable<SizeF>, Cloneable
```

Slaat een geordend paar van zwevende-komma getallen op, meestal de breedte en hoogte van een rechthoek.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [SizeF()](#SizeF--) |  |
| [SizeF(float width, float height)](#SizeF-float-float-) | Initialiseert een nieuw exemplaar van de SizeF-structuur met de opgegeven afmetingen. |
| [SizeF(PointF pt)](#SizeF-com.aspose.drawing.PointF-) | Initialiseert een nieuw exemplaar van de [SizeF](../../com.aspose.drawing/sizef) struct. |
| [SizeF(SizeF size)](#SizeF-com.aspose.drawing.SizeF-) | Initialiseert een nieuw exemplaar van de [SizeF](../../com.aspose.drawing/sizef) struct. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [op_Equality(SizeF sz1, SizeF sz2)](#op-Equality-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-) | Test of twee [SizeF](../../com.aspose.drawing/sizef) structuren gelijk zijn. |
| [op_Inequality(SizeF sz1, SizeF sz2)](#op-Inequality-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-) | Test of twee [SizeF](../../com.aspose.drawing/sizef) structuren verschillend zijn. |
| [add(SizeF sz1, SizeF sz2)](#add-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-) | Voegt de breedte en hoogte van één [SizeF](../../com.aspose.drawing/sizef) structuur toe aan de breedte en hoogte van een andere [SizeF](../../com.aspose.drawing/sizef) structuur. |
| [subtract(SizeF sz1, SizeF sz2)](#subtract-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-) | Trekt de breedte en hoogte van één [SizeF](../../com.aspose.drawing/sizef) structuur af van de breedte en hoogte van een andere [SizeF](../../com.aspose.drawing/sizef) structuur. |
| [op_Addition(SizeF sz1, SizeF sz2)](#op-Addition-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-) | Voegt de breedte en hoogte van één [SizeF](../../com.aspose.drawing/sizef) structuur toe aan de breedte en hoogte van een andere [SizeF](../../com.aspose.drawing/sizef) structuur. |
| [op_Subtraction(SizeF sz1, SizeF sz2)](#op-Subtraction-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-) | Trekt de breedte en hoogte van één [SizeF](../../com.aspose.drawing/sizef) structuur af van de breedte en hoogte van een andere [SizeF](../../com.aspose.drawing/sizef) structuur. |
| [op_Multiply(float left, SizeF right)](#op-Multiply-float-com.aspose.drawing.SizeF-) | Vermenigvuldigt [SizeF](../../com.aspose.drawing/sizef) met een `float` en produceert [SizeF](../../com.aspose.drawing/sizef). |
| [op_Multiply(SizeF left, float right)](#op-Multiply-com.aspose.drawing.SizeF-float-) | Vermenigvuldigt [SizeF](../../com.aspose.drawing/sizef) met een `float` en produceert [SizeF](../../com.aspose.drawing/sizef). |
| [op_Division(SizeF left, float right)](#op-Division-com.aspose.drawing.SizeF-float-) | Deelt [SizeF](../../com.aspose.drawing/sizef) door een `float` en produceert [SizeF](../../com.aspose.drawing/sizef). |
| [to_PointF(SizeF size)](#to-PointF-com.aspose.drawing.SizeF-) |  |
| [isEquals(SizeF obj1, SizeF obj2)](#isEquals-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-) |  |
| [getEmpty()](#getEmpty--) |  |
| [isEmpty()](#isEmpty--) | Haalt een waarde op die aangeeft of deze [SizeF](../../com.aspose.drawing/sizef) structuur een breedte en hoogte van nul heeft. |
| [getWidth()](#getWidth--) | Haalt het horizontale component van deze SizeF-structuur op. |
| [setWidth(float value)](#setWidth-float-) | Stelt het horizontale component van deze SizeF-structuur in. |
| [getHeight()](#getHeight--) | Haalt het verticale component van deze SizeF-structuur op. |
| [setHeight(float value)](#setHeight-float-) | Stelt het verticale component van deze SizeF-structuur in. |
| [hashCode()](#hashCode--) | Retourneert een hashcode voor deze [SizeF](../../com.aspose.drawing/sizef) structuur. |
| [toString()](#toString--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Test of het opgegeven object een [SizeF](../../com.aspose.drawing/sizef) structuur is met dezelfde afmetingen als deze [SizeF](../../com.aspose.drawing/sizef) structuur. |
| [toSize()](#toSize--) | Converteert een [SizeF](../../com.aspose.drawing/sizef) structuur naar een [Size](../../com.aspose.drawing/size) structuur. |
| [toPointF()](#toPointF--) | Converteert een [SizeF](../../com.aspose.drawing/sizef) structuur naar een [PointF](../../com.aspose.drawing/pointf) structuur. |
| [equals(SizeF other)](#equals-com.aspose.drawing.SizeF-) | Test of een andere [SizeF](../../com.aspose.drawing/sizef) structuur dezelfde grootte heeft als deze [SizeF](../../com.aspose.drawing/sizef) structuur. |
| [CloneTo(SizeF that)](#CloneTo-com.aspose.drawing.SizeF-) |  |
| [Clone()](#Clone--) |  |
| [clone()](#clone--) |  |
### SizeF() {#SizeF--}
```
public SizeF()
```


### SizeF(float width, float height) {#SizeF-float-float-}
```
public SizeF(float width, float height)
```


Initialiseert een nieuw exemplaar van de SizeF-structuur met de opgegeven afmetingen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| breedte | float | Het breedtecomponent van de nieuwe SizeF-structuur. |
| hoogte | float | Het hoogtecomponent van de nieuwe SizeF-structuur. |

### SizeF(PointF pt) {#SizeF-com.aspose.drawing.PointF-}
```
public SizeF(PointF pt)
```


Initialiseert een nieuw exemplaar van de [SizeF](../../com.aspose.drawing/sizef) struct.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pt | [PointF](../../com.aspose.drawing/pointf) | De [PointF](../../com.aspose.drawing/pointf) structuur waarvan deze [SizeF](../../com.aspose.drawing/sizef) structuur moet worden geïnitialiseerd. |

### SizeF(SizeF size) {#SizeF-com.aspose.drawing.SizeF-}
```
public SizeF(SizeF size)
```


Initialiseert een nieuw exemplaar van de [SizeF](../../com.aspose.drawing/sizef) struct.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.drawing/sizef) | De [SizeF](../../com.aspose.drawing/sizef) structuur waarvan de nieuwe [SizeF](../../com.aspose.drawing/sizef) structuur moet worden gemaakt. |

### op_Equality(SizeF sz1, SizeF sz2) {#op-Equality-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-}
```
public static boolean op_Equality(SizeF sz1, SizeF sz2)
```


Test of twee [SizeF](../../com.aspose.drawing/sizef) structuren gelijk zijn.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sz1 | [SizeF](../../com.aspose.drawing/sizef) | De [SizeF](../../com.aspose.drawing/sizef) structuur aan de linkerkant van de gelijkheidsoperator. |
| sz2 | [SizeF](../../com.aspose.drawing/sizef) | De [SizeF](../../com.aspose.drawing/sizef) structuur aan de rechterkant van de gelijkheidsoperator. |

**Returns:**
boolean - Deze operator retourneert true als `sz1` en `sz2` gelijke breedte en hoogte hebben; anders false.
### op_Inequality(SizeF sz1, SizeF sz2) {#op-Inequality-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-}
```
public static boolean op_Inequality(SizeF sz1, SizeF sz2)
```


Test of twee [SizeF](../../com.aspose.drawing/sizef) structuren verschillend zijn.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sz1 | [SizeF](../../com.aspose.drawing/sizef) | De [SizeF](../../com.aspose.drawing/sizef) structuur aan de linkerkant van de ongelijkheidsoperator. |
| sz2 | [SizeF](../../com.aspose.drawing/sizef) | De [SizeF](../../com.aspose.drawing/sizef) structuur aan de rechterkant van de ongelijkheidsoperator. |

**Returns:**
boolean - Deze operator retourneert true als `sz1` en `sz2` verschillen in breedte of hoogte; false als `sz1` en `sz2` gelijk zijn.
### add(SizeF sz1, SizeF sz2) {#add-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-}
```
public static SizeF add(SizeF sz1, SizeF sz2)
```


Voegt de breedte en hoogte van één [SizeF](../../com.aspose.drawing/sizef) structuur toe aan de breedte en hoogte van een andere [SizeF](../../com.aspose.drawing/sizef) structuur.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sz1 | [SizeF](../../com.aspose.drawing/sizef) | De eerste [SizeF](../../com.aspose.drawing/sizef) structuur om toe te voegen. |
| sz2 | [SizeF](../../com.aspose.drawing/sizef) | De tweede [SizeF](../../com.aspose.drawing/sizef) structuur om toe te voegen. |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - A [SizeF](../../com.aspose.drawing/sizef) structure that is the result of the addition operation.
### subtract(SizeF sz1, SizeF sz2) {#subtract-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-}
```
public static SizeF subtract(SizeF sz1, SizeF sz2)
```


Trekt de breedte en hoogte van één [SizeF](../../com.aspose.drawing/sizef) structuur af van de breedte en hoogte van een andere [SizeF](../../com.aspose.drawing/sizef) structuur.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sz1 | [SizeF](../../com.aspose.drawing/sizef) | De [SizeF](../../com.aspose.drawing/sizef) structuur aan de linkerkant van de aftreksomoperator. |
| sz2 | [SizeF](../../com.aspose.drawing/sizef) | De [SizeF](../../com.aspose.drawing/sizef) structuur aan de rechterkant van de aftreksomoperator. |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - A [SizeF](../../com.aspose.drawing/sizef) structure that is a result of the subtraction operation.
### op_Addition(SizeF sz1, SizeF sz2) {#op-Addition-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-}
```
public static SizeF op_Addition(SizeF sz1, SizeF sz2)
```


Voegt de breedte en hoogte van één [SizeF](../../com.aspose.drawing/sizef) structuur toe aan de breedte en hoogte van een andere [SizeF](../../com.aspose.drawing/sizef) structuur.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sz1 | [SizeF](../../com.aspose.drawing/sizef) | De eerste [SizeF](../../com.aspose.drawing/sizef) structuur om toe te voegen. |
| sz2 | [SizeF](../../com.aspose.drawing/sizef) | De tweede [SizeF](../../com.aspose.drawing/sizef) structuur om toe te voegen. |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - A [Size](../../com.aspose.drawing/size) structure that is the result of the addition operation.
### op_Subtraction(SizeF sz1, SizeF sz2) {#op-Subtraction-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-}
```
public static SizeF op_Subtraction(SizeF sz1, SizeF sz2)
```


Trekt de breedte en hoogte van één [SizeF](../../com.aspose.drawing/sizef) structuur af van de breedte en hoogte van een andere [SizeF](../../com.aspose.drawing/sizef) structuur.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sz1 | [SizeF](../../com.aspose.drawing/sizef) | De [SizeF](../../com.aspose.drawing/sizef) structuur aan de linkerkant van de aftreksomoperator. |
| sz2 | [SizeF](../../com.aspose.drawing/sizef) | De [SizeF](../../com.aspose.drawing/sizef) structuur aan de rechterkant van de aftreksomoperator. |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - A [SizeF](../../com.aspose.drawing/sizef) that is the result of the subtraction operation.
### op_Multiply(float left, SizeF right) {#op-Multiply-float-com.aspose.drawing.SizeF-}
```
public static SizeF op_Multiply(float left, SizeF right)
```


Vermenigvuldigt [SizeF](../../com.aspose.drawing/sizef) met een `float` en produceert [SizeF](../../com.aspose.drawing/sizef).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| links | float | Vermenigvuldiger van type `float`. |
| right | [SizeF](../../com.aspose.drawing/sizef) | Vermenigvuldiger van type [SizeF](../../com.aspose.drawing/sizef). |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - Product of type [SizeF](../../com.aspose.drawing/sizef).
### op_Multiply(SizeF left, float right) {#op-Multiply-com.aspose.drawing.SizeF-float-}
```
public static SizeF op_Multiply(SizeF left, float right)
```


Vermenigvuldigt [SizeF](../../com.aspose.drawing/sizef) met een `float` en produceert [SizeF](../../com.aspose.drawing/sizef).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| left | [SizeF](../../com.aspose.drawing/sizef) | Vermenigvuldiger van type [SizeF](../../com.aspose.drawing/sizef). |
| rechts | float | Vermenigvuldiger van type `float`. |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - Product of type [SizeF](../../com.aspose.drawing/sizef).
### op_Division(SizeF left, float right) {#op-Division-com.aspose.drawing.SizeF-float-}
```
public static SizeF op_Division(SizeF left, float right)
```


Deelt [SizeF](../../com.aspose.drawing/sizef) door een `float` en produceert [SizeF](../../com.aspose.drawing/sizef).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| left | [SizeF](../../com.aspose.drawing/sizef) | Dividend van type [SizeF](../../com.aspose.drawing/sizef). |
| rechts | float | Deler van type `int`. |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - Result of type [SizeF](../../com.aspose.drawing/sizef).
### to_PointF(SizeF size) {#to-PointF-com.aspose.drawing.SizeF-}
```
public static PointF to_PointF(SizeF size)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.drawing/sizef) |  |

**Returns:**
[PointF](../../com.aspose.drawing/pointf)
### isEquals(SizeF obj1, SizeF obj2) {#isEquals-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-}
```
public static boolean isEquals(SizeF obj1, SizeF obj2)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj1 | [SizeF](../../com.aspose.drawing/sizef) |  |
| obj2 | [SizeF](../../com.aspose.drawing/sizef) |  |

**Returns:**
boolean
### getEmpty() {#getEmpty--}
```
public static SizeF getEmpty()
```




**Returns:**
[SizeF](../../com.aspose.drawing/sizef)
### isEmpty() {#isEmpty--}
```
public final boolean isEmpty()
```


Haalt een waarde op die aangeeft of deze [SizeF](../../com.aspose.drawing/sizef) structuur een breedte en hoogte van nul heeft.

**Returns:**
boolean - een waarde die aangeeft of deze [SizeF](../../com.aspose.drawing/sizef) structuur nul breedte en hoogte heeft.
### getWidth() {#getWidth--}
```
public final float getWidth()
```


Haalt het horizontale component van deze SizeF-structuur op.

**Returns:**
float - het horizontale component van deze SizeF-structuur.
### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```


Stelt het horizontale component van deze SizeF-structuur in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float | het horizontale component van deze SizeF-structuur. |

### getHeight() {#getHeight--}
```
public final float getHeight()
```


Haalt het verticale component van deze SizeF-structuur op.

**Returns:**
float - het verticale component van deze SizeF-structuur.
### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```


Stelt het verticale component van deze SizeF-structuur in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float | het verticale component van deze SizeF-structuur. |

### hashCode() {#hashCode--}
```
public int hashCode()
```


Retourneert een hashcode voor deze [SizeF](../../com.aspose.drawing/sizef) structuur.

**Returns:**
int - Een geheel getal dat een hashwaarde voor deze [SizeF](../../com.aspose.drawing/sizef) structuur specificeert.
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Test of het opgegeven object een [SizeF](../../com.aspose.drawing/sizef) structuur is met dezelfde afmetingen als deze [SizeF](../../com.aspose.drawing/sizef) structuur.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | java.lang.Object | Het object om te testen. |

**Returns:**
boolean - Deze methode retourneert `true` als obj een [SizeF](../../com.aspose.drawing/sizef) is en dezelfde breedte en hoogte heeft als deze SizeF; anders `false`.
### toSize() {#toSize--}
```
public final Size toSize()
```


Converteert een [SizeF](../../com.aspose.drawing/sizef) structuur naar een [Size](../../com.aspose.drawing/size) structuur.

**Returns:**
[Size](../../com.aspose.drawing/size) - Returns a [Size](../../com.aspose.drawing/size) structure.
### toPointF() {#toPointF--}
```
public final PointF toPointF()
```


Converteert een [SizeF](../../com.aspose.drawing/sizef) structuur naar een [PointF](../../com.aspose.drawing/pointf) structuur.

**Returns:**
[PointF](../../com.aspose.drawing/pointf) - Returns a [PointF](../../com.aspose.drawing/pointf) structure.
### equals(SizeF other) {#equals-com.aspose.drawing.SizeF-}
```
public final boolean equals(SizeF other)
```


Test of een andere [SizeF](../../com.aspose.drawing/sizef) structuur dezelfde grootte heeft als deze [SizeF](../../com.aspose.drawing/sizef) structuur.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| other | [SizeF](../../com.aspose.drawing/sizef) | Andere grootte om te testen |

**Returns:**
boolean - Deze methode retourneert `true` als een andere [SizeF](../../com.aspose.drawing/sizef) structuur en zijn Width- en Height-eigenschappen gelijk zijn aan de overeenkomstige eigenschappen van deze [SizeF](../../com.aspose.drawing/sizef) structuur; anders `false`.
### CloneTo(SizeF that) {#CloneTo-com.aspose.drawing.SizeF-}
```
public void CloneTo(SizeF that)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| that | [SizeF](../../com.aspose.drawing/sizef) |  |

### Clone() {#Clone--}
```
public SizeF Clone()
```




**Returns:**
[SizeF](../../com.aspose.drawing/sizef)
### clone() {#clone--}
```
public Object clone()
```




**Returns:**
java.lang.Object
