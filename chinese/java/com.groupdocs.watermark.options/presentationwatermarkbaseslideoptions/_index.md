---
title: "PresentationWatermarkBaseSlideOptions"
second_title: "GroupDocs.Watermark for Java API Reference"
description: "演示文稿文档水印添加选项的基类。"
type: docs
weight: 39
url: /zh/java/com.groupdocs.watermark.options/presentationwatermarkbaseslideoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.PresentationWatermarkOptions](../../com.groupdocs.watermark.options/presentationwatermarkoptions)
```
public abstract class PresentationWatermarkBaseSlideOptions extends PresentationWatermarkOptions
```

演示文稿文档水印添加选项的基类。

**Learn more:**

* [Add watermarks to presentation documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+presentation+documents)

以下示例演示如何向 Power Point 演示文稿的不同服务幻灯片添加水印。
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


## 方法

| 方法 | 描述 |
| --- | --- |
|  | [isLocked()](#isLocked--) | 获取一个值，指示在 PowerPoint 中是否禁止编辑形状。 |
|
|  | [setLocked(boolean value)](#setLocked-boolean-) | 设置一个值，指示在 PowerPoint 中是否禁止编辑形状。 |
|
|  | [getProtectWithUnreadableCharacters()](#getProtectWithUnreadableCharacters--) | 获取或设置一个值，指示文本水印字符是否与不可读字符混合。 |
|
|  | [setProtectWithUnreadableCharacters(boolean value)](#setProtectWithUnreadableCharacters-boolean-) | 获取或设置一个值，指示文本水印字符是否与不可读字符混合。 |
|
|  | [getName()](#getName--) | 获取形状的名称。 |
|
|  | [setName(String value)](#setName-java.lang.String-) | 设置形状的名称。 |
|
|  | [getAlternativeText()](#getAlternativeText--) | 获取将与形状关联的描述性（替代）文本。 |
|
|  | [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | 设置将与形状关联的描述性（替代）文本。 |
|
|  | [getEffects()](#getEffects--) | 获取 `[PresentationImageEffects](../../com.groupdocs.watermark.options/presentationimageeffects)` 或 `[PresentationTextEffects](../../com.groupdocs.watermark.options/presentationtexteffects)` 的值，用于应应用于水印的效果。 |
|
|  | [setEffects(IPresentationWatermarkEffects value)](#setEffects-com.groupdocs.watermark.options.IPresentationWatermarkEffects-) | 设置 `[PresentationImageEffects](../../com.groupdocs.watermark.options/presentationimageeffects)` 或 `[PresentationTextEffects](../../com.groupdocs.watermark.options/presentationtexteffects)` 的值，用于应应用于水印的效果。 |
|
### isLocked() {#isLocked--}
```
public final boolean isLocked()
```


获取一个值，指示在 PowerPoint 中是否禁止编辑形状。


**Returns:**
布尔型 - 如果值为 true，则禁止编辑形状。默认情况下，值为 false，形状可以在 PowerPoint 中编辑。

### setLocked(boolean value) {#setLocked-boolean-}
```
public final void setLocked(boolean value)
```


设置一个值，指示在 PowerPoint 中是否禁止编辑形状。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | boolean | 如果值为 true，则禁止编辑形状。默认情况下，值为 false，形状可以在 PowerPoint 中编辑。 |
|

### getProtectWithUnreadableCharacters() {#getProtectWithUnreadableCharacters--}
```
public final boolean getProtectWithUnreadableCharacters()
```


获取或设置一个值，指示文本水印字符是否与不可读字符混合。

此保护仅在 `#isLocked().isLocked()` 返回 `true` 时适用。


**Returns:**
布尔型 - 一个指示文本水印字符是否与不可读字符混合的值。

### setProtectWithUnreadableCharacters(boolean value) {#setProtectWithUnreadableCharacters-boolean-}
```
public final void setProtectWithUnreadableCharacters(boolean value)
```


获取或设置一个值，指示文本水印字符是否与不可读字符混合。

此保护仅在 `#isLocked().isLocked()` 返回 `true` 时适用。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | boolean | 指示文本水印字符是否与不可读字符混合的值。 |
|

### getName() {#getName--}
```
public final String getName()
```


获取形状的名称。


**Returns:**
java.lang.String - 形状名称。

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


设置形状的名称。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | java.lang.String | 形状名称。 |
|

### getAlternativeText() {#getAlternativeText--}
```
public final String getAlternativeText()
```


获取将与形状关联的描述性（替代）文本。


**Returns:**
java.lang.String - 将与形状关联的描述性（替代）文本。

### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public final void setAlternativeText(String value)
```


设置将与形状关联的描述性（替代）文本。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | java.lang.String | 将与形状关联的描述性（替代）文本。 |
|

### getEffects() {#getEffects--}
```
public final IPresentationWatermarkEffects getEffects()
```


获取 `[PresentationImageEffects](../../com.groupdocs.watermark.options/presentationimageeffects)` 或 `[PresentationTextEffects](../../com.groupdocs.watermark.options/presentationtexteffects)` 的值，用于应应用于水印的效果。


**Returns:**
[IPresentationWatermarkEffects](../../com.groupdocs.watermark.options/ipresentationwatermarkeffects) - The value of `[PresentationImageEffects](../../com.groupdocs.watermark.options/presentationimageeffects)` or `[PresentationTextEffects](../../com.groupdocs.watermark.options/presentationtexteffects)` for effects that should be applied to the watermark.

### setEffects(IPresentationWatermarkEffects value) {#setEffects-com.groupdocs.watermark.options.IPresentationWatermarkEffects-}
```
public final void setEffects(IPresentationWatermarkEffects value)
```


设置 `[PresentationImageEffects](../../com.groupdocs.watermark.options/presentationimageeffects)` 或 `[PresentationTextEffects](../../com.groupdocs.watermark.options/presentationtexteffects)` 的值，用于应应用于水印的效果。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | value | [IPresentationWatermarkEffects](../../com.groupdocs.watermark.options/ipresentationwatermarkeffects) | 用于应应用于水印的效果的 `[PresentationImageEffects](../../com.groupdocs.watermark.options/presentationimageeffects)` 或 `[PresentationTextEffects](../../com.groupdocs.watermark.options/presentationtexteffects)` 的值。 |
|

