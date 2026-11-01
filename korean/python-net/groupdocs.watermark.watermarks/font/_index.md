---
title: "Font 클래스"
second_title: "Python용 .NET을 통한 GroupDocs.Watermark API 참조"
description: "폰트를 나타냅니다."
type: docs
url: /ko/python-net/groupdocs.watermark.watermarks/font/
is_root: false
weight: 20
---


## Font class

폰트를 나타냅니다.

Font 유형은 다음 멤버를 노출합니다:

### 생성자
| 생성자 | 설명 |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.watermarks/font/__init__/#font_family_name-size) | 지정된 글꼴 패밀리 이름과 크기로 새로운 Font 인스턴스를 초기화합니다. |
| [__init__](/watermark/python-net/groupdocs.watermark.watermarks/font/__init__/#font_family_name-size-style) | 지정된 글꼴 패밀리 이름, 크기 및 스타일로 새로운 Font 인스턴스를 초기화합니다. |
| [__init__](/watermark/python-net/groupdocs.watermark.watermarks/font/__init__/#font_family_name-folder_path-size) | 맞춤 글꼴 패밀리 이름, TrueType 글꼴이 포함된 폴더, 크기 및 스타일로 새로운 Font 인스턴스를 초기화합니다. |
| [__init__](/watermark/python-net/groupdocs.watermark.watermarks/font/__init__/#font_family_name-folder_path-size-style) | 맞춤 글꼴 패밀리 이름, TrueType 글꼴 파일이 포함된 폴더, 그리고 크기로 새로운 Font 인스턴스를 초기화합니다. |

### 속성
| 속성 | 설명 |
| :- | :- |
| [bold](/watermark/python-net/groupdocs.watermark.watermarks/font/bold/) | 글꼴이 굵게 설정됩니다. |
| [family_name](/watermark/python-net/groupdocs.watermark.watermarks/font/family_name/) | 이 Font의 패밀리 이름. |
| [folder_path](/watermark/python-net/groupdocs.watermark.watermarks/font/folder_path/) | TrueType 글꼴 파일이 포함된 폴더. |
| [italic](/watermark/python-net/groupdocs.watermark.watermarks/font/italic/) | 글꼴이 기울임꼴입니다. |
| [size](/watermark/python-net/groupdocs.watermark.watermarks/font/size/) | 이 Font의 크기. |
| [strikeout](/watermark/python-net/groupdocs.watermark.watermarks/font/strikeout/) | 글꼴은 텍스트에 가로줄을 지정합니다. |
| [style](/watermark/python-net/groupdocs.watermark.watermarks/font/style/) | 이 Font에 대한 스타일 정보. |
| [underline](/watermark/python-net/groupdocs.watermark.watermarks/font/underline/) | 글꼴에 밑줄이 있습니다. |

### 예시

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color

with Watermarker("document.pdf") as watermarker:
    watermark = TextWatermark("CONFIDENTIAL", Font("Arial", 48))
    watermark.foreground_color = Color.red
    watermarker.add(watermark)
    watermarker.save("watermarked.pdf")
```

### Guides
`Font`을 사용하는 작업 가이드:

* [Hello, World!](/watermark/python-net/guides/hello-world/)
* [Add text watermarks](/watermark/python-net/guides/add-text/)
* [Customize watermarks](/watermark/python-net/guides/customize/)
* [Adding repeated watermarks](/watermark/python-net/guides/adding-repeated-watermarks/)

### 또 보기
* module [`groupdocs.watermark.watermarks`](/watermark/python-net/groupdocs.watermark.watermarks/)
