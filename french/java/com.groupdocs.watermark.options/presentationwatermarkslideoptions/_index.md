---
title: "PresentationWatermarkSlideOptions"
second_title: "GroupDocs.Watermark pour Java Référence API"
description: "Représente les options lors de l'ajout d'un filigrane à une diapositive de document Presentation."
type: docs
weight: 46
url: /fr/java/com.groupdocs.watermark.options/presentationwatermarkslideoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.PresentationWatermarkOptions](../../com.groupdocs.watermark.options/presentationwatermarkoptions), [com.groupdocs.watermark.options.PresentationWatermarkBaseSlideOptions](../../com.groupdocs.watermark.options/presentationwatermarkbaseslideoptions)
```
public final class PresentationWatermarkSlideOptions extends PresentationWatermarkBaseSlideOptions
```

Représente les options lors de l'ajout d'un filigrane à une diapositive de document Presentation.

**Learn more:**

* [Add watermarks to presentation documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+presentation+documents)

L'exemple suivant montre comment ajouter un filigrane à une diapositive particulière d'une présentation Power Point.
>
> ````
> ```
>
>    PresentationLoadOptions loadOptions = new PresentationLoadOptions();
>    Watermarker watermarker = new Watermarker("C:\\Documents\\test.ppt", loadOptions);
>
>    TextWatermark watermark = new TextWatermark("Test watermark", new Font("Arial", 36, FontStyle.Bold | FontStyle.Italic));
>    watermark.setHorizontalAlignment(HorizontalAlignment.Center);
>    watermark.setVerticalAlignment(VerticalAlignment.Center);
>  
>    PresentationWatermarkSlideOptions options = new PresentationWatermarkSlideOptions();
>    options.setSlideIndex(0);
>    options.setLocked(false); // default
>    options.setProtectWithUnreadableCharacters(false); // default
>    options.setName(null); // default
>    options.setAlternativeText(null); // default
>    
>    watermarker.save("C:\\Documents\\watermarked_test.ppt");
>    watermarker.close();
>  
> ```
> ````


## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [PresentationWatermarkSlideOptions()](#PresentationWatermarkSlideOptions--) | Initialise une nouvelle instance de la classe `[PresentationWatermarkSlideOptions](../../com.groupdocs.watermark.options/presentationwatermarkslideoptions)`. |
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getSlideIndex()](#getSlideIndex--) | Obtient l'index de la diapositive à laquelle ajouter le filigrane. |
|
|  | [setSlideIndex(int value)](#setSlideIndex-int-) | Définit l'index de la diapositive à laquelle ajouter le filigrane. |
|
### PresentationWatermarkSlideOptions() {#PresentationWatermarkSlideOptions--}
```
public PresentationWatermarkSlideOptions()
```


Initialise une nouvelle instance de la classe `[PresentationWatermarkSlideOptions](../../com.groupdocs.watermark.options/presentationwatermarkslideoptions)`.


### getSlideIndex() {#getSlideIndex--}
```
public final int getSlideIndex()
```


Obtient l'index de la diapositive à laquelle ajouter le filigrane.


**Returns:**
int - L'index de la diapositive à laquelle ajouter le filigrane.

<br />

*** ** * ** ***

-1 means all slides.

<br />


### setSlideIndex(int value) {#setSlideIndex-int-}
```
public final void setSlideIndex(int value)
```


Définit l'index de la diapositive à laquelle ajouter le filigrane.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | int | L'index de la diapositive à laquelle ajouter le filigrane. |

<br />

*** ** * ** ***

-1 means all slides.

<br />

|

