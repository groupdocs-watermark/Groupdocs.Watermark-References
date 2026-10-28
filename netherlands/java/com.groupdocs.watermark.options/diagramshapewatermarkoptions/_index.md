---
title: "DiagramShapeWatermarkOptions"
second_title: "GroupDocs.Watermark for Java API-referentie"
description: "Stelt opties voor het toevoegen van een watermerk voor wanneer een vormwatermerk wordt toegevoegd aan een Visiodocument voor."
type: docs
weight: 14
url: /nl/java/com.groupdocs.watermark.options/diagramshapewatermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.DiagramWatermarkOptions](../../com.groupdocs.watermark.options/diagramwatermarkoptions)
```
public final class DiagramShapeWatermarkOptions extends DiagramWatermarkOptions
```

Stelt opties voor het toevoegen van een watermerk voor wanneer een vormwatermerk wordt toegevoegd aan een Visiodocument voor.

**Learn more:**

* [Add watermarks to diagram documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+diagram+documents)

Het volgende voorbeeld toont hoe u een beschermde watermerk aan alle pagina's van het Visio-document kunt toevoegen.
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


## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [DiagramShapeWatermarkOptions()](#DiagramShapeWatermarkOptions--) | Initialiseert een nieuw exemplaar van de `[DiagramShapeWatermarkOptions](../../com.groupdocs.watermark.options/diagramshapewatermarkoptions)` klasse. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getPlacementType()](#getPlacementType--) | Haalt een waarde op die aangeeft aan welke pagina's een watermerk moet worden toegevoegd. |
|
|  | [setPlacementType(int value)](#setPlacementType-int-) | Haalt op of stelt een waarde in die aangeeft op welke pagina's een watermerk moet worden toegevoegd. |
|
### DiagramShapeWatermarkOptions() {#DiagramShapeWatermarkOptions--}
```
public DiagramShapeWatermarkOptions()
```


Initialiseert een nieuw exemplaar van de `[DiagramShapeWatermarkOptions](../../com.groupdocs.watermark.options/diagramshapewatermarkoptions)` klasse.


### getPlacementType() {#getPlacementType--}
```
public final int getPlacementType()
```


Haalt een waarde op die aangeeft aan welke pagina's een watermerk moet worden toegevoegd.


**Returns:**
int - De `[DiagramWatermarkPlacementType](../../com.groupdocs.watermark.contents/diagramwatermarkplacementtype)`, die aangeeft op welke pagina's een watermerk moet worden toegevoegd.

### setPlacementType(int value) {#setPlacementType-int-}
```
public final void setPlacementType(int value)
```


Haalt op of stelt een waarde in die aangeeft op welke pagina's een watermerk moet worden toegevoegd.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | value | int | De `[DiagramWatermarkPlacementType](../../com.groupdocs.watermark.contents/diagramwatermarkplacementtype)`, die aangeeft op welke pagina's een watermerk moet worden toegevoegd. |
|

