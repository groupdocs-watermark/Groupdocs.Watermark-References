---
title: SpreadsheetHeaderFooterCollection
second_title: GroupDocs.Watermark for Java API Reference
description: Represents a collection of headers and footers in an Excel document.
type: docs
weight: 110
url: /java/com.groupdocs.watermark.contents/spreadsheetheaderfootercollection/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase
```
public class SpreadsheetHeaderFooterCollection extends ReadOnlyListBase<SpreadsheetHeaderFooter>
```

Represents a collection of headers and footers in an Excel document.

This collection contains the items of `[SpreadsheetHeaderFooter](../../com.groupdocs.watermark.contents/spreadsheetheaderfooter)` type.
## Constructors

| Constructor | Description |
| --- | --- |
| [SpreadsheetHeaderFooterCollection(SpreadsheetWorksheet worksheet)](#SpreadsheetHeaderFooterCollection-com.groupdocs.watermark.contents.SpreadsheetWorksheet-) |  |
## Methods

| Method | Description |
| --- | --- |
| [getByOfficeHeaderFooterType(int headerFooterType)](#getByOfficeHeaderFooterType-int-) | Gets the header or footer of specified type. |
### SpreadsheetHeaderFooterCollection(SpreadsheetWorksheet worksheet) {#SpreadsheetHeaderFooterCollection-com.groupdocs.watermark.contents.SpreadsheetWorksheet-}
```
public SpreadsheetHeaderFooterCollection(SpreadsheetWorksheet worksheet)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| worksheet | [SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet) |  |

### getByOfficeHeaderFooterType(int headerFooterType) {#getByOfficeHeaderFooterType-int-}
```
public final SpreadsheetHeaderFooter getByOfficeHeaderFooterType(int headerFooterType)
```


Gets the header or footer of specified type.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| headerFooterType | int | A `[OfficeHeaderFooterType](../../com.groupdocs.watermark.contents/officeheaderfootertype)` value that specifies the type of the header/footer to get. |

**Returns:**
[SpreadsheetHeaderFooter](../../com.groupdocs.watermark.contents/spreadsheetheaderfooter) - The `[SpreadsheetHeaderFooter](../../com.groupdocs.watermark.contents/spreadsheetheaderfooter)` of specified type.
