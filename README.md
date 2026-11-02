# Требования к карточке товара: Ozon, Wildberries, Яндекс Маркет

Открытый реестр требований площадок к карточке товара — название, описание, фото, видео, баллы качества.
У каждого правила — ссылка на справку площадки (`source_url`) и дата, когда мы её сверили (`verified_at`).

Это зеркало реестра [eseo.su/pravila](https://eseo.su/pravila). Снимок на 02.11.2026: 63 правила
(Ozon — 22, Wildberries — 19, Яндекс Маркет — 22).

Площадки меняют правила без анонса. Источник правды — справка площадки по ссылке в строке; при расхождении
верна справка. Свежая версия — всегда на сайте:

- страница: https://eseo.su/pravila
- CSV: https://eseo.su/pravila.csv
- Markdown: https://eseo.su/pravila.md

## Файлы

| Файл | Что внутри |
| --- | --- |
| `data/pravila.csv` | реестр, UTF-8, разделитель — запятая |
| `data/pravila.md` | тот же реестр таблицами по площадкам |
| `datapackage.json` | описание полей (Frictionless Data) |

## Поля CSV

| Поле | Смысл |
| --- | --- |
| `marketplace` | код площадки: `OZON`, `WB`, `YM` |
| `marketplace_name` | название площадки |
| `section` | раздел: поля карточки, фото, видео, баллы качества |
| `key` | стабильный ключ правила |
| `value` | значение (число, диапазон, формат) |
| `rule` | что означает значение |
| `source_url` | справка площадки |
| `source_domain` | домен справки |
| `verified_at` | дата сверки, ГГГГ-ММ-ДД |
| `status` | статус сверки |

## Лицензия

[CC BY 4.0](LICENSE). При использовании укажите источник: «ESEO, eseo.su/pravila».

---

# Marketplace product card requirements (Ozon, Wildberries, Yandex Market)

An open registry of product card rules for Russian marketplaces: title, description, photo, video and quality
score limits. Each row links to the marketplace's own help page and carries the date we last checked it.
Mirror of https://eseo.su/pravila (snapshot 2026-11-02, 63 rules). The marketplace help page is the source
of truth. License: CC BY 4.0, attribution "ESEO, eseo.su/pravila".
