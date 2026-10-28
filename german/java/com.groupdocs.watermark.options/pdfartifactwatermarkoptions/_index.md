---
title: "PdfArtifactWatermarkOptions"
second_title: "GroupDocs.Watermark für Java API-Referenz"
description: "Stellt Optionen zum Hinzufügen von Wasserzeichen beim Hinzufügen eines Artefaktwasserzeichens zu einem PDF‑Dokument dar."
type: docs
weight: 29
url: /de/java/com.groupdocs.watermark.options/pdfartifactwatermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.PdfWatermarkOptions](../../com.groupdocs.watermark.options/pdfwatermarkoptions)
```
public final class PdfArtifactWatermarkOptions extends PdfWatermarkOptions
```

Stellt Optionen zum Hinzufügen von Wasserzeichen beim Hinzufügen eines Artefaktwasserzeichens zu einem PDF‑Dokument dar.

**Leran more:**

* [Add watermarks to PDF documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+PDF+documents)

Das folgende Beispiel zeigt, wie man ein Bild‑Artifact‑Wasserzeichen zu einem PDF-Dokument hinzufügt.
>
> ````
> ```
>
>    PdfLoadOptions loadOptions = new PdfLoadOptions();
>    Watermarker watermarker = new Watermarker("D:\\test.pdf", loadOptions);
>
>    ImageWatermark watermark = new ImageWatermark("D:\\icon.png");
>
>    PdfArtifactWatermarkOptions options = new PdfArtifactWatermarkOptions();
>    options.setPageIndex(-1); // default - all pages
>
>    watermarker.add(watermark, options);
>    watermarker.save("D:\\watermarked_test.pdf");
>    watermark.close();
>    watermarker.close();
>  
> ```
> ````


## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [PdfArtifactWatermarkOptions()](#PdfArtifactWatermarkOptions--) | Initialisiert eine neue Instanz der Klasse `[PdfArtifactWatermarkOptions](../../com.groupdocs.watermark.options/pdfartifactwatermarkoptions)`. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getPageIndex()](#getPageIndex--) | Ermittelt den Seitenindex, zu dem das Wasserzeichen hinzugefügt werden soll. |
|
|  | [setPageIndex(int value)](#setPageIndex-int-) | Setzt den Seitenindex, zu dem das Wasserzeichen hinzugefügt werden soll. |
|
### PdfArtifactWatermarkOptions() {#PdfArtifactWatermarkOptions--}
```
public PdfArtifactWatermarkOptions()
```


Initialisiert eine neue Instanz der Klasse `[PdfArtifactWatermarkOptions](../../com.groupdocs.watermark.options/pdfartifactwatermarkoptions)`.


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

