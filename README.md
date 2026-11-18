<div align="center">

# W1bbex

**Python Backend · Telegram Ecosystem · Systems & Hardware Automation**

Проектирую прикладные сервисы на **Python**: асинхронные бэкенды, Telegram-боты и Mini Apps,  
анализаторы кода (`AST`), CLI-утилиты для `PyPI` и системную автоматизацию под **Windows / Linux / ESP8266**.

<br/>

[![Website](https://img.shields.io/badge/Portfolio-w1bbex.ru-7C3AED?style=for-the-badge&logo=vercel&logoColor=white)](https://w1bbex.ru)
[![Telegram](https://img.shields.io/badge/Telegram-@w1bbex-26A5E4?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/w1bbex)
[![PyPI](https://img.shields.io/badge/PyPI-W1bbex-3775A9?style=for-the-badge&logo=pypi&logoColor=white)](https://pypi.org/user/W1bbex/)

</div>

---

### Открытые проекты

<table>
  <thead>
    <tr>
      <th align="left">Проект</th>
      <th align="left">Что делает</th>
      <th align="left">Стек</th>
      <th align="center">Тесты</th>
      <th align="left">Ссылки</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>PC Control</strong></td>
      <td>Управление ПК до входа в Windows: реле ATX, замок Морзе, <code>Winlogon</code>, VPN и телеметрия <sub><i>(pet-project под личный сетап)</i></sub></td>
      <td><code>Python</code> · <code>ESP8266</code> · <code>Win32</code> · <code>MQTT TLS</code></td>
      <td align="center"><strong>642</strong></td>
      <td><a href="https://github.com/W1bbex/pc-control">GitHub</a> · <a href="https://w1bbex.ru/ru/pc-control/">Кейс</a></td>
    </tr>
    <tr>
      <td><strong>TG-FlowMap</strong></td>
      <td>SAST (<code>Python AST</code>) + DAST (<code>Telethon</code>) карта экранов Telegram-ботов и UX-бенчмаркинг</td>
      <td><code>Python AST</code> · <code>Telethon</code> · <code>SVG</code></td>
      <td align="center"><strong>311</strong></td>
      <td><a href="https://github.com/W1bbex/tg-flowmap">GitHub</a> · <a href="https://pypi.org/project/tg-flowmap/">PyPI</a></td>
    </tr>
    <tr>
      <td><strong>FPC Plugins</strong></td>
      <td>Модульные плагины для FunPay Cardinal: <code>AutoSMM</code> (203 теста) и <code>W1bbex Hub</code> (153 теста)</td>
      <td><code>Python</code> · <code>FastAPI</code> · <code>Cython</code></td>
      <td align="center"><strong>356</strong></td>
      <td><a href="https://github.com/W1bbex/fpc-plugins">GitHub</a></td>
    </tr>
    <tr>
      <td><strong>Nail Atelier</strong></td>
      <td>Онлайн-запись и управление расписанием салона: бот + Telegram Mini App с админкой и RBAC</td>
      <td><code>aiogram 3</code> · <code>FastAPI</code> · <code>SQLAlchemy</code></td>
      <td align="center"><strong>213</strong></td>
      <td><a href="https://github.com/W1bbex/nail-booking-bot">GitHub</a> · <a href="https://t.me/NailsAtelier_app">Демо</a></td>
    </tr>
    <tr>
      <td><strong>W1x CLI</strong></td>
      <td>Терминальный клиент для локальных моделей Ollama с поиском, REPL и долговременной памятью</td>
      <td><code>Python</code> · <code>Ollama</code> · <code>Rich</code></td>
      <td align="center"><strong>126</strong></td>
      <td><a href="https://github.com/W1bbex/w1x-cli">GitHub</a> · <a href="https://pypi.org/project/w1x-cli/">PyPI</a></td>
    </tr>
    <tr>
      <td><strong>FunPay Parser</strong></td>
      <td>Асинхронный ETL-скрапер лотов, отзывов и продавцов с immutable raw-слоем</td>
      <td><code>Python</code> · <code>asyncio</code> · <code>SQLite WAL</code></td>
      <td align="center"><strong>129</strong></td>
      <td><a href="https://github.com/W1bbex/funpay-parser">GitHub</a></td>
    </tr>
  </tbody>
</table>

---

### Технологический стек

<table>
  <tr>
    <td width="190"><strong>Backend &amp; Data</strong></td>
    <td>
      <img src="https://img.shields.io/badge/Python_3.12+-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"/>
      <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI"/>
      <img src="https://img.shields.io/badge/SQLite_WAL-003B57?style=flat-square&logo=sqlite&logoColor=white" alt="SQLite"/>
      <img src="https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat-square&logo=sqlalchemy&logoColor=white" alt="SQLAlchemy"/>
      <img src="https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white" alt="pytest"/>
    </td>
  </tr>
  <tr>
    <td><strong>Telegram &amp; Automation</strong></td>
    <td>
      <img src="https://img.shields.io/badge/Telegram_Bot_API-26A5E4?style=flat-square&logo=telegram&logoColor=white" alt="Telegram Bot API"/>
      <img src="https://img.shields.io/badge/aiogram_3-2CA5E0?style=flat-square&logo=telegram&logoColor=white" alt="aiogram"/>
      <img src="https://img.shields.io/badge/Telethon_MTProto-1E293B?style=flat-square" alt="Telethon"/>
      <img src="https://img.shields.io/badge/Python_AST_(SAST)-4B5563?style=flat-square" alt="Python AST"/>
      <img src="https://img.shields.io/badge/Mini_Apps-7C3AED?style=flat-square" alt="Telegram Mini Apps"/>
    </td>
  </tr>
  <tr>
    <td><strong>Systems &amp; Hardware</strong></td>
    <td>
      <img src="https://img.shields.io/badge/ESP8266_C++-E7352C?style=flat-square&logo=espressif&logoColor=white" alt="ESP8266"/>
      <img src="https://img.shields.io/badge/MQTT_TLS-660066?style=flat-square&logo=eclipse-mosquitto&logoColor=white" alt="MQTT"/>
      <img src="https://img.shields.io/badge/Win32_API-0078D4?style=flat-square&logo=windows&logoColor=white" alt="Win32 API"/>
      <img src="https://img.shields.io/badge/Linux_systemd-FCC624?style=flat-square&logo=linux&logoColor=black" alt="Linux"/>
      <img src="https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white" alt="Nginx"/>
    </td>
  </tr>
</table>

---

<details>
<summary><strong>🇬🇧 English version</strong></summary>

<br/>

I build practical services and tools in **Python**: asynchronous backends, Telegram bots & Mini Apps, static/dynamic code analyzers (`AST`), `PyPI` CLI utilities, and system automation across **Windows, Linux, and ESP8266**.

### Open Source Projects

| Project | Summary | Stack | Tests | Links |
| :--- | :--- | :--- | :---: | :--- |
| **PC Control** | Out-of-band power & remote Windows unlock across Session 0 *(custom pet-project reference)* | `Python` · `ESP8266` · `Win32` · `MQTT TLS` | **642** | [GitHub](https://github.com/W1bbex/pc-control) · [Case](https://w1bbex.ru/en/pc-control/) |
| **TG-FlowMap** | Static AST (`SAST`) + Telethon crawler (`DAST`) screen mapper for Telegram bots | `Python AST` · `Telethon` · `SVG` | **311** | [GitHub](https://github.com/W1bbex/tg-flowmap) · [PyPI](https://pypi.org/project/tg-flowmap/) |
| **FPC Plugins** | Modular FunPay Cardinal plugins: `AutoSMM` (203 tests) & `W1bbex Hub` (153 tests) | `Python` · `FastAPI` · `Cython` | **356** | [GitHub](https://github.com/W1bbex/fpc-plugins) |
| **Nail Atelier** | Beauty studio booking Telegram bot & Mini App with admin panel and RBAC | `aiogram 3` · `FastAPI` · `SQLAlchemy` | **213** | [GitHub](https://github.com/W1bbex/nail-booking-bot) · [Demo](https://t.me/NailsAtelier_app) |
| **W1x CLI** | Keyboard-first CLI client for local Ollama models with tool calling and persistent memory | `Python` · `Ollama` · `Rich` | **126** | [GitHub](https://github.com/W1bbex/w1x-cli) · [PyPI](https://pypi.org/project/w1x-cli/) |
| **FunPay Parser** | Asynchronous ETL scraper and seller/listing analytics on SQLite WAL | `Python` · `asyncio` · `SQLite WAL` | **129** | [GitHub](https://github.com/W1bbex/funpay-parser) |

</details>
