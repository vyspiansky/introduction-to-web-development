# Додаток 2. Часті Git-команди

Задати e-mail та ім’я

```
git config --global user.email "you@example.com"
git config --global user.name "Your Name"
```

Ініціалізувати порожній репозиторій

```
git init
```

Клонувати репозиторій, що існує, по HTTP (на прикладі GitHub)

```
git clone https://github.com/vyspiansky/english-verb-tenses-quiz.git
```

Або клонувати репозиторій, що існує, за допомогою SSH

```
git clone git@github.com:vyspiansky/english-verb-tenses-quiz.git
```

Перевірити стан

```
git status
```

Перевірити, чи потрібен pull

```
git status -uno
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
