---
title: "ドキュメントプレビュー"
linkTitle: "Document preview"
second_title: "GroupDocs.Watermark for Python via .NET API リファレンス"
description: "GroupDocs.Watermark for Python via .NET を使用して、ドキュメントページのプレビュー画像（PNG/JPG/BMP）を生成します。"
type: docs
url: /ja/python-net/guides/preview/
is_root: false
weight: 110
---


GroupDocs.Watermark は、ドキュメントページを画像としてレンダリングできるため、ビューアでドキュメントを完全に開かずにページサムネイルを表示できます。各ページに書き込み可能なファイルストリームを提供する `create_page_stream` コールバックでレンダリングを制御します — ライブラリはページ画像を書き込み、ストリームを閉じます。

## Generate a document preview

`create_page_stream` コールバックを使用して [`PreviewOptions`](/watermark/python-net/groupdocs.watermark.options/previewoptions/) を設定し、`preview_format` を選択し、レンダリングする `page_numbers` をリストします。

{{< tabs \"code-example-preview\">}}
{{< tab \"generate_preview.py\" >}}
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options import PreviewOptions, PreviewFormats

def generate_preview():
    # 各ページをレンダリングするための書き込み可能なファイルストリームを提供します
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
{{< /tab >}}
{{< tab \"sample.pdf\" >}}

`sample.pdf` はこの例で使用される2ページのサンプルファイルです。ダウンロードするには、[ここ](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/preview/sample.pdf) をクリックしてください。

{{< /tab >}}
{{< tab \"generate-preview-outputs.zip\" >}}
```text
output-page-1.png (600 KB)
output-page-2.png (94 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/preview/generate_preview/generate-preview-outputs.zip)
{{< /tab >}}
{{< /tabs >}}

ページ画像は現在のディレクトリに書き込まれます — 要求されたページごとに1つの PNG が生成されます。他の形式には `PreviewFormats.JPEG` または `PreviewFormats.BMP` を使用し、`options.width` / `options.height` を設定してレンダリングサイズを制御します。

ライブラリは、ページが書き込まれた後に `create_page_stream` が返す各ファイルを閉じます。ページが準備でき次第処理したい場合は、2つ目のコールバックを渡します：`PreviewOptions(create_page_stream, release_page_stream)` は、ページ全体の画像が書き込まれた後に、`create_page_stream` がそのページ用に返したオブジェクトと共に `release_page_stream(page_number, stream)` を呼び出します。引数が1つの `release_page_stream(page_number)` でも動作します。`create_page_stream` は `io.BytesIO` を返すこともでき、ストリームは開いたままで、`release_page_stream` が取得する時点でページ画像を保持しています。

**Use case:** Generate page previews to display in a web app, dashboard, or document-management system without requiring users to download the full file.
