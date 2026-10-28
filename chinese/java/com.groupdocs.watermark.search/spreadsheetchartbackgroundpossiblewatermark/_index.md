---
title: "SpreadsheetChartBackgroundPossibleWatermark"
second_title: "GroupDocs.Watermark for Java API Reference"
description: "表示 Excel 图表背景中的可能图像水印。"
type: docs
weight: 61
url: /zh/java/com.groupdocs.watermark.search/spreadsheetchartbackgroundpossiblewatermark/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark), [com.groupdocs.watermark.search.TwoDObjectPossibleWatermark](../../com.groupdocs.watermark.search/twodobjectpossiblewatermark)
```
public class SpreadsheetChartBackgroundPossibleWatermark extends TwoDObjectPossibleWatermark
```

表示 Excel 图表背景中的可能图像水印。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [SpreadsheetChartBackgroundPossibleWatermark(SpreadsheetChart chart)](#SpreadsheetChartBackgroundPossibleWatermark-com.groupdocs.watermark.contents.SpreadsheetChart-) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getParent()](#getParent--) | 获取此 `[SpreadsheetChartBackgroundPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetchartbackgroundpossiblewatermark)` 的父对象。 |
|
|  | [getRotateAngle()](#getRotateAngle--) | 获取此 `[SpreadsheetChartBackgroundPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetchartbackgroundpossiblewatermark)` 的旋转角度（单位：度）。 |
|
|  | [getUnitOfMeasurement()](#getUnitOfMeasurement--) | 获取此 `[SpreadsheetChartBackgroundPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetchartbackgroundpossiblewatermark)` 的 `[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)`。 |
|
| [getImageInternally()](#getImageInternally--) |  |
| [remove()](#remove--) |  |
### SpreadsheetChartBackgroundPossibleWatermark(SpreadsheetChart chart) {#SpreadsheetChartBackgroundPossibleWatermark-com.groupdocs.watermark.contents.SpreadsheetChart-}
```
public SpreadsheetChartBackgroundPossibleWatermark(SpreadsheetChart chart)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| chart | [SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart) |  |

### getParent() {#getParent--}
```
public ContentPart getParent()
```


获取此 `[SpreadsheetChartBackgroundPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetchartbackgroundpossiblewatermark)` 的父对象。


**Returns:**
[ContentPart](../../com.groupdocs.watermark.contents/contentpart) - The parent of this `[SpreadsheetChartBackgroundPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetchartbackgroundpossiblewatermark)`.

### getRotateAngle() {#getRotateAngle--}
```
public double getRotateAngle()
```


获取此 `[SpreadsheetChartBackgroundPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetchartbackgroundpossiblewatermark)` 的旋转角度（单位：度）。


**Returns:**
double - 此类可能的水印的值始终为 0。

### getUnitOfMeasurement() {#getUnitOfMeasurement--}
```
public int getUnitOfMeasurement()
```


获取此 `[SpreadsheetChartBackgroundPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetchartbackgroundpossiblewatermark)` 的 `[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)`。


**Returns:**
int - 此 `[SpreadsheetChartBackgroundPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetchartbackgroundpossiblewatermark)` 的 `[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)`。

### getImageInternally() {#getImageInternally--}
```
public WatermarkableImage getImageInternally()
```




**Returns:**
[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)
### remove() {#remove--}
```
public void remove()
```




