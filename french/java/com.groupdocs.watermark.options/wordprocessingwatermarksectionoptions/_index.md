---
title: "WordProcessingWatermarkSectionOptions"
second_title: "GroupDocs.Watermark pour Java Référence API"
description: "Représente les options lors de l'ajout d'un filigrane de forme à une section de document Word."
type: docs
weight: 77
url: /fr/java/com.groupdocs.watermark.options/wordprocessingwatermarksectionoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.WordProcessingWatermarkOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkoptions), [com.groupdocs.watermark.options.WordProcessingWatermarkBaseOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkbaseoptions)
```
public final class WordProcessingWatermarkSectionOptions extends WordProcessingWatermarkBaseOptions
```

Représente les options lors de l'ajout d'un filigrane de forme à une section de document Word.

**Learn more:**

* [Add watermarks to word processing documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+word+processing+documents)

L'exemple suivant montre comment ajouter un filigrane à une section particulière d'un document Word.
>
> ````
> ```
>
>    WordProcessingLoadOptions loadOptions = new WordProcessingLoadOptions();
>    Watermarker watermarker = new Watermarker("D:\\test.doc", loadOptions);
>
>    TextWatermark watermark = new TextWatermark("Test", new Font("Arial", 14));
>
>    WordProcessingWatermarkSectionOptions options = new WordProcessingWatermarkSectionOptions();
>    options.setSectionIndex(0);
>    
>    watermarker.save("D:\\watermarked_test.doc");
>    watermarker.close();
>  
> ```
> ````


## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [WordProcessingWatermarkSectionOptions()](#WordProcessingWatermarkSectionOptions--) | Initialise une nouvelle instance de la classe `[WordProcessingWatermarkSectionOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarksectionoptions)`. |
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getSectionIndex()](#getSectionIndex--) | Obtient l'index d'une section où ajouter le filigrane. |
|
|  | [setSectionIndex(int value)](#setSectionIndex-int-) | Définit l'index d'une section où ajouter le filigrane. |
|
### WordProcessingWatermarkSectionOptions() {#WordProcessingWatermarkSectionOptions--}
```
public WordProcessingWatermarkSectionOptions()
```


Initialise une nouvelle instance de la classe `[WordProcessingWatermarkSectionOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarksectionoptions)`.


### getSectionIndex() {#getSectionIndex--}
```
public final int getSectionIndex()
```


Obtient l'index d'une section où ajouter le filigrane.


**Returns:**
int - L’indice d’une section à laquelle ajouter le filigrane.

<br />

*** ** * ** ***

-1 means all sections.

<br />


### setSectionIndex(int value) {#setSectionIndex-int-}
```
public final void setSectionIndex(int value)
```


Définit l'index d'une section où ajouter le filigrane.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | int | L’indice d’une section à laquelle ajouter le filigrane. |

<br />

*** ** * ** ***

-1 means all sections.

<br />

|

