---
title: "EmailContent 클래스"
second_title: "Python용 .NET을 통한 GroupDocs.Watermark API 참조"
description: "이메일 메시지를 나타냅니다."
type: docs
url: /ko/python-net/groupdocs.watermark.contents.email/emailcontent/
is_root: false
weight: 70
---


## EmailContent class

이메일 메시지를 나타냅니다.

자세히 알아보기:
- [Add watermarks to email attachments](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+email+attachments)
- [Email attachments](https://docs.groupdocs.com/display/watermarknet/Email+attachments)
- [Email messages](https://docs.groupdocs.com/display/watermarknet/Email+messages)

EmailContent 유형은 다음 멤버를 노출합니다:

### 메서드
| 메서드 | 설명 |
| :- | :- |
| [dispose](/watermark/python-net/groupdocs.watermark.contents/content/dispose/) | 현재 인스턴스를 해제합니다. ([`Content`](/watermark/python-net/groupdocs.watermark.contents/content/)에서 상속됨) |
| [find_images](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images/) | 지정된 검색 기준에 따라 이미지를 찾습니다. 검색은 [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/)에 지정된 객체에서 수행됩니다. ([`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)에서 상속됨) |
| [find_images_image_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images_image_search_criteria/) | ([`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)에서 상속됨) |
| [search](/watermark/python-net/groupdocs.watermark.contents/contentpart/search/) | 지정된 검색 기준에 따라 가능한 워터마크를 찾습니다. 검색은 [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/)에 나열된 객체에서 수행됩니다. ([`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)에서 상속됨) |
| [search_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/search_search_criteria/) | ([`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)에서 상속됨) |

### 속성
| 속성 | 설명 |
| :- | :- |
| [attachments](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/attachments/) | 이메일 메시지의 모든 첨부 파일 컬렉션. |
| [bcc](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/bcc/) | 이메일 메시지의 BCC(숨은 참조) 수신자 컬렉션. |
| [body](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/body/) | 메시지 본문의 일반 텍스트 표현. |
| [body_type](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/body_type/) | 이메일 메시지 본문의 유형. |
| [cc](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/cc/) | 이메일 메시지의 CC(참조) 수신자 컬렉션. |
| [embedded_objects](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/embedded_objects/) | 이메일 메시지의 모든 임베디드 객체 컬렉션. |
| [from_](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/from_/) | 이메일 메시지의 발신자 주소. |
| [html_body](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/html_body/) | 메시지 본문의 HTML 표현. |
| [subject](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/subject/) | 이메일 메시지의 제목. |
| [to](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/to/) | 이 이메일 메시지의 수신자 컬렉션입니다. |

### 예시

```python
import groupdocs.watermark as gw
from groupdocs.watermark.options.email import EmailLoadOptions
import groupdocs.watermark.contents.email as gwc_email

load_options = EmailLoadOptions()
with gw.Watermarker("message.msg", load_options) as watermarker:
    content = watermarker.get_content()
    # 첨부 파일 추가
    with open("sample.msg", "rb") as f:
        content.attachments.add(f.read(), "sample.msg")
    watermarker.save("output.msg")
```

### 또 보기
* module [`groupdocs.watermark.contents.email`](/watermark/python-net/groupdocs.watermark.contents.email/)
