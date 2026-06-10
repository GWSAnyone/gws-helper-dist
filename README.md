# GWS Helper — distribution

Подписанный Firefox-аддон (self-distribution, unlisted) + update-манифест.

- `updates.json` — Firefox update manifest (`update_url` в расширении смотрит сюда).
- релизы `vX.Y` содержат `gws_helper-X.Y.xpi` (подписанный AMO).

Секретов тут нет: расширение лишь читает куки маркетплейсов в браузере
пользователя и работает только вместе с GWS Analytics на доверенном хосте.

⚠ Для работы Firefox-автообновления репозиторий (или эти 2 файла) должны быть
анонимно доступны по HTTPS (public репо / pages.dev). Из private репо Firefox
их не прочитает.
