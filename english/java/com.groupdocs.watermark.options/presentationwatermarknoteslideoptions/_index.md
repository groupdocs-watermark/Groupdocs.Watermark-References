---
title: PresentationWatermarkNoteSlideOptions
second_title: GroupDocs.Watermark for Java API Reference
description: Represents options when adding watermark to a Presentation document note slide.
type: docs
weight: 44
url: /java/com.groupdocs.watermark.options/presentationwatermarknoteslideoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.PresentationWatermarkOptions](../../com.groupdocs.watermark.options/presentationwatermarkoptions), [com.groupdocs.watermark.options.PresentationWatermarkBaseSlideOptions](../../com.groupdocs.watermark.options/presentationwatermarkbaseslideoptions)
```
public final class PresentationWatermarkNoteSlideOptions extends PresentationWatermarkBaseSlideOptions
```

Represents options when adding watermark to a Presentation document note slide.

**Learn more:**

 *  [Add watermarks to presentation documents][]

See the usage examples in `[PresentationWatermarkBaseSlideOptions](../../com.groupdocs.watermark.options/presentationwatermarkbaseslideoptions)`.


[Add watermarks to presentation documents]: https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+presentation+documents
## Constructors

| Constructor | Description |
| --- | --- |
| [PresentationWatermarkNoteSlideOptions()](#PresentationWatermarkNoteSlideOptions--) | Initializes a new instance of the `[PresentationWatermarkNoteSlideOptions](../../com.groupdocs.watermark.options/presentationwatermarknoteslideoptions)` class. |
## Methods

| Method | Description |
| --- | --- |
| [getSlideIndex()](#getSlideIndex--) | Gets the index of a slide to add the watermark to note slide of it. |
| [setSlideIndex(int value)](#setSlideIndex-int-) | Sets the index of a slide to add the watermark to note slide of it. |
### PresentationWatermarkNoteSlideOptions() {#PresentationWatermarkNoteSlideOptions--}
```
public PresentationWatermarkNoteSlideOptions()
```


Initializes a new instance of the `[PresentationWatermarkNoteSlideOptions](../../com.groupdocs.watermark.options/presentationwatermarknoteslideoptions)` class.

### getSlideIndex() {#getSlideIndex--}
```
public final int getSlideIndex()
```


Gets the index of a slide to add the watermark to note slide of it.

**Returns:**
int - The index of slide to add the watermark to note slide of it.

--------------------

\-1 means all slides.
### setSlideIndex(int value) {#setSlideIndex-int-}
```
public final void setSlideIndex(int value)
```


Sets the index of a slide to add the watermark to note slide of it.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The index of slide to add the watermark to note slide of it.

--------------------

\-1 means all slides. |

