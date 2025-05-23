# Kucheriki Kids Game

![](documentation_images/main_menu.png)

Kucheriki Kids Game – это детская игра с возможностью выбора героев и поддержкой дополненной реальности (AR) на основе технологии Vuforia. Проект разработан на Unity 6.

## 📄 Содержание
- [Установка и запуск](#установка-и-запуск)
- [Особенности игры](#особенности-игры)
- [Addressables](#addressables)
- [Технологии](#технологии)
- [Требования](#требования)
- [Как играть](#как-играть)

---

### 🚀 Установка и запуск

1. Скачайте и установите `Unity 6`  
   https://unity.com/download

2. Клонируйте репозиторий:
   ```bash
   git clone https://github.com/your-repo/Kucheriki-kids-game.git


Откройте проект в Unity.

Соберите и запустите приложение на целевой платформе.

🧠 Особенности игры
Различные персонажи

Поддержка AR (Vuforia)

Развивающий игровой процесс

Dynamic content loading через Addressables

## 🎯 Addressables

Игра использует **Addressables** для динамической загрузки контента (сцен и ресурсов).  
Это позволяет обновлять отдельные части без полной пересборки приложения.

📦 Каталог доступен по ссылке:  
👉 [`catalog.json`](https://leoxench.github.io/Kucheriki-kids-game/StandaloneOSX/catalog.json)

### 🔹 Чтобы сцены подгружались корректно:
- Все адреса сцен указаны в `AddressableAssetSettings`
- Загрузка происходит через:
  ```csharp
  Addressables.LoadSceneAsync("sceneAddress", LoadSceneMode.Single);


🛠️ Технологии
Компонент	Назначение
Unity 6	Игровой движок
Vuforia	Дополненная реальность (AR)
Addressables	Система динамической загрузки
C#	Язык программирования

💻 Требования
✅ Unity 6

✅ Vuforia SDK

✅ Редактор кода (VSCode или Visual Studio)

✅ Android или iOS устройство

🎮 Как играть
📱 Запустите приложение

👧 Выберите героя

🕶️ Включите AR-режим

🧩 Взаимодействуйте с элементами

yaml
Copy
Edit
