---
type: "note"
description: "Для первого push vault нужны коммит и данные автора Git; после их настройки vault отправлен в репозиторий sterlyagov/iva-vault."
tags: ["git","github","vault"]
status: "active"
confidence: "EXTRACTED"
domain: "knowledge"
created: "2026-09-18"
source: "daily/2026-09-18.md"
last_accessed: "2026-09-18"
tier: "active"
relevance: 0.97
updated: "2026-09-19"
---

# Первый push vault требует коммита и настроенных данных автора Git

17 сентября 2026 года в репозитории vault на GitHub remote `origin` указывал на `https://github.com/sterlyagov/iva-vault.git`. Локальная ветка `master` существовала, но коммитов ещё не было, поэтому `git push --set-upstream origin master` завершался ошибкой `src refspec master does not match any`. После подготовки файлов через `git add -A` создание первого коммита остановилось, потому что Git не знал имя и email автора. Для продолжения нужно настроить `user.name` и `user.email`, затем создать коммит и повторить push.

## Related

- [[cards/notes/_index|Знания]]
- [[cards/notes/github-аккаунт-sterlyagov-подключён-к-иве]]
- [[cards/projects/организация-smm-команды-из-трёх-человек]]

## Log

- 2026-09-19: 17 сентября 2026 года после настройки `user.name` и `user.email` был создан первый коммит `cc90fb3` с сообщением `Initial vault snapshot`. Затем vault успешно отправлен в репозиторий `https://github.com/sterlyagov/iva-vault.git`; ветка `master` связана с `origin/master`. Источник: daily/2026-09-18.md.
