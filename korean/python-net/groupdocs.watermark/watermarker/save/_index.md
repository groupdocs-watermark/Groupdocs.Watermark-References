---
title: "save 메서드"
second_title: "Python용 .NET을 통한 GroupDocs.Watermark API 참조"
description: "문서 데이터를 기본 스트림에 저장합니다."
type: docs
url: /ko/python-net/groupdocs.watermark/watermarker/save/
is_root: false
weight: 1130
---


## save

문서 데이터를 기본 스트림에 저장합니다.

문서 저장에 대해 자세히 알아보려면: https://docs.groupdocs.com/display/watermarknet/Saving+documents.

```python
def save(self):
    ...
```

### 예시

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import TextSearchCriteria

with Watermarker(r"D:\\test.msg") as watermarker:
    criteria = TextSearchCriteria("test", False)
    watermarks = watermarker.search(criteria)
    watermarker.remove(watermarks)
    watermarker.save()
```

## save {#file_path}

문서를 지정된 파일 위치에 저장합니다.

문서 저장에 대해 자세히 알아보려면: https://docs.groupdocs.com/display/watermarknet/Saving+documents.

```python
def save(self, file_path):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| file_path | `str` | 문서 데이터를 저장할 파일 경로. |

### 예시

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font

def add_and_save():
    with Watermarker("input.pdf") as watermarker:
        watermark = TextWatermark("top secret", Font("Arial", 36))
        watermarker.add(watermark)
        watermarker.save("output.pdf")
```

## save {#document}

문서를 지정된 스트림에 저장합니다.

https://docs.groupdocs.com/display/watermarknet/Saving+documents 에서 문서 저장에 대해 자세히 알아보세요.

```python
def save(self, document):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| document | `io.RawIOBase` | 문서 데이터를 저장할 스트림. |

### 예시

```python
from io import BytesIO
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark
from groupdocs.watermark.watermarks import Font

with Watermarker("input.pdf") as watermarker:
    watermark = TextWatermark("top secret", Font("Arial", 36))
    watermarker.add(watermark)
    stream = BytesIO()
    watermarker.save(stream)
    # `stream` 이제 저장된 PDF 바이트를 포함합니다
```

## save {#options}

저장 옵션을 사용하여 문서 데이터를 기본 스트림에 저장합니다.

문서 저장에 대해 자세히 알아보세요.

```python
def save(self, options):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| options | `SaveOptions` | 문서를 저장할 때 사용할 추가 옵션. |

### 예시

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options import SaveOptions
from groupdocs.watermark.watermarks import TextWatermark
from groupdocs.watermark.watermarks import Font

with Watermarker("input.pdf") as watermarker:
    watermark = TextWatermark("top secret", Font("Arial", 36))
    watermarker.add(watermark)
    watermarker.save(SaveOptions())
```

## save {#file_path-options}

저장 옵션을 사용하여 문서를 지정된 파일 위치에 저장합니다.

문서 저장에 대해 자세히 알아보려면: https://docs.groupdocs.com/display/watermarknet/Saving+documents.

```python
def save(self, file_path, options):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| file_path | `str` | 문서 데이터를 저장할 파일 경로. |
| options | `SaveOptions` | 문서를 저장할 때 사용할 추가 옵션. |

### 예시

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark
from groupdocs.watermark.watermarks import Font
from groupdocs.watermark.options import SaveOptions

with Watermarker("input.pdf") as watermarker:
    watermark = TextWatermark("top secret", Font("Arial", 36))
    watermarker.add(watermark)
    watermarker.save("output.pdf", SaveOptions())
```

## save {#document-options}

지정된 스트림에 저장 옵션을 사용하여 문서를 저장합니다.

GroupDocs 문서에서 문서 저장에 대해 자세히 알아보세요.

```python
def save(self, document, options):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| document | `io.RawIOBase` | 문서 데이터를 저장할 스트림. |
| options | `SaveOptions` | 문서를 저장할 때 사용할 추가 옵션. |

### 예시

```python
from io import BytesIO
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options import SaveOptions
from groupdocs.watermark.watermarks import TextWatermark
from groupdocs.watermark.watermarks import Font

def add_watermark_and_save():
    with Watermarker("input.pdf") as watermarker:
        watermark = TextWatermark("top secret", Font("Arial", 36))
        watermarker.add(watermark)

        stream = BytesIO()
        watermarker.save(stream, SaveOptions())
        # stream 이제 저장된 PDF 데이터를 포함합니다
        # 예를 들어, 파일에 쓰기
        with open("output.pdf", "wb") as f:
            f.write(stream.getvalue())

if __name__ == "__main__":
    add_watermark_and_save()
```

### 또 보기
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
