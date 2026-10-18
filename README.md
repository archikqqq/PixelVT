# PixelVT

**EN:** An unofficial Material You (Material Design 3) Android client for the VirusTotal API.
**RU:** Неофициальный Android-клиент для VirusTotal API в стиле Material You (Material Design 3).

![Platform](https://img.shields.io/badge/platform-Android-3DDC84?logo=android&logoColor=white)
![Design](https://img.shields.io/badge/design-Material%203-6750A4)
![License](https://img.shields.io/badge/license-MIT-blue)

[English](#english) | [Русский](#русский)

## English

### About

PixelVT is a lightweight, open-source Android app that talks directly to the VirusTotal API. It brings file, URL, domain and IP lookups to your phone with a clean Material 3 interface, dynamic colors and dark theme support.

This is an independent project and is not affiliated with or endorsed by VirusTotal.

### Features

- Scan files and look up results by hash (MD5 / SHA-1 / SHA-256)
- Check URLs, domains and IP addresses
- Detailed detection report: per-engine verdicts, reputation, tags, file info
- Scan history stored locally on your device
- Material 3 UI with dynamic color (Material You) and dark mode
- Your own API key: requests go straight from your device to VirusTotal, with no middleman server

### Getting started

1. Create a free account at [virustotal.com](https://www.virustotal.com) and copy your API key from your profile.
2. Download the latest APK from the [Releases](../../releases) page, or build it yourself (see below).
3. Open the app, go to Settings and paste your API key.

### Build from source

```bash
git clone https://github.com/archikqqq/PixelVT.git
cd PixelVT
./gradlew assembleDebug
```

The APK will be in `app/build/outputs/apk/debug/`.

Requirements: Android Studio (latest stable), JDK 17, Android 8.0+ device or emulator.

### API limits

The free VirusTotal API key has rate limits (currently 4 requests per minute and a daily quota). The app respects these limits, but heavy use may hit them. Check the official VirusTotal docs for current values.

### Privacy

The app stores your API key and history only on your device. Files and URLs you submit are sent to VirusTotal and may become visible to other VirusTotal users according to their terms. Do not upload sensitive files.

### Contributing

Issues and pull requests are welcome. If you found a bug or have an idea, open an issue.

### License

MIT, see [LICENSE](LICENSE).

## Русский

### О проекте

PixelVT это лёгкое open-source приложение для Android, которое напрямую работает с VirusTotal API. Проверка файлов, ссылок, доменов и IP-адресов прямо с телефона, аккуратный интерфейс на Material 3, динамические цвета и тёмная тема.

Это независимый проект, он никак не связан с VirusTotal и не одобрен ими.

### Возможности

- Сканирование файлов и поиск результатов по хешу (MD5 / SHA-1 / SHA-256)
- Проверка URL, доменов и IP-адресов
- Подробный отчёт: вердикты каждого движка, репутация, теги, информация о файле
- История проверок хранится локально на устройстве
- Интерфейс Material 3 с динамическими цветами (Material You) и тёмной темой
- Свой API-ключ: запросы идут с телефона прямо в VirusTotal, без промежуточных серверов

### Быстрый старт

1. Зарегистрируйся на [virustotal.com](https://www.virustotal.com) и скопируй API-ключ из профиля.
2. Скачай последний APK на странице [Releases](../../releases) или собери сам (см. ниже).
3. Открой приложение, зайди в настройки и вставь API-ключ.

### Сборка из исходников

```bash
git clone https://github.com/archikqqq/PixelVT.git
cd PixelVT
./gradlew assembleDebug
```

APK появится в `app/build/outputs/apk/debug/`.

Требования: свежая стабильная Android Studio, JDK 17, устройство или эмулятор с Android 8.0+.

### Лимиты API

У бесплатного ключа VirusTotal есть ограничения (сейчас 4 запроса в минуту и дневная квота). Приложение учитывает лимиты, но при активном использовании их можно упереть. Актуальные значения смотри в документации VirusTotal.

### Приватность

API-ключ и история хранятся только на твоём устройстве. Файлы и ссылки, которые ты отправляешь, уходят в VirusTotal и по их правилам могут быть доступны другим пользователям сервиса. Не загружай конфиденциальные файлы.

### Участие в разработке

Issues и pull request'ы приветствуются. Нашёл баг или есть идея, открывай issue.

### Лицензия

MIT, см. [LICENSE](LICENSE).
