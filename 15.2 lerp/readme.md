# Please read!
I know this looks different from the video, but just read the install instruction down bellow, and it should be just as easy :) <br>
Should there be any problem, you can always ask for help over at my [Discord server](https://discord.com/invite/RfgA6wqzZP).
15.2 lerp script for [Team Fortress 2](https://www.teamfortress.com).
## Installation
If you have a autoexec from before, simply copy the context from [this](https://raw.githubusercontent.com/tf2iMicro/TF2-Mods/main/15.2%20lerp/autoexec.cfg) website and paste it into your autoexec. If not, just download [this](https://github.com/tf2iMicro/TF2-Mods/releases/download/v1.0/autoexec.cfg) and put it in `tf\cfg`.
## Installation (Mastercomfig)
**Note**: Mastercomfig has optimized net values for hitscan and projectile classes, but if you still want 15.2 lerp on every class, continue with the installation instructions bellow. <br> If you're using masterconfig, your class configs is located in `tf\cfg\overrides`. Mastercomfig also uses custom net settings which you need to override to get 15.2 lerp on all the classes. This is done with the class configs, they'll have the class name and a `.cfg` at the end of it (`[class].cfg` example: `spy.cfg`. Read more about class configs [here](https://docs.mastercomfig.com/latest/faq/?h=class+configs#why-does-mastercomfig-override-my-class-configs)) <br>
So if you want to change the lerp setting for some, or all classes you can do it by putting `net_projectiles` or `net_hitscan` in the file `tf/cfg/overrides/[classname].cfg` <br>
That's it. Enjoy!
