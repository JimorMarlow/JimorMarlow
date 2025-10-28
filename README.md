# 👋 Hello, I'm Jimor Marlow!

Welcome to my GitHub profile! It's my hobby pet projects page.
Добро пожаловать в мой GitHub профиль! 
PS. В основное время я профессиональный C++ программист (25+ лет)

## 🔥 Featured Projects

### 🎯 Arduino & Embedded Systems

#### **[etl (embedded eemplate library)](https://github.com/JimorMarlow/WEMOS_D1_Mini_V4)**
Lightweight C++ template library optimized for embedded systems (Arduino, ESP8266/ESP32). Provides STL-like containers and algorithms with minimal memory footprint. Note: Tested on EPS8266/ESP32 boards only but used only Arduino functions.
Лековесная библиотека с минимально необходимым набором STL-подобных контейров и обработок с максимальным упрощением функционала и компактным использованием памяти. Я проверяю все на ESP8266/ESP32, но ипользую только Arduino функции.

**Features:**
- `etl::vector` легковесный динамический vector для хранения данных
- `etl::queue` упрощенный кольцевой буфер для усреднения и фильтрации входящих данных
- `etl::array` with fixed capacity. Обертка над статическими массивами в оперативной и флеш памяти (RAM, PROGMEM array support)
- `etl::lookup` Lookup tables with interpolation support (например, для NTC температурных датчиков). Таблица с интерполяцией результатов между опорными точками.
- filters: moving average, median3, median5, exponential. Базовый набор для фильтрации выходного сигнала. То, что в Arduino библиотеке должно было быть из коробки.
- Color manipulation utilities
- Memory-efficient algorithms

#### **Other Arduino Projects:**
NOTE: все они так или иначе используют etl.
- **WEMOS_D1_Mini_V4** - Collection of utilities and drivers for WEMOS D1 Mini/ESP32 C3 Mini boards. Test projects for [etl](https://github.com/JimorMarlow/WEMOS_D1_Mini_V4) debug.
- **ESP8266 Templates** - Reusable code patterns for ESP8266 development
- **Sensor Libraries** - Various sensor drivers and data processing utilities

### ⏱️ PuzzleTimer Projects

#### **PuzzleTimer Applications**
Официальное ПО для тайминга Российского Чемпионата по скоростной сборке пазлов.

**Available Platforms:**
- **Windows** - Windows desktop version only. Специально сделано для off-line использования во время проведения чемпионата в условиях ограниченного доступа к Internet.

## 📈 GitHub Stats

![Your GitHub stats](https://github-readme-stats.vercel.app/api?username=JimorMarlow&show_icons=true&theme=radical)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=JimorMarlow&layout=compact&theme=radical)

## 📫 Let's Connect

- 📧 Email: your.email@domain.com
