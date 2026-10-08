# 🐱 Catai
<p align="center">
  <img src="assets/catai-banner.svg" alt="Catai" width="100%" />
</p>

**Локальный ИИ-помощник с собственной базой знаний и интернет-поиском.**

[![GitHub release](https://img.shields.io/github/v/release/Kirill638849776/catai)](https://github.com/Kirill638849776/catai/releases)
[![winget](https://img.shields.io/badge/winget-Kirill638849776.CatAI-blue)](https://winget.run/pkg/Kirill638849776/CatAI)
[![License](https://img.shields.io/badge/license-MIT-blue)](LICENSE)
[![Downloads](https://img.shields.io/github/downloads/Kirill638849776/catai/total)](https://github.com/Kirill638849776/catai/releases)

---

## 📖 О проекте

**Catai** — ИИ-помощник, рассчитанный на локальное использование.

Основные возможности:

- 🧠 работа с локальным файлом `knowledge.txt`;
- 🌐 поиск дополнительной информации в интернете через Wikipedia и DuckDuckGo;
- 💬 диалоговый интерфейс и история сообщений;
- 🧹 очистка истории диалога;
- 😼 собственный характер и немного самоиронии.

### 🔐 Приватность

Локальная база знаний хранится на компьютере пользователя. При использовании интернет-поиска приложение обращается к внешним веб-сервисам, поэтому утверждение «полностью локально» не относится к сетевым запросам.

Не размещайте в `knowledge.txt` пароли, токены, персональные данные или другую информацию, которую нельзя передавать во внешние сервисы, если она может попасть в контекст интернет-поиска или запроса.

---

## 📥 Установка

### Через winget (рекомендуется)

Самый быстрый способ — установить Catai через встроенный менеджер пакетов Windows.

Откройте **PowerShell** или **Терминал** и выполните:

```powershell
winget install Kirill638849776.CatAI
