---
title: WordProcessingTextEffects
second_title: GroupDocs.Watermark for Java API Reference
description: Represents effects that can be applied to a text watermark for a Word document.
type: docs
weight: 72
url: /java/com.groupdocs.watermark.options/wordprocessingtexteffects/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.OfficeTextEffects](../../com.groupdocs.watermark.contents/officetexteffects)

**All Implemented Interfaces:**
[com.groupdocs.watermark.options.IWordProcessingWatermarkEffects](../../com.groupdocs.watermark.options/iwordprocessingwatermarkeffects)
```
public final class WordProcessingTextEffects extends OfficeTextEffects implements IWordProcessingWatermarkEffects
```

Represents effects that can be applied to a text watermark for a Word document.
## Constructors

| Constructor | Description |
| --- | --- |
| [WordProcessingTextEffects()](#WordProcessingTextEffects--) | Initializes a new instance of the `[WordProcessingTextEffects](../../com.groupdocs.watermark.options/wordprocessingtexteffects)` class. |
## Methods

| Method | Description |
| --- | --- |
| [getFlipOrientation()](#getFlipOrientation--) | Gets the orientation of a shape. |
| [setFlipOrientation(int value)](#setFlipOrientation-int-) | Sets the orientation of a shape. |
### WordProcessingTextEffects() {#WordProcessingTextEffects--}
```
public WordProcessingTextEffects()
```


Initializes a new instance of the `[WordProcessingTextEffects](../../com.groupdocs.watermark.options/wordprocessingtexteffects)` class.

### getFlipOrientation() {#getFlipOrientation--}
```
public final int getFlipOrientation()
```


Gets the orientation of a shape.

The default value is `[WordProcessingFlipOrientation.None](../../com.groupdocs.watermark.options/wordprocessingfliporientation#None)`.

**Returns:**
int - The orientation `[WordProcessingFlipOrientation](../../com.groupdocs.watermark.options/wordprocessingfliporientation)` of a shape.
### setFlipOrientation(int value) {#setFlipOrientation-int-}
```
public final void setFlipOrientation(int value)
```


Sets the orientation of a shape.

The default value is `[WordProcessingFlipOrientation.None](../../com.groupdocs.watermark.options/wordprocessingfliporientation#None)`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The orientation `[WordProcessingFlipOrientation](../../com.groupdocs.watermark.options/wordprocessingfliporientation)` of a shape. |

