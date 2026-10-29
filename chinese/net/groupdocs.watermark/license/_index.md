---
title: "License"
second_title: "GroupDocs.Watermark 的 .NET API 参考"
description: "提供对组件进行授权的方法。"
type: docs
weight: 1680
url: /zh/net/groupdocs.watermark/license/
---
## License class

提供对组件进行授权的方法。

```csharp
public sealed class License
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [License](license)() | 初始化 [`License`](../license) 类的新实例。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [SetLicense](../../groupdocs.watermark/license/setlicense#setlicense)(Stream) | 为组件授权。 |
| [SetLicense](../../groupdocs.watermark/license/setlicense#setlicense_1)(string) | 为组件授权。 |

### 备注

* More about licensing: [GroupDocs Licensing FAQ](https://purchase.groupdocs.com/faqs/licensing)
* More about **GroupDocs.Watermark** licensing: [Evaluation Limitations and Licensing](https://docs.groupdocs.com/display/watermarknet/Evaluation+Limitations+and+Licensing)

### 示例

此示例演示如何从本地文件设置许可证。

```csharp
// 初始化 License 类。
License license = new License();

// 设置 .lic 文件的路径。
license.SetLicense("C:\\GroupDocs.Watermark.lic");
```

### 另请参阅

* namespace [GroupDocs.Watermark](../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../)

<!-- 请勿编辑：由 xmldoccmd 为 GroupDocs.watermark.dll 生成 -->
