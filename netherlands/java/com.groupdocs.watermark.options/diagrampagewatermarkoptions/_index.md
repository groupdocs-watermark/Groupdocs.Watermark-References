---
title: "DiagramPageWatermarkOptions"
second_title: "GroupDocs.Watermark for Java API-referentie"
description: "Stelt opties voor het toevoegen van een watermerk voor wanneer een vormwatermerk wordt toegevoegd aan een specifieke pagina van een Visiodocument voor."
type: docs
weight: 11
url: /nl/java/com.groupdocs.watermark.options/diagrampagewatermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.DiagramWatermarkOptions](../../com.groupdocs.watermark.options/diagramwatermarkoptions)
```
public final class DiagramPageWatermarkOptions extends DiagramWatermarkOptions
```

Stelt opties voor het toevoegen van een watermerk voor wanneer een vormwatermerk wordt toegevoegd aan een specifieke pagina van een Visiodocument voor.

**Learn more:**

* [Add watermarks to diagram documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+diagram+documents)

Het volgende voorbeeld laat zien hoe u een beschermd watermerk toevoegt aan de eerste pagina van een Visio‑document.
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


## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [DiagramPageWatermarkOptions()](#DiagramPageWatermarkOptions--) | Initialiseert een nieuw exemplaar van de `[DiagramPageWatermarkOptions](../../com.groupdocs.watermark.options/diagrampagewatermarkoptions)`‑klasse. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getPageIndex()](#getPageIndex--) | Haalt de pagina‑index op om het watermerk toe te voegen. |
|
|  | [setPageIndex(int value)](#setPageIndex-int-) | Stelt de pagina‑index in om het watermerk toe te voegen. |
|
### DiagramPageWatermarkOptions() {#DiagramPageWatermarkOptions--}
```
public DiagramPageWatermarkOptions()
```


Initialiseert een nieuw exemplaar van de `[DiagramPageWatermarkOptions](../../com.groupdocs.watermark.options/diagrampagewatermarkoptions)`‑klasse.


### getPageIndex() {#getPageIndex--}
```
public final int getPageIndex()
```


Haalt de pagina‑index op om het watermerk toe te voegen.


**Returns:**
int - De pagina‑index om het watermerk toe te voegen.

### setPageIndex(int value) {#setPageIndex-int-}
```
public final void setPageIndex(int value)
```


Stelt de pagina‑index in om het watermerk toe te voegen.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | int | De pagina‑index om het watermerk toe te voegen. |
|

