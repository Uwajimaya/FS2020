
**FAQ**

**Q**: Can you create mods for any of the Premium/Deluxe edition aircraft?<br>
**A**: Unfortunately not. The DA40-TDI, DV20, Baron G58, C152 Aerobat, C172 Classic, Boeing 787, Cirrus 22, Virus SW 121, Citation Longitude and Shock Ultra all have hidden & encrypted files. We have to wait and see if/when Asobo makes those files available.  

**Q**: I like the lights but prefer not to use the lens flare effects. What do I do?<br>
**A**: Go to ...\Packages\Community\Uwa light mod pack (v1.03 or later)\Effects\ and delete the TEXTURE folder - that's it. Unfortunately you'll have to do this again every time you install a new version of my mod.  

{% comment %}
**Q**: How do I use your mod for some aircraft but not all of them? How do I avoid the lighting mod conflicting with another mod?<br>
**A**: Go to ...\Packages\Community\Uwa light mod pack (v.X)\SimObjects\Airplanes. You can either delete the folder for the aircraft that you don't want my mod for OR, you can go into the desired aircraft folder and rename the systems.cfg file to something else. That way, you can easily get the mod back by renaming it back to systems.cfg. Just remember to do this again if/when you install a new version of my mod.
{% endcomment %}

**Q**: When using the default planes, I can see the landing lights reflecting inside clouds. Why don't I see that anymore after installing your mod?  
**A**: A light setting called "volumetric" enables those reflections - which I purposefully disabled for landing and taxi lights (but enabled for strobes). With the dim default lights, it's not too much of a problem, but the brighter lights also make the lighting "cone" a lot more visible when outside of clouds - and it looks like fog (see images below). If you want you can enable it for any light - go into the .fx file, look for "volumetric=0" and change it to "volumetric=1".

Volumetric landing lights enabled, external and internal view
<br>
![Volumetric1](https://github.com/Uwajimaya/FS2020/raw/gh-pages/images/Volumetric1.jpg)
![Volumetric2](https://github.com/Uwajimaya/FS2020/raw/gh-pages/images/Volumetric2.jpg)


<div id="disqus_thread"></div>
<script>

/**
*  RECOMMENDED CONFIGURATION VARIABLES: EDIT AND UNCOMMENT THE SECTION BELOW TO INSERT DYNAMIC VALUES FROM YOUR PLATFORM OR CMS.
*  LEARN WHY DEFINING THESE VARIABLES IS IMPORTANT: https://disqus.com/admin/universalcode/#configuration-variables*/
/*
var disqus_config = function () {
this.page.url = PAGE_URL;  // Replace PAGE_URL with your page's canonical URL variable
this.page.identifier = '1234567'; // Replace PAGE_IDENTIFIER with your page's unique identifier variable
};
*/
(function() { // DON'T EDIT BELOW THIS LINE
var d = document, s = d.createElement('script');
s.src = 'https://https-uwa-lights.disqus.com/embed.js';
s.setAttribute('data-timestamp', +new Date());
(d.head || d.body).appendChild(s);
})();
</script>
<noscript>Please enable JavaScript to view the <a href="https://disqus.com/?ref_noscript">comments powered by Disqus.</a></noscript>
