---
title: WordProcessingHeaderFooter
second_title: .NET API 참조용 GroupDocs.Watermark
description: Word 문서의 머리글/바닥글을 나타냅니다.
type: docs
weight: 1300
url: /ko/net/groupdocs.watermark.contents.wordprocessing/wordprocessingheaderfooter/
---
## WordProcessingHeaderFooter class

Word 문서의 머리글/바닥글을 나타냅니다.

```csharp
public class WordProcessingHeaderFooter : ContentPart
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [HeaderFooterType](../../groupdocs.watermark.contents.wordprocessing/wordprocessingheaderfooter/headerfootertype) { get; } | 이 유형을 가져옵니다.[`WordProcessingHeaderFooter`](../wordprocessingheaderfooter) . |
| [IsLinkedToPrevious](../../groupdocs.watermark.contents.wordprocessing/wordprocessingheaderfooter/islinkedtoprevious) { get; set; } | 이 머리글/바닥글이 이전 섹션의 해당 머리글/바닥글 에 연결되어 있는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [Section](../../groupdocs.watermark.contents.wordprocessing/wordprocessingheaderfooter/section) { get; } | 이 항목의 상위 섹션을 가져옵니다.[`WordProcessingHeaderFooter`](../wordprocessingheaderfooter) . |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)() | 콘텐츠의 모든 이미지를 찾습니다. 에 지정된 개체에서 검색이 수행됩니다.[`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) . |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)(ImageSearchCriteria) | 지정된 검색 기준에 따라 이미지를 찾습니다. 지정된 개체에서 검색이 수행됩니다.[`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) . |
| [Search](../../groupdocs.watermark.contents/contentpart/search)() | 콘텐츠에서 가능한 모든 워터마크를 찾습니다. 검색은 다음에 지정된 개체에서 수행됩니다.[`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) . |
| [Search](../../groupdocs.watermark.contents/contentpart/search)(SearchCriteria) | 지정된 검색 기준에 따라 가능한 워터마크를 찾습니다. 지정된 개체에서 검색이 수행됩니다.[`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) . |

### 또한보십시오

* class [ContentPart](../../groupdocs.watermark.contents/contentpart)
* 네임스페이스 [GroupDocs.Watermark.Contents.WordProcessing](../../groupdocs.watermark.contents.wordprocessing)
* 집회 [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->