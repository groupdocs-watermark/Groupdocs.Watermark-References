---
title: "set_license 方法"
second_title: "GroupDocs.Watermark 用于 Python via .NET API 参考"
description: "将 license 应用于当前进程。"
type: docs
url: /zh/python-net/groupdocs.watermark/license/set_license/
is_root: false
weight: 1010
---


## set_license {#license_source}

将 license 应用于当前进程。

```python
def set_license(self, license_source):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| license_source |  | 可以是指向 ``.lic`` 文件的字符串路径，或是可读取的类文件对象（file‑like object），该对象会产生许可证字节。类文件输入会先写入临时文件，然后再传递给桥接层。 |

| 引发 | 描述 |
| :- | :- |
| `TypeError` | 如果 ``license_source`` 既不是字符串路径，也不是可读取的类文件对象。 |

### 另请参见
* class [`License`](/watermark/python-net/groupdocs.watermark/license/)
