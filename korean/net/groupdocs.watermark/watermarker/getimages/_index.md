---
title: GetImages
second_title: .NET API 참조용 GroupDocs.Watermark
description: 지정된 검색 기준에 따라 이미지를 찾습니다.
type: docs
weight: 80
url: /ko/net/groupdocs.watermark/watermarker/getimages/
---
## GetImages(ImageSearchCriteria) {#getimages_1}

지정된 검색 기준에 따라 이미지를 찾습니다.

```csharp
public WatermarkableImageCollection GetImages(ImageSearchCriteria searchCriteria)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| searchCriteria | ImageSearchCriteria | 사용할 검색 기준입니다. |

### 반환 값

발견된 이미지 모음입니다.

### 비고

검색은 다음에 지정된 개체에서 수행됩니다.[`SearchableObjects`](../searchableobjects).

watermarks 검색에 대해 자세히 알아보기[워터마크 검색](https://docs.groupdocs.com/display/watermarknet/Searching+watermarks).

### 예

지원되는 모든 유형의 문서에서 참조와 유사한 모든 이미지를 제거합니다.

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\input.doc"))
{
    ImageThumbnailSearchCriteria criteria = new ImageThumbnailSearchCriteria("reference.png");
    WatermarkableImageCollection images = watermarker.GetImages(criteria);
    images.Clear();
    watermarker.Save(@"D:\output.doc");
}
```

### 또한보십시오

* class [WatermarkableImageCollection](../../../groupdocs.watermark.contents.image/watermarkableimagecollection)
* class [ImageSearchCriteria](../../../groupdocs.watermark.search.searchcriteria/imagesearchcriteria)
* class [Watermarker](../../watermarker)
* 네임스페이스 [GroupDocs.Watermark](../../watermarker)
* 집회 [GroupDocs.Watermark](../../../)

---

## GetImages() {#getimages}

문서의 모든 이미지를 찾습니다.

```csharp
public WatermarkableImageCollection GetImages()
```

### 반환 값

발견된 이미지 모음입니다.

### 비고

검색은 다음에 지정된 개체에서 수행됩니다.[`SearchableObjects`](../searchableobjects).

watermarks 검색에 대해 자세히 알아보기[워터마크 검색](https://docs.groupdocs.com/display/watermarknet/Searching+watermarks).

### 예

지원되는 모든 유형의 문서에 있는 모든 이미지에 워터마크를 추가합니다.

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\input.doc"))
{
    // 텍스트 또는 이미지 워터마크를 초기화합니다.
    TextWatermark watermark = new TextWatermark("DRAFT", new Font("Arial", 19));

    // 문서의 모든 이미지를 찾습니다.
    WatermarkableImageCollection images = watermarker.GetImages();

    // 워터 마크를 추가.
    foreach (WatermarkableImage watermarkableImage in images)
    {
        watermarkableImage.AddWatermark(watermark);
    }

    // 변경 사항을 저장하다.
    watermarker.Save(@"D:\output.doc");
}
```

### 또한보십시오

* class [WatermarkableImageCollection](../../../groupdocs.watermark.contents.image/watermarkableimagecollection)
* class [Watermarker](../../watermarker)
* 네임스페이스 [GroupDocs.Watermark](../../watermarker)
* 집회 [GroupDocs.Watermark](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->