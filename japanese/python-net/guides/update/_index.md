---
title: "ウォーターマークを更新する"
linkTitle: "Update watermarks"
second_title: "GroupDocs.Watermark for Python via .NET API リファレンス"
description: "GroupDocs.Watermark for Python via .NET を使用して、既存のテキストまたは画像のウォーターマークを検索し、更新します。"
type: docs
url: /ja/python-net/guides/update/
is_root: false
weight: 90
---


ドキュメント内の既存のウォーターマークを検索し、その場で変更できます。たとえば、テキストウォーターマークのテキストを置き換えたり、画像ウォーターマークの画像を差し替えたりできます。

## Update text watermarks

テキスト内容でウォーターマークを検索し、各一致に新しい値を割り当てます。以下の例では、すでに「CONFIDENTIAL」ウォーターマークが含まれるドキュメントを開き、それを「APPROVED」に置き換えます。

{{< tabs "code-example-update">}}
{{< tab "update_watermark.py" >}}
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import TextSearchCriteria

def update_watermark():
    with Watermarker("./watermarked-document.pdf") as watermarker:
        # 基準に一致するテキストを持つウォーターマークを検索する
        possible = watermarker.search(TextSearchCriteria("CONFIDENTIAL"))
        print("Found", len(possible), "possible watermark(s).")
        for watermark in possible:
            try:
                watermark.text = "APPROVED"
            except Exception:
                # 見つかった一部のエンティティはテキスト編集をサポートしていません — スキップしてください
                pass
        watermarker.save("./output.pdf")

if __name__ == "__main__":
    update_watermark()
```
{{< /tab >}}
{{< tab \"watermarked-document.pdf\" >}}

`watermarked-document.pdf` はこの例で使用されるサンプルファイルです。[こちら](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/update/watermarked-document.pdf) をクリックしてダウンロードしてください。

{{< /tab >}}
{{< tab \"output.pdf\" >}}
```text
Binary file (PDF, 444 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/update/update_watermark/output.pdf)
{{< /tab >}}
{{< /tabs >}}

## Update image watermarks

画像ウォーターマークは知覚ハッシュ（[`ImageDctHashSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/imagedcthashsearchcriteria/)）で検出でき、`image_data` に新しいバイトを割り当てて更新できます。以下の例では、ロゴウォーターマークを検出し、"APPROVED" スタンプに置き換えます。

{{< tabs "code-example-update-image">}}
{{< tab "update_image_watermark.py" >}}
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
                # 見つかった一部のエンティティは画像編集をサポートしていません — スキップしてください
                pass
        watermarker.save("./output.docx")

if __name__ == "__main__":
    update_image_watermark()
```
{{< /tab >}}
{{< tab "watermarked-document.docx" >}}

`watermarked-document.docx`、`logo.png`、および `stamp.png` はこの例で使用されるサンプルファイルです。[watermarked-document.docx](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/update/watermarked-document.docx)、[logo.png](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/update/logo.png)、[stamp.png](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/update/stamp.png) をダウンロードしてください。

{{< /tab >}}
{{< tab "output.docx" >}}
```text
Binary file (DOCX, 19 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/update/update_image_watermark/output.docx)
{{< /tab >}}
{{< /tabs >}}
