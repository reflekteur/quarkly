## 📖 Detailed overview

Зацикленная анимация смены текстовых слайдов для ваших заголовков.

## 🎬 Live Demo

[Live demo link](https://quarkly-catalog.netlify.app/looptext/)

## ⚙️ Usage

Добавьте компонент на страницу и посмотрите в режиме превью.

### Изменение слайдов

Чтобы изменить надписи на свои, выберете компонент и измените значения свойства `Список слайдеров`.
Для добавления или удаления слайдов, воспользуйтесь соответствующими кнопками "+" и "-".‎

Примечание: слайды по умолчанию нельзя удалить, просто замените стандартный текст своим.

## 🧩 Components and Props

| Названия свойств                |   Type   | Description                                                           | Default |      Example      |
| :------------------------------ | :------: | :-------------------------------------------------------------------- | :-----: | :---------------: |
| Список слайдеров                | `array`  | Используйте кнопки "+" и "-" для добавления и удаления слайдов        |  `[]`   | `[first, second]` |
| Интервал смены слайдов          | `number` | Интервал (в мс) с которым сменяются слайды                            | `3000`  |      `1500`       |
| Задержка перед началом анимации | `number` | Задержка (в мс) перед началом анимации                                |   `0`   |      `1000`       |
| Длительность изменения ширины   | `number` | Длительность (в мс) изменения ширины контейнера вокруг каждого слайда |  `150`  |       `50`        |
| Анимация появления и скрытия    |  `bool`  | Включить или выключить анимацию появления и скрытия слайдов           | `true`  |      `false`      |
| Скрытие анимации на границе     |  `bool`  | Скрытие анимации слайда, если он выходит за границы контейнера        | `true`  |      `false`      |
| Запретить перенос текста        |  `bool`  | Запретить перенос текста, используется для вычисления ширины          | `true`  |      `false`      |

## 🗓 Changelog

 - 21/04/2021 (v1.0)
 - Первая версия

## 📮 Feedback

If you encountered a bug, please contact us so we can fix it promptly. We’re rapidly developing, so don’t hesitate to send us your feedback and request new features you would like to see added. Feel free to share what you’re working on - we **love** to see what you’re building with Quarkly!

[Help with components](https://community.quarkly.io/c/requests/11)

[We're on Discord](https://discord.gg/f9KhSMGX)

[Our Twitter](https://twitter.com/quarklyapp)

[dev@quarkly.io](mailto:dev@quarkly.io)

## 📝 License

Licensed under the [MIT License](./LICENSE).
