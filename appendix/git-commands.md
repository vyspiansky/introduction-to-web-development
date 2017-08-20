# Додаток 2. Деякі Git-команди

Задати e-mail та ім’я

```
git config --global user.email "you@example.com"
git config --global user.name "Your Name"
```

Ініціалізувати порожній локальний Git-репозиторій

```
git init
```

Клонувати репозиторій, що існує, по HTTP (на прикладі GitHub)

```
git clone https://github.com/{vendor_name}/{project_name}.git
```

Або клонувати репозиторій, що існує, за допомогою SSH

```
git clone git@github.com:{vendor_name}/{project_name}.git
```

Перевірити стан

```
git status
```

Перевірити, чи потрібен pull

```
git status -uno
```

Додати файл(и) в індекс

```
git add file_name
```

Покласти зміни в локальний репозиторій

```
git commit
```

Покласти зміни з локального у віддалений репозиторій

```
git push
```

Забрати зміни з віддаленого репозиторію

```
git pull
```


Показати локальні гілки

```
git branch
```

Показати всі локальні та віддалені (remote) гілки

```
git branch -a
```

Показати лише віддалені (remote) гілки

```
git branch -r
```

Змінити гілку на branch_name

```
git checkout branch_name
```

Оновити дані з віддаленого репозиторію по поточній гілці

```
git pull
```

Створити гілку на своєму локальному комп'ютері та перейти в цю гілку

```
git checkout -b branch_name
```
