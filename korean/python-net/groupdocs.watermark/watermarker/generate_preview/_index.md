---
title: "generate_preview 메서드"
second_title: "Python용 .NET을 통한 GroupDocs.Watermark API 참조"
description: "문서에 대한 미리보기 이미지를 생성합니다."
type: docs
url: /ko/python-net/groupdocs.watermark/watermarker/generate_preview/
is_root: false
weight: 1040
---


## generate_preview {#preview_options}

문서에 대한 미리보기 이미지를 생성합니다.

```python
def generate_preview(self, preview_options):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| preview_options | `PreviewOptions` | 미리보기 이미지를 생성할 때 사용할 추가 옵션. |

### 예시

```python
    from groupdocs.watermark import Watermarker
    from groupdocs.watermark.options import PreviewOptions, PreviewFormats

    def generate_preview():
        # 렌더링할 각 페이지에 대한 쓰기 가능한 파일 스트림을 제공하십시오
        def create_page_stream(page_number):
            return open(f"./output-page-{page_number}.png", "wb")

        with Watermarker("./sample.pdf") as watermarker:
            options = PreviewOptions(create_page_stream)
            options.preview_format = PreviewFormats.PNG
            options.page_numbers = [1, 2]
            watermarker.generate_preview(options)

    if __name__ == "__main__":
        generate_preview()
    ```

### 또 보기
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
