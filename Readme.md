# Инструкция по работе с Git

## Подготовка репозитория
Для создания репозитория используется команда *git init*. Чтобы созадать репозиторий напишите в терминале с открытой папкой для репозитория *git init*

## Добавление файлов в репозиторий

Для добавления файла к коммиту используется комманда *git add*. Для этого в терминале с папкой-репозиторием необходимо написать *git add <название файла>*

## Создание коммита
Для создания коммита используется команда *git commit*. Чтобы создать новый коммит в терминале с открытой папкой-репозиторием пишем команду *git commit -m "<сообщение к коммиту>"*. Сообщения к коммитам писать ***ОБЯЗАТЕЛЬНО***

## Копия репозитория
*git clone [url-адрес]*
Скачивает репозиторий вместе со всей его историей изменений

## Статус Git-a в папке
*git status*
Перечисляет все новые или изменённые файлы, которые нуждаются в фиксации. Проверяет создан ли репозиторий вообще

## Разница между изменённым и не добавленым файлом
*git diff*
Показывает различия по внесённым изменениям в ещё не проиндексированных файлах

## Список веток
*git branch*
Список именованных веток коммитов с указанием выбранной ветки. *git branch -a* подгружает список всех веток проекта из удалённого репозитория
