---
title: PresentationWatermarkLayoutSlideOptions
second_title: GroupDocs.Watermark for Java API Reference
description: Represents options when adding watermark to a Presentation document layout slide.
type: docs
weight: 40
url: /java/com.groupdocs.watermark.options/presentationwatermarklayoutslideoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.PresentationWatermarkOptions](../../com.groupdocs.watermark.options/presentationwatermarkoptions), [com.groupdocs.watermark.options.PresentationWatermarkBaseSlideOptions](../../com.groupdocs.watermark.options/presentationwatermarkbaseslideoptions)
```
public final class PresentationWatermarkLayoutSlideOptions extends PresentationWatermarkBaseSlideOptions
```

Represents options when adding watermark to a Presentation document layout slide.

**Learn more:**

 *  [Add watermarks to presentation documents][]

See the usage examples in `[PresentationWatermarkBaseSlideOptions](../../com.groupdocs.watermark.options/presentationwatermarkbaseslideoptions)`.


[Add watermarks to presentation documents]: https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+presentation+documents
## Constructors

| Constructor | Description |
| --- | --- |
| [PresentationWatermarkLayoutSlideOptions()](#PresentationWatermarkLayoutSlideOptions--) | Initializes a new instance of the `[PresentationWatermarkOptions](../../com.groupdocs.watermark.options/presentationwatermarkoptions)` class. |
## Methods

| Method | Description |
| --- | --- |
| [getLayoutSlideIndex()](#getLayoutSlideIndex--) | Gets the index of layout slide to add the watermark to. |
| [setLayoutSlideIndex(int value)](#setLayoutSlideIndex-int-) | Sets the index of layout slide to add the watermark to. |
### PresentationWatermarkLayoutSlideOptions() {#PresentationWatermarkLayoutSlideOptions--}
```
public PresentationWatermarkLayoutSlideOptions()
```


Initializes a new instance of the `[PresentationWatermarkOptions](../../com.groupdocs.watermark.options/presentationwatermarkoptions)` class.

### getLayoutSlideIndex() {#getLayoutSlideIndex--}
```
public final int getLayoutSlideIndex()
```


Gets the index of layout slide to add the watermark to.

**Returns:**
int - The index of layout slide to add the watermark to.

--------------------

\-1 means all slides.
### setLayoutSlideIndex(int value) {#setLayoutSlideIndex-int-}
```
public final void setLayoutSlideIndex(int value)
```


Sets the index of layout slide to add the watermark to.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The index of layout slide to add the watermark to.

--------------------

\-1 means all slides. |

