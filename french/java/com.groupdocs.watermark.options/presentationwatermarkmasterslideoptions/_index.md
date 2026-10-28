---
title: "PresentationWatermarkMasterSlideOptions"
second_title: "GroupDocs.Watermark pour Java Référence API"
description: "Représente les options lors de l'ajout d'un filigrane à une diapositive maîtresse d'un document de présentation."
type: docs
weight: 43
url: /fr/java/com.groupdocs.watermark.options/presentationwatermarkmasterslideoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.PresentationWatermarkOptions](../../com.groupdocs.watermark.options/presentationwatermarkoptions), [com.groupdocs.watermark.options.PresentationWatermarkBaseSlideOptions](../../com.groupdocs.watermark.options/presentationwatermarkbaseslideoptions)
```
public final class PresentationWatermarkMasterSlideOptions extends PresentationWatermarkBaseSlideOptions
```

Représente les options lors de l'ajout d'un filigrane à une diapositive maîtresse d'un document de présentation.

**Learn more:**

* [Add watermarks to presentation documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+presentation+documents)

Voir les exemples d'utilisation dans `[PresentationWatermarkBaseSlideOptions](../../com.groupdocs.watermark.options/presentationwatermarkbaseslideoptions)`.

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [PresentationWatermarkMasterSlideOptions()](#PresentationWatermarkMasterSlideOptions--) | Initialise une nouvelle instance de la classe `[PresentationWatermarkMasterSlideOptions](../../com.groupdocs.watermark.options/presentationwatermarkmasterslideoptions)`. |
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getMasterSlideIndex()](#getMasterSlideIndex--) | Obtient l'index de la diapositive maître à laquelle ajouter le filigrane. |
|
|  | [setMasterSlideIndex(int value)](#setMasterSlideIndex-int-) | Définit l'index de la diapositive maître à laquelle ajouter le filigrane. |
|
### PresentationWatermarkMasterSlideOptions() {#PresentationWatermarkMasterSlideOptions--}
```
public PresentationWatermarkMasterSlideOptions()
```


Initialise une nouvelle instance de la classe `[PresentationWatermarkMasterSlideOptions](../../com.groupdocs.watermark.options/presentationwatermarkmasterslideoptions)`.


### getMasterSlideIndex() {#getMasterSlideIndex--}
```
public final int getMasterSlideIndex()
```


Obtient l'index de la diapositive maître à laquelle ajouter le filigrane.


**Returns:**
int - L'index de la diapositive maître à laquelle ajouter le filigrane.

<br />

*** ** * ** ***

-1 means all slides.

<br />


### setMasterSlideIndex(int value) {#setMasterSlideIndex-int-}
```
public final void setMasterSlideIndex(int value)
```


Définit l'index de la diapositive maître à laquelle ajouter le filigrane.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | int | L'index de la diapositive maître à laquelle ajouter le filigrane. |

<br />

*** ** * ** ***

-1 means all slides.

<br />

|

