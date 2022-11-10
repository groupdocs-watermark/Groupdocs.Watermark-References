---
title: PresentationWatermarkBaseSlideOptions
second_title: GroupDocs.Watermark for Java API Reference
description: Base class for watermark adding options to a Presentation document.
type: docs
weight: 39
url: /java/com.groupdocs.watermark.options/presentationwatermarkbaseslideoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.PresentationWatermarkOptions](../../com.groupdocs.watermark.options/presentationwatermarkoptions)
```
public abstract class PresentationWatermarkBaseSlideOptions extends PresentationWatermarkOptions
```

Base class for watermark adding options to a Presentation document.

**Learn more:**

 *  [Add watermarks to presentation documents][]

The following example demonstrates how to add a watermark to different service slides of a Power Point presentation.

> ```
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
> ```


[Add watermarks to presentation documents]: https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+presentation+documents
## Methods

| Method | Description |
| --- | --- |
| [isLocked()](#isLocked--) | Gets a value indicating whether an editing of the shape in PowerPoint is forbidden. |
| [setLocked(boolean value)](#setLocked-boolean-) | Sets a value indicating whether an editing of the shape in PowerPoint is forbidden. |
| [getProtectWithUnreadableCharacters()](#getProtectWithUnreadableCharacters--) | Gets or sets a value indicating whether the text watermark characters are mixed with unreadable characters. |
| [setProtectWithUnreadableCharacters(boolean value)](#setProtectWithUnreadableCharacters-boolean-) | Gets or sets a value indicating whether the text watermark characters are mixed with unreadable characters. |
| [getName()](#getName--) | Gets the name a shape. |
| [setName(String value)](#setName-java.lang.String-) | Sets the name a shape. |
| [getAlternativeText()](#getAlternativeText--) | Gets the descriptive (alternative) text that will be associated with a shape. |
| [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | Sets the descriptive (alternative) text that will be associated with a shape. |
| [getEffects()](#getEffects--) | Gets a value of `[PresentationImageEffects](../../com.groupdocs.watermark.options/presentationimageeffects)` or `[PresentationTextEffects](../../com.groupdocs.watermark.options/presentationtexteffects)` for effects that should be applied to the watermark. |
| [setEffects(IPresentationWatermarkEffects value)](#setEffects-com.groupdocs.watermark.options.IPresentationWatermarkEffects-) | Sets a value of `[PresentationImageEffects](../../com.groupdocs.watermark.options/presentationimageeffects)` or `[PresentationTextEffects](../../com.groupdocs.watermark.options/presentationtexteffects)` for effects that should be applied to the watermark. |
### isLocked() {#isLocked--}
```
public final boolean isLocked()
```


Gets a value indicating whether an editing of the shape in PowerPoint is forbidden.

**Returns:**
boolean - If the value is true, shape editing will be forbidden. By default, the value is false, the shape can be edited in PowerPoint.
### setLocked(boolean value) {#setLocked-boolean-}
```
public final void setLocked(boolean value)
```


Sets a value indicating whether an editing of the shape in PowerPoint is forbidden.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | If the value is true, shape editing will be forbidden. By default, the value is false, the shape can be edited in PowerPoint. |

### getProtectWithUnreadableCharacters() {#getProtectWithUnreadableCharacters--}
```
public final boolean getProtectWithUnreadableCharacters()
```


Gets or sets a value indicating whether the text watermark characters are mixed with unreadable characters.

This protection applies only when `#isLocked().isLocked()` returns `true`.

**Returns:**
boolean - A value indicating whether the text watermark characters are mixed with unreadable characters.
### setProtectWithUnreadableCharacters(boolean value) {#setProtectWithUnreadableCharacters-boolean-}
```
public final void setProtectWithUnreadableCharacters(boolean value)
```


Gets or sets a value indicating whether the text watermark characters are mixed with unreadable characters.

This protection applies only when `#isLocked().isLocked()` returns `true`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | A value indicating whether the text watermark characters are mixed with unreadable characters. |

### getName() {#getName--}
```
public final String getName()
```


Gets the name a shape.

**Returns:**
java.lang.String - The shape name.
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Sets the name a shape.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The shape name. |

### getAlternativeText() {#getAlternativeText--}
```
public final String getAlternativeText()
```


Gets the descriptive (alternative) text that will be associated with a shape.

**Returns:**
java.lang.String - The descriptive (alternative) text that will be associated with a shape.
### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public final void setAlternativeText(String value)
```


Sets the descriptive (alternative) text that will be associated with a shape.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The descriptive (alternative) text that will be associated with a shape. |

### getEffects() {#getEffects--}
```
public final IPresentationWatermarkEffects getEffects()
```


Gets a value of `[PresentationImageEffects](../../com.groupdocs.watermark.options/presentationimageeffects)` or `[PresentationTextEffects](../../com.groupdocs.watermark.options/presentationtexteffects)` for effects that should be applied to the watermark.

**Returns:**
[IPresentationWatermarkEffects](../../com.groupdocs.watermark.options/ipresentationwatermarkeffects) - The value of `[PresentationImageEffects](../../com.groupdocs.watermark.options/presentationimageeffects)` or `[PresentationTextEffects](../../com.groupdocs.watermark.options/presentationtexteffects)` for effects that should be applied to the watermark.
### setEffects(IPresentationWatermarkEffects value) {#setEffects-com.groupdocs.watermark.options.IPresentationWatermarkEffects-}
```
public final void setEffects(IPresentationWatermarkEffects value)
```


Sets a value of `[PresentationImageEffects](../../com.groupdocs.watermark.options/presentationimageeffects)` or `[PresentationTextEffects](../../com.groupdocs.watermark.options/presentationtexteffects)` for effects that should be applied to the watermark.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IPresentationWatermarkEffects](../../com.groupdocs.watermark.options/ipresentationwatermarkeffects) | The value of `[PresentationImageEffects](../../com.groupdocs.watermark.options/presentationimageeffects)` or `[PresentationTextEffects](../../com.groupdocs.watermark.options/presentationtexteffects)` for effects that should be applied to the watermark. |

