---
title: "PresentationWatermarkBaseSlideOptions"
second_title: "GroupDocs.Watermark pour Java Référence API"
description: "Classe de base pour les options d'ajout de filigrane à un document de présentation."
type: docs
weight: 39
url: /fr/java/com.groupdocs.watermark.options/presentationwatermarkbaseslideoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.PresentationWatermarkOptions](../../com.groupdocs.watermark.options/presentationwatermarkoptions)
```
public abstract class PresentationWatermarkBaseSlideOptions extends PresentationWatermarkOptions
```

Classe de base pour les options d'ajout de filigrane à un document de présentation.

**Learn more:**

* [Add watermarks to presentation documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+presentation+documents)

L'exemple suivant montre comment ajouter un filigrane à différentes diapositives de service d'une présentation Power Point.
>
> ````
> ```
>
>    PresentationLoadOptions loadOptions = new PresentationLoadOptions();
>    Watermarker watermarker = new Watermarker("D:\\test.pptx", loadOptions);
>
>    TextWatermark watermark = new TextWatermark("Test watermark", new Font("Arial", 8));
>
>    // Add watermark to all master slides
>    PresentationWatermarkMasterSlideOptions masterSlideOptions = new PresentationWatermarkMasterSlideOptions();
>    masterSlideOptions.setMasterSlideIndex(-1); // default
>    watermarker.add(watermark, masterSlideOptions);
>    
>    // Add watermark to all layout slides
>    PresentationWatermarkLayoutSlideOptions layoutSlideOptions = new PresentationWatermarkLayoutSlideOptions();
>    layoutSlideOptions.setLayoutSlideIndex(-1); // default
>    watermarker.add(watermark, layoutSlideOptions);
>    
>    // Add watermark to all notes slides
>    PresentationWatermarkNoteSlideOptions noteSlideOptions = new PresentationWatermarkNoteSlideOptions();
>    noteSlideOptions.setSlideIndex(-1); // default
>    watermarker.add(watermark, noteSlideOptions);
>    
>    // Add watermark to handout master
>    PresentationWatermarkMasterHandoutSlideOptions masterHandoutSlideOptions = new PresentationWatermarkMasterHandoutSlideOptions();
>    watermarker.add(watermark, masterHandoutSlideOptions);
>    
>    // Add watermark to notes master
>    PresentationWatermarkMasterNotesSlideOptions masterNotesSlideOptions = new PresentationWatermarkMasterNotesSlideOptions();
>    watermarker.add(watermark, masterNotesSlideOptions);
>    
>    watermarker.save("D:\\watermarked_test.pptx");
>    watermarker.close();
>  
> ```
> ````


## Méthodes

| Méthode | Description |
| --- | --- |
|  | [isLocked()](#isLocked--) | Obtient une valeur indiquant si la modification de la forme dans PowerPoint est interdite. |
|
|  | [setLocked(boolean value)](#setLocked-boolean-) | Définit une valeur indiquant si la modification de la forme dans PowerPoint est interdite. |
|
|  | [getProtectWithUnreadableCharacters()](#getProtectWithUnreadableCharacters--) | Obtient ou définit une valeur indiquant si les caractères du filigrane texte sont mélangés avec des caractères illisibles. |
|
|  | [setProtectWithUnreadableCharacters(boolean value)](#setProtectWithUnreadableCharacters-boolean-) | Obtient ou définit une valeur indiquant si les caractères du filigrane texte sont mélangés avec des caractères illisibles. |
|
|  | [getName()](#getName--) | Obtient le nom d'une forme. |
|
|  | [setName(String value)](#setName-java.lang.String-) | Définit le nom d'une forme. |
|
|  | [getAlternativeText()](#getAlternativeText--) | Obtient le texte descriptif (alternatif) qui sera associé à une forme. |
|
|  | [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | Définit le texte descriptif (alternatif) qui sera associé à une forme. |
|
|  | [getEffects()](#getEffects--) | Obtient une valeur de `[PresentationImageEffects](../../com.groupdocs.watermark.options/presentationimageeffects)` ou `[PresentationTextEffects](../../com.groupdocs.watermark.options/presentationtexteffects)` pour les effets qui doivent être appliqués au filigrane. |
|
|  | [setEffects(IPresentationWatermarkEffects value)](#setEffects-com.groupdocs.watermark.options.IPresentationWatermarkEffects-) | Définit une valeur de `[PresentationImageEffects](../../com.groupdocs.watermark.options/presentationimageeffects)` ou `[PresentationTextEffects](../../com.groupdocs.watermark.options/presentationtexteffects)` pour les effets qui doivent être appliqués au filigrane. |
|
### isLocked() {#isLocked--}
```
public final boolean isLocked()
```


Obtient une valeur indiquant si la modification de la forme dans PowerPoint est interdite.


**Returns:**
booléen - Si la valeur est vraie, la modification de la forme sera interdite. Par défaut, la valeur est fausse, la forme peut être modifiée dans PowerPoint.

### setLocked(boolean value) {#setLocked-boolean-}
```
public final void setLocked(boolean value)
```


Définit une valeur indiquant si la modification de la forme dans PowerPoint est interdite.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | boolean | Si la valeur est vraie, la modification de la forme sera interdite. Par défaut, la valeur est fausse, la forme peut être modifiée dans PowerPoint. |
|

### getProtectWithUnreadableCharacters() {#getProtectWithUnreadableCharacters--}
```
public final boolean getProtectWithUnreadableCharacters()
```


Obtient ou définit une valeur indiquant si les caractères du filigrane texte sont mélangés avec des caractères illisibles.

Cette protection s'applique uniquement lorsque `#isLocked().isLocked()` renvoie `true`.


**Returns:**
booléen - Une valeur indiquant si les caractères du filigrane texte sont mélangés avec des caractères illisibles.

### setProtectWithUnreadableCharacters(boolean value) {#setProtectWithUnreadableCharacters-boolean-}
```
public final void setProtectWithUnreadableCharacters(boolean value)
```


Obtient ou définit une valeur indiquant si les caractères du filigrane texte sont mélangés avec des caractères illisibles.

Cette protection s'applique uniquement lorsque `#isLocked().isLocked()` renvoie `true`.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | boolean | Une valeur indiquant si les caractères du filigrane texte sont mélangés avec des caractères illisibles. |
|

### getName() {#getName--}
```
public final String getName()
```


Obtient le nom d'une forme.


**Returns:**
java.lang.String - Le nom de la forme.

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Définit le nom d'une forme.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | java.lang.String | Le nom de la forme. |
|

### getAlternativeText() {#getAlternativeText--}
```
public final String getAlternativeText()
```


Obtient le texte descriptif (alternatif) qui sera associé à une forme.


**Returns:**
java.lang.String - Le texte descriptif (alternatif) qui sera associé à une forme.

### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public final void setAlternativeText(String value)
```


Définit le texte descriptif (alternatif) qui sera associé à une forme.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | java.lang.String | Le texte descriptif (alternatif) qui sera associé à une forme. |
|

### getEffects() {#getEffects--}
```
public final IPresentationWatermarkEffects getEffects()
```


Obtient une valeur de `[PresentationImageEffects](../../com.groupdocs.watermark.options/presentationimageeffects)` ou `[PresentationTextEffects](../../com.groupdocs.watermark.options/presentationtexteffects)` pour les effets qui doivent être appliqués au filigrane.


**Returns:**
[IPresentationWatermarkEffects](../../com.groupdocs.watermark.options/ipresentationwatermarkeffects) - The value of `[PresentationImageEffects](../../com.groupdocs.watermark.options/presentationimageeffects)` or `[PresentationTextEffects](../../com.groupdocs.watermark.options/presentationtexteffects)` for effects that should be applied to the watermark.

### setEffects(IPresentationWatermarkEffects value) {#setEffects-com.groupdocs.watermark.options.IPresentationWatermarkEffects-}
```
public final void setEffects(IPresentationWatermarkEffects value)
```


Définit une valeur de `[PresentationImageEffects](../../com.groupdocs.watermark.options/presentationimageeffects)` ou `[PresentationTextEffects](../../com.groupdocs.watermark.options/presentationtexteffects)` pour les effets qui doivent être appliqués au filigrane.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | value | [IPresentationWatermarkEffects](../../com.groupdocs.watermark.options/ipresentationwatermarkeffects) | La valeur de `[PresentationImageEffects](../../com.groupdocs.watermark.options/presentationimageeffects)` ou de `[PresentationTextEffects](../../com.groupdocs.watermark.options/presentationtexteffects)` pour les effets qui doivent être appliqués au filigrane. |
|

