# tretton37 ioquake3
## 1
1. Download tretton37 quake 3.zip from this link => [ioquake3](https://drive.google.com/open?id=1SRy_TndkLsdmUEibOPStCL-54rCKpDLc) and unzip it
2. Mount **ioquake3 1.36.dmg** and drag **ioquake3** folder to applications
3. Drag **pak0.pk3** into the **baseq3** folder of the ioquake3 folder you just added to applications. The other pak files are already there
4. Drag ioquake3.app into the root folder of **ioquake3**

Should look like this.
```
├── applications
│   ├── baseq3
│   │   ├── pak0.pk3
│   ├── missionpack
│   ├── ioquake3-1.36.app (don't run)
│   ├── ioquake3.app (this is the one! Yay!)
│   ├── ioquake3fe-1.36.app (don't run)
````

## 2
Now you should be able to run quake 3 on your mac, but it will look crap. First of, make sure you know what resolution your screens has got. To find out, open *displays*. This will open multiple screens if you have a laptop connected to a external screen. Choose the external screens and hold down **option** button and click **scaled**. This will reveal what screens size to use while playing.

Now when you know the screen resolution to use start quake (just click past key) and when it loads press **SHIFT** + **ESC** to open the console. I chose 1920 * 1080.

### To enable custom width/height for HD monitors
Write the following and press enter on each command, this is just my example resolution.
````
/r_mode -1
/r_customheight 1080
/r_customwidth 1920
/vid_restart
````

You can also use `/r_fullscreen 0` followed by `/vid_restart` to disable fullscreen (1 to enable).

Then you are good to go! :D

There are a bunch of more stuff here that can be interesting to read, [Wiki for ioquake3](http://web.archive.org/web/20180926205015/http://wiki.ioquake3.org/Players_guide#I_can.E2.80.99t_bring_down_the_console_with_the_.60_or_the_.7E.21).
