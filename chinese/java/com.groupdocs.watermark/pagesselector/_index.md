---
title: "PagesSelector"
second_title: "GroupDocs.Watermark for Java API Reference"
description: 
type: docs
weight: 10
url: /zh/java/com.groupdocs.watermark/pagesselector/
---
**Inheritance:**
java.lang.Object
```
public class PagesSelector
```

<br />


## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PagesSelector()](#PagesSelector--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getPages(boolean allPages, PagesSetup pagesSetup, int totalPages, System.Nullable<Integer> pageIndex)](#getPages-boolean-com.groupdocs.watermark.PagesSetup-int-com.aspose.ms.System.Nullable-java.lang.Integer--) | 获取基于指定设置的页面列表。 |
|
|  | [getPages(boolean allPages, PagesSetup pagesSetup, int totalPages, int[] pageNumbers, boolean fromOne)](#getPages-boolean-com.groupdocs.watermark.PagesSetup-int-int---boolean-) | 获取基于指定条件的已选页面列表。 |
|
### PagesSelector() {#PagesSelector--}
```
public PagesSelector()
```


### getPages(boolean allPages, PagesSetup pagesSetup, int totalPages, System.Nullable<Integer> pageIndex) {#getPages-boolean-com.groupdocs.watermark.PagesSetup-int-com.aspose.ms.System.Nullable-java.lang.Integer--}
```
public static System.Collections.Generic.List<Integer> getPages(boolean allPages, PagesSetup pagesSetup, int totalPages, System.Nullable<Integer> pageIndex)
```


获取基于指定设置的页面列表。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | allPages | boolean | 是否包含所有页面。 |
|
|  | pagesSetup | [PagesSetup](../../com.groupdocs.watermark/pagessetup) | 页面设置配置。 |
|
|  | totalPages | int | 页面的总数。 |
|
|  | pageIndex | com.aspose.ms.System.Nullable<java.lang.Integer> | 特定页面索引（从 0 开始）。 |
|

**Returns:**
com.aspose.ms.System.Collections.Generic.List<java.lang.Integer> - 基于指定设置的页面列表。

### getPages(boolean allPages, PagesSetup pagesSetup, int totalPages, int[] pageNumbers, boolean fromOne) {#getPages-boolean-com.groupdocs.watermark.PagesSetup-int-int---boolean-}
```
public static System.Collections.Generic.List<Integer> getPages(boolean allPages, PagesSetup pagesSetup, int totalPages, int[] pageNumbers, boolean fromOne)
```


获取基于指定条件的已选页面列表。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | allPages | boolean | 指示是否包含所有页面的标志。 |
|
|  | pagesSetup | [PagesSetup](../../com.groupdocs.watermark/pagessetup) | 页面的设置配置。 |
|
|  | totalPages | int | 文档中页面的总数。 |
|
|  | pageNumbers | int[] | 要包含的特定页面编号数组。 |
|
| fromOne | boolean |  |

**Returns:**
com.aspose.ms.System.Collections.Generic.List<java.lang.Integer> - 已排序且唯一的已选页面编号列表。

