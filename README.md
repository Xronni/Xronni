<div align="center">

# Xronni

**Native desktop software for Linux and Windows.**<br>
Python · GTK4 / Libadwaita · PyQt6 · systems integration · reverse engineering · LLMs

<p>
  <img src="https://img.shields.io/badge/Python-3.10%2B-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python 3.10+">
  <img src="https://img.shields.io/badge/GTK4-Libadwaita-3584E4?style=flat-square&logo=gnome&logoColor=white" alt="GTK4 / Libadwaita">
  <img src="https://img.shields.io/badge/Qt-6-41CD52?style=flat-square&logo=qt&logoColor=white" alt="Qt 6">
  <img src="https://img.shields.io/badge/Linux-X11%20%7C%20D--Bus-FCC624?style=flat-square&logo=linux&logoColor=black" alt="Linux">
  <img src="https://img.shields.io/badge/Windows-10%20%7C%2011-0078D4?style=flat-square&logo=windows11&logoColor=white" alt="Windows 10/11">
  <img src="https://img.shields.io/badge/AI-cloud%20%7C%20local%20GGUF-7C3AED?style=flat-square" alt="AI: cloud and local GGUF">
</p>

<p>
  <a href="#english">English</a> ·
  <a href="#русский">Русский</a> ·
  <a href="https://boosty.to/xronni/single-payment/donation/809763/target?share=target_link">Boosty</a>
</p>

</div>

---

## English

### About

I've been writing code since 2021. Most projects start the same way: a tool almost does what I need, so I dig into how it works and build the version I actually want.

- **Desktop** — GTK4 and Libadwaita on Linux, PyQt6 on Linux and Windows.
- **Systems** — X11/EWMH window handling, D-Bus/MPRIS, git plumbing, LevelDB records, `.deb` packaging.
- **AI** — cloud models (OpenAI, Gemini, DeepSeek, OpenRouter) and local `.gguf` models through `llama-cpp`.

### Projects

#### ⚡ [GitPulse HUD](https://github.com/Xronni/git-pulse-hud)

[![Latest release](https://img.shields.io/github/v/release/Xronni/git-pulse-hud?style=flat-square&label=release&color=0B7285)](https://github.com/Xronni/git-pulse-hud/releases/latest)

A Git companion for Linux: micro-staging, an interactive branch graph, Conventional Commits, a stash inspector, a secret scanner and repository analytics.

- Cairo-drawn branch tree with merge curves and one-click checkout.
- Pre-commit scan of staged diffs for leaked keys, in under 3 ms.
- Commit velocity, a 24-hour punchcard, GitHub traffic and release download stats.

`GTK4` · `Libadwaita` · `Cairo` · `GitHub API` · `Python 3.10+`

#### 🎵 [Spotify Mini Player](https://github.com/Xronni/spotify-mini-player)

[![Latest release](https://img.shields.io/github/v/release/Xronni/spotify-mini-player?style=flat-square&label=release&color=0B7285)](https://github.com/Xronni/spotify-mini-player/releases/latest)

A translucent mini-player and OSD HUD for Spotify on Linux, with the real queue read straight from Spotify's local cache.

- LevelDB parsing reconstructs the queue and history without the Web API or developer tokens.
- Bi-directional volume and playback sync over MPRIS D-Bus; global media keys and CLI flags.
- Four themes, automatic localization (ru/en/de/es/fr), and an OSD that hides when the Spotify window is focused.

`GTK4` · `Libadwaita` · `MPRIS` · `LevelDB` · `Python 3.10+`

#### 📚 [YaRead](https://github.com/Xronni/yaread)

[![Latest release](https://img.shields.io/github/v/release/Xronni/yaread?style=flat-square&label=release&color=0B7285)](https://github.com/Xronni/yaread/releases/latest)

A PyQt6 reader for PDF, EPUB and FB2 with an AI assistant and adaptive soundtracks.

- Select a passage, press **Ask AI**, get an explanation in place.
- Twelve narrative emotions drive smooth crossfades between background loops.
- Cloud providers or local `.gguf` models — with a local model, the text never leaves the machine.
- Builds for Linux (`.deb`, portable archive) and Windows.

`PyQt6` · `PyMuPDF` · `Pygame` · `llama-cpp` · `Python 3.10+`

### Toolbox

| Area | Stack |
| :--- | :--- |
| **Languages** | `Python 3.10+` · `Bash` |
| **Desktop** | `GTK4` · `Libadwaita` · `PyQt6` · `Cairo` · `CSS` |
| **Linux** | `X11 / EWMH` · `D-Bus / MPRIS` · `.deb` packaging |
| **Formats & internals** | `LevelDB` · `git porcelain` · `PDF / EPUB / FB2` |
| **AI** | `OpenAI` · `Gemini` · `DeepSeek` · `OpenRouter` · `llama-cpp` |

---

## Русский

### Обо мне

Пишу код с 2021 года. Почти каждый проект начинается одинаково: готовый инструмент делает почти то, что нужно, — я разбираюсь, как он устроен, и пишу версию, которой мне не хватает.

- **Десктоп** — GTK4 и Libadwaita под Linux, PyQt6 под Linux и Windows.
- **Системы** — работа с окнами через X11/EWMH, D-Bus/MPRIS, внутренности git, записи LevelDB, сборка `.deb`.
- **ИИ** — облачные модели (OpenAI, Gemini, DeepSeek, OpenRouter) и локальные `.gguf` через `llama-cpp`.

### Проекты

#### ⚡ [GitPulse HUD](https://github.com/Xronni/git-pulse-hud)

[![Последний релиз](https://img.shields.io/github/v/release/Xronni/git-pulse-hud?style=flat-square&label=release&color=0B7285)](https://github.com/Xronni/git-pulse-hud/releases/latest)

Git-компаньон для Linux: микро-стейджинг, интерактивный граф веток, Conventional Commits, инспектор stash, сканер секретов и аналитика репозитория.

- Граф веток на Cairo: линии слияний, подсветка коммитов, переключение ветки в один клик.
- Проверка staged-диффа на утёкшие ключи перед коммитом — меньше 3 мс.
- Скорость коммитов, 24-часовой панчкард, трафик GitHub и счётчики скачиваний релизов.

`GTK4` · `Libadwaita` · `Cairo` · `GitHub API` · `Python 3.10+`

#### 🎵 [Spotify Mini Player](https://github.com/Xronni/spotify-mini-player)

[![Последний релиз](https://img.shields.io/github/v/release/Xronni/spotify-mini-player?style=flat-square&label=release&color=0B7285)](https://github.com/Xronni/spotify-mini-player/releases/latest)

Полупрозрачный мини-плеер и OSD HUD для Spotify под Linux — с настоящей очередью из локального кэша.

- Разбор LevelDB восстанавливает очередь и историю без Web API и токенов разработчика.
- Двусторонняя синхронизация громкости и управления по MPRIS D-Bus, глобальные медиаклавиши и CLI-флаги.
- Четыре темы, автолокализация (ru/en/de/es/fr), OSD прячется, когда окно Spotify в фокусе.

`GTK4` · `Libadwaita` · `MPRIS` · `LevelDB` · `Python 3.10+`

#### 📚 [YaRead](https://github.com/Xronni/yaread)

[![Последний релиз](https://img.shields.io/github/v/release/Xronni/yaread?style=flat-square&label=release&color=0B7285)](https://github.com/Xronni/yaread/releases/latest)

Читалка PDF, EPUB и FB2 на PyQt6 с ИИ-помощником и адаптивными саундтреками.

- Выделяешь фрагмент, нажимаешь **Ask AI** — объяснение появляется прямо в тексте.
- Двенадцать эмоций сцены плавно переключают фоновые аудиопетли.
- Облачные провайдеры или локальные `.gguf`-модели: с локальной моделью текст не покидает машину.
- Сборки для Linux (`.deb`, портативный архив) и Windows.

`PyQt6` · `PyMuPDF` · `Pygame` · `llama-cpp` · `Python 3.10+`

### Стек

| Направление | Технологии |
| :--- | :--- |
| **Языки** | `Python 3.10+` · `Bash` |
| **Десктоп** | `GTK4` · `Libadwaita` · `PyQt6` · `Cairo` · `CSS` |
| **Linux** | `X11 / EWMH` · `D-Bus / MPRIS` · сборка `.deb` |
| **Форматы и внутренности** | `LevelDB` · `git porcelain` · `PDF / EPUB / FB2` |
| **ИИ** | `OpenAI` · `Gemini` · `DeepSeek` · `OpenRouter` · `llama-cpp` |

---

<div align="center">
  <sub>If the tool you need doesn't exist — build it.</sub>
</div>
