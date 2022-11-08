---
title: WordProcessingHeaderFooterCollection
second_title: GroupDocs.Watermark for Java API Reference
description: Represents a collection of headers and footers in a Word document.
type: docs
weight: 132
url: /java/com.groupdocs.watermark.contents/wordprocessingheaderfootercollection/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase
```
public class WordProcessingHeaderFooterCollection extends ReadOnlyListBase<WordProcessingHeaderFooter>
```

Represents a collection of headers and footers in a Word document.

This collection contains the items of `[WordProcessingHeaderFooter](../../com.groupdocs.watermark.contents/wordprocessingheaderfooter)` type.
## Methods

| Method | Description |
| --- | --- |
| [getByOfficeHeaderFooterType(int headerFooterType)](#getByOfficeHeaderFooterType-int-) | Gets the header or footer of specified type. |
| [linkToPrevious(boolean isLinkToPrevious)](#linkToPrevious-boolean-) | Links or unlinks all headers and footers to the corresponding headers and footers in the previous section. |
### getByOfficeHeaderFooterType(int headerFooterType) {#getByOfficeHeaderFooterType-int-}
```
public final WordProcessingHeaderFooter getByOfficeHeaderFooterType(int headerFooterType)
```


Gets the header or footer of specified type.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| headerFooterType | int | A `[OfficeHeaderFooterType](../../com.groupdocs.watermark.contents/officeheaderfootertype)` value that specifies the type of the header/footer to get. |

**Returns:**
[WordProcessingHeaderFooter](../../com.groupdocs.watermark.contents/wordprocessingheaderfooter) - The `[WordProcessingHeaderFooter](../../com.groupdocs.watermark.contents/wordprocessingheaderfooter)` of specified type.
### linkToPrevious(boolean isLinkToPrevious) {#linkToPrevious-boolean-}
```
public final void linkToPrevious(boolean isLinkToPrevious)
```


Links or unlinks all headers and footers to the corresponding headers and footers in the previous section.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| isLinkToPrevious | boolean | True to link the headers and footers to the previous section; false to unlink them. |

