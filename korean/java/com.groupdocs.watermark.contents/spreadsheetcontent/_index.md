---
title: "SpreadsheetContent"
second_title: "Java용 GroupDocs.Watermark API 레퍼런스"
description: "워터마크를 배치할 수 있는 Excel 문서를 나타냅니다."
type: docs
weight: 108
url: /ko/java/com.groupdocs.watermark.contents/spreadsheetcontent/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.ContentPart](../../com.groupdocs.watermark.contents/contentpart), [com.groupdocs.watermark.contents.Content](../../com.groupdocs.watermark.contents/content)

**All Implemented Interfaces:**
[com.groupdocs.watermark.internal.IEncryptable](../../com.groupdocs.watermark.internal/iencryptable)
```
public class SpreadsheetContent extends Content implements IEncryptable
```

워터마크를 배치할 수 있는 Excel 문서를 나타냅니다.

**Learn more:**

* [Add watermarks to spreadsheet documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+spreadsheet+documents)
* [Shapes in spreadsheet document](../https://docs.groupdocs.com/display/watermarkjava/Shapes+in+spreadsheet+document)
* [Working with spreadsheet document attachments](../https://docs.groupdocs.com/display/watermarkjava/Working+with+spreadsheet+document+attachments)
* [Working with worksheet backgrounds](../https://docs.groupdocs.com/display/watermarkjava/Working+with+worksheet+backgrounds)
* [Working with worksheet headers and footers](../https://docs.groupdocs.com/display/watermarkjava/Working+with+worksheet+headers+and+footers)

다음 예제는 지원되는 모든 유형의 Excel 콘텐츠를 로드하고 저장하는 방법을 보여줍니다.
>
> ````
> ```
>
>    SpreadsheetLoadOptions loadOptions = new SpreadsheetLoadOptions();
>    Watermarker watermarker = new Watermarker("D:\\input.xls", loadOptions);
>  
>    // Use add method to add watermark to a particular or all worksheets.
>  
>    // Save changes.
>    watermarker.save("D:\\output.xls");
>    watermarker.close();
>  
> ```
> ````


## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [SpreadsheetContent(StreamContainer stream, StrategyManager<Integer> strategyManager, FileFormatInfo fileFormatInfo, SpreadsheetLoadOptions spreadsheetLoadOptions, WatermarkerSettings watermarkerSettings)](#SpreadsheetContent-com.groupdocs.watermark.internal.StreamContainer-com.groupdocs.watermark.internal.StrategyManager-java.lang.Integer--com.aspose.cells.FileFormatInfo-com.groupdocs.watermark.options.SpreadsheetLoadOptions-com.groupdocs.watermark.WatermarkerSettings-) | <br /> |

|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getWorksheets()](#getWorksheets--) | 이 `[SpreadsheetContent](../../com.groupdocs.watermark.contents/spreadsheetcontent)`의 모든 워크시트 컬렉션을 가져옵니다. |
|
|  | [getAsposeCellsWorkbook()](#getAsposeCellsWorkbook--) | <br /> |

|
|  | [addWatermark(Watermark watermark, SpreadsheetShapeSettings shapeSettings, ISpreadsheetWatermarkEffects effects)](#addWatermark-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.options.SpreadsheetShapeSettings-com.groupdocs.watermark.options.ISpreadsheetWatermarkEffects-) | <br /> |

|
|  | [addWatermarkAsBackground(Watermark watermark, int backgroundWidth, int backgroundHeight)](#addWatermarkAsBackground-com.groupdocs.watermark.Watermark-int-int-) | <br /> |

|
|  | [addModernWordArtWatermark(TextWatermark watermark, SpreadsheetShapeSettings shapeSettings)](#addModernWordArtWatermark-com.groupdocs.watermark.watermarks.TextWatermark-com.groupdocs.watermark.options.SpreadsheetShapeSettings-) | <br /> |

|
|  | [addWatermarkIntoHeaderFooter(Watermark watermark)](#addWatermarkIntoHeaderFooter-com.groupdocs.watermark.Watermark-) | <br /> |

|
|  | [encrypt(String password)](#encrypt-java.lang.String-) | 콘텐츠를 암호화합니다. |
|
|  | [decrypt()](#decrypt--) | 문서를 복호화합니다. |
|
|  | [performSave(String filePath)](#performSave-java.lang.String-) | <br /> |

|
|  | [performSave(String filePath, SaveOptions saveOptions)](#performSave-java.lang.String-com.groupdocs.watermark.options.SaveOptions-) | <br /> |

|
|  | [performSave(OutputStream stream)](#performSave-java.io.OutputStream-) | <br /> |

|
|  | [performSave(OutputStream stream, SaveOptions saveOptions)](#performSave-java.io.OutputStream-com.groupdocs.watermark.options.SaveOptions-) | <br /> |

|
|  | [getDocumentInfo()](#getDocumentInfo--) | <br /> |

|
|  | [getFileType()](#getFileType--) | <br /> |

|
|  | [add(Watermark watermark, WatermarkOptions options)](#add-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.options.WatermarkOptions-) | <br /> |

|
|  | [generatePreview(PreviewOptions previewOptions)](#generatePreview-com.groupdocs.watermark.options.PreviewOptions-) | <br /> |

|
### SpreadsheetContent(StreamContainer stream, StrategyManager<Integer> strategyManager, FileFormatInfo fileFormatInfo, SpreadsheetLoadOptions spreadsheetLoadOptions, WatermarkerSettings watermarkerSettings) {#SpreadsheetContent-com.groupdocs.watermark.internal.StreamContainer-com.groupdocs.watermark.internal.StrategyManager-java.lang.Integer--com.aspose.cells.FileFormatInfo-com.groupdocs.watermark.options.SpreadsheetLoadOptions-com.groupdocs.watermark.WatermarkerSettings-}
```
public SpreadsheetContent(StreamContainer stream, StrategyManager<Integer> strategyManager, FileFormatInfo fileFormatInfo, SpreadsheetLoadOptions spreadsheetLoadOptions, WatermarkerSettings watermarkerSettings)
```


<br />



**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| stream | [StreamContainer](../../com.groupdocs.watermark.internal/streamcontainer) |  |
| strategyManager | com.groupdocs.watermark.internal.StrategyManager<java.lang.Integer> |  |
| fileFormatInfo | com.aspose.cells.FileFormatInfo |  |
| spreadsheetLoadOptions | [SpreadsheetLoadOptions](../../com.groupdocs.watermark.options/spreadsheetloadoptions) |  |
| watermarkerSettings | [WatermarkerSettings](../../com.groupdocs.watermark/watermarkersettings) |  |

### getWorksheets() {#getWorksheets--}
```
public final SpreadsheetWorksheetCollection getWorksheets()
```


이 `[SpreadsheetContent](../../com.groupdocs.watermark.contents/spreadsheetcontent)`의 모든 워크시트 컬렉션을 가져옵니다.


**Returns:**
[SpreadsheetWorksheetCollection](../../com.groupdocs.watermark.contents/spreadsheetworksheetcollection) - The collection of all worksheets of this `[SpreadsheetContent](../../com.groupdocs.watermark.contents/spreadsheetcontent)`.

### getAsposeCellsWorkbook() {#getAsposeCellsWorkbook--}
```
public final Workbook getAsposeCellsWorkbook()
```


<br />



**Returns:**
com.aspose.cells.Workbook
### addWatermark(Watermark watermark, SpreadsheetShapeSettings shapeSettings, ISpreadsheetWatermarkEffects effects) {#addWatermark-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.options.SpreadsheetShapeSettings-com.groupdocs.watermark.options.ISpreadsheetWatermarkEffects-}
```
public final void addWatermark(Watermark watermark, SpreadsheetShapeSettings shapeSettings, ISpreadsheetWatermarkEffects effects)
```


<br />



**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |
| shapeSettings | [SpreadsheetShapeSettings](../../com.groupdocs.watermark.options/spreadsheetshapesettings) |  |
| effects | [ISpreadsheetWatermarkEffects](../../com.groupdocs.watermark.options/ispreadsheetwatermarkeffects) |  |

### addWatermarkAsBackground(Watermark watermark, int backgroundWidth, int backgroundHeight) {#addWatermarkAsBackground-com.groupdocs.watermark.Watermark-int-int-}
```
public final void addWatermarkAsBackground(Watermark watermark, int backgroundWidth, int backgroundHeight)
```


<br />



**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |
| backgroundWidth | int |  |
| backgroundHeight | int |  |

### addModernWordArtWatermark(TextWatermark watermark, SpreadsheetShapeSettings shapeSettings) {#addModernWordArtWatermark-com.groupdocs.watermark.watermarks.TextWatermark-com.groupdocs.watermark.options.SpreadsheetShapeSettings-}
```
public final void addModernWordArtWatermark(TextWatermark watermark, SpreadsheetShapeSettings shapeSettings)
```


<br />



**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| watermark | [TextWatermark](../../com.groupdocs.watermark.watermarks/textwatermark) |  |
| shapeSettings | [SpreadsheetShapeSettings](../../com.groupdocs.watermark.options/spreadsheetshapesettings) |  |

### addWatermarkIntoHeaderFooter(Watermark watermark) {#addWatermarkIntoHeaderFooter-com.groupdocs.watermark.Watermark-}
```
public final void addWatermarkIntoHeaderFooter(Watermark watermark)
```


<br />



**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |

### encrypt(String password) {#encrypt-java.lang.String-}
```
public final void encrypt(String password)
```


콘텐츠를 암호화합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 비밀번호 | java.lang.String | 문서를 열 때 필요한 비밀번호입니다. |
|

### decrypt() {#decrypt--}
```
public final void decrypt()
```


문서를 복호화합니다.


### performSave(String filePath) {#performSave-java.lang.String-}
```
public void performSave(String filePath)
```


<br />



**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| filePath | java.lang.String |  |

### performSave(String filePath, SaveOptions saveOptions) {#performSave-java.lang.String-com.groupdocs.watermark.options.SaveOptions-}
```
public void performSave(String filePath, SaveOptions saveOptions)
```


<br />



**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| filePath | java.lang.String |  |
| saveOptions | [SaveOptions](../../com.groupdocs.watermark.options/saveoptions) |  |

### performSave(OutputStream stream) {#performSave-java.io.OutputStream-}
```
public void performSave(OutputStream stream)
```


<br />



**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 스트림 | java.io.OutputStream |  |

### performSave(OutputStream stream, SaveOptions saveOptions) {#performSave-java.io.OutputStream-com.groupdocs.watermark.options.SaveOptions-}
```
public void performSave(OutputStream stream, SaveOptions saveOptions)
```


<br />



**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 스트림 | java.io.OutputStream |  |
| saveOptions | [SaveOptions](../../com.groupdocs.watermark.options/saveoptions) |  |

### getDocumentInfo() {#getDocumentInfo--}
```
public IDocumentInfo getDocumentInfo()
```


<br />



**Returns:**
[IDocumentInfo](../../com.groupdocs.watermark.common/idocumentinfo)
### getFileType() {#getFileType--}
```
public FileType getFileType()
```


<br />



**Returns:**
[FileType](../../com.groupdocs.watermark.common/filetype)
### add(Watermark watermark, WatermarkOptions options) {#add-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.options.WatermarkOptions-}
```
public void add(Watermark watermark, WatermarkOptions options)
```


<br />



**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |
| options | [WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions) |  |

### generatePreview(PreviewOptions previewOptions) {#generatePreview-com.groupdocs.watermark.options.PreviewOptions-}
```
public void generatePreview(PreviewOptions previewOptions)
```


<br />



**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| previewOptions | [PreviewOptions](../../com.groupdocs.watermark.options/previewoptions) |  |

