# USDTZ — project site

Минимальный статический сайт (одна страница) с данными проекта USDTZ:
- Логотип и название
- Контракт: `0xb60aad9d014640067d71b4c2736ac578314daff3`
- Total Supply: `5,000,000,000`
- Ссылка на BscScan

## Локальный запуск

Открой `index.html` в браузере.

## Деплой на GitHub Pages

В репозитории уже есть workflow: `.github/workflows/pages.yml`.

1. Залей код в GitHub (ветка `main`).
2. В GitHub открой **Settings → Pages**.
3. В разделе **Build and deployment** выбери **Source: GitHub Actions**.
4. Сделай push в `main` (или запусти workflow вручную через **Actions**).

После успешного деплоя ссылка появится:
- в **Actions** (в job `deploy`),
- и в **Settings → Pages**.

