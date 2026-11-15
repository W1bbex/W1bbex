# W1bbex

**Python Backend • Telegram Ecosystem • Systems & IoT**

Пишу прикладные сервисы на **Python**: бэкенды и Telegram-боты, статические/динамические анализаторы, CLI-инструменты и системную автоматизацию под Windows / Linux и `ESP8266`. Основной фокус — надёжная логика без лишних абстракций, воспроизводимая сборка и реальные тесты.

🌐 **[w1bbex.ru](https://w1bbex.ru)** · 💬 **[Telegram (@w1bbex)](https://t.me/w1bbex)** · 📦 **[PyPI (`w1x-cli`)](https://pypi.org/project/w1x-cli/)**

---

### Открытые проекты

| Репозиторий | Описание | Стек | Тесты |
| :--- | :--- | :--- | :--- |
| **[pc-control](https://github.com/W1bbex/pc-control)** | Удалённое управление ПК до входа в Windows: реле ATX, замок Морзе и `Winlogon` *(reference / pet-project под личный сетап)* | `Python` · `ESP8266` · `Win32 API` · `MQTT TLS` | **608** |
| **[tg-flowmap](https://github.com/W1bbex/tg-flowmap)** | SAST (`Python AST`) и DAST (`Telethon`) карта экранов Telegram-ботов + UX-бенчмаркинг | `Python AST` · `Telethon` · `SVG` | **304** |
| **[fpc-plugins](https://github.com/W1bbex/fpc-plugins)** | Модульные плагины для FunPay Cardinal (`AutoSMM` и клиент автообновлений `W1bbex Hub`) | `Python` · `FastAPI` · `Cython` | **349** |
| **[w1x-cli](https://github.com/W1bbex/w1x-cli)** | Быстрый CLI-клиент для локальных моделей Ollama с tool calling и памятью (`pip install w1x-cli`) | `Python` · `Ollama` · `Rich` | **120** |
| **[funpay-parser](https://github.com/W1bbex/funpay-parser)** | Асинхронный ETL-скрапер и аналитика лотов, отзывов и продавцов | `Python` · `asyncio` · `SQLite WAL` | **100** |
| **[nail-booking-bot](https://github.com/W1bbex/nail-booking-bot)** | Telegram-бот онлайн-записи и Mini App для студии красоты | `Python` · `Telegram Bot API` · `Mini App` | — |
| **[tg-shop-showcase](https://github.com/W1bbex/tg-shop-showcase)** | Архитектурный обзор коммерческого магазина цифровых товаров в Telegram (`@w1bbex_demo_bot`) | `aiogram 3` · `Bot API 10.1` · `SQLite WAL` | **311** |

---

### Основной стек

- **Backend & Data:** `Python 3.12+` · `asyncio` · `FastAPI` · `aiohttp` · `SQLite (WAL)` · `pytest`
- **Telegram:** `Telegram Bot API` · `aiogram 3.x` · `Telethon (MTProto)` · `Mini Apps`
- **Systems & Hardware:** `Win32 API` · `C++ (ESP8266 / BearSSL)` · `MQTT over TLS` · `Linux / systemd / Nginx`

---

<details>
<summary>🇬🇧 English version</summary>

### About

I build practical services and developer tools in **Python**: Telegram bots and backends, static/dynamic analyzers, CLI utilities, and Windows / Linux / `ESP8266` automation. I prefer straightforward architecture, explicit error contracts, and persistent regression test suites.

🌐 **[w1bbex.ru](https://w1bbex.ru/en/dev/)** · 💬 **[Telegram (@w1bbex)](https://t.me/w1bbex)** · 📦 **[PyPI (`w1x-cli`)](https://pypi.org/project/w1x-cli/)**

### Open Source Projects

| Repository | Summary | Stack | Tests |
| :--- | :--- | :--- | :--- |
| **[pc-control](https://github.com/W1bbex/pc-control)** | Out-of-band PC power control and remote Windows unlock across Session 0 *(custom pet-project reference)* | `Python` · `ESP8266` · `Win32 API` · `MQTT TLS` | **608** |
| **[tg-flowmap](https://github.com/W1bbex/tg-flowmap)** | Static AST (`SAST`) + Telethon crawler (`DAST`) screen mapper for Telegram bots | `Python AST` · `Telethon` · `SVG` | **304** |
| **[fpc-plugins](https://github.com/W1bbex/fpc-plugins)** | Modular FunPay Cardinal plugins (`AutoSMM` + `W1bbex Hub` auto-updater) | `Python` · `FastAPI` · `Cython` | **349** |
| **[w1x-cli](https://github.com/W1bbex/w1x-cli)** | Keyboard-first CLI client for local Ollama models with tool calling and memory (`pip install w1x-cli`) | `Python` · `Ollama` · `Rich` | **120** |
| **[funpay-parser](https://github.com/W1bbex/funpay-parser)** | Asynchronous ETL scraper and analytics for marketplace listings and sellers | `Python` · `asyncio` · `SQLite WAL` | **100** |
| **[nail-booking-bot](https://github.com/W1bbex/nail-booking-bot)** | Telegram booking bot and Mini App for beauty studios | `Python` · `Telegram Bot API` · `Mini App` | — |
| **[tg-shop-showcase](https://github.com/W1bbex/tg-shop-showcase)** | Architecture showcase for a Telegram digital storefront (`@w1bbex_demo_bot`) | `aiogram 3` · `Bot API 10.1` · `SQLite WAL` | **311** |

### Core Stack

- **Backend & Data:** `Python 3.12+` · `asyncio` · `FastAPI` · `aiohttp` · `SQLite (WAL)` · `pytest`
- **Telegram:** `Telegram Bot API` · `aiogram 3.x` · `Telethon (MTProto)` · `Mini Apps`
- **Systems & Hardware:** `Win32 API` · `C++ (ESP8266 / BearSSL)` · `MQTT over TLS` · `Linux / systemd / Nginx`

</details>
