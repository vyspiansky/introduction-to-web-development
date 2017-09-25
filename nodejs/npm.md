# npm

**[npm](https://www.npmjs.com)** — менеджер пакетів для Node.js, який значно спрощує процес встановлення сторонніх пакетів у ваш проект.

> Якщо скористатися встановлювачами для Windows чи Macintosh з офіційного сайту [https://nodejs.org](https://nodejs.org), то скоріш за все також встановиться npm.

Щоб розпочати роботу з npm з чистого аркуша, в директорії з проектом виконайте команду:

```
$ npm init
```

![$ npm init](/nodejs/npm_init.png)

В результаті буде створено файл-опис для проекту `package.json`.

Щоб встановити пакет за допомогою npm, слід запустити

```
$ npm install НАЗВА_ПАКЕТУ --save
```

Після чого в папку `node_modules` проекту буде завантажена остання версія вказаного пакету.

Прапорець `--save` (або ж `--save-dev`) додає пакет, що встановлюється, у файл `package.json`. Таким чином, коли наступного разу хтось буде розгортати проект, досить буде написати `npm install`, щоб встановити всі залежності.

Для прикладу встановимо пакет Express \(фреймворк для Node.js\):

```
$ npm install express --save
```

Якщо ви хочете встановити пакет глобально \(щоб він був доступний для інших проектів\), слід використати прапорець `-g`:

```
$ npm install -g express
```
