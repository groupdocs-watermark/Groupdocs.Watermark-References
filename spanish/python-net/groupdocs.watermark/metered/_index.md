---
title: "Clase de facturación por consumo"
second_title: "Referencias de la API de GroupDocs.Watermark para Python a través de .NET"
description: "Administra licencias medidas (pago por uso)."
type: docs
url: /es/python-net/groupdocs.watermark/metered/
is_root: false
weight: 30
---


## Metered class

Administra licencias medidas (pago por uso).

Las licencias por consumo facturan según el consumo real (normalmente páginas o
documentos procesados). Establezca el par de claves pública/privada una vez en
el inicio de la aplicación; el contenedor informa el uso al servidor de GroupDocs
de licencias en segundo plano.

El tipo Metered expone los siguientes miembros:

### Métodos
| Método | Descripción |
| :- | :- |
| [get_consumption_credit](/watermark/python-net/groupdocs.watermark/metered/get_consumption_credit/) | Devuelve el número de créditos consumidos hasta ahora. |
| [get_consumption_quantity](/watermark/python-net/groupdocs.watermark/metered/get_consumption_quantity/) | Devuelve la cantidad de datos procesados hasta ahora. |
| [set_metered_key](/watermark/python-net/groupdocs.watermark/metered/set_metered_key/#public_key-private_key) | Active la facturación por consumo con el par de claves pública/privada proporcionado. |

### Ver también
* module [`groupdocs.watermark`](/watermark/python-net/groupdocs.watermark/)
