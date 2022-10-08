# Конспект по Git

# Семинар 1

## Описание команд

### Проверка работы Git
    git --version

### Представляемся Git
    git config --global user.name "Name"
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

1. git branch - название веток
2. git branch name - создать новую ветку
3. git checkout name - переключиться на ветку
4. git merge name - добавить ветку в ветку мастер
5. git branch -d name - удалить ветку
6. git log --graph - список коммитов