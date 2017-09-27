# Chocolatey

**Chocolatey** — це менеджер пакетів для Windows (як apt-get в Ubuntu). Він був розроблений таким чином, щоб бути децентралізованою системою для швидкого встановлення програм та інструментів, які вам потрібні.

Сайт: [https://chocolatey.org/](https://chocolatey.org/)

## Як використовувати?

Скажімо, вам потрібен Node.js, тоді відкрийте командний рядок як адміністратор, а потім запустіть:

```
choco install nodejs.install
```

Чи Python 2:

```
choco install python3
```

Назви програм можна знайти в списку пакетів на сторінці [https://chocolatey.org/packages](https://chocolatey.org/packages).

За допомогою Chocolatey ви також можете оновлювати потрібні вам програми. Наприклад,  щоб оновити Node.js, запустіть з командного рядка або з PowerShell:

```
choco upgrade nodejs.install
```