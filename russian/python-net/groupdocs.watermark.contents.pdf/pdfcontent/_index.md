---
title: "Класс PdfContent"
second_title: "GroupDocs.Watermark для Python через .NET справочник API"
description: "Представляет PDF‑документ, в который можно добавить водяной знак."
type: docs
url: /ru/python-net/groupdocs.watermark.contents.pdf/pdfcontent/
is_root: false
weight: 100
---


## PdfContent class

Представляет PDF‑документ, в который можно добавить водяной знак.

Узнать больше:
- [Add watermarks to PDF documents](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+PDF+documents)
- [Existing objects in PDF document](https://docs.groupdocs.com/display/watermarknet/Existing+objects+in+PDF+document)
- [Rasterize document or page](https://docs.groupdocs.com/display/watermarknet/Rasterize+document+or+page)
- [Watermarks in PDF document](https://docs.groupdocs.com/display/watermarknet/Watermarks+in+PDF+document)

Тип PdfContent раскрывает следующие члены:

### Методы
| Метод | Описание |
| :- | :- |
| [decrypt](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/decrypt/) | Расшифровывает содержимое. |
| [encrypt](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/encrypt/#password) | Шифрует документ, используя тот же пароль, что и пароль пользователя и пароль владельца. |
| [encrypt](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/encrypt/#user_password-owner_password-permissions-crypto_algorithm) | Шифрует содержимое. |
| [encrypt_file](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/encrypt_file/) |  |
| [encrypt_string](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/encrypt_string/) |  |
| [rasterize](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/rasterize/#horizontal_resolution-vertical_resolution-image_format) | Преобразует все страницы содержимого в изображения. |
| [rasterize_int32](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/rasterize_int32/) |  |
| [dispose](/watermark/python-net/groupdocs.watermark.contents/content/dispose/) | Освобождает текущий экземпляр. (унаследовано от [`Content`](/watermark/python-net/groupdocs.watermark.contents/content/)) |
| [find_images](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images/) | Находит изображения в соответствии с указанными критериями поиска. Поиск выполняется в объектах, указанных в [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/). (унаследовано от [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [find_images_image_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images_image_search_criteria/) | (унаследовано от [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [search](/watermark/python-net/groupdocs.watermark.contents/contentpart/search/) | Находит возможные водяные знаки в соответствии с указанными критериями поиска. Поиск выполняется по объектам, перечисленным в [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/). (унаследовано от [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [search_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/search_search_criteria/) | (унаследовано от [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |

### Свойства
| Свойство | Описание |
| :- | :- |
| [attachments](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/attachments/) | Коллекция всех вложений этого [`PdfContent`](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/). |
| [page_margin_type](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/page_margin_type/) | Поля страниц PDF, которые будут использоваться при добавлении водяного знака. |
| [pages](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/pages/) | Коллекция всех страниц этого [`PdfContent`](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/). |

### Пример

```python
from groupdocs.watermark import Watermarker

# Загрузить PDF‑файл
watermarker = Watermarker("sample.pdf")

# Получить дерево содержимого PDF
pdf_content = watermarker.get_content()

# Итерировать страницы и выводить их размеры
for page in pdf_content.pages:
    print(page.width, page.height)
```

### См. также
* module [`groupdocs.watermark.contents.pdf`](/watermark/python-net/groupdocs.watermark.contents.pdf/)
