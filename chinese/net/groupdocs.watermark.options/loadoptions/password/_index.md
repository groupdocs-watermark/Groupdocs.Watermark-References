---
title: "Password"
second_title: "GroupDocs.Watermark 的 .NET API 参考"
description: "获取或设置打开加密文档的密码。"
type: docs
weight: 50
url: /zh/net/groupdocs.watermark.options/loadoptions/password/
---
## LoadOptions.Password property

获取或设置打开加密文档的密码。

```csharp
public string Password { get; set; }
```

### Property Value

打开加密文档的密码。

### 备注

密码可以为 null 或空字符串。默认值为 null。如果内容未加密，请将其设置为 null 或空字符串。

### 示例

加载受密码保护的内容。

```csharp
LoadOptions loadOptions = new LoadOptions
{
    Password = "pwd123"
};
using (Watermarker watermarker = new Watermarker(@"D:\doc.vsdx", loadOptions))
{
    // ...
}
```

### 另请参阅

* class [LoadOptions](../../loadoptions)
* namespace [GroupDocs.Watermark.Options](../../../groupdocs.watermark.options)
* assembly [GroupDocs.Watermark](../../../)

<!-- 请勿编辑：由 xmldoccmd 为 GroupDocs.watermark.dll 生成 -->
