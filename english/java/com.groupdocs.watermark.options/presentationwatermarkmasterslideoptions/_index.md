---
title: PresentationWatermarkMasterSlideOptions
second_title: GroupDocs.Watermark for Java API Reference
description: Represents options when adding watermark to a Presentation document master slide.
type: docs
weight: 43
url: /java/com.groupdocs.watermark.options/presentationwatermarkmasterslideoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.PresentationWatermarkOptions](../../com.groupdocs.watermark.options/presentationwatermarkoptions), [com.groupdocs.watermark.options.PresentationWatermarkBaseSlideOptions](../../com.groupdocs.watermark.options/presentationwatermarkbaseslideoptions)
```
public final class PresentationWatermarkMasterSlideOptions extends PresentationWatermarkBaseSlideOptions
```

Represents options when adding watermark to a Presentation document master slide.

**Learn more:**

 *  [Add watermarks to presentation documents][]

See the usage examples in `[PresentationWatermarkBaseSlideOptions](../../com.groupdocs.watermark.options/presentationwatermarkbaseslideoptions)`.


[Add watermarks to presentation documents]: https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+presentation+documents
## Constructors

| Constructor | Description |
| --- | --- |
| [PresentationWatermarkMasterSlideOptions()](#PresentationWatermarkMasterSlideOptions--) | Initializes a new instance of the `[PresentationWatermarkMasterSlideOptions](../../com.groupdocs.watermark.options/presentationwatermarkmasterslideoptions)` class. |
## Methods

| Method | Description |
| --- | --- |
| [getMasterSlideIndex()](#getMasterSlideIndex--) | Gets the index of master slide to add the watermark to. |
| [setMasterSlideIndex(int value)](#setMasterSlideIndex-int-) | Sets the index of master slide to add the watermark to. |
### PresentationWatermarkMasterSlideOptions() {#PresentationWatermarkMasterSlideOptions--}
```
public PresentationWatermarkMasterSlideOptions()
```


Initializes a new instance of the `[PresentationWatermarkMasterSlideOptions](../../com.groupdocs.watermark.options/presentationwatermarkmasterslideoptions)` class.

### getMasterSlideIndex() {#getMasterSlideIndex--}
```
public final int getMasterSlideIndex()
```


Gets the index of master slide to add the watermark to.

**Returns:**
int - The index of master slide to add the watermark to.

--------------------

\-1 means all slides.
### setMasterSlideIndex(int value) {#setMasterSlideIndex-int-}
```
public final void setMasterSlideIndex(int value)
```


Sets the index of master slide to add the watermark to.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The index of master slide to add the watermark to.

--------------------

\-1 means all slides. |

