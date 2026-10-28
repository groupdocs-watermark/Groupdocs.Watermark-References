---
title: "PresentationWatermarkLayoutSlideOptions"
second_title: "GroupDocs.Watermark pour Java Référence API"
description: "Représente les options lors de l'ajout d'un filigrane à une diapositive de mise en page d'un document de présentation."
type: docs
weight: 40
url: /fr/java/com.groupdocs.watermark.options/presentationwatermarklayoutslideoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.PresentationWatermarkOptions](../../com.groupdocs.watermark.options/presentationwatermarkoptions), [com.groupdocs.watermark.options.PresentationWatermarkBaseSlideOptions](../../com.groupdocs.watermark.options/presentationwatermarkbaseslideoptions)
```
public final class PresentationWatermarkLayoutSlideOptions extends PresentationWatermarkBaseSlideOptions
```

Représente les options lors de l'ajout d'un filigrane à une diapositive de mise en page d'un document de présentation.

**Learn more:**

* [Add watermarks to presentation documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+presentation+documents)

Voir les exemples d'utilisation dans `[PresentationWatermarkBaseSlideOptions](../../com.groupdocs.watermark.options/presentationwatermarkbaseslideoptions)`.

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [PresentationWatermarkLayoutSlideOptions()](#PresentationWatermarkLayoutSlideOptions--) | Initialise une nouvelle instance de la classe `[PresentationWatermarkOptions](../../com.groupdocs.watermark.options/presentationwatermarkoptions)`. |
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getLayoutSlideIndex()](#getLayoutSlideIndex--) | Obtient l’indice de la diapositive de mise en page à laquelle ajouter le filigrane. |
|
|  | [setLayoutSlideIndex(int value)](#setLayoutSlideIndex-int-) | Définit l’indice de la diapositive de mise en page à laquelle ajouter le filigrane. |
|
### PresentationWatermarkLayoutSlideOptions() {#PresentationWatermarkLayoutSlideOptions--}
```
public PresentationWatermarkLayoutSlideOptions()
```


Initialise une nouvelle instance de la classe `[PresentationWatermarkOptions](../../com.groupdocs.watermark.options/presentationwatermarkoptions)`.


### getLayoutSlideIndex() {#getLayoutSlideIndex--}
```
public final int getLayoutSlideIndex()
```


Obtient l’indice de la diapositive de mise en page à laquelle ajouter le filigrane.


**Returns:**
int - L’indice de la diapositive de mise en page à laquelle ajouter le filigrane.

<br />

*** ** * ** ***

-1 means all slides.

<br />


### setLayoutSlideIndex(int value) {#setLayoutSlideIndex-int-}
```
public final void setLayoutSlideIndex(int value)
```


Définit l’indice de la diapositive de mise en page à laquelle ajouter le filigrane.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | int | L’indice de la diapositive de mise en page à laquelle ajouter le filigrane. |

<br />

*** ** * ** ***

-1 means all slides.

<br />

|

