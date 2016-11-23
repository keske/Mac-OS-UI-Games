# Mac OS UI Games

Two rather simple games, but based on the Mac OS X Interface. This approach shows how the things you are used to, obtain new meaning. My games is continuation of finding the way of interaction between the OS and the user on levels that are slightly noticeable at first sight.

## Slot Machines

3 slots, each has a set of pictures. The aim of the game is to get 3 the same pictures. In my game each slot is the simple folder in Cover Flow mode and in contrast WI the original game the movement of the slots is horizontal.

### How to play

Open Terminal
```$ cd path-to-game/```

Open 3 folders and place them on below the other.
```$ open first/```
```$ open second/```
```$ open third/```

Run game.php script. After that pictures from the source folder will be randomly copied 600 times to the folders first, second mad third;

```$php game.php```

Now you can play. Ideally with the trackpad.

[Download game (34Kb)](https://github.com/keske/Mac-OS-UI-Games/blob/master/slotmachine.zip?raw=true)

## Dice game

Very simple. Normal folder in Preview mode shows previews of the image files, two in our case. Script copes such two images randomly and gives a combination of two dices.

How to play

Open folder and set Preview mode;
Open Terminal
```$ cd path-to-game/```
Run the game (`$ php game.php`);
Each roll is a script run.

[Download game (34Kb)](https://github.com/keske/Mac-OS-UI-Games/blob/master/dicegame.zip?raw=true)