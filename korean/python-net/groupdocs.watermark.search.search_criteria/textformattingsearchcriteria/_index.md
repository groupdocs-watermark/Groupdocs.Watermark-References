---
title: "TextFormattingSearchCriteria 클래스"
second_title: "Python용 .NET을 통한 GroupDocs.Watermark API 참조"
description: "텍스트 서식으로 필터링을 허용하는 기준을 나타냅니다."
type: docs
url: /ko/python-net/groupdocs.watermark.search.search_criteria/textformattingsearchcriteria/
is_root: false
weight: 150
---


## TextFormattingSearchCriteria class

텍스트 서식으로 필터링을 허용하는 기준을 나타냅니다.

자세히 알아보기:
- Searching watermarks (https://docs.groupdocs.com/display/watermarknet/Searching+watermarks)

TextFormattingSearchCriteria 유형은 다음 멤버를 노출합니다:

### 생성자
| 생성자 | 설명 |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.search.search_criteria/textformattingsearchcriteria/__init__/) | 새 인스턴스를 초기화합니다 [`TextFormattingSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/textformattingsearchcriteria/). |

### 메서드
| 메서드 | 설명 |
| :- | :- |
| [and_](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/and_/) | 논리 AND 연산자를 사용하여 이 SearchCriteria를 다른 기준과 결합합니다. ([`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/) 로부터 상속됨) |
| [and_search_criteria](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/and_search_criteria/) | ([`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/) 로부터 상속됨) |
| [not_](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/not_/) | 이 SearchCriteria를 부정합니다. ([`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/) 로부터 상속됨) |
| [or_](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/or_/) | 논리 OR 연산자를 사용하여 이 SearchCriteria를 다른 기준과 결합합니다. ([`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/) 로부터 상속됨) |
| [or_search_criteria](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/or_search_criteria/) | ([`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/) 로부터 상속됨) |

### 속성
| 속성 | 설명 |
| :- | :- |
| [background_color_range](/watermark/python-net/groupdocs.watermark.search.search_criteria/textformattingsearchcriteria/background_color_range/) | 텍스트 배경색으로 워터마크를 필터링하는 데 사용되는 색상 범위입니다. |
| [font_bold](/watermark/python-net/groupdocs.watermark.search.search_criteria/textformattingsearchcriteria/font_bold/) | 워터마크 텍스트 서식에 사용되는 글꼴은 굵게 설정됩니다. |
| [font_italic](/watermark/python-net/groupdocs.watermark.search.search_criteria/textformattingsearchcriteria/font_italic/) | font_italic 속성은 워터마크 텍스트 글꼴이 이탤릭인지 여부를 나타냅니다. |
| [font_name](/watermark/python-net/groupdocs.watermark.search.search_criteria/textformattingsearchcriteria/font_name/) | 가능한 워터마크 텍스트 서식에 사용되는 글꼴 이름입니다. |
| [font_strikeout](/watermark/python-net/groupdocs.watermark.search.search_criteria/textformattingsearchcriteria/font_strikeout/) | 워터마크 텍스트 서식에 대한 글꼴 취소선 플래그입니다. |
| [font_underline](/watermark/python-net/groupdocs.watermark.search.search_criteria/textformattingsearchcriteria/font_underline/) | 워터마크 텍스트에 밑줄이 사용되는지 여부를 나타내는 글꼴 밑줄 플래그입니다. |
| [foreground_color_range](/watermark/python-net/groupdocs.watermark.search.search_criteria/textformattingsearchcriteria/foreground_color_range/) | 텍스트 전경색으로 워터마크를 필터링하는 데 사용되는 색상 범위입니다. |
| [max_font_size](/watermark/python-net/groupdocs.watermark.search.search_criteria/textformattingsearchcriteria/max_font_size/) | 글꼴 크기의 끝 값입니다. |
| [min_font_size](/watermark/python-net/groupdocs.watermark.search.search_criteria/textformattingsearchcriteria/min_font_size/) | 글꼴 크기의 시작 값입니다. |

### 예시

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import TextFormattingSearchCriteria, ColorRange

def search_by_formatting():
    with Watermarker("./document.pdf") as watermarker:
        criteria = TextFormattingSearchCriteria()
        criteria.foreground_color_range = ColorRange()
        criteria.foreground_color_range.min_hue = -15
        criteria.foreground_color_range.max_hue = 15
        criteria.foreground_color_range.min_brightness = 0.01
        criteria.foreground_color_range.max_brightness = 0.99
        criteria.min_font_size = 19
        criteria.max_font_size = 42

        possible = watermarker.search(criteria)
        print("Found", len(possible), "possible watermark(s)")

if __name__ == "__main__":
    search_by_formatting()
```

### Guides
`TextFormattingSearchCriteria`를 사용하는 작업 가이드:

* [Searching watermarks](/watermark/python-net/guides/searching-watermarks/)

### 또 보기
* module [`groupdocs.watermark.search.search_criteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/)
