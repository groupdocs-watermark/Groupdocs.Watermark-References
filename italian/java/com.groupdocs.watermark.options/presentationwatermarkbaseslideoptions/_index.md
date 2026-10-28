---
title: "PresentationWatermarkBaseSlideOptions"
second_title: "Riferimento API di GroupDocs.Watermark per Java"
description: "Classe base per le opzioni di aggiunta della filigrana a un documento di presentazione."
type: docs
weight: 39
url: /it/java/com.groupdocs.watermark.options/presentationwatermarkbaseslideoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.PresentationWatermarkOptions](../../com.groupdocs.watermark.options/presentationwatermarkoptions)
```
public abstract class PresentationWatermarkBaseSlideOptions extends PresentationWatermarkOptions
```

Classe base per le opzioni di aggiunta della filigrana a un documento di presentazione.

**Learn more:**

* [Add watermarks to presentation documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+presentation+documents)

Il seguente esempio dimostra come aggiungere una filigrana a diverse diapositive di servizio di una presentazione Power Point.
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


## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [isLocked()](#isLocked--) | Restituisce un valore che indica se la modifica della forma in PowerPoint è vietata. |
|
|  | [setLocked(boolean value)](#setLocked-boolean-) | Imposta un valore che indica se la modifica della forma in PowerPoint è vietata. |
|
|  | [getProtectWithUnreadableCharacters()](#getProtectWithUnreadableCharacters--) | Restituisce o imposta un valore che indica se i caratteri della filigrana di testo sono mescolati con caratteri illeggibili. |
|
|  | [setProtectWithUnreadableCharacters(boolean value)](#setProtectWithUnreadableCharacters-boolean-) | Restituisce o imposta un valore che indica se i caratteri della filigrana di testo sono mescolati con caratteri illeggibili. |
|
|  | [getName()](#getName--) | Ottiene il nome di una forma. |
|
|  | [setName(String value)](#setName-java.lang.String-) | Imposta il nome di una forma. |
|
|  | [getAlternativeText()](#getAlternativeText--) | Ottiene il testo descrittivo (alternativo) che sarà associato a una forma. |
|
|  | [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | Imposta il testo descrittivo (alternativo) che sarà associato a una forma. |
|
|  | [getEffects()](#getEffects--) | Restituisce un valore di `[PresentationImageEffects](../../com.groupdocs.watermark.options/presentationimageeffects)` o `[PresentationTextEffects](../../com.groupdocs.watermark.options/presentationtexteffects)` per gli effetti da applicare alla filigrana. |
|
|  | [setEffects(IPresentationWatermarkEffects value)](#setEffects-com.groupdocs.watermark.options.IPresentationWatermarkEffects-) | Imposta un valore di `[PresentationImageEffects](../../com.groupdocs.watermark.options/presentationimageeffects)` o `[PresentationTextEffects](../../com.groupdocs.watermark.options/presentationtexteffects)` per gli effetti da applicare alla filigrana. |
|
### isLocked() {#isLocked--}
```
public final boolean isLocked()
```


Restituisce un valore che indica se la modifica della forma in PowerPoint è vietata.


**Returns:**
boolean - Se il valore è true, la modifica della forma sarà vietata. Per impostazione predefinita, il valore è false, la forma può essere modificata in PowerPoint.

### setLocked(boolean value) {#setLocked-boolean-}
```
public final void setLocked(boolean value)
```


Imposta un valore che indica se la modifica della forma in PowerPoint è vietata.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | boolean | Se il valore è true, la modifica della forma sarà vietata. Per impostazione predefinita, il valore è false, la forma può essere modificata in PowerPoint. |
|

### getProtectWithUnreadableCharacters() {#getProtectWithUnreadableCharacters--}
```
public final boolean getProtectWithUnreadableCharacters()
```


Restituisce o imposta un valore che indica se i caratteri della filigrana di testo sono mescolati con caratteri illeggibili.

Questa protezione si applica solo quando `#isLocked().isLocked()` restituisce `true`.


**Returns:**
boolean - Un valore che indica se i caratteri della filigrana di testo sono mescolati con caratteri illeggibili.

### setProtectWithUnreadableCharacters(boolean value) {#setProtectWithUnreadableCharacters-boolean-}
```
public final void setProtectWithUnreadableCharacters(boolean value)
```


Restituisce o imposta un valore che indica se i caratteri della filigrana di testo sono mescolati con caratteri illeggibili.

Questa protezione si applica solo quando `#isLocked().isLocked()` restituisce `true`.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | boolean | Un valore che indica se i caratteri della filigrana di testo sono mescolati con caratteri illeggibili. |
|

### getName() {#getName--}
```
public final String getName()
```


Ottiene il nome di una forma.


**Returns:**
java.lang.String - Il nome della forma.

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Imposta il nome di una forma.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | java.lang.String | Il nome della forma. |
|

### getAlternativeText() {#getAlternativeText--}
```
public final String getAlternativeText()
```


Ottiene il testo descrittivo (alternativo) che sarà associato a una forma.


**Returns:**
java.lang.String - Il testo descrittivo (alternativo) che verrà associato a una forma.

### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public final void setAlternativeText(String value)
```


Imposta il testo descrittivo (alternativo) che sarà associato a una forma.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | java.lang.String | Il testo descrittivo (alternativo) che verrà associato a una forma. |
|

### getEffects() {#getEffects--}
```
public final IPresentationWatermarkEffects getEffects()
```


Restituisce un valore di `[PresentationImageEffects](../../com.groupdocs.watermark.options/presentationimageeffects)` o `[PresentationTextEffects](../../com.groupdocs.watermark.options/presentationtexteffects)` per gli effetti da applicare alla filigrana.


**Returns:**
[IPresentationWatermarkEffects](../../com.groupdocs.watermark.options/ipresentationwatermarkeffects) - The value of `[PresentationImageEffects](../../com.groupdocs.watermark.options/presentationimageeffects)` or `[PresentationTextEffects](../../com.groupdocs.watermark.options/presentationtexteffects)` for effects that should be applied to the watermark.

### setEffects(IPresentationWatermarkEffects value) {#setEffects-com.groupdocs.watermark.options.IPresentationWatermarkEffects-}
```
public final void setEffects(IPresentationWatermarkEffects value)
```


Imposta un valore di `[PresentationImageEffects](../../com.groupdocs.watermark.options/presentationimageeffects)` o `[PresentationTextEffects](../../com.groupdocs.watermark.options/presentationtexteffects)` per gli effetti da applicare alla filigrana.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | value | [IPresentationWatermarkEffects](../../com.groupdocs.watermark.options/ipresentationwatermarkeffects) | Il valore di `[PresentationImageEffects](../../com.groupdocs.watermark.options/presentationimageeffects)` o `[PresentationTextEffects](../../com.groupdocs.watermark.options/presentationtexteffects)` per gli effetti che dovrebbero essere applicati alla filigrana. |
|

