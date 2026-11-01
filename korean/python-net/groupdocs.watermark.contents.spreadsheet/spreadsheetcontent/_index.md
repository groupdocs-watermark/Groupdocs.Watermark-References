---
title: "SpreadsheetContent 클래스"
second_title: "Python용 .NET을 통한 GroupDocs.Watermark API 참조"
description: "워터마크를 배치할 수 있는 Excel 문서를 나타냅니다."
type: docs
url: /ko/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetcontent/
is_root: false
weight: 80
---


## SpreadsheetContent class

워터마크를 배치할 수 있는 Excel 문서를 나타냅니다.

자세히 알아보기:
- https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+spreadsheet+documents
- https://docs.groupdocs.com/display/watermarknet/Shapes+in+spreadsheet+document
- https://docs.groupdocs.com/display/watermarknet/Working+with+spreadsheet+document+attachments
- https://docs.groupdocs.com/display/watermarknet/Working+with+worksheet+backgrounds
- https://docs.groupdocs.com/display/watermarknet/Working+with+worksheet+headers+and+footers

SpreadsheetContent 유형은 다음 멤버를 노출합니다:

### 메서드
| 메서드 | 설명 |
| :- | :- |
| [decrypt](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetcontent/decrypt/) | 문서를 복호화합니다. |
| [encrypt](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetcontent/encrypt/#password) | 콘텐츠를 암호화합니다. |
| [encrypt_file](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetcontent/encrypt_file/) |  |
| [encrypt_string](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetcontent/encrypt_string/) |  |
| [dispose](/watermark/python-net/groupdocs.watermark.contents/content/dispose/) | 현재 인스턴스를 해제합니다. ([`Content`](/watermark/python-net/groupdocs.watermark.contents/content/)에서 상속됨) |
| [find_images](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images/) | 지정된 검색 기준에 따라 이미지를 찾습니다. 검색은 [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/)에 지정된 객체에서 수행됩니다. ([`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)에서 상속됨) |
| [find_images_image_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images_image_search_criteria/) | ([`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)에서 상속됨) |
| [search](/watermark/python-net/groupdocs.watermark.contents/contentpart/search/) | 지정된 검색 기준에 따라 가능한 워터마크를 찾습니다. 검색은 [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/)에 나열된 객체에서 수행됩니다. ([`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)에서 상속됨) |
| [search_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/search_search_criteria/) | ([`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)에서 상속됨) |

### 속성
| 속성 | 설명 |
| :- | :- |
| [worksheets](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetcontent/worksheets/) | 이 [`SpreadsheetContent`](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetcontent/)의 모든 워크시트 컬렉션입니다. |

### 예시

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.spreadsheet import SpreadsheetLoadOptions

load_options = SpreadsheetLoadOptions()
with Watermarker(r"D:\input.xls", load_options) as watermarker:
    # 특정 워크시트 또는 모든 워크시트에 워터마크를 추가하려면 add 메서드를 사용하십시오.
    watermarker.save(r"D:\output.xls")
```

### 또 보기
* module [`groupdocs.watermark.contents.spreadsheet`](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/)
