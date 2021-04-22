## 📖 Overview

Adds a VK.com community page widget.

## 🎬 Live demo

[Check out the live demo page 🗗](https://quarkly-catalog.netlify.app/vkpages/)

## ⚙️ Usage

 1. Add component to a page.
  2. Set your `VK container ID` and `VK page ID` in the Props panel.
  3. Click the Preview button to see how it's working!

### Display Modes

The `View` property changes the display mode of the widget's content. There are three options available:
  - Display community members;
  - Display community wall;
  - Display community name only.

### Advanced Mode

`Enable Advanced Mode`  adds a Like button and a community picture to the widget.

## 🧩 Props

| Props name                 |   Type    |   Default value  |   Example value  |
| :------------------------------- | :-------: | :---------: | :---------: |
| VK page ID        | `number`  |     `-`     | `123456789` |
| VK container ID | `string`  | `vk_groups` |  `some_id`  |
| Background color               | `string`  |   `#fff`    |   `blue`    |
| Text color              | `string`  |   `#000`    |   `#fff`    |
| Link color              | `string`  |  `#5181B8`  |  `#fdfdfd`  |
| Display mode         |  `enum`   |  `Members`  | `Only name` |
| Show community page cover? | `boolean` |   `false`   |   `true`    |
| Enable Advanced Mode       | `boolean` |   `false`   |   `true`    |

## 🗓 Changelog

* 21/04/2021 (v1.0)
  * First version

## 📮 Feedback

If you encountered a bug, please contact us so we can fix it promptly. We’re rapidly developing, so don’t hesitate to send us your feedback and [request new features](https://community.quarkly.io/c/requests/11) you would like to see added. Feel free to share what you’re working on - we **love** to see what you’re building with Quarkly!

[Join the official Quarkly community](https://community.quarkly.io/)

[Reach us on Discord](https://discord.gg/f9KhSMGX)

[Follow updates on Twitter](https://twitter.com/quarklyapp)

[dev@quarkly.io](mailto:dev@quarkly.io)

## 📝 License

Licensed under the [MIT License](./LICENSE).