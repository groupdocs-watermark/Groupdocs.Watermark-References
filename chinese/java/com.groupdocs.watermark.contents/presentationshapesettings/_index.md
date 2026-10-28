---
title: "PresentationShapeSettings"
second_title: "GroupDocs.Watermark for Java API Reference"
description: "表示可应用于 PowerPoint 文档中形状水印的设置。"
type: docs
weight: 95
url: /zh/java/com.groupdocs.watermark.contents/presentationshapesettings/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.OfficeShapeSettings](../../com.groupdocs.watermark.contents/officeshapesettings)
```
public final class PresentationShapeSettings extends OfficeShapeSettings
```

表示可应用于 PowerPoint 文档中形状水印的设置。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [PresentationShapeSettings()](#PresentationShapeSettings--) | 初始化 `[PresentationShapeSettings](../../com.groupdocs.watermark.contents/presentationshapesettings)` 类的新实例。 |
|
## 字段

| 字段 | 描述 |
| --- | --- |
|  | [UnreadableCharacter](#UnreadableCharacter) | <br /> |

|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [isLocked()](#isLocked--) | 获取一个值，指示在 PowerPoint 中是否禁止编辑形状。 |
|
|  | [setLocked(boolean value)](#setLocked-boolean-) | 设置一个值，指示在 PowerPoint 中是否禁止编辑形状。 |
|
|  | [getProtectWithUnreadableCharacters()](#getProtectWithUnreadableCharacters--) | 获取一个值，指示文本水印字符是否与不可读字符混合。 |
|
|  | [setProtectWithUnreadableCharacters(boolean value)](#setProtectWithUnreadableCharacters-boolean-) | 设置一个值，指示文本水印字符是否与不可读字符混合。 |
|
### PresentationShapeSettings() {#PresentationShapeSettings--}
```
public PresentationShapeSettings()
```


初始化 `[PresentationShapeSettings](../../com.groupdocs.watermark.contents/presentationshapesettings)` 类的新实例。


### UnreadableCharacter {#UnreadableCharacter}
```
public static final char UnreadableCharacter
```


<br />



### isLocked() {#isLocked--}
```
public final boolean isLocked()
```


获取一个值，指示在 PowerPoint 中是否禁止编辑形状。


**Returns:**
布尔型 - `true` 表示禁止形状编辑，`false` 表示可以在 PowerPoint 中编辑形状。

### setLocked(boolean value) {#setLocked-boolean-}
```
public final void setLocked(boolean value)
```


设置一个值，指示在 PowerPoint 中是否禁止编辑形状。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | boolean | `true` 表示应禁止形状编辑，`false` 表示可以在 PowerPoint 中编辑形状。 |
|

### getProtectWithUnreadableCharacters() {#getProtectWithUnreadableCharacters--}
```
public final boolean getProtectWithUnreadableCharacters()
```


获取一个值，指示文本水印字符是否与不可读字符混合。

此保护仅在 `#isLocked().isLocked()` 返回 `true` 时适用。


**Returns:**
布尔型 - 一个指示文本水印字符是否与不可读字符混合的值。

### setProtectWithUnreadableCharacters(boolean value) {#setProtectWithUnreadableCharacters-boolean-}
```
public final void setProtectWithUnreadableCharacters(boolean value)
```


设置一个值，指示文本水印字符是否与不可读字符混合。

此保护仅在 `#isLocked().isLocked()` 返回 `true` 时适用。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | boolean | 指示文本水印字符是否与不可读字符混合的值。 |
|

