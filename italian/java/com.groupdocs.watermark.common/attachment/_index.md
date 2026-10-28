---
title: "Attachment"
second_title: "Riferimento API di GroupDocs.Watermark per Java"
description: "Rappresenta un file allegato a un documento."
type: docs
weight: 10
url: /it/java/com.groupdocs.watermark.common/attachment/
---
**Inheritance:**
java.lang.Object
```
public abstract class Attachment
```

Rappresenta un file allegato a un documento.

**Learn more**

* [Email attachments](../https://docs.groupdocs.com/display/watermarkjava/Email+attachments)
* [Attachments in PDF document](../https://docs.groupdocs.com/display/watermarkjava/Attachments+in+PDF+document)
* [Working with spreadsheet document attachments](../https://docs.groupdocs.com/display/watermarkjava/Working+with+spreadsheet+document+attachments)

## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getDocumentInfo()](#getDocumentInfo--) | Restituisce le informazioni su un documento memorizzato nel file allegato. |
|
|  | [getContent()](#getContent--) | Ottiene il contenuto del file allegato. |
|
|  | [setContent(byte[] value)](#setContent-byte---) | Imposta il contenuto del file allegato. |
|
|  | [createWatermarker()](#createWatermarker--) | Carica un contenuto dal file allegato. |
|
|  | [createWatermarker(LoadOptions loadOptions)](#createWatermarker-com.groupdocs.watermark.options.LoadOptions-) | Carica un contenuto dal file allegato con le opzioni di caricamento specificate. |
|
|  | [createWatermarker(LoadOptions loadOptions, WatermarkerSettings watermarkerSettings)](#createWatermarker-com.groupdocs.watermark.options.LoadOptions-com.groupdocs.watermark.WatermarkerSettings-) | Carica un contenuto dal file allegato con le opzioni di caricamento e le impostazioni specificate. |
|
|  | [getContentStream()](#getContentStream--) | Ottiene uno stream dal file allegato. |
|
|  | [setContentStream(System.IO.Stream stream)](#setContentStream-com.aspose.ms.System.IO.Stream-) | Aggiorna il file allegato da uno stream. |
|
|  | [updateContent(Watermarker updatedVersion)](#updateContent-com.groupdocs.watermark.Watermarker-) | Aggiorna il contenuto allegato. |
|
### getDocumentInfo() {#getDocumentInfo--}
```
public final IDocumentInfo getDocumentInfo()
```


Restituisce le informazioni su un documento memorizzato nel file allegato.


**Returns:**
[IDocumentInfo](../../com.groupdocs.watermark.common/idocumentinfo) - The `[IDocumentInfo](../../com.groupdocs.watermark.common/idocumentinfo)` instance that contains detected information.

### getContent() {#getContent--}
```
public abstract byte[] getContent()
```


Ottiene il contenuto del file allegato.


**Returns:**
byte[] - Il contenuto del file allegato.

### setContent(byte[] value) {#setContent-byte---}
```
public abstract void setContent(byte[] value)
```


Imposta il contenuto del file allegato.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | byte[] | Il contenuto del file allegato. |
|

### createWatermarker() {#createWatermarker--}
```
public final Watermarker createWatermarker()
```


Carica un contenuto dal file allegato.


**Returns:**
[Watermarker](../../com.groupdocs.watermark/watermarker) - The instance of appropriate descendant of `[Content](../../com.groupdocs.watermark.contents/content)` class.

### createWatermarker(LoadOptions loadOptions) {#createWatermarker-com.groupdocs.watermark.options.LoadOptions-}
```
public final Watermarker createWatermarker(LoadOptions loadOptions)
```


Carica un contenuto dal file allegato con le opzioni di caricamento specificate.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | loadOptions | [LoadOptions](../../com.groupdocs.watermark.options/loadoptions) | Opzioni aggiuntive da utilizzare durante il caricamento del contenuto di un allegato. |
|

**Returns:**
[Watermarker](../../com.groupdocs.watermark/watermarker) - The instance of appropriate descendant of `[Content](../../com.groupdocs.watermark.contents/content)` class.

### createWatermarker(LoadOptions loadOptions, WatermarkerSettings watermarkerSettings) {#createWatermarker-com.groupdocs.watermark.options.LoadOptions-com.groupdocs.watermark.WatermarkerSettings-}
```
public final Watermarker createWatermarker(LoadOptions loadOptions, WatermarkerSettings watermarkerSettings)
```


Carica un contenuto dal file allegato con le opzioni di caricamento e le impostazioni specificate.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | loadOptions | [LoadOptions](../../com.groupdocs.watermark.options/loadoptions) | Opzioni aggiuntive da utilizzare durante il caricamento del contenuto di un allegato. |
|
|  | watermarkerSettings | [WatermarkerSettings](../../com.groupdocs.watermark/watermarkersettings) | Impostazioni aggiuntive da utilizzare quando si lavora con il documento caricato. |
|

**Returns:**
[Watermarker](../../com.groupdocs.watermark/watermarker) - The instance of appropriate descendant of `[Content](../../com.groupdocs.watermark.contents/content)` class.

### getContentStream() {#getContentStream--}
```
public System.IO.Stream getContentStream()
```


Ottiene uno stream dal file allegato.


**Returns:**
com.aspose.ms.System.IO.Stream - Lo stream da cui leggere il contenuto del file.

### setContentStream(System.IO.Stream stream) {#setContentStream-com.aspose.ms.System.IO.Stream-}
```
public void setContentStream(System.IO.Stream stream)
```


Aggiorna il file allegato da uno stream.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | stream | com.aspose.ms.System.IO.Stream | Lo stream da cui aggiornare il file allegato. |
|

### updateContent(Watermarker updatedVersion) {#updateContent-com.groupdocs.watermark.Watermarker-}
```
public final void updateContent(Watermarker updatedVersion)
```


Aggiorna il contenuto allegato.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | updatedVersion | [Watermarker](../../com.groupdocs.watermark/watermarker) | La versione aggiornata del contenuto. |
|

