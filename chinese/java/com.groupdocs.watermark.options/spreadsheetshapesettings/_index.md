---
title: "SpreadsheetShapeSettings"
second_title: "GroupDocs.Watermark for Java API Reference"
description: "表示可应用于 Excel 文档形状水印的设置。"
type: docs
weight: 54
url: /zh/java/com.groupdocs.watermark.options/spreadsheetshapesettings/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.OfficeShapeSettings](../../com.groupdocs.watermark.contents/officeshapesettings)
```
public final class SpreadsheetShapeSettings extends OfficeShapeSettings
```

表示可应用于 Excel 文档形状水印的设置。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [SpreadsheetShapeSettings()](#SpreadsheetShapeSettings--) | 初始化 `[SpreadsheetShapeSettings](../../com.groupdocs.watermark.options/spreadsheetshapesettings)` 类的新实例。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [isLocked()](#isLocked--) | 获取指示在 Excel 中是否禁止编辑形状的值。 |
|
|  | [setLocked(boolean value)](#setLocked-boolean-) | 设置指示在 Excel 中是否禁止编辑形状的值。 |
|
### SpreadsheetShapeSettings() {#SpreadsheetShapeSettings--}
```
public SpreadsheetShapeSettings()
```


初始化 `[SpreadsheetShapeSettings](../../com.groupdocs.watermark.options/spreadsheetshapesettings)` 类的新实例。


### isLocked() {#isLocked--}
```
public final boolean isLocked()
```


获取指示在 Excel 中是否禁止编辑形状的值。


**Returns:**
boolean - 如果该值为 true，则禁止编辑形状。默认情况下，该值为 false，形状可以在 Excel 中编辑。

### setLocked(boolean value) {#setLocked-boolean-}
```
public final void setLocked(boolean value)
```


设置指示在 Excel 中是否禁止编辑形状的值。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | boolean | 如果该值为 true，则禁止编辑形状。默认情况下，该值为 false，形状可以在 Excel 中编辑。 |
|

