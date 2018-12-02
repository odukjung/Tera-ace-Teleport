# cmd-slash
tera-proxy module compiled to use slash commands for common functions

## Auto-update guide
- Create a folder called `cmd-slash` in `tera-proxy/bin/node_modules` and download >> [`module.json`](https://raw.githubusercontent.com/seraphinush-gaming/cmd-slash/master/module.json) << (right-click save link as...) into the folder

## Dependency
- `command` module
- `tera-game-state` module

## Usage
- __`broker` · `거래`__
  - Call broker UI
- __`ch` · `초`__
  - Change channel
    - No argument : next channel
    - number as argument : change channel to number (eg. ch (num))
    - `b` : previous channel (!= one channel back)
- __`dr` · `ㅇㄱ` · `ㅌㅌ` · `xx`__
  - Drop party/raid
- __`exit`__
  - Quit TERA
- __`lobby` · `캐선`__
  - Return to lobby
- __`res` · `ㄱㄷㄴ` · `ㄹㄹ` · `ff`__
  - Reset dungeon
- __`talent` · `특성`__
  - Call talent UI

## Info
- **Support seraph via paypal donations, thanks in advance : [paypal](https://www.paypal.me/seraphinush)**
- Code schematic based on [`tera-game-state`](https://github.com/caali-hackerman/tera-game-state)
- Compiled modules :
  - `cmd-broker` (mod. by [wuaw](https://github.com/wuaw), branch [seraphinush-gaming](https://github.com/ylennia-archives/cmd-broker))
  - `cmd-channel` (mod. by [teralove](https://github.com/teralove), branch [seraphinush-gaming](https://github.com/ylennia-archives/cmd-channel))
  - `cmd-exit` (mod. by [teralove](https://github.com/teralove))
  - `exit-instantly (mod. by [teralove](https://github.com/teralove))
  - `cmd-slash-kr` (mod. by [seraphinush-gaming](https://github.com/ylennia-archives/cmd-slash-kr))
  - `cmd-lobby` (mod. by [teralove](https://github.com/teralove))
- cmd-slash-kr : Dungeon reset is `/던전리셋`, which is `/ejswjsfltpt` on Korean keyboard
  - `res` in proxy chat or `/ejswjsfltpt` :thinking:
- cmd-channel : "Changing channels while inside a dungeon will teleport you out"
- cmd-channel : "Changing to a channel number that doesn't exist will send you to channel 1"

## Changelog
<details>

    2.01
    - Added automatic submodule scan
    - Added `cmd-exit` and `exit-instantly`
    2.00
    - Refactored into submodules
    1.00
    - Initial commit
    - Added `talent` option

</details>