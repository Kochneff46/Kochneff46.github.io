# GITHUB_PAGES_DEPLOY_REPORT.md

Дата проверки: 2026-06-12

## Итог

- Репозиторий: `Kochneff46/autogatespro-site`
- Ветка: `main`
- Remote `main`: `033d47e02a30d6b5b0986a9f9670056ea7217ab6`
- GitHub Pages: ON
- URL сайта GitHub Pages: `https://kochneff46.github.io/`
- Статус публикации: сайт публично открывается
- Главная страница GitHub Pages: HTTP `200`

## Статус GitHub Pages

Публичный URL GitHub Pages проверен через HTTP HEAD:

`https://kochneff46.github.io/`

Результат:

- HTTP status: `200`
- Server: `GitHub.com`
- Content-Type: `text/html; charset=utf-8`
- Content-Length: `28218`
- Last-Modified: `Fri, 12 Jun 2026 17:55:59 GMT`

GitHub REST endpoint `/pages` без авторизации вернул `404`, но публичная раздача GitHub Pages работает, поэтому фактический статус публикации: ON.

## Проверенные страницы

| Страница | HTTP | Метрика 109810390 | yandex-verification | Canonical | OpenGraph | JSON-LD |
|---|---:|---:|---:|---:|---:|---:|
| `/` | 200 | OK | OK | OK | OK | OK |
| `/cities/` | 200 | OK | OK | OK | OK | OK |
| `/moscow.html` | 200 | OK | OK | OK | OK | OK |
| `/mytishchi.html` | 200 | OK | OK | OK | OK | OK |
| `/korolev.html` | 200 | OK | OK | OK | OK | OK |
| `/pushkino.html` | 200 | OK | OK | OK | OK | OK |
| `/khimki.html` | 200 | OK | OK | OK | OK | OK |
| `/balashiha.html` | 200 | OK | OK | OK | OK | OK |
| `/schelkovo.html` | 200 | OK | OK | OK | OK | OK |
| `/dmitrov.html` | 200 | OK | OK | OK | OK | OK |

Примечание: проверка содержимого выполнена по опубликованному коммиту `033d47e` и локальным файлам с совпадающими размерами `Content-Length` на GitHub Pages. Массовая загрузка тела страниц через `curl` в текущей среде периодически возвращала DNS `code 6`, но HTTP HEAD для страниц, robots и sitemap стабильно отдаёт `200`.

## robots.txt

Публичный URL:

`https://kochneff46.github.io/robots.txt`

Статус:

- HTTP: `200`
- Файл есть: да
- Индексация разрешена: да
- Sitemap указан: да

Текущий sitemap в robots:

`https://kochneff46.github.io/sitemap.xml`

## sitemap.xml

Публичный URL:

`https://kochneff46.github.io/sitemap.xml`

Статус:

- HTTP: `200`
- URL в sitemap: 10
- Файл есть: да

Текущие URL в sitemap указывают на:

`https://kochneff46.github.io/`

## Canonical и домен

Canonical и OpenGraph URL сейчас указывают на домен:

`https://kochneff46.github.io`

GitHub Pages URL:

`https://kochneff46.github.io/`

Это значит:

- Для технической проверки GitHub Pages сайт готов.
- Для подтверждения именно GitHub Pages в Яндекс.Вебмастере метатег присутствует.
- Для SEO лучше выбрать один основной домен. Если основным будет GitHub Pages, нужно заменить canonical, sitemap и robots на `https://kochneff46.github.io/`. Если основным будет Netlify, нужно восстановить/настроить Netlify, потому что сейчас Netlify отдавал `404`.

## Яндекс.Метрика

- Счётчик: `109810390`
- Установлен на всех HTML-страницах: да
- Дубликатов по локальной проверке: нет

## Яндекс.Вебмастер

- Метатег: `<meta name="yandex-verification" content="9858055d47a09ae9" />`
- Установлен на всех HTML-страницах: да
- Готовность к нажатию «Подтвердить» для GitHub Pages URL: YES

## Рекомендация

Следующее действие: в Яндекс.Вебмастере добавить сайт:

`https://kochneff46.github.io/`

и нажать «Подтвердить» по метатегу.

Если нужен основной коммерческий домен `https://kochneff46.github.io`, сначала нужно исправить Netlify 404 или выбрать GitHub Pages как основной домен и обновить canonical/sitemap/robots под него.
