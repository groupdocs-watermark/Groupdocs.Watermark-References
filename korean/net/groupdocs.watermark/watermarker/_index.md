---
title: Watermarker
second_title: .NET API 참조용 GroupDocs.Watermark
description: 문서에서 워터마크 관리를 위한 클래스를 나타냅니다.
type: docs
weight: 3060
url: /ko/net/groupdocs.watermark/watermarker/
---
## Watermarker class

문서에서 워터마크 관리를 위한 클래스를 나타냅니다.

```csharp
public class Watermarker : IDisposable
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [Watermarker](watermarker#constructor)(Stream) | 의 새 인스턴스를 초기화합니다.[`Watermarker`](../watermarker) 지정된 stream. 클래스 |
| [Watermarker](watermarker#constructor_4)(string) | 의 새 인스턴스를 초기화합니다.[`Watermarker`](../watermarker) 지정된 문서 경로가 있는 클래스. |
| [Watermarker](watermarker#constructor_1)(Stream, LoadOptions) | 의 새 인스턴스를 초기화합니다.[`Watermarker`](../watermarker) 지정된 stream 및 로드 옵션이 있는 클래스. |
| [Watermarker](watermarker#constructor_3)(Stream, WatermarkerSettings) | 의 새 인스턴스를 초기화합니다.[`Watermarker`](../watermarker) stream 및 settings. 가 지정된 클래스 |
| [Watermarker](watermarker#constructor_5)(string, LoadOptions) | 의 새 인스턴스를 초기화합니다.[`Watermarker`](../watermarker)지정된 문서 경로 및 로드 옵션이 있는 클래스. |
| [Watermarker](watermarker#constructor_7)(string, WatermarkerSettings) | 의 새 인스턴스를 초기화합니다.[`Watermarker`](../watermarker) 지정된 문서 경로 및 설정이 있는 클래스. |
| [Watermarker](watermarker#constructor_2)(Stream, LoadOptions, WatermarkerSettings) | 의 새 인스턴스를 초기화합니다.[`Watermarker`](../watermarker) 지정된 스트림이 있는 클래스, 로드 옵션 및 설정. |
| [Watermarker](watermarker#constructor_6)(string, LoadOptions, WatermarkerSettings) | 의 새 인스턴스를 초기화합니다.[`Watermarker`](../watermarker) 지정된 문서 경로, 로드 옵션 및 설정이 있는 클래스. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [SearchableObjects](../../groupdocs.watermark/watermarker/searchableobjects) { get; set; } | 워터마크 검색에 포함될 콘텐츠 개체를 가져오거나 설정합니다. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| [Add](../../groupdocs.watermark/watermarker/add#add)(Watermark) | 로드된 문서에 워터마크를 추가합니다. |
| [Add](../../groupdocs.watermark/watermarker/add#add_1)(Watermark, WatermarkOptions) | 워터마크 옵션을 사용하여 로드된 문서에 워터마크를 추가합니다. |
| [Dispose](../../groupdocs.watermark/watermarker/dispose)() | 현재 인스턴스를 삭제합니다. |
| [GeneratePreview](../../groupdocs.watermark/watermarker/generatepreview)(PreviewOptions) | 문서의 미리보기 이미지를 생성합니다. |
| [GetContent&lt;T&gt;](../../groupdocs.watermark/watermarker/getcontent)() | 반환[`Content`](../../groupdocs.watermark.contents/content) 로드된 문서의 개체. |
| [GetDocumentInfo](../../groupdocs.watermark/watermarker/getdocumentinfo)() | 로드된 문서의 형식에 대한 정보를 가져옵니다. |
| [GetImages](../../groupdocs.watermark/watermarker/getimages#getimages)() | 문서의 모든 이미지를 찾습니다. |
| [GetImages](../../groupdocs.watermark/watermarker/getimages#getimages_1)(ImageSearchCriteria) | 지정된 검색 기준에 따라 이미지를 찾습니다. |
| [Remove](../../groupdocs.watermark/watermarker/remove#remove)(PossibleWatermark) | 문서에서 워터마크를 제거합니다. |
| [Remove](../../groupdocs.watermark/watermarker/remove#remove_1)(PossibleWatermarkCollection) | 문서에서 컬렉션의 모든 워터마크를 제거합니다. |
| [Save](../../groupdocs.watermark/watermarker/save#save)() | 문서 데이터를 기본 스트림에 저장합니다. |
| [Save](../../groupdocs.watermark/watermarker/save#save_1)(SaveOptions) | 저장 옵션을 사용하여 기본 스트림에 문서 데이터를 저장합니다. |
| [Save](../../groupdocs.watermark/watermarker/save#save_2)(Stream) | 지정된 스트림에 문서를 저장합니다. |
| [Save](../../groupdocs.watermark/watermarker/save#save_4)(string) | 지정된 파일 위치에 문서를 저장합니다. |
| [Save](../../groupdocs.watermark/watermarker/save#save_3)(Stream, SaveOptions) | 저장 옵션을 사용하여 지정된 스트림에 문서를 저장합니다. |
| [Save](../../groupdocs.watermark/watermarker/save#save_5)(string, SaveOptions) | 저장 옵션을 사용하여 지정된 파일 위치에 문서를 저장합니다. |
| [Search](../../groupdocs.watermark/watermarker/search#search)() | 문서에서 가능한 모든 워터마크를 검색합니다. |
| [Search](../../groupdocs.watermark/watermarker/search#search_1)(SearchCriteria) | 지정된 검색 기준에 따라 가능한 워터마크를 검색합니다. |

### 예

지원되는 형식의 콘텐츠를 로드하고 저장합니다.

```csharp
// 파일에서 콘텐츠를 로드합니다.
using (Watermarker watermarker = new Watermarker("D:\\input.pdf"))
{
    // Watermarker 클래스의 메서드를 사용하여 워터마크를 추가, 검색 또는 제거합니다.

    // 변경 사항을 저장하다.
    watermarker.Save("D:\\output.pdf");
}
```

### 또한보십시오

* 네임스페이스 [GroupDocs.Watermark](../../groupdocs.watermark)
* 집회 [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->