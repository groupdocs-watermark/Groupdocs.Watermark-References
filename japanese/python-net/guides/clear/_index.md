---
title: "透かしのクリア"
linkTitle: "Clear watermarks"
second_title: "GroupDocs.Watermark for Python via .NET API リファレンス"
description: "GroupDocs.Watermark for Python via .NET を使用して、既存のテキストまたは画像の透かしを検索し、削除します。"
type: docs
url: /ja/python-net/guides/clear/
is_root: false
weight: 100
---


ドキュメント内の既存の透かしを検索して削除できます。以下の例では、\"CONFIDENTIAL\" テキスト透かしを検出し、削除してクリーンなドキュメントを生成します。

## Remove text watermarks

検索結果を逆順に反復処理することで、項目を削除しても残りのインデックスがずれないようにし、各一致に対して `remove()` を呼び出します。

{{< tabs \"code-example-clear\">}}
{{< tab \"clear_watermark.py\" >}}
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import TextSearchCriteria

def clear_watermark():
    with Watermarker("./watermarked-document.pdf") as watermarker:
        possible = watermarker.search(TextSearchCriteria("CONFIDENTIAL"))
        # 削除時にインデックスが有効なままになるよう、逆順で削除します
        for i in range(len(possible) - 1, -1, -1):
            watermarker.remove(possible[i])
        watermarker.save("./output.pdf")

if __name__ == "__main__":
    clear_watermark()
```
{{< /tab >}}
{{< tab \"watermarked-document.pdf\" >}}

`watermarked-document.pdf` はこの例で使用されるサンプルファイルです。ダウンロードするには [here](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/clear/watermarked-document.pdf) をクリックしてください。

{{< /tab >}}
{{< tab \"output.pdf\" >}}
```text
Binary file (PDF, 360 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/clear/clear_watermark/output.pdf)
{{< /tab >}}
{{< /tabs >}}

**Use case:** Remove outdated labels such as "Draft" or "Internal Use Only" before sharing a document externally.

## Remove image watermarks

画像透かしは知覚ハッシュで検出でき、同様の方法で削除できます：

{{< tabs "code-example-clear-image">}}
{{< tab "clear_image_watermark.py" >}}
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import ImageDctHashSearchCriteria

def clear_image_watermark():
    with Watermarker("./watermarked-document.docx") as watermarker:
        criteria = ImageDctHashSearchCriteria("./logo.png")
        criteria.max_difference = 0.9
        possible = watermarker.search(criteria)
        # 削除時にインデックスが有効なままになるよう、逆順で削除します
        for i in range(len(possible) - 1, -1, -1):
            watermarker.remove(possible[i])
        watermarker.save("./output.docx")

if __name__ == "__main__":
    clear_image_watermark()
```
{{< /tab >}}
{{< tab "watermarked-document.docx" >}}

`watermarked-document.docx` と `logo.png` はこの例で使用されるサンプルファイルです。 [watermarked-document.docx](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/clear/watermarked-document.docx) と [logo.png](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/clear/logo.png) をダウンロードしてください。

{{< /tab >}}
{{< tab "output.docx" >}}
```text
Binary file (DOCX, 13 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/clear/clear_image_watermark/output.docx)
{{< /tab >}}
{{< /tabs >}}
