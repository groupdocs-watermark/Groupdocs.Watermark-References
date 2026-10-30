---
title: "FileType"
second_title: "GroupDocs.Watermark for .NET API 레퍼런스"
description: "파일 유형을 나타냅니다."
type: docs
weight: 40
url: /ko/net/groupdocs.watermark.common/filetype/
---
## FileType class

파일 유형을 나타냅니다.

```csharp
public sealed class FileType : IEquatable<FileType>
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [Extension](../../groupdocs.watermark.common/filetype/extension) { get; } | 파일 이름 접미사(마침표 "." 포함)를 가져옵니다. 예: ".doc". |
| [FileFormatName](../../groupdocs.watermark.common/filetype/fileformatname) { get; } | 파일 유형 이름을 가져옵니다. 예: "Microsoft Word Document". |
| [FormatFamily](../../groupdocs.watermark.common/filetype/formatfamily) { get; } | 포맷 계열을 가져옵니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| static [FromExtension](../../groupdocs.watermark.common/filetype/fromextension)(string) | 파일 확장자를 파일 유형에 매핑합니다. |
| [Equals](../../groupdocs.watermark.common/filetype/equals#equals)(FileType) | 현재 [`FileType`](../filetype) 가 지정된 [`FileType`](../filetype) 객체와 동일한지 확인합니다. |
| override [Equals](../../groupdocs.watermark.common/filetype/equals#equals_1)(object) | 현재 [`FileType`](../filetype)이 지정된 객체와 동일한지 여부를 결정합니다. |
| override [GetHashCode](../../groupdocs.watermark.common/filetype/gethashcode)() | 현재 [`FileType`](../filetype) 객체에 대한 해시 코드를 반환합니다. |
| override [ToString](../../groupdocs.watermark.common/filetype/tostring)() | 현재 객체를 나타내는 문자열을 반환합니다. |
| static [GetSupportedFileTypes](../../groupdocs.watermark.common/filetype/getsupportedfiletypes)() | 지원되는 파일 유형을 검색합니다. |
| [operator ==](../../groupdocs.watermark.common/filetype/op_equality) | 두 [`FileType`](../filetype) 객체가 동일한지 여부를 결정합니다. |
| [operator !=](../../groupdocs.watermark.common/filetype/op_inequality) | 두 [`FileType`](../filetype) 객체가 동일하지 않은지 여부를 결정합니다. |

## 필드

| 이름 | 설명 |
| --- | --- |
| static readonly [BMP](../../groupdocs.watermark.common/filetype/bmp) | 확장자가 .BMP인 파일은 비트맵 디지털 이미지를 저장하는 데 사용되는 Bitmap Image 파일을 나타냅니다. 이러한 이미지는 그래픽 어댑터와 독립적이며 장치 독립 비트맵(DIB) 파일 형식이라고도 합니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/image/bmp/)를 클릭하십시오. |
| static readonly [DOC](../../groupdocs.watermark.common/filetype/doc) | 확장자가 .doc인 파일은 Microsoft Word 또는 기타 워드 프로세서에서 생성된 문서를 바이너리 파일 형식으로 나타냅니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/word-processing/doc/)를 클릭하십시오. |
| static readonly [DOCM](../../groupdocs.watermark.common/filetype/docm) | DOCM 파일은 매크로를 실행할 수 있는 Microsoft Word 2007 이상에서 생성된 문서입니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/word-processing/docm/)를 클릭하십시오. |
| static readonly [DOCX](../../groupdocs.watermark.common/filetype/docx) | DOCX는 Microsoft Word 문서의 잘 알려진 형식입니다. 2007년 Microsoft Office 2007 출시와 함께 도입되었으며, 이 새로운 문서 형식의 구조는 순수 바이너리에서 XML과 바이너리 파일의 조합으로 변경되었습니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/word-processing/docx/)를 클릭하십시오. |
| static readonly [DOT](../../groupdocs.watermark.common/filetype/dot) | 확장자가 .DOT인 파일은 Microsoft Word에서 생성한 템플릿 파일로, 추가 DOC 또는 DOCX 파일을 생성하기 위한 사전 서식 설정을 포함합니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/word-processing/dot/)를 클릭하십시오. |
| static readonly [DOTM](../../groupdocs.watermark.common/filetype/dotm) | DOTM 확장자를 가진 파일은 Microsoft Word 2007 이상에서 생성된 템플릿 파일을 나타냅니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/word-processing/dotm/)를 클릭하십시오. |
| static readonly [DOTX](../../groupdocs.watermark.common/filetype/dotx) | DOTX 확장자를 가진 파일은 Microsoft Word에서 생성한 템플릿 파일로, 추가 DOCX 파일을 생성하기 위한 사전 서식 설정을 포함합니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/word-processing/dotx/)를 클릭하십시오. |
| static readonly [EML](../../groupdocs.watermark.common/filetype/eml) | EML 파일 형식은 Outlook 및 기타 관련 애플리케이션을 사용하여 저장된 이메일 메시지를 나타냅니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/email/eml/)를 클릭하십시오. |
| static readonly [EMLX](../../groupdocs.watermark.common/filetype/emlx) | EMLX 파일 형식은 Apple에서 구현 및 개발되었습니다. Apple Mail 애플리케이션은 이메일을 내보내기 위해 EMLX 파일 형식을 사용합니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/email/emlx/)를 클릭하십시오. |
| static readonly [FlatOpc](../../groupdocs.watermark.common/filetype/flatopc) | Office Open XML WordprocessingML은 ZIP 패키지(.xml) 대신 평면 XML 파일에 저장됩니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://en.wikipedia.org/wiki/Office_Open_XML)를 클릭하십시오. |
| static readonly [FlatOpcMacroEnabled](../../groupdocs.watermark.common/filetype/flatopcmacroenabled) | Office Open XML WordprocessingML 매크로 사용 문서는 ZIP 패키지(.xml) 대신 평면 XML 파일에 저장됩니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://en.wikipedia.org/wiki/Office_Open_XML)를 클릭하십시오. |
| static readonly [FlatOpcTemplate](../../groupdocs.watermark.common/filetype/flatopctemplate) | Office Open XML WordprocessingML 템플릿(매크로 없음)은 ZIP 패키지(.xml) 대신 평면 XML 파일에 저장됩니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://en.wikipedia.org/wiki/Office_Open_XML)를 클릭하십시오. |
| static readonly [FlatOpcTemplateMacroEnabled](../../groupdocs.watermark.common/filetype/flatopctemplatemacroenabled) | Office Open XML WordprocessingML 매크로 사용 템플릿은 ZIP 패키지(.xml) 대신 평면 XML 파일에 저장됩니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://en.wikipedia.org/wiki/Office_Open_XML)를 클릭하십시오. |
| static readonly [GIF](../../groupdocs.watermark.common/filetype/gif) | GIF(그래픽 교환 형식)는 고도로 압축된 이미지 유형입니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/image/gif/)를 클릭하십시오. |
| static readonly [JPEG](../../groupdocs.watermark.common/filetype/jpeg) | JPEG은 손실 압축 방식을 사용하여 저장되는 이미지 형식입니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/image/jpeg/)를 클릭하십시오. |
| static readonly [JPF](../../groupdocs.watermark.common/filetype/jpf) | JPEG 2000 (JPF)은 이미지 코딩 시스템이자 최첨단 이미지 압축 표준입니다. 웨이브릿 기술을 사용하여 설계된 JPEG 2000은 어떤 품질에서도 무손실 콘텐츠를 한 번에 코딩할 수 있습니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/image/jp2/)를 클릭하십시오. |
| static readonly [JPG](../../groupdocs.watermark.common/filetype/jpg) | JPEG은 손실 압축 방식을 사용하여 저장되는 이미지 형식입니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/image/jpeg/)를 클릭하십시오. |
| static readonly [JPM](../../groupdocs.watermark.common/filetype/jpm) | JPEG 2000 (JPM)은 이미지 코딩 시스템이자 최첨단 이미지 압축 표준입니다. 웨이브릿 기술을 사용하여 설계된 JPEG 2000은 어떤 품질에서도 무손실 콘텐츠를 한 번에 코딩할 수 있습니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/image/jp2/)를 클릭하십시오. |
| static readonly [JPX](../../groupdocs.watermark.common/filetype/jpx) | JPEG 2000 (JPX)은 이미지 코딩 시스템이자 최첨단 이미지 압축 표준입니다. 웨이브릿 기술을 사용하여 설계된 JPEG 2000은 어떤 품질에서도 무손실 콘텐츠를 한 번에 코딩할 수 있습니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/image/jp2/)를 클릭하십시오. |
| static readonly [MSG](../../groupdocs.watermark.common/filetype/msg) | MSG는 Microsoft Outlook 및 Exchange에서 이메일 메시지, 연락처, 약속 또는 기타 작업을 저장하는 파일 형식입니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/email/msg/)를 클릭하십시오. |
| static readonly [ODT](../../groupdocs.watermark.common/filetype/odt) | ODT 파일은 OpenDocument 텍스트 파일 형식을 기반으로 하는 워드 프로세싱 애플리케이션으로 만든 문서 유형입니다. 이러한 파일은 무료 OpenOffice Writer와 같은 워드 프로세서 애플리케이션으로 생성되며 텍스트, 이미지, 객체 및 스타일과 같은 콘텐츠를 포함할 수 있습니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/word-processing/odt/)를 클릭하십시오. |
| static readonly [OFT](../../groupdocs.watermark.common/filetype/oft) | .OFT 확장자는 Microsoft Outlook을 사용하여 만든 메시지 템플릿 파일을 나타냅니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/email/oft/)를 클릭하십시오. |
| static readonly [OOXML](../../groupdocs.watermark.common/filetype/ooxml) | Office Open XML 파일 (.ooxml)입니다. |
| static readonly [PDF](../../groupdocs.watermark.common/filetype/pdf) | Portable Document Format (PDF)은 1990년대 Adobe에서 만든 문서 유형입니다. 이 파일 형식의 목적은 애플리케이션 소프트웨어, 하드웨어 및 운영 체제와 무관하게 문서 및 기타 참고 자료를 표현하기 위한 표준을 도입하는 것이었습니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/view/pdf/)를 클릭하십시오. |
| static readonly [PNG](../../groupdocs.watermark.common/filetype/png) | PNG, Portable Network Graphics는 무손실 압축을 사용하는 래스터 이미지 파일 형식입니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/image/png/)를 클릭하십시오. |
| static readonly [POTM](../../groupdocs.watermark.common/filetype/potm) | POTM 확장자는 매크로를 지원하는 Microsoft PowerPoint 템플릿 파일입니다. POTM 파일은 PowerPoint 2007 이상에서 생성되며 추가 프레젠테이션 파일을 만들 때 사용할 수 있는 기본 설정을 포함합니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/presentation/potm/)를 클릭하십시오. |
| static readonly [POTX](../../groupdocs.watermark.common/filetype/potx) | .POTX 확장자는 Microsoft PowerPoint 2007 이상에서 만든 Microsoft PowerPoint 템플릿 프레젠테이션을 나타냅니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/presentation/potx/)를 클릭하십시오. |
| static readonly [PPS](../../groupdocs.watermark.common/filetype/pps) | PPS, PowerPoint Slide Show 파일은 Microsoft PowerPoint를 사용하여 슬라이드 쇼 용도로 생성됩니다. PPS 파일의 읽기 및 생성은 Microsoft PowerPoint 97-2003에서 지원됩니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/presentation/pps/)를 클릭하십시오. |
| static readonly [PPSM](../../groupdocs.watermark.common/filetype/ppsm) | PPSM 확장자는 Microsoft PowerPoint 2007 이상에서 만든 매크로 지원 슬라이드 쇼 파일 형식을 나타냅니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/presentation/ppsm/)를 클릭하십시오. |
| static readonly [PPSX](../../groupdocs.watermark.common/filetype/ppsx) | PPSX, Power Point Slide Show 파일은 Microsoft PowerPoint 2007 이상에서 슬라이드 쇼 용도로 생성됩니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/presentation/ppsx/)를 클릭하십시오. |
| static readonly [PPT](../../groupdocs.watermark.common/filetype/ppt) | PPT 확장자를 가진 파일은 슬라이드 쇼로 표시되는 슬라이드 모음으로 구성된 PowerPoint 파일을 나타냅니다. 이는 Microsoft PowerPoint 97-2003에서 사용되는 이진 파일 형식을 지정합니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/presentation/ppt/)를 클릭하십시오. |
| static readonly [PPTM](../../groupdocs.watermark.common/filetype/pptm) | PPTM 확장자는 Microsoft PowerPoint 2007 이상 버전으로 만든 매크로 지원 프레젠테이션 파일입니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/presentation/pptm/)를 클릭하십시오. |
| static readonly [PPTX](../../groupdocs.watermark.common/filetype/pptx) | PPTX 확장자는 널리 사용되는 Microsoft PowerPoint 애플리케이션으로 만든 프레젠테이션 파일입니다. 이전 이진 형식인 PPT와 달리, PPTX 형식은 Microsoft PowerPoint Open XML 프레젠테이션 파일 형식을 기반으로 합니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/presentation/pptx/)를 클릭하십시오. |
| static readonly [RTF](../../groupdocs.watermark.common/filetype/rtf) | Microsoft에서 도입하고 문서화한 Rich Text Format (RTF)은 애플리케이션 내에서 서식이 지정된 텍스트와 그래픽을 인코딩하는 방법을 나타냅니다. 이 형식은 다른 Microsoft 제품과의 교차 플랫폼 문서 교환을 용이하게 하여 상호 운용성을 제공합니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/word-processing/rtf/)를 클릭하십시오. |
| static readonly [TIF](../../groupdocs.watermark.common/filetype/tif) | TIFF 또는 TIF, Tagged Image File Format은 다양한 장치에서 이 파일 형식 표준을 준수하도록 사용되는 래스터 이미지를 나타냅니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/image/tiff/)를 클릭하십시오. |
| static readonly [TIFF](../../groupdocs.watermark.common/filetype/tiff) | TIFF 또는 TIF, Tagged Image File Format은 다양한 장치에서 이 파일 형식 표준을 준수하도록 사용되는 래스터 이미지를 나타냅니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/image/tiff/)를 클릭하십시오. |
| static readonly [Unknown](../../groupdocs.watermark.common/filetype/unknown) | 알 수 없는 파일 형식을 나타냅니다. |
| static readonly [VDW](../../groupdocs.watermark.common/filetype/vdw) | VDW는 웹 드로잉을 렌더링하는 데 필요한 스트림 및 스토리지를 지정하는 Visio Graphics Service 파일 형식입니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/web/vdw/)를 클릭하십시오. |
| static readonly [VDX](../../groupdocs.watermark.common/filetype/vdx) | Microsoft Visio에서 만든 모든 도면이나 차트가 XML 형식으로 저장된 경우 .VDX 확장자를 가집니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/image/vdx/)를 클릭하십시오. |
| static readonly [VSD](../../groupdocs.watermark.common/filetype/vsd) | VSD 파일은 Microsoft Visio 애플리케이션으로 만든 도면으로, 다양한 그래픽 객체와 이들 간의 연결을 나타냅니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/image/vsd/)를 클릭하십시오. |
| static readonly [VSDM](../../groupdocs.watermark.common/filetype/vsdm) | VSDM 확장자는 매크로를 지원하는 Microsoft Visio 애플리케이션으로 만든 도면 파일입니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/image/vsdm/)를 클릭하십시오. |
| static readonly [VSDX](../../groupdocs.watermark.common/filetype/vsdx) | .VSDX 확장자는 Microsoft Office 2013 이후부터 도입된 Microsoft Visio 파일 형식을 나타냅니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/image/vsdx/)를 클릭하십시오. |
| static readonly [VSS](../../groupdocs.watermark.common/filetype/vss) | VSS는 Microsoft Visio 2007 및 이전 버전으로 만든 스텐실 파일입니다. 스텐실 파일은 .VSD Visio 도면에 포함될 수 있는 도면 객체를 제공합니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/image/vss/)를 클릭하십시오. |
| static readonly [VSSM](../../groupdocs.watermark.common/filetype/vssm) | .VSSM 확장자는 매크로를 지원하는 Microsoft Visio 스텐실 파일입니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/image/vssm/)를 클릭하십시오. |
| static readonly [VSSX](../../groupdocs.watermark.common/filetype/vssx) | .VSSX 확장자는 Microsoft Visio 2013 이상에서 만든 도면 스텐실입니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/image/vssx/)를 클릭하십시오. |
| static readonly [VST](../../groupdocs.watermark.common/filetype/vst) | VST 확장자를 가진 파일은 Microsoft Visio로 만든 벡터 이미지 파일이며, 추가 파일을 만들기 위한 템플릿 역할을 합니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/image/vst/). |
| static readonly [VSTM](../../groupdocs.watermark.common/filetype/vstm) | VSTM 확장자를 가진 파일은 매크로를 지원하는 Microsoft Visio로 만든 템플릿 파일입니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/image/vstm/). |
| static readonly [VSTX](../../groupdocs.watermark.common/filetype/vstx) | VSTX 확장자를 가진 파일은 Microsoft Visio 2013 이상에서 만든 도면 템플릿 파일입니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/image/vstx/). |
| static readonly [VSX](../../groupdocs.watermark.common/filetype/vsx) | .VSX 확장자를 가진 파일은 Microsoft Visio에서 다이어그램을 만들 때 사용되는 도면 및 도형으로 구성된 스텐실을 나타냅니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/image/vsx/). |
| static readonly [VTX](../../groupdocs.watermark.common/filetype/vtx) | VTX 확장자를 가진 파일은 XML 파일 형식으로 디스크에 저장된 Microsoft Visio 도면 템플릿입니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/image/vtx/). |
| static readonly [WEBP](../../groupdocs.watermark.common/filetype/webp) | WebP는 Google이 도입한 최신 래스터 웹 이미지 파일 형식으로, 손실 및 무손실 압축을 기반으로 합니다. 동일한 이미지 품질을 제공하면서 이미지 크기를 크게 줄여줍니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/image/webp/). |
| static readonly [XLS](../../groupdocs.watermark.common/filetype/xls) | XLS 확장자를 가진 파일은 Excel 이진 파일 형식을 나타냅니다. 이러한 파일은 Microsoft Excel뿐만 아니라 OpenOffice Calc 또는 Apple Numbers와 같은 유사한 스프레드시트 프로그램에서도 생성될 수 있습니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/specification/spreadsheet/xls/). |
| static readonly [XLSB](../../groupdocs.watermark.common/filetype/xlsb) | XLSB 파일 형식은 Excel 이진 파일 형식을 지정하며, 이는 Excel 워크북 내용을 정의하는 레코드와 구조의 모음입니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/specification/spreadsheet/xlsb/). |
| static readonly [XLSM](../../groupdocs.watermark.common/filetype/xlsm) | XLSM 확장자를 가진 파일은 매크로를 지원하는 스프레드시트 파일 유형입니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/specification/spreadsheet/xlsm/). |
| static readonly [XLSX](../../groupdocs.watermark.common/filetype/xlsx) | XLSX는 Microsoft Office 2007 출시와 함께 Microsoft가 도입한 Microsoft Excel 문서의 잘 알려진 형식입니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/specification/spreadsheet/xlsx/). |
| static readonly [XLT](../../groupdocs.watermark.common/filetype/xlt) | .XLT 확장자를 가진 파일은 Microsoft Office 제품군의 일부인 스프레드시트 애플리케이션 Microsoft Excel로 만든 템플릿 파일입니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/specification/spreadsheet/xlt/). |
| static readonly [XLTM](../../groupdocs.watermark.common/filetype/xltm) | XLTM 파일 확장자는 Microsoft Excel에서 매크로 사용이 가능한 템플릿 파일로 생성됩니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/specification/spreadsheet/xltm/). |
| static readonly [XLTX](../../groupdocs.watermark.common/filetype/xltx) | XLTX 확장자를 가진 파일은 Office OpenXML 파일 형식 사양을 기반으로 하는 Microsoft Excel 템플릿 파일을 나타냅니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/specification/spreadsheet/xltx/). |

### 비고

이 클래스는 **GroupDocs.Watermark**에서 지원하는 모든 파일 유형 목록을 가져오는 메서드를 제공합니다.**자세히 보기**

* [Supported Document Formats](https://docs.groupdocs.com/display/watermarknet/Supported+Document+Formats)
* [Get supported file formats](https://docs.groupdocs.com/display/watermarknet/Get+supported+file+formats)
* [Get document info](https://docs.groupdocs.com/display/watermarknet/Get+document+info)

### 또 보기

* namespace [GroupDocs.Watermark.Common](../../groupdocs.watermark.common)
* assembly [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.watermark.dll -->
