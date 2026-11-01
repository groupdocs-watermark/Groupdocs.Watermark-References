---
title: "SpreadsheetPreviewOptions 클래스"
second_title: "Python용 .NET을 통한 GroupDocs.Watermark API 참조"
description: "스프레드시트 문서 미리보기 생성을 위한 요구 사항 및 스트림 대리자를 설정하는 옵션을 제공합니다."
type: docs
url: /ko/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetpreviewoptions/
is_root: false
weight: 50
---


## SpreadsheetPreviewOptions class

스프레드시트 문서 미리보기 생성을 위한 요구 사항 및 스트림 대리자를 설정하는 옵션을 제공합니다.

SpreadsheetPreviewOptions 타입은 다음 멤버를 노출합니다:

### 생성자
| 생성자 | 설명 |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetpreviewoptions/__init__/#create_page_stream) | SpreadsheetPreviewOptions 클래스의 새 인스턴스를 초기화하며, 출력 스트림을 닫습니다. |
| [__init__](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetpreviewoptions/__init__/#create_page_stream-release_page_stream) | SpreadsheetPreviewOptions 클래스의 새 인스턴스를 초기화하여 출력 스트림을 클라이언트에 반환하고 이후에 사용할 수 있게 합니다. |

### 속성
| 속성 | 설명 |
| :- | :- |
| [only_data_area](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetpreviewoptions/only_data_area/) | 헤더, 푸터, 여백 없이 데이터 영역만 렌더링하기 위한 플래그. |
| [resolution](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetpreviewoptions/resolution/) | 생성된 이미지의 해상도(인치당 도트 수)입니다. |
| [create_page_stream](/watermark/python-net/groupdocs.watermark.options/previewoptions/create_page_stream/) | 각 렌더링된 페이지에 대해 쓰기 가능한 스트림을 얻기 위해 사용되는 페이지 스트림 생성 대리자입니다. ([`PreviewOptions`](/watermark/python-net/groupdocs.watermark.options/previewoptions/)에서 상속됨) |
| [height](/watermark/python-net/groupdocs.watermark.options/previewoptions/height/) | 페이지 미리보기 높이입니다. ([`PreviewOptions`](/watermark/python-net/groupdocs.watermark.options/previewoptions/)에서 상속됨) |
| [page_numbers](/watermark/python-net/groupdocs.watermark.options/previewoptions/page_numbers/) | 미리보기를 생성할 페이지 번호 배열입니다. ([`PreviewOptions`](/watermark/python-net/groupdocs.watermark.options/previewoptions/)에서 상속됨) |
| [preview_format](/watermark/python-net/groupdocs.watermark.options/previewoptions/preview_format/) | 미리보기 이미지 형식입니다. ([`PreviewOptions`](/watermark/python-net/groupdocs.watermark.options/previewoptions/)에서 상속됨) |
| [release_page_stream](/watermark/python-net/groupdocs.watermark.options/previewoptions/release_page_stream/) | 페이지 미리보기 완료 대리자입니다. ([`PreviewOptions`](/watermark/python-net/groupdocs.watermark.options/previewoptions/)에서 상속됨) |
| [width](/watermark/python-net/groupdocs.watermark.options/previewoptions/width/) | 페이지 미리보기 너비입니다. ([`PreviewOptions`](/watermark/python-net/groupdocs.watermark.options/previewoptions/)에서 상속됨) |

### 필드
| 필드 | 설명 |
| :- | :- |
| [DEFAULT_RESOLUTION](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetpreviewoptions/default_resolution/) | 기본 해상도(인치당 도트 수)입니다. |

### 또 보기
* module [`groupdocs.watermark.options.spreadsheet`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/)
