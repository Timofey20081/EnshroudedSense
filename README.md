# EnshroudedSense

![Platform](https://img.shields.io/badge/Platform-Windows%2010%2F11%20(64--bit)-blue?logo=windows)
![Controller](https://img.shields.io/badge/Controller-DualSense%20%7C%20DualSense%20Edge-003791?logo=playstation)
![Version](https://img.shields.io/badge/Version-2.2-brightgreen)
![Languages](https://img.shields.io/badge/Installer-EN%20%7C%20RU-orange)

**Brings Enshrouded's native PS5 DualSense features to PC** — adaptive triggers, HD haptics, controller speaker, lightbar, gyro aiming, and touchpad controls.

> *Enshrouded's PC version already contains the game's PS5 DualSense code, but most of it never reaches the controller. EnshroudedSense switches it back on — all effects come directly from the game itself.*

*Created by **MeT1oR** and **Tianku***

🌐 **Language / Язык:** [English](#english) • [Русский](#русский)

---

<a name="english"></a>
## 🇬🇧 English

### ✨ Features

* **Adaptive Triggers** — Native trigger resistance and feedback for bows, spells, abilities, and fishing.
* **HD Haptics** — Native PS5-grade vibration for footsteps across different surfaces, hits, shield and ward blocks, and menu clicks.
* **Controller Speaker** — Routes the game's native DualSense audio cues directly to the built-in speaker.
* **Lightbar & Player LEDs** — Dynamic lighting for health status (with a low-health heartbeat pulse), underwater oxygen levels, Shroud timer, and player-number indicators.
* **Gyro Aiming** — Motion-controlled precision aiming while holding `L2`.
* **Touchpad Controls** — Full PS5 touch integration:
  * **Swipe** through the action bar, ammo, songs, loot, building, NPC, and logic lists.
  * **Touch** to open the quick item wheel.
  * **Drag & pinch-zoom** to navigate the map.
  * **Swipe** to switch between menu tabs.
  * **Click** to go Back.

---

### 📋 Before You Install (Requirements)

1. **Update DualSense Firmware:** Install Sony's free [PlayStation® Accessories](https://controller.dl.playstation.net/controller/lang/gb/2100004.html) app for Windows, connect the controller via USB, and install any available firmware update.
2. **Disable Steam Input:** `Steam Library → Right-click Enshrouded → Properties → Controller → Disable Steam Input`.
3. **Close Conflicting Software:** Exit **DSX**, **DS4Windows**, and any other controller emulation tools.
4. **Use a USB Cable:** HD haptics and the controller speaker only work over a wired USB connection.
5. **OS:** Windows 10 or 11 (64-bit).

---

### 🚀 Installation & Uninstallation

#### Installation
1. Close the game.
2. Download and run **`EnshroudedSense_Setup_2.2.exe`** from [**Releases**](../../releases).
   * *If Windows SmartScreen shows **"Windows protected your PC"**, click **More info → Run anyway** (the installer is not digitally signed).*
   * *Administrator rights are requested because the game is usually located inside `Program Files`.*
3. The installer automatically detects your Steam copy. For other launchers or custom paths, click **Browse** and select the folder containing `enshrouded.exe`.
4. Launch the game with your DualSense connected.

> **Mod Compatibility:** The installer interface automatically matches your Windows language (English or Russian). If your game folder already contains `dinput8.dll` or `xinput1_4.dll` from another mod, they are safely backed up to `EnshroudedSense_backup` and restored upon uninstallation.

#### How to Check If It Works
* The lightbar reflects your health (green at full health).
* Draw a bow — the right trigger (`R2`) pushes back.
* `EnshroudedSense.ini` and `EnshroudedSense.log` appear in your game folder.

#### Uninstallation
* Uninstall via **Windows Settings → Apps → EnshroudedSense**, or run **`EnshroudedSense_Uninstall.exe`** in your game folder.

---

### ⚙️ Settings (`EnshroudedSense.ini`)

All settings are stored in **`EnshroudedSense.ini`** inside your game folder (generated on first launch). Edit a value, save, and restart the game. Delete the file to reset to defaults.

| Feature | Section & Parameter | Description |
| :--- | :--- | :--- |
| **Trigger strength** | `[Triggers] Strength` | Resistance strength in percent |
| **Vibration strength** | `[Rumble] Scale`, `[Haptics] Gain` | Standard rumble & HD haptics intensity |
| **Gyro aiming** | `[Gyro] SensitivityX / SensitivityY`, `Mode` | `0` = off, `1` = while aiming, `2` = always |
| **Lightbar** | `[Lightbar] Mode, Brightness` | Lighting behavior and brightness |
| **Map drag speed** | `[Touchpad] MapDragSpeed` | Touchpad map panning sensitivity |
| **Quick item wheel** | `[Touchpad] QuickItemWheelOpenOnTouch` | Open wheel on touchpad touch |
| **Block feel** | `[Block] Offhand` | Shield or ward block feedback |
| **Touchpad click** | `[Buttons] TouchpadAs` | `0` = Back, `1` = Menu, `2` = Nothing |
| **Controller speaker** | `[Speaker] Enabled, Volume` | Enable/disable speaker and adjust volume |

---

### 🛠️ Compatibility & Troubleshooting

* **Game Updates:** Built for the current version of Enshrouded. After a game patch, any signatures that no longer match automatically disable themselves so the game keeps running normally until the mod is updated.
* **Nothing works:** Make sure Steam Input is disabled and DSX / DS4Windows are closed. If `EnshroudedSense.log` is missing in the game folder, reinstall the mod into the exact folder containing `enshrouded.exe`.
* **No HD haptics or speaker sound:** Connect via USB cable and ensure the controller's audio device (*"Wireless Controller"*) is not disabled in Windows Sound settings.
* **Gyro too weak or too strong:** Adjust `[Gyro] SensitivityX` and `SensitivityY` in `EnshroudedSense.ini`.

---
---

<a name="русский"></a>
## 🇷🇺 Русский

**Переносит нативные функции PS5-версии DualSense для Enshrouded на ПК** — адаптивные курки, HD-вибрацию, динамик геймпада, подсветку, гироскоп и управление тачпадом.

> *В ПК-версии Enshrouded уже зашит код поддержки DualSense от версии для PS5, но большая его часть не доходит до контроллера. EnshroudedSense включает его обратно — все эффекты идут напрямую из самой игры.*

*Авторы: **MeT1oR** и **Tianku***

---

### ✨ Возможности

* **Адаптивные курки (Adaptive Triggers)** — родное сопротивление и отдача курков для луков, заклинаний, способностей и рыбалки.
* **HD-вибрация (HD Haptics)** — точная вибрация из PS5-версии: шаги по разным поверхностям, удары, блоки щитом и оберегом, щелчки в меню.
* **Динамик геймпада** — звуки, которые игра отправляет на встроенный динамик DualSense.
* **Подсветка и индикаторы игроков** — цвет здоровья с пульсацией при низком HP, запас кислорода под водой, таймер Пелены (Shroud) и светодиоды номера игрока.
* **Прицеливание гироскопом** — точная доводка прицела наклоном геймпада при зажатом `L2`.
* **Управление тачпадом** — полноценное сенсорное управление с PS5:
  * **Свайпы** для пролистывания панели действий, боеприпасов, песен, лута, строительства, списков NPC и логики.
  * **Касание** открывает колесо быстрого выбора предметов.
  * **Перетаскивание и щипок (pinch-zoom)** для управления картой.
  * **Свайпы** для переключения вкладок меню.
  * **Нажатие** — кнопка «Назад».

---

### 📋 Перед установкой (Требования)

1. **Обновите прошивку DualSense:** установите бесплатное приложение Sony [PlayStation® Accessories](https://controller.dl.playstation.net/controller/lang/gb/2100004.html) для Windows, подключите геймпад USB-кабелем и установите обновление, если оно доступно.
2. **Выключите Steam Input для Enshrouded:** `Библиотека Steam → ПКМ по Enshrouded → Свойства → Контроллер → «Отключить Steam Input»`.
3. **Закройте сторонние программы:** выйдите из **DSX**, **DS4Windows** и любых других утилит для эмуляции геймпадов.
4. **Используйте USB-кабель:** HD-вибрация и динамик геймпада работают только по проводу.
5. **ОС:** Windows 10 или 11 (64-бит).

---

### 🚀 Установка и удаление

#### Установка
1. Закройте игру.
2. Скачайте и запустите **`EnshroudedSense_Setup_2.2.exe`** из раздела [**Releases**](../../releases).
   * *Если Windows покажет окно **«Система Windows защитила ваш компьютер»**, нажмите **Подробнее → Выполнить в любом случае** (у установщика нет цифровой подписи).*
   * *Установщик запросит права администратора, так как папка игры обычно находится в `Program Files`.*
3. Установщик сам найдёт игру в Steam. Если игра установлена в другом лаунчере или папке, нажмите **«Обзор...»** и укажите папку с `enshrouded.exe`.
4. Запустите игру с подключённым DualSense.

> **Совместимость с другими модами:** язык установщика (русский или английский) выбирается автоматически по языку Windows. Если в папке игры уже были `dinput8.dll` или `xinput1_4.dll` от другого мода, установщик сохранит их в `EnshroudedSense_backup` и вернёт на место при удалении.

#### Как проверить, что мод работает
* В игре подсветка геймпада показывает здоровье (при полном — зелёная).
* Натяните лук — правый курок (`R2`) начнёт сопротивляться.
* В папке игры появились файлы `EnshroudedSense.ini` и `EnshroudedSense.log`.

#### Удаление
* Через **Параметры Windows → Приложения → EnshroudedSense**, либо запустите **`EnshroudedSense_Uninstall.exe`** в папке игры.

---

### ⚙️ Настройки (`EnshroudedSense.ini`)

Все настройки находятся в файле **`EnshroudedSense.ini`** в папке игры (создаётся при первом запуске). Измените нужное значение, сохраните файл и перезапустите игру. Чтобы сбросить настройки по умолчанию, просто удалите этот файл.

| Параметр | Раздел и ключ | Описание |
| :--- | :--- | :--- |
| **Сила курков** | `[Triggers] Strength` | Сопротивление курков (в процентах) |
| **Сила вибрации** | `[Rumble] Scale`, `[Haptics] Gain` | Интенсивность обычной и HD-вибрации |
| **Гироскоп** | `[Gyro] SensitivityX / SensitivityY`, `Mode` | `0` — выкл, `1` — при прицеливании, `2` — всегда |
| **Подсветка** | `[Lightbar] Mode, Brightness` | Режим работы и яркость световой панели |
| **Скорость карты** | `[Touchpad] MapDragSpeed` | Чувствительность перемещения карты пальцем |
| **Колесо предметов** | `[Touchpad] QuickItemWheelOpenOnTouch` | Открытие колеса по касанию тачпада |
| **Ощущение блока** | `[Block] Offhand` | Отдача при блоке щитом или оберегом |
| **Нажатие на тачпад** | `[Buttons] TouchpadAs` | `0` — «Назад», `1` — меню, `2` — ничего |
| **Динамик геймпада** | `[Speaker] Enabled, Volume` | Включение/выключение и громкость динамика |

---

### 🛠️ Совместимость и решение проблем

* **Обновления игры:** мод сделан под актуальную версию Enshrouded. После выхода патча игры всё, что перестало совпадать, автоматически отключается само — игра продолжит работать без вылетов, пока вы ждёте обновление мода.
* **Ничего не работает:** проверьте, что Steam Input выключен, а DSX и DS4Windows закрыты. Если в папке игры нет файла `EnshroudedSense.log`, мод не загрузился — переустановите его в папку, где лежит `enshrouded.exe`.
* **Нет HD-вибрации или звука из динамика:** подключите геймпад по USB-кабелю и убедитесь, что его звуковое устройство (*«Wireless Controller»*) не отключено в настройках звука Windows.
* **Гироскоп слишком слабый или резкий:** настройте `[Gyro] SensitivityX` и `SensitivityY` в `EnshroudedSense.ini`.
