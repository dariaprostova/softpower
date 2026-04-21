# soft power website — GitHub Pages deploy

Эта папка уже готова для GitHub Pages.

## Что внутри

- `index.html` — главная страница сайта
- `assets/photos/` — оптимизированные фотографии
- `.nojekyll` — чтобы GitHub Pages отдавал файлы как обычный статический сайт

## Вариант 1: отдельный сайт на username.github.io

Если репозиторий называется:

```text
USERNAME.github.io
```

то сайт будет открываться по адресу:

```text
https://USERNAME.github.io/
```

В репозиторий нужно загрузить содержимое папки `website`, не саму папку.

## Вариант 2: проект внутри аккаунта

Если репозиторий называется:

```text
softpower
```

то сайт будет открываться по адресу:

```text
https://USERNAME.github.io/softpower/
```

В настройках репозитория нужно включить:

```text
Settings → Pages → Build and deployment → Deploy from a branch → main → /root
```

## Когда подключать softpowerspace.com

Сначала лучше открыть сайт на временном GitHub Pages URL и проверить:

- desktop
- iPhone Safari
- все фотографии
- все кнопки
- тексты, цены и расписание

После этого можно подключить домен `softpowerspace.com` через настройки GitHub Pages и DNS у регистратора.
