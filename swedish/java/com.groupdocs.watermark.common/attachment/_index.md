---
title: "Attachment"
second_title: "GroupDocs.Watermark för Java API-referens"
description: "Representerar en fil som är bifogad till ett dokument."
type: docs
weight: 10
url: /sv/java/com.groupdocs.watermark.common/attachment/
---
**Inheritance:**
java.lang.Object
```
public abstract class Attachment
```

Representerar en fil som är bifogad till ett dokument.

**Learn more**

* [Email attachments](../https://docs.groupdocs.com/display/watermarkjava/Email+attachments)
* [Attachments in PDF document](../https://docs.groupdocs.com/display/watermarkjava/Attachments+in+PDF+document)
* [Working with spreadsheet document attachments](../https://docs.groupdocs.com/display/watermarkjava/Working+with+spreadsheet+document+attachments)

## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getDocumentInfo()](#getDocumentInfo--) | Hämtar informationen om ett dokument som lagras i den bifogade filen. |
|
|  | [getContent()](#getContent--) | Hämtar det bifogade filinnehållet. |
|
|  | [setContent(byte[] value)](#setContent-byte---) | Ställer in det bifogade filinnehållet. |
|
|  | [createWatermarker()](#createWatermarker--) | Laddar ett innehåll från den bifogade filen. |
|
|  | [createWatermarker(LoadOptions loadOptions)](#createWatermarker-com.groupdocs.watermark.options.LoadOptions-) | Laddar ett innehåll från den bifogade filen med de angivna inläsningsalternativen. |
|
|  | [createWatermarker(LoadOptions loadOptions, WatermarkerSettings watermarkerSettings)](#createWatermarker-com.groupdocs.watermark.options.LoadOptions-com.groupdocs.watermark.WatermarkerSettings-) | Laddar ett innehåll från den bifogade filen med de angivna inläsningsalternativen och inställningarna. |
|
|  | [getContentStream()](#getContentStream--) | Hämtar en ström från den bifogade filen. |
|
|  | [setContentStream(System.IO.Stream stream)](#setContentStream-com.aspose.ms.System.IO.Stream-) | Uppdaterar den bifogade filen från en ström. |
|
|  | [updateContent(Watermarker updatedVersion)](#updateContent-com.groupdocs.watermark.Watermarker-) | Uppdaterar det bifogade innehållet. |
|
### getDocumentInfo() {#getDocumentInfo--}
```
public final IDocumentInfo getDocumentInfo()
```


Hämtar informationen om ett dokument som lagras i den bifogade filen.


**Returns:**
[IDocumentInfo](../../com.groupdocs.watermark.common/idocumentinfo) - The `[IDocumentInfo](../../com.groupdocs.watermark.common/idocumentinfo)` instance that contains detected information.

### getContent() {#getContent--}
```
public abstract byte[] getContent()
```


Hämtar det bifogade filinnehållet.


**Returns:**
byte[] - Det bifogade filinnehållet.

### setContent(byte[] value) {#setContent-byte---}
```
public abstract void setContent(byte[] value)
```


Ställer in det bifogade filinnehållet.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | byte[] | Det bifogade filinnehållet. |
|

### createWatermarker() {#createWatermarker--}
```
public final Watermarker createWatermarker()
```


Laddar ett innehåll från den bifogade filen.


**Returns:**
[Watermarker](../../com.groupdocs.watermark/watermarker) - The instance of appropriate descendant of `[Content](../../com.groupdocs.watermark.contents/content)` class.

### createWatermarker(LoadOptions loadOptions) {#createWatermarker-com.groupdocs.watermark.options.LoadOptions-}
```
public final Watermarker createWatermarker(LoadOptions loadOptions)
```


Laddar ett innehåll från den bifogade filen med de angivna inläsningsalternativen.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | loadOptions | [LoadOptions](../../com.groupdocs.watermark.options/loadoptions) | Ytterligare alternativ att använda när ett bilagainnehåll laddas. |
|

**Returns:**
[Watermarker](../../com.groupdocs.watermark/watermarker) - The instance of appropriate descendant of `[Content](../../com.groupdocs.watermark.contents/content)` class.

### createWatermarker(LoadOptions loadOptions, WatermarkerSettings watermarkerSettings) {#createWatermarker-com.groupdocs.watermark.options.LoadOptions-com.groupdocs.watermark.WatermarkerSettings-}
```
public final Watermarker createWatermarker(LoadOptions loadOptions, WatermarkerSettings watermarkerSettings)
```


Laddar ett innehåll från den bifogade filen med de angivna inläsningsalternativen och inställningarna.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | loadOptions | [LoadOptions](../../com.groupdocs.watermark.options/loadoptions) | Ytterligare alternativ att använda när ett bilagainnehåll laddas. |
|
|  | watermarkerSettings | [WatermarkerSettings](../../com.groupdocs.watermark/watermarkersettings) | Ytterligare inställningar att använda när man arbetar med ett inläst dokument. |
|

**Returns:**
[Watermarker](../../com.groupdocs.watermark/watermarker) - The instance of appropriate descendant of `[Content](../../com.groupdocs.watermark.contents/content)` class.

### getContentStream() {#getContentStream--}
```
public System.IO.Stream getContentStream()
```


Hämtar en ström från den bifogade filen.


**Returns:**
com.aspose.ms.System.IO.Stream - Strömmen för att läsa filinnehållet från.

### setContentStream(System.IO.Stream stream) {#setContentStream-com.aspose.ms.System.IO.Stream-}
```
public void setContentStream(System.IO.Stream stream)
```


Uppdaterar den bifogade filen från en ström.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | stream | com.aspose.ms.System.IO.Stream | Strömmen för att uppdatera den bifogade filen från. |
|

### updateContent(Watermarker updatedVersion) {#updateContent-com.groupdocs.watermark.Watermarker-}
```
public final void updateContent(Watermarker updatedVersion)
```


Uppdaterar det bifogade innehållet.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | updatedVersion | [Watermarker](../../com.groupdocs.watermark/watermarker) | Den uppdaterade versionen av innehållet. |
|

