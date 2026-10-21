# VK Admin

Информационный сайт Android-приложения VK Admin.

- `index.html` — описание приложения и ссылка на сообщество проекта.
- `privacy.html` — политика конфиденциальности, включая отправку логов на Google Drive.
- `terms.html` — условия использования.
- `styles.css` — оформление страниц.
- `.nojekyll` — публикация готовых файлов без Jekyll.

Сайт статический: без JavaScript, форм, собственных cookies, аналитики и внешних шрифтов.
Документы описывают реализацию VK Admin 4.83; редакция от 21.10.2026.

Сообщество: https://vk.ru/vkmax26
Поддержка: murugov1976@gmail.com

## GitHub Pages

В настройках этого репозитория: Settings → Pages → Build and deployment →
Source: Deploy from a branch → Branch: main → Folder: /(root) → Save.
Публичный URL и состояние развёртывания отображаются на этой же странице после публикации.

## Подтверждение Google

Добавить фактический корневой HTTPS-адрес опубликованного сайта в Google Search Console
как URL prefix. Для проверки через HTML tag добавить выданный Search Console тег
`google-site-verification` в `<head>` файла `index.html`. Тег оставить после проверки.

В Google Auth Platform → Branding зарегистрировать hostname сайта в Authorized domains,
а затем указать фактические URL главной страницы, `privacy.html` и `terms.html`.
Сохранить и выполнить требования, которые Google покажет для публикации OAuth-приложения.

При изменении обработки данных обновлять тексты документов и дату редакции.
