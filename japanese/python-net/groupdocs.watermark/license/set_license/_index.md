---
title: "set_license メソッド"
second_title: "GroupDocs.Watermark for Python via .NET API リファレンス"
description: "現在のプロセスにライセンスを適用します。"
type: docs
url: /ja/python-net/groupdocs.watermark/license/set_license/
is_root: false
weight: 1010
---


## set_license {#license_source}

現在のプロセスにライセンスを適用します。

```python
def set_license(self, license_source):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| license_source |  | ``.lic`` ファイルへの文字列パス、またはライセンスバイトを生成する読み取り可能なファイルライクオブジェクトのいずれかです。ファイルライク入力は、ブリッジに渡す前に一時ファイルに書き込まれます。 |

| 例外が発生 | 説明 |
| :- | :- |
| `TypeError` | ``license_source`` が文字列パスでも読み取り可能なファイルライクオブジェクトでもない場合。 |

### 関連項目
* class [`License`](/watermark/python-net/groupdocs.watermark/license/)
