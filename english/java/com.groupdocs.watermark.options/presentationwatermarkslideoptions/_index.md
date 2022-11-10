---
title: PresentationWatermarkSlideOptions
second_title: GroupDocs.Watermark for Java API Reference
description: Represents options when adding watermark to a Presentation document slide.
type: docs
weight: 46
url: /java/com.groupdocs.watermark.options/presentationwatermarkslideoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.PresentationWatermarkOptions](../../com.groupdocs.watermark.options/presentationwatermarkoptions), [com.groupdocs.watermark.options.PresentationWatermarkBaseSlideOptions](../../com.groupdocs.watermark.options/presentationwatermarkbaseslideoptions)
```
public final class PresentationWatermarkSlideOptions extends PresentationWatermarkBaseSlideOptions
```

Represents options when adding watermark to a Presentation document slide.

**Learn more:**

 *  [Add watermarks to presentation documents][]

The following example demonstrates how to add a watermark to a particular slide of a Power Point presentation.

> ```
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
> ```


[Add watermarks to presentation documents]: https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+presentation+documents
## Constructors

| Constructor | Description |
| --- | --- |
| [PresentationWatermarkSlideOptions()](#PresentationWatermarkSlideOptions--) | Initializes a new instance of the `[PresentationWatermarkSlideOptions](../../com.groupdocs.watermark.options/presentationwatermarkslideoptions)` class. |
## Methods

| Method | Description |
| --- | --- |
| [getSlideIndex()](#getSlideIndex--) | Gets the index of slide to add the watermark to. |
| [setSlideIndex(int value)](#setSlideIndex-int-) | Sets the index of slide to add the watermark to. |
### PresentationWatermarkSlideOptions() {#PresentationWatermarkSlideOptions--}
```
public PresentationWatermarkSlideOptions()
```


Initializes a new instance of the `[PresentationWatermarkSlideOptions](../../com.groupdocs.watermark.options/presentationwatermarkslideoptions)` class.

### getSlideIndex() {#getSlideIndex--}
```
public final int getSlideIndex()
```


Gets the index of slide to add the watermark to.

**Returns:**
int - The index of slide to add the watermark to.

--------------------

\-1 means all slides.
### setSlideIndex(int value) {#setSlideIndex-int-}
```
public final void setSlideIndex(int value)
```


Sets the index of slide to add the watermark to.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The index of slide to add the watermark to.

--------------------

\-1 means all slides. |

