# SnakeModsBookmarklet
Full credit goes to [DarkSnakeGang](https://github.com/DarkSnakeGang/GoogleSnakeModLoader).

## How to make it work...

1. Search up any type of snake game.
2. The second you press enter click on the bookmarklet and hope you have slow wifi.
3. If you pressed the bookmarklet before the page fully loads, the bookmarklet will load.

YOU HAVE TO CLICK THE BOOKMARKLET BEFORE THE PAGE LOADS!!!

Just bookmark this as the url:
```js
javascript:fetch(%60https://raw.githubusercontent.com/RatInChat/SnakeModsBookmarklet/main/bookmarklet.js%60).then(data%3D%3E%7Bdata.text().then(text%3D%3E%7Beval(text)%7D)%7D)%3B
```
