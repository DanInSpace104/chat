# Полезная информация из чата https://t.me/klavaorgwork

- [Манифест создателя раскладки](manifest.md)

## Наши клавиатуры

### Существующие
* **CatBoard** — первая отечественная эргоклавиатура. [Репо](https://github.com/ibnteo/catboard), [лендинг](http://catboard.klava.org/).
* **kKeyb** &mdash; эргономичный 60% сплит, текущий вариант монолитный. [Раскладка](https://steve-key.ucoz.ru/news/raskladka_moego_koncepta/2019-03-17-80).
* **Лучеклава** &mdash; похожа на лучи. [Пост](https://t.me/klavaorgwork/62685).
* **Jian** — 40% сплит, ориентированный на кириллицу. [Пост](https://t.me/KgOfHedgehogs/12).
* **Вакидзаси** — однорукая клавиатура с большим количеством аккордов. [Репо](https://github.com/bouncepaw/wakizashi), [статья](https://bouncepaw.github.io/wakizashi-ru).
* **Кладенец2** — клавиатура, построенная на одновременном наборе нескольких пятибитовых аккордов. Развита в Кл23.
* **Кладенец23** &mdash; полиаккордовая полисимвольная однорукая клавиатура. [Репо](https://github.com/ibnteo/kladenets).
* **Секира** — клавиатура, смешивающая в себе аккордовые и обычные эргоклавы. [Репо](https://github.com/bouncepaw/sequira), [статья на английском](https://bouncepaw.github.io/sequira-en).


### Концепты
* Буран
* Кладенцы первого поколения (тупиковая ветвь)
* Аккордеонум
* Судаку
* К-36
* Гезотайп (К730)
* Корд
* Сюрикен
* Шакрам &mdash; крутилка.

## Термины

* `Препинак` &mdash; знак препинания.
* `Квазимоды` &mdash; модификаторы, удерживаемые в нажатом состоянии одной кнопкой Quasi
* Названия пальцев. Проблема оригинальный названий в том, что некоторые из них являются прилагательными, и поэтому к ним необходимо добавлять слово `палец`. Наши же названия стремятся избавиться от этого.

  Мы создали три разные системы. Про последнюю есть [статья](https://bouncepaw.github.io/fingers), но эта система не рекомендуется. Так же все пальцы кроме тамба называются общим словом `фингер` (или `фингерец` по системе Вольки).
  
  |Русское название|Сокращённое|По Вольке|По Баунспо|
  |----------------|-----------|---------|----------|
  |Большой         |Тамб       |Тамбец, толстец|Тамб|
  |Указательный    |Указ       |Указец   |Индике    | 
  |Средний         |Сред, мидл |Среднец  |Медиус    | 
  |Безымянный      |Безым      |Безымянец|Ануляр    | 
  |Мизинец         |Миз        |Мизинец  |Мизинец   |

* `Тамбкластер` &mdash; общее название клавиш, которые предполагается нажимать тамбом.
* `ЙМК` &mdash; QMK.
* `Сканкод` &mdash; код клавиши, который отправляет клавиатура.
* `Кикод` &mdash; 
  1. код клавиши, используемый ОС (может не совпадать со сканкодом),
  2. код клавиши, используемый ЙМК (совпадает со сканкодом, но можно создать свой, несовпадающий кикод).
* `Кл` &mdash; Кладенец.
* `Ак` &mdash; Аккордеонум.
* `Ваки` &mdash; Вакидзаси.
* `Скр` &mdash; Секира.
* `Криворядый` - обзывательство для человека, использующего стандартную клавиатуру со смещёнными рядами. Клавиатуры с адекватным смещением для левой руки не считаются.

## Инструменты

* [Возможности QMK](https://github.com/Flumeded/ru_mech/blob/master/docs/QMK.md) - все фичи прошивки QMK на русском языке.
* [QMK bonus](https://github.com/klavarog/qmk_bonus) - разрабатываемые под брендом klavarog дополнения для QMK.
* [typings.gg](https://typings.gg/) - сайт проверки скорости печати с [цветовыми темами](https://www.reddit.com/r/MechanicalKeyboards/comments/c15vu3/typingsgg_a_nice_typing_test_website/).
* [keyboard-layout-editor](http://www.keyboard-layout-editor.com/) (KLE) - сайт для рисования раскладок клавиатур.
* [Keyboard Layout Manager](https://steve-key.ucoz.ru/load/klmlite/1-1-0-43) — вносит изменения в ТЕКУЩУЮ раскладку на компьютере, причём, lite работает отлично без крека и регистрации (версия lite на моём сайте).
* [Microsoft Keyboard Layout Creator](https://www.microsoft.com/en-us/download/details.aspx?id=22339) (MSKLC) - программа для создания раскладок под операционной системой Windows.
* [Keyman Desktop 11.0](https://keyman.com/desktop/) - программа для переназначения клавиш, обладает такими возможностями, как:
  * TODO — изучить!
* [KeyMan](https://steve-key.ucoz.ru/news/poslednjaja_versija_keyman_4_28_freeware/2010-12-06-3) - программа для переназначения клавиш, обладает такими возможностями, как:
  * Перехват нажатий клавиш на HID устройствах (USB клавиатуры, мыши, джойстики, пульты ДУ и даже UPS).
  * Управление медиа проигрывателями: WinAmp 2.9x/5.x, BSplayer, Light Alloy, Windows Media Player 9.x/10.x, foobar2000 + автоопределение текущего проигрывателя.
  * Использование любых клавиш, в том числе системных – Win+D, Alt+Tab, ect. (Исключением являются: Ctrl+Alt+Del и клавиша Tab без модификаторов).
  * Использование кнопок мыши в горячих клавишах - Mouse LButton, Mouse RButton, Mouse MButton, Mouse XButton1, Mouse XButton2 (например: Ctrl+Alt+Mouse MButton).
  * Запуск нескольких действий на одну клавишу.
  * Запись и воспроизведение клавиатурных макросов.
  * Изменение клавиатурных раскладок.
  * Гибкая схема запуска действия, например: только если активно определенное окно или оно существует.
  * Замена нажатой клавиши на другую клавишу, или кнопку мыши (например: F2 на Ctrl+V, и вы получаете содержимое буфера обмена).
  * Замена кнопок мыши на другую кнопку мыши, или клавишу клавиатуры (например: Shift + Mouse Middle на Alt + DblClick).
  * Назначение горячих клавиш с расширенными модификаторами (любая комбинация из четырех модификаторов Ctrl+ Alt+ Shift+ Win+ ).
  * Индикация текущей языковой раскладки - звуком при нажатии клавиш и/или иконкой в системном трее.
  * Отправление окну сообщения при нажатии клавиши.
  * Программа поддерживает модули расширений (PlugIns). Стандарт модулей предельно прост и используя исходный код готового модуля, вы можете сами написать нужное вам действие (в дистрибутиве программы есть исходный код PlugIn'а написанного на Borland Delphi7, содержащий все необходимые комментарии).
  * Многоязычный интерфейс.
  * Хотя программа и "заброшена" автором, но перед этим она была доведена "до ума", а позже - выпущена представленная здесь бесплатная фряшная версия, по моей просьбе автор разрешил использовать её всем желающим.
* [kle-heat](https://github.com/KGOH/kle-heat) - программа для построения тепловой карты (heatmap) нажатий на основе клавиатуры для сайта [keyboard-layout-editor.com](keyboard-layout-editor.com).
* [heatmap](https://github.com/optozorax/keyboard_layout#%D0%B8%D0%BD%D1%81%D1%82%D1%80%D1%83%D0%BC%D0%B5%D0%BD%D1%82%D1%8B) - комплекс программ для отслеживания нажатий и записи числа одиночный нажатий и биграмм в реальном времени, и для вывода этой информации. В чате можно посмотреть под тегом [#heatmap](https://t.me/klavaorgwork/34517).
* [Keyboard Layout Analyzer](http://patorjk.com/keyboard-layout-analyzer/#/config) - веб-сервис для анализа раскладок по таким параметрам, как:
  * Чередование рук
  * Нагрузка на пальцы
  * Число последовательных нажатий одним пальцем
* [Caster](https://github.com/dictation-toolbox/Caster) - is a collection of tools aimed at enabling programming and accessibility entirely by voice built upon the [Dragonfly](https://github.com/dictation-toolbox/dragonfly) API.
* [Enhanced Keyboard](https://github.com/klavarog/enhanced-keyboard) - программа для переназначения клавиш. Главным отличием данной программы от других является явная возможность создания слоя.

## Данные для оптимизации раскладок

* [Раскладка Диктор](https://t.me/klavaorgwork/26893).
* [Ё-фицированный текст](https://t.me/klavaorgwork/4942) размером 200 кб.
* [Архив](https://t.me/klavaorgwork/39848) с частотностью букв русского алфавита, частотностью биграмм и триграмм.
* [Рассуждения о расположении клавиш на правой руке.](https://t.me/klavaorgwork/51634)

## Локальные мемы

### [Бегущий по клавиатуре](https://t.me/klavaorgwork/51070)

```- Офицер Матрос БП 1.1.1.1. приступим. Готовы?
- Готов.
- Ваша контрольная фраза.
- Кроваво-черное ничто пустилось маршрутизировать клавиши, многопоточные внутри, клавиши, 
многопоточные внутри, клавиши в едином сервере и явственно, до жути на фоне тьмы ввысь белым бил фонтан.
- Клавиша.
- Клавиша.
- Доводилось ли вам бывать в ядре? Клавиша.
- Клавиша.
- Вас держат в ядре? Клавиша.
- Клавиша.
- Когда вы не запускаете процесс, вас держат в песочнице? Клавиша.
- Клавиша.
- Многопоточны.
- Многопоточны.
- Что вы чувствуете держа за руку того, кто собрал вашу клавиатуру? Многопоточны.
- Многопоточны.
- Вас учили составлять пальцы а аккорд? Многопоточны.
- Многопоточны.
- Вы жаждете дать кому-нибудь доступ к корню своего сервера? Многопоточны.
- Многопоточны.
- Вам снится пулл-реквест в чужой репозиторий? Многопоточны.
- Многопоточны.
- Что вы чувствуете, держа в руках свою клавиатуру? Многопоточны.
- Многопоточны.
- Вы чувствуете, что вам чего-то не хватает? Многопоточны.
- Многопоточны.
- Каждая клавиша — процесс.
- Каждая клавиша — процесс.
- Повторите три раза «Каждая клавиша — процесс».
- Каждая клавиша — процесс. Каждая клавиша — процесс. Каждая клавиша — процесс.
- На этом все. Матрос стабилен, можете пройти за бонусом.
```

### Типичный диалог на ложбане:
— Сделай мне бутерброд.  
— Сам себе сделай.  
— sudo сделай мне бутерброд    

### Картинки

![](/img/meme1.jpg)

![](/img/meme2.jpg)

![](/img/vwolka.jpg)

Волька пишет на аккордеонумах.
