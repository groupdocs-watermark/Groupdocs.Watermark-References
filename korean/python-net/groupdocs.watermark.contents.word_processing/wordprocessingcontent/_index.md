---
title: "WordProcessingContent 클래스"
second_title: "Python용 .NET을 통한 GroupDocs.Watermark API 참조"
description: "워터마크를 배치할 수 있는 Word 문서(doc, docx 등)를 나타냅니다."
type: docs
url: /ko/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/
is_root: false
weight: 10
---


## WordProcessingContent class

워터마크를 배치할 수 있는 Word 문서(doc, docx 등)를 나타냅니다.

자세히 알아보기:
- Add watermarks to word processing documents: https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+word+processing+documents
- Existing objects in word processing document: https://docs.groupdocs.com/display/watermarknet/Existing+objects+in+word+processing+document
- Locking watermark in word processing document: https://docs.groupdocs.com/display/watermarknet/Locking+watermark+in+word+processing+document
- Protecting word processing documents: https://docs.groupdocs.com/display/watermarknet/Protecting+word+processing+documents
- Watermarks in word processing document: https://docs.groupdocs.com/display/watermarknet/Watermarks+in+word+processing+document

WordProcessingContent 유형은 다음 멤버를 노출합니다:

### 메서드
| 메서드 | 설명 |
| :- | :- |
| [decrypt](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/decrypt/) | 문서를 복호화합니다. |
| [encrypt](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/encrypt/#password) | 문서를 암호화합니다. |
| [encrypt_file](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/encrypt_file/) |  |
| [encrypt_string](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/encrypt_string/) |  |
| [protect](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/protect/#protection_type-password) | 문서를 변경으로부터 보호하고 보호 암호를 설정합니다. |
| [protect_file](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/protect_file/) |  |
| [protect_string](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/protect_string/) |  |
| [protect_word_processing_protection_type](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/protect_word_processing_protection_type/) |  |
| [unprotect](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/unprotect/) | 암호와 관계없이 문서의 보호를 해제합니다. |
| [dispose](/watermark/python-net/groupdocs.watermark.contents/content/dispose/) | 현재 인스턴스를 해제합니다. ([`Content`](/watermark/python-net/groupdocs.watermark.contents/content/)에서 상속됨) |
| [find_images](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images/) | 지정된 검색 기준에 따라 이미지를 찾습니다. 검색은 [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/)에 지정된 객체에서 수행됩니다. ([`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)에서 상속됨) |
| [find_images_image_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images_image_search_criteria/) | ([`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)에서 상속됨) |
| [search](/watermark/python-net/groupdocs.watermark.contents/contentpart/search/) | 지정된 검색 기준에 따라 가능한 워터마크를 찾습니다. 검색은 [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/)에 나열된 객체에서 수행됩니다. ([`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)에서 상속됨) |
| [search_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/search_search_criteria/) | ([`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)에서 상속됨) |

### 속성
| 속성 | 설명 |
| :- | :- |
| [page_count](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/page_count/) | 문서의 페이지 수입니다. |
| [sections](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/sections/) | 이 [`WordProcessingContent`](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/)의 모든 섹션 컬렉션입니다. |

### 예시

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.word_processing import WordProcessingLoadOptions

load_options = WordProcessingLoadOptions()
with Watermarker("input.docx", load_options) as watermarker:
    # 필요한 경우 여기에서 특정 섹션 또는 모든 섹션에 워터마크를 추가하십시오.
    watermarker.save("output.docx")
```

### 또 보기
* module [`groupdocs.watermark.contents.word_processing`](/watermark/python-net/groupdocs.watermark.contents.word_processing/)
