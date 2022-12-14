# Инструкция по работе с git

## Инициализация репозитория

Для инициализации репозитория в текущей дирректории нужно ввести команду
```
git init
```
## Добавление файлов в коммит

Для добавления файллов в коммит используется команда

```
git add <имя файла>
```
## Проверка репозитория

Для отображения состояния файлов в рабочем каталоге и индексе (какие файлы изменены, но не добавлены в индекс; какие ожидают коммита в индексе) используется команда

```
git status
```
## Сравнение изменений в Git

Для вычисления разницы между любыми двумя Git деревьями используется команда

```
git diff
```
## Просмотр истории коммитов

Для просмотра истории коммитов используется команда

```
git log
```
## Переключение между коммитами

Для переключения между коммитами используется команда

```
git checkout <название коммита>
```
## Переключение на актуальную версию коммита

Для переключения на актуальную версию коммита используется команда

```
git checkout master
```

## Откат к нужной версии коммита

Для отката к нужной версии коммита (все, что было после данной версии коммита - удаляется) используется команда

```
git reset <название коммита>
```
## Откат (жесткий или hard) к нужной версии коммита 

Для отката к нужной версии коммита (все, что было после данной версии коммита - удаляется, А ТАК ЖЕ ДОПОЛНИТЕЛЬНО К ЭТОМУ ПРОИСХОДИТ ИЗМЕНЕНИЕ ФАЙЛОВ В ВАШЕЙ РАБОЧЕЙ ДИРЕКТОРИИ) используется команда

```
git reset --hard <название коммита>
```
## Как «представиться» системе контроля версий Git

Первое, что вам следует сделать после установки Git — указать ваше имя и адрес электронной почты. Для этого используются следующие 2 команды

```
git config --global user.name "Ваше имя английскими буквами"

git config --global user.email "Ваша электронная почта"
```

## Создание коммита (сохранения)

Для создания коммита (сохранения) с комментариями к данному коммиту используется команда
```
git commit -m «Ваши комментарии к коммиту»
```
## Просмотр лога комитов

Для просмотра лога комитов введите команду

```
git log --graph --all
```
## Создание ветки

Для создания новой ветки, введите команду

```
git branch <имя ветки>
```
## Удаление ветки 

Для удаления ветки введите команду

```
git branch -d <имя ветки>
```

## Слияние ветки с текущей

Для слияния ветки с текущей введите команду

```
git merge <имя ветки>
```

## Клонирование репозитория

Для клонирования репозитория нужно ввести команду

```
git clone <repository_url>
```

## Обновление текущей ветки

Для обновления текущей ветки введите команду

```
git pull
```

## Отправка изменений в удаленный репозиторий

Для отправки текущей ветки в удаленный репозиторий введите команду

```
git push
```

## Просмотр лога репозитория

Введите команду 

```
git log --graph --all
```

## Загрузка изменений из всех веток

```
git fetch
```
