# Конспект по Git

# Семинар 1

## Описание команд

### Проверка работы Git
    git --version

### Представляемся Git
    git cofig --global user.name "Name"
    git config --global user.email "Email Address"

### Создаем репозиторий
    git init

### Добавляем файл/файлы для отслеживания
    git add - все
    git add "file_name"

### Сохраняем изменения
    git commit -m "text"

### Журнал изменений
    git log

### Переключение между версиями
    git checkout <название версии>

# Семинар 2

## Ветвление

1. git branch - список веток
2. git branch name - создание новой ветки
3. git checkout name - переключение на другую ветку