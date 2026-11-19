<p align="center">
  <img src="docs/og.jpg" alt="Apple Apps — SmartMaster IPA library" width="920">
</p>

<h1 align="center">Apple Apps</h1>

<p align="center">
  <b>Витрина IPA в стиле App Store</b><br>
  TrollStore · Sideloadly · AltServer · Scarlet
</p>

<p align="center">
  <a href="https://smartmaster35rus-dev.github.io/Apple-Apps/"><img alt="App Store" src="https://img.shields.io/badge/Open-App%20Store-007AFF?style=for-the-badge"></a>
  <a href="https://github.com/smartmaster35rus-dev/Apple-Apps/releases/tag/ipa"><img alt="Releases" src="https://img.shields.io/badge/IPA-Releases-111111?style=for-the-badge&logo=github"></a>
  <a href="https://smartmaster35rus-activator.ru/app-install/sideload"><img alt="Site" src="https://img.shields.io/badge/Site-Скачать%20IPA-00c853?style=for-the-badge"></a>
</p>

<p align="center">
  <a href="https://smartmaster35rus-dev.github.io/Apple-Apps/">Открыть витрину</a> ·
  <a href="https://github.com/smartmaster35rus-dev/Apple-Apps/releases">Releases</a> ·
  <a href="https://t.me/SmartMaster35Rus">Telegram</a> ·
  <a href="https://smartmaster35rus-activator.ru/">SmartMaster</a>
</p>

---

## Как устроено

IPA **не лежат в git**. Каталог и иконки — в репозитории, сами файлы — в **GitHub Releases**.

| Что | Где |
|-----|-----|
| Витрина App Store | [GitHub Pages](https://smartmaster35rus-dev.github.io/Apple-Apps/) |
| Каталог | [`docs/apps.json`](docs/apps.json) |
| Скачать IPA | релиз с тегом **`ipa`** |
| Та же витрина на сайте | [Скачать IPA](https://smartmaster35rus-activator.ru/app-install/sideload) |

Ссылка на файл всегда такая:

```
https://github.com/smartmaster35rus-dev/Apple-Apps/releases/download/ipa/<ИмяФайла>.ipa
```

---

## Как залить IPA

1. **Releases → Draft a new release**
2. Tag: `ipa` (если релиз уже есть — Edit и прикрепи файлы туда)
3. Title: `Apple Apps`
4. Прикрепи `.ipa` **точно с этими именами**:

| Приложение | Файл в релизе |
|------------|----------------|
| СберБанк Онлайн | `Sberbank-Online_v17.6.1.ipa` |
| Т-Банк | `T-Bank_v7.13.1.ipa` |
| ВТБ (Сириус) | `Sirius-VTB_v2.0.1.ipa` |
| Альфа-Банк (А-Ключ) | `Alfa-Bank-A-Kluch_v2.0.0.ipa` |
| Газпромбанк | `Gazprombank_v5.6.0.ipa` |
| Яндекс Банк | `Yandex-Bank_v0.234.4.ipa` |
| ЮMoney | `YooMoney_v11.12.0.ipa` |
| МТС Банк | `MTS-Bank_v11.0.0.ipa` |
| Совкомбанк | `Sovcombank_v1.1.1.ipa` |
| Россельхозбанк | `Rosselkhozbank_v1.0.7.ipa` |

5. Publish. Кнопки GET на витрине и на сайте начнут качать файл.

Лимит GitHub: **2 ГБ на один файл**. Большие IPA (Авито и т.п.) сюда не класть — для них OTA в каталоге.

Новое приложение: добавь карточку в админке **IPA Installer → IPA для клиентов**, либо строку в `docs/apps.json`, и приложи файл в тот же релиз `ipa`.

---

## Apps

| | App | Version | iOS | GET |
|---:|-----|---------|-----|-----|
| 1 | СберБанк Онлайн | 17.6.1 | 14.0+ | [GET](https://github.com/smartmaster35rus-dev/Apple-Apps/releases/download/ipa/Sberbank-Online_v17.6.1.ipa) |
| 2 | Т-Банк | 7.13.1 | 14.0+ | [GET](https://github.com/smartmaster35rus-dev/Apple-Apps/releases/download/ipa/T-Bank_v7.13.1.ipa) |
| 3 | ВТБ (Сириус) | 2.0.1 | 16.0+ | [GET](https://github.com/smartmaster35rus-dev/Apple-Apps/releases/download/ipa/Sirius-VTB_v2.0.1.ipa) |
| 4 | Альфа-Банк (А-Ключ) | 2.0.0 | 14.0+ | [GET](https://github.com/smartmaster35rus-dev/Apple-Apps/releases/download/ipa/Alfa-Bank-A-Kluch_v2.0.0.ipa) |
| 5 | Газпромбанк | 5.6.0 | 14.0+ | [GET](https://github.com/smartmaster35rus-dev/Apple-Apps/releases/download/ipa/Gazprombank_v5.6.0.ipa) |
| 6 | Яндекс Банк | 0.234.4 | 14.0+ | [GET](https://github.com/smartmaster35rus-dev/Apple-Apps/releases/download/ipa/Yandex-Bank_v0.234.4.ipa) |
| 7 | ЮMoney | 11.12.0 | 14.0+ | [GET](https://github.com/smartmaster35rus-dev/Apple-Apps/releases/download/ipa/YooMoney_v11.12.0.ipa) |
| 8 | МТС Банк | 11.0.0 | 14.0+ | [GET](https://github.com/smartmaster35rus-dev/Apple-Apps/releases/download/ipa/MTS-Bank_v11.0.0.ipa) |
| 9 | Совкомбанк | 1.1.1 | 14.0+ | [GET](https://github.com/smartmaster35rus-dev/Apple-Apps/releases/download/ipa/Sovcombank_v1.1.1.ipa) |
| 10 | Россельхозбанк | 1.0.7 | 14.0+ | [GET](https://github.com/smartmaster35rus-dev/Apple-Apps/releases/download/ipa/Rosselkhozbank_v1.0.7.ipa) |

---

## GitHub Pages

Settings → Pages → **Deploy from a branch** → `main` / `/docs`.

После этого витрина: **https://smartmaster35rus-dev.github.io/Apple-Apps/**

---

## Контакты

Вологда, Осановский проезд 33 · [+7 999 988-81-58](tel:+79999888158) · [Telegram](https://t.me/SmartMaster35Rus)
