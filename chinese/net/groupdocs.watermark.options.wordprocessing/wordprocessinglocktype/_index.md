---
title: "WordProcessingLockType"
second_title: "GroupDocs.Watermark 的 .NET API 参考"
description: "指定 Word 文档中水印的锁定类型。"
type: docs
weight: 2350
url: /zh/net/groupdocs.watermark.options.wordprocessing/wordprocessinglocktype/
---
## WordProcessingLockType enumeration

指定 Word 文档中水印的锁定类型。

```csharp
public enum WordProcessingLockType
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| AllowOnlyRevisions | `0` | 用户只能向文档添加修订标记。 |
| AllowOnlyComments | `1` | 用户只能修改文档中的批注。 |
| AllowOnlyFormFields | `2` | 用户只能在文档的表单字段中输入数据。 |
| ReadOnly | `3` | 整个文档为只读。 |
| ReadOnlyWithEditableContent | `4` | 文档为只读，但除水印之外的所有内容均标记为可编辑。 |
| NoLock | `-1` | 禁用对水印和文档的任何锁定。 |

### 另请参阅

* namespace [GroupDocs.Watermark.Options.WordProcessing](../../groupdocs.watermark.options.wordprocessing)
* assembly [GroupDocs.Watermark](../../)

<!-- 请勿编辑：由 xmldoccmd 为 GroupDocs.watermark.dll 生成 -->
