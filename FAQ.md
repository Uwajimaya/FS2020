
**FAQ**

**Q**: I like the lights but prefer not to use the lens flare effects. What do I do?<br>
**A**: Go to ...\Packages\Community\Uwa light mod pack (v.X)\Effects\ and delete the TEXTURE folder - that's it. Unfortunately you'll have to do this again every time you install a new version of my mod.

**Q**: How do I use your mod for some aircraft but not all of them? How do I avoid the light mod conflicting with another mod?<br>
**A**: Go to ...\Packages\Community\Uwa light mod pack (v.X)\SimObjects\Airplanes. You can either delete the folder for the aircraft that you don't want my mod for OR, you can go into the desired aircraft folder and rename the systems.cfg file to something else. That way, you can easily get the mod back by renaming it back to systems.cfg. Just remember to do this again if/when you install a new version of my mod.

**Q**: When using the default planes, I can see the landing light reflecting inside clouds. Why I don't see that anymore after installing your mod?<br>
**A**: A light setting called "volumetric" enables those reflections - which I purposefully disabled for landing and taxi lights (but enabled for strobes). With the dim default lights, it's not too much of a problem, but the brighter lights also make the lighting "cone" a lot more visible when outside of clouds - and it looks like fog (see images below). If you want you can enable it for any light - go into the .fx file, look for "volumetric=0" and change it to "volumetric=1".

Volumetric landing lights enabled, external and internal view
<br>
![Volumetric1](https://github.com/Uwajimaya/FS2020/raw/gh-pages/images/Volumetric1.jpg)
![Volumetric2](https://github.com/Uwajimaya/FS2020/raw/gh-pages/images/Volumetric2.jpg)
