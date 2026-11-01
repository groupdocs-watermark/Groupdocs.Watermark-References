---
title: "PdfWatermarkableImage 클래스"
second_title: "Python용 .NET을 통한 GroupDocs.Watermark API 참조"
description: "PDF 문서 내부의 이미지를 나타냅니다."
type: docs
url: /ko/python-net/groupdocs.watermark.contents.pdf/pdfwatermarkableimage/
is_root: false
weight: 240
---


## PdfWatermarkableImage class

PDF 문서 내부의 이미지를 나타냅니다.

PdfWatermarkableImage 유형은 다음 멤버를 노출합니다:

### 생성자
| 생성자 | 설명 |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfwatermarkableimage/__init__/#image_data) | 지정된 이미지 데이터를 사용하여 [`PdfWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfwatermarkableimage/) 클래스의 새 인스턴스를 초기화합니다. |

### 메서드
| 메서드 | 설명 |
| :- | :- |
| [add](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/add/) | 이 [`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/)에 워터마크를 추가합니다. 이 메서드는 워터마크 오프셋과 크기가 픽셀 단위로 측정된다고 가정합니다(할당된 경우). ([`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/)에서 상속됨) |
| [add_watermark](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/add_watermark/) | ([`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/)에서 상속됨) |
| [find_images](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images/) | 지정된 검색 기준에 따라 이미지를 찾습니다. 검색은 [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/)에 지정된 객체에서 수행됩니다. ([`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)에서 상속됨) |
| [find_images_image_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images_image_search_criteria/) | ([`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)에서 상속됨) |
| [get_bytes](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/get_bytes/) | 이미지를 바이트 배열로 가져옵니다. ([`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/)에서 상속됨) |
| [search](/watermark/python-net/groupdocs.watermark.contents/contentpart/search/) | 지정된 검색 기준에 따라 가능한 워터마크를 찾습니다. 검색은 [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/)에 나열된 객체에서 수행됩니다. ([`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)에서 상속됨) |
| [search_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/search_search_criteria/) | ([`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)에서 상속됨) |

### 속성
| 속성 | 설명 |
| :- | :- |
| [height](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/height/) | 이 [`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/)의 높이(픽셀 단위). ([`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/)에서 상속됨) |
| [width](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/width/) | 이 WatermarkableImage의 너비(픽셀 단위). ([`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/)에서 상속됨) |

### 예시

```python
import groupdocs.watermark.contents.pdf as gwc_pdf

with open("test.png", "rb") as f:
    img = gwc_pdf.PdfWatermarkableImage(f.read())
```

### 또 보기
* module [`groupdocs.watermark.contents.pdf`](/watermark/python-net/groupdocs.watermark.contents.pdf/)
