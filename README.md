<div align="center">

  <!-- Typing SVG Header -->
  <a href="https://github.com/Xronni">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&pause=1000&color=00B4D8&center=true&vCenter=true&width=620&lines=Hi%2C+I'm+Xronni+%F0%9F%91%8B;Python%2C+Rust+%26+Go+Systems+Developer;Reverse+Engineering+%26+Desktop+UX;AI-Powered+Apps+%E2%80%A2+Linux+%26+Windows" alt="Typing SVG" />
  </a>

  <p align="center">
    <strong>Software & Reverse Engineering Developer (since 2021)</strong><br>
    Crafting fast native desktop software, diving into OS internals (Linux & Windows), and integrating cutting-edge AI.
  </p>

  <p align="center">
    <img src="https://img.shields.io/badge/Python-3.10%20%7C%203.12-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
    <img src="https://img.shields.io/badge/Rust-1.98%2B-DEA584?style=flat-square&logo=rust&logoColor=white" alt="Rust" />
    <img src="https://img.shields.io/badge/Go-1.26%2B-00ADD8?style=flat-square&logo=go&logoColor=white" alt="Go" />
    <img src="https://img.shields.io/badge/OS-Linux%20%7C%20Windows%2011%2F10-0078D4?style=flat-square&logo=windows11&logoColor=white" alt="OS" />
    <img src="https://img.shields.io/badge/AI-Claude%20%7C%20GGUF%20%7C%20LLMs-7C3AED?style=flat-square" alt="AI" />
    <a href="https://boosty.to/xronni/single-payment/donation/809763/target?share=target_link">
      <img src="https://img.shields.io/badge/Support_on-Boosty-F15F2C?style=flat-square&logo=boosty&logoColor=white" alt="Boosty" />
    </a>
  </p>

  <!-- Language Switcher / Переключатель языка -->
  <p align="center">
    <b>🌐 Language / Язык:</b> 
    <a href="#-english-version">English</a> • 
    <a href="#-русская-версия">Русский</a>
  </p>

</div>

---

## 🇺🇸 English Version

### 👨‍💻 About Me
* ⚙️ **Coding since 2021:** 4+ years of hands-on experience in desktop engineering, R&D, and systems development.
* 🔍 **Reverse Engineering & OS Internals:** Dissecting binary formats, parsing internal caches (e.g. LevelDB write-ahead logs), and interfacing directly with OS windowing and message protocols (Linux X11/D-Bus and Windows 10/11).
* 🧠 **AI Integrations:** Building intelligent tools backed by **Claude (Anthropic)**, OpenAI, Google Gemini, DeepSeek, as well as local offline `.gguf` language models via `llama-cpp`.
* 💻 **Cross-Platform:** Native applications crafted for both **Linux** (GTK4 / Libadwaita) and **Windows 11 / 10** (PyQt6).

---

### 🚀 Featured Projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h3 align="center">🎵 <a href="https://github.com/Xronni/spotify-mini-player">spotify-mini-player</a></h3>
      <p align="center">
        <img src="https://img.shields.io/badge/Linux-GTK4%20%2F%20Libadwaita-3584E4?style=flat-square&logo=gnome" />
        <img src="https://img.shields.io/badge/MPRIS-D--Bus-blueviolet?style=flat-square" />
        <img src="https://img.shields.io/badge/LevelDB-Reverse%20Engineering-4EBA6F?style=flat-square" />
      </p>
      <p>
        Lightweight translucent mini-player & OSD HUD for Spotify on Linux.
      </p>
      <ul>
        <li><b>Zero-API Queue:</b> Reverse-engineered Spotify's local LevelDB cache (WAL blocks and varints) to reconstruct genuine track queues and history without Spotify Web API tokens.</li>
        <li><b>Bi-directional Volume Sync:</b> Real-time volume slider and mouse wheel scrolling synchronized via MPRIS D-Bus.</li>
        <li><b>Smart OSD:</b> Low-latency HUD that auto-hides when Spotify Desktop is focused via X11 <code>ctypes</code>.</li>
      </ul>
      <p align="center">
        <a href="https://github.com/Xronni/spotify-mini-player"><b>View Repository →</b></a>
      </p>
    </td>
    <td width="50%" valign="top">
      <h3 align="center">📚 <a href="https://github.com/Xronni/yaread">YaRead</a></h3>
      <p align="center">
        <img src="https://img.shields.io/badge/Platform-Windows%2011%2F10%20%7C%20Linux-blue?style=flat-square" />
        <img src="https://img.shields.io/badge/AI-Claude%20%7C%20Local%20GGUF-FF6F61?style=flat-square" />
        <img src="https://img.shields.io/badge/GUI-PyQt6-41CD52?style=flat-square&logo=qt" />
      </p>
      <p>
        Intelligent reader with dynamic AI-driven ambient music adapting to story emotions.
      </p>
      <ul>
        <li><b>12 Adaptive Soundtracks:</b> AI analyzes the emotional arc of the narrative in real time and smoothly crossfades ambient loops.</li>
        <li><b>Dual AI Engine:</b> Supports private local models (<code>.gguf</code> via llama-cpp) and top-tier cloud models: <b>Claude</b>, OpenAI, Gemini, and DeepSeek.</li>
        <li><b>Multi-format:</b> High-speed rendering of PDF (PyMuPDF), EPUB, and FB2 with interactive <code>Alt + Drag</code> AI assistant.</li>
      </ul>
      <p align="center">
        <a href="https://github.com/Xronni/yaread"><b>View Repository →</b></a>
      </p>
    </td>
  </tr>
</table>

---

### 🛠 Tech Stack & Toolbox

| Domain | Technologies |
| :--- | :--- |
| **Languages** | `Python 3.10 / 3.12` • `Rust 1.98+` • `Go 1.26+` • `Bash / Shell` • `C / ctypes` |
| **Operating Systems** | `Linux (Ubuntu, Arch, Debian)` • `Windows 11 / 10` |
| **GUI & Systems** | `GTK4` • `Libadwaita` • `PyQt6` • `Cairo` • `X11 Interop` • `D-Bus / MPRIS` • `Win32 API` |
| **AI & LLMs** | `Claude (Anthropic API)` • `OpenAI` • `Google Gemini` • `DeepSeek` • `llama-cpp (.gguf)` |
| **Reverse Eng. & Audio** | `LevelDB WAL & record parsing` • `Protobuf / Varints` • `Pygame Audio Mixer` • `PyMuPDF (fitz)` |

---

## 🇷🇺 Русская версия

### 👨‍💻 Обо мне
* ⚙️ **В разработке с 2021 года:** 4+ года практического опыта в desktop-разработке, системном программировании и R&D.
* 🔍 **Реверс-инжиниринг и системные механизмы:** Исследую бинарные структуры данных, читаю кэш-файлы (LevelDB WAL логи) и взаимодействую напрямую с API операционных систем (**Linux** через D-Bus/X11 и **Windows 11/10**).
* 🧠 **Искусственный Интеллект:** Интегрирую как передовые облачные LLM (**Claude от Anthropic**, OpenAI, Gemini, DeepSeek), так и автономные приватные локальные модели формата `.gguf` через `llama-cpp`.
* 💻 **Кроссплатформенность:** Создаю нативный софт под Linux (GTK4 / Libadwaita) и Windows 11/10 (PyQt6).

---

### 🚀 Проекты

<table>
  <tr>
    <td width="50%" valign="top">
      <h3 align="center">🎵 <a href="https://github.com/Xronni/spotify-mini-player">spotify-mini-player</a></h3>
      <p align="center">
        <img src="https://img.shields.io/badge/Linux-GTK4%20%2F%20Libadwaita-3584E4?style=flat-square&logo=gnome" />
        <img src="https://img.shields.io/badge/MPRIS-D--Bus-blueviolet?style=flat-square" />
        <img src="https://img.shields.io/badge/LevelDB-Reverse%20Engineering-4EBA6F?style=flat-square" />
      </p>
      <p>
        Элегантный полупрозрачный мини-плеер и OSD HUD для Spotify под Linux.
      </p>
      <ul>
        <li><b>Очередь без API:</b> Реверс-инжиниринг локальной базы LevelDB Spotify (декодирование WAL-блоков и varint) для извлечения реальной очереди треков без необходимости заводить API-ключи разработчика.</li>
        <li><b>Двусторонняя синхронизация звука:</b> Мгновенный отклик ползунка и колесика мыши по протоколу MPRIS D-Bus.</li>
        <li><b>Умный OSD:</b> Автоматическое скрытие виджета при фокусе на основном окне Spotify через <code>ctypes</code> X11.</li>
      </ul>
      <p align="center">
        <a href="https://github.com/Xronni/spotify-mini-player"><b>Перейти в репозиторий →</b></a>
      </p>
    </td>
    <td width="50%" valign="top">
      <h3 align="center">📚 <a href="https://github.com/Xronni/yaread">YaRead</a></h3>
      <p align="center">
        <img src="https://img.shields.io/badge/Платформа-Windows%2011%2F10%20%7C%20Linux-blue?style=flat-square" />
        <img src="https://img.shields.io/badge/ИИ-Claude%20%7C%20Локальный%20GGUF-FF6F61?style=flat-square" />
        <img src="https://img.shields.io/badge/Интерфейс-PyQt6-41CD52?style=flat-square&logo=qt" />
      </p>
      <p>
        Умная читалка книг с динамической сменой атмосферного саундтрека под эмоциональный тон сюжета.
      </p>
      <ul>
        <li><b>12 адаптивных саундтреков:</b> ИИ в реальном времени анализирует тональность сцены и плавно микширует звуковые петли.</li>
        <li><b>Гибридный ИИ-движок:</b> Работа с ведущими моделями: <b>Claude</b>, OpenAI, Gemini, DeepSeek, а также полная приватность с локальными <code>.gguf</code> моделями (Qwen/LLaMA).</li>
        <li><b>Форматы:</b> Быстрый рендеринг PDF, EPUB, FB2 и контекстный ИИ-помощник по <code>Alt + Drag</code>.</li>
      </ul>
      <p align="center">
        <a href="https://github.com/Xronni/yaread"><b>Перейти в репозиторий →</b></a>
      </p>
    </td>
  </tr>
</table>

---

### 🛠 Технологический стек

| Направление | Стек и инструменты |
| :--- | :--- |
| **Языки** | `Python 3.10 / 3.12` • `Rust 1.98+` • `Go 1.26+` • `Bash / Shell` • `C / ctypes` |
| **Операционные системы** | `Linux (Ubuntu, Arch, Debian)` • `Windows 11 / 10` |
| **GUI и системы** | `GTK4` • `Libadwaita` • `PyQt6` • `Cairo` • `X11 Interop` • `D-Bus / MPRIS` • `Win32 API` |
| **Искусственный Интеллект** | `Claude (Anthropic API)` • `OpenAI` • `Google Gemini` • `DeepSeek` • `llama-cpp (.gguf)` |
| **Реверс и медиа** | `Парсинг LevelDB WAL & binary` • `Protobuf / Varints` • `Pygame Audio Mixer` • `PyMuPDF (fitz)` |

---

### 📈 GitHub Overview

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Xronni&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" height="155" alt="GitHub Stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Xronni&layout=compact&theme=tokyonight&hide_border=true" height="155" alt="Top Langs" />
</div>

---

<div align="center">
  <sub>⭐️ <i>«If it doesn't exist or doesn't work the way it should — reverse engineer it and build your own.»</i></sub>
</div>
