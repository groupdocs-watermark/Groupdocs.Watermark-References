---
title: "__init__ 생성자"
second_title: "Python용 .NET을 통한 GroupDocs.Watermark API 참조"
description: "사각형의 각 면에 특정 길이를 적용하여 새로운 Thickness 인스턴스를 초기화합니다."
type: docs
url: /ko/python-net/groupdocs.watermark.watermarks/thickness/__init__/
is_root: false
weight: 10
---


## __init__ {#left-right-top-bottom}

사각형의 각 면에 특정 길이를 적용하여 새로운 Thickness 인스턴스를 초기화합니다.

```python
def __init__(self, left, right, top, bottom):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| left | `float` | 사각형의 왼쪽 면에 대한 두께입니다. |
| right | `float` | 사각형의 오른쪽 면에 대한 두께입니다. |
| top | `float` | 사각형의 위쪽 면에 대한 두께입니다. |
| bottom | `float` | 사각형의 아래쪽 면에 대한 두께입니다. |

## __init__ {#uniform_length}

각 면에 지정된 균일한 길이를 적용하여 새로운 Thickness 인스턴스를 초기화합니다.

```python
def __init__(self, uniform_length):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| uniform_length | `float` | 경계 사각형의 네 면 모두에 적용되는 균일한 길이입니다. |

### 또 보기
* class [`Thickness`](/watermark/python-net/groupdocs.watermark.watermarks/thickness/)
