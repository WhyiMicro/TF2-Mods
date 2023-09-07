# Please read!
I know this looks different from the video, but just read the install instruction down bellow, and it should be just as easy :) <br>
Should there be any problem, you can always ask for help over at my [Discord server](https://discord.com/invite/RfgA6wqzZP).
15.2 lerp script for [Team Fortress 2](https://www.teamfortress.com).
## Installation
If you have a autoexec from before, simply copy the context from [this](https://raw.githubusercontent.com/tf2iMicro/TF2-Mods/main/15.2%20lerp/autoexec.cfg) website and paste it into your autoexec. If not, just download [this](https://github.com/tf2iMicro/TF2-Mods/releases/download/v1.0/autoexec.cfg) and put it in `Team Fortress 2\tf\cfg`.
## Installation (Mastercomfig)
**Note**: Mastercomfig has optimized net values for hitscan (30.3 lerp) and projectile classes (15.2 lerp), but if you would like to override them, you can still do so! A good example is if you'd like to play demonight. Demonight is a melee based subclass and thus hitscan would be better to use, even though mastercomfig defaults to 15.2 cause it's a projectile based class. <br>
So, how do we fix this issue? Well, by the use of mastercomfig's override system. <br>
<br>
Mastercomfig - when downloaded with customizations - comes with a override's folder which will be placed in `Team Fortress 2\tf\cfg`. If you don't have one, you can download the [template](https://github.com/mastercomfig/mastercomfig/releases/latest/download/template.zip) and place it there manually. Once everything is in place, you'll have a bunch of [class configs](https://docs.mastercomfig.com/latest/faq/?h=class#why-does-mastercomfig-override-my-class-configs) in `Team Fortress 2\tf\cfg\overrides`. These class configs are used to customize each class. In our case, we wanna customize the lerp. So, since we wanna change demoman's lerp, we're gonna located and open `demoman.cfg`. In here, we're gonna put `net_hitscan` (30.3 lerp) on an empty line. Once you're done, make sure to save the file. <br>
<br>
That's pretty much it. So if you'd like 15.2 lerp on each class (not necessarily the best option) then you'd have to put `net_projectiles` on an empty line in each respective class config.
