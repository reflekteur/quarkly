## 📖 Overview

Adds a counter that increases or decreases to a certain value.

## 🎬 Live demo

[Check out the live demo page 🗗](https://quarkly-catalog.netlify.app/counter/)

## ⚙️ Usage

  1. Add component to a page.
  2. Click the Preview button to see how it's working!

### Initial and final values

The values for `Initial value` and `Final value` can be positive or negative. But it's important that the starting number is smaller than the ending number.

If you need to count _down_, select `Descending` in the `Direction` property. This way the initial value will become the final value and vice versa. 

### Trigger

The counter will start automatically as soon as it comes into view.

## 🧩 Props

| Props name      |   Type   | Default value | Example value |
| :-------------------- | :------: | :------: | :-----: |
| Initial value    | `number` |   `0`    |  `-43`  |
| Final value     | `number` |  `100`   |  `300`  |
| Direction   |  `enum`  | `normal` | `Descending`  |
| Duration (in ms)  | `number` |  `2000`  | `3000`  |
| Text after the value   | `string` |   `-`    |   `%`   |
| Text in front of the value | `string` |   `-`    |   `$`   |

## 🗓 Changelog

 - 21/04/2021 (v1.0)
   - First version

## 📮 Feedback

If you encountered a bug, please contact us so we can fix it promptly. We’re rapidly developing, so don’t hesitate to send us your feedback and [request new features](https://community.quarkly.io/c/requests/11) you would like to see added. Feel free to share what you’re working on - we **love** to see what you’re building with Quarkly!

[Join the official Quarkly community](https://community.quarkly.io/)

[Reach us on Discord](https://discord.gg/f9KhSMGX)

[Follow updates on Twitter](https://twitter.com/quarklyapp)

[dev@quarkly.io](mailto:dev@quarkly.io)

## 📝 License

Licensed under the [MIT License](./LICENSE).