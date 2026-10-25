# Awesome PlayStation Portable Homebrew

Подборка homebrew для PSP: прошивки, плагины, эмуляторы, нативные порты и утилиты.

> Нужна консоль с кастомной прошивкой (ARK-4 или ARK-5) и карта Memory Stick PRO Duo.
> Проекты помечены как `со своими копиями игры` там, где нужны собственные файлы игры.

Каталог homebrew и архив старых сборок: [PSP-Archive](https://github.com/PSP-Archive) (532 репозитория, включая исходники давно закрытых проектов) и [PSP-Archive.github.io](https://github.com/PSP-Archive/PSP-Archive.github.io).

## Содержание

- [Прошивка и загрузка](#прошивка-и-загрузка)
- [Меню, файлы, медиа](#меню-файлы-медиа)
- [Кастомизация и плагины](#кастомизация-и-плагины)
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
- [Chronoswitch](https://github.com/PSP-Archive/Chronoswitch) — даунгрейдер прошивки, откат на нужную версию.
- [LibPspExploit](https://github.com/PSP-Archive/LibPspExploit) — библиотека ядерных эксплойтов, база для собственных загрузчиков.
- [Universal Flash Dumper](https://github.com/PSP-Archive/Universal-Flash-Dumper) — дамп флеш-памяти консоли на большинстве прошивок.

## Меню, файлы, медиа

- [psp5](https://github.com/08Weber/psp5) — тёмный лаунчер игр под ARK-5, заменяет штатный список.
- [CMFileManager-PSP](https://github.com/joel16/CMFileManager-PSP) — файловый менеджер в духе CM: копирование, архивы, запуск.
- [PSP-FTPD](https://github.com/PSP-Archive/PSP-FTPD) — FTP-сервер прямо на консоли.
- [RemoteJoyLite](https://github.com/PSP-Archive/RemoteJoyLite) — плагин, выводит экран консоли на ПК по USB.
- [PSP-LCDC-Capture](https://github.com/mayuta212/PSP-LCDC-Capture) — захват видео и звука по USB одним кабелем, отдельный PRX под ARK-5.
- [PSPdisp](https://github.com/PSP-Archive/PSPdisp) — PSP как второй монитор Windows.
- [PSPWrite](https://github.com/PSP-Archive/PSPWrite) — текстовый редактор.
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

### J2ME и мобильные

- [Gravity Defied PSP](https://github.com/antim0118/gravity_defied_psp) — полный порт легендарного мотокросса на PSP: весь контент оригинала, gLib2D и intraFont, готовые сборки на [GameJolt](https://gamejolt.com/games/gravitydefiedpsp/1060552).
- [Gravity Defied SDL2](https://github.com/den4iklovelinux/gravity_defied_psp) — база порта на SDL2, промежуточный репозиторий для сборки под другие платформы.
- [gravity_defied_cpp](https://github.com/rgimad/gravity_defied_cpp) — исходный C++ порт с J2ME, от которого идут обе PSP-версии.
- [DoomRPG4PSP](https://github.com/dadcapgamer/DoomRPG4PSP) — Doom RPG (мобильная Java-игра) нативно на PSP.

### ПК

- **Need for Speed: Underground 2** — порт на PSP, публичного репозитория нет, только демонстрация: [видео](https://www.youtube.com/watch?v=K3V-dOojS2w). `со своими копиями игры`
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

### Открытые движки и игры

- [Kurok](https://github.com/TheMrIron2/kurok) — открытый шутер на движке Quake под PSP.
- [Abuse](https://github.com/PSP-Archive/Abuse) — Abuse-SDL, мрачный платформер-стрелялка.
- [C-Dogs SDL](https://github.com/PSP-Archive/CDogs) — C-Dogs, кооперативный top-down шутер.
- [OpenTyrian](https://github.com/PSP-Archive/Open-Tyrian-PSP) — OpenTyrian, вертикальный скролл-шутер.
- [OpenTTD PSP](https://github.com/PSP-Archive/OpenTTD-PSP) — OpenTTD, экономическая стратегия про транспорт.
- [MUGEN (infcat)](https://github.com/PSP-Archive/infcat) — движок MUGEN, нужны свои пакеты персонажей. `со своими копиями игры`
- [Frontier Elite II](https://github.com/PSP-Archive/Frontier-1337) — космический симулятор Frontier: Elite II.

## Игры PSP на других платформах

- [PPSSPP](https://github.com/hrydgard/ppsspp) — эмулятор PSP для ПК, Android, iOS и консолей.
- [PSPRecomp](https://github.com/jessicanataliagta/PSPRecomp) — фреймворк статической рекомпиляции PSP-игр: Allegrex MIPS в нативный код.
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
- [box3d-psp](https://github.com/Saymond/box3d-psp) — физика Box3D с ускорением через VFPU и рендером GU.
- [MicroAllegrex](https://github.com/Goatman13/MicroAllegrex) — плагин Allegrex для декомпилятора IDA Hex-Rays.
- [PSP-Homebrew-Dev-Notes](https://github.com/JustKidding23/PSP-Homebrew-Dev-Notes) — особенности железа PSP, IO карты памяти и отличия от PPSSPP.
- [3D-PSP-Tutorials](https://github.com/PSP-Archive/3D-PSP-Tutorials) — учебник по 3D от Ghoti.
- [pspdecompiler](https://github.com/PSP-Archive/pspdecompiler) — декомпилятор PRX.
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
