# Shadow Fist 影拳

Файтинг в стиле кунг-фу и аниме от третьего лица. Выбери героя и выходи против ронинов: они идут один за другим, пока ты
не упадёшь. Рекорд — сколько противников ты победил за один забег.

**Четыре героя:** странствующий ронин Wanderer 旅人, молодой монах с повязкой на глазах Young Monk 若僧, старый мастер с белым огнём в глазах Old Master 老師 и куноити в стальной маске Kunoichi くノ一.

**Три карты, и на всех всё рушится:** круглая арена под открытым небом, буддийский храм с проламываемыми стенами и водопад: бой на мокрой плите и по мелководью, тории, мельница, бамбук, а за завесой воды — пещера с алтарём.

![Выбор героя](screenshots/select.png)

![Водопад](screenshots/waterfall.png)

![Пещера за водопадом](screenshots/cave.png)

![Храм](screenshots/temple.png)

## Как запустить

1. Открой страницу **[Releases](../../releases/latest)** и скачай **`ShadowFist.exe`**.
2. Запусти его. Устанавливать ничего не нужно.
3. Windows может показать «Система Windows защитила ваш компьютер», потому что exe не подписан. Нажми **«Подробнее» →
   «Выполнить в любом случае»**.

Нужно: Windows 10 или 11 (64 бит) и видеокарта с поддержкой Vulkan (любая GeForce или Radeon последних лет).
Рекорды сохраняются в `%APPDATA%\Godot\app_userdata\Shadow Fist\`.

## Управление

| Клавиша | Что делает |
|---|---|
| WASD, мышь | ходьба и взгляд, Shift — бег |
| ЛКМ | удары руками, до 5 подряд |
| ПКМ | удары ногами: правой → левой → вертушка. После 2+ ударов рукой — Crane flight. По летящему противнику ПКМ ×3 — Sky kick → Hammer fall → Tornado, один раз за полёт |
| Пробел | прыжок; ещё раз в воздухе — двойной: кувырок вперёд, вбок — боковое сальто, назад — сальто назад. Лёжа — подъём разгибом. В прыжке ЛКМ — шпагат и два кулака вниз (1 деление ци), ПКМ — удар ногой с налётом |
| Двойной пробел | рывок-уклон |
| E | Wind step — рывок к противнику с ударом (тратит ци) |
| Q | блок; если поставить вовремя — парирование и ответный One Inch Punch |
| F | Thousand hands — супер-удар (нужно 2 деления ци, тратит всю шкалу, немного лечит) |
| Tab / C | выбрать / применить способность: заморозка Frost seal или «каменная обезьяна» Rock solid — отбив и удар, который впечатывает в стену (тратит ци) |
| T | вызов |
| Колёсико | приблизить / отдалить камеру |
| Esc | пауза и выход в меню; F1 — подсказка |

Ци копится от попаданий, блоков, парирований и идеальных уклонов. Все кнопки можно переназначить в меню, пункт CONTROLS.

## Авторы

Игра — tensei888 (с помощью Claude). Модели героев — свои, сделаны в Tripo. Движок — [Godot](https://godotengine.org) 4.7.

- **Статуя Будды:** Yahoo! JAPAN, [«大仏（Buddha）3Dデータ»](https://www.thingiverse.com/thing:182082), лицензия
  [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). В игре изменены масштаб и сглаживание.
- **Кисть для длани Будды:** Blender Studio, Dan Ulrich и др., Human Base Meshes (CC0). В игре переделана: срезана, упрощена,
  добавлены колесо дхармы и браслеты.
- **Текстура камня на водопаде:** [Poly Haven](https://polyhaven.com/a/cliff_side), cliff_side (CC0).
- **Ледяные кристаллы:** ipoly3d, [LowPoly Crystals Pack](https://opengameart.org/content/lowpoly-crystals-pack) (CC0).
- **Анимации:**
  - mocapdata.com, Eyes, JAPAN Co. Ltd. — *This motion capture data is licensed by mocapdata.com, Eyes, JAPAN Co. Ltd.
    under the Creative Commons Attribution 2.1 Japan License. http://mocapdata.com/ (C) Copyright Eyes, JAPAN Co. Ltd.
    2008-2009.* Переделанные из этих записей клипы распространяются по той же лицензии
    ([CC BY-SA 2.1 JP](https://creativecommons.org/licenses/by-sa/2.1/jp/)).
  - [CMU Graphics Lab Motion Capture Database](http://mocap.cs.cmu.edu).
  - [Quaternius](https://quaternius.com), Universal Animation Library (CC0).
  - [Motifect](https://motifect.itch.io), Martial Arts, Combat, Fantasy & Magic Motion Packs.
- **Звуки, CC BY 3.0:**
  - CGEffex, «Punch, slap, n' kick»;
  - Michel Baradari, «2 High Quality Explosions»;
  - Blender Foundation, «rock_breaking» (Yo Frankie!).
- **Звуки, CC0:** Kenney (Impact Sounds, RPG Audio, Voiceover Pack: Fighter), artisticdude, Independent.nu, rubberduck,
  StarNinjas, pyranostudios.
- **Музыка** (все треки с [OpenGameArt](https://opengameart.org)):
  - neocrey, «Last Cyber Dance» (CC BY 3.0);
  - Matthew Pablo, «Wasteland Overdrive» (CC BY 3.0);
  - nene, «Boss Battle #6 Metal» (CC0);
  - Emma_MA, «Determined Pursuit» (CC0).
- **Шрифты:** Teko (Indian Type Foundry) и Yuji Syuku (Kinuta Font Factory), SIL Open Font License.
