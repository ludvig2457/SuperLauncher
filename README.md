# SuperLauncher

🎮 Лёгкий и быстрый лаунчер для Minecraft с автоматическим обновлением до последних версий.

---

## 🚀 Особенности

- Поддержка последней версии Minecraft (на момент релиза — 1.21.8)  
- Автоматическое обновление лаунчера и Minecraft при выходе новых версий от Mojang  
- Возможность создания и управления своими локальными Minecraft-серверами прямо из лаунчера  
- Панель управления серверами с настройками EULA, онлайн/оффлайн режимом и запуском/остановкой сервера  
- Добавление любых серверов в список для быстрого подключения  
- Поддержка ручного скачивания и управления версиями Minecraft (папка `versions`)  
- Возможность вручную скачивать и использовать модификации Fabric, Forge и OptiFine  
- Лаунчер не требует установки Java — для запуска Minecraft и серверов используется библиотека `minecraft-launcher-lib`  
- Простой и минималистичный интерфейс  

---

## 📁 Что в комплекте

- `super_launcher.exe` — исполняемый файл лаунчера  
- `assets/title.png` — иконка/логотип лаунчера

---

## 🔧 Технологии

- Язык: Python 3.x  
- Компиляция: PyInstaller  
- Для запуска Minecraft и серверов: библиотека [`minecraft-launcher-lib`](https://github.com/TechnicPack/MinecraftLauncherLib)

---

## 📥 Как использовать

1. Скачайте файл `super_launcher.exe` из раздела [релизов](https://github.com/ludvig2457/SuperLauncher/releases)  
2. Запустите файл двойным кликом  
3. Лаунчер автоматически загрузит последнюю версию Minecraft и запустит игру  
4. Для создания и управления серверами используйте встроенную панель управления  
5. При необходимости можно вручную скачивать версии Minecraft и модификации Fabric, Forge и OptiFine, помещая их в соответствующие папки  
6. Наслаждайтесь игрой без лишних настроек и заморочек!

---

## 🆕 Что нового в версии 1.4.0.5

- ✅ Интеграция с Modrinth API для загрузки и управления модами прямо из лаунчера  
- 🎨 Добавлена поддержка светлой и тёмной темы интерфейса  
- ⚙️ Новый выбор способа запуска Minecraft: по умолчанию используется `minecraft-launcher-lib`, опционально можно указать путь к установленной Java  
- 🐞 Исправлены мелкие баги и улучшена стабильность

---

## ❌ Ограничения

- На данный момент не реализована автоматическая поддержка Fabric, Forge и OptiFine — их нужно скачивать и подключать вручную  
- Запуск Minecraft и серверов производится через `minecraft-launcher-lib`, поэтому внешняя Java не требуется  

---

## 🌟 Автор

**Ludvig2457** — [GitHub профиль](https://github.com/ludvig2457)

---

Спасибо за использование SuperLauncher!  
Если есть идеи или баги — создавайте issue или пишите в PR.
