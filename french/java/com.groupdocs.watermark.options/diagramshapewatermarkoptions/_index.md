---
title: "DiagramShapeWatermarkOptions"
second_title: "GroupDocs.Watermark pour Java Référence API"
description: "Représente les options d’ajout de filigrane lors de l’ajout d’un filigrane de forme à un document Visio."
type: docs
weight: 14
url: /fr/java/com.groupdocs.watermark.options/diagramshapewatermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.DiagramWatermarkOptions](../../com.groupdocs.watermark.options/diagramwatermarkoptions)
```
public final class DiagramShapeWatermarkOptions extends DiagramWatermarkOptions
```

Représente les options d’ajout de filigrane lors de l’ajout d’un filigrane de forme à un document Visio.

**Learn more:**

* [Add watermarks to diagram documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+diagram+documents)

L'exemple suivant montre comment ajouter un filigrane protégé à toutes les pages du document Visio.
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


## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [DiagramShapeWatermarkOptions()](#DiagramShapeWatermarkOptions--) | Initialise une nouvelle instance de la classe `[DiagramShapeWatermarkOptions](../../com.groupdocs.watermark.options/diagramshapewatermarkoptions)`. |
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getPlacementType()](#getPlacementType--) | Obtient une valeur indiquant sur quelles pages le filigrane doit être ajouté. |
|
|  | [setPlacementType(int value)](#setPlacementType-int-) | Obtient ou définit une valeur indiquant sur quelles pages le filigrane doit être ajouté. |
|
### DiagramShapeWatermarkOptions() {#DiagramShapeWatermarkOptions--}
```
public DiagramShapeWatermarkOptions()
```


Initialise une nouvelle instance de la classe `[DiagramShapeWatermarkOptions](../../com.groupdocs.watermark.options/diagramshapewatermarkoptions)`.


### getPlacementType() {#getPlacementType--}
```
public final int getPlacementType()
```


Obtient une valeur indiquant sur quelles pages le filigrane doit être ajouté.


**Returns:**
int - Le `[DiagramWatermarkPlacementType](../../com.groupdocs.watermark.contents/diagramwatermarkplacementtype)`, qui indique sur quelles pages le filigrane doit être ajouté.

### setPlacementType(int value) {#setPlacementType-int-}
```
public final void setPlacementType(int value)
```


Obtient ou définit une valeur indiquant sur quelles pages le filigrane doit être ajouté.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | value | int | Le `[DiagramWatermarkPlacementType](../../com.groupdocs.watermark.contents/diagramwatermarkplacementtype)`, qui indique sur quelles pages le filigrane doit être ajouté. |
|

