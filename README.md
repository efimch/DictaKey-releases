# «С голоса» — сборки и обновления

**«С голоса»** — диктовка для Mac: распознаёт речь и вставляет текст туда, где стоит курсор. Работает целиком на компьютере — голос и текст никуда не отправляются. До версии 1.2.0 приложение называлось DictaKey.

Сайт: **[sgolosa.ru](https://sgolosa.ru)** — что умеет приложение, замеры, установка и покупка лицензии.

Исходный код закрыт. В этом репозитории лежат только:

- **сборки** — образ диска и архив обновления, на [странице выпусков](https://github.com/efimch/DictaKey-releases/releases/latest);
- **лента обновлений** — `appcast.xml` на ветке `gh-pages`; установленное приложение сверяется с ней само.

## Установка

1. Скачайте `Sgolosa.dmg` из [последнего выпуска](https://github.com/efimch/DictaKey-releases/releases/latest), откройте его и перетащите «С голоса» в «Программы».
2. При первом запуске macOS не откроет приложение сразу: оно подписано собственным сертификатом разработчика и не заверено Apple. Разрешите запуск в «Системные настройки» → «Конфиденциальность и безопасность».

Нужны Mac с процессором Apple и macOS 14 или новее. Те же шаги подробно — в [инструкции на сайте](https://sgolosa.ru/install.html).

## Лицензия

Первые 14 дней все функции работают без ограничений. Дальше обычная диктовка остаётся бесплатной, а LLM-слой, перевод и правка голосом — до 2 500 слов в неделю; лицензия снимает это ограничение. Цены и покупка — [на сайте](https://sgolosa.ru/#price).

## Обновления

Приложение проверяет обновления само, через [Sparkle](https://sparkle-project.org). Архив обновления подписан (EdDSA), ключ проверки встроен в приложение.

## Связь

Поддержка: support@sgolosa.ru. Сайт: https://sgolosa.ru.

---

**In English.** «С голоса» (“S golosa”, formerly DictaKey) is an offline dictation app for macOS (Apple silicon, macOS 14 or later). This repository hosts its binary releases and the Sparkle update feed; the source code is private. For the first 14 days everything works without limits; after that plain dictation stays free, and the LLM layer, translation and editing by voice are limited to 2,500 words a week unless a licence is entered. Website (in Russian): https://sgolosa.ru.

© Efim Chernov. All rights reserved.
