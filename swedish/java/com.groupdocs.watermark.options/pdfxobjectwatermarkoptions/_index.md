---
title: "PdfXObjectWatermarkOptions"
second_title: "GroupDocs.Watermark för Java API-referens"
description: "Representerar alternativ för att lägga till vattenstämpel när en XObject-vattenstämpel läggs till ett PDF-dokument."
type: docs
weight: 34
url: /sv/java/com.groupdocs.watermark.options/pdfxobjectwatermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.PdfWatermarkOptions](../../com.groupdocs.watermark.options/pdfwatermarkoptions)
```
public final class PdfXObjectWatermarkOptions extends PdfWatermarkOptions
```

Representerar alternativ för att lägga till vattenstämpel när en XObject-vattenstämpel läggs till ett PDF-dokument.

**Learn more:**

* [Add watermarks to PDF documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+PDF+documents)

Följande exempel visar hur man lägger till en vattenstämpel på en specifik sida i ett pdf-dokument.
>
> ````
> ```
>
>    PdfLoadOptions loadOptions = new PdfLoadOptions();
>    Watermarker watermarker = new Watermarker("C:\\doc.pdf", loadOptions);
>
>    ImageWatermark watermark = new ImageWatermark("C:\\watermark.png");
>
>    PdfXObjectWatermarkOptions options = new PdfXObjectWatermarkOptions();
>    options.setPageIndex(0);
>
>    watermarker.add(watermark, options);
>    watermarker.save("C:\\watermarked_doc.pdf");
>    watermark.close();
>    watermarker.close();
>  
> ```
> ````


## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [PdfXObjectWatermarkOptions()](#PdfXObjectWatermarkOptions--) | Initierar en ny instans av klassen `[PdfXObjectWatermarkOptions](../../com.groupdocs.watermark.options/pdfxobjectwatermarkoptions)`. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getPageIndex()](#getPageIndex--) | Hämtar sidindexet som vattenstämpeln ska läggas till på. |
|
|  | [setPageIndex(int value)](#setPageIndex-int-) | Ställer in sidindexet som vattenstämpeln ska läggas till på. |
|
### PdfXObjectWatermarkOptions() {#PdfXObjectWatermarkOptions--}
```
public PdfXObjectWatermarkOptions()
```


Initierar en ny instans av klassen `[PdfXObjectWatermarkOptions](../../com.groupdocs.watermark.options/pdfxobjectwatermarkoptions)`.


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

