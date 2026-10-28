---
title: "Attachment"
second_title: "GroupDocs.Watermark for Java API-referentie"
description: "Stelt een bestand voor dat aan een document is gekoppeld."
type: docs
weight: 10
url: /nl/java/com.groupdocs.watermark.common/attachment/
---
**Inheritance:**
java.lang.Object
```
public abstract class Attachment
```

Stelt een bestand voor dat aan een document is gekoppeld.

**Learn more**

* [Email attachments](../https://docs.groupdocs.com/display/watermarkjava/Email+attachments)
* [Attachments in PDF document](../https://docs.groupdocs.com/display/watermarkjava/Attachments+in+PDF+document)
* [Working with spreadsheet document attachments](../https://docs.groupdocs.com/display/watermarkjava/Working+with+spreadsheet+document+attachments)

## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getDocumentInfo()](#getDocumentInfo--) | Haalt de informatie op over een document dat is opgeslagen in het bijgevoegde bestand. |
|
|  | [getContent()](#getContent--) | Haalt de inhoud van het bijgevoegde bestand op. |
|
|  | [setContent(byte[] value)](#setContent-byte---) | Stelt de inhoud van het bijgevoegde bestand in. |
|
|  | [createWatermarker()](#createWatermarker--) | Laadt de inhoud van het bijgevoegde bestand. |
|
|  | [createWatermarker(LoadOptions loadOptions)](#createWatermarker-com.groupdocs.watermark.options.LoadOptions-) | Laadt de inhoud van het bijgevoegde bestand met de opgegeven laadopties. |
|
|  | [createWatermarker(LoadOptions loadOptions, WatermarkerSettings watermarkerSettings)](#createWatermarker-com.groupdocs.watermark.options.LoadOptions-com.groupdocs.watermark.WatermarkerSettings-) | Laadt de inhoud van het bijgevoegde bestand met de opgegeven laadopties en instellingen. |
|
|  | [getContentStream()](#getContentStream--) | Haalt een stream op van het bijgevoegde bestand. |
|
|  | [setContentStream(System.IO.Stream stream)](#setContentStream-com.aspose.ms.System.IO.Stream-) | Werk het bijgevoegde bestand bij vanuit een stream. |
|
|  | [updateContent(Watermarker updatedVersion)](#updateContent-com.groupdocs.watermark.Watermarker-) | Werk de bijgevoegde inhoud bij. |
|
### getDocumentInfo() {#getDocumentInfo--}
```
public final IDocumentInfo getDocumentInfo()
```


Haalt de informatie op over een document dat is opgeslagen in het bijgevoegde bestand.


**Returns:**
[IDocumentInfo](../../com.groupdocs.watermark.common/idocumentinfo) - The `[IDocumentInfo](../../com.groupdocs.watermark.common/idocumentinfo)` instance that contains detected information.

### getContent() {#getContent--}
```
public abstract byte[] getContent()
```


Haalt de inhoud van het bijgevoegde bestand op.


**Returns:**
byte[] - De inhoud van het bijgevoegde bestand.

### setContent(byte[] value) {#setContent-byte---}
```
public abstract void setContent(byte[] value)
```


Stelt de inhoud van het bijgevoegde bestand in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | byte[] | De inhoud van het bijgevoegde bestand. |
|

### createWatermarker() {#createWatermarker--}
```
public final Watermarker createWatermarker()
```


Laadt de inhoud van het bijgevoegde bestand.


**Returns:**
[Watermarker](../../com.groupdocs.watermark/watermarker) - The instance of appropriate descendant of `[Content](../../com.groupdocs.watermark.contents/content)` class.

### createWatermarker(LoadOptions loadOptions) {#createWatermarker-com.groupdocs.watermark.options.LoadOptions-}
```
public final Watermarker createWatermarker(LoadOptions loadOptions)
```


Laadt de inhoud van het bijgevoegde bestand met de opgegeven laadopties.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | loadOptions | [LoadOptions](../../com.groupdocs.watermark.options/loadoptions) | Aanvullende opties om te gebruiken bij het laden van een bijlage-inhoud. |
|

**Returns:**
[Watermarker](../../com.groupdocs.watermark/watermarker) - The instance of appropriate descendant of `[Content](../../com.groupdocs.watermark.contents/content)` class.

### createWatermarker(LoadOptions loadOptions, WatermarkerSettings watermarkerSettings) {#createWatermarker-com.groupdocs.watermark.options.LoadOptions-com.groupdocs.watermark.WatermarkerSettings-}
```
public final Watermarker createWatermarker(LoadOptions loadOptions, WatermarkerSettings watermarkerSettings)
```


Laadt de inhoud van het bijgevoegde bestand met de opgegeven laadopties en instellingen.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | loadOptions | [LoadOptions](../../com.groupdocs.watermark.options/loadoptions) | Aanvullende opties om te gebruiken bij het laden van een bijlage-inhoud. |
|
|  | watermarkerSettings | [WatermarkerSettings](../../com.groupdocs.watermark/watermarkersettings) | Aanvullende instellingen om te gebruiken bij het werken met een geladen document. |
|

**Returns:**
[Watermarker](../../com.groupdocs.watermark/watermarker) - The instance of appropriate descendant of `[Content](../../com.groupdocs.watermark.contents/content)` class.

### getContentStream() {#getContentStream--}
```
public System.IO.Stream getContentStream()
```


Haalt een stream op van het bijgevoegde bestand.


**Returns:**
com.aspose.ms.System.IO.Stream - De stream om de bestandsinhoud van te lezen.

### setContentStream(System.IO.Stream stream) {#setContentStream-com.aspose.ms.System.IO.Stream-}
```
public void setContentStream(System.IO.Stream stream)
```


Werk het bijgevoegde bestand bij vanuit een stream.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | stream | com.aspose.ms.System.IO.Stream | De stream om het bijgevoegde bestand mee bij te werken. |
|

### updateContent(Watermarker updatedVersion) {#updateContent-com.groupdocs.watermark.Watermarker-}
```
public final void updateContent(Watermarker updatedVersion)
```


Werk de bijgevoegde inhoud bij.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | updatedVersion | [Watermarker](../../com.groupdocs.watermark/watermarker) | De bijgewerkte versie van de inhoud. |
|

