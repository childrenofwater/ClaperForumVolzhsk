# Claper — Профориентационный форум г. Волжск

> **Форк открытого проекта [Claper](https://github.com/ClaperCo/Claper)** с добавлением русской локализации и адаптацией для проведения Профориентационного форума в г. Волжск.

[![License: AGPL v3](https://img.shields.io/badge/License-AGPL_v3-blue.svg)](LICENSE.txt)
[![Original Project](https://img.shields.io/badge/Original-ClaperCo%2FClaper-orange)](https://github.com/ClaperCo/Claper)
[![Elixir](https://img.shields.io/badge/elixir-1.18-4B275F?logo=elixir&logoColor=white)](https://elixir-lang.org/)
[![Phoenix](https://img.shields.io/badge/phoenix-1.7-f35424?logo=phoenixframework&logoColor=white)](https://www.phoenixframework.org/)

---

## 🇷🇺 О форке / About this fork

Данный репозиторий представляет собой форк интерактивной презентационной платформы **[Claper](https://github.com/ClaperCo/Claper)**.  
Форк подготовлен в рамках организации форума **«Энергия Молодых»** для вовлечения молодежи и участников форума в реальном времени.

### Основные внесенные изменения (Modifications):
1. **Полная русская локализация пользовательского интерфейса**:
   - Переведены экраны участников (вход по коду сессии, голосования, вопросы спикерам, чат, реакции, смайлы).
   - Переведены интерфейсы докладчиков и модераторов (загрузка презентаций, создание опросов, викторин, форм обратной связи).
   - Локализованы экраны авторизации, сброса пароля и настроек профиля.
   - Настроена поддержка грамматических форм множественного числа для русского языка (`Gettext` plural forms: 1, 2-4, 5+).
2. **Адаптация конфигурации**:
   - Русский язык (`ru`) добавлен в список поддерживаемых локалей и установлен языком по умолчанию.
   - Подготовка окружения для развертывания на площадке форума.

---

## 👏 Благодарности и первоисточник (Attribution & Credits)

Мы выражаем искреннюю благодарность создателю **[Alex Lion](https://github.com/alxlion)** и всем участникам команды **[ClaperCo](https://github.com/ClaperCo)** за создание замечательного инструмента для интерактивных презентаций и предоставление его миру как открытого ПО.

- **Оригинальный репозиторий**: [https://github.com/ClaperCo/Claper](https://github.com/ClaperCo/Claper)
- **Официальный сайт**: [https://claper.co](https://claper.co)
- **Документация Claper**: [https://docs.claper.co](https://docs.claper.co)

Пожалуйста, поддержите оригинальный проект звёздочкой ⭐️ на [GitHub](https://github.com/ClaperCo/Claper)!

---

## 🚀 Быстрый старт (Quick Start)

### С использованием Docker Compose (рекомендуется):

1. **Скопируйте пример настроек окружения**:
   ```bash
   cp .env.sample .env
   ```

2. **Запустите контейнеры**:
   ```bash
   docker compose -f compose.dev.yml up -d
   ```

3. **Инициализируйте базу данных** (при первом запуске):
   ```bash
   docker compose -f compose.dev.yml exec app mix ecto.setup
   ```

4. Откройте приложение в браузере: **[http://localhost:4000](http://localhost:4000)**.

---

## 📜 Лицензия (License)

В полном соответствии с условиями оригинального проекта, этот форк распространяется под свободной лицензией **GNU Affero General Public License v3.0 (AGPL-3.0)**.

- Исходный код остаётся полностью открытым.
- Любые последующие модификации при публичном сетевом использовании должны также публиковаться под лицензией AGPLv3.
- Полный текст лицензии доступен в файле [LICENSE.txt](LICENSE.txt).

Copyright (c) Claper contributors & Alex Lion.
Modifications for Youth Energy (Энергия Молодых) (c) 2026.
