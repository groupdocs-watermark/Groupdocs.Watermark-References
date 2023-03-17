---
title: FileType
second_title: .NET API 참조용 GroupDocs.Watermark
description: 파일 형식을 나타냅니다.
type: docs
weight: 40
url: /ko/net/groupdocs.watermark.common/filetype/
---
## FileType class

파일 형식을 나타냅니다.

```csharp
public sealed class FileType : IEquatable<FileType>
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [Extension](../../groupdocs.watermark.common/filetype/extension) { get; } | 파일 이름 접미사(마침표 "." 포함)를 가져옵니다. 예: ".doc". |
| [FileFormatName](../../groupdocs.watermark.common/filetype/fileformatname) { get; } | "Microsoft Word 문서"와 같은 파일 형식 이름을 가져옵니다. |
| [FormatFamily](../../groupdocs.watermark.common/filetype/formatfamily) { get; } | 형식 제품군을 가져옵니다. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| static [FromExtension](../../groupdocs.watermark.common/filetype/fromextension)(string) | 파일 확장자를 파일 유형에 매핑합니다. |
| [Equals](../../groupdocs.watermark.common/filetype/equals#equals)(FileType) | 현재 여부를 결정합니다.[`FileType`](../filetype) 지정된 것과 동일합니다.[`FileType`](../filetype) object. |
| override [Equals](../../groupdocs.watermark.common/filetype/equals#equals_1)(object) | 현재 여부를 결정합니다.[`FileType`](../filetype) 지정된 개체와 동일합니다. |
| override [GetHashCode](../../groupdocs.watermark.common/filetype/gethashcode)() | 현재 해시 코드를 반환합니다.[`FileType`](../filetype) object. |
| override [ToString](../../groupdocs.watermark.common/filetype/tostring)() | 현재 개체를 나타내는 문자열을 반환합니다. |
| static [GetSupportedFileTypes](../../groupdocs.watermark.common/filetype/getsupportedfiletypes)() | 지원되는 파일 형식을 검색합니다. |
| [operator ==](../../groupdocs.watermark.common/filetype/op_equality) | 여부를 결정합니다.[`FileType`](../filetype) 객체는 동일합니다. |
| [operator !=](../../groupdocs.watermark.common/filetype/op_inequality) | 여부를 결정합니다.[`FileType`](../filetype) 개체가 동일하지 않습니다. |

## 필드

| 이름 | 설명 |
| --- | --- |
| static readonly [BMP](../../groupdocs.watermark.common/filetype/bmp) | 확장자가 .BMP인 파일은 비트맵 디지털 이미지를 저장하는 데 사용되는 비트맵 이미지 파일을 나타냅니다. 이러한 이미지는 그래픽 어댑터와 독립적이며 DIB(장치 독립적 비트맵) 파일 형식이라고도 합니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/image/bmp/) . |
| static readonly [DOC](../../groupdocs.watermark.common/filetype/doc) | 확장자가 .doc인 파일은 Microsoft Word 또는 기타 워드 프로세싱 문서에서 생성된 이진 파일 형식의 문서를 나타냅니다. 이 파일 형식에 대해 자세히 알아보기 [여기](https://wiki.fileformat.com/word-processing/doc/) . |
| static readonly [DOCM](../../groupdocs.watermark.common/filetype/docm) | DOCM 파일은 매크로 실행 기능이 있는 Microsoft Word 2007 이상에서 생성된 문서입니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/word-processing/docm/) . |
| static readonly [DOCX](../../groupdocs.watermark.common/filetype/docx) | DOCX는 Microsoft Word 문서의 잘 알려진 형식입니다. 2007년 Microsoft Office 2007의 release 와 함께 도입된 이 새로운 문서 형식의 구조는 일반 binary 에서 XML과 이진 파일의 조합으로 변경되었습니다. 이 파일 형식에 대해 자세히 알아보기 [여기](https://wiki.fileformat.com/word-processing/docx/) . |
| static readonly [DOT](../../groupdocs.watermark.common/filetype/dot) | 확장자가 .DOT인 파일은 추가 DOC 또는 DOCX 파일 생성을 위해 미리 형식이 지정된 settings 를 갖도록 Microsoft Word에서 만든 템플릿 파일입니다. 이 파일 형식에 대해 자세히 알아보기 [여기](https://wiki.fileformat.com/word-processing/dot/) . |
| static readonly [DOTM](../../groupdocs.watermark.common/filetype/dotm) | 확장자가 DOTM인 파일은 Microsoft Word 2007 이상에서 만든 템플릿 파일을 나타냅니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/word-processing/dotm/) . |
| static readonly [DOTX](../../groupdocs.watermark.common/filetype/dotx) | DOTX 확장자를 가진 파일은 추가 DOCX 파일 생성을 위해 미리 형식이 지정된 settings 를 갖도록 Microsoft Word에서 만든 템플릿 파일입니다. 이 파일 형식에 대해 자세히 알아보기 [여기](https://wiki.fileformat.com/word-processing/dotx/) . |
| static readonly [EML](../../groupdocs.watermark.common/filetype/eml) | EML 파일 형식은 Outlook 및 기타 관련 응용 프로그램을 사용하여 저장된 이메일 메시지를 나타냅니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/email/eml/) . |
| static readonly [EMLX](../../groupdocs.watermark.common/filetype/emlx) | EMLX 파일 형식은 Apple에서 구현하고 개발합니다. Apple Mail 애플리케이션은 이메일 내보내기에 EMLX 파일 형식을 사용합니다. 이 파일 형식에 대해 자세히 알아보기 [여기](https://wiki.fileformat.com/email/emlx/) . |
| static readonly [FlatOpc](../../groupdocs.watermark.common/filetype/flatopc) | ZIP 패키지(.xml) 대신 플랫 XML 파일에 저장된 Office Open XML WordprocessingML. 이 파일 형식에 대해 자세히 알아보기[여기](https://en.wikipedia.org/wiki/Office_Open_XML) . |
| static readonly [FlatOpcMacroEnabled](../../groupdocs.watermark.common/filetype/flatopcmacroenabled) | ZIP 패키지(.xml) 대신 플랫 XML 파일에 저장된 Office Open XML WordprocessingML 매크로 사용 문서. 이 파일 형식에 대해 자세히 알아보기[여기](https://en.wikipedia.org/wiki/Office_Open_XML) . |
| static readonly [FlatOpcTemplate](../../groupdocs.watermark.common/filetype/flatopctemplate) | ZIP 패키지(.xml) 대신 일반 XML 파일에 저장된 Office Open XML WordprocessingML 템플릿(매크로 없음). 이 파일 형식에 대해 자세히 알아보기[여기](https://en.wikipedia.org/wiki/Office_Open_XML) . |
| static readonly [FlatOpcTemplateMacroEnabled](../../groupdocs.watermark.common/filetype/flatopctemplatemacroenabled) | ZIP 패키지(.xml) 대신 일반 XML 파일에 저장된 Office Open XML WordprocessingML 매크로 사용 템플릿. 이 파일 형식에 대해 자세히 알아보기[여기](https://en.wikipedia.org/wiki/Office_Open_XML) . |
| static readonly [GIF](../../groupdocs.watermark.common/filetype/gif) | GIF 또는 그래픽 교환 형식은 고도로 압축된 이미지 유형입니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/image/gif/) . |
| static readonly [JPEG](../../groupdocs.watermark.common/filetype/jpeg) | JPEG는 손실 압축 방법을 사용하여 저장되는 이미지 형식 유형입니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/image/jpeg/) . |
| static readonly [JPF](../../groupdocs.watermark.common/filetype/jpf) | JPEG 2000(JPF)은 이미지 코딩 시스템이자 최신 이미지 압축 표준입니다. 설계 웨이블릿 기술 사용 JPEG 2000은 한 번에 모든 품질의 무손실 콘텐츠를 코딩할 수 있습니다. about 이 파일 형식 자세히 알아보기[여기](https://wiki.fileformat.com/image/jp2/) . |
| static readonly [JPG](../../groupdocs.watermark.common/filetype/jpg) | JPEG는 손실 압축 방법을 사용하여 저장되는 이미지 형식 유형입니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/image/jpeg/) . |
| static readonly [JPM](../../groupdocs.watermark.common/filetype/jpm) | JPEG 2000(JPM)은 이미지 코딩 시스템이자 최신 이미지 압축 표준입니다. 설계 웨이블릿 기술 사용 JPEG 2000은 한 번에 모든 품질의 무손실 콘텐츠를 코딩할 수 있습니다. about 이 파일 형식 자세히 알아보기[여기](https://wiki.fileformat.com/image/jp2/) . |
| static readonly [JPX](../../groupdocs.watermark.common/filetype/jpx) | JPEG 2000(JPX)은 이미지 코딩 시스템이자 최신 이미지 압축 표준입니다. 설계 웨이블릿 기술 사용 JPEG 2000은 한 번에 모든 품질의 무손실 콘텐츠를 코딩할 수 있습니다. about 이 파일 형식 자세히 알아보기[여기](https://wiki.fileformat.com/image/jp2/) . |
| static readonly [MSG](../../groupdocs.watermark.common/filetype/msg) | MSG는 Microsoft Outlook 및 Exchange에서 전자 메일 메시지, 연락처, 약속 또는 기타 작업을 저장하는 데 사용하는 파일 형식입니다. 이 파일 형식에 대해 자세히 알아보기 [여기](https://wiki.fileformat.com/email/msg/) . |
| static readonly [ODT](../../groupdocs.watermark.common/filetype/odt) | ODT 파일은 OpenDocument 텍스트 파일 형식을 기반으로 하는 워드 프로세싱 응용 프로그램으로 만든 문서 유형입니다. 이들은 무료 OpenOffice Writer와 같은 워드 프로세서 응용 프로그램으로 생성되며 는 텍스트, 이미지, 개체 및 스타일과 같은 콘텐츠를 저장할 수 있습니다. 이 파일 형식에 대해 자세히 알아보기 [여기](https://wiki.fileformat.com/word-processing/odt/) . |
| static readonly [OFT](../../groupdocs.watermark.common/filetype/oft) | 확장자가 .OFT인 파일은 Microsoft Outlook을 사용하여 만든 메시지 템플릿 파일을 나타냅니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/email/oft/) . |
| static readonly [OOXML](../../groupdocs.watermark.common/filetype/ooxml) | Office 열기 xml 파일(.ooxml). |
| static readonly [PDF](../../groupdocs.watermark.common/filetype/pdf) | PDF(Portable Document Format)는 Adobe에서 1990년대에 만든 문서 유형입니다. 이 파일 형식의 목적은 응용 프로그램 소프트웨어, 하드웨어 및 운영 체제와 독립적인 형식인 문서 및 기타 참조 자료를 표현하기 위한 표준을 도입하는 것이었습니다. 이 파일 형식에 대해 자세히 알아보기 [여기](https://wiki.fileformat.com/view/pdf/) . |
| static readonly [PNG](../../groupdocs.watermark.common/filetype/png) | PNG(이동식 네트워크 그래픽)는 무손실 압축을 사용하는 일종의 래스터 이미지 파일 형식을 나타냅니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/image/png/) . |
| static readonly [POTM](../../groupdocs.watermark.common/filetype/potm) | 확장자가 POTM인 파일은 매크로를 지원하는 Microsoft PowerPoint 템플릿 파일입니다. POTM 파일 은 PowerPoint 2007 이상에서 생성되며 추가 프레젠테이션 파일을 생성 하는 데 사용할 수 있는 기본 설정을 포함합니다. 이 파일 형식에 대해 자세히 알아보기 [여기](https://wiki.fileformat.com/presentation/potm/) . |
| static readonly [POTX](../../groupdocs.watermark.common/filetype/potx) | 확장자가 .POTX인 파일은 Microsoft PowerPoint 2007 이상에서 생성된 Microsoft PowerPoint 템플릿 프레젠테이션을 나타냅니다. 이 파일 형식에 대해 자세히 알아보기 [여기](https://wiki.fileformat.com/presentation/potx/) . |
| static readonly [PPS](../../groupdocs.watermark.common/filetype/pps) | PPS, PowerPoint 슬라이드 쇼, 파일은 슬라이드 쇼 목적으로 Microsoft PowerPoint를 사용하여 생성됩니다. PPS 파일 읽기 및 생성은 Microsoft PowerPoint 97-2003에서 지원됩니다. 이 파일 형식에 대해 자세히 알아보기 [여기](https://wiki.fileformat.com/presentation/pps/) . |
| static readonly [PPSM](../../groupdocs.watermark.common/filetype/ppsm) | 확장자가 PPSM인 파일은 Microsoft PowerPoint 2007 이상에서 만든 매크로 사용 슬라이드 쇼 파일 형식을 나타냅니다. 이 파일 형식에 대해 자세히 알아보기 [여기](https://wiki.fileformat.com/presentation/ppsm/) . |
| static readonly [PPSX](../../groupdocs.watermark.common/filetype/ppsx) | PPSX, Power Point Slide Show, 파일은 Microsoft PowerPoint 2007 이상을 사용하여 슬라이드 쇼 목적으로 생성됩니다. 이 파일 형식에 대해 자세히 알아보기 [여기](https://wiki.fileformat.com/presentation/ppsx/) . |
| static readonly [PPT](../../groupdocs.watermark.common/filetype/ppt) | PPT 확장자를 가진 파일은 슬라이드 쇼로 표시되는 용 슬라이드 모음으로 구성된 PowerPoint 파일을 나타냅니다. Microsoft PowerPoint 97-2003에서 사용하는 이진 파일 형식을 지정합니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/presentation/ppt/) . |
| static readonly [PPTM](../../groupdocs.watermark.common/filetype/pptm) | PPTM 확장자를 가진 파일은 Microsoft PowerPoint 2007 이상 버전으로 생성된 매크로 사용 프레젠테이션 파일입니다. 이 파일 형식에 대해 자세히 알아보기 [여기](https://wiki.fileformat.com/presentation/pptm/) . |
| static readonly [PPTX](../../groupdocs.watermark.common/filetype/pptx) | PPTX 확장자를 가진 파일은 널리 사용되는 Microsoft PowerPoint 응용 프로그램으로 만든 프레젠테이션 파일입니다. 바이너리인 이전 버전의 프레젠테이션 파일 형식 PPT와 달리 PPTX 형식은 Microsoft PowerPoint open XML 프레젠테이션 파일 형식을 기반으로 됩니다. 이 파일 형식에 대해 자세히 알아보기 [여기](https://wiki.fileformat.com/presentation/pptx/) . |
| static readonly [RTF](../../groupdocs.watermark.common/filetype/rtf) | Microsoft에서 도입하고 문서화한 RTF(서식 있는 텍스트 형식)는 응용 프로그램 내에서 사용하기 위한 인코딩 형식의 텍스트 및 그래픽 방법을 나타냅니다. 이 형식은 다른 Microsoft 제품과 플랫폼 간 document 교환을 용이하게 하여 상호 운용성을 제공합니다. about 이 파일 형식 자세히 알아보기[여기](https://wiki.fileformat.com/word-processing/rtf/) . |
| static readonly [TIF](../../groupdocs.watermark.common/filetype/tif) | TIFF 또는 TIF, Tagged Image File Format은 이 파일 형식 표준을 준수하는 다양한 장치에서 사용하기 위한 래스터 이미지를 나타냅니다. 이 파일 형식에 대해 자세히 알아보기 [여기](https://wiki.fileformat.com/image/tiff/) . |
| static readonly [TIFF](../../groupdocs.watermark.common/filetype/tiff) | TIFF 또는 TIF, Tagged Image File Format은 이 파일 형식 표준을 준수하는 다양한 장치에서 사용하기 위한 래스터 이미지를 나타냅니다. 이 파일 형식에 대해 자세히 알아보기 [여기](https://wiki.fileformat.com/image/tiff/) . |
| static readonly [Unknown](../../groupdocs.watermark.common/filetype/unknown) | 알 수 없는 파일 형식을 나타냅니다. |
| static readonly [VDW](../../groupdocs.watermark.common/filetype/vdw) | VDW는 웹 드로잉을 렌더링하는 에 필요한 스트림과 저장소를 지정하는 Visio Graphics Service 파일 형식입니다. 이 파일 형식에 대해 자세히 알아보기 [여기](https://wiki.fileformat.com/web/vdw/) . |
| static readonly [VDX](../../groupdocs.watermark.common/filetype/vdx) | Microsoft Visio에서 생성되었지만 XML 형식으로 저장된 모든 그림 또는 차트에는 .VDX 확장자가 있습니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/image/vdx/) . |
| static readonly [VSD](../../groupdocs.watermark.common/filetype/vsd) | VSD 파일은 다양한 그래픽 개체와 이들 간의 상호 연결을 나타내기 위해 Microsoft Visio 응용 프로그램으로 만든 도면입니다. 이 파일 형식에 대해 자세히 알아보기 [여기](https://wiki.fileformat.com/image/vsd/) . |
| static readonly [VSDM](../../groupdocs.watermark.common/filetype/vsdm) | 확장자가 VSDM인 파일은 매크로를 지원하는 Microsoft Visio 응용 프로그램으로 만든 도면 파일입니다. 이 파일 형식에 대해 자세히 알아보기 [여기](https://wiki.fileformat.com/image/vsdm/) . |
| static readonly [VSDX](../../groupdocs.watermark.common/filetype/vsdx) | 확장자가 .VSDX인 파일은 Microsoft Office 2013부터 도입된 Microsoft Visio 파일 형식을 나타냅니다. 이 파일 형식에 대해 자세히 알아보기 [여기](https://wiki.fileformat.com/image/vsdx/) . |
| static readonly [VSS](../../groupdocs.watermark.common/filetype/vss) | VSS는 Microsoft Visio 2007 및 이전 버전에서 만든 스텐실 파일입니다. 스텐실 파일은 .VSD Visio 드로잉에 포함될 수 있는 drawing 개체를 제공합니다. 이 파일 형식에 대해 자세히 알아보기 [여기](https://wiki.fileformat.com/image/vss/) . |
| static readonly [VSSM](../../groupdocs.watermark.common/filetype/vssm) | 확장자가 .VSSM인 파일은 매크로를 지원하는 Microsoft Visio 스텐실 파일입니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/image/vssm/) . |
| static readonly [VSSX](../../groupdocs.watermark.common/filetype/vssx) | 확장자가 .VSSX인 파일은 Microsoft Visio 2013 이상에서 만든 드로잉 스텐실입니다. 이 파일 형식에 대해 자세히 알아보기 [여기](https://wiki.fileformat.com/image/vssx/) . |
| static readonly [VST](../../groupdocs.watermark.common/filetype/vst) | VST 확장자가 있는 파일은 Microsoft Visio로 만든 벡터 이미지 파일이며 추가 파일을 만드는 의 템플릿 역할을 합니다. 이 파일 형식에 대해 자세히 알아보기 [여기](https://wiki.fileformat.com/image/vst/) . |
| static readonly [VSTM](../../groupdocs.watermark.common/filetype/vstm) | VSTM 확장자를 가진 파일은 매크로를 지원하는 Microsoft Visio로 만든 템플릿 파일입니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/image/vstm/) . |
| static readonly [VSTX](../../groupdocs.watermark.common/filetype/vstx) | 확장자가 VSTX인 파일은 Microsoft Visio 2013 이상에서 만든 도면 템플릿 파일입니다. 이 파일 형식에 대해 자세히 알아보기 [여기](https://wiki.fileformat.com/image/vstx/) . |
| static readonly [VSX](../../groupdocs.watermark.common/filetype/vsx) | 확장자가 .VSX인 파일은 Microsoft Visio에서 다이어그램을 생성하는 에 사용되는 도면 및 도형으로 구성된 스텐실을 나타냅니다. 이 파일 형식에 대해 자세히 알아보기 [여기](https://wiki.fileformat.com/image/vsx/) . |
| static readonly [VTX](../../groupdocs.watermark.common/filetype/vtx) | VTX 확장자를 가진 파일은 XML 파일 형식으로 디스크에 저장되는 Microsoft Visio 드로잉 템플릿입니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/image/vtx/) . |
| static readonly [WEBP](../../groupdocs.watermark.common/filetype/webp) | Google에서 소개한 WebP는 무손실 및 손실 압축을 기반으로 하는 최신 래스터 웹 이미지 파일 형식입니다. 이미지 크기를 상당히 줄이면서 동일한 이미지 품질을 제공합니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/image/webp/) . |
| static readonly [XLS](../../groupdocs.watermark.common/filetype/xls) | XLS 확장자를 가진 파일은 Excel 바이너리 파일 형식을 나타냅니다. 이러한 파일은 Microsoft Excel 뿐만 아니라 OpenOffice Calc 또는 Apple Numbers와 같은 기타 유사한 스프레드시트 프로그램으로 만들 수 있습니다. about 이 파일 형식 자세히 알아보기[여기](https://wiki.fileformat.com/specification/spreadsheet/xls/) . |
| static readonly [XLSB](../../groupdocs.watermark.common/filetype/xlsb) | XLSB 파일 형식은 Excel 통합 문서 내용을 지정하는 레코드 및 구조의 모음인 Excel 이진 파일 형식을 지정합니다. 이 파일 형식에 대해 자세히 알아보기 [여기](https://wiki.fileformat.com/specification/spreadsheet/xlsb/) . |
| static readonly [XLSM](../../groupdocs.watermark.common/filetype/xlsm) | 확장자가 XLSM인 파일은 매크로를 지원하는 스프레드시트 파일 유형입니다. 이 파일 형식에 대해 자세히 알아보기 [여기](https://wiki.fileformat.com/specification/spreadsheet/xlsm/) . |
| static readonly [XLSX](../../groupdocs.watermark.common/filetype/xlsx) | XLSX는 Microsoft Office 2007 릴리스 와 함께 Microsoft에서 도입한 잘 알려진 Microsoft Excel 문서 형식입니다. 이 파일 format 에 대해 자세히 알아보십시오.[여기](https://wiki.fileformat.com/specification/spreadsheet/xlsx/) . |
| static readonly [XLT](../../groupdocs.watermark.common/filetype/xlt) | 확장자가 .XLT인 파일은 Microsoft Office 제품군의 일부로 제공되는 스프레드시트 응용 프로그램인 Microsoft Excel로 만든 템플릿 파일입니다. 이 파일 형식에 대해 자세히 알아보기 [여기](https://wiki.fileformat.com/specification/spreadsheet/xlt/) . |
| static readonly [XLTM](../../groupdocs.watermark.common/filetype/xltm) | XLTM 파일 확장자는 Microsoft Excel에서 Macro-enabled 템플릿 파일로 생성된 파일을 나타냅니다. 이 파일 형식에 대해 자세히 알아보기 [여기](https://wiki.fileformat.com/specification/spreadsheet/xltm/) . |
| static readonly [XLTX](../../groupdocs.watermark.common/filetype/xltx) | XLTX 확장자를 가진 파일은 Office OpenXML 파일 형식 사양을 기반으로 하는 Microsoft Excel 템플릿 파일을 나타냅니다. 이 파일 형식에 대해 자세히 알아보기 [여기](https://wiki.fileformat.com/specification/spreadsheet/xltx/) . |

### 비고

이 클래스는 지원하는 모든 파일 유형 목록을 얻는 방법을 제공합니다.**GroupDocs.워터마크**.**더 알아보기**

* [지원되는 문서 형식](https://docs.groupdocs.com/display/watermarknet/Supported+Document+Formats)
* [지원되는 파일 형식 가져오기](https://docs.groupdocs.com/display/watermarknet/Get+supported+file+formats)
* [문서 정보 얻기](https://docs.groupdocs.com/display/watermarknet/Get+document+info)

### 또한보십시오

* 네임스페이스 [GroupDocs.Watermark.Common](../../groupdocs.watermark.common)
* 집회 [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->
