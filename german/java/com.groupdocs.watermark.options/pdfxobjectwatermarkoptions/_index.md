---
title: "PdfXObjectWatermarkOptions"
second_title: "GroupDocs.Watermark für Java API-Referenz"
description: "Stellt Optionen zum Hinzufügen von Wasserzeichen beim Hinzufügen eines XObject‑Wasserzeichens zu einem PDF‑Dokument dar."
type: docs
weight: 34
url: /de/java/com.groupdocs.watermark.options/pdfxobjectwatermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.PdfWatermarkOptions](../../com.groupdocs.watermark.options/pdfwatermarkoptions)
```
public final class PdfXObjectWatermarkOptions extends PdfWatermarkOptions
```

Stellt Optionen zum Hinzufügen von Wasserzeichen beim Hinzufügen eines XObject‑Wasserzeichens zu einem PDF‑Dokument dar.

**Learn more:**

* [Add watermarks to PDF documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+PDF+documents)

Das folgende Beispiel zeigt, wie man ein Wasserzeichen zu einer bestimmten Seite eines PDF-Dokuments hinzufügt.
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


## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [PdfXObjectWatermarkOptions()](#PdfXObjectWatermarkOptions--) | Initialisiert eine neue Instanz der Klasse `[PdfXObjectWatermarkOptions](../../com.groupdocs.watermark.options/pdfxobjectwatermarkoptions)`. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getPageIndex()](#getPageIndex--) | Ermittelt den Seitenindex, zu dem das Wasserzeichen hinzugefügt werden soll. |
|
|  | [setPageIndex(int value)](#setPageIndex-int-) | Setzt den Seitenindex, zu dem das Wasserzeichen hinzugefügt werden soll. |
|
### PdfXObjectWatermarkOptions() {#PdfXObjectWatermarkOptions--}
```
public PdfXObjectWatermarkOptions()
```


Initialisiert eine neue Instanz der Klasse `[PdfXObjectWatermarkOptions](../../com.groupdocs.watermark.options/pdfxobjectwatermarkoptions)`.


### getPageIndex() {#getPageIndex--}
```
public final int getPageIndex()
```


Ermittelt den Seitenindex, zu dem das Wasserzeichen hinzugefügt werden soll.


**Returns:**
int - Der Seitenindex, zu dem das Wasserzeichen hinzugefügt werden soll.

### setPageIndex(int value) {#setPageIndex-int-}
```
public final void setPageIndex(int value)
```


Setzt den Seitenindex, zu dem das Wasserzeichen hinzugefügt werden soll.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | int | Der Seitenindex, zu dem das Wasserzeichen hinzugefügt werden soll. |
|

