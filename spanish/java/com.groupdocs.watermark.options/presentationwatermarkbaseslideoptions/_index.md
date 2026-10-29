---
title: "PresentationWatermarkBaseSlideOptions"
second_title: "Referencia de API de GroupDocs.Watermark para Java"
description: "Clase base para opciones de adición de marca de agua a un documento Presentation."
type: docs
weight: 39
url: /es/java/com.groupdocs.watermark.options/presentationwatermarkbaseslideoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.PresentationWatermarkOptions](../../com.groupdocs.watermark.options/presentationwatermarkoptions)
```
public abstract class PresentationWatermarkBaseSlideOptions extends PresentationWatermarkOptions
```

Clase base para opciones de adición de marca de agua a un documento Presentation.

**Learn more:**

* [Add watermarks to presentation documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+presentation+documents)

El siguiente ejemplo muestra cómo agregar una marca de agua a diferentes diapositivas de servicio de una presentación de PowerPoint.
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


## Métodos

| Método | Descripción |
| --- | --- |
|  | [isLocked()](#isLocked--) | Obtiene un valor que indica si la edición de la forma en PowerPoint está prohibida. |
|
|  | [setLocked(boolean value)](#setLocked-boolean-) | Establece un valor que indica si la edición de la forma en PowerPoint está prohibida. |
|
|  | [getProtectWithUnreadableCharacters()](#getProtectWithUnreadableCharacters--) | Obtiene o establece un valor que indica si los caracteres de la marca de agua de texto se mezclan con caracteres ilegibles. |
|
|  | [setProtectWithUnreadableCharacters(boolean value)](#setProtectWithUnreadableCharacters-boolean-) | Obtiene o establece un valor que indica si los caracteres de la marca de agua de texto se mezclan con caracteres ilegibles. |
|
|  | [getName()](#getName--) | Obtiene el nombre de una forma. |
|
|  | [setName(String value)](#setName-java.lang.String-) | Establece el nombre de una forma. |
|
|  | [getAlternativeText()](#getAlternativeText--) | Obtiene el texto descriptivo (alternativo) que se asociará a una forma. |
|
|  | [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | Establece el texto descriptivo (alternativo) que se asociará a una forma. |
|
|  | [getEffects()](#getEffects--) | Obtiene un valor de `[PresentationImageEffects](../../com.groupdocs.watermark.options/presentationimageeffects)` o `[PresentationTextEffects](../../com.groupdocs.watermark.options/presentationtexteffects)` para los efectos que deben aplicarse a la marca de agua. |
|
|  | [setEffects(IPresentationWatermarkEffects value)](#setEffects-com.groupdocs.watermark.options.IPresentationWatermarkEffects-) | Establece un valor de `[PresentationImageEffects](../../com.groupdocs.watermark.options/presentationimageeffects)` o `[PresentationTextEffects](../../com.groupdocs.watermark.options/presentationtexteffects)` para los efectos que deben aplicarse a la marca de agua. |
|
### isLocked() {#isLocked--}
```
public final boolean isLocked()
```


Obtiene un valor que indica si la edición de la forma en PowerPoint está prohibida.


**Returns:**
boolean - Si el valor es true, la edición de la forma estará prohibida. Por defecto, el valor es false, la forma puede editarse en PowerPoint.

### setLocked(boolean value) {#setLocked-boolean-}
```
public final void setLocked(boolean value)
```


Establece un valor que indica si la edición de la forma en PowerPoint está prohibida.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | boolean | Si el valor es true, la edición de la forma estará prohibida. Por defecto, el valor es false, la forma puede editarse en PowerPoint. |
|

### getProtectWithUnreadableCharacters() {#getProtectWithUnreadableCharacters--}
```
public final boolean getProtectWithUnreadableCharacters()
```


Obtiene o establece un valor que indica si los caracteres de la marca de agua de texto se mezclan con caracteres ilegibles.

Esta protección se aplica solo cuando `#isLocked().isLocked()` devuelve `true`.


**Returns:**
boolean - Un valor que indica si los caracteres de la marca de agua de texto se mezclan con caracteres ilegibles.

### setProtectWithUnreadableCharacters(boolean value) {#setProtectWithUnreadableCharacters-boolean-}
```
public final void setProtectWithUnreadableCharacters(boolean value)
```


Obtiene o establece un valor que indica si los caracteres de la marca de agua de texto se mezclan con caracteres ilegibles.

Esta protección se aplica solo cuando `#isLocked().isLocked()` devuelve `true`.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | boolean | Un valor que indica si los caracteres de la marca de agua de texto están mezclados con caracteres ilegibles. |
|

### getName() {#getName--}
```
public final String getName()
```


Obtiene el nombre de una forma.


**Returns:**
java.lang.String - El nombre de la forma.

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Establece el nombre de una forma.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | java.lang.String | El nombre de la forma. |
|

### getAlternativeText() {#getAlternativeText--}
```
public final String getAlternativeText()
```


Obtiene el texto descriptivo (alternativo) que se asociará a una forma.


**Returns:**
java.lang.String - El texto descriptivo (alternativo) que se asociará con una forma.

### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public final void setAlternativeText(String value)
```


Establece el texto descriptivo (alternativo) que se asociará a una forma.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | java.lang.String | El texto descriptivo (alternativo) que se asociará con una forma. |
|

### getEffects() {#getEffects--}
```
public final IPresentationWatermarkEffects getEffects()
```


Obtiene un valor de `[PresentationImageEffects](../../com.groupdocs.watermark.options/presentationimageeffects)` o `[PresentationTextEffects](../../com.groupdocs.watermark.options/presentationtexteffects)` para los efectos que deben aplicarse a la marca de agua.


**Returns:**
[IPresentationWatermarkEffects](../../com.groupdocs.watermark.options/ipresentationwatermarkeffects) - The value of `[PresentationImageEffects](../../com.groupdocs.watermark.options/presentationimageeffects)` or `[PresentationTextEffects](../../com.groupdocs.watermark.options/presentationtexteffects)` for effects that should be applied to the watermark.

### setEffects(IPresentationWatermarkEffects value) {#setEffects-com.groupdocs.watermark.options.IPresentationWatermarkEffects-}
```
public final void setEffects(IPresentationWatermarkEffects value)
```


Establece un valor de `[PresentationImageEffects](../../com.groupdocs.watermark.options/presentationimageeffects)` o `[PresentationTextEffects](../../com.groupdocs.watermark.options/presentationtexteffects)` para los efectos que deben aplicarse a la marca de agua.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | value | [IPresentationWatermarkEffects](../../com.groupdocs.watermark.options/ipresentationwatermarkeffects) | El valor de `[PresentationImageEffects](../../com.groupdocs.watermark.options/presentationimageeffects)` o `[PresentationTextEffects](../../com.groupdocs.watermark.options/presentationtexteffects)` para los efectos que se deben aplicar a la marca de agua. |
|

