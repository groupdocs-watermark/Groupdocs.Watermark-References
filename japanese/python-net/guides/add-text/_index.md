---
title: "テキスト透かしを追加"
linkTitle: "Add text watermarks"
second_title: "GroupDocs.Watermark for Python via .NET API リファレンス"
description: "この記事では、ドキュメントにテキスト透かしを追加し、GroupDocs.Watermark for Python via .NET で結果を保存する方法を示します。"
type: docs
url: /ja/python-net/guides/add-text/
is_root: false
weight: 40
---


GroupDocs.Watermark の主な機能のひとつは、文書にテキスト透かしを追加することです。ローカルパスやストリームから、文書や画像に透かしを追加できます。サポートされているフォーマットの全リストについては、[Supported document formats](https://docs.groupdocs.com/watermark/python-net/supported-document-formats/) を確認してください。

## Add a text watermark

テキスト透かしを追加するには、以下の手順に従ってください：

1. ドキュメントのパス（またはストリーム）を [Watermarker](https://reference.groupdocs.com/watermark/python-net/) クラスに渡し、`with` ブロックを使用して自動的にドキュメントが解放されるように開きます。
2. 目的のテキストと [`Font`](/watermark/python-net/groupdocs.watermark.watermarks/font/) を使用して、[`TextWatermark`](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/) を作成します。
3. 透かしのスタイルを設定します — 例えば、`foreground_color` や配置を設定します。
4. `add()` を呼び出してウォーターマークを適用し、`save()` で結果を書き出します。

{{< tabs \"code-example-add-text\">}}
{{< tab \"add_text_watermark.py\" >}}
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color
from groupdocs.watermark.common import HorizontalAlignment, VerticalAlignment

def add_text_watermark():
    with Watermarker("./sample.pdf") as watermarker:
        # テキスト透かしを作成し、スタイルを設定します
        watermark = TextWatermark("Top Secret", Font("Arial", 36.0))
        watermark.foreground_color = Color.red
        watermark.horizontal_alignment = HorizontalAlignment.CENTER
        watermark.vertical_alignment = VerticalAlignment.CENTER
        watermark.rotate_angle = 45.0
        watermark.opacity = 0.4

        watermarker.add(watermark)
        watermarker.save("./output.pdf")

if __name__ == "__main__":
    add_text_watermark()
```
{{< /tab >}}
{{< tab \"sample.pdf\" >}}

`sample.pdf` はこの例で使用されているサンプルファイルです。[here](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/add-text/sample.pdf) をクリックしてダウンロードしてください。

{{< /tab >}}
{{< tab \"output.pdf\" >}}
```text
Binary file (PDF, 313 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/add-text/add_text_watermark/output.pdf)
{{< /tab >}}
{{< /tabs >}}

プログラムを実行します。指定されたパスに新しい透かし入りドキュメントが作成されます。

## What's next

GroupDocs.Watermark はテキスト透かしに対して、背景色と前景色、カスタムフォント、不透明度、回転、タイル配置、絶対位置または相対位置など、さらに多くの機能を提供します。詳細は上級ガイドの [Adding text watermarks](https://docs.groupdocs.com/watermark/python-net/adding-text-watermarks/) を参照してください。
