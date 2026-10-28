---
title: "Attachment"
second_title: "GroupDocs.Watermark pour Java Référence API"
description: "Représente un fichier joint à un document."
type: docs
weight: 10
url: /fr/java/com.groupdocs.watermark.common/attachment/
---
**Inheritance:**
java.lang.Object
```
public abstract class Attachment
```

Représente un fichier joint à un document.

**Learn more**

* [Email attachments](../https://docs.groupdocs.com/display/watermarkjava/Email+attachments)
* [Attachments in PDF document](../https://docs.groupdocs.com/display/watermarkjava/Attachments+in+PDF+document)
* [Working with spreadsheet document attachments](../https://docs.groupdocs.com/display/watermarkjava/Working+with+spreadsheet+document+attachments)

## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getDocumentInfo()](#getDocumentInfo--) | Obtient les informations sur un document stocké dans le fichier joint. |
|
|  | [getContent()](#getContent--) | Obtient le contenu du fichier joint. |
|
|  | [setContent(byte[] value)](#setContent-byte---) | Définit le contenu du fichier joint. |
|
|  | [createWatermarker()](#createWatermarker--) | Charge un contenu depuis le fichier joint. |
|
|  | [createWatermarker(LoadOptions loadOptions)](#createWatermarker-com.groupdocs.watermark.options.LoadOptions-) | Charge un contenu depuis le fichier joint avec les options de chargement spécifiées. |
|
|  | [createWatermarker(LoadOptions loadOptions, WatermarkerSettings watermarkerSettings)](#createWatermarker-com.groupdocs.watermark.options.LoadOptions-com.groupdocs.watermark.WatermarkerSettings-) | Charge un contenu depuis le fichier joint avec les options de chargement et les paramètres spécifiés. |
|
|  | [getContentStream()](#getContentStream--) | Obtient un flux depuis le fichier joint. |
|
|  | [setContentStream(System.IO.Stream stream)](#setContentStream-com.aspose.ms.System.IO.Stream-) | Met à jour le fichier joint à partir d'un flux. |
|
|  | [updateContent(Watermarker updatedVersion)](#updateContent-com.groupdocs.watermark.Watermarker-) | Met à jour le contenu joint. |
|
### getDocumentInfo() {#getDocumentInfo--}
```
public final IDocumentInfo getDocumentInfo()
```


Obtient les informations sur un document stocké dans le fichier joint.


**Returns:**
[IDocumentInfo](../../com.groupdocs.watermark.common/idocumentinfo) - The `[IDocumentInfo](../../com.groupdocs.watermark.common/idocumentinfo)` instance that contains detected information.

### getContent() {#getContent--}
```
public abstract byte[] getContent()
```


Obtient le contenu du fichier joint.


**Returns:**
byte[] - Le contenu du fichier joint.

### setContent(byte[] value) {#setContent-byte---}
```
public abstract void setContent(byte[] value)
```


Définit le contenu du fichier joint.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | byte[] | Le contenu du fichier joint. |
|

### createWatermarker() {#createWatermarker--}
```
public final Watermarker createWatermarker()
```


Charge un contenu depuis le fichier joint.


**Returns:**
[Watermarker](../../com.groupdocs.watermark/watermarker) - The instance of appropriate descendant of `[Content](../../com.groupdocs.watermark.contents/content)` class.

### createWatermarker(LoadOptions loadOptions) {#createWatermarker-com.groupdocs.watermark.options.LoadOptions-}
```
public final Watermarker createWatermarker(LoadOptions loadOptions)
```


Charge un contenu depuis le fichier joint avec les options de chargement spécifiées.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | loadOptions | [LoadOptions](../../com.groupdocs.watermark.options/loadoptions) | Options supplémentaires à utiliser lors du chargement du contenu d'une pièce jointe. |
|

**Returns:**
[Watermarker](../../com.groupdocs.watermark/watermarker) - The instance of appropriate descendant of `[Content](../../com.groupdocs.watermark.contents/content)` class.

### createWatermarker(LoadOptions loadOptions, WatermarkerSettings watermarkerSettings) {#createWatermarker-com.groupdocs.watermark.options.LoadOptions-com.groupdocs.watermark.WatermarkerSettings-}
```
public final Watermarker createWatermarker(LoadOptions loadOptions, WatermarkerSettings watermarkerSettings)
```


Charge un contenu depuis le fichier joint avec les options de chargement et les paramètres spécifiés.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | loadOptions | [LoadOptions](../../com.groupdocs.watermark.options/loadoptions) | Options supplémentaires à utiliser lors du chargement du contenu d'une pièce jointe. |
|
|  | watermarkerSettings | [WatermarkerSettings](../../com.groupdocs.watermark/watermarkersettings) | Paramètres supplémentaires à utiliser lors du travail avec le document chargé. |
|

**Returns:**
[Watermarker](../../com.groupdocs.watermark/watermarker) - The instance of appropriate descendant of `[Content](../../com.groupdocs.watermark.contents/content)` class.

### getContentStream() {#getContentStream--}
```
public System.IO.Stream getContentStream()
```


Obtient un flux depuis le fichier joint.


**Returns:**
com.aspose.ms.System.IO.Stream - Le flux à partir duquel lire le contenu du fichier.

### setContentStream(System.IO.Stream stream) {#setContentStream-com.aspose.ms.System.IO.Stream-}
```
public void setContentStream(System.IO.Stream stream)
```


Met à jour le fichier joint à partir d'un flux.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | stream | com.aspose.ms.System.IO.Stream | Le flux à partir duquel mettre à jour le fichier joint. |
|

### updateContent(Watermarker updatedVersion) {#updateContent-com.groupdocs.watermark.Watermarker-}
```
public final void updateContent(Watermarker updatedVersion)
```


Met à jour le contenu joint.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | updatedVersion | [Watermarker](../../com.groupdocs.watermark/watermarker) | La version mise à jour du contenu. |
|

