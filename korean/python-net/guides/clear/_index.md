---
title: "워터마크 제거"
linkTitle: "Clear watermarks"
second_title: "Python용 .NET을 통한 GroupDocs.Watermark API 참조"
description: "GroupDocs.Watermark for Python via .NET를 사용하여 기존 텍스트 또는 이미지 워터마크를 검색하고 제거합니다."
type: docs
url: /ko/python-net/guides/clear/
is_root: false
weight: 100
---


문서에서 기존 워터마크를 검색하고 제거할 수 있습니다. 아래 예제는 "CONFIDENTIAL" 텍스트 워터마크를 찾아 제거하여 깨끗한 문서를 생성합니다.

## Remove text watermarks

검색 결과를 역순으로 반복하면 항목을 제거해도 아직 방문해야 할 인덱스가 이동하지 않으며, 각 매치에 대해 `remove()`를 호출합니다.

{{< tabs "code-example-clear">}}
{{< tab "clear_watermark.py" >}}
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import TextSearchCriteria

def clear_watermark():
    with Watermarker("./watermarked-document.pdf") as watermarker:
        possible = watermarker.search(TextSearchCriteria("CONFIDENTIAL"))
        # 항목이 삭제될 때 인덱스가 유효하게 유지되도록 역순으로 제거합니다
        for i in range(len(possible) - 1, -1, -1):
            watermarker.remove(possible[i])
        watermarker.save("./output.pdf")

if __name__ == "__main__":
    clear_watermark()
```
{{< /tab >}}
{{< tab "watermarked-document.pdf" >}}

`watermarked-document.pdf`는 이 예제에서 사용된 샘플 파일입니다. 다운로드하려면 [here](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/clear/watermarked-document.pdf)를 클릭하십시오.

{{< /tab >}}
{{< tab "output.pdf" >}}
```text
Binary file (PDF, 360 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/clear/clear_watermark/output.pdf)
{{< /tab >}}
{{< /tabs >}}

**Use case:** Remove outdated labels such as "Draft" or "Internal Use Only" before sharing a document externally.

## Remove image watermarks

이미지 워터마크는 인지 해싱을 사용하여 찾을 수 있으며 동일한 방법으로 제거됩니다:

{{< tabs \"code-example-clear-image\">}}
{{< tab \"clear_image_watermark.py\" >}}
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import ImageDctHashSearchCriteria

def clear_image_watermark():
    with Watermarker("./watermarked-document.docx") as watermarker:
        criteria = ImageDctHashSearchCriteria("./logo.png")
        criteria.max_difference = 0.9
        possible = watermarker.search(criteria)
        # 항목이 삭제될 때 인덱스가 유효하게 유지되도록 역순으로 제거합니다
        for i in range(len(possible) - 1, -1, -1):
            watermarker.remove(possible[i])
        watermarker.save("./output.docx")

if __name__ == "__main__":
    clear_image_watermark()
```
{{< /tab >}}
{{< tab \"watermarked-document.docx\" >}}

`watermarked-document.docx`와 `logo.png`는 이 예제에 사용된 샘플 파일입니다. [watermarked-document.docx](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/clear/watermarked-document.docx) 및 [logo.png](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/clear/logo.png)를 다운로드하십시오.

{{< /tab >}}
{{< tab \"output.docx\" >}}
```text
Binary file (DOCX, 13 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/clear/clear_image_watermark/output.docx)
{{< /tab >}}
{{< /tabs >}}
