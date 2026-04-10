---
title: CustomLineCap
second_title: Riferimento API di Aspose.Drawing per Java
description: Incapsula un cappuccio di linea personalizzato definito dall'utente.
type: docs
weight: 17
url: /it/java/com.aspose.drawing.drawing2d/customlinecap/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public class CustomLineCap implements System.IDisposable
```

Incapsula un cappuccio di linea personalizzato definito dall'utente.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath)](#CustomLineCap-com.aspose.drawing.drawing2d.GraphicsPath-com.aspose.drawing.drawing2d.GraphicsPath-) | Inizializza una nuova istanza della classe [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) con il contorno e il riempimento specificati. |
| [CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap)](#CustomLineCap-com.aspose.drawing.drawing2d.GraphicsPath-com.aspose.drawing.drawing2d.GraphicsPath-int-) | Inizializza una nuova istanza della classe [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) a partire dall'enumerazione [LineCap](../../com.aspose.drawing.drawing2d/linecap) esistente specificata, con il contorno e il riempimento specificati. |
| [CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap, float baseInset)](#CustomLineCap-com.aspose.drawing.drawing2d.GraphicsPath-com.aspose.drawing.drawing2d.GraphicsPath-int-float-) | Inizializza una nuova istanza della classe [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) a partire dall'enumerazione [LineCap](../../com.aspose.drawing.drawing2d/linecap) esistente specificata, con il contorno, il riempimento e l'inserimento specificati. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getStrokeJoin()](#getStrokeJoin--) | Ottiene o imposta l'enumerazione [LineJoin](../../com.aspose.drawing.drawing2d/linejoin) che determina come le linee che compongono questo oggetto [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) vengono unite. |
| [setStrokeJoin(int value)](#setStrokeJoin-int-) | Ottiene o imposta l'enumerazione [LineJoin](../../com.aspose.drawing.drawing2d/linejoin) che determina come le linee che compongono questo oggetto [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) vengono unite. |
| [getBaseCap()](#getBaseCap--) | Ottiene o imposta l'enumerazione [LineCap](../../com.aspose.drawing.drawing2d/linecap) su cui si basa questo [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap). |
| [setBaseCap(int value)](#setBaseCap-int-) | Ottiene o imposta l'enumerazione [LineCap](../../com.aspose.drawing.drawing2d/linecap) su cui si basa questo [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap). |
| [getBaseInset()](#getBaseInset--) | Ottiene o imposta la distanza tra il cappuccio e la linea. |
| [setBaseInset(float value)](#setBaseInset-float-) | Ottiene o imposta la distanza tra il cappuccio e la linea. |
| [getWidthScale()](#getWidthScale--) | Ottiene o imposta la quantità con cui scalare questo oggetto di classe [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) rispetto alla larghezza dell'oggetto [Pen](../../com.aspose.drawing/pen). |
| [setWidthScale(float value)](#setWidthScale-float-) | Ottiene o imposta la quantità con cui scalare questo oggetto di classe [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) rispetto alla larghezza dell'oggetto [Pen](../../com.aspose.drawing/pen). |
| [dispose()](#dispose--) | Rilascia tutte le risorse utilizzate da questo oggetto [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap). |
| [deepClone()](#deepClone--) | Crea una copia esatta di questo [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap). |
| [setStrokeCaps(int startCap, int endCap)](#setStrokeCaps-int-int-) | Imposta le punte utilizzate per avviare e terminare le linee che compongono questa punta personalizzata. |
| [getStrokeCaps(int[] startCap, int[] endCap)](#getStrokeCaps-int---int---) | Restituisce le punte utilizzate per avviare e terminare le linee che compongono questa punta personalizzata. |
| [getFillPath()](#getFillPath--) |  |
| [getStrokePath()](#getStrokePath--) | Restituisce l'oggetto che definisce il contorno della punta personalizzata. |
### CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath) {#CustomLineCap-com.aspose.drawing.drawing2d.GraphicsPath-com.aspose.drawing.drawing2d.GraphicsPath-}
```
public CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath)
```


Inizializza una nuova istanza della classe [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) con il contorno e il riempimento specificati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fillPath | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | Un oggetto [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) che definisce il riempimento per la punta personalizzata. |
| strokePath | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | Un oggetto [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) che definisce il contorno della punta personalizzata. |

### CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap) {#CustomLineCap-com.aspose.drawing.drawing2d.GraphicsPath-com.aspose.drawing.drawing2d.GraphicsPath-int-}
```
public CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap)
```


Inizializza una nuova istanza della classe [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) a partire dall'enumerazione [LineCap](../../com.aspose.drawing.drawing2d/linecap) esistente specificata, con il contorno e il riempimento specificati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fillPath | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | Un oggetto [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) che definisce il riempimento per la punta personalizzata. |
| strokePath | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | Un oggetto [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) che definisce il contorno della punta personalizzata. |
| baseCap | int | La punta di linea da cui creare la punta personalizzata. |

### CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap, float baseInset) {#CustomLineCap-com.aspose.drawing.drawing2d.GraphicsPath-com.aspose.drawing.drawing2d.GraphicsPath-int-float-}
```
public CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap, float baseInset)
```


Inizializza una nuova istanza della classe [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) a partire dall'enumerazione [LineCap](../../com.aspose.drawing.drawing2d/linecap) esistente specificata, con il contorno, il riempimento e l'inserimento specificati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fillPath | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | Un oggetto [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) che definisce il riempimento per la punta personalizzata. |
| strokePath | [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) | Un oggetto [GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) che definisce il contorno della punta personalizzata. |
| baseCap | int | La punta di linea da cui creare la punta personalizzata. |
| baseInset | float | La distanza tra la punta e la linea. |

### getStrokeJoin() {#getStrokeJoin--}
```
public final int getStrokeJoin()
```


Ottiene o imposta l'enumerazione [LineJoin](../../com.aspose.drawing.drawing2d/linejoin) che determina come le linee che compongono questo oggetto [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) vengono unite.

**Returns:**
int
### setStrokeJoin(int value) {#setStrokeJoin-int-}
```
public final void setStrokeJoin(int value)
```


Ottiene o imposta l'enumerazione [LineJoin](../../com.aspose.drawing.drawing2d/linejoin) che determina come le linee che compongono questo oggetto [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) vengono unite.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getBaseCap() {#getBaseCap--}
```
public final int getBaseCap()
```


Ottiene o imposta l'enumerazione [LineCap](../../com.aspose.drawing.drawing2d/linecap) su cui si basa questo [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap).

**Returns:**
int
### setBaseCap(int value) {#setBaseCap-int-}
```
public final void setBaseCap(int value)
```


Ottiene o imposta l'enumerazione [LineCap](../../com.aspose.drawing.drawing2d/linecap) su cui si basa questo [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getBaseInset() {#getBaseInset--}
```
public final float getBaseInset()
```


Ottiene o imposta la distanza tra il cappuccio e la linea.

**Returns:**
float
### setBaseInset(float value) {#setBaseInset-float-}
```
public final void setBaseInset(float value)
```


Ottiene o imposta la distanza tra il cappuccio e la linea.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float |  |

### getWidthScale() {#getWidthScale--}
```
public final float getWidthScale()
```


Ottiene o imposta la quantità con cui scalare questo oggetto di classe [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) rispetto alla larghezza dell'oggetto [Pen](../../com.aspose.drawing/pen).

**Returns:**
float
### setWidthScale(float value) {#setWidthScale-float-}
```
public final void setWidthScale(float value)
```


Ottiene o imposta la quantità con cui scalare questo oggetto di classe [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) rispetto alla larghezza dell'oggetto [Pen](../../com.aspose.drawing/pen).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float |  |

### dispose() {#dispose--}
```
public final void dispose()
```


Rilascia tutte le risorse utilizzate da questo oggetto [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap).

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Crea una copia esatta di questo [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap).

**Returns:**
java.lang.Object - Il [CustomLineCap](../../com.aspose.drawing.drawing2d/customlinecap) che questo metodo crea, convertito in un oggetto.
### setStrokeCaps(int startCap, int endCap) {#setStrokeCaps-int-int-}
```
public final void setStrokeCaps(int startCap, int endCap)
```


Imposta le punte utilizzate per avviare e terminare le linee che compongono questa punta personalizzata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| startCap | int | L'enumerazione [LineCap](../../com.aspose.drawing.drawing2d/linecap) utilizzata all'inizio di una linea all'interno di questa punta. |
| endCap | int | L'enumerazione [LineCap](../../com.aspose.drawing.drawing2d/linecap) utilizzata alla fine di una linea all'interno di questa punta. |

### getStrokeCaps(int[] startCap, int[] endCap) {#getStrokeCaps-int---int---}
```
public final void getStrokeCaps(int[] startCap, int[] endCap)
```


Restituisce le punte utilizzate per avviare e terminare le linee che compongono questa punta personalizzata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| startCap | int[] | L'enumerazione [LineCap](../../com.aspose.drawing.drawing2d/linecap) utilizzata all'inizio di una linea all'interno di questa punta. |
| endCap | int[] | L'enumerazione [LineCap](../../com.aspose.drawing.drawing2d/linecap) utilizzata alla fine di una linea all'interno di questa punta. |

### getFillPath() {#getFillPath--}
```
public GraphicsPath getFillPath()
```




**Returns:**
[GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath)
### getStrokePath() {#getStrokePath--}
```
public GraphicsPath getStrokePath()
```


Restituisce l'oggetto che definisce il contorno della punta personalizzata.

**Returns:**
[GraphicsPath](../../com.aspose.drawing.drawing2d/graphicspath) - The object that defines the outline of the custom cap.
