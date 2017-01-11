FEG Snippets - Sublime Plugin
==================

A sublime plugin complete with FEG snippets

Feel free to let me know what else you want added via:

- FEG [Blog](http://feg.netease.com/)
- [Issues](https://github.com/w3cmark/feg-sublime-snippets/issues)

##What's included - contents
- [Html](#html)
- [Less](#less)
- [Javascript](#javascript)
- [License](#license)

### Installation

There are 3 methods for installing this plugin.

1. Search for "FEG Snippets" via the "Package Control: Install Packages" menu.
**Note:** If you don't have Sublime Package Control installed, you can find out how to install it here [https://sublime.wbond.net/installation](https://sublime.wbond.net/installation)

2. Clone the repository into your Sublime Text 2/3 packages directory.
`git clone https://github.com/w3cmark/feg-sublime-snippets.git

3. Download the .zip file and unzip it into your Sublime Text 2/3 packages directory.
**Note:** You can find your Sublime Text 2/3 packages directory by going to Preferences > Browse Packages.

### Usage

Start typing `feg` in html files and the autocomplete window opens. It matches fuzzily. So you can type `feg-html5` to find the `html5` snippet.

Be sure you have enabled "<" and "feg" in your Preferences.sublime-settings:

`"auto_complete_triggers": [{"selector": "text.html", "characters": "<"},{"selector": "text.html", "characters": "feg"},{"selector": "source.less", "characters": "feg"},{"selector": "source.js", "characters": "feg"}]`

### Html

| Component                               | Snippet code                   |
|---------------------------------------- | :-----------------------------:|
| mobile template:html5                   | feg-html5-m                    |
| pc template:html5                       | feg-html5-pc                   |
| nie-download-plugin code                | feg-niedownload                |
| include code                            | feg-include                    |
| inline code                             | feg-inline                     |
| alertbox-plugin link (CSS only)         | feg-alertbox                   |
| baidutemplate-plugin link (JS only)     | feg-baidutemplate              |
| jquery.easing-plugin link (JS only)     | feg-easing                     |
| jquery.form-plugin link (JS only)       | feg-form                       |
| jquery.fullpage-plugin link (JS only)   | feg-fullpage                   |
| lightbox2-plugin link (JS only)         | feg-lightbox2                  |
| masonry-plugin link (JS only)           | feg-masonry                    |
| moment-plugin link (JS only)            | feg-moment                     |
| mustache-plugin link (JS only)          | feg-mustache                   |
| jquery.nicescroll.3.6.8-plugin link (JS only)| feg-nicescroll.3.6.8      |
| jquery.nicescroll-plugin link (JS only) | feg-nicescroll                 |
| jquery.parallax-plugin link (JS only)   | feg-parallax                   |
| jquery.scrollorama-plugin link (JS only)| feg-scrollorama                |
| skrollr-plugin link (JS only)           | feg-skrollr                    |
| jquery.superslide-plugin link (JS only) | feg-superslide                 |
| swiper-plugin link (JS only)            | feg-swiper                     |
| swiper.2.7.0-plugin link (JS only)      | feg-swiper.2.7.0               |
| GreenSock-timelinemax-plugin link (JS only) | feg-timelinemax            |
| GreenSock-timelinelite-plugin link (JS only)| feg-timelinelite           |
| GreenSock-tweenlite-plugin link (JS only)| feg-tweenlite                 |
| GreenSock-tweenmax-plugin link (JS only) | feg-tweenmax                  |
| GreenSock-xss-plugin link (JS only)      | feg-xss                       |


### Less

| Component                               | Snippet code                   |
|---------------------------------------- | :-----------------------------:|
| mobile reset                            | feg-reset-m                    |
| pc reset                                | feg-reset-pc                   |
| mobile art-reset                        | feg-art-reset-m                |
| pc art-reset                            | feg-art-reset-pc               |
| animation                               | feg-animation                  |
| background-rgba                         | feg-background-rgba            |
| box-shadow                              | feg-box-shadow                 |
| gradient                                | feg-gradient                   |
| gradient-opacity                        | feg-gradient-opacity           |
| inline-block                            | feg-inline-block               |
| keyframes                               | feg-keyframes                  |
| opacity                                 | feg-opacity                    |
| text-overflow-ellipsis                  | feg-text-overflow-ellipsis     |
| transform                               | feg-transform                  |
| transition                              | feg-transition                 |
| animation libs                          | feg-animation-lib              |

### Javascript

| Component                               | Snippet code                   |
|---------------------------------------- | :-----------------------------:|
| audio plugin                            | feg-audio                      |
| bjTime plugin                           | feg-bjTime                     |
| comment plugin                          | feg-comment                    |
| copytext plugin                         | feg-copytext                   |
| define template                         | feg-define                     |
| flash-cc plugin                         | feg-flash-cc                   |
| flash plugin                            | feg-flash                      |
| formcheck plugin                        | feg-formcheck                  |
| fur3 plugin                             | feg-fur3                       |
| galleryV2 plugin                        | feg-galleryV2                  |
| imageshow plugin                        | feg-imageshow                  |
| niedownload plugin                      | feg-niedownload                |
| pager plugin                            | feg-pager                      |
| PopDialog plugin                        | feg-popdialog                  |
| shareV5 plugin                          | feg-share                      |
| mobishare2 plugin                       | feg-mobishare2                 |
| videoV2 plugin                          | feg-videoV2                    |
| login2 plugin                           | feg-login2                     |
| interface module:DB                     | feg-db                         |


### License

FEG Snippets - Sublime Plugin is open-sourced software licensed under the [MIT license](http://opensource.org/licenses/MIT).