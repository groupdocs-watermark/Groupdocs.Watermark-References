---
title: "워터마커"
second_title: "GroupDocs.Watermark for .NET API 레퍼런스"
description: "지정된 문서 경로를 사용하여 Watermarkergroupdocs.watermark/watermarker 클래스의 새 인스턴스를 초기화합니다."
type: docs
weight: 10
url: /ko/net/groupdocs.watermark/watermarker/watermarker/
---
## Watermarker(string) {#constructor_4}

지정된 문서 경로를 사용하여 [`Watermarker`](../../watermarker) 클래스의 새 인스턴스를 초기화합니다.

```csharp
public Watermarker(string filePath)
```

| 매개변수 | Type | 설명 |
| --- | --- | --- |
| filePath | String | 문서를 로드할 파일 경로입니다. |

### 예외

| 예외 | 조건 |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | 제공된 문서 유형은 지원되지 않습니다. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | 제공된 비밀번호가 올바르지 않습니다. |

### 비고

문서 로드에 대해 자세히 알아보세요: [Loading documents](https://docs.groupdocs.com/display/watermarknet/Loading+documents).

### 예제

지원되는 모든 형식의 콘텐츠를 로드하고 저장합니다.

```csharp
// 파일에서 콘텐츠를 로드합니다.
using (Watermarker watermarker = new Watermarker("D:\\input.pdf"))
{
    // 워터마커 클래스를 사용하여 워터마크를 추가, 검색 또는 제거합니다.

    // 문서를 저장합니다.
    watermarker.Save("D:\\output.pdf");
}
```

### 또 보기

* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Watermarker(string, LoadOptions) {#constructor_5}

지정된 문서 경로와 로드 옵션을 사용하여 [`Watermarker`](../../watermarker) 클래스의 새 인스턴스를 초기화합니다.

```csharp
public Watermarker(string filePath, LoadOptions options)
```

| 매개변수 | Type | 설명 |
| --- | --- | --- |
| filePath | String | 문서를 로드할 파일 경로입니다. |
| 옵션 | LoadOptions | 문서를 로드할 때 사용할 추가 옵션입니다. |

### 예외

| 예외 | 조건 |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | 제공된 문서 유형은 지원되지 않습니다. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | 제공된 비밀번호가 올바르지 않습니다. |

### 비고

문서 로드에 대해 자세히 알아보세요: [Loading documents](https://docs.groupdocs.com/display/watermarknet/Loading+documents).

### 예제

비밀번호를 사용하여 암호화된 PDF 문서를 로드합니다.

```csharp
PdfLoadOptions loadOptions = new PdfLoadOptions();
loadOptions.Password = "123";
using (Watermarker watermarker = new Watermarker(@"C:\Documents\test.pdf", loadOptions))
{
    // ...
}
```

### 또 보기

* class [LoadOptions](../../../groupdocs.watermark.options/loadoptions)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Watermarker(string, WatermarkerSettings) {#constructor_7}

지정된 문서 경로와 설정으로 [`Watermarker`](../../watermarker) 클래스를 새 인스턴스로 초기화합니다.

```csharp
public Watermarker(string filePath, WatermarkerSettings settings)
```

| 매개변수 | Type | 설명 |
| --- | --- | --- |
| filePath | String | 문서를 로드할 파일 경로입니다. |
| 설정 | WatermarkerSettings | 로드된 문서를 작업할 때 사용할 추가 설정. |

### 예외

| 예외 | 조건 |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | 제공된 문서 유형은 지원되지 않습니다. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | 제공된 비밀번호가 올바르지 않습니다. |

### 비고

문서 로드에 대해 자세히 알아보세요: [Loading documents](https://docs.groupdocs.com/display/watermarknet/Loading+documents).

### 예제

검색 가능한 객체를 전역으로 설정합니다(그 이후에 로드되는 모든 문서에 적용).

```csharp
WatermarkerSettings settings = new WatermarkerSettings();
settings.SearchableObjects = new SearchableObjects
{
    WordProcessingSearchableObjects = WordProcessingSearchableObjects.Hyperlinks
                                    | WordProcessingSearchableObjects.Text,
    SpreadsheetSearchableObjects = SpreadsheetSearchableObjects.HeadersFooters,
    PresentationSearchableObjects = PresentationSearchableObjects.SlidesBackgrounds
                                  | PresentationSearchableObjects.Shapes,
    DiagramSearchableObjects = DiagramSearchableObjects.None,
    PdfSearchableObjects = PdfSearchableObjects.All
};

foreach (string file in Directory.GetFiles(@"D:\files"))
{
    using (Watermarker watermarker = new Watermarker(file, settings))
    {
        PossibleWatermarkCollection watermarks = watermarker.Search();

        // 찾은 워터마크를 처리하는 코드는 여기에서 작성합니다.
    }
}
```

### 또 보기

* class [WatermarkerSettings](../../watermarkersettings)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Watermarker(string, LoadOptions, WatermarkerSettings) {#constructor_6}

지정된 문서 경로, 로드 옵션 및 설정으로 [`Watermarker`](../../watermarker) 클래스를 새 인스턴스로 초기화합니다.

```csharp
public Watermarker(string filePath, LoadOptions options, WatermarkerSettings settings)
```

| 매개변수 | Type | 설명 |
| --- | --- | --- |
| filePath | String | 문서를 로드할 파일 경로입니다. |
| 옵션 | LoadOptions | 문서를 로드할 때 사용할 추가 옵션입니다. |
| 설정 | WatermarkerSettings | 로드된 문서를 작업할 때 사용할 추가 설정. |

### 예외

| 예외 | 조건 |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | 제공된 문서 유형은 지원되지 않습니다. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | 제공된 비밀번호가 올바르지 않습니다. |

### 비고

문서 로드에 대해 자세히 알아보세요: [Loading documents](https://docs.groupdocs.com/display/watermarknet/Loading+documents).

### 예제

이메일 메시지 본문/제목에서 특정 텍스트 조각을 찾습니다.

```csharp
WatermarkerSettings settings = new WatermarkerSettings();
settings.SearchableObjects = new SearchableObjects
{
    EmailSearchableObjects = EmailSearchableObjects.Subject
                           | EmailSearchableObjects.HtmlBody
                           | EmailSearchableObjects.PlainTextBody
};
EmailLoadOptions loadOptions = new EmailLoadOptions();
using (Watermarker watermarker = new Watermarker(@"D:\test.msg", loadOptions, settings))
{
    SearchCriteria criteria = new TextSearchCriteria("test", false);
    // 참고: 검색은 TextSearchCriteria 인스턴스를 Search 메서드에 전달할 때만 수행됩니다.
    PossibleWatermarkCollection watermarks = watermarker.Search(criteria);
    // 찾은 텍스트 조각을 제거합니다
    watermarks.Clear();
    // 변경 사항을 저장합니다
    watermarker.Save();
}
```

### 또 보기

* class [LoadOptions](../../../groupdocs.watermark.options/loadoptions)
* class [WatermarkerSettings](../../watermarkersettings)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Watermarker(Stream) {#constructor}

지정된 스트림으로 [`Watermarker`](../../watermarker) 클래스를 새 인스턴스로 초기화합니다.

```csharp
public Watermarker(Stream document)
```

| 매개변수 | Type | 설명 |
| --- | --- | --- |
| 문서 | Stream | 문서를 로드할 스트림입니다. |

### 예외

| 예외 | 조건 |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | 제공된 문서 유형은 지원되지 않습니다. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | 제공된 비밀번호가 올바르지 않습니다. |

### 비고

문서 로드에 대해 자세히 알아보세요 [Loading documents](https://docs.groupdocs.com/display/watermarknet/Loading+documents).

### 예제

지원되는 모든 형식의 문서를 로드하고 저장합니다.

```csharp
// 스트림에서 콘텐츠를 로드합니다.
using (FileStream inputStream = File.Open("D:\\input.pdf", FileMode.Open))
using (FileStream outputStream = File.Open("D:\\output.pdf", FileMode.Create))
using (Watermarker watermarker = new Watermarker(inputStream))
{
    // 워터마커 클래스를 사용하여 워터마크를 추가, 검색 또는 제거합니다.

    // 변경 사항을 저장합니다.
    watermarker.Save(outputStream);
}
```

### 또 보기

* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Watermarker(Stream, LoadOptions) {#constructor_1}

지정된 스트림 및 로드 옵션으로 [`Watermarker`](../../watermarker) 클래스를 새 인스턴스로 초기화합니다.

```csharp
public Watermarker(Stream document, LoadOptions options)
```

| 매개변수 | Type | 설명 |
| --- | --- | --- |
| 문서 | Stream | 문서를 로드할 스트림입니다. |
| 옵션 | LoadOptions | 문서를 로드할 때 사용할 추가 옵션입니다. |

### 예외

| 예외 | 조건 |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | 제공된 문서 유형은 지원되지 않습니다. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | 제공된 비밀번호가 올바르지 않습니다. |

### 비고

문서 로드에 대해 자세히 알아보세요 [Loading documents](https://docs.groupdocs.com/display/watermarknet/Loading+documents).

### 예제

비밀번호를 사용하여 암호화된 PDF 문서를 로드합니다

```csharp
PdfLoadOptions loadOptions = new PdfLoadOptions();
loadOptions.Password = "123";
using (FileStream fileStream = File.Open(@"C:\Documents\test.pdf", FileMode.Open))
using (Watermarker watermarker = new Watermarker(fileStream, loadOptions))
{
    // ...
}
```

### 또 보기

* class [LoadOptions](../../../groupdocs.watermark.options/loadoptions)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Watermarker(Stream, WatermarkerSettings) {#constructor_3}

지정된 스트림과 설정으로 [`Watermarker`](../../watermarker) 클래스를 새 인스턴스로 초기화합니다.

```csharp
public Watermarker(Stream document, WatermarkerSettings settings)
```

| 매개변수 | Type | 설명 |
| --- | --- | --- |
| 문서 | Stream | 문서를 로드할 스트림입니다. |
| 설정 | WatermarkerSettings | 로드된 문서를 작업할 때 사용할 추가 설정. |

### 예외

| 예외 | 조건 |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | 제공된 문서 유형은 지원되지 않습니다. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | 제공된 비밀번호가 올바르지 않습니다. |

### 비고

문서 로드에 대해 자세히 알아보세요 [Loading documents](https://docs.groupdocs.com/display/watermarknet/Loading+documents).

### 예제

검색 가능한 객체를 전역으로 설정합니다(그 이후에 로드되는 모든 문서에 적용).

```csharp
WatermarkerSettings settings = new WatermarkerSettings();
settings.SearchableObjects = new SearchableObjects
{
    WordProcessingSearchableObjects = WordProcessingSearchableObjects.Hyperlinks
                                    | WordProcessingSearchableObjects.Text,
    SpreadsheetSearchableObjects = SpreadsheetSearchableObjects.HeadersFooters,
    PresentationSearchableObjects = PresentationSearchableObjects.SlidesBackgrounds
                                  | PresentationSearchableObjects.Shapes,
    DiagramSearchableObjects = DiagramSearchableObjects.None,
    PdfSearchableObjects = PdfSearchableObjects.All
};

foreach (string file in Directory.GetFiles(@"D:\files"))
{
    using (FileStream fileStream = File.Open(file, FileMode.Open))
    using (Watermarker watermarker = new Watermarker(fileStream, settings))
    {
        PossibleWatermarkCollection watermarks = watermarker.Search();

        // 찾은 워터마크를 처리하는 코드는 여기에서 작성합니다.
    }
}
```

### 또 보기

* class [WatermarkerSettings](../../watermarkersettings)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Watermarker(Stream, LoadOptions, WatermarkerSettings) {#constructor_2}

지정된 스트림, 로드 옵션 및 설정으로 [`Watermarker`](../../watermarker) 클래스를 새 인스턴스로 초기화합니다.

```csharp
public Watermarker(Stream document, LoadOptions options, WatermarkerSettings settings)
```

| 매개변수 | Type | 설명 |
| --- | --- | --- |
| 문서 | Stream | 문서를 로드할 스트림입니다. |
| 옵션 | LoadOptions | 문서를 로드할 때 사용할 추가 옵션입니다. |
| 설정 | WatermarkerSettings | 로드된 문서를 작업할 때 사용할 추가 설정. |

### 예외

| 예외 | 조건 |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | 제공된 문서 유형은 지원되지 않습니다. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | 제공된 비밀번호가 올바르지 않습니다. |

### 비고

문서 로드에 대해 자세히 알아보세요 [Loading documents](https://docs.groupdocs.com/display/watermarknet/Loading+documents).

### 예제

이메일 메시지 본문/제목에서 특정 텍스트 조각을 찾습니다.

```csharp
WatermarkerSettings settings = new WatermarkerSettings();
settings.SearchableObjects = new SearchableObjects
{
    EmailSearchableObjects = EmailSearchableObjects.Subject
                           | EmailSearchableObjects.HtmlBody
                           | EmailSearchableObjects.PlainTextBody
};
EmailLoadOptions loadOptions = new EmailLoadOptions();
using (FileStream fileStream = File.Open(@"D:\test.msg", FileMode.Open))
using (Watermarker watermarker = new Watermarker(fileStream, loadOptions, settings))
{
    SearchCriteria criteria = new TextSearchCriteria("test", false);
    // 참고: 검색은 TextSearchCriteria 인스턴스를 Search 메서드에 전달할 때만 수행됩니다.
    PossibleWatermarkCollection watermarks = watermarker.Search(criteria);
    // 찾은 텍스트 조각을 제거합니다
    watermarks.Clear();
    // 변경 사항을 저장합니다
    watermarker.Save();
}
```

### 또 보기

* class [LoadOptions](../../../groupdocs.watermark.options/loadoptions)
* class [WatermarkerSettings](../../watermarkersettings)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.watermark.dll -->
