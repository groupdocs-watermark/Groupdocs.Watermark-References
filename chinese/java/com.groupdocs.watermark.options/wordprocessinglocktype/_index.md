---
title: "WordProcessingLockType"
second_title: "GroupDocs.Watermark for Java API Reference"
description: "指定 Word 文档中水印锁定类型。"
type: docs
weight: 68
url: /zh/java/com.groupdocs.watermark.options/wordprocessinglocktype/
---
**Inheritance:**
java.lang.Object
```
public final class WordProcessingLockType
```

指定 Word 文档中水印锁定类型。

## 字段

| 字段 | 描述 |
| --- | --- |
|  | [AllowOnlyRevisions](#AllowOnlyRevisions) | 用户只能向文档添加修订标记。 |
|
|  | [AllowOnlyComments](#AllowOnlyComments) | 用户只能修改文档中的注释。 |
|
|  | [AllowOnlyFormFields](#AllowOnlyFormFields) | 用户只能在文档的表单字段中输入数据。 |
|
|  | [ReadOnly](#ReadOnly) | 整个文档为只读。 |
|
|  | [ReadOnlyWithEditableContent](#ReadOnlyWithEditableContent) | 文档为只读，但除水印之外的所有内容均标记为可编辑。 |
|
|  | [NoLock](#NoLock) | 禁用水印和文档的任何锁定。 |
|
### AllowOnlyRevisions {#AllowOnlyRevisions}
```
public static final int AllowOnlyRevisions
```


用户只能向文档添加修订标记。


### AllowOnlyComments {#AllowOnlyComments}
```
public static final int AllowOnlyComments
```


用户只能修改文档中的注释。


### AllowOnlyFormFields {#AllowOnlyFormFields}
```
public static final int AllowOnlyFormFields
```


用户只能在文档的表单字段中输入数据。

<br />

*** ** * ** ***

文档被拆分为单页章节，并在每两个相邻内容章节之间添加带水印的锁定章节。

<br />



### ReadOnly {#ReadOnly}
```
public static final int ReadOnly
```


整个文档为只读。


### ReadOnlyWithEditableContent {#ReadOnlyWithEditableContent}
```
public static final int ReadOnlyWithEditableContent
```


文档为只读，但除水印之外的所有内容均标记为可编辑。


### NoLock {#NoLock}
```
public static final int NoLock
```


禁用水印和文档的任何锁定。


