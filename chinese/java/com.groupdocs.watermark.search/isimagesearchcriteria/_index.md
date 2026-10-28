---
title: "IsImageSearchCriteria"
second_title: "GroupDocs.Watermark for Java API Reference"
description: "表示仅过滤图像水印的搜索条件。"
type: docs
weight: 34
url: /zh/java/com.groupdocs.watermark.search/isimagesearchcriteria/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)
```
public final class IsImageSearchCriteria extends SearchCriteria
```

表示仅过滤图像水印的搜索条件。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [IsImageSearchCriteria()](#IsImageSearchCriteria--) | 初始化 `[IsImageSearchCriteria](../../com.groupdocs.watermark.search/isimagesearchcriteria)` 类的新实例。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
| [isSatisfiedBy(PossibleWatermark candidate)](#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-) |  |
| [accept(ICriteriaVisitor visitor)](#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-) |  |
### IsImageSearchCriteria() {#IsImageSearchCriteria--}
```
public IsImageSearchCriteria()
```


初始化 `[IsImageSearchCriteria](../../com.groupdocs.watermark.search/isimagesearchcriteria)` 类的新实例。


### isSatisfiedBy(PossibleWatermark candidate) {#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-}
```
public boolean isSatisfiedBy(PossibleWatermark candidate)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| candidate | [PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark) |  |

**Returns:**
boolean
### accept(ICriteriaVisitor visitor) {#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-}
```
public void accept(ICriteriaVisitor visitor)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| visitor | [ICriteriaVisitor](../../com.groupdocs.watermark.internal/icriteriavisitor) |  |

