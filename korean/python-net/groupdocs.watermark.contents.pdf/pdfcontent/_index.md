---
title: "PdfContent 클래스"
second_title: "Python용 .NET을 통한 GroupDocs.Watermark API 참조"
description: "워터마크를 배치할 수 있는 PDF 문서를 나타냅니다."
type: docs
url: /ko/python-net/groupdocs.watermark.contents.pdf/pdfcontent/
is_root: false
weight: 100
---


## PdfContent class

워터마크를 배치할 수 있는 PDF 문서를 나타냅니다.

자세히 알아보기:
- [Add watermarks to PDF documents](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+PDF+documents)
- [Existing objects in PDF document](https://docs.groupdocs.com/display/watermarknet/Existing+objects+in+PDF+document)
- [Rasterize document or page](https://docs.groupdocs.com/display/watermarknet/Rasterize+document+or+page)
- [Watermarks in PDF document](https://docs.groupdocs.com/display/watermarknet/Watermarks+in+PDF+document)

PdfContent 유형은 다음 멤버를 노출합니다:

### 메서드
| 메서드 | 설명 |
| :- | :- |
| [decrypt](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/decrypt/) | 콘텐츠를 복호화합니다. |
| [encrypt](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/encrypt/#password) | 사용자 비밀번호와 소유자 비밀번호와 동일한 비밀번호를 사용하여 문서를 암호화합니다. |
| [encrypt](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/encrypt/#user_password-owner_password-permissions-crypto_algorithm) | 콘텐츠를 암호화합니다. |
| [encrypt_file](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/encrypt_file/) |  |
| [encrypt_string](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/encrypt_string/) |  |
| [rasterize](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/rasterize/#horizontal_resolution-vertical_resolution-image_format) | 모든 콘텐츠 페이지를 이미지로 변환합니다. |
| [rasterize_int32](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/rasterize_int32/) |  |
| [dispose](/watermark/python-net/groupdocs.watermark.contents/content/dispose/) | 현재 인스턴스를 해제합니다. ([`Content`](/watermark/python-net/groupdocs.watermark.contents/content/)에서 상속됨) |
| [find_images](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images/) | 지정된 검색 기준에 따라 이미지를 찾습니다. 검색은 [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/)에 지정된 객체에서 수행됩니다. ([`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)에서 상속됨) |
| [find_images_image_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images_image_search_criteria/) | ([`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)에서 상속됨) |
| [search](/watermark/python-net/groupdocs.watermark.contents/contentpart/search/) | 지정된 검색 기준에 따라 가능한 워터마크를 찾습니다. 검색은 [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/)에 나열된 객체에서 수행됩니다. ([`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)에서 상속됨) |
| [search_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/search_search_criteria/) | ([`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)에서 상속됨) |

### 속성
| 속성 | 설명 |
| :- | :- |
| [attachments](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/attachments/) | 이 [`PdfContent`](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/)의 모든 첨부 파일 컬렉션입니다. |
| [page_margin_type](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/page_margin_type/) | 워터마크 추가 중에 사용할 PDF 페이지 여백입니다. |
| [pages](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/pages/) | 이 [`PdfContent`](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/)의 모든 페이지 컬렉션입니다. |

### 예시

```python
from groupdocs.watermark import Watermarker

# PDF 파일을 로드합니다
watermarker = Watermarker("sample.pdf")

# PDF 콘텐츠 트리를 검색합니다
pdf_content = watermarker.get_content()

# 페이지를 순회하고 크기를 출력합니다
for page in pdf_content.pages:
    print(page.width, page.height)
```

### 또 보기
* module [`groupdocs.watermark.contents.pdf`](/watermark/python-net/groupdocs.watermark.contents.pdf/)
