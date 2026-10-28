---
title: "WordProcessingTextEffects"
second_title: "GroupDocs.Watermark for Java API Reference"
description: "表示可应用于 Word 文档中文本水印的效果。"
type: docs
weight: 72
url: /zh/java/com.groupdocs.watermark.options/wordprocessingtexteffects/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.OfficeTextEffects](../../com.groupdocs.watermark.contents/officetexteffects)

**All Implemented Interfaces:**
[com.groupdocs.watermark.options.IWordProcessingWatermarkEffects](../../com.groupdocs.watermark.options/iwordprocessingwatermarkeffects)
```
public final class WordProcessingTextEffects extends OfficeTextEffects implements IWordProcessingWatermarkEffects
```

表示可应用于 Word 文档中文本水印的效果。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [WordProcessingTextEffects()](#WordProcessingTextEffects--) | 初始化一个 `[WordProcessingTextEffects](../../com.groupdocs.watermark.options/wordprocessingtexteffects)` 类的新实例。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getFlipOrientation()](#getFlipOrientation--) | 获取形状的方向。 |
|
|  | [setFlipOrientation(int value)](#setFlipOrientation-int-) | 设置形状的方向。 |
|
### WordProcessingTextEffects() {#WordProcessingTextEffects--}
```
public WordProcessingTextEffects()
```


初始化一个 `[WordProcessingTextEffects](../../com.groupdocs.watermark.options/wordprocessingtexteffects)` 类的新实例。


### getFlipOrientation() {#getFlipOrientation--}
```
public final int getFlipOrientation()
```


获取形状的方向。

默认值是 `[WordProcessingFlipOrientation.None](../../com.groupdocs.watermark.options/wordprocessingfliporientation#None)`。


**Returns:**
int - 形状的方向 `[WordProcessingFlipOrientation](../../com.groupdocs.watermark.options/wordprocessingfliporientation)`。

### setFlipOrientation(int value) {#setFlipOrientation-int-}
```
public final void setFlipOrientation(int value)
```


设置形状的方向。

默认值是 `[WordProcessingFlipOrientation.None](../../com.groupdocs.watermark.options/wordprocessingfliporientation#None)`。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | value | int | 形状的方向 `[WordProcessingFlipOrientation](../../com.groupdocs.watermark.options/wordprocessingfliporientation)`。 |
|

