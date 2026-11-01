---
title: "__init__ コンストラクタ"
second_title: "GroupDocs.Watermark for Python via .NET API リファレンス"
description: "PagesSetup クラスの新しいインスタンスを初期化します。"
type: docs
url: /ja/python-net/groupdocs.watermark.watermarks/pagessetup/__init__/
is_root: false
weight: 10
---


## __init__

[`PagesSetup`](/watermark/python-net/groupdocs.watermark.watermarks/pagessetup/) クラスの新しいインスタンスを初期化します。

```python
def __init__(self):
    ...
```

## __init__ {#all_pages-first_page-last_page-odd_pages-even_pages-pages-page_number}

指定されたパラメーターで新しい PagesSetup インスタンスを初期化します。

```python
def __init__(self, all_pages, first_page, last_page, odd_pages, even_pages, pages, page_number):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| all_pages | `bool` | すべてのページを含めるかどうか。 |
| first_page | `bool` | 最初のページを含めるかどうか。 |
| last_page | `bool` | 最後のページを含めるかどうか。 |
| odd_pages | `bool` | 奇数ページを含めるかどうか。 |
| even_pages | `bool` | 偶数ページを含めるかどうか。 |
| pages | `List[int]` | 含める特定のページ番号のリスト。 |
| page_number | `Optional[int]` | 現在のページのインデックス。 |

### 関連項目
* class [`PagesSetup`](/watermark/python-net/groupdocs.watermark.watermarks/pagessetup/)
