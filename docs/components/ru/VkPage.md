## 📖 Detailed overview

Компонент для добавления виджета сообщества VK.

## 🎬 Live Demo

[Live demo link](https://quarkly-catalog.netlify.app/vkpages/)

## ⚙️ Usage

 1. Добавьте компонент на страницу
 2. Укажите ваш `Идентификатор сообщества` и `Идентификатор контейнера`
 3. Посмотрите как он работает в режиме превью

### Режимы отображения

Свойство `View` отвечает за режим отображения содержимого виджета. Доступно три варианта:
 - Отображать участников сообщества
 - Отображать стену сообщества
 - Отображать только название сообщества

### Расширенный режим

Если выделить свойство `Включить расширенный режим`, в виджете добавится кнопка 'Мне нравится' и изображение сообщества.

## 🧩 Components and Props

| Названия свойств                 |   Type    |   Default   |   Example   |
| :------------------------------- | :-------: | :---------: | :---------: |
| ID сообщества VK                 | `number`  |     `-`     | `123456789` |
| ID контейнера виджета            | `string`  | `vk_groups` |  `some_id`  |
| Цвет фона виджета                | `string`  |   `#fff`    |   `blue`    |
| Цвет текста виджета              | `string`  |   `#000`    |   `#fff`    |
| Цвет ссылок виджета              | `string`  |  `#5181B8`  |  `#fdfdfd`  |
| Что отображать в виджете         |  `enum`   |  `Members`  | `Only name` |
| Не отображать обложки сообщества | `boolean` |   `false`   |   `true`    |
| Включить расширенный режим       | `boolean` |   `false`   |   `true`    |

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
