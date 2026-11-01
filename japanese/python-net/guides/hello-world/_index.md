---
title: "こんにちは、世界！"
linkTitle: "Hello, World!"
second_title: "GroupDocs.Watermark for Python via .NET API リファレンス"
description: ".NET 経由で Python 用 GroupDocs.Watermark をすぐに始めるには、シンプルな例を作成して実行します。"
type: docs
url: /ja/python-net/guides/hello-world/
is_root: false
weight: 20
---


## Introduction
.NET 経由で Python 用 GroupDocs.Watermark を調査する際、\"Hello, World!\" の例はしばしば最初のステップです。これは、開発環境が正しく設定され、ライブラリが期待通りに機能していることを確認するシンプルなテストとして役立ちます。

## Overview
.NET 経由で Python 用 GroupDocs.Watermark を使用すると、さまざまな文書フォーマットで透かしの追加、検索、削除が可能です。幅広い [supported formats](https://docs.groupdocs.com/watermark/python-net/getting-started/supported-document-formats/) により、さまざまなユースケースに柔軟に対応できます。

## How to add a watermark
以下の手順は、.NET 経由で Python 用 GroupDocs.Watermark を使用して文書にテキスト透かしを追加する方法を示しています：

1. 必要な `groupdocs.watermark` クラスをインポートします。
2. サンプル文書へのパスを指定して、[`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/) を開きます。
3. 目的のテキストとフォントを使用して、[`TextWatermark`](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/) を作成し、スタイルを設定します。
4. `add()` を使用して透かしを適用します。
5. 結果を保存します。

## Complete example
以下の例は、半透明で斜めの \"Hello, Watermark!\" テキスト透かしを追加し、結果を保存します：

{{< tabs \"code-example-hello-world\" >}}
{{< tab \"hello_world.py\" >}}
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color

def hello_world():
    # ドキュメントを開き、単一のテキスト透かしを追加して、結果を保存します
    with Watermarker("./sample.pdf") as watermarker:
        watermark = TextWatermark("Hello, Watermark!", Font("Arial", 36.0))
        watermark.foreground_color = Color.red
        watermark.opacity = 0.5
        watermark.rotate_angle = 45.0
        watermarker.add(watermark)
        watermarker.save("./output.pdf")

    print("Watermark added successfully. Output saved to ./output.pdf.")

if __name__ == "__main__":
    hello_world()
```
{{< /tab >}}
{{< tab \"sample.pdf\" >}}

`sample.pdf` はこの例で使用されるサンプルファイルです。ダウンロードするには [here](https://docs.groupdocs.com/watermark/python-net/_sample_files/getting-started/hello-world/sample.pdf) をクリックしてください。

{{< /tab >}}
{{< tab \"output.pdf\" >}}
```text
Binary file (PDF, 315 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/getting-started/hello-world/hello_world/output.pdf)
{{< /tab >}}
{{< /tabs >}}

透かしは `output.pdf` と同じ PDF 形式で保存されます。別のドキュメントにスタンプを付けるには、入力パスと出力拡張子を変更してください — GroupDocs.Watermark は入力ドキュメントの形式で保存します。

## Additional resources
このデモは GroupDocs.Watermark for Python via .NET の [code samples](https://github.com/groupdocs-watermark/GroupDocs.Watermark-for-Python-via-.NET/) を参照しています。
