---
title: "기능 개요"
linkTitle: "Features overview"
second_title: "Python용 .NET을 통한 GroupDocs.Watermark API 참조"
description: "GroupDocs.Watermark for Python via .NET는 단일 형식에 독립적인 API를 통해 텍스트 및 이미지 워터마크를 추가, 검색 및 제거합니다 — 형식별 배치, 콘텐츠 트리 편집, 잠금 및 래스터화를 지원합니다."
type: docs
url: /ko/python-net/guides/features-overview/
is_root: false
weight: 30
---


GroupDocs.Watermark for Python via .NET는 광범위한 [지원되는 문서 형식](https://docs.groupdocs.com/watermark/python-net/supported-document-formats/)에서 워터마크를 추가, 검색 및 제거합니다. 모든 작업은 동일한 워크플로를 따릅니다: [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)로 문서를 열고, `add()`, `search()`, 또는 `remove()`를 호출한 다음, `save()`로 결과를 원래 형식으로 저장합니다. 아래 기능은 단일 패스에서 자유롭게 결합할 수 있습니다.

## Text and image watermarks

스타일이 적용된 텍스트 또는 이미지 워터마크를 글꼴, 색상, 불투명도, 회전, 정렬 및 크기에 대한 전체 제어와 함께 추가합니다. 이미지 워터마크는 파일이나 스트림에서 로드할 수 있습니다. [텍스트 워터마크 추가](/watermark/python-net/guides/add-text/) 및 [이미지 워터마크 추가](/watermark/python-net/guides/add-image/)를 참조하십시오.

## Customization and tiling

워터마크를 절대 좌표 또는 상위 요소 상대 정렬 및 여백으로 배치하고, 페이지에 비례하여 크기를 조정하고, 회전시키며, 전체 페이지에 반복 패턴으로 타일링합니다. [워터마크 사용자 지정](/watermark/python-net/guides/customize/), [반복 워터마크 추가](/watermark/python-net/guides/adding-repeated-watermarks/), 및 [텍스트 워터마크 추가](https://docs.groupdocs.com/watermark/python-net/adding-text-watermarks/)를 참조하십시오.

## Format-specific placement

각 형식에 맞는 옵션을 사용하여 워터마크를 배치합니다 — PDF 아티팩트, 주석 및 인쇄 전용 주석; 프레젠테이션 슬라이드, 마스터, 레이아웃 및 노트; 스프레드시트 워크시트, 배경 및 머리글/바닥글; Visio 페이지; 그리고 잠긴 Word 섹션 및 페이지. [PDF 문서에 워터마크 추가](https://docs.groupdocs.com/watermark/python-net/add-watermarks-to-pdf-documents/) 및 [개발자 가이드](https://docs.groupdocs.com/watermark/python-net/adding-watermarks/)의 다른 형식 주제를 참조하십시오.

## Searching, modifying, and removing

문서에 이미 존재하는 워터마크를 — 제3자 도구가 추가한 것 포함 — 정확한 텍스트, 정규식, 이미지 유사도 또는 텍스트 서식으로 찾아내고, `and_`/`or_`/`not_`로 기준을 결합합니다. 찾은 후에는 텍스트나 이미지를 교체하거나 제거할 수 있습니다. [워터마크 검색](/watermark/python-net/guides/searching-watermarks/), [찾은 워터마크 속성 수정](https://docs.groupdocs.com/watermark/python-net/modifying-found-watermark-properties/), 및 [찾은 워터마크 제거](https://docs.groupdocs.com/watermark/python-net/removing-found-watermarks/)를 참조하십시오.

## Working with existing content

`Watermarker.get_content()`는 형식별 콘텐츠 트리를 노출하여 기존 도형, PDF XObjects/아티팩트/주석, 첨부 파일, 배경 및 머리글/바닥글을 검사하고 편집할 수 있게 합니다 — 또한 `get_images()`를 사용하여 문서에 포함된 이미지를 워터마크 할 수 있습니다. [문서 내부 이미지에 워터마크 추가](https://docs.groupdocs.com/watermark/python-net/adding-watermark-to-images-inside-a-document/)를 참조하십시오.

## Tamper resistance

워터마크를 잠그거나 Word 문서를 보호하고, 인쇄 전용 PDF 주석을 추가하거나 PDF 페이지를 래스터화하여 워터마크를 제거하기 어렵게 만듭니다. [워드 프로세싱 문서에서 워터마크 잠금](https://docs.groupdocs.com/watermark/python-net/locking-watermark-in-word-processing-document/) 및 [문서 또는 페이지 래스터화](https://docs.groupdocs.com/watermark/python-net/rasterize-document-or-page/)를 참조하십시오.

## Document inspection

문서를 수정하지 않고 파일 유형, 페이지 수 및 크기를 읽고, 라이브러리가 지원하는 모든 파일 형식을 나열합니다. [문서 정보 가져오기](/watermark/python-net/guides/get-document-info/) 및 [지원되는 파일 형식 가져오기](/watermark/python-net/guides/get-supported-file-formats/)를 참조하십시오.

## On-premise

GroupDocs.Watermark for Python via .NET는 완전히 자체 인프라에서 실행됩니다 — 문서는 절대 환경을 떠나지 않습니다. 이 패키지는 필요한 모든 것을 포함하는 자체 포함 휠이며, Microsoft Office, OpenOffice 또는 별도 런타임을 설치할 필요가 없습니다. 지원되는 플랫폼 및 네이티브 종속성에 대해서는 [시스템 요구 사항](https://docs.groupdocs.com/watermark/python-net/system-requirements/)을 참조하십시오.
