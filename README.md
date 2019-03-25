# Hyperpower

Extension for Hyper that turns on power mode.

- Simple configuration in `.hyper.js`
- Bonus `wow` mode

![hyper](https://cloud.githubusercontent.com/assets/13041/16820268/13c9bfe6-4905-11e6-8fe4-baf8fc8d9293.gif)

**Note:** shaking is only enabled in wow mode now! Which makes `hyperpower` an extension that you can use full time :P

## How to use

Install [Hyper](https://hyper.is) and add `hyperpower`
to `plugins` in `~/.hyper.js`.

## Configure

Add a `hyperPower` section to your hyper configuration (`~/.hyper.js`) with any of the following properties. Missing properties will use these default values:

```js
module.exports = {
  config: {
    // rest of the config
    hyperPower: {
      shake: false,
      colorMode: 'cursor', // 'cursor', 'custom', 'rainbow'
      colors: ['#eee'],
      particleSize: 3,
      minSpawnCount: 10,
      maxSpawnCount: 12,
      maximumParticles: 500
    }
  }
  // rest of the file
};
```

## Credits

Based on [`power-mode`](https://atom.io/packages/power-mode) and
[`rage-power`](https://github.com/itszero/rage-power).

## License

MIT
