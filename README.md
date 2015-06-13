[![](https://img.shields.io/badge/Wahoo-Package-00b0ff.svg?style=flat-square)][Wahoo]
![](https://img.shields.io/badge/License-MIT-707070.svg?style=flat-square)

# :battery: _battery_ ▮▮▮▮▮▮▯▯▯▯

OS X and Linux compatible battery utility.

## Install

```fish
wa g battery
```

## Usage

Display `battery` slots.

```fish
if available battery
  battery
end
```


Customize `battery` options.

```fish
if available battery
  battery ▶ ▷
end
```

Check if the battery is currently charging.

```fish
if set -q BATTERY_IS_CHARGING
  echo Charging ⌁
end
```

### Environment Variables

+ #### `BATTERY_IS_PLUGGED`
Unset if `false`.

+ #### `BATTERY_IS_CHARGING`
Unset if `false`.

+ #### `BATTERY_TIME_LEFT`
Time left in `HH:MM` format.

+ #### `BATTERY_SLOTS`
Number of slots/gauges from 10 available.

+ #### `BATTERY_MAX_CAP`
Battery maximum capacity.

+ #### `BATTERY_CUR_CAP`
Battery current capacity.

+ #### `BATTERY_PCT`
Current battery life in `%`.

### Screenshot

![](https://cloud.githubusercontent.com/assets/8317250/8145972/4e867a12-125a-11e5-8b88-3470d1b39a84.png)

# License

[MIT](http://opensource.org/licenses/MIT) © [Jorge Bucaran][Author]

[Author]: https://github.com/bucaran
[Wahoo]: https://github.com/bucaran/wahoo
