# SCSS Keyframes mixin
###Properties
* keyframes
* animation-name
* animation-duration
* animation-timing-function
* animation-fill-mode
* animation-iteration-count

###Using
Connect to your project `sprite.scss`.

HTML:
```
<div class="animated-icon" data-name="icon_name" data-frames="50" data-time="1s" data-size="128"></div>
```
Second SCSS:
```
[data-name="icon_name.svg"] { background-image: url('/img/icon_name.svg'); }
```
Add a class `play` for `div.animated-icon` to play!
###Demo
[svgsprite.com](http://svgsprite.com/) –  Animated Vector Graphics for Web
