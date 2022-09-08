---
title: Search
second_title: GroupDocs.Watermark for .NET API Reference
description: Finds possible watermarks according to specified search criteria. The search is conducted in the objects specified in SearchableObjectsgroupdocs.watermark/watermarker/searchableobjects.
type: docs
weight: 20
url: /net/groupdocs.watermark.contents/contentpart/search/
---
## Search(SearchCriteria) {#search_1}

Finds possible watermarks according to specified search criteria. The search is conducted in the objects specified in [`SearchableObjects`](../../../groupdocs.watermark/watermarker/searchableobjects).

```csharp
public PossibleWatermarkCollection Search(SearchCriteria searchCriteria)
```

| Parameter | Type | Description |
| --- | --- | --- |
| searchCriteria | SearchCriteria | The search criteria to use. |

### Return Value

The collection of the possible watermarks.

### See Also

* class [PossibleWatermarkCollection](../../../groupdocs.watermark.search/possiblewatermarkcollection)
* class [SearchCriteria](../../../groupdocs.watermark.search.searchcriteria/searchcriteria)
* class [ContentPart](../../contentpart)
* namespace [GroupDocs.Watermark.Contents](../../contentpart)
* assembly [GroupDocs.Watermark](../../../)

---

## Search() {#search}

Finds all possible watermarks in the content. The search is conducted in the objects specified in [`SearchableObjects`](../../../groupdocs.watermark/watermarker/searchableobjects).

```csharp
public PossibleWatermarkCollection Search()
```

### Return Value

The collection of the possible watermarks.

### See Also

* class [PossibleWatermarkCollection](../../../groupdocs.watermark.search/possiblewatermarkcollection)
* class [ContentPart](../../contentpart)
* namespace [GroupDocs.Watermark.Contents](../../contentpart)
* assembly [GroupDocs.Watermark](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.watermark.dll -->