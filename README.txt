EnshroudedSense 2.2 — DualSense features of the PS5 version for Enshrouded on PC
by MeT1oR and Tianku

[ English ]                                         [ Русский — ниже ]

======================================================================
 BEFORE YOU INSTALL
======================================================================

1. Update the DualSense firmware.
   Install Sony's free PlayStation Accessories app for Windows:
   https://controller.dl.playstation.net/controller/lang/gb/2100004.html
   Connect the controller with a USB cable and install the update if the
   app offers one.

2. Turn Steam Input off for Enshrouded.
   Steam Library > right-click Enshrouded > Properties > Controller >
   "Disable Steam Input".

3. Close DSX, DS4Windows and any other program that controls the DualSense.

4. Use a USB cable. HD haptics and the controller speaker only work over USB.

5. Windows 10 or 11, 64-bit.

======================================================================
 INSTALLATION
======================================================================

1. Close the game.
2. Run EnshroudedSense_Setup_2.2.exe.
   - If Windows says "Windows protected your PC", click "More info" >
     "Run anyway". The installer has no digital signature.
   - Windows asks for administrator rights: the game folder is usually
     inside Program Files.
3. The installer finds a Steam copy of the game by itself. For another
   launcher or a copy somewhere else, click Browse and choose the folder
   that contains enshrouded.exe.
4. Start the game with the DualSense connected.

The installer is in English or Russian, depending on the Windows language.
If the folder already had dinput8.dll or xinput1_4.dll from another mod,
the installer saves them in EnshroudedSense_backup and puts them back when
you uninstall.

======================================================================
 IS IT WORKING?
======================================================================

- In game the lightbar shows your health (green at full health).
- Draw a bow: the right trigger pushes back.
- The game folder now has EnshroudedSense.ini and EnshroudedSense.log.

======================================================================
 SETTINGS
======================================================================

Everything is in EnshroudedSense.ini in the game folder (it appears after
the first start). Change a value, save, restart the game. Delete the file
to get the default settings back.

  Trigger strength ............ [Triggers] Strength (percent)
  Vibration strength .......... [Rumble] Scale, [Haptics] Gain
  Gyro ........................ [Gyro] SensitivityX / SensitivityY
                                Mode: 0 off, 1 while aiming, 2 always
  Lightbar .................... [Lightbar] Mode, Brightness
  Map speed under the finger .. [Touchpad] MapDragSpeed
  Quick item wheel on touch ... [Touchpad] QuickItemWheelOpenOnTouch
  Shield or ward (block feel) . [Block] Offhand = shield / ward
  Touchpad click .............. [Buttons] TouchpadAs: 0 Back, 1 Menu, 2 nothing
  Controller speaker .......... [Speaker] Enabled, Volume

======================================================================
 TROUBLESHOOTING
======================================================================

- Nothing works: check that Steam Input is off for the game and that
  DSX / DS4Windows are closed. If there is no EnshroudedSense.log in the
  game folder, the mod was not loaded: reinstall it into the folder that
  contains enshrouded.exe.
- No HD haptics or speaker sound: connect the controller with a cable and
  do not disable its sound device in Windows ("Wireless Controller").
- Something stopped working after a game update: the mod switches off
  whatever no longer matches the new game version, and the game keeps
  running normally. Wait for a mod update.
- Gyro too weak or too strong: [Gyro] SensitivityX / SensitivityY.

======================================================================
 UNINSTALL
======================================================================

Windows Settings > Apps > EnshroudedSense, or run
EnshroudedSense_Uninstall.exe in the game folder.


######################################################################


[ Русский ]

======================================================================
 ПЕРЕД УСТАНОВКОЙ
======================================================================

1. Обновите прошивку DualSense.
   Установите бесплатное приложение Sony PlayStation Accessories для Windows:
   https://controller.dl.playstation.net/controller/lang/gb/2100004.html
   Подключите геймпад USB-кабелем и установите обновление, если приложение
   его предложит.

2. Выключите Steam Input для Enshrouded.
   Библиотека Steam > правой кнопкой по Enshrouded > Свойства > Контроллер >
   «Отключить Steam Input».

3. Закройте DSX, DS4Windows и другие программы, которые управляют DualSense.

4. Подключайте геймпад кабелем. HD-вибрация и динамик геймпада работают
   только по USB.

5. Windows 10 или 11, 64-бит.

======================================================================
 УСТАНОВКА
======================================================================

1. Закройте игру.
2. Запустите EnshroudedSense_Setup_2.2.exe.
   - Если Windows пишет «Система Windows защитила ваш компьютер», нажмите
     «Подробнее» > «Выполнить в любом случае». У установщика нет цифровой
     подписи.
   - Windows попросит права администратора: папка игры обычно лежит
     в Program Files.
3. Установщик сам находит игру в Steam. Если игра в другом лаунчере или
   в другой папке, нажмите «Обзор...» и выберите папку, где лежит
   enshrouded.exe.
4. Запустите игру с подключённым DualSense.

Установщик на русском или английском — по языку Windows.
Если в папке уже были dinput8.dll или xinput1_4.dll от другого мода,
установщик сохранит их в EnshroudedSense_backup и вернёт при удалении.

======================================================================
 КАК ПРОВЕРИТЬ, ЧТО МОД РАБОТАЕТ
======================================================================

- В игре подсветка геймпада показывает здоровье (при полном — зелёная).
- Натяните лук: правый курок начнёт сопротивляться.
- В папке игры появились EnshroudedSense.ini и EnshroudedSense.log.

======================================================================
 НАСТРОЙКИ
======================================================================

Все настройки — в файле EnshroudedSense.ini в папке игры (появляется после
первого запуска). Измените значение, сохраните файл и перезапустите игру.
Чтобы вернуть всё по умолчанию, удалите файл.

  Сила курков ................. [Triggers] Strength (в процентах)
  Сила вибрации ............... [Rumble] Scale, [Haptics] Gain
  Гироскоп .................... [Gyro] SensitivityX / SensitivityY
                                Mode: 0 выкл, 1 при прицеливании, 2 всегда
  Подсветка ................... [Lightbar] Mode, Brightness
  Скорость карты под пальцем .. [Touchpad] MapDragSpeed
  Колесо предметов по касанию . [Touchpad] QuickItemWheelOpenOnTouch
  Щит или оберег (блок) ....... [Block] Offhand = shield / ward
  Нажатие на тачпад ........... [Buttons] TouchpadAs: 0 «Назад», 1 меню, 2 ничего
  Динамик геймпада ............ [Speaker] Enabled, Volume

======================================================================
 ЕСЛИ ЧТО-ТО НЕ РАБОТАЕТ
======================================================================

- Не работает ничего: проверьте, что Steam Input для игры выключен,
  а DSX и DS4Windows закрыты. Если в папке игры нет EnshroudedSense.log,
  мод не загрузился: переустановите его в папку, где лежит enshrouded.exe.
- Нет HD-вибрации или звука из динамика: подключите геймпад кабелем и не
  отключайте его звуковое устройство в Windows («Wireless Controller»).
- После обновления игры что-то пропало: мод сам отключает то, что
  не совпало с новой версией игры, а игра работает как обычно.
  Дождитесь обновления мода.
- Гироскоп слишком слабый или сильный: [Gyro] SensitivityX / SensitivityY.

======================================================================
 УДАЛЕНИЕ
======================================================================

«Параметры Windows > Приложения > EnshroudedSense» или
EnshroudedSense_Uninstall.exe в папке игры.
