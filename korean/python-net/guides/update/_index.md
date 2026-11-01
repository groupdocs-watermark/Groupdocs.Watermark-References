---
title: "워터마크 업데이트"
linkTitle: "Update watermarks"
second_title: "Python용 .NET을 통한 GroupDocs.Watermark API 참조"
description: "GroupDocs.Watermark for Python via .NET를 사용하여 기존 텍스트 또는 이미지 워터마크를 검색하고 업데이트합니다."
type: docs
url: /ko/python-net/guides/update/
is_root: false
weight: 90
---


문서에서 기존 워터마크를 검색하고 바로 수정할 수 있습니다 — 예를 들어 텍스트 워터마크의 텍스트를 교체하거나 이미지 워터마크의 이미지를 교체합니다.

## Update text watermarks

워터마크를 텍스트 내용으로 검색한 다음 각 일치 항목에 새 값을 할당합니다. 아래 예제는 이미 \"CONFIDENTIAL\" 워터마크가 포함된 문서를 열고 이를 \"APPROVED\"로 교체합니다.

{{< tabs \"code-example-update\">}}
{{< tab \"update_watermark.py\" >}}
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import TextSearchCriteria

def update_watermark():
    with Watermarker("./watermarked-document.pdf") as watermarker:
        # 조건과 일치하는 텍스트를 가진 워터마크 찾기
        possible = watermarker.search(TextSearchCriteria("CONFIDENTIAL"))
        print("Found", len(possible), "possible watermark(s).")
        for watermark in possible:
            try:
                watermark.text = "APPROVED"
            except Exception:
                # 일부 검색된 엔터티는 텍스트 편집을 지원하지 않으므로 건너뜁니다
                pass
        watermarker.save("./output.pdf")

if __name__ == "__main__":
    update_watermark()
```
{{< /tab >}}
{{< tab "watermarked-document.pdf" >}}

`watermarked-document.pdf`는 이 예제에 사용된 샘플 파일입니다. 다운로드하려면 [here](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/update/watermarked-document.pdf)를 클릭하십시오.

{{< /tab >}}
{{< tab "output.pdf" >}}
```text
Binary file (PDF, 444 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/update/update_watermark/output.pdf)
{{< /tab >}}
{{< /tabs >}}

## Update image watermarks

이미지 워터마크는 지각 해싱([`ImageDctHashSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/imagedcthashsearchcriteria/))을 사용하여 찾을 수 있으며 `image_data`에 새로운 바이트를 할당하여 업데이트합니다. 아래 예제는 로고 워터마크를 찾아 \"APPROVED\" 스탬프로 교체합니다.

{{< tabs \"code-example-update-image\">}}
{{< tab \"update_image_watermark.py\" >}}
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import ImageDctHashSearchCriteria

def update_image_watermark():
    with Watermarker("./watermarked-document.docx") as watermarker:
        criteria = ImageDctHashSearchCriteria("./logo.png")
        criteria.max_difference = 0.9
        possible = watermarker.search(criteria)
        with open("./stamp.png", "rb") as f:
            image_data = f.read()
        for watermark in possible:
            try:
                watermark.image_data = image_data
            except Exception:
                # 일부 검색된 엔터티는 이미지 편집을 지원하지 않으므로 건너뜁니다
                pass
        watermarker.save("./output.docx")

if __name__ == "__main__":
    update_image_watermark()
```
{{< /tab >}}
{{< tab \"watermarked-document.docx\" >}}

`watermarked-document.docx`, `logo.png`, 및 `stamp.png`는 이 예제에 사용된 샘플 파일입니다. [watermarked-document.docx](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/update/watermarked-document.docx), [logo.png](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/update/logo.png), 및 [stamp.png](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/update/stamp.png)를 다운로드하십시오.

{{< /tab >}}
{{< tab \"output.docx\" >}}
```text
Binary file (DOCX, 19 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/update/update_image_watermark/output.docx)
{{< /tab >}}
{{< /tabs >}}
