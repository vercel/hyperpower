
# Hyperpower

Extension for hyperterm that turns on power mode, with bonus `wow` mode.

![hyperterm](https://cloud.githubusercontent.com/assets/13041/16820268/13c9bfe6-4905-11e6-8fe4-baf8fc8d9293.gif)

## How to use

Install [HyperTerm](https://hyperterm.org) and add `hyperpower-plus`
to `plugins` in `~/.hyperterm.js`.

## Shake config

```
$ vim ~/.hyperterm.js
module.exports = {
  config: {
    // default font size in pixels for all tabs
    fontSize: 12,

    .....

    plugins: {
      hyperpower-plus: {
        "shake.enabled": false
      }
    }
  }
}
```

## Credits

Based on [`power-mode`](https://atom.io/packages/power-mode) and
[`rage-power`](https://github.com/itszero/rage-power).

## License

MIT
