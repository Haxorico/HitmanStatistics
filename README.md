# Hitman Statistics
Hitman 2 and Hitman Contracts real-time statistics tracker.

## Features
- Silent Assassin rating
- Current mission name & number
- Timer with 3 decimals
- Shots fired
- Close encounters
- Headshots
- Alerts
- Enemies killed
- Enemies harmed
- Innocents killed
- Innocents harmed

## How to use
Run the program while playing the game, during a mission all values will be updated automatically.

## Screenshot
![Screenshot](http://i.imgur.com/jJh3kcj.png "Screenshot")

## Credits
Original Trainer class by Cless.

## Licence
[MIT License](https://github.com/nvillemin/HitmanStatistics/blob/master/LICENSE.txt)

## Note by Haxorico:
I updated the pointer to 'Number of shots fired' to one of 12 possibilities I found (using CE)
If in the future it seems I picked the wrong address+pointers here are the 12 possilbities and one of them might be the true one

baseAddress + 0x038974, {0xF8C, 0x11C7}
baseAddress + 0x03981C, {0x324, 0x11C7}
baseAddress + 0x03981C, {0x3C8, 0x11C7}
baseAddress + 0x03981C, {0x3CC, 0x11C7}
baseAddress + 0x03A398, {0x248, 0x11C7}
baseAddress + 0x03D7FC, {0x29C, 0x11C7}
baseAddress + 0x03E328, {0xC78, 0x11C7}
baseAddress + 0x03E5F8, {0xF48, 0x11C7}
baseAddress + 0x03E9C0, {0x9C0, 0x11C7}
baseAddress + 0x1163E4, {0xF44, 0x11C7}
baseAddress + 0x1163E4, {0xFE8, 0x11C7}
baseAddress + 0x1163E4, {0xFEC, 0x11C7}
