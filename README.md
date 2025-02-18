Інструкція з встановлення середовища для Angular

Перевірка Node.js:

Відкрий термінал і введи команду node --version.
Якщо показано версію, це означає, що Node.js вже встановлено. Перевір, чи ця версія підходить для Angular за ось цим посиланням https://angular.io/guide/versions.
Якщо Node.js не встановлено або версія застаріла, встанови оновлену версію з https://nodejs.org/en/download/.
Використання NVM (Node Version Manager) (Опціонально):

NVM дозволяє встановлювати, видаляти та перемикатися між різними версіями Node.js.
Для встановлення дивись https://github.com/nvm-sh/nvm.
Встановлення Angular CLI:

Після оновлення або встановлення Node.js введи команду npm install -g @angular/cli у терміналі.
Це встановить Angular CLI глобально на комп'ютері, дозволяючи використовувати його у будь-якому проєкті.
Створення нового Angular-проєкту:

В терміналі перейди до папки, де хочеш розмістити проєкт.
Введи команду ng new my-first-app для швидкого створення нового проєкту.
Вибери опцію Angular routing.
Після створення проєкту перейди в його папку командою cd my-first-app.
Запуск проєкту:

У терміналі введи ng serve --open, щоб запустити застосунок.
Твій перший Angular-застосунок буде відкрито в браузері за адресою http://localhost:4200/.

ng new my-project --directory . ---- створення проєкту якщо ти вже в папці з відкритим vsc то команда для створення

ng serve ----- після створення просто запускай

# MyProject

This project was generated using [Angular CLI](https://github.com/angular/angular-cli) version 19.1.7.

## Development server

To start a local development server, run:

```bash
ng serve
```

Once the server is running, open your browser and navigate to `http://localhost:4200/`. The application will automatically reload whenever you modify any of the source files.

## Code scaffolding

Angular CLI includes powerful code scaffolding tools. To generate a new component, run:

```bash
ng generate component component-name
```

For a complete list of available schematics (such as `components`, `directives`, or `pipes`), run:

```bash
ng generate --help
```

## Building

To build the project run:

```bash
ng build
```

This will compile your project and store the build artifacts in the `dist/` directory. By default, the production build optimizes your application for performance and speed.

## Running unit tests

To execute unit tests with the [Karma](https://karma-runner.github.io) test runner, use the following command:

```bash
ng test
```

## Running end-to-end tests

For end-to-end (e2e) testing, run:

```bash
ng e2e
```

Angular CLI does not come with an end-to-end testing framework by default. You can choose one that suits your needs.

## Additional Resources

For more information on using the Angular CLI, including detailed command references, visit the [Angular CLI Overview and Command Reference](https://angular.dev/tools/cli) page.
