---
title: "WordProcessingPageSetup"
second_title: "GroupDocs.Watermark for Java API Reference"
description: "表示 Word 文档章节的打印页面属性。"
type: docs
weight: 134
url: /zh/java/com.groupdocs.watermark.contents/wordprocessingpagesetup/
---
**Inheritance:**
java.lang.Object
```
public class WordProcessingPageSetup
```

表示 Word 文档章节的打印页面属性。

## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getWidth()](#getWidth--) | 获取打印页面的宽度（单位：点）。 |
|
|  | [getHeight()](#getHeight--) | 获取打印页面的高度（单位：点）。 |
|
|  | [getLeftMargin()](#getLeftMargin--) | 获取左边距的大小（单位：点）。 |
|
|  | [getTopMargin()](#getTopMargin--) | 获取上边距的大小（单位：点）。 |
|
|  | [getRightMargin()](#getRightMargin--) | 获取右边距的大小（单位：点）。 |
|
|  | [getBottomMargin()](#getBottomMargin--) | 获取下边距的大小（单位：点）。 |
|
|  | [getDifferentFirstPageHeaderFooter()](#getDifferentFirstPageHeaderFooter--) | 获取一个值，指示首页是否使用不同的页眉/页脚。 |
|
|  | [setDifferentFirstPageHeaderFooter(boolean value)](#setDifferentFirstPageHeaderFooter-boolean-) | 设置一个值，指示首页是否使用不同的页眉/页脚。 |
|
|  | [getOddAndEvenPagesHeaderFooter()](#getOddAndEvenPagesHeaderFooter--) | 获取一个值，指示奇数页和偶数页是否使用不同的页眉/页脚 |
页面。
|
|  | [setOddAndEvenPagesHeaderFooter(boolean value)](#setOddAndEvenPagesHeaderFooter-boolean-) | 设置一个值，指示奇数页和偶数页是否使用不同的页眉/页脚 |
页面。
|
### getWidth() {#getWidth--}
```
public final double getWidth()
```


获取打印页面的宽度（单位：点）。


**Returns:**
double - 打印页面的宽度（单位：点）。

### getHeight() {#getHeight--}
```
public final double getHeight()
```


获取打印页面的高度（单位：点）。


**Returns:**
double - 打印页面的高度（单位：点）。

### getLeftMargin() {#getLeftMargin--}
```
public final double getLeftMargin()
```


获取左边距的大小（单位：点）。


**Returns:**
double - 左边距的大小（单位：点）。

### getTopMargin() {#getTopMargin--}
```
public final double getTopMargin()
```


获取上边距的大小（单位：点）。


**Returns:**
double - 顶部边距的大小（单位：点）。

### getRightMargin() {#getRightMargin--}
```
public final double getRightMargin()
```


获取右边距的大小（单位：点）。


**Returns:**
double - 右边距的大小（单位：点）。

### getBottomMargin() {#getBottomMargin--}
```
public final double getBottomMargin()
```


获取下边距的大小（单位：点）。


**Returns:**
double - 底部边距的大小（单位：点）。

### getDifferentFirstPageHeaderFooter() {#getDifferentFirstPageHeaderFooter--}
```
public final boolean getDifferentFirstPageHeaderFooter()
```


获取一个值，指示首页是否使用不同的页眉/页脚。


**Returns:**
布尔型 - 如果首页使用不同的页眉/页脚，则为 True；否则为 false。

### setDifferentFirstPageHeaderFooter(boolean value) {#setDifferentFirstPageHeaderFooter-boolean-}
```
public final void setDifferentFirstPageHeaderFooter(boolean value)
```


设置一个值，指示首页是否使用不同的页眉/页脚。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | boolean | 如果首页使用不同的页眉/页脚，则为 True；否则为 false。 |
|

### getOddAndEvenPagesHeaderFooter() {#getOddAndEvenPagesHeaderFooter--}
```
public final boolean getOddAndEvenPagesHeaderFooter()
```


获取一个值，指示奇数页和偶数页是否使用不同的页眉/页脚
页面。
注意，修改此属性会影响内容中的所有章节。


**Returns:**
布尔型 - 如果奇数页和偶数页使用不同的页眉/页脚，则为 True；否则为 false。

### setOddAndEvenPagesHeaderFooter(boolean value) {#setOddAndEvenPagesHeaderFooter-boolean-}
```
public final void setOddAndEvenPagesHeaderFooter(boolean value)
```


设置一个值，指示奇数页和偶数页是否使用不同的页眉/页脚
页面。
注意，修改此属性会影响内容中的所有章节。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | boolean | 如果奇数页和偶数页使用不同的页眉/页脚，则为 True；否则为 false。 |
|

