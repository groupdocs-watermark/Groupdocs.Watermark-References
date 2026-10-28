---
title: "MultiframeImageWatermarkOptions"
second_title: "GroupDocs.Watermark pour Java Référence API"
description: "Représente les options d'ajout de filigrane lors de l'ajout d'un filigrane à une image multi-frame."
type: docs
weight: 26
url: /fr/java/com.groupdocs.watermark.options/multiframeimagewatermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions)
```
public class MultiframeImageWatermarkOptions extends WatermarkOptions
```

Représente les options d'ajout de filigrane lors de l'ajout d'un filigrane à une image multi-frame.

**Learn more:**

* [Add watermarks to images](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+images)

L'exemple suivant montre comment ajouter un filigrane à un cadre particulier d'une image multi‑cadres.
>
> ````
> ```
>
>    ImageLoadOptions loadOptions = new ImageLoadOptions();
>    Watermarker watermarker = new Watermarker("C:\\test.gif", loadOptions);
>
>    TextWatermark watermark = new TextWatermark("Test", new Font("Arial", 12));
>
>    MultiframeImageWatermarkOptions options = new MultiframeImageWatermarkOptions();
>    options.setFrameIndex(0);
>
>    watermarker.add(watermark, options);
>    watermarker.save("D:\\watermarked_test.gif");
>    watermarker.close();
>  
> ```
> ````


## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [MultiframeImageWatermarkOptions()](#MultiframeImageWatermarkOptions--) | Initialise une nouvelle instance de la classe `[MultiframeImageWatermarkOptions](../../com.groupdocs.watermark.options/multiframeimagewatermarkoptions)`. |
|
|  | [MultiframeImageWatermarkOptions(int frameIndex)](#MultiframeImageWatermarkOptions-int-) | Initialise une nouvelle instance de la classe `[MultiframeImageWatermarkOptions](../../com.groupdocs.watermark.options/multiframeimagewatermarkoptions)` avec un indice spécifié du cadre. |
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getFrameIndex()](#getFrameIndex--) | Obtient l'indice du cadre auquel ajouter le filigrane. |
|
|  | [setFrameIndex(int value)](#setFrameIndex-int-) | Définit l'indice du cadre auquel ajouter le filigrane. |
|
### MultiframeImageWatermarkOptions() {#MultiframeImageWatermarkOptions--}
```
public MultiframeImageWatermarkOptions()
```


Initialise une nouvelle instance de la classe `[MultiframeImageWatermarkOptions](../../com.groupdocs.watermark.options/multiframeimagewatermarkoptions)`.


### MultiframeImageWatermarkOptions(int frameIndex) {#MultiframeImageWatermarkOptions-int-}
```
public MultiframeImageWatermarkOptions(int frameIndex)
```


Initialise une nouvelle instance de la classe `[MultiframeImageWatermarkOptions](../../com.groupdocs.watermark.options/multiframeimagewatermarkoptions)` avec un indice spécifié du cadre.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | frameIndex | int | L'indice du cadre auquel ajouter le filigrane. |
|

### getFrameIndex() {#getFrameIndex--}
```
public final int getFrameIndex()
```


Obtient l'indice du cadre auquel ajouter le filigrane.


**Returns:**
int - L'indice du cadre auquel ajouter le filigrane.

<br />

*** ** * ** ***

-1 means all frames.

<br />


### setFrameIndex(int value) {#setFrameIndex-int-}
```
public final void setFrameIndex(int value)
```


Définit l'indice du cadre auquel ajouter le filigrane.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | int | L'indice du cadre auquel ajouter le filigrane. |

<br />

*** ** * ** ***

-1 means all frames.

<br />

|

