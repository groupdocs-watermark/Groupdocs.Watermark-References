---
title: "PresentationWatermarkBaseSlideOptions"
second_title: "GroupDocs.Watermark für Java API-Referenz"
description: "Basisklasse für Optionen zum Hinzufügen von Wasserzeichen zu einem Präsentationsdokument."
type: docs
weight: 39
url: /de/java/com.groupdocs.watermark.options/presentationwatermarkbaseslideoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.PresentationWatermarkOptions](../../com.groupdocs.watermark.options/presentationwatermarkoptions)
```
public abstract class PresentationWatermarkBaseSlideOptions extends PresentationWatermarkOptions
```

Basisklasse für Optionen zum Hinzufügen von Wasserzeichen zu einem Präsentationsdokument.

**Learn more:**

* [Add watermarks to presentation documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+presentation+documents)

Das folgende Beispiel zeigt, wie man ein Wasserzeichen zu verschiedenen Service‑Folien einer Power Point‑Präsentation hinzufügt.
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


## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [isLocked()](#isLocked--) | Gibt einen Wert zurück, der angibt, ob das Bearbeiten der Form in PowerPoint verboten ist. |
|
|  | [setLocked(boolean value)](#setLocked-boolean-) | Setzt einen Wert, der angibt, ob das Bearbeiten der Form in PowerPoint verboten ist. |
|
|  | [getProtectWithUnreadableCharacters()](#getProtectWithUnreadableCharacters--) | Liest oder setzt einen Wert, der angibt, ob die Zeichen des Textwasserzeichens mit unlesbaren Zeichen gemischt werden. |
|
|  | [setProtectWithUnreadableCharacters(boolean value)](#setProtectWithUnreadableCharacters-boolean-) | Liest oder setzt einen Wert, der angibt, ob die Zeichen des Textwasserzeichens mit unlesbaren Zeichen gemischt werden. |
|
|  | [getName()](#getName--) | Liefert den Namen einer Form. |
|
|  | [setName(String value)](#setName-java.lang.String-) | Setzt den Namen einer Form. |
|
|  | [getAlternativeText()](#getAlternativeText--) | Liefert den beschreibenden (alternativen) Text, der einer Form zugeordnet wird. |
|
|  | [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | Setzt den beschreibenden (alternativen) Text, der einer Form zugeordnet wird. |
|
|  | [getEffects()](#getEffects--) | Gibt einen Wert von `[PresentationImageEffects](../../com.groupdocs.watermark.options/presentationimageeffects)` oder `[PresentationTextEffects](../../com.groupdocs.watermark.options/presentationtexteffects)` zurück, der die Effekte angibt, die auf das Wasserzeichen angewendet werden sollen. |
|
|  | [setEffects(IPresentationWatermarkEffects value)](#setEffects-com.groupdocs.watermark.options.IPresentationWatermarkEffects-) | Setzt einen Wert von `[PresentationImageEffects](../../com.groupdocs.watermark.options/presentationimageeffects)` oder `[PresentationTextEffects](../../com.groupdocs.watermark.options/presentationtexteffects)` fest, der die Effekte angibt, die auf das Wasserzeichen angewendet werden sollen. |
|
### isLocked() {#isLocked--}
```
public final boolean isLocked()
```


Gibt einen Wert zurück, der angibt, ob das Bearbeiten der Form in PowerPoint verboten ist.


**Returns:**
boolesch – Wenn der Wert true ist, ist das Bearbeiten der Form verboten. Standardmäßig ist der Wert false, die Form kann in PowerPoint bearbeitet werden.

### setLocked(boolean value) {#setLocked-boolean-}
```
public final void setLocked(boolean value)
```


Setzt einen Wert, der angibt, ob das Bearbeiten der Form in PowerPoint verboten ist.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | boolean | Wenn der Wert true ist, ist das Bearbeiten der Form verboten. Standardmäßig ist der Wert false, die Form kann in PowerPoint bearbeitet werden. |
|

### getProtectWithUnreadableCharacters() {#getProtectWithUnreadableCharacters--}
```
public final boolean getProtectWithUnreadableCharacters()
```


Liest oder setzt einen Wert, der angibt, ob die Zeichen des Textwasserzeichens mit unlesbaren Zeichen gemischt werden.

Dieser Schutz gilt nur, wenn `#isLocked().isLocked()` `true` zurückgibt.


**Returns:**
boolesch – Ein Wert, der angibt, ob die Zeichen des Textwasserzeichens mit unlesbaren Zeichen gemischt werden.

### setProtectWithUnreadableCharacters(boolean value) {#setProtectWithUnreadableCharacters-boolean-}
```
public final void setProtectWithUnreadableCharacters(boolean value)
```


Liest oder setzt einen Wert, der angibt, ob die Zeichen des Textwasserzeichens mit unlesbaren Zeichen gemischt werden.

Dieser Schutz gilt nur, wenn `#isLocked().isLocked()` `true` zurückgibt.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | boolean | Ein Wert, der angibt, ob die Zeichen des Textwasserzeichens mit unlesbaren Zeichen gemischt sind. |
|

### getName() {#getName--}
```
public final String getName()
```


Liefert den Namen einer Form.


**Returns:**
java.lang.String - Der Name der Form.

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Setzt den Namen einer Form.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | java.lang.String | Der Name der Form. |
|

### getAlternativeText() {#getAlternativeText--}
```
public final String getAlternativeText()
```


Liefert den beschreibenden (alternativen) Text, der einer Form zugeordnet wird.


**Returns:**
java.lang.String - Der beschreibende (alternative) Text, der mit einer Form verknüpft wird.

### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public final void setAlternativeText(String value)
```


Setzt den beschreibenden (alternativen) Text, der einer Form zugeordnet wird.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | java.lang.String | Der beschreibende (alternative) Text, der mit einer Form verknüpft wird. |
|

### getEffects() {#getEffects--}
```
public final IPresentationWatermarkEffects getEffects()
```


Gibt einen Wert von `[PresentationImageEffects](../../com.groupdocs.watermark.options/presentationimageeffects)` oder `[PresentationTextEffects](../../com.groupdocs.watermark.options/presentationtexteffects)` zurück, der die Effekte angibt, die auf das Wasserzeichen angewendet werden sollen.


**Returns:**
[IPresentationWatermarkEffects](../../com.groupdocs.watermark.options/ipresentationwatermarkeffects) - The value of `[PresentationImageEffects](../../com.groupdocs.watermark.options/presentationimageeffects)` or `[PresentationTextEffects](../../com.groupdocs.watermark.options/presentationtexteffects)` for effects that should be applied to the watermark.

### setEffects(IPresentationWatermarkEffects value) {#setEffects-com.groupdocs.watermark.options.IPresentationWatermarkEffects-}
```
public final void setEffects(IPresentationWatermarkEffects value)
```


Setzt einen Wert von `[PresentationImageEffects](../../com.groupdocs.watermark.options/presentationimageeffects)` oder `[PresentationTextEffects](../../com.groupdocs.watermark.options/presentationtexteffects)` fest, der die Effekte angibt, die auf das Wasserzeichen angewendet werden sollen.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | [IPresentationWatermarkEffects](../../com.groupdocs.watermark.options/ipresentationwatermarkeffects) | Der Wert von `[PresentationImageEffects](../../com.groupdocs.watermark.options/presentationimageeffects)` oder `[PresentationTextEffects](../../com.groupdocs.watermark.options/presentationtexteffects)` für Effekte, die auf das Wasserzeichen angewendet werden sollen. |
|

