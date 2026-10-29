---
title: "DiagramShapeWatermarkOptions"
second_title: "Referencia de API de GroupDocs.Watermark para Java"
description: "Representa opciones de adición de marca de agua al agregar una marca de agua de forma a un documento Visio."
type: docs
weight: 14
url: /es/java/com.groupdocs.watermark.options/diagramshapewatermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.DiagramWatermarkOptions](../../com.groupdocs.watermark.options/diagramwatermarkoptions)
```
public final class DiagramShapeWatermarkOptions extends DiagramWatermarkOptions
```

Representa opciones de adición de marca de agua al agregar una marca de agua de forma a un documento Visio.

**Learn more:**

* [Add watermarks to diagram documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+diagram+documents)

El siguiente ejemplo muestra cómo agregar una marca de agua protegida a todas las páginas del documento Visio.
>
> ````
> ```
>
>    DiagramLoadOptions loadOptions = new DiagramLoadOptions();
>    Watermarker watermarker = new Watermarker("D:\\test.vsdx", loadOptions);
>
>    TextWatermark watermark = new TextWatermark("watermark test", new Font("Arial", 42));
>
>    DiagramShapeWatermarkOptions options = new DiagramShapeWatermarkOptions();
>    options.setLocked(true);
>    options.setPlacementType(DiagramWatermarkPlacementType.AllPages);
>
>    watermarker.add(watermark, options);
>    watermarker.save("D:\\watermarked_test.vsdx");
>    watermarker.close();
>  
> ```
> ````


## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [DiagramShapeWatermarkOptions()](#DiagramShapeWatermarkOptions--) | Inicializa una nueva instancia de la clase `[DiagramShapeWatermarkOptions](../../com.groupdocs.watermark.options/diagramshapewatermarkoptions)`. |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getPlacementType()](#getPlacementType--) | Obtiene un valor que especifica en qué páginas se debe agregar una marca de agua. |
|
|  | [setPlacementType(int value)](#setPlacementType-int-) | Obtiene o establece un valor que especifica en qué páginas se debe agregar una marca de agua. |
|
### DiagramShapeWatermarkOptions() {#DiagramShapeWatermarkOptions--}
```
public DiagramShapeWatermarkOptions()
```


Inicializa una nueva instancia de la clase `[DiagramShapeWatermarkOptions](../../com.groupdocs.watermark.options/diagramshapewatermarkoptions)`.


### getPlacementType() {#getPlacementType--}
```
public final int getPlacementType()
```


Obtiene un valor que especifica en qué páginas se debe agregar una marca de agua.


**Returns:**
int - El `[DiagramWatermarkPlacementType](../../com.groupdocs.watermark.contents/diagramwatermarkplacementtype)`, que especifica en qué páginas se debe agregar una marca de agua.

### setPlacementType(int value) {#setPlacementType-int-}
```
public final void setPlacementType(int value)
```


Obtiene o establece un valor que especifica en qué páginas se debe agregar una marca de agua.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | value | int | El `[DiagramWatermarkPlacementType](../../com.groupdocs.watermark.contents/diagramwatermarkplacementtype)`, que especifica en qué páginas se debe agregar una marca de agua. |
|

