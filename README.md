# Лабораторная работа №6
## Цель лабораторной работы
Изучение базовых возможностей системы управления версиями, опыт работы с Git Api, опыт работы с локальным и удаленным репозиторием.

## Ход работы
Сначала необходимо было сделать форк репозитория на ноутбук:

![screen1](https://github.com/GoncharenkoAlla2437/LR6/blob/otchet/photos/Снимок%20экрана%202025-11-14%20182805.png?raw=true)

Была получена история операций для ветки master:

![screen2](https://github.com/GoncharenkoAlla2437/LR6/blob/otchet/photos/Снимок%20экрана%202025-11-14%20184722.png?raw=true)

Также были получены изменения этой ветки:

![screen3](https://github.com/GoncharenkoAlla2437/LR6/blob/otchet/photos/Снимок%20экрана%202025-11-14%20191650.png?raw=true)

Был совершен переход из ветки master в ветку branch1:

![screen4](https://github.com/GoncharenkoAlla2437/LR6/blob/otchet/photos/Снимок%20экрана%202025-11-14%20191757.png?raw=true)

Были получены история операций и изменения  для ветки branch1:

![screen5](https://github.com/GoncharenkoAlla2437/LR6/blob/otchet/photos/Снимок%20экрана%202025-11-14%20191710.png?raw=true)

Была совершена попытка объединить две ветки, но между ветками начал происходить конфликт из-за разной информации в файле merge.txt в разных ветках репозитория:

![screen6](https://github.com/GoncharenkoAlla2437/LR6/blob/otchet/photos/Снимок%20экрана%202025-11-14%20192013.png?raw=true)

Через блокнот был открыт этот файл:

![screen7](https://github.com/GoncharenkoAlla2437/LR6/blob/otchet/photos/Снимок%20экрана%202025-11-14%20192442.png?raw=true)

И он был изменен соответственно тексту из ветки master:

![screen8](https://github.com/GoncharenkoAlla2437/LR6/blob/otchet/photos/Снимок%20экрана%202025-11-14%20192500.png?raw=true)

Был создан файл commitfile.txt чтобы его закоммитить и тем самым сохранить объединение веток:

![screen9](https://github.com/GoncharenkoAlla2437/LR6/blob/otchet/photos/Снимок%20экрана%202025-11-14%20193143.png?raw=true)

Была удалена побочная ветка, оставшаяся после слияния:

![screen10](https://github.com/GoncharenkoAlla2437/LR6/blob/otchet/photos/Снимок%20экрана%202025-11-14%20235929.png?raw=true)

Были созданы несколько коммитов, один из которых был удален с помощью команды revert, хотя информация о нем и осталась в истории коммитов:

![screen11](https://github.com/GoncharenkoAlla2437/LR6/blob/otchet/photos/Снимок%20экрана%202025-11-15%20022842.png?raw=true)

Была создана ветка otchet для включения в нее отчета в файл readme.md, содержимок которого было написано в VS code с помощью разметки markdown:

![screen12](https://github.com/GoncharenkoAlla2437/LR6/blob/otchet/photos/Снимок%20экрана%202025-11-15%20011750.png?raw=true)

Был создан коммит папки со скриншотами для отчета:

![screen13](https://github.com/GoncharenkoAlla2437/LR6/blob/otchet/photos/Снимок%20экрана%202025-11-15%20011955.png?raw=true)

Также был создан коммит с обновленным (но не до конца) отчетом и новыми скриншотами самого отчета, чтобы их можно было добавить в следующий коммит ветки:

![screen15](https://github.com/GoncharenkoAlla2437/LR6/blob/otchet/photos/Снимок%20экрана%202025-11-15%20023641.png?raw=true)

![screen16](https://github.com/GoncharenkoAlla2437/LR6/blob/otchet/photos/Снимок%20экрана%202025-11-15%20031204.png?raw=true)

Затем я получила историю операций в форматированном виде и добавила два коммита в отчет: со скриншотами этого и с изменением отчета:

![screen17](https://github.com/GoncharenkoAlla2437/LR6/blob/otchet/photos/скринлог1.png?raw=true)

![screen18](https://github.com/GoncharenkoAlla2437/LR6/blob/otchet/photos/скринлог2.png?raw=true)

В итоге был создан еще один коммит с готовой версией отчета, а в репозитории осталось две ветки: master и otchet.

## Выводы
Были изучены базовые возможности системы управления версиями, опыт работы с Git Api, опыт работы с локальным и удаленным репозиторием. Был приобретен навык работы с ветками и коммитами.
