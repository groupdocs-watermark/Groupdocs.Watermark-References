---
title: "DiagramPageWatermarkOptions"
second_title: "GroupDocs.Watermark för Java API-referens"
description: "Representerar alternativ för att lägga till vattenstämpel när en formvattenstämpel läggs till på en specifik sida i ett Visio-dokument."
type: docs
weight: 11
url: /sv/java/com.groupdocs.watermark.options/diagrampagewatermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.DiagramWatermarkOptions](../../com.groupdocs.watermark.options/diagramwatermarkoptions)
```
public final class DiagramPageWatermarkOptions extends DiagramWatermarkOptions
```

Representerar alternativ för att lägga till vattenstämpel när en formvattenstämpel läggs till på en specifik sida i ett Visio-dokument.

**Learn more:**

* [Add watermarks to diagram documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+diagram+documents)

Följande exempel visar hur man lägger till en skyddad vattenstämpel på den första sidan i ett Visio-dokument.
>
> ````
> ```
>
>    DiagramLoadOptions loadOptions = new DiagramLoadOptions();
>    Watermarker watermarker = new Watermarker("D:\\test.vsdx", loadOptions);
>
>    TextWatermark watermark = new TextWatermark("watermark test", new Font("Arial", 42));
>
>    DiagramPageWatermarkOptions options = new DiagramPageWatermarkOptions();
>    options.setLocked(true);
>    options.setPageIndex(0);
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
|  | [DiagramPageWatermarkOptions()](#DiagramPageWatermarkOptions--) | Initierar en ny instans av klassen `[DiagramPageWatermarkOptions](../../com.groupdocs.watermark.options/diagrampagewatermarkoptions)`. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getPageIndex()](#getPageIndex--) | Hämtar sidindexet som vattenstämpeln ska läggas till på. |
|
|  | [setPageIndex(int value)](#setPageIndex-int-) | Ställer in sidindexet som vattenstämpeln ska läggas till på. |
|
### DiagramPageWatermarkOptions() {#DiagramPageWatermarkOptions--}
```
public DiagramPageWatermarkOptions()
```


Initierar en ny instans av klassen `[DiagramPageWatermarkOptions](../../com.groupdocs.watermark.options/diagrampagewatermarkoptions)`.


### getPageIndex() {#getPageIndex--}
```
public final int getPageIndex()
```


Hämtar sidindexet som vattenstämpeln ska läggas till på.


**Returns:**
int - Sidindexet som vattenstämpeln ska läggas till på.

### setPageIndex(int value) {#setPageIndex-int-}
```
public final void setPageIndex(int value)
```


Ställer in sidindexet som vattenstämpeln ska läggas till på.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | int | Sidindexet som vattenstämpeln ska läggas till på. |
|

