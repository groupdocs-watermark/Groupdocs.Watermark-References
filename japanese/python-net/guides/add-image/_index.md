---
title: "画像透かしを追加する"
linkTitle: "Add image watermarks"
second_title: "GroupDocs.Watermark for Python via .NET API リファレンス"
description: "この記事では、ドキュメントに画像透かしを追加し、.NET 経由で Python 用 GroupDocs.Watermark を使用して結果を保存する方法を示します。"
type: docs
url: /ja/python-net/guides/add-image/
is_root: false
weight: 50
---


GroupDocs.Watermark の主な機能の一つは、ドキュメントに画像透かしを追加することです。ローカルパスやストリームからドキュメントや画像に透かしを追加できます。サポートされているフォーマットの完全な一覧は、[Supported document formats](https://docs.groupdocs.com/watermark/python-net/supported-document-formats/) を確認してください。

## Add an image watermark

画像透かしを追加するには、以下の手順に従ってください：

1. ドキュメントのパス（またはストリーム）を[`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/) クラスに渡して開きます。
2. 透かし画像ファイル（またはストリーム）から[`ImageWatermark`](/watermark/python-net/groupdocs.watermark.watermarks/imagewatermark/) を作成します。
3. ウォーターマークの位置を設定します — 例として、`horizontal_alignment`、`vertical_alignment`、`opacity` を設定します。
4. `add()` を呼び出してウォーターマークを適用し、`save()` で結果を書き出します。

{{< tabs \"code-example-add-image\">}}
{{< tab \"add_image_watermark.py\" >}}
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import ImageWatermark
from groupdocs.watermark.common import HorizontalAlignment, VerticalAlignment

def add_image_watermark():
    with Watermarker("./sample.docx") as watermarker:
        # ロゴファイルから画像ウォーターマークを作成し、中央に配置します
        watermark = ImageWatermark("./logo.png")
        watermark.horizontal_alignment = HorizontalAlignment.CENTER
        watermark.vertical_alignment = VerticalAlignment.CENTER
        watermark.opacity = 0.7

        watermarker.add(watermark)
        watermarker.save("./output.docx")

if __name__ == "__main__":
    add_image_watermark()
```
{{< /tab >}}
{{< tab \"sample.docx\" >}}

`sample.docx` と `logo.png` はこの例で使用されるサンプルファイルです。ダウンロードは [sample.docx](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/add-image/sample.docx) と [logo.png](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/add-image/logo.png) をご利用ください。

{{< /tab >}}
{{< tab "output.docx" >}}
```text
Binary file (DOCX, 127 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/add-image/add_image_watermark/output.docx)
{{< /tab >}}
{{< /tabs >}}

## What's next

GroupDocs.Watermark は画像ウォーターマーク向けに、ストリームからの読み込み、スケーリング、タイル配置、絶対位置または相対位置指定など、さらに多くの機能を提供します。詳細は上級ガイドの [Adding image watermarks](https://docs.groupdocs.com/watermark/python-net/adding-image-watermarks/) を参照してください。
