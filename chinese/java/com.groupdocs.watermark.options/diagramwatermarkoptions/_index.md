---
title: "DiagramWatermarkOptions"
second_title: "GroupDocs.Watermark for Java API Reference"
description: "Visio 文档的水印添加选项的基类。"
type: docs
weight: 15
url: /zh/java/com.groupdocs.watermark.options/diagramwatermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions)
```
public abstract class DiagramWatermarkOptions extends WatermarkOptions
```

Visio 文档的水印添加选项的基类。

## 方法

| 方法 | 描述 |
| --- | --- |
|  | [isLocked()](#isLocked--) | 获取一个值，指示在 Visio 中是否禁止编辑形状。 |
|
|  | [setLocked(boolean value)](#setLocked-boolean-) | 设置一个值，指示在 Visio 中是否禁止编辑形状。 |
|
### isLocked() {#isLocked--}
```
public final boolean isLocked()
```


获取一个值，指示在 Visio 中是否禁止编辑形状。


**Returns:**
boolean - 如果该值为 true，形状编辑将被禁止。

<br />

*** ** * ** ***

默认情况下，该值为 false，形状可以在 Visio 中编辑。

<br />


### setLocked(boolean value) {#setLocked-boolean-}
```
public final void setLocked(boolean value)
```


设置一个值，指示在 Visio 中是否禁止编辑形状。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | boolean | 如果该值为 true，形状编辑将被禁止。 |

<br />

*** ** * ** ***

默认情况下，该值为 false，形状可以在 Visio 中编辑。

<br />

|

