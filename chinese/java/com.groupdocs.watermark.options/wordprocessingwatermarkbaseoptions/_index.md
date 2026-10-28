---
title: "WordProcessingWatermarkBaseOptions"
second_title: "GroupDocs.Watermark for Java API Reference"
description: "用于向 Word 文档添加水印选项的基类。"
type: docs
weight: 73
url: /zh/java/com.groupdocs.watermark.options/wordprocessingwatermarkbaseoptions/
---
**Inheritance:**
java.lang.Object, `[com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions)`, `[com.groupdocs.watermark.options.WordProcessingWatermarkOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkoptions)`
```
public abstract class WordProcessingWatermarkBaseOptions extends WordProcessingWatermarkOptions
```

用于向 Word 文档添加水印选项的基类。

## 方法

| 方法 | 描述 |
| --- | --- |
|  | [isLocked()](#isLocked--) | 获取一个值，指示在 Word 中是否禁止编辑形状。 |
|
|  | [setLocked(boolean value)](#setLocked-boolean-) | 设置一个值，指示在 Word 中是否禁止编辑形状。 |
|
|  | [getLockType()](#getLockType--) | 获取水印锁定类型。 |
|
|  | [setLockType(int value)](#setLockType-int-) | 设置水印锁定类型。 |
|
|  | [getPassword()](#getPassword--) | 获取用于锁定水印的密码。 |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | 设置用于锁定水印的密码。 |
|
|  | [getName()](#getName--) | 获取形状的名称。 |
|
|  | [setName(String value)](#setName-java.lang.String-) | 设置形状的名称。 |
|
|  | [getAlternativeText()](#getAlternativeText--) | 获取将与形状关联的描述性（替代）文本。 |
|
|  | [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | 设置将与形状关联的描述性（替代）文本。 |
|
| [getEffects()](#getEffects--) |  |
| [setEffects(IWordProcessingWatermarkEffects value)](#setEffects-com.groupdocs.watermark.options.IWordProcessingWatermarkEffects-) |  |
### isLocked() {#isLocked--}
```
public final boolean isLocked()
```


获取一个值，指示在 Word 中是否禁止编辑形状。


**Returns:**
boolean - 如果该值为 true，则禁止编辑形状。默认情况下，该值为 false，形状可以在 Word 中编辑。

### setLocked(boolean value) {#setLocked-boolean-}
```
public final void setLocked(boolean value)
```


设置一个值，指示在 Word 中是否禁止编辑形状。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | boolean | 如果该值为 true，则形状编辑将被禁止。默认情况下，该值为 false，形状可以在 Word 中编辑。 |
|

### getLockType() {#getLockType--}
```
public final int getLockType()
```


获取水印锁定类型。


**Returns:**
int - 水印 `[WordProcessingLockType](../../com.groupdocs.watermark.options/wordprocessinglocktype)` 锁定类型。

### setLockType(int value) {#setLockType-int-}
```
public final void setLockType(int value)
```


设置水印锁定类型。

值 `[WordProcessingLockType.AllowOnlyFormFields](../../com.groupdocs.watermark.options/wordprocessinglocktype#AllowOnlyFormFields)` 不能与
类型为 `[WordProcessingHeaderFooter](../../com.groupdocs.watermark.contents/wordprocessingheaderfooter)` 的对象。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | value | int | 水印 `[WordProcessingLockType](../../com.groupdocs.watermark.options/wordprocessinglocktype)` 锁定类型。 |
|

### getPassword() {#getPassword--}
```
public final String getPassword()
```


获取用于锁定水印的密码。


**Returns:**
java.lang.String - 用于锁定水印的密码。

### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


设置用于锁定水印的密码。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | java.lang.String | 用于锁定水印的密码。 |
|

### getName() {#getName--}
```
public final String getName()
```


获取形状的名称。


**Returns:**
java.lang.String - 形状名称。

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


设置形状的名称。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | java.lang.String | 形状名称。 |
|

### getAlternativeText() {#getAlternativeText--}
```
public final String getAlternativeText()
```


获取将与形状关联的描述性（替代）文本。


**Returns:**
java.lang.String - 将与形状关联的描述性（替代）文本。

### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public final void setAlternativeText(String value)
```


设置将与形状关联的描述性（替代）文本。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | java.lang.String | 将与形状关联的描述性（替代）文本。 |
|

### getEffects() {#getEffects--}
```
public final IWordProcessingWatermarkEffects getEffects()
```




**Returns:**
[IWordProcessingWatermarkEffects](../../com.groupdocs.watermark.options/iwordprocessingwatermarkeffects)
### setEffects(IWordProcessingWatermarkEffects value) {#setEffects-com.groupdocs.watermark.options.IWordProcessingWatermarkEffects-}
```
public final void setEffects(IWordProcessingWatermarkEffects value)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IWordProcessingWatermarkEffects](../../com.groupdocs.watermark.options/iwordprocessingwatermarkeffects) |  |

