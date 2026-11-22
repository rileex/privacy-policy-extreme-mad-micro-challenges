# Privacy Policy — Extreme Mad Micro Challenges

Статический сайт с политикой конфиденциальности для мобильной игры «Extreme Mad Micro Challenges».
Публикуется через **GitHub Pages** без сборки и зависимостей.

## Что внутри

| Файл | Назначение |
| --- | --- |
| `index.html` | Русская версия (главная страница) |
| `en.html` | English version |
| `assets/style.css` | Общие стили, светлая и тёмная тема |
| `.nojekyll` | Отключает обработку Jekyll на GitHub Pages |

## Уже настроено

- Название игры: **Extreme Mad Micro Challenges**
- Контактный email: **xlabsgames@gmail.com**
- Адрес сайта: `https://rileex.github.io/privacy-policy/`
- `canonical` и `hreflang` в обеих версиях уже указывают на этот адрес

Если репозиторий переименован, обновите URL в тегах `<link rel="canonical">`
и `hreflang` в `index.html` и `en.html`.

## Публикация на GitHub Pages

```powershell
cd privacy-policy
git add .
git commit -m "Update privacy policy"
git push
```

GitHub Pages настроен на ветку `main`, каталог `/` — сайт обновляется
автоматически в течение 1–2 минут после пуша.

## Что стоит проверить в тексте

Политика написана под игру **без аккаунтов, с рекламой Google AdMob**. Если появится:

- **аналитика** (Firebase Analytics, Unity Analytics, GameAnalytics) — добавьте её в разделы 2.2, 3 и 6;
- **покупки** (IAP) — уточните, что платежи обрабатывает магазин, а мы получаем только факт покупки;
- **облачные сохранения / вход** — опишите, какие данные аккаунта хранятся и где;
- **чат или UGC** — понадобится отдельный раздел о модерации и хранении сообщений.

Также обновите дату вступления в силу и версию в начале документа.

## Ссылка для магазинов

- Google Play Console → *App content* → *Privacy policy* → URL сайта.
- App Store Connect → *App Privacy* → *Privacy Policy URL*.
