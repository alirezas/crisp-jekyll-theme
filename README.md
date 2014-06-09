# Crisp 

A minimalist, responsive, and open-source theme originally for [Ghost](http://ghost.org) by [Kathy Qian](http://kathyqian.com) that ported to [Jekyll](http://jekyllrb.com/) by [Alireza Sarabchi](https://github.com/alirezas). You can [view it live here](http://kathyqian.com).

![Index](https://raw.github.com/kathyqian/crisp-ghost-theme/master/index.png)   

### Required Steps for Installation

1. Download the files
2. Manually add/remove all links to static pages by copying (or deleting) the code in **crisp/\_includes/navigation.html**    
3. Replace the `example` disqus_shortname with your shortname on *line 17* of **crisp/\_layouts/post.html**, or change the **comments** to `false` in **crips/\_config.yml**
4. Configure the follow buttons in **crisp/\_includes/follow.html** (see section below)

### Suggested Customizations

* Change the link color on *line 86* in **crisp/assets/styles/crisp.css**
* Add code for Google Analytics in **crisp/\_layouts/default.html** after `footer`
* Remove irrelevant social sharing services in **crisp/\_includes/share.html**

### Editing Follow Buttons

Crisp uses Font Awesome for icons. See the Font Awesome documentation for the [full list of icons](http://fortawesome.github.io/Font-Awesome/icons/) and [usage tips](http://fortawesome.github.io/Font-Awesome/examples/). 

I have placed some common buttons in **follow.html**, with more options in the commented out sections. Make sure to replace the `username` in the URLs so the links point to your profiles. 

### Features, Changelog, and Technical Notes

To see changelog visit [crisp-ghost-theme](https://github.com/kathyqian/crisp-ghost-theme)

### Credits

Many thanks to [@davegandy](http://twitter.com/davegandy) for the [Font Awesome](https://github.com/FortAwesome/Font-Awesome) icons used throughout the theme.

Social sharing buttons are a modified version of the [Ridiculously Responsive Social Sharing Buttons](https://github.com/kni-labs/rrssb) by [@dbox](http://www.twitter.com/dbox) and [@seagoat](http://www.twitter.com/seagoat). Great job, guys!

### More Screenshots

![Post](https://raw.github.com/kathyqian/crisp-ghost-theme/master/post.png)
![Post w/Image](https://raw.github.com/kathyqian/crisp-ghost-theme/master/post-2.png)
![Post w/Long Text](https://raw.github.com/kathyqian/crisp-ghost-theme/master/post-3.png)
