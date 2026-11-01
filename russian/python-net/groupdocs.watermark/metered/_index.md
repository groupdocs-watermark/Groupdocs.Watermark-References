---
title: "Класс Metered"
second_title: "GroupDocs.Watermark для Python через .NET справочник API"
description: "Управляет измеряемым (по-использованию) лицензированием."
type: docs
url: /ru/python-net/groupdocs.watermark/metered/
is_root: false
weight: 30
---


## Metered class

Управляет измеряемым (по-использованию) лицензированием.

Лицензии Metered выставляют счет на основе фактического потребления (обычно страниц или
обработанных документов). Установите пару публичного/приватного ключа один раз при
запуске приложения; обёртка отправляет данные об использовании обратно в GroupDocs
сервер лицензий в фоновом режиме.

Тип Metered раскрывает следующие члены:

### Методы
| Метод | Описание |
| :- | :- |
| [get_consumption_credit](/watermark/python-net/groupdocs.watermark/metered/get_consumption_credit/) | Возвращает количество использованных кредитов на данный момент. |
| [get_consumption_quantity](/watermark/python-net/groupdocs.watermark/metered/get_consumption_quantity/) | Возвращает объём обработанных данных на данный момент. |
| [set_metered_key](/watermark/python-net/groupdocs.watermark/metered/set_metered_key/#public_key-private_key) | Активируйте тарификацию Metered с указанной парой публичного/приватного ключа. |

### См. также
* module [`groupdocs.watermark`](/watermark/python-net/groupdocs.watermark/)
