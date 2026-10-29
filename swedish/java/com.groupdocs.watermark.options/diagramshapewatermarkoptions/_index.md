---
title: "DiagramShapeWatermarkOptions"
second_title: "GroupDocs.Watermark för Java API-referens"
description: "Representerar alternativ för att lägga till vattenstämpel när en formvattenstämpel läggs till i ett Visio-dokument."
type: docs
weight: 14
url: /sv/java/com.groupdocs.watermark.options/diagramshapewatermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.DiagramWatermarkOptions](../../com.groupdocs.watermark.options/diagramwatermarkoptions)
```
public final class DiagramShapeWatermarkOptions extends DiagramWatermarkOptions
```

Representerar alternativ för att lägga till vattenstämpel när en formvattenstämpel läggs till i ett Visio-dokument.

**Learn more:**

* [Add watermarks to diagram documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+diagram+documents)

Följande exempel visar hur man lägger till ett skyddat vattenstämpel på alla sidor i Visio-dokumentet.
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


## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [DiagramShapeWatermarkOptions()](#DiagramShapeWatermarkOptions--) | Initierar en ny instans av klassen `[DiagramShapeWatermarkOptions](../../com.groupdocs.watermark.options/diagramshapewatermarkoptions)`. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getPlacementType()](#getPlacementType--) | Hämtar ett värde som anger på vilka sidor ett vattenstämpel ska läggas till. |
|
|  | [setPlacementType(int value)](#setPlacementType-int-) | Hämtar eller anger ett värde som specificerar på vilka sidor ett vattenstämpel ska läggas till. |
|
### DiagramShapeWatermarkOptions() {#DiagramShapeWatermarkOptions--}
```
public DiagramShapeWatermarkOptions()
```


Initierar en ny instans av klassen `[DiagramShapeWatermarkOptions](../../com.groupdocs.watermark.options/diagramshapewatermarkoptions)`.


### getPlacementType() {#getPlacementType--}
```
public final int getPlacementType()
```


Hämtar ett värde som anger på vilka sidor ett vattenstämpel ska läggas till.


**Returns:**
int - Den `[DiagramWatermarkPlacementType](../../com.groupdocs.watermark.contents/diagramwatermarkplacementtype)`, som specificerar på vilka sidor ett vattenstämpel ska läggas till.

### setPlacementType(int value) {#setPlacementType-int-}
```
public final void setPlacementType(int value)
```


Hämtar eller anger ett värde som specificerar på vilka sidor ett vattenstämpel ska läggas till.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | int | `[DiagramWatermarkPlacementType](../../com.groupdocs.watermark.contents/diagramwatermarkplacementtype)`, som specificerar på vilka sidor ett vattenstämpel ska läggas till. |
|

