---
title: "PresentationContent 클래스"
second_title: "Python용 .NET을 통한 GroupDocs.Watermark API 참조"
description: "워터마크를 배치할 수 있는 PowerPoint 문서를 나타냅니다."
type: docs
url: /ko/python-net/groupdocs.watermark.contents.presentation/presentationcontent/
is_root: false
weight: 60
---


## PresentationContent class

워터마크를 배치할 수 있는 PowerPoint 문서를 나타냅니다.

자세히 알아보기:
- Add watermarks to presentation documents: https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+presentation+documents
- Working with slide backgrounds: https://docs.groupdocs.com/display/watermarknet/Working+with+slide+backgrounds

PresentationContent 유형은 다음 멤버를 제공합니다:

### 메서드
| 메서드 | 설명 |
| :- | :- |
| [decrypt](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/decrypt/) | 문서를 복호화합니다. |
| [encrypt](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/encrypt/#password) | 문서를 암호화합니다. |
| [encrypt_file](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/encrypt_file/) |  |
| [encrypt_string](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/encrypt_string/) |  |
| [dispose](/watermark/python-net/groupdocs.watermark.contents/content/dispose/) | 현재 인스턴스를 해제합니다. ([`Content`](/watermark/python-net/groupdocs.watermark.contents/content/)에서 상속됨) |
| [find_images](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images/) | 지정된 검색 기준에 따라 이미지를 찾습니다. 검색은 [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/)에 지정된 객체에서 수행됩니다. ([`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)에서 상속됨) |
| [find_images_image_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images_image_search_criteria/) | ([`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)에서 상속됨) |
| [search](/watermark/python-net/groupdocs.watermark.contents/contentpart/search/) | 지정된 검색 기준에 따라 가능한 워터마크를 찾습니다. 검색은 [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/)에 나열된 객체에서 수행됩니다. ([`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)에서 상속됨) |
| [search_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/search_search_criteria/) | ([`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)에서 상속됨) |

### 속성
| 속성 | 설명 |
| :- | :- |
| [layout_slides](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/layout_slides/) | 이 [`PresentationContent`](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/)의 모든 레이아웃 슬라이드 컬렉션입니다. |
| [master_handout_slide](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/master_handout_slide/) | 이 [`PresentationContent`](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/)의 마스터 핸드아웃 슬라이드입니다. |
| [master_notes_slide](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/master_notes_slide/) | 이 [`PresentationContent`](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/)의 모든 노트 슬라이드에 대한 마스터 슬라이드입니다. |
| [master_slides](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/master_slides/) | 이 PresentationContent의 모든 마스터 슬라이드 컬렉션입니다. |
| [notes_slide_height](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/notes_slide_height/) | 노트 슬라이드의 높이(포인트)입니다. |
| [notes_slide_width](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/notes_slide_width/) | 노트 슬라이드의 너비(포인트)입니다. |
| [slide_height](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/slide_height/) | 슬라이드의 높이(포인트)입니다. |
| [slide_width](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/slide_width/) | 슬라이드의 너비(포인트)입니다. |
| [slides](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/slides/) | 이 [`PresentationContent`](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/)의 모든 슬라이드 컬렉션입니다. |

### 예시

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.presentation import PresentationLoadOptions

load_options = PresentationLoadOptions()
with Watermarker(r"D:\input.ppt", load_options) as watermarker:
    # 특정 슬라이드 또는 모든 슬라이드에 워터마크를 추가하려면 add 메서드를 사용하십시오.
    watermarker.save(r"D:\output.ppt")
```

### 또 보기
* module [`groupdocs.watermark.contents.presentation`](/watermark/python-net/groupdocs.watermark.contents.presentation/)
