---
title: SpreadsheetAttachment
second_title: .NET API 참조용 GroupDocs.Watermark
description: 엑셀 문서에 첨부된 파일을 나타냅니다.
type: docs
weight: 1030
url: /ko/net/groupdocs.watermark.contents.spreadsheet/spreadsheetattachment/
---
## SpreadsheetAttachment class

엑셀 문서에 첨부된 파일을 나타냅니다.

```csharp
public class SpreadsheetAttachment : Attachment, ITwoDObject
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [AlternativeText](../../groupdocs.watermark.contents.spreadsheet/spreadsheetattachment/alternativetext) { get; set; } | 첨부 파일과 관련된 설명(대체) 텍스트를 가져오거나 설정합니다. |
| override [Content](../../groupdocs.watermark.contents.spreadsheet/spreadsheetattachment/content) { get; set; } | 첨부파일 내용을 가져오거나 설정합니다. |
| [Height](../../groupdocs.watermark.contents.spreadsheet/spreadsheetattachment/height) { get; set; } | 부착 프레임의 높이를 포인트 단위로 가져오거나 설정합니다. |
| [IsLink](../../groupdocs.watermark.contents.spreadsheet/spreadsheetattachment/islink) { get; } | 콘텐츠에 파일에 대한 링크만 포함되어 있는지 여부를 나타내는 값을 가져옵니다. |
| [PreviewImageContent](../../groupdocs.watermark.contents.spreadsheet/spreadsheetattachment/previewimagecontent) { get; set; } | 첨부파일 미리보기 이미지를 바이트 배열로 가져오거나 설정합니다. |
| [SourceFullName](../../groupdocs.watermark.contents.spreadsheet/spreadsheetattachment/sourcefullname) { get; } | 첨부 파일의 전체 이름을 가져옵니다. |
| [Width](../../groupdocs.watermark.contents.spreadsheet/spreadsheetattachment/width) { get; set; } | 부착 프레임의 너비를 포인트 단위로 가져오거나 설정합니다. |
| [X](../../groupdocs.watermark.contents.spreadsheet/spreadsheetattachment/x) { get; set; } | 워크시트 왼쪽 테두리에서 부착 프레임의 수평 오프셋을 포인트 단위로 가져오거나 설정합니다. |
| [Y](../../groupdocs.watermark.contents.spreadsheet/spreadsheetattachment/y) { get; set; } | 워크시트 위쪽 테두리에서 첨부 프레임의 수직 오프셋을 포인트 단위로 가져오거나 설정합니다. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| [CreateWatermarker](../../groupdocs.watermark.common/attachment/createwatermarker)() | 첨부파일에서 컨텐츠를 불러옵니다. |
| [CreateWatermarker](../../groupdocs.watermark.common/attachment/createwatermarker)(LoadOptions) | 지정된 로드 옵션으로 첨부 파일에서 콘텐츠를 로드합니다. |
| [CreateWatermarker](../../groupdocs.watermark.common/attachment/createwatermarker)(LoadOptions, WatermarkerSettings) | 지정된 로드 옵션 및 설정으로 첨부 파일에서 콘텐츠를 로드합니다. |
| [GetDocumentInfo](../../groupdocs.watermark.common/attachment/getdocumentinfo)() | 첨부파일에 저장된 문서의 정보를 가져옵니다. |

### 또한보십시오

* class [Attachment](../../groupdocs.watermark.common/attachment)
* interface [ITwoDObject](../../groupdocs.watermark.search/itwodobject)
* 네임스페이스 [GroupDocs.Watermark.Contents.Spreadsheet](../../groupdocs.watermark.contents.spreadsheet)
* 집회 [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->