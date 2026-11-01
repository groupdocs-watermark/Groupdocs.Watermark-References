---
title: "Класс EmailPreviewOptions"
second_title: "GroupDocs.Watermark для Python через .NET справочник API"
description: "Предоставляет параметры для установки требований и делегатов потоков при генерации предварительного просмотра документа электронной почты."
type: docs
url: /ru/python-net/groupdocs.watermark.options.email/emailpreviewoptions/
is_root: false
weight: 20
---


## EmailPreviewOptions class

Предоставляет параметры для установки требований и делегатов потоков при генерации предварительного просмотра документа электронной почты.

Тип EmailPreviewOptions раскрывает следующие члены:

### Конструкторы
| Конструктор | Описание |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.email/emailpreviewoptions/__init__/#create_page_stream) | Инициализирует новый экземпляр класса [`EmailPreviewOptions`](/watermark/python-net/groupdocs.watermark.options.email/emailpreviewoptions/), закрывая выходной поток. |
| [__init__](/watermark/python-net/groupdocs.watermark.options.email/emailpreviewoptions/__init__/#create_page_stream-release_page_stream) | Инициализирует новый экземпляр класса EmailPreviewOptions, возвращая выходной поток клиенту для дальнейшего использования. |

### Свойства
| Свойство | Описание |
| :- | :- |
| [resolution](/watermark/python-net/groupdocs.watermark.options.email/emailpreviewoptions/resolution/) | Разрешение генерируемых изображений в точках на дюйм. |
| [create_page_stream](/watermark/python-net/groupdocs.watermark.options/previewoptions/create_page_stream/) | Делегат создания потока страницы, используемый для получения записываемого потока для каждой отрисованной страницы. (наследуется от [`PreviewOptions`](/watermark/python-net/groupdocs.watermark.options/previewoptions/)) |
| [height](/watermark/python-net/groupdocs.watermark.options/previewoptions/height/) | Высота предварительного просмотра страницы. (наследуется от [`PreviewOptions`](/watermark/python-net/groupdocs.watermark.options/previewoptions/)) |
| [page_numbers](/watermark/python-net/groupdocs.watermark.options/previewoptions/page_numbers/) | Массив номеров страниц для генерации предварительных просмотров. (наследуется от [`PreviewOptions`](/watermark/python-net/groupdocs.watermark.options/previewoptions/)) |
| [preview_format](/watermark/python-net/groupdocs.watermark.options/previewoptions/preview_format/) | Формат изображения предварительного просмотра. (наследуется от [`PreviewOptions`](/watermark/python-net/groupdocs.watermark.options/previewoptions/)) |
| [release_page_stream](/watermark/python-net/groupdocs.watermark.options/previewoptions/release_page_stream/) | Делегат завершения предварительного просмотра страницы. (наследуется от [`PreviewOptions`](/watermark/python-net/groupdocs.watermark.options/previewoptions/)) |
| [width](/watermark/python-net/groupdocs.watermark.options/previewoptions/width/) | Ширина предварительного просмотра страницы. (наследуется от [`PreviewOptions`](/watermark/python-net/groupdocs.watermark.options/previewoptions/)) |

### Поля
| Поле | Описание |
| :- | :- |
| [DEFAULT_RESOLUTION](/watermark/python-net/groupdocs.watermark.options.email/emailpreviewoptions/default_resolution/) | Разрешение по умолчанию в точках на дюйм. |

### См. также
* module [`groupdocs.watermark.options.email`](/watermark/python-net/groupdocs.watermark.options.email/)
