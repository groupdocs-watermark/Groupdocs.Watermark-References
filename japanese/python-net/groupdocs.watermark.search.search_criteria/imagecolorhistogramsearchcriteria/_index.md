---
title: "ImageColorHistogramSearchCriteria クラス"
second_title: "GroupDocs.Watermark for Python via .NET API リファレンス"
description: "コンテンツ内の画像を検索するための検索条件を表します。"
type: docs
url: /ja/python-net/groupdocs.watermark.search.search_criteria/imagecolorhistogramsearchcriteria/
is_root: false
weight: 30
---


## ImageColorHistogramSearchCriteria class

コンテンツ内の画像を検索するための検索条件を表します。

この検索基準は画像の類似性計算に画像カラー ヒストグラムを使用します。

ImageColorHistogramSearchCriteria 型は以下のメンバーを公開します：

### コンストラクタ
| コンストラクタ | 説明 |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.search.search_criteria/imagecolorhistogramsearchcriteria/__init__/#file_path) | 指定されたファイルパスで ImageColorHistogramSearchCriteria の新しいインスタンスを初期化します。 |
| [__init__](/watermark/python-net/groupdocs.watermark.search.search_criteria/imagecolorhistogramsearchcriteria/__init__/#stream) | 指定されたストリームで ImageColorHistogramSearchCriteria の新しいインスタンスを初期化します。 |

### メソッド
| メソッド | 説明 |
| :- | :- |
| [and_](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/and_/) | この SearchCriteria を他の基準と論理 AND 演算子で結合します。（[`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/) から継承） |
| [and_search_criteria](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/and_search_criteria/) | （[`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/) から継承） |
| [not_](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/not_/) | この SearchCriteria を否定します。（[`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/) から継承） |
| [or_](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/or_/) | この SearchCriteria を他の基準と論理 OR 演算子で結合します。（[`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/) から継承） |
| [or_search_criteria](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/or_search_criteria/) | （[`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/) から継承） |

### プロパティ
| プロパティ | 説明 |
| :- | :- |
| [bins_count](/watermark/python-net/groupdocs.watermark.search.search_criteria/imagecolorhistogramsearchcriteria/bins_count/) | カラー ヒストグラムの構築に使用されるビンの数です。 |
| [max_difference](/watermark/python-net/groupdocs.watermark.search.search_criteria/imagesearchcriteria/max_difference/) | 画像間で許容される最大差異です。（[`ImageSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/imagesearchcriteria/) から継承） |
| [pages](/watermark/python-net/groupdocs.watermark.search.search_criteria/pagesearchcriteria/pages/) | 特定のページ番号のリストです。（[`PageSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/pagesearchcriteria/) から継承） |

### 関連項目
* module [`groupdocs.watermark.search.search_criteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/)
