---
title: "WordProcessingHeaderFooterCollection"
second_title: "GroupDocs.Watermark for Java API Reference"
description: "表示 Word 文档中页眉和页脚的集合。"
type: docs
weight: 132
url: /zh/java/com.groupdocs.watermark.contents/wordprocessingheaderfootercollection/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase
```
public class WordProcessingHeaderFooterCollection extends ReadOnlyListBase<WordProcessingHeaderFooter>
```

表示 Word 文档中页眉和页脚的集合。

此集合包含 `[WordProcessingHeaderFooter](../../com.groupdocs.watermark.contents/wordprocessingheaderfooter)` 类型的项。

## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getByOfficeHeaderFooterType(int headerFooterType)](#getByOfficeHeaderFooterType-int-) | 获取指定类型的页眉或页脚。 |
|
|  | [linkToPrevious(boolean isLinkToPrevious)](#linkToPrevious-boolean-) | 链接或取消链接所有页眉和页脚到相应的 |
前一节中的页眉和页脚。
|
### getByOfficeHeaderFooterType(int headerFooterType) {#getByOfficeHeaderFooterType-int-}
```
public final WordProcessingHeaderFooter getByOfficeHeaderFooterType(int headerFooterType)
```


获取指定类型的页眉或页脚。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | headerFooterType | int | 一个 `[OfficeHeaderFooterType](../../com.groupdocs.watermark.contents/officeheaderfootertype)` 值，用于指定要获取的页眉/页脚的类型。 |
|

**Returns:**
[WordProcessingHeaderFooter](../../com.groupdocs.watermark.contents/wordprocessingheaderfooter) - The `[WordProcessingHeaderFooter](../../com.groupdocs.watermark.contents/wordprocessingheaderfooter)` of specified type.

### linkToPrevious(boolean isLinkToPrevious) {#linkToPrevious-boolean-}
```
public final void linkToPrevious(boolean isLinkToPrevious)
```


链接或取消链接所有页眉和页脚到相应的
前一节中的页眉和页脚。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | isLinkToPrevious | boolean | 设为 True 可将页眉和页脚链接到前一节；设为 false 可取消链接。 |
|

