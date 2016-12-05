Victorias_site_notes

Here are the notes to find my way around the implementation of the feeling-responsive Jekyll theme for Victoria's yoga site. Combined with the Google doc, I should have enough details to maintain this site.

Start with opening jekyll_victoriaheron.com/_config_dev.yml and take note of the following from the config:

# This config-file is only needed for development. Instead of changing the url
# everytime you work locally on the project, you start both config-files, overwriting
# the first one with the development variables needed.
#
# Start development with: $ jekyll serve --config _config.yml,_config_dev.yml --incremental

Publish to repo mapping

/ (root) => _layouts/frontpage.html
	image 
	intro text from  
/about => pages/about-me.md

/classes => pages/classes.md

/classes/corporate-classes => _posts/classes/2016-10-02-corporate-classes.md

/classes/private-classes => _posts/classes/2016-10-02-corporate-classes.md

/media - 404
/media/archive - 404
/blog => (builds from /blog/index and /_layouts/blog.htmlblog)
/blog/archive
/contact
	needs wufoo form


[![Flattr this git repo](http://api.flattr.com/button/flattr-badge-large.png)](https://flattr.com/submit/auto?user_id=Phlow&url=https://github.com/Phlow/feeling-responsive&title=Support%20Feeling%20Responsive%20Jekyll%20Theme&language=en_GB&tags=github,jekyll,theme,webdesign&category=software)


# Newsletter: Stay in Touch for Future Updates

If you are a webdesigner interested in Jekyll, the static website generator, this little newsletter is for you. I share tutorials, clever code snippets and information about my own Jekyll Themes called [*Feeling Responsive*][7] and [*Simplicity*][8]. Please don't expect weekly emails :)

[![Subscribe to Jekyll Newsletter](https://phlow.github.io/static/tinyletter_subscribe_button.png)](https://tinyletter.com/feeling-responsive)


[![Start Video](https://github.com/Phlow/feeling-responsive/blob/gh-pages/images/video-feeling-responsive-1280x720.jpg)](https://www.youtube.com/embed/3b5zCFSmVvU)

## A Responsive Jekyll Theme: *Feeling Responsive*

Do you want to get to know *Feeling Responsive*? Than check it out first and have a look on its home at  <http://phlow.github.io/feeling-responsive/>.

To get to know *Feeling Responsive* check out all the features explained in the [documentation][1].

And what license is *Feeling Responsive* released under? [This one][2].



## Why use this theme?

Feeling Responsive is heavily customizable.

1. Language-Support :)
2. Optimized for speed and it's responsive.
3. Built on Foundation Framework.
4. Six different Headers.
5. Customizable navigation, footer,...

**[More ›][3]**



## Changelog

*Feeling Responsive* is in active development. Thank you to everyone who contributed, especially [Róbert Papp][5], [Alexandra von Criegern](https://github.com/plutonik-a) and [Juan Jose Amor Iglesias](https://github.com/jjamor).

**[Read Changelog ›][6]**



## Video Tutorial

Click the image to [watch the YouTube-Video-Tutorial][4].

[![Start Video](https://github.com/Phlow/feeling-responsive/blob/gh-pages/images/video-feeling-responsive-tutorial-frontpage.jpg)](https://www.youtube.com/watch?v=rLS-BEvlEyY)








 [1]: http://phlow.github.io/feeling-responsive/documentation/
 [2]: https://github.com/Phlow/feeling-responsive/blob/gh-pages/LICENSE
 [3]: http://phlow.github.io/feeling-responsive/info/
 [4]: https://www.youtube.com/watch?v=rLS-BEvlEyY
 [5]: https://github.com/TWiStErRob
 [6]: https://phlow.github.io/feeling-responsive/changelog/
 [7]: http://phlow.github.io/feeling-responsive/
 [8]: http://phlow.github.io/simplicity/
 [9]: #
 [10]: #
