This project contains more than 1,000 CSS3-based graphics code samples (think "swatches") with linear gradients, radial gradients, box-shadows, transforms, reflections, 2D/3D effects, and 2D/3D animation.  Surprisingly, these code samples create visual effects that require only rudimentary features of CSS in conjunction with CSS3-specific features.

Incidentally, in case you're wondering why the eff there are so many code samples, creating graphics is what I enjoy doing during some of my spare time, yet I understand that this free stuff could be both vacuous and an egregious waste of time for serious designers and developers (et alors, c'est vraiment tant pis pour toi).  Alas, these code samples will not help anyone get a pay raise, obtain a better job, or find a smokin' hot paramour (you wish).

Further disclaimer: these code samples are primarily for entertainment and utterly lacking vis-a-vis a meaningful higher purpose in life, possibly devoid of any intrinsic value beyond a fleetingly ephemeral and momentary distraction of the senses. In fact, watching too many code samples at one time can lead to temporary mental paralysis, so take frequent breaks to relax (I recommend chilled Chardonnay).

What you'll get: code samples for rendering various 2D shapes, including rectangles, circles, triangular shapes, ellipses, oval arcs, checkerboard patterns, and diagonal lines, combined with linear and radial gradients to create unusual visual effects (sort of like Matisse-meets-Warhol-meets-Jefferson-Airplane in the 21st century).  The code samples attempt to explore the capabilities and limitations of CSS3, and I hope that the inclusion of a **massive** number of code samples will increase the likelihood that you'll find something that appeals to you.

The code samples were tested successfully in Chrome on Windows Vista and Chrome (version 17) on a Macbook; however, the code for browser-specific extensions for Mozilla, Opera, Firefox, and IE is not included.   Interestingly, some code samples render differently (and better) on Chrome/Windows Vista and on Chrome/Linux than on Chrome/Macbook.  In addition, some of the long-running code samples (four minutes for those that have 240 embedded in the filenames) are very CPU-intensive, so it's better to view them on a laptop instead of a tablet or a smart phone, lest you drain your battery.

Various randomly selected code samples were tested on a Nook Color with Android 3.0, and the results were mixed: the static samples rendered correctly, and the effects look like Chrome/Vista instead of Chrome on Macbook; the 2D animation samples rendered the text animation but not the graphics effects; the 3D text and graphics animation effects rendered correctly.  However, intensive 3D graphics effects are agonizingly slow on a Nook (clearly there is no hardware acceleration).

Among the tablets tested thusfar, iOS devices are the best in terms of both performance and visual quality, based on a randomly selected set of code samples.  Another interesting point: in some Canvas-based graphics samples, an iPod Touch outperforms the Nook Color in terms of rendering speed of the graphics.

A randomly selected set of CSS3 2D/3D samples that are part of HTML5 hybrid Android applications (as well as PhoneGap-based apps) render very nicely on both an Asus Prime 10" tablet with Android ICS and on an iPad3, as well as "pure" SVG code and CSS3/SVG combinations.  The only SVG feature that does not work on Android ICS is SVG filters (perhaps Android 5 supports SVG filters, which AFAIK will soon be the same as CSS filters), which will also be tested on an iPad3.

As you'll soon see, there are **many** **many** similar samples that are often propagated across multiple download files, which might help you find the subset of code samples that are of interest to you.  As you might also surmise, these code samples do not represent production-quality code, nor do they reflect any best practices, so code refactoring would be a good idea. Future code samples will probably contain examples of CSS3/SVG graphics.

A jQuery+CSS3 code project with code samples that can achieve the same visual effects as their counterparts in D3, SVG, and HTML5 Canvas:
```
https://code.google.com/p/jquery-css3-graphics/
```

Meanwhile, as you slog through the mind-numbing array of code samples, I offer you this encouragement: even if 95% of the code samples are irrelevant for your needs, you'll still have roughly 100 useful samples.  Once you've found the samples that really resonate in a meaningful way, you can get guidance from one of the immensely talented CSS3 experts in Silicon Valley to help you optimize the code (and who knows, they might even help you for free).

The recommended order for viewing the code samples:
```
css3-samples.zip
css3-graphics-reflect.zip
css3-graphics-reflect-animation.zip
css3-graphics-animation2D.zip
css3-graphics-animation3DUpdated.zip
css3-graphics-ovals-animation3D.zip
css3-graphics-ovals-arcs-animation3D.zip
css3-graphics-ovals-arcs2-animation3D.zip
```
Note that the CSS3 code samples in css3-graphics-animation3D.zip have been superseded by the code samples contained in css3-graphics-animation3DUpdated.zip.

There are some cases where an HTML file does not specify the correct corresponding CSS stylesheet, and sometimes the HTML is not well-formed (propagated because of my haste as I wrote the code samples), but in each of those cases, you can easily make the necessary corrections.

Recently I managed to combine some of these code samples with CSS Shaders, which I believe will be a fabulous addition to the power of CSS3, thereby imbuing CSS3 with some of the capabilities of WebGL. However, Adobe changed the APIs so these code samples only work with the browser that is specified in this project:
```
https://code.google.com/p/css-shaders-graphics/
```

Note that the 3D animation effects in the samples whose filename contains either the number "120" or "240" often "disappear" for a prolonged period of time (eh bien, it's sort of a nod to John Cage's 4'33"); if you find this excessive, tweak the code by reducing the duration of the animation effect and/or change the CSS3 code.

I'll also be presenting a CSS3 session at SVCC 2012/2013 and OWC 2012/2013:
```
http://www.siliconvalley-codecamp.com/
```
Finally, two books with various examples of combining HTML5 Canvas, CSS3, and SVG:
```
http://www.amazon.com/HTML5-Canvas-CSS3-Graphics-Primer/dp/1936420341
http://www.amazon.com/jQuery-HTML5-Mobile-Desktop-Devices/dp/1938549031
```
Incidentally, here are a few songs that I enjoyed while experimenting with CSS3 graphics:
```
http://www.youtube.com/watch?v=5r8G3SEGIV0
https://www.youtube.com/watch?v=oBhj-Tv4WHI
http://www.youtube.com/watch?v=kZ7hNdC5Hi0
https://www.youtube.com/watch?v=C-dvTjK_07c&feature=related
https://www.youtube.com/watch?v=BqfIvPQ8Dgo
https://www.youtube.com/watch?v=qnFYjrfWX3M
https://www.youtube.com/watch?v=k4VFFBCa5Aw
https://www.youtube.com/watch?v=BCP9NuvYw5M&feature=related
https://www.youtube.com/watch?v=jl1mQASHc48
https://www.youtube.com/watch?v=f9lkxq7tGuY&feature=related
http://www.metacafe.com/watch/sy-219479220/outkast_the_way_you_move_official_music_video/
https://www.youtube.com/watch?v=su_vabpqvvQ
http://www.youtube.com/watch?v=xwhBRJStz7w
```

Enjoy!