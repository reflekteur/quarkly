## 📖 Detailed overview

Компонент представляет из себя счетчик, который увеличивается или уменьшается до определенного значения.

## 🎬 Live Demo

[Live demo link](https://quarkly-catalog.netlify.app/counter/)

## ⚙️ Usage

Добавьте компонент на страницу и посмотрите в режиме превью.

### Начальное и конечное значение

Значения в параметрах `Начальное число` и `Конечное число` можно задать как положительными, так и отрицательными. Важно, чтобы начальное значение было меньше конечного.
В случае, если нужен обратный отсчет, выберите значение `Убывание` в свойстве `Направление отсчёта`, тогда начальное значение станет конечным, а конечное начальным.

### Запуск счетчика

Счетчик запустится атоматически, когда попадёт в поле видимости окна.

## 🧩 Components and Props

| Названия свойств      |   Type   | Default  | Example |
| :-------------------- | :------: | :------: | :-----: |
| Начальное значение    | `number` |   `0`    |  `-43`  |
| Конечное значение     | `number` |  `100`   |  `300`  |
| Направление отсчёта   |  `enum`  | `normal` | `true`  |
| Длительность отсчёта  | `number` |  `2000`  | `3000`  |
| Текст после значения  | `string` |   `-`    |   `%`   |
| Текст перед значением | `string` |   `-`    |   `$`   |

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
