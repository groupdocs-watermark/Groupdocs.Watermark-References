---
title: Remove
second_title: .NET API 참조용 GroupDocs.Watermark
description: 문서에서 워터마크를 제거합니다.
type: docs
weight: 90
url: /ko/net/groupdocs.watermark/watermarker/remove/
---
## Remove(PossibleWatermark) {#remove}

문서에서 워터마크를 제거합니다.

```csharp
public void Remove(PossibleWatermark possibleWatermark)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| possibleWatermark | PossibleWatermark | 제거할 워터마크입니다. |

### 비고

워터마크 제거에 대해 자세히 알아보기: [발견된 워터마크 제거](https://docs.groupdocs.com/display/watermarknet/Removing+found+watermarks) .

### 예

지원되는 유형의 document 에서 특정 텍스트나 이미지가 포함된 첫 번째 가능한 워터마크를 찾아 제거합니다.

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\input.doc"))
{
    ImageSearchCriteria imageSearchCriteria = new ImageDctHashSearchCriteria(@"D:\logo.png");
    Regex regex = new Regex(@"^Company\sName$", RegexOptions.IgnoreCase);
    TextSearchCriteria textSearchCriteria = new TextSearchCriteria(regex);
    PossibleWatermarkCollection watermarks = watermarker.Search(textSearchCriteria.Or(imageSearchCriteria));
    if (watermarks.Count > 0)
    {
        watermarker.Remove(watermarks[0]);
    }

    watermarker.Save(@"D:\output.doc");
}
```

### 또한보십시오

* class [PossibleWatermark](../../../groupdocs.watermark.search/possiblewatermark)
* class [Watermarker](../../watermarker)
* 네임스페이스 [GroupDocs.Watermark](../../watermarker)
* 집회 [GroupDocs.Watermark](../../../)

---

## Remove(PossibleWatermarkCollection) {#remove_1}

문서에서 컬렉션의 모든 워터마크를 제거합니다.

```csharp
public void Remove(PossibleWatermarkCollection possibleWatermarks)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| possibleWatermarks | PossibleWatermarkCollection | 제거할 워터마크 컬렉션입니다. |

### 비고

워터마크 제거에 대해 자세히 알아보기 [발견된 워터마크 제거](https://docs.groupdocs.com/display/watermarknet/Removing+found+watermarks) .

### 예

지원되는 모든 유형의 document 에서 특정 텍스트나 이미지가 포함된 가능한 모든 워터마크를 찾아 제거합니다.

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\input.doc"))
{
    ImageSearchCriteria imageSearchCriteria = new ImageDctHashSearchCriteria(@"D:\logo.png");
    Regex regex = new Regex(@"^Company\sName$", RegexOptions.IgnoreCase);
    TextSearchCriteria textSearchCriteria = new TextSearchCriteria(regex);
    PossibleWatermarkCollection watermarks = watermarker.Search(textSearchCriteria.Or(imageSearchCriteria));
    watermarker.Remove(watermarks);
    watermarker.Save(@"D:\output.doc");
}
```

### 또한보십시오

* class [PossibleWatermarkCollection](../../../groupdocs.watermark.search/possiblewatermarkcollection)
* class [Watermarker](../../watermarker)
* 네임스페이스 [GroupDocs.Watermark](../../watermarker)
* 집회 [GroupDocs.Watermark](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->
