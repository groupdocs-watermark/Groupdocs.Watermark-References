---
title: "Metered 클래스"
second_title: "Python용 .NET을 통한 GroupDocs.Watermark API 참조"
description: "계량식(사용량 기반) 라이선스를 관리합니다."
type: docs
url: /ko/python-net/groupdocs.watermark/metered/
is_root: false
weight: 30
---


## Metered class

계량식(사용량 기반) 라이선스를 관리합니다.

Metered 라이선스는 실제 사용량에 따라 청구됩니다 (보통 페이지 또는
처리된 문서). 공개/비공개 키 쌍을 한 번만 설정합니다
응용 프로그램 시작 시; 래퍼가 사용량을 GroupDocs에 보고합니다
백그라운드에서 라이선스 서버에.

Metered 형식은 다음 멤버를 노출합니다:

### 메서드
| 메서드 | 설명 |
| :- | :- |
| [get_consumption_credit](/watermark/python-net/groupdocs.watermark/metered/get_consumption_credit/) | 지금까지 사용된 크레딧 수를 반환합니다. |
| [get_consumption_quantity](/watermark/python-net/groupdocs.watermark/metered/get_consumption_quantity/) | 지금까지 처리된 데이터 양을 반환합니다. |
| [set_metered_key](/watermark/python-net/groupdocs.watermark/metered/set_metered_key/#public_key-private_key) | 주어진 공개/비공개 키 쌍으로 사용량 기반 청구를 활성화합니다. |

### 또 보기
* module [`groupdocs.watermark`](/watermark/python-net/groupdocs.watermark/)
