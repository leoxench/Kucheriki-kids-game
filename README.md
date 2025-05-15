# 🎯 Addressables в Kucheriki Kids Game

**Addressables** — это система Unity для динамической загрузки контента (сцен, ассетов, ресурсов) во время работы приложения. Это позволяет обновлять контент без полной пересборки игры.

---

## 📦 Где хранятся Addressables?

Все AssetBundles и метаданные игры размещены на GitHub Pages:

👉 [https://leoxench.github.io/Kucheriki-kids-game/StandaloneOSX/catalog.json](https://leoxench.github.io/Kucheriki-kids-game/StandaloneOSX/catalog.json)

Файл `catalog.json` содержит структуру всех доступных ресурсов и их адреса.

---

## ⚙️ Как это работает в проекте

- Сцены **не находятся в Build Settings**
- Все нужные сцены добавлены в **Addressables Groups**
- Загрузка сцены выполняется через:
  ```csharp
  Addressables.LoadSceneAsync("Assets/Scenes/A4_ScrollMenu.unity", LoadSceneMode.Single);
