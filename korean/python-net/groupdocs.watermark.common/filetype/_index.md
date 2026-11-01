---
title: "FileType 클래스"
second_title: "Python용 .NET을 통한 GroupDocs.Watermark API 참조"
description: "파일 유형을 나타냅니다."
type: docs
url: /ko/python-net/groupdocs.watermark.common/filetype/
is_root: false
weight: 40
---


## FileType class

파일 유형을 나타냅니다.

[`GroupDocs.Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)가 지원하는 모든 파일 유형 목록을 얻는 메서드를 제공합니다.

FileType 유형은 다음 멤버를 노출합니다:

### 메서드
| 메서드 | 설명 |
| :- | :- |
| [equals](/watermark/python-net/groupdocs.watermark.common/filetype/equals/#other) | 현재 [`FileType`](/watermark/python-net/groupdocs.watermark.common/filetype/)가 지정된 [`FileType`](/watermark/python-net/groupdocs.watermark.common/filetype/) 객체와 동일한지 확인합니다. |
| [equals](/watermark/python-net/groupdocs.watermark.common/filetype/equals/#obj) | 현재 FileType이 지정된 객체와 동일한지 확인합니다. |
| [equals_file_type](/watermark/python-net/groupdocs.watermark.common/filetype/equals_file_type/) |  |
| [equals_object](/watermark/python-net/groupdocs.watermark.common/filetype/equals_object/) |  |
| [from_extension](/watermark/python-net/groupdocs.watermark.common/filetype/from_extension/#extension) | 파일 확장자를 파일 유형에 매핑합니다. |
| [get_hash_code](/watermark/python-net/groupdocs.watermark.common/filetype/get_hash_code/) | 현재 [`FileType`](/watermark/python-net/groupdocs.watermark.common/filetype/) 객체에 대한 해시 코드를 반환합니다. |
| [get_supported_file_types](/watermark/python-net/groupdocs.watermark.common/filetype/get_supported_file_types/) | 지원되는 파일 유형을 검색합니다. |
| [to_string](/watermark/python-net/groupdocs.watermark.common/filetype/to_string/) | 현재 객체를 나타내는 문자열을 반환합니다. |

### 속성
| 속성 | 설명 |
| :- | :- |
| [extension](/watermark/python-net/groupdocs.watermark.common/filetype/extension/) | 파일 이름 접미사(점 \".\" 포함) 예: \".doc\". |
| [file_format_name](/watermark/python-net/groupdocs.watermark.common/filetype/file_format_name/) | 파일 유형 이름, 예: \"Microsoft Word Document\". |
| [format_family](/watermark/python-net/groupdocs.watermark.common/filetype/format_family/) | 포맷 패밀리. |

### 필드
| 필드 | 설명 |
| :- | :- |
| [UNKNOWN](/watermark/python-net/groupdocs.watermark.common/filetype/unknown/) | 알 수 없는 파일 유형을 나타냅니다. |
| [OOXML](/watermark/python-net/groupdocs.watermark.common/filetype/ooxml/) | Office Open XML 파일 (.ooxml). |
| [VSD](/watermark/python-net/groupdocs.watermark.common/filetype/vsd/) | VSD 파일은 다양한 그래픽 객체와 이들 간의 연결을 나타내기 위해 Microsoft Visio 애플리케이션으로 만든 도면입니다. 여기에서 이 파일 형식에 대해 자세히 알아보세요. |
| [VSDX](/watermark/python-net/groupdocs.watermark.common/filetype/vsdx/) | .VSDX 확장자를 가진 파일은 Microsoft Office 2013 이후에 도입된 Microsoft Visio 파일 형식을 나타냅니다. 여기에서 이 파일 형식에 대해 자세히 알아보세요. |
| [VSS](/watermark/python-net/groupdocs.watermark.common/filetype/vss/) | VSS는 Microsoft Visio 2007 및 이전 버전으로 만든 스텐실 파일입니다. 스텐실 파일은 .VSD Visio 도면에 포함될 수 있는 그리기 객체를 제공합니다. 여기에서 이 파일 형식에 대해 자세히 알아보세요. |
| [VSSX](/watermark/python-net/groupdocs.watermark.common/filetype/vssx/) | .VSSX 확장자를 가진 파일은 Microsoft Visio 2013 이상에서 만든 도면 스텐실입니다. 여기에서 이 파일 형식에 대해 자세히 알아보세요. |
| [VSDM](/watermark/python-net/groupdocs.watermark.common/filetype/vsdm/) | VSDM 확장자를 가진 파일은 매크로를 지원하는 Microsoft Visio 애플리케이션으로 만든 도면 파일입니다. 여기에서 이 파일 형식에 대해 자세히 알아보세요. |
| [VST](/watermark/python-net/groupdocs.watermark.common/filetype/vst/) | VST 확장자를 가진 파일은 Microsoft Visio로 만든 벡터 이미지 파일이며, 추가 파일을 만들기 위한 템플릿 역할을 합니다. 여기에서 이 파일 형식에 대해 자세히 알아보세요. |
| [VSTX](/watermark/python-net/groupdocs.watermark.common/filetype/vstx/) | VSTX 확장자를 가진 파일은 Microsoft Visio 2013 이상에서 만든 도면 템플릿 파일입니다. 여기에서 이 파일 형식에 대해 자세히 알아보세요. |
| [VSTM](/watermark/python-net/groupdocs.watermark.common/filetype/vstm/) | VSTM 확장자를 가진 파일은 매크로를 지원하는 Microsoft Visio로 만든 템플릿 파일입니다. 여기에서 이 파일 형식에 대해 자세히 알아보세요. |
| [VSSM](/watermark/python-net/groupdocs.watermark.common/filetype/vssm/) | .VSSM 확장자를 가진 파일은 매크로를 지원하는 Microsoft Visio 스텐실 파일입니다. 여기에서 이 파일 형식에 대해 자세히 알아보세요. |
| [VSX](/watermark/python-net/groupdocs.watermark.common/filetype/vsx/) | .VSX 확장자를 가진 파일은 Microsoft Visio에서 다이어그램을 만들 때 사용되는 도면 및 도형으로 구성된 스텐실을 나타냅니다. 여기에서 이 파일 형식에 대해 자세히 알아보세요. |
| [VTX](/watermark/python-net/groupdocs.watermark.common/filetype/vtx/) | VTX 확장자를 가진 파일은 XML 파일 형식으로 디스크에 저장된 Microsoft Visio 도면 템플릿입니다. 여기에서 이 파일 형식에 대해 자세히 알아보세요. |
| [VDW](/watermark/python-net/groupdocs.watermark.common/filetype/vdw/) | VDW는 웹 도면을 렌더링하는 데 필요한 스트림 및 스토리지를 지정하는 Visio Graphics Service 파일 형식입니다. 여기에서 이 파일 형식에 대해 자세히 알아보세요. |
| [VDX](/watermark/python-net/groupdocs.watermark.common/filetype/vdx/) | Microsoft Visio에서 만든 모든 도면이나 차트가 XML 형식으로 저장되면 .VDX 확장자를 가집니다. 여기에서 이 파일 형식에 대해 자세히 알아보세요. |
| [MSG](/watermark/python-net/groupdocs.watermark.common/filetype/msg/) | MSG는 Microsoft Outlook 및 Exchange에서 이메일 메시지, 연락처, 약속 또는 기타 작업을 저장하는 데 사용하는 파일 형식입니다. 여기에서 이 파일 형식에 대해 자세히 알아보세요. |
| [EML](/watermark/python-net/groupdocs.watermark.common/filetype/eml/) | EML 파일 형식은 Outlook 및 기타 관련 애플리케이션을 사용하여 저장된 이메일 메시지를 나타냅니다. 이 파일 형식에 대해 자세히 알아보려면 여기에서 확인하십시오. |
| [EMLX](/watermark/python-net/groupdocs.watermark.common/filetype/emlx/) | EMLX 파일 형식은 Apple에서 구현 및 개발되었습니다. Apple Mail 애플리케이션은 이메일 내보내기에 EMLX 파일 형식을 사용합니다. 이 파일 형식에 대해 자세히 알아보려면 여기에서 확인하십시오. |
| [OFT](/watermark/python-net/groupdocs.watermark.common/filetype/oft/) | .OFT 확장자를 가진 파일은 Microsoft Outlook을 사용하여 만든 메시지 템플릿 파일을 나타냅니다. 이 파일 형식에 대해 자세히 알아보려면 여기에서 확인하십시오. |
| [TIF](/watermark/python-net/groupdocs.watermark.common/filetype/tif/) | TIFF 또는 TIF, Tagged Image File Format은 이 파일 형식 표준을 준수하는 다양한 장치에서 사용하도록 설계된 래스터 이미지를 나타냅니다. 이 파일 형식에 대해 자세히 알아보려면 여기에서 확인하십시오. |
| [TIFF](/watermark/python-net/groupdocs.watermark.common/filetype/tiff/) | TIFF 또는 TIF, Tagged Image File Format은 이 파일 형식 표준을 준수하는 다양한 장치에서 사용하도록 설계된 래스터 이미지를 나타냅니다. 이 파일 형식에 대해 자세히 알아보려면 여기에서 확인하십시오. |
| [JPG](/watermark/python-net/groupdocs.watermark.common/filetype/jpg/) | JPEG은 손실 압축 방식을 사용하여 저장되는 이미지 형식의 한 종류입니다. 이 파일 형식에 대해 자세히 알아보려면 여기에서 확인하십시오. |
| [JPEG](/watermark/python-net/groupdocs.watermark.common/filetype/jpeg/) | JPEG은 손실 압축 방식을 사용하여 저장되는 이미지 형식의 한 종류입니다. 이 파일 형식에 대해 자세히 알아보려면 여기에서 확인하십시오. |
| [PNG](/watermark/python-net/groupdocs.watermark.common/filetype/png/) | PNG, Portable Network Graphics는 무손실 압축을 사용하는 래스터 이미지 파일 형식의 한 종류를 의미합니다. 이 파일 형식에 대해 자세히 알아보려면 여기에서 확인하십시오. |
| [GIF](/watermark/python-net/groupdocs.watermark.common/filetype/gif/) | GIF 또는 Graphical Interchange Format은 고도로 압축된 이미지 형식입니다. 이 파일 형식에 대해 자세히 알아보려면 여기에서 확인하십시오. |
| [BMP](/watermark/python-net/groupdocs.watermark.common/filetype/bmp/) | .BMP 확장자를 가진 파일은 비트맵 디지털 이미지를 저장하는 비트맵 이미지 파일을 나타냅니다. 이러한 이미지는 그래픽 어댑터와 무관하며 디바이스 독립 비트맵(DIB) 파일 형식이라고도 합니다. 이 파일 형식에 대해 자세히 알아보려면 여기에서 확인하십시오. |
| [JPF](/watermark/python-net/groupdocs.watermark.common/filetype/jpf/) | JPEG 2000 (JPF)은 이미지 코딩 시스템이자 최첨단 이미지 압축 표준입니다. 웨이브렛 기술을 사용해 설계된 JPEG 2000은 손실 없는 콘텐츠를 한 번에 모든 품질로 코딩할 수 있습니다. 이 파일 형식에 대해 자세히 알아보려면 여기에서 확인하십시오. |
| [JPX](/watermark/python-net/groupdocs.watermark.common/filetype/jpx/) | JPEG 2000 (JPX)은 이미지 코딩 시스템이자 최첨단 이미지 압축 표준입니다. 웨이브렛 기술을 사용해 설계된 JPEG 2000은 손실 없는 콘텐츠를 한 번에 모든 품질로 코딩할 수 있습니다. 이 파일 형식에 대해 자세히 알아보려면 여기에서 확인하십시오. |
| [JPM](/watermark/python-net/groupdocs.watermark.common/filetype/jpm/) | JPEG 2000 (JPM)은 이미지 코딩 시스템이자 최첨단 이미지 압축 표준입니다. 웨이브렛 기술을 사용해 설계된 JPEG 2000은 손실 없는 콘텐츠를 한 번에 모든 품질로 코딩할 수 있습니다. 이 파일 형식에 대해 자세히 알아보려면 여기에서 확인하십시오. |
| [WEBP](/watermark/python-net/groupdocs.watermark.common/filetype/webp/) | WebP는 Google에서 도입한 현대적인 래스터 웹 이미지 파일 형식으로, 무손실 및 손실 압축을 기반으로 합니다. 동일한 이미지 품질을 제공하면서 이미지 크기를 크게 줄여줍니다. 이 파일 형식에 대해 자세히 알아보려면 여기에서 확인하십시오. |
| [PDF](/watermark/python-net/groupdocs.watermark.common/filetype/pdf/) | Portable Document Format(PDF)은 1990년대 Adobe에서 만든 문서 형식입니다. 이 파일 형식의 목적은 애플리케이션 소프트웨어, 하드웨어 및 운영 체제와 무관하게 문서 및 기타 참고 자료를 표현하기 위한 표준을 도입하는 것이었습니다. 이 파일 형식에 대해 자세히 알아보려면 여기에서 확인하십시오. |
| [PPT](/watermark/python-net/groupdocs.watermark.common/filetype/ppt/) | PPT 확장자를 가진 파일은 슬라이드쇼로 표시되는 슬라이드 모음으로 구성된 PowerPoint 파일을 나타냅니다. 이는 Microsoft PowerPoint 97-2003에서 사용되는 바이너리 파일 형식을 지정합니다. 이 파일 형식에 대해 자세히 알아보려면 여기에서 확인하십시오. |
| [PPTX](/watermark/python-net/groupdocs.watermark.common/filetype/pptx/) | PPTX 확장자를 가진 파일은 인기 있는 Microsoft PowerPoint 애플리케이션으로 만든 프레젠테이션 파일입니다. 이전 버전인 바이너리 PPT와 달리 PPTX 형식은 Microsoft PowerPoint Open XML 프레젠테이션 파일 형식을 기반으로 합니다. 이 파일 형식에 대해 자세히 알아보려면 여기에서 확인하십시오. |
| [PPS](/watermark/python-net/groupdocs.watermark.common/filetype/pps/) | PPS, PowerPoint Slide Show 파일은 슬라이드쇼 용도로 Microsoft PowerPoint를 사용해 생성됩니다. PPS 파일 읽기 및 생성은 Microsoft PowerPoint 97-2003에서 지원됩니다. 이 파일 형식에 대해 자세히 알아보려면 여기에서 확인하십시오. |
| [PPSX](/watermark/python-net/groupdocs.watermark.common/filetype/ppsx/) | PPSX, Power Point Slide Show 파일은 Microsoft PowerPoint 2007 이상을 사용해 슬라이드쇼 용도로 생성됩니다. 이 파일 형식에 대해 자세히 알아보려면 여기에서 확인하십시오. |
| [PPTM](/watermark/python-net/groupdocs.watermark.common/filetype/pptm/) | PPTM 확장자를 가진 파일은 Microsoft PowerPoint 2007 이상 버전으로 만든 매크로 사용 프레젠테이션 파일입니다. 이 파일 형식에 대해 자세히 알아보려면 여기에서 확인하십시오. |
| [POTX](/watermark/python-net/groupdocs.watermark.common/filetype/potx/) | .POTX 확장자를 가진 파일은 Microsoft PowerPoint 2007 이상으로 만든 PowerPoint 템플릿 프레젠테이션을 나타냅니다. 이 파일 형식에 대해 자세히 알아보려면 여기에서 확인하십시오. |
| [POTM](/watermark/python-net/groupdocs.watermark.common/filetype/potm/) | POTM 확장자를 가진 파일은 매크로를 지원하는 Microsoft PowerPoint 템플릿 파일입니다. POTM 파일은 PowerPoint 2007 이상으로 생성되며 추가 프레젠테이션 파일을 만들 때 사용할 수 있는 기본 설정을 포함합니다. 이 파일 형식에 대해 자세히 알아보려면 여기에서 확인하십시오. |
| [PPSM](/watermark/python-net/groupdocs.watermark.common/filetype/ppsm/) | PPSM 확장자를 가진 파일은 Microsoft PowerPoint 2007 이상으로 만든 매크로 사용 슬라이드쇼 파일 형식입니다. 이 파일 형식에 대해 자세히 알아보려면 여기에서 확인하십시오. |
| [XLS](/watermark/python-net/groupdocs.watermark.common/filetype/xls/) | XLS 확장자를 가진 파일은 Excel 바이너리 파일 형식을 나타냅니다. 이러한 파일은 Microsoft Excel뿐만 아니라 OpenOffice Calc 또는 Apple Numbers와 같은 유사한 스프레드시트 프로그램에서도 생성될 수 있습니다. 이 파일 형식에 대해 자세히 알아보려면 여기에서 확인하십시오. |
| [XLSX](/watermark/python-net/groupdocs.watermark.common/filetype/xlsx/) | XLSX는 Microsoft Office 2007 출시와 함께 Microsoft에서 도입한 Microsoft Excel 문서의 잘 알려진 형식입니다. 이 파일 형식에 대해 자세히 알아보려면 여기에서 확인하십시오. |
| [XLSM](/watermark/python-net/groupdocs.watermark.common/filetype/xlsm/) | XLSM 확장자를 가진 파일은 매크로를 지원하는 스프레드시트 파일의 한 종류입니다. 이 파일 형식에 대해 자세히 알아보려면 여기에서 확인하십시오. |
| [XLTX](/watermark/python-net/groupdocs.watermark.common/filetype/xltx/) | XLTX 확장자를 가진 파일은 Office OpenXML 파일 형식 사양을 기반으로 하는 Microsoft Excel 템플릿 파일을 나타냅니다. 이 파일 형식에 대해 자세히 알아보려면 여기에서 확인하십시오. |
| [XLTM](/watermark/python-net/groupdocs.watermark.common/filetype/xltm/) | XLTM 파일 확장자는 Microsoft Excel에서 매크로 사용 템플릿 파일로 생성된 파일을 나타냅니다. 이 파일 형식에 대해 자세히 알아보려면 여기에서 확인하십시오. |
| [XLSB](/watermark/python-net/groupdocs.watermark.common/filetype/xlsb/) | XLSB 파일 형식은 Excel 바이너리 파일 형식을 지정하며, 이는 Excel 통합 문서 내용을 지정하는 레코드와 구조의 모음입니다. 이 파일 형식에 대해 자세히 알아보려면 여기에서 확인하십시오. |
| [XLT](/watermark/python-net/groupdocs.watermark.common/filetype/xlt/) | .XLT 확장자를 가진 파일은 Microsoft Office 제품군에 포함된 스프레드시트 응용 프로그램인 Microsoft Excel로 만든 템플릿 파일입니다. 이 파일 형식에 대해 자세히 알아보려면 여기에서 확인하십시오. |
| [DOC](/watermark/python-net/groupdocs.watermark.common/filetype/doc/) | .doc 확장자를 가진 파일은 Microsoft Word 또는 기타 워드 프로세서에서 바이너리 파일 형식으로 생성된 문서를 나타냅니다. 이 파일 형식에 대해 자세히 알아보려면 여기에서 확인하십시오. |
| [DOCX](/watermark/python-net/groupdocs.watermark.common/filetype/docx/) | DOCX는 Microsoft Word 문서에 널리 알려진 형식입니다. 2007년 Microsoft Office 2007 출시와 함께 도입된 이 새로운 문서 형식의 구조는 순수 바이너리에서 XML과 바이너리 파일의 조합으로 변경되었습니다. 이 파일 형식에 대해 자세히 알아보려면 여기에서 확인하십시오. |
| [DOCM](/watermark/python-net/groupdocs.watermark.common/filetype/docm/) | DOCM 파일은 매크로 실행 기능이 포함된 Microsoft Word 2007 이상에서 생성된 문서입니다. 이 파일 형식에 대해 자세히 알아보려면 여기에서 확인하십시오. |
| [DOT](/watermark/python-net/groupdocs.watermark.common/filetype/dot/) | .DOT 확장자를 가진 파일은 Microsoft Word에서 추가 DOC 또는 DOCX 파일 생성을 위한 사전 서식 설정을 갖춘 템플릿 파일입니다. 이 파일 형식에 대해 자세히 알아보려면 여기에서 확인하십시오. |
| [DOTX](/watermark/python-net/groupdocs.watermark.common/filetype/dotx/) | DOTX 확장자를 가진 파일은 Microsoft Word에서 추가 DOCX 파일 생성을 위한 사전 서식 설정을 갖춘 템플릿 파일입니다. 이 파일 형식에 대해 자세히 알아보려면 여기에서 확인하십시오. |
| [DOTM](/watermark/python-net/groupdocs.watermark.common/filetype/dotm/) | DOTM 확장자를 가진 파일은 Microsoft Word 2007 이상에서 만든 템플릿 파일을 나타냅니다. 이 파일 형식에 대해 자세히 알아보려면 여기에서 확인하십시오. |
| [RTF](/watermark/python-net/groupdocs.watermark.common/filetype/rtf/) | Microsoft에서 도입하고 문서화한 Rich Text Format(RTF)은 응용 프로그램 내에서 사용하기 위한 서식 있는 텍스트와 그래픽을 인코딩하는 방법을 나타냅니다. 이 형식은 다른 Microsoft 제품과의 교차 플랫폼 문서 교환을 용이하게 하여 상호 운용성을 제공합니다. 이 파일 형식에 대해 자세히 알아보려면 여기에서 확인하십시오. |
| [ODT](/watermark/python-net/groupdocs.watermark.common/filetype/odt/) | ODT 파일은 OpenDocument 텍스트 파일 형식을 기반으로 하는 워드 프로세서 응용 프로그램으로 만든 문서 유형입니다. 이러한 파일은 무료 OpenOffice Writer와 같은 워드 프로세서 응용 프로그램으로 생성되며 텍스트, 이미지, 객체 및 스타일과 같은 콘텐츠를 포함할 수 있습니다. 이 파일 형식에 대해 자세히 알아보려면 여기에서 확인하십시오. |
| [FLAT_OPC](/watermark/python-net/groupdocs.watermark.common/filetype/flat_opc/) | Office Open XML WordprocessingML은 ZIP 패키지(.xml) 대신 평면 XML 파일에 저장됩니다. 이 파일 형식에 대해 자세히 알아보려면 여기에서 확인하십시오. |
| [FLAT_OPC_MACRO_ENABLED](/watermark/python-net/groupdocs.watermark.common/filetype/flat_opc_macro_enabled/) | Office Open XML WordprocessingML 매크로 사용 문서는 ZIP 패키지(.xml) 대신 평면 XML 파일에 저장됩니다. 이 파일 형식에 대해 자세히 알아보려면 여기에서 확인하십시오. |
| [FLAT_OPC_TEMPLATE](/watermark/python-net/groupdocs.watermark.common/filetype/flat_opc_template/) | Office Open XML WordprocessingML 템플릿(매크로 없음)은 ZIP 패키지(.xml) 대신 평면 XML 파일에 저장됩니다. 이 파일 형식에 대해 자세히 알아보려면 여기에서 확인하십시오. |
| [FLAT_OPC_TEMPLATE_MACRO_ENABLED](/watermark/python-net/groupdocs.watermark.common/filetype/flat_opc_template_macro_enabled/) | Office Open XML WordprocessingML 매크로 사용 템플릿은 ZIP 패키지(.xml) 대신 평면 XML 파일에 저장됩니다. 이 파일 형식에 대해 자세히 알아보려면 여기에서 확인하십시오. |

### 예시

```python
from groupdocs.watermark.common import FileType

def list_supported_formats():
    # 라이브러리가 열 수 있는 모든 파일 유형을 열거하십시오
    supported_file_types = FileType.get_supported_file_types()
    for file_type in sorted(supported_file_types, key=lambda x: x.extension):
        print(file_type)

if __name__ == "__main__":
    list_supported_formats()
```

### Guides
`FileType`을 사용하는 작업 가이드:

* [Get supported file formats](/watermark/python-net/guides/get-supported-file-formats/)

### 또 보기
* module [`groupdocs.watermark.common`](/watermark/python-net/groupdocs.watermark.common/)
