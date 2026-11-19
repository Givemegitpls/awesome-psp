# Awesome PlayStation Portable Homebrew

Подборка homebrew для PSP: прошивки, плагины, эмуляторы, нативные порты и утилиты.

> Нужна консоль с кастомной прошивкой (ARK-4 или ARK-5) и карта Memory Stick PRO Duo.
> Проекты помечены как `со своими копиями игры` там, где нужны собственные файлы игры.

Каталог homebrew и архив старых сборок: [PSP-Archive](https://github.com/PSP-Archive) (532 репозитория, включая исходники давно закрытых проектов) и [PSP-Archive.github.io](https://github.com/PSP-Archive/PSP-Archive.github.io). Официальная база homebrew с данными для инсталляторов — [pspdev/homebrew](https://github.com/pspdev/homebrew), справка по кодам ошибок и ремонту — [PSP Homebrew Community Wiki](https://github.com/psp-homebrew-community/wiki).

## Содержание

- [Прошивка и загрузка](#прошивка-и-загрузка)
- [Меню, файлы, медиа](#меню-файлы-медиа)
- [Кастомизация и плагины](#кастомизация-и-плагины)
- [Железо](#железо)
- [Сохранения и читы](#сохранения-и-читы)
- [Эмуляторы](#эмуляторы)
- [Нативные порты](#нативные-порты)
- [Игры PSP на других платформах](#игры-psp-на-других-платформах)
- [Для разработки](#для-разработки)
- [Серая зона](#серая-зона)
- [Legacy](#legacy)

## Прошивка и загрузка

- [ARK-5](https://github.com/PSP-Arkfive/ARK-5) — актуальная кастомная прошивка для PSP и ePSP на Vita, живая разработка (ранее — ARK-4).
- [ARK-4](https://github.com/PSP-Archive/ARK-4) — предыдущая ветка, репозиторий заархивирован: сборки, плагины и инструкции остались.
- [FasterARK](https://github.com/PSP-Arkfive/FasterARK) — установщик и загрузчик ARK для PSP и Vita; полная сборка несёт DC10, ARK-150, LEDA, кастомный лаунчер и VSH-меню.
- [DC10 (Despertar Del Cementerio)](https://github.com/PSP-Arkfive/Despertar-Del-Cementerio) — восстановление «кирпичей», актуальная сборка под 6.61. С ARK 5.1.0 / DC 10.12 починен WLAN на поздних PSP-3000 (ревизии 07g и 09g): в манифестах flash0 не хватало `vsh/module/netconf_plugin.prx`, из-за чего не открывались «Настройки сети», а обновление по сети вешало консоль.
- [ARK-150](https://github.com/PSP-Arkfive/ARK-150) — ARK на ядре 1.50 для PSP-1000: двойная загрузка и старое homebrew; на 2K и новее вместо него ставят плагин LEDA.
- [TimeMachine](https://github.com/PSP-Arkfive/TimeMachine) — установка и загрузка прошивки и CFW целиком с карты памяти.
- [M33-7](https://github.com/PSP-Arkfive/M33-7), [PRO-D](https://github.com/PSP-Arkfive/PRO-D), [LME-3](https://github.com/PSP-Arkfive/LME-3) — обновлённые ревизии старых CFW M33, PRO и LME из архивов сцены.
- [Launcher-Menus](https://github.com/PSP-Arkfive/Launcher-Menus) — набор кастомных меню лаунчера на случай, когда XMB недоступен.
- [Chronoswitch](https://github.com/PSP-Archive/Chronoswitch) — даунгрейдер прошивки, откат на нужную версию.
- [LibPspExploit](https://github.com/PSP-Archive/LibPspExploit) — библиотека ядерных эксплойтов, база для собственных загрузчиков.
- [Universal Flash Dumper](https://github.com/PSP-Archive/Universal-Flash-Dumper) — дамп флеш-памяти консоли на большинстве прошивок.

## Меню, файлы, медиа

- [psp5](https://github.com/08Weber/psp5) — тёмный лаунчер игр под ARK-5, заменяет штатный список.
- [CMFileManager-PSP](https://github.com/joel16/CMFileManager-PSP) — файловый менеджер в духе CM: копирование, архивы, запуск.
- [PSP-FTPD](https://github.com/PSP-Archive/PSP-FTPD) — FTP-сервер прямо на консоли.
- [PocketSend-PSP](https://github.com/caesarium25/PocketSend-PSP) — передача файлов с ПК и телефона по протоколу LocalSend.
- [RemoteJoyLite](https://github.com/PSP-Archive/RemoteJoyLite) — плагин, выводит экран консоли на ПК по USB.
- [PSP-LCDC-Capture](https://github.com/mayuta212/PSP-LCDC-Capture) — захват видео и звука по USB одним кабелем, отдельный PRX под ARK-5.
- [PSPdisp](https://github.com/PSP-Archive/PSPdisp) — PSP как второй монитор Windows.
- [Moonlight-PSP](https://github.com/k4idyn/Moonlight-PSP) — стриминг игр с ПК через Sunshine, аппаратное декодирование H.264.
- [PSPWrite](https://github.com/PSP-Archive/PSPWrite) — текстовый редактор.
- [WiliMini](https://github.com/wilimini/WiliMini) — клиент Bilibili.
- [PSPotify ME](https://github.com/Luxotick/PSPotify-ME) — нативный клиент Spotify, Media Engine декодирует Ogg Vorbis, XMB-интерфейс с темами. Требует Premium, проект в разработке.
- [YMPSP](https://github.com/amdray/yandex_music_psp) — клиент Yandex Music: плейлисты, поиск, стриминг и кэш, TLS 1.2 через mbedTLS, MP3 до 320 kbps на sceMp3.
- [MapThis](https://github.com/PSP-Archive/MapThis) — просмотр карт.
- [pbp-unpacker](https://github.com/PSP-Archive/pbp-unpacker) — разборка и сборка PBP под Windows.
- [UMD Region Changer](https://github.com/PSP-Archive/UMD_Region_Changer) — смена региона UMD.

## Кастомизация и плагины

- [CXMB](https://github.com/PSP-Archive/CXMB) — плагин кастомных тем оформления XMB.
- [wavezbg](https://github.com/koutsie/wavezbg) — свои волны на фоне XMB, проверено на ARK-5.
- [vshbgm](https://github.com/PSP-Archive/vshbgm) — фоновая музыка в XMB.
- [Game Categories Lite](https://github.com/codestation/gclite) — категории игр в меню.
- [btfree-ark](https://github.com/Hirador/btfree-ark) — разблокировка Bluetooth на PSP Go, работает на 6.61 с ARK-4 и ARK-5.
- [BatteryGuardPro](https://github.com/XirnoTV/BatteryGuardPro-for-main-psp-street) — фикс VRAM-багов в тяжёлых играх (NFS, MHFU), работает на всех ревизиях.
- [GTANativeRes](https://github.com/TheOfficialFloW/GTANativeRes) — патч внутреннего разрешения GTA: LCS и VCS (архив).
- [psp-gta_trophies](https://github.com/Freakler/psp-gta_trophies) — трофеи для Liberty City Stories и Vice City Stories.
- [Gran Turismo PSP Career](https://github.com/Memetrix/gran-turismo-psp-career) — фанатский патч: карьера в GT PSP, пять вырезанных трасс и 32 машины.

## Железо

Аппаратные моды и расширения: часть требует пайки или второй платы рядом.

- [PSP-Bluetooth](https://github.com/ste2425/PSP-Bluetooth) — ESP32 вместо UMD-привода: Bluetooth-геймпады на PSP-1000/2000/3000.
- [PSPExp](https://github.com/pleft/PSPExp) — PSP-1000 с CFW плюс Linux-плата по USB: плата запускает игры, PSP выводит картинку, звук и ввод.
- [psp-wlan-linux](https://github.com/zeroootwo/psp-wlan-linux) — Wi-Fi под uClinux на PSP-3000: драйвер WLAN-чипа, WPA2-суппликант и супервизор подключения, настоящий `wlan0` с DHCP, DNS и TCP. Wi-Fi чип впервые заработал под Linux; протокол описан в репозитории. Нужна своя прошивка чипа из дампа консоли.

## Сохранения и читы

- [Apollo Save Tool](https://github.com/bucanero/apollo-psp) — менеджер сейвов: бэкап, восстановление, подмена.
- [Apollo Saves](https://github.com/bucanero/apollo-saves) — онлайн-база готовых сохранений.
- [CWCheat Database Plus](https://github.com/Saramagrean/CWCheat-Database-Plus-) — большая база кодов для CWCheat и PPSSPP.
- [TempAR](https://github.com/Yohoki/TempAR-Vita) — поиск указателей и читы, версия для Vita работает и с PSP-играми.

## Эмуляторы

- [RetroArch](https://github.com/libretro/RetroArch) — оболочка с ядрами от NES до PS1.
- [DaedalusX64](https://github.com/DaedalusX64/daedalus) — Nintendo 64.
- [gpSP](https://github.com/PSP-Archive/gpsp) — Game Boy Advance от Exophase, эталон скорости.
- [unofficial-gpSP-kai](https://github.com/PSP-Archive/unofficial-gpSP-kai) — форк gpSP от Takka с доработками.
- [GBA-Rush-PSP](https://github.com/redcode9/GBA-Rush-PSP) — GBA-эмулятор, форк TempGBA4PSP-mod с упором на скорость.
- [snes9xTYL](https://github.com/173210/snes9xTYL) — Super Nintendo.
- [Snes9x Euphoria](https://github.com/BASLQC/snes9x-euphoria) — продолжение snes9xTYL.
- [PicoDrive](https://github.com/PSP-Archive/PicoDrive-notaz) — Sega Mega Drive / Genesis.
- [MasterBoy](https://github.com/PSP-Archive/MasterBoy) — Game Boy, Game Boy Color, Master System, Game Gear.
- [InfoNES](https://github.com/PSP-Archive/InfoNES) — NES / Famicom.
- [PCE-for-PSP](https://github.com/PSP-Archive/PCE-for-PSP) — PC Engine / TurboGrafx-16.
- [FBA4PSP](https://github.com/PSP-Archive/FBA4PSP-original) — Final Burn Alpha: CPS1, CPS2, Neo Geo.
- [oswanpsp](https://github.com/PSP-Archive/oswanpsp) — WonderSwan.
- [PSPVice](https://github.com/PSP-Archive/PSPVice) — Commodore 64.
- [PSP-UAE4ALL](https://github.com/PSP-Archive/PSP-UAE4ALL) — Amiga, порт TTYman.
- [DOSBox](https://github.com/PSP-Archive/dosbox_psp) — DOS-игры, порт crazyc.
- [MAME4ALL](https://github.com/PSP-Archive/PSP-MAME4ALL) — аркадные автоматы на MAME 0.34.
- [nulldce-psp](https://github.com/PSP-Archive/nulldce-psp) — Sega Dreamcast, экспериментальный.
- [ScummVM](https://github.com/scummvm/scummvm) — квесты LucasArts и Sierra, PSP-сборки в upstream.

## Нативные порты

Порты сгруппированы по платформе, с которой перенесена игра. Часть проектов — нативные движки, которые читают данные из вашего диска или сборки игры.

### PlayStation 2

- [re3psp](https://github.com/st1x51/re3psp_files) — GTA III на движке re3: архив с файлами порта плюс `Re3PSPTools`, который за ~10 минут собирает репак из вашей папки с игрой. Известен сюжетный баг на миссии «Sayonara Salvatore». `со своими копиями игры`
- **GTA: Vice City** — нативная сборка reVC на PSP, публичного репозитория нет, только демонстрации: [видео](https://www.youtube.com/watch?v=KxtUNkSuoc4), [ещё одно](https://www.youtube.com/watch?v=hZkrVOQR-MU). `со своими копиями игры`
- [Sandstone Engine](https://github.com/SandstoneDev/sandstone-engine) + [Quarry](https://github.com/SandstoneDev/quarry) — GTA: San Andreas (PS2) на PSP: нативный движок и конвертер данных из своего образа диска (мир, машины, HUD, интерьеры, радио, катсцены, миссии). Официально игра в README не названа. `со своими копиями игры`
- [shar-psp-engine](https://github.com/robvagin/shar-psp-engine) — The Simpsons: Hit & Run (PS2), нативный движок на PSPSDK, данные конвертируются из своего диска. `со своими копиями игры`

### Nintendo 64

- [oot-PSP](https://github.com/z2442/oot-PSP) — The Legend of Zelda: Ocarina of Time из декомпиляции, сборки в CI на каждый пуш; нужен свой ROM NTSC 1.0. `со своими копиями игры`

### J2ME и мобильные

- [Gravity Defied PSP](https://github.com/antim0118/gravity_defied_psp) — полный порт легендарного мотокросса на PSP: весь контент оригинала, gLib2D и intraFont, готовые сборки на [GameJolt](https://gamejolt.com/games/gravitydefiedpsp/1060552).
- [Gravity Defied SDL2](https://github.com/den4iklovelinux/gravity_defied_psp) — база порта на SDL2, промежуточный репозиторий для сборки под другие платформы.
- [gravity_defied_cpp](https://github.com/rgimad/gravity_defied_cpp) — исходный C++ порт с J2ME, от которого идут обе PSP-версии.
- [DoomRPG4PSP](https://github.com/dadcapgamer/DoomRPG4PSP) — Doom RPG (мобильная Java-игра) нативно на PSP.
- [WolfensteinRPG4PSP](https://github.com/dadcapgamer/WolfensteinRPG4PSP) — Wolfenstein RPG нативно на PSP, на базе WolfensteinRPG-RE.
- [Minecraft PE PSP](https://github.com/Pencea-Flavius/Minecraft-PE-PSP) — порт Minecraft Pocket Edition 0.6.1: мир, мобы, крафт, сохранения; работает и на PSP-1000.
- [Minecraft Story Mode](https://github.com/entitybtw/mcsm_portable) — Minecraft Story Mode: Season 1, Netflix Edition.

### ПК

- [OpenUG2-PSP](https://github.com/jussimir-labs/OpenUG2-PSP) — Need for Speed: Underground 2, нативный порт. Открытая бета 0.4.0: готовый `EBOOT.PBP` плюс генератор данных из своего образа диска для Windows x64, Linux x86-64 (включая SteamOS) и macOS; нужен образ NTSC-U — PS2 `SLUS_210.65` или Xbox. Инвайт не нужен, баг-репорты через GitHub issues. `со своими копиями игры`
- [OMORI](https://github.com/meetox80/omori) — OMORI на PSP: движок RPG Maker MV, переписанный с нуля на C++, сборка ~1.6 ГБ из своей Steam-копии, работает на железе; PSP-1000 получает урезанный режим памяти. `со своими копиями игры`
- [Insomnia ProQuake](https://github.com/darkduke606/Insomnia-ProQuake-Engine) — Quake с аппаратным рендером.
- [DQuakePlus](https://github.com/st1x51/DQuakePlus) — ещё один движок Quake для PSP.
- [Quake II PSP](https://github.com/PSP-Archive/Quake-II-PSP) — Quake II, порт McZonk. `со своими копиями игры`
- [ioQuake3-PSP](https://github.com/Mayo1970/ioQuake3-PSP) — Quake III Arena.
- [Quake3PSP-mirror](https://github.com/Fighter19/Quake3PSP-mirror) — зеркало классического порта Quake III на случай потери оригинала.
- [jfduke3d_psp](https://github.com/PSP-Archive/jfduke3d_psp) — Duke Nukem 3D на JonoF Duke 3D. `со своими копиями игры`
- [Wolf3D-PSP](https://github.com/BenMcLean/Wolf3D-PSP) — Wolfenstein 3D, исходный порт Zack и Chilly Willy. `со своими копиями игры`
- [wolf3Dpsp](https://github.com/Wa59/wolf3Dpsp) — тот же Wolfenstein 3D с автобегом, картой и правильным соотношением сторон. `со своими копиями игры`
- [Rise of the Triad PSP](https://github.com/PSP-Archive/Rise-Of-The-Triad-PSP) — Rise of the Triad. `со своими копиями игры`
- [psp-heretic](https://github.com/PSP-Archive/psp-heretic) — Heretic на движке Chocolate Doom. `со своими копиями игры`
- [Jazz Jackrabbit PSP](https://github.com/PSP-Archive/Jazz-JackRabbit-PSP) — Jazz Jackrabbit, порт Deniska. `со своими копиями игры`
- [Commander Keen PSP](https://github.com/PSP-Archive/Commander-Keen-PSP) — Commander Keen на CloneKeen. `со своими копиями игры`
- [Aquaria PSP](https://github.com/PSP-Archive/aquaria-psp) — Aquaria, порт Andrew Church. `со своими копиями игры`
- [xclannad](https://github.com/PSP-Archive/xclannad) — движок для визуальной новеллы Clannad. `со своими копиями игры`
- [Helltaker PSP](https://github.com/surelynotvain/helltaker-psp) — Helltaker и Examtaker как демейк на нативном C-движке, играбельно на железе.
- [Touhou 6 PSP](https://github.com/kan8223-dotcom/th06-psp-native) — Embodiment of Scarlet Devil, нативный порт; нужны данные оригинальной игры. `со своими копиями игры`
- [Touhou 10 PSP](https://github.com/kan8223-dotcom/th10-psp-native) — Mountain of Faith, один EBOOT на все модели PSP. `со своими копиями игры`
- [REminiscencePSP](https://github.com/PSP-Archive/REminiscencePSP) — Flashback: The Quest for Identity, порт Sektor. `со своими копиями игры`

### Открытые движки и игры

- [Kurok](https://github.com/TheMrIron2/kurok) — открытый шутер на движке Quake под PSP.
- [Abuse](https://github.com/PSP-Archive/Abuse) — Abuse-SDL, мрачный платформер-стрелялка.
- [C-Dogs SDL](https://github.com/PSP-Archive/CDogs) — C-Dogs, кооперативный top-down шутер.
- [OpenTyrian](https://github.com/PSP-Archive/Open-Tyrian-PSP) — OpenTyrian, вертикальный скролл-шутер.
- [OpenTTD PSP](https://github.com/PSP-Archive/OpenTTD-PSP) — OpenTTD, экономическая стратегия про транспорт.
- [MUGEN (infcat)](https://github.com/PSP-Archive/infcat) — движок MUGEN, нужны свои пакеты персонажей. `со своими копиями игры`
- [Frontier Elite II](https://github.com/PSP-Archive/Frontier-1337) — космический симулятор Frontier: Elite II.
- [Champyonshipp Kaiten Patissier](https://github.com/PSP-Archive/Champyonshipp-Kaiten-Patissier) — открытая игра Alpha Secret Base, порт MK2k.
- [Gannatsu Portable](https://github.com/PSP-Archive/Gannatsu-Portable) — Ganbare Natsuki-san от Alpha Secret Base.

## Игры PSP на других платформах

- [PPSSPP](https://github.com/hrydgard/ppsspp) — эмулятор PSP для ПК, Android, iOS и консолей.
- [PSPRecomp](https://github.com/jessicanataliagta/PSPRecomp) — фреймворк статической рекомпиляции PSP-игр: Allegrex MIPS в нативный код.
- [psp-web-recomp](https://github.com/snuri00/psp-web-recomp) — рекомпиляция PSP-игр в WebAssembly: браузер, HLE-ядро, WebGL2.
- [Nakagawa-Recomp](https://github.com/Jstar269/Nakagawa-Recomp) — статический рекомпилятор: свой диск PSP превращается в программу под Windows. `со своими копиями игры`
- [God of War PSP Recomp](https://github.com/DrummingBird1/gow-psp-recomp) — Chains of Olympus и Ghost of Sparta нативно на ПК. `со своими копиями игры`
- [MHForever](https://github.com/Mango77x/MHForever) — Monster Hunter Freedom Unite нативно на ПК, без эмулятора. `со своими копиями игры`
- [azazel6](https://github.com/zxyandreay/azazel6) — Tekken 6 (PSP) нативно на Android ARM64 через статическую рекомпиляцию. Пока исследование: загрузка доходит до инициализации графики, игра не запускается. `со своими копиями игры`
- [sims2-psp-recomp](https://github.com/tokenbroker/sims2-psp-recomp) — The Sims 2 (PSP) нативно на ПК: Vulkan, Windows и Linux, Wayland/X11. `со своими копиями игры`
- [swbes-recomp](https://github.com/Revgith/swbes-recomp) — Star Wars Battlefront: Elite Squadron (PSP) нативно на ПК. `со своими копиями игры`
- [PSBridge](https://github.com/eclipsebladestudioficial/PSBridge) — обратное направление: PSP-софт на PS2 через трансляцию вызовов.
- [sp00nznet/psprecomp](https://github.com/sp00nznet/psprecomp) — альтернативный тулкит рекомпиляции PSP в C.
- [Yakumo](https://github.com/TeamGDB/Yakumo) — рекомпиляция PSP-игры в нативный исполняемый файл, Vulkan и SDL3. `со своими копиями игры`
- [fuc-recomp](https://github.com/elprogramadorloco-arch/fuc-recomp) — гибрид: геймплей PS2-версии Fate/unlimited codes с PSP-ассетами и управлением. `со своими копиями игры`
- [PSPRecomp-LCS-Android](https://github.com/codepdbh/PSPRecomp-LCS-Android) — GTA: Liberty City Stories (PSP) нативно на Android. `со своими копиями игры`
- [PSPRecomp-VCS-Android](https://github.com/codepdbh/PSPRecomp-VCS-Android) — то же для Vice City Stories. `со своими копиями игры`
- [CarsPSPRecomp](https://github.com/DanielPerezL/CarsPSPRecomp) — Disney/Pixar Cars (PSP) нативно на ПК. `со своими копиями игры`
- [ygo-tf-5-decomp](https://github.com/angelof-exe/ygo-tf-5-decomp) — декомпиляция Yu-Gi-Oh! 5D's Tag Force 5.
- [daxter-psp-decomp](https://github.com/llesieur99/daxter-psp-decomp) — matching-декомпиляция Daxter.

## Для разработки

- [pspsdk](https://github.com/pspdev/pspsdk) — официальный SDK: тулчейн, libc, документация.
- [pspdev](https://github.com/pspdev/pspdev) — Docker-образ со всем тулчейном для сборки под PSP.
- [psp-forge](https://github.com/Hauntlight/psp-forge) — all-in-one CLI, пайплайн ассетов и микро-движок на C99.
- [AMGLib-Plus](https://github.com/jopadan/AMGLib-Plus) — 3D-движок и утилиты для PSPSDK.
- [rust-psp](https://github.com/overdrivenpotato/rust-psp) — Rust на PSP: паника, аллокатор, доступ к системным библиотекам.
- [Zig-PSP](https://github.com/zPSP-Dev/Zig-PSP) — Zig для PSP.
- [psplinkusb](https://github.com/pspdev/psplinkusb) — запуск и отладка homebrew по USB.
- [UOFW](https://github.com/uofw/uofw) — реверс официальной прошивки целиком.
- [box3d-psp](https://github.com/Saymond/box3d-psp) — физика Box3D с ускорением через VFPU и рендером GU.
- [MicroAllegrex](https://github.com/Goatman13/MicroAllegrex) — плагин Allegrex для декомпилятора IDA Hex-Rays.
- [ghidra-allegrex](https://github.com/kotcrab/ghidra-allegrex) — модуль процессора Allegrex для Ghidra.
- [PSP-Homebrew-Dev-Notes](https://github.com/JustKidding23/PSP-Homebrew-Dev-Notes) — особенности железа PSP, IO карты памяти и отличия от PPSSPP.
- [3D-PSP-Tutorials](https://github.com/PSP-Archive/3D-PSP-Tutorials) — учебник по 3D от Ghoti.
- [pspdecompiler](https://github.com/PSP-Archive/pspdecompiler) — декомпилятор PRX.
- [PatchSFO](https://github.com/PSP-Archive/PatchSFO) — правка SFO в EBOOT под текущую прошивку.
- [PSvid](https://github.com/PSP-Archive/PSvid) — конвертер видео для PSP, PS3 и Vita.
- [PSX2PSP-Reborn](https://github.com/hkmodd/PSX2PSP-Reborn) — сборщик POPS `EBOOT.PBP` на Rust: мультидиск, ICON1/SND0, предпросмотр XMB.
- [PSDevWiki](https://www.psdevwiki.com/psp/) — вики по железу, прошивкам и форматам.

## Серая зона

Инструменты, связанные с запуском образов и обходом защиты. Отдельный раздел, ссылки не привожу: используй на свой риск.

- **ISO/CSO-лоадеры** — запуск образов дисков с карты памяти.
- **CSO-компрессоры** — сжатие образов под медленную карту памяти.
- **npdrm_free** и подобное — снятие DRM с PSN-контента.
- **PKG-шопы и установщики PSN-контента** — загрузка игр из неофициальных источников.

## Legacy

- **PRO CFW / 6.61 LME** — старые кастомные прошивки, вытеснены ARK-4 и ARK-5.
- [Infinity](https://github.com/DaveeFTW/Infinity) — перманентный патч загрузки для 6.31 и 6.61 под PRO/LME, с ARK не нужен.
- **eLoader** — загрузчик homebrew для прошивки 1.50.
- **Dark_AleX Open Edition** — ранние OE-прошивки, история сцены.
- [Pandora Battery Tool](https://github.com/PSP-Archive/Open-Source-Pandora-Battery-Tool) — восстановление «кирпичей» через сервисную батарею.
- [Psx-P](https://github.com/PSP-Archive/Psx-P) — ранний эмулятор PlayStation 1, заменён встроенным POPS.
- **UMDGen** — сборка и правка образов UMD.

## Правила подборки

- Один проект — одна строка: ссылка + короткое описание.
- Помечай `со своими копиями игры`, если нужны файлы игры.
- Заброшенные проекты уходят в `Legacy`.
- PR с новыми проектами приветствуются.

## Лицензия

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)
