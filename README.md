# AvrorA Blocks

Тетрис-подобная игра в киберпанк-стиле Авроры. Android-обёртка над WebView, игра лежит в `app/src/main/assets/index.html`.

## Подпись (нужна один раз, чтобы обновления ставились поверх)
Ключ лежит ВНЕ репозитория. В GitHub: **Settings → Secrets and variables → Actions** добавь секреты:
- `KEYSTORE_BASE64` — содержимое KEYSTORE_BASE64.txt
- `KEYSTORE_PASSWORD`, `KEY_PASSWORD`, `KEY_ALIAS` — из SECRETS.txt

Храни `avrora-release.jks` в надёжном месте: без него обновления не встанут поверх.

## Сборка
Пуш в `main` или кнопка **Run workflow** → Actions → скачай артефакт `AvrorA-Blocks` (подписанный APK).
