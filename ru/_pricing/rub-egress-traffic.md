### Исходящий трафик {#prices-traffic}

При использовании сервиса оплачивается исходящий трафик из {{ yandex-cloud }} в интернет. Передача трафика между сервисами {{ yandex-cloud }}, как и входящий трафик из интернета, не тарифицируется.

Минимальная единица тарификации — 1 МБ.

| Категория ресурса | Цена за ГБ, вкл. НДС | |
| --- | --- | --- |
| | **До 12 апреля 2022<br>включительно** | **С 13 апреля 2022** |
| Исходящий трафик, до 10 ГБ | {{ sku|RUB|network.egress.inet|string }} | {{ sku|RUB|network.egress.inet|string }} |
| Исходящий трафик, сверх 10 ГБ | {{ sku|RUB|network.egress.inet|pricingRate.10|string }} | 1,53 ₽ |