---
title: "WordProcessingWatermarkPagesOptions"
second_title: "GroupDocs.Watermark pour Java Référence API"
description: "Représente les options lors de l'ajout d'un filigrane aux pages d'un document Word."
type: docs
weight: 76
url: /fr/java/com.groupdocs.watermark.options/wordprocessingwatermarkpagesoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.WordProcessingWatermarkOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkoptions), [com.groupdocs.watermark.options.WordProcessingWatermarkBaseOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkbaseoptions)
```
public final class WordProcessingWatermarkPagesOptions extends WordProcessingWatermarkBaseOptions
```

Représente les options lors de l'ajout d'un filigrane aux pages d'un document Word.

**Learn more:**

* [Add watermarks to word processing documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+word+processing+documents)

L'exemple suivant montre comment ajouter un filigrane à une page particulière d'un document Word.
>
> ````
> ```
>
>    WordProcessingLoadOptions loadOptions = new WordProcessingLoadOptions();
>    Watermarker watermarker = new Watermarker("D:\\test.doc", loadOptions);
>
>    TextWatermark watermark = new TextWatermark("Test", new Font("Arial", 14));
>
>    WordProcessingWatermarkPagesOptions options = new WordProcessingWatermarkPagesOptions();
>    options.setPageNumbers(new int[] { 1 });
>    
>    watermarker.save("D:\\watermarked_test.doc");
>    watermarker.close();
>  
> ```
> ````


## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [WordProcessingWatermarkPagesOptions()](#WordProcessingWatermarkPagesOptions--) | Initialise une nouvelle instance de la classe `[WordProcessingWatermarkPagesOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkpagesoptions)`. |
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getPageNumbers()](#getPageNumbers--) | Obtient les numéros de page où ajouter le filigrane. |
|
|  | [setPageNumbers(int[] value)](#setPageNumbers-int---) | Définit les numéros de page où ajouter le filigrane. |
|
### WordProcessingWatermarkPagesOptions() {#WordProcessingWatermarkPagesOptions--}
```
public WordProcessingWatermarkPagesOptions()
```


Initialise une nouvelle instance de la classe `[WordProcessingWatermarkPagesOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkpagesoptions)`.


### getPageNumbers() {#getPageNumbers--}
```
public final int[] getPageNumbers()
```


Obtient les numéros de page où ajouter le filigrane.


**Returns:**
int[] - Les numéros de page où ajouter le filigrane.

<br />

*** ** * ** ***

Tous les nombres doivent être supérieurs ou égaux à 1. Cette propriété n'est utilisée que lors de l'ajout du filigrane à un document. Si cette valeur est  null  ou vide, le filigrane est ajouté à toutes les pages.

<br />


### setPageNumbers(int[] value) {#setPageNumbers-int---}
```
public final void setPageNumbers(int[] value)
```


Définit les numéros de page où ajouter le filigrane.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | int[] | Les numéros de page où ajouter le filigrane. |

<br />

*** ** * ** ***

Tous les nombres doivent être supérieurs ou égaux à 1. Cette propriété n'est utilisée que lors de l'ajout du filigrane à un document. Si cette valeur est  null  ou vide, le filigrane est ajouté à toutes les pages.

<br />

|

