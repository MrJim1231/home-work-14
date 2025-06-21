npm install
npm install bootstrap

// Подключаем Bootstrap
@import '../../node_modules/bootstrap/scss/bootstrap';

// Ваши собственные стили (по желанию)
body {
background-color: #f8f9fa;
}

Откатить SASS чтобы не было ошибки при сборке Deprecation Warning: red() is deprecated. Suggestion:
color.channel($color, "red", $space: rgb)

npm install sass@1.62.1

Установить плагин IntelliSense for CSS class names in HTML для подсказаок написания классов

ctrl+alt+i - открыть чат Copilot

Если добавить импорт в scss то по 5 секунд собирает проект ,лучше добавить

  <link rel="stylesheet" href="node_modules/bootstrap/dist/css/bootstrap.css">
