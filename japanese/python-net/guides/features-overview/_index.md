---
title: "機能概要"
linkTitle: "Features overview"
second_title: "GroupDocs.Watermark for Python via .NET API リファレンス"
description: "GroupDocs.Watermark for Python via .NET は、単一のフォーマット非依存 API を通じてテキストおよび画像の透かしを追加、検索、削除します — フォーマット固有の配置、コンテンツツリーの編集、ロック、ラスタライズをサポートします。"
type: docs
url: /ja/python-net/guides/features-overview/
is_root: false
weight: 30
---


GroupDocs.Watermark for Python via .NET は、幅広い [supported document formats](https://docs.groupdocs.com/watermark/python-net/supported-document-formats/) にわたって透かしの追加、検索、削除を行います。すべての操作は同じワークフローに従います：[`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/) でドキュメントを開き、`add()`、`search()`、または `remove()` を呼び出し、最後に `save()` で元の形式に保存します。以下の機能は単一のパスで自由に組み合わせて使用できます。

## Text and image watermarks

フォント、色、不透明度、回転、配置、サイズをフルコントロールして、スタイル化されたテキストまたは画像の透かしを追加します。画像透かしはファイルまたはストリームから読み込むことができます。[Add text watermarks](/watermark/python-net/guides/add-text/) と [Add image watermarks](/watermark/python-net/guides/add-image/) を参照してください。

## Customization and tiling

透かしを絶対座標または親相対の配置と余白で位置決めし、ページに対してスケールし、回転させ、全ページに繰り返しパターンでタイル配置できます。[Customize watermarks](/watermark/python-net/guides/customize/)、[Adding repeated watermarks](/watermark/python-net/guides/adding-repeated-watermarks/)、および [Adding text watermarks](https://docs.groupdocs.com/watermark/python-net/adding-text-watermarks/) を参照してください。

## Format-specific placement

各フォーマットに適したオプションを使用して透かしを配置します — PDF のアーティファクト、注釈、印刷専用注釈；プレゼンテーションのスライド、マスター、レイアウト、ノート；スプレッドシートのワークシート、背景、ヘッダー/フッター；Visio ページ；およびロックされた Word のセクションやページ。[Add watermarks to PDF documents](https://docs.groupdocs.com/watermark/python-net/add-watermarks-to-pdf-documents/) と [Developer Guide](https://docs.groupdocs.com/watermark/python-net/adding-watermarks/) の他のフォーマットトピックをご覧ください。

## Searching, modifying, and removing

ドキュメント内に既に存在する透かし（サードパーティツールで追加されたものも含む）を、正確なテキスト、正規表現、画像類似度、またはテキスト書式で検索し、条件を `and_`/`or_`/`not_` で組み合わせます。見つかったらテキストまたは画像を置換するか、削除します。[Searching watermarks](/watermark/python-net/guides/searching-watermarks/)、[Modifying found watermark properties](https://docs.groupdocs.com/watermark/python-net/modifying-found-watermark-properties/)、および [Removing found watermarks](https://docs.groupdocs.com/watermark/python-net/removing-found-watermarks/) を参照してください。

## Working with existing content

`Watermarker.get_content()` はフォーマット固有のコンテンツツリーを公開し、既存のシェイプ、PDF XObjects/アーティファクト/注釈、添付ファイル、背景、ヘッダー/フッターを検査・編集できます。また、`get_images()` を使用してドキュメント内に埋め込まれた画像に透かしを付けることも可能です。[Adding watermark to images inside a document](https://docs.groupdocs.com/watermark/python-net/adding-watermark-to-images-inside-a-document/) を参照してください。

## Tamper resistance

透かしをロックしたり、Word ドキュメントを保護したり、印刷専用 PDF 注釈を追加したり、PDF ページをラスタライズすることで、透かしを削除しにくくします。[Locking watermark in word processing document](https://docs.groupdocs.com/watermark/python-net/locking-watermark-in-word-processing-document/) と [Rasterize document or page](https://docs.groupdocs.com/watermark/python-net/rasterize-document-or-page/) をご覧ください。

## Document inspection

ドキュメントを変更せずにファイルタイプ、ページ数、サイズを取得し、ライブラリがサポートするすべてのファイル形式を一覧表示します。[Get document info](/watermark/python-net/guides/get-document-info/) と [Get supported file formats](/watermark/python-net/guides/get-supported-file-formats/) を参照してください。

## On-premise

GroupDocs.Watermark for Python via .NET は完全に自社インフラ上で実行され、ドキュメントは環境から外部に出ません。パッケージはすべてを含む自己完結型の wheel で、Microsoft Office、OpenOffice、別個のランタイムをインストールする必要はありません。[System Requirements](https://docs.groupdocs.com/watermark/python-net/system-requirements/) でサポートされるプラットフォームとネイティブ依存関係をご確認ください。
