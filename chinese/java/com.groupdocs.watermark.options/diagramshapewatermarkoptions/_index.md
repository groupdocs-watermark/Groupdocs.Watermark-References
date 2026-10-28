---
title: "DiagramShapeWatermarkOptions"
second_title: "GroupDocs.Watermark for Java API Reference"
description: "表示在 Visio 文档中添加形状水印时的水印添加选项。"
type: docs
weight: 14
url: /zh/java/com.groupdocs.watermark.options/diagramshapewatermarkoptions/
---
**Inheritance:**
java.lang.Object，[com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions)，[com.groupdocs.watermark.options.DiagramWatermarkOptions](../../com.groupdocs.watermark.options/diagramwatermarkoptions)
```
public final class DiagramShapeWatermarkOptions extends DiagramWatermarkOptions
```

表示在 Visio 文档中添加形状水印时的水印添加选项。

**Learn more:**

* [Add watermarks to diagram documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+diagram+documents)

以下示例演示如何向 Visio 文档的所有页面添加受保护的水印。
>
> ````
> ```
>
>    DiagramLoadOptions loadOptions = new DiagramLoadOptions();
>    Watermarker watermarker = new Watermarker("D:\\test.vsdx", loadOptions);
>
>    TextWatermark watermark = new TextWatermark("watermark test", new Font("Arial", 42));
>
>    DiagramShapeWatermarkOptions options = new DiagramShapeWatermarkOptions();
>    options.setLocked(true);
>    options.setPlacementType(DiagramWatermarkPlacementType.AllPages);
>
>    watermarker.add(watermark, options);
>    watermarker.save("D:\\watermarked_test.vsdx");
>    watermarker.close();
>  
> ```
> ````


## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [DiagramShapeWatermarkOptions()](#DiagramShapeWatermarkOptions--) | 初始化 `[DiagramShapeWatermarkOptions](../../com.groupdocs.watermark.options/diagramshapewatermarkoptions)` 类的新实例。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getPlacementType()](#getPlacementType--) | 获取指定应在何页添加水印的值。 |
|
|  | [setPlacementType(int value)](#setPlacementType-int-) | 获取或设置指定应在何页添加水印的值。 |
|
### DiagramShapeWatermarkOptions() {#DiagramShapeWatermarkOptions--}
```
public DiagramShapeWatermarkOptions()
```


初始化 `[DiagramShapeWatermarkOptions](../../com.groupdocs.watermark.options/diagramshapewatermarkoptions)` 类的新实例。


### getPlacementType() {#getPlacementType--}
```
public final int getPlacementType()
```


获取指定应在何页添加水印的值。


**Returns:**
int - `[DiagramWatermarkPlacementType](../../com.groupdocs.watermark.contents/diagramwatermarkplacementtype)`，指定应在何页添加水印。

### setPlacementType(int value) {#setPlacementType-int-}
```
public final void setPlacementType(int value)
```


获取或设置指定应在何页添加水印的值。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | value | int | 该 `[DiagramWatermarkPlacementType](../../com.groupdocs.watermark.contents/diagramwatermarkplacementtype)`，指定应在何页添加水印。 |
|

