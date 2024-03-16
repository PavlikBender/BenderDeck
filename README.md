# ![](/Screenshots/Square44x44Logo.altform-lightunplated_targetsize-32.png) BenderDeck 3.0 Beta

### [:arrow_right: English version](https://github.com/PavlikBender/BenderDeck/blob/main/README_EN.md)
Бесплатное приложение для воспроизведения звука по нажатию клавиши для стримеров.
### [:arrow_right: Скачать последнюю версию](https://github.com/PavlikBender/BenderDeck/releases/download/v3.0/BenderDeckSetup.msi)
### [:arrow_right: Скачать portable версию](https://github.com/PavlikBender/BenderDeck/releases/download/v3.0/BenderDeck.3.0.Portable.zip)

*Portable версия запускается через файл BenderDeck.exe*

#### Не забудьте поддержать меня: [DonationAlerts](https://www.donationalerts.com/r/pavlikbender) 

### **Внимание!** Приложение находится в стадии Beta и могут наблюдаться некоторые баги и проблемы. 

Сообщить о них можно в моем [Discord-е](https://discord.com/invite/gaVrv6k).

## Известные баги
1. Windows Defender может ругаться при скачивании установочного файла, если вы не смогли разобраться как скачать и запустить файл [**СКАЧАЙТЕ PORTABLE ВЕРСИЮ**](https://github.com/PavlikBender/BenderDeck/releases/download/v3.0/BenderDeck.3.0.Portable.zip).

## Оглавление
- [Быстрый старт](#быстрый-старт)
- [Описание](#описание)
  - [Сетка кнопок](#сетка-кнопок)
  - [Меню настроек](#меню-настроек)
  - [Свойства кнопки](#свойства-кнопки)
- [Часто задаваемые вопросы](#часто-задаваемые-вопросы)
- [Связь со мной](#связь-со-мной)

## Быстрый старт
1. Настрой раскладку кнопок.

![](/Screenshots/QS1Ru.gif)

2. Настрой кнопку.

![](/Screenshots/QS2Ru.gif)

3. Кликни по настроенной кнопке или нажми на горячую клавишу.

![](/Screenshots/QS3.gif)

## Описание

Я написал это приложение, что бы помочь стримерам разнообразить их стримы.
Приложение позволяет мгновенно воспроизвести любой твой звуковой файл по нажатию клавиши клавиатуры или клику мышкой.

Перед тем как перейти к описанию интерфейса, нужно заметить, что размеры окна строго фиксированы и меняются автоматически от количества кнопок, настроенных колонок и т.д.

![](/Screenshots/Resizability.gif)

### Сетка кнопок
![](/Screenshots/D1.png)

1. Кнопка открывающая меню настроек.
2. Базовый элемент приложения - Кнопка. Кнопка кликабельна, а также её можно передвигать. Отображает своё наименование и настроенную горячую клавишу (оба свойства могут быть пустыми). 
3. Кнопка, которая в данный момент воспроизводит звуковой файл. Воспроизведение происходит при нажатии горячей клавиши или клику мышкой.
По умолчанию при повторном нажатии горячей клавиши произойдет воспроизведение звука сначала, но при повторном клике мышкой воспроизведение остановится.
5. Кнопка, которая в данный момент воспроизводит звуковой файл, одновременно с основной кнопкой т.е. с включенным свойством "Воспроизводить отдельно".

### Меню настроек
![](/Screenshots/D2.png)

1. Действие "Добавить кнопку", добавляет пустую кнопку в сетку с кнопками.
2. Регулировка количества колонок в сетке кнопок.
3. Свойство включающее возможность приложения быть поверх всех окон.
4. Настройка текущего языка приложения - поддерживаются Русский и Английский языки.
5. Ссылка на страницу приложения.
6. (X) Действие удаления кнопки.

![](/Screenshots/D4.png)

Все кнопки в сетке можно передвигать, а также при клике на кнопку в режиме редактирования, открывается окно свойства кнопки.

### Свойства кнопки
![](/Screenshots/D3.png)

1. Наименование кнопки, может быть пустым.
2. Поле настройки горячей клавиши. По действию "Назначить" открывается окно назначения горячей клавишы. По действию "Очистить" горячая клавиша очищается.
При этом если горячая клавиша не указана, но указан звуковой файл, кнопка воспроизведётся по клику мышкой.
4. Поле настройки звукового файла для воспроизведения, По действию "Выбрать" открывается окно выбора файла в формате mp3 и wav, если наименование кнопки пустое, автоматически заполняется именем файла. По действию "Очистить" свойство "Имя файла" очищается.
5. Громкость воспроизведения звукового файла, по умолчанию - 50 из 100.
6. Функция "Старт-Стоп", определяет поведение играющей кнопки при повторном нажатии горячей клавиши. По умолчанию воспроизведение начинается заново, при включенной функции "Старт-Стоп", повторное нажатие останавливает воспроизведение.
7. Функция "Воспроизводить отдельно", определяет как будет воспроизводится кнопка. По умолчанию когда воспроизводится первая кнопка, при нажатии второй кнопки, воспроизведение первой кнопки прекращается, начинается воспроизведение второй.
При включенной функции "Воспроизводить отдельно", воспроизведение первой кнопки не прекращается и при это начинается воспроизведение второй кнопки. При помощи этой функции можно реализовать воспроизведение нескольких кнопок одновременно.

## Часто задаваемые вопросы

**Q.** При нажатии горячей клавиши звук не воспроизводится.

**A.** Выбери заново звуковой файл. Проверь установленную громкость. В некоторых случаях приложение не может перехватить нажатую клавишу, поэтому попробуй запустить приложение от имени администратора.

**Q.** Есть ли в приложении Русский язык?

**A.** Да, его можно включить в левом нижнем углу меню настроек.

**Q.** Есть *ПриложениеНейм* оно легче, у него лучше функциональность, почему я должен использовать твоё приложение?

**A.** Плюсы моего приложения - это бесплатность, простота настройки и современный интерфейс(UI к сожалению тяжелый). Также я сам обкатывал концепцию этого приложения на стримах. Аналоги же обычно сложнее настраивать и нужно потратить тонну времени на это, несмотря на призрачно лучший итоговый результат. Я потратил эту тонну времени за тебя и хочу что бы тебе было проще. Но конечный выбор всегда стоит за тобой.

**Q.** Приложение не запускается.

**A.** Перейди по пути "C:\Users\{Имя пользователя}\AppData\Roaming\BenderDeck 3.0" и удали файл settings.json (ВНИМАНИЕ! это удалит все твои настройки). Запусти приложение.

**Q.** У меня Windows 10, 8, 7 запустится ли твоё приложение?

**A.** Приложение собрано для Windows 10, 11 x64. Windows 8 и 7 не поддерживается. Тестировалось только на Windows 11.

**Q.** Почему не сохранились настройки приложения?

**A.** Настройки сохраняются в момент закрытия меню настроек. Убедись, что перед закрытием приложения меню настроек было закрыто.


## Связь со мной
Если у вас появились вопросы по приложению, вы можете их задать в моем [Discord-е](https://discord.com/invite/gaVrv6k).

<sub>*Теги: Бесплатный StreamDeck, Stream Deck, Soundboard, Sound board, Free StreamDeck, Stream Deck аналоги, StreamDeck аналоги, OBS, для стримеров, горячая клавиша, hotkey, sound effects, Play SFX with hotkeys, Soundpad, Soundpad аналоги, AutoHotKey, AutoHotKey аналоги, HID Macros*</sub>
